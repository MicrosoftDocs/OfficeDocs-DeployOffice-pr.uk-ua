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
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604304"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="6444b-103">Параметри налаштування елементів керування конфіденційністю в Office на пристроях з iOS</span><span class="sxs-lookup"><span data-stu-id="6444b-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="6444b-104">Office на пристроях з iOS включає нові параметри, що дають змогу налаштувати:</span><span class="sxs-lookup"><span data-stu-id="6444b-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="6444b-105">збір і надсилання до корпорації Майкрософт ***діагностичних даних*** про клієнтське програмне забезпечення Office;</span><span class="sxs-lookup"><span data-stu-id="6444b-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="6444b-106">доступність додаткових хмарних ***підключених можливостей*** Office.</span><span class="sxs-lookup"><span data-stu-id="6444b-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="6444b-107">Докладні відомості про діагностичні дані та компоненти підключеного функціоналу див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="6444b-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="6444b-108">Ці параметри застосовуються до таких програм:</span><span class="sxs-lookup"><span data-stu-id="6444b-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="6444b-109">Word для iOS, Excel для iOS і PowerPoint для iOS версії 2.30 і новіших;</span><span class="sxs-lookup"><span data-stu-id="6444b-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="6444b-110">OneNote для iOS версії 16.30 і новіших;</span><span class="sxs-lookup"><span data-stu-id="6444b-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="6444b-111">Переглядач Visio для iOS версії 1.17 і новіших.</span><span class="sxs-lookup"><span data-stu-id="6444b-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="6444b-112">Використання подібних параметрів на комп’ютерах із macOS описано в цій [статті про Office для Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="6444b-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="6444b-113">Налаштування параметрів для пристроїв</span><span class="sxs-lookup"><span data-stu-id="6444b-113">Setting device preferences</span></span>
<span data-ttu-id="6444b-114">Ці нові параметри також можна задати на рівні пристрою на сервері керування мобільними пристроями (MDM), якщо інстальовано програму Office.</span><span class="sxs-lookup"><span data-stu-id="6444b-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="6444b-115">Багато серверів MDM дозволяють ІТ-адміністраторам додати словник конфігурації, якщо сервер надсилає MDM-команду `InstallApplication` на пристрій з iOS.</span><span class="sxs-lookup"><span data-stu-id="6444b-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="6444b-116">Докладні відомості див. в документації сервера MDM.</span><span class="sxs-lookup"><span data-stu-id="6444b-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="6444b-117">Словник являє собою набір пар "ключ-значення" у форматі XML.</span><span class="sxs-lookup"><span data-stu-id="6444b-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="6444b-118">Наприклад,</span><span class="sxs-lookup"><span data-stu-id="6444b-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="6444b-119">надісланий на пристрій словник конфігурації матиме ключ `com.apple.managed.configuration` і буде зчитаний під час запуску програми Office.</span><span class="sxs-lookup"><span data-stu-id="6444b-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="6444b-120">Налаштування параметра для діагностичних даних </span><span class="sxs-lookup"><span data-stu-id="6444b-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="6444b-121">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="6444b-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="6444b-122">Додаткові відомості див. в статті [Діагностичні дані, надіслані з Office 365 ProPlus до корпорації Майкрософт](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="6444b-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6444b-123">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="6444b-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="6444b-124">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="6444b-124">**Data Type**</span></span>  | <span data-ttu-id="6444b-125">Рядок</span><span class="sxs-lookup"><span data-stu-id="6444b-125">String</span></span> |
|<span data-ttu-id="6444b-126">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="6444b-126">**Possible values**</span></span>  | <span data-ttu-id="6444b-127">`BasicDiagnosticData` *(установлюється рівень "Необхідні дані")*</span><span class="sxs-lookup"><span data-stu-id="6444b-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="6444b-128">`FullDiagnosticData` *(установлюється рівень "Необов’язкові дані")*</span><span class="sxs-lookup"><span data-stu-id="6444b-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="6444b-129">`ZeroDiagnosticData` *(установлюється рівень "Немає")*</span><span class="sxs-lookup"><span data-stu-id="6444b-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="6444b-130">Якщо не задавати цей параметр, від користувачів із передплатою на Office 365, які ввійшли в робочий або навчальний обліковий запис, до корпорації Майкрософт надсилаються лише необхідні діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="6444b-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="6444b-131">До того ж, такі користувачі не зможуть змінювати рівень діагностичних даних незалежно від того, як ви налаштували цей параметр.</span><span class="sxs-lookup"><span data-stu-id="6444b-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="6444b-132">Від інших, як-от домашніх користувачів із передплатою на Office 365, надсилаються лише необхідні діагностичні дані (але користувач може на власний розсуд додати ще й необов’язкові дані в розділі **Параметри** > **Параметри конфіденційності**).</span><span class="sxs-lookup"><span data-stu-id="6444b-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="6444b-133">Налаштування параметра для підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="6444b-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="6444b-134">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="6444b-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="6444b-135">Наприклад, Варіанти оформлення в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="6444b-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="6444b-136">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6444b-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6444b-137">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="6444b-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="6444b-138">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="6444b-138">**Data Type**</span></span>  | <span data-ttu-id="6444b-139">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="6444b-139">Boolean</span></span> |
|<span data-ttu-id="6444b-140">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="6444b-140">**Possible values**</span></span>  | <span data-ttu-id="6444b-141">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6444b-142">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="6444b-143">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу для аналізу вмісту.</span><span class="sxs-lookup"><span data-stu-id="6444b-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="6444b-144">Їх не зможуть вимкнути користувачі з передплатою на Office 365, які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="6444b-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="6444b-145">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="6444b-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="6444b-146">Налаштування параметра для підключених можливостей, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="6444b-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="6444b-147">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="6444b-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="6444b-148">Наприклад, шаблони Office або вставлення піктограм з Інтернету.</span><span class="sxs-lookup"><span data-stu-id="6444b-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="6444b-149">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6444b-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6444b-150">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="6444b-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="6444b-151">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="6444b-151">**Data Type**</span></span>  | <span data-ttu-id="6444b-152">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="6444b-152">Boolean</span></span> |
|<span data-ttu-id="6444b-153">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="6444b-153">**Possible values**</span></span>  | <span data-ttu-id="6444b-154">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6444b-155">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="6444b-156">Якщо не задавати цей параметр, користувачі матимуть доступ до компонентів підключеного функціоналу, що завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="6444b-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="6444b-157">Їх не зможуть вимкнути користувачі з передплатою на Office 365, які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="6444b-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="6444b-158">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="6444b-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="6444b-159">Налаштування параметра для необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="6444b-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="6444b-160">На додачу до згаданих вище пропонуються необов’язкові підключені можливості, до яких можна надати доступ користувачам з обліковим записом організації, також відомим як робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="6444b-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="6444b-161">Наприклад, надбудови Office, завантажені на ваш пристрій із Магазину Office.</span><span class="sxs-lookup"><span data-stu-id="6444b-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="6444b-162">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей в Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6444b-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6444b-163">**Ключ**</span><span class="sxs-lookup"><span data-stu-id="6444b-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="6444b-164">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="6444b-164">**Data Type**</span></span>  | <span data-ttu-id="6444b-165">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="6444b-165">Boolean</span></span> |
|<span data-ttu-id="6444b-166">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="6444b-166">**Possible values**</span></span>  | <span data-ttu-id="6444b-167">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6444b-168">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="6444b-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="6444b-169">Якщо не задавати цей параметр, компоненти необов’язкового підключеного функціоналу будуть доступні для користувачів із передплатою на Office 365, які ввійшли в робочий або навчальний обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="6444b-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="6444b-170">Якщо ви не задали для цього параметра значення FALSE, такі користувачі можуть вимкнути ці можливості в розділі **Параметри** > **Параметри конфіденційності**.</span><span class="sxs-lookup"><span data-stu-id="6444b-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="6444b-171">Інші, як-от домашні користувачі з передплатою на Office 365, не зможуть їх вимкнути.</span><span class="sxs-lookup"><span data-stu-id="6444b-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>