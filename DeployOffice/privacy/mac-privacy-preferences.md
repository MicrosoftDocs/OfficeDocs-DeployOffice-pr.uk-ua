---
title: Налаштування параметрів конфіденційності в Office для Mac
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
description: 'З цієї статті адміністратори Office можуть дізнатися, як налаштувати елементи керування конфіденційністю в Office для Mac. '
hideEdit: true
ms.openlocfilehash: a1fdd9f7d0fe2095b3a32f61f885f724f2259188
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510234"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="c35b6-103">Налаштування параметрів конфіденційності в Office для Mac</span><span class="sxs-lookup"><span data-stu-id="c35b6-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="c35b6-104">У версії 16.28 (і подальших) Office для Mac включає нові параметри, що дають змогу налаштувати:</span><span class="sxs-lookup"><span data-stu-id="c35b6-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="c35b6-105">збір і надсилання до корпорації Майкрософт ***діагностичних даних*** про клієнтське програмне забезпечення Office;</span><span class="sxs-lookup"><span data-stu-id="c35b6-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="c35b6-106">доступність додаткових хмарних ***підключених можливостей*** Office.</span><span class="sxs-lookup"><span data-stu-id="c35b6-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="c35b6-107">Окрім того, з’явилася змога налаштувати відображення діалогового вікна **Повідомлення про необхідні дані** для засобу автоматичного оновлення (Microsoft AutoUpdate).</span><span class="sxs-lookup"><span data-stu-id="c35b6-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="c35b6-108">Докладні відомості про діагностичні дані та компоненти підключеного функціоналу див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> - <span data-ttu-id="c35b6-109">Використання подібних параметрів на комп’ютерах із Windows описано в цій [статті про Office 365 ProPlus](manage-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md).</span></span>
> - <span data-ttu-id="c35b6-110">Використання подібних параметрів Office на пристроях з iOS описано в [цій статті](ios-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-110">For information about similar settings for Office on iOS devices, see [Use preferences to manage privacy controls for Office on iOS devices](ios-privacy-preferences.md).</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="c35b6-111">Налаштування параметрів</span><span class="sxs-lookup"><span data-stu-id="c35b6-111">Setting preferences</span></span>

<span data-ttu-id="c35b6-112">Ці нові параметри підтримуються в CFPreferences API. Їх можна налаштувати за допомогою команди `defaults` на Терміналі, у профілі конфігурації або на сервері керування мобільними пристроями (MDM).</span><span class="sxs-lookup"><span data-stu-id="c35b6-112">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="c35b6-113">Коли параметри застосуються, користувачі не зможуть змінювати значення, і будь-які елементи керування в програмах відображатимуться як неактивні. </span><span class="sxs-lookup"><span data-stu-id="c35b6-113">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="c35b6-114">Налаштування параметра для діагностичних даних </span><span class="sxs-lookup"><span data-stu-id="c35b6-114">Policy setting for diagnostic data</span></span>

<span data-ttu-id="c35b6-115">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="c35b6-115">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="c35b6-116">Додаткові відомості див. в [цьому розділі](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="c35b6-116">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-117">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-117">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c35b6-118">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-118">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="c35b6-119">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-119">**Data Type**</span></span>  | <span data-ttu-id="c35b6-120">Рядок</span><span class="sxs-lookup"><span data-stu-id="c35b6-120">String</span></span> |
|<span data-ttu-id="c35b6-121">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-121">**Possible values**</span></span>  | <span data-ttu-id="c35b6-122">`BasicDiagnosticData` *(установлюється рівень "Необхідні дані")*</span><span class="sxs-lookup"><span data-stu-id="c35b6-122">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="c35b6-123">`FullDiagnosticData` *(установлюється рівень "Необов’язкові дані")*</span><span class="sxs-lookup"><span data-stu-id="c35b6-123">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="c35b6-124">`ZeroDiagnosticData` *(установлюється рівень "Немає")*</span><span class="sxs-lookup"><span data-stu-id="c35b6-124">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="c35b6-125">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-125">**Availability**</span></span> |<span data-ttu-id="c35b6-126">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-126">16.28 and later</span></span> |

<span data-ttu-id="c35b6-127">Якщо не задавати цей параметр, у нових інсталяціях версії 16.30 (і подальших) від користувачів із передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачів Office 2019 для Mac за корпоративною ліцензією до корпорації Майкрософт надсилаються тільки необхідні діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="c35b6-127">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="c35b6-128">До того ж, такі користувачі не зможуть змінювати рівень діагностичних даних незалежно від того, як ви налаштували цей параметр.</span><span class="sxs-lookup"><span data-stu-id="c35b6-128">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

> [!NOTE]
> - <span data-ttu-id="c35b6-129">Якщо ви інсталюєте версію 16.28 або 16.29 і не налаштуєте цей параметр, до корпорації Майкрософт надсилатимуться як необхідні, так і необов’язкові діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="c35b6-129">If you install Version 16.28 or 16.29 and you don't set this preference, both optional and required diagnostic data is sent to Microsoft.</span></span> <span data-ttu-id="c35b6-130">Якщо пізніше ви перейдете до версії 16.30 або новішої й не зміните значення параметра, до корпорації Майкрософт і надалі надсилатимуться як необхідні, так і необов’язкові діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="c35b6-130">If you then upgrade to Version 16.30 or later, both optional and required diagnostic data is still sent to Microsoft, unless you use this preference to set a different value.</span></span>
> - <span data-ttu-id="c35b6-131">Якщо ви налаштуєте цей параметр, він також застосовуватиметься для Teams для Mac (версії 1.00.217856 і новіших) та Skype для бізнесу для Mac (версії 16.28 і новіших).</span><span class="sxs-lookup"><span data-stu-id="c35b6-131">If you set this preference, it also will apply to Version 1.00.217856 and later of Teams for Mac and to Version 16.28 and later of Skype for Business for Mac.</span></span>

<span data-ttu-id="c35b6-132">Від інших, як-от домашніх користувачів із передплатою на Office 365, надсилаються лише необхідні діагностичні дані (але користувач може на власний розсуд додати ще й необов’язкові дані в розділі **Параметри** > **Конфіденційність**).</span><span class="sxs-lookup"><span data-stu-id="c35b6-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="c35b6-133">Налаштування параметра для підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="c35b6-133">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="c35b6-134">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="c35b6-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="c35b6-135">Зокрема, до них належать Дизайнер PowerPoint і Дослідник у Word.</span><span class="sxs-lookup"><span data-stu-id="c35b6-135">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="c35b6-136">Перелік див. в статті [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-137">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-137">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c35b6-138">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-138">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="c35b6-139">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-139">**Data Type**</span></span>  | <span data-ttu-id="c35b6-140">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c35b6-140">Boolean</span></span> |
|<span data-ttu-id="c35b6-141">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-141">**Possible values**</span></span>  | <span data-ttu-id="c35b6-142">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-142">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c35b6-143">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-143">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c35b6-144">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-144">**Availability**</span></span> |<span data-ttu-id="c35b6-145">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-145">16.28 and later</span></span> |

<span data-ttu-id="c35b6-146">Якщо не задавати цей параметр, підключені можливості, що аналізують вміст, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="c35b6-146">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="c35b6-147">Їх не зможуть вимикати користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c35b6-147">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="c35b6-148">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c35b6-148">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="c35b6-149">Налаштування параметра для підключених можливостей, що завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="c35b6-149">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="c35b6-150">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, об’ємні моделі, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="c35b6-150">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="c35b6-151">Наприклад, шаблони Office або компонувальник презентації PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c35b6-151">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="c35b6-152">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-152">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-153">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-153">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c35b6-154">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-154">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="c35b6-155">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-155">**Data Type**</span></span>  | <span data-ttu-id="c35b6-156">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c35b6-156">Boolean</span></span> |
|<span data-ttu-id="c35b6-157">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-157">**Possible values**</span></span>  | <span data-ttu-id="c35b6-158">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-158">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c35b6-159">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-159">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c35b6-160">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-160">**Availability**</span></span> |<span data-ttu-id="c35b6-161">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-161">16.28 and later</span></span> |

<span data-ttu-id="c35b6-162">Якщо не задавати цей параметр, підключені можливості, що завантажують вміст із мережі, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="c35b6-162">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="c35b6-163">Їх не зможуть вимикати користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c35b6-163">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="c35b6-164">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c35b6-164">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="c35b6-165">Налаштування параметра для необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="c35b6-165">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="c35b6-166">На додачу до згаданих вище пропонуються необов’язкові підключені можливості, до яких можна надати доступ користувачам із робочим або навчальним обліковим записом.</span><span class="sxs-lookup"><span data-stu-id="c35b6-166">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="c35b6-167">Зокрема, до них належать Укладач резюме у Word (на основі LinkedIn) і Панель погоди в Outlook (на основі служби "MSN Погода").</span><span class="sxs-lookup"><span data-stu-id="c35b6-167">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="c35b6-168">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-168">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-169">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-169">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c35b6-170">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-170">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="c35b6-171">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-171">**Data Type**</span></span>  | <span data-ttu-id="c35b6-172">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c35b6-172">Boolean</span></span> |
|<span data-ttu-id="c35b6-173">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-173">**Possible values**</span></span>  | <span data-ttu-id="c35b6-174">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-174">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c35b6-175">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-175">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c35b6-176">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-176">**Availability**</span></span> |<span data-ttu-id="c35b6-177">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-177">16.28 and later</span></span> |

<span data-ttu-id="c35b6-178">Якщо не задавати цей параметр, необов’язкові підключені можливості доступні користувачам із передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачам Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c35b6-178">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="c35b6-179">Якщо ви не задали для цього параметра значення `FALSE`, такі користувачі можуть вимкнути ці можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c35b6-179">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="c35b6-180">Інші, як-от домашні користувачі з передплатою на Office 365, не можуть їх вимкнути.</span><span class="sxs-lookup"><span data-stu-id="c35b6-180">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="c35b6-181">Налаштування параметра для основного переліку підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="c35b6-181">Policy setting for most connected experiences</span></span>

<span data-ttu-id="c35b6-182">Цей параметр дає змогу регулювати доступ користувачів до більшості підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="c35b6-182">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-183">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-183">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c35b6-184">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-184">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="c35b6-185">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-185">**Data Type**</span></span>  | <span data-ttu-id="c35b6-186">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c35b6-186">Boolean</span></span> |
|<span data-ttu-id="c35b6-187">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-187">**Possible values**</span></span>  | <span data-ttu-id="c35b6-188">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-188">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c35b6-189">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c35b6-189">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c35b6-190">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-190">**Availability**</span></span> |<span data-ttu-id="c35b6-191">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-191">16.28 and later</span></span> |

<span data-ttu-id="c35b6-192">Якщо не задавати цей параметр, користувачам доступні всі підключені можливості (хіба що ви налаштували якийсь з описаних вище параметрів, як-от `OfficeExperiencesAnalyzingContentPreference`).</span><span class="sxs-lookup"><span data-stu-id="c35b6-192">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="c35b6-193">Наприклад, ви можете налаштувати значення `FALSE`, щоб вимкнути для користувачів указане нижче.</span><span class="sxs-lookup"><span data-stu-id="c35b6-193">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="c35b6-194">Можливості, які аналізують ваш вміст</span><span class="sxs-lookup"><span data-stu-id="c35b6-194">Experiences that analyze your content</span></span>
- <span data-ttu-id="c35b6-195">Можливості, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="c35b6-195">Experiences that download online content</span></span>
- <span data-ttu-id="c35b6-196">Необов'язкові підключені можливості</span><span class="sxs-lookup"><span data-stu-id="c35b6-196">Optional connected experiences</span></span>

<span data-ttu-id="c35b6-197">Також значення `FALSE` вимикає більшість інших підключених можливостей, як-от співавторства та файлового онлайн-сховища.</span><span class="sxs-lookup"><span data-stu-id="c35b6-197">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="c35b6-198">Перелік див. в статті [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c35b6-198">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="c35b6-199">Утім, навіть зі значенням `FALSE` обмежені функціональні можливості Office (зокрема синхронізація поштової скриньки в Outlook), Teams і "Skype для бізнесу" працюватимуть далі.</span><span class="sxs-lookup"><span data-stu-id="c35b6-199">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="c35b6-200">[Базові служби](essential-services.md), як-от служба ліцензування, що підтверджує наявність чинної ліцензії на Office, також залишатимуться доступними.</span><span class="sxs-lookup"><span data-stu-id="c35b6-200">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="c35b6-201">Користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією не можуть вимикати основний перелік підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="c35b6-201">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="c35b6-202">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути їх у розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c35b6-202">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="c35b6-203">Налаштування параметра "Повідомлення про необхідні дані" для Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="c35b6-203">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="c35b6-204">Під час першого запуску Microsoft AutoUpdate версії 4.12 або новіших користувачам відображається діалогове вікно **Повідомлення про необхідні дані**. Воно інформує про відомості, що надсилаються до корпорації Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="c35b6-204">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="c35b6-205">Якщо ви не хочете, щоб ваші користувачі бачили **Повідомлення про необхідні дані**, налаштуйте описаний нижче параметр.</span><span class="sxs-lookup"><span data-stu-id="c35b6-205">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="c35b6-206">Незалежно від обраного значення діалогове вікно не відображатиметься користувачам.</span><span class="sxs-lookup"><span data-stu-id="c35b6-206">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c35b6-207">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-207">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="c35b6-208">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-208">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="c35b6-209">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c35b6-209">**Data Type**</span></span>  | <span data-ttu-id="c35b6-210">Рядок</span><span class="sxs-lookup"><span data-stu-id="c35b6-210">String</span></span> |
|<span data-ttu-id="c35b6-211">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c35b6-211">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="c35b6-212">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c35b6-212">**Availability**</span></span> |<span data-ttu-id="c35b6-213">4.12 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c35b6-213">4.12 and later</span></span> |

<span data-ttu-id="c35b6-214">Якщо користувач перегляне це діалогове вікно й натисне в ньому кнопку **OK**, для ключа `AcknowledgedDataCollectionPolicy` запишеться значення `RequiredDataOnly`. Надалі це вікно користувачеві не відображатиметься.</span><span class="sxs-lookup"><span data-stu-id="c35b6-214">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="c35b6-215">Пов’язані теми</span><span class="sxs-lookup"><span data-stu-id="c35b6-215">Related topics</span></span>

- [<span data-ttu-id="c35b6-216">Довідник із профілів конфігурації (документація розробника Apple)</span><span class="sxs-lookup"><span data-stu-id="c35b6-216">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="c35b6-217">Параметри розгортання Office для Mac</span><span class="sxs-lookup"><span data-stu-id="c35b6-217">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="c35b6-218">Параметри конфіденційності облікового запису</span><span class="sxs-lookup"><span data-stu-id="c35b6-218">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
