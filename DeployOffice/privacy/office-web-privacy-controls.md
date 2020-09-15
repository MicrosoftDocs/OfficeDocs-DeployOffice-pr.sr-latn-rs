---
title: Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti kod Office aplikacija za veb
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Pruža informacije administratorima sistema Office o tome kako da upravljaju postavkama privatnosti za Office aplikacije za veb.
hideEdit: true
ms.openlocfilehash: b5131d5ffc09b28a3b5731a417fcd6d383fb7d01
ms.sourcegitcommit: da41d41b443c8392c96e64a4d2fc674957abddf5
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/11/2020
ms.locfileid: "47431981"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a>Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti kod Office aplikacija za veb

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Kao administrator organizacije, možete da kontrolišete da li korisnici imaju mogućnost da koriste opciona povezana iskustva prilikom upotrebe Office aplikacija za veb, kao što su Word za veb ili PowerPoint za veb. Ova mogućnost je dostupna korisnicima samo ako su prijavljeni pomoću poslovnog ili školskog naloga tokom korišćenja Office aplikacija za veb. Da biste kontrolisali da li korisnici imaju mogućnost da koriste opciona povezana iskustva, koristite regulatornu postavku *„Dozvoli upotrebu dodatnih opcionih povezanih iskustava u sistemu Office“*.

## <a name="overview-of-optional-connected-experiences"></a>Pregled opcionih povezanih iskustava

Opciona povezana iskustva su usluge u oblaku koje su dostupne korisnicima kada koriste Office. Primeri opcionih povezanih iskustava uključuju kreiranje grafikona mape u programu Excel ili umetanje slike sa interneta u Word dokument, pri čemu se obe radnje oslanjaju na usluge koje pruža Microsoft Bing. Upotreba ovih usluga u oblaku je opciona. 

Opciona povezana iskustva nisu pokrivena komercijalnim ugovorom vaše organizacije sa korporacijom Microsoft. Umesto toga, opciona povezana iskustva koja Microsoft nudi direktno na raspolaganje vašim korisnicima uređena su dokumentom [„Microsoft ugovor o pružanju usluga“](https://www.microsoft.com/servicesagreement). U nekim slučajevima, sadržaj ili funkcionalnost nezavisnih proizvođača se obezbeđuju putem ovih opcionih povezanih iskustava, a mogu se primenjivati i drugi uslovi.

Neka opciona povezana iskustva možda neće biti dostupna u Office aplikacijama za veb, ali će biti dostupna prilikom korišćenja drugih verzija sistema Office, kao što je verzija za računar sa operativnim sistemom Windows.

Više informacija potražite u članku [„Pregled opcionih povezanih iskustava u sistemu Office“](optional-connected-experiences.md).

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a>Konfigurisanje regulatorne postavke pomoću Office usluge smernica u oblaku

Možete da koristite regulatornu postavku *„Dozvoli upotrebu dodatnih opcionih povezanih iskustava u sistemu Office“* da biste kontrolisali da li korisnici imaju mogućnost da koriste opciona povezana iskustva. Da biste konfigurisali ovu regulatornu postavku za Office aplikacije za veb, morate da koristite [Office uslugu smernica u oblaku](../overview-office-cloud-policy-service.md).  

Ako ne konfigurišete ovu regulatornu postavku, mogućnost korišćenja opcionih povezanih iskustava će biti dostupna korisnicima. Ako je onemogućite, korisnici neće moći da koriste opciona povezana iskustva.

Kod Office aplikacija za veb, regulatorna postavka se primenjuje kada korisnici rade na Office dokumentima koji se čuvaju u Microsoft skladištu na vebu, kao što su OneDrive for Business ili SharePoint Online.

Budući da se koristi Office usluga smernica u oblaku, ova regulatorna postavka se primenjuje i kada korisnici koriste Office na uređajima sa operativnim sistemom Windows, Mac, iOS ili Android. Ova regulatorna postavka se ne može konfigurisati samo za to kada korisnici koriste Office aplikacije za veb. Međutim, možete da kreirate konfiguraciju smernica koja uključuje ovu regulatornu postavku i da podesite da se data konfiguracija smernica primenjuje samo na korisnike koji pristupaju dokumentima anonimno pomoću Office aplikacija za veb.

Ako odlučite da korisnicima omogućite opciona povezana iskustva, oni će primiti obaveštenje o privatnosti kada prvi put budu koristili Office aplikaciju za veb. Ovo obaveštenje javlja korisnicima da im je data mogućnost korišćenja ovih opcionih povezanih iskustava. Ono ih obaveštava i o tome da su opciona povezana iskustva obezbeđena u skladu sa Microsoft ugovorom o pružanju usluga. Budući da ovo obaveštenje sadrži važne informacije za vaše korisnike, ono se mora prikazati i ne sme se isključiti, sakriti ili prihvatiti u ime korisnika.

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a>Korisnici mogu da odaberu da isključe opciona povezana iskustva

Ako odlučite da korisnicima omogućite opciona povezana iskustva, oni mogu da odu na [postavke privatnosti naloga](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online) i da odaberu da sebi isključe pristup opcionim povezanim iskustvima. Ova mogućnost je dostupna u postavkama privatnosti naloga samo ako su korisnici prijavljeni pomoću poslovnog ili školskog naloga. Ne postoji način da vi, kao administrator, sprečite pojedinačne korisnike u organizaciji da sebi isključe pristup opcionim povezanim iskustvima u postavkama privatnosti naloga ukoliko ste im dali mogućnost da ih koriste.

## <a name="related-articles"></a>Povezani članci

- [Pregled kontrola privatnosti za Microsoft 365 Apps za velika preduzeća](overview-privacy-controls.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za velika preduzeća](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)