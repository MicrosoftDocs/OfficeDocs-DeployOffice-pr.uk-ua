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
ms.openlocfilehash: 6465a5b5e2103070170bdec8cd64b8bc044d46a3
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087868"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="07da0-103">Параметри налаштування елементів керування конфіденційністю в Office на пристроях з iOS</span><span class="sxs-lookup"><span data-stu-id="07da0-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="07da0-104">Office на пристроях з iOS включає нові параметри, що дають змогу налаштувати:</span><span class="sxs-lookup"><span data-stu-id="07da0-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="07da0-105">збір і надсилання до корпорації Майкрософт ***діагностичних даних*** про клієнтське програмне забезпечення Office;</span><span class="sxs-lookup"><span data-stu-id="07da0-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="07da0-106">доступність додаткових хмарних ***підключених можливостей*** Office.</span><span class="sxs-lookup"><span data-stu-id="07da0-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="07da0-107">Докладні відомості про діагностичні дані та компоненти підключеного функціоналу див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="07da0-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="07da0-108">Ці параметри застосовуються до таких програм:</span><span class="sxs-lookup"><span data-stu-id="07da0-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="07da0-109">Word для iOS, Excel для iOS і PowerPoint для iOS версії 2.30 і новіших;</span><span class="sxs-lookup"><span data-stu-id="07da0-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="07da0-110">Outlook для iOS версії 4.30.0 і новіших;</span><span class="sxs-lookup"><span data-stu-id="07da0-110">Version 4.30.0 and later of Outlook for iOS</span></span>
- <span data-ttu-id="07da0-111">OneNote для iOS версії 16.30 і новіших;</span><span class="sxs-lookup"><span data-stu-id="07da0-111">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="07da0-112">OneDrive для iOS версії 11.19.11 і новіших;</span><span class="sxs-lookup"><span data-stu-id="07da0-112">Version 11.19.11 and later of OneDrive for iOS.</span></span>
- <span data-ttu-id="07da0-113">Переглядач Visio для iOS версії 1.17 і новіших.</span><span class="sxs-lookup"><span data-stu-id="07da0-113">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="07da0-114">Використання подібних параметрів на комп’ютерах із macOS описано в цій [статті про Office для Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="07da0-114">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="07da0-115">Налаштування параметрів для пристроїв</span><span class="sxs-lookup"><span data-stu-id="07da0-115">Setting device preferences</span></span>
<span data-ttu-id="07da0-116">Ці нові параметри також можна задати на рівні пристрою на сервері керування мобільними пристроями (MDM), якщо інстальовано програму Office.</span><span class="sxs-lookup"><span data-stu-id="07da0-116">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="07da0-117">Багато серверів MDM дозволяють ІТ-адміністраторам додати словник конфігурації, якщо сервер надсилає MDM-команду `InstallApplication` на пристрій з iOS.</span><span class="sxs-lookup"><span data-stu-id="07da0-117">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="07da0-118">Докладні відомості див. в документації сервера MDM.</span><span class="sxs-lookup"><span data-stu-id="07da0-118">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="07da0-119">Словник являє собою набір пар "ключ-значення" у форматі XML.</span><span class="sxs-lookup"><span data-stu-id="07da0-119">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="07da0-120">Наприклад,</span><span class="sxs-lookup"><span data-stu-id="07da0-120">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="07da0-121">надісланий на пристрій словник конфігурації матиме ключ `com.apple.managed.configuration` і буде зчитаний під час запуску програми Office.</span><span class="sxs-lookup"><span data-stu-id="07da0-121">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="07da0-122">Крім того, ви можете скористатися службою хмарної політики Office і такими 4 параметрами політики:</span><span class="sxs-lookup"><span data-stu-id="07da0-122">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="07da0-123">Настроювання рівня діагностичних даних клієнтського програмного забезпечення, які передаються з Office до корпорації Майкрософт</span><span class="sxs-lookup"><span data-stu-id="07da0-123">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="07da0-124">Дозволити використання в Office підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="07da0-124">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="07da0-125">Дозволити використання в Office підключених можливостей, які завантажують вміст з Інтернету</span><span class="sxs-lookup"><span data-stu-id="07da0-125">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="07da0-126">Дозволити використання в Office додаткових необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="07da0-126">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="07da0-127">Параметри конфіденційності в Outlook для iOS і OneDrive для iOS можна налаштувати лише за допомогою служби хмарної політики Office.</span><span class="sxs-lookup"><span data-stu-id="07da0-127">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="07da0-128">Додаткові відомості про використання служби хмарної політики Office див. в статті [Огляд служби хмарної політики Office](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="07da0-128">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="07da0-129">Налаштування параметра для діагностичних даних </span><span class="sxs-lookup"><span data-stu-id="07da0-129">Preference setting for diagnostic data</span></span>

<span data-ttu-id="07da0-130">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="07da0-130">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="07da0-131">Додаткові відомості див. в статті [Діагностичні дані, надіслані зі служби "Програми Microsoft 365 для підприємств" до корпорації Майкрософт](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="07da0-131">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="07da0-132">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="07da0-132">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="07da0-133">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="07da0-133">**Data Type**</span></span>  | <span data-ttu-id="07da0-134">Рядок</span><span class="sxs-lookup"><span data-stu-id="07da0-134">String</span></span> |
|<span data-ttu-id="07da0-135">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="07da0-135">**Possible values**</span></span>  | <span data-ttu-id="07da0-136">`BasicDiagnosticData` *(установлюється рівень "Необхідні дані")*</span><span class="sxs-lookup"><span data-stu-id="07da0-136">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="07da0-137">`FullDiagnosticData` *(установлюється рівень "Необов’язкові дані")*</span><span class="sxs-lookup"><span data-stu-id="07da0-137">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="07da0-138">`ZeroDiagnosticData` *(установлюється рівень "Немає")*</span><span class="sxs-lookup"><span data-stu-id="07da0-138">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="07da0-139">Якщо не задавати цей параметр, від користувачів із передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис, до корпорації Майкрософт надсилаються лише необхідні діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="07da0-139">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="07da0-140">До того ж такі користувачі не зможуть змінювати рівень діагностичних даних, незалежно від того, як ви налаштували цей параметр.</span><span class="sxs-lookup"><span data-stu-id="07da0-140">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="07da0-141">Від інших, зокрема користувачів із передплатою на Office 365 (або Microsoft 365) для дому, надсилаються лише необхідні діагностичні дані (але користувач може на власний розсуд додати ще й необов’язкові дані до розділу **Параметри** > **Параметри конфіденційності**).</span><span class="sxs-lookup"><span data-stu-id="07da0-141">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="07da0-142">Налаштування параметра для підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="07da0-142">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="07da0-143">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="07da0-143">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="07da0-144">Наприклад, Варіанти оформлення в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="07da0-144">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="07da0-145">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="07da0-145">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="07da0-146">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="07da0-146">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="07da0-147">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="07da0-147">**Data Type**</span></span>  | <span data-ttu-id="07da0-148">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="07da0-148">Boolean</span></span> |
|<span data-ttu-id="07da0-149">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="07da0-149">**Possible values**</span></span>  | <span data-ttu-id="07da0-150">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-150">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="07da0-151">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-151">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="07da0-152">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу для аналізу вмісту.</span><span class="sxs-lookup"><span data-stu-id="07da0-152">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="07da0-153">Їх не зможуть вимкнути користувачі з передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="07da0-153">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="07da0-154">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="07da0-154">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="07da0-155">Налаштування параметра для підключених можливостей, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="07da0-155">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="07da0-156">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="07da0-156">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="07da0-157">Наприклад, шаблони Office або вставлення піктограм з Інтернету.</span><span class="sxs-lookup"><span data-stu-id="07da0-157">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="07da0-158">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="07da0-158">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="07da0-159">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="07da0-159">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="07da0-160">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="07da0-160">**Data Type**</span></span>  | <span data-ttu-id="07da0-161">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="07da0-161">Boolean</span></span> |
|<span data-ttu-id="07da0-162">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="07da0-162">**Possible values**</span></span>  | <span data-ttu-id="07da0-163">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-163">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="07da0-164">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-164">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="07da0-165">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу, що завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="07da0-165">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="07da0-166">Їх не зможуть вимкнути користувачі з передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="07da0-166">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="07da0-167">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="07da0-167">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="07da0-168">Налаштування параметра для необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="07da0-168">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="07da0-169">На додачу до згаданих вище пропонуються необов’язкові підключені можливості, до яких можна надати доступ користувачам з обліковим записом організації, також відомим як робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="07da0-169">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="07da0-170">Наприклад, надбудови Office, завантажені на ваш пристрій із Магазину Office.</span><span class="sxs-lookup"><span data-stu-id="07da0-170">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="07da0-171">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей в Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="07da0-171">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="07da0-172">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="07da0-172">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="07da0-173">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="07da0-173">**Data Type**</span></span>  | <span data-ttu-id="07da0-174">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="07da0-174">Boolean</span></span> |
|<span data-ttu-id="07da0-175">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="07da0-175">**Possible values**</span></span>  | <span data-ttu-id="07da0-176">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-176">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="07da0-177">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="07da0-177">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="07da0-178">Якщо не задавати цей параметр, компоненти необов’язкового підключеного функціонала будуть доступні для користувачів із передплатою на Office 365 (або Microsoft 365), які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="07da0-178">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="07da0-179">Якщо ви не задали для цього параметра значення FALSE, такі користувачі можуть вимкнути ці можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="07da0-179">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="07da0-180">Інші, як-от користувачі з передплатою на Office 365 (або Microsoft 365) для дому, не можуть їх вимкнути.</span><span class="sxs-lookup"><span data-stu-id="07da0-180">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>