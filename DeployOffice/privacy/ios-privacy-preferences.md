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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="0f098-103">Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje</span><span class="sxs-lookup"><span data-stu-id="0f098-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="0f098-104">Da biste videli listu Office proizvoda koji su obuhvaćeni ovim informacijama o privatnosti, pogledajte članak [„Dostupne kontrole privatnosti za Office proizvode“](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="0f098-105">Postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:</span><span class="sxs-lookup"><span data-stu-id="0f098-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="0f098-106">***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi</span><span class="sxs-lookup"><span data-stu-id="0f098-106">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="0f098-107">***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.</span><span class="sxs-lookup"><span data-stu-id="0f098-107">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="0f098-108">Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="0f098-109">Za više informacija o sličnim postavkama za Office na računaru koji koristi macOS, pogledajte članak [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="0f098-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="0f098-110">Postavljanje željenih opcija uređaja</span><span class="sxs-lookup"><span data-stu-id="0f098-110">Setting device preferences</span></span>
<span data-ttu-id="0f098-111">Ove nove željene postavke mogu da se postave i na nivou uređaja pomoću servera za upravljanje mobilnim uređajima (MDM) kada je instalirana Office aplikacija.</span><span class="sxs-lookup"><span data-stu-id="0f098-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="0f098-112">Mnogi MDM serveri omogućavaju IT administratorima da dodaju opcionalni rečnik za konfiguraciju kada server pošalje `InstallApplication` MDM komandu na iOS uređaj.</span><span class="sxs-lookup"><span data-stu-id="0f098-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="0f098-113">Za više detalja pogledajte dokumentaciju za MDM server.</span><span class="sxs-lookup"><span data-stu-id="0f098-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="0f098-p102">Rečnik je predstavljen kao skup parova ključeva/vrednosti u XML formatu. Na primer:</span><span class="sxs-lookup"><span data-stu-id="0f098-p102">The dictionary is represented as a set of key/value pairs in XML format. For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="0f098-116">Nakon što ga pošaljete na uređaj, rečnik za konfiguraciju će se nalaziti pod `com.apple.managed.configuration` ključem, gde će pročitati kada se pokrene aplikacija Office.</span><span class="sxs-lookup"><span data-stu-id="0f098-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="0f098-117">Možete da koristite i Office uslugu smernica u oblaku i ove 4 postavke smernica:</span><span class="sxs-lookup"><span data-stu-id="0f098-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="0f098-118">Podesite nivo dijagnostičkih podataka klijentskog softvera koje Office šalje korporaciji Microsoft</span><span class="sxs-lookup"><span data-stu-id="0f098-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="0f098-119">Dozvolite upotrebu povezanih iskustava koja analiziraju sadržaj u sistemu Office</span><span class="sxs-lookup"><span data-stu-id="0f098-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="0f098-120">Dozvolite upotrebu povezanih iskustava u sistemu Office koja preuzimaju mrežni sadržaj</span><span class="sxs-lookup"><span data-stu-id="0f098-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="0f098-121">Dozvolite upotrebu dodatnih opcionalnih povezanih iskustava u sistemu Office</span><span class="sxs-lookup"><span data-stu-id="0f098-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="0f098-122">Postavke privatnosti za Outlook za iOS i OneDrive za iOS mogu da se konfigurišu samo pomoću Office usluge smernice u oblaku.</span><span class="sxs-lookup"><span data-stu-id="0f098-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="0f098-123">Za više informacija o korišćenju usluge smernica oblaka za Office pogledajte članak [Pregled usluge smernica oblaka za Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="0f098-124">Postavka željenih opcija za dijagnostičke podatke</span><span class="sxs-lookup"><span data-stu-id="0f098-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="0f098-125">Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod.</span><span class="sxs-lookup"><span data-stu-id="0f098-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="0f098-126">Više informacija potražite u članku [Dijagnostički podaci koji se šalju iz Microsoft 365 aplikacija za velika preduzeća korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="0f098-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|<span data-ttu-id="0f098-127">Kategorija</span><span class="sxs-lookup"><span data-stu-id="0f098-127">Category</span></span>|<span data-ttu-id="0f098-128">Detalji</span><span class="sxs-lookup"><span data-stu-id="0f098-128">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="0f098-129">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="0f098-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="0f098-130">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="0f098-130">**Data Type**</span></span>  | <span data-ttu-id="0f098-131">Niska</span><span class="sxs-lookup"><span data-stu-id="0f098-131">String</span></span> |
|<span data-ttu-id="0f098-132">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="0f098-132">**Possible values**</span></span>  | <span data-ttu-id="0f098-133">`BasicDiagnosticData` *(ova vrednost postavlja nivo na Obavezno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-133">`BasicDiagnosticData` *(this value sets the level to Required)*</span></span> <br/> <span data-ttu-id="0f098-134">`FullDiagnosticData` *(ova vrednost postavlja nivo na Opcionalno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-134">`FullDiagnosticData` *(this value sets the level to Optional)*</span></span> <br/> <span data-ttu-id="0f098-135">`ZeroDiagnosticData` *(ova vrednost postavlja nivo na Nijedno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-135">`ZeroDiagnosticData` *(this value sets the level to Neither)*</span></span> |

<span data-ttu-id="0f098-136">Ako ne postavite ovu željenu postavku, Microsoftu se šalju obavezni i opcionalni dijagnostički podaci ako se korisnici sa pretplatom na Office 365 (ili Microsoft 365) prijavljuju pomoću poslovnog ili školskog naloga.</span><span class="sxs-lookup"><span data-stu-id="0f098-136">If you don't set this preference, both required and optional diagnostic data are sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="0f098-137">Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.</span><span class="sxs-lookup"><span data-stu-id="0f098-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

> [!NOTE]
> <span data-ttu-id="0f098-138">Ažurirali smo prethodni pasus da bismo pojasnili da se opcionalni dijagnostički podaci takođe šalju Microsoftu ako ne podesite ovu opciju.</span><span class="sxs-lookup"><span data-stu-id="0f098-138">We've updated the previous paragraph to clarify that optional diagnostic data is also sent to Microsoft if you don't set this preference.</span></span>

<span data-ttu-id="0f098-139">Za druge korisnike, kao što su kućni korisnici sa Office 365 (ili Microsoft 365) pretplatom, šalju se samo obavezni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="0f098-139">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="0f098-140">Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj</span><span class="sxs-lookup"><span data-stu-id="0f098-140">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="0f098-141">Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije.</span><span class="sxs-lookup"><span data-stu-id="0f098-141">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="0f098-142">Na primer, „Ideje za dizajn“ u programu PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="0f098-142">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="0f098-143">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-143">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="0f098-144">Kategorija</span><span class="sxs-lookup"><span data-stu-id="0f098-144">Category</span></span>|<span data-ttu-id="0f098-145">Detalji</span><span class="sxs-lookup"><span data-stu-id="0f098-145">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="0f098-146">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="0f098-146">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="0f098-147">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="0f098-147">**Data Type**</span></span>  | <span data-ttu-id="0f098-148">Bulov</span><span class="sxs-lookup"><span data-stu-id="0f098-148">Boolean</span></span> |
|<span data-ttu-id="0f098-149">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="0f098-149">**Possible values**</span></span>  | <span data-ttu-id="0f098-150">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-150">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0f098-151">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-151">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="0f098-152">Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="0f098-152">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="0f098-153">Ako korisnik ima Office 365 (ili Microsoft 365) pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.</span><span class="sxs-lookup"><span data-stu-id="0f098-153">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="0f098-154">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365 (ili Microsoft 365), korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="0f098-154">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="0f098-155">Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži</span><span class="sxs-lookup"><span data-stu-id="0f098-155">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="0f098-156">Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, video zapise i referentne materijale kako biste poboljšali svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="0f098-156">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="0f098-157">Na primer, Office predlošci ili umetanje ikone na mreži.</span><span class="sxs-lookup"><span data-stu-id="0f098-157">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="0f098-158">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-158">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="0f098-159">Kategorija</span><span class="sxs-lookup"><span data-stu-id="0f098-159">Category</span></span>|<span data-ttu-id="0f098-160">Detalji</span><span class="sxs-lookup"><span data-stu-id="0f098-160">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="0f098-161">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="0f098-161">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="0f098-162">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="0f098-162">**Data Type**</span></span>  | <span data-ttu-id="0f098-163">Bulov</span><span class="sxs-lookup"><span data-stu-id="0f098-163">Boolean</span></span> |
|<span data-ttu-id="0f098-164">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="0f098-164">**Possible values**</span></span>  | <span data-ttu-id="0f098-165">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-165">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0f098-166">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-166">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="0f098-167">Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="0f098-167">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="0f098-168">Ako korisnik ima Office 365 (ili Microsoft 365) pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.</span><span class="sxs-lookup"><span data-stu-id="0f098-168">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="0f098-169">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365 (ili Microsoft 365), korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="0f098-169">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="0f098-170">Postavka željenih opcija za opcionalna povezana iskustva</span><span class="sxs-lookup"><span data-stu-id="0f098-170">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="0f098-171">Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog.</span><span class="sxs-lookup"><span data-stu-id="0f098-171">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="0f098-172">Na primer, programski dodaci za Office koji se na uređaj preuzimaju pomoću Office prodavnice.</span><span class="sxs-lookup"><span data-stu-id="0f098-172">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="0f098-173">Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0f098-173">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|<span data-ttu-id="0f098-174">Kategorija</span><span class="sxs-lookup"><span data-stu-id="0f098-174">Category</span></span>|<span data-ttu-id="0f098-175">Detalji</span><span class="sxs-lookup"><span data-stu-id="0f098-175">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="0f098-176">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="0f098-176">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="0f098-177">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="0f098-177">**Data Type**</span></span>  | <span data-ttu-id="0f098-178">Bulov</span><span class="sxs-lookup"><span data-stu-id="0f098-178">Boolean</span></span> |
|<span data-ttu-id="0f098-179">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="0f098-179">**Possible values**</span></span>  | <span data-ttu-id="0f098-180">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-180">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0f098-181">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="0f098-181">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="0f098-182">Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 (ili Microsoft 365) koji se prijave pomoću poslovnog ili školskog naloga.</span><span class="sxs-lookup"><span data-stu-id="0f098-182">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="0f098-183">Ako niste postavili ovu željenu opciju na FALSE, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će otići na **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="0f098-183">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="0f098-184">Za druge korisnike, kao što su kućni korisnici sa Office 365 (ili Microsoft 365) pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.</span><span class="sxs-lookup"><span data-stu-id="0f098-184">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>