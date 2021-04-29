---
title: test
--- 
### Notater
En samling av notater som (i hvert fall foreløpig) kun er ment for eget bruk. Jeg forsøker å skrive ned alt som er verdt å huske, slik at jeg slipper å faktisk huske det. Dette prosjektet ble påbegynt våren 2020 slik at det er en del etterslep, men notatene blir oppdatert fortløpende. 

#### Generelt
- [Notater](main.pdf) som begynner fra sannsynlighetsteori og bygger opp til klassisk statistisk inferens, statistisk læring og økonometri. Det er også noen kapitler om den underliggende matematikken. Innholdet er tatt fra diverse bøker og forelesninger, men de viktigste kildene er nok [Stachurski (2016)](https://johnstachurski.net/emet) og [Angrist & Pischke (2009)](https://www.mostlyharmlesseconometrics.com/). Jeg har forsøkt å frigjøre meg fra originaltekstene for å lage en helhetlig syntese, og kvaliteten på fremstillingen er deretter. Noen av kapitlene er mer fullstendige enn andre. 

#### Python
- [Python](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/python.ipynb) har oversikt over syntax, innebygde classer og andre programmeringskonsepter (namespace, moduler, mm). Har også informasjon om andre verktøy for å jobbe med filer på datamaskinen; i hovedsak git for versjonskontroll og bash som lar oss navigere og endre på filstruktur gjennom kommandolinje i stedet for gui til operativsystem. Det er i tillegg informasjon om verktøy som gir bedre workflow: vscode for .py-filer (debugging mm) og jupyter for sammensatte dokumneter med kode og tekst (egnet for eksperimentering og presentasjoner). 
- [Matplotlib](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/Matplotlib.ipynb) er en kraftig og fleksibel visualiseringspakke. Den er lite velegnet for daglig datavisualisering siden det i liten grad utnytter informasjon i dataframe. Dette gjør koden veldig verbos. På en annen side har man full kontroll. 
- [Seaborn](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/Seaborn.ipynb) gir et *high-level* grensesnitt til Matplolib som utnytter informasjon fra dataframe til å lage visualiseringer med få linjer av kode. Dette gjør det spesielt velegnet for utforskende dataanlyse. 
- [Altair](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/Altair.ipynb) har smart API som bygger på "Grammar of Graphics". Det lar oss generere json-filer med vega-lite spesifikasjon som kan bli *renderet* av d3 i javascript. Dette gjør at man enkelt kan lage interaktive figurer, der interaktiviteten blir håndtert av nettleseren. 
- [Holoviz](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/Holoviz.ipynb) er et økosystem av *libraries* som fasiliterer visualisering i nettleseren. Jeg bruker i hovedsak Panel som gjør det enkelt
å lage interaktive dashboard.
- [Pandas](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/pandas.ipynb) er et verktøy for analyse og manipulering av tabulær data.
- [Numpy og Scipy](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/numpy_og_scipy.ipynb) muliggjør vitenskaplig programmering i Python. Det grunnleggende objektetet i Numpy er ndarray som er representer en n-dimensjonal array med homogen datatype. Dette fasiliterer rask, vektorisert kode. Det har også mange funksjoner for å manipulere dette objektet. Scipy er et økosystem av verktøy for vitenskaplig programmering som bygger på numpy; det er verktøy for blant annet numerisk optimering, lineær algebra og statistikk.
- [Sympy](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/Sympy.ipynb) er et såkalt Computer Algebra System (CAS) som er skrevet utelukkende i python. Det lar oss representere uttrykk der symboler er abstrakte plassholdere istedet for å ha konkret verdi. Det gjør at vi kan manipulere uttrykkene på generell form og eventuelt substituere inn gitte verdier etter hvert. Kan blant annet løse ligningsystem og gjøre integrasjon.
- [Scikit-learn](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/sklearn.ipynb) har de fleste algoritmer for både supervised- og unsupervised learning innenfor en felles API. Det smarte designet gjør det mulig å få hele prosessen fra bearbeiding av data til modellseleksjon på noen få linjer av kode.
- [Statsmodels og Linearmodels](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/statsmodels_og_linearmodels.ipynb) har verktøy for regresjonsanalyse. Statsmodels implementerer i praksis lm og glm fra base R i python. Det har i tillegg mye funksjonalitet for tidsseriedata. Linearmodels implementerer blant annet paneldata og intstrumentelle variabler.
- [Datastrukturer og algoritmer](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/numpy_og_scipy.ipynb) har oversikt over datastrukturer samt algoritmer som kan anvendes på disse. Datastrukturene kan deles inn i lineære (har rekkefølge) og ikke-lineære (som bygger på grafer). Algoritmer er blant annet ulike måter å sortere elementene i datastrukturen eller undersøke om det inneholder et gitt element. 
#### R
- [R](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/R.ipynb) er i hovedsak en oversikt over Tidyverse. Detteer et økosystem av pakker for å manipulere data med konsistent syntax. Min workflow i R er begrenset til å laste inn et datasett, manipulere, analysere og visualisere det. Alt annet blir i Python. Har muligens bedre verktøy for statistisk modellering så det kan bli aktuelt å sette seg inn i dette. 
- [ggplot2](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/ggplot.ipynb) er visualiseringspakke som i likhet med Altair bygger på *Grammar of Graphics*. I motsetning til Altair lager den bare statiske figurer. Den regnes ofte som den beste visualiseringspakken, på tross av stygge defaults (grå bakgrunn og glorete farger). Har økosystem av tilleggspakker som forbedrer utseendet og gir ekstra verktøy. 
#### Annet
- [SQL](https://nbviewer.jupyter.org/github/SverreFL/Notater/blob/main/SQL.ipynb) er et standardspråk for å kommunisere med databasesystem for å få ut og manipulere data. 




