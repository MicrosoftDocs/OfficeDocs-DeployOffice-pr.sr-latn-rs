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
ms.openlocfilehash: a482854210e5f609a41e6a810c3c3338a19586e7
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510479"
---
# <a name="essential-services-for-office"></a>Osnovne usluge za Office

> [!IMPORTANT]
> Informacije u ovom članku se odnose na verziju 1904 ili noviju, sledećih Office klijentskih softvera instaliranih na računaru sa operativnim sistemom Windows:
> - Office 365 ProPlus i Office 365 Business
> - Office 365 Personal, Office 365 Home ili druge verzije sistema Office koje su deo pretplate na Office 365.
> - Project i Visio koji se dobijaju uz neke planove pretplata, kao što je plan za Project Online Professional ili Visio Online Plan 2.
>
> Informacije se odnose i na verziju 16.28 ili noviju verziju sledećih Office aplikacija za Mac: Excel, Outlook, OneNote, PowerPoint i Word.

Office se sastoji od aplikacija klijentskog softvera i povezanih iskustava dizajniranih tako da vam omogućavaju da efikasnije kreirate, komunicirate i sarađujete. Iako možete da kontrolišete mnoga povezana iskustva koja su dostupna vama ili, ako ste administrator organizacije, vašim korisnicima, postoji i skup usluga koje su od suštinske važnosti za funkcionisanje sistema Office, te stoga ne mogu biti onemogućene. Na primer, usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office. Neophodni podaci o ovim uslugama prikupljaju se i šalju korporaciji Microsoft, bez obzira na bilo koje druge postavke smernica za privatnost koje ste konfigurisali. Možete da vidite ove podatke tako što ćete koristiti Prikazivač dijagnostičkih podataka.

Dodatne informacije potražite u sledećim člancima:

- [Neophodni podaci o usluzi za Office](required-service-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Povezana iskustva u sistemu Office](connected-experiences.md)

Ako ste administrator organizacije, možda će vas zanimati i sledeće:

- [Pregled kontrola privatnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti u programu Office 365 ProPlus](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)

## <a name="list-of-essential-services-for-office"></a>Lista osnovnih usluga za Office 

Sledeća tabela sadrži listu osnovnih usluga za Office i njihov opis.

