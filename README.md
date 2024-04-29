Izračunao sam sledece stvari:
LOC za kompletan pojekat
Ciklomatska i kognitivna složenost metoda evaluateExpression i Calculate 
LOC ima ukupno 214 linija koda za kompletan projekat
 za startje  a za 12 za Calculate je ciklomatska složenost 12 
 a za drugi zadatak je bio da uradim neformalan pregled koda i njegovu statičku analizu bez pokretanje koda u:

fajl – broj linije koda – zapažanje
pa onda za start.java je:

Start.java LOC 1  fajl nije dodeljen u pravi paket.
Start.java LOC 6  metoda Expression treba da se promeni u expression. 
Start.java LOC 8  Sintaksna greška.
Start.java LOC 19 Sintaksna greška.
i pronasao sam u Start.java 4 nedoslednosti
pa onda za calculater.java je:
Calculator.java LOC 1 fajl nije dodeljen u pravi paket.
Calculator.java LOC 4 klasa Calculator treba da bude privatna a ne javna.
Calculator.java LOC 18 preimenovati metodu ToString da ne bi dolazilo do mešanja sa superklasom toString. i na ovoj liniji koda je pronađeno dva CODE SMELL
Calculator.java LOC 24 preimenovati metodu 
Calculator.java LOC 70 Sintaksna greška 
Calculator.java LOC 74 preimenovati metodu
Calculator.java LOC 183 višak komande
Calculater.java LOC 18 preimenovati metoda
u calculator.java sam pronasao ukupno 8 nedoslednosti 

