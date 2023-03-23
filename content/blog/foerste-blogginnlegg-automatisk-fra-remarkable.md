 

---

title: Første blogginnlegg automatisk fra reMarkable

date: 2023-03-23T11:50

draft: false

tags: [remarkable, koding]

slug: foerste blogginnlegg automatisk fra remarkable

---

Hvis du kan lese dette så har jeg lyktes i å få til følgende:

1. Skrive et innlegg på min reMarkable (med tastaturet Type Folio)

2. Sende teksten som epost til en egen epostadresse

3. Automatisk tagge eposten som et nytt innlegg

4. Få Google Apps Script til å oppdage det nye innlegget og "commite" det 
til riktig sted på Github slik at det dukker opp på bloggen

(samt et ørlite manuelt kvalitetssikringssteg inni der som jeg kan gjøre 
fra mobiltelefonen)

En liten fun-fact er at jeg trengte litt kode for å lage et filnavn basert 
på innholdet i teksten. Ikke veldig avansert, men likevel noe som krevde 
noen få linjer JavaScript-kode (Google Apps Script bruker JavaScript). Jeg 
regnet med at jeg ville klare å finne det ut siden jeg kjenner til hvordan 
man gjør det med Python, men sånt tar alltid litt tid og mye prøving og 
feiling.

Da slo det meg at det finnes en venn for slike anledninger; OpenAIs 
ChatGPT. Så jeg skrev koden i Python og testet at den gjorde det jeg ville, 
og så ba jeg bare om å få den samme koden som JavaScript. Det fungerte 
feilfritt på første forsøk :-)

Enda en grunn til å lære Python; du kan få hjelp av ChatGPT til å skrive 
det om til JavaScript, og kanskje andre programmeringsspråk også, hvis du 
trenger det senere. (Vel, det samme argumentet kan sikkert brukes andre 
veien også, men det overser jeg akkurat nå ...)

