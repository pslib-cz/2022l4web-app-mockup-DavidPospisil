# Moderní prší
Aplikace, která simuluje známou českou karetní hru Prší, akorát v moderním provedení.
## Jak bude hra vypadat
Hráč bude soupeřit v karetní hře prší proti třem protivníkům, které bude ovládat počítač. Počítači Budou rozdány náhodné karty z balíčku a bude hrát stejně jako hráč podle pravidel, které jsou vypsány níže.
## Pravidla hry
Prší může hrát 4 hráči (1 uživatel + 3 boti).

Na začátku kola jsou každému hráči rozdány 4 karty, které jsou náhodně vybrány. Uprostřed hrací plochy je jedna karta otočená lícem nahoru a zbytek karet je rubovou stranou nahoru v dobíracím balíčku (pokud hráč nemůže zahrát jakoukoliv kartu v jeho ruce).

Hráči si navzájem do karet nevidí. Hru zahajuje hráč, který je ve směru hodinových ručiček za rozdávajícím hráčem. Na lícem otočenou kartu hráč odhazuje své karty, přičemž smí odhodit jen kartu, která má buď stejnou hodnotu anebo barvu, jako vrchní lícová karta. Toto však neplatí, pokud je na vrchu speciální karta svršek. Pokud hráč nemá kartu, kterou by mohl odložit, musí si tzv. líznout, tzn. vzít kartu z rubem otočené části balíčku.
Vítěz se stává ten, kdo se první zbaví všech karet.
## Karty
Karty se kterými se Prší hraje, se nazývají Mariášové karty. Sada obsahuje 32 karet s hodnotami 7, 8, 9, 10, spodek, svršek, král, eso. Celkem jsou čtyři druhy karet, jmenují se Žaludy, Listy, Kule a Srdce.

Když hráč zahraje kartu s hodnotou 7, tak hráč, který je další na řadě, si musí vzít dvě karty navíc z dobíracího balíčku. Pokud má hráč, který je další na řadě jinou kartu s označením 7, tak jí může zahrát a další hráč, který je na řadě si musí brát 4 karty. Takto si může jeden hráč brát až osm karet z balíčku, jelikož existují pouze čtyři karty s označením 7.

Při zahrání svršku (měnič), tak hráč který kartu zahrál, si může vybrat, jaký druh karty (Žaludy, Listy, Kule a Srdce) se musí hrát jako další.

Když je zahraná karta "Eso", tak další hráč, který má být na řadě, svůj tah ztrácí.

Ostatní karty nemají žádné speciální pravidla.
## Design
Karty se pokládají na střed hrací plochy pod náhodným úhlem. Vedle oblasti pro odkládání karet je balíček pro braní si karet, když si hráč musí lízat. Každý hráč je umístěn na svoji stranu hrací plochy, přičemž hráč za kterého hraje uživatel je na spodní straně monitoru a vidí pouze líce vlastních karet. Karty ostatních hráču jsou otočeny rubem nahoru.
![Ukázka ze hry](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/52d12b18e59a7f097438393ffa0a49908c8ef54f/Uk%C3%A1zka%20ze%20hry.svg)
### Design karet
![Srdce 7](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%207.svg)
![Srdce 8](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%208.svg)
![Srdce 9](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%209.svg)
![Srdce 10](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%2010.svg)
![Srdce Spodek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Spodek.svg)
![Srdce Svršek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Svr%C5%A1ek.svg)
![Srdce Eso](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Eso.svg)
![Srdce Král](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Kr%C3%A1l.svg)
![Listy 7](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%207.svg)
![Listy 8](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%208.svg)
![Listy 9](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%209.svg)
![Listy 10](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%2010.svg)
![Listy Spodek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%20Spodek.svg)
![Listy Svršek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%20Svr%C5%A1ek.svg)
![Listy Eso](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%20Eso.svg)
![Listy Král](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Listy/Listy%20Kr%C3%A1l.svg)
![Kule 7](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%207.svg)
![Kule 8](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%208.svg)
![Kule 9](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%209.svg)
![Kule 10](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%2010.svg)
![Kule Spodek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%20Spodek.svg)
![Kule Svršek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%20Svr%C5%A1ek.svg)
![Kule Eso](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%20Eso.svg)
![Kule Král](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Kule/Kule%20kr%C3%A1l.svg)
![Žaludy 7](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%207.svg)
![Žaludy 8](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%208.svg)
![Žaludy 9](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%209.svg)
![Žaludy 10](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%2010.svg)
![Žaludy Spodek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%20Spodek.svg)
![Žaludy Svršek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%20Svr%C5%A1ek.svg)
![Žaludy Eso](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%20Eso.svg)
![Žaludy Král](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/%C5%BDaludy/%C5%BDaludy%20Kr%C3%A1l.svg)
![Záda karet](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Z%C3%A1da.svg)
### Pozadí (hrací plocha)
![pozadi](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/480a02588848fbb5e25fce827c8bbc46ac1c7d1b/Podklady/Pozad%C3%AD/Pozad%C3%AD.svg)
