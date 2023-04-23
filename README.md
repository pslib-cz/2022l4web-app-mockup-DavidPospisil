# Moderní prší
Aplikace, která simuluje známou českou karetní hru Prší, akorát v moderním provedení.
## Jak bude hra vypadat
Hráč bude soupeřit v karetní hře prší proti třem protivníkům, které bude ovládat počítač. Počítači Budou rozdány náhodné karty z balíčku a bude hrát stejně jako hráč podle pravidel, které jsou vypsány níže.
## Pravidla hry
Prší může hrát 2-4 hráči.

Na začátku kola jsou každému hráči rozdány 4 karty, které jsou náhodně vybrány. Uprostřed hrací plochy je jedna karta otočená lícem nahoru a zbytek karet slouží jako karty lízací (pokud hráč nemůže zahrát jakoukoliv kartu v jeho ruce.

Hráči si navzájem do karet nevidí. Hru zahajuje hráč, který je ve směru hodinových ručiček za rozdávajícím hráčem. Na lícem otočenou kartu hráč odhazuje své karty, přičemž smí odhodit jen kartu, která má buď stejnou hodnotu anebo barvu, jako vrchní lícová karta. Toto však neplatí, pokud je na vrchu speciální karta svršek. Pokud hráč nemá kartu, kterou by mohl odložit, musí si tzv. líznout, tzn. vzít kartu z rubem otočené části balíčku.
Vítěz se stává ten, kdo se první zbaví všech karet.
## Karty
Karty se kterými se Prší hraje, se nazývají Mariášové karty. Sada obsahuje 32 karet s hodnotami 7, 8, 9, 10, spodek, svršek, král, eso. Celkem jsou čtyři druhy karet, jmenují se Žaludy, zelená, kule, a červené srdce.

Když hráč zahraje kartu s hodnotou 7, tak hráč, který je další na řadě, si musí vzít dvě karty navíc z balíčku. Pokud má hráš, který je další na řadě jinou kartu s označením 7, tak jí může zahrát a další hráč, který je na řadě si musí brát 4 karty. Takto si může jeden hráč brát až osm karet z balíčku, jelikož existují pouze čtyři karty s označením 7.

Při zahrání svršku (měnič), tak hráč který kartu zahrál, si může vybrat, jaký druh karty (Žaludy, zelená, kule, a červené srdce) se musí hrát jako další.

Když je zahraná karta "Eso", tak další hráč, který má být na řadě, svůj tah ztrácí.

Ostatní karty nemají žádné speciální pravidla.
## Design
Karty se pokládají na střed hrací plochy pod náhodným úhlem. Vedle oblasti pro odhládání karet je balíček pro braní si karet, když si hráč musí lízat. Každý hráč je umístěn na svoji stranu hrací plochy, přičemž hráč za kterého hraje uživatel je na spodní straně monitoru a vidí pouze líce vlastních karet. Karty ostatních hráču jsou otočeny zády nahoru.
### Design karet
![Srdce 7](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%207.svg)
![Srdce 8](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%208.svg)
![Srdce 9](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%209.svg)
![Srdce 10](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%2010.svg)
![Srdce Spodek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Spodek.svg)
![Srdce Svršek](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Svr%C5%A1ek.svg)
![Srdce Eso](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Eso.svg)
![Srdce Král](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/aa038fadbb78ba5d0e11e4e19ba95dfbf8d6d95e/Podklady/Srdce/Srdce%20Kr%C3%A1l.svg)
### Pozadí (hrací plocha)
![pozadi](https://github.com/pslib-cz/2022l4web-app-mockup-DavidPospisil/blob/2914602bb5c398e7fa4f4b4fc891201b605eab3c/Pozad%C3%AD.jpg)
