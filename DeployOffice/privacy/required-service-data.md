---
title: Neophodni podaci o usluzi za Office
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
description: Pruža administratorima sistema Office pregled neophodnih podataka o usluzi koji se prikupljaju o povezanim iskustvima u sistemu Office.
hideEdit: true
ms.openlocfilehash: 9a276e00f5c852ffda00844c5e1aaa9187f581c3
ms.sourcegitcommit: 3f5de6281b8e92c6c41a800f4374211188460320
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34701021"
---
# <a name="required-service-data-for-office"></a>Neophodni podaci o usluzi za Office 

> [!IMPORTANT]
> Informacije u ovom članku se odnose na verziju 1904 ili noviju, sledećih Office klijentskih softvera instaliranih na računaru sa operativnim sistemom Windows:
> - Office 365 ProPlus i Office 365 Business
> - Office 365 Personal, Office 365 Home ili druge verzije sistema Office koje su deo pretplate na Office 365.
> - Project i Visio koji se dobijaju uz neke planove pretplata, kao što je plan za Project Online Professional ili Visio Online Plan 2.

Office se sastoji od aplikacija klijentskog softvera i povezanih iskustava dizajniranih tako da vam omogućavaju da efikasnije kreirate, komunicirate i sarađujete. Rad sa drugima na dokumentu uskladištenom u usluzi OneDrive for Business ili prevođenje sadržaja Word dokumenta na neki drugi jezik su primeri povezanih iskustava.

Neophodni podaci o usluzi imaju suštinski značaj jer nam omogućavaju da isporučimo ova povezana iskustva zasnovana na oblaku i učinimo ih bezbednim i funkcionalnim za naše klijente, kao što se očekuje. Neophodne podatke o usluzi čine tri tipa informacija.

- **Sadržaj klijenta**, što je sadržaj koji kreirate pomoću sistema Office, kao što je tekst koji ste otkucali u Word dokumentu i koristi se zajedno sa povezanim iskustvom.
- **Funkcionalni podaci**, koji uključuju informacije potrebne da povezano iskustvo izvrši svoj zadatak, kao što su informacije o konfiguraciji aplikacije.
- **Uslužni dijagnostički podaci**, odnosno podaci potrebni da biste zaštitili uslugu, redovno je ažurirali i obezbedili da funkcioniše kao što je očekivano. Zbog toga što su ti podaci strogo vezani za povezano iskustvo, oni su odvojeni od nivoa obaveznih ili opcionalnih dijagnostičkih podataka.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Primer neophodnih podataka o usluzi za povezano iskustvo

Da biste lakše razumeli neophodne podatke o usluzi, sledi primer scenarija za Dizajner za PowerPoint, povezano iskustvo koje možete da koristite prilikom kreiranja slajdova za prezentaciju. PowerPoint Designer vam pomaže da poboljšate slajdove tako što automatski generiše dizajnerske ideje koje možete da koristite. Dok stavljate sadržaj na slajd, Designer radi u pozadini da bi taj sadržaj preneo na profesionalno dizajnirane rasporede.

Neophodni podaci o usluzi koji se šalju korporaciji Microsoft kako bismo omogućili ovo povezano iskustvo mogu da obuhvate sledeće:

- *Sadržaj klijenta*, kao što su tekst ili slike koje ste dodali na slajd.
- *Funkcionalne podatke*, kao što je slajd na kome radite i njegov raspored.
- *Uslužne dijagnostičke podatke*, kao što su događaji koji nam govore da li je ideja za dizajn ispravno primenjena na vašem slajdu i da li uslužni pozivi rade ispravno.

## <a name="view-and-manage-required-service-data"></a>Prikaz neophodnih podataka o usluzi i upravljanje njima

