# Callow 2

Ovo je prilagođena verzija Callow brute-force skripte, koja omogućuje napade na login stranice koje imaju samo polje za unos lozinke.

Bilo je problema pri pokretanju chromedriver-a, iako je bio dodat u "path"
Povezana stranica na stackowerflow:

[https://stackoverflow.com/questions/29858752/error-message-chromedriver-executable-needs-to-be-available-in-the-path](https://stackoverflow.com/questions/29858752/error-message-chromedriver-executable-needs-to-be-available-in-the-path)

Primenjena je izmena sa navedene strnice.

Ova stranica je sačuvana i u html-u za slučaj da stranica na stackoverflow u nekom trenutku postane nedostupna: [chromedriver-fix.html](./chromedriver-fix.html)

više detalja o instalaciji i upotrebi može se naći u originalnom [README fajlu](./readme-original.md)

U slučaju da polje za lozinku nema css selektor, kao naziv selektora može se staviti asterisk `*`

Takođe je potrebno preuzeti i odgovarajuću listu, odnosno rečnik, često korišćenih lozinki, pošto sama skripta nema ugrađenu arhivu.

Lista koja se nalazi u ovom repozitorijumu je preuzeta sa sledeće stranice:
[https://github.com/scipag/password-list/blob/main/overall/password-list-all.txt](https://github.com/scipag/password-list/blob/main/overall/password-list-all.txt)
i nalazi se u fajlu [password-list-all.txt](password-list-all.txt)