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
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="ec034-103">Korišćenje željenih postavki za upravljanje kontrolama privatnosti u sistemu Office za Mac</span><span class="sxs-lookup"><span data-stu-id="ec034-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="ec034-104">Počevši od verzije 16.28 sistema Office za Mac, postoje nove željene postavke koje će vam omogućiti da kontrolišete postavke vezane za sledeće:</span><span class="sxs-lookup"><span data-stu-id="ec034-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="ec034-105">***Diagnostičke podatke*** koji se prikupljaju i šalju korporaciji Microsoft o Office klijentskom softveru koji se koristi</span><span class="sxs-lookup"><span data-stu-id="ec034-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="ec034-106">***Povezana iskustva*** koja koriste funkcionalnost zasnovanu na oblaku da pruže poboljšane funkcije sistema Office vama i vašim korisnicima.</span><span class="sxs-lookup"><span data-stu-id="ec034-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="ec034-107">Pored toga, postoji nova željena postavka koja se odnosi na dijalog **Obaveštenje o zahtevanim podacima** za Microsoft AutoUpdate (MAU).</span><span class="sxs-lookup"><span data-stu-id="ec034-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="ec034-108">Više informacija o dijagnostičkim podacima i povezanim iskustvima potražite u članku [Pregled kontrola privatnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="ec034-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="ec034-109">Za više informacija o sličnim postavkama za Office na računaru koji koristi Windows pogledajte članak [Koristite regulatorne postavke za upravljanje kontrolama privatnosti za Office 365 ProPlus](manage-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="ec034-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="ec034-110">Postavljanje željenih postavki</span><span class="sxs-lookup"><span data-stu-id="ec034-110">Setting preferences</span></span>

<span data-ttu-id="ec034-111">Ove nove postavke željenih opcija su CFPreferences API kompatibilne i mogu se postaviti pomoću `defaults` komande u Terminalu i nametnuti putem Configuration Profile ili Mobile Device Management (MDM) servera.</span><span class="sxs-lookup"><span data-stu-id="ec034-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="ec034-112">Kada su željene postavke nametnute, korisnik ne može da promeni vrednosti, a sve kontrole unutar aplikacije će biti onemogućene.</span><span class="sxs-lookup"><span data-stu-id="ec034-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="ec034-113">Postavka željenih opcija za dijagnostičke podatke</span><span class="sxs-lookup"><span data-stu-id="ec034-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="ec034-114">Dijagnostički podaci se koriste da bi Office bio bezbedan i ažuriran, da bi se otkrili i otklonili problemi i da bi se poboljšao proizvod.</span><span class="sxs-lookup"><span data-stu-id="ec034-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="ec034-115">Za više informacija pogledajte [Dijagnostički podaci koji se šalju iz Office 365 ProPlus korporaciji Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="ec034-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-116">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="ec034-117">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="ec034-118">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-118">**Data Type**</span></span>  | <span data-ttu-id="ec034-119">Niska</span><span class="sxs-lookup"><span data-stu-id="ec034-119">String</span></span> |
|<span data-ttu-id="ec034-120">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-120">**Possible values**</span></span>  | <span data-ttu-id="ec034-121">`BasicDiagnosticData` *(ovo postavlja nivo na Obavezno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="ec034-122">`FullDiagnosticData` *(ovo postavlja nivo na Opcionalno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="ec034-123">`ZeroDiagnosticData` *(ovo postavlja nivo na Nijedno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="ec034-124">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-124">**Availability**</span></span> |<span data-ttu-id="ec034-125">16.28 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="ec034-126">Ako podesite ovu željenu opciju, ona će se primeniti i na sledeće proizvode:</span><span class="sxs-lookup"><span data-stu-id="ec034-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="ec034-127">Verzija 1.00.217856 i novije verzije aplikacije Teams za Mac</span><span class="sxs-lookup"><span data-stu-id="ec034-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="ec034-128">Verzija 16.28 i novije verzije programa Skype za posao za Mac</span><span class="sxs-lookup"><span data-stu-id="ec034-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="ec034-129">Ako ne postavite ovu željenu postavku, i opcionalni i obavezni dijagnostički podaci šalju se korporaciji Microsoft ako se korisnici sa pretplatom na Office 365 prijave pomoću poslovnog ili školskog naloga ili ako korisnici imaju količinsku licenciranu verziju sistema Office 2019 za Mac.</span><span class="sxs-lookup"><span data-stu-id="ec034-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="ec034-130">Osim toga, ti korisnici ne mogu da promene nivo dijagnostičkih podataka bez obzira na to kako ste postavili ove željene opcije.</span><span class="sxs-lookup"><span data-stu-id="ec034-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="ec034-131">Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, šalju se samo neophodni dijagnostički podaci, osim ako korisnik odabere da pošalje i opcionalne dijagnostičke podatke tako što će posetiti **Željene opcije** > **Privatnost**.</span><span class="sxs-lookup"><span data-stu-id="ec034-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="ec034-132">Postavka željenih opcija za povezana iskustva koja analiziraju vaš sadržaj</span><span class="sxs-lookup"><span data-stu-id="ec034-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="ec034-133">Povezana iskustva koja analiziraju vaš sadržaj su iskustva koja koriste vaš Office da pruže preporuke za dizajn, predloge za uređivanje, uvid u podatke i slične funkcije.</span><span class="sxs-lookup"><span data-stu-id="ec034-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="ec034-134">Na primer, PowerPoint Dizajner ili Istraživač u programu Word.</span><span class="sxs-lookup"><span data-stu-id="ec034-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="ec034-135">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="ec034-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-136">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="ec034-137">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="ec034-138">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-138">**Data Type**</span></span>  | <span data-ttu-id="ec034-139">Bulov</span><span class="sxs-lookup"><span data-stu-id="ec034-139">Boolean</span></span> |
|<span data-ttu-id="ec034-140">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-140">**Possible values**</span></span>  | <span data-ttu-id="ec034-141">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="ec034-142">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="ec034-143">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-143">**Availability**</span></span> |<span data-ttu-id="ec034-144">16.28 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-144">16.28 and later</span></span> |

<span data-ttu-id="ec034-145">Ako ne podesite ovu željenu opciju, povezana iskustva koja analiziraju sadržaj dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="ec034-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="ec034-146">Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima verziju sistema Office 2019 za količinsku licencu za Mac, korisnik ne može da isključi povezana iskustva koja analiziraju sadržaj.</span><span class="sxs-lookup"><span data-stu-id="ec034-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="ec034-147">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja analiziraju sadržaj tako što posetiti **Željene opcije** > **Privatnost**.</span><span class="sxs-lookup"><span data-stu-id="ec034-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="ec034-148">Postavka željenih opcija za povezana iskustva koja preuzimaju sadržaj na mreži</span><span class="sxs-lookup"><span data-stu-id="ec034-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="ec034-149">Povezana iskustva koja preuzimaju sadržaj na internetu su iskustva koja vam omogućavaju da pretražite i preuzmete sadržaj na mreži, uključujući predloške, slike, 3D modele, video zapise i referentne materijale kako biste poboljšali svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="ec034-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="ec034-150">Na primer, Office predloške ili PowerPoint QuickStarter.</span><span class="sxs-lookup"><span data-stu-id="ec034-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="ec034-151">Kompletniji spisak povezanih iskustava potražite u članku [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="ec034-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-152">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="ec034-153">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="ec034-154">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-154">**Data Type**</span></span>  | <span data-ttu-id="ec034-155">Bulov</span><span class="sxs-lookup"><span data-stu-id="ec034-155">Boolean</span></span> |
|<span data-ttu-id="ec034-156">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-156">**Possible values**</span></span>  | <span data-ttu-id="ec034-157">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="ec034-158">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="ec034-159">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-159">**Availability**</span></span> |<span data-ttu-id="ec034-160">16.28 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-160">16.28 and later</span></span> |

<span data-ttu-id="ec034-161">Ako ne podesite ovu željenu opciju, povezana iskustva koja preuzimaju sadržaj na mreži dostupna su korisnicima.</span><span class="sxs-lookup"><span data-stu-id="ec034-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="ec034-162">Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima neku količinski licenciranu verziju sistema Office 2019 za Mac, korisnik ne može da isključi povezana iskustva koja preuzimaju sadržaj na mreži.</span><span class="sxs-lookup"><span data-stu-id="ec034-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="ec034-163">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva koja preuzimaju sadržaj tako što će posetiti **Željene opcije** > **Privatnost**.</span><span class="sxs-lookup"><span data-stu-id="ec034-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="ec034-164">Postavka željenih opcija za opcionalna povezana iskustva</span><span class="sxs-lookup"><span data-stu-id="ec034-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="ec034-165">Pored povezanih iskustava spomenutih iznad, postoje neka opcionalna povezana iskustva za koje možete da odaberete da omogućite svojim korisnicima da im pristupe pomoću naloga organizacije koji se ponekad zove poslovni ili školski nalog.</span><span class="sxs-lookup"><span data-stu-id="ec034-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="ec034-166">Na primer, LinkedIn funkcije Pomoćnika za biografiju u programu Word ili traka vremenske prognoze u programu Outlook koja koristi MSN vremensku prognozu.</span><span class="sxs-lookup"><span data-stu-id="ec034-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="ec034-167">Za više primera, pogledajte[Pregled opcionalnih povezanih iskustava u sistemu Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="ec034-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-168">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="ec034-169">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="ec034-170">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-170">**Data Type**</span></span>  | <span data-ttu-id="ec034-171">Bulov</span><span class="sxs-lookup"><span data-stu-id="ec034-171">Boolean</span></span> |
|<span data-ttu-id="ec034-172">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-172">**Possible values**</span></span>  | <span data-ttu-id="ec034-173">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="ec034-174">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="ec034-175">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-175">**Availability**</span></span> |<span data-ttu-id="ec034-176">16.28 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-176">16.28 and later</span></span> |

<span data-ttu-id="ec034-177">Ako ne postavite ovu željenu postavku, opcionalna povezana iskustva su dostupna korisnicima sa pretplatom na Office 365 koji se prijave pomoću poslovnog ili školskog naloga ili korisnicima koji imaju količinski licenciranu verziju sistema Office 2019 za Mac.</span><span class="sxs-lookup"><span data-stu-id="ec034-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="ec034-178">Ako niste postavili ovu željenu opciju na `FALSE`, ovi korisnici mogu da isključe opcionalna povezana iskustva tako što će posetiti **Željene opcije** > **Privatnost**.</span><span class="sxs-lookup"><span data-stu-id="ec034-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="ec034-179">Za druge korisnike, kao što su kućni korisnici sa Office 365 pretplatom, ne postoji opcija za isključivanje opcionalnih povezanih iskustava.</span><span class="sxs-lookup"><span data-stu-id="ec034-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="ec034-180">Postavka željenih opcija za većinu povezanih iskustava</span><span class="sxs-lookup"><span data-stu-id="ec034-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="ec034-181">Ovu opciju možete da koristite da biste kontrolisali da li je većina povezanih iskustva dostupna vašim korisnicima.</span><span class="sxs-lookup"><span data-stu-id="ec034-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-182">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="ec034-183">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="ec034-184">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-184">**Data Type**</span></span>  | <span data-ttu-id="ec034-185">Bulov</span><span class="sxs-lookup"><span data-stu-id="ec034-185">Boolean</span></span> |
|<span data-ttu-id="ec034-186">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-186">**Possible values**</span></span>  | <span data-ttu-id="ec034-187">`TRUE` *(omogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="ec034-188">`FALSE` *(onemogućeno)*</span><span class="sxs-lookup"><span data-stu-id="ec034-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="ec034-189">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-189">**Availability**</span></span> |<span data-ttu-id="ec034-190">16.28 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-190">16.28 and later</span></span> |

<span data-ttu-id="ec034-191">Ako ne postavite željenu opciju, sva povezana iskustva su dostupna vašim korisnicima, osim ako niste postavili neku od drugih željenih opcija za povezana iskustva prethodno pomenuta, kao što je `OfficeExperiencesAnalyzingContentPreference`.</span><span class="sxs-lookup"><span data-stu-id="ec034-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="ec034-192">Na primer, ako postavite ovu željenu opciju na `FALSE`, sledeći tipovi povezanih iskustava neće biti dostupni korisnicima:</span><span class="sxs-lookup"><span data-stu-id="ec034-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="ec034-193">Iskustva koja analiziraju vaš sadržaj</span><span class="sxs-lookup"><span data-stu-id="ec034-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="ec034-194">Iskustva koja preuzimaju sadržaj na mreži</span><span class="sxs-lookup"><span data-stu-id="ec034-194">Experiences that download online content</span></span>
- <span data-ttu-id="ec034-195">Opcionalna povezana iskustva</span><span class="sxs-lookup"><span data-stu-id="ec034-195">Optional connected experiences</span></span>

<span data-ttu-id="ec034-196">Pored toga, ako postavite ovu željenu opciju na `FALSE`, većina drugih povezanih iskustava će takođe biti isključena, kao što su koautorstvo i skladištenje datoteka na mreži.</span><span class="sxs-lookup"><span data-stu-id="ec034-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="ec034-197">Za kompletni spisak drugih povezanih iskustava, pogledajte članak [Povezana iskustva u sistemu Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="ec034-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="ec034-198">Čak i ako postavite ovu željenu opciju na `FALSE`, pojedine funkcije će ostati na raspolaganju, kao što su sinhronizacija poštanskog sandučeta u programu Outlook, a Teams i Skype za posao će i dalje raditi.</span><span class="sxs-lookup"><span data-stu-id="ec034-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="ec034-199">[Osnovne usluge](essential-services.md), kao što je usluga licenciranja koja potvrđuje da ste ispravno licencirani da koristite Office, će ostati na raspolaganju.</span><span class="sxs-lookup"><span data-stu-id="ec034-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="ec034-200">Ako korisnik ima Office 365 pretplatu i ako se prijavi pomoću poslovnog ili školskog naloga ili ako korisnik ima verziju sistema Office 2019 za količinsku licencu za Mac, korisnik ne može da isključi većinu povezanih iskustava.</span><span class="sxs-lookup"><span data-stu-id="ec034-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="ec034-201">Za druge korisnike, kao što su kućni korisnici sa pretplatom na Office 365, korisnik može da odabere da isključi povezana iskustva tako što će posetiti **Željene opcije** > **Privatnost**.</span><span class="sxs-lookup"><span data-stu-id="ec034-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="ec034-202">Postavka željenih opcija za dijalog Obaveštenje o obaveznim podacima za Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="ec034-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="ec034-203">Kada se pokrene prva verzija 4.12 ili novija verzija programa Microsoft AutoUpdate (MAU), korisnici će videti dijalog **Obaveštenje o obaveznim podacima** koji pruža informacije o tome koji podaci se iz programa MAU šalju korporaciji Microsoft.</span><span class="sxs-lookup"><span data-stu-id="ec034-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="ec034-204">Ako ne želite da korisnici vide ovaj dijalog **Obaveštenje o obaveznim podacima** za Microsoft AutoUpdate, možete da postavite sledeće željene opcije.</span><span class="sxs-lookup"><span data-stu-id="ec034-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="ec034-205">Bez obzira na to koju vrednost postavite, dijalog se neće prikazivati korisnicima.</span><span class="sxs-lookup"><span data-stu-id="ec034-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ec034-206">**Prioritetni domen**</span><span class="sxs-lookup"><span data-stu-id="ec034-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="ec034-207">**Taster**</span><span class="sxs-lookup"><span data-stu-id="ec034-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="ec034-208">**Tip podataka**</span><span class="sxs-lookup"><span data-stu-id="ec034-208">**Data Type**</span></span>  | <span data-ttu-id="ec034-209">Niska</span><span class="sxs-lookup"><span data-stu-id="ec034-209">String</span></span> |
|<span data-ttu-id="ec034-210">**Moguće vrednosti**</span><span class="sxs-lookup"><span data-stu-id="ec034-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="ec034-211">**Dostupnost**</span><span class="sxs-lookup"><span data-stu-id="ec034-211">**Availability**</span></span> |<span data-ttu-id="ec034-212">4.12 i novije verzije</span><span class="sxs-lookup"><span data-stu-id="ec034-212">4.12 and later</span></span> |

<span data-ttu-id="ec034-213">Ako korisnicima dozvolite da vide ovaj dijalog, kada korisnik odabere **U redu**, vrednost `RequiredDataOnly` je upisana u `AcknowledgedDataCollectionPolicy` i dijalog se više neće prikazivati korisniku.</span><span class="sxs-lookup"><span data-stu-id="ec034-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="ec034-214">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="ec034-214">Related topics</span></span>

- [<span data-ttu-id="ec034-215">Referenca profila za konfiguraciju (dokumentacija za Apple programere)</span><span class="sxs-lookup"><span data-stu-id="ec034-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="ec034-216">Primena željenih opcija za Office za Mac</span><span class="sxs-lookup"><span data-stu-id="ec034-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="ec034-217">Postavke privatnosti naloga</span><span class="sxs-lookup"><span data-stu-id="ec034-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
