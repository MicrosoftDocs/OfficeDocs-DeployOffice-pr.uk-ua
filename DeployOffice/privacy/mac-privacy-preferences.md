---
title: Параметри налаштування елементів керування конфіденційністю в Office для Mac
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
description: Ця стаття пропонує адміністраторам Office інформацію про налаштування елементів керування конфіденційністю в Office для Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246334"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="0558a-103">Параметри налаштування елементів керування конфіденційністю в Office для Mac</span><span class="sxs-lookup"><span data-stu-id="0558a-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="0558a-104">Починаючи з версії 16.28 в Office для Mac, з’явилися нові параметри налаштування, що дають змогу керувати параметрами, пов'язаними з:</span><span class="sxs-lookup"><span data-stu-id="0558a-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="0558a-105">***діагностичними даними*** про використовуване клієнтське програмне забезпечення Office, які збираються та надсилаються до корпорації Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="0558a-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="0558a-106">***підключеними можливостями*** які використовують хмарні функції, що надають розширені можливості Office вам та вашим користувачам.</span><span class="sxs-lookup"><span data-stu-id="0558a-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="0558a-107">Окрім того, у діалоговому вікні автоматичного оновлення Microsoft (МАУ) з'явився новий параметр налаштування, пов'язаний з **повідомленням про обов'язкові дані**.</span><span class="sxs-lookup"><span data-stu-id="0558a-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="0558a-108">Докладні відомості про діагностичні дані та підключені можливості див. у статті[Огляд елементів керування](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="0558a-109">Докладні відомості про використання подібних параметрів Office для комп’ютерів з Windows див. у статті [Використання параметрів політики для налаштування елементів керування конфіденційністю в Office 365 ProPlus](manage-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="0558a-110">Налаштування параметрів</span><span class="sxs-lookup"><span data-stu-id="0558a-110">Setting preferences</span></span>

