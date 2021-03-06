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
ms.openlocfilehash: 000fd2c5e13ed51abf3afba6e7a1433c9d4b912f
ms.sourcegitcommit: 9b5f18c543c286c95e546e22fc8edb60ef541030
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/20/2021
ms.locfileid: "52578350"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje

> [!NOTE]
> Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).

Postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:

- ***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi

- ***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.

Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).

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

> [!NOTE]
> Možete da koristite i Office uslugu smernica u oblaku i ove 4 postavke smernica:
> - Podesite nivo dijagnostičkih podataka klijentskog softvera koje Office šalje korporaciji Microsoft
> - Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office
> - Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj
> - Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office
>
> Postavke privatnosti za Outlook za iOS i OneDrive za iOS mogu da se konfigurišu samo pomoću Office usluge smernice u oblaku.
>
> Za više informacija o korišćenju usluge smernica oblaka za Office pogledajte članak [Pregled usluge smernica oblaka za Office](../overview-office-cloud-policy-service.md).

## <a name="preference-setting-for-diagnostic-data"></a>Postavka željenih opcija za dijagnostičke podatke

Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod. Više informacija potražite u članku [Dijagnostički podaci koji se šalju iz Microsoft 365 aplikacija za velika preduzeća korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|Kategorija|Detalji|
|:-----|:-----|
|**Ključ**  | `DiagnosticDataTypePreference`  |
|**Tip podataka**  | Niska |
|**Moguće vrednosti**  | `BasicDiagnosticData` *(ova vrednost postavlja nivo na Obavezno)* <br/> `FullDiagnosticData` *(ova vrednost postavlja nivo na Opcionalno)* <br/> `ZeroDiagnosticData` *(ova vrednost postavlja nivo na Nijedno)* |

Ako ne postavite ovu željenu postavku, Microsoftu se šalju obavezni i opcionalni dijagnostički podaci ako se korisnici sa pretplatom na Office 365 (ili Microsoft 365) prijavljuju pomoću poslovnog ili školskog naloga. Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.

> [!NOTE]
> Ažurirali smo prethodni pasus da bismo pojasnili da se opcionalni dijagnostički podaci takođe šalju Microsoftu ako ne podesite ovu opciju.

Za druge korisnike, kao što su kućni korisnici sa Office 365 (ili Microsoft 365) pretplatom, šalju se samo obavezni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Postavke** > **Postavke privatnosti**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj

Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije. Na primer, „Ideje za dizajn“ u programu PowerPoint. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|Kategorija|Detalji|
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima.

Ako korisnik ima Office 365 (ili Microsoft 365) pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365 (ili Microsoft 365), korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži

Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, video zapise i referentne materijale kako biste poboljšali svoje dokumente. Na primer, Office predlošci ili umetanje ikone na mreži. Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).

|Kategorija|Detalji|
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.

Ako korisnik ima Office 365 (ili Microsoft 365) pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.

Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365 (ili Microsoft 365), korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Postavka željenih opcija za opcionalna povezana iskustva

Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog. Na primer, programski dodaci za Office koji se na uređaj preuzimaju pomoću Office prodavnice. Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).

|Kategorija|Detalji|
|:-----|:-----|
|**Ključ**  | `OptionalConnectedExperiencesPreference`  |
|**Tip podataka**  | Bulov |
|**Moguće vrednosti**  | `TRUE` *(omogućeno)* <br/> `FALSE` *(onemogućeno)*|


Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 (ili Microsoft 365) koji se prijave pomoću poslovnog ili školskog naloga. Ako niste postavili ovu željenu opciju na FALSE, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će otići na **Postavke** > **Postavke privatnosti**.

Za druge korisnike, kao što su kućni korisnici sa Office 365 (ili Microsoft 365) pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.