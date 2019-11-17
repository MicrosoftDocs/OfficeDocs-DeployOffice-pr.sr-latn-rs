---
title: Obavezni dijagnostički podaci za Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Administratorima sistema Office pruža informacije o obaveznim dijagnostičkim podacima u sistemu Office kao i listu događaja i polja podataka.
hideEdit: true
ms.openlocfilehash: 0437779d269d4de7132961ce2edc37363d10b309
ms.sourcegitcommit: ff396a54d8e36d71ebc4cade5014eb502952dc65
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "38639394"
---
# <a name="required-diagnostic-data-for-office"></a>Obavezni dijagnostički podaci za Office

> [!IMPORTANT]
> Informacije u ovom članku se odnose na verziju 1904 ili noviju, sledećih Office klijentskih softvera instaliranih na računaru sa operativnim sistemom Windows.
> - Office 365 ProPlus i Office 365 Business
> - Office 365 Personal, Office 365 Home ili druge verzije sistema Office koje su deo pretplate na Office 365.
> - Project i Visio koji se dobijaju uz neke planove pretplata, kao što je plan za Project Online Professional ili Visio Online Plan 2.
>
> Informacije se odnose i na verziju 16.28 ili noviju verziju sledećih Office aplikacija za Mac: Excel, Outlook, OneNote, PowerPoint i Word.

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Ti podaci ne sadrže korisničko ime ili adresu elektronske pošte, sadržaj korisničkih datoteka ili informacije o aplikacijama nevezanim za Office.

Ovi dijagnostički podaci se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi na Windows računarima. Neki dijagnostički podaci su obavezni, a neki su opcionalni. Možete da izaberete da li ćete nam slati obavezne ili opcionalne dijagnostičke podatke pomoću kontrole privatnosti, kao što su postavke smernica organizacije. Možete da vidite dijagnostičke podatke koji nam se šalju koristeći prikaz dijagnostičkih podataka.

***Obavezni dijagnostički podaci*** su minimalni podaci neophodni da bi Office bio bezbedan, ažuriran i da radi kao što se očekuje na uređaju na kome je instaliran.

Obavezni dijagnostički podaci pomažu u identifikovanju problema sa sistemom Office koji su možda povezani sa konfiguracijom uređaja ili softvera. Na primer, oni mogu da pomognu da odredite da li neka funkcija sistema Office pada češće na određenoj verziji operativnog sistema, zbog novih funkcija, ili kada su određene funkcije sistema Office onemogućene. Obavezni dijagnostički podaci pomažu nam da otkrijemo, ustanovimo i rešimo probleme brže, tako da se smanji uticaj na korisnike ili organizacije.

Za više informacija o dijagnostičkim podacima pogledajte sledeće članke:

- [Opcionalni dijagnostički podaci za Office](optional-diagnostic-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Ako ste administrator organizacije, možda će vas zanimati i sledeće:

- [Pregled kontrola privatnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti u programu Office 365 ProPlus](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Kategorije, podtipovi podataka, događaji i polja podataka za obavezne dijagnostičke podatke

Obavezni dijagnostički podaci organizovani su u kategorije i podtipove podataka. U okviru svakog podtipa podataka su događaji koji sadrže polja podataka koja su specifična za taj događaj.

Sledeća tabela sadrži listu kategorija za obavezne dijagnostičke podatke. Navedeni su podtipovi podataka u okviru svake kategorije, uz opis fokusa za taj podtip podataka. Postoje veze do svakog odeljka podtipa podataka gde ćete pronaći sledeće informacije:

- Liste događaja u tom podtipu podataka
- Opis svakog događaja
- Listu polja sa podacima u svakom događaju
- Opis svakog polja sa podacima

| **Kategorija**       | **Podtip podataka**| **Opis**    |
| ---------- | ------------- | ---- |
| **Podešavanje softvera i popis** | [Podešavanje sistema Office i popis](#office-setup-and-inventory-subtype)   | Instalirani proizvod, verzija i status instalacije.  |
| | [Konfiguracija Office programskih dodataka](#office-add-in-configuration-subtype)  | Softverski dodaci i njihova podešavanja.     |
| | [Bezbednost](#security-subtype)  | Uslovi pod kojima dolazi do greški u dokumentima, funkcijama i dodacima a koje mogu da ugroze bezbednost, uključujući spremnost proizvoda za ažuriranje.  |
| **Upotreba proizvoda i usluga**    | [Uspešnost funkcija aplikacije](#application-feature-success-subtype)   | Uspešnost funkcionalnosti aplikacije. Ograničena na otvaranje i zatvaranje aplikacije i dokumenata, uređivanje i deljenje (saradnju) datoteka. |
| | [Status aplikacije i pokretanje](#application-status-and-boot-subtype)    | Utvrđivanje da li su se određene funkcije događaja odigrale, kao što su pokretanje ili zaustavljanje i da li funkcija radi.   |
| | [Konfiguracija pristupačnosti sistema Office](#office-accessibility-configuration-subtype)  | Funkcije pristupačnosti u sistemu Office       |
| | [Privatnost](#privacy-subtype)| Postavke privatnosti za Office|
| **Performanse proizvoda i usluga**       | [Neočekivani izlaz iz aplikacije (pad)](#unexpected-application-exit-crash-subtype)  | Neočekivani izlazi (padovi) iz aplikacije i njeno stanje u trenutku kada se to dogodi.    |
|  | [Performanse funkcija aplikacije](#application-feature-performance-subtype)  | Loše vreme odziva ili performansi u scenarijima kao što su pokretanje aplikacije ili otvaranje datoteke. |
|  | [Greška u aktivnosti aplikacije](#application-activity-error-subtype)   | Greške u funkcionalnosti funkcije ili korisničkog iskustva.  |
| **Povezivanje uređaja i konfiguracija** | [Povezivanje uređaja i konfiguracija](#device-connectivity-and-configuration-subtype) | Stanje mrežne veze i podešavanje uređaja, kao što je memorija. |


> [!NOTE]
> - Kategorije su prikazane u prikazivaču dijagnostičkih podataka, ali podtipovi podataka se ne prikazuju.
> - Polje podataka koje je označeno kao *Zastarelo* je ili će uskoro biti uklonjeno iz obaveznih dijagnostičkih podataka. Neka od ovih polja podataka su duplikati koji su se pojavili u toku procesa modernizovanja dijagnostičkih podataka i koristili su se da osiguraju neometano funkcionisanje izveštaja aktivnog dijagnostičkog nadgledanja.

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a>Kategorije i polja podataka koje su zajedničke za sve događaje

Postoje određene informacije o događajima koje su zajedničke za sve događaje, bez obzira na kategoriju ili podtip podataka. Ove zajedničke informacije, koje se ponekad nazivaju *ugovori podataka*, organizovane su u kategorije. Svaka kategorija sadrži polja, a ova polja čine metapodatke i svojstva pojedinačnih događaja. Možete da vidite ove informacije tako što ćete koristiti „Prikazivač dijagnostičkih podataka“.

Kategorije prikupljenih informacija o događajima mogu biti podeljene u dve grupe:

  - [Informacije koje su zajedničke za sve događaje](#information-common-to-all-events)
  - [Informacije koje posebno podržavaju prikupljanje dijagnostičkih podataka](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a>*Informacije koje su zajedničke za sve događaje*

Informacije koje su zajedničke za sve događaje se prikupljaju u sledećim kategorijama.

#### <a name="app"></a>Aplikacija 

Informacije o aplikaciji. Sva polja su konstantna za sve sesije određene verzije aplikacije.

Ova kategorija sadrži sledeća polja:

  - **Grana** -Grana na kojoj je nastala određena verzija. Omogućava nam da utvrdimo na kojem je tipu grane određena verzija nastala tako da možemo da ispravno usmerimo popravke.
  - **Tip instalacije** – brojač koji utvrđuje način na koji je korisnik instalirao aplikaciju. Omogućava nam da utvrdimo da li određeni mehanizmi instalacije prave probleme koji se ne vide u drugim mehanizmima za instalaciju.
  - **Ime** - ime aplikacije koja pruža podatke. Omogućava nam da utvrdimo koja aplikacija ima problem, tako da znamo kako da ga popravimo.
  - **Platforma** - široka klasifikacija platforme na kojoj je aplikacija pokrenuta. Omogućava nam da utvrdimo na kojim platformama se javlja problem tako da možemo ispravno da damo prioritet rešavanju tog problema.
  - **Verzija** - verzija aplikacije. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.

#### <a name="client"></a>Klijent 

Identifikator povezan sa instancom sistema Office na uređaju. Konstantan za sve sesije svih aplikacija određene verzije instalacije za paketi koji sadrže više aplikacija ili konstantan za sve sesije određene verzija aplikacije.

Ova kategorija sadrži sledeća polja:

  - **Id** -Jedinstveni identifikator dodeljen klijentu u trenutku instaliranja sistema Office. Omogućava nam da utvrdimo da li problemi utiču na određeni skup instalacija i na koliko korisnika oni utiču.

#### <a name="consent"></a>Pristanak

Informacije o pristanku korisnika na prikupljanje dijagnostičkih podataka i povezanih iskustva.

Ova kategorija sadrži sledeća polja:

  - **Kategorija korisnika –** identifikuje tip korisnika koji je dao pristanak. Jedan od MSAUser, AADUser ili LocalDeviceUser

  - **Nivo pristanka za prikupljanje dijagnostičkih podataka** – označava na koji je nivo prikupljanja dijagnostičkih podataka korisnika dao pristanak.

  - **Izvorna lokacija nivoa pristanka za prikupljanje dijagnostičkih podataka** – ukazuje na to kako je korisnik obezbedio pristanak za prikupljanje dijagnostičkih podataka.

  - **Vreme pristanka za prikupljanje dijagnostičkih podataka** – ukazuje na to kada je korisnik obezbedio pristanak za prikupljanje dijagnostičkih podataka. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Status povezanih usluga** – ukazuje na to da li je korisnik odabrao da koristi ili ne koristi sva povezana iskustva

  - **Izvorna lokacija statusa povezanih usluga** – ukazuje na to kako je korisnik napravio izbor da li želi da koristi sva povezane iskustva

  - **Vreme pristanka za prikupljanje podataka o statusu povezanih usluga** – Ukazuje na to kada je korisnik odabrao da li da koristi sva povezana iskustva. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Kontroler statusa povezanih usluga** – ukazuje na to da li korisnik ima pristup opcionalnim povezanim iskustvima

  - **Izvorna lokacija za kontroler statusa povezanih usluga** – ukazuje na to kako je izvršen izbor korisnika za opcionalna povezana iskustva

  - **Vreme pristanka za prikupljanje podataka o kontroleru statusa povezanih usluga** – Ukazuje na to kada je korisnik odabrao status opcionalnih povezanih iskustava. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Status analize sadržaja povezanih iskustava korisnika** – ukazuje na to da li je korisnik odabrao da omogući ili onemogući povezana iskustva koja analiziraju sadržaj

  - **Izvorna lokacija statusa analize sadržaja povezanih iskustava korisnika** – ukazuje na to kako je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja analiziraju sadržaj

  - **Vreme pristanka za prikupljanje podataka o statusu analize sadržaja povezanih iskustava korisnika** – Ukazuje na kada je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja analiziraju sadržaj. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Status preuzetog sadržaja** – ukazuje na to da li je korisnik odabrao da omogući ili onemogući povezana iskustva koja preuzimaju sadržaj na mreži

  - **Izvorna lokacija statusa preuzetog sadržaja** – ukazuje na to kako je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja preuzimaju sadržaj na mreži

  - **Vreme pristanka na prikupljanje podataka o statusu preuzetog sadržaja** – ukazuje na to kada je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja preuzimaju sadržaj na mreži Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

#### <a name="device"></a>Uređaj 

Informacije o operativnom sistemu i izdanju.

Ova kategorija sadrži sledeća polja:

  - **Izdanje operativnog sistema** - broj izdanja operativnog sistema instaliranog na uređaju. Omogućava nam da otkrijemo da li problemi utiču na pojedinačne servisne pakete ili verzije određenog operativnog sistema drugačije od drugih kako bismo dali prioritet rešavanju problema.

  - **Verzija operativnog sistema** - verzija operativnog sistema instaliranog na uređaju. Omogućava nam da utvrdimo da li problemi utiču na jednu određenu verziju operativnog sistema više nego na druge kako bismo dali prioritet rešavanju problema.

#### <a name="legacy"></a>Zastarelo 

Pruža Id aplikacije i verziju operativnog sistema za kompatibilnost sa postojećim zastarelim metodama prikupljanja.

Ova kategorija sadrži sledeća polja:

  - **ID aplikacije** – vrednost brojača koja predstavlja aplikaciju koja šalje podatke. Omogućava nam da utvrdimo koja aplikacija ima problem, tako da znamo kako da ga popravimo.

  - **Okruženje operativnog sistema** – brojač koja ukazuje na kojem operativnom sistemu je sesija pokrenuta. Omogućava nam da utvrdimo na kojem operativnom sistemu se problem ispoljava kako bismo dali prioritet rešavanju problema.

#### <a name="release"></a>Izdanje 

Informacije koje se odnose na kanal izdanja. Sva polja su konstantna za sve sesije svih aplikacija određene verzije instalacije. Određuje grupu uređaja sve u jednoj fazi ciklusa izdavanja proizvoda.

Ova kategorija sadrži sledeća polja:

  - **Publika** - određuje podgrupu korisnika u okviru određene grupe korisnika. Omogućava nam da pratimo podskupove grupa korisnika radi procene rasprostranjenosti i određivanja prioriteta problema.

  - **Grupa korisnika** - određuje iz kog kruga podaci dolaze. Omogućava nam da objavimo funkcije u fazama i ustanovimo potencijalne probleme pre nego što dospeju do većina korisnika.

  - **Kanal** - kanal putem kojeg se proizvod objavljuje. Omogućava nam da utvrdimo da li problem utiče na jedan od naših distributivnih kanala drugačije nego na druge.

  - **Ogranak** - određuje ogranak proizvoda. Omogućava mehanizam za grupisanje podataka u okviru skupa verzija radi utvrđivanja problema vezanih za određeno izdanje.

#### <a name="session"></a>Sesija 

Informacije o procesu sesije. Sva polja su konstantna za ovu sesiju.

Ova kategorija sadrži sledeća polja:

  - **AB konfiguracije** - određuje skup letova koji se izvršavaju u određenoj sesiji. Omogućava nam da utvrdimo koji pojedinačni letovi se izvršavaju u sesiji, tako da možemo utvrditi da li je let izvor problema koji utiče na korisnike.

  - **EcsETag** – indikator iz sistema letova koji predstavlja letove poslate na računar. Omogućava nam da utvrdimo koji letovi mogu da utiču na određenu sesiju.

  - **Zastavice** – zastavice za praćenje maske bitova koje se mogu primeniti na celu sesiju, trenutno prevashodno usmerene na uzorkovanje i opcije dijagnostičkih podataka. Omogućava nam da kontrolišemo ponašanje određene sesije u odnosu na dijagnostičke podatke koje ona generiše.

  - **Id** – jedinstveno identifikuje određenu sesiju podataka. Omogućava nam da utvrdimo uticaj problema procenom broja sesija na koje problem utiče i da li postoje funkcije koje su zajedničke za ove sesije.

  - **Id utiska** - određuje skup letova koji se izvršavaju u određenoj sesiji. Omogućava nam da utvrdimo koji pojedinačni letovi se izvršavaju u sesiji, tako da možemo utvrditi da li je let izvor problema koji utiče na korisnike.

  - **Merenje omogućeno** – zastavica koja ukazuje na to da li se podaci trenutne sesije uzorkuju ili ne. Omogućava nam da odredimo kako statistički proceniti podatke koji su prikupljeni u određenoj sesiji.

  - **Id klijenta za uzimanje uzorka** - id klijenta koji se koristi za utvrđivanje da li je deo procesa uzorkovanja. Omogućava nam da utvrdimo zašto je pojedinačna sesija uključena ili isključena iz uzoraka.

#### <a name="user"></a>Korisnik

Pruža informacije o zakupcu za jedinice za čuvanje zaliha komercijalnog softvera.

Ova kategorija sadrži sledeća polja:

  - **Heš primarnog identiteta** – identifikator pod pseudonimom koji predstavlja trenutnog korisnika.

  - **Mesto primarnog identiteta** – tip identiteta sadržanog u hešu primarnog identiteta. Jedan od MASCID, OrgIdCID ili UserObjectId.

  - **Grupa zakupca** - tip zakupca kome pripada pretplata. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem rasprostranjen ili izolovan u skupu korisnika.

  - **ID zakupca** - zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem rasprostranjen ili izolovan u skupu korisnika ili u određenom zakupcu.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Informacije koje posebno podržavaju prikupljanje dijagnostičkih podataka*

Informacije koje posebno podržavaju prikupljanje dijagnostičkih podataka se prikupljaju u sledećim kategorijama.

#### <a name="activity"></a>Aktivnost

Informacije koje služe za razumevanje uspešnosti samog procesa prikupljanja.

Ova kategorija sadrži sledeća polja:

  - **Režim grupisanja** - govori sistemu kako da grupiše rezultate aktivnosti. Omogućava nam da smanjimo količinu informacija koje se otpremaju sa računara korisnika tako što grupišemo rezultate aktivnosti u jedan događaj koji se šalje povremeno.

  - **Broj** - koliko puta se aktivnost izvršila ako se broj izračunava iz grupisanog događaja. Omogućava nam da odredimo koliko često se aktivnost uspešno ili neuspešno izvršila u odnosu na režim grupisanja aktivnosti.

  - **CV** - vrednost koja određuje odnos između aktivnosti i podaktivnosti. Omogućava nam da obnovimo odnos između ugnežđenih aktivnosti.

  - **Trajanje** - koliko vremena je bilo potrebno za izvršavanje aktivnosti. Omogućava nam da utvrdimo probleme sa performansama koje negativno utiču na iskustvo korisnika.

  - **Rezultat**.**Kod** - Aplikacijom određena šifra koja služi za identifikaciju određenih rezultata. Omogućava nam da odredimo preciznije detalje određenog neuspeha, kao što je kôd greške koji se može koristiti za klasifikaciju i rešavanje problema.

  - **Rezultat.Oznaka** - oznaka celog broja koji određuje lokaciju u kodu gde je rezultat generisan. Omogućava nam da jasno odredimo lokaciju u kôdu na kojoj je rezultat generisan što omogućava klasifikaciju grešaka.

  - **Rezultat**.**Tip** - tip kôda rezultata. Određuje koji tip koda rezultata je poslat tako da vrednost može da se ispravno tumači.

  - **Uspeh** – zastavica koja označava da li je aktivnost uspešno izvršena ili ne. Omogućava nam da utvrdimo da li se radnje koje korisnik preduzima u proizvodu uspešno izvršavaju ili ne. To nam omogućava da prepoznamo probleme koji utiču na korisnika.

#### <a name="application"></a>Aplikacija 

Informacije o instalaciji aplikacije iz koje se događaji prikupljaju.

Ova kategorija sadrži sledeća polja:

  - **Arhitektura** - arhitektura aplikacije. Omogućava nam da klasifikujemo greške koje mogu biti specifične za arhitekturu aplikacije.

  - **Verzija „Klikni i pokreni“ paketa** - broj verzije „Klikni i pokreni“ paketa putem kojeg je aplikacija instalirana. Omogućava nam da utvrdimo koja verzija instalacionog programa je korišćena za instalaciju sistema Office tako da moćemo da utvrdimo probleme vezane za instalaciju.

  - **Distribucioni kanal** - kanal putem kojeg je aplikacija implementirana. Omogućava nam da podelimo dolazne podatke kako bismo utvrdili da li problemi utiču na korisnike.

  - **Metod instalacije** - Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **Je „Klikni i pokreni“ instalacija** – zastavica koja ukazuje na to da li je instalacija tipa „Klikni i pokreni“. Omogućava nam da prepoznamo probleme koje mogu biti specifični za mehanizam „Klikni i Pokreni“ instalacije.

  - **IsDebug** – zastavica koja ukazuje na to da li verzija sistema Office predstavlja izdanje za otklanjanje grešaka. Omogućava nam da otkrijemo da li problemi dolaze iz verzija za otklanjanje grešaka koje mogu da se ponašaju drugačije.

  - **Je instalirano na spoljašnjem uređaju za skladištenje** – zastavica koja ukazuje na to da li je sistem Office instaliran na spoljašnjem uređaju za skladištenje. Omogućava nam da odredimo da li uzrok problema može biti vezan za spoljni prostor za skladištenje.

  - **Je OEM Instalacija** – zastavica koja ukazuje na to da li je Office instalirao proizvođač originalne opreme (OEM). Omogućava nam da odredimo da li aplikaciju instalirao OEM, što nam pomaže da klasifikujemo i prepoznamo probleme.

  - **Prethodna verzija** - verzija sistema Office koja je prethodno bila instalirana na računaru. Omogućava nam da vratimo prethodnu verziju ako aktuelna verzija ima problem.

  - **Ime izvršne datoteke procesa** - ime izvršne datoteke aplikacije. Omogućava nam da utvrdimo ime izvršne datoteke koja generiše podatke pošto može postojati nekoliko različitih imena izvršne datoteke procesa koja se pojavljuju pod istim imenom aplikacije.

#### <a name="client"></a>Klijent

Informacije o Office aplikaciji.

Ova kategorija sadrži sledeća polja:

  - **Vreme prvog pokretanja** – Kada je klijent prvi put pokrenut. Omogućava nam da razumemo koliko dugo je korisnik imao instaliran sistem Office.

#### <a name="device"></a>Uređaj

Informacije o mogućnostima i konfiguraciji uređaja.

Ova kategorija sadrži sledeća polja:

  - **Podaci uređaja za digitalizaciju** – informacije o uređaju za digitalizaciju koji računar koristi. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Veličina i oblik uređaja** - određuje koje veličine i oblika je uređaj koji šalje infomacije. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Veličina i oblik uređaja** - određuje koje veličine i oblika je uređaj koji šalje informacije. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Horizontalna rezolucija** - horizontalna rezolucija ekrana uređaja. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Id** - jedinstveni identifikator uređaja. Omogućava nam da utvrdimo distribuciju problema u skupu uređaja.

  - **Poboljšana zaštita podataka je omogućena** - zastavica koja označava da li je na računaru omogućena poboljšana zaštita podataka. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **IsTerminalServer** - zastavica za utvrđivanje da li računar predstavlja terminal server. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Proizvođač** - Proizvođač uređaja. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Model** - model uređaja. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **UUIDHash matične ploče** - heš jedinstvenog identifikatora matične ploče. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Ime** - Ime uređaja. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.
  
  - **NetworkCost** - Ukazuje na tip mreže/vrstu troška, kao što je ograničena ili ograničena iznad granice.
  
  - **NetworkCountry** - Poštanski broj zemlje pošiljaoca, na osnovu nepročišćene IP adrese klijenta.

  - **Broj fizičkih jezgara procesora** Broj fizičkih jezgara procesora računara. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Lokalni standard operativnog sistema** - Lokalni standard pokrenutog operativnog sistema. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Arhitektura procesora** - Arhitektura procesora. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Broj procesora** - Broj procesora u računaru. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Brzina procesora u megahercima** - Brzina procesora. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Količina RAM memorije u megabajtima** - Količina memorije koju uređaj poseduje. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Dubina ekrana** - Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Rezolucija ekrana u TPI** - TPI vrednost rezolucije ekrana. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **SusClientId** - Windows Update ID uređaja na kome se pokreće Office.

  - **Količina slobodnog prostora u megabajtima** Količina slobodnog prostora koja je dostupna na sistemskoj particiji. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Veličina sistemske particije u megabajtima** - Veličina sistemske particije na računaru. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Vertikalna rezolucija** - Vertikalna rezolucija ekrana uređaja. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **Id računara za izveštavanje o greškama** - Jedinstveni identifikator računara koji obezbeđuje Windows izveštavanje o greškama. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

  - **WindowSqm Id računara** - Jedinstveni identifikator za računar koji obezbeđuje Windows SQM. Omogućava nam da klasifikujemo podatke na osnovu okretanja uređaja.

#### <a name="event"></a>Događaj 

Informacije specifične za određeni događaj, uključujući i njegov jedinstveni identifikator u okviru sesije.

Ova kategorija sadrži sledeća polja:

  - **Ugovor** - Lista svih ugovora koji događaj sprovodi. Omogućava nam da razmotrimo koji podaci su deo pojedinačnog događaja, tako da efikasno možemo da ih obradimo.

  - **CV** - Vrednost koja nam omogućava da identifikujemo događaje koji su povezani jedan sa drugim. Koristi se za dijagnostiku da nam omogući da identifikujemo obrasce srodnog ponašanja ili srodnih događaja.

  - **Zastavice** - Informacije koje se koriste da izmene način odgovara određenog događaja. Koristi se za upravljanje načina na koji se određeni događaj tretira u svrhu otpremanja podataka korporaciji Microsoft.

  - **Id** - Jedinstveni identifikator događaja. Omogućava nam da jedinstveno identifikujemo događaje koji primamo.

  - **Ime** - Ime događaja. Omogućava da identifikujemo događaj koji je klijent poslao.

  - **Pravilo** – Identifikator pravila koji je generisao podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Id pravila** – Identifikator pravila koje je generisalo podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Interfejs pravila** - Bilo koji interfejs koji određeno pravilo implementira. Omogućava nam da klasifikujemo i uvezemo podatke zasnovane na njihovoj strukturu, što pojednostavljuje obradu podataka.

  - **Verzija pravila** – Identifikator pravila koje je generisalo podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Učestalost uzorkovanja** – pokazatelj procenta korisnika koji šalju ovaj deo podataka. To nam omogućava da uradimo statističku analizu podataka i za vrlo česte tačke podataka ne zahteva slanje od svih korisnika.

  - **Verzija šeme** – Verzija šeme koja se koristi za generisanje dijagnostičkih podataka. Obavezno za upravljanje podacima koji šalje klijent. Ovo omogućava povremene promene podataka koje svaki klijent šalje.

  - **Redosled** - Brojač koji identifikuje redosled prema kojem je događaj generisan na klijentu. Omogućava da se primljeni podaci poređaju tako da možemo da utvrdimo koji su koraci možda doveli do problema koji utiče na klijente.

  - **Izvor** -Izvorni kanal koji je korišćen za otpremanje podataka. Obavezno za praćenje svih naš otpremnih kanala za celokupno zdravlje i za pomoć u prepoznavanju problema sa otpremnih kanala. To nam omogućava praćenje pojedinačnih otpremnih kanala kako bismo obezbedili njihovu usaglašenost.

  - **Vreme** – Vreme generisanja događaja na klijentu. Omogućava nam da sinhronizujemo i proverimo redosled događaja generisanih na klijentu, kao i da uspostavimo pokazatelje performansi za uputstva korisnika. 

#### <a name="host"></a>Domaćin

Informacije o aplikaciji koja sadrži ugrađenu aplikaciju

Ova kategorija sadrži sledeća polja:

  - **ID** -Jedinstveni identifikator koji ugrađena aplikacija pripisuje aplikaciji koja je domaćin.

  - **ID sesije** - univerzalni jedinstveni identifikator za sesiju domaćina.

  - **Verzija** - Identifikator verzije primarne izvršne datoteke domaćina.

#### <a name="legacy"></a>Zastarelo

Informacije koje su neophodne za kompatibilnost starih sistema.

Ova kategorija sadrži sledeća polja:

  - **Izdanje operativnog sistema** - Specifičan broj izdanja operativnog sistema. Omogućava nam da utvrdimo iz koje verzije operativnog sistema potiču dijagnostički podaci kako bismo odredili prioritet problema.

  - **Broj revizije izdanja operativnog sistema** - broj revizije za izdanje operativnog sistema. Omogućava nam da utvrdimo iz koje verzije operativnog sistema potiču dijagnostički podaci kako bismo odredili prioritet problema.

  - **Međuverzija operativnog sistema** - Međuverzija operativnog sistema. Omogućava nam da utvrdimo iz koje verzije operativnog sistema potiču dijagnostički podaci kako bismo odredili prioritet problema.

  - **Niska verzije operativnog sistema** – Objedinjena niska koja predstavlja broj izdanja operativnog sistema. Omogućava nam da utvrdimo iz koje verzije operativnog sistema potiču dijagnostički podaci kako bismo odredili prioritet problema.

#### <a name="session"></a>Sesija

Informacije o procesu sesije.

Ova kategorija sadrži sledeća polja:

  - **Delta AB konfiguracija** - Prati razlike između podataka trenutne AB konfiguracije i prethodne vrednosti. Omogućava nam da pratimo nove letove na računaru kako bi utvrdili da li je novi let odgovoran za problem.

  - **Klasifikacija prikupljenih podataka** - Klase informacija koje sesija može da prikupi. Omogućava filtriranje sesija na osnovu podataka koje bi one imale.

  - **Onemogućavanje telemetrije** – Zastavica koja ukazuje na to da li je aktiviran ključ za onemogućavanje telemetrije. Omogućava nam da znamo ako sesija nije prijavljivala dijagnostičke podatke koji ne spadaju u metapodatke osnovnih usluga.

  - **Ključ uzorkovanja** -ključ koji se koristi za određivanje da li je sesija uzorkovana ili ne. Omogućava nam da razumemo kako pojedinačne sesije prave izbor da li su uzorkovane ili ne.

  - **Metoda uzorkovanja** - Metoda koja se koristi za određivanje smernica za uzorkovanje. Omogućava nam da razumemo koji podaci potiču iz sesije.

  - **Redosled** - Jedinstveni numerički identifikator za sesiju. Omogućava uređivanje rasporeda sesija za analiziranje kada je možda došlo je do problema.

  - **Početak** – Vreme pokretanja procesa sesije. Omogućava nam da utvrdimo kada je sesija počela.

  - **Razlika između vremenskih zona u minutima** - Razlika u minutima između lokalnog vremena i UTC vremena. Omogućava normalizaciju UTC vremena u lokalno vreme.

  - **Id vrednost klijenta za uzorkovanje** - Vrednost ključa koji se koristi za određivanje uzorkovanja. Omogućava nam da utvrdimo zašto je sesija uzorkovana ili nije.

  - **Id vrednost uređaja za uzorkovanje** - Vrednost ključa koji se koristi za određivanje uzorkovanja. Omogućava nam da utvrdimo zašto je sesija uzorkovana ili nije.

  - **K vrednost uzorkovanja sesije** – Napredni metapodaci uzorkovanja. Koriste se za procenu statističkog značenja primljenih podataka.

  - **N vrednost uzorkovanja sesije** – Napredni metapodaci uzorkovanja. Koriste se za procenu statističkog značenja primljenih podataka.

  - **Nivo dozvole za telemetriju** – Vrednost koja ukazuje na nivo prikupljanja dijagnostičkih podataka koji je korisnik dozvolio. Omogućava nam da razumemo koji nivo dijagnostičkih podataka da očekujemo od sesije.

## <a name="data-fields-that-are-common-for-onenote-events"></a>Polja podataka koja su uobičajena za OneNote događaje

Sledeća polja podataka su uobičajena za sve događaje za OneNote u sistemu Mac, iOS i Android.

> [!NOTE]
> Kada koristite prikazivač podataka za dijagnostiku, pojaviće se događaji za OneNote u usluzi Mac, iOS i Android sa nazivom Aktivnosti, ReportData ili Neočekivano. Da biste pronašli stvarno ime događaja, izaberite događaj, a zatim pogledajte polje Ime događaja.

- **Activity_ActivityType** -  Označava vrstu ovog događaja. Aktivnost može biti normalna aktivnost ili aktivnost visokih vrednosti.

- **Activity_AggMode** - Pokazuje sistemu kako da grupiše rezultate aktivnosti. Omogućava nam da smanjimo količinu informacija koje se otpremaju sa računara korisnika tako što grupišemo rezultate aktivnosti u jedan događaj koji se šalje povremeno.

- **Activity_Count** - Koliko puta se aktivnost izvršila ako se broj izračunava iz grupisanog događaja. Omogućava nam da odredimo koliko često se aktivnost uspešno ili neuspešno izvršila u odnosu na režim grupisanja aktivnosti.

- **Activity_CV** - Vrednost koja određuje odnos između aktivnosti i podaktivnosti. Omogućava nam da obnovimo odnos između ugnježđenih aktivnosti.

- **Activity_DetachedDurationInMicroseconds** – Vreme trajanja kada aktivnost miruje i ne radi nijedan stvarni posao, ali vreme se i dalje računa prema vremenu ukupne aktivnosti.

- **Activity_DurationInMicroseconds** - Koliko vremena je bilo potrebno za izvršavanje aktivnosti. Omogućava nam da utvrdimo probleme sa performansama koje negativno utiču na iskustvo korisnika.

- **Activity_Expiration** – Datum u numeričkom formatu označava kada će ovaj događaj prestati da se šalje od klijenata

- **Activity_FailCount** - Koliko puta ova aktivnost nije uspela

- **Activity_Name** – Skraćeno ime događaja. Omogućava da identifikujemo događaj koji je klijent poslao.

- **Activity_Namespace** – Prostor imena događaja. Dozvoljava grupisanje događaja u grupe.

- **Activity_Reason** - Niska koja pokazuje razlog zbog kojeg se aktivnost završava određenim rezultatom.

- **Activity_Result** - Zastavica koja ukazuje da li je aktivnost uspela, nije uspela ili neočekivano nije uspela. Omogućava nam da utvrdimo da li se radnje koje korisnik preduzima u proizvodu uspešno izvršavaju ili ne. To nam omogućava da prepoznamo probleme koji utiču na korisnika.

- **Activity_State** – Zastavica koja označava da li je događaj početak korisničke aktivnosti ili kraj korisničke aktivnosti.

- **Activity_FailCount** - Koliko puta je ova aktivnost uspela.

- **Kôd greške** – Označava kôd greške ako je dostupan.

- **Kôd greške2** – Označava drugi kôd greške ako je dostupan.

- **Kôd greške3** – Označava treći kôd greške ako je dostupan.

- **Oznaka greške** – Ukazuje na oznaku koja se odnosi na kôd greške ako je dostupna.

- **ErrorType** – Ukazuje na tip greške ako je dostupan.

- **EventName** - Jedinstveno ime događaja programa OneNote. OneNote događaji koriste ovo prilagođeno polje da bi naveli jedinstveno ime zahvaljujući inženjerskom ograničenju u prošlosti.

- **ExpFeatures** - Ukazuje na to da li korisnik uključuje eksperimentalne funkcije u aplikaciji OneNote ili ne.

- **ExpirationDate** – Datum u numeričkom formatu označava kada će ovaj događaj prestati da se šalje od klijenata

- **IsConsumer** – Ukazuje na to da li je korisnik potrošač ili nije

- **IsEdu** – Ukazuje na to da li je korisnik u zakupcu obrazovanja ili nije

- **IsIW** – Ukazuje na to da li je korisnik korporativni koristnik ili nije

- **IsMsftInternal** – Ukazuje na to da li je korisnik Microsoft službenik ili nije

- **IsPremiumUser** – Ukazuje na to da li korisnik ima Premium licencu ili ne

- **Namespace** – Prostor imena događaja. Dozvoljava grupisanje događaja u grupe.

- **Release_AppStore** - Zastavica ukazuje na to da li verzija dolazi iz prodavnice aplikacija ili ne.

- **Release_Audience** - Određuje podgrupu korisnika u okviru određene grupe korisnika. Omogućava nam da pratimo podskupove grupa korisnika radi procene rasprostranjenosti i određivanja prioriteta problema.

- **Release_AudienceGroup** - Određuje iz kog kruga podaci dolaze. Omogućava nam da objavimo funkcije u fazama i ustanovimo potencijalne probleme pre nego što dospeju do većine korisnika.

- **Release_Channel** - Kanal putem kojeg se proizvod objavljuje. Omogućava nam da utvrdimo da li problem utiče na jedan od naših distributivnih kanala drugačije nego na druge.

- **RunningMode** – Ukazuje na to na koji način je aplikacija pokrenuta, od strane korisnika ili iz sistemskog procesa.

- **SchemaVersion** -  Označava aktuelnu verziju telemetrije u telemetrijskom cevovodu programa OneNote.

- **Session_EcsETag** - Indikator iz sistema letova koji predstavlja letove poslate na računar. Omogućava nam da utvrdimo koji letovi mogu da utiču na određenu sesiju.

- **Session_ImpressionId** - Određuje skup letova koji se izvršavaju u određenoj sesiji. Omogućava nam da utvrdimo koji pojedinačni letovi se izvršavaju u sesiji, tako da možemo utvrditi da li je let izvor problema koji utiče na korisnike.

- **SessionCorrelationId** - Univerzalni jedinstveni identifikator za sesiju domaćina.

- **SH_ErrorCode** – Označava kôd greške ako je dostupan ako neka aktivnost ne uspe.

- **Oznaka** - Oznaka celog broja koji određuje lokaciju u kodugde se generiše telemetrijski događaj.

- **UserInfo_IdType** – Niska označava vrstu korisničkog naloga

- **UserInfo_OMSTenantId** - Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

- **UserInfo_OtherId** – Lista neprimarnih pseudonimnih identifikatora koji predstavljaju korisničke naloge.

- **UserInfo_OtherIdType** – Lista tipova naloga koji nisu primarni.

## <a name="software-setup-and-inventory-data-events"></a>Podaci dobijeni iz instalacije i popis softvera

Podtipovi podataka koji spadaju u ovu kategoriji su:
- [Podešavanje sistema Office i popis](#office-setup-and-inventory-subtype)
- [Konfiguracija Office programskih dodataka](#office-add-in-configuration-subtype)
- [Bezbednost](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Podtip podešavanja sistema Office i popisa*

Instalirani proizvod, verzija i status instalacije.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Dostupno za sve win32 aplikacije. Pomaže nam da razumemo status procesa ažuriranja office paketa (uspeh ili neuspeh sa detaljima o grešci)

Prikupljaju se sledeća polja:

- **izdanje** - Trenutno instalirana verzija sistema Office

- **kanal** - Kanal preko kog je distribuiran sistem Office.

- **kôd greške** -kôd greške koji ukazuje na neuspeh

- **poruka greške** – Dodatne informacije o grešci

- **status** - Trenutni status ažuriranja

- **ciljno izdanje** - Verzija na koju se sistem Office ažurira

#### <a name="officecompliancefileformatballotdisplayedonfirstboot"></a>Office.Compliance.FileFormatBallotDisplayedOnFirstBoot

Ukazuje na to da li je dijalog Izbor formata Office datoteka prikazan korisniku na prvom/drugom mestu prilikom pokretanja programa Word, Excel, PowerPoint u sistemu Win32.  Prati da li se prikazuje dijalog FileFormat glasački tekst koji se prikazuje u prvom/drugom pokretanju programa Word, Excel ili PPT Win32.

Prikupljaju se sledeća polja.

- **ZemljaRegion** – Podešavanje regiona zemlje korisnika u sistemu Windows

- **FileFormatBallotBoxAppIDBootedOnce** – U kojoj je aplikaciji (Word, Excel, PPT) obrađena logika glasačkog prikaza u formatu datoteke.

- **FileFormatBallotBoxDisplayedOnFirstBoot** - Šta je rezultat prikaza za format datoteke (prikazano/nije prikazano kao neočekivano/nije prikazano zbog licence/nije prikazano zbog lokacije).

#### <a name="officecompliancefileformatballotoption"></a>Office.Compliance.FileFormatBallotOption

Prati da li se prikazuje dijalog FileFormat glasački tekst koji se prikazuje u prvom/drugom pokretanju programa Word, Excel ili PPT Win32.  Ukazuje na to da li se dijalog Izbor formata Office datoteka prikazuje na prvom ili drugom mestu prilikom pokretanja programa Word, Excel ili PowerPoint u sistemu Win32.

Prikupljaju se sledeća polja:

- **FileFormatBallotSelectedOption** – Prepoznaje opciju formata datoteke (OOKSML / ODF) koju je korisnik odabrao putem dijaloškog okvira za glasački oblik datoteke.


#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Prikuplja metapodatke sistema Office kroz UTC za poređenje sa ekvivalentnim podacima prikupljenim putem kanal Office telemetrije u cilju provere ispravnosti i potpunosti podataka.

Prikupljaju se sledeća polja:

- **ab konfiguracije** - Lista ID-ova funkcija za utvrđivanje koje funkcije su omogućene na klijentu ili su prazne kada se ti podaci se ne prikupljaju.

- **abFlights** -„NoNL:NoFlights” kada letovi funkcija nisu podešeni. U suprotnom „holdoutinfo = nepoznato”.

- **Guid sesije aplikacije** – identifikator sesije za određenu aplikaciju počevši od vremena kreiranja procesa do kraja procesa. Oblikovan je kao standardni 128-bitni GUID, ali se sastoji iz 4 dela. Ta četiri dela su po redu (1) 32-bitni ID procesa (2) 16-bitni ID sesije (3) 16-bitni ID za pokretanje (4) 64-bitni proces nastanka u UTC 100ns

- **verzija izdanja aplikacije ** – Broj verzije izdanja aplikacije.

- **appVersionMajor** - Broj glavne verzije aplikacije.

- **sporedna verzija aplikacije** - Broj sporedne verzije aplikacije.

- **revizija verzije aplikacije** - Broj revizije verzije aplikacije.

- **Grupa korisnika** - Ime za grupu korisnika izdanja

- **Id korisnika** - Ime za korisnike izdanja

- **kanal** - Kanal preko kog je distribuiran sistem Office.

- **klasa uređaja** - Veličina i oblik uređaja iz operativnog sistema

- **ecsETag** - Identifikator eksperimenta za proces

- **impressionId** – guid koji ukazuje na aktuelni skup funkcija.

- **Oznaka za jezik** - Aktuelna Office UI IETF oznaka za jezik

- **ID korisnika sistema Office** – Nasumično generisan GUID za ovu instalaciju sistema Office

- **arhitektura operativnog sistema** - Arhitektura operativnog sistema

- **okruženje operativnog sistema** – Ceo broj koji označava operativni sistem (Windows, Android, iOS, Mac, itd).

- **niska verzije operativnog sistema** - Verzija operativnog sistema.

- **ID sesije** – nasumično generisan guid za identifikovanje sesije aplikacije

- **UTCReplace_AppSessionGuid** - Nepromenjiva logička vrednost. Uvek ima vrednost TRUE.

#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritičan signal koji se koristi da omogući da novi korisnici mogu uspešno da pokrenu i koriste OneNote po prvi put.  Telemetrija se prikuplja da obezbedi otkrivanje kritičnih regresija za OneNote aplikaciju i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

- **AfterOneDriveFrozenAccountError** - Ukazuje na grešku koja se javlja u OneDrive aplikaciji kada je nalog zamrznut.

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **IsDelayedSignIn** – Ukazuje na to da li se prvo pokretanje vrši u odloženim režimu prijavljivanja u kojem korisnik nije dužan da se prijavi.

- **IsMSA** – Ukazuje na to da li se radi o Microsoft nalogu ili ne.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritičan signal koji se koristi da omogući da novi pojedinačni korisnici (Microsoft nalog) mogu uspešno da pokrenu i koriste OneNote po prvi put.
Kako se telemetrija koristi da obezbedi otkrivanje kritičnih regresija za OneNote aplikaciju i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

Prikupljaju se sledeća polja:

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **Error A** - OneNote objekat greške ukazuje na bilo koju grešku tokom prvog pokretanja.

- **FAllowAddingGuide** - Ukazuje na to da li će OneNote dozvoliti kreiranje beležnice sa vodičem ili ne.

- **FrozenOneDriveAccount** - Ukazuje na to da li je OneDrive nalog zamrznut ili ne.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **NoInternetConnection** - Ukazuje na to da li uređaj ima ili nema internet vezu.

- **ProvisioningFailure** - OneNote objekat greške ukazuje na postojanje ili nepostojanje greške pri dodeljivanju privilegija.

- **ProvisioningFinishedTime** - Označava vreme kada će OneNote završiti dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ProvisioningStartedTime** - Označava vreme kada će OneNote početi dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ShowSuggestedNotebooks** - Ukazuje na to da li će OneNote prikazati funkciju predložene beležnice ili ne.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritičan signal koji se koristi da omogući da novi korisnici u velikim preduzećima mogu uspešno da pokrenu i koriste OneNote po prvi put.  Kako se telemetrija koristi da obezbedi otkrivanje kritičnih regresija za OneNote aplikaciju i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **Error** - OneNote objekat greške ukazuje na bilo koju grešku tokom prvog pokretanja.

- **FAllowAddingGuide** - Ukazuje na to da li će OneNote dozvoliti kreiranje beležnice sa vodičem ili ne.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **ProvisioningFailure** - OneNote objekat greške ukazuje na postojanje bilo kakve greške pri dodeljivanju privilegija.

- **ProvisioningFinishedTime** - Označava vreme kada će OneNote završiti dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ProvisioningStartedTime** - Označava vreme kada će OneNote početi dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Prati da li je preuzet paket za „Dinamičko platno“. Smatra se konfiguracijom softvera zato što paket mora biti uspešno preuzet da bi klijentu omogućio pružanje odgovarajućeg iskustva. Posebno je važno u korisničkim pretplatama gde platno koristimo da korisnika obavestimo da je licenca istekla. Koristi se za praćenje metapodataka paketa dinamičkog sadržaja koje proizvod preuzima i kešira, kao i rezultate operacija koje se izvršavaju na paketu: neuspela preuzimanja, neuspela raspakivanja, greške pri proveri doslednosti, pregledi keša, primene paketa, izvori preuzimanja.

Prikupljaju se sledeća polja:

  - **Podaci\_Keš fascikla nije kreirana -** Bulova zastavica koja ukazuje na to da je kreiranje fascikle keša uspešno izvršeno

  - **Podaci\_CdnPath – izvorna adresa paketa-**

  - **Podaci\_EnsureCached -** Bulova zastavica koja ukazuje na to da li je paket sa sadržajem keširan

  - **Podaci\_Već postoji -** Bulova zastavica koja ukazuje na to da je paket ranije već bio preuzet i da je napravljen još jedan pokušaj

  - **Podaci\_Preuzimanje toka datoteka nije uspelo -** izvorni paket nije dostupan u izvoru

  - **Podaci\_Preuzimanje toka datoteka nije uspelo na kreira lokalnu fasciklu -** problemi na lokalnom disku izazivaju grešku prilikom kreiranja direktorijuma

  - **Podaci\_Preuzimanje toka datoteka iz paketa nije uspelo -** zastavica koja označava da li je paket preuzet, ali ga klijent ne može pročitati

  - **Podaci\_Preuzimanje toka datoteka iz paketa je uspelo -** uspešni pokušaj čitanja paketa

  - **Podaci\_Preuzimanje toka datoteka je uspelo -** bez problema na disku ili problema sa konfiguracijom koja ne dozvoljava čitanje toka datoteka

  - **Podaci\_Preuzimanje relativne putanje nije uspelo -** relativna putanja ne upućuje na pristupačnu lokaciju

  - **Podaci\_Stvarna vrednost heša -** heš vrednost izdvojena iz imena datoteke kada je paket upotrebljen

  - **Podaci\_Neuspešno izračunavanje heša -** greška pri izračunavanju heša

  - **Podaci\_HashMatchFailed -** nepodudaranje heša za ime paketa i keširanih vrednosti registratora

  - **Podaci\_HashMatchSuccess -** uspešna provera doslednosti heša

  - **Podaci\_Neuspeli zahtev za preuzimanje paketa -** preuzimanje paketa nije moguće

  - **Podaci\_Zahtev za preuzimanje paketa ne sadrži podatke -** preuzeti paket ne sadrži podatke

  - **Podaci\_Uspešan zahtev za preuzimanje paketa -** uspešno preuzimanje paketa

  - **Podaci\_Uspešno raspakivanje paketa -** statusi pokušaja raspakivanja 

  - **Podaci\_Otvaranje paketa nije uspelo -** neuspeli pokušaji otvaranja datoteke paketa

  - **Podaci\_Uspešno otvaranje paketa -** uspešni pokušaji otvaranja datoteke paketa

  - **Podaci\_Uspešna vrednost heša -** heš vrednost izdvojena iz imena datoteke kada je paket preuzet

  - **Podaci\_Uspešan izvor -** površina za koju je paket preuzet

#### <a name="officevisiovisiosku"></a>Office.Visio.VisioSKU

Obuhvata Visio SKU standard ili professional. Od suštinskog značaja za kategorizaciju problema na osnovu SKU-a.

Prikupljaju se sledeća polja:

  - **Podaci\_VisioSKU**:**ceo broj** - 0 za Standard SKU i 1 za Professional SKU

### <a name="office-add-in-configuration-subtype"></a>*Podtip konfiguracije Office programskih dodataka*

Softverski dodaci i njihova podešavanja.

#### <a name="exceladdindefinedfunctioncustomfunctionsallinone"></a>Excel.AddinDefinedFunction.CustomFunctionsAllInOne

Prikuplja informacije o ponašanju prilagođenih programskih dodataka. Održava brojače pokušaja izvršavanja, uspešnih dovršavanja, infrastrukturnih grešaka i grešaka korisničkog koda. Ovo se koristi za identifikovanje problema u vezi sa pouzdanošću u proizvodu i rešavanje problema koji utiču na korisnika.
 
Prikupljaju se sledeća polja:

- **AsyncBegin** – broj funkcija asinhronizacije koje počinju

- **AsyncEndAddinError** - broj funkcija asinhronizacije koje se završavaju greškom

- **AsyncEndInfraFailure** - broj funkcija asinhronizacije koje se završavaju u infra neuspešnosti

- **AsyncEndSuccess** - broj funkcija asinhronizacije koje se uspešno završavaju

- **AsyncRemoveCancel** – broj funkcija asinhronizacije koje su otkazane 

- **AsyncRemoveRecycle** – broj funkcija asinhronizacije koje su uklonjene zbog recikliranja 

- **StreamingCycles1** - brojač protočnog ciklusa

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Prikuplja informacije za praćenje koje instalacije Office programskih dodataka su uspešno ažurirale traku u odnosu na one koje to nisu uspele.

Koristi se za rešavanje uobičajenih problema registracije gde programski dodaci nisu ispravno instalirani i nikad se ne pojave, što ih čini neupotrebljivim.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officeextensibilityappcommandsaddsolution"></a>Office.Extensibility.AppCommands.AddSolution

Prikuplja informacije o instalaciji za Office programske dodatke koji prilagođavaju traku.  Koristi se za otkrivanje problema sa načinom na koji prilagođeni programski dodaci uređuju Office traku.
 
Prikupljaju se sledeća polja:

- **AppVersion** - verzija aplikacije

- **SolutionId** - ID rešenja

- **StoreType** - ukazuje na poreklo aplikacije

- **Telemetryid** – lična telemetrija zasnovana na potpisu identiteta


#### <a name="officeextensibilitycatalogexchangegetentitlements"></a>Office.Extensibility.Catalog.ExchangeGetEntitlements

Podaci u vezi sa uspehom za neuspelo preuzimanje podataka o pravima programskih dodataka za Office 365 zakupca i administratorski dodeljenih programskih dodatka. Koristi se za metriku ispravnosti, grafikone i analize problema klijenata.

Prikupljaju se sledeća polja:

  - **Rezultat keširanja -** rezultat pokušaja da se sačuva povratna vrednost pozivanja usluge

  - **Parametar klijenta -** identifikator klijenta poslat prilikom pozivanja usluge

  - **Broj prava -** broj prava koji se očekuje u odgovoru na pozivanje usluge

  - **Raščlanjena prava -** broj raščlanjenih prava iz odgovora

  - **Da li su sva prava raščlanjena -** da li se broj očekivanih raščlanjenih prava podudara sa brojem raščlanjenih prava

  - **ServiceCallHResult -** povratni rezultat API-a pozivanja usluge

  - **Id za telemetriju -** GUID koji predstavlja jedinstvenog korisnika

  - **Iskorišćeni keš -** da li je iskorišćen keširani odgovor umesto pozivanja usluge

  - **Parametar verzije -** broj verzije sistema Office poslat prilikom pozivanja usluge

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a>Office.Extensibility.Catalog.ExchangeGetLastUpdate

Podaci u vezi sa uspehom za neuspelo preuzimanje potrebe za ažuriranim podacima o administratorski dodeljenim programskim dodacima za Office 365 zakupca. Koristi se za metriku ispravnosti, grafikone i analize problema klijenata. ExchangeGetLastUpdate će se uvek izvršiti prilikom pokretanja operativnog sistema kao deo koda hosta i utvrditi da li su promenjene dodele programskih dodataka za korisnika.  Ako je tako, onda će se osf.DLL Će učitati tako da možemo da pozovemo ExchangeGetEntitlements da dobijemo određene zadatke (i ExchangeGetManifests će biti pozvan da preuzme sve nove manifeste koji su potrebni).  ExchangeGetEntitlements (i ExchangeGetManifests) može se takođe pozvati na zahtev kada je host aplikacija pokrenuta.  Ideja je da se ne učitava veliki DLL ako nema potrebe za tim.  Bez ovog događaja u Obavezno, ne bismo mogli da prepoznamo da li korisnici ne uspevaju da događaju do programskih dodataka koji su im dodeljeni ako to prvo pozivanje usluge ne uspe.  To takođe predstavlja glavni pokazatelj za sve probleme potvrde identiteta sa kojima se suočavamo prilikom komunikacije sa uslugom.

Prikupljaju se sledeća polja:

  - **Prekid -** da li je host ugašen tokom poziva usluge

  - **Dozvola zahteva -** da li je bio dozvoljen zahtev za potvrdu identiteta

  - **Šema potvrde identiteta -** šema potvrde identiteta koju zahteva exchange

  - **BackEndHttpStatus -** http kôd koji je naveden prilikom kominikacije sa exchange potporom

  - **Rezervni Url -** sekundarni exchange URL za pozivanje

  - **BEServer -** ime potpornog exchange servera

  - **CalculatedBETarget -** puno ime računara potpornog exchange servera

  - **Pozovi(n)\_TokenAuthError -** greška pri proveri identiteta n-tog pokušaja poziva usluge.

  - **Pozovi(n)\_TokenIsValid -** da li je token potvrde identiteta n-tog pokušaja pozivanja usluge bio važeći

  - **Metoda pozivanja -** niska koja označava kojim putem je šifra išla

  - **ConfigSvcReady -** da li usluga podešavanja već pokrenuta 

  - **Datum -** povratna vrednost exchange servera

  - **DiagInfo -** povratne informacije exchange servera

  - **Kraj\_TicketAuthError -** sve greške prilikom preuzimanja tiketa za proveru identiteta posle pozivanja usluge

  - **Kraj\_TokenIsValid -** da li je tiket za proveru identiteta važeći posle pozivanja usluge

  - **EndingIdentityState -** prijavljeni status objekata identiteta posle pozivanja usluge

  - **EwsHandler -** povratna vrednost dobijena od exchange servera

  - **FEServer -** exchange izloženi server koji uslužuje zahtev

  - **HResult -** kôd rezultata

  - **HttpStatus -** Http Statusni kôd dobijen od Exchange servera

  - **IsSupportedAuthResponse -** da li je tip potvrde identiteta onaj koji možemo da koristimo

  - **LastUpdateValueRegistry -** heš vrednost preuzeta iz registratora

  - **LastUpdateValueRetrieved -** povratna heš vrednost dobijena od pozivanja usluge

  - **MSDiagnostics -** povratna vrednost dobijena od exchange servera

  - **MsoHttpResult -** vrednost brojača koju vraća http API

  - **NeedRefresh –-** ovo je true ili false polje koje ukazuje na to da li su podaci programskog dodatka bili zastareli i da li ih je trebalo ažurirati.

  - **PrimaryUrl -** glavni URL za pozivanje usluge

  - **Id zahteva -** povratna vrednost dobijena od exchange servera

  - **Broj pokušaja zahteva -** koliko puta smo pokušali pozivanje usluge

  - **Broj pokušaja zahteva -** koliko puta su pokušali da komuniciramo sa exchange serverom

  - **Lanac rezultata -** serija šifri rezultata iz svakog pokušaja pozivanja usluge

  - **Početni status identiteta -** prijavljeni status objekata identiteta pre pozivanja usluge

  - **Id za telemetriju -** GUID koji predstavlja jedinstveni korisnički, da li treba upućivati pozive drugim uslugama

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a>Office.Extensibility.Catalog.ExchangeGetManifests

Podaci u vezi sa uspehom za neuspelo preuzimanje podataka o manifestima programskih dodataka za Office 365 zakupca i administratorski dodeljenih programskih dodatka. Koristi se za metriku ispravnosti, grafikone i analize problema klijenata.

Prikupljaju se sledeća polja:

  - **CachedManifestsParsed** – broj manifesta koji se nalaze u kešu

  - **IsAllReturnedManifestsParsed** – da li je sve vraćene manifeste bilo moguće raščlaniti

  - **ManifestsRequested** – broj potrebnih manifesta

  - **ManifestsReturned** – broj manifesta koje je server vratio

  - **ManifestsToRetrieve** – broj manifesta za preuzimanje od servera

  - **ReturnedManifestsParsed** – broj manifesta koje je server vratio koji su uspešno raščlanjeni

  - **Id za telemetriju** - GUID koji predstavlja jedinstvenog korisnika

#### <a name="officeextensibilityuxfensureloadosfdll"></a>Office.Extensibility.UX.FEnsureLoadOsfDLL 

Prati neuspela učitavanja za Osf.DLL. Otkriva grešku pri učitavanju DLL-a koje sprečava pokretanje funkcije.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officeextensibilityuxfensureloadosfuidll"></a>Office.Extensibility.UX.FEnsureLoadOsfUIDLL 

Prati neuspela učitavanja za OsfUI.DLL. Otkriva grešku pri učitavanju DLL-a koje sprečava pokretanje funkcije.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officeextensibilityuxfensureosfshareddllload"></a>Office.Extensibility.UX.FEnsureOsfSharedDLLLoad 

Prati neuspela učitavanja za OsfShared.DLL. Otkriva grešku pri učitavanju DLL-a koje sprečava pokretanje funkcije.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a>Office.Extensibility.VBATelemetryComObjectInstantiated

Prikuplja informacije o pozivanju servera za automatizaciju ili klijenta u VBA rešenjima. Koristi se za razumevanje interakcije između VBA i Com objekata.

Prikupljaju se sledeća polja:

  - **ComObjectInstantiatedCount** – broj kreiranja instanci COM objekta

  - **HashComObjectInstantiatedClsid** – heš identifikator klase COM objekta

  - **HashProjectName** – heš imena VBA projekta

  - **Id oznake** – jedinstvena oznaka

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Prikuplja informacije o pozivanju Win32 API-a u VBA rešenjima. Koristi se za razumevanje interakcije između VBA i upotrebe i za dopunu istraga bezbednosti.

Prikupljaju se sledeća polja:

  - **Broj deklaracija** – broj deklaracija

  - **Heš deklaracija** – heš DLL imena

  - **Ulazna tačka heša** – heš API imena

  - **HashProjectName** – heš imena VBA projekta

  - **IsPtrSafe** – da li je izjava deklaracije kompatibilna za različitu arhitekturu

  - **Id oznake** – jedinstvena oznaka

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Prikuplja podatke o uspehu i neuspehu učitavanja Outlook programskog dodatka. Ti podaci se aktivno prate da bi se osigurao ispravan rad programa Outlook sa programskim dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

  - **Standardna HVA aktivnost** bez prilagođenih korisnih podataka

#### <a name="officeoutlookmacaddinapiusage"></a>Office.Outlook.Mac.AddinAPIUsage

Prikuplja uspeh i neuspeh izvršavanja programskih dodataka u programu Outlook. Ti podaci se aktivno prate kako bi se osigurao ispravan rad programa Outlook sa dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AccountType** - vrsta naloga povezanog sa dodatkom 

- **Cookie** – kolačić koji koristi programski dodatak

- **DispId** - identifikator dispečera 

- **EndTime** - vreme kada je završen programski dodatak 

- **ExecutionTime** - vreme koje je proteklo tokom izvršenja programskog dodatka 

- **Result** - rezultat upotrebe programskog dodatka u programu Outlook 

- **StartTime** - vreme kada je počeo programski dodatak


#### <a name="officeoutlookmacaddineventapisusage"></a>Office.Outlook.Mac.AddinEventAPIsUsage

Prikuplja uspeh ili neuspeh izvršavanja programskih dodataka u programu Outlook. Ti podaci se aktivno prate kako bi se osigurao ispravan rad programa Outlook sa dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AddinType** – tip programskog dodatka 

- **EventAction** – radnja koju vrši programski dodatak 

- **EventDispid** - identifikator dispečera

- **EventResult** - rezultat radnje koju je izvršio programski dodatak 

#### <a name="officeoutlookmacaddininstallationfrominclientstore"></a>Office.Outlook.Mac.AddInInstallationFromInClientStore

Prikuplja uspeh i neuspeh instaliranja programskih dodataka u programu Outlook. Ti podaci se aktivno prate kako bi se osigurao ispravan rad programa Outlook sa dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AccountType** - vrsta naloga koji je povezan sa dodatkom 

- **FailureReason** - razlog zbog koga programski dodatak nije uspeo da se instalira 

- **MarketplaceAssetId** – identifikator programskog dodatka u prodavnici 

- **Status** – status programskog dodatka za instalaciju


#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add ins.InternalSetConnectEnterprise

Događaj koji se generiše kada se COM programski dodatak učita na uređaju u okviru preduzeća. 

Prikupljaju se sledeća polja:

  - **Activity Result** – stanje uspeha veze

  - **Add-inconnectFlag** – trenutno ponašanje učitavanja

  - **Add-inId** – Id klase programskog dodatka

  - **Add-inTimeDateStamp** – Vremenska oznaka programskog dodatka dobijena iz DLL metapodataka

  - **IsBootInProgress** – da li je aplikacija Office u procesu pokretanja

#### <a name="officevisiovisioaddonload"></a>Office.Visio.Visio.AddonLoad

Hvata greške kada se rešenje ne učita. Neophodna za otklanjanje grešaka pri učitavanju programskih dodataka u programu Visio.

Prikupljaju se sledeća polja:

  - **Podaci\_Load1Error:integer** -vrednost greške tokom učitavanja programskog dodatka programa Visio

#### <a name="officevisiovisioaddonusage"></a>Office.Visio.Visio.AddonUsage

Hvata greške kada dođe do greške u funkcionisanju rešenja. Neophodna za otklanjanje grešaka u programskim dodacima.

Prikupljaju se sledeća polja:

  - **Podaci\_DocumentSessionLogID:string** -identifikator sesije dokumenta

  - **Podaci\_JeOmogućeno**:**bool** – true ako je rešenje omogućeno

  - **Podaci\_TemplateID:string** -GUID predloška u kojem je učitano rešenje. Evidentirano kao 0 za prilagođeno rešenje

  - **Podaci\_ID programskog dodatka**:**niska** -GUID za identifikovanje učitanog dodatka

  - **Podaci\_Greška**:**ceo broj** - ID greške

### <a name="security-subtype"></a>*Podtip bezbednosti*

Uslovi pod kojima dolazi do greški u dokumentima, funkcijama i dodacima a koje mogu da ugroze bezbednost, uključujući spremnost proizvoda za ažuriranje.

#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Prati kada se određeni identifikator klase (Flash, Silverlight itd.) aktivira u sistemu Office. Koristi se za praćenje uticaja blokiranja Flash, Silverlight i Shockwave kontrola na krajnje korisnike.

Prikupljaju se sledeća polja:

  - **Tip aktivacije** - Tip aktivacije za kontrolu

  - **Blokirani** - da li je office blokirao kontrolu

  - **CLSID** - identifikator klase kontrole

  - **Broj** - kako je puta aktivirana kontrola

#### <a name="officesecurityactivationfilterfailedtoregister"></a>Office.Security.ActivationFilter.FailedToRegister

Prati stanje greške u bezbednosnom ublažavanju koje blokira aktiviranje opasnih kontrola u sistemu Office.

Koristi se za dijagnostikovanje stanja grešaka u bezbednosnom ublažavanju koja mogu da utiču na bezbednost krajnjih korisnika.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a>Office.Security.ComSecurity.FileExtensionListFromService

Prati da li su proširenja za blokiranje programa za pakovanje bila pročitana iz usluge podešavanja ili smo koristili podrazumevanu listu klijenta. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **RetrievedFromServiceStatus** – da li smo uspeli da preuzmemo listu oznaka tipa datoteka koje treba blokirati i ako nismo onda šta je bio uzrok greške

#### <a name="officesecuritycomsecurityload"></a>Office.Security.ComSecurity.Load

Prati kada se u dokumentu učitao OLE objekat. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **CLSID** - identifikator klase OLE kontrole

  - **Broj** – koliko puta je OLE kontrola bila učitana.

  - **DocUrlHash** – heš koji predstavlja dokument na jedinstven način. (Napomena – ne postoji način da iz ovoga saznate stvarne detalje dokumenta. To je samo jedinstven prikaz dokumenta.)

  - **JeKategorizovan** – da li je OLE kontrola bila kategorizovana da učita office

  - **SeMožeUmetnuti** – da li se OLE kontrola može umetnuti ili ne

#### <a name="officesecuritycomsecurityobjdetected"></a>Office.Security.ComSecurity.ObjDetected

Prati kada je u dokumentu otkriven OLE objekat. Koristi se da bi se obezbedila efikasnost ublažavanja bezbednosti koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **CLSID** - identifikator klase OLE kontrole

  - **Broj** – koliko puta je ovaj OLE objekat otkriven

  - **DocUrlHash** – heš koji predstavlja dokument na jedinstven način. (Napomena – ne postoji način da iz ovoga saznate stvarne detalje dokumenta. To je samo jedinstven prikaz dokumenta.)

  - **JeKategorizovan** – da li je OLE kontrola kategorizovana da učita office

  - **SeMožeUmetnuti** – da li se OLE kontrola može umetnuti ili ne

#### <a name="officesecuritycomsecuritypackageractivation"></a>Office.Security.ComSecurity.PackagerActivation

Prati ishod ublažavanja bezbednosti koje blokira opasana proširenja ugrađena u Office dokumente. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **SaInterneta** - da li je dokument bio sa interneta

  - **Postavke programa za pakovanje** - koje su bile trenutne postavke program za pakovanje

  - **PouzdaniDokument** - da li je dokument bio pouzdani dokument

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a>Office.Security.ComSecurity.PackagerActivationErrors

Prati stanje greške pri ublažavanju bezbednosti koje blokira opasana proširenja ugrađena u Office dokumente. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **Greška** - Kôd greške

  - **Oznaka tipa datoteke** - koja je oznaka tipa datoteke

  - **SaInterneta** - da li je dokument bio sa interneta

  - **PovezaniDokument** – da li je dokument povezan ili ne

  - **Postavke programa za pakovanje** - koje su bile trenutne postavke program za pakovanje

  - **PouzdaniDokument** - da li je dokument bio pouzdan


#### <a name="officesecuritymacrointernetvbablockenabled"></a>Office.Security.Macro.InternetVBABlockEnabled

Prati da li je postavka za blokiranje makroa sa Interneta omogućena na klijentu. Procenite upotrebu ublažavanja bezbednosti u cilju zaštite od zlonamernih makroa.

Prikupljaju se sledeća polja:

  - Nijedno

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a>Office.Security.Macro.PolicyDigSigTrustedPublishers

Prati da li je provereno da makro potiče od pouzdanog izdavača. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

Prikupljaju se sledeća polja:

  - **Smernice** -da li su smernice postavljanje ili ne, da li su dostupne

#### <a name="officesecuritymacroprompted"></a>Office.Security.Macro.Prompted

Prati kada je od korisnika zatraženo da omogući VBA makroe. Koristi se za procenu rasprostranjenosti VBA makroa i podsticanje budućih bezbednosnih olakšica koje ograničavaju izvršavanje makroa kao odgovor na bezbednosne incidente.

Prikupljaju se sledeća polja:

  - **TipZahteva** - koju tip zahteva je prikazan

  - **VBAMacroAntiVirusHash** - antivirusni heš makroa

  - **VBAMacroAntiVirusHRESULT** - rezultat antivirusne procene

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a>Office.Security.Macro.VBASecureRuntimeSessionEnableState

Prati svaku obavljenu proveru AMSI izvršavanja kada se makro izvršava. Prati efikasnost provere AMSI izvršavanja makroa i utvrđuje greške koje mogu da utiču bezbednosne krajnjih korisnika.

Prikupljaju se sledeća polja:

  - **IsRegistry** - da li je administrator napravio neke izmene u registratoru

  - **Status** - koji je status bezbednog izvršavanja

#### <a name="officesecuritymacroxl4prompted"></a>Office.Security.Macro.XL4Prompted

Prati kada je od korisnika zatraženo da omogući XL4 makroe. Koristi se za procenu rasprostranjenosti XL4 makroa u programu Excel i podsticanje budućih bezbednosnih olakšica koje automatski blokiraju XL4 kao odgovor na bezbednosne incidente koji uključuju zloupotrebu XL4 makroa.

Prikupljaju se sledeća polja:

  - **TipZahteva** - koju tip zahteva je prikazan


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Prati kada se korisniku prikazuje bezbednosni zahtev prilikom učitavanja ActiveX kontrole koja je označena kao nebezbedna za pokretanje. Koristi se za praćenje rasprostranjenosti UFI ActiveX kontrola u Office dokumentima u cilju podsticanja olakšica (npr. killbitting kontrola) kao odgovor na bezbednosne incidente.

Prikupljaju se sledeća polja:

  - **JeSaInterneta** - da li je otvoren dokument sa interneta

  - **JeURežimuBezbednogČitača** - da li je dokument otvoren u bezbednom čitaču

  - **OcxTrustCenterSettings** - koje su trenutne postavke za ActiveX kontrole


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Prati završetak otvorene u zaštićenom prikazu. Koristi se za dijagnostikovanje uslova koji dovode do greške prilikom otvaranja datoteke u zaštićenom prikazu što utiče na bezbednost i produktivnost klijenata.

Prikupljaju se sledeća polja:

  - Nijedno

## <a name="product-and-service-usage-data-events"></a>Podaci događaja upotrebe proizvoda i usluga

Podtipovi podataka koji spadaju u ovu kategoriji su:

- [Uspešnost funkcija aplikacije](#application-feature-success-subtype)
- [Status aplikacije i pokretanje](#application-status-and-boot-subtype)
- [Konfiguracija pristupačnosti sistema Office](#office-accessibility-configuration-subtype)
- [Privatnost](#privacy-subtype)


### <a name="application-feature-success-subtype"></a>*Podtip uspešnosti funkcija aplikacije*

Uspešnost funkcionalnosti aplikacije. Ograničena na otvaranje i zatvaranje aplikacije i dokumenata, uređivanje i deljenje (saradnju) datoteka.


#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcCreateRepublishingLicense API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgetlicenseproperty"></a>IpcGetLicenseProperty

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetLicenseProperty API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.LicensePropertyType** - tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgetserializedlicenseproperty"></a>IpcGetSerializedLicenseProperty

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetSerializedLicenseProperty API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey**- Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.LicensePropertyType** - Tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgettemplateissuerlist"></a>IpcGetTemplateIssuerList

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetTemplateIssuerList API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije o URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga
 
- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **UserInfo.UserObjectId** - Id korisničkog objekta

#### <a name="ipcgettemplatelist"></a>IpcGetTemplateList

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetTemplateList API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije o URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga
 
- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **UserInfo.UserObjectId** - Id korisničkog objekta

#### <a name="ipcpcreatelicensefromscratch"></a>IpcpCreateLicenseFromScratch

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpCreateLicenseFromScratch API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** - Id korisničkog objekta 

#### <a name="ipcpcreatelicensefromtemplate"></a>IpcpCreateLicenseFromTemplate

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpCreateLicenseFromTemplate API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

#### <a name="ipcpgettemplatelistforuser"></a>IpcpGetTemplateListForUser

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpGetTemplateListForUser API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije o URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 
    
- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** - Id korisničkog objekta 

#### <a name="ipcpserializelicense"></a>IpcpSerializeLicense

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpSerializeLicense API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.ContentId** - Id sadržaja dokumenta

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.KeyHandle** - Memorijska adresa pokazivača ključa

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** - Id korisničkog objekta 

#### <a name="ipcsetlicenseproperty"></a>IpcSetLicenseProperty

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcSetLicenseProperty API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva 

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.LicensePropertyType** - tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Id scenarija definisan API-jem


#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Generisano prilikom pokretanja klijenta kada krajnji korisnik omogući Kontrolnu tablu Office telemetrije.  Prikuplja informacije o tome kada je Office Telemetry agent učitao podatke u fasciklu „Deljenje“. Primarno korišćenje ovog događaja jeste nadgledanje zdravlja usluge Office Telemetrije, a sekundarno korišćenje događaja jeste da proceni korišćenje kontrolne table Office telemetrije.

Prikupljaju se sledeća polja:

- **UploadTime** - vremenski žig poslednjeg uspešnog otpremanja koji je obavio telemetrijski agent.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Prikupljaju se samo kada krajnji korisnik omogući Kontrolnu tablu Office telemetrije.Prikuplja informacije o tome kada se izvršava Office Telemetry agent.  Ovo se prikuplja samo kada je Kontrolna tabla Office telemetrije omogućena, a koristi se za određivanje ispravnost agenta Office telemetrije.

Prikupljaju se sledeća polja:

  - **Data.AgentExit** - Vremenska oznaka koja označava kada se agent telemetrije uspešno zatvori.

  - **Data.AgentExit** - Vremenska oznaka koja označava kada agent telemetrije uspešno obavi skeniranje.

  - **Data.AgentUpload** - Vremenska oznaka koja označava kada agent telemetrije uspešno završi otpremanje.

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Prikuplja se samo kada krajni korisnik (najverovatnije administrator) omogući Kontrolnu tablu Office telemetrije.  Prikuplja pojavljivanje padova Office programskih dodataka i dokumenata. Ovo se prikupljaju samo onda kada korisnik omogući Kontrolnu tablu Office telemetrije i koristi se za utvrđivanje da li postoji povećano pojavljivanje padova programskih dodataka ili dokumenata.

Prikupljaju se sledeća polja:

  - **Vreme prikupljanja podataka** - Vremenska oznaka koja označava kada je evidentiran događaj pada

#### <a name="office_apple_activateperpetual"></a>Office_Apple_ActivatePerpetual

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja neprekidnog toka aktivacije kao i za istraživanje uzroka greški pregledom vrednosti FailedAt.

Prikupljaju se sledeća polja:

- **Data_FailedAt** - Sakupljamo nisku koja obeležava mesto gde je došlo do neuspeha pri procesu aktivacije stalne licence.

#### <a name="office_apple_activatesubscription"></a>Office_Apple_ActivateSubscription

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informacije vezane za migraciju iz zastarelog steka koda za licenciranje na vNext klin koda za licenciranje. Ovo se koristi za nadgledanje stanja aktiviranja pretplate, kao i za praćenje da li je ovo migracija na licencu vNext i da li je korišten primarni identitet.

Prikupljaju se sledeća polja:

- **Data_ActivatingPrimaryIdentity** - Vrednost true/false koja označava da li je korišten primarni identitet. 

- **Data_NULSubscriptionLicensed** - Vrednost true/false koja označava stanje pretplate

#### <a name="office_apple_cisauthticketwithidentity"></a>Office_Apple_CISAuthTicketWithIdentity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za hvatanje neuspeha automatskog dodavanja tokena za potvrdu identiteta tokom kupovine unutar aplikacije na Mac računarima (događaj evidentira primljeni kôd greške).  Ovaj događaj se koristi za otkrivanje i rešavanja neuspešnog dodavanja tokena za potvrdu identiteta

Prikupljaju se sledeća polja:

- **Data_EmptyAuthToken** - Sakupljamo nisku koja obeležava mesto gde je došlo do neuspeha pri procesu aktivacije stalne licence.

- **Data_TicketAuthError** - Kôd greške koji ukazuje na uzrok neuspeha

- **Data_ValidIdentity** – Da li klijent ima važeći identitet

#### <a name="office_apple_inappassociationactivity"></a>Office_Apple_InAppAssociationActivity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informacije povezane sa povezivanjem proizvoda nakon kupovine iz aplikacije. Evidentiramo koji SKU pretplate povezujemo.  Ovo se koristi za nadgledanje stanja povezanih proizvoda kupljenih iz aplikacije.

Prikupljaju se sledeća polja:

- **Data_ProductID** - SKU pretplate kojem pokušavamo da pridružimo proizvod.

#### <a name="office_apple_inapppurchaseactivity"></a>Office_Apple_InAppPurchaseActivity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. 

Informacije povezane sa kupovinom proizvoda prikupljamo u usluzi AppStore. Pratimo rezultat kupovine (neuspeh, uspeh, problem sa plaćanjem, itd.), tip zahteva za kupovinu (vraćanje, kupovina) i SKU/proizvod koji se kupuje (Office 365 Home, itd.).  Ovi podaci se koriste za nadgledanje stanja tokova kupovine iz aplikacije.


Prikupljaju se sledeća polja:

- **Data_ Data_PurchaseResult** - rezultat operacije kupovine

- **Data_ProductID** - proizvod koji se kupuje

- **Data_PurchaseRequestType** - tip zahteva za kupovinu

#### <a name="office_apple_intune"></a>Office_Apple_InTune

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informaciju da li trenutnu sesiju kontroliše Intune. Koristi se za izvođenje/filtriranje sesija koje kontroliše InTune i omogućava nam da istražimo potencijalne probleme vezane za to da se Office pokreće kao aplikacija koju kontroliše InTune.

Prikupljaju se sledeća polja:

- **Data_EventID** - prikupljamo nisku koja predstavlja kôd koji označava da li sesiju kontroliše Intune.

#### <a name="office_apple_licensing_mac_licensingstate"></a>Office_Apple_Licensing_Mac_LicensingState

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj snima trenutno stanje licence za sesiju na računaru (id OLS licence, SKU koji se koristi, grejs period ili ne, RFM, itd.). Prikupljeni podaci koriste se za otkrivanje grešaka i istraživanje uzroka neuspeha. 

Prikupljaju se sledeća polja:

- **Data_DidRunPreview** - niska koja pokazuje da li se ova sesija pokreće u pregledu

- **Data_LicensingACID** - niska koja predstavlja interni identifikator sistema licenciranja

- **Data_LicensingType** - niska koja predstavlja tip licence

- **Data_OLSLicenseId** - niska koja predstavlja identifikator licence

- **Data_State** - niska koja predstavlja trenutno stanje licence

#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Omogućava nam da znamo da li je povezivanje uređaja ili aplikacije bilo uspešno.  Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Ime_Aktivnosti** = ime aktivnosti „ConnectDevice“

- **Activity_CV** = ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** = Početak

- **Activity_DateTimeTicks** = vreme podataka za aktivnost
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Omogućava nam da znamo da li je povezivanje uređaja ili aplikacije bilo uspešno. Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Ime_Aktivnosti** - ime aktivnosti „ConnectDevice“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Zaustavljanje

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="office_docs_apple_docsuxiossaveasthroughfilemenu"></a>Office_Docs_Apple_DocsUXiOSSaveAsThroughFileMenu 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija „Sačuvaj kao“ i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji datoteka, kao što su kategorije lokacije.  Operacija „Sačuvaj kao“ pojavljuje se svaki put kada korisnik napravi novu datoteku i prvi put je sačuva ili sačuva kopiju postojeće datoteke na novu lokaciju.

Prikupljaju se sledeća polja:

- **Data_OriginServiceType** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_ServiceType** - apstraktna kategorizacija nove lokacije datoteke nakon što se dovrši čuvanje kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="office_docs_apple_docsuxmacatmentioninsertedatmention"></a>Office_Docs_Apple_DocsUXMacAtMentionInsertedAtMention 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik „@“ pominje drugog korisnika i koristi se za razumevanje i određivanje prioriteta korisničkog iskustva na osnovu načina na koji korisnici sarađuju sa drugim korisnicima.

Prikupljaju se sledeća polja:

- **Data_CharactersTyped** - numerička vrednost koja označava ukupan broj znakova otkucanih u tekstu pominjanja „@“.

#### <a name="office_docs_apple_docsuxmacodspsharingwebviewsharingcompleted"></a>Office_Docs_Apple_DocsUXMacODSPSharingWebViewSharingCompleted 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se beleži kada korisnik odluči da deli dokument u oblaku koristeći iskustvo deljenja usluge OneDrive i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ShareType** - fiksno kodirana niska koja pokazuje kakva je operacija deljenja završena uključujući, ali ne ograničavajući se na „Kopiraj vezu“, „Više aplikacija“, „Teams“.

- **Data_ShareWebViewMode** - fiksno kodirana niska koja pokazuje kakav je režim deljenja bio aktivan kada je deljenje dovršeno, uključujući, ali ne ograničavajući se na „Upravljanje pristupom“, „AtMentions“, „Deljenje“.

#### <a name="office_docsui_collaboration_coauthorgalleryrowtapped"></a>Office_DocsUI_Collaboration_CoauthorGalleryRowTapped 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se beleži kada korisnik odabere da pogleda spisak trenutnih koautora.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na koautorstvo dokumenta u isto vreme.

Prikupljaju se sledeća polja:

- **Data_CoauthorCount** - numerička vrednost koja predstavlja ukupan broj osoba koji trenutno uređuju isti dokument kao i korisnik.

#### <a name="office_docsui_collaboration_collabcornerpeoplegallerycoauthorsupdated"></a>Office_DocsUI_Collaboration_CollabCornerPeopleGalleryCoauthorsUpdated 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kada se promeni broj aktivnih koautora u dokumentu u oblaku.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na koautorstvo dokumenta u isto vreme.

Prikupljaju se sledeća polja:

- **Data_CoauthorsJoined** - Broj koautora koji su se pridružili dokumentu.

- **Data_CoauthorsLeft** - Broj koautora koji su napustili dokument.

- **Data_NewCoauthorCount** - novi broj aktivnih koautora u dokumentu. 

- **Data_OldCoauthorCount** - prethodni broj aktivnih koautora pre ažuriranja.

- **Data_ServiceType** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="office_docsui_docstage_docstagecreatenewfromtemplate"></a>Office_DocsUI_DocStage_DocStageCreateNewFromTemplate 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kada se nova datoteka kreira iz iskustva „Novo iz predloška“ i koristi se za bolje razumevanje i određivanje prioriteta korisničkog iskustva na osnovu informacija o kreiranju dokumenata.

Prikupljaju se sledeća polja:

- **Data_InHomeTab** - Bulova vrednost koja označava da li je nova datoteka iz predloška kreirana na kartici „Početak“ novog iskustva datoteke.

- **Data_InSearch** - Bulova vrednost koja označava da li je datoteka kreirana kada je korisnik tražio predložak.

- **Data_IsHomeTabEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupna kartica „Početak“.

- **Data_IsRecommendedEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupno iskustvo „Preporučeno“.

- **Data_TemplateIndex** - Numerički indeks datoteke predloška dok se vizuelno prikazuje korisniku.

- **Data_TemplateType** - Klasifikacija koja će vam pomoći da razlikujete tip predloška, uključujući, ali ne ograničavajući se na predložak „Na mreži“, predložak „Pretraži na mreži“, predloške „Lokalno“.

#### <a name="office_docsui_docstage_recommendedopen"></a>Office_DocsUI_DocStage_RecommendedOpen

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija otvaranja datoteke iz odeljka preporučenih datoteka u galeriji dokumenata i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke.

Prikupljaju se sledeća polja:

- **Data_Success** - Bulova vrednost koja pokazuje da li je operacija uspela.

#### <a name="office_docsui_fileoperations_docsuifileopenmacrequired"></a>Office_DocsUI_FileOperations_DocsUIFileOpenMacRequired

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija otvaranja datoteke i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke kao što su kategorija lokacije „Tip usluge“ i prva četiri znaka oznake tipa datoteke.

Prikupljaju se sledeća polja:

- **Data_Ext** - Oznaka tipa datoteke ograničena je na prva četiri znaka oznake ili manje.

- **Data_ServiceType** - apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd.

#### <a name="office_docsui_fileoperations_openfilewithreason"></a>Office_DocsUI_FileOperations_OpenFileWithReason 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija otvaranja datoteke i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke kao što su kategorija lokacije „Tip usluge“ i odakle je u okviru aplikacije korisnik zatražio da otvori datoteku.

Prikupljaju se sledeća polja:

- **Data_IsCandidateDropboxFile** - ovo je Bulova vrednost koja se evidentira ako pregledajući putanju datoteke smatramo da je to možda iz fascikle koju sinhronizuju DropBox.

- **Data_IsSignedIn** - bez obzira na to da li je korisnik prijavljen kada se čuva datoteka.

- **Data_OpenReason** - otvoreni razlog je numerička vrednost koja označava mesto u okviru aplikacije sa kojeg je korisnik otvorio datoteku.

- **Data_ServiceType** - apstraktna numerička kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="office_docsui_fileoperations_savetourl"></a>Office_DocsUI_FileOperations_SaveToURL

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija „Sačuvaj kao“ i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji datoteka, kao što su kategorije lokacije i prva četiri znaka oznake tipa datoteke.  Operacija „Sačuvaj kao“ pojavljuje se svaki put kada korisnik napravi novu datoteku i prvi put je sačuva ili sačuva kopiju postojeće datoteke na novu lokaciju.

Prikupljaju se sledeća polja:

- **Data_FileExtension** - prva četiri znaka oznake tipa nove datoteke.

- **Data_IsNewFileCreation** - označava da li je operacija čuvanja za novu datoteku ili kopiju postojeće datoteke.


- **Data_IsSignedIn** - bez obzira na to da li je korisnik prijavljen kada se čuva datoteka.

- **Data_SaveErrorCode** - numerička vrednost koja se postavlja ako postoji greška koja će vam pomoći u prepoznavanju vrste greške.

- **Data_SaveErrorDomain** - precizira domen SaveErrorCode kako je definisan od strane Apple SaveErrorDomains „to su proizvoljne niske koje se koriste za razlikovanje kodova“.

- **Data_SaveLocation** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_SaveOperationType** - numerička vrednost definisana NSSaveOperationType grupom vrednosti kompanije Apple.

#### <a name="office_docsui_sharingui_cloudupsellshown"></a>Office_DocsUI_SharingUI_CloudUpsellShown 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik prođe kroz nadogradnju dokumenata u tok oblaka.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileStyle** - numerička vrednost koja pokazuje iz kojeg scenarija je prikazano iskustvo nadogradnje kao što je preklopnik za automatsko čuvanje ili dugme za deljenje.

- **Data_FileType** - prva četiri znaka oznake tipa nove datoteke.

- **Data_InDocStage** - Bulova vrednost koja pokazuje da li je iskustvo nadogradnje prikazano iz galerije dokumenata ili iz prozora dokumenta.

- **Data_IsDocumentOpened** - Bulova vrednost koja pokazuje da li je trenutni dokument za koji se prikazuje iskustvo nadogradnje takođe otvoren.

- **Data_IsDraft** - Bulova vrednost koja pokazuje da li je trenutna datoteka ikada sačuvana.

- **Data_IsSheetModal** - Bulova vrednost koja označava da li je iskustvo nadogradnje predstavljeno modalno ili ne.

#### <a name="office_docsui_sharingui_cloudupsellupload"></a>Office_DocsUI_SharingUI_CloudUpsellUpload 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik odluči da otpremi novu ili lokalnu datoteku u oblak i rezultat te operacije.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileStyle** - numerička vrednost koja pokazuje iz kojeg scenarija je prikazano iskustvo nadogradnje kao što je preklopnik za automatsko čuvanje ili dugme za deljenje.

- **Data_FileType** - prva četiri znaka oznake tipa nove datoteke.

- **Data_InDocStage** - Bulova vrednost koja pokazuje da li je iskustvo nadogradnje prikazano iz galerije dokumenata ili iz prozora dokumenta.

- **Data_IsDefaultServiceLocation** - Bulova vrednost koja označava da li je izabrana lokacija za otpremu dokumenta podrazumevana lokacija.

- **Data_IsDocumentOpened** - Bulova vrednost koja pokazuje da li je trenutni dokument za koji se prikazuje iskustvo nadogradnje takođe otvoren.

- **Data_IsDraft** - Bulova vrednost koja pokazuje da li je trenutna datoteka ikada sačuvana.

- **Data_IsSheetModal** - Bulova vrednost koja označava da li je iskustvo nadogradnje predstavljeno modalno ili ne.

- **Data_LocationServiceType** - apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_UploadAction** - fiksno kodirana niska koja pokazuje da li je otprema bila operacija premeštanja ili kopiranja.

- **Data_UploadResult** - fiksno kodirana niska koja pokazuje rezultat pokušaja otpremanja, uključujući, ali ne ograničavajući se na, „Uspeh“, „UserCancelledUpload“ i „PreAuthFailed“.

#### <a name="office_docsui_sharingui_copylinkoperation"></a>Office_DocsUI_SharingUI_CopyLinkOperation

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik odluči da deli dokument u oblaku generisanjem veze na dokument u oblaku i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ ServiceType** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_LinkType** - Fiksno kodirana niska koja opisuje vrstu izvršenog poziva kao što su „Samo za prikaz“ i „Prikaz i uređivanje“.

- **Data_ShareScenario** - Fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="office_docsui_sharingui_docsuionedriveshare"></a>Office_DocsUI_SharingUI_DocsUIOneDriveShare 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se beleži kada korisnik odluči da deli dokument u oblaku koristeći iskustvo deljenja usluge OneDrive i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ODSPShareWebviewShareError** - ako iskustvo deljenja doživi grešku, ovo je numerička vrednost koja će vam pomoći da identifikujete razlog neuspeha.

- **Data_ODSPShareWebviewShareGrantAccessResult** - Bulova vrednost koja kad je vrednost „true“ ukazuje da je lagana operacija deljenja uspešno završena.

- **Data_ODSPShareWebviewShareSuccessType** - kada se operacija deljenja uspešno dovrši, ovo je numerička vrednost koja se koristi da se odredi koja operacija deljenja je dovršena.

- **Data_WebViewInfoResult** - ako se korisnički interfejs ne učita, ovo je numerička vrednost koja će vam pomoći da identifikujete razlog neuspeha. 

- **Data_WebViewLoadTimeInMs** - numerička vrednost koja snima koliko je vremena potrebno da se veb korisnički interfejs učita.


#### <a name="office_docsui_sharingui_invitepeople"></a>Office_DocsUI_SharingUI_InvitePeople 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik odluči da pozove osobe dokument u oblaku i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ ServiceType** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_InviteeCount** - ukupan broj kontakata pozvanih u dokument u jednoj akciji poziva.

- **Data_LinkType** - fiksno kodirana niska koja opisuje vrstu izvršenog poziva kao što su „Samo za prikaz“ i „Prikaz i uređivanje“.

- **Data_MessageLength** - numerički broj ukupnog broja znakova poslatih u poruci poziva.

- **Data_ShareScenario** - fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="office_docsui_sharingui_sendacopyoperation"></a>Office_DocsUI_SharingUI_SendACopyOperation

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik odluči da pošalje kopiju dokumenta i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_IsHomeTabEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupna kartica „Početak“.

- **Data_IsRecommendedEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupno iskustvo „Preporučeno“.

- **Data_OperationType** - numerička vrednost koja označava koja vrsta slanja operacije kopiranja se izvršava kao što je slanje kopije e-poštom ili slanje kopije putem Apple kontrole deljenja.

- **Data_ServiceType** - apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_ShareFileType** - fiksno kodirana niska opisa tipa objekta koji se deli, uključujući, ali ne ograničavajući se na: „Dokument“, „PDF”, „Slika“.

- **Data_ShareScenario** - fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

- **Data_SharingService** - Bulova vrednost koja označava da li je datoteka kreirana kada je korisnik tražio predložak.

#### <a name="office_docsui_sharingui_upsellshare"></a>Office_DocsUI_SharingUI_UpsellShare 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik prođe kroz nadogradnju dokumenata u tok oblaka kada pokušava da podeli dokument.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileOperationResult** - numerička vrednost koja pokazuje da li je operacija uspela.

- **Data_HostedFromDocStage** - Bulova vrednost koja označava da li korisnik prolazi kroz nadogradnju do protoka oblaka iz DocStage iskustva ili iz otvorenog dokumenta.

- **Data_isLocalCopyOn** - Bulova vrednost koja označava da li je korisnik odlučio da zadrži lokalnu kopiju dokumenta otpremom na lokaciju u oblaku ili da premesti postojeći dokument na lokaciju u oblaku.

- **Data_NewFileType** - apstraktna kategorizacija lokacije nove lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_OriginalFileType** - apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_UploadButtonPressed** - Bulova vrednost koja označava da li je korisnik odlučio da otpremi trenutni dokument na lokaciju u oblaku.

- **Data_UploadError** - numerička vrednost koja ukazuje na vrstu greške do koje je došlo ako operacija slanja ne uspe.

- **Data_UpsellAppearsFromDelegate** - Bulova vrednost koja označava da li je prikaz prikazan iz menija deljenja.

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Podaci u vezi sa obradom pojedinačnog prava administratorski dodeljenog programskog dodatka Office 365 zakupca.

Koristi se za pravljenje grafikona (na zahtev uprave tima) koji prikazuju analizu uspeha i problema korisnika.

Prikupljaju se sledeća polja:

  - **VerzijaAplikacije** - verzija aplikacije koje sadrži programski dodatak.

  - **SolutionId** - GUID koji predstavlja jedinstveni programski dodatak

  - **Id za telemetriju** - GUID koji predstavlja jedinstvenog korisnika

#### <a name="officeextensibilitycatalogexchangeprocessmanifest"></a>Office.Extensibility.Catalog.ExchangeProcessManifest

Podaci u vezi sa obradom pojedinačnog manifesta za administratora dodeljenog O365 programskom dodatku. Koristi se za analizu problema klijenata i izrade grafikona uspešnosti klijenta.
 
Prikupljaju se sledeća polja:

- **AppVersion** - verzija aplikacije

- **IsAllReturnedManifestsParsed** - Bulov označava da smo raščlanili sve vraćene spiskove

- **IsAppCommand** - Bulov označava da li je ovo aplikacija za komande aplikacije 

- **ReturnedManifestsParsed** - prebrojavanje za raščlanjene manifeste

- **SolutionId** - ID Rešenja

- **TelemetryId** – lična telemetrija zasnovana na potpisu identiteta

#### <a name="officeextensibilityodpappcommandsribbonclick"></a>Office.Extensibility.ODPAppCommandsRibbonClick

Prikuplja da li je klik na prilagođenu kontrolu programskog dodatka uspešno ili ne. Koristi se za otkrivanje problema u interakciji korisnika pomoću kontrola programskih dodataka.
 
Prikupljaju se sledeća polja:

- **CommandActionType** - tip komande programski dodatak

- **CommandLabel** - kliknuta je oznaka komande

- **SolutionId** - ID Rešenja

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Omogućava nam da znamo da li se datoteka uspešno otvorila iz FIO sloja. Koristi se za nadgledanje i ispravnost funkcija.

Prikupljaju se sledeća polja:

  - **Grupa aktivnosti -** oznaka koja omogućava da skup događaja za praćenje bude grupisan kako bi upravljao sveukupnim uspehom

  - **Activity.IsHVA -** zastavica koja označava da je događaj ključan za uspeh korisnika

  - **Data.AsyncOpen -** zastavica koja označava da je otvoreno imalo sadržaj koji je stigao posle otvaranja glavnog tela

  - **Data.CacheFileId -** se povezuje sa telemetrijom keša Office dokumenata da omogući analizu uticaja problema sa kešom na korisničko iskustvo
 
  - **Data.CFREnabled** - ukazuje da je za sesiju omogućen CacheFileRuntime.

  - **Data.CFRFailure** - ukazuje da je CacheFileRuntime naišao na grešku.
  
  - **Data.CoauthStatus -** saopštava status saradnje na dokumentu prilikom otvaranja

  - **Data.CountOfMultiRoundTripsDownload -** Broj povratnih putovanja ka serveru koji se koristi za rešavanje problema sa performansama i mrežnih problema

  - **Data.CountOfMultiRoundTripsUpload -** Broj povratnih putovanja ka serveru koji se koristi za rešavanje problema sa performansama i mrežnih problema

  - **Data.DialogId -** Aktivirano ako je dijalog korisničkog interfejsa bio prikazan tokom otvaranja, ukazuje na to da je korisniku prikazana poruka upozorenja

  - **Data.DidFallbackToDAV -** Aktivirano ako je dokument otvoren korišćenjem starije verzije protokola za prenos datoteka

  - **Data.Doc.AccessMode -** Dokument je samo za čitanje/ili može da se uređuje

  - **Data.Doc.AssistedReadingReasons -** Aktivirano ako dokument ima primenjenu elektronsku zaštitu podataka

  - **Data.Doc.AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data.Doc.ChunkingType -** Jedinice koje se koriste za postepeno otvaranje dokumenta

  - **Data.Doc.EdpState -** Postavke elektronske zaštite podataka za dokument

  - **Data.Doc.Ext -** Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

  - **Data.Doc.Extension -** Zastarelo

  - **Data.Doc.FileFormat -** Verzija protokola za format datoteke

  - **Data.Doc.Fqdn -** Ime domena za OneDrive ili SharePoint Online

  - **Data.Doc.FqdnHash -** Jednosmerni heš imena domena koji se može identifikovati

  - **Data.Doc.IdentityTelemetryId -** Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

  - **Data.Doc.IdentityUniqueId -** Zastarelo

  - **Data.Doc.InitializationScenario -** Beleži način na koji je otvoren dokument

  - **Data.Doc.IOFlags -** Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

  - **Data.Doc.IrmRights -** Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

  - **Data.Doc.IsCloudCollabEnabled -** Zastavica koja ukazuje na to da usluga podržava saradnju u oblaku

  - **Data.Doc.IsIncrementalOpen -** Zastavica koja označava da je dokument postepeno otvoren

  - **Data.Doc.IsOcsSupported -** Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

  - **Data.Doc.IsOpeningOfflineCopy -** Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

  - **Data.Doc.IsSyncBacked -** Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

  - **Data.Doc.Location -** Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

  - **Data.Doc.LocationDetails -** Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

  - **Data.Doc.NumberCoAuthors -** Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

  - **Data.Doc.PasswordFlags -** Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

  - **Data.Doc.ReadOnlyReasons -** Razlozi zbog kojih je dokument otvoren samo za čitanje

  - **Data.Doc.ResourceIdHash -** Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data.Doc.ServerDocId -** Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data.Doc.ServerProtocol -** Verzija protokola koji se koristi za komunikaciju sa uslugom

  - **Data.Doc.ServerType -** Tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

  - **Data.Doc.ServerVersion -** Verzija servera koji nudi uslugu

  - **Data.Doc.SessionId -** Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

  - **Data.Doc.SharePointServiceContext -** Informacije o dijagnostici iz zahteva usluge SharePoint Online

  - **Data.Doc.SizeInBytes -** Indikator veličine dokumenta

  - **Data.Doc.SpecialChars -** Indikator specijalnih znakova u URL adresi ili putanji dokumenta

  - **Data.Doc.StorageProviderId -** Zastarelo

  - **Data.Doc.StreamAvailability -** Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

  - **Data.Doc.SyncBackedType -** Indikator tipa dokumenta (lokalni ili iz usluge)

  - **Data.Doc.UrlHash -** Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

  - **Data.Doc.UsedWrsDataOnOpen -** Dijagnostički indikator za postepeno otvaranje dokumenta

  - **Data.Doc.WopiServiceId -** Sadrži jedinstveni identifikator WOPI dobavljača usluge

  - **Data.DocumentLoadEndpoint -** zastareli/suvišni duplikat (Data.Doc.Location i Data.Doc.IsSyncbacked)

  - **Data.DocumentSizeInBytes -** Zastarelo/suvišno, zamenjeno sa Data.Doc. SizeInBytes

  - **Data.DocumentSizeOnDisk -** Zastarelo

  - **Data.DoesBaseHaveContentOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.DownloadFragmentSize -** Veličina podataka koji se šalju u podzahtevu za dijagnostikovanje problema sa mrežom

  - **Data.DsmcStartedTooEarly -** Ukazuje na grešku tokom pokretanja sesije za zajedničko uređivanje

  - **Data.EditorsCount -** Broj drugih saradnika koji uređuju dokument

  - **Data.ExcludedDataThresholdInBytes -** Veličina datoteke potrebna za korišćenje asinhronog otvaranja 

  - **Data.FileIOResult.Code -** keš povratnog kôda poslednjeg otvaranja iz sloja protokola

  - **Data.FileIOResult.Success -** Keš indikatora za poslednje uspešno otvaranje iz sloja protokola

  - **Data.FileIOResult.Code -** Keš oznake greške poslednjeg otvaranja iz sloja protokola

  - **Data.FileIOResult.Code -** Keš tipa greške poslednjeg otvaranja iz sloja protokola

  - **Data.FqdnHash -** Zastarelo, zamenjeno sa Podaci\_Doc\_FqdnHash

  - **Data.FullIError -** keš svih šifri grešaka za otvaranje iz sloja protokola

  - **Data.FullyQualifiedDomainName -** Zastareo, zamenjeno sa Podaci\_Doc\_Fqdn

  - **Data.Input.FileOpenState -** Status koji zahteva aplikacija (Čitanje/ČitanjePisanje, itd.)

  - **Data.Input.OpenAsync -** asinhrono otvaranje na zahtev aplikacije

  - **Data.Input.OpenOfflineCopy -** Otvaranje iz vanmrežne kopije na zahtev programskog dodatka

  - **Data.IOFlags -** Zastarelo

  - **Data.IsBaseBranchEmptyOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.IsCachedHistoricalVersion -** keš sadrži stariju verziju dokumenta

  - **Data.IsDocEnterpriseProtected -** Dokument je zaštićen šifrovanjem (elektronska zaštita dokumenta / EDP)

  - **Data.IsDocInODC -** dokument je ranije otvoren i je već u kešu

  - **Data.IsMapUnMapCase -** Deo statusa keširane datoteke

  - **Data.IsMapUnMapCase.End -** Deo statusa keširane datoteke

  - **Data.IsOfficeHydrationInProgress -** Operati sistem Windows vraća dokument u prethodno stanje iz vanmrežnog skladišta

  - **Data.isOfficeHydrationRequired -** Dokument je trenutno uskladišten van mreže

  - **Data.isOpenFromCollab -** Najnovija kopija dokumenta je preuzeta iz deljene usluge za saradnju

  - **Data.isPendingNameExist -** U toku je preimenovanje dokumenta

  - **Data.IsStubFile -** Dokument još uvek nije sačuvan u usluzi u oblaku

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen -** stanje dokumenta se promenilo, promene su možda stigle dok dokument nije bio otvoren

  - **Data.isTaskCanceledAfterOpenComplete -** Zastarelo

  - **Data.IsWorkingBranchAvailableOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.LicenseStatus** - Podaci o statusu licence proizvoda za potrebe dijagonstike, koriste se za proveru da li su odgovarajuće karakteristike proizvoda omogućene za vrstu korisničke licence 

  - **Top licence za podatke -** Ukazuje na status licence (besplatna/plaćenu ili probnu verziju, itd.)

  - **Lokacija podataka -** Ukazuje na tip medijuma za skladištenje/lokaciju (USB, oblak itd.)

  - **Data.LockRequestDocMode -** Označava da li je dokument dostupan drugima

  - **Data.MyDeferredValue -** Zastarelo

  - **Data.Network.BytesReceived -** Zastarelo

  - **Data.Network.BytesSent -** Zastarelo

  - **Data.Network.ConnectionsCreated -** Zastarelo

  - **Data.Network.ConnectionsEnded -** Zastarelo

  - **Data.OcsDisableReasons -** Razlog zašto usluga deljene saradnje nije dostupna za dokument

  - **Data.OcsHostOnOpen -** Zastavica koja ukazuje na to da će se kontrola prebaciti na uslugu deljene saradnje tokom otvaranja

  - **Data.OpeningOfflineCopy -** Zastavica koja ukazuje na to da će se otvoriti lokalna kopija dokumenta

  - **Data.Partition -** Zastarelo

  - **Data.RequestTime -** Zastarelo

  - **Data.ResourceIdHash -** Zastarelo

  - **Data.ResumedIncrementalOpen -** Zastarelo

  - **Data.RTCEnabled -** pokrenut je protokol za distribuciju brze promene

  - **Data.SaveOnOpen -** promene koje nisu sačuvane u lokalnom dokumentu sačuvane su u usluzi tokom otvaranja

  - **Data.ServerProtocol -** Zastarelo, zamenjeno sa Podaci\_Doc\_ServerProtocol

  - **Data.ServerType -** Zastarelo, zamenjeno sa Podaci\_Doc\_ServerType

  - **Data.ServerVersion -** Zastarelo, zamenjeno sa Podaci\_Doc\_ServerVersion

  - **Data.ServiceId -** Zastarelo, zamenjeno sa Podaci\_Doc\_WopiServiceId

  - **Data.SessionId -** Zastarelo

  - **Data.ShouldSwitchToServerOnly -** lokalna kopija dokumenta ne može se koristiti a verzija sa servera mora da se koristi

  - **Data.SpecialChars -** Zastarelo

  - **Data.StopwatchDuration -** Zastarelo

  - **Data.SyncBackedFileTelemetrySessionId -** Zastarelo

  - **Data.SyncElapsedTime -** Zastarelo

  - **Data.SyncRequestId -** Zastarelo

  - **Data.TestProperty -** Zastarelo

  - **Data.TransitionToHostOnOpen -** zastavica koja ukazuje na to da će se sesija povezati sa uslugom hostinga dokumenta

  - **Data.TransitionToHostOnOpenResult -** status prelaza na uslugu hosta

  - **Data.UseCachedNetworkConnection -** zastavica koja ukazuje na to da li se veza ponovo koristi ili se kreira nova veza

  - **Data.UseClientIdAsSchemaLockId -** korišćenje zastavice za kontrolu nad načinom zaključavanja dokumenta u usluzi

  - **Data.VersionType** - ukazuje na tip verzije trenutno otvorene operacije.

  - **Data.WopiServiceId -** Zastarelo, zamenjeno sa Podaci\_Doc\_WopiServiceId

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

Omogućava nam da znamo da li je datoteka uspešno sačuvana iz FIO sloja. Koristi se za nadgledanje i ispravnost funkcija.

Prikupljaju se sledeća polja:

  - **Grupa aktivnosti -** oznaka koja omogućava da skup događaja za praćenje bude grupisan kako bi upravljao sveukupnim uspehom

  - **Activity.IsHVA -** zastavica koja označava da je događaj ključan za uspeh korisnika

  - **Data.AsyncOpen -** zastavica koja označava da je otvoren dokument sa sadržajem koji je stigao posle otvaranja glavnog tela

  - **Data.BaseDownloadTriggered -** Promena praćenja dijagnostike koja ukazuje na to da je zatražena osnovna verzija dokumenta

  - **Data.BlockAutoUploadReasons -** kodove razloga za blokiran status otpremanja (npr. Automatsko čuvanje je isključeno, dokument je u tranziciji)

  - **Data.BlockUploadDueToFailedSaveAsOverExisting -** Otpremanje je blokirao jer će biti neuspešno pri ponovnom pokušaju

  - **Data.CacheFileId -** se povezuje sa telemetrijom keša Office dokumenata da omogući analizu uticaja problema sa kešom na korisničko iskustvo

  - **Data.ChartType -** Zastarelo

  - **Data.CoAuthStatus -** saopštava status saradnje na dokumentu prilikom čuvanja

  - **Data.CoauthUpdatesContext -** izveštaja o kontekstu (objedinjavanje/postepeno otvaranje)

  - **Data.CountOfMultiRoundTripsDownload -** Broj povratnih putovanja ka serveru koji se koristi za rešavanje problema sa performansama i mrežnih problema

  - **Data.CountOfMultiRoundTripsUpload -** Broj povratnih putovanja ka serveru koji se koristi za rešavanje problema sa performansama i mrežnih problema
  
  - **Data.CFREnabled** - ukazuje da je za sesiju omogućen CacheFileRuntime.

  - **Data.CFRFailure** - ukazuje da je CacheFileRuntime naišao na grešku.

  - **Data.DialogChoice -** Beleži izbor u dijalozima grešaka

  - **Data.DialogId -** Beleži DialogId za sve dijaloge grešaka prikazane tokom čuvanja

  - **Data.Dmc.IsOcsSupported -** Zastarelo

  - **Data.Doc.AccessMode -** Dokument je samo za čitanje

  - **Data.Doc.AssistedReadingReasons -** Aktivirano ako dokument ima primenjenu elektronsku zaštitu podataka

  - **Data.Doc.AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data.Doc.ChunkingType -** Jedinice koje se koriste za postepeno otvaranje dokumenta

  - **Data.Doc.EdpState -** Postavke elektronske zaštite podataka za dokument

  - **Data.Doc.Ext -** Oznaka tipa dokumenta (docx/xlsm/pptx, itd.)

  - **Data.Doc.Extension -** Zastarelo

  - **Data.Doc.FileFormat -** Verzija protokola za format datoteke

  - **Data.Doc.Fqdn -** Ime domena za OneDrive ili SharePoint Online

  - **Data.Doc.FqdnHash -** Jednosmerni heš imena domena koji se može identifikovati

  - **Data.Doc.FqdnHasi -** Zastarelo

  - **Data.Doc.IdentityTelemetryId -** Jednosmerni heš za identitet korisnika koji se koristi za čuvanje

  - **Data.Doc.IdentityUniqueId -** Zastarelo

  - **Data.Doc.IKFlags -** Zastarelo

  - **Data.Doc.InitializationScenario -** Beleži način na koji je otvoren dokument

  - **Data.Doc.IOFlags -** Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

  - **Data.Doc.IrmRights -** Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

  - **Data.Doc.IsCloudCollabEnabled -** Zastavica koja ukazuje na to da aplikacija podržava saradnju u oblaku

  - **Data.Doc.IsIncrementalOpen -** Zastavica koja označava da je dokument postepeno otvoren

  - **Data.Doc.IsOcsSupported -** Zastavica koja ukazuje na to da dokument podržava saradnju u oblaku

  - **Data.Doc.IsOpeningOfflineCopy -** Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

  - **Data.Doc.IsSyncBacked -** Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

  - **Data.Doc.Location -** Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

  - **Data.Doc.LocationDetails -** Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

  - **Data.Doc.NumberCoAuthors -** Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

  - **Data.Doc.PasswordFlags -** Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

  - **Data.Doc.ReadOnlyReasons -** Razlozi zbog kojih je dokument otvoren samo za čitanje

  - **Data.Doc.ResourceIdHash -** Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data.Doc.ServerDocId -** Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data.Doc.ServerProtocol -** Verzija protokola koji se koristi za komunikaciju sa uslugom

  - **Data.Doc.ServerType -** Tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

  - **Data.Doc.ServerVersion -** Verzija servera koji nudi uslugu

  - **Data.Doc.SessionId -** Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

  - **Data.Doc.SharePointServiceContext -** Informacije o dijagnostici iz zahteva usluge SharePoint Online

  - **Data.Doc.SizeInBytes -** Indikator veličine dokumenta

  - **Data.Doc.SpecialChars -** Indikator specijalnih znakova u URL adresi ili putanji dokumenta

  - **Data.Doc.StorageProviderId -** Zastarelo

  - **Data.Doc.StreamAvailability -** Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

  - **Data.Doc.SussionId -** Zastarelo

  - **Data.Doc.SyncBackedType -** Indikator tipa dokumenta (lokalni ili iz usluge)

  - **Data.Doc.UrlHash -** Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

  - **Data.Doc.UsedWrsDataOnOpen -** Dijagnostički indikator za postepeno otvaranje dokumenta

  - **Data.Doc.WopiServiceId -** Sadrži jedinstveni identifikator WOPI dobavljača usluge

  - **Data.DocnReadOnlyReasons -** Zastarelo

  - **Data.DocumentSaveEndpoint -** Zastarelo, zamenjeno sa Podaci\_Dok\_Lokacija

  - **Data.DocumentSaveType -** Vrsta čuvanja (normalno, kreiraj, sačuvaj kao)

  - **Data.DocumentSizeOnDisk -** Zastarelo, zamenjeno sa Podaci\_Dok\_Veličina u bajtovima

  - **Data.DoesBaseHaveContentOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.DstDoc.AccessMode -** Novi dokument je samo za čitanje/ili može da se uređuje

  - **Data.DstDoc.EdpState -** Postavke elektronske zaštite podataka za novi dokument

  - **Data.DstDoc.Extension -** Tip novog dokumenta (docx/xlsm/pptx, itd.)

  - **Data.DstDoc.FileFormat -** Protokol za format datoteke novog dokumenta

  - **Data.DstDoc.Fqdn -** Ime OneDrive ili SharePoint Online domena novog dokumenta

  - **Data.DstDoc.FqdnHash -** Jednosmerni heš imena domena novog dokumenta koji se može identifikovati

  - **Data.DstDoc.IdentityUniqueId -** Zastarelo

  - **Data.DstDoc.IOFlags -** Zastavice keširanih opcija novog dokumenta koje se koriste prilikom otvaranja

  - **Data.Doc.IsOpeningOfflineCopy -** Zastavica koja ukazuje na to je otvorena vanmrežna kopija novog dokumenta

  - **Data.DstDoc.IsSyncBacked -** Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

  - **Data.DstDoc.Location -** Ukazuje na to koja je usluga obezbedila novi dokument (OneDrive, File Server, SharePoint, itd.)

  - **Data.DstDoc.NumberCoAuthors -** Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja novog dokumenta

  - **Data.DstDoc.ReadOnlyReasons -** Razlozi zbog kojih je dokument otvoren samo za čitanje

  - **Data.DstDoc.ResourceIdHash -** Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi sa novim dokumentom

  - **Data.DstDoc.ServerDocId -** Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi sa novim dokumentom

  - **Data.DstDoc.ServerProtocol -** Verzija protokola koji se koristi za komunikaciju sa uslugom prilikom kreiranja novog dokumenta

  - **Data.DstDoc.ServerType -** Tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.) za novi dokument

  - **Data.DstDoc.ServerVersion -** Verzija servera koji nudi uslugu za novi dokument

  - **Data.DstDoc.SessionId -** Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije za novi dokument

  - **Data.DstDoc.SharePointServiceContext -** Informacije o dijagnostici iz zahteva usluge SharePoint Online za novi dokument

  - **Data.DstDoc.SizeInBytes -** Indikator veličine novog dokumenta

  - **Data.DstDoc.UrlHash -** Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta za novi dokument

  - **Data.EditorsCount -** Broj drugih saradnika koji uređuju dokument

  - **Data.FullIError -** keš svih šifri grešaka iz sloja protokola

  - **Data.HasFilteredCategories -** Zastarelo

  - **Data.HasFilteredCategoryNames -** Zastarelo

  - **Data.HasFilteredSeries -** Zastarelo

  - **Data.HasFilteredSeriesNames -** Zastarelo

  - **Data.HasPendingSaveAs -** ukazuje na to da je u toku zahtev Sačuvaj kao/Sačuvaj kopiju 

  - **Data.Input.FileOpenState -** Status koji zahteva aplikacija (Čitanje/ČitanjePisanje, itd.)

  - **Data.Input.FileSaveState -** Status koji zahteva aplikacija (Sačuvaj pri otvaranju, Sačuvaj kao, itd.)

  - **Data.Input.NetworkCost -** ukazuje na tip mreže/vrstu troška (ograničena, ograničena iznad granice, itd.)

  - **Data.Input.OpenAsync -** Zastavica koja ukazuje na to da aplikacija zahteva asinhrono otvaranje 

  - **Data.Input.OpenOfflineCopy -** Zastavica ukazuje na to da aplikacija zahteva otvaranje van mreže

  - **Data.IsCachedHistoricalVersion -** Ukazuje na to da ova keširana datoteka nije najnovija verzija

  - **Data.IsHtml -** Ukazuje na to da je nalepljen tekst u HTML formatu

  - **Data.IsLegacyCode -** Označava da je nalepljen tekst u starom formatu koda

  - **Data.IsLocalOnlyFile -** Označava da je otvorena datoteka samo iz lokalnog skladišta

  - **Data.IsLocalOrSyncBackedFile -** Označava da je datoteka otvorena lokalno i mapirana kroz uslugu

  - **Data.IsMapUnMapCase -** Deo statusa keširane datoteke

  - **Data.isOpenFromCollab -** Označava da je datoteka je otvorena iz deljene usluge za saradnju 

  - **Data.IsStubFile -** Dokument još uvek nije podeljen u usluzi u oblaku

  - **Data.IsSyncBackedFile -** dokument se nalazi u fascikli koja se ažurira putem automatskog sinhronizovanja 

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen -** stanje dokumenta se promenilo, promene su možda stigle dok dokument nije bio otvoren

  - **Data.IsWorkingBranchAvailableOnOpen -** promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Lokacija podataka -** Označava tip medijuma za skladištenje/lokaciju (USB, oblak itd.)

  - **Data.LockRequestDocMode -** Označava da li je dokument dostupan drugima

  - **Data.MruRequestResult -** Zastarelo

  - **Data.NewDataNotAvailableReason -** Zastarelo

  - **Data.OcsDisableReasons -** Ne koristi se za čuvanje

  - **Data.OcsHostOnOpen -** Ne koristi se za čuvanje

  - **Data.Output.FileSaveState -** Status po završetku čuvanja

  - **Data.PivotChart -** Zastarelo

  - **Data.resolveConflictState -** Kodovi razloga za zahtev za rešavanje neusaglašenosti objedinjavanja

  - **Data.RTCEnabled -** pokrenut je protokol za distribuciju brze promene

  - **Data.SaveAsToCurrent -** Označava da će aktivni dokument zameniti postojeću uskladištenu datoteku

  - **Data.ServiceId -** Zastarelo, zamenjeno sa Podaci\_Doc\_WopiServiceId

  - **Data.SessionId -** Zastarelo

  - **Data.SizeInBytes -** Zastarelo, zamenjeno sa Podaci\_Dok\_Veličina u bajtovima

  - **Data.StopwatchDuration -** Zastarelo

  - **Data.SyncBackedFileRequiresOnlineTransition -** Zastavica koja označava da radnju čuvanja privremeno blokira mrežni prelaz

  - **Data.SyncBackedFileSaveOnOpen -** Zastavica koja označava da promene koje su izvršene putem automatskog sinhronizovanja zahtevanju čuvanje po otvaranju

  - **Data.TelemetryId -** Zastarelo

  - **Data.TriggerSaveAfterBaseDownload -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.UploadBlockedDueToCoherencyFailure -** Sačuvaj u usluzi je blokirano do rešavanja neusaglašenih izmena od strane korisnika

  - **Data.UploadBlockedDueToFailedSaveAsOverExisting -** Sačuvaj u usluzi je blokirano zbog neuspelog pokušaja zamene postojeće datoteke

  - **Data.UploadPreemptedForCoherency -** Sačuvaj u usluzi komanda je odbačena pošto korisnik vrši dodatne izmene

  - **Data.UploadPreemptedForSaveAsOverExistingFailure -** Sačuvaj u usluzi komanda je odbačena zbog prethodnog neuspelog izvršavanja komande „Sačuvaj Kao preko postojećeg“

  - **Data.UploadScheduled -** datoteka je spreman za asinhrono prosleđivanje usluzi

  - **Data.UseClientIdAsSchemaLockId -** korišćenje zastavice za kontrolu nad načinom zaključavanja dokumenta u usluzi

  - **Data.WorkingCopySaved -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.ZrtSaveAsforSyncBackedBusinessEnabled -** zastavica koja označava da je brzo čuvanje omogućeno za SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedConsumerEnabled -** zastavica koja označava da je brzo čuvanje omogućeno za SharePoint korisnika

  - **Data.ZrtSaveAsforSyncBackedCTBusinessEnabled -** zastavica koja označava da je brzo čuvanje tipova sadržaja omogućeno za SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedCTConsumerEnabled -** zastavica koja označava da je brzo čuvanje tipova sadržaja omogućeno za SharePoint korisnika

  - **Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled -** zastavica koja označava da je brzo čuvanje metapodataka datoteke omogućeno za SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled -** zastavica koja označava da je brzo čuvanje metapodataka datoteke omogućeno za SharePoint korisnika

#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Prikuplja se kada aplikacija ne uspeva da se pokrene zbog neočekivane greške prilikom pokretanja. Koristi se za praćenje izuzetaka i padova. Pomaže u nadgledanju i otklanjanju grešaka ispravnosti aplikacije.

Prikupljaju se sledeća polja:
- **Datum i vreme** - Vremenska oznaka kada je događaj evidentiran

- **ImeDogađaja** - Ime događaja koji se evidentira

#### <a name="office_firstrun_apple_activationresult"></a>Office_FirstRun_Apple_ActivationResult

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktiviranja pretplate na O365 zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.).

Prikupljaju se sledeća polja:

- **Data_ActivationStatusCollectionTime** – vremenska oznaka

- **Data_ActivationStatusError** – kod greške prilikom aktiviranja.

- **Data_ActivationStatusFlowType** – numerička vrednost koja označava tip toka aktivacije

#### <a name="office_firstrun_apple_activationstatus"></a>Office_FirstRun_Apple_ActivationStatus

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za utvrđivanje ishoda aktiviranja pretplate na O365 zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). Prikupljamo podatke koji sadrže tip aktivacije, vrstu toka (FRE/DocStage/Kupovina) i ID Office usluge licenciranja.

Prikupljaju se sledeća polja:

- **Data_ActivationTypeCollectionTime** – vremenska oznaka

- **Data_ActivationTypeFlowType** – numerička vrednost koja označava tip toka aktivacije

- **Data_ActivationTypeOLSLicense** – identifikator licence

- **Data_ActivationTypeStatus** – kod status aktivacije

#### <a name="office_firstrun_apple_firstruncomplete"></a>Office_FirstRun_Apple_FirstRunComplete

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da li korisnik radi u freemium programu, tip toka koji se pokreće (FRE/DocStage/Kupovina) i tip identiteta (MSA/OrgID). Koristimo ovaj događaj da utvrdimo da li je „Utisak pri prvom pokretanju“ (FRE) dovršen i tip identiteta koji se koristi za prijavu (MSA/OrgID).

Prikupljaju se sledeća polja:

- **Data_FirstRunCompletedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunCompletedFlowType** - kod koji označava tip korisničkog toka koji je dovršen 

- **Data_FirstRunCompletedFreemiumStatus** - kod koji predstavlja status dovršenosti za tok freemium korisnika

- **Data_FirstRunCompletedIdentityType** - tip identiteta korisnika koji je završio tok

#### <a name="office_firstrun_apple_firstrunstart"></a>Office_FirstRun_Apple_FirstRunStart

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“ i tip toka koji se pokreće (FRE/DocStage/Kupovina). Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunStartedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunStartedFlowType** - kod koji označava tip korisničkog toka koji je dovršen 

#### <a name="office_firstrun_apple_firstrunstartedandcompleted"></a>Office_FirstRun_Apple_FirstRunStartedAndCompleted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da li korisnik radi u freemium programu, tip toka koji se pokreće (FRE/DocStage/Kupovina) i tip identiteta (MSA/OrgID). Koristimo ovaj događaj da utvrdimo stanje i efikasnost toka „Utiska pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunCompletedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunCompletedFlowType** - kod koji označava tip korisničkog toka koji je dovršen  

- **Data_FirstRunCompletedFreemiumStatus** - kod koji predstavlja status dovršenosti za tok freemium korisnika

- **Data_FirstRunCompletedIdentityType** - tip identiteta korisnika koji je završio tok

- **Data_FirstRunStartedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok pokrenut

- **Data_FirstRunStartedFlowType** - kod koji označava tip korisničkog toka koji je pokrenut

#### <a name="office_firstrun_apple_inapppurchaseactivationfail"></a>Office_FirstRun_Apple_InAppPurchaseActivationFail

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_ActivationFailCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do neuspeha aktivacije 

- **Data_ActivationFailFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do povezivanja 

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="office_firstrun_apple_inapppurchaseactivationsuccess"></a>Office_FirstRun_Apple_InAppPurchaseActivationSuccess

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_ActivatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do aktivacije 

- **Data_ActivatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do povezivanja 

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="office_firstrun_apple_inapppurchaseassociationfailed"></a>Office_FirstRun_Apple_InAppPurchaseAssociationFailed

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_AppChargedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kom je kupovina naplaćena

- **Data_AppChargedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicationFailedCollectionTime** - vremenska oznaka koja registruje vreme u kojem povezivanje aplikacije nije uspelo

- **Data_AssoicationFailedFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicationFailedResult** - kod koji označava tip uočenog neuspeha

#### <a name="office_firstrun_apple_inapppurchaseassociationsuccess"></a>Office_FirstRun_Apple_InAppPurchaseAssociationSuccess

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_AppChargedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kom je kupovina naplaćena

- **Data_AppChargedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem povezivanje aplikacije nije uspelo

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="office_firstrun_apple_inapppurchasefailures"></a>Office_FirstRun_Apple_InAppPurchaseFailures

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke o ishodu toka kupovine iz aplikacije.

Prikupljaju se sledeća polja:

- **Data_AppStoreFailureFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AppStoreFailureResult** - uočen rezultat neuspeha

- **Data_CancelRequestFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_EventId** - kod koji označava tip uočenog neuspeha

#### <a name="office_firstrun_apple_inapppurchasesattempted"></a>Office_FirstRun_Apple_InAppPurchasesAttempted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje kupovine iz aplikacije i tip SKU-a koji se kupuje (mesečno/godišnje/za kućnu upotrebu/za ličnu upotrebu).

Prikupljaju se sledeća polja:

- **Data_EventId** - kod koji označava tip uočenog rezultata

- **Data_PurchasedClickedOfferType** - tip SKU-a koji se pokušao kupiti

- **Data_PurchaseSuccessfulFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="office_firstrun_apple_inapprestoreattempted"></a>Office_FirstRun_Apple_InAppRestoreAttempted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje obnove u aplikaciji

Prikupljaju se sledeća polja:

- **Data_EventId** - kod koji označava tip ishoda pokušaja

- **Data_RestoreAttemptFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="office_firstrun_apple_inapprestoreattemptfailed"></a>Office_FirstRun_Apple_InAppRestoreAttemptFailed

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje obnove u aplikaciji i njihove povezane tokove i greške.

Prikupljaju se sledeća polja:

- **Data_RestoreButtonFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_RestoredFailedPaymentCancelledFlowType** - kod koji označava tip toka otkazivanja plaćanja koje je izvršeno

- **Data_RestoredFailedUnKnownFlowType** - da li je pokušaj propao zbog sprovođenja neočekivanog toka korisnika

- **Data_RestoredFailedUnKnownResult** - da li je pokušaj propao iz nepoznatih razloga

#### <a name="office_firstrun_apple_macfirstruncompleted"></a>Office_FirstRun_Apple_MacFirstRunCompleted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik prošao kroz „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je „Utisak pri prvom pokretanju“ (FRE) uspešno izveden.

Prikupljaju se sledeća polja:

- **Data_FirstRunCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen.

#### <a name="office_firstrun_apple_macwxpfirstrunstarted"></a>Office_FirstRun_Apple_MacWXPFirstRunStarted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunPanelName** - naziv table sa koje je iskustvo počelo

#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Evidentira se kada korisnik otvori Karticu „Personalnost“. Koristi se za posmatranje kritičnih anomalija u stopama neuspešnih pokretanja Aktivne kartice „Personalnost“.

Prikupljaju se sledeća polja:

- **Data.appContextId** – Slučajno generisani id koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Ime upotrebljene usluge (Kartica profila)

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija.

- **Data.eventId** - Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.exportName** - Ime događaja korisničkog postupka koje ljudi mogu da pročitaju, npr. "OpenedPersonaCard"

- **Data.exportType** - Kategorija događaja za izvoz GDPR zahteva

- **Data.feature** - Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.hostAppRing** – Prsten pomoću kojeg je aplikacija distribuirana

- **Data.OTelJS.Version** - Verzija OTel sistema za evidenciju

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** - Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog 

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** - Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.userPuid** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** – Verzija usluge (Kartica profila)

- **Data.viewType** – Definiše tip prikazane Kartice profila

- **NetworkCost** - Označava tip mreže/vrstu troška (ograničena, ograničena iznad granice, itd.)

- **NetworkCountry** - Poštanski broj zemlje pošiljaoca, na osnovu nepročišćene IP adrese klijenta.

- **Data.properties** – Dodatni metapodaci sakupljeni za svaki događaj na sledeći način.

    - **bandwidthEstimateMbps** - Procena efektivnog propusnog opsega merena u MB/s

    - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId 

    - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId

    - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId 

    - **externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih Kartica „Personalnost“ otvorenih u istoj podsesiji

    - **immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

    - **networkEffectiveType** – Efektivan tip mrežne veze, npr. "Slow-2g online" da bi se identifikovalo da li je korisnik povezan sa Internetom u vreme prikazivanja Kartice „Personalnost“

    - **networkType** – Tip mrežnog povezivanja uređaja koji se koristi

    - **personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene „Personalnosti“ u sesiji

    - **roundTripEstimateMs** - Procenjeni efektivni povratni put trenutne veze izražen u milisekundama

    - **wasOpenedAsCompactCard** – Koristi se za identifikovanje toga da li je kartica prvobitno otvorena kao sažeti prikaz


#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a>Office.Manageability.Client Fetch.PolicyPreChecks

Telemetrija koja je ključna za praćenje neuspeha\\uspeha za proveru valjanosti dobavljanja smernica za oblak. RazlogIzlaska sadrži mapu brojača do uslova predprovere koji nije bio ispunjen.

Prikupljaju se sledeća polja:

  - **Data.ExitReason** – Vrednost brojača koja objašnjava razlog, ukoliko predprovera nije uspela

  - **Data.Log** - Prilagođena poruka evidencije koja označava uspeh ili neuspeh predprovere

#### <a name="officemanageabilityclientfetchandapplypolicy"></a>Office.Manageability.Client.Fetch.AndApplyPolicy

Telemetrija koja je ključna za praćenje neuspeha\\uspeha pokretanja komande za dobavljanje smernica za oblak iz aplikacije. Razlog izlaska sadrži mapu brojača do razloga neuspeha.

Prikupljaju se sledeća polja:

  - **Data.ExitReason** – Vrednost brojača koja objašnjava razlog, ukoliko predprovera nije uspela

  - **Data.Log** - Prilagođena poruka evidencije koja označava uspeh ili neuspeh predprovere


#### <a name="officeonenotenavigationcreatepage"></a>Office.OneNote.Navigation.CreatePage

Kritični signal koji se koristi za nadgledanje sposobnosti korisnika programa OneNote da stvaraju stranice u programu OneNote.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave stranicu, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **IsAtSectionEnd** - Ukazuje na to da li je nova stranica kreirana na kraju odeljka ili ne.

- **IsBlank** – Ukazuje na to da li je nova stranica prazna stranica ili kreirana pomoću predloška.

- **IsRecentsView** - Ukazuje na to da li se stranica kreira iz nedavnih ili ne.

- **NavVieww** – Ukazuje na to da li se stranica kreira iz navigacionog prikaza ili ne.

- **NoteType** – Ukazuje na tip (brza beleška, lista ili fotografija) stranice.

- **QuickNoteType** – Ukazuje na tip (brza beleška, lista ili fotografija) stranice.

- **RailState** – Pokazuje stanje navigacijske šine OneNote navigacije kada pravite stranicu.

- **Trigger** - Pokazuje tačku unosa radnje "Kreiranje stranice".

- **TrigerInfo** – Označava dodatne informacije u vezi sa okidačem.


#### <a name="officeonenotenavigationcreatesection"></a>Office.OneNote.Navigation.CreateSection

Kritični signal koji se koristi za nadgledanje sposobnosti korisnika programa OneNote da stvaraju odeljke u programu OneNote.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave stranicu, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja

- **NotebookID** – Jedinstveni identifikator beležnice.

- **SectionID** – Jedinstveni identifikator odeljka koji je kreiran.

- **Trigger** - Pokazuje tačku unosa radnje "Kreiranje odeljka".

- **TrigerInfo** – Označava dodatne informacije u vezi sa okidačem.


#### <a name="officeonenotenavigationnavigate"></a>Office.OneNote.Navigation.Navigate

Kritični signal koji se koristi za nadgledanje sposobnosti korisnika programa OneNote da se kreću između stranica u programu OneNote.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da se kreću, to bi izazvalo krajnje ozbiljna incident.

Prikupljaju se sledeća polja:

- **FromNotebook** – Jedinstveni identifikator beležnice.

- **FromPage** – Jedinstveni identifikator stranice.

- **FromSection** – Jedinstveni identifikator odeljka.

- **FromSectionGroup** – Jedinstveni identifikator grupe odeljka.

- **IsCurrentUserEduStudent** – Ukazuje na to da li aktuelni korisnik ima studentsku ulogu u beležnici za edukaciju ili ne.

- **IsEduNotebook** – ukazuje na to da li je, ili nije, trenutna stranica u beležnici za obrazovanje.

- **IsEduNotebookReadOnlyPage** – ukazuje na to da li je, ili nije, trenutna stranica samo za čitanje u beležnici za obrazovanje.

- **ToNotebook** – Jedinstveni identifikator beležnice.

- **ToPage** – Jedinstveni identifikator stranice.

- **ToSection** – Jedinstveni identifikator odeljka.

- **ToSectionGroup** – Jedinstveni identifikator grupe odeljka.


#### <a name="officeonenotenotebookmanagementcreatenotebook"></a>Office.OneNote.NotebookManagement.CreateNotebook

Kritični signal koji se koristi za nadgledanje sposobnosti korisnika programa OneNote da stvaraju beležnice u programu OneNote.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave stranicu, to bi izazvalo krajnje ozbiljan incident.

Prikupljaju se sledeća polja:
    
- **NotebookID** – Jedinstveni identifikator beležnice.


#### <a name="officeonenotenotebookmanagementopennotebook"></a>Office.OneNote.NotebookManagement.OpenNotebook

Kritični signal koji se koristi za nadgledanje sposobnosti korisnika programa OneNote da otvaraju beležnice u programu OneNote.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da otvore beležnice, to bi izazvalo ozbiljan incident.

Prikupljaju se sledeća polja:

-  **NotebookID** – Jedinstveni identifikator beležnice.

    
#### <a name="officeonenotesearchsearch"></a>Office.OneNote.Search.Search

ID kritične identifikacije koje se koristi za nadgledanje mogućnosti programa OneNote korisnika za pronalaženje informacija na hiljade stranica i beležnica.   Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da pronađu informacije u beležnicama, to bi izazvalo ozbiljan incident.

Prikupljaju se sledeća polja:

- **PageSearchResultCount** – označava broj rezultata pretrage pronađenih u režimu pretrage stranice.

-  **PageTimeToFirstResultInMs** – označava vreme koje potrebno da bi OneNote pronašao prvo podudaranje u režimu pretrage stranice.
    
-  **PageTimeToLastResultInMs** – označava vreme koje potrebno da bi OneNote pronašao poslednje podudaranje u režimu pretrage stranice.

-  **PageTimeToMedianResultInMs** – označava srednji vremenski period koji je potreban da bi OneNote pronašao sva podudaranja u režimu pretrage stranice.

-  **SearchResultCount** – označava broj pronađenih rezultata pretrage.

-  **TagSearchResultCount** – označava broj rezultata pretrage pronađenih u režimu pretrage stranice.

-  **TagTimeToFirstResultInMs** – označava vreme koje potrebno da bi OneNote pronašao prvo podudaranje u režimu pretrage stranice.

-  **TagTimeToLastResultInMs** – označava vreme koje potrebno da bi OneNote pronašao poslednje podudaranje u režimu pretrage stranice.

-  **TagTimeToMedianResultInMs** – označava vreme koje potrebno da bi OneNote pronašao poslednje podudaranje u režimu pretrage oznaka.

-  **TimeToFirstResultInMs** – označava vreme koje potrebno da bi OneNote pronašao prvo podudaranje.

-  **TimeToLastResultInMs** – označava vreme koje potrebno da bi OneNote pronašao poslednje podudaranje.

-  **TimeToMedianResultInMs** – označava vreme koje potrebno da bi OneNote pronašao sva podudaranja.


#### <a name="officeonenotestickynotesnotecreated"></a>Office.OneNote.StickyNotes.NoteCreated

Ovo je kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji.  Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteCreated radnja koju aktivira korisnik.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenotestickynotesnoteviewed"></a>Office.OneNote.StickyNotes.NoteViewed

Ovo je kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji.  Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **HasImages** - Zastavica koja ukazuje na to da li prikazana beleška sadrži uskladištene slike.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteViewed radnja koju aktivira korisnik.

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ovaj događaj evidentira rezultat sinhronizacije beležnice. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote.
 
Prikupljaju se sledeća polja

- **CachedError_Code** – numerisani ili alfanumerički kod koji se koristi za određivanje prirode keširane greške i/ili zašto se ona dogodila
    
- **CachedError_Description** –opis keširane greške

- **CachedError_Tag** – ukazuje na to gde u kodu se javlja keširana greška

- **CachedError_Type** – tip keširane greške, npr. Win32Error itd.

- **ExecutionTime** - vreme u milisekundama potrebno za kopiranje beležnice

- **Gosid** -globalni ID prostora objekta

- **IdentityType** -tip identiteta, npr. Windows Live, org ID itd.

- **InitialReplicationInSession** – da li je ovo replikacija prve beležnice nakon otvaranja ili ne

- **IsBackgroundSync** – da li je ovo sinhronizacija pozadine ili ne

- **IsCachedErrorSuppressed** -da li je keširana greška potisnuta ili ne

- **IsCachedErrorUnexpected** - da li je keširana greška neočekivana ili ne

- **IsNotebookErrorSuppressed** -da li je greška sinhronizacije beležnice potisnuta ili ne

- **IsNotebookErrorUnexpected**- da li je greška sinhronizacije beležnice neočekivana ili ne

- **IsSectionErrorSuppressed** - da li je greška sinhronizacije odeljka potisnuta ili ne

- **IsSectionErrorUnexpected** – da li je greška sinhronizacije odeljka neočekivana ili ne

- **IsUsingRealtimeSync** – da li sinhronizacija beležnice koristi modernu sinhronizaciju sadržaja stranice ili ne

- **LastAttemptedSync** -vremenska oznaka kada je beležnica pokušavala da se sinhronizuje poslednji put

- **LastBackgroundSync** -vremenska oznaka kada je poslednji put pokušana sinhronizacija najnovijih pozadina

- **LastNotebookViewedDate** – datum kada je beležnica poslednji put prikazana

- **LastSuccessfulSync** – vremenska oznaka kada je beležnica uspešno sinhronizovana ranije

- **NeedToRestartBecauseOfInconsistencies** -da li se sinhronizacija mora ponovo pokrenuti zbog nedoslednosti ili ne

- **NotebookErrorCode** – kôd greške sinhronizovanja nivoa beležnice sačuvan na prostoru za grafiku beležnice

- **NotebookId** – ID beležnice

- **NotebookType** -tip beležnice

- **ReplicatingAgainBecauseOfInconsistencies**-da li se sinhronizacija ponovo pokreće zbog nedoslednosti ili ne

- **SectionError_Code** – numerisani ili alfanumerički kod koji se koristi za određivanje prirode greške u sinhronizaciji odeljka i/ili zašto se ona dogodila

- **SectionError_Description** –opis greške sinhronizacije odeljka

- **SectionError_Tag** – ukazuje na to gde u kodu se javlja greška sinhronizacije odeljka

- **SectionError_Type** – tip greške sinhronizacije odeljka, npr. Win32Error itd.

- **Success** – da li je beležnica uspešno sinhronizovana ili ne

- **SyncDestinationType** -tip odredišnog sinhronizovanja, npr. OneDrive ili SharePoint Online

- **SyncId** – broj jedinstven za svaku sinhronizaciju beležnice

- **SyncWasFirstInSession** –da li je ova sinhronizacija prva sinhronizacija u trenutnoj sesiji

- **SyncWasUserInitiated** -da li je ovu sinhronizaciju pokrenuo korisnik ili ne

- **TenantId** – ID SharePoint zakupca

- **TimeSinceLastAttemptedSync**- vreme od poslednjeg pokušaja sinhronizacije beležnice

- **TimeSinceLastSuccessfulSync** - vreme od poslednje uspešne sinhronizacije beležnice


#### <a name="officeonenotesystemapplifecycleapplaunch"></a>Office.OneNote.System.AppLifeCycle.AppLaunch

Kritični signal koji se koristi da bi se osiguralo da korisnici usluge OneNote mogu uspešno pokrenuti aplikaciju. Telemetrija se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju u prozoru performansi, to bi izazvalo incident velike ozbiljnosti.

Prikupljena su sledeća polja:   Nijedno

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult

Rezultat dodavanja naloga u novi profil u programu Outlook, iz Office Backstage ili iz dijaloga "postavke naloga". Podaci se aktivno nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha.

Prikupljaju se sledeća polja:

  - **RezultatKreiranjaNaloga** – Rezultat (uspeh, neuspeh, otkazivanje, itd.) dodavanja naloga u Outlook.

  - **VremeKreiranjaNaloga** – proteklo vreme pri pokušaju kreiranja naloga

  - **IzborPodatakaNaloga** - izvor postavki za nalog (npr. automatsko otkrivanje, GuessSmart, automatsko otkrivanje itd.)

  - **TipNaloga** – Tip naloga koji se konfiguriše.

  - **HeširanaAdresaEpošte** – heširana adresa e-pošte

  - **ShowPasswordPageFlightEnabled** -indikator koji pokazuje da li je ShowPopImapPasswordPage let omogućen

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult

Rezultat popravke naloga ili promene naprednih postavki naloga. Podaci se aktivno nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Pošto je ovo novo (prerađeno) iskustvo, želimo da budemo sigurni da sve funkcioniše kako treba.

Prikupljaju se sledeća polja:

  - **IzvorInformacijaNaloga** - Izvor informacija naloga za nalog koji se koristi pri pokušaju popravke

  - **TipNaloga** - tip naloga za koji je pokušana popravka

  - **HashedEmailAddress** – heširana adresa e-pošte

  - **ZahtevZaRučnuPopravku** - indikator koji označava da li je postoji zahtev za ručno popravljanje.

  - **Rezultat** - rezultat pokušaja popravke naloga. Na primer: „Uspeh“ ili „Neuspeh\_ČuvanjaIzmenaUNalogu“

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a>Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult

Rezultat ažuriranja lozinke naloga iz padajuće liste „Postavke naloga“. Podaci se aktivno nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Pošto je ovo novo (prerađeno) iskustvo, želimo da budemo sigurni da sve funkcioniše kako treba.

Prikupljaju se sledeća polja:

  - **TipNaloga** - tip naloga za koji je pokušano ažuriranje lozinke

  - **HashedEmailAddress** – heširana adresa e-pošte

  - **Rezultat** - rezultat pokušaja ažuriranja lozinke. Na primer: „Uspeh“ ili „Neuspeh\_Deaktivirana opcija za omogućavanje manje bezbednih aplikacija“


#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Prikuplja rezultat kreiranja nove prodavnice (sa tipom i verzijom), kao i kôd rezultata. Aktivno pratimo ovaj događaj da bismo pratili ispravno funkcionisanje mogućnosti da korisnik sinhronizuje i skladišti e-poštu lokalno, arhivira e-poštu (u PST) ili da koristi grupe.

Prikupljaju se sledeća polja:

  - **Standardna HVA aktivnost** sa prilagođenim korisnim podacima

  - **TipSkladišta** – tip kreiranog skladišta OST ili PST/NST

  - **VerzijaSkladišta** – Verzija kreiranog skladišta Malo/Veliko/Tardis

#### <a name="officeoutlookmacaccountaddworkflow"></a>Office.Outlook.Mac.AccountAddWorkflow

Rezultat dodavanja naloga u programu Outlook. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

Prikupljaju se sledeća polja:

- **AccountConfigMethod** – metod konfigurisanja Naloga

- **AccountType** – Tip naloga koji se konfiguriše.

- **AccountWorkflowSession** – sesiji u kojoj se pokušava izvršiti tok naloga

- **Sessionduration** – trajanje sesije 

- **ThreadId** - identifikator za nit


#### <a name="officeoutlookmacaccountonboardingflow"></a>Office.Outlook.Mac.AccountOnboardingFlow

Rezultat dodavanja naloga u programu Outlook pomoću novog iskustva konfigurisanja naloga. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

Prikupljaju se sledeća polja:

- **AccountConfigAutoSignIn** -Automatska konfiguracija naloga koju je podesio administrator

- **AccountConfigDomain** – domen naveden tokom konfiguracije naloga 

- **AccountConfigEntryPoint** - tačka unosa gde je korisnik uneo konfiguraciju naloga 

- **AccountConfigErrorCode** -kod greške na koji se naišlo tokom konfiguracije naloga 

- **AccountConfigErrorString** -greška na koju se naišlo tokom konfiguracije naloga

- **AccountConfigMethod** – metod konfigurisanja naloga

- **AccountConfigPhase** -aktuelni korak toka posla konfigurisanja naloga

- **AccountConfigPhaseFrom** -početni korak toka posla konfigurisanja naloga 

- **AccountConfigPhaseTo** -poslednji korak toka posla konfigurisanja naloga 

- **AccountType** – tip naloga koji se konfiguriše

- **AccountWorkflowSession** – sesiji u kojoj se pokušava izvršiti tok naloga

- **Sessionduration** – trajanje sesije


#### <a name="officeoutlookmacdeleteaccountusage"></a>Office.Outlook.Mac.DeleteAccountUsage

Rezultat brisanja naloga u programu Outlook. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

Prikupljaju se sledeća polja:

- **AccountType** – tip naloga koji se konfiguriše

- **AccountID** identifikator naloga

- **DeprovisionAccount** – označava da li je nalog uklonjen sa servera

- **IsFastDelete** – označava da li je nalog izbrisan iz pozadinske niti

#### <a name="officepowerpointdocoperationclose"></a>Office.PowerPoint.DocOperation.Close

Prikuplja se kada se zatvore PowerPoint prezentacije. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se odigravaju tokom procesa zatvaranja koji podrazumeva očuvanje i sinhronizovanje korisničkih podataka. Microsoft koristi ove podatke da obezbedili da zatvaranje radi kao što je očekivano i uspešno očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemetryResult:long -** Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Podaci\_Dokument\_\* polja)? Ako ne, zašto?

  - **Podaci\_AutoSaveDisabledReasons:string -** Unapred definisani skup vrednosti zašto je automatsko čuvanje onemogućeno za ovaj dokument? (Objedinjavanje grešaka, čuvanje greške, smernice grupe).

  - **Podaci\_CloseReason:long -** Kako je zatvaranje izvršeno? Zatvaranje dokumenta? Zatvaranje aplikacije?

  - **Podaci\_CppUncaughtExceptionCount:long -** Broj nekontrolisanih izuzetaka

  - **Data\_DetachedDuration:long -** Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

  - **Data\_Doc\_AccessMode:long -** Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType:long -** Kako je dokument uskladišten u sistemu SharePoint

  - **Data\_Doc\_EdpState:long -** Status dokumenta u vezi sa zaštitom podataka preduzeća

  - **Data\_Doc\_Ext:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_Extension:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_FileFormat:long -** Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

  - **Data\_Doc\_Fqdn:string -** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za domene programa Office 365

  - **Data\_Doc\_FqdnHash:string -** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IdentityTelemetryId:string -** Jedinstveni korisnički GUID

  - **Data\_Doc\_IdentityUniqueId:string -** Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

  - **Data\_Doc\_IOFlags:long -** Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

  - **Data\_Doc\_IrmRights:long -** Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool -** Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

  - **Data\_Doc\_IsIncrementalOpen:bool-** Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOcsSupported:bool -** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Proverava da li se dokument otvara iz lokalnog keša

  - **Data\_Doc\_IsSyncBacked:bool -** Proverava da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long -** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string -** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_DocHasStorage:bool -** Da li ovaj dokument ima lokalno skladište?

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez upita za korisnika)?

  - **Podaci\_IsDocAutoSaveable:bool -** Da li se prezentacija može automatski sačuvati?

  - **Podaci\_IsDocDirty:bool -** Da li prezentacija sadrži promene koje još nisu sačuvane?

  - **Podaci\_IsNewDoc:bool -** Da li se radi o novom ili postojećem dokumentu? 

  - **Podaci\_IsRecoveredDoc:bool -** Da li se radi o spasenom dokumentu? (Ako je došlo do pada prethodne sesije, pokazujemo okno za oporavak dokumenta prilikom sledeće sesije)

  - **Podaci\_NewDocDiscarded:bool -** Da li je nova prezentacija odbačena bez čuvanja?

  - **Podaci\_OCSClosingDlgCanceled:bool -** Ako je otpremanje na čekanju na OCS dok korisnik zatvori dokument, pojaviće se dijalog sa porukom korisniku da sačeka. Koju opciju je odabrao korisnik?

  - **Podaci\_OCSClosingDlgExpired:bool -** Da li je isteklo vreme za dijalog (nakon 1 minuta) samo od sebe?

  - **Podaci\_OCSClosingStatus:long -** Koji je konačni status OCS (u CSI, može se zatvoriti, u OCS prelazu, u CSI prelazu, itd.)

  - **Podaci\_OCSClosingWaitDurationMS:long -** Koliko je vremena korisnik morao da čeka na OCS otpremanje?

  - **Podaci\_OCSHandleTransitionResult:long -** Unapred definisan skup vrednosti rezultata prelaza obavljenog tokom zatvaranja (već pokušano, nastavi sa zatvaranjem, itd).

  - **Podaci\_ServerDocId:string -** GUID za jedinstveno identifikovanje dokumenta

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Podaci\_UserContinuedZRTClose:bool -** Kada je prikazan dijalog prilikom zatvaranja, da li je korisnik izabrao da „Nastavi” sa zatvaranjem?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Prikuplja se kada PowerPoint kreira novu prezentaciju. Uključuje metriku za uspeh, neuspeh i performanse.

Ove informacije su potrebne da bismo proverili da li PowerPoint može uspešno da kreira datoteke bez degradacije u performansama.

Prikupljaju se sledeća polja:

  - **TipNovogDokumenta** – Da li je novi dokument kreiran iz predloška ili kreiran prazan?

  - **FLifeguarded** – Da li dokument ima mogućnost samokorigovanja (funkcija koja sama ispravlja greške u dokumentu bez upita za korisnika)?

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Prikuplja se kada PowerPoint otvori prezentacije. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju na kraju procesa otvaranja.

Microsoft koristi te podatke da bi se uverili da funkcija radi kao što je očekivano i ne postoji bilo kakva degradacija pri otvaranju prezentacija.

Prikupljaju se sledeća polja:

  - **Data\_AntiVirusScanMethod:long -** Unapred definisani skup vrednosti za tip antivirusnog skeniranja (IOAV, AMSI, nijedan, itd.)

  - **Data\_AntiVirusScanStatus:long -** Unapred definisani skup vrednosti za antivirusno skeniranje koje se izvršava za svaki otvoreni dokument (nisu otkrivene pretnje, neuspelo, otkriven je malver, itd.)

  - **Podaci\_CloseAndReopen:bool -** Da li je ovaj dokument zatvoren i ponovo otvoren?

  - **Data\_DetachedDuration:long -** Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

  - **Data\_Doc\_AccessMode:long -** Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType:long -** Kako je dokument uskladišten u sistemu SharePoint

  - **Data\_Doc\_EdpState:long -** Status dokumenta u vezi sa zaštitom podataka preduzeća

  - **Data\_Doc\_Ext:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_Extension:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_FileFormat:long -** Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

  - **Data\_Doc\_Fqdn:string -** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za domene programa Office 365

  - **Data\_Doc\_FqdnHash:string -** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IdentityTelemetryId:string -** Jedinstveni korisnički GUID

  - **Data\_Doc\_IdentityUniqueId:string -** Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

  - **Data\_Doc\_IOFlags:long -** Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

  - **Data\_Doc\_IrmRights:long -** Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool -** Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

  - **Data\_Doc\_IsIncrementalOpen:bool-** Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOcsSupported:bool -** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Da li se dokument otvara iz lokalnog keša?

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long -** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string -** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_ExecutionCount:long -** Koliko puta se izvršava IncOpen protokol pre izvršavanja ovog protokola (OpenComplete)

  - **Data\_FailureComponent:long -** Unapred definisani skup vrednosti za komponentu koja je izazvala neuspeh protokola (neusaglašenost, CSI, unutrašnja, itd.)

  - **Data\_FailureReason:long -** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data_FullDownloadRoundTripCount: Long –** Broj povratnih odziva servera potrebnih za preuzimanje celog dokumenta.
  
  - **Data_IsProtocolRunInIncOpenMode: Bool –** Da li je protokol bio pokrenut za postepeno preuzimanje u kome su delovi dokumenta preuzeti nakon što je dokument prvobitno prikazan korisniku.

  - **Podaci\_MethodId:long -** Interno koji red koda je poslednji koji se izvršio

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Podaci\_TimeToEdit:long -** Koliko vremena je bilo potrebno da bi dokument stekao mogućnost uređivanja

  - **Podaci\_TimeToView:long -** Vreme utrošeno za prikaz prvog slajda dokumenta

  - **Podaci\_UnhandledException:bool -** Da li je bilo nekontrolisanih izvornih izuzetaka?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Prikuplja se kad god PowerPoint vrši čuvanje pomoću moderne putanje kôda. Uključuje rezultat tipa uspeh ili neuspeh za metriku performansi pri čuvanju i odgovarajuće metapodatke dokumenta.  Greške pri čuvanju mogu dovesti do gubitka podataka. Microsoft koristi ove podatke da obezbedi da funkcija radi kao što je očekivano i da se uspešno vrši očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemetryResult:long -** Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Podaci\_Dokument\_\* polja)? Ako ne, zašto?

  - **Podaci\_BeforeSaveEvent:long -** Vreme utrošeno da se podigne dokument pre događaja čuvanja

  - **Podaci\_CheckDownRevSaveTimeMS:long -** Vreme utrošeno za proveru revizije

  - **Podaci\_CheckMacroSaveTimeMS:long -** Vreme utrošeno za čuvanje makroa

  - **Podaci\_ClearAutoSaveTimeMS:long -** Vreme utrošeno da se ukloni zastavica za automatsko čuvanje

  - **Podaci\_ClearDirtyFlagTimeMS:long -** Vreme utrošeno da se ukloni zastavica za nesređeni dokument

  - **Podaci\_CloneDocumentTimeMS:long -** Vreme utrošeno na kloniranje dokumenta pre početka čuvanja

  - **Podaci\_CommitTransactionTimeMS:long -** Vreme utrošeno da se izvrši transakcija čuvanja

  - **Data\_CppUncaughtExceptionCount:long -** Neuhvaćeni izvorni izuzeci dok je aktivnost pokrenuta

  - **Data\_DetachedDuration:long -** Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

  - **Data\_Doc\_AccessMode:long -** Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType:long -** Kako je dokument uskladišten u sistemu SharePoint

  - **Data\_Doc\_EdpState:long -** Status dokumenta u vezi sa zaštitom podataka preduzeća

  - **Data\_Doc\_Ext:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_Extension:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_FileFormat:long -** Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

  - **Data\_Doc\_Fqdn:string -** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za domene programa Office 365

  - **Data\_Doc\_FqdnHash:string -** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IdentityTelemetryId:string -** Jedinstveni korisnički GUID

  - **Data\_Doc\_IdentityUniqueId:string -** Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

  - **Data\_Doc\_IOFlags:long -** Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

  - **Data\_Doc\_IrmRights:long -** Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool -** Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

  - **Data\_Doc\_IsIncrementalOpen:bool-** Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOcsSupported:bool -** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Proverava da li se dokument otvara iz lokalnog keša

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long -** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string -** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_DurationUAEOnSaveStartedMs:long -** Vreme potrebno za izlaz iz nepoznate aplikacije tokom čuvanja

  - **Podaci\_EnsureSaveTransactionTimeMS:long -** Vreme potrebno da se obezbedi kreiranje transakcije čuvanja ako već ne postoji

  - **Data\_FailureComponent:long -** Unapred definisani skup vrednosti za komponentu koja je izazvala neuspeh protokola (neusaglašenost, CSI, unutrašnja, itd.)

  - **Data\_FailureReason:long -** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez upita za korisnika)?

  - **Podaci\_HandleEnsureContentType:long -** Vreme potrebno da se obezbedi ispravnost svih tipova sadržaja

  - **Podaci\_HandleEnsureContentTypeTimeMS:long -** Vreme potrebno da se obezbedi ispravnost svih tipova sadržaja

  - **Podaci\_HasEmbeddedFont:bool -** Da li ovaj dokument sadrži ugrađene fontove?

  - **Podaci\_InitializeSaveTimeMS:long -** Vreme potrebno da se pokrene sadržaj dokumenta da bi započelo čuvanje

  - **Podaci\_InOCSTransition:bool -** Da li se ovo čuvanje vrši za prelaz u OCS

  - **Podaci\_IsSavingWithEmbeddedFont:bool -** Da li ovaj dokument sadrži ugrađene fontove?

  - **Podaci\_MethodId:long -** Interno koji red koda je poslednji koji se izvršio

  - **Podaci\_PerformEmbedFontsTimeMS:long -** Vreme potrebno za serijalizovanje ugrađenih fontova

  - **Podaci\_PerformModernSaveTimeMS:long -** Vreme potrebno za izvršavanje modernog čuvanja (novi kôd)

  - **Podaci\_PerformPostSaveTimeMS:long -** Vreme potrebno za izvršavanje funkcija po obavljanju čuvanja (obaveštenja, Opozovi stavke)

  - **Podaci\_PrepareForSaveTimeMS:long -** Vreme potrebno za pokretanje procesa čuvanja

  - **Podaci\_RaiseDocumentBeforeSaveEventTimeMS:long -** Vreme potrebno za podizanje BeforeSave događaja

  - **Podaci\_ReflectDocumentChangeTimeMS:long -** Vreme potrebno za prikaz sačuvanih promena u korisničkom interfejsu (ponovno popunjavanje sličica itd.)

  - **Podaci\_ReportStartTimeMS:long -** Vreme potrebno da se završi pokretanje telemetrije za čuvanje

  - **Podaci\_ReportSuccessTimeMS:long -** Vreme potrebno da se završi izveštavanje o uspešno obavljenom čuvanju

  - **Podaci\_ResetDirtyFlagOnErrorTimeMS:long -** Vreme potrebno da se poništi zastavica za nesačuvani dokument prilikom greške 

  - **Podaci\_SaveReason:long -** Unapred definisan skup vrednosti zašto je ovo čuvanje izvršeno? (Automatsko čuvanje, ToOCSTransitionSave, ToCSITransitionSave itd.)

  - **Podaci\_SaveType:long -** Unapred definisan skup vrednosti za tip čuvanja (sačuvaj kao, objavi, ručno, OMSave itd.)

  - **Podaci\_SavingWithFont:bool-** Da li čuvamo dokument sa novim ugrađenim fontovima?

  - **Podaci\_ScrubClonedDocumentTimeMS:long -** Vreme potrebno za uklanjanje ličnih podataka u kloniranoj kopiji dokumenta

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Podaci\_TransactionType:long -** Da li se radi o čuvanju ili transakciji „Objedini i sačuvaj“?

#### <a name="officepowerpointdocoperationsaveas"></a>Office.PowerPoint.DocOperation.SaveAs

Prikuplja se kad god PowerPoint izvršava komandu „Sačuvaj kao“ Uključuje rezultat tipa uspeh ili neuspeh za metriku performansi pri čuvanju i odgovarajuće metapodatke dokumenta. Greške pri čuvanju mogu dovesti do gubitka podataka.  Microsoft koristi ove podatke da obezbedi da funkcija radi kao što je očekivano i da se uspešno vrši očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemetryResult:long** - Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Data_Doc_* fields)? Ako ne, zašto?

- **Data_CppUncaughtExceptionCount:long** - Neuhvaćeni izvorni izuzeci dok je aktivnost pokrenuta

- **Data_DetachedDuration:long**- Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

- **Data_DstDoc_AccessMode:long**- Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

- **Data_DstDoc_AssistedReadingReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_DstDoc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_DstDoc_ChunkingType:long** - Kako je dokument uskladišten u sistemu SharePoint

- **Data_DstDoc_EdpState:long** - Status dokumenta u vezi sa zaštitom podataka preduzeća

- **Data_DstDoc_Ext:string** - Oznaka tipa dokumenta

- **Data_DstDoc_Extension:string** - Oznaka tipa dokumenta

- **Data_DstDoc_FileFormat:long** - Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

- **Data_DstDoc_Fqdn:string** - Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene
    
- **Data_DstDoc_FqdnHash:string** - Heš mesta gde je uskladišten dokument

- **Data_DstDoc_IdentityTelemetryId:string** - Jedinstveni korisnički GUID

- **Data_DstDoc_IdentityUniqueId:string** - Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

- **Data_DstDoc_IOFlags:long** - Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_DstDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)
    
- **Data_DstDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_DstDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_DstDoc_IsOcsSupported:bool** - Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_DstDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_DstDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju
    
- **Data_DstDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_DstDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_DstDoc_NumberCoAuthors:long** - Broj koautora u trenutku otvaranja dokumenta

- **Data_DstDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_DstDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_DstDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_DstDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_DstDoc_ServerVersion:long** - proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_DstDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_DstDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_DstDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_DstDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_DstDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_DstDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_DstDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_DstDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_DstDoc_WopiServiceId:string** - WOPI Service Identifier, na primer "Dropbox"

- **Data_FileType:long** - Unapred definisan skup vrednosti internog tipa datoteke

- **Data_fLifeguarded:bool** - Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

- **Data_FWebCreated:bool** - Da li ovaj dokument ima WebCreator zastavicu?

- **Data_SaveReason:long** - Unapred definisan skup vrednosti zašto je ovo čuvanje izvršeno? (Automatsko čuvanje, ToOCSTransitionSave, ToCSITransitionSave, itd.)

- **Data_SaveType:long** -Unapred definisan skup vrednosti za tip čuvanja (sačuvaj kao, objavi, ručno, OMSave itd.) 

- **Data_SrcDoc_AccessMode:long** - Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

- **Data_SrcDoc_AssistedReadingReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_SrcDoc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_SrcDoc_ChunkingType:long** - Kako je dokument uskladišten u sistemu SharePoint 

- **Data_SrcDoc_EdpState:long** - Status dokumenta u vezi sa zaštitom podataka preduzeća

- **Data_SrcDoc_Ext:string** - Oznaka tipa dokumenta

- **Data_SrcDoc_Extension:string** - Oznaka tipa dokumenta

- **Data_SrcDoc_FileFormat:long** - Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

- **Data_SrcDoc_Fqdn:string** - Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene

- **Data_SrcDoc_FqdnHash:string** - Heš mesta gde je uskladišten dokument

- **Data_SrcDoc_IdentityTelemetryId:string** - Jedinstveni GUID korisnika

- **Data_SrcDoc_IdentityUniqueId:string** - Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

- **Data_SrcDoc_IOFlags:long** - Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_SrcDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_SrcDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_SrcDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_SrcDoc_IsOcsSupported:bool** - Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_SrcDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_SrcDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_SrcDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike itd.)

- **Data_SrcDoc_NumberCoAuthors:long** - Broj koautora u trenutku otvaranja dokumenta

- **Data_SrcDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_SrcDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_SrcDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_SrcDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_SrcDoc_ServerVersion:long** - proverava da li je server baziran na Office14, Office15 ili Office16 DataSrcDocSessionId:long generiše GUID koji identifikuje instancu dokumenta u okviru iste sesije procesa

- **Data_SrcDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_SrcDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_SrcDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_SrcDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_SrcDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_SrcDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_SrcDoc_WopiServiceId:string** - WOPI Service identifikator, na primer"Dropbox"

- **Data_StopwatchDuration:long** - Ukupno vreme aktivnosti

- **Data_TypeOfSaveDialog:long** - unapred definisani skup vrednosti dijaloga (RUN_SAVEAS_DLG,RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **DstDoc -** Nova lokacija dokumenta 

- **SrcDoc -** Prvobitna lokacija dokumenta


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Prikuplja se kad god PowerPoint vrši čuvanje pomoću zastarele putanje kôda. Uključuje rezultat tipa uspeh ili neuspeh za metriku performansi pri čuvanju i odgovarajuće metapodatke dokumenta.  Greške pri čuvanju mogu dovesti do gubitka podataka.  Microsoft koristi ove podatke da obezbedi da funkcija radi kao što je očekivano i da se uspešno vrši očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemetryResult:long** - Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Data_Doc_* fields)? Ako ne, zašto?

- **Data_CppUncaughtExceptionCount:long** - Neuhvaćeni izvorni izuzeci dok je aktivnost pokrenuta

- **Data_DetachedDuration:long**- Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

- **Data_Doc_AccessMode:long**- Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

- **Data_Doc_AssistedReadingReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType:long** - Kako je dokument uskladišten u sistemu SharePoint

- **Data_Doc_EdpState:long** - Status dokumenta u vezi sa zaštitom podataka preduzeća

- **Data_Doc_Ext:string** - Oznaka tipa dokumenta

- **Data_Doc_Extension:string** - Oznaka tipa dokumenta

- **Data_Doc_FileFormat:long** - Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

- **Data_Doc_Fqdn:string** - Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene

- **Data_Doc_FqdnHash:string** - Heš mesta gde je uskladišten dokument

- **Data_Doc_IdentityTelemetryId:string** - Jedinstveni GUID korisnika

- **Data_Doc_IdentityUniqueId:string** - Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

- **Data_Doc_IOFlags:long** - Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_Doc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_Doc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_Doc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_Doc_IsOcsSupported:bool** - Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_Doc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_Doc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_Doc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_Doc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_Doc_NumberCoAuthors:long** - Broj koautora u trenutku otvaranja dokumenta

- **Data_Doc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_Doc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_Doc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_Doc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_Doc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI) 

- **Data_Doc_ServerVersion:long** - proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_Doc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_Doc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_Doc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_Doc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_Doc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_Doc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_Doc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_Doc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_Doc_WopiServiceId:string** - WOPI Service identifikator, na primer "Dropbox"

- **Data_DstDoc_AccessMode:long**- Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

- **Data_DstDoc_AssistedReadingReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_DstDoc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_DstDoc_ChunkingType:long** - Kako je dokument uskladišten u sistemu SharePoint

- **Data_DstDoc_EdpState:long** - Status dokumenta u vezi sa zaštitom podataka preduzeća

- **Data_DstDoc_Ext:string** - Oznaka tipa dokumenta

- **Data_DstDoc_Extension:string** - Oznaka tipa dokumenta

- **Data_DstDoc_FileFormat:long** - Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

- **Data_DstDoc_Fqdn:string** - Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene
    
- **Data_DstDoc_FqdnHash:string** - Heš mesta gde je uskladišten dokument

- **Data_DstDoc_IdentityTelemetryId:string** - Jedinstveni korisnički GUID

- **Data_DstDoc_IdentityUniqueId:string** - Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

- **Data_DstDoc_IOFlags:long** - Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_DstDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_DstDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_DstDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_DstDoc_IsOcsSupported:bool** - Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_DstDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_DstDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_DstDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_DstDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_DstDoc_NumberCoAuthors:long** - Broj koautora u trenutku otvaranja dokumenta

- **Data_DstDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_DstDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje itd.)

- **Data_DstDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_DstDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_DstDoc_ServerVersion:long** - proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_DstDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_DstDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_DstDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_DstDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_DstDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_DstDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_DstDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_DstDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_DstDoc_WopiServiceId:string** - WOPI Service Identifier, na primer "Dropbox"

- **Data_FileType:long** - Unapred definisan skup vrednosti internog tipa datoteke

- **Data_fLifeguarded:bool** - Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

- **Data_SaveReason:long** - Unapred definisan skup vrednosti zašto je ovo čuvanje izvršeno? (Automatsko čuvanje, ToOCSTransitionSave, ToCSITransitionSave itd.)

- **Data_SaveType:long** - Unapred definisan skup vrednosti za tip čuvanja (sačuvaj kao, objavi, ručno, OMSave itd.)

- **Data_SrcDoc_AccessMode:long** - Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

- **Data_SrcDoc_AssistedReadingReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_SrcDoc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_SrcDoc_ChunkingType:long** - Kako je dokument uskladišten u sistemu SharePoint

- **Data_SrcDoc_EdpState:long** - Status dokumenta u vezi sa zaštitom podataka preduzeća

- **Data_SrcDoc_Ext:string** - Oznaka tipa dokumenta

- **Data_SrcDoc_Extension:string** - Oznaka tipa dokumenta

- **Data_SrcDoc_FileFormat:long** - Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

- **Data_SrcDoc_Fqdn:string** - Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene

- **Data_SrcDoc_FqdnHash:string** - Heš mesta gde je uskladišten dokument 

- **Data_SrcDoc_IdentityTelemetryId:string** - Jedinstveni GUID korisnika

- **Data_SrcDoc_IdentityUniqueId:string** - Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

- **Data_SrcDoc_IOFlags:long** - Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_SrcDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)
    
- **Data_SrcDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_SrcDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_SrcDoc_IsOcsSupported:bool** - Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_SrcDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_SrcDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_SrcDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_SrcDoc_NumberCoAuthors:long** - Broj koautora u trenutku otvaranja dokumenta

- **Data_SrcDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_SrcDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_SrcDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_SrcDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_SrcDoc_ServerVersion:long** - proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_SrcDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_SrcDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_SrcDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_SrcDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_SrcDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_SrcDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_SrcDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_SrcDoc_WopiServiceId:string** - WOPI Service identifikator, na primer"Dropbox"

- **Data_StopwatchDuration:long** - Ukupno vreme aktivnosti

- **Data_TypeOfSaveDialog:long** - unapred definisani skup vrednosti dijaloga (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Doc** - trenutni dokument za čuvanje

- **DstDoc**- Nova lokacija dokumenta (u slučaju opcije „Sačuvaj kao“)

- **SrcDoc**- Prvobitna lokacija dokumenta (u slučaju opcije „Sačuvaj kao“)

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Sakuplja svaki put kada se dovrši PDF operacija i sadrži informacije o uspešnosti operacije. Ove informacije su važne za identifikovanje uspešnog izvoza PDF operacija za našu aplikaciju.

Prikupljaju se sledeća polja:

- **Data_ExportAsPDFSucceed** – Boolean označava da li je uspeh izvoza kao PDF bio uspešan.


#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Uzimanje kvarova tokom projekcije slajdova kao ključne funkcije za PowerPoint. Microsoft korporacija prikuplja podatke o tome kada se greška događa tokom projekcije slajdova u cilju poboljšanja iskustva korisnika pri projekciji slajdova. Microsoft korporacija koristi te podatke da sakupi dijagnostičke informacije o tome gde dolazi do greške dok korisnik koristi projekcije slajdova

Prikupljaju se sledeća polja:

- **CountOArtErrors** – ukupan broj OArt grešaka

- **CountOtherErrors** – ukupan broj drugih grešaka

- **CountPPTErrors** – ukupan broj PPT grešaka

- **CountSlideShowErrors** – ukupan broj grešaka tokom projekcije slajdova

- **FirstOArtError** - prva greška koja se desila u OArt

- **FirstOtherError** - prva greška koja se desila u drugoj oblasti

- **FirstPPTError** - prva greška koja se desila u PPT

- **FirstSlideShowError** -prva greška koja se desila tokom projekcije slajdova

    
#### <a name="officepowerpointrunprintoperation"></a>Office.PowerPoint.RunPrintOperation

Sakuplja svaki put kada se dovrši PDF operacija i sadrži informacije o tipu rasporeda, upotrebi brojeva slajda kao i uspešnosti operacije. Ove informacije su važne za identifikovanje uspešnog štampanja PDF operacija za našu aplikaciju.

Prikupljaju se sledeća polja:

- **Data_PrintWithSlideNumbers** -Boolean ukazuje na to da li korisnik štampa sa brojevima slajda.

- **Data_SavePrintLayoutType** – tip rasporeda štampanja u trenutku pokretanja operacije "Štampanje" ili "izvoz".

- **Data_Success** -Boolean označava da li je štampanje uspešno.


#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Projekat će sačuvati datoteku. Ovaj događaj označava čuvanje projekta. On omogućava Microsoft korporaciji da izmeri uspeh čuvanja datoteke projekta što je važno da bi se izbegao gubitak podataka u dokumentu.

Prikupljaju se sledeća polja:

  - **Podaci\_TriggerTime** – vreme izvršenog čuvanja

  - **Podaci\_Tip datoteke** - tip datoteke koji se koristi za čuvanje projekta
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

Omogućava nam da znamo kada je pokrenuta sesija protoka podataka.  Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Ime_Aktivnosti** - ime aktivnosti „Sesija“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Početak

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Omogućava nam da znamo kada je zaustavljena sesija protoka podataka. Koristi se za ispravnost funkcija i nadgledanje. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Ime_Aktivnosti** - ime aktivnosti „Sesija“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Zaustavljanje

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

Omogućava nam da znamo da li je početak protoka izvora podataka uspešan.   Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Activity_Name** - Ime aktivnosti „ProtokPodatakaUređaja“ ili „ProtokPodatakaDatoteke“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Početak

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

Omogućava nam da znamo da li je zaustavljanje protoka izvora podataka uspešno.   Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Activity_Name** - Ime aktivnosti „ProtokPodatakaUređaja“ ili „ProtokPodatakaDatoteke“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Zaustavljanje

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a>Office.TargetedMessaging.ABExperimentMessageTrigger

Prati broj korisnika koji prima „BizBar“ i „Dinamičko platno“ poruke iz „Usluge ciljane razmene poruka“ (TMS). Ovi podaci su od ključni za razumevanje koje poruke korisnici dobijaju i na kojoj površini tako da možemo biti sigurni da korisnici neće propustiti poruke koje mogu biti od presudnog značaja za njihovu dalju upotrebu proizvoda. Takođe su neophodni za precizno merenje uspeha eksperimenta i kampanje koje se izvršavaju kroz TMS.

Prikupljaju se sledeća polja:

  - **Podaci\_Površina** – Ime površine za koju je namenjena poruka isporučena putem ove usluge

  - **Podaci\_Letovi** – ECS/CT identifikator leta koji je korišćen da isporuči ovu poruku

  - **Podaci\_IdKampanje** – identifikator kampanje kojoj pripada ova poruka

  - **Podaci\_IdPoruke** – identifikator poruke isporučene putem ove usluge

  - **Podaci\_IdTransakcije** – identifikator ove transakcije sa uslugom

  - **Podaci\_TačkaAktivacije** – korak u kome je ovaj događaj evidentiran (primljena poruka u odnosu na prikazanu poruku)

#### <a name="officetextfontpickerfontselectedwin32"></a>Office.Text.FontPickerFontSelected.Win32

Ovaj događaj označava da li je preuzeti font ispravno prikazan. Koristi se za označavanje uspelog ili neuspelog preuzimanja fontova.

Prikupljaju se sledeća polja:

  - **Ime fonta (Podaci\_fonta)** – ime izabranog fonta u biraču fonta

  - **Klik korisnika (Podaci\_FKlick)** – da li je korisnik koristio miša da izabere stavku

#### <a name="officetextresourceclientrequestresourceinternal"></a>Office.Text.ResourceClient.RequestResourceInternal

Ovaj događaj označava da li je font ispravno preuzet. Koristi se za označavanje uspelog ili neuspelog prikazivanja preuzetog fonta.

Prikupljaju se sledeća polja:

  - **Podaci\_FontToken** - ime resursa datoteke će se sačuvati kao

  - **Podaci\_HTTPRezultat** - rezultat HTTP zahteva

  - **Podaci\_Šifra HTTP statusa** - Povratni HTTP kôd kao odgovor na HTTP zahtev

  - **Podaci\_isInternetOn** – Da li smo imali vezu pri pokušaju preuzimanja resursa

  - **Podaci\_UrlZahteva** - URL adresa CDN resursa kojeg pokušavamo da preuzmemo



#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Prikuplja uspešno ili neuspešno izvršeno prevođenje celog dokumenta pokrenutog od strane korisnika pomoću Translator SDX. Ovo je od presudnog značaja za proveru ispravnosti funkcije prevođenja i omogućava nam da reagujemo na sve prekide do kojih može doći. Nadgledanje ispravnosti „Prevedi dokument” scenarija u programu Word.

Prikupljaju se sledeća polja:

- **Data.actionSource**- Kako je aktiviran izbor za prevođenje-

- **Data.bodyBackgroundColor **- Boja pozadine Office teme

- **Data.bodyForegroundColor** - Boja prednjeg plana Office teme

- **Data.browserLang **- Trenutni jezika prikaza u pregledaču

- **Data.browserOnline **- Zastarelo

- **Data.browserPlatform** - Platforma pregledača

- **Data.browserUserAgent** - Korisnički agent pregledača

- **Data.colorDepth** - Dubina boja sistema

- **Data.contentLanguage** - Otkriveni jezik sadržaja za prevođenje

- **Data.controlBackgroundColor** - Boja pozadine kontrole Office teme

- **Data.controlForegroundColor**- Boja prednjeg plana kontrole Office teme

- **Data.correlationId** - Jedinstveni identifikator zahteva koji je poslat usluzi

- **Data.crossSessionId** - Jedinstveni identifikator korisnika

- **Data.crossSessionStartTime** - UTC vremenska oznaka za vreme početka sesije prevođenja

- **Data.currentTime**- UTC vremenska oznaka za vreme slanja ove telemetrijske poruke

- **Data.displayLanguage**- Jezik prikaza sistema Office

- **Data.documentSourceLang**- Jezik sadržaja dokumenta-

- **Data.documentTargetLang**- Jezik na koji se prevodi dokument

- **Data.environment**- Okruženje usluge kojoj je zahtev poslat

- **Data.errorMessage**- Poruka o grešci koju je prijavila usluga

- **Data.eventActionType** - Tip telemetrijskog događaja

- **Data.eventTagId**- Jedinstveni identifikator reda koda koji je napravio ovo telemetrijsku poruku

- **Data.flights**- Omogućeni letovi

- **Data.fileSize**- Veličina Word datoteke za prevod-

- **Data.fileSource**- Gde se hostuje Word datoteka (van mreže, na mreži)-

- **Data.fileType**- Oznaka tipa Word datoteke

- **Data.innerHeight**- Visina kontejnera bočnog okna

- **Data.innerWidth"**- Širina kontejnera bočnog okna

- **Data.lookupSourceLang**- Ne koristi se za prevođenje dokumenta-

- **Data.lookupTargetLang**- Ne koristi se za prevođenje dokumenta-

- **Data.officeHost**- Office aplikacija koja sadrži bočno okno

- **Data.officeLocale**- Korisnički jezik sistema Office

- **Data.officeMachineId**- Jedinstveni identifikator uređaja

- **Data.officePlatform**- Platforma uređaja

- **Data.officeSessionId**- Identifikator Office sesije

- **Data.officeUserId**- Jedinstveni identifikator Office korisnika

- **Data.officeVersion**- Verzija sistema Office

- **Data.pageXOffset** - Horizontalna pozicija pomeranja bočnog okna u odnosu na levu stranu okna

- **Data.pageYOffset**- Vertikalna pozicija pomeranja bočnog okna u odnosu na gornju stranu okna

- **Data.pixelDepth**- Rezolucija boje ekrana

- **Data.responseCode** - Zatraži kod odziva od usluge

- **Data.responseTime**- Zatraži proteklo vreme 

- **Data.resultType**- Zatraži rezultat

- **Data.screenHeight**- Visina ekrana u pikselima

- **Data.screenLeft**- Horizontalna koordinata prozora u odnosu na ekran

- **Data.screenLeft**- Vertikalna koordinata prozora u odnosu na ekran

- **Data.screenWidth**- Širina ekrana u pikselima

- **Data.selectedTab**- Koja je kartica izabrana, „Izbor“ ili „Dokument“

- **Data.serverUrl**- URL adresa usluge prevođenja

- **Data.sessionId**- Identifikator sesije bočnog okna

- **Data.sessionStartTime**- UTC vremenska oznaka za vreme početka sesije prevođenja

- **Data.sourceTextHash**- Heš teksta koji treba da se prevede

- **Data.sourceTextLength**- Dužina teksta koji treba da se prevede

- **Data.sourceTextWords** – Broj reči u tekstu koji treba da se prevede

- **Data.warningMessage**- Poruka upozorenja koju je prijavila usluga


#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Prikuplja uspešno ili neuspešno izvršeno prevođenje izabranog dela dokumenta koje korisnik pokreće u Translator SDX. Ovo je od presudnog značaja za proveru ispravnosti funkcije prevođenja i omogućava nam da reagujemo na sve prekide do kojih može doći. Koristi se za praćenje ispravnosti scenarija „Prevođenje odabranog dela“ u programu Excel, PowerPoint, Word.

Prikupljaju se sledeća polja:

- **Data.actionSource**- Kako je aktiviran izbor za prevođenje-

- **Data.bodyBackgroundColor **- Boja pozadine Office teme

- **Data.bodyForegroundColor** - Boja prednjeg plana Office teme

- **Data.browserLang **- Trenutni jezika prikaza u pregledaču

- **Data.browserOnline **- Zastarelo

- **Data.browserPlatform** - Platforma pregledača

- **Data.browserUserAgent** - Korisnički agent pregledača

- **Data.colorDepth** - Dubina boja sistema

- **Data.contentLanguage** - Otkriveni jezik sadržaja za prevođenje

- **Data.controlBackgroundColor** - Boja pozadine kontrole Office teme

- **Data.controlForegroundColor**- Boja prednjeg plana kontrole Office teme

- **Data.correlationId** - Jedinstveni identifikator zahteva koji je poslat usluzi

- **Data.crossSessionId** - Jedinstveni identifikator korisnika

- **Data.crossSessionStartTime** - UTC vremenska oznaka za vreme početka sesije prevođenja

- **Data.currentTime**- UTC vremenska oznaka za vreme slanja ove telemetrijske poruke

- **Data.displayLanguage**- Jezik prikaza sistema Office

- **Data.documentSourceLang**- Ne koristiti se za izbor

- **Data.documentTargetLang**- Ne koristiti se za izbor prevoda

- **Data.environment**- Okruženje usluge kojoj je zahtev poslat

- **Data.errorMessage**- Poruka o grešci koju je prijavila usluga

- **Data.eventActionType** - Tip telemetrijskog događaja

- **Data.eventTagId"**- Jedinstveni identifikator reda koda koji je napravio ovo telemetrijsku poruku

- **Data.flights**- Omogućeni letovi

- **Data.innerHeight** - Visina kontejnera bočnog okna

- **Data.innerWidth**- Širina kontejnera bočnog okna

- **Data.lookupSourceLang** - Jezik trenutno izabranog teksta

- **Data.lookupTargetLang**- Jezik na koji će trenutno izabrani tekst biti preveden

- **Data.officeHost**- Office aplikacija koja sadrži bočno okno

- **Data.officeLocale**- Korisnički jezik sistema Office

- **Data.officeMachineId**- Jedinstveni identifikator uređaja

- **Data.officePlatform**- Platforma uređaja

- **Data.officeSessionId**- Identifikator Office sesije

- **Data.officeUserId**- Jedinstveni identifikator Office korisnika

- **Data.officeVersion**- Verzija sistema Office

- **Data.pageXOffset** - Horizontalna pozicija pomeranja bočnog okna u odnosu na levu stranu okna

- **Data.pageYOffset**- Vertikalna pozicija pomeranja bočnog okna u odnosu na gornju stranu okna

- **Data.pixelDepth**- Rezolucija boje ekrana

- **Data.responseCode** - Zatraži kod odziva od usluge

- **Data.responseTime**- Zatraži proteklo vreme

- **Data.resultType**- Zatraži rezultat

- **Data.screenHeight**- Visina ekrana u pikselima

- **Data.screenLeft**- Horizontalna koordinata prozora u odnosu na ekran

- **Data.screenLeft**- Vertikalna koordinata prozora u odnosu na ekran

- **Data.screenWidth**- Širina ekrana u pikselima

- **Data.selectedTab**- Koja je kartica izabrana, „Izbor“ ili „Dokument“

- **Data.serverUrl**- URL adresa usluge prevođenja

- **Data.sessionId**- Identifikator sesije bočnog okna

- **Data.sessionStartTime**- UTC vremenska oznaka za vreme početka sesije prevođenja

- **Data.sourceTextHash**- Heš teksta koji treba da se prevede

- **Data.sourceTextLength**- Dužina teksta koji treba da se prevede

- **Data.sourceTextWords** – Broj reči u tekstu koji treba da se prevede

- **Data.warningMessage**- Poruka upozorenja koju je prijavila usluga


#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Prati funkciju letova za korisnike. Ovaj događaj nam pomaže da odredimo uspešnost ili neuspešnost funkcije letova.

Prikupljaju se sledeća polja:

  - **Data\_Enable:bool**- tačno ukazuje na to da je funkcija omogućena za trenutnog korisnika

  - **Data\_Feature:string** - ime funkcije

  - **Data\_Flighted:bool** - tačno ukazuje na to da je funkcija omogućena

  - **Data\_Licensed:bool** - tačno ukazuje na to da se funkcija nalazi u okviru provere licenciranja

  - **Data\_Subscriber:bool** - tačno ukazuje na to da korisnik ima licencu za pretplatu

#### <a name="officevisiosharedrefreshsmartdiagram"></a>Office.Visio.Shared.RefreshSmartDiagram

Hvata greške u osvežavanju dijagrama kada se datoteka kreira pomoću funkcije VP. To nam pomaže da otklonimo greške i probleme u osvežavanju podataka u dijagramu VP.

Prikupljaju se sledeća polja:

  - **Data\_ConnectorsBasedOnSequence:bool** - tačno ako je osveženi dijagram prvobitno keiran pomoću konektora koji se zasniva na opciji „sekvence“

  - **Data\_DialogError**:**string** - greška tokom osvežavanja pametnog dijagrama

  - **Data\_FileError:string** - greška niske kada je povezana Excel datoteka nevažeća

  - **Data\_OverwriteSelected**:**bool** - tačno ako je korisnik izabrao opciju zamene dijagrama tokom osvežavanja

  - **Data\_WarningShown**:**bool** - tačno ako je korisniku prikazano upozorenje tokom osvežavanja podataka

#### <a name="officevisiosharedwritebacktoexcel"></a>Office.Visio.Shared.WritebackToExcel

Hvata greške povratnog upisivanja u programu Excel kada se datoteka kreira pomoću funkcije VP. To nam pomaže da otklonimo greške i probleme ponovnog upisivanja podataka u program Excel u dijagramu VP.

Prikupljaju se sledeća polja:

  - **Data\_ConnectorsBasedOnSequence:bool** - tačno znači da su konektori kreirani na osnovu postavki sekvence

  - **Data\_DataSourceType:string** - Polje koje ukazuje na to da li je dijagram kreiran iz „tabele“ ili „prilagođenog opsega“

  - **Data\_DialogError:string** - tip česte greške koja se javlja tokom kreiranja pametnog dijagrama u programu Excel

  - **Data\_NoOfShapesAdded:int** - Broj oblika koji su dodati tokom funkcije ponovnog upisivanja u program Excel

  - **Data\_NoOfShapesAdded:int** - Broj oblika koji su obrisani tokom funkcije ponovnog upisivanja u program Excel

  - **Data\_OverwriteSelected:bool** - tačno ukazuje na to da je korisnik izabrao opciju zamene podataka

  - **Data\_SourceDataModified:bool** - tačno ukazuje na to da su izvorni podaci izmenjeni

  - **Data\_WarningShown:bool** - tačno znači da je korisniku prikazano upozorenje o ažuriranju podataka

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje zbog formule koja je prisutna u programu Excel

  - **Data\_WarningShownToAddNextStepID:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje zato što u programu Excel nedostaje identifikator sledećeg koraka

  - **Data\_WarningShownToConvertToTable:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje da konvertuje Excel podatke u format tabele


#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a>Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend

Ovaj događaj evidentira statističke podatke za svaki dokument kada je program Office Word zatvoren ili obustavljen.  Događaj se koristi za označavanje uzajamne veze između uređivanja dokumenta, veličine itd. i čuvanja dokumenta, deljenja dokumenta i grešaka prilikom saradnje na uređivanju dokumenta na mreži.

Prikupljaju se sledeća polja:

- **Data_BkmkRefCount** - Broj referenci obeleživača u dokumentu

- **Data_CharacterCount** - Broj znakova u dokumentu

- **Data_CharactersWithSpaceCount** - Broj znakova i razmaka u dokumentu

- **Data_ChartCount** - Broj grafikona u dokumentu

- **Data_CitationCount** - Broj citata u dokumentu

- **Data_DocumentLocation** - Označava koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_ETW_TrackbackTag** - identifikuje mesto u kodu odakle je ovaj događaj aktiviran (zatvaranje ili obustavljanje)

- **Data_EndnoteDocCount** - Broj endnota u dokumentu

- **Data_FootnoteDocCount** - Broj fusnota u dokumentu

- **Data_HasBibliography** - Ukazuje na to da li dokument sadrži bibliografiju

- **Data_HasHeader** - Ukazuje na to da li dokument sadrži zaglavlje

- **Data_IsImeUsed** - Ukazuje na to da li je u dokumentu korišćen „Uređivač metode unosa“

- **Data_IsPageCountInProgress** - Ukazuje na to da li je trenutno u toku prebrojavanje stranica dokumenta.
    
- **Data_IsTouchUsed** - Ukazuje na to da li je u dokumentu korišćen unos dodirom

- **Data_IsTrackChangesOn** - Označava da li je bilo uključeno praćenje promena za dokument

- **Data_LineCount** - Broj redova u dokumentu

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word.

- **Data_PageCount** - Broj stranica u dokumentu

- **Data_PageNumberFieldCount** - Broj polja sa rednim brojem stranice u dokumentu

- **Data_ParagraphCount** - Broj pasusa u dokumentu

- **Data_PicCount** - Broj slika u dokumentu

- **Data_RsidCount** - Broj revizija čuvanje identifikator u dokumentu

- **Data_TocCount** - Broj sadržaja u dokumentu

- **Data_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_UserActionID** - ovo polje podataka se ne koristi (vrednost je uvek 0).

- **Data_UserActionName** - uvek „DocumentStatsOnCloseAndSuspend”

- **Data_UserInteractionTimeMsec** - Vreme u milisekundama koje je korisnik utrošio na interakciju sa dokumentom
    
- **Data_WordCount** - Broj reči u dokumentu

#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Ovaj događaj označava da je kreiran novi dokument u programu Office Word i prati uspešnost ili neuspešnost operacije. Događaj se koristi da prati da li kreiranje novog dokumenata radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.

Prikupljaju se sledeća polja:

  - **Podaci\_DirtyState** – Da li je dokument kreiran u nesačuvanom stanju (sa promenama koje treba da se sačuvaju)

  - **Podaci\_ErrorID** - identifikator greške u slučaju otkazivanja operacije

  - **Data\_MainPdod -** Identifikator dokumenta tokom ove sesije procesa

  - **Podaci\_KoristiPrilagođeniPredložak** - ukazuje na to da li je dokument kreiran na osnovu prilagođenog predloška

#### <a name="officewordfileopenuserinitiatedopen"></a>Office.Word.FileOpen.UserInitiatedOpen 

Ovaj događaj ukazuje na to da Office Word otvara dokument na zahtev korisnika umesto programski. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika.  Događaj prati da li otvaranje datoteke radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.  
 
Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka. 

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje. 

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo 

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke 

- **Data_BytesUnknown** - Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo. 

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje 

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje 

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta 

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument 

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.) 

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke 

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online 

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati 

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja 

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument 

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje 

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika 

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren 

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje 

- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta 

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje 

- **Data_Doc_Location** - Označava uslugu koja je obezbedila dokument (OneDrive, File Server, SharePoint, itd.) 

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument 

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja 

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje 

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje 

- **Data_Doc_ResourceIdHash** - Anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi 

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi 

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom 

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI itd.) 

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu 

- **Data_Doc_SessionId** - Verzija servera koji nudi uslugu 

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online 

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta 

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta 

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen 

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge) 

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta 

- **Data_Doc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge 

- **Data_EditorDisablingRename** -Identifikator prvog urednika zbog kojeg je onemogućeno preimenovanje 

- **Data_EditorsCount** - Broj urednika dokumenta 

- **Data_ForceReadWriteReason** -Vrednost celog broja koja predstavlja razlog zbog kog je datoteka primorana da se otvori u režimu za čitanje/pisanje 

- **Data_FSucceededAfterRecoverableFailure** - Ukazuje na to da je otvaranje uspelo nakon popravke greške prilikom otvaranja dokumenta 

- **Data_LastLoggedTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada otvaranje dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka) 

- **Data_LinkStyles** - Ukazuje na to da li se povezujemo sa stilovima predložaka 

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word 

- **Data_Measurements** - Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata Koristi se za dijagnostikovanje performanse otvaranja. 

- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta 

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja 

- **Data_OpenInitiateKind** – Tip scenarija u kome su korisnici pokrenuli otvaranje datoteke. 

- **Data_PartsUnknown** - Broj segmenata dokumenta za koji nismo mogli da dobijemo podatke 

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo 

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno 

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja 

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja. 

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument. 

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku. 

- **Data_VerboseMeasurements** - Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata.  Koristi se za merenje performansi, omogućenog samo za unutrašnje prstenove. 



#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Ovaj događaj ukazuje na to da korisnik čuva promene u novom dokumentu. Događaj prati da li operacija čuvanja u novom dokumentu radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika
    
- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje
    
- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_ServerProtocol** - Verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - Tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

- **Data_Doc_ServerVersion** - Verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_EditorDisablingRename** -Identifikator prvog urednika koji je uzrokovao onemogućavanje opcije preimenovanja

- **Data_EditorsCount** - Broj urednika dokumenta

- **Data_LastLoggedTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada pokušaj čuvanja dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka)

- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_RenameDisabledReason** - Greška koja uzrokuje nemogućnost preimenovanja dokumenta

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

    
#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave

Ovaj događaj ukazuje na to da Office Word čuva dokument sa automatskim oporavkom koji ranije nije sačuvan. To omogućava korporaciji Microsoft da otkrije greške u automatskom oporavku, što je bitno za bezbednost dokumenta.  Događaj prati da li automatski oporavak radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.

Prikupljaju se sledeća polja:

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.
    
- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje
    
- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI itd.)

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_Doc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_FailureClass** - Ceo broj koji predstavlja klasu greške kod neuspelog Office Collaboration Services OCS prelaza
    
- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word.

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_OCSSyncbackSaveStarted** - Zastavica koja ukazuje na to da se čuvanje odnosi na čuvanje ponovne sinhronizacije

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SaveInitiateKind** - Ceo broj koji ukazuje na to kako je pokrenuto čuvanje

- **Data_SrcDocIsUnnamedOrNew** - Ukazuje na to da li je dokument koji čuvamo nov


#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Ovaj događaj ukazuje na to da program Office Word traži od korisnika da sačuva promene kada program pokuša da zatvori dokument. On omogućava korporaciji Microsoft da prati da li funkcija „Sačuvaj pri zatvaranju“ radi kao što se očekuje da bi bio izbegnut gubitak podataka u dokumentu. Događaj prati da li funkcija „Sačuvaj pri zatvaranju“ radi kao što se očekuje. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje
    
- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI itd.)

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_Doc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_DstDoc_AccessMode** - Odredišni dokument je samo za čitanje/ili može da se uređuje

- **Data_DstDoc_EdpState** -Postavke za zaštitu elektronskih podataka odredišnog dokumenta-

- **Data_DstDoc_Ext** - Oznaka tipa odredišnog dokumenta (docx/xlsb/pptx, itd.)

- **Data_DstDoc_FileFormat** - Verzija protokola za format datoteke odredišnog dokumenta

- **Data_DstDoc_Location** - Ukazuje na to koja usluga će obezbediti skladištenje odredišnog dokumenta (OneDrive, File Server, SharePoint, itd.)

- **Data_DstDoc_LocationDetails** - Ukazuje na to koja je lokalna „Poznata fascikla“ uskladištila odredišni dokument

- **Data_DstDoc_SessionId** - Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_DstDoc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta za odredišni dokument

- **Data_FailureClass** - Ceo broj koji predstavlja klasu greške kod neuspelog OCS prelaza

- **Data_LocationPickerSaveStatus** - Vrednost celog broja koja ukazuje na radnju koja je pokrenula čuvanje sa dijaloga za izlaz

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word.

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_OCSSyncbackSaveStarted** - Zastavica koja ukazuje na to da se čuvanje odnosi na čuvanje ponovne sinhronizacije 

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SaveInitiateKind** - Ceo broj koji ukazuje na to kako je pokrenuto čuvanje

- **Data_SrcDocIsUnnamedOrNew** - Ukazuje na to da li je dokument koji čuvamo nov


#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Ovaj događaj ukazuje na to da program Office Word čuva dokument kao nov. To omogućava korporaciji Microsoft da otkrije greške u funkciji „Sačuvaj kao“, što je bitno da bi se izbeglo gubljenje podataka u dokumentu. Događaj prati da li funkcija „Sačuvaj kao“ radi kao što se očekuje. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_AddDocTelemResDst** - Izveštava da li smo u ovom događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta za odredišni dokument. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_AddDocTelemResSrc** - Izveštava da li smo u ovom događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta za izvorni dokument. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI itd.)

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_DstDoc_AccessMode** - Odredišni dokument je samo za čitanje/ili može da se uređuje

- **Data_DstDoc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je odredišni dokument otvoren u režimu za čitanje

- **Data_DstDoc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.
    
- **Data_DstDoc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_DstDoc_EdpState** - Postavke za zaštitu elektronskih podataka odredišnog dokumenta

- **Data_DstDoc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_DstDoc_FileFormat** - Verzija protokola za format datoteke

- **Data_DstDoc_Fqdn** - Ime OneDrive ili SharePoint Online domena za odredišni dokument

- **Data_DstDoc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati za odredišni dokument

- **Data_DstDoc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_DstDoc_InitializationScenario** - Beleži način na koji je otvoren odredišni dokument

- **Data_DstDoc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje odredišnog dokumenta
    
- **Data_DstDoc_IrmRights** - Radnje koje su dozvoljenje putem smernica za zaštitu elektronskih podataka koje su primenjene na odredišni dokument/korisnika

- **Data_DstDoc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_DstDoc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

- **Data_DstDoc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_DstDoc_IsSyncBacked**- Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_DstDoc_Location** - Ukazuje na to koja usluga je obezbedila skladištenje odredišnog dokumenta (OneDrive, File Server, SharePoint, itd.)

- **Data_DstDoc_LocationDetails** -Ukazuje na to koja poznata fascikla je obezbedila lokalno uskladišteni dokument

- **Data_DstDoc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_DstDoc_PasswordFlags** - Ukazuje na skup zastavica koje obeležavaju lozinke za čitanje ili čitanje/pisanje odredišnog dokumenta

- **Data_DstDoc_ReadOnlyReasons** - Razlozi zbog kojih je odredišni dokument otvoren samo za čitanje 

- **Data_DstDoc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_DstDoc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_DstDoc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_DstDoc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)
    
- **Data_DstDoc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_DstDoc_SessionId** - Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_DstDoc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_DstDoc_SizeInBytes** - Indikator veličine dokumenta

- **Data_DstDoc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_DstDoc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_DstDoc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_DstDoc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta za odredišni dokument
    
- **Data_DstDoc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_FailureClass** - Ceo broj koji predstavlja klasu greške kod neuspelog OCS prelaza

- **Data_LocationPickerPropagateToSaveTime,spLapsedMsec** -Merenje vremena u milisekundama koje potrebno za aktiviranje čuvanja kada se dobije rezultat izbora lokacije

- **Data_LocationPickerSaveStatus** -Status koji je vratio izbor lokacije

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word

- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SaveInitiateKind** - Ceo broj koji ukazuje na to kako je pokrenuto čuvanje

- **Data_SrcDoc_AccessMode** - Izvorni dokument je samo za čitanje/ili može da se uređuje

- **Data_SrcDoc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_SrcDoc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_SrcDoc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_SrcDoc_EdpState** - Postavke za zaštitu elektronskih podataka izvornog dokumenta

- **Data_SrcDoc_Ext** -Oznaka tipa izvornog dokumenta (docx/xlsb/pptx, itd.)

- **Data_SrcDoc_FileFormat** - Verzija protokola za format datoteke izvornog dokumenta

- **Data_SrcDoc_Fqdn** - Ime OneDrive ili SharePoint Online domena za izvorni dokument

- **Data_SrcDoc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati za izvorni dokument

- **Data_SrcDoc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_SrcDoc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_SrcDoc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_SrcDoc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_SrcDoc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_SrcDoc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

- **Data_SrcDoc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_SrcDoc_IsSyncBacked**- Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje
    
- **Data_SrcDoc_Location** - Ukazuje na to koja je usluga obezbedila izvorni dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_SrcDoc_LocationDetails** -Ukazuje na to koja poznata fascikla je obezbedila lokalno uskladišteni dokument

- **Data_SrcDoc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_SrcDoc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_SrcDoc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_SrcDoc_ResourceIdHash** - Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_SrcDoc_ServerDocId** - Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_SrcDoc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_SrcDoc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

- **Data_SrcDoc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_SrcDoc_SessionId** - Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_SrcDoc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_SrcDoc_SizeInBytes** - Indikator veličine dokumenta

- **Data_SrcDoc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_SrcDoc_StreamAvailability**- Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_SrcDoc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_SrcDoc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_SrcDoc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_SrcDocIsUnnamedOrNew** - Ukazuje na to da li je dokument koji čuvamo nov


#### <a name="officewordworddocumentdirtyflagchanged"></a>Office.Word.Word.DocumentDirtyFlagChanged

Ovaj događaj ukazuje na to da program Office Word uređuje dokument, što menja unutrašnji status dokumenta u „nesređeno“. To omogućava korporaciji Microsoft da proceni ispravnost funkcije uređivanja dokumenta. Događaj predstavlja otkucaj korisnikovih izmena. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja. 

Prikupljaju se sledeća polja:

  - **Data\_CollectionTime-** Vremenska oznaka događaja

  - **Data\_DocumentLocation-** tip lokacije dokumenta

  - **Data\_DocumentLocationDetails-** Podtip lokacije dokumenta

  - **Data\_FAlwaysSaveEnabled-** Ukazuje na to da li je omogućena funkcija „Uvek sačuvaj“

  - **Data\_FirstEditTime-** Vremenska oznaka prvog uređivanja

  - **Data\_NumberCoAuthors-** Broj koautora koji uređuju dokument tokom sesije

  - **Data\_NumberOfTimesDocumentDirtied-** Broj napravljenih izmena u dokumentu

  - **Data\_Pdod -** Identifikator dokumenta koji se obrađuje u programu Office Word

  - **Data\_UrlHash-** Heš putanje dokumenta

  - **Data\_ViewKind-** Tip prikaza u programu Word


#### <a name="parselicenseop"></a>ParseLicenseOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije raščlanjivanja licenci. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera sistema za evidenciju

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.VerifyCertChainDuration** - Trajanje verifikacije niza certifikata

- **RMS.VerifySignatureDuration** - Trajanje verifikacije potpisa

#### <a name="storeop"></a>StoreOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije skladištenja licence Usluge upravljanja pravima. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.ContentId** - Id sadržaja u licenci krajnjeg korisnika

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – Ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Url** – URL adresa servera Usluge upravljanja pravima


### <a name="application-status-and-boot-subtype"></a>*Status aplikacije i podtip pokretanja*

Utvrđivanje da li su se određene funkcije događaja odigrale, kao što su pokretanje ili zaustavljanje i da li funkcija radi.

#### <a name="dnslookupop"></a>DnsLookupOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije pronalaženja DNS informacija. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.NoOfDomainsSearched** - Broj pretraženih domena  

- **RMS.NoOfDomainsSearched** - Broj preskočenih domena 

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

#### <a name="getuserop"></a>GetUserOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije preuzimanja korisničkih certifikata. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.ContentId** - Id sadržaja

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Type** - Tip informacija o korisniku

#### <a name="httpop"></a>HttpOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja http zahteva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju
    
- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.CallBackStatus** - Status vraćenog rezultata povratnog poziva potvrde identiteta

- **RMS.CallbackTime** – Vreme koje je potrošeno na povratni poziv za potvrdu identiteta 

- **RMS.CorrelationId** - Id korelacije http zahteva

- **RMS.DataSize** - Veličina podataka http zahteva

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji ugnežđena http operacija 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Url** – URL adresa servera Usluge upravljanja pravima

- **RMS.WinhttpCallbackStatus** – Status rezultata winhttp povratnog poziva

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcCreateOauth2Token API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju
    
- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Beleži informacije o neočekivanim isključivanjima sistema Office. To nam omogućava da identifikujemo padove ili prekide proizvoda, tako da mogu biti rešeni.

Prikupljaju se sledeća polja:

  - **Data\_AirspaceInitTime:integer-** vreme koje je bilo potrebno za pokretanje AirSpace komponente sistema Office

  - **Data\_AllShapes:integer -** Broj oblika u dokumentu

  - **Data\_APIInitTime:integer -** vreme koje je bilo potrebno za pokretanje Visio API modula

  - **Data\_AppSizeHeight –** Visina**-** prozora programskog dodatka

  - **Data\_AppSizeWidth –** Širina**-** prozora programskog dodatka

  - **Data\_AppURL -** URL adresa programskog dodatka; Evidentira punu URL adresu programskih dodataka iz prodavnice i URL domen programskih dodataka koji nisu iz prodavnice

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_AuthorsCount:integer -** broj koautora koji su izmenili dokument tokom sesije

  - **Data\_BackgroundPages:integer -** broj stranica koje su u pozadini u dijagramu

  - **Data\_BootTime:integer -** Vreme koje je bilo potrebno za pokretanje programa Visio

  - **Data\_Browser -** Niska pregledača sa informacijama o pregledaču, kao što je tip, verzija

  - **Data\_ChildWindowMixedModeTime:integer -** vreme koje je bilo potrebno da se omogući mešoviti režim u programu Visio (pomoćni prozor može imati drugačije podešene tpi vrednosti od nadređenog prozora)

  - **Data\_CommentsCount:integer -** broj komentara u dokumentu

  - **Data\_ConnectionCount:integer -** Broj povezivanja sa podacima u dijagramu

  - **Data\_ContentMgrInitTim:integer -** vreme koje je bilo potrebno da se pokrene menadžer sadržaja

  - **Data\_CreateMainFrameTime:integer -** Kreiranje vremena centralnog računara

  - **Data\_CreatePaletteTime:integer -** Vreme koje je bilo potrebno za kreiranje opšte palete boja

  - **Data\_DispFormatCount:integer -** broj grafike podataka u dijagramu

  - **Data\_Doc\_Ext:string -** oznaka tipa dokumenta

  - **Data\_Doc\_Fqdn:string -** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo Office 365 domene

  - **Data\_Doc\_FqdnHash:string -** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IsIncrementalOpen:bool-** : Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Da li se dokument otvara iz lokalnog keša?

  - **Data\_Doc\_IsSyncBacked:bool-** tačno kada je u pitanju dokument servera koji postoji lokalno i koji se sinhronizuje sa serverom (npr. putem klijentskih aplikacija OneDrive ili ODB)

  - **Data\_Doc\_Location:long-** : Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** duga maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_SyncBackedType -** Indikator tipa dokumenta (lokalni ili iz usluge) 

  - **Data\_Doc\_UrlHash:string -** Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

  - **Data\_DpiAwarenessTime:integer -** Vreme koje je bilo potrebno da se omoguće tpi vrednosti po monitoru

  - **Data\_DurationToCompleteInMilliseconds:double-** Trajanje izvršavanja opcije „Sačuvaj kao“ u milisekundama

  - **Data\_ErrorCode:int -** : 0 za uspeh, ceo broj za grešku u čuvanju

  - **Data\_FailureReason:integer -** razlog greške za asinhrono čuvanje

  - **Data\_FileExtension -** Oznaka tipa datoteke dijagrama koji je otvoren

  - **Data\_FileHasDGMaster:bool -** tačno kada datoteka sadrži grafiku za podatke

  - **Data\_FileHasImportedData:bool -** tačno kada datoteka sadrži uvezene podatke

  - **Data\_FileHasShapesLinked:bool -** tačno kada datoteka sadrži oblike povezane sa podacima

  - **Data\_FileIOBytesRead:int -** Ukupno bajtova koji su pročitani prilikom čuvanja

  - **Data\_FileIOBytesReadSquared:int -** kvadratna vrednost podataka\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int -** Ukupno bajtova koji su napisani prilikom čuvanja

  - **Data\_FileIOBytesWrittenSquared:int -** kvadratna vrednost podataka\_FileIOBytesWritten

  - **Data\_FilePathHash:binary** -Binarni heš putanje datoteke

  - **Data\_FilePathHash: binary** - GUID za putanju datoteke

  - **Data\_FileSize -** Veličina dokumenta u bajtovima

  - **Data\_ForegroundPages:integer -** Broj stranica koje su u prednjem planu u dijagramu

  - **Data\_ForegroundShapes:integer -** Ceo broj oblika na stranicama koje su u prednjem planu

  - **Data\_GdiInitTime:integer -** vreme koje je bilo potrebno za pokretanje GDI modula

  - **Data\_HasCoauthUserEdit:bool -** tačno ako je dokument izmenjen u sesiji koautorstva

  - **Data\_HasCustomPages:bool -** tačno ako dokument sadrži prilagođene stranice

  - **Data\_HasCustPatterns:bool -** tačno ako datoteka sadrži prilagođene obrasce

  - **Data\_HasDynConn:bool -** tačno ako dokument sadrži dinamičku vezu

  - **Data\_HasCustomPages:bool -** tačno ako dokument sadrži skalirane stranice

  - **Data\_HasUserWaitTime:bool -** tačno ako je prikazan dijalog datoteke prilikom čuvanja

  - **Data\_InitAddinsTime:integer -** vreme koje je bilo potrebno za pokretanje i učitavanje programskog dodatka COM

  - **Data\_InitBrandTime:integer -** vreme koje je potrebno za pokretanje uvodnog ekrana i brendiranih komponenti sistema Office

  - **Data\_InitGimmeTime:integer -** vreme koje je bilo potrebno za pokretanje komponente sistema Office

  - **Data\_InitLicensingTime:integer -** vreme koje je bilo potrebno za pokretanje komponente licenciranja sistema Office

  - **Data\_InitMsoUtilsTime:integer -** Vreme potrebno za pokretanje komponente MSOUTILS sistema Office

  - **Data\_InitPerfTime:integer -** Vreme potrebno za pokretanje komponente performansi sistema Office

  - **Data\_InitTCOTime:integer -** vreme koje je potrebno za pokretanje komponente menadžera sistema Office

  - **Data\_InitTrustCenterTime:integer -** Vreme koje je bilo potrebno za pokretanje komponente centra za pouzdanost sistema Office

  - **Data\_InitVSSubSystemsTime:integer -** vreme koje je potrebno za pokretanje komponenti programa Visio

  - **Data\_InternalFile:bool -** tačno ako je datoteka unutrašnja npr. šablon

  - **Data\_IsAsyncSave:bool -** tačno ako je čuvanje asinhrono

  - **Data\_IsAutoRecoveredFile:bool -** tačno ako je datoteka automatski oporavljena

  - **Data\_IsEmbedded:bool -** tačno ako je datoteka programa Visio ugrađena u drugu aplikaciju

  - **Data\_IsInfinitePageDisabledForAllPages:bool -** tačno ako je onemogućena opcija „beskonačna strana“ za sve stranice u dokumentu

  - **Data\_IsIRMProtected:bool -** tačno ako je datoteka zaštićena pravima o informacijama

  - **Data\_IsLocal:bool -** tačno ako je datoteka lokalna

  - **Data\_IsRecoverySave:bool -** tačno ako je aktivirana bezbednost zbog oporavka

  - **Data\_IsShapeSearchPaneHiddenState:bool -** tačno ako je okno za pretragu oblika skriveno za dokument

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool -** bool, tačno ako je dijagram vizuelizatora pametnih podataka prisutan na aktivnoj stranici datoteke

  - **Data\_IsSmartDiagramPresentInFile:bool -** bool, tačno ako je dijagram vizuelizatora pametnih podataka prisutan u datoteci

  - **Data\_IsUNC:bool -** tačno ako se putanja dokumenta pridržava univerzalne konvencije imenovanja

  - **Data\_LandscapePgCount:integer -** broj strana koje imaju položeni položaj u dijagramu

  - **Data\_Layers:integer -** broj slojeva u dijagramu

  - **Data\_LoadProfileTime:integer -** vreme koje je potrebno za učitavanje profilera sistema Office

  - **Data\_LoadRichEditTim:integer-** vreme potrebno za učitavanje komponente obogaćenog uređivanja

  - **Data\_LoadVisIntlTime:integer -** vreme koje je bilo potrebno za učitavanje međunarodnog DLL-a programa Visio

  - **Data\_Location:integer -** Lokacija datoteke sa koje je otvorena 0 lokalno, 1, mreža, 2, usluga SharePoint, 3 - internet

  - **Data\_MasterCount:integer -** broj mastera u dijagramu

  - **Data\_MaxCoauthUsers:integer -** najveći broj korisnika koji sarađuju u bilo kom trenutku u sesiji sistema datoteke, registratora, direktnoj, SDX

  - **Data\_MaxTilesAutoSizeOn:integer -** Maksimalni broj pločica stranice za koje je omogućena automatska veličina

  - **Data\_MsoBeginBootTime:integer -** vreme pokretanja MSO-a

  - **Data\_MsoDllLoadTime:integer -** vreme koje je bilo potrebno za učitavanje MSO DLL-a

  - **Data\_MsoEndBootTime:integer -** vreme koje je bilo potrebno da se završi pokretanje datoteke MSO

  - **Data\_MsoInitCoreTime:integer -** Vreme koje je bilo potrebno da se pokrene MSO komponenta sistema Office

  - **Data\_MsoInitUITime:integer -** vreme koje je bilo potrebno da se pokrene korisnički interfejs MSO komponente sistema Office

  - **Data\_MsoMigrateTime:integer -** vreme koje je bilo potrebno za premeštanje korisničkih postavki pri prvom pokretanju ako je korisnik izvršio nadogradnju sa prethodne verzije

  - **Data\_NetworkIOBytesRead:int -** Ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesReadSquared:int -** kvadratna vrednost podataka\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten:int -** Ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesWrittenSquared :int-** kvadratna vrednost podataka NetworkIOBytesWritten

  - **Data\_OartStartupTime:integer -** vreme koje je bilo potrebno za pokretanje komponente OART sistema Office

  - **Data\_OleInitTime:integer -** Vreme pokretanja komponente OLE sistema Office

  - **Data\_OpenDurationTimeInMs:integer -** Trajanje otvaranja datoteke u milisekundama

  - **Data\_OriginatedFromTemplateID:integer -** identifikator predloška pomoću kog je napravljen dijagram NULL za predloške nezavisnih proizvođača

  - **Data\_Pages:integer -** broj stranica u dokumentu

  - **Data\_PositionToolbarsTime:integer -** vreme koje je bilo potrebno da se traka sa alatkama postavi na mesto

  - **Data\_ReadOnly:bool -** Tačno ako je datoteka samo za čitanje

  - **Data\_RecordSetCount:integer -** broj skupa zapisa u dijagramu

  - **Data\_RecoveryTime:integer -** vreme koje je bilo potrebno da se otvore oporavljene datoteke

  - **Data\_ReviewerPages:integer -** broj redaktorskih stranica u dijagramu

  - **Data\_RibbonTime:integer -** vreme koje je bilo potrebno za prikaz statusne trake

  - **Data\_RoamingSettingsStartupTime:integer -** vreme koje je bilo potrebno za kreiranje i učitavanje svih postavki koje su trenutno prenete u program Visio

  - **Data\_SchemeMgrStartupTime:integer -** vreme koje je bilo potrebno da se pokrene menadžer šeme

  - **Data\_SDX\_AssetId -** Postoji SAMO za programske dodatke koji su u prodavnici. OMEX im dodeljuje parametar „assetid“ kada se objave u prodavnici.

  - **Data\_SDX\_BrowserToken -** Identifikator koji se nalazi u kešu pregledača

  - **Data\_SDX\_HostJsVersion -** Verzija Office.js-a koja je karakteristična za platformu (npr. outlook web16.01.js). Sadrži API površinu za programske dodatke

  - **Data\_SDX\_Id -** GUID programskog dodatka koji ga jedinstveno identifikuje

  - **Data\_SDX\_InstanceId -** Predstavlja programski dodatak u paru dokumenata

  - **Data\_SDX\_MarketplaceType -** Ukazuje na to odakle je instaliran programski dodatak

  - **Data\_SDX\_OfficeJsVersion -** Verzija Office.js-a koja će preusmeriti na verziju karakterističnu za platformu

  - **Data\_SDX\_Version -** Verzija programskog dodatka

  - **Data\_ShellCmdLineTime:integer -** vreme koje je bilo potrebno da se raščlane i izvrše bilo koje komande ljuske u komandnoj liniji

  - **Data\_Size:long** - Veličina datoteke u bajtovima

  - **Data\_StartEndTransactionTime:integer -** vreme koje je bilo potrebno za pokretanje komponenti programa Visio

  - **Data\_STNInitTime:integer -** vreme koje je bilo potrebno da se pokrene konfiguracija šablona za prozor

  - **Data\_Tag:string -** jedinstveni identifikator za događaje funkcije „Sačuvaj kao“

  - **Data\_ThemeCount:integer -** broj tema u dijagramu

  - **Data\_TimeStamp -** Vremenska oznaka za trenutak zatvaranja dokumenta

  - **Data\_UIInitTime:integer -** Vreme pokretanja korisničkog interfejsa

  - **Data\_WasSuccessful:bool -** tačno ako je funkcija „Sačuvaj kao“ bila uspešna

  - **Data\_WinLaunchTime:integer -** vreme koje je bilo potrebno za pokretanje polaznog okna programa Visio, itd.

  - **Office.Visio.FileCharacteristicsVisio -** Snima svojstva datoteke prilikom njenog pokretanja za Visio C2R i Dev16. Ovaj događaj nam pomaže da kategorizujemo i otklonimo greške u svojstvima dokumenta, što nam zauzvrat omogućava da brže odredimo glavni uzrok problema i da ga rešimo na zadovoljstvo klijenta.

  - **Office.Visio.Shared.BootStats -** Ovaj događaj prikuplja vreme pokretanja za aplikaciju Visio Win32 Prikuplja različita polja sa podacima o pokretanju raznih komponenti, kao što je vreme učitavanja trake, vreme pokretanja aplikacije. Koristi se za merenje performansi pokretanja za program Visio.

  - **Office.Visio.Shared.FileOpen -** Ovaj događaj prikuplja statistiku o otvaranju datoteke za program Visio. Koristi se za praćenje stope uspeha/neuspeha otvaranja datoteke i za povezivanje istih sa nekoliko svojstava kao što je veličina datoteke. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

  - **Office.Visio.Shared.Filesave -** Ovaj događaj prikuplja statistiku o čuvanju datoteke za program Visio. Koristi se za praćenje stope uspeha/neuspeha čuvanja datoteke i za povezivanje istih sa nekoliko svojstava kao što su veličina datoteke i lokacija na kojoj se čuva, npr. na oblaku/lokalno. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

  - **Office.Visio.Shared.FilesaveAs -** Ovaj događaj prikuplja statistiku o funkciji datoteke „Sačuvaj kao“ za program Visio. Koristi se za praćenje stope uspeha/neuspeha čuvanja datoteke i za povezivanje istih sa nekoliko svojstava kao što su veličina datoteke i lokacija na kojoj se čuva, npr. na oblaku/lokalno. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

  - **Office.Visio.Shared.PostSave -** Ovaj događaj snima razlog greške u čuvanju datoteke

  - **Office.Visio.VisioFileSaveAs -** Ovaj događaj prikuplja statistiku o funkciji datoteke „Sačuvaj kao“ za Visio Dev16. Koristi se za praćenje stope uspeha/neuspeha opcije datoteke „Sačuvaj kao“ i za povezivanje istih sa nekoliko svojstava kao što su veličina datoteke i lokacija na kojoj se čuva, npr. na oblaku/lokalno. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

  - **Office.Visio.VisioFileSaveAsync -** Ovaj događaj prikuplja statistiku o asinhronom čuvanju datoteke za Visio Dev16. Koristi se za praćenje stope uspeha/neuspeha asinhronog čuvanja datoteke i za povezivanje istih sa nekoliko svojstava kao što su veličina datoteke i lokacija na kojoj se čuva, npr. na oblaku/lokalno. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

  - **Office.Visio.VisioFileSaveSync -** Ovaj događaj prikuplja statistiku o sinhronizovanom čuvanju datoteke za Visio Dev16. Koristi se za praćenje stope uspeha/neuspeha sinhronizovanog čuvanja datoteke i za povezivanje istih sa nekoliko svojstava kao što su veličina datoteke i lokacija na kojoj se čuva, npr. na oblaku/lokalno. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema. Ovaj događaj nam pomaže u praćenju razloga zbog kojih je došlo do greške u čuvanju kod datoteke.

#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Prikuplja kada je Office programskom dodatku potrebno neočekivano dugo da se pokrene (> 5 SEC). Koristi se za otkrivanje i rešavanje problema sa pokretanjem Office programskih dodataka.
 
Prikupljaju se sledeća polja:

- **AppId** -ID aplikacije

- **ApInfo** -podaci u vezi sa tipom programskog dodatka (okno zadatka ili UILess ili u sadržaju itd.) i tip dobavljača (Omen, SharePoint, okviru sistema datoteka itd.)

- **AppInstanceId** – ID instance aplikacije 

- **AssetId** - ID procene za aplikaciju

- **NumberOfAddinsActivated**- brojač aktivnih programskih dodataka

- **RemoterType** – precizira tip daljinca (pouzdanih, nepouzdanih, Win32webView, pouzdanih UDF-ova itd.) koji se koristi za aktiviranje programskog dodatka

- **StoreType** - poreklo aplikacije

- **TimeForAuth** - vreme potrošeno na potvrdu identiteta 

- **TimeForSandbox** - vreme potrošeno na sandbox

- **TimeForServerCall** - vreme potrošeno na pozivu na serveru 

- **TotalTime** - ukupno potrošeno vreme


#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Prikuplja korisnički PUID i identifikator zakupca jednom po sesiji. Korelacija između PUID-a i zakupca je neophodna da bi se razumeli i dijagnostikovali problemi po zakupcu u programu Outlook.

Prikupljaju se sledeća polja:

  - **CollectionTime** - Vremenska oznaka događaja

  - **ConnId** - Identifikator veze: Identifikator o vezi koja raščlanjuje PUID i identifikator OMS zakupca

  - **OMSTenantId** - Jedinstveni identifikator zakupca koji je generisao Microsoft

  - **PUID** - Menja PUID da bi se korisnici jedinstveno identifikovali


#### <a name="officeoutlookmacmacolkactivationstate"></a>Office.Outlook.Mac.MacOLKActivationState

Prikuplja na koji način je Outlook aktiviran, kao što je pretplata ili količinsko licenciranje. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja.  Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. 

Prikupljaju se sledeća polja:

- **SetupUIActivationMethod** – metod aktivacije programa Outlook, kao što su pretplata ili količinsko licenciranje

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Prikuplja se svaki put kada se otvori datoteka u programu PowerPoint. Sadrži informacije o uspehu, detalje o greškama, metriku performansi i osnovne podatke o datoteci uključujući tip formata i metapodatke dokumenta. Ove informacije su potrebne da bismo proverili da li PowerPoint može uspešno da otvara datoteke bez degradacije u performansama. Omogućavaju nam da dijagnostikujemo sve probleme koje otkrijemo.

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemetryResult -** Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Podaci\_Dokument\_\* polja)

  - **Data\_AddDocumentToMruList -** Trajanje izvršavanja metode AddDocumentToMruList

  - **Data\_AlreadyOpened -** Da li je dokument prethodno otvoren (u smislu istog procesa sesije)

  - **Data\_AntiVirusScanMethod -** Unapred definisani skup vrednosti za tip antivirusnog skeniranja (IOAV, AMSI, nijedan, itd.)

  - **Data\_AntiVirusScanStatus -** Unapred definisani skup vrednosti za antivirusno skeniranje koje se izvršava za svaki otvoreni dokument (nisu otkrivene pretnje, neuspelo, otkriven je malver, itd.)

  - **Data\_AsyncOpenKind -** Unapred definisani skup vrednosti za opcije asinhronizacije (saradnja, samo server, ponovna sinhronizacija, nije asinhronizacija)

  - **Data\_CancelBackgroundDownloadHr -** Da li je preuzimanje dokumenta prekinuto? Ako jeste, koji je ishod prekida?

  - **Data\_CheckForAssistedReadingReasons -** Trajanje izvršavanja metode CheckForAssistedReadingReasons u milisekundama

  - **Data\_CheckForDisabledDocument -** Trajanje izvršavanja metode CheckForDisabledDocument u milisekundama

  - **Data\_CheckForExistingDocument -** Trajanje izvršavanja metode CheckForExistingDocument u milisekundama

  - **Data\_CheckIncOpenResult -** Trajanje izvršavanja metode CheckIncOpenResult u milisekundama

  - **Data\_CheckLambdaResult -** Trajanje izvršavanja metode CheckLambdaResult u milisekundama

  - **Data\_CheckPackageForRequiredParts -** Trajanje izvršavanja metode CheckPackageForRequiredParts u milisekundama

  - **Data\_CheckPackageForSpecialCases -** Trajanje izvršavanja metode CheckPackageForSpecialCases u milisekundama

  - **Data\_CheckRequiredPartsLoaded -** Trajanje izvršavanja metode CheckRequiredPartsLoaded u milisekundama

  - **Data\_CheckWebSharingViolationForIncOpen -** Trajanje izvršavanja metode CheckWebSharingViolationForIncOpen u milisekundama
   
  - **Data_CloseAndReopenWithoutDiscard –** Da li je dokument zatvoren i ponovo otvoren tokom otvorenog procesa bez odbacivanja.

  - **Data\_ContentTransaction -** Unapred definisani skup vrednosti koji se odnosi na to kada transakcija može biti kreirana (dozvoljeno pri učitavanju dokumenta, dozvoljeno pri završenom otvaranju, itd.)

  - **Data_CorrelationId –** GUID je prosleđen programu PowerPoint pomoću programa ProtocolHandler za korelaciju telemetrije. ProtokolHandler je odvojeni proces koji upravlja Office vezama za OS.

  - **Data\_CppUncaughtExceptionCount:long -** Neopaženi osnovni izuzeci dok je aktivnost pokrenuta

  - **Data\_CreateDocumentTimeMS -** Trajanje izvršavanja metode CreateDocumentTimeMS u milisekundama

  - **Data\_CreateDocumentToken -** Trajanje izvršavanja metode CreateDocumentToken u milisekundama

  - **Data\_CreateDocumentToW -** Trajanje izvršavanja metode CreateDocumentToW u milisekundama

  - **Data\_CreateDocWindow -** Trajanje izvršavanja metode CreateDocWindow u milisekundama

  - **Data\_CreateLocalTempFile -** Trajanje izvršavanja metode CreateLocalTempFile u milisekundama

  - **Data\_DetachedDuration:long -** Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

  - **Data\_DetermineFileType -** Trajanje izvršavanja metode DetermineFileType u milisekundama

  - **Data\_Doc\_AccessMode:long -** Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu za čitanje

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType:long -** Kako je dokument uskladišten u sistemu SharePoint

  - **Data\_Doc\_EdpState:long -** Stanje dokumenta u vezi sa „Zaštitom podataka preduzeća“

  - **Data\_Doc\_Ext:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_Extension:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_FileFormat:long -** Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

  - **Data\_Doc\_Fqdn:string -** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za Office 365 domene

  - **Data\_Doc\_FqdnHash:string -** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IdentityTelemetryId:string -** Jedinstveni korisnički GUID

  - **Data\_Doc\_IdentityUniqueId:string -** Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

  - **Data\_Doc\_IOFlags:long -** Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

  - **Data\_Doc\_IrmRights:long -** Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool -** Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

  - **Data\_Doc\_IsIncrementalOpen:bool-** : Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOcsSupported:bool -** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Da li se dokument otvara iz lokalnog keša?

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long -** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Da li je server zasnovan na verziji Office14, Office15, Office16?

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string -** Identifikator usluge WOPI, npr. „Dropbox“

  - **Data\_DownloadExcludedData -** Trajanje izvršavanja metode DownloadExcludedData u milisekundama

  - **Data\_DownloadExcludedDataTelemetry -** Unapred definisani skup vrednosti za status sinhronizovanog čekanja na preuzimanje (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult, itd.)

  - **Data\_DownloadFileInBGThread -** Trajanje izvršavanja metode DownloadFileInBGThread u milisekundama

  - **Data\_DownloadFragmentSize -** Veličina fragmenta (deo datoteke koji se može preuzeti), obično 3,5 MB

  - **Data\_ExcludedEmbeddedItems -** Broj segmenata zip arhive koji su isključeni iz prvog prikazivanja

  - **Data\_ExcludedEmbeddedItemsSize -** Ukupna veličina segmenata zip arhive koja je isključena iz prvog prikazivanja

  - **Data\_ExcludedRequiredItems -** Broj segmenata zip arhive koji su isključeni, ali neophodni za prvo prikazivanje

  - **Data\_ExcludedRequiredItemsSize -** Ukupna veličina segmenata zip arhive koja je isključena, ali neophodna za prvo prikazivanje

  - **Data\_ExecutionCount -** Koliko puta je izvršen protokol IncOpen

  - **Data\_FailureComponent:long -** Unapred definisani skup vrednosti za komponentu koja je izazvala neuspeh protokola (neusaglašenost, CSI, unutrašnja, itd.)

  - **Data\_FailureReason:long -** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data\_FCreateNew -** Da li je novi prazan dokument

  - **Data\_FCreateNewFromTemplate -** Da li je novi dokument iz predložaka

  - **Data_FErrorAfterDocWinCreation: Boolean-** Da li je došlo do greške ili izuzetka nakon kreiranja prozora dokumenta.

  - **Data\_FileUrlLocation -** Unapred definisani skup vrednosti za mesto gde je uskladišten dokument (NetworkShare, LocalDrive, ServerOther, itd.)

  - **Data\_FirstSlideCompressedSize -** komprimovana veličina prvog slajda segmenta zip arhive (obično Slide1.xml)

  - **Data\_FIsDownloadFileInBgThreadEnabled -** Da li je omogućeno preuzimanje u pozadinskom nizu?

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

  - **Data\_ForceReopenOnIncOpenMergeFailure -** Zastavica koja označava da li smo bili primorani na ponovno otvaranje zbog greške u objedinjavanju u protokolu Inc Open

  - **Data\_ForegroundThreadPass0TimeMS -** (Samo za Mac) Ukupno vreme koje je provedeno u nizu prednjeg plana tokom prvog prenosa

  - **Data\_ForegroundThreadPass1TimeMS -** (Samo za Mac) Ukupno vreme koje je provedeno u nizu prednjeg plana tokom drugog prenosa

  - **Data\_FWebCreatorDoc -** Da li je dokument kreiran iz predloška ili u usluzi QuickStarter

  - **Data\_HasDocToken -** Da li dokument ima CSI token dokumenta (unutrašnji kôd)

  - **Data\_HasDocument -** Da li dokument ima CSI dokument (unutrašnji kôd)

  - **Data\_InclusiveMeasurements -** Da li mere trajanja metode sadrže trajanje poziva pomoćne metode

  - **Data\_IncompleteDocReasons -** Unapred definisani skup vrednosti za razloge zbog kojih je otvaranje nedovršeno (nepoznato, neuspešno odbacivanje, itd.)

  - **Data\_IncOpenDisabledReasons -** Unapred definisani skup vrednosti za razloge zbog kojih je onemogućeno postepeno otvaranje

  - **Data\_IncOpenFailureHr -** Rezultat zbog kog nije uspelo postepeno otvaranje

  - **Data\_IncOpenFailureTag -** Oznaka (pokazivač lokacije koda) mesta na kom nije uspelo postepeno otvaranje

  - **Data\_IncOpenFallbackReason -** Zašto nije pokrenut IncOpen

  - **Data\_IncOpenRequiredTypes -** Unapred definisani skup vrednosti za tip sadržaja koji je neophodan za prvo prikazivanje (RequiredXmlZipItem, RequiredNotesMaster, itd.)

  - **Data\_IncOpenStatus -** Unapred definisani skup vrednosti za status postepenog otvaranja (Attempted, FoundExcludedItems, DocIncOpenInfoCreated, itd.)

  - **Data\_InitFileContents -** Trajanje izvršavanja metode InitFileContents u milisekundama

  - **Data\_InitialExcludedItems -** Broj segmenata zip arhive koji su isključeni na početku

  - **Data\_InitialExcludedItemsSize -** Ukupna veličina segmenata zip arhive koja je isključena na početku

  - **Data\_InitializationTimeMS -** (Samo za Mac) Vreme potrebno za pokretanje

  - **Data\_InitialRoundtripCount -** Broj odziva servera koji je neophodan da bi se formirala početna zip arhiva

  - **Data\_InitLoadProcess -** Trajanje izvršavanja metode InitLoadProcess u milisekundama

  - **Data\_InitPackage -** Trajanje izvršavanja metode InitPackage u milisekundama

  - **Data\_InitSecureReaderReasons -** Trajanje izvršavanja metode InitSecureReaderReasons u milisekundama

  - **Data\_IsIncOpenInProgressWhileOpen -** Da li je protokol Inc open pokrenut zajedno sa otvorenim protokolom u slučaju višestrukog otvaranja istog dokumenta?

  - **Data\_IsMultiOpen -** Da li podržavamo višestruko otvaranje?

  - **Data\_IsOCS -** Da li se dokument u svom poslednjem poznatom stanju nalazio u režimu OCS

  - **Data\_IsODPFile -** Da li je dokument u formatu „Open Document Format“ koji koristi OpenOffice.org

  - **Data\_IsPPTMetroFile -** Da li je dokument u metro (pptx) formatu

  - **Data\_LoadDocument -** Trajanje izvršavanja metode LoadDocument u milisekundama

  - **Data\_MeasurementBreakdown -** Analiza šifrovanih mera (skraćeni detalji o performansama metode)

  - **Data\_Measurements -** Šifrovane mere

  - **Data\_MethodId -** Poslednji metod koji je izvršen

  - **Data\_NotRequiredExcludedItems -** Ukupan broj stavki u PowerPoint paketu koje su isključene i nisu neophodne za prvo prikazivanje

  - **Data\_NotRequiredExcludedItemsSize -** Ukupna veličina stavki u PowerPoint paketu koje su isključene i nisu neophodne za prvo prikazivanje

  - **Data\_NotRequiredExcludedIParts -** Ukupan broj segmenata zip arhive koji su isključeni i nisu neophodni za prvo prikazivanje

  - **Data\_NotRequiredExcludedIPartsSize -** Ukupan broj segmenata zip arhive koji su isključeni i nisu neophodni za prvo prikazivanje

  - **Data\_OpenCompleteFailureHR -** rezultat zbog kog nije uspeo protokol OpenComplete

  - **Data\_OpenCompleteFailureTag -** Oznaka (pokazivač lokacije koda) mesta na kom nije uspeo protokol OpenComplete

  - **Data\_OpenLifeguardOption -** Unapred definisani skup vrednosti izbora za operaciju samokorigovanja (nijedan, pokušaj ponovo, otvori u veb aplikaciji, itd.)

  - **Data\_OpenReason -** Unapred definisani skup vrednosti za način na koji je otvoren dokument (FilePicker, OpenFromMru, FileDrop, itd.)

  - **Data\_OSRPolicy -** Smernice za bezbedni čitač

  - **Data\_OSRReason -** Razlozi zbog kojih je dokument otvoren u bezbednom čitaču

  - **Data\_OtherContentTypesWithRequiredParts -** Nestandardni tipovi sadržaja koji su isključeni, ali neophodni za prvo prikazivanje

  - **Data\_PrepCacheAsync -** Zastavica koja označava OcsiOpenPerfPrepCacheAsync

  - **Data\_PreviousDiscardFailed -** Ukazuje na to da prethodni pokušaj otvaranja/zatvaranja dokumenta nije pravilno oslobodio svu memoriju

  - **Data\_PreviousFailureHr -** Koji je bio poslednji rezultat greške u slučaju ponovnog otvaranja istog dokumenta?

  - **Data\_PreviousFailureTag -** Koja je bila poslednja oznaka greške (pokazivač lokacije koda) u slučaju ponovnog otvaranja istog dokumenta? 

  - **Data\_RemoteDocToken -** Da li je omogućeno daljinsko otvaranje (prototip funkcije koja omogućava otvaranje datoteke iz usluge umesto sa hosta)?

  - **Data\_Repair -** Da li je dokument u režimu popravke (za oštećene dokumente koji mogu da se poprave)

  - **Data\_RequestPauseStats -** Koliko puta je kôd zahtevao da se pauzira snimanje performansi

  - **Data\_RequiredPartsComressedSize -** Ukupna veličina PowerPoint segmenata koji su neophodni za prvo prikazivanje

  - **Data\_RequiredPartsDownload -** Ukupna veličina neophodnih PowerPoint segmenata koji su preuzeti

  - **Data\_RequiredPartsRoundtripCount -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni da bi se preuzeli svi neophodni PowerPoint segmenti za prvo prikazivanje

  - **Data\_RequiredZipItemsDownload -** Ukupna veličina zip stavki koje su neophodne za prvo prikazivanje

  - **Data\_RequiredZipItemsRoundtripCount -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni da bi se preuzeli sve neophodne zip stavke za prvo prikazivanje

  - **Data\_RoundtripsAfterMissingRequiredParts -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni kada otkrijemo da nedostaju neophodni PowerPoint segmenti

  - **Data\_RoundtripsAfterMissingRequiredZipItems -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni kada otkrijemo da nedostaju neophodne zip stavke

  - **Data\_RoundtripsAfterRequiredPackage -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni kada kreiramo paket

  - **Data\_RoundtripsAfterRequiredParts -** Ukupan broj povratnih odziva (pozivi upućeni hostu) koji su potrebni kada preuzmemo sve neophodne segmente

  - **Data\_SetDocCoAuthAutoSaveable -** Trajanje izvršavanja metode SetDocCoAuthAutoSaveable u milisekundama

  - **Data\_SniffedFileType -** Osnovana pretpostavka o tipu predložene datoteke oštećenog dokumenta

  - **Data\_StartTime -** Brojač performansi kad počne otvaranje

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Data\_SyncSlides -** Trajanje izvršavanja metode SyncSlides u milisekundama

  - **Data\_TimerStartReason -** Unapred definisani skup vrednosti za način na koji je počeo merač vremena (CatchMissedSyncStateNotification, WaitingForFirstDownload, itd.)

  - **Data\_TimeSplitMeasurements -** Analiza šifrovanih mera (skraćeni detalji o performansama metode)

  - **Data\_TimeToInitialPackage -** Vreme koje je bilo potrebno za kreiranje početnog paketa

  - **Data\_TimeToRequiredPackage -** Vreme koje je bilo potrebno za kreiranje neophodnog paketa

  - **Data\_TimeToRequiredParts -** Vreme koje je bilo potrebno za kreiranje paketa sa svim neophodnim segmentima

  - **Data\_TotalRequiredParts -** Ukupan broj PowerPoint segmenata koji su potrebni za prvo prikazivanje

  - **Data\_UnknownRequiredParts -** Ukupan broj nestandardnih segmenata koji su potrebni za prvo prikazivanje

  - **Data\_UnpackLinkWatsonId -** „Watson“ identifikator za greške kada je dokument otvoren putem Share OneDrive URL adrese

  - **Data\_UnpackResultHint -** Unapred definisani skup vrednosti za rezultate raspakivanja deljene URL adrese (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen etc.)

  - **Data\_UnpackUrl -** Trajanje izvršavanja metode UnpackUrl u milisekundama

  - **Data\_UpdateAppstateTimeMS -** Trajanje izvršavanja metode UpdateAppstate u milisekundama

  - **Data\_UpdateCoauthoringState -** Trajanje izvršavanja metode UpdateCoauthoringState u milisekundama

  - **Data\_UpdateReadOnlyState -** Trajanje izvršavanja metode UpdateReadOnlyState u milisekundama

  - **Data\_WACCorrelationId -** Prikuplja korelaciju evidencije WebApp-a u slučaju otvaranja datoteke u pregledaču

  - **Data\_WasCachedOnInitialize -** Da li je dokument keširan tokom pokretanja

  - **Data\_WBDirtyBeforeDiscard -** Da li je radna grana bila nesređena pre ponovnog otvaranja dokumenta

  - **Data\_ZRTOpenDisabledReasons -** Zašto nismo mogli da otvorimo dokument iz keša (nula povratnih odziva)

#### <a name="officepowerpointpptdesktopbootime"></a>Office.PowerPoint.PPT.Desktop.Bootime

Prikuplja podatke o načinu na koji je pokrenut program PowerPoint. To uključuje pokretanje u zaštićenom prikazu, u režimu za čitanje, iz makroa, za štampanje, kao novi i prazan dokument, za oporavak dokumenta, automatizacijom, i ako je pokrenut pomoću „Klikni i pokreni“. Prikuplja i podatke o tome koliko vremena mu je potrebno za pokretanje.  Ovi podaci su od presudnog značaja za garanciju dobrog funkcionisanja kada se pokreće u različitim režimima. Microsoft ih koristi da bi primetili dugo vreme pokretanja kada se PowerPoint otvara u različitim režimima.

Prikupljaju se sledeća polja:

  - **AssistedReading -** u režimu za čitanje

  - **Automation -** automatizacijom

  - **Benchmark -** Izvršavanje testiranja performansi

  - **Blank -** prazan dokument

  - **BootTime -** vreme pokretanja sesije

  - **Embedding -** ugrađivanje dokumenta

  - **IsC2R -** da li je „Klikni i pokreni“

  - **IsNew -** novi dokument

  - **IsOpen -** da li je otvoren

  - **Macro1 -** pokretanje makroa

  - **Macro2 -** pokretanje makroa

  - **NonStandardSpaceInCmdLine** - postoji nestandardni razmak u komandnoj liniji

  - **Print -** štampanje dokumenta

  - **PrintDialog -** štampanje dokumenta pomoću dijaloga

  - **PrintPrinter -** štampanje dokumenta na štampaču

  - **ProtectedView -** u zaštićenom prikazu

  - **RegServer -** Registrovanje programa PowerPoint kao COM server

  - **Restore -** vraćanje prethodne verzije dokumenta

  - **Show -** prikaži dokument

  - **Time -** vreme sesije

  - **UnprotectedView -** u nezaštićenom prikazu

#### <a name="officepowerpointppthasuserediteddocument"></a>Office.PowerPoint.PPT.HasUserEditedDocument

Prikuplja se kada korisnik počne da uređuje dokument. Microsoft koristi te podatke da bi izračunao broj aktivnih korisnika koji uređuju dokument u programu PowerPoint

Prikupljaju se sledeća polja:

  - **CorrelationId** - Identifikator korelacije dokumenta

#### <a name="officeprojectbootandopenproject"></a>Office.Project.BootAndOpenProject

Program Project je pokrenut otvaranjem datoteke. Ovaj događaj ukazuje na to da je korisnik otvorio Office Project pomoću povezane datoteke. Sadrži bitne podatke o uspešnosti za proveravanje da li može da se pokrene i učita datoteku.

Prikupljaju se sledeća polja:

  - **Data\_AlertTime -** Koliko vremena je bio aktivan dijalog pokretanja.

  - **Data\_BootTime -** Vreme koje je bilo potrebno za pokretanje programa Project

  - **Data\_CacheFileSize -** Veličina datoteke ako je keširana

  - **Data\_EntDocType -** Tip datoteke koja je otvorena

  - **Data\_IsInCache -** Da li je otvorena datoteka keširana

  - **Data\_LoadSRAs -** Ako korisnik želi da učita SRAs ili ne želi

  - **Data\_Outcome -** Ukupno vreme pokretanja i otvaranja datoteke.

  - **Data\_OpenFromDocLib -** Ako je datoteka programa Project otvorena iz biblioteke dokumenata

  - **Data\_ProjectServerVersion -** Trenutna verzija i izdanje programa Project

#### <a name="officeprojectbootproject"></a>Office.Project.BootProject

Program Project je pokrenut bez otvaranja datoteke. Ovaj događaj ukazuje na to da je korisnik otvorio Office Project bez povezane datoteke. Sadrži bitne podatke o uspešnosti za proveravanje da li može da se pokrene.

Prikupljaju se sledeća polja:

  - **Data\_BootTime -** Vreme koje je bilo potrebno za pokretanje programa Project

  - **Data\_FileLoaded -** Netačno ako se otvara izvan programa ili kao novi prazan projekat

  - **Data\_IsEntOfflineWithProfile -** Ako se korisnici nalaze u profesionalnom SKU i nisu povezani na server

  - **Data\_IsEntOnline -** Ako je sesija programa Project povezana sa serverom Project koji ima funkciju edicije Enterprise

  - **Data\_IsLocalProfile -** Ako je sesija programa Project povezana sa serverom Project koji ima funkciju edicije Enterprise

  - **Data\_ProjectServerVersion -** Trenutna verzija i izdanje programa Project


#### <a name="officeprojectopenproject"></a>Office.Project.OpenProject

Datoteka se otvara u programu Project. Ovaj događaj ukazuje na to da korisnik direktno otvara korisničku Project datoteku. Sadrži bitne podatke o uspehu otvaranja datoteka u programu Project.

Prikupljaju se sledeća polja:

  - **Data\_AgileMode -** definiše da li je otvoreni projekat kaskadni ili agilni

  - **Data\_AlertTime -** Koliko vremena je bio aktivan dijalog pokretanja

  - **Data\_CacheFileSize -** Veličina datoteke ako je keširana

  - **Data\_EntDocType -** tip datoteke koja je otvorena

  - **Data\_IsInCache -** da li je otvorena datoteka keširana

  - **Data\_LoadSRAs -** Ako korisnik želi da učita SRAs ili ne želi

  - **Data\_OpenFromDocLib -** Ako je datoteka programa Project otvorena iz biblioteke dokumenata

  - **Data\_Outcome -** Ukupno vreme pokretanja i otvaranja datoteke

  - **Data\_Outcome -** Ukupno vreme pokretanja i otvaranja datoteke.

  - **Data\_ProjectServerVersion -** Trenutna verzija i izdanje programa Project

#### <a name="officesessionidproviderofficeprocesssessionstart"></a>Office.SessionIdProvider.OfficeProcessSessionStart

Primenjuje se na sve Office aplikacije koje se zasnivaju na operativnom sistemu Windows: Win32 i UWP

Prikupljaju se sledeća polja:

- **OfficeProcessSessionStart** šalje osnovne informacije posle pokretanja nove sesije sistema Office.  Koristi se za izračunavanje broja jedinstvenih sesija koje su primećene na datom uređaju. Koristi se kao događaj otkucaja da bi se proverilo da li je aplikacija pokrenuta na uređaju ili nije. Osim toga, služi i kao bitan pokazatelj celokupne pouzdanosti aplikacije.

- **AppSessionGuid** - Identifikator sesije za određenu aplikaciju počevši od vremena kreiranja procesa do kraja procesa. Oblikovan je kao standardni 128-bitni GUID, ali se sastoji iz 4 dela. Ta četiri dela su po redu (1) 32-bitni ID procesa (2) 16-bitni ID sesije (3) 16-bitni ID za pokretanje (4) 64-bitni proces nastanka u UTC 100ns

- **processSessionId** - nasumično generisan guid za identifikovanje sesije aplikacije

- **UTCReplace_AppSessionGuid** - Nepromenjiva logička vrednost. Uvek ima vrednost TRUE.

#### <a name="officesystemsessionhandoff"></a>Office.System.SessionHandoff

Označava da je trenutna sesija aplikacije Office sesija predaje. To znači da se rukovanje zahtevom korisnika za otvaranje dokumenta predaje već pokrenutoj instanci iste aplikacije.

Prikupljaju se sledeća polja.

- **ParentSessionId** - ID sesije koja će preuzeti upravljanje zahtevom korisnika.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Primenjuje se za Office aplikacije za UWP.  Ovaj događaj se aktivira kada se Office aplikacija pokrene po prvi put nakon ažuriranja/instalacije iz prodavnice. Ovo je deo osnovnih dijagnostičkih podataka koji se koriste za praćenje da li je sesija pokretanja ili nije.

Prikupljaju se sledeća polja:

- **appVersionBuild** - Broj verzije izdanja aplikacije.

- **appVersionMajor** - Broj glavne verzije aplikacije.

- **appVersionMinor** - Broj sporedne verzije aplikacije.

- **appVersionRev** - Broj revizije verzije aplikacije.

- **SessionID** - nasumično generisan GUID za identifikovanje sesije aplikacije

#### <a name="officetelemetryenginesessionhandoff"></a>Office.TelemetryEngine.SessionHandOff

Primenjuje se za Office aplikacije za Win32.  Ovaj događaj nam pomaže da shvatimo da li je nova sesija kreirana da bi rukovala događajem otvaranja datoteke koji je pokrenuo korisnik. To su bitne dijagnostičke informacije koje se koriste za slanje signala za pouzdanost i za proveravanje da li aplikacija radi kao što je očekivano.

Prikupljaju se sledeća polja:

- **appVersionBuild** - Broj verzije izdanja aplikacije.

- **appVersionMajor** - Broj glavne verzije aplikacije.

- **appVersionMinor** - Broj sporedne verzije aplikacije.

- **appVersionRev** - Broj revizije verzije aplikacije.

- **childSessionID** - nasumično generisan guid za identifikovanje sesije aplikacije

- **parentSessionId** - nasumično generisan guid za identifikovanje sesije aplikacije

#### <a name="officevisiovisioiosappboottime"></a>Office.Visio.VisioIosAppBootTime

Ovo se pokreće svaki put kada se Visio iOS aplikacija pokrene. Neophodno je razumeti performanse pokretanja Visio iOS aplikacije. Koristi se za rešavanje problema loših performansi. 

Prikupljaju se sledeća polja:

- **Data_AppBootTime** - trajanje potrebno za pokretanje aplikacije u milisekundama.

#### <a name="officevisiovisioiosappresumetime"></a>Office.Visio.VisioIosAppResumeTime 

Ovaj događaj se pokreće svaki put kada Visio iOS aplikacija nastavi s radom. Važno je da merite performanse nastavka aplikacije i rešite probleme performansi aplikacije Visio iOS.

Prikupljaju se sledeća polja:

- **Data_AppResumeTime** - trajanje potrebno za nastavak rada aplikacije u milisekundama.

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Ovaj događaj ukazuje na to da program Office Word otvara dokument sa liste nedavno korišćenih dokumenata (MRU). Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke iz MRU liste radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

- **Data_BytesUnknown** - Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo. 

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** - Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** - Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi 

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi dokumenta 

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_Doc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_EditorDisablingRename** -Identifikator prvog urednika zbog kojeg je onemogućeno preimenovanje

- **Data_EditorsCount** - Broj urednika dokumenta

- **Data_ForceReadWriteReason** -Vrednost celog broja koja predstavlja razlog zbog kog je datoteka primorana da se otvori u režimu za čitanje/pisanje

- **Data_FSucceededAfterRecoverableFailure** - Ukazuje na to da je otvaranje uspelo nakon popravke greške prilikom otvaranja dokumenta

- **Data_LastLoggedTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada otvaranje dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka)

- **Data_LinkStyles** - Ukazuje na to da li se povezujemo sa stilovima predložaka

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word

- **Data_Measurements** - Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata Koristi se za merenje performansi.

- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_PartsUnknown** - broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja 

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument.

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku

- **PathData_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen


#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Ovaj događaj ukazuje na to da Office Word otvara dokument na koji je korisnik kliknuo dvaput. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke pomoću dvostrukog klika radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka
    
- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.
    
- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke
    
- **Data_BytesUnknown** - Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** - Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika

- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje
    
- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)
    
- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI itd.)
    
- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu 

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_Doc_WopiServiceId** - Sadrži jedinstveni identifikator WOPI dobavljača usluge

- **Data_EditorDisablingRename** -Identifikator prvog urednika zbog kojeg je onemogućeno preimenovanje

- **Data_EditorsCount** - Broj urednika dokumenta

- **Data_FSucceededAfterRecoverableFailure** - Ukazuje na to da je otvaranje uspelo nakon popravke greške prilikom otvaranja dokumenta

- **Data_ForceReadWriteReason** -Vrednost celog broja koja predstavlja razlog zbog kog je datoteka primorana da se otvori u režimu za čitanje/pisanje
    
- **Data_LastLoggedTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada otvaranje dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka)

- **Data_LinkStyles** - Ukazuje na to da li se povezujemo sa stilovima predložaka

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word

- **Data_Measurements** - Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata Koristi se za merenje performansi.
    
- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_PartsUnknown** - broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo.

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja.

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument.

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku.


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Ovaj događaj ukazuje na to da Office Word otvara dokument putem COM aktivacije ili komandne linije. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke iz komandne linije radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemRes -** Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

  - **Data\_BytesAsynchronous -** Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

  - **Data\_BytesAsynchronousWithWork -** Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

  - **Data\_BytesSynchronous -** Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

  - **Data\_BytesUnknown -** Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

  - **Data\_Doc\_AccessMode -** Dokument je samo za čitanje/ili može da se uređuje

  - **Data\_Doc\_AssistedReadingReasons -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu za čitanje

  - **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType -** Jedinice koje se koriste za postepeno otvaranje dokumenta

  - **Data\_Doc\_EdpState -** Postavke za zaštitu elektronskih podataka dokumenta

  - **Data\_Doc\_Ext -** Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

  - **Data\_Doc\_FileFormat -** Verzija protokola za format datoteke

  - **Data\_Doc\_Fqdn -** Ime domena za OneDrive ili SharePoint Online 

  - **Data\_Doc\_FqdnHash -** Jednosmerni heš imena domena koji se može identifikovati

  - **Data\_Doc\_IOFlags -** Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

  - **Data\_Doc\_IdentityTelemetryId -** Jednosmerni heš identiteta korisnika koji se koristi za izvršavanje otvaranja

  - **Data\_Doc\_InitializationScenario -** Beleži način na koji je otvoren dokument

  - **Data\_Doc\_IrmRights -** Radnje koje su dozvoljene putem smernica za zaštitu elektronskih podataka koje su primenjene na dokument/korisnika

  - **Data\_Doc\_IsIncrementalOpen -** Zastavica koja ukazuje na to da je dokument postepeno otvoren

  - **Data\_Doc\_IsOcsSupported -** Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

  - **Data\_Doc\_IsOpeningOfflineCopy -** Zastavica koja ukazuje na to da je otvorena vanmrežna kopija dokumenta

  - **Data\_Doc\_IsSyncBacked -** Zastavica koja ukazuje na to da na računaru postoji kopija dokumenta koja se automatski sinhronizuje

  - **Data\_Doc\_Location -** Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint)

  - **Data\_Doc\_LocationDetails -** Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

  - **Data\_Doc\_NumberCoAuthors -** Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

  - **Data\_Doc\_PasswordFlags -** Ukazuje na skup zastavica koje obeležavaju lozinke za čitanje ili čitanje/pisanje

  - **Data\_Doc\_ReadOnlyReasons -** Razlozi zbog kojih je dokument otvoren samo za čitanje

  - **Data\_Doc\_ResourceIdHash -** Anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data_Doc_RtcType -**  Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

  - **Data\_Doc\_ServerDocId -** Nepromenljivi anonimni identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

  - **Data\_Doc\_ServerProtocol -** Verzija protokola koji se koristi za komunikaciju sa uslugom

  - **Data\_Doc\_ServerType -** Tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

  - **Data\_Doc\_ServerVersion -** Verzija servera koji nudi uslugu

  - **Data\_Doc\_SessionId -** Verzija servera koji nudi uslugu

  - **Data\_Doc\_SharePointServiceContext -** Informacije o dijagnostici iz zahteva za SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Indikator veličine dokumenta

  - **Data\_Doc\_SpecialChars -** Indikator specijalnih znakova u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StreamAvailability -** Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

  - **Data\_Doc\_SyncBackedType -** Indikator tipa dokumenta (lokalni ili iz usluge)

  - **Data\_Doc\_UrlHash -** Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

  - **Data\_Doc\_WopiServiceId -** Sadrži jedinstveni identifikator WOPI dobavljača usluge

  - **Data\_EditorDisablingRename -** Identifikator prvog urednika koji je uzrokovao onemogućavanje opcije preimenovanja

  - **Data\_EditorsCount -** Broj urednika dokumenta

  - **Data\_FSucceededAfterRecoverableFailure -** Ukazuje na to da je otvaranje uspelo nakon popravke greške prilikom otvaranja dokumenta

  - **Data\_ForceReadWriteReason -** Vrednost celog broja koja predstavlja razlog zbog kog je datoteka primorana da se otvori u režimu za čitanje/pisanje

  - **Data\_LastLoggedTag -** Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada otvaranje dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka)

  - **Data\_LinkStyles -** Ukazuje na to da li se povezujemo sa stilovima predložaka

  - **Data\_MainPdod -** Identifikator dokumenta koji se obrađuje u programu Office Word

  - **Data\_Measurements -** Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata Koristi se za dijagnostikovanje performanse otvaranja.

  - **Data\_MoveDisabledReason -** Greška koja onemogućava premeštanje dokumenta

  - **Data\_MoveFlightEnabled -** Da li je omogućena putanja za funkciju premeštanja

  - **Data\_PartsUnknown -** broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

  - **Data\_RecoverableFailureInitiationLocationTag -** Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo

  - **Data\_RenameDisabledReason -** Greška koja uzrokuje nemogućnost preimenovanja dokumenta

  - **Data\_RenameFlightEnabled -** Da li je omogućena putanja za funkciju preimenovanja

  - **Data\_SecondaryTag -** Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja.

  - **Data\_TemplateFormat -** Format datoteke predloška na kome je zasnovan dokument.

  - **Data\_UsesNormal -** Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku.


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Ovaj događaj ukazuje na to da Office Word otvara dokument putem dijaloga „Otvaranje“. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke pomoću dijaloga „Otvaranje“ radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** - Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo
    
- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

- **Data_BytesUnknown** - Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

- **Data_DetachedDuration** - Koliko dugo je radnja odvojena od niti

- **Data_Doc_AccessMode** -Dokument je samo za čitanje/ili može da se uređuje

- **Data_Doc_AssistedReadingReasons** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

- **Data_Doc_AsyncOpenKind –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

- **Data_Doc_ChunkingType** - Jedinice koje se koriste za postepeno otvaranje dokumenta

- **Data_Doc_EdpState** - Postavke elektronske zaštite podataka za dokument

- **Data_Doc_Ext** - Oznaka tipa dokumenta (docx/xlsb/pptx, itd.)

- **Data_Doc_FileFormat** - Verzija protokola za format datoteke

- **Data_Doc_Fqdn** - Ime domena za OneDrive ili SharePoint Online

- **Data_Doc_FqdnHash** - Jednosmerni heš imena domena koji se može identifikovati

- **Data_Doc_IdentityTelemetryId** - Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja

- **Data_Doc_InitializationScenario** - Beleži način na koji je otvoren dokument

- **Data_Doc_IOFlags** - Izveštava o keširanim zastavicama koje su korišćene za podešavanje postavki zahteva za otvaranje

- **Data_Doc_IrmRights** - Radnje koje su dozvoljene putem smernica za elektronskih zaštitu podataka koje su primenjene na dokument/korisnika
    
- **Data_Doc_IsIncrementalOpen** - Zastavica koja označava da je dokument postepeno otvoren

- **Data_Doc_IsOcsSupported** - Zastavica koja ukazuje na to da je dokument podržan u usluzi saradnje

- **Data_Doc_IsOpeningOfflineCopy** - Zastavica koja ukazuje na to je otvorena vanmrežna kopija dokumenta

- **Data_Doc_IsSyncBacked** -Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** - Označava kako je kanal u realnom vremenu (RTC) podešen za trenutnu datoteku (onemogućen, nije podržan, na zahtev, uvek uključen, itd.)

- **Data_Doc_ServerDocId** - Nepromenljivi anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi 

- **Data_Doc_ServerProtocol** - verzija protokola koji se koristi za komunikaciju sa uslugom

- **Data_Doc_ServerType** - tip servera koji nudi uslugu (SharePoint, OneDrive, WOPI, itd.)

- **Data_Doc_ServerVersion** - verzija servera koji nudi uslugu

- **Data_Doc_SessionId** -Identifikuje određenu sesiju uređivanja dokumenta u okviru cele sesije

- **Data_Doc_SharePointServiceContext** - Informacije o dijagnostici iz zahteva usluge SharePoint Online

- **Data_Doc_SizeInBytes** - Indikator veličine dokumenta

- **Data_Doc_SpecialChars** - Indikator specijalnih znakova u URL adresi ili putanji dokumenta

- **Data_Doc_StreamAvailability** - Indikator koji ukazuje na to da li je protok dokumenta omogućen/onemogućen

- **Data_Doc_SyncBackedType** - Indikator tipa dokumenta (lokalni ili iz usluge)

- **Data_Doc_UrlHash** - Jednosmerni heš za kreiranje identifikatora jednostavnog dokumenta

- **Data_EditorDisablingRename** -Identifikator prvog urednika zbog kojeg je onemogućeno preimenovanje

- **Data_EditorsCount** - Broj urednika dokumenta

- **Data_ForceReadWriteReason** -Vrednost celog broja koja predstavlja razlog zbog kog je datoteka primorana da se otvori u režimu za čitanje/pisanje
    
- **Data_FSucceededAfterRecoverableFailure** - Ukazuje na to da je otvaranje uspelo nakon popravke greške prilikom otvaranja dokumenta

- **Data_LastLoggedTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za identifikovanje kada pokušaj čuvanja dva puta ne uspe (koristi se za dijagnostiku kvaliteta podataka)

- **Data_LinkStyles** - Ukazuje na to da li se povezujemo sa stilovima predložaka

- **Data_MainPdod** - Identifikator dokumenta koji se obrađuje u programu Office Word

- **Data_Measurements** - Šifrovana niska koja sadrži analizu vremena otvaranja različitih segmenata Koristi se za merenje performansi.

- **Data_MoveDisabledReason** - Greška koja onemogućava premeštanje dokumenta

- **Data_MoveFlightEnabled** - Da li je omogućena putanja za funkciju premeštanja

- **Data_PartsUnknown** - broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku


#### <a name="renewuserop"></a>RenewUserOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije obnavljanja korisničkih certifikata. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera sistema za evidenciju

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji HTTP operacija

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Type** - Tip informacija o korisniku

#### <a name="servicediscoveryop"></a>ServiceDiscoveryOp

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu.  Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom izvršavanja operacije pronalaženja usluge. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji http operacija

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – Ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije


### <a name="office-accessibility-configuration-subtype"></a>*Podtip konfiguracije pristupačnosti sistema Office*

Funkcije pristupačnosti u sistemu Office

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Omogućava nam da otkrijemo da li korisnik ima alatku za pomoćnu tehnologiju i koje je njeno ime. Time možemo da razumemo da li korisnik sistema Office ima probleme sa određenom alatkom za pomoćnu tehnologiju.

Prikupljaju se sledeća polja:

  - **Data\_Data\_Jaws -** ukazuje na to da li je alatka „Jaws“ radila tokom sesije**Data\_Data\_Magic -** ukazuje na to da li je alatka „Magic“ radila tokom sesije

  - **Data\_Data\_Magnify -** ukazuje na to da li je alatka „Lupa“ radila tokom sesije

  - **Data\_Data\_Narrator -** ukazuje na to da li je alatka „Narator“ radila tokom sesije

  - **Data\_Data\_NVDA -** ukazuje na to da li je alatka „NVDA“ radila tokom sesije

  - **Data\_Data\_SA -** ukazuje na to da li je alatka „SA“ radila tokom sesije

  - **Data\_Data\_Supernova -** ukazuje na to da li je alatka „Supernova“ radila tokom sesije

  - **Data\_Data\_SuperNovaessSuite -** ukazuje na to da li je SuperNovaAccessSuite radio tokom sesije

  - **Data\_Data\_WinEyes -** ukazuje na to da li je alatka „WinEyes“ radila tokom sesije

  - **Data\_Data\_ZoomText -** ukazuje na to da li je alatka „Zumiranje teksta“ radila tokom sesije

#### <a name="office_apple_darkmode"></a>Office_Apple_DarkMode

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam govori da li je korisnik pokrenuo sistem u Tamnom režimu i da li je korisnik zamenio postavku sistema Tamnog režima u aplikaciji Office.  Koristimo ovaj događaj da bismo obezbedili pristupačnost i odredili prioritete u optimizaciji korisničkog iskustva.

Prikupljaju se sledeća polja:

- **Data_DarkModeIsEnabled** - da li je Tamni režim omoguće u sistemu.

- **Data_RequiresAquaSystemAppearanceEnabled** - da li je Tamni režim zamenjen u aplikaciji Office.

#### <a name="office_apple_hardwarekeyboardinuse_apple"></a>Office_Apple_HardwareKeyboardInUse_Apple

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam govori da korisnik priključuje tastaturu na svoj mobilni uređaj. Događaj nam pomaže da poboljšamo pristupačnost i optimizujemo korisničko iskustvo.


Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka koja označava vreme prikupljanja događaja.

#### <a name="office_apple_mbuinstrument_deviceaccessibilitysettings"></a>Office_Apple_MbuInstrument_DeviceAccessibilitySettings

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj prikuplja stanje različitih opcija pristupačnosti dostupnih tokom sesije. Koristimo ovaj događaj da bismo obezbedili pristupačnost i odredili prioritete u optimizaciji korisničkog iskustva.

Prikupljaju se sledeća polja:

- **Data_AccessibilityContentSize** - zastavica koja označava da li je ova postavka omogućena

- **Data_AssistiveTouchRunning** - zastavica koja označava da li je ova postavka omogućena

- **Data_BoldTextEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_CollectionTime** - zastavica koja označava da li je ova postavka omogućena

- **Data_DarkerSystemColorsEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_DifferentiateWithoutColor** - zastavica koja označava da li je ova postavka omogućena

- **Data_GrayscaleEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_GuidedAccessEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_IncreaseContrast** - zastavica koja označava da li je ova postavka omogućena

- **Data_InvertColorsEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_PreferredContentSizeCategory** - zastavica koja označava da li je ova postavka omogućena

- **Data_ReduceMotionEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_ReduceTransparency** - zastavica koja označava da li je ova postavka omogućena

- **Data_ReduceTransparencyEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_ShakeToUndeEnabled** - zastavica koja označava da li je ova postavka omogućena. (Zastarelo - koristi se samo na starim verzijama.)

- **Data_ShakeToUndoEnabled** - zastavica koja označava da li je ova postavka omogućena.

- **Data_SpeakScreenEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_SpeakSelectionEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_SwitchControlRunning** - zastavica koja označava da li je ova postavka omogućena

- **Data_UAZoomEnabled** - zastavica koja označava da li je ova postavka omogućena

- **Data_VoiceOverRunning** - zastavica koja označava da li je ova postavka omogućena

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Ovaj događaj ukazuje na to da program Office Word čita naglas tekst iz dokumenta. Događaj je otkucaj funkcije pristupačnosti koji omogućava korporaciji Microsoft da proceni ispravnost funkcije čitanja naglas.

Prikupljaju se sledeća polja:

  - **Data\_CharacterCount -** broj znakova u dokumentu

  - **Data\_CharactersWithSpaceCount -** broj znakova i razmaka u dokumentu

  - **Data\_IsPageCountInProgress -** da li je brojanje stranica u toku

  - **Data\_LineCount -** broj redova u dokumentu

  - **Data\_PageCount -** broj stranica u dokumentu

  - **Data\_ParagraphCount -** broj pasusa u dokumentu

  - **Data\_Play -** Da li program Word čita naglas prvi put

  - **Data\_ViewKind -** Tip prikaza dokumenta

  - **Data\_WordCount -** broj reči u dokumentu

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Ovaj događaj ukazuje na to da je program Office Word prestao da čita naglas tekst iz dokumenta. Ovo omogućava korporaciji Microsoft da proceni ispravnost funkcije čitanja naglas tako što meri trajanje rada.

Prikupljaju se sledeća polja:

  - Nijedno

### <a name="privacy-subtype"></a>*Podtip privatnosti*

Postavke privatnosti za Office 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a>Office.IntelligentService.PrivacyConsent.PrivacyEvent

Ovaj događaj predstavlja akciju koju je pokrenuo korisnik ili sistem koji je deo korisničkog iskustva za Office. Pokreće se u dijalozima Prvo pokretanje privatnosti, dijalogu Privatnost naloga i obaveštenjima o privatnosti. Događaj se koristi da bi se razumelo sledeće: korisnici koji su saglasni sa postavkama privatnosti za Office, korisnici koji menjaju postavke privatnosti za Office i postavke privatnosti za Office koje se ažuriraju u korisničkim sesijama.

Prikupljaju se sledeća polja:

  - **Data_ActionId - ** Radnja korisnika u dijalogu „Privatnost“

  - **Data_ControllerConnectedServicesState –** Postavka korisničke politike za dodatna opciona povezana iskustva

  - **Data_DownloadedContentServiceGroupState –** Korisničke postavke za preuzet sadržaj 
 
  - **Data_ForwardLinkId-** Veza sa dokumentacijom o privatnosti za korisnički scenario

  - **Data_HRESULT-** Zapis grešaka tokom interakcije sa dijalogom o privatnosti

  - **Data_IsEnterpriseUser –** Kategorija licence korisnika

  - **Data_OfficeServiceConnectionState –** Korisnička podešavanje za povezane usluge

  - **Data_RecordRegistry –** Zapis o prikazivanju dijaloga o privatnosti preduzeća

  - **Data_Scenario –** Scenario prvog pokretanja zasnovan na korisničkoj licenci i kategoriji

  - **Data_SeenInsidersDialog –** Zapis o prikazivanju dijaloga o privatnosti insajdera

  - **Data_SendTelemetryOption –** Korisničko podešavanje za telemetriju

  - **Data_SendTelemetryOption –** Postavka korisničkih smernica za telemetriju

  - **Data_UserCategory –** Tip korisničkog naloga  

  - **Data_UserCCSDisabled-** Korisnička razmena za dodatna opciona povezana iskustva

   - **Data_UserContentServiceGroupState –** Korisničke postavke za analizu sadržaja

  - **Data_WillShowDialogs –** Zapis korisnika koji treba da vidi prvi put pokrenut dijalog o privatnosti



## <a name="product-and-service-performance-data-events"></a>Podaci događaja performanse proizvoda i usluga

Podtipovi podataka koji spadaju u ovu kategoriji su:
- [Neočekivani izlaz iz aplikacije (pad)](#unexpected-application-exit-crash-subtype)
- [Performanse funkcija aplikacije](#application-feature-performance-subtype)
- [Greška u aktivnosti aplikacije](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Podtip neočekivanog izlaza iz aplikacije (pad)*

Neočekivani izlazi iz aplikacije i njeno stanje u trenutku kada se to dogodi.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Prikuplja informacije o nekontrolisanim izuzecima pomoću aplikacije Data Streamer. Ti podaci se koriste za praćenje ispravnosti aplikacije. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Exception** - Niz poziva za izuzetak

- **Event Name** - Ime događaja, što je kategorija i oznaka događaja

#### <a name="office_apple_identitydomainname"></a>Office_Apple_IdentityDomainName

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja našeg sistema kao i za istraživanje uzroka neuspeha određenih korisnika domena. Prikupljamo domen koji koriste naši korisnici prilikom potvrde identiteta.  Ove podatke koristimo da bismo pomogli da identifikujemo i ispravimo one probleme koji na širem nivou možda ne deluju previše uticajno, ali za koje se ispostavi da su vrlo uticajni za određeni domen korisnika.

Prikupljaju se sledeća polja:

- **Data_Domain** - domen koji se koristi za potvrdu identiteta

- **Data_IdentityProvider** - ime dobavljača identiteta za potvrdu identiteta. (npr. LiveId ili ADAL)

- **Data_IdentityProviderEnum** - kod dobavljača identiteta za potvrdu identiteta. (Broj)

#### <a name="office_apple_systemhealthappexitmacandios"></a>Office_Apple_SystemHealthAppExitMacAndiOS

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja naših Office aplikacija kao i za istraživanje uzroka neuspeha. Prikupljamo podatke o svakom izlazu iz aplikacije kako bismo utvrdili da li je aplikacija zatvorena bez poteškoća.

Prikupljaju se sledeća polja:

- **Data_AffectedProcessSessionID** - identifikator za sesiju koja ima izlaz iz aplikacije.

- **Data_AffectedSessionBuildNumber** - pomoćna verzija aplikacije u kojoj je uočen izlaz iz aplikacije.

- **Data_AffectedSessionDuration** - dužina sesije od početka do kraja

- **Data_AffectedSessionIDSMatch** - indikator stanja telemetrije.

- **Data_AffectedSessionMERPSessionID** - indikator stanja telemetrije.

- **Data_AffectedSessionOSLocale** - lokalni standard OS-a pod kojim je uočen izlaz iz aplikacije.

- **Data_AffectedSessionOSVersion** - verzija OS-a u kojoj je uočen izlaz iz aplikacije.

- **Data_AffectedSessionResidentMemoryOnCrash** - količina ugrađene memorije koja je potrošena kada je došlo do izlaza iz aplikacije

- **Data_AffectedSessionStackHash** - identifikator koji označava da je pogođena određena greška.

- **Data_AffectedSessionStartTime** - vreme kada je sesija počela.

- **Data_AffectedSessionUAEType** - tip uočenog izlaza iz aplikacije (ako je to bio izlaz sa poteškoćama, ovaj kod će označavati tip uočene greške)

- **Data_AffectedSessionVersion** - glavna verzija aplikacije u kojoj je uočen izlaz iz aplikacije.

- **Data_AffectedSessionVirtualMemoryOnCrash** - količina virtualne memorije koja je potrošena kada je došlo do izlaza iz aplikacije.

- **Data_ExitWasGraceful** - da li je izlaz iz aplikacije protekao bez poteškoća ili ne.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Događaj koji se generiše kada padne programski dodatak COM na potrošačkoj verziji Office aplikacija. 

Upotreba: koristi se za računanje globalnog „usvajanja“ programa Office 365 ProPlus za neodređena velika preduzeća za dodatak koji se zatim objavljuje na sajtu readyforwindows.com i drugim alatkama kao što je Readiness Toolkit To omogućava poslovnim kupcima da provere da li su programski dodaci koje su ugradili u njihove organizacije kompatibilni sa najnovijim verzijama programa Office 365 ProPlus i da na odgovarajući način planiraju nadogradnje. 

Prikupljaju se sledeća polja:

- **ScopeId** - trenutni opseg niti

- **Method** - Office metod u kome je došlo do izuzetka

- **Interface** - Interfejs sistema Office u kome je došlo do izuzetka

- **AddinId** - Id klase programskog dodatka

- **AddinProgId** – zastarelo

- **AddinFriendlyName** – zastarelo

- **AddinTimeDateStamp** – vremenska oznaka programskog dodatka dobijena iz DLL metapodataka

- **AddinVersion** – zastarelo

- **AddinFileName** – zastarelo

- **VSTOAddIn** - da li je VSTO programski dodatak

- **AddinConnectFlag** - trenutno ponašanje učitavanja

- **LoadAttempts** - broj pokušaja učitavanja programskog dodatka

#### <a name="officeextensibilitycomaddinunhandledexceptionenterprise"></a>Office.Extensibility.COMAddinUnhandledExceptionEnterprise

Događaj koji se generiše kada padne programski dodatak COM na poslovnoj verziji Office aplikacija.

Upotreba: koristi se za računanje globalnog „usvajanja“ programa Office 365 ProPlus za neodređena velika preduzeća za dodatak koji se zatim objavljuje na sajtu readyforwindows.com i drugim alatkama kao što je Readiness Toolkit To omogućava poslovnim kupcima da provere da li su programski dodaci koje su ugradili u njihove organizacije kompatibilni sa najnovijim verzijama programa Office 365 ProPlus i da na odgovarajući način planiraju nadogradnje. 

- **ScopeId** - trenutni opseg niti

- **Method** - Office metod u kome je došlo do izuzetka

- **Interface** - Interfejs sistema Office u kome je došlo do izuzetka

- **AddinId** - Id klase programskog dodatka

- **AddinProgId** – zastarelo

- **AddinFriendlyName** – zastarelo

- **AddinTimeDateStamp** – vremenska oznaka programskog dodatka dobijena iz DLL metapodataka

- **AddinVersion** – zastarelo

- **AddinFileName** – zastarelo

- **VSTOAddIn** - da li je VSTO programski dodatak

- **AddinConnectFlag** - trenutno ponašanje učitavanja

- **LoadAttempts** - broj pokušaja učitavanja programskog dodatka

#### <a name="officeextensibilitysandboxodpactivationheartbeat"></a>Office.Extensibility.Sandbox.ODPActivationHeartbeat

Programski dodaci za Office u sandboxu. Ovaj događaj prikuplja informacije o otkucajima srca o aktivacijama. Kada se programski dodatak sruši, ovaj događaj prikuplja zašto se srušio u slučaju da je povezan sa našim sandboxom. Koristi se za istraživanje kada klijenti eskaliraju probleme.
 
Prikupljaju se sledeća polja:

- **AppId** -ID aplikacije

- **AppInfo** - Podaci u vezi sa tipom programskog dodatka (okno zadatka ili UILess ili u sadržaju itd.) i tip dobavljača (Omen, SharePoint, okviru sistema datoteka itd.)

- **AppInstanceId** – ID instance aplikacije 

- **AssetId** - ID Procene za aplikaciju

- **ErrorCode** – Ukupno potrošeno vreme 

- **NumberOfAddinsActivated**- Brojač aktivnih programskih dodataka

- **RemoterType** – Precizira tip daljinca (pouzdanih, nepouzdanih, Win32webView, pouzdanih UDF-ova itd.) koji se koristi za aktiviranje programskog dodatka

- **StoreType** – Poreklo aplikacije

- **Tag**- navodi gde tačno kod nije uspeo pomoću jedinstvene oznake koja je s njim povezana.

- **UsesSharedRuntime** - označava da li aplikacija koristi sharedRuntime ili ne.


#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Događaj koji se generiše kada datoteka sa omogućenim makroima naiđe na grešku u kompajliranju ili izvršavanju.

Analitika za stone računare: Koristi se kao brojilac za izračunavanje statusa ispravnosti tipova makroa (npr. makro u programu Word, u programu Excel, itd.) u određenim velikim preduzećima, što služi da se tokom probe odredi da li je programski dodatak „spreman za ažuriranje“ u proizvodnom krugu.

Prikupljaju se sledeća polja:

- **TagId** - id oznake telemetrije

- **BreakReason** - razlog prekida (greška u izvršavanju, kompajliranju, ostalom)

- **SolutionType** - tip rešenja (dokument, predložak, programski dodatak aplikacije, programski dodatak COM)

- **Data.ErrorCode** - kôd greške koji je prijavila VBA mašina


#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Prikuplja se kada aplikacija ne uspeva da se pokrene zbog neočekivane greške prilikom pokretanja. Koristi se za praćenje izuzetaka i padova.  Pomaže u nadgledanju i otklanjanju grešaka ispravnosti aplikacije.

Prikupljaju se sledeća polja: 

- **DateTime** - Vremenska oznaka kada je događaj evidentiran.

- **EventName** - Ime događaja koji se evidentira.

#### <a name="officeoutlookdesktophangbucketmetrics"></a>Office.Outlook.Desktop.HangBucketMetrics

Prikuplja vreme prekida u programu Outlook - jedinstveni identifikator po prekidu, proteklo vreme i informacije o nizu poziva Podaci se koriste za otkrivanje i identifikovanje padova aplikacije da bi se otklonila greška u budućim ažuriranjima.

Prikupljaju se sledeća polja:

  - **BucketId** - heš niza poziva

  - **ElapsedTotal** - ukupno vreme provedeno u pozivu

  - **ElapsedHanging** - vreme trajanja prekida poziva

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a>Office.Outlook.Desktop.HangReportingScopePerfMetrics

Prikuplja podatke o vremenu koje je potrebno da se izvrše osnovne situacije u programu Outlook - promena fascikle, promena modula, slanje pošte iz otpremnog sandučeta, klasično otvaranje stavki, transport e-pošte. Ovi podaci se aktivno prate da bi se pronašli neuobičajeni problemi sa performansama. Koristi se za otkrivanje i dijagnostikovanje problema sa performansama, kao i za poboljšanje istih sa svakim ažuriranjem.

Prikupljaju se sledeća polja:

  - **ElapsedTotal** - Ukupno vreme provedeno u pozivu

  - **ScopeId** - ime funkcije koja sadrži deklaraciju ili prilagođeno ime koje je dobijeno putem definicije opsega

#### <a name="officeoutlookdesktopwatsonbuckets"></a>Office.Outlook.Desktop.WatsonBuckets

Ovo pravilo prikuplja informacije o padu iz evidencije događaja ako je program Outlook pao u prethodnoj sesiji.

Podaci se aktivno prate da bi se pronašli neuobičajeni prekidi. Koriste se za otkrivanje i identifikovanje prekida da bi se otklonila greška u budućim ažuriranjima.

Prikupljaju se sledeća polja:

  - **BucketId** - heš niza poziva

  - **ElapsedTotal** - ukupno vreme provedeno u pozivu

  - **ElapsedHanging** - vreme trajanja prekida poziva

#### <a name="officepowerpointsession"></a>Office.PowerPoint.Session

Prikuplja podatke o upotrebi funkcije pri svakoj PowerPoint sesiji. Ti podaci se koriste za izračunavanje stope nasilnih izlaza iz programa PowerPoint prilikom upotrebe funkcije. Stopa nasilnih izlaza iz programa PowerPoint predstavlja ključni pokazatelj koji garantuje da se program izvršava kao što je očekivano.

Prikupljaju se sledeća polja:

  - **Flag** - zastavice koje označavaju sesije

  - **Usage** - upotrebe funkcije

#### <a name="officepowerpointuaedialog"></a>Office.PowerPoint.UAE.Dialog

Prikuplja se svaki put kada se PowerPoint nasilno zatvori dok je na vrhu glavnog prozora programa otvoren dijalog. Ove informacije su bitne da bi se primetili nasilni izlazi iz programa PowerPoint koje uzrokuje aktivni dijalog tako što blokira glavni prozor programa. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **DlgCnt** - ukupan broj otvorenih dijaloga kada je sesija pala

  - **DlgId** - identifikator otvorenog dijaloga

  - **IdType** - identifikator tipa otvorenog dijaloga

  - **InitTime** - vreme pokretanja pale sesije

  - **SessionId** - identifikator pale sesije

  - **TopId** - identifikator najvažnijeg dijaloga

  - **Version** - verzija pale sesije

#### <a name="officepowerpointuaedocument"></a>Office.PowerPoint.UAE.Document

Prikuplja podatke o tome koja funkcija je korišćena u dokumentu u trenutku kada je PowerPoint nasilno zatvoren. Ove funkcije uključuju projekciju slajdova, otvaranje dokumenta, čuvanje, uređivanje, koautorstvo, isključivanje. Te informacije su bitne da bi se primetili nasilni izlasci iz programa prilikom upotrebe funkcije. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **CoauthFlag** - zastavice koje označavaju upotrebu funkcije koautorstva

  - **CommandFlag** zastavice koje označavaju izmenu dokumenta

  - **FileIOFlag** - zastavice koje označavaju upotrebu datoteke IO

  - **InitTime** - vreme pokretanja pale sesije

  - **Location** - lokacija dokumenta

  - **ServerDocId** - identifikator servera dokumenta

  - **SessionId** - identifikator pale sesije

  - **UrlHash** - heš URL adrese dokumenta

  - **Usage** - upotrebe funkcije

  - **Version** - verzija pale sesije

#### <a name="officepowerpointuaeopen"></a>Office.PowerPoint.UAE.Open

Prikuplja se svaki put kada se PowerPoint nasilno zatvori prilikom otvaranja dokumenta. Te informacije su bitne da bi se primetili nasilni izlasci iz programa prilikom otvaranja dokumenta. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **FileUrlLocation** - lokacija URL adrese dokumenta

  - **Flag** - zastavice koje označavaju otvaranje

  - **InitTime** - vreme pokretanja pale sesije

  - **Location** - lokacija dokumenta

  - **OpenReason** - razlog otvaranja

  - **ServerDocId** - identifikator servera dokumenta

  - **SessionId** - identifikator pale sesije

  - **UrlHash** - heš URL adrese dokumenta

  - **Version** - verzija pale sesije

#### <a name="officepowerpointuaesession"></a>Office.PowerPoint.UAE.Session

Prikuplja podatke o tome koja funkcija je korišćena u trenutku kada je PowerPoint sesija nasilno zatvorena.Te informacije su bitne da bi se primetili nasilni izlasci iz programa. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **Flag** - zastavice koje označavaju sesije

  - **InitTime** - vreme pokretanja pale sesije

  - **PreviousSessionId** - identifikator pale sesije

  - **Usage** - upotrebe funkcije

  - **Version** - verzija pale sesije

#### <a name="officepowerpointuaeshutdown"></a>Office.PowerPoint.UAE.Shutdown

Prikuplja podatke o nasilnim izlascima prilikom isključivanja programa PowerPoint. Te informacije su bitne da bi se primetili nasilni izlasci iz programa prilikom isključivanja. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao pokretanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **InitTime** - vreme pokretanja pale sesije

  - **SessionId** - identifikator pale sesije

  - **Stage** - faza isključivanja

  - **Version** - verzija pale sesije

#### <a name="officepowerpointuaeslideshow"></a>Office.PowerPoint.UAE.SlideShow

Prikuplja podatke o nasilnim izlascima prilikom isključivanja programa PowerPoint. Te informacije su bitne da bi se primetili nasilni izlasci iz programa prilikom isključivanja. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao pokretanje programa kao što je očekivano.

Prikupljaju se sledeća polja:

  - **InitTime** - vreme pokretanja pale sesije

  - **Mode** - režim projekcije slajdova

  - **SessionId** - identifikator pale sesije

  - **State** - status projekcije slajdova

  - **Version** - verzija pale sesije

#### <a name="officeprogrammabilitytelemetryaddincrash"></a>Office.Programmability.Telemetry.AddInCrash

Događaj koji se generiše kada se učita programski dodatak COM. Ove informacije su bitne da bi se odredilo da li je programski dodatak izazvao pad Office aplikacije. Koriste se za procenu opšte kompatibilnosti programskog dodatka sa Office aplikacijama.

Prikupljaju se sledeća polja:

  - **CLSID** - identifikator klase programskog dodatka

  - **ConnectFlag** - trenutno ponašanje učitavanja programskog dodatka

  - **FileName** - ime datoteke programskog dodatka, osim putanje datoteke

  - **FriendlyName** - prepoznatljivo ime programskog dodatka

  - **Interface** - Interfejs sistema Office u kome je došlo do izuzetka

  - **LoadAttempts** - broj pokušaja učitavanja programskog dodatka

  - **Method** - Office metod u kome je došlo do izuzetka

  - **OfficeApplication** - Office aplikacija u kojoj je došlo do izuzetka

  - **OfficeVersion** – verzija sistema Office

  - **ProgID** - Prog identifikator programskog dodatka

#### <a name="officeprogrammabilitytelemetrymacrofileopened"></a>Office.Programmability.Telemetry.MacroFileOpened 

Pokrenut pri otvaranju datoteke koja sadrži makro (VBA) na uređaju koji je IT administrator uveo u sistem korišćenja Office aplikacija kao usluge (OAAS) i gde je Office 365 ProPlus aktiviran pomoću licence za velika preduzeća. Događaj se koristi za razumevanje ispravnosti datoteka koje sadrže makro (VBA) u zakupcu i upoređuje se sa Office.Programmability.Telemetry.VbaTelemetryBreak koji prati greške na datotekama koje sadrže VBA. 

Ne prikuplja se ni jedno polje.

#### <a name="officesystemsystemhealthungracefulappexitmacandios"></a>Office.System.SystemHealthUngracefulAppExitMacAndiOS

Na festivalu pokretanja koji obuhvata negraciozne izlaze iz aplikacije radi dalje istrage.

Prikupljaju se sledeća polja:

- **AffectedProcessAppBuild** – Broj verzije

- **AffectedProcessAppBuildRevision** – Broj verzije revizije

- **AffectedProcessAppMajorVer** – Veliki broj verzije aplikacije

- **AffectedProcessAppMinorVer** – Mali broj verzije aplikacije

- **AffectedProcessAppName** – Ime aplikacije

- **AffectedProcessResidentMemoryOnCrash** – Stambena memorija srušene aplikacije

- **AffectedProcessUnsymbolicatedChecksum** - Ide sa kompletom hash za simbolizaciju

- **AffectedProcessVirtualMemoryOnCrash** - Virtuelna memorija srušene aplikacije

- **AffectedSessionDuration** – Trajanje sesije u sekundama pri padu

- **AffectedSessionLongBuildNumber** – Dugački broj izgradnje

- **CrashedProcessSessionID** – ID sesije procesa u padu aplikacije

- **DetectionTime** – Datum i vreme pada aplikacije
    
- **DeviceModel** – Hardver model

- **MERPSessionID** – ID sesije za MERP

- **ReportingOsLocaleTag** – standard OS

- **ReportingOSVerStr** – verzija OS

- **SessionBuildNumber** – Verzija srušene aplikacije

- **SessionIDSMatch** – Boolean da biste proverili da li je ID sesije prijavljivanja isti kao što je pokupila Merp

- **Sessionversion** –Verzija srušene aplikacije **– StackHash** – heš iz praćenja steka aplikacije "srušio se"

- **UAEType** – Enum koji nam daje informacije o tipu pada koji je bio

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Prikuplja informacije o izuzecima do kojih dolazi prilikom pokretanja aplikacije Data Streamer. Ti podaci se koriste za praćenje ispravnosti aplikacije. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Exception** - Niz poziva za izuzetak

- **Event Name** - Ime događaja, što je kategorija i oznaka događaja


### <a name="application-feature-performance-subtype"></a>*Podtip performanse funkcija aplikacije*

Loše vreme odziva ili performansi u scenarijima kao što su pokretanje aplikacije ili otvaranje datoteke.

#### <a name="initial_page_landing"></a>Initial_page_landing 
 
Ovaj događaj vam pomaže da pratite tip iskustva koju korisnici vide kada otvore stranicu naše aplikacije.  Ovi podaci se koriste za utvrđivanje prometa korisnika ugrađenih u svako iskustvo u našoj aplikaciji, i takođe nam pomažu da lako konsolidujemo rezultate eksperimentisanja.
 
Prikupljaju se sledeća polja: 

- **Page** - koristi se za praćenje tipa iskustva koje korisnik prvi put vidi kada otvori našu stranicu. Moguće vrednosti su: „Probna verzija“, „Preskoči“, „Prepakovano“, „Pretplata“, itd.

- **storeExperience** - ovo se koristi da se utvrdi da li je korisnik imao pravo da vidi iskustvo prodavnice SDK.

- **stringVariant** - ovo se koristi za utvrđivanje tipa niski koje korisnik vidi kada otvori našu stranicu. Imajte u vidu da za bilo koju stranicu, kao što je recimo „Probna verzija“, korisnik može da ima pravo da vidi različite niske na osnovu toga da li su imale instaliranu stariju verziju aplikacije Office ili ako su prethodno aktivirali Office. Moguća nabrajanja ovog svojstva su: „LegacyUpsell“, „OfficeOpened“, „Default“, YesIntent“, „NoIntent“, itd.

- **windowsBuildType** - koristi se za praćenje WindowsBuildType tipa na kojem je korisnik. Npr. „RS4“, „RS5“, „RS19H1“, „Vibranium“, itd. Pošto su naša iskustva obično usmerena na različite WindowsBuildTypes tipove, ovo svojstvo je od vitalne važnosti za razlikovanje objavljenih tipova. 

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpBootstrapUser API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** - Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije u URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** - Id privremenog zakupca za korisnika

- **RMS.HomeTenant** - Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** - Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga  

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** - Id scenarija definisan API-jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** - Id korisničkog objekta

#### <a name="json_parse_error"></a>json_parse_error 
 
Ovaj događaj označava da je grešku ubacio JSON analizator.  Moći ćemo da otklonimo grešku pročitanog registra niske koja je poslata u JSON analizator, da bismo omogućili glatko iskustvo našim korisnicima.
 
Prikupljaju se sledeća polja: 

- **Error** - sastoji se od poruke o grešci koju objekt greške vraća.

#### <a name="office_apple_apple_appboot_mac"></a>Office_Apple_Apple_AppBoot_Mac

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje vremena potrebnog za pokretanje aplikacije, kao i nekih detalja o tipu obavljenog pokretanja. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_ Data_EvtBootTimerDocStageReady** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_DocumentRecoveryInvoked** - da li je spasavanje dokumenta pozvano tokom pokretanja.

- **Data_EvtBootTimerBootIdle** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtBootTimerFinishLaunchEnd** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtBootTimerLaunchDidFinish** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtBootTimerLaunchStart** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtBootTimerMainStart** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtBootTimerStaticInit** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_EvtDockStageReady** - vreme proteklo do dostizanja određene tačke u kodu.

- **Data_IsFileOpenAttempted** - da li je pokušano otvaranje datoteke tokom pokretanja sistema.

- **Data_IsFirstRunAttempted** - da li je pokretanje aplikacije prošlo „Utisak pri prvom pokretanju“.

- **Data_SentToBackground** - da li je aplikacija poslata u pozadinu tokom pokretanja sistema.

#### <a name="office_apple_diskruleresultserializererroronstreamop"></a>Office_Apple_DiskRuleResultSerializerErrorOnStreamOp

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja telemetrijske infrastrukture. Ovaj događaj pokazuje da je došlo do greške.

Prikupljaju se sledeća polja:

- **Data_ActualBytesModified** - broj izmenjenih bajtova.

- **Data_BytesRequested** - broj bajtova za obradu.

- **Data_IsWriteOp** - bez obzira na to da li ćemo izvršiti operaciju pisanja

#### <a name="office_apple_macbootresourceusage"></a>Office_Apple_MacBootResourceUsage

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje više indikatora oko resursa koji se troše prilikom pokretanja pomoću Office aplikacija. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_BlockInputOperations** - broj blokiranih operacija ulaza

- **Data_BlockOutputOperations** - broj blokiranih operacija izlaza

- **Data_InvoluntaryContextSwitches** - broj nehotičnih kontekstnih prekidača

- **Data_MainThreadCPUTime** - mera proteklog vremena

- **Data_MaxResidentSize** - mera veličine memorije

- **Data_MessagesReceived** - broj primljenih poruka

- **Data_MessagesSent** - broj poslatih poruka

- **Data_PageFaults** - broj povrata stranica

- **Data_PageReclaims** - broj povrata stranica

- **Data_ProcessCPUTime** - mera proteklog vremena

- **Data_SharedTextMemorySize** - mera veličine memorije

- **Data_SignalsReceived** - broj primljenih signala

- **Data_Swaps** - broj zamena podataka

- **Data_SystemCPUTime** - mera proteklog vremena

- **Data_SystemUpTime** - mera proteklog vremena

- **Data_UnsharedDataSize** - mera veličine podataka

- **Data_UnsharedStackSize** - mera veličine steka

- **Data_UserCPUTime** - mera proteklog vremena

- **Data_VoluntaryContextSwitchesNvcsw** - broj nehotičnih kontekstnih prekidača

#### <a name="office_apple_mau_validation"></a>Office_Apple_MAU_Validation

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja komponente Microsoft automatskog ažuriranja koja se koristi za distribuciju i instaliranje ispravki aplikacija. Prikupljeni podaci koriste se za otkrivanje grešaka i istraživanje uzroka neuspeha.

Prikupljaju se sledeća polja:

- **Data_EventID** - prikupljamo nisku koja predstavlja kod greške

- **Data_Message** - prikupljamo nisku koja sadrži opis greške

#### <a name="office_apple_mbuinstrument_hang_detection_spin_control"></a>Office_Apple_MbuInstrument_Hang_Detection_Spin_Control

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se evidentira kad god se čini da neka aplikacija ne reaguje. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CountSpinControlStart** - označivač koji ukazuje na to da je aplikacija prestala da reaguje (ili da sporo reaguje)

#### <a name="office_apple_mbuinstrument_vmondocumentclose"></a>Office_Apple_MbuInstrument_VMOnDocumentClose

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom zatvaranja dokumenta. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="office_apple_mbuinstrument_vmonshutdown"></a>Office_Apple_MbuInstrument_VMOnShutdown

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom zatvaranja aplikacije. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="office_apple_mbuinstrument_vmonstart"></a>Office_Apple_MbuInstrument_VMOnStart

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom pokretanja aplikacije. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="office_apple_msoappdelegate_bootperf"></a>Office_Apple_MsoAppDelegate_BootPerf

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje vremena i memorije utrošene tokom pokretanja od strane Office aplikacija, kao i neke detalje o tipu izvršenog pokretanja. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_AppLaunchDurationMicroSec** - trajanje procesa pokretanja

- **Data_AppLaunchFinishSystemTime** - vremenska oznaka na određenom označivaču koda za pokretanje

- **Data_AppLaunchStartSystemTime** - vremenska oznaka na određenom označivaču koda za pokretanje

- **Data_ResidentMemory** - snimak raspoložive ugrađene memorije tokom pokretanja

- **Data_VirtualMemory** - snimak raspoložive virtuelne memorije tokom pokretanja

#### <a name="office_apple_ungracefulappexithangsinprevioussession"></a>Office_Apple_UngracefulAppExitHangsInPreviousSession

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja naših Office aplikacija kao i za istraživanje uzroka neuspeha. Prikupljamo podatak koliko se puta činilo da aplikacija ne reaguje pre nego što je došlo do izlaza iz aplikacije sa poteškoćama.

Prikupljaju se sledeća polja:

- **Data_HangsDetected** - podatak koliko se puta činilo da aplikacija ne reaguje pre nego što je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_LastSessionId** - identifikator za sesiju u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_SessionBuildNumber** - pomoćna verzija aplikacije u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_SessionVersion** - glavna verzija aplikacije u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

#### <a name="office_apple_whatsnewerrorandwarning"></a>Office_Apple_WhatsNewErrorAndWarning

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja funkcije „Šta je novo“. Ovaj događaj ukazuje na to da je došlo do greške/upozorenja tokom raščlanjivanja sadržaja „Šta je novo“, što ukazuje na potencijalni problem sa kreiranjem sadržaja.

Prikupljaju se sledeća polja:

- **Data_ContentKey** - pokazivač na deo sadržaja koji je verovatno prouzrokovao grešku.

- **Data_ErrorCode** - uočeni kôd greške (ako je dostupno)

- **Data_ErrorDescription** - opis greške (ako je dostupno)

- **Data_EventID** - prikupljamo nisku koja predstavlja tip uočene greške.

- **Data_IncludesHTMLTag** - da li sadržaj ima obogaćeni html

- **Data_IncludesItemsTag** - da li sadržaj ima hijerarhiju stavki

- **Data_LengthOfRawData** - veličina sadržaja

- **Data_RequestURL** - URL adresa sa koje je sadržaj preuzet

- **Data_ServerLanguageTag** - jezik na kojem je sadržaj.

- **Data_StatusCode** - status greške (ako je dostupno)

#### <a name="officeextensibilityrichapimethodinvocation"></a>Office.Extensibility.RichApiMethodInvocation

Kada klijent koristi programski dodatak za Office i telefonira obogaćeni API za pružanje usluge, ovaj događaj će biti aktiviran. Koristi se za merenje pouzdanosti usluge, performansi i upotrebe za pozivanje metoda Rich API.
 
Prikupljaju se sledeća polja:

- **API** - ime punog API-ja

- **DispFlag** - Mala zastava opisuje tip metoda poziva (Na primer: 0x1 = METHOD, 0x2 = PROPERTYGET, 0x4 = PROPERTYPUT, 0x8 = PROPERTYPUTREF)

- **DispId** - ID za metod koji se zove

- **HResult** - HResult za poziv metode

- **Latency** - Kašnjenje za poziv u mikrosekundama

- **ReqId** -GUID za zahtev za grupnu obradu koji ovaj metod pripada

- **TypeId** -GUID za interfejs za koji se ovaj metod zove


#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Telemetrija koja je ključna za praćenje neuspeha\\uspeha primene regulatornih postavki oblaka na registrator. „LastError“ ukazuje na to zašto i gde u registratoru nije uspela primena smernica.

Prikupljaju se sledeća polja:

  - **Data.ApplyLogMsg** - poruka o izuzetku prilikom primene smernica

  - **Data.Cid** - dinamički generisan identifikator korelacije koji se šalje usluzi kada je ona pozvana da bi dobavila smernice za oblak. Koristi se za označavanje uzajamne veze poziva koji je izazvao problem i smernica koje su u tom trenutku primenjene na oblak.

  - **Data.Last Error** - Jedna od pet vrednosti niske (brojači) koja evidentira fazu izvršavanja primene smernica tokom koje je došlo do izuzetka.

#### <a name="officeoutlookdesktopbootperfmetrics"></a>Office.Outlook.Desktop.BootPerfMetrics

Prikuplja vreme koje je potrebno za pokretanje programa Outlook. Vreme pokretanja programa se aktivno prati da bi se otkrile i dijagnostikovale regresije. Koristi se i za dijagnostikovanje eskalacije nezadovoljstva korisnika kao i za poboljšanje performansi pokretanja programa tokom vremena.

Prikupljaju se sledeća polja:

  - **AddinElapsedTotal** - Ukupno vreme koje je bilo potrebno za učitavanje programskih dodataka

  - **CredPromptCount** - Broj prikazanih upita o akreditivima

  - **ElapsedTotal** - Ukupno vreme koje je bilo potrebno za pokretanje

  - **IsLoggingEnabled** - Da li je omogućeno evidentiranje

  - **ShowChooseProfileDlg** - Da li je prikazan dijalog „Izbor profila“

  - **ShowFirstRunDlg** - da li je Outlook pokrenut prvi put

  - **ShowIMAPSrchfldWarningDlg** - Upozorenja u slučaju da imamo IMAP nalog sa ANSI PST-om

  - **ShowNeedSupportDlg** - Greška u pokretanju koja je aktivirala dijalog korisničke podrške

  - **ShowSafeModeDlg** - da li je sesija otvorena u bezbednom režimu

  - **ShowScanPstDlg** - Provera popravki u prodavnici prikazuje poruku o grešci


#### <a name="officeoutlookmacbootperf"></a>Office.Outlook.Mac.BootPerf

Prikuplja vreme koje je potrebno za pokretanje programa Outlook. Vreme pokretanja programa se aktivno prati da bi se otkrile i dijagnostikovale regresije. Koristi se i za dijagnostikovanje eskalacije nezadovoljstva korisnika kao i za poboljšanje performansi pokretanja programa tokom vremena.

Prikupljaju se sledeća polja:

- **MacOLKBootPerfDuration** – ukupno vreme potrošeno na pokretanje

- **MacOLKBootPerfID** – identifikator za potrošeno vreme za pokretanje


#### <a name="officeoutlookmacperformanceunresponsive"></a>Office.Outlook.Mac.PerformanceUnresponsive

Koristi se za prepoznavanje problema koji utiču na korisnike u programu Outlook koji se mogu pokazati kao smanjena performansa. 

Prikupljaju se sledeća polja:

- **Duration** - vreme isteklo od degradiranog učinka

- **EventType** - tip događaja sa degradiranim performansama


#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Sakuplja se pri pokretanju Office aplikacije. Obuhvata podatke o tome da li je do pokretanja došlo otvaranjem datoteke ili pokretanjem pomoću menija „Start“, da li je to bilo prvo pokretanje aplikacije, koliko memorije aplikacija koristi, kao i da li je korisniku prikazan bilo koji blokirajući korinički interfejs. Koristi se za merenje brzine pokretanja Office aplikacija i koliko memorije koriste pri pokretanju da bi se osigurao prihvatljiv utisak korisnika pri radu.

Prikupljaju se sledeća polja:

  - **ActivationKind** – Da li je aplikacija pokrenuta iz menija „Start“, otvaranjem datoteke ili putem OLE automatizacije.
  
  - **BootToStart** – Da li je korisnik odlučio da prikaže početni ekran kada se pokrene ova aplikacija.

  - **DocLocation** –  Pri otvaranju dokumenta naznačeno je koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.).

  - **FirstBoot** – Da li je ovo bilo prvo pokretanje aplikacije.

  - **InitializationDuration** - Koliko je mikrosekundi bilo potrebo za prvo pokretanje Office procesa.

  - **InterruptionMessageId** - Da li je pokretanje prekinuto dijalogom u kome se traži korisnički unos i ID dijaloga.

  - **TotalWorkingSetMB** - Količina memorije u megabajtima u radnom skupu procesa.

  - **VirtualSetMB** - Količina memorije u megabajtima u virtualnom skupu procesa. (Samo za MacOS/iOS)

  - **WorkingSetPeakMB** - najveća količina memorije u megabajtima koja je do sada bila u radnom skupu procesa.

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Aktivnost koja prati da li se Office Insider ploča može prikazati korisniku na kartici „Nalog“ u Office Backstage korisničkom interfejsu.

Prikupljaju se sledeća polja:

  - **Data_CanShow** - Ukazuje na to da li se Office Insider ploča može prikazati korisniku na kartici „Nalog“ u Office Backstage korisničkom interfejsu.
  
  - **Data_Event** – Nekorišćeno

  - **Data_EventInfo** – Nekorišćeno

  - **Data_Reason** – Nekorišćeno
 

#### <a name="officeuxofficeinsiderregistercurrentinsider"></a>Office.UX.OfficeInsider.RegisterCurrentInsider

Kritični signal za praćenje uspeha ili neuspeha registracije korisnika koji koriste Office Insider verzije a koji ranije nisu bili registrovani kao učesnici programa Office Insider. Glavni scenario za ovo su aktuelni učesnici programa Office Insider koji su se pridružili programu Office Insider pre dodavanja registracije programa Office Insider.

Prikupljaju se sledeća polja:

- **Data_RegisterInsider** – Status Office Insider registracije

- **Data_RegisterInsider** – Kod rezultata za registraciju Office Insider-a

- **Data_RegistrationStateCurrent** – Trenutno stanje registracije

- **Data_RegistrationStateDesired** – Traženo stanje registracije


#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

Kritična interakcija korisnika znaka za praćenje pomoću pridruživanja Office Insider dijalogu. Koristi se za prepoznavanje bilo kakvih problema u izvršavanju promena koje je inicirao korisnik, kao što su pridruživanje ili napuštanje Office Insider programa i promena nivoa programa Office Insider.

Prikupljaju se sledeća polja:

- **Data_AcceptedContactMeNew** – Označava da li je korisnik prihvatio da bude kontaktiran od strane Microsoft prilikom pridruživanja programu Office Insider

- **Data_InsiderLevel** -Insider Level za otvaranje dijaloga "pridruži se sistemu Office Insider"

- **Data_InsiderLevel** -Insider level za zatvaranje dijaloga "pridruži se sistemu Office Insider"

- **Data_IsInternalUser** – Ukazuje na to da li je aplikacija pokrenuta pod akreditivima Microsoft korporativnog naloga.

- **Data_IsInternalUserInit** - Označava da li je kod mogao da utvrdi da li je aplikacija pokrenuta pod akreditivima Microsoft korporativnog naloga.

- **Data_OpenNewsletterWebpage** – Ukazuje na to da li je veza pretplate na Office Insider bilten izazvana pod uslovom da se korisnik pridružio programu Office Insider, funkcija pretplate na newsletter je omogućena i da korisnik nije otkazao Otvaranje stranice pretplate na Office Insider newsletter.
    
- **Data_RegisterInsider** - Status Office Insider registracije

- **Data_RegisterInsider** – Kod rezultata za registraciju Office Insider-a

- **Data_RegistrationStateCurrent** – Trenutno stanje registracije

- **Data_RegistrationStateDesired** – Traženo stanje registracije




#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Ovaj događaj beleži vreme prikazivanja datoteke. Pomaže nam da održimo performanse prikazivanja datoteke pod kontrolom.

Prikupljaju se sledeća polja:

  - **Data\_AvgTime: integer** - Prosečno vreme koje je potrebno za prikazivanje Visio crteža u sesiji

  - **Data\_CompositeSurfEnabled: bool** - tačno ako je omogućen režim složenog prikazivanja

  - **Data\_Count: integer** - koliko puta Visio prikazuje crtež u sesiji

  - **Data\_FirstRenderTime: long** - trajanje prikazivanja datoteke pri prvom pokretanju u milisekundama

  - **Data\_MaxTime: integer** - Maksimalno vreme koje je potrebno za prikazivanje Visio crteža u sesiji

#### <a name="officevisiovisiofileopenreliability"></a>Office.Visio.VisioFileOpenReliability

Ovaj događaj prikuplja podatke o performansama otvaranja datoteke za Visio Dev16. Koristi se praćenje performansi otvaranja datoteke i za povezivanje istih sa svojstvima datoteke kao što je veličina kod programa Visio Dev16. Svojstva datoteke nam omogućavaju da brže otklonimo greške i glavni razlog problema.

Prikupljaju se sledeća polja:

  - **Data\_CorrelationId: string -** Identifikator korelacije dokumenta

  - **Data\_DocIsEnterpriseProtected: bool -** tačno ako je dokument zaštićen sa Windows zaštitom informacija

  - **Data\_DocumentId: string -** GUID putanje datoteke

  - **Data\_DurationToCompleteInMilliseconds: double -** Trajanje izvršavanja čuvanja u milisekundama

  - **Data\_DurationToCompleteInMillisecondsSquared: double -** kvadratna vrednost za trajanje izvršavanja čuvanja u milisekundama

  - **Data\_ErrorCode: integer -** Unutrašnji kôd greške koji se odnosi na grešku otvaranja datoteke

  - **Data\_Extension\_Docs: string -** Oznaka tipa datoteke dijagrama koji je otvoren

  - **Data\_FileIOBytesRead:int -** Ukupno bajtova koji su pročitani prilikom čuvanja

  - **Data\_FileIOBytesReadSquared: int -** kvadratna vrednost podataka\_FileIOBytesRead

  - **Data\_FileIOBytesWritten: int -** ukupno bajtova koji su napisani prilikom čuvanja

  - **Data\_FileIOBytesWrittenSquared: int -** kvadratna vrednost podataka\_FileIOBytesWritten

  - **Data\_FileName: binary -** Binarni heš imena datoteke

  - **Data\_FileOpenDownloadDurationInMs: long -** trajanje preuzimanja datoteke u milisekundama

  - **Data\_FileOpenDownloadDurationInMs: long -** trajanje otvaranja datoteke u milisekundama

  - **Data\_FileOpenTimeStamp: time: -** Vremenska oznaka za početak otvaranja dokumenta

  - **Data\_FilePathHash: binary -** GUID za putanju datoteke

  - **Data\_FileSize:long -** Veličina dokumenta u bajtovima

  - **Data\_FileType: string -** Oznaka tipa datoteke dijagrama koji je otvoren

  - **Data\_IsInternalFile: bool -** tačno ako je datoteka unutrašnja. npr. šablon

  - **Data\_IsIRM: bool -** tačno ako je datoteka zaštićena pravima o informacijama

  - **Data\_IsReadOnly: bool -** tačno ako je datoteka samo za čitanje

  - **Data\_IsSuccess: bool -** tačno ako je otvaranje datoteke uspešno

  - **Data\_Location: string -** lokacija datoteke kao što je lokalna, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer

  - **Data\_NetworkIOBytesRead: int -** ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesReadSquared: int -** kvadratna vrednost podataka\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten: int -** Ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesWrittenSquared: int -** kvadratna vrednost podataka NetworkIOBytesWritten

  - **Data\_OpenLocation: integer -** Lokacija datoteke sa koje je otvorena 0, lokalno, 1, mreža, 2, usluga SharePoint, 3 - internet

  - **Data\_Size\_Docs: integer -** Veličina dokumenta u bajtovima

  - **Data\_Tag: string -** jedinstveni identifikator za događaje funkcije „Sačuvaj kao“

  - **Data\_WasSuccessful: bool -** tačno ako je otvaranje bilo uspešno

### <a name="application-activity-error-subtype"></a>*Podtip greške u aktivnosti aplikacije*

Greške u funkcionalnosti funkcije ili korisničkog iskustva.

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Pomaže korporaciji Microsoft da razdvoji duge prekide u upravljačkom programu grafičke kartice od kratkih prekida, što zauzvrat pomaže da se odredi koji upravljački program grafičke kartice može imati probleme. Upravljački program grafičke kartice korisnika je izazvao prekid u sistemu Office, ali uticaj tog prekida još uvek nije poznat.

Prikupljaju se sledeća polja:

  - **Data\_InDeviceCall** - Pozvani metod na grafičkoj kartici koji je proizveo prekid

  - **Data\_Timeout** - Koliko dugo je trajao prekid

#### <a name="office_apple_licensing_mac_dractivationfailures"></a>Office_Apple_Licensing_Mac_DRActivationFailures

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za snimanje neuspeha aktivacije preduzeća Digital River (događaj evidentira ključ i proizvod koji su korišteni za aktiviranje, kao i primljeni kod greške).  Ovaj događaj se koristi za otkrivanje i pomoć pri rešavanju problema sa neuspelim aktivacijama (problemi preduzeća Digital River).

Prikupljaju se sledeća polja:

- **Data_DigitalRiverID** - ID Digital River proizvoda koji se mapira na ovaj Office proizvod - SKY

- **Data_Error** - niska koja predstavlja kôd greške aktivacije.

- **Data_ProductKey** - šifra proizvoda koja je pokušana da se aktivira

- **Data_ProductKeyHash** - aktivirana je kodirana šifra proizvoda

#### <a name="office_apple_licensing_mac_getmachinestatuserrors"></a>Office_Apple_Licensing_Mac_GetMachineStatusErrors

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj prikuplja kod greške vraćen tokom periodične provere valjanosti licence pretplate. Kôd greške može da označava nedostupnost servera, ali i isticanje licence, ograničenje broja računara, nevažeći ID hardvera, itd. Ovaj događaj se koristi za nadgledanje stanja usluge Office licenciranja, ali i za istraživanje problema vezanih za upravljanje mašinom pretplate.

Prikupljaju se sledeća polja:

- **Data_Error** - prikupljamo nisku koja predstavlja kod greške

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Prati različita obaveštenja o greškama dobijene iz sandboxa. Koristi se za otkrivanje scenarija grešaka u sandboxu i tamo tako što ćete ga popraviti, da biste poboljšali produktivnost korisnika
 
Prikupljaju se sledeća polja:

- **AppId** - Id aplikacije

- **AppUrl** - pročišćena URL adresa aplikacije 

- **Result** - kôd greške rezultata

#### <a name="office_firstrun_apple_maconiolkfirstrunstarted"></a>Office_FirstRun_Apple_MacONIOLKFirstRunStarted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunCollectionTime** - vremenska oznaka koja registruje vreme kad je tok pokrenut.

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ove informacije koje izveštavaju o izuzecima su bitne da bi se procenila celokupna ispravnost grafičkog niza, kao i za identifikovanje delova koda u kojima često dolazi do grešaka kako bi se odredio prioritet istrage. Ove informacije koje izveštavaju o izuzecima su bitne da bi se procenila celokupna ispravnost grafičkog niza, kao i za identifikovanje delova koda u kojima često dolazi do grešaka. Ovo pomaže inženjeru da odredi koje greške u prikazivanju utiču na najveći broj korisnika, što nam omogućava da kao prioritet istrage postavimo otklanjanje problema posle kojih će najveći broj korisnika imati koristi.

Prikupljaju se sledeća polja:

  - **Data\_HResult** - Kôd greške koji je vraćen iz otkazivanja

  - **Data\_TagCount** - Broj svih grešaka do kojih je došlo

  - **Data\_TagID** - Identifikator greške do koje je došlo

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfolder_error"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error

Prikuplja informacije o greškama koje se javljaju prilikom navigacije kroz deljeni kalendar. Ti podaci se koriste za praćenje ispravnosti API-ja deljenog kalendara, kao i za interakciju programa Outlook sa deljenim kalendarima.

Prikupljaju se sledeća polja:

  - **FailedCaseHResult** - Kôd greške koji je vraćen iz otkazivanja

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a>Office.Outlook.Desktop.EDP.EDPOpenStoreFailure

Uspeh ili neuspeh otvaranja skladišta pošte koje je zaštićeno „Zaštitom podataka preduzeća“, što zavisi od mogućnosti Windows API poziva da dobavi ključ za dešifrovanje skladišta. Ovo koristimo da bismo dijagnostikovali jedan od glavnih problema „Zaštite podataka preduzeća“ koji spečava prokretanje programa Outlook. Primarni uzrok greške je interakcija programa Outlook sa Windows API-jem koji se koristi za dešifrovanje ključa skladišta.

Prikupljaju se sledeća polja:

  - **HVA aktivnost** **-** sa prilagođenim poljima sa podacima

  - **IsFlightOn** - ukazuje na to da li je omogućen „Let EDP dešifrovanja“ 

#### <a name="officeoutlookdesktopndbcorruptionresult"></a>Office.Outlook.Desktop.NdbCorruptionResult

Office.Outlook.Desktop.NdbCorruptionResult (rezultat oštećenja) i Office.Outlook.Desktop.NDBCorruptStore.Warning (upozorenje o oštećenju skladišta) se prikupljaju kada otkrijemo oštećenje u korisničkoj PST/OST datoteci. Kada otkrijemo oštećenje, korporacija Microsoft prikuplja informacije o formatu baze podataka, mestu na kom je oštećenje primećeno i malu količinu konteksta o oštećenju. Oštećenje OST/PST datoteke sprečava korisnike da pristupe svojoj e-pošti. Aktivno pratimo ove podatke da bismo primetili neuobičajene aktivnosti. Cilj nam je da istražimo i dijagnostikujemo probleme da bismo ograničili gubitak korisničkih podataka.

Prikupljaju se sledeća polja:

  - **0 -** Ime procesa koji je prijavio oštećenje

  - **1 -** Bool koji ukazuje na to da li korisnik bira novu datoteku ili ne

  - **2 -** Broj drugih procesa u kojima je otvorena baza podataka

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a>Office.Outlook.Desktop.NDBCorruptStore.Warning

Office.Outlook.Desktop.NdbCorruptionResult (rezultat oštećenja) i Office.Outlook.Desktop.NDBCorruptStore.Warning (upozorenje o oštećenju skladišta) se prikupljaju kada otkrijemo oštećenje u korisničkoj PST/OST datoteci. Kada otkrijemo oštećenje, korporacija Microsoft prikuplja informacije o formatu baze podataka, mestu na kom je oštećenje primećeno i malu količinu konteksta o oštećenju. Oštećenje OST/PST datoteke sprečava korisnike da pristupe svojoj e-pošti. Aktivno pratimo ove podatke da bismo primetili neuobičajene aktivnosti. Cilj nam je da istražimo i dijagnostikujemo probleme da bismo ograničili gubitak korisničkih podataka.

Prikupljaju se sledeća polja:

  - **VremePrikupljanja** - vreme prikupljanja

  - **Kontekst** - Kontekst oštećenog skladišta, gde je primećeno oštećenje

  - **KreiranoPomoćuVerzije** - (opciono) polje sa podacima o verziji skladišta

  - **Detalji** - detalji o padu

  - **NdbTip** - Tip skladišta, može biti 0 = NdbNedefinisano, 1 = NdbMalo, 2 = NdbVeliko, 3 = NdbTardis

  - **ImeProcesa** - Ime procesa koji je izazvao oštećenje skladišta

  - **PstVerzija** - Verzija MSPST32.DLL-a

  - **Verzija** - Verzija formata datoteke skladišta

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16

Prikuplja informacije o uspehu i neuspehu radnji „Prosleđivanja“, „Prosleđivanja priloga“ i „Prosleđivanja iCalendar-a“ koje su odgovor na pojedinačne, periodične i vanredne sastanke u Outlook prikazu e-pošte, kalendara i nadzora. Stopa grešaka u „Prosleđivanju“, „Prosleđivanju priloga“ i „Prosleđivanju iCalendar-a“ se aktivno prati da bi se otkrile nepravilnosti. Neuobičajene statistike ukazuju na grešku u sposobnosti programa Outlook da sprovede osnovne operacije kalendara. Ovi podaci se koriste i za dijagnostikovanje drugih problema kalendara koji se mogu otkriti.

Prikupljaju se sledeća polja:

  - **CountExceptionForward **- Broj prosleđenih vanrednih sastanaka 

  - **CountExceptionForwardAsiCal**- Broj prosleđenih vanrednih sastanaka u vidu iCal-a

  - **CountExceptionForwardInSplit** - broj prosleđenih vanrednih sastanaka pomoću stavke menija „Razdeli“ koja se nalazi na traci

  - **CountExceptionForwardWithAttach**- Broj prosleđenih vanrednih sastanaka u vidu priloga

  - **CountRecurringForward**- Broj prosleđenih periodičnih sastanaka

  - **CountRecurringForwardAsiCal**- Broj prosleđenih periodičnih sastanaka u vidu iCal-a

  - **CountRecurringForwardInSplit** - Broj prosleđenih periodičnih sastanaka pomoću stavke menija „Razdeli“ koja se nalazi na traci

  - **CountRecurringForwardWithAttach**- Broj prosleđenih periodičnih sastanaka u vidu priloga

  - **CountSingleForward** - Broj prosleđenih pojedinačnih sastanaka

  - **CountSingleForwardAsiCal**- Broj prosleđenih pojedinačnih sastanaka u vidu iCal-a

  - **CountSingleForwardInSplit**- Broj prosleđenih pojedinačnih sastanaka pomoću stavke menija „Razdeli“ koja se nalazi na traci

  - **CountSingleForwardWithAttach**- Broj prosleđenih pojedinačnih sastanaka u vidu priloga

  - **HRezultat** - KôdGreške

  - **OlkViewName**- Ukazuje na prikaz e-pošte, kalendara ili nadzora 

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Prikuplja informacije o uspehu i neuspehu radnji „Odgovaranja“, „Odgovaranja svima“, „Odgovaranja putem trenutne poruke“ i „Odgovaranja svima putem trenutne poruke“ koje su odgovor na pojedinačne, periodične i vanredne sastanke u Outlook prikazu e-pošte, kalendara i nadzora. Stopa grešaka u „Odgovaranju“, „Odgovaranju svima“, „Odgovaranju putem trenutne poruke“ i „Odgovaranju svima putem trenutne poruke“ se aktivno prati da bi se otkrile nepravilnosti. Neuobičajene statistike ukazuju na grešku u sposobnosti programa Outlook da sprovede osnovne operacije kalendara. Ovi podaci se koriste i za dijagnostikovanje drugih problema kalendara koji se mogu otkriti.

Prikupljaju se sledeća polja:

  - **CountExceptionReply** - Broj odgovora na vanredne sastanke pomoću funkcije „Odgovori“

  - **CountExceptionReplyAll** - Broj odgovora na vanredne sastanke pomoću funkcije „Odgovori svima“

  - **CountExceptionReplyAllWithIM**- Broj odgovora na vanredne sastanke pomoću funkcije „Odgovori svima putem trenutne poruke“

  - **CountExceptionReplyWithIM** - Broj odgovora na vanredne sastanke pomoću funkcije „Odgovori putem trenutne poruke“

  - **CountRecurringReply** - Broj odgovora na periodične sastanke pomoću funkcije „Odgovori“

  - **CountRecurringReplyAll** - Broj odgovora na periodične sastanke pomoću funkcije „Odgovori svima“

  - **CountRecurringReplyAllWithIM** - Broj odgovora na periodične sastanke pomoću funkcije „Odgovori svima putem trenutne poruke“

  - **CountRecurringReplyWithIM** - Broj odgovora na periodične sastanke pomoću funkcije „Odgovori putem trenutne poruke“

  - **CountSingleReply** - Broj odgovora na pojedinačne sastanke pomoću funkcije „Odgovori“

  - **CountSingleReplyAll** - Broj odgovora na pojedinačne sastanke pomoću funkcije „Odgovori svima“

  - **CountSingleReplyAllWithIM** - Broj odgovora na pojedinačne sastanke pomoću funkcije „Odgovori svima putem trenutne poruke“

  - **CountSingleReplyWithIM** - Broj odgovora na pojedinačne sastanke pomoću funkcije „Odgovori putem trenutne poruke“

  - **HRezultat** - KôdGreške

  - **OlkViewName**- Ukazuje na prikaz e-pošte, kalendara ili nadzora 

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Ovo pravilo prikuplja informacije o greškama u deljenju kalendara kada se dodaje novi korisnik (tipa EX ili SMTP) iz adresara. Ti podaci se koriste za dijagnostikovanje i rešavanje problema koji su otkriveni u dijalogu „Deljenje kalendara“.

Prikupljaju se sledeća polja:

  - **CountAccountWizardEnd** - koliko puta je završen dijalog zastarelog čarobnjaka

  - **CountCreatePIMAccount** - koliko puta je korisnik napravio PIM profil

#### <a name="officeoutlookmacmacolkasserts"></a>Office.Outlook.Mac.MacOLKAsserts

Koristi se za identifikovanje problema unutar programa Outlook, koji se ispoljavaju u vidu padova ili smanjene funkcionalnosti. 

Prikupljaju se sledeća polja:

- **Kategorija** - tip tvrdnje

- **CollectionTime** - vreme kada je prikupljena tvrdnja


#### <a name="officeoutlookmacmacolkerrors"></a>Office.Outlook.Mac.MacOLKErrors

Koristi se za identifikovanje problema unutar programa Outlook, koji se ispoljavaju u vidu padova ili smanjene funkcionalnosti. 

Prikupljaju se sledeća polja:

- **Category** - tip greške

- **CollectionTime** - vreme kada je prikupljena greška

- **ThreadId** - identifikator za nit


#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Greške koje ovaj događaj identifikuje nam pomažu da razumemo kada je korisničko iskustvo ugroženo. Mnoge od ovih otprema potvrde (ShipAsserts) dovode do padova i te informacije nam omogućavaju da ispravimo mnoge greške. Prikupljaju se informacije o otpremama potvrde (ShipAsserts), što nam pomaže u identifikovanju grešaka.

Prikupljaju se sledeća polja:

 - **Broj** - Broj svih prijavljenih potvrda (assert-a)

  - **VremeZavršetka** - Vreme kada se dogodila poslednja potvrda koja je prijavljena

  - **GrupaGreške** - Identifikator grupe za svaku potvrdu

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do potvrde

  - **PraćenjeUnazad** - Jedinstveni identifikator određene potvrde

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se ispoljavaju padovima ili umanjenom funkcionalnošću. Beleži greške do kojih dolazi tokom izvršavanja procesa.

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se ispoljavaju padovima ili umanjenom funkcionalnošću. Beleži greške do kojih dolazi tokom izvršavanja procesa.

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se ispoljavaju padovima ili umanjenom funkcionalnošću. Beleži greške do kojih dolazi tokom izvršavanja procesa.

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se ispoljavaju padovima ili umanjenom funkcionalnošću. Beleži greške do kojih dolazi tokom izvršavanja procesa.

Prikupljaju se sledeća polja:

Broj - Broj svih grešaka

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **KôdGreške** - Identifikator greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **IdGreške** - Identifikator greške

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se ispoljavaju padovima ili umanjenom funkcionalnošću. Beleži greške do kojih dolazi tokom izvršavanja procesa.

Prikupljaju se sledeća polja:

  - **Broj** - Broj svih grešaka

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **KôdGreške** - Identifikator greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **IdGreške** - Identifikator greške

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

#### <a name="renewidentityfailure"></a>RenewIdentityFailure

Sakuplja se kada korisnik pokuša da otvori IRM zaštićeni dokument ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom neuspešnog obnavljanja korisničkih certifikata.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** - Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **Failure.Category** – Kategorija greške „UnhandledError”

- **Failure.Detail** - Detaljne informacije o grešci

- **Failure.Id** - Id greške

- **Failure.Signature** - Potpis greške, koji je isti kao ime događaja

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.HRESULT** – Rezultat obnavljanja korisničkog certifikata

- **RMS.ScenarioId** - ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management


## <a name="device-connectivity-and-configuration-data-events"></a>Podaci dobijeni iz povezivanja uređaja i konfiguracije

Podtipovi podataka koji spadaju u ovu kategoriji su:

- [Povezivanje uređaja i konfiguracija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Podtip povezivanja uređaja i konfiguracije*

Stanje mrežne veze i podešavanje uređaja, kao što je memorija.

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a>Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated

Korisnik je ažurirao upravljački program grafičke kartice koja je prethodno uzrokovala padove sistema Office zbog čega se ona više ne koristi za prikazivanje. Obaveštava korporaciju Microsoft da se korisnici, koji su se nalazili u stanju prikazivanja koje je ispod optimalnog, ponovo nalaze u preporučenom stanju.

Prikupljaju se sledeća polja:

  - **Data\_BlockedDriverVersion** - Verzija upravljačkog programa koja se nalazi na listi blokiranih.

  - **Data\_DeviceId** - identifikator grafičke kartice uređaja koji se nalazi na listi blokiranih.

  - **Data\_UpdatedDriverVersion** - Verzija ažuriranog upravljačkog programa

#### <a name="officeairspaceairspacelocalblocklistinfo"></a>Office.AirSpace.AirSpaceLocalBlocklistInfo

Detalji o upravljačkom programu grafičke kartice koji je nedavno izazvao višestruke padove Office aplikacija. Sistem Office neće koristiti datu grafičku karticu u sesijama dok se upravljački program ne ažurira (umesto toga će koristiti softver za prikazivanje). Obaveštava Microsoft o upravljačkim programima grafičke kartice koji uzrokuju probleme u sistemu Office, tako da ti trendovi mogu biti identifikovani, a uticaj takvih upravljačkih programa analiziran. Govori korporaciji Microsoft koliko korisnika se nalazi u stanju koje je ispod optimalnog.

Prikupljaju se sledeća polja:

  - **Data\_AllAppsBlocked** - Da li se sve Office aplikacije nalaze na listi blokiranih

  - **Data\_BlockedDeviceId** - identifikator grafičke kartice uređaja koji se nalazi na listi blokiranih

  - **Data\_BlockedDriverVersion** - Verzija upravljačkog programa koja se nalazi na listi blokiranih

  - **Data\_CrashHistory** - Niska koja predstavlja istoriju padova koji su izazvani upravljačkim programom grafičke kartice i služi za analizu 

  - **Data\_SecsBetweenCrashes** - Koliko često dolazi do padova upravljačkog programa kartice

#### <a name="officeairspaceairspacewincompisenabled"></a>Office.AirSpace.AirSpaceWinCompIsEnabled

Da li se koristi najnovija Office platforma za prikazivanje niskog nivoa koja se zasniva na Windows kompoziciji.

Ovo omogućava korporaciji Microsoft da, tokom razvijanja najnovije Office platforme za prikazivanje niskog nivoa i njenog objavljivanja za korisnike, vidi koliko korisnika ima na svakoj verziji da bi obezbedila platformu bez grešaka.

Prikupljaju se sledeća polja:

  - **Data\_WinCompEnabled** - Da li je u upotrebi pozadinska komponenta koja je zasnovana na Windows kompoziciji

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp

Otkriveno je da grafička kartica korisnika uzrokuje duge ili nepopravljive prekide. Sistem Office neće koristiti datu grafičku karticu u sesijama dok se upravljački program ne ažurira (umesto toga će koristiti softver za prikazivanje). Obaveštava Microsoft o upravljačkim programima grafičke kartice koji uzrokuju probleme u sistemu Office, tako da ti trendovi mogu biti identifikovani, a uticaj takvih upravljačkih programa analiziran. Pomaže i u informisanju koliko korisnika se nalazi u stanju koje je ispod optimalnog.

Prikupljaju se sledeća polja:

  - **Data\_AppName** - Koja aplikacija je naišla na prekide u upravljačkom programu grafičke kartice

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite

Sistem Office je prepoznao da je upravljački program grafičke kartice korisnika uzrokovao prekid koji bi trebalo da bude analiziran prilikom sledećeg pokretanja Office aplikacije. Koristi se da bi se odredilo da li korišćenje drugog upravljačkog programa grafičke kartice ili adaptera može ponuditi bolje korisničko iskustvo. Tokom javljanja obrazaca, Microsoft može izvršiti prilagođavanja da bi osigurao što bolje iskustvo. 

Prikupljaju se sledeća polja:

  - **Data\_HangDetected** - Da li je otkriven prekid

  - **Data\_InDeviceCall** - U kom pozivu prikazivanja pomoću grafičke kartice se nalazio Office kada je došlo do prekida

  - **Data\_Timeout** - Koliko dugo je trajao prekid ako je došlo do oporavka

  - **Data\_UnrecoverableCommand** - Da li se prekid u komandi prikazivanja pomoću grafičke kartice obično može ispraviti

#### <a name="officeairspacebackendwin32localblocklistactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistActivity

Detalji o upravljačkom programu grafičke kartice koji je nedavno izazvao višestruke padove Office aplikacija. Sistem Office neće koristiti datu grafičku karticu u sesijama dok se upravljački program ne ažurira (umesto toga će koristiti softver za prikazivanje). Obaveštava Microsoft o upravljačkim programima grafičke kartice koji uzrokuju probleme u sistemu Office, tako da ti trendovi mogu biti identifikovani, a uticaj takvih upravljačkih programa analiziran. Govori korporaciji Microsoft koliko korisnika se nalazi u stanju koje je ispod optimalnog.

Prikupljaju se sledeća polja:

  - **Data.AllAppsBlocked** - Da li se sve Office aplikacije nalaze na listi blokiranih

  - **Data.BlockedDeviceId** - identifikator grafičke kartice uređaja koji je blokiran

  - **Data.BlockedDriverVersion** - Verzija upravljačkog programa koja se nalazi na listi blokiranih

  - **Data.CrashHistory System.String** - Niska koja predstavlja istoriju padova koji su izazvani upravljačkim programom grafičke kartice i služi za analizu 

  - **Data.SecsBetweenCrashes** - Koliko često dolazi do padova upravljačkog programa kartice

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity

Korisnik je ažurirao upravljački program grafičke kartice koja je prethodno uzrokovala padove sistema Office zbog čega se ona više ne koristi za prikazivanje. Obaveštava korporaciju Microsoft da se korisnici, koji su se nalazili u stanju prikazivanja koje je ispod optimalnog, ponovo nalaze u preporučenom stanju.

Prikupljaju se sledeća polja:

  - **Data\_BlockedDeviceId** - identifikator grafičke kartice uređaja koji se nalazi na listi blokiranih

  - **Data\_BlockedDriverVersion** - Verzija upravljačkog programa koja se nalazi na listi blokiranih

  - **Data\_UpdatedDriverVersion** - Verzija ažuriranog upravljačkog programa

#### <a name="officegraphicsspritememcorrupt"></a>Office.Graphics.SpriteMemCorrupt

Izveštava o greškama koje su otkrivene u proračunu telemetrijskog niza memorije. Ključna je za procenu ispravnosti telemetrije upotrebe grafičke memorije. Ove informacije su potrebne da bi se potvrdila ispravnost naše SpriteMem telemetrije.

Prikupljaju se sledeća polja:

  - **Data\_CurrentSpriteMem** - Ukupna memorija koja se aktivno dodeljuje za čuvanje niza (slika), što dovodi do pojave sadržaja na ekranu.

  - **Data\_Function** - Ime funkcije koja pokušava da oslobodi niz memorije.

  - **Data\_SpriteMemToRemove** - Količina memorije koja treba da bude uklonjena iz dodeljenog niza

#### <a name="officepowerpointpptsharednointernetconnectivity"></a>Office.PowerPoint.PPT.Shared.NoInternetConnectivity

Prikuplja se svaki put kada program PowerPoint otkrije da nema internet veze. Microsoft koristi ove podatke da bi dobio dijagnostičke informacije o internet vezi korisnika u cilju razumevanja njenog uticaja na povezivanje sa uslugama sistema Office.

Prikupljaju se sledeća polja:

- **Data\_IsNexusDetected:bool** - prikazuje da li imamo vezu sa internetom prilikom pozivanja usluge Nexus (vrednost tačno) ili prilikom pozivanja generičke veb usluge API (vrednost netačno)
