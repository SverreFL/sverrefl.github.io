---
title: Prosjekter
---
### Prosjekter
#### Webapplikasjoner
Jeg har laget to webapplikasjoner som visualiserer [data](https://bergenbysykkel.no/apne-data/historisk) fra i overkant av én million reiser med Bergen Bysykkel i 2020. Begge appene tar utgangspunkt i et interaktivt kart fra [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/). Den éne appen er laget med [Panel](https://panel.holoviz.org/) som er et veldig fleksibelt verktøy for å lage interaktive dashboard i Python. Den andre appen er laget med [Voilà](https://voila.readthedocs.io/en/stable/using.html) som i praksis konverter en [jupyter notebook](https://jupyter.org/) til en applikasjon. Jeg også laget en pedagogisk webappplikasjon om hypotesetesting. Merk at de kan bruk litt tid på å laste inn.
- [Applikasjon i Panel](https://bysykkel-panel.herokuapp.com) som for hver stasjon viser gjennomsnitllig antall reiser til og fra for hver time av dagen.
- [Applikasjon i Voilà](https://bysykkel-voila.herokuapp.com) som for hver stasjon viser antall reiser og gjennomsnittlig reisetid til alle de andre stasjonene.
- [Applikasjon i Panel](https://hypotesetest.herokuapp.com) som interkativt viser hvilke faktorer som påvirker styrken til en hypotesetest om gjennomsnittet i en normalfordeling med kjent varians. 

#### Interaktive visualiseringer i Altair
Jeg har også laget noen interaktive figurer med data fra [Bildeleringen](https://bildeleringen.no/). Dette er bare html-filer, så i motsetning til applikasjonene over trenger de ikke en aktiv python-kernel; all interaktiviteten blir håndtert av nettleseren lokalt. 
- [Tidseriedata](figures/tidsserie.html) med antall reiser per dag.
- [Sammensatt figur](figures/mars.html) som viser antall reiser med de ulike biltypene, samt medianen av kjørelengde og reisetid. Data er fra Mars 2021. 

