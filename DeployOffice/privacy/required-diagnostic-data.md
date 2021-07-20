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
ms.openlocfilehash: 575d9e737e529ba999ece88d69bf8dd91d171d64
ms.sourcegitcommit: 85bef3bf44e4d6db25fd5817a0e49a159642dab2
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/16/2021
ms.locfileid: "53456210"
---
# <a name="required-diagnostic-data-for-office"></a>Obavezni dijagnostički podaci za Office

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Ti podaci ne sadrže korisničko ime ili adresu e-pošte, sadržaj korisničkih datoteka ili informacije o aplikacijama nevezanim za Office.

Ovi dijagnostički podaci se prikupljaju i šalju korporaciji Microsoft u vezi sa Office klijentskim softverom pokrenutim na uređaju korisnika. Neki dijagnostički podaci su obavezni, a neki su opcionalni. Možete da izaberete da li ćete nam slati obavezne ili opcionalne dijagnostičke podatke pomoću kontrole privatnosti, kao što su postavke smernica organizacije. Možete da vidite dijagnostičke podatke koji nam se šalju koristeći prikaz dijagnostičkih podataka.

***Obavezni dijagnostički podaci*** su minimalni podaci neophodni da bi Office bio bezbedan, ažuriran i da radi kao što se očekuje na uređaju na kome je instaliran.

Obavezni dijagnostički podaci pomažu u identifikovanju problema sa sistemom Office koji su možda povezani sa konfiguracijom uređaja ili softvera. Na primer, oni mogu da pomognu da odredite da li neka funkcija sistema Office pada češće na određenoj verziji operativnog sistema, zbog novih funkcija, ili kada su određene funkcije sistema Office onemogućene. Obavezni dijagnostički podaci pomažu nam da otkrijemo, ustanovimo i rešimo probleme brže, tako da se smanji uticaj na korisnike ili organizacije.

Za više informacija o dijagnostičkim podacima pogledajte sledeće članke:

- [Opcionalni dijagnostički podaci za Office](optional-diagnostic-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Ako ste administrator organizacije, možda će vas zanimati i sledeći članci:

- [Pregled kontrola privatnosti za Microsoft 365 Apps za velika preduzeća](overview-privacy-controls.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)

> [!NOTE]
> Informacije o neophodnim dijagnostičkim podacima za Microsoft Teams potražite u sledećim člancima:
> - [Neophodni dijagnostički podaci za računare za Microsoft Teams](/microsoftteams/policy-control-diagnostic-data-desktop)
> - [Neophodni mobilni dijagnostički podaci za Microsoft Teams](/microsoftteams/policy-control-diagnostic-data-mobile)

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
| **Upotreba proizvoda i usluga**    | [Uspešnost funkcija aplikacije](#application-feature-success-subtype)   | Uspešna funkcionalnost aplikacije. Ograničeno na otvaranje i zatvaranje aplikacije i dokumenata, uređivanje i deljenje datoteka (saradnju). |
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

Identifikator koji je povezan sa programom Office-a na uređaju. Konstantan za sve sesije svih aplikacija određene verzije instalacije za pakete koji sadrže više aplikacija ili konstantan za sve sesije određene verzije aplikacije.

Ova kategorija sadrži sledeća polja:

  - **Id** -Jedinstveni identifikator dodeljen klijentu u trenutku instaliranja sistema Office. Omogućava nam da utvrdimo da li problemi utiču na određeni skup instalacija i na koliko korisnika oni utiču.

#### <a name="consent"></a>Pristanak

Informacije o pristanku korisnika na prikupljanje dijagnostičkih podataka i povezanih iskustva.

Ova kategorija sadrži sledeća polja:

  - **ControllerConnectedServicesSourceLocation** – ukazuje na to kako je izvršen izbor korisnika za opcionalna povezana iskustva

  - **ControllerConnectedServicesState** – ukazuje na to da li korisnik ima pristup opcionalnim povezanim iskustvima

  - **Vreme pristanka za prikupljanje podataka o kontroleru statusa povezanih usluga** – Ukazuje na to kada je korisnik odabrao status opcionalnih povezanih iskustava. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Vreme pristanka za prikupljanje dijagnostičkih podataka** – ukazuje na to kada je korisnik obezbedio pristanak za prikupljanje dijagnostičkih podataka. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Nivo pristanka za prikupljanje dijagnostičkih podataka** – označava na koji je nivo prikupljanja dijagnostičkih podataka korisnika dao pristanak.

  - **DiagnosticConsentLevelSourceLocation** – označava način na koji je korisnik dao pristanak za dijagnostičke podatke

  - **DownloadContentSourceLocation** – označava kako je korisnik napravio odabir omogućavanja ili onemogućavanja povezanih iskustava koja preuzimaju onlajn sadržaj

  - **Status preuzetog sadržaja** – ukazuje na to da li je korisnik odabrao da omogući ili onemogući povezana iskustva koja preuzimaju sadržaj na mreži

  - **Vreme pristanka na prikupljanje podataka o statusu preuzetog sadržaja** – ukazuje na to kada je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja preuzimaju sadržaj na mreži Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Status povezanih usluga** – ukazuje na to da li je korisnik odabrao da koristi ili ne koristi sva povezana iskustva

  - **Vreme pristanka za prikupljanje podataka o statusu povezanih usluga** – Ukazuje na to kada je korisnik odabrao da li da koristi sva povezana iskustva. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

  - **Izvorna lokacija statusa povezanih usluga** – ukazuje na to kako je korisnik napravio izbor da li želi da koristi sva povezane iskustva

  - **UserCategoryValue ―** određuje vrstu korisnika koji daje pristanak. Jedan od MSAUser, AADUser ili LocalDeviceUser

  - **UserContentDependentSourceLocation** – ukazuje na to kako je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja analiziraju sadržaj

  - **Status analize sadržaja povezanih iskustava korisnika** – ukazuje na to da li je korisnik odabrao da omogući ili onemogući povezana iskustva koja analiziraju sadržaj

  - **Vreme pristanka za prikupljanje podataka o statusu analize sadržaja povezanih iskustava korisnika** – Ukazuje na kada je korisnik napravio izbor da omogući ili onemogući povezana iskustva koja analiziraju sadržaj. Datum će se pojaviti kao tip datuma koji ljudi mogu da pročitaju ili kao računarski kodirani datum koji izgleda kao veliki broj.

#### <a name="device"></a>Uređaj 

Informacije o operativnom sistemu i izdanju.

Ova kategorija sadrži sledeća polja:

  - **Model** – niska koja sadrži fizički model za uređaj koji radi pod aplikacijom. Samo iOS. Na primer, iPhone13,3 ili iPad11,6.
  
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

  - **HostAppName** –prepoznaje ime aplikacije hosta koje pokreće potaplikaciju. Aplikacije kao što su Office Mobile (Android) mogu da pokrenu podaplikacije za Word, Excel i PowerPoint. Za takve podaplikacije, aplikacija host je Office – Emobajl

  - **Hostssionid** –jedinstveno identifikuje sesiju hosta aplikacije za podaplikaciju

  - **Id** – jedinstveno identifikuje određenu sesiju podataka. Omogućava nam da utvrdimo uticaj problema procenom broja sesija na koje problem utiče i da li postoje funkcije koje su zajedničke za ove sesije.

  - **Id utiska** - određuje skup letova koji se izvršavaju u određenoj sesiji. Omogućava nam da utvrdimo koji pojedinačni letovi se izvršavaju u sesiji, tako da možemo utvrditi da li je let izvor problema koji utiče na korisnike.

  - **Merenje omogućeno** – zastavica koja ukazuje na to da li se podaci trenutne sesije uzorkuju ili ne. Omogućava nam da odredimo kako statistički proceniti podatke koji su prikupljeni u određenoj sesiji.

  - **SamplingClientIdValue** – ID klijenta kojim se utvrđuje da li je deo uzorkovanja. Omogućava nam da utvrdimo zašto je pojedinačna sesija uključena ili isključena iz uzoraka.
  
 - **SubAppName** – za aplikaciju Office za mobilne uređaje ovo polje predstavlja temeljnu aplikaciju koja se koristi za otvaranje dokumenta. Na primer, ako otvorite dokument programa Word u aplikaciji Office, to polje će prijaviti vrednost „Word“.

 - **VirtualizationType** – vrsta vizuelizacije ako se Office radi u jednoj. Moguće vrednosti su: 
    - 0 = Nijedno
    - 1 = Windows virtuelna radna površina.
    - 2 = Application Guard Windows zaštitnika
    - 3 = Windows Core OS

#### <a name="user"></a>Korisnik

Pruža informacije o zakupcu za jedinice za čuvanje zaliha komercijalnog softvera.

Ova kategorija sadrži sledeća polja:

  - **Heš primarnog identiteta** – identifikator pod pseudonimom koji predstavlja trenutnog korisnika.

  - **Mesto primarnog identiteta** – tip identiteta sadržanog u hešu primarnog identiteta. Jedan od MASCID, OrgIdCID ili UserObjectId.

  - **Grupa zakupca** - tip zakupca kome pripada pretplata. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem rasprostranjen ili izolovan u skupu korisnika.

  - **ID zakupca** – zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Informacije koje posebno podržavaju prikupljanje dijagnostičkih podataka*

Informacije koje posebno podržavaju prikupljanje dijagnostičkih podataka se prikupljaju u sledećim kategorijama.

#### <a name="activity"></a>Aktivnost

Informacije koje služe za razumevanje uspešnosti samog procesa prikupljanja.

Ova kategorija sadrži sledeća polja:

  - **Režim grupisanja** - govori sistemu kako da grupiše rezultate aktivnosti. Omogućava nam da smanjimo količinu informacija koje se otpremaju sa računara korisnika tako što grupišemo rezultate aktivnosti u jedan događaj koji se šalje povremeno.

  - **Broj** - koliko puta se aktivnost izvršila ako se broj izračunava iz grupisanog događaja. Omogućava nam da odredimo koliko često se aktivnost uspešno ili neuspešno izvršila u odnosu na režim grupisanja aktivnosti.

  - **CV** - vrednost koja određuje odnos između aktivnosti i podaktivnosti. Omogućava nam da obnovimo odnos između ugnežđenih aktivnosti.

  - **Trajanje** - koliko vremena je bilo potrebno za izvršavanje aktivnosti. Omogućava nam da utvrdimo probleme sa performansama koje negativno utiču na iskustvo korisnika.

  - **Result.Code** – Aplikacijom određen kôd koji služi za identifikaciju određenog rezultata. Omogućava nam da odredimo preciznije detalje određenog neuspeha, kao što je kôd greške koji se može koristiti za klasifikaciju i rešavanje problema.

  - **Rezultat.Oznaka** - oznaka celog broja koji određuje lokaciju u kodu gde je rezultat generisan. Omogućava nam da jasno odredimo lokaciju u kôdu na kojoj je rezultat generisan što omogućava klasifikaciju grešaka.

  - **Result.Type** – tip kôda rezultata. Određuje koji tip koda rezultata je poslat tako da vrednost može da se ispravno tumači.

  - **Uspeh** – zastavica koja označava da li je aktivnost uspešno izvršena ili ne. Omogućava nam da utvrdimo da li se radnje koje korisnik preduzima u proizvodu uspešno izvršavaju ili ne. To nam omogućava da prepoznamo probleme koji utiču na korisnika.

#### <a name="application"></a>Aplikacija 

Informacije o instalaciji aplikacije iz koje se događaji prikupljaju.

Ova kategorija sadrži sledeća polja:

  - **Arhitektura** - arhitektura aplikacije. Omogućava nam da klasifikujemo greške koje mogu biti specifične za arhitekturu aplikacije.

  - **Verzija „Klikni i pokreni“ paketa** - broj verzije „Klikni i pokreni“ paketa putem kojeg je aplikacija instalirana. Omogućava nam da identifikujemo koja je verzija programa za instaliranje korišćena za instalaciju sistema Office, tako da možemo identifikovati probleme povezane sa podešavanjem.

  - **Distribucioni kanal** - kanal putem kojeg je aplikacija implementirana. Omogućava nam da podelimo dolazne podatke kako bismo utvrdili da li problemi utiču na korisnike.

  - **Metod instalacije** - Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **Je „Klikni i pokreni“ instalacija** – zastavica koja ukazuje na to da li je instalacija tipa „Klikni i pokreni“. Omogućava nam da prepoznamo probleme koje mogu biti specifični za mehanizam „Klikni i Pokreni“ instalacije.

  - **IsDebug** – Zastavica koja ukazuje na to da li verzija sistema Office predstavlja izdanje za otklanjanje grešaka. Omogućava nam da otkrijemo da li problemi dolaze iz verzija za otklanjanje grešaka koje mogu da se ponašaju drugačije.

  - **Je instalirano na spoljašnjem uređaju za skladištenje** – zastavica koja ukazuje na to da li je sistem Office instaliran na spoljašnjem uređaju za skladištenje. Omogućava nam da odredimo da li uzrok problema može biti vezan za spoljni prostor za skladištenje.

  - **Je OEM Instalacija** – zastavica koja ukazuje na to da li je Office instalirao proizvođač originalne opreme (OEM). Omogućava nam da odredimo da li je aplikaciju instalirao OEM, što nam može pomoći da klasifikujemo i identifikujemo probleme.

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

  - **SusClientId** – Windows Update ID uređaja na kome se pokreće Office.

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

  - **IsExportable** – Polje koje označava da li je ovom događaju potrebna dodatna obrada kanala izvoza.

  - **Level** – označava tip događaja.

  - **Ime** - Ime događaja. Omogućava da identifikujemo događaj koji je klijent poslao.

  - **Pravilo** – Identifikator pravila koji je generisao podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Id pravila** – Identifikator pravila koje je generisalo podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Interfejs pravila** - Bilo koji interfejs koji određeno pravilo implementira. Omogućava nam da klasifikujemo i uvezemo podatke zasnovane na njihovoj strukturi, što pojednostavljuje obradu podataka.

  - **Verzija pravila** – Identifikator pravila koje je generisalo podatke ako su generisani po pravilu. Omogućava nam da utvrdimo izvor dela podataka, kako bismo mogli da proverimo valjanost i upravljamo parametrima tog događaja.

  - **Učestalost uzorkovanja** – Pokazatelj procenta korisnika koji šalju ovaj deo podataka. To nam omogućava da uradimo statističku analizu podataka i za vrlo česte tačke podataka ne zahteva slanje od svih korisnika.

  - **Verzija šeme** – Verzija šeme koja se koristi za generisanje dijagnostičkih podataka. Obavezno za upravljanje podacima koji su poslati od klijenta. Ovo omogućava povremene promene podataka koje svaki klijent šalje.

  - **Redosled** - Brojač koji identifikuje redosled prema kojem je događaj generisan na klijentu. Omogućava da se primljeni podaci poređaju tako da možemo da utvrdimo koji su koraci možda doveli do problema koji utiče na klijente.

  - **Izvor** -Izvorni kanal koji je korišćen za otpremanje podataka. Obavezno za praćenje svih naš otpremnih kanala za celokupno zdravlje i za pomoć u prepoznavanju problema sa otpremnih kanala. To nam omogućava praćenje pojedinačnih otpremnih kanala kako bismo obezbedili njihovu usaglašenost.

  - **Vreme** – Vreme generisanja događaja na klijentu. Omogućava nam da sinhronizujemo i proverimo redosled događaja generisanih na klijentu, kao i da uspostavimo pokazatelje performansi za uputstva korisnika. 

#### <a name="host"></a>Domaćin

Informacije o aplikaciji koja sadrži ugrađenu aplikaciju

Ova kategorija sadrži sledeća polja:

  - **ID** -Jedinstveni identifikator koji ugrađena aplikacija pripisuje aplikaciji koja je domaćin.

  - **ID sesije** – univerzalni jedinstveni identifikator za sesiju domaćina.

  - **Verzija** – Identifikator verzije primarne izvršne datoteke domaćina.

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

  - **Id vrednost klijenta za uzorkovanje** - Vrednost ključa koji se koristi za određivanje uzorkovanja. Omogućava nam da utvrdimo zašto je sesija uzorkovana ili nije.

  - **Id vrednost uređaja za uzorkovanje** - Vrednost ključa koji se koristi za određivanje uzorkovanja. Omogućava nam da utvrdimo zašto je sesija uzorkovana ili nije.

  - **Ključ uzorkovanja** -ključ koji se koristi za određivanje da li je sesija uzorkovana ili ne. Omogućava nam da razumemo kako pojedinačne sesije prave izbor da li su uzorkovane ili ne.

  - **Metoda uzorkovanja** - Metoda koja se koristi za određivanje smernica za uzorkovanje. Omogućava nam da razumemo koji podaci potiču iz sesije.

  - **K vrednost uzorkovanja sesije** – Napredni metapodaci uzorkovanja. Koriste se za procenu statističkog značenja primljenih podataka.

  - **N vrednost uzorkovanja sesije** – Napredni metapodaci uzorkovanja. Koriste se za procenu statističkog značenja primljenih podataka.

  - **Redosled** - Jedinstveni numerički identifikator za sesiju. Omogućava redosled sesija za analizu problema koji može da nastane.

  - **Početak** – Vreme pokretanja procesa sesije. Omogućava nam da utvrdimo kada je sesija počela.

  - **Nivo dozvole za telemetriju** – Vrednost koja ukazuje na nivo prikupljanja dijagnostičkih podataka koji je korisnik dozvolio. Omogućava nam da razumemo koji nivo dijagnostičkih podataka da očekujemo od sesije.

  - **Razlika između vremenskih zona u minutima** - Razlika u minutima između lokalnog vremena i UTC vremena. Omogućava normalizaciju UTC vremena u lokalno vreme.

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

- **Activity_FailCount** – Koliko puta ova aktivnost nije uspela

- **Activity_Name** – Skraćeno ime događaja. Omogućava da identifikujemo događaj koji je klijent poslao.

- **Activity_Namespace** – Prostor imena događaja. Dozvoljava grupisanje događaja u grupe.

- **Activity_Reason** - Niska koja pokazuje razlog zbog kojeg se aktivnost završava određenim rezultatom.

- **Activity_Result** - Zastavica koja ukazuje da li je aktivnost uspela, nije uspela ili neočekivano nije uspela. Omogućava nam da utvrdimo da li se radnje koje korisnik preduzima u proizvodu uspešno izvršavaju ili ne. To nam omogućava da prepoznamo probleme koji utiču na korisnika.

- **Activity_State** – Zastavica koja označava da li je događaj početak korisničke aktivnosti ili kraj korisničke aktivnosti.

- **Activity_FailCount** – Koliko puta je ova aktivnost uspela.

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

- **SessionCorrelationId** – Univerzalni jedinstveni identifikator za sesiju domaćina.

- **SH_ErrorCode** – Označava kôd greške ako je dostupan ako neka aktivnost ne uspe.

- **Oznaka** - Oznaka celog broja koji određuje lokaciju u kodugde se generiše telemetrijski događaj.

- **UserInfo_IdType** – Niska označava vrstu korisničkog naloga

- **UserInfo.OMSTenantId** – Zakupac za koga je vezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

- **UserInfo_OtherId** – Lista neprimarnih pseudonimnih identifikatora koji predstavljaju korisničke naloge.

- **UserInfo_OtherIdType** – Lista tipova naloga koji nisu primarni.

## <a name="data-fields-that-are-common-for-outlook-mobile-events"></a>Polja podataka koja su uobičajena za Outlook Mobile događaje

Outlook Mobile prikuplja uobičajena polja za svaki od naših događaja tako da možemo osigurati da je aplikacija ažurirana, bezbedna i funkcioniše kao što je očekivano. 

Sledeća polja podataka su uobičajena za sve događaje za Outlook u sistemu iOS i Android.

- **aad_tenant_id** – ID zakupca klijenta ako je dostupan

- **account_cid** – identifikator pod pseudonimom koji predstavlja trenutnog korisnika.

- **account_domain** – Ime domena naloga

- **account_puid** - Globalni jedinstveni identifikator korisnika Microsoft naloga.

- **account_type** – Prati tip naloga kao što je Office 365, Google Cloud Cache, Outlook.com itd.

- **action** – Ime radnje događaja (kao što je arhiviraj, Izbriši itd.) tako da možemo da otkrijemo probleme sa određenim radnjama koje su preduzete.

- **ad_id** – Jedinstveni identifikator oglašavanja

- **app_version** – Aktuelna verzija instalirane aplikacije koja bi trebala da nam pomogne da otkrijemo probleme koji utiču na određenu verziju aplikacije

- **AppInfo.ETag** - Jedinstveni identifikator za upravljanje objavljivanjem naših funkcija koji bi trebao da nam pomogne da otkrijemo probleme koji utiču na određene funkcije koje se objavljuju

- **AppInfo.Language** - Trenutna postavka jezika na uređaju koja bi trebala da nam pomogne da otkrijemo probleme koji utiču na određene jezike

- **AppInfo.Version** – Aktuelna verzija instalirane aplikacije koja bi trebala da nam pomogne da otkrijemo probleme koji utiču na određenu verziju aplikacije

- **ci** – pseudonimski jedinstveni identifikator uređaja specifičan za aplikaciju

- **cid_type** – ukazuje na tip naloga, kao što je komercijalni nalog ili Outlook.com nalog.

- **cloud** - Gde se nalazi poštansko sanduče za nalog na ovom uređaju, pomaže u otkrivanju problema specifičnih za određeni oblak poštanskog sandučeta, kao što je Office 365 ili GCC.

- **customer_type** – Pokazuje tip klijenta (potrošač, trgovac, treća strana itd.) da nam pomogne da ustanovimo probleme koji utiču na određene tipove klijenata

- **device_category** – Ukazuje na tip uređaja (telefon, tablet, itd.) da nam pomogne da ustanovimo probleme sa određenom kategorijom uređaja

- **DeviceInfo.Id** – Jedinstveni identifikator uređaja koji nam pomaže da otkrijemo probleme sa određenim uređajem

- **DeviceInfo.Make** – Marka uređaja (tj. Apple, Samsung itd) pomaže nam da otkrijemo probleme sa određenom markom uređaja

- **DeviceInfo.Model** – Model uređaja (tj. iPhone 6s) nam pomaže da otkrijemo probleme sa određenim modelom uređaja

- **DeviceInfo.NetworkType** – Mreža uređaja koja se trenutno koristi (WiFi, mobilna mreža itd), pomaže nam da otkrijemo probleme sa određenom mrežom uređaja

- **DeviceInfo.OsBuild** - Aktuelna verzija operativnog sistema uređaja, pomaže nam da otkrijemo probleme koji utiču na određene verzije operativnog sistema

- **DeviceInfo.OsName** – Ime operativnog sistema (na primer, iOS), pomaže nam da otkrijemo probleme koji utiču na određene platforme

- **DeviceInfo.OsVersion** - Aktuelna verzija operativnog sistema uređaja, pomaže nam da otkrijemo probleme koji utiču na određene verzije operativnog sistema

- **DeviceInfo.SDKUid** – Jedinstven identifikator uređaja (slično kao DeviceInfo.Id)

- **EventInfo.InitId** – ID koji se koristi kao deo sekvence za redosled događaja putem našeg telemetrijskog kanala, pomaže nam da otkrijemo osnovni uzrok problema sa kanalom

- **EventInfo.SdkVersion** – SDK verzija koju koristimo za slanje telemetrije kako bismo otkrili osnovni uzrok problema sa kanalom

- **EventInfo.Sequence** - Sekvenca za redosled događaja putem našeg telemetrijskog kanala, pomaže nam da otkrijemo osnovni uzrok problema sa kanalom

- **EventInfo.Source** – Govori nam koji deo koda nam je poslao događaj, pomaže nam da otkrijemo osnovni uzrok problema

- **EventInfo.Time** – Vreme i datum kada je događaj emitovan na uređaju tako da naši sistemi mogu uspešno da upravljaju događajima koji pristižu

- **eventpriority** – Prioritet telemetrijskog događaja u odnosu na druge događaje tako da naši sistemi mogu uspešno da upravljaju događajima koji pristižu

- **first_launch_date** – Prvo pokretanje aplikacije, pomaže nam da shvatimo kada se problem prvi put pojavio

- **hashed_email** – Identifikator pod pseudonimom koji predstavlja e-poštu trenutnog korisnika

- **is_first_session** - Prati da li je ovo prva sesija aplikacije radi otklanjanja grešaka

- **origin** - Poreklo radnje. Na primer, označavanje pročitane poruke može da potiče sa liste poruka ili od obaveštenja o pristigloj pošti, to nam pomaže da otkrijemo probleme na osnovu porekla radnje

- **PipelineInfo.AccountId** – Identifikator pod pseudonimom koji predstavlja trenutnog korisnika

- **PipelineInfo.ClientCountry** – Zemlja u kojoj se uređaj trenutno nalazi radi otkrivanja problema i prekida u određenoj zemlji ili regionu

- **PipelineInfo.ClientIp** - IP adresa sa kojom je uređaj povezan radi otklanjanja problema sa povezivanjem

- **PipelineInfo.IngestionTime** - Vremenske oznake kada se odvija preuzimanje telemetrije za ovaj događaj

- **sample_rate** – Procenat uređaja koji prikupljaju instance događaja. Pomaže u izračunavanju originalnog broja instanci događaja.

- **Session.Id** – Jedinstveni identifikator sesije aplikacije, pomaže u identifikaciji problema sa sesijom

- **Sesija.Impresionid** – Jedinstveni identifikator za upravljanje objavljivanjem funkcija obezbeđuje uspešno objavljivanje svim korisnicima i uređajima

- **ui_mode** – Da li korisnik koristi svetli ili tamni režim, pomaže pri trijaži UX grešaka sa tamnim režimom

- **UserInfo.Language** - Jezik korisnika, pomaže u otklanjanju grešaka sa prevodom teksta

- **UserInfo.TimeZone** - Vremenska zona korisnika radi otklanjanja problema sa kalendarom


Pored toga, sledeća polja su uobičajena za sve događaje za aplikaciju Outlook u sistemu iOS.

- **DeviceInfo.NetworkProvider** – Dobavljač mreže uređaja (tj. Verizon)

- **gcc_restrictions_enabled** – Saopštava nam da li su GCC ograničenja primenjena na aplikaciju kako bismo obezbedili da GCC klijenti bezbedno koriste našu aplikaciju
 
- **multi_pane_mode** – Govori nam da li korisnik na iPad računaru koristi svoje prijemno sanduče sa uključenim više okana gde može da vidi svoju listu direktorijuma dok triažira e-poštu. To je potrebno kako bi nam pomoglo da otkrijemo probleme specifične za one koji koriste svoje prijemno poštansko sanduče s više otvorenih okna.

- **multi_window_mode** – Saopštava nam da li korisnik na iPad uređaju koristi više prozora kako bismo lakše otkrili probleme vezane za korišćenje većeg broja prozora.

- **office_session_id** – Jedinstveni ID koji prati sesiju za povezane Office usluge, pomaže u otkrivanju problema sa integracijom određene Office usluge u programu Outlook, kao što je Word

- **state** – Da li je aplikacija bila aktivna kada je ovaj događaj poslat, pomaže pri otkrivanju problema specifičnih za aktivan ili neaktivan status aplikacije


Pored toga, sledeća polja su uobičajena za sve događaje za aplikaciju Outlook u sistemu Android.

- **aad_id** – pseudonimski Azure Active Directory identifikator

- **DeviceInfo.NetworkCost** – Naznaka postojećih mrežnih troškova uređaja koja prikazuje status usluge WiFi/mobilne mreže/rominga, pomaže u otkrivanju problema specifičnih za mrežu uređaja

- **is_app_in_duo_split_view_mode** – To će nam dati do znanja da je aplikacija bila u Duo režimu podeljenog ekrana.  Ovo svojstvo je postavljeno samo za Duo (samo Android) uređaje.

- **is_dex_mode_enabled** - Da li je Samsung DeX režim omogućen, pomaže u otkrivanju problema koji su specifični za DeX režim Samsung uređaja

- **is_preload_install** – Govori nam da li je aplikacija unapred učitana na uređaju (Android 11 ili kasnijim uređajima)

- **is_sliding_drawer_enabled** – Da li je omogućen interfejs kliznog menija, pomaže u otkrivanju problema koje uzrokuje interfejs kliznog menija

- **oem_preinstall** - Govori nam da li je aplikacija unapred instalirana na uređaju

- **oem_preload_property** – Govori nam da li je naša aplikacija unapred učitana u sklopu određenog ugovora sa OEM-om

- **orientation** - Fizički položaj ekrana (uspravan/položen), pomaže pri otkrivanju problema specifičnih za položaj uređaja

- **os_arch** - Arhitektura operativnog sistema uređaja, pomaže u otkrivanju problema specifičnih za operativni sistem uređaja

- **process_bitness** - Broj bitova procesa (32 ili 64) aplikacije, pomaže u otkrivanju problema koji su specifični za broj bitova uređaja

- **webview_kernel_version**: verzija jezgra sistema Chromium veb prikaza na uređaju koja nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.

- **webview_package_name**: naziv paketa veb prikaza na uređaju koji nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.

- **webview_package_version**: verzija paketa veb prikaza na uređaju koji nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.


## <a name="software-setup-and-inventory-data-events"></a>Podaci dobijeni iz instalacije i popis softvera

Podtipovi podataka koji spadaju u ovu kategoriji su:
- [Podešavanje sistema Office i popis](#office-setup-and-inventory-subtype)
- [Konfiguracija Office programskih dodataka](#office-add-in-configuration-subtype)
- [Bezbednost](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Podtip podešavanja sistema Office i popisa*

Instalirani proizvod, verzija i status instalacije.

#### <a name="addssoaccount"></a>add.sso.account

Ovo će obavestiti Microsoft o tome da li je korisnik uspeo da doda nalog putem jedinstvenog prijavljivanja (SSO) ili nije.

Prikupljaju se sledeća polja: 

- **account_type** – tip naloga koji je dodat koristeći SSO.

- **action_origin** – odakle je generisan ovaj događaj. (na primer, vrednosti: sso_drawer, sso_add_account, sso_add_account_prompt, sso_settings, sso_oobe).

- **provider** – identifikator dobavljača softverskog paketa za SSO.

- **state** – trenutno stanje naloga (na primer, vrednosti: FAILED, PENDING, ADDED itd.)


#### <a name="installreferral"></a>install.referral

Ovaj događaj se pokreće prilikom početne instalacije aplikacije i beleži odakle je korisnik upućen (ako je dostupan).

Prikupljaju se sledeća polja:

- **install_referrer** – proizvod ili iskustva odakle je korisnik upućen

 
#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Primenljivo na sve win32 aplikacije. Pomaže nam da razumemo status procesa ažuriranja Office paketa (uspeh ili neuspeh sa detaljima o grešci)

Prikupljaju se sledeća polja:

- **izdanje** - Trenutno instalirana verzija sistema Office

- **kanal** - Kanal preko kog je distribuiran sistem Office.

- **kôd greške** -kôd greške koji ukazuje na neuspeh

- **poruka greške** – Dodatne informacije o grešci

- **status** - Trenutni status ažuriranja

- **ciljno izdanje** - Verzija na koju se sistem Office ažurira

#### <a name="officecompliancefileformatballotdisplayedonfirstboot"></a>Office.Compliance.FileFormatBallotDisplayedOnFirstBoot

Ukazuje na to da li je dijalog Izbor formata Office datoteka prikazan korisniku na prvom/drugom mestu prilikom pokretanja programa Word, Excel, PowerPoint u sistemu Win32.  Prati da li je prikazan dijaloški okvir FileFormat Ballot – događaj se šalje prilikom prvog / drugog pokretanja programa Word, Excel ili PPT Win32.

Prikupljaju se sledeća polja.

- **ZemljaRegion** – Podešavanje regiona zemlje korisnika u sistemu Windows

- **FileFormatBallotBoxAppIDBootedOnce** – U kojoj je aplikaciji (Word, Excel, PPT) obrađena logika glasačkog prikaza u formatu datoteke.

- **FileFormatBallotBoxDisplayedOnFirstBoot** - Šta je rezultat prikaza za format datoteke (prikazano/nije prikazano kao neočekivano/nije prikazano zbog licence/nije prikazano zbog lokacije).

#### <a name="officecompliancefileformatballotoption"></a>Office.Compliance.FileFormatBallotOption

Prati da li je prikazan dijaloški okvir FileFormat Ballot – događaj se šalje prilikom prvog / drugog pokretanja programa Word, Excel ili PPT Win32.  Ukazuje na to da li se dijalog Izbor formata Office datoteka prikazuje na prvom ili drugom mestu prilikom pokretanja programa Word, Excel ili PowerPoint u sistemu Win32.

Prikupljaju se sledeća polja:

- **FileFormatBallotSelectedOption** – Prepoznaje opciju formata datoteke (OOKSML / ODF) koju je korisnik odabrao putem dijaloškog okvira za glasački oblik datoteke.


#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Prikuplja metapodatke sistema Office kroz UTC za poređenje sa ekvivalentnim podacima prikupljenim putem kanal Office telemetrije u cilju provere ispravnosti i potpunosti podataka.

Prikupljaju se sledeća polja:

- **ab konfiguracije** - Lista ID-ova funkcija za utvrđivanje koje funkcije su omogućene na klijentu ili su prazne kada se ti podaci se ne prikupljaju.

- **abFlights** -„NoNL:NoFlights” kada letovi funkcija nisu podešeni. U suprotnom „holdoutinfo = nepoznato”.

- **Guid sesije aplikacije** – identifikator sesije za određenu aplikaciju počevši od vremena kreiranja procesa do kraja procesa. Oblikovan je kao standardni 128–bitni GUID, ali se sastoji iz 4 dela. Ta četiri dela su po redu (1) 32–bitni ID procesa (2) 16–bitni ID sesije (3) 16–bitni ID za pokretanje (4) 64–bitni proces nastanka u UTC 100ns

- **appVersionBuild** - Broj verzije izdanja aplikacije.

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

- **osEnvironment** – Ceo broj koji označava operativni sistem (Windows, Android, iOS, Mac, itd).

- **niska verzije operativnog sistema** - Verzija operativnog sistema.

- **ID sesije** – nasumično generisan guid za identifikovanje sesije aplikacije

- **UTCReplace_AppSessionGuid** - Nepromenjiva logička vrednost. Uvek ima vrednost TRUE.

#### <a name="officeonenoteandroidapponenotelaunchednonactivated"></a>Office.OneNote.Android.App.OneNoteLaunchedNonActivated

*[Ovaj događaj je prethodno nazvan OneNote.App.OneNoteLaunchedNonActivated.]*

Beleži informacije o stanju aktivacije u aplikaciji.  Podaci se nadziru da bi se osiguralo identifikovanje problema sa aktivacijom. Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje.

Prikupljaju se sledeća polja: 

- **INSTALL_LOCATION** – Označava da li je aplikacija unapred instalirana ili da li je preuzeta iz prodavnice

#### <a name="officeonenoteandroidresetstatus"></a>Office.OneNote.Android.ResetStatus

*[Ovaj događaj je prethodno nazvan OneNote.ResetStatus.]*

Signal koji se koristi za beleženje bilo kakvih problema kada korisnik pokuša da poništi podešavanja aplikacije i vrati ih na prvobitne vrednosti.  Telemetrija se koristi za nadgledanje, otkrivanje i rešavanje problema tokom poništavanja podešavanja aplikacije i vraćanja na prvobitne vrednosti. 

Prikupljaju se sledeća polja: 

- **Accounts** - Označava tipove naloga koji se koriste za prijavljivanje unutar aplikacije

- **Generic String Type** - Vraća se ako je potpuno vraćanje notes_light_data reset

- **LaunchPoint** - Tačka iz koje se pokreće vraćanje na prvobitne vrednosti. Moguće vrednosti: dugme „Odjavljivanje”, neuspelo prijavljivanje, Intune aktiviranje

- **Pass** – Označava da li je uspostavljanje početnih vrednost bilo uspešno

#### <a name="officeonenoteandroidsigninsignincompleted"></a>Office.OneNote.Android.SignIn.SignInCompleted

*[Ovaj događaj je prethodno nazvan OneNote.SignIn.SignInCompleted.]*

Kritičan signal koji se koristi da omogući uspešno prijavljivanje. Telemetrija se prikuplja da omogući otkrivanje kritičnih regresija za OneNote aplikaciju i ispravnost usluge.

Prikupljaju se sledeća polja: 

- **CompletionState** - Konačno stanje prijavljivanja - uspešno ili neuspešno. I slučajevi neuspeha

- **EntryPoint** - Ukazuje odakle je pokrenuta prijava

- **Hresult** - Kôd greške

- **Provider Package ID** - U slučaju automatskog prijavljivanja

- **Result**- Uspeo, neuspešan, nepoznat, otkazan

- **ServerType** - daje tip servera koji nudi uslugu 

- **SignInMode** - prijavljivanje, automatsko prijavljivanje ili ubrzavanje prijavljivanja

#### <a name="officeonenoteandroidsigninsigninstarted"></a>Office.OneNote.Android.SignIn.SignInStarted

*[Ovaj događaj je prethodno nazvan OneNote.SignIn.SignInStarted.]*

Signal koji se koristi za označavanje problema prilikom korišćenja trake sa porukama.  Telemetrija se koristi za nadgledanje, otkrivanje i rešavanje problema tokom interakcije sa trakom sa porukama.

Prikupljaju se sledeća polja: 

- **EntryPoint** - Ukazuje odakle je pokrenuta prijava

- **Result** - Rezultat toka prijavljivanja

- **ServerType** – Daje tip servera koji nudi uslugu 

- **SignInMode** – prijavljivanje, automatsko prijavljivanje ili ubrzavanje prijavljivanja


#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritičan signal koji se koristi da omogući da novi korisnici mogu uspešno da pokrenu i koriste OneNote po prvi put.  Telemetrija se prikuplja da obezbedi otkrivanje kritičnih regresija za OneNote aplikaciju i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

- **AfterOneDriveFrozenAccountError** - Ukazuje na grešku koja se javlja u OneDrive aplikaciji kada je nalog zamrznut.

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **IsDelayedSignIn** – Ukazuje na to da li se prvo pokretanje vrši u odloženim režimu prijavljivanja u kojem korisnik nije dužan da se prijavi.

- **IsMSA** – Ukazuje na to da li se radi o Microsoft nalogu ili ne.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritičan signal koji se koristi da omogući da novi pojedinačni korisnici (Microsoft nalog) mogu uspešno da pokrenu i koriste OneNote po prvi put.

Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

Prikupljaju se sledeća polja:

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **Greška A** – OneNote objekat greške ukazuje na bilo koju grešku tokom prvog pokretanja.

- **FAllowAddingGuide** - Ukazuje na to da li će OneNote dozvoliti kreiranje beležnice sa vodičem ili ne.

- **FrozenOneDriveAccount** - Ukazuje na to da li je OneDrive nalog zamrznut ili ne.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **NoInternetConnection** - Ukazuje na to da li uređaj ima ili nema internet vezu.

- **ProvisioningFailure** - OneNote objekat greške ukazuje na postojanje ili nepostojanje greške pri dodeljivanju privilegija.

- **ProvisioningFinishedTime** - Označava vreme kada će OneNote završiti dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ProvisioningStartedTime** - Označava vreme kada će OneNote početi dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ShowSuggestedNotebooks** - Ukazuje na to da li će OneNote prikazati funkciju predložene beležnice ili ne.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritičan signal koji se koristi da omogući da novi korisnici u velikim preduzećima mogu uspešno da pokrenu i koriste OneNote po prvi put.  Telemetrija koja se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

- **Attempt** - Koliko puta treba ponovo pokušati pokretanje prvog utiska.

- **Error** - OneNote objekat greške ukazuje na bilo koju grešku tokom prvog pokretanja.

- **FAllowAddingGuide** - Ukazuje na to da li će OneNote dozvoliti kreiranje beležnice sa vodičem ili ne.

- **IsDefaultNotebookCreated** - Ukazuje na to da li je aplikacija OneNote kreirala podrazumevanu beležnicu za korisnika ili ne.

- **ProvisioningFailure** - OneNote objekat greške ukazuje na postojanje bilo kakve greške pri dodeljivanju privilegija.

- **ProvisioningFinishedTime** - Označava vreme kada će OneNote završiti dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

- **ProvisioningStartedTime** - Označava vreme kada će OneNote početi dodelu privilegija za beležnicu prilikom pokretanja prvog utiska.

#### <a name="officeonenotefirstrunmrureadernotebookentries"></a>Office.OneNote.FirstRun.MruReaderNoteBookEntries 

Signal koji se koristi za snimanje bilo kakvih problema prilikom učitavanja Beležnica tokom prvog pokretanja.  Telemetrija se koristi za nadgledanje, otkrivanje i rešavanje problema tokom prvog pokretanja.

Prikupljaju se sledeća polja: 

- **OnPremNBCount**- Broj beležnica na Prem serveru

- **TotalNBCount**- ukupan broj beležnica povezanih sa korisničkim nalogom

#### <a name="officeonenotesystemapplifecycleuseraccountinfo"></a>Office.OneNote.System.AppLifeCycle.UserAccountInfo

Ovaj događaj se pokreće za deljeni kôd i vrednosti zapisa za tip naloga prijavljenih putem usluge isEdu, isMsftInternal, isIW, isMSA. Podaci se prikupljaju prvi put kada dođe do zastoja u redu nakon pokretanja. Ovaj označivač se koristi za praćenje tipova naloga koji su prijavljeni na uređaju. To će nam pomoći da identifikujemo EDU korisnike u OneNote. 

Prikupljaju se sledeća polja: 

- **IsEdu** – moguće vrednosti – true/false

- **IsMSA** – moguće vrednosti – true/false

- **IsIW** – moguće vrednosti – true/false

- **IsMsftInternal** – moguće vrednosti – true/false


#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Prati da li je preuzet paket za „Dinamičko platno“. Smatra se konfiguracijom softvera zato što paket mora biti uspešno preuzet da bi klijentu omogućio pružanje odgovarajućeg iskustva. Posebno je važno u korisničkim pretplatama gde platno koristimo da korisnika obavestimo da je licenca istekla. Koristi se za praćenje metapodataka paketa dinamičkog sadržaja koje proizvod preuzima i kešira, kao i rezultate operacija koje se izvršavaju na paketu: neuspela preuzimanja, neuspela raspakivanja, greške pri proveri doslednosti, pregledi keša, primene paketa, izvori preuzimanja.

Prikupljaju se sledeća polja:

  - **Podaci\_KeširanaFasciklaNijeKreirana –** Bulova zastavica koja ukazuje na to da je kreiranje fascikle keša uspešno izvršeno

  - **Podaci\_CdnPath – izvorna adresa paketa-**

  - **Podaci\_EnsureCached -** Bulova zastavica koja ukazuje na to da li je paket sa sadržajem keširan

  - **Podaci\_Već postoji -** Bulova zastavica koja ukazuje na to da je paket ranije već bio preuzet i da je napravljen još jedan pokušaj

  - **Podaci\_Preuzimanje toka datoteka nije uspelo -** izvorni paket nije dostupan u izvoru

  - **Podaci\_Preuzimanje toka datoteka nije uspelo na kreira lokalnu fasciklu -** problemi na lokalnom disku izazivaju grešku prilikom kreiranja direktorijuma

  - **Podaci\_Preuzimanje toka datoteka iz paketa nije uspelo –** zastavica koja označava da li je paket preuzet, ali ga klijent ne može pročitati

  - **Podaci\_Preuzimanje toka datoteka iz paketa je uspelo -** uspešni pokušaj čitanja paketa

  - **Data\_GetFileStreamSuccess –** nema problema s diskom ili konfiguracijom koji ne dozvoljavaju čitanje toka datoteka

  - **Podaci\_Preuzimanje relativne putanje nije uspelo –** relativna putanja ne upućuje na pristupačnu lokaciju

  - **Podaci\_Stvarna vrednost heša -** heš vrednost izdvojena iz imena datoteke kada je paket upotrebljen

  - **Podaci\_Neuspešno izračunavanje heša -** greška pri izračunavanju heša

  - **Podaci\_HashMatchFailed -** nepodudaranje heša za ime paketa i keširanih vrednosti registratora

  - **Podaci\_HashMatchSuccess -** uspešna provera doslednosti heša

  - **Podaci\_Neuspeli zahtev za preuzimanje paketa –** preuzimanje paketa nije moguće

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

- **SolutionId** – ID Rešenja

- **StoreType** - ukazuje na poreklo aplikacije


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

Podaci u vezi sa uspehom za neuspelo preuzimanje potrebe za ažuriranim podacima o administratorski dodeljenim programskim dodacima za Office 365 zakupca. Koristi se za metriku ispravnosti, grafikone i analize problema klijenata. ExchangeGetLastUpdate će se uvek izvršiti prilikom pokretanja operativnog sistema kao deo koda hosta i utvrditi da li su promenjene dodele programskih dodataka za korisnika.   Ako je tako, onda će se osf.DLL Će učitati tako da možemo da pozovemo ExchangeGetEntitlements da dobijemo određene zadatke (i ExchangeGetManifests će biti pozvan da preuzme sve nove manifeste koji su potrebni).   ExchangeGetEntitlements (i ExchangeGetManifests) može se takođe pozvati na zahtev kada je host aplikacija pokrenuta.   Ideja je da se ne učitava veliki DLL ako nema potrebe za tim.   Bez ovog događaja u Obavezno, ne bismo mogli da prepoznamo da li korisnici ne uspevaju da događaju do programskih dodataka koji su im dodeljeni ako to prvo pozivanje usluge ne uspe.   To takođe predstavlja glavni pokazatelj za sve probleme potvrde identiteta sa kojima se suočavamo prilikom komunikacije sa uslugom.

Prikupljaju se sledeća polja:

  - **Prekid -** da li je host ugašen tokom poziva usluge

  - **Dozvola zahteva -** da li je bio dozvoljen zahtev za potvrdu identiteta

  - **Šema potvrde identiteta -** šema potvrde identiteta koju zahteva exchange

  - **BackEndHttpStatus –** http kôd koji je naveden prilikom kominikacije sa exchange potporom

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

  - **Mso Http Rezultat –** vrednost brojača koju je vratio http API

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

Prikuplja informacije o pozivanju Win32 API–a u VBA rešenjima. Koristi se za razumevanje interakcije između VBA i upotrebe i za dopunu istraga bezbednosti.

Prikupljaju se sledeća polja:

  - **Broj deklaracija** – broj deklaracija

  - **Heš deklaracija** – heš DLL imena

  - **Ulazna tačka heša** – heš API imena

  - **HashProjectName** – heš imena VBA projekta

  - **IsPtrSafe** – da li je izjava deklaracije kompatibilna za različitu arhitekturu

  - **Id oznake** – jedinstvena oznaka

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Prikupljaju se podaci o uspešnom ili neuspešnom pokretanju dodatka. Ti podaci se aktivno prate da bi se osigurao ispravan rad programa Outlook sa programskim dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

  - **Standardna HVA aktivnost** bez prilagođenih korisnih podataka

#### <a name="officeoutlookmacaddinapiusage"></a>Office.Outlook.Mac.AddinAPIUsage

Prikuplja uspeh i neuspeh izvršavanja programskih dodataka u programu Outlook.Ti podaci se aktivno prate kako bi se osigurao ispravan rad programa Outlook sa dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AccountType** - vrsta naloga povezanog sa dodatkom 

- **Cookie** – kolačić koji koristi programski dodatak

- **DispId** - identifikator dispečera 

- **EndTime** - vreme kada je završen programski dodatak 

- **ExecutionTime** - vreme koje je proteklo tokom izvršenja programskog dodatka 

- **Result** - rezultat upotrebe programskog dodatka u programu Outlook 

- **StartTime** - vreme kada je počeo programski dodatak


#### <a name="officeoutlookmacaddineventapisusage"></a>Office.Outlook.Mac.AddinEventAPIsUsage

Prikuplja uspeh ili neuspeh izvršavanja programski dodatak u programu Outlook. Ti podaci se aktivno nadgledaju kako bi se obezbedilo da Outlook ispravno radi sa programski dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AddinType** – tip programskog dodatka 

- **EventAction** – radnja koju vrši programski dodatak 

- **EventDispid** - identifikator dispečera

- **EventResult** - rezultat radnje koju je izvršio programski dodatak 

#### <a name="officeoutlookmacaddininstallationfrominclientstore"></a>Office.Outlook.Mac.AddInInstallationFromInClientStore

Prikuplja uspeh i neuspeh izvršavanja programskih dodataka u programu Outlook.Ti podaci se aktivno prate kako bi se osigurao ispravan rad programa Outlook sa dodacima. Ti podaci se koriste za otkrivanje i istraživanje problema.

Prikupljaju se sledeća polja:

- **AccountType** - vrsta naloga koji je povezan sa dodatkom 

- **FailureReason** - razlog zbog koga programski dodatak nije uspeo da se instalira 

- **MarketplaceAssetId** – identifikator programskog dodatka u prodavnici 

- **Status** – status programskog dodatka za instalaciju


#### <a name="officeprogrammabilityaddinsinternalsetconnectenterprise"></a>Office.Programmability.Add ins.InternalSetConnectEnterprise

Događaj koji se generiše kada se COM programski dodatak učita na uređaju u okviru preduzeća. Koristi se za utvrđivanje problema sa usvojenjem, performansama i pouzdanošću pomoću programskih dodataka za Office. 

Prikupljaju se sledeća polja:

  - **account** – nalog koji je obavio radnju *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AddinConnectFlag** – trenutno ponašanje učitavanja 

  - **AddinDescriptionV2** – opis programskog dodatka

  - **AddinFileNameV2** – ime datoteke programskog dodatka, osim putanje datoteke

  - **AddinFriendlyNameV2** – prepoznatljivo ime programskog dodatka

  - **Add-inId** – ID klase programskog dodatka *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AddinIdV2** – Id klase programskog dodatka

  - **AddinProgIdV2** – Prog Id programskog dodatka

 - **AddinProviderV2** –programski dobavljač programskih dodataka

  - **Add-inTimeDateStamp** – vremenska oznaka programskog dodatka iz DLL metapodataka *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AddinTimeDateStampV2** – vremenska oznaka programskog dodatka dobijena iz DLL metapodataka

  - **AddinVersionV2** – verzija programskog dodatka

  - **IsBootInProgress** – da li je aplikacija Office u procesu pokretanja
 
  - **Učitavanje** –trajanje opterećenja programskog dodatka
  
  - **Loadresalt** – stanje uspeha opterećenja

  - **OfficeArchitecture** – Arhitektura Office klijenta


#### <a name="officeprogrammabilityaddinsribbonbuttonclick"></a>Office.Programmability.Addins.RibbonButtonClick

Događaj se generiše prvi put u sesiji kada korisnik klikne na dugme koje je određeni programski dodatak dodao na traku. Ako sesija obuhvata više dana, ova telemetrija će se umesto nje slati jednom dnevno. Podaci se koriste na dva načina: 1. Kada se programski dodatak prekine, saznanje koliko ga korisnici zaista koriste, pomoći će nam da preispitamo problem. 2. Prikazati administratorima kao deo COM scenarija upravljanja programskim dodacima u inventaru dodataka i kao deo planiranih scenarija ispravnosti programskih dodataka u Microsoft 365 ispravnosti aplikacija. Administratori će moći da nadgledaju upotrebu programskih dodataka po uređaju, omogućavajući im da onemoguće ili deinstaliraju neiskorišćene COM programske dodatke.

Prikupljaju se sledeća polja:

- **AddinTimeDateStamp** - vremenska oznaka programskog dodatka dobijena iz DLL metapodataka

- **CLSID** - identifikator klase programskog dodatka

- **Opis programskog dodatka** - opis programskog dodatka

- **FileName** - ime datoteke programskog dodatka, osim putanje datoteke

- **FriendlyName** - prepoznatljivo ime programskog dodatka

- **OfficeApplication** - Office aplikacija koja se trenutno izvršava

- **ProgID** - Prog identifikator programskog dodatka


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

  - **Podaci\_Greška**:**ceo broj** – ID greške

### <a name="security-subtype"></a>*Podtip bezbednosti*

Uslovi pod kojima dolazi do greški u dokumentima, funkcijama i dodacima a koje mogu da ugroze bezbednost, uključujući spremnost proizvoda za ažuriranje.

#### <a name="officeappguardcreatecontainer"></a>Office.AppGuard.CreateContainer

Prikupljamo kodove greške i informacije o tome da li je kontejner već postojao ili nije. Takođe prikupljamo kodove greške za događaj uspostavljanja početnih vrednosti u slučaju da ne uspemo da kreiramo kontejner pri prvom pokušaju. Podaci će se koristiti za identifikaciju procenta sesija u kojima smo uspešno kreirali kontejner za pokretanje Office Application Guard aplikacija. Podaci će takođe omogućiti korporaciji Microsoft da identifikuje i reši kodove greške iz kreiranja kontejnera.

Prikupljaju se sledeća polja:

- **ErrorCode1** – Tip koda greške pri podešavanju kontejnera.  

- **ErrorCode2** – Kôd greške iz izvršavanja kreiranja. 

- **ErrorCode3** – Dodatni kôd greške. 

- **Id** – Jedinstveni identifikator (GUID) za kreiranje kontejnera.

- **ResetError** – Kôd greške iz pokušaja uspostavljanja početnih vrednosti kontejnera nakon neuspelog pokušaja.

- **ResetErrorCode1** – Tip koda greške pri podešavanju kontejnera nakon komande za uspostavljanje početnih vrednosti. 

- **ResetErrorCode2** – Kôd greške iz izvršavanja kreiranja nakon komande za uspostavljanje početnih vrednosti.

- **ResetErrorCode3** – Dodatni kôd greške nakon komande za uspostavljanje početnih vrednosti.

- **ResetErrorType** – Tip greške tokom uspostavljanja početnih vrednosti: Kreiranje, Priprema datoteke ili Pokretanje.

- **WarmBoot** – Identifikuje da li je kontejner već bio kreiran ili nije.

#### <a name="officeappguardlaunchfile"></a>Office.AppGuard.LaunchFile

Ovaj događaj označava rezultat pokretanja izvršavanja Application Guard datoteka. Moći ćemo da definišemo procenat sesija u kojima smo uspešno pokrenuli Word, Excel ili PowerPoint datoteku i kodove greške za neuspele pokušaje.

Prikupljaju se sledeća polja:

- **AppId** – Identifikuje aplikaciju koja se pokreće.

- **DetachedDuration** – Identifikuje ukupno vreme utrošeno za objedinjenu aktivnost. 

- **ErrorCode1** – Tip koda greške pri podešavanju kontejnera.  

- **ErrorCode2** – Kôd greške iz izvršavanja kreiranja. 

- **ErrorCode3** – Dodatni kôd greške. 

- **FileId** – Jedinstveni identifikator (GUID) vraćen iz Windows API-ja nakon pokretanja datoteke.

- **Id** – Jedinstveni identifikator (GUID) za pokretanje i kreiranje datoteke. Ovaj ID se koristi za korelaciju događaja iz sistema Office i operativnog sistema Windows.

- **ResetError** – Kôd greške iz pokušaja uspostavljanja početnih vrednosti kontejnera nakon neuspelog pokušaja.

- **ResetErrorCode1** – Tip koda greške pri podešavanju kontejnera nakon komande za uspostavljanje početnih vrednosti. 

- **ResetErrorCode2** – Kôd greške iz izvršavanja kreiranja nakon komande za uspostavljanje početnih vrednosti.

- **ResetErrorCode3** – Dodatni kôd greške nakon komande za uspostavljanje početnih vrednosti.  

- **ResetErrorType** – Tip greške : Kreiranje, Priprema datoteke ili Pokretanje.



#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Prati kada se određeni identifikator klase (Flash, Silverlight itd.) aktivira u sistemu Office. Koristi se za praćenje uticaja blokiranja Flash, Silverlight i Shockwave kontrola na krajnje korisnike.

Prikupljaju se sledeća polja:

  - **Tip aktivacije** - Tip aktivacije za kontrolu

  - **Blokirani** - da li je office blokirao kontrolu

  - **CLSID** - identifikator klase kontrole

  - **Count** – koliko je puta aktivirana kontrola

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

Prati kada je u dokumentu otkriven OLE objekat. Koristi se da obezbedi efikasnost ublažavanje bezbednost koja štiti krajnje korisnike sistema Office.

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

  - **Smernice** – da li su smernice postavljene, nisu postavljene, ili nisu dostupne

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

Prati kada se od korisnika traži da uključi XL4 makroe. Koristi se za procenu rasprostranjenosti XL4 makroa u programu Excel i podsticanje budućih bezbednosnih olakšica koje automatski blokiraju XL4 kao odgovor na bezbednosne incidente koji uključuju zloupotrebu XL4 makroa.

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

Uspešna funkcionalnost aplikacije. Ograničeno na otvaranje i zatvaranje aplikacije i dokumenata, uređivanje i deljenje datoteka (saradnju).

#### <a name="accountaction"></a>account.action

Potrebno je da se osigura da konfiguracija naloga uspešno funkcioniše i da se koristi za nadgledanje zdravlja pri kreiranju naloga, mogućnosti dodavanja novih naloga e-pošte i nadgledanje promena početnih naloga 

Prikupljaju se sledeća polja: 

- **account_calendar_count** - koliko kalendara ima nalog
 
- **action** – tip izvršene akcije, npr. create_account, delete_account.
 
- **duration_seconds** - trajanje akcije
 
- **entry_point** - ulazna tačka akcije, kako je korisnik započeo akciju
 
- **has_hx** - da li uređaj ima nalog koji koristi našu novu uslugu sinhronizacije pošte, ne nužno i nalog na kome je izvršena radnja
 
- **is_hx** - nalog koji koristi našu novu uslugu sinhronizacije
 
- **is_shared_mailbox** - da li se radnja odnosi na deljeno poštansko sanduče
 
- **number_of_accounts** - ukupan broj naloga na kojima se radnja obavlja
 
- **result** – rezultat akcije, npr. uspeh, neuspeh.
   
- **server_type** - tip servera za nalog, slično kao account_type
 
- **shared_type** - tip deljenog naloga (ako je nalog deljen)
 
- **scope** - obim akcije; za brisanje naloga, this_device ili all_devices
 
- **total_calendar_accounts** - broj kalendarskih naloga u aplikaciji u trenutku radnje
 
- **total_email_accounts** - broj naloga e-pošte u aplikaciji u trenutku radnje
 
- **total_file_accounts** - broj naloga datoteke u aplikaciji u trenutku radnje

#### <a name="accountlifecycle"></a>account.lifecycle

Ovaj događaj se prikuplja da bi se osiguralo da konfiguracija naloga uspešno funkcioniše i da se koristi za nadgledanje zdravlja pri kreiranju naloga, mogućnosti dodavanja novih naloga e-pošte i nadgledanje promena početnih naloga.

Prikupljaju se sledeća polja: 

- **account_creation_source** – opciono svojstvo koje se koristi za pronalaženje i dijagnostikovanje problema koji se dešavaju tokom kreiranja naloga kada se doda tip radnje.  Ono može da ima vrednosti kao što su jedinstveno prijavljivanje (SS0), create_new_account, uputstvo, itd.

- **action** – Tip radnje koja se izvršava na nalogu, na primer, dodavanje, uklanjanje ili uspostavljanje početnih vrednosti

#### <a name="addnewaccountstep"></a>add.new.account.step

Ovaj događaj nam omogućava da otkrijemo koliko je korisnik napredovao u kreiranju novog obrasca naloga.  On ukazuje na to kada je korisnik prešao na drugi korak ili ako je otkazao.  Ove informacije su nam potrebne da bismo otkrili da li neki koraci ne uspevaju i da bismo obezbedili uspešnost kreiranja korisničkog naloga. 

Prikuplja se sledeće polje: 

- **OTAddAccountCurrentStep** – To može da ima sledeće vrednosti: profile_form, redirect_mobile_check, mobile_check_success

#### <a name="apperror"></a>app.error

Prati kritične greške aplikacije kako bismo sprečili probleme koji mogu da dovedu do toga da vam aplikacija padne ili da vam onemoguće da pročitate e-poštu.

Prikupljaju se sledeća polja: 

- **clientName** - Naziv klijenta za datoteku u oblaku u kojoj je došlo do greške, ako je primenljivo.

- **cloudfile_error_type** - Vrsta greške koja se dogodila za datoteku u oblaku, ako je primenljivo.

- **cloudfile_response_name** - Naziv odgovora za grešku koja se dogodila za datoteku u oblaku, ako je primenljivo.

- **component_name** - Naziv komponente aplikacije u kojoj se dogodila greška, kao što su pošta ili kalendar

- **debug_info** - Informacije o grešci koja se dogodila za datoteku u oblaku kako bi se moglo utvrditi zašto se greška dogodila.

- **error_origin_identifier** - Poreklo greške koja se dogodila na skici da je greška nastala, ako je primenljivo.

- **error_type** - Tip greške koja se dogodila. Neki primeri uključuju grešku sačuvaj radnu verziju, pošalji radnu verziju i grešku datoteke u oblaku.

- **exdate** – datum proširenog pravila (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **exrule** – proširena vrednost pravila (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **has_attachments** - odražava ako je došlo do nacrta greške u vezi sa prilogom, ako je primenljivo.

- **is_IRM_protected** - odražava ako je nacrt na kom se greška pojavila zaštićen programom Information Rights Management, ako je primenljivo.

- **is_legitimate** – odražava ako greška potiče od greške u programiranju ili ne. Greške u programiranju se smatraju nelegitimnim.

- **is_local** - odražava ako je došlo do nacrta greške u programu sinhronizovano sa serverom, ako je primenljivo.

- **is_recoverable** - odražava da li se greška može oporaviti od ili ako je u pitanju fatalna greška.

- **rdate** – datum pravila ponavljanja (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **rrule** – samo pravilo ponavljanja (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **rrule_error_message** – poruka o grešci sa raščlanjavanjem pravila ponavljanja (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **rrule_error_type** – vrsta greške sa raščlanjavanjem pravila ponavljanja (odnosi se samo na greške u ponavljanju zakazanih obaveza) *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **status_code** - Statusni kôd greške koja se dogodila. To nam pomaže da shvatimo uzrok greške.

Svi znakovi su takođe moguća svojstva. To nam pomaže da shvatimo znakove u radnoj verziji poruke kada se dogodila greška. Na primer, „a“, „b“, „c“ su moguća svojstva.

#### <a name="applaunchreport"></a>app.launch.report

Ovaj događaj se pokreće kada se Outlook pokreće sporo ili nepotpuno. Prikupljeni podaci pružaju informacije o određenim funkcijama koje su omogućene i o tome koliko dugo je trajalo pokretanje.  Omogućava nam da otkrijemo i otklonimo uzrok problema.

Prikupljaju se sledeća polja: 

- **is_agenda_widget_active** - govori nam da li je vidžet rasporeda aktivan.

- **is_alert_available** - Recite nam da li je aplikacija konfigurisana da dopušta upozorenja u obaveštenjima.

- **is_background_refresh_available** - govori da li je aplikacija konfigurisana za osvežavanje u pozadini.

- **is_badge_available** - recite nam da li je aplikacija podešena tako da omogući značke u obaveštenjima.

- **is_intune_managed** - recite nam da li aplikacijom upravlja Intune.

- **is_registered_for_remote_notifications** - recite nam da li je aplikacija registrovana za daljinska obaveštenja.

- **is_sound_available** - Recite nam da li je aplikacija podešena tako da dozvoli zvukove u obaveštenjima.

- **is_watch_app_installed** - saopštava nam da li je instalirana aplikacija sat Outlook.

- **is_watch_paired** - saopštava nam da li je Outlook aplikacija Sat uparena sa glavnom Outlook aplikacijom.

- **launch_to_db_ready_ms** - Recite nam koliko vremena je Outlook aplikaciji bilo potrebno od pokretanja do pripreme baze podataka.

- **num_calendar_accounts** - govori nam broj naloga kalendara u aplikaciji.

- **num_cloud_file_accounts** - govori nam broj naloga za skladištenje u aplikaciji.

- **num_hx_calendar_accounts** - govori nam broj naloga kalendara u aplikaciji koji se povezuju na našu novu uslugu sinhronizacije pošte.

- **num_hx_mail_accounts** - govori nam broj naloga pošte u aplikaciji koji se povezuju na našu novu uslugu sinhronizacije pošte.

- **num_mail_accounts** - govori nam broj naloga pošte u aplikaciji.

#### <a name="calendaraction"></a>calendar.action

Koristi se za nadgledanje mogućih negativnih uticaja na izvršavanje osnovnih radnji kalendara poput stvaranja ili uređivanja događaja.  Događaj može da sadrži i niz imena svojstava i da li su se izmenili ili nisu. Na primer, „title_changed“, „online_meeting_changed“ i „description_changed“ su imena svojstava koja su uključena kako bi nam pomogla da shvatimo da li postoje problemi sa uređivanjem određenih svojstava.

Prikupljaju se sledeća polja: 

- **account_sfb_enabled** - pomaže nam da se uverimo da je Skype za posao ispravno konfigurisan. 

- **action** - tip radnje koja je izvršena u kalendaru. Ovo obuhvata stvari kao što su otvaranje, uređivanje, dodavanje prečice, odlaganje itd. Pomaže nam da osiguramo da naše iskustvo kalendara funkcioniše kao što je očekivano i da ništa nije prekinuto 

- **action_result** - rezultat radnje koju ste napravili u komponentama kalendara. To može da obuhvata vrednosti kao što su uspeh, neuspeh, nepoznato i istek vremena. Koristi se za praćenje stope uspešnosti radnji i utvrđivanje da li postoji širok problem sa radnjama kalendara. 

- **attendee_busy_status** - status obaveštenja o zauzetosti učesnika sa kojim je radnja povezana. Ova vrednost može da bude slobodan, zauzet ili uslovno. Pomaže nam da shvatimo da li postoji problem sa radnjama u vezi sa određenim zauzetim statusom. 

- **availability** - vrednost dostupnost ako se vrednost zauzetosti na sastanku promeni. Pomaže nam da shvatimo da li postoje problemi sa podešavanjem određene vrednosti dostupnosti. 

- **calendar_onlinemeeting_default_provider** – sadrži podrazumevanog dobavljača za sastanak na mreži za korišćenje sa kreiranjem servera podržane na mreži. To obuhvata tipove Skype, Skype za posao, Hangout i Teams za posao. Pomaže nam da ustanovimo potencijalne probleme sa kreiranjem sastanaka na mreži za određene dobavljače. 

- **calendar_onlinemeeting_enabled** - tačno ako kalendar podržava kreiranje sastanka na mreži koji podržava server, zasnovano na podrazumevanom dobavljaču usluga na mreži za sastanke. Pomaže nam da shvatimo da li postoje problemi sa kalendarima omogućenim za sastanak na mreži. 

- **calendar_type** - tip kalendara koji se dešava tokom događaja nakon što je korisnik uredio sastanak. Moguće vrednosti obuhvataju primarno, sekundarno, deljeno i grupu. Pomaže nam da shvatimo da li postoje problemi sa određenim tipom kalendara. 

- **delete_action_origin** - poreklo izvršene akcije brisanja. Ovo obuhvata vrednosti kao što su traka sa alatkama za navigaciju i traka sa alatkama.  Pomaže nam da shvatimo da li postoje problemi sa brisanjem sastanka sa određene lokacije. 

- **distribution_list_count** – broj učesnika koji su na spiskovima distribucije. Pomaže nam da pratimo da li postoje problemi sa učesnicima koji su na spiskovima distribucije. 

- **guest_count** - broj gostiju na sastanku.  Pomaže nam da budemo sigurni da se gosti ispravno dodaju. 

- **is_all_day** – koristi kao „meeting_duration“ da biste naveli da li je ovo celodnevni sastanak. Pomaže nam da shvatimo da li postoje problemi sa radnjama koji se izvode na celodnevnim sastancima. 

- **is_every_meeting_online_on** – Tačno ako je korisnički nalog podešen tako da podrazumevano ima sastanke na mreži. Pomaže nam da shvatimo da li postoje problemi sa kalendarima omogućenim za sastanak na mreži. 

- **is_location_permission_granted** – da li je korisnik dodelio dozvolu aplikaciji za sistemsku lokaciju. Ako je dozvoljen pristup lokaciji, aplikacija može da prikaže dodatne uslužne informacije u korisničkom interfejsu. Ako znamo da je dozvola lokacije dodeljena, moći ćemo da znamo koliko se često dodatne uslužne informacije prikazuju korisnicima.

- **is_organizer** - pomaže nam da shvatimo da li organizator može ispravno da uređuje i kreira sastanke. 

- **is_recurring** - pomaže nam da shvatimo da li postoji problem koji posebno utiče na periodične sastanke. 

- **launch_point** - tačka lansiranja radnje. Mogu da budu vrednosti kao što su vidžet zaglavlje, vidžet podnožje, vidžet ceo dan i prečica za kalendar. Pomaže nam da shvatimo kontekst sa kojeg je radnja pokrenuta. 

- **location_count** - broj mesta koji su podešeni na kreiranju i uređivanju događaja. Pomaže nam da shvatimo da li postoje problemi sa kreiranjem ili uređivanjem događaja sa određenim brojem lokacija. 

- **location_selection_source_type** - tip izvora za izbor lokacije. To može da obuhvati vrednosti kao što su sugestija lokacije, prilagođeno i postojeće. Pomaže nam da ustanovimo da li postoje problemi sa biranjem lokacije od određenog izvora. 

- **location_session_id** - ID sesije za izbor lokacije za sastanke. Pomaže nam da ustanovimo bilo kakve probleme pomoću izbora lokacije za dodavanje na sastanak. 

- **location_type** - izabrani tip lokacije.  Sadrži tipove kao što su prilagođena lokacija, sala za konferencije i Bing. Pomaže nam da shvatimo probleme prilikom dodavanja određenih tipova lokacija sastanku. 

- **meeting_duration** - dužina sastanka.  Pomaže nam da se uverimo da se sastanci konfigurišu sa ispravnim vremenima. 

- **meeting_insights_type** - tip uvida sastanka u detalje o događaju.  Ovo uključuje datoteku i poruku. Pomaže nam da shvatimo broj uvida sastanaka koji se prikazuju. 

- **meeting_type** - tip sastanka na mreži povezan sa akcijom.  To obuhvata tipove Skype, Skype za posao, Hangout i Teams za posao. Pomaže nam da shvatimo da li su sastanci na mreži ispravno konfigurisani. 

- **online_meeting_provider_switch_type** - Tip prebacivanja koje je izvršio korisnik između organizatora sastanaka na mreži. Pomaže nam da razumemo angažovanje korisnika sa funkcijom.

- **origin** - poreklo akcije u kalendaru. Ovo obuhvata tipove kao što su dnevni red, kalendar, vidžet rasporeda itd. Pomaže nam da bolje osiguramo da interakcija unutar komponenti kalendara ispravno funkcioniše 

- **recurrence_scope** - tip ponavljanja za sastanak, bilo koja pojava ili grupa.  Pomaže nam da shvatimo da li postoje problemi sa uređivanjem različitih tipova obrazaca ponavljanja sastanaka. 

- **reminder_time** - vreme podsetnika sastanka ako se promenio.  Koristi se da biste se uverili da je vreme sastanka podsetnika ispravno sačuvano. 

- **reminders_count** - broj podsetnika na događaju ako su se podsetnici promenili. Pomaže nam da ustanovimo da li postoje problemi sa više podsetnika na događaju. 

- **sensitivity** - osetljivost sastanka. Ovo obuhvata tipove normalnih, ličnih, privatnih i poverljivih. Pomaže nam da shvatimo da li je osetljivost sastanka ispravno konfigurisana. 

- **session_duration** - dužina trajanja sesije u milisekundama. Pomaže nam da shvatimo da li postoje problemi koji povećavaju količinu potrebnog vremena za izvođene radnje "Kalendar". 

- **shared_calendar_result** - rezultat radnje izvršene u deljenoj fascikli. Moguće vrednosti obuhvataju u redu, ne dozvoljavate, nepoznato, vlasnik lokalno i vlasnik je grupa. Pomaže nam da shvatimo pouzdanost radnji izvršenih u deljenim kalendarima. 

- **time_picker_origin** - poreklo vremena čuvanja za akciju čuvanja. Obuhvata vrednosti kao što su više opcija i manje opcija. Pomaže nam da shvatimo na koji način je korisnik otišao u tok da sačuva sastanak i osigura ispravno funkcionisanje 

- **title** - automatski predloženi naslov iz vrednosti koje definišu određene aplikacije. Ovo obuhvata vrednosti kao što su „Pozovi“, „Ručak“ i „Skype“. Pomaže nam da shvatimo da li je automatska sugestija naslova ispravno konfigurisana. 

- **txp** - tip rezervacije ili rezervacija na događaju, ako ih ima. Ovo obuhvata tipove kao što su rezervacije događaja, rezervacije leta, rezervacije iznajmljivanja kola itd. Pomaže nam da shvatimo da li kartice za rezervacije rade ispravno. 

- **upcoming_event_count** - broj predstojećih događaja prikazanih u prikazu predstojećih događaja. Pomaže nam da shvatimo da li postoje problemi sa predstojećim prikazom događaja. 

- **upcoming_event_seconds_until_event** - broj sekundi do početka sledećeg događaja. Pomaže nam da shvatimo tipične događaje koji su prikazani u prikazu predstojećih događaja. 

- **value** - detalji koji se odnose samo za radnje, kao što su dužina odlaganja ili ponavljanje-do kategorije. Pomaže nam da shvatimo kontekst koji je izvršen tokom radnje. 

#### <a name="combinedsearchuse"></a>combined.search.use

Koristi se za nadgledanje mogućeg negativnog uticaja na vašu sposobnost da obavljate ključne funkcije pretraživanja, kao što su pretraživanje pošte, kontakata ili događaja.

Sledeća polja se prikupljaju za iOS i Android: 

- **account_switcher_action_type** - ovaj tip radnje prati ako je korisnik koristio program za promenu naloga bilo u jednostavnom otkrivanju ili ako je odlučio da promeni nalog

- **action** - tip radnje koja je izvršena za pretragu. Ovo prepoznaje da li je pokrenuta pretraga, da li je nastala ili završena, kao i koje su se radnje događale tokom pretrage, tj. bio je mikrofon korišćen. Ovo je instrument za obezbeđivanje ispravnih i korisnih pretraga.

- **action_type** - tip radnje koja je izvršena za pretragu. Ovo prepoznaje da li je pokrenuta pretraga, da li je nastala ili završena, kao i koje su se radnje događale tokom pretrage, tj. bio je mikrofon korišćen. Ovo je instrument za obezbeđivanje ispravnih i korisnih pretraga. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]* 

- **conversation_id** – jedinstveni ID za svaku sesiju pretraživanja (tj. svaki put kada korisnik otvori okvir za pretraživanje)

- **entrance_type** - ovo utvrđuje na koji način je korisnik pokrenuo upit za pretragu, sa kartice pretraga, nuli upita, zaglavlju pretrage ili rezultatu pretrage. 

- **has_contact_results** – jednostavno bilo da su prikazani rezultati kontakta ili ne u upitu pretrage

- **include_deleted** - da li pretraga prikazuje izbrisane opcije u rezultatima pretrage 

- **is_best_match_suggestion** – da li izabrani predlog za pretragu najbolje odgovara.

- **is_ics_external_data** – snima da li je dodati događaj unutrašnji (tj. dodat u Outlook u kalendar programa Outlook) ili spoljni (tj. dodat iz neke druge aplikacije za e-poštu, kao što je Gmail u kalendar programa Outlook).

- **is_network_fully_connected** – ovo služi da dobijete nagoveštaj o razlogu za pretragu van mreže. Ako je mreža povezana i pretraga je van mreže, razlog je verovatno vremensko ograničenje servera

- **is_offline_search** – da li je sesija pretrage bila pretraga van mreže na osnovu rezultata pretrage koje je vratio hx

- **re_enter_search_tab** - Boolean da naznači da li je korisnik zamenio kartice pre nego što je odabrao rezultat pretraživanja

- **result_selected_type** – tip podataka koji su prikazani je uključen u interakciju sa programom itd. pogledajte članak razgovori o kontaktu, razgovorima, događaju itd. 

- **search_conversation_result_data** - ovo sadrži podatke o razgovoru izabranom u rezultatima pretrage uključujući tip naloga (hx, ac itd.), bez obzira da li se poruka zadržava pomoću usluge u oblaku, kao i da li je prikaz pomaka stranice ista stranica kao i prva poruka. 

- **search_origin** – odakle je došla pretraga, tj. pomoćnik za glasovne pomoćnika, Cortana, unos tastature itd. 

- **search_scope** – niska koja ukazuje na tip naloga koji je korisnik tražio (npr. Exchange, gmail itd.) ili ako je to bilo na svim nalozima. 

- **search_suggestion_type** – pokazuje šta se nalazi iza predloga pretrage, tj. da li je ispravka pravopisa? Na osnovu istorije? Automatsko dovršavanje?

- **search_request_reason** – označava razlog za slanje zahteva za pretragu iz aplikacije, što znači da ukazuje na akciju komponente ili korisnika koja je pokrenula pretragu.

- **search_result_filter_type** - označava koji tip filtera je primenjen za pretraživanje, samo prikaz svih ili priloga

Sledeća polja se prikupljaju za iOS aplikacije programa Outlook Mobile: 

- **answer_result_selected_count** – prati koliko puta je pretraživanje bilo „uspešno“ tj. da li je korisnik pronašao osobu koju je želeo? Napisali ste e-poruku? Obeležili ste poruku obeleživačem? 

- **contact_result_in_full_list_selected_count**–prati koliko puta je korisnik tražio da „Vidi sve kontakte“ na celoj listi izabranoj tokom kombinovanih sesija pretrage

- **contact_result_selected_count** - prati koliko je bilo izbora izabranih kontakata tokom kombinovane sesije pretrage

- **conversation_result_selected_count** - prati koliko razgovora je bilo izabrano tokom kombinovane sesije pretrage

- **mail_paging_gesture_count** – prati koliko je gesti listanja stranica za pretraživanje pošte izvršeno unutar kombinovane sesije pretraživanja

- **mail_requests_count** – prati koliko je zahteva za pretragu pošte poslato u okviru kombinovane sesije pretrage

- **people_filter_selected_contacts_count** – prati koliko kontakata je izabrano u filteru za osobe

- **search_session_ended_type** - označava gde je pretraga završena zato što je otkazana ili je upit ažuriran

- **search_suggestion_type** – pokazuje šta se nalazi iza predloga pretrage, tj. da li je ispravka pravopisa? Na osnovu istorije? Automatsko dovršavanje?

- **see_all_contacts_selected_count** – prati koliko je puta izabrano „pogledaj sve kontakte“ tokom kombinovane sesije pretrage

- **subtab_type** –  prati sa koje kartice sa rezultatima je korisnik izabrao rezultat

- **top_mail_result_selected_count** - prati koliko puta korisnik izabere najbolje rezultate koji im je pružen.

- **ui_reload_result_count** – snima vremena ponovnog učitavanja korisničkog interfejsa zbog ažuriranja skupa rezultata (tokom izvršavanja odgovarajućeg upita)

- **ui_reload_result_time** – snima ukupno vreme utrošeno na ponovno učitavanje korisničkog interfejsa zbog ažuriranja skupa rezultata (tokom izvršavanja odgovarajućeg upita)

- **ui_reload_status_count** – snima vremena ponovnog učitavanja korisničkog interfejsa zbog ažuriranja statusa (tokom izvršavanja odgovarajućeg upita)

- **ui_reload_status_time** – snima ukupno vreme utrošeno na ponovno učitavanje korisničkog interfejsa zbog ažuriranja statusa (tokom izvršavanja odgovarajućeg upita)

#### <a name="composemailaccessory"></a>compose.mail.accessory

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme sa ključnim radnjama za pisanje e-pošte kako bi vas sprečilo da nailazite na probleme sa prilaganjem datoteke, slikate kao prilog ili šaljete dostupnost.

Prikupljaju se sledeća polja: 

- **action** - govori nam šta je bilo pokušano kada se evidentira radnja. Neki primeri uključuju prilaganje datoteke i predstavljanje više opcija.

- **icon_name** - govori nam ime ikone koja se prikazuje kada se evidentira radnja.
 
- **origin** – Pokazuje nam poreklo radnje. Moguće vrednosti su quick_reply i full_screen.

- **toolbar_type** – Pokazuje nam tip trake sa alatkama koji se nalazi na stranici za sastavljanje. Moguće vrednosti su compose_actions i formatting.


#### <a name="conversationviewaction"></a>conversation.view.action

Koristi se za monitoring mogućeg negativnog uticaja na mogućnost prikazivanja i odgovaranje na e-poruke

Prikupljaju se sledeća polja:

- **contains_mention** - saopštava nam da li je konverzacija za @ pominjanje primenjena kako bi nam pomogao da otkrijemo probleme sa pomenutim porukama

- **conversation_type** - govori nam koji tip prikaza e-poruke je vizuelizovana, kao što su jedan prikaz poruke ili više prikaza poruke. Pomaže nam da otkrijemo probleme u vezi sa određenim tipom poruke u našem prikazu za razgovor kroz e-poštu.

- **hx_error_type** – govori nam koja greška je zabranila usluzi da izvrši uklanjanje, ažuriranje ili dodavanje reakcije na poruku.

- **hx_string_tag** – govori nam oznaku greške u bazi koda usluge

- **is_pinned** – Govori nam da li je razgovor zakačen. Ovo služi za procenu da li korisnici komuniciraju sa kačenjem poruka i da li se funkcija kačenja ponaša kako se očekuje.

- **reaction_origin** – saopštava koji je izvor iz kog je korisnik reagovao 

- **reaction_type** – saopštava tip reakcije korisnika

- **suggested_reply_char_count** - govori nam koliko znakova predlažemo predloge koji pružamo (ako je dostupno) da nam pomognu da otkrijemo anomalije i probleme u vezi sa našim predlozima

- **suggested_reply_click_pos** - saopštava nam na koji položaj predloženi odgovor (ako je dostupno) se prikazuje tako da možete da otkrijete probleme sa određenim predlozima

- **suggested_reply_type** – Ukazuje na tip predloženog odgovora za ovu radnju. Moguće vrednosti su text, send_avail i create_meeting.

- **use_default_quick_reply_mode** - govori nam ako je podrazumevani režim za brze odgovore korišćen da bi nam pomogao da otkrijemo probleme u vezi sa iskustvom za brze odgovore za e-poštu

#### <a name="draftaction"></a>draft.action

Koristi se za monitoring mogućeg negativnog uticaja na mogućnost pravljenja i čuvanja radnih verzija pošte.

Prikupljaju se sledeća polja: 

- **action** – tip radnje, npr. sačuvaj, odbaci.
 
- **draft_message_id** - ID poruke za radnu verziju

- **is_groups** - da li se radna verzija šalje u/iz fascikle grupa
 
- **origin** – gde je pokrenuta radna verzija, npr. detalj poruke, pisanje.

- **smart_compose_model_version** – prati koja se verzija modela pametnog sastavljanja koristi

- **suggestions_requested** – pokazuje koliko se predloga pametnog sastavljanja traži

- **suggestions_results** – rezultati predloga pametnog sastavljanja, tj. prihvaćeno, odbijeno

- **suggestions_returned** – pokazuje koliko je predloga pametnog sastavljanja vraćeno sa servera

- **suggestions_shown** – pokazuje koliko se predloga pametnog sastavljanja prikazuje korisniku
 
- **thread_id** - ID za radnu verziju razgovora povezuje se sa

#### <a name="draganddrop"></a>drag.and.drop

Ovaj događaj nam omogućava da otkrijemo da li je radnja prevlačenja i otpuštanja bila uspešna ili ne.  On se koristi da bismo se uverili da iskustva prevlačenja i otpuštanja ispravno rade u svim aplikacijama kao događaj otpuštanja u Outlook i kao događaj prevlačenja koji napušta Outlook.  Sa ovim podacima možemo da osiguramo da kompletno iskustvo sa drugim aplikacijama radi na očekivani način.

Prikupljaju se sledeća polja: 

- **action** – Radnja će biti prevlačenje ili otpuštanje

- **location** – U slučaju radnje prevlačenja, ovo će nas obavestiti sa koje lokacije je korisnik započeo prevlačenje.  U slučaju radnje otpuštanja, to će nam dati do znanja gde je korisnik otpustio datoteku koja je prevučena. 

- **source** – U slučaju radnje otpuštanja, ovo će nas obavestiti sa koje lokacije je korisnik započeo prevlačenje. To nam pomaže da lakše otkrijemo probleme sa određenim izvorima poput OneDrive ili datotekama u određenoj lokaciji za otpuštanje, poput nove e-poruke.

#### <a name="drawerevent"></a>drawer.event

Koristi se za monitoring mogućeg negativnog uticaja na mogućnost pristupa fasciklama u prijemnom poštanskom sandučetu

Prikupljaju se sledeća polja:

- **add_calendar_option** – ukazuje na tip kalendara koji se dodaje iz fioke ili interesantnog kalendara, kalendar pošte, deljeni kalendar, da bi nam pomogao da otkrijemo probleme u vezi sa određenim tipovima kalendara

- **calendar_accounts_count** - ukazuje na broj naloga kalendara koji nam pomažu da ustanovljene probleme u vezi sa brojem naloga koje imate

- **calendar_apps_count** – označava broj aplikacija kalendara koji se nalaze na uređaju korisnika da bi nam pomogao da otkrijemo probleme u vezi sa kalendar aplikacijama

- **drawer_type** - ukazuje na tip fioke: kalendar, pošta ili 0 upit koji će nam pomoći da otkrijemo probleme u vezi sa tipom fioke

- **from_favorites** - označava da li je radnja uzeta iz omiljenih lokacija kako bi nam pomogao da otkrijemo probleme u vezi sa omiljenim lokacijama

- **group_calendar_count** – označava broj kalendara za nalog koji će nam pomoći da otkrijemo probleme vezane sa grupom kalendara

- **inbox_unread_count** – označava broj nepročitanih poruka u prijemnom poštanskom sandučetu da bi nam pomogao da ustanovljene probleme sa prikazivanjem obaveštenja o nepročitanom sandučetu.

- **interesting_calendar_accounts_count** – ukazuje na broj naloga koji ispunjavaju uslove za zanimljive kalendari na uređaju kako bi nam pomogli da otkrijemo probleme koji se tiču zanimljivih kalendara

- **is_group_calendar** – označava da li je kalendar grupni kalendar koji će nam pomoći u otkrivanju problema povezanih grupnih kalendara

- **mail_folder_type** – ukazuje na tip fascikle "Pošta", "Prijemno poštansko sanduče", "radne verzije" itd. da biste nam pomogli da otkrijemo probleme u vezi sa tipovima fascikli.

- **mail_accounts_count** – označava broj naloga za poštu koji će nam pomoći u otkrivanju problema povezanih računa pošte.

- **selected_group_calendar_count** – označava broj grupnih kalendara koji su odabrani i aktivni u korisničkom interfejsu

- **visibility_toggle** - označava da li je korisnik uključio ili isključio dati kalendara kako bi nam pomogao da ustanovimo probleme u vezi sa prikazivanjem ili sakrivanjem kalendara

#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcCreateRepublishingLicense API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgetlicenseproperty"></a>IpcGetLicenseProperty

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetLicenseProperty API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.LicensePropertyType** - tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgetserializedlicenseproperty"></a>IpcGetSerializedLicenseProperty

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetSerializedLicenseProperty API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** – Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.LicensePropertyType** - Tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

#### <a name="ipcgettemplateissuerlist"></a>IpcGetTemplateIssuerList

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetTemplateIssuerList API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

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

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga
 
- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **UserInfo.UserObjectId** – Id korisničkog objekta

#### <a name="ipcgettemplatelist"></a>IpcGetTemplateList

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcGetTemplateList API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

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

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga
 
- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **UserInfo.UserObjectId** – Id korisničkog objekta

#### <a name="ipcpcreatelicensefromscratch"></a>IpcpCreateLicenseFromScratch

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpCreateLicenseFromScratch API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** – Id korisničkog objekta 

#### <a name="ipcpcreatelicensefromtemplate"></a>IpcpCreateLicenseFromTemplate

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpCreateLicenseFromTemplate API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

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

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

#### <a name="ipcpgettemplatelistforuser"></a>IpcpGetTemplateListForUser

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpGetTemplateListForUser API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije o URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - Označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 
    
- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** – Id korisničkog objekta 

#### <a name="ipcpserializelicense"></a>IpcpSerializeLicense

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpSerializeLicense API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.ContentId** – Id sadržaja dokumenta

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.KeyHandle** - Memorijska adresa pokazivača ključa

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.PL.KeyType** – Vrednosti „Jedan“ ili „Dupli“. Ukazuje na to da li je PL zaštićen pomoću zaštite jednim ključem ili zaštite duplim ključem.

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** – Id korisničkog objekta 

#### <a name="ipcsetlicenseproperty"></a>IpcSetLicenseProperty

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcSetLicenseProperty API poziva. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva 

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.LicensePropertyType** - tip svojstva licence

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** – Id scenarija definisan API–jem


#### <a name="linkclickedaction"></a>link.clicked.action

Događaj se koristi za praćenje uspeha korisnika u prikazu URL adrese u Edge veb prikazu i ispunjavanju standardnih veb scenarija u tom veb prikazu bez grešaka

Prikupljaju se sledeća polja:

- **account_type** – ako je Edge veb prikaz pokrenut iz e-poruke ili događaja u sistemu Outlook, tip naloga odakle je URL potekao

- **action** – radnja koju obavlja korisnik u sistemu Outlook od trenutka kada dodire URL do trenutka kada izađe iz tog toka (otvaranje veze u Edge veb prikazu, stranica ne može da se učita u veb prikazu, obavljanje pretrage u veb prikazu, izlazak iz Edge veb prikaza radi otvaranja veze u aplikaciji veb pregledača itd.)

- **duration** – trajanje korisničke sesije

- **launch_type** – ako je pokrenut Edge veb prikaz, bilo iz sistema Outlook, bilo iz vidžeta ili komponente OS

- **origin** – ako je korisnik obavio radnju u Edge veb prikazu, poreklo te radnje

- **referrer** – lokacija URL adrese koju je korisnik dodirnuo (e-poruka, događaj iz kalendara, TXP karta itd.)

- **search_scope** – ako je korisnik obavio pretragu u Edge veb prikazu, opseg te pretrage (sve, slike, video itd.)

- **search_subtype** – ako je korisnik obavio pretragu u Edge veb prikazu, da li je to bila početna pretraga ili sužena

- **session_summary_page_loaded_count** – broj strana koje korisnik učita tokom sesije u Edge veb prikazu

- **session_summary_search_count** – broj Bing pretraga koje korisnik obavi tokom sesije u Edge veb prikazu

- **session_summary_session_id** – identifikator za trenutnu korisničku sesiju u Edge veb prikazu

- **txp** – ako je Edge veb prikaz pokrenut iz TXP karte, tip događaja te kartice (večera, let itd.)

- **txp_component** – ako je Edge veb prikaz pokrenut iz TXP karte, tip komponente korisničkog interfejsa te karte


#### <a name="mailaction"></a>mail.action

Koristi se za nadgledanje mogućeg negativnog uticaja na mogućnost izvršavanja kritičnih radnji pošte (kao što je pokretanje lančanog režima rada pošte, obezbeđivanje trijažne radnje pošte) kako bi se osiguralo da aplikacija radi ispravo za poštu.

Prikupljaju se sledeća polja:

- **account** – nalog koji je obavio radnju *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **action** – prati koji tip radnje je preduzeo, tj. arhiviranje, izbriši, označi kao pročitano itd. 

- **attachment_content_type** - tip sadržaja preuzetog priloga 

- **attachment_content_type_with_count** - prati broj priloga u e-poruci

- **attachment_download_result** – rezultat (npr. uspeh/neuspeh) za akciju preuzimanja priloga

- **attachment_download_time** - vreme radnje preuzimanja priloga

- **attachment_extn** – produžetak datoteke preuzetog priloga *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali se i dalje može pojaviti u starijim verzijama.]*

- **attachment_id** - identifikator sistema za preuzet prilog 

- **attachment_size** - veličina preuzetog priloga

- **domain** - domen dokumenta koji se otvara

- **duration** – prati koliko dugo je trajala radnja u vidu engleski String (npr. 1s, 4č)

- **error** - poruka o grešci koja se odnosi na akciju 

- **event_mode** - kakav tip režima događaja je bio u programu, grupi ili drugima. 

- **Extension**– četiri znaka nastavka datoteke veze ili priloga povezanog sa ovom radnjom  *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali se i dalje može pojaviti u starijim verzijama.]*

- **internet_message_id** - ID poruke praćenja

- **is_group_escalation** - označava da li je poruka, prema kojoj je preduzeta radnja, poslata u poštansko sanduče korisnika zbog eskalacije (pretplaćenog na grupu)

- **is_pinned** – Govori nam da li je razgovor zakačen. Ovo služi za procenu da li korisnici komuniciraju sa kačenjem poruka i da li se funkcija kačenja ponaša kako se očekuje.

- **is_rule** - označava da li je izvšena radnja pošte vraćena u fokusiranu/drugu klasifikaciju 

- **is_threaded_mode** – označava da li je poruka bila u nitnom režimu ili ne, tj. kako su poruke grupisane

- **is_unread** - označava da li je poruka nepročitana da je akcija preduzeta

- **left_swipe_setting** - ukazuje na to koja je radnja bila podešena da bude prevlačenje ulevo

- **message_id** – ID poruke serveru koji je usmeren na akciju ili je razdvojena zarezima ako je u pitanju radnja veća od jedne stavke.

- **message_type** – označava na kojem tipu poruke je napravljena radnja – grupnoj ili drugoj

- **number_selected** – broj stavki koje je korisnik izabrao na listi poruka i preduzeo radnje tokom režima višestrukog izbora.

- **origin** – izvor radnje, npr. prevlačenje ćelija, 0–upit, duboka veza, prikaz e–pošte, lista e–pošte itd.

- **origin_view** – izvor prikaza radnje, npr., razgovor, poruka itd.

- **reported_to_msft** - kada šaljete e-poruku u neželjenu (bezvrednu poštu) ili kantu za smeće (phishing), oni mogu da odaberu da prijave njihovu akciju korporaciji Microsoft.

- **retry** - da li je radnja ponovo pokušana

- **right_swipe_setting** - ukazuje na to koja je radnja bila podešena da bude prevlačenje udesno 

- **shortcut** – označava da li je prečica korišćena i koja prečica je korišćena za planiranje poruke npr. kasnije, sutra, izbor vremena itd.

- **size** – veličine veze ili priloga povezan sa ovom akcijom

- **source_folder** – prati tip izvorne fascikle kada radnja pokazuje prelazak iz jedne fascikle u drugu, tj. u prijemno sanduče, smeće itd. 

- **source_inbox** – označava u kom prijemnom poštanskom sandučetu se odvija radnja pošte (npr. fokusirano, drugo itd.) stanje – stanje radnje, tj. uspeh ili tačka neuspeha

- **source_inbox** – stanje akcije, tj. uspeh ili tačka neuspeha

- **target_folder** – označava odredišni tip fascikle prilikom premeštanja e–pošte iz jedne fascikle u drugu

- **thread_id** – ID razgovora usmerenog na akciju ili listu razdvojenu zarezima ako je više od jedne stavke ciljano

- **time_taken_to_fetch_access_token** -potrebno vreme da se dobavi sistemski token pristupa koji se koristi za otvaranje veze

- **time_taken_to_fetch_drive_item** - vreme potrebno za hvatanje resursa OneDrive kada se klikne

- **time_taken_to_fetch_embed_viewer_resource** - vreme potrebno za inicijalizaciju ugrađenog preglednika prilikom otvaranja veza

- **time_taken_to_load_embed_viewer** - vreme snimljeno za pokretanje ugrađenog preglednika pri otvaranju veza

- **time_taken_to_load_link** - vreme za dovršavanje radnje učitavanja

- **time_taken_to_tap_attachment** – vreme između otvaranja poruke i klika na prilog

- **time_taken_to_tap_link** - vreme koje je korisnik uzeo između prikaza poruke i klika na vezu

- **txp** – označava da li postoji txp tip artikla koji se povezuje sa poštom na koju je radnja snimljena, npr. rezervacija događaja, rezervacija leta itd. 

- **type** - tip dokumenta koji se otvara preko veze

#### <a name="mailcompose"></a>mail.compose

Koristi se za monitoring mogućeg negativnog uticaja na vaše mogućnosti za pisanje i odgovaranje na e-poruke kao što je "pokretanje" u problemima i odgovaranje na njih, formatiranje e-poruke ili slanje e-poruka.

Prikupljaju se sledeća polja: 

- **draft_message_id** – radna verzija razgovora koji se kreira kao radna verzija kako bi nam pomogao da otkrijemo probleme u vezi sa nacrtima e–pošte

- **from_context_menu** – Govori nam da li sastavljanje potiče iz radnji kontekstualnog menija.

- **message_id** – ID poruke razgovora na koju je odgovoreno ili prosleđeno iz programa kako bi nam pomoglo da otkrijemo probleme u vezi sa određenom porukom

- **origin** - govori nam gde je nastala nova poruka, kao što je odgovori svima, nova poruka ili brzi odgovor. Pomaže nam da otkrijemo probleme koji su povezati sa određenim izvornim tipom odgovora.

- **is_group_escalation** - bez obzira na to da li je poruka eskalirana grupna poruka, možemo da otkrijemo probleme povezane sa sastavljanjem grupe.

- **is_link** - saopštava nam da li je nova radna verzija napravljena od veze. Pomaže nam da otkrijemo probleme povezane sa radnim verzijama koje se kreiraju.

- **is_force_touch** – saopštava nam da li je nova radna verzija napravljena od radnje dodirom na silu. Pomaže nam da otkrijemo probleme povezane sa radnim verzijama koje se kreiraju iz određenih radnji.

- **is_groups** - da li je događaj pokrenut iz prostora grupa tako da možemo da otkrijemo probleme prilikom sastavljanja stavki u vezi sa grupama.

- **source_inbox** - saopštava da li je izvorno poštansko sanduče bilo fokusirano ili drugo prijemno sanduče 

- **thread_id** – ID nit razgovora na koju je odgovoreno ili prosleđeno iz programa kako bi nam pomoglo da otkrijemo probleme u vezi sa određenom niti

#### <a name="meetingcalltoaction"></a>meeting.call.to.action

Koristi se za monitoring mogućeg negativnog uticaja na mogućnost izvršavanja koraka za kritične sastanke kao što je pravljenje, uređivanje i odgovaranje na sastanke.

Prikupljaju se sledeća polja:

- **event_mode** - ukazuje na to da li je ovaj događaj bio iz grupe ili nije, da bi nam pomogao da otkrijemo probleme sa grupom događaja

- **meeting_id** - ID sastanka koji nam pomaže da pratimo probleme tokom životnog veka sastanka da bismo otkrili probleme sa određenim sastancima

- **meeting_provider** – pokazuje snabdevača za sastanak na mreži, npr. timovi, Skype za posao da biste nam pomogli da otkrijemo probleme sa određenim dobavljačima sastanaka na mreži

- **notify_type** – ukazuje na tip odgovora za druge tipove naloga koji nam pomažu da otkrijemo probleme sa drugim tipovima naloga

- **recurrence** – pokazuje koliko često ovaj sastanak nastaje npr. ponavljanje ili serije kako bi nam pomogao da ustanovite probleme sa grupom sastanaka koji se ponavljaju

- **response** - ukazuje na tip odgovora kao što su prihvatanje ili odbijanje određenih tipova naloga kako bi nam pomogao da otkrijemo probleme pri odgovoru na događaje

- **response_message_length** - pokazuje kolika je dužina poruke bila pri otkrivanju problema sa odgovorima na sastanku

- **review_time_proposal_action_type** - pokazuje novi predlog za odziv korisnika da bi nam pomogao da ustanovite probleme sa predlaganjem novog vremena

- **send_response** - označava da li je poslat odgovor da bi nam pomogao da otkrijemo probleme slanja odgovora o pozivu na sastanak

- **txp** - ukazuje na tip sastanka koji je generisan u vezi sa rezervacijama letova i isporukama kako bi nam pomogao da otkrijemo probleme sa ovim tipom sastanaka

- **with_message_enabled** – označava da li korisnik može da odgovara porukom kako bi nam pomogao da ustanovimo probleme pri odgovaranju na pozivnice za sastanke


#### <a name="multiwindowlaunch"></a>multi.window.launch

Ovaj događaj beleži kada korisnik preduzima radnju koja podrazumeva pokretanje više prozora na uređajima koji se mogu preklopiti, npr. sastavljanje pošte, događaja, otvaranje prozora kalendara.  Koristi tu radnju kako bi je zapamtio, npr. kako bi se dobio odziv ili uvek pokretao u novom prozoru.  Podaci koje ovaj događaj prikuplja koriste se za procenu mogućnosti otkrivanja, efikasnosti, kao i opštih željenih postavki korisnika kako bi se podstakao trenutni i budući razvoj funkcionalnosti povezanih sa više prozora.

Prikupljaju se sledeća polja: 

- **is_remembered** – da li je korisnik sačuvao željenu postavku da se otvara u novom prozoru sa prijavljene lokacije.

- **multi_window_origin** – lokacija u okviru aplikacije u kojoj dolazi do interakcije za pokretanje ekrana druge aplikacije u novom prozoru.


#### <a name="notificationcenter"></a>notification.center

Ovaj događaj nam omogućava da pratimo kada korisnici ulaze i izlaze iz centra za obaveštenja pored broja neviđenih obaveštenja. Ovo nam pomaže da budemo sigurni da je centar za obaveštenja u skladu sa svim ostalim klijentima. Pratimo i kada korisnik dodirne obaveštenje kako bismo mogli da utvrdimo koji je tip.

Prikupljaju se sledeća polja: 

- **radnja** - radnja koju je preduzeo korisnik (zatvoreno, otvoreno, notification_tapped)

- **otkucajte** – tip obaveštenja, od sada će uvek biti reakcija

- **unseen_count** - koliko obaveštenja u trenutnom prikazu ranije nije viđeno
 


#### <a name="officeandroiddocsuifileoperationsopendocumentmeasurements"></a>Office.Android.DocsUI.FileOperations.OpenDocumentMeasurements

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Android platforme i zapisa kada se pokrene operacija otvaranja datoteke. Događaj pomaže u održavanju otvorene operacije datoteka bezbednim, ažuriranim i da ispravno funkcionišu. Cilj prikupljanja ovih podataka jeste da se kontinuirano poboljšava performanse otvorene datoteke. 

Prikupljaju se sledeća polja:

- **Data_AppDocsOperationDuration** - vreme provedeno u podsloju tokom operacije otvaranja datoteke.

- **Data_AppDuration** - vreme provedeno u obradi aplikacije tokom operacije otvaranja datoteke. 

- **Data_AppWarmUpGain** – Podešavanje trajanja pokretanja aplikacije koje dobijamo zbog prethodnog dela aplikacije pre pokretanja.

- **Data_BootDuration** - trajanje pokretanja aplikacije u procesu otvorene datoteke.

- **Data_ClosePreviouslyOpenedMarkers** – Vrednost niske koja evidentira trajanje između nekih poziva funkcije prilikom pokretanja aplikacije, u formatu sa ID-om funkcije i trajanjem.

- **Data_ClosePreviouslyOpenedMarkers** – U nekim scenarijima otvaranja datoteka, zatvaranje prethodno otvorenog dokumenta se obavlja pre otvaranja trenutnog dokumenta. Ovaj period između nekih operacija koje se obavljaju u ovom slučaju hvata se u vrednosti niske koja je u formatu \<functionId>\<functionValue>\<functionId>\<functionValue>...

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje pisanje.

- **Data_Doc_AsyncOpenKind**- Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType**- Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** - Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** - Oznaka tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** - globalno jedinstven identifikator (GUID) koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – GUID koji jedinstveno identifikuje identitet koji se koristi za otvaranje datoteke. 

- **Data_Doc_InitializationScenario**- Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** - Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** - Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** - Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** - Niska koja označava od koje usluge potiče Web Application Open Platform Interface Protocol (WOPI) datoteka.

- **Data_ErrorId_Code** - kôd greške koji ukazuje na neuspeh u operaciji prikupljanja podataka

- **Data_ErrorId_Tag** - oznaka u kodu kako bi vam pomogla da nađete tačku neuspeha

- **Data_FileOpenFlowMarkers** – Pre nego što počne proces otvaranja datoteke, postoji neka preliminarna obrada. Vreme utrošeno za ovu preliminarnu obradu hvata se u vrednosti niske koja je u formatu \<functionId>\<functionValue>\<functionId>\<functionValue>...

- **Data_FirstPartyProviderApp** – ako se otvaranje datoteke u programu Word, Excel ili PowerPoint ili Office aplikacijama, poziva iz druge Microsoft aplikacije, onda se ime tog dobavljača aplikacije snima ovde.

- **Data_InclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva. 

- **Data_InitializationReason** – Nabrajanje koje ukazuje na način otvaranja datoteke, npr. element korisničkog interfejsa, pokretanje iz druge aplikacije, itd.

- **Data_Measurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_OfficeMobileInitReason**- prebrojavanje koje ukazuje na ulaznu tačku otvaranja datoteke. 

- **Data_RenderToInSpaceDuration** – Period između završetka prikazivanja i animacije siluete/podloge.

- **Data_SilhouetteDuration** – Trajanje prikazivanja otvorene datoteke.

- **Data_TimeSplitMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije, vremenskom oznakom početka i trajanjem. 

#### <a name="officeandroiddocsuipaywallcontrolpresigninfre"></a>Office.Android.DocsUI.PaywallControl.PreSignInFRE

*[Ovaj događaj se prethodno zvao Office. DocsUI. PaywallControl.]*
 
Ovo je ključna telemetrija upotrebe za nadogradnju u utisku pri prvom pokretanju za neprijavljene korisnike. Ovaj događaj snima metriku za prvo pokretanje prijavljivanja. Podaci će se koristiti za dobijanje uvida za prethodno prijavljivanje i razumevanje da li korisnik nastavlja sa sledećom fazom u korisničkom toku.
 
Prikupljaju se sledeća polja: 

- **EventDate** – vremenska oznaka pojavljivanja događaja  

- **FunnelPoint** – Brojač da naznači gde je korisnik u ovom toku eksperimenta. Brojač će reći da li korisnik vidi tretman i odustane ili ne.

- **Sessioid** – globalno jedinstveni identifikator za povezivanje događaja po sesiji


#### <a name="officeandroiddocsuipaywallcontrolskuchoosertoggled"></a>Office.Android.DocsUI.PaywallControl.SkuChooserToggled

Telemetrija korišćenja da biste videli koliko puta se korisnik prebacuje između različitih SK-ova pre pokušaja kupovine. Koristi se za razumevanje upotrebe birača SKU-a i optimizaciju iskustva kupovine iz aplikacije u budućim verzijama.

Prikupljaju se sledeća polja:

- **EventDate** – vremenska oznaka pojavljivanja događaja 

- **SessionID** – GUID za povezivanje događaja po sesiji


#### <a name="officeandroiddocsuipaywallcontroluserimageclicked"></a>Office.Android.DocsUI.PaywallControl.UserImageClicked 

*[Ovaj događaj se prethodno zvao Office.DocsUI.PaywallControl.UserImageClicked.]*
 
Ovaj događaj meri telemetriju kako bi utvrdio da li korisnici pokušavaju da dovrše neku radnju klikom na avatar korisnika. Ovi podaci će se koristiti za merenje broja korisnika koji stupaju u interakciju sa ikonom avatara da bi procenili potrebu za dodatnim iskustvom nakon dodira.
 
Prikupljaju se sledeća polja: 

- **EventDate** – vremenska oznake pojave događaja  

- **Sessioid** – globalno jedinstveni identifikator za povezivanje događaja po sesiji 


#### <a name="officeandroidearlytelemetryexpansionfilesavailability"></a>Office.Android.EarlyTelemetry.ExpansionFilesAvailability

Omogućavamo datoteke proširenja Android Package Kit (APK) za Office aplikaciju za mobilne uređaje. APK datoteke proširenja su dodatne datoteke resursa koje projektanti Android aplikacija mogu da objave uz svoju aplikaciju. Da biste razumeli pouzdanost datoteka proširenja, evidentiramo zastavicu koja ukazuje na to da li su datoteke proširenja dostupne ili nisu pri svakom pokretanju.

Prikupljaju se sledeća polja:

- **Data_ExpansionFilesAvailable** – Bulova zastavica koja ukazuje na to da li su APK datoteke proširenja dostupne na uređaju u vreme pokretanja aplikacije.

#### <a name="officeandroidearlytelemetryexpansionfilesdownloader"></a>Office.Android.EarlyTelemetry.ExpansionFilesDownloader

Omogućavamo datoteke proširenja Android Package Kit (APK) za Office aplikaciju za mobilne uređaje. APK datoteke proširenja su dodatne datoteke resursa koje projektanti Android aplikacija mogu da objave uz svoju aplikaciju.  Da biste razumeli pouzdanost mehanizma preuzimanja datoteka proširenja, evidentiramo zastavicu koja ukazuje na to da li uspešno možemo da preuzmemo datoteke proširenja.

Prikupljaju se sledeća polja: 

- **Data_DownloadSuccess** – Bulova zastavica koja ukazuje na to da li je preuzimanje APK datoteka proširenja uspelo svaki put kada pokušamo da ih preuzmemo tokom pokretanja aplikacije.

#### <a name="officeandroidearlytelemetrynotecreated"></a>Office.Android.EarlyTelemetry.NoteCreated

Kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji. Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteCreated radnja koju aktivira korisnik.

- **NoteLocalId** – Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeandroidearlytelemetrynoteviewed"></a>Office.Android.EarlyTelemetry.NoteViewed 

Kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da prikazuju beleške u aplikaciji. Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da prikazuju beležnice, to bi izazvalo ozbiljan incident.

Prikupljaju se sledeća polja:

- **HasImages** - Zastavica koja ukazuje na to da li prikazana beleška sadrži uskladištene slike.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteViewed radnja koju aktivira korisnik.

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeandroidintuneintunecompliancerequest"></a>Office.Android.Intune.IntuneComplianceRequest

Ovaj događaj se sakuplja za Office aplikacije pokrenute u programu android, uključujući Office Mobile, Word, Excel, PowerPoint i OneNote. Događaj ukazuje na pokušaj prijave na nalog organizacije sa licencom Intune gde je administrator organizacije konfigurisao smernice za nametanje uslovnog pristupa aplikaciji. Koristi se za razumevanje broja krajnjih korisnika koji pokušavaju da koriste aplikacije u okviru ove konfiguracije smernica, kao i da je u kombinaciji sa drugim događajem, Office.Android.Intune.IntuneComplianceStatus, da bi se osiguralo primenjivanje konfigurisane politike. 

Ne skupljaju se polja podataka.

#### <a name="officeandroidintuneintunecompliancestatus"></a>Office.Android.Intune.IntuneComplianceStatus

Ovaj događaj se sakuplja za Office aplikacije pokrenute u programu android, uključujući Office Mobile, Word, Excel, PowerPoint i OneNote. Događaj ukazuje na pokušaj prijave na nalog organizacije sa licencom Intune gde je administrator organizacije konfigurisao smernice za nametanje uslovnog pristupa aplikaciji. Ovaj događaj pokazuje status usaglašenosti aplikacije koju je korisnik potpisao i koristi se za istraživanje neuspeha. Kombinuje se sa drugim događajem, Office.Android.Intune.IntuneComplianceRequest, da bi se osiguralo da je nametnuto.
  
Prikupljaju se sledeća polja:

- **Data_ComplianceStatus** - označava status usaglašenosti aplikacije tokom prijavljivanja pomoću ispravnog ili neispravnog kôda greške.
  - -1 – Nepoznata greška
  -    0 – aplikacija je usaglašena sa smernicama organizacije
  - 1 – aplikacija nije usaglašena sa smernicama organizacije
  - 2 – Neuspeh u vezi sa uslugom
  - 3 – Neuspeh u vezi sa mrežom
  - 4 – aplikacija nije uspela da preuzme token potvrde identiteta 
  - 5 – odgovor još nije primljen iz usluge
  - 6 – treba da instalirate aplikaciju portala preduzeća

#### <a name="officeandroidodwxpssotelemetry"></a>Office.Android.ODWXPSSO.Telemetry

Ovaj događaj pomaže nam da razumemo pomoću koje druge Microsoft aplikacije u uređaju je naša aplikacija uspela nečujno da se pojedinačno prijavi, putem koje ulazne tačke itd. Pomaže i u razumevanju razloga neuspelog nečujnog pojedinačnog prijavljivanja.  Dobijamo bolji uvid o tome od koje Microsoft aplikacije na uređaju dobijamo iskustvo za pojedinačno prijavljivanje. Reagujemo na neuspehe, gde pojedinačno prijavljivanje ne funkcioniše na očekivani način.

Prikupljaju se sledeća polja:

- **AccountType** – Označava tip naloga putem kojeg je došlo do pojedinačnog prijavljivanja, kao što su lični Microsoft nalog ili poslovni nalog.

- **EntryPoint** – Označava ulaznu tačku u aplikaciji sa koje je pokrenut pokušaj pojedinačnog prijavljivanja.

- **ErrorCode** – Označava kôd greške pri pokušaju pojedinačnog prijavljivanja.

- **ErrorDescription** – Označava poruku o grešci pri pokušaju pojedinačnog prijavljivanja.

- **HResult** – Označava kod stanja rezultata pokušaja pojedinačnog prijavljivanja.

- **ProviderPackageId** - Druga Microsoft aplikacija na uređaju putem koje se odvija pojedinačno prijavljivanje.

#### <a name="officeandroidphonenumbersignins"></a>Office.Android.PhoneNumberSignIns

Ovaj događaj pomaže u razumevanju da li se korisnik prijavio pomoću naloga koji se zasniva na telefonskom broju ili pomoću ličnog Microsoft naloga koji se zasniva na e-pošti.  Ovaj događaj pomaže da saznamo broj korisnika koji se prijavljuje putem ličnog Microsoft naloga koji se zasniva na broju telefona.

Prikupljaju se sledeća polja:

- **EntryPoint** – Označava ulaznu tačku u aplikaciji sa koje je pokrenut pokušaj prijavljivanja.

- **IsEmailMissing** - Da li nedostaje adresa e-pošte u podacima o profilu naloga?

- **IsEmailMissing** - Da li nedostaje broj telefona u podacima o profilu naloga?

- **UserDecision** – Označava izbor korisnika kao što je prijavljivanje odmah ili kasnije.

#### <a name="officeandroidusersignindecision"></a>Office.Android.UserSignInDecision

Ovaj događaj pomaže u razumevanju na kom nivou dolazi do neuspelog prijavljivanja korisnika, zbog čega se to dešava, koliko korisnika se uspešno prijavljuje i sa koje ulazne tačke u aplikaciji itd.  Ovaj događaj nam pomaže da sakupimo podatke o prijavljivanju, što nam dalje pomaže da razumemo u kojoj fazi dolazi od neuspelog prijavljivanja korisnika itd.

Prikupljaju se sledeća polja:

- **AccountType** – Označava tip naloga putem kojeg je došlo do pokušaja jednokratnog prijavljivanja, kao što je lični nalog ili poslovni nalog.

- **AfterLicensingState** – Označava stanje licenciranja aplikacije nakon izvršenog prijavljivanja.

- **AllowedEditsWithoutSignIn** – Označava koliko je besplatnih izmena isteklo pre pokušaja prijave.

- **BeforeLicensingState** – Označava stanje licenciranja aplikacije pre izvršenog pokušaja prijavljivanja.

- **CompletionState** – Označava fazu završetka prijavljivanja.

- **EntryPoint** – Označava ulaznu tačku u aplikaciji sa koje je pokrenut pokušaj prijavljivanja.

- **HRDAutoAcceleratedSignUpAttemptCount** – Označava broj pokušaja ubrzanih prijavljivanja.

- **HRDAutoAcceleratedSignUpQuitCount** – Označava broj otkazanih ubrzanih prijavljivanja.

- **HResult** – Označava kod stanja rezultata operacije prijavljivanja.

- **IsPhoneOnlyAuthFeatureEnabled** - Da li je prijavljivanje na osnovu broja telefona dozvoljeno ili ne?

- **LicenseActivationHResult** - Ukazuje na kod statusa pokušaja aktivacije licence.

- **LicenseActivationMessageCode** – Označava kôd poruke iz usluge licenciranja.

- **NoFreeEditsTreatmentValue** – Da li je dozvoljeno besplatno uređivanje ili ne?

- **SignUpAttemptCount** – Označava broj pokušanih prijavljivanja.

- **StartMode** – Označava režim u kom je pokrenut pokušaj prijavljivanja.

- **UserDecision** – Označava izbor korisnika kao što je prijavljivanje odmah ili kasnije.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Prikupljaju se samo kada krajnji korisnik omogući Kontrolnu tablu Office telemetrije. Prikuplja informacije o tome kada se izvršava Office Telemetry agent.    Ovo se prikuplja samo kada je Kontrolna tabla Office telemetrije omogućena, a koristi se za određivanje ispravnost agenta Office telemetrije.

Prikupljaju se sledeća polja:

  - **Data.AgentExit** - Vremenska oznaka koja označava kada se agent telemetrije uspešno zatvori.

  - **Data.AgentExit** - Vremenska oznaka koja označava kada agent telemetrije uspešno obavi skeniranje.

  - **Data.AgentUpload** - Vremenska oznaka koja označava kada agent telemetrije uspešno završi otpremanje.

#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Generisano prilikom pokretanja klijenta kada krajnji korisnik omogući Kontrolnu tablu Office telemetrije.  Prikuplja informacije o tome kada je Office Telemetry agent učitao podatke u fasciklu „Deljenje“. Primarno korišćenje ovog događaja jeste nadgledanje zdravlja usluge Office Telemetrije, a sekundarno korišćenje događaja jeste da proceni korišćenje kontrolne table Office telemetrije.

Prikupljaju se sledeća polja:

- **UploadTime** - vremenski žig poslednjeg uspešnog otpremanja koji je obavio telemetrijski agent.


#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Prikuplja se samo kada krajni korisnik (najverovatnije administrator) omogući Kontrolnu tablu Office telemetrije.  Prikuplja pojavljivanje padova Office programskih dodataka i dokumenata.  Ovo se prikupljaju samo onda kada korisnik omogući Kontrolnu tablu Office telemetrije i koristi se za utvrđivanje da li postoji povećano pojavljivanje padova programskih dodataka ili dokumenata.

Prikupljaju se sledeća polja:

  - **Vreme prikupljanja podataka** - Vremenska oznaka koja označava kada je evidentiran događaj pada

#### <a name="officeappdocsappdocsdocumentoperation"></a>Office.AppDocs.AppDocs.DocumentOperation

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj beleži kada se izvršava operacija datoteke (kreiranje/otvaranje/spremanje/izvoz/itd) i koristi se za razumevanje i određivanje prioriteta korisničkog iskustva.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka datoteke za oznaku tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_InitializationReason** – Predstavljanje nabrajanja specifičnog razloga za operaciju. Na primer – otvoreno iz URL adrese ili lokalne putanje datoteke, kreirano pomoću birača datoteke, kopirano na putanju datoteke, izvezeno u URL, itd.

- **Data_IsDisambiguateCsiNetworkConnectivityErrorEnabled**.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_OperationType** – predstavljanje nabrajanja generičkog tipa operacije. Na primer – kreirati, otvoriti, kopirati, sačuvati, itd.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.

#### <a name="officeappleactivateperpetual"></a>Office.Apple.ActivatePerpetual

Događaj se koristi za Office aplikacije koje rade na Apple platformama. Događaj se koristi za praćenje stanja neprekidnog toka aktivacije kao i za istraživanje uzroka greški pregledom vrednosti FailedAt.

Prikupljaju se sledeća polja:

- **Data_FailedAt** - Sakupljamo nisku koja obeležava mesto gde je došlo do neuspeha pri procesu aktivacije stalne licence.

#### <a name="officeappleactivatesubscription"></a>Office.Apple.ActivateSubscription

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informacije vezane za migraciju iz zastarelog steka koda za licenciranje na vNext klin koda za licenciranje. Ovo se koristi za nadgledanje stanja aktiviranja pretplate, kao i za praćenje da li je ovo migracija na licencu vNext i da li je korišten primarni identitet.

Prikupljaju se sledeća polja:

- **Data_ActivatingPrimaryIdentity** - Vrednost true/false koja označava da li je korišten primarni identitet. 

- **Data_NULSubscriptionLicensed** - Vrednost true/false koja označava stanje pretplate

#### <a name="officeapplecisauthticketwithidentity"></a>Office.Apple.CISAuthTicketWithIdentity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za hvatanje neuspeha automatskog dodavanja tokena za potvrdu identiteta tokom kupovine unutar aplikacije na Mac računarima (događaj evidentira primljeni kôd greške).  Ovaj događaj se koristi za otkrivanje i rešavanja neuspešnog dodavanja tokena za potvrdu identiteta

Prikupljaju se sledeća polja:

- **Data_EmptyAuthToken** - Sakupljamo nisku koja obeležava mesto gde je došlo do neuspeha pri procesu aktivacije stalne licence.

- **Data_TicketAuthError** – Kôd greške koji ukazuje na uzrok neuspeha

- **Data_ValidIdentity** – Da li klijent ima važeći identitet

#### <a name="officeappleinappassociationactivity"></a>Office.Apple.InAppAssociationActivity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informacije povezane sa povezivanjem proizvoda nakon kupovine iz aplikacije. Evidentiramo koji SKU pretplate povezujemo.  Ovo se koristi za nadgledanje stanja povezanih proizvoda kupljenih iz aplikacije.

Prikupljaju se sledeća polja:

- **Data_ProductID** - SKU pretplate kojem pokušavamo da pridružimo proizvod.

#### <a name="officeappleinapppurchaseactivity"></a>Office.Apple.InAppAssociationActivity

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. 

Informacije povezane sa kupovinom proizvoda prikupljamo u usluzi AppStore. Pratimo rezultat kupovine (neuspeh, uspeh, problem sa plaćanjem itd.), tip zahteva za kupovinu (vraćanje, kupovina) i SKU/proizvod koji se kupuje (Microsoft 365 Family itd.).  Ovi podaci se koriste za nadgledanje stanja tokova kupovine iz aplikacije.


Prikupljaju se sledeća polja:

- **Data_ Data_PurchaseResult** - rezultat operacije kupovine

- **Data_ProductID** - proizvod koji se kupuje

- **Data_PurchaseRequestType** - tip zahteva za kupovinu

#### <a name="officeappleintune"></a>Office.Apple.InTune

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Prikupljamo informaciju da li trenutnu sesiju kontroliše Intune. Koristi se za izvođenje/filtriranje sesija koje kontroliše InTune i omogućava nam da istražimo potencijalne probleme vezane za to da se Office pokreće kao aplikacija koju kontroliše InTune.

Prikupljaju se sledeća polja:

- **Data_EventID** - prikupljamo nisku koja predstavlja kôd koji označava da li sesiju kontroliše Intune.

#### <a name="officeapplelicensingmaclicensingstate"></a>Office.Apple.Licensing.Mac.LicensingState

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

- **Ime_Aktivnosti** – ime aktivnosti „ConnectDevice“

- **Activity_CV** = ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** = Početak

- **Activity_DateTimeTicks** = vreme podataka za aktivnost
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Omogućava nam da znamo da li je povezivanje uređaja ili aplikacije bilo uspešno. Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Ime_Aktivnosti** – ime aktivnosti „ConnectDevice“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Zaustavljanje

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officedocsappdocsoperationopenfrommrubypath"></a>Office.Docs.AppDocs.OperationOpenFromMruByPath

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj se snima kad se izvršava operacija otvaranja datoteke sa putanje obezbeđene na poslednjoj korišćenoj listi i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.

#### <a name="officedocsappdocsoperationopenfrommrubyurl"></a>Office.Docs.AppDocs.OperationOpenFromMruByUrl

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj se snima kad se izvršava operacija otvaranja datoteke sa URL adrese obezbeđene na poslednjoj korišćenoj listi i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke. 

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.


#### <a name="officedocsappdocsoperationopenfrompath"></a>Office.Docs.AppDocs.OperationOpenFromPath

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj se snima kad se izvršava operacija otvaranja datoteke sa putanje obezbeđene na poslednjoj korišćenoj listi i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.

#### <a name="officedocsappdocsoperationopenfromprotocolhandler"></a>Office.Docs.AppDocs.OperationOpenFromProtocolHandler

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj beleži kada se operacija otvaranja datoteke odvija iz druge aplikacije koja koristi interfejs rukovaoca protokolom i koristi se za razumevanje i davanje prioriteta korisničkom iskustvu na osnovu informacija o operacijama otvorenih datoteka.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.

#### <a name="officedocsappdocsoperationopenfromshell"></a>Office.Docs.AppDocs.OperationOpenFromShell

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj beleži kada se operacija otvaranja datoteke odvija iz ljuske i koristi se za razumevanje i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvorenog fajla.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.


#### <a name="officedocsappdocsoperationopenfromurl"></a>Office.Docs.AppDocs.OperationOpenFromUrl

Ovaj događaj se prikuplja za Office aplikacije koje rade na platformama Android, iOS, Universal ili Windows. Događaj beleži kada se operacija otvaranja datoteke odvija iz URL adrese i koristi se za razumevanje i određivanje prioriteta korisničkih iskustava na osnovu informacija o operacijama otvorenih datoteka.

Prikupljaju se sledeća polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije kada nije poznat pre nego što je kraj izveštaja pozvao operaciju.

- **Data_CanContinueFromOnBeforeOperationBegins** – CanContinue stanje, pre nego što je pozvan rukovalac početkom.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind** – Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType** – Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** – Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** – Prva 4 znaka oznake tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – Jednosmerni heš za identitet korisnika koji se koristi za izvršavanje otvaranja.

- **Data_Doc_InitializationScenario** – Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** – Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** – Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** – Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_DocumentInputCurrency** – Tip unosa dokumenta koji koristi operacija.

- **Data_DocumentOperation_AppId** – Vrednost nabrajanja koja predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka koja predstavlja gde se operacija završila.

- **Data_DocumentOperation_EndReason** – Vrednost nabrajanja koja predstavlja razlog završetka.

- **Data_DocumentOperation_IsReinitialized** – Predstavlja ponovno pokretanje dokumenta koji je već otvoren.

- **Data_DocumentOperation_ParamsFlags** – Zastavice nabrajanja koje se koriste za pokretanje operacije.

- **Data_DocumentOperation_TelemetryReason** – Predstavljanje nabrajanja ulaze tačke za otvoreni događaj. Npr. otvaranje iz MRU-a ili pregledanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Predstavlja ciljni kontekst izvršavanja isti kao odakle je otvoren kontekst.

- **Data_FileIOInclusiveMeasurements**-– Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_FileIOMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_IsNameMissingInUrl** – Ukazuje na to da li ime nije rapčlanjeno iz URL adrese.

- **Data_IsPathMissingForLocalFile** – Ukazuje na to da li je ovo lokalna datoteka bez putanje.

- **Data_IsUnpackedLinkSupportedForOpen** – Ukazuje na to da li je veza koja se ne može spakovati podržana za otvaranje.

- **Data_LinksOpenRightScenario** – Vrednost nabrajanja za scenario ispravnog otvaranja veza.

- **Data_OpEndEventId** – Otnaka koja predstavlja gde se operacija završila.

- **Data_RelatedPrevOpTelemetryReason** – Predstavlja operaciju vezanu za prethodnu operaciju.

- **Data_StopwatchDuration** – Ukupno vreme za događaj.

- **Data_UnpackLinkHint** – Nabrajanje koje predstavlja potencijalnu radnju korisnika na osnovu veze za raspakivanje.

- **Data_UnpackLinkPromptResult** – Nabrajanje koje predstavlja odgovor upita veze za raspakivanje.



#### <a name="officedocsappledocsuxiossaveasthroughfilemenu"></a>Office.Docs.Apple.DocsUXiOSSaveAsThroughFileMenu 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija „Sačuvaj kao“ i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji datoteka, kao što su kategorije lokacije.  Operacija „Sačuvaj kao“ pojavljuje se svaki put kada korisnik napravi novu datoteku i prvi put je sačuva ili sačuva kopiju postojeće datoteke na novu lokaciju.

Prikupljaju se sledeća polja:

- **Data_OriginServiceType** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_ServiceType** – apstraktna kategorizacija nove lokacije datoteke nakon što se dovrši čuvanje kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="officedocsappledocsuxmacatmentioninsertedatmention"></a>Office.Docs.Apple.DocsUXMacAtMentionInsertedAtMention 

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Ovaj događaj se snima kada korisnik „@“ pominje drugog korisnika i koristi se za razumevanje i određivanje prioriteta korisničkog iskustva na osnovu načina na koji korisnici sarađuju sa drugim korisnicima.

Prikupljaju se sledeća polja:

- **Data_CharactersTyped** – numerička vrednost koja označava ukupan broj znakova otkucanih u tekstu pominjanja „@“.

#### <a name="officedocsappledocsuxmacodspsharingwebviewsharingcompleted"></a>Office.Docs.Apple.DocsUXMacODSPSharingWebViewSharingCompleted 

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Ovaj događaj se beleži kada korisnik odluči da deli dokument u oblaku koristeći iskustvo deljenja usluge OneDrive i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ShareType** – fiksno kodirana niska koja pokazuje kakva je operacija deljenja završena uključujući, ali ne ograničavajući se na „Kopiraj vezu“, „Više aplikacija“, „Teams“.

- **Data_ShareWebViewMode** – fiksno kodirana niska koja pokazuje kakav je režim deljenja bio aktivan kada je deljenje dovršeno, uključujući, ali ne ograničavajući se na „Upravljanje pristupom“, „AtMentions“, „Deljenje“.

#### <a name="officedocsuicollaborationcoauthorgalleryrowtapped"></a>Office.DocsUI.Collaboration.CoauthorGalleryRowTapped 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se beleži kada korisnik odabere da pogleda spisak trenutnih koautora.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na koautorstvo dokumenta u isto vreme.

Prikupljaju se sledeća polja:

- **Data_CoauthorCount** - numerička vrednost koja predstavlja ukupan broj osoba koji trenutno uređuju isti dokument kao i korisnik.

#### <a name="officedocsuicollaborationcollabcornerpeoplegallerycoauthorsupdated"></a>Office.DocsUI.Collaboration.CollabCornerPeopleGalleryCoauthorsUpdated 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kada se promeni broj aktivnih koautora u dokumentu u oblaku.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na koautorstvo dokumenta u isto vreme.

Prikupljaju se sledeća polja:

- **Data_CoauthorsJoined** - Broj koautora koji su se pridružili dokumentu.

- **Data_CoauthorsLeft** - Broj koautora koji su napustili dokument.

- **Data_NewCoauthorCount** - novi broj aktivnih koautora u dokumentu. 

- **Data_OldCoauthorCount** - prethodni broj aktivnih koautora pre ažuriranja.

- **Data_ ServiceType** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="officedocsuidocstagedocstagecreatenewfromtemplate"></a>Office.DocsUI.DocStage.DocStageCreateNewFromTemplate 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kada se nova datoteka kreira iz iskustva „Novo iz predloška“ i koristi se za bolje razumevanje i određivanje prioriteta korisničkog iskustva na osnovu informacija o kreiranju dokumenata.

Prikupljaju se sledeća polja:

- **Data_InHomeTab** – Bulova vrednost koja pokazuje da li je nova datoteka iz predloška kreirana na kartici „Početak“ datoteke novog iskustva.

- **Data_InSearch** - Bulova vrednost koja označava da li je datoteka kreirana kada je korisnik tražio predložak.

- **Data_IsHomeTabEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupna kartica „Početak“.

- **Data_IsRecommendedEnabled** – Bulova vrednost koja označava da li je korisniku trenutno dostupno iskustvo „Preporučeno“.

- **Data_TemplateIndex** - Numerički indeks datoteke predloška dok se vizuelno prikazuje korisniku.

- **Data_TemplateType** – Klasifikacija koja će vam pomoći da razlikujete tip predloška, uključujući, ali ne ograničavajući se na predložak „Na mreži“, predložak „Pretraži na mreži“, predloške „Lokalno“.

#### <a name="officedocsuidocstagerecommendedopen"></a>Office.DocsUI.DocStage.RecommendedOpen

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Događaj se snima kad se izvršava operacija otvaranja datoteke iz odeljka preporučenih datoteka u galeriji dokumenata i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke.

Prikupljaju se sledeća polja:

- **Data_Success** - Bulova vrednost koja pokazuje da li je operacija uspela.

#### <a name="officedocsuifileoperationsdocsuifileopenmacrequired"></a>Office.DocsUI.FileOperations.DocsUIFileOpenMacRequired

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Događaj se snima kad se izvršava operacija otvaranja datoteke i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji otvaranja datoteke kao što su kategorija lokacije „Tip usluge“ i prva četiri znaka oznake tipa datoteke.

Prikupljaju se sledeća polja:

- **Data_Ext** - Oznaka tipa datoteke ograničena je na prva četiri znaka oznake ili manje.

- **Data_ServiceType** – apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd.

#### <a name="officedocsuifileoperationsopendocumentmeasurements"></a>Office.DocsUI.FileOperations.OpenDocumentMeasurements

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Događaj beleži kada se izvršava otvaranje datoteke i koristi se za razumevanje i određivanje prioriteta korisničkog iskustva na osnovu informacija o otvaranju datoteka, naročito informacija o performansama.

Prikupljaju se sledeća polja:

- **Data_AppDuration** – Vreme obrade tokom operacije otvaranja datoteke.

- **Data_BootDuration** – Trajanje procesa pokretanja otvorene datoteke.

- **Data_ClickOrigin** - Niska koja ukazuje na to odakle je deo veze koji je korisnik kliknuo u iOS Outlook aplikaciji da bi otvorio datoteku u Office aplikaciji.

- **Data_ClickTime** – Unix vreme epohe kada je korisnik kliknuo na link u iOS Outlook aplikaciji da bi otvorio datoteku u Office aplikaciji.

- **Data_ClosePreviouslyOpenedMarkers** – Vrednost niske koja evidentira trajanje između nekih pozivanja funkcije, u formatu sa id–om funkcije i trajanjem.

- **Data_DetachedDuration** – Trajanje procesa odvajanja događaja. 

- **Data_Doc_AccessMode** – Nabrajanje koje označava režim pristupa datoteke, npr. samo za čitanje, čitanje i pisanje.

- **Data_Doc_AsyncOpenKind**- Nabrajanje koje ukazuje na tip asinhronog toka korišćenog za otvaranje datoteke.

- **Data_Doc_ChunkingType**- Nabrajanje koje ukazuje na tip algoritma deljenja datoteke na odlomke.

- **Data_Doc_EdpState** - Nabrajanje koje označava stanje zaštite podataka preduzeća.

- **Data_Doc_Ext** - Oznaka tipa datoteke.

- **Data_Doc_Fqdn** – Ime datoteke na host serveru.

- **Data_Doc_FqdnHash** – GUID koji jedinstveno identifikuje ime hosta servera.

- **Data_Doc_IdentityTelemetryId** – GUID koji jedinstveno identifikuje identitet koji se koristi za otvaranje datoteke.

- **Data_Doc_InitializationScenario**- Nabrajanje koje označava detaljan tip scenarija operacije otvaranja datoteke.

- **Data_Doc_IOFlags** – Nabrajanje koje ukazuje na IO zastavice operacije otvaranje datoteke, npr. da li je datoteka keširana ili ne.

- **Data_Doc_IsCloudCollabEnabled** – Da li je za određenu datoteku omogućena saradnja u oblaku ili ne.

- **Data_Doc_IsIncrementalOpen** – Da li je datoteka otvorena postepenim otvaranjem ili ne.

- **Data_Doc_IsOcsSupported** – Da li datoteka podržava Office uslugu za saradnju ili ne.

- **Data_Doc_IsOpeningOfflineCopy** – Da li je datoteka otvorena iz vanmrežne keširane kopije ili ne.

- **Data_Doc_IsPrefetched** – Da li je datoteka bila učitana u pozadini pre operacije otvaranja.

- **Data_Doc_IsSyncBacked** – Da li datoteka u oblaku postoji lokalno i da li je sinhronizovana sa serverom.

- **Data_Doc_Location** – Nabrajanje koje ukazuje na to gde se datoteka nalazi, npr. lokalno ili u oblaku.

- **Data_Doc_ReadOnlyReasons** – Nabrajanje koji označava razlog za datoteku koja je samo za čitanje.

- **Data_Doc_ResourceIdHash** – GUID koji na jedinstveno identifikuje ID resursa datoteke na serveru.

- **Data_Doc_RtcType** – Nabrajanje koje označava tip RTC kanala koji datoteka koristi.

- **Data_Doc_ServerDocId** – GUID koji jedinstveno identifikuje ID dokumenta na serveru.

- **Data_Doc_ServerProtocol** – Nabrajanje koje označava protokol servera datoteke u oblaku.

- **Data_Doc_ServerType** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_ServerVersion** – Nabrajanje koje označava tip servera datoteke u oblaku.

- **Data_Doc_SessionId** – Ceo broj koji se povećava za 1 za svaku operaciju otvaranja datoteke u sesiji.

- **Data_Doc_SharePointServiceContext** - Niska koja se koristi za uporednu evidenciju na strani klijenta i na strani servera, to je obično neka vrsta ID-a.

- **Data_Doc_SizeInBytes** - Veličina dokumenta u bajtovima.

- **Data_Doc_SpecialChars** – Nabrajanje koje označava vrstu specijalnog znaka u URL adresi.

- **Data_Doc_UrlHash** – GUID koji jedinstveno identifikuje URL adresu datoteke.

- **Data_Doc_UsedWrsDataOnOpen** - Da li je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka.

- **Data_Doc_WopiServiceId** - Niska koja označava od koje usluge potiče WOPI (Web Application Open Platform Interface Protocol) datoteka.

- **Data_HWModel** – Vrednost niske koja evidentira model iPad ili iPhone uređaja.

- **Data_InclusiveMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje obuhvata trajanje podfunkcijskih poziva.

- **Data_InitializationReason** – Nabrajanje koje ukazuje na način otvaranja datoteke, npr. iz kog elementa korisničkog interfejsa ili pokretanje iz druge aplikacije.

- **Data_IsDocumentAlreadyOpen** – Da li je datoteka već otvorena ili nije.

- **Data_IsInterrupted** – Da li je radnju otvorene datoteke prekinula aplikacija koja prelazi u pozadinu ili nije.

- **Data_Measurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije i trajanjem koje isključuje trajanje podfunkcijskih poziva.

- **Data_OpenInPlace** – Da li datoteka mora da se kopira u zaštićeno sandbox okruženje Office sistema pre nego što korisnik može da je otvori.

- **Data_OpenStartTime** – Vreme Unix epohe kada je započeto otvaranje datoteke.

- **Data_PrefetchSourceOptions** – Naznačavanje koje ukazuje na to kako se datoteka stavlja na raspolaganje van mreže za dokumente u oblaku, na primer, od nedavnih i preporučenih datoteka. 

- **Data_SilhouetteDuration** – Trajanje prikazivanja otvorene datoteke.

- **Data_SourceApplication** - Niska koja označava paket ID izvorne aplikacije kada je druga aplikacija pokrenula otvaranje datoteke.

- **Data_StopwatchDuration** – Trajanje događaja od početka da kraja.

- **Data_TimeSplitMeasurements** – Vrednost niske koja evidentira trajanje pozivanja funkcije, u formatu sa oznakom funkcije, vremenskom oznakom početka i trajanjem.

#### <a name="officedocsuifileoperationsopenfilewithreason"></a>Office.DocsUI.FileOperations.OpenFileWithReason 

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Događaj beleži kada se odvija operacija otvaranja datoteke i koristi se za razumevanje i davanje prioriteta korisničkom iskustvu na osnovu informacija o operacijama otvorenih datoteka, kao što su kategorije lokacija „Vrsta usluge“ i odakle je u aplikaciji korisnik zatražio da otvori datoteku.

Prikupljaju se sledeća polja:

- **Data_IsCandidateDropboxFile** – ovo je Bulova vrednost koja se evidentira ako pregledajući putanju datoteke smatramo da je to možda iz fascikle koju sinhronizuju DropBox.

- **Data_IsSignedIn** - bez obzira na to da li je korisnik prijavljen kada se čuva datoteka.

- **Data_OpenReason** - otvoreni razlog je numerička vrednost koja označava mesto u okviru aplikacije sa kojeg je korisnik otvorio datoteku.

- **Data_ServiceType** – apstraktna numerička kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

#### <a name="officedocsuifileoperationssavetourl"></a>Office.DocsUI.FileOperations.SaveToURL

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se snima kad se izvršava operacija „Sačuvaj kao“ i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji datoteka, kao što su kategorije lokacije i prva četiri znaka oznake tipa datoteke.  Operacija „Sačuvaj kao“ pojavljuje se svaki put kada korisnik napravi novu datoteku i prvi put je sačuva ili sačuva kopiju postojeće datoteke na novu lokaciju.

Prikupljaju se sledeća polja:

- **Data_FileExtension** – prva četiri znaka oznake tipa nove datoteke.

- **Data_IsNewFileCreation** - označava da li je operacija čuvanja za novu datoteku ili kopiju postojeće datoteke.


- **Data_IsSignedIn** - bez obzira na to da li je korisnik prijavljen kada se čuva datoteka.

- **Data_SaveErrorCode** - numerička vrednost koja se postavlja ako postoji greška koja će vam pomoći u prepoznavanju vrste greške.

- **Data_SaveErrorDomain** – precizira domen SaveErrorCode kako je definisan od strane Apple SaveErrorDomains „to su proizvoljne niske koje se koriste za razlikovanje kodova“.

- **Data_SaveLocation** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_SaveOperationType** – numerička vrednost definisana NSSaveOperationType grupom vrednosti kompanije Apple.


#### <a name="officedocsuisharinguicloudupsellshown"></a>Office.DocsUI.SharingUI.CloudUpsellShown 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik prođe kroz nadogradnju dokumenata u tok oblaka.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileStyle** - numerička vrednost koja pokazuje iz kojeg scenarija je prikazano iskustvo nadogradnje kao što je preklopnik za automatsko čuvanje ili dugme za deljenje.

- **Data_FileType** – prva četiri znaka oznake tipa nove datoteke.

- **Data_InDocStage** - Bulova vrednost koja pokazuje da li je iskustvo nadogradnje prikazano iz galerije dokumenata ili iz prozora dokumenta.

- **Data_IsDocumentOpened** - Bulova vrednost koja pokazuje da li je trenutni dokument za koji se prikazuje iskustvo nadogradnje takođe otvoren.

- **Data_IsDraft** - Bulova vrednost koja pokazuje da li je trenutna datoteka ikada sačuvana.

- **Data_IsSheetModal** - Bulova vrednost koja označava da li je iskustvo nadogradnje predstavljeno modalno ili ne.

#### <a name="officedocsuisharinguicloudupsellupload"></a>Office.DocsUI.SharingUI.CloudUpsellShown 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik odluči da otpremi novu ili lokalnu datoteku u oblak i rezultat te operacije.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileStyle** - numerička vrednost koja pokazuje iz kojeg scenarija je prikazano iskustvo nadogradnje kao što je preklopnik za automatsko čuvanje ili dugme za deljenje.

- **Data_FileType** – prva četiri znaka oznake tipa nove datoteke.

- **Data_InDocStage** - Bulova vrednost koja pokazuje da li je iskustvo nadogradnje prikazano iz galerije dokumenata ili iz prozora dokumenta.

- **Data_IsDefaultServiceLocation** - Bulova vrednost koja označava da li je izabrana lokacija za otpremu dokumenta podrazumevana lokacija.

- **Data_IsDocumentOpened** - Bulova vrednost koja pokazuje da li je trenutni dokument za koji se prikazuje iskustvo nadogradnje takođe otvoren.

- **Data_IsDraft** - Bulova vrednost koja pokazuje da li je trenutna datoteka ikada sačuvana.

- **Data_IsSheetModal** - Bulova vrednost koja označava da li je iskustvo nadogradnje predstavljeno modalno ili ne.

- **Data_LocationServiceType** – apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_UploadAction** – fiksno kodirana niska koja pokazuje da li je otpremanje bilo operacija „premeštanje“ ili „kopiranje“.

- **Data_UploadResult** – fiksno kodirana niska koja označava rezultat pokušaja otpremanja, uključujući, ali ne ograničavajući se na „Uspeh“', „UserCancelledUpload“, i „PreAuthFailed“.

#### <a name="officedocsuisharinguicopylinkoperation"></a>Office.DocsUI.SharingUI.CopyLinkOperation

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Ovaj događaj se snima kada korisnik odluči da deli dokument u oblaku generisanjem veze na dokument u oblaku i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ ServiceType** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_LinkType** – fiksno kodirana niska koja opisuje vrstu izvršenog poziva kao što su „Samo za prikaz“ i „Prikaz i uređivanje“.

- **Data_ShareScenario** – fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="officedocsuisharinguidocsuionedriveshare"></a>Office.DocsUI.SharingUI.DocsUIOneDriveShare 

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Ovaj događaj se beleži kada korisnik odluči da deli dokument u oblaku koristeći iskustvo deljenja usluge OneDrive i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ODSPShareWebviewShareError** - ako iskustvo deljenja doživi grešku, ovo je numerička vrednost koja će vam pomoći da identifikujete razlog neuspeha.

- **Data_ODSPShareWebviewShareGrantAccessResult** - Bulova vrednost koja kad je vrednost „true“ ukazuje da je lagana operacija deljenja uspešno završena.

- **Data_ODSPShareWebviewShareSuccessType** - kada se operacija deljenja uspešno dovrši, ovo je numerička vrednost koja se koristi da se odredi koja operacija deljenja je dovršena.

- **Data_WebViewInfoResult** - ako se korisnički interfejs ne učita, ovo je numerička vrednost koja će vam pomoći da identifikujete razlog neuspeha. 

- **Data_WebViewLoadTimeInMs** - numerička vrednost koja snima koliko je vremena potrebno da se veb korisnički interfejs učita.


#### <a name="officedocsuisharinguiinvitepeople"></a>Office.DocsUI.SharingUI.InvitePeople 

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama. Ovaj događaj se snima kada korisnik odluči da pozove osobe dokument u oblaku i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_ ServiceType** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_InviteeCount** - ukupan broj kontakata pozvanih u dokument u jednoj akciji poziva.

- **Data_LinkType** – fiksno kodirana niska koja opisuje vrstu izvršenog poziva kao što su „Samo za prikaz“ i „Prikaz i uređivanje“.

- **Data_MessageLength** - numerički broj ukupnog broja znakova poslatih u poruci poziva.

- **Data_ShareScenario** – fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

#### <a name="officedocsuisharinguisendacopyoperation"></a>Office.DocsUI.SharingUI.SendACopyOperation

Ovaj događaj se prikuplja za Office aplikacije koje rade na Apple platformama.. Ovaj događaj se snima kada korisnik odluči da pošalje kopiju dokumenta i koristi se za bolje razumevanje i određivanje prioriteta kod korisnika na osnovu deljenja dokumenata.

Prikupljaju se sledeća polja:

- **Data_IsHomeTabEnabled** - Bulova vrednost koja označava da li je korisniku trenutno dostupna kartica „Početak“.

- **Data_IsRecommendedEnabled** – Bulova vrednost koja označava da li je korisniku trenutno dostupno iskustvo „Preporučeno“.

- **Data_OperationType** – numerička vrednost koja označava koja vrsta slanja operacije kopiranja se izvršava kao što je slanje kopije e–poštom ili slanje kopije putem Apple kontrole deljenja.

- **Data_ ServiceType** – apstraktna kategorizacija originalne lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_ShareFileType** – fiksno kodirana niska opisa tipa objekta koji se deli, uključujući, ali ne ograničavajući se na: „Dokument“, „PDF”, „Slika“.

- **Data_ShareScenario** – fiksno kodirana niska opisa gde se u korisničkom interfejsu aplikacije deli datoteka, uključujući, ali ne ograničavajući se na, „Meni datoteka“, „OpenTabShareActionMenu“, „RecentTabShareActionMenu“.

- **Data_SharingService** - Bulova vrednost koja označava da li je datoteka kreirana kada je korisnik tražio predložak.

#### <a name="officedocsuisharinguiupsellshare"></a>Office.DocsUI.SharingUI.UpsellShare 

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Ovaj događaj se snima kada korisnik prođe kroz nadogradnju dokumenata u tok oblaka kada pokušava da podeli dokument.  Ovi podaci se koriste za bolje razumevanje i određivanje prioriteta korisničkog iskustva koji se odnose na premeštanje dokumenata na lokacije u oblaku.

Prikupljaju se sledeća polja:

- **Data_FileOperationResult** - numerička vrednost koja pokazuje da li je operacija uspela.

- **Data_HostedFromDocStage** - Bulova vrednost koja označava da li korisnik prolazi kroz nadogradnju do protoka oblaka iz DocStage iskustva ili iz otvorenog dokumenta.

- **Data_isLocalCopyOn** - Bulova vrednost koja označava da li je korisnik odlučio da zadrži lokalnu kopiju dokumenta otpremom na lokaciju u oblaku ili da premesti postojeći dokument na lokaciju u oblaku.

- **Data_NewFileType** – apstraktna kategorizacija lokacije nove lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

- **Data_OriginalFileType** – apstraktna kategorizacija lokacije datoteke kao što je „SharePoint“, „OneDrive“, „Lokalno“, „WOPI“, itd., a eksplicitno nije stvarna lokacija datoteke.

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

Podaci u vezi sa obradom pojedinačnog manifesta za O365 programski dodatak dodeljen od strane administratora. Koristi se za analizu problema klijenata i izrade grafikona uspešnosti klijenta.
 
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

#### <a name="officefeedeventsinitializing"></a>Office.Feed.Events.Initializing

Ovaj događaj se sakuplja kada se feed pokrene. Ovaj događaj se koristi za ukazivanje na to da feed počinje i da bi se dijagnostikovali problemi sa pouzdanošću prilikom pokretanja feedova.

- **AppInfo.Language** - Jezik aplikacije u IETF formatu jezičke oznake.

- **AppInfo.Name** - Ime komponente u korišćenju (Office feed).

- **AppInfo.Version** - Verzija aplikacije.

- **clientCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **clientType** – Aplikacija na kojoj se komponenta pokreće.

- **DeviceInfo.Make** - Proizvođač uređaja ili ime OEM proizvođača.

- **DeviceInfo.NetworkProvider** - Mrežni ili mobilni operater, kao što je "AT&T".

- **DeviceInfo.NetworkType** - Tip mrežnog povezivanja uređaja koji se koristi, kao što je "Wired", "Wi-Fi" ili "WWAN" (podaci/mobilne uređaje).

- **DeviceInfo.OsName** - Ime OS uređaja.

- **DeviceInfo_SDKUid** – Jedinstveno identifikuje uređaj iz perspektive telemetrije SDK–a.

- **eventId** - Identifikator imena događaja. 

- **EventInfo.SdkVersion** - Verzija telemetrije SDK-a koju klijent koristi za generisanje događaja.

- **eventpriority** - Vrednost nabrajanja za prioritet slanja događaja.

- **feature** - Koristi se za grupisanje različitih događaja iste funkcije.

- **hostAppRing** - Populacija korisnika kojima je aplikacija distribuirana.

- **properties** – Sadrži dodatna svojstva metapodataka prikupljenih za svaki događaj..
        
    - **ClientTimeStamp** - Vremenska oznaka kada je događaj prijavljen u klijentu.

- **publicEventName** - Ime događaja koji je javno okrenut.  

- **region** – Geografsko područje usluge feeda na koju je korisnik povezan. 

- **tenantAadObjectId** – Globalni jedinstveni identifikator za korisnika zakupca preduzeća.

- **type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj, QoS.

- **userAadObjectId** - Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog.

- **UserInfo.Id** - Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog.

- **UserInfo.IdType** - Određuje vrstu ID korisnika 

- **UserInfo.Language** - The user's language in IETF language tag format.

- **UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za korisnika Microsoft naloga.

- **UserInfo.OMSTenantId** – Zakupac za koga je vezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

- **UserInfo.TimeZone** - Korisnička vremenska zona u odnosu na UTC vreme.

- **userPuid** - Globalni jedinstveni identifikator korisnika Microsoft naloga.

- **version** - Verzija feeda klijenta.

#### <a name="officefeedeventsofficefeeddidappear"></a>Office.Feed.Events.OfficeFeedDidAppear

Ovaj događaj se sakuplja kada se feed prikazuje korisniku. Događaj se koristi za proveru da li je feed završio korak inicijalizacije i da bi se dijagnostikovali problemi sa pouzdanošću prilikom pokretanja feedova.

- **AppInfo.Language** - Jezik aplikacije u IETF formatu jezičke oznake.

- **AppInfo.Name** - Ime komponente u korišćenju (Office feed).

- **AppInfo.Version** - Verzija aplikacije.

- **bridgeWaitingTime** - Metrika za dijagnostiku performansi u prikazivanju feeda.

- **clientCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **clientScenario** – Diskriminator scenarija za različite varijante fida.

- **ClientTimeStamp** - Vremenska oznaka kada je događaj prijavljen u klijentu.

- **clientType** – Aplikacija na kojoj se komponenta pokreće.

- **DeviceInfo.Make** - Proizvođač uređaja ili ime OEM proizvođača.

- **DeviceInfo.NetworkProvider** - Mrežni ili mobilni operater, kao što je "AT&T".

- **DeviceInfo.NetworkType** - Tip mrežnog povezivanja uređaja koji se koristi, kao što je "Wired", "Wi-Fi" ili "WWAN" (podaci/mobilne uređaje).

- **DeviceInfo.OsName** - Ime OS uređaja.

- **DeviceInfo_SDKUid** – Jedinstveno identifikuje uređaj iz perspektive telemetrije SDK–a.

- **eventId** - Identifikator imena događaja.

- **EventInfo.SdkVersion** - Verzija telemetrije SDK-a koju klijent koristi za generisanje događaja.

- **eventpriority** - Vrednost nabrajanja za prioritet slanja događaja.

- **feature** - Koristi se za grupisanje različitih događaja iste funkcije.

- **hostAppRing** - Populacija korisnika kojima je aplikacija distribuirana.

- **properties** – Sadrži dodatna svojstva metapodataka prikupljenih za svaki događaj.. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **publicEventName** - Ime događaja koji je javno okrenut.  

- **region** – Geografsko područje usluge feeda na koju je korisnik povezan. 

- **renderTime** - Metrika za dijagnostiku performansi u prikazivanju feeda.

- **tenantAadObjectId** - Globalni jedinstveni identifikator za korisnika zakupca preduzeća.

- **type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj, QoS.

- **userAadObjectId** - Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog.

- **UserInfo.Id** - Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog.

- **UserInfo.IdType** - Određuje vrstu ID korisnika 

- **UserInfo.Language** - The user's language in IETF language tag format.

- **UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za korisnika Microsoft naloga.

- **UserInfo.OMSTenantId** – Zakupac za koga je vezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

- **UserInfo.TimeZone** - Korisnička vremenska zona u odnosu na UTC vreme.

- **userPuid** - Globalni jedinstveni identifikator korisnika Microsoft naloga.

- **version** - Verzija feeda klijenta.

#### <a name="officefeedbacksurveyfloodgateclientgetdecisionforactionprestart"></a>Office.Feedback.Survey.FloodgateClient.GetDecisionForActionPreStart

U Office aplikacijama kontrolišemo učestalost poruka u proizvodu i pritiskamo poruke putem sloja upravljanja. Ovaj događaj se prijavljuje u uslovima greške kada pokušavamo da primenimo upravljanje na poruke u aplikaciji pre nego što se modul koji upravlja upravljanjem u potpunosti aktivira. Ova telemetrija poboljšava logiku upravljanja prikupljanjem detalja scenarija u kojima se ne primenjuje upravljanje.

Prikupljaju se sledeća polja:

- **Data_EventId** – Jedinstveni identifikator izraza evidencije.

- **Data_SurveyId** – ime poruke koju pokušavamo da pokažemo kada se generiše ova greška.


#### <a name="officefeedbacksurveyfloodgateclientsurveytracked"></a>Office.Feedback.Survey.FloodgateClient.SurveyTracked

Prati kada je uređaj odabran za ispitivanje. Koristi se za procenu ispravnosti procesa izbora korisnika ankete i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyfloodgateclienttriggermet"></a>Office.Feedback.Survey.FloodgateClient.TriggerMet

Prati kada je uređaj ispunio kriterijume za prikazivanje ankete. Koristi se za procenu ispravnosti procesa aktiviranja ankete i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyfloodgateclientuserselected"></a>Office.Feedback.Survey.FloodgateClient.UserSelected

Prati kada je uređaj odabran za ispitivanje. Koristi se za procenu ispravnosti procesa izbora korisnika ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyuiandroid"></a>Office.Feedback.Survey.UI.Android

Na Android uređaju prati kada korisnik uređaja vrši interakciju sa odzivom za anketu i korisničkim interfejsom ankete. Koristi se za procenu ispravnosti celokupnog iskustva ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyuiios"></a>Office.Feedback.Survey.UI.IOS

Na iOS uređaju prati kada korisnik uređaja vrši interakciju sa odzivom za anketu i korisničkim interfejsom ankete. Koristi se za procenu ispravnosti celokupnog iskustva ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyuimac"></a>Office.Feedback.Survey.UI.Mac

Na Mac uređaju prati kada korisnik uređaja vrši interakciju sa odzivom za anketu i korisničkim interfejsom ankete. Koristi se za procenu ispravnosti celokupnog iskustva ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyuiwin32"></a>Office.Feedback.Survey.UI.Win32

Na Win32 uređaju prati kada korisnik uređaja vrši interakciju sa odzivom za anketu i korisničkim interfejsom ankete. Koristi se za procenu ispravnosti celokupnog iskustva ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefeedbacksurveyuiwin32toast"></a>Office.Feedback.Survey.UI.Win32.Toast

Prati kada se pokazuje upit za anketu. Koristi se za procenu ispravnosti procesa slanja odziva za anketu, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja:

- **ExpirationTimeUTC** – datum/vreme isteka ankete

- **SurveyName** – ime prikazane ankete

- **SurveyId** – jedinstvena instanca kampanje

- **UniqueId** – ID za identifikaciju pojedinačnog dela telemetrije

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Omogućava nam da znamo da li se datoteka uspešno otvorila iz FIO sloja. Koristi se u svrhu održavanja dobrog stanja opcije i praćenja.

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

  - **Data.DialogId –** Podesite da li će se tokom otvaranja prikazivati dijalog korisničkog interfejsa, što znači da je korisniku prikazana poruka upozorenja

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

  - **Data.IsStubFile –** Dokument još uvek nije sačuvan u usluzi u oblaku

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** stanje dokumenta se promenilo, promene su možda stigle dok dokument nije bio otvoren

  - **Data.isTaskCanceledAfterOpenComplete -** Zastarelo

  - **Data.IsWorkingBranchAvailableOnOpen -** Promena praćenja dijagnostike kako bismo bili sigurni da imamo najnoviju verziju deljene datoteke

  - **Data.LicenseStatus** – Podaci o statusu licence proizvoda za potrebe dijagonstike, koriste se za proveru da li su odgovarajuće karakteristike proizvoda omogućene za vrstu korisničke licence 

  - **Top licence za podatke -** Ukazuje na status licence (besplatna/plaćenu ili probnu verziju, itd.)

  - **Lokacija podataka -** Ukazuje na tip medijuma za skladištenje/lokaciju (USB, oblak itd.)

  - **Data.LockRequestDocMode -** Označava da li je dokument dostupan drugima

  - **Data.MyDeferredValue -** Zastarelo

  - **Data.Network.BytesReceived -** Zastarelo

  - **Data.Network.BytesSent -** Zastarelo

  - **Data.Network.ConnectionsCreated -** Zastarelo

  - **Data.Network.ConnectionsEnded -** Zastarelo

  - **Data.OcsDisableReasons –** Razlog zašto usluga deljene saradnje nije dostupna za dokument

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

Ovaj događaj nam omogućava da znamo da li je datoteka uspešno sačuvana iz FIO sloja. Koristi se za nadgledanje i ispravnost funkcija.

Prikupljaju se sledeća polja:

  - **Grupa aktivnosti -** oznaka koja omogućava da skup događaja za praćenje bude grupisan kako bi upravljao sveukupnim uspehom

  - **Activity.IsHVA -** zastavica koja označava da je događaj ključan za uspeh korisnika

  - **Data.AsyncOpen -** zastavica koja označava da je otvoren dokument sa sadržajem koji je stigao posle otvaranja glavnog tela

  - **Data.BaseDownloadTriggered -** Promena praćenja dijagnostike koja ukazuje na to da je zatražena osnovna verzija dokumenta

  - **Data.BlockAutoUploadReasons –** kodove razloga za blokiran status otpremanja (npr. Automatsko čuvanje je isključeno, dokument je u tranziciji)

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

  - **Data.DstDoc.Extension –** Tip novog dokumenta (docx/xlsm/pptx, itd.)

  - **Data.DstDoc.FileFormat –** Protokol za format datoteke novog dokumenta

  - **Data.DstDoc.Fqdn –** Ime OneDrive ili SharePoint Online domena novog dokumenta

  - **Data.DstDoc.FqdnHash –** Jednosmerni heš imena domena novog dokumenta koji se može identifikovati

  - **Data.DstDoc.IdentityUniqueId -** Zastarelo

  - **Data.DstDoc.IOFlags –** Zastavice keširanih opcija novog dokumenta koje se koriste prilikom otvaranja

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

  - **Data.IsStubFile –** Dokument još uvek nije podeljen u usluzi u oblaku

  - **Data.IsSyncBackedFile -** dokument se nalazi u fascikli koja se ažurira putem automatskog sinhronizovanja 

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen –** stanje dokumenta se promenilo, promene su možda stigle dok dokument nije bio otvoren

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

#### <a name="officefirstrunappleactivationresult"></a>Office.FirstRun.Apple.ActivationResult

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktiviranja pretplate na Office 365 zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.).

Prikupljaju se sledeća polja:

- **Data_ActivationStatusCollectionTime** – vremenska oznaka

- **Data_ActivationStatusError** – kod greške prilikom aktiviranja.

- **Data_ActivationStatusFlowType** – numerička vrednost koja označava tip toka aktivacije

#### <a name="officefirstrunappleactivationstatus"></a>Office.FirstRun.Apple.ActivationStatus

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za utvrđivanje ishoda aktiviranja pretplate na Office 365 zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). Prikupljamo podatke koji sadrže tip aktivacije, vrstu toka (FRE/DocStage/Kupovina) i ID Office usluge licenciranja.

Prikupljaju se sledeća polja:

- **Data_ActivationTypeCollectionTime** – vremenska oznaka

- **Data_ActivationTypeFlowType** – numerička vrednost koja označava tip toka aktivacije

- **Data_ActivationTypeOLSLicense** – identifikator licence

- **Data_ActivationTypeStatus** – kod status aktivacije

#### <a name="officefirstrunapplefirstruncomplete"></a>Office.FirstRun.Apple.FirstRunComplete

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da li korisnik radi u freemium programu, tip toka koji se pokreće (FRE/DocStage/Kupovina) i tip identiteta (MSA/OrgID). Koristimo ovaj događaj da bismo utvrdili da li je završen utisak pri prvom pokretanju (FRE) i tip identiteta koji se koristi za prijavljivanje (MSA / OrgID).

Prikupljaju se sledeća polja:

- **Data_FirstRunCompletedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunCompletedFlowType** - kod koji označava tip korisničkog toka koji je dovršen 

- **Data_FirstRunCompletedFreemiumStatus** - kod koji predstavlja status dovršenosti za tok freemium korisnika

- **Data_FirstRunCompletedIdentityType** - tip identiteta korisnika koji je završio tok

#### <a name="officefirstrunapplefirstrunstart"></a>Office.FirstRun.Apple.FirstRunStart

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“ i tip toka koji se pokreće (FRE/DocStage/Kupovina). Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunStartedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunStartedFlowType** - kod koji označava tip korisničkog toka koji je dovršen 

#### <a name="officefirstrunapplefirstrunstartedandcompleted"></a>Office.FirstRun.Apple.FirstRunStartedAndCompleted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da li korisnik radi u freemium programu, tip toka koji se pokreće (FRE/DocStage/Kupovina) i tip identiteta (MSA/OrgID). Koristimo ovaj događaj da utvrdimo stanje i efikasnost toka „Utiska pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunCompletedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen

- **Data_FirstRunCompletedFlowType** - kod koji označava tip korisničkog toka koji je dovršen  

- **Data_FirstRunCompletedFreemiumStatus** - kod koji predstavlja status dovršenosti za tok freemium korisnika

- **Data_FirstRunCompletedIdentityType** - tip identiteta korisnika koji je završio tok

- **Data_FirstRunStartedCollectionTime** - vremenska oznaka koja registruje vreme kad je tok pokrenut

- **Data_FirstRunStartedFlowType** - kod koji označava tip korisničkog toka koji je pokrenut

#### <a name="officefirstrunappleinapppurchaseactivationfail"></a>Office.FirstRun.Apple.InAppPurchaseActivationFail

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_ActivationFailCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do neuspeha aktivacije 

- **Data_ActivationFailFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do povezivanja 

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="officefirstrunappleinapppurchaseactivationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseActivationSuccess

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_ActivatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do aktivacije 

- **Data_ActivatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem je došlo do povezivanja 

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="officefirstrunappleinapppurchaseassociationfailed"></a>Office.FirstRun.Apple.InAppPurchaseAssociationFailed

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_AppChargedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kom je kupovina naplaćena

- **Data_AppChargedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicationFailedCollectionTime** - vremenska oznaka koja registruje vreme u kojem povezivanje aplikacije nije uspelo

- **Data_AssoicationFailedFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicationFailedResult** - kod koji označava tip uočenog neuspeha

#### <a name="officefirstrunappleinapppurchaseassociationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseAssociationSuccess

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke da bismo utvrdili ishod aktivacije kupovine iz aplikacije zajedno sa tokom koji se koristi za aktiviranje (utisak pri prvom pokretanju, tok u aplikaciji, kupovina, itd.). 

Prikupljaju se sledeća polja:

- **Data_AppChargedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kom je kupovina naplaćena

- **Data_AppChargedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AssoicatedSuccessfullyCollectionTime** - vremenska oznaka koja registruje vreme u kojem povezivanje aplikacije nije uspelo

- **Data_AssoicatedSuccessfullyFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="officefirstrunappleinapppurchasefailures"></a>Office.FirstRun.Apple.InAppPurchaseFailures

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka aktivacije aplikacije. Prikupljamo podatke o ishodu toka kupovine iz aplikacije.

Prikupljaju se sledeća polja:

- **Data_AppStoreFailureFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_AppStoreFailureResult** - uočen rezultat neuspeha

- **Data_CancelRequestFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_EventId** - kod koji označava tip uočenog neuspeha

#### <a name="officefirstrunappleinapppurchasesattempted"></a>Office.FirstRun.Apple.InAppPurchasesAttempted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje kupovine iz aplikacije i tip SKU-a koji se kupuje (mesečno/godišnje/za kućnu upotrebu/za ličnu upotrebu).

Prikupljaju se sledeća polja:

- **Data_EventId** - kod koji označava tip uočenog rezultata

- **Data_PurchasedClickedOfferType** - tip SKU-a koji se pokušao kupiti

- **Data_PurchaseSuccessfulFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="officefirstrunappleinapprestoreattempted"></a>Office.FirstRun.Apple.InAppRestoreAttempted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje obnove u aplikaciji

Prikupljaju se sledeća polja:

- **Data_EventId** - kod koji označava tip ishoda pokušaja

- **Data_RestoreAttemptFlowType** - kod koji označava tip korisničkog toka koji se koristio

#### <a name="officefirstrunappleinapprestoreattemptfailed"></a>Office.FirstRun.Apple.InAppRestoreAttemptFailed

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja toka kupovine iz aplikacije. Prikupljamo podatke da bismo pratili pokušaje obnove u aplikaciji i njihove povezane tokove i greške.

Prikupljaju se sledeća polja:

- **Data_RestoreButtonFlowType** - kod koji označava tip korisničkog toka koji se koristio

- **Data_RestoredFailedPaymentCancelledFlowType** - kod koji označava tip toka otkazivanja plaćanja koje je izvršeno

- **Data_RestoredFailedUnKnownFlowType** - da li je pokušaj propao zbog sprovođenja neočekivanog toka korisnika

- **Data_RestoredFailedUnKnownResult** - da li je pokušaj propao iz nepoznatih razloga

#### <a name="officefirstrunapplemacfirstruncompleted"></a>Office.FirstRun.Apple.MacFirstRunCompleted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik prošao kroz „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je „Utisak pri prvom pokretanju“ (FRE) uspešno izveden.

Prikupljaju se sledeća polja:

- **Data_FirstRunCollectionTime** - vremenska oznaka koja registruje vreme kad je tok dovršen.

#### <a name="officefirstrunapplemacwxpfirstrunstarted"></a>Office.FirstRun.Apple.MacWXPFirstRunStarted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunPanelName** - naziv table sa koje je iskustvo počelo


#### <a name="officefloodgateuserfactappusage"></a>Office.Floodgate.UserFact.AppUsage

To ukazuje na to kada korisnik koristi funkcije visoke vrednosti u okviru proizvoda. Ono može da ukazuje na to da li je korisnik otkrio funkciju ili ju je koristio. Signal će omogućiti uvid u upotrebu proizvoda koji pomaže u poboljšanju proizvoda.

Prikupljaju se sledeća polja: 

- **FeatureAction** – Oznaka koja označava funkciju velike vrednosti i radnju koju je izvršio korisnik, na primer ContentPickerTried, TemplatesSeen.


#### <a name="officelenslenssdkcloudconnectorlaunch"></a>Office.Lens.LensSdk.CloudConnectorLaunch

Kada korisnik zaberja sliku i željene funkcije u konačnom izboru za sliku za korišćenje sistema OCR, ovaj događaj se sakuplja.     
Ovo je korisnički zapis od korisnika do korisnika za uslugu jer ne postoji mapiranje zadatka od korisnika do usluge na samoj usluzi. Korisnički ID se zahteva da bi ispunio zahteve GDPR-a jer usluga nije direktno izložena korisnicima, već putem klijenata i identifikuje ukupan broj osoba koje koriste uslugu, pomažući usluzi da prati broj korisnika pomoću proizvoda, kao i identifikovanje promena u trendovima i pomaže pri pronalaženju i ispravljanju problema u proizvodu.

Prikupljaju se sledeća polja:

- **CallType** –String za identifikovanje ako je API Call bio sinhronizovano ili asinhrono.

- **CloudConnectorRequestId** –String koji identifikuje zahtev za uslugom koji je napravljen da konvertuje slike koristeći uslugu. 

- **Target–Connetconnectortarget** –String koji potvrđuje tip konverzije koju će usluga izvršiti na slikama, kao što je konvertovanje u PDF, docx, Text itd.

- **User ID** –String koji identifikuje korisnika koji poseduje slike koje se obrađuju.

- **Tip klijenta** –String koji identifikuje klijenta kao Enterprise ili pojedinačnog korisnika. Ova razlika utiče na broj slika (kvota) koju klijent može da konvertuje istovremeno. 

- **Odnosi** –String, koji identifikuje povezanost između soиiva i usluge koja se koristi za obradu datoteka.


#### <a name="officelenslenssdkcloudconnectoruploaderror"></a>Office.Lens.LensSdk.CloudConnectorUploadError

U vidu slike u tabelu, kada korisnik pribavi deljenje, kopiranje ili otvaranje, ispravke u tabeli koju je napravio korisnik dele se sa uslugom da bi se poboljšali OCR. Ovaj događaj se sakuplja na osnovu reakcije greške te usluge i sadrži relevantne identifikatore da bi se otklanjaju Razni problemi u usluzi. 

Prikupljaju se sledeća polja:

- **CloudConnectorRequestId** –String identifikator da biste povezali posao sa uslugom u trenutnom zahtevu za uslugu za koji su podaci o poboljšanju deljeni.

- **Korodnosu** –String koji sadrži identifikator instance trenutnog posla usluge.

- **Razlog** –String koji sadrži kôd greške i opis greške.

- **TargetType** –String koji identifikuje krajnju tačku u usluzi.

- **Tip zadatka** –String koji identifikuje nameru poziva za uslugu.


#### <a name="officelenslenssdkcloudconnectoruploadsuccess"></a>Office.Lens.LensSdk.CloudConnectorUploadSuccess

U vidu slike u tabelu, kada korisnik pribavi deljenje, kopiranje ili otvaranje, ispravke u tabeli koju je napravio korisnik dele se sa uslugom da bi se poboljšali OCR. Ovaj događaj se sakuplja na uspešnom odgovoru te usluge i sadrži relevantne identifikatore za rešavanje problema sa procesom. On omogućava i da analizirate korišćenje gasovoda za poboljšanje usluge.

Prikupljaju se sledeća polja:

- **CloudConnectorRequestId** –String identifikator da biste povezali posao sa uslugom u trenutnom zahtevu za uslugu za koji su podaci o poboljšanju deljeni.

- **Korodnosu** –String koji sadrži identifikator instance trenutnog posla usluge.

- **TargetType** –String koji identifikuje krajnju tačku u usluzi.

- **Tip zadatka** –String koji identifikuje nameru poziva za uslugu.


#### <a name="officelenslenssdksavemedia"></a>Office.Lens.LensSdk.SaveMedia

Ovaj događaj je pozvan kada korisnik klikne na dugme Gotovo i sačuva slike na Android i iOS uređaju. On olakšava merenje nivoa učešća korisnika kvanciranjem korisnika koji završe čuvanjem slika kroz našu aplikaciju.

Prikupljaju se sledeća polja samo za Android:

- **Data_FileSizeAfterCleanUp** veličine datoteke nakon čišćenja, da biste razumeli koliko se komprimovanja ostvarilo nakon čišćenja.

- **Data_FileSizeAfterSave** veličine datoteke, kada je korisnik sačuva, da bi razumeo koliko se komprimovanja ostvarilo nakon čuvanja.

- **Data_FileSizeBeforeCleanUp** veličine datoteke pre nego što je očišćene, da biste razumeli koliko je zahvatljena veličina

- **Data_Filter** – filter primenjen na sliku.

- **Data_ImageHeightAfterCleanUp** visine slike nakon očišćene aplikacije.

- **Data_ImageHeightBeforeCleanUp** – visina slike pre nego što ju je očistila aplikacija.

- **Data_ImageWidthAfterCleanUp** širinu slike pre nego što je oиistila aplikacija.

- **Data_ImageWidthBeforeCleanUp** širinu slike pre nego što je oиistila aplikacija.

- **Data_MediaId** – identifikator za slike kako bi vam pomogao da pratite uspeh operacije.

- **Data_ProcessMode** – režimu korisnika u vreme čuvanja slike od strane korisnika.

- **Data_Source** – definiše mesto na kojem je slika napravljena od primera "kamera snimljena" pomoću fotoaparata, uvezene iz galerije itd. 

Prikupljaju se sledeća polja samo za iOS:

- **Data_filter** – filter primenjen na sliku. 

- **Data_imageDPI** – smanjenje slike koje je primenjeno na sliku sačuvane datoteke

- **Data_imageSize** veličine slike nakon što je korisnik saиuvao sliku

- **Data_mediaId** – identifikator za slike kako bi vam pomogao da pratite uspeh operacije.

- **Data_mode** – režimu korisnika u vreme čuvanja slike od strane korisnika.

- **Data_sizeinPixel** veličine slike u obliku piksela

- **Data_source** – definiše mesto na kojem je slika napravljena od primera "kamera snimljena" pomoću fotoaparata, uvezene iz galerije itd. 


#### <a name="officelenslenssdkserviceidmapping"></a>Office.Lens.LensSdk.ServiceIDMapping

Ovaj događaj se prikuplja kada Lens SDK komunicira sa Microsoft uslugom „Slika u dokument“ (ili I2D). To znači da se događaj zove:

- Kada se slika otpremi u našu I2D uslugu za konverziju i izdvajanje datoteka (OCR).
- Kada korisnik treba da ispravi izlaz usluge, šaljemo povratne informacije da bismo poboljšali kvalitet.

Podaci se koriste za analizu upotrebe i rešavanje problema na strani usluge.  

Prikupljaju se sledeća polja:

- **CloudConnectorRequestId** – Niska koja identifikuje zahteve za uslugom klijentske aplikacije za scenarije konverzije i povratnih informacija.

- **CustomerId** – Ova niska pomaže da mapirate korisnike u zahteve za uslugu i pomogne nam da pratimo korišćenje. UserId je potreban da bi se ispunili GDPR zahtevi jer usluga nije direktno izložena korisnicima, već putem korisnika i identifikuje ukupan broj ljudi koji koriste uslugu, pomažući usluzi da prati obim korisnika koji koriste proizvod. 

- **I2DFeedbackAPICorrelationId** – niska koja identifikuje zahtev za povratne informacije u usluzi I2D kada korisnik ispravi izlaz usluge.

- **I2DServiceProcessID** – niska koja identifikuje zahtev za uslugom u usluzi I2D kada korisnik otprema slike radi konverzije.


#### <a name="officelivepersonacardconfigurationsetaction"></a>Office.LivePersonaCard.ConfigurationSetAction

Beležimo kada je korisnik u aplikaciji koja učitava karticu „Osoba“ u očekivanju da korisnik otvori aktivnu karticu „Trenutna osoba“. Podaci se koriste za određivanje da li je kartica pravilno učitana. 

Prikupljaju se sledeća polja: 

- **Data.accountType** – Da li korisnik pripada organizaciji ili potrošaču

- **Data.appContextId** – Slučajno generisani ID koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Naziv usluge koja se koristi (Kartica profila)

- **Data.AppInfo_Id** - Ime host aplikacije

- **Data.AppInfo_Version** - Verzija host aplikacije

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija

- **Data.contextType** – Iz kog konteksta (aplikacije) je pokrenuta kartica

- **Data.ecsConfigIds** – Identifikatori verzije za funkcije omogućene na kartici

- **Data.ecsTagId** – ID oznake za funkcije

- **Data.eventId** – Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.eventpriority** - Vrednost nabrajanja za prioritet slanja događaja.

- **Data.feature** - Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.flights** – Funkcije omogućene na kartici

- **Data.fromCache** – Da li su podaci dobavljeni iz memorije

- **Data.hasFinePointer** – Da li uređaj ima mogućnost pokazivača miša

- **Data.hasHoverEvents** – Da li uređaj ima mogućnost zadržavanja pokazivača miša

- **Data.immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

- **Data.offlineResolved** – Da li su podaci dobavljeni tokom rada van mreže

- **Data.OTelJS.Version** – Verzija OTel sistema za evidenciju

- **Data.personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene personalnosti u sesiji

- **Data.properties** – Dodatni metapodaci prikupljeni za svaki događaj na sledeći način: *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje pojaviti u starijim izdanjima.]*

  - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId
  - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId
  - **ClientTimeStamp** - Vreme u aplikaciji kada se evidentira događaj
  - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId

  - **externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih Kartica „Personalnost“ otvorenih u istoj podsesiji

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** – Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.userPuid** - Globalni jedinstveni identifikator korisnika za Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** - Verzija usluge (Kartica profila)

- **Data.workloadCulture** - Kultura postavljena u host aplikaciji

- **DeviceInfo_Id** - Globalni jedinstveni identifikator uređaja za uređaj

- **DeviceInfo_Make** - Brend operativnog sistema

- **DeviceInfo_Model** - Model uređaja

- **DeviceInfo_OsName** - Ime OS uređaja

- **DeviceInfo_OsVersion** - Verzija operativnog sistema

- **DeviceInfo_SDKUid** – Jedinstveno identifikuje uređaj iz perspektive telemetrije SDK–a.

#### <a name="officelivepersonacarduseractionsclosedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedExpandedPersonaCard

Evidentira se kada korisnik zatvori razvijenu karticu „Personalnost“. Koristi se za posmatranje kritičnih anomalija u stopama neuspešnih zatvaranja aktivne kartice „Personalnost“.

Prikupljaju se sledeća polja:

- **AppInfo_Id** – Ime host aplikacije

- **AppInfo_Version** – Verzija host aplikacije

- **Data.appContextId** – Slučajno generisani ID koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Ime upotrebljene usluge (Kartica profila)

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija, npr. „Outlook_Win32“

- **Data.eventId** – Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.exportName** – Ime događaja radnje korisnika koje ljudi mogu da pročitaju, npr. „ClosedExpandedPersonaCard“

- **Data.exportType** - Kategorija događaja za izvoz GDPR zahteva

- **Data.externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih kartica „Personalnost“ otvorenih u istoj podsesiji

- **Data.feature** – Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

- **Data.OTelJS.Version** – Verzija OTel sistema za evidenciju

- **Data.personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene personalnosti u sesiji

- **Data.properties** – Dodatni metapodaci prikupljeni za svaki događaj na sledeći način: *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje pojaviti u starijim izdanjima.]*

   - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId 
   - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId
   - **ClientTimeStamp** – vreme kada se desio događaj u vremenu Unix epohe
   - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId 

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog 

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** - Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili izolovan skup korisnika ili određenog zakupca.

- **Data.userPuid** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** – Verzija usluge (Kartica profila)

- **DeviceInfo_Id** – Globalni jedinstveni identifikator uređaja za uređaj

- **DeviceInfo_Make** – Brend operativnog sistema

- **DeviceInfo_Model** – Model uređaja

- **DeviceInfo.NetworkCost** – Ukazuje na cenu/tip mreže (ograničena, ograničena iznad granice itd.)

- **DeviceInfo_OsName** - Ime OS uređaja

- **DeviceInfo_OsVersion** – Verzija operativnog sistema

- **PipelineInfo.ClientCountry** – Pozivni broj za zemlju pošiljaoca, zasnovan na neočišćenoj IP adresi klijenta


#### <a name="officelivepersonacarduseractionsclosedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedPersonaCard

Beležimo kada korisnik zatvori „Persona“ karticu. Podaci se koriste za utvrđivanje da li se kartica pravilno zatvorila. 

Prikupljaju se sledeća polja: 

- **BatchId** - univerzalni jedinstveni identifikator ako je skup zahteva napravljen

- **Data.appContextId** – Slučajno generisani ID koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Naziv usluge koja se koristi (Kartica profila)

- **Data.AppInfo_Id** - Ime host aplikacije

- **Data.AppInfo_Version** - Verzija host aplikacije

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija

- **Data.eventId** – Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih kartica „Personalnost“ otvorenih u istoj podsesiji.

- **Data.feature** – Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

- **Data.OTelJS.Version** – Verzija OTel sistema za evidenciju

- **Data.personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene personalnosti u sesiji

- **Data.properties** – Dodatni metapodaci prikupljeni za svaki događaj na sledeći način: *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje pojaviti u starijim izdanjima.]*

  - **ClientTimeStamp** - Vreme u aplikaciji kada se evidentira događaj
  - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId
  - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId
  - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** – Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.userPuid** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** – Verzija usluge (Kartica profila)

- **Data_hostAppRing** - iskačući prsten na karti

- **Event_ReceivedTime** - vreme kada je događaj evidentiran u usluzi

#### <a name="officelivepersonacarduseractionsopenedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedExpandedPersonaCard

Evidentira se kada korisnik otvori proširenu karticu „Personalnost“. Koristi se za posmatranje kritičnih anomalija u stopama neuspešnih pokretanja Aktivne kartice „Personalnost“.

Prikupljaju se sledeća polja:

- **AppInfo_Id** – Ime host aplikacije

- **AppInfo_Version** – Verzija host aplikacije

- **Data.appContextId** – Slučajno generisani ID koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Ime upotrebljene usluge (Kartica profila)

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientScenario** – Za identifikovanje funkcije u aplikaciji odakle je otvorena kartica „Personalnost“

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija

- **Data.eventId** – Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih kartica „Personalnost“ otvorenih u istoj podsesiji.

- **Data.exportName** – Ime događaja korisničkog postupka koje ljudi mogu da pročitaju, npr. "OpenedPersonaCard"

- **Data.exportType** - Kategorija događaja za izvoz GDPR zahteva

- **Data.feature** - Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.hasPersonaInsightRing** – Uvidi iz sistema Office ili usluge LinkedIn mogu biti dostupni korisniku

- **Data.hostAppRing** – Prsten pomoću kojeg je aplikacija distribuirana

- **Data.immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

- **Data.OTelJS.Version** – Verzija OTel sistema za evidenciju

- **Data.personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene personalnosti u sesiji

- **Data.properties** – Dodatni metapodaci prikupljeni za svaki događaj na sledeći način: *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje pojaviti u starijim izdanjima.]*

  - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId 
  - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId
  - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId 

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.section** – Aktivni odeljak proširene kartice

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog 

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** – Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.userPuid** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** – Verzija usluge (Kartica profila)

- **DeviceInfo_Id** – Globalni jedinstveni identifikator uređaja za uređaj

- **DeviceInfo_Make** – Brend operativnog sistema

- **DeviceInfo_Model** – Model uređaja

- **DeviceInfo_OsName** - Ime OS uređaja

- **DeviceInfo_OsVersion** – Verzija operativnog sistema

- **DeviceInfo_SDKUid** – Jedinstveno identifikuje uređaj iz perspektive telemetrije SDK–a.

- **NetworkCost** - Označava tip mreže/vrstu troška (ograničena, ograničena iznad granice, itd.)

- **NetworkCountry** – Poštanski broj zemlje pošiljaoca, na osnovu neočišćene IP adrese klijenta


#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Evidentira se kada korisnik otvori Karticu „Personalnost“. Koristi se za posmatranje kritičnih anomalija u stopama neuspešnih pokretanja Aktivne kartice „Personalnost“.

Prikupljaju se sledeća polja:

- **Data.appContextId** – Slučajno generisani ID koji se koristi za identifikovanje različitih naloga u istoj aplikaciji

- **Data.AppInfo.Name** - Ime upotrebljene usluge (Kartica profila)

- **Data.bandwidthEstimateMbps** – Procena efektivnog propusnog opsega u MB/s

- **Data.cardCorrelationId** - Globalni jedinstveni identifikator za Karticu „Personalnost“

- **Data.cardPersonaCorrelationId** – Globalni jedinstveni identifikator za određenu personalnost prikazanu na kartici

- **SessionCorrelationId** - Globalni jedinstveni identifikator za sesiju aplikacije.

- **Data.clientType** – Tip uređaja na kom se pokreće aplikacija.

- **Data.eventId** – Identifikator imena događaja, npr. "LivePersonaCardRenderedAction"

- **Data.exportName** – Ime događaja korisničkog postupka koje ljudi mogu da pročitaju, npr. "OpenedPersonaCard"

- **Data.exportType** - Kategorija događaja za izvoz GDPR zahteva

- **Data.externalAppSessionCorrelationId** – Globalni jedinstveni identifikator za aplikaciju za identifikovanje svih kartica „Personalnost“ otvorenih u istoj podsesiji

- **Data.feature** - Koristi se za grupisanje različitih događaja iste funkcije (Kartica profila)

- **Data.hasPersonaInsightRing** – Uvidi iz sistema Office ili usluge LinkedIn mogu biti dostupni korisniku

- **Data.hostAppRing** – Prsten pomoću kojeg je aplikacija distribuirana

- **Data.immersiveProfileCorrelationId** – Globalni jedinstveni identifikator za sesiju prikaza proširenog profila

- **Data.OTelJS.Version** – Verzija OTel sistema za evidenciju

- **Data.personaCorrelationId** – Globalni jedinstveni identifikator za jedinstvene personalnosti u sesiji

- **Data.properties** – Dodatni metapodaci prikupljeni za svaki događaj na sledeći način: *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje pojaviti u starijim izdanjima.]*

    - **cardCorrelationId** - Duplikat gore navedenog Data.appContextId 
    - **cardPersonaCorrelationId** - Duplikat gore navedenog Data.cardCorrelationId
    - **consumerCorrelationId** - Duplikat gore navedenog Data.clientCorrelationId 
    - **networkEffectiveType** – Efektivan tip mrežne veze, npr. "Slow–2g online" da bi se identifikovalo da li je korisnik povezan sa Internetom u vreme prikazivanja Kartice „Personalnost“
    - **networkType** – Tip mrežnog povezivanja uređaja koji se koristi
    - **roundTripEstimateMs** – Procenjeni efektivni povratni put trenutne veze izražen u milisekundama

- **Data.region** – Geografska oblast pozadinska usluga kartice profila na koji se korisnik povezuje

- **Data.tenantAadObjectId** – Zakupac sa kojim je pretplata korisnika povezana. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.type** – Tip evidentiranih događaja, npr. praćenje, greška, događaj

- **Data.userAadObjectId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat broja Data.UserInfo.Id)

- **Data.UserInfo.Id** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog 

- **Data.UserInfo.MsaId** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog

- **Data.UserInfo.OMSTenantId** – Zakupac sa kojim je povezana pretplata korisnika. Omogućava nam da klasifikujemo probleme i otkrijemo da li je problem široko rasprostranjen ili je ograničen na skup korisnika ili određenog zakupca.

- **Data.userPuid** – Globalni jedinstveni identifikator korisnika za Enterprise Microsoft nalog (duplikat od Data.UserInfo.MsaId)

- **Data.version** – Verzija usluge (Kartica profila)

- **Data.viewType** – Definiše tip prikazane Kartice profila

- **Data.wasOpenedAsCompactCard** – Koristi se za identifikovanje toga da li je kartica prvobitno otvorena u kompaktnom prikazu

- **NetworkCost** – Označava tip mreže/vrstu troška (ograničena, ograničena iznad granice, itd.)

- **NetworkCountry** – Poštanski broj zemlje pošiljaoca, na osnovu nepročišćene IP adrese klijenta.

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


#### <a name="officeofficemobilefluidfluidfileoperations"></a>Office.OfficeMobile.Fluid.FluidFileOperations

Ovaj događaj se prikuplja za Office aplikacije kada se odvija fluidna datoteka. Podaci se koriste za praćenje stanja karakteristika i razumevanje korisničkog iskustva na osnovu operativnih informacija.

Prikupljaju se sledeća polja: 

- **FailureReason** - Ako je operacija bila neuspešna. Sadrži kod greške za neuspeh.

- **Rezultat** - Logička vrednost koja označava krajnji rezultat operacije.

- **Otkucajte** - tip operacije (na primer, "Otvori").


#### <a name="officeofficemobilepdfviewerpdffileoperations-on-android"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (na Android uređaju)

Događaj se prikuplja za Office aplikaciju za Android. On snima kad se izvršava operacija otvaranja, zatvaranja ili čuvanja pdf-a i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji pdf datoteka. Događaj nam omogućava da operacije otvaranja, zatvaranja i čuvanja pdf–a rade na očekivani način, kao i da se poboljšaju performanse operacija pdf datoteka.

Prikupljaju se sledeća polja:

- **Data_Doc_FileOpSessionID** – Jedinstveni ID za sesiju dokumenta

- **Data_ErrorCode** – greška u slučaju neuspelih otvaranja datoteka/neuspelih preuzimanja / otkazanih preuzimanja

- **Data_ErrorMessage** – relevantan kôd poruke-do-greške

- **Data_FailureReason** – U slučaju neuspešnog otvaranja, ovi enums definišu razlog neuspeha.

- **Data_FetchReason** – Opisuje način na koji je datoteka pribavljena (ručno, keširano, nije keširano) 

- **Data_FileGUID** – globalni identifikator datoteke koja se generiše nasumično

- **Data_FileLocation** – Lokacija na kojoj se nalazi datoteka, npr. Lokalna, ODSP, iCloud itd.

- **Data_FileOpenEntryPoint Ulazna tačka** – ulazna tačka za otvaranje datoteke

- **Data_FileSize** – Veličina datoteke na kojoj se odvija operacija

- **Data_NetworkRequestErrorResponse** – odgovor greške na mreži koja odgovara kôdu greške.

- **Data_NetworkRequestStage** – faza greške u slučaju preuzimanja pdf datoteke iz oblaka.

- **Data_OpenMode** – U kojem režimu je PDF otvoren, npr. 0: Režim prikaza, 2: Režim potpisivanja

- **Data_PageCount** – Prebrojavanje stranica u PDF datoteci.

- **Data_PasswordProtected** – Obeleživač koji nam pokazuje da li je datoteka zaštićena lozinkom ili ne.

- **Data_ProviderApp** – trenutno obezbeđena aplikacija dobavljača samo u slučaju aktiviranja datoteka 

- **Data_ReadOnly** – Obeleživač koji govori da li je datoteka samo za čitanje ili nije.

- **Data_Result** – Status operacije koja se izvršava, npr. true:uspeh, false:neuspeh

- **Data_Type** – Tip operacije datoteke (otvaranje, zatvaranje ili čuvanje) 

#### <a name="officeofficemobilepdfviewerpdffileoperations-on-ios"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (na iOS uređaju)

Događaj se prikuplja za Office aplikaciju za iOS. On snima kad se izvršava operacija otvaranja, zatvaranja ili čuvanja pdf-a i koristi se za razumevanje korisnika i određivanje prioriteta korisničkog iskustva na osnovu informacija o operaciji pdf datoteka. Događaj nam omogućava da operacije otvaranja, zatvaranja i čuvanja pdf–a rade na očekivani način, kao i da se poboljšaju performanse operacija pdf datoteka. 

- **Data_Doc_FileOpSessionID** – Jedinstveni ID za sesiju dokumenta 

- **Data_ErrorCode** – greška u slučaju neuspelih otvaranja datoteka/neuspelih preuzimanja / otkazanih preuzimanja 

- **Data_ErrorMessage** – Relevantan kôd poruke-do-greške 

- **Data_FailureReason** – U slučaju neuspešnog otvaranja, ova nabrajanja definišu razlog neuspeha. 

- **Data_FetchReason** – Opisuje način na koji je datoteka pribavljena (ručno, keširano, nije keširano)

- **Data_FileGUID** – globalni identifikator datoteke koja se generiše nasumično

- **Data_FileLocation** – Lokacija na kojoj se nalazi datoteka (Lokalna, ODSP, iCloud itd.) 

- **Data_FileOpenEntryPoint Ulazna tačka** – Ulazna tačka za otvaranje datoteke 

- **Data_FileSize** – Veličina datoteke na kojoj se odvija operacija 

- **Data_OpenMode** – U kojem režimu je PDF otvoren (0: Režim prikaza, 2: Režim potpisivanja) 

- **Data_PageCount** – Prebrojavanje stranica u PDF datoteci.

- **Data_PasswordProtected** – Obeleživač koji nam pokazuje da li je datoteka zaštićena lozinkom ili ne. 

- **Data_ProviderApp** – Trenutno obezbeđena aplikacija dobavljača samo u slučaju aktiviranja datoteka 

- **Data_ReadOnly** – Obeleživač koji govori da li je datoteka samo za čitanje ili nije.

- **Data_Result** – Status operacije koja se izvršava, (true:uspeh, false:neuspeh) 

- **Data_Type** – Tip operacije datoteke (otvaranje, zatvaranje ili čuvanje)


#### <a name="officeonenoteandroidappnavigationnavigationuistatechanged"></a>Office.OneNote.Android.App.Navigation.NavigationUIStateChanged

*[Ovaj događaj je prethodno nazvan OneNote.App.Navigation.NavigationUIStateChanged.]*

Ovaj događaj prikuplja kritični signal koji se koristi da bi se osiguralo da korisnici usluge OneNote mogu uspešno da se kreću kroz aplikaciju.  Telemetrija se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. 

Prikupljaju se sledeća polja: 

- **IS_SPANNED** – Označava da li je aplikacija u raširenom režimu. Ovo se konkretno evidentira za uređaje koji se mogu preklopiti.

- **NEW_STATE** – Označava stanje aplikacije odmah nakon navigacije

- **OLD_STATE** – Označava državu aplikacije neposredno pre navigacije

#### <a name="officeonenoteandroidcanvaspageopened"></a>Office.OneNote.Android.Canvas.PageOpened

*[Ovaj događaj je prethodno nazvan OneNote.Canvas.PageOpened.]*

Signal koji se koristi za beleženje kada je stranica otvorena.  Telemetrija se koristi za nadgledanje, otkrivanje i rešavanje problema tokom otvaranja stranice u aplikaciji OneNote

Prikupljaju se sledeća polja: 

- **JOT_ID** - objekat otvorene stranice

- **TIME_TAKEN_IN_MS** - vreme utrošeno na otvaranje stranice

#### <a name="officeonenoteandroidcapturenewnotenewnotetaken"></a>Office.OneNote.Android.Capture.NewNote.NewNoteTaken

*[Ovaj događaj je prethodno nazvan OneNote.Capture.NewNote.NewNoteTaken.]*

Ovaj signal koristi se za obezbeđivanje aplikacije korisnika u OneNote Android aplikaciji, beležnice su propisno obezbeđene i korisnik je uspešno kreirao novu napomenu.  Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge.

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeonenoteandroidlenssdkofficelenslaunched"></a>Office.OneNote.Android.LensSDK.OfficeLensLaunched

*[Ovaj događaj je prethodno nazvan OneNote.LensSDK.OfficeLensLaunched]*

Ovaj događaj prikuplja kritični signal koji se koristi da bi se Office Lens ispravno pokrenuo.  Telemetrija se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. 

Prikupljaju se sledeća polja: 

- **CAPTURE_MODE** – Ukazuje na režim u kojem je OfficeLens pokrenut.  Može da bude podrazumevani, uređivanje, brzo umetanje ili uvoz video zapisa.

- **ERROR_CODE** – Označava kôd greške pri pokretanju u slučaju da je došlo do greške prilikom pokretanja.

- **IMAGE_COUNT** – Označava koliko slika je snimljeno

- **LAUNCH_REASON** – Ukazuje na tok u okviru kojeg je pokrenut Office Lens. Može da bude iznad ekrana za zaključavanje ili putem kamere ili opcija galerije u lepljivim beleškama ili putem OneNote podloge itd.

#### <a name="officeonenoteandroidmessagebarmessagebarclicked"></a>Office.OneNote.Android.MessageBar.MessageBarClicked

*[Ovaj događaj je prethodno nazvan OneNote.MessageBar.MessageBarClicked.]*

Signal koji se koristi za označavanje problema prilikom korišćenja trake sa porukama.  Telemetrija se koristi za nadgledanje, otkrivanje i rešavanje problema tokom interakcije sa trakom sa porukama.

Prikupljaju se sledeća polja: 

- **Message_Bar_Type** – Daje informaciju o tome da li korisnik koristi staru ili novu traku sa porukama.

- **Message_Type** – Daje ID poruke o grešci

#### <a name="officeonenoteandroidstickynotesnotecreated"></a>Office.OneNote.Android.StickyNotes.NoteCreated
 
Kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji.   Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteCreated radnja koju aktivira korisnik.

- **NoteLocalId** – Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenoteandroidstickynotesnoteviewed"></a>Office.OneNote.Android.StickyNotes.NoteViewed

Kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da prikazuju beleške u aplikaciji.  Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da prikazuju beležnice, to bi izazvalo ozbiljan incident.

Prikupljaju se sledeća polja:

- **HasImages** - Zastavica koja ukazuje na to da li prikazana beleška sadrži uskladištene slike.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteViewed radnja koju aktivira korisnik.

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenotecanvasinkinkstrokelogger"></a>Office.OneNote.Canvas.Ink.InkStrokeLogger 

Ovaj događaj se koristi za otkrivanje i dijagnostikovanje visokofrekventne greške sa kojom korisnik može da se susretne pri korišćenju funkcije Ink.  Ovo će se koristiti za utvrđivanje najprikladnijeg načina za rešavanje ovog problema. 

Prikupljaju se sledeća polja:

- **CurrentCanvasZoomFactor** - Trenutni faktor zumiranja podloge.

- **CurrentNotebook** – Identifikator trenutno aktivne beležnice.

- **CurrentPage** – Identifikator trenutno aktivne stranice.

- **CurrentSection** – Identifikator trenutno aktivnog odeljka.

- **DefaultCanvasZoomFactor** - Podrazumevani faktor zumiranja podloge.

- **InkStrokeCount** - Zbir poteza mastilom od poslednje evidencije.

- **InkStrokeWithLayerInkEffect** - Broj poteza mastilom sa slojevitim efektom od poslednje evidencije.

- **InkStrokeWithoutPressureCount** - Broj poteza mastilom bez pritiska od poslednje evidencije.

- **InkStrokeWithPencilInkEffect** - Broj poteza mastilom sa efektom olovke od poslednje evidencije.

- **InkStrokeWithTilt** - Broj poteza perom sa nagibom od poslednje evidencije.

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

### <a name="officeonenotesigscriticalerrorencountered"></a>Office.OneNote.SIGS.CriticalErrorEncountered

Ovim događajem se beleži ključni signal koji se koristi za nadziranje stanja usluge Signal Ingestion Service (SIG) evidentiranjem svake kritične pogreške. Kritične greške mogu da blokiraju ceo SIGS, a to će nam pomoći da vidimo svaki takav problem čim korisnici na njih naiđu. 

Bez toga zavisimo od toga da korisnici prijavljuju probleme koje imaju. Odsutnost takve telemetrije mogla bi znatno povećati vreme rešavanja takvih problema.

Prikupljaju se sledeća polja: 

- **ErrorCode** – kôd problema na koji je naišao korisnik.


#### <a name="officeonenotestickynotesnotecreated-on-ios-onenotestickynotesnotecreated-on-android"></a>Office.OneNote.StickyNotes.NoteCreated (on iOS), OneNote.StickyNotes.NoteCreated (on Android)

Ovo je kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji.  Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteCreated radnja koju aktivira korisnik.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenotestickynotesnoteviewed-on-ios-onenotestickynotesnoteviewed-on-android"></a>Office.OneNote.StickyNotes.NoteViewed (on iOS), OneNote.StickyNotes.NoteViewed (on Android)

Ovo je kritičan signal koji se koristi da prati da li korisnici Lepljivih beležaka mogu da kreiraju beleške u aplikaciji.  Telemetrija se koristi za obezbeđivanje otkrivanja kritične regresivne OneNote aplikacije i ispravnost usluge. Ako korisnici ne mogu da naprave belešku, to bi izazvalo incident krajnje ozbiljnosti.

Prikupljaju se sledeća polja:

- **HasImages** - Zastavica koja ukazuje na to da li prikazana beleška sadrži uskladištene slike.

- **IsExportable** - Zastavica koja ukazuje na to da li je ovaj događaj bio rezultat delovanja korisnika ili ne. Treba da bude postavljeno na vrednost "ispravno" pošto je NoteViewed radnja koju aktivira korisnik.

- **NoteLocalId** - Jedinstveni identifikator koji se jasno razlikuje od drugih dodeljuje se belešci kada korisnik kreira belešku unutar aplikacije.

- **StickyNotes-SDKVersion** - Broj verzije koji označava verziju aplikacije Lepljive beleške koje korisnik koristi. Omogućava nam da utvrdimo koje verzije proizvoda ispoljavaju problem tako da možemo ispravno da damo prioritet rešavanju tog problema.


#### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ovaj događaj evidentira rezultat sinhronizovanja sveske. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote.
 
Prikupljaju se sledeća polja

- **CachedError_Code** – numerisani ili alfanumerički kod koji se koristi za određivanje prirode keširane greške i/ili zašto se ona dogodila
    
- **CachedError_Description** –opis keširane greške

- **CachedError_Tag** – ukazuje na to gde u kodu se javlja keširana greška

- **CachedError_Type** – tip keširane greške, npr. Win32Error itd.

- **ExecutionTime** - vreme u milisekundama potrebno za kopiranje beležnice

- **Gosid** -globalni ID prostora objekta

- **IdentityType** –tip identiteta, npr. Windows Live, org ID itd.

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

- **SyncDestinationType** –tip odredišnog sinhronizovanja, npr. OneDrive ili SharePoint Online

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

  - **IzborPodatakaNaloga** – izvor postavki za nalog (npr. automatsko otkrivanje, GuessSmart, automatsko otkrivanje itd.)

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

Prikuplja rezultat kreiranja nove prodavnice (sa tipom i verzijom), kao i kôd rezultata. Aktivno pratimo ovaj događaj da bismo pratili ispravno funkcionisanje mogućnosti da korisnik sinhronizuje i skladišti e–poštu lokalno, arhivira e–poštu (u PST) ili da koristi grupe.

Prikupljaju se sledeća polja:

  - **Standardna HVA aktivnost** sa prilagođenim korisnim podacima

  - **TipSkladišta** – tip kreiranog skladišta OST ili PST/NST

  - **VerzijaSkladišta** – Verzija kreiranog skladišta Malo/Veliko/Tardis

#### <a name="officeoutlookmacaccountaddworkflow"></a>Office.Outlook.Mac.AccountAddWorkflow

Rezultat dodavanja naloga u programu Outlook. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja. Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

Prikupljaju se sledeća polja:

- **AccountConfigMethod** – metod konfigurisanja Naloga

- **AccountType** – Tip naloga koji se konfiguriše.

- **AccountWorkflowSession** – sesiji u kojoj se pokušava izvršiti tok naloga

- **Sessionduration** – trajanje sesije 

- **ThreadId** - identifikator za nit


#### <a name="officeoutlookmacaccountonboardingflow"></a>Office.Outlook.Mac.AccountOnboardingFlow

Rezultat dodavanja naloga u programu Outlook pomoću novog iskustva konfigurisanja naloga. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja. Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

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

Rezultat brisanja naloga u programu Outlook. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja. Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. Cilj nam je da sa svakim izdanjem poboljšamo stopu uspeha. 

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

  - **Data\_Doc\_IsOcsSupported:bool –** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Proverava da li se dokument otvara iz lokalnog keša

  - **Data\_Doc\_IsSyncBacked:bool -** Proverava da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long –** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType –**  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string –** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_DocHasStorage:bool -** Da li ovaj dokument ima lokalno skladište?

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

  - **Podaci\_IsDocAutoSaveable:bool -** Da li se prezentacija može automatski sačuvati?

  - **Podaci\_IsDocDirty:bool -** Da li prezentacija sadrži promene koje još nisu sačuvane?

  - **Podaci\_IsNewDoc:bool -** Da li se radi o novom ili postojećem dokumentu? 

  - **Podaci\_IsRecoveredDoc:bool -** Da li se radi o spasenom dokumentu? (Ako je došlo do pada prethodne sesije, pokazujemo okno za oporavak dokumenta prilikom sledeće sesije)

  - **Podaci\_NewDocDiscarded:bool -** Da li je nova prezentacija odbačena bez čuvanja?

  - **Podaci\_OCSClosingDlgCanceled:bool -** Ako je otpremanje na čekanju na OCS dok korisnik zatvori dokument, pojaviće se dijalog sa porukom korisniku da sačeka. Koju opciju je odabrao korisnik?

  - **Podaci\_OCSClosingDlgExpired:bool -** Da li je isteklo vreme za dijalog (nakon 1 minuta) samo od sebe?

  - **Podaci\_OCSClosingStatus:long –** Koji je konačni status OCS (u CSI, može se zatvoriti, u OCS prelazu, u CSI prelazu, itd.)

  - **Podaci\_OCSClosingWaitDurationMS:long -** Koliko je vremena korisnik morao da čeka na OCS otpremanje?

  - **Podaci\_OCSHandleTransitionResult:long -** Unapred definisan skup vrednosti rezultata prelaza obavljenog tokom zatvaranja (već pokušano, nastavi sa zatvaranjem, itd).

  - **Podaci\_ServerDocId:string -** GUID za jedinstveno identifikovanje dokumenta

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Podaci\_UserContinuedZRTClose:bool –** Kada je prikazan dijalog prilikom zatvaranja, da li je korisnik izabrao da „Nastavi” sa zatvaranjem?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Prikuplja se kada PowerPoint kreira novu prezentaciju.  Uključuje metriku za uspeh, neuspeh i performanse.

Ove informacije su potrebne da bismo proverili da li PowerPoint može uspešno da kreira datoteke bez degradacije u performansama.

Prikupljaju se sledeća polja:

  - **TipNovogDokumenta** – Da li je novi dokument kreiran iz predloška ili kreiran prazan?

  - **FLifeguarded** – Da li dokument ima mogućnost samokorigovanja (funkcija koja sama ispravlja greške u dokumentu bez upita za korisnika)?

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Prikupljeno kada PowerPoint otvara prezentacije. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju na kraju procesa otvaranja.

Microsoft koristi te podatke da bi se uverili da funkcija radi kao što je očekivano i ne postoji bilo kakva degradacija pri otvaranju prezentacija.

Prikupljaju se sledeća polja:

  - **Data\_AntiVirusScanMethod:long -** Unapred definisani skup vrednosti za tip antivirusnog skeniranja (IOAV, AMSI, nijedan, itd.)

  - **Data\_AntiVirusScanStatus:long -** Unapred definisani skup vrednosti za antivirusno skeniranje koje se izvršava za svaki otvoreni dokument (nisu otkrivene pretnje, neuspelo, otkriven je malver, itd.)

  - **Podaci\_CloseAndReopen:bool -** Da li je ovaj dokument zatvoren i ponovo otvoren?

  - **Data_ClpDocHasDrmDoc:bool** – Da li dokument ima DRM dokument

  - **Data_ClpDocHasIdentity:bool**  – Da li dokument ima informacije o identitetu (koje se koriste za preuzimanje i podešavanje oznaka osetljivosti)

  - **Data_ClpDocHasSessionMetadata:bool** – Da li dokument ima metapodatke radne oznake osetljivosti iz sesije

  - **Data_ClpDocHasSpoMetadata:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IMetadataCache-a

  - **Data_ClpDocHasSpoPackage:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IPackage-a

  - **Data_ClpDocIsProtected:bool** – Da li je dokument zaštićen putem IRM ili nije

  - **Data_ClpDocMetadataSource:int** – Prebrojavanje koje označava odakle su metapodaci oznake osetljivosti (IRM, OPC deo, SharePoint itd.)

  - **Data_ClpDocNeedsUpconversion:bool** – Da li dokument mora da konvertuje naviše podatke oznake osetljivosti iz custom.xml dela

  - **Data_ClpDocNumFailedSetLabels:int** – Ukupan broj oznaka osetljivosti čije podešavanje na dokumentu nije uspelo

  - **Data_ClpDocSessionMetadataDirty:bool** – Da li dokument ima metapodatke radne oznake osetljivosti koji su nesređeni

  - **Data_ClpDocWasInTrustBoundary:bool** – Da li je dokument bio u granicama poverenja (da li je dozvoljavao koautorstvo nad dokumentima koje štite oznake osetljivosti)

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

  - **Data\_Doc\_IsOcsSupported:bool –** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Da li se dokument otvara iz lokalnog keša?

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long –** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType –**  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string –** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_ExecutionCount:long -** Koliko puta se izvršava IncOpen protokol pre izvršavanja ovog protokola (OpenComplete)

  - **Data\_FailureComponent:long -** Unapred definisani skup vrednosti za komponentu koja je izazvala neuspeh protokola (neusaglašenost, CSI, unutrašnja, itd.)

  - **Data\_FailureReason:long –** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data_FullDownloadRoundTripCount: Long –** Broj povratnih odziva servera potrebnih za preuzimanje celog dokumenta.
  
  - **Data_IsProtocolRunInIncOpenMode: Bool –** Da li je protokol bio pokrenut za postepeno preuzimanje u kome su delovi dokumenta preuzeti nakon što je dokument prvobitno prikazan korisniku.

  - **Podaci\_MethodId:long -** Interno koji red koda je poslednji koji se izvršio

  - **Data\_StopwatchDuration:long -** Ukupno vreme aktivnosti

  - **Podaci\_TimeToEdit:long -** Koliko vremena je bilo potrebno da bi dokument stekao mogućnost uređivanja

  - **Podaci\_TimeToView:long -** Vreme utrošeno za prikaz prvog slajda dokumenta

  - **Podaci\_UnhandledException:bool -** Da li je bilo nekontrolisanih izvornih izuzetaka?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Prikuplja se kad god PowerPoint vrši čuvanje pomoću moderne putanje kôda. Uključuje rezultat tipa uspeh ili neuspeh za metriku performansi pri čuvanju i odgovarajuće metapodatke dokumenta.  Greške pri čuvanju mogu dovesti do gubitka podataka. Microsoft koristi ove podatke da obezbedi da funkcija radi kao što je očekivano i da se uspešno vrši očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemetryResult:long -** Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Podaci\_Dokument\_\* polja)? Ako ne, zašto?

  - **Podaci\_BeforeSaveEvent:long -** Vreme utrošeno da se podigne dokument pre događaja čuvanja

  - **Podaci\_CheckDownRevSaveTimeMS:long -** Vreme utrošeno za proveru revizije

  - **Podaci\_CheckMacroSaveTimeMS:long -** Vreme utrošeno za čuvanje makroa

  - **Podaci\_ClearAutoSaveTimeMS:long -** Vreme utrošeno da se ukloni zastavica za automatsko čuvanje

  - **Podaci\_ClearDirtyFlagTimeMS:long -** Vreme utrošeno da se ukloni zastavica za nesređeni dokument

  - **Podaci\_CloneDocumentTimeMS:long -** Vreme utrošeno na kloniranje dokumenta pre početka čuvanja

  - **Data_ClpDocHasDrmDoc:bool** – Da li dokument ima DRM dokument

  - **Data_ClpDocHasIdentity:bool**  – Da li dokument ima informacije o identitetu (koje se koriste za preuzimanje i podešavanje oznaka osetljivosti)

  - **Data_ClpDocHasSessionMetadata:bool** – Da li dokument ima metapodatke radne oznake osetljivosti iz sesije

  - **Data_ClpDocHasSpoMetadata:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IMetadataCache-a

  - **Data_ClpDocHasSpoPackage:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IPackage-a

  - **Data_ClpDocIsProtected:bool** – Da li je dokument zaštićen putem IRM ili nije

  - **Data_ClpDocMetadataSource:int** – Prebrojavanje koje označava odakle su metapodaci oznake osetljivosti (IRM, OPC deo, SharePoint itd.)

  - **Data_ClpDocNeedsUpconversion:bool** – Da li dokument mora da konvertuje naviše podatke oznake osetljivosti iz custom.xml dela

  - **Data_ClpDocNumFailedSetLabels:int** – Ukupan broj oznaka osetljivosti čije podešavanje na dokumentu nije uspelo

  - **Data_ClpDocSessionMetadataDirty:bool** – Da li dokument ima metapodatke radne oznake osetljivosti koji su nesređeni

  - **Data_ClpDocWasInTrustBoundary:bool** – Da li je dokument bio u granicama poverenja (da li je dozvoljavao koautorstvo nad dokumentima koje štite oznake osetljivosti)

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

  - **Data\_Doc\_IsOcsSupported:bool –** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Proverava da li se dokument otvara iz lokalnog keša

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long -** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long –** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType –**  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** Proverava da li je server zasnovan na verziji Office14, Office15, Office16

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long-** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš za celu URL adresu dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string –** Identifikator usluge WOPI, npr. „Dropbox“

  - **Podaci\_DurationUAEOnSaveStartedMs:long -** Vreme potrebno za izlaz iz nepoznate aplikacije tokom čuvanja

  - **Podaci\_EnsureSaveTransactionTimeMS:long –** Vreme potrebno da se obezbedi kreiranje transakcije čuvanja ako već ne postoji

  - **Data\_FailureComponent:long -** Unapred definisani skup vrednosti za komponentu koja je izazvala neuspeh protokola (neusaglašenost, CSI, unutrašnja, itd.)

  - **Data\_FailureReason:long –** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

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

- **Data_ClpDocHasDrmDoc:bool** – Da li dokument ima DRM dokument

- **Data_ClpDocHasIdentity:bool**  – Da li dokument ima informacije o identitetu (koje se koriste za preuzimanje i podešavanje oznaka osetljivosti)

- **Data_ClpDocHasSessionMetadata:bool** – Da li dokument ima metapodatke radne oznake osetljivosti iz sesije

- **Data_ClpDocHasSpoMetadata:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IMetadataCache-a

- **Data_ClpDocHasSpoPackage:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IPackage-a

- **Data_ClpDocIsProtected:bool** – Da li je dokument zaštićen putem IRM ili nije

- **Data_ClpDocMetadataSource:int** – Prebrojavanje koje označava odakle su metapodaci oznake osetljivosti (IRM, OPC deo, SharePoint itd.)

- **Data_ClpDocNeedsUpconversion:bool** – Da li dokument mora da konvertuje naviše podatke oznake osetljivosti iz custom.xml dela

- **Data_ClpDocNumFailedSetLabels:int** – Ukupan broj oznaka osetljivosti čije podešavanje na dokumentu nije uspelo

- **Data_ClpDocSessionMetadataDirty:bool** – Da li dokument ima metapodatke radne oznake osetljivosti koji su nesređeni

- **Data_ClpDocWasInTrustBoundary:bool** – Da li je dokument bio u granicama poverenja (da li je dozvoljavao koautorstvo nad dokumentima koje štite oznake osetljivosti)

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

- **Data_DstDoc_IOFlags:long** – Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_DstDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)
    
- **Data_DstDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_DstDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_DstDoc_IsOcsSupported:bool** – Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_DstDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_DstDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju
    
- **Data_DstDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_DstDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_DstDoc_NumberCoAuthors:long** – Broj koautora u trenutku otvaranja dokumenta

- **Data_DstDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_DstDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_DstDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_DstDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_DstDoc_ServerVersion:long** – proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_DstDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_DstDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_DstDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_DstDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_DstDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_DstDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_DstDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_DstDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_DstDoc_WopiServiceId:string** – WOPI Service Identifier, na primer "Dropbox"

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

- **Data_SrcDoc_IOFlags:long** – Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_SrcDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_SrcDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_SrcDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_SrcDoc_IsOcsSupported:bool** – Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_SrcDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_SrcDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_SrcDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike itd.)

- **Data_SrcDoc_NumberCoAuthors:long** – Broj koautora u trenutku otvaranja dokumenta

- **Data_SrcDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_SrcDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_SrcDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_SrcDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_SrcDoc_ServerVersion:long** – proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_SrcDoc_SessionId:long** - Generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_SrcDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_SrcDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_SrcDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_SrcDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_SrcDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_SrcDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_SrcDoc_WopiServiceId:string** – WOPI Service identifikator, na primer"Dropbox"

- **Data_StopwatchDuration:long** - Ukupno vreme aktivnosti

- **Data_TypeOfSaveDialog:long** - unapred definisani skup vrednosti dijaloga (RUN_SAVEAS_DLG,RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Data_WaitForSaveOrMergeSuccess:bool** – SaveAs je uspeo tokom čekanja na čuvanje ili objedinjavanje u pozadini.
 
- **Data_WaitForSaveOrMergeTimeout:long** – SaveAs je istekao tokom čekanja na čuvanje ili objedinjavanje u pozadini.

- **DstDoc -** Nova lokacija dokumenta 

- **SrcDoc -** Prvobitna lokacija dokumenta


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Prikuplja se kad god PowerPoint vrši čuvanje pomoću zastarele putanje kôda. Uključuje rezultat tipa uspeh ili neuspeh za metriku performansi pri čuvanju i odgovarajuće metapodatke dokumenta.  Greške pri čuvanju mogu dovesti do gubitka podataka.  Microsoft koristi ove podatke da obezbedi da funkcija radi kao što je očekivano i da se uspešno vrši očuvanje korisničkog sadržaja.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemetryResult:long** - Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Data_Doc_* fields)? Ako ne, zašto?

- **Data_ClpDocHasDrmDoc:bool** – Da li dokument ima DRM dokument

- **Data_ClpDocHasIdentity:bool**  – Da li dokument ima informacije o identitetu (koje se koriste za preuzimanje i podešavanje oznaka osetljivosti)

- **Data_ClpDocHasSessionMetadata:bool** – Da li dokument ima metapodatke radne oznake osetljivosti iz sesije

- **Data_ClpDocHasSpoMetadata:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IMetadataCache-a

- **Data_ClpDocHasSpoPackage:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IPackage-a

- **Data_ClpDocIsProtected:bool** – Da li je dokument zaštićen putem IRM ili nije

- **Data_ClpDocMetadataSource:int** – Prebrojavanje koje označava odakle su metapodaci oznake osetljivosti (IRM, OPC deo, SharePoint itd.)

- **Data_ClpDocNeedsUpconversion:bool** – Da li dokument mora da konvertuje naviše podatke oznake osetljivosti iz custom.xml dela

- **Data_ClpDocNumFailedSetLabels:int** – Ukupan broj oznaka osetljivosti čije podešavanje na dokumentu nije uspelo

- **Data_ClpDocSessionMetadataDirty:bool** – Da li dokument ima metapodatke radne oznake osetljivosti koji su nesređeni

- **Data_ClpDocWasInTrustBoundary:bool** – Da li je dokument bio u granicama poverenja (da li je dozvoljavao koautorstvo nad dokumentima koje štite oznake osetljivosti)

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

- **Data_Doc_IOFlags:long** – Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_Doc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_Doc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_Doc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_Doc_IsOcsSupported:bool** – Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_Doc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_Doc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_Doc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_Doc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_Doc_NumberCoAuthors:long** – Broj koautora u trenutku otvaranja dokumenta

- **Data_Doc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_Doc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_Doc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

- **Data_Doc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_Doc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_Doc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI) 

- **Data_Doc_ServerVersion:long** – proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_Doc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_Doc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_Doc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_Doc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_Doc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_Doc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_Doc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_Doc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_Doc_WopiServiceId:string** – WOPI Service identifikator, na primer "Dropbox"

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

- **Data_DstDoc_IOFlags:long** – Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_DstDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

- **Data_DstDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_DstDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_DstDoc_IsOcsSupported:bool** – Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_DstDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_DstDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_DstDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_DstDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_DstDoc_NumberCoAuthors:long** – Broj koautora u trenutku otvaranja dokumenta

- **Data_DstDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_DstDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje itd.)

- **Data_DstDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_DstDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_DstDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_DstDoc_ServerVersion:long** – proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_DstDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_DstDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_DstDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_DstDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_DstDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_DstDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_DstDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_DstDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_DstDoc_WopiServiceId:string** – WOPI Service Identifier, na primer "Dropbox"

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

- **Data_SrcDoc_IOFlags:long** – Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

- **Data_SrcDoc_IrmRights:long** - Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)
    
- **Data_SrcDoc_IsCloudCollabEnabled:bool** - Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

- **Data_SrcDoc_IsIncrementalOpen:bool** - Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

- **Data_SrcDoc_IsOcsSupported:bool** – Da li dokument podržava koautorstvo putem nove OCS usluge

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** - Proverava da li se dokument otvara iz lokalnog keša

- **Data_SrcDoc_IsSyncBacked:bool** - Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

- **Data_SrcDoc_Location:long** - Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

- **Data_SrcDoc_LocationDetails:long** - Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

- **Data_SrcDoc_NumberCoAuthors:long** – Broj koautora u trenutku otvaranja dokumenta

- **Data_SrcDoc_PasswordFlags:long** - Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

- **Data_SrcDoc_ReadOnlyReasons:long** - Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

- **Data_SrcDoc_ResourceIdHash:string** - Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerDocId:string** - nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

- **Data_SrcDoc_ServerProtocol:long** - Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)

- **Data_SrcDoc_ServerType:long** - Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

- **Data_SrcDoc_ServerVersion:long** – proverava da li je server zasnovan na verziji Office14, Office15 ili Office16

- **Data_SrcDoc_SessionId:long** - generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

- **Data_SrcDoc_SharePointServiceContext:string** - Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

- **Data_SrcDoc_SizeInBytes:long** - Veličina dokumenta u bajtovima

- **Data_SrcDoc_SpecialChars:long** - Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

- **Data_SrcDoc_StorageProviderId:string** - Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

- **Data_SrcDoc_StreamAvailability:long** - Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

- **Data_SrcDoc_UrlHash:string** -Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** - tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

- **Data_SrcDoc_WopiServiceId:string** – WOPI Service identifikator, na primer"Dropbox"

- **Data_StopwatchDuration:long** - Ukupno vreme aktivnosti

- **Data_TypeOfSaveDialog:long** - unapred definisani skup vrednosti dijaloga (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Doc** - trenutni dokument za čuvanje

- **DstDoc**- Nova lokacija dokumenta (u slučaju opcije „Sačuvaj kao“)

- **SrcDoc**- Prvobitna lokacija dokumenta (u slučaju opcije „Sačuvaj kao“)


#### <a name="officepowerpointpptiosrehearseview"></a>Office.PowerPoint.PPT.IOS.RehearseView 

Ovaj događaj označava da je korisnik prekinuo probnu sesiju. Podaci se koriste u kombinaciji sa Office.PowerPoint.IOS.Android.RehearseView.StartSession kao prvi pokazatelj bilo kakvih rušenja ili grešaka sa kojima se suočava korisnik.  
 
Prikupljaju se sledeća polja:

- **Vreme kreiranja veze** – vreme potrošeno na kreiranje veza na strani usluge.

- **CountDownAlertTime** – Vreme za koje je prikazano upozorenje za odbrojavanje.

- **CountdownInitTime** – Vreme između dovršenog učitavanja projekcije slajdova i početka odbrojavanja.

- **CritiqueSummary** – Rezime svih kritika koje su korisnici videli uz svoje brojeve.

- **ExitEventCode** – Kôd za identifikaciju u kom scenariju korisnik izlazi iz probe, bilo da je reč o scenariju greške ili uspešnom izlasku

- **FRETime** – Vreme za koje je FRE ekran počeo da prikazuje dok ga korisnik nije odbacio.

- **MicrophonePermissionTime** – Vreme tokom kojeg se prikazivalo upozorenje za dozvolu mikrofona dok korisnik nije izabrao jednu od opcija.

- **PauseRehearsingCount** – Prebrojavanje koliko je puta korisnik kliknuo na pauziranje probe

- **RehearsalInitTime** – Vreme koje je potrebno da se proba pokrene

- **ResumeRehearsingCount** – Prebrojavanje koliko je puta korisnik kliknuo na nastavak probe

- **Sessionid** – ovo je ID sesije prednjih vrata.  Ovo se koristi za otklanjanje grešaka u evidencijama usluge.

- **SlideshowViewLoadTime** – Vreme potrebno za učitavanje projekcije slajdova.


#### <a name="officepowerpointpptiosrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.IOS.RehearseView.RehearsalSummaryPage

Događaj se pokreće kada stranica za rezime završi sa učitavanjem. Ovaj događaj nam pomaže da uhvatimo performanse stranice rezimea. Pokazuje koliko je vremena potrebno da se stranica sa rezimeom probe učita kod klijenta. Potrebno je da se zadrži funkcija performanta.  

Prikupljaju se sledeća polja: 

- **PayloadCreationTime** – vreme koje je potrebno u milisekundama za kreiranje opterećenja.  

- **PostUrlCallTime** – vreme koje je potrebno u milisekundama za slanje naknadnog URL poziva. 

- **RehearseSessionId** – ovo je ID sesije prednjih vrata. Ovo možemo da koristimo za otklanjanje grešaka u evidencijama usluge.  

- **SummaryPageErrorReceived** – to je Bulova vrednost koja pokazuje da li je primljena stranica rezimea ili je došlo do greške.

- **SummaryPageHtmlLoadTime** – to je vreme u milisekundama koje je potrebno za učitavanje summarypageHtml. 

- **SummaryPageLoadStartTime** – to je vreme u milisekundama za primanje prvog odgovora sa servera. 

- **SummaryPageLoadTime** – vreme potrebno za učitavanje stranice rezimea. Ovo obuhvata vreme kreiranja korisnog tereta. 

- **ThumbnailsCount** – to je ukupan broj sličica koje će biti deo stranice rezimea. 


#### <a name="officepowerpointpptiosrehearseviewstartsession"></a>Office.PowerPoint.PPT.IOS.RehearseView.StartSession 
 
Ovaj događaj se pokreće kada korisnik klikne na početnu sesiju. Ovaj događaj nam pomaže da utvrdimo koliko korisnika koristi funkciju „Trener za izlagače“ na iOS uređaju. Kada se kombinuje sa Office.PowerPoint.PPT.iOs.RehearseView reći će nam koliko korisnika je uspešno obavilo probnu sesiju a koliko nije moglo. Ovo je prvi pokazatelj padova ili grešaka u funkciji.

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Sakuplja svaki put kada se dovrši PDF operacija i sadrži informacije o uspešnosti operacije. Ove informacije su važne za identifikovanje uspešnog izvoza PDF operacija za našu aplikaciju.

Prikupljaju se sledeća polja:

- **Data_ExportAsPDFSucceed** – Boolean označava da li je uspeh izvoza kao PDF bio uspešan.

#### <a name="officepowerpointpptsharedrehearseviewrehearseclicked"></a>Office.PowerPoint.PPT.Shared.RehearseView.RehearseClicked

Ovaj događaj prikuplja kada se klikne na RehearseWithCoach.  Ovaj događaj se koristi za analizu isprobanog levka funkcije. Ovaj događaj zajedno sa isprobanim i zadržanim događajem pomaže nam da utvrdimo da li korisnici odustaju od levka. To nam pomaže da sačuvamo ispravnost funkcije.

Prikupljaju se sledeća polja:

- Nijedno


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

- **Ime_Aktivnosti** – ime aktivnosti „Sesija“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Početak

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Omogućava nam da znamo kada je zaustavljena sesija protoka podataka. Koristi se za ispravnost funkcija i nadgledanje. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Ime_Aktivnosti** – ime aktivnosti „Sesija“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Zaustavljanje

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

Omogućava nam da znamo da li je početak protoka izvora podataka uspešan.   Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Activity_Name** – Ime aktivnosti „ProtokPodatakaUređaja“ ili „ProtokPodatakaDatoteke“

- **Activity_CV** - ID za označavanje uzajamne veze događaja u okviru sesije veze

- **Activity_StartStopType** - Početak

- **Activity_DateTimeTicks** - Vreme podataka za aktivnost

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

Omogućava nam da znamo da li je zaustavljanje protoka izvora podataka uspešno.   Koristi se za nadgledanje i ispravnost funkcija. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Tip izvora podataka** - Informacije o serijskom uređaju ili usluzi aplikacije

- **Ime izvora podataka** - Ime izvora povezanih podataka

- **Activity_Name** – Ime aktivnosti „ProtokPodatakaUređaja“ ili „ProtokPodatakaDatoteke“

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

  - **Podaci\_UrlZahteva** – URL adresa CDN resursa kojeg pokušavamo da preuzmemo



#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Prikuplja uspešno ili neuspešno izvršeno prevođenje celog dokumenta pokrenutog od strane korisnika pomoću Translator SDX. Ovo je od presudnog značaja za proveru ispravnosti funkcije prevođenja i omogućava nam da reagujemo na sve prekide do kojih može doći. Nadgledanje ispravnosti „Prevedi dokument” scenarija u programu Word.

Prikupljaju se sledeća polja:

- **Data.actionSource**- Kako je aktiviran izbor za prevođenje-

- **Data.bodyBackgroundColor**- Boja pozadine Office teme

- **Data.bodyForegroundColor** - Boja prednjeg plana Office teme

- **Data.browserLang**- Trenutni jezika prikaza u pregledaču

- **Data.browserOnline**- Zastarelo

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

- **Data.bodyBackgroundColor**- Boja pozadine Office teme

- **Data.bodyForegroundColor** - Boja prednjeg plana Office teme

- **Data.browserLang**- Trenutni jezika prikaza u pregledaču

- **Data.browserOnline**- Zastarelo

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


#### <a name="officeuxacccheckeracccheckerfinalviolationcountperrule"></a>Office.UX.AccChecker.AccCheckerFinalViolationCountPerRule

Ovaj događaj se pokreće kada se prijave problemi sa pristupačnošću za trenutno otvoreni dokument. Ovaj događaj predstavlja kršenja pristupačnosti (greške, upozorenja i saveti) koja postoje po pravilu, za otvoreni dokument na početku i na kraju sesije.  Ovaj događaj se koristi za snimanje tačaka kršenja pristupačnosti (greške, upozorenja i saveti) po pravilu, za otvoreni dokument na početku i na kraju sesije.

Detalji o tačkama kršenja po pravilu pomažu korporaciji Microsoft da identifikuje koji su problemi sa pristupačnošću najčešći u Office dokumentima. Ovo pomaže da se oni isprave i pokreće stvaranje inkluzivnog okruženja na radnom mestu i u učionici za osobe sa umanjenim sposobnostima.

Prikupljaju se sledeća polja:

- **Data_FinalCount_RuleID_0** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_1** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_2** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_3** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_4** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_5** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_6** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_7** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_8** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_9** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_10** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_11** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_12** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_13** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_14** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_15** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_16** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_FinalCount_RuleID_17** – broj kršenja ID-a pravila koja ostaju poslednji put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_0** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_1** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_2** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_3** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_4** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_5** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_6** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_7** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_8** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_9** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_10** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_11** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_12** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_13** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_14** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_15** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_16** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **Data_InitialCount_RuleID_17** – broj kršenja ID-a pravila koja su pronađena prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **FinalDocID** – konačni ID dokumenta o skeniranom dokumentu

- **FinalDocUrlHash** – konačni heš URL adrese dokumenta o skeniranom dokumentu
    
- **InitialDocID** – početni ID dokumenta o skeniranom dokumentu

- **InitialDocUrlHash** – početni heš URL adrese dokumenta o skeniranom dokumentu

- **PaneOpened** – logički operator koji prati da li je otvaran kontrolor pristupačnosti

- **ServerDocID** – server ID-a dokumenta za dokument koji je skenirao kontrolor pristupačnosti


#### <a name="officeuxacccheckeracccheckerviolationinformation"></a>Office.UX.AccChecker.AccCheckerViolationInformation

Ovaj događaj se pokreće kada se prijave problemi sa pristupačnošću za trenutno otvoreni dokument. On predstavlja skup tačaka kršenja (greške, upozorenja i saveti) za otvoreni dokument na početku i na kraju sesije. Ovaj događaj se koristi za snimanje skupa tačaka kršenja pristupačnosti (greške, upozorenja i saveti) za otvoreni dokument na početku i na kraju sesije. Znanje o korišćenju kontrolora pristupačnosti dozvoljava korporaciji Microsoft da poboljša utiske pri radu sa aplikacijom da bi bila inkluzivnija za osobe sa umanjenim sposobnostima u scenarijima korišćenja sistema Office za radno mesto i učionicu.

Prikupljaju se sledeća polja:
    
- **FinalDocID** – konačni ID dokumenta o skeniranom dokumentu

- **FinalDocUrlHash** – konačni heš URL adrese dokumenta o skeniranom dokumentu

- **FinalErrorCount** – konačni zbir grešaka koje je kontrolor pristupačnosti prijavio za dokument

- **FinalIntelligentServiceCount** – konačni zbir problema sa pametnim uslugama koje je kontrolor pristupačnosti prijavio za dokument

- **FinalTipCount** – konačni zbir saveta koje je kontrolor pristupačnosti prijavio za dokument

- **FinalViolationCount** – konačni zbir prekršaja koje je kontrolor pristupačnosti prijavio za dokument

- **FinalWarningCount** – konačni zbir upozorenja koja je kontrolor pristupačnosti prijavio za dokument

- **InitialDocID** – početni ID dokumenta o skeniranom dokumentu

- **InitialDocUrlHash** – početni heš URL adrese dokumenta o skeniranom dokumentu

- **InitialErrorCount** – broj svih prekršaja tipa “Greška” koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **InitialIntelligentServicesCount** – broj svih prekršaja tipa “Inteligentna usluga” koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **InitialTipCount** – broj svih prekršaja tipa “Savet” koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **InitialUrlHash** – broj svih prekršaja tipa greške koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **InitialViolationCount** – broj svih prekršaja koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **InitialWarningCount** – broj svih prekršaja tipa “Upozorenje” koji su pronađeni prvi put kada se kontrolor pristupačnosti pokrenuo u sesiji.

- **PaneOpened** – logički operator koji prati da li je otvaran kontrolor pristupačnosti

- **ServerDocID** – server ID-a dokumenta za dokument koji je skenirao kontrolor pristupačnosti


#### <a name="officeuxacccheckerbackgroundacccheckerenabledstate"></a>Office.UX.AccChecker.BackgroundAccCheckerEnabledState

Ovaj događaj se pokreće kada je korisnik ili IT administrator omogućio kontrolor pristupačnosti u pozadini za Office korisnika. Ovaj događaj se koristi da bi se shvatile instance kada je omogućen kontrolor pristupačnosti u pozadini za Office korisnike. Omogućeni status kontrolora pristupačnosti u pozadini dozvoljava korporaciji Microsoft da shvati da li se dokumenti mogu automatski skenirati u pozadini. To pomaže da kreirate inkluzivnije okruženje na radnom mestu i u učionici za osobe sa umanjenim sposobnostima.

Prikupljaju se sledeća polja:

- **BackgroundAccCheckerEnabled** – logički operator za praćenje omogućenog/onemogućenog stanja kontrolora pristupačnosti u pozadini


#### <a name="officeuxacccheckerbackgroundscanningcheckboxclicked"></a>Office.UX.AccChecker.BackgroundScanningCheckboxClicked

Ovaj događaj se pokreće kada korisnik omogući kontrolor pristupačnosti u pozadini iz okna zadatka kontrolora pristupačnosti.  Ovaj događaj se koristi da bi se shvatile instance kada je omogućen kontrolor pristupačnosti u pozadini za Office dokumente. Omogućeni status kontrolora pristupačnosti u pozadini dozvoljava korporaciji Microsoft da shvati da li se dokumenti mogu automatski skenirati u pozadini. To pomaže da kreirate inkluzivnije okruženje na radnom mestu i u učionici za osobe sa umanjenim sposobnostima.

Prikupljaju se sledeća polja:
    
- **FinalBackgroundScanningState** – početno stanje polja za potvrdu koje omogućava skeniranje pozadine

- **InitialBackgroundScanningState** – početno stanje polja za potvrdu koje omogućava skeniranje pozadine


#### <a name="officeuxacccheckerdisabledresults"></a>Office.UX.AccChecker.DisabledResults

Ovaj događaj se pokreće kada se kontrolor pristupačnosti onemogući za otvoreni dokument. Ovaj događaj se koristi da bi se shvatile instance kada se onemogući kontrolor pristupačnosti za Office, zbog zastarelog ili nepodržanog Office dokumenta. Onemogućen status kontrolora pristupačnosti dozvoljava korporaciji Microsoft da shvati koliko često dokument nije moguće skenirati i da pomogne korisnicima u omogućavanju skeniranja takvih dokumenata – konvertovanjem naviše dokumenta u moderan format datoteke. To pomaže da kreirate inkluzivnije okruženje na radnom mestu i u učionici za osobe sa umanjenim sposobnostima.

Prikupljaju se sledeća polja:
    
- **Data_Disabled_ID** – ID onemogućene greške

- **Data_Disabled_Reason** – razlog za onemogućavanje kontrolora pristupačnosti

- **Data_IsUpConvertEnabled** – prati da li je konvertovanje naviše u moderan format datoteke dostupno za dokument


#### <a name="officeuxacccheckershowtaskpane"></a>Office.UX.AccChecker.ShowTaskPane

Ovaj događaj se pokreće kada se okno zadatka kontrolora pristupačnosti pokrene za trenutno otvoreni dokument.  Ovaj događaj se koristi da bi se shvatila upotreba kontrolora pristupačnosti za Office. Kontrolor pristupačnosti se koristi za identifikovanje i popravljene problema sa pristupačnošću u Office dokumentima. Znanje o korišćenju kontrolora pristupačnosti dozvoljava korporaciji Microsoft da poboljša utiske pri radu sa aplikacijom da bi bila inkluzivnija za osobe sa umanjenim sposobnostima u scenarijima korišćenja sistema Office za radno mesto i učionicu.

Prikupljaju se sledeća polja:

- **BackgroundScanCheckboxEnabled** – prati da li je omogućen kontrolor pristupačnosti u pozadini
    
- **Kolona** – Namena

- **DocUrlHash** – jedinstven heš ID–a dokumenta koji je bio skeniran

- **HasAccessibilityViolations** – prati da li dokument sadrži bilo kakva kršenja pristupačnosti u momentu kada se okno otvori

- **IsPaneDisabled** – prati da li je okno kontrolora pristupačnosti otvoreno u onemogućenom stanju (zastareo ili nepodržani dokument)

- **PaneOpenedBefore** – prati da li je okno kontrolora pristupačnosti otvarano ranije

- **WAC_ServerDocId** – server ID-a dokumenta koji je bio skeniran


#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Prati promene u karakteristikama za korisnike. Ovaj događaj nam pomaže da odredimo uspešnost ili neuspešnost funkcije letova.

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

  - **Data\_DataSourceType:string** – Polje koje ukazuje na to da li je dijagram kreiran iz „tabele“ ili „prilagođenog opsega“

  - **Data\_DialogError:string** - tip česte greške koja se javlja tokom kreiranja pametnog dijagrama u programu Excel

  - **Data\_NoOfShapesAdded:int** - Broj oblika koji su dodati tokom funkcije ponovnog upisivanja u program Excel

  - **Data\_NoOfShapesAdded:int** - Broj oblika koji su obrisani tokom funkcije ponovnog upisivanja u program Excel

  - **Data\_OverwriteSelected:bool** - tačno ukazuje na to da je korisnik izabrao opciju zamene podataka

  - **Data\_SourceDataModified:bool** - tačno ukazuje na to da su izvorni podaci izmenjeni

  - **Data\_WarningShown:bool** - tačno znači da je korisniku prikazano upozorenje o ažuriranju podataka

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje zbog formule koja je prisutna u programu Excel

  - **Data\_WarningShownToAddNextStepID:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje zato što u programu Excel nedostaje identifikator sledećeg koraka

  - **Data\_WarningShownToConvertToTable:bool** - tačno ukazuje na to da je korisniku prikazano upozorenje da konvertuje Excel podatke u format tabele


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

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka. 

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje. 

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo 

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke 

- **Data_BytesUnknown** – Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo. 

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

- **Data_PartsUnknown** – broj segmenata dokumenta za koji nismo mogli da dobijemo podatke 

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

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

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

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

    

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Ovaj događaj ukazuje na to da program Office Word traži od korisnika da sačuva promene kada program pokuša da zatvori dokument. On omogućava korporaciji Microsoft da prati da li funkcija „Sačuvaj pri zatvaranju“ radi kao što se očekuje da bi bio izbegnut gubitak podataka u dokumentu. Događaj prati da li funkcija „Sačuvaj pri zatvaranju“ radi kao što se očekuje. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka.

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

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

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_AddDocTelemResDst** – Izveštava da li smo u ovom događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta za odredišni dokument. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_AddDocTelemResSrc** – Izveštava da li smo uspeli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta u slučaju izvornog dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

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

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

  - **Data\_NumberCoAuthors–** Broj koautora koji uređuju dokument tokom sesije

  - **Data\_NumberOfTimesDocumentDirtied-** Broj napravljenih izmena u dokumentu

  - **Data\_Pdod -** Identifikator dokumenta koji se obrađuje u programu Office Word

  - **Data\_UrlHash-** Heš putanje dokumenta

  - **Data\_ViewKind-** Tip prikaza u programu Word



#### <a name="onenoteappnavigationratingreminderdialogshown"></a>OneNote.App.Navigation.RatingReminderDialogShown

Kritičan signal koji se koristi za merenje efikasnosti logike okidača za podsetnik za ocenu. Ovaj dijalog se prikazuje kada korisnik ispuni sve uslove za prikaz podsetnika za ocenu (br. aktivnih dana, da li je prethodno ocenjivao ili nije itd.). Ovo se koristi da bi se obezbedila logika okidača za podsetnik za ocenu. Ako korisnici vide ovaj dijalog, to će nam obezbediti načine da na vreme dobijemo povratne informacije od klijenata i poboljšamo ispravnost aplikacije.

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="parselicenseop"></a>ParseLicenseOp

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom vršenja operacija kategorizacije operacije. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** – Id servera sistema za evidenciju

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.VerifyCertChainDuration** - Trajanje verifikacije niza certifikata

- **RMS.VerifySignatureDuration** - Trajanje verifikacije potpisa


#### <a name="qrcodescan"></a>qr.code.scan

Ovaj događaj nas obaveštava kada se korisnik prijavi na Outlook Mobile skeniranjem autorizovanog QR koda na Outlook klijentu na radnoj površini koji sigurno sadrži informacije o prijavljivanju korisnika, čime eliminiše potrebu za ručnom prijavom. Događaj se koristi za otkrivanje uspešnog pokretanja i dovršavanja procesa potvrde identiteta korisnika pomoću QR funkcionalnosti. Događaj dijagnostikuje greške pri prijavi koje mogu sprečiti korisnika da uspešno proveri potvrdu identiteta u mobilnoj aplikaciji.

Prikupljaju se sledeća polja: 

- **action** – koju radnju je korisnik preduzeo za tok qrcode


#### <a name="readconversation"></a>read.conversation

Koristi se za monitoring mogućeg negativnog uticaja na zdravlje i performanse prikazivanja e-poruke

Prikupljaju se sledeća polja: 

- **above_40fps** – prebrojavanje okvira prikazanih preko 40 o/s
 
- **above_50fps** – broj okvira prikazanih preko 50 o/s
 
- **above_55fps** – prebrojavanje okvira prikazanih preko 55 o/s

- **adal_id** – potvrda identiteta korisničkog direktorijuma, jedinstveni identifikator u Microsoft sistemu za potvrdu identiteta 

- **component_name** – ime komponente/prikaz koji je aktivan tokom filtriranja

- **event_mode** - mesto u aplikaciji koje je korisnik uneo u razgovor (grupe ili druge)

- **internet_message_id** - ID praćenja za najnoviju poruku u razgovoru
      
- **orientation** - položaj ekrana u trenutku ravnomernosti (uspravno ili položeno)

- **recent_message_id** - ID najnovije poruke u razgovoru

- **suggested_reply_state** – stanje predloženih odgovora za ovaj razgovor (nedostupan, dostupan, prikazano, korišćeno, upotrebljeno ili odbačeno)

- **suggested_reply_types** – ukazuje na tip i broj predloženih odgovora prikazanih/korišćenih za ovaj razgovor. To je rečnik. Na primer {text: 2, send_avail: 1}.
  
- **total_count** - ukupni okviri koje prikazuje komponenta
 
- **view_duration** - koliko dugo korisnik prikazuje komponentu

#### <a name="saveattempt"></a>save.attempt

Omogućava nam da identifikujemo uticaj problema koje su izazvali korisnici koji pokušavaju da sačuvaju datoteku tako što procenjuju broj sesija koji su uticali i ako postoje uobičajene funkcije tih sesija.

Prikupljaju se sledeća polja: 

- **file_type** - tip datoteke koji je korisnik pokušao da sačuva (na primer. doc)

- **origin** - odakle potiče pokušaj čuvanja datoteke, (na primer, iz e-poruke) kako bismo mogli da otkrijemo probleme koje se odnose na čuvanje datoteke sa određenog mesta u aplikaciji

- **token_type** - tip simbola koji se koristi za potvrdu identiteta naloga da biste sačuvali datoteku kako bi nam pomogao u otkrivanju problema potvrde identiteta povezanog sa čuvanjem datoteke

#### <a name="searchsubtabselected"></a>search.subtab.selected

Događaj prikuplja tačke porekla za razlog što je odabrana podkartica za pretraživanje. Podkartice se nalaze ispod primarne trake za pretraživanje aplikacije radi filtriranja podataka. Ovaj događaj nam omogućava da pratimo proširenja za verziju tipa entiteta (sve, pošta, kontakti i kalendar) koje korisnici koriste kada obave pretragu kako bismo obezbedili da mehanizmi filtera pretrage funkcionišu ispravno.

Prikupljaju se sledeća polja:

- **properties_general** – Opšta svojstva koja prikupljaju svi Aria događaji

- **selected_reason** – Uzrok vrste pilule koja se odabira, a koja može biti jedna od ovih vrednosti (glif je ikona): tap_on_header, tap_on_see_all, enter_search_mode, mail_glyph, calendar_glyph.

- **subtab_type** – Proširenje za verziju tipa koji je izabran, što može da bude jedna od ove četiri vrednosti: sve, pošta, kontakt, događaj.

#### <a name="sendmessage"></a>send.message

Prikupljeni podaci ukazuju na mogući negativan uticaj na performanse i ispravnost slanja e-poruka. Podaci se koriste za razumevanje da li funkcija uspešno funkcioniše i za planiranje poboljšanja funkcija za slike u e-porukama.

Prikupljaju se sledeća polja:
  
- **account** – prati nalog koji je izvršio akciju

- **compose_addressing_duration** - ukazuje na ukupno vreme koje korisnik provodi na poljima "Za/Cc/Bcc"

- **compose_duration** - prati ukupno vreme koje je korisniku potrebno za sastavljanje poruke, uključujući više sesija radnih verzija

- **draft_message_id** - prati ID poruke za pisanje koja se šalje

- **event_mode** – prati režim događaja ako je primenljiv na poruku, ("grupe" ili "drugo")

- **has_attachment** - označava da li poruka ima priloge

- **has_mip_label** - označava da li je nalepnica "MIP" bila označena na poruci ili ne

- **image_attachment_count** – označava koliko se slika šalje kao prilog poruke

- **image_body_count** – označava koliko se slika šalje umetnuto kao deo tela poruke

- **image_movement_count** – označava koliko se slika poruke koje su premeštene u umetnute ili premeštene nazad.

- **is_group_escalation** – da li je ovo grupna eskalirana poruka, "eskalirana poruka" je poruka koja je poslata u poštansko sanduče korisnika zbog eskalacije (pretplaćenog na grupu)

- **is_groups** - praćenje da li je poslata poruka grupna poruka ili nije

- **key_stroke_count** - praćenje pritisaka na taster za poruku koja se šalje

- **message_id** - prati ID poruke koje se odgovore/prosleđuju

- **origin** – označava gde je pokrenuto pisanje, npr. novi, odgovor, brzi odgovor itd.

- **send_draft_origin** – označava gde je pokrenuto slanje, npr. pisanje ili kratki odgovor

- **smart_compose_model_version** – prati koja se verzija modela pametnog sastavljanja koristi

- **source_inbox** - označava izvorno Prijemno sanduče u referenci poruke, 

- **suggested_reply_state** – hvatanje predložene poruke za odgovor, odnosno nedostupan, dostupan, prikazano, upotrebljeno, odbačen za ovu poslatu poštu

- **suggested_reply_types** – ukazuje na tip i broj predloženih odgovora prikazanih/korišćenih za ovu poslatu e-poruku. To je rečnik. Na primer {text: 2,  send_avail: 1}.

- **suggestions_requested** – pokazuje koliko se predloga pametnog sastavljanja traži

- **suggestions_results**– rezultati predloga pametnog sastavljanja, tj. prihvaćeno ili odbijeno

- **suggestions_returned** – pokazuje koliko je predloga pametnog sastavljanja vraćeno sa servera

- **suggestions_shown** – pokazuje koliko se predloga pametnog sastavljanja prikazuje korisniku

- **thread_id** - označava nit ID razgovora koji su odgovoreni/prosleđeni

#### <a name="session"></a>sesija

Omogućava nam da otkrijemo i rešimo situacije u kojima koristimo previše baterije uređaja i pomažu nam da identifikujemo šta može da bude uzrok.

Prikupljaju se sledeća polja: 

- **battery_level** – saopštava nam nivo baterije na uređaju koji će nam pomoći da otkrijemo kada aplikacija uzrokuje negativan uticaj na nivo baterije uređaja

- **has_hx** - govori nam da nalog koristi našu novu uslugu sinhronizacije kako bi nam pomogao da otkrijemo probleme izazvane uslugom sinhronizacije

- **Session.Duration** – dužina sesije u sekundama

- **Session.DurationBucket** – dužina trajanja vremenskog područja *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali se i dalje može pojaviti u starijim verzijama.]*

- **Session.FirstLaunchTime**– prvo zabeleženo vreme pokretanja aplikacije *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali se i dalje može pojaviti u starijim verzijama.]*

- **Session.State** – indikator da li je ovo početak ili kraj sesije

#### <a name="settingsaction"></a>settings.action

Ovaj događaj prikuplja podatke konfiguracije u podešavanjima. Podaci nam omogućavaju da otkrijemo situacije u kojima postoji mogući negativnog uticaja na mogućnost korisnika da konfiguriše postavke aplikacije, kao što su postavke obaveštenja, primarni nalog e-pošte i da konfiguriše potpis e-pošte.

Prikupljaju se sledeća polja: 

- **account_order_changed** - da biste proverili da li je ova konfiguracija promenjena, da biste se uverili da ova konfiguracija ispravno funkcioniše 

- **action** - potencijalne radnje preduzete u okviru postavke, kao što je brisanje naloga kako bi nam pomoglo da ustanovimo negativne probleme i obezbedimo da nema negativnog uticaja

- **auth_type** - tip potvrde identiteta koju koristi nalog, tako da možemo da shvatimo koji pozadinski sloj za sinhronizaciju koristimo da bismo pomogli u dijagnostikovanju problema 

- **changed_folder** – hvatanje u vidu da li se fascikla promenila da bi nam pomoglo da ustanovimo probleme. 

- **delete_scope** – tokom brisanja naloga, bez obzira na to da li ste izbrisali nalog sa ovog uređaja ili sa svih uređaja sa programom Outlook.  

- **emo_default_provider_selected_type** – polje koje određuje tip podrazumevanog dobavljača sastanaka koji je postavio korisnik. 

- **emo_default_provider_switch_type** – Tip prebacivanja koje je izvršio korisnik između organizatora sastanaka na mreži na ekranu „Svaki sastanak na mreži“. Pomaže nam da razumemo angažovanje korisnika sa funkcijom. 

- **enabled_state** – bilo da automatski odgovarate, čuvate kontakte i blokirate spoljne slike, postavke su ispravno konfigurisane  

- **notification_action** – da biste proverili da li ste konfigurisali radnje obaveštenja za sledeće e-poruke kako bi nam pomogli da se uverimo da ova postavka uspešno funkcioniše 

- **notification_action_number** – da biste proverili da li su vaše radnje obaveštenja (radnja 1 ili radnja 2) ispravno konfigurisane

- **server_type** – slični auth_type, on nam pokazuje koji tip naloga treba da nam pomogne da bolje ustanovimo probleme.  Primeri: Office365, Gmail, Outlook

- **setting_properties** – Prati svojstva u vezi sa podešavanjem radnji detaljno opisanih u nastavku: 
   - **alternate_app_icon_setting** – izabrana alternativna ikona aplikacije (svetla, tamna)
   - **auth_type** – ukazuje na tip potvrde identiteta na zadnjoj strani koji nam omogućava da znamo da li postoji problem sa određenim tipom naloga
   - **badge_count_state** – označava tip broja na bedžu koji je korisnik zatražio tj. bez značaka, fokusirano prijemno poštansko sanduče itd. 
   - **changed_folder** – utvrđuje da li je ova radnja arhivirana, planirana ili druga radnja.
   - **delete_scope** – prati da li je ova radnja bila u vezi sa brisanjem nekoga samo na ovom uređaju ili na svim uređajima, ako je primenljivo. 
  - **enabled_state** - bez obzira na to da li je stanje vezano za akciju
  - **in_app_language** – izabrani jezik u aplikaciji, tip niske (podrazumevani, en-US, fa, ru itd.)
  - **notification_action_setting** – ukazuje na detalje, ako je primenljivo, postavki obaveštenja koja se tiču ove radnje
    - **notification_action** – označava ono što je korisnik pokušavao da uradi, npr. zastavica, brisanje, arhiviranje, to nam omogućava da ustanovimo koju radnju poruke je korisnik želeo da izvrši u obaveštenju, kao i da li je radnja uspela ili ne. 
    - **notification_action_number** – ukazuje na to koji broj radnje (dve od tri radnje su prilagodljive) je dodeljen radnji obaveštenja, tj. radnja jedan, radnja dva. To nam omogućava da utvrdimo da li postoji problem sa određenom radnjom.
   - **notification_state** – označava tip broja na bedžu koji je korisnik zatražio tj. bez značaka, fokusirano prijemno poštansko sanduče itd.
   - **server_type** – ukazuje na tip pomoćnog servera koji nam omogućava da znamo da li postoji problem sa određenom vrstom servera
   - **izvor** – označava šta je izvor obaveštenja, ako je primenljivo, iz postavki ili ne uznemiravaj postavke
   - **swipe_setting** – ukazuje na detalje, ako je primenljivo, postavki prevlačenja koje se tiču ove radnje
     - **swipe_action** – označava ono što je korisnik pokušavao da uradi, npr. zastavica, brisanje, arhiviranje, to nam omogućava da ustanovimo koju akciju je korisnik tražio, kao i da li je radnja uspela ili ne. 
     - **swipe_direction** – označava na koji način će korisnik podesiti prevlačenje, tj. sleva nadesno ili zdesna nalevo. To nam omogućava da odlučimo da li postoji problem sa određenim pravcima za brzo prevlačenje.
   - **temperature_unit_setting** – izabrana jedinica za temperaturu koja treba da se koristi za vremensku prognozu 
   - **theme_color_setting** – prilagođena boja teme aplikacije koju je izabrao korisnik 
   - **ui_mode_setting** – izabrani režim korisničkog interfejsa (mračno, svetlo, podrazumevano sistemski, niska baterija itd.)
   - **signature_setting** – označava da li je postavka primenjena na ceo nalog ili pojedinačni nalog

- **state_changed_to** – da biste proverili da li je postavka vašeg fokusiranog prijemnog sandučeta „uključeno/isključeno“ ispravno konfigurisana 

- **swipe_action** – da biste proverili da li ste konfigurisali radnje brzog prevlačenja za sledeće e-poruke kako bi nam pomogli da se uverimo da ova postavka uspešno funkcioniše 

- **swipe_direction** – da biste proverili da li su vam smerovi prevlačenja (levo ili desno) ispravno konfigurisani


#### <a name="sidebaraction"></a>sidebar.action

Omogućava nam da otkrijemo situacije u kojima postoji mogući negativnog uticaja na vašu mogućnost da konfigurišete postavke aplikacije, kao što su postavke obaveštenja, primarni nalog e-pošte i da konfigurišete potpis pošte.

Polja podataka koja su uobičajena za Outlook Mobile za ovaj događaj na iOS i Android uređajima:

- **Account** – prati nalog i njegove podatke koji su povezani sa događajem, vrednosti koje su praćene u tim podacima su u zajedničkoj dokumentaciji OM polja *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office ali se i dalje može pojavljivati u starijim verzijama.]*

- **action** – praćenje tipa radnje bočne trake tj. odbačeno, izabrana pomoćna dugmad, bočna traka pošte itd., 

- **from_favorites** - prati da li radnja dolazi iz stavke u omiljenim lokacijama 

- **mail_folder_type** - kakav tip fascikle je izabran tokom radnje na traci sa strane, ako ih ima.

- **sidebar_type** – prati tip bočne trake povezane sa ovim događajem, tj. poštu ili kalendar kako bi nam pomogao da obezbedimo da navigacija kroz postavku omiljenih lokacija funkcioniše ispravno

Prikupljaju se sledeća polja: 

- **account_type** – označava tip potvrde identiteta naloga tj. gmail, outlook itd. 

- **account_has_groups** - pomaže nam da se uverimo da li nalog ima grupe, da su one ispravno konfigurisane

- **calendar_accounts_count** - broj naloga kalendara za koje morate da nam pomognete da se uverimo da su nalozi kalendara ispravno konfigurisani 

- **calendar_apps_count** - broj aplikacija za kalendar za koje morate da nam pomognete da se uverimo da su zanimljive za kalendar su ispravno konfigurisane 

- **calendar_type** - tip kalendara koji imate (primarni kalendar, grupni kalendar itd.) 

- **has_favorite_folders** - pomaže nam da se uverimo da su omiljene fascikle ispravno konfigurisane 

- **has_favorite_people** - pomaže nam da se uverimo da su omiljene osobe/kontakti konfigurisani ispravno 

- **has_group_calendar** - pomaže nam da se uverimo, ukoliko imate grupne kalendare, da su oni ispravno konfigurisani 

- **has_group_calendar_account** - pomaže nam da se uverimo, ukoliko imate grupne kalendare, da su oni ispravno konfigurisani 

- **has_group_toggled** - pomaže nam da se uverimo da ako ste proverili grupisanje kalendara, da je ova postavka ispravno konfigurisana 

- **interesting_calendar_accounts_count** - broj zanimljivih naloga kalendara za koje morate da nam pomognete da se uverimo da su zanimljivi nalozi kalendara ispravno konfigurisani 

- **mail_accounts_count** - ukupan broj naloga pošte na bočnoj traci da biste se uverili da je ovo ispravno konfigurisano 

- **mail_folder_type** – tip fascikle na koju je korisnik tapnuo da bi se uverili da je ispravno konfigurisana. To može da uključi izbrisanu fasciklu, bezvrednu poštu ili fasciklu koja je poslata. 

- **mail_inbox_unread_count** - pomaže nam da osiguramo da se prebrojavanje nepročitano prikazuje i precizno konfiguriše 

- **mail_subfolder_depth** – pomaže nam da uspešno prikažemo konfiguranje podfascikli za poštu korisnika

#### <a name="storeop"></a>StoreOp

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije potrebne za pravilno ispitivanje i dijagnostikovanje problema koji se dešavaju kada se izvrši operacija skladišta licenci za uslugu za upravljanje pravima. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.ContentId** – Id sadržaja u licenci krajnjeg korisnika

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – Ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Url** – URL adresa servera Usluge upravljanja pravima


#### <a name="surveyfloodgatetriggermet"></a>Survey.Floodgate.TriggerMet

Prati kada je uređaj ispunio kriterijume za prikazivanje ankete. Koristi se za procenu ispravnosti procesa aktiviranja ankete, kao i za obezbeđivanje toga da signal koji se koristi za analizu problema klijenata i ispravnosti radi ispravno.

Prikupljaju se sledeća polja: 

- **CampaignId** – identifikator isporučene kampanje usluge

- **SurveyId** – jedinstvena instanca kampanje

- **SurveyType** – identifikuje tip ankete


#### <a name="surveyuiformsubmit"></a>Survey.UI.Form.Submit

Prati kada je poslata anketa. Koristi se za procenu ispravnosti procesa podnošenja ankete, kao i za osiguravanje signala koji se koristi za analizu problema kupaca i da li stanje funkcioniše ispravno.

Prikupljaju se sledeća polja: 

- **CampaignId** – identifikator isporučene kampanje usluge

- **SurveyId** – jedinstvena instanca kampanje

- **SurveyType** – identifikuje tip ankete


#### <a name="watchappv2"></a>watchAppV2

Ovaj događaj nam omogućava da otkrijemo i rešimo moguće probleme sa mogućnostima na Apple satu kao što su primanje obaveštenja i odgovaranje na e-poruke.

Prikupljaju se sledeća polja: 

- **app_action** – govori nam tipove radnje koje je korisnik koristio u Apple watch, kao što je "archive_message" kako bi nam pomogao da otkrijemo probleme koji se odnose na određenu akciju kao što je nemoguće uspešno arhiviranje poruke na Apple watch

- **is_watch_app_installed** - saopštava nam da li je korisnik instalirao Apple Watch aplikaciju na svom uređaju

- **is_complication_enabled** – saopštava nam ako je korisnik dodao Outlook na Apple Watch ekran kako bi nam pomogao da otkrijemo probleme u vezi sa Apple Watch ekranima

- **watch_os** - govori nam verziju OS koji su instalirali na Apple satu kako bi nam pomogao da otkrijemo probleme u vezi sa određenim verzijama programa Apple sata


### <a name="application-status-and-boot-subtype"></a>*Status aplikacije i podtip pokretanja*

Utvrđivanje da li su se određene funkcije događaja odigrale, kao što su pokretanje ili zaustavljanje i da li funkcija radi.

#### <a name="appstartup"></a>app.startup

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde se Outlook kreće sporo ili nepotpuno, što otežava korisnicima da koriste našu aplikaciju.  Ovo obuhvata informacije o specifičnim funkcijama koje su omogućene i koliko su dugački delovi pokretanja.

Prikupljaju se sledeća polja: 

- **attach_base_context_millis** - vreme između početka osnovnog konteksta i početka onCreate()

- **device_ram_in_mb** - RAM dostupan na uređaju

- **has_company_portal** - da li je instalirana aplikacija za kompaniju

- **hx_okhttp_mode** - da li nova komponenta usluge za sinhronizaciju e-pošte koristi OKHttp za slanje i primanje mrežnih zahteva zasnovanih na usluzi HTTP-a

- **initial_activity_name** – android aktivnost koja je pokrenula aplikaciju

- **manufacturer** - proizvođač uređaja

- **model** - model uređaja

- **on_create_millis** - potrošeno vreme u onCreate() metodi

- **on_resume_millis** - vreme potrošeno u onResume() metodi

- **time_until_attach** - vreme između učitavanja klase i početnog pokretanja konteksta

- **total_millis** - ukupno vreme od početka učitavanja razreda do završetka nastavka Android aktivnosti

#### <a name="boottime"></a>boot.time 

Ovaj događaj nam omogućava da otkrijemo kada su se dogodile kritične greške u aplikaciji koje bi mogle prouzrokovati pad aplikacije ili ozbiljne probleme, kao što je prouzrokovanje da vidite prazne redove u pristigloj pošti. Ovaj događaj prikuplja informacije koje nam omogućavaju da razvrstavamo i klasifikujemo probleme radi određivanja prioriteta uticaja problema na klijente.

Prikupljaju se sledeća polja:

- **black_list_reason** - govori nam da li postoji razlog za zanemarivanje tih podataka. Neki primeri uključuju pokretanje zbog daljinskog obaveštenja i pokretanja zbog dodavanja pozadine.

- **step_premain** – Pokazuje nam vreme potrebno da Outlook pređe sa korisničkog dodirivanja ikone do step0_main „glavnog“ koraka definisanog u ovom dokumentu.

- **step0_main** – saopštava vreme koje je preduzeo za Outlook da bi prošao do "glavnog" koraka, što je korak koji je definisao Apple.

- **step1_appWillFinishLaunching** – govori nam koliko je vremena potrebno da Outlook pređe iz "glavnog" koraka u korak "appVillFinishLaunching", što je korak koji je definisao Apple.

- **step2_appDidFinishLaunching** – govori nam koliko je vremena potrebno da Outlook pređe iz "appWillFinishLaunching" koraka u korak "appDidFinishLaunching", što je korak koji je definisao Apple.

- **step3_engineStarted** – govori nam koliko je vremena potrebno da Outlook pređe iz koraka "appDidFinishLaunching" do pokretanja motora aplikacije, koji rukuje skladištenjem i sinhronizovanjem podataka.

- **step4_runLoopFirstIdle** – saopštava vreme koje je preduzeo za Outlook da bi prošao iz koraka "engineStarted" kako ne bi bilo dodatnog posla koji treba da dovršite.

- **total_time** - govori nam ukupnu količinu vremena koju je preduzeo za Outlook da bi dovršio proces pokretanja.

#### <a name="dnslookupop"></a>DnsLookupOp

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije potrebne za pravilno ispitivanje i dijagnostikovanje problema koji se dešavaju kada se izvrši operacija pretraživanja DNS informacija. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.NoOfDomainsSearched** - Broj pretraženih domena    

- **RMS.NoOfDomainsSearched** - Broj preskočenih domena 

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

#### <a name="firstvisible"></a>first.visible

Ovaj događaj nam omogućava da otkrijemo kada je korisnik prvi put namerno pokrenuo aplikaciju. Ovaj događaj je obavezan da bi se osiguralo da aplikacija uspešno radi u verzijama proizvođača originalne opreme (OEM).

Prikupljaju se sledeća polja:

- **is_oem** – praćenje polja koje ukazuje na to da li je aplikacija pokrenuta na OEM varijanti

- **is_system_install** – polje koje prati prisustvo unapred instalirane datoteke svojstava koja bi trebalo da ukazuje na to da li je ova instalacija OEM 

- **manufacturer** – proizvođač uređaja

- **model** – model uređaja

- **systemFlagSet** – vrednost zastavice Android sistema (ApplicationInfo.FLAG_SYSTEM) koja ukazuje na to da li je aplikacija instalirana kao deo sistemske slike uređaja

#### <a name="getuserop"></a>GetUserOp

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju kada se izvrši operacija otkrivanja usluga. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.ContentId** – Id sadržaja

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd greške vraćen kao rezultat operacije

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Type** - Tip informacija o korisniku

#### <a name="httpop"></a>HttpOp

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom vršenja operacija http zahteva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju
    
- **AppInfo.Name** – Ime aplikacije

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.CallBackStatus** - Status vraćenog rezultata povratnog poziva potvrde identiteta

- **RMS.CallbackTime** – Vreme koje je potrošeno na povratni poziv za potvrdu identiteta 

- **RMS.CorrelationId** – Id korelacije http zahteva

- **RMS.DataSize** - Veličina podataka http zahteva

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji ugnežđena http operacija 

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Url** – URL adresa servera Usluge upravljanja pravima

- **RMS.WinhttpCallbackStatus** – Status rezultata winhttp povratnog poziva

#### <a name="initialized"></a>Inicijalizirano

Dozvoljava nam da analiziramo zdravlje interfejsa koji mobilnim aplikacijama omogućava da preuzmu postavke korisnika i privatnosti iz Office usluga i dijagnostikovanje problema vezanih za vezu i privatnost.

Prikupljaju se sledeća polja:

- **roamingSettingType** - identifikuje lokaciju od koje pokušavamo da pročitamo postavke

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcCreateOauth2Token API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju
    
- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.StatusCode** - Kod statusa vraćenog rezultata


#### <a name="officeandroidaccountstorageinfo"></a>Office.Android.AccountStorageInfo

Ovaj događaj utvrđuje broj MSA i ADAL naloga u registratoru i deljenim željenim opcijama. On omogućava analizu nedoslednosti između skladištenja podataka i pomaže nam da stabilizujemo učinak aplikacije.

Prikupljaju se sledeća polja:

- **RegistryADALCount** – Označava broj ADAL naloga u registratoru.

- **RegistryLiveIdCount** – Označava broj MSA naloga u registratoru.

- **SharedPrefADALCount** – Označava broj ADAL naloga u deljenim željenim opcijama.

- **SharedPrefLiveIdCount** – Označava broj MSA naloga u deljenim željenim opcijama.


#### <a name="officeandroidandroidoffice16bootlatency"></a>Office.Android.AndroidOffice16BootLatency

Veoma važno za snimanje metrike performansi aplikacije u odnosu na vreme odziva aplikacije od pokretanja.  Microsoft koristi ovo da prikuplja informacije o vremenu utrošenom da bi se aplikacija odazvala i za otkrivanje scenarija koji utiču na vreme pokretanja u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **AppLaunchResponsiveTimeInMilliSec** – Vreme potrebno za odziv aplikacije pri pokretanju

- **AppSuspendedDuringBoot** - Logička vrednost koja ukazuje na to da li je aplikacija obustavljena tokom pokretanja

- **CollectionTime** - Vreme događaja

- **FileActivationAttempted** - Logička vrednost koja ukazuje na to da li je pokušana aktivacija datoteke

- **FirstIdleOnAppThreadTimeInMilliSec** - Vreme mirovanja niti aplikacije

- **IsThisFirstLaunch** - Logička vrednost koja ukazuje na to da li je ovo prvo pokretanje aplikacije

- **UserDialogInterruptionDuringBoot** - Logička vrednost koja ukazuje na to da li je došlo do blokiranja korisničkog interfejsa tokom pokretanja

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Prikuplja podatke o neočekivanim prekidima u radu Office-a. To nam omogućava da identifikujemo padove ili prekide proizvoda, tako da mogu biti rešeni.

Prikupljaju se sledeća polja:

  - **Data\_AirspaceInitTime:integer-** vreme koje je bilo potrebno za pokretanje AirSpace komponente sistema Office

  - **Data\_AllShapes:integer -** Broj oblika u dokumentu

  - **Data\_APIInitTime:integer -** vreme koje je bilo potrebno za pokretanje Visio API modula

  - **Data\_AppSizeHeight –** Visina **-** prozora programskog dodatka

  - **Data\_AppSizeWidth –** Širina **-** prozora programskog dodatka

  - **Data\_AppURL –** URL adresa programskog dodatka; Evidentira punu URL adresu programskih dodataka iz prodavnice i URL domen programskih dodataka koji nisu iz prodavnice

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

  - **Data\_Doc\_IsSyncBacked:bool–** tačno kada je u pitanju dokument servera koji postoji lokalno i koji se sinhronizuje sa serverom (npr. putem klijentskih aplikacija OneDrive ili ODB)

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

  - **Data\_DpiAwarenessTime:integer –** Vreme koje je bilo potrebno da se omoguće tpi vrednosti po monitoru

  - **Data\_DurationToCompleteInMilliseconds:double–** Trajanje izvršavanja opcije „Sačuvaj kao“ u milisekundama

  - **Data\_ErrorCode:int –** : 0 za uspeh, ceo broj za grešku u čuvanju

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

  - **Data\_HasCoauthUserEdit:bool –** tačno ako je dokument izmenjen u sesiji koautorstva

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

  - **Data\_InternalFile:bool -** tačno ako je datoteka unutrašnja na primer, šablon

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

  - **Data\_MaxCoauthUsers:integer –** najveći broj korisnika koji sarađuju u bilo kom trenutku u sesiji sistema datoteke, registratora, direktnoj, SDX

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

  - **Data\_SDX\_HostJsVersion –** Ovo je Office.js verzija specifična za platformu (npr. Outlook web16.01.js) Sadrži površinu API–ja programske dodatke

  - **Data\_SDX\_Id –** GUID programskog dodatka koji ga jedinstveno identifikuje

  - **Data\_SDX\_InstanceId -** Predstavlja programski dodatak u paru dokumenata

  - **Data\_SDX\_MarketplaceType –** Ukazuje na to odakle je instaliran programski dodatak

  - **Data\_SDX\_OfficeJsVersion –** Ovo je Office.js verzija koja će preusmeriti na verziju karakterističnu za platformu.

  - **Data\_SDX\_Verzija –** Verzija programskog dodatka

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

  
#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Prikuplja kada je Office programskom dodatku potrebno neočekivano dugo da se pokrene (> 5 SEC). Koristi se za otkrivanje i rešavanje problema sa pokretanjem Office programskih dodataka.
 
Prikupljaju se sledeća polja:

- **AppId** -ID aplikacije

- **ApInfo** -podaci u vezi sa tipom programskog dodatka (okno zadatka ili UILess ili u sadržaju itd.) i tip dobavljača (Omen, SharePoint, okviru sistema datoteka itd.)

- **AppInstanceId** – ID instance aplikacije 

- **AssetId** - ID procene za aplikaciju

- **IsPreload** – označava da li je programski dodatak unapred učitan u pozadini radi unapređenja učinka aktivacije

- **NumberOfAddinsActivated**- brojač aktivnih programskih dodataka

- **RemoterType** – precizira tip daljinca (pouzdanih, nepouzdanih, Win32webView, pouzdanih UDF-ova itd.) koji se koristi za aktiviranje programskog dodatka

- **StoreType** - poreklo aplikacije

- **TimeForAuth** - vreme potrošeno na potvrdu identiteta 

- **TimeForSandbox** - vreme potrošeno na sandbox

- **TimeForServerCall** - vreme potrošeno na pozivu na serveru 

- **TotalTime** - ukupno potrošeno vreme

- **UsesSharedRuntime** – označava da li aplikacija koristi sharedRuntime ili ne.

#### <a name="officelenslenssdklaunchlens"></a>Office.Lens.LensSdk.LaunchLens

Kada korisnik pokrene Lens da bi uhvatio ili uvezao slike u bilo kojoj aplikaciji, pokrenut je SDK i taj događaj se sakuplja. Pokretanje podataka olakšava određivanje broja korisnika/uređaja koji pokreću aplikaciju i dodatno razumeju potrošnju funkcija. Pomaže nam da pratimo količinu korisnika pomoću proizvoda, kao i da identifikujemo promene u trendovima, pomoć za pronalaženje i ispravljanje problema u proizvodu.

Prikupljaju se sledeća polja:

- **Data_isResumeSession** – da li je aplikacija pokrenuta u nastavku ili da li je korisnik pokrenuo novi početak. (Boolean polje) 

- **Data_launchPerf** – ceo broj koji označava vreme koje je snimljeno da pokrene aplikaciju (u programu Android)

- **Data_LaunchWorkFlowItem** polje navodi da li se aplikacija pokreće sa ekrana kamera ili uređivanje ekrana. 

- **Data_mediaCompressionFactor** – faktor prema kom se slike komprimovaju pomoću aplikacije.

- **Data_RecoveryMode** –Boolean polje koje ukazuje na to da li je sesija bila oporavljena nakon što je pokrenuta aplikacija (u programu Android)

- **Alatka "nadexmodemode"** –Boolean označava da li uređaj podržava Samsung Dex funkcije.

- **Isemkrevet** –Boolean polje koje ukazuje na to da li je korisnik pokrenuo kontrolu u režimu Picture in Picture.

- **Zainterimcropenabit** –Boolean polje koje ukazuje na to da li je korisnik odlučio da ručno izrezali svaku sliku.

- **Zamultiwindowenabled** –Boolean polje koje označava da li je moguće pokrenuti aplikaciju na razdeljenom ekranu.

- **LaunchPerf** –ceo broj koji se koristi za pokretanje aplikacije (na iOS)

- **Funkcija "Reklistmod"** –Boolean polje koje ukazuje na to da li je sesija oporavljena nakon što je pokrenuta aplikacija (na osnovu iOS)

- **Sdkmod** – režim u kom su fotografije snimljene.


#### <a name="officeofficemobileappactivationlaunch"></a>Office.OfficeMobile.AppActivation.Launch

Ovaj događaj identifikuje prvu i daljnje aktivacije putem spoljašnjih okidača koji aktiviraju aplikaciju. Aktivacija aplikacije učitava određene zavisnosti koje su odgovorne za rad aplikacije bez problema i taj događaj će zabeležiti da li su uspešno učitale. Takođe će zabeležiti izvor aktivacije i nameru aplikacije koja je bila odgovorna za aktivaciju aplikacije.

Prikupljaju se sledeća polja:

- **ActionName** – mapiranje vrednosti celog broja na ime radnje/funkcije koja je pozvana iz tačke aktivacije.
 
- **ActivationType** – mapiranje vrednosti celog broja na izvor aktivacije
  
- **IsActionTriggered** – Bulova vrednost koja određuje da li je radnja pokrenuta nakon uspešne aktivacija aplikacije.

- **IsFirstRun** – Bulova vrednost koja određuje radi li se o prvom ili daljnjem izvršavanju aplikacije.
 

#### <a name="officeofficemobilefrefirstrunsetup"></a>Office.OfficeMobile.FRE.FirstRunSetup

Prvo pokretanje aplikacije nakon instalacije će pokrenuti početni događaj. On će nam pomoći da identifikujemo instalacije i automatske nadogradnje sa starijih verzija aplikacije i omogućiće nam da identifikujemo greške u automatskim nadogradnjama, uključujući opterećenja biblioteka i neuspela preuzimanja paketa proširenja/jezičkih paketa.

Prikupljaju se sledeća polja:

- **IsFlightAssigned** – Bulova vrednost koja određuje da li je korisnik bio deo unapred dodeljene grupe letova koja može da aktivira izloženost određenim iskustvima.

- **IsFRELoadSuccessful** – ceo broj koji pokazuje stanje rezultata

#### <a name="officeonenoteandroidappappbootcomplete-officeandroidearlytelemetryappbootcomplete"></a>Office.OneNote.Android.App.AppBootComplete, Office.Android.EarlyTelemetry.AppBootComplete

*[Ovaj događaj je prethodno nazvan OneNote.App.AppBootComplete.]*

Kritičan signal koji se koristi da omogući da novi pojedinačni korisnici (Microsoft nalog) mogu uspešno da pokrenu i koriste OneNote po prvi put.  Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge.  Ako korisnici ne mogu da pokrenu aplikaciju po prvi put, to bi izazvalo incident velike ozbiljnosti.

Prikupljaju se sledeća polja: 

- **ACTIVITY_BOOT_TIME_IN_MS** - Vreme potrebno za dovršetak kreiranja aktivnosti

- **ACTIVITY_NAME** - Ime otvorene aktivnosti pri pokretanju 

- **ANY_DIALOG_SHOWN** – Označava da li je bilo koji dijalog prikazan tokom vremena pokretanja

- **APP_SUSPEND_DURING_EVENT** – Označava da li je pokretanje sprečeno

- **APP_THREAD_CREATION_WAIT_TIME_TIME_FOR_APP_THREAD_CREATION** - Vreme potrebno za kreiranje niti aplikacije

- **AVAILABLE_MEMORY_IN_MB** - Ukupna količina memorije dostupne na uređaju 

- **AVG_SNAPSHOT_POPULATION_TIME** - Prosečno vreme potrebno za dobavljanje strukture beležnice tokom korišćenja aplikacije

- **BOOT_END_AT_VIEW** - Potkategorija imena aktivnosti (ime prikaza)

- **BOOT_SNAPSHOTS** – Detalji dobavljanja structure beležnice za naloge koji se koriste u aplikaciji

- **COREAPP_STARTUP_ACCOUNT_SETUP_STARTUP_ACCOUNT_SETUP** - Vreme potrebno za proveru i pokretanja SSO iskustva

- **CRASH_INTERACTION_DURING_BOOT > 0** – Ukazuje na to da li se aplikacija srušila tokom poslednje sesije

- **DALVIK_HEAP_LIMIT_IN_MB** - Zastarelo

- **DELAY_LOAD_STICKY_NOTES** – Označava da li lepljive beleške imaju odlaganje ili ne

- **FISHBOWL_SHOWN_DURING_EVENT** – Označava instance u kojima se sadržaj ne sinhronizuje

- **HAS_LOGCAT_LOGGING_IMPACT_ON_BOOT** – Označava da li evidencije utiču na vreme pokretanja

- **INIT_SNAPSHOT_DURATION** - Vreme potrebno za dobavljanje strukture beležnice za korisničke naloge

- **IS_COLD_BOOT** – Označava da li se aplikacija pokreće kada aplikacija nije pokrenuta u pozadini

- **IS_FIRST_LAUNCH** – Označava da li je ovo prvi put da je pokrenuta aplikacija na uređaju

- **IS_FOLDABLE_TYPE** – Označava da li uređaj može da se preklopi

- **IS_PHONE** - Označava da li je uređaj telefon ili tablet

- **IS_RECENT_PAGES_AVAILABLE_ON_FRAGMENT_CREATION** - Označava da li je korisnički interfejs spreman i čeka da sadržaj postane dostupan 

- **IS_REHYDRATE_LAUNCH** - Označava da li je aplikaciju zatvorio sistem

- **IS_UPGRADE** - Označava da li je aplikacija pokrenuta nakon nadogradnje

- **JOT_MAIN_APP_CREATE_TIME_MAIN_APP_CREATE_TIME** - Vreme potrebno za kreiranje JOT komponente (komponenta sa deljenim kodom) 

- **JOT_MAIN_APP_INIT_TIME_MAIN_APP_INIT_TIME** - Vreme potrebno za pokretanje JOT komponente

- **LAUNCH_POINT** - Označava da li je aplikacija pokrenuta putem vidžeta, ikone ili hiperveze ili Deljenja itd.

- **MSO_ACTIVATION_TIME_ACTIVATION_TIME** - Vreme potrebno za pokretanje MSO

- **NATIVE_LIBRARIES_LOAD_TIME** - Vreme potrebno za učitavanje biblioteka

- **NAVIGATION_CREATE_TO_NAVIGATION_RESUME_CREATE_TO_NAVIGATION_RESUME** - Vreme potrebno za dovršavanje navigacije

- **NAVIGATION_RESUME_TO_BOOT_END_RESUME_TO_BOOT_END** - Vreme potrebno za merenje odloženog učitavanja stranice posle pokretanja

- **NAVIGATION_SET_CONTENT_VIEW_TIME_SET_CONTENT_VIEW_TIME** - Vreme potrebno za dovođenje sadržaja

- **NUMBER_Of_RUNNING_PROCESSES** - Označava broj aktivnih procesa koji su pokrenuti

- **NUMBER_OF_SNAPSHOTS** - Broj dobavljanja structure beležnice pri pokretanju

- **OFFICEASSETMANAGER_INITIALIZATION_TIME** - Vreme potrebno za raspakivanje i pokretanje Upravljača resursima

- **ACTIVITY_BOOT_TIME_IN_MS** - Vreme potrebno za dovršetak kreiranja procesa

- **ROOT_ACTIVITY_CREATE_ACTIVITY_CREATE** - Vreme potrebno za prelazak iz korenog sloja 

- **ROOT_ACTIVITY_DISK_CHECK_ACTIVITY_DISK_CHECK** - Zastarelo

- **ROOT_ACTIVITY_LAUNCH_NEXTACTIVITY_ACTIVITY_LAUNCH_NEXTACTIVITY** - Zastarelo

- **ROOT_ACTIVITY_PROCESS_INTENT_ACTIVITY_PROCESS_INTENT** - Zastarelo 

- **ROOT_ACTIVITY_SESSION_ACTIVITY_SESSION** - Vreme potrebno za prelazak iz korenog sloja 

- **ROOT_TO_NAVIGATION_TRANSITION_TO_NAVIGATION_TRANSITION** - Vreme potrebno za obavljanje navigacije iz korena

- **SNAPSHOT_PUBLISH_TO_RENDERING_END_PUBLISH_TO_RENDERING_END** - Vreme potrebno za dovršavanje prikazivanja sadržaja

- **SPLASH_ACTIVITY_SESSION_ACTIVITY_SESSION** - Vreme potrebno za prikaz uvodnog ekrana

- **SPLASH_TO_ROOT_TRANSITION_TO_ROOT_TRANSITION** - Vreme potrebno za prelazak iz korenog sloja 

- **TIME_BETWEEN_PROCESS_BOOT_AND_ACTIVITY_BEGIN_IN_MS** - Vreme izmeðu kreiranja procesa i aktivnosti 

- **TIME_TAKEN_IN_MS** - vreme utrošeno na dovršavanje pokretanja
 
- **TOTAL_MEMORY_IN_MB** - Ukupna količina memorije uređaja
 
- **USER_INTERACTED_DURING_EVENT** - Označava da li je došlo do korisničke interakcije tokom pokretanja

#### <a name="officeonenoteandroidapponenoteappforeground-officeandroidearlytelemetryonenoteappforeground"></a>Office.OneNote.Android.App.OneNoteAppForeground, Office.Android.EarlyTelemetry.OneNoteAppForeground

*[Ovaj događaj je prethodno nazvan OneNote.App.OneNoteAppForeground.]*

Signal koji se koristi za označavanje da je OneNote aplikacija u prednjem planu  Telemetrija se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. 

Prikupljaju se sledeća polja: 

- Nijedno

#### <a name="officeonenoteandroidapplaunch-officeandroidearlytelemetryapplaunch"></a>Office.OneNote.Android.AppLaunch, Office.Android.EarlyTelemetry.AppLaunch

*[Ovaj događaj je prethodno nazvan OneNote.AppLaunch.]*

Kritični signal koji se koristi da bi se osiguralo da korisnici usluge OneNote mogu uspešno pokrenuti aplikaciju.  Telemetrija se koristi za obezbeđivanje kritične regresivne ispravnosti za OneNote aplikacije i ispravnost usluge. 

Prikupljaju se sledeća polja: 

- **ANDROID_SDK_VERSION** – Hvata Android SDK verziju

- **FirstLaunchTime** - Beleži vreme prvog pokretanja aplikacije

- **InstallLocation** – Označava da li je aplikacija unapred instalirana ili da li je preuzeta iz prodavnice

- **is_boot_completed_ever** – Označava da li je aplikacija ikada ranije bila uspešno pokrenuta na uređaju

- **IS_DARK_MODE_ENABLED** – Bulov znak koji ukazuje na to da li je aplikacija u mračnom režimu ili nije

- **NewOneNoteUser** - Prepoznaje da li se radi o novom korisniku

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Prikuplja korisnički PUID i identifikator zakupca jednom po sesiji. Korelacija između PUID-a i zakupca je neophodna da bi se razumeli i dijagnostikovali problemi po zakupcu u programu Outlook.

Prikupljaju se sledeća polja:

  - **CollectionTime** - Vremenska oznaka događaja

  - **ConnId** - Identifikator veze: Identifikator o vezi koja raščlanjuje PUID i identifikator OMS zakupca

  - **OMSTenantId** - Jedinstveni identifikator zakupca koji je generisao Microsoft

  - **PUID** - Menja PUID da bi se korisnici jedinstveno identifikovali


#### <a name="officeoutlookmacmacolkactivationstate"></a>Office.Outlook.Mac.MacOLKActivationState

Prikuplja na koji način je Outlook aktiviran, kao što je pretplata ili količinsko licenciranje. Podaci se nadgledaju da bismo bili sigurni da neće doći do povećanog broja otkazivanja. Takođe analiziramo podatke da bismo pronašli oblasti za poboljšanje. 

Prikupljaju se sledeća polja:

- **SetupUIActivationMethod** – metod aktivacije programa Outlook, kao što su pretplata ili količinsko licenciranje

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Prikuplja se svaki put kada se otvori datoteka u programu PowerPoint. Sadrži informacije o uspehu, detalje o greškama, metriku performansi i osnovne podatke o datoteci uključujući tip formata i metapodatke dokumenta. Ove informacije su potrebne da bismo proverili da li PowerPoint može uspešno da otvara datoteke bez degradacije u performansama. Omogućavaju nam da dijagnostikujemo sve probleme koje otkrijemo.

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemetryResult -** Da li stavka evidencije sadrži svu neophodnu telemetriju dokumenta (Podaci\_Dokument\_\* polja)

  - **Data\_AddDocumentToMruList -** Trajanje izvršavanja metode AddDocumentToMruList

  - **Data\_AlreadyOpened –** Da li je ovaj dokument prethodno otvoren (u kontekstu iste sesije procesa)

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

  - **Data_ClpDocHasDrmDoc:bool** – Da li dokument ima DRM dokument

  - **Data_ClpDocHasIdentity:bool**  – Da li dokument ima informacije o identitetu (koje se koriste za preuzimanje i podešavanje oznaka osetljivosti)

  - **Data_ClpDocHasSessionMetadata:bool** – Da li dokument ima metapodatke radne oznake osetljivosti iz sesije

  - **Data_ClpDocHasSpoMetadata:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IMetadataCache-a

  - **Data_ClpDocHasSpoPackage:bool** – Da li dokument ima metapodatke oznake osetljivosti iz SPO putem IPackage-a

  - **Data_ClpDocIsProtected:bool** – Da li je dokument zaštićen putem IRM ili nije

  - **Data_ClpDocMetadataSource:int** – Prebrojavanje koje označava odakle su metapodaci oznake osetljivosti (IRM, OPC deo, SharePoint itd.)

  - **Data_ClpDocNeedsUpconversion:bool** – Da li dokument mora da konvertuje naviše podatke oznake osetljivosti iz custom.xml dela

  - **Data_ClpDocNumFailedSetLabels:int** – Ukupan broj oznaka osetljivosti čije podešavanje na dokumentu nije uspelo

  - **Data_ClpDocSessionMetadataDirty:bool** – Da li dokument ima metapodatke radne oznake osetljivosti koji su nesređeni

  - **Data_ClpDocWasInTrustBoundary:bool** – Da li je dokument bio u granicama poverenja (da li je dozvoljavao koautorstvo nad dokumentima koje štite oznake osetljivosti)

  - **Data\_ContentTransaction -** Unapred definisani skup vrednosti koji se odnosi na to kada transakcija može biti kreirana (dozvoljeno pri učitavanju dokumenta, dozvoljeno pri završenom otvaranju, itd.)

  - **Data_CorrelationId –** GUID je prosleđen programu PowerPoint pomoću programa ProtocolHandler za korelaciju telemetrije. ProtokolHandler je odvojeni proces koji upravlja Office vezama za OS.

  - **Data\_CppUncaughtExceptionCount:long -** Neuhvaćeni izvorni izuzeci dok je aktivnost pokrenuta

  - **Data\_CreateDocumentTimeMS -** Trajanje izvršavanja metode CreateDocumentTimeMS u milisekundama

  - **Data\_CreateDocumentToken -** Trajanje izvršavanja metode CreateDocumentToken u milisekundama

  - **Data\_CreateDocumentToW -** Trajanje izvršavanja metode CreateDocumentToW u milisekundama

  - **Data\_CreateDocWindow -** Trajanje izvršavanja metode CreateDocWindow u milisekundama

  - **Data\_CreateLocalTempFile -** Trajanje izvršavanja metode CreateLocalTempFile u milisekundama

  - **Data_CsiDownloadErrDlgSuppressed:bulova** – Da li je suzbijen dijalog koji bi CSI prikazao tokom greške pri preuzimanju, obično u korist dijaloga koji umesto toga prikazuje PowerPoint.

  - **Data\_DetachedDuration:long -** Vreme tokom kog je aktivnost bila uklonjena/nije bila pokrenuta

  - **Data\_DetermineFileType -** Trajanje izvršavanja metode DetermineFileType u milisekundama

  - **Data\_Doc\_AccessMode:long –** Kako je dokument otvoren (samo za čitanje/čitanje i pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long -** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument otvoren u režimu pomoći za čitanje

  - **Data_Doc_AsyncOpenKind:long –** Ukazuje na to da li je otvorena keširana verzija dokumenta u oblaku i koja je logika nesinhronizovanog osvežavanja korišćena.

  - **Data\_Doc\_ChunkingType:long -** Kako je dokument uskladišten u sistemu SharePoint

  - **Data\_Doc\_EdpState:long -** Status dokumenta u vezi sa zaštitom podataka preduzeća

  - **Data\_Doc\_Ext:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_Extension:string -** Oznaka tipa dokumenta

  - **Data\_Doc\_FileFormat:long -** Unapred definisani skup vrednosti za format datoteke (detaljniji od oznake tipa datoteke)

  - **Data\_Doc\_Fqdn:string –** Gde je dokument uskladišten (SharePoint.com, live.net), dostupno samo za domene programa Office 365

  - **Data\_Doc\_FqdnHash:string –** Heš mesta gde je uskladišten dokument

  - **Data\_Doc\_IdentityTelemetryId:string –** Jedinstveni korisnički GUID

  - **Data\_Doc\_IdentityUniqueId:string -** Jedinstveni identifikator identiteta koji je korišćen za radnju deljenja dokumenata

  - **Data\_Doc\_IOFlags:long -** Maske bitova za različite zastavice koje se odnose na IO u datom dokumentu

  - **Data\_Doc\_IrmRights:long -** Unapred definisani skup vrednosti za tip upravljanja pravima o informacijama koji je primenjen na dokument (prosleđivanje, odgovaranje, bezbedni čitač, uređivanje, itd.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool -** Tačno ako je HTTP zaglavlje "IsCloudCollabEnabled" već dobijeno iz zahteva za opcije

  - **Data\_Doc\_IsIncrementalOpen:bool–** Da li je dokument otvoren postepeno (nova funkcija koja otvara dokument, bez potrebe za preuzimanjem celog dokumenta)

  - **Data\_Doc\_IsOcsSupported:bool –** Da li dokument podržava koautorstvo putem nove OCS usluge

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Da li se dokument otvara iz lokalnog keša?

  - **Data\_Doc\_IsSyncBacked:bool -** Da li je dokument otvoren iz fascikle koja koristi aplikaciju OneDrive za ponovnu sinhronizaciju

  - **Data\_Doc\_Location:long -** Unapred definisani skup vrednosti za mesto gde je dokument uskladišten (lokalno, u usluzi SharePoint, na WOPI serveru, na mreži, itd.) 

  - **Data\_Doc\_LocationDetails:long –** Unapred definisani skup vrednosti za detaljnije informacije o lokaciji („privremena“ fascikla, fascikla „preuzimanja“, usluga One Drive za dokumente i slike, itd.)

  - **Data\_Doc\_NumberCoAuthors:long –** Broj koautora u trenutku otvaranja dokumenta

  - **Data\_Doc\_PasswordFlags:long -** Unapred definisani skup vrednosti za način na koji je dokument šifrovan lozinkom (nije šifrovan, lozinka za čitanje, lozinka za uređivanje)

  - **Data\_Doc\_ReadOnlyReasons:long –** Unapred definisani skup vrednosti koji se odnosi na razloge zbog kojih je dokument označen samo za čitanje (zaključan na serveru, konačni dokument, zaštićen lozinkom za uređivanje, itd.)

  - **Data\_Doc\_ResourceIdHash:string -** Heš identifikatora resursa za dokumente koji su uskladišteni na oblaku

  - **Data_Doc_RtcType –**  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

  - **Data\_Doc\_ServerDocId:string -** nepromenljivi identifikator za dokumente koji su uskladišteni na oblaku

  - **Data\_Doc\_ServerProtocol:long -** Unapred definisani skup vrednosti koji se odnosi na to koji protokol se koristi za komunikaciju sa serverom (Http, Cobalt, WOPI, itd.)
 
  - **Data\_Doc\_ServerType:long -** Unapred definisani skup vrednosti za tip servera (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** Da li je server zasnovan na verziji Office14, Office15, Office16?

  - **Data\_Doc\_SessionId:long -** generisani GUID koji identifikuje instance dokumenta tokom istog procesa sesije

  - **Data\_Doc\_SharePointServiceContext:string -** Neprozirna niska, obično GridManagerID.FarmID. Korisna je za povezivanje evidencija na strani klijenta i na strani servera

  - **Data\_Doc\_SizeInBytes:long -** Veličina dokumenta u bajtovima

  - **Data\_Doc\_SpecialChars:long -** Maska bitova koja ukazuje na specijalne znakove u URL adresi ili putanji dokumenta

  - **Data\_Doc\_StorageProviderId:string -** Niska koja identifikuje dobavljača skladišta za dokument, kao što je „DropBox“

  - **Data\_Doc\_StreamAvailability:long–** Unapred definisani skup vrednosti za status protoka dokumenta (dostupan, trajno onemogućen, nedostupan)

  - **Data\_Doc\_UrlHash:string -** Heš cele URL adrese dokumenata koji su uskladišteni na oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** tačno ako je datoteka otvorena postepeno pomoću unapred keširanih WRS podataka na hostu

  - **Data\_Doc\_WopiServiceId:string –** Identifikator usluge WOPI, npr. „Dropbox“

  - **Data_DownloadErrorCsi:int** – Tip greške preuzimanja, kao što obezbeđuje CSI

  - **Data_DownloadErrorHResult:int** – HRezultat greške preuzimanja, kao što obezbeđuje CSI

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

  - **Data\_FailureReason:long –** Unapred definisani skup vrednosti za razlog neuspešnosti (datoteka je oštećena, blokirao je antivirus, itd.)

  - **Data\_FCreateNew -** Da li je novi prazan dokument

  - **Data\_FCreateNewFromTemplate -** Da li je novi dokument iz predložaka

  - **Data_FErrorAfterDocWinCreation: Boolean-** Da li je došlo do greške ili izuzetka nakon kreiranja prozora dokumenta.

  - **Data_FileIOClpState:int** – Bitset koji sadrži vrednosti koje se odnose na status oznake osetljivosti. Na primer, tu spadaju informacije o tome da li je omogućeno koautorstvo sa zaštićenim etiketama, da li dokument ima oznaku primenjenu sa trenutnog korisnika i da li je dokument zaštićen IRM-om.

  - **Data\_FileUrlLocation -** Unapred definisani skup vrednosti za mesto gde je uskladišten dokument (NetworkShare, LocalDrive, ServerOther, itd.)

  - **Data\_FirstSlideCompressedSize -** komprimovana veličina prvog slajda segmenta zip arhive (obično Slide1.xml)

  - **Data_FIsAutoBackupFile-** Da li je ova datoteka automatska rezervna kopija datoteke?

  - **Data\_FIsDownloadFileInBgThreadEnabled -** Da li je omogućeno preuzimanje u pozadinskom nizu?

  - **Data\_fLifeguarded:bool -** Da li se dokument ikada samokorigovao (funkcija koja sama ispravlja greške u dokumentu bez slanja upita korisniku)?

  - **Data\_ForceReopenOnIncOpenMergeFailure –** Zastavica koja označava da li smo bili primorani na ponovno otvaranje zbog greške u objedinjavanju u protokolu Inc Open

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

  - **Data\_IsIncOpenInProgressWhileOpen –** U slučaju višestrukog otvaranja istog dokumenta, da li Inc otvoreni protokol radi zajedno sa otvorenim protokolom?

  - **Data\_IsMultiOpen -** Da li podržavamo višestruko otvaranje?

  - **Data\_IsOCS –** Da li se dokument u svom poslednjem poznatom stanju nalazio u režimu OCS

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

  - **Data_OngoingBlockingOpenCount –** Ovo je prebrojavanje trenutno pokrenutih otvorenih protokola za blokiranje.
  
  - **Data_OngoingOpenCount –** Ovo je prebrojavanje trenutno pokrenutih otvorenih protokola.

  - **Data\_OpenCompleteFailureHR -** rezultat zbog kog nije uspeo protokol OpenComplete

  - **Data\_OpenCompleteFailureTag -** Oznaka (pokazivač lokacije koda) mesta na kom nije uspeo protokol OpenComplete

  - **Data\_OpenLifeguardOption -** Unapred definisani skup vrednosti izbora za operaciju samokorigovanja (nijedan, pokušaj ponovo, otvori u veb aplikaciji, itd.)

  - **Data\_OpenReason -** Unapred definisani skup vrednosti za način na koji je otvoren dokument (FilePicker, OpenFromMru, FileDrop, itd.)

  - **Data\_OSRPolicy -** Smernice za bezbedni čitač

  - **Data\_OSRReason -** Razlozi zbog kojih je dokument otvoren u bezbednom čitaču

  - **Data\_OtherContentTypesWithRequiredParts -** Nestandardni tipovi sadržaja koji su isključeni, ali neophodni za prvo prikazivanje

  - **Data\_PrepCacheAsync -** Zastavica koja označava OcsiOpenPerfPrepCacheAsync

  - **Data\_PreviousDiscardFailed -** Ukazuje na to da prethodni pokušaj otvaranja/zatvaranja dokumenta nije pravilno oslobodio svu memoriju

  - **Data\_PreviousFailureHr –** Koji je bio poslednji rezultat greške u slučaju ponovnog otvaranja istog dokumenta?

  - **Data\_PreviousFailureTag –** Koja je bila poslednja oznaka greške (pokazivač lokacije koda) u slučaju ponovnog otvaranja istog dokumenta? 

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

  - **Data\_WBDirtyBeforeDiscard –** Da li je radna grana bila nesređena pre ponovnog otvaranja dokumenta

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

- **AppSessionGuid** - Identifikator sesije za određenu aplikaciju počevši od vremena kreiranja procesa do kraja procesa. Oblikovan je kao standardni 128–bitni GUID, ali se sastoji iz 4 dela. Ta četiri dela su po redu (1) 32–bitni ID procesa (2) 16–bitni ID sesije (3) 16–bitni ID za pokretanje (4) 64–bitni proces nastanka u UTC 100ns

- **processSessionId** - nasumično generisan guid za identifikovanje sesije aplikacije

- **UTCReplace_AppSessionGuid** - Nepromenjiva logička vrednost. Uvek ima vrednost TRUE.

#### <a name="officesystemsessionhandoff"></a>Office.System.SessionHandoff

Ukazuje da je trenutna sesija Office-a završna sesija. To znači da se rukovanje zahtevom korisnika za otvaranje dokumenta predaje već pokrenutoj instanci iste aplikacije.

Prikupljaju se sledeća polja.

- **ParentSessionId** – ID sesije koja će preuzeti upravljanje zahtevom korisnika.

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

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

- **Data_BytesUnknown** – Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo. 

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

- **Data_Doc_IsSyncBacked** - Zastavica koja ukazuje na to da na računaru postoji kopija koja se automatski sinhronizuje

- **Data_Doc_Location** - Ukazuje na to koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint, itd.)

- **Data_Doc_LocationDetails** - Ukazuje na to koja „Poznata fascikla“ je obezbedila lokalno uskladišteni dokument

- **Data_Doc_NumberCoAuthors** - Izračunavanje broja drugih korisnika u sesiji zajedničkog uređivanja

- **Data_Doc_PasswordFlags** - Ukazuje na to da je postavljena zastavica za lozinku za čitanje ili čitanje/pisanje

- **Data_Doc_ReadOnlyReasons** - Razlozi zbog kojih je dokument otvoren samo za čitanje

- **Data_Doc_ResourceIdHash** - Anonimni Identifikator dokumenta koji se koristi da bi se dijagnostikovali problemi

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

- **Data_PartsUnknown** – broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

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

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka
    
- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.
    
- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke
    
- **Data_BytesUnknown** – Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

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

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

- **Data_PartsUnknown** – broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo.

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja.

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument.

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku.


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Ovaj događaj ukazuje na to da Office Word otvara dokument putem COM aktivacije ili komandne linije. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke iz komandne linije radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

  - **Data\_AddDocTelemRes –** Izveštava da li smo u događaju mogli ispravno da unesemo druge vrednosti koje se tiču telemetrije dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

  - **Data\_BytesAsynchronous -** Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

  - **Data\_BytesAsynchronousWithWork -** Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo

  - **Data\_BytesSynchronous -** Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

  - **Data\_BytesUnknown –** Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

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

  - **Data_Doc_RtcType –**  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

  - **Data\_PartsUnknown –** broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

  - **Data\_RecoverableFailureInitiationLocationTag -** Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo

  - **Data\_RenameDisabledReason -** Greška koja uzrokuje nemogućnost preimenovanja dokumenta

  - **Data\_RenameFlightEnabled -** Da li je omogućena putanja za funkciju preimenovanja

  - **Data\_SecondaryTag -** Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja.

  - **Data\_TemplateFormat -** Format datoteke predloška na kome je zasnovan dokument.

  - **Data\_UsesNormal -** Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku.


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Ovaj događaj ukazuje na to da Office Word otvara dokument putem dijaloga „Otvaranje“. Sadrži i bitne podatke o performansama otvaranja datoteke i o tome da li je u pitanju događaj pokretanja aplikacije iz perspektive korisnika. Događaj prati da li otvaranje datoteke pomoću dijaloga „Otvaranje“ radi kao što je očekivano. Takođe se koristi i za izračunavanje mesečno aktivnih korisnika/uređaja i metrike pouzdanosti oblaka. 

Prikupljaju se sledeća polja:

- **Data_AddDocTelemRes** – Izveštava da li smo u slučaju mogli pravilno da popunimo druge vrednosti povezane sa telemetrijom dokumenta. Koristi se za dijagnostiku kvaliteta podataka.

- **Data_BytesAsynchronous** - Broj bajtova (komprimovanih) bez kojeg možemo da otvorimo datoteku ako ih preuzmemo pre nego što korisnik započne uređivanje ili čuvanje.

- **Data_BytesAsynchronousWithWork** - Broj bajtova (komprimovanih) bez kojeg možda možemo da otvorimo dokument, ali potrebno je značajno investiranje u kôd da bi se to omogućilo
    
- **Data_BytesSynchronous** - Broj bajtova (komprimovanih) koji moramo da imamo da bismo započeli otvaranje datoteke

- **Data_BytesUnknown** – Broj bajtova u segmentima dokumenta koji ne očekujemo da nađemo.

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

- **Data_Doc_RtcType** –  Označava kako je postavljen kanal u realnom vremenu (RTC) za trenutnu datoteku (onemogućeno, nepodržano, na zahtev, uvek uključeno itd.).

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

- **Data_PartsUnknown** – broj segmenata dokumenta za koji nismo mogli da dobijemo podatke

- **Data_RecoverableFailureInitiationLocationTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi da bi se identifikovalo mesto u kodu na kom pokušavamo da popravimo datoteku pre nego što je otvorimo

- **Data_RenameDisabledReason** - Greška koja uzrokuje da preimenovanje ovog dokumenta bude onemogućeno

- **Data_RenameFlightEnabled** - Da li je omogućena putanja za funkciju preimenovanja

- **Data_SecondaryTag** - Jedinstvena oznaka za lokaciju poziva koda koja se koristi za dodavanje dodatnih podataka o grešci otvaranja

- **Data_TemplateFormat** - Format datoteke predloška na kome je zasnovan dokument

- **Data_UsesNormal** - Ukazuje na to da li je otvoreni dokument zasnovan na normalnom predlošku


#### <a name="renewuserop"></a>RenewUserOp

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije potrebne za pravilno ispitivanje i dijagnostikovanje problema koji se dešavaju kada se izvrši operacija obnavljanja korisničkih sertifikata. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** – Id servera sistema za evidenciju

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji HTTP operacija

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije

- **RMS.Type** - Tip informacija o korisniku

#### <a name="servicediscoveryop"></a>ServiceDiscoveryOp

Sakuplja se kada korisnik pokuša da primeni IRM zaštitu na dokument. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom vršenja operacije otkrivanja usluga. 

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.Duration** - Ukupno vreme za dovršavanje operacije

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kôd bilo koje greške vraćen kao rezultat operacije

- **RMS.HttpCall** - Ukazuje na to da li postoji http operacija

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.OperationName** – Ime operacije

- **RMS.Result** - Uspešna ili neuspešna operacija

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa rezultata operacije


### <a name="office-accessibility-configuration-subtype"></a>*Podtip konfiguracije pristupačnosti sistema Office*

Funkcije pristupačnosti u sistemu Office

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Omogućava nam da otkrijemo da li korisnik ima alatku za pomoćnu tehnologiju i koje je njeno ime. Time možemo da razumemo da li korisnik sistema Office ima probleme sa određenom alatkom za pomoćnu tehnologiju.

Prikupljaju se sledeća polja:

  - **Data\_Data\_Jaws -** ukazuje na to da li je alatka „Jaws“ radila tokom sesije **Data\_Data\_Magic -** ukazuje na to da li je alatka „Magic“ radila tokom sesije

  - **Data\_Data\_Magnify -** ukazuje na to da li je alatka „Lupa“ radila tokom sesije

  - **Data\_Data\_Narrator -** ukazuje na to da li je alatka „Narator“ radila tokom sesije

  - **Data\_Data\_NVDA -** ukazuje na to da li je alatka „NVDA“ radila tokom sesije

  - **Data\_Data\_SA -** ukazuje na to da li je alatka „SA“ radila tokom sesije

  - **Data\_Data\_Supernova -** ukazuje na to da li je alatka „Supernova“ radila tokom sesije

  - **Data\_Data\_SuperNovaessSuite -** ukazuje na to da li je SuperNovaAccessSuite radio tokom sesije

  - **Data\_Data\_WinEyes -** ukazuje na to da li je alatka „WinEyes“ radila tokom sesije

  - **Data\_Data\_ZoomText -** ukazuje na to da li je alatka „Zumiranje teksta“ radila tokom sesije

#### <a name="officeappledarkmode"></a>Office.Apple.DarkMode

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam govori da li je korisnik pokrenuo sistem u Tamnom režimu i da li je korisnik zamenio postavku sistema Tamnog režima u aplikaciji Office.  Koristimo ovaj događaj da bismo obezbedili pristupačnost i odredili prioritete u optimizaciji korisničkog iskustva.

Prikupljaju se sledeća polja:

- **Data_DarkModeIsEnabled** - da li je Tamni režim omoguće u sistemu.

- **Data_RequiresAquaSystemAppearanceEnabled** - da li je Tamni režim zamenjen u aplikaciji Office.

#### <a name="officeapplehardwarekeyboardinuseapple"></a>Office.Apple.HardwareKeyboardInUse.Apple

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam govori da korisnik priključuje tastaturu na svoj mobilni uređaj. Događaj nam pomaže da poboljšamo pristupačnost i optimizujemo korisničko iskustvo.


Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka koja označava vreme prikupljanja događaja.

#### <a name="officeapplembuinstrumentdeviceaccessibilitysettings"></a>Office.Apple.MbuInstrument.DeviceAccessibilitySettings

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

  - **Data\_ParagraphCount -** broj pasusa u dokumentu

  - **Data\_Play -** Da li program Word čita naglas prvi put

  - **Data\_ViewKind -** Tip prikaza dokumenta

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Ovaj događaj ukazuje na to da je program Office Word prestao da čita naglas tekst iz dokumenta. Ovo omogućava korporaciji Microsoft da proceni ispravnost funkcije čitanja naglas tako što meri trajanje rada.

Prikupljaju se sledeća polja:

  - Nijedno

### <a name="privacy-subtype"></a>*Podtip privatnosti*

Postavke privatnosti za Office 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a>Office.IntelligentService.PrivacyConsent.PrivacyEvent

Ovaj događaj predstavlja akciju koju je pokrenuo korisnik ili sistem koji je deo korisničkog iskustva za Office. Pokreće se u dijalozima Prvo pokretanje privatnosti, dijalogu Privatnost naloga i obaveštenjima o privatnosti. Događaj se koristi da bi se razumelo sledeće: korisnici koji su saglasni sa postavkama privatnosti za Office, korisnici koji menjaju postavke privatnosti za Office i postavke privatnosti za Office koje se ažuriraju u korisničkim sesijama.

Prikupljaju se sledeća polja:

  - **Data_ActionId -** Radnja korisnika u dijalogu „Privatnost“

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

#### <a name="appstartupreason"></a>app.startup.reason

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde je Outlook pao tokom pokretanja aplikacije.  Ovaj događaj obuhvata informacije o tome zašto se pad dogodio, tako da brzo možemo da rešimo problem.

Prikupljaju se sledeća polja: 

- **app_background_time** - trajanje aplikacije u pozadini u poslednjoj sesiji

- **startup_reason_type** - označava zašto se aplikacija pokreće, to će ukazati na to da li je zbog toga što je prinudno zaustavljena ili zbog drugog razloga. 

- **watch_status_info** - prati sledeće informacije, ako je primenljivo. 

  - **is_watch_app_installed** - utvrđuje da li korisnik ima instaliranu Watch aplikaciju

  - **is_watch_paired** - utvrđuje da li je iOS uređaj uparen za sat

  - **is_watch_supported_and_active** - označava da li je sat podržan i aktivan tokom sesije

Sledeća polja se prikupljaju samo za Outlook Mobile za iOS:

- **clean_exit_reason** - niska reči koje ukazuju na to zašto je postojao razlog za zaustavljanje aplikacije

- **is_agenda_user** – označava da li je korisnik nedavno otvarao dnevni red koji ukazuje na to da li pišemo na disku za pokretanje

- **is_watch_supported_and_active** - označava da li je sat podržan i aktivan tokom sesije


#### <a name="applicationcrash"></a>application.crash

Koristi se za nadgledanje pada kritičnih aplikacija i pomaže nam da sakupimo informacije o tome zašto je aplikacija pala i kako da to sprečite.

Prikupljaju se sledeća polja: 

- **android.hardware.** – vrednosti konfiguracije hardvera (npr. android.hardware.bluetooth) koje pruža Android platforma

- **android.software.** – (npr. android. software.device_admin) vrednosti konfigurisanja softvera koje pruža Android platforma

- **android_version** - ime verzije Android na uređaju, kao što je naznačeno android.os.Build.VERSION#RELEASE

- **application_package_name** - ime paketa aplikacije kao što je naznačio android.content.Context#getPackageName()

- **application_stack_trace** - praćenje steka pri padu

- **application_version_code** - kôd verzije aplikacije definisane od strane aplikacije Outlook

- **application_version_name** - ime verzije aplikacije definisane od strane aplikacije Outlook 

- **com.** (e.g. com.google.android.feature.FASTPASS_BUILD, com.amazon.feature.PRELOAD, com.samsung.android.bio.face) Vrednosti konfiguracije specifične za proizvođača koje pruža Android platforma

- **crash_report_sdk** – SDK za slanje evidencija o padu. Ili Hockey ili AppCenter

- **crash_type** – crash_type će za tip imati java, osnovni i otklonjivi.

     - java – ako je pad zabeležen na sloju aplikacije.

     - osnovni – ako je pad zabeležen na osnovnom sloju unutar aplikacije. 

     - otklonjivi – padovi koji se zabeleže da bi se otklonile greške u bilo kojoj funkciji. Aplikacije neće pasti već će otpremiti evidencije o otklonjivim padovima radi lakšeg otklanjanja greške u funkciji.

- **device_brand** - marka uređaja (proizvođač ili operater) kao što je naznačio android.os.Build#BRAND

- **device_ID** - Jedinstveni ID uređaja (IMEI) *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali se i dalje može pojaviti u starijim verzijama.]*

- **device_manufacturer** - proizvođač uređaja kao što je naznačio android.os.Build#PROIZVOĐAČ

- **device_model** - model uređaja, kao što je označio android.os.Build#MODEL

- **device_name** - ime uređaja, kao što je označio android.os.Build#UREĐAJ

- **device_total_memory** - ocena ukupne veličine memorije uređaja na osnovu vrednosti datoteke okviru sistema datoteka.

- **glEsVersion** - OpenGL Embedded Systems verzije ključa


#### <a name="crashevent"></a>crash.event

Omogućava nam da otkrijemo i rešimo situacije u kojima su se desile kritične aplikacije za pad i pomaže nam da sakupimo informacije o tome zašto je aplikacija pala i kako da to sprečite.

Prikupljaju se sledeća polja: 

- **crashTime** - datum i vreme kada se pad dogodio da bi pomogao u vezi sa istragom

- **crash_time_from_start** – proteklo vreme od pokretanja aplikacije do rušenja, kao pomoć tokom istrage

- **exceptionName** – ime izuzetka koji je pokrenuo pad da bi pomogao u vezi sa istragom

- **exception_reason** – naziv razloga koji je izazvao rušenje kao pomoć tokom istrage

- **hasHx** - govori nam da nalog koristi našu novu uslugu sinhronizacije kako bi nam pomogao da otkrijemo probleme izazvane uslugom sinhronizacije

- **incidentIdentifier** - jedinstveni ID za izveštaj o padu tako da možemo da pronađemo odgovarajući problem

- **isAppKill** - pomaže nam da shvatimo da li je ta aplikacija prekinuta ili zatvorena na uređaju

- **is_crashloop** – Pomaže nam da razumemo kolika je verovatnoća da je pad petlja padova.

- **reportKey** - jedinstveni ID za instalaciju aplikacije om uređaj za istragu o problemima

- **signal** - signal koji je izazvao sudar daje nam više detalja da istražimo ovaj pad


#### <a name="error"></a>Greška

Dozvoljava nam da shvatimo probleme sa kojima se suočavaju aplikacije za mobilne uređaje kada pokušaju da pokupe postavke privatnosti sa servera.

Prikupljaju se sledeća polja:

- **correlationId** - jedinstveni identifikator za vezu usluge koja je rezultirala greškom, omogućavajući nam da ustanovimo šta je moglo da se pogreši

- **errorCode** - identifikuje relevantni kôd greške primljen od usluge koji se može koristiti za dijagnozu problema

- **exceptionType** - tip greške sa kojom se biblioteka susrela prilikom postavljanju postake

- **message** - prepoznaje poruku o grešci koju ste dobili od usluge

- **roamingSettingType** - identifikuje lokaciju od koje pokušavamo da pročitamo postavke

- **settingId** - postavka koja je Pokušana da se uradi

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Prikuplja informacije o nekontrolisanim izuzecima pomoću aplikacije Data Streamer. Ti podaci se koriste za praćenje ispravnosti aplikacije. Ovaj događaj je generisao programski dodatak Microsoft Data Streamer za Excel.

Prikupljaju se sledeća polja:

- **Exception** - Niz poziva za izuzetak

- **Event Name** - Ime događaja, što je kategorija i oznaka događaja

#### <a name="officeappleidentitydomainname"></a>Office.Apple.IdentityDomainName

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja našeg sistema kao i za istraživanje uzroka neuspeha određenih korisnika domena. Prikupljamo domen koji koriste naši korisnici prilikom potvrde identiteta.  Ove podatke koristimo da bismo pomogli da identifikujemo i ispravimo one probleme koji na širem nivou možda ne deluju previše uticajno, ali za koje se ispostavi da su vrlo uticajni za određeni domen korisnika.

Prikupljaju se sledeća polja:

- **Data_Domain** - domen koji se koristi za potvrdu identiteta

- **Data_IdentityProvider** - ime dobavljača identiteta za potvrdu identiteta. (to jest, Ћiveid ili ADAL)

- **Data_IdentityProviderEnum** - kod dobavljača identiteta za potvrdu identiteta. (Broj)

#### <a name="officeapplesystemhealthappexitmacandios"></a>Office.Apple.SystemHealthAppExitMacAndiOS

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

Upotreba: koristi se za računanje globalnog „usvajanja“ programa Microsoft 365 Apps za neodređena velika preduzeća za dodatak koji zatim koriste druge alatke kao što je Readiness Toolkit. To omogućava poslovnim kupcima da provere da li su programski dodaci koje su ugradili u njihove organizacije kompatibilni sa najnovijim verzijama programa Microsoft 365 Apps i da na odgovarajući način planiraju nadogradnje. 

Prikupljaju se sledeća polja:

- **ScopeId** - trenutni opseg niti

- **Method** - Office metod u kome je došlo do izuzetka

- **Interface** - Interfejs sistema Office u kome je došlo do izuzetka

- **AddinId** – ID klase programskog dodatka

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

Upotreba: koristi se za računanje globalnog „usvajanja“ programa Microsoft 365 Apps za neodređena velika preduzeća za dodatak koji zatim koriste druge alatke kao što je Readiness Toolkit. To omogućava poslovnim kupcima da provere da li su programski dodaci koje su ugradili u njihove organizacije kompatibilni sa najnovijim verzijama programa Microsoft 365 Apps i da na odgovarajući način planiraju nadogradnje. 

- **ScopeId** - trenutni opseg niti

- **Method** - Office metod u kome je došlo do izuzetka

- **Interface** - Interfejs sistema Office u kome je došlo do izuzetka

- **AddinId** – ID klase programskog dodatka

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

- **IsArm64** – ukazuje na to da li se aktivacija programskog dodatka odvija na aplikaciji emuliranoj na ARM64 uređaju

- **IsAugmentationScenario** – Označava da li je petlja za proširenje odgovorna za pokretanje kontrole okvirnog sistema Office Solutions

- **IsDebug**-označava da li je ta sesija namenjena za otklanjanje grešaka

- **IsPreload** – označava da li je programski dodatak unapred učitan u pozadini radi unapređenja učinka aktivacije.

- **IsWdagContainer** – ukazuje na to da li se aktivacija programskog dodatka obavlja u kontejneru Application Guard Windows zaštitnika.

- **NumberOfAddinsActivated**- Brojač aktivnih programskih dodataka

- **RemoterType** – Precizira tip daljinca (pouzdanih, nepouzdanih, Win32webView, pouzdanih UDF-ova itd.) koji se koristi za aktiviranje programskog dodatka

- **StoreType** – Poreklo aplikacije

- **Tag**- navodi gde tačno kod nije uspeo pomoću jedinstvene oznake koja je s njim povezana.

- **UsesSharedRuntime** - označava da li aplikacija koristi sharedRuntime ili ne.


#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Događaj koji se generiše kada datoteka sa omogućenim makroima naiđe na grešku u kompajliranju ili izvršavanju.

Analitika za stone računare: Koristi se kao brojilac za izračunavanje statusa ispravnosti tipova makroa (npr. makro u programu Word, u programu Excel, itd.) u određenim velikim preduzećima, što služi da se tokom probe odredi da li je programski dodatak „spreman za ažuriranje“ u proizvodnom krugu.

Prikupljaju se sledeća polja:

- **TagId** – id oznake telemetrije

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

Prikuplja podatke o upotrebi funkcije pri svakoj PowerPoint sesiji.  Ti podaci se koriste za izračunavanje stope nasilnih izlaza iz programa PowerPoint prilikom upotrebe funkcije. Stopa nasilnih izlaza iz programa PowerPoint predstavlja ključni pokazatelj koji garantuje da se program izvršava kao što je očekivano.

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

Prikuplja podatke o tome koja funkcija je korišćena u dokumentu u trenutku kada je PowerPoint nasilno zatvoren. Ove funkcije uključuju projekciju slajdova, otvaranje dokumenta, čuvanje, uređivanje, koautorstvo, isključivanje. Te informacije su bitne da bi se primetili nasilni izlasci iz programa PowerPoint prilikom upotrebe funkcije. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

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

Prikuplja se svaki put kada se PowerPoint nasilno zatvori prilikom otvaranja dokumenta. Te informacije su bitne da bi se primetili nasilni izlasci iz programa PowerPoint prilikom otvaranja dokumenta. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

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

Prikuplja podatke o tome koja funkcija je korišćena u trenutku kada je PowerPoint sesija nasilno zatvorena.  Te informacije su bitne da bi se primetili nasilni izlasci iz programa PowerPoint. Microsoft koristi te podatke da bi dijagnostikovao problem i osigurao izvršavanje programa kao što je očekivano.

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


#### <a name="officeprogrammabilityaddinscomaddincrash"></a>Office.Programmability.Addins.COMAddInCrash 

Događaj koji se generiše kada padne programski dodatak COM. Koristi se za utvrđivanje problema sa usvojenjem i pouzdanošću pomoću programskih dodataka za Office. 

Prikupljaju se sledeća polja:

- **AddinConnectFlag** – ponašanje opterećenja  

- **AddinDescriptionV2** –opis programskog dodatka 

- **AddinFileNameV2** –ime stvarnog programskog dodatka DLL–a. Ne obuhvata lokaciju datoteke.

- **AddinFriendlyNameV2** – prepoznatljivo ime programskog dodatka

- **AddinIdV2** –ID razreda programskog dodatka (CLSID)

- **AddinProgIdV2** –ID prog–a za programski dodatak 

- **AddinProviderV2** – dobavljač programskog dodatka 

- **AddinTimeDateStampV2** – vremenska oznaka kompajlera

- **AddinVersionV2** –programski dodatak 

- **Interface** –COM interfejs programskog dodatka koji je doveo do mesta za pad 

- **Load** –koliko pokušaja učitavanja je napravljeno pre nego što je pao 

- **Method** –COM metodu programskog dodatka, koji je doveo do nesrece 

- **OfficeArchitecture** – Arhitektura Office klijenta

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

Pokrenut pri otvaranju datoteke koja sadrži makro (VBA) na uređaju koji je IT administrator uveo u sistem korišćenja Office aplikacija kao usluge (OAAS) i gde je Microsoft 365 Apps za velika preduzeća aktiviran pomoću licence za velika preduzeća. Događaj se koristi za razumevanje ispravnosti datoteka koje sadrže makro (VBA) u zakupcu i upoređuje se sa Office.Programmability.Telemetry.VbaTelemetryBreak koji prati greške na datotekama koje sadrže VBA. 

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


#### <a name="onenotesafebootaction"></a>OneNote.SafeBootAction

Ovo se pokreće tokom pokretanja aplikacije ako se aplikacija srušila u prethodnoj sesiji. Ovi podaci se koriste za praćenje novih rušenja i pomoći će nam da utvrdimo da li logika otkrivanja rušenja radi ispravno i da pratimo broj rušenja i ranih rušenja.

Prikupljaju se sledeća polja: 

- **ActionType** – moguće vrednosti – IncrementCount, ResetBootCounter, ResetEarlyCounter

- **IsLoopCrash** – moguće vrednosti – Da/Ne

- **IsNativeCrash** – moguće vrednosti – Da/Ne


#### <a name="onenotesafebootresetcrashcounteronappsuspend-officeonenoteandroidsafebootresetcrashcounteronappsuspend-officeandroidearlytelemetrysafebootresetcrashcounteronappsuspend"></a>OneNote.SafeBootResetCrashCounterOnAppSuspend, Office.OneNote.Android.SafeBootResetCrashCounterOnAppSuspend, Office.Android.EarlyTelemetry.SafeBootResetCrashCounterOnAppSuspend

Kritični signal se šalje kada uspostavljamo početne vrednosti brojača padova pri obustavljanju aplikacije pre prikazivanja dijaloga za bezbedno pokretanje. Ovaj obeleživač je obavezan za praćenje i dijagnozu ispravnosti aplikacije. Dijalog za bezbedno pokretanje se prikazuje kada aplikacija padne više puta uzastopno. Daje korisniku opciju da uspostavi početne vrednosti aplikacije. Ovaj obeleživač će vam pomoći da shvatite ako dijalog za bezbedno pokretanje nije prikazan korisniku uprkos dostizanju kriterijuma za aktiviranje. 

Prikupljaju se sledeća polja:

- Nijedno


#### <a name="telemetryerror"></a>telemetry.error

Ovaj događaj omogućava nam da ustanovimo i popravimo probleme koji sprečavaju stvaranje ili slanje potrebnih dijagnostičkih podataka. Ovi događaji nam pomažu da shvatimo da li nam nedostaju kritički podaci neophodni za identifikovanje problema sa bezbednosnim problemima ili važnih problema sa načinom rada aplikacije.

Prikupljaju se sledeća polja: 

- **timer_name** - govori nam gde se problem telemetrije dešava, na primer, u komponenti poštanskog sandučeta ili u kalendaru. To nam pomaže da otkrijemo i rešimo problem sa telemetrijom koji se dešava u određenom delu aplikacije

- **type** - saopštava tip greške tajmera koji će nam pomoći da otkrijemo kada aplikacija ima bilo kakvih problema sa slanjem dijagnostičkih telemetrijskih podataka


#### <a name="watchdoganr"></a>watchdog.anr

Potrebno za nadgledanje grešaka performansi aplikacije za sprečavanje slučajeva u kojima aplikacija prestaje da se odaziva i ekran se zamrzava u aplikaciji (naziva se "ANR-aplikacija" ne odgovara).

Prikupljaju se sledeća polja: 

- **callstack** - kalvansko korišćenje mesta na kom je došlo do ANR
 
- **caused_restart** - bilo da je aplikacija primorana da se ponovo pokrene zbog ANR-a
 
- **duration** - koliko vremena je uređaj bio zamrznut
 
- **id** - jedinstveni identifikator za ANR
 
- **interval** - konfigurisani cenzus za aktiviranje
 
- **is_application_object_initialized** - bez obzira na to da li se ANR desio kada je aplikacija potpuno pokrenuta ili pre
 
- **last_known_is_in_foreground** - bez obzira na to da li je aplikacija nedavno bila u prednjem planu ili u pozadini


### <a name="application-feature-performance-subtype"></a>*Podtip performanse funkcija aplikacije*

Loše vreme odziva ili performansi u scenarijima kao što su pokretanje aplikacije ili otvaranje datoteke.

#### <a name="androidframemetrics"></a>android.frame.metrics

Omogućava nam da otkrijemo i rešimo situacije u kojima aplikacije Android aplikacije izazivaju probleme sa performansama, na primer, ako prijemno sanduče se ne pomera glatko

Prikupljaju se sledeća polja: 

- **animation_duration** - trajanje vizuelizacije animacije u milisekundama

- **command_issue_duration** - trajanje komande za izdavanje komandi platformi u milisekundama 

- **draw_duration** - trajanje izvlačenja korisničkog interfejsa u milisekundama 

- **input_handling_duration** - trajanje upravljanja unosom u milisekundama 

- **layout_measure_duration** - trajanje merenja rasporeda u milisekundama

- **origin** - komponenta aplikacija koja je merena, na primer kalendar ili pošta

- **sync_duration** - trajanje sinhronizacije okvira u milisekundama

- **swap_buffers_duration** - trajanje razmene bafera u milisekundama

- **total_duration** - ukupno trajanje prikazivanja okvira u milisekundama

- **unknown_delay** - odlaganje koji su izazvali nepoznati izvori osim izričito praćenih trajanja

#### <a name="calcomponent"></a>cal.component

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde postoji uticaj učinka na komponente korisničkog interfejsa kalendara koji bi izazvali da kalendar ima problema sa pomeranjem.

Prikupljaju se sledeća polja: 

- **above_40fps** – prebrojavanje okvira prikazanih preko 40 o/s

- **above_40rate** – radio okvira prikazanih preko 40 o/s

- **above_50fps** – broj okvira prikazanih preko 50 o/s

- **above_50rate** – radio okvira prikazanih preko 50 o/s

- **above_55fps** – prebrojavanje okvira prikazanih preko 55 o/s

- **above_55rate** – radio okvira prikazanih preko 55 o/s

- **account_counter** –prati broj naloga povezanih za svaku vrstu kalendara, npr. 2 za Gmail kalendar i da li taj nalog koristi našu novu uslugu sinhronizacije

- **app_instance** – Outlook ima 2 ulazna mesta za duo, jedan je za kalendar i jedan je za poštu i oba mogu da se lansiraju uporedo u okruženju sa više instanci. Tako ćemo znati koja instanca obavlja ovaj poziv izveštavanja, bilo poštom ili kalendarom

- **component_name** – govori nam ime komponente kalendara, kao što je prikaz dnevnog reda ili prikaz dana, kako bi nam pomogao da otkrijemo probleme sa performansama koji utiču na određenu komponentu u kalendaru

- **display_frame_data** - prati vreme provedeno na prikazivanju svih 60 okvira da biste utvrdili da li postoje problemi sa performansama. 

- **orientation** - govori nam da li je uređaj bio u uspravnom ili položenom režimu da bi nam pomogao da otkrijemo probleme sa performansama koji utiču na određeni položaj uređaja

- **taskId** – TaskId će nam dati taskId aktuelne instance. Ovo će biti obavezno u okruženju sa više instanci ako korisnik želi da uporedo lansira iste instance (kalendar, kalendar ili pošta, pošta)

- **view_duration** - govori nam koliko vremena je potrebno da se različite komponente kalendara korisničkog interfejsa pomognu da otkriju problem sa performansama koji utiču na iskustvo pri radu sa kalendarom

#### <a name="contactaction"></a>contact.action

Ovaj događaj se pokreće na različitim radnjama u vezi sa kontaktima – prikazom, ažuriranjem i brisanjem kontakata, kao i pregledanjem spiska kontakata. Koristi se za utvrđivanje da li postoje regresije performansi koja imaju veze sa kontaktima.

Prikupljaju se sledeća polja: 

- **accounts_with_filters** – broj naloga sa filterima primenjenim na listu kontakata

- **radnja** – radnja koja je izvršena, npr. prikazivanje kontakta
 
- **duration_initial_view_load** – trajanje od otvaranja prikaza do početnog učitavanja spiska kontakata

- **duration_show_contacts** – trajanje od otvaranja prikaza do prikazivanja kontakata na spisku kontakata
 
- **total_contacts** – broj kontakata koji nemaju primenjene filtere
 
- **total_filtered_contacts** – broj kontakata sa primenjenim filterima

#### <a name="conversationloadtime"></a>conversation.load.time

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde postoji uticaj učinka na učitavanje razgovora e-pošte kako bi se osiguralo da se e-poruke učitavaju na očekivani način.

Prikupljaju se sledeća polja: 

- **time** - daje nam količinu vremena za dovršavanje učitavanja e-poruke.

#### <a name="conversationreloaded"></a>conversation.reloaded

Ovaj događaj nam omogućava da otkrijemo koliko često ponovo učitavamo konverzaciju na osnovu obaveštenja o usluzi. Moramo da pratimo da li su obaveštenja o ažuriranju preglasna i da li ih treba smanjiti jer narušavaju upotrebljivost.

Prikupljaju se sledeća polja: 

- **average** – količina ponovnog učitavanja podeljena veličinom 

- **client–request–ID** – identifikator zahteva klijenta za zahtev koji je izazvao grešku

- **date** – oznaka datuma zahteva koji je izazvao grešku

- **duration** – vreme kada je razgovor bio otvoren 


#### <a name="coredatamigration"></a>core.data.migration

Dozvoljava nam da otkrijemo i popravimo situacije u kojima je došlo do greške u ažuriranju podataka e-pošte na uređaju novije verzije.

Prikupljaju se sledeća polja:

- **db_size_megabytes** - prati veličinu osnovne baze podataka zaokruženu na najbližih 25 megabajta i maksimalnih 500 megabajta

- **db_wal_size_megabytes** – prati veličinu baze podataka osnovnih podataka kada je glavna datoteka skladišta netaknuta zaokružena na najbližih 1 megabajt i sa maksimalnih megabajt 10

- **free_space_megabytes** - prati besplatno prazno mesto u kontejnerima 10, 100, 1000, 10.000, a zatim 100.000. 

- **migration_duration_seconds** - praćenje trajanja migracije zaokruženog na jedan od ovih vremenskih intervala - 0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180 (180 i izvan treba samo da bude 180)

#### <a name="coredataperformance"></a>core.data.performance

Dozvoljava nam da otkrijemo i popravimo situacije u kojima podaci e-pošte koje skladištimo na uređaju izazivaju problem sa performansama.

Prikupljaju se sledeća polja:

- **Caller** - praćenje imena entiteta koji je pokrenuo operaciju čuvanja

- **db_size_megabytes** - prati veličinu osnovne baze podataka zaokruženu na najbližih 25 megabajta i maksimalnih 500 megabajta

- **duration** - prati vreme koje je potrebno za dovršavanje operacije

- **entity** - praćenje imena entiteta koji je pokrenuo operaciju dobavljanja

- **operation** – RAW vrednosti operacije bilo da je "Sačuvaj", "Donesi" ili "Red za pisanje čitanja je blokiran"

#### <a name="inboxcomponent"></a>inbox.component

Ovaj događaj prikuplja dve vrste korisničkih podataka: status pretplate na Microsoft 365 i vidi li korisnik oglase. Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde postoji uticaj učinka na komponente korisničkog interfejsa prijemnog sandučeta koji bi izazvali da poruke e–pošte, avatar, pročitano/nepročitano stanje se ne učita ili ne prikaže ispravno.

Prikupljaju se sledeća polja: 

- **above_40fps** – prebrojavanje okvira prikazanih preko 40 o/s

- **above_40rate** – radio okvira prikazanih preko 40 o/s

- **above_50fps** – broj okvira prikazanih preko 50 o/s

- **above_50rate** – radio okvira prikazanih preko 50 o/s

- **above_55fps** – prebrojavanje okvira prikazanih preko 55 o/s

- **above_55rate** – radio okvira prikazanih preko 55 o/s

- **account_counter**- prebrojavanje za svaki tip naloga koji je prisutan na uređaju, na primer, Office 365 nalog = 1 nalog, Outlook.com nalog = 1 nalog.

- **ad_not_shown_reason** - razlog zašto se oglasi ne prikazuju

- **ad_shown** - da li je reklama prikazana (ako su reklame omogućene)

- **ad_shown_for_premium** – neočekivan prikaz oglasa premium korisnicima

- **age** – dob osobe (koristi se za potvrdu usaglašenosti s uzrasnim ograničenjima za oglase) *[Ovo je polje uklonjeno iz trenutnih izdanja sistema Office, ali može se i dalje prikazivati u drugim izdanjima.]*

- **app_instance** – Outlook ima 2 ulazna mesta za duo, jedan je za kalendar i jedan je za poštu i oba mogu da se lansiraju uporedo u okruženju sa više instanci. Tako ćemo znati koja instanca obavlja ovaj poziv izveštavanja, bilo poštom ili kalendarom

- **component_name** – ime komponente/prikaz koji je aktivan tokom filtriranja

- **has_hx** – da li uređaj ima barem jedan HxK (naša nova usluga za sinhronizaciju e-pošte)

- **has_subscription** - da li uređaj ima pretplatu na oglase

- **is_all_accounts_inbox** – bez obzira na to da li je aktuelno prijemno sanduče „Svi nalozi“ fascikla

- **is_current_account** - bez obzira na to da li je aktuelni aktivni nalog, nalog oglasa

- **load_error_code** - kôd greške prilikom učitavanja oglasa

- **network_error_code** - kôd greške mreže prilikom zahteva oglasa

- **orientation** - položaj ekrana u trenutku ravnomernosti (uspravno ili položeno)

- **provider** – dobavljač usluge (Xandr ili Facebook) oglasa koji se trenutno prikazuje

- **sub_error_type** - detaljan tip greške

- **taskId** – TaskId će nam dati taskId aktuelne instance. Ovo će biti obavezno u okruženju sa više instanci ako korisnik želi da uporedo lansira iste instance (kalendar, kalendar ili pošta, pošta)

- **total_count** - ukupni okviri koje prikazuje komponenta

- **view_duration** - koliko dugo korisnik prikazuje komponentu

#### <a name="initialpagelanding"></a>Initial.page.landing 
 
Ovaj događaj vam pomaže da pratite tip iskustva koju korisnici vide kada otvore stranicu naše aplikacije.  Ovi podaci se koriste za utvrđivanje prometa korisnika ugrađenih u svako iskustvo u našoj aplikaciji, i takođe nam pomažu da lako konsolidujemo rezultate eksperimentisanja.
 
Prikupljaju se sledeća polja: 

- **Page** - koristi se za praćenje tipa iskustva koje korisnik prvi put vidi kada otvori našu stranicu. Moguće vrednosti su: „Probna verzija“, „Preskoči“, „Prepakovano“, „Pretplata“, itd.

- **storeExperience** - ovo se koristi da se utvrdi da li je korisnik imao pravo da vidi iskustvo prodavnice SDK.

- **stringVariant** - ovo se koristi za utvrđivanje tipa niski koje korisnik vidi kada otvori našu stranicu. Imajte u vidu da za bilo koju stranicu, kao što je recimo „Probna verzija“, korisnik može da ima pravo da vidi različite niske na osnovu toga da li su imale instaliranu stariju verziju aplikacije Office ili ako su prethodno aktivirali Office. Moguća nabrajanja ovog svojstva su: „LegacyUpsell“, „OfficeOpened“, „Default“, YesIntent“, „NoIntent“, itd.

- **windowsBuildType** - koristi se za praćenje WindowsBuildType tipa na kojem je korisnik. Npr. „RS4“, „RS5“, „RS19H1“, „Vibranium“, itd. Pošto su naša iskustva obično usmerena na različite WindowsBuildTypes tipove, ovo svojstvo je od vitalne važnosti za razlikovanje objavljenih tipova. 

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpBootstrapUser API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionInfo.ExtranetUrl** - Informacije o URL adresi veze spoljne mreže

- **RMS.ConnectionInfo.IntranetUrl** - Informacije u URL adresi veze intranet mreže

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje HTTP operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga  

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima 

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** – Id korisničkog objekta

#### <a name="ipcpgetkey"></a>IpcpGetKey

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije koje su potrebne da bismo mogli pravilno da istražimo i dijagnostikujemo probleme koji se događaju prilikom IpcpGetKey API poziva.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **iKey** - Id servera usluge vođenja evidencije

- **RMS.ApplicationScenarioId** – Id scenarija koji obezbeđuje aplikacija

- **RMS.AuthCallbackProvided** - Ukazuje na to da li pruža povratni poziv potvrde identiteta kao unos API poziva ili ne

- **RMS.ConnectionMode** - Režim veze između klijenta usluge Rights Management Service i servera: na mreži ili van mreže

- **RMS.ContentId** – Id sadržaja dokumenta

- **RMS.Duration** - Ukupno vreme za dovršavanje API poziva

- **RMS.DurationWithoutExternalOps** – Ukupno vreme umanjeno za spoljne operacije, kao što je mrežno vreme kašnjenja.

- **RMS.ErrorCode** - Kod bilo koje greške vraćen kao rezultat API poziva

- **RMS.EulId** – ID licence krajnjeg korisnika

- **RMS.EulProvided** – Označava da li obezbeđuje licencu krajnjeg korisnika kao unos API poziva ili ne

- **RMS.GuestTenant** – Id privremenog zakupca za korisnika 

- **RMS.HomeTenant** – Id stalnog zakupca za korisnika

- **RMS.HttpCall** - označava postojanje http operacije

- **RMS.Identity.ExtranetUrl** - URL adresa spoljašnje mreže servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera preuzima novi Certifikat o pravima naloga

- **RMS.Identity.IntranetUrl** - Intranet URL adresa servera Usluge za upravljanje pravima za korisnika, koja se prikuplja dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.Identity.Status** - Vreme prvog ili ponovnog pribavljanja Certifikata o pravima naloga od servera 

- **RMS.Identity.Type** - Tip korisničkog naloga kao što je Windows nalog ili live nalog

- **RMS.Identity.UserProvided** - Ukazuje na to da li jeste ili nije obezbeđena korisnička adresa e-pošte dok se od servera pribavlja novi Certifikat o pravima naloga

- **RMS.IssuerId** – Id servera Usluge upravljanja pravima koji izdaje Certifikat o pravima naloga 

- **RMS.KeyHandle** - Memorijska adresa pokazivača ključa

- **RMS.LicenseFormat** - Format licence: Xrml ili Json

- **RMS.PL.ExtranetUrl** – URL ekstraneta u licenci za objavljivanje

- **RMS.PL.IntranetUrl** – URL intraneta u licenci za objavljivanje

- **RMS.PL.KeyType** – Vrednosti „Jedan“ ili „Dupli“ Ukazuje na to da li je PL zaštićen pomoću zaštite jednim ključem ili zaštite duplim ključem

- **RMS.RACType** - Tip Certifikata o pravima naloga

- **RMS.Result** - Uspešan ili neuspešan API poziv

- **RMS.ScenarioId** – Id scenarija definisan API–jem

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

- **RMS.ServerType** - Tip servera Usluge upravljanja pravima

- **RMS.StatusCode** - Kod statusa vraćenog rezultata

- **RMS.TemplatesCount** - Broj predložaka

- **RMS.TokenProvided** - Označava da li obezbeđuje token kao unos API poziva ili ne 

- **RMS.TokenProvided** - Označava da li obezbeđuje korisnika kao unos API poziva ili ne 

- **UserInfo.UserObjectId** – Id korisničkog objekta

#### <a name="jsonparseerror"></a>json.parse.error 
 
Ovaj događaj označava da je grešku ubacio JSON analizator.  Moći ćemo da otklonimo grešku pročitanog registra niske koja je poslata u JSON analizator, da bismo omogućili glatko iskustvo našim korisnicima.
 
Prikupljaju se sledeća polja: 

- **Error** - sastoji se od poruke o grešci koju objekt greške vraća.

#### <a name="mailfiltercomponent"></a>mail.filter.component

Ovaj događaj nam omogućava da otkrijemo i rešimo probleme tamo gde postoji uticaj učinka na iskustvo filtriranja pošte što bi izazvalo da se filteri ne učitaju ili prikažu ispravno.

Prikupljaju se sledeća polja: 

- **above_40fps** – prebrojavanje okvira prikazanih preko 40 o/s

- **above_40rate** – radio okvira prikazanih preko 40 o/s
 
- **above_50fps** – broj okvira prikazanih preko 50 o/s

- **above_50rate** – radio okvira prikazanih preko 50 o/s
 
- **above_55fps** – prebrojavanje okvira prikazanih preko 55 o/s

- **above_55rate** – radio okvira prikazanih preko 55 o/s
 
- **account_counter**- prebrojavanje za svaki tip naloga koji je prisutan na uređaju, na primer, Office 365 nalog = 1 nalog, Outlook.com nalog = 1 nalog.
 
- **ad_not_shown_reason** - razlog zašto se oglasi ne prikazuju
 
- **ad_shown** - da li je reklama prikazana (ako su oglasi omogućeni)
 
- **age** - starost osobe (koja se koristi za potvrdu usaglašenosti sa ograničenjima uzrasta na oglasima)

- **app_instance** – Outlook ima 2 ulazna mesta za duo, jedan je za kalendar i jedan je za poštu i oba mogu da se lansiraju uporedo u okruženju sa više instanci. Tako ćemo znati koja instanca obavlja ovaj poziv izveštavanja, bilo poštom ili kalendarom
 
- **component_name** – ime komponente/prikaz koji je aktivan tokom filtriranja
 
- **folder_type** – tip fascikle koja se filtrira (npr. prijemno sanduče, smeće, nesistemsko)
 
- **has_hx** - da li uređaj ima barem jedan Hx nalog (novi servis za sinhronizaciju e-pošte)
 
- **has_subscription** - da li uređaj ima pretplatu na oglase
 
- **is_all_accounts_inbox** – bez obzira na to da li je aktuelno prijemno sanduče „Svi nalozi“ fascikla
 
- **is_current_account** - bez obzira na to da li je aktuelni aktivni nalog, nalog oglasa
 
- **load_error_code** - kôd greške prilikom učitavanja oglasa
 
- **network_error_code** - kôd greške mreže prilikom zahteva oglasa
 
- **orientation** - položaj ekrana u trenutku ravnomernosti (uspravno ili položeno)
 
- **sub_error_type** - detaljan tip greške

- **taskId** – TaskId će nam dati taskId aktuelne instance. Ovo će biti obavezno u okruženju sa više instanci ako korisnik želi da uporedo lansira iste instance (kalendar, kalendar ili pošta, pošta)
 
- **total_count** - ukupni okviri koje prikazuje komponenta
 
- **view_duration** - koliko dugo korisnik prikazuje komponentu

#### <a name="messagerenderingintercepted"></a>message.rendering.intercepted

Ovaj događaj nam omogućava da pratimo koliko često korisnici presreću postupak prikazivanja pre nego što je završen. Podatke koristimo kako bismo otkrili probleme u radu.

Prikupljaju se sledeća polja: 

- **is_cache** – da li je tijelo poruke učitano iz keširanja

- **is_on_screen** – da li je proces prikazivanja vidljiv korisnicima (normalno prikazivanje)

- **is_rendering_complete** – da li se proces prikazivanja dovršio 

- **is_trimmed_body** – da li je telo poruke skraćeno tijelo 

- **rendering_method** – metod prikazivanja poruke

- **rendering_time** – trajanje prikazivanja poruke dok korisnik ne napusti stranicu

#### <a name="messagerenderingperformance"></a>message.rendering.performance

Ovaj događaj nam omogućava praćenje performansi procesa prikazivanja poruka, tako da možemo analizirati performanse različitih procesa prikazivanja i otkriti probleme sa performansama. 

Prikupljaju se sledeća polja: 

- **bundle_prepare_time** – vreme za pripremu paketa za prikazivanje

- **full_rendering_time** – vreme punog procesa prikazivanja

- **is_cache** – da li je tijelo poruke učitano iz keširanja

- **is_on_screen** – da li je proces prikazivanja vidljiv korisnicima (normalno prikazivanje)

- **is_trimmed_body** – da li je telo poruke skraćeno tijelo 

- **load_message_time** – vreme učitavanja poruke sa pozadine (može biti 0 ako je poruka keširana)

- **native_preprocess_time** – vreme za prethodnu obradu tela poruke na izvornoj strani 

- **prepare_body_time** – vreme za pripremu tela poruke (uključujući poruku učitavanja i predobrade)

- **rendering_method** – metod prikazivanja poruke

- **rendering_time** – vreme za prikazivanje poruke po paketu  

- **wait_time** – vreme za pravljenje URL adrese poruke


#### <a name="officeandroidandroidofficelaunchtolandingpagelatency"></a>Office.Android.AndroidOfficeLaunchToLandingPageLatency

Veoma važno za snimanje metrike performansi aplikacije u odnosu na vreme odziva aplikacije od pokretanja.  Microsoft koristi ovo da prikuplja informacije o vremenu utrošenom da bi se aplikacija odazvala i za otkrivanje scenarija koji utiču na vreme pokretanja u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:
 
- **AnyCrashInteractionDuringBoot** - Logička vrednost za bilo kakav pad aplikacije tokom pokretanja

- **AppActivationTimeInMs** - Vremenska faza aplikacije

- **AppSuspendedDuringBoot** - Logička vrednost za obustavljanje aplikacije tokom pokretanja

- **AvailableMemoryInMB** - Dostupna memorija

- **CollectionTime** - Vreme događaja

- **DalvikHeapLimitInMB** - Podaci o dinamičkoj memoriji

- **DocumentRecoveryInvoked** - Logička vrednost koja označava da li je bilo koji dokument oporavljen

- **ExtractionDone** - Vreme izdvajanja izvorne biblioteke

- **FastBootGainTimeInMs** - Vreme za dovršavanje brzog pokretanja

- **FileActivationAttempted** - Logička vrednost koja ukazuje na to da li je aplikacija pokrenuta zbog pokretanja datoteke

- **HasLogcatLoggingImpactOnBoot** - Logička vrednost koja ukazuje na to da li je evidencija uticala na vreme pokretanja

- **IsThisFirstLaunch** - Logička vrednost koja ukazuje na to da li je ovo prvo pokretanje aplikacije

- **LatencyTimeInMilliSec** - kašnjenje izraženo u milisekundama

- **LibrarySharingTimeInMs** - Vreme za deljenje biblioteka

- **LoadMinLibsTimeInMs** - Vreme učitavanja minimalnog skupa biblioteka

- **MruListingTimeInMs** - Vreme učitavanja MRU-a

- **NativeLibrariesLoadTime** - Vreme učitavanja CPP biblioteke

- **NumberOfRunningProcesses** - broj pokrenutih procesa

- **NumberOfRunningProcesses** - Broj pokrenutih procesa

- **NumberOfRunningProcesses** - Broj pokrenutih usluga

- **OfficeActivityTimeInMs** - Vreme za pokretanje Office aktivnosti

- **PostAppInitTimeInMs** - Vremenska faza aplikacije

- **PreAppInitializationTime** - Vreme pokretanja faze aplikacije

- **PreAppInitTimeInMs** - Vremenska faza aplikacije

- **TotalMemoryInMB** - ukupna memorija

- **UIRaaSDownloadLanguagePackageBoot** - podaci vezani za preuzimanje jezičkog paketa

- **UserDialogInterruptionDuringBoot** - Logička vrednost za bilo koji blokirajući dijalog koji se prikazuje tokom pokretanja


#### <a name="officeandroiddocsuiviewsdimepurchaseflowstate"></a>Office.Android.DocsUI.Views.DimePurchaseFlowState

Ovaj zdravstveni događaj pokušava da zabeleži svako stanje kroz koje korisnik prolazi kada korisnik pokušava da napravi kupovinu putem toka kupovine u aplikaciji koji hostuje Dime. Podaci se koriste za nadgledanje i obaveštavanje o stanju toka kupovine koji se pokreće iz Office Mobile aplikacije kada korisnik odluči da kupi Microsoft 365 pretplatu.

Prikupljaju se sledeća polja:

- **EntryPoint** – Ulazna tačka kupovine koju je pokušao korisnik

- **OEMPreInstaled** – Identifikuje da li je korisnik unapred instalirao ili organski instalirao aplikaciju

- **PurchaseState** – stanje korisnika prilikom pokušaja kupovine
    - 0 – Nepoznata greška
    - 1 - Korisnik pokušava da otvori Dime
    - 2 – Greška na mreži
    - 3 – Dime se pokazuje korisniku
    - 4 - Korisnik otkazuje Dime
    - 5 – Potrebno je osvežavanje jer je kupovina uspešno obavljena
    - 6 – Kupovina je uspešno obavljena
    - 7 - Generičke dime greške
    - 8 - Nije moguće snimiti dime telemetriju zbog neuspele komunikacije
    - 9 - Dva pokrenuta programa "Dime" izazivaju prekid
    - 10 – Osnovni WebURL učitan na aplikaciju officemobile je nevažeći
    - 11 – Komunikacija aplikacije officemobile sa Dime nije uspela 
    - 12 – Nije moguće uspostaviti nijedan kanal komunikacije
    - 13 – ID komunikacije nije moguće poslati u Dime
    - 14 – Officemobile aplikacija se prenosi sa pogrešnom krajnjom tačkom
    - 15 – AuthToken nije dobijen za ovaj MSA nalog
    - 16 – AuthToken nije poslat u Dime

- **WebViewShownDuration** – vreme tokom kog se stranica sa dime kupovinom prikazuje korisniku 


#### <a name="officeappleappleappbootmac"></a>Office.Apple.Apple.AppBoot.Mac

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

- **Data_IsFirstRunAttempted** – da li je pokretanje aplikacije prošlo „Utisak pri prvom pokretanju“.

- **Data_SentToBackground** - da li je aplikacija poslata u pozadinu tokom pokretanja sistema.

#### <a name="officeapplediskruleresultserializererroronstreamop"></a>Office.Apple.DiskRuleResultSerializerErrorOnStreamOp

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja telemetrijske infrastrukture. Ovaj događaj pokazuje da je došlo do greške.

Prikupljaju se sledeća polja:

- **Data_ActualBytesModified** - broj izmenjenih bajtova.

- **Data_BytesRequested** - broj bajtova za obradu.

- **Data_IsWriteOp** - bez obzira na to da li ćemo izvršiti operaciju pisanja

#### <a name="officeapplemacbootresourceusage"></a>Office.Apple.MacBootResourceUsage

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

#### <a name="officeapplemauvalidation"></a>Office.Apple.MAU.Validation

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja komponente Microsoft automatskog ažuriranja koja se koristi za distribuciju i instaliranje ispravki aplikacija. Prikupljeni podaci koriste se za otkrivanje grešaka i istraživanje uzroka neuspeha.

Prikupljaju se sledeća polja:

- **Data_EventID** - prikupljamo nisku koja predstavlja kod greške

- **Data_Message** - prikupljamo nisku koja sadrži opis greške

#### <a name="officeapplembuinstrumenthangdetectionspincontrol"></a>Office.Apple.MbuInstrument.Hang.Detection.Spin.Control

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se evidentira kad god se čini da neka aplikacija ne reaguje. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CountSpinControlStart** – Oznaka koja ukazuje na to da aplikacija izgleda ne reaguje (ili sporo reaguje)

#### <a name="officeapplembuinstrumentvmondocumentclose"></a>Office.Apple.MbuInstrument.VMOnDocumentClose

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom zatvaranja dokumenta. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="officeapplembuinstrumentvmonshutdown"></a>Office.Apple.MbuInstrument.VMOnShutdown

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom zatvaranja aplikacije. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="officeapplembuinstrumentvmonstart"></a>Office.Apple.MbuInstrument.VMOnStart

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje snimka stanja memorije tokom pokretanja aplikacije. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_CollectionTime** - vremenska oznaka od trenutka kada su podaci prikupljeni

- **Data_ResidentMemory** - uočena vrednost ugrađene memorije

- **Data_VirtualMemory** - uočena vrednost virtuelne memorije

#### <a name="officeapplemsoappdelegatebootperf"></a>Office.Apple.MsoAppDelegate.BootPerf

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za prikupljanje vremena i memorije utrošene tokom pokretanja od strane Office aplikacija, kao i neke detalje o tipu izvršenog pokretanja. Ovaj događaj nam pomaže da nadgledamo performanse i pružimo poboljšanja performansi.

Prikupljaju se sledeća polja:

- **Data_AppLaunchDurationMicroSec** - trajanje procesa pokretanja

- **Data_AppLaunchFinishSystemTime** - vremenska oznaka na određenom označivaču koda za pokretanje

- **Data_AppLaunchStartSystemTime** - vremenska oznaka na određenom označivaču koda za pokretanje

- **Data_ResidentMemory** - snimak raspoložive ugrađene memorije tokom pokretanja

- **Data_VirtualMemory** - snimak raspoložive virtuelne memorije tokom pokretanja

#### <a name="officeappleungracefulappexithangsinprevioussession"></a>Office.Apple.UngracefulAppExitHangsInPreviousSession

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje stanja naših Office aplikacija kao i za istraživanje uzroka neuspeha. Prikupljamo podatak koliko se puta činilo da aplikacija ne reaguje pre nego što je došlo do izlaza iz aplikacije sa poteškoćama.

Prikupljaju se sledeća polja:

- **Data_HangsDetected** - podatak koliko se puta činilo da aplikacija ne reaguje pre nego što je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_LastSessionId** - identifikator za sesiju u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_SessionBuildNumber** - pomoćna verzija aplikacije u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

- **Data_SessionVersion** - glavna verzija aplikacije u kojoj je uočen izlaz iz aplikacije sa poteškoćama.

#### <a name="officeapplewhatsnewerrorandwarning"></a>Office.Apple.WhatsNewErrorAndWarning

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


#### <a name="officeofficemobilepdfviewerpdffileopenmeasurements-on-android"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (na Android)

Događaj se prikuplja za aplikaciju Office za Android. Prikuplja kada se izvršava operacija otvaranja datoteke. Prikupili smo ove podatke da bismo obezbedili dobar učinak za svako otvaranje datoteke u aplikaciji. 

Prikupljaju se sledeća polja:

- **Data_Doc_ActivationFQDN** – Ime domena aplikacije dobavljača za scenario aktiviranja datoteke (beleže se samo informacije o aplikaciji 1. strane).

- **Data_Doc_DownloadDurationms** – Vreme za preuzimanje PDF datoteke na oblaku.

- **Data_Doc_Location** – Lokacija gde se datoteka nalazi (lokalno, ODSP, iCloud, datoteka aplikacije treće strane, wopi

- **Data_Doc_OpenDurationms** – Vreme otvaranja PDF datoteke u milisekundama.

- **Data_FetchReason** – Opisuje način na koji je datoteka pribavljena (ručno, keširano, nije keširano)

- **Doc_RenderDurationms** – Vreme za prikazivanje PDF datoteke

#### <a name="officeofficemobilepdfviewerpdffileopenmeasurements-on-ios"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (na iOS)

Događaj se prikuplja za aplikaciju Office za iOS. Prikuplja kada se izvršava operacija otvaranja datoteke. Prikupili smo ove podatke da bismo obezbedili dobar učinak za svako otvaranje datoteke u aplikaciji. 

Prikupljaju se sledeća polja:

- **Data_Doc_ActivationFQDN** – Ime domena aplikacije dobavljača za scenario aktiviranja datoteke (beleže se samo informacije o aplikaciji 1. strane).

- **Data_Doc_CreateTelemetryReason** – telemetrijski razlog za kreiranje PDF datoteke. (npr: kreiranje iz skeniranja pomoću radnje „slika u PDF“, radnje „dokument u PDF“ itd.)

- **Data_Doc_DownloadDurationms** – Vreme za preuzimanje PDF datoteke u oblaku.

- **Data_Doc_DownloadEndTime** – Vremenska oznaka zaustavljanja preuzimanja datoteke u oblaku.

- **Data_Doc_DownloadStartTime** – Vremenska oznaka početka preuzimanja datoteke u oblaku.

- **Data_Doc_FileOpSessionID** – Jedinstveni ID za sesiju dokumenta.

- **Data_Doc_Location** – Lokacija gde se datoteka nalazi (lokalno, ODSP, iCloud, aplikacija datoteka treće strane, wopi

- **Data_Doc_OpenCompletionTime** – Vremenska oznaka zaustavljanja operacije otvaranja PDF datoteke.

- **Data_Doc_OpenDurationms** – Vreme otvaranja PDF datoteke u milisekundama.

- **Data_Doc_OpenDurationms** – Vremenska oznaka zaustavljanja operacije otvaranja PDF datoteke.

- **Data_Doc_TelemetryReason** – Telemetrijski razlog za otvaranje događaja (npr. otvorite iz MRU ili pregledajte, aktivacija datoteke, aktivacija protokola itd.).

- **Data_FetchReason** – Opisuje način na koji je datoteka pribavljena (ručno, keširano, nije keširano)

- **Doc_RenderDurationms** – Vreme za prikazivanje PDF datoteke


#### <a name="officeonenoteandroidsyncprovisioningcompleted"></a>Office.OneNote.Android.Sync.ProvisioningCompleted

*[Ovaj događaj je prethodno nazvan OneNote.Sync.ProvisioningCompleted.]*

Kritičan signal koji se koristi za obezbeđivanje aplikacije korisnika u OneNote aplikaciji OneNote android, beležnice su propisno obezbeđene tako da se mogu lako pristupiti. Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge

Prikupljaju se sledeća polja: 

- **AppSuspendedDuringEvent** - vraća Boolean da ukaže na to da li je aplikacija obustavljena tokom obezbeđivanja

- **NetworkConnection** - tip mrežnog povezivanja uređaja u upotrebi

- **NetworkDataExchange** - evidentira se broj bajtova koji se razmenjuju tokom dodeljivanja.

- **ServerType** - daje tip servera koji nudi uslugu

- **TimeTakenInMilliSeconds** - vreme vraćanja u vidu potpune obezbeđivanje u milisekundama

#### <a name="officeonenoteandroidsyncprovisioningerror"></a>Office.OneNote.Android.Sync.ProvisioningError

Kritičan signal koji se koristi za obezbeđivanje aplikacije korisnika u OneNote aplikaciji OneNote android, beležnice su propisno obezbeđene tako da se mogu lako pristupiti. Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge.

Prikupljaju se sledeća polja:

- **AppSuspendedDuringEvent**: vraća Boolean da ukaže na to da li je aplikacija obustavljena tokom obezbeđivanja

- **ErrorCode** – Daje šifru greške odgovorne za neuspeh obezbeđivanja 

- **NetworkConnection**: Tip mrežnog povezivanja uređaja u upotrebi

- **NetworkDataExchange** – Evidentira se broj bajtova koji se razmenjuju tokom dodeljivanja.

- **ServerType**: Daje tip servera koji nudi uslugu

- **TimeTakenInMilliSeconds**: Daje vreme vraćanja u vidu potpunog obezbeđivanja u milisekundama


#### <a name="officeonenoteandroidsyncprovisioningstarted"></a>Office.OneNote.Android.Sync.ProvisioningStarted

*[Ovaj događaj je prethodno nazvan OneNote.Sync.ProvisioningStarted]*

Kritičan signal koji se koristi da bi se obezbedilo da nakon što se korisnik potpiše u OneNote android aplikaciji, beležnice budu propisno obezbeđene tako da im se može lako pristupiti.  Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge

Prikupljaju se sledeća polja: 

- **NetworkConnection** - tip mrežnog povezivanja uređaja u upotrebi

- **ServerType** - daje tip servera koji nudi uslugu

#### <a name="officeonenotesystembootdialogssafebootdialogpending"></a>Office.OneNote.System.BootDialogs.SafeBootDialogPending 

Kritičan signal koji se koristi za praćenje kada odlučimo da korisniku prikažemo dijalog „Bezbedno pokretanja aplikacije“ prilikom narednog pokretanja aplikacije jer smo uzastopno više puta padali prilikom pokretanja aplikacije. Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge. Ako korisnici vide dijalog „Bezbedno pokretanja aplikacije“, onda imamo grešku kritičnog pada pokretanja aplikacije i ta informacija će nam pomoći da saznamo koliko korisnika ima taj problem a koliko korisnika ponovo pokreće aplikaciju da bi zapravo videli dijalog „Bezbedno pokretanja aplikacije“ nasuprot onih koji se ne vrate.

Prikupljaju se sledeća polja:

 - Nijedno

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

- **ChildProcessCount** – broj podređenih procesa koje je pokrenula aplikacija. (samo za Windows)

- **ColdBoot** – Da li je ovo prvi put kada se Office aplikacija pokreće nakon ponovnog pokretanja sistema ili se binarni aplikacije morao učitati sa diska. (samo za macOS/iOS)

- **DeviceModel** – Model uređaja. (samo za macOS/iOS)

- **DocLocation** – Pri otvaranju dokumenta naznačeno je koja je usluga obezbedila dokument (OneDrive, File Server, SharePoint itd.).

- **DurationUntilMso20Initialization** – Trajanje koliko je u mikrosekundama trajalo od kada je Office proces započet a mso20win32client.dll učitan.

- **Embedding** – da li je aplikacija otvorena za OLE ugradnju.

- **FirstBoot** – Da li je ovo bilo prvo pokretanje aplikacije.

- **FreeMemoryPercentage** – Koji je procenat memorije uređaja slobodan. (samo za Windows)

- **HandleCount** – Broj operativnih sistema kojima je proces otvoren. (samo za Windows)

- **HardFaultCount** – Broj padova preloma stranice za proces. (samo za Windows)

- **InitializationDuration** - Koliko je mikrosekundi bilo potrebo za prvo pokretanje Office procesa.

- **InterruptionMessageId** - Da li je pokretanje prekinuto dijalogom u kome se traži korisnički unos i ID dijaloga.

- **LegacyDuration** – koliko je dugo trebalo da se aktivnost izvrši, izmereno koristeći različite početne i završne tačke u odnosu na Activity.Duration.

- **OpenAsNew** – da li je aplikacija pokrenuta otvaranjem postojećeg dokumenta kao predloška za novi dokument.

- **OtherOperationCount** – Broj izvedenih I/O operacija, osim operacija čitanja i pisanja. (samo za Windows)

- **OtherTransferCount** – broj bajtova preneti tokom operacija koje se ne prenose, osim operacija čitanja i pisanja. (samo za Windows)

- **PageFaultCount** – Broj padova stranice za proces. (samo za Windows)

- **PrimaryDiskType** – Da li je primarni uređaj za skladištenje solid state uređaj ili rotaciona disk jedinica i njegova rotaciona disk jedinica, ako je primenjivo. (samo za macOS/iOS)

- **PrivateCommitUsageMB** – Trošak izvršenja (tj. količina memorije koju je menadžer memorije izvršio za ovaj proces) u megabajtima za ovaj proces. (samo za Windows)

- **PrivateWorkingSetMB** – Količina memorije u megabajtima u radnom skupu procesa koja se ne deli sa drugim procesima. (samo za Windows)

- **Broj procesora** – Broj procesora u uređaju. (samo za macOS/iOS)

- **ReadOperationCount** – broj izvršenih operacija čitanja. (samo za Windows)

- **ReadTransferCount** – broj pročitanih bajtova.

- **TotalPhysicalMemory** – Ukupna količina fizičke memorije u uređaju. (samo za macOS/iOS)

- **TotalWorkingSetMB** – Količina memorije u megabajtima u radnom skupu procesa.

- **VirtualSetMB** – Količina memorije u megabajtima u virtualnom skupu procesa. (samo za macOS/iOS)

- **WorkingSetPeakMB** – najveća količina memorije u megabajtima koja je do sada bila u radnom skupu procesa.

- **WriteOperationCount** – broj izvršenih operacija pisanja. (samo za Windows)

- **WriteTransferCount** – broj pisanih bajtova. (samo za Windows)


#### <a name="officepowerpointpptandroidrehearseview"></a>Office.PowerPoint.PPT.Android.RehearseView

Ovaj događaj označava da je korisnik prekinuo probnu sesiju. U kombinaciji sa Office.PowerPoint.PPT.Android.RehearseView.StartSession ovo će biti prvi pokazatelj bilo kakvih rušenja ili grešaka sa kojima se suočava korisnik.

Prikupljaju se sledeća polja:

- **Vreme kreiranja veze** – vreme potrošeno na kreiranje veza na strani usluge.

- **CountDownAlertTime** – Vreme za koje je prikazano upozorenje za odbrojavanje.

- **CountdownInitTime–** Vreme između dovršenog učitavanja projekcije slajdova i početka odbrojavanja.

- **CritiqueSummary** – Rezime svih kritika koje su korisnici videli uz svoje brojeve.

- **ExitEventCode** – Kôd za prepoznavanje u kom scenariju korisnik izlazi iz sesije vežbanja, bez obzira na to je li reč o scenariju greške ili uspešnom izlazu. 

- **FRE vreme** – Vreme za koje je FRE ekran počeo da prikazuje dok ga korisnik nije odbacio. 

- **Vreme za dozvolu za mikrofon** – Vreme tokom kojeg je prikazano upozorenje za dozvolu mikrofona dok korisnik ne odabere jednu od opcija.

- **PauseRehearsingCount** – Prebrojavanje koliko je puta korisnik kliknuo na pauziranje probe.

- **RehearsalInitTime** – Vreme koje je potrebno da se proba pokrene.

- **ResumeRehearsingCount** – Prebrojavanje koliko je puta korisnik kliknuo na nastavak probe.

- **ID sesije** – Ovo je ID sesije prednjeg ulaza za govor. Ovo možemo da koristimo za otklanjanje grešaka u evidencijama usluge.

- **SlideshowViewLoadTime** – Vreme potrebno za učitavanje projekcije slajdova.


#### <a name="officepowerpointpptandroidrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.Android.RehearseView.RehearsalSummaryPage 

Događaj je pokrenut kada se učita stranica rezimea. Ovaj događaj nam pomaže da ubeležimo učinak stranice rezimea. Govori koliko vremena treba da se kod klijenta učita stranica usluge probnog rezimea. Potrebno je da se zadrži funkcija performanta. 

Prikupljaju se sledeća polja:

- **PayloadCreationTime** – vreme koje je potrebno u milisekundama za stvaranje opterećenja. 

- **PostUrlCallTime** – vreme koje je potrebno u milisekundama za slanje naknadnog URL poziva. 

- **RehearseSessionid** – Ovo je ID sesije prednjeg ulaza za govor. Ovo možemo da koristimo za otklanjanje grešaka u evidencijama usluge.

- **RequestPayloadSize** – to je veličina zahtevanog opterećenja. 

- **ResourcesLoadTime** – to je vreme u milisekundama koje je potrebno za učitavanje resursa (js, css). 

- **SummaryPageErrorReceived** – ovo je Bulova vrednost koja pokazuje da li je primljena stranica rezimea ili je došlo do greške.

- **SummaryPageHtmlLoadTime** – to je vreme u milisekundama koje je potrebno za učitavanje summarypageHtml. 

- **SummaryPageLoadStartTime** – to je vreme u milisekundama za primanje prvog odgovora sa servera. 

- **SummaryPageLoadTime** – vreme (u ms) potrebno za učitavanje stranice rezimea. Ovo obuhvata vreme kreiranja korisnog tereta 

- **ThumbnailsCount** – to je ukupan broj minijatura koje će biti deo stranice rezimea. 

#### <a name="officepowerpointpptandroidrehearseviewstartsession"></a>Office.PowerPoint.PPT.Android.RehearseView.StartSession

Događaj je pokrenut kada korisnik klikne na „Pokreni sesiju“. Ovaj događaj nam pomaže da ubeležimo koliko korisnika koristi funkciju trenera izlagača na sistemu Android. Kada se kombinuje sa Office.PowerPoint.PPT.Android.RehearseView reći će nam koliko korisnika je uspešno obavilo probnu sesiju a koliko nije moglo. Ovo je prvi pokazatelj padova ili grešaka u funkciji.
 
Prikupljaju se sledeća polja:

 - Nijedno


#### <a name="officepowerpointpptsharedrehearseviewerrors"></a>Office.PowerPoint.PPT.Shared.RehearseView.Errors

*[Ovaj događaj je prethodno nazvan Office.PowerPoint.PPT.Android.RehearseView.Errors]*

Događaj pokrenut kada dođe do bilo kakve greške. Ovaj događaj će nam pomoći da saznamo sa kojim greškama se suočio korisnik i pomoći će da „Trener za izlagače“ radi na mobilnim uređajima.

Prikupljaju se sledeća polja:

- **ID sesije** – ID probne sesije

- **RehearsalEventCode** – šifra probne greške


#### <a name="officepowerpointrehearsalsessionmetrics"></a>Office.PowerPoint.Rehearsal.SessionMetrics 

Događaj se aktivira kada se sesija govora zaustavi za trenera za izlagače. Ovaj događaj nam pomaže da uhvatimo neku metriku za probnu sesiju u treneru za izlagače. On će vam pomoći da održite visok kvalitet usluge za ovu funkciju.

Prikupljaju se sledeća polja:

- **ActualRehearseBootTimeInMs** – to je stvarno utrošeno vreme za stvaranje veza.

- **AdaptationTextSize** – to je veličina teksta koji se šalje u uslugu.

- **AuthDurationInMs** – Ovo je vreme u milisekundama potrebno za potvrdu identiteta (osvežite token za potvrdu identiteta).

- **AuthError** – Ovo opisuje grešku pri potvrdi identiteta do koje je došlo (ako je uopšte došlo do nje).

- **AvgFragmentLatencyInMs** – Ovo je prosečno vreme povratnog puta za govorne poruke na mreži.

- **ConnectDurationInMs** – Ovo je vreme u milisekundama potrebno da sesija dovrši vezu. 

- **FirstAudioDelayInMs** – Ovo je vreme u milisekundama potrebno da se prime prvi zvučni podaci.

- **FRetriedOnOpenConnection** – to je Bulova vrednost koja pokazuje je li došlo do ponovnog pokušaja za openconnection ili nije.

- **InitMediaCaptureLayerDurationInMs** – Ovo je vreme u milisekundama potrebno da se pokrene sloj hvatanja medija/zvuka.

- **LocallyDroppedMessageCount** – Ovo je ukupan broj lokalno otpuštenih poruka.

- **NumReconnectAttemptsDuringSession** – to pokazuje koliko je puta pokušano ponovno povezivanje na speechservice.

- **NumTriesDuringEachReconnectAttempt** – to je polje koje pokazuje broj izvršenih pokušaja tokom svakog pokušaja ponovnog povezivanja.

- **OpenFrontDoorConnectionDurationInMs** – Ovo je vreme u milisekundama potrebno za otvaranje veze ka usluzi prednjeg ulaza.

- **SendAdaptationTextDurationInMs** – Ovo je vreme u milisekundama potrebno za slanje teksta adaptacije u uslugu.

- **ServiceDroppedMessageCount** – Ovo je ukupan broj poruka koje je otpustila usluga.

- **SessionDurationInMs** – to je vreme trajanja cele sesije od kada je korisnik kliknuo za početak do kada je kliknuo za kraj.

- **SessionId** – Ovo je ID sesije prednjeg ulaza za govor. Ovo možemo da koristimo za otklanjanje grešaka u evidencijama usluge.

- **SpeechClientResultEventsWithTimestamps** – Ovo je niz kodova greške primljenih zajedno sa vremenskim oznakama koje mogu pomoći pri otklanjanju grešaka.

- **SpeechHResultsWithTimestamps** – Ovo je niz kodova greške primljenih zajedno sa vremenskim oznakama koje mogu pomoći pri otklanjanju grešaka.

- **StartSpeechCaptureDurationInMs** – Ovo je vreme u milisekundama potrebno za pokretanje hvatanja govora.

- **StartSpeechServiceDurationInMs** – to je polje vremena koliko je potrebno da sesija govora započne svaki put kada dođe do ponovnog povezivanja, uključujući trajanje prve pokrenute sesije govora. 

- **TotalMessageCount** – Ovo je ukupan broj audio poruka poslatih u uslugu.

- **WebSocketConnectDurationInMs** – Ovo je vreme u milisekundama potrebno za dovršenje veze sa veb priključkom.


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

Kritičko praćenje signala interakcije korisnika sa dijalogom Join Office. Koristi se za prepoznavanje bilo kakvih problema u izvršavanju promena koje je inicirao korisnik, kao što su pridruživanje ili napuštanje Office Insider programa i promena nivoa programa Office Insider.

Prikupljaju se sledeća polja:

- **Data_AcceptedContactMeNew** – Označava da li je korisnik prihvatio da bude kontaktiran od strane Microsoft prilikom pridruživanja programu Office Insider

- **Data_InsiderLevel** –Insider Level za otvaranje dijaloga "pridruži se sistemu Office Insider"

- **Data_InsiderLevel** –Insider level za zatvaranje dijaloga "pridruži se sistemu Office Insider"

- **Data_IsInternalUser** – Ukazuje na to da li je aplikacija pokrenuta pod akreditivima Microsoft korporativnog naloga.

- **Data_IsInternalUserInit** - Označava da li je kod mogao da utvrdi da li je aplikacija pokrenuta pod akreditivima Microsoft korporativnog naloga.

- **Data_OpenNewsletterWebpage** – Ukazuje na to da li je veza pretplate na Office Insider bilten aktivirana pod uslovom da se korisnik pridružio programu Office Insider, funkcija pretplate na bilten je omogućena i da korisnik nije otkazao Otvaranje stranice pretplate na Office Insider bilten.
    
- **Data_RegisterInsider** - Status Office Insider registracije

- **Data_RegisterInsider** – Kod rezultata za registraciju Office Insider-a

- **Data_RegistrationStateCurrent** – Trenutno stanje registracije

- **Data_RegistrationStateDesired** – Traženo stanje registracije


#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Ovaj događaj beleži vreme prikazivanja datoteke. Pomaže nam da održimo performanse prikazivanja datoteke pod kontrolom.

Prikupljaju se sledeća polja:

  - **Data\_AvgTime: integer** - Prosečno vreme koje je potrebno za prikazivanje Visio crteža u sesiji

  - **Data\_CompositeSurfEnabled: bool** - tačno ako je omogućen režim složenog prikazivanja

  - **Data\_Count: integer** – koliko puta Visio prikazuje crtež u sesiji

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

  - **Data\_IsInternalFile: bool -** tačno ako je datoteka unutrašnja. na primer, šablon

  - **Data\_IsIRM: bool -** tačno ako je datoteka zaštićena pravima o informacijama

  - **Data\_IsReadOnly: bool -** tačno ako je datoteka samo za čitanje

  - **Data\_IsSuccess: bool -** tačno ako je otvaranje datoteke uspešno

  - **Data\_Location: string -** lokacija datoteke kao što je lokalna, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer

  - **Data\_NetworkIOBytesRead: int -** ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesReadSquared: int -** kvadratna vrednost podataka\_NetworkIOBytesRead

  - **Data\_NetworkIOBytesWritten: int -** Ukupno mrežnih bajtova koji su pročitani prilikom čuvanja

  - **Data\_NetworkIOBytesWrittenSquared: int -** kvadratna vrednost podataka NetworkIOBytesWritten

  - **Data\_OpenLocation: integer –** Lokacija datoteke sa koje je otvorena 0, lokalno, 1, mreža, 2, usluga SharePoint, 3 – internet

  - **Data\_Size\_Docs: integer -** Veličina dokumenta u bajtovima

  - **Data\_Tag: string -** jedinstveni identifikator za događaje funkcije „Sačuvaj kao“

  - **Data\_WasSuccessful: bool -** tačno ako je otvaranje bilo uspešno


#### <a name="onenoteappsafebootdialogactiontaken-officeonenoteandroidsafebootdialogactiontaken-officeandroidearlytelemetrysafebootdialogactiontaken"></a>OneNote.App.SafeBootDialogActionTaken, Office.OneNote.Android.SafeBootDialogActionTaken, Office.Android.EarlyTelemetry.SafeBootDialogActionTaken

Kritični signal koji se koristi za praćenje odgovora korisnika kada se prikaže dijalog sigurnog pokretanja. Dijalog „Bezbedno pokretanje aplikacije“ se prikazuje kada nismo bili u mogućnosti da pokrećemo više puta. Koristi se da obezbedi otkrivanje kritičnih regresija OneNote aplikacije i ispravnost usluge. Korisnik vidi kada naiđe na kritičnu grešku kritičnog pada prilikom pokretanja aplikacije. Ove informacije će pomoći da se prati da li je rešen uzrok pada i da li korisnik može da uspešno pokrene aplikaciju.

Prikupljaju se sledeća polja: 

- **DIALOG_ACTION** – Na koje je dugme dijaloga korisnik kliknuo – Pozitivno ili negativno dugme


#### <a name="perfevent"></a>perf.event

Koristi se za monitoring mogućeg negativnog uticaja na performanse učitavanja različitih delova aplikacije, na primer, da se uverite kada prvi put otvorite aplikaciju, da će se prijemno poštansko sanduče brzo učitati.

Prikupljaju se sledeća polja: 

- **app_start_show_message_list** - to znači da je došlo do problema sa pokretanjem aplikacije koji uzrokuje da se na lista poruka iz prijemnog poštanskog sandučeta učitava duže vreme

- **average** – prikuplja količinu ponovnih učitavanja koja se dešavaju u konverzaciji podeljenu količinom poruka u toj konverzaciji.  

- **event_type** – objašnjava tip događaja performansi koji je izazvao problem sa performansama kako bi nam pomogao da otkrijemo probleme u vezi sa određenim tipom.   

- **extra_params** – programer ovde može da doda dodatne parametre da bi nam omogućio više detalja o tome šta može da izazove ove probleme sa učinkom, tj. kada je ova radnja počela i završena itd. 

-   **has_work_profile** – označava da li aplikacija radi u okviru programa Android Work profile ili sličnu konfiguraciju kako bi se ispravljene analize performansi imale u tim okruženjima.

- **profiling_summary** – pruža informacije o grupi zadataka, broju zadataka i prosečnom vremenu da te grupe pomognu u shvatanju mogućih regresija u određenim oblastima prilikom učitavanja aplikacije

- **runtime_performance_monitoring_data** – pruža podatke o performansama (vreme učitavanja, broj zapisa) prilikom učitavanja podataka u različitim delovima aplikacije.
  - **average_cost_time_ns** – Prosečno vreme troškova izmereno u nanosekundama.
  - **cost_type** – pokazuje nam da li se ovaj događaj odnosi na merenje ili trajanje skladištenja slojeva skladišta ili ukupne trajanja.
  - **hx_object_type** – pruža detaljni tip objekta merenja.
  - **is_main_thread** – pokazuje nam da li ovaj događaj zavisi samo od vremena izvršenja glavne niti.
  - **record_count** – broj zapisa koji vraća osnovni sloj skladišta.
  - **scopre** – navodi ime stranice / komponenata korisničkog interfejsa kojem ovaj događaj pripada.
  - **total_cost_time_ns** – ukupno vreme izvršavanja izmereno u nanosekundama. 

- **total_time_elapsed** - govori nam koliko dugo se odigrao događaj koji nam je pomogao da shvatimo ozbiljnost problema sa izvođenjem

#### <a name="performancerecord"></a>performance.record

Ovaj događaj prikuplja podatke o učinku aplikacije. Omogućuje nam otkrivanje i rešavanje situacija kada iskorišćenost memorije aplikacije i CPU postanu kritično visoki ili postoje neki drugi problemi s performansama, što može dovesti do usporavanja vašeg uređaja.

Prikupljaju se sledeća polja: 

- **app_exit_metric** – javlja nam metriku o broju različitih vrsti performansi za prednji i pozadinski izlaz iz aplikacije, kao pomoć u razumevanju neočekivanog izlaska iz aplikacije s razlozima negativnih performansi.

- **average_suspended_memory** – javlja nam prosečnu količinu memorije koju aplikacija upotrebljava kada je obustavljena kako bismo imali vrednost za poređenje i kako bismo razumeli negativan učinak na funkciju.

- **category** - govori nam da li da li je aplikacija u prednjem planu ili u pozadini u tom trenutku. Moguće vrednosti obuhvataju prednji plan i pozadinu.

- **cpu_usage** – govori nam koliko je aplikacija koristila CPU tako da imamo nešto da uporedimo, da bismo razumeli negativan uticaj na performanse

- **cumulative_CPU_time** – govori nam koliko ukupno CPU-a aplikacija koristi s merenjem trajanja kako bismo imali vrednost za poređenje i kako bismo razumeli negativan učinak na funkciju.

- **cumulative_GPU_time** – govori nam koliko ukupno GPU vremena aplikacija koristi kako bismo imali vrednost za poređenje i kako bismo razumeli negativan uticaj veka trajanja baterije.

- **is_watch_app_installed** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je instaliran da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **is_watch_paired** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je uparen sa uređajem da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **is_watch_supported_and_active** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je aktivan da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **memoAry_used_percentage** – govori nam koji procenat memorije koristi aplikacija tako da imamo šta da uporedimo, da bi nam pomogao da shvatimo uticaj negativnih performansi

- **memory_used** – objašnjava koliko aplikacije koristi memorija, pa imamo šta da uporedimo, da bismo razumeli negativan uticaj na performanse

- **peak_memory_usage** – govori nam koliko je najviše memorije aplikacija koristila kako bismo imali vrednost za poređenje i kako bismo razumeli negativan učinak na funkciju.

- **scroll_hitch_time_ratio** – govori nam koji je odnos vremena proveden u zastoju tokom kretanja kroz korisnički interfejs kako bismo razumeli negativan utjecaj na učinak korisničkog interfejsa.


### <a name="application-activity-error-subtype"></a>*Podtip greške u aktivnosti aplikacije*

Greške u funkcionalnosti funkcije ili korisničkog iskustva.

#### <a name="assertion"></a>tvrdnja

Ovaj događaj nam omogućava da otkrijemo kada su se dogodile kritične greške u aplikaciji koje bi mogle prouzrokovati pad aplikacije ili ozbiljne probleme, kao što je prouzrokovanje da vidite prazne redove u pristigloj pošti.

Prikupljaju se sledeća polja:

- **count** - ukupni broj stavki povezanih sa greškom; na primer, broj kalendara koji imaju greške

- **has_hx** - govori nam da nalog koristi našu novu uslugu sinhronizacije kako bi nam pomogao da otkrijemo probleme izazvane uslugom sinhronizacije

- **host_name** - ime hosta usluge koji je učestvovao u grešci da bi nam pomogao da otkrijemo probleme povezane sa određenim hostom

- **host_type** - tip domaćina koji je umešan u grešku kako bi nam pomogao da otkrijemo probleme u vezi sa određenim tipom domaćina

- **message** - prilagođena poruka za tvrdnju koja se koristi za dijagnozu problema 

- **origin** - poreklo greške u kodu da nam pomogne da otkrijemo probleme povezane sa određenim delom koda

- **stacktrace** - praćenje steka gde je tvrdnja nastupila da bi nam pomogla u otkrivanju problema u vezi sa određenim dela kôda

- **type** – tip greške potvrde koja se dogodila, npr. null_folder_name, compose_selected_null_account, da bi nam pomogao da otkrijemo probleme u vezi sa određenim delom kôda

#### <a name="editcontacterror"></a>edit.contact.error

Dozvoljava nam da otkrijemo i rešimo situacije u kojima je došlo do grešaka kada pokušavate da prikažete ili uredite kontakte kroz našu aplikaciju.

Prikupljaju se sledeća polja: 

- **errorType** - tip greške koji nam se dogodio da bi pomogao u dijagnozi problema

- **field** - polje za kontakt koje je korisnik pokušavao da uredi kako bi nam pomogao da ustanovimo problem

- **version** - verzija usluge kontaktnih vizitkarti koju koristimo da bismo joj pomogli da dijagnostikujemo problem

#### <a name="errorreport"></a>error.report

Ovaj događaj omogućava nam da otkrijemo kada su se pojavile kritične greške u aplikaciji, tako da možemo sprečiti probleme koji mogu prouzrokovati pad aplikacije ili sprečiti čitanje e-pošte. 

Prikupljaju se sledeća polja: 

- **client–request–id** – identifikator zahteva klijenta za zahtev koji je izazvao grešku
 
- **date** – pečat datuma koji je izazvao grešku

- **error** – tip greške, npr. get_mailbox_location_failed
 
- **error_body** - telo poruke o grešci
 
- **is_x_mailbox_anchor_set** - da li je vrednost podataka X-AnchorMailbox podešena na zahtev
 
- **reason** – razlog greške, tj. poruka o grešci
 
- **request–id** – identifikator zahteva servera za zahtev koji je izazvao grešku
 
- **source** - izvor greške unutar OM infrastrukture, obično jedan od sledećih „BE“ ili „FE“


#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Pomaže korporaciji Microsoft da razdvoji duge prekide u upravljačkom programu grafičke kartice od kratkih prekida, što zauzvrat pomaže da se odredi koji upravljački program grafičke kartice može imati probleme. Upravljački program grafičke kartice korisnika je izazvao prekid u sistemu Office, ali uticaj tog prekida još uvek nije poznat.

Prikupljaju se sledeća polja:

  - **Data\_InDeviceCall** - Pozvani metod na grafičkoj kartici koji je proizveo prekid

  - **Data\_Timeout** - Koliko dugo je trajao prekid

  #### <a name="officeandroidadalsigninuiprompts"></a>Office.Android.ADALSignInUIPrompts

Ovaj događaj označava da je korisniku prikazan zahtev za prijavljivanje za lični ili poslovni nalog  Ovaj događaj nam pomaže da razumemo ispravnost stanja prijavljivanja aplikacija i preduzmemo odgovarajuće radnje kada primetimo neočekivane ponovne zahteve za prijavljivanje 

Prikupljaju se sledeća polja:

- **LastLoginDelta** - Vreme proteklo od poslednjeg uspešnog prijavljivanja.

- **PreviousIdentityCredProviderState** - Označava stanje naloga

- **PreviousIdentityState** - Označava stanje naloga, npr. istekla sesija 

- **SignInResultCode** - Označava kod rezultata kraja zahteva za prijavljivanje.

- **UseCache** - Označava da li smo naterali korisnika da ponovo unese lozinku.

- **UserType** - Označava da li je nalog postojeći ili nov

#### <a name="officeandroidandroidappdocsfileoperationends"></a>Office.Android.AndroidAppDocsFileOperationEnds

Podaci telemetrije kritičnih dokumenata samo za Android (AppDocs) za završavanje operacija File New/Open/SaveAs. Ovo beleži kodove grešaka za neuspešne AppDocs operacije  Microsoft to koristi za identifikovanje grešaka u različitim operacijama datoteka i tačnog sloja na kojem je došlo do kvara u programu Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **AccessMode** - nabrajanje za pristupni režim za datoteku. Vrednosti – nijedna, samo za čitanje, samo za čitanje sa nadogradnjom, čitanje i pisanje

- **BlockingUIShown** - Logička vrednost koja označava da li je bilo gde u toku prikazan blokirajući korisnički interfejs.

- **ContentUriAuthority** - autoritet URL adrese sadržaja iz sistema SAF

- **Correlation** - GUID za ID korelacije koji se odnosi na operaciju

- **DocId** - ID dokumenta koji generišu AppDocs

- **DocInstanceId** - ID instance dokumenta koji generišu AppDocs koji je obuhvaćen instancom operacije na dokumentu

- **DocIsEnterpriseProtected** - Logička vrednost koja označava da li je dokument zaštićen.

- **DocUserId** - ID korisnika koji potiče iz MS sloja za proveru identiteta

- **DocUserIdProvider** - nabrajanje koje predstavlja dobavljača ID-ja korisnika, 0 = Nepoznat, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL

- **DurationInMs** - vreme izraženo u milisekundama koje je potrebno za završetak operacije nad datotekom

- **EndReason** - nabrajanje za razlog završetka  Vrednosti – nijedno, uspeh, neuspeh, otkazivanje

- **ErrorCode** - kôd greške za operaciju nad datotekom

- **Extension** - Oznaka tipa datoteke koja je otvorena.

- **FileSourceLocation** - nabrajanje za lokaciju datoteke. Moguće vrednosti: nijedno, lokalno, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, nepoznati server

- **FILETIME** - Vreme događaja

- **FirstBCSClientError_Info** informacije o kôdu greške koja se tiče konverzije datoteka

- **HttpStatusCode** - HTTP kôd za odziv za zahtev za veb uslugu

- **InitalizationReason** - Ulazna tačka za otvaranje datoteke

- **K2FileIOHresult**- Hresult kod za okončanje operacije otvaranja datoteke

- **LastBCSClientError_TagId** - poslednja greška u programu BCS (usluga binarne konverzije) klijenta

- **OfficeWebServiceApiStatusFlag** - zastavica statusa za zahtev za Veb uslugom

- **OpEndEventId** - oznaka koja predstavlja mesto na kojem je operacija zapravo završena

- **OpFlags** - Oznake parametara operacije nad dokumentom koje koristi AppDocs sloj

- **OpSeqNum** – Broj koji predstavlja redosled poziva vezanih za operacije nad datotekama u AppDocs sloju

- **OpType** - nabrajanje tipa operacije. Vrednosti: "Ništa", "Kreiraj Document", "Otvori Document", "Kopiraj dokument", "Zatvori Document", "Sačuvaj dokument", "Otvori Verziju", "Zatvori verziju"

- **PreFetchState** - nabrajanje za učitavanje predložaka u pozadini za operacije kreiranja nove datoteke.

- **ProviderApp** - ime paketa aplikacije iz koje je datoteka otvorena

- **ScopeInstanceId** - ID instance opsega koji se koristi za povezivanje konteksta podataka sa aktivnostima

- **Size** - veličina datoteke

- **State** - nabrajanje za stanje datoteke. Vrednosti: ništa, kreiranje, kreirano, kreiranje nije uspelo, otvaranje, otvoreno, otvaranje nije uspelo, kopiranje, iskopirano, kopiranje nije uspelo, zatvaranje, zatvoreno, zatvaranje nije uspelo

- **TemplateName** – ime binarnog predloška dokumenta iz usluge predložaka, npr. TF10002009. dotx

- **UriScheme** – šema URL adrese

#### <a name="officeandroidandroidautherror"></a>Office.Android.AndroidAuthError

Ovaj događaj označava osnovne greške pri potvrdi identiteta tokom nečujnog osvežavanja tokena, učitavanje stranice za prijavljivanje na uslugu itd.  Ovaj događaj nam pomaže da razumemo ispravnost stanja prijavljivanja naših aplikacija, napravljenih pokušaja prijavljivanja kao i preduzmemo odgovarajuće mere kada primetimo neočekivane greške. 

Prikupljaju se sledeća polja:

- **ADALErrorCode** – označava kôd greške tokom prikazivanja zahteva za prijavljivanje ili pokušaja nečujnog preuzimanja tokena za poslovni nalog.

- **ADALRawErrorCode** – Označava sirovi kôd greške tokom prikazivanja zahteva za prijavljivanje ili pokušaja nečujnog preuzimanja tokena za poslovni nalog.

- **ErrorGroup** - Označava tip naloga kao što je lični, poslovni ili lokalni nalog.

- **IDCRLErrorCode** – Označava kôd greške dok prikazuje zahtev za prijavljivanje za lični nalog.

- **IDCRLRawErrorCode** – Označava sirovi kôd greške dok prikazuje zahtev za prijavljivanje za lični nalog.

- **LiveOAuthErrorCode** – Označava kôd greške tokom pokušaja nečujnog osvežavanja tokena za lični nalog.

- **LiveOAuthRawErrorCode** – Označava sirovi kôd greške tokom pokušaja nečujnog osvežavanja tokena za lični nalog.

- **NTLMErrorCode** – Označava kôd greške dok prikazuje zahtev za prijavljivanje za lokalni poslovni nalog.

#### <a name="officeandroidandroidfileasyncsavestatus"></a>Office.Android.AndroidFileAsyncSaveStatus

Beleži asinhrono stanje čuvanja datoteke i razne kodove grešaka koji potiču od drugih komponenti.  Kompanija Microsoft ove podatke koristi da analizira da li dolazi do gubitka korisničkih podatka u aplikaciji prilikom čuvanja datoteka u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **FileExtension** - oznake tipa datoteke

- **FileIOSaveHResult** - Hrezultat za operaciju čuvanja datoteke

- **FileIOSaveIsCopy** - Logička vrednost koja označava da li operacija čuva kopiju.

- **FileSize** - veličina datoteke

- **FileSourceLocation** - nabrajanje za izvornu lokaciju datoteke. Vrednosti: ništa, lokalno, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, nepoznati server

#### <a name="officeandroidandroidfileopenreliability"></a>Office.Android.AndroidFileOpenReliability

Ovo snima podatke o statusu otvorene datoteke i razne kodove grešaka da bi se identifikovalo koje se greške u otvaranju datoteka očekuju u odnosu na neočekivane i koji deo koda ih prijavljuje.  Microsoft koristi ove podatke za analizu razloga grešaka pri otvaranju datoteka i izračunavanje kritične metrike kao što je stopa uspešnosti otvaranja datoteka u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **AccessMode** - Nabrajanje režima pristupa

- **AppDocsFileOpenErrorCode** - AppDocs kod greške za neuspešno otvaranje datoteke

- **ContentUriAuthority** - autoritet URL adrese sadržaja iz sistema SAF

- **DownloadCsiError** - poruka o grešci preuzimanja od CSI

- **FileExtension** - oznake tipa datoteke

- **FileOpenEndErrorCode** - kod greške za neuspešno otvaranje datoteke

- **FileOpenStatus** - Nabrajanje stanja otvaranja datoteke

- **FileSize** - veličina datoteke

- **FileSourceLocation** - Nabrajanje za lokaciju datoteke.

- **LastBCSClientError_TagId** - poslednja greška u programu BCS (usluga binarne konverzije) klijenta

- **IfWordFileOpencanceled** - da li je korisnik otkazao otvaranje datoteke u aplikaciji Word

- **InitializationReason** - nabrajanje za ulaznu tačku za otvaranje datoteke

- **IsAutoSaveDisabled** - da li je tokom otvaranja datoteke onemogućeno automatsko čuvanje

- **IsFileEmpty** - Logička vrednost koja označava da li je datoteka prazna

- **K2FileIOHresult**- Hrezultat za okončanje operacije nad datotekom

- **OpenCsiError** - poruka o grešci pri otvaranju datoteke iz CSI sloja

- **OpEndEventId** - oznaka koja predstavlja mesto na kojem je operacija zapravo završena

- **PPTHresult** - Hrezultat u PPT

- **PPTIsExpectedError** - Klasifikacija PPT greške za očekivano/neočekivano neuspelo otvaranje datoteke 

- **PPTTag**-oznaka greške u usluzi PPT

- **ProviderApp** - ime paketa aplikacije iz koje je datoteka otvorena

- **ProviderFileSize** - veličina datoteke zabeležena pri otvaranju putem aktivacije datoteke

- **State** - Nabrajanje stanja otvaranja datoteke

- **UriScheme** – Šema URL adrese

- **WordErrortag** - Oznaka greške u programu Word

- **WordFileCorruptionReason** - razlog za korupciju zbog kojeg može da se desi da otvaranje Word datoteke ne uspe

- **WordFileOpenErrorCode** – Kod greške pri otvaranju datoteke koji je specifičan za Word.

- **WordFileTypeFromDod** - tip datoteke utvrđuje Word na osnovu stvarnog formata datoteke

- **WordFileTypeFromExtension** - tip datoteke utvrđuje Word na osnovu oznake tipa datoteke

#### <a name="officeandroidandroidfilesavestatus"></a>Office.Android.AndroidFileSaveStatus

Od presudne važnosti za beleženje podataka o stanju čuvanja datoteke i raznim kodovima grešaka koji potiču od drugih komponenti.  Kompanija Microsoft ove podatke koristi da analizira da li dolazi do gubitka korisničkih podatka u aplikaciji prilikom čuvanja datoteka u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **AccessMode** - Vrednosti** – ništa, samo za čitanje, samo za čitanje sa nadogradnjom, čitanje i pisanje.

- **AppDocsEndReason** - nabrajanje za File save Appdoc EndReason  Vrednosti: ništa, uspeh, neuspeh, otkazivanje

- **AppDocsErrorCode** - Konačan kod greške za neuspešno obavljeno čuvanje datoteke

- **AppDocsTriggeringSaveDetails** - polje koje označava da li AppDocs pokreće čuvanje

- **DocInstanceId** - ID instance dokumenta koji generišu AppDocs koji je obuhvaćen instancom operacije na dokumentu

- **ExcelFileSaveResult** – HRezultat specifičan za Excel

- **FileExtension** - Oznaka tipa datoteke.

- **FileIOSaveErrorCode** - Kôd greške u FileIO

- **FileIOSaveHResult** - Hrezultat u FileIO

- **FileIOSaveIsCopy** - Logička vrednost koja označava da li se radi o operaciji kopiranja.

- **FileSize** - Veličina datoteke

- **FileSourceLocation** - Nabrajanje za lokaciju datoteke.  Vrednosti: ništa, lokalno, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, nepoznati server

- **OpFlags** - Oznake za operaciju čuvanja

- **PPTFileSaveFailHresult** - PPT hrezultat za greške pri čuvanju

- **PPTFileSaveFailTag** - PPT oznaka za greške pri čuvanju

- **State** - Nabrajanje stanja otvaranja datoteke 

- **Values** - ništa, kreiranje, kreirano, kreiranje nije uspelo, otvaranje, otvoreno, otvaranje nije uspelo, kopiranje, iskopirano, kopiranje nije uspelo, zatvaranje, zatvoreno, zatvaranje nije uspelo

- **WordFileCopyErrorTrackbackTag** - oznaka za praćenje greške u fazi kopiranja dokumenta u aplikaciji Word

- **WordFileSaveCancelReason** - oznaka za praćenje otkazivanja u aplikaciji Word

- **WordFileSaveEid** – kôd greške specifičan za Word

- **WordFileSaveErrorTrackbackTag** - oznaka za praćenje grešaka pri čuvanju

- **WordFileSaveOpResult** - nabrajanje za status rezultata 0 ako je uspešan, 1 ako je bio neuspešan, 2 ako je otkazan

- **WordFileSaveSuccess** – nabrajanje detalja specifičnih za Word za uspeh operacije spremanja datoteka.

#### <a name="officeandroidandroidofficeactivationlatency"></a>Office.Android.AndroidOfficeActivationLatency

Podaci od ključne važnosti za prikupljanje ukupnog vremena za sva otvaranja datoteka u Windows operativnom sistemu i aplikacijama Excel i PowerPoint  Ove podatke Microsoft koristi za utvrđivanje performansi svih naših aplikacija pri otvaranju datoteke

Prikupljaju se sledeća polja:

- **AppBootingOccured** - Logička vrednost kojom se proverava da li je dovršeno pokretanje aplikacije

- **ApplicationBootTime** - vreme potrebno u toku određene faze pokretanja aplikacije

- **AppSuspendedDuringBoot** - Logička vrednost kojom se proverava da li je aplikacija obustavljena tokom pokretanja

- **BlockingUIShownDuringFileOpen** - Logička vrednost koja označava da li se pojavio blokirajući dijalog tokom operacije otvaranja datoteke

- **CachedInfoAvailable** - Logička vrednost kojom se traže keširani podaci specifični za operaciju otvaranja datoteke

- **DocumentRecoveryInvoked** - Logička vrednost koja označava da li je postojao dokument koji je bio na čekanju za oporavak

- **EndToEndActivationTime** - vreme potrebno za prikazivanje datoteke otvorene van aplikacije

- **EndToEndFileOpenTime** - vreme potrebno za prikazivanje datoteke otvorene unutar aplikacije

- **FileOpenPhaseDurationInMs** - vreme utrošeno na određenu fazu otvaranja datoteke

- **FileSourceLocation** - nabrajanje za lokaciju datoteke kao npr. nijedna, lokalna, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, nepoznati server

- **InitalizationReason** - Ulazna tačka za otvaranje datoteke

- **InitialBootPhaseTime** - vreme potrebno u toku određene faze pokretanja aplikacije

- **IsThisFirstLaunch** - Logička vrednost koja ukazuje na to da li je ovo prvo pokretanje aplikacije

- **MinimumLibraryLoadPhaseTime** - vreme potrebno tokom određene faze pokretanja aplikacije

- **MinimumLibraryLoadPhaseTime** - vreme potrebno tokom određene faze pokretanja aplikacije

- **MinimumLibraryLoadPhaseTime** - vreme potrebno tokom određene faze pokretanja aplikacije

- **PostAppInitTimeInMs** - vreme potrebno u toku određene faze pokretanja aplikacije

- **PPTRenderPhase** - vreme povezano sa određenom fazom prikazivanja PPT

- **PreAppInitTimeInMs** - vreme potrebno u toku određene faze pokretanja aplikacije

- **ProviderApp** - ime paketa aplikacije iz koje je datoteka otvorena

- **TelemetryReason** – sličan razlogu za pokretanje, ali detaljnije nabrajanje u vezi ulazne tačke otvaranja datoteke

- **UserDialogInterruptionDuringBoot** - Logička vrednost koja ukazuje na to da li je došlo do blokiranja korisničkog interfejsa tokom pokretanja

- **XLRenderPhase** - vreme povezano sa određenom fazom u prikazivanju u programu Excel

#### <a name="officeandroidappdocsfileoperationends"></a>Office.Android.AppDocsFileOperationEnds

Podaci telemetrije kritičnih dokumenata samo za Android (AppDocs) za završavanje operacija File New/Open/SaveAs. Ovo beleži kodove grešaka za neuspešne AppDocs operacije  Microsoft to koristi za identifikovanje grešaka u različitim operacijama datoteka i tačnog sloja na kojem je došlo do kvara u programu Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **AccessMode** - nabrajanje za pristupni režim za datoteku.  Vrednosti: nijedna, samo za čitanje, samo za čitanje sa nadogradnjom, čitanje i pisanje

- **BlockingUIShown** - Logička vrednost koja označava da li je bilo gde u toku prikazan blokirajući korisnički interfejs.

- **ContentUriAuthority** - autoritet URL adrese sadržaja iz sistema SAF

- **Correlation** - GUID za ID korelacije koji se odnosi na operaciju

- **DocId** - ID dokumenta koji generišu AppDocs

- **DocInstanceId** - ID instance dokumenta koji generišu AppDocs koji je obuhvaćen instancom operacije na dokumentu

- **DocIsEnterpriseProtected** - Logička vrednost koja označava da li je dokument zaštićen.

- **DocUserId** - ID korisnika koji potiče iz MS sloja za proveru identiteta

- **DocUserIdProvider** - nabrajanje koje predstavlja dobavljača ID-ja korisnika, 0 = Nepoznat, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL

- **DurationInMs** - vreme izraženo u milisekundama koje je potrebno za završetak operacije nad datotekom

- **EndReason** - nabrajanje za razlog završetka  Vrednosti: ništa, uspeh, neuspeh, otkazivanje

- **ErrorCode** - kôd greške za operaciju nad datotekom

- **Extension** – prva četiri znaka oznake tipa datoteke koja se otvara.

- **FileSourceLocation** - nabrajanje za lokaciju datoteke. Moguće vrednosti: nijedno, lokalno, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, nepoznati server

- **FILETIME** - Vreme događaja

- **FirstBCSClientError_Info** informacije o kôdu greške koja se tiče konverzije datoteka

- **HttpStatusCode** - HTTP kôd za odziv za zahtev za veb uslugu

- **InitalizationReason** - Ulazna tačka za otvaranje datoteke

- **K2FileIOHresult**- Hresult kod za okončanje operacije otvaranja datoteke

- **LastBCSClientError_TagId** - poslednja greška u programu BCS (usluga binarne konverzije) klijenta

- **OfficeWebServiceApiStatusFlag** - zastavica statusa za zahtev za Veb uslugom

- **OpEndEventId** - oznaka koja predstavlja mesto na kojem je operacija zapravo završena

- **OpFlags** - Oznake parametara operacije nad dokumentom koje koristi AppDocs sloj

- **OpSeqNum** – Broj koji predstavlja redosled poziva vezanih za operacije nad datotekama u AppDocs sloju

- **OpType** - nabrajanje tipa operacije. Vrednosti: "Ništa", "Kreiraj Document", "Otvori Document", "Kopiraj dokument", "Zatvori Document", "Sačuvaj dokument", "Otvori Verziju", "Zatvori verziju"

- **PreFetchState** - nabrajanje za učitavanje predložaka u pozadini za operacije kreiranja nove datoteke.

- **ProviderApp** - ime paketa aplikacije iz koje je datoteka otvorena

- **ScopeInstanceId** - ID instance opsega koji se koristi za povezivanje konteksta podataka sa aktivnostima

- **Size** - veličina datoteke

- **State** - nabrajanje za stanje datoteke. Vrednosti: ništa, kreiranje, kreirano, kreiranje nije uspelo, otvaranje, otvoreno, otvaranje nije uspelo, kopiranje, iskopirano, kopiranje nije uspelo, zatvaranje, zatvoreno, zatvaranje nije uspelo

- **TemplateName** – ime binarnog predloška dokumenta iz usluge predložaka, npr. TF10002009. dotx

- **UriScheme** – šema URL adrese

#### <a name="officeandroidauthaceerrors"></a>Office.Android.AuthACEErrors

Ovaj događaj koristi Microsoft nalog (MSA) da bi utvrdio koji korisnik pokušava da se prijavi u aplikaciju i tokom toga koja se telemetrija u diskusiji pokreće kao deo neuspelog pokušaja.  

Ovaj događaj pomaže u analizi grešaka distribucije MSA prijavljivanja, što pomaže u razumevanju razloga koji se nalaze iza neuspešnih tokova MSA prijavljivanja.

Prikupljaju se sledeća polja:

- **Nazivi izuzetaka** – Označava klase izuzetaka s obzirom na oznake izuzetaka koje se javljaju tokom toka prijave na Microsoft nalog.

- **Oznake izuzetaka** – označava koji izuzeci ulaznog toka prisutni u uniji se javljaju za tok prijave na MSA.

- **IDCRLACEErrorCode** – Daje kod greške koja se pojavljuje tokom MSA toka prijavljivanja. Različiti kodovi grešaka pomenuti u %SRCROOT%\identity\coreapi\public\IdentityData.h

- **IDCRLAuthenticationStatusErrorCode** – Označava kodove za greške za nevažeći status Rezultata potvrde identiteta koji dolazi iz Microsoft naloga (MSA). 

- **IDCRLUserInteractionMissingError** – Označava da li je tok prijave na Microsoft nalog (MSA) pozvan showUI zastavicom kao greškom koja izaziva udarac.


#### <a name="officeandroidbcserrors"></a>Office.Android.BCS.Errors

Telemetrija za greške binarne konverzije za štampanje i deljenje PDF-a.  Microsoft ovo koristi za identifikovanje tački u kojima dolazi do neuspešne BCS konverzije u aplikacijama Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **DocumentFileSize** - Veličina datoteke.

- **FileExtension** – Prva četiri znaka oznake tipa datoteke koja se otvara.

- **IsFileDirty** - Logička vrednost koja označava da li su postojale nesačuvane izmene u datoteci

- **Location** - Nabrajanje za lokaciju datoteke.  Vrednosti: OneDrive, SharePoint, Dropbox itd.

- **PDFConversionError** - oznaka kod koje dolazi do greške pri konverziji PDF-a

- **PdfConversionErrorCode** - kôd greške pri konverziji PDF-a

- **PdfConversionHRStatus** - kôd greške pri konverziji PDF-a

- **PdfConversionResult** – nabrajanje rezultata PDF konverzije.  Vrednosti: "uspešno", "neuspešno" i "otkazano"

- **PdfFileSize** - Veličina PDF-a

#### <a name="officeandroidclientsideiap"></a>Office.Android.ClientSideIAP

Telemetrija kritičnih grešaka za prekid rada baze podataka u toku pregleda datoteka i dodaje mesta. Microsoft koristi ovo za identifikovanje problema sa oštećenjem baze podatake u aplikacijama koje mogu sprečiti korisnika da dodaje mesta ili da ih pretražuje u okviru aplikacija Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **ClientTransactionId** - GUID je prosleđen DSC-u za određeni zahtev za iskorišćavanje.

- **CollectionTime** - vreme završetka kupovine pretplate

- **CountryCode** – kôd zemlje klijenta koji se šalje DSC–u za klijentov zahtev za iskorišćavanje

- **GoPremiumEntryPoint** – Ulazna tačka za pokretanje kupovine 

- **IsActivateExistingSubscription** – Logička vrednost koja ukazuje na to da li je bila pokrenuta postojeća pretplata

- **IsErrorRetriable** - Logička vrednost koja označava da li je moguće ponoviti iskorišćavanje

- **IsPreviousPurchase** - Logička vrednost koja označava da li se aktivacija dogodila sa prethodnom kupovinom pretplate

- **IsProvisioningTriggeredByRetry** - Logička vrednost koja označava da li je došlo do ponovnog pokušaja

- **LanguageCode** – Šifra jezika klijenta koja se šalje DSC–u za klijentov zahtev za iskorišćavanje

- **ProductIdentifier** – MJ ime koje klijent pokušava da kupi

- **ProvisioningHttpStatusCode** - obezbeđivanje HTTP statusnog kôda obezbeđivanja

- **ProvisioningStatusCode** - obezbeđivanje statusnog kôda

- **PurchaseOrderId** - Identifikator porudžbenice koju izdaje Google/Samsung prodavnica

- **RedemptionTaskHR** - HRezultat za povraćaj pretplate

- **SubscriptionProvisioningSucceeded** - Logička vrednost za uspešan rezultat dodeljivanja privilegija

- **SubscriptionPurchaseHR** - Hrezultat za kupovinu pretplate

- **SubscriptionType** - nabrajanje za tip pretplate ili MJ-a.

- **TCID** - klik na ikonu pokreće tok pretplate

#### <a name="officeandroiddbfailurecause"></a>Office.Android.DBFailureCause

Telemetrija kritičnih grešaka za prekid rada baze podataka u toku pregleda datoteka i dodaje mesta. Microsoft koristi ovo za identifikovanje problema sa oštećenjem baze podatake u aplikacijama koje mogu sprečiti korisnika da dodaje mesta ili da ih pretražuje u okviru aplikacija Word, Excel ili PowerPoint.

Prikupljaju se sledeća polja:

- **ErrorAt** - Vrednost oznake: podaci o mestu na kome je došlo do otkazivanja

- **ExceptionErrorMessage** - detaljna poruka o grešci

#### <a name="officeandroidearlytelemetryexpansionfileserrors"></a>Office.Android.EarlyTelemetry.ExpansionFilesErrors

Android Package Kit (APK) datoteke proširenja za Office aplikaciju za mobilne uređaje su dodatne datoteke resursa koje projektanti Android aplikacija mogu da objave uz svoju aplikaciju. Da bismo mehanizme preuzimanja datoteka proširenja učinili pouzdanijim, evidentiramo uzroke grešaka do kojih dolazi pri preuzimanju datoteka proširenja ili prilikom čitanja preuzetih datoteka proširenja.

Prikupljaju se sledeća polja:

- **Data_ClassName** – Tekst koji predstavlja ime datoteke izvornog koda tamo gde postoji greška.

- **Data_ErrorMessage** – Tekst koji predstavlja operaciju koja nije uspela.

- **Data_ExceptionMessage** – Opcionalno tekstualno polje koje predstavlja uzrok izuzetka.

- **Data_ExceptionType** – Opcionalno tekstualno polje koje predstavlja ime izuzetka koji se izbacuje iz izvornog koda.

- **Data_MethodName** – Tekst koji predstavlja ime metoda u izvornom kodu tamo gde postoji greška.

#### <a name="officeandroidearlytelemetryextractionerror"></a>Office.Android.EarlyTelemetry.ExtractionError

Da bismo smanjili veličinu Office Android aplikacija, primenjujemo kompresiju na resurse u završnom paketu. Za vreme izvršavanja, pre korišćenja prvo izvlačimo ove resurse. Ponekad postoje neočekivane greške prilikom izvršavanja izdvajanja, što dovodi do pada aplikacija. 

Kroz ovaj događaj prikupljamo neke dijagnostičke informacije povezane sa izdvajanjem, kao što je ime resursa koji se izdvaja, putanja gde se izdvaja itd., dostupan slobodan prostor na disku itd. Ovi podaci se prikupljaju samo kada postoje greške pri izdvajanju.  

Ove podatke koristimo da bismo razumeli uzrok grešaka u izdvajanju i poboljšali korisničko iskustvo naših aplikacija.

Prikupljaju se sledeća polja:

- **Data_ArchiveName** – ime resursa koji se izdvaja.

- **Data_ArchivePath** – putanja u kojoj je resurs privremeno keširan.

- **Data_ArchiveSizeKB** – veličina resursa koji se izdvaja.
 
- **Data_ClassName** – Ime datoteke u izvornom kodu gde je došlo do greške.

- **Data_ErrorDetail** – Tekst koji opisuje više detalja o uzroku greške, kao što je kod greške itd.

- **Data_ErrorMessage** – Tekst koji opisuje vrstu greške do koje je došlo prilikom izdvajanja.

- **Data_ExtractionDestinationPath** – Putanja na kojoj će resurs biti sačuvan nakon izdvajanja.

- **Data_FreeDiskSpaceMB** – količina slobodnog prostora na disku dostupna na uređaju, merena u megabajtima. 

- **Data_ItemToExtract** – ime resursa koji se izdvaja.

- **Data_MethodName** – Ime metode u izvornom kodu gde je došlo do greške.


#### <a name="officeandroidearlytelemetryregistryerrors"></a>Office.Android.EarlyTelemetry.RegistryErrors

Ovaj događaj hvata sve greške na koje se naišlo tokom pristupa Android registratoru. Ovi podaci o događaju nam pomažu da razumemo korisničke greške i ojačamo funkciju registratora.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj.

- **AppVersionLong** – Verzija aplikacije.

- **Data_StackTrace** – Praćenje steka greške.

#### <a name="officeandroidearlytelemetrysharedlibraryloadersearchandloadlibraryerror"></a>Office.Android.EarlyTelemetry.SharedLibraryLoadersearchAndloadLibraryError 

Evidentiramo ovaj događaj u slučaju da dođe do grešaka pri učitavanju deljenih biblioteka. Do grešaka pri učitavanju biblioteka može da dođe iz dva razloga 1) instalirana aplikacija nije kompatibilna sa uređajem. 2) Biblioteka koju pokušavamo da učitamo možda je oštećena zbog grešaka pri izdvajanju koje su posledica nedostatka prostora na disku ili nedovoljne količine dostupne memorije.

Prikupljaju se sledeća polja:

- **Data_ExceptionMessage** - Poruka o grešci koja potiče od Android API System.loadlibrary

- **Data_FreeSpaceInMB** - Dostupan slobodni prostor na uređaju

- **Data_nickName** – Ime biblioteke koju nije moguće učitati.

#### <a name="officeandroidintuneintunejavacopyfailedattempts"></a>Office.Android.Intune.IntuneJavaCopyFailedAttempts

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi se sačuvala lokalna kopija dokumenata u oblaku koji su zaštićeni putem Intune-a  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- **Data_FileCreationFailedErrorCode** kôd greške povezan sa tokom

#### <a name="officeandroidintuneintunejavaexceptionadaltokenformam"></a>Office.Android.Intune.IntuneJavaExceptionADALTokenForMAM

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi se pribavio ADAL token za Intune resurse.  Microsoft koristi ove podatke za identifikovanje grešaka tokom Intune upisivanja podataka unutar aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- **Data_ErrorCode** - kôd greške povezan sa tokom

#### <a name="officeandroidintuneintunejavaexceptionapppolicy"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicy

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi pozvala Intune API-je povezane sa dobavljanjem smernica za identitet trenutnog procesa.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:
 
- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionapppolicyforcontext"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicyForContext

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi pozvala Intune API-je povezane sa dobavljanjem smernica za identitet trenutne aktivnosti.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:
 
- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionauthenticationcallback"></a>Office.Android.Intune.IntuneJavaExceptionAuthenticationCallback

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi pozvala Intune API-je povezane sa registracijom povratnih poziva potvrde identiteta za kontrolisane naloge.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetaccountstatesync"></a>Office.Android.Intune.IntuneJavaExceptionGetAccountStateSync

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja povezanih sa kontrolisanim nalogom.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:
 
- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetissavetolocationallowed"></a>Office.Android.Intune.IntuneJavaExceptionGetIsSaveToLocationAllowed

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka da bi dobavila smernice povezane sa lokalnim čuvanjem.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetpolicyforidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetPolicyForIdentity

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za dobavljanje smernica za identitet.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofromdescriptor"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromDescriptor

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za podatke o zaštiti.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:
  
- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofrompath"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromPath

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za podatke o zaštiti.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptiongetuipolicyidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetUIPolicyIdentity

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za dobavljanje smernica korisničkog interfejsa za kontrolisani nalog.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionisidentitymanaged"></a>Office.Android.Intune.IntuneJavaExceptionIsIdentityManaged

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja povezanih sa identifikovanjem kontrolisanog naloga.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle Intune upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga.

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionnullenrollmentmanager"></a>Office.Android.Intune.IntuneJavaExceptionNullEnrollmentManager

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za registraciju komponenti za povratni poziv.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionprotect"></a>Office.Android.Intune.IntuneJavaExceptionProtect

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za zaštitu kontrolisanog dokumenta.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle Intune upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga.

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionprotectfromdescriptorifrequired"></a>Office.Android.Intune.IntuneJavaExceptionProtectFromDescriptorIfRequired

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za zaštitu kontrolisanog dokumenta.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionRegisterAccountSync

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja povezanih sa registracijom Intune upravljanjem.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionsetuipolicyidentitysync"></a>Office.Android.Intune.IntuneJavaExceptionSetUIPolicyIdentitySync

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za podešavanje smernica za kontrolisani nalog.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionunregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionUnregisterAccountSync

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za scenario daljinskog brisanja za Intune upravljanje.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidintuneintunejavaexceptionupdatetoken"></a>Office.Android.Intune.IntuneJavaExceptionUpdateToken

Telemetrija kritičnih grešaka koja služi za praćenje padova pojedinačnih Intune API-ja; Ova telemetrija se evidentira u slučaju grešaka radi pozivanja Intune API-ja vezanih za token za ovlašćenje ažuriranja za kontrolisani nalog.  Microsoft koristi ove podatke za identifikovanje grešaka tokom i posle upisivanja u okviru aplikacije, nakon prijavljivanja u aplikaciju pomoću poslovnog naloga

Prikupljaju se sledeća polja:

- Nijedno

#### <a name="officeandroidlicenseactivationfailure"></a>Office.Android.LicenseActivationFailure

Telemetrija kritičnih grešaka koja služi za praćenje greški pri aktivaciji licenci za Office 365 unutar aplikacija Word, Excel ili PowerPoint.  Microsoft koristi ovo da analizira greške pri aktivaciji kupljene Office 365 licence.

Prikupljaju se sledeća polja:

- **EntryPoint** - Nabrajanje ulaznih tačaka za pokretanje toka aktiviranja licence

- **HResult** - kôd greške za neuspeh

- **IsGallatin** - Logička vrednost koja proverava da li se radi o Gallatin nalogu

- **MessageCode** - nabrajanje da bi se ukazalo na tačku otkazivanja aktivacije

- **PreviousEntryPoint** - Nabrajanje ulaznih tačaka za pokretanje toka aktiviranja licence

- **StateAfterActivation** - Nabrajanje da označi stanje licenciranja aplikacije pre početka toka aktivacije

- **StateBeforeActivation** - Nabrajanje da označi stanje licenciranja aplikacije pre početka toka aktivacije

- **UserAccountType** - nabrajanje da bi se ukazalo na to da li se radi o ličnom ili poslovnom nalogu.

#### <a name="officeandroidmsasigninuiprompts"></a>Office.Android.MSASignInUIPrompts

Ovaj događaj označava da je korisniku prikazan zahtev za prijavljivanje za lični ili poslovni nalog.  Ovaj događaj nam pomaže da razumemo ispravnost stanja prijavljivanja aplikacija i preduzmemo odgovarajuće radnje kada primetimo neočekivane ponovne zahteve za prijavljivanje 

Prikupljaju se sledeća polja:

- **ExternalCacheRefreshError** - Kôd greške pokušaja osvežavanja tokena, pre nego što prikaže zahtev za prijavljivanje.

- **LastLoginDelta** - Vreme proteklo od poslednjeg uspešnog prijavljivanja.

- **MSAserverUAID** – ID korelacije sa podacima o telemetriji usluge.

- **PreviousIdentityState** - Označava stanje naloga, npr. istekla sesija 

- **SignInResultCode** - Označava kod rezultata kraja zahteva za prijavljivanje.

- **UseCache** - Označava da li smo naterali korisnika da ponovo unese lozinku.

- **UserType** - Označava da li je nalog postojeći ili nov

- **WasIdentitySignedOut** – Označava da li je nalog u odjavljenim stanjem.


#### <a name="officeapplelicensingmacdractivationfailures"></a>Office.Apple.Licensing.Mac.DRActivationFailures

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za snimanje neuspeha aktivacije preduzeća Digital River (događaj evidentira ključ i proizvod koji su korišteni za aktiviranje, kao i primljeni kod greške).  Ovaj događaj se koristi za otkrivanje i pomoć pri rešavanju problema sa neuspelim aktivacijama (problemi preduzeća Digital River).

Prikupljaju se sledeća polja:

- **Data_DigitalRiverID** – ID Digital River proizvoda koji se mapira na ovaj Office proizvod – SKY

- **Data_Error** - niska koja predstavlja kôd greške aktivacije.

- **Data_ProductKey** - šifra proizvoda koja je pokušana da se aktivira

- **Data_ProductKeyHash** - aktivirana je kodirana šifra proizvoda

#### <a name="officeapplelicensingmacgetmachinestatuserrors"></a>Office.Apple.Licensing.Mac.GetMachineStatusErrors

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj prikuplja kod greške vraćen tokom periodične provere valjanosti licence pretplate. Kôd greške može da označava nedostupnost servera, ali i isticanje licence, ograničenje broja računara, nevažeći ID hardvera, itd. Ovaj događaj se koristi za nadgledanje stanja usluge Office licenciranja, ali i za istraživanje problema vezanih za upravljanje mašinom pretplate.

Prikupljaju se sledeća polja:

- **Data_Error** - prikupljamo nisku koja predstavlja kod greške

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Prati različita obaveštenja o greškama dobijene iz sandboxa. Koristi se za otkrivanje scenarija grešaka u sandboxu i tamo tako što ćete ga popraviti, da biste poboljšali produktivnost korisnika
 
Prikupljaju se sledeća polja:

- **AppId** -ID aplikacije

- **AppUrl** - pročišćena URL adresa aplikacije 

- **Result** - kôd greške rezultata

#### <a name="officefirstrunapplemaconiolkfirstrunstarted"></a>Office.FirstRun.Apple.MacONIOLKFirstRunStarted

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj nam daje do znanja da je korisnik uneo „Utisak pri prvom pokretanju“. Koristimo ovaj događaj da utvrdimo da li je uspešno pokrenut „Utisak pri prvom pokretanju“ (FRE).

Prikupljaju se sledeća polja:

- **Data_FirstRunCollectionTime** - vremenska oznaka koja registruje vreme kad je tok pokrenut.

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ove informacije koje izveštavaju o izuzecima su bitne da bi se procenila celokupna ispravnost grafičkog niza, kao i za identifikovanje delova koda u kojima često dolazi do grešaka kako bi se odredio prioritet istrage. Ove informacije koje izveštavaju o izuzecima su bitne da bi se procenila celokupna ispravnost grafičkog niza, kao i za identifikovanje delova koda u kojima često dolazi do grešaka. Ovo pomaže inženjeru da odredi koje greške u prikazivanju utiču na najveći broj korisnika, što nam omogućava da kao prioritet istrage postavimo otklanjanje problema posle kojih će najveći broj korisnika imati koristi.

Prikupljaju se sledeća polja:

  - **Data\_HResult** - Kôd greške koji je vraćen iz otkazivanja

  - **Data\_TagCount** - Broj svih grešaka do kojih je došlo

  - **Data\_TagID** - Identifikator greške do koje je došlo


#### <a name="officeofficemobilepersonalizedcampaigningerrors"></a>Office.OfficeMobile.PersonalizedCampaigning.Errors

Da bi povećao svest o funkcijama sistema Office Mobile koje korisnici još nisu istražili, Office Mobile se integriše sa IRIS-om za podršku u aplikacijama i prosleđenim obaveštenjima. U slučaju obaveštenja u aplikaciji, on snima greške koje se dešavaju tokom povlačenja ili prikazivanja obaveštenja i kada korisnik vrši interakciju sa obaveštenjem, kao i pružanje povratnih informacija IRIS serveru. U slučaju prosleđenih obaveštenja, snima greške koje se dešavaju tokom prikazivanja obaveštenja i kada korisnik stupi u interakciju sa obaveštenjem.

Prikupljaju se sledeća polja:

- **Class** – ime klase u kojoj se pojavila greška

- **CreativeId** – ID obaveštenja koje jedinstveno identifikuje obaveštenje i njegov sadržaj.

- **ErrorDetails** – Detalji o grešci

- **ErrorMessage** – Poruka o grešci.

- **ErrorReason** – najsloženiji razlog greške

- **Method** – ime funkcije u kojoj se pojavila greška.

- **RequestParams** – Zahtevajte parametre koji se koriste prilikom kontaktiranja IRIS servera radi povlačenja obaveštenja.

- **SurfaceId** – ID površine na kojoj će se prikazati obaveštenje.


#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder.Error

Prikuplja informacije o greškama koje se javljaju prilikom navigacije kroz deljeni kalendar. Ti podaci se koriste za praćenje ispravnosti API–ja deljenog kalendara, kao i za interakciju programa Outlook sa deljenim kalendarima.

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

  - **0 –** Ime procesa koji je prijavio oštećenje

  - **1 –** Bool koji ukazuje na to da li korisnik bira novu datoteku ili ne

  - **2 –** Broj drugih procesa u kojima je otvorena baza podataka

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

Prikuplja informacije o uspehu i neuspehu radnji „Prosleđivanja“, „Prosleđivanja priloga“ i „Prosleđivanja iCalendar-a“ koje su odgovor na pojedinačne, periodične i vanredne sastanke u Outlook prikazu e-pošte, kalendara i nadzora. Stopa grešaka u „Prosleđivanju“, „Prosleđivanju priloga“ i „Prosleđivanju iCalendar-a“ se aktivno prati da bi se otkrile nepravilnosti. Neuobičajene statistike ukazuju na grešku u sposobnosti programa Outlook da sprovede osnovne operacije kalendara. Ovi podaci se takođe koriste za dijagnozu drugih problema vezanih za kalendar koji se mogu otkriti.

Prikupljaju se sledeća polja:

  - **CountExceptionForward**- Broj prosleđenih vanrednih sastanaka 

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

Prikuplja informacije o uspehu i neuspehu radnji „Odgovaranja“, „Odgovaranja svima“, „Odgovaranja putem trenutne poruke“ i „Odgovaranja svima putem trenutne poruke“ koje su odgovor na pojedinačne, periodične i vanredne sastanke u Outlook prikazu e-pošte, kalendara i nadzora. Stopa grešaka u „Odgovaranju“, „Odgovaranju svima“, „Odgovaranju putem trenutne poruke“ i „Odgovaranju svima putem trenutne poruke“ se aktivno prati da bi se otkrile nepravilnosti. Neuobičajene statistike ukazuju na grešku u sposobnosti programa Outlook da sprovede osnovne operacije kalendara. Ovi podaci se takođe koriste za dijagnozu drugih problema vezanih za kalendar koji se mogu otkriti.

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

Koristi se za identifikovanje problema unutar aplikacije koji utiču na korisnika u okviru aplikacije koja se izvršava, a koji se ispoljavaju padovima ili umanjenom funkcionalnošću.

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Koristi se za identifikovanje problema unutar aplikacije koji utiču na korisnika u okviru aplikacije koja se izvršava, a koji se ispoljavaju padovima ili umanjenom funkcionalnošću.

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Koristi se za identifikovanje problema unutar aplikacije koja se izvršava i koji se mogu ispoljiti padovima ili umanjenom funkcionalnošću. Beleži greške koje se dešavaju u toku rada procesa

Prikupljaju se sledeća polja:

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **Broj** - Broj svih grešaka

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Koristi se za identifikovanje problema unutar aplikacije koji utiču na korisnika u okviru aplikacije koja se izvršava, a koji se mogu ispoljiti padovima ili umanjenom funkcionalnošću. Beleži greške koje se dešavaju u toku rada procesa.

Prikupljaju se sledeća polja:

Broj - Broj svih grešaka

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **KôdGreške** - Identifikator greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **IdGreške** - Identifikator greške

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Koristi se za identifikovanje problema unutar aplikacije koji utiču na korisnika u okviru aplikacije koja se izvršava, a koji se mogu ispoljiti padovima ili umanjenom funkcionalnošću. Beleži greške koje se dešavaju u toku rada procesa.

Prikupljaju se sledeća polja:

  - **Broj** - Broj svih grešaka

  - **VremeZavršetka** - Vreme kada se dogodila poslednja greška koja je prijavljena

  - **KôdGreške** - Identifikator greške

  - **GrupaGreške** - Identifikator grupe za svaku grešku

  - **IdGreške** - Identifikator greške

  - **PrvaVremenskaOznaka** - Kada je prvi put došlo do greške

  - **PraćenjeUnazad** - Jedinstveni identifikator određene greške

#### <a name="renewidentityfailure"></a>RenewIdentityFailure

Sakuplja se kada korisnik pokuša da otvori dokument zaštićen IRM zaštitom ili primeni IRM zaštitu. Sadrži informacije potrebne za pravilno ispitivanje i dijagnostikovanje problema koji se dešavaju u slučaju neuspešnog obnavljanja korisničkih sertifikata.

Prikupljaju se sledeća polja:

- **AppInfo.ClientHierarchy** – Hijerarhija klijenata koja označava da aplikacija radi u proizvodnom okruženju ili razvojnom okruženju

- **AppInfo.Name** – Ime aplikacije.

- **AppInfo.Version** - Verzija aplikacije

- **Failure.Category** – Kategorija greške „UnhandledError”

- **Failure.Detail** - Detaljne informacije o grešci

- **Failure.Id** – Id greške

- **Failure.Signature** – Potpis greške, koji je isti kao ime događaja

- **iKey** – ID servera usluge vođenja evidencije

- **RMS.HRESULT** – Rezultat obnavljanja korisničkog certifikata

- **RMS.ScenarioId** – ID scenarija definisan klijentom Usluge upravljanja pravima

- **RMS.SDKVersion** - Verzija klijenta usluge Rights Management

#### <a name="saveerror"></a>save.error

Dozvoljava nam da otkrijemo i popravimo situacije u kojima je došlo do greške kada ste pokušali da sačuvate datoteku.  On prati greške izazvane neuspesima pri čuvanju datoteke, uključujući i opisnu poruku o grešci kako bi nam pomogao da rešimo problem.

Prikupljaju se sledeća polja: 

- **error** - tip greške koji se dogodio da bi nam pomogao da otkrijemo i rešimo probleme u vezi sa određenim tipom greške

- **file_type** - tip datoteke koji je korisnik pokušao da sačuva (na primer. doc)

- **origin** - odakle potiče pokušaj čuvanja datoteke, (na primer, iz e-poruke) kako bismo mogli da otkrijemo probleme koje se odnose na čuvanje datoteke sa određenog mesta u aplikaciji

- **token_type** - tip simbola koji se koristi za potvrdu identiteta naloga da biste sačuvali datoteku kako bi nam pomogao u otkrivanju problema potvrde identiteta povezanog sa čuvanjem datoteke

#### <a name="wkwebviewerror"></a>wkwebview.error

Ovaj događaj nam omogućava da otkrijemo kada su nastale greške u prikazu na vebu prilikom sastavljanja ili čitanja e-poruke kako bismo mogli da sprečimo probleme koji mogu da dovedu do toga da aplikacija ne može da sastavi e-poruku ili da čita e-poruku. 

Prikupljaju se sledeća polja: 

- **description** – opis za grešku

- **error_code** – kôd greške za WKError

- **function_name** – JavaScript ime funkcije kada je došlo do greške

- **js_exception_column_number** – broj kolone u kojoj je došlo do JavaScript izuzetka 

- **js_exception_line_number** – broj reda u kome je došlo do JavaScript izuzetka

- **js_exception_message** – poruka izuzetka kada je došlo do JavaScript izuzetka

- **js_exception_source_url** – izvorna URL adresa gde je došlo do JavaScript izuzetka  

- **scenario** – gde je došlo do greške. To je prebrojavanje. Moguće vrednosti su old_renderer, react_renderer i sastavljanje.

#### <a name="wkwebviewterminate"></a>wkwebview.terminate

Ovaj događaj nam omogućava da otkrijemo kada sistem prekida veb prikaz. Ovi podaci nam omogućavaju da nadgledamo grešku koju je korisnik naišao prilikom sastavljanja ili čitanja e-poruke. 

Prikupljaju se sledeća polja: 

- **is_foreground** – da li je aplikacija u prvom planu kada se ovaj događaj dešava.

- **Scenario** – gde je došlo do greške, prilikom prikazivanja ili sastavljanja.


## <a name="device-connectivity-and-configuration-data-events"></a>Podaci dobijeni iz povezivanja uređaja i konfiguracije

Podtipovi podataka koji spadaju u ovu kategoriji su:

- [Povezivanje uređaja i konfiguracija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Podtip povezivanja uređaja i konfiguracije*

Stanje mrežne veze i podešavanje uređaja, kao što je memorija.

#### <a name="applicationdidreceivememorywarning"></a>application.did.receive.memory.warning

Ovaj događaj se šalje kada nam Apple saopštava da je aplikaciji ponestaje memorije. Govori nam da smo uvezli problem sa menadžmentom memorije na uređaju.

Prikupljaju se sledeća polja: 

- **current_memory_used** - objašnjava količinu memorije koju aplikacija koristi u trenutku kada aplikacija nema više memorije.

- **current_memory_used_percentage** – govori nam procenat memorije koji aplikacija koristi od ukupne raspoložive memorije na tački na kojoj je aplikaciji ponestalo memorije.

- **currentVC** - saopštava nam prikaz koji se trenutno prikazuje kada aplikaciji ponestane memorije.

- **has_hx** - govori nam da nalog koristi našu novu uslugu sinhronizacije kako bi nam pomogao da otkrijemo probleme izazvane uslugom sinhronizacije

- **is_watch_app_installed** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je instaliran da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **is_watch_paired** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je uparen sa uređajem da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **is_watch_supported_and_active** – saopštava nam da li korisnik trenutno koristi Apple Watch i da li je aktivan da biste nam pomogli da shvatimo uticaj negativnih performansi zahvaljujući usluzi Watch

- **rn_initialized** - recite nam da li je React Native pokrenut u trenutku kada je aplikaciji ponestalo memorije.

- **running_time** - saopštava nam koliko vremena je aplikacija potrošila radeći u trenutku kada je aplikacija ostala bez memorije.

#### <a name="conversationmemoryleak"></a>conversation.memory.leak

Dozvoljava nam da otkrijemo situacije u kojima nas prikaz razgovora e-pošte tera da iskoristimo više memorije na uređaju nego što se očekuje.

Prikupljaju se sledeća polja:

- Ne prikupljaju se polja ili dodatni podaci. Samo evidencije se sakupljaju ako postoji curenje memorije koje se odnosi na deo razgovora.

#### <a name="coredatacorruption"></a>core.data.corruption

Omogućava nam da otkrijemo situacije u kojima ne možemo da vam pokažemo vašu e-poštu ili kalendar zato što je mesto gde skladištimo vašu e-poruku na uređaju oštećeno.

Prikupljaju se sledeća polja:

- **errorSource** - ukazuje na to da li je došlo iz radnje čuvanja ili kreiranja

- **sqlError** - numerički kôd greške na navedenoj lokacijihttps://www.sqlite.org/c3ref/c_abort.html

#### <a name="coredatacorruptionuserreset"></a>core.data.corruption.user.reset

Dozvoljava nam da otkrijemo situacije u kojima ste izbrisali ili poništili uspostavljanje naloga u našoj aplikaciji i to uzrokovano oštećenjem podataka e-pošte koje smo uskladištili na uređaju.

Prikupljaju se sledeća polja:

- **errorSource** - diktira mesto na kojem se oštećenje dogodilo tokom čuvanja ili kreiranja

#### <a name="coredatadiagnostics"></a>core.data.diagnostics 

Omogućava nam da otkrijemo i rešimo situacije u kojima skladište e-pošte koristi previše prostora za skladištenje uređaja

Prikupljaju se sledeća polja:

- **db_size_megabytes** - prati veličinu osnovne baze podataka zaokruženu na najbližih 25 megabajta i maksimalnih 500 megabajta

#### <a name="generalpropertieslog"></a>general.properties.log

Ovaj događaj prikuplja informacije koje nam omogućavaju da razvrstavamo i klasifikujemo probleme unutar Outlook aplikacije koje su u vezi sa postavkama pristupačnosti i uređaja.  Ova kategorizacija je neophodna da biste odredili određivanje prioriteta uticaja problema na korisnike.

Prikupljaju se sledeća polja samo za iOS:

- **alternate_app_icon**– Recite nam koju je alternativnu ikonu aplikacije koju je trenutno izabrala aplikacija

- **bold_text** - saopštava nam da li uređaj ima uključen podebljani tekst kako bi nam pomogao da otkrijemo problem koji se odnosi na podebljani tekst

- **closed_caption** – saopštava nam ako je korisnik uključio pomoćni titl na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa pomoćnim titlovima

- **darker_system_colors** – saopštava nam ako je korisnik uključio zamračenje sistemskih boja na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **gray_scale** - saopštava nam da li je korisnik uključio sivu skalu na svom uređaju kako bi nam pomogao da otkrijemo probleme vezane za ovu postavku 

- **guided_access** – saopštava nam ako je korisnik uključio vođeni pristup na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **invert_colors** – saopštava nam ako je korisnik uključio postavku da obrne boje na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **mono_audio** – saopštava nam ako je korisnik uključio postavku za mono audio na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **reduce_motion** – saopštava nam ako je korisnik uključio postavku za smanjivanje kretanja na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **reduce_transparency** - saopštava nam da li je korisnik uključio postavku radi smanjenja transparentnosti na svom uređaju kako bi nam pomogao da otkrijemo probleme vezane za ovu postavku 

- **speak_screen** – saopštava nam ako je korisnik uključio postavku za mono audio na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **speak_selection** – saopštava nam ako je korisnik uključio postavku za početak izbora na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **switch_control** – saopštava nam ako je korisnik uključio postavku za prebacivanje kontrole na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **voice_over** – saopštava nam ako je korisnik uključio postavku za glasove na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

Prikupljaju se sledeća polja samo za Android:

- **braille** – saopštava nam ako je korisnik uključio postavku da obrne boje na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **caption** – saopštava nam ako je korisnik uključio pomoćni titl na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa pomoćnim titlovima

- **color_inversion** – saopštava nam ako je korisnik uključio postavku da obrne boje na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **density_setting** – prilagođen (izabrana od strane korisnika) režim gustine koju aplikacija trenutno koristi

- **high_contrast** – saopštava nam ako je korisnik uključio postavku za veliki kontrast na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **large_text** - saopštava nam da li uređaj ima uključene postavke za veliki tekst kako bi nam pomogao da otkrijemo problem u vezi sa ovom postavkom

- **oem_preinstall** - saopštava nam da li je aplikacija unapred instalirana na uređaju (ovo se odnosi samo na Samsung uređaje)

- **supported_abis** - govori nam koju vrstu binarnog interfejsa aplikacije (ABIs) podržava platforma uređaja kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **switch_access** – saopštava nam ako je korisnik uključio postavku za prebacivanje pristupa na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **talkbalk** – saopštava nam ako je korisnik uključio postavku za vezu na uređaju kako bi nam pomogao da otkrijemo probleme u vezi sa ovom postavkom

- **theme_color** – prilagođena (izabrana od strane korisnika) boja teme koju aplikacija trenutno koristi

- **webview_kernel_version**: verzija jezgra sistema Chromium veb prikaza na uređaju koja nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.

- **webview_package_name**: naziv paketa veb prikaza na uređaju koji nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.

- **webview_package_version**: verzija paketa veb prikaza na uređaju koji nam pomaže da prepoznamo probleme sa kompatibilnošću povezane sa verzijom veb prikaza.

#### <a name="lowstoragewarning"></a>low.storage.warning

Ovo je potrebno da biste nadgledali da li nam aplikacija iznenada preuzima većinu skladišta uređaja zbog velike upotrebe memorije označavajući kada uređaj ima malo prostora za skladištenje

Prikupljaju se sledeća polja: 

- **free_bytes** - količina besplatnog prostora za skladištenje dostupnog na uređaju

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

Prikuplja se kad god PowerPoint detektuje da nema veze sa internetom. Microsoft koristi ove podatke da bi dobio dijagnostičke informacije o internet vezi korisnika u cilju razumevanja njenog uticaja na povezivanje sa uslugama sistema Office.

Prikupljaju se sledeća polja:

- **Data\_IsNexusDetected:bool** - prikazuje da li imamo vezu sa internetom prilikom pozivanja usluge Nexus (vrednost tačno) ili prilikom pozivanja generičke veb usluge API (vrednost netačno)

#### <a name="officeserviceabilitymanagerofficesvcmgrprofile"></a>Office.ServiceabilityManager.OfficeSvcMgrProfile

Ovaj događaj se pokreće kada se pokrene Office funkcija Upravljač servisiranja, i od izuzetne je važnosti za obezbeđivanje tačnih uvida vezanih za status primene kao i padove aplikacija i dodataka u okviru korisnikovog zakupca time što nam omogućava da IT administratoru obezbedimo uvid na osnovu koga će moći da sa lakoćom da ažurira računare svog preduzeća.  

Prikupljaju se sledeća polja:

- **DeviceIdJoinToken** – koristi se za pridruživanje telemetrijskih podataka o statusu ispravnosti i primene i drugih funkcionalnih podataka koji se prikupljaju pomoću kanala usluga.

- **TenantAssociationKeyStamped** - Logička oznaka koja se koristi za utvrđivanje broja kontrolisanih uređaja u okviru Office ekosistema.
