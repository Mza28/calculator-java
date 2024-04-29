Izračunao sam sledece stvari:
LOC za kompletan pojekat
Ciklomatska i kognitivna složenost metoda evaluateExpression i Calculate
 *koristio sam sonar lint kako bi uradeo analizu i sve*
LOC ima ukupno 214 linija koda za kompletan projekat
 za evaluateExpression ciklomatska složenost 12
za Calculate je ciklomatska složenost 12 
drugi zadatak je bio da uradim neformalan pregled koda i njegovu statičku analizu bez pokretanje koda u:

fajl – broj linije koda – zapažanje
pa onda za start.java je:

 LOC 1  fajl nije dodeljen u pravi paket.
 LOC 6  metoda Expression treba da se promeni u expression.
 LOC "8"  Sintaksna greška.
 LOC "19" Sintaksna greška.
i pronasao sam u Start.java 4 nedoslednosti
pa onda za calculater.java:
LOC 1 fajl nije dodeljen u pravi paket.
LOC 4 klasa Calculator treba da bude privatna a ne javna.
LOC 18 preimenovati metodu ToString da ne bi dolazilo do mešanja sa superklasom toString. i na ovoj liniji koda je pronađeno dva CODE SMELL
LOC 24 preimenovati metodu 
LOC 70 Sintaksna greška 
LOC 74 preimenovati metodu
LOC 183 višak komande
u calculator.java sam pronasao ukupno 8 nedoslednosti 

hvala na saradnju!