<span data-ttu-id="0558a-111">Ці нові параметри налаштування підтримують CFPreferences API, і їх можна налаштувати за допомогою `defaults` команди в терміналі або на сервері конфігурації чи керування мобільними пристроями.</span><span class="sxs-lookup"><span data-stu-id="0558a-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="0558a-112">Коли параметри застосуються, користувач не може змінити значення, і будь-які елементи керування в програмах відобразяться неактивними.</span><span class="sxs-lookup"><span data-stu-id="0558a-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="0558a-113">Параметри налаштування для діагностичних даних</span><span class="sxs-lookup"><span data-stu-id="0558a-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="0558a-114">Діагностичні дані служать для підтримання безпеки та актуальності Office, виявлення, діагностування та вирішення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="0558a-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="0558a-115">Докладні відомості див. в [Діагностичні дані надіслані з Office 365 ProPlus до корпорації Майкрософт](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="0558a-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-116">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="0558a-117">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="0558a-118">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-118">**Data Type**</span></span>  | <span data-ttu-id="0558a-119">Рядок</span><span class="sxs-lookup"><span data-stu-id="0558a-119">String</span></span> |
|<span data-ttu-id="0558a-120">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-120">**Possible values**</span></span>  | <span data-ttu-id="0558a-121">`BasicDiagnosticData` *(установлюється обов'язковий рівень)*</span><span class="sxs-lookup"><span data-stu-id="0558a-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="0558a-122">`FullDiagnosticData` *(установлюється необов'язковий рівень)*</span><span class="sxs-lookup"><span data-stu-id="0558a-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="0558a-123">`ZeroDiagnosticData` *(установлюється рівень «Немає»)*</span><span class="sxs-lookup"><span data-stu-id="0558a-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="0558a-124">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-124">**Availability**</span></span> |<span data-ttu-id="0558a-125">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="0558a-126">Якщо вибрати цей параметр, його також буде застосовано до наведених нижче продуктів:</span><span class="sxs-lookup"><span data-stu-id="0558a-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="0558a-127">Версія 1.00.217856 і новіші версії Teams для Mac</span><span class="sxs-lookup"><span data-stu-id="0558a-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="0558a-128">Версія 16.28 і новіші версії Skype для бізнесу для Mac</span><span class="sxs-lookup"><span data-stu-id="0558a-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="0558a-129">Якщо цей параметр не задано, корпорації Майкрософт надсилаються і обов'язкові, і необов'язкові діагностичні дані, якщо користувачі з передплатою на Office 365 ввійшли в службу, використовуючи робочий або навчальний обліковий запис, або якщо для користувачів інстальовано ліцензійну версію Office 2019 для Mac.</span><span class="sxs-lookup"><span data-stu-id="0558a-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="0558a-130">Крім того, ці користувачі не зможуть змінювати рівень діагностичних даних незалежно від того, які параметри ви задали.</span><span class="sxs-lookup"><span data-stu-id="0558a-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="0558a-131">Для інших користувачів, як-от домашніх користувачів з передплатою на Office 365, надсилаються лише обов'язкові діагностичні дані, якщо користувач не хоче надсилати необов'язкові діагностичні дані, зазначивши це в **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="0558a-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="0558a-132">Параметри налаштувань для підключених можливостей, які аналізують ваш вміст</span><span class="sxs-lookup"><span data-stu-id="0558a-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="0558a-133">Підключені можливості аналізу вмісту вивчають ваш вміст Office і надають рекомендації щодо дизайну, пропозиції з редагування, висновки про дані та виконують інші подібні функції.</span><span class="sxs-lookup"><span data-stu-id="0558a-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="0558a-134">Наприклад, Дизайнер PowerPoint або Редактор у Word.</span><span class="sxs-lookup"><span data-stu-id="0558a-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="0558a-135">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-136">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="0558a-137">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="0558a-138">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-138">**Data Type**</span></span>  | <span data-ttu-id="0558a-139">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="0558a-139">Boolean</span></span> |
|<span data-ttu-id="0558a-140">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-140">**Possible values**</span></span>  | <span data-ttu-id="0558a-141">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0558a-142">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="0558a-143">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-143">**Availability**</span></span> |<span data-ttu-id="0558a-144">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-144">16.28 and later</span></span> |

<span data-ttu-id="0558a-145">Якщо цей параметр не задано, підключені можливості, що аналізують вміст, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="0558a-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="0558a-146">Якщо користувач має передплату на Office 365 і ввійшов в робочий або навчальний обліковий запис, або якщо він має ліцензію на службу Office 2019 для Mac, користувач не зможе вимкнути підключені можливості, що аналізують вміст.</span><span class="sxs-lookup"><span data-stu-id="0558a-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="0558a-147">Інші користувачі, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути підключення, що аналізує вміст, перейшовши до розділу \*\*ПараметриКонфіденційність.</span><span class="sxs-lookup"><span data-stu-id="0558a-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="0558a-148">Параметр налаштування для підключених можливостей, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="0558a-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="0558a-149">Ці можливості дають змогу знайти в мережі та завантажити вміст, зокрема шаблони, зображення, об’ємні моделі, відео та довідкові матеріали для доповнення ваших документів.</span><span class="sxs-lookup"><span data-stu-id="0558a-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="0558a-150">Наприклад, шаблони Office або компонувальник презентації PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="0558a-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="0558a-151">Перелік цих підключених можливостей див. у розділі [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-152">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="0558a-153">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="0558a-154">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-154">**Data Type**</span></span>  | <span data-ttu-id="0558a-155">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="0558a-155">Boolean</span></span> |
|<span data-ttu-id="0558a-156">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-156">**Possible values**</span></span>  | <span data-ttu-id="0558a-157">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0558a-158">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="0558a-159">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-159">**Availability**</span></span> |<span data-ttu-id="0558a-160">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-160">16.28 and later</span></span> |

<span data-ttu-id="0558a-161">Якщо цей параметр не задано, підключені можливості, що завантажують вміст з мережі, доступні для користувачів.</span><span class="sxs-lookup"><span data-stu-id="0558a-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="0558a-162">Якщо користувач має передплату на Office 365 і ввійшов в робочий або навчальний обліковий запис, або якщо він має ліцензію на службу Office 2019 для Mac, користувач не зможе вимкнути підключені можливості, що завантажують вміст з мережі.</span><span class="sxs-lookup"><span data-stu-id="0558a-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="0558a-163">Інші користувачі, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути підключені можливості, що завантажують вміст з мережі, перейшовши до розділу **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="0558a-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="0558a-164">Параметр налаштування для необов'язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="0558a-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="0558a-165">На додачу до згаданих вище підключених можливостей, існують необов'язкові підключені можливості, доступ до яких можна надати користувачам з обліковим записом організації, який часом називають робочим або навчальним обліковим записом.</span><span class="sxs-lookup"><span data-stu-id="0558a-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="0558a-166">Це, наприклад, функції LinkedIn Укладача резюме у Word або функція панелі погоди в Outlook, яка використовує службу MSN Погода.</span><span class="sxs-lookup"><span data-stu-id="0558a-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="0558a-167">Інші приклади див. в розділі [Огляд необов’язкових підключених можливостей Office](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-168">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="0558a-169">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="0558a-170">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-170">**Data Type**</span></span>  | <span data-ttu-id="0558a-171">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="0558a-171">Boolean</span></span> |
|<span data-ttu-id="0558a-172">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-172">**Possible values**</span></span>  | <span data-ttu-id="0558a-173">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0558a-174">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="0558a-175">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-175">**Availability**</span></span> |<span data-ttu-id="0558a-176">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-176">16.28 and later</span></span> |

<span data-ttu-id="0558a-177">Якщо цей параметр не задано, необов'язкові підключені можливості доступні для користувачів з передплатою на Office 365, які ввійшли в службу, використовуючи робочий або навчальний обліковий запис, або для користувачів, яким інстальовано ліцензійну версію Office 2019 для Mac.</span><span class="sxs-lookup"><span data-stu-id="0558a-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="0558a-178">Якщо ви не налаштували цей параметр , ці користувачі можуть вимкнути необов'язкові підключені можливості, перейшовши до розділуПараметри > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="0558a-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="0558a-179">Інші користувачі, як-от домашні користувачі з передплатою на Office 365, не можуть вимкнути необов'язкові підключені можливості.</span><span class="sxs-lookup"><span data-stu-id="0558a-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="0558a-180">Параметр налаштування для більшості підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="0558a-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="0558a-181">Ви можете використовувати цей параметр, щоб визначити, чи більшість підключених можливостей доступна для ваших користувачів.</span><span class="sxs-lookup"><span data-stu-id="0558a-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-182">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="0558a-183">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="0558a-184">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-184">**Data Type**</span></span>  | <span data-ttu-id="0558a-185">Логічне значення</span><span class="sxs-lookup"><span data-stu-id="0558a-185">Boolean</span></span> |
|<span data-ttu-id="0558a-186">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-186">**Possible values**</span></span>  | <span data-ttu-id="0558a-187">`TRUE` *(увімкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="0558a-188">`FALSE` *(вимкнуто)*</span><span class="sxs-lookup"><span data-stu-id="0558a-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="0558a-189">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-189">**Availability**</span></span> |<span data-ttu-id="0558a-190">16.28 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-190">16.28 and later</span></span> |

<span data-ttu-id="0558a-191">Якщо цей параметр не задано, усі підключені можливості доступні для користувачів, якщо ви не задали якийсь із зазначених вище параметрів для підключених можливостей, наприклад `OfficeExperiencesAnalyzingContentPreference`.</span><span class="sxs-lookup"><span data-stu-id="0558a-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="0558a-192">Якщо задати цьому параметру значення `FALSE`, вашим користувачам будуть недоступні такі підключені можливості:</span><span class="sxs-lookup"><span data-stu-id="0558a-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="0558a-193">Можливості, які аналізують ваш вміст</span><span class="sxs-lookup"><span data-stu-id="0558a-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="0558a-194">Можливості, які завантажують вміст із мережі</span><span class="sxs-lookup"><span data-stu-id="0558a-194">Experiences that download online content</span></span>
- <span data-ttu-id="0558a-195">Необов'язкові підключені можливості</span><span class="sxs-lookup"><span data-stu-id="0558a-195">Optional connected experiences</span></span>

<span data-ttu-id="0558a-196">Крім того, якщо задати цьому параметру значення `FALSE`, більшість інших підключених можливостей, як-от співавторства та онлайнове сховище для файлів, також вимикається.</span><span class="sxs-lookup"><span data-stu-id="0558a-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="0558a-197">Докладніше про ці підключені можливості див. в статті [Підключені можливості в Office](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="0558a-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="0558a-198">Але навіть коли цьому параметру задано значення `FALSE`, залишаються доступними обмежені функціональні можливості Office, такі як синхронізація поштової скриньки в Outlook, і також працюватимуть Teams і Skype для бізнесу.</span><span class="sxs-lookup"><span data-stu-id="0558a-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="0558a-199">[Основні служби](essential-services.md), як-от Служба ліцензування, яка підтверджує, що ви маєте чинну ліцензію на використання Office, також залишатимуться доступними.</span><span class="sxs-lookup"><span data-stu-id="0558a-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="0558a-200">Якщо користувач має передплату на Office 365 і ввійшов в робочий або навчальний обліковий запис, або якщо він має ліцензію на службу Office 2019 для Mac, користувач не зможе вимкнути більшість підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="0558a-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="0558a-201">Інші користувачі, як-от домашні користувачі з передплатою на Office 365, можуть вимкнути більшість підключених можливостей, перейшовши до розділу **Параметри** > **Конфіденційність**.</span><span class="sxs-lookup"><span data-stu-id="0558a-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="0558a-202">Налаштування параметра «Повідомлення про обов'язкові дані» для автоматичного оновлення Microsoft</span><span class="sxs-lookup"><span data-stu-id="0558a-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="0558a-203">Під час першого запуску версії 4.12 або новіших версій автоматичного оновлення Microsoft, користувачі бачитимуть діалогове вікно**Повідомлення про обов'язкові дані** з інформацією про те, що дані автоматичного оновлення Microsoft надсилаються до корпорації Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="0558a-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="0558a-204">Якщо ви не хочете, щоб ваші користувачі бачили це діалогове вікно**Повідомлення про обов'язкові дані**для автоматичного оновлення Microsoft, ви можете встановити наведені нижче параметри.</span><span class="sxs-lookup"><span data-stu-id="0558a-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="0558a-205">Незалежно від того, яке значення задано, діалогове вікно не відображатиметься для користувачів.</span><span class="sxs-lookup"><span data-stu-id="0558a-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0558a-206">**Preference Domain**</span><span class="sxs-lookup"><span data-stu-id="0558a-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="0558a-207">\*\*Клавіша \*\*</span><span class="sxs-lookup"><span data-stu-id="0558a-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="0558a-208">**Тип даних**</span><span class="sxs-lookup"><span data-stu-id="0558a-208">**Data Type**</span></span>  | <span data-ttu-id="0558a-209">Рядок</span><span class="sxs-lookup"><span data-stu-id="0558a-209">String</span></span> |
|<span data-ttu-id="0558a-210">**Можливі значення**</span><span class="sxs-lookup"><span data-stu-id="0558a-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="0558a-211">**Доступність**</span><span class="sxs-lookup"><span data-stu-id="0558a-211">**Availability**</span></span> |<span data-ttu-id="0558a-212">4.12 і новіші версії</span><span class="sxs-lookup"><span data-stu-id="0558a-212">4.12 and later</span></span> |

<span data-ttu-id="0558a-213">Якщо дозволити користувачам бачити це діалогове вікно, коли користувач вибирає кнопку **OK**, значення  буде записано , і діалогове вікно не відображається для користувача.</span><span class="sxs-lookup"><span data-stu-id="0558a-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="0558a-214">Пов’язані теми</span><span class="sxs-lookup"><span data-stu-id="0558a-214">Related topics</span></span>

- [<span data-ttu-id="0558a-215">Довідник із профілів конфігурації (документація розробника Apple)</span><span class="sxs-lookup"><span data-stu-id="0558a-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="0558a-216">Параметри розгортання для Office для Mac</span><span class="sxs-lookup"><span data-stu-id="0558a-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="0558a-217">Настройки конфіденційності облікового запису</span><span class="sxs-lookup"><span data-stu-id="0558a-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
