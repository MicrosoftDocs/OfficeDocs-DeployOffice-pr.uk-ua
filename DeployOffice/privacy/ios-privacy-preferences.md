---
title: Параметри налаштування елементів керування конфіденційністю в Office на пристроях з iOS
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
description: Ця стаття пропонує адміністраторам Office інформацію про налаштування параметрів конфіденційності на пристроях з iOS.
hideEdit: true
ms.openlocfilehash: ed24ac934625bba61eac25e764a892d48365c005
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794678"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="12efa-103">Параметри налаштування елементів керування конфіденційністю в Office на пристроях з iOS</span><span class="sxs-lookup"><span data-stu-id="12efa-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="12efa-104">Перелік продуктів Office, яких стосуються ці відомості про приватність, див. в статті [Елементи керування приватністю, доступні для продуктів Office](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="12efa-105">Office на пристроях з iOS включає нові параметри, що дають змогу налаштувати:</span><span class="sxs-lookup"><span data-stu-id="12efa-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="12efa-106">збір і надсилання до корпорації Майкрософт \***діагностичних даних** про клієнтське програмне забезпечення Office;</span><span class="sxs-lookup"><span data-stu-id="12efa-106">\***Diagnostic data** _ that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="12efa-107">_\*_підключені можливості_\*_ , які використовують хмарні функції, що надають розширені можливості Office вам та вашим користувачам.</span><span class="sxs-lookup"><span data-stu-id="12efa-107">_*_Connected experiences_*_ that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="12efa-108">Докладні відомості про діагностичні дані та компоненти підключеного функціоналу див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="12efa-109">Використання подібних параметрів на комп’ютерах із macOS описано в цій [статті про Office для Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="12efa-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="12efa-110">Налаштування параметрів для пристроїв</span><span class="sxs-lookup"><span data-stu-id="12efa-110">Setting device preferences</span></span>
<span data-ttu-id="12efa-111">Ці нові параметри також можна задати на рівні пристрою на сервері керування мобільними пристроями (MDM), якщо інстальовано програму Office.</span><span class="sxs-lookup"><span data-stu-id="12efa-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="12efa-112">Багато серверів MDM дозволяють ІТ-адміністраторам додати словник конфігурації, якщо сервер надсилає MDM-команду `InstallApplication` на пристрій з iOS.</span><span class="sxs-lookup"><span data-stu-id="12efa-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="12efa-113">Докладні відомості див. в документації сервера MDM.</span><span class="sxs-lookup"><span data-stu-id="12efa-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="12efa-114">Словник являє собою набір пар "ключ-значення" у форматі XML.</span><span class="sxs-lookup"><span data-stu-id="12efa-114">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="12efa-115">Наприклад,</span><span class="sxs-lookup"><span data-stu-id="12efa-115">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="12efa-116">надісланий на пристрій словник конфігурації матиме ключ `com.apple.managed.configuration` і буде зчитаний під час запуску програми Office.</span><span class="sxs-lookup"><span data-stu-id="12efa-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="12efa-117">Крім того, ви можете скористатися службою хмарної політики Office і такими 4 параметрами політики:</span><span class="sxs-lookup"><span data-stu-id="12efa-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="12efa-118">Настроювання рівня діагностичних даних клієнтського програмного забезпечення, які передаються з Office до корпорації Майкрософт</span><span class="sxs-lookup"><span data-stu-id="12efa-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="12efa-119">Дозволити використання в Office підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="12efa-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="12efa-120">Дозволити використання в Office підключених можливостей, які завантажують вміст з Інтернету</span><span class="sxs-lookup"><span data-stu-id="12efa-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="12efa-121">Дозволити використання в Office додаткових необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="12efa-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="12efa-122">Параметри конфіденційності в Outlook для iOS і OneDrive для iOS можна налаштувати лише за допомогою служби хмарної політики Office.</span><span class="sxs-lookup"><span data-stu-id="12efa-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="12efa-123">Додаткові відомості про використання служби хмарної політики Office див. в статті [Огляд служби хмарної політики Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="12efa-124">Налаштування параметра для діагностичних даних </span><span class="sxs-lookup"><span data-stu-id="12efa-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="12efa-125">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="12efa-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="12efa-126">Додаткові відомості див. в статті [Діагностичні дані, надіслані зі служби "Програми Microsoft 365 для підприємств" до корпорації Майкрософт](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="12efa-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="12efa-127">_ *Ключ*\*</span><span class="sxs-lookup"><span data-stu-id="12efa-127">_ *Key*\*</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="12efa-128">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="12efa-128">**Data Type**</span></span>  | <span data-ttu-id="12efa-129">Рядок</span><span class="sxs-lookup"><span data-stu-id="12efa-129">String</span></span> |
|<span data-ttu-id="12efa-130">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="12efa-130">**Possible values**</span></span>  | <span data-ttu-id="12efa-131">`BasicDiagnosticData` *(установлюється рівень "Необхідні дані")*</span><span class="sxs-lookup"><span data-stu-id="12efa-131">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="12efa-132">`FullDiagnosticData` *(установлюється рівень "Необов’язкові дані")*</span><span class="sxs-lookup"><span data-stu-id="12efa-132">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="12efa-133">`ZeroDiagnosticData` *(установлюється рівень "Немає")*</span><span class="sxs-lookup"><span data-stu-id="12efa-133">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="12efa-134">Якщо не задавати цей параметр, від користувачів із передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис, до корпорації Майкрософт надсилаються лише необхідні діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="12efa-134">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="12efa-135">До того ж такі користувачі не зможуть змінювати рівень діагностичних даних, незалежно від того, як ви налаштували цей параметр.</span><span class="sxs-lookup"><span data-stu-id="12efa-135">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="12efa-136">Від інших, зокрема користувачів із передплатою на Office 365 (або Microsoft 365) для дому, надсилаються лише необхідні діагностичні дані (але користувач може на власний розсуд додати ще й необов’язкові дані до розділу **Параметри** > **Параметри конфіденційності** ).</span><span class="sxs-lookup"><span data-stu-id="12efa-136">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings** .</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="12efa-137">Налаштування параметра для підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="12efa-137">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="12efa-138">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="12efa-138">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="12efa-139">Наприклад, Варіанти оформлення в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="12efa-139">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="12efa-140">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-140">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="12efa-141">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="12efa-141">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="12efa-142">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="12efa-142">**Data Type**</span></span>  | <span data-ttu-id="12efa-143">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="12efa-143">Boolean</span></span> |
|<span data-ttu-id="12efa-144">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="12efa-144">**Possible values**</span></span>  | <span data-ttu-id="12efa-145">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-145">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="12efa-146">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-146">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="12efa-147">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу для аналізу вмісту.</span><span class="sxs-lookup"><span data-stu-id="12efa-147">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="12efa-148">Їх не зможуть вимкнути користувачі з передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="12efa-148">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="12efa-149">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності** .</span><span class="sxs-lookup"><span data-stu-id="12efa-149">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="12efa-150">Налаштування параметра для підключених можливостей, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="12efa-150">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="12efa-151">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="12efa-151">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="12efa-152">Наприклад, шаблони Office або вставлення піктограм з Інтернету.</span><span class="sxs-lookup"><span data-stu-id="12efa-152">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="12efa-153">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-153">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="12efa-154">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="12efa-154">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="12efa-155">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="12efa-155">**Data Type**</span></span>  | <span data-ttu-id="12efa-156">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="12efa-156">Boolean</span></span> |
|<span data-ttu-id="12efa-157">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="12efa-157">**Possible values**</span></span>  | <span data-ttu-id="12efa-158">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-158">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="12efa-159">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-159">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="12efa-160">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу, що завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="12efa-160">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="12efa-161">Їх не зможуть вимкнути користувачі з передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="12efa-161">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="12efa-162">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності** .</span><span class="sxs-lookup"><span data-stu-id="12efa-162">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="12efa-163">Налаштування параметра для необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="12efa-163">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="12efa-164">На додачу до згаданих вище пропонуються необов’язкові підключені можливості, до яких можна надати доступ користувачам з обліковим записом організації, також відомим як робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="12efa-164">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="12efa-165">Наприклад, надбудови Office, завантажені на ваш пристрій із Магазину Office.</span><span class="sxs-lookup"><span data-stu-id="12efa-165">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="12efa-166">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей в Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="12efa-166">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="12efa-167">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="12efa-167">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="12efa-168">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="12efa-168">**Data Type**</span></span>  | <span data-ttu-id="12efa-169">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="12efa-169">Boolean</span></span> |
|<span data-ttu-id="12efa-170">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="12efa-170">**Possible values**</span></span>  | <span data-ttu-id="12efa-171">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-171">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="12efa-172">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="12efa-172">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="12efa-173">Якщо не задавати цей параметр, компоненти необов’язкового підключеного функціонала будуть доступні для користувачів із передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="12efa-173">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="12efa-174">Якщо ви не задали для цього параметра значення FALSE, такі користувачі можуть вимкнути ці можливості в розділі **Параметри** > **Параметри конфіденційності** .</span><span class="sxs-lookup"><span data-stu-id="12efa-174">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings** .</span></span>

<span data-ttu-id="12efa-175">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, не можуть їх вимкнути.</span><span class="sxs-lookup"><span data-stu-id="12efa-175">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>