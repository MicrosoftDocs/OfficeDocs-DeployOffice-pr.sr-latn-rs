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
ms.openlocfilehash: 81b5ff2e1451f910f2e9695dba488d39d27b7241
ms.sourcegitcommit: 3f5de6281b8e92c6c41a800f4374211188460320
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34701291"
---
# <a name="essential-services-for-office"></a>Osnovne usluge za Office

> [!IMPORTANT]
> Informacije u ovom članku se odnose na verziju 1904 ili noviju, sledećih Office klijentskih softvera instaliranih na računaru sa operativnim sistemom Windows:
> - Office 365 ProPlus i Office 365 Business
> - Office 365 Personal, Office 365 Home ili druge verzije sistema Office koje su deo pretplate na Office 365.
> - Project i Visio koji se dobijaju uz neke planove pretplata, kao što je plan za Project Online Professional ili Visio Online Plan 2.


Office se sastoji od aplikacija klijentskog softvera i povezanih iskustava dizajniranih tako da vam omogućavaju da efikasnije kreirate, komunicirate i sarađujete. Iako možete da kontrolišete mnoga povezana iskustva koja su dostupna vama ili, ako ste administrator organizacije, vašim korisnicima, postoji i skup usluga koje su od suštinske važnosti za funkcionisanje sistema Office, te stoga ne mogu biti onemogućene. Na primer, usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office. Neophodni podaci o ovim uslugama prikupljaju se i šalju korporaciji Microsoft, bez obzira na bilo koje druge postavke smernica za privatnost koje ste konfigurisali. Možete da vidite ove podatke tako što ćete koristiti Prikazivač dijagnostičkih podataka.

Dodatne informacije potražite u sledećim člancima:

- [Neophodni podaci o usluzi za Office](required-service-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Povezana iskustva u sistemu Office](connected-experiences.md)

Ako ste administrator organizacije, možda će vas zanimati i sledeće:

