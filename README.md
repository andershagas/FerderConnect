# FerderConnect
 
![FerderConnect](https://github.com/andershagas/FerderConnect/assets/42244235/05d1b23c-ef4c-4983-a27c-3a6e367476bf)


Hva er FerderConnect?
=============

Etter at alt av logistikk oppsettet var ferdig dagen før, så måtte vi sende ut informasjon til alle sjåførene.

Måten de gjorde dette på når jeg startet bedriften, var veldig baklengs. Du må sende MMS til hver eneste sjåfør på hver eneste bil og minibus.
Det er flere biler og minibuser som endrer sjåfør ofte, og da blir det veldig vanskelig.

Jeg valgte da og lage både en app, og ett .NET basert program. Appen er for sjåførene, og programmet er for sentralen å bruke.

Etter at alt ble laget, lagde jeg enda flere funksjoner ved appen, som å sende ut live-meldinger og la sjåførene svare på dette
i app. Jeg lagde også en måte for å laste inn et Excel dokument som var det sjefen brukte for å lage "vaktliste" på bilene.
Når vaktlista ble lastet opp, hentet baksystemet ut alle biler som er brukt på vaktlista, eksporterer en versjon av den vaktlista hvor en og en bil er merka, og dette ble da sendt til sjåføren automatisk.

![image](https://github.com/andershagas/FerderConnect/assets/42244235/860fe911-f3ee-423f-9217-ff87546de373)

![image](https://github.com/andershagas/FerderConnect/assets/42244235/216f02a2-b678-45cf-acc4-b134fcd146d8)

![image](https://github.com/andershagas/FerderConnect/assets/42244235/bb48ca36-dca8-487b-b77f-d88bdbec91cc)

Det som bestemmer hvem som kjører hva er sentralen. Sentralen gir tilgang til løyver for en sjåfør,
hvor da den sjåføren får alle oppdateringer som er tilknyttet den løyva.

![image](https://github.com/andershagas/FerderConnect/assets/42244235/abb1899d-a493-4b24-80c4-1adc0b6c8b41)

Du kan også lett se hvem som har sett sist oppdatering.

![image](https://github.com/andershagas/FerderConnect/assets/42244235/ee2821ca-4323-4601-aa01-8cb82767b47e)
![image](https://github.com/andershagas/FerderConnect/assets/42244235/4f5455ca-331d-4b8c-afe9-52578c10238c)

![image](https://github.com/andershagas/FerderConnect/assets/42244235/8c0337fe-c688-47d9-98bb-320e86421e1a)
![image](https://github.com/andershagas/FerderConnect/assets/42244235/6dbc3ff2-dc9c-4985-b08e-2182f7496605)


Prosjekt Oppsett
-------------

Programmet er skrevet i C# hvor jeg bryker costura fra Fody for å sette alle filer internt, samt MySql.Data for sql.

Databasen er en jeg hoster på egen server. 

Dessverre så ble ikke dette veldig iverdsatt utenom ett "Å det var kult" type opplegg, og jeg ville ikke dekke kostnader for server. (Det var veldig liten kostnad uansett men var ikke interesert.)

