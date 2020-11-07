---
title: Opcionalni dijagnostički podaci za Office
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
description: Pruža informacije Office administratorima o opcionalno dijagnostičkim podacima u sistemu Office, uključujući neke primere događaja.
hideEdit: true
ms.openlocfilehash: 7dc10c50baed0306e3e7fc6dd70e0d798a72d0bc
ms.sourcegitcommit: e64b8f2b7f92a3972d8dc83f47d84648fbe17370
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/06/2020
ms.locfileid: "48931268"
---
# <a name="optional-diagnostic-data-for-office"></a>Opcionalni dijagnostički podaci za Office

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Ti podaci ne sadrže korisničko ime ili adresu elektronske pošte, sadržaj korisničkih datoteka ili informacije o aplikacijama nevezanim za Office.

Ovi dijagnostički podaci se prikupljaju i šalju korporaciji Microsoft u vezi sa Office klijentskim softverom pokrenutim na uređaju korisnika. Neki dijagnostički podaci su obavezni, a neki su opcionalni. Možete da izaberete da li ćete nam slati obavezne ili opcionalne dijagnostičke podatke pomoću kontrole privatnosti, kao što su postavke smernica organizacije. Možete da vidite dijagnostičke podatke koji nam se šalju koristeći prikaz dijagnostičkih podataka.

> [!NOTE]
> Ako koristite verziju sistema Office 2019 ili Office 2016 koja vama ili vašem administratoru ne daje mogućnost izbora da li želite da nam šaljete obavezne ili opcionalne dijagnostičke podatke, onda se šalju samo obavezni dijagnostički podaci. Na primer, ako koristite Office Professional Plus 2019 ili Office Standard 2016, koji ne pružaju tu mogućnost izbora, onda se šalju samo obavezni dijagnostički podaci. Office 2013 ne šalje obavezne ili opcionalne dijagnostičke podatke. Za više informacija o tome koja verzija sistema Office pruža ovu mogućnost izbora, pogledajte članak [Kontrole privatnosti dostupne za Office proizvode](products-versions-privacy-controls.md).

***Opcionalni dijagnostički podaci** _ su dodatni podaci koji nam pomažu da poboljšamo proizvod i pružaju dodatne informacije koje nam pomažu u otkrivanju i otklanjaju problema.

