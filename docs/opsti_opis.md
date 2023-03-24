# 2. Opšti opis
## 2.1 Perspektiva proizvoda(projekta)
Sam sistem će biti kreiran u cilju bržeg i efikasnijeg odabira ciljanog događaja. S obzirom da se u zadnje vrijeme javila velika potreba za organizacijom događaja velikih razmjera pogotovo online kao što su webinar-i, javlja se ideja za razvojem softera ovakvog tipa. Ovaj sistem omogućava u bilo koje doba dana ili noći kreirate i prisustvujete željenom događaju. 

U narednom use case dijagramu, prikazan je sam koncept projekta i interakcija korisnika i organizatora samog događaja:

![Ne može se učitati](/slike/usecase.jpg "OEM Use Case")
<p style='text-align: justify;'>Ono što možemo vidjeti na datom dijagramu jeste da postoje dvije vrste aktera u ovom sistemu: gost i organizator. Gost, kao osoba koja se prijavljuje na web stranicu, ima uvid u pregled događaja koji se organizuju, odabir istih, odabir vrste plaćanja. S druge strane, imamo organizatora koji ima mogućnost da vrši kreiranje događaja, vrši promjene na kreiranim događajima, briše događaje, prima rezervacije. U pozadini, administrator, koji ima stalni nadzor nad sistemom ima mogućnosti da vodi evidenciju o gostima i organizatorima, vrši izmjene na samom sistemu.</p>

## 2.2 Funkcije proizvoda

| R.Br. | Funkcija proizvoda                                                                                          |
|-------|-------------------------------------------------------------------------------------------------------------|
| FP-1  | Sistem mora omogućiti pregled svih usluga korisniku                                                         |
| FP-2  | Sistem mora organizatoru omogućiti kreiranje događaja.                                                      |
| FP-3  | Sistem mora organizatoru omogućiti brisanje događaja.                                                       |
| FP-4  | Sistem mora obezbijediti pregled svih događaja na stranici bez obzira da li je korisnik registrovan ili ne. |
| FP-5  | Korisnik (Gost) treba imati mogućnost rezervacije karata samo ukoliko je registrovan.                       |
| FP-6  | Korisci koji su rezervisali događaj moraju biti u mogućnosti da komuniciraju sa organizatorom istog.        |
| FP-7  | Korisnik treba biti u mogućnosti da ostavi recenziju za odabrani događaj.                                   |

## 2.3 Korisničke klase i karakteristike
U sistemu će se nalaziti dvije korisničke klase: **organizator i gost**. Prilikom logina, iz baze će se povući pored ličnih podataka i nivo pristupa korisnika koji se logina i na osnovu toga će se prikazati određeni dijelovi stranice. Gosti će moći pristupiti pregledu svih događaja, rezervisati željeni događaj, a organizatori će pored toga moći pristupiti i panelu gdje će se moći dodati, izbrisati ili urediti događaj.
### 2.3.1 Klasa organizator

 ![Ne može se učitati](/slike/organizator.jpg "Organizator korisnička klasa")

Kratki opis: **Organizator pristupa sistemu, vrši izmjene, dodavanje događaja, te dodavanja korisnika u sistem, te ima mogućnost pregleda rezervacija.**

1.	Organizator vrši kreiranje događaja. 
2.	Organizator vrši izmjene na kreiranom događaja. 
3.	Organizator vrši brisanje događaja. 
4.	Organizator vrši pregled rezervacija za kreirani događaj. 5.    Organizator šalje potvrdu o rezervaciji (pristup za online event ili potvrdu o ulaznici).
5.  Organizator šalje potvrdu o rezervaciji (pristup za online event ili potvrdu o ulaznici).
