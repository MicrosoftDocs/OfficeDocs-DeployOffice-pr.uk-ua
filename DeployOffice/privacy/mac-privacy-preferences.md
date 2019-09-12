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
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246334"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="c67f5-103">Налаштування параметрів конфіденційності в Office для Mac</span><span class="sxs-lookup"><span data-stu-id="c67f5-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="c67f5-104">У версії 16.28 (і подальших) Office для Mac включає нові параметри, що дають змогу налаштувати:</span><span class="sxs-lookup"><span data-stu-id="c67f5-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="c67f5-105">збір і надсилання до корпорації Майкрософт ***діагностичних даних*** про клієнтське програмне забезпечення Office;</span><span class="sxs-lookup"><span data-stu-id="c67f5-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="c67f5-106">доступність додаткових хмарних ***підключених можливостей*** Office.</span><span class="sxs-lookup"><span data-stu-id="c67f5-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="c67f5-107">Окрім того, з’явилася змога налаштувати відображення діалогового вікна **Повідомлення про необхідні дані** для засобу автоматичного оновлення (Microsoft AutoUpdate).</span><span class="sxs-lookup"><span data-stu-id="c67f5-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="c67f5-108">Докладні відомості про діагностичні дані та підключені можливості див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="c67f5-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="c67f5-109">Використання подібних параметрів конфіденційності на комп’ютерах із Windows описано в цій [статті про Office 365 ProPlus](manage-privacy-controls.md). </span><span class="sxs-lookup"><span data-stu-id="c67f5-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="c67f5-110">Налаштування параметрів</span><span class="sxs-lookup"><span data-stu-id="c67f5-110">Setting preferences</span></span>

