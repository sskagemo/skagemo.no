 

---

title: F?rste blogginnlegg automatisk fra reMarkable

date: 2023-03-23T11:50

draft: true

tags: [remarkable, koding]

slug: foerste blogginnlegg automatisk fra remarkable

---

Hvis du kan lese dette s? har jeg lyktes i ? f? til f?lgende:

1. Skrive et innlegg p? min reMarkable (med tastaturet Type Folio)

2. Sende teksten som epost til en egen epostadresse

3. Automatisk tagge eposten som et nytt innlegg

4. F? Google Apps Script til ? oppdage det nye innlegget og "commite" det 
til riktig sted p? Github slik at det dukker opp p? bloggen

(samt et ?rlite manuelt kvalitetssikringssteg inni der som jeg kan gj?re 
fra mobiltelefonen)

En liten fun-fact er at jeg trengte litt kode for ? lage et filnavn basert 
p? innholdet i teksten. Ikke veldig avansert, men likevel noe som krevde 
noen f? linjer JavaScript-kode (Google Apps Script bruker JavaScript). Jeg 
regnet med at jeg ville klare ? finne det ut siden jeg kjenner til hvordan 
man gj?r det med Python, men s?nt tar alltid litt tid og mye pr?ving og 
feiling.

Da slo det meg at det finnes en venn for slike anledninger; OpenAIs 
ChatGPT. S? jeg skrev koden i Python og testet at den gjorde det jeg ville, 
og s? ba jeg bare om ? f? den samme koden som JavaScript. Det fungerte 
feilfritt p? f?rste fors?k :-)

Enda en grunn til ? l?re Python; du kan f? hjelp av ChatGPT til ? skrive 
det om til JavaScript, og kanskje andre programmeringsspr?k ogs?, hvis du 
trenger det senere. (Vel, det samme argumentet kan sikkert brukes andre 
veien ogs?, men det overser jeg akkurat n? ...)

