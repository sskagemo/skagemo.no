---
title: Innlegg med kodeeksempler
draft: false
date: 2023-02-13T09:50:00+01:00
Tags: [kode]
---
En av grunnene til at jeg ønsker å få igang en nettside, er at jeg ofte får lyst til å dele ting jeg har lært om Python. Ikke minst for å øke sjansen for å huske det selv ... Da er det nyttig å på en enkel måte dele kodeeksempler, for eksempel sånn som dette:

```python
url = (
    "saft.xml"
)
saft = saft2dataframe(open_url(url)) # leser en SAF-T Financial fil

saft.loc[
(    # filtrerer de relevante transaksjonene (tid og kontoer):
    saft['Transaction.TransactionDate'] >= '2017-01-01')     
    & (saft['Transaction.TransactionDate'] < '2017-02-01')   
    & (saft['Line.AccountID'] >= 3000)          
    & (saft['Line.AccountID'] < 4000)] \
    [[  # summerer de relevante beløpene for rapportering til SSB:
    'Line.DebitAmount.Amount',  
    'Line.TaxAmount.Amount',
    'Line.CreditAmount.Amount',]].sum()
```

Eksempelet over er hentet fra en nettside som [demonstrerer hvordan python nå kan kjøre direkte i nettleseren](https://nordicsmartgovernment.github.io/saf-t_analyse_pwa/), og bruker python og pandas
til å lese og analysere en SAF-T fil med bokføringsdata.

Dette kan for eksempel være nyttig hvis
SSB vil gjøre det lettere for bedrifter å rapportere. Mange av deres rapporter ber om tall som kan
utledes av bokføringen, og istedenfor å gjøre den jobben (delvis) manuelt, kan en nettside som den jeg har lenket til over, ha den nødvendige koden for å lese, analysere og trekke ut de relevante tallene 
som skal rapporteres. Det er også mulig å ha kode som rapporterer tallene direkte til et API, dersom
SSB eller Altinn lager et slikt API.