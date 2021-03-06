---
title: Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Administratorima sistema Office pruža informacije o tome kako da upravljaju kontrolama privatnosti u Microsoft 365 aplikacijama za velika preduzeća (ranije poznato kao Office 365 ProPlus) pomoću regulatornih postavki.
hideEdit: true
ms.openlocfilehash: 636916acf0cb36eecc7ba51318467264bb9ff2d4
ms.sourcegitcommit: 2c4bf05e77415559080766cc7d7f241e9f968108
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2021
ms.locfileid: "51181220"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-microsoft-365-apps-for-enterprise"></a>Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Microsoft je posvećen tome da vam pruži informacije i kontrole koje su vam potrebne da biste odabrali način prikupljanja i upotrebe vaših podataka kada koristite Microsoft 365 aplikacije za velika preduzeća (ranije poznato kao Office 365 ProPlus).

Počevši od verzije 1904 usluge Microsoft 365 Apps za preduzeće, postojaće nove regulatorne postavke koje će vam omogućiti da kontrolišete postavke koje se odnose na sledeće:

- ***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi

- ***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.

Ovo je pet novih regulatornih postavki:

- Podesite nivo dijagnostičkih podataka klijentskog softvera koje Office šalje korporaciji Microsoft
- Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj
- Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office

Ove regulatorne postavke mogu da se implementiraju korišćenjem Grupnih pravila ili [Uslugom pravila za Office iz oblaka](../overview-office-cloud-policy-service.md). Ako koristite Grupna pravila, potrebno je da preuzmete najnoviju verziju datoteka administrativnih predložaka (ADMX/ADML) sa [Microsoft centra za preuzimanje](https://www.microsoft.com/download/details.aspx?id=49030).

> [!NOTE]
> - Za informacije o tome kako da upravljate kontrolama privatnosti u sistemu Office za Mac, pogledajte članak [Korišćenje željenih postavki za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md).
> - Za više informacija o sličnim postavkama za Office na uređajima koji koriste iOS pogledajte članak [Koristite regulatorne postavke za upravljanje kontrolama privatnosti za Office na iOS uređajima](ios-privacy-preferences.md).
> - Za više informacija o sličnim postavkama za Office na Android uređajima pogledajte članak [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md).
> - Za više informacija o kontrolama privatnosti za Office aplikacije na vebu pogledajte članak [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office za veb aplikacije](office-web-privacy-controls.md).


Ako koristite alatku za upravljanje grupnim pravilima, sve ove regulatorne postavke se nalaze u okviru Konfiguracija korisnika\\Politika\\Administrativni predlošci\\Microsoft Office 2016\\Privatnost\\ Centar za pouzdanost.

Ove nove regulatorne postavke se primenjuju i na verzije programa Project i Visio za računare koje se dobijaju uz neke planove pretplata, kao što su Project Plan 5 ili Visio Plan 2. Primenjuju se i na Microsoft 365 aplikacije za manje firme (ranije poznato kao Office 365 Business).

Postoje i neke postojeće regulatorne postavke koje se više neće primenjivati na Microsoft 365 Apps za preduzeće, kao i neke promene korisničkog interfejsa (UI) za postavke privatnosti koje bi trebalo da imate na umu jer vaši korisnici mogu da ih primete i da vam postave pitanja o njima.

Kao i sa bilo kojim novim regulatornim postavkama, pažljivo ih testirajte u kontrolisanom okruženju da obezbedite da postavke koje ste konfigurisali imaju željeni efekat pre nego što ih implementirate u vašoj organizaciji.

## <a name="policy-setting-for-diagnostic-data"></a>Regulatorne postavke za dijagnostičke podatke

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod.

Možete da koristite regulatornu postavku *Podesite nivo dijagnostičkih podataka klijentskog softvera koje Office šalje korporaciji Microsoft* da biste odabrali koji nivo dijagnostičkih podataka se šalje korporaciji Microsoft.

Ako omogućite ovu regulatornu postavku, morate da odaberete nivo dijagnostičkih podataka koji se šalje korporaciji Microsoft. Opcije između kojih možete da odaberete su Obavezni, Opcionalni ili Nijedan.

- Ukoliko odaberete ***Obavezan*** nivo, korporaciji Microsoft se šalju minimalni podaci neophodni da bi Office bio bezbedan, ažuriran i da radi kao što se očekuje na uređaju na kome je instaliran.

- Ukoliko odaberete ***Opcionalan*** nivo, korporaciji Microsoft se šalju dodatni podaci koji nam pomažu da poboljšamo proizvod i oni pružaju dodatne informacije koje nam pomažu u detektovanju, dijagnostikovanju i rešavanju problema. Ako odaberete da nam pošaljete opcionalne dijagnostičke podatke, oni se prikupljaju uz obavezne dijagnostičke podatke.

- Ako odaberete ***Nijedan***, nikakvi dijagnostički podaci o Office klijentskom softveru koji radi na uređaju korisnika se ne prikupljaju i ne šalju korporaciji Microsoft. Ova opcija, međutim, znatno ograničava našu mogućnost da otkrijemo, dijagnoziramo i rešimo probleme na koje vaši korisnici mogu da naiđu dok koriste Office.

Ako onemogućite ili ne konfigurišete ovu regulatornu postavku, opcionalni i obavezni dijagnostički podaci se šalju korporaciji Microsoft.

Za više informacija o dijagnostičkim podacima pogledajte sledeće članke:

- [Pregled kontrola privatnosti za Microsoft 365 Apps za preduzeće](overview-privacy-controls.md)
- [Obavezni dijagnostički podaci za Office](required-diagnostic-data.md)
- [Opcionalni dijagnostički podaci za Office](optional-diagnostic-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="policy-settings-for-connected-experiences"></a>Regulatorne postavke za povezana iskustva

Microsoft 365 Apps za preduzeće se sastoji od aplikacija klijentskog softvera i povezanih iskustava dizajniranih tako da vam omoguće da efikasnije kreirate, komunicirate i sarađujete. Rad sa drugima na dokumentu uskladištenom u OneDrive for Business usluzi ili prevođenje sadržaja Word dokumenta na neki drugi jezik su primeri povezanih iskustava.

Razumemo da možda želite da odaberete koji tipovi povezanih iskustava su dostupni vašim korisnicima prilikom rada u Office aplikacijama. Zato smo za vas obezbedili četiri nove regulatorne postavke:

- Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj
- Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office

Ako ne konfigurišete ove regulatorne postavke, sva povezana iskustva će biti dostupna. To vašim korisnicima pruža sve funkcije i funkcionalnosti dostupne kroz uslugu Microsoft 365 Apps za preduzeće. Mi razumemo da ćete možda morati da isključite neka ili sva od ovih povezanih iskustava da ispunite određene zahteve vaše organizacije.

Ako odlučite da svojim korisnicima ne ponudite neke vrste povezanih iskustava, traka ili komande na meniju za ta povezana iskustva će biti nedostupne, ili će korisnici dobiti poruku o grešci kada pokušaju da koriste ta povezana iskustva. U tom slučaju, nema [obaveznih uslužnih podataka](required-service-data.md) za ta povezana iskustva koja se šalju korporaciji Microsoft.

Vaši korisnici neće moći da odaberu da li žele da isključe ili uključe ova povezana iskustva koja su deo usluge Microsoft 365 Apps za preduzeće ukoliko su prijavljeni u Office pomoću akreditiva organizacije, koji se ponekad nazivaju poslovnim ili školskim nalogom.

### <a name="policy-setting-for-connected-experiences-that-analyze-your-content"></a>Regulatorne postavke za povezana iskustva koja analiziraju vaš sadržaj

Ovo su iskustva koja koriste vaš Office sadržaj da vam daju preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije. Na primer, Dizajner za PowerPoint ili Prevodilac. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

Možete da koristite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office koja analiziraju sadržaj* da kontrolišete da li su ove vrste povezanih iskustava dostupna svim vašim korisnicima. Ako ne konfigurišete ove regulatorne postavke, sva povezana iskustva će biti dostupna vašim korisnicima.

Imajte u vidu da ako onemogućite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office*, povezana iskustva koja analiziraju sadržaj neće biti dostupna vašim korisnicima.

### <a name="policy-setting-for-connected-experiences-that-download-online-content"></a>Regulatorne postavke za povezana iskustva koja preuzimaju sadržaj na mreži

Ovo su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, 3D modele, video zapise i referentne materijale kako biste poboljšali svoje dokumente. Na primer, Office predloške ili PowerPoint QuickStarter. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

Možete da koristite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office koja analiziraju sadržaj* da kontrolišete da li su ove vrste povezanih iskustava dostupne vašim korisnicima. Ako ne konfigurišete ove regulatorne postavke, sva povezana iskustva će biti dostupna vašim korisnicima.

Imajte u vidu da ako onemogućite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office*, povezana iskustva koja preuzimaju mrežni sadržaj neće biti dostupna vašim korisnicima.

### <a name="policy-setting-for-optional-connected-experiences"></a>Regulatorne postavke za opcionalna povezana iskustva

Pored gorenavedenih povezanih iskustava koja su uključena u Microsoft 365 Apps za preduzeće, postoje neka opcionalna povezana iskustva za koje možete da odaberete da li želite da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije. Na primer, LinkedIn funkcije Pomoćnika za biografiju u programu Word ili funkcija 3D mape u programu Excel, koja koristi Bing. Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).

Ova povezana iskustva su različita, zato što nisu pokrivena komercijalnim ugovorom vaše organizacije sa korporacijom Microsoft. Opcionalna povezana iskustva koja Microsoft nudi direktno na raspolaganje vašim korisnicima uređena su dokumentom[Microsoft ugovor o pružanju usluga](https://www.microsoft.com/servicesagreement), a ne [Uslovima korišćenja usluga na mreži](https://www.microsoft.com/licensing/product-licensing/products). U nekim slučajevima, sadržaj ili funkcionalnost nezavisnih proizvođača se obezbeđuju putem ovih opcionih povezanih iskustava, a mogu se primenjivati i drugi uslovi. Za više informacija, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).

Možete da koristite regulatornu postavku *Dozvoli upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office* da kontrolišete da li su ove vrste povezanih iskustava dostupne vašim korisnicima. Ako ne konfigurišete ovu regulatornu postavku, ova povezana iskustva će biti dostupna vašim korisnicima.

> [!NOTE]
> Da biste primenili postavku smernica *Dozvoli korišćenje dodatnih opcionalno povezanih iskustava u sistemu Office* na verzije za količinsko licenciranje sistema Office 2019, Project 2019 ili Visio 2019, morate koristiti Smernice grupe. Ne možete koristiti Office uslugu smernica u oblaku. Ovo se primenjuje kada su Office 2019, Project 2019 ili Visio 2019 konfigurisani za korišćenje kanala ažuriranja PerpetualVL2019.

Čak i ako odaberete da ova opcionalna povezana iskustva učinite dostupnim vašim korisnicima, korisnici će imati opciju da ih isključe kao grupu tako što će otići u [dijalog postavki privatnosti](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Vaši korisnici će imati ovaj izbor samo ako su prijavljeni u Office pomoću akreditiva organizacije (oni se ponekad nazivaju poslovnim ili školskim nalozima), a ne ako su prijavljeni na ličnu adresu elektronske pošte.

Pored toga, neka od ovih opcionalnih povezanih iskustava se takođe smatraju povezanim iskustvima koja analiziraju sadržaj ili preuzimaju sadržaj na mreži. Na primer, Umetanje slika na mreži je opcionalno povezano iskustvo, bazirano na tehnologiji Microsoft Bing, ali se takođe smatra i povezanim iskustvom koje preuzima sadržaj na mreži. Stoga, ako onemogućite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj*, Umetanje slika na mreži neće biti dostupno vašim korisnicima. Ono neće biti dostupno čak i ako ste omogućili regulatornu postavku *Dozvoli upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office*. Više informacija o tome koja povezana iskustva analiziraju sadržaj ili preuzimaju sadržaj na mreži potražite u članku [Povezani iskustva u sistemu Office](connected-experiences.md).

Postoji jedan izuzetak. Regulatorna postavka *Dozvoli upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office* ne kontroliše iskustva koja zahtevaju da povežete svoj LinkedIn nalog sa Microsoft poslovnim ili školskim nalogom. Da biste kontrolisali ovu vrstu iskustava (poput LinkedIn informacija na [kartici profila](https://support.microsoft.com/office/365-e80f931f-5fc4-4a59-ba6e-c1e35a85b501) u usluzi Outlook) pogledajte članak [LinkedIn u Microsoft aplikacijama i uslugama](https://support.microsoft.com/office/dc81cc70-4d64-4755-9f1c-b9536e34d381) i [Integracija veza sa LinkedIn naloga u Azure Active Directory](/azure/active-directory/users-groups-roles/linkedin-integration).

### <a name="policy-setting-for-most-connected-experiences"></a>Regulatorne postavke za najčešće povezana iskustva

Možete da koristite regulatornu postavku *„Dozvoli upotrebu povezanih iskustava u sistemu Office“* da biste kontrolisali da li su najčešće povezana iskustva dostupna vašim korisnicima putem usluge Microsoft 365 Apps za preduzeće. Ako onemogućite regulatornu postavku, sledeći tipovi povezanih iskustava neće biti dostupni korisnicima:

- Iskustva koja analiziraju vaš sadržaj
- Iskustva koja preuzimaju sadržaj na mreži
- Opcionalna povezana iskustva

Pored toga, ako onemogućite ovu regulatornu postavku, većina drugih povezanih iskustava će takođe biti isključena, kao što su koautorstvo i skladištenje datoteka na mreži. Za kompletni spisak drugih povezanih iskustava, pogledajte članak [Povezana iskustva u sistemu Office](connected-experiences.md).

Čak i ako onemogućite ovu regulatornu postavku, pojedine funkcije će ostati na raspolaganju, kao što su sinhronizacija poštanskog sandučeta u programu Outlook, a Timovi i Skype za posao će i dalje raditi. [Osnovne usluge](essential-services.md), kao što je usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office, će ostati na raspolaganju.

## <a name="existing-policy-settings-that-are-replaced-by-new-policy-settings"></a>Postojeće regulatorne postavke koje su zamenile nove regulatorne postavke

Postoje dve postojeće regulatorne postavke koje se više ne primenjuju na Microsoft 365 Apps za preduzeće, počevši od verzije 1904. To su sledeće regulatorne postavke:

- **Slanje ličnih informacija**, koje možete pronaći u okviru Konfiguracija korisnika\\Politika\\Administrativni predlošci\\Microsoft Office 2016\\Privatnost\\Centar za pouzdanost.

- **Opcije sadržaja na mreži**, koje možete pronaći u okviru Konfiguracije korisnika\\Politika\\Administrativni predlošci\\Microsoft Office 2016\\Alatke | Opcije | Opšte | Opcije usluge... \\Sadržaj na mreži.

Počevši od verzije 1904, konfigurisanje ove dve postojeće regulatorne postavke neće imati uticaja na Microsoft 365 Apps za preduzeće. One više nisu primenljive zato što je njihova funkcionalnost zamenjena ovim novim regulatornim postavkama:

- Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj
- Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office
- Dozvolite upotrebu povezanih iskustava u sistemu Office

Ove nove regulatorne postavke vam daju precizniju kontrolu u odnosu na dve postojeće regulatorne postavke. Na primer, ako ste ranije koristili regulatornu postavku *Slanje ličnih informacija*, i PowerPoint QuickStarter i Smart Lookup bi bili isključeni. Ali sada, uz nove regulatorne postavke, ako koristite regulatornu postavku *Dozvoli upotrebu povezanih iskustava u sistemu Office koja analiziraju sadržaj* da biste isključili taj tip povezanih iskustava, isključuje se samo Smart Lookup. PowerPoint QuickStarter će i dalje biti dostupan korisnicima.

Regulatorne postavke se i dalje pojavljuju u alatki za Upravljanje grupnom politikom zato što i dalje važe za količinski licencirane verzije sistema Office 2016 i Office 2019, kao što je Office Professional Plus 2019.

## <a name="what-about-existing-policy-settings-that-control-connected-experiences"></a>Šta je sa postojećim regulatornim postavkama koje kontrolišu povezana iskustva?

Kao što verovatno već znate, postoje neke postojeće regulatorne postavke koje vam omogućavaju da kontrolišete povezana iskustva. Evo nekoliko primera postojećih regulatornih postavki:

- *Opcije za PowerPoint Dizajner*, koje možete pronaći u okviru Konfiguracije korisnika\\Politika\\Administrativni predlošci\\Microsoft Office 2016\\Alatke | Opcije | Opšte | Opcije usluge... \\PowerPoint Dizajner

- *Isključivanje brzog početka*, u okviru Konfiguracija korisnika\\Politika\\Administrativni predlošci\\Microsoft PowerPoint 2016\\Opcije programa PowerPoint\\Opšte

- *Dozvoli funkciju LinkedIn pomoćnika za pisanje biografije*, u okviru Konfiguracija korisnika\\Politiku\\Administrativni predlošci\\Microsoft Word 2016\\Opcije programa Word\\Opšte

 I dalje možete da koristite ove postojeće regulatorne postavke ako želite da isključite pojedinačna povezana iskustva. Ali imajte na umu da ako koristite neku od novih regulatornih postavki, ta nova regulatorna postavka može da isključi povezano iskustvo koje ste uključili pomoću druge regulatorne postavke. Na primer, ako omogućite regulatornu postavku *Dozvoli funkciju LinkedIn pomoćnika za pisanje biografije*, ali onemogućite regulatornu postavku *Dozvoli upotrebu povezanih iskustva u sistemu Office*, LinkedIn pomoćnik za pisanje biografije neće biti dostupan vašim korisnicima.

Uopšteno, ako je jedna regulatorna postavka konfigurisana da uključi određeno povezano iskustvo, dok je istovremeno druga regulatorna postavka konfigurisana tako da isključi taj tip povezanog iskustva, to određeno povezano iskustvo je isključeno za vaše korisnike.

## <a name="privacy-related-changes-to-the-office-ui"></a>Promene u vezi sa privatnošću u korisničkom interfejsu sistema Office

Postoje neke promene u korisničkom interfejsu (UI) usluge Microsoft 365 Apps za preduzeće u vezi sa privatnošću koje vaši korisnici mogu da primete i da vam postave pitanja o njima. Te promene su direktan rezultat nove kontrole privatnosti i regulatornih postavki koje su dostupne počevši od verzije 1904.

### <a name="dialog-about-optional-connected-experiences"></a>Dijaloški okvir o opcionalnim povezanim iskustvima

Ako ste odabrali da korisnicima omogućite [opcionalna povezana iskustva](optional-connected-experiences.md), prvi put kada otvore Office aplikaciju nakon ažuriranja na verziju 1904 ili noviju, pojaviće se informativni dijalog. Ovaj dijaloški okvir obaveštava vaše korisnike da ste im dali izbor da koriste ova opcionalna povezana iskustva i da mogu otići u **Datoteka** > **Nalog**  >  **Privatnost naloga** da bi promenili ovu postavku.

### <a name="privacy-settings-removed-from-the-office-ui"></a>Postavke privatnosti su uklonjene iz korisničkog interfejsa sistema Office

Sledeće postavke se uklanjaju iz **Datoteka** > **Opcije** > **Centar za pouzdanost** > **Postavke centra za pouzdanost...** > **Opcije privatnosti**:

- Dobijte dizajne, informacije, preporuke i usluge tako što ćete dozvoliti sistemu Office da pristupi proizvodima i poboljša ih na osnovu Office sadržaja na uređaju.

- Dozvolite da se Office poveže sa Microsoft uslugama na mreži da bi se pružila funkcionalnost relevantna za vaše korišćenje i željene opcije.

Pored toga, u okviru **Datoteka** > **Opcije** > **Opšte**, uklanja se izbor da omogućite inteligentne Office usluge.

Kao administrator za organizaciju, vi sada kontrolišete ekvivalentne postavke za ovo kroz nove regulatorne postavke opisane ranije.

### <a name="privacy-settings-added-to-the-office-ui"></a>Postavke privatnosti dodate su u korisnički interfejs za Office

Ovo su novi elementi dodati korisničkom interfejsu za Office:

- U okviru **Datoteka** > **Nalog**, korisnici će videti novi izbor za **Privatnost naloga** > **Upravljanje postavkama**. Nalazi se pod **Upravljanje postavkama** gde korisnici mogu da isključe opcionalna povezana iskustva, ako ste im dali tu opciju.

- U okviru **Datoteka** > **Opcije** > **Centar za pouzdanost** > **Postavke centra za pouzdanost...** > **Opcije privatnosti,** postoji opcija da omogućite upotrebu [Prikazivača dijagnostičkih podataka](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855) na uređaju.

 
## <a name="control-privacy-settings-by-editing-the-registry"></a>Kontrolišite postavke privatnosti uređivanjem registratora

Neki administratori žele da promene postavke direktno u registratoru, na primer pomoću skripte, umesto da koriste „Smernice grupe“ ili uslugu Office smernice za oblak. Sledeće informacije možete da koristite da biste konfigurisali postavke privatnosti direktno u registratoru.


|**Postavka smernica** |**Postavka registratora**  |**Vrednosti**  |
|---------|---------|---------|---------|
|Podesite nivo dijagnostičkih podataka klijentskog softvera koje Office šalje korporaciji Microsoft  | SendTelemetry |1 =Obavezno <br/> 2=Opcionalno <br/> 3=Nijedno|
|Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office  | UserContentDisabled | 1 =Omogućeno <br/> 2 =Onemogućeno|
|Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj  | DownloadContentDisabled | 1 =Omogućeno <br/> 2 =Onemogućeno|
|Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office   | ControllerConnectedServicesEnabled  |1 =Omogućeno <br/> 2 =Onemogućeno|
|Dozvolite upotrebu povezanih iskustava u sistemu Office | DisconnectedState  | 1 =Omogućeno <br/> 2 =Onemogućeno|

Da biste napravili. reg datoteku za postavke privatnosti, otvorite „Beležnicu“ i dodajte sledeće redove. Prilagodite vrednosti tako da odgovaraju vašim potrebama, a zatim sačuvajte datoteku. Uverite se da ime datoteke ima oznaku tipa. reg

```console
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\16.0\common\privacy]
"disconnectedstate"=dword:00000001
"usercontentdisabled"=dword:00000001
"downloadcontentdisabled"=dword:00000001
"controllerconnectedservicesenabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\common\clienttelemetry]
"sendtelemetry"=dword:00000002
```

Na primer, možete da koristite ovu. reg datoteku pomoću komande regedit.exe u skripti da biste konfigurisali postavke privatnosti za korisnika.