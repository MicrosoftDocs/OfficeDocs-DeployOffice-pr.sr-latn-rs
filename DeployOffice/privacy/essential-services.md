---
title: Osnovne usluge za Office
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
description: Administratorima sistema Office pruža informacije o osnovnim uslugama u sistemu, kao što su „Klikni i pokreni“ i licenciranje, a pruža i listu događaja i polja sa podacima o ovim osnovnim uslugama.
hideEdit: true
ms.openlocfilehash: 66a34445b66389f82d7be4ab87d34ab9b331c675
ms.sourcegitcommit: 85bef3bf44e4d6db25fd5817a0e49a159642dab2
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/16/2021
ms.locfileid: "53456164"
---
# <a name="essential-services-for-office"></a>Osnovne usluge za Office

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Office se sastoji od aplikacija klijentskog softvera i povezanih iskustava dizajniranih tako da vam omogućavaju da efikasnije kreirate, komunicirate i sarađujete. Iako možete da kontrolišete mnoga povezana iskustva koja su dostupna vama ili, ako ste administrator organizacije, vašim korisnicima, postoji i skup usluga koje su od suštinske važnosti za funkcionisanje sistema Office, te stoga ne mogu biti onemogućene. Na primer, usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office. Neophodni podaci o ovim uslugama prikupljaju se i šalju korporaciji Microsoft, bez obzira na bilo koje druge postavke smernica za privatnost koje ste konfigurisali.

Više informacija potražite u sledećim člancima:

- [Neophodni podaci o usluzi za Office](required-service-data.md)
- [Povezana iskustva u sistemu Office](connected-experiences.md)

Ako ste administrator organizacije, možda će vas zanimati i sledeći članci:

- [Pregled kontrola privatnosti za Microsoft 365 Apps za velika preduzeća](overview-privacy-controls.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office aplikacije za veb](office-web-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Lista osnovnih usluga za Office 

Sledeća tabela sadrži listu osnovnih usluga za Office i njihov opis.

| **Usluga**  | **Opis**  |
| ------ | ---- |
| [Potvrda identiteta](#authentication-events) | Potvrda identiteta je usluga koja se nalazi na bilo kom uređaju i koja potvrđuje vaš korisnički identitet u sistemu Office. Ona je potrebna za prijavljivanje u Office, aktiviranje Office licence, pristup vašim datotekama koje su uskladištene u oblaku i za pružanje doslednog iskustva u svim Office sesijama i uređajima.    |
| [Klikni i pokreni](#click-to-run-events) | „Klikni i pokreni“ je tehnologija instaliranja koja se koristi za instalaciju i ažuriranje sistema Office na operativnom sistemu Windows. Ona proverava da li postoje nove verzije sistema Office, a kada nova verzija postane dostupna, preuzima je i instalira.  „Klikni i pokreni“ će otkrivati potrebu za preuzimanjem i instaliranjem Office ispravki, kao i bezbednosnih zakrpi.     |
| [Usluga poboljšane konfiguracije (UPK)](#enhanced-configuration-service-ecs-events) | UPK omogućava korporaciji Microsoft da ponovo konfiguriše instalacije sistema Office, a da vi ne morate ponovo da ga instalirate. Koristi se za kontrolu postepenog objavljivanja funkcija i ažuriranja, dok se uticaj objavljivanja nadgleda preko dijagnostičkih podataka koji se prikupljaju. Takođe se koristi i za smanjivanje bezbednosnih problema i problema performansi uz pomoć funkcija ili ažuriranja. Osim toga, UPK podržava promene u konfiguraciji koje se odnose na dijagnostičke podatke kako bi se obezbedilo prikupljanje odgovarajućih događaja. |
| [Licenciranje](#licensing-events)     | Licenciranje je usluga zasnovana na tehnologiji oblaka koja održava vašu Office aktivaciju tokom novih instalacija i čuva licencu na vašim uređajima nakon aktivacije. Ona registruje svaki od vaših uređaja i aktivira Office, provera status vaše pretplate na sistem Office i upravlja vašom šifrom proizvoda.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) predstavlja tehnologiju koja se koristi za ažuriranje Microsoft aplikacija za macOS, na primer za Office. MAU otkriva potrebu za ispravkama za aplikacije, kao i bezbednosnim ispravkama, preuzima ih i instalira.|
|[Sinhronizovanje programa OneNote](#onenote-sync-events)|OneNote za Mac podržava samo beležnice uskladištene na internetu u usluzi OneDrive ili SharePoint Online. OneNote za Mac neprestano sinhronizuje sve beleške korisnika sa uslugom OneDrive ili SharePoint Online. To korisnicima omogućava otvaranje, pregled i uređivanje beležnica na svim uređajima tako da su njihove beležnice uvek ažurne.
 [Konfiguracija usluga](#services-configuration-events)  | Konfiguracija usluga pruža mogućnost ažuriranja postavki konfiguracije za Office da bi se omogućile ili onemogućile funkcije klijenta. Ova funkcija se poziva svaki put kada se pokrene Office aplikacija i pruža detalje o ostalim konfiguracijama i uslugama sistema Office. Konfiguracija usluga takođe kontroliše koje usluge su određene kao osnovne.  |
| [Telemetrija ](#telemetry-events)  | Usluga telemetrije se koristi za prikupljanje dijagnostičkih podataka iz Office aplikacija. Ona omogućava prikupljanje dijagnostičkih podataka koje generiše Office, i obaveznih i opcionalnih. Takođe je odgovorna za delimično prikupljanje neophodnih podataka o usluzi za Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Događaji i polja sa podacima za osnovne usluge za Office

Odeljci u nastavku pružaju sledeće informacije:

- Listu događaja za svaku osnovnu uslugu
- Opis svakog događaja
- Listu polja sa podacima u svakom događaju
- Opis svakog polja sa podacima


## <a name="authentication-events"></a>Događaji potvrde identiteta

Ovi događaji dijagnostičkih podataka se prikupljaju kada Office pokuša da preuzme token potvrde identiteta, ili tiho ili putem upita.

### <a name="officeandroidmsaguesttoaad"></a>Office.Android.MSAGuestToAAD

Ovaj događaj pomaže u razumevanju koliko korisnika se traži za unošenje lozinke za lični nalog, dok pristupaju radnom resursu, jer bi njihov lični nalog mogao da bude validan zakupac gosta na poslu.

Ovi podaci nam pomažu da shvatimo koliko korisnika prolazi kroz muku zbog ponovnog pokretanja zahteva da prioritetno dobiju AAD tokene tiho na osnovu tvrdnje Microsoft računa SAML (Securiti Assertion Markup Language).

Prikupljaju se sledeća polja:

- **Tag** - Označava da je korisnik dobio poziv za prijavu za lični nalog, dok je pristupao resursima radnog naloga.


### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Prikuplja se kada Office prikaže korisniku Forms-Based-Auth upit za prijavljivanje zasnovan na formularu za potvrdu identiteta.

Pored tihog preuzimanja tokena, upit za potvrdu identiteta se koristi da se odredi da li se korisnik nalazi u statusu neispravne potvrde identiteta, što bi za korisnika značilo da je stanje klijenta van mreže, a u najgorem slučaju, neispravna potvrda identiteta može sprečiti preuzimanje licence i dovesti do potpuno neupotrebljivog klijenta.

Upiti za prijavljivanje zasnovani na formularu za potvrdu identiteta (FBA – Forms-Based-Auth) se koriste u nekim scenarijima za lokalnu potvrdu identiteta i uglavnom se trudimo da se to ne dešava jer bi svi trebalo da koriste modernu identifikaciju (modern-Auth) zbog bezbednosnih ranjivosti koje se odnose na FBA.

Prikupljaju se sledeća polja:

  - **AuthScheme** - šema koja se koristi za potvrdu identiteta

  - **DocumentUrlHash** - šifrovani URL zahtevi

  - **EndTag** - oznaka gde je završen FBA obrazac

  - **Flags** - zastarelo

  - **EndTag** - oznaka gde počinje FBA obrazac

  - **LastError** - vraćanje koda greške

  - **PromptEndTime** - vreme kada je upit završen

  - **PromptStartTime** - vreme kada je upit započet

  - **Rezultat** - da li je potvrda identiteta uspela

  - **SessionEndTime** - vreme kada je sesija događaja završena

  - **Timeout** - vreme kada je upit istekao

### <a name="officeidentitysignoutevent"></a>Office.Identity.SignOutEvent

Prikuplja se kada se korisnik odjavi sa sistema Office.

Saznanje da se korisnik odjavio omogućava klasifikaciju ostalih događaja, kao što su upiti, na način na koji se očekuje kako bi se pravilno izračunala njihova pouzdanost / metrička spremnost otpreme i da bi se izbeglo upozorenje i vraćanje na prethodne verzije zasnovano na lažnoj premisi da korisnik ima neočekivane probleme sa upitima za potvrdu identiteta.

Prikupljaju se sledeća polja:

  - **FlowEndTime** - vreme kada je aktivnost odjave završena

  - **FlowEndTime** - vreme kada je aktivnost odjave započeta

  - **IdentityErrorState** - bilo koji status greške identiteta prilikom odjave

  - **IdentityHashedUniqueId** - odjava šifrovanog ID identiteta

  - **IdentityProviderType** - odjava dobavljača identiteta

  - **IdentityUniqueID** - odjava ID identiteta

  - **SessionEndTime** - vreme kada je sesija događaja završena

  - **SignOutUserAction** - ukazuje na to da je korisnik započeo radnju odjavljivanja

### <a name="officeidentitysspipromptwin32"></a>Office.Identity.SspiPromptWin32

Prikuplja se kada Office prikaže korisniku Windows SSPI upit za prijavljivanje. Pored tihog preuzimanja tokena, upiti za potvrdu identiteta određuju da li se korisnik nalazi u statusu neispravne potvrde identiteta, što bi značilo da je stanje klijenta van mreže. Neispravna potvrda identiteta može sprečiti preuzimanje licence i dovesti do potpuno neupotrebljivog klijenta.

Windows SSPI upiti se koriste za potvrdu identiteta sa sistemom Exchange (za sinhronizaciju e-pošte) kada korisnikovi Exchange resursi nisu podešeni za višestruke potvrde identiteta.

Ovi događaji, zajedno sa događajima prostora Office.MATS, koriste se za sledeće svrhe:

1\) Utvrđivanje da li klijent može uspešno da pribavi token potvrde identiteta ili se nalazi u neispravnom stanju potvrde identiteta.

2\) Procenjivanje da li su promene koje su se desile u klijentu ili uslugama dovele do kritičnih regresija u korisničkom iskustvu potvrde identiteta i pouzdanosti.

3\) Kada dođe do greške, ovi signali emituju bitne kodove grešaka odgovornih komponenata (kôd Office klijenta, biblioteke potvrde identiteta, upravne usluge) i mogu se koristiti za trijažu, dijagnozu i ublažavanje.

4\) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka koje blokiraju korisnika

Prikupljaju se sledeća polja:

  - **AllowSavedCreds** - da li je novi akreditiv stalan

  - **AuthScheme** - šema koja se koristi za potvrdu identiteta

  - **CredsSaved** - da li je novi akreditiv sačuvan.

  - **DocumentUrlHash** - šifrovani URL zahtevi

  - **EndTag** - oznaka gde je upit završen.

  - **NewIdentity**\_ErrorState – da li je novi identitet važeći

  - **NewIdentity\_HashedUniqueId** - novi šifrovani ID identiteta kada se upit završi

  - **NewIdentity\_ProviderType** - novi dobavljač identiteta kada se upit završi

  - **NewIdentity\_HashedUniqueId** - novi šifrovani ID kada se upit završi

  - **OutStatus** – da li je izlaz upita važeći

  - **PromptEndTime** - vreme kada je upit završen

  - **PromptFailedTag** - oznaka koja označava neuspešnost SSPI upita

  - **PromptFlow** - oznaka koja poziva SSPI upit

  - **PromptStartTime** - vreme kada je upit započet

  - **Proxy** - ako se koristi proxy

  - **ServerHash** - šifrovana adresa servera

  - **SessionEndTime** - vreme kada je sesija događaja završena

  - **Timeout** - vreme kada je upit istekao

  - **UiMessage** - poruka korisničkog interfejsa u upitu 

  - **UserNameHash** - šifrovano korisničko ime

### <a name="officeidentitywin32prompt"></a>Office.Identity.Win32Prompt

Prikuplja se kada Office prikaže korisniku upit za prijavljivanje za višestruku potvrdu identiteta. Pored tihog preuzimanja tokena, upiti za potvrdu identiteta određuju da li se korisnik nalazi u statusu neispravne potvrde identiteta, što bi značilo da je stanje klijenta van mreže. Neispravna potvrda identiteta može sprečiti preuzimanje licence i dovesti do potpuno neupotrebljivog klijenta.

Ovi događaji, zajedno sa događajima prostora Office.MATS, koriste se za sledeće svrhe:

1\) Utvrđivanje da li klijent može uspešno da pribavi token potvrde identiteta ili se nalazi u neispravnom stanju potvrde identiteta.

2\) Procenjivanje da li su promene koje su se desile u klijentu ili uslugama dovele do kritičnih regresija u korisničkom iskustvu potvrde identiteta i pouzdanosti.

3\) Kada dođe do greške, ovi signali emituju bitne kodove grešaka odgovornih komponenata (kôd Office klijenta, biblioteke potvrde identiteta, upravne usluge) i mogu se koristiti za trijažu, dijagnozu i ublažavanje.

4\) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka koje blokiraju korisnika.

Prikupljaju se sledeća polja:

  - **AdalWAMUsed** - oznaka koja ukazuje na rezultat ako se koristi ADAL-atop-WAM

  - **CallTag** - oznaka koja ukazuje na poziv korisničkog interfejsa za prijavljivanje

  - **Context** - kontekst za upita za prijavljivanje

  - **EndTagIdentityProviderRequested** - oznaka gde je zatražen dobavljač identiteta

  - **HrdShownTag** - oznaka gde se prikazuje HDR dijalog za prijavljivanje

  - **IdentityProviderResulted** - tip dobavljača identiteta koji se zahteva

  - **IdPFlowTag** - oznaka koja ukazuje na rezultat zahteva identiteta

  - **LastLoginDelta** - vreme proteklo od poslednjeg uspešnog prijavljivanja

  - **NewIdentity\_** ErrorState – da li je novi identitet važeći nakon završenog upita

  - **NewIdentity\_ProviderType** - novi tip dobavljača identiteta nakon završenog upita

  - **NewIdentity\_HashedUniqueId** - novi dobijeni ID identiteta nakon završenog upita

  - **PromptCorrelation** - Upit ID korelacije za dijagnostičke svrhe

  - **PromptEndTime** - vreme kada je upit završen

  - **PromptStartTime** - vreme kada je upit započet

  - **SessionEndTime** - vreme kada je sesija događaja završena

  - **ShowUIResult** - vraćeni kôd rezultata iz upita korisničkog interfejsa

  - **StartTag** - oznaka gde počinje upit Win32

  - **Timeout** - vreme kada je upit istekao

  - **WasIdentitySignedOut** – da li je korisnik je odjavljen

### <a name="officematsactionofficewin32-officematsactionofficewinrt"></a>Office.MATS.actionofficewin32, Office.MATS.actionofficewinrt

Sledeći opisi se odnose na događaje Win32 i WinRT (ime zavisi od platforme)

Microsoft Auth Telemetry System (MATS) se prikuplja kada Office pokuša da preuzme token potvrde identiteta, ili tiho ili putem upita. Kada pokušaj preuzimanja ne uspe, šalju se i informacije o grešci. Ovi događaji pomažu korisnicima da izbegnu unošenje neispravne identifikacije tako što će:

1\) Utvrditi da li klijent može uspešno da pribavi token potvrde identiteta ili se nalazi u neispravnom stanju potvrde identiteta.

2\) Proceniti da li su promene koje su se desile u klijentu ili uslugama dovele do kritičnih regresija u korisničkom iskustvu potvrde identiteta i pouzdanosti.

3\) Kada dođe do greške, ovi signali emituju bitne kodove grešaka odgovornih komponenata (kôd Office klijenta, biblioteke potvrde identiteta, upravne usluge) i mogu se koristiti za trijažu, dijagnozu i ublažavanje.

4\) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka.

Prikupljaju se sledeća polja:

  - **Actiontype** - koja biblioteka potvrde identiteta se koristi

  - **Appaudience** - da li je aplikacija napravljena za internu ili spoljnu upotrebu

  - **Appforcedprompt** - da li aplikacija poništava keš i nameće pojavljivanje upita

  - **Appname** - ime aplikacije koja potvrđuje identitet

  - **Appver** - verzija aplikacije koja potvrđuje identitet

  - **Askedforcreds** - da li aplikacija traži od korisnika da unese akreditive za ovu radnju

  - **Authoutcome** - da li je pokušaj potvrde identiteta uspešan, neuspešan ili otkazan.

  - **Blockingprompt** - da li aplikacija izbacuje upit koji zahteva interakciju korisnika

  - **Correlationid** - GUID koji se koristi za spajanje sa uslužnim podacima

  - **Count** - broj događaja u slučaju agregacije

  - **Data\_accounttype** - nalog potrošača ili organizacije

  - **Devicenetworkstate** - da li je korisnik bio na mreži

  - **Deviceprofiletelemetryid** - Anonimni ID uređaja koji se koristi za merenje utiska pri radu sa uređajem

  - **Duration** - Koliko vremena je bilo potrebno za potvrdu identiteta

  - **Duration_Max** – Ako je ovaj signal agreriran, maksimalno trajanje bilo kog agreriranog događaja.

  - **Duration_Min** – Ako je ovaj signal agreriran, minimalno trajanje bilo kog agreriranog događaja.

  - **Duration_Sum** – Ako je ovaj signal agreriran, zbir trajanja svih agreriranih događaja.

  - **EndTime** - Kada je događaj potvrde identiteta završen

  - **Error** - Kôd greške ako potvrda identiteta nije uspela

  - **Errordescription** - Kratak opis greške

  - **Errorsource** - Da li je došlo do greške u usluzi, biblioteci potvrde identiteta ili aplikaciji

  - **Identityservice** - Da li je aktiviran nalog Microsoft usluge (MSA) ili usluge Azure Active Directory (AAD)

  - **Interactiveauthcontainer** - Koji tip upita je prikazan

  - **Issilent** - Da li je upit prikazan

  - **Microsoft**\_**ADAL**\_**adal**\_**version** - Verzija biblioteke potvrde identiteta usluge Azure Active Directory (ADAL)

  - **Microsoft\_ADAL\_api\_error\_code** - Kôd greške kod pokušaja potvrde identiteta koji emituje biblioteka potvrde identiteta

  - **Microsoft\_ADAL\_api\_id** - API aktivacija za ovaj pokušaj potvrde identiteta

  - **Microsoft\_ADAL\_authority** - URL autoriteta usluge Azure Active Directory koji je odgovoran za potvrdu identiteta korisnika

  - **Microsoft\_ADAL\_authority\_type** - Potrošač / ugovor o pružanju Microsoft usluga (MSA) naspram organizacije / Azure Active Directory (AAD), trenutno uvek AAD

  - **Microsoft\_ADAL\_authority\_validation\_status** - Pokazuje da li je potvrda identiteta završena na strani usluge

  - **Microsoft\_ADAL\_broker\_app** - Pokazuje da li je ADAL koristio posrednika za potvrdu identiteta

  - **Microsoft\_ADAL\_broker\_app\_used** – Prikazuje ime posrednika (npr. Windows Account Management)

  - **Microsoft\_ADAL\_broker\_version** - Prikazuje verziju posrednika ako je korišćen

  - **Microsoft\_ADAL\_cache\_event\_count** - Broj keš događaja koje je ADAL izvršio prilikom preuzimanja tokena

  - **Microsoft\_ADAL\_cache\_event\_count\_max** - Ako je signal prikupljen, prikazuje maksimalan broj keš događaja u bilo kom skupu događaja.

  - **Microsoft\_ADAL\_cache\_event\_count\_min** - Ako je signal prikupljen, prikazuje minimalan broj keš događaja u bilo kom skupu događaja

  - **Microsoft\_ADAL\_cache\_event\_count\_sum** - Ako je signal prikupljen, prikazuje zbir keš događaja iz svih skupova događaja

  - **Microsoft\_ADAL\_cache\_read\_count** - Koliko puta je API čitao keš diska. Prisutno je ako postoji makar jedno očitavanje.

  - **Microsoft\_ADAL\_cache\_read\_error\_count** - Koliko puta je čitanje keš diska bilo neuspešno Prisutno je ako postoji makar jedan neuspeh. 

  - **Microsoft\_ADAL\_cache\_read\_last\_error** - Kôd greške ADAL. Prisutan je ako postoji makar jedan neuspeh u očitavanju.

  - **Microsoft\_ADAL\_cache\_read\_last\_system\_error** - Kôd sistemske greške. Prisutan je ako postoji makar jedan neuspeh u očitavanju.

  - **Microsoft\_ADAL\_cache\_write\_count** - Koliko puta je API pisao na keš disku. Prisutno je ako postoji makar jedno pisanje.

  - **Microsoft\_ADAL\_cache\_write\_error\_count** - Koliko puta je pisanje na keš disku bilo neuspešno Prisutno je ako postoji makar jedan neuspeh. 

  - **Microsoft\_ADAL\_cache\_write\_last\_error** - Kôd greške ADAL. Prisutan je ako postoji makar jedan neuspeh u pisanju.

  - **Microsoft\_ADAL\_cache\_write\_last\_system\_error** - Kôd sistemske greške. Prisutan je ako postoji makar jedan neuspeh u pisanju.

  - **Microsoft\_ADAL\_client\_id** - Heš ID aplikacije AAD

  - **Microsoft\_ADAL\_extended\_expires\_on\_setting** - Obaveštenje u obliku tačno/netačno koje prikazuje da li token ima produženo trajanje.

  - **Microsoft\_ADAL\_http\_event\_coun** t - Broj HTTP poziva koje je uputio ADAL

  - **Microsoft\_ADAL\_http\_event\_count\_max** - Ako je signal prikupljen, prikazuje maksimalan broj HTTP poziva koje je uputio ADAL u bilo kom skupu događaja. 

  - **Microsoft\_ADAL\_http\_event\_count\_min** - Ako je signal prikupljen, prikazuje minimalan broj HTTP poziva koje je uputio ADAL u bilo kom skupu događaja.

  - **Microsoft\_ADAL\_http\_event\_count\_sum** - Ako je signal prikupljen, prikazuje zbir HTTP poziva koje je uputio ADAL iz svih skupova događaja.

  - **Microsoft\_ADAL\_is\_silent\_ui** - Obaveštenje u obliku tačno/netačno koje ukazuje na to da li je ADAL prikazao korisnički interfejs (upit). 

  - **Microsoft\_ADAL\_is\_successful** - Obaveštenje u obliku tačno/netačno koje ukazuje na to da li je ADAL API uspešan.

  - **Microsoft\_ADAL\_logging\_pii\_enabled** - Obaveštenje u obliku tačno/netačno koje ukazuje na to da li je omogućen ADAL režim potpunog evidentiranja. Ovi podaci se evidentiraju lokalno, ne emituju se telemetrijski.

  - **Microsoft\_ADAL\_oauth\_error\_code** – Kôd greške protokola OAuth koji je vratila usluga.

  - **Microsoft\_ADAL\_prompt\_behavior** - Prijavljivanje ili nijedan od HTTP parametara nije prosleđeno da bi se odredilo da li korisnički interfejs može da bude prikazan.

  - **Microsoft\_ADAL\_request\_id** - Transakcioni GUID za zahtev koji ADAL emituje usluzi.

  - **Microsoft\_ADAL\_response\_code** - HTTP kôd odgovora od usluge.

  - **Microsoft\_ADAL\_response\_time** - Koliko vremena je bilo potrebno da se usluga vrati na ADAL.

  - **Microsoft\_ADAL\_response\_time\_max** - Ako je signal prikupljen, prikazuje maksimalno vreme iz bilo kog skupa događaja koje je bilo potrebno da se ADAL vrati iz svoje API.

  - **Microsoft\_ADAL\_response\_time\_min** - Ako je signal prikupljen, prikazuje minimalno vreme iz bilo kog skupa događaja koje je bilo potrebno da usluga odgovori ADAL-u.

  - **Microsoft\_ADAL\_response\_time\_sum** - Ako je signal prikupljen, prikazuje zbir vremena iz svih skupova događaja koje je bilo potrebno da se ADAL vrati iz svoje API.

  - **Microsoft\_ADAL\_rt\_age** - Rok trajanja tokena za osvežavanje

  - **Microsoft\_ADAL\_server\_error\_code** - Kôd greške koji je vratio server

  - **Microsoft\_ADAL\_server\_sub\_error\_code** - Kôd podgreške koji je vratio server da bi se razjasnilo zašto zahtev nije uspeo.

  - **Microsoft\_ADAL\_spe\_ring** - Objašnjenje u obliku tačno/netačno koje ukazuje na to da li je korisnik koristio Secure Production Enterprise (samo za zasposlene u korporaciji Microsoft).

  - **Microsoft\_ADAL\_start\_time** - Vreme kada je upućen poziv ADAL API

  - **Microsoft\_ADAL\_stop\_time** - Vreme kada je vraćen poziv ADAL API

  - **Microsoft\_ADAL\_telemetry\_pii\_enabled** - Objašnjenje u obliku tačno/netačno koje ukazuje na to da li je omogućen potpuni telemetrijski ADAL režim. Ime je pogrešno jer se ne emituje PII/EUII.

  - **Microsoft\_ADAL\_tenant\_id** - GUID identifikacija zakupca kojoj autorizovani korisnika pripada.

  - **Microsoft\_ADAL\_token\_acquisition\_from\_context** - Opisuje kako se ponaša ADAL na osnovu tokena iz konteksta potvrde identiteta.

  - **Microsoft\_ADAL\_token\_type** - Ili token za osvežavanje (RT) ili token za osvežavanje različitih resursa (MRRT).

  - **Microsoft\_ADAL\_ui\_event\_count** - Broj upita koji se prikazuju korisniku. Mogu biti i tihi.

  - **Microsoft\_ADAL\_user\_cancel** - Tačno/netačno ako je prozor korisničkog interfejsa otkazan.

  - **Microsoft_ADAL_was_request_throttled** – True / false koji označava da li je ADAL ograničio ovaj događaj zbog previše zahteva.
 
  - **Microsoft\_ADAL\_x\_ms\_request\_id** - Dodatni zahtev koji je obezbedio ID za ADAL uslugu u HTTP zaglavlju.

  - **Platform** - Win32/WinRT/Android/iOS/Mac

  - **Promptreasoncorrelationid** – Za upite, ovo je ID korelacije drugog događaja koji objašnjava zašto korisnik možda vidi upit za potvrdu identiteta.

  - **Resource** – Resurs za koji korisnik zahteva token, kao što su Exchange ili SharePoint.

  - **Scenarioid** - GUID. Različiti događaji mogu da pripadaju samo jednom scenariju, na primer on može da dodaje novi nalog, ali postoji više različitih upita koji se javljaju kao deo tog scenarija. Ovaj ID omogućava da se korelacija dogodi.

  - **Scenarioname** – Ime scenarija kojem pripada ovaj događaj autentifikacije.

  - **Sessionid** - GUID identifikacija za pokretanje sesije

  - **Skdver** - Verzija SDK MATS klijenta koja se koristi za sačinjavanje ovih podataka

  - **Starttime** - Vreme kada je pozvana akcija\*pokretanja MATS API

  - **Tenantid** - GUID identifikacija zakupca kojoj autorizovani korisnika pripada (u slučajevima kada to nije ADAL).

  - **Uploadid** - Jedinstveni GUID za ovaj događaj koji se koristi za uklanjanje duplikata

  - **Wamapi** - Određuje koji je WAM API pozvan

  - **Wamtelemetrybatch** - Trenutno nekorišćeno. U budućnosti će omogućiti WAM komponenti da odašilje dodatne informacije koje se tiču događaja potvrde identiteta.


### <a name="officematsoneauthactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.ActionMicrosoftOfficeWin32

Microsoft Auth Telemetry System (MATS) se prikuplja kada Office pokuša da preuzme token potvrde identiteta, ili tiho ili putem upita. Kada pokušaj preuzimanja ne uspe, šalju se i informacije o grešci. Ovi događaji pomažu korisnicima da izbegnu unošenje neispravne identifikacije tako što će:

1) Utvrditi mogu li klijenti uspešno da nabave token za potvrdu identiteta iz usluge ili su prešli u stanje neispravne potvrde identiteta.

2) Proceniti da li su promene koje su se desile u klijentu ili uslugama dovele do kritičnih regresija u korisničkom iskustvu potvrde identiteta i pouzdanosti.

3) Kada dođe do greške, ovi signali emituju bitne kodove grešaka odgovornih komponenata (kôd Office klijenta, biblioteke potvrde identiteta, upravne usluge) i mogu se koristiti za trijažu, dijagnozu i ublažavanje.

4) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka.

Prikupljaju se sledeća polja:

- **Accounttype** – vrsta naloga koji se koristi za taj događaj potvrde identiteta, na primer, potrošački ili organizacijski.

- **ActionName** – neslužbeni naziv za taj događaj, ako je naveden.

- **Actiontype** – određuje vrstu korišćene biblioteke za potvrdu identiteta.

- **Appaudience** - da li je aplikacija napravljena za internu ili spoljnu upotrebu

- **Appforcedprompt** - da li aplikacija poništava keš i nameće pojavljivanje upita

- **Appname** - ime aplikacije koja potvrđuje identitet

- **Appver** - verzija aplikacije koja potvrđuje identitet

- **Askedforcreds** - da li aplikacija traži od korisnika da unese akreditive za ovu radnju

- **Authoutcome** - da li je pokušaj potvrde identiteta uspešan, neuspešan ili otkazan.

- **Blockingprompt** - da li aplikacija izbacuje upit koji zahteva interakciju korisnika

- **Correlationid** – identifikator koji se upotrebljava za spajanje podataka o ovom pojedinačnom događaju sa servisnim podacima

- **Count** – ukupan broj grupisanih radnji prijavljenih u ovom jednom događaju podataka.

- **Devicenetworkstate** – označava je li uređaj povezan s internetom.

- **Deviceprofiletelemetryid** – anonimni ID uređaja koji se koristi za merenje iskustva autentičnosti i pouzdanosti uređaja.

- **Duration** - Koliko vremena je bilo potrebno za potvrdu identiteta

- **duration_max** – maksimalno trajanje bilo kojeg od grupisanih događaja

- **duration_min** – min trajanje bilo kojeg od grupisanih događaja

- **duration_sum** – zbir trajanja svih grupisanih događaja

- **endtime** – vreme završetka događaja potvrde identiteta

- **error** – kôd greške ako potvrda identiteta nije uspela

- **errordescription** – kratak opis greške

- **errorsource** – da li je došlo do greške u usluzi, biblioteci potvrde identiteta ili aplikaciji

- **eventtype** – izveštava li ovaj događaja o tački podataka potvrde identiteta ili događaju greške kvaliteta podataka. Koristi se za merenje kvaliteta podataka.

- **from_cache** – Bulov izraz koji predstavlja je li zapis iz keš memorije jezgra WAM-a ili dodatak

- **hasadaltelemetry** – označava da li je Azure Active Directory biblioteka potvrde identiteta (ADAL) obezbedila telemetriju za ovaj događaj.

- **Identityservice** - Da li je aktiviran nalog Microsoft usluge (MSA) ili usluge Azure Active Directory (AAD)

- **Interactiveauthcontainer** - Koji tip upita je prikazan

- **Issilent** – označava je li prikazan upit ili je to bio tihi (pozadinski) događaj potvrde identiteta.

- **Microsoft_ADAL_adal_version** – verzija biblioteke Azure Active Directory Authentication Library (ADAL)

- **Microsoft_ADAL_api_error_code** – šifra greške koju je biblioteka za potvrdu identiteta poslala za ovaj pokušaj potvrde identiteta

- **Microsoft_ADAL_api_id** – API koji je pozvan za taj pokušaj potvrde identiteta

- **Microsoft_ADAL_application_name** – naziv aplikacije/procesa koji koristi ADAL.

- **Microsoft_ADAL_application_version** – verzija aplikacije koja koristi ADAL.

- **Microsoft_ADAL_authority** – URL izdavaoca certifikata za Azure Active Directory koji je odgovoran za potvrdu identiteta korisnika

- **Microsoft_ADAL_authority_type** – potrošački / Microsoft ugovor o usluzi (MSA) ili organizacijski / Azure Active Directory (AAD); trenutno uvek AAD

- **Microsoft_ADAL_authority_validation_status**– označava da li je potvrda identiteta sprovedena na strani usluge

- **Microsoft_ADAL_broker_app** – označava da li je ADAL koriš'en kao posrednik za proveru identiteta

- **Microsoft_ADAL_broker_app_used** – označava naziv posrednika (npr. Windows Account Management)

- **Microsoft_ADAL_broker_version** – označava verziju posrednika ako se koristi

- **Microsoft_ADAL_cache_event_count** – broj događaja keš memorije koje je ADAL sproveo tokom preuzimanja tokena

- **Microsoft_ADAL_cache_event_count_max** – ako je signal grupni, označava maksimalni broj događaja keš memorije za bilo koji grupni događaj

- **Microsoft_ADAL_cache_event_count_min** – ako je signal grupni, označava minimalni broj događaja keš memorije za bilo koji grupni događaj

- **Microsoft_ADAL_cache_event_count_sum** – ako je signal grupni, označava zbir događaja keš memorije svih grupnih događaja

- **Microsoft_ADAL_cache_read_count** – označava koliko je puta API čitao iz keš memorije diska. Postoji ako je došlo barem do jednog čitanja

- **Microsoft_ADAL_cache_read_error_count** – predstavlja broj neuspešnih čitanja iz keš memorije diska. Postoji ako je barem jedno bilo neuspešno

- **Microsoft_ADAL_cache_read_last_error** – ADAL šifra greške. Postoji ako čitanje barem jednom nije uspelo

- **Microsoft_ADAL_cache_read_last_system_error** – šifra greške sistema.  Postoji ako čitanje barem jednom nije uspelo

- **Microsoft_ADAL_cache_write_count** – označava koliko je puta API pisao u keš memoriju diska. Postoji ako je došlo barem do jednog pisanja

- **Microsoft_ADAL_cache_write_error_count** – predstavlja broj neuspešnih pisanja u keš memoriju diska. Postoji ako je barem jednom bilo neuspešno

- **Microsoft_ADAL_cache_write_last_error**– ADAL šifra greške. Postoji ako pisanje barem jednom nije uspelo

- **Microsoft_ADAL_cache_write_last_system_error** – šifra greške sistema. Postoji ako pisanje barem jednom nije uspelo

- **Microsoft_ADAL_client_id** – raspršeni ID aplikacije usluge Azure Active Directory

- **Microsoft_ADAL_device_id** – ID lokalnog uređaja koji generiše ADAL.

- **Microsoft_ADAL_error_domain** – domen/komponenta koja je generisala šifru greške.

- **Microsoft_ADAL_error_protocol_code** – šifra greške protokola OAuth koju je vratila usluga, snimio ADAL.

- **Microsoft_ADAL_extended_expires_on_setting** – vrednost true/false koja označava ima li token produžen životni vek

- **Microsoft_ADAL_http_event_count** – broj HTTP zahteva koje generiše ADAL.

- **Microsoft_ADAL_idp** – Dobavljač identiteta (IDP) koji koristi ADAL.

- **Microsoft_ADAL_network_event_count** – broj mrežnih poziva koje je uputio ADAL

- **Microsoft_ADAL_http_event_count_max** – ako je taj signal grupni, označava maksimalni broj http poziva koje je uputio ADAL

- **Microsoft_ADAL_http_event_count_min** – ako je taj signal grupni, označava minimalni broj http poziva koje je uputio ADAL

- **Microsoft_ADAL_http_event_count_sum** – ako je taj signal grupni, označava zbir poziva koje je uputio ADAL

- **Microsoft_ADAL_network_event_count_max** – ako je taj signal grupni, označava maksimalni broj mrežnih poziva koje je ADAL uputio za bilo koji grupni događaj

- **Microsoft_ADAL_network_event_count_min** – ako je taj signal grupni, označava minimalni broj mrežnih poziva koje je ADAL uputio za bilo koji grupni događaj

- **Microsoft_ADAL_network_event_count_sum** – ako je taj signal grupni, označava zbir mrežnih poziva koje je ADAL uputio za bilo koji grupni događaj

- **Microsoft_ADAL_is_silent_ui** – vrednost true/false koja označava je li ADAL prikazao korisnički interfejs (upit)

- **Microsoft_ADAL_is_successfull** – vrednost true/false koja označava je li API ADAL-a uspeo (macOS)

- **Microsoft_ADAL_is_successful** – vrednost true/false koja označava je li API ADAL-a uspeo

- **Microsoft_ADAL_logging_pii_enabled** – vrednost true/false koja označava je li omogućen način rada za potpuno zapisivanje za ADAL. Ti se podaci beleže samo lokalno i ne šalju se u telemetriju

- **Microsoft_ADAL_ntlm** – vrednost true/false koja označava je li ADAL upotrebio osnovnu aut. (NTLM).

- **Microsoft_ADAL_oauth_error_code** – šifra greške protokola OAuth koju je vratila usluga

- **Microsoft_ADAL_prompt_behavior** – prijava ili parametar koji nije mrežni prosleđen usluzi kojim se određuje može li se prikazati korisnički interfejs

- **Microsoft_ADAL_request_id** – transakcijski GUID za zahtev koji je ADAL poslao usluzi

- **Microsoft_ADAL_response_code** – kôd mrežnog odgovora iz usluge

- **Microsoft_ADAL_response_time** – vreme koje je bilo potrebno usluzi da odgovori ADAL-u.

- **Microsoft_ADAL_response_time_max** – ako je signal grupni, maksimalno vreme koje je ADAL-u bilo potrebno da se vrati iz API-ja u bilo kojem od grupnih događaja

- **Microsoft_ADAL_response_time_min** – ako je signal grupni, označava minimalno vreme koje je usluzi bilo potrebno da odgovori ADAL-u u bilo kojem od grupnih događaja

- **Microsoft_ADAL_response_time_sum** – ako je signal grupni, označava zbir vremena koje je ADAL-u bilo potrebno da se vrati iz API-ja za sve skupne događaje.

- **Microsoft_ADAL_rt_age**– starost tokena za osvežavanje

- **Microsoft_ADAL_server_error_code** – šifra greške koju je vratio server

- **Microsoft_ADAL_server_sub_error_code** – podšifra greške koju je server vratio, a služi za utvrđivanje zašto zahtev nije uspeo

- **Microsoft_ADAL_spe_info** – vrednost true/false koja određuje je li korisnik koristio sigurni unutrašnji krug produkcijskog korporacijskog okruženja (samo za Microsoft zaposlene).

- **Microsoft_ADAL_spe_ring** – vrednost true/false koja određuje je li korisnik koristio sigurni unutrašnji krug produkcijskog korporacijskog okruženja (samo za Microsoft zaposlene).

- **Microsoft_ADAL_start_time**– vreme upućivanja poziva ADAL API-ja

- **Microsoft_ADAL_status** – status uspeha/neuspeha celokupnog pozivanja ADAL-a

- **Microsoft_ADAL_stop_time** – vreme uzvraćanja poziva ADAL API-ja

- **Microsoft_ADAL_telemetry_pii_enabled**– vrednost true/false koja označava je li omogućen način rada za potpunu telemetriju za ADAL. Naziv je pogrešan jer se ne šalje PII/EUII

- **Microsoft_ADAL_tenant_id** – GUID koji označava klijenta kojem korisnik proverenog identiteta pripada

- **Microsoft_ADAL_token_acquisition_from_context** – opisuje ponašanje ADAL-a u zavisnosti od tokena u kontekstu potvrde identiteta

- **Microsoft_ADAL_token_frt_status** – status tokena za osvežavanje: je li isproban, nije potreban, nije pronađen ili je izbrisan.

- **Microsoft_ADAL_token_mrrt_status** – status MultiResourceRefreshToken: je li isproban, nije potreban, nije pronađen ili je izbrisan.

- **Microsoft_ADAL_token_rt_status** – status tokena za osvežavanje: je li isproban, nije potreban, nije nađen ili je izbrisan.

- **Microsoft_ADAL_token_type** – token za osvežavanje (RT) ili token za osvežavanje više resursa (MRRT).

- **Microsoft_ADAL_ui_event_count** – broj upita prikazanih korisniku. Mogu biti i u pozadini

- **Microsoft_ADAL_user_cancel** – vrednost true / false koja označava je li prozor korisničkog interfejsa otkazan

- **Microsoft_ADAL_x_ms_request_id** – dodatni ID zahteva koji ADAL navodi u mrežnom zaglavlju za uslugu

- **Microsoft_ADAL_x_client_cpu** – informacije o CPU arhitekturi uređaja

- **Microsoft_ADAL_x_client_os** – verzija OS-a uređaja.

- **Microsoft_ADAL_x_client_sku** – naziv SKU-a OS-a uređaja.

- **Microsoft_ADAL_x_client_ver** – verzija biblioteke ADAL-a.

- **MSAL_all_error_tags** – sve oznake grešaka s kojima se susrela Microsoft Authentication Library (MSAL) za vreme toka potvrde identiteta.

- **MSAL_api_error_code** – ako MSAL naiđe na grešku u OS-u, ovde su uskladištene šifre grešaka platforme.

- **MSAL_api_error_context** – niz koji sadrži dodatne čoveku čitljive pojedinosti o zadnjoj grešci na koju je MSAL naišla. 

- **MSAL_api_error_tag** – jedinstveni niz za mesto u kodu gde se pojavila ta greška.

- **MSAL_api_name** – naziv API-ja MSAL najvišeg nivoa koji je pozvan za pokretanje ovog toka potvrde identiteta.

- **MSAL_api_status_code** – kôd statusa MSAL vraćen je za taj rezultat toka potvrde identiteta.

- **MSAL_auth_flow** – koraci koje je MSAL pokušao za vreme tog toka potvrde identiteta (AT, PRT, LRT, FRT, ART, IRT). Odvojen simbolom uspravne crte "|" za jednostavno raščlanjivanje.

- **MSAL_auth_flow_last_error** – šifra greške koji smo primili sa servera od druge do zadnje stavke u AuthFlowu. (Prim.: If AuthFlow = „PRT|LRT ", greška PRT-a bila bi u AuthFlowLastError).

- **MSAL_authority_type** – označava je li ovaj zahtev za korisnika bio u: AAD, spoljašnji ili MSA.

- **MSAL_broker_app_used** – označava je li u ovom toku potvrde identiteta korišćena aplikacija posrednika.

- **MSAL_client_id** – ID klijenta aplikacije za pozivanje

- **MSAL_correlation_id** – jedinstveni GUID za taj događaj, koji se upotrebljava za pridruživanje radnjama u evidencijama klijenta, servera i aplikacija.

- **MSAL_delete_token** – popis tokena koji su izbrisani iz keš memorije za vreme tog toka potvrde identiteta.

- **MSAL_http_call_count** – broj HTTP poziva koje je MSAL izvršio za vreme toka potvrde identiteta.

- **MSAL_is_successful** – označava je li tok potvrde identiteta bio uspešan.

- **MSAL_last_http_response_code** – ako je MSAL izvršio jedan ili više HTTP poziva, to je zadnji kôd odgovora HTTP-a koji smo primili.

- **MSAL_msal_version** – označava niz verzije MSAL, oblik X. X. X + („OneAuth“, „local" ili izvršite raspršivanje).

- **MSAL_read_token** – tokeni koji su se pročitali iz keš memorije (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT koji je istekao je pročitan, ali odbačen]).

- **MSAL_read_token_last_error** – ako je MSAL naišla na grešku prilikom čitanja keš memorije, ovde ćemo skladištiti informacije. (Primer: greška čitanja diska iz OS-a, Keychain greška na macOS-u).

- **MSAL_request_duration** – označava koliko je zahtevu trebalo vremena od kada je pozvan API najvišeg nivoa MSAL-a do vraćanja rezultata.

- **MSAL_request_id** – ID zahteva za zadnji poziv koji smo uneli u Microsoft uslugu sigurnog tokena.

- **MSAL_server_error_code** – označava numeričku šifru greške Microsoft usluge sigurnog tokena ako smo ga primili.

- **MSAL_server_spe_ring** – informacije o krugu produkcijskog korporacijskog okruženja Microsoft servisa sigurnog tokena, ako smo ga primili.

- **MSAL_server_suberror_code** – niz podšifre greške Microsoft usluge sigurnog tokena, ako smo je primili.

- **MSAL_start_time** – označava vreme pokretanja zahteva MSALA-a na javnom API-ju najvišeg nivoa.

- **MSAL_stop_time** označava vreme u kojem je MSAL dovršila obradu zahteva i vratila rezultat pozivaocu.

- **MSAL_tenant_id** – označava Microsoft GUID koji prepoznaje klijenta u kojem postoji korisnik.

- **MSAL_ui_event_count** – označava broj upita korisničkog interfejsa MSAL-a prikazan na ekranu.

- **MSAL_wam_telemetry** – sadrži skup WAM telemetrijskih podataka u nizu JSON koji će se raščlaniti i pretvoriti u polja u ovom dokumentu koja potiču iz WAM-a.

- **MSAL_was_request_throttled** – tačno ako je MSAL ograničila ovaj zahtev i sprečila ga da napadne mrežu. Ako je ovo ikad tačno, u aplikaciji za pozivanje najverovatnije se nalazi petlja.

- **MSAL_write_token** – tokeni koji su pisani u keš memoriji (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT koji je istekao je pročitan, ali odbačen]).

- **MSAL_read_token_last_error** – ako je MSAL naišla na grešku prilikom pisanja u keš memoriju, ovde ćemo skladištiti informacije. (Primer: greška čitanja diska iz OS-a, Keychain greška na macOS-u).

- **oneauth_api** – API za OneAuth koji je pozvan za taj pokušaj potvrde identiteta.

- **oneauth_transactionuploadid** – GUID koji određuje pojedinačni poziv API-ja za OneAuth.

- **oneauth_version** – verzija SDK-a za OneAuth.

- **Platform** – označava platformu OS-a (0: Windows Desktop; 1: Android; 2: iOS; 3: MacOS; 4: UWP)

- **Promptreasoncorrelationid** – označava identifikator korelacije koji se može upotrebljavati za traženje prethodnog događaja potvrde identiteta, koji se upotrebljava za objašnjenje zašto je korisnik zatražio potvrdu identiteta.

- **Resource** – označava resurs za koji se traži token.

- **Scenarioid** – Veći broj događaja može pripadati jednom scenariju, npr. scenarij možda dodaje novi nalog, ali u sklopu tog scenarija postoji više upita. Ovaj identifikator omogućuje korelaciju tih povezanih događaja.

- **Scenarioname** – označava naziv scenarija aplikacije u kojem je bila potrebna potvrda identiteta, na primer prvo pokretanje, provera licenciranja, itd.

- **Scope** – označava opseg pretraživanja za koji se traži token.

- **Sdkver** – označava verziju biblioteke Microsoft Auth Telemetry System koja se upotrebljava za izradu tih podataka

- **SessionId** – označava identifikator sesije pokretanja

- **Starttime** – vreme kada je započeo događaj potvrde identiteta.

- **Tenantid** – GUID koji označava klijent kojem korisnik proverene autentičnosti pripada (u slučajevima koji nisu ADAL)

- **Uploadid** – Jedinstveni GUID za ovaj događaj koji se koristi za uklanjanje duplikata

- **wamapi** – određuje koji će se API za Windows Web Account Management (WAM) pozvati

- **wamtelemetrybatch** – trenutno se ne koristi. Ubuduće će komponenti WAM omogućiti slanje dodatnih informacija o događaju potvrde identiteta

- **WAM_account_join_on_end** – stanje pridruživanja naloga na kraju operacije WAM.  Moguće vrednosti: „primary", „secondary“, „not_joined"

- **WAM_account_join_on_start** – stanje pridruživanja naloga na početku operacije WAM.  Moguće vrednosti: „primary", „secondary“, „not_joined"

- **WAM_api_error_code** – ako je došlo do odgovora na grešku iz dodatka AAD WAM, to će polje postojati i sadržaće tu šifru greške

- **WAM_authority** – niz koji sadrži URL autoriteta – to bi trebalo da bude login.windows.net korišćena kranja tačka

- **WAM_broker_version** – prisutno kada se upotrebljava WAM, ovo je niz verzije posrednika

- **WAM_cache_event_count** – označava broj događaja keš memorije u WAM-u unutar operacije

- **WAM_client_id** – identifikator za pridruživanje sa podacima usluge, time se označava klijentska aplikacija.

- **WAM_correlation_id** – identifikator za pridruživanje događajima sa podacima usluge

- **WAM_device_join** – označava stanje pridruživanja uređaja; moguće vrednosti su „aadj", „haadj"

- **WAM_network_event_count** – prisutno ako se dogodio najmanje jedan mrežni poziv; broj mrežnih poziva na uslugu za tu operaciju WAM

- **WAM_network_status** – prisutno ako se dogodio najmanje jedan mrežni poziv, sadrži šifru greške HTTP-a ako mrežni zahtev nije uspeo.

- **WAM_idp** – određuje je li korišćen WAM potrošački ili organizacijski dodatak za potvrdu identiteta.

- **WAM_is_cached** – određuje je li odgovor koji je pružio WAM preuzet iz keš memorije.

- **WAM_oauth_error_code** – sadrži šifru greške koju je usluga vratila kao deo protokola oauth.

- **WAM_prompt_behavior** – određuje je li ovaj upit zatražila aplikacija, ili, može li ovaj zahtev preskočiti pitanja ako može neprimetno potvrditi identitet.

- **WAM_provider_id** – Određuje Microsoftu krajnju tačku za ustanovu koja se koristi za scenarij potvrde identiteta.

- **WAM_redirect_uri** – URI za preusmeravanje registrovan za aplikaciju u usluzi Azure Active Directory.

- **WAM_resource** – označava resurs za koji se traži token.

- **WAM_server_error_code** – šifra greške koju je usluga vratila u WAM.

- **WAM_server_sub_code** – dodatna šifra greške koja se upotrebljava za daljnje razbijanje uzroka kvara koji je vratila usluga.

- **WAM_silent_code** – šifra greške koja je naišla na tihi interni pokušaj WAM-a, pre nego što pošalje upit korisniku.

- **WAM_silent_mats** – označava neiskorišćeno.

- **WAM_silent_message** – označava poruku o grešci povezanu sa unutrašnjim tihim pokušajima WAM-a, pre nego što pošalje upit korisniku.

- **WAM_silent_status** – označava status uspeha/neuspeha za tihi interni pokušaj WAM-a, pre nego što pošalje upit korisniku.

- **WAM_tenant_id** – identifikator za klijenta kojem pripada korisnik proverene AAD autentičnosti, ako ga vraća usluga

- **WAM_ui_visible** – prisutno ako je korisniku prikazan najmanje jedan prozor korisničkog interfejsa, bilo ‘true’ ili ‘false’

- **WAM_x_ms_clitelem** – prisutno ako usluga vrati zaglavlje “x-ms-clitelem"


### <a name="officematsoneauthtransactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.TransactionMicrosoftOfficeWin32

Microsoft Auth Telemetry System (MATS) se prikuplja kada Office pokuša da preuzme token potvrde identiteta, ili tiho ili putem upita. Ovaj je događaj nadređen jednom ili više ActionMicrosoftOffice događaja, što omogućava grupisanje povezanih događaja. Ovi događaji pomažu korisnicima da izbegnu unošenje neispravne identifikacije tako što će:

1) Utvrditi mogu li klijenti uspešno da nabave token za potvrdu identiteta iz usluge ili su prešli u stanje neispravne potvrde identiteta.

2) Proceniti da li su promene koje su se desile u klijentu ili uslugama dovele do kritičnih regresija u korisničkom iskustvu potvrde identiteta i pouzdanosti.

3) Kada dođe do greške, ovi signali emituju bitne kodove grešaka odgovornih komponenata (kôd Office klijenta, biblioteke potvrde identiteta, upravne usluge) i mogu se koristiti za trijažu, dijagnozu i ublažavanje.

4) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka.

Prikupljaju se sledeća polja:

- **Actiontype** – „oneauthtransaction" je jedina vrednost.

- **Appaudience** –označava ciljnu skupinu aplikacije (automatizacija, pred proizvodnja ili proizvodnja)

- **Appname** – označava naziv aplikacije

- **Appver**– označava verziju aplikacije

- **Authoutcome** - da li je pokušaj potvrde identiteta uspešan, neuspešan ili otkazan.

- **Correlationid** – identifikator koji se upotrebljava za spajanje podataka o ovom pojedinačnom događaju sa servisnim podacima

- **Count** – označava koliko je puta došlo do greške

- **Devicenetworkstate** – stanje mreže uređaja

- **Deviceprofilatelemetryid** – ID telemetrije profila uređaja (niz koji koristi MATS za određivanje određenog uređaja)

- **duration_max** – označava minimalno trajanje, u milisekundama, transakcija koje se skupljaju na tom signalu.

- **duration_min** – označava maksimalno trajanje, u milisekundama, transakcija koje se skupljaju na tom signalu.

- **duration_sum** – označava zbir trajanja transakcija koje se skupljaju na tom signalu u milisekundama.

- **Endtime** – označava vreme u kojem se završila transakcija OneAuth.

- **Error** – OneAuth kôd statusa.

- **Eventtype** – označava vrstu događaja

- **Issilent** – False ako je prikazano korisničko interfejs; true ako je reč o događaju u pozadini.

- **oneauth_Activeflights** - Spisak letova koji su aktivni u sesiji,koriste se za AB testiranje.

- **oneauth_api** – određuje javni API za OneAuth koji je pozvan.

- **oneauth_Domain** – ako je poziv API-ja uzrokovao grešku, to je sistemski domen te greške.

- **oneauth_ErrorCode** – šifra greške koja predstavlja interno stanje greške za OneAuth. Zamenjuje staro polje oneauth_errortag field.

- **oneauth_errortag** – numerički identifikator za red kôda koji je odgovoran za generisanje greške.

- **oneauth_ExecutionFlow** – niz oznaka koje identifikuju put koda koji je preuzeo ovaj API.

- **oneauth_internalerror** – šifra greške koja predstavlja interno stanje greške za OneAuth.

- **oneauth_ServerErrorCode** – greška servera vraćena u OneAuth po završetku tog poziva API-ja, ako se naiđe na nju.

- **oneauth_SystemErrorCode** – sistemska greška vraćena u OneAuth po završetku tog poziva API-ja, ako se naiđe na nju.

- **oneauth_Tag** – oznaka OneAuth koja označava konačno mesto u kodu postignuto na kraju ovog poziva API-ja.

- **oneauth_transactionuploadid** – određuje nasumično generisani interni GUID koji se preslikava na određeno pozivanje OneAuth API-ja.

- **oneauth_version** – verzija SDK-a za OneAuth.

- **Platform** – OS (0: Win32; 1: Android; 2: iOS; 3: MacOS; 4: WinRT

- **Scenarioname** – naziv scenarija za koji je potrebna potvrda identiteta, a određuje ga aplikacija za pozivanje.

- **Schemaver**– označava verziju šeme

- **Sdkver** – označava verziju SDK-a MATS-a

- **Sessionid** – označava ID sesije

- **severityError** – označava ozbiljnost

- **startime** – označava vreme u kojem je započela transakcija OneAuth.

- **Timestamp** – označava vremensku oznaku

- **Type** – označava vrstu greške

- **Uploaded** – Jedinstveni identifikator za ovaj određeni događaj, u svrhe uklanjanja duplikata.


### <a name="onenotesigninssoexternalappsaccountfound"></a>OneNote.SignIn.SSOExternalAppsAccountFound
 
Ovaj događaj se evidentira kada se na listi naloga, koju obezbeđuje TokenSharingManager, nalazi nalog sa važećim tokenom osvežavanja.Ovaj slučaj je specifičan za jedinstveno prijavljivanje (SSO).
 
Prikupljaju se sledeća polja:
 
- **AccountType** - Evidentira tip naloga

- **ProviderPackageID** - Evidentira ID paketa aplikacije koji je obezbedio ovaj nalog

### <a name="onenotesigninssoexternalappsinvalidaccount"></a>OneNote.SignIn.SSOExternalAppsInvalidAccount

Ovaj događaj se evidentira kada dođe do greške prilikom pokušaja pribavljanja tokena osvežavanja za nalog sa liste naloga koju obezbeđuje TokenSharingManager. Ovaj slučaj je specifičan za jedinstveno prijavljivanje (SSO)
 
Prikupljaju se sledeća polja:
 
- **RawError** - Evidentira neobrađenu grešku dobijenu prilikom pokušaja pribavljanja tokena osvežavanja za dati nalog

### <a name="onenotestickynotesfetchtokencompleted"></a>OneNote.StickyNotes.FetchTokenCompleted
 
Ovaj događaj se evidentira nakon potvrde identiteta, kada je preuzimanje tokena osvežavanja završeno.
 
Prikupljaju se sledeća polja:
 
- **ErrorMessage** - Evidentira poruku o grešci ako preuzimanje tokena nije uspelo 

- **Result** - Evidentira rezultat pokušaja preuzimanja tokena

- **StickyNoteAccountType** - Evidentira tip naloga za koji je aplikacija pokušala da preuzme token osvežavanja


## <a name="click-to-run-events"></a>Događaji „Klikni i pokreni“

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

Podešavanje sistema Office i prikupljanje podataka o zalihama kada korisnik pokreće Office setup.exe da bi izmenio svoje instalirane Office proizvode. Koristi se za merenje uspeha / neuspeha instalacije sistema Office koju je u potpunosti započeo korisnik, uključujući i preduslovne provere.

Prikupljaju se sledeća polja:

  - **Data\_BootStrapperStateFailure\_ErrorCode** - Kôd greške koji nismo uspeli da sredimo

  - **Data\_BootStrapperStateFailure\_ErrorSource** - Funkcija koju nismo uspeli da sredimo

  - **Data\_BootStrapperStateFailure\_FailingState** - Deo koji nismo uspeli da sredimo u boostrapperbootstrapper-u

  - **Data\_BootStrapperStateFailure\_OExceptionType** - Vrsta izuzetka koji nismo uspeli da sredimo

  - **Data\_Culture** - Jezičke postavke kojima pokrećemo exe datoteku, npr. en-us

  - **Data\_HashedOLSToken** - sha-256 heš tokena koji nam daje OLS usluga

  - **Data\_Platfom** - x64 ili x86 instalacija

  - **Data\_PrereqFailure\_Type** - Neuspeli preduslov na koji smo naišli, npr. operativni sistem nije podržan

  - **Data\_ProductReleaseId** – Proizvod koji instaliramo, tj. Microsoft 365 Apps za preduzeće

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ pokreće proveru oštećenja da bi proverio da li su Office binarne datoteke ispravne. Koristi se za merenje oštećenja binarnih datoteka sistema Office i određivanje binarnih datoteka koje su oštećene.

Prikupljaju se sledeća polja:

  - **Data\_Active –** Manifest trenutnog protoka koji proveravamo na disku

  - **Data\_ActivePackages -** koje pakete sadrži manifest

  - **Data\_ActiveVersion -** verzija manifesta

  - **Data\_AddFileCount –** koliko datoteka dodajemo

  - **Data\_AddFileFiles –** uzorak datoteka koje dodajemo

  - **Data\_CompressionLevel -** kako su datoteke kompresovane

  - **Data\_CorruptionCheckLevel –** koliko detaljno proveravamo oštećenja, faze

  - **Data\_CorruptSizeCount -** koliko datoteka je oštećeno

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje su oštećene

  - **Data\_CorruptSizeCount -** koliko datoteka ima oštećenu verziju

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje imaju oštećenu verziju

  - **Data\_FileBadDigestCount -** koliko datoteka nismo uspeli da otvorimo

  - **Data\_FileBadDigestFiles -** uzorak datoteka koje nismo mogli da otvorimo

  - **Data\_FileNotSignedCount –** datoteke koje nisu potpisane

  - **Data\_FileNotSignedFiles –** uzorak datoteka koje nisu potpisane

  - **Data\_FileNotTrustedCount –** koliko datoteka nije pouzdano

  - **Data\_FileNotTrustedFiles –** uzorak datoteka koje nisu pouzdane

  - **Data\_IncompleteFileCount -** koliko datoteka izgleda nepotpuno

  - **Data\_IncompleteFileFiles -** uzorak datoteka koje su nepotpune

  - **Data\_KeepFileCount –** koliko datoteka ne koristimo

  - **Data\_KeepFileFiles –** uzorak datoteka koje čuvamo

  - **Data\_KeepIncompleteFileCount –** koliko datoteka ne menjamo iako su nepotpune

  - **Data\_KeepIncompleteFileFiles –** uzorak datoteka koje čuvamo, a koje su nepotpune

  - **Data\_MismatchSizeCount –** koliko ima datoteka čija se veličina ne poklapa sa veličinom našeg manifesta

  - **Data\_MismatchSizeFiles -** uzorak datoteka koje se ne podudaraju u veličini

  - **Data\_MismatchVersionCount -** koliko datoteka ima verziju koja je drugačija od verzije našeg manifesta

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje se ne podudaraju u verzijama

  - **Data\_MissingFileCount -** koliko datoteka nedostaje

  - **Data\_IncompleteFileFiles -** uzorak datoteka koje nedostaju

  - **Data\_NotToBeStreamedFileCount –** koliko datoteka ne strimujemo

  - **Data\_RemoveFileCount –** koliko datoteka uklanjamo

  - **Data\_RemoveFileFiles –** uzorak datoteka koje uklanjamo

  - **Data\_StreamUnitsMismatchCount –** koliko datoteka ima jedinice koje se ne podudaraju sa manifestom

  - **Data\_StreamUnitsMismatchFiles -** uzorak datoteka čije se jedinice ne podudaraju u protoku

  - **Data\_TimeElapsed -** koliko vremena je bilo potrebno za proveru oštećenja

  - **Data\_UpdateFileCount –** koliko datoteka ažuriramo

  - **Data\_UpdateFileFiles –** uzorak datoteka koje dodajemo

  - **Data\_Working –** novi manifest koji proveravamo

  - **Data\_WorkingVersion -** verzija novog manifesta

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

Podešavanje sistema Office i podaci o zalihama koji pružaju neophodne metapodatke za podešavanje i za zalihe, a koristi se za određivanje tačne osnovne instalacije.

Prikupljaju se sledeća polja:

  - **Data\_C2RClientVer** - Verzija OfficeClickToRun.exe koja se nalazi na računaru

  - **Data\_OfficeBitness** - Broj bita na kojima je instaliran Office, x86 ili x64

  - **Data\_OfficeVersion** - Verzija instaliranog Office sistema

  - **Data\_Sku** – SKU koji je instaliran, tj. Microsoft 365 Apps za preduzeće

  - **Data\_SqmMachineID** - Jedinstveni ID računara koji koristi Windows SQM Data\_SusClientID- identifikator ažuriranja za Office na računaru

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

Podešavanje sistema Office i prikupljeni podaci o zalihama kada IT administrator pokreće „Klikni i pokreni“ setup.exe Alatke za primenu programskog paketa Office da bi izmenio instalirane Office proizvode korisnika. Koristi se za merenje uspeha / neuspeha instalacije sistema Office koju je u potpunosti započeo IT administrator, uključujući i preduslovne provere.

Prikupljaju se sledeća polja:

  - **Data\_BootStrapperStateFailure\_ErrorCode-** Kôd greške koji nismo uspeli da sredimo

  - **Data\_BootStrapperStateFailure\_ErrorSource-** Funkcija koju nismo uspeli da sredimo

  - **Data\_BootStrapperStateFailure\_FailingState** - Deo koji nismo uspeli da sredimo u boot-strapper-u

  - **Data\_BootStrapperStateFailure\_OExceptionType-** Vrsta izuzetka koji nismo uspeli da sredimo

  - **Data\_ConfigurationHost-** Host od kog je stigla datoteka configuration.xml

  - **Data\_ConfigurationId-** ID koji dobijamo od datoteke configuration.xml

  - **Data\_ConfigurationSource-** Odakle je stigla datoteka configuration.xml

  - **Data\_Culture-** Jezičke postavke kojima pokrećemo exe datoteku, npr. en-us

  - **Data\_HashedOLSToken-** sha-256 heš tokena koji nam daje OLS usluga

  - **Data\_MigrateArchRequest-** ako premeštamo korisnika sa sistema x86 na sistem x64 i obratno

  - **Data\_MigrateArchRequestValid-** ako smatramo da je zahtev za premeštanje validan

  - **Data\_Platfom-** x64 ili x86 instalacija

  - **Data\_PlatformMigratedFrom-** Početna platforma, npr. x86

  - **Data\_PlatformMigratedTo-** Krajnja platforma, npr. x64

  - **Data\_PrereqFailure\_Type-** Neuspeli preduslov na koji smo naišli

  - **Data\_ProductReleaseId –** Proizvod koji instaliramo, tj. Microsoft 365 Apps za preduzeće

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Izveštaji o statusu novog „Klikni i pokreni“ kanala ažuriranja („Repoman“) i da li uspešno preuzima i primenjuje Office ispravke.

Prikupljaju se sledeća polja:

  - **ApplySucceeded -** Tačno ako je kanal uspešno primenio ažuriranje za Office, netačno ako nije.
  
  - **DownloadSucceeded -** Tačno ako je kanal uspešno preuzeo ažuriranje za Office, netačno ako nije.

  - **ErrorCode -** Kod poslednje greške koja se dogodila u „Klikni i pokreni“ kanalu Repoman.

  - **ErrorDetails -**  Dodatni detalji o poslednjoj grešci koja se dogodila u „Klikni i pokreni“ kanalu Repoman.
 
  - **ErrorMessage -** Poruka o poslednjoj grešci koja se dogodila u „Klikni i pokreni“ kanalu Repoman.

  - **OpenStreamSessionSucceeded -** Tačno ako kanal uspešno kreira sesiju za striming Office ažuriranja, netačno ako je ne kreira.

  - **RepomanErrorMessage -** Poruka o grešci primljena od repoman.dll.
 

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Podaci o podešavanju sistema Office i inventar koji se prikupljaju kada program za instalaciju sistema Office postavlja nove preuzete datoteke. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails -** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Podaci o podešavanju sistema Office i inventar prikupljaju se kada program za instalaciju sistema Office odlučuje koje datoteke treba preuzeti. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage –** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program Office instalira licence i postavke registra. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version –** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails -** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office instalira fontove. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage –** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  –** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office kreira postavke da bi ispravke ispravno funkcionisale. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID ––** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office kreira stavke registratora za Office aplikacije. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Podaci o podešavanju sistema Office i inventar prikupljaju se kada instalacioni program Office završava instalaciju, zakači prečice i kreira konačna podešavanja registra. Koristi se za merenje uspeha / neuspeha instalacije sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  –** koji scenario je pokrenut, npr. instaliranje

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Podaci o podešavanju sistema Office i podaci prikupljeni kada Office Installer migrira postavke iz starijih verzija sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage –** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource – –** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  –** koji scenario je pokrenut, npr. instaliranje

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID –** identifikator ažuriranja za Office na računaru

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Podaci o podešavanju sistema Office i inventar prikupljeni kada Office instalacioni program objavljuje virtuelni registar za sloj virtuelizacije AppV. Koristi se za merenje uspeha / neuspeha instalacije sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Podešavanje sistema Office i prikupljanje podataka o zalihama kada deinstalacioni program za Office uklanja sa uređaja delove sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion–** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office preuzima nove datoteke. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version –** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts  –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office deinstalira prethodnu verziju koja je instalirana iz prodavnice. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office ponovo objavi .msi datoteke i programske dodatke za Office. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion–** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office preuzima najnoviju verziju klijenta „Klikni i pokreni“ da bi pripremio računar za deinstalaciju i ponovnu instalaciju. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office pokuša da popravi neke poznate problematične stavke registratora. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth –** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office ukloni Office sa uređaja tokom popravke da bi ga pripremio za ponovno instaliranje. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Podaci o podešavanju sistema Office i inventar prikupljaju se kada klijent klikni za pokretanje po potrebi ažurira licence. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Podešavanje sistema Office i prikupljanje zaliha kada klijent „Klikni i pokreni“ ažurira postavke registratora za nove binarne datoteke. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ zatvara pokrenute aplikacije po potrebi i instalira nove datoteke koje su preuzete. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion to-** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_CompletedWithoutActionInfo –** Zašto nismo dovršili scenario, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_CorruptionChecksOnly –** Ako samo proveravamo oštećenja, a ne ažuriramo

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_HardlinkingException -** Izuzetak na koji smo naišli dok smo pokušavali da kreiramo čvrste veze

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageOperationSuccessful -** Istinito ako smo uspešno dovršili zadatak sa Office paketom

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID –** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

  - **Data\_WorkstationLockState -** Istinito ako mislimo da je računar zaključan

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ preuzima svoju noviju verziju. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName-** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Podaci o podešavanju sistema Office i inventar prikupljaju se kada klijent klikni za pokretanje proveri da li je dostupno novo ažuriranje. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion -** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_ComAction –** Int koji predstavlja com radnju koju izvršavamo

  - **Data\_CompletedWithoutActionInfo –** Zašto nismo dovršili scenario, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource –** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageUpdateAvailable -** Istinito ako je dostupna nova verzija sistema Office

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID –** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Podaci o podešavanju sistema Office i inventar prikupljeni kada klijent „Klikni i pokreni“ preuzme novu ispravku. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion –** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion -** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_CompletedWithoutActionInfo –** Zašto nismo dovršili scenario, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_CorruptionChecksOnly –** Ako samo proveravamo oštećenja, a ne ažuriramo

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_FoundCorruptFiles -** Istinito ako smo pronašli oštećene datoteke

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageOperationSuccessful -** Istinito ako smo uspešno dovršili zadatak sa Office paketom

  - **Data\_PipelineExitCode -** Izlazni kôd koji je vratio kanal datoteke

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID–** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ obavlja čišćenje nakon ažuriranja i vraća aplikacije koje su prethodno otvorene. Koristi se za merenje uspeha ili neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType –** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled –** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion–** Na koju verziju sistema Office 15 vršimo ažuriranje 

  - **Data\_15\_Version –** Office 15 verzija 

  - **Data\_16\_SourceType –** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled–** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion –** Na koju verziju sistema Office 16 vršimo ažuriranje 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts –** Proizvodi koje dodajemo 

  - **Data\_AddingProducts –** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails–** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd –** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove –** Koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts –** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts –** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID –** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName –** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType –** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType –** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState –** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Izveštava o radnjama preuzimanja datoteka kako bi se odredilo da li je operacija bila uspešna, tipu preuzimanja i dijagnostičkim informacijama.


- **BytesFromGroupPeers –**    Bajtovi ravnopravnih uređaja u grupi, samo za preuzimanja pomoću optimizacije isporučivanja

- **BytesFromHttp –**     Bajtovi http protokola, samo za preuzimanja pomoću optimizacije isporučivanja

- **ByteFromInternetPeers –**    Bajtovi ravnopravnih uređaja na internetu, samo za preuzimanja pomoću optimizacije isporučivanja 

- **BytesFromLanPeers –**    Bajtovi ravnopravnih uređaja na LAN mreži, samo za preuzimanja pomoću optimizacije isporučivanja 

- **canceledJobs -**     Broj otkazanih zahteva u sesiji

- **Connected –**    Pokazuje da li postoji veza sa izvorom

- **ErrorCode –**    Kôd poslednje greške

- **ErrorDetails** – Detalji poslednje greške

- **ErrorMessage** – Poruka poslednje greške 

- **ErrorSource –**    Izvor poslednje greške, na primer, Connection, LoadFile ili LoadRange

- **FailedJob –**    Broj zahteva u sesiji koji nisu uspeli

- **FileSize** – Veličina resursa

- **SourcePathNoFilePath** – Izvorna putanja resursa. Izveštava se samo o http izvoru, a filtrira se putanja do lokalne datoteke ili UNC putanja

- **SucceededJobs –**    Broj uspešnih zahteva u sesiji

- **TotalJobs –**    Ukupan broj zahteva u sesiji

- **TotalRequestedBytes –**    Ukupan broj traženih bajtova u sesiji

- **TotalTransferTime –**    Ukupno vreme prenosa u sesiji

- **TransferredBytes –**    Ukupan broj prenetih bajtova u sesiji

- **TransportType –**    Tip prenosa, na primer (optimizacija isporučivanja u memoriji, HTTP, usluga inteligentnog prenosa u pozadini)



### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ kreira protok za prenos da bi preuzeo Office datoteke. Koristi se za utvrđivanje ispravnosti raznih tehnologija za prenos (npr. HTTP, BITS, DO), što je od presudnog značaja za ispravno preuzimanje instalacije i ažuriranja za sistem Office.

Prikupljaju se sledeća polja:

  - **Data\_IsForeGroundStreaming**– da li emitujemo u prednjem planu ili u pozadini

  - **Data\_IsInstallMode** – 1 ako instaliramo i preuzimamo datoteke, 0 ako to ne radimo

  - **Data\_SourceProtocol –** Ako preuzimamo sa mreže za podatke sadržaja, CDN, sa računara na koji instaliramo, lokalno, ili iz resursa sa lokalne mreže,

  - **Data\_Status**– Uspeh ili neuspeh 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ završava status ažuriranja

Prikupljaju se sledeća polja:

  - **Data\_build** - Trenutno instalirana verzija sistema Office

  - **Data\_channel** – Kanal na kom se nalazi korisnik

  - **Data\_errorCode** – Kôd sa celim brojevima koji određuje tip greške ako je do nje došlo

  - **Data\_errorMessage** – Niska koja opisuje grešku ako je do nje došlo

  - **Data\_status** – Kratki status onoga što se dogodili tokom ažuriranja, kao što je uspešnost ili završeno preuzimanje

  - **Data\_targetBuild -** - Verzija koju pokušavamo da nadogradimo na Office


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Izveštava o rezultatu pokušaja potpunog instaliranja

 - **ErrorCode –**    Vrednost celog broja povezana sa nekontrolisanim izuzetkom

 - **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

 - **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

 - **ErrorType –**    Niska koja opisuje kategoriju nekontrolisanog izuzetka

 - **ExitCode –**    Vrednost celog broja povezana sa rezultatom pokretanja programa koji se pokreće prilikom pokretanja računara koja označava uspeh naspram određenih tipova otkazivanja

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Izveštava o radnji koja donosi programske odluke u vezi sa unosom prikupljenim pomoću događaja CollectParameters

- **BitField –**    Vrednost celog broja argumenta BitField koji pokazuje da li je zatražen eksplicitan kanal instalacije/ažuriranja. Na primer, beta kanal, trenutni kanal (pregled), trenutni kanal, mesečni kanal za preduzeća, polugodišnji kanal za preduzeća (pregled) ili polugodišnji kanal za preduzeća.

- **ChannelID –**    Ceo broj koji predstavlja numeričku vrednost izabranog kanala ažuriranja/instalalcije. Na primer, beta kanal, trenutni kanal (pregled), trenutni kanal, mesečni kanal za preduzeća, polugodišnji kanal za preduzeća (pregled), polugodišnji kanal za preduzeća ili nevažeći.

- **CMDMode –**    Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena je u .exe datoteku.

- **C2RClientUICulture –**    Kultura klijenta za verziju „Klikni i pokreni“ koju treba instalirati

- **ErrorCode –**    Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType –**    Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExcludedApps** – Niska koja navodi imena pojedinačnih Office aplikacija za koje je zatraženo da se isključe iz instaliranih Office programskih paketa

- **InstalledCabVersion –**    Već je instalirana verzija 16.0.xxxxx.yyyyy klijenta za Office „Klikni i pokreni“

- **InstalledProductVersion –**    Već je instalirana verzija 16.0.xxxxx.yyyyy Office „Klikni i pokreni“ proizvoda

- **IsC2RServiceRunning –**    Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za verziju „Klikni i pokreni“ normalno radi na uređaju

- **IsElevatedFlagSet –**    Bulova zastavica koja pokazuje da li je program koji se pokreće prilikom pokretanja računara već pokušao da dobije podizanje na nivo administratora

- **IsFireFlyInstalled –**    Bulova zastavica koja pokazuje da li je trenutno instaliran klijent za Office 2013 RTM C2R

- **IsFireflyServiceRunning –**    Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za 2013 RTM C2R normalno radi na uređaju

- **IsOfficeInstalled –**    Bulova zastavica koja pokazuje da li je već instaliran moderni klijent za Office

- **OfficeCultures –**    Serijalizovana lista Office kultura koje treba instalirati

- **OfficeSourceType** – Prepoznatljiva niska povezana sa numeričkom vrednošću instalacionog izvora (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin –**    Vrednost niske koja saopštava koji od podržanih izvora (Portoriko [PR], Singapur [SG], Dablin [DB]) treba koristiti za početni protok instalacije

- **PlatformFromLink** – Niska koja pokazuje podrazumevani broj bitova x86 | x64 | sistema Office zatražen od usluge podešavanja za verziju „Klikni i pokreni“

- **PlatformOfExistingInstallation –**    Niska koja pokazuje da li je x86-bitna ili x64-bitna verzija sistema Office već instalirana na uređaju

- **PlatformToInstall –**    Niska koja pokazuje konačnu odluku u vezi sa time da li će se instalirati x86-bitna ili x64-bitna verzija sistema Office. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **PRID –**    Vrednost niske koja predstavlja traženi ID izdanja proizvoda u slučaju korisničke instalacije (na primer, „O365ProPlusRetail“)

- **PridsToMigrateFromCentennial –**    Niska Office proizvoda koje treba migrirati iz instalacija prodavnice u uslugu „Klikni i pokreni“

- **ProductsToAdd –**    Serijalizovana niska koja daje uputstva klijentu „Klikni i pokreni“ o tome koje kombinacije proizvoda/kultura treba da instalira

- **ProductsToMigrateFromO15C2R -**  Niska Office proizvoda i jezika koje treba migrirati iz „Klikni i pokreni“ instalacije sistema Office 2013

- **ProductsToRemove** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome koje kombinacije proizvoda/jezika treba da deinstalira

- **SharedComputerLicensing –**    Bulova vrednost koja pokazuje da li je IT administrator zatražio podešavanje kako bi se omogućila funkcija „SharedComputerLicensing“

- **ShouldActivate –**    Bulova vrednost koja pokazuje da li je IT administrator zatražio pokušaj automatskog aktiviranja licenciranja u datoteci configuration.xml

- **ShouldUninstallCentennial -** Bulova zastavica koja pokazuje da li treba deinstalirati Office proizvode iz prodavnice

- **VersionToInstall** – Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Izveštava o radnji koja čita označeni unos iz ugrađenog potpisa izvršne datoteke. Ovo je nedokazani koncept koji prethodna iteracija izvršne datoteke setup.exe nije primenila i to je ono na šta se oslanjamo prilikom prenošenja izbora korisnika u vezi sa proizvodom/jezikom/brojem bitova sa veb stranice u proces unutar izvršne datoteke setup.exe.
 
- **ErrorCode –**    Ceo broj povezan sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType –**    Niska koja opisuje kategoriju nekontrolisanog izuzetka

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Izveštava o parametrima koji se koriste za instaliranje sistema Office

- **BitField –**    Vrednost celog broja argumenta BitField koji pokazuje da li je zatražen eksplicitan kanal instalacije/ažuriranja. Na primer, beta kanal, trenutni kanal (pregled), trenutni kanal, mesečni kanal za preduzeća, polugodišnji kanal za preduzeća (pregled) ili polugodišnji kanal za preduzeća.

- **ChannelID –**    Ceo broj koji predstavlja numeričku vrednost izabranog kanala ažuriranja/instalalcije. Na primer, beta kanal, trenutni kanal (pregled), trenutni kanal, mesečni kanal za preduzeća, polugodišnji kanal za preduzeća (pregled), polugodišnji kanal za preduzeća ili nevažeći.

- **CMDMode –**    Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena je u .exe datoteku. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **C2RClientUICulture –**    Kultura klijenta za verziju „Klikni i pokreni“ koju treba instalirati

- **ErrorCode –**    Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType –**    Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExcludedApps** – Niska koja navodi imena pojedinačnih Office aplikacija za koje je zatraženo da se isključe iz instaliranih Office programskih paketa

- **InstalledCabVersion –**    Već je instalirana verzija 16.0.xxxxx.yyyyy klijenta za Office „Klikni i pokreni“

- **InstalledProductVersion –**    Već je instalirana verzija 16.0.xxxxx.yyyyy Office „Klikni i pokreni“ proizvoda

- **IsC2RServiceRunning –**    Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za verziju „Klikni i pokreni“ normalno radi na uređaju

- **IsElevatedFlagSet –**    Bulova zastavica koja pokazuje da li je program koji se pokreće prilikom pokretanja računara već pokušao da dobije podizanje na nivo administratora

- **IsFireFlyInstalled –**    Bulova zastavica koja pokazuje da li je trenutno instaliran klijent za Office 2013 RTM C2R

- **IsFireflyServiceRunning –**    Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za 2013 RTM C2R normalno radi na uređaju

- **IsOfficeInstalled –**    Bulova zastavica koja pokazuje da li je već instaliran moderni klijent za Office

- **OfficeCultures –**    Serijalizovana lista Office kultura koje treba instalirati

- **OfficeSourceType** – Prepoznatljiva niska povezana sa numeričkom vrednošću instalacionog izvora (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin –**    Vrednost niske koja saopštava koji od podržanih izvora (Portoriko [PR], Singapur [SG], Dablin [DB]) treba koristiti za početni protok instalacije

- **PlatformFromLink** – Niska koja pokazuje podrazumevani broj bitova x86 | x64 | sistema Office zatražen od usluge podešavanja za verziju „Klikni i pokreni“

- **PlatformOfExistingInstallation –**    Niska koja pokazuje da li je x86-bitna ili x64-bitna verzija sistema Office već instalirana na uređaju

- **PlatformToInstall –**    Niska koja pokazuje konačnu odluku u vezi sa time da li će se instalirati x86-bitna ili x64-bitna verzija sistema Office

- **PRID –**    Vrednost niske koja predstavlja traženi ID izdanja proizvoda u slučaju korisničke instalacije (na primer, „O365ProPlusRetail“)

- **PridsToMigrateFromCentennial-** Niska Office proizvoda koje treba migrirati iz instalacija prodavnice u uslugu „Klikni i pokreni“

- **ProductsToAdd –**    Serijalizovana niska koja daje uputstva klijentu „Klikni i pokreni“ o tome koje kombinacije proizvoda/kultura treba da instalira

- **ProductsToMigrateFromO15C2R -** Niska Office proizvoda i jezika koje treba migrirati iz „Klikni i pokreni“ instalacije sistema Office 2013

- **ProductsToRemove** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome koje kombinacije proizvoda/jezika treba da deinstalira

- **SharedComputerLicensing –**    Bulova vrednost koja pokazuje da li je IT administrator zatražio podešavanje kako bi se omogućila funkcija „SharedComputerLicensing“

- **ShouldActivate –**    Bulova vrednost koja pokazuje da li je IT administrator zatražio pokušaj automatskog aktiviranja licenciranja u datoteci configuration.xml

- **ShouldUninstallCentennial -** Bulova zastavica koja pokazuje da li treba deinstalirati Office proizvode iz prodavnice

- **VersionToInstall –**    Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira

### <a name="officeclicktorununiversalbootstrapperexecute"></a>Office.ClickToRun.UniversalBootstrapper.Execute

Izveštava o preduzetim radnjama koje utiču na mašinu, koje su odredili podaci iz događaja „CalculateParameters“ u vezi sa kojima su donete programske odluke

- **AvailableClientVersionText –**    Vrednost niske klijenta za verziju 16.0.xxxxx.yyyyy „Klikni i pokreni“ koja se nalazi u XML datoteci opisa verzije, koja se koristi za određivanje toga da li treba ažurirati trenutno instalirani klijent za verziju „Klikni i pokreni“

- **CleanFireFlyAction –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak CleanFireFlyAction pokrene tokom ovog instaliranja

- **CleanO15Action –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak CleanO15Action pokrene tokom ovog instaliranja

- **CMDMode –**    Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena je u .exe datoteku. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **DeliveryMechanism –**    GUID „FFNRoot“ izdvojen iz XML datoteke opisa verzije (koju je označio RDX) koji saopštava putem kojih je korisnika/kanala dobijen izvor verzije

- **DownloadC2RClientAction –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak DownloadC2RClientAction pokrene tokom ovog instaliranja

- **ErrorCode –**    Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType –**    Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExitCode –**    Vrednost celog broja povezana sa rezultatom pokretanja izvršne faze programa koji se pokreće prilikom pokretanja računara koja označava uspeh naspram određenih tipova otkazivanja

- **LaunchAction –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak LaunchAction pokrene tokom ovog instaliranja

- **LaunchUpdateAction –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak LaunchUpdateAction pokrene tokom ovog instaliranja

- **PreReqResult –**    Numerička vrednost celog broja rezultata izvršavanja provera preduslova (prolaz/neuspeh/ponovno pokretanje)

- **UnexpectedAction –**    Ima vrednost „tačno“ ako je isplanirano da se zadatak UnexpectedAction (slučaj greške) pokrene tokom ovog instaliranja

- **VersionToInstall** – Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira

### <a name="officeserviceabilitymanagerinventoryaddonheartbeat"></a>Office.ServiceabilityManager.InventoryAddon.Heartbeat

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Ovaj se događaj koristi za sticanje standardnih metapodataka pri svakom pokretanju dodatka Inventory, koji je deo usluge Office Serviceabiliti Manager, a koristi se za informacije o Office inventaru na onim mašinama za koje se IT administrator odlučio. Metapodaci od specifičnog interesa ovde su ID sesije i koriste se za povezivanje s drugim podacima pohranjenim u oblačnom servisu korisnika.

Ovaj događaj ne sadrži dodatna polja jer su samo metapodaci relevantni.

### <a name="officeserviceabilitymanagerinventoryaddonresults"></a>Office.ServiceabilityManager.InventoryAddon.Results

Ovaj događaj se evidentira kada se završi poziv upućen funkciji webservice, obavljen u okviru dodatka, Upravljača Servisiranja Inventara „Klikni i pokreni“, bez obzira na to da li je uspešan ili neuspešan. Ovo je u suštini poslednja operacija u okviru dodatka za praćenje celokupnog statusa operacije.

Prikupljaju se sledeća polja:

- **ActionDetail** - Dodatni detalji kada dođe do neuspeha.

- **Result** - Zastavice numeričkog koda greške dobijene iz API-ja za pozivanje Office veb usluge. Na primer, 3 bi značilo da je došlo do problema prilikom pokretanja HTTP zaglavlja.

- **Type** - Dodatne informacije o tipu. U slučaju inventara, ove informacije određuju vrstu korisnog tereta koji se šalje. Na primer, puna ili samo delta promena. 

- **Verzija** - puni četvorodelni broj verzije sistema Office. Na primer, 16.0.10000.10000. (Imajte na umu da se za ove događaje polje standardne verzije popunjava verzijom Windows, jer se ovo izvodi kao deo Windows procesa.)

-  **WebCallSource** - Vrednost nabrajanja (navedena kao ceo broj) koja ukazuje na dodatak Upravljača servisiranja koji je bio izvor poziva.
   

### <a name="officeserviceabilitymanagerwebservicefailure"></a>Office.ServiceabilityManager.WebserviceFailure

Kad god ne uspe poziv upućen veb usluzi u okviru jednog od Office Serviceability Manager programskih dodataka, ova izjava se evidentira. Do neuspeha može da dođe zbog internih grešaka ili nemogućnosti povezivanja sa veb uslugom.

Prikupljaju se sledeća polja:

- **Add-on** - Dodatak „Upravljač servisiranja klikni i pokreni“ u okviru kog je upućen poziv funkciji webservice. Ovo može da ima vrednosti kao što su inventar, mogućnost upravljanja, itd, kodirani kao numeričke vrednosti.

- **Correlation ID** - Nasumično generisan GUID koji je specifičan za trenutnu instancu i koji se šalje funkciji webservice za korelaciju poziva između klijenta i servera.

- **ErrorInfo** - Informacije o numeričkom kodu greške dobijene iz Office webservice API-ja za pozivanje.

- **ErrorMessage** – Poruka koja pruža dodatni uvid u neuspeh. Svaki tip greške mapira se sa fiksno kodiranom niskom, pri čemu se neki tipovi grešaka potencijalno mapiraju sa više niski, u zavisnosti od konkretne prirode neuspeha.

- **Function** - Funkcija u kodu u kojoj je obavljen trenutni poziv.

- **Status** - HTTP statusni kôd dobijen iz poziva upućenog funkciji webservice, npr. 404, 500, itd.


## <a name="enhanced-configuration-service-ecs-events"></a>Događaji usluge poboljšane konfiguracije (ECS)

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Prikuplja informacije o prolazima funkcije / promena čiji je upit poslao izvršeni kôd

Prikupljaju se sledeća polja:

  - **Count** - Broj upita o prolazima funkcije u paketnom događaju

  - **Features** - Informacije o prolazu upita.

  - **Sequence** - Redosled po kojem je izvršen upit o prolazu funkcije

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Prikuplja listu o konfiguracijama koje je primio klijent iz usluge ECS

Prikupljaju se sledeća polja:

  - **ECSConfigs** – Lista konfiguracije ECS odvojena zarezima

  - **LockType** - Tip FlightManager zaključavanja

  - **TasFlightingVersion** - Broj verzija

  - **TimeToLock** - Vreme koje protekne od liblet pokretanja do FlightManager zaključavanja

  - **UnmergedConfigs** - Lista konfiguracija koje nisu objedinjene

### <a name="officeexperimentationtriggeranalysis"></a>Office.Experimentation.TriggerAnalysis

Ovaj događaj pomaže u analizi opsega korištenja proizvoda i metrika performansi (kao što su padovi, prekidi, itd.) podskupa korisnika ili uređaja koji imaju pravo na korišćenje funkcije, i na taj način pomažu u osiguravanju ispravnog rada proizvoda.

Prikupljaju se sledeća polja:

  - **FeatureGate -** Identifikuje skup funkcija za koje je primenjiva analiza okidača.

### <a name="onenoteflightdefault"></a>OneNote.FlightDefault
 
Ovaj događaj se evidentira kada OneNote upita ECS server za vrednosti probnog paketa.  Ovo se koristi za omogućavanje eksperimentalnih funkcija korisnicima koji su izabrali da primaju takve probne pakete.
 
Prikupljaju se sledeća polja:
 
- **ConfigParam** – Konfiguracija zbog koje se pristupa vrednosti

## <a name="licensing-events"></a>Događaji licenciranja

### <a name="officeandroiddocsuipaywallcontrolautoredeempendingpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.AutoRedeemPendingPurchaseResult

Kritična inženjerska telemetrija za beeeženje rezultata automatskog pokušaja iskorišćavanja kupovina na čekanju. Telemetrija proizvoda koja se upotrebljava za usklađivanje podataka o transakcijama kupovine s Microsoft sistemom trgovine radi omogućivanja povezanih pogodnosti pretplate.

Prikupljaju se sledeća polja:

- **EventDate** – vremenska oznaka pojavljivanja događaja 

- **Result** – Int koji označava rezultat nabrajanja operacije. 

- **SessionID** – GUID za povezivanje događaja po sesiji

### <a name="officeandroiddocsuipaywallcontrolpaywalluishown"></a>Office.Android.DocsUI.PaywallControl.PaywallUIShown

Kritična telemetrija korištenja kada se Paywall kontrola prikazuje korisniku. Koristi se za razumevanje iskustva kupovine iz aplikacije i optimizaciju iste u budućim verzijama.

Prikupljaju se sledeća polja:

- **EventDate** – vremenska oznaka pojavljivanja događaja 

- **IsModeFRE** – Bulov izraz za označavanje vrste iskustva, dijaloga prodaje dodatnih opcija ili SKU birača

- **SessionID** – GUID za povezivanje događaja po sesiji

### <a name="officeandroiddocsuipaywallcontrolpurchasebuttonclicked"></a>Office.Android.DocsUI.PaywallControl.PurchaseButtonClicked

Kritična telemetrija upotrebe kako bismo znali kada korisnik klikne na dugme Kupovina. Upotrebljava se za zaključivanje o načinu korišćenja i mernim podacima konverzije za korisnike koji pokušaju da kupe pretplatu u aplikaciji.

Prikupljaju se sledeća polja:

- **EventDate** – vremenska oznaka pojavljivanja događaja

- **Isdefaultsk** – Bulov izraz koji ukazuje na to pokušava li korisnik kupiti SKU koji se prvi pojavio/zadani

- **ProductID** – niz koji prepoznaje korisnika pretplate koji pokušava kupiti kako je konfigurisan u trgovini

- **SessionID** – GUID za povezivanje događaja po sesiji

### <a name="officeandroiddocsuipaywallcontrolpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.PurchaseResult

Kritična inženjerska telemetrija da biste evidentirali rezultat pokušaja kupovine koji korisnik aktivira ručno. Telemetrija proizvoda koja se upotrebljava za usklađivanje podataka o transakcijama kupovine s Microsoft sistemom trgovine radi omogućivanja povezanih pogodnosti pretplate.

Prikupljaju se sledeća polja:

- **EventDate** – vremenska oznaka pojavljivanja događaja 

- **IsModeFre** – Bulov izraz koji ukazuje na to je li kupovina stvorena pomoću ekrana s početnim interfejsom prodaje dodatnih opcija ili SKU birača

- **Result** – Int koji označava rezultat nabrajanja operacije.

- **SessionID** – GUID za povezivanje događaja po sesiji

### <a name="officeandroiddocsuipaywallcontrolpurchasetokenredemptionresponse"></a>Office.Android.DocsUI.PaywallControl.PurchaseTokenRedemptionResponse

*[Ovaj događaj je prethodno imao ime Office.Android.DocsUI.Views.PurchaseTokenRedemptionResponse.]*

Ova telemetrija proizvoda prikuplja se za praćenje i evidentiranje statusa interne transakcije i informacija o usaglašavanju radi poboljšanja pouzdanosti i performansi. Microsoft koristi ove podatke za analizu i poboljšanje pouzdanosti i performansi mehanizama interne obrade transakcija i usaglašavanja.

Prikupljaju se sledeća polja:

- **MicrosoftPurchaseOrderId** – Microsoft ID porudžbine koji šalje usluga maloprodajne službe (RFS) za svrhu praćenja.

- **ResponseCode** – HTTP kôd za odziv (INT)

- **StatusCode** – RFS status statusa odgovora (RFS definisao brojač beskonačan)


### <a name="officeandroiddocsuipaywallcontrolseeallfeaturesanalytics"></a>Office.Android.DocsUI.PaywallControl.SeeAllFeaturesAnalytics

Prikupljamo ovu telemetriju upotrebe kako bismo videli koliko vremena korisnik provodi na ekranu „Pogledajte više pogodnosti“.  Podaci se upotrebljavaju za razumevanje upotrebe funkcije „Pogledajte više pogodnosti“ i daljnju optimizaciju iskustva u budućim verzijama.

Prikupljaju se sledeća polja:

- **Duration** – Dugi ceo broj koji označava vreme koje je korisnik proveo na ekranu „Vidi sve funkcije“ u milisekundama

- **EventDate** – vremenska oznaka pojavljivanja događaja 

- **MostExplored** – Ce broj koji označava indeks stavke s najviše promena na popisu aplikacija Microsoft 365 i njihovih funkcija

- **Sessioid** – globalno jedinstveni identifikator (GUID) za povezivanje događaja po sesiji

### <a name="officeandroiddocsuipaywallcontrolskuchooseranalytics"></a>Office.Android.DocsUI.PaywallControl.SkuChooserAnalytics

Telemetrija upotrebe da biste videli koliko vremena korisnik troši na ekranu SKU birača. Telemetrija upotrebe da biste videli koliko vremena korisnik troši na ekranu SKU birača.

Prikupljaju se sledeća polja:

- **Duration** – Dugi ceo broj koji označava vreme koje je korisnik proveo na ekranu SKU birača u milisekundama

- **EventDate** – vremenska oznaka pojavljivanja događaja

- **SessionID** – GUID za povezivanje događaja po sesiji


### <a name="officeandroiddocsuiviewsdimeerror"></a>Office.Android.DocsUI.Views.DimeError

Ovaj događaj se prikuplja za Office aplikaciju za Android (objavljen u prodavnicama Huawei i u Kini). Taj događaj označava da pokušaj kupovine pretplate na Microsoft 365 putem platforme Dime (webURL učitan u veb prikazu u klijentu) nije uspeo. Snimaju se samo scenariji grešaka. Ti podaci o događajima su samo podaci o greškama, a koriste se za osiguravanje dobrog stanja toka kupovine putem platforme Dime u klijentu.

Prikupljaju se sledeća polja:

- **CorrelationID** – ID koji na jedinstven način identifikuje sesiju kupovine putem platforme Dime.

- **ErrorReason** – označava razlog greške do koje je došlo.
  - 0 – nepoznata greška
  - 1 – internet nije dostupan
  - 2 – nije uspela provera valjanosti univerzalno jedinstvenog identifikatora (UUID)
  - 3 – univerzalno jedinstven identifikator (UUID) null je ili prazan
  - 4 – greška umetanja u JavaScript pri kojoj aplikacija Office za Android ne može da prosledi authToken platformi Dime
  - 5 – osnovni WebURL učitan na klijentu nije važeći


### <a name="officeandroiddocsuiviewspremiumfeatureupsell"></a>Office.Android.DocsUI.Views.PremiumFeatureUpsell

Ovaj događaj beleži klikove besplatnog korisnika kako bi video funkciju iza platnog zida. Podaci se koriste za merenje interakcije korisnika sa kontekstualnim doživljajem prodaje skupih proizvoda i razumevanje funkcija koje korisnik priželjkuje, što ih podstiče da kupe pretplatu. Ovo nam pomaže da investiramo u poboljšanje željenog skupa ulaznih tačaka. 

Prikupljaju se sledeća polja:

- **featureId** – TCID za Premium funkciju

- **featureName** – naslov Premium funkcije

- **seePlanButtonClick** – Koliko puta se klikne na dugme "Pogledajte dugmad plana" u korisničkom interfejsu prodaje skupih proizvoda

### <a name="officeappleiapreviewyoursubscriptionios"></a>Office.Apple.IAPReviewYourSubscriptioniOS

Ovaj događaj beleži metapodatke zasnovane na sesiji kada se korisniku prikaže korisnički interfejs „Kupovina unutar aplikacije“ (IAP) i dugmad s kojima korisnik naknadno stupa u interakciju. Ti se podaci koriste kako bi nam pomogli da shvatimo probleme u toku kupovine i uporedimo ih sa levkom različitog iskustva kupovine kako bismo shvatili koje je iskustvo bolje za korisnika. 

Prikupljaju se sledeća polja:

- **FlowType** – Ceo broj – Tok odakle je pokrenut IAP.

- **Restore** – Niska – oznaka pravila se evidentira kada se klikne na dugme „Vrati u prethodno stanje“.

- **PremiumFeatures** – Niska – oznaka pravila se evidentira kada se klikne na dugme "PremiumFeatures"

- **Product**– Niska – SKU koji su izabrali korisnici


### <a name="officeappleinapppurchasecontext"></a>Office.Apple.InAppPurchaseContext

Ovaj događaj meri telemetriju kritične upotrebe za mesto ulaska na ekran za kupovinu u aplikaciji. Podaci pomažu u razumevanju i poboljšanju korisničkog iskustva identifikovanjem željene ulazne tačke za kupovinu u aplikaciji.

Prikupljaju se sledeća polja:

- **context** – Niska – Tok kroz koji je korisnik došao na stranicu „Kupovina“ u aplikaciji


### <a name="officeapplelicensingcommonpaywallcontrol"></a>Office.Apple.Licensing.CommonPaywallControl

Ovaj događaj se koristi za razumevanje iskustva kupovine u aplikaciji (IAP) za korisnika. Omogućava nam da osiguramo da IAP radi onako kako se očekuje i pomaže nam da razumemo korisničke probleme kako bismo mogli da optimizujemo IAP iskustvo.  Kolekcija se odvija putem jednog od sledećih pod događaja.

- **Office.iOS.Paywall.Paywall.Predstavljen** – Podaci se prikupljaju kada se korisniku prikaže kontrola platnog zida. Podaci se koriste za izgradnju prikaza za merenje stope konverzije u svakom koraku i osiguravanje da korisnički interfejs radi onako kako se očekuje kod korisnika koji imaju minimalno trenje tokom iskustva kupovine.

   Prikupljaju se sledeća polja:

  - **mesto unosa** – String – Dugme/Tok odakle je Paywall prikazan. Kao što je "Dugme za premijum nadogradnju" ili "Tok prvog pokretanja"
  - **is FRE** – Bulov izraz – Da li pokazujemo Iskustvo prvog pokretanja ili običan korisnički interfejs?

- **Office.iOS.Paywall.Paywall.Stats** – Podaci se prikupljaju kada se korisniku prikaže korisničko sučelje platnog zida, trajanje interakcije i da li je kupovina pokušana, uspela ili nije uspela. Podaci se koriste za merenje performansi korisničkog interfejsa i osiguravanje da on radi kako se očekuje. 

   Prikupljaju se sledeća polja:

   - **entryPoint** – niz – dugme/tok s kojeg je prikazan Paywall. Kao što je "Dugme za premijum nadogradnju" ili "Tok prvog pokretanja".
   - **is FRE** – Bulov izraz – Proverite da li se prikazuje iskustvo prvog pokretanja ili redovni korisnički interfejs.
   - **status** – niska – Status izlaska Paywall-a. Kao što je “initiated”, “paymentDone”, “provisionFailed”.
   - **userDuration** – Duplo – Trajanje u milisekundama koje je korisnik potrošio na Paywall-u
  
- **Office.iOS.Paywall.SKUChooser.BuyButtonTap** – Podaci se prikupljaju kada korisnik dodirne dugme Kupovina/Kupi. Podaci se koriste za merenje performansi dugmeta i osiguravanje da radi prema očekivanjima.

   Prikupljaju se sledeća polja:

   - **entryPoint** – niz – dugme/tok s kojeg je prikazan Paywall. Kao što je "Premium Upgrade Button" ili „First run flow“
   - **isdefaultSKU** – Bulova vrednost – ako korisnik kupuje proizvod, preporučili smo mu, prikazujući ga prema podrazumevanim postavkama.
   - **productId** – niz – ID proizvoda trgovine App-store za koji je dodirnuto dugme „Kupi“.
   - **toggleCount** – Int – koliko je puta korisnik prelazio s jednog prikaza proizvoda na drugi pre nego što je dodirnuo dugme Kupi u trenutnoj sesiji Paywall-a.

- **Office.iOS.Paywall.SKUChooser.Stats** – Podaci prikupljeni da bi se videlo kako je korisnik ušao u SKU Chooser, koliko vremena korisnik provodi na ekranu SKU Chooser i zašto je napustio SKU Chooser. Koristeći informacije, možemo da obezbedimo da SKU Chooser radi onako kako se očekivalo, i moći ćemo da optimizujemo i poboljšamo doživljaj krajnjeg korisnika.

   Prikupljaju se sledeća polja:

   - **entryPoint** – niz – dugme/tok s kojeg je prikazan Paywall. Kao što je "Dugme za premijum nadogradnju" ili "Tok prvog pokretanja".
   - **Razlog napuštanja** – String – Razlog za izlaz iz birača SKU. Kao što je “BuyButton”, “CloseButton“
   - **is FRE** – Bulov izraz – Da li pokazujemo Iskustvo prvog pokretanja ili običan korisnički interfejs?
   - **userDuration** – Duplo – Trajanje u milisekundama koje je korisnik proveo na SKU Chooser.

- **Office.iOS.Paywall.FailedScreen.RetryButtonTap** – Podaci prikupljeni kada kupovina/obezbeđivanje/aktivacija nisu uspeli i korisnik je dodirnuo dugme za ponovni pokušaj. Podaci se koriste za rešavanje problema sa scenarijima grešaka pri kupovini i za njihovo popravljanje kako bi se osiguralo da se izvrše kako se očekuje.

   Prikupljaju se sledeća polja:

   - **failureReason** – Niska – Označava šta je greška u pokušaju korisnika; na primer, „provisioningFailed“, „purchaseFailed“, „activationFailed“.
   - **productId** – Niska – ID proizvoda u App Store za koji korisnik ponovo pokušava neuspeli zahtev.

- **Office.iOS.Paywall.SKUChooser.MoreBenefits.Stats** – Podaci prikupljeni kada korisnici dodirnu „Pogledajte još pogodnosti“ da biste videli sve usluge, aplikacije i funkcije uključene u kupovinu. Moraju proširiti odeljke sa detaljima funkcija svake od aplikacija. Ovaj događaj prikuplja funkcije i aplikacije koje su proširili, zajedno sa trajanjem provedenog vremena. Podaci se koriste kako bi se osiguralo da korisnički interfejs koji se nudi krajnjim korisnicima radi upoznavanja s prednostima se izvršava prema očekivanjima. 

   Prikupljaju se sledeća polja:

   - **appsExpanded** – Niska – Usluge/aplikacije, razdvojene zarezima, za koje su razvijene pogodnosti.
   - **productId** – Niska – ID proizvoda u App Store za koji korisnik prikazuje više ponuđenih pogodnosti
   - **userDuration** – Duplo – Trajanje u milisekundama koje je korisnik proveo na ekranu „Pogodnosti“.

- **Office.iOS.Paywall.SuccessScreen.SeeAllBenefitsButtonTap** – Ovaj događaj se prikuplja kada korisnik nakon uspešne kupovine dodirne „Pogledajte sve pogodnosti“ da bi video aplikacije i funkcije uključene u kupovinu. Podaci se koriste za merenje korisničkog interfejsa kako se očekuje.

   Prikupljaju se sledeća polja:

   - **productId** – niska – ID proizvoda usluge App Store za koji korisnik prikazuje sve ponuđene pogodnosti.

- **Office.iOS.Paywall.SKUChooser.ProductSwitched** – Korišćenje telemetrije za prikazivanje interakcije krajnjeg korisnika sa korisničkim interfejsom predviđena za prebacivanje između različitih SKU-ova i osiguravanje da ona funkcioniše kako se očekuje. 

   Prikupljaju se sledeća polja:

  - **productId** – niska – ID proizvoda usluge App Store na čije prikazivanje se korisnik upravo prebacio sa dostupnih proizvoda u SKU biraču.

- **Office.iOS.Paywall.StoreKit.Response** – Kritična inženjerska telemetrija za evidenciju rezultata pokušaja kupovine koji su ručno pokrenuli korisnik i odgovor App Store-a na događaj. Podaci se koriste za merenje statusa pokušaja kupovine i razloga neuspeha (ako postoje) i preduzimanje korektivnih radnji kako bi se osiguralo da IAP i sve ulazne tačke rade onako kako se očekuje.

   Prikupljaju se sledeća polja:

   - **entryPoint** – niz – dugme/tok s kojeg je prikazan Paywall. Kao što je "Premium Upgrade Button" ili „First run flow“
   - **failureReason** – niz – dodat samo kada je status "neupeh". Ukazuje na odgovor na grešku koji je dala prodavnica App-store.
   - **productId** – niz – samo za „MakePurchase“, „PendingPurchase”, ID proizvoda prodavnice app-store za koji je zahtev stvoren.
   - **productsCount** -Int – samo za "ProductsFetch", broj proizvoda koje prodavnica vraća.
   - **requestType** – niz – vrsta zahteva za Storekit. Kao što je "ProductsFetch", "Pendingpurchase"
   - **status** – Niska – Uspeh ili neuspeh, što ukazuje na uspeh ili neuspeh zahteva.

- **Office.iOS.Paywall.Provisioning.Response** – Telemetrija kritičnog inženjeringa i ugovor sa Službom maloprodajnog saveza (RFS) za prikupljanje podataka danih u ovom dokumentu. RFS je interna usluga koja se u okviru korporacije Microsoft koristi za unakrsnu proveru kupovine. Ovo se koristi za dobijanje ispravnosti API poziva upućenog RFS-u, što bi pomoglo u razumevanju da su performanse integracije očekivane.  

   Prikupljaju se sledeća polja:

   - **entryPoint** – niz – dugme/tok s kojeg je prikazan Paywall. Kao što je "Premium Upgrade Button" ili „First run flow“
   - **failureReason** – niz – dodat samo kada je status "neupeh". Ukazuje na odgovor na grešku koji je dao RFS odgovor dodeljivanja privilegija.
   - **productId** – niz – ID proizvoda prodavnice App Store za koji je izrađen zahtev
   - **stanje** – niz – upeh ili neupeh, što upućuje na to je li zahtev uspeo ili ne


### <a name="officedimesdkhealth"></a>Office.Dime.Sdk.Health

Ovaj događaj prikuplja podatke koji pomažu u nadgledanju zdravlja komponenata Dime. Na primer, da biste mogli da koristite tok kupovine u aplikaciji kada se korisnik odluči za kupovinu pretplate na Microsoft 365 iz aplikacije Office za Android ili na uređajima sa sistemom Windows.

Prikupljaju se sledeća polja:

- **Data_ActivityErrorDescription** – opis greške aktivnosti

- **Data_ActivityErrorMessage** – poruka o grešci aktivnosti 

- **Data_CampaignId** – ID kampanja za autorstvo

- **Data_ContentId** –Na osnovu ID-a iskustva; mapira se u ID-u tokova i ID sadržaja

- **Data_CorrelationVector** –vektor za povezanost sa partnerima koji koriste vektor korelacije

- **Data_CustomerImpacted** – koristi se za rešavanje problema ako je korisnik uticao na učitavanje tokova

- **Data_DimeActivityDuration** – vreme trajanja 

- **Data_DimeActivityMetadata** – metapodaci aktivnosti

- **Data_DimeActivityName** – ime aktivnosti za nadgledanje ispravnosti

- **Data_DimeActivityResult** – Rezultat aktivnosti, uspeh / greška / očekivana greška

- **Data_DimeVersion verzije** –verzija izdanja

- **Data_DurationLevel** – Ozbiljnost – 0/1/2

- **Data_EcsConfigIds** – ID-evi za eksperimente

- **Data_EcsCountry** – otkrivena zemlja

- **Data_EcsETag** – informacije o letovima

- **Data_Environment** – Dime Environment proizvodnja / predprodukcija

- **Data_ExperienceId** – iskustvo za učitavanje 

- **Data_FlowId** – Na osnovu ID-a iskustva; mapira se u ID-u tokova i ID sadržaja

- **Data_Language** – kultura

- **Data_Market** – otkriveno tržište

- **Data_OTelJS_Version** – verzija telemetrije sistema Office

- **Data_PageSessionId** – ID sesije na stranici.

- **Data_PartnerId** – Caller App

- **Data_QosLevel** – Severity 0/1/2

- **Data_SDX_AssetId** – ID sredstva hosting sadržaja sa isporučenim iskustvom (SDX) za Win32

- **Data_SDX_BrowserToken** – token pregledača za Win32

- **Data_SDX_HostJsVersion** – JavaScript verzija biblioteke za Win32

- **Data_SDX_Id** – ID isporučenog iskustva usluge za Win32

- **Data_SDX_InstanceId** – ID instance za SDX za Win32

- **Data_SDX_MarketplaceType** – tip SDX tržišta za Win32

- **Data_SDX_OfficeJsVersion** – Office JS verzija za Win32

- **Data_PageSessionId** – ID sesije za SDX za Win32

- **Data_SDX_Version** – SDX verzija za Win32

- **Data_TimestampUTC** – vremenska oznaka događaja

- **Data_TsgId** – ID vodiča za rešavanje problema za svaku aktivnost

- **Data_UserAgent** – oznake u zaglavlju


### <a name="officedocssharedpremiumfeaturemessagebar"></a>Office.Docs.Shared.PremiumFeatureMessageBar

Ovaj događaj prikuplja dodire besplatnih korisnika na premium funkciju koja se nalazi iza platnog zida. Podaci se koriste za razumevanje skupa funkcija sa kojima potrošači u interakciji dok se pretvaraju u plaćenog korisnika. Ovo nam govori o poželjnim ulaznim tačkama korisnika i poboljšava korisničko iskustvo.

Prikupljaju se sledeća polja:

- **featureId** – TCID za premium funkciju koju korisnik dodirne


### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Ovo se prikuplja kada korisnik postane licenciran i prihvati EULA ugovor za trenutnu licencu

Koristi se za određivanje da li se korisnik nalazi u dobrom ili lošem statusu, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **ACID** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **DwEulaId** – Numerički identifikator za tip EULA ugovora koji je korisnik prihvatio


### <a name="officelicensingactivatedeviceentitlement"></a>Office.Licensing.ActivateDeviceEntitlement

Ovaj događaj se pokreće kada pokušavamo da aktiviramo trajnu Office ponudu na osnovu uređaja za korisnika. Ove podatke koristimo za nadgledanje ispravnosti sistema i usluga.

Prikupljaju se sledeća polja: 

- **Activity_Success** – govori nam da li uređaj ima licencu uz trajnu Office ponudu zasnovanu na uređaju.

- **Data_Count** – govori nam broj trajnih ovlašćenja za Office zasnovanih na uređaju povezanih sa uređajem. Tehnički ne bi trebalo da bude više od jednog.

- **Data_EligibleEntitlementsCount** – govori nam broj prihvatljivih prava. Pošto će usluga vratiti sva ovlašćenja za uređaj povezana sa uređajem, ali moramo da proverimo one ponude koje su relevantne za Office aplikaciju koja je pokrenuta.

- **Data_Errors** – niska sa listom grešaka dok dobavljamo licence za prava, odvojene zarezom.

- **Data_LicensedEntitlementsCount** – govori nam broj ovlašćenja za koja smo uspešno dobavili licencu. Moglo bi doći do grešaka u ovlašćenju zbog kojih ne možemo dobiti licencu. 


### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Kada podesimo licencu na računaru, pokušavamo da je aktiviramo tako što pozivamo uslugu AVS. Ovo izveštava o ishodu poziva za aktivaciju

Od suštinskog je značaja za određivanje koliko korisnika nailazi na probleme prilikom aktivacije. Imamo detektor anomalija koji otkriva bilo koju regresiju. To je izuzetno važno jer zavisimo od spoljašnje usluge AVS, pa nam ovaj signal pokazuje je li stanje naših spoljnih partnera dobro. Takođe se koristi i za dijagnostičke svrhe i ispravnost sistema ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **ReferralData** – Identifikator OEM proizvođača koji je instalirao Office na računaru

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Ako iz nekog razloga nismo u mogućnosti da automatski aktiviramo licencu, prikazujemo korisniku čarobnjaka za aktivaciju. Ovo obaveštava da je čarobnjak za aktivaciju prikazan korisniku. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingbusbarcheckfordynamicbusbarexperiment"></a>Office.Licensing.BusBar.CheckForDynamicBusbarExperiment

Ovaj događaj se pokreće jednom za svaki tip informativne trake za licenciranje koja se pokazuje i koja ima dinamički let informativne trake na (grupa za tretiranje). Ovaj događaj podataka izveštava o tome da li je na disku spremna dinamička informativna traka kampanje platforme životnog ciklusa. Podaci će se koristiti za merenje ispravnosti nove tehnologije dinamičkog licenciranja informativne trake za programiranje platforme životnog ciklusa.

Prikupljaju se sledeća polja:

- **DoesCampaignExist (bulova)** – ukazuje na to da li je kampanja na disku

- **Tip (int32)** – ukazuje na tip poslovne trake licenciranja


### <a name="officelicensingbusbarshowstashedbusbar"></a>Office.Licensing.BusBar.ShowStashedBusbar

Ovaj događaj se pokreće kada se dinamička informativna traka platforme za programiranje životnog ciklusa ne prikaže i umesto toga treba prikazati skrivenu statičku poslovnu traku. Ovaj događaj podataka koristiće se da bi se osiguralo da je vraćanje na statičku poslovnu traku uspešno.

Prikupljaju se sledeća polja:

- **Tip (int32)** – ukazuje na tip poslovne trake licenciranja


### <a name="officelicensingdialogswebviewdialogclose"></a>Office.Licensing.Dialogs.WebViewDialog.Close
 
Ovaj događaj se koristi kao signal koji nam govori da korisnik ili aplikacija zatvara iskustvo kupovine u aplikaciji. Podaci se koriste za nadgledanje i upozoravanje na stanje toka kupovine u aplikaciji kako bi se osiguralo da radi kako se očekuje.  
 
Prikupljaju se sledeća polja:
 
- **Data_ClosedDialog** – zastava koja označava da je korisnik zatvorio dijalog

### <a name="officelicensingdialogswebviewdialoghandleerrornotification"></a>Office.Licensing.Dialogs.WebViewDialog.HandleErrorNotification
 
Ovaj događaj se koristi kao signal koji nam govori da je iskustvo kupovine u aplikaciji pokušalo da se učita. Podaci se koriste za nadgledanje i upozoravanje na stanje toka kupovine u aplikaciji kako bi se osiguralo da radi kako se očekuje.  
 
Prikupljaju se sledeća polja:
  
- **Data_MoeErrorCode** – kôd greške koji se vidi u okviru dijaloga veb dijalog

### <a name="officelicensingdialogswebviewdialogpreload"></a>Office.Licensing.Dialogs.WebViewDialog.Preload
 
Ovaj događaj se koristi kao signal koji nam govori da se iskustvo kupovine u aplikaciji učitava u pozadini. Podaci se koriste za nadgledanje i upozoravanje na stanje toka kupovine u aplikaciji kako bi se osiguralo da radi kako se očekuje.  
 
Prikupljaju se sledeća polja:

 - Nijedno

### <a name="officelicensingdialogswebviewdialogshow"></a>Office.Licensing.Dialogs.WebViewDialog.Show
 
Ovaj događaj se koristi kao signal koji nam govori da se iskustvo kupovine u aplikaciji prikazuje korisniku. Podaci se koriste za nadgledanje i upozoravanje na stanje toka kupovine u aplikaciji.  

Prikupljaju se sledeća polja:

 - Nijedno

### <a name="officelicensingdialogswebviewdialogtimeout"></a>Office.Licensing.Dialogs.WebViewDialog.Timeout

Ovaj događaj se koristi kao signal koji nam govori da je iskustvo kupovine u aplikaciji pokušalo da se učita, ali je isteklo. Podaci se koriste za nadgledanje i upozoravanje na stanje toka kupovine u aplikaciji kako bi se osiguralo da funkcioniše kako se očekuje. 

Prikupljaju se sledeća polja:

 - Nijedno


### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Ovo je signal koji nam govori da li je uspešan eksperiment koji smo pokrenuli da bismo nametnuli prijavljivanje korisnika kao deo licenciranja. Od suštinskog je značaja za otkrivanje uspešnosti ili neuspešnosti eksperimenta koji nameće prijavljivanje korisnika, što je neophodan korak u nizu modernog licenciranja.  Neuspešno prijavljivanje će onemogućiti da korisnici koriste aplikaciju.

Prikupljaju se sledeća polja:

  - **Qualified** - Određuje da li je korisnik kvalifikovan za nametnuto prijavljivanje

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Ovo se prikuplja kada korisniku prikažemo dijalog isteka koji pokazuje da je njihova licenca istekla. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i da li ima svu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **LicNotificationState** - Brojač koji nam govori koja vrsta obaveštenja se prikazuje korisniku

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Ovo se prikuplja pri svakoj sesiji koja izveštava o statusu licence na računaru i greškama koje se prikazuju korisniku zbog kojih nije u mogućnosti da koristi aplikaciju. Ovaj događaj ukazuje na to da li je korisnikov računar ispravan ili nije. Za ovaj događaj imamo podešen detektor anomalija da bismo označili da li regresija ili mehanizam aktivacije uzrokuje neispravno ponašanje korisnika. Takođe je od suštinske važnosti pri dijagnostikovanju korisničkih problema i za nadgledanje ispravnosti sistema.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran  
  
  - **ActivationAttributes** – tip mehanizma aktivacije koji korisnik koristi.

  - **IsSessionLicensing** - Da li je trenutno pokrenuta u režimu aktivacije deljenog računara ili nije. 

  - **LicenseCategory** – Kategorija Office licence koju koristi korisnik 

  - **Licenses** – Lista sa imenima svih Office licenci koje se nalaze na računaru 

  - **LicenseStatuses** – Status svih Office licenci koje se nalaze na računaru 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Ovo prikupljamo kad korisnik podešava uređaj, a mi pozivamo uslugu licenciranja da bismo otkrili da li prijavljeni korisnik ima prava na sistem Office ili nema. Ovo izveštava o ishodu tog poziva. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

- **EntitlementCount** - Broj prava koji korisnik poseduje


### <a name="officelicensinggetnextuserlicense"></a>Office.Licensing.GetNextUserLicense

Ovaj događaj se pokreće prilikom dobavljanja licence za izabrano Office pravo zasnovano na korisniku tokom iskustva sa prvim pokretanjem aktivacije. Ove podatke koristimo za nadgledanje ispravnosti sistema i usluga.

Prikupljaju se sledeća polja:

- **Activity_Success** – Bulov: govori nam da li smo uspešno preuzeli licencu za uređaj koji će se aktivirati u njegovoj Office aplikaciji.

- **Data_AllowNULPerpetual** – Bulov: govori nam je li uključen let za omogućavanje funkcije vNext Perpetual.

- **Data_AttemptNulReactivation** – Bulov: govori nam da li je ovo scenario reaktivacije.

- **Data_CurrentMode** – 0 znači SPP (zadati stek licenciranja), 2 znači vNext (moderni stek licenciranja).

- **Data_HasError** – Bulov: govori nam da li smo imali grešku prilikom pokušaja dobijanja licence za izabrano pravo zasnovano na korisniku.

- **Data_IsSubscription** – Bulov: govori nam da li je ponovno aktiviranje za office pretplatu.

- **Data_NewMode** – 0 znači SPP (zadati stek licenciranja), 2 znači vNext (moderni stek licenciranja). Većinu vremena bismo trebali očekivati 2.

- **Data_SkuToSkuNeeded** – Bulov: govori nam da li treba da izvršimo konverziju SKU u SKU zbog toga što naslovljeni Office SKU ne odgovara instaliranom Office SKU-u.


### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Prilikom svake sesije proveravamo da li je prošlo 72 sata od poslednje obnove licence i pokušavamo da produžimo rok isteka trenutne licence. Ovaj događaj izveštava o uspešnosti ili neuspešnosti poziva koji smo uputili da bismo proverili da li možemo da produžimo rok isteka licence i da korisnikovu instalaciju sistema Office održimo u funkciji. Od suštinske je važnosti pri dijagnostikovanju korisnikovih problema vezanih za pretplatu i uslugu, kao i za otkrivanje regresija kod korisnika koji su već aktivirali pretplatu.

Prikupljaju se sledeća polja:

  - **Mode** - Numeričko predstavljanje paketa licenci za sistem Office koji se koristi na računaru

### <a name="officelicensinginclientpinredemptioncallpinredemptionapi"></a>Office.Licensing.InClientPinRedemption.CallPinRedemptionAPI

Ova telemetrija prati rezultate servisnog poziva za aktivaciju sistema Office pomoću PIN koda.

Prikupljaju se sledeća polja:

- **ClientTransactionId** - Jedinstveni identifikator pozivanja usluge

- **ErrorCategory** – Svaki tip greške može da spada u uopšteniju kategoriju, kao što je „Mogućnost ponovnog pokušaja“.

- **ErrorType** – Razlog neuspeha, kao što je „AlreadyRedeemedByOther“.

- **InAFOFlow** – Bulova vrednost koja pokazuje da li se nalazimo u Aktivacija za Office aktivacionom toku.

- **StatusCode** – Rezultat pozivanja usluge koji se sastoji od jedne reči, kao što je „Napravljeno“.

- **StatusMessage** – Detalji o statusnom kodu, kao što je „Uspešno obezbeđeno“.

- **UsingNulApi** - Bulova vrednost koja pokazuje da li se koristi novi paket licenci.

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Ako uređaj uđe u režim smanjene funkcionalnosti, šaljemo ovaj signal da bismo ukazali da računar nije u zdravom stanju. Ključno je u otkrivanju da li je korisnik u dobrom stanju i nedostaje mu funkcionalnost, koristi li se za zdravlje sistema i koristi u dijagnostičke svrhe ako korisnik prijavi problem sa svojim računarom

Prikupljaju se sledeća polja:

  - **ACID** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **DaysRemaining** – Broj dana koji je preostao do isteka trenutne Office licence

  - **Mode** – Numeričko predstavljanje paketa licenci za sistem Office koji se koristi na računaru

  - **ProductName** - Ime proizvoda koji korisnik trenutno koristi

  - **Reason** - Kôd greške koji ukazuje na razlog trenutnog statusa licence

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Ovo se prikuplja kada pokušavamo da instaliramo ključ na uređaj da bismo licencirali računar. Izveštava da li je instalacija uspešna, a ako nije, šalje kôd greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **Prid** - Ime grupe proizvoda za koju se instalira ključ

  - **SkuId** – GUID identifikator koji predstavlja Office proizvod za koji se instalira ključ 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

U slučaju da primetimo probleme sa tokom posla aktivacije, pokrećemo čarobnjaka za licenciranje i šaljemo signal koji to naznačava. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i da li ima svu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **LicenseStatus** – Status Office licence koju korisnik koristi

  - **MachineKey** - Alfanumerički identifikator ključa licence koji je izdat korisniku

### <a name="officelicensinglaunchsetupoffice"></a>Office.Licensing.LaunchSetupOffice

Ovaj događaj se pokreće kada iskoristimo Office ponudu za korisnika koji je kupio uređaj u paketu sa OEM ovlašćenjem ili je uneo šifru proizvoda. Ove podatke koristimo za nadgledanje ispravnosti sistema i usluga.

Prikupljaju se sledeća polja:

- **Activity_Result_Tag** – govori nam kako smo završili ovaj događaj.

- **Data_DialogResult** – govori nam ukupan rezultat procesa prihvatanja.

- **Data_Scenario** – govori nam o scenariju za koji je došlo do otkupa.


### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Ako uređaj naiđe na probleme sa licenciranjem i dođe do toga da korisniku prikažemo sabirnicu, šaljemo ovaj signal koji izveštava i o tipu sabirnice koja je prikazana korisniku. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **SuppressNotification** - Označava da li smo potisnuli sabirnicu licenciranja

  - **Title** - Naziv sabirnice licenciranja koja je prikazana korisniku

  - **Type** - Tip sabirnice licenciranja koja je prikazana korisniku

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Ako dođe do zatvaranja ili pada sistema Office zbog problema sa licenciranjem, šaljemo ovaj signal da bismo to naznačili. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i da li ima svu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **ExitCode** - Unutrašnji kôd koji je izazvao zatvaranje aplikacije

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

U toku pokušaja da se uređaj licencira, aplikacija pokušava da učita korisnikov identitet da bi videla da li korisnik ima pravo na sistem Office. Događaj prijavljuje uspeh ili neuspeh istog zajedno s eventualnom šifrom greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **FederationProvider** - Niska koja identifikuje dobavljača spoljnog pristupa za trenutno prijavljenog korisnika

  - **IdentityProvider** - Niska koja identifikuje dobavljača identiteta za trenutno prijavljenog korisnika

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Ovo se prikuplja ako smo korisniku prikazali EULA ugovor, a on je izabrao da ga ne prihvati što je dovelo do pada/zatvaranja aplikacije. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **OptInShown** – označava je li dijalog za uključivanje koji se prikazuje prilikom prvog pokretanja aplikacije već prikazan

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

Ovaj signal nam pokazuje da li je korisnik kvalifikovan za prelazak na novi paket licenci. Ovo je od suštinske važnosti za određivanje stepena uticaja na postojeće korisnike dok objavljujemo nove pakete licenci i obezbeđivanje da korisnici zadrže funkcionalnost.

Ovaj događaj ne prikuplja nikakva polja.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Kada je uređaj na modernom paketu licence, trudimo se da datoteku licence preuzmemo direktno iz usluge. Ovaj događaj izveštava o uspešnosti ili neuspešnosti, kao i o kôdu greške kod poziva usluge. Ključan je za otkrivanje je li korisnik u dobrom stanju na modernom paketu za licenciranje, koristi se u svrhe određivanja stanja sistema i za dijagnostiku ako korisnik prijavi problem s mašinom.

Prikupljaju se sledeća polja:

  - **MetadataValidationResult** - Rezultat provere valjanosti metapodataka licence da bi se proverilo da nisu neovlašćeno promenjeni

  - **SignatureValidationResult** - Rezultat provere valjanosti potpisa da bi se proverilo da nije neovlašćeno promenjen

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Ovo se prikuplja pri svakoj sesiji uređaja koji je pokrenut na modernom paketu licence. Prijavljuje stanje licenciranja mašine i prijavljuje greške koje se korisniku prikazuju i zbog kojih ne može koristiti aplikaciju. Događaj označava je li korisnikova mašina u dobrom stanju na modernom paketu za licenciranje. Za ovaj događaj imamo podešen detektor anomalija da bismo označili da li regresija uzrokuje neispravno ponašanje korisnika. Takođe je od suštinske važnosti pri dijagnostikovanju korisničkih problema i za nadgledanje ispravnosti sistema.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran  

  - **AllAcids** - Lista svih GUID proizvoda za koje je korisnik trenutno licenciran 

  - **Category** – Kategorija Office licence koju korisnik koristi 

  - **DaysRemaining** – Broj dana koji je preostao do isteka trenutne Office licence 

  - **LicenseId** - Alfanumerički identifikator licence koji je izdat korisniku 

  - **LicenseType** – Tip Office licence koju korisnik koristi 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Ovo su metapodaci licenciranja koji se prikupljaju pri svakom pokretanju i koji izveštavaju o proizvodu, statusu, tipu i drugim svojstvima licence koja su važna za određivanje skupa funkcija dostupnih korisniku. Od suštinske je važnosti za određivanje skupa funkcija koje su dostupne korisniku i da li nedostaje neka funkcionalnost. Takođe se koristi i za izračunavanje broja dnevno/mesečno aktivnih korisnika, kao i za različite izveštaje koje koriste razni timovi u svim Office oblastima, jer nam to govori koji tip proizvoda koristi korisnik, da li je u pitanju pretplata na proizvod i da li nedostaje neka bitna funkcionalnost.

Prikupljaju se sledeća polja:

  - **FullValidationMode** - Režim koji ukazuje na to da se nalazimo u potpunoj validaciji verifikacije licence 

  - **IsRFM** - Ukazuje na to da li se korisnik nalazi u režimu smanjene funkcionalnosti ili ne 

  - **IsSCA** - Ukazuje na to da li se nalazimo u režimu aktivacije deljenog računara 

  - **IsSubscription** - Ukazuje na to da li korisnik koristi licencu za pretplatu ili ne 

  - **IsvNext** - Ukazuje na to da li koristimo novi moderni paket licenciranja ili ne 

  - **LicenseCategory** – Kategorija Office licence koju koristi korisnik 

  - **LicenseStatus** – Status Office licence koju korisnik koristi 

  - **LicenseType** – Tip Office licence koju korisnik koristi 

  - **LicensingACID** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **OlsLicenseId** - Alfanumerički identifikator licence koji je izdat korisniku 

  - **SkuIdIsNull** – Ukazuje na to da li smo naišli na grešku i ne znamo koji proizvod korisnika pokreće 

  - **SlapiIsNull** - Ukazuje na to da li smo naišli na problem u popunjavanju jednog od objekata licenciranja  

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Ovaj događaj se pokreće ako iz nekog razloga nismo u mogućnosti da aktiviramo korisnika i moramo da im prikažemo dijalog koji mu traži da se priključi na mrežu i pokuša da prati korake za popravak. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingoobehandledigitalattachfailure"></a>Office.Licensing.OOBE.HandleDigitalAttachFailure

Ovaj događaj se pokreće kada provera usluge (pogledajte Office.Licensing.OOBE.SearchForDigitalAttach) na ovom uređaju nije pronašla ponuđenu ponudu Digital Attach. Na osnovu različitih uslova uređaja, korisniku ćemo prikazati različite dijaloge. Ovaj događaj evidentiraće različite scenarije o tome kako se bavimo neuspehom digitalnog priloga.

Prikupljaju se sledeća polja:

- **Activity_Result_Tag** govori nam kako prelazimo korisnika u različita stanja grešaka.
   - 0x222e318f – Trebalo bi da nastavimo da tražimo Aktivaciju za Office ponudu.
   - 0x222e318e – Vratićemo se u OEM režim u ovoj sesiji kada ovaj uređaj ne bude isporučen sa bilo kojom ponudom Digital Attach.
   - 0x222e318d – Nema internet veze, što će nas dovesti do toga da korisniku prikažemo dijalog NoInternetConnectiviti 
   - 0 – Korisniku ćemo prikazati različite greške u korisničkom interfejsu na osnovu njihovog specifičnog koda greške.

- **Data_DigitalAttachErrorType** – govori nam koji je konkretan kod greške iz poziva usluge.

- **Data_FallbackFlight** – govori nam da li je UseAFOAsFallBack let uključen ili nije.


### <a name="officelicensingoobehandledigitalattachsuccess"></a>Office.Licensing.OOBE.HandleDigitalAttachSuccess

Ovaj događaj se pokreće kada provera usluge na ovom uređaju pronađe potražnu ponudu Digital Attach. Na osnovu različitih uslova uređaja, korisniku ćemo prikazati različite dijaloge. Ovaj događaj evidentiraće različite scenarije o tome kako se bavimo uspehom digitalnog priloga.

Prikupljaju se sledeća polja:

- **Activity_Result_Tag** – govori nam kako rukujemo scenarijima uspeha digitalnih prilaganja.
   - 0 – U mogućnosti smo da automatski učitamo identitet i korisniku smo prikazali korisničko ime „Imate Office“ (sa nalogom).
   - 0x222e3191 – Nismo u mogućnosti da automatski učitamo identitet, pa ćemo im pokazati korisnički interfejs „Imate Office“ (bez računa).
   - 0x222e3193 – Korisniku smo prikazali korisnički interfejs „Imate Office“ (bez računa) ili ne moramo korisniku da prikažemo bilo koji korisnički interfejs „Imate Office“ jer je to ponuda zasnovana na uređaju.

- **Data_IsClaimTypeDevice** – govori nam da li je vrsta zahteva za ponudu digitalnog priloga zasnovana na uređaju.

### <a name="officelicensingoobepopulatedigitalattachoffersignindex"></a>Office.Licensing.OOBE.PopulateDigitalAttachOfferSignInDEX

Proizvođači originalne opreme (OEM) prodaju računare koje dolaze sa sistemom Office (jednogodišnje pretplate ili trajne) i koje se plaćaju kada kupac kupi njihovu mašinu. Ovaj događaj prati kada se za uređaj pronađe pretpostavka za Office, a korisnik je već prijavljen sa Microsoft nalogom da bi nam omogućio da nadgledamo stanje sistema i usluga.

Prikupljaju se sledeća polja:

- **Data_ExpirationDate** – govori nam datum isteka ponude za pretplatu

- **Data_IsSubscription** – govori nam da li je proizvod koji se zahteva pretplata na SKU ili večiti SKU

- **Data_ProductName** – govori nam naziv proizvoda ponude za digitalni prilog


### <a name="officelicensingoobesearchfordigitalattach"></a>Office.Licensing.OOBE.SearchForDigitalAttach

Proizvođači originalne opreme (OEM) prodaju računare koje dolaze sa sistemom Office (jednogodišnje pretplate ili trajne) i koje se plaćaju kada kupac kupi njihov računar. Računari koji su podešeni sa određenim ključem regkey (OOBEMode: OEMTA) mogu imati digitalnu vezu sa Office ponudom. Kada pokrenemo Office, vršimo provere usluga da bismo utvrdili da li je pronađena digitalno priložena Office ponuda. Ova aktivnost je instrumentirana da to prati. 

Prikupljaju se sledeća polja:

- **Activity_Result_Tag** – govori nam ukupan rezultat ove provere usluge. 
   - 0x222e318c Digital Attach Flight je ISKLJUČEN, tako da se ne vrši provjera usluge.
   - 0x222e318b Klijent nema internet, pa se ne vrši provera usluge.
   - 0x222e318a Pronašli smo Digital Attach ponudu koja se može iskoristiti
   - 0x222e3189 Pronašli smo Digital Attach ponudu koja se ne može iskoristiti

- **Data_EnableDAFlight** – govori nam da li je let Digital Attach koji omogućava ovu proveru usluge UKLJUČEN ili ne.


### <a name="officelicensingoobeshowtouchlessattachfailuredialog"></a>Office.Licensing.OOBE.ShowTouchlessAttachFailureDialog

Proizvođači originalne opreme (OEM) prodaju računare koje dolaze sa sistemom Office (jednogodišnje pretplate ili trajne) i koje se plaćaju kada kupac kupi njihov računar. Ovaj događaj se pokreće kada se dogodi greška u procesu otkupa i aktiviranja digitalnog priloga za OEM računare koji imaju unapred dodeljeni naslov uz Office.  Ove podatke koristimo za nadgledanje ispravnosti sistema i usluga i rešavanje problema povezanih sa tokom aktivacije OEM Office aktivacije.

Prikupljaju se sledeća polja:

- **Data_Continue** – govori nam ako korisnik klikne na dugme „Nastavi“ u dijalogu.

- **Activity_Result_Tag** – govori nam dugme na koje je korisnik kliknuo u dijalogu.
   - 0x222e319d – Korisnik klikne na dugme „Pokušaj ponovo“ u dijalogu
   - 0x222e319c – Korisnik klikće na dugme „Nastavi“ u dijalogu
   - 0 – Korisnik izlazi iz dijaloga

- **Data_IsForDigitalAttach** – govori nam na kojoj je platformi i u kom toku posla korisnik – Zastarelo (Activacija za Office (AFO)) ili Moderno (Digital Attach).

- **Data_Retry** – govori nam da li korisnik klikne na „Pokušaj ponovo“ u dijalogu.


### <a name="officelicensingoobeshowtouchlessattachofferdialog"></a>Office.Licensing.OOBE.ShowTouchlessAttachOfferDialog

Proizvođači originalne opreme (OEM) prodaju računare koje dolaze sa sistemom Office (jednogodišnje pretplate ili trajne) i koje se plaćaju kada kupac kupi njihov računar. Ovaj događaj prati kada se za uređaj pronađe pretpostavka za Office, a korisnik nije prijavljen sa Microsoft nalogom da bi nam omogućio da nadgledamo stanje sistema i usluga.

Prikupljaju se sledeća polja:

- **Activity_Result_Tag** – govori nam da li je za korisnika pronađen identitet
   - 0x222e3194 – Ne možemo da dobijemo korisnički identitet (oni su otkazali prijavu ili potvrda identiteta nije uspela).
   - 0 – Dobili smo identitet od korisnika.

- **Data_ExpirationDate** – govori nam datum isteka ponude za pretplatu

- **Data_IsCentennial** – govori nam da li je pokrenuta kancelarijska aplikacija na stogodišnjoj platformi

- **Data_IsForDigitalAttach** – govori nam da li se ovaj dijalog pokreće iz toka Digital Attach ili Aktivacija za Office.

- **Data_IsSubscription** – govori nam da li je proizvod koji se zahteva pretplata na SKU ili večiti SKU

- **Data_OExType** – govori nam da li korisnik izlazi iz dijaloga nakon što klikne na vezu ChangeAccount

- **Data_ProductName** – govori nam naziv proizvoda ponude za digitalni prilog

- **Data_UseInAppRedemption** – govori nam da li koristimo iskorišćenje interneta u aplikaciji – ovo je relevantno samo za tok aktivacije za Office.


### <a name="officelicensingoobetrybuychoice"></a>Office.Licensing.OOBE.TryBuyChoice

Korisnicima, koji imaju unapred instaliran Office na novim računarima i koji ne poseduju prava na sistem Office, prikazuje se dijalog pomoću kog mogu da isprobaju, kupe ili unesu šifru proizvoda da bi dobili licencu. Ovaj događaj beleži radnju korisnika u dijalogu. Ovaj događaj se koristi za praćenje korisničke radnje izvršene u dijalogu koji se prikazuje korisnicima bez prava na Office, kod kojih je Office unapred instaliran na računaru, s namerom da pomogne pri utvrđivanju da li korisnik ima licencu ili ne.

Prikupljaju se sledeća polja:

- **Buy** - Obaveštava da li je korisnik kliknuo na dugme „Kupi“ ili nije

- **ForceAutoActivate** - Obaveštava da li treba pokušati aktivaciju u aplikaciji ili ne

- **GoBackToSignIn** - Obaveštava da li je korisnik želeo ponovo da se prijavi (verovatno sa drugim nalogom)

- **IsPin** - Obaveštava da li je korisnik uneo pin

- **ProductKey** - Obaveštava da li je korisnik pokušao da unese šifru proizvoda

- **Try** - Obaveštava da li je korisnik kliknuo na dugme „Isprobaj“ ili nije

- **UserDismissed** – Obaveštava da li je korisnik odbacio dijalog i da li se samim tim nalazi u grejs periodu ili u režimu smanjene funkcionalnosti jer nije izabrao da kupi ili isproba Office

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Imamo eksperiment u kojem se korisniku nudi mogućnost da isproba i postavi automatsko plaćanje sistema Office direktno iz aplikacije, a da ni u jednom trenutku ne mora da izađe iz aplikacije. Ovo izveštava o uspešnosti ili neuspešnosti datog eksperimenta, kao i o kôdu greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **StorePurchaseStatus** - Predstavlja kôd greške/uspeha poziva za kupovinu koji je upućen in Windows prodavnice

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Ako se korisnik nalazi u režimu aktivacije deljenog računara, pokušavamo da pronađemo token sesije na računaru koji dozvoljava korisniku da koristi aplikaciju. Događaj prijavljuje uspeh ili neuspeh scenarija zajedno s eventualnom šifrom greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **LoadLicenseResult** - Predstavlja kôd greške/uspeha za to da li smo bili u mogućnosti da učitamo licence za trenutnog korisnika

  - **OpportunisticTokenRenewalAttempted** – Ukazuje na to da li smo pokušali da oportunistički obnovimo token korisnikove sesije

  - **SetAcidResult** - Predstavlja kôd greške/uspeha za to da li smo bili u mogućnosti da podesimo acid na očekivane vrednosti

### <a name="officelicensingshownewdeviceactivationdialog"></a>Office.Licensing.ShowNewDeviceActivationDialog

Prilikom prvog pokretanja Office aplikacije, pokušaćemo da prikažemo dijalog za prijavljivanje koji je unapred popunjen sa akreditivima koje je korisnik upotrebio da bi preuzeo sistem Office. Korisnik zatim može da nastavi prijavljivanje sa tim akreditivima, da koristi druge ili da odbaci dijalog. Ovaj događaj izveštava o aktivnosti koju je izvršio korisnik kada mu je prikazan dijalog. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu kod modernog paketa licence, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **UserAction** - Identifikator aktivnosti koju je izvršio korisnik kada mu je prikazan dijalog.

### <a name="officelicensingskutoskuconversion"></a>Office.Licensing.SkuToSkuConversion

U sklopu licenciranja korisnika, ako treba da promenimo korisnikov SKU iz jednog u drugi, šaljemo ovaj signal zajedno sa kodom uspeha ili neuspeha. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu, a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **DestinationSku** - Ime SKU na koji trenutno instalirani proizvod treba da bude konvertovan

  - **PendingAcid** - Ime proizvoda čija je SKU konverzija na čekanju

  - **SourceSku** - Ime prvobitnog SKU koji je instaliran na računaru

  - **UninstallProduct** - Ukazuje na to da li će stari proizvod biti deinstaliran u sklopu konverzije

### <a name="officelicensingtelemetryflowolsresults"></a>Office.Licensing.TelemetryFlow.OLSResults

Kada korisnik nema licencu, upućujemo nekoliko poziva usluzi da bi dobio licencu i aktivirao svoj Office proizvod.  Ovaj događaj se pokreće prilikom pozivanja Office usluge licenciranja da bi se proverilo da li korisnik poseduje prava.  Ovaj događaj se koristi za praćenje ispravnosti korisničkog licenciranja nakon pozivanja Office usluge licenciranja i ispravnosti Office klijenta nakon pokušaja aktivacije sistema Office.

Prikupljaju se sledeća polja:

- **EntitlementPickerShown** - Obaveštava da li korisnik poseduje više prava i da li je morao ručno da odabere neko od njih da bi dobio licencu

- **GetAuthResult** - Obaveštava o različitim stanjima u kojima se može naći klijent, na primer, ako je dobio praznu šifru proizvoda od Office usluge licenciranja ili ako je posedovao prava za drugi proizvod, a Office treba da se konvertuje u novi proizvod

- **GetEntitlementsCount** - Obaveštava o broju prava koji korisnik poseduje

- **GetEntitlementsSucceeded** – Obaveštava da li je poziv upućen API usluzi Office licenciranja radi preuzimanja korisničkog prava bio uspešan ili ne

- **GetKeySucceeded** - Obaveštava da li je poziv upućen API usluzi Office licenciranja radi preuzimanja šifre bio uspešan

- **GetNextUserLicenseResult** - Obaveštava da li je moderan paket licenci mogao da funkcioniše i da li je korisnik dobio licencu ili ne

- **InstallKeyResult** - Obaveštava o različitim razlozima zbog kojih se korisnik može nalaziti u lošem stanju, kao što je neuspela aktivacija ili neuspela instalacija šifre

- **NotInitializedBeforeWhileAdding** - Ovo je samo informativno i obaveštava da li je događaj dodat u mapu za upravljanje telemetrijom, a da nije izričito urađena registracija za to

- **NotInitializedBeforeWhileSending** - Ovo je samo informativno i obaveštava da li je pokušano slanje događaja, a da ranije nije urađena izričita registracija za to u mapi za upravljanje telemetrijom

- **SentOnDestruction** – Ovo je samo informativno i obaveštava da li je događaj dodat u mapu za upravljanje telemetrijom, a nije izričito poslat

- **Tag** - Koristi se da saopšti sa kog mesta u kodu je poslat događaj

- **VerifyEntitlementsResult** - Obaveštava o različitim stanjima u kojima se može nalaziti korisnik nakon provere valjanosti prava preuzetih iz Office usluge licenciranja

### <a name="officelicensingtelemetryflowsearchforbindingresult"></a>Office.Licensing.TelemetryFlow.SearchForBindingResult

OEM proizvođači prodaju računare koji dolaze sa sistemom Office (sa jednogodišnjom ili stalnom pretplatom).  Ovi Office proizvodi su plaćeni kada klijent kupi svoj računar. Mašine koje se podešavaju pomoću određenog reg.ključa (OOBEMode: OEMTA) možda su povezane Office povezivanjem.  Kada na takvim računarima pokrenemo Office, izvršavamo provere usluge da bismo videli da li je pronađen obavezujući Office ugovor za odgovarajući računar.

Ova aktivnost telemetrije prati tačke uspeha i neuspeha u pretraživanju obavezujućeg ugovora da bismo bili sigurni da računari koji ga imaju mogu uspešno da ga preuzmu i da su naše usluge ispravne.  Nakon provere sa našim uslugama, ova aktivnost ne prati računare za koje se ispostavi da nemaju nikakav obavezujući ugovor koji je povezan sa njima.

Prikupljaju se sledeća polja:

- **DexShouldRetry** – Signal da smo pronašli problem koji se može ponovo pokušati (internet i nijedan server nisu prestali sa radom)

- **GenuineTicketFailure** – Obaveštava nas o grešci HRESULT prilikom pokušaja preuzimanja originalnog Windows tiketa/šifre proizvoda (WPK) za računar.

- **PinValidationFailure** - Obaveštava nas zašto nije uspeo proces provere valjanosti pin-a. Moguće greške:
    - Blokirana geografska zona
    - Nevažeći format 
    - Nevažeći pin
    - Nevažeće stanje
    - Nevažeća verzija
    - Nepoznato
    - Iskorišćeno

- **PinValidationResult** - Obaveštava nas o rezultatu provere valjanosti pin-a za pin koji nismo uspeli da razbijemo.

- **Pkpn** - opseg pkpn-a kome pripada pin

- **Success** - Pokazuje da smo uspešno preuzeli važeći obavezujući Office ugovor (pin) za računar.

- **Tag** - Obaveštava kada smo prestali da pretražujemo obavezujući ugovor. Moguće oznake:
  - 0x03113809    Nema internet veze/usluge prilikom provere valjanosti PIN koda
  - 0x0311380a    Neuspeh provere valjanosti PIN koda, poslato pomoću polja „PinValidationFailure“
  - 0x0310410f    Uspeh, poslato pomoću polja „Success“
  - 0x0311380d    Greške kod kojih je moguć ponovni pokušaj (problemi sa internet vezom, nepoznate greške)
  - 0x0311380e    Greške kod kojih nije moguć ponovni pokušaj (ponuda obavezujućeg ugovora je istekla)
  - 0x0311380f    Druge greške (licenciranje nije moguće)
  - 0x03104111    Nije uspelo razbijanje Office pin-a, poslato pomoću polja „PinValidationResult“

- **WpkBindingFailure** – Obaveštava o kodu greške kod povezivanja Office PIN koda sa WPK-om računara.

### <a name="officelicensingtelemetryflowshowafodialogs"></a>Office.Licensing.TelemetryFlow.ShowAFODialogs

Nakon uspešnog pribavljanja važećeg Office pin-a koji je povezan sa računarom sa kojim dolazi Office paket, korisniku prikazujemo dijalog za prijavljivanje ili preuzimanje.  Kada se preuzme pin, prikazujemo dijalog za EULA ugovor.  U sklopu naše modernizacije Aktivacija za Office funkcije, osvežili smo dva dijaloga da bismo preneli više informacija o Office proizvodima koji dolaze sa računarom.  Ova telemetrija služi za praćenje da li funkcija smanjuje korisničke probleme u preuzimanju njihovog proizvoda, tako što prati tok i tačke izlaska iz procesa preuzimanja (koji dijalog je odbačen).

Prikupljaju se sledeća polja:

- **ActionActivate** – Signal da je korisnik kliknuo na dugme „Aktiviraj“.

- **ActionChangeAccount** – Signal da je korisnik kliknuo na hipervezu „Koristite drugi nalog“.

- **ActionCreateAccount** – Signal da je korisnik kliknuo na dugme „Kreiraj nalog“.

- **ActionSignIn** – Signal da je korisnik kliknuo na dugme „Prijavite se“.

- **CurrentView** – Tip dijaloga koji je korisnik zatvorio.

- **DialogEULA** – Signal da smo prikazali dijalog „Prihvatite EULA“. 

- **DialogRedemption** – Signal da smo prikazali dijalog „Aktivacija za Office iskorišćavanje“.

- **DialogSignIn** – Signal da smo prikazali dijalog „Aktivacija za Office prijavljivanje“.

- **EmptyRedemptionDefaults** – Signal da nismo uspeli da dobavimo informacije o podrazumevanom iskorišćavanju.
 
- **GetRedemptionInfo** – Signal da dobavljamo informacije o demografiji za iskorišćavanje PIN koda.

- **MalformedCountryCode** – Signal da je pozivni broj za zemlju koji je potreban za iskorišćavanje PIN koda pogrešno uobličen.

- **OExDetails** – Detalji o grešci koje dobijemo kada je odbačen dijalog za prijavljivanje sa identitetom.

- **OExType** – Tip greške koji dobijemo kada je odbačen dijalog za prijavljivanje pomoću identiteta.

- **Tag** – Obaveštava nas na kom koraku je korisnik izašao iz Aktivacija za Office procesa preuzimanja. Moguće oznake:
    - 0x0311380b    Korisnik je u dijalogu za preuzimanje odbacio dijalog za prijavljivanje pomoću identiteta
    - 0x0311380c    Nije uspelo automatsko učitavanje identiteta nakon korisničkog prijavljivanja iz dijaloga za preuzimanje
    - 0x03113810    Nije uspelo učitavanje demografskih informacija o nalogu (državni kôd, jezik,     valuta, ponuda za probnu verziju i željene postavke za reklame)
    - 0x03113805    Korisnik je u dijalogu za prijavljivanje odbacio dijalog za prijavljivanje pomoću identiteta
    - 0x03113806    Nije uspelo automatsko učitavanje identiteta nakon korisničkog prijavljivanja iz dijaloga za prijavljivanje
    - 0x03113807   Nije uspelo automatsko učitavanje identiteta
    - 0x03113811    Korisnik je zatvorio dijalog za prijavljivanje/preuzimanje
    - 0x03113812    Korisnik je zatvorio dijalog za prihvatanje EULA ugovora
    - 0x03113808    Korisnik je prihvatio EULA ugovor
    - 0x03113811      Korisnik je zatvorio dijalog
    - 0x2370e3a0      Korisnik je zatvorio dijalog
    - 0x2370e3c1      Idi na veb radi iskorišćavanja PIN koda
    - 0x2370e3a1      Idi na veb radi iskorišćavanja PIN koda
    - 0x2370e3c0      Petlja sekvence dijaloga do koje je doveo korisnik koji se kretao napred-nazad u toku dijaloga
    - 0x2370e3a3      Korisnik je kliknuo na hipervezu „Ne sada“, koja preskače Aktivacija za Office ponudu za tu sesiju
    - 0x2370e3a2      Korisnik je kliknuo na hipervezu „Nikada ne prikazuj ovo“, koja onemogućava Aktivacija za Office ponudu


- **UseInAppRedemption** – Obaveštava nas da li zadržavamo korisnike u aplikaciji radi preuzimanja ili ih prebacujemo na veb da bi iskoristili svoj preuzeti pin (unapred popunjen).

- **UseModernAFO** – Obaveštava nas da li koristimo staru ili novu aktivaciju za Office iskustvo.

### <a name="officelicensingtelemetryflowshowtrybuydialogforoobe"></a>Office.Licensing.TelemetryFlow.ShowTryBuyDialogForOOBE

Kada novi računari imaju unapred instaliran sistem Office, a korisnici ne poseduju prava na njega, prikazujemo dijalog koji korisniku daje opciju da isproba, kupi ili unese šifru proizvoda da bi dobio licencu. Ovaj događaj prati da li je dijalog prikazan.  Ovaj događaj nam omogućuje da saznamo da li je dijalog prikazan korisniku kako bi isprobao, kupio ili uneo šifru proizvoda i tako određujemo da li je imao priliku da dobije licencu.

Prikupljaju se sledeća polja: 

- **ActiveView** - Obaveštava o ID dijaloga koji je prikazan korisniku

- **CurrentOOBEMode** – Obaveštava o unapred instaliranom režimu (režim OOBE, kao što je Aktivacija za Office, OEM, itd.)

- **NotInitializedBeforeWhileAdding** - Ovo je samo informativno i obaveštava da li je događaj dodat u mapu za upravljanje telemetrijom, a da nije izričito urađena registracija za to

- **SentOnDestruction** – Ovo je samo informativno i obaveštava da li je događaj dodat u mapu za upravljanje telemetrijom, a nije izričito poslat

- **ShowTryButton** - Obaveštava da li je korisniku prikazano dugme „Isprobaj“ u dijalogu ili ne

- **Tag** - Koristi se da saopšti sa kog mesta u kodu je poslat događaj

### <a name="officelicensingtelemetryflowtrialflow"></a>Office.Licensing.TelemetryFlow.TrialFlow

Ovaj događaj se pokreće kada korisnik bez licence, sa unapred instaliranim sistemom Office na računaru, pokušava da dobije probnu verziju.  Koristi se da se vidi kojim putem će korisnik ići da bi dobio probnu verziju i da li je došlo do grešaka prilikom njenog preuzimanja putem kupovine u aplikaciji.  U zavisnosti od korisničke radnje i rezultata kupovine u aplikaciji, korisnik može da ostane bez licence.

Prikupljaju se sledeća polja:

- **HasConnectivity** – Obaveštava da li korisnik ima vezu sa internetom i u slučaju da nema, može koristiti grejs licencu tokom pet dana ili se može naći u režimu smanjene funkcionalnosti

- **InAppTrialPurchase** – Saopštava da li je probni paket omogućen za pokretanje SDK-a za kupovinu u prodavnici da bi se uhvatio PI i kupila probna verzija unutar aplikacije *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali možda će se i dalje prikazivati u starijim izdanjima.]*

- **IsRS1OrGreater** - Obaveštava da li je OS verzija novija od verzije RS1 ili ne, pošto SDK za kupovinu u prodavnici treba koristiti samo ako jeste

- **NotInitializedBeforeWhileAdding**: Ovo je samo informativno i obaveštava da li je događaj dodat u mapu za upravljanje telemetrijom, a da nije izričito urađena registracija za to

- **OEMSendToWebForTrial** - Obaveštava da li je probni paket omogućen za prebacivanje korisnika na veb da bi preuzeli probnu verziju

- **StoreErrorConditions** – Saopštava različite uslove u kojima je moguć neuspeh SDK-a za kupovinu u prodavnici *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali možda će se i dalje prikazivati u starijim izdanjima.]*

- **StoreErrorHResult** – Saopštava kôd greške koji je dobijen iz SDK-a za kupovinu u prodavnici *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali možda će se i dalje prikazivati u starijim izdanjima.]*

- **StorePurchaseStatusResult** – Saopštava rezultat pozivanja SDK-a za kupovinu u prodavnici i da li je korisnik obavio kupovinu, čime se određuje da li korisnik treba da dobije licencu za korišćenje sistema Office *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali možda će se i dalje prikazivati u starijim izdanjima.]*

- **Tag** – Koristi se da saopšti sa kog mesta u kodu je poslat događaj

- **UserSignedInExplicitly** – Saopštava da li se korisnik eksplicitno prijavio i u tom slučaju preusmeravamo korisnike na veb za probnu verziju *[Ovo polje je uklonjeno iz trenutnih izdanja sistema Office, ali možda će se i dalje prikazivati u starijim izdanjima.]*

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Ako iz nekog razloga nismo u mogućnosti da licenciramo korisnika, instaliramo „grejs“ ključ i šaljemo signal koji to označava. Iz nekog razloga, ako ne možemo da licenciramo korisnika, instaliramo grejs ključ i šaljemo ovaj signal koji označava. 

Prikupljaju se sledeća polja:

  - **OpportunisticTokenRenewalAttempted** - Ukazuje na to da smo pokušali oportunističku obnovu za korisnika koji se nalazi u režimu aktivacije deljenog računara

  - **ReArmResult** - Ukazuje na rezultat vraća instaliranog ključa u početno stanje, što može da produži rok trajanje trenutne licence

### <a name="officesetupofficesdxlog"></a>Office.SetupOffice.Sdx.Log 

Ovaj događaj se pokreće kada iskoristimo Office ponudu za korisnika koji je kupio uređaj u paketu sa OEM ovlašćenjem ili je uneo šifru proizvoda. Ovi podaci se koriste za opšte poruke evidencije.

Prikupljaju se sledeća polja:

- **Ctid (Data_Ctid)** - Korelacioni ID se koristi za povezivanje različitih evidencija u okviru jedne sesije otkupa.

- **Okruženje (Data_ Environment)** - okruženje za projektante (Pr, Edog, Prod, Int).

- **Poruka (Data_Message)** - Poruka evidencije od setup.office.com. Na primer, "slika "." ne može da se učita,koristi se /img/spinner.csv' i cdn."

- **Tip (Data_Type)** - tip poruke evidencije (greška, upozorenje, Informacije)


### <a name="onenoteenrollmentresult"></a>OneNote.EnrollmentResult
 
Ovaj događaj evidentira status posle prijave na Intune.  Ovaj slučaj je specifičan za naloge omogućene za Intune.
 
Prikupljaju se sledeća polja:
 
- **EnrollmentResult** - Rezultat prijave na Intune

### <a name="skuproductpricenullevent"></a>SKU.PRODUCT.PRICE.NULL.EVENT

Ovaj događaj se koristi za evidentiranje događaja radi kvantifikovanja uticaja greške zbog koje korisnici danas vide "Bez vrednosti" umesto cene na SKU ekrana za biranje.Greška će se dalje dijagnostikovati kako bi se utvrdila ispravka. 

Prikupljaju se sledeća polja:

- **PriceNotFound** – Cene se ne mogu naći u prodavnici.

- **StoreNotInitilized** – Kada prodavnica nije uspešno pokrenuta.


## <a name="microsoft-autoupdate-mau-events"></a>Događaji aplikacije Microsoft AutoUpdate (MAU)

### <a name="additionalappinfoinvalidpreference"></a>additionalappinfo.invalidpreference

Ovaj događaj prijavljuje nevažeći skup željenih opcija za prikazivanje više informacija u pogledu prestanka pružanja usluge za proizvod. Ove informacije koristimo da bismo savetovali klijente da postave ispravne željene opcije kako bi videli dodatne informacije.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **Reason** – Detalji nevažećeg unosa u željenim opcijama

- **SessionId** – Identifikator sesije

### <a name="appdelegatelaunch"></a>appdelegate_launch

Ovaj događaj pokazuje da je došlo do pokušaja pokretanja aplikacije. Evidentiramo njegov rezultat (otkazivanje ili uspeh). Koristimo ga da bismo identifikovali slučajeve kada MAU ne uspe da se pokrene

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppversionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Skup statičkog teksta koji pokazuje status pokretanja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="appdelegateterminate"></a>appdelegate.terminate

Ovaj događaj pokazuje da je došlo do skladnog izlaska iz aplikacije. Koristimo ga da bismo razlikovali skladne izlaske iz aplikacije od neskladnih.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike
    
- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja
    
- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst koji pokazuje da je Microsoft Autoupdate prekinut.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="appinstallconnecttoxpc"></a>appinstall.connecttoxpc

Ovaj događaj pokazuje da je došlo do grešaka prilikom povezivanja sa pomoćnikom za MAU (komponentom koja instalira aplikaciju).  On pokazuje potencijalno oštećenje aplikacije MAU. Uređaj neće moći da instalira ispravke.

Prikupljaju se sledeća polja:    

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o grešci problema sa vezom.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="appinstalllogscanned"></a>appinstall.logscanned

Ovaj događaj se koristi za utvrđivanje da li je datoteka evidencije uspešno obrađena. Koristimo ovaj događaj da bismo otkrili i rešili probleme koji se javljaju tokom instalacije aplikacije. 
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Izveštaji o greškama pronađenim tokom instalacije aplikacije i/ili o statusu dovršenja skeniranja 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="appinstallxpcremoteobjecterror"></a>appinstall.xpcremoteobjecterror

Ovaj događaj izveštava o grešci koja je pronađena prilikom pokušaja povezivanja sa „Privileged Helper“ alatkom putem XPC veze. Ovaj događaj koristimo za praćenje i rešavanje mogućih problema sa instalacijom MAU-a.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o prirodi proxy greške do koje je došlo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="appregistryconfig"></a>appregistry.config

Ovaj događaj prijavljuje greške na koje se naišlo tokom učitavanja informacija o registratoru aplikacija. Ovaj izveštaj koristimo da bismo savetovali IT administratore o tačnom formatu podešavanja registracija klijentskih aplikacija.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o prirodi greške na koju se naišlo u registraciji aplikacija.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="appregistryinfo"></a>appregistry.info

Ovaj događaj pokazuje da je aplikacija pokrenuta. Koristimo ga kako bismo naveli aplikacije za koje MAU kontroliše ažuriranja, broj dostupnih kopija, kao i verziju i instalacionu lokaciju (podrazumevanu ili drugu).

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o listi identifikatora koje aplikacija koristi za registrovanje sa Microsoft Autoupdate uslugama i broju instalacija registrovanih za aplikaciju.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="appregistryremove"></a>appregistry.remove

Ovaj događaj pokazuje da je pokušano uklanjanje aplikacije sa liste aplikacija kojima upravlja MAU. Koristimo ga da bismo potvrdili da MAU upravlja samo aplikacijama koje je sam izdao (ovde ne bi trebalo da se pojavljuju aplikacije iz prodavnice AppStore).

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Ime i identifikator aplikacije koja se uklanja, bez obzira na to da li aplikacija i dalje postoji na registrovanoj lokaciji i to da li je instalirana iz prodavnice AppStore.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="catalogerrorsignature"></a>catalog.errorsignature

Ovaj događaj izveštava o različitim problemima sa preuzetim datotekama, uključujući potpis prodavca i nepodudaranje vrednosti heša u preuzetoj datoteci. Ovaj događaj koristimo za otkrivanje problema u skupu manifesta za objavljivanje za aplikacije.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **FileHash** – Vrednost heša preuzete datoteke

- **FileName** – Ime datoteke koje prikazuje nepodudaranje vrednosti heša

- **HashInCatalog** – Stavka vrednosti heša u odgovarajućoj datoteci kataloga

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – sadrži informacije o aplikaciji koja prijavljuje problem

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="cataloginvalid"></a>catalog.invalid

Ovaj događaj beleži uslov greške koji upućuje na preuzet nevažeći katalog manifesta. Koristimo ovaj događaj da bismo se uverili da u objavljenim datotekama manifesta nema grešaka. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **CatalogFile** – ime datoteke kataloga koja je izazvala stanje greške.

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme kada je primljena telemetrija

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="cloningtaskbegin"></a>cloningtask.begin

Ovaj događaj ukazuje na početak zadatka kloniranja pre ažuriranja aplikacije. Ovaj događaj koristimo zajedno sa događajem cloningtask.status da bismo utvrdili količinu neuspelih kloniranja kako bismo otkrili da li funkcija kloniranja treba da se ograniči na različitim kanalima korisnika.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku.


### <a name="cloningtaskhelpertoolconnection"></a>cloningtask.helpertoolconnection

Ovaj događaj beleži probleme sa instaliranjem na klonu (to jest, ne uspemo da se povežemo sa pomoćnikom da bismo primenili ažuriranje ili se povežemo, ali pomoćnik ne može da primeni ažuriranje). Ako nam se prijavi zapis, to znači da instaliranje na klonu nije uspelo i da mora da se vrati na ažuriranje na licu mesta.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID za identifikovanje pojedine aktivnosti ažuriranja i proxy grešku prijavljenu tokom procesa kloniranja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="cloningtaskstatus"></a>cloningtask.status

Ovaj događaj ukazuje na status procesa kloniranja za aplikaciju koju treba ažurirati. Ovaj događaj koristimo da bismo utvrdili stopu uspešnosti, kao i tipove grešaka na koje se naišlo i koje dovode do otkazivanja. Ovaj događaj se koristi da bi se utvrdili da li funkcija kloniranja treba da se ograniči na različitim kanalima korisnika.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Niska sadrži informacije o grešci na koju se naišlo tokom zadatka kloniranja.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Predstavljanje niske Bulove promenljive.

- **UpdateID** – Identifikator za ispravku.

### <a name="cloningtaskstatusfinish"></a>cloningtask.status.finish

Ovaj događaj izveštava o dovršenju zadatka „kloniranja“. Ovaj događaj čini deo izveštaja o levku ispravke i koristimo za utvrđivanje ispravnosti ispravki aplikacije.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Indikator da li je zadatak kloniranja uspeo

- **UpdateID** – Identifikator ispravke.


### <a name="configurationchannel"></a>configuration.channel

Ovaj događaj beleži pokušaje promene kanala (grupe korisnika) u aplikaciji MAU.  Koristimo ga da bismo evidentirali pokušaje i njihove rezultate (uspeh ili otkazivanje).

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime izabranog kanala.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="configurationmetadata"></a>configuration.metadata

Ovaj događaj se evidentira svaki put prilikom pokretanja aplikacije MAU. To je tip događaja MAU signala za povezivanje

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst koji pokazuje da se pokreću pojedinačni metapodaci ili konfiguracija.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije.

### <a name="configurationsystemversion"></a>configuration.systemVersion

Ovaj događaj ukazuje na to da pokušaj preuzimanja verzije sistema nije uspeo. On takođe sadrži informacije o informacijama koje je Microsoft automatsko ažuriranje (MAU) uspelo da prikupi iz sistema. Ovaj događaj koristimo da bismo utvrdili da li MAU treba da se bavi greškama. Imajte u vidu da se verzija sistema koristi da bi se utvrdilo da li ispravka može da se primeni na uređaj klijenta.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o grešci na koju se naišlo tokom preuzimanja niske verzije sistema macOS.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="controlleralertmanagerreinstallresponse"></a>controller.alertmanager.reinstallresponse

Ovaj događaj pokazuje da je MAU ušao u stanje kojem je postao neupotrebljiv/nepopravljiv i mora da se ponovo instalira. On označava nepopravljivu grešku koja zahteva intervenciju korisnika.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveravanje da li postoje ažuriranja.

- **Payload** – Sadrži nabrojani izbor korisnika.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controlleralertmanagertmpdiskfull"></a>controller.alertmanager.tmpdiskfull

Ovaj događaj pokazuje da je otkriveno da nema dovoljno prostora na disku. Ne možemo da instaliramo ispravke jer nema dovoljno prostora na disku.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controlleralertmanagertmpdiskfullretry"></a>controller.alertmanager.tmpdiskfullretry

Ovaj događaj pokazuje da je pokrenut ponovni pokušaj instaliranja ispravke posle otkrivanja da nema dovoljno prostora na disku. Ponovo pokušavamo da pokrenemo instaliranje kada ne uspemo da instaliramo ispravke jer nema dovoljno prostora na disku.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije
    

### <a name="controlleralertmanagertmpdiskfullretrycancel"></a>controller.alertmanager.tmpdiskfullretrycancel

Ovaj događaj pokazuje da je otkriveno da je otkazan ponovni pokušaj instaliranja posle otkrivanja da nema dovoljno prostora na disku. Koristimo ga kako bismo odredili da li je mehanizam vraćanja bio dovoljan da provede korisnika kroz proces ažuriranja kada je otkriveno da nema dovoljno prostora na disku.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke
    
- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllercheckwindownoupdatefoundok"></a>controller.checkwindow.noupdatefoundok

Ovaj događaj pokazuje da se proverom da li postoje ispravke nisu pronašle nikakve ispravke. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način, za optimizaciju opterećenja usluge i definisanje toga koliko često treba proveravati da li postoje ispravke. Želimo i da optimizujemo učestalost izdavanja na osnovu očekivanja korisnika u vezi sa ispravkama.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    

### <a name="controllercheckwindowupdatecheck"></a>controller.checkwindow.updatecheck

Ovaj događaj označava da je izvršena provera za ispravke. Koristimo ovaj događaj da bismo osigurali da se ispravno nude ažuriranja, da bismo optimizirali opterećenja usluga i definisali učestalost provere naših ažuriranja. Takođe želimo da optimizujemo svoj ritam izdanja na osnovu očekivanja korisnika od ažuriranja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja
    
- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllercheckwindowupdatecheckcancel"></a>controller.checkwindow.updatecheckcancel

Ovaj događaj označava da je postupak provere ažuriranja otkazan (bilo od strane korisnika ili sistema). Koristimo ovaj događaj da bismo osigurali da se ispravno nude ažuriranja, da bismo optimizirali opterećenja usluga i definisali učestalost provere naših ažuriranja. Takođe želimo da optimizujemo svoj ritam izdanja na osnovu očekivanja korisnika od ažuriranja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllercheckwindowupdatecheckcanceluser"></a>controller.checkwindow.updatecheckcanceluser

Ovaj događaj označava da je korisnik otkazao postupak provere ispravnosti. Koristimo ovaj događaj da bismo osigurali da se ispravno nude ažuriranja, da bismo optimizirali opterećenja usluga i definisali učestalost provere naših ažuriranja. Takođe želimo da optimizujemo svoj ritam izdanja na osnovu očekivanja korisnika od ažuriranja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije
    
- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllercheckwindowupdatesfound"></a>controller.checkwindow.updatesfound

Ovaj događaj označava da je proces provere ispravnosti rezultirao pronađenim ispravkama. Koristimo ovaj događaj da bismo osigurali da se ispravne ponude nude.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllercheckwindowuptodate"></a>controller.checkwindow.uptodate

Ovaj događaj pokazuje da tokom procesa provere da li postoje ispravke nisu pronađene ispravke jer su aplikacije na uređaju ažurirane. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowapplaunchwithpendingupdate"></a>controller.downloadwindow.applaunchwithpendingupdate

Ovaj događaj pokazuje da je pokrenuta aplikacija koja je u procesu preuzimanja ispravki. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način. Trebalo bi da sprečimo otvorene aplikacije da preuzimaju ispravke. Aplikacije moraju da se zatvore pre ažuriranja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese
    
- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindowcloseapplicationdialog"></a>controller.downloadwindow.closeapplicationdialog

Ovaj događaj pokazuje da je pokrenuta aplikacija koja je u procesu preuzimanja ispravki. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način. Trebalo bi da sprečimo otvorene aplikacije da preuzimaju ispravke. Aplikacije moraju da se zatvore pre ažuriranja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindowcurtasknull"></a>controller.downloadwindow.curtasknull

Ovaj događaj pokazuje da je došlo do neočekivane greške tokom pokušaja primene ispravke. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindowdownloadcancel"></a>controller.downloadwindow.downloadcancel

Ovaj događaj pokazuje da je korisnik otkazao proces preuzimanja.  Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Statički tekst. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindowdownloadfailed"></a>controller.downloadwindow.downloadfailed

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindowdownloadfailedok"></a>controller.downloadwindow.downloadfailedok

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke i da je korisnik obavešten. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način i da se korisniku pruža obaveštenje u slučaju otkazivanja.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowdownloadpathmissing"></a>controller.downloadwindow.downloadpathmissing

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način. Ovaj događaj pokazuje da nedostaje URL za preuzimanje.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowdownloadtasknull"></a>controller.downloadwindow.downloadtasknull

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način. Ovaj događaj pokazuje da je zatraženo da Microsoft Autoupdate pauzira/nastavi preuzimanje, ali on nije mogao da pronađe odgovarajući menadžer za preuzimanje.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowfilesignaturenotverified"></a>controller.downloadwindow.filesignaturenotverified

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke. On pokazuje da Microsoft Autoupdate nije mogao da potvrdi da je ovu ispravku objavio Microsoft. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji sadrži URL za preuzimanje. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowinstallcomplete"></a>controller.downloadwindow.installcomplete

Ovaj događaj pokazuje da je završeno instaliranje svih ispravki koje nudi Microsoft Autoupdate. Koristimo ga da bismo obezbedili da se ispravke nude i preuzimaju na odgovarajući način. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi
    
- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindownetworkunavailablealert"></a>controller.downloadwindow.networkunavailablealert

Ovaj događaj označava da je mrežna povezanost izgubljena tokom preuzimanja ispravki. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindownetworkunavailablealertok"></a>controller.downloadwindow.networkunavailablealertok

Ovaj događaj pokazuje da je mrežna veza izgubljena prilikom preuzimanja ispravki. Takođe pokazuje da je korisnik obavešten o ovoj grešci. Ovaj događaj koristimo za obezbeđivanje da proces ažuriranja funkcioniše na očekivani način i za rešavanje grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerdownloadwindownoconnectionok"></a>controller.downloadwindow.noconnectionok

Ovaj događaj pokazuje da je mrežna veza izgubljena prilikom preuzimanja ispravki. Takođe pokazuje da je korisnik obavešten o ovoj grešci. Ovaj događaj koristimo za obezbeđivanje da proces ažuriranja funkcioniše na očekivani način i za rešavanje grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowrepairrequired"></a>controller.downloadwindow.repairrequired

Ovaj događaj pokazuje da proces ažuriranja nije uspeo. On pokazuje i da je ažuriranje završeno, ali da je Microsoft Autoupdate pronašao problem sa ažuriranom aplikacijom i da je neophodna popravka. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja
    
- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="controllerdownloadwindowupdateaborted"></a>controller.downloadwindow.updateaborted

Ovaj događaj pokazuje da se odustalo od procesa ažuriranja. On pokazuje i da je daemon već pokrenuo ažuriranje i da je korisnik kliknuo na dugme „U redu“ kako bi odustao od preuzimanja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowupdatefailed"></a>controller.downloadwindow.updatefailed

Ovaj događaj označava da jedno ili više ažuriranja iz trenutne serije nije uspelo. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowupdatesuccessful"></a>controller.downloadwindow.updatesuccessful

Ovaj događaj označava da su sva ažuriranja iz trenutne serije bila uspešna. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowuserpaused"></a>controller.downloadwindow.userpaused

Ovaj događaj označava da su sva ažuriranja iz trenutne serije bila uspešna. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerdownloadwindowuserresumed"></a>controller.downloadwindow.userresumed

Ovaj događaj označava da je postupak ažuriranja preuzimanja uspešno nastavljen nakon ulaska u pauzu. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllermainwindowsetautomaticchecking"></a>controller.mainwindow.setautomaticchecking

Ovaj događaj označava da je uređaj prijavljen u režim automatskog ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

 - **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – tekst koji ukazuje na prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllermainwindowsetautomaticdownloadinstall"></a>controller.mainwindow.setautomaticdownloadinstall

Ovaj događaj označava da je uređaj prijavljen u režim automatskog ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllermainwindowsetmanualchecking"></a>controller.mainwindow.setmanualchecking

Ovaj događaj označava da je uređaj prijavljen u režim ručnog ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllertemplateawindowcancel"></a>controller.templateawindow.cancel

Ovaj događaj označava da je korisnik izabrao da otkaže ili zanemari pruženu poruku upozorenja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllertemplateawindowenroll"></a>controller.templateawindow.enroll

Ovaj događaj označava da je korisnik odabrao da sledi obezbeđenu preporuku upozorenja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke
    
- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije



### <a name="controllertemplateawindowinstall"></a>controller.templateawindow.install

Ovaj događaj pokazuje da je korisnik odabrao da prihvati prikazanu preporuku upozorenja u vezi sa radnjom pokretanja instaliranja softvera. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerupdatewindowbegindownloadingapps"></a>controller.updatewindow.begindownloadingapps

Ovaj događaj označava da je preuzimanje ažuriranja započeto kroz prozor za ažuriranje. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži rečnik dostupnih paketa ispravki i naznaku toga da li je korisnik izabrao da instalira tu stavku.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerupdatewindownetworkretry"></a>controller.updatewindow.networkretry

Ovaj događaj pokazuje da je pokrenut ponovni pokušaj na listu sa ispravkama zbog otkazivanja mreže. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerupdatewindownetworkretrycancel"></a>controller.updatewindow.networkretrycancel

Ovaj događaj pokazuje da ponovni pokušaj nije mogao da se pokrene na listu sa ispravkama zbog otkazivanja mreže. On pokazuje da je korisnik izabrao da otkaže ažuriranja kada je dobio upozorenje da mreža postaje nedostupna. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerupdatewindownetworkunavailable"></a>controller.updatewindow.networkunavailable

Ovaj događaj pokazuje da je mrežna veza iznenada izgubljena. On pokazuje da server nije dostupan prilikom pokušaja preuzimanja paketa ispravki. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerupdatewindownoupdateavailable"></a>controller.updatewindow.noupdateavailable

Ovaj događaj pokazuje da je izvršena provera da li postoje ispravke koja je otkrila da ne postoje dostupne ispravke. On pokazuje da Microsoft Autoupdate nije pronašao dostupne ispravke. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerupdatewindownoupdatestoselect"></a>controller.updatewindow.noupdatestoselect

Ovaj događaj pokazuje da je došlo do greške koja je izazvala to da lista ispravki bude prazna. On pokazuje da Microsoft Autoupdate prikazuje prazan list sa ispravkama. To ne bi trebalo da se dešava. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="controllerupdatewindowupdateavailable"></a>Controller.UpdateWindow.UpdateAvailable

Ovaj događaj pokazuje da je izvršena provera da li postoje ispravke koja je otkrila da se ispravke nude. Koristimo ga da bismo odredili da li se ispravke nude korisniku na odgovarajući način da ih vidi, da li se prikazuju odgovarajuće ispravke ili da li blokiranje ažuriranja funkcioniše na očekivani način. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži rečnik dostupnih paketa ispravki i status izbora korisnika za svaki od njih.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="controllerupdatewindowupdateavailablecancel"></a>controller.updatewindow.updateavailablecancel

Ovaj događaj pokazuje da je korisnik otkazao kada smo prikazali list sa ispravkama koji navodi ispravke. Koristimo ga da bismo objasnili razloge zbog kojih se ažuriranje nije izvršilo (to jest, korisnik je to svojevoljno otkazao). Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadactorpause"></a>downloadactor.pause

Ovaj događaj pokazuje da je korisnik uputio zahtev da se preuzimanje pauzira. Koristimo ga da bismo objasnili razloge zbog kojih se ažuriranja očigledno nisu završila. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadactorredirect"></a>downloadactor.redirect

Ovaj događaj pokazuje da je agent preuzimača usmeren na krajnju tačku koja izdaje preusmeravanje URL adrese za zahtev za preuzimanjem. Koristimo ga da bismo objasnili razloge otkazivanja preuzimanja i dijagnostikovali probleme sa proxy serverom. Može da pomogne i prilikom dijagnostikovanja razloga zbog kojih je primećeno da korisnici instaliraju starije verzije. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži preusmereni URL. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="downloadactorresume"></a>downloadactor.resume

Ovaj događaj pokazuje da je korisnik uputio zahtev da se nastavi pauzirano preuzimanje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadactorresumeerror"></a>downloadactor.resumeerror

Ovaj događaj pokazuje da je korisnik uputio zahtev da se nastavi pauzirano preuzimanje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži putanju URL adrese za preuzimanje. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="downloadactorstatus"></a>downloadactor.status

To evidentira da postoje pokušaji dobavljanja pratećih datoteka i njihove rezultate (uspeh ili otkazivanje). Želimo da znamo koje se pomoćne datoteke i koji se paketi dobavljaju. Dobavljanje pogrešne datoteke može da ukazuje na problem sa verzijom/pomoćnom datotekom. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži URL za preuzimanje i kôd greške u slučaju otkazivanja. URL za preuzimanje je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestconfiguration"></a>downloadmanifest.configuration

Ovaj događaj prijavljuje grešku sa konfiguracijom Microsoft automatskog ažuriranja (MAU) – bilo da je u pitanju podešavanje prilagođenog servera u željenim postavkama ili u definicijama krajnje tačke u pomoćniku za ažuriranje u instaliranim MAU komponentama. Ovaj događaj koristimo da bismo savetovali IT administratore da postave ispravne krajnje tačke servera manifesta.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **Payload** – Ukazuje na to da li se greška nalazi u podešavanju prilagođenog servera ili u instaliranim MAU komponentama

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestdownloadcatalogfail"></a>downloadmanifest.downloadcatalogfail

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja. Evidentira se datoteka čije preuzimanje nije uspelo. Želimo da znamo koje se pomoćne datoteke i koji se paketi dobavljaju. Neuspešno preuzimanje manifesta može da ukazuje na otkazivanje prilikom generisanja pomoćne datoteke verzije, grešku u konfiguraciji sistema CDN, grešku u konfiguraciji klijenta ili grešku na mreži. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="downloadmanifestdownloadcatalogsuccess"></a>downloadmanifest.downloadcatalogsuccess

Ovaj događaj pokazuje da je datoteka uspešno preuzeta. Neuspešno preuzimanje manifesta može da ukazuje na otkazivanje prilikom generisanja pomoćne datoteke verzije, grešku u konfiguraciji sistema CDN, grešku u konfiguraciji klijenta ili grešku na mreži. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestdownloadfail"></a>downloadmanifest.downloadfail

Ovaj događaj pokazuje da je došlo do greške prilikom preuzimanja. Evidentira se datoteka manifesta ili paketa čije preuzimanje nije uspelo, kao i detalji greške. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestdownloadfromurl"></a>downloadmanifest.downloadfromurl

Ovaj događaj pokazuje da je započeto preuzimanje datoteke kataloga. Evidentiramo URL sa kojeg se preuzima datoteka kataloga. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestdownloading"></a>downloadmanifest.downloading

Ovaj događaj pokazuje da je započeto preuzimanje datoteke kataloga. Evidentiramo URL sa kojeg se preuzima datoteka kataloga. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestdownloadsuccess"></a>downloadmanifest.downloadsuccess

Ovaj događaj pokazuje da je uspelo preuzimanje XML datoteke i datoteke kataloga. Evidentiramo URL sa kojeg se preuzima datoteka. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="downloadmanifestdownloadurl"></a>downloadmanifest.downloadurl

Ovaj događaj pokazuje da je upućen zahtev za preuzimanje datoteke. Evidentiramo URL sa kojeg se preuzima datoteka. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži kôd greške prilikom preuzimanja i URL za preuzimanje datoteke. To je Microsoft lokacija za preuzimanje kada kanal nije podešen na opciju „Prilagođeno“. Ta vrednost je postavljena na opciju „Prilagođena lokacija“ za prilagođeni kanal.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestfilenameerror"></a>downloadmanifest.filenameerror

Ovaj događaj označava da je došlo do neočekivane greške. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestinvalidhash"></a>downloadmanifest.invalidhash

Ovaj događaj označava da sigurnosna provera naših datoteka nije uspela. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime preuzete datoteke sa nevažećom heš vrednošću.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestmissingdaemon"></a>downloadmanifest.missingdaemon

Ovaj događaj pokazuje da je korisnik pokušao da proveri da li postoje ispravke i otkrili smo da nedostaje osnovna komponenta (daemon) aplikacije MAU. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifestsignatureerror"></a>downloadmanifest.signatureerror

Ovaj događaj označava da verifikacija potpisa koda nije uspela za paket. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime preuzete datoteke sa nevažećom heš vrednošću.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmanifeststatus"></a>downloadmanifest.status

Ovaj događaj evidentira rezimirane agregirane podatke o pokušajima/otkazivanjima tokom procesa preuzimanja za datoteke manifesta i paketa. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije koje obuhvataju URL (Microsoft adresu), prefiks datoteke koja se preuzima, sve greške na koje se naišlo itd.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmgrdownloadend"></a>downloadmgr.downloadend

Ovaj događaj beleži marker koji označava da je proces preuzimanja završen sam. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije koje obuhvataju URL (Microsoft adresu), prefiks datoteke koja se preuzima, sve greške na koje se naišlo itd.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadmgrdownloadstart"></a>downloadmgr.downloadstart

Ovaj događaj beleži ažuriranje koje će se preuzeti. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime ispravke koja se preuzima.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="downloadtaskdownloadbegin"></a>downloadtask.downloadbegin

Ovaj događaj ukazuje na početak aktivnosti preuzimanja za ispravku aplikacije. Ovo čini deo levka ispravke i koristimo ga za utvrđivanje ispravnosti ispravki aplikacije.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **BundleVersion** – Verzija aplikacije koja se ažurira

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **PreviousUpdateID** – Identifikator za ispravku aplikacije

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdatePkg** – Ime paketa ispravki koji se primenjuje

- **UpdateVersion** – Verzija aplikacije nakon ažuriranja


### <a name="downloadtaskdownloadfailure"></a>downloadtask.downloadfailure

Ovaj događaj evidentira to da je došlo do greške prilikom preuzimanja datoteke paketa. Evidentiramo putanju ispravke i grešku. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije koja ima neuspešno preuzimanje.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Greška uočena tokom preuzimanja.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime ispravke koja se preuzima i uočenu grešku. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke koja se preuzima.


### <a name="downloadtaskdownloadsuccess"></a>downloadtask.downloadsuccess

Uspešno preuzimanje datoteke paketa. Evidentiramo putanju ispravke koja se koristi. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži putanju ispravke za uspešno preuzimanje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator preuzete ispravke.

### <a name="downloadtaskupdatertypeerror"></a>downloadtask.updatertypeerror

Ovaj događaj prijavljuje grešku tipa programa za ažuriranje u preuzetoj datoteci manifesta. Ovaj događaj koristimo za obaveštavanje vlasnika datoteke manifesta kako bi greška mogla da se ispravi.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdaterType** – Tip programa za ažuriranje navedenog u preuzetoj datoteci manifesta

- **UpdateURL** – URL paketa ispravki koji treba da se primeni

### <a name="downloadtaskurlerror"></a>downloadtask.urlerror

Ovaj događaj prijavljuje grešku u URL adresi navedenoj u preuzetoj datoteci manifesta. Ovaj događaj koristimo za obaveštavanje vlasnika datoteke manifesta kako bi greška mogla da se ispravi.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **Error** – Ukazuje na prirodu greške na koju se nailazi

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateURL** – URL paketa ispravki koji treba da se primeni

### <a name="fbachangelastupdate"></a>fba.changelastupdate

Ovaj događaj prijavljuje kada Microsoft automatsko ažuriranje (MAU) proveri da li postoje ispravke. Ovaj događaj koristimo za otklanjanje grešaka kada određenom uređaju nije ponuđena ispravka tokom dužeg vremenskog perioda.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **Payload** – Sadrži datum i vreme kada je MAU proverio da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbacheckforupdate"></a>fba.checkforupdate

Ovaj događaj označava da proces u pozadini proverava ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbacheckforupdateskip"></a>fba.checkforupdateskip

Ovaj događaj označava da je pozadinski proces preskočio ažuriranje zbog otvaranja MAU GUI. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbaforceinstallmsgsent"></a>fba.forceinstallmsgsent

Ovaj događaj ukazuje na to da je nametnuta ispravka pokrenuta iz korisničkog interfejsa. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbaforceupdatecheck"></a>fba.forceupdatecheck

Ovaj događaj ukazuje na to da je provera ispravke nametnuta. Ovaj događaj koristimo da bismo utvrdili količinu provera nametnutih ispravki do kojih dolazi izvan uobičajenog ciklusa provere ispravki.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbaguiappopen"></a>fba.guiappopen

Ovaj događaj ukazuje na to da se korisnički interfejs pokreće u okviru režima automatske provere zato što je aplikacija sa primenljivom ispravkom trenutno otvorena. Ovaj događaj se koristi za utvrđivanje količine pokretanja korisničkog interfejsa iz režima automatske provere za budući razvoj funkcija.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbainstallpending"></a>fba.installpending

Ovaj događaj ukazuje na to da je Microsoft automatsko ažuriranje (MAU) poslalo obaveštenje u vezi sa ispravkama na čekanju. Ovaj događaj se koristi za utvrđivanje količine ispravki koje su pokrenute iz korisničkih obaveštenje i koristi se za poboljšanje korisničkog iskustva tako što se smanjuju prekidi korisnika u budućim izdanjima.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbalaunch"></a>fba.launch

Ovaj događaj ukazuje na početak rada Microsoft pomoćnika za ažuriranje uz metod pokretanja. Ovaj događaj se koristi za utvrđivanje da li je Microsoft Update pomoćnik pokrenut u pogrešnom kontekstu.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbalaunchbyagent"></a>fba.launchbyagent

Ovaj događaj ukazuje na to da je Microsoft Update pomoćnik pokrenut pomoću agenta za pokretanje. Ovaj događaj se koristi za utvrđivanje obima programa Microsoft Update pomoćnik koji se pokreće iz korisničkog interfejsa za budući razvoj.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbalaunchfromprotocol"></a>fba.launchfromprotocol

Ovaj događaj ukazuje na to da je Microsoft Update pomoćnik pokrenut pomoću protokola URL protokola. Ovaj događaj se koristi za utvrđivanje obima Microsoft Update pomoćnika koje se pokreće preko URL adrese za buduće razvoj.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o URL šemi i URL hostu

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbalaunchgui"></a>fba.launchgui

Ovaj događaj ukazuje na to da pomoćnik za Microsoft Update pokušava da pokrene grafički korisnički interfejs (GUI). Ovaj događaj se koristi za utvrđivanje obima pokretanja korisničkog interfejsa iniciran od usluge Microsoft Update pomoćnik, da bi pomogao u budućim razvojem, uključujući smanjenje broja korisnika od čestih pokretanja korisničkog interfejsa.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbalaunchstatus"></a>fba.launchstatus

Ovaj događaj evidentira MAU-ove kvarove demona prilikom pokušaja pokretanja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Sadrži OSStatus (kôd Apple statusa) koji odražava status pokretanja.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži status operativnog sistema (kôd Apple statusa) koji pokazuje status pokretanja. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulov znak niske koji ukazuje na to da li je MAU daemon proces uspešno pokrenut.


### <a name="fbamausilentupdate"></a>fba.mausilentupdate

Ovaj događaj ukazuje na to da pomoćnik za Microsoft Update iniciraju tihe ispravke. Ovaj događaj se koristi za utvrđivanje obima ispravki koji su primenjeni bez intervencije korisnika, da biste pomogli u poboljšanjima korisnika pomoću korisničkog iskustva.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije
 
- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – statični tekst *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali može se i dalje pojaviti u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **Reason** – Statični tekst koji ukazuje na to da tiho ažuriranje ne može da se nastavi zato što je korisnički interfejs otvoren

- **SessionId** – Identifikator sesije

### <a name="fbamoreinfofromappnotification"></a>fba.moreinfofromappnotification

Ovi izveštaji o događaju se izveštavaju o informacijama koje registrovana aplikacija usmjeravaju putem Microsoft automatskog ažuriranja (MAU). Na primer, poruke na kraju usluge se guraju kroz MAU-ove obaveštenja. Koristite ovaj događaj da biste utvrdili količinsko prikazivanje uređaja koji prikazuju ovo određeno obaveštenje, da biste utvrdili uspeh širenja informacija.

Prikupljaju se sledeća polja:

- **AdditionalInfoID** – Jedinstveno identifikuje „Više informacija“ koje se prosleđuju kroz MAU.

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **NotificationEvent** – Statički tekst koji ukazuje na tip obaveštenja koji se primenjuje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbamultipledaemon"></a>fba.multipledaemon

Ovaj događaj ukazuje na to da je otkrivena još jedna instanca Microsoft Update pomoćnika i da će trenutna instanca biti prekinuta. Koristite ovaj događaj da biste utvrdili količinsko korišćenje uređaja koji pokušava da pokrene više instanci pomoćnika za ažuriranje i dizajnirate rešenje ako treba da se pojavi.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbanofifyappclosed"></a>fba.nofifyappclosed

Ovaj događaj ukazuje na to da pomoćnik Microsoft Update šalje obaveštenje za ispravke na čekanju zato što nisu otvorene registrovane aplikacije i ispravke mogu da se nastavljaju bez prekida korisnika. Koristite ovaj događaj da biste utvrdili količinske ispravke koje mogu da se primene, ali treba nam radnja korisnika da bi to uradili. Ovaj događaj se koristi da bi se podstaklo poboljšanje korisničkog iskustva.

Prikupljaju se sledeća polja: 
    
- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi
    
- **AppVersionLong** – Verzija aplikacije
    
- **Channel** – Željene opcije za korisnike
    
- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **DeviceID** – Identifikator uređaja
    
- **DeviceInfo_Model** – Model hardvera uređaja
    
- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)
    
- **DeviceInfo_OsBuild** – Verzija operativnog sistema
    
- **Event_ReceivedTime** – Vreme prijema telemetrije
    
- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira
    
- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 
    
- **HowToCheck** – Kako proveriti postavku
    
- **Payload** – Statički tekst
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese
    
- **SessionId** – Identifikator sesije

### <a name="fbanofifyappopen"></a>fba.nofifyappopen

Ovaj događaj ukazuje na to da pomoćnik Microsoft Update šalje obaveštenje za ispravke na čekanju zato što postoje otvorene aplikacije i ispravke, zahtijevaju aplikacije zatvorenim da bi bile nastavljene.  Koristite ovaj događaj da biste utvrdili količinsko ažuriranje koje zahtijeva intervenciju korisnika.  Ovaj događaj se koristi da bi se podstaklo poboljšanje korisničkog iskustva.

Prikupljaju se sledeća polja:  

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi
    
- **AppVersionLong** – Verzija aplikacije
    
- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbasettimerfail"></a>fba.settimerfail  

Ovaj događaj označava neuspeli pokušaj za postavljanje brojača za pokretanje budućeg ažuriranja. Ovaj događaj je kritičan i koristite ovaj događaj da biste utvrdili količinstvo neuspešnih grešaka razvijanju rada ako je potrebno.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o vremenu poslednjeg ažuriranja i kalendaru koji se koristi

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateoptin"></a>fba.silentupdateoptin

Ovaj događaj označava da se korisnik uključuje u nečujna ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbaskipforcedupdate"></a>fba.skipforcedupdate

Ovaj događaj znači da je prisilna provera ažuriranja preskočena zbog otvorenih aplikacija. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbastartforcedupdate"></a>fba.startforcedupdate

Ovaj događaj pokazuje da je došlo do pokušaja primene nametnutog ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbaterminate"></a>fba.terminate

Ovaj događaj ukazuje na to da se demon MAU normalno prekinuo. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbaupdatefound"></a>fba.updatefound

Ovaj događaj ukazuje na to da je demon MAU pronašao dostupna ažuriranja koja može da ponudi. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži broj pronađenih dostupnih ispravki.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="fbaupdatetimer"></a>fba.updatetimer

Ovaj događaj pokazuje da je proces daemona aplikacije Microsoft Autoupdate postao aktivan radi provere da li postoje ispravke nakon što je određeno vreme proveo u stanju spavanja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o trenutnom datumu i vremenu.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateallappsclosed"></a>fbasilentupdate.allappsclosed

Ovaj se događaj evidentira ako su sve aplikacije bile zatvorene pre instalacije. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike
    
- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateapplaunchafterupdate"></a>fbasilentupdate.applaunchafterupdate

Ovaj događaj evidentira pokušaj ponovnog pokretanja aplikacije posle tihog ažuriranja i režim ažuriranja (klon ili ne). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Detalj greške do koje je došlo tokom pokretanja aplikacije nakon ažuriranja.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime aplikacije koja se pokreće. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateapplaunchwileinstalling"></a>fbasilentupdate.applaunchwileinstalling

Evidentiramo kada je došlo do pokretanja aplikacije tokom instaliranja ispravke. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateappneedtoclose"></a>fbasilentupdate.appneedtoclose

Evidentiramo kada je pokrenut proces ažuriranja i nalazimo da je aplikacija koja treba da se ažurira otvorena. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke i ID kompleta za aplikaciju.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateappterminationeventreceived"></a>fbasilentupdate.appterminationeventreceived

Ovaj događaj pokazuje da je Microsoft Autoupdate primio Apple događaj kojim se obaveštava o tome da je aplikacija prekinuta. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Detalj greške do koje je došlo tokom prekidanja aplikacije.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ID kompleta za aplikaciju. Može da sadrži i nisku greške ako Microsoft Autoupdate odredi da je aplikacija još uvek pokrenuta iako je primljen događaj prekidanja. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke aplikacije.


### <a name="fbasilentupdateclientsession"></a>FBASilentUpdate.ClientSession

Ovaj događaj se koristi za izračunavanje metrike ispravnosti kritičnih ispravki za Microsoft automatsko ažuriranje (MAU). Ovaj događaj nam omogućava da naznačite koje ispravke ažuriranja (preuzimanje ili instaliranje) funkcija "potpornim serverom" se trenutno rukuje.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Ukazuje na to kojom sesija ažuriranja (preuzimanje ili instalacija) potporni server trenutno rukuje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdatecodesignfailure"></a>fbasilentupdate.codesignfailure

Ovaj događaj evidentira rezultat verifikacije kodnog dizajna nakon primene ispravke. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži rezultat operacije verifikacije potpisa kodom.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdatedownload"></a>fbasilentupdate.download

Ovaj događaj označava preuzimanje ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ispravke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **ScreenLocked** – indikacija je li preuzimanje pokrenuto iza zaključanog ekrana

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdatedownloadfailed"></a>fbasilentupdate.downloadfailed

Ovaj događaj označava da je došlo do greške prilikom preuzimanja ispravke. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Detalj greške do koje je došlo tokom preuzimanja ispravke aplikacije.

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ispravke. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke aplikacije.

- **UpdateName** – Ime ispravke aplikacije.


### <a name="fbasilentupdatedownloadinbackground"></a>fbasilentupdate.downloadinbackground

Ovaj događaj pokazuje da pokrećemo preuzimanje skupa ispravki u pozadini (evidentiramo broj ispravki koje se istovremeno preuzimaju). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži broj ispravki u redu za čekanje.

    - **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdatedownloadingrepairupdate"></a>fbasilentupdate.downloadingrepairupdate

Ovaj događaj pokazuje da smo pokrenuli pokušaj preuzimanja popravke za neuspelu ispravku. Evidentiramo verziju i ispravku. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ispravke.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **ScreenLocked** – indikacija je li preuzimanje pokrenuto iza zaključanog ekrana

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateduplicatedownloadattempted"></a>fbasilentupdate.duplicatedownloadattempted

Ovaj događaj pokazuje da je došlo do greške. Trebalo bi da preuzimamo jednu po jednu ispravku za datu aplikaciju. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateinstallattemptfailed"></a>fbasilentupdate.installattemptfailed

Ovaj događaj označava da pokušaj instalacije za ažuriranje (verziju) nije uspeo. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateinstallcomplete"></a>fbasilentupdate.installcomplete

Ovaj događaj označava da su sva ažuriranja paketa završena sa instaliranjem. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateinstalled"></a>fbasilentupdate.installed

Ovaj događaj označava da je pojedinačna ispravka uspešno instalirana. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja. Sadrži identifikator ispravke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="fbasilentupdateinstalling"></a>fbasilentupdate.installing

Ovaj događaj označava da je pokrenuto pojedinačno ažuriranje. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke i ime paketa ispravki.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbasilentupdateinstallstatus"></a>fbasilentupdate.installstatus

Ovi izveštaji o događaju o statusu zadatka ažuriranja aplikacije. Ovaj događaj čini deo izveštaja o levku ispravke i koristimo za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o tome da li je prikazan prikaz toka

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazuje na to da li je ažuriranje aplikacije uspelo

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

- **UpdatePkg** – Ime paketa ispravki koji se primenjuje

### <a name="fbasilentupdatenotificationerror"></a>fbasilentupdate.notificationerror

Ovi izveštaji o događaju se susrela prilikom pokušaja slanja korisničkog obaveštenja. Ovaj događaj će se koristiti da bi se otklanjaju greške greške i da se preduzimaju korektivne radnje.

Prikupljaju se sledeća polja:  

- **App** – Proces aplikacije koji šalje događaj
 
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **ErrType** – Ukazuje na prirodu greške na koju se naišlo

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Message** – Sadržaj obaveštenja

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Title** – Naslov obaveštenja

- **Type** – Tip obaveštenja

### <a name="fbasilentupdatenotificationremoved"></a>fbasilentupdate.notificationremoved

Ovaj događaj označava da ažuriranje koje je blokirano više nije blokirano. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije (identifikator koji aplikacija koristi za registrovanje sa Microsoft Autoupdate uslugom) za prethodno blokiranu aplikaciju
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdatequeueinstall"></a>fbasilentupdate.queueinstall

Ovaj događaj označava da će se ažuriranje staviti u red za tihu instalaciju. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ispravke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdaterequiredappsclosed"></a>fbasilentupdate.requiredappsclosed

Evidentiramo kada se zatvori aplikacija za koju postoji ispravka na čekanju. To pokazuje vreme kada može da se nastavi sa stvarnim instaliranjem. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ID kompleta za aplikaciju.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbasilentupdatetimerforapptermination"></a>FBASilentUpdate.TimerForAppTermination

Ovaj događaj se koristi za izračunavanje metrike ispravnosti kritičnih ispravki za Microsoft automatsko ažuriranje (MAU). Ovaj događaj nam omogućava da pratimo događaj završetka otvorene aplikacije i trajanje otvorenog stanja.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Ukazuje na to da li je postavljen tajmer za otvorenu aplikaciju kada se pokrene instalacija njene ispravke. 

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="fbasilentupdateupdateavailablenotification"></a>fbasilentupdate.updateavailablenotification

Ovaj događaj pokazuje da je pokrenuto obaveštenje o dostupnoj ispravci. Moramo da obezbedimo da se pokrene tok traženja ispravki kada se otkrije ispravka. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **CustomNotification** – Bulova vrednost koja ukazuje na to da li je korišćeno prilagođeno obaveštenje.

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateuserclicknotification"></a>fbasilentupdate.userclicknotification

Ovaj događaj pokazuje da je korisnik kliknuo na odeljak sa sadržajem obaveštenja o dostupnim ispravkama i da se pokreće grafički korisnički interfejs aplikacije Microsoft Autoupdate. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateuserselectinstalllater"></a>fbasilentupdate.userselectinstalllater

Ovaj događaj pokazuje da je korisnik izabrao da izvrši instaliranje kasnije kada mu je prikazano obaveštenje o dostupnom ažuriranju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdateuserselectinstallnow"></a>fbasilentupdate.userselectinstallnow

Ovaj događaj pokazuje da je korisnik izabrao da izvrši instaliranje odmah kada mu je prikazano obaveštenje o dostupnom ažuriranju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="guidashboardrowviewupdatestate"></a>gui.dashboardrowview.updatestate

Ovaj događaj izveštava o grešci koja je pronađena prilikom pokušaja prikazivanja informacija o aplikaciji u MAU korisničkom interfejsu. Koristimo ovaj događaj da bismo obezbedili ispravnost MAU-a i pratili i adresirali neuspehe.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o prirodi greške do koje je došlo.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="guidashboardviewappisopendialogdisplay"></a>gui.dashboardview.appisopendialog.display 

Ovaj događaj ukazuje na to da je UI pokazivao dijalog za zatvaranje otvorene aplikacije da biste nastavili sa ažuriranjem aplikacije. Ovaj događaj se koristi za utvrđivanje obima ispravki koje se odlažu da bi se poboljšala prekida pri pružanju budućih poboljšanja.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="guidashboardviewappisopendialogbuttonclicked"></a>gui.dashboardview.appisopendialogbutton.clicked

Ovaj događaj ukazuje na to da li je ispravka zatvaranja preskočena ili je došlo do nekog drugog pokušaja nakon prikazivanja dijaloga otvorene aplikacije. Ovaj događaj se koristi za utvrđivanje količinskog ažuriranja koje se preskoče i koje se koriste za buduće poboljšanja radi umanjive prekida korisnika.

Prikupljaju se sledeća polja:   

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **ButtonType** – Preskoči ili Pokušaj opet

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja 

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="guidashboardviewupdateinprogressdialogdisplay"></a>gui.dashboardview.updateinprogressdialog.display

Ovaj događaj evidentira da li se prikazuje dijalog korisnicima koji ukazuju na to da je ispravka već u toku.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guidashboardviewupdatemodebuttonclicked"></a>gui.dashboardview.updatemodebutton.clicked

Ovaj događaj ukazuje na to da je režim ažuriranja izmenjen u kontroli korisničkog interfejsa. Ovaj događaj se koristi za utvrđivanje obima uređaja koji prelaze iz jednog režima u drugi i koristi se za utvrđivanje zašto se klijenti udaljavaju od automatskih ispravki. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
 
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Ukazuje na to da li je automatsko preuzimanje ISKLJUČENO

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guifeedbackwindowbuttonclicked"></a>gui.feedbackwindow.buttonclicked

Ovi izveštaji o događaju o tome da li se povratne informacije prosleđuju ili otkazuju pre predaje. Ovaj događaj se koristi za utvrđivanje obima povratnih informacija upućenog na određenu verziju izdanja. Ovo vam pomaže da ranije izolovite potencijalne probleme.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **ButtonType** – Ukazuje na to da li su povratne informacije poslate ili otkazane

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema
 
- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guipreferenceviewconsentsheetdisplay"></a>gui.preferenceview.consentsheet.display

Ovaj događaj ukazuje na to da se prikazuje saglasnost za datu televiziju, ako je dostupan. Ovaj događaj se koristi za utvrđivanje obima uređaja koji se nedavno upisujete u važeći kanali korisnika (Insider Fast/Insider Slow). Koristite ovaj događaj da biste obezbedili da dijalog za saglasnost funkcioniše da biste prikazali uslove korišćenja korisnicima.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **ChannelName** – Kanal za koji se prikazuje dijalog pristanka

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guipreferenceviewconsentsheetlicenseerror"></a>gui.preferenceview.consentsheet.licenseerror

Ovi izveštaji o grešci su nailasili pri pokušaju da se prikaže dijalog pristanak. Ovaj događaj je kritičan i koristi se za ispravljanje problema izazvane promenom proizvoda, ako je primenljivo.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **ErrorCode** – Kôd greške na koju se naišlo

- **ErrorDomain** – Domen greške

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guipreferenceviewswitchchannel"></a>gui.preferenceview.switchchannel

Ovi izveštaji o događaju u tranziciji između korisnika izabranih kanala. Ovaj događaj se koristi za utvrđivanje zašto klijenti objavljuju izvan kanala Insider kanala.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PickedFrom** – Stari kanal

- **PickedTo** – Novi kanal

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="guiupdatemanagerapplaunchduringupdate"></a>gui.updatemanager.applaunchduringupdate

Ovaj događaj izveštava da je aplikacija pokrenuta tokom ažuriranja, a Microsoft AutoUpdate prekida lansiranu aplikaciju. Obratite pažnju na to da pokretanje aplikacije dok se ažurira može da dovede do oštećenja aplikacije. Koristite ovaj događaj da biste obezbedili da proces ažuriranja nije uticao na pokrenutu aplikaciju pre nego što bude spreman za korišćenje.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije koja je pokrenuta tokom ažuriranja.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulova vrednost niske koja ukazuje na to da li je aplikacija uspešno prekinuta.

- **UpdateID** – Identifikator ispravke aplikacije.

### <a name="guiupdatemanagerdownloadupdateforapp"></a>gui.updatemanager.downloadupdateforapp

Ovi izveštaji o događaju o preuzimanju statusa završetka za ispravku. Koristite ovaj događaj da biste obezbedili ispravnost procesa ažuriranja i taиke nestanka/adresa.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **IsRepair** – Bulova vrednost niske koja ukazuje na to da li određena ispravka predstavlja preuzimanje popravke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **isRepair** – Ukazuje na to da li je preuzimanje bilo preuzimanje popravke za prethodno neuspelu ispravku.

- **UpdateID** – Identifikator ispravke.

- **UpdateName** – Ime ispravke.


### <a name="guiupdatemanagererror"></a>gui.updatemanager.error

Ovaj događaj se prijavljuje na bilo koje greške koje se susrecu tokom ispravki aplikacije. To može da ukazuje na grešku u Microsoft automatskom ažuriranju (MAU) sekvenci izvršavanja.  Koristite ovaj izveštaj da biste primenili ispravke na programu MAU na opciju "Najčešća slučaja grešaka".

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o grešci na koju se naišlo tokom ažuriranja aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulova vrednost niske koja ukazuje na to da li je aplikacija uspešno prekinuta.

### <a name="guiupdatemanagerinstallcleanupforapp"></a>gui.updatemanager.installcleanupforapp

Ovaj događaj ukazuje na to da je privremena datoteka kreirana tokom instalacije aplikacije uspešno ociљtena. Ovo čini deo levka ispravke i koristimo ga za utvrđivanje ispravnosti ispravki aplikacije.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppState** – Ceo broj ukazuje na stanje aplikacije nakon pokušaja ažuriranja.

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke.


### <a name="guiupdatemanagerinstallsuccessforapp"></a>gui.updatemanager.installsuccessforapp

Ovaj događaj pokazuje uspešnu ispravku aplikacije. Ovaj događaj čini deo levka ispravke koji koristimo da bismo utvrdili ispravnost ispravke.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulova vrednost niske koja ukazuje na to da li su ispravke uspešno instalirane.

- **UpdateID** – Identifikator ispravke.

### <a name="guiupdatemanagerinstallupdateforapp"></a>gui.updatemanager.installupdateforapp

Ovaj događaj ukazuje na početak stvarnog procesa instalacije za ispravku aplikacije. Ovaj događaj čini deo levka ispravke aplikacije koji koristimo da biste utvrdili ispravnost ispravke.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke.

### <a name="guiupdatemanagerqueueinstallforapp"></a>gui.updatemanager.queueinstallforapp

Ovaj događaj ukazuje na početak stvarnog procesa instalacije za ispravku aplikacije. Ovaj događaj čini deo levka ispravke aplikacije koji koristimo da biste utvrdili ispravnost ispravke.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke.

### <a name="guiupdatemanagerrelaunchapp"></a>gui.updatemanager.relaunchapp

Ovaj događaj evidentira da li su primene aplikacije uspešno ponovo poništeni nakon ispravki.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulova vrednost niske koja ukazuje na to da li je aplikacija uspešno prekinuta.

- **UpdateID** – Identifikator ispravke.

- **UpdateName** – Ime ispravke.

### <a name="installdatacheckrunning"></a>installdata.checkrunning

Ovaj događaj evidentira rezultat provere među aplikacijama koje će se instalirati i toga da li će se pokušaj instaliranja nastaviti na osnovu toga da li je aplikacija otvorena. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installdatacleanup"></a>installdata.cleanup

Datoteke paketa treba da se uklone posle instaliranja. Ovaj događaj beleži instance kada ne uspemo da ih uklonimo. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime preuzete datoteke i detalje greške.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installedappacknowledgedcoreappleevent"></a>installedapp.acknowledgedcoreappleevent

Ovaj događaj ukazuje na to da je Microsoft Auto Update (MAU) primio potvrdu o Apple događaju od registrovane aplikacije da bi je prekinuo i nastavio sa ažuriranjem aplikacije na čekanju. Ovaj događaj se koristi da bi se razvijala buduća poboljšanja radi umanjenja prekida tokom ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppleEventClass** – Ukazuje na tim događaja koji se šalje/potvrđuje

- **AppleEventID** – Jedinstveni identifikator za događaj koji se šalje/potvrđuje

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži broj ponovnih pokušaja

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke.


### <a name="installedappinvalidbundle"></a>installedapp.invalidbundle

Ovaj događaj pokazuje da Microsoft Autoupdate ne može da preuzme informacije o paketu za registrovanu aplikaciju na datoj putanji. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installedappinvalidpreference"></a>installedapp.invalidpreference

Ovaj događaj evidentira slučajeve u kojima željene opcije korisnika sadrže nevažeći unos aplikacije. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveravanje da li postoje ažuriranja.

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installedappnilbundleid"></a>installedapp.nilbundleid

Ovaj događaj evidentira slučajeve u kojima nedostaje ID paketa za aplikaciju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installedappnilbundlename"></a>installedapp.nilbundlename

Ovaj događaj evidentira slučajeve u kojima nedostaje ime paketa za aplikaciju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installedapprespondedcoreappleevent"></a>installedapp.respondedcoreappleevent

Ovaj događaj ukazuje na to da je Microsoft automatsko ažuriranje (MAU) od registrovane aplikacije primilo Appleov odgovor na događaj za prekid aplikacije kako bi se nastavilo s ažuriranjem aplikacije na čekanju. Ovaj događaj se koristi da bi se razvijala buduća poboljšanja radi umanjenja prekida tokom ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppleEventClass** – Ukazuje na tim događaja koji se šalje/potvrđuje

- **AppleEventID** – Jedinstveni identifikator za događaj koji se šalje/potvrđuje

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži broj ponovnih pokušaja

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator ispravke.


### <a name="installedappsendcoreappleevent"></a>installedapp.sendcoreappleevent

Ovaj događaj ukazuje na to da Microsoft automatsku ispravku (MAU) šalje Apple Event u registrovanu aplikaciju da bi se okonиalo zatvaranje aplikacije kako bi se nastavili sa ažuriranjem aplikacije Neobrađeno. Ovaj događaj se trenutno koristi da bi se razvijala buduća poboljšanja radi umanjene prekida korisnika tokom ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **Acknowledged** – Ukazuje na to da li je aplikacija subjekta potvrdila prijem događaja

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppleEventClass** – Ukazuje na tim događaja koji se šalje/potvrđuje

- **AppleEventID** – Jedinstveni identifikator za događaj koji se šalje/potvrđuje

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži broj ponovnih pokušaja

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazuje na to da li je aplikacija subjekta prijavila uspeh operacije

- **UpdateID** – Identifikator ispravke.
    
### <a name="installstatuscodesign"></a>installstatus.codesign

Ovaj događaj evidentira status binarnog softvera OS kodnog dizajna. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installstatusdaemon"></a>installstatus.daemon

Ovaj događaj beleži status demona Microsoft AutoUpdate. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **BundleReachable** – Bulova vrednost koja ukazuje na to da li je došlo do problema sa pristupanjem kompletu za aplikaciju Microsoft AutoUpdate.

- **Channel** – Željene opcije za korisnike

- **Codesigned** – Bulova vrednost koja ukazuje na to da li je pomoćnik za ažuriranje ispravno kodizajniran.

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **Exists** – Bulova vrednost koja ukazuje na to da li pomoćnik za ažuriranje postoji na disku.

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži naznaku toga da li komponenta daemona postoji na očekivanoj lokaciji i da li je potpisana kodom. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installstatushelper"></a>installstatus.helper

Ovaj događaj beleži status pomoćnog alata Microsoft AutoUpdate. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži naznaku toga da li komponenta PrivilegedHelperTool postoji na očekivanoj lokaciji i da li je potpisana kodom.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installupdatestaskapplaunched"></a>installupdatestask.applaunched

Ovaj događaj pokazuje da je Microsoft Autoupdate otkrio pokretanje aplikacije za blokiranu ispravku, ali nije mogao da pronađe odgovarajući instalacioni program. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime pokrenute aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installupdatestaskapplaunchwithpendingupdate"></a>installupdatestask.applaunchwithpendingupdate

Ovaj događaj pokazuje da je Microsoft Autoupdate otkrio pokretanje aplikacije za aplikaciju sa ispravkom na čekanju. Pokrenuta aplikacija se prekida. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installupdatestaskcodesignverificationfail"></a>installupdatestask.codesignverificationfail

Ovaj događaj označava da verifikacija CodeSign-a nije uspela za ažuriranje aplikacije. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ažurirane aplikacije i kôd otkazivanja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestaskcodesignverificationstart"></a>installupdatestask.codesignverificationstart

Ovaj događaj označava da je verifikacija CodeSign započeta za ažuriranje aplikacije. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ažurirane aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestaskcodesignverificationsuccess"></a>installupdatestask.codesignverificationsuccess

Ovaj događaj označava uspeh verifikacije CodeSign za ažuriranje aplikacije. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ažurirane aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestaskfailsilentinstall"></a>installupdatestask.failsilentinstall

Ovaj događaj evidentira otkazivanja prilikom primene tihih ažuriranja i to da li instaliranje bilo klonirano ili normalno. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 
    
- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i tip ispravke.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installupdatestaskmultiplerelocatablepackage"></a>installupdatestask.multiplerelocatablepackage

Ovaj događaj pokazuje da je Microsoft Autoupdate pronašao više instanci unosa aplikacije za dati paket ispravki u preuzetom manifestu. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="installupdatestaskremoveclone"></a>installupdatestask.removeclone

Ovaj događaj pokazuje da je klon uklonjen. Klona uklanjamo kada se završi proces instaliranja na klonu ili kada se započne novi proces i pronađe se starija klonirana verzija na mašini. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke, ime paketa ispravki i detalje o statusu/greškama za uklanjanje klona.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestaskretryfail"></a>installupdatestask.retryfail

Ovaj događaj označava da su se tokom postupka ponovnog pokušaja instalacije pojavile greške. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke i to da li instaliranje treba da se izvrši pomoću opcije „Instaliraj na klon“

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

   
### <a name="installupdatestaskretryproxyerror"></a>installupdatestask.retryproxyerror

Ovaj događaj evidentira greške u komunikaciji unutar procesa (komunikacija sa MAU pomoćnim alatom). Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke i detalje o prijavljenoj grešci proxy servera.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    

### <a name="installupdatestaskretryresponse"></a>installupdatestask.retryresponse

Ovaj događaj beleži da ponovljeni pokušaj nije uspeo. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke, verziju aplikacije, ime paketa ispravki i naznaku toga da li je opcija „Instaliraj na klon“ bila uključena, da li je instaliranje bilo uspešno, kao i sve greške prijavljene u slučaju otkazivanja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestaskretrysuccess"></a>installupdatestask.retrysuccess

Ovaj događaj beleži uspešnu instalaciju ažuriranja nakon ponovnog pokušaja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, ime ispravke, verziju aplikacije, ime paketa ispravki i naznaku toga da li je opcija „Instaliraj na klon“ bila uključena.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installupdatestasksetreopengui"></a>installupdatestask.setreopengui

Ovaj događaj pokazuje da li je uspelo podešavanje željenih opcija za ponovno otvaranje grafičkog korisničkog interfejsa posle instaliranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji označava da li je operacija uspela. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Bulov izraz koji ukazuje na uspeh operacije.

### <a name="installupdatestaskupdatestatus"></a>installupdatestask.updatestatus

Ovi izveštaji o događaju o statusu zadatka instalacije. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Ukazuje na greške na koje se naišlo tokom procesa ažuriranja, ako je popunjeno

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **IOC** – Ukazuje na to da li se koristi funkcija „Instaliranje na klonu“

- **Payload** – Statički tekst koji ukazuje na početak procesa instalacije ako je prisutan

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazuje na to da li je proces instalacije uspešno dovršen

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

- **UpdatePkg** – Ime paketa ispravki koji se primenjuje

### <a name="lifecyclecomplimentproclaunch"></a>Lifecycle.complimentproclaunch

Ovaj događaj ukazuje na pokušaj pokretanja Microsoft Update pomoćnika iz Microsoft AutoUpdate ili iz Microsoft AutoUpdate iz Microsoft Update pomoćnika. Ovaj događaj se koristi za određivanje i osiguravanje ispravnosti Microsoft AutoUpdate i Microsoft Update pomoćnika.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Svaka greška prijavljena tokom pokušaja pokretanja

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **Reason** – Razlog za pokušaj pokretanja procesa komplimenta

- **SessionId** – Identifikator sesije

- **Success** – Indikacija da li je pokušaj lansiranja bio uspešan

### <a name="lifecyclelaunch"></a>Lifecycle.launch

Ovaj događaj ukazuje na početak usluge Microsoft AutoUpdate ili Microsoft Update pomoćnika. Ovaj događaj se takođe koristi za prijavljivanje svih problema pronađenih tokom procesa pokretanja, kao i način izveštavanja koji se koristi za pokretanje u slučaju Microsoft Update pomoćnika.

*[Ovaj događaj zamenjuje fba.launch i appdelegate.launch events.]*

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – bilo koja greška pronađena prilikom pokretanja

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **LaunchedBy** – Metoda koja se koristi za pokretanje Microsoft Update pomoćnika, ako je primenljivo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="lifecycleperiodiccheck"></a>Lifecycle.periodiccheck

Ovaj događaj periodično izveštava o statusu procesa MicrosoftAutoUpdate. Posebno izveštava o tome na šta preostali procesi zadataka čekaju za dovršavanje pomoćnika za ažuriranje a u slučaju UI izveštava o tome da li se proces prekida zbog nepostupanja korisnika.  Ovaj događaj koristimo za određivanje toga šta sprečava pomoćnika za ažuriranje da dovrši ažuriranja i prekidanja i da li se UI prekida zbog nepostupanja korisnika.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **dataCollectionDialog** – Bulov izraz koji ukazuje na to da li proces čeka na odgovor korisnika u dijalogu za prikupljanje podataka

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **forcedUpdateDialog** – Bulov izraz koji ukazuje na to da li proces čeka na odgovor korisnika u dijalogu nametnutog ažuriranja

- **howToCheck** – Postavka „Kako proveriti“

- **isBusy** – Bulov izraz koji ukazuje na to da li je proces zauzet aktivnim ažuriranjem

- **isInactive** – Bulov izraz koji ukazuje na to da li proces čeka na radnju korisnika duže vreme

- **isWaiting** – Bulov izraz koji ukazuje na to da li proces čeka na odgovor korisnika na obaveštenje

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

- **SessionLength** – Dužina trenutne sesije procesa u sekundama


### <a name="lifecycleterminate"></a>Lifecycle.terminate

Ovaj događaj ukazuje na prestanak usluge Microsoft AutoUpdate ili Microsoft Update pomoćnika. Ovaj događaj se koristi za određivanje ispravnosti Microsoft AutoUpdate i Microsoft Update pomoćnika.

*[Ovaj događaj zamenjuje fba.terminate i appdelegate.terminate events.]*

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **SessionLength** – Dužina trenutne sesije procesa u sekundama



### <a name="msupdateclieventhandler"></a>msupdate.cli.eventhandler

Ovaj događaj se koristi za izračunavanje upotrebe različitih tipova Microsoft automatskih ispravki (MAU) interfejsa komandne linije za Office automatsko ažuriranje (MAU).

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator aplikacije koja šalje API interfejsa komandne linije u MAU.

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme kada je primljena telemetrija

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **EventType** – Tip događaja koji aplikacija šalje u MAU API interfejsa komandne linije.

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdateclieventhandlerapplyupdatesappids"></a>msupdate.cli.eventhandler.applyupdates.appids

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Ovaj događaj pokazuje da je izdata komanda interfejsa za pozive da se primeni ispravka. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu ID-ova aplikacija koje treba ažurirati.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdateclieventhandlerconfig"></a>msupdate.cli.eventhandler.config

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Ovaj događaj pokazuje da je modul interfejsa sa komandnom linijom aplikacije Microsoft Autoupdate primio Apple događaj za konfigurisanje. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdateclieventhandlerupdates"></a>msupdate.cli.eventhandler.updates

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Ovaj događaj pokazuje da je modul interfejsa sa komandnom linijom aplikacije Microsoft Autoupdate primio Apple događaj za navođenje ispravki. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="msupdatemonitorprogressdownloaded"></a>msupdate.monitor.progress.downloaded

Ovaj događaj pokazuje da su ispravke preuzete. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu preuzetih ispravki

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdatemonitorprogressfailure"></a>msupdate.monitor.progress.failure

Ovaj događaj evidentira listu ažuriranja u redu koje nisu uspele da se primene. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu ispravki.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="msupdatemonitorprogressfinished"></a>msupdate.monitor.progress.finished

Ovaj događaj evidentira listu ispravki na čekanju koje su dovršile instalaciju. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu ispravki.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdatemonitorprogressqueued"></a>msupdate.monitor.progress.queued

Ovaj događaj evidentira listu ažuriranja u redu. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu ispravki.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="optinnotificationaction"></a>Optinnotificationaction

*[Ovaj događaj je uklonjen iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

Ovaj događaj beleži odgovor korisnika na dijalog za prijavu za upis u nečujna ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži statički tekst koji predstavlja izbor korisnika za davanje saglasnosti za automatsko preuzimanje i instaliranje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="sauforcedupdateautodismiss"></a>sauforcedupdate.autodismiss

Ovaj događaj ukazuje na prikazano dijalog "prikazano energetsko ažuriranje" zbog neaktivnosti korisnika. Ovaj događaj se koristi za utvrđivanje količine nametnutih ispravki koje se nastavlju bez ikakvog korisničkog unosa u prikazano obaveštenje. Ovaj događaj se koristi za poboljšanje korisničkog interfejsa radi smanjenja prekida.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja
  
- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – statični tekst *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali može se i dalje pojaviti u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **Reason** – Statički tekst

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateclose"></a>sauforcedupdate.close

Ovaj događaj ukazuje na to da je korisnik izabrao da zatvori dijalog "prisilno ažuriranje". Ovaj događaj se koristi za utvrđivanje obima prinudnih ispravki koje su odložene tokom radnje korisnika. Ovaj događaj se koristi za poboljšanje korisničkog interfejsa radi smanjenja prekida. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatecompleteautodismiss"></a>sauforcedupdate.completeautodismiss

Ovaj događaj ukazuje na to da se prikazuje dijalog nametnuto ažuriranje od krajnjeg roka koji se odbacuje zbog neaktivnosti korisnika. Ovaj događaj se koristi za utvrđivanje količine nametnutih ispravki koje se nastavlju bez ikakvog korisničkog unosa u prikazano obaveštenje. Ovaj događaj se koristi za poboljšanje korisničkog interfejsa radi umanjive funkcije prekida za krajnji rok.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatecompleteclose"></a>sauforcedupdate.completeclose

Ovaj događaj pokazuje uspešan dovršavanje prinudne ispravke. Ovaj događaj se koristi za utvrđivanje zdravlja funkcije prinudne ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatedisplay"></a>sauforcedupdate.display

Ovaj događaj ukazuje na to da je prikazan dijalog "nametnuto ažuriranje".  Ovaj događaj čini deo levka nametnute ispravke i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatedisplayfinalhour"></a>sauforcedupdate.displayfinalhour

Ovaj događaj ukazuje na to da je prikazan dijalog nametnuto završnog trenutka ažuriranja. Ovaj događaj čini deo levka nametnute ispravke i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatedone"></a>sauforcedupdate.done

Ovaj događaj ukazuje na to da je nametnuto ažuriranje uspešno dovršeno. Ovaj događaj čini deo levka nametnute ispravke i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateenabled"></a>sauforcedupdate.enabled

Ovaj događaj se pokreće kada Microsoft automatsko ažuriranje (MAU) utvrdi nametnuto ažuriranje.  Ovaj događaj se koristi za utvrđivanje ispravnosti funkcije nametnute ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Enabled** – Ukazuje na to da li je nametnuta ispravka omogućena

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **InvalidUpdates** – Broj postavljenih nametnutih ispravki sa nevažećim verzijama ispravki

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateforcedupdatedismiss"></a>sauforcedupdate.forcedupdatedismiss

Ovaj događaj ukazuje na to da se dijalog "prikazano snage funkcije" funkcija za poslednji čas otpušta zbog neaktivnosti korisnika. Ovaj događaj se koristi za utvrđivanje količine nametnutih ispravki koje se nastavlju bez ikakvog korisničkog unosa u prikazano obaveštenje. Ovaj događaj se koristi za poboljšanje korisničkog interfejsa radi smanjenja prekida. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – statični tekst *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali može se i dalje pojaviti u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **Reason** – Statički tekst

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateforcequitandupdatenow"></a>sauforcedupdate.forcequitandupdatenow

Ovaj događaj ukazuje na početak nametnutog ažuriranja koje je pokrenuto korisnik. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije 

### <a name="sauforcedupdateforceterminate"></a>sauforcedupdate.forceterminate

Ovaj događaj pokazuje početak prinudne ispravke pomoću primene prisilnog prekida.  Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži broj aplikacija koje treba prekinuti

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatequitandupdatenow"></a>sauforcedupdate.quitandupdatenow

Ovaj događaj ukazuje na to da je korisnik izabrao da zatvori aplikaciju i primeni ispravku. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdatesnooze"></a>sauforcedupdate.snooze

Ovaj događaj ukazuje na to da je korisnik izabrao da odloži nametnuto ažuriranje. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Duration** – Tekst koji ukazuje na trajanje odlaganja

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – statični tekst *[Ovo polje je uklonjeno iz trenutnih verzija sistema Office, ali može se i dalje pojaviti u starijim verzijama.]*

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateterminate"></a>sauforcedupdate.terminate

Ovaj događaj pokazuje početak prinudne ispravke koju je aplikacija prekinula. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži broj aplikacija koje treba prekinuti

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="sauforcedupdateupdatenow"></a>sauforcedupdate.updatenow

Ovaj događaj ukazuje na to da je korisnik izabrao da ažurira aplikaciju sada.  Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti funkcije nametnute ispravke.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="sauupdateinfoprovider"></a>sauupdateinfoprovider

Ovaj događaj se evidentira kad god nedostaje manifestni ključ u dodatku. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži nisku koja se koristi za traženje lokacije ili veličine ispravke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updateapplaunchdetected"></a>update.applaunchdetected

Ovaj događaj ukazuje na to da je aplikacija pokrenuta dok je ispravka bila u toku. Ovaj događaj se koristi za utvrđivanje obima aplikacija koje su pokrenute tokom ažuriranja i koje se koristi za povećanje iskustva korisnika u budućim izdanjima.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazuje na to da li je pokrenuta aplikacija uspešno prekinuta

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateappterminationreceived"></a>update.appterminationreceived

Ovaj događaj ukazuje na to da je prekinuta aplikacija sa blokiranom ažuriranjem i da li Microsoft automatsko ažuriranje (MAU) može da nastavi sa ažuriranjem. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Ukazuje na to da li su druge instance aplikacije i dalje pokrenute, što sprečava MAU da nastavi

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst koji ukazuje na to da MAU nastavlja sa ažuriranjem

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateblockedappclosed"></a>update.blockedappclosed

Ovaj događaj ukazuje na to da je Microsoft automatsku ispravku (MAU) otkrio da je aplikacija sa blokiranom ažuriranjem zatvorena i može da nastavi sa ažuriranjem. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije.

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira.

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije. 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateblockedinstallskip"></a>update.blockedinstallskip

Ovaj događaj evidentira grešku prilikom pokušaja preskočite ispravke aplikacije. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljenih grešaka.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o grešci na koju se naišlo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updateclientsession"></a>update.clientsession

Ovaj događaj se prijavljuje kada se promeni status klijenta uređaja, što dovodi do toga da pomoćnik za Microsoft Update pauzirala ili nastavi proces ažuriranja. Ovaj događaj čini deo levka i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Ukazuje na to da li se Microsoft automatsko ažuriranje (MAU) nastavlja ili pauzira

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updateclonedisablereason"></a>update.clonedisablereason

Ovaj događaj beleži uslov da je funkcija Install-On-Clone onemogućena za određeno ažuriranje. Ovaj događaj koristimo za nadgledanje ispravnosti funkcije Install-On-Clone i za pružanje poboljšane usluge.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme kada je primljena telemetrija

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – prva tri okteta IP adrese

- **Reason** – razlog zašto je instaliranje na klonu onemogućeno za ovu ispravku.

- **SessionId** – Identifikator sesije


### <a name="updatedownloadbegin"></a>update.download.begin 

Ovaj događaj pokazuje početak procesa ažuriranja aplikacije. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **IsRepair** – Ukazuje na to da li ispravka treba da popravi neuspelo ažuriranje

- **Payload** – Ukazuje na to da li je prethodno došlo do pokušaja preuzimanja

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="updatedownloadfinish"></a>update.download.finish

Ovaj događaj pokazuje dovršavanje faze preuzimanja za ispravku aplikacije. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **IsRepair** – Ukazuje na to da li ispravka treba da popravi neuspelo ažuriranje

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="updatedownloadresume"></a>update.downloadresume

Ovaj događaj izveštava da je došlo do greške prilikom pokušaja nastavka pauzenog zadatka preuzimanja. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljenih grešaka. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Ukazuje na prirodu greške na koju se naišlo

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateerror"></a>update.error

Ovaj događaj izveštava da je došlo do greške prilikom pokušaja ažuriranja registrovane aplikacije.  Ovaj događaj je kritičan i koristi se za ispitivanje prijavljenih grešaka. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Sadrži informacije o prirodi greške na koju se naišlo

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o prirodi greške na koju se naišlo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updateinstallcleanupforapp"></a>update.installcleanupforapp

Ovaj događaj ukazuje na to da je instalirana ispravka dovršena i da je Microsoft automatska ispravka (MAU) čišćenja.  Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppState** – Stanje registrovane aplikacije. Može da ukazuje na grešku, popravku na čekanju itd.

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateinstallupdateforapp"></a>update.installupdateforapp

Ovaj događaj se koristi za izveštavanje na početnom procesu instaliranja ažuriranja aplikacije. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Greške na koje se naišlo ukoliko postoje

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="updateinstallupdateforappsuccess"></a>update.installupdateforapp.success

Ovi izveštaji o događaju o statusu zadatka instaliranja. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **ForcedUpdate** – Oznaka niza da li IT administrator nameće ažuriranje

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Ukazuje na to da li je prikaz toka prikazan tokom procesa instalacije

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazivanje na uspeh koje se vraća iz zadatka instalacije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updateinstallvariance"></a>Update.InstallVariance

Ovaj događaj se koristi za izračunavanje metrike ispravnosti kritičnih ispravki za MAU. Ovaj događaj nam omogućava da utvrdimo mernost uspeha funkcije "Instaliranje prioriteta" i verifikovamo integritet funkcije.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži listu ID-ova aplikacije i njihov odgovarajući prioritet instaliranja predstavljen brojevima.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatemultipleappupdates"></a>update.multipleappupdates 

Ovaj događaj ukazuje na to da su više ispravki aplikacije u toku u pozadini. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja 

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o broju aplikacija koje se ažuriraju

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatepreviousidnil"></a>update.previousidnil

Ovaj događaj ukazuje na to da je paket ispravki opravke preuzet, ali ne postoji prethodna informacija o preuzimanju. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljenih grešaka. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Ukazuje na prirodu greške na koju se naišlo

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatequeueinstallforapp"></a>update.queueinstallforapp 

Ovaj događaj ukazuje na to da je preuzet paket ispravki postavljen u red za instaliranje.  Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst koji ukazuje na to da aplikacija treba da se zatvori ako je prisutan

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

- **UpdateName** – Ime ispravke kao što je prikazano u preuzetoj datoteci manifesta

### <a name="updaterelaunchafterupdate"></a>update.relaunchafterupdate 

Ovaj događaj označava da je ispravka aplikacije dovršena i da se ponovo pokreće. Ovaj događaj čini deo levka ispravke i koristi se za utvrđivanje ispravnosti ispravki aplikacije. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Sadrži informacije o greškama na koje se naišlo tokom pokušaja ponovnog pokretanja aplikacije

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **UpdateID** – Identifikator za ispravku aplikacije

### <a name="updatetimerforapptermination"></a>update.timerforapptermination 

Ovaj događaj pokazuje početak/kraj tajmera za proveru statusa aplikacije. Ovaj događaj stiže u paru i koristi se za utvrđivanje svih objekata tajmera koji se uklanjaju kad ispravka aplikacije prelazi.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Ukazuje na to da li je tajmer dodat ili uklonjen

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatecoreappregistration"></a>updatecore.appregistration

Ovaj događaj evidentira pokušaje registracije aplikacije i rezultata / razloga. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja, naznaku toga da li su dostupne željene opcije, naznaku toga da li je ovo ponovna registracija i naznaku toga da li je registracija neophodna.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatecoreloadinglaunchagent"></a>updatecore.loadinglaunchagent

Ovaj događaj znači da se agent za pokretanje učitava. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatecorerunnstaskcommand"></a>updatecore.runnstaskcommand

Ovi događaji izveštavaju o grešci prilikom pokušaja pokretanja zadatka. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljenih grešaka.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži putanju do komande koja se izvršava

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatecoreserverconnectionfail"></a>updatecore.server.connectionfail

Ovaj događaj evidentira greške pogođene prilikom kontaktiranja sa CDN-om. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o imenu servera, tome da li je server važeći i da li je dostupan.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatecoreservernullurl"></a>updatecore.server.nullurl

Ovim događajem javlja se greška koja ukazuje na to da nije moguće stići do datog servera. Ovaj događaj se koristi za utvrđivanje brzine ažuriranja koju uzrokuje problem sa mrežom. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefilterhelpercannotretrievebuilddate"></a>updatefilterhelper.cannotretrievebuilddate

Ispravke možemo da filtriramo pomoću MAU usluge samo kada ispravka koja se nudi nije starija od određenog broja dana. Ovde evidentiramo da nismo mogli da preuzmemo datum iz metapodataka aplikacije. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefilterhelperinvalidappid"></a>updatefilterhelper.invalidappid

Ovaj događaj izveštava o grešci koja ukazuje na to da nije moguće pronaći nijednu podudarnu manifest datoteku sa ID-om aplikacije preuzetom iz Veb odgovora. Ovaj događaj se koristi za ispitivanje prijavljene greške.

Prikupljaju se sledeća polja: 

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži ID aplikacije u veb odgovoru

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefilterhelperinvalidappidfromwebservices"></a>updatefilterhelper.invalidappidfromwebservices

Ovaj događaj izveštava o grešci koja ukazuje na to da ID aplikacije preuzet sa Veb odgovora nije u očekivanom formatu. Ovaj događaj se koristi za ispitivanje prijavljene greške.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Statički tekst

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefilterhelperinvalidresponsefromupdatefiltering"></a>updatefilterhelper.invalidresponsefromupdatefiltering

Ispravke možemo da filtriramo pomoću MAU usluge samo kada ispravka koja se nudi nije starija od određenog broja dana. Ovde evidentiramo da u metapodacima aplikacije nedostaje datum. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 
    
- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefilterhelpermissingbuilddate"></a>updatefilterhelper.missingbuilddate

Ispravke možemo da filtriramo pomoću MAU usluge samo kada ispravka koja se nudi nije starija od određenog broja dana. Ovde evidentiramo da u metapodacima aplikacije nedostaje datum. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefilterhelperupdatebypassedoldage"></a>updatefilterhelper.updatebypassedoldage

Ispravke možemo da filtriramo pomoću MAU usluge samo kada ispravka koja se nudi nije starija od određenog broja dana. Ovde evidentiramo da je usluga zaobiđena zbog datuma starog ažuriranja. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindercheckerror"></a>updatefinder.check.error

Ovaj događaj izveštava da je došlo do greške prilikom provere da li postoje ispravke. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljene greške. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Code** – Kôd greške 

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Domain** – Domen greške

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

 
### <a name="updatefindercheckstart"></a>updatefinder.check.start

Ovaj događaj se evidentira svaki put kada započnemo proveru operacija ažuriranja. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj
    
- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o ispravkama koje se nude, registrovanim aplikacijama i lokaciji na kojoj se privremeno čuvaju preuzete datoteke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindercheckstatus"></a>updatefinder.check.status

Ovaj događaj agregira status operacija provere da li postoje ispravke (tok od pretrage do preuzimanja). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži informacije o ispravkama koje se nude, registrovanim aplikacijama i lokaciji na kojoj se privremeno čuvaju preuzete datoteke.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindercheckupdatefound"></a>updatefinder.check.updatefound

Registrujemo se svaki put kada provera za ispravke rezultira pronađenim ispravkama. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindercheckupdatenotfound"></a>updatefinder.check.updatenotfound

Evidentiramo svaki put kada provera da li postoje ispravke ne pronađe ponuđene ispravke jer ispravke nisu pronađene. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindercheckuptodate"></a>updatefinder.check.uptodate

Evidentiramo svaki put kada provera da li postoje ispravke ne pronađe ponuđene ispravke jer su sve aplikacije već ažurirane. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefinderofferupdatesinvalidappid"></a>updatefinder.offerupdates.invalidappid

Ovaj događaj prijavljuje grešku dok pokušava da proceni da li je ispravka primenljiva. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljene greške.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **CatalogID** – Identifikator za katalog kom je pristupljeno

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **IsNullID** – Ukazuje na to da li je ID bez vrednosti

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefinderofferupdatesminoscheckfail"></a>updatefinder.offerupdates.minoscheckfail

Evidentiramo svaki put kada blokiramo ispravku zbog toga što ne ispunjava zahteve operativnog sistema. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži minimalne preduslove za verziju operativnog sistema onako kako je navedeno u preuzetoj datoteci manifesta.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefinderofferupdatesmissingtrigger"></a>updatefinder.offerupdates.missingtrigger

Ovaj događaj prijavljuje grešku dok pokušava da oceni okidače iz preuzete primene ispravki aplikacije. Ovo je kritično i koristi se za ispitivanje prijavljene greške.  

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **TriggerKey** – Ključ aktivatora koji se nalazi u manifestu

- **Triggers** – Rečnik aktivatora koji se nalaze u manifestu

### <a name="updatefinderofferupdatesnullbundleforappid"></a>updatefinder.offerupdates.nullbundleforappid

Ovaj događaj pokazuje da Microsoft Autoupdate nije mogao da učita informacije o paketu za ID aplikacije naveden u preuzetoj datoteci manifesta. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefinderofferupdatesupdaterulematched"></a>updatefinder.offerupdates.updaterulematched

Ovaj događaj označava da je pronađeno ažuriranje za aplikaciju i osnovnu liniju. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije i informacije o verziji paketa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="updatefinderregisteredapps"></a>updatefinder.registeredapps

Evidentiramo aplikacije koje je MAU instalirao i registrovao, kao i one koje kontroliše. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID aplikacije i informacije o verziji paketa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatefindersuiteinvalidsuiteversion"></a>updatefinder.suite.invalidsuiteversion

Ovaj događaj prijavljuje grešku verzije programskog paketa dok procenjuje da li je ispravka primenljiva. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljene greške.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Suite** – Ime programskog paketa koji se razmatra

### <a name="updatefindersuitekeyvaluemissing"></a>updatefinder.suite.keyvaluemissing

Ovaj događaj prijavljuje grešku tokom pokušaja dodavanja aplikacije u programski paket. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljene greške.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije 

- **Suite** – Ime programskog paketa u koji aplikacija treba da se doda

    
### <a name="updatefindersuitemissingcollateral"></a>updatefinder.suite.missingcollateral

Ažuriranje programskog paketa – Evidentiramo svaki put kada ispravka za programski paket ne može da se primeni jer nedostaje pomoćna datoteka. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Tekst koji navodi prirodu događaja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindersuitestaleversion"></a>updatefinder.suite.staleversion

Ažuriranje programskog paketa – Evidentiramo svaki put kada ispravka za programski paket ne može da se primeni jer je osnovna verzija previše stara. Evidentiramo osnovnu verziju i ID aplikacije paketa. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime programskog paketa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindersuiteupdateapplicable"></a>updatefinder.suite.updateapplicable

Ažuriranje programskog paketa – Evidentiramo svaki put kada ispravka za programski paket može da se primeni. Evidentiramo osnovnu verziju i ID aplikacije paketa. Evidentiramo osnovnu verziju i ID aplikacije paketa. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime, osnovnu verziju i verziju ispravke za programski paket.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindersuiteupdatenotapplicabledefaultpath"></a>updatefinder.suite.updatenotapplicabledefaultpath

Ažuriranje programskog paketa – Evidentiramo svaki put kada se ispravka za programski paket ne nudi jer sve aplikacije programskog paketa nisu instalirane na istoj podrazumevanoj putanji. Evidentiramo osnovnu verziju i ID aplikacije paketa. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime, osnovnu verziju i verziju ispravke za programski paket.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="updatefindersuiteupdatenotapplicableversion"></a>updatefinder.suite.updatenotapplicableversion

Ažuriranje programskog paketa – Evidentiramo svaki put kada se ispravka za programski paket ne nudi jer sve aplikacije programskog paketa nemaju istu osnovnu verziju. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime, osnovnu verziju i verziju ispravke za programski paket.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindersuiteupdatenotoffered"></a>updatefinder.suite.updatenotoffered

Ažuriranje programskog paketa – Evidentiramo svaki put kada se ispravka za programski paket ne nudi jer je veličina programskog paketa veća od pojedinačnih ispravki. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime programskog paketa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatefindersuiteupdateoffered"></a>updatefinder.suite.updateoffered

Ažuriranje programskog paketa – Evidentiramo svaki put kada se nudi ispravka za programski paket. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ime, osnovnu verziju i verziju ispravke za programski paket.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatemanagercheckupdate"></a>updatemanager.checkupdate

Ovaj događaj evidentira broj ispravki koje je Microsoft Autoupdate pronašao tokom provere da li postoje dostupne ispravke. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži broj pronađenih dostupnih ispravki.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="updatemanagernetwork"></a>updatemanager.network

Ovaj događaj evidentira mrežnu dostupnost. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme kada je primljena telemetrija

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Serverreacheable** – Bulov izraz koji ukazuje na to da li je mreža dostupna.

    
### <a name="updatemanagerupdatespending"></a>updatemanager.updatespending

Ovaj događaj označava da su pronađene ispravke koje čekaju na instalaciju. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži naznaku toga da li je zadatak pokrenut u glavnoj niti i broj ispravki na čekanju.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="updatestatuscodesign"></a>UpdateStatus.Codesign

Ovaj događaj izveštava o statusu iz programa za verifikaciju klijenta za Office dizajn koji se izvršava nakon instaliranja ispravki klijentske aplikacije. Koristite ovaj događaj da biste obezbedili važeće pakete i ažuriraćemo instalirane aplikacije za najnoviju verziju.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppID** – Identifikator za aplikaciju koja se ažurira

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Error** – Greške koje su uočene tokom procesa verifikacije zajedničkog dizajna

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

- **Success** – Ukazuje na to da li je verifikacija zajedničkog dizajna uspela

- **UpdateID** – Jedinstveno identifikuje primenjenu ispravku 

- **UpdateName** – Ime ispravke kao što je opisano u manifestu ispravke

- **UpdatePkg** – Ime primenjenog paketa ispravki

### <a name="urlutilitiesgetmauinfo"></a>urlutilities.getmauinfo

Ovaj događaj izveštava da je došlo do greške prilikom pristupanja paketu Microsoft automatskog ažuriranja (MAU) aplikacije. Ovaj događaj je kritičan i koristi se za ispitivanje prijavljene greške.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o grešci na koju se naišlo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije
   
### <a name="webservicescheckforsilentupdates"></a>webservices.checkforsilentupdates

Ovaj događaj označava da su pronađeni kandidati za tiho ažuriranje. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži broj pronađenih ispravki i ID aplikacije.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="webservicesdeltaupdater"></a>webservices.deltaupdater

Ovaj događaj evidentira interakcije između koda klijenta i prolaza funkcije koji kontroliše to da li klijent treba da dozvoli Delta ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži odgovor veb usluga i vrstu programa za ažuriranje koji se primenjuje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="webservicesserviceaction"></a>webservices.serviceaction

Evidentiramo sve greške do kojih dolazi usled neočekivanog odgovora veb usluge. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži detalje radnje koja se prosleđuje iz veb usluga.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="webservicesserviceresponse"></a>webservices.serviceresponse

Ovaj događaj evidentira zahteve za MAU uslugu, vreme odziva i greške. Ovaj događaj koristimo da bismo osigurali da postupak ažuriranja radi kako se očekuje i da bismo pomogli u rešavanju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID zahteva, ime aplikacije, vreme odziva i/ili kôd statusa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

    
### <a name="webservicessilentupdate"></a>webservices.silentupdate

Evidentiramo zahteve za proverom da li postoje pravila za primenu „nametnutih ispravki“, to jest moramo da prebacimo korisnika sa verzije N na verziju N+1 zbog nekog velikog problema. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID zahteva, ime aplikacije, vreme odziva i/ili kôd statusa.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="webservicesupdatefiltering"></a>webservices.updatefiltering

Ovaj događaj ukazuje na to da je filtriranje izvedeno na listi primenljivih ispravki preko Veb usluga. Koristite ovaj događaj da biste obezbedili da aplikacioni funkcionišu ispravno ako treba da blokiramo ispravku.

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o broju ispravki koje su blokirane putem veb usluga

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="webserviceswebcontent"></a>webservices.webcontent

Evidentiramo zahteve i odgovore primljene u veb uslugama. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowTocheck** – Željene opcije za proveru da li postoje ispravke

- **Payload** – Sadrži ID pozivaoca veb usluge

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije

### <a name="webserviceswhatsnew"></a>webservices.whatsnew

Ovaj događaj se pokreće kada su Microsoft automatske ispravke (MAU) upiti Veb-usluge na funkciji "Šta je novo" za registrovane aplikacije. Ovaj događaj se koristi za utvrđivanje stanja funkcije „Šta je novo“. 

Prikupljaju se sledeća polja:

- **App** – Proces aplikacije koji šalje događaj

- **AppInfo_Language** – Jezik koji aplikacija koristi

- **AppVersionLong** – Verzija aplikacije

- **Channel** – Željene opcije za korisnike

- **Device_NetworkCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **DeviceID** – Identifikator uređaja

- **DeviceInfo_Model** – Model hardvera uređaja

- **DeviceInfo_NetworkType** – Tip mreže (Wi-Fi, žična, nepoznato)

- **DeviceInfo_OsBuild** – Verzija operativnog sistema

- **Event_ReceivedTime** – Vreme prijema telemetrije

- **EventInfo_Name** – Ime događaja telemetrije koji se evidentira

- **EventInfo_Time** – Vreme dešavanja evidentiranog događaja telemetrije 

- **HowToCheck** – Kako proveriti postavku

- **Payload** – Sadrži informacije o broju aplikacija sa informacijama o tome šta je novo

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije

## <a name="onenote-sync-events"></a>Događaji sinhronizovanja programa OneNote

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ovaj događaj evidentira rezultat sinhronizovanja sveske. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote.
 
Prikupljaju se sledeća polja

- **CachedError_Code** – Numerički ili alfanumerički kôd koji se koristi za određivanje prirode keširane greške i/ili toga zbog čega je do nje došlo

- **CachedError_Description** – Opis keširane greške

- **CachedError_Tag** – Pokazuje gde se u kodu javlja keširana greška

- **CachedError_Type** – Tip keširane greške, na primer Win32Error itd.

- **ExecutionTime** – Vreme u milisekundama potrebno za kopiranje beležnice

- **Gosid** – Globalni ID prostora objekta

- **IdentityType** – Tip identiteta, na primer Windows Live, Org ID itd.

- **InitialReplicationInSession** – Pokazuje da li je ova replikacija prva replikacija beležnice posle otvaranja ili nije

- **IsBackgroundSync** – Pokazuje da li je ovo sinhronizacija u pozadini ili nije

- **IsCachedErrorSuppressed** – Pokazuje da li je keširana greška potisnuta ili nije

- **IsCachedErrorUnexpected** – Pokazuje da li je keširana greška neočekivana ili nije

- **IsNotebookErrorSuppressed** – Pokazuje da li je greška pri sinhronizaciji na nivou beležnice potisnuta ili nije

- **IsNotebookErrorUnexpected** – Pokazuje da li je greška pri sinhronizaciji na nivou beležnice neočekivana ili nije

- **IsSectionErrorSuppressed** – Pokazuje da li je greška pri sinhronizaciji odeljka potisnuta ili nije

- **IsSectionErrorUnexpected** – Pokazuje da li je greška pri sinhronizaciji odeljka neočekivana ili nije

- **IsUsingRealtimeSync** – Pokazuje da li sinhronizovanje beležnice koristi modernu sinhronizaciju sadržaja stranice ili ne

- **LastAttemptedSync** – Vremenska oznaka kada je poslednji put pokušano sinhronizovanje beležnice

- **LastBackgroundSync** – Vremenska oznaka kada je poslednji put pokušano sinhronizovanje u pozadini

- **LastNotebookViewedDate** – Datum kada je beležnica poslednji put prikazana

- **LastSuccessfulSync** – Vremenska oznaka kada je beležnica prethodno uspešno sinhronizovana

- **NeedToRestartBecauseOfInconsistencies** – Pokazuje da li sinhronizacija mora ponovo da se pokrene zbog nedoslednosti ili ne

- **NotebookErrorCode** – Kôd greške pri sinhronizaciji na nivou beležnice sačuvan u prostoru za grafikon beležnice

- **NotebookId** – ID beležnice

- **NotebookType** – Tip beležnice

- **ReplicatingAgainBecauseOfInconsistencies** – Pokazuje da li se sinhronizacija ponovo pokreće zbog nedoslednosti ili ne

- **SectionError_Code** – Numerički ili alfanumerički kôd koji se koristi za određivanje prirode greške pri sinhronizaciji odeljka i/ili toga zbog čega je do nje došlo

- **SectionError_Description** – Opis greške pri sinhronizaciji odeljka

- **SectionError_Tag** – Pokazuje gde se u kodu javlja greška pri sinhronizaciji odeljka

- **SectionError_Type** – Tip greške pri sinhronizaciji odeljka, na primer Win32Error itd.

- **Success** – Pokazuje da li je beležnica uspešno sinhronizovana ili nije

- **SyncDestinationType** – Tip odredišta sinhronizacije, to jest OneDrive ili SharePoint Online

- **SyncId** – Broj jedinstven za svako sinhronizovanje beležnice

- **SyncWasFirstInSession** – Pokazuje da li je ova sinhronizacija prva sinhronizacija u trenutnoj sesiji

- **SyncWasUserInitiated** – Pokazuje da li je ovu sinhronizaciju pokrenuo korisnik ili nije

- **TenantId** – ID SharePoint zakupca

- **TimeSinceLastAttemptedSync** – Vreme proteklo od poslednjeg pokušaja sinhronizacije beležnice

- **TimeSinceLastSuccessfulSync** – Vreme proteklo od poslednje uspešne sinhronizacije beležnice

### <a name="officeonenotestoragerealtimewebsocketsessioninfo"></a>Office.OneNote.Storage.RealTime.WebSocketSessionInfo
 
Ovaj događaj evidentira rezultat sinhronizovanja veb priključka za obe sinhronizacije programa OneNote: modernu sinhronizaciju sadržaja stranice i modernu sinhronizaciju hijerarhije. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote. Koristi se i za kontrolnu tablu performansi moderne sinhronizacije programa OneNote.
 
Prikupljaju se sledeća polja:
 
- **CloseReason** – Razlog zatvaranja veb priključka, na primer nestandardno zatvaranje itd.

- **DataIsFreshCount** – Broj uspešnih zahteva za pregled izmena u sesiji veb priključka

- **DeviceSessionId** – ID sesije uređaja

- **DownloadCount** – Broj preuzimanja u sesiji veb priključka

- **Error** – U osnovi predstavlja: Exception_Type + Exception_Description + Exception_Code + Exception_Tag

- **Exception_Code** – Numerički ili alfanumerički kôd koji se koristi za određivanje prirode greške i/ili toga zbog čega je do nje došlo

- **Exception_Description** – Opis greške

- **Exception_Tag** – Pokazuje gde se u kodu javlja greška

- **Exception_Type** – Tip greške, na primer Win32Error itd.

- **FirstUpdateSize** – Dužina poruke o prvom ažuriranju

- **HasError** – Pokazuje da li postoji greška tokom sesije veb priključka 

- **IsEducationNotebook** – Pokazuje da li je trenutna beležnica obrazovna beležnica ili nije

- **IsHierarchyResource** – Pokazuje da li je trenutni resurs stranica ili odeljak

- **NotebookId** – ID OneNote beležnice

- **OperationWithError** – Pokazuje u kojoj operaciji je došlo do greške, na primer WebSocket.Close, WebSocket.Open itd.

- **ResourceId** – ID resursa OneNote stranice ili odeljka

- **SectionId** – ID OneNote odeljka

- **ServerSessionId** – ID sesije koji se koristi za korelaciju zahteva veb priključka sa sajtom onenote.com

- **SessionDurationInMs** – Trajanje sesije veb priključka u milisekundama

- **TenantId** – ID SharePoint zakupca

- **TimeToFirstUpdateInMs** – Vreme u milisekundama potrebno za prijem prve ispravke sa strane servera posle uspostavljanja sesije veb priključka

- **UploadAckCount** – Broj potvrda za otpremanje u sesiji veb priključka

- **WebUrl** – PII čišćenje veb URL adrese 

### <a name="officeonenotestoragesectionsyncresult"></a>Office.OneNote.Storage.SectionSyncResult
 
Ovaj događaj evidentira rezultat sinhronizacije odeljka. Koristi se za otkrivanje koliko jedinstvenih ciljeva sinhronizacije izračunava OneNote rezultat sinhronizacije. Takođe se koristi za OneNote modernu kontrolnu tablu performansi sinhronizacije.
 
Prikupljaju se sledeća polja

- **Error_Code** – Numerički ili alfanumerički kôd koji se koristi za određivanje prirode greške i/ili toga zbog čega je do nje došlo

- **Error_Description** – Opis greške

- **Error_Tag** – Pokazuje gde se u kodu javlja greška

- **Error_Type** – Tip greške, na primer Win32Error itd.

- **ErrorLast** – Kôd greške poslednje viđene greške 

- **ExecutionTime** – Vreme u milisekundama potrebno za kopiranje odeljka

- **InitialReplicationInSession** – Pokazuje da li je ova replikacija prva replikacija beležnice posle otvaranja ili nije

- **IsAttachedViaShortcut** – Pokazuje da li je odeljak priložen putem prečice ili nije

- **IsBackgroundSync** – Pokazuje da li je ovo sinhronizacija u pozadini ili nije

- **IsEncrypted** – Pokazuje da li je odeljak šifrovan ili nije

- **IsErrorSuppressed** – Pokazuje da li je ova greška potisnuta ili nije 

- **IsErrorTransient** – Pokazuje da li je ova greška privremena ili nije

- **IsErrorUnexpected** – Pokazuje da li je ova greška neočekivana ili nije

- **IsUsingRealtimeSync** – Pokazuje da li sinhronizovanje odeljka koristi modernu sinhronizaciju sadržaja stranice ili ne

- **NotebookId** – ID beležnice

- **NotebookPath** - PII čišćenje URL adrese beležnice

- **SectionPath** - PII čišćenje URL adrese odeljka

- **SectionReplicatingIsOutbound** – Pokazuje da li je ova replikacija odlazna ili nije

- **SectionReplicatingIsSameIdentity** – Pokazuje da li je ova replikacija zasnovana na istom identitetu datoteke ili nije

- **SectionResourceId** – ID resursa OneNote odeljka

- **Success** – Pokazuje da li je odeljak uspešno sinhronizovan ili nije

- **SyncDestinationType** – Tip odredišta sinhronizacije, to jest OneDrive ili SharePoint Online

- **SyncId** – Broj jedinstven za svaku sinhronizaciju odeljka

- **SyncWasFirstInSession** – Pokazuje da li je ova sinhronizacija prva sinhronizacija u trenutnoj sesiji

- **SyncWasUserInitiated** – Pokazuje da li je ovu sinhronizaciju pokrenuo korisnik ili nije

- **TenantId** – ID SharePoint zakupca

- **UnmappedGosid** – ID odeljka pre nego što se primeni GUID za mapiranje


### <a name="officeonenotestoragesyncscore"></a>Office.OneNote.Storage.SyncScore
 
Ovaj događaj evidentira sve negativne faktore u utisku pri radu sa sinhronizovanjem koje korisnici mogu da vide. Koristi se za izračunavanje rezultata sinhronizacije programa OneNote koji predstavlja ključnu metriku za procenu utiska korisnika pri radu sa sinhronizovanjem u programu OneNote.
 
Prikupljaju se sledeća polja

- **AutoShowSyncStatus** – Pokazuje to da li se status sinhronizovanja prikazuje automatski ili ne

- **Cause** – Pokazuje zašto su OneNote stranice/odeljci premešteni u odeljke na pogrešnom mestu

- **Context** – Identifikator koji kategorizuje to što korisnik pokušava da uradi, na primer preimenovanje odeljka, ponovno otvaranje beležnice itd.

- **Error_Code** – Numerički ili alfanumerički kôd koji se koristi za određivanje prirode greške i/ili toga zbog čega je do nje došlo

- **Error_Description** – Opis greške

- **Error_Tag** – Pokazuje gde se u kodu javlja greška

- **Error_Type** – Tip greške, na primer Win32Error itd.

- **ErrorText** – Tekst greške prikazan u korisničkom interfejsu

- **Explanation** – Objašnjava koje je odlazne promene na čekanju potrebno premestiti u odeljke na pogrešnom mestu

- **fishbowlType** – Vrsta akvarijuma, na primer akvarijum stranice, akvarijum odeljka itd.

- **IDS** – Identifikator vrednosti celog broja za tekst prikazan u korisničkom interfejsu

- **idsFishbowl** – Identifikator vrednosti celog broja za grešku akvarijuma prikazanu u korisničkom interfejsu

- **IsUsingRealtimeHierarchySync** – Pokazuje da li se koristi moderna sinhronizacija hijerarhije ili ne

- **NotebookId** - ID beležnice

- **PageSyncUIState** - Niska statusa sinhronizovanja stranice, na primer UpToDate, Syncing, SaveOffline, SyncError itd. 

- **ServerGosid** – ID resursa za novu napravljenu stranicu sa neusaglašenostima

- **Source** – Identifikator koji pokazuje koji je događaj pokrenuo korisnički interfejs, to jest napravio novu Redx sliku, grešku pri sinhronizovanju u korisničkom interfejsu sinhronizacije, prikazani dijalog greške itd.

### <a name="onenoteappprovisioningmovelocalnotebooktoonlinenotebookfailed"></a>OneNote.App.Provisioning.MoveLocalNotebookToOnlineNotebookFailed
 
Ovaj događaj se evidentira kada ne uspe premeštanje lokalne beležnice na disk jedinicu.  Ovaj slučaj je specifičan za korisnika u odloženom režimu prijavljivanja. Kada se korisnik prijavi, lokalna beležnica će se preneti na skladište usluge OneDrive. 
 
Prikupljaju se sledeća polja:
 
- **ErrorMsg** - Poruka o grešci koja odgovara neuspehu.

### <a name="onenotestorageconnectivitychanged"></a>OneNote.Storage.ConnectivityChanged

Događaj se evidentira bez obzira da li korisnik ima vezu sa internetom. Ovo se koristi za uzajamno povezivanje sa drugom metrikom performansi sinhronizacije, omogućavajući nam da zanemarimo događaje koji se dešavaju dok korisnik nema vezu sa Internetom, jer ne očekujemo da bi kašnjenje u usluzi bilo prihvatljivo bez veze sa Internetom. To nam omogućava da proračunamo tačan broj sesija za naše metrike, kroz isečke klijenata (po zakupcu, po sektoru). Koristimo ga i da bi filtrirali izveštaje o greškama jer postoje brojne greške sinhronizacije za koje očekujemo da se pojave bez mrežnog povezivanja, što u suprotnom garantuje istragu.

Ukoliko ne primimo ove podatke, nećemo moći da precizno nadgledamo performanse proizvoda ili utvrdimo da li su greške koje korisnik iskusi, očekivane ili zahtevaju dalju istragu. 

Prikupljaju se sledeća polja:

- **InternetConnectivityNowAvailable** – ako je došlo do promene stanja veze, tako da je sada internet

### <a name="onenotestoragelegacyinboundlatency"></a>OneNote.Storage.LegacyInboundLatency

Kritičan signal koji se koristi za praćenje performansi ulaznih operacija sinhronizacije, koje komuniciraju direktno sa SharePoint, uključujući povezivanje informacija koje nam omogućavaju da nadgledamo i istražujemo performanse otpremanja podataka ka našoj usluzi (onenote.com). Ovaj signal se sakuplja za najgore izvedena preuzimanja u poslednjih 300 sekundi (broj sekundi konfiguriše Microsoft u zavisnosti od performansi i uslova usluge).

Ovo se koristi za obezbeđivanje ispravnosti usluge dopuštajući nam da vidimo koji zakupci prolaze kroz neprihvatljivo spor dolazak podataka u našu uslugu, informacije o podacima koje su otpremali kada su doživeli spor dolazak i koliko je rasprostranjen problem sa kašnjenjem među zakupcima. Koristi se i za izveštavanje o ispravnosti i performansama usluge za sve naše klijente, radi merenja trendova tokom vremena i automatskog upozorenja o problemima za ublažavanje inženjeringa. Ako nemamo ove podatke, to će nas sprečiti da osiguramo adekvatne performanse kada se sinhronizovanje korisnika promeni u sistemu SharePoint.

Prikupljaju se sledeća polja: 

- **IsEducationNotebook** – Bulova vrednost koja ukazuje da li je beležnica, beležnica za obrazovanje

- **NotebookId** – ID beležnice čiji je deo ovo otpremanje

- **TimeToConfirmSyncedWithServerInMs** – Vreme, u milisekundama, koje je bilo potrebno da se izvrši otpremanje

### <a name="onenotestoragelegacyoutboundlatency"></a>OneNote.Storage.LegacyOutboundLatency

Kritičan signal koji se koristi za praćenje performansi odlaznih operacija sinhronizacije koje direktno komuniciraju sa SharePoint, uključujući informacije o međusobnom povezivanju, koje nam omogućavaju da nadgledamo i istražujemo performanse otpremanja podataka ka našoj usluzi (onenote.com). Ovaj signal se sakuplja za najgore izvedena preuzimanja u poslednjih 300 sekundi (broj sekundi konfiguriše Microsoft u zavisnosti od performansi i uslova usluge).

Ovo se koristi za obezbeđivanje ispravnosti usluge, omogućavajući nam da vidimo koji zakupci prolaze kroz neprihvatljivo sporo odlaženje podataka ka našoj usluzi, informacije o podacima koje su otpremali kada su iskusili sporo odlaženje i koliko je rasprostranjen problem sa kašnjenjem među zakupcima. Koristi se i za izveštavanje o ispravnosti i performansama usluge za sve naše klijente, radi merenja trendova tokom vremena i automatskog upozorenja o problemima za ublažavanje inženjeringa. Ako nemamo ove podatke, to će nas sprečiti da osiguramo adekvatne performanse kada se sinhronizovanje korisnika promeni u sistemu SharePoint. 

Prikupljaju se sledeća polja: 

- **IsEducationNotebook** – Bulova vrednost koja ukazuje da li je beležnica, beležnica za obrazovanje

- **NotebookId** – ID beležnice čiji je deo ovo otpremanje

- **TimeToConfirmSyncedWithServerInMs** – Vreme, u milisekundama, koje je bilo potrebno da se izvrši otpremanje

### <a name="onenotestoragerealtimefiledataobjectdownload"></a>OneNote.Storage.RealTime.FileDataObjectDownload 

Kritičan signal koji se koristi za praćenje performansi kada korisniku dolazi objekat sa podacima datoteke (tj. ugrađena datoteka ili slika) koja se preuzima direktno iz naše usluge, a ne kao deo operacije sinhronizacije na stranici, odeljku ili beležnici. Ovaj signal se sakuplja za najgore izvedena preuzimanja u poslednjih 300 sekundi (broj sekundi konfiguriše Microsoft u zavisnosti od performansi i uslova usluge).

Ovo se koristi za obezbeđivanje ispravnosti usluge, omogućavajući nam da vidimo koji zakupci prolaze kroz neprihvatljivo sporo preuzimanje podataka iz naše usluge, i koliko je rasprostranjen problem sa kašnjenjem među zakupcima, i izveštavamo o našem ponašanju tokom vremena omogućavajući nam da merimo trendove performanse usluge. Ako vidimo neprihvatljivo kašnjenje objekta za datoteku, takođe ćemo koristiti i ove podatke kako bismo to uzajamno povezali sa signalima od klijenta i usluge u vezi sa poboljšanjima procesa preuzimanja od strane objekta. Takođe delimo podatke na osnovu proširenja preuzetog objekta datoteke, jer imamo drugačija očekivanja na osnovu toga da li je datoteka predstavljena neposredno na podlozi na platnu (npr. slika) ili je posredna datoteka (na primer, tekstualni dokument). Ako ne primimo ove podatke, to će nas sprečiti u nadgledanju performansi tih preuzimanja

Prikupljaju se sledeća polja: 

- **FileSizeInBytes** – veličina datoteke preuzete u bajtovima 

- **IsImage** – Bulova vrednost koja utvrđuje da li datoteka koja se preuzima ima proširenje koje se podudara sa unapred definisanom listom uobičajenih formata slika (.bmp, .emf, .gif, .jpe, .jpeg, .jpg, .png) koje prikazujemo u okviru podloge za pisanje

- **TimeToDownload** – Dužina vremena koje je bilo potrebno za uspešno preuzimanje FDO, na uređaj, iz našeg skladišta blob objekta 

### <a name="onenotestoragerealtimewebsocketdownload"></a>OneNote.Storage.RealTime.WebSocketDownload

Kritičan signal koji se koristi za praćenje performansi ulaznih operacija sinhronizacije, uključujući informacije o međusobnom povezivanju, koje nam omogućavaju da nadgledamo i istražujemo performanse preuzimanja podataka iz naše usluge (onenote.com). Ovaj signal se sakuplja za najgore izvedena preuzimanja u poslednjih 300 sekundi (broj sekundi konfiguriše Microsoft u zavisnosti od performansi i uslova usluge).

Ovo se koristi za obezbeđivanje ispravnosti usluge, omogućavajući nam da vidimo koji zakupci prolaze kroz neprihvatljivo sporo ulaženje podataka iz naše usluge, informacije o podacima koje su preuzimali kada su iskusili sporo ulaženje i koliko je rasprostranjen problem sa kašnjenjem među zakupcima. Koristi se i za izveštavanje o ispravnosti i performansama usluge za sve naše klijente, radi merenja trendova tokom vremena i automatskog upozorenja o problemima za ublažavanje inženjeringa. 

Ako vidimo neprihvatljivo kašnjenje odeljka ili beležnice, koristićemo i ove kako bismo to uzajamno povezali sa drugim signalima klijenta i usluge u vezi sa istim dokumentom za identifikovanje regresije performansi koje nam omogućavaju da pružimo uslugu sa boljim performansama.

Ukoliko ne primimo ove podatke, nećemo moći da nadgledamo performanse ovog aspekta naše usluge, ili uticaj promena na strani servera koje možda smatramo neophodnim zbog korišćenja drugih faktora.

Prikupljaju se sledeća polja:

- **DeviceSessionId** – ID sesije uređaja

- **IsEducationNotebook** – Bulova vrednost koja ukazuje da li je beležnica, beležnica za obrazovanje

- **IsHierarchyResource** – Bulova vrednost koja označava je li resurs hijerarhijski

- **NotebookId** – ID beležnice čiji je deo ovo otpremanje

- **ResourceId** – ID resursa koji otpremamo

- **SectionId** – ID odeljka čiji je deo ovo otpremanje

- **ServerSessionId** – ID sesije servera čiji je deo ovo otpremanje

- **TimeToConfirmSyncedWithServerInMs** – Vreme, u milisekundama, između odlaska korisnika na stranicu i svežnja replikacije koji potvrđuje da je stranica sinhronizovana sa serverom.

- **TimeToFirstUpdateInMs** – Vreme, u milisekundama, između početka ulazne replikacije stranice od strane mašine za sinhronizaciju i operacije replikacije koja se sinhronizuje sa stanjem servera.

### <a name="onenotestoragerealtimewebsocketupload"></a>OneNote.Storage.RealTime.WebSocketUpload

Kritičan signal koji se koristi za praćenje performansi ulaznih operacija sinhronizacije, uključujući informacije o međusobnom povezivanju, koje nam omogućavaju da nadgledamo i istražujemo performanse otpremanja podataka ka našoj usluzi (onenote.com).

Ovo se koristi za obezbeđivanje ispravnosti usluge, omogućavajući nam da vidimo koji zakupci prolaze kroz neprihvatljivo sporo odlaženje podataka ka našoj usluzi, informacije o podacima koje su otpremali kada su iskusili sporo odlaženje i koliko je rasprostranjen problem sa kašnjenjem među zakupcima. Koristi se i za izveštavanje o ispravnosti i performansama usluge za sve naše klijente, radi merenja trendova tokom vremena i automatskog upozorenja o problemima za ublažavanje inženjeringa. Takođe ćemo koristiti ove podatke za praćenje uticaja i efikasnosti poboljšanja koje pružamo našim klijentima i uslugama. 

Ako vidimo neprihvatljivo kašnjenje odeljka ili beležnice, koristićemo ove i podatke kako bismo to uzajamno povezali sa drugim signalima klijenta i usluge u vezi sa istim dokumentom za identifikovanje regresije performansi koje nam omogućavaju da pružimo iskustvo sa boljim performansama.

Ukoliko ne primimo ove podatke, nećemo moći da nadgledamo performanse ovog aspekta naše usluge, ili uticaj promena na strani servera koje možda smatramo neophodnim zbog korišćenja drugih faktora.

Prikupljaju se sledeća polja: 

- **DeviceSessionId** – ID sesije uređaja

- **IsEducationNotebook** – Bulova vrednost koja ukazuje da li je beležnica, beležnica za obrazovanje

- **IsHierarchyResource** – Bulova vrednost koja označava je li resurs hijerarhijski

- **IsWorstTime** – Bulova vrednost koja ukazuje da li je vreme uobičajen događaj otpremanja, ili najgore vreme koje smo videli za ovog klijenta u poslednjih 300 sekundi (broj sekundi konfiguriše Microsoft u zavisnosti od performansi i stanja usluge).

- **NotebookId** – ID beležnice čiji je deo ovo otpremanje

- **RecommendedPutIntervalInMs** – vreme kada je usluga komunicirala sa klijentom kao preporučeni interval stavljanja

- **ResourceId** – ID resursa koji otpremamo

- **SectionId** – ID odeljka čiji je deo ovo otpremanje

- **SenderRequestId** – ID pošiljaoca koji izvršava otpremanje

- **ServerSessionId** – ID sesije servera čiji je deo ovo otpremanje

- **UploadNonSuspendedTimeInMs**– vreme, u milisekundama, koje je bilo potrebno da se izvrši otpremanje, izuzimajući vreme kada je aplikacija bila obustavljena

- **UploadTimeInMs** – Vreme, u milisekundama, koje je bilo potrebno da se stvarno izvrši otpremanje

- **WaitTimeInMs** – Vreme, u milisekundama, između zahteva za otpremanje i započinjanja otpremanja

- **WebUrl** – URL adresa veb lokacije otpremanja (Prijavljen kao PiiWz)

### <a name="onenotestoragesynchealth"></a>OneNote.Storage.SyncHealth

Kritičan signal koji se koristi za praćenje grešaka i izuzetaka koji su se dogodili unutar svežnja sinhronizacije u klijentu programa OneNote, koji nam omogućava da nadgledamo i ublažavamo ove neočekivane uslove.

Ovo se koristi za obezbeđivanje ispravnosti usluge tako što će nam omogućiti da vidimo izveštaje o greškama klijenata u bliskom realnom vremenu, koji nam omogućavaju da odgovaramo na probleme pri sinhronizaciji kada se pojave. Koristi se i za identifikovanje toga koliko je rasprostranjen i obiman problem kroz unakrsno upućivanje na oznaku greške sa kodom klijenta za identifikovanje izvora neuspeha. Prikupljamo i ove podatke kako bismo dobili informacije o našem nastupu kroz vreme i o uticaju i efikasnosti poboljšanja koje pružamo našim klijentima i uslugama. Ako nemamo ove podatke, nećemo moći da proaktivno odgovaramo na uslove greške u usluzi sinhronizacije bez eskalacije klijenata.

Prikupljaju se sledeća polja: 

- **Service** – usluga sinhronizacije koju je klijent koristio kada se dogodila greška (zastarela ili moderna sinhronizacija)

- **Tag** – Oznaka (identifikaciona vrednost) koja predstavlja grešku na koju je klijent naišao tokom postupka sinhronizacije

### <a name="onenotesynccreatenotebookfailed"></a>OneNote.Sync.CreateNotebookFailed
 
Ovaj događaj se evidentira kada ne uspe kreiranje beležnice.  
 
Prikupljaju se sledeća polja:
 
- **NetworkConnection** - Evidentira tip veze koju uređaj trenutno koristi, npr. Wi-Fi, van mreže, 3G 

- **ServerType** - Evidentira tip servera na kom je trebalo da se kreira beležnica.

### <a name="onenotesyncfirstrunerror"></a>OneNote.Sync.FirstRunError
 
Ovaj događaj se evidentira kada korisniku ne uspe sinhronizacija brzih beležaka tokom „Utiska pri prvom pokretanju“ na uređaju. Ovo je specifično za slučaj „Prvog pokretanja“.
 
Prikupljaju se sledeća polja:
 
- **NetworkConnection** - Evidentira tip veze koju uređaj trenutno koristi, npr. Wi-Fi, van mreže, 3G

- **ServerType** - Evidentira tip servera na kom je trebalo da se kreira beležnica „Brze beleške“

## <a name="services-configuration-events"></a>Događaji konfiguracije usluga

Konfiguracija usluga ne prikuplja neophodne podatke o usluzi.

## <a name="telemetry-events"></a>Događaji telemetrije

### <a name="appdeeplink"></a>app.deep.link

Ovaj događaj vam pomaže da pratite korišćenje pokretanja sastanka kalendara u različitim krajnjim tačkama. Ovaj događaj nam omogućava da otkrijemo dve stvari kada je sastanak pokrenut putem aplikacije Skype za posao, i kada je sastanak pokrenut putem aplikacije Teams i da li je instalirana aplikacija Teams.

Prikupljaju se sledeća polja: 

- **account** – Heširani podaci o nalogu koji su izvršili radnju

- **action_type** – izvršena radnja, kao što je pokretanje sastanka ili instaliranje aplikacije

- **aplication** – Aplikacija koja je pokrenuta putem duboke veze, kao što su Teams ili Skype za posao

- **context** – Iskustvo do kojeg se došlo unutar aplikacije, npr. Office_union – word, office_union – excel itd.

- **source** – Poreklo radnje, na primer pokrenuto od korisnika, automatski od strane klijenta itd.


### <a name="officeandroiddocsuipaywallcontrolpaywalloperationmetrics"></a>Office.Android.DocsUI.PaywallControl.PaywallOperationMetrics

*[Ovaj događaj je prethodno imao ime Office.Android.DocsUI.Views.PaywallOperationMetrics.]*

Microsoft to koristi za dobijanje ispravnosti funkcije, uspeha ili stope grešaka za korisnike pri kupovinama, kako bi osigurao odgovarajuća ulaganja za poboljšanje korisničkog iskustva kupca na mobilnim platformama.

Prikupljaju se sledeća polja:

- **OperationTimeInMs** – vreme potrebno za završetak postupka kupovine (dugo – millisekunde)

- **PaywallOperationResult** – upeh/ šifra greške / korisnik otkazan (Enum / int – konačna)

- **PaywallOperationType** – označava vrstu Paywall operacije (enum/ int – konačna)

### <a name="officeandroiddocsuipaywallcontrolpaywallsessiondata"></a>Office.Android.DocsUI.PaywallControl.PaywallSessionData

*[Ovaj događaj je prethodno imao ime Office.Android.DocsUI.Views.PaywallSessionData.]*

Metapodaci zasnovani na sesiji kada se UI Paywall-a prikaže korisniku. Microsoft ovo koristi zarad korisničkog putovanja i razumevanja uređaja i verzije operativnog sistema koji korisnik koristi, radi lakšeg donošenja odluka o investiranju u unapređenje iskustva u tim oblastima.

Prikupljaju se sledeća polja:

- **Verzija aplikacije** – Verzija koda zahtevne aplikacije

- **ClientId** – Anonimni identifikator uređaja jedinstvenog za ne-PII (guID/niska)

- **Ulazna tačka** – Jedinstveni identifikator za kontekstualne ili konstantne ulazne tačke iz zahtevne aplikacije

- **isTablet** – Da li uređaj prikazuje UX tableta

- **OSVersion** – Verzija operativnog sistema Android uređaja

- **SessionId** – GuID: Identifikator sesije jedinstvenog Paywall-a


### <a name="officefirstrunappletelemetryoptin"></a>Office.FirstRun.Apple.TelemetryOptIn

Ovaj događaj se sakuplja za Office aplikacije koje se pokreću u okviru Apple platformi. Događaj se koristi za nadgledanje zdravstvenog stanja našeg protoka telemetrije kod davanja saglasnosti za pokretanje prvog utiska. Prikupljamo kôd koji označava koji tip opcije prikupljanja dijagnostičkih podataka je izabrao korisnik.

Prikupljaju se sledeća polja:

- **Data_EventId** – kôd koji označava željenu opciju za prikupljanje dijagnostičkih podataka koju je odabrao korisnik.

### <a name="officeonenotegetsharepointidsfordocument"></a>Office.OneNote.GetSharePointIdsForDocument

Prikupljeni podaci evidentiraju neuspeh i uspeh preuzimanja SharePoint (SPO) ID-ova za URL dokumenta. Uspeh i neuspeh (uključujući razlog neuspeha) poziva evidentiraju se za sve platforme. Ovaj obeleživač je potreban za praćenje i dijagnozu zdravlja poziva upućenog za dobijanje ID-ova. ID-ovi su potrebni da bi podaci OneNote (koji pripadaju SharePoint sačuvanim beležnicama) bili prikazani u feed-u. 

Prikupljaju se sledeća polja:

- **ErrorCode** – INT vrednost greške

- **ErrorMessage** – niska koja opisuje grešku

- **FailureType** – niska za utvrđivanje tipa greške

- **HttpStatusCode** – HTTP kôd greške za mrežni poziv

- **InnerErrorCode** – int kôd

- **InnerErrorMesage** – poruka za grešku

- **IsSuccess** – Bulova vrednost da je signal uspeo

### <a name="officeonenotegetsharepointidsfordocumentw32old"></a>Office.OneNote.GetSharePointIdsForDocumentW32Old

Telemetrija evidentira scenarije neuspeha i uspeh preuzimanja SharePoint (SPO) ID-ova za URL adresu dokumenta. Uspeh i neuspeh (uključujući razlog neuspeha) poziva se evidentiraju. Ovo je evidentirano samo na staroj win32 platformi. Ovaj obeleživač je potreban za praćenje i dijagnozu zdravlja poziva upućenog za dobijanje ID-ova. ID-ovi su potrebni da bi podaci OneNote (koji pripadaju SharePoint sačuvanim beležnicama) bili prikazani u feed-u. 

Prikupljaju se sledeća polja:

- **ErrorCode** – INT vrednost greške

- **ErrorMessage** – niska koja opisuje grešku

- **FailureType** – niska za utvrđivanje tipa greške

- **HttpStatusCode** – HTTP kôd greške za mrežni poziv

- **InnerErrorCode** – int kôd

- **InnerErrorMesage** – poruka za grešku

- **IsSuccess** – Bulova vrednost da je signal uspeo


### <a name="officesystemgracefulexitgracefulappexitdesktop"></a>Office.System.GracefulExit.GracefulAppExitDesktop

Događaj je pokrenut gracioznim raskidom aplikacija za Office klijentske aplikacije kao što su, ali ne ograničavajući se na, Word, Excel, PowerPoint i Outlook. Korišćenje gracioznog izlaza za merenje ispravnosti proizvoda Office klijenata. Zamišljeno je da bude poslovni kritični signal koji koriste Office inženjeri a bi postigli stabilnost proizvoda.

Prikupljaju se sledeća polja:

- **AppBuild** – Identifikator izdanja verzije ugroženog procesa.
- **AppMajor** – Identifikator glavne verzije ugroženog procesa.
- **AppMinor** – Identifikator međuverzije ugroženog procesa.
- **AppRevision** – Identifikator izdanja verzije ugroženog procesa.
- **BootCompleted** – Da li je Office proces završio pokretanje sistema.
- **DetectionTime** – Vreme kada je otkriven neočekivani izlaz.
- **EcsETag** – Identifikator eksperimenta za proces.
- **HasEdit** – Da li se uređivanje dokumenta dogodilo tokom Office procesa.
- **HasOpen** – Da li je dokument otvoren tokom Office procesa.
- **InstallMethod** – Da li je trenutno izdanje sistema Office instalirano nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.
- **OfficeUILang** – Jezik Office procesa.
- **PreviousBuild** – Izdanje prethodno instalirane verzije.
- **SafeMode** – Bio je Office proces u bezbednom režimu.
- **SessionId** – Jedinstveni identifikator procesa.
- **SessionInitTime** – Vreme kada je počeo ugroženi proces.

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Informacije o korisničkom identitetu koje su potrebne za ispunjavanje podataka koji podležu zahtevima

Prikupljaju se sledeća polja:

  - **IdentityChanged** - Uvek istinito. Identitet je promenjen.

  - **TimerDetectedChange** - Da li je promena otkrivena u redovnom vremenskom pingu.

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Koristi se da bi se utvrdilo da li postoje neuspesi u čitanju postavki privatnosti korisnika iz Roaming prodavnice.

Prikupljaju se sledeća polja:

  - **Oznaka -** Oznaka koda koja pokazuje koja postavka se vratila u skladište postavki.

### <a name="officesystemsessiondatao365"></a>Office.System.SessionDataO365

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **AppId -** Identifikator Office aplikacije na koju se ovi podaci odnose.

  - **ApplicationArchitecture -** Za koju je arhitekturu procesora napravljen sistem Office

  - **AppVersionBuild -** Izdanje verzije Office aplikacije.

  - **AppVersionMajor -** Glavna verzija Office aplikacije.

  - **AppVersionMinor -** Međuverzija Office aplikacije.

  - **AppVersionUpdate -** Izdanje revizije Office aplikacije.

  - **CollectorVersion -** Identifikator verzije za logiku kolekcije klijenta.

  - **DeviceHash -** Jednosmerni heš za identifikator operativnog sistema uređaja.

  - **DeviceName -** Ime uređaja na kome se pokreće Office.

  - **Domain -** Domen uređaja na kome se pokreće Office

  - **IsCeip -** Da li je Office instalacija registrovana u neaktivanom Programu za unapređenje na osnovu korisničkog iskustva

  - **IsDebug -** Da li je to Office izdanje za otklanjanje grešaka

  - **IsImmersive -** Da li je Office aplikacija jedinstvena za Windows ili je sveobuhvatna.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsMicrosoftInternal -** Da li je korisnik koji pokreće Office zaposlen u korporaciji Microsoft

  - **IsO365 -** Da li je Office instalacija deo neaktivnog programa Outlook 365.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut tablet.

  - **IsTerminalServer -** Tačno/netačno da je klijent terminal servera

  - **MaxMemory -** Maksimalna količina radne memorije koja je dostupna uređaju na kome se pokreće Office

  - **OsArchitecture -** Za koju CPU arhitekturu je napravljen operativni sistem na kome se pokreće Office

  - **OsVersionBuild -** Izdanje verzije operativnog sistema.

  - **OsVersionMajor -** Glavna verzija operativnog sistema.

  - **OsVersionMinor -** Međuverzija operativnog sistema.

  - **OsVersionUpdate -** Izdanje revizije operativnog sistema

  - **ProcessFileName –** Ime izvršne aplikacije koja je pokrenuta.

  - **ProcessorArchitecture –** Na kojoj arhitekturi procesora je pokrenut Office.

  - **ProcessorFrequency -** Brzina procesora u megahercima na uređajima na kojima je pokrenut Office.

  - **SessionStart -** Vreme kada je započeto pokretanje Office procesa

  - **UserName -** Ime naloga na kome se pokreće Office

### <a name="officesystemsystemhealthcoremetadata"></a>Office.System.SystemHealthCoreMetadata

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **AppBuild -** Izdanje verzije Office aplikacije.

  - **AppBuildRevision -** Izdanje revizije Office aplikacije.

  - **AppMajorVer -** Glavna verzija Office aplikacije.

  - **AppMinorVer -** Međuverzija Office aplikacije.

  - **CID -** Pseudonim korisničkog identiteta

  - **CollectibleClassifications -** Skup klasifikacije podataka koje je moguće prikupiti.

  - **CollectionTime -** Vreme kada su prikupljeni metapodaci.

  - **DeviceManufacturer -** Proizvođač uređaja na kome je pokrenut Office.

  - **DeviceModel -** Model uređaja na kome se pokreće Office.

  - **FirstRunTime -** Prvi put kada je Office aplikacija pokrenuta.

  - **IsClickToRunInstall -** Da li je Office aplikacija instalirana pomoću usluge „Klikni i pokreni“

  - **IsDebug -** Da li je to Office izdanje za otklanjanje grešaka

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsMsftInternal -** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft.

  - **IsSubscription -** Da li je Office aplikacija instalirana u okviru licence za pretplatu.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut tablet.

  - **IsTerminalServer -** Da li je Office pokrenut na terminal serveru.

  - **MsoAppId -** Identifikator Office aplikacije na koju se ovi podaci odnose.

  - **OfficeArchitectureText -** Za koju je arhitekturu procesora napravljen sistem Office

  - **OsBuild -** Izdanje verzije operativnog sistema.

  - **OsBuildRevision -** Izdanje revizije operativnog sistema

  - **OSEnvironment -** Identifikator okruženja u kome je pokrenut Office.

  - **OsMajorVer -** Glavna verzija operativnog sistema.

  - **OsMinorVer -** Međuverzija operativnog sistema.

  - **OSVersionString -** Verzija operativnog sistema u vidu niske.

  - **ProcessorArchitecture -** Na kojoj arhitekturi procesora je pokrenut Office

  - **ProcessorCount -** Broj procesora na uređaju na kome je pokrenut Office.

  - **ProcSpeedMHz -** Brzina procesora u megahercima na uređajima na kojima je pokrenut Office.

  - **RamMB -** Količina dostupne RAM memorije na uređaju na kome se pokreće Office.

  - **SqmUserId -** Nasumični identifikator instalacije za sistem Office.

### <a name="officesystemsystemhealthdesktopsessionlifecycleandheartbeat"></a>Office.System.SystemHealthDesktopSessionLifecycleAndHeartbeat

Pruža informacije o metrici ispravnosti sistema.

Prikupljaju se sledeća polja:

  - **InstallMethod** - Da li je trenutno izdanje sistema Office instalirano nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **OfficeArchitectureText** – Arhitektura Office proizvoda u vidu niske (npr. x86, arm).

  - **PreviousBuild** – Verzija na koju je Office izdanje nadograđeno ili sa koje je vraćeno.

  - **State** - Stanje u koje je promenjena sesija.

  - **Time** - Vreme kada je stanje sesije promenjeno.

### <a name="officesystemsystemhealthessentialidentitycount"></a>Office.System.SystemHealthEssentialIdentityCount

Prikuplja broj prijavljenih korisničkih identiteta

Prikupljaju se sledeća polja:

  - **AllIdentityCount** - Broj svih identiteta

  - **ValidIdentityCount** - Broj identiteta koji imaju proverenu valjanost

### <a name="officesystemsystemhealthessentialmetadataallidentities"></a>Office.System.SystemHealthEssentialMetadataAllIdentities

Nadgleda stanje naloga koje prepoznaje sistem Office u ovoj sesiji. Koristi se za izolaciju greške kod tipa prijavljivanja na nalog ako je greška karakteristična za tip.

Prikupljaju se sledeća polja:

  - **CollectionTime** - Vreme kada su prikupljene informacije o identitetu.

  - **IdentityType** - Tip potvrde identiteta ili naloga

  - **IdentityUniqueId** - Identifikator pseudonima identiteta

  - **IdentityUniqueIdHashed** - Jednosmerni heš jedinstvenog ID identiteta

### <a name="officesystemsystemhealthmetadataapplicationadditional"></a>Office.System.SystemHealthMetadataApplicationAdditional

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **Alias -** Interni pseudonim kompanije ako je korisnik koji pokreće Office zaposlen u korporaciji Microsoft

  - **AppBuild -** Izdanje verzije Office aplikacije.

  - **AppBuildRevision -** Izdanje revizije Office aplikacije.

  - **AppMajorVer -** Glavna verzija Office aplikacije.

  - **AppMinorVer -** Međuverzija Office aplikacije.

  - **CID -** Pseudonim korisničkog identiteta

  - **CollectibleClassifications -** Skup klasifikacije podataka koje je moguće prikupiti.

  - **DeviceManufacturer -** Proizvođač uređaja na kome je pokrenut Office.

  - **DeviceModel -** Model uređaja na kome se pokreće Office.

  - **DeviceProcessorModel -** Model procesora u uređaju na kome se pokreće Office.

  - **DigitizerInfo -** Informacije o priloženim digitizatorima na uređaju na kome se pokreće Office.

  - **DomainName -** Ime domena kome je pridružen računar (ako jeste) na kome se pokreće Office.

  - **FirstRunTime -** Prvi put kada je Office aplikacija pokrenuta.

  - **HorizontalResolution -** Horizontalna rezolucija ekrana

  - **IsDebug -** Da li je to Office izdanje za otklanjanje grešaka

  - **IsImmersive -** Da li je Office aplikacija jedinstvena za Windows ili je sveobuhvatna.

  - **IsJoinedToDomain -** Da li je uređaj na kome se pokreće Office pridružen domenu.

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsMsftInternal -** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft.

  - **IsOEMInstalled -** Da li je OEM instalirao Office aplikaciju koja se pokreće

  - **IsRunAsAdmin -** Da li je Office aplikacija pokrenuta sa administratorskim pravima.

  - **IsSubscription -** Da li je Office aplikacija instalirana u okviru licence za pretplatu.

  - **MsoAppId -** Identifikator Office aplikacije na koju se ovi podaci odnose.

  - **NumProcPhysCores -** Broj fizičkih jezgara procesora.

  - **OfficeBuild -** Izdanje verzije deljenih biblioteka sistema Office

  - **OfficeBuildRevision -** Izdanje revizije deljenih biblioteka sistema Office

  - **OfficeMajorVer -** Glavna verzija deljenih biblioteka sistema Office.

  - **OfficeMinorVer -** Međuverzija deljenih biblioteka sistema Office.

  - **OsBuild -** Izdanje verzije operativnog sistema.

  - **OsBuildRevision -** Izdanje revizije operativnog sistema

  - **OsMajorVer -** Glavna verzija operativnog sistema.

  - **OsMinorVer -** Međuverzija operativnog sistema.

  - **PowerPlatformRole –** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **ProcessFileName –** Ime izvršne aplikacije koja je pokrenuta.

  - **ProcessorCount -** Broj procesora na uređaju na kome se pokreće Office.

  - **RamMB -** Količina dostupne RAM memorije na uređaju na kome se pokreće Office.

  - **SqmUserId -** Nasumični identifikator instalacije za sistem Office.

  - **StudyId -** Identifikator studije metrike za kvalitet softvera.

  - **VerticalResolution -** Vertikalna rezolucija ekrana

  - **WinUserActType -** Da li je Windows korisnik koji pokreće Office lokalni administrator, administrator sa ovlašćenjima ili normalan korisnik.

### <a name="officesystemsystemhealthmetadataapplicationandlanguage"></a>Office.System.SystemHealthMetadataApplicationAndLanguage

Metapodaci su potrebni da bi se izolovala greška repodukovanja.

Prikupljaju se sledeća polja:

  - **AppBuild -** Izdanje verzije Office aplikacije.

  - **AppBuildRevision -** Izdanje revizije Office aplikacije.

  - **AppMajorVer -** Glavna verzija Office aplikacije.

  - **AppMinorVer -** Međuverzija Office aplikacije.

  - **AppState -** Identifikator stanja u kojem se nalazi Office aplikacija.

  - **Click2RunPackageVersionBuild -** Izdanje verzije instalacionog paketa „Klikni i pokreni“.

  - **Click2RunPackageVersionMajor -** Glavna verzija instalacionog paketa „Klikni i pokreni“.

  - **Click2RunPackageVersionMinor -** Međuverzija instalacionog paketa „Klikni i pokreni“.

  - **Click2RunPackageVersionRevision -** Izdanje revizije instalacionog paketa „Klikni i pokreni“.

  - **DistributionChannel -** Kanal preko kog se distribuirao sistem Office.

  - **InstallType -** Identifikator načina na koji je instaliran sistem Office.

  - **IsClickToRunInstall -** Da li je Office aplikacija instalirana pomoću usluge „Klikni i pokreni“

  - **IsDebug -** Da li je to Office izdanje za otklanjanje grešaka

  - **IsImmersive -** Da li je Office aplikacija jedinstvena za Windows ili je sveobuhvatna.

  - **IsMsftInternal -** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft.

  - **IsOEMInstalled -** Da li je OEM instalirao Office aplikaciju koja se pokreće

  - **IsRunAsAdmin -** Da li je Office aplikacija pokrenuta sa administratorskim pravima.

  - **IsSubscription -** Da li je Office aplikacija instalirana u okviru licence za pretplatu.

  - **MsoAppId -** Identifikator Office aplikacije na koju se ovi podaci odnose.

  - **OfficeArchitectureText -** Za koju je arhitekturu procesora napravljen sistem Office

  - **OfficeBuild -** Izdanje verzije deljenih biblioteka sistema Office

  - **OfficeBuildRevision -** Izdanje revizije deljenih biblioteka sistema Office

  - **OfficeMajorVer -** Glavna verzija deljenih biblioteka sistema Office.

  - **OfficeMinorVer -** Međuverzija deljenih biblioteka sistema Office.

  - **OfficeMuiCount -** Broj instaliranih jezičkih paketa za sistem Office.

  - **OfficeSkuLanguage -** Instalirani jezik SKU.

  - **OfficeSkuLanguageTag -** Instalirani jezik SKU.

  - **OfficeUiLang -** Jezik korisničkog interfejsa za Office aplikaciju.

  - **OfficeUiLangTag -** Jezik korisničkog interfejsa za Office aplikaciju.

  - **ProcessFileName –** Ime izvršne aplikacije koja je pokrenuta.

  - **SqmAppId -** Identifikator Office aplikacije na koju se ovi podaci odnose.

### <a name="officesystemsystemhealthmetadatadelayedlogin"></a>Office.System.SystemHealthMetadataDelayedLogin

Informacije o korisničkom identitetu koje su potrebne za ispunjavanje podataka koji podležu zahtevima

Prikupljaju se sledeća polja:

  - **CID** - Pseudonim korisničkog identiteta

### <a name="officesystemsystemhealthmetadatadevice"></a>Office.System.SystemHealthMetadataDevice

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **CollectionTime -** Vreme kada su prikupljeni metapodaci.

  - **ComputerSystemProductUuidHash -** Jednosmerni heš UUID matične ploče.

  - **DeviceClass -** identifikator tipa uređaja na kome se pokreće Office.

  - **DeviceMake -** Identifikator porodice hardverskog sistema na uređaju na kome se pokreće Office.

  - **DeviceManufacturer -** Proizvođač uređaja na kome se pokreće Office.

  - **DeviceModel -** Model uređaja na kome se pokreće Office.

  - **DigitizerInfo -** Informacije o priloženim digitizatorima na uređaju na kome se pokreće Office.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut tablet.

  - **LicensingACID** Identifikator licenciranja za Office instalaciju.

  - **MachineName -** Ime uređaja na kome je pokrenut Office.

  - **NumProcPhysCores -** Broj fizičkih jezgara procesora.

  - **NumProcShareSingleCache -** Broj procesora koji dele jedan keš na uređaju na kome je se pokreće Office.

  - **NumProcShareSingleCore -** Broj procesora po fizičkom jezgru na uređaju na kome se pokreće Office.

  - **OlsLicenseId** Identifikator usluge licenciranja za Office instalaciju.

  - **Platform -** Identifikator okruženja u kome se pokreće Office.

  - **PowerPlatformRole -** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **ProcessorCount -** Broj procesora na uređaju na kome se pokreće Office.

  - **ProcSpeedMHz -** Brzina procesora u megahercima na uređaju na kome se pokreće Office.

  - **ProcType -** Arhitektura procesora.

  - **ProcTypeText -** Tip procesora u uređaju na kome se pokreće Office.

  - **RamMB -** Količina dostupne RAM memorije na uređaju na kome se pokreće Office.

  - **SusClientId -** Windows Update ID uređaja na kome se pokreće Office.

  - **SystemFamily -** Identifikator porodice hardverskog sistema na uređaju na kome se pokreće Office.

  - **SystemSKU -** Identifikator SKU hardverskog sistema na kome se pokreće Office.

  - **SysVolFreeSpaceMB -** Količina slobodnog prostora koja je dostupna na sistemskom volumenu u megabajtima.

  - **SysVolSizeMB -** Količina prostora koja se nalazi na sistemskom volumenu u megabajtima.

  - **WindowsErrorReportingMachineId -** Windows izveštavanje o greškama dodeljuje identifikator mašine na uređaju na kome se pokreće Office.

  - **WindowsSqmMachineId -** Identifikator mašine koji dodeljuje Windows na uređaju na kome se pokreće Office.

### <a name="officesystemsystemhealthmetadatadeviceconsolidated"></a>Office.System.SystemHealthMetadataDeviceConsolidated

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **BootDiskType -** Disk ili SSD uređaj

  - **ComputerSystemProductUuidHash -** Jednosmerni heš UUID matične ploče.

  - **DeviceClass -** identifikator tipa uređaja na kome se pokreće Office.

  - **DeviceManufacturer -** Proizvođač uređaja na kome se pokreće Office.

  - **DeviceModel -** Model uređaja na kome se pokreće Office.

  - **DeviceProcessorModel -** Model procesora u uređaju na kome se pokreće Office.

  - **DigitizerInfo -** Informacije o priloženim digitizatorima na uređaju na kome se pokreće Office.

  - **HasSpectreFix -** Da li procesor uređaja na kome se pokreće Office ima Spectre ispravku.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut tablet.

  - **MachineName -** Ime uređaja na kome je pokrenut Office.

  - **NumProcPhysCores -** Broj fizičkih jezgara procesora.

  - **NumProcShareSingleCache -** Broj procesora koji dele jedan keš na uređaju na kome je se pokreće Office.

  - **NumProcShareSingleCore -** Broj procesora po fizičkom jezgru na uređaju na kome se pokreće Office.

  - **Platform -** Identifikator okruženja u kome se pokreće Office.

  - **PowerPlatformRole -** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **powerPlatformRole -** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **ProcessorCount -** Broj procesora na uređaju na kome se pokreće Office.

  - **ProcSpeedMHz -** Brzina procesora u megahercima na uređaju na kome se pokreće Office.

  - **ProcType -** Arhitektura procesora.

  - **ProcTypeText -** Tip procesora u uređaju na kome se pokreće Office.

  - **RamMB -** Količina dostupne RAM memorije na uređaju na kome se pokreće Office.

  - **SusClientId -** Windows Update ID uređaja na kome se pokreće Office.

  - **SysVolFreeSpaceMB -** Količina slobodnog prostora koja je dostupna na sistemskom volumenu u megabajtima.

  - **SysVolSizeMB -** Količina prostora koja se nalazi na sistemskom volumenu u megabajtima.

  - **sysVolSizeMB -** Količina prostora koja se nalazi na sistemskom volumenu u megabajtima.

  - **WindowsErrorReportingMachineId** - Windows izveštavanje o greškama koje dodeljuje identifikator mašine na uređaju na kome se pokreće Office.

  - **WindowsSqmMachineId** - Identifikator mašine koji dodeljuje Windows na uređaju na kome se pokreće Office.

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **CollectionTime** - Vreme kada je događaj bio na čekanju za otpremanje

  - **IsTerminalServer** - Tačno/netačno da je klijent terminal servera

  - **OsBuild** - Izdanje verzije operativnog sistema.

  - **OsBuildRevision** - Izdanje revizije operativnog sistema

  - **OSEnvironment** - Windows, iOS, Mac, Android, itd.

  - **OsMajorVer** - Glavna verzija operativnog sistema.

  - **OsMinorVer** - Međuverzija operativnog sistema.

  - **OSSDKVersionCode** - Identifikator verzije za SDK operativnog sistema.

  - **OsSku** - SKU operativnog sistema

  - **OsSuite2** - Identifikator programskog paketa operativnog sistema.

  - **OSVersionString** - Identifikator verzije operativnog sistema.

  - **ServicePackMajorVer** - Glavna verzija servisnog paketa za operativni sistem

  - **ServicePackMinorVer** - Međuverzija servisnog paketa za operativni sistem

### <a name="officesystemsystemhealthmetadataoperatingsystemdevice"></a>Office.System.SystemHealthMetadataOperatingSystemDevice

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **CollectionTime -** Vreme kada je događaj bio na čekanju za otpremanje

  - **DeviceClass -** identifikator tipa uređaja na kome se pokreće Office.

  - **DeviceManufacturer -** Proizvođač uređaja na kome se pokreće Office.

  - **DeviceModel -** Model uređaja na kome se pokreće Office.

  - **DigitizerInfo -** Informacije o priloženim digitizatorima na uređaju na kome se pokreće Office.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut laptop.

  - **IsLaptop -** Da li je uređaj na kome je Office pokrenut tablet.

  - **IsTerminalServer -** Tačno/netačno da je klijent terminal servera

  - **MachineName -** Ime uređaja na kome je pokrenut Office.

  - **NumProcPhysCores -** Broj fizičkih jezgara procesora.

  - **NumProcShareSingleCache -** Broj procesora koji dele jedan keš na uređaju na kome je se pokreće Office.

  - **NumProcShareSingleCore -** Broj procesora po fizičkom jezgru na uređaju na kome se pokreće Office.

  - **OsBuild -** Izdanje verzije operativnog sistema.

  - **OsBuildRevision -** Izdanje revizije operativnog sistema

  - **OSEnvironment -** Windows, iOS, Mac, Android, itd.

  - **OsMajorVer -** Glavna verzija operativnog sistema.

  - **OsMinorVer -** Međuverzija operativnog sistema.

  - **OSSDKVersionCode -** Identifikator verzije za SDK operativnog sistema.

  - **OsSku -** SKU operativnog sistema

  - **OsSuite2 -** Identifikator programskog paketa operativnog sistema.

  - **OSVersionString -** Identifikator verzije operativnog sistema.

  - **Platform -** Identifikator okruženja u kome se pokreće Office.

  - **PowerPlatformRole -** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **ProcessorCount -** Broj procesora na uređaju na kome se pokreće Office.

  - **ProcSpeedMHz -** Brzina procesora u megahercima na uređaju na kome se pokreće Office.

  - **ProcTypeText -** Tip procesora

  - **RamMB -** Količina dostupne RAM memorije na uređaju na kome se pokreće Office.

  - **ServicePackMajorVer -** Glavna verzija servisnog paketa za operativni sistem

  - **ServicePackMinorVer -** Međuverzija servisnog paketa za operativni sistem

  - **SysVolFreeSpaceMB -** Količina slobodnog prostora koja je dostupna na sistemskom volumenu u megabajtima.

  - **SysVolSizeMB -** Količina prostora koja se nalazi na sistemskom volumenu u megabajtima.

### <a name="officesystemsystemhealthmetadataos"></a>Office.System.SystemHealthMetadataOS

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **CountryRegion -** Identifikator postavki operativnog sistema za zemlju/region.

  - **HorizontalResolution -** Horizontalna rezolucija ekrana

  - **IsTerminalServer -** Tačno/netačno da je klijent terminal servera

  - **KeyboardLanguage -** Identifikator jezika na tastaturi uređaja

  - **KeyboardLanguageTag -** Identifikator jezika na tastaturi uređaja

  - **OfficeWvd -** Identifikuje stanje u kome se nalazi Windows virtuelna radna površina.

  - **OsBuild -** Izdanje verzije operativnog sistema.

  - **OsBuildRevision -** Izdanje revizije operativnog sistema

  - **OSEnvironment -** Windows, iOS, Mac, Android, itd.

  - **OsLocale -** Identifikator lokalnog operativnog sistema.

  - **OsLocaleTag -** Identifikator lokalnog operativnog sistema.

  - **OsMajorVer -** Glavna verzija operativnog sistema.

  - **OsMinorVer -** Međuverzija operativnog sistema.

  - **OSSDKVersionCode -** Identifikator verzije za SDK operativnog sistema.

  - **OsSku -** Identifikator za SKU operativnog sistema.

  - **OsSuite2 -** Identifikator programskog paketa operativnog sistema.

  - **OsUiLang -** Jezik korisničkog interfejsa za operativni sistem.

  - **OSVersionString -** Identifikator verzije operativnog sistema.

  - **ScreenDepth -** Dubina ekrana

  - **ScreenDpi -** Tpi ekrana

  - **ServicePackMajorVer -** Glavna verzija servisnog paketa za operativni sistem

  - **ServicePackMinorVer -** Međuverzija servisnog paketa za operativni sistem

  - **SystemLocale -** Lokalna podrazumevana vrednost operativnog sistema

  - **SystemLocaleTag -** Lokalna podrazumevana vrednost operativnog sistema

  - **TimeZoneBiasInMinutes -** Razlika u minutima između lokalnog vremena i UTC vremena.

  - **VerticalResolution -** Vertikalna rezolucija ekrana

### <a name="officesystemsystemhealthmetadatascreencultureusersqmid"></a>Office.System.SystemHealthMetadataScreenCultureUserSqmId

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **Alias -** Radnik u korporaciji Microsoft ili automatizovani korisnički pseudonim

  - **CID -** Pseudonim korisničkog identiteta

  - **CollectibleClassifications -** Klasifikacije podataka koje se mogu prikupljati u skladu s postavkama zaštite privatnosti klijenta

  - **CollectionTime -** Vreme kada je događaj bio na čekanju za otpremanje

  - **CountryRegion -** Identifikator postavki operativnog sistema za zemlju/region.

  - **DomainName -** Ime za Microsoft domen

  - **HorizontalResolution -** Horizontalna rezolucija ekrana

  - **IntegratedScreenSize -** Veličina integrisanog ekrana.

  - **IsJoinedToDomain -** Tačno/netačno da je klijent pridružen domenu

  - **IsLabMachine -** Da li je pomoćni Microsoft računar za testiranje

  - **IsMsftInternal -** Tačno/netačno da je računar u Microsoft korporativnom domenu

  - **IsSubscription -** Da li je Office aplikacija instalirana u okviru licence za pretplatu.

  - **KeyboardLanguage -** Identifikator jezika na tastaturi uređaja

  - **KeyboardLanguageTag -** Identifikator jezika na tastaturi uređaja

  - **OsLocale -** Identifikator lokalnog operativnog sistema.

  - **OsLocaleTag -** Identifikator lokalnog operativnog sistema.

  - **OsUiLang -** Jezik korisničkog interfejsa za operativni sistem.

  - **ScreenDepth -** Dubina ekrana

  - **ScreenDpi -** Tpi ekrana

  - **ScreenXDpi -** Tpi ekrana X

  - **ScreenYDpi -** Tpi ekana Y

  - **SqmUserId -** Nasumični identifikator instalacije za sistem Office.

  - **StudyId -** Identifikator studije metrike za kvalitet softvera.

  - **SystemLocale -** Lokalna podrazumevana vrednost operativnog sistema

  - **SystemLocaleTag -** Lokalna podrazumevana vrednost operativnog sistema

  - **TimeZoneBiasInMinutes -** Razlika u minutima između lokalnog vremena i UTC vremena.

  - **VerticalResolution -** Vertikalna rezolucija ekrana

  - **WinUserActType -** Da li je Windows korisnik koji pokreće Office lokalni administrator, administrator sa ovlašćenjima ili normalan korisnik.

### <a name="officesystemsystemhealthofficelensidentity"></a>Office.System.SystemHealthOfficeLensIdentity

Informacije o korisničkom identitetu koje su potrebne za ispunjavanje podataka koji podležu zahtevima

Prikupljaju se sledeća polja:

  - **CID** - Pseudonim korisničkog identiteta

### <a name="officesystemsystemhealthrollbacksessionmetadata"></a>Office.System.SystemHealthRollbackSessionMetadata

Metapodaci koji su potrebni da bi se izolovala greška reprodukovanja.

Prikupljaju se sledeća polja:

  - **InstallMethod** - Nova instalacija, ažuriranje ili vraćanje

  - **IsSubscription** - Da li je Office aplikacija instalirana u okviru licence za pretplatu.

  - **PreviousBuild** - Izdanje prethodno instalirane verzije

### <a name="officesystemsystemhealthsessionlifecycleandheartbeat"></a>Office.System.SystemHealthSessionLifecycleAndHeartbeat

Pruža informacije o metrici ispravnosti sistema.

Prikupljaju se sledeća polja:

  - **InstallMethod** - Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **InteractionSessionID** - Identifikator sesije.

  - **PreviousBuild** – Verzija na koju je Office izdanje nadograđeno ili sa koje je vraćeno.

  - **State** - Stanje u koje je promenjena sesija.

  - **Vreme** - Trenutak kada se promenilo stanje sesije.

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Koristi se sa podacima o padu da bi se razdvojili rani i kasni padovi (npr. da se odredi da li je korisnik koristio aplikaciju neko vreme pre pada) 

Prikupljaju se sledeća polja:

  - **SessionStart** - Vreme kada telemetrija počinje da obrađuje podatke.

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Događaj pokreće abnormalni završetak aplikacije (primer: zatvaranje upravljača zadacima, obustava aplikacije itd.) Za Office klijentske aplikacije kao što su Word, Excel, PowerPoint i Outlook. Metrike neočekivanog izlaska iz aplikacija koristimo za merenje ispravnosti proizvoda klijenata sistema Office. To je signal, ključan za posao, koji se koristi za postizanje stabilnosti proizvoda.

Prikupljaju se sledeća polja:

  - **AffectedProcessAppBuild -** Identifikator izdanja verzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessAppBuildRevision -** Identifikator izdanja revizije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessAppMajorVer** – Identifikator međuverzije pogođenog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessAppMinorVer -** Identifikator međuverzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessAppName -** Ime ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*
  
  - **AffectedProcessAppVersion** – Identifikator verzije ugroženog procesa.

  - **AffectedProcessExeBuildVersion –** Broj izdanja verzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessExeMajorVersion –** Broj glavne verzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessExeMinorVersion -** Broj međuverzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessExeRevisionVersion –** Broj izdanja verzije revizije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessIsDebug –** Da li je ugroženi proces izdanje za otklanjanje grešaka. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessIsLabMachine –** Da li je ugroženi proces u Microsoft pomoćnim tehnologijama. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AffectedProcessOsEnvironment –** Identifikator operativnog sistema na kome je ugroženi proces. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AppName –** Ime ugrožene aplikacije. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **AppUsedVirtualMemory** – virtuelna memorija koju koristi Office aplikacija

- **BucketId** – Watson identifikator grupe za pad

- **CabGuid** – univerzalni jedinstveni identifikator (GUID) za Watson cab.

- **CallStack** – Microsoft interni stek poziva koji izaziva pad.

- **CrashedAssignedFlights –** Događaji dodeljeni palom procesu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **CrashedConfigIds –** Konfiguracija dodeljena palom procesu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **CrashedEcsETag -** Identifikator eksperimenta palog procesa.

- **CrashedImpressionId -** Identifikator prikaza palog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **CrashedModuleName** – Ime neispravnog modula

- **CrashedProcessSessionID -** Jedinstveni identifikator palog procesa. 

- **CrashedProcessSessionInitTime -** Vreme kada je počeo ugroženi proces. 

- **CrashedProcessSessionUninitTime -** Vreme kada se završio ugroženi proces.

- **CrashTag** – Jedinstveni identifikator za kôd pada.

- **CrashType -** Identifikator grupe za tip pada

- **DetectionTime -** Vreme kada je otkriven neočekivani izlaz. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ErrorString –** Opis greške. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ExceptionAddress –** Adresa u aplikaciji u kojoj je došlo je do greške. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ExceptionCode -** Identifikator grupe za izuzetak.

- **ExceptionInfo** – Informacije o sistemu za izuzetak.

- **FaultAppName -** Ime neispravne aplikacije. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*
- **HangTypeCode** – Predstavlja hang klasu ako je proces visio tokom izvršavanja.

- **InstallMethod -** Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

- **InstallType -** Identifikator načina na koji je instaliran sistem Office. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **InstallTypeName –** Identifikator načina na koji je instaliran sistem Office. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **IsLabMachine –** Da li je Office pokrenut u Microsoft laboratoriji. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **IsMsftInternal –** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleBaseAddress –** Osnovna adresa neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleBuildVersion –** Broj izdanja verzije neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleMajorVersion –** Broj glavne verzije neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleMinorVersion –** Broj međuverzije neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleName –** Ime neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleOffset –** Pomak u bajtovima (heksadecimalnom zapisu) od osnovne adrese gde je došlo je do greške.

- **ModuleRevisionVersion –** Broj izdanja verzije revizije neispravnog modula. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleSize –** Veličina neispravnog modula u bajtovima. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **ModuleVersion** – verzija modula kvara odgovornog za pad.

- **OfficeArchitectureText** – arhitektura instalacije: x64, x86 itd.

- **OfficeUILang** – Jezik korisničkog interfejsa u verziji sistema Office.

- **OSEnvironment -** Identifikator okruženja u kome je pokrenut Office.

- **PreviousBuild -** Izdanje prethodno instalirane verzije

- **ProcessorArchitecture** – Arhitektura procesora za okruženje: x64, x86 itd.

- **SessionFlags** – definiše uslove sesije kao što su: da li je datoteka otvorena ili uređena, da li je otvoren dokument u oblaku, da li je završena sekvenca pokretanja itd. 

- **StackHash** – Obezbeđuje heširani ID za stek grešaka u sistemu Office.

- **SystemAvailableMemory** –dostupna memorija u operativnom sistemu

- **UAETypeName –** Identifikator grupisanja načina na koji je aplikacija nespretno zatvorena. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **UninitLibletId** – Jedinstveni identifikator za neispravnu komponentu pada.

- **VerifyElseCrashTag -** Jedinstveni identifikator mesta na kom je aplikacija pala. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

- **WatsonReportId** – identifikator izveštaja koji se šalje usluzi Windows Watson.

- **WerEventCreatedTime** – vreme oznake za izveštavanje o greškama za Windows.

### <a name="officesystemsystemhealthungracefulappexitimmersive"></a>Office.System.SystemHealthUngracefulAppExitImmersive

Koristi se za snimanje metrike pada.

Prikupljaju se sledeća polja:

  - **AffectedProcessAppBuild -** Identifikator izdanja verzije ugroženog procesa.

  - **AffectedProcessAppBuildRevision -** Identifikator izdanja revizije ugroženog procesa.

  - **AffectedProcessAppMajorVer -** Identifikator glavne verzije ugroženog procesa.

  - **AffectedProcessAppMinorVer -** Identifikator međuverzije ugroženog procesa.

  - **AffectedProcessAppName -** Ime ugroženog procesa.

  - **AffectedProcessExeBuildVersion -** Broj izdanja verzije ugroženog procesa.

  - **AffectedProcessExeMajorVersion -** Broj glavne verzije ugroženog procesa.

  - **AffectedProcessExeMinorVersion -** Broj međuverzije ugroženog procesa.

  - **AffectedProcessExeRevisionVersion -** Broj izdanja verzije revizije ugroženog procesa.

  - **AffectedProcessIsDebug -** Da li je ugroženi proces izdanje za otklanjanje grešaka.

  - **AffectedProcessIsLabMachine -** Da li je ugroženi proces u Microsoft pomoćnim tehnologijama.

  - **AffectedProcessOsEnvironment -** Identifikator operativnog sistema na kome je ugroženi proces.

  - **AppName -** Ime ugrožene aplikacije.

  - **CrashedAssignedFlights -** Događaji dodeljeni palom procesu.

  - **CrashedConfigIds -** Konfiguracija dodeljena palom procesu.

  - **CrashedImpressionId -** Identifikator prikaza palog procesa.

  - **CrashedInteractionSessionID -** Identifikator sesije interakcije ugroženog procesa.

  - **CrashedInteractionSessionTime -** Vreme kada je mogla da se vrši interakcija sa ugroženim procesom.

  - **CrashedProcessSessionID -** Jedinstveni identifikator palog procesa.

  - **CrashedProcessSessionInitTime -** Vreme kada je počeo ugroženi proces.

  - **DetectionTime -** Vreme kada je otkriven neočekivani izlaz.

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **IsMsftInternal -** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft.

  - **OSEnvironment -** Identifikator okruženja u kome je pokrenut Office.

  - **PreviousLifecycleState -** Stanje ugroženog procesa u trenutku pada.

  - **UAETypeName -** Identifikator grupisanja načina na koji je aplikacija nespretno zatvorena.

### <a name="officesystemsystemhealthungracefulapplicationexitwin32"></a>Office.System.SystemHealthUngracefulApplicationExitWin32

Događaj pokreće neočekivani prekid aplikacije (na primer, uklanjanje u upravljaču zadacima, prekid aplikacije, itd.) za Office klijentske aplikacije kao što su, ali ne ograničavajući se na, Word, Excel, PowerPoint i Outlook. Metrike neočekivanog izlaska iz aplikacija koristimo za merenje ispravnosti proizvoda klijenata sistema Office. To je signal, ključan za posao, koji koriste Office inženjeri da bi postigli stabilnost proizvoda.

Prikupljaju se sledeća polja:

  - **AddinExecution** – Zastavica koja vas obaveštava da li se programski dodatak izvršavao i nije završio rad tokom neskladnog napuštanja aplikacije. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **AppUsedVirtualMemory** – virtuelna memorija koju koristi Office aplikacija

  - **BootCompleted** – Da li je pokretanje sistema Office dovršeno u vreme pada. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **BucketId** – Watson identifikator grupe za pad
 
  - **CabGuid** – univerzalni jedinstveni identifikator (GUID) za Watson cab.

  - **CallStack** – Microsoft interni stek poziva koji izaziva pad.

  - **CrashedAppBuild** – verzija izdanja pogođenog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **CrashedAppMajor** – Identifikator glavne verzije pogođenog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*
 
  - **CrashedAppMinor** – Identifikator međuverzije ugroženog procesa. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **CrashedAppVersion** – Identifikator verzije aplikacije za srušeni proces.

  - **CrashedEcsETag** – Identifikator eksperimenta palog procesa.

  - **CrashedModuleName** – Ime neispravnog modula.

  - **CrashedProcessSessionId** – Jedinstveni identifikator palog procesa.

  - **CrashedProcessSessionInitTime** – Vreme kada je pogođeni proces započeo.

  - **CrashedProcessSessionUninitTime -** Vreme kada se završio ugroženi proces.

  - **CrashTag** – Jedinstveni identifikator za kôd pada.

  - **CrashTime** – Vreme koje pokazuje kada je klijent nasilno prekinuo rad. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **CrashType** – Identifikovanje segmenta za tip otkazivanja.

  - **DetectionTime** – Vreme kada je otkriven neočekivani izlaz. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **ExceptionAddress** – Adresa u aplikaciji u kojoj je došlo je do greške. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **ExceptionCode** – Identifikator segmenta za izuzetak.

  - **ExceptionInfo** – Informacije o sistemu za izuzetak.

  - **HandOff** – da li je korisnik kreirao i predao Office proces u novu sesiju. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HangTypeCode** – Predstavlja hang klasu ako je proces visio tokom izvršavanja.

  - **HasEdit** – Da li je korisnik uređivao dokument na klijentu koji je pao. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HasOpen –** Da li je dokument bio otvoren na klijentu koji je pao. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexCrashTag** – Jedinstveni identifikator za kôd pada. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexExceptionAddress** – Adresa u heksadecimalnom obliku u programu u kojem je došlo do kvara. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexExceptionCode** – Identifikator grupe za izuzetak u heksadecimalnom zapisu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexModuleBaseAddress** – Osnovna adresa neispravnog modula u heksadecimalnom zapisu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexModuleOffset** – Pomak u bajtovima (u heksadecimalnom obliku) od osnovne adrese na kojoj je došlo do kvara. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexModuleSize** – veličina neispravnog modula u bajtovima u heksadecimalnom zapisu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **HexVerifyElseCrashTag** – Jedinstveni identifikator mesta na kom je aplikacija pala u heksadecimalnom zapisu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **InstallMethod** – Da li je trenutno izdanje sistema Office instalirano nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **IsLabMachine** – Da li je Office pokrenut u Microsoft laboratoriji. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **ModuleBaseAddress** – Osnovna adresa modula u kvaru. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **ModuleOffset** – Pomak u bajtovima (heksadecimalnom zapisu) od osnovne adrese gde je došlo je do greške.

  - **ModuleSize** – Veličina neispravnog modula u bajtovima. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **ModuleStamp** – oznaka modula koja otkazuje.

  - **ModuleVersion** – verzija modula kvara odgovornog za pad.

  - **OfficeArchitectureText** – Arhitektura Office proizvoda u vidu niske (npr. x86, arm).

  - **OfficeUILang** – Jezik korisničkog interfejsa u verziji sistema Office.

  - **PreviousBuild** – Izdanje prethodno instalirane verzije

  - **ProcessorArchitecture** – Arhitektura procesora za okruženje x64, x86 itd.

  - **SafeMode** – Da li je sesija pokrenuta u bezbednom režimu. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **SessionFlags** – definiše uslove sesije kao što su: da li je datoteka otvorena ili uređena, da li je otvoren dokument u oblaku, da li je završena sekvenca pokretanja itd. 

  - **StackHash** – Obezbeđuje heširani ID za stek grešaka u sistemu Office.

  - **SystemAvailableMemory** –dostupna memorija u operativnom sistemu

  - **UAEOSEnvironment** – Identifikator okruženja operativnog sistema. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **UninitLibletId** – Jedinstveni identifikator za neispravnu komponentu pada.

  - **VerifyElseCrashTag** – Jedinstveni identifikator mesta na kom je aplikacija pala. *[Ovo polje je uklonjeno iz aktuelnih verzija sistema Office, ali se i dalje može pojavljivati u starijim verzijama.]*

  - **WatsonReportId** – identifikator izveštaja koji se šalje usluzi Windows Watson.

  - **WerEventCreatedTime** – vreme oznake za izveštavanje o greškama za Windows.


### <a name="officesystemungracefulapplicationexitdesktopappexit"></a>Office.System.UngracefulApplicationExit.DesktopAppExit

Koristi se za snimanje metrike pada.

Prikupljaju se sledeća polja:

  - **AppBuildVersion -** Identifikator izdanja verzije ugroženog procesa.

  - **AppMajorVersion -** Broj glavne verzije ugroženog procesa.

  - **AppMinorVersion -** Identifikator međuverzije ugroženog procesa.

  - **AppName -** Ime ugrožene aplikacije.

  - **AppRevisionVersion -** Identifikator izdanja revizije ugroženog procesa.

  - **CrashedAssignedFlights -** Događaji dodeljeni palom procesu.

  - **CrashedConfigIds -** Konfiguracija dodeljena palom procesu.

  - **CrashedImpressionId -** Identifikator prikaza palog procesa.

  - **CrashedInteractionSessionId -** Identifikator sesije interakcije palog procesa.

  - **CrashedProcessSessionId -** Jedinstveni identifikator palog procesa.

  - **CrashType -** Identifikator grupe za tip pada

  - **ErrorString -** Opis greške.

  - **ExceptionAddress -** Adresa u aplikaciji u kojoj je došlo je do greške.

  - **ExceptionCode -** Identifikator grupe za izuzetak.

  - **FaultAppName -** Ime neispravne aplikacije.

  - **InstallMethod -** Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **InstallType -** Identifikator načina na koji je instaliran sistem Office.

  - **IsDebug -** Da li je to Office izdanje za otklanjanje grešaka

  - **IsHandledCrash -** Da li je rukovalac pada pozvan tokom pada sesije.

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **ModuleBaseAddress -** Osnovna adresa neispravnog modula.

  - **ModuleName -** Ime neispravnog modula.

  - **ModuleOffset -** Pomak u bajtovima od osnovne adrese gde je došlo je do greške.

  - **ModuleSize -** Veličina neispravnog modula u bajtovima.

  - **OSEnvironment -** Identifikator okruženja u kome je pokrenut Office.

  - **PreviousBuild -** Izdanje prethodno instalirane verzije

  - **PreviousInteractionSessionTime -** Vreme kada je započeta prethodna sesija interakcije.

  - **PreviousLifecycleState -** Identifikator stanja prethodnog životnog ciklusa sesije.

  - **PreviousSessionInitTime -** Vreme kada je započeta prethodna sesija.

  - **StackHash -** Identifikator koji ukazuje na to gde se nalazi kôd zbog kojeg je ugroženi proces pao.

  - **VerifyElseCrashTag -** Jedinstveni identifikator mesta na kom je aplikacija pala.

### <a name="officesystemuserchangeddiagnosticlevel"></a>Office.System.UserChangedDiagnosticLevel

Informacije koje su potrebne da bi se osigurala primena smernica za privatnost koje je izabrao korisnik.

Prikupljaju se sledeća polja:

  - **DiagnosticLevelChanged**: Ukazuje na to da je korisnik promenio dijagnostički nivo.

  - **NewDiagnosticLevel**: Nivo nakon korisnikove promene.

  - **OldDiagnosticLevel**: Nivo koji je korisnik koristio pre promene.

### <a name="officetelemetryariaeventsinkhandlemsadevicetokenresponse"></a>Office.Telemetry.AriaEventSink.HandleMsaDeviceTokenResponse

Signal prekida u usluzi Microsoft naloga.

Prikupljaju se sledeća polja:

  - **RetryCount** - Broj ponovnih pokušaja povezivanja sa uslugom MSA.

### <a name="officetelemetryariaeventsinkrequestmsadevicetoken"></a>Office.Telemetry.AriaEventSink.RequestMsaDeviceToken

Signal prekida u usluzi Microsoft naloga.

Prikupljaju se sledeća polja:

  - **RetryCount** - Broj ponovnih pokušaja povezivanja sa uslugom Microsoft naloga.

### <a name="officetelemetryclientsamplingoverridden"></a>Office.Telemetry.ClientSamplingOverridden

Neophodno da bi se pravilno odredile tarife reprodukcije. Obično se ne odnosi na grupu korisnika verzije „Production“.

Prikupljaju se sledeća polja:

  - **OverriddenMeasureEnabled** - Da li je klijent podešen da šalje još nešto osim neuzrokovanih događaja

  - **OverriddenNumberlinePosition** - Novi broj reda pozicije za ispitivanje.

  - **OverriddenReportedSampleRate** - Novi prijavljeni uzorak tarife

  - **OverriddenSampleRate** - Novi uzorak tarife

  - **PreviousNumberlinePosition** - Pozicija ispitivanja u broju reda.

  - **PreviousSampleRate** - Uzorak tarife pre nego što je zamenjen.

  - **WasMeasureEnabled** - Da li je klijent bio podešen da šalje još nešto osim neuzrokovanih događaja

### <a name="officetelemetrycomplianceeventnotinbasicallowlist"></a>Office.Telemetry.Compliance.EventNotInBasicAllowList

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **EventName** - Ime događaja koji se ne nalazi na listi

### <a name="officetelemetrycompliancemissingdatacategory"></a>Office.Telemetry.Compliance.MissingDataCategory

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **EventName** - Ime događaja kome nedostaje kategorija

  - **IsFromRule** - Da li je došlo do događaja zbog telemetrijskog pravila

### <a name="officetelemetrycompliancemissingdatacategoryinrule"></a>Office.Telemetry.Compliance.MissingDataCategoryInRule

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **RuleId** - ID pravila kome nedostaje kategorija podataka

  - **RuleVersion** - Verzija pravila kojoj nedostaje kategorija podataka

### <a name="officetelemetrydiagnosticdataviewerstatechanged"></a>Office.Telemetry.DiagnosticDataViewerStateChanged

Proverava da li korisnici mogu da vide podatke u trenutku kada oni napuštaju računar tako što će koristiti Prikazivač dijagnostičkih podataka.

Prikupljaju se sledeća polja:

  - **Dialogcanceled** - Da li je otkazan dijalog Prikazivača dijagnostičkih podataka

  - **NewState** - Novo stanje Prikazivača dijagnostičkih podataka

  - **WasDialogUsed** - Da li je korišćen dijalog Prikazivača dijagnostičkih podataka

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Podaci koji su potrebni da bi se izmerila ispravnost usluge konfiguracije telemetrije.

Prikupljaju se sledeća polja:

  - **ParsedConfigCount** - Broj obrađenih dinamičkih konfiguracija

  - **ParsedConfigs** - Broj obrađenih dinamičkih konfiguracija

  - **RejectedConfigCount** - Broj odbijenih konfiguracija

  - **RejectedConfigs** - Broj odbijenih konfiguracija

  - **RejectedConfigsList** – Lista odbijenih konfiguracija razdvojena zarezima

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Podaci koji su potrebni da bi se izmerila ispravnost usluge konfiguracije telemetrije.

Prikupljaju se sledeća polja:

  - **ErrorMessage** - Poruka o grešci obrade

  - **NodeName** - Čvor koji nije uspeo da se obradi

### <a name="officetelemetrydynamicconfigpopulatedrequestignored"></a>Office.Telemetry.DynamicConfig.PopulatedRequestIgnored

Ovaj događaj se generiše kada ne uspemo da postavimo kanal za konfiguraciju telemetrije.

Ovaj događaj ne prikuplja polja.

### <a name="officetelemetrydynamicconfigpopulatetreecalledagain"></a>Office.Telemetry.DynamicConfig.PopulateTreeCalledAgain

Podaci koji su potrebni da bi se izmerila ispravnost usluge konfiguracije telemetrije.

Ovaj događaj ne prikuplja polja.

### <a name="officetelemetryeventquarantined"></a>Office.Telemetry.EventQuarantined

Koriste se da bi se proverilo da li drugi NSD događaji rade ispravno.

Prikupljaju se sledeća polja:

  - **EventName** - Ime događaja koji je u karantinu

  - **Reason** - Razlog za karantin

### <a name="officetelemetryflusheventbuffer"></a>Office.Telemetry.FlushEventBuffer 

Izveštava o veličini bafera događaja i može da ukaže na greške telemetrije koje se odnose na upotrebu velikog bafera. 

Prikupljaju se sledeća polja:

  - **EventCount** - Broj događaja u baferu

  - **FirstPassCount** - Broj događaja u prvom prenosu

  - **SecondPassCount** - Broj događaja u drugom prenosu

### <a name="officetelemetrygetfilteredpayloadsfromdisk"></a>Office.Telemetry.GetFilteredPayloadsFromDisk

Proverava da li rade određeni delovi zastarelog kanala telemetrije na platformama koje ga i dalje koristite.

Ovaj događaj ne prikuplja polja.

### <a name="officetelemetryinvaliddatacontractname"></a>Office.Telemetry.InvalidDataContractName

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **DataContractName** - Ime ugovora o telemetrijskim podacima

  - **EventName** - Ime događaja sa ugovorom o nevažećim podacima

  - **IsRuleEvent** - Tačno/netačno da je pravilo telemetrije implementiralo događaj

### <a name="officetelemetryinvaliddatafieldname"></a>Office.Telemetry.InvalidDataFieldName 

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **DataContractName** - Ime polja sa podacima telemetrije

  - **EventName** - Ime događaja sa nevažećim poljima

  - **IsRuleEvent** - Tačno/netačno da je pravilo telemetrije implementiralo događaj.

### <a name="officetelemetryinvalideventcontractname"></a>Office.Telemetry.InvalidEventContractName 

Izveštava o nevažećim telemetrijskim implementacijama ili primenama

Prikupljaju se sledeća polja:

  - **EventContractName** - Ime nevažećeg ugovora o telemetriji

  - **EventName** - Ime događaja sa nevažećim imenom ugovora

  - **IsRuleEvent** - Tačno/netačno da je pravilo telemetrije implementiralo događaj

### <a name="officetelemetryloadxmlrules"></a>Office.Telemetry.LoadXmlRules

Izveštava da li je uspela obrada telemetrijskih pravila

Prikupljaju se sledeća polja:

  - **DetachedDuration** - Odvojeno trajanje u mikrosekundama

### <a name="officetelemetrymissingfielddetails"></a>Office.Telemetry.MissingFieldDetails

Izveštava o informacijama o polju koje nedostaju da bi se otkrile greške u kucanju u konfiguraciji telemetrije.

Prikupljaju se sledeća polja:

  - **ErrorRuleId** - ID pravila telemetrije koje je zatražilo polje koje nedostaje

  - **ErrorRuleVersion** - Verzija pravila telemetrije koje je zatražilo polje koje nedostaje

  - **EtwEventGuid** - ETW GUID zatraženih polja

  - **EtwEventId** - ID ETW događaja zatraženih polja

  - **MissingFieldName** - Ime zatraženog polja

  - **UlsTagId** - Oznaka koda polja koje nedostaje

### <a name="officetelemetryprocessidlequeuejob"></a>Office.Telemetry.ProcessIdleQueueJob

Izveštava da je obrada telemetrije u stanju mirovanja počela kao što je očekivano.

Prikupljaju se sledeća polja:

  - **DetachedDuration** - Odvojeno trajanje u mikrosekundama

  - **FailureDiagnostic** - Operacija nije uspela

### <a name="officetelemetryredstoneinboxsampling"></a>Office.Telemetry.RedstoneInboxSampling

Stanje uzorkovanja klijenta koje je potrebno da bi se pravilno protumačile druge metrike.

Prikupljaju se sledeća polja:

  - **MeasuresEnabled** - Da li su omogućene mere u sesiji?

  - **SamplingClientIdValue** - Vrednost uzorkovanja za klijent

  - **SamplingKey** - Ključ uzorkovanja za klijent

  - **SamplingMethod** - Metod uzorkovanja za klijent

### <a name="officetelemetryredstoneinboxsamplingcritical"></a>Office.Telemetry.RedstoneInboxSamplingCritical

Stanje uzorkovanja klijenta koje može biti potrebno da bi se pravilno protumačile druge metrike.

Prikupljaju se sledeća polja:

  - **MeasuresEnabled** - Da li su omogućene mere u sesiji?

  - **SamplingClientIdValue** - Vrednost uzorkovanja za klijent

  - **SamplingKey** - Ključ uzorkovanja za klijent

  - **SamplingMethod** - Metod uzorkovanja za klijent

### <a name="officetelemetryruleerrorsaggregated"></a>Office.Telemetry.RuleErrorsAggregated

Izveštavanje o greškama telemetrije. Potrebno je za proveru valjanosti drugih podataka (uključujući NSD).

Prikupljaju se sledeća polja:

  - **ErrorCount** - Broj prijavljivanja greške unutar vremenskog okvira agregacije

  - **ErrorInfo** - Broj informacije o dijagnostičkoj grešci

  - **ErrorRuleId** - ID pravila telemetrije koje je izazvalo grešku

  - **ErrorRuleVersion** - Verzija pravila telemetrije koje je izazvala grešku

  - **WarningInfo** - Broj informacije o dijagnostičkom upozorenju

  - **QueueFlushCount** - Broj pražnjenja reda

  - **QueueFlushDueToSizeLimit** - Veličina posle koje telemetrija prazni red

  - **QueueFlushesDueToSize** - Broj pražnjenja reda koje je uzrokovano veličinom bafera

  - **QueueHardLimit** - Ograničenje isključivanja telemetrije

  - **QueueLimitHitTime** - Kada je dostignuto ograničenje isključivanja

  - **ResultTime** - Vreme događaja

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

Isključivanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Prikupljaju se sledeća polja:

  - **DiskWriteLimit** - Ograničenje veličine diska za telemetrijske podatke

  - **DiskWriteTotal** - Ukupno pisanje diska za telemetrijske podatke

  - **SessionDiskWriteTotal** - Ukupno pisanje diska za telemetrijske podatke tokom sesije

  - **ThrottlingTimestamp** - Vreme kada je sesija ograničena

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

Isključivanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Ovaj događaj ne prikuplja polja.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

Isključivanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Prikupljaju se sledeća polja:

  - **CurrentLimit** - Trenutno ograničenje skladišta

  - **Trajanje** - Trajanje skladišta

  - **Faktor** - Faktor skladišta

  - **HighestImpactingRuleBytes** - Najveći broj bajtova koje je zabeležilo pravilo telemetrije

  - **HighestImpactingRuleId** - ID pravilo koje je zabeležilo najveći broj bajtova

  - **HighestImpactingRuleVersion** - Verzija pravila koje je zabeležilo najveći broj bajtova

  - **MaxLimit** - Maksimalno ograničenje

  - **ThrottlingTimestamp** - Kada je ograničena telemetrija

### <a name="officetelemetryrulesenginethrottled"></a>Office.Telemetry.RulesEngineThrottled

Isključivanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Prikupljaju se sledeća polja:

  - **ThrottlingTimestamp** - Kada je ograničena telemetrija

### <a name="officetelemetryrulesengineulsqueuesizebackgroundprocessinglevelreached"></a>Office.Telemetry.RulesEngineUlsQueueSizeBackgroundProcessingLevelReached

Izveštava da ima previše događaja za obradu koji su na čekanju tokom vremena mirovanja aplikacije.

Prikupljaju se sledeća polja:

  - **BackgroundProcessingLevelInBytes** - Veličina reda koji započinje obradu u pozadini.

  - **CurrentQueueSize** - Broj događaja u nULS redu.

  - **CurrentQueueSizeInBytes** - Veličina nULS reda u bajtovima.

  - **ReachedTimestamp** - Vreme kada je počela obrada u pozadini.

### <a name="officetelemetryrulesresultuploadlatencyrule"></a>Office.Telemetry.RulesResultUploadLatencyRule

Prosečno, minimalno i maksimalno kašnjenje otpremanja rezultata pravila za otpremanje korisnih podataka na svakih sat vremena.

Prikupljaju se sledeća polja:

  - **AverageLatency** - Prosečno kašnjenje otpremanja.

  - **CollectionTime** - Vreme kada su prikupljeni podaci o pravilu otpremanja.

  - **LatencyGE201LE400** - Broj otpremanja sa kašnjenjem koje je veće ili jednako od 201ms i manje ili jednako od 400ms

  - **LatencyGE3001** - Broj otpremanja sa kašnjenjem koje je veće ili jednako od 3001ms.

  - **LatencyGE401LE600** - Broj otpremanja sa kašnjenjem koje je veće ili jednako od 401ms i manje ili jednako od 600ms.

  - **LatencyGE601LE800** - Broj otpremanja sa kašnjenjem koje je veće ili jednako od 601ms i manje ili jednako od 800ms.

  - **LatencyLE200** - Broj otpremanja sa kašnjenjem koje je manje od 200 milisekunde.

  - **MaxLatency** - Najveće kašnjenje koje je primećeno.

  - **MinLatency** - Najmanje kašnjenje koje je primećeno.

### <a name="officetelemetrysamplingpolicy"></a>Office.Telemetry.SamplingPolicy

Stanje uzorkovanja klijenta koje je potrebno da bi se pravilno protumačile druge metrike.

Prikupljaju se sledeća polja:

  - **MeasuresEnabled** - Da li su omogućene mere u sesiji?

  - **SamplingClientIdValue** - Vrednost uzorkovanja za klijent

  - **SamplingKey** - Ključ uzorkovanja za klijent

  - **SamplingMethod** - Metod uzorkovanja za klijent

### <a name="officetelemetrysamplingpolicyeventtrigger"></a>Office.Telemetry.SamplingPolicyEventTrigger

Stanje uzorkovanja klijenta koje je potrebno da bi se pravilno protumačile druge metrike.

Prikupljaju se sledeća polja:

  - **MeasuresEnabled** - Da li su omogućene mere u sesiji?

  - **SamplingKey** - Ključ uzorkovanja za klijent

  - **SamplingMethod** - Metod uzorkovanja za klijent

### <a name="officetelemetrysessiontelemetryruleschanged"></a>Office.Telemetry.SessionTelemetryRulesChanged

Izveštava da je promenjen skup pravila telemetrije.

Prikupljaju se sledeća polja:

  - **ChangedRuleId** - ID pravila telemetrije koje je promenjeno u trenutnoj ispravki.

  - **ChangedRuleVersion** - Verzija pravila telemetrije koje je promenjeno u trenutnoj ispravki.

  - **OperationType** – Dodavanje ili uklanjanje oznake za operaciju

### <a name="officetelemetrysessiontelemetryrulescount"></a>Office.Telemetry.SessionTelemetryRulesCount

Izveštava broj učitanih pravila telemetrije

Prikupljaju se sledeća polja:

  - **CountOfLoadedRules** - Koliko je učitano pravila telemetrije

  - **HadRuleFileAtBoot** - Da li je postojala datoteka pravila telemetrije pri pokretanju aplikacije

### <a name="officetelemetrysessiontelemetryrulesinitialstate"></a>Office.Telemetry.SessionTelemetryRulesInitialState

Izveštava o pravilima telemetrije koja su učitana na početku sesije

Prikupljaju se sledeća polja:

  - **HadRuleFileAtBoot** - Da li je postojala datoteka pravila telemetrije pri pokretanju aplikacije

  - **LoadedRulesCount** - Koliko je učitano pravila telemetrije

  - **LoadedRulesList** - Lista učitanih pravila telemetrije

### <a name="officetelemetrysystemhealthmetadatanetworkcost"></a>Office.Telemetry.SystemHealthMetadataNetworkCost

Cena mreže ukazuje na mogućnost preuzimanja podataka.

Prikupljaju se sledeća polja:

  - **NetworkCost** - Cena nove ograničene ili neograničene mreže

  - **OldNetworkCost** - Cena prethodne ograničene ili neograničene mreže

  - **Tag** - Oznaka izvornog koda koji je otkrio promenu

### <a name="officetelemetrysystemhealthmetadatanetworkcostchange"></a>Office.Telemetry.SystemHealthMetadataNetworkCostChange

Cena mreže ukazuje na mogućnost preuzimanja podataka.

Prikupljaju se sledeća polja:

  - **NewNetworkCost** - Cena nove ograničene ili neograničene mreže

  - **OldNetworkCost** - Cena prethodne ograničene ili neograničene mreže

  - **Tag** - Oznaka izvornog koda koji je otkrio promenu

### <a name="officetelemetrytelemetryactivityaggregationwindowstatistics"></a>Office.Telemetry.TelemetryActivityAggregationWindowStatistics

Izveštava o broju prikupljenih grupa aktivnosti i instanci u svakoj aktivnosti koja se otprema.

Prikupljaju se sledeća polja:

  - **GroupCount** - Broj prikupljenih aktivnosti koje šalju podatke.

  - **InstancesToSend** - Broj instanci prikupljenih aktivnosti koje šalju podatke.

### <a name="officetelemetrytelemetryulsqueueusage"></a>Office.Telemetry.TelemetryUlsQueueUsage

Izveštavanje o greškama telemetrije. Potrebno je za proveru valjanosti drugih podataka (uključujući NSD).

Prikupljaju se sledeća polja:

  - **AverageEventCount** - Prosečan broj događaja u redu

  - **AverageQueueCB** - Prosečna veličina memorije reda

  - **PeakEventCount** - Maksimalan broj događaja reda

  - **PeakQueueCB** - Najveća veličina memorije reda

  - **QueueDisableRuleLimit** - Ograničenje pri kojem se onemogućuju pravila telemetrije

### <a name="officetelemetryulsqueuetopthrottlingtags"></a>Office.Telemetry.UlsQueueTopThrottlingTags

Izveštava o najvažnijim oznakama koje su doprinele zatvaranju ULS reda.

Prikupljaju se sledeća polja:

  - **Tag0 -** Oznaka koja je zauzela najveći prostor reda

  - **Tag0Percent -** Procenat reda koji koristi oznaka0

  - **Tag1 -** Oznaka koja je zauzela 2. po veličini prostor reda

  - **Tag10 -** Oznaka koja je zauzela 11. po veličini prostor reda

  - **Tag10Percent -** Procenat reda koji koristi oznaka10

  - **Tag11 -** Oznaka koja je zauzela 12. po veličini prostor reda

  - **Tag11Percent -** Procenat reda koji koristi oznaka11

  - **Tag12 -** Oznaka koja je zauzela 13. po veličini prostor reda

  - **Tag12Percent -** Procenat reda koji koristi oznaka12

  - **Tag13 -** Oznaka koja je zauzela 14. po veličini prostor reda

  - **Tag13Percent -** Procenat reda koji koristi oznaka13

  - **Tag14 -** Oznaka koja je zauzela 15. po veličini prostor reda

  - **Tag14Percent -** Procenat reda koji koristi oznaka14

  - **Tag1Percent -** Procenat reda koji koristi oznaka1

  - **Tag2 -** Oznaka koja je zauzela treći po veličini prostor reda

  - **Tag2Percent -** Procenat reda koji koristi oznaka2

  - **Tag3 -** Oznaka koja je zauzela četvrti po veličini prostor reda

  - **Tag3Percent -** Procenat reda koji koristi oznaka3

  - **Tag4 -** Oznaka koja je zauzela peti po veličini prostor reda

  - **Tag4Percent -** Procenat reda koji koristi oznaka4

  - **Tag5 -** Oznaka koja je zauzela šesti po veličini prostor reda

  - **Tag5Percent -** Procenat reda koji koristi oznaka5

  - **Tag6 -** Oznaka koja je zauzela sedmi po veličini prostor reda

  - **Tag6Percent -** Procenat reda koji koristi oznaka6

  - **Tag7 -** Oznaka koja je zauzela osmi po veličini prostor reda

  - **Tag7Percent -** Procenat reda koji koristi oznaka7

  - **Tag8 -** Oznaka koja je zauzela deveti po veličini prostor reda

  - **Tag8Percent -** Procenat reda koji koristi oznaka8

  - **Tag9 -** Oznaka koja je zauzela deseti po veličini prostor reda

  - **Tag9Percent -** Procenat reda koji koristi oznaka9

### <a name="officetelemetryvolumetrackingdata"></a>Office.Telemetry.VolumeTrackingData

Događaj količinskog praćenja metrike za događaj telemetrije

Prikupljaju se sledeća polja:

  - **EventThreshold** - Maksimalan broj instanci jednog događaja koje mogu biti poslate u vremenskom okviru

  - **HighestEventCount** - Najveći broj instanci jednog događaja koje su poslate u vremenskom okviru

  - **HighestEventName** - Ime događaja sa najvećim brojem instanci u vremenskom okviru.

  - **TimeWindowInSeconds** - Trajanje vremenskog okvira u sekundama.

  - **TotalEvents** - Ukupan broj događaja koji su poslati tokom vremenskog okvira.

  - **UniqueEvents** - Broj jedinstvenih događaja koji su poslati tokom vremenskog okvira.

### <a name="officetelemetrywritepayloadstodisk"></a>Office.Telemetry.WritePayloadsToDisk

Proverava da li rade određeni delovi zastarelog kanala na platformama koje ga i dalje koristite.

Prikupljaju se sledeća polja:

  - **DetachedDuration** - Odvojeno trajanje u mikrosekundama
