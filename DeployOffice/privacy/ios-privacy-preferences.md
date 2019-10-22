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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="79a20-103">Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za iOS uređaje</span><span class="sxs-lookup"><span data-stu-id="79a20-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="79a20-104">Postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:</span><span class="sxs-lookup"><span data-stu-id="79a20-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="79a20-105">***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi</span><span class="sxs-lookup"><span data-stu-id="79a20-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="79a20-106">***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.</span><span class="sxs-lookup"><span data-stu-id="79a20-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="79a20-107">Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="79a20-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="79a20-108">Ove željene postavke odnose se na sledeće aplikacije:</span><span class="sxs-lookup"><span data-stu-id="79a20-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="79a20-109">Verzija 2.30 i novije verzije programa Word za iOS, Excel za iOS i PowerPoint za iOS.</span><span class="sxs-lookup"><span data-stu-id="79a20-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="79a20-110">Verzija 16.30 i novije verzije programa OneNote za iOS.</span><span class="sxs-lookup"><span data-stu-id="79a20-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="79a20-111">Verzija 1.17 i novije verzije programa Visio Viewer za iOS.</span><span class="sxs-lookup"><span data-stu-id="79a20-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="79a20-112">Za više informacija o sličnim postavkama za Office na računaru koji koristi macOS, pogledajte članak [Korišćenje željenih opcija za upravljanje kontrolama privatnosti u sistemu Office za Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="79a20-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="79a20-113">Postavljanje željenih opcija uređaja</span><span class="sxs-lookup"><span data-stu-id="79a20-113">Setting device preferences</span></span>
<span data-ttu-id="79a20-114">Ove nove željene postavke mogu da se postave i na nivou uređaja pomoću servera za upravljanje mobilnim uređajima (MDM) kada je instalirana Office aplikacija.</span><span class="sxs-lookup"><span data-stu-id="79a20-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="79a20-115">Mnogi MDM serveri omogućavaju IT administratorima da dodaju opcionalni rečnik za konfiguraciju kada server pošalje `InstallApplication` MDM komandu na iOS uređaj.</span><span class="sxs-lookup"><span data-stu-id="79a20-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="79a20-116">Za više detalja pogledajte dokumentaciju za MDM server.</span><span class="sxs-lookup"><span data-stu-id="79a20-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="79a20-117">Rečnik je predstavljen kao skup parova ključeva/vrednosti u XML formatu.</span><span class="sxs-lookup"><span data-stu-id="79a20-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="79a20-118">Na primer:</span><span class="sxs-lookup"><span data-stu-id="79a20-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="79a20-119">Nakon što ga pošaljete na uređaj, rečnik za konfiguraciju će se nalaziti pod `com.apple.managed.configuration` ključem, gde će pročitati kada se pokrene aplikacija Office.</span><span class="sxs-lookup"><span data-stu-id="79a20-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="79a20-120">Postavka željenih opcija za dijagnostičke podatke</span><span class="sxs-lookup"><span data-stu-id="79a20-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="79a20-121">Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod.</span><span class="sxs-lookup"><span data-stu-id="79a20-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="79a20-122">Za više informacija pogledajte [Dijagnostički podaci koji se šalju iz Office 365 ProPlus korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="79a20-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="79a20-123">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="79a20-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="79a20-124">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="79a20-124">**Data Type**</span></span>  | <span data-ttu-id="79a20-125">Niska</span><span class="sxs-lookup"><span data-stu-id="79a20-125">String</span></span> |
|<span data-ttu-id="79a20-126">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="79a20-126">**Possible values**</span></span>  | <span data-ttu-id="79a20-127">`BasicDiagnosticData` *(ovo postavlja nivo na Obavezno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="79a20-128">`FullDiagnosticData` *(ovo postavlja nivo na Opcionalno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="79a20-129">`ZeroDiagnosticData` *(ovo postavlja nivo na Nijedno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="79a20-130">Ako ne postavite ovu željenu postavku, korporaciji Microsoft šalju se samo obavezni dijagnostički podaci ako se korisnici sa pretplatom na Office 365 prijave pomoću poslovnog ili školskog naloga</span><span class="sxs-lookup"><span data-stu-id="79a20-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="79a20-131">Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.</span><span class="sxs-lookup"><span data-stu-id="79a20-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="79a20-132">Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, šalju se samo obavezni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="79a20-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="79a20-133">Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj</span><span class="sxs-lookup"><span data-stu-id="79a20-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="79a20-134">Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije.</span><span class="sxs-lookup"><span data-stu-id="79a20-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="79a20-135">Na primer, „Ideje za dizajn“ u programu PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="79a20-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="79a20-136">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="79a20-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="79a20-137">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="79a20-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="79a20-138">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="79a20-138">**Data Type**</span></span>  | <span data-ttu-id="79a20-139">Bulov</span><span class="sxs-lookup"><span data-stu-id="79a20-139">Boolean</span></span> |
|<span data-ttu-id="79a20-140">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="79a20-140">**Possible values**</span></span>  | <span data-ttu-id="79a20-141">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="79a20-142">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="79a20-143">Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="79a20-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="79a20-144">Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.</span><span class="sxs-lookup"><span data-stu-id="79a20-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="79a20-145">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="79a20-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="79a20-146">Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži</span><span class="sxs-lookup"><span data-stu-id="79a20-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="79a20-147">Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, video zapise i referentne materijale kako biste poboljšali svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="79a20-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="79a20-148">Na primer, Office predlošci ili umetanje ikone na mreži.</span><span class="sxs-lookup"><span data-stu-id="79a20-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="79a20-149">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="79a20-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="79a20-150">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="79a20-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="79a20-151">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="79a20-151">**Data Type**</span></span>  | <span data-ttu-id="79a20-152">Bulov</span><span class="sxs-lookup"><span data-stu-id="79a20-152">Boolean</span></span> |
|<span data-ttu-id="79a20-153">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="79a20-153">**Possible values**</span></span>  | <span data-ttu-id="79a20-154">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="79a20-155">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="79a20-156">Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="79a20-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="79a20-157">Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.</span><span class="sxs-lookup"><span data-stu-id="79a20-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="79a20-158">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što posetiti **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="79a20-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="79a20-159">Postavka željenih opcija za opcionalna povezana iskustva</span><span class="sxs-lookup"><span data-stu-id="79a20-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="79a20-160">Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog.</span><span class="sxs-lookup"><span data-stu-id="79a20-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="79a20-161">Na primer, programski dodaci za Office koji se na uređaj preuzimaju pomoću Office prodavnice.</span><span class="sxs-lookup"><span data-stu-id="79a20-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="79a20-162">Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="79a20-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="79a20-163">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="79a20-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="79a20-164">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="79a20-164">**Data Type**</span></span>  | <span data-ttu-id="79a20-165">Bulov</span><span class="sxs-lookup"><span data-stu-id="79a20-165">Boolean</span></span> |
|<span data-ttu-id="79a20-166">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="79a20-166">**Possible values**</span></span>  | <span data-ttu-id="79a20-167">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="79a20-168">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="79a20-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="79a20-169">Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 koji se prijave pomoću poslovnog ili školskog naloga.</span><span class="sxs-lookup"><span data-stu-id="79a20-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="79a20-170">Ako niste postavili ovu željenu opciju na FALSE, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će otići na **Postavke** > **Postavke privatnosti**.</span><span class="sxs-lookup"><span data-stu-id="79a20-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="79a20-171">Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.</span><span class="sxs-lookup"><span data-stu-id="79a20-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>