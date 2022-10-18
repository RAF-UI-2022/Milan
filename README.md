# Milan Došlić RN35-20
Objekat:
- Povezan sa tipom člana objekat mora da ima 1 tip člana, tip člana 0...* objekata

Komentar:
- mora da bude vezan za 1 objekat, objekat moze da ima 0...* komentara

Poseta:
razreseneje many to many objekat-clan( jake veze i sa jednim i drugim)

Tip Objekta:
- Bazen, Teretana, Teniski teren itd. 

Lokacija:
- vise korisnika na jednoj lokaciji jedna lokacija po korisniku( povezano i sa aktivnim i neaktivnim), isto i za objekat

Firma:
- Zemlja osnivanja kako bih kasnije uveo mozda neki porez na poslovanje s njima ili slicno

Beneficija:
Razrešenje many to many veze između saradnika i tipa člana

Cenovnik:
- povezan sa tipom člana jedan prema više
- mogu i da ga povežem i sa lokacijom i to jakom vezom tako da nasledi primarni ključ od lokacije kako bih brže pretraživao cene po državi/gradu
