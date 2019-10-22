---
title: Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje
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
description: Administratorima sistema Office pruža informacije o tome kako da upravljaju postavkama privatnosti na iOS uređajima.
hideEdit: true
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604297"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje

Postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:

- ***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi

- ***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.

Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).

Ove željene postavke odnose se na sledeće aplikacije:
- Verzija 2.30 i novije verzije programa Word za iOS, Excel za iOS i PowerPoint za iOS.
- Verzija 16.30 i novije verzije programa OneNote za iOS.
- Verzija 1.17 i novije verzije programa Visio Viewer za iOS.

> [!NOTE]
> Za više informacija o sličnim postavkama za Office na računaru koji koristi macOS, pogledajte članak [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)


## <a name="setting-device-preferences"></a>Postavljanje željenih opcija uređaja
Ove nove željene postavke mogu da se postave i na nivou uređaja pomoću servera za upravljanje mobilnim uređajima (MDM) kada je instalirana Office aplikacija. Mnogi MDM serveri omogućavaju IT administratorima da dodaju opcionalni rečnik za konfiguraciju kada server pošalje `InstallApplication` MDM komandu na iOS uređaj. Za više detalja pogledajte dokumentaciju za MDM server.

Rečnik je predstavljen kao skup parova ključeva/vrednosti u XML formatu. Na primer:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Nakon što ga pošaljete na uređaj, rečnik za konfiguraciju će se nalaziti pod `com.apple.managed.configuration` ključem, gde će pročitati kada se pokrene aplikacija Office.

## <a name="preference-setting-for-diagnostic-data"></a>Postavka željenih opcija za dijagnostičke podatke

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Za više informacija pogledajte [Dijagnostički podaci koji se šalju iz Office 365 ProPlus korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Ključ**  | `DiagnosticDataTypePreference`  |
|**Tip podataka**  | Niska |
|**Moguće vrednosti**  | `BasicDiagnosticData` *(ovo postavlja nivo na Obavezno)* <br/> `FullDiagnosticData` *(ovo postavlja nivo na Opcionalno)* <br/> `ZeroDiagnosticData` *(ovo postavlja nivo na Nijedno)* |

Ako ne postavite ovu željenu postavku, korporaciji Microsoft šalju se samo obavezni dijagnostički podaci ako se korisnici sa pretplatom na Office 365 prijave pomoću poslovnog ili školskog naloga Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.

Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, šalju se samo obavezni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Postavke** > **Postavke privatnosti**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj

Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije. Na primer, „Ideje za dizajn“ u programu PowerPoint. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima.

Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži

Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, video zapise i referentne materijale kako biste poboljšali svoje dokumente. Na primer, Office predlošci ili umetanje ikone na mreži. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.

Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Postavka željenih opcija za opcionalna povezana iskustva

Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog. Na primer, programski dodaci za Office koji se na uređaj preuzimaju pomoću Office prodavnice. Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OptionalConnectedExperiencesPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 koji se prijave pomoću poslovnog ili školskog naloga. Ako niste postavili ovu željenu opciju na FALSE, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će otići na **Postavke** > **Postavke privatnosti**.

Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.