| **Usluga**  | **Opis**  |
| ------ | ---- |
| [Potvrda identiteta](#authentication-events) | Potvrda identiteta je usluga koja se nalazi na bilo kom uređaju i koja potvrđuje vaš korisnički identitet u sistemu Office. Ona je potrebna za prijavljivanje u Office, aktiviranje Office licence, pristup vašim datotekama koje su uskladištene u oblaku i za pružanje doslednog iskustva u svim Office sesijama i uređajima.    |
| [Klikni i pokreni](#click-to-run-events) | „Klikni i pokreni“ je tehnologija instaliranja koja se koristi za instalaciju i ažuriranje sistema Office na operativnom sistemu Windows. Ona proverava da li postoje nove verzije sistema Office, a kada nova verzija postane dostupna, preuzima je i instalira. „Klikni i pokreni“ će otkrivati potrebu za preuzimanjem i instaliranjem Office ispravki, kao i bezbednosnih zakrpi.     |
| [Usluga poboljšane konfiguracije (UPK)](#enhanced-configuration-service-ecs-events) | UPK omogućava korporaciji Microsoft da ponovo konfiguriše instalacije sistema Office, a da vi ne morate ponovo da ga instalirate. Koristi se za kontrolu postepenog objavljivanja funkcija i ažuriranja, dok se uticaj objavljivanja nadgleda preko dijagnostičkih podataka koji se prikupljaju. Takođe se koristi i za smanjivanje bezbednosnih problema i problema performansi uz pomoć funkcija ili ažuriranja. Osim toga, UPK podržava promene u konfiguraciji koje se odnose na dijagnostičke podatke kako bi se obezbedilo prikupljanje odgovarajućih događaja. |
| [Licenciranje](#licensing-events)     | Licenciranje je usluga zasnovana na tehnologiji oblaka koja održava vašu Office aktivaciju tokom novih instalacija i čuva licencu na vašim uređajima nakon aktivacije. Ona registruje svaki od vaših uređaja i aktivira Office, provera status vaše pretplate na sistem Office i upravlja vašom šifrom proizvoda.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) predstavlja tehnologiju koja se koristi za ažuriranje Microsoft aplikacija za MacOS, na primer za Office. MAU otkriva potrebu za ispravkama za aplikacije, kao i bezbednosnim ispravkama, preuzima ih i instalira.|
|[Sinhronizovanje programa OneNote](#onenote-sync-events)|OneNote za Mac podržava samo beležnice uskladištene na internetu u usluzi OneDrive ili SharePoint Online. OneNote za Mac neprestano sinhronizuje sve beleške korisnika sa uslugom OneDrive ili SharePoint Online. Na taj način omogućava korisnicima da otvaraju, pregledaju i uređuju beležnice na svim uređajima, tako da su one uvek ažurirane.
 [Konfiguracija usluga](#services-configuration-events)  | Konfiguracija usluga pruža mogućnost ažuriranja postavki konfiguracije za Office da bi se omogućile ili onemogućile funkcije klijenta. Ova funkcija se poziva svaki put kada se pokrene Office aplikacija i pruža detalje o ostalim konfiguracijama i uslugama sistema Office. Konfiguracija usluga takođe kontroliše koje usluge su određene kao osnovne.  |
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

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Izveštaji o statusu novog „Klikni i pokreni“ kanala ažuriranja („Repoman“) i ako uspešno preuzima i primenjuje Office ispravke.

Prikupljaju se sledeća polja:

  - **ApplySucceeded -** Tačno ako je kanal uspešno primenio ažuriranje za Office, netačno ako nije.
  
  - **DownloadSucceeded -** Tačno ako je kanal uspešno preuzeo ažuriranje za Office, netačno ako nije.

  - **ErrorCode -** Kod poslednje greške koja se dogodila u „Klikni i pokreni“ kanalu Repoman.

  - **ErrorDetails -**  Dodatni detalji o poslednjoj grešci koja se dogodila u „Klikni i pokreni“ kanalu Repoman.
 
  - **ErrorMessage -** Poruka o poslednjoj grešci koja se dogodila u „Klikni i pokreni“ kanalu Repoman.

  - **OpenStreamSessionSucceeded -** Tačno ako kanal uspešno kreira sesiju za striming Office ažuriranja, netačno ako je ne kreira.

  - **RepomanErrorMessage -** Poruka o grešci primljena od repoman.dll.
 

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

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Izveštava o radnjama preuzimanja datoteka kako bi se odredilo da li je operacija bila uspešna, tipu preuzimanja i dijagnostičkim informacijama.


- **BytesFromGroupPeers** – Bajtovi ravnopravnih uređaja u grupi, samo za preuzimanja pomoću optimizacije isporučivanja

- **BytesFromHttp** – Bajtovi http protokola, samo za preuzimanja pomoću optimizacije isporučivanja

- **ByteFromInternetPeers** – Bajtovi ravnopravnih uređaja na internetu, samo za preuzimanja pomoću optimizacije isporučivanja 

- **BytesFromLanPeers** – Bajtovi ravnopravnih uređaja na Lan mreži, samo za preuzimanja pomoću optimizacije isporučivanja 

- **CancelledJobs** – Broj otkazanih zahteva u sesiji

- **Connected** – Pokazuje da li postoji veza sa izvorom

- **ErrorCode** – Kôd poslednje greške

- **ErrorDetails** – Detalji poslednje greške

- **ErrorMessage** – Poruka poslednje greške 

- **ErrorSource** – Izvor poslednje greške, na primer Connection, LoadFile ili LoadRange

- **FailedJob** – Broj zahteva u sesiji koji nisu uspeli

- **FileSize** – Veličina resursa

- **SourcePathNoFilePath** – Izvorna putanja resursa. Izveštava se samo o http izvoru, a filtrira se putanja do lokalne datoteke ili UNC putanja

- **SucceededJobs** – Broj uspešnih zahteva u sesiji

- **TotalJobs** – Ukupan broj zahteva u sesiji

- **TotalRequestedBytes** – Ukupan broj traženih bajtova u sesiji

- **TotalTransferTime** – Ukupno vreme prenosa u sesiji

- **TransferredBytes** – Ukupan broj prenetih bajtova u sesiji

- **TransportType** – Tip prenosa, na primer (optimizacija isporučivanja u memoriji, HTTP, usluga inteligentnog prenosa u pozadini)



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


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Izveštava o rezultatu pokušaja potpunog instaliranja

 - **ErrorCode** – Vrednost celog broja povezana sa nekontrolisanim izuzetkom

 - **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

 - **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

 - **ErrorType** – Niska koja opisuje kategoriju nekontrolisanog izuzetka

 - **ExitCode** – Vrednost celog broja povezana sa rezultatom pokretanja programa koji se pokreće prilikom pokretanja računara koja označava uspeh naspram određenih tipova otkazivanja

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Izveštava o radnji koja donosi programske odluke u vezi sa unosom prikupljenim pomoću događaja CollectParameters

- **BitField** – Vrednost celog broja argumenta BitField koji pokazuje da li je zatražen eksplicitan kanal instalacije/ažuriranja (mesečni, spori za insajdere, brzi za insajdere, polugodišnji, polugodišnji za izabrane korisnike)

- **ChannelID** – Vrednost celog broja koja predstavlja numeričku vrednost izabranog kanala instalacije/ažuriranja (mesečni, spori za insajdere, brzi za insajdere, polugodišnji, polugodišnji za izabrane korisnike)

- **CMDMode** – Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena u izvršnu datoteku.

- **C2RClientUICulture** – Jezik klijenta za verziju „Klikni i pokreni“ koji treba instalirati

- **ErrorCode** – Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType** – Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExcludedApps** – Niska koja navodi imena pojedinačnih Office aplikacija za koje je zatraženo da se isključe iz instaliranih Office programskih paketa

- **InstalledCabVersion** – Već je instalirana verzija 16.0.xxxxx.yyyyy klijenta za Office „Klikni i pokreni“

- **InstalledProductVersion** – Već je instalirana verzija 16.0.xxxxx.yyyyy Office „Klikni i pokreni“ proizvoda

- **IsC2RServiceRunning** – Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za verziju „Klikni i pokreni“ normalno radi na uređaju

- **IsElevatedFlagSet** – Bulova zastavica koja pokazuje da li je program koji se pokreće prilikom pokretanja računara već pokušao da dobije podizanje na nivo administratora

- **IsFireFlyInstalled** – Bulova zastavica koja pokazuje da li je trenutno instaliran klijent za Office 2013 RTM C2R

- **IsFireflyServiceRunning** – Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za 2013 RTM C2R normalno radi na uređaju

- **IsOfficeInstalled** – Bulova zastavica koja pokazuje da li je već instaliran moderni klijent za Office

- **OfficeCultures** – Serijalizovana lista Office jezika koje treba instalirati

- **OfficeSourceType** – Prepoznatljiva niska povezana sa numeričkom vrednošću instalacionog izvora (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin** – Vrednost niske koja saopštava koji od podržanih izvora (Portoriko [PR], Singapur [SG], Dablin [DB]) treba koristiti za početni protok instalacije

- **PlatformFromLink** – Niska koja pokazuje podrazumevani broj bitova x86 | x64 | sistema Office zatražen od usluge podešavanja za verziju „Klikni i pokreni“

- **PlatformOfExistingInstallation** – Niska koja pokazuje da li je x86-bitna ili x64-bitna verzija sistema Office već instalirana na uređaju

- **PlatformToInstall** – Niska koja pokazuje konačnu odluku u vezi sa time da li treba instalirati x86-bitnu ili x64-bitnu verziju sistema Office. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **PRID** – Vrednost niske koja predstavlja traženi ID izdanja proizvoda u slučaju korisničke instalacije (na primer, „O365ProPlusRetail“)

- **ProductsToAdd** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome kombinacije proizvoda/jezika treba da instalira

- **ProductsToRemove** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome koje kombinacije proizvoda/jezika treba da deinstalira

- **SharedComputerLicensing** – Bulova vrednost koja pokazuje da li je IT administrator zatražio podešavanje kako bi se omogućila funkcija „SharedComputerLicensing“

- **ShouldActivate** – Bulova vrednost koja pokazuje da li je IT administrator zatražio pokušaj automatskog aktiviranja licenciranja u datoteci configuration.xml

- **VersionToInstall** – Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Izveštava o radnji koja čita označeni unos iz ugrađenog potpisa izvršne datoteke.  Ovo je nedokazani koncept koji prethodna iteracija izvršne datoteke setup.exe nije primenila i to je ono na šta se oslanjamo prilikom prenošenja izbora korisnika u vezi sa proizvodom/jezikom/brojem bitova sa veb stranice u proces unutar izvršne datoteke setup.exe.
 
- **ErrorCode** – Ceo broj povezan sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType** – Niska koja opisuje kategoriju nekontrolisanog izuzetka

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Izveštava o parametrima koji se koriste za instaliranje sistema Office

- **BitField** – Vrednost celog broja argumenta BitField koji pokazuje da li je zatražen eksplicitan kanal instalacije/ažuriranja (mesečni, spori za insajdere, brzi za insajdere, polugodišnji, polugodišnji za izabrane korisnike)

- **ChannelID** – Vrednost celog broja koja predstavlja numeričku vrednost izabranog kanala instalacije/ažuriranja (mesečni, spori za insajdere, brzi za insajdere, polugodišnji, polugodišnji za izabrane korisnike)

- **CMDMode** – Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena u izvršnu datoteku. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **C2RClientUICulture** – Jezik klijenta za verziju „Klikni i pokreni“ koji treba instalirati

- **ErrorCode** – Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType** – Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExcludedApps** – Niska koja navodi imena pojedinačnih Office aplikacija za koje je zatraženo da se isključe iz instaliranih Office programskih paketa

- **InstalledCabVersion** – Već je instalirana verzija 16.0.xxxxx.yyyyy klijenta za Office „Klikni i pokreni“

- **InstalledProductVersion** – Već je instalirana verzija 16.0.xxxxx.yyyyy Office „Klikni i pokreni“ proizvoda

- **IsC2RServiceRunning** – Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za verziju „Klikni i pokreni“ normalno radi na uređaju

- **IsElevatedFlagSet** – Bulova zastavica koja pokazuje da li je program koji se pokreće prilikom pokretanja računara već pokušao da dobije podizanje na nivo administratora

- **IsFireFlyInstalled** – Bulova zastavica koja pokazuje da li je trenutno instaliran klijent za Office 2013 RTM C2R

- **IsFireflyServiceRunning** – Bulova zastavica koja pokazuje da li usluga lokalne mašine modernog klijenta za 2013 RTM C2R normalno radi na uređaju

- **IsOfficeInstalled** – Bulova zastavica koja pokazuje da li je već instaliran moderni klijent za Office

- **OfficeCultures** – Serijalizovana lista Office jezika koje treba instalirati

- **OfficeSourceType** – Prepoznatljiva niska povezana sa numeričkom vrednošću instalacionog izvora (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin** – Vrednost niske koja saopštava koji od podržanih izvora (Portoriko [PR], Singapur [SG], Dablin [DB]) treba koristiti za početni protok instalacije

- **PlatformFromLink** – Niska koja pokazuje podrazumevani broj bitova x86 | x64 | sistema Office zatražen od usluge podešavanja za verziju „Klikni i pokreni“

- **PlatformOfExistingInstallation** – Niska koja pokazuje da li je x86-bitna ili x64-bitna verzija sistema Office već instalirana na uređaju

- **PlatformToInstall** – Niska koja pokazuje konačnu odluku u vezi sa time da li će se instalirati x86-bitna ili x64-bitna verzija sistema Office

- **ProductsToRemove** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome koje kombinacije proizvoda/jezika treba da deinstalira

- **PRID** – Vrednost niske koja predstavlja traženi ID izdanja proizvoda u slučaju korisničke instalacije (na primer, „O365ProPlusRetail“)

- **ProductsToAdd** – Serijalizovana niska koja daje uputstva klijentu za verziju „Klikni i pokreni“ o tome kombinacije proizvoda/jezika treba da instalira

- **SharedComputerLicensing** – Bulova vrednost koja pokazuje da li je IT administrator zatražio podešavanje kako bi se omogućila funkcija „SharedComputerLicensing“

- **ShouldActivate** – Bulova vrednost koja pokazuje da li je IT administrator zatražio pokušaj automatskog aktiviranja licenciranja u datoteci configuration.xml

- **VersionToInstall** – Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira

### <a name="officeclicktorununiversalbootstrapperexecute"></a>Office.ClickToRun.UniversalBootstrapper.Execute

Izveštava o preduzetim radnjama koje utiču na mašinu, koje su odredili podaci iz događaja „CalculateParameters“ u vezi sa kojima su donete programske odluke

- **AvailableClientVersionText** – Vrednost niske klijenta za verziju 16.0.xxxxx.yyyyy „Klikni i pokreni“ koja se nalazi u XML datoteci opisa verzije, koja se koristi za određivanje toga da li treba ažurirati trenutno instalirani klijent za verziju „Klikni i pokreni“

- **CleanFireFlyAction** – Ima vrednost „tačno“ ako je isplanirano da se zadatak CleanFireFlyAction pokrene tokom ovog instaliranja

- **CleanO15Action** – Ima vrednost „tačno“ ako je isplanirano da se zadatak CleanO15Action pokrene tokom ovog instaliranja

- **CMDMode** – Prepoznatljiva niska koja odgovara celokupnom prekidaču za režim otkrivenom u cmd argumentima prebačena je u izvršnu datoteku. Mogućnosti su: automatsko pokretanje, konfigurisanje, potrošačka verzija, preuzimanje, pomoć i program za pakovanje

- **DeliveryMechanism** – GUID „FFNRoot“ izdvojen iz XML datoteke opisa verzije (koju je označio RDX) koji saopštava putem kojih je korisnika/kanala dobijen izvor verzije

- **DownloadC2RClientAction** – Ima vrednost „tačno“ ako je isplanirano da se zadatak DownloadC2RClientAction pokrene tokom ovog instaliranja

- **ErrorCode** – Vrednost celog broja povezana sa nekontrolisanim izuzetkom

- **ErrorDetails** – Niska koja opisuje lokaciju na kojoj je došlo do nekontrolisanog izuzetka (funkcija, datoteka, broj reda, dodatni parametri koji postavlja izbacivač)

- **ErrorMessage** – Niska definisana u trenutku javljanja nekontrolisanog izuzetka koja opisuje prirodu otkazivanja

- **ErrorType** – Niska koja opisuje kategoriju nekontrolisanog izuzetka

- **ExitCode** – Vrednost celog broja povezana sa rezultatom pokretanja izvršne faze programa koji se pokreće prilikom pokretanja računara koja označava uspeh naspram određenih tipova otkazivanja

- **LaunchAction** – Ima vrednost „tačno“ ako je isplanirano da se zadatak LaunchAction pokrene tokom ovog instaliranja

- **LaunchUpdateAction** – Ima vrednost „tačno“ ako je isplanirano da se zadatak LaunchUpdateAction pokrene tokom ovog instaliranja

- **PreReqResult** – Numerička vrednost celog broja rezultata izvršavanja provera preduslova (prolaz/neuspeh/ponovno pokretanje)

- **UnexpectedAction** – Ima vrednost „tačno“ ako je isplanirano da se zadatak UnexpectedAction (slučaj greške) pokrene tokom ovog instaliranja

- **VersionToInstall** – Vrednost niske verzije 16.0.xxxxx.yyyyy sistema Office koja se instalira


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

  - **ECSConfigs** - Lista konfiguracije ECS odvojena zarezima

  - **LockType** - Tip FlightManager zaključavanja

  - **TasFlightingVersion** - Broj verzija

  - **TimeToLock** - Vreme koje protekne od liblet pokretanja do FlightManager zaključavanja

  - **UnmergedConfigs** - Lista konfiguracija koje nisu objedinjene

### <a name="officeexperimentationtriggeranalysis"></a>Office.Experimentation.TriggerAnalysis

Ovaj događaj pomaže u analizi opsega korištenja proizvoda i metrika performansi (kao što su padovi, prekidi, itd.) podskupa korisnika ili uređaja koji imaju pravo na korišćenje funkcije, i na taj način pomažu u osiguravanju ispravnog rada proizvoda.

Prikupljaju se sledeća polja:

  - **FeatureGate -** Identifikuje skup funkcija za koje je primenjiva analiza okidača.

## <a name="licensing-events"></a>Događaji licenciranja

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Ovo se prikuplja kada korisnik postane licenciran i prihvati EULA ugovor za trenutnu licencu

Koristi se za određivanje da li se korisnik nalazi u dobrom ili lošem statusu, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru

Prikupljaju se sledeća polja:

  - **ACID** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran

  - **DwEulaId** – Numerički identifikator za tip EULA ugovora koji je korisnik prihvatio

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Kada podesimo licencu na računaru, pokušavamo da je aktiviramo tako što pozivamo uslugu AVS. Ovo izveštava o ishodu poziva za aktivaciju

Od suštinskog je značaja za određivanje koliko korisnika nailazi na probleme prilikom aktivacije. Imamo detektor anomalija koji otkriva bilo koju regresiju. Ovo je veoma važno jer spoljno zavisimo od usluge AVS, a ovaj signal upućuje na to da li su naši spoljni partneri ispravni. Takođe se koristi i za dijagnostičke svrhe i ispravnost sistema ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **ReferralData** – Identifikator OEM proizvođača koji je instalirao Office na računaru

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

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran  

  - **IsSessionLicensing** - Da li je trenutno pokrenuta u režimu aktivacije deljenog računara ili nije. 

  - **LicenseCategory** – Kategorija Office licence koju koristi korisnik 

  - **Licenses** – Lista sa imenima svih Office licenci koje se nalaze na računaru 

  - **LicenseStatuses** – Status svih Office licenci koje se nalaze na računaru 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Ovo prikupljamo kad korisnik podešava uređaj, a mi pozivamo uslugu licenciranja da bismo otkrili da li prijavljeni korisnik ima prava na sistem Office ili nema. Ovo izveštava o ishodu tog poziva. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Prilikom svake sesije proveravamo da li je prošlo 72 sata od poslednje obnove licence i pokušavamo da produžimo rok isteka trenutne licence. Ovaj događaj izveštava o uspešnosti ili neuspešnosti poziva koji smo uputili da bismo proverili da li možemo da produžimo rok isteka licence i da korisnikovu instalaciju sistema Office održimo u funkciji. Od suštinske je važnosti pri dijagnostikovanju korisnikovih problema vezanih za pretplatu i uslugu, kao i za otkrivanje regresija kod korisnika koji su već aktivirali pretplatu.

Prikupljaju se sledeća polja:

  - **Mode** – Numeričko predstavljanje paketa licenci za sistem Office koji se koristi na računaru

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Ako uređaj uđe u režim smanjene funkcionalnosti, šaljemo ovaj signal da bismo naznačili da se računar ne nalazi u ispravnom stanju. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu,a nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

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

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Ako uređaj naiđe na probleme sa licenciranjem i dođe do toga da korisniku prikažemo sabirnicu, šaljemo ovaj signal koji izveštava i o tipu sabirnice koja je prikazana korisniku. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **SuppressNotification** - Označava da li smo potisnuli sabirnicu licenciranja

  - **Title** - Naziv sabirnice licenciranja koja je prikazana korisniku

  - **Type** - Tip sabirnice licenciranja koja je prikazana korisniku

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Ako dođe do zatvaranja ili pada sistema Office zbog problema sa licenciranjem, šaljemo ovaj signal da bismo to naznačili. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

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

  - **Acid** – GUID identifikator koji predstavlja Office proizvod za koji je korisnik licenciran 

  - **OptInShown** – Pokazuje da li je već prikazan dijalog za davanje saglasnosti koji se prikazuje prilikom prvog pokretanja aplikacije

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

Ovaj signal nam pokazuje da li je korisnik kvalifikovan za prelazak na novi paket licenci. Ovo je od suštinske važnosti za određivanje stepena uticaja na postojeće korisnike dok objavljujemo nove pakete licenci i obezbeđivanje da korisnici zadrže funkcionalnost.

Ovaj događaj ne prikuplja nikakva polja.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Kada je uređaj na modernom paketu licence, trudimo se da datoteku licence preuzmemo direktno iz usluge. Ovaj događaj izveštava o uspešnosti ili neuspešnosti, kao i o kôdu greške kod poziva usluge. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu kod modernog paketa licence, za ispravnost sistema i za svrhe dijagnostikovanja ako korisnik prijavi problem na računaru.

Prikupljaju se sledeća polja:

  - **MetadataValidationResult** - Rezultat provere valjanosti metapodataka licence da bi se proverilo da nisu neovlašćeno promenjeni

  - **SignatureValidationResult** - Rezultat provere valjanosti potpisa da bi se proverilo da nije neovlašćeno promenjen

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Ovo se prikuplja pri svakoj sesiji uređaja koji je pokrenut na modernom paketu licence. Izveštava o statusu licence na računaru i greškama koje se prikazuju korisniku zbog kojih nije u mogućnosti da koristi aplikaciju. Ovaj događaj ukazuje na to da li je ispravan korisnikov računar na modernom paketu licence. Za ovaj događaj imamo podešen detektor anomalija da bismo označili da li regresija uzrokuje neispravno ponašanje korisnika. Takođe je od suštinske važnosti pri dijagnostikovanju korisničkih problema i za nadgledanje ispravnosti sistema.

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

  - **SkuIdIsNull** - Ukazuje na to da li smo naišli na grešku i ne znamo koji proizvod korisnika pokreće 

  - **SlapiIsNull** - Ukazuje na to da li smo naišli na problem u popunjavanju jednog od objekata licenciranja  

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Ovaj događaj se pokreće ako iz nekog razloga nismo u mogućnosti da aktiviramo korisnika i moramo da im prikažemo dijalog koji mu traži da se priključi na mrežu i pokuša da prati korake za popravak. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru

Ovaj događaj ne prikuplja polja.

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Sprovodimo eksperiment koji korisniku pruža mogućnost da isproba i podesi automatsko plaćanje za Office direktno iz aplikacije bez potrebe da napušta aplikaciju. Ovo izveštava o uspešnosti ili neuspešnosti datog eksperimenta, kao i o kôdu greške. Od suštinske je važnosti za određivanje da li se korisnik nalazi u dobrom statusu i ne nedostaje mu funkcionalnost, za ispravnost sistema i za dijagnostičke svrhe ako korisnik prijavi problem na računaru.

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

## <a name="microsoft-autoupdate-mau-events"></a>Događaji aplikacije Microsoft AutoUpdate (MAU)

### <a name="appdelegate_launch"></a>appdelegate_launch

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


### <a name="appdelegate_terminate"></a>appdelegate_terminate

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


### <a name="appinstall_connecttoxpc"></a>appinstall_connecttoxpc

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


### <a name="appregistry_info"></a>appregistry_info

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


### <a name="appregistry_remove"></a>appregistry_remove

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


### <a name="catalog_errorsignature"></a>catalog_errorsignature

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom validacije potpisivanja kodom u pomoćnoj datoteci ispravke.  Sve pomoćne datoteke za koje nije uspela verifikacija potpisa kodom treba smatrati nevažećim.

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

- **Payload** – Sadrži ime datoteke kataloga sa nevažećim potpisom. Različiti statički tekstovi opisuju različita stanja greške.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva tri okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="cloningtask_helpertoolconnection"></a>cloningtask_helpertoolconnection

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


### <a name="configuration_channel"></a>configuration_channel

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


### <a name="configuration_metadata"></a>configuration_metadata

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


### <a name="controller_alertmanager_reinstallresponse"></a>controller_alertmanager_reinstallresponse

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

    
### <a name="controller_alertmanager_tmpdiskfull"></a>controller_alertmanager_tmpdiskfull

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


### <a name="controller_alertmanager_tmpdiskfullretry"></a>controller_alertmanager_tmpdiskfullretry

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
    

### <a name="controller_alertmanager_tmpdiskfullretrycancel"></a>controller_alertmanager_tmpdiskfullretrycancel

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

    
### <a name="controller_checkwindow_noupdatefoundok"></a>controller_checkwindow_noupdatefoundok

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

    

### <a name="controller_checkwindow_updatecheck"></a>controller_checkwindow_updatecheck

Ovaj događaj pokazuje da je provereno da li postoje ispravke. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način, za optimizaciju opterećenja usluge i definisanje toga koliko često treba proveravati da li postoje ispravke. Želimo i da optimizujemo učestalost izdavanja na osnovu očekivanja korisnika u vezi sa ispravkama.

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


### <a name="controller_checkwindow_updatecheckcancel"></a>controller_checkwindow_updatecheckcancel

Ovaj događaj pokazuje da je korisnik ili sistem otkazao proces provere da li postoje ispravke. Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način, za optimizaciju opterećenja usluge i definisanje toga koliko često treba proveravati da li postoje ispravke. Želimo i da optimizujemo učestalost izdavanja na osnovu očekivanja korisnika u vezi sa ispravkama.

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

    
### <a name="controller_checkwindow_updatecheckcanceluser"></a>controller_checkwindow_updatecheckcanceluser

Ovaj događaj pokazuje da je korisnik otkazao proces provere da li postoje ispravke.  Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način, za optimizaciju opterećenja usluge i definisanje toga koliko često treba proveravati da li postoje ispravke. Želimo i da optimizujemo učestalost izdavanja na osnovu očekivanja korisnika u vezi sa ispravkama.

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

    
### <a name="controller_checkwindow_updatesfound"></a>controller_checkwindow_updatesfound

Ovaj događaj pokazuje da su se tokom procesa provere da li postoje ispravke pronašle ispravke.  Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način.

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

    
### <a name="controller_checkwindow_uptodate"></a>controller_checkwindow_uptodate

Ovaj događaj pokazuje da tokom procesa provere da li postoje ispravke nisu pronađene ispravke jer su aplikacije na uređaju ažurirane.  Koristimo ga da bismo obezbedili da se ispravke nude na odgovarajući način.

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


### <a name="controller_downloadwindow_applaunchwithpendingupdate"></a>controller_downloadwindow_applaunchwithpendingupdate

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

    
### <a name="controller_downloadwindow_closeapplicationdialog"></a>controller_downloadwindow_closeapplicationdialog

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

    
### <a name="controller_downloadwindow_curtasknull"></a>controller_downloadwindow_curtasknull

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

    
### <a name="controller_downloadwindow_downloadcancel"></a>controller_downloadwindow_downloadcancel

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

    
### <a name="controller_downloadwindow_downloadfailed"></a>controller_downloadwindow_downloadfailed

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

    
### <a name="controller_downloadwindow_downloadfailedok"></a>controller_downloadwindow_downloadfailedok

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


### <a name="controller_downloadwindow_downloadpathmissing"></a>controller_downloadwindow_downloadpathmissing

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


### <a name="controller_downloadwindow_downloadtasknull"></a>controller_downloadwindow_downloadtasknull

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


### <a name="controller_downloadwindow_filesignaturenotverified"></a>controller_downloadwindow_filesignaturenotverified

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


### <a name="controller_downloadwindow_installcomplete"></a>controller_downloadwindow_installcomplete

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


### <a name="controller_downloadwindow_networkunavailablealert"></a>controller_downloadwindow_networkunavailablealert

Ovaj događaj pokazuje da je mrežna veza izgubljena tokom preuzimanja ispravki.  Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_downloadwindow_networkunavailablealertok"></a>controller_downloadwindow_networkunavailablealertok

Ovaj događaj pokazuje da je mrežna veza izgubljena tokom preuzimanja ispravki. On pokazuje i da je korisnik obavešten o toj grešci. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_downloadwindow_noconnectionok"></a>controller_downloadwindow_noconnectionok

Ovaj događaj pokazuje da je mrežna veza izgubljena tokom preuzimanja ispravki. On pokazuje i da je korisnik obavešten o toj grešci. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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


### <a name="controller_downloadwindow_repairrequired"></a>controller_downloadwindow_repairrequired

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

### <a name="controller_downloadwindow_updateaborted"></a>controller_downloadwindow_updateaborted

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


### <a name="controller_downloadwindow_updatefailed"></a>controller_downloadwindow_updatefailed

Ovaj događaj pokazuje da nisu uspele neke ispravke iz trenutne grupe. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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


### <a name="controller_downloadwindow_updatesuccessful"></a>controller_downloadwindow_updatesuccessful

Ovaj događaj pokazuje da su uspele sve ispravke iz trenutne grupe. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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


### <a name="controller_downloadwindow_userpaused"></a>controller_downloadwindow_userpaused

Ovaj događaj pokazuje da su uspele sve ispravke iz trenutne grupe. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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


### <a name="controller_downloadwindow_userresumed"></a>controller_downloadwindow_userresumed

Ovaj događaj pokazuje da je proces preuzimanja ispravki uspešno nastavljen posle pauziranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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


### <a name="controller_mainwindow_setautomaticdownloadinstall"></a>controller_mainwindow_setautomaticdownloadinstall

Ovaj događaj pokazuje da je uređaj registrovan za režim automatskog ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_mainwindow_setmanualchecking"></a>controller_mainwindow_setmanualchecking

Ovaj događaj pokazuje da je uređaj registrovan za režim ručnog ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_templateawindow_cancel"></a>controller_templateawindow_cancel

Ovaj događaj pokazuje da je korisnik odabrao da otkaže ili zanemari prikazanu poruku upozorenja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_templateawindow_enroll"></a>controller_templateawindow_enroll

Ovaj događaj pokazuje da je korisnik odabrao da prihvati prikazanu preporuku upozorenja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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



### <a name="controller_templateawindow_install"></a>controller_templateawindow_install

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


### <a name="controller_updatewindow_begindownloadingapps"></a>controller_updatewindow_begindownloadingapps

Ovaj događaj pokazuje da je preuzimanje ispravki započeto putem prozora za ažuriranje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.

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

    
### <a name="controller_updatewindow_networkretry"></a>controller_updatewindow_networkretry

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

    
### <a name="controller_updatewindow_networkretrycancel"></a>controller_updatewindow_networkretrycancel

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


### <a name="controller_updatewindow_networkunavailable"></a>controller_updatewindow_networkunavailable

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


### <a name="controller_updatewindow_noupdateavailable"></a>controller_updatewindow_noupdateavailable

Ovaj događaj pokazuje da je izvršena provera da li postoje ispravke koja je otkrila da ne postoje dostupne ispravke. On pokazuje da Microsoft Autoupdate nije pronašao dostupne ispravke. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="controller_updatewindow_noupdatestoselect"></a>controller_updatewindow_noupdatestoselect

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


### <a name="controller_updatewindow_updateavailable"></a>Controller_UpdateWindow_UpdateAvailable

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

    
### <a name="controller_updatewindow_updateavailablecancel"></a>controller_updatewindow_updateavailablecancel

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


### <a name="downloadactor_pause"></a>downloadactor_pause

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


### <a name="downloadactor_redirect"></a>downloadactor_redirect

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

    
### <a name="downloadactor_resume"></a>downloadactor_resume

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


### <a name="downloadactor_resumeerror"></a>downloadactor_resumeerror

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

    
### <a name="downloadactor_status"></a>downloadactor_status

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


### <a name="downloadmanifest_downloadcatalogfail"></a>downloadmanifest_downloadcatalogfail

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

    
### <a name="downloadmanifest_downloadcatalogsuccess"></a>downloadmanifest_downloadcatalogsuccess

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


### <a name="downloadmanifest_downloadfail"></a>downloadmanifest_downloadfail

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


### <a name="downloadmanifest_downloadfromurl"></a>downloadmanifest_downloadfromurl

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


### <a name="downloadmanifest_downloading"></a>downloadmanifest_downloading

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


### <a name="downloadmanifest_downloadsuccess"></a>downloadmanifest_downloadsuccess

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

    
### <a name="downloadmanifest_downloadurl"></a>downloadmanifest_downloadurl

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


### <a name="downloadmanifest_filenameerror"></a>downloadmanifest_filenameerror

Ovaj događaj pokazuje da je došlo do neočekivane greške. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="downloadmanifest_invalidhash"></a>downloadmanifest_invalidhash

Ovaj događaj pokazuje nije uspela bezbednosna provera valjanosti datoteka. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="downloadmanifest_missingdaemon"></a>downloadmanifest_missingdaemon

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


### <a name="downloadmanifest_signatureerror"></a>downloadmanifest_signatureerror

Ovaj događaj pokazuje da za paket nije uspela verifikacija potpisa koda. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="downloadmanifest_status"></a>downloadmanifest_status

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


### <a name="downloadmgr_downloadend"></a>downloadmgr_downloadend

Ovaj događaj evidentira označivač koji pokazuje da se proces preuzimanja samostalno dovršio. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="downloadmgr_downloadstart"></a>downloadmgr_downloadstart

Ovaj događaj evidentira ispravku koja će se preuzeti. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="downloadtask_downloadfailure"></a>downloadtask_downloadfailure

Ovaj događaj evidentira to da je došlo do greške prilikom preuzimanja datoteke paketa. Evidentiramo putanju ispravke i grešku. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži ime ispravke koja se preuzima i uočenu grešku.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="downloadtask_downloadsuccess"></a>downloadtask_downloadsuccess

Uspešno preuzimanje datoteke paketa. Evidentiramo putanju ispravke koja se koristi. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži putanju ispravke za uspešno preuzimanje.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fba_checkforupdate"></a>fba_checkforupdate

Ovaj događaj pokazuje da proces u pozadini proverava da li postoje ispravke. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fba_checkforupdateskip"></a>fba_checkforupdateskip

Ovaj događaj pokazuje da je proces u pozadini preskočio ažuriranje zbog toga što je otvoren grafički korisnički interfejs aplikacije MAU. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fba_launchstatus"></a>fba_launchstatus

Ovaj događaj evidentira otkazivanja daemona aplikacije MAU prilikom pokušaja pokretanja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži status operativnog sistema (kôd Apple statusa) koji pokazuje status pokretanja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fba_silentupdateoptin"></a>fba_silentupdateoptin

Ovaj događaj pokazuje da korisnik daje saglasnost za tiha ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fba_skipforcedupdate"></a>fba_skipforcedupdate

Ovaj događaj pokazuje da se preskače nametnuta provera da li postoje ispravke zbog otvorenih aplikacija. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fba_startforcedupdate"></a>fba_startforcedupdate

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


### <a name="fba_terminate"></a>fba_terminate

Ovaj događaj pokazuje da je daemon aplikacije MAU normalno prekinut. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fba_updatefound"></a>fba_updatefound

Ovaj događaj pokazuje da je daemon aplikacije MAU pronašao dostupne ispravke koje će ponuditi. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="fba_updatetimer"></a>fba_updatetimer

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


### <a name="fbasilentupdate_allappsclosed"></a>fbasilentupdate_allappsclosed

Ovaj događaj evidentira to da li su sve aplikacije zatvorene pre instaliranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_applaunchafterupdate"></a>fbasilentupdate_applaunchafterupdate

Ovaj događaj evidentira pokušaj ponovnog pokretanja aplikacije posle tihog ažuriranja i režim ažuriranja (klon ili ne). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ime aplikacije koja se pokreće.
    
- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)
    
- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdate_applaunchwileinstalling"></a>fbasilentupdate_applaunchwileinstalling

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


### <a name="fbasilentupdate_appneedtoclose"></a>fbasilentupdate_appneedtoclose

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


### <a name="fbasilentupdate_appterminationeventreceived"></a>fbasilentupdate_appterminationeventreceived

Ovaj događaj pokazuje da je Microsoft Autoupdate primio Apple događaj kojim se obaveštava o tome da je aplikacija prekinuta. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži identifikator koji se koristi za praćenje aktivnosti ažuriranja i ID kompleta za aplikaciju. Može da sadrži i nisku greške ako Microsoft Autoupdate odredi da je aplikacija još uvek pokrenuta iako je primljen događaj prekidanja.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdate_codesignfailure"></a>fbasilentupdate_codesignfailure

Ovaj događaj evidentira rezultat verifikacije potpisa kodom posle primene ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_download"></a>fbasilentupdate_download

Ovaj događaj pokazuje da se ispravka preuzima. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_downloadfailed"></a>fbasilentupdate_downloadfailed

Ovaj događaj pokazuje da je došlo do otkazivanja prilikom preuzimanja ispravke. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_downloadinbackground"></a>fbasilentupdate_downloadinbackground

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


### <a name="fbasilentupdate_downloadingrepairupdate"></a>fbasilentupdate_downloadingrepairupdate

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

- **SessionId** – Identifikator sesije


### <a name="fbasilentupdate_duplicatedownloadattempted"></a>fbasilentupdate_duplicatedownloadattempted

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


### <a name="fbasilentupdate_installattemptfailed"></a>fbasilentupdate_installattemptfailed

Ovaj događaj pokazuje da nije uspeo pokušaj instaliranja ispravke (verzije). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_installcomplete"></a>fbasilentupdate_installcomplete

Ovaj događaj pokazuje da je završeno instaliranje svih ispravki iz paketa. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_installed"></a>fbasilentupdate_installed

Ovaj događaj pokazuje da je pojedinačna ispravka uspešno instalirana. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="fbasilentupdate_installing"></a>fbasilentupdate_installing

Ovaj događaj pokazuje da je pokrenuta pojedinačna ispravka. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_notificationremoved"></a>fbasilentupdate_notificationremoved

Ovaj događaj pokazuje da ispravka koja je bila blokirana nije više blokirana. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_queueinstall"></a>fbasilentupdate_queueinstall

Ovaj događaj pokazuje da se ispravka stavlja u red za čekanje za tiho instaliranje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_requiredappsclosed"></a>fbasilentupdate_requiredappsclosed

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


### <a name="fbasilentupdate_updateavailablenotification"></a>fbasilentupdate_updateavailablenotification

Ovaj događaj pokazuje da je pokrenuto obaveštenje o dostupnoj ispravci. Moramo da obezbedimo da se pokrene tok traženja ispravki kada se otkrije ispravka. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="fbasilentupdate_userclicknotification"></a>fbasilentupdate_userclicknotification

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


### <a name="fbasilentupdate_userselectinstalllater"></a>fbasilentupdate_userselectinstalllater

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


### <a name="fbasilentupdate_userselectinstallnow"></a>fbasilentupdate_userselectinstallnow

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


### <a name="installdata_checkrunning"></a>installdata_checkrunning

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

    
### <a name="installdata_cleanup"></a>installdata_cleanup

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


### <a name="installedapp_invalidbundle"></a>installedapp_invalidbundle

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

    
### <a name="installedapp_invalidpreference"></a>installedapp_invalidpreference

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

    
### <a name="installedapp_nilbundleid"></a>installedapp_nilbundleid

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


### <a name="installedapp_nilbundlename"></a>installedapp_nilbundlename

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

    
### <a name="installstatus_codesign"></a>installstatus_codesign

Ovaj događaj evidentira status binarnog alata operativnog sistema za potpisivanje koda. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installstatus_daemon"></a>installstatus_daemon

Ovaj događaj evidentira stanje statusa daemona aplikacije Microsoft AutoUpdate. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

- **Payload** – Sadrži naznaku toga da li komponenta daemona postoji na očekivanoj lokaciji i da li je potpisana kodom.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="installstatus_helper"></a>installstatus_helper

Ovaj događaj evidentira stanje statusa alatke pomoćnika za Microsoft AutoUpdate. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="installupdatestask_applaunched"></a>installupdatestask_applaunched

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

    
### <a name="installupdatestask_applaunchwithpendingupdate"></a>installupdatestask_applaunchwithpendingupdate

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

    
### <a name="installupdatestask_codesignverificationfail"></a>installupdatestask_codesignverificationfail

Ovaj događaj pokazuje da nije uspela verifikacija potpisa kodom za ispravku za aplikaciju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_codesignverificationstart"></a>installupdatestask_codesignverificationstart

Ovaj događaj pokazuje da je verifikacija potpisa kodom pokrenuta za ispravku za aplikaciju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_codesignverificationsuccess"></a>installupdatestask_codesignverificationsuccess

Ovaj događaj pokazuje uspešnu verifikaciju potpisa kodom za ispravku za aplikaciju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_failsilentinstall"></a>installupdatestask_failsilentinstall

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

    
### <a name="installupdatestask_multiplerelocatablepackage"></a>installupdatestask_multiplerelocatablepackage

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

    
### <a name="installupdatestask_removeclone"></a>installupdatestask_removeclone

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


### <a name="installupdatestask_retryfail"></a>installupdatestask_retryfail

Ovaj događaj pokazuje da je došlo do grešaka tokom procesa pokušaja ponovnog instaliranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

Ovaj događaj evidentira greške u komunikaciji unutar procesa (komunikacija sa alatkom pomoćnik za MAU). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

Ovaj događaj evidentira greške u komunikaciji unutar procesa (komunikacija sa alatkom pomoćnik za MAU). Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    

### <a name="installupdatestask_retryresponse"></a>installupdatestask_retryresponse

Ovaj događaj evidentira to da ponovni pokušaj nije uspeo. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_retrysuccess"></a>installupdatestask_retrysuccess

Ovaj događaj evidentira uspešno instaliranje ispravke posle ponovnog pokušaja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="installupdatestask_setreopengui"></a>installupdatestask_setreopengui

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

- **Payload** – Tekst koji označava da li je operacija uspela.

- **PipelineInfo_ClientCountry** – Zemlja u kojoj se nalazi uređaj (na osnovu IP adrese)

- **PipelineInfo_ClientIp** – Prva 3 okteta IP adrese

- **SessionId** – Identifikator sesije


### <a name="msupdate_cli_eventhandler_applyupdates_appids"></a>msupdate_cli_eventhandler_applyupdates_appids

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


### <a name="msupdate_cli_eventhandler_config"></a>msupdate_cli_eventhandler_config

Ovaj događaj pokazuje da je modul interfejsa sa komandnom linijom aplikacije Microsoft Autoupdate primio Apple događaj za konfigurisanje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="msupdate_cli_eventhandler_updates"></a>msupdate_cli_eventhandler_updates

Ovaj događaj pokazuje da je modul interfejsa sa komandnom linijom aplikacije Microsoft Autoupdate primio Apple događaj za navođenje ispravki. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="msupdate_monitor_progress_downloaded"></a>msupdate_monitor_progress_downloaded

Ovaj događaj pokazuje da su ispravke preuzete. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="msupdate_monitor_progress_failure"></a>msupdate_monitor_progress_failure

Ovaj događaj evidentira listu ispravki u redu za čekanje čija primena nije uspela. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="msupdate_monitor_progress_finished"></a>msupdate_monitor_progress_finished

Ovaj događaj evidentira listu ispravki u redu za čekanje čije je instaliranje završeno. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="msupdate_monitor_progress_queued"></a>msupdate_monitor_progress_queued

Ovaj događaj evidentira listu ispravki u redu za čekanje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

Ovaj događaj evidentira odgovor korisnika u dijalogu za davanje saglasnosti za registrovanje za tiha ažuriranja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="sauupdateinfoprovider"></a>sauupdateinfoprovider

Ovaj događaj evidentira svaki put kada ključ manifesta nedostaje u pomoćnoj datoteci. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatecore_appregistration"></a>updatecore_appregistration

Ovaj događaj evidentira pokušaje registrovanja aplikacije i rezultat/razlog. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatecore_loadinglaunchagent"></a>updatecore_loadinglaunchagent

Ovaj događaj pokazuje da je učitan agent pokretanja. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatecore_server_connectionfail"></a>updatecore_server_connectionfail

Ovaj događaj evidentira greške na koje se naišlo na putu do sistema CDN. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatefilterhelper_cannotretrievebuilddate"></a>updatefilterhelper_cannotretrievebuilddate

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


### <a name="updatefilterhelper_invalidresponsefromupdatefiltering"></a>updatefilterhelper_invalidresponsefromupdatefiltering

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


### <a name="updatefilterhelper_missingbuilddate"></a>updatefilterhelper_missingbuilddate

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


### <a name="updatefilterhelper_updatebypassedoldage"></a>updatefilterhelper_updatebypassedoldage

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


### <a name="updatefinder_check_start"></a>updatefinder_check_start

Ovaj događaj evidentira svaki put kada pokrenemo operaciju provere da li postoje ispravke. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatefinder_check_status"></a>updatefinder_check_status

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


### <a name="updatefinder_check_updatefound"></a>updatefinder_check_updatefound

Evidentiramo svaki put kada se provera da li postoje ispravke završi pronalaženjem ispravki. Ovaj događaj koristimo da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="updatefinder_check_updatenotfound"></a>updatefinder_check_updatenotfound

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


### <a name="updatefinder_check_uptodate"></a>updatefinder_check_uptodate

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


### <a name="updatefinder_offerupdates_minoscheckfail"></a>updatefinder_offerupdates_minoscheckfail

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


### <a name="updatefinder_offerupdates_nullbundleforappid"></a>updatefinder_offerupdates_nullbundleforappid

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


### <a name="updatefinder_offerupdates_updaterulematched"></a>updatefinder_offerupdates_updaterulematched

Ovaj događaj pokazuje da je pronađena ispravka za aplikaciju i osnovnu verziju. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="updatefinder_registeredapps"></a>updatefinder_registeredapps

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

    
### <a name="updatefinder_suite_missingcollateral"></a>updatefinder_suite_missingcollateral

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


### <a name="updatefinder_suite_staleversion"></a>updatefinder_suite_staleversion

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


### <a name="updatefinder_suite_updateapplicable"></a>updatefinder_suite_updateapplicable

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


### <a name="updatefinder_suite_updatenotapplicabledefaultpath"></a>updatefinder_suite_updatenotapplicabledefaultpath

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

    
### <a name="updatefinder_suite_updatenotapplicableversion"></a>updatefinder_suite_updatenotapplicableversion

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


### <a name="updatefinder_suite_updatenotoffered"></a>updatefinder_suite_updatenotoffered

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


### <a name="updatefinder_suite_updateoffered"></a>updatefinder_suite_updateoffered

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


### <a name="updatemanager_checkupdate"></a>updatemanager_checkupdate

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

    
### <a name="updatemanager_updatespending"></a>updatemanager_updatespending

Ovaj događaj pokazuje da su ispravke pronađene i da čekaju na instaliranje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="webservices_checkforsilentupdates"></a>webservices_checkforsilentupdates

Ovaj događaj pokazuje da su pronađeni kandidati za tiho ažuriranje. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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


### <a name="webservices_deltaupdater"></a>webservices_deltaupdater

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


### <a name="webservices_serviceaction"></a>webservices_serviceaction

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


### <a name="webservices_serviceaction"></a>webservices_serviceaction

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


### <a name="webservices_serviceresponse"></a>webservices_serviceresponse

Ovaj događaj evidentira zahteve upućene MAU usluzi, vremena odziva i greške. Koristimo ga da bismo obezbedili da proces ažuriranja funkcioniše na očekivani način i da bismo vam pomogli prilikom rešavanja problema u slučaju grešaka.
 
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

    
### <a name="webservices_silentupdate"></a>webservices_silentupdate

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



### <a name="webservices_webcontent"></a>webservices_webcontent

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

## <a name="onenote-sync-events"></a>Događaji sinhronizovanja programa OneNote

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ovaj događaj evidentira rezultat sinhronizacije beležnice. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote.
 
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
 
Ovaj događaj evidentira rezultat sinhronizovanja odeljka. Koristi se za otkrivanje broja jedinstvenih ciljeva sinhronizacije kada se izračunava rezultat sinhronizacije programa OneNote. Koristi se i za kontrolnu tablu performansi moderne sinhronizacije programa OneNote.
 
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

- **NotebookId** – ID beležnice

- **PageSyncUIState** – Niska statusa sinhronizovanja stranice, na primer UpToDate, Syncing, SaveOffline, SyncError itd. 

- **ServerGosid** – ID resursa za novu napravljenu stranicu sa neusaglašenostima

- **Source** – Identifikator koji pokazuje koji je događaj pokrenuo korisnički interfejs, to jest napravio novu Redx sliku, grešku pri sinhronizovanju u korisničkom interfejsu sinhronizacije, prikazani dijalog greške itd.


## <a name="services-configuration-events"></a>Događaji konfiguracije usluga

Konfiguracija usluga ne prikuplja neophodne dijagnostičke podatke o usluzi.

## <a name="telemetry-events"></a>Događaji telemetrije

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Informacije o korisničkom identitetu koje su potrebne za ispunjavanje podataka koji podležu zahtevima

Prikupljaju se sledeća polja:

  - **IdentityChanged** - Uvek istinito. Identitet je promenjen.

  - **TimerDetectedChange** - Da li je promena otkrivena u redovnom vremenskom pingu.

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Koristi se da bi se utvrdilo da li postoje neuspesi u čitanju postavki privatnosti korisnika iz Roaming prodavnice.

Prikupljaju se sledeća polja:

  - **Oznaka - **Oznaka koda koja pokazuje koja postavka se vratila u skladište postavki.

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

  - **IsDebug –** Da li je ovo verzija programa Office u kojoj su otklonjene greške.

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

  - **PreviousBuild** – Verzija na koju je Office izdanje nadograđeno ili sa koje je vraćeno.

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

Događaj pokreće neočekivani prekid aplikacije (na primer, uklanjanje u upravljaču zadacima, prekid aplikacije, itd.) za Office klijentske aplikacije kao što su, ali ne ograničavajući se na, Word, Excel, PowerPoint i Outlook. Metrike neočekivanog izlaska iz aplikacija koristimo za merenje ispravnosti proizvoda klijenata sistema Office. To je signal, ključan za posao, koji koriste Office inženjeri da bi postigli stabilnost proizvoda.

Prikupljaju se sledeća polja:

  - **CrashedAppBuild -** Identifikator izdanja verzije ugroženog procesa.

  - **CrashedAppMajor -** Identifikator glavne verzije ugroženog procesa.

  - **CrashedAppMinor -** Identifikator međuverzije ugroženog procesa.

  - **CrashedAppRevision -** Identifikator izdanja verzije ugroženog procesa.

  - **CrashedEcsETag -** Identifikator eksperimenta palog procesa.

  - **CrashedModuleName -** Ime neispravnog modula.

  - **CrashedSessionId -** Jedinstveni identifikator palog procesa.

  - **CrashedSessionInitTime -** Vreme kada je počeo ugroženi proces.

  - **CrashType -** Identifikator grupe za tip pada

  - **DetectionTime -** Vreme kada je otkriven neočekivani izlaz.

  - **ExceptionAddress -** Adresa u aplikaciji u kojoj je došlo je do greške.

  - **ExceptionCode -** Identifikator grupe za izuzetak.

  - **HexCrashTag -** Jedinstveni identifikator za kôd pada.

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

  - **UninitLibletId –** Jedinstveni identifikator za neispravnu komponentu pada.

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
