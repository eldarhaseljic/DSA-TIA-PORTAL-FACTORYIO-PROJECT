# DSA-TIA-PORTAL-FACTORYIO-PROJECT
Fakultet elektrotehnike Tuzla - Distribuirani sistemi automatizacije
UNIVERZITET U TUZLI

Zadatak seminarskog rada je automatizovati virtuelnu fabriku koristeći softvere TIA
Portal i Factory IO. U nastavku je dat opis problema.

Prilikom prvog pokretanja programa, učitanog na virtuelni PLC ( PLCSim ), na
signalnim tornjevima ( 1 i 2 ) su aktivni crveni indikatori koji znače da je pogon u STOP
modu. Pritiskom na taster START ( zeleni ) omogućiti pokretanje trake 1 ( duža traka ),
te u tom trenutku promijeniti stanja signalnog tornja 1 ( koji se nalazi na upravljackom
ormaru ), a promjena je iskljucivanje crvenog i ukljucivanje zelenog indikatora koji znaci
da je traka aktivna.

Diffuse senzor 1 sluzi za brojanje elemenata, te u trenutku kada vrijednost brojaca
bude veca od 5 aktivirati zuti indikator na prvom signalnom tornju sa frekvencijom
od 5 Hz. Kada vrijednost istog brojaca bude 7, iskljuciti zuti indikator i resetovati brojac.

U trenutku kada je aktivan drugi diffuse senzor ( na kraju prve trake ), aktivirati traku
broj 2. Tek kada je aktivirana traka broj 2, promijeniti stanje signalnog tornja. ( isljuciti
crveni, a ukljuciti zeleni indikator). Kada diffuse senzor na drugoj ( kracoj ) traci dosegne
vrijednost 22, zaustaviti cijeli proces. Ovo znaci da se na signalnom tornju cetiri puta
aktivira zuti indikator sa frekvencijom od 5 Hz.

Takodjer, pritiskom na STOP taster ( lijevi ), omoguciti zaustavljanje trake 1 ( duze ),
te pritiskom na STOP taster ( desni ), omoguciti zaustavljanje trake 2 ( krace ).

Svako zaustavljanje bilo koje od traka znaci i promjenu stanja na signalnim tornjevima!!!

