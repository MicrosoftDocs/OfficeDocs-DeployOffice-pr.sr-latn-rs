---
title: Korišćenje željenih postavki za upravljanje kontrolama privatnosti u sistemu Office za Mac
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: Administratorima sistema Office pruža informacije o tome kako da upravljaju kontrolama privatnosti u sistemu Office za Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246318"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>Korišćenje željenih postavki za upravljanje kontrolama privatnosti u sistemu Office za Mac

Počevši od verzije 16.28 sistema Office za Mac, postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:

- ***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi

- ***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.

Pored toga, postoji nova željena postavka koja se odnosi na dijalog **Obaveštenje o zahtevanim podacima** za Microsoft AutoUpdate (MAU).

Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).

> [!NOTE]
> Za više informacija o sličnim postavkama za Office na računaru koji koristi Windows pogledajte članak [Koristite regulatorne postavke za upravljanje kontrolama privatnosti za Office 365 ProPlus](manage-privacy-controls.md)

## <a name="setting-preferences"></a>Postavljanje željenih postavki

Ove nove postavke željenih opcija su CFPreferences API kompatibilne i mogu se postaviti pomoću `defaults` komande u Terminalu i nametnuti putem Configuration Profile ili Mobile Device Management (MDM) servera. Kada su željene postavke nametnute, korisnik ne može da promeni vrednosti, a sve kontrole unutar aplikacije će biti onemogućene.

## <a name="preference-setting-for-diagnostic-data"></a>Postavka željenih opcija za dijagnostičke podatke

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Za više informacija pogledajte [Dijagnostički podaci koji se šalju iz Office 365 ProPlus korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.office` |
|**Taster**  | `DiagnosticDataTypePreference`  |
|**Tip podataka**  | Niska |
|**Moguće vrednosti**  | `BasicDiagnosticData` *(ovo postavlja nivo na Obavezno)* <br/> `FullDiagnosticData` *(ovo postavlja nivo na Opcionalno)* <br/> `ZeroDiagnosticData` *(ovo postavlja nivo na Nijedno)* |
|**Dostupnost** |16.28 i novije verzije |

> [!NOTE]
> Ako podesite ovu željenu opciju, ona će se primeniti i na sledeće proizvode:
> - Verzija 1.00.217856 i novije verzije aplikacije Teams za Mac
> - Verzija 16.28 i novije verzije programa Skype za posao za Mac

Ako ne postavite ovu željenu postavku, i opcionalni i obavezni dijagnostički podaci šalju se korporaciji Microsoft ako se korisnici sa pretplatom na Office 365 prijave pomoću poslovnog ili školskog naloga ili ako korisnici imaju količinsku licenciranu verziju sistema Office 2019 za Mac. Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.

Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, šalju se samo neophodni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Željene opcije** > **Privatnost**.

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj

Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije. Na primer, PowerPoint Dizajner ili Istraživač u programu Word. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.office` |
|**Taster**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|
|**Dostupnost** |16.28 i novije verzije |

Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima. 

Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima verziju sistema Office 2019 za količinsku licencu za Mac, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Željene opcije** > **Privatnost**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži

Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, 3D modele, video zapise i referentne materijale kako biste poboljšali svoje dokumente. Na primer, Office predloške ili PowerPoint QuickStarter. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.office` |
|**Taster**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|
|**Dostupnost** |16.28 i novije verzije |

Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.

Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima neku količinski licenciranu verziju sistema Office 2019 za Mac, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što će posetiti **Željene opcije** > **Privatnost**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Postavka željenih opcija za opcionalna povezana iskustva

Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog. Na primer, LinkedIn funkcije Pomoćnika za biografiju u programu Word ili traka vremenske prognoze u programu Outlook koja koristi MSN vremensku prognozu. Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.office` |
|**Taster**  | `OptionalConnectedExperiencesPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|
|**Dostupnost** |16.28 i novije verzije |

Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 koji se prijave pomoću poslovnog ili školskog naloga ili korisnicima koji imaju količinski licenciranu verziju sistema Office 2019 za Mac. Ako niste postavili ovu željenu opciju na `FALSE`, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će posetiti **Željene opcije** > **Privatnost**.

Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.

## <a name="preference-setting-for-most-connected-experiences"></a>Postavka željenih opcija za većinu povezanih iskustava

Ovu opciju možete da koristite da biste kontrolisali da li je većina povezanih iskustva dostupna vašim korisnicima.

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.office` |
|**Taster**  | `ConnectedOfficeExperiencesPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|
|**Dostupnost** |16.28 i novije verzije |

Ako ne postavite željenu opciju, sva povezana iskustva su dostupna vašim korisnicima, osim ako niste postavili neku od drugih željenih opcija za povezana iskustva prethodno pomenuta, kao što je `OfficeExperiencesAnalyzingContentPreference`.

Na primer, ako postavite ovu željenu opciju na `FALSE`, sledeći tipovi povezanih iskustava neće biti dostupni korisnicima:
- Iskustva koja analiziraju vaš sadržaj
- Iskustva koja preuzimaju sadržaj na mreži
- Opcionalna povezana iskustva

Pored toga, ako postavite ovu željenu opciju na `FALSE`, većina drugih povezanih iskustava će takođe biti isključena, kao što su koautorstvo i skladištenje datoteka na mreži. Za kompletni spisak drugih povezanih iskustava, pogledajte članak [Povezana iskustva u sistemu Office](connected-experiences.md).

Čak i ako postavite ovu željenu opciju na `FALSE`, pojedine funkcije će ostati na raspolaganju, kao što su sinhronizacija poštanskog sandučeta u programu Outlook, a Teams i Skype za posao će i dalje raditi. [Osnovne usluge](essential-services.md), kao što je usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office, će ostati na raspolaganju.

Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima verziju sistema Office 2019 za količinsku licencu za Mac, korisnik ne može da isključi većinu povezanih iskustava.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva tako što će posetiti **Željene opcije** > **Privatnost**.

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>Postavka željenih opcija za dijalog Obaveštenje o obaveznim podacima za Microsoft AutoUpdate

Kada se pokrene prva verzija 4.12 ili novija verzija programa Microsoft AutoUpdate (MAU), korisnici će videti dijalog **Obaveštenje o obaveznim podacima** koji pruža informacije o tome koji podaci se iz programa MAU šalju korporaciji Microsoft.

Ako ne želite da korisnici vide ovaj dijalog **Obaveštenje o obaveznim podacima** za Microsoft AutoUpdate, možete da postavite sledeće željene opcije. Bez obzira na to koju vrednost postavite, dijalog se neće prikazivati korisnicima.

|||
|:-----|:-----|
|**Prioritetni domen**  | `com.microsoft.autoupdate2` |
|**Taster**  | `AcknowledgedDataCollectionPolicy`  |
|**Tip podataka**  | Niska |
|**Moguće vrednosti**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Dostupnost** |4.12 i novije verzije |

Ako korisnicima dozvolite da vide ovaj dijalog, kada korisnik odabere **U redu**, vrednost `RequiredDataOnly` je upisana u `AcknowledgedDataCollectionPolicy` i dijalog se više neće prikazivati korisniku.


## <a name="related-topics"></a>Povezane teme

- [Referenca profila za konfiguraciju (dokumentacija za Apple programere)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [Primena željenih opcija za Office za Mac](../mac/deploy-preferences-for-office-for-mac.md)
- [Postavke privatnosti naloga](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