Ako odaberete da nam pošaljete opcionalne dijagnostičke podatke, oni se prikupljaju uz obavezne dijagnostičke podatke. Osim toga, možda će biti poslate dijagnostičke datoteke evidencije za Office, koje sadrže informacije koje su vrlo slične pojedinim dijagnostičkim podacima. Za više informacija o tim datotekama evidencije pogledajte članak [Pregled dijagnostičkih datoteka evidencije za Office](https://support.microsoft.com/office/fba86aac-70dc-4858-ae1f-ec2034346cdf).

Primeri opcionalnih dijagnostičkih podataka koje prikupljamo sadrže podatke vezane za slike koje korisnici umeću u Word dokumente da bismo obezbedili bolje opcije slike, kao i podatke o vremenu potrebnom da se PowerPoint slajd pojavi na ekranu da bismo poboljšali iskustvo ako je sporo.

Za više informacija o dijagnostičkim podacima pogledajte sledeće članke:

- [Obavezni dijagnostički podaci za Office](required-diagnostic-data.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Ako ste administrator organizacije, možda će vas zanimati i sledeći članci:

- [Pregled kontrola privatnosti za Microsoft 365 Apps za velika preduzeća](overview-privacy-controls.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za velika preduzeća](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a>Kategorije opcionalnih dijagnostičkih podataka

Opcionalno dijagnostički podaci su podeljeni u sledeće kategorije:

- Softver za podešavanje i zalihe
- Upotreba proizvoda i usluga
- Performanse proizvoda i usluga
- Povezivanje uređaja i konfiguracija

Ove kategorije su prikazane u prikazivaču dijagnostičkih podataka i iste su i za obavezne dijagnostičke podatke.

Sledeći odeljci sadrže opise i primere događaja za svaku kategoriju.

## <a name="software-setup-and-inventory-events"></a>Događaji softvera za podešavanje i zaliha

Ova kategorija uključuje događaje koji obuhvataju sledeće oblasti:

- Instalirani proizvod, verziju i status instalacije
- Programske dodatke i njihove postavke
- Dokument, funkciju i grešku dodatka koji mogu da ugroze bezbednost, uključujući spremnost ažuriranja proizvoda.

Sledeća tabela sadrži primere događaja za ovu kategoriju, kao i njihove opise.

| _ *Ime događaja**   | **Opis događaja**  |
| ---- | ---- |
| Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId | Ovaj događaj ukazuje na to da li Word uspešno ažurira traku na Word korisničkom interfejsu kada korisnik promeni svoj identitet. Koristimo ga za otkrivanje neispravnog podešavanja i drugih problema koji utiču na Office korisnički interfejs. |
| Office.Extensibility.AppCommands.AppCmdInstall   | Ovaj događaj pruža informacije o Office programskom dodatku koji je korisnik instalirao, uključujući ID aplikacije, verziju operativnog sistema, uspeh i trajanje instalacije.  |

## <a name="product-and-service-usage-events"></a>Događaji upotrebe proizvoda i usluga

Ova kategorija uključuje događaje koji obuhvataju sledeće oblasti:

- Uspešnost funkcionalnosti aplikacije. Ograničena na otvaranje i zatvaranje aplikacije i dokumenata, uređivanje i deljenje (saradnju) datoteka.
- Utvrđivanje da li su se određene funkcije događaja odigrale, kao što su pokretanje ili zaustavljanje i da li funkcija radi.
- Funkcije pristupačnosti u sistemu Office

Sledeća tabela sadrži primere događaja za ovu kategoriju, kao i njihove opise.

| **Ime događaja**   | **Opis događaja**  |
| ------ | ------- |
| Office.Word.Commanding.Highlight  | Ovaj događaj ukazuje na to da je Word izvršio komandu za isticanje teksta. Koristimo ga za otkrivanje grešaka u komandi za isticanje teksta.  |
| Office.Translator.AddInLoaded   | Signal koji ukazuje na to da je prevodilačka funkcija uspešno učitana i prikazana.  |
| Office.Graphics.GVizInsertShape |Prati korišćenje funkcije „Umetni oblik" i izveštava o detaljima tipova umetnutih oblika i njihovim izvorima.| 
| Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule   | Ovaj događaj određuje da li postoje odeljci prisutni u dokumentu kada korisnik umeće zumiranje rezimea i da li bira da izbriše postojeće odeljke. |
| Office.Security.SecureReaderHost.ProtectedViewValidation | Prati kada i zašto je datoteka otvorena u zaštićenom prikazu. Koristi se za dijagnostikovanje uslova u kojima zaštićeni prikaz nije ispravno pokrenut da bi se obezbedio pravilan rad funkcije. |

## <a name="product-and-service-performance-events"></a>Događaji performansi proizvoda i usluga

Ova kategorija uključuje događaje koji obuhvataju sledeće oblasti:

- Neočekivani izlazi (padovi) iz aplikacije i njeno stanje u trenutku kada se to dogodi.
- Loše vreme odziva ili performansi u scenarijima kao što su pokretanje aplikacije ili otvaranje datoteke.
- Greške u funkcionalnosti funkcije ili korisničkog iskustva.

Sledeća tabela sadrži primere događaja za ovu kategoriju, kao i njihove opise.

| **Ime događaja**    | **Opis događaja**   |
| --------------- | -------------- |
| Office.Word.Word.CoreSaveTime100ns     | Ovaj događaj evidentira performanse aktivnosti čuvanja dokumenta u programu Word. Koristimo ga za otkrivanje grešaka i problema sa performansama u programu Word prilikom čuvanja dokumenta.|
| Office.Identity.SignInForWamAccountAad  | Ovaj događaj se šalje kada se korisnik prijavi na Azure Active Directory nalog sa bibliotekom menadžera naloga na mreži (WAM). Ovaj događaj šalje metapodatke kao što su ime i verzija aplikacije i kôd greške ako je događaj neuspešan. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Ovaj događaj prikuplja koliko dugo vremena je potrebno za prikazivanje prve sličice mastera slajda u programu PowerPoint.  |
| Office.Extensibility.Diagnostics   | Ovaj događaj pruža osnovne dijagnostičke informacije o Office programskim dodacima, kao što su izveštaji o padu da bi se otklonile greške.|

## <a name="device-connectivity-and-configuration-events"></a>Događaji povezivanja uređaja i konfiguracije

Ova kategorija uključuje događaje koji obuhvataju sledeće oblasti:

- Stanje mrežne veze i podešavanje uređaja, kao što je memorija.

Sledeća tabela sadrži primere događaja za ovu kategoriju, kao i njihove opise.

| **Ime događaja**                    | **Opis događaja**                                                                                                                                                     |
| ------ | ----- |
| Office.Graphics.ArtViewValidate | Ovaj događaj evidentira rezultate provere valjanosti grafičkih prikaza koji podržavaju grafički korisnički interfejs. Koristimo ga za prikupljanje podataka o korišćenju i greške grafičkog prikazivanja. |
| Office.Graphics.ARCExceptionScope | Ovaj događaj prati greške prikazivanja nastale u mehanizmu za prikazivanje. |
| Office.Extensibility.ODPLatency   | Ovaj događaj pruža informacije o korisničkoj mrežnoj vezi i njenoj brzini.     |
