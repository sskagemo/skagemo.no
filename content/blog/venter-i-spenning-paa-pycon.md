---
title: Venter i spenning på PyCon!
date: 2023-03-08T14:00:00+01:00
draft: false
Tags: [kode, pyscript]
---
Jeg tror PyScript kan bidra til å gjøre det mye, mye enklere for mange flere å bruke Python.

Med dagens strenge begrensninger hos mange arbeidsgivere
 for hva man får lov til å gjøre, og ikke gjøre, på PC-ene på jobben, så kan det være vanskelig å få på tilgang til Python på en god måte.

Med PyScript blir Python-universet tilgjengelig i nettleseren, og det løser samtidig en annen utfordring
med å bruke Python, nemlig behovet for å sette opp et separat "miljø" med de relevante pakkene, for hvert program.
Hver PyScript-nettside kan spesifisere sitt eget miljø, og de relevante pakkene lastes ned og installeres uten
at brukeren må gjøre noe.

Det er fortsatt mye "work in progress", men det er mye som skjer. En svært spennende utvikling er at 
PyScript ser på MicroPython som et alternativ, i visse tilfeller. Det er allerede laget en "[technical preview](https://pyscript.net/tech-preview/micropython/repl.html)"
og der er siden ferdig med å laste ned og starte Python på et par sekunder.

Det gjenstår fortsatt mye arbeid for å øke farten, og samtidig tilby full integrasjon med nettleseren og øvrig nettsideteknologi. 22. april skal det være en
presentasjon på Python-konferansen PyCon US som oppsummerer det som har skjedd det siste året, og hva som er er status og veien videre for Python i nettleseren:

[PyScript and the magic of Python in the browser](https://us.pycon.org/2023/schedule/presentation/77/)

Fra beskrivelsen:

> A year after its announcement, PyScript is a very different project. From major performance improvements to great plugins, PyScript applications allow a new way to create fun and
> educational opportunities that were not possible until now. This talk summarizes the work done over the past year, and what you might expect in the future. In this talk I will:
> Give a quick overview of what PyScript is
> - Talk about features and changes introduced this year:
> - Support for the blazing fast MicroPython interpreter
> - Improved support for data