- [Pregled kontrola privatnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti u programu Office 365 ProPlus](manage-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Lista osnovnih usluga za Office 

Sledeća tabela sadrži listu osnovnih usluga za Office i njihov opis.

| **Usluga**  | **Opis**  |
| ------ | ---- |
| [Potvrda identiteta](#authentication-events) | Potvrda identiteta je usluga koja se nalazi na bilo kom uređaju i koja potvrđuje vaš korisnički identitet u sistemu Office. Ona je potrebna za prijavljivanje u Office, aktiviranje Office licence, pristup vašim datotekama koje su uskladištene u oblaku i za pružanje doslednog iskustva u svim Office sesijama i uređajima.    |
| [Klikni i pokreni](#click-to-run-events) | „Klikni i pokreni“ je tehnologija instaliranja koja se koristi za instalaciju i ažuriranje sistema Office na operativnom sistemu Windows. Ona proverava da li postoje nove verzije sistema Office, a kada nova verzija postane dostupna, preuzima je i instalira. „Klikni i pokreni“ će otkrivati potrebu za preuzimanjem i instaliranjem Office ispravki, kao i bezbednosnih zakrpi.     |
| [Usluga poboljšane konfiguracije (UPK)](#experimentation-and-configuration-service-ecs-events) | UPK omogućava korporaciji Microsoft da ponovo konfiguriše instalacije sistema Office, a da vi ne morate ponovo da ga instalirate. Koristi se za kontrolu postepenog objavljivanja funkcija i ažuriranja, dok se uticaj objavljivanja nadgleda preko dijagnostičkih podataka koji se prikupljaju. Takođe se koristi i za smanjivanje bezbednosnih problema i problema performansi uz pomoć funkcija ili ažuriranja. Osim toga, UPK podržava promene u konfiguraciji koje se odnose na dijagnostičke podatke kako bi se obezbedilo prikupljanje odgovarajućih događaja. |
| [Licenciranje](#licensing-events)     | Licenciranje je usluga zasnovana na tehnologiji oblaka koja održava vašu Office aktivaciju tokom novih instalacija i čuva licencu na vašim uređajima nakon aktivacije. Ona registruje svaki od vaših uređaja i aktivira Office, provera status vaše pretplate na sistem Office i upravlja vašom šifrom proizvoda.    |
| [Konfiguracija usluga](#services-configuration-events)  | Konfiguracija usluga pruža mogućnost ažuriranja postavki konfiguracije za Office da bi se omogućile ili onemogućile funkcije klijenta. Ova funkcija se poziva svaki put kada se pokrene Office aplikacija i pruža detalje o ostalim konfiguracijama i uslugama sistema Office. Konfiguracija usluga takođe kontroliše koje usluge su određene kao osnovne.  |
| [Telemetrija ](#telemetry-events)  | Usluga telemetrije se koristi za prikupljanje dijagnostičkih podataka iz Office aplikacija. Ona omogućava prikupljanje dijagnostičkih podataka koje generiše Office, i obaveznih i opcionalnih. Takođe je odgovorna za delimično prikupljanje neophodnih dijagnostičkih podataka o usluzi za Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Događaji i polja sa podacima za osnovne usluge za Office

Odeljci u nastavku pružaju sledeće informacije:

- Listu događaja za svaku osnovnu uslugu
- Opis svakog događaja
- Listu polja sa podacima u svakom događaju
- Opis svakog polja sa podacima

Možete da vidite ove događaje tako što ćete koristiti Prikazivač dijagnostičkih podataka.



## <a name="authentication-events"></a>Događaji potvrde identiteta

Ovi događaji dijagnostičkih podataka se prikupljaju kada Office pokuša da preuzme token potvrde identiteta, ili tiho ili putem upita.

### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Prikuplja se kada Office prikaže korisniku Forms-Based-Auth upit za prijavljivanje zasnovan na formularu za potvrdu identiteta.

Pored tihog preuzimanja tokena, upit za potvrdu identiteta se koristi da se odredi da li se korisnik nalazi u statusu neispravne potvrde identiteta, što bi za korisnika značilo da je stanje klijenta van mreže, a u najgorem slučaju, neispravna potvrda identiteta može sprečiti preuzimanje licence i dovesti do potpuno neupotrebljivog klijenta.

Upiti za prijavljivanje zasnovani na formularu za potvrdu identiteta (FBA - Forms-Based-Auth) se koriste u nekim scenarijima za lokalnu potvrdu identiteta i uglavnom se trudimo da se to ne dešava jer bi svi trebalo da koriste modernu identifikaciju (modern-Auth) zbog bezbednosnih ranjivosti koje se odnose na FBA.

**Prikupljaju se sledeća polja:**

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

4\) Ovi signali napajaju razne spremnosti otpreme i nadgledanja ispravnosti koja šalju upozorenja da bi naši inženjeri mogli brzo da odreaguju i da smanje vreme ublažavanja kritičnih grešaka koje blokiraju korisnika.

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

  - **Microsoft\_ADAL\_broker\_app\_used** - Prikazuje ime posrednika (npr. Windows Account Management)

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

  - **Microsoft\_ADAL\_http\_event\_coun**t - Broj HTTP poziva koje je uputio ADAL

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

  - **Microsoft\_ADAL\_x\_ms\_request\_id** - Dodatni zahtev koji je obezbedio ID za ADAL uslugu u HTTP zaglavlju.

  - **Platform** - Win32/WinRT/Android/iOS/Mac

  - **Scenarioid** - GUID. Različiti događaji mogu da pripadaju samo jednom scenariju, npr. on može da dodaje novi nalog, ali postoji više različitih upita koji se javljaju kao deo tog scenarija. Ovaj ID omogućava da se korelacija dogodi.

  - **Sessionid** - GUID identifikacija za pokretanje sesije

  - **Skdver** - Verzija SDK MATS klijenta koja se koristi za sačinjavanje ovih podataka

  - **Starttime** - Vreme kada je pozvana akcija\*pokretanja MATS API

  - **Tenantid** - GUID identifikacija zakupca kojoj autorizovani korisnika pripada (u slučajevima kada to nije ADAL).

  - **Uploadid** - Jedinstveni GUID za ovaj događaj koji se koristi za uklanjanje duplikata

  - **Wamapi** - Određuje koji je WAM API pozvan

  - **Wamtelemetrybatch** - Trenutno nekorišćeno. U budućnosti će omogućiti WAM komponenti da odašilje dodatne informacije koje se tiču događaja potvrde identiteta.

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

  - **Data\_ProductReleaseId** - Proizvod koji instaliramo, npr. Office 365 ProPlus

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ pokreće proveru oštećenja da bi proverio da li su Office binarne datoteke ispravne. Koristi se za merenje oštećenja binarnih datoteka sistema Office i određivanje binarnih datoteka koje su oštećene.

Prikupljaju se sledeća polja:

  - **Data\_Active -** Manifest trenutnog protoka koji proveravamo na disku

  - **Data\_ActivePackages -** koje pakete sadrži manifest

  - **Data\_ActiveVersion -** verzija manifesta

  - **Data\_AddFileCount -** koliko datoteka dodajemo

  - **Data\_AddFileFiles -** uzorak datoteke koju dodajemo

  - **Data\_CompressionLevel -** kako su datoteke kompresovane

  - **Data\_CorruptionCheckLevel -** koliko detaljno proveravamo oštećenja, faze

  - **Data\_CorruptSizeCount -** koliko datoteka je oštećeno

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje su oštećene

  - **Data\_CorruptSizeCount -** koliko datoteka ima oštećenu verziju

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje imaju oštećenu verziju

  - **Data\_FileBadDigestCount -** koliko datoteka nismo uspeli da otvorimo

  - **Data\_FileBadDigestFiles -** uzorak datoteka koje nismo mogli da otvorimo

  - **Data\_FileNotSignedCount -** datoteke koje nisu prijavljene

  - **Data\_FileNotSignedFiles -** uzorak datoteka koje nisu prijavljene

  - **Data\_FileNotTrustedCount -** koliko datoteka nije pouzdano

  - **Data\_FileNotTrustedFiles -** uzorak datoteka koje nisu pouzdane

  - **Data\_IncompleteFileCount -** koliko datoteka izgleda nepotpuno

  - **Data\_IncompleteFileFiles -** uzorak datoteka koje su nepotpune

  - **Data\_KeepFileCount -** koliko datoteka ne koristimo

  - **Data\_KeepFileFiles -** uzorak datoteka koje čuvamo

  - **Data\_KeepIncompleteFileCount -** koliko datoteka ne menjamo iako su nepotpune

  - **Data\_KeepIncompleteFileFiles -** uzorak datoteka koje čuvamo, a koje su nepotpune

  - **Data\_MismatchSizeCount -** koliko ima datoteka čija se veličina ne poklapa sa veličinom našeg manifesta

  - **Data\_MismatchSizeFiles -** uzorak datoteka koje se ne podudaraju u veličini

  - **Data\_MismatchVersionCount -** koliko datoteka ima verziju koja je drugačija od verzije našeg manifesta

  - **Data\_CorruptSizeFiles -** uzorak datoteka koje se ne podudaraju u verzijama

  - **Data\_MissingFileCount -** koliko datoteka nedostaje

  - **Data\_IncompleteFileFiles -** uzorak datoteka koje nedostaju

  - **Data\_NotToBeStreamedFileCount -** koliko datoteka ne delimo

  - **Data\_RemoveFileCount -** koliko datoteka uklanjamo

  - **Data\_RemoveFileFiles -** uzorak datoteka koje uklanjamo

  - **Data\_StreamUnitsMismatchCount -** koliko datoteka ima jedinica koje se ne podudaraju sa jedinicama manifesta

  - **Data\_StreamUnitsMismatchFiles -** uzorak datoteka čije se jedinice ne podudaraju u protoku

  - **Data\_TimeElapsed -** koliko vremena je bilo potrebno za proveru oštećenja

  - **Data\_UpdateFileCount -** koliko datoteka ažuriramo

  - **Data\_UpdateFileFiles -** uzorak datoteka koje dodajemo

  - **Data\_Working -** novi manifest koji proveravamo

  - **Data\_WorkingVersion -** verzija novog manifesta

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

Podešavanje sistema Office i podaci o zalihama koji pružaju neophodne metapodatke za podešavanje i za zalihe, a koristi se za određivanje tačne osnovne instalacije.

Prikupljaju se sledeća polja:

  - **Data\_C2RClientVer** - Verzija OfficeClickToRun.exe koja se nalazi na računaru

  - **Data\_OfficeBitness** - Broj bita na kojima je instaliran Office, x86 ili x64

  - **Data\_OfficeVersion** - Verzija instaliranog Office sistema

  - **Data\_Sku** - SKU koji je instaliran, npr. Office 365 ProPlus.en-us

  - **Data\_SqmMachineID** - Jedinstveni ID računara koji koristi Windows SQM Data\_SusClientID- identifikator ažuriranja za Office na računaru

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

Podešavanje sistema Office i prikupljanje podataka o zalihama kada IT administrator pokreće „Klikni i pokreni“ setup.exe alatku za primenu programskog paketa Office da bi izmenio korisnikove instalirane Office proizvode. Koristi se za merenje uspeha / neuspeha instalacije sistema Office koju je u potpunosti započeo IT administrator, uključujući i preduslovne provere.

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

  - **Data\_ProductReleaseId-** Proizvod koji instaliramo, npr. Office 365 ProPlus

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office je primenjuje novo preuzete datoteke. Koristi se za merenje uspeha / neuspeha instalacionog programa za Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Koju verziju nadograđujemo na Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts -** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

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

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove -** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts -** Proizvodi koje uklanjamo 

  - **Data\_RemovingFixedProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office odlučuje koje datoteke će preuzeti. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office instalira licence i postavke registratora. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Na koju verziju nadograđujemo Office 15

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion  -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts -** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails -** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource  -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove -** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts -** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office instalira fontove. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  -** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID   -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office kreira postavke da bi ažuriranja radila ispravno. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID –-** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office kreira stavke registratora za Office aplikacije. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Na koju verziju nadograđujemo Office 15

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  -** koji scenario je pokrenut.  npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID  -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office završava instalaciju, kači prečice i kreira konačne postavke registratora. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Na koju verziju nadograđujemo Office 15

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-**  koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  -** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office premešta postavke iz starije verzije sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Na koju verziju nadograđujemo Office 15

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts -** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource – -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName  -** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID  -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-**  identifikator ažuriranja za Office na računaru

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office objavljuje virtuelni registrator za virtuelizaciju AppV sloja. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Na koju verziju nadograđujemo Office 15

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut, npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Podešavanje sistema Office i prikupljanje podataka o zalihama kada deinstalacioni program za Office uklanja sa uređaja delove sistema Office. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion-**  Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts -** Proizvodi koje  uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID  -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office preuzima nove datoteke. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -**  Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType  -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion  -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version  -** Office 16 verzija 

  - **Data\_AddingFixedProducts -** Proizvodi koje dodajemo 

  - **Data\_AddingProducts  -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource  -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-**  koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Podešavanje sistema Office i prikupljanje podataka o zalihama kada instalacioni program za Office deinstalira prethodnu verziju koja je instalirana iz prodavnice. Koristi se za merenje uspeha / neuspeha instalacije sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office ponovo objavi .msi datoteke i programske dodatke za Office. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion-**  Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office preuzima najnoviju verziju klijenta „Klikni i pokreni“ da bi pripremio računar za deinstalaciju i ponovnu instalaciju. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office pokuša da popravi neke poznate problematične stavke registratora. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da se kôd greške može zanemariti 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent za popravku sistema Office ukloni Office sa uređaja tokom popravke da bi ga pripremio za ponovno instaliranje. Koristi se za merenje uspeha / neuspeha popravke sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion  -** Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource  -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-**  koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ ažurira licence po potrebi. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Podešavanje sistema Office i prikupljanje zaliha kada klijent „Klikni i pokreni“ ažurira postavke registratora za nove binarne datoteke. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ zatvara pokrenute aplikacije po potrebi i instalira nove datoteke koje su preuzete. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion to-** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_CompletedWithoutActionInfo -** Zašto scenario nije dovršen, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_CorruptionChecksOnly –-** Ako samo proveravamo oštećenja, a ne ažuriramo

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_HardlinkingException -** Izuzetak na koji smo naišli dok smo pokušavali da kreiramo čvrste veze

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageOperationSuccessful -** Istinito ako smo uspešno dovršili zadatak sa Office paketom

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID  -**  Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-**  identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

  - **Data\_WorkstationLockState -** Istinito ako mislimo da je računar zaključan

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ preuzima svoju noviju verziju. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName-** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID  -** Jedinstveni ID računara koji koristi Windows SQM

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ provera da li je dostupno novo ažuriranje. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -** Na koju verziju nadograđujemo Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion -** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_ComAction -** Int koji predstavlja com radnju koju izvršavamo

  - **Data\_CompletedWithoutActionInfo -** Zašto scenario nije dovršen, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource  -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageUpdateAvailable -** Istinito ako je dostupna nova verzija sistema Office

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-**  koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-**  identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ preuzima novo ažuriranje. Koristi se za merenje uspeha / neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion -**  Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_AvailableVersion -** Koja verzija sistema Office je dostupna za ažuriranje

  - **Data\_CompletedWithoutActionInfo-** Zašto scenario nije dovršen, npr. aplikacije su bile otvorene

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_CorruptionChecksOnly -** Ako samo proveravamo oštećenja, a ne ažuriramo

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_FoundCorruptFiles -** Istinito ako smo pronašli oštećene datoteke

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_PackageOperationSuccessful -** Istinito ako smo uspešno dovršili zadatak sa Office paketom

  - **Data\_PipelineExitCode -** Izlazni kôd koji je vratio kanal datoteke

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -** Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID-** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ obavlja čišćenje nakon ažuriranja i vraća aplikacije koje su prethodno otvorene. Koristi se za merenje uspeha ili neuspeha ažuriranja sistema Office.

Prikupljaju se sledeća polja:

  - **Data\_15\_SourceType -** Mesto gde se nalazi izvor za Office 15, npr. CDN ili lokalno 

  - **Data\_15\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 15 

  - **Data\_15\_UpdateVersion-**  Koju verziju nadograđujemo na Office 15 

  - **Data\_15\_Version -** Office 15 verzija 

  - **Data\_16\_SourceType -** Mesto gde se nalazi izvor za Office 16, npr. CDN ili lokalno 

  - **Data\_16\_UpdatesEnabled-** Ako su omogućena ažuriranja za Office 16 

  - **Data\_16\_UpdateVersion -** Na koju verziju nadograđujemo Office 16 

  - **Data\_16\_Version -** Office 16 verzija 

  - **Data\_AddingFixedProducts-** Proizvodi koje dodajemo 

  - **Data\_AddingProducts -** Proizvodi čije je dodavanje zatraženo 

  - **Data\_CompletionState -** Ako smo završili zadatak

  - **Data\_ErrorCode -** Kôd greške koji nismo uspeli da sredimo 

  - **Data\_ErrorDetails-** Dodatni detalji o grešci 

  - **Data\_ErrorMessage -** Poruka o grešci koja prikazuje u čemu je bio problem 

  - **Data\_ErrorSource -** Gde je došlo do greške 

  - **Data\_ExceptionType -** Izuzetak koji nismo uspeli da sredimo 

  - **Data\_IsErrorCodeIgnorable -** Ako je kôd greške koji nismo uspeli da sredimo zanemarljiv 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Ako smatramo da je kôd greške zanemarljiv 

  - **Data\_NewestPackageVersion -** Najnovija verzija sistema Office na računaru 

  - **Data\_OldestPackageVersion -** Najstarija verzija sistema Office na računaru 

  - **Data\_ProductsToAdd -** Koje Office proizvode dodajemo 

  - **Data\_ProductsToRemove-** koje Office proizvode uklanjamo 

  - **Data\_RemovingFixedProducts-** Proizvodi koje uklanjamo 

  - **Data\_RemovingProducts -** Proizvodi čije je uklanjanje zatraženo 

  - **Data\_ScenarioInstanceID -** Jedinstveni GUID za pokretanje scenarija 

  - **Data\_ScenarioName -** koji scenario je pokrenut. npr. instaliranje 

  - **Data\_ScenarioSubType -** Koji tip scenarija smo pokrenuli, npr. deinstaliranje, ponovno instaliranje 

  - **Data\_SourceType -** Gde je naš izvor, npr. CDN 

  - **Data\_SqmMachineID -**  Jedinstveni ID računara koji koristi Windows SQM 

  - **Data\_SusClientID -** identifikator ažuriranja za Office na računaru 

  - **Data\_TaskState -** Status u kom se nalazi zadatak, kao što je pokrenut ili prekinut 

  - **Data\_TotalClientCabSize -** Veličina pakovanja našeg klijenta 

  - **Data\_TriggeringUI -** Šta je aktiviralo korisnički interfejs 

  - **Data\_UpdatesEnabled -** Ako su omogućena ažuriranja za Office 

  - **Data\_Version -** Office verzija 

### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ kreira protok za prenos da bi preuzeo Office datoteke. Koristi se za utvrđivanje ispravnosti raznih tehnologija za prenos (npr. HTTP, BITS, DO), što je od presudnog značaja za ispravno preuzimanje instalacije i ažuriranja za sistem Office.

Prikupljaju se sledeća polja:

  - **Data\_IsForeGroundStreaming** – Ako emitujemo u prednjem planu ili u pozadini

  - **Data\_IsInstallMode** – 1 ako instaliramo i preuzimamo datoteke, 0 ako to ne radimo

  - **Data\_SourceProtocol –** Ako preuzimamo sa mreže za podatke sadržaja, CDN, sa računara na koji instaliramo, lokalno, ili iz resursa sa lokalne mreže,

  - **Data\_Status** – Uspešno ili neuspešno 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Podešavanje sistema Office i prikupljanje podataka o zalihama kada klijent „Klikni i pokreni“ završava status ažuriranja

Prikupljaju se sledeća polja:

  - **Data\_build** - Trenutno instalirana verzija sistema Office

  - **Data\_channel** – Kanal na kom se nalazi korisnik

  - **Data\_errorCode** – Kôd sa celim brojevima koji određuje tip greške ako je do nje došlo

  - **Data\_errorMessage** – Niska koja opisuje grešku ako je do nje došlo

  - **Data\_status** – Kratki status onoga što se dogodili tokom ažuriranja, kao što je uspešnost ili završeno preuzimanje

  - **Data\_targetBuild -** - Verzija koju pokušavamo da nadogradimo na Office


## <a name="experimentation-and-configuration-service-ecs-events"></a>Događaji za eksperimentalne i konfiguracijske (ECS) usluge

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Prikuplja informacije o prolazima funkcije / promena čiji je upit poslao izvršeni kôd

Prikupljaju se sledeća polja:

  - **Count** - Broj upita o prolazima funkcije u paketnom događaju

  - **Features** - Informacije o prolazu upita.

  - **Sequence** - Redosled po kojem je izvršen upit o prolazu funkcije

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Prikuplja listu o konfiguracijama koje je primio klijent iz usluge ECS

Prikupljaju se sledeća polja:

  - **ECSConfigs** - Lista konfiguracije ECS odvojena zarezima

  - **LockType** - Tip FlightManager zaključavanja

  - **TasFlightingVersion** - Broj verzija

  - **TimeToLock** - Vreme koje protekne od liblet pokretanja do FlightManager zaključavanja

  - **UnmergedConfigs** - Lista konfiguracija koje nisu objedinjene


## <a name="licensing-events"></a>Događaji licenciranja

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Ovo se prikuplja kada korisnik postane licenciran i prihvati EULA ugovor za trenutnu licencu

Koristi se za određivanje da li se korisnik nalazi u dobrom ili lošem statusu, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **ACID** - GUID identifikator koji predstavlja Office proizvode za koje je korisnik licenciran

  - **DwEulaId** – Numerički identifikator za tip EULA ugovora koji je korisnik prihvatio

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Kada podesimo licencu na računaru, pokušavamo da je aktiviramo tako što pozivamo uslugu AVS. Ovo izveštava o ishodu poziva za aktivaciju

Od suštinskog je značaja za određivanje koliko korisnika nailazi na probleme prilikom aktivacije. Imamo detektor anomalija koji otkriva bilo koju regresiju. Ovo je veoma važno jer spoljno zavisimo od usluge AVS, a ovaj signal upućuje na to da li su naši spoljni partneri ispravni. Takođe se koristi i za dijagnostičke svrhe i ispravnost sistema ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** - GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **ReferralData** - Identifikator za OEM koji je instalirao Office na računar

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Ako iz nekog razloga nismo u mogućnosti da automatski aktiviramo licencu, prikazujemo korisniku čarobnjaka za aktivaciju. Ovo obaveštava da je čarobnjak za aktivaciju prikazan korisniku. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Ovo je signal koji nam govori da li je uspešan eksperiment koji smo pokrenuli da bismo nametnuli prijavljivanje korisnika kao deo licenciranja. Od suštinskog je značaja za otkrivanje uspešnosti ili neuspešnosti eksperimenta koji nameće prijavljivanje korisnika, što je neophodan korak u nizu modernog licenciranja.  Neuspešno prijavljivanje će onemogućiti da korisnici koriste aplikaciju.

Prikupljaju se sledeća polja:

  - **Qualified** - Određuje da li je korisnik kvalifikovan za nametnuto prijavljivanje

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Ovo se prikuplja kada korisniku prikažemo dijalog isteka koji pokazuje da je njihova licenca istekla. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i da li ima svu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **LicNotificationState** - Brojač koji nam govori koja vrsta obaveštenja se prikazuje korisniku

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Ovo se prikuplja pri svakoj sesiji koja izveštava o statusu licence na računaru i greškama koje se prikazuju korisniku zbog kojih nije u mogućnosti da koristi aplikaciju. Ovaj događaj ukazuje na to da li je korisnikov računar ispravan ili nije. Za ovaj događaj imamo podešen detektor anomalija da bismo označili da li regresija uzrokuje neispravno ponašanje korisnika. Takođe je od suštinske važnosti pri dijagnostikovanju korisničkih problema i za nadgledanje ispravnosti sistema

Prikupljaju se sledeća polja:

  - **Acid** - GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **IsSessionLicensing** - Da li je trenutno pokrenuta u režimu aktivacije deljenog računara ili nije. 

  - **LicenseCategory** - Kategorija Office licence koju korisnik koristi 

  - **Licences** - Lista sa imenima svih Office licenci koje se nalaze na računaru 

  - **LicenseStatuses** - Status svih Office licenci koje se nalaze na računaru 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Ovo prikupljamo kad korisnik podešava uređaj, a mi pozivamo uslugu licenciranja da bismo otkrili da li prijavljeni korisnik ima prava na sistem Office ili nema. Ovo izveštava o ishodu tog poziva. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Prilikom svake sesije proveravamo da li je prošlo 72 sata od poslednje obnove licence i pokušavamo da produžimo rok isteka trenutne licence. Ovaj događaj izveštava o uspešnosti ili neuspešnosti poziva koji smo uputili da bismo proverili da li možemo da produžimo rok isteka licence i da korisnikovu instalaciju sistema Office održimo funkcionalnom. Od suštinske je važnosti pri dijagnostikovanju korisnikovih problema vezanih za pretplatu i uslugu, kao i za otkrivanje regresija kod korisnika koji su već aktivirali pretplatu.

Prikupljaju se sledeća polja:

  - **Mode** - Numeričko predstavljanje paketa licenci za sistem Office koji se koristi na računaru

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Ako uređaj uđe u režim smanjene funkcionalnosti, šaljemo ovaj signal da bismo naznačili da se računar ne nalazi u ispravnom stanju. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **ACID** - GUID identifikator koji predstavlja Office proizvode za koje je korisnik licenciran

  - **DaysRemaining** - Broj dana koji je preostao do isteka trenutne Office licence

  - **Mode** - Numeričko predstavljanje paketa licenci za sistem Office koji se koristi na računaru

  - **ProductName** - Ime proizvoda koji korisnik trenutno koristi

  - **Reason** - Kôd greške koji ukazuje na razlog trenutnog statusa licence

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Ovo se prikuplja kada pokušavamo da instaliramo ključ na uređaj da bismo licencirali računar. Izveštava da li je instalacija uspešna, a ako nije, šalje kôd greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **Prid** - Ime grupe proizvoda za koju se instalira ključ

  - **SkuId** - GUID identifikator koji predstavlja Office proizvod za koji se instalira ključ 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

U slučaju da primetimo probleme sa tokom posla aktivacije, pokrećemo čarobnjaka za licenciranje i šaljemo signal koji to naznačava. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i da li ima svu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** - GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **LicenseStatus** - Status Office licence koju korisnik koristi

  - **MachineKey** - Alfanumerički identifikator ključa licence koji je izdat korisniku

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Ako uređaj naiđe na probleme sa licenciranjem i dođe do toga da korisniku prikažemo sabirnicu, šaljemo ovaj signal koji izveštava i o tipu sabirnice koja je prikazana korisniku. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **SuppressNotification** - Označava da li smo potisnuli sabirnicu licenciranja

  - **Title** - Naziv sabirnice licenciranja koja je prikazana korisniku

  - **Type** - Tip sabirnice licenciranja koja je prikazana korisniku

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Ako dođe do zatvoranja/pada sistema Office zbog problema sa licenciranjem, šaljemo ovaj signal da bismo to naznačili. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **ExitCode** - Unutrašnji kôd koji je izazvao zatvaranje aplikacije

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

U toku pokušaja da se uređaj licencira, aplikacija pokušava da učita korisnikov identitet da bi videla da li korisnik ima pravo na sistem Office. Ovaj događaj izveštava o uspešnosti ili neuspešnosti istog, kao i o kôdu greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **FederationProvider** - Niska koja identifikuje dobavljača spoljnog pristupa za trenutno prijavljenog korisnika

  - **IdentityProvider** - Niska koja identifikuje dobavljača identiteta za trenutno prijavljenog korisnika

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Ovo se prikuplja ako smo korisniku prikazali EULA ugovor, a on je izabrao da ga ne prihvati što je dovelo do pada/zatvaranja aplikacije. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** - GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **OptInShown** - Ukazuje na to da li je dijalog za davanje saglasnosti koji se prikazuje pri prvom pokretanju aplikacije već prikazan. 

  - **Office.Licensing.NextUserLicensingEligible -** Ovaj signal nam govori da li je korisnik kvalifikovan za prelazak na naš novi paket licenci. Ovo je od suštinske važnosti za određivanje količine uticaja na postojeće korisnike dok objavljujemo nove pakete licenci i proveravanje da li korisnici zadržavaju funkcionalnost.

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Kada je uređaj na modernom paketu licence, trudimo se da datoteku licence preuzmemo direktno iz usluge. Ovaj događaj izveštava o uspešnosti ili neuspešnosti, kao i o kôdu greške kod poziva usluge. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu kod modernog paketa licence, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **MetadataValidationResult** - Rezultat provere valjanosti metapodataka licence da bi se proverilo da nisu neovlašćeno promenjeni

  - **SignatureValidationResult** - Rezultat provere valjanosti potpisa da bi se proverilo da nije neovlašćeno promenjen

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Ovo se prikuplja pri svakoj sesiji uređaja koji je pokrenut na modernom paketu licence. Izveštava o statusu licence na računaru i greškama koje se prikazuju korisniku zbog kojih nije u mogućnosti da koristi aplikaciju. Ovaj događaj ukazuje na to da li je ispravan korisnikov računar na modernom paketu licence. Za ovaj događaj imamo podešen detektor anomalija da bismo označili da li regresija uzrokuje neispravno ponašanje korisnika. Takođe je od suštinske važnosti pri dijagnostikovanju korisničkih problema i za nadgledanje ispravnosti sistema.

Prikupljaju se sledeća polja:

  - **Acid** - GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **AllAcids** - Lista svih GUID proizvoda za koje je korisnik trenutno licenciran 

  - **Category** - Kategorija Office licence koju korisnik koristi 

  - **DaysRemaining** - Broj dana koji je preostao do isteka trenutne Office licence 

  - **LicenseId** - Alfanumerički identifikator licence koji je izdat korisniku 

  - **LicenseType** - Tip Office licence koju korisnik koristi 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Ovo su metapodaci licenciranja koji se prikupljaju pri svakom pokretanju i koji izveštavaju o proizvodu, statusu, tipu i drugim svojstvima licence koja su važna za određivanje skupa funkcija dostupnih korisniku. Od suštinske je važnosti za određivanje skupa funkcija koje su dostupne korisniku i da li nedostaje neka funkcionalnost. Takođe se koristi i za izračunavanje broja dnevno/mesečno aktivnih korisnika, kao i za različite izveštaje koje koriste razni timovi u svim Office oblastima (marketing/DIG/licenciranje) jer nam to govori koji tip proizvoda koristi korisnik, da li je u pitanju pretplata na proizvod i da li nedostaje neka bitna funkcionalnost.

Prikupljaju se sledeća polja:

  - **FullValidationMode** - Režim koji ukazuje na to da se nalazimo u potpunoj validaciji verifikacije licence 

  - **IsRFM** - Ukazuje na to da li se korisnik nalazi u režimu smanjene funkcionalnosti ili ne 

  - **IsSCA** - Ukazuje na to da li se nalazimo u režimu aktivacije deljenog računara 

  - **IsSubscription** - Ukazuje na to da li korisnik koristi licencu za pretplatu ili ne 

  - **IsvNext** - Ukazuje na to da li koristimo novi moderni paket licenciranja ili ne 

  - **LicenseCategory** - Kategorija Office licence koju koristi korisnik 

  - **LicenseStatus** - Status Office licence koju korisnik koristi 

  - **LicenseType** - Tip Office licence koju korisnik koristi 

  - **LicensingACID** - GUID identifikator koji predstavlja Office proizvode za koje je korisnik licenciran 

  - **OlsLicenseId** - Alfanumerički identifikator licence koji je izdat korisniku 

  - **SkuIdIsNull** - Ukazuje na to da li smo naišli na grešku i ne znamo koji proizvod korisnika pokreće 

  - **SlapiIsNull** - Ukazuje na to da li smo naišli na problem u popunjavanju jednog od objekata licenciranja  

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Ovaj događaj se pokreće ako iz nekog razloga nismo u mogućnosti da aktiviramo korisnika i moramo da im prikažemo dijalog koji mu traži da se priključi na mrežu i pokuša da prati korake za popravak. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Sprovodimo eksperiment koji korisniku pruža mogućnost da isproba i podesi automatsko plaćanje za Office direktno iz aplikacije bez potrebe da napušta njen kontekstualni meni. Ovo izveštava o uspešnosti ili neuspešnosti datog eksperimenta, kao i o kôdu greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **StorePurchaseStatus** - Predstavlja kôd greške/uspeha poziva za kupovinu koji je upućen in Windows prodavnice

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Ako se korisnik nalazi u režimu aktivacije deljenog računara, pokušavamo da pronađemo token sesije na računaru koji dozvoljava korisniku da koristi aplikaciju. Ovaj događaj izveštava o uspešnosti ili neuspešnosti datog scenarija, kao i o kôdu greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **LoadLicenseResult** - Predstavlja kôd greške/uspeha za to da li smo bili u mogućnosti da učitamo licence za trenutnog korisnika

  - **OpportunisticTokenRenewalAttempted** - Ukazuje na to da li smo pokušali da oportunistički obnovimo token korisnikove sesije

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

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Ako iz nekog razloga nismo u mogućnosti da licenciramo korisnika, instaliramo „grejs“ ključ i šaljemo signal koji to označava. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **OpportunisticTokenRenewalAttempted** - Ukazuje na to da smo pokušali oportunističku obnovu za korisnika koji se nalazi u režimu aktivacije deljenog računara

  - **ReArmResult** - Ukazuje na rezultat vraća instaliranog ključa u početno stanje, što može da produži rok trajanje trenutne licence

## <a name="services-configuration-events"></a>Događaji konfiguracije usluga

Konfiguracija usluga ne prikuplja neophodne dijagnostičke podatke o usluzi.

## <a name="telemetry-events"></a>Događaji telemetrije

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Informacije o korisničkom identitetu koje su potrebne za ispunjavanje podataka koji podležu zahtevima

Prikupljaju se sledeća polja:

  - **IdentityChanged** - Uvek istinito. Identitet je promenjen.

  - **TimerDetectedChange** - Da li je promena otkrivena u redovnom vremenskom pingu.

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

  - **ProcessFileName -** Ime izvršne aplikacije koja je pokrenuta

  - **ProcessorArchitecture -** Na kojoj arhitekturi procesora je pokrenut Office

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

  - **PreviousBuild** - Verzija na koju je Office izdanje nadograđeno ili sa koje je vraćeno.

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

  - **PowerPlatformRole -** Identifikator računarske uloge uređaja kojoj OEM daje prednost i na kome se pokreće Office.

  - **ProcessFileName -** Ime izvršne aplikacije koja je pokrenuta

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

  - **ProcessFileName -** Ime izvršne aplikacije koja je pokrenuta

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

<!-- end list -->

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

  - **CollectibleClassifications -** Klasifikacije podataka koje je moguće prikupiti u skladu sa postavkama privatnosti klijenta.

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

  - **PreviousBuild** - Verzija na koju je Office izdanje nadograđeno ili sa koje je vraćeno.

  - **State** - Stanje u koje je promenjena sesija.

  - **Vreme** - Trenutak kada se promenilo stanje sesije.

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Koristi se sa podacima o padu da bi se razdvojili rani i kasni padovi (npr. da se odredi da li je korisnik koristio aplikaciju neko vreme pre pada) 

Prikupljaju se sledeća polja:

  - **SessionStart** - Vreme kada telemetrija počinje da obrađuje podatke.

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Koristi se za snimanje metrike pada.

Prikupljaju se sledeća polja:

  - **AffectedProcessAppBuild -** Identifikator izdanja verzije ugroženog procesa.

  - **AffectedProcessAppBuildRevision -** Identifikator izdanja revizije ugroženog procesa.

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

  - **CrashedEcsETag -** Identifikator eksperimenta palog procesa.

  - **CrashedImpressionId -** Identifikator prikaza palog procesa.

  - **CrashedProcessSessionID -** Jedinstveni identifikator palog procesa.

  - **CrashedProcessSessionInitTime -** Vreme kada je počeo ugroženi proces.

  - **CrashType -** Identifikator grupe za tip pada

  - **DetectionTime -** Vreme kada je otkriven neočekivani izlaz.

  - **ErrorString -** Opis greške.

  - **ExceptionAddress -** Adresa u aplikaciji u kojoj je došlo je do greške.

  - **ExceptionCode -** Identifikator grupe za izuzetak.

  - **FaultAppName -** Ime neispravne aplikacije.

  - **InstallMethod -** Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **InstallType -** Identifikator načina na koji je instaliran sistem Office.

  - **InstallTypeName -** Identifikator načina na koji je instaliran sistem Office.

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **IsMsftInternal -** Da li je korisnik operativnog sistema Windows koji pokreće Office zaposlen u korporaciji Microsoft.

  - **ModuleBaseAddress -** Osnovna adresa neispravnog modula.

  - **ModuleBuildVersion -** Broj izdanja verzije neispravnog modula.

  - **ModuleMajorVersion -** Broj glavne verzije neispravnog modula.

  - **ModuleMinorVersion -** Broj međuverzije neispravnog modula.

  - **ModuleName -** Ime neispravnog modula.

  - **ModuleOffset -** Pomak u bajtovima od osnovne adrese gde je došlo je do greške.

  - **ModuleRevisionVersion -** Broj izdanja verzije revizije neispravnog modula.

  - **ModuleSize -** Veličina neispravnog modula u bajtovima.

  - **OSEnvironment -** Identifikator okruženja u kome je pokrenut Office.

  - **PreviousBuild -** Izdanje prethodno instalirane verzije

  - **UAETypeName -** Identifikator grupisanja načina na koji je aplikacija nespretno zatvorena.

  - **VerifyElseCrashTag -** Jedinstveni identifikator mesta na kom je aplikacija pala.

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

Koristi se za snimanje metrike pada.

Prikupljaju se sledeća polja:

  - **CrashedAppBuild -** Identifikator izdanja verzije ugroženog procesa.

  - **CrashedAppMajor -** Identifikator glavne verzije ugroženog procesa.

  - **CrashedAppMinor -** Identifikator međuverzije ugroženog procesa.

  - **CrashedAppRevision -** Identifikator izdanja verzije ugroženog procesa.

  - **CrashedConfigIds -** Konfiguracija dodeljena palom procesu.

  - **CrashedEcsETag -** Identifikator eksperimenta palog procesa.

  - **CrashedImpressionId -** Identifikator prikaza palog procesa.

  - **CrashedModuleName -** Ime neispravnog modula.

  - **CrashedSessionId -** Jedinstveni identifikator palog procesa.

  - **CrashedSessionInitTime -** Vreme kada je počeo ugroženi proces.

  - **CrashType -** Identifikator grupe za tip pada

  - **DetectionTime -** Vreme kada je otkriven neočekivani izlaz.

  - **ExceptionAddress -** Adresa u aplikaciji u kojoj je došlo je do greške.

  - **ExceptionCode -** Identifikator grupe za izuzetak.

  - **HexExceptionAddress -** Adresa u heksadecimalnom zapisu u aplikaciji u kojoj je došlo do greške.

  - **HexExceptionCode -** Identifikator grupe za izuzetak u heksadecimalnom zapisu.

  - **HexModuleBaseAddress -** Osnovna adresa neispravnog modula u heksadecimalnom zapisu.

  - **HexModuleOffset -** Pomak u bajtovima (heksadecimalnom zapisu) od osnovne adrese gde je došlo je do greške.

  - **HexModuleSize -** Veličina neispravnog modula u bajtovima u heksadecimalnom zapisu.

  - **HexVerifyElseCrashTag -** Jedinstveni identifikator mesta na kom je aplikacija pala u heksadecimalnom zapisu.

  - **InstallMethod -** Da li je trenutna verzija sistema Office instalirana nadogradnjom, vraćanjem na prethodnu verziju ili novom instalacijom.

  - **IsLabMachine -** Da li je Office pokrenut u Microsoft laboratoriji.

  - **ModuleBaseAddress -** Osnovna adresa neispravnog modula.

  - **ModuleOffset -** Pomak u bajtovima od osnovne adrese gde je došlo je do greške.

  - **ModuleSize -** Veličina neispravnog modula u bajtovima.

  - **PreviousBuild -** Izdanje prethodno instalirane verzije

  - **UAEOSEnvironment -** Identifikator okruženja operativnog sistema.

  - **VerifyElseCrashTag -** Jedinstveni identifikator mesta na kom je aplikacija pala.

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

  - **DialogCancelled** - Da li je otkazan dijalog Prikazivača dijagnostičkih podataka

  - **NewState** - Novo stanje Prikazivača dijagnostičkih podataka

  - **WasDialogUsed** - Da li je korišćen dijalog Prikazivača dijagnostičkih podataka

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Podaci koji su potrebni da bi se izmerila ispravnost usluge konfiguracije telemetrije.

Prikupljaju se sledeća polja:

  - **ParsedConfigCount** - Broj obrađenih dinamičkih konfiguracija

  - **ParsedConfigs** - Broj obrađenih dinamičkih konfiguracija

  - **RejectedConfigCount** - Broj odbijenih konfiguracija

  - **RejectedConfigs** - Broj odbijenih konfiguracija

  - **RejectedConfigsList** - Lista odbijenih konfiguracija razdvojena zarezima

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Podaci koji su potrebni da bi se izmerila ispravnost usluge konfiguracije telemetrije.

Prikupljaju se sledeća polja:

  - **ErrorMessage** - Poruka o grešci obrade

  - **NodeName** - Čvor koji nije uspeo da se obradi

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

<!-- end list -->

  - **QueueFlushCount** - Broj pražnjenja reda

  - **QueueFlushDueToSizeLimit** - Veličina posle koje telemetrija prazni red

  - **QueueFlushesDueToSize** - Broj pražnjenja reda koje je uzrokovano veličinom bafera

  - **QueueHardLimit** - Ograničenje isključivanja telemetrije

  - **QueueLimitHitTime** - Kada je dostignuto ograničenje isključivanja

  - **ResultTime** - Vreme događaja

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

Ograničavanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Prikupljaju se sledeća polja:

  - **DiskWriteLimit** - Ograničenje veličine diska za telemetrijske podatke

  - **DiskWriteTotal** - Ukupno pisanje diska za telemetrijske podatke

  - **SessionDiskWriteTotal** - Ukupno pisanje diska za telemetrijske podatke tokom sesije

  - **ThrottlingTimestamp** - Vreme kada je sesija ograničena

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

Ograničavanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

Ovaj događaj ne prikuplja polja.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

Ograničavanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

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

Ograničavanje DQ metrike. Potrebno je za pouzdanost svih drugih podataka.

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
