---
title: Pregled kontrola privatnosti za Microsoft 365 Apps za preduzeće
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: conceptual
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Пружа Office администраторима преглед контрола приватности за Microsoft 365 Apps for enterprise (претходно Office 365 ProPlus), укључујући дијагностичке податке и повезане утиске при раду.
hideEdit: true
ms.openlocfilehash: d984be8ef09c8a46c4588ae643c4d6ebad1b2533
ms.sourcegitcommit: 2c4bf05e77415559080766cc7d7f241e9f968108
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2021
ms.locfileid: "51181709"
---
# <a name="overview-of-privacy-controls-for-microsoft-365-apps-for-enterprise"></a>Pregled kontrola privatnosti za Microsoft 365 Apps za preduzeće

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Microsoft je posvećen tome da vam pruži informacije i kontrole koje su vam potrebne da biste odabrali način prikupljanja i upotrebe vaših podataka kada koristite Microsoft 365 aplikacije za velika preduzeća (ranije poznato kao Office 365 ProPlus).

Почевши од верзије 1904 услуге Microsoft 365 Apps for enterprise, пружаћемо вам нове, ажуриране и унапређене контроле приватности за следеће области:
- ***Дијагностички подаци*** који се прикупљају и шаљу корпорацији Microsoft о Office клијентском софтверу који се користи на уређају корисника у вашој организацији.
- ***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.

U sklopu ovih promena, postoje elementi novog i ažuriranog korisničkog interfejsa (UI) i postavki pravila.

## <a name="diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft"></a>Dijagnostički podaci koji se šalju iz usluge Microsoft 365 Apps za preduzeće korporaciji Microsoft

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Ti podaci ne sadrže korisničko ime ili adresu elektronske pošte, sadržaj korisničkih datoteka ili informacije o aplikacijama nevezanim za Office.

Ovi dijagnostički podaci se prikupljaju i šalju korporaciji Microsoft u vezi sa Office klijentskim softverom pokrenutim na uređaju korisnika u vašoj organizaciji.

Постоје три нивоа дијагностичких података за Microsoft 365 Apps for enterprise клијентски софтвер између којих можете да бирате:

- **Обавезни** Минимални подаци неопходни да би Office остао безбедан, ажуран и да би функционисао као што је очекивано на уређају на ком је инсталиран.

- **Опционални** Додатни подаци који нам помажу да унапредимо производ и пружају побољшане информације помоћу којих откривамо, дијагностикујемо и решавамо проблеме.

- **Никакви** Не прикупљају се и не шаљу нам се никакви дијагностички подаци о Office клијентском софтверу покренутом на уређају корисника. Међутим, ова опција знатно ограничава нашу могућност откривања, дијагнозе и решавања проблема на које ваши корисници могу наићи док користе Office.

Обавезни дијагностички подаци могу да обухвате, на пример, информације о верзији система Office инсталираној на уређају или информације које указују на то да Office апликације отказују кад покушате да отворите документе. Опционални дијагностички подаци могу да обухвате информације о времену потребном да се сачува документ, што може да указује на проблем специфичан за чување на вашем уређају.

Ako odaberete da nam pošaljete opcionalne dijagnostičke podatke, oni se prikupljaju uz obavezne dijagnostičke podatke.

Као администратор своје организације, моћи ћете да користите поставку смерница да бисте одабрали који нам ниво дијагностичких података шаљете. Опционални дијагностички подаци слаће се корпорацији Microsoft осим ако не промените поставку. Слање опционалних дијагностичких података омогућава Office инжењерском тиму у корпорацији Microsoft да боље открива, врши дијагнозу и избегне проблеме како би се смањио њихов утицај на вашу организацију.

Ваши корисници неће моћи да промене ниво дијагностичких података за своје уређаје ако су пријављени у Office са акредитивима организације, што се некад назива и пословни или школски налог.