<span data-ttu-id="c67f5-111">Ці нові параметри підтримуються в CFPreferences API. Їх можна налаштувати за допомогою команди `defaults` на Терміналі, у профілі конфігурації або на сервері керування мобільними пристроями (MDM).</span><span class="sxs-lookup"><span data-stu-id="c67f5-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="c67f5-112">Коли параметри застосуються, користувачі не зможуть змінювати значення, і будь-які елементи керування в програмах відображатимуться як неактивні. </span><span class="sxs-lookup"><span data-stu-id="c67f5-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="c67f5-113">Налаштування параметра для діагностичних даних </span><span class="sxs-lookup"><span data-stu-id="c67f5-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="c67f5-114">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="c67f5-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="c67f5-115">Додаткові відомості див. в [цьому розділі](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="c67f5-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-116">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c67f5-117">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="c67f5-118">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-118">**Data Type**</span></span>  | <span data-ttu-id="c67f5-119">Рядок</span><span class="sxs-lookup"><span data-stu-id="c67f5-119">String</span></span> |
|<span data-ttu-id="c67f5-120">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-120">**Possible values**</span></span>  | <span data-ttu-id="c67f5-121">`BasicDiagnosticData` *(установлюється рівень "Необхідні дані")*</span><span class="sxs-lookup"><span data-stu-id="c67f5-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="c67f5-122">`FullDiagnosticData` *(установлюється рівень "Необов’язкові дані")*</span><span class="sxs-lookup"><span data-stu-id="c67f5-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="c67f5-123">`ZeroDiagnosticData` *(установлюється рівень "Немає")*</span><span class="sxs-lookup"><span data-stu-id="c67f5-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="c67f5-124">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-124">**Availability**</span></span> |<span data-ttu-id="c67f5-125">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="c67f5-126">Якщо налаштувати цей параметр, він також застосовуватиметься до таких продуктів:</span><span class="sxs-lookup"><span data-stu-id="c67f5-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="c67f5-127">Teams для Mac версії 1.00.217856 і новіших;</span><span class="sxs-lookup"><span data-stu-id="c67f5-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="c67f5-128">Skype для бізнесу для Mac версії 16.28 і новіших.</span><span class="sxs-lookup"><span data-stu-id="c67f5-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="c67f5-129">Якщо не задавати цей параметр, від користувачів із передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачів Office 2019 для Mac за корпоративною ліцензією до корпорації Майкрософт надсилаються як необхідні, так і необов’язкові діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="c67f5-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="c67f5-130">До того ж, такі користувачі не зможуть змінювати рівень діагностичних даних незалежно від того, як ви налаштували цей параметр.</span><span class="sxs-lookup"><span data-stu-id="c67f5-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="c67f5-131">Від інших, як-от домашніх користувачів із передплатою на Office 365, надсилаються лише необхідні діагностичні дані (але користувач може на власний розсуд додати ще й необов’язкові дані в розділі **Параметри** > **Конфіденційність**).</span><span class="sxs-lookup"><span data-stu-id="c67f5-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="c67f5-132">Налаштування параметра для підключених можливостей, які аналізують вміст</span><span class="sxs-lookup"><span data-stu-id="c67f5-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="c67f5-133">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="c67f5-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="c67f5-134">Зокрема, до них належать Дизайнер PowerPoint і Дослідник у Word.</span><span class="sxs-lookup"><span data-stu-id="c67f5-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="c67f5-135">Перелік див. в статті [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c67f5-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-136">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c67f5-137">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="c67f5-138">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-138">**Data Type**</span></span>  | <span data-ttu-id="c67f5-139">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c67f5-139">Boolean</span></span> |
|<span data-ttu-id="c67f5-140">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-140">**Possible values**</span></span>  | <span data-ttu-id="c67f5-141">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c67f5-142">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c67f5-143">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-143">**Availability**</span></span> |<span data-ttu-id="c67f5-144">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-144">16.28 and later</span></span> |

<span data-ttu-id="c67f5-145">Якщо не задавати цей параметр, підключені можливості, що аналізують вміст, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="c67f5-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="c67f5-146">Їх не зможуть вимикати користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c67f5-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="c67f5-147">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c67f5-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="c67f5-148">Налаштування параметра для підключених можливостей, що завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="c67f5-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="c67f5-149">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, об’ємні моделі, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="c67f5-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="c67f5-150">Наприклад, шаблони Office або компонувальник презентації PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c67f5-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="c67f5-151">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c67f5-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-152">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c67f5-153">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="c67f5-154">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-154">**Data Type**</span></span>  | <span data-ttu-id="c67f5-155">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c67f5-155">Boolean</span></span> |
|<span data-ttu-id="c67f5-156">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-156">**Possible values**</span></span>  | <span data-ttu-id="c67f5-157">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c67f5-158">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c67f5-159">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-159">**Availability**</span></span> |<span data-ttu-id="c67f5-160">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-160">16.28 and later</span></span> |

<span data-ttu-id="c67f5-161">Якщо не задавати цей параметр, підключені можливості, що завантажують вміст із мережі, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="c67f5-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="c67f5-162">Їх не зможуть вимикати користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c67f5-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="c67f5-163">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути такі можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c67f5-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="c67f5-164">Налаштування параметра для необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="c67f5-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="c67f5-165">На додачу до згаданих вище пропонуються необов’язкові підключені можливості, до яких можна надати доступ користувачам із робочим або навчальним обліковим записом.</span><span class="sxs-lookup"><span data-stu-id="c67f5-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="c67f5-166">Зокрема, до них належать Укладач резюме у Word (на основі LinkedIn) і Панель погоди в Outlook (на основі служби "MSN Погода").</span><span class="sxs-lookup"><span data-stu-id="c67f5-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="c67f5-167">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c67f5-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-168">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c67f5-169">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="c67f5-170">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-170">**Data Type**</span></span>  | <span data-ttu-id="c67f5-171">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c67f5-171">Boolean</span></span> |
|<span data-ttu-id="c67f5-172">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-172">**Possible values**</span></span>  | <span data-ttu-id="c67f5-173">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c67f5-174">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c67f5-175">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-175">**Availability**</span></span> |<span data-ttu-id="c67f5-176">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-176">16.28 and later</span></span> |

<span data-ttu-id="c67f5-177">Якщо не задавати цей параметр, необов’язкові підключені можливості доступні користувачам із передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачам Office 2019 для Mac за корпоративною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="c67f5-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="c67f5-178">Якщо ви не задали для цього параметра значення `FALSE`, такі користувачі можуть вимкнути ці можливості в розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c67f5-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="c67f5-179">Інші, як-от домашні користувачі з передплатою на Office 365, не можуть їх вимкнути.</span><span class="sxs-lookup"><span data-stu-id="c67f5-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="c67f5-180">Налаштування параметра для основного переліку підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="c67f5-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="c67f5-181">Цей параметр дає змогу регулювати доступ користувачів до більшості підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="c67f5-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-182">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="c67f5-183">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="c67f5-184">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-184">**Data Type**</span></span>  | <span data-ttu-id="c67f5-185">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="c67f5-185">Boolean</span></span> |
|<span data-ttu-id="c67f5-186">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-186">**Possible values**</span></span>  | <span data-ttu-id="c67f5-187">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c67f5-188">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="c67f5-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="c67f5-189">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-189">**Availability**</span></span> |<span data-ttu-id="c67f5-190">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-190">16.28 and later</span></span> |

<span data-ttu-id="c67f5-191">Якщо не задавати цей параметр, користувачам доступні всі підключені можливості (хіба що ви налаштували якийсь з описаних вище параметрів, як-от `OfficeExperiencesAnalyzingContentPreference`).</span><span class="sxs-lookup"><span data-stu-id="c67f5-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="c67f5-192">Наприклад, ви можете налаштувати значення `FALSE`, щоб вимкнути для користувачів указане нижче.</span><span class="sxs-lookup"><span data-stu-id="c67f5-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="c67f5-193">Можливості, які аналізують ваш вміст</span><span class="sxs-lookup"><span data-stu-id="c67f5-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="c67f5-194">Можливості, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="c67f5-194">Experiences that download online content</span></span>
- <span data-ttu-id="c67f5-195">Необов'язкові підключені можливості</span><span class="sxs-lookup"><span data-stu-id="c67f5-195">Optional connected experiences</span></span>

<span data-ttu-id="c67f5-196">Також значення `FALSE` вимикає більшість інших підключених можливостей, як-от співавторства та файлового онлайн-сховища.</span><span class="sxs-lookup"><span data-stu-id="c67f5-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="c67f5-197">Перелік див. в статті [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c67f5-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="c67f5-198">Утім, навіть зі значенням `FALSE` обмежені функціональні можливості Office (зокрема синхронізація поштової скриньки в Outlook), Teams і "Skype для бізнесу" працюватимуть далі.</span><span class="sxs-lookup"><span data-stu-id="c67f5-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="c67f5-199">[Базові служби](essential-services.md), як-от служба ліцензування, що підтверджує наявність чинної ліцензії на Office, також залишатимуться доступними.</span><span class="sxs-lookup"><span data-stu-id="c67f5-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="c67f5-200">Користувачі з передплатою на Office 365, що ввійшли в робочий або навчальний обліковий запис, і користувачі Office 2019 для Mac за корпоративною ліцензією не можуть вимикати основний перелік підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="c67f5-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="c67f5-201">Інші, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути їх у розділі **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="c67f5-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="c67f5-202">Налаштування параметра "Повідомлення про необхідні дані" для Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="c67f5-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="c67f5-203">Під час першого запуску Microsoft AutoUpdate версії 4.12 або новіших користувачам відображається діалогове вікно **Повідомлення про необхідні дані**. Воно інформує про відомості, що надсилаються до корпорації Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="c67f5-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="c67f5-204">Якщо ви не хочете, щоб ваші користувачі бачили **Повідомлення про необхідні дані**, налаштуйте описаний нижче параметр.</span><span class="sxs-lookup"><span data-stu-id="c67f5-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="c67f5-205">Незалежно від обраного значення діалогове вікно не відображатиметься користувачам.</span><span class="sxs-lookup"><span data-stu-id="c67f5-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c67f5-206">**Preference Domain (Домен параметрів)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="c67f5-207">**Key (Ключ)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="c67f5-208">**Data Type (Тип даних)**</span><span class="sxs-lookup"><span data-stu-id="c67f5-208">**Data Type**</span></span>  | <span data-ttu-id="c67f5-209">Рядок</span><span class="sxs-lookup"><span data-stu-id="c67f5-209">String</span></span> |
|<span data-ttu-id="c67f5-210">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="c67f5-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="c67f5-211">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="c67f5-211">**Availability**</span></span> |<span data-ttu-id="c67f5-212">4.12 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="c67f5-212">4.12 and later</span></span> |

<span data-ttu-id="c67f5-213">Якщо користувач перегляне це діалогове вікно й натисне в ньому кнопку **OK**, для ключа `AcknowledgedDataCollectionPolicy` запишеться значення `RequiredDataOnly`. Надалі це вікно користувачеві не відображатиметься.</span><span class="sxs-lookup"><span data-stu-id="c67f5-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="c67f5-214">Пов’язані теми</span><span class="sxs-lookup"><span data-stu-id="c67f5-214">Related topics</span></span>

- [<span data-ttu-id="c67f5-215">Довідник із профілів конфігурації (документація розробника Apple)</span><span class="sxs-lookup"><span data-stu-id="c67f5-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="c67f5-216">Параметри розгортання Office для Mac</span><span class="sxs-lookup"><span data-stu-id="c67f5-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="c67f5-217">Параметри конфіденційності облікового запису</span><span class="sxs-lookup"><span data-stu-id="c67f5-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
