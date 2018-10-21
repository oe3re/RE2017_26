# RE2017_26
2048


Napraviti igricu 2048 (https://en.wikipedia.org/wiki/2048_(video_game)).
Igrica se igra na 4 × 4 mreži. Na početku igrice na mreži se popunjava
nasumično jedno polje kvadratom na kome je ispisan broj koji predstavlja stepen dvojke. Svi
stepeni dvojke imaju odgovarajuću boju polja. Pritiskom kursora na tastaturi se popunjena
polja pomeraju skroz levo, desno, gore ili dole.
Ukoliko se pomeranjem dodirnu dva polja sa istim stepenom dvojke, ona se zamenjuju
poljem čija je vrednost jednaka zbiru ova dva polja, a ukupan broj poena se inkrementira za tu
istu vrednost. U slučaju ako se desi da postoje 3 susedna polja koja imaju istu vrednost, onda
se dva koja su bliža onoj granici mreže na koju ukazuje pritisnuti kursor zamenjuju jednim
poljem sa duplo većom vrednošću.
Svaki put kada se pritisne neki od kursora na tastaturi, nakon pomeranja svih polja u smeru
tog kursora, na neko od praznih polja se nasumično generiše novi element. Vrednost na polju
se generiše nasumično i to 2 sa verovatnoćom 5/8, 4 sa verovatno¢om 2/8 i 8 sa verovatnoćom 1/8.
Igrica se završava pritiskom tastera ESC ili kada na mreži ne postoji više nijedno prazno
polje, a susedni elemenati ne mogu pomeranjem da daju jedno polje.

Više na: http://tnt.etf.bg.ac.rs/~oe3re/Projekti/Projekti_2017.pdf
