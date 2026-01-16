Žao nam je zbog zakašnjenog predavanja. Nadamo se da će te i dalje uzeti naš domaći u razmatranje.

# Domaći zadatak HZS - Tim Dvor
# AFTERain

Mi smo tim **Dvor**, i odlučili smo se da pravimo mobilnu aplikaciju pod nazivom ***AFTERain***. Naša mobilna aplikacija pomaže ljudima da žive zdravije. Naša aplikacija ima više aspekata:

1) **Psihološki**

Svakog jutra, korisniku stiže motivaciona poruka kako bi imao lep početak dana
Osim toga, pozadina naše aplikacije se menja u zavisnosti od sleeping score-a kako bi motivisala korisnika da se usmeri zdravim životnim navikama. Kada je sleeping score nizak, u pozadini se nalazi kišna šuma bez biljaka, dok kada je jako visok, pozadina je sunčana i puna cveća.

2) **Fizička aktivnost**

Svakog jutra i večeri, korisnik ima listu vežbi koje treba da uradi, i u aplikaciju unosi koje vežbe je uradio.

3) **Zdravstveni**

Korisnik osim vežbi koje je radio unosi i koliko je spavao, pa se na osnovu svih podataka računa sleeping score i korisnik može da prati kako mu se sleeping score popravlja kada spava duže i radi vežbe.

## Funkcionalnosti:

- **Baza podataka**

Baza podataka:
Napravili smo bazu podataka za jedan entitet a to je san. Entitet sna kod nas ima 4 atributa (za sad) i to su:

#id_sna - jedinstveni identifikator

*datum - datum kada je bio san

*trajanje_min - trajanje sna u minutima

*jut_mask - broj vežbi odrađenih ujutru, maksimalno 6, po default-u 0

*vec_mask - broj vežbi odrađenih uveče, maksimalno 6, po default-u 0

*score - računa se na osnovu prethodnih karakteristika, povratna informacija za korisnika

Zahvaljujući bazi podataka korisnik može da prati kvalitet sna kako vreme prolazi, i može da vidi da mu je san kvalitetniji kada ispoštuje sve kriterijume.

- **Spoljašnji API**

Na početku dana, jako nam je bitno da znamo kakvo će vreme tog dana biti. Zato smo integrisali spoljašnji API koji nam prenosi temperaturu i vlažnost vazduha.

- **Veći broj stranica**

Imamo stranice za jutro, dan i veče, kao i za vreme.

- **Putanja ka svakoj stranici**

Za sada, kao test verzija postoje putanje ka svakoj stranici. U finalnoj verziji aplikacije ujutru će se otvarati jutarnja stranica sa motivacionom porukom i jutarnjim vežbama, dok će se uveče otvarati stranica za večernje vezbe i unošenje kada je korisnik legao da spava. U toku celog dana biće dostupne informacije koje nam pruža spoljašnji API, kao što su temperatura i vlažnost vazduha.

- **Aplikacija je prilagođena različitim veličinama ekrana**