Ти дијагностички подаци не обухватају имена корисника, њихове адресе е-поште или садржај њихових Office датотека. Наш систем прави јединствени ID који повезује са дијагностичким подацима вашег корисника. Кад добијемо дијагностичке податке који приказују да је нека од наших апликација отказала 100 пута, тај јединствени ID нам омогућава да утврдимо да ли је до отказа дошло код једног корисника 100 пута или је код 100 различитих корисника по једном дошло до отказивања. Тај јединствени ID не користимо да бисмо идентификовали одређеног корисника.

Да бисте видели који се дијагностички подаци шаљу корпорацији Microsoft, можете да користите Приказивач дијагностичких података који можете да преузмете и инсталирате из услуге Microsoft Store.

Više informacija potražite u sledećim člancima:

- [Obavezni dijagnostički podaci za Office](required-diagnostic-data.md)
- [Opcionalni dijagnostički podaci za Office](optional-diagnostic-data.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)
- [Korišćenje Prikazivača dijagnostičkih podataka uz Office](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="connected-experiences-for-microsoft-365-apps-for-enterprise"></a>Повезана искуства за Microsoft 365 Apps for enterprise

Microsoft 365 Apps for enterprise се састоји од апликација клијентског софтвера и повезаних искустава осмишљених тако да вам омогућавају ефикасније креирање, комуникацију и сарадњу. Rad sa drugima na dokumentu uskladištenom u OneDrive for Business usluzi ili prevođenje sadržaja Word dokumenta na neki drugi jezik su primeri povezanih iskustava.

Разумемо да ћете можда желети да одаберете типове повезаних утисака при раду који су доступни вашим корисницима док раде у Office апликацијама. Као администратор своје организације, имаћете поставке смерница које вам омогућавају да одаберете да ли ћете својим корисницима омогућити следеће типове повезаних утисака при раду:

- **Утисци при раду који анализирају садржај** Утисци при раду који користе Office садржај да би вам обезбедили препоруке дизајна, предлоге уређивања, увиде у податке и сличне функције. На пример, PowerPoint дизајнер или Преводилац.

- **Утисци при раду који преузимају садржај на мрежи** Утисци при раду који вам омогућавају претраживање и преузимање садржаја на мрежи, укључујући предлошке, слике, 3D моделе, видео записе и референтне материјале за побољшавање докумената. Na primer, Office predlošci ili PowerPoint QuickStarter.

На пример, можете одабрати да својим корисницима обезбедите повезане утиске при раду који преузимају садржај на мрежи, али не и повезане утиске при раду који анализирају садржај. Ако не конфигуришете те поставке смерница, корисницима ће бити доступни сви ти повезани утисци при раду.

Поред тога, доступна вам је и поставка смерница која вам омогућава да искључите све те повезане утиске при раду и која ће такође искључити друге повезане утиске при раду као што су коауторство докумената и складиштење датотека на мрежи. Међутим, чак и ако употребите ту поставку смерница да искључите све те повезане утиске при раду, одређене функције система Office остаће доступне, као што су синхронизовање поштанског сандучета у програму Outlook, коришћење услуга Teams или Skype за посао, као и основне услуге описане у наставку.

Ако одаберете да корисницима не обезбедите одређене типове повезаних утисака при раду, команда на траци или у менију за те повезане утиске при раду биће засивљена или ће корисници добијати поруку о грешци кад покушају да користе те повезане утиске при раду.

Ваши корисници неће моћи да одаберу да ли ће укључити или искључити те повезане утиске при раду ако су пријављени у Office са акредитивима организације, што се некад назива и пословни или школски налог.

Više informacija potražite u sledećim člancima:

- [Povezana iskustva u sistemu Office](connected-experiences.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)

## <a name="optional-connected-experiences-for-microsoft-365-apps-for-enterprise"></a>Опционална повезана искуства за Microsoft 365 Apps for enterprise

Поред повезаних утисака при раду поменутих у претходном тексту који су укључени уз Microsoft 365 Apps for enterprise, постоје опционални повезани утисци при раду које можете одабрати да бисте омогућили корисницима приступ путем налога организације. Na primer, LinkedIn funkcije Pomoćnika za biografiju u programu Word ili funkcija 3D mape u programu Excel, koja koristi Bing.

То су опционални повезани утисци при раду који нису покривени комерцијалним уговором ваше организације са корпорацијом Microsoft, већ за њих важе засебни услови и одредбе. За опционалне повезане утиске при раду које Microsoft нуди директно вашим корисницима важи [Microsoft уговор о пружању услуга](https://www.microsoft.com/servicesagreement) уместо [Услова за услуге на мрежи](https://www.microsoft.com/licensing/product-licensing/products).

Пошто за опционалне повезане утиске при раду важе засебни услови и одредбе, њима управљате одвојено од горепоменутих повезаних утисака при раду. Као администратор своје организације, моћи ћете да користите поставку смерница да бисте одабрали да ли ћете те опционалне повезане утиске при раду, као групу, учинити доступним за своје кориснике. Ако не конфигуришете ту поставку смерница, ти опционални утисци при раду биће доступни корисницима.

Чак и ако одаберете да те опционална повезана искуства учините доступним за своје кориснике, корисници ће имати опцију да их искључе као групу тако што ће отићи у [дијалог са поставкама приватности](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Ваши корисници ће имати овај избор само ако су у Office пријављени са акредитивима организације (који се понекад називају пословни или школски налог), а не ако су пријављени са личном адресом е-поште.

Više informacija potražite u sledećim člancima:

- [Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md)
- [Korišćenje postavki smernica za upravljanje kontrolama privatnosti za Microsoft 365 Apps za preduzeće](manage-privacy-controls.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)
- [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje](ios-privacy-preferences.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office na Android uređajima](android-privacy-controls.md)
- [Korišćenje regulatornih postavki za upravljanje kontrolama privatnosti za Office aplikacije za veb](office-web-privacy-controls.md)

## <a name="required-service-data-for-connected-experiences"></a>Neophodni podaci o usluzi za povezane utiske pri radu

Dok koristite povezano iskustvo, podaci se šalju i Microsoft ih obrađuje kako bi se obezbedilo povezano iskustvo. Ovi podaci su od suštinskog značaja jer nam te informacije omogućavaju da isporučimo povezana iskustva zasnovana na tehnologiji oblaka. Ove podatke smatramo obaveznim podacima o usluzi.

Obavezni podaci o usluzi mogu da obuhvataju informacije koje se odnose na radnju povezanog iskustva koja je neophodna da bi osnovna usluga bila bezbedna, ažurna i da bi funkcionisala kao što je očekivano. Ako odlučite da koristite povezano iskustvo koje analizira sadržaj, na primer, funkciju „Prevođenje“ u programu Word, tekst koji otkucate i izaberete za prevođenje u dokumentu se takođe šalje i obrađuje kako bi se obezbedilo povezano iskustvo. Obavezni podaci o usluzi mogu da obuhvataju i informacije koje su potrebne kako bi povezano iskustvo obavilo svoj zadatak, kao što su informacije o konfiguraciji aplikacije Office.

Više informacija potražite u članku [Neophodni podaci o usluzi za Office](required-service-data.md).

## <a name="essential-services-for-microsoft-365-apps-for-enterprise"></a>Osnovne usluge za Microsoft 365 Apps za preduzeće

Postoji i skup usluga koje su od suštinske važnosti za to kako funkcije usluge Microsoft 365 Apps za preduzeće rade i one se ne mogu onemogućiti. Na primer, usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Microsoft 365 Apps za preduzeće. Обавезни подаци о услузи о овим услугама прикупљају се и шаљу корпорацији Microsoft без обзира на друге поставке услуга које сте конфигурисали.

Више информација потражите у чланку [Основне услуге за Office](essential-services.md).

## <a name="related-articles"></a>Povezani članci
- [Приватност у корпорацији Microsoft](https://privacy.microsoft.com/)
- [Windows приватност](/windows/privacy/)