Možete da vidite dijagnostičke podatke koristeći Prikazivač dijagnostičkih podataka. Za više informacija pogledajte članak [Primeri događaja za uslužne dijagnostičke podatke](#examples-of-events-for-service-diagnostic-data).

Pružamo vam mogućnost da izaberete tipove povezanih iskustava koje želite da koristite u sistemu Office, što određuje koji se neophodni podaci o usluzi šalju nama. Na primer, Dizajner za PowerPoint predstavlja jedno od nekoliko povezanih iskustava koja analiziraju vaš sadržaj. Ako odlučite da isključite povezana iskustva koja analiziraju sadržaj, nama se neće slati nikakvi neophodni podaci o usluzi za funkciju Dizajner za PowerPoint jer nam ona neće biti dostupna za korišćenje.

Neophodni podaci o usluzi prikupljaju se i šalju korporaciji Microsoft i za osnovne usluge sistema Office, kao što je usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office. Ovi podaci o osnovnim uslugama se šalju bez obzira na sva druga podešavanja vezana za privatnost koja ste konfigurisali.

Za više informacija pogledajte sledeće članke:

- [Povezana iskustva u sistemu Office](connected-experiences.md)
- [Osnovne usluge za Office](essential-services.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Ako ste administrator organizacije, možda će vas zanimati i sledeće:

- [Pregled kontrola privatnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti u programu Office 365 ProPlus](manage-privacy-controls.md)

## <a name="examples-of-events-for-service-diagnostic-data"></a>Primeri događaja za uslužne dijagnostičke podatke

Uslužni dijagnostički podaci se pojavljuju u Prikazivaču dijagnostičkih podataka i podeljeni su u iste kategorije kao i obavezni i opcionalni dijagnostički podaci. Na primer, *Upotreba proizvoda i usluge* ili *Performanse proizvoda i usluge.*

Ovi događaji uslužnih dijagnostičkih podataka nam pružaju neophodne informacije o tome da li povezana iskustva funkcionišu onako kako klijent očekuje. Na primer, da li je usluga koju koristi povezano iskustvo uspešno pokrenuta i da li je dostupna kada je potrebno, da li je došlo do grešaka ili drugih neočekivanih problema (padova) tokom interakcije sa uslugom, kao i informacije o njenom odzivu i performansi.

Sledeća tabela pruža neke primere događaja za uslužne dijagnostičke podatke.

| **Ime**      | **Opis**    |
| ---------- | --------------------- |
| Office.Excel.Coauth.SaveXrr     | Događaj koji se pokreće u programu Excel prilikom korišćenja usluge saradnje koja izveštava o detaljima pojedinačnih revizija koji su zapisani u datoteci za evidenciju revizija. Ovo omogućava nadgledanje kašnjenja i ukazivanje na greške u programu Excel koje se odnose na saradnju.  |
| Office.Excel.Coauth.CloseWorkbook  | Događaj koji se pokreće u programu Excel prilikom korišćenja usluge saradnje koja izveštava kada je radna sveska zatvorena. Ovo je potrebno za određivanje svih grešaka u ponovnom učitavanju i automatskom osvežavanju. To pruža merenje uspeha za aktivnosti usluge saradnje.   |
| Office.Security.OCX.NonTrustedEncounter    | Događaj koji se pokreće u Office aplikacijama (uključujući Word, Excel, Outlook, PowerPoint i Visio) kada korisnik otvori nepouzdani dokument sa ActiveX kontrolom. Koristi se za potpuniju procenu upotrebe ActiveX kontrola koje su ugrađene u Office dokumenta i za smanjenje režima bezbednosti kao odgovor na bezbednosne incidente.  |
| Office.Security.UrlReputation.GetUrlReputation | Događaj koji se pokreće u Office aplikacijama (uključujući Word, Excel, PowerPoint, Visio i Publisher) i prati uspešnost ili neuspešnost pozivanja funkcije Bezbedne veze. Koristi se da bi se obezbedio pravilan rad usluge Bezbedne veze i da bi se dijagnostikovao bilo koji problem.  |
| Office.Voice.VoiceManager.StreamingAudio   | Događaj koji se pokreće u Office aplikacijama (uključujući Word, Outlook i PowerPoint) i pruža informacije o ispravnosti audio protoka u usluzi govora. Sadrži informacije o veličini audio protoka i greškama do kojih je možda došlo. Ove informacije se koriste za nadgledanje ispravnosti usluge, kao i za dijagnostikovanje problema koji su možda klijenti prijavili. |
