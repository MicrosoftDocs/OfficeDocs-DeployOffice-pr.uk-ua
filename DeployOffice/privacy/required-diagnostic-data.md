---
title: Обов’язкові діагностичні дані в Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Ця стаття пропонує адміністраторам Office відомості про обов’язкові діагностичні дані в Office та містить список подій і полів даних.
hideEdit: true
ms.openlocfilehash: d42f2bd20e3e2169e58d6f5c0a563f1b117ea847
ms.sourcegitcommit: 186aae0571f8ef5f62882b4edb10378ee8e42b6e
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/10/2019
ms.locfileid: "34813323"
---
# <a name="required-diagnostic-data-for-office"></a><span data-ttu-id="1bd6a-103">Обов’язкові діагностичні дані в Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-103">Required diagnostic data for Office</span></span>

> [!IMPORTANT]
> <span data-ttu-id="1bd6a-104">Інформація в цій статті стосується версії 1904 або новіших версій переліченого нижче клієнтського програмного забезпечення Office, інстальованого на комп’ютері з Windows.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-104">The information in this article applies to Version 1904 or later of the following Office client software installed on a computer running Windows:</span></span>
> - <span data-ttu-id="1bd6a-105">Office 365 ProPlus і Office 365 Business</span><span class="sxs-lookup"><span data-stu-id="1bd6a-105">Office 365 ProPlus and Office 365 Business</span></span>
> - <span data-ttu-id="1bd6a-106">Office 365 персональний, Office 365 домашній або інші версії Office, які входять до передплати на Office 365.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-106">Office 365 Personal, Office 365 Home, or other versions of Office that are part of an Office 365 subscription.</span></span>
> - <span data-ttu-id="1bd6a-107">Project і Visio, які входять до деяких планів передплати, як-от план Project Online професійний або Visio Online (план 2).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-107">Project and Visio that come with some subscription plans, such as the Project Online Professional plan or Visio Online Plan 2.</span></span>

<span data-ttu-id="1bd6a-108">Діагностичні дані служать для підтримки безпеки та актуальності Office, виявлення, діагностування та усунення проблем, а також для вдосконалення продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-108">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and fix problems, and also make product improvements.</span></span> <span data-ttu-id="1bd6a-109">До цих даних не входить ім’я користувача або адреса електронної пошти, вміст файлів, а також відомості про програми, не пов’язані з Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-109">This data does not include a user’s name or email address, the content of the user’s files, or information about apps unrelated to Office.</span></span>

<span data-ttu-id="1bd6a-110">Ці діагностичні дані, які збираються й надсилаються до корпорації Майкрософт, описують клієнтське програмне забезпечення Office, що використовується на комп'ютерах із Windows.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-110">This diagnostic data is collected and sent to Microsoft about Office client software being used on computers running Windows.</span></span> <span data-ttu-id="1bd6a-111">Деякі діагностичні дані обов’язкові, а деякі – ні.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-111">Some diagnostic data is required, while some diagnostic data is optional.</span></span> <span data-ttu-id="1bd6a-112">За допомогою елементів керування конфіденційністю, зокрема параметрів політики для організацій, ви маєте змогу вибрати, обов’язкові чи необов’язкові дані будуть надсилатися.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-112">We give you the ability to choose whether to send us required or optional diagnostic data through the use of privacy controls, such as policy settings for organizations.</span></span> <span data-ttu-id="1bd6a-113">Ви можете переглянути діагностичні дані, що надсилаються, за допомогою засобу перегляду діагностичних даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-113">You can see the diagnostic data being sent to us by using the Diagnostic Data Viewer.</span></span>

<span data-ttu-id="1bd6a-114">***Обов’язкові діагностичні дані*** – це мінімум даних, необхідний для підтримання безпеки та актуальності пакета Office і забезпечення нормальної роботи пакета на пристрої, на якому його інстальовано.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-114">***Required diagnostic data*** is the minimum data necessary to help keep Office secure, up-to-date, and performing as expected on the device it’s installed on.</span></span>

<span data-ttu-id="1bd6a-115">Обов’язкові діагностичні дані допомагають виявити проблеми з пакетом Office, які можуть бути пов'язані з конфігурацією пристрою або програмного забезпечення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-115">Required diagnostic data helps to identify problems with Office that may be related to a device or software configuration.</span></span> <span data-ttu-id="1bd6a-116">Наприклад, за їх допомогою можна визначити, чи компонент Office частіше аварійно завершує роботу в певній версії операційної системи, з нещодавно запровадженими функціями або коли певні функції Office вимкнуто.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-116">For example, it can help determine if an Office feature crashes more frequently on a particular operating system version, with newly introduced features, or when certain Office features are disabled.</span></span> <span data-ttu-id="1bd6a-117">Обов’язкові діагностичні дані допомагають нам швидше виявити, діагностувати та вирішити ці проблеми, тому їхній вплив на користувачів або організації зменшується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-117">Required diagnostic data helps us detect, diagnose, and fix these problems more quickly so the impact to users or organizations is reduced.</span></span>

<span data-ttu-id="1bd6a-118">Щоб більше дізнатися про діагностичні дані, зверніться до таких статей:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-118">For more information about diagnostic data, see the following:</span></span>

- [<span data-ttu-id="1bd6a-119">Необов’язкові діагностичні дані для Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-119">Optional diagnostic data for Office</span></span>](optional-diagnostic-data.md)
- [<span data-ttu-id="1bd6a-120">Використання засобу перегляду діагностичних даних з Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-120">Using the Diagnostic Data Viewer with Office</span></span>](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

<span data-ttu-id="1bd6a-121">Адміністратору організації також можуть бути корисними такі ресурси:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-121">If you’re the admin for your organization, you might also be interested in the following:</span></span>

- [<span data-ttu-id="1bd6a-122">Огляд елементів керування конфіденційністю в Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="1bd6a-122">Overview of privacy controls for Office 365 ProPlus</span></span>](overview-privacy-controls.md)
- [<span data-ttu-id="1bd6a-123">Використання параметрів політики для налаштування елементів керування конфіденційністю в Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="1bd6a-123">Use policy settings to manage privacy controls for Office 365 ProPlus</span></span>](manage-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a><span data-ttu-id="1bd6a-124">Категорії, підтипи даних, події та поля даних для обов’язкових діагностичних даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-124">Categories, data subtypes, events, and data fields for required diagnostic data</span></span>

<span data-ttu-id="1bd6a-125">Обов’язкові діагностичні дані поділяються на категорії та підтипи даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-125">Required diagnostic data is organized into categories and data subtypes.</span></span> <span data-ttu-id="1bd6a-126">Кожен підтип даних містить події з полями даних, які стосуються цієї конкретної події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-126">Within each data subtype are events, which contain data fields that are specific to that event.</span></span>

<span data-ttu-id="1bd6a-127">У таблиці нижче наведено перелік категорій обов’язкових діагностичних даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-127">The following table provides a list of the categories for required diagnostic data.</span></span> <span data-ttu-id="1bd6a-128">У кожній категорії зазначено підтипи даних, а також опис призначення цього підтипу даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-128">The data subtypes within each category are listed, along with a description of the focus for that data subtype.</span></span> <span data-ttu-id="1bd6a-129">Наведено посилання на розділ кожного підтипу даних, де містяться такі відомості:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-129">There are links to each data subtype section where you’ll find the following information:</span></span>

- <span data-ttu-id="1bd6a-130">Перелік подій у цьому підтипі даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-130">A list of events in that data subtype</span></span>
- <span data-ttu-id="1bd6a-131">Опис кожної події</span><span class="sxs-lookup"><span data-stu-id="1bd6a-131">A description of each event</span></span>
- <span data-ttu-id="1bd6a-132">Перелік полів даних у кожній події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-132">A list of data fields in each event</span></span>
- <span data-ttu-id="1bd6a-133">Опис кожного поля даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-133">A description of each data field</span></span>

| <span data-ttu-id="1bd6a-134">**Категорія**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-134">**Category**</span></span>       | <span data-ttu-id="1bd6a-135">**Підтип даних**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-135">**Data subtype**</span></span>| <span data-ttu-id="1bd6a-136">**Опис**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-136">**Description**</span></span>    |
| ---------- | ------------- | ---- |
| <span data-ttu-id="1bd6a-137">**Настроювання та облік програмного забезпечення**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-137">**Software setup and inventory**</span></span> | [<span data-ttu-id="1bd6a-138">Настроювання та облік Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-138">Office setup and inventory</span></span>](#office-setup-and-inventory-subtype)   | <span data-ttu-id="1bd6a-139">Назва та версія інстальованого продукту, стан інсталяції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-139">Installed product and version and the installation status.</span></span>  |
| | [<span data-ttu-id="1bd6a-140">Конфігурація надбудов Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-140">Office add-in configuration</span></span>](#office-add-in-configuration-subtype)  | <span data-ttu-id="1bd6a-141">Програмні надбудови та їхні параметри.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-141">Software add-ins and their settings.</span></span>     |
| | [<span data-ttu-id="1bd6a-142">Безпека</span><span class="sxs-lookup"><span data-stu-id="1bd6a-142">Security</span></span>](#security-subtype)  | <span data-ttu-id="1bd6a-143">Помилки документів, функцій та надбудов, які можуть зашкодити безпеці, зокрема вплинути на стан готовності до оновлення продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-143">Document, feature, and add-in error conditions that may compromise security, including product update readiness.</span></span>  |
| <span data-ttu-id="1bd6a-144">**Використання продуктів і служб**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-144">**Product and service usage**</span></span>    | [<span data-ttu-id="1bd6a-145">Успіх функцій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-145">Application feature success</span></span>](#application-feature-success-subtype)   | <span data-ttu-id="1bd6a-146">Успішність виконання функцій програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-146">Success of application functionality.</span></span> <span data-ttu-id="1bd6a-147">Обмежується операціями відкривання та закривання програм і документів, редагування файлів і спільного доступу до файлів (співпраці).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-147">Limited to opening and closing of the application and documents, file editing, and file sharing (collaboration).</span></span> |
| | [<span data-ttu-id="1bd6a-148">Стан та завантаження програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-148">Application status and boot</span></span>](#application-status-and-boot-subtype)    | <span data-ttu-id="1bd6a-149">Визначення, чи сталися події конкретних функцій, таких як запуск або припинення, а також чи працює ця функція.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-149">Determination if specific feature events have occurred, such as start or stop, and if feature is running.</span></span>   |
| | [<span data-ttu-id="1bd6a-150">Конфігурація спеціальних можливостей Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-150">Office accessibility configuration</span></span>](#office-accessibility-configuration-subtype)  | <span data-ttu-id="1bd6a-151">Функції спеціальних можливостей Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-151">Office accessibility features</span></span>       |
| | <span data-ttu-id="1bd6a-152">[Конфіденційність](#privacy-subtype)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-152">[Privacy Options](#privacy-subtype):</span></span>| <span data-ttu-id="1bd6a-153">Настройки конфіденційності Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-153">Office privacy settings</span></span>|
| <span data-ttu-id="1bd6a-154">**Якість роботи продуктів і служб**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-154">**Product and service performance**</span></span>       | [<span data-ttu-id="1bd6a-155">Неочікуване закриття (аварійне завершення роботи) програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-155">Unexpected application exit (crash)</span></span>](#unexpected-application-exit-crash-subtype)  | <span data-ttu-id="1bd6a-156">Неочікуване закриття програми та стан програми на цей момент.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-156">Unexpected application exits and the state of the application when that happens.</span></span>    |
|  | [<span data-ttu-id="1bd6a-157">Якість виконання функцій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-157">Application feature performance </span></span>](#application-feature-performance-subtype)  | <span data-ttu-id="1bd6a-158">Повільна або погана робота в таких ситуаціях, як запуск програми або відкриття файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-158">Poor response time or performance for scenarios such as application start up or opening a file.</span></span> |
|  | [<span data-ttu-id="1bd6a-159">Помилки дій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-159">Application activity error</span></span>](#application-activity-error-subtype)   | <span data-ttu-id="1bd6a-160">Помилки виконання функцій або взаємодії з користувачем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-160">Errors in functionality of a feature or user experience.</span></span>  |
| <span data-ttu-id="1bd6a-161">**Підключення та конфігурація пристрою**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-161">**Device connectivity and configuration**</span></span> | [<span data-ttu-id="1bd6a-162">Підключення та конфігурація пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-162">Device connectivity and configuration</span></span>](#device-connectivity-and-configuration-subtype) | <span data-ttu-id="1bd6a-163">Стан підключення до мережі та параметри пристрою, наприклад пам'ять.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-163">Network connection state and device settings, such as memory.</span></span> |


> [!NOTE]
> - <span data-ttu-id="1bd6a-164">Категорії відображаються в засобі діагностики перегляду даних, але підтипи даних не відображаються.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-164">Categories are shown in the Diagnostic Data Viewer, but data subtypes are not shown.</span></span>
> - <span data-ttu-id="1bd6a-165">Поле даних із позначкою *Застаріле* нещодавно було вилучено або незабаром буде вилучено з обов’язкових діагностичних даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-165">A data field marked *Obsolete* has been or will soon be removed from required diagnostic data.</span></span> <span data-ttu-id="1bd6a-166">Деякі з цих полів даних являють собою дублікати, які виникли внаслідок модернізації діагностичних даних і використовувалися для забезпечення безперервності подання оперативних звітів діагностичного моніторингу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-166">Some of these data fields are duplicates that arose as diagnostic data was modernized and were used to ensure no service disruption to live diagnostic monitoring reports.</span></span>

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a><span data-ttu-id="1bd6a-167">Категорії та поля даних, спільні для всіх подій</span><span class="sxs-lookup"><span data-stu-id="1bd6a-167">Categories and data fields that are common for all events</span></span>

<span data-ttu-id="1bd6a-168">Є певні відомості про події, які властиві всім подіям, незалежно від категорії або підтипу даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-168">There is some information about events that is common to all events, regardless of category or data subtype.</span></span> <span data-ttu-id="1bd6a-169">Ці універсальні відомості, які інколи називають *контрактами даних*, поділяються на категорії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-169">This common information, which is sometimes referred to as *data contracts*, is organized into categories.</span></span> <span data-ttu-id="1bd6a-170">Кожна категорія містить поля, які є метаданими та властивостями окремих подій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-170">Each category contains fields, and these fields are the metadata and properties of an individual event.</span></span> <span data-ttu-id="1bd6a-171">Ці відомості можна переглянути за допомогою засобу перегляду діагностичних даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-171">You can view this information by using the Diagnostic Data Viewer.</span></span>

<span data-ttu-id="1bd6a-172">Категорії відомостей про події можна розділити на дві групи:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-172">The categories of information that is collected about events can be divided into two groups:</span></span>

  - [<span data-ttu-id="1bd6a-173">Відомості, властиві всім подіям</span><span class="sxs-lookup"><span data-stu-id="1bd6a-173">Information common to all events</span></span>](#information-common-to-all-events)
  - [<span data-ttu-id="1bd6a-174">Відомості, які служать для збирання діагностичних даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-174">Information that specifically supports diagnostic data collection</span></span>](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a><span data-ttu-id="1bd6a-175">*Відомості, властиві всім подіям*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-175">*Information common to all events*</span></span>

<span data-ttu-id="1bd6a-176">Відомості, властиві всім подіям, збираються в такі категорії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-176">Information common to all events is collected in the following categories.</span></span>

#### <a name="app"></a><span data-ttu-id="1bd6a-177">App</span><span class="sxs-lookup"><span data-stu-id="1bd6a-177">App</span></span> 

<span data-ttu-id="1bd6a-178">Відомості про програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-178">Information about the application.</span></span> <span data-ttu-id="1bd6a-179">Вміст усіх полів постійний для всіх сеансів певної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-179">All fields are constant for all sessions of a given application version.</span></span>

<span data-ttu-id="1bd6a-180">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-180">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-181">**Branch** – гілка, з якої походить ця збірка.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-181">**Branch** - The branch that the given build came from.</span></span> <span data-ttu-id="1bd6a-182">Дає змогу визначити, з якого типу гілки походить певна збірка, що допомагає правильно вибирати виправлення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-182">Allows us to determine what type of branch a given build came from so that we can correctly target fixes.</span></span>
  - <span data-ttu-id="1bd6a-183">**InstallType** – нумератор, який вказує, як користувач інсталював програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-183">**InstallType** - An enumerator that identifies how the user installed the application.</span></span> <span data-ttu-id="1bd6a-184">Дає змогу визначити, чи певні механізми інсталяції створюють проблеми, які не трапляються в інших механізмах інсталяції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-184">Allows us to determine if specific install mechanisms are creating issues that are not seen in other installation mechanisms.</span></span>
  - <span data-ttu-id="1bd6a-185">**Name** – ім’я програми, яка надає дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-185">**Name** - The name of the application that is providing the data.</span></span> <span data-ttu-id="1bd6a-186">Дає змогу визначити, яка програма показує проблему, щоб ми знали, як вирішити її.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-186">Allows us to identify which application is showing an issue so we know how to address it.</span></span>
  - <span data-ttu-id="1bd6a-187">**Platform** – узагальнена класифікація платформи, на якій виконується програма.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-187">**Platform** - The broad classification of the platform on which the app is running.</span></span> <span data-ttu-id="1bd6a-188">Дає змогу визначити, на яких платформах може виникати проблема, що допомагає правильно визначити її пріоритетність.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-188">Allows us to identify on which platforms an issue may be occurring so that we can correctly prioritize the issue.</span></span>
  - <span data-ttu-id="1bd6a-189">**Version** – версія програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-189">**Version** - The version of the application.</span></span> <span data-ttu-id="1bd6a-190">Дає змогу визначити, які версії продукту показують проблему, що допомагає правильно визначити її пріоритетність.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-190">Allows us to identify which versions of the product are showing an issue so that we can correctly prioritize it.</span></span>

#### <a name="client"></a><span data-ttu-id="1bd6a-191">Client</span><span class="sxs-lookup"><span data-stu-id="1bd6a-191">Client</span></span> 

<span data-ttu-id="1bd6a-192">Ідентифікатор, який стосується екземпляра Office на пристрої.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-192">Identifier related to an Office instance on a device.</span></span> <span data-ttu-id="1bd6a-193">Один і той самий для всіх сеансів певної версії інсталяції версії для багатопрограмних пакетів або один і той самий для всіх сеансів певної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-193">Constant for all sessions of all apps of a given installation version for multi-app suites, or constant for all sessions of a given application version.</span></span>

<span data-ttu-id="1bd6a-194">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-194">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-195">**Id** – унікальний ідентифікатор, призначений клієнту під час інсталяції Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-195">**Id** - Unique identifier assigned to a client at install time of Office.</span></span> <span data-ttu-id="1bd6a-196">Дає змогу визначити, чи впливають проблеми на конкретний набір інсталяцій і скільки користувачів зазнають впливу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-196">Allows us to identify whether issues are impacting a select set of installs and how many users are impacted.</span></span>

#### <a name="consent"></a><span data-ttu-id="1bd6a-197">Consent</span><span class="sxs-lookup"><span data-stu-id="1bd6a-197">Consent</span></span>

<span data-ttu-id="1bd6a-198">Відомості про згоду користувачів на діагностичні дані та підключені можливості.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-198">Information regarding the users consent for diagnostic data and connected experiences.</span></span>

<span data-ttu-id="1bd6a-199">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-199">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-200">**UserCategory** – визначає тип користувача, який дав згоду.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-200">**UserCategory –** Identified the type of user who made the consent.</span></span> <span data-ttu-id="1bd6a-201">Може мати значення MSAUser, AADUser або LocalDeviceUser.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-201">One of MSAUser, AADUser or LocalDeviceUser</span></span>

  - <span data-ttu-id="1bd6a-202">**DiagnosticConsentLevel** – указує на рівень діагностичних даних, на які користувач дав згоду.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-202">**DiagnosticConsentLevel** – Indicates what level of diagnostic data consent the user has given</span></span>

  - <span data-ttu-id="1bd6a-203">**DiagnosticConsentSourceLocation** – указує, яким чином користувач дав згоду на діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-203">**DiagnosticConsentSourceLocation** – Indicates how the user had provided the consent for diagnostic data</span></span>

  - <span data-ttu-id="1bd6a-204">**DiagnosticConsentConsentTime** – указує, коли користувач дав згоду на діагностичні дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-204">**DiagnosticConsentConsentTime** – Indicates when the user provided the consent for diagnostic data</span></span>

  - <span data-ttu-id="1bd6a-205">**ServiceConnectionState** – указує на те, чи користувач вирішив використовувати всі підключені можливості.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-205">**ServiceConnectionState** – Indicates whether the user has chosen to use or not use all connected experiences</span></span>

  - <span data-ttu-id="1bd6a-206">**ServiceConnectionStateSourceLocation** – указує, яким чином користувач здійснив свій вибір стосовно використання всіх підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-206">**ServiceConnectionStateSourceLocation** – Indicates how the user provided the choice whether to use all connected experiences</span></span>

  - <span data-ttu-id="1bd6a-207">**ServiceConnectionStateConsentTime** – указує, коли користувач здійснив свій вибір стосовно використання всіх підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-207">**ServiceConnectionStateConsentTime** – Indicates when the user chose whether to use all connected experiences</span></span>

  - <span data-ttu-id="1bd6a-208">**ControllerConnectedServicesState** – указує, чи користувач має доступ до необов'язкових підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-208">**ControllerConnectedServicesState** – Indicates whether the user has access to optional connected experiences</span></span>

  - <span data-ttu-id="1bd6a-209">**ControllerConnectedServicesStateSourceLocation** – указує, яким чином користувач здійснив свій вибір стосовно необов’язкових підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-209">**ControllerConnectedServicesStateSourceLocation** – Indicates how the user’s choice for optional connected experiences was made</span></span>

  - <span data-ttu-id="1bd6a-210">**ControllerConnectedServicesStateConsentTime** – указує, коли користувач вибрав статус необов’язкових підключених можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-210">**ControllerConnectedServicesStateConsentTime** – Indicates when the user chose the status of optional connected experiences</span></span>

  - <span data-ttu-id="1bd6a-211">**UserContentDependentState** – указує, чи вибрав користувач увімкнення або вимкнення підключених можливостей, які аналізують вміст.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-211">**UserContentDependentState** – Indicates whether the user has chosen to enable or disable connected experiences that analyze content</span></span>

  - <span data-ttu-id="1bd6a-212">**UserContentDependentStateSourceLocation** – указує, яким чином користувач здійснив свій вибір стосовно ввімкнення або вимкнення підключених можливостей, які аналізують вміст.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-212">**UserContentDependentStateSourceLocation** – Indicates how the user’s choice to enable or disable was made for connected experiences that analyze content</span></span>

  - <span data-ttu-id="1bd6a-213">**UserContentDependentStateConsentTime** – указує, коли користувач вибрав увімкнення або вимкнення підключених можливостей, які аналізують вміст.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-213">**UserContentDependentStateConsentTime** – Indicates when the user chose to enable or disable connected experiences that analyze content was made</span></span>

  - <span data-ttu-id="1bd6a-214">**DownloadContentState** – указує, чи вибрав користувач увімкнення або вимкнення підключених можливостей, які завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-214">**DownloadContentState** – Indicates whether the user has chosen to enable or disable connected experiences that download online content</span></span>

  - <span data-ttu-id="1bd6a-215">**UserContentDependentStateSourceLocation** – указує, яким чином користувач здійснив свій вибір стосовно ввімкнення або вимкнення підключених можливостей, які завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-215">**DownloadContentStateSourceLocation** – Indicates how the user made the choice to enable or disable connected experiences that that download online content</span></span>

  - <span data-ttu-id="1bd6a-216">**DownloadContentStateConsentTime** – указує, коли користувач вибрав увімкнення або вимкнення підключених можливостей, які завантажують вміст із мережі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-216">**DownloadContentStateConsentTime** – Indicates when the user made the choice to enable or disable connected experiences that download online content.</span></span>

#### <a name="device"></a><span data-ttu-id="1bd6a-217">Device</span><span class="sxs-lookup"><span data-stu-id="1bd6a-217">Device</span></span> 

<span data-ttu-id="1bd6a-218">Відомості про операційну систему та збірку.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-218">Information about the operating system and build.</span></span>

<span data-ttu-id="1bd6a-219">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-219">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-220">**OsBuild** – номер збірки операційної системи, інстальованої на пристрої.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-220">**OsBuild** - The build number of the operating system installed on the device.</span></span> <span data-ttu-id="1bd6a-221">Дає змогу визначити, чи впливають проблеми на окремі пакети оновлень або версій певної операційної системи інакше, ніж на інші, що допомагає правильно визначити їхню пріоритетність.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-221">Allows us to identify whether issues are impacting individual service packs or versions of a given operating system differently than others so we can prioritize issues.</span></span>

  - <span data-ttu-id="1bd6a-222">**OsBuild** – основна версія операційної системи, інстальованої на пристрої.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-222">**OsVersion** - The major version of the operating system installed on the device.</span></span> <span data-ttu-id="1bd6a-223">Дає змогу визначити, чи впливають проблеми на певну версію операційної системи сильніше, ніж на інші, щоб можна було правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-223">Allows us to determine if issues are impacting a particular operating system version more than other so we can prioritize issues.</span></span>

#### <a name="legacy"></a><span data-ttu-id="1bd6a-224">Legacy</span><span class="sxs-lookup"><span data-stu-id="1bd6a-224">Legacy</span></span> 

<span data-ttu-id="1bd6a-225">Повідомляє ідентифікатор програми та версію ОС для сумісності з попередніми методами збирання даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-225">Provides an App Id and OS version for compatibility with existing legacy collection practices.</span></span>

<span data-ttu-id="1bd6a-226">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-226">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-227">**AppId** – нумератор, який указує, яка саме програма надсилає дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-227">**AppId** - An enumerator value representing which application is sending the data.</span></span> <span data-ttu-id="1bd6a-228">Дає змогу визначити, яка програма показує проблему, щоб ми знали, як вирішити її.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-228">Allows us to identify which application is showing an issue so we know how to address it.</span></span>

  - <span data-ttu-id="1bd6a-229">**OsEnv** – нумератор, який указує, з якою операційною системою працює сеанс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-229">**OsEnv** - An enumerator indicating which operating system the session is running on.</span></span> <span data-ttu-id="1bd6a-230">Дає змогу визначити, в якій операційній системі виникає проблема, що допомагає правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-230">Allows us to identify which operating system an issue happening on so we can prioritize issues.</span></span>

#### <a name="release"></a><span data-ttu-id="1bd6a-231">Release</span><span class="sxs-lookup"><span data-stu-id="1bd6a-231">Release</span></span> 

<span data-ttu-id="1bd6a-232">Відомості, пов'язані з каналом випуску.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-232">Information related to the release channel.</span></span> <span data-ttu-id="1bd6a-233">Вміст усіх полів постійний для всіх сеансів усіх програм певної версії інсталяції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-233">All fields are constant for all sessions of all apps of a given installation version.</span></span> <span data-ttu-id="1bd6a-234">Визначає групи пристроїв, які всі перебувають на одному етапі циклу випуску продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-234">Identifies a group of devices all in one phase of a product release cycle.</span></span>

<span data-ttu-id="1bd6a-235">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-235">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-236">**Audience** – визначає частину певної групи аудиторії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-236">**Audience** - Identifies a sub-audience of a given audience group.</span></span> <span data-ttu-id="1bd6a-237">Дає змогу відстежувати підмножини груп аудиторії, щоб оцінити поширення проблем та їхню пріоритетність.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-237">Allows us to track subsets of audience groups to evaluate prevalence and prioritization of issues.</span></span>

  - <span data-ttu-id="1bd6a-238">**AudienceGroup** – визначає коло, з якого походять дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-238">**AudienceGroup** - Identifies the ring where data is coming from.</span></span> <span data-ttu-id="1bd6a-239">Дає змогу поетапно розгортати функції та виявляти потенційні проблеми, перш ніж їх відчує більшість користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-239">Allows us to roll out features in a staged fashion and identify potential issues before they reach most users.</span></span>

  - <span data-ttu-id="1bd6a-240">**Channel** – канал, через який випускається продукт.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-240">**Channel** - The channel that the product is being released through.</span></span> <span data-ttu-id="1bd6a-241">Дає змогу визначити, чи впливає проблема на один із наших каналів розгортання інакше, ніж на інші.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-241">Allows us to identify if an issue is impacting one of our rollout channels differently than others.</span></span>

  - <span data-ttu-id="1bd6a-242">**Fork** – визначає відгалуження продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-242">**Fork** - Identifies the fork of the product.</span></span> <span data-ttu-id="1bd6a-243">Надає механізм агрегації даних у сукупності номерів збірок для виявлення проблем, пов'язаних із певним випуском.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-243">Allows a mechanism to aggregate data across a set of build numbers to identify issues related to a given release.</span></span>

#### <a name="session"></a><span data-ttu-id="1bd6a-244">Session</span><span class="sxs-lookup"><span data-stu-id="1bd6a-244">Session</span></span> 

<span data-ttu-id="1bd6a-245">Відомості про сеанс процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-245">Information about the process session.</span></span> <span data-ttu-id="1bd6a-246">Для одного сеансу всі поля мають один і той самий вміст.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-246">All fields are constant for this session.</span></span>

<span data-ttu-id="1bd6a-247">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-247">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-248">**ABConfigs** – визначає набір тестів, які виконуються в певному сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-248">**ABConfigs** - Identifies the set of flights that are running in a given session.</span></span> <span data-ttu-id="1bd6a-249">Дає змогу визначити, які окремі тести виконуються в сеансі, що допомагає з’ясувати, чи є тест причиною проблеми, яка впливає на користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-249">Allows us to identify which individual flights are running on a session so that we can determine if a flight is the source of an issue impacting users.</span></span>

  - <span data-ttu-id="1bd6a-250">**EcsETag** – індикатор системи тестування, який представляє тести, надіслані на комп'ютер.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-250">**EcsETag** - An indicator from the flighting system that represents the flights sent to the machine.</span></span> <span data-ttu-id="1bd6a-251">Дає змогу визначити, які тести можуть впливати на певний сеанс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-251">Allows us to identify what flights might be impacting a given session.</span></span>

  - <span data-ttu-id="1bd6a-252">**Flags** – позначки відстеження-бітові маски, застосовні до всього сеансу, на цей час служать насамперед для вибирання даних і способів діагностування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-252">**Flags** - Bitmask tracking flags applicable to an entire session, currently primarily focused on sampling and diagnostic data options.</span></span> <span data-ttu-id="1bd6a-253">Дає змогу керувати поведінкою певного сеансу стосовно діагностичних даних, які створюються в цьому сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-253">Allows us to control how a given session behaves in relation to the diagnostic data that the session generates.</span></span>

  - <span data-ttu-id="1bd6a-254">**Id** – однозначно ідентифікує певний сеанс даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-254">**Id** - Uniquely identifies a given session of data.</span></span> <span data-ttu-id="1bd6a-255">Дає змогу визначити вплив проблем, оцінюючи кількість сеансів, які зазнали впливу, і чи мають ці сеанси спільні функції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-255">Allows us to identify the impact of issues by evaluating the number of sessions that are impacted and if there are common features of those sessions.</span></span>

  - <span data-ttu-id="1bd6a-256">**ImpressionId** – визначає набір тестів, які виконуються в певному сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-256">**ImpressionId** - Identifies the set of flights that are running in a given session.</span></span> <span data-ttu-id="1bd6a-257">Дає змогу визначити, які окремі тести виконуються в сеансі, що допомагає з’ясувати, чи є тест причиною проблеми, яка впливає на користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-257">Allows us to identify which individual flights are running on a session so that we can determine if a flight is the source of an issue impacting users.</span></span>

  - <span data-ttu-id="1bd6a-258">**MeasuresEnabled** – позначка, яка вказує, чи вибираються дані поточного сеансу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-258">**MeasuresEnabled** - Flag indicating if the current sessions data is sampled or not.</span></span> <span data-ttu-id="1bd6a-259">Дає змогу визначити, як статистично оцінювати дані, зібрані в певному сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-259">Allows us to determine how to statistically evaluate the data that is gathered from the given session.</span></span>

  - <span data-ttu-id="1bd6a-260">**SamplingClientId** – ідентифікатор клієнта, який визначає, чи належить він до вибірки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-260">**SamplingClientId** - The id of the client used to determine if it is part of sampling.</span></span> <span data-ttu-id="1bd6a-261">Дає змогу визначити, чому певний сеанс було долучено до вибірки або виключено з неї.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-261">Allows us to determine why an individual session was included or excluded from sampling.</span></span>

#### <a name="user"></a><span data-ttu-id="1bd6a-262">User</span><span class="sxs-lookup"><span data-stu-id="1bd6a-262">User</span></span>

<span data-ttu-id="1bd6a-263">Надає клієнтські відомості про облікові номери комерційного програмного забезпечення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-263">Provides tenant information for commercial software SKUs.</span></span>

<span data-ttu-id="1bd6a-264">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-264">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-265">**PrimaryIdentityHash** – псевдонімічний ідентифікатор, який відповідає поточному користувачеві.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-265">**PrimaryIdentityHash** – A pseudonymous identifier that represents the current user.</span></span>

  - <span data-ttu-id="1bd6a-266">**PrimaryIdentitySpace** – тип ідентичності, які міститься в PrimaryIdentityHash.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-266">**PrimaryIdentitySpace** – The type of identity contained in the PrimaryIdentityHash.</span></span> <span data-ttu-id="1bd6a-267">Може мати значення MASCID, OrgIdCID або UserObjectId.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-267">One of MASCID, OrgIdCID or UserObjectId.</span></span>

  - <span data-ttu-id="1bd6a-268">**TenantGroup** – тип клієнта, до якого належить передплата.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-268">**TenantGroup** - The type of the tenant that the subscription belongs to.</span></span> <span data-ttu-id="1bd6a-269">Дає змогу класифікувати проблеми та визначити, чи є проблема поширеною або обмежується певними користувачами.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-269">Allows us to classify issues and identify whether a problem is widespread or isolated to a set of users.</span></span>

  - <span data-ttu-id="1bd6a-270">**TenantId** – клієнт, з яким зв’язано передплату користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-270">**TenantId** - The tenant that a user’s subscription is tied to.</span></span> <span data-ttu-id="1bd6a-271">Дає змогу класифікувати проблеми та визначити, чи є проблема поширеною або обмежується певними користувачами чи конкретним клієнтом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-271">Allows us to classify issues and identify whether a problem is widespread or isolated to a set of users or a specific tenant.</span></span>

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a><span data-ttu-id="1bd6a-272">*Відомості, які служать для збирання діагностичних даних*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-272">*Information that specifically supports diagnostic data collection*</span></span>

<span data-ttu-id="1bd6a-273">Відомості, які служать для збирання діагностичних даних, збираються в такі категорії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-273">Information that specifically supports diagnostic data collection is collected in the following categories.</span></span>

#### <a name="activity"></a><span data-ttu-id="1bd6a-274">Activity</span><span class="sxs-lookup"><span data-stu-id="1bd6a-274">Activity</span></span>

<span data-ttu-id="1bd6a-275">Відомості, які показують успіх самої події збирання.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-275">Information to understand the success of the collection event itself.</span></span>

<span data-ttu-id="1bd6a-276">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-276">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-277">**AggMode** – указує системі, як об’єднувати результати дій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-277">**AggMode** - Tells the system how to aggregate activity results.</span></span> <span data-ttu-id="1bd6a-278">Дає змогу зменшити обсяг інформації, яка передається з комп'ютера користувача, шляхом об'єднання (агрегації) результатів дій в одну подію, яка періодично надсилається.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-278">Allows us to reduce the amount of information uploaded from a user’s machine by aggregating activity results into a single event that gets sent periodically.</span></span>

  - <span data-ttu-id="1bd6a-279">**Count** – скільки разів відбувалася дія, якщо ця кількість походить з агрегатної події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-279">**Count** - The number of times the activity happened if the count is from an aggregated event.</span></span> <span data-ttu-id="1bd6a-280">Дає змогу визначити, як часто траплявся успіх або невдача дії, виходячи з режиму агрегації дії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-280">Allows us to determine how often an activity succeeded or failed based on the aggregation mode of the activity.</span></span>

  - <span data-ttu-id="1bd6a-281">**CV** – значення, яке показує зв’язок між діями та субдіями.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-281">**CV** - A value that identifies the relationship between activities and sub-activities.</span></span> <span data-ttu-id="1bd6a-282">Дає змогу відновити зв'язок між вкладеними діями.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-282">Allows us to rebuild the relationship between nested activities.</span></span>

  - <span data-ttu-id="1bd6a-283">**Duration** – час, який тривало виконання дії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-283">**Duration** - The length of time the activity took to execute.</span></span> <span data-ttu-id="1bd6a-284">Дає змогу визначити проблеми з продуктивністю, які негативно впливають на можливості користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-284">Allows us to identify performance issues that are negatively impacting the users experience.</span></span>

  - <span data-ttu-id="1bd6a-285">**Result**.**Code** – визначений у програмі код, яким позначаються певні результати.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-285">**Result**.**Code** - An application defined code to identify a given results.</span></span> <span data-ttu-id="1bd6a-286">Дає змогу вказати конкретніші відомості про певну невдачу, як-от код помилки, які можна використовувати для класифікації та виправлення проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-286">Allows us to determine more specific details of a given failure such as a failure code that can be used to classify and fix issues.</span></span>

  - <span data-ttu-id="1bd6a-287">**Result.Tag** – ціле число-тег, яке визначає місце в коді, де було створено дію.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-287">**Result.Tag** - An integer tag that identifies the location in code where the result was generated.</span></span> <span data-ttu-id="1bd6a-288">Дає змогу точно визначити місце в коді, де виник результат, що дає змогу класифікувати помилки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-288">Allows us to distinctly identify the location in code where a result was generated which enables classification of failures.</span></span>

  - <span data-ttu-id="1bd6a-289">**Result**.**Type** – тип коду результату.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-289">**Result**.**Type** - The type of the result code.</span></span> <span data-ttu-id="1bd6a-290">Визначає, який тип коду результату було надіслано, що дає змогу правильно інтерпретувати значення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-290">Identifies what type of result code was sent so that the value can be correctly interpreted.</span></span>

  - <span data-ttu-id="1bd6a-291">**Success** – позначка, яка вказує, чи була дія успішною або невдалою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-291">**Success** - A flag indicating if the activity succeeded or failed.</span></span> <span data-ttu-id="1bd6a-292">Дає змогу визначити, успішними чи невдалими є дії користувача в продукті.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-292">Allows us to determine if actions the user takes in the product are succeeding or failing.</span></span> <span data-ttu-id="1bd6a-293">Це допомагає виявити проблеми, які впливають на користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-293">This allows us to identify issues that are impacting the user.</span></span>

#### <a name="application"></a><span data-ttu-id="1bd6a-294">Application</span><span class="sxs-lookup"><span data-stu-id="1bd6a-294">Application</span></span> 

<span data-ttu-id="1bd6a-295">Відомості про інсталяцію програми, з якої надходять події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-295">Information about the installation of the application from which the events are being gathered.</span></span>

<span data-ttu-id="1bd6a-296">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-296">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-297">**Architecture** – архітектура програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-297">**Architecture** - The architecture of the application.</span></span> <span data-ttu-id="1bd6a-298">Дає змогу класифікувати помилки, які можуть бути властивими архітектурі програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-298">Let’s us classify errors that might be specific to an architecture of the application.</span></span>

  - <span data-ttu-id="1bd6a-299">**Click2RunPackageVersion** – номер версії пакета "Office умить", з якого було інстальовано програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-299">**Click2RunPackageVersion** - The version number of the Click-To-Run package that installed the app.</span></span> <span data-ttu-id="1bd6a-300">Дає змогу визначити, яку версію інсталятора було використано для інсталяції Office, що допомагає ідентифікувати проблеми, пов’язані з інсталяцією.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-300">Allows us to identify which version of the installer was used to install Office so we can identify setup related issues.</span></span>

  - <span data-ttu-id="1bd6a-301">**DistributionChannel** – канал, яким було розгорнуто програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-301">**DistributionChannel** - The channel where the app was deployed.</span></span> <span data-ttu-id="1bd6a-302">Дає змогу розподіляти дані, що надходять, так що можна визначити, чи впливають проблеми на певну аудиторію.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-302">Allows us to partition incoming data so we can determine if issues are impacting audiences.</span></span>

  - <span data-ttu-id="1bd6a-303">**InstallMethod** – чи було поточну збірку Office оновлено зі старішої збірки, відкочено з новішої збірки на старішу, або це цілком нова інсталяція.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-303">**InstallMethod** - Whether the current build of Office was upgraded from an older build, rolled back to an older build, or a fresh install.</span></span>

  - <span data-ttu-id="1bd6a-304">**IsClickToRunInstall** – позначка, яке вказує, чи було використано для інсталяції пакет "Office умить".</span><span class="sxs-lookup"><span data-stu-id="1bd6a-304">**IsClickToRunInstall** - Flag indicating if install was a click to run install.</span></span> <span data-ttu-id="1bd6a-305">Дає змогу визначити проблеми, які можуть стосуватися певного механізму інсталяції "Office умить".</span><span class="sxs-lookup"><span data-stu-id="1bd6a-305">Allows us to identify issues that might be specific to the Click-To-Run install mechanism.</span></span>

  - <span data-ttu-id="1bd6a-306">**IsDebug** – позначка, яка вказує, чи є збірка Office налагоджувальною.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-306">**IsDebug** - Flag indicating if the office build is a Debug build.</span></span> <span data-ttu-id="1bd6a-307">Дає змогу визначити, чи походять проблеми з налагоджувальних збірок, які може працювати інакше.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-307">Allows us to identify if issues are coming from Debug builds which may behave differently .</span></span>

  - <span data-ttu-id="1bd6a-308">**IsInstalledOnExternalStorage** – позначка, яка вказує, чи інстальовано пакет Office на зовнішньому пристрої зберігання.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-308">**IsInstalledOnExternalStorage** - Flag indicating if Office was installed on an external storage device.</span></span> <span data-ttu-id="1bd6a-309">Допомагає з’ясувати, чи можна звести проблеми до зовнішнього пристрою зберігання.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-309">Let’s us determine if issues can be traced to an external storage location.</span></span>

  - <span data-ttu-id="1bd6a-310">**IsOEMInstalled** – позначка, яка вказує, чи інстальовано пакет Office постачальником обчислювальної техніки (OEM).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-310">**IsOEMInstalled** - Flag indicating if Office was installed by an original equipment manufacturer (OEM).</span></span> <span data-ttu-id="1bd6a-311">Дає змогу з’ясувати, чи це OEM-інсталяція програми, що допомагає класифікувати й виявляти проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-311">Let’s us determine if the application was installed by an OEM which can help us classify and identify issues.</span></span>

  - <span data-ttu-id="1bd6a-312">**PreviousVersion** – версія Office, яку перед цим було інстальовано на комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-312">**PreviousVersion** - The version of Office that was previously installed on the machine.</span></span> <span data-ttu-id="1bd6a-313">Дає змогу відкотити пакет до попередньої версії, якщо в поточній версії виникла проблема.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-313">Allows us to roll back to a previous version if the current one has an issue.</span></span>

  - <span data-ttu-id="1bd6a-314">**ProcessFileName** – ім'я файлу програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-314">**ProcessFileName** - The name of the application filename.</span></span> <span data-ttu-id="1bd6a-315">Дає змогу визначити ім'я виконуваного файлу, який генерує дані, оскільки може бути кілька файлів, про які повідомляється як про одну програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-315">Allows us to identify the name of the executable which is generating the data as there may be several different process filenames reporting as the same app name.</span></span>

#### <a name="client"></a><span data-ttu-id="1bd6a-316">Client</span><span class="sxs-lookup"><span data-stu-id="1bd6a-316">Client</span></span>

<span data-ttu-id="1bd6a-317">Відомості про клієнт Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-317">Information about the Office client.</span></span>

<span data-ttu-id="1bd6a-318">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-318">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-319">**FirstRunTime** – час першого запуску клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-319">**FirstRunTime** - The first time the client was run.</span></span> <span data-ttu-id="1bd6a-320">Дає змогу зрозуміти, скільки часу минуло з інсталяції Office у клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-320">Allows us to understand how long the client has had Office installed.</span></span>

#### <a name="device"></a><span data-ttu-id="1bd6a-321">Device</span><span class="sxs-lookup"><span data-stu-id="1bd6a-321">Device</span></span>

<span data-ttu-id="1bd6a-322">Відомості про конфігурацію та можливості пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-322">Information about device configuration and capabilities.</span></span>

<span data-ttu-id="1bd6a-323">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-323">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-324">**DigitizerInfo** – відомості про дігітайзер, який використовується на комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-324">**DigitizerInfo** - Information on the digitizer used by the machine.</span></span> <span data-ttu-id="1bd6a-325">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-325">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-326">**FormFactor** – визначає форм-фактор пристрою, який надсилає інформацію.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-326">**FormFactor** - Identifies what form factor the device sending the info is.</span></span> <span data-ttu-id="1bd6a-327">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-327">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-328">**FormFactorFamily** – визначає форм-фактор пристрою, який надсилає інформацію.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-328">**FormFactorFamily** - Identifies what form factor the device sending the info is.</span></span> <span data-ttu-id="1bd6a-329">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-329">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-330">**HorizontalResolution** – горизонтальна роздільна здатність екрана пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-330">**HorizontalResolution** - The horizontal resolution of the devices screen.</span></span> <span data-ttu-id="1bd6a-331">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-331">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-332">**Id** – унікальний ідентифікатор пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-332">**Id** - A unique identifier for the device.</span></span> <span data-ttu-id="1bd6a-333">Дає змогу визначити розподіл проблеми в сукупності пристроїв.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-333">Allows us to identify the distribution of issues across a set of devices.</span></span>

  - <span data-ttu-id="1bd6a-334">**IsEDPPolicyEnabled** – позначка, яка вказує, чи ввімкнуто на комп’ютері розширений захист даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-334">**IsEDPPolicyEnabled** - Flag to indicate if enhanced data protection is enabled on the machine.</span></span> <span data-ttu-id="1bd6a-335">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-335">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-336">**IsTerminalServer** – позначка, яка вказує, чи є комп'ютера сервером терміналів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-336">**IsTerminalServer** - Flag to determine if the machine is a terminal server.</span></span> <span data-ttu-id="1bd6a-337">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-337">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-338">**Manufacturer** – виробник пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-338">**Manufacturer** - The manufacturer of the device.</span></span> <span data-ttu-id="1bd6a-339">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-339">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-340">**Model** – модель пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-340">**Model** - The model of the device.</span></span> <span data-ttu-id="1bd6a-341">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-341">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-342">**MotherboardUUIDHash** – геш-код унікального ідентифікатора системної плати.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-342">**MotherboardUUIDHash** - A hash of a unique identifier for the motherboard.</span></span> <span data-ttu-id="1bd6a-343">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-343">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-344">**Name** – ім’я пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-344">**Name** - The name of the device.</span></span> <span data-ttu-id="1bd6a-345">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-345">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-346">**NumProcPhysCores** – кількість фізичних ядер на комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-346">**NumProcPhysCores** - The number of physical cores on the machine.</span></span> <span data-ttu-id="1bd6a-347">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-347">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-348">**OsLocale** – локалізація операційної системи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-348">**OsLocale** - The locale of the operating system that is running.</span></span> <span data-ttu-id="1bd6a-349">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-349">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-350">**ProcessorArchitecture** – архітектура процесора.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-350">**ProcessorArchitecture** - The architecture of the processor.</span></span> <span data-ttu-id="1bd6a-351">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-351">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-352">**ProcessorCount** – кількість процесорів на комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-352">**ProcessorCount** - The number of processors on the machine.</span></span> <span data-ttu-id="1bd6a-353">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-353">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-354">**ProcSpeedMHz** – швидкість процесора.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-354">**ProcSpeedMHz** - The speed of the processor.</span></span> <span data-ttu-id="1bd6a-355">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-355">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-356">**RamMB** – обсяг пам'яті, яку має пристрій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-356">**RamMB** - The amount of memory the device has.</span></span> <span data-ttu-id="1bd6a-357">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-357">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-358">**ScreenDepth** – дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-358">**ScreenDepth** - Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-359">**ScreenDPI** – роздільна здатність екрана в точках на дюйм.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-359">**ScreenDPI** - The DPI value of the screen.</span></span> <span data-ttu-id="1bd6a-360">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-360">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-361">**SusClientId** – ідентифікатор Windows Update пристрою, на якому працює Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-361">**SusClientId** - The Windows Update id of the device Office is run on.</span></span>

  - <span data-ttu-id="1bd6a-362">**SystemVolumeFreeSpaceMB** – обсяг вільного місця на системному томі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-362">**SystemVolumeFreeSpaceMB** - The amount of free space on the system volume.</span></span> <span data-ttu-id="1bd6a-363">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-363">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-364">**SystemVolumeSizeMB** – розмір системного тому на комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-364">**SystemVolumeSizeMB** - The size of the system volume on the machine.</span></span> <span data-ttu-id="1bd6a-365">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-365">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-366">**VerticalResolution** – вертикальна роздільна здатність екрана пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-366">**VerticalResolution** - The vertical resolution of the devices screen.</span></span> <span data-ttu-id="1bd6a-367">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-367">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-368">**WindowErrorReportingMachineId** – унікальний ідентифікатор комп’ютера, наданий службою звітування про помилки Windows.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-368">**WindowErrorReportingMachineId** - A unique machine identifier provided by Windows error reporting.</span></span> <span data-ttu-id="1bd6a-369">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-369">Allows us to classify data based on device pivot.</span></span>

  - <span data-ttu-id="1bd6a-370">**WindowSqmMachineId** – унікальний ідентифікатор комп'ютера, наданий службою Windows SQM.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-370">**WindowSqmMachineId** - A unique identifier for the machine provided by Windows SQM.</span></span> <span data-ttu-id="1bd6a-371">Дає змогу класифікувати дані виходячи з характеристик пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-371">Allows us to classify data based on device pivot.</span></span>

#### <a name="event"></a><span data-ttu-id="1bd6a-372">Event</span><span class="sxs-lookup"><span data-stu-id="1bd6a-372">Event</span></span> 

<span data-ttu-id="1bd6a-373">Відомості про конкретну подію, зокрема її унікальний ідентифікатор у сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-373">Event-specific information, including its unique identifier in the session.</span></span>

<span data-ttu-id="1bd6a-374">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-374">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-375">**Contract** – перелік усіх контрактів, які реалізує подія.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-375">**Contract** - A list of any contracts that the event is implementing.</span></span> <span data-ttu-id="1bd6a-376">Дає змогу з’ясувати, які дані належать до певної події, щоб їх можна було ефективно обробити.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-376">Allows us to evaluate what data is part of the individual event so that we can process it effectively.</span></span>

  - <span data-ttu-id="1bd6a-377">**CV** – значення, яке дає змогу ідентифікувати події, пов'язані між собою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-377">**CV** - A value that allows us to identify events that are related to one another.</span></span> <span data-ttu-id="1bd6a-378">Використовується для потреб діагностики, щоб можна було виявити закономірності пов’язаної поведінки або пов’язаних подій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-378">Used for diagnostics to allow us to identify patterns of related behavior or related events.</span></span>

  - <span data-ttu-id="1bd6a-379">**Flags** – відомості, які використовуються для змінення реакції певної події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-379">**Flags** - Information used to alter how a given event responds.</span></span> <span data-ttu-id="1bd6a-380">Служить для керування обробкою події для потреб завантаження даних до корпорації Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-380">Used to manage how a given event is treated for the purposes of uploading the data to Microsoft.</span></span>

  - <span data-ttu-id="1bd6a-381">**Id** – унікальний ідентифікатор події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-381">**Id** - A unique identifier for the event.</span></span> <span data-ttu-id="1bd6a-382">Дає змогу однозначно визначити події, які надходять.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-382">Allows us to uniquely identify the events that are being received.</span></span>

  - <span data-ttu-id="1bd6a-383">**Name** – ім’я події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-383">**Name** - The name of the event.</span></span> <span data-ttu-id="1bd6a-384">Дає змогу ідентифікувати подію, яка надійшла від клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-384">Allows to identify the event that was being sent from the client.</span></span>

  - <span data-ttu-id="1bd6a-385">**Rule** – ідентифікатор правила, яке створило дані, якщо їх було створено правилом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-385">**Rule** - An identifier of the rule that generated the data if it was generated by a rule.</span></span> <span data-ttu-id="1bd6a-386">Дає змогу визначити джерело елемента даних, щоб можна було перевіряти параметри події та керувати ними.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-386">Allows us to identify the source of a piece of data so that we can validate and manage that events parameters</span></span>

  - <span data-ttu-id="1bd6a-387">**RuleId** – ідентифікатор правила, яке створило дані, якщо їх було створено правилом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-387">**RuleId** - The identifier of the rule that generated the data if it was generated by a rule.</span></span> <span data-ttu-id="1bd6a-388">Дає змогу визначити джерело елемента даних, щоб можна було перевіряти параметри події та керувати ними.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-388">Allows us to identify the source of a piece of data so that we can validate and manage that events parameters.</span></span>

  - <span data-ttu-id="1bd6a-389">**RuleInterfaces** – будь-які інтерфейси, які реалізуються поточним правилом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-389">**RuleInterfaces** - Any interfaces that are implemented by the specific rule.</span></span> <span data-ttu-id="1bd6a-390">Дає змогу класифікувати й імпортувати дані виходячи з їхньої структури, що спрощує обробку даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-390">Allows us to classify and import the data based on its structure which simplifies data processing.</span></span>

  - <span data-ttu-id="1bd6a-391">**RuleVersion** – ідентифікатор правила, яке створило дані, якщо їх було створено правилом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-391">**RuleVersion** - The identifier of the rule that generated the data if it was generated by a rule.</span></span> <span data-ttu-id="1bd6a-392">Дає змогу визначити джерело елемента даних, щоб можна було перевіряти параметри події та керувати ними.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-392">Allows us to identify the source of a piece of data so that we can validate and manage that events parameters.</span></span>

  - <span data-ttu-id="1bd6a-393">**SampleRate** – указує, який відсоток користувачів надсилають цей елемент даних. Це дає змогу проводити статистичний аналіз даних і для дуже поширених точок даних не вимагати, щоб дані надсилали всі користувачі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-393">**SampleRate** - An indication of what percentage of users are sending this piece of data This allows us to do statistical analysis of the data and for very common data points not require that to be sent by all users.</span></span>

  - <span data-ttu-id="1bd6a-394">**SchemaVersion** – версія схеми, яка використовувалася для створення діагностичних даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-394">**SchemaVersion** - The version of the schema used to generate diagnostic data.</span></span> <span data-ttu-id="1bd6a-395">Це поле необхідне для керування даними, які надсилаються клієнтом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-395">Required to manage data being sent form the client.</span></span> <span data-ttu-id="1bd6a-396">Воно дає змогу з часом змінювати дані, які має надсилати кожен клієнт.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-396">This allows changes over time in what data is being sent from each client.</span></span>

  - <span data-ttu-id="1bd6a-397">**Sequence** – лічильник, який визначає порядок, в якому подію було створено в клієнті.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-397">**Sequence** - A counter that identifies the order that an event was generated on the client.</span></span> <span data-ttu-id="1bd6a-398">Дає змогу впорядковувати отримувані дані, що допомагає з’ясувати, які кроки могли призвести до проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-398">Allows the data being received to be ordered so that we can identify what steps may have led to an issue that is impacting clients.</span></span>

  - <span data-ttu-id="1bd6a-399">**Source** – вихідний конвеєр, який було використано, щоб передати дані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-399">**Source** - The source pipeline that was used to upload the data.</span></span> <span data-ttu-id="1bd6a-400">Це поле необхідне для стеження за загальним станом кожного з наших передавальних конвеєрів і для виявлення проблем із передавальним конвеєром.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-400">Required to monitor each of our upload pipelines for overall health and to help identify issues with the upload pipeline.</span></span> <span data-ttu-id="1bd6a-401">Воно дає змогу відстежувати окремі передавальні конвеєри та контролювати їхню відповідність вимогам.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-401">This allows us to monitor individual upload pipelines to make sure they remain compliant.</span></span>

  - <span data-ttu-id="1bd6a-402">**Time** – час створення події в клієнті.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-402">**Time** - The time that the event was generated on the client.</span></span> <span data-ttu-id="1bd6a-403">Дає змогу синхронізувати та перевіряти порядок подій, створюваних у клієнті, а також установлювати показники продуктивності для користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-403">Allows us to synchronize and validate the order of events generated on the client as well as establish performance metrics for user instructions.</span></span> 

#### <a name="host"></a><span data-ttu-id="1bd6a-404">Host</span><span class="sxs-lookup"><span data-stu-id="1bd6a-404">Host</span></span>

<span data-ttu-id="1bd6a-405">Відомості про програму, в якій розміщено вбудовану програму.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-405">Information about an application that hosts an embedded application</span></span>

<span data-ttu-id="1bd6a-406">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-406">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-407">**Id** – унікальний ідентифікатор, призначений хост-програмі вбудованою програмою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-407">**Id** - The unique identifier attributed to the host application by the embedded application.</span></span>

  - <span data-ttu-id="1bd6a-408">**SessionId** – глобальний унікальний ідентифікатор сеансу хоста.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-408">**SessionId** - The globally unique identifier for the host’s session.</span></span>

  - <span data-ttu-id="1bd6a-409">**Version** – ідентифікатор версії основного виконуваного файлу хоста.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-409">**Version** - The version identifier of the host’s primary executable.</span></span>

#### <a name="legacy"></a><span data-ttu-id="1bd6a-410">Legacy</span><span class="sxs-lookup"><span data-stu-id="1bd6a-410">Legacy</span></span>

<span data-ttu-id="1bd6a-411">Відомості, необхідні для сумісності із застарілими системами.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-411">Information needed for legacy system compatibility.</span></span>

<span data-ttu-id="1bd6a-412">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-412">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-413">**OsBuild** – номер збірки операційної системи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-413">**OsBuild** - The specific build number of the operating system.</span></span> <span data-ttu-id="1bd6a-414">Дає змогу визначити, з якої версії операційної системи надходять діагностичні дані, щоб правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-414">Allows us to determine which version of the operating system the diagnostic data is coming from in order to prioritize issues.</span></span>

  - <span data-ttu-id="1bd6a-415">**OsBuildRevision** – редакція збірки операційної системи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-415">**OsBuildRevision** - The revision number of the build of the operating system.</span></span> <span data-ttu-id="1bd6a-416">Дає змогу визначити, з якої версії операційної системи надходять діагностичні дані, щоб правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-416">Allows us to determine which version of the operating system the diagnostic data is coming from in order to prioritize issues.</span></span>

  - <span data-ttu-id="1bd6a-417">**OsMinorVersion** – проміжна версія операційної системи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-417">**OsMinorVersion** - The minor version of the operating system.</span></span> <span data-ttu-id="1bd6a-418">Дає змогу визначити, з якої версії операційної системи надходять діагностичні дані, щоб правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-418">Allows us to determine which version of the operating system the diagnostic data is coming from in order to prioritize issues.</span></span>

  - <span data-ttu-id="1bd6a-419">**OsVersionString** – уніфікований рядок, який представляє номер збірки операційної системи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-419">**OsVersionString** - A unified string representing the operating system build number.</span></span> <span data-ttu-id="1bd6a-420">Дає змогу визначити, з якої версії операційної системи надходять діагностичні дані, щоб правильно визначити пріоритетність проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-420">Allows us to determine which version of the operating system the diagnostic data is coming from in order to prioritize issues.</span></span>

#### <a name="session"></a><span data-ttu-id="1bd6a-421">Session</span><span class="sxs-lookup"><span data-stu-id="1bd6a-421">Session</span></span>

<span data-ttu-id="1bd6a-422">Відомості про сеанс процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-422">Information about the process session.</span></span>

<span data-ttu-id="1bd6a-423">Ця категорія містить такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-423">This category contains the following fields:</span></span>

  - <span data-ttu-id="1bd6a-424">**ABConfigsDelta** – відстежує відмінність між поточними даними ABConfigs і попереднім значенням.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-424">**ABConfigsDelta** - Tracks the difference between the current ABConfigs data and the previous value.</span></span> <span data-ttu-id="1bd6a-425">Дає змогу відстежувати, які нові тести є на комп'ютері, що допомагає з’ясувати, чи відповідає новий тест за проблему.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-425">Allows us to track what new flights are on the machine to help identify if a new flight is responsible for an issue.</span></span>

  - <span data-ttu-id="1bd6a-426">**CollectibleClassification** – класи інформації, які можуть збиратися в сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-426">**CollectibleClassification** - The classes of information the session can collect.</span></span> <span data-ttu-id="1bd6a-427">Дає змогу фільтрувати сеанси виходячи з їхніх даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-427">Allows filtering of sessions based on the data they would have.</span></span>

  - <span data-ttu-id="1bd6a-428">**DisableTelemetry** – позначка, яка вказує, чи задано ключ DisableTelemetry.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-428">**DisableTelemetry** - Flag indicating if the DisableTelemetry key is set.</span></span> <span data-ttu-id="1bd6a-429">Сповіщає, чи повідомляє сеанс інші діагностичні дані, окрім EssentialServiceMetadata.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-429">Allows us to know if a session was not reporting diagnostic data other than EssentialServiceMetadata.</span></span>

  - <span data-ttu-id="1bd6a-430">**SamplingKey** – ключ, який визначає, чи виконується вибірка в сеансі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-430">**SamplingKey** - The key used to determine whether the session is sampled or not.</span></span> <span data-ttu-id="1bd6a-431">Дає змогу зрозуміти, як в окремих сеансах здійснюється вибір стосовно використання вибірки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-431">Allows us to understand how individual sessions are making their choice of whether they are sampled or not.</span></span>

  - <span data-ttu-id="1bd6a-432">**SamplingMethod** – метод, який визначає політику вибірки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-432">**SamplingMethod** - The method used to determine sampling policy.</span></span> <span data-ttu-id="1bd6a-433">Дає змогу зрозуміти, які дані надходять із сеансу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-433">Allows us to understand what data is coming from a session.</span></span>

  - <span data-ttu-id="1bd6a-434">**Sequence** – унікальний числовий ідентифікатор для сеансу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-434">**Sequence** - A unique numeric identifier for the session.</span></span> <span data-ttu-id="1bd6a-435">Дає змогу вибирати сеанси для аналізу можливих проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-435">Allows the ordering of sessions for analysis of then issues might have occurred.</span></span>

  - <span data-ttu-id="1bd6a-436">**Start** – час завантаження сеансу процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-436">**Start** - The boot time of the process session.</span></span> <span data-ttu-id="1bd6a-437">Дає змогу визначити, коли почався сеанс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-437">Allows us to establish when the session started.</span></span>

  - <span data-ttu-id="1bd6a-438">**TimeZoneBiasInMinutes** – різниця в хвилинах між UTC та місцевим часом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-438">**TimeZoneBiasInMinutes** - The difference in minutes between UTC and the local time.</span></span> <span data-ttu-id="1bd6a-439">Забезпечує приведення часу UTC до місцевого часу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-439">Allows normalization of UTC times back to the local time.</span></span>

  - <span data-ttu-id="1bd6a-440">**SamplingClientIdValue** – значення ключа, який визначає вибірку.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-440">**SamplingClientIdValue** - The value of the key used to determine sampling.</span></span> <span data-ttu-id="1bd6a-441">Дає змогу визначити, чи виконувалася в сеансі вибірка.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-441">Allows us to determine why a session was sampled or not.</span></span>

  - <span data-ttu-id="1bd6a-442">**SamplingDeviceIdValue** – значення ключа, який визначає вибірку.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-442">**SamplingDeviceIdValue** - The value of the key used to determine sampling.</span></span> <span data-ttu-id="1bd6a-443">Дає змогу визначити, чи виконувалася в сеансі вибірка.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-443">Allows us to determine why a session was sampled or not.</span></span>

  - <span data-ttu-id="1bd6a-444">**SamplingSessionKValue** – розширені метадані вибірки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-444">**SamplingSessionKValue** - Advanced sampling metadata.</span></span> <span data-ttu-id="1bd6a-445">Допомагає оцінити статистичну значущість отриманих даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-445">Used to help evaluate statistical meaning of data that is received.</span></span>

  - <span data-ttu-id="1bd6a-446">**SamplingSessionNValue** – розширені метадані вибірки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-446">**SamplingSessionNValue** - Advanced sampling metadata.</span></span> <span data-ttu-id="1bd6a-447">Допомагає оцінити статистичну значущість отриманих даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-447">Used to help evaluate statistical meaning of data that is received.</span></span>

  - <span data-ttu-id="1bd6a-448">**TelemetryPermissionLevel** – показує, який рівень діагностичних даних дозволив користувач.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-448">**TelemetryPermissionLevel** - Value indicating what level of diagnostic data the user has opted into.</span></span> <span data-ttu-id="1bd6a-449">Дає змогу зрозуміти, який рівень діагностичних даних слід очікувати від сеансу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-449">Allows us to understand what level of diagnostic data to expect from a session.</span></span>

## <a name="software-setup-and-inventory-data-events"></a><span data-ttu-id="1bd6a-450">Події даних настроювання та обліку програмного забезпечення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-450">Software setup and inventory data events</span></span>

<span data-ttu-id="1bd6a-451">Нижче наведено підтипи даних у цій категорії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-451">The following are the data subtypes in this category:</span></span>
- [<span data-ttu-id="1bd6a-452">Настроювання та облік Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-452">Office setup and inventory</span></span>](#office-setup-and-inventory-subtype)
- [<span data-ttu-id="1bd6a-453">Конфігурація надбудов Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-453">Office add-in configuration</span></span>](#office-add-in-configuration-subtype)
- [<span data-ttu-id="1bd6a-454">Безпека</span><span class="sxs-lookup"><span data-stu-id="1bd6a-454">Security</span></span>](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a><span data-ttu-id="1bd6a-455">*Підтип настроювання та обліку Office*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-455">*Office setup and inventory subtype*</span></span>

<span data-ttu-id="1bd6a-456">Назва та версія інстальованого продукту, стан інсталяції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-456">Installed product and version and the installation status.</span></span>

#### <a name="officeclicktorunupdatestatus"></a><span data-ttu-id="1bd6a-457">Office.ClickToRun.UpdateStatus</span><span class="sxs-lookup"><span data-stu-id="1bd6a-457">Office.ClickToRun.UpdateStatus</span></span>

<span data-ttu-id="1bd6a-458">Застосовується до всіх програм win32.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-458">Applicable to all win32 applications.</span></span> <span data-ttu-id="1bd6a-459">Допомагає зрозуміти стан процесу оновлення програмного комплексу Office (успіх або невдача з відомостями про помилку).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-459">Helps us understand the status of the update process of the office suite (Success or failure with error details)</span></span>

<span data-ttu-id="1bd6a-460">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-460">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-461">**build** – інстальована на цей час версія Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-461">**build** - Currently installed Office version</span></span>

- <span data-ttu-id="1bd6a-462">**channel** – канал, яким було розповсюджено Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-462">**channel** - The channel by which Office was distributed</span></span>

- <span data-ttu-id="1bd6a-463">**errorCode** – код помилки, який описує невдачу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-463">**errorCode** - Error code indicating the failure</span></span>

- <span data-ttu-id="1bd6a-464">**errorMessage** – додаткові відомості про помилку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-464">**errorMessage** - Additional error information</span></span>

- <span data-ttu-id="1bd6a-465">**status** – поточний статус оновлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-465">**status** - Current status of the update</span></span>

- <span data-ttu-id="1bd6a-466">**targetBuild** – нова версія Office, перехід на яку відбувається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-466">**targetBuild** - Version Office is updating to</span></span>

#### <a name="officecorrelationmetadatautccorrelationmetadata"></a><span data-ttu-id="1bd6a-467">Office.CorrelationMetadata.UTCCorrelationMetadata</span><span class="sxs-lookup"><span data-stu-id="1bd6a-467">Office.CorrelationMetadata.UTCCorrelationMetadata</span></span>

<span data-ttu-id="1bd6a-468">Збирає метадані Office через UTC для порівняння з еквівалентними даними, які збираються конвеєром телеметрії Office, з метою перевірки правильності й повноти даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-468">Collects Office metadata through UTC to compare with equivalent data collected through the Office telemetry pipeline to check correctness and completeness of data.</span></span>

<span data-ttu-id="1bd6a-469">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-469">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-470">**abConfigs** – список ідентифікаторів функцій, які ввімкнуто в клієнті, або пустий, якщо ці дані не збираються.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-470">**abConfigs** - A list of feature IDs to identify which features are enabled on the client or empty when this data is not being collected.</span></span>

- <span data-ttu-id="1bd6a-471">**abFlights** – "NoNL:NoFlights", якщо тести функцій не задано.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-471">**abFlights** - "NoNL:NoFlights" when the feature flights aren't set.</span></span> <span data-ttu-id="1bd6a-472">В іншому разі "holdoutinfo=unknown".</span><span class="sxs-lookup"><span data-stu-id="1bd6a-472">Otherwise "holdoutinfo=unknown".</span></span>

- <span data-ttu-id="1bd6a-473">**AppSessionGuid** – ідентифікатор сеансу певної програми, який почався в момент створення процесу та існує до закінчення процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-473">**AppSessionGuid** - An identifier of a particular application session starting at process creation time and persisting until process end.</span></span> <span data-ttu-id="1bd6a-474">Він має формат стандартного 128-бітного глобального унікального ідентифікатора (GUID), але складається з 4 частин.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-474">It is formatted as a standard 128-bit GUID but constructed of 4 parts.</span></span> <span data-ttu-id="1bd6a-475">Це такі частини: (1) 32-бітний ідентифікатор процесу, (2) 16-бітний ідентифікатор сеансу, (3) 16-бітний ідентифікатор завантаження та (4) 64-бітний час створення процесу за UTC з кроком 100 нс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-475">Those four parts in order are (1) 32 bit Process ID (2) 16 bit Session ID (3) 16 bit Boot ID (4) 64 bit Process creation time in UTC 100ns</span></span>

- <span data-ttu-id="1bd6a-476">**appVersionBuild** – номер версії збірки програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-476">**appVersionBuild** - The app build version number.</span></span>

- <span data-ttu-id="1bd6a-477">**appVersionMajor** – номер основної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-477">**appVersionMajor** - The app major version number.</span></span>

- <span data-ttu-id="1bd6a-478">**appVersionMinor** – номер проміжної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-478">**appVersionMinor** - The app minor version number.</span></span>

- <span data-ttu-id="1bd6a-479">**appVersionRevision** – редакція версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-479">**appVersionRevision** - The app revision version number.</span></span>

- <span data-ttu-id="1bd6a-480">**audienceGroup** – ім’я групи аудиторії випуску</span><span class="sxs-lookup"><span data-stu-id="1bd6a-480">**audienceGroup** - The release audience group name</span></span>

- <span data-ttu-id="1bd6a-481">**audienceId** – ім’я аудиторії випуску</span><span class="sxs-lookup"><span data-stu-id="1bd6a-481">**audienceId** - The release audience name</span></span>

- <span data-ttu-id="1bd6a-482">**channel** – канал, яким було розповсюджено Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-482">**channel** - The channel by which Office was distributed</span></span>

- <span data-ttu-id="1bd6a-483">**deviceClass** – форм-фактор пристрою з ОС</span><span class="sxs-lookup"><span data-stu-id="1bd6a-483">**deviceClass** - Device form factor from the OS</span></span>

- <span data-ttu-id="1bd6a-484">**ecsETag** – ідентифікатор експерименту для процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-484">**ecsETag** - An experiment identifier for the process</span></span>

- <span data-ttu-id="1bd6a-485">**impressionId** – глобальний унікальний ідентифікатор, що вказує поточний набір функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-485">**impressionId** - A guid indicating the current set of features.</span></span>

- <span data-ttu-id="1bd6a-486">**languageTag** – тег поточної мови IETF інтерфейсу користувача Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-486">**languageTag** - The current Office UI IETF language tag</span></span>

- <span data-ttu-id="1bd6a-487">**officeUserID** – випадково згенерований глобальний унікальний ідентифікатор для цієї інсталяції Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-487">**officeUserID** - Randomly generated guid for this Office install</span></span>

- <span data-ttu-id="1bd6a-488">**osArchitecture** – архітектура операційної системи</span><span class="sxs-lookup"><span data-stu-id="1bd6a-488">**osArchitecture** - Operating system architecture</span></span>

- <span data-ttu-id="1bd6a-489">**osEnvironment** – ціле число, яке зазначає операційну систему (Windows, Android, iOS, Mac тощо).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-489">**osEnvironment** - An integer indicating the operating system (Windows, Android, iOS, Mac, etc).</span></span>

- <span data-ttu-id="1bd6a-490">**osVersionString** – версія операційної системи</span><span class="sxs-lookup"><span data-stu-id="1bd6a-490">**osVersionString** - Operating system version</span></span>

- <span data-ttu-id="1bd6a-491">**sessionID** – випадково згенерований глобальний унікальний ідентифікатор для позначення сеансу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-491">**sessionID** - Randomly generated guid to identify the app session</span></span>

- <span data-ttu-id="1bd6a-492">**UTCReplace_AppSessionGuid** – логічна константа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-492">**UTCReplace_AppSessionGuid** - Constant boolean value.</span></span> <span data-ttu-id="1bd6a-493">Завжди має значення TRUE.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-493">Always true.</span></span>

#### <a name="officetargetedmessagingensurecached"></a><span data-ttu-id="1bd6a-494">Office.TargetedMessaging.EnsureCached</span><span class="sxs-lookup"><span data-stu-id="1bd6a-494">Office.TargetedMessaging.EnsureCached</span></span> 

<span data-ttu-id="1bd6a-495">Показує, чи було завантажено пакет динамічного полотна.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-495">Tracks if a package for Dynamic Canvas was downloaded.</span></span> <span data-ttu-id="1bd6a-496">Вважається конфігурацією програмного забезпечення, оскільки пакет має бути успішно завантажено для належної роботи клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-496">Considered a software configuration because the package must be successfully downloaded to enable the client to render the right experience.</span></span> <span data-ttu-id="1bd6a-497">Це особливо важливо для користувацьких передплат, де полотно використовується, щоб сповістити користувача про закінчення ліцензії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-497">Is especially critical in consumer subscriptions where we use canvas to communicate to the user that the license has expired.</span></span> <span data-ttu-id="1bd6a-498">Використовується для відстеження метаданих пакета динамічного вмісту, який завантажується та кешується продуктом, а також результатів операцій, виконуваних пакетом: помилок завантаження, помилок розпакування, помилок перевірки узгодженості, кешування, використання пакета, джерел завантаження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-498">Used to track metadata of a dynamic content package downloaded and cached by the product as well as results of operations performed on the package: download failures, unpacking failures, consistency checks failures, cache hits, package usages, download sources.</span></span>

<span data-ttu-id="1bd6a-499">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-499">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-500">**Data\_CacheFolderNotCreated** – логічна позначка, яка вказує, чи успішно створено папку кешу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-500">**Data\_CacheFolderNotCreated -** Boolean flag indicating if cache folder creation succeed</span></span>

  - <span data-ttu-id="1bd6a-501">**Data\_CdnPath – вихідна адреса пакета**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-501">**Data\_CdnPath – source address of the package-**</span></span>

  - <span data-ttu-id="1bd6a-502">**Data\_EnsureCached** – логічна позначка, яка вказує, чи було кешовано пакет вмісту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-502">**Data\_EnsureCached -** Boolean flag indicating if content package was cached</span></span>

  - <span data-ttu-id="1bd6a-503">**Data\_ExistsAlready** – логічна позначка, яка вказує, що пакет уже було раніше завантажено та мала місце інша спроба</span><span class="sxs-lookup"><span data-stu-id="1bd6a-503">**Data\_ExistsAlready -** Boolean flag indicating that the package was already downloaded before and there was another attempt</span></span>

  - <span data-ttu-id="1bd6a-504">**Data\_GetFileStreamFailed** – вихідний пакет недоступний у джерелі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-504">**Data\_GetFileStreamFailed -** source package not available in source</span></span>

  - <span data-ttu-id="1bd6a-505">**Data\_GetFileStreamFailedToCreateLocalFolder** – через проблеми з локальним диском не вдалося створити каталог</span><span class="sxs-lookup"><span data-stu-id="1bd6a-505">**Data\_GetFileStreamFailedToCreateLocalFolder -** local disk issues causing failure in directory creation</span></span>

  - <span data-ttu-id="1bd6a-506">**Data\_GetFileStreamFromPackageFailed** – позначка, яка вказує, що пакет завантажено, але клієнт не може прочитати його</span><span class="sxs-lookup"><span data-stu-id="1bd6a-506">**Data\_GetFileStreamFromPackageFailed -** flag indicating if package was downloaded, but the client can’t read it</span></span>

  - <span data-ttu-id="1bd6a-507">**Data\_GetFileStreamFromPackageSuccess** – успішні спроби прочитати пакет</span><span class="sxs-lookup"><span data-stu-id="1bd6a-507">**Data\_GetFileStreamFromPackageSuccess -** successful attempts to read the package</span></span>

  - <span data-ttu-id="1bd6a-508">**Data\_GetFileStreamSuccess** – немає проблем із диском або проблем конфігурації, які перешкоджали б читанню файлового потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-508">**Data\_GetFileStreamSuccess -** no disk issues nor configuration issues which doesn’t let the file stream to be read</span></span>

  - <span data-ttu-id="1bd6a-509">**Data\_GetRelativePathsFailed** – відносний шлях не вказує на доступне розташування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-509">**Data\_GetRelativePathsFailed -** relative path doesn’t point to accessible location</span></span>

  - <span data-ttu-id="1bd6a-510">**Data\_HashActualValue** – геш-значення, видобуте з імені файлу під час використання пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-510">**Data\_HashActualValue -** hash value extracted from file name when the package was used</span></span>

  - <span data-ttu-id="1bd6a-511">**Data\_HashCalculationFailed** – помилка обчислення геш-коду</span><span class="sxs-lookup"><span data-stu-id="1bd6a-511">**Data\_HashCalculationFailed -** error with calculation of a hash</span></span>

  - <span data-ttu-id="1bd6a-512">**Data\_HashMatchFailed** – невідповідність геш-кодів між іменем пакета та значеннями з реєстру в кеші</span><span class="sxs-lookup"><span data-stu-id="1bd6a-512">**Data\_HashMatchFailed -** hash mismatch between the package name and registry values cached</span></span>

  - <span data-ttu-id="1bd6a-513">**Data\_HashMatchSuccess** – узгодженість геш-кодів успішно підтверджено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-513">**Data\_HashMatchSuccess -** hash consistency check success</span></span>

  - <span data-ttu-id="1bd6a-514">**Data\_PackageDownloadRequestFailed** – не вдалося завантажити пакет</span><span class="sxs-lookup"><span data-stu-id="1bd6a-514">**Data\_PackageDownloadRequestFailed -** can’t download the package</span></span>

  - <span data-ttu-id="1bd6a-515">**Data\_PackageDownloadRequestNoData** – завантажений пакет не містить даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-515">**Data\_PackageDownloadRequestNoData -** downloaded package contains no data</span></span>

  - <span data-ttu-id="1bd6a-516">**Data\_PackageDownloadRequestSuccess** – успішне завантаження пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-516">**Data\_PackageDownloadRequestSuccess -** successful download of a package</span></span>

  - <span data-ttu-id="1bd6a-517">**Data\_PackageExplodedSuccess** – стан спроб розпакування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-517">**Data\_PackageExplodedSuccess -** unpacking attempts statuses</span></span>

  - <span data-ttu-id="1bd6a-518">**Data\_PackageOpenFailed** – невдалі спроби відкрити файл пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-518">**Data\_PackageOpenFailed -** failed attempts to open the package file</span></span>

  - <span data-ttu-id="1bd6a-519">**Data\_PackageOpenSuccess** – успішні спроби відкрити файл пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-519">**Data\_PackageOpenSuccess -** successful attempts to open the package file</span></span>

  - <span data-ttu-id="1bd6a-520">**Data\_SuccessHashValue** – геш-значення, видобуте з імені файлу під час завантаження пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-520">**Data\_SuccessHashValue -** hash value extracted from file name when the package was downloaded</span></span>

  - <span data-ttu-id="1bd6a-521">**Data\_SuccessSource** – поверхня, для якої було завантажено пакет</span><span class="sxs-lookup"><span data-stu-id="1bd6a-521">**Data\_SuccessSource -** surface for which the package was downloaded</span></span>

#### <a name="officevisiovisiosku"></a><span data-ttu-id="1bd6a-522">Office.Visio.VisioSKU</span><span class="sxs-lookup"><span data-stu-id="1bd6a-522">Office.Visio.VisioSKU</span></span>

<span data-ttu-id="1bd6a-523">Визначає, який обліковий номер Visio SKU – стандартний чи професійний.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-523">Captures Visio SKU whether it's standard or professional.</span></span> <span data-ttu-id="1bd6a-524">Це важливо для впорядкування проблем на основі облікового номера.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-524">Essential to categorize issues based on SKU.</span></span>

<span data-ttu-id="1bd6a-525">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-525">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-526">**Data\_VisioSKU**:**integer** – 0 для стандартного облікового номера та 1 для професійного</span><span class="sxs-lookup"><span data-stu-id="1bd6a-526">**Data\_VisioSKU**:**integer** - 0 for Standard SKU and 1 for Professional SKU</span></span>

### <a name="office-add-in-configuration-subtype"></a><span data-ttu-id="1bd6a-527">*Підтип конфігурації надбудов Office*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-527">*Office add-in configuration subtype*</span></span>

<span data-ttu-id="1bd6a-528">Програмні надбудови та їхні параметри.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-528">Software add-ins and their settings.</span></span>

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a><span data-ttu-id="1bd6a-529">Office.Extensibility.AppCommands.AppCmdProjectionStatus</span><span class="sxs-lookup"><span data-stu-id="1bd6a-529">Office.Extensibility.AppCommands.AppCmdProjectionStatus</span></span>

<span data-ttu-id="1bd6a-530">Збирає відомості про те, які інсталяції надбудов Office успішно оновили стрічку, а які ні.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-530">Collects information to track which Office add-in installations successfully updated the ribbon vs failed.</span></span>

<span data-ttu-id="1bd6a-531">Використовується для вирішення поширених проблем реєстрації, коли надбудови не інсталюються належним чином і не відображаються, внаслідок чого стають недоступними для використання.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-531">Used to fix common registration issues where add-ins are not installed properly and never show up resulting in them being unusable.</span></span>

<span data-ttu-id="1bd6a-532">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-532">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-533">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-533">None</span></span>

#### <a name="officeextensibilitycatalogexchangegetentitlements"></a><span data-ttu-id="1bd6a-534">Office.Extensibility.Catalog.ExchangeGetEntitlements</span><span class="sxs-lookup"><span data-stu-id="1bd6a-534">Office.Extensibility.Catalog.ExchangeGetEntitlements</span></span>

<span data-ttu-id="1bd6a-535">Дані щодо успіху або невдачі отримання даних про права на використання надбудов Office 365, призначених адміністратором клієнта. Використовуються для показників стану, діаграм та аналізу проблем користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-535">Data regarding the success for failure of retrieving add-in entitlement data for the Office 365 tenant admin assigned add-ins. Used for health metrics, charts, and analysis of customer problems.</span></span>

<span data-ttu-id="1bd6a-536">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-536">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-537">**CachingResult** – результат спроби зберегти значення, повернуте викликом служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-537">**CachingResult -** the result of the attempt to save the service call return value</span></span>

  - <span data-ttu-id="1bd6a-538">**ClientParameter** – ідентифікатор клієнта, надісланий у виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-538">**ClientParameter -** client identifier sent in the service call</span></span>

  - <span data-ttu-id="1bd6a-539">**EntitlementsCount** – кількість прав, яка очікується у відповіді на виклик</span><span class="sxs-lookup"><span data-stu-id="1bd6a-539">**EntitlementsCount -** The number of entitlements expected in the call response</span></span>

  - <span data-ttu-id="1bd6a-540">**EntitlementsParsed** – кількість прав, видобутих із відповіді</span><span class="sxs-lookup"><span data-stu-id="1bd6a-540">**EntitlementsParsed -** the number of entitlements parsed from the response</span></span>

  - <span data-ttu-id="1bd6a-541">**IsAllEntitlementsParsed** – чи збігається очікувана кількість прав із кількістю видобутих прав</span><span class="sxs-lookup"><span data-stu-id="1bd6a-541">**IsAllEntitlementsParsed -** whether expected entitlements count matches parsed entitlements count</span></span>

  - <span data-ttu-id="1bd6a-542">**ServiceCallHResult** – результат, повернутий інтерфейсом API виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-542">**ServiceCallHResult -** the result returned by the service call API</span></span>

  - <span data-ttu-id="1bd6a-543">**TelemetryId** – GUID, який представляє унікального користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-543">**TelemetryId -** a GUID representing a unique user</span></span>

  - <span data-ttu-id="1bd6a-544">**UsedCache** – чи використовувалася кешована відповідь замість виконання виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-544">**UsedCache -** whether the cached response was used instead of making a service call</span></span>

  - <span data-ttu-id="1bd6a-545">**VersionParameter** – номер версії Office, надісланий у виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-545">**VersionParameter -** Office version number sent in the service call</span></span>

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a><span data-ttu-id="1bd6a-546">Office.Extensibility.Catalog.ExchangeGetLastUpdate</span><span class="sxs-lookup"><span data-stu-id="1bd6a-546">Office.Extensibility.Catalog.ExchangeGetLastUpdate</span></span>

<span data-ttu-id="1bd6a-547">Дані щодо успіху або невдачі отримання відомостей про необхідність оновлення даних про надбудови Office 365, призначені адміністратором клієнта. Використовуються для показників стану, діаграм та аналізу проблем користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-547">Data regarding the success for failure of retrieving the need for updated data regarding the Office 365 tenant admin assigned add-ins. Used for health metrics, charts, and analysis of customer problems.</span></span> <span data-ttu-id="1bd6a-548">ExchangeGetLastUpdate завжди виконується під час завантаження як частина коду хоста й визначає, чи змінилися призначення надбудов для користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-548">ExchangeGetLastUpdate will always run on boot as part of the host code and determine whether add-in assignments have changed for a user.</span></span> <span data-ttu-id="1bd6a-549"> Якщо так, завантажується osf.DLL, що дає змогу викликати ExchangeGetEntitlements і отримати інформацію про певні призначення (також буде викликано ExchangeGetManifests для отримання будь-яких необхідних нових маніфестів).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-549"> If so then osf.DLL will be loaded so we can call ExchangeGetEntitlements to get the specific assignments (and ExchangeGetManifests will called to retrieve any new manifest that are needed).</span></span> <span data-ttu-id="1bd6a-550"> ExchangeGetEntitlements (і ExchangeGetManifests) також можна викликати на вимогу після запуску хост-програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-550"> ExchangeGetEntitlements (and ExchangeGetManifests) could also be called on demand after host application has been running.</span></span> <span data-ttu-id="1bd6a-551"> Ідея полягає в тому, щоб не завантажувати велику бібліотеку DLL, якщо це не потрібно.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-551"> The idea is to not load the large DLL if we don’t need to.</span></span> <span data-ttu-id="1bd6a-552"> Якщо ця подія не була б обов'язковою, не можна було б дізнатися, що користувачам не вдається отримати призначені їм надбудови в разі невдачі цього першого виклику служби.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-552"> Without this event in Required, we would not be able to tell if users are failing to get add-ins assigned to them if that first service call fails.</span></span> <span data-ttu-id="1bd6a-553"> Крім того, це основна ознака будь-яких проблем авторизації, які можуть виникнути під час звертання до служби.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-553"> It’s also the main signal for any auth problems we face talking to our service.</span></span>

<span data-ttu-id="1bd6a-554">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-554">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-555">**Abort** – чи відбулося завершення роботи хоста під час виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-555">**Abort -** whether the host was shut down during the service call</span></span>

  - <span data-ttu-id="1bd6a-556">**AllowPrompt** – чи було дозволено пропонування автентифікації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-556">**AllowPrompt -** whether auth prompting was allowed</span></span>

  - <span data-ttu-id="1bd6a-557">**AuthScheme** – схема автентифікації, запитана сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-557">**AuthScheme -** the auth scheme requested by exchange</span></span>

  - <span data-ttu-id="1bd6a-558">**BackEndHttpStatus** – код http, повідомлений під час обміну даними з внутрішнім сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-558">**BackEndHttpStatus -** http code reported when talking to exchange back end-</span></span>

  - <span data-ttu-id="1bd6a-559">**BackupUrl** – URL-адреса додаткового сервера Exchange для виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-559">**BackupUrl -** the secondary exchange URL to call</span></span>

  - <span data-ttu-id="1bd6a-560">**BEServer** – ім’я внутрішнього сервера Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-560">**BEServer -** the back-end exchange server name</span></span>

  - <span data-ttu-id="1bd6a-561">**CalculatedBETarget** – повне ім'я комп’ютера внутрішнього сервера Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-561">**CalculatedBETarget -** The full name of the exchange back end machine</span></span>

  - <span data-ttu-id="1bd6a-562">**Call(n)\_TokenAuthError** – помилка автентифікації n-ї спроби виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-562">**Call(n)\_TokenAuthError -** the auth error of the nth service call attempt</span></span>

  - <span data-ttu-id="1bd6a-563">**Call(n)\_TokenIsValid** – чи був чинний маркер автентифікації на n-й спробі виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-563">**Call(n)\_TokenIsValid -** whether the auth token on the nth service attempt was valid</span></span>

  - <span data-ttu-id="1bd6a-564">**CallMethod** – рядок із зазначенням шляху коду</span><span class="sxs-lookup"><span data-stu-id="1bd6a-564">**CallMethod -** a string indicating which path the code took</span></span>

  - <span data-ttu-id="1bd6a-565">**ConfigSvcReady** – чи було ініціалізовано службу конфігурації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-565">**ConfigSvcReady -** whether the config service had been initialized yet</span></span>

  - <span data-ttu-id="1bd6a-566">**Date** – значення, повернуте сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-566">**Date -** value returned by exchange server</span></span>

  - <span data-ttu-id="1bd6a-567">**DiagInfo** – відомості, повернуті сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-567">**DiagInfo -** information returned by exchange server</span></span>

  - <span data-ttu-id="1bd6a-568">**End\_TicketAuthError** – будь-яка помилка під час отримання маркера автентифікації після виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-568">**End\_TicketAuthError -** any error in getting the auth ticket after service call</span></span>

  - <span data-ttu-id="1bd6a-569">**End\_TokenIsValid** – чи є чинним маркер автентифікації після виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-569">**End\_TokenIsValid -** whether the auth ticket is valid after the service call</span></span>

  - <span data-ttu-id="1bd6a-570">**EndingIdentityState** – повідомлений стан об’єктів ідентичності після викликів служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-570">**EndingIdentityState -** identity objects reported state after making the service calls</span></span>

  - <span data-ttu-id="1bd6a-571">**EwsHandler** – значення, повернуте сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-571">**EwsHandler -** value returned from exchange</span></span>

  - <span data-ttu-id="1bd6a-572">**FEServer** – зовнішній сервер Exchange, який обслуговує запит</span><span class="sxs-lookup"><span data-stu-id="1bd6a-572">**FEServer -** the exchange front end servicing the request</span></span>

  - <span data-ttu-id="1bd6a-573">**HResult** – код результату</span><span class="sxs-lookup"><span data-stu-id="1bd6a-573">**HResult -** the result code</span></span>

  - <span data-ttu-id="1bd6a-574">**HttpStatus** – код статусу HTTP, повернутий сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-574">**HttpStatus -** Http status code returned from exchange</span></span>

  - <span data-ttu-id="1bd6a-575">**IsSupportedAuthResponse** – чи підтримується тип автентифікації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-575">**IsSupportedAuthResponse -** whether the auth type is one we can use</span></span>

  - <span data-ttu-id="1bd6a-576">**LastUpdateValueRegistry** – хеш-значення, отримане з реєстру</span><span class="sxs-lookup"><span data-stu-id="1bd6a-576">**LastUpdateValueRegistry -** hash value retrieved from the registry</span></span>

  - <span data-ttu-id="1bd6a-577">**LastUpdateValueRetrieved** – хеш-значення, отримане з виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-577">**LastUpdateValueRetrieved -** hash value returned from the service call</span></span>

  - <span data-ttu-id="1bd6a-578">**MSDiagnostics** – значення, повернуте сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-578">**MSDiagnostics -** value returned from exchange</span></span>

  - <span data-ttu-id="1bd6a-579">**MsoHttpResult** – значення-нумератор, повернуте інтерфейсом http API</span><span class="sxs-lookup"><span data-stu-id="1bd6a-579">**MsoHttpResult -** the enumerator value returned form the http API</span></span>

  - <span data-ttu-id="1bd6a-580">**NeedRefresh** – логічне поле, яке показує, чи потребують оновлення дані надбудови.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-580">**NeedRefresh –-** This is a true or false field indicating whether the add-in data was stale and we needed to update it.</span></span>

  - <span data-ttu-id="1bd6a-581">**PrimaryUrl** – основна URL-адреса для виконання виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-581">**PrimaryUrl -** the main URL to make the service call to</span></span>

  - <span data-ttu-id="1bd6a-582">**RequestId** – значення, повернуте сервером Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-582">**RequestId -** value returned from exchange</span></span>

  - <span data-ttu-id="1bd6a-583">**RequestTryCount** – кількість спроб зробити виклик служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-583">**RequestTryCount -** the number of times we attempted to make the service call</span></span>

  - <span data-ttu-id="1bd6a-584">**RequestTryCount** – кількість спроб звернутися до сервера Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd6a-584">**RequestTryCount -** the number of times we tried to talk to exchange</span></span>

  - <span data-ttu-id="1bd6a-585">**ResultChain** – низка кодів результату з кожної спроби виклику служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-585">**ResultChain -** the series of result code from each of the service call attempts</span></span>

  - <span data-ttu-id="1bd6a-586">**StartingIdentityState** – повідомлений стан об’єктів ідентичності до викликів служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-586">**StartingIdentityState -** identity objects reported state before making service calls</span></span>

  - <span data-ttu-id="1bd6a-587">**TelemetryId** – GUID, який представляє унікального користувача, коли потрібно зробити інші виклики служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-587">**TelemetryId -** a GUID representing a unique user whether we need to make other service calls</span></span>

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a><span data-ttu-id="1bd6a-588">Office.Extensibility.Catalog.ExchangeGetManifests</span><span class="sxs-lookup"><span data-stu-id="1bd6a-588">Office.Extensibility.Catalog.ExchangeGetManifests</span></span>

<span data-ttu-id="1bd6a-589">Дані щодо успіху або невдачі отримання даних про маніфести для надбудов Office 365, призначених адміністратором клієнта. Використовуються для показників стану, діаграм та аналізу проблем користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-589">Data regarding the success for failure of retrieving add-in manifests data for the Office 365 tenant admin assigned add-ins. Used for health metrics, charts, and analysis of customer problems.</span></span>

<span data-ttu-id="1bd6a-590">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-590">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-591">**CachedManifestsParsed** – кількість маніфестів, знайдених у кеші</span><span class="sxs-lookup"><span data-stu-id="1bd6a-591">**CachedManifestsParsed** – the number of manifests found in the cache</span></span>

  - <span data-ttu-id="1bd6a-592">**IsAllReturnedManifestsParsed** – чи вдалося розібрати всі повернуті маніфести</span><span class="sxs-lookup"><span data-stu-id="1bd6a-592">**IsAllReturnedManifestsParsed** – whether all the manifests that were returned were able to be parsed</span></span>

  - <span data-ttu-id="1bd6a-593">**ManifestsRequested** – кількість потрібних маніфестів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-593">**ManifestsRequested** – the number of manifests needed</span></span>

  - <span data-ttu-id="1bd6a-594">**ManifestsReturned** – кількість маніфестів, повернутих сервером</span><span class="sxs-lookup"><span data-stu-id="1bd6a-594">**ManifestsReturned** – the number of manifest returned form the server</span></span>

  - <span data-ttu-id="1bd6a-595">**ManifestsToRetrieve** – кількість маніфестів, які мають надійти з сервера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-595">**ManifestsToRetrieve** – the number of manifests to get form the server</span></span>

  - <span data-ttu-id="1bd6a-596">**ReturnedManifestsParsed** – кількість маніфестів, повернутих сервером і успішно розібраних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-596">**ReturnedManifestsParsed** – the number of manifests returned from the server that were successfully parsed</span></span>

  - <span data-ttu-id="1bd6a-597">**TelemetryId** – GUID, який представляє унікального користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-597">**TelemetryId** – a GUID representing a unique user</span></span>

#### <a name="officeextensibilityuxfensureloadosfdll"></a><span data-ttu-id="1bd6a-598">Office.Extensibility.UX.FEnsureLoadOsfDLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-598">Office.Extensibility.UX.FEnsureLoadOsfDLL</span></span> 

<span data-ttu-id="1bd6a-599">Відстежує невдале завантаження Osf.DLL.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-599">Tracks failure to load Osf.DLL.</span></span> <span data-ttu-id="1bd6a-600">Виявляє помилки завантаження DLL, які перешкоджають запуску функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-600">Detect DLL load failure that prevents feature from running.</span></span>

<span data-ttu-id="1bd6a-601">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-601">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-602">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-602">None</span></span>

#### <a name="officeextensibilityuxfensureloadosfuidll"></a><span data-ttu-id="1bd6a-603">Office.Extensibility.UX.FEnsureLoadOsfUIDLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-603">Office.Extensibility.UX.FEnsureLoadOsfUIDLL</span></span> 

<span data-ttu-id="1bd6a-604">Відстежує невдале завантаження OsfUI.DLL.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-604">Tracks failure to load OsfUI.DLL.</span></span> <span data-ttu-id="1bd6a-605">Виявляє помилки завантаження DLL, які перешкоджають запуску функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-605">Detect DLL load failure that prevents feature from running.</span></span>

<span data-ttu-id="1bd6a-606">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-606">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-607">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-607">None</span></span>

#### <a name="officeextensibilityuxfensureosfshareddllload"></a><span data-ttu-id="1bd6a-608">Office.Extensibility.UX.FEnsureOsfSharedDLLLoad</span><span class="sxs-lookup"><span data-stu-id="1bd6a-608">Office.Extensibility.UX.FEnsureOsfSharedDLLLoad</span></span> 

<span data-ttu-id="1bd6a-609">Відстежує невдале завантаження OsfShared.DLL.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-609">Tracks failure to load OsfShared.DLL.</span></span> <span data-ttu-id="1bd6a-610">Виявляє помилки завантаження DLL, які перешкоджають запуску функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-610">Detect DLL load failure that prevents feature from running.</span></span>

<span data-ttu-id="1bd6a-611">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-611">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-612">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-612">None</span></span>

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a><span data-ttu-id="1bd6a-613">Office.Extensibility.VBATelemetryComObjectInstantiated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-613">Office.Extensibility.VBATelemetryComObjectInstantiated</span></span>

<span data-ttu-id="1bd6a-614">Збирає відомості про звертання до сервера або клієнта автоматизації в рішеннях VBA.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-614">Collects information about invocation of automation server or client in VBA solutions.</span></span> <span data-ttu-id="1bd6a-615">Допомагає зрозуміти взаємодію між об’єктами VBA та Com.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-615">Used to understand interaction between VBA and Com Objects.</span></span>

<span data-ttu-id="1bd6a-616">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-616">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-617">**ComObjectInstantiatedCount** – кількість екземплярів об’єкта COM</span><span class="sxs-lookup"><span data-stu-id="1bd6a-617">**ComObjectInstantiatedCount** – number of COM Object instantiations</span></span>

  - <span data-ttu-id="1bd6a-618">**HashComObjectInstantiatedClsid** – геш-код ідентифікатора класу об’єкта COM</span><span class="sxs-lookup"><span data-stu-id="1bd6a-618">**HashComObjectInstantiatedClsid** – hash of COM Object Class Identifier</span></span>

  - <span data-ttu-id="1bd6a-619">**HashProjectName** – геш-код імені проекту VBA</span><span class="sxs-lookup"><span data-stu-id="1bd6a-619">**HashProjectName** – hash of the VBA project name</span></span>

  - <span data-ttu-id="1bd6a-620">**TagId** – унікальний тег</span><span class="sxs-lookup"><span data-stu-id="1bd6a-620">**TagId** – unique tag</span></span>

#### <a name="officeextensibilityvbatelemetrydeclare"></a><span data-ttu-id="1bd6a-621">Office.Extensibility.VBATelemetryDeclare</span><span class="sxs-lookup"><span data-stu-id="1bd6a-621">Office.Extensibility.VBATelemetryDeclare</span></span> 

<span data-ttu-id="1bd6a-622">Збирає відомості про звертання до інтерфейсів API Win32 в рішеннях VBA.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-622">Collects information about invocation of Win32 API’s in VBA solutions.</span></span> <span data-ttu-id="1bd6a-623">Допомагає зрозуміти взаємодію між VBA та API й доповнити інформацією аналіз безпеки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-623">Used to understand interaction between VBA and usage and to supplement security investigations.</span></span>

<span data-ttu-id="1bd6a-624">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-624">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-625">**DeclareCount** – кількість оголошень</span><span class="sxs-lookup"><span data-stu-id="1bd6a-625">**DeclareCount** – number of declarations</span></span>

  - <span data-ttu-id="1bd6a-626">**HashDeclare** – геш-код імені DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-626">**HashDeclare** – hash of the DLL name</span></span>

  - <span data-ttu-id="1bd6a-627">**HashEntryPoint** – геш-код імені API</span><span class="sxs-lookup"><span data-stu-id="1bd6a-627">**HashEntryPoint** – hash of the API Name</span></span>

  - <span data-ttu-id="1bd6a-628">**HashProjectName** – геш-код імені проекту VBA</span><span class="sxs-lookup"><span data-stu-id="1bd6a-628">**HashProjectName** – hash of the VBA project name</span></span>

  - <span data-ttu-id="1bd6a-629">**IsPtrSafe** – чи сумісний оператор оголошення для іншої архітектури</span><span class="sxs-lookup"><span data-stu-id="1bd6a-629">**IsPtrSafe** – whether the declaration statement is compatible for different architecture</span></span>

  - <span data-ttu-id="1bd6a-630">**TagId** – унікальний тег</span><span class="sxs-lookup"><span data-stu-id="1bd6a-630">**TagId** – unique tag</span></span>

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a><span data-ttu-id="1bd6a-631">Office.Outlook.Desktop.Add-ins.Add-inLoaded</span><span class="sxs-lookup"><span data-stu-id="1bd6a-631">Office.Outlook.Desktop.Add-ins.Add-inLoaded</span></span>

<span data-ttu-id="1bd6a-632">Збирає відомості про успішне та невдале завантаження надбудови Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-632">Collects the success and failure of Outlook loading of an add-in.</span></span> <span data-ttu-id="1bd6a-633">Ці дані активно відстежуються для забезпечення належної роботи Outlook із надбудовами клієнтів. Вони використовуються для виявлення та дослідження проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-633">This data is actively monitored in order to ensure Outlook is correctly working with customer add-ins. This data is used to detect and investigate issues.</span></span>

<span data-ttu-id="1bd6a-634">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-634">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-635">**Стандартна робота HVA без користувацького навантаження**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-635">**Standard HVA activity with no custom payload**</span></span>

#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a><span data-ttu-id="1bd6a-636">Office.Programmability.Add-ins.InternalSetConnectEnterprise</span><span class="sxs-lookup"><span data-stu-id="1bd6a-636">Office.Programmability.Add-ins.InternalSetConnectEnterprise</span></span>

<span data-ttu-id="1bd6a-637">Подія виникає, коли надбудова COM завантажується на корпоративний пристрій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-637">Event generated when a COM Add-in is loaded on an Enterprise Device.</span></span> <span data-ttu-id="1bd6a-638">Аналітика для настільних комп’ютерів: \# завантажень використовується як нумератор для обчислення робочого стану (\# збоїв / \# завантажень), для розрахунків показників стану для пілотних і робочих кіл у корпоративних сценаріях.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-638">Desktop Analytics: \# of loads is used as denominator for calculation of health (\# crash / \# loads) for computation of health metrics for pilot and production rings in enterprise scenarios.</span></span> <span data-ttu-id="1bd6a-639">Для цього потрібно, щоб дані були точні та не вибіркові, оскільки кількість пристроїв менша (100–1000).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-639">This demands that the data is precise, not sampled since the number of devices is smaller (100-1K).</span></span>

<span data-ttu-id="1bd6a-640">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-640">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-641">**Add-inconnectFlag** – поведінка поточного завантаження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-641">**Add-inconnectFlag** – current load behavior</span></span>

  - <span data-ttu-id="1bd6a-642">**Add-inDescription** – опис надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-642">**Add-inDescription** – the add-in description</span></span>

  - <span data-ttu-id="1bd6a-643">**Add-inFileName** – ім’я файлу надбудови зі шляхом до нього</span><span class="sxs-lookup"><span data-stu-id="1bd6a-643">**Add-inFileName** – the add-in file name, excluding file path</span></span>

  - <span data-ttu-id="1bd6a-644">**Add-inFriendlyName** – зрозуміле ім’я надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-644">**Add-inFriendlyName** – the add-in friendly name</span></span>

  - <span data-ttu-id="1bd6a-645">**Add-inId** – ідентифікатор класу надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-645">**Add-inId** – the add-in Class Id</span></span>

  - <span data-ttu-id="1bd6a-646">**Add-inProgId** – ідентифікатор програми надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-646">**Add-inProgId** – the add-in Prog Id</span></span>

  - <span data-ttu-id="1bd6a-647">**Add-inProvider** – постачальник надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-647">**Add-inProvider** – the add-in provider</span></span>

  - <span data-ttu-id="1bd6a-648">**Add-inTimeDateStamp** – позначка часу надбудови з метаданих DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-648">**Add-inTimeDateStamp** – the add-in timestamp from the DLL metadata</span></span>

  - <span data-ttu-id="1bd6a-649">**Add-inVersion** – версія надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-649">**Add-inVersion** – the add-in version</span></span>

#### <a name="officevisiovisioaddonload"></a><span data-ttu-id="1bd6a-650">Office.Visio.Visio.AddonLoad</span><span class="sxs-lookup"><span data-stu-id="1bd6a-650">Office.Visio.Visio.AddonLoad</span></span>

<span data-ttu-id="1bd6a-651">Реєструє помилки, коли рішення не вдається завантажити.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-651">Captures errors when a solution fails to load.</span></span> <span data-ttu-id="1bd6a-652">Необхідна для налагодження помилок завантаження надбудов у Visio.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-652">Essential to debug addon load errors in Visio.</span></span>

<span data-ttu-id="1bd6a-653">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-653">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-654">**Data\_Load1Error:integer** – значення помилки під час завантаження надбудови Visio</span><span class="sxs-lookup"><span data-stu-id="1bd6a-654">**Data\_Load1Error:integer** - Error value during the load of Visio add-on</span></span>

#### <a name="officevisiovisioaddonusage"></a><span data-ttu-id="1bd6a-655">Office.Visio.Visio.AddonUsage</span><span class="sxs-lookup"><span data-stu-id="1bd6a-655">Office.Visio.Visio.AddonUsage</span></span>

<span data-ttu-id="1bd6a-656">Реєструє помилки функціональних можливостей рішень.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-656">Captures errors when there is an error in solution functionality.</span></span> <span data-ttu-id="1bd6a-657">Необхідна для налагодження помилок у надбудовах.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-657">Essential to debug addon errors in add-ons.</span></span>

<span data-ttu-id="1bd6a-658">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-658">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-659">**Data\_DocumentSessionLogID:string** – ідентифікатор сеансу документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-659">**Data\_DocumentSessionLogID:string** - Document session identifier</span></span>

  - <span data-ttu-id="1bd6a-660">**Data\_IsEnabled**:**bool** – має значення TRUE, якщо рішення активовано</span><span class="sxs-lookup"><span data-stu-id="1bd6a-660">**Data\_IsEnabled**:**bool** - true if solution is enabled</span></span>

  - <span data-ttu-id="1bd6a-661">**Data\_TemplateID:string** – GUID шаблону, в якому завантажено рішення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-661">**Data\_TemplateID:string** - GUID of template in which solution was loaded.</span></span> <span data-ttu-id="1bd6a-662">Для спеціальних рішень має значення 0.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-662">Logged as 0 for custom solution</span></span>

  - <span data-ttu-id="1bd6a-663">**Data\_AddOnID**:**string** – GUID для ідентифікації завантаженої надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-663">**Data\_AddOnID**:**string** - GUID to identify addon loaded</span></span>

  - <span data-ttu-id="1bd6a-664">**Data\_Error**:**integer** – ідентифікатор помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-664">**Data\_Error**:**integer** - Error Id</span></span>

### <a name="security-subtype"></a><span data-ttu-id="1bd6a-665">*Підтип безпеки*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-665">*Security subtype*</span></span>

<span data-ttu-id="1bd6a-666">Помилки документів, функцій та надбудов, які можуть зашкодити безпеці, зокрема вплинути на стан готовності до оновлення продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-666">Document, feature, and add-in error conditions that may compromise security, including product update readiness.</span></span>

#### <a name="officesecurityactivationfilterclsidactivated"></a><span data-ttu-id="1bd6a-667">Office.Security.ActivationFilter.CLSIDActivated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-667">Office.Security.ActivationFilter.CLSIDActivated</span></span>

<span data-ttu-id="1bd6a-668">Відстежує, коли в Office активується певний ідентифікатор класу (Flash, Silverlight тощо).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-668">Tracks when a specific Class Identifier (Flash, Silverlight etc.) is activated in Office.</span></span> <span data-ttu-id="1bd6a-669">Використовується для відстеження впливу блокування елементів керування Flash, Silverlight і Shockwave на кінцевих користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-669">Used to track impact of blocking Flash, Silverlight and Shockwave controls on end users.</span></span>

<span data-ttu-id="1bd6a-670">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-670">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-671">**ActivationType** – тип активації елемента керування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-671">**ActivationType** - Type of activation for the control</span></span>

  - <span data-ttu-id="1bd6a-672">**Blocked** – чи було елемент керування заблоковано в Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-672">**Blocked** - was the control blocked by office</span></span>

  - <span data-ttu-id="1bd6a-673">**CLSID** – ідентифікатор класу елемента керування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-673">**CLSID** - class identifier of the control</span></span>

  - <span data-ttu-id="1bd6a-674">**Count** – скільки разів було активовано елемент керування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-674">**Count** - how many times was the control activated</span></span>

#### <a name="officesecurityactivationfilterfailedtoregister"></a><span data-ttu-id="1bd6a-675">Office.Security.ActivationFilter.FailedToRegister</span><span class="sxs-lookup"><span data-stu-id="1bd6a-675">Office.Security.ActivationFilter.FailedToRegister</span></span>

<span data-ttu-id="1bd6a-676">Відстежує стан помилки під час застосування заходів зниження ризику безпеки, які блокують активацію небезпечних елементів керування в Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-676">Tracks an error condition in security mitigation that blocks activation of dangerous controls in Office.</span></span>

<span data-ttu-id="1bd6a-677">Використовується для діагностування станів помилки під час застосування заходів зниження ризику безпеки, які можуть вплинути на безпеку кінцевих користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-677">Used to diagnose error conditions in security mitigation that could impact security of end users.</span></span>

<span data-ttu-id="1bd6a-678">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-678">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-679">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-679">None</span></span>

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a><span data-ttu-id="1bd6a-680">Office.Security.ComSecurity.FileExtensionListFromService</span><span class="sxs-lookup"><span data-stu-id="1bd6a-680">Office.Security.ComSecurity.FileExtensionListFromService</span></span>

<span data-ttu-id="1bd6a-681">Відстежує, чи було прочитано розширення блокування пакувальника зі служба конфігурації або було використано стандартний список клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-681">Tracks if packager block extensions were read from config service or we used client default list.</span></span> <span data-ttu-id="1bd6a-682">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-682">Used to ensure effectiveness of security mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-683">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-683">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-684">**RetrievedFromServiceStatus** – чи вдалося отримати список розширень файлів, які блокуються, і якщо ні, то яка причина помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-684">**RetrievedFromServiceStatus** - were we able to retrieve the list of file extensions to block if not then what was the error reason</span></span>

#### <a name="officesecuritycomsecurityload"></a><span data-ttu-id="1bd6a-685">Office.Security.ComSecurity.Load</span><span class="sxs-lookup"><span data-stu-id="1bd6a-685">Office.Security.ComSecurity.Load</span></span>

<span data-ttu-id="1bd6a-686">Відстежує, коли в документі завантажується об'єкт OLE.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-686">Tracks when an OLE object is loaded in a document.</span></span> <span data-ttu-id="1bd6a-687">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-687">Used to ensure effectiveness of security mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-688">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-688">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-689">**Clsid** – ідентифікатор класу елемента керування OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-689">**Clsid** - class identifier of the OLE control</span></span>

  - <span data-ttu-id="1bd6a-690">**Count** – скільки разів було завантажено елемент керування OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-690">**Count** - how many times the OLE control was loaded</span></span>

  - <span data-ttu-id="1bd6a-691">**DocUrlHash** – геш-код, який унікально представляє документ.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-691">**DocUrlHash** - a hash representing the document uniquely.</span></span> <span data-ttu-id="1bd6a-692">(Майте на увазі, що отримати з геш-кода якісь конкретні відомості про документ неможливо.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-692">(Note – no way to find out the actual details of the document from this.</span></span> <span data-ttu-id="1bd6a-693">Це лише унікальний ідентифікатор документа.)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-693">It is just a unique representation of the document.)</span></span>

  - <span data-ttu-id="1bd6a-694">**IsCategorized** – чи отримав елемент керування OLE категорію для завантаження в Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-694">**IsCategorized** – was the OLE control categorized to load in office</span></span>

  - <span data-ttu-id="1bd6a-695">**IsInsertable** – чи можна вставляти елемент керування OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-695">**IsInsertable** – is the OLE control insertable or not</span></span>

#### <a name="officesecuritycomsecurityobjdetected"></a><span data-ttu-id="1bd6a-696">Office.Security.ComSecurity.ObjDetected</span><span class="sxs-lookup"><span data-stu-id="1bd6a-696">Office.Security.ComSecurity.ObjDetected</span></span>

<span data-ttu-id="1bd6a-697">Відстежує, коли в документі виявляється об'єкт OLE.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-697">Tracks when an OLE object is detected in a document.</span></span> <span data-ttu-id="1bd6a-698">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-698">Used to ensure effectiveness of security .mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-699">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-699">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-700">**Clsid** – ідентифікатор класу елемента керування OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-700">**Clsid** - class identifier of the OLE control</span></span>

  - <span data-ttu-id="1bd6a-701">**Count** – скільки разів було виявлено цей об’єкт OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-701">**Count** - how many times this OLE object was detected</span></span>

  - <span data-ttu-id="1bd6a-702">**DocUrlHash** – геш-код, який унікально представляє документ.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-702">**DocUrlHash** - a hash representing the document uniquely.</span></span> <span data-ttu-id="1bd6a-703">(Майте на увазі, що отримати з геш-кода якісь конкретні відомості про документ неможливо.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-703">(Note – no way to find out the actual details of the document from this.</span></span> <span data-ttu-id="1bd6a-704">Це лише унікальний ідентифікатор документа.)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-704">It is just a unique representation of the document.)</span></span>

  - <span data-ttu-id="1bd6a-705">**IsCategorized** – чи має елемент керування OLE категорію для завантаження в Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-705">**IsCategorized** - is the OLE control categorized to load in office</span></span>

  - <span data-ttu-id="1bd6a-706">**IsInsertable** – чи можна вставляти елемент керування OLE</span><span class="sxs-lookup"><span data-stu-id="1bd6a-706">**IsInsertable** - is the OLE control insertable or not</span></span>

#### <a name="officesecuritycomsecuritypackageractivation"></a><span data-ttu-id="1bd6a-707">Office.Security.ComSecurity.PackagerActivation</span><span class="sxs-lookup"><span data-stu-id="1bd6a-707">Office.Security.ComSecurity.PackagerActivation</span></span>

<span data-ttu-id="1bd6a-708">Відстежує результат застосування заходів зниження ризику безпеки, які блокують небезпечні розширення, вбудовані в документах Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-708">Tracks the outcome of security mitigation that blocks dangerous extensions embedded in Office documents.</span></span> <span data-ttu-id="1bd6a-709">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-709">Used to ensure effectiveness of security mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-710">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-710">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-711">**FromInternet** – чи отримано документ з Інтернету</span><span class="sxs-lookup"><span data-stu-id="1bd6a-711">**FromInternet** - was the document from internet</span></span>

  - <span data-ttu-id="1bd6a-712">**PackagerSetting** – поточна настройка пакувальника</span><span class="sxs-lookup"><span data-stu-id="1bd6a-712">**PackagerSetting** - what was the current packager setting</span></span>

  - <span data-ttu-id="1bd6a-713">**TrustedDocument** – чи був документ надійним</span><span class="sxs-lookup"><span data-stu-id="1bd6a-713">**TrustedDocument** - was the document a trusted document</span></span>

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a><span data-ttu-id="1bd6a-714">Office.Security.ComSecurity.PackagerActivationErrors</span><span class="sxs-lookup"><span data-stu-id="1bd6a-714">Office.Security.ComSecurity.PackagerActivationErrors</span></span>

<span data-ttu-id="1bd6a-715">Відстежує стани помилки в заходах зниження ризику безпеки, які блокують небезпечні розширення, вбудовані в документах Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-715">Tracks error conditions in security mitigation that blocks dangerous extensions embedded in Office documents.</span></span> <span data-ttu-id="1bd6a-716">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-716">Used to ensure effectiveness of security mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-717">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-717">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-718">**Error** – код помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-718">**Error** - error code</span></span>

  - <span data-ttu-id="1bd6a-719">**Extension** – яке було розширення файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-719">**Extension** - what was the file extension</span></span>

  - <span data-ttu-id="1bd6a-720">**FromInternet** – чи отримано документ з Інтернету</span><span class="sxs-lookup"><span data-stu-id="1bd6a-720">**FromInternet** - was the document from internet</span></span>

  - <span data-ttu-id="1bd6a-721">**LinkedDocument** – чи це був зв’язаний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-721">**LinkedDocument** - was it a linked document or not</span></span>

  - <span data-ttu-id="1bd6a-722">**PackagerSetting** – поточна настройка пакувальника</span><span class="sxs-lookup"><span data-stu-id="1bd6a-722">**PackagerSetting** - what was the current packager setting</span></span>

  - <span data-ttu-id="1bd6a-723">**TrustedDocument** – чи був документ надійним</span><span class="sxs-lookup"><span data-stu-id="1bd6a-723">**TrustedDocument** - was the document trusted</span></span>


#### <a name="officesecuritymacrointernetvbablockenabled"></a><span data-ttu-id="1bd6a-724">Office.Security.Macro.InternetVBABlockEnabled</span><span class="sxs-lookup"><span data-stu-id="1bd6a-724">Office.Security.Macro.InternetVBABlockEnabled</span></span>

<span data-ttu-id="1bd6a-725">Відстежує, чи ввімкнуто в клієнті настройку блокування макросів з Інтернету.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-725">Tracks whether the Block Macro from Internet setting is enabled in a client.</span></span> <span data-ttu-id="1bd6a-726">Оцінює використання заходів зниження ризику безпеки для захисту від зловмисних макросів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-726">Assess use of security mitigation to protect against malicious macros.</span></span>

<span data-ttu-id="1bd6a-727">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-727">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-728">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-728">None</span></span>

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a><span data-ttu-id="1bd6a-729">Office.Security.Macro.PolicyDigSigTrustedPublishers</span><span class="sxs-lookup"><span data-stu-id="1bd6a-729">Office.Security.Macro.PolicyDigSigTrustedPublishers</span></span>

<span data-ttu-id="1bd6a-730">Відстежує, чи підтверджено походження макросу від надійного видавця.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-730">Tracks if the macro was verified to be from a trusted publisher.</span></span> <span data-ttu-id="1bd6a-731">Використовується, щоб забезпечити ефективність заходів зниження ризику безпеки, які захищають кінцевих користувачів Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-731">Used to ensure effectiveness of security mitigation that protects end users of Office.</span></span>

<span data-ttu-id="1bd6a-732">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-732">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-733">**Policy** – чи політика встановлена, не встановлена або недоступна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-733">**Policy** - is the policy set or not set or not available</span></span>

#### <a name="officesecuritymacroprompted"></a><span data-ttu-id="1bd6a-734">Office.Security.Macro.Prompted</span><span class="sxs-lookup"><span data-stu-id="1bd6a-734">Office.Security.Macro.Prompted</span></span>

<span data-ttu-id="1bd6a-735">Відстежує, коли користувачеві пропонується ввімкнути макроси VBA.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-735">Tracks when a user is prompted to enable VBA Macros.</span></span> <span data-ttu-id="1bd6a-736">Використовується, щоб оцінити поширення макросів VBA та сприяти подальшим заходам зниження ризику безпеки, які обмежують виконання макросів у відповідь на інциденти безпеки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-736">Used to assess prevalence of VBA Macros and drive future security mitigations that restrict macro execution in response to security incidents.</span></span>

<span data-ttu-id="1bd6a-737">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-737">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-738">**PromptType** – який тип запрошення відображається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-738">**PromptType** - what type of prompt was shown</span></span>

  - <span data-ttu-id="1bd6a-739">**VBAMacroAntiVirusHash** – геш-код антивірусу макросу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-739">**VBAMacroAntiVirusHash** - antivirus hash of the macro</span></span>

  - <span data-ttu-id="1bd6a-740">**VBAMacroAntiVirusHRESULT** – результат антивірусного оцінювання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-740">**VBAMacroAntiVirusHRESULT** - result of the antivirus assessment</span></span>

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a><span data-ttu-id="1bd6a-741">Office.Security.Macro.VBASecureRuntimeSessionEnableState</span><span class="sxs-lookup"><span data-stu-id="1bd6a-741">Office.Security.Macro.VBASecureRuntimeSessionEnableState</span></span>

<span data-ttu-id="1bd6a-742">Відстежує кожної перевірки в середовищі виконання AMSI, яка виконується під час виконання макросу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-742">Tracks each AMSI runtime verification performed when a macro executes.</span></span> <span data-ttu-id="1bd6a-743">Відстежує ефективність перевірки виконання макросу в середовищі виконання AMSI та виявлення помилок, які можуть впливати на безпеку кінцевих користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-743">Tracks effectiveness of the AMSI runtime verification of Macro execution and identify errors that could impact security of end users.</span></span>

<span data-ttu-id="1bd6a-744">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-744">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-745">**IsRegistry** – чи робив адміністратор якісь заміни в реєстрі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-745">**IsRegistry** - did admin set some override in registry</span></span>

  - <span data-ttu-id="1bd6a-746">**State** – стан для безпечного середовища виконання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-746">**State** - what is the state to for secure runtime</span></span>

#### <a name="officesecuritymacroxl4prompted"></a><span data-ttu-id="1bd6a-747">Office.Security.Macro.XL4Prompted</span><span class="sxs-lookup"><span data-stu-id="1bd6a-747">Office.Security.Macro.XL4Prompted</span></span>

<span data-ttu-id="1bd6a-748">Відстежує, коли користувачеві пропонується ввімкнути макроси XL4.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-748">Tracks when a user is prompted to enable XL4 Macros.</span></span> <span data-ttu-id="1bd6a-749">Використовується, щоб оцінити поширення макросів XL4 в Excel і сприяти подальшим заходам зниження ризику безпеки, які за замовчуванням блокують XL4 у відповідь на інциденти, пов'язані зі зловживанням макросами XL4.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-749">Used to assess prevalence of XL4 Macros in Excel to drive future security mitigations that block XL4 by default in response to security incidents that involve abusing XL4 macros.</span></span>

<span data-ttu-id="1bd6a-750">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-750">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-751">**PromptType** – який тип запрошення відображається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-751">**PromptType** - what type of prompt was shown</span></span>


#### <a name="officesecurityocxufiprompt"></a><span data-ttu-id="1bd6a-752">Office.Security.OCX.UFIPrompt</span><span class="sxs-lookup"><span data-stu-id="1bd6a-752">Office.Security.OCX.UFIPrompt</span></span>

<span data-ttu-id="1bd6a-753">Відстежує, коли користувачеві відображається повідомлення системи безпеки під час завантаження елемента керування ActiveX, позначеного як небезпечний для ініціалізації.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-753">Tracks when a security prompt is shown to the user when loading an ActiveX control that is marked Unsafe for Initialization.</span></span> <span data-ttu-id="1bd6a-754">Використовується, щоб відстежувати поширення елементів керування UFI ActiveX у документах Office і сприяти подальшим заходам зниження ризику безпеки (наприклад, заборони елементів керування) у відповідь на інциденти безпеки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-754">Used to track prevalence of UFI ActiveX controls in Office documents to drive mitigations (e.g. killbitting controls) in response to security incidents.</span></span>

<span data-ttu-id="1bd6a-755">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-755">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-756">**IsFromInternet** – чи відкрито документ з Інтернету</span><span class="sxs-lookup"><span data-stu-id="1bd6a-756">**IsFromInternet** - is the document opened from internet</span></span>

  - <span data-ttu-id="1bd6a-757">**IsSecureReaderMode** – чи відкрито документ у безпечному засобі читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-757">**IsSecureReaderMode** - is the document opened in secure reader</span></span>

  - <span data-ttu-id="1bd6a-758">**OcxTrustCenterSettings** – поточна настройка ActiveX</span><span class="sxs-lookup"><span data-stu-id="1bd6a-758">**OcxTrustCenterSettings** - what is the current ActiveX setting</span></span>


#### <a name="officesecuritysecurereaderhostopeninosr"></a><span data-ttu-id="1bd6a-759">Office.Security.SecureReaderHost.OpenInOSR</span><span class="sxs-lookup"><span data-stu-id="1bd6a-759">Office.Security.SecureReaderHost.OpenInOSR</span></span>

<span data-ttu-id="1bd6a-760">Відстежує завершення відкриття в безпечному поданні.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-760">Tracks completion of an open in Protected View.</span></span> <span data-ttu-id="1bd6a-761">Використовується для діагностування умов, які призводять до помилок під час відкриття файлів у безпечному поданні, що впливає на безпеку та продуктивність роботи клієнтів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-761">Used to diagnose conditions that lead to failures when opening files in Protected View impacting security and productivity of customers.</span></span>

<span data-ttu-id="1bd6a-762">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-762">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-763">Немає</span><span class="sxs-lookup"><span data-stu-id="1bd6a-763">None</span></span>

## <a name="product-and-service-usage-data-events"></a><span data-ttu-id="1bd6a-764">Події даних про використання продуктів і служб</span><span class="sxs-lookup"><span data-stu-id="1bd6a-764">Product and service usage data events</span></span>

<span data-ttu-id="1bd6a-765">Нижче наведено підтипи даних у цій категорії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-765">The following are the data subtypes in this category:</span></span>

- [<span data-ttu-id="1bd6a-766">Успіх функцій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-766">Application feature success</span></span>](#application-feature-success-subtype)
- [<span data-ttu-id="1bd6a-767">Стан та завантаження програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-767">Application status and boot</span></span>](#application-status-and-boot-subtype)
- [<span data-ttu-id="1bd6a-768">Конфігурація спеціальних можливостей Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-768">Office accessibility configuration</span></span>](#office-accessibility-configuration-subtype)
- <span data-ttu-id="1bd6a-769">[Конфіденційність](#privacy-subtype)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-769">[Privacy Options](#privacy-subtype):</span></span>


### <a name="application-feature-success-subtype"></a><span data-ttu-id="1bd6a-770">*Підтип успіху функцій програми*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-770">*Application feature success subtype*</span></span>

<span data-ttu-id="1bd6a-771">Успішність виконання функцій програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-771">Success of application functionality.</span></span> <span data-ttu-id="1bd6a-772">Обмежується операціями відкривання та закривання програм і документів, редагування файлів і спільного доступу до файлів (співпраці).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-772">Limited to opening and closing of the application and documents, file editing, and file sharing (collaboration).</span></span>

#### <a name="officeappcompatappcompatagentscanandupload"></a><span data-ttu-id="1bd6a-773">Office.AppCompat.AppCompat.AgentScanAndUpload</span><span class="sxs-lookup"><span data-stu-id="1bd6a-773">Office.AppCompat.AppCompat.AgentScanAndUpload</span></span>

<span data-ttu-id="1bd6a-774">Збираються, лише якщо користувач активував приладну дошку телеметрії Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-774">Only collected when end user has enabled Office Telemetry Dashboard.</span></span><span data-ttu-id="1bd6a-775"> Збираються відомості про те, коли виконується агент телеметрії Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-775"> It collects information on when the Office Telemetry Agent is executed.</span></span><span data-ttu-id="1bd6a-776"> Діє, лише коли ввімкнуто приладну дошку телеметрії Office, і використовується для визначення справності агента телеметрії Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-776">  This is only collected when Office Telemetry Dashboard is enabled and is used to determine the health of Office Telemetry agent.</span></span>

<span data-ttu-id="1bd6a-777">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-777">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-778">**Data.AgentExit** – позначка часу успішного завершення роботи агента телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-778">**Data.AgentExit** - Timestamp of when the Telemetry agent exits successfully</span></span>

  - <span data-ttu-id="1bd6a-779">**Data.AgentScan** – позначка часу успішного завершення сканування агентом телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-779">**Data.AgentScan** - Timestamp of when the Telemetry agent completed a scan successfully</span></span>

  - <span data-ttu-id="1bd6a-780">**Data.AgentUpload** – позначка часу успішного завершення передавання агентом телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-780">**Data.AgentUpload** - Timestamp of when the Telemetry agent completes the upload successfully</span></span>

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a><span data-ttu-id="1bd6a-781">Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog</span><span class="sxs-lookup"><span data-stu-id="1bd6a-781">Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog</span></span>

<span data-ttu-id="1bd6a-782">Збирається, лише коли приладну дошку телеметрії Office активовано кінцевим користувачем (зазвичай адміністратором).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-782">Only collected when Office Telemetry Dashboard has been enabled by end user (most likely an admin).</span></span> <span data-ttu-id="1bd6a-783">Реєструються несправності надбудов Office і документів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-783">It collects the occurrence of Office Add-ins and documents crashes.</span></span><span data-ttu-id="1bd6a-784"> Діє, лише коли користувач увімкнув приладну дошку телеметрії Office, і використовується, щоб визначити, чи стають частішими несправності надбудов або документів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-784"> This is only collected when user has enabled Office Telemetry Dashboard and is used to determine if there is an increased occurrence of add-in or document crashes.</span></span>

<span data-ttu-id="1bd6a-785">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-785">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-786">**Data.CollectionTime** – позначка часу реєстрації події несправності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-786">**Data.CollectionTime** - Timestamp of when a crash event was logged</span></span>

#### <a name="officeconnectdeviceactivitystart"></a><span data-ttu-id="1bd6a-787">Office.ConnectDevice.Activity.Start</span><span class="sxs-lookup"><span data-stu-id="1bd6a-787">Office.ConnectDevice.Activity.Start</span></span>

<span data-ttu-id="1bd6a-788">Повідомляє, чи успішне було підключення до пристрою або програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-788">Allows us to know if a connection to a device or application was successful.</span></span>  <span data-ttu-id="1bd6a-789">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-789">Used for feature health and monitoring.</span></span> <span data-ttu-id="1bd6a-790">Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-790">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-791">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-791">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-792">**Datasource_Type** – відомості про пристрій або службу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-792">**Datasource_Type** - Serial device, or App Service information</span></span>

- <span data-ttu-id="1bd6a-793">**DataSource_Name** – ім’я підключеного джерела даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-793">**DataSource_Name** - Name of connected data source</span></span>

- <span data-ttu-id="1bd6a-794">**Activity_Name** – ім’я дії “ConnectDevice”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-794">**Activity_Name** = Name of the activity “ConnectDevice”</span></span>

- <span data-ttu-id="1bd6a-795">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-795">**Activity_CV** = ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-796">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-796">**Activity_StartStopType** = Start</span></span>

- <span data-ttu-id="1bd6a-797">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-797">**Activity_DateTimeTicks** = Data Time for the activity</span></span>
 
#### <a name="officeconnectdeviceactivitystop"></a><span data-ttu-id="1bd6a-798">Office.ConnectDevice.Activity.Stop</span><span class="sxs-lookup"><span data-stu-id="1bd6a-798">Office.ConnectDevice.Activity.Stop</span></span>

<span data-ttu-id="1bd6a-799">Повідомляє, чи успішне було підключення до пристрою або програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-799">Allows us to know if a connection to a device or application was successful.</span></span> <span data-ttu-id="1bd6a-800">Використовується для дослідження справності та моніторингу функцій. Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-800">Used for feature health and monitoring This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-801">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-801">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-802">**Datasource_Type** – відомості про пристрій або службу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-802">**Datasource_Type** - Serial device, or App Service information</span></span>

- <span data-ttu-id="1bd6a-803">**DataSource_Name** – ім’я підключеного джерела даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-803">**DataSource_Name** - Name of connected data source</span></span>

- <span data-ttu-id="1bd6a-804">**Activity_Name** – ім’я дії “ConnectDevice”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-804">**Activity_Name** - Name of the activity “ConnectDevice”</span></span>

- <span data-ttu-id="1bd6a-805">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-805">**Activity_CV** - ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-806">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-806">**Activity_StartStopType** - Stop</span></span>

- <span data-ttu-id="1bd6a-807">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-807">**Activity_DateTimeTicks** - Data Time for the activity</span></span>

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a><span data-ttu-id="1bd6a-808">Office.Extensibility.Catalog.ExchangeProcessEntitlement</span><span class="sxs-lookup"><span data-stu-id="1bd6a-808">Office.Extensibility.Catalog.ExchangeProcessEntitlement</span></span>

<span data-ttu-id="1bd6a-809">Дані щодо обробки окремого права на використання надбудови та адміністратор клієнта Office 365, який призначив надбудову.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-809">Data regarding the processing of an individual entitlement of and Office 365 tenant admin assigned add-in.</span></span>

<span data-ttu-id="1bd6a-810">Використовується для діаграм (на запит керівництва групи) успішності клієнтів і аналізу проблем клієнтів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-810">Used in charting (requested by team management) of customer success and analysis of customer problems.</span></span>

<span data-ttu-id="1bd6a-811">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-811">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-812">**AppVersion** – версія хост-програми надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-812">**AppVersion** – the version of the add-in host application</span></span>

  - <span data-ttu-id="1bd6a-813">**SolutionId** – GUID, який представляє унікальну надбудову</span><span class="sxs-lookup"><span data-stu-id="1bd6a-813">**SolutionId** – a GUID representing a unique add-in</span></span>

  - <span data-ttu-id="1bd6a-814">**TelemetryId** – GUID, який представляє унікального користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-814">**TelemetryId** – a GUID representing a unique user</span></span>

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a><span data-ttu-id="1bd6a-815">Office.FileIO.CSI.CCachedFileCsiLoadFileBasic</span><span class="sxs-lookup"><span data-stu-id="1bd6a-815">Office.FileIO.CSI.CCachedFileCsiLoadFileBasic</span></span>

<span data-ttu-id="1bd6a-816">Повідомляє, чи успішно було відкрито файл із рівня FIO.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-816">Allows us to know if a file successfully opened from the FIO Layer.</span></span> <span data-ttu-id="1bd6a-817">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-817">Used for feature health and monitoring.</span></span>

<span data-ttu-id="1bd6a-818">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-818">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-819">**Activity.Group** – тег, який дає змогу групувати події моніторингу для контролю загального успіху</span><span class="sxs-lookup"><span data-stu-id="1bd6a-819">**Activity.Group -** tag that allows a set of monitoring events to be grouped to manage overall success</span></span>

  - <span data-ttu-id="1bd6a-820">**Activity.IsHVA** – позначка, яка показує, що подія критично важлива для успіху користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-820">**Activity.IsHVA -** flag to indicate that event is critical to user success</span></span>

  - <span data-ttu-id="1bd6a-821">**Data.AsyncOpen** – позначка, яка показує, що у вхідному потоці був вміст, який з’явився після відкриття основного тексту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-821">**Data.AsyncOpen -** flag to indicate the open had content that arrived after the main body was opened</span></span>

  - <span data-ttu-id="1bd6a-822">**Data.CacheFileId** – підключається до телеметрії кеша документів Office і забезпечує аналіз впливу проблем із кешем на користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-822">**Data.CacheFileId -** connects to Office Document Cache telemetry to enable impact analysis of cache issues on the user experience</span></span>

  - <span data-ttu-id="1bd6a-823">**Data.CoauthStatus** – повідомляє статус співпраці над відкритим документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-823">**Data.CoauthStatus -** reports collaborative status of the document on Open</span></span>

  - <span data-ttu-id="1bd6a-824">**Data.CountOfMultiRoundTripsDownload** – кількість звернень до сервера, які було використано для виправлення проблем із продуктивністю та мережею</span><span class="sxs-lookup"><span data-stu-id="1bd6a-824">**Data.CountOfMultiRoundTripsDownload -** Count of round trips to the server used to troubleshoot performance and network issues</span></span>

  - <span data-ttu-id="1bd6a-825">**Data.CountOfMultiRoundTripsUpload** – кількість звернень до сервера, які було використано для виправлення проблем із продуктивністю та мережею</span><span class="sxs-lookup"><span data-stu-id="1bd6a-825">**Data.CountOfMultiRoundTripsUpload -** Count of round trips to the server used to troubleshoot performance and network issues</span></span>

  - <span data-ttu-id="1bd6a-826">**Data.DialogId** – діє, якщо під час відкриття відображалося діалогове вікно інтерфейсу користувача, показуючи, що користувач отримав попереджувальне повідомлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-826">**Data.DialogId -** Set if a UI dialog was displayed during Open, indicating a that a warning message was displayed to the user</span></span>

  - <span data-ttu-id="1bd6a-827">**Data.DidFallbackToDAV** – показує, чи було відкрито документ із використанням старого протоколу передачі файлів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-827">**Data.DidFallbackToDAV -** Set if the document was opened using an older file transfer protocol</span></span>

  - <span data-ttu-id="1bd6a-828">**Data.Doc.AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-828">**Data.Doc.AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-829">**Data.Doc.AssistedReadingReasons** – чи застосовано до документа електронний захист даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-829">**Data.Doc.AssistedReadingReasons -** Set if the document has electronic data protection in place</span></span>

  - <span data-ttu-id="1bd6a-830">**Data.Doc.ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-830">**Data.Doc.ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-831">**Data.Doc.EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-831">**Data.Doc.EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-832">**Data.Doc.Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-832">**Data.Doc.Ext -** Document extension (docx/xlsb/pptx, etc.)</span></span>

  - <span data-ttu-id="1bd6a-833">**Data.Doc.Extension** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-833">**Data.Doc.Extension -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-834">**Data.Doc.FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-834">**Data.Doc.FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-835">**Data.Doc.Fqdn** – ім’я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-835">**Data.Doc.Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-836">**Data.Doc.FqdnHash** – односторонній геш-код особистого імені домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-836">**Data.Doc.FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-837">**Data.Doc.IdentityTelemetryId** – односторонній геш-код ідентичності користувача, яку було використано для відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-837">**Data.Doc.IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-838">**Data.Doc.IdentityUniqueId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-838">**Data.Doc.IdentityUniqueId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-839">**Data.Doc.InitializationScenario** – реєструє, яким чином було відкрито документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-839">**Data.Doc.InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-840">**Data.Doc.IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-840">**Data.Doc.IOFlags -** Reports on the cached flags used to set request options</span></span>

  - <span data-ttu-id="1bd6a-841">**Data.Doc.IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-841">**Data.Doc.IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-842">**Data.Doc.IsCloudCollabEnabled** – позначка, яка вказує, що служба підтримує хмарну співпрацю</span><span class="sxs-lookup"><span data-stu-id="1bd6a-842">**Data.Doc.IsCloudCollabEnabled -** Flag indicating that the service supports Cloud Collaboration</span></span>

  - <span data-ttu-id="1bd6a-843">**Data.Doc.IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-843">**Data.Doc.IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-844">**Data.Doc.IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-844">**Data.Doc.IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-845">**Data.Doc.IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-845">**Data.Doc.IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-846">**Data.Doc.IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-846">**Data.Doc.IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-847">**Data.Doc.Location** – указує службу, яка надала документ (OneDrive, файловий сервер, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-847">**Data.Doc.Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-848">**Data.Doc.LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-848">**Data.Doc.LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-849">**Data.Doc.NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-849">**Data.Doc.NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-850">**Data.Doc.PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-850">**Data.Doc.PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-851">**Data.Doc.ReadOnlyReasons** –причини, з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-851">**Data.Doc.ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-852">**Data.Doc.ResourceIdHash** – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-852">**Data.Doc.ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-853">**Data.Doc.ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-853">**Data.Doc.ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-854">**Data.Doc.ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-854">**Data.Doc.ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-855">**Data.Doc.ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-855">**Data.Doc.ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-856">**Data.Doc.ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-856">**Data.Doc.ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-857">**Data.Doc.SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-857">**Data.Doc.SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-858">**Data.Doc.SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-858">**Data.Doc.SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-859">**Data.Doc.SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-859">**Data.Doc.SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-860">**Data.Doc.SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-860">**Data.Doc.SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-861">**Data.Doc.StorageProviderId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-861">**Data.Doc.StorageProviderId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-862">**Data.Doc.StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-862">**Data.Doc.StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-863">**Data.Doc.SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-863">**Data.Doc.SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-864">**Data.Doc.UrlHash** – односторонній геш-код для створення наївного ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-864">**Data.Doc.UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-865">**Data.Doc.UsedWrsDataOnOpen** – діагностичний індикатор для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-865">**Data.Doc.UsedWrsDataOnOpen -** Diagnostic indicator for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-866">**Data.Doc.WopiServiceId** – містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-866">**Data.Doc.WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-867">**Data.DocumentLoadEndpoint** – застарілий/зайвий дублікат полів (Data.Doc.Location і Data.Doc.IsSyncbacked)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-867">**Data.DocumentLoadEndpoint -** obsolete/redundant duplicate of (Data.Doc.Location and Data.Doc.IsSyncbacked)</span></span>

  - <span data-ttu-id="1bd6a-868">**Data.DocumentSizeInBytes** – застаріле/зайве поле, яке замінює Data.Doc. SizeInBytes</span><span class="sxs-lookup"><span data-stu-id="1bd6a-868">**Data.DocumentSizeInBytes -** Obsolete/redundant supplanted by Data.Doc. SizeInBytes</span></span>

  - <span data-ttu-id="1bd6a-869">**Data.DocumentSizeOnDisk** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-869">**Data.DocumentSizeOnDisk -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-870">**Data.DoesBaseHaveContentOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-870">**Data.DoesBaseHaveContentOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-871">**Data.DoesWorkingBranchHaveExcludedDataOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-871">**Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-872">**Data.DownloadFragmentSize** – розмір даних, переданих у підзапиті для діагностування проблем мережі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-872">**Data.DownloadFragmentSize -** Size of data sent in a sub request for diagnosing network issues</span></span>

  - <span data-ttu-id="1bd6a-873">**Data.DsmcStartedTooEarly** – помилка початку сеансу спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-873">**Data.DsmcStartedTooEarly -** Indicates an error starting a collaborative edit session</span></span>

  - <span data-ttu-id="1bd6a-874">**Data.EditorsCount** – кількість інших співавторів, які редагують документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-874">**Data.EditorsCount -** A count of other collaborators editing the document</span></span>

  - <span data-ttu-id="1bd6a-875">**Data.ExcludedDataThresholdInBytes** – розмір файлу, потрібний для застосування асинхронного відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-875">**Data.ExcludedDataThresholdInBytes -** File size required for Asynch open to be used</span></span>

  - <span data-ttu-id="1bd6a-876">**Data.FileIOResult.Code** – кеш останнього коду, повернутого операцією відкриття з рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-876">**Data.FileIOResult.Code -** Cache of last Open return code from protocol layer</span></span>

  - <span data-ttu-id="1bd6a-877">**Data.FileIOResult.Success** – кеш останнього індикатора успішного відкриття з рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-877">**Data.FileIOResult.Success -** Cache of last Open success indicator from protocol layer</span></span>

  - <span data-ttu-id="1bd6a-878">**Data.FileIOResult.Tag** – кеш останнього тега помилки відкриття з рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-878">**Data.FileIOResult.Tag -** Cache of last Open error tag from protocol layer</span></span>

  - <span data-ttu-id="1bd6a-879">**Data.FileIOResult.Type** – кеш останнього типу помилки відкриття з рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-879">**Data.FileIOResult.Type -** Cache of last Open error type from protocol layer</span></span>

  - <span data-ttu-id="1bd6a-880">**Data.FqdnHash** – застаріле, замінено на Data\_Doc\_FqdnHash</span><span class="sxs-lookup"><span data-stu-id="1bd6a-880">**Data.FqdnHash -** Obsolete, replaced by Data\_Doc\_FqdnHash</span></span>

  - <span data-ttu-id="1bd6a-881">**Data.FullIError** – кеш усіх кодів помилок відкриття з рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-881">**Data.FullIError -** Cache of all Open error codes from the protocol layer</span></span>

  - <span data-ttu-id="1bd6a-882">**Data.FullyQualifiedDomainName** – застаріле, замінено на Data\_Doc\_Fqdn</span><span class="sxs-lookup"><span data-stu-id="1bd6a-882">**Data.FullyQualifiedDomainName -** Obsolete, replaced by Data\_Doc\_Fqdn</span></span>

  - <span data-ttu-id="1bd6a-883">**Data.Input.FileOpenState** – стан, запитаний програмою (Read/ReadWrite тощо) **-**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-883">**Data.Input.FileOpenState -** State requested by app (Read/ReadWrite etc.) **-**</span></span>

  - <span data-ttu-id="1bd6a-884">**Data.Input.OpenAsync** – програмою запитано асинхронне відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-884">**Data.Input.OpenAsync -** Async open requested by app</span></span>

  - <span data-ttu-id="1bd6a-885">**Data.Input.OpenOfflineCopy** – програмою запитано відкриття з автономної копії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-885">**Data.Input.OpenOfflineCopy -** Open from offline copy requested by add</span></span>

  - <span data-ttu-id="1bd6a-886">**Data.IOFlags** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-886">**Data.IOFlags -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-887">**Data.IsBaseBranchEmptyOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-887">**Data.IsBaseBranchEmptyOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-888">**Data.IsCachedHistoricalVersion** – кеш містить попередню версію документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-888">**Data.IsCachedHistoricalVersion -** Cache contains an older version of the document</span></span>

  - <span data-ttu-id="1bd6a-889">**Data.IsDocEnterpriseProtected** – до документа застосовано електронний захист даних (EDP)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-889">**Data.IsDocEnterpriseProtected -** Document has been protected by encryption (Electronic Document Protection / EDP)</span></span>

  - <span data-ttu-id="1bd6a-890">**Data.IsDocInODC** – документ було відкрито раніше, і він уже є в кеші</span><span class="sxs-lookup"><span data-stu-id="1bd6a-890">**Data.IsDocInODC -** Document has been opened before and is already in the cache</span></span>

  - <span data-ttu-id="1bd6a-891">**Data.IsMapUnMapCase** – частина стану кешованого файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-891">**Data.IsMapUnMapCase -** Part of state of cached file</span></span>

  - <span data-ttu-id="1bd6a-892">**Data.IsMapUnMapCase.End** – частина стану кешованого файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-892">**Data.IsMapUnMapCase.End -** Part of state of cached file</span></span>

  - <span data-ttu-id="1bd6a-893">**Data.IsOfficeHydrationInProgress** – Windows відновлює документ із автономного сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-893">**Data.IsOfficeHydrationInProgress -** The document is being restored from offline storage by Windows</span></span>

  - <span data-ttu-id="1bd6a-894">**Data.isOfficeHydrationRequired** – документ зараз перебуває в автономному сховищі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-894">**Data.isOfficeHydrationRequired -** The document is currently in offline storage</span></span>

  - <span data-ttu-id="1bd6a-895">**Data.isOpenFromCollab** – останню копію документа отримано зі спільної служби співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-895">**Data.isOpenFromCollab -** The latest copy of the document was retrieved from the shared collaboration service</span></span>

  - <span data-ttu-id="1bd6a-896">**Data.isPendingNameExist** – триває перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-896">**Data.isPendingNameExist -** Document rename is in progress</span></span>

  - <span data-ttu-id="1bd6a-897">**Data.IsStubFile** – документ ще не збережено у хмарній службі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-897">**Data.IsStubFile -** The document hasn’t been saved to the cloud service yet</span></span>

  - <span data-ttu-id="1bd6a-898">**Data.IsSyncBackedStateDifferentThanOnLastOpen** – стан документа змінився; можливо, зміни сталися, коли документ не було відкрито</span><span class="sxs-lookup"><span data-stu-id="1bd6a-898">**Data.IsSyncBackedStateDifferentThanOnLastOpen -** the document state has changed, changes may have arrived while the document wasn’t open</span></span>

  - <span data-ttu-id="1bd6a-899">**Data.isTaskCanceledAfterOpenComplete** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-899">**Data.isTaskCanceledAfterOpenComplete -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-900">**Data.IsWorkingBranchAvailableOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-900">**Data.IsWorkingBranchAvailableOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-901">**Data.LicenseStatus** – стан ліцензії на діагностичний продукт, за допомогою якого перевіряється, чи ввімкнуто відповідні функції продукту для ліцензії користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-901">**Data.LicenseStatus** - Diagnostic product license status, used to validate that appropriate product features are enabled for the user’s license type</span></span> 

  - <span data-ttu-id="1bd6a-902">**Data.LicenseType** – указує стан ліцензії (платна, безкоштовна, ознайомлювальна тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-902">**Data.LicenseType -** Indicates state of license (free/paid/trial etc.)</span></span>

  - <span data-ttu-id="1bd6a-903">**Data.Location** – указує тип і розташування носія даних (USB, хмара тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-903">**Data.Location -** Indicates storage media type/location (USB, Cloud, etc.)</span></span>

  - <span data-ttu-id="1bd6a-904">**Data.LockRequestDocMode** – указує, чи доступний документ для інших</span><span class="sxs-lookup"><span data-stu-id="1bd6a-904">**Data.LockRequestDocMode -** Indicates if the document is available to others</span></span>

  - <span data-ttu-id="1bd6a-905">**Data.MyDeferredValue** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-905">**Data.MyDeferredValue -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-906">**Data.Network.BytesReceived** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-906">**Data.Network.BytesReceived -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-907">**Data.Network.BytesSent** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-907">**Data.Network.BytesSent -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-908">**Data.Network.ConnectionsCreated** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-908">**Data.Network.ConnectionsCreated -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-909">**Data.Network.ConnectionsEnded** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-909">**Data.Network.ConnectionsEnded -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-910">**Data.OcsDisableReasons** – причина, чому спільна служба співпраці була недоступна для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-910">**Data.OcsDisableReasons -** Reason why the shared collaboration service wasn’t available for the document</span></span>

  - <span data-ttu-id="1bd6a-911">**Data.OcsHostOnOpen** – позначка про те, що під час відкриття керування перейде до спільної служби співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-911">**Data.OcsHostOnOpen -** Flag indicating that control will switch to the shared collaboration service during Open</span></span>

  - <span data-ttu-id="1bd6a-912">**Data.OpeningOfflineCopy** – позначка про те, що буде відкрито локальну копію документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-912">**Data.OpeningOfflineCopy -** Flag indicating that the local copy of the document will be opened</span></span>

  - <span data-ttu-id="1bd6a-913">**Data.Partition** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-913">**Data.Partition -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-914">**Data.RequestTime** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-914">**Data.RequestTime -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-915">**Data.ResourceIdHash** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-915">**Data.ResourceIdHash -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-916">**Data.ResumedIncrementalOpen** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-916">**Data.ResumedIncrementalOpen -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-917">**Data.RTCEnabled** – почав роботу протокол швидкого поширення змін</span><span class="sxs-lookup"><span data-stu-id="1bd6a-917">**Data.RTCEnabled -** the fast change distribution protocol has started</span></span>

  - <span data-ttu-id="1bd6a-918">**Data.SaveOnOpen** – незбережені зміни в локальному документі було збережено у службі під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-918">**Data.SaveOnOpen -** unsaved changes in the local document were saved to the service during Open</span></span>

  - <span data-ttu-id="1bd6a-919">**Data.ServerProtocol** – застаріле, замінено на Data\_Doc\_ServerProtocol</span><span class="sxs-lookup"><span data-stu-id="1bd6a-919">**Data.ServerProtocol -** Obsolete, replaced by Data\_Doc\_ServerProtocol</span></span>

  - <span data-ttu-id="1bd6a-920">**Data.ServerType** – застаріле, замінено на Data\_Doc\_ServerType</span><span class="sxs-lookup"><span data-stu-id="1bd6a-920">**Data.ServerType -** Obsolete, replaced by Data\_Doc\_ServerType</span></span>

  - <span data-ttu-id="1bd6a-921">**Data.ServerVersion** – застаріле, замінено на Data\_Doc\_ServerVersion</span><span class="sxs-lookup"><span data-stu-id="1bd6a-921">**Data.ServerVersion -** Obsolete, replaced by Data\_Doc\_ServerVersion</span></span>

  - <span data-ttu-id="1bd6a-922">**Data.ServiceId** – застаріле, замінено на Data\_Doc\_WopiServiceId</span><span class="sxs-lookup"><span data-stu-id="1bd6a-922">**Data.ServiceId -** Obsolete, replaced by Data\_Doc\_WopiServiceId</span></span>

  - <span data-ttu-id="1bd6a-923">**Data.SessionId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-923">**Data.SessionId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-924">**Data.ShouldSwitchToServerOnly** – локальну копію документа не можна використовувати, має використовуватися версія з сервера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-924">**Data.ShouldSwitchToServerOnly -** the local copy of the document cannot be used, and the server version must be used</span></span>

  - <span data-ttu-id="1bd6a-925">**Data.SpecialChars** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-925">**Data.SpecialChars -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-926">**Data.StopwatchDuration** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-926">**Data.StopwatchDuration -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-927">**Data.SyncBackedFileTelemetrySessionId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-927">**Data.SyncBackedFileTelemetrySessionId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-928">**Data.SyncElapsedTime** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-928">**Data.SyncElapsedTime -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-929">**Data.SyncRequestId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-929">**Data.SyncRequestId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-930">**Data.TestProperty** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-930">**Data.TestProperty -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-931">**Data.TransitionToHostOnOpen** – позначка про те, що сеанс підключиться до служби, де розміщено документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-931">**Data.TransitionToHostOnOpen -** flag indicating that the session will connect to the service hosting the document</span></span>

  - <span data-ttu-id="1bd6a-932">**Data.TransitionToHostOnOpenResult** – статус переходу до служби розміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-932">**Data.TransitionToHostOnOpenResult -** status of the transition to the host service</span></span>

  - <span data-ttu-id="1bd6a-933">**Data.UseCachedNetworkConnection** – позначка про те, чи було використано старе підключення, чи створено нове</span><span class="sxs-lookup"><span data-stu-id="1bd6a-933">**Data.UseCachedNetworkConnection -** flag to indicate if a connection was reused or a new connection created</span></span>

  - <span data-ttu-id="1bd6a-934">**Data.UseClientIdAsSchemaLockId** – позначка для керування блокуванням документів у службі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-934">**Data.UseClientIdAsSchemaLockId -** flag to control how documents are locked in the service</span></span>

  - <span data-ttu-id="1bd6a-935">**Data.WopiServiceId** – застаріле, замінено на Data\_Doc\_WopiServiceId</span><span class="sxs-lookup"><span data-stu-id="1bd6a-935">**Data.WopiServiceId -** Obsolete, replaced by Data\_Doc\_WopiServiceId</span></span>

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a><span data-ttu-id="1bd6a-936">Office.FileIO.CSI.CCachedFileCsiSaveFileBasic</span><span class="sxs-lookup"><span data-stu-id="1bd6a-936">Office.FileIO.CSI.CCachedFileCsiSaveFileBasic</span></span>

<span data-ttu-id="1bd6a-937">Повідомляє, чи успішно було збережено файл із рівня FIO.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-937">Allows us to know if a file was successfully saved from the FIO Layer.</span></span> <span data-ttu-id="1bd6a-938">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-938">Used for Feature Health and monitoring.</span></span>

<span data-ttu-id="1bd6a-939">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-939">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-940">**Activity.Group** – тег, який дає змогу групувати події моніторингу для контролю загального успіху</span><span class="sxs-lookup"><span data-stu-id="1bd6a-940">**Activity.Group -** tag that allows a set of monitoring events to be grouped to manage overall success</span></span>

  - <span data-ttu-id="1bd6a-941">**Activity.IsHVA** – позначка, яка показує, що подія критично важлива для успіху користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-941">**Activity.IsHVA -** flag to indicate that event is critical to user success</span></span>

  - <span data-ttu-id="1bd6a-942">**Data.AsyncOpen** – позначка про те, що документ було відкрито із вмістом, який з’явився після відкриття основного тексту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-942">**Data.AsyncOpen -** flag to indicate that the document was opened with content that arrived after the main body was opened</span></span>

  - <span data-ttu-id="1bd6a-943">**Data.BaseDownloadTriggered** – діагностика відстеження змін, яка показує, що було запитано базову версію документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-943">**Data.BaseDownloadTriggered -** Change tracking diagnostic indicating that the base version of the document was requested</span></span>

  - <span data-ttu-id="1bd6a-944">**Data.BlockAutoUploadReasons** – код причин стану блокування передавання (наприклад, автозбереження вимкнуто, виконується перехід документа)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-944">**Data.BlockAutoUploadReasons -** Reason codes for blocked upload state (e.g. Autosave is turned off, the document is transitioning)</span></span>

  - <span data-ttu-id="1bd6a-945">**Data.BlockUploadDueToFailedSaveAsOverExisting** – передавання заблоковано, оскільки його спроба призвела б до помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-945">**Data.BlockUploadDueToFailedSaveAsOverExisting -** Upload is blocked as it would fail if retried</span></span>

  - <span data-ttu-id="1bd6a-946">**Data.CacheFileId** – підключається до телеметрії кеша документів Office і забезпечує аналіз впливу проблем із кешем на користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-946">**Data.CacheFileId -** connects to Office Document Cache telemetry to enable impact analysis of cache issues on the user experience</span></span>

  - <span data-ttu-id="1bd6a-947">**Data.ChartType** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-947">**Data.ChartType -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-948">**Data.CoAuthStatus** – повідомляє статус співпраці над збереженим документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-948">**Data.CoAuthStatus -** reports collaborative status of the document on Save</span></span>

  - <span data-ttu-id="1bd6a-949">**Data.CoauthUpdatesContext** – повідомляє контекст (об’єднання/інкрементне відкриття)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-949">**Data.CoauthUpdatesContext -** reports context (Merge/Incremental Open)</span></span>

  - <span data-ttu-id="1bd6a-950">**Data.CountOfMultiRoundTripsDownload** – кількість звернень до сервера, які було використано для виправлення проблем із продуктивністю та мережею</span><span class="sxs-lookup"><span data-stu-id="1bd6a-950">**Data.CountOfMultiRoundTripsDownload -** Count of round trips to the server used to troubleshoot performance and network issues</span></span>

  - <span data-ttu-id="1bd6a-951">**Data.CountOfMultiRoundTripsUpload** – кількість звернень до сервера, які було використано для виправлення проблем із продуктивністю та мережею</span><span class="sxs-lookup"><span data-stu-id="1bd6a-951">**Data.CountOfMultiRoundTripsUpload -** Count of round trips to the server used to troubleshoot performance and network issues</span></span>

  - <span data-ttu-id="1bd6a-952">**Data.DialogChoice** – реєструє вибір, зроблений в усіх діалогових вікнах помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-952">**Data.DialogChoice -** Records choice made in any error dialogs</span></span>

  - <span data-ttu-id="1bd6a-953">**Data.DialogId** – реєструє ідентифікатор будь-якого діалогового вікна помилки, яке з’являлося під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-953">**Data.DialogId -** Records the DialogId of any error dialogs that display during save</span></span>

  - <span data-ttu-id="1bd6a-954">**Data.Dmc.IsOcsSupported** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-954">**Data.Dmc.IsOcsSupported -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-955">**Data.Doc.AccessMode** – документ лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-955">**Data.Doc.AccessMode -** Document is read only</span></span>

  - <span data-ttu-id="1bd6a-956">**Data.Doc.AssistedReadingReasons** – чи застосовано до документа електронний захист даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-956">**Data.Doc.AssistedReadingReasons -** Set if the document has electronic data protection in place</span></span>

  - <span data-ttu-id="1bd6a-957">**Data.Doc.ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-957">**Data.Doc.ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-958">**Data.Doc.EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-958">**Data.Doc.EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-959">**Data.Doc.Ext** – розширення документа (docx/xlsm/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-959">**Data.Doc.Ext -** Document extension (docx/xlsm/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-960">**Data.Doc.Extension** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-960">**Data.Doc.Extension -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-961">**Data.Doc.FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-961">**Data.Doc.FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-962">**Data.Doc.Fqdn** – ім’я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-962">**Data.Doc.Fqdn -** OneDrive or SharePoint Online Domain name</span></span>

  - <span data-ttu-id="1bd6a-963">**Data.Doc.FqdnHash** – односторонній геш-код особистого імені домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-963">**Data.Doc.FqdnHash -** One-way hash of the customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-964">**Data.Doc.FqdnHasi** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-964">**Data.Doc.FqdnHasi -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-965">**Data.Doc.IdentityTelemetryId** – односторонній геш-код ідентичності користувача, яку було використано для збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-965">**Data.Doc.IdentityTelemetryId -** A one-way hash of the user identity used to perform the save</span></span>

  - <span data-ttu-id="1bd6a-966">**Data.Doc.IdentityUniqueId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-966">**Data.Doc.IdentityUniqueId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-967">**Data.Doc.IKFlags** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-967">**Data.Doc.IKFlags -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-968">**Data.Doc.InitializationScenario** – реєструє, яким чином було відкрито документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-968">**Data.Doc.InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-969">**Data.Doc.IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-969">**Data.Doc.IOFlags -** Reports on the cached flags used to set request options</span></span>

  - <span data-ttu-id="1bd6a-970">**Data.Doc.IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-970">**Data.Doc.IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-971">**Data.Doc.IsCloudCollabEnabled** – позначка, яка вказує, що програма підтримує хмарну співпрацю</span><span class="sxs-lookup"><span data-stu-id="1bd6a-971">**Data.Doc.IsCloudCollabEnabled -** Flag indicating that the application supports Cloud Collaboration</span></span>

  - <span data-ttu-id="1bd6a-972">**Data.Doc.IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-972">**Data.Doc.IsIncrementalOpen -** Flag indicating that the document was opened incrementally</span></span>

  - <span data-ttu-id="1bd6a-973">**Data.Doc.IsOcsSupported** – позначка, яка вказує, що документ підтримує хмарну співпрацю</span><span class="sxs-lookup"><span data-stu-id="1bd6a-973">**Data.Doc.IsOcsSupported -** Flag indicating that the document supports Cloud Collaboration</span></span>

  - <span data-ttu-id="1bd6a-974">**Data.Doc.IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-974">**Data.Doc.IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-975">**Data.Doc.IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-975">**Data.Doc.IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-976">**Data.Doc.Location** – указує службу, яка надала документ (OneDrive, файловий сервер, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-976">**Data.Doc.Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-977">**Data.Doc.LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-977">**Data.Doc.LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-978">**Data.Doc.NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-978">**Data.Doc.NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-979">**Data.Doc.PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-979">**Data.Doc.PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-980">**Data.Doc.ReadOnlyReasons** –причини, з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-980">**Data.Doc.ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-981">**Data.Doc.ResourceIdHash** – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-981">**Data.Doc.ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-982">**Data.Doc.ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-982">**Data.Doc.ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-983">**Data.Doc.ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-983">**Data.Doc.ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-984">**Data.Doc.ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-984">**Data.Doc.ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-985">**Data.Doc.ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-985">**Data.Doc.ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-986">**Data.Doc.SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-986">**Data.Doc.SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-987">**Data.Doc.SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-987">**Data.Doc.SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-988">**Data.Doc.SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-988">**Data.Doc.SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-989">**Data.Doc.SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-989">**Data.Doc.SpecialChars -** Indicator of special chars in the document’s URL or Path</span></span>

  - <span data-ttu-id="1bd6a-990">**Data.Doc.StorageProviderId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-990">**Data.Doc.StorageProviderId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-991">**Data.Doc.StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-991">**Data.Doc.StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-992">**Data.Doc.SussionId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-992">**Data.Doc.SussionId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-993">**Data.Doc.SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-993">**Data.Doc.SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-994">**Data.Doc.UrlHash** – односторонній геш-код для створення наївного ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-994">**Data.Doc.UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-995">**Data.Doc.UsedWrsDataOnOpen** – діагностичний індикатор для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-995">**Data.Doc.UsedWrsDataOnOpen -** Diagnostic indicator for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-996">**Data.Doc.WopiServiceId** – містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-996">**Data.Doc.WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-997">**Data.DocnReadOnlyReasons** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-997">**Data.DocnReadOnlyReasons -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-998">**Data.DocumentSaveEndpoint** – застаріле, замінено на Data\_Doc\_Location</span><span class="sxs-lookup"><span data-stu-id="1bd6a-998">**Data.DocumentSaveEndpoint -** Obsolete, replaced by Data\_Doc\_Location</span></span>

  - <span data-ttu-id="1bd6a-999">**Data.DocumentSaveType** – тип збереження (Normal, Create, SaveAs)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-999">**Data.DocumentSaveType -** Type of Save (Normal, Create, SaveAs)</span></span>

  - <span data-ttu-id="1bd6a-1000">**Data.DocumentSizeOnDisk** – застаріле, замінено на Data\_Doc\_SizeInBytes</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1000">**Data.DocumentSizeOnDisk -** Obsolete, replaced by Data\_Doc\_SizeInBytes</span></span>

  - <span data-ttu-id="1bd6a-1001">**Data.DoesBaseHaveContentOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1001">**Data.DoesBaseHaveContentOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-1002">**Data.DoesWorkingBranchHaveExcludedDataOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1002">**Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-1003">**Data.DstDoc.AccessMode** – новий документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1003">**Data.DstDoc.AccessMode -** New document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-1004">**Data.DstDoc.EdpState** – параметр електронного захисту даних для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1004">**Data.DstDoc.EdpState -** Electronic Data Protection setting for the new document</span></span>

  - <span data-ttu-id="1bd6a-1005">**Data.DstDoc.Extension** – розширення нового документа (docx/xlsm/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1005">**Data.DstDoc.Extension -** New document’s extension (docx/xlsm/pptx, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1006">**Data.DstDoc.FileFormat** – протокол формату файлу нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1006">**Data.DstDoc.FileFormat -** New document’s file format protocol</span></span>

  - <span data-ttu-id="1bd6a-1007">**Data.DstDoc.Fqdn** – ім’я домену OneDrive або SharePoint Online нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1007">**Data.DstDoc.Fqdn -** New document’s OneDrive or SharePoint Online domain name</span></span>

  - <span data-ttu-id="1bd6a-1008">**Data.DstDoc.FqdnHash** – односторонній геш-код особистого імені домену користувача для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1008">**Data.DstDoc.FqdnHash -** One-way hash of new document’s customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-1009">**Data.DstDoc.IdentityUniqueId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1009">**Data.DstDoc.IdentityUniqueId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1010">**Data.DstDoc.IOFlags** – позначки параметрів кешування документа, які використовуються під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1010">**Data.DstDoc.IOFlags -** New document’s cached options flags used when opening</span></span>

  - <span data-ttu-id="1bd6a-1011">**Data.DstDoc.IsOpeningOfflineCopy** – позначка відкриття автономної копії нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1011">**Data.DstDoc.IsOpeningOfflineCopy -** Flag indicating that an offline copy of the new document was opened</span></span>

  - <span data-ttu-id="1bd6a-1012">**Data.DstDoc.IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1012">**Data.DstDoc.IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-1013">**Data.DstDoc.Location** – указує службу, яка надала новий документ (OneDrive, файловий сервер, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1013">**Data.DstDoc.Location -** Indicates which service provided the new document (OneDrive, File Server, SharePoint, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1014">**Data.DstDoc.NumberCoAuthors** – кількість користувачів у сеансі спільного редагування нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1014">**Data.DstDoc.NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session on the new document</span></span>

  - <span data-ttu-id="1bd6a-1015">**Data.DstDoc.ReadOnlyReasons** –причини, з яких новий документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1015">**Data.DstDoc.ReadOnlyReasons -** Reasons why the new document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-1016">**Data.DstDoc.ResourceIdHash** – анонімний ідентифікатор нового документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1016">**Data.DstDoc.ResourceIdHash -** An anonymized document identifier used to diagnose problems with the new document</span></span>

  - <span data-ttu-id="1bd6a-1017">**Data.DstDoc.ServerDocId** – незмінний анонімний ідентифікатор нового документа для діагностики проблем із новим документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1017">**Data.DstDoc.ServerDocId -** An immutable anonymized document identifier used to diagnose problems with the new document</span></span>

  - <span data-ttu-id="1bd6a-1018">**Data.DstDoc.ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою під час створення нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1018">**Data.DstDoc.ServerProtocol -** the protocol version used to communicate with the service when creating the new document</span></span>

  - <span data-ttu-id="1bd6a-1019">**Data.DstDoc.ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо) для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1019">**Data.DstDoc.ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.) for the new document</span></span>

  - <span data-ttu-id="1bd6a-1020">**Data.DstDoc.ServerVersion** – версія сервера, який надає службу для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1020">**Data.DstDoc.ServerVersion -** the server version offering the service for the new document</span></span>

  - <span data-ttu-id="1bd6a-1021">**Data.DstDoc.SessionId** – визначає сеанс редагування документа в межах повного сеансу для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1021">**Data.DstDoc.SessionId -** Identifies a specific document edit session within the full session for the new document</span></span>

  - <span data-ttu-id="1bd6a-1022">**Data.DstDoc.SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online для нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1022">**Data.DstDoc.SharePointServiceContext -** Diagnostic information from SharePoint Online requests for the new document</span></span>

  - <span data-ttu-id="1bd6a-1023">**Data.DstDoc.SizeInBytes** – індикатор розміру нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1023">**Data.DstDoc.SizeInBytes -** Indicator of document size of new document</span></span>

  - <span data-ttu-id="1bd6a-1024">**Data.DstDoc.UrlHash** – односторонній геш-код для створення наївного ідентифікатора нового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1024">**Data.DstDoc.UrlHash -** One-way hash to create a naïve document identifier for the new document</span></span>

  - <span data-ttu-id="1bd6a-1025">**Data.EditorsCount** – кількість інших співавторів, які редагують документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1025">**Data.EditorsCount -** A count of other collaborators editing the document</span></span>

  - <span data-ttu-id="1bd6a-1026">**Data.FullIError** – кеш усіх кодів помилок із рівня протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1026">**Data.FullIError -** Cache of all error codes from the protocol layer</span></span>

  - <span data-ttu-id="1bd6a-1027">**Data.HasFilteredCategories** – застарілий</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1027">**Data.HasFilteredCategories -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1028">**Data.HasFilteredCategoryNames** – застарілий</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1028">**Data.HasFilteredCategoryNames -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1029">**Data.HasFilteredSeries** – застарілий</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1029">**Data.HasFilteredSeries -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1030">**Data.HasFilteredSeriesNames** – застарілий</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1030">**Data.HasFilteredSeriesNames -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1031">**Data.HasPendingSaveAs** – указує, що триває запит "Зберегти як/Зберегти копію"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1031">**Data.HasPendingSaveAs -** Indicates that a request Save As/Save a Copy is in progress</span></span>

  - <span data-ttu-id="1bd6a-1032">**Data.Input.FileOpenState** – стан, запитаний програмою (Read/ReadWrite тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1032">**Data.Input.FileOpenState -** State requested by app (Read/ReadWrite, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1033">**Data.Input.FileSaveState** – стан, запитаний програмою (Save on Open, Save As тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1033">**Data.Input.FileSaveState -** State requested by app (Save on Open, Save As, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1034">**Data.Input.NetworkCost** – указує тарифікацію/тип мережі (лімітний, лімітний із перевищенням тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1034">**Data.Input.NetworkCost -** Indicates network cost/type (metered, metered above cap, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1035">**Data.Input.OpenAsync** – позначка про те, що програма запитала асинхронне відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1035">**Data.Input.OpenAsync -** Flag indicates app requested an async open</span></span>

  - <span data-ttu-id="1bd6a-1036">**Data.Input.OpenOfflineCopy** – позначка про те, що програма запитала відкриття з автономної копії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1036">**Data.Input.OpenOfflineCopy -** Flag indicates app requested an offline open</span></span>

  - <span data-ttu-id="1bd6a-1037">**Data.IsCachedHistoricalVersion** – указує, що файл у кеші не є останньою версією</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1037">**Data.IsCachedHistoricalVersion -** Indicates that this cached file is not the latest version</span></span>

  - <span data-ttu-id="1bd6a-1038">**Data.IsHtml** – указує, що вставлено текст у форматі HTML</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1038">**Data.IsHtml -** Indicates that HTML format text was pasted</span></span>

  - <span data-ttu-id="1bd6a-1039">**Data.IsLegacyCode** – указує, що вставлено текст у застарілому форматі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1039">**Data.IsLegacyCode -** Indicates that Legacy code format text was pasted</span></span>

  - <span data-ttu-id="1bd6a-1040">**Data.IsLocalOnlyFile** – указує, що відкрито файл лише з локального сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1040">**Data.IsLocalOnlyFile -** Indicates that the file was opened from local storage only</span></span>

  - <span data-ttu-id="1bd6a-1041">**Data.IsLocalOrSyncBackedFile** – указує, що файл відкрито локально та зіставлено зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1041">**Data.IsLocalOrSyncBackedFile -** Indicates that the file was opened locally and mapped through to the service</span></span>

  - <span data-ttu-id="1bd6a-1042">**Data.IsMapUnMapCase** – частина стану кешованого файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1042">**Data.IsMapUnMapCase -** Part of state of cached file</span></span>

  - <span data-ttu-id="1bd6a-1043">**Data.isOpenFromCollab** – указує, що файл відкрито зі спільної служби співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1043">**Data.isOpenFromCollab -** Indicates that the file was opened from the shared collaboration service</span></span>

  - <span data-ttu-id="1bd6a-1044">**Data.IsStubFile** – до документа ще не надано спільний доступ у хмарній службі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1044">**Data.IsStubFile -** The document hasn’t been shared to the cloud service yet</span></span>

  - <span data-ttu-id="1bd6a-1045">**Data.IsSyncBackedFile** – документ міститься в папці, яка оновлюється автосинхронізацією</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1045">**Data.IsSyncBackedFile -** the document is in a folder that is auto sync updated</span></span>

  - <span data-ttu-id="1bd6a-1046">**Data.IsSyncBackedStateDifferentThanOnLastOpen** – стан документа змінився; можливо, зміни сталися, коли документ не було відкрито</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1046">**Data.IsSyncBackedStateDifferentThanOnLastOpen -** the document state has changed, changes may have arrived while the document wasn’t open</span></span>

  - <span data-ttu-id="1bd6a-1047">**Data.IsWorkingBranchAvailableOnOpen** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1047">**Data.IsWorkingBranchAvailableOnOpen -** change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-1048">**Data.Location** – указує тип і розташування носія даних (USB, хмара тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1048">**Data.Location -** Indicates storage media type/location (USB; Cloud, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1049">**Data.LockRequestDocMode** – указує, чи доступний документ для інших</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1049">**Data.LockRequestDocMode -** Indicates if the document is available to others</span></span>

  - <span data-ttu-id="1bd6a-1050">**Data.MruRequestResult** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1050">**Data.MruRequestResult -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1051">**Data.NewDataNotAvailableReason** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1051">**Data.NewDataNotAvailableReason -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1052">**Data.OcsDisableReasons** – не використовується операцією збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1052">**Data.OcsDisableReasons -** Not used by Save</span></span>

  - <span data-ttu-id="1bd6a-1053">**Data.OcsHostOnOpen** – не використовується операцією збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1053">**Data.OcsHostOnOpen -** Not used by Save</span></span>

  - <span data-ttu-id="1bd6a-1054">**Data.Output.FileSaveState** – стан на момент завершення збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1054">**Data.Output.FileSaveState -** State on save completion</span></span>

  - <span data-ttu-id="1bd6a-1055">**Data.PivotChart** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1055">**Data.PivotChart -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1056">**Data.resolveConflictState** – коди причин для запиту на усунення конфліктів злиття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1056">**Data.resolveConflictState -** Reason codes for a request to resolve merge conflicts</span></span>

  - <span data-ttu-id="1bd6a-1057">**Data.RTCEnabled** – почав роботу протокол швидкого поширення змін</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1057">**Data.RTCEnabled -** the fast change distribution protocol has started</span></span>

  - <span data-ttu-id="1bd6a-1058">**Data.SaveAsToCurrent** – указує, що активний документ замінить файл, який зберігається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1058">**Data.SaveAsToCurrent -** Indicates that the active document will overwrite the stored file</span></span>

  - <span data-ttu-id="1bd6a-1059">**Data.ServiceId** – застаріле, замінено на Data\_Doc\_WopiServiceId</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1059">**Data.ServiceId -** Obsolete, replaced by Data\_Doc\_WopiServiceId</span></span>

  - <span data-ttu-id="1bd6a-1060">**Data.SessionId** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1060">**Data.SessionId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1061">**Data.SizeInBytes** – застаріле, замінено на Data\_Doc\_SizeInBytes</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1061">**Data.SizeInBytes -** Obsolete, replaced by Data\_Doc\_SizeInBytes</span></span>

  - <span data-ttu-id="1bd6a-1062">**Data.StopwatchDuration** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1062">**Data.StopwatchDuration -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1063">**Data.SyncBackedFileRequiresOnlineTran** – позначка про те, що операцію збереження тимчасово заблоковано переходом до мережі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1063">**Data.SyncBackedFileRequiresOnlineTransition -** Flag indicating that Save action is temporarily blocked by online transition</span></span>

  - <span data-ttu-id="1bd6a-1064">**Data.SyncBackedFileSaveOnOpen** – позначка про те, що зміни, внесені автоматичною синхронізацією, потребують збереження під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1064">**Data.SyncBackedFileSaveOnOpen -** Flag indicating that changes made by auto sync require a save on open</span></span>

  - <span data-ttu-id="1bd6a-1065">**Data.TelemetryId** – застаріло</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1065">**Data.TelemetryId -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1066">**Data.TriggerSaveAfterBaseDownload** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1066">**Data.TriggerSaveAfterBaseDownload -** change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-1067">**Data.UploadBlockedDueToCoherencyFailure** – збереження у службі заблоковано, очікується вирішення користувачем конфліктних змін</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1067">**Data.UploadBlockedDueToCoherencyFailure -** Save to service blocked pending user resolution of conflicting changes</span></span>

  - <span data-ttu-id="1bd6a-1068">**Data.UploadBlockedDueToFailedSaveAsOverExisting** – збереження у службі заблоковано через невдалу спробу замінити наявний файл</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1068">**Data.UploadBlockedDueToFailedSaveAsOverExisting -** Save to service blocked due to failed attempt to overwrite an existing file</span></span>

  - <span data-ttu-id="1bd6a-1069">**Data.UploadPreemptedForCoherency** – збереження у службі припинено, оскільки користувач вносить нові зміни</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1069">**Data.UploadPreemptedForCoherency -** Save to service abandoned as more changes are being made by the user</span></span>

  - <span data-ttu-id="1bd6a-1070">**Data.UploadPreemptedForSaveAsOverExistingFailure** – збереження у службі припинено через ранішу помилку SaveAsOverExisting</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1070">**Data.UploadPreemptedForSaveAsOverExistingFailure -** Save to service abandoned due to earlier SaveAsOverExisting failure</span></span>

  - <span data-ttu-id="1bd6a-1071">**Data.UploadScheduled** – файл готовий до асинхронної передачі до служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1071">**Data.UploadScheduled -** file is ready to be asynchronously uploaded to the service</span></span>

  - <span data-ttu-id="1bd6a-1072">**Data.UseClientIdAsSchemaLockId** – позначка для керування блокуванням документів у службі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1072">**Data.UseClientIdAsSchemaLockId -** flag to control how documents are locked in the service</span></span>

  - <span data-ttu-id="1bd6a-1073">**Data.WorkingCopySaved** – діагностика відстеження змін, щоб можна було засвідчити, що це остання версія спільного файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1073">**Data.WorkingCopySaved -** change tracking diagnostic making sure we have the latest version of a shared file</span></span>

  - <span data-ttu-id="1bd6a-1074">**Data.ZrtSaveAsforSyncBackedBusinessEnabled** – позначка про те, що ввімкнуто швидке збереження для SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1074">**Data.ZrtSaveAsforSyncBackedBusinessEnabled -** flag indicating fast save enabled for SharePoint Online</span></span>

  - <span data-ttu-id="1bd6a-1075">**Data.ZrtSaveAsforSyncBackedConsumerEnabled** – позначка про те, що ввімкнуто швидке збереження для OneDrive для споживачів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1075">**Data.ZrtSaveAsforSyncBackedConsumerEnabled -** flag indicating fast save enabled for OneDrive Consumer</span></span>

  - <span data-ttu-id="1bd6a-1076">**Data.ZrtSaveAsforSyncBackedCTBusinessEnabled** – позначка про те, що ввімкнуто швидке збереження типів вмісту для SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1076">**Data.ZrtSaveAsforSyncBackedCTBusinessEnabled -** flag indicating fast save content types enabled for SharePoint Online</span></span>

  - <span data-ttu-id="1bd6a-1077">**Data.ZrtSaveAsforSyncBackedCTConsumerEnabled** – позначка про те, що ввімкнуто швидке збереження типів вмісту для OneDrive для споживачів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1077">**Data.ZrtSaveAsforSyncBackedCTConsumerEnabled -** flag indicating fast save content types enabled for OneDrive Consumer</span></span>

  - <span data-ttu-id="1bd6a-1078">**Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled** – позначка про те, що ввімкнуто швидке збереження метаданих файлу для SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1078">**Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled -** flag indicating fast file metadata save enabled for SharePoint Online</span></span>

  - <span data-ttu-id="1bd6a-1079">**Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled** – позначка про те, що ввімкнуто швидке збереження метаданих файлу для OneDrive для споживачів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1079">**Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled -** flag indicating fast file metadata save enabled for OneDrive Consumer-</span></span>

#### <a name="officefindtimeappfailedtostart"></a><span data-ttu-id="1bd6a-1080">Office.FindTime.AppFailedToStart</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1080">Office.FindTime.AppFailedToStart</span></span>

<span data-ttu-id="1bd6a-1081">Збирається, якщо програма не може запуститися через неочікувану помилку під час запуску.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1081">Collected when app fails to start due to an unexpected error during startup.</span></span> <span data-ttu-id="1bd6a-1082">Використовується для відстеження виняткових ситуацій та аварійних завершень роботи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1082">Used to track exceptions & crashes.</span></span> <span data-ttu-id="1bd6a-1083">Допомагає контролювати й налагоджувати справність програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1083">Helps monitor & debug app health.</span></span>

<span data-ttu-id="1bd6a-1084">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1084">The following fields are collected:</span></span>
- <span data-ttu-id="1bd6a-1085">**DateTime** – позначка часу реєстрації події</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1085">**DateTime** - Timestamp of when the event is logged</span></span>

- <span data-ttu-id="1bd6a-1086">**EventName** – ім’я події, яка реєструється</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1086">**EventName** - The name of the event being logged</span></span>


#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a><span data-ttu-id="1bd6a-1087">Office.Manageability.Client Fetch.PolicyPreChecks</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1087">Office.Manageability.Client Fetch.PolicyPreChecks</span></span>

<span data-ttu-id="1bd6a-1088">Критично важлива телеметрія для відстеження невдач\\успіхів із метою підтвердження попередньої перевірки отримання хмарної політики.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1088">Critical telemetry to track failure\\success for cloud policy fetch precheck validation.</span></span> <span data-ttu-id="1bd6a-1089">ExitReason містить нумератор, зіставлений з умовою попередньої перевірки з невдалим результатом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1089">ExitReason contains an enumerator map to the pre-check condition that failed.</span></span>

<span data-ttu-id="1bd6a-1090">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1090">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1091">**Data.ExitReason** – значення-нумератор, яке повідомляє причину виходу, якщо попередня перевірка зазнала невдачі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1091">**Data.ExitReason** - An enumerator value telling the exit reason, if the Precheck failed</span></span>

  - <span data-ttu-id="1bd6a-1092">**Data.Log** – спеціальне повідомлення журналу, яке показує успіх чи невдачу попередньої перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1092">**Data.Log** - Custom log message indicating the precheck success or failure</span></span>

#### <a name="officemanageabilityclientfetchandapplypolicy"></a><span data-ttu-id="1bd6a-1093">Office.Manageability.Client.Fetch.AndApplyPolicy</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1093">Office.Manageability.Client.Fetch.AndApplyPolicy</span></span>

<span data-ttu-id="1bd6a-1094">Критично важлива телеметрія для відстеження невдач\\успіхів із метою ініціювання з програми отримання хмарної політики.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1094">Critical telemetry to track failure\\success for cloud policy fetch initiation from app.</span></span> <span data-ttu-id="1bd6a-1095">Причина виходу містить нумератор, зіставлений із причиною помилки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1095">Exit Reason contains an enumerator Map to the failure reason.</span></span>

<span data-ttu-id="1bd6a-1096">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1096">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1097">**Data.ExitReason** – значення-нумератор, яке повідомляє причину виходу, якщо попередня перевірка зазнала невдачі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1097">**Data.ExitReason** - An enumerator value telling the exit reason, if the Precheck failed</span></span>

  - <span data-ttu-id="1bd6a-1098">**Data.Log** – спеціальне повідомлення журналу, яке показує успіх чи невдачу попередньої перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1098">**Data.Log** - Custom log message indicating the precheck success or failure</span></span>

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a><span data-ttu-id="1bd6a-1099">Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1099">Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult</span></span>

<span data-ttu-id="1bd6a-1100">Результат додавання облікового запису до програми Outlook у новому профілі, з подання Office Backstage або з діалогового вікна параметрів облікового запису.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1100">Result of adding an account to Outlook in a new profile, from the Office Backstage, or from the account settings dialog.</span></span> <span data-ttu-id="1bd6a-1101">Дані активно відстежуються з метою забезпечити відсутність будь-якого зростання помилок.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1101">The data is actively monitored to ensure we don't see any spikes in failures.</span></span> <span data-ttu-id="1bd6a-1102">Також дані аналізуються для пошуку областей, де потрібне вдосконалення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1102">We also analyze the data to find areas of improvement.</span></span> <span data-ttu-id="1bd6a-1103">Ми прагнемо покращувати цей показник успіху з кожним випуском.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1103">We aim to improve this success rate with each release.</span></span>

<span data-ttu-id="1bd6a-1104">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1104">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1105">**AccountCreationResult** – результат (успіх, невдача, скасування тощо) додавання облікового запису до Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1105">**AccountCreationResult** – The result (success, failure, cancellation, etc.) of adding the account to Outlook.</span></span>

  - <span data-ttu-id="1bd6a-1106">**AccountCreationTime** – час, витрачений на спробу створення облікового запису</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1106">**AccountCreationTime** – time taken to attempt account creation</span></span>

  - <span data-ttu-id="1bd6a-1107">**AccountInfoSource** – джерело параметрів облікового запису (наприклад AutoDiscover, GuessSmart, AutoDetect тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1107">**AccountInfoSource** - account settings source (e.g. AutoDiscover, GuessSmart, AutoDetect, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1108">**AccountType** – тип налаштовуваного облікового запису.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1108">**AccountType** – The type of account being configured.</span></span>

  - <span data-ttu-id="1bd6a-1109">**HashedEmailAddress** – геш-код адреси електронної пошти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1109">**HashedEmailAddress** – hashed email address</span></span>

  - <span data-ttu-id="1bd6a-1110">**ShowPasswordPageFlightEnabled** – показує, чи активовано тест ShowPopImapPasswordPage</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1110">**ShowPasswordPageFlightEnabled** - indicator if ShowPopImapPasswordPage flight is enabled</span></span>

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a><span data-ttu-id="1bd6a-1111">Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1111">Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult</span></span>

<span data-ttu-id="1bd6a-1112">Результат відновлення облікового запису або змінення розширених параметрів облікового запису.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1112">Result of repairing an account or changing advanced account settings.</span></span> <span data-ttu-id="1bd6a-1113">Дані активно відстежуються з метою забезпечити відсутність будь-якого зростання помилок.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1113">The data is actively monitored to ensure we don't see any spikes in failures.</span></span> <span data-ttu-id="1bd6a-1114">Також дані аналізуються для пошуку областей, де потрібне вдосконалення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1114">We also analyze the data to find areas of improvement.</span></span> <span data-ttu-id="1bd6a-1115">Оскільки це нові (перероблені) можливості, ми бажаємо переконатися, що їх реалізовано правильно.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1115">Since this a new (refactored) experiences we want to make sure we got this right.</span></span>

<span data-ttu-id="1bd6a-1116">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1116">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1117">**AccountInfoSource** – джерело відомостей про обліковий запис, який використовується у спробі відновлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1117">**AccountInfoSource** - account info source for the account used to attempt repair</span></span>

  - <span data-ttu-id="1bd6a-1118">**AccountType** – тип облікового запису, для якого була зроблена спроба відновлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1118">**AccountType** - type of account for which account repair was attempted</span></span>

  - <span data-ttu-id="1bd6a-1119">**HashedEmailAddress** – геш-код адреси електронної пошти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1119">**HashedEmailAddress** - hashed email address</span></span>

  - <span data-ttu-id="1bd6a-1120">**ManualRepairRequested** – показує, чи було запитано відновлення вручну</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1120">**ManualRepairRequested** - indicator if manual repair was requested</span></span>

  - <span data-ttu-id="1bd6a-1121">**Результат** – результат спроби відновити обліковий запис.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1121">**Result** - result of attempt to repair account.</span></span> <span data-ttu-id="1bd6a-1122">Наприклад: "Успіх" або "Невдача\_SaveChangesToAccount"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1122">For example: "Success" or "Fail\_SaveChangesToAccount"</span></span>

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a><span data-ttu-id="1bd6a-1123">Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1123">Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult</span></span>

<span data-ttu-id="1bd6a-1124">Результат оновлення пароля облікового запису з розкривного меню параметрів облікового запису.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1124">Result of updating an account's password from the Account Settings dropdown.</span></span> <span data-ttu-id="1bd6a-1125">Дані активно відстежуються з метою забезпечити відсутність будь-якого зростання помилок.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1125">The data is actively monitored to ensure we don't see any spikes in failures.</span></span> <span data-ttu-id="1bd6a-1126">Також дані аналізуються для пошуку областей, де потрібне вдосконалення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1126">We also analyze the data to find areas of improvement.</span></span> <span data-ttu-id="1bd6a-1127">Оскільки це нові (перероблені) можливості, ми бажаємо переконатися, що їх реалізовано правильно.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1127">Since this a new (refactored) experiences we want to make sure we got this right.</span></span>

<span data-ttu-id="1bd6a-1128">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1128">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1129">**AccountType** – тип облікового запису, для якого була зроблена спроба оновлення пароля</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1129">**AccountType** - type of account for which updating password was attempted</span></span>

  - <span data-ttu-id="1bd6a-1130">**HashedEmailAddress** – геш-код адреси електронної пошти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1130">**HashedEmailAddress** - hashed email address</span></span>

  - <span data-ttu-id="1bd6a-1131">**Результат** – результат спроби оновити пароль.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1131">**Result** - result of attempt to update password.</span></span> <span data-ttu-id="1bd6a-1132">Наприклад: "Успіх" або "Невдача\_AllowLessSecureAppsDisabled"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1132">For example: "Success" or "Fail\_AllowLessSecureAppsDisabled"</span></span>

#### <a name="officeoutlookdesktopprovidersloadproviderlibrary"></a><span data-ttu-id="1bd6a-1133">Office.Outlook.Desktop.Providers.LoadProviderLibrary</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1133">Office.Outlook.Desktop.Providers.LoadProviderLibrary</span></span>

<span data-ttu-id="1bd6a-1134">Ця подія відстежує успіх або невдачу спроби MAPI завантажити DLL постачальника (наприклад, contab32.dll, emsmdb32.dll, або DLL, що використовується надбудовою).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1134">This event tracks the success or failure of MAPI trying to load a provider DLL (e.g. contab32.dll, emsmdb32.dll, a DLL used by an add-in).</span></span> <span data-ttu-id="1bd6a-1135">Операції MAPI із завантаження DLL постачальника дуже важливі для базових функціональних можливостей Outlook, а також для їхнього розширення (за допомогою надбудов або спеціальних постачальників послуг сховища, транспорту або адресної книги).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1135">The MAPI operation responsible for loading provider DLLs is fundamental for Outlook’s Required operation as well as extensibility (via Add-ins or custom Store/Transport/AddressBook providers).</span></span> <span data-ttu-id="1bd6a-1136">Ми активно відстежуємо успішні або невдалі результати цієї операції, щоб гарантувати належне виконання цієї базової функції MAPI.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1136">We actively monitor the success or failure result of this operation to ensure that this core MAPI functionality continues to work as expected.</span></span>

<span data-ttu-id="1bd6a-1137">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1137">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1138">**Стандартна робота HVA** без користувацького навантаження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1138">**Standard HVA Activity** with no custom payload</span></span>

#### <a name="officeoutlookdesktopstorescreatenewstore"></a><span data-ttu-id="1bd6a-1139">Office.Outlook.Desktop.Stores.CreateNewStore</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1139">Office.Outlook.Desktop.Stores.CreateNewStore</span></span>

<span data-ttu-id="1bd6a-1140">Збирає результат створення нового сховища (тип і версію), а також код результату.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1140">Collects the result of creating a new store (with type and version), as well as the result code.</span></span> <span data-ttu-id="1bd6a-1141">Ми активно відстежуємо цю подію, щоб контролювати здатність користувача синхронізувати та зберігати пошту локально, архівувати повідомлення (в PST) або використовувати Групи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1141">We actively monitor this event to track the health a user’s ability to sync and store mail locally, archive mails (in a PST), or use Groups.</span></span>

<span data-ttu-id="1bd6a-1142">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1142">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1143">**Стандартна робота HVA** з користувацьким навантаженням</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1143">**Standard HVA Activity** with custom payload</span></span>

  - <span data-ttu-id="1bd6a-1144">**StoreType** – тип створеного сховища, OST/PST/NST</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1144">**StoreType** – The type of store created OST/PST/NST</span></span>

  - <span data-ttu-id="1bd6a-1145">**StoreVersion** – версія створеного сховища, Small/Large/Tardis</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1145">**StoreVersion** – The store version created Small/Large/Tardis</span></span>

#### <a name="officepowerpointdocoperationclose"></a><span data-ttu-id="1bd6a-1146">Office.PowerPoint.DocOperation.Close</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1146">Office.PowerPoint.DocOperation.Close</span></span>

<span data-ttu-id="1bd6a-1147">Збирається під час закриття презентацій PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1147">Collected when PowerPoint presentations are closed.</span></span> <span data-ttu-id="1bd6a-1148">Містить відомості, необхідні для належного дослідження та діагностування проблем, які виникають у процесі закриття, пов’язаного зі збереженням і синхронізацією даних користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1148">It contains the information needed to be able to properly investigate and diagnose issues that happen through the close process which entail persisting and syncing the user's data.</span></span> <span data-ttu-id="1bd6a-1149">Корпорація Майкрософт за допомогою цих даних підтверджує належне виконання операції закриття та успішне збереження вмісту користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1149">Microsoft uses this data to ensure that close is working as expected and user content is successfully being persisted.</span></span>

<span data-ttu-id="1bd6a-1150">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1150">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1151">**Data\_AddDocTelemetryResult:long** – чи є в цьому записі журналу вся необхідна телеметрія документа (поля Data\_Doc\_\*)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1151">**Data\_AddDocTelemetryResult:long -** Does this log entry have all necessary document telemetry (Data\_Doc\_\* fields)?</span></span> <span data-ttu-id="1bd6a-1152">Якщо ні, чому?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1152">If not, why?</span></span>

  - <span data-ttu-id="1bd6a-1153">**Data\_AutoSaveDisabledReasons:string** – попередньо визначений набір значень – причин, чому вимкнуто автозбереження в цьому документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1153">**Data\_AutoSaveDisabledReasons:string -** Predefined set of values of why was autosave disabled on this document?</span></span> <span data-ttu-id="1bd6a-1154">(помилка об'єднання, помилка збереження, групова політика тощо).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1154">(Merge error, Save error, Group policy etc.)</span></span>

  - <span data-ttu-id="1bd6a-1155">**Data\_CloseReason:long** – як було виконано закриття?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1155">**Data\_CloseReason:long -** How was close performed?</span></span> <span data-ttu-id="1bd6a-1156">Закриття документа?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1156">Closing document?</span></span> <span data-ttu-id="1bd6a-1157">Закриття програми?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1157">Closing app?</span></span>

  - <span data-ttu-id="1bd6a-1158">**Data\_CppUncaughtExceptionCount:long** – кількість необроблених винятків</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1158">**Data\_CppUncaughtExceptionCount:long -** Number of unhandled exceptions</span></span>

  - <span data-ttu-id="1bd6a-1159">**Data\_DetachedDuration:long** – час, протягом якого дія була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1159">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-1160">**Data\_Doc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1160">**Data\_Doc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1161">**Data\_Doc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1161">**Data\_Doc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1162">**Data\_Doc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1162">**Data\_Doc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1163">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1163">**Data\_Doc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1164">**Data\_Doc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1164">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1165">**Data\_Doc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1165">**Data\_Doc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1166">**Data\_Doc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1166">**Data\_Doc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1167">**Data\_Doc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1167">**Data\_Doc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1168">**Data\_Doc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1168">**Data\_Doc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1169">**Data\_Doc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1169">**Data\_Doc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1170">**Data\_Doc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1170">**Data\_Doc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1171">**Data\_Doc\_IOFlags:long –** бітова маска для різних позначок пов'язаних з IO для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1171">**Data\_Doc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1172">**Data\_Doc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1172">**Data\_Doc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1173">**Data\_Doc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1173">**Data\_Doc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1174">**Data\_Doc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1174">**Data\_Doc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1175">**Data\_Doc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1175">**Data\_Doc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1176">**Data\_Doc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1176">**Data\_Doc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1177">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1177">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1178">**Data\_Doc\_IsSyncBacked:bool** – чи відкривається документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1178">**Data\_Doc\_IsSyncBacked:bool -** verifies if document is being opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1179">**Data\_Doc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1179">**Data\_Doc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1180">**Data\_Doc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1180">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1181">**Data\_Doc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1181">**Data\_Doc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1182">**Data\_Doc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1182">**Data\_Doc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)-</span></span>

  - <span data-ttu-id="1bd6a-1183">**Data\_Doc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1183">**Data\_Doc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1184">**Data\_Doc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1184">**Data\_Doc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1185">**Data\_Doc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1185">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1186">**Data\_Doc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1186">**Data\_Doc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1187">**Data\_Doc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1187">**Data\_Doc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1188">**Data\_Doc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1188">**Data\_Doc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1189">**Data\_Doc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1189">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1190">**Data\_Doc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1190">**Data\_Doc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1191">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1191">Useful for correlating client-side and server-side log</span></span>

  - <span data-ttu-id="1bd6a-1192">**Data\_Doc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1192">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1193">**Data\_Doc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1193">**Data\_Doc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1194">**Data\_Doc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1194">**Data\_Doc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1195">**Data\_Doc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1195">**Data\_Doc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1196">**Data\_Doc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1196">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1197">**Data\_Doc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1197">**Data\_Doc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1198">**Data\_Doc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1198">**Data\_Doc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1199">**Data\_DocHasStorage:bool** – чи має цей документ локальне сховище?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1199">**Data\_DocHasStorage:bool -** Does this document have local storage?</span></span>

  - <span data-ttu-id="1bd6a-1200">**Data\_fLifeguarded:bool** – чи оброблявся документ функцією lifeguard (самостійне виправлення помилок документів без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1200">**Data\_fLifeguarded:bool -** Was document ever lifeguarded (feature to fix document errors by themselves without prompting user)?</span></span>

  - <span data-ttu-id="1bd6a-1201">**Data\_IsDocAutoSaveable:bool** – чи діє автозбереження презентації?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1201">**Data\_IsDocAutoSaveable:bool -** Is presentation auto savable?</span></span>

  - <span data-ttu-id="1bd6a-1202">**Data\_IsDocDirty:bool** – чи містить презентація ще не збережені зміни?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1202">**Data\_IsDocDirty:bool -** Does presentation have changes that are not yet saved?</span></span>

  - <span data-ttu-id="1bd6a-1203">**Data\_IsNewDoc:bool** – це новий документ або існуючий?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1203">**Data\_IsNewDoc:bool -** Is new document or existing</span></span>

  - <span data-ttu-id="1bd6a-1204">**Data\_IsRecoveredDoc:bool** – чи було відновлено документ?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1204">**Data\_IsRecoveredDoc:bool -** Is document recovered one?</span></span> <span data-ttu-id="1bd6a-1205">(Якщо попередній сеанс завершився аварійно, у наступному сеансі буде показано область відновлення документа)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1205">(If prior session crashed, we show document recovery pane on next session)</span></span>

  - <span data-ttu-id="1bd6a-1206">**Data\_NewDocDiscarded:bool** – чи було нову презентацію скасовано без збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1206">**Data\_NewDocDiscarded:bool -** Was new presentation discarded without being saved</span></span>

  - <span data-ttu-id="1bd6a-1207">**Data\_OCSClosingDlgCanceled:bool** – якщо, коли користувач закриває документ, передачу в OCS не завершено, користувачеві відображається запрошення почекати.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1207">**Data\_OCSClosingDlgCanceled:bool -** If upload is pending on OCS while user closes document, dialog is popped up to user to wait.</span></span> <span data-ttu-id="1bd6a-1208">Який варіант вибрав користувач?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1208">Which option user chose?</span></span>

  - <span data-ttu-id="1bd6a-1209">**Data\_OCSClosingDlgExpired:bool** – чи закрилося діалогове вікно самостійно (через 1 хвилину)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1209">**Data\_OCSClosingDlgExpired:bool -** Did dialog expire (after 1 minute) on its own?</span></span>

  - <span data-ttu-id="1bd6a-1210">**Data\_OCSClosingStatus:long** – який остаточний статус OCS (в CSI, можна закривати, у переході на OCS, у переході на CSI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1210">**Data\_OCSClosingStatus:long -** What’s final status of OCS (In CSI, Closable, In OCS Transition, In CSI transition, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1211">**Data\_OCSClosingWaitDurationMS:long** – скільки часу користувач мав чекати передавання від OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1211">**Data\_OCSClosingWaitDurationMS:long -** How much time user had to wait for OCS to upload</span></span>

  - <span data-ttu-id="1bd6a-1212">**Data\_OCSHandleTransitionResult:long** – попередньо визначений набір значень результату переходу, виконаного під час закриття (вже була спроба, продовження закриття тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1212">**Data\_OCSHandleTransitionResult:long -** Predefined set of values of result of transition performed during close (Already tried, continue to close, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1213">**Data\_ServerDocId:string** – GUID, що унікально ідентифікує документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1213">**Data\_ServerDocId:string -** GUID to uniquely identify a document</span></span>

  - <span data-ttu-id="1bd6a-1214">**Data\_StopwatchDuration:long** – загальний час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1214">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-1215">**Data\_UserContinuedZRTClose:bool** – коли під час закриття було відображено діалогове вікно, чи вибрав користувач варіант "Продовжити" для закриття?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1215">**Data\_UserContinuedZRTClose:bool -** Upon showing dialog on close, did user selected ‘Continue’ to close?</span></span>

#### <a name="officepowerpointdocoperationnewdocument"></a><span data-ttu-id="1bd6a-1216">Office.PowerPoint.DocOperation.NewDocument</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1216">Office.PowerPoint.DocOperation.NewDocument</span></span>

<span data-ttu-id="1bd6a-1217">Збирається під час створення презентації PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1217">Collected when PowerPoint creates a new presentation.</span></span><span data-ttu-id="1bd6a-1218"> Містить показники успіху/невдачі та продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1218"> Includes success failure and performance metrics.</span></span>

<span data-ttu-id="1bd6a-1219">Ці відомості використовуються як підтвердження можливості успішно створювати файли без зниження продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1219">This information is used to ensure we can create files successfully and with no degradation in performance.</span></span>

<span data-ttu-id="1bd6a-1220">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1220">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1221">**NewDocumentType** – створюється документ із шаблону або пустий документ?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1221">**NewDocumentType** – Whether new document is created from template or just created blank?</span></span>

  - <span data-ttu-id="1bd6a-1222">**FLifeguarded** – чи оброблено документ функцією lifeguard (відновлення стану пошкодженого документа без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1222">**FLifeguarded** – Is document life guarded (feature that restores corrupt document state without prompting user)</span></span>

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a><span data-ttu-id="1bd6a-1223">Office.PowerPoint.DocOperation.OpenCompleteProtocol</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1223">Office.PowerPoint.DocOperation.OpenCompleteProtocol</span></span>

<span data-ttu-id="1bd6a-1224">Збирається під час відкриття презентацій PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1224">Collected when PowerPoint opens presentations.</span></span> <span data-ttu-id="1bd6a-1225">Містить відомості, необхідні для належного дослідження та діагностування проблем, які виникають на прикінцевих етапах процесу відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1225">It contains the information needed to be able to properly investigate and diagnose issues that happen through the end stages of the open process.</span></span>

<span data-ttu-id="1bd6a-1226">Корпорація Майкрософт за допомогою цих даних підтверджує належну роботу функції та відсутність зниження продуктивності у процесі відкривання презентацій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1226">Microsoft uses this data to ensure the feature is working as expected and there is no degradation to opening presentations.</span></span>

<span data-ttu-id="1bd6a-1227">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1227">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1228">**Data\_AntiVirusScanMethod:long** – попередньо визначений набір значень типів сканування антивірусом (IOAV, AMSI, тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1228">**Data\_AntiVirusScanMethod:long -** Predefined set of values of type of AntiVirus scanned (IOAV, AMSI, None etc.)</span></span>

  - <span data-ttu-id="1bd6a-1229">**Data\_AntiVirusScanStatus:long** – попередньо визначений набір значень сканування антивірусом кожного документа (NoThreatsDetected, Failed, MalwareDetected тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1229">**Data\_AntiVirusScanStatus:long -** Predefined set of values of anti-virus scan that happens for every document opened (NoThreatsDetected, Failed, MalwareDetected etc.)</span></span>

  - <span data-ttu-id="1bd6a-1230">**Data\_CloseAndReopen:bool** – чи було цей документ закрито, а потім знову відкрито?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1230">**Data\_CloseAndReopen:bool -** Was this document closed and reopened?</span></span>

  - <span data-ttu-id="1bd6a-1231">**Data\_DetachedDuration:long** – час, протягом якого дія була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1231">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-1232">**Data\_Doc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1232">**Data\_Doc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1233">**Data\_Doc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1233">**Data\_Doc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1234">**Data\_Doc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1234">**Data\_Doc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1235">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1235">**Data\_Doc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1236">**Data\_Doc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1236">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1237">**Data\_Doc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1237">**Data\_Doc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1238">**Data\_Doc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1238">**Data\_Doc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1239">**Data\_Doc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1239">**Data\_Doc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1240">**Data\_Doc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1240">**Data\_Doc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1241">**Data\_Doc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1241">**Data\_Doc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1242">**Data\_Doc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1242">**Data\_Doc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1243">**Data\_Doc\_IOFlags:long –** бітова маска для різних позначок пов'язаних з IO для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1243">**Data\_Doc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1244">**Data\_Doc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1244">**Data\_Doc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1245">**Data\_Doc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1245">**Data\_Doc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1246">**Data\_Doc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1246">**Data\_Doc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1247">**Data\_Doc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1247">**Data\_Doc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1248">**Data\_Doc\_IsOpeningOfflineCopy:bool –** чи відкривається документ із локального кеша?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1248">**Data\_Doc\_IsOpeningOfflineCopy:bool -** Is document being opened from local cache?</span></span>

  - <span data-ttu-id="1bd6a-1249">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1249">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1250">**Data\_Doc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1250">**Data\_Doc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1251">**Data\_Doc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1251">**Data\_Doc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1252">**Data\_Doc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1252">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1253">**Data\_Doc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1253">**Data\_Doc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1254">**Data\_Doc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1254">**Data\_Doc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)-</span></span>

  - <span data-ttu-id="1bd6a-1255">**Data\_Doc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1255">**Data\_Doc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1256">**Data\_Doc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1256">**Data\_Doc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1257">**Data\_Doc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1257">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1258">**Data\_Doc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1258">**Data\_Doc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1259">**Data\_Doc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1259">**Data\_Doc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1260">**Data\_Doc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1260">**Data\_Doc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1261">**Data\_Doc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1261">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1262">**Data\_Doc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1262">**Data\_Doc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1263">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1263">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1264">**Data\_Doc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1264">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1265">**Data\_Doc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1265">**Data\_Doc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1266">**Data\_Doc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1266">**Data\_Doc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1267">**Data\_Doc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1267">**Data\_Doc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1268">**Data\_Doc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1268">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1269">**Data\_Doc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1269">**Data\_Doc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1270">**Data\_Doc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1270">**Data\_Doc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1271">**Data\_ExecutionCount:long** – скільки разів було виконано протокол IncOpen перед виконанням цього протоколу (OpenComplete)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1271">**Data\_ExecutionCount:long -** How many times we executed IncOpen protocol before executing this (OpenComplete) protocol</span></span>

  - <span data-ttu-id="1bd6a-1272">**Data\_FailureComponent:long** – попередньо визначений набір значень, які вказують на компонент, що став причиною помилки протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1272">**Data\_FailureComponent:long -** Predefined set of values of which component caused this protocol to fail?</span></span> <span data-ttu-id="1bd6a-1273">(Conflict, CSI, Internal тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1273">(Conflict, CSI, Internal etc.)</span></span>

  - <span data-ttu-id="1bd6a-1274">**Data\_FailureReason:long –** попередньо визначений набір значень причини помилки (FileIsCorrupt, BlockedByAntivirus тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1274">**Data\_FailureReason:long -** Predefined set of values of what’s the failure reason (FileIsCorrupt, BlockedByAntivirus etc.)</span></span>

  - <span data-ttu-id="1bd6a-1275">**Data_FullDownloadRoundTripCount:long** – кількість повторних звернень до сервера, необхідних для завантаження всього документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1275">**Data_FullDownloadRoundTripCount:long -** The number of roundtrips to the server taken to download the entire document.</span></span>
  
  - <span data-ttu-id="1bd6a-1276">**Data_IsProtocolRunInIncOpenMode:bool** – визначає, чи виконувався протокол інкрементного завантаження, тобто завантаження, у процесі якого частини документа завантажуються після їхнього початкового відображення користувачу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1276">**Data_IsProtocolRunInIncOpenMode:bool -** Was the protocol run for an incremental download, which is a download where parts of the document were downloaded after initially showing it to the user.</span></span>

  - <span data-ttu-id="1bd6a-1277">**Data\_MethodId:long** – який рядок коду виконувався останнім</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1277">**Data\_MethodId:long -** Internally which line of code was last one to be executed</span></span>

  - <span data-ttu-id="1bd6a-1278">**Data\_StopwatchDuration:long** – загальний час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1278">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-1279">**Data\_TimeToEdit:long** – час, потрібний для переведення документа в доступний для редагування стан</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1279">**Data\_TimeToEdit:long -** Time it took for document to become editable</span></span>

  - <span data-ttu-id="1bd6a-1280">**Data\_TimeToView:long** – час, потрібний для відображення першого слайда документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1280">**Data\_TimeToView:long -** Time it took for first slide of document to be rendered</span></span>

  - <span data-ttu-id="1bd6a-1281">**Data\_UnhandledException:bool** – чи є необроблений внутрішній виняток?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1281">**Data\_UnhandledException:bool -** Any unhandled native exception?</span></span>

#### <a name="officepowerpointdocoperationsave"></a><span data-ttu-id="1bd6a-1282">Office.PowerPoint.DocOperation.Save</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1282">Office.PowerPoint.DocOperation.Save</span></span>

<span data-ttu-id="1bd6a-1283">Збирається, коли PowerPoint виконує збереження з використанням сучасного шляху до коду.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1283">Collected whenever PowerPoint performs a save using the modern code path.</span></span> <span data-ttu-id="1bd6a-1284">Містить тип успішного або невдалого результату, показники продуктивності збереження та відповідні метадані документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1284">Includes success or failure result type of save performance metrics and relevant document metadata.</span></span> <span data-ttu-id="1bd6a-1285"> Помилки під час збереження можуть призвести до втрати даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1285"> Failures in save can result in data loss.</span></span> <span data-ttu-id="1bd6a-1286">Корпорація Майкрософт за допомогою цих даних підтверджує належну роботу функції та успішне збереження вмісту користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1286">Microsoft uses this data to ensure the feature is working as expected and user content is successfully being persisted.</span></span>

<span data-ttu-id="1bd6a-1287">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1287">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1288">**Data\_AddDocTelemetryResult:long** – чи є в цьому записі журналу вся необхідна телеметрія документа (поля Data\_Doc\_\*)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1288">**Data\_AddDocTelemetryResult:long -** Does this log entry have all necessary document telemetry (Data\_Doc\_\* fields)?</span></span> <span data-ttu-id="1bd6a-1289">Якщо ні, чому?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1289">If not, why?</span></span>

  - <span data-ttu-id="1bd6a-1290">**Data\_BeforeSaveEvent:long** – час, витрачений на створення події документа перед збереженням</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1290">**Data\_BeforeSaveEvent:long -** Time taken to raise Document Before Save Event</span></span>

  - <span data-ttu-id="1bd6a-1291">**Data\_CheckDownRevSaveTimeMS:long** – час, витрачений на перевірку виправлень</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1291">**Data\_CheckDownRevSaveTimeMS:long -** Time taken to check revision</span></span>

  - <span data-ttu-id="1bd6a-1292">**Data\_CheckMacroSaveTimeMS:long** – час, витрачений на збереження макросів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1292">**Data\_CheckMacroSaveTimeMS:long -** Time taken to save macros</span></span>

  - <span data-ttu-id="1bd6a-1293">**Data\_ClearAutoSaveTimeMS:long** – час, витрачений на зняття позначки автозбереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1293">**Data\_ClearAutoSaveTimeMS:long -** Time taken to clear AutoSave flag</span></span>

  - <span data-ttu-id="1bd6a-1294">**Data\_ClearDirtyFlagTimeMS:long** – час, витрачений на зняття позначки наявності змін у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1294">**Data\_ClearDirtyFlagTimeMS:long -** Time taken to clear document dirty flag</span></span>

  - <span data-ttu-id="1bd6a-1295">**Data\_CloneDocumentTimeMS:long** – час, витрачений на клонування документа перед початком збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1295">**Data\_CloneDocumentTimeMS:long -** Time taken to clone document before starting the save</span></span>

  - <span data-ttu-id="1bd6a-1296">**Data\_CommitTransactionTimeMS:long** – час, витрачений на затвердження транзакції збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1296">**Data\_CommitTransactionTimeMS:long -** Time taken to commit the save transaction</span></span>

  - <span data-ttu-id="1bd6a-1297">**Data\_CppUncaughtExceptionCount:long** – необроблені внутрішні винятки впродовж активності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1297">**Data\_CppUncaughtExceptionCount:long -** Uncaught native exceptions while activity was running</span></span>

  - <span data-ttu-id="1bd6a-1298">**Data\_DetachedDuration:long** – час, протягом якого дія була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1298">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-1299">**Data\_Doc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1299">**Data\_Doc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1300">**Data\_Doc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1300">**Data\_Doc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1301">**Data\_Doc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1301">**Data\_Doc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1302">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1302">**Data\_Doc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1303">**Data\_Doc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1303">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1304">**Data\_Doc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1304">**Data\_Doc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1305">**Data\_Doc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1305">**Data\_Doc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1306">**Data\_Doc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1306">**Data\_Doc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1307">**Data\_Doc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1307">**Data\_Doc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1308">**Data\_Doc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1308">**Data\_Doc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1309">**Data\_Doc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1309">**Data\_Doc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1310">**Data\_Doc\_IOFlags:long –** бітова маска для різних позначок пов'язаних з IO для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1310">**Data\_Doc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1311">**Data\_Doc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1311">**Data\_Doc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1312">**Data\_Doc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1312">**Data\_Doc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1313">**Data\_Doc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1313">**Data\_Doc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1314">**Data\_Doc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1314">**Data\_Doc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1315">**Data\_Doc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1315">**Data\_Doc\_IsOpeningOfflineCopy:bool -** verifies if document being is opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1316">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1316">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1317">**Data\_Doc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1317">**Data\_Doc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1318">**Data\_Doc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1318">**Data\_Doc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1319">**Data\_Doc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1319">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1320">**Data\_Doc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1320">**Data\_Doc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1321">**Data\_Doc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1321">**Data\_Doc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-1322">**Data\_Doc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1322">**Data\_Doc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1323">**Data\_Doc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1323">**Data\_Doc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1324">**Data\_Doc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1324">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1325">**Data\_Doc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1325">**Data\_Doc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1326">**Data\_Doc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1326">**Data\_Doc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1327">**Data\_Doc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1327">**Data\_Doc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1328">**Data\_Doc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1328">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1329">**Data\_Doc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1329">**Data\_Doc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1330">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1330">Useful for correlating client-side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1331">**Data\_Doc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1331">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1332">**Data\_Doc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1332">**Data\_Doc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1333">**Data\_Doc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1333">**Data\_Doc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1334">**Data\_Doc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1334">**Data\_Doc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1335">**Data\_Doc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1335">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1336">**Data\_Doc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1336">**Data\_Doc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1337">**Data\_Doc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1337">**Data\_Doc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1338">**Data\_DurationUAEOnSaveStartedMs:long** – час, витрачений на вихід із невідомої програми під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1338">**Data\_DurationUAEOnSaveStartedMs:long -** Time taken for Unknown App Exit during save</span></span>

  - <span data-ttu-id="1bd6a-1339">**Data\_EnsureSaveTransactionTimeMS:long** – час, необхідний для підтвердження створення успішної транзакції збереження, якщо її ще не існує</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1339">**Data\_EnsureSaveTransactionTimeMS:long -** Time taken to ensure save transaction is created if doesn’t exist already</span></span>

  - <span data-ttu-id="1bd6a-1340">**Data\_FailureComponent:long** – попередньо визначений набір значень, які вказують на компонент, що став причиною помилки протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1340">**Data\_FailureComponent:long-** Predefined set of values of which component caused this protocol to fail?</span></span> <span data-ttu-id="1bd6a-1341">(Conflict, CSI, Internal тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1341">(Conflict, CSI, Internal etc.)</span></span>

  - <span data-ttu-id="1bd6a-1342">**Data\_FailureReason:long** – попередньо визначений набір значень причини помилки (FileIsCorrupt, BlockedByAntivirus тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1342">**Data\_FailureReason:long -** Predefined set of values of what’s the failure reason (FileIsCorrupt, BlockedByAntivirus etc.)</span></span>

  - <span data-ttu-id="1bd6a-1343">**Data\_fLifeguarded:bool** – чи оброблявся документ функцією lifeguard (самостійне виправлення помилок документів без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1343">**Data\_fLifeguarded:bool -** Was document ever lifeguarded (feature to fix document errors by themselves without prompting user)?</span></span>

  - <span data-ttu-id="1bd6a-1344">**Data\_HandleEnsureContentType:long** – час, необхідний для підтвердження, що всі типи вмісту правильні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1344">**Data\_HandleEnsureContentType:long -** Time taken to ensure all the content types are correct</span></span>

  - <span data-ttu-id="1bd6a-1345">**Data\_HandleEnsureContentTypeTimeMS:long** – час, необхідний для підтвердження, що всі типи вмісту правильні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1345">**Data\_HandleEnsureContentTypeTimeMS:long -** Time taken to ensure all the content types are correct</span></span>

  - <span data-ttu-id="1bd6a-1346">**Data\_HasEmbeddedFont:bool** – чи містить цей документ вбудовані шрифти?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1346">**Data\_HasEmbeddedFont:bool -** Does this document have embedded fonts?</span></span>

  - <span data-ttu-id="1bd6a-1347">**Data\_InitializeSaveTimeMS:long** – час, витрачений на ініціалізацію вмісту документа, щоб почати збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1347">**Data\_InitializeSaveTimeMS:long -** Time taken to initialize document content to begin save</span></span>

  - <span data-ttu-id="1bd6a-1348">**Data\_InOCSTransition:bool** – чи виконується збереження для переходу до OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1348">**Data\_InOCSTransition:bool -** Is this save performed for transitioning to OCS</span></span>

  - <span data-ttu-id="1bd6a-1349">**Data\_IsSavingWithEmbeddedFont:bool** – чи містить цей документ вбудовані шрифти?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1349">**Data\_IsSavingWithEmbeddedFont:bool -** Does this document have embedded fonts?</span></span>

  - <span data-ttu-id="1bd6a-1350">**Data\_MethodId:long** – який рядок коду виконувався останнім</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1350">**Data\_MethodId:long -** Internally which line of code was last one to be executed</span></span>

  - <span data-ttu-id="1bd6a-1351">**Data\_PerformEmbedFontsTimeMS:long** – час, витрачений на серіалізацію вбудованих шрифтів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1351">**Data\_PerformEmbedFontsTimeMS:long -** Time taken to serialize embedded fonts</span></span>

  - <span data-ttu-id="1bd6a-1352">**Data\_PerformModernSaveTimeMS:long** – час, витрачений на виконання сучасного збереження (новий код)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1352">**Data\_PerformModernSaveTimeMS:long -** Time taken to perform modern save (new code)</span></span>

  - <span data-ttu-id="1bd6a-1353">**Data\_PerformPostSaveTimeMS:long** – час, витрачений на виконання функцій після збереження (сповіщення, скасування записів)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1353">**Data\_PerformPostSaveTimeMS:long -** Time taken to perform post save functions (notifications, undo entries)</span></span>

  - <span data-ttu-id="1bd6a-1354">**Data\_PrepareForSaveTimeMS:long** – час, витрачений, щоб почати збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1354">**Data\_PrepareForSaveTimeMS:long -** Time taken to start save</span></span>

  - <span data-ttu-id="1bd6a-1355">**Data\_RaiseDocumentBeforeSaveEventTimeMS:long** – час, витрачений на створення події BeforeSave</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1355">**Data\_RaiseDocumentBeforeSaveEventTimeMS:long -** Time taken to raise the BeforeSave event</span></span>

  - <span data-ttu-id="1bd6a-1356">**Data\_ReflectDocumentChangeTimeMS:long** – час, витрачений на відображення збережених змін в інтерфейсі користувача (повторне виведення ескізів тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1356">**Data\_ReflectDocumentChangeTimeMS:long -** Time taken to reflect saved changes to UI (repopulate thumbnails etc.)</span></span>

  - <span data-ttu-id="1bd6a-1357">**Data\_ReportStartTimeMS:long** – час, витрачений на завершення ініціалізації телеметрії для збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1357">**Data\_ReportStartTimeMS:long -** Time taken to finish initializing telemetry for save</span></span>

  - <span data-ttu-id="1bd6a-1358">**Data\_ReportSuccessTimeMS:long** – час, витрачений на завершення звітування про успішне збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1358">**Data\_ReportSuccessTimeMS:long -** Time taken to finish reporting successful save</span></span>

  - <span data-ttu-id="1bd6a-1359">**Data\_ResetDirtyFlagOnErrorTimeMS:long** – час, витрачений на скидання позначки наявності змін у документі в разі помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1359">**Data\_ResetDirtyFlagOnErrorTimeMS:long -** Time taken to reset document dirty flag on error</span></span>

  - <span data-ttu-id="1bd6a-1360">**Data\_SaveReason:long** – попередньо визначений набір значень причини цього збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1360">**Data\_SaveReason:long -** Predefined set of values of why this save was performed?</span></span> <span data-ttu-id="1bd6a-1361">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1361">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave etc.)</span></span>

  - <span data-ttu-id="1bd6a-1362">**Data\_SaveType:long** – попередньо визначений набір значень типу збереження (SaveAs, Publish, Manual, OMSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1362">**Data\_SaveType:long -** Predefined set of values of save type (SaveAs, Publish, Manual, OMSave etc.)</span></span>

  - <span data-ttu-id="1bd6a-1363">**Data\_SavingWithFont:bool** – чи зберігається документ із новими вбудованими шрифтами?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1363">**Data\_SavingWithFont:bool-** Are we saving document with new embedded fonts?</span></span>

  - <span data-ttu-id="1bd6a-1364">**Data\_ScrubClonedDocumentTimeMS:long** – час, витрачений на вилучення особистих відомостей із клонованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1364">**Data\_ScrubClonedDocumentTimeMS:long -** Time taken to remove personal information on cloned copy of document</span></span>

  - <span data-ttu-id="1bd6a-1365">**Data\_StopwatchDuration:long** – загальний час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1365">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-1366">**Data\_TransactionType:long** – чи це транзакція Save або MergeAndSave?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1366">**Data\_TransactionType:long -** Is it Save or MergeAndSave transaction?</span></span>

#### <a name="officepowerpointdocoperationsaveas"></a><span data-ttu-id="1bd6a-1367">Office.PowerPoint.DocOperation.SaveAs</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1367">Office.PowerPoint.DocOperation.SaveAs</span></span>

<span data-ttu-id="1bd6a-1368">Збирається, коли PowerPoint виконує дію "Зберегти як".</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1368">Collected whenever PowerPoint performs a Save As.</span></span> <span data-ttu-id="1bd6a-1369">Містить тип успішного або невдалого результату, показники продуктивності збереження та відповідні метадані документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1369">Includes success or failure result type of save performance metrics and relevant document metadata.</span></span> <span data-ttu-id="1bd6a-1370">Помилки під час збереження можуть призвести до втрати даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1370">Failures in save can result in data loss.</span></span>

<span data-ttu-id="1bd6a-1371">Корпорація Майкрософт за допомогою цих даних підтверджує належну роботу функції та успішне збереження вмісту користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1371">Microsoft uses this data to ensure the feature is working as expected and user content is successfully being persisted.</span></span>

<span data-ttu-id="1bd6a-1372">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1372">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1373">**Data\_AddDocTelemetryResult:long** – чи є в цьому записі журналу вся необхідна телеметрія документа (поля Data\_Doc\_\*)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1373">**Data\_AddDocTelemetryResult:long -** Does this log entry have all necessary document telemetry (Data\_Doc\_\* fields)?</span></span> <span data-ttu-id="1bd6a-1374">Якщо ні, чому?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1374">If not, why?</span></span>

  - <span data-ttu-id="1bd6a-1375">**Data\_CppUncaughtExceptionCount:long** – необроблені внутрішні винятки впродовж активності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1375">**Data\_CppUncaughtExceptionCount:long -** Uncaught native exceptions while activity was running</span></span>

  - <span data-ttu-id="1bd6a-1376">**Data\_DetachedDuration:long** – час, протягом якого дія була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1376">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-1377">**Data\_DstDoc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1377">**Data\_DstDoc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1378">**Data\_DstDoc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1378">**Data\_DstDoc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1379">**Data\_DstDoc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1379">**Data\_DstDoc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1380">**Data\_DstDoc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1380">**Data\_DstDoc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1381">**Data\_DstDoc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1381">**Data\_DstDoc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1382">**Data\_DstDoc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1382">**Data\_DstDoc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1383">**Data\_DstDoc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1383">**Data\_DstDoc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1384">**Data\_DstDoc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1384">**Data\_DstDoc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1385">**Data\_DstDoc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1385">**Data\_DstDoc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1386">**Data\_DstDoc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1386">**Data\_DstDoc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1387">**Data\_DstDoc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1387">**Data\_DstDoc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1388">**Data\_DstDoc\_IOFlags:long** – бітова маска для різних позначок, пов’язаних із вводом/виводом для цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1388">**Data\_DstDoc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1389">**Data\_DstDoc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1389">**Data\_DstDoc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1390">**Data\_DstDoc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1390">**Data\_DstDoc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1391">**Data\_DstDoc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1391">**Data\_DstDoc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1392">**Data\_DstDoc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1392">**Data\_DstDoc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1393">**Data\_DstDoc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1393">**Data\_DstDoc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1394">**Data\_DstDoc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1394">**Data\_DstDoc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1395">**Data\_DstDoc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1395">**Data\_DstDoc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1396">**Data\_DstDoc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1396">**Data\_DstDoc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1397">**Data\_DstDoc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1397">**Data\_DstDoc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1398">**Data\_DstDoc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1398">**Data\_DstDoc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-1399">**Data\_DstDoc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1399">**Data\_DstDoc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1400">**Data\_DstDoc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1400">**Data\_DstDoc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1401">**Data\_DstDoc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1401">**Data\_DstDoc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1402">**Data\_DstDoc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1402">**Data\_DstDoc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1403">**Data\_DstDoc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1403">**Data\_DstDoc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1404">**Data\_DstDoc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1404">**Data\_DstDoc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1405">**Data\_DstDoc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1405">**Data\_DstDoc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1406">**Data\_DstDoc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1406">**Data\_DstDoc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1407">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1407">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1408">**Data\_DstDoc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1408">**Data\_DstDoc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1409">**Data\_DstDoc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1409">**Data\_DstDoc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1410">**Data\_DstDoc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1410">**Data\_DstDoc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1411">**Data\_DstDoc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1411">**Data\_DstDoc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1412">**Data\_DstDoc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1412">**Data\_DstDoc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1413">**Data\_DstDoc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1413">**Data\_DstDoc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1414">**Data\_DstDoc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1414">**Data\_DstDoc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1415">**Data\_FileType:long** – попередньо визначений набір значень внутрішнього типу файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1415">**Data\_FileType:long -** Predefined set of values of internal type of file</span></span>

  - <span data-ttu-id="1bd6a-1416">**Data\_fLifeguarded:bool** – чи оброблявся документ функцією lifeguard (самостійне виправлення помилок документів без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1416">**Data\_fLifeguarded:bool -** Was document ever lifeguarded (feature to fix document errors by themselves without prompting user)?</span></span>

  - <span data-ttu-id="1bd6a-1417">**Data\_FWebCreated:bool** – чи має документ позначку WebCreator?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1417">**Data\_FWebCreated:bool -** Does this document have WebCreator flag?</span></span>

  - <span data-ttu-id="1bd6a-1418">**Data\_SaveReason:long** – попередньо визначений набір значень причини цього збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1418">**Data\_SaveReason:long -** Predefined set of values of why this save was performed?</span></span> <span data-ttu-id="1bd6a-1419">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1419">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1420">**Data\_SaveType:long** – попередньо визначений набір значень типу збереження (SaveAs, Publish, Manual, OMSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1420">**Data\_SaveType:long -** Predefined set of values of save type (SaveAs, Publish, Manual, OMSave, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1421">**Data\_SrcDoc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1421">**Data\_SrcDoc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1422">**Data\_SrcDoc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1422">**Data\_SrcDoc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1423">**Data\_SrcDoc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1423">**Data\_SrcDoc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1424">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1424">**Data\_SrcDoc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1425">**Data\_SrcDoc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1425">**Data\_SrcDoc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1426">**Data\_SrcDoc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1426">**Data\_SrcDoc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1427">**Data\_SrcDoc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1427">**Data\_SrcDoc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1428">**Data\_SrcDoc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1428">**Data\_SrcDoc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1429">**Data\_SrcDoc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1429">**Data\_SrcDoc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1430">**Data\_SrcDoc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1430">**Data\_SrcDoc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1431">**Data\_SrcDoc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1431">**Data\_SrcDoc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1432">**Data\_SrcDoc\_IOFlags:long** – бітова маска для різних позначок, пов’язаних із вводом/виводом для цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1432">**Data\_SrcDoc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1433">**Data\_SrcDoc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1433">**Data\_SrcDoc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1434">**Data\_SrcDoc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1434">**Data\_SrcDoc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1435">**Data\_SrcDoc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1435">**Data\_SrcDoc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1436">**Data\_SrcDoc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1436">**Data\_SrcDoc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1437">**Data\_SrcDoc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1437">**Data\_SrcDoc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1438">**Data\_SrcDoc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1438">**Data\_SrcDoc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1439">**Data\_SrcDoc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1439">**Data\_SrcDoc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1440">**Data\_SrcDoc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1440">**Data\_SrcDoc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1441">**Data\_SrcDoc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1441">**Data\_SrcDoc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1442">**Data\_SrcDoc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1442">**Data\_SrcDoc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)-</span></span>

  - <span data-ttu-id="1bd6a-1443">**Data\_SrcDoc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1443">**Data\_SrcDoc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1444">**Data\_SrcDoc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1444">**Data\_SrcDoc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1445">**Data\_SrcDoc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1445">**Data\_SrcDoc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1446">**Data\_SrcDoc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1446">**Data\_SrcDoc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1447">**Data\_SrcDoc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1447">**Data\_SrcDoc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1448">**Data\_SrcDoc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16 Data\_SrcDoc\_SessionId:long – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1448">**Data\_SrcDoc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16Data\_SrcDoc\_SessionId:long generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1449">**Data\_SrcDoc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1449">**Data\_SrcDoc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1450">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1450">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1451">**Data\_SrcDoc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1451">**Data\_SrcDoc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1452">**Data\_SrcDoc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1452">**Data\_SrcDoc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1453">**Data\_SrcDoc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1453">**Data\_SrcDoc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1454">**Data\_SrcDoc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1454">**Data\_SrcDoc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1455">**Data\_SrcDoc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1455">**Data\_SrcDoc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1456">**Data\_SrcDoc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1456">**Data\_SrcDoc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1457">**Data\_SrcDoc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1457">**Data\_SrcDoc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1458">**Data\_StopwatchDuration:long** – загальний час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1458">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-1459">**Data\_TypeOfSaveDialog:long** – попередньо визначений набір значень діалогового вікна (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1459">**Data\_TypeOfSaveDialog:long -** Predefined set of values of Dialog (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG etc.)</span></span>

  - <span data-ttu-id="1bd6a-1460">**DstDoc** – нове розташування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1460">**DstDoc -** New location of document</span></span>

  - <span data-ttu-id="1bd6a-1461">**SrcDoc** – початкове розташування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1461">**SrcDoc -** Original location of document</span></span>

#### <a name="officepowerpointdocoperationsavelegacy"></a><span data-ttu-id="1bd6a-1462">Office.PowerPoint.DocOperation.SaveLegacy</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1462">Office.PowerPoint.DocOperation.SaveLegacy</span></span>

<span data-ttu-id="1bd6a-1463">Збирається, коли PowerPoint виконує збереження з використанням застарілого шляху до коду.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1463">Collected whenever PowerPoint performs a save using the legacy code path.</span></span> <span data-ttu-id="1bd6a-1464">Містить тип успішного або невдалого результату, показники продуктивності збереження та відповідні метадані документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1464">Includes success or failure result type of save performance metrics and relevant document metadata.</span></span> <span data-ttu-id="1bd6a-1465">Помилки під час збереження можуть призвести до втрати даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1465">Failures in save can result in data loss.</span></span> <span data-ttu-id="1bd6a-1466">Корпорація Майкрософт за допомогою цих даних підтверджує належну роботу функції та успішне збереження вмісту користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1466">Microsoft uses this data to ensure the feature is working as expected and user content is successfully being persisted.</span></span>

<span data-ttu-id="1bd6a-1467">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1467">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1468">**Data\_AddDocTelemetryResult:long** – чи є в цьому записі журналу вся необхідна телеметрія документа (поля Data\_Doc\_\*)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1468">**Data\_AddDocTelemetryResult:long -** Does this log entry have all necessary document telemetry (Data\_Doc\_\* fields)?</span></span> <span data-ttu-id="1bd6a-1469">Якщо ні, чому?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1469">If not, why?</span></span>

  - <span data-ttu-id="1bd6a-1470">**Data\_CppUncaughtExceptionCount:long** – необроблені внутрішні винятки впродовж активності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1470">**Data\_CppUncaughtExceptionCount:long -** Uncaught native exceptions while activity was running</span></span>

  - <span data-ttu-id="1bd6a-1471">**Data\_DetachedDuration:long** – час, протягом якого дія була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1471">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-1472">**Data\_Doc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1472">**Data\_Doc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1473">**Data\_Doc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1473">**Data\_Doc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1474">**Data\_Doc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1474">**Data\_Doc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1475">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1475">**Data\_Doc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1476">**Data\_Doc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1476">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1477">**Data\_Doc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1477">**Data\_Doc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1478">**Data\_Doc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1478">**Data\_Doc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1479">**Data\_Doc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1479">**Data\_Doc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1480">**Data\_Doc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1480">**Data\_Doc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1481">**Data\_Doc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1481">**Data\_Doc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1482">**Data\_Doc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1482">**Data\_Doc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1483">**Data\_Doc\_IOFlags:long –** бітова маска для різних позначок пов'язаних з IO для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1483">**Data\_Doc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1484">**Data\_Doc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1484">**Data\_Doc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1485">**Data\_Doc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1485">**Data\_Doc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1486">**Data\_Doc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1486">**Data\_Doc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1487">**Data\_Doc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1487">**Data\_Doc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1488">**Data\_Doc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1488">**Data\_Doc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1489">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1489">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1490">**Data\_Doc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1490">**Data\_Doc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1491">**Data\_Doc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1491">**Data\_Doc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1492">**Data\_Doc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1492">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1493">**Data\_Doc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1493">**Data\_Doc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1494">**Data\_Doc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1494">**Data\_Doc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-1495">**Data\_Doc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1495">**Data\_Doc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1496">**Data\_Doc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1496">**Data\_Doc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1497">**Data\_Doc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1497">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1498">**Data\_Doc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1498">**Data\_Doc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1499">**Data\_Doc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1499">**Data\_Doc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1500">**Data\_Doc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1500">**Data\_Doc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1501">**Data\_Doc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1501">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1502">**Data\_Doc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1502">**Data\_Doc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1503">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1503">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1504">**Data\_Doc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1504">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1505">**Data\_Doc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1505">**Data\_Doc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1506">**Data\_Doc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1506">**Data\_Doc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1507">**Data\_Doc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1507">**Data\_Doc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1508">**Data\_Doc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1508">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1509">**Data\_Doc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1509">**Data\_Doc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1510">**Data\_Doc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1510">**Data\_Doc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1511">**Data\_DstDoc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1511">**Data\_DstDoc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1512">**Data\_DstDoc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1512">**Data\_DstDoc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1513">**Data\_DstDoc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1513">**Data\_DstDoc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1514">**Data\_DstDoc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1514">**Data\_DstDoc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1515">**Data\_DstDoc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1515">**Data\_DstDoc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1516">**Data\_DstDoc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1516">**Data\_DstDoc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1517">**Data\_DstDoc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1517">**Data\_DstDoc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1518">**Data\_DstDoc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1518">**Data\_DstDoc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1519">**Data\_DstDoc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1519">**Data\_DstDoc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1520">**Data\_DstDoc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1520">**Data\_DstDoc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1521">**Data\_DstDoc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1521">**Data\_DstDoc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1522">**Data\_DstDoc\_IOFlags:long** – бітова маска для різних позначок, пов’язаних із вводом/виводом для цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1522">**Data\_DstDoc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1523">**Data\_DstDoc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1523">**Data\_DstDoc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1524">**Data\_DstDoc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1524">**Data\_DstDoc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1525">**Data\_DstDoc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1525">**Data\_DstDoc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1526">**Data\_DstDoc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1526">**Data\_DstDoc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1527">**Data\_DstDoc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1527">**Data\_DstDoc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1528">**Data\_DstDoc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1528">**Data\_DstDoc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1529">**Data\_DstDoc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1529">**Data\_DstDoc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1530">**Data\_DstDoc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1530">**Data\_DstDoc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures etc.)</span></span>

  - <span data-ttu-id="1bd6a-1531">**Data\_DstDoc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1531">**Data\_DstDoc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1532">**Data\_DstDoc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1532">**Data\_DstDoc\_PasswordFlags:long-** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-1533">**Data\_DstDoc\_ReadOnlyReasons:long** – попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1533">**Data\_DstDoc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1534">**Data\_DstDoc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1534">**Data\_DstDoc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1535">**Data\_DstDoc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1535">**Data\_DstDoc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1536">**Data\_DstDoc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1536">**Data\_DstDoc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1537">**Data\_DstDoc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1537">**Data\_DstDoc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1538">**Data\_DstDoc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1538">**Data\_DstDoc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1539">**Data\_DstDoc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1539">**Data\_DstDoc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1540">**Data\_DstDoc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1540">**Data\_DstDoc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1541">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1541">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1542">**Data\_DstDoc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1542">**Data\_DstDoc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1543">**Data\_DstDoc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1543">**Data\_DstDoc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1544">**Data\_DstDoc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1544">**Data\_DstDoc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1545">**Data\_DstDoc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1545">**Data\_DstDoc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1546">**Data\_DstDoc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1546">**Data\_DstDoc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1547">**Data\_DstDoc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1547">**Data\_DstDoc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1548">**Data\_DstDoc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1548">**Data\_DstDoc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1549">**Data\_FileType:long** – попередньо визначений набір значень внутрішнього типу файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1549">**Data\_FileType:long -** Predefined set of values of internal type of file</span></span>

  - <span data-ttu-id="1bd6a-1550">**Data\_fLifeguarded:bool** – чи оброблявся документ функцією lifeguard (самостійне виправлення помилок документів без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1550">**Data\_fLifeguarded:bool -** Was document ever lifeguarded (feature to fix document errors by themselves without prompting user)?</span></span>

  - <span data-ttu-id="1bd6a-1551">**Data\_SaveReason:long** – попередньо визначений набір значень причини цього збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1551">**Data\_SaveReason:long -** Predefined set of values of why this save was performed?</span></span> <span data-ttu-id="1bd6a-1552">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1552">(AutoSave, ToOCSTransitionSave, ToCSITransitionSave etc.)</span></span>

  - <span data-ttu-id="1bd6a-1553">**Data\_SaveType:long** – попередньо визначений набір значень типу збереження (SaveAs, Publish, Manual, OMSave тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1553">**Data\_SaveType:long -** Predefined set of values of save type (SaveAs, Publish, Manual, OMSave etc.)</span></span>

  - <span data-ttu-id="1bd6a-1554">**Data\_SrcDoc\_AccessMode:long** – як було відкрито цей документ (лише для читання | читання та записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1554">**Data\_SrcDoc\_AccessMode:long -** How was this document opened (Read only | read write)</span></span>

  - <span data-ttu-id="1bd6a-1555">**Data\_SrcDoc\_AssistedReadingReasons:long** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1555">**Data\_SrcDoc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1556">**Data\_SrcDoc\_ChunkingType:long** – як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1556">**Data\_SrcDoc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-1557">**Data\_Doc\_EdpState:long** – стан захисту корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1557">**Data\_SrcDoc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-1558">**Data\_SrcDoc\_Ext:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1558">**Data\_SrcDoc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1559">**Data\_SrcDoc\_Extension:string** – розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1559">**Data\_SrcDoc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-1560">**Data\_SrcDoc\_FileFormat:long** – попередньо визначений набір значень формату файлу (детальніший, ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1560">**Data\_SrcDoc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-1561">**Data\_SrcDoc\_Fqdn:string** – місце збереження документа (SharePoint.com, live.net), тільки для доменів Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1561">**Data\_SrcDoc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-1562">**Data\_SrcDoc\_FqdnHash:string** – геш-код місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1562">**Data\_SrcDoc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-1563">**Data\_SrcDoc\_IdentityTelemetryId:string** – унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1563">**Data\_SrcDoc\_IdentityTelemetryId:string -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-1564">**Data\_SrcDoc\_IdentityUniqueId:string** – унікальний ідентифікатор ідентичності, який було використано для дії зі спільними документами</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1564">**Data\_SrcDoc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-1565">**Data\_SrcDoc\_IOFlags:long** – бітова маска для різних позначок, пов’язаних із вводом/виводом для цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1565">**Data\_SrcDoc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-1566">**Data\_SrcDoc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1566">**Data\_SrcDoc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-1567">**Data\_SrcDoc\_IsCloudCollabEnabled:bool** – має значення True, якщо HTTP-заголовок IsCloudCollabEnabled уже було отримано з запиту OPTIONS.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1567">**Data\_SrcDoc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-1568">**Data\_SrcDoc\_IsIncrementalOpen:bool** – чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1568">**Data\_SrcDoc\_IsIncrementalOpen:bool -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-1569">**Data\_SrcDoc\_IsOcsSupported:bool** – чи підтримує документ співавторство з використанням нової служби OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1569">**Data\_SrcDoc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-1570">**Data\_SrcDoc\_IsOpeningOfflineCopy:bool** – чи відкривається документ із локального кеша</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1570">**Data\_SrcDoc\_IsOpeningOfflineCopy:bool -** verifies if document is being opened from local cache</span></span>

  - <span data-ttu-id="1bd6a-1571">**Data\_SrcDoc\_IsSyncBacked:bool** – чи відкрито документ із папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1571">**Data\_SrcDoc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-1572">**Data\_SrcDoc\_Location:long** – попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1572">**Data\_SrcDoc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-1573">**Data\_SrcDoc\_LocationDetails:long** – попередньо визначений набір значень більш детального розташування (папка Temp, папка "Завантаження", One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1573">**Data\_SrcDoc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1574">**Data\_SrcDoc\_NumberCoAuthors:long** – кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1574">**Data\_SrcDoc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-1575">**Data\_SrcDoc\_PasswordFlags:long** – попередньо визначений набір значень шифрування документа паролем (жодного, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1575">**Data\_SrcDoc\_PasswordFlags:long-** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-1576">**Data\_SrcDoc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини, з якої документ позначено як доступний лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1576">**Data\_SrcDoc\_ReadOnlyReasons:long -** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit, etc.)</span></span>

  - <span data-ttu-id="1bd6a-1577">**Data\_SrcDoc\_ResourceIdHash:string** – геш-код ідентифікатора ресурсів для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1577">**Data\_SrcDoc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1578">**Data\_SrcDoc\_ServerDocId:string** – незмінний ідентифікатор для документів, збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1578">**Data\_SrcDoc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1579">**Data\_SrcDoc\_ServerProtocol:long** – попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1579">**Data\_SrcDoc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1580">**Data\_SrcDoc\_ServerType:long** – попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1580">**Data\_SrcDoc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-1581">**Data\_SrcDoc\_ServerVersion:long** – версія сервера: Office14, Office15 або Office16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1581">**Data\_SrcDoc\_ServerVersion:long -** verifies if server is based off Office14, Office15 or Office 16</span></span>

  - <span data-ttu-id="1bd6a-1582">**Data\_SrcDoc\_SessionId:long** – згенерований GUID, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1582">**Data\_SrcDoc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-1583">**Data\_SrcDoc\_SharePointServiceContext:string** – непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1583">**Data\_SrcDoc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-1584">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1584">Useful for correlating client side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-1585">**Data\_SrcDoc\_SizeInBytes:long** – розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1585">**Data\_SrcDoc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-1586">**Data\_SrcDoc\_SpecialChars:long** – бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1586">**Data\_SrcDoc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1587">**Data\_SrcDoc\_StorageProviderId:string** – рядок, що визначає постачальника зберігання документа, наприклад "DropBox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1587">**Data\_SrcDoc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox"</span></span>

  - <span data-ttu-id="1bd6a-1588">**Data\_SrcDoc\_StreamAvailability:long** – попередньо визначений набір значень стану потоку документів (доступний, постійно вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1588">**Data\_SrcDoc\_StreamAvailability:long -** Predefined set of values of status of document Stream(available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-1589">**Data\_SrcDoc\_UrlHash:string** – геш-код повної URL-адреси документа, збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1589">**Data\_SrcDoc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-1590">**Data\_SrcDoc\_UsedWrsDataOnOpen:bool** – має значення true, якщо файл відкривався інкрементно з використанням попередньо кешованих даних WRS із хоста</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1590">**Data\_SrcDoc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-1591">**Data\_SrcDoc\_WopiServiceId:string** – ідентифікатор служби WOPI, наприклад "Dropbox"</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1591">**Data\_SrcDoc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-1592">**Data\_StopwatchDuration:long** – загальний час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1592">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-1593">**Data\_TypeOfSaveDialog:long** – попередньо визначений набір значень діалогового вікна (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1593">**Data\_TypeOfSaveDialog:long -** Predefined set of values of Dialog (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG etc.)</span></span>

  - <span data-ttu-id="1bd6a-1594">**Doc** – поточний документ для збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1594">**Doc -** current document for Save</span></span>

  - <span data-ttu-id="1bd6a-1595">**DstDoc** – нове розташування документа (у випадку "Зберегти як")</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1595">**DstDoc -** New location of document (in case of SaveAs)</span></span>

  - <span data-ttu-id="1bd6a-1596">**SrcDoc** – початкове розташування документа (у випадку "Зберегти як")</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1596">**SrcDoc -** Original location of document (in case of SaveAs)</span></span>

#### <a name="officepowerpointpptsharedslideshowfailure"></a><span data-ttu-id="1bd6a-1597">Office.PowerPoint.PPT.Shared.SlideShow.Failure</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1597">Office.PowerPoint.PPT.Shared.SlideShow.Failure</span></span>

<span data-ttu-id="1bd6a-1598">Збирання помилок під час показу слайдів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1598">Collecting failures during slide show.</span></span> <span data-ttu-id="1bd6a-1599">Показ слайдів – це ключова функція програми PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1599">Slide show is a key feature for PowerPoint.</span></span> <span data-ttu-id="1bd6a-1600">Корпорація Майкрософт збирає дані, коли під час показу слайдів трапляється помилка, з метою підвищення зручності для користувача у процесі показу слайдів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1600">Microsoft is collecting when error happens during slide show to help improve user experience on slide show.</span></span> <span data-ttu-id="1bd6a-1601">Ці дані використовуються в корпорації Майкрософт для отримання діагностичної інформації про місце виникнення помилки під час показу слайдів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1601">Microsoft uses this data to get diagnostic information about where the error happens while user is using slide show</span></span>

<span data-ttu-id="1bd6a-1602">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1602">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1603">**CountSlideShowErrors** – загальна кількість помилок показу слайдів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1603">**CountSlideShowErrors** - total number of slide show errors</span></span>

  - <span data-ttu-id="1bd6a-1604">**CountPPTErrors** – загальна кількість помилок PPT</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1604">**CountPPTErrors** - total number of PPT errors</span></span>

  - <span data-ttu-id="1bd6a-1605">**CountOArtErrors** – загальна кількість помилок OArt</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1605">**CountOArtErrors** - total number of OArt errors</span></span>

  - <span data-ttu-id="1bd6a-1606">**CountOtherErrors** – загальна кількість інших помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1606">**CountOtherErrors** - total number of other errors</span></span>

  - <span data-ttu-id="1bd6a-1607">**FirstSlideShowError** – перша помилка під час показу слайдів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1607">**FirstSlideShowError** - first error happened in slide show</span></span>

  - <span data-ttu-id="1bd6a-1608">**FirstOArtError** – перша помилка в OArt</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1608">**FirstOArtError** - first error happened in OArt</span></span>

  - <span data-ttu-id="1bd6a-1609">**FirstPPTError** – перша помилка в PPT</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1609">**FirstPPTError** - first error happened in PPT</span></span>

  - <span data-ttu-id="1bd6a-1610">**FirstOtherError** – перша помилка в іншій області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1610">**FirstOtherError** - first error happened in other area</span></span>

#### <a name="officeprojectprojectfilesave"></a><span data-ttu-id="1bd6a-1611">Office.Project.ProjectFileSave</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1611">Office.Project.ProjectFileSave</span></span>

<span data-ttu-id="1bd6a-1612">Програма Project зберігає файл.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1612">Project saves a file.</span></span> <span data-ttu-id="1bd6a-1613">Ця подія вказує на операцію збереження в Project.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1613">This event indicates a Project save.</span></span> <span data-ttu-id="1bd6a-1614">Це дає корпорації Майкрософт змогу вимірювати успішність збереження файлу в Project, що важливо, щоб уникнути втрати даних документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1614">It allows Microsoft to measure success of Project saving a file which is important to avoid document data loss.</span></span>

<span data-ttu-id="1bd6a-1615">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1615">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1616">**Data\_TriggerTime** – час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1616">**Data\_TriggerTime** - time of save</span></span>

  - <span data-ttu-id="1bd6a-1617">**Data\_FileType** – тип файлу, в якому зберігається проект</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1617">**Data\_FileType** - type of file the project is being saved as</span></span>
 
#### <a name="officesessionactivitystart"></a><span data-ttu-id="1bd6a-1618">Office.Session.Activity.Start</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1618">Office.Session.Activity.Start</span></span>

<span data-ttu-id="1bd6a-1619">Повідомляє, коли почався сеанс транслятора даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1619">Allows us to know when a data streamer session has started.</span></span>  <span data-ttu-id="1bd6a-1620">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1620">Used for feature health and monitoring.</span></span> <span data-ttu-id="1bd6a-1621">Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1621">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-1622">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1622">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-1623">**Activity_Name** – ім’я дії “Session”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1623">**Activity_Name** - Name of the activity “Session”</span></span>

- <span data-ttu-id="1bd6a-1624">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1624">**Activity_CV** - ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-1625">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1625">**Activity_StartStopType** - Start</span></span>

- <span data-ttu-id="1bd6a-1626">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1626">**Activity_DateTimeTicks** - Data Time for the activity</span></span>

#### <a name="officesessionactivitystop"></a><span data-ttu-id="1bd6a-1627">Office.Session.Activity.Stop</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1627">Office.Session.Activity.Stop</span></span>

<span data-ttu-id="1bd6a-1628">Повідомляє, коли закінчився сеанс транслятора даних. Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1628">Allows us to know when a data streamer session has stopped Used for feature health and monitoring.</span></span> <span data-ttu-id="1bd6a-1629">Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1629">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-1630">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1630">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-1631">**Activity_Name** – ім’я дії “Session”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1631">**Activity_Name** - Name of the activity “Session”</span></span>

- <span data-ttu-id="1bd6a-1632">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1632">**Activity_CV** - ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-1633">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1633">**Activity_StartStopType** - Stop</span></span>

- <span data-ttu-id="1bd6a-1634">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1634">**Activity_DateTimeTicks** - Data Time for the activity</span></span>

#### <a name="officestreamdeviceactivitystart"></a><span data-ttu-id="1bd6a-1635">Office.StreamDevice.Activity.Start</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1635">Office.StreamDevice.Activity.Start</span></span>

<span data-ttu-id="1bd6a-1636">Повідомляє, чи успішно почалася трансляція джерела даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1636">Allows us to know if start streaming data source is successful.</span></span>   <span data-ttu-id="1bd6a-1637">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1637">Used for feature health and monitoring.</span></span> <span data-ttu-id="1bd6a-1638">Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1638">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-1639">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1639">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-1640">**Datasource_Type** – відомості про пристрій або службу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1640">**Datasource_Type** - Serial device, or App Service information</span></span>

- <span data-ttu-id="1bd6a-1641">**DataSource_Name** – ім’я підключеного джерела даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1641">**DataSource_Name** - Name of connected data source</span></span>

- <span data-ttu-id="1bd6a-1642">**Activity_Name** – назва дії “StreamDeviceData” або “StreamFileData”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1642">**Activity_Name** - Name of the activity “StreamDeviceData” or “StreamFileData”</span></span>

- <span data-ttu-id="1bd6a-1643">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1643">**Activity_CV** - ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-1644">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1644">**Activity_StartStopType** - Start</span></span>

- <span data-ttu-id="1bd6a-1645">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1645">**Activity_DateTimeTicks** - Data Time for the activity</span></span>

#### <a name="officestreamdeviceactivitystop"></a><span data-ttu-id="1bd6a-1646">Office.StreamDevice.Activity.Stop</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1646">Office.StreamDevice.Activity.Stop</span></span>

<span data-ttu-id="1bd6a-1647">Повідомляє, чи успішно закінчилася трансляція джерела даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1647">Allows us to know if stop streaming data source is successful.</span></span>   <span data-ttu-id="1bd6a-1648">Використовується для дослідження справності та моніторингу функцій.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1648">Used for feature health and monitoring.</span></span> <span data-ttu-id="1bd6a-1649">Ця подія генерується службою Транслятора даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1649">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-1650">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1650">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-1651">**Datasource_Type** – відомості про пристрій або службу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1651">**Datasource_Type** - Serial device, or App Service information</span></span>

- <span data-ttu-id="1bd6a-1652">**DataSource_Name** – ім’я підключеного джерела даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1652">**DataSource_Name** - Name of connected data source</span></span>

- <span data-ttu-id="1bd6a-1653">**Activity_Name** – назва дії “StreamDeviceData” або “StreamFileData”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1653">**Activity_Name** - Name of the activity “StreamDeviceData” or “StreamFileData”</span></span>

- <span data-ttu-id="1bd6a-1654">**Activity_CV** – ідентифікатор для зіставлення події протягом сеансу підключення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1654">**Activity_CV** - ID to correlate the events across the connection session</span></span>

- <span data-ttu-id="1bd6a-1655">**Activity_StartStopType** – початок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1655">**Activity_StartStopType** - Stop</span></span>

- <span data-ttu-id="1bd6a-1656">**Activity_DateTimeTicks** – дата й час дії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1656">**Activity_DateTimeTicks** - Data Time for the activity</span></span>

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a><span data-ttu-id="1bd6a-1657">Office.TargetedMessaging.ABExperimentMessageTrigger</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1657">Office.TargetedMessaging.ABExperimentMessageTrigger</span></span>

<span data-ttu-id="1bd6a-1658">Відстежує кількість користувачів, які отримують повідомлення BizBar та Dynamic Canvas із TargetedMessagingService (ТМС).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1658">Tracks the number of users receiving BizBar and Dynamic Canvas messages from TargetedMessagingService (TMS).</span></span> <span data-ttu-id="1bd6a-1659">Ці дані критично важливі для розуміння, які повідомлення отримують користувачі та на якій поверхні, щоб можна було гарантувати, що не пропущено жодне з повідомлень, які можуть бути важливі для подальшого використання продукту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1659">This data is critical to understand what messages users are getting and on what surface so that we can ensure they are not missing any messages that may be critical to their continued use of the product.</span></span> <span data-ttu-id="1bd6a-1660">Крім того, вони потрібні для точного вимірювання успішності наших експериментів і кампаній, які проводяться через ТМС.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1660">Also needed to accurately measure the success of our experiments and campaigns run through TMS.</span></span>

<span data-ttu-id="1bd6a-1661">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1661">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1662">**Data\_Surface** – ім’я поверхні, для якої призначалося повідомлення, доставлене службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1662">**Data\_Surface** – Name of the surface that this service delivered message is meant for</span></span>

  - <span data-ttu-id="1bd6a-1663">**Data\_Flight** – ідентифікатор тесту ECS/CT, який було використано для доставлення цього повідомлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1663">**Data\_Flight** – ECS/CT Flight identifier that was used to deliver this message</span></span>

  - <span data-ttu-id="1bd6a-1664">**Data\_CampaignId** – ідентифікатор кампанії, до якої належить це повідомлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1664">**Data\_CampaignId** – identifier of the campaign that this message is part of</span></span>

  - <span data-ttu-id="1bd6a-1665">**Data\_MessageId** – ідентифікатор цього повідомлення, доставленого службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1665">**Data\_MessageId** – identifier of this service delivered message</span></span>

  - <span data-ttu-id="1bd6a-1666">**Data\_TransactionId** – ідентифікатор цієї транзакції зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1666">**Data\_TransactionId** – identifier of this transaction with the service</span></span>

  - <span data-ttu-id="1bd6a-1667">**Data\_TriggerPoint** – крок, на якому зареєстровано цю подію (отримання повідомлення або відображення повідомлення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1667">**Data\_TriggerPoint** – The step in which this event was logged (message received vs message displayed)</span></span>

#### <a name="officetextfontpickerfontselectedwin32"></a><span data-ttu-id="1bd6a-1668">Office.Text.FontPickerFontSelected.Win32</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1668">Office.Text.FontPickerFontSelected.Win32</span></span>

<span data-ttu-id="1bd6a-1669">Ця подія вказує, чи правильно було відтворено завантажений шрифт.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1669">This event indicates whether the downloaded font was rendered correctly.</span></span> <span data-ttu-id="1bd6a-1670">Використовується для позначення успіху або невдачі завантаження шрифту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1670">Used to indicate success or failure of Font Download.</span></span>

<span data-ttu-id="1bd6a-1671">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1671">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1672">**Font name (Data\_Font)**  – ім’я шрифту, вибраного у списку шрифтів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1672">**Font name (Data\_Font)** - name of font picked in font picker</span></span>

  - <span data-ttu-id="1bd6a-1673">**User click (Data\_FClick)**  – якщо користувач використав мишу, щоб вибрати елемент</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1673">**User click (Data\_FClick)** - if user used mouse to select item</span></span>

#### <a name="officetextresourceclientrequestresourceinternal"></a><span data-ttu-id="1bd6a-1674">Office.Text.ResourceClient.RequestResourceInternal</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1674">Office.Text.ResourceClient.RequestResourceInternal</span></span>

<span data-ttu-id="1bd6a-1675">Ця подія вказує, чи правильно було завантажено шрифт.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1675">This event indicates whether the font was downloaded correctly.</span></span> <span data-ttu-id="1bd6a-1676">Використовується для позначення успіху або невдачі відтворення завантаженого шрифту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1676">Used to indicate success or failure of rendering the downloaded font.</span></span>

<span data-ttu-id="1bd6a-1677">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1677">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1678">**Data\_FontToken** – ім’я файлу, в якому буде збережено ресурс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1678">**Data\_FontToken** - resource file name will be saved as</span></span>

  - <span data-ttu-id="1bd6a-1679">**Data\_HTTPResult** – результат запиту HTTP</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1679">**Data\_HTTPResult** - result of the HTTP request</span></span>

  - <span data-ttu-id="1bd6a-1680">**Data\_HTTPStatusCode** – код HTTP, повернутий запитом HTTP</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1680">**Data\_HTTPStatusCode** - HTTP code returned from the HTTP request</span></span>

  - <span data-ttu-id="1bd6a-1681">**Data\_isInternetOn** – чи було підключення у спробі отримати ресурс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1681">**Data\_isInternetOn** - If we had connection when trying to retrieve the resource</span></span>

  - <span data-ttu-id="1bd6a-1682">**Data\_RequestUrl** – URL-адреса ресурсу CDN, який ми намагаємося отримати</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1682">**Data\_RequestUrl** - URL of the CDN resource we’re trying to retrieve</span></span>

#### <a name="officetranslatordocumenttranslated"></a><span data-ttu-id="1bd6a-1683">Office.Translator.DocumentTranslated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1683">Office.Translator.DocumentTranslated</span></span>

<span data-ttu-id="1bd6a-1684">Збирає дані про успіх або невдачу повного перекладу документа, ініційованого користувачем у службі Translator SDX.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1684">Collects success or failure of a full document translation a user trigger in the Translator SDX.</span></span> <span data-ttu-id="1bd6a-1685">Це вкрай важливо для оцінювання справності функції перекладу та реагування на будь-які перебої, що можуть виникнути.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1685">This is critical to evaluate the health of the translation feature and react to any outages that might occur.</span></span> <span data-ttu-id="1bd6a-1686">Відстеження роботоздатності сценарію "Перекласти документ" у програмі Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1686">Monitor the health of the "Translate Document" scenario in Word.</span></span>

<span data-ttu-id="1bd6a-1687">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1687">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1688">**Data.actionSource** – як було ініційовано переклад вибраного</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1688">**Data.actionSource -** How was the translate selection triggered-</span></span>

  - <span data-ttu-id="1bd6a-1689">**Data.bodyBackgroundColor** – колір тла контейнера теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1689">**Data.bodyBackgroundColor -** Office theme container background color-</span></span>

  - <span data-ttu-id="1bd6a-1690">**Data.bodyForegroundColor** – колір переднього плану контейнера теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1690">**Data.bodyForegroundColor -** Office theme container foreground color-</span></span>

  - <span data-ttu-id="1bd6a-1691">**Data.browserLang** – поточна мова відображення браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1691">**Data.browserLang -** Browser current display language-</span></span>

  - <span data-ttu-id="1bd6a-1692">**Data.browserOnline** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1692">**Data.browserOnline -** Obsolete-</span></span>

  - <span data-ttu-id="1bd6a-1693">**Data.browserPlatform** – платформа браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1693">**Data.browserPlatform -** Browser platform-</span></span>

  - <span data-ttu-id="1bd6a-1694">**Data.browserUserAgent** – агент користувача браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1694">**Data.browserUserAgent -** Browser user agent-</span></span>

  - <span data-ttu-id="1bd6a-1695">**Data.colorDepth** – глибина кольору в системі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1695">**Data.colorDepth -** System color depth-</span></span>

  - <span data-ttu-id="1bd6a-1696">**Data.contentLanguage** – виявлена мова вмісту, який потрібно перекласти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1696">**Data.contentLanguage -** Detected language of the content to translate-</span></span>

  - <span data-ttu-id="1bd6a-1697">**Data.controlBackgroundColor** – колір тла елементів керування теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1697">**Data.controlBackgroundColor -** Office theme control background color-</span></span>

  - <span data-ttu-id="1bd6a-1698">**Data.controlForegroundColor** – колір переднього плану елементів керування теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1698">**Data.controlForegroundColor -** Office theme control foreground color-</span></span>

  - <span data-ttu-id="1bd6a-1699">**Data.correlationId** – унікальний ідентифікатор запиту, надісланого до служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1699">**Data.correlationId -** Unique identifier of the request sent to the service-</span></span>

  - <span data-ttu-id="1bd6a-1700">**Data.crossSessionId** – унікальний ідентифікатор користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1700">**Data.crossSessionId -** Unique identifier of the user-</span></span>

  - <span data-ttu-id="1bd6a-1701">**Data.crossSessionStartTime** – позначка часу UTC, коли почався сеанс перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1701">**Data.crossSessionStartTime -** UTC timestamp of when the translation session started-</span></span>

  - <span data-ttu-id="1bd6a-1702">**Data.currentTime** – позначка часу UTC, коли було надіслано це повідомлення телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1702">**Data.currentTime -** UTC timestamp of when this telemetry message was sent-</span></span>

  - <span data-ttu-id="1bd6a-1703">**Data.displayLanguage** – мова інтерфейсу Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1703">**Data.displayLanguage -** Office display language-</span></span>

  - <span data-ttu-id="1bd6a-1704">**Data.documentSourceLang** – мова вмісту документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1704">**Data.documentSourceLang -** Document content language-</span></span>

  - <span data-ttu-id="1bd6a-1705">**Data.documentTargetLang** – мова, якою буде перекладено документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1705">**Data.documentTargetLang -** Language document will be translated to-</span></span>

  - <span data-ttu-id="1bd6a-1706">**Data.environment** – середовище служби, до якого надсилається запит</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1706">**Data.environment -** Service environment the request is sent to-</span></span>

  - <span data-ttu-id="1bd6a-1707">**Data.errorMessage** – повідомлення про помилку від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1707">**Data.errorMessage -** Error message reported by the service-</span></span>

  - <span data-ttu-id="1bd6a-1708">**Data.eventActionType** – тип події телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1708">**Data.eventActionType -** Type of telemetry event-</span></span>

  - <span data-ttu-id="1bd6a-1709">**Data.eventTagId** – унікальний ідентифікатор рядка коду, який створив це повідомлення телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1709">**Data.eventTagId -** Unique identifier of the line of code that produced this telemetry message-</span></span>

  - <span data-ttu-id="1bd6a-1710">**Data.flights** – увімкнуті тести</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1710">**Data.flights-** Enabled flights-</span></span>

  - <span data-ttu-id="1bd6a-1711">**Data.fileSize** – розмір файлу Word для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1711">**Data.fileSize -** Size of Word file to translate-</span></span>

  - <span data-ttu-id="1bd6a-1712">**Data.fileSource** – де розташовано файл Word (локально, в мережі)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1712">**Data.fileSource -** Where is the Word file hosted (offline, online)-</span></span>

  - <span data-ttu-id="1bd6a-1713">**Data.fileType** – розширення файлу Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1713">**Data.fileType -** Word file extension-</span></span>

  - <span data-ttu-id="1bd6a-1714">**Data.innerHeight"**  – висота контейнера бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1714">**Data.innerHeight"-** Side pane container height-</span></span>

  - <span data-ttu-id="1bd6a-1715">**Data.innerWidth"**  – ширина контейнера бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1715">**Data.innerWidth"-** Side pane container width-</span></span>

  - <span data-ttu-id="1bd6a-1716">**Data.lookupSourceLang** – не використовується для перекладу документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1716">**Data.lookupSourceLang-** Not used for document translation-</span></span>

  - <span data-ttu-id="1bd6a-1717">**Data.lookupTargetLang** – не використовується для перекладу документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1717">**Data.lookupTargetLang-** Not used for document translation-</span></span>

  - <span data-ttu-id="1bd6a-1718">**Data.officeHost** – програма Office, в якій розташована бічна область</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1718">**Data.officeHost-** Office application hosting the side pane-</span></span>

  - <span data-ttu-id="1bd6a-1719">**Data.officeLocale** – мова користувача Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1719">**Data.officeLocale-** Office user language-</span></span>

  - <span data-ttu-id="1bd6a-1720">**Data.officeMachineId** – унікальний ідентифікатор пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1720">**Data.officeMachineId-** Device Unique identifier-</span></span>

  - <span data-ttu-id="1bd6a-1721">**Data.officePlatform** – платформа пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1721">**Data.officePlatform -** Device platform-</span></span>

  - <span data-ttu-id="1bd6a-1722">**Data.officeSessionId** – ідентифікатор сеансу Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1722">**Data.officeSessionId -** Office session identifier-</span></span>

  - <span data-ttu-id="1bd6a-1723">**Data.officeUserId** – унікальний ідентифікатор користувача Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1723">**Data.officeUserId -** Office user unique identifier-</span></span>

  - <span data-ttu-id="1bd6a-1724">**Data.officeVersion** – версія Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1724">**Data.officeVersion -** Office version-</span></span>

  - <span data-ttu-id="1bd6a-1725">**Data.pageXOffset** – позиція прокручування бічної області по горизонталі від лівого краю області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1725">**Data.pageXOffset -** Side pane horizontal scroll position from the left side of the pane-</span></span>

  - <span data-ttu-id="1bd6a-1726">**Data.pageYOffset** – позиція прокручування бічної області по вертикалі від верхнього краю області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1726">**Data.pageYOffset -** Side pane vertical scroll position from the top side of the pane-</span></span>

  - <span data-ttu-id="1bd6a-1727">**Data.pixelDepth** – глибина кольору екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1727">**Data.pixelDepth -** Screen color resolution-</span></span>

  - <span data-ttu-id="1bd6a-1728">**Data.responseCode** – код відповіді на запит від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1728">**Data.responseCode -** Request response code from the service-</span></span>

  - <span data-ttu-id="1bd6a-1729">**Data.responseTime** – час виконання запиту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1729">**Data.responseTime -** Request elapsed time -</span></span>

  - <span data-ttu-id="1bd6a-1730">**Data.resultType** – результат запиту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1730">**Data.resultType -** Request result-</span></span>

  - <span data-ttu-id="1bd6a-1731">**Data.screenHeight** – висота екрана в пікселах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1731">**Data.screenHeight -** Screen height in pixels-</span></span>

  - <span data-ttu-id="1bd6a-1732">**Data.screenLeft** – горизонтальна координата вікна відносно екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1732">**Data.screenLeft -** Horizontal coordinate of the window relative to the screen-</span></span>

  - <span data-ttu-id="1bd6a-1733">**Data.screenTop** – вертикальна координата вікна відносно екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1733">**Data.screenTop -** Vertical coordinate of the window relative to the screen-</span></span>

  - <span data-ttu-id="1bd6a-1734">**Data.screenWidth** – ширина екрана в пікселах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1734">**Data.screenWidth -** Screen width in pixels-</span></span>

  - <span data-ttu-id="1bd6a-1735">**Data.selectedTab** – на якій вкладці міститься вибраний фрагмент або документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1735">**Data.selectedTab -** Which tab is selected Selection or Document-</span></span>

  - <span data-ttu-id="1bd6a-1736">**Data.serverUrl** – URL-адреса служби перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1736">**Data.serverUrl -** Translation service URL-</span></span>

  - <span data-ttu-id="1bd6a-1737">**Data.sessionId** – ідентифікатор сеансу бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1737">**Data.sessionId -** Side pane session identifier-</span></span>

  - <span data-ttu-id="1bd6a-1738">**Data.sessionStartTime** – позначка часу UTC, коли почався сеанс перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1738">**Data.sessionStartTime -** UTC Timestamp of when the translation session started-</span></span>

  - <span data-ttu-id="1bd6a-1739">**Data.sourceTextHash** – геш-код тексту для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1739">**Data.sourceTextHash -** Hash of text to translate-</span></span>

  - <span data-ttu-id="1bd6a-1740">**Data.sourceTextLength** – довжина тексту для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1740">**Data.sourceTextLength -** Text to translate length-</span></span>

  - <span data-ttu-id="1bd6a-1741">**Data.sourceTextWords** – кількість слів у тексті для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1741">**Data.sourceTextWords -** Number of words in the text to translate-</span></span>

  - <span data-ttu-id="1bd6a-1742">**Data.warningMessage** – попереджувальне повідомлення від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1742">**Data.warningMessage -** Warning message reported by the service-</span></span>

#### <a name="officetranslatortexttranslated"></a><span data-ttu-id="1bd6a-1743">Office.Translator.TextTranslated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1743">Office.Translator.TextTranslated</span></span>

<span data-ttu-id="1bd6a-1744">Збирає дані про успіх або невдачу перекладу вибраного фрагмента, ініційованого користувачем у службі Translator SDX.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1744">Collects success or failure of a selection translation that a user action triggers in the Translator SDX.</span></span> <span data-ttu-id="1bd6a-1745">Це вкрай важливо для оцінювання справності функції перекладу та реагування на будь-які перебої, що можуть виникнути.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1745">This is critical to evaluate the health of the translation feature and react to any outages that might occur.</span></span> <span data-ttu-id="1bd6a-1746">Використовується для відстеження роботоздатності сценарію "Перекласти вибране" у програмах Excel, PowerPoint, Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1746">Used to monitor the health of the "Translate Selection" scenario in Excel, PowerPoint, Word.</span></span>

<span data-ttu-id="1bd6a-1747">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1747">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1748">**Data.actionSource** – як було ініційовано переклад вибраного</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1748">**Data.actionSource -** How was the translate selection triggered</span></span>

  - <span data-ttu-id="1bd6a-1749">**Data.bodyBackgroundColor** – колір тла контейнера теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1749">**Data.bodyBackgroundColor -** Office theme container background color</span></span>

  - <span data-ttu-id="1bd6a-1750">**Data.bodyForegroundColor** – колір переднього плану контейнера теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1750">**Data.bodyForegroundColor -** Office theme container foreground color</span></span>

  - <span data-ttu-id="1bd6a-1751">**Data.browserLang** – поточна мова відображення браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1751">**Data.browserLang -** Browser current display language</span></span>

  - <span data-ttu-id="1bd6a-1752">**Data.browserOnline** – застаріле</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1752">**Data.browserOnline -** Obsolete</span></span>

  - <span data-ttu-id="1bd6a-1753">**Data.browserPlatform** – платформа браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1753">**Data.browserPlatform -** Browser platform</span></span>

  - <span data-ttu-id="1bd6a-1754">**Data.browserUserAgent** – агент користувача браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1754">**Data.browserUserAgent -** Browser user agent</span></span>

  - <span data-ttu-id="1bd6a-1755">**Data.colorDepth** – глибина кольору в системі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1755">**Data.colorDepth -** System color depth</span></span>

  - <span data-ttu-id="1bd6a-1756">**Data.contentLanguage** – виявлена мова вмісту, який потрібно перекласти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1756">**Data.contentLanguage -** Detected language of the content to translate</span></span>

  - <span data-ttu-id="1bd6a-1757">**Data.controlBackgroundColor** – колір тла елементів керування теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1757">**Data.controlBackgroundColor -** Office theme control background color</span></span>

  - <span data-ttu-id="1bd6a-1758">**Data.controlForegroundColor** – колір переднього плану елементів керування теми Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1758">**Data.controlForegroundColor -** Office theme control foreground color</span></span>

  - <span data-ttu-id="1bd6a-1759">**Data.correlationId** – унікальний ідентифікатор запиту, надісланого до служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1759">**Data.correlationId -** Unique identifier of the request sent to the service</span></span>

  - <span data-ttu-id="1bd6a-1760">**Data.crossSessionId** – унікальний ідентифікатор користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1760">**Data.crossSessionId -** Unique identifier of the user</span></span>

  - <span data-ttu-id="1bd6a-1761">**Data.crossSessionStartTime** – позначка часу UTC, коли почався сеанс перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1761">**Data.crossSessionStartTime -** UTC timestamp of when the translation session started</span></span>

  - <span data-ttu-id="1bd6a-1762">**Data.currentTime** – позначка часу UTC, коли було надіслано це повідомлення телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1762">**Data.currentTime -** UTC timestamp of when this telemetry message was sent</span></span>

  - <span data-ttu-id="1bd6a-1763">**Data.displayLanguage** – мова інтерфейсу Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1763">**Data.displayLanguage -** Office display language</span></span>

  - <span data-ttu-id="1bd6a-1764">**Data.documentSourceLang** – не використовується для виділення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1764">**Data.documentSourceLang -** Not used for selection</span></span>

  - <span data-ttu-id="1bd6a-1765">**Data.documentTargetLang** – не використовується для виділення перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1765">**Data.documentTargetLang -** Nor used for translation selection</span></span>

  - <span data-ttu-id="1bd6a-1766">**Data.environment** – середовище служби, до якого надсилається запит</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1766">**Data.environment -** Service environment the request is sent to</span></span>

  - <span data-ttu-id="1bd6a-1767">**Data.errorMessage** – повідомлення про помилку від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1767">**Data.errorMessage -** Error message reported by the service</span></span>

  - <span data-ttu-id="1bd6a-1768">**Data.eventActionType** – тип події телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1768">**Data.eventActionType -** Type of telemetry event</span></span>

  - <span data-ttu-id="1bd6a-1769">**Data.eventTagId** – унікальний ідентифікатор рядка коду, який створив це повідомлення телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1769">**Data.eventTagId"-** Unique identifier of the line of code that produced this telemetry message</span></span>

  - <span data-ttu-id="1bd6a-1770">**Data.flights** – увімкнуті тести</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1770">**Data.flights-** Enabled flights</span></span>

  - <span data-ttu-id="1bd6a-1771">**Data.innerHeight** – висота контейнера бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1771">**Data.innerHeight -** Side pane container height</span></span>

  - <span data-ttu-id="1bd6a-1772">**Data.innerWidth** – ширина контейнера бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1772">**Data.innerWidth -** Side pane container width</span></span>

  - <span data-ttu-id="1bd6a-1773">**Data.lookupSourceLang** – мова виділеного тексту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1773">**Data.lookupSourceLang-** Language of the currently selected text</span></span>

  - <span data-ttu-id="1bd6a-1774">**Data.lookupTargetLang** – мова, якою буде перекладено виділений текст</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1774">**Data.lookupTargetLang-** Language currently selected text will be translated to</span></span>

  - <span data-ttu-id="1bd6a-1775">**Data.officeHost** – програма Office, в якій розташована бічна область</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1775">**Data.officeHost-** Office application hosting the side pane</span></span>

  - <span data-ttu-id="1bd6a-1776">**Data.officeLocale** – мова користувача Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1776">**Data.officeLocale-** Office user language</span></span>

  - <span data-ttu-id="1bd6a-1777">**Data.officeMachineId** – унікальний ідентифікатор пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1777">**Data.officeMachineId-** Device Unique identifier</span></span>

  - <span data-ttu-id="1bd6a-1778">**Data.officePlatform** – платформа пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1778">**Data.officePlatform -** Device platform</span></span>

  - <span data-ttu-id="1bd6a-1779">**Data.officeSessionId** – ідентифікатор сеансу Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1779">**Data.officeSessionId -** Office session identifier</span></span>

  - <span data-ttu-id="1bd6a-1780">**Data.officeUserId** – унікальний ідентифікатор користувача Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1780">**Data.officeUserId -** Office user unique identifier</span></span>

  - <span data-ttu-id="1bd6a-1781">**Data.officeVersion** – версія Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1781">**Data.officeVersion -** Office version</span></span>

  - <span data-ttu-id="1bd6a-1782">**Data.pageXOffset** – позиція прокручування бічної області по горизонталі від лівого краю панелі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1782">**Data.pageXOffset -** Side pane horizontal scroll position from the left side of the pane</span></span>

  - <span data-ttu-id="1bd6a-1783">**Data.pageYOffset** – позиція прокручування бічної області по вертикалі від верхнього краю області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1783">**Data.pageYOffset -** Side pane vertical scroll position from the top side of the pane</span></span>

  - <span data-ttu-id="1bd6a-1784">**Data.pixelDepth** – глибина кольору екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1784">**Data.pixelDepth -** Screen color resolution</span></span>

  - <span data-ttu-id="1bd6a-1785">**Data.responseCode** – код відповіді на запит від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1785">**Data.responseCode -** Request response code from the service</span></span>

  - <span data-ttu-id="1bd6a-1786">**Data.responseTime** – час виконання запиту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1786">**Data.responseTime -** Request elapsed time</span></span>

  - <span data-ttu-id="1bd6a-1787">**Data.resultType** – результат запиту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1787">**Data.resultType -** Request result</span></span>

  - <span data-ttu-id="1bd6a-1788">**Data.screenHeight** – висота екрана в пікселах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1788">**Data.screenHeight -** Screen height in pixels</span></span>

  - <span data-ttu-id="1bd6a-1789">**Data.screenLeft** – горизонтальна координата вікна відносно екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1789">**Data.screenLeft -** Horizontal coordinate of the window relative to the screen</span></span>

  - <span data-ttu-id="1bd6a-1790">**Data.screenTop** – вертикальна координата вікна відносно екрана</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1790">**Data.screenTop -** Vertical coordinate of the window relative to the screen</span></span>

  - <span data-ttu-id="1bd6a-1791">**Data.screenWidth** – ширина екрана в пікселах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1791">**Data.screenWidth -** Screen width in pixels</span></span>

  - <span data-ttu-id="1bd6a-1792">**Data.selectedTab** – на якій вкладці міститься вибраний фрагмент або документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1792">**Data.selectedTab -** Which tab is selected Selection or Document</span></span>

  - <span data-ttu-id="1bd6a-1793">**Data.serverUrl** – URL-адреса служби перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1793">**Data.serverUrl -** Translation service URL</span></span>

  - <span data-ttu-id="1bd6a-1794">**Data.sessionId** – ідентифікатор сеансу бічної області</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1794">**Data.sessionId -** Side pane session identifier</span></span>

  - <span data-ttu-id="1bd6a-1795">**Data.sessionStartTime** – позначка часу UTC, коли почався сеанс перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1795">**Data.sessionStartTime -** UTC Timestamp of when the translation session started</span></span>

  - <span data-ttu-id="1bd6a-1796">**Data.sourceTextHash** – геш-код тексту для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1796">**Data.sourceTextHash -** Hash of text to translate</span></span>

  - <span data-ttu-id="1bd6a-1797">**Data.sourceTextLength** – довжина тексту для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1797">**Data.sourceTextLength -** Text to translate length</span></span>

  - <span data-ttu-id="1bd6a-1798">**Data.sourceTextWords** – кількість слів у тексті для перекладу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1798">**Data.sourceTextWords -** Number of words in the text to translate</span></span>

  - <span data-ttu-id="1bd6a-1799">**Data.warningMessage** – попереджувальне повідомлення від служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1799">**Data.warningMessage -** Warning message reported by the service</span></span>

#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a><span data-ttu-id="1bd6a-1800">Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1800">Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend</span></span>

<span data-ttu-id="1bd6a-1801">Ця подія реєструє статистику для кожного документа, коли програма Office Word закривається або тимчасово припиняє роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1801">This event logs document statistics for each document when Office Word is closed or suspended.</span></span>

<span data-ttu-id="1bd6a-1802">Вона використовується для зіставлення змін у документі, його розміру тощо з помилками збереження документа, надання спільного доступу до нього та спільної роботи над ним у мережі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1802">The event is used to correlate document edits, size, etc. with document-save, document-share, and document-online-collaboration errors.</span></span>

<span data-ttu-id="1bd6a-1803">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1803">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1804">**Data\_BkmkRefCount** – кількість посилань на закладки в документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1804">**Data\_BkmkRefCount -** Number of bookmark references in the document</span></span>

  - <span data-ttu-id="1bd6a-1805">**Data\_CharacterCount** – кількість символів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1805">**Data\_CharacterCount -** Number of characters in the document</span></span>

  - <span data-ttu-id="1bd6a-1806">**Data\_CharactersWithSpaceCount** – кількість символів і пробілів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1806">**Data\_CharactersWithSpaceCount -** Number of characters and spaces in the document</span></span>

  - <span data-ttu-id="1bd6a-1807">**Data\_ChartCount** – кількість діаграм у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1807">**Data\_ChartCount -** Number of charts in the document</span></span>

  - <span data-ttu-id="1bd6a-1808">**Data\_CitationCount** – кількість посилань у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1808">**Data\_CitationCount -** Number of citations in the document</span></span>

  - <span data-ttu-id="1bd6a-1809">**Data\_DocumentLocation** – указує службу, яка надала документ (OneDrive, файловий сервер, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1809">**Data\_DocumentLocation -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-1810">**Data\_ETW\_TrackbackTag** – визначає місце в коді, де виникла подія (закриття або тимчасове припинення роботи)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1810">**Data\_ETW\_TrackbackTag -** Identifies the place in code where this event was fired from (Close or Suspend)</span></span>

  - <span data-ttu-id="1bd6a-1811">**Data\_EndnoteDocCount** – кількість кінцевих виносок у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1811">**Data\_EndnoteDocCount -** Number of endnotes in the document</span></span>

  - <span data-ttu-id="1bd6a-1812">**Data\_FootnoteDocCount** – кількість виносок у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1812">**Data\_FootnoteDocCount -** Number of footnotes in the document</span></span>

  - <span data-ttu-id="1bd6a-1813">**Data\_HasBibliography** – указує, чи містить документ бібліографію</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1813">**Data\_HasBibliography -** Indicates whether the document contains bibliography</span></span>

  - <span data-ttu-id="1bd6a-1814">**Data\_HasHeader** – указує, чи містить документ верхній колонтитул</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1814">**Data\_HasHeader -** Indicates whether the document contains a header</span></span>

  - <span data-ttu-id="1bd6a-1815">**Data\_IsImeUsed** – указує, чи використовувався в документі редактор засобів вводу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1815">**Data\_IsImeUsed -** Indicates whether Input Method Editor been was used in the document</span></span>

  - <span data-ttu-id="1bd6a-1816">**Data\_IsPageCountInProgress** – чи виконується зараз у документі підрахунок сторінок.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1816">**Data\_IsPageCountInProgress -** Indicates whether page count is currently in progress for the document.</span></span>

  - <span data-ttu-id="1bd6a-1817">**Data\_IsTouchUsed** – указує, чи було використано в документі сенсорний ввід</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1817">**Data\_IsTouchUsed -** Indicates whether touch input was used in the document</span></span>

  - <span data-ttu-id="1bd6a-1818">**Data\_IsTrackChangesOn** – указує, чи ввімкнуто в документі відстеження змін</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1818">**Data\_IsTrackChangesOn -** Indicates whether track-changes was on for the document</span></span>

  - <span data-ttu-id="1bd6a-1819">**Data\_LineCount** – кількість рядків у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1819">**Data\_LineCount -** Number of lines in the document</span></span>

  - <span data-ttu-id="1bd6a-1820">**Data\_MainPdod** – ідентифікатор документа в процесі Office Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1820">**Data\_MainPdod -** The document identifier in Office Word process.</span></span>

  - <span data-ttu-id="1bd6a-1821">**Data\_PageCount** – кількість сторінок у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1821">**Data\_PageCount -** Number of pages in the document</span></span>

  - <span data-ttu-id="1bd6a-1822">**Data\_PageNumberFieldCount** – кількість полів номерів сторінок у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1822">**Data\_PageNumberFieldCount -** Number of page number fields in the document</span></span>

  - <span data-ttu-id="1bd6a-1823">**Data\_ParagraphCount** – кількість абзаців у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1823">**Data\_ParagraphCount -** Number of paragraphs in the document</span></span>

  - <span data-ttu-id="1bd6a-1824">**Data\_PicCount** – кількість зображень у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1824">**Data\_PicCount -** Number of pictures in the document</span></span>

  - <span data-ttu-id="1bd6a-1825">**Data\_RsidCount** – кількість ідентифікаторів збереження редакцій у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1825">**Data\_RsidCount -** Number of revisions save identifier in the document</span></span>

  - <span data-ttu-id="1bd6a-1826">**Data\_TocCount** – кількість змістів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1826">**Data\_TocCount -** Number of table of contents in the document</span></span>

  - <span data-ttu-id="1bd6a-1827">**Data\_UrlHash** – односторонній геш-код для створення наївного ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1827">**Data\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-1828">**Data\_UserActionID** – це поле даних не використовується (значення завжди 0).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1828">**Data\_UserActionID -** this data field is not used (the value is always 0).</span></span>

  - <span data-ttu-id="1bd6a-1829">**Data\_UserActionName** – завжди “DocumentStatsOnCloseAndSuspend”</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1829">**Data\_UserActionName -** always “DocumentStatsOnCloseAndSuspend”</span></span>

  - <span data-ttu-id="1bd6a-1830">**Data\_UserInteractionTimeMsec** – тривалість активної роботи користувача з документом у мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1830">**Data\_UserInteractionTimeMsec -** Number of milliseconds that the user was actively interacting with the document</span></span>

  - <span data-ttu-id="1bd6a-1831">**Data\_WordCount** – кількість слів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1831">**Data\_WordCount -** Number of words in document</span></span>

#### <a name="officewordfilenewcreatenewfile"></a><span data-ttu-id="1bd6a-1832">Office.Word.FileNew.CreateNewFile</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1832">Office.Word.FileNew.CreateNewFile</span></span>

<span data-ttu-id="1bd6a-1833">Ця подія вказує, що в Office Word створено новий документ, і відстежує успіх або невдачу операції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1833">This event indicates that a new document is created in Office Word and tracks success or failure of the operation.</span></span> <span data-ttu-id="1bd6a-1834">Вона використовується, щоб контролювати належне створення документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1834">The event is used to monitor that new document creation is working as expected.</span></span> <span data-ttu-id="1bd6a-1835">Також вона використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1835">It is also used to calculated monthly active users/devices and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-1836">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1836">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1837">**Data\_DirtyState** – чи було створено документ зі змінами, які потребують збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1837">**Data\_DirtyState** - whether the document was created in a dirty state (with changes that need to be saved)</span></span>

  - <span data-ttu-id="1bd6a-1838">**Data\_ErrorID** – ідентифікатор помилки у разі невдалої операції</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1838">**Data\_ErrorID** - error identifier in case of operation failure</span></span>

  - <span data-ttu-id="1bd6a-1839">**Data\_MainPdod** – ідентифікатор документа в цьому сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1839">**Data\_MainPdod** - The document identifier during this process session</span></span>

  - <span data-ttu-id="1bd6a-1840">**Data\_UsesCustomTemplate** – указує, чи було створено документ із настроюваного шаблону</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1840">**Data\_UsesCustomTemplate** - indicates whether the document was created from a custom template</span></span>

#### <a name="officewordfilesaveactcmdgosubsaveas"></a><span data-ttu-id="1bd6a-1841">Office.Word.FileSave.ActCmdGosubSaveAs</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1841">Office.Word.FileSave.ActCmdGosubSaveAs</span></span>

<span data-ttu-id="1bd6a-1842">Ця подія вказує, що користувач зберігає внесені зміни в новому документі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1842">This event indicates that a user is saving their changes to a new document.</span></span> <span data-ttu-id="1bd6a-1843">Подія відстежує, чи працює операція збереження нового документа належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1843">The event monitors whether saving to a new document is working as expected.</span></span> <span data-ttu-id="1bd6a-1844">Також вона використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1844">It is also used to calculated monthly active users/devices and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-1845">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1845">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1846">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1846">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-1847">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1847">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-1848">**Data\_DetachedDuration** – як довго дія була від’єднаною від потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1848">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-1849">**Data\_Doc\_AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1849">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-1850">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1850">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1851">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1851">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-1852">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1852">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-1853">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1853">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-1854">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1854">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-1855">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1855">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-1856">**Data\_Doc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1856">**Data\_Doc\_FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-1857">**Data\_Doc\_IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1857">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-1858">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1858">**Data\_Doc\_IdentityTelemetryId -** A one way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-1859">**Data\_Doc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1859">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-1860">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1860">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-1861">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1861">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-1862">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1862">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-1863">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1863">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-1864">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1864">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1865">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1865">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-1866">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1866">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-1867">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1867">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-1868">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1868">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-1869">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1869">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-1870">**Data\_Doc**ReadOnlyReasons\_ –причини, з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1870">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-1871">**Data\_Doc**ResourceIdHash\_ – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1871">**Data\_Doc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1872">**Data\_Doc\_ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1872">**Data\_Doc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1873">**Data\_Doc\_ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1873">**Data\_Doc\_ServerProtocol -** The protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-1874">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1874">**Data\_Doc\_ServerType -** The type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1875">**Data\_Doc\_ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1875">**Data\_Doc\_ServerVersion -** The server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-1876">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1876">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-1877">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1877">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-1878">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1878">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-1879">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1879">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1880">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1880">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-1881">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1881">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-1882">**Data\_Doc\_UrlHash** – односторонній геш-код для створення наївного ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1882">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-1883">**Data\_EditorDisablingRename** – ідентифікатор першого редактора, який спричинив заборону перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1883">**Data\_EditorDisablingRename -** identifier of the first editor that caused rename to be disabled</span></span>

  - <span data-ttu-id="1bd6a-1884">**Data\_EditorsCount** – кількість редакторів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1884">**Data\_EditorsCount -** Number of editors in the document</span></span>

  - <span data-ttu-id="1bd6a-1885">**Data\_LastLoggedTag** – унікальний тег сайту виклику коду, який повідомляє, коли не вдалося двічі виконати збереження (використовується для діагностики якості даних)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1885">**Data\_LastLoggedTag -** Unique tag for code call site used to identify when we fail to try the save twice (used for data quality diagnostics)</span></span>

  - <span data-ttu-id="1bd6a-1886">**Data\_MoveDisabledReason** – помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1886">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-1887">**Data\_MoveFlightEnabled** – указує, чи активовано тест функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1887">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-1888">**Data\_RenameDisabledReason** – помилка, що забороняє перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1888">**Data\_RenameDisabledReason -** Error that is causing rename to be disabled for the document</span></span>

  - <span data-ttu-id="1bd6a-1889">**Data\_RenameFlightEnabled** – чи активовано тест функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1889">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a><span data-ttu-id="1bd6a-1890">Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1890">Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave</span></span>

<span data-ttu-id="1bd6a-1891">Ця подія повідомляє про збереження в Office Word автоматично відновленого документа, який не було збережено раніше.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1891">This event indicates Office Word saves an auto-recovery document that has not been saved before.</span></span> <span data-ttu-id="1bd6a-1892">Це дає змогу корпорації Майкрософт виявляти помилки автоматичного відновлення, що важливо для безпеки даних документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1892">It allows Microsoft to detect errors in auto-recovery which is important for document data safety.</span></span>

<span data-ttu-id="1bd6a-1893">Подія відстежує, чи працює збереження після автоматичного відновлення належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1893">The event monitors whether auto-recovery-save is working as expected.</span></span> <span data-ttu-id="1bd6a-1894">Також вона використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1894">It is also used to calculated monthly active users/devices and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-1895">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1895">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1896">**Data\_DetachedDuration** – як довго дія була від’єднаною від потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1896">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-1897">**Data\_Doc\_AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1897">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-1898">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1898">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1899">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1899">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-1900">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1900">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-1901">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1901">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-1902">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1902">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-1903">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1903">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-1904">**Data\_Doc\_FqdnHash** – односторонній геш-код особистого імені домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1904">**Data\_Doc\_FqdnHash -** One way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-1905">**Data\_Doc\_IdentityTelemetryId** – односторонній геш-код ідентичності користувача, яку було використано для відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1905">**Data\_Doc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-1906">**Data\_Doc\_InitializationScenario** – реєструє, яким чином було відкрито документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1906">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-1907">**Data\_Doc\_IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1907">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-1908">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1908">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-1909">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1909">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-1910">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1910">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-1911">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1911">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-1912">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1912">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1913">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1913">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-1914">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1914">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-1915">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1915">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-1916">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1916">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-1917">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1917">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-1918">**Data\_Doc**ReadOnlyReasons\_ –причини, з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1918">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-1919">**Data\_Doc**ResourceIdHash\_ – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1919">**Data\_Doc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1920">**Data\_Doc\_ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1920">**Data\_Doc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1921">**Data\_Doc\_ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1921">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-1922">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1922">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1923">**Data\_Doc\_ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1923">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-1924">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1924">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-1925">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1925">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-1926">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1926">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-1927">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1927">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1928">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1928">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-1929">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1929">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-1930">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1930">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-1931">**Data\_Doc\_WopiServiceId** – містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1931">**Data\_Doc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-1932">**Data\_FailureClass** – ціле число, що вказує клас відмови для відмов переходу на OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1932">**Data\_FailureClass -** Integer representing the failure class for Office Collaboration Services (OCS) transition failures</span></span>

  - <span data-ttu-id="1bd6a-1933">**Data\_MainPdod** – ідентифікатор документа в процесі Office Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1933">**Data\_MainPdod -** The document identifier in Office Word process.</span></span>

  - <span data-ttu-id="1bd6a-1934">**Data\_MoveFlightEnabled** – указує, чи активовано тест функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1934">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-1935">**Data\_OCSSyncbackSaveStarted** – позначка синхронізованого збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1935">**Data\_OCSSyncbackSaveStarted -** Flag that indicates that this save is related to sync back save</span></span>

  - <span data-ttu-id="1bd6a-1936">**Data\_RenameDisabledReason** – помилка, що забороняє перейменування цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1936">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-1937">**Data\_RenameFlightEnabled** – чи активовано тест функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1937">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-1938">**Data\_SaveInitiateKind** – ціле число, що вказує, як було розпочато збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1938">**Data\_SaveInitiateKind -** Integer that indicates how the save was initiated</span></span>

  - <span data-ttu-id="1bd6a-1939">**Data\_SrcDocIsUnnamedOrNew** – указує, чи новий документ, що зберігається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1939">**Data\_SrcDocIsUnnamedOrNew -** Indicates whether the document we are saving is new</span></span>

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a><span data-ttu-id="1bd6a-1940">Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1940">Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave</span></span>

<span data-ttu-id="1bd6a-1941">Ця подія показує, що програма Office Word пропонує користувачеві, зберегти зміни, коли він намагається закрити документ.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1941">This event indicates Office Word prompts the user to save changes when it tries to close the document.</span></span> <span data-ttu-id="1bd6a-1942">Це дає корпорації Майкрософт змогу відстежувати якість збереження під час виходу, щоб уникнути втрати даних документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1942">It allows Microsoft to monitor whether save-at-quit works as expected to avoid document data loss.</span></span> <span data-ttu-id="1bd6a-1943">Подія відстежує, чи працює збереження під час виходу належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1943">The event monitors whether save-at-quit is working as expected.</span></span> <span data-ttu-id="1bd6a-1944">Також вона використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1944">It is also used to calculated monthly active users/devices and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-1945">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1945">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-1946">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1946">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-1947">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1947">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-1948">**Data\_DetachedDuration** – як довго дія була від’єднаною від потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1948">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-1949">**Data\_Doc\_AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1949">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-1950">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1950">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-1951">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1951">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-1952">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1952">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-1953">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1953">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-1954">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1954">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-1955">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1955">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-1956">**Data\_Doc\_FqdnHash** – односторонній геш-код особистого імені домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1956">**Data\_Doc\_FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-1957">**Data\_Doc\_IdentityTelemetryId** – односторонній геш-код ідентичності користувача, яку було використано для відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1957">**Data\_Doc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-1958">**Data\_Doc\_InitializationScenario** – реєструє, яким чином було відкрито документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1958">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-1959">**Data\_Doc\_IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1959">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-1960">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1960">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-1961">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1961">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-1962">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1962">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-1963">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1963">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-1964">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1964">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-1965">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1965">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-1966">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1966">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-1967">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1967">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-1968">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1968">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-1969">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1969">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-1970">**Data\_Doc**ReadOnlyReasons\_ –причини, з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1970">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-1971">**Data\_Doc**ResourceIdHash\_ – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1971">**Data\_Doc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1972">**Data\_Doc\_ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1972">**Data\_Doc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-1973">**Data\_Doc\_ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1973">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-1974">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1974">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-1975">**Data\_Doc\_ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1975">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-1976">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1976">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-1977">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1977">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-1978">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1978">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-1979">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1979">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-1980">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1980">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-1981">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1981">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-1982">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1982">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-1983">**Data\_Doc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1983">**Data\_Doc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-1984">**Data\_DstDoc\_AccessMode –** Кінцевий документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1984">**Data\_DstDoc\_AccessMode -** Destination Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-1985">**Data\_DstDoc\_EdpState –Параметр електронного захисту даних кінцевого документа-**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1985">**Data\_DstDoc\_EdpState –Electronic Data Protection setting for the destination document-**</span></span>

  - <span data-ttu-id="1bd6a-1986">**Data\_DstDoc\_Ext –** Розширення кінцевого документа (docx/xlsb/pptx, тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1986">**Data\_DstDoc\_Ext -** Document extension (docx/xlsb/pptx, etc.) for the destination document</span></span>

  - <span data-ttu-id="1bd6a-1987">**Data\_DstDoc\_FileFormat –** Версія протоколу формату файлу кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1987">**Data\_DstDoc\_FileFormat -** File format protocol version for the destination document</span></span>

  - <span data-ttu-id="1bd6a-1988">**Data\_DstDoc\_Location –** Вказує службу, що надає сховище для кінцевого документа (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1988">**Data\_DstDoc\_Location -** Indicates which service will provide storage for destination document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-1989">**Data\_DstDoc\_LocationDetails –** Вказує локальну відому папку де зберігається кінцевий документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1989">**Data\_DstDoc\_LocationDetails -** Indicates which local Known Folder stored the destination document</span></span>

  - <span data-ttu-id="1bd6a-1990">**Data\_DstDoc\_SessionId –** Визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1990">**Data\_DstDoc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-1991">**Data\_DstDoc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1991">**Data\_DstDoc\_UrlHash -** One-way hash to create a naïve document identifier for the destination document</span></span>

  - <span data-ttu-id="1bd6a-1992">**Data\_FailureClass –** Ціле число, що вказує клас відмов для відмов переходу OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1992">**Data\_FailureClass -** Integer representing the failure class for OCS transition failures</span></span>

  - <span data-ttu-id="1bd6a-1993">**Data\_LocationPickerSaveStatus –** Ціле значення, яке вказує дію, що спричинила збереження в діалоговому вікні виходу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1993">**Data\_LocationPickerSaveStatus -** Integer value that indicates the action that triggered the save from the save on exit dialog</span></span>

  - <span data-ttu-id="1bd6a-1994">**Data\_MainPdod –** Ідентифікатор документа в Office Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1994">**Data\_MainPdod -** The document identifier in Office Word process.</span></span>

  - <span data-ttu-id="1bd6a-1995">**Data\_MoveFlightEnabled** – указує, чи активовано тест функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1995">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-1996">**Data\_OCSSyncbackSaveStarted** – позначка синхронізованого збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1996">**Data\_OCSSyncbackSaveStarted -** Flag that indicates that this save is related to sync back save</span></span>

  - <span data-ttu-id="1bd6a-1997">**Data\_RenameDisabledReason** – помилка, що забороняє перейменування цього документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1997">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-1998">**Data\_RenameFlightEnabled** – чи активовано тест функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1998">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-1999">**Data\_SaveInitiateKind** – ціле число, що вказує, як було розпочато збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-1999">**Data\_SaveInitiateKind -** Integer that indicates how the save was initiated</span></span>

  - <span data-ttu-id="1bd6a-2000">**Data\_SrcDocIsUnnamedOrNew –** Вказує чи новий документ, що зберігається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2000">**Data\_SrcDocIsUnnamedOrNew -** Indicates whether the document we are saving is new</span></span>

#### <a name="officewordfilesavesaveassavefile"></a><span data-ttu-id="1bd6a-2001">Office.Word.FileSave.SaveAsSaveFile</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2001">Office.Word.FileSave.SaveAsSaveFile</span></span>

<span data-ttu-id="1bd6a-2002">Ця подія вказує, що Office Word зберігає документ у новий документ.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2002">This event indicates Office Word saves a document into a new document.</span></span> <span data-ttu-id="1bd6a-2003">Це дає змогу Microsoft виявляти помилки команди «Зберегти як», що важливо для уникнення втрати даних документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2003">It allows Microsoft to detect errors in save-as which is important to avoid document data loss.</span></span> <span data-ttu-id="1bd6a-2004">Подія відстежує чи працює команда «Зберегти як» належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2004">The event monitors whether save-as is working as expected.</span></span> <span data-ttu-id="1bd6a-2005">І використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2005">It is also used to calculated monthly active users/devices and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-2006">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2006">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2007">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2007">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-2008">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2008">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2009">**Data\_AddDocTelemResDst –** Повідомляє чи заповнені інші пов'язані значення телеметрії документів у події для кінцевого документа. </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2009">**Data\_AddDocTelemResDst -** Reports whether we were able to properly populate other document telemetry related values in the event for the destination document.</span></span> <span data-ttu-id="1bd6a-2010">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2010">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2011">**Data\_AddDocTelemResSrc –** Повідомляє чи заповнені інші пов'язані значення телеметрії документів у події для вихідного документа. </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2011">**Data\_AddDocTelemResSrc -** Reports whether we were able to properly populate other document telemetry related values in the event for the source document.</span></span> <span data-ttu-id="1bd6a-2012">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2012">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2013">**Data\_DetachedDuration** – як довго дія була від’єднаною від потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2013">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-2014">**Data\_Doc\_AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2014">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-2015">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2015">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2016">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2016">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2017">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2017">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-2018">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2018">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-2019">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2019">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2020">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2020">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-2021">**Data\_Doc\_FqdnHash** – односторонній геш-код особистого імені домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2021">**Data\_Doc\_FqdnHash -** One way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-2022">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2022">**Data\_Doc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2023">**Data\_Doc\_IOFlags –** Повідомляє про кешовані позначки для встановлення параметрів запитів відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2023">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2024">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2024">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2025">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2025">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2026">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2026">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2027">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2027">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2028">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2028">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2029">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2029">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2030">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2030">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-2031">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2031">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2032">**Data\_Doc\_NumberCoAuthors –** Кількість користувачів під час сеансу спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2032">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2033">**Data\_Doc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2033">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2034">**Data\_Doc**ResourceIdHash\_ – анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2034">**Data\_Doc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2035">**Data\_Doc\_ServerDocId** – незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2035">**Data\_Doc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2036">**Data\_Doc\_ServerProtocol** – версія протоколу, що використовується для зв'язку зі службою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2036">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2037">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2037">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2038">**Data\_Doc\_ServerVersion** – версія сервера, який надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2038">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2039">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2039">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-2040">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2040">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2041">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2041">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2042">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2042">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2043">**Data\_Doc\_StreamAvailability –** Індикатор, що вказує доступний чи вимкнений потік документів </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2043">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2044">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2044">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2045">**Data\_DstDoc\_AccessMode –** Кінцевий документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2045">**Data\_DstDoc\_AccessMode -** Destination Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-2046">**Data\_DstDoc\_AssistedReadingReasons –** Попередньо визначений набір значень причини відкриття кінцевого документу в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2046">**Data\_DstDoc\_AssistedReadingReasons -** Predefined set of values of why the destination document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2047">**Data\_DstDoc\_ChunkingType –** Одиниці для інкрементного відкриття кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2047">**Data\_DstDoc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2048">**Data\_DstDoc\_EdpState –** Параметр електронного захисту даних кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2048">**Data\_DstDoc\_EdpState -** Electronic Data Protection setting for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2049">**Data\_DstDoc\_Ext –** Розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2049">**Data\_DstDoc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-2050">**Data\_DstDoc\_FileFormat –** Версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2050">**Data\_DstDoc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2051">**Data\_DstDoc\_Fqdn –** Ім'я домену OneDrive або SharePoint Online для кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2051">**Data\_DstDoc\_Fqdn -** OneDrive or SharePoint Online Domain Name for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2052">**Data\_DstDoc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача для кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2052">**Data\_DstDoc\_FqdnHash -** One-way hash of customer identifiable domain name for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2053">**Data\_DstDoc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2053">**Data\_DstDoc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2054">**Data\_DstDoc\_InitializationScenario –** Звіт про спосіб відкриття кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2054">**Data\_DstDoc\_InitializationScenario -** Records how the destination document was opened</span></span>

  - <span data-ttu-id="1bd6a-2055">**Data\_DstDoc\_IOFlags –** Повідомляє про кешовані позначки для встановлення параметрів запитів відкриття кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2055">**Data\_DstDoc\_IOFlags -** Reports on the cached flags used to set open request options for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2056">**Data\_DstDoc\_IrmRights –** Дії дозволені Політикою Захисту Електронних Даних для застосування до кінцевого документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2056">**Data\_DstDoc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the destination document/user</span></span>

  - <span data-ttu-id="1bd6a-2057">**Data\_DstDoc\_IsIncrementalOpen –** Позначка про інкрементне відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2057">**Data\_DstDoc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2058">**Data\_DstDoc\_IsOcsSupported –** Позначка про спільну підтримку документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2058">**Data\_DstDoc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2059">**Data\_DstDoc\_IsOpeningOfflineCopy –** Позначка про відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2059">**Data\_DstDoc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2060">**Data\_DstDoc\_IsSyncBacked –** Позначка про авто синхронізовану копію документа на комп’ютері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2060">**Data\_DstDoc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2061">**Data\_DstDoc\_Location –** Вказує службу, що надала сховище для кінцевого документа (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2061">**Data\_DstDoc\_Location -** Indicates which service provided the storage for the destination document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-2062">**Data\_DstDoc\_LocationDetails –** Вказує відому папку з локальним документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2062">**Data\_DstDoc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2063">**Data\_DstDoc\_NumberCoAuthors –** Кількість користувачів під час сеансу спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2063">**Data\_DstDoc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2064">**Data\_DstDoc\_PasswordFlags –** Установлені позначки паролю на читання чи читання й записування для кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2064">**Data\_DstDoc\_PasswordFlags -** Indicates read or read/write password flags set for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2065">**Data\_DstDoc\_ReadOnlyReasons –** Причини з яких кінцевий документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2065">**Data\_DstDoc\_ReadOnlyReasons -** Reasons why the destination document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2066">**Data\_DstDoc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2066">**Data\_DstDoc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2067">**Data\_DstDoc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2067">**Data\_DstDoc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2068">**Data\_DstDoc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2068">**Data\_DstDoc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2069">**Data\_DstDoc\_ServerType –** Тип сервера служби (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2069">**Data\_DstDoc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2070">**Data\_DstDoc\_ServerVersion –** Версія сервера, що надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2070">**Data\_DstDoc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2071">**Data\_DstDoc\_SessionId –** Визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2071">**Data\_DstDoc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-2072">**Data\_DstDoc\_SharePointServiceContext –** Діагностичні відомості запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2072">**Data\_DstDoc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2073">**Data\_DstDoc\_SizeInBytes –** Індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2073">**Data\_DstDoc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2074">**Data\_DstDoc\_SpecialChars –** Індикатор спеціальних символів URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2074">**Data\_DstDoc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2075">**Data\_DstDoc\_StreamAvailability –** Індикатор, що вказує доступний чи вимкнений потік документів </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2075">**Data\_DstDoc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2076">**Data\_DstDoc\_SyncBackedType –** Індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2076">**Data\_DstDoc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2077">**Data\_DstDoc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2077">**Data\_DstDoc\_UrlHash -** One-way hash to create a naïve document identifier for the destination document</span></span>

  - <span data-ttu-id="1bd6a-2078">**Data\_DstDoc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2078">**Data\_DstDoc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-2079">**Data\_FailureClass –** Ціле число, що вказує клас відмов для відмов переходу OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2079">**Data\_FailureClass -** Integer representing the failure class for OCS transition failures</span></span>

  - <span data-ttu-id="1bd6a-2080">**Data\_LocationPickerPropagateToSaveTime,spLapsedMsec –** Вимірює час в мілісекундах, що знадобився для збереження після отримання результату у вікні вибору розташування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2080">**Data\_LocationPickerPropagateToSaveTime,spLapsedMsec -** Measure the time, in milliseconds, that it takes for the save to trigger after getting a result from the location picker</span></span>

  - <span data-ttu-id="1bd6a-2081">**Data\_LocationPickerSaveStatus –** Статус повернений засобом вибору розташування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2081">**Data\_LocationPickerSaveStatus -** Status returned by the location picker</span></span>

  - <span data-ttu-id="1bd6a-2082">**Data\_MainPdod –** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2082">**Data\_MainPdod -** The document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2083">**Data\_MoveDisabledReason –** Помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2083">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-2084">**Data\_MoveFlightEnabled –** Вказує чи активовано тестування функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2084">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2085">**Data\_RenameDisabledReason –** Помилка, що скасовує перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2085">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-2086">**Data\_RenameFlightEnabled** – чи активовано тест функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2086">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2087">**Data\_SaveInitiateKind –** Ціле число, що вказує як розпочато збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2087">**Data\_SaveInitiateKind -** Integer that indicates how the save was initiated</span></span>

  - <span data-ttu-id="1bd6a-2088">**Data\_SrcDoc\_AccessMode –** Вихідний документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2088">**Data\_SrcDoc\_AccessMode -** Source Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-2089">**Data\_SrcDoc\_AssistedReadingReasons –** Попередньо визначений набір значень причини відкриття документу в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2089">**Data\_SrcDoc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2090">**Data\_SrcDoc\_ChunkingType –** Одиниці для інкрементного відкриття кінцевого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2090">**Data\_SrcDoc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2091">**Data\_SrcDoc\_EdpState –** Параметр електронного захисту даних вихідного документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2091">**Data\_SrcDoc\_EdpState -** Electronic Data Protection setting for the source document</span></span>

  - <span data-ttu-id="1bd6a-2092">**Data\_SrcDoc\_Ext –** Розширення вихідного документа (docx, xlsb, pptx, тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2092">**Data\_SrcDoc\_Ext -** Document extension for the source document (docx/xlsb/pptx, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2093">**Data\_SrcDoc\_FileFormat –** Версія протоколу формату файлу вихідного документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2093">**Data\_SrcDoc\_FileFormat -** File format protocol version for the source document</span></span>

  - <span data-ttu-id="1bd6a-2094">**Data\_SrcDoc\_Fqdn –** Ім'я домену OneDrive або SharePoint Online для вихідного документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2094">**Data\_SrcDoc\_Fqdn -** OneDrive or SharePoint Online Domain Name for the source document</span></span>

  - <span data-ttu-id="1bd6a-2095">**Data\_SrcDoc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача для вихідного документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2095">**Data\_SrcDoc\_FqdnHash -** One-way hash of customer identifiable domain name for the source document</span></span>

  - <span data-ttu-id="1bd6a-2096">**Data\_SrcDoc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2096">**Data\_SrcDoc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2097">**Data\_SrcDoc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2097">**Data\_SrcDoc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-2098">**Data\_SrcDoc\_IOFlags –** Повідомляє про кешовані позначки для встановлення параметрів запитів відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2098">**Data\_SrcDoc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2099">**Data\_SrcDoc\_IrmRights –** Дії дозволені Політикою Захисту Електронних Даних для застосування до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2099">**Data\_SrcDoc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2100">**Data\_SrcDoc\_IsIncrementalOpen –** Позначка про інкрементне відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2100">**Data\_SrcDoc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2101">**Data\_SrcDoc\_IsOcsSupported –** Позначка про спільну підтримку документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2101">**Data\_SrcDoc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2102">**Data\_SrcDoc\_IsOpeningOfflineCopy –** Позначка про відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2102">**Data\_SrcDoc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2103">**Data\_SrcDoc\_IsSyncBacked –** Позначка про авто синхронізовану копію документа на комп’ютері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2103">**Data\_SrcDoc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2104">**Data\_SrcDoc\_Location –** Вказує службу, що надала вихідний документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2104">**Data\_SrcDoc\_Location -** Indicates which service provided the source document (OneDrive, File Server, SharePoint, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2105">**Data\_SrcDoc\_LocationDetails –** Вказує відому папку з локальним документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2105">**Data\_SrcDoc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2106">**Data\_SrcDoc\_NumberCoAuthors –** Кількість користувачів під час сеансу спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2106">**Data\_SrcDoc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2107">**Data\_SrcDoc\_PasswordFlags –** Установлені позначки паролю на читання чи читання й записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2107">**Data\_SrcDoc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-2108">**Data\_SrcDoc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2108">**Data\_SrcDoc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2109">**Data\_SrcDoc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2109">**Data\_SrcDoc\_ResourceIdHash -** An anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2110">**Data\_SrcDoc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2110">**Data\_SrcDoc\_ServerDocId -** An immutable anonymized document identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2111">**Data\_SrcDoc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2111">**Data\_SrcDoc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2112">**Data\_SrcDoc\_ServerType –** Тип сервера служби (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2112">**Data\_SrcDoc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2113">**Data\_SrcDoc\_ServerVersion –** Версія сервера служби</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2113">**Data\_SrcDoc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2114">**Data\_SrcDoc\_SessionId –** Визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2114">**Data\_SrcDoc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-2115">**Data\_SrcDoc\_SharePointServiceContext –** Діагностичні відомості запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2115">**Data\_SrcDoc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2116">**Data\_SrcDoc\_SizeInBytes –** Індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2116">**Data\_SrcDoc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2117">**Data\_SrcDoc\_SpecialChars –** Індикатор спеціальних символів URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2117">**Data\_SrcDoc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2118">**Data\_SrcDoc\_StreamAvailability –** Індикатор, що вказує доступний чи вимкнений потік документів </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2118">**Data\_SrcDoc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2119">**Data\_SrcDoc\_SyncBackedType –** Індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2119">**Data\_SrcDoc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2120">**Data\_SrcDoc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2120">**Data\_SrcDoc\_UrlHash -** One way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2121">**Data\_SrcDoc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2121">**Data\_SrcDoc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-2122">**Data\_SrcDocIsUnnamedOrNew –** Вказує чи новий документ, що зберігається</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2122">**Data\_SrcDocIsUnnamedOrNew -** Indicates whether the document we are saving is new</span></span>

#### <a name="officewordworddocumentdirtyflagchanged"></a><span data-ttu-id="1bd6a-2123">Office.Word.Word.DocumentDirtyFlagChanged</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2123">Office.Word.Word.DocumentDirtyFlagChanged</span></span>

<span data-ttu-id="1bd6a-2124">Подія, яка вказує на редагування документа, внутрішній стан якого не затверджено, в Office Word.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2124">This event indicates Office Word edits a document which changes the document internal state into "dirty".</span></span> <span data-ttu-id="1bd6a-2125">Так Microsoft може оцінювати стан документа, що редагується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2125">It allows Microsoft to evaluate the feature health of edit-document.</span></span> <span data-ttu-id="1bd6a-2126">Ця подія підтверджує функціонування усіх редагувань користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2126">The event is a heartbeat of user edits.</span></span> <span data-ttu-id="1bd6a-2127">А також, використовується для обчислення щомісячних активних користувачів/пристроїв.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2127">It is also used to calculated monthly active users/devices.</span></span>

<span data-ttu-id="1bd6a-2128">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2128">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2129">**Data\_CollectionTime–** Позначка часу події</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2129">**Data\_CollectionTime-** Timestamp of the event</span></span>

  - <span data-ttu-id="1bd6a-2130">**Data\_DocumentLocation–** Тип розташування документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2130">**Data\_DocumentLocation-** type of the document location</span></span>

  - <span data-ttu-id="1bd6a-2131">**Data\_DocumentLocationDetails–** Підтип розташування документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2131">**Data\_DocumentLocationDetails-** Sub-type of the document location</span></span>

  - <span data-ttu-id="1bd6a-2132">**Data\_FAlwaysSaveEnabled–** Вказує, чи ввімкнуто функцію «Завжди зберігати»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2132">**Data\_FAlwaysSaveEnabled-** Indicates whether always-save was enabled</span></span>

  - <span data-ttu-id="1bd6a-2133">**Data\_FirstEditTime–** Позначка часу першого редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2133">**Data\_FirstEditTime-** Timestamp of first edit</span></span>

  - <span data-ttu-id="1bd6a-2134">**Data\_NumberCoAuthors–** Кількість співавторів, що редагують документ під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2134">**Data\_NumberCoAuthors-** Number of coauthors editing the document during the session</span></span>

  - <span data-ttu-id="1bd6a-2135">**Data\_NumberOfTimesDocumentDirtied–** Кількість внесення змін до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2135">**Data\_NumberOfTimesDocumentDirtied-** Number of edits made to the document</span></span>

  - <span data-ttu-id="1bd6a-2136">**Data\_Pdod–** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2136">**Data\_Pdod-** Document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2137">**Data\_UrlHash–** Гешування шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2137">**Data\_UrlHash-** Hash of the document path</span></span>

  - <span data-ttu-id="1bd6a-2138">**Data\_ViewKind–** Тип подання у Word </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2138">**Data\_ViewKind-** Type of Word view</span></span>

#### <a name="officevisiosharedfeatureexperimentation"></a><span data-ttu-id="1bd6a-2139">Office.Visio.Shared.FeatureExperimentation</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2139">Office.Visio.Shared.FeatureExperimentation</span></span>

<span data-ttu-id="1bd6a-2140">Відстежує тестування для користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2140">Tracks feature flighting for users.</span></span> <span data-ttu-id="1bd6a-2141">Ця подія визначає успішно чи невдало відбулося тестування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2141">This event helps us determines success or failure of feature flights.</span></span>

<span data-ttu-id="1bd6a-2142">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2142">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2143">**Data\_Enable:bool**– Значення true, яке вказує, що функцію активовано для поточного користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2143">**Data\_Enable:bool**- true indicate the feature is enabled for current user</span></span>

  - <span data-ttu-id="1bd6a-2144">**Data\_Feature:string** – Назва функції</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2144">**Data\_Feature:string** - name of the feature</span></span>

  - <span data-ttu-id="1bd6a-2145">**Data\_Flighted:bool** – Значення true, яке вказує, що функцію ввімкнуто</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2145">**Data\_Flighted:bool** - true indicates the feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2146">**Data\_Licensed:bool** – Значення true, яке вказує, що функція підлягає перевірці ліцензування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2146">**Data\_Licensed:bool** - true indicates the feature is under licensing check</span></span>

  - <span data-ttu-id="1bd6a-2147">**Data\_Subscriber:bool** – Значення true, яке вказує, що користувач має ліцензію підписки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2147">**Data\_Subscriber:bool** - true indicates the user has subscription license</span></span>

#### <a name="officevisiosharedrefreshsmartdiagram"></a><span data-ttu-id="1bd6a-2148">Office.Visio.Shared.RefreshSmartDiagram</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2148">Office.Visio.Shared.RefreshSmartDiagram</span></span>

<span data-ttu-id="1bd6a-2149">Свідчить про помилки оновлення схеми під час створення файлу в DV.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2149">Captures diagram refresh failures when file is created through DV.</span></span> <span data-ttu-id="1bd6a-2150">Це налагоджує помилки та проблеми оновлення даних на DV схемі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2150">This helps us debug the failures and issues in data refresh in a DV diagram.</span></span>

<span data-ttu-id="1bd6a-2151">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2151">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2152">**Data\_ConnectorsBasedOnSequence:bool** – Значення true, якщо оновлена схема від самого створення використовувала з'єднувач на основі параметру послідовності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2152">**Data\_ConnectorsBasedOnSequence:bool** - true if the refreshed diagram was originally created using connector based on sequence" option</span></span>

  - <span data-ttu-id="1bd6a-2153">**Data\_DialogError**:**string** – Помилка під час оновлення смарт-схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2153">**Data\_DialogError**:**string** - error during refreshing smart diagram</span></span>

  - <span data-ttu-id="1bd6a-2154">**Data\_FileError:string** – Рядок помилки при недійсному підключені файлу Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2154">**Data\_FileError:string** - error string when connected Excel file is invalid</span></span>

  - <span data-ttu-id="1bd6a-2155">**Data\_OverwriteSelected**:**bool** – Значення true, якщо користувач вибрав перезапис схеми під час оновлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2155">**Data\_OverwriteSelected**:**bool** - true if user selected overwrite diagram option during refresh</span></span>

  - <span data-ttu-id="1bd6a-2156">**Data\_WarningShown**:**bool** – Значення true, якщо виникає будь-яке попередження під час оновлення даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2156">**Data\_WarningShown**:**bool** - true if there was any warning shown to user during data refresh</span></span>

#### <a name="officevisiosharedwritebacktoexcel"></a><span data-ttu-id="1bd6a-2157">Office.Visio.Shared.WritebackToExcel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2157">Office.Visio.Shared.WritebackToExcel</span></span>

<span data-ttu-id="1bd6a-2158">Свідчить про помилки перезапису в Excel під час створення файлу в DV.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2158">Captures Excel write back failures when file is created through DV.</span></span> <span data-ttu-id="1bd6a-2159">Це налагоджує помилки та проблеми оновлення перезапису даних на DV схемі в Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2159">This helps us debug the failures and issues in writing back data to Excel in a DV diagram.</span></span>

<span data-ttu-id="1bd6a-2160">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2160">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2161">**Data\_ConnectorsBasedOnSequence:bool** – Значення true, що з'єднувачі створюються на основі параметрів послідовності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2161">**Data\_ConnectorsBasedOnSequence:bool** - true means connectors are created based on sequence settings</span></span>

  - <span data-ttu-id="1bd6a-2162">**Data\_DataSourceType:string** – Це поле вказує, чи створено схему з «Таблиці» або «Іншого діапазону»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2162">**Data\_DataSourceType:string** - This filed indicates whether diagram is created from  "Table" or "CustomRange"</span></span>

  - <span data-ttu-id="1bd6a-2163">**Data\_DialogError:string** – Спеціальний тип помилки під час створення смарт-схеми через Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2163">**Data\_DialogError:string** - Custom Error type while creating smart diagram through Excel</span></span>

  - <span data-ttu-id="1bd6a-2164">**Data\_NoOfShapesAdded:int** – Кількість доданих фігур під час зворотнього записування до функціоналу Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2164">**Data\_NoOfShapesAdded:int** - Number of shapes added during writeback to Excel functionality</span></span>

  - <span data-ttu-id="1bd6a-2165">**Data\_NoOfShapesDeleted:int** – Кількість видалених фігур під час зворотнього записування до функціоналу Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2165">**Data\_NoOfShapesDeleted:int** - Number of shapes deleted during writeback to Excel functionality</span></span>

  - <span data-ttu-id="1bd6a-2166">**Data\_OverwriteSelected:bool** – Значення true, якщо користувач вибрав перезапис даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2166">**Data\_OverwriteSelected:bool** - true indicate user selected overwrite data option</span></span>

  - <span data-ttu-id="1bd6a-2167">**Data\_SourceDataModified:bool** – Значення true, яке вказує, що вихідні дані змінено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2167">**Data\_SourceDataModified:bool** - true indicates source data is modified</span></span>

  - <span data-ttu-id="1bd6a-2168">**Data\_WarningShown:bool** – Значення true, що попередження про оновлення даних показано користувачу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2168">**Data\_WarningShown:bool** - true means data update warning shown to the user</span></span>

  - <span data-ttu-id="1bd6a-2169">**Data\_WarningShownBecauseOfPresenceOfFormula:bool** – Значення true, яке вказує на попередження користувачів про присутність формули в Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2169">**Data\_WarningShownBecauseOfPresenceOfFormula:bool** - true indicates warning shown to the user because of presence of formula in Excel</span></span>

  - <span data-ttu-id="1bd6a-2170">**Data\_WarningShownToAddNextStepID:bool** – Значення true, яке вказує на попередження користувачів про відсутність ідентифікатора наступного кроку в Excel</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2170">**Data\_WarningShownToAddNextStepID:bool** - true indicates warning show to the user because next step Identifier missing in Excel</span></span>

  - <span data-ttu-id="1bd6a-2171">**Data\_WarningShownToConvertToTable:bool** – Значення true, яке вказує на попередження користувачів про перетворення даних Excel у формат таблиці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2171">**Data\_WarningShownToConvertToTable:bool** - true indicates warning shown to the user to convert Excel data to table format</span></span>

### <a name="application-status-and-boot-subtype"></a><span data-ttu-id="1bd6a-2172">*Стан програми та підтип завантаження*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2172">*Application status and boot subtype*</span></span>

<span data-ttu-id="1bd6a-2173">Визначення, чи сталися події конкретних функцій, таких як запуск або припинення, а також чи працює ця функція.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2173">Determination if specific feature events have occurred, such as start or stop, and if feature is running.</span></span>

#### <a name="officeextensibilityofficejsappactivated"></a><span data-ttu-id="1bd6a-2174">Office.Extensibility.OfficeJS.Appactivated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2174">Office.Extensibility.OfficeJS.Appactivated</span></span>

<span data-ttu-id="1bd6a-2175">Записує відомості про несподівані завершення роботи Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2175">Records information about unexpected shutdowns of Office.</span></span> <span data-ttu-id="1bd6a-2176">Це дає змогу визначити аварійне завершення роботи або зависання продукту, щоб вирішити їх.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2176">This allows us to identify crashes or hangs in the product so that they can be addressed.</span></span>

<span data-ttu-id="1bd6a-2177">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2177">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2178">**Data\_AirspaceInitTime:integer–** час, витрачений, щоб ініціалізувати компонент Airspace office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2178">**Data\_AirspaceInitTime:integer-** time taken to initialize Airspace office component</span></span>

  - <span data-ttu-id="1bd6a-2179">**Data\_AllShapes:integer –** кількість фігур у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2179">**Data\_AllShapes:integer -** number of shapes in the document</span></span>

  - <span data-ttu-id="1bd6a-2180">**Data\_APIInitTime:integer –** час, витрачений, щоб ініціалізувати модуль Visio API</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2180">**Data\_APIInitTime:integer -** time taken to initialize Visio API module</span></span>

  - <span data-ttu-id="1bd6a-2181">**Data\_AppSizeHeight –** Надбудова**-** висоти вікна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2181">**Data\_AppSizeHeight –** Add**-** in window size’s height</span></span>

  - <span data-ttu-id="1bd6a-2182">**Data\_AppSizeWidth –** Надбудова**-** ширини вікна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2182">**Data\_AppSizeWidth –** Add**-** in window size’s width</span></span>

  - <span data-ttu-id="1bd6a-2183">**Data\_AppURL –** URL-адреса надбудови; Журнали URL-адрес надбудов зі сховища та URL-адрес доменів надбудов не зі сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2183">**Data\_AppURL -** URL of the Add in; Logs full URL for Store Add ins and URL domain for non-store Add ins</span></span>

  - <span data-ttu-id="1bd6a-2184">**Data\_AuthorsCount:integer –** кількість авторів, які редагувати документ за поточний сеанс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2184">**Data\_AuthorsCount:integer -** number of authors who edited the document in this session</span></span>

  - <span data-ttu-id="1bd6a-2185">**Data\_BackgroundPages:integer –** кількість фонових сторінок схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2185">**Data\_BackgroundPages:integer -** number of background pages in diagram</span></span>

  - <span data-ttu-id="1bd6a-2186">**Data\_BootTime:integer –** обсяг часу, витрачений на завантаження Visio</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2186">**Data\_BootTime:integer -** The amount of time it took to boot Visio</span></span>

  - <span data-ttu-id="1bd6a-2187">**Data\_Browser –** рядок браузера з відомостями про його тип, версію</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2187">**Data\_Browser -** Browser string with information about the browser such as type, version</span></span>

  - <span data-ttu-id="1bd6a-2188">**Data\_ChildWindowMixedModeTime:integer –** час, витрачений на активацію змішаного режиму Visio (DpiAwareness дочірнього вікна може відрізнятися від батьківського)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2188">**Data\_ChildWindowMixedModeTime:integer -** time taken to enable mixed mode in Visio (Child window can have different DpiAwareness from parent window)</span></span>

  - <span data-ttu-id="1bd6a-2189">**Data\_CommentsCount:integer –** кількість приміток у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2189">**Data\_CommentsCount:integer -** number of comments in document</span></span>

  - <span data-ttu-id="1bd6a-2190">**Data\_ConnectionCount:integer –** кількість підключень до даних схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2190">**Data\_ConnectionCount:integer -** number of data connection in diagram</span></span>

  - <span data-ttu-id="1bd6a-2191">**Data\_ContentMgrInitTim:integer –** час, витрачений, щоб ініціалізувати диспетчер вмісту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2191">**Data\_ContentMgrInitTim:integer -** time taken to initialize content manager</span></span>

  - <span data-ttu-id="1bd6a-2192">**Data\_CreateMainFrameTime:integer –** створення часу мейнфрейму</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2192">**Data\_CreateMainFrameTime:integer -** Create mainframe time</span></span>

  - <span data-ttu-id="1bd6a-2193">**Data\_CreatePaletteTime:integer –** час, щоб створити загальну палітру кольорів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2193">**Data\_CreatePaletteTime:integer -** Time taken to create the global color palette</span></span>

  - <span data-ttu-id="1bd6a-2194">**Data\_DispFormatCount:integer –** кількість графіки даних у схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2194">**Data\_DispFormatCount:integer -** number of data graphics in diagram</span></span>

  - <span data-ttu-id="1bd6a-2195">**Data\_Doc\_Ext:string –** розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2195">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-2196">**Data\_Doc\_Fqdn:string –** місце збереження документа (SharePoint.com, live.net), тільки для доменів у службі Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2196">**Data\_Doc\_Fqdn:string -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-2197">**Data\_Doc\_FqdnHash:string –** геш місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2197">**Data\_Doc\_FqdnHash:string -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-2198">**Data\_Doc\_IsIncrementalOpen:bool–** : чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2198">**Data\_Doc\_IsIncrementalOpen:bool-** : Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-2199">**Data\_Doc\_IsOpeningOfflineCopy:bool –** чи відкривається документ із локального кеша?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2199">**Data\_Doc\_IsOpeningOfflineCopy:bool -** Is document being opened from local cache?</span></span>

  - <span data-ttu-id="1bd6a-2200">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2200">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2201">**Data\_Doc\_IsSyncBacked:bool–** значення true, коли документ на сервері існує локально та синхронізується з сервером (наприклад, через OneDrive або клієнтські програми ODB)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2201">**Data\_Doc\_IsSyncBacked:bool-** true when this is a server document that exists locally, and is synchronized with the server (e.g. through OneDrive or ODB client apps)</span></span>

  - <span data-ttu-id="1bd6a-2202">**Data\_Doc\_Location:long–** : попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2202">**Data\_Doc\_Location:long-** : Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-2203">**Data\_Doc\_LocationDetails:long –** попередньо визначений набір значень більш детального розташування (папка Temp, папка «Завантаження», One Drive Documents, One Drive Pictures)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2203">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures</span></span>

  - <span data-ttu-id="1bd6a-2204">**Data\_Doc\_ResourceIdHash:string –** гешування ідентифікатора ресурсів документів збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2204">**Data\_Doc\_ResourceIdHash:string -** Hash of resource Identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2205">**Data\_Doc\_ServerDocId:string –** незмінний ідентифікатор документів збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2205">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2206">**Data\_Doc\_SessionId:long –** згенерований глобальний унікальний ідентифікатор, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2206">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-2207">**Data\_Doc\_SizeInBytes:long –** розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2207">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-2208">**Data\_Doc\_SpecialChars:long –** велика бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2208">**Data\_Doc\_SpecialChars:long -** long Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2209">**Data\_Doc\_SyncBackedType –** Індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2209">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span> 

  - <span data-ttu-id="1bd6a-2210">**Data\_Doc\_UrlHash:string –** гешування повної URL-адреси документа збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2210">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2211">**Data\_DpiAwarenessTime:integer –** час активації Per Monitor Dpi Awareness</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2211">**Data\_DpiAwarenessTime:integer -** Time taken to enable Per Monitor Dpi Awareness</span></span>

  - <span data-ttu-id="1bd6a-2212">**Data\_DurationToCompleteInMilliseconds:double–** тривалість збереження в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2212">**Data\_DurationToCompleteInMilliseconds:double-** Duration to complete save as in millisecond</span></span>

  - <span data-ttu-id="1bd6a-2213">**Data\_ErrorCode:int –** : 0 при успішному завершенні, ціле число при помилці збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2213">**Data\_ErrorCode:int -** : 0 for success, integer for failure in save</span></span>

  - <span data-ttu-id="1bd6a-2214">**Data\_FailureReason:integer –** причина помилки асинхронного збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2214">**Data\_FailureReason:integer -** failure reason for asynchronous save</span></span>

  - <span data-ttu-id="1bd6a-2215">**Data\_FileExtension –** розширення файлу відкритої схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2215">**Data\_FileExtension -** File extension of diagram opened</span></span>

  - <span data-ttu-id="1bd6a-2216">**Data\_FileHasDGMaster:bool –** значення true, якщо файл має графіки даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2216">**Data\_FileHasDGMaster:bool -** true when file has Data Graphics</span></span>

  - <span data-ttu-id="1bd6a-2217">**Data\_FileHasImportedData:bool –** значення true, якщо файл має імпортовані дані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2217">**Data\_FileHasImportedData:bool -** true when file has imported data</span></span>

  - <span data-ttu-id="1bd6a-2218">**Data\_FileHasShapesLinked:bool –** значення true, якщо файл має зв'язаний з даними фігури</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2218">**Data\_FileHasShapesLinked:bool -** true when file has linked shapes to data</span></span>

  - <span data-ttu-id="1bd6a-2219">**Data\_FileIOBytesRead:int –** загальна кількість прочитаних байтів під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2219">**Data\_FileIOBytesRead:int -** total bytes read while saving</span></span>

  - <span data-ttu-id="1bd6a-2220">**Data\_FileIOBytesReadSquared:int –** квадратне значення Data\_FileIOBytesRead</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2220">**Data\_FileIOBytesReadSquared:int -** squared value of Data\_FileIOBytesRead</span></span>

  - <span data-ttu-id="1bd6a-2221">**Data\_FileIOBytesWritten:int –** загальна кількість записаних байтів під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2221">**Data\_FileIOBytesWritten:int -** total bytes written while saving</span></span>

  - <span data-ttu-id="1bd6a-2222">**Data\_FileIOBytesWrittenSquared:int–** квадратне значення Data\_FileIOBytesWritten</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2222">**Data\_FileIOBytesWrittenSquared:int-** squared value of Data\_FileIOBytesWritten</span></span>

  - <span data-ttu-id="1bd6a-2223">**Data\_FilePathHash:binary** – двійкове гешування шляху до файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2223">**Data\_FilePathHash:binary** -Binary Hash of file path</span></span>

  - <span data-ttu-id="1bd6a-2224">**Data\_FilePathHash: binary** – глобальний унікальний ідентифікатор шляху до файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2224">**Data\_FilePathHash: binary** - GUID for file path</span></span>

  - <span data-ttu-id="1bd6a-2225">**Data\_FileSize –** розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2225">**Data\_FileSize -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-2226">**Data\_ForegroundPages:integer –** кількість сторінок переднього плану на схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2226">**Data\_ForegroundPages:integer -** number of foreground pages in diagram</span></span>

  - <span data-ttu-id="1bd6a-2227">**Data\_ForegroundShapes:integer –** ціле число кількості фігур на сторінках переднього плану</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2227">**Data\_ForegroundShapes:integer -** integer number of shapes in Foreground pages</span></span>

  - <span data-ttu-id="1bd6a-2228">**Data\_GdiInitTime:integer –** час, витрачений, щоб ініціалізувати модуль GDI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2228">**Data\_GdiInitTime:integer -** time taken to initialize GDI module</span></span>

  - <span data-ttu-id="1bd6a-2229">**Data\_HasCoauthUserEdit:bool –** значення true, якщо документ редагували під час сеансу співавторства</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2229">**Data\_HasCoauthUserEdit:bool -** true if document was edited in a coauthoring session</span></span>

  - <span data-ttu-id="1bd6a-2230">**Data\_HasCustomPages:bool –** значення true, якщо документ містить спеціальні сторінки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2230">**Data\_HasCustomPages:bool -** true if document contains custom pages</span></span>

  - <span data-ttu-id="1bd6a-2231">**Data\_HasCustPatterns:bool –** значення true, якщо файл має настроювані шаблони</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2231">**Data\_HasCustPatterns:bool -** true if file has custom patterns</span></span>

  - <span data-ttu-id="1bd6a-2232">**Data\_HasDynConn:bool –** значення true, якщо документ містить динамічне з'єднання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2232">**Data\_HasDynConn:bool -** true if document contains dynamic connection</span></span>

  - <span data-ttu-id="1bd6a-2233">**Data\_HasScaledPages:bool –** значення true, якщо документ містить масштабовані сторінки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2233">**Data\_HasScaledPages:bool -** true if document contains scaled pages</span></span>

  - <span data-ttu-id="1bd6a-2234">**Data\_HasUserWaitTime:bool –** значення true, при відображенні діалогового вікна під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2234">**Data\_HasUserWaitTime:bool -** true when file dialog is shown while saving</span></span>

  - <span data-ttu-id="1bd6a-2235">**Data\_InitAddinsTime:integer –** час, витрачений, щоб ініціалізувати та завантажити COM Add</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2235">**Data\_InitAddinsTime:integer -** time taken to initialize and load the COM Add</span></span>

  - <span data-ttu-id="1bd6a-2236">**Data\_InitBrandTime:integer –** необхідний обсяг часу, щоб ініціалізувати екранну заставку та компоненти фірмової символіки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2236">**Data\_InitBrandTime:integer -** amount of time it takes to initialize splash screen and branding office components</span></span>

  - <span data-ttu-id="1bd6a-2237">**Data\_InitGimmeTime:integer –** час, витрачений, щоб ініціалізувати компонент office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2237">**Data\_InitGimmeTime:integer -** time taken to initialize office component</span></span>

  - <span data-ttu-id="1bd6a-2238">**Data\_InitLicensingTime:integer –** час, витрачений, щоб ініціалізувати ліцензування компонентів office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2238">**Data\_InitLicensingTime:integer -** time taken to initialize licensing office component</span></span>

  - <span data-ttu-id="1bd6a-2239">**Data\_InitMsoUtilsTime:integer –** час ініціалізації MSOUTILS компонентів office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2239">**Data\_InitMsoUtilsTime:integer -** Initialization time to MSOUTILS office component</span></span>

  - <span data-ttu-id="1bd6a-2240">**Data\_InitPerfTime:integer –** час ініціалізації продуктивності компонентів office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2240">**Data\_InitPerfTime:integer -** Performance office component initialization time</span></span>

  - <span data-ttu-id="1bd6a-2241">**Data\_InitTCOTime:integer –** обсяг необхідного часу, щоб ініціалізувати диспетчер компонентів office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2241">**Data\_InitTCOTime:integer -** amount of time it takes to initialize office component manager</span></span>

  - <span data-ttu-id="1bd6a-2242">**Data\_InitTrustCenterTime:integer –** час, витрачений, щоб ініціалізувати центр безпеки та конфіденційності компонентів office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2242">**Data\_InitTrustCenterTime:integer -** Time taken to initialize office component trust center</span></span>

  - <span data-ttu-id="1bd6a-2243">**Data\_InitVSSubSystemsTime:integer –** обсяг необхідного часу, щоб ініціалізувати компоненти Visio</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2243">**Data\_InitVSSubSystemsTime:integer -** amount of time it takes to initialize Visio components</span></span>

  - <span data-ttu-id="1bd6a-2244">**Data\_InternalFile:bool –** значення true, якщо файл є внутрішнім.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2244">**Data\_InternalFile:bool -** true if file is an internal file.</span></span> <span data-ttu-id="1bd6a-2245">Наприклад, Трафарет</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2245">e.g. Stencil</span></span>

  - <span data-ttu-id="1bd6a-2246">**Data\_IsAsyncSave:bool –** значення true, якщо збереження відбулося асинхронно</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2246">**Data\_IsAsyncSave:bool -** true if save was asynchronous</span></span>

  - <span data-ttu-id="1bd6a-2247">**Data\_IsAutoRecoveredFile:bool -** значення true, файл відновився автоматично</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2247">**Data\_IsAutoRecoveredFile:bool -** true if file was auto recovered</span></span>

  - <span data-ttu-id="1bd6a-2248">**Data\_IsEmbedded:bool –** значення true, якщо файл Visio було вбудовано в іншу програму</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2248">**Data\_IsEmbedded:bool -** true if Visio file was embedded in another app</span></span>

  - <span data-ttu-id="1bd6a-2249">**Data\_IsInfinitePageDisabledForAllPages:bool –** якщо вимкнення Infinite Page усіх сторінок документа істина</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2249">**Data\_IsInfinitePageDisabledForAllPages:bool -** if Infinite Page disabled for all pages for the document true</span></span>

  - <span data-ttu-id="1bd6a-2250">**Data\_IsIRMProtected:bool –** значення true, якщо інформаційне право файлу захищено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2250">**Data\_IsIRMProtected:bool -** true if file is Information Right Protected</span></span>

  - <span data-ttu-id="1bd6a-2251">**Data\_IsLocal:bool –** значення true, якщо файл локальний</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2251">**Data\_IsLocal:bool -** true if file is local</span></span>

  - <span data-ttu-id="1bd6a-2252">**Data\_IsRecoverySave:bool –** значення true, якщо збереження спричинено відновленням</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2252">**Data\_IsRecoverySave:bool -** true if safe was triggered because of recovery</span></span>

  - <span data-ttu-id="1bd6a-2253">**Data\_IsShapeSearchPaneHiddenState:bool –** значення true, якщо панель пошуку форм приховано для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2253">**Data\_IsShapeSearchPaneHiddenState:bool -** true if shape search pane was hidden for document</span></span>

  - <span data-ttu-id="1bd6a-2254">**Data\_IsSmartDiagramPresentInActivePageOfFile:bool –** bool, true, якщо візуальна схема смарт-даних існує на активній сторінці файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2254">**Data\_IsSmartDiagramPresentInActivePageOfFile:bool -** bool, true if smart data visual diagram is present in active page of file</span></span>

  - <span data-ttu-id="1bd6a-2255">**Data\_IsSmartDiagramPresentInFile:bool –** bool, true, якщо візуальна схема смарт-даних існує у файлі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2255">**Data\_IsSmartDiagramPresentInFile:bool -** bool, true if the smart data visual diagram present in file.</span></span>

  - <span data-ttu-id="1bd6a-2256">**Data\_IsUNC:bool –** значення true, якщо шлях до документа дотримується Universal Naming Convention</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2256">**Data\_IsUNC:bool -** true if document path is adhering to Universal Naming Convention</span></span>

  - <span data-ttu-id="1bd6a-2257">**Data\_LandscapePgCount:integer –** кількість сторінок з альбомною орієнтацією на схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2257">**Data\_LandscapePgCount:integer -** number of pages having landscape orientation in the diagram</span></span>

  - <span data-ttu-id="1bd6a-2258">**Data\_Layers:integer –** кількість шарів на схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2258">**Data\_Layers:integer -** number of layers in the diagram</span></span>

  - <span data-ttu-id="1bd6a-2259">**Data\_LoadProfileTime:integer –** обсяг часу, необхідного для завантаження профілювальника office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2259">**Data\_LoadProfileTime:integer -** amount of time it takes to load office profiler</span></span>

  - <span data-ttu-id="1bd6a-2260">**Data\_LoadRichEditTim:integer–** час завантаження компоненту редагування форматованого тексту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2260">**Data\_LoadRichEditTim:integer-** rich edit component load time</span></span>

  - <span data-ttu-id="1bd6a-2261">**Data\_LoadVisIntlTime:integer –** час, витрачений на завантаження Visio international DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2261">**Data\_LoadVisIntlTime:integer -** time taken to load Visio international DLL</span></span>

  - <span data-ttu-id="1bd6a-2262">**Data\_Location:integer –** розташування з якого було відкрито файл 0 Local, 1, Network, 2, SharePoint, 3 – Web</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2262">**Data\_Location:integer -** Location of the file from which it was opened 0 Local, 1, Network, 2, SharePoint, 3 – Web</span></span>

  - <span data-ttu-id="1bd6a-2263">**Data\_MasterCount:integer –** кількість зразків на схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2263">**Data\_MasterCount:integer -** number of masters in the diagram</span></span>

  - <span data-ttu-id="1bd6a-2264">**Data\_MaxCoauthUsers:integer –** максимальна кількість користувачів спільного редагування в будь-який момент сеансу Filesystem, Registry, First Party, SDX</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2264">**Data\_MaxCoauthUsers:integer -** maximum number of users coauthoring at any point of time in the session Filesystem, Registry, First Party, SDX</span></span>

  - <span data-ttu-id="1bd6a-2265">**Data\_MaxTilesAutoSizeOn:integer –** максимальна кількість плиток сторінки для яких ввімкнуто автоматичний вибір розміру</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2265">**Data\_MaxTilesAutoSizeOn:integer -** Maximum number of tiles of a page for which auto size was enabled</span></span>

  - <span data-ttu-id="1bd6a-2266">**Data\_MsoBeginBootTime:integer –** час завантаження MSO</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2266">**Data\_MsoBeginBootTime:integer -** MSO boot time</span></span>

  - <span data-ttu-id="1bd6a-2267">**Data\_MsoDllLoadTime:integer –** час, витрачений на завантаження MSO DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2267">**Data\_MsoDllLoadTime:integer -** time taken to load MSO DLL</span></span>

  - <span data-ttu-id="1bd6a-2268">**Data\_MsoEndBootTime:integer –** час, витрачений на завершення завантаження MSO</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2268">**Data\_MsoEndBootTime:integer -** time taken to end MSO boot</span></span>

  - <span data-ttu-id="1bd6a-2269">**Data\_MsoInitCoreTime:integer –** час, витрачений на ініціалізацію компонента MSO office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2269">**Data\_MsoInitCoreTime:integer -** Take taken to initialize MSO office component</span></span>

  - <span data-ttu-id="1bd6a-2270">**Data\_MsoInitUITime:integer –** час, витрачений на ініціалізацію інтерфейсу компонента MSO office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2270">**Data\_MsoInitUITime:integer -** time taken to initialize MSO office component UI</span></span>

  - <span data-ttu-id="1bd6a-2271">**Data\_MsoMigrateTime:integer –** час, витрачений на перенесення настройок користувача під час першого завантаження, якщо користувач оновлює попередню версію</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2271">**Data\_MsoMigrateTime:integer -** Time taken to migrate user settings on first bootup if user upgraded from previous version</span></span>

  - <span data-ttu-id="1bd6a-2272">**Data\_NetworkIOBytesRead:int –** загальна кількість прочитаних байтів мережі під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2272">**Data\_NetworkIOBytesRead:int -** total network bytes read while saving</span></span>

  - <span data-ttu-id="1bd6a-2273">**Data\_NetworkIOBytesReadSquared:int –** квадратне значення Data\_NetworkIOBytesRead</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2273">**Data\_NetworkIOBytesReadSquared:int -** squared value of Data\_NetworkIOBytesRead</span></span>

  - <span data-ttu-id="1bd6a-2274">**Data\_NetworkIOBytesWritten:int –** загальна кількість записаних байтів мережі під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2274">**Data\_NetworkIOBytesWritten:int -** total network bytes written while saving</span></span>

  - <span data-ttu-id="1bd6a-2275">**Data\_NetworkIOBytesWrittenSquared :int–** квадратне значення NetworkIOBytesWritten</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2275">**Data\_NetworkIOBytesWrittenSquared :int-** squared value of NetworkIOBytesWritten</span></span>

  - <span data-ttu-id="1bd6a-2276">**Data\_OartStartupTime:integer –** час, витрачений, щоб ініціалізувати компонент OART office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2276">**Data\_OartStartupTime:integer -** time taken to initialize OART office component</span></span>

  - <span data-ttu-id="1bd6a-2277">**Data\_OleInitTime:integer –** час ініціалізації продуктивності компонентів OLE office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2277">**Data\_OleInitTime:integer -** OLE office component initialization time</span></span>

  - <span data-ttu-id="1bd6a-2278">**Data\_OpenDurationTimeInMs:integer –** тривалість відкриття файлу в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2278">**Data\_OpenDurationTimeInMs:integer -** duration to open file in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2279">**Data\_OriginatedFromTemplateID:integer –** ідентифікатор шаблону з якого була створена схема.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2279">**Data\_OriginatedFromTemplateID:integer -** identifier for template from which diagram was created.</span></span> <span data-ttu-id="1bd6a-2280">Null-значення шаблонів сторонніх постачальників</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2280">NULL for third party templates</span></span>

  - <span data-ttu-id="1bd6a-2281">**Data\_Pages:integer –** кількість сторінок у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2281">**Data\_Pages:integer -** number of pages in document</span></span>

  - <span data-ttu-id="1bd6a-2282">**Data\_PositionToolbarsTime:integer –** час, витрачений, щоб встановити панелі інструментів на місце</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2282">**Data\_PositionToolbarsTime:integer -** time taken to get the toolbars into place</span></span>

  - <span data-ttu-id="1bd6a-2283">**Data\_ReadOnly:bool –** значення True, якщо файл лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2283">**Data\_ReadOnly:bool -** True if the file is read only</span></span>

  - <span data-ttu-id="1bd6a-2284">**Data\_RecordSetCount:integer –** кількість наборів записів на схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2284">**Data\_RecordSetCount:integer -** number of record set in the diagram</span></span>

  - <span data-ttu-id="1bd6a-2285">**Data\_RecoveryTime:integer –** час, витрачений на відкриття файлів відновлення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2285">**Data\_RecoveryTime:integer -** time taken to open recovery files</span></span>

  - <span data-ttu-id="1bd6a-2286">**Data\_ReviewerPages:integer –** кількість сторінок рецензента у схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2286">**Data\_ReviewerPages:integer -** number of reviewer pages in diagram</span></span>

  - <span data-ttu-id="1bd6a-2287">**Data\_RibbonTime:integer –** час, витрачений, щоб відобразити рядок стану</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2287">**Data\_RibbonTime:integer -** time taken to display the status bar</span></span>

  - <span data-ttu-id="1bd6a-2288">**Data\_RoamingSettingsStartupTime:integer –** час, витрачений на створення та завантаження усіх наразі переміщених параметрів Visio</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2288">**Data\_RoamingSettingsStartupTime:integer -** time taken create and load all currently roamed Visio settings</span></span>

  - <span data-ttu-id="1bd6a-2289">**Data\_SchemeMgrStartupTime:integer –** час, витрачений, щоб ініціалізувати менеджер схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2289">**Data\_SchemeMgrStartupTime:integer -** time taken to initialize scheme manager</span></span>

  - <span data-ttu-id="1bd6a-2290">**Data\_SDX\_AssetId –** тільки для надбудов зі сховища. OMEX надає надбудові у сховищі ідентифікатор ресурсу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2290">**Data\_SDX\_AssetId -** ONLY exists for store Add- ins. OMEX gives the Add in an AssetId when it goes into Store</span></span>

  - <span data-ttu-id="1bd6a-2291">**Data\_SDX\_BrowserToken –** ідентифікатор з кешу браузера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2291">**Data\_SDX\_BrowserToken -** Identifier that sits in the browser's cache</span></span>

  - <span data-ttu-id="1bd6a-2292">**Data\_SDX\_HostJsVersion –** особлива версія платформи Office.js (наприклад outlook web16.01.js),що містить API поверхні для надбудов</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2292">**Data\_SDX\_HostJsVersion -** This is the platform specific version of Office.js (e.g. outlook web16.01.js) This contains the API surface for ad ins</span></span>

  - <span data-ttu-id="1bd6a-2293">**Data\_SDX\_Id –** глобальний унікальний ідентифікатор надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2293">**Data\_SDX\_Id -** The GUID of an Add in which uniquely identifies it</span></span>

  - <span data-ttu-id="1bd6a-2294">**Data\_SDX\_InstanceId –** позначає пару документа надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2294">**Data\_SDX\_InstanceId -** Represents Add in document pair</span></span>

  - <span data-ttu-id="1bd6a-2295">**Data\_SDX\_MarketplaceType –** вказує звідки інстальовано надбудову</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2295">**Data\_SDX\_MarketplaceType -** Indicates where the Add in installed from</span></span>

  - <span data-ttu-id="1bd6a-2296">**Data\_SDX\_OfficeJsVersion –** версія Office.js, що переспрямує до необхідної версії платформи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2296">**Data\_SDX\_OfficeJsVersion -** This is the version of Office.js which will redirect to the platform specific version.</span></span>

  - <span data-ttu-id="1bd6a-2297">**Data\_SDX\_Version –** версія надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2297">**Data\_SDX\_Version -** Version of the Add in</span></span>

  - <span data-ttu-id="1bd6a-2298">**Data\_ShellCmdLineTime:integer –** час, витрачений на аналіз і виконання будь-якої команди операційної системи з командного рядка </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2298">**Data\_ShellCmdLineTime:integer -** time taken to Parse and execute any shell commands on the command line</span></span>

  - <span data-ttu-id="1bd6a-2299">**Data\_Size:long** – розмір файлу в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2299">**Data\_Size:long** - File size in bytes</span></span>

  - <span data-ttu-id="1bd6a-2300">**Data\_StartEndTransactionTime:integer –** час, витрачений, щоб ініціалізувати компоненти Visio</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2300">**Data\_StartEndTransactionTime:integer -** time taken to initialize Visio components</span></span>

  - <span data-ttu-id="1bd6a-2301">**Data\_STNInitTime:integer –** час, витрачений, щоб ініціалізувати конфігурацію «Вікно» трафарету </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2301">**Data\_STNInitTime:integer -** time taken to initialize stencil window configuration</span></span>

  - <span data-ttu-id="1bd6a-2302">**Data\_Tag:string –** унікальний ідентифікатор «Зберегти як» події</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2302">**Data\_Tag:string -** unique identifier to identify Save As event</span></span>

  - <span data-ttu-id="1bd6a-2303">**Data\_ThemeCount:integer –** кількість тем у схемі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2303">**Data\_ThemeCount:integer -** number of themes in diagram</span></span>

  - <span data-ttu-id="1bd6a-2304">**Data\_TimeStamp –** позначка часу закриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2304">**Data\_TimeStamp -** Time stamp when document was closed</span></span>

  - <span data-ttu-id="1bd6a-2305">**Data\_UIInitTime:integer –** час ініціалізації інтерфейсу користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2305">**Data\_UIInitTime:integer -** UI initialization time</span></span>

  - <span data-ttu-id="1bd6a-2306">**Data\_WasSuccessful:bool –** значення true, якщо «Зберегти як» виконано успішно</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2306">**Data\_WasSuccessful:bool -** true if save as was successful</span></span>

  - <span data-ttu-id="1bd6a-2307">**Data\_WinLaunchTime:integer –** час запуску Visio startup pane тощо</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2307">**Data\_WinLaunchTime:integer -** time taken to launch the Visio startup pane, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2308">**Office.Visio.FileCharacteristicsVisio –** записує властивості файлу під час завантаження для Visio C2R і Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2308">**Office.Visio.FileCharacteristicsVisio -** Captures file properties at the time of file boot for Visio C2R and Dev16.</span></span> <span data-ttu-id="1bd6a-2309">Ця подія допомагає класифікувати та виправити помилки властивостей документа, що сприяє швидкому визначенню основних причин проблеми та її вирішенню.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2309">This event helps us to categorize and debug errors about document properties, which in turn enables us root cause issues faster and fix it for customer satisfaction.</span></span>

  - <span data-ttu-id="1bd6a-2310">**Office.Visio.Shared.BootStats –** записує час завантаження Visio Win32.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2310">**Office.Visio.Shared.BootStats -** This event collects boot time for Visio Win32 app.</span></span> <span data-ttu-id="1bd6a-2311">Збираються різні поля для завантаження різноманітних компонентів, як-от час завантаження стрічки, час ініціалізації програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2311">It collects various fields for boot of various components like Ribbon load time, App Initialization time.</span></span> <span data-ttu-id="1bd6a-2312">Ця подія вимірює продуктивність часу завантаження Visio.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2312">This event is used to measure Boot perf for Visio.</span></span>

  - <span data-ttu-id="1bd6a-2313">**Office.Visio.Shared.FileOpen –** записує статистику відкриття файлу для Visio.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2313">**Office.Visio.Shared.FileOpen -** This event collects File open stats for Visio.</span></span> <span data-ttu-id="1bd6a-2314">Ця подія використовується для моніторингу Успіху/Помилки відкриття файлу та зіставляє його з бажаними властивостями розміру файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2314">This event is used to monitor file open Success/ Fail rates and maps it with few properties of like file size.</span></span> <span data-ttu-id="1bd6a-2315">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2315">File properties enable us debug and root cause issues faster.</span></span>

  - <span data-ttu-id="1bd6a-2316">**Office.Visio.Shared.Filesave –** записує статистику збереження файлу для Visio.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2316">**Office.Visio.Shared.Filesave -** This event collects File save stats for Visio.</span></span> <span data-ttu-id="1bd6a-2317">Ця подія використовується для моніторингу Успіху/Помилки збереження файлу та зіставляє його з бажаними властивостями розміру та розташування (наприклад, у хмарі/локально).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2317">This event is used to monitor file save Success/ Fail rates and maps it with few properties of like file size and location it is being saved to e.g. cloud/local.</span></span> <span data-ttu-id="1bd6a-2318">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2318">File properties enable us debug and root cause issues faster.</span></span>

  - <span data-ttu-id="1bd6a-2319">**Office.Visio.Shared.FilesaveAs –** записує статистику «Зберегти як» для Visio.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2319">**Office.Visio.Shared.FilesaveAs -** This event collects File save as stats for Visio.</span></span> <span data-ttu-id="1bd6a-2320">Ця подія використовується для моніторингу Успіху/Помилки збереження файлу та зіставляє його з бажаними властивостями розміру та розташування (наприклад, у хмарі/локально).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2320">This event is used to monitor file save Success/ Fail rates and maps it with few properties of like file size and location it is being saved to, e.g. cloud/local.</span></span> <span data-ttu-id="1bd6a-2321">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2321">File properties enable us debug and root cause issues faster.</span></span>

  - <span data-ttu-id="1bd6a-2322">**Office.Visio.Shared.PostSave –** ця подія записує причину помилки збереження файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2322">**Office.Visio.Shared.PostSave -** This event captures failure reason for failure in file save.</span></span>

  - <span data-ttu-id="1bd6a-2323">**Office.Visio.VisioFileSaveAs –** записує статистику «Зберегти як» для Visio Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2323">**Office.Visio.VisioFileSaveAs -** This event collects File save as stats for Visio Dev16.</span></span> <span data-ttu-id="1bd6a-2324">Ця подія використовується для моніторингу Успіху/Помилки команди файлу «Зберегти як» та зіставляє це з бажаними властивостями розміру та розташування файлу (наприклад, у хмарі/локально).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2324">This event is used to monitor file save as Success/ Fail rates and maps it with few properties of like file size and location that it is being saved to, e.g. cloud/local.</span></span> <span data-ttu-id="1bd6a-2325">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2325">File properties enable us debug and root cause issues faster.</span></span>

  - <span data-ttu-id="1bd6a-2326">**Office.Visio.VisioFileSaveAsync –** записує статистику асинхронного збереження файлу для Visio Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2326">**Office.Visio.VisioFileSaveAsync -** This event collects File save async stats for Visio Dev16.</span></span> <span data-ttu-id="1bd6a-2327">Ця подія використовується для моніторингу Успіху/Помилки асинхронного збереження файлу та зіставляє його з бажаними властивостями розміру та розташування (наприклад, у хмарі/локально).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2327">This event is used to monitor file save async Success/ Fail rates and maps it with few properties of like file size and location that it is being saved to e.g., cloud/local.</span></span> <span data-ttu-id="1bd6a-2328">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2328">File properties enable us debug and root cause issues faster.</span></span>

  - <span data-ttu-id="1bd6a-2329">**Office.Visio.VisioFileSaveSync –** записує статистику синхронного збереження файлу для Visio Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2329">**Office.Visio.VisioFileSaveSync -** This event collects File save sync stats for Visio Dev16.</span></span> <span data-ttu-id="1bd6a-2330">Ця подія використовується для моніторингу Успіху/Помилки синхронного збереження файлу та зіставляє його з бажаними властивостями розміру та розташування (наприклад, у хмарі/локально).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2330">This event is used to monitor file save sync Success/ Fail rates and maps it with few properties of like file size and location that it is being saved to e.g., cloud/local.</span></span> <span data-ttu-id="1bd6a-2331">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2331">File properties enable us debug and root cause issues faster.</span></span> <span data-ttu-id="1bd6a-2332">Ця подія допомагає відстежувати причини помилки збереження файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2332">This event helps us monitor save failure reasons for a file.</span></span>

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a><span data-ttu-id="1bd6a-2333">Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2333">Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation</span></span>

<span data-ttu-id="1bd6a-2334">Записує PUID користувача та ідентифікатор клієнта за сеанс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2334">Collects the user PUID and Tenant Identifier once per session.</span></span> <span data-ttu-id="1bd6a-2335">Взаємозв'язок PUID і клієнта необхідні для розуміння та діагностики проблем Outlook на рівні клієнта.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2335">The correlation of PUID and Tenant are necessary to understand and diagnose Outlook issues on a per-tenant basis.</span></span>

<span data-ttu-id="1bd6a-2336">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2336">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2337">**CollectionTime** – Позначка часу події</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2337">**CollectionTime** - Timestamp of the event</span></span>

  - <span data-ttu-id="1bd6a-2338">**ConnId** – ідентифікатор підключення: ідентифікатор підключення, що аналізує PUID й OMS ідентифікатор клієнта</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2338">**ConnId** - Connection Identifier: Identifier of the connection parsing out PUID and OMS tenant Identifier</span></span>

  - <span data-ttu-id="1bd6a-2339">**OMSTenantId** – унікальний ідентифікатор клієнта створений Microsoft</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2339">**OMSTenantId** – Microsoft-generated Unique identifier of Tenant</span></span>

  - <span data-ttu-id="1bd6a-2340">**PUID** – замінює PUID для унікальної ідентифікації користувачів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2340">**PUID** - Exchange's PUID to uniquely identify users</span></span>

#### <a name="officepowerpointpptdesktopbootime"></a><span data-ttu-id="1bd6a-2341">Office.PowerPoint.PPT.Desktop.Bootime</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2341">Office.PowerPoint.PPT.Desktop.Bootime</span></span>

<span data-ttu-id="1bd6a-2342">Записує завантаження PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2342">Collecting how PowerPoint is booted.</span></span> <span data-ttu-id="1bd6a-2343">Це включає завантаження PowerPoint у безпечному поданні, у режимі читання з підтримкою, з макросів, з друку, нового та пустого документа, з відновлення документів, автоматизації та «Office умить».</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2343">It includes boot PowerPoint in protected view, in assisted reading mode, from Macro, print, new and blank document, document recovery, from automation and if it is click- to-run.</span></span> <span data-ttu-id="1bd6a-2344">Також записується скільки часу займає завантаження PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2344">It also collects how long it takes PowerPoint to boot.</span></span> <span data-ttu-id="1bd6a-2345">Ці важливі дані гарантують, що PowerPoint працює належним чином під час завантаження у різних режимах.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2345">This data is critical to guarantee PowerPoint performs well when booted from different modes.</span></span> <span data-ttu-id="1bd6a-2346">Корпорація Майкрософт використовує ці дані, щоб виявити довгий час завантаження PowerPoint у різних режимах.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2346">Microsoft uses this data to catch long booting time when opening PowerPoint from different modes.</span></span>

<span data-ttu-id="1bd6a-2347">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2347">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2348">**AssistedReading –** у режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2348">**AssistedReading -** in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2349">**Автоматизація –** з автоматизації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2349">**Automation -** from automation</span></span>

  - <span data-ttu-id="1bd6a-2350">**Benchmark –** запуск тестування продуктивності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2350">**Benchmark -** run performance benchmark</span></span>

  - <span data-ttu-id="1bd6a-2351">**Blank –** пустий документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2351">**Blank -** blank document</span></span>

  - <span data-ttu-id="1bd6a-2352">**BootTime –** час завантаження сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2352">**BootTime -** session boot time</span></span>

  - <span data-ttu-id="1bd6a-2353">**Embedding –** вбудовування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2353">**Embedding -** embedding document</span></span>

  - <span data-ttu-id="1bd6a-2354">**IsC2R –** технологія «Office умить»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2354">**IsC2R -** is click-to-run</span></span>

  - <span data-ttu-id="1bd6a-2355">**IsNew –** новий документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2355">**IsNew -** new document</span></span>

  - <span data-ttu-id="1bd6a-2356">**IsOpen –** відкритий</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2356">**IsOpen -** is open</span></span>

  - <span data-ttu-id="1bd6a-2357">**Macro1 –** виконання макросу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2357">**Macro1 -** run Macro</span></span>

  - <span data-ttu-id="1bd6a-2358">**Macro2 –** виконання макросу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2358">**Macro2 -** run Macro</span></span>

  - <span data-ttu-id="1bd6a-2359">**NonStandardSpaceInCmdLine** – нестандартний простір у командному рядку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2359">**NonStandardSpaceInCmdLine** – there is non-standard space in command line</span></span>

  - <span data-ttu-id="1bd6a-2360">**Print –** друк документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2360">**Print -** print document</span></span>

  - <span data-ttu-id="1bd6a-2361">**PrintDialog –** друк документа через діалогове вікно</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2361">**PrintDialog -** print document with dialog</span></span>

  - <span data-ttu-id="1bd6a-2362">**PrintPrinter –** друк документа через принтер</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2362">**PrintPrinter -** print document with printer</span></span>

  - <span data-ttu-id="1bd6a-2363">**ProtectedView –** у безпечному поданні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2363">**ProtectedView -** in protected view</span></span>

  - <span data-ttu-id="1bd6a-2364">**RegServer –** реєстрація PowerPoint як сервера COM</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2364">**Regserver -** Register PowerPoint as a COM server</span></span>

  - <span data-ttu-id="1bd6a-2365">**Restore –** відновлення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2365">**Restore -** restore document</span></span>

  - <span data-ttu-id="1bd6a-2366">**Show –** відображення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2366">**Show -** show document</span></span>

  - <span data-ttu-id="1bd6a-2367">**Time –** час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2367">**Time -** session time</span></span>

  - <span data-ttu-id="1bd6a-2368">**UnprotectedView –** у незахищеному поданні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2368">**UnprotectedView -** in unprotected view</span></span>

#### <a name="officepowerpointppthasuserediteddocument"></a><span data-ttu-id="1bd6a-2369">Office.PowerPoint.PPT.HasUserEditedDocument</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2369">Office.PowerPoint.PPT.HasUserEditedDocument</span></span>

<span data-ttu-id="1bd6a-2370">Збираються під час запуску редагування документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2370">Collected when a user starts editing a document.</span></span> <span data-ttu-id="1bd6a-2371">Корпорація Майкрософт використовує ці дані для підрахунку активних користувачів, які редагували документ PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2371">Microsoft uses this data to calculate active users who edited a PowerPoint document</span></span>

<span data-ttu-id="1bd6a-2372">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2372">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2373">**CorrelationId** – ідентифікатор кореляції документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2373">**CorrelationId** – document Correlation Identifier</span></span>

#### <a name="officeprojectbootandopenproject"></a><span data-ttu-id="1bd6a-2374">Office.Project.BootAndOpenProject</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2374">Office.Project.BootAndOpenProject</span></span>

<span data-ttu-id="1bd6a-2375">Project завантажується при відкритті файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2375">Project is booted by opening a file.</span></span> <span data-ttu-id="1bd6a-2376">Ця подія вказує на те, що користувач відкривав Office Project з пов'язаним файлом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2376">This event indicates that a user has opened Office Project with an associated file.</span></span> <span data-ttu-id="1bd6a-2377">Вона містить важливі для успіху дані, що Project може почати й завантажити файл.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2377">It contains critical success data of making sure Project can start and load a file.</span></span>

<span data-ttu-id="1bd6a-2378">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2378">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2379">**Data\_AlertTime –** час активності діалогового вікна завантаження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2379">**Data\_AlertTime -** The amount of time the boot dialog was active.</span></span>

  - <span data-ttu-id="1bd6a-2380">**Data\_BootTime –** обсяг часу, витрачений на завантаження Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2380">**Data\_BootTime -** The amount of time it took to boot Project</span></span>

  - <span data-ttu-id="1bd6a-2381">**Data\_CacheFileSize –** розмір файлу, якщо він кешований</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2381">**Data\_CacheFileSize -** If the file was cached, the size of the file</span></span>

  - <span data-ttu-id="1bd6a-2382">**Data\_EntDocType –** тип відкритого файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2382">**Data\_EntDocType -** The type of file that was opened</span></span>

  - <span data-ttu-id="1bd6a-2383">**Data\_IsInCache –** чи кешований відкритий файл</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2383">**Data\_IsInCache -** Whether the file opened was cached</span></span>

  - <span data-ttu-id="1bd6a-2384">**Data\_LoadSRAs –** чи хоче користувач завантажити SRAs</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2384">**Data\_LoadSRAs -** If the user wants to load SRAs or not</span></span>

  - <span data-ttu-id="1bd6a-2385">**Data\_Outcome –** загальний час завантаження та відкриття файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2385">**Data\_Outcome -** Total boot and file open time.</span></span>

  - <span data-ttu-id="1bd6a-2386">**Data\_OpenFromDocLib –** чи з бібліотеки документів відкритий файл Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2386">**Data\_OpenFromDocLib -** If the Project file opened was from the document library</span></span>

  - <span data-ttu-id="1bd6a-2387">**Data\_ProjectServerVersion –** поточна версія та збірка Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2387">**Data\_ProjectServerVersion -** The version and build that Project is currently on</span></span>

#### <a name="officeprojectbootproject"></a><span data-ttu-id="1bd6a-2388">Office.Project.BootProject</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2388">Office.Project.BootProject</span></span>

<span data-ttu-id="1bd6a-2389">Project завантажується без відкриття файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2389">Project is booted without opening a file.</span></span> <span data-ttu-id="1bd6a-2390">Ця подія вказує на те, що користувач відкривав Office Project без пов'язаного файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2390">This event indicates that a user has opened Office Project without an associated file.</span></span> <span data-ttu-id="1bd6a-2391">Вона містить важливі для успіху дані, що Project може розпочати роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2391">It contains critical success data of making sure Project can start.</span></span>

<span data-ttu-id="1bd6a-2392">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2392">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2393">**Data\_BootTime –** обсяг часу, витрачений на завантаження Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2393">**Data\_BootTime -** The amount of time it took to boot Project</span></span>

  - <span data-ttu-id="1bd6a-2394">**Data\_FileLoaded –** значення False, якщо відкриття ззовні або нового пустого проекту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2394">**Data\_FileLoaded -** False if opening from out-space or new blank project</span></span>

  - <span data-ttu-id="1bd6a-2395">**Data\_IsEntOfflineWithProfile –** якщо користувачі працюють через професійний обліковий номер без підключення до сервера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2395">**Data\_IsEntOfflineWithProfile -** If the users are in the professional SKU and not connected to the server</span></span>

  - <span data-ttu-id="1bd6a-2396">**Data\_IsEntOnline –** якщо сеанс Project підключено до серверу з корпоративною функцією</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2396">**Data\_IsEntOnline -** If the session of Project is connected to a Project server with enterprise features</span></span>

  - <span data-ttu-id="1bd6a-2397">**Data\_IsLocalProfile –** якщо Project сеанс підключено до серверу з корпоративною функцією</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2397">**Data\_IsLocalProfile -** If the Project session is connected to a Project server with enterprise features</span></span>

  - <span data-ttu-id="1bd6a-2398">**Data\_ProjectServerVersion –** поточна версія та збірка Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2398">**Data\_ProjectServerVersion -** The version and build that Project is currently on</span></span>

#### <a name="officepowerpointdocoperationopen"></a><span data-ttu-id="1bd6a-2399">Office.PowerPoint.DocOperation.Open</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2399">Office.PowerPoint.DocOperation.Open</span></span> 

<span data-ttu-id="1bd6a-2400">Збираються щоразу, як програма PowerPoint відкриває файл.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2400">Collected whenever PowerPoint opens a file.</span></span> <span data-ttu-id="1bd6a-2401">Містить відомості успіху, дані про помилки, показники продуктивності та основні відомості про файл, включно з типом формату та метаданими документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2401">Contains success information, failure details, performance metrics, and basic details about the file including file format type and document metadata.</span></span> <span data-ttu-id="1bd6a-2402">Ці відомості необхідні, щоб забезпечити можливість PowerPoint відкривати успішно файли без зниження продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2402">This information is necessary to ensure PowerPoint can open files successfully with no degradation in performance.</span></span> <span data-ttu-id="1bd6a-2403">Це дає змогу діагностувати будь-які проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2403">It allows us to diagnose any problems we discover.</span></span>

<span data-ttu-id="1bd6a-2404">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2404">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2405">**Data\_AddDocTelemetryResult –** чи має запис журналу всі необхідні телеметрії документа (Data\_Doc\_\* fields)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2405">**Data\_AddDocTelemetryResult -** Does this log entry have all necessary document telemetry (Data\_Doc\_\* fields)</span></span>

  - <span data-ttu-id="1bd6a-2406">**Data\_AddDocumentToMruList –** тривалість виконання методу AddDocumentToMruList</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2406">**Data\_AddDocumentToMruList -** Method AddDocumentToMruList execution duration</span></span>

  - <span data-ttu-id="1bd6a-2407">**Data\_AlreadyOpened –** чи відкривався документ раніше (в межах сеансу)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2407">**Data\_AlreadyOpened -** Was this document previously opened (within the context of same process session)</span></span>

  - <span data-ttu-id="1bd6a-2408">**Data\_AntiVirusScanMethod –** попередньо визначений набір значень типів сканування антивірусом (IOAV, AMSI, тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2408">**Data\_AntiVirusScanMethod -** Predefined set of values of type of anti-virus scanned (IOAV, AMSI, None etc.)</span></span>

  - <span data-ttu-id="1bd6a-2409">**Data\_AntiVirusScanStatus –** попередньо визначений набір значень сканування антивірусом кожного документа (NoThreatsDetected, Failed, MalwareDetected тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2409">**Data\_AntiVirusScanStatus -** Predefined set of values of anti-virus scan that happens for every document opened (NoThreatsDetected, Failed, MalwareDetected, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2410">**Data\_AsyncOpenKind –** попередньо визначений набір значень асинхронних параметрів (Collab, ServerOnly, SyncBacked, NotAsync)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2410">**Data\_AsyncOpenKind -** Predefined set of values of async options (Collab, ServerOnly, SyncBacked, NotAsync)</span></span>

  - <span data-ttu-id="1bd6a-2411">**Data\_CancelBackgroundDownloadHr –** чи переривалось завантаження документа?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2411">**Data\_CancelBackgroundDownloadHr -** Was downloading of document interrupted?</span></span> <span data-ttu-id="1bd6a-2412">Якщо так, який результат переривання?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2412">If yes, what was the result of interruption?</span></span>

  - <span data-ttu-id="1bd6a-2413">**Data\_CheckForAssistedReadingReasons –** тривалість виконання методу CheckForAssistedReadingReasons в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2413">**Data\_CheckForAssistedReadingReasons -** Method CheckForAssistedReadingReasons execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2414">**Data\_CheckForDisabledDocument –** тривалість виконання CheckForDisabledDocument методу в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2414">**Data\_CheckForDisabledDocument -** Method CheckForDisabledDocument execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2415">**Data\_CheckForExistingDocument –** тривалість виконання CheckForExistingDocument методу в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2415">**Data\_CheckForExistingDocument -** Method CheckForExistingDocument execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2416">**Data\_CheckIncOpenResult –** тривалість виконання методу CheckIncOpenResult в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2416">**Data\_CheckIncOpenResult -** Method CheckIncOpenResult execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2417">**Data\_CheckLambdaResult –** тривалість виконання методу CheckLambdaResult в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2417">**Data\_CheckLambdaResult -** Method CheckLambdaResult execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2418">**Data\_CheckPackageForRequiredParts –** тривалість виконання методу CheckPackageForRequiredParts в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2418">**Data\_CheckPackageForRequiredParts -** Method CheckPackageForRequiredParts execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2419">**Data\_CheckPackageForSpecialCases –** тривалість виконання методу CheckPackageForSpecialCases в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2419">**Data\_CheckPackageForSpecialCases -** Method CheckPackageForSpecialCases execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2420">**Data\_CheckRequiredPartsLoaded –** тривалість виконання методу CheckRequiredPartsLoaded в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2420">**Data\_CheckRequiredPartsLoaded -** Method CheckRequiredPartsLoaded execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2421">**Data\_CheckWebSharingViolationForIncOpen –** тривалість виконання методу CheckWebSharingViolationForIncOpen в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2421">**Data\_CheckWebSharingViolationForIncOpen -** Method CheckWebSharingViolationForIncOpen execution duration in milliseconds</span></span>
   
  - <span data-ttu-id="1bd6a-2422">\*\*Data_CloseAndReopenWithoutDiscard – \*\*чи було закрито, а потім знову відкрито документ у процесі відкриття без скасування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2422">**Data_CloseAndReopenWithoutDiscard –** Whether a document was closed and reopened during the open process without discarding.</span></span>

  - <span data-ttu-id="1bd6a-2423">**Data\_ContentTransaction –** попередньо визначений набір значень умов створення транзакцій (AllowedOnLoadDocument, AllowedOnOpenComplete тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2423">**Data\_ContentTransaction -** Predefined set of values of when transaction can be created (AllowedOnLoadDocument, AllowedOnOpenComplete, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2424">**Data_CorrelationId –** GUID, переданий процесом ProtocolHandler до програми PowerPoint для узгодження телеметрії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2424">**Data_CorrelationId -** A GUID passed to PowerPoint by ProtocolHandler for correlating telemetry.</span></span> <span data-ttu-id="1bd6a-2425">ProtocolHandler – це окремий процес, який обробляє зв'язки Office для ОС.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2425">ProtocolHandler is a separate process which handles Office links for the OS.</span></span>

  - <span data-ttu-id="1bd6a-2426">**Data\_CppUncaughtExceptionCount:long –** власні необроблені винятки впродовж активності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2426">**Data\_CppUncaughtExceptionCount:long -** Uncaught native exceptions while activity was running</span></span>

  - <span data-ttu-id="1bd6a-2427">**Data\_CreateDocumentTimeMS –** тривалість виконання методу CreateDocumentTimeMS в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2427">**Data\_CreateDocumentTimeMS -** Method CreateDocumentTimeMS execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2428">**Data\_CreateDocumentToken –** тривалість виконання методу CreateDocumentToken в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2428">**Data\_CreateDocumentToken -** Method CreateDocumentToken execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2429">**Data\_CreateDocumentToW –** тривалість виконання методу CreateDocumentToW в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2429">**Data\_CreateDocumentToW -** Method CreateDocumentToW execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2430">**Data\_CreateDocWindow –** тривалість виконання методу CreateDocWindow в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2430">**Data\_CreateDocWindow -** Method CreateDocWindow execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2431">**Data\_CreateLocalTempFile –** тривалість виконання методу CreateLocalTempFile в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2431">**Data\_CreateLocalTempFile -** Method CreateLocalTempFile execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2432">**Data\_DetachedDuration:long –** час під час якого активність була від'єднана/не працювала</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2432">**Data\_DetachedDuration:long -** Time for which Activity was detached/not running</span></span>

  - <span data-ttu-id="1bd6a-2433">**Data\_DetermineFileType –** тривалість виконання методу DetermineFileType в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2433">**Data\_DetermineFileType -** Method DetermineFileType execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2434">**Data\_Doc\_AccessMode:long –** спосіб відкриття документа (лише читання/читання й записування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2434">**Data\_Doc\_AccessMode:long -** How was this document opened (Read only / read write)</span></span>

  - <span data-ttu-id="1bd6a-2435">**Data\_Doc\_AssistedReadingReasons:long –** попередньо визначений набір значень причини відкриття документу в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2435">**Data\_Doc\_AssistedReadingReasons:long -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2436">**Data\_Doc\_ChunkingType:long –** як документ зберігається в SharePoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2436">**Data\_Doc\_ChunkingType:long -** How is document stored in SharePoint</span></span>

  - <span data-ttu-id="1bd6a-2437">**Data\_Doc\_EdpState:long –** захист корпоративних даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2437">**Data\_Doc\_EdpState:long -** Enterprise Data Protection state of document</span></span>

  - <span data-ttu-id="1bd6a-2438">**Data\_Doc\_Ext:string –** розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2438">**Data\_Doc\_Ext:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-2439">**Data\_Doc\_Extension:string –** розширення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2439">**Data\_Doc\_Extension:string -** Document extension</span></span>

  - <span data-ttu-id="1bd6a-2440">**Data\_Doc\_FileFormat:long –** попередньо визначений набір значень формату файлу (більш деталізація ніж розширення)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2440">**Data\_Doc\_FileFormat:long -** Predefined set of values of format of file (more granular than extension)</span></span>

  - <span data-ttu-id="1bd6a-2441">**Data\_Doc\_Fqdn:string – -** місце збереження документа (SharePoint.com, live.net), тільки для доменів у службі Office 365</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2441">**Data\_Doc\_Fqdn:string – -** Where is document stored (SharePoint.com, live.net), only available for Office 365 domains</span></span>

  - <span data-ttu-id="1bd6a-2442">**Data\_Doc\_FqdnHash:string – -** геш місця збереження документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2442">**Data\_Doc\_FqdnHash:string – -** Hash of where document is stored</span></span>

  - <span data-ttu-id="1bd6a-2443">**Data\_Doc\_IdentityTelemetryId:string – -** унікальний GUID користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2443">**Data\_Doc\_IdentityTelemetryId:string – -** Unique GUID of user</span></span>

  - <span data-ttu-id="1bd6a-2444">**Data\_Doc\_IdentityUniqueId:string –** унікальний ідентифікатор ідентичності при роботі над документами зі спільним доступом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2444">**Data\_Doc\_IdentityUniqueId:string -** Unique identifier of identity that was used for Shared Documents action</span></span>

  - <span data-ttu-id="1bd6a-2445">**Data\_Doc\_IOFlags:long –** бітова маска для різних позначок пов'язаних з IO для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2445">**Data\_Doc\_IOFlags:long -** Bitmask for various IO related flags for a given document</span></span>

  - <span data-ttu-id="1bd6a-2446">**Data\_Doc\_IrmRights:long** – попередньо визначений набір значень типу керування правами доступу до інформації документа (Forward, Reply, SecureReader, Edit тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2446">**Data\_Doc\_IrmRights:long -** Predefined set of values of what type of Information Rights Management is applied on this document (Forward, Reply, SecureReader, Edit etc.)</span></span>

  - <span data-ttu-id="1bd6a-2447">**Data\_Doc\_IsCloudCollabEnabled:bool –** значення True, якщо HTTP заголовок IsCloudCollabEnabled вже було отримано від запиту параметрів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2447">**Data\_Doc\_IsCloudCollabEnabled:bool -** True if the "IsCloudCollabEnabled" HTTP header has already been received from an OPTIONS request.</span></span>

  - <span data-ttu-id="1bd6a-2448">**Data\_Doc\_IsIncrementalOpen:bool – -** чи відкрито документ інкрементно (нова функція, що відкриває документ без необхідності повного завантаження)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2448">**Data\_Doc\_IsIncrementalOpen:bool – -** Was document opened incrementally (new feature that opens document without needing to download entire document)</span></span>

  - <span data-ttu-id="1bd6a-2449">**Data\_Doc\_IsOcsSupported:bool –** чи використовує підтримка співавторства документів нову службу OCS</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2449">**Data\_Doc\_IsOcsSupported:bool -** Is Document supports coauthoring using new OCS service</span></span>

  - <span data-ttu-id="1bd6a-2450">**Data\_Doc\_IsOpeningOfflineCopy:bool –** чи відкрито документ з локального кеша?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2450">**Data\_Doc\_IsOpeningOfflineCopy:bool -** Is document being opened from local cache?</span></span>

  - <span data-ttu-id="1bd6a-2451">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2451">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2452">**Data\_Doc\_IsSyncBacked:bool –** чи відкрито документ з папки, яка використовує програму синхронізації OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2452">**Data\_Doc\_IsSyncBacked:bool -** Is document opened from folder that is using OneDrive sync back app</span></span>

  - <span data-ttu-id="1bd6a-2453">**Data\_Doc\_Location:long –** попередньо визначений набір значень місця збереження документа (Local, SharePoint, WOPI, Network тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2453">**Data\_Doc\_Location:long -** Predefined set of values of where document is stored (Local, SharePoint, WOPI, Network etc.)</span></span>

  - <span data-ttu-id="1bd6a-2454">**Data\_Doc\_LocationDetails:long –** попередньо визначений набір значень більш детального розташування (папка Temp, папка «Завантаження», One Drive Documents, One Drive Pictures тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2454">**Data\_Doc\_LocationDetails:long -** Predefined set of values of more detailed location (Temp folder, downloads folder, One Drive Documents, One Drive Pictures, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2455">**Data\_Doc\_NumberCoAuthors:long –** кількість співавторів під час відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2455">**Data\_Doc\_NumberCoAuthors:long -** Number of coauthors at the time of opening of a document</span></span>

  - <span data-ttu-id="1bd6a-2456">**Data\_Doc\_PasswordFlags:long –** попередньо визначений набір значень шифрування документа паролем (ніякого, пароль для читання, пароль для редагування)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2456">**Data\_Doc\_PasswordFlags:long -** Predefined set of values of how document is encrypted with password (None, password to read, password to edit)</span></span>

  - <span data-ttu-id="1bd6a-2457">**Data\_Doc\_ReadOnlyReasons:long –-** попередньо визначений набір значень причини з якої документ позначено як лише для читання (заблоковано на сервері, остаточна версія документа, захищено паролем для редагування тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2457">**Data\_Doc\_ReadOnlyReasons:long –-** Predefined set of values of why this document was marked read only (Locked on server, final document, password protected to edit, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2458">**Data\_Doc\_ResourceIdHash:string –** гешування ідентифікатора ресурсів документів збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2458">**Data\_Doc\_ResourceIdHash:string -** Hash of resource identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2459">**Data\_Doc\_ServerDocId:string –** незмінний ідентифікатор документів збережених у хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2459">**Data\_Doc\_ServerDocId:string -** immutable identifier for documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2460">**Data\_Doc\_ServerProtocol:long –** попередньо визначений набір значень типу протоколу звернення до сервера (Http, Cobalt, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2460">**Data\_Doc\_ServerProtocol:long -** Predefined set of values of which protocol is used to talk to server (Http, Cobalt, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2461">**Data\_Doc\_ServerType:long –** попередньо визначений набір значень типу сервера (SharePoint, DropBox, WOPI)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2461">**Data\_Doc\_ServerType:long -** Predefined set of values of type of server (SharePoint, DropBox, WOPI)</span></span>

  - <span data-ttu-id="1bd6a-2462">**Data\_Doc\_ServerVersion:long –** чи сервер поза властивістю Office14, Office15, Office 16?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2462">**Data\_Doc\_ServerVersion:long -** Is server is based off Office14, Office15, Office 16?</span></span>

  - <span data-ttu-id="1bd6a-2463">**Data\_Doc\_SessionId:long –** згенерований глобальний унікальний ідентифікатор, який визначає екземпляр документа у тому ж сеансі процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2463">**Data\_Doc\_SessionId:long -** generated GUID that Identifies the instance of the document within the same process session</span></span>

  - <span data-ttu-id="1bd6a-2464">**Data\_Doc\_SharePointServiceContext:string –** непрозорий рядок, зазвичай GridManagerID.FarmID.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2464">**Data\_Doc\_SharePointServiceContext:string -** An opaque string, typically GridManagerID.FarmID.</span></span> <span data-ttu-id="1bd6a-2465">Зручно для узгодження клієнтського та серверного журналів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2465">Useful for correlating client-side and server-side logs</span></span>

  - <span data-ttu-id="1bd6a-2466">**Data\_Doc\_SizeInBytes:long –** розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2466">**Data\_Doc\_SizeInBytes:long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-2467">**Data\_Doc\_SpecialChars:long –** бітова маска, що визначає спеціальні символи URL-адреси або шляху до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2467">**Data\_Doc\_SpecialChars:long -** Bitmask indicating special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2468">**Data\_Doc\_StorageProviderId:string –** рядок, що визначає постачальника зберігання документа, наприклад «DropBox»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2468">**Data\_Doc\_StorageProviderId:string -** A string that identifies the document's storage provider, like "DropBox”</span></span>

  - <span data-ttu-id="1bd6a-2469">**Data\_Doc\_StreamAvailability:long–** попередньо визначений набір значень стану потоку документів (доступний, вимкнений, недоступний)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2469">**Data\_Doc\_StreamAvailability:long-** Predefined set of values of status of document Stream (available, permanently disabled, not available)</span></span>

  - <span data-ttu-id="1bd6a-2470">**Data\_Doc\_UrlHash:string –** гешування повної URL-адреси документа збереженого в хмарі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2470">**Data\_Doc\_UrlHash:string -** hash of full URL of documents stored in cloud</span></span>

  - <span data-ttu-id="1bd6a-2471">**Data\_Doc\_UsedWrsDataOnOpen:bool –** значення true, якщо файл відкривався інкрементно використовуючи попередньо кешовані дані WRS з хостингу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2471">**Data\_Doc\_UsedWrsDataOnOpen:bool -** true if the file was opened incrementally using pre-cached WRS data on the host</span></span>

  - <span data-ttu-id="1bd6a-2472">**Data\_Doc\_WopiServiceId:string –** ідентифікатор служби WOPI, наприклад «Dropbox»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2472">**Data\_Doc\_WopiServiceId:string -** WOPI Service identifier, e.g. "Dropbox"</span></span>

  - <span data-ttu-id="1bd6a-2473">**Data\_DownloadExcludedData –** тривалість виконання методу DownloadExcludedData в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2473">**Data\_DownloadExcludedData -** Method DownloadExcludedData execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2474">**Data\_DownloadExcludedDataTelemetry –** попередньо визначений набір значень стану синхронної черги завантаження (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2474">**Data\_DownloadExcludedDataTelemetry -** Predefined set of values of state of synchronously waiting for download(SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult etc.)</span></span>

  - <span data-ttu-id="1bd6a-2475">**Data\_DownloadFileInBGThread –** тривалість виконання методу DownloadFileInBGThread в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2475">**Data\_DownloadFileInBGThread -** Method DownloadFileInBGThread execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2476">**Data\_DownloadFragmentSize –** розмір фрагменту (доступна для завантаження частина файлу), зазвичай 3,5 МБ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2476">**Data\_DownloadFragmentSize -** Size of fragment(downloadable chunk of file), usually 3.5 MB</span></span>

  - <span data-ttu-id="1bd6a-2477">**Data\_ExcludedEmbeddedItems –** кількість zip частин виключених з першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2477">**Data\_ExcludedEmbeddedItems -** Number of zip parts that are excluded for first render</span></span>

  - <span data-ttu-id="1bd6a-2478">**Data\_ExcludedEmbeddedItemsSize –** загальна кількість zip частин виключених з першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2478">**Data\_ExcludedEmbeddedItemsSize -** Total size of zip parts that are excluded for first render</span></span>

  - <span data-ttu-id="1bd6a-2479">**Data\_ExcludedRequiredItems –** кількість zip частин виключених з першого відтворення, що були необхідними</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2479">**Data\_ExcludedRequiredItems -** Number of zip parts that are excluded but required for first render</span></span>

  - <span data-ttu-id="1bd6a-2480">**Data\_ExcludedRequiredItemsSize –** загальна кількість zip частин виключених з першого відтворення, що були необхідними</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2480">**Data\_ExcludedRequiredItemsSize -** Total size of zip parts that are excluded but required for first render</span></span>

  - <span data-ttu-id="1bd6a-2481">**Data\_ExecutionCount –** кількість разів виконання протоколу IncOpen</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2481">**Data\_ExecutionCount -** How many times IncOpen protocol was executed</span></span>

  - <span data-ttu-id="1bd6a-2482">**Data\_FailureComponent:long –** попередньо визначений набір значень, які вказують на компонент, що став причиною помилки протоколу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2482">**Data\_FailureComponent:long -** Predefined set of values of which component caused this protocol to fail?</span></span> <span data-ttu-id="1bd6a-2483">(Conflict, CSI, Internal тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2483">(Conflict, CSI, Internal etc.)</span></span>

  - <span data-ttu-id="1bd6a-2484">**Data\_FailureReason:long –** попередньо визначений набір значень причини помилки (FileIsCorrupt, BlockedByAntivirus тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2484">**Data\_FailureReason:long -** Predefined set of values of what’s the failure reason (FileIsCorrupt, BlockedByAntivirus etc.)</span></span>

  - <span data-ttu-id="1bd6a-2485">**Data\_FCreateNew –** це новий пустий документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2485">**Data\_FCreateNew -** Is this new blank document</span></span>

  - <span data-ttu-id="1bd6a-2486">**Data\_FCreateNewFromTemplate –** це новий документ із шаблонів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2486">**Data\_FCreateNewFromTemplate -** Is this new document from templates</span></span>

  - <span data-ttu-id="1bd6a-2487">**Data_FErrorAfterDocWinCreation:boolean** – визначає, чи ставалися будь-які помилки або винятки після створення вікна перегляду документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2487">**Data_FErrorAfterDocWinCreation:boolean-**  Did any error or exception happen after the document window is created.</span></span>

  - <span data-ttu-id="1bd6a-2488">**Data\_FileUrlLocation –** попередньо визначений набір значень місця збереження документа (NetworkShare, LocalDrive, ServerOther тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2488">**Data\_FileUrlLocation -** Predefined set of values of where document is stored (NetworkShare, LocalDrive, ServerOther etc.)</span></span>

  - <span data-ttu-id="1bd6a-2489">**Data\_FirstSlideCompressedSize –** стиснутий розмір першого слайда zip частини (зазвичай Slide1.xml)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2489">**Data\_FirstSlideCompressedSize -** compressed size of first slide zip part (usually Slide1.xml)</span></span>

  - <span data-ttu-id="1bd6a-2490">**Data\_FIsDownloadFileInBgThreadEnabled –** чи відбувається завантаження у фоновому потоці?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2490">**Data\_FIsDownloadFileInBgThreadEnabled -** Is downloading in background thread enabled?</span></span>

  - <span data-ttu-id="1bd6a-2491">**Data\_fLifeguarded:bool –** чи оброблений документ функцією lifeguarded (функція самостійного виправлення помилок документів без запиту користувача)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2491">**Data\_fLifeguarded:bool -** Was document ever lifeguarded (feature to fix document errors by themselves without prompting user)?</span></span>

  - <span data-ttu-id="1bd6a-2492">**Data\_ForceReopenOnIncOpenMergeFailure –** позначка примусового повторного відкриття через помилку злиття в Inc Open</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2492">**Data\_ForceReopenOnIncOpenMergeFailure -** Flag representing if we were forced to re-open due to merge failure in Inc Open</span></span>

  - <span data-ttu-id="1bd6a-2493">**Data\_ForegroundThreadPass0TimeMS –** (лише для Mac) загальний час, витрачений на передній потік з першого разу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2493">**Data\_ForegroundThreadPass0TimeMS -** (Mac only) Total time spent in foreground thread in first pass</span></span>

  - <span data-ttu-id="1bd6a-2494">**Data\_ForegroundThreadPass1TimeMS –** (лише для Mac) загальний час, витрачений на передній потік з другого разу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2494">**Data\_ForegroundThreadPass1TimeMS -** (Mac only) Total time spent in foreground thread in second pass</span></span>

  - <span data-ttu-id="1bd6a-2495">**Data\_FWebCreatorDoc –** документ створений з шаблону чи компонувальника презентації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2495">**Data\_FWebCreatorDoc -** Is doc created from template or QuickStarter</span></span>

  - <span data-ttu-id="1bd6a-2496">**Data\_HasDocToken –** чи має документ маркер CSI doc (внутрішній індекс)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2496">**Data\_HasDocToken -** Does this document have CSI doc token (internal code)</span></span>

  - <span data-ttu-id="1bd6a-2497">**Data\_HasDocument –** чи має документ CSI документ (внутрішній індекс)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2497">**Data\_HasDocument -** Does this document have CSI document (internal code)</span></span>

  - <span data-ttu-id="1bd6a-2498">**Data\_InclusiveMeasurements –** чи включає тривалість вимірювання методу тривалість виклику дочірнього методу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2498">**Data\_InclusiveMeasurements -** Does method measurement durations are inclusive of child method call duration</span></span>

  - <span data-ttu-id="1bd6a-2499">**Data\_IncompleteDocReasons –** попередньо визначений набір значень причини неповного відкриття (Unknown, DiscardFailure тощо.)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2499">**Data\_IncompleteDocReasons -** Predefined set of values of why open was incomplete (Unknown, DiscardFailure etc.)</span></span>

  - <span data-ttu-id="1bd6a-2500">**Data\_IncOpenDisabledReasons –** попередньо визначений набір значень причин з яких інкрементне відкриття було вимкнуто</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2500">**Data\_IncOpenDisabledReasons -** Predefined set of values of Reasons why incremental open was disabled</span></span>

  - <span data-ttu-id="1bd6a-2501">**Data\_IncOpenFailureHr –** результат того, що інкрементне відкриття не вдалося</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2501">**Data\_IncOpenFailureHr -** result of why Incremental open failed</span></span>

  - <span data-ttu-id="1bd6a-2502">**Data\_IncOpenFailureTag –** позначка (вказівник для розташування коду) де стався збій інкрементного відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2502">**Data\_IncOpenFailureTag -** Tag (pointer to code location) of where Incremental open failed</span></span>

  - <span data-ttu-id="1bd6a-2503">**Data\_IncOpenFallbackReason –** причина з якої не запущено IncOpen</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2503">**Data\_IncOpenFallbackReason -** Why was IncOpen not run</span></span>

  - <span data-ttu-id="1bd6a-2504">**Data\_IncOpenRequiredTypes –** попередньо визначений набір значень типів вмісту, потрібних для першого відтворення (RequiredXmlZipItem, RequiredNotesMaster тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2504">**Data\_IncOpenRequiredTypes -** Predefined set of values of content types needed for first render (RequiredXmlZipItem, RequiredNotesMaster etc.)</span></span>

  - <span data-ttu-id="1bd6a-2505">**Data\_IncOpenStatus –** попередньо визначений набір значень інкрементного стану відкриття (Attempted, FoundExcludedItems, DocIncOpenInfoCreated тощо).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2505">**Data\_IncOpenStatus -** Predefined set of values of Incremental open status (Attempted, FoundExcludedItems, DocIncOpenInfoCreated etc.)</span></span>

  - <span data-ttu-id="1bd6a-2506">**Data\_InitFileContents –** тривалість виконання методу InitFileContents в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2506">**Data\_InitFileContents -** Method InitFileContents execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2507">**Data\_InitialExcludedItems –** кількість zip частин виключених в першу чергу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2507">**Data\_InitialExcludedItems -** Number of zip parts that are excluded initially</span></span>

  - <span data-ttu-id="1bd6a-2508">**Data\_InitialExcludedItemsSize –** початкова кількість zip частин виключених в першу чергу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2508">**Data\_InitialExcludedItemsSize -** Total size of zip parts that are excluded initially</span></span>

  - <span data-ttu-id="1bd6a-2509">**Data\_InitializationTimeMS –** (лише для Mac) час ініціалізації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2509">**Data\_InitializationTimeMS -** (Mac Only) Time to initialize</span></span>

  - <span data-ttu-id="1bd6a-2510">**Data\_InitialRoundtripCount –** кількість відповідей сервера необхідних для створення початкового zip архіву</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2510">**Data\_InitialRoundtripCount -** Number of server responses needed to form initial zip archive</span></span>

  - <span data-ttu-id="1bd6a-2511">**Data\_InitLoadProcess –** тривалість виконання методу InitLoadProcess в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2511">**Data\_InitLoadProcess -** Method InitLoadProcess execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2512">**Data\_InitPackage –** тривалість виконання методу InitPackage в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2512">**Data\_InitPackage -** Method InitPackage execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2513">**Data\_InitSecureReaderReasons –** тривалість виконання методу InitSecureReaderReasons в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2513">**Data\_InitSecureReaderReasons -** Method InitSecureReaderReasons execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2514">**Data\_IsIncOpenInProgressWhileOpen –** чи працюють Inc open протокол і відкритий протокол одночасно, у випадку кількох відкриттів одного документа?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2514">**Data\_IsIncOpenInProgressWhileOpen -** In case of multiple open of same document, is Inc open protocol running alongside open protocol?</span></span>

  - <span data-ttu-id="1bd6a-2515">**Data\_IsMultiOpen –** чи підтримується декілька відкривань?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2515">**Data\_IsMultiOpen -** Do we support multiple open?</span></span>

  - <span data-ttu-id="1bd6a-2516">**Data\_IsOCS –** чи документ в режимі OCS був в його останньому відомому стані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2516">**Data\_IsOCS -** Was document in OCS mode in its’ last known state</span></span>

  - <span data-ttu-id="1bd6a-2517">**Data\_IsODPFile –** чи використовуються OpenOffice.org документ формату «Open Document»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2517">**Data\_IsODPFile -** Is document in 'Open Document Format' used by OpenOffice.org</span></span>

  - <span data-ttu-id="1bd6a-2518">**Data\_IsPPTMetroFile –** чи документ metro (pptx) file format</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2518">**Data\_IsPPTMetroFile -** Is document metro (pptx) file format</span></span>

  - <span data-ttu-id="1bd6a-2519">**Data\_LoadDocument –** тривалість виконання методу LoadDocument в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2519">**Data\_LoadDocument -** Method LoadDocument execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2520">**Data\_MeasurementBreakdown –** закодоване вимірювання підрозділу (докладний скорочений метод прод.)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2520">**Data\_MeasurementBreakdown -** Encoded measurement breakdown (shortened detailed method perf)</span></span>

  - <span data-ttu-id="1bd6a-2521">**Data\_Measurements –** закодовані вимірювання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2521">**Data\_Measurements -** Encoded measurements</span></span>

  - <span data-ttu-id="1bd6a-2522">**Data\_MethodId –** останній метод, що виконувався</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2522">**Data\_MethodId -** Last method that was executed</span></span>

  - <span data-ttu-id="1bd6a-2523">**Data\_NotRequiredExcludedItems –** загальна кількість елементів PowerPoint, що виключені та не потрібні для першого відтворення </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2523">**Data\_NotRequiredExcludedItems -** Total number of PowerPoint package items that are not required for first render and excluded</span></span>

  - <span data-ttu-id="1bd6a-2524">**Data\_NotRequiredExcludedItemsSize –** загальний розмір елементів PowerPoint, що виключені та не потрібні для першого відтворення </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2524">**Data\_NotRequiredExcludedItemsSize -** Total size of PowerPoint package items that are not required for first render and excluded</span></span>

  - <span data-ttu-id="1bd6a-2525">**Data\_NotRequiredExcludedParts –** загальна кількість zip частин, що виключені та не потрібні для першого відтворення </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2525">**Data\_NotRequiredExcludedParts -** Total number of zip parts that are not required for first render and excluded</span></span>

  - <span data-ttu-id="1bd6a-2526">**Data\_NotRequiredExcludedPartsSize –** загальний розмір zip частин, що виключені та не потрібні для першого відтворення </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2526">**Data\_NotRequiredExcludedPartsSize -** Total number of zip parts that are not required for first render and excluded</span></span>

  - <span data-ttu-id="1bd6a-2527">**Data\_OpenCompleteFailureHR –** результат причини помилки протоколу OpenComplete</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2527">**Data\_OpenCompleteFailureHR -** result of why OpenComplete protocol failed</span></span>

  - <span data-ttu-id="1bd6a-2528">**Data\_OpenCompleteFailureTag –** позначка (вказівник розташування коду) де стався збій протоколу OpenComplete</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2528">**Data\_OpenCompleteFailureTag -** Tag (pointer to code location) of where OpenComplete protocol failed</span></span>

  - <span data-ttu-id="1bd6a-2529">**Data\_OpenLifeguardOption –** попередньо визначений набір значень варіантів операції lifeguard(None, TryAgain, OpenInWebApp тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2529">**Data\_OpenLifeguardOption -** Predefined set of values of choices for lifeguard operation (None, TryAgain, OpenInWebApp etc.)</span></span>

  - <span data-ttu-id="1bd6a-2530">**Data\_OpenReason –** попередньо визначений набір значень способу відкриття документа (FilePicker, OpenFromMru, FileDrop тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2530">**Data\_OpenReason -** Predefined set of values of how this document was opened (FilePicker, OpenFromMru, FileDrop etc.)</span></span>

  - <span data-ttu-id="1bd6a-2531">**Data\_OSRPolicy –** політика Secure Reader</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2531">**Data\_OSRPolicy -** SecureReader Policy</span></span>

  - <span data-ttu-id="1bd6a-2532">**Data\_OSRReason –** причини з яких документ відкрито в Secure Reader</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2532">**Data\_OSRReason -** Reasons why this document was opened in Secure Reader</span></span>

  - <span data-ttu-id="1bd6a-2533">**Data\_OtherContentTypesWithRequiredParts –** нестандартні типи вмісту необхідні для першого відтворення, які було виключено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2533">**Data\_OtherContentTypesWithRequiredParts -** Nonstandard content types that were excluded but required for first render</span></span>

  - <span data-ttu-id="1bd6a-2534">**Data\_PrepCacheAsync –** позначка для OcsiOpenPerfPrepCacheAsync</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2534">**Data\_PrepCacheAsync -** Flag for OcsiOpenPerfPrepCacheAsync</span></span>

  - <span data-ttu-id="1bd6a-2535">**Data\_PreviousDiscardFailed –** вказує на попередні спроби відкриття/закриття документа, що не вивільнив пам'ять належним чином</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2535">**Data\_PreviousDiscardFailed -** Indicates previous open/close attempt on the document didn't properly release all memory</span></span>

  - <span data-ttu-id="1bd6a-2536">**Data\_PreviousFailureHr –** остання помилка повторного відкриття однакового документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2536">**Data\_PreviousFailureHr -** In case of re-opening of same document, what was last failure result</span></span>

  - <span data-ttu-id="1bd6a-2537">**Data\_PreviousFailureTag –** остання позначка помилки повторного відкриття однакового документа (вказівник розташування коду)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2537">**Data\_PreviousFailureTag -** In case of re-opening of same document, what was last failure tag (pointer to code location)</span></span>

  - <span data-ttu-id="1bd6a-2538">**Data\_RemoteDocToken –** чи ввімкнуто віддалене відкриття (прототип функції, яка відкриває файл зі служби, а не з хостингу)?</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2538">**Data\_RemoteDocToken -** Is Remote Open enabled (prototype feature that enables opening file from service rather than from host)?</span></span>

  - <span data-ttu-id="1bd6a-2539">**Data\_Repair –** чи йде робота в режимі відновлення документа (для пошкоджених документів, які можна виправити)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2539">**Data\_Repair -** Are we in document repair mode (for corrupt documents that are fixable)</span></span>

  - <span data-ttu-id="1bd6a-2540">**Data\_RequestPauseStats –** кількість разів коли код надсилав запит на призупинення записування прод.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2540">**Data\_RequestPauseStats -** How many times code requested to pause perf recording</span></span>

  - <span data-ttu-id="1bd6a-2541">**Data\_RequiredPartsComressedSize –** загальний розмір необхідних частин PowerPoint потрібних для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2541">**Data\_RequiredPartsComressedSize -** Total size of required PowerPoint parts needed for first render</span></span>

  - <span data-ttu-id="1bd6a-2542">**Data\_RequiredPartsDownload –** загальний розмір необхідних частин PowerPoint, які завантажуються</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2542">**Data\_RequiredPartsDownload -** Total size of required PowerPoint parts that are downloaded</span></span>

  - <span data-ttu-id="1bd6a-2543">**Data\_RequiredPartsRoundtripCount –** загальна кількість повторних звернень (до хостингу) необхідних, щоб отримати всі потрібні частини PowerPoint для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2543">**Data\_RequiredPartsRoundtripCount -** Total number of roundtrips (calls to host) needed to get all the required PowerPoint parts for first render</span></span>

  - <span data-ttu-id="1bd6a-2544">**Data\_RequiredZipItemsDownload –** загальний розмір необхідних zip елементів, потрібних для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2544">**Data\_RequiredZipItemsDownload -** Total size of required zip items needed for first render</span></span>

  - <span data-ttu-id="1bd6a-2545">**Data\_RequiredZipItemsRoundtripCount –** загальна кількість повторних звернень (до хостингу) необхідних, щоб отримати всі потрібні zip елементи для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2545">**Data\_RequiredZipItemsRoundtripCount -** Total number of roundtrips (calls to host) needed to get all the required zip items for first render</span></span>

  - <span data-ttu-id="1bd6a-2546">**Data\_RoundtripsAfterMissingRequiredParts –** загальна кількість повторних звернень (до хостингу) потрібних після знайдення відсутніх необхідних частин PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2546">**Data\_RoundtripsAfterMissingRequiredParts -** Total number of roundtrips (calls to host) needed after we found missing required PowerPoint parts</span></span>

  - <span data-ttu-id="1bd6a-2547">**Data\_RoundtripsAfterMissingRequiredZipItems –** загальна кількість повторних звернень (до хостингу) необхідних після знайдення zip елементів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2547">**Data\_RoundtripsAfterMissingRequiredZipItems -** Total number of roundtrips (calls to host) needed after we found missing required zip items</span></span>

  - <span data-ttu-id="1bd6a-2548">**Data\_RoundtripsAfterRequiredPackage -** загальну кількість повторних звернень (до хостингу) необхідних після створення пакету</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2548">**Data\_RoundtripsAfterRequiredPackage -** Total number of roundtrips (calls to host) needed after we created the package</span></span>

  - <span data-ttu-id="1bd6a-2549">**Data\_RoundtripsAfterRequiredParts –** загальну кількість повторних звернень (до хостингу) необхідних після завантаження всіх потрібних частин</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2549">**Data\_RoundtripsAfterRequiredParts -** Total number of roundtrips (calls to host) needed after we downloaded all required parts</span></span>

  - <span data-ttu-id="1bd6a-2550">**Data\_SetDocCoAuthAutoSaveable –** тривалість виконання методу SetDocCoAuthAutoSaveable в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2550">**Data\_SetDocCoAuthAutoSaveable -** Method SetDocCoAuthAutoSaveable execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2551">**Data\_SniffedFileType –** припущення запропонованого типу пошкодженого документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2551">**Data\_SniffedFileType -** An educated guess of proposed file type of corrupt document</span></span>

  - <span data-ttu-id="1bd6a-2552">**Data\_StartTime –** лічильник прод. початку відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2552">**Data\_StartTime -** Perf counter when Open started</span></span>

  - <span data-ttu-id="1bd6a-2553">**Data\_StopwatchDuration:long –** загальний час активності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2553">**Data\_StopwatchDuration:long -** Total time for Activity</span></span>

  - <span data-ttu-id="1bd6a-2554">**Data\_SyncSlides –** тривалість виконання методу SyncSlides в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2554">**Data\_SyncSlides -** Method SyncSlides execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2555">**Data\_TimerStartReason –** попередньо визначений набір значень способу запуску таймера (CatchMissedSyncStateNotification, WaitingForFirstDownload тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2555">**Data\_TimerStartReason -** Predefined set of values of how timer was started (CatchMissedSyncStateNotification, WaitingForFirstDownload etc.)</span></span>

  - <span data-ttu-id="1bd6a-2556">**Data\_TimeSplitMeasurements –** закодоване вимірювання підрозділу (докладний скорочений метод прод.)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2556">**Data\_TimeSplitMeasurements -** Encoded measurement breakdown (shortened detailed method perf)</span></span>

  - <span data-ttu-id="1bd6a-2557">**Data\_TimeToInitialPackage –** час, витрачений на створення початкового пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2557">**Data\_TimeToInitialPackage -** Time took to create initial package</span></span>

  - <span data-ttu-id="1bd6a-2558">**Data\_TimeToRequiredPackage –** час, витрачений на створення необхідного пакета</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2558">**Data\_TimeToRequiredPackage -** Time took to create required package</span></span>

  - <span data-ttu-id="1bd6a-2559">**Data\_TimeToRequiredParts –** час, витрачений на створення пакета, що містить всі необхідні частини</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2559">**Data\_TimeToRequiredParts -** Time took to create package with all required parts in it</span></span>

  - <span data-ttu-id="1bd6a-2560">**Data\_TotalRequiredParts –** загальна кількість частин PowerPoint необхідних для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2560">**Data\_TotalRequiredParts -** Total number of PowerPoint parts required for first render</span></span>

  - <span data-ttu-id="1bd6a-2561">**Data\_UnknownRequiredParts –** загальна кількість нестандартних частин необхідних для першого відтворення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2561">**Data\_UnknownRequiredParts -** Total number of non-standard parts required for first render</span></span>

  - <span data-ttu-id="1bd6a-2562">**Data\_UnpackLinkWatsonId –** ідентифікатор Watson для помилки під час відкриття документа за допомогою URL-адреси Share OneDrive</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2562">**Data\_UnpackLinkWatsonId -** Watson identifier of error when document is opened via Share OneDrive URL</span></span>

  - <span data-ttu-id="1bd6a-2563">**Data\_UnpackResultHint –** попередньо визначений набір значень розпакування результатів поширення URL-адрес (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2563">**Data\_UnpackResultHint -** Predefined set of values of unpacking share URL results (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen etc.)</span></span>

  - <span data-ttu-id="1bd6a-2564">**Data\_UnpackUrl –** тривалість виконання методу UnpackUrl в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2564">**Data\_UnpackUrl -** Method UnpackUrl execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2565">**Data\_UpdateAppstateTimeMS –** тривалість виконання методу UpdateAppstate в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2565">**Data\_UpdateAppstateTimeMS -** Method UpdateAppstate execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2566">**Data\_UpdateCoauthoringState –** тривалість виконання методу UpdateCoauthoringState в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2566">**Data\_UpdateCoauthoringState -** Method UpdateCoauthoringState execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2567">**Data\_UpdateReadOnlyState –** тривалість виконання методу UpdateReadOnlyState в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2567">**Data\_UpdateReadOnlyState -** Method UpdateReadOnlyState execution duration in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-2568">**Data\_WACCorrelationId –** отримання кореляції WebApp журналів, у разі відкриття файлу в браузері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2568">**Data\_WACCorrelationId -** In case of opening file in browser, get the correlation of WebApp logs</span></span>

  - <span data-ttu-id="1bd6a-2569">**Data\_WasCachedOnInitialize –** чи був документ кешованим під час ініціалізації</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2569">**Data\_WasCachedOnInitialize -** Was this document cached during initialization</span></span>

  - <span data-ttu-id="1bd6a-2570">**Data\_WBDirtyBeforeDiscard –** чи стала робоча область пошкодженою перед повторним відкриттям документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2570">**Data\_WBDirtyBeforeDiscard -** Is working branch became dirty before re-opening document</span></span>

  - <span data-ttu-id="1bd6a-2571">**Data\_ZRTOpenDisabledReasons –** причини через які не вдалося відкрити документ із кеша (Zero Round Trip)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2571">**Data\_ZRTOpenDisabledReasons -** Why we could not open document from cache (Zero Round Trip)</span></span>

#### <a name="officeprojectopenproject"></a><span data-ttu-id="1bd6a-2572">Office.Project.OpenProject</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2572">Office.Project.OpenProject</span></span>

<span data-ttu-id="1bd6a-2573">Project відкриє файл.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2573">Project opens a file.</span></span> <span data-ttu-id="1bd6a-2574">Ця подія вказує на безпосереднього користувача, який відкриває файл Project.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2574">This event indicates a user directly opening a Project file by a user.</span></span> <span data-ttu-id="1bd6a-2575">Вона містить важливі для успіху дані про відкриття файлу в Project.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2575">It contains critical success data of opening files in Project.</span></span>

<span data-ttu-id="1bd6a-2576">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2576">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2577">**Data\_AgileMode –** визначає чи відкритий проект каскадною діаграмою або гнучким методом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2577">**Data\_AgileMode -** defines if the project opened is a waterfall or agile project</span></span>

  - <span data-ttu-id="1bd6a-2578">**Data\_AlertTime –** час активності діалогового вікна завантаження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2578">**Data\_AlertTime -** The amount of time the boot dialog was active</span></span>

  - <span data-ttu-id="1bd6a-2579">**Data\_CacheFileSize –** розмір файлу, якщо він кешований</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2579">**Data\_CacheFileSize -** If the file was cached, the size of the file</span></span>

  - <span data-ttu-id="1bd6a-2580">**Data\_EntDocType –** тип відкритого файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2580">**Data\_EntDocType -** the type of file that was opened</span></span>

  - <span data-ttu-id="1bd6a-2581">**Data\_IsInCache –** чи кешований відкритий файл</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2581">**Data\_IsInCache -** whether the file opened was cached</span></span>

  - <span data-ttu-id="1bd6a-2582">**Data\_LoadSRAs –** чи хоче користувач завантажити SRAs</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2582">**Data\_LoadSRAs -** If the user wants to load SRAs or not</span></span>

  - <span data-ttu-id="1bd6a-2583">**Data\_OpenFromDocLib –** чи з бібліотеки документів відкритий файл Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2583">**Data\_OpenFromDocLib -** If the Project file opened was from the document library</span></span>

  - <span data-ttu-id="1bd6a-2584">**Data\_Outcome –** загальний час завантаження та відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2584">**Data\_Outcome -** Total boot and file open time</span></span>

  - <span data-ttu-id="1bd6a-2585">**Data\_Outcome –** загальний час завантаження та відкриття файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2585">**Data\_Outcome -** Total boot and file open time.</span></span>

  - <span data-ttu-id="1bd6a-2586">**Data\_ProjectServerVersion –** поточна версія та збірка Project</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2586">**Data\_ProjectServerVersion -** The version and build that Project is currently on</span></span>

#### <a name="officesessionidproviderofficeprocesssessionstart"></a><span data-ttu-id="1bd6a-2587">Office.SessionIdProvider.OfficeProcessSessionStart</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2587">Office.SessionIdProvider.OfficeProcessSessionStart</span></span>

<span data-ttu-id="1bd6a-2588">Розповсюджуються на всі програми на основі Office windows: win32 та UWP</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2588">Applicable to all the Office windows-based applications: win32 and UWP</span></span>

<span data-ttu-id="1bd6a-2589">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2589">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-2590">**OfficeProcessSessionStart** надсилає основні відомості на початку нового сеансу Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2590">**OfficeProcessSessionStart** sends basic information upon the start of a new Office session.</span></span> <span data-ttu-id="1bd6a-2591">Використовується для підрахунку кількості унікальних сеансів з певного пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2591">This is used to count the number of unique sessions seen on a given device.</span></span> <span data-ttu-id="1bd6a-2592">Використовується як підтвердження функціонування події, щоб переконатися чи запущена програма на пристрої.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2592">This is used as a heartbeat event to ensure that the application is running on a device or not.</span></span> <span data-ttu-id="1bd6a-2593">На додачу, виступає критичним сигналом загальної надійності програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2593">In addition, it serves as a critical signal for overall application reliability</span></span>

- <span data-ttu-id="1bd6a-2594">**AppSessionGuid** – ідентифікатор сеансу певної програми, який почався в момент створення процесу та існує до закінчення процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2594">**AppSessionGuid** - An identifier of a particular application session starting at process creation time and persisting until process end.</span></span> <span data-ttu-id="1bd6a-2595">Він має формат стандартного 128-бітного глобального унікального ідентифікатора (GUID), але складається з 4 частин.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2595">It is formatted as a standard 128-bit GUID but constructed of 4 parts.</span></span> <span data-ttu-id="1bd6a-2596">Це такі частини: (1) 32-бітний ідентифікатор процесу, (2) 16-бітний ідентифікатор сеансу, (3) 16-бітний ідентифікатор завантаження та (4) 64-бітний час створення процесу за UTC з кроком 100 нс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2596">Those four parts in order are (1) 32 bit Process ID (2) 16 bit Session ID (3) 16 bit Boot ID (4) 64 bit Process creation time in UTC 100ns</span></span>

- <span data-ttu-id="1bd6a-2597">**processSessionId** – випадково згенерований глобальний унікальний ідентифікатор для позначення сеансу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2597">**processSessionId** - Randomly generated guid to identify the app session</span></span>

- <span data-ttu-id="1bd6a-2598">**UTCReplace_AppSessionGuid** – логічна константа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2598">**UTCReplace_AppSessionGuid** - Constant boolean value.</span></span> <span data-ttu-id="1bd6a-2599">Завжди має значення TRUE.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2599">Always true.</span></span>

#### <a name="officetelemetryengineisprelaunch"></a><span data-ttu-id="1bd6a-2600">Office.TelemetryEngine.IsPreLaunch</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2600">Office.TelemetryEngine.IsPreLaunch</span></span>

<span data-ttu-id="1bd6a-2601">Застосовується до програм Office UWP.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2601">Applicable for Office UWP applications.</span></span>  <span data-ttu-id="1bd6a-2602">Ця подія спрацьовує, коли програма office вперше починає оновлення/інсталяцію допису з магазину.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2602">This event is fired when an office application is initiated for the first-time post upgrade/install from the store.</span></span> <span data-ttu-id="1bd6a-2603">Це частина основних діагностичних даних, яка використовується, щоб відстежувати чи запустився сеанс.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2603">This is part of basic diagnostic data, used to track whether a session is launch session or not.</span></span>

<span data-ttu-id="1bd6a-2604">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2604">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-2605">**appVersionBuild** – номер версії збірки програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2605">**appVersionBuild** - The app build version number.</span></span>

- <span data-ttu-id="1bd6a-2606">**appVersionMajor** – номер основної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2606">**appVersionMajor** - The app major version number.</span></span>

- <span data-ttu-id="1bd6a-2607">**appVersionMinor** – номер проміжної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2607">**appVersionMinor** - The app minor version number.</span></span>

- <span data-ttu-id="1bd6a-2608">**appVersionRev** – номер редакції версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2608">**appVersionRev** - The app revision version number.</span></span>

- <span data-ttu-id="1bd6a-2609">**SessionID** – випадково згенерований глобальний унікальний ідентифікатор для позначення сеансу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2609">**SessionID** - Randomly generated GUID to identify the app session</span></span>

#### <a name="officetelemetryenginesessionhandoff"></a><span data-ttu-id="1bd6a-2610">Office.TelemetryEngine.SessionHandOff</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2610">Office.TelemetryEngine.SessionHandOff</span></span>

<span data-ttu-id="1bd6a-2611">Застосовується до програм Win32 Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2611">Applicable to Win32 Office applications.</span></span>  <span data-ttu-id="1bd6a-2612">Ця подія допомагає зрозуміти, чи створювався новий сеанс для обробки відкриття ініційованого користувачем файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2612">This event helps us understand whether there was a new session created to handle a user-initiated file open event.</span></span> <span data-ttu-id="1bd6a-2613">Критичні діагностичні відомості використовуються, щоб отримати сигнал надійності та переконатися, що програма працює належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2613">It is a critical diagnostic information that is used to derive reliability signal and ensure that the application is working as expected.</span></span>

<span data-ttu-id="1bd6a-2614">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2614">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-2615">**appVersionBuild** – номер версії збірки програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2615">**appVersionBuild** - The app build version number.</span></span>

- <span data-ttu-id="1bd6a-2616">**appVersionMajor** – номер основної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2616">**appVersionMajor** - The app major version number.</span></span>

- <span data-ttu-id="1bd6a-2617">**appVersionMinor** – номер проміжної версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2617">**appVersionMinor** - The app minor version number.</span></span>

- <span data-ttu-id="1bd6a-2618">**appVersionRev** – номер редакції версії програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2618">**appVersionRev** - The app revision version number.</span></span>

- <span data-ttu-id="1bd6a-2619">**childSessionID** – випадково згенерований глобальний унікальний ідентифікатор для позначення сеансу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2619">**childSessionID** - Randomly generated guid to identify the app session</span></span>

- <span data-ttu-id="1bd6a-2620">**parentSessionId** – випадково згенерований глобальний унікальний ідентифікатор для позначення сеансу програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2620">**parentSessionId** - Randomly generated guid to identify the app session</span></span>

#### <a name="officewordfileopenopencmdfilemrupriv"></a><span data-ttu-id="1bd6a-2621">Office.Word.FileOpen.OpenCmdFileMruPriv</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2621">Office.Word.FileOpen.OpenCmdFileMruPriv</span></span>

<span data-ttu-id="1bd6a-2622">Ця подія вказує, що Office Word відкриває документ зі списку останніх використаних документів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2622">This event indicates Office Word opens a document from the Most Recent Used (MRU) list.</span></span> <span data-ttu-id="1bd6a-2623">А також критичні дані продуктивності відкриття файлів. З точки зору користувача, це подія запуску програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2623">It also contains critical file open performance data, and is an app start event from user perspective.</span></span> <span data-ttu-id="1bd6a-2624">Подія відстежує чи відкриваються документи зі списку останніх використаних належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2624">The event monitors whether file-open-from-MRU is working as expected.</span></span> <span data-ttu-id="1bd6a-2625">І використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2625">It is also used to calculated monthly active users/devices, and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-2626">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2626">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2627">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2627">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-2628">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2628">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2629">**Data\_BytesAsynchronous –** Кількість байтів (стиснутих), без яких можна відкрити файл, якщо отримати їх, перш ніж користувач розпочне редагування або збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2629">**Data\_BytesAsynchronous -** Number of bytes (compressed) that we believe we can open the file without if we get them before the user wants to start editing or maybe saving</span></span>

  - <span data-ttu-id="1bd6a-2630">**Data\_BytesAsynchronousWithWork –** Кількість байтів (стиснутих), без яких можна відкрити файл, але для цього знадобиться значна робота з кодом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2630">**Data\_BytesAsynchronousWithWork -** Number of bytes (compressed) that we might be able to open the file without but would require significant code investments to make it happen</span></span>

  - <span data-ttu-id="1bd6a-2631">**Data\_BytesSynchronous –** Кількість байтів (стиснутих), яка потрібна для початку відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2631">**Data\_BytesSynchronous -** Number of bytes (compressed) that we must have before we can start opening the file</span></span>

  - <span data-ttu-id="1bd6a-2632">**Data\_BytesUnknown –** Кількість байтів у частинах документа, яку не очікувалося знайти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2632">**Data\_BytesUnknown -** Number of bytes in document parts that we don’t expect to find</span></span>

  - <span data-ttu-id="1bd6a-2633">**Data\_DetachedDuration –** Скільки часу потік був не активним</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2633">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-2634">**Data\_Doc\_AccessMode –** Документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2634">**Data\_Doc\_AccessMode -** Document is read-only/editable</span></span>

  - <span data-ttu-id="1bd6a-2635">**Data\_Doc\_AssistedReadingReasons –** Попередньо визначений набір значень причини відкриття документу в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2635">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2636">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2636">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2637">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2637">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-2638">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2638">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-2639">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2639">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2640">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2640">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-2641">**Data\_Doc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2641">**Data\_Doc\_FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-2642">**Data\_Doc\_IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2642">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2643">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2643">**Data\_Doc\_IdentityTelemetryId -** A one way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2644">**Data\_Doc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2644">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-2645">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2645">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2646">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2646">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2647">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2647">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2648">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2648">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2649">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2649">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2650">**Data\_Doc\_IsSyncBacked –** Позначка про авто синхронізовану копію документа на комп’ютері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2650">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto-synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2651">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2651">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-2652">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2652">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2653">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2653">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2654">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2654">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-2655">**Data\_Doc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2655">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2656">**Data\_Doc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2656">**Data\_Doc\_ResourceIdHash -** An anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2657">**Data\_Doc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2657">**Data\_Doc\_ServerDocId -** An immutable anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2658">**Data\_Doc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2658">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2659">**Data\_Doc\_ServerType –** Тип сервера послуг (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2659">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2660">**Data\_Doc\_ServerVersion –** Версія сервера, що надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2660">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2661">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2661">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-2662">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2662">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2663">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2663">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2664">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2664">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2665">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2665">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2666">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2666">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2667">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2667">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2668">**Data\_Doc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2668">**Data\_Doc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-2669">**Data\_EditorDisablingRename –** Ідентифікатор першого редактора, який спричинив заборону перейменування </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2669">**Data\_EditorDisablingRename -** Identifier of the first editor that caused for rename to be disabled</span></span>

  - <span data-ttu-id="1bd6a-2670">**Data\_EditorsCount –** Кількість редакторів в документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2670">**Data\_EditorsCount -** Number of editors in the document</span></span>

  - <span data-ttu-id="1bd6a-2671">**Data\_FSucceededAfterRecoverableFailure –** Вказує, що документ відкрився після виправлення помилки під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2671">**Data\_FSucceededAfterRecoverableFailure -** Indicates that open succeeded after repairing a failure while opening the document</span></span>

  - <span data-ttu-id="1bd6a-2672">**Data\_ForceReadWriteReason –** Ціле значення, яке позначає причину переведення файлу режим читання й записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2672">**Data\_ForceReadWriteReason -** Integer value representing the reason why the file was forced into read/write mode</span></span>

  - <span data-ttu-id="1bd6a-2673">**Data\_LastLoggedTag –** Унікальний тег кодового виклику сайту, що визначає спробу не виконувати відкриття двічі (використовується для діагностики якості даних)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2673">**Data\_LastLoggedTag -** Unique tag for code call site used to identify when we try to fail the open twice (used for data quality diagnostics)</span></span>

  - <span data-ttu-id="1bd6a-2674">**Data\_LinkStyles –** Вказує чи створюються посилання на стилі шаблонів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2674">**Data\_LinkStyles -** Indicates whether we are linking to the template styles</span></span>

  - <span data-ttu-id="1bd6a-2675">**Data\_MainPdod –** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2675">**Data\_MainPdod -** The document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2676">**Data\_Measurements –** Закодований рядок, що містить час розподілу різних частин відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2676">**Data\_Measurements -** Encoded string containing the time breakdown of the different parts of open.</span></span> <span data-ttu-id="1bd6a-2677">Використовується для вимірювання продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2677">Used to measure performance.</span></span>

  - <span data-ttu-id="1bd6a-2678">**Data\_MoveDisabledReason –** Помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2678">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-2679">**Data\_MoveFlightEnabled –** Вказує чи активовано тестування функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2679">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2680">**Data\_PartsUnknown –** Кількість частин документа, для яких не вдалося отримати дані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2680">**Data\_PartsUnknown -** the number of document parts that we couldn’t get data for</span></span>

  - <span data-ttu-id="1bd6a-2681">**Data\_RecoverableFailureInitiationLocationTag –** Унікальний тег кодового виклику сайту, який використовується, щоб позначити місце у коді, для спроби виправити файл перш ніж його відкривати</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2681">**Data\_RecoverableFailureInitiationLocationTag -** Unique tag for code call site used to identify the place in code where we attempt to fix the file before opening it</span></span>

  - <span data-ttu-id="1bd6a-2682">**Data\_RenameDisabledReason –** Помилка, що скасовує перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2682">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-2683">**Data\_RenameFlightEnabled –** Вказує чи активовано тестування функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2683">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2684">**Data\_SecondaryTag –** Унікальний тег кодового виклику сайту, який використовується, щоб додати дані про помилки для відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2684">**Data\_SecondaryTag -** Unique tag for code call site used to add additional failure data for open</span></span>

  - <span data-ttu-id="1bd6a-2685">**Data\_TemplateFormat –** Формат файлу шаблону, який є основою документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2685">**Data\_TemplateFormat -** File format of the template that the document is based on.</span></span>

  - <span data-ttu-id="1bd6a-2686">**Data\_UsesNormal –** Вказує чи базується відкритий документ на звичайному шаблоні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2686">**Data\_UsesNormal -** Indicates whether the open document is based on the normal template</span></span>

#### <a name="officewordfileopenopenffileopenxstzcore"></a><span data-ttu-id="1bd6a-2687">Office.Word.FileOpen.OpenFFileOpenXstzCore</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2687">Office.Word.FileOpen.OpenFFileOpenXstzCore</span></span>

<span data-ttu-id="1bd6a-2688">Ця подія вказує, що Office Word відкриває документ на який користувач клацнув двічі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2688">This event indicates Office Word opens a document who is double clicked by a user.</span></span> <span data-ttu-id="1bd6a-2689">І містить критичні дані продуктивності відкриття файлів. З точки зору користувача, це подія запуску програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2689">It also contains critical file open performance data, and is an app start event from user perspective.</span></span> <span data-ttu-id="1bd6a-2690">Подія відстежує чи відкривається файл на який клацнули двічі належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2690">The event monitors whether file-open-from-file-double-click is working as expected.</span></span> <span data-ttu-id="1bd6a-2691">І використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2691">It is also used to calculated monthly active users/devices, and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-2692">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2692">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2693">**Data\_AddDocTelemRes –** Повідомляє чи заповнені інші пов'язані значення телеметрії документів у події. </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2693">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-2694">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2694">Used for data quality diagnostics</span></span>

  - <span data-ttu-id="1bd6a-2695">**Data\_BytesAsynchronous –** Кількість байтів (стиснутих), без яких можна відкрити файл, якщо отримати їх, перш ніж користувач розпочне редагування або збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2695">**Data\_BytesAsynchronous -** Number of bytes (compressed) that we believe we can open the file without if we get them before the user wants to start editing or maybe saving</span></span>

  - <span data-ttu-id="1bd6a-2696">**Data\_BytesAsynchronousWithWork –** Кількість байтів (стиснутих), без яких можна відкрити файл, але для цього знадобиться значна робота з кодом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2696">**Data\_BytesAsynchronousWithWork -** Number of bytes (compressed) that we might be able to open the file without but would require significant code investments to make it happen</span></span>

  - <span data-ttu-id="1bd6a-2697">**Data\_BytesSynchronous –** Кількість байтів (стиснутих), яка потрібна для початку відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2697">**Data\_BytesSynchronous -** Number of bytes (compressed) that we must have before we can start opening the file</span></span>

  - <span data-ttu-id="1bd6a-2698">**Data\_BytesUnknown –** Кількість байтів у частинах документа, яку не очікувалося знайти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2698">**Data\_BytesUnknown -** Number of bytes in document parts that we don’t expect to find</span></span>

  - <span data-ttu-id="1bd6a-2699">**Data\_DetachedDuration –** Скільки часу потік був не активним</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2699">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-2700">**Data\_Doc\_AccessMode –** Документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2700">**Data\_Doc\_AccessMode -** Document is read-only/editable</span></span>

  - <span data-ttu-id="1bd6a-2701">**Data\_Doc\_AssistedReadingReasons –** Попередньо визначений набір значень причини відкриття документу в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2701">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2702">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2702">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2703">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2703">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-2704">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2704">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-2705">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2705">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2706">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2706">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-2707">**Data\_Doc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2707">**Data\_Doc\_FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-2708">**Data\_Doc\_IOFlags –** Повідомляє про кешовані позначки для встановлення параметрів запитів відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2708">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2709">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2709">**Data\_Doc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2710">**Data\_Doc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2710">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-2711">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2711">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2712">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2712">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2713">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2713">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2714">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2714">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2715">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2715">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2716">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2716">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2717">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2717">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-2718">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2718">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2719">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2719">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2720">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2720">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-2721">**Data\_Doc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2721">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2722">**Data\_Doc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2722">**Data\_Doc\_ResourceIdHash -** An anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2723">**Data\_Doc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2723">**Data\_Doc\_ServerDocId -** An immutable anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2724">**Data\_Doc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2724">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2725">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2725">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2726">**Data\_Doc\_ServerVersion –** Версія сервера, що надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2726">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2727">**Data\_Doc\_SessionId –** Версія сервера, що надає послуги</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2727">**Data\_Doc\_SessionId -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2728">**Data\_Doc\_SharePointServiceContext-**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2728">**Data\_Doc\_SharePointServiceContext-**</span></span>

  - <span data-ttu-id="1bd6a-2729">**Data\_Doc\_SizeInBytes –** Індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2729">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2730">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2730">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2731">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2731">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2732">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2732">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2733">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2733">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2734">**Data\_Doc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2734">**Data\_Doc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-2735">**Data\_EditorDisablingRename –** Ідентифікатор першого редактора, який спричинив заборону перейменування </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2735">**Data\_EditorDisablingRename -** Identifier of the first editor that caused for rename to be disabled</span></span>

  - <span data-ttu-id="1bd6a-2736">**Data\_EditorsCount –** Кількість редакторів в документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2736">**Data\_EditorsCount -** Number of editors in the document</span></span>

  - <span data-ttu-id="1bd6a-2737">**Data\_FSucceededAfterRecoverableFailure –** Вказує, що документ відкрився після виправлення помилки під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2737">**Data\_FSucceededAfterRecoverableFailure -** Indicates that open succeeded after repairing a failure while opening the document</span></span>

  - <span data-ttu-id="1bd6a-2738">**Data\_ForceReadWriteReason –** Ціле значення, яке позначає причину переведення файлу режим читання й записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2738">**Data\_ForceReadWriteReason -** Integer value representing the reason why the file was forced into read/write mode</span></span>

  - <span data-ttu-id="1bd6a-2739">**Data\_LastLoggedTag –** Унікальний тег кодового виклику сайту, що визначає спробу не виконувати відкриття двічі (використовується для діагностики якості даних)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2739">**Data\_LastLoggedTag -** Unique tag for code call site used to identify when we try to fail the open twice (used for data quality diagnostics)</span></span>

  - <span data-ttu-id="1bd6a-2740">**Data\_LinkStyles –** Вказує чи створюються посилання на стилі шаблонів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2740">**Data\_LinkStyles -** Indicates whether we are linking to the template styles</span></span>

  - <span data-ttu-id="1bd6a-2741">**Data\_MainPdod –** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2741">**Data\_MainPdod -** The document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2742">**Data\_Measurements –** Закодований рядок, що містить час розподілу різних частин відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2742">**Data\_Measurements -** Encoded string containing the time breakdown of the different parts of open.</span></span> <span data-ttu-id="1bd6a-2743">Використовується для вимірювання продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2743">Used to measure performance.</span></span>

  - <span data-ttu-id="1bd6a-2744">**Data\_MoveDisabledReason –** Помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2744">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-2745">**Data\_MoveFlightEnabled –** Вказує чи активовано тестування функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2745">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2746">**Data\_PartsUnknown –** Кількість частин документа, для яких не вдалося отримати дані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2746">**Data\_PartsUnknown -** the number of document parts that we couldn’t get data for</span></span>

  - <span data-ttu-id="1bd6a-2747">**Data\_RecoverableFailureInitiationLocationTag -** Унікальний тег кодового виклику сайту, який використовується, щоб позначити місце у коді, для спроби виправити файл перш ніж його відкривати.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2747">**Data\_RecoverableFailureInitiationLocationTag -** Unique tag for code call site used to identify the place in code where we attempt to fix the file before opening it.</span></span>

  - <span data-ttu-id="1bd6a-2748">**Data\_RenameDisabledReason –** Помилка, що скасовує перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2748">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-2749">**Data\_RenameFlightEnabled –** Вказує чи активовано тестування функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2749">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2750">**Data\_SecondaryTag –** Унікальний тег кодового виклику сайту, який використовується, щоб додати дані про помилки для відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2750">**Data\_SecondaryTag -** Unique tag for code call site used to add additional failure data for open.</span></span>

  - <span data-ttu-id="1bd6a-2751">**Data\_TemplateFormat –** Формат файлу шаблону, який є основою документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2751">**Data\_TemplateFormat -** File format of the template that the document is based on.</span></span>

  - <span data-ttu-id="1bd6a-2752">**Data\_UsesNormal –** Вказує чи базується відкритий документ на звичайному шаблоні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2752">**Data\_UsesNormal -** Indicates whether the open document is based on the normal template</span></span>


#### <a name="officewordfileopenopenifrinitargs"></a><span data-ttu-id="1bd6a-2753">Office.Word.FileOpen.OpenIfrInitArgs</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2753">Office.Word.FileOpen.OpenIfrInitArgs</span></span>

<span data-ttu-id="1bd6a-2754">Ця подія вказує, що Office Word відкриває документ за допомогою активації COM або командного рядка.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2754">This event indicates Office Word opens a document via COM activation or command line.</span></span> <span data-ttu-id="1bd6a-2755">А також містить критичні дані продуктивності відкриття файлів. З точки зору користувача, це подія запуску програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2755">It also contains critical file open performance data, and is an app start event from user perspective.</span></span> <span data-ttu-id="1bd6a-2756">Подія відстежує чи відкривається файл з командного рядка належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2756">The event monitors whether file-open-from-command-line is working as expected.</span></span> <span data-ttu-id="1bd6a-2757">І використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2757">It is also used to calculated monthly active users/devices, and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-2758">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2758">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2759">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2759">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-2760">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2760">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2761">**Data\_BytesAsynchronous -** Кількість байтів (стиснутих), без яких можна відкрити файл, якщо отримати їх, перш ніж користувач розпочне редагування або збереження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2761">**Data\_BytesAsynchronous -** Number of bytes (compressed) that we believe we can open the file without if we get them before the user wants to start editing or maybe saving.</span></span>

  - <span data-ttu-id="1bd6a-2762">**Data\_BytesAsynchronousWithWork –** Кількість байтів (стиснутих), без яких можна відкрити файл, але для цього знадобиться значна робота з кодом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2762">**Data\_BytesAsynchronousWithWork -** Number of bytes (compressed) that we might be able to open the file without but would require significant code investments to make it happen</span></span>

  - <span data-ttu-id="1bd6a-2763">**Data\_BytesSynchronous –** Кількість байтів (стиснутих), яка потрібна для початку відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2763">**Data\_BytesSynchronous -** Number of bytes (compressed) that we must have before we can start opening the file</span></span>

  - <span data-ttu-id="1bd6a-2764">**Data\_BytesUnknown -** Кількість байтів у частинах документа, яку не очікувалося знайти.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2764">**Data\_BytesUnknown -** Number of bytes in document parts that we don’t expect to find.</span></span>

  - <span data-ttu-id="1bd6a-2765">**Data\_Doc\_AccessMode –** Документ тільки для читання/редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2765">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-2766">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2766">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2767">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2767">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2768">**Data\_Doc\_EdpState –** Параметр електронного захисту даних документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2768">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-2769">**Data\_Doc\_Ext –** Розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2769">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2770">**Data\_Doc\_FileFormat –** Версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2770">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2771">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2771">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-2772">**Data\_Doc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2772">**Data\_Doc\_FqdnHash -** One-way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-2773">**Data\_Doc\_IOFlags –** Повідомляє про кешовані позначки для встановлення параметрів запитів відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2773">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2774">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2774">**Data\_Doc\_IdentityTelemetryId -** A one-way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2775">**Data\_Doc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2775">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-2776">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2776">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2777">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2777">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2778">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2778">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2779">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2779">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2780">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2780">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2781">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2781">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2782">**Data\_Doc\_Location –** указує службу, яка надала документ (OneDrive, файловий сервер, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2782">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint)</span></span>

  - <span data-ttu-id="1bd6a-2783">**Data\_Doc\_LocationDetails –** Вказує відому папку з локально збереженим документом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2783">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2784">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2784">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2785">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2785">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-2786">**Data\_Doc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2786">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2787">**Data\_Doc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2787">**Data\_Doc\_ResourceIdHash -** An anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2788">**Data\_Doc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2788">**Data\_Doc\_ServerDocId -** An immutable anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2789">**Data\_Doc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2789">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2790">**Data\_Doc\_ServerType** – тип сервера, який надає службу (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2790">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI etc.)</span></span>

  - <span data-ttu-id="1bd6a-2791">**Data\_Doc\_ServerVersion –** Версія сервера, що надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2791">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2792">**Data\_Doc\_SessionId –** Версія сервера, що надає послуги</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2792">**Data\_Doc\_SessionId -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2793">**Data\_Doc\_SharePointServiceContext –** Діагностичні відомості запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2793">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2794">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2794">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2795">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2795">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2796">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2796">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2797">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2797">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2798">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2798">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2799">**Data\_Doc\_WopiServiceId –** Містить унікальний ідентифікатор постачальника послуг WOPI</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2799">**Data\_Doc\_WopiServiceId -** Contains unique identifier of WOPI service provider</span></span>

  - <span data-ttu-id="1bd6a-2800">**Data\_EditorDisablingRename –** Ідентифікатор першого редактора, який спричинив заборону перейменування </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2800">**Data\_EditorDisablingRename -** Identifier of the first editor that caused for rename to be disabled</span></span>

  - <span data-ttu-id="1bd6a-2801">**Data\_EditorsCount –** Кількість редакторів в документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2801">**Data\_EditorsCount -** Number of editors in the document</span></span>

  - <span data-ttu-id="1bd6a-2802">**Data\_FSucceededAfterRecoverableFailure –** Вказує, що документ відкрився після виправлення помилки під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2802">**Data\_FSucceededAfterRecoverableFailure -** Indicates that open succeeded after repairing a failure while opening the document</span></span>

  - <span data-ttu-id="1bd6a-2803">**Data\_ForceReadWriteReason –** Ціле значення, яке позначає причину переведення файлу режим читання й записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2803">**Data\_ForceReadWriteReason -** Integer value representing the reason why the file was forced into read/write mode</span></span>

  - <span data-ttu-id="1bd6a-2804">**Data\_LastLoggedTag –** Унікальний тег кодового виклику сайту, що визначає спробу не виконувати відкриття двічі (використовується для діагностики якості даних)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2804">**Data\_LastLoggedTag -** Unique tag for code call site used to identify when we try to fail the open twice (used for data quality diagnostics)</span></span>

  - <span data-ttu-id="1bd6a-2805">**Data\_LinkStyles –** Вказує чи створюються посилання на стилі шаблонів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2805">**Data\_LinkStyles -** Indicates whether we are linking to the template styles</span></span>

  - <span data-ttu-id="1bd6a-2806">**Data\_MainPdod –** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2806">**Data\_MainPdod -** The document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2807">**Data\_Measurements –** Закодований рядок, що містить час розподілу різних частин відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2807">**Data\_Measurements -** Encoded string containing the time breakdown of the different parts of open.</span></span> <span data-ttu-id="1bd6a-2808">Використовується для діагностики продуктивності відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2808">Used to diagnose open performance.</span></span>

  - <span data-ttu-id="1bd6a-2809">**Data\_MoveDisabledReason –** Помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2809">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-2810">**Data\_MoveFlightEnabled –** Вказує чи активовано тестування функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2810">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2811">**Data\_PartsUnknown –** Кількість частин документа, для яких не вдалося отримати дані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2811">**Data\_PartsUnknown -** the number of document parts that we couldn’t get data for</span></span>

  - <span data-ttu-id="1bd6a-2812">**Data\_RecoverableFailureInitiationLocationTag –** Унікальний тег кодового виклику сайту, який використовується, щоб позначити місце у коді, для спроби виправити файл перш ніж його відкривати</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2812">**Data\_RecoverableFailureInitiationLocationTag -** Unique tag for code call site used to identify the place in code where we attempt to fix the file before opening it</span></span>

  - <span data-ttu-id="1bd6a-2813">**Data\_RenameDisabledReason –** Помилка, що скасовує перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2813">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-2814">**Data\_RenameFlightEnabled –** Вказує чи активовано тестування функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2814">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2815">**Data\_SecondaryTag –** Унікальний тег кодового виклику сайту, який використовується, щоб додати дані про помилки для відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2815">**Data\_SecondaryTag -** Unique tag for code call site used to add additional failure data for open.</span></span>

  - <span data-ttu-id="1bd6a-2816">**Data\_TemplateFormat –** Формат файлу шаблону, який є основою документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2816">**Data\_TemplateFormat -** File format of the template that the document is based on.</span></span>

  - <span data-ttu-id="1bd6a-2817">**Data\_UsesNormal –** Вказує чи базується відкритий документ на звичайному шаблоні.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2817">**Data\_UsesNormal -** Indicates whether the open document is based on the normal template.</span></span>


#### <a name="officewordfileopenopenloadfile"></a><span data-ttu-id="1bd6a-2818">Office.Word.FileOpen.OpenLoadFile</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2818">Office.Word.FileOpen.OpenLoadFile</span></span>

<span data-ttu-id="1bd6a-2819">Ця подія вказує, що Office Word відкриває документ за допомогою діалогового вікна «Відкрити».</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2819">This event indicates Office Word opens a document via Open dialog.</span></span> <span data-ttu-id="1bd6a-2820">А також містить критичні дані продуктивності відкриття файлів. З точки зору користувача, це подія запуску програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2820">It also contains critical file open performance data, and is an app start event from user perspective.</span></span> <span data-ttu-id="1bd6a-2821">Подія відстежує чи відкривається файл за допомогою діалогового вікна «Відкрити» належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2821">The event monitors whether file-open-from-the-open-file-dialog is working as expected.</span></span> <span data-ttu-id="1bd6a-2822">І використовується для обчислення щомісячних активних користувачів/пристроїв і хмарних показників стабільності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2822">It is also used to calculated monthly active users/devices, and cloud reliability metrics.</span></span>

<span data-ttu-id="1bd6a-2823">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2823">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2824">**Data\_AddDocTelemRes** – повідомляє, чи вдалося правильно надати в події інші значення, пов’язані з телеметрією документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2824">**Data\_AddDocTelemRes -** Reports whether we were able to properly populate other document telemetry related values in the event.</span></span> <span data-ttu-id="1bd6a-2825">Використовується для діагностики якості даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2825">Used for data quality diagnostics.</span></span>

  - <span data-ttu-id="1bd6a-2826">**Data\_BytesAsynchronous –** Кількість байтів (стиснутих), без яких можна відкрити файл, якщо отримати їх, перш ніж користувач розпочне редагування або збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2826">**Data\_BytesAsynchronous -** Number of bytes (compressed) that we believe we can open the file without if we get them before the user wants to start editing or maybe saving</span></span>

  - <span data-ttu-id="1bd6a-2827">**Data\_BytesAsynchronousWithWork –** Кількість байтів (стиснутих), без яких можна відкрити файл, але для цього знадобиться значна робота з кодом</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2827">**Data\_BytesAsynchronousWithWork -** Number of bytes (compressed) that we might be able to open the file without but would require significant code investments to make it happen</span></span>

  - <span data-ttu-id="1bd6a-2828">**Data\_BytesSynchronous –** Кількість байтів (стиснутих), яка потрібна для початку відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2828">**Data\_BytesSynchronous -** Number of bytes (compressed) that we must have before we can start opening the file</span></span>

  - <span data-ttu-id="1bd6a-2829">**Data\_BytesUnknown –** Кількість байтів у частинах документа, яку не очікувалося знайти</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2829">**Data\_BytesUnknown -** Number of bytes in document parts that we don’t expect to find</span></span>

  - <span data-ttu-id="1bd6a-2830">**Data\_DetachedDuration –** Скільки часу потік був не активним</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2830">**Data\_DetachedDuration -** How long was the activity detached from the thread</span></span>

  - <span data-ttu-id="1bd6a-2831">**Data\_Doc\_AccessMode** – документ лише для читання/доступний для редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2831">**Data\_Doc\_AccessMode -** Document is read only/editable</span></span>

  - <span data-ttu-id="1bd6a-2832">**Data\_Doc\_AssistedReadingReasons** – попередньо визначений набір значень причини відкриття документа в режимі читання з підтримкою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2832">**Data\_Doc\_AssistedReadingReasons -** Predefined set of values of why document was opened in assisted reading mode</span></span>

  - <span data-ttu-id="1bd6a-2833">**Data\_Doc\_ChunkingType** – одиниці, які використовуються для інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2833">**Data\_Doc\_ChunkingType -** Units used for incremental document open</span></span>

  - <span data-ttu-id="1bd6a-2834">**Data\_Doc\_EdpState** – параметр електронного захисту даних для документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2834">**Data\_Doc\_EdpState -** Electronic Data Protection setting for the document</span></span>

  - <span data-ttu-id="1bd6a-2835">**Data\_Doc\_Ext** – розширення документа (docx/xlsb/pptx тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2835">**Data\_Doc\_Ext -** Document extension (docx/xlsb/pptx etc.)</span></span>

  - <span data-ttu-id="1bd6a-2836">**Data\_Doc\_FileFormat** – версія протоколу формату файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2836">**Data\_Doc\_FileFormat -** File format protocol version</span></span>

  - <span data-ttu-id="1bd6a-2837">**Data\_Doc\_Fqdn** – ім'я домену OneDrive або SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2837">**Data\_Doc\_Fqdn -** OneDrive or SharePoint Online Domain Name</span></span>

  - <span data-ttu-id="1bd6a-2838">**Data\_Doc\_FqdnHash –** Одностороннє гешування особистого ім’я домену користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2838">**Data\_Doc\_FqdnHash -** One way hash of customer identifiable domain name</span></span>

  - <span data-ttu-id="1bd6a-2839">**Data\_Doc\_IdentityTelemetryId –** Одностороннє гешування ідентифікації користувача при відкритті</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2839">**Data\_Doc\_IdentityTelemetryId -** A one way hash of the user identity used to perform the open</span></span>

  - <span data-ttu-id="1bd6a-2840">**Data\_Doc\_InitializationScenario –** Звіт про спосіб відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2840">**Data\_Doc\_InitializationScenario -** Records how the document was opened</span></span>

  - <span data-ttu-id="1bd6a-2841">**Data\_Doc\_IOFlags** – повідомляє про кешовані позначки для встановлення параметрів запитів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2841">**Data\_Doc\_IOFlags -** Reports on the cached flags used to set open request options</span></span>

  - <span data-ttu-id="1bd6a-2842">**Data\_Doc\_IrmRights** – дії, дозволені політикою електронного захисту даних і застосовані до документа/користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2842">**Data\_Doc\_IrmRights -** Actions permitted by the Electronic Data Protection policy that has been applied to the document/user</span></span>

  - <span data-ttu-id="1bd6a-2843">**Data\_Doc\_IsIncrementalOpen** – позначка інкрементного відкриття документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2843">**Data\_Doc\_IsIncrementalOpen -** Flag indicating that the document has been incrementally opened</span></span>

  - <span data-ttu-id="1bd6a-2844">**Data\_Doc\_IsOcsSupported** – позначка, яка вказує, що документ підтримується у службі співпраці</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2844">**Data\_Doc\_IsOcsSupported -** Flag indicating that the document is supported in the collaboration service</span></span>

  - <span data-ttu-id="1bd6a-2845">**Data\_Doc\_IsOpeningOfflineCopy** – позначка відкриття автономної копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2845">**Data\_Doc\_IsOpeningOfflineCopy -** Flag indicating that the offline copy of a document was opened</span></span>

  - <span data-ttu-id="1bd6a-2846">**Data_Doc_IsRtcAlwaysOn** – має значення true, якщо в цьому файлі постійно ввімкнуто співпрацю в реальному часі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2846">**Data_Doc_IsRtcAlwaysOn -** true if the real time channel (RTC) is always on for this file.</span></span>

  - <span data-ttu-id="1bd6a-2847">**Data\_Doc\_IsSyncBacked** – позначка існування на комп’ютері автосинхронізованої копії документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2847">**Data\_Doc\_IsSyncBacked -** Flag indicating that an auto synced copy of the document exists on the computer</span></span>

  - <span data-ttu-id="1bd6a-2848">**Data\_Doc\_Location –** Вказує службу, що надала документ (OneDrive, File Server, SharePoint тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2848">**Data\_Doc\_Location -** Indicates which service provided the document (OneDrive, File Server, SharePoint etc.)</span></span>

  - <span data-ttu-id="1bd6a-2849">**Data\_Doc\_LocationDetails** – указує, з якої відомої папки надано локальний документ</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2849">**Data\_Doc\_LocationDetails -** Indicates which Known Folder provided a locally stored document</span></span>

  - <span data-ttu-id="1bd6a-2850">**Data\_Doc\_NumberCoAuthors** – кількість користувачів у сеансі спільного редагування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2850">**Data\_Doc\_NumberCoAuthors -** Count of the number of fellow users in a collaborative editing session</span></span>

  - <span data-ttu-id="1bd6a-2851">**Data\_Doc\_PasswordFlags** – установлені позначки паролю на читання або читання/записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2851">**Data\_Doc\_PasswordFlags -** Indicates read or read/write password flags set</span></span>

  - <span data-ttu-id="1bd6a-2852">**Data\_Doc\_ReadOnlyReasons –** Причини з яких документ відкрито лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2852">**Data\_Doc\_ReadOnlyReasons -** Reasons why the document was opened read only</span></span>

  - <span data-ttu-id="1bd6a-2853">**Data\_Doc\_ResourceIdHash –** Анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2853">**Data\_Doc\_ResourceIdHash -** An anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2854">**Data\_Doc\_ServerDocId –** Незмінний анонімний ідентифікатор документа для діагностики проблем</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2854">**Data\_Doc\_ServerDocId -** An immutable anonymized document Identifier used to diagnose problems</span></span>

  - <span data-ttu-id="1bd6a-2855">**Data\_Doc\_ServerProtocol –** Версія протоколу, що використовується для зв'язку зі службою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2855">**Data\_Doc\_ServerProtocol -** the protocol version used to communicate with the service</span></span>

  - <span data-ttu-id="1bd6a-2856">**Data\_Doc\_ServerType –** Тип сервера послуг (SharePoint, OneDrive, WOPI тощо)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2856">**Data\_Doc\_ServerType -** the type of the server offering the service (SharePoint, OneDrive, WOPI, etc.)</span></span>

  - <span data-ttu-id="1bd6a-2857">**Data\_Doc\_ServerVersion –** Версія сервера, що надає службу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2857">**Data\_Doc\_ServerVersion -** the server version offering the service</span></span>

  - <span data-ttu-id="1bd6a-2858">**Data\_Doc\_SessionId** – визначає сеанс редагування документа в межах повного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2858">**Data\_Doc\_SessionId -** Identifies a specific document edit session within the full session</span></span>

  - <span data-ttu-id="1bd6a-2859">**Data\_Doc\_SharePointServiceContext** – діагностичні відомості із запитів SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2859">**Data\_Doc\_SharePointServiceContext -** Diagnostic information from SharePoint Online requests</span></span>

  - <span data-ttu-id="1bd6a-2860">**Data\_Doc\_SizeInBytes** – індикатор розміру документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2860">**Data\_Doc\_SizeInBytes -** Indicator of document size</span></span>

  - <span data-ttu-id="1bd6a-2861">**Data\_Doc\_SpecialChars** – індикатор спеціальних символів URL-адреси або шляху документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2861">**Data\_Doc\_SpecialChars -** Indicator of special chars in the document's URL or Path</span></span>

  - <span data-ttu-id="1bd6a-2862">**Data\_Doc\_StreamAvailability** – індикатор, що вказує, доступний чи вимкнений потік документів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2862">**Data\_Doc\_StreamAvailability -** Indicator if document stream is available/disabled</span></span>

  - <span data-ttu-id="1bd6a-2863">**Data\_Doc\_SyncBackedType** – індикатор типу документа (локальний чи зі служби)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2863">**Data\_Doc\_SyncBackedType -** Indicator as to the type of document (local or service based)</span></span>

  - <span data-ttu-id="1bd6a-2864">**Data\_Doc\_UrlHash –** Одностороннє гешування для створення простуватого ідентифікатора документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2864">**Data\_Doc\_UrlHash -** One-way hash to create a naïve document identifier</span></span>

  - <span data-ttu-id="1bd6a-2865">**Data\_EditorDisablingRename –** Ідентифікатор першого редактора, який спричинив заборону перейменування </span><span class="sxs-lookup"><span data-stu-id="1bd6a-2865">**Data\_EditorDisablingRename -** Identifier of the first editor that caused for rename to be disabled</span></span>

  - <span data-ttu-id="1bd6a-2866">**Data\_EditorsCount –** Кількість редакторів в документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2866">**Data\_EditorsCount -** Number of editors in the document</span></span>

  - <span data-ttu-id="1bd6a-2867">**Data\_ForceReadWriteReason –** Ціле значення, яке позначає причину переведення файлу режим читання й записування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2867">**Data\_ForceReadWriteReason -** Integer value representing the reason why the file was forced into read/write mode</span></span>

  - <span data-ttu-id="1bd6a-2868">**Data\_FSucceededAfterRecoverableFailure –** Вказує, що документ відкрився після виправлення помилки під час відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2868">**Data\_FSucceededAfterRecoverableFailure -** Indicates that open succeeded after repairing a failure while opening the document</span></span>

  - <span data-ttu-id="1bd6a-2869">**Data\_LastLoggedTag –** Унікальний тег кодового виклику сайту, що визначає помилку при збереженні двічі (використовується для діагностики якості даних)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2869">**Data\_LastLoggedTag -** Unique tag for code call site used to identify when we fail to try the save twice (used for data quality diagnostics)</span></span>

  - <span data-ttu-id="1bd6a-2870">**Data\_LinkStyles –** Вказує чи створюються посилання на стилі шаблонів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2870">**Data\_LinkStyles -** Indicates whether we are linking to the template styles</span></span>

  - <span data-ttu-id="1bd6a-2871">**Data\_MainPdod –** Ідентифікатор документа в Office Word</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2871">**Data\_MainPdod -** The document identifier in Office Word process</span></span>

  - <span data-ttu-id="1bd6a-2872">**Data\_Measurements –** Закодований рядок, що містить час розподілу різних частин відкриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2872">**Data\_Measurements -** Encoded string containing the time breakdown of the different parts of open.</span></span> <span data-ttu-id="1bd6a-2873">Використовується для вимірювання продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2873">Used to measure performance.</span></span>

  - <span data-ttu-id="1bd6a-2874">**Data\_MoveDisabledReason –** Помилка, що вимикає переміщення до документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2874">**Data\_MoveDisabledReason -** Error that is disabling move for the document</span></span>

  - <span data-ttu-id="1bd6a-2875">**Data\_MoveFlightEnabled –** Вказує чи активовано тестування функції переміщення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2875">**Data\_MoveFlightEnabled -** Whether the flight for the move feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2876">**Data\_PartsUnknown –** Кількість частин документа, для яких не вдалося отримати дані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2876">**Data\_PartsUnknown -** the number of document parts that we couldn’t get data for</span></span>

  - <span data-ttu-id="1bd6a-2877">**Data\_RecoverableFailureInitiationLocationTag –** Унікальний тег кодового виклику сайту, який використовується, щоб позначити місце у коді, для спроби виправити файл перш ніж його відкривати</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2877">**Data\_RecoverableFailureInitiationLocationTag -** Unique tag for code call site used to identify the place in code where we attempt to fix the file before opening it</span></span>

  - <span data-ttu-id="1bd6a-2878">**Data\_RenameDisabledReason –** Помилка, що скасовує перейменування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2878">**Data\_RenameDisabledReason -** Error that is causing for rename to be disabled for this document</span></span>

  - <span data-ttu-id="1bd6a-2879">**Data\_RenameFlightEnabled –** Вказує чи активовано тестування функції перейменування</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2879">**Data\_RenameFlightEnabled -** Whether the flight for the rename feature is enabled</span></span>

  - <span data-ttu-id="1bd6a-2880">**Data\_SecondaryTag –** Унікальний тег кодового виклику сайту, який використовується, щоб додати дані про помилки для відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2880">**Data\_SecondaryTag -** Unique tag for code call site used to add additional failure data for open</span></span>

  - <span data-ttu-id="1bd6a-2881">**Data\_TemplateFormat -** Формат файлу шаблону, який є основою документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2881">**Data\_TemplateFormat -** File format of the template that the document is based on</span></span>

  - <span data-ttu-id="1bd6a-2882">**Data\_UsesNormal -** Вказує чи базується відкритий документ на звичайному шаблоні</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2882">**Data\_UsesNormal** - Indicates whether the open document is based on the normal template</span></span>


### <a name="office-accessibility-configuration-subtype"></a><span data-ttu-id="1bd6a-2883">\* Підтип конфігурації спеціальних можливостей Office\*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2883">*Office accessibility configuration subtype*</span></span>

<span data-ttu-id="1bd6a-2884">Функції спеціальних можливостей Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2884">Office accessibility features</span></span>

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a><span data-ttu-id="1bd6a-2885">Office.Accessibility.AccessibilityToolSessionPresenceWin32</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2885">Office.Accessibility.AccessibilityToolSessionPresenceWin32</span></span>

<span data-ttu-id="1bd6a-2886">Дає змогу визначати інструмент спеціальних можливостей, що має користувач і його назву.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2886">Allows us to detect that the user has an Assistive technology tool and its name.</span></span> <span data-ttu-id="1bd6a-2887">Це дозволяє зрозуміти, чи виникають у користувача служби Office проблеми з інструментом спеціальних можливостей.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2887">This allows us to understand if an Office user is experiencing issues with a specific Assistive Technology tool.</span></span>

<span data-ttu-id="1bd6a-2888">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2888">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2889">**Data\_Data\_Jaws –** вказує, чи працює Jaws під час сеансу **Data\_Data\_Magic –** вказує, чи працює Magic під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2889">**Data\_Data\_Jaws -** indicates if Jaws was running during the session**Data\_Data\_Magic -** indicates if Magic was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2890">**Data\_Data\_Magnify –** вказує, чи працює Magnify під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2890">**Data\_Data\_Magnify -** indicates if Magnify was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2891">**Data\_Data\_Narrator –** вказує, чи працює Narrator під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2891">**Data\_Data\_Narrator -** indicates if Narrator was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2892">**Data\_Data\_NVDA –** вказує, чи працює NVDA під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2892">**Data\_Data\_NVDA -** indicates if NVDA was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2893">**Data\_Data\_SA –** вказує, чи працює SA під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2893">**Data\_Data\_SA -** indicates if SA was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2894">**Data\_Data\_Supernova –** вказує, чи працює Supernova під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2894">**Data\_Data\_Supernova -** indicates if Supernova was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2895">**Data\_Data\_SuperNovaessSuite –** вказує, чи працює SuperNovaAccessSuite під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2895">**Data\_Data\_SuperNovaessSuite -** indicates if SuperNovaAccessSuite was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2896">**Data\_Data\_WinEyes –** вказує, чи працює WinEyes під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2896">**Data\_Data\_WinEyes -** indicates if WinEyes was running during the session</span></span>

  - <span data-ttu-id="1bd6a-2897">**Data\_Data\_ZoomText –** вказує, чи працює ZoomText під час сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2897">**Data\_Data\_ZoomText -** indicates if ZoomText was running during the session</span></span>

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a><span data-ttu-id="1bd6a-2898">Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2898">Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud</span></span>

<span data-ttu-id="1bd6a-2899">Ця подія вказує, що Office Word зачитує текст у документі вголос.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2899">This event indicates Office Word reads aloud the text in the document.</span></span> <span data-ttu-id="1bd6a-2900">Подія підтверджує функціонування спеціальних можливостей, що дає змогу Microsoft оцінити справність функції читання тексту вголос.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2900">The event is a heartbeat of the accessibility feature which allows Microsoft to evaluate the feature health of read-aloud-text.</span></span>

<span data-ttu-id="1bd6a-2901">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2901">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2902">**Data\_CharacterCount –** кількість символів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2902">**Data\_CharacterCount -** character count of the document</span></span>

  - <span data-ttu-id="1bd6a-2903">**Data\_CharactersWithSpaceCount –** кількість символів разом з пробілами у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2903">**Data\_CharactersWithSpaceCount -** character and space count of the document</span></span>

  - <span data-ttu-id="1bd6a-2904">**Data\_IsPageCountInProgress –** чи виконується підрахунок сторінок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2904">**Data\_IsPageCountInProgress -** is the page count in progress</span></span>

  - <span data-ttu-id="1bd6a-2905">**Data\_LineCount –** кількість рядків у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2905">**Data\_LineCount -** line count of the document</span></span>

  - <span data-ttu-id="1bd6a-2906">**Data\_PageCount –** кількість сторінок документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2906">**Data\_PageCount -** page count of the document</span></span>

  - <span data-ttu-id="1bd6a-2907">**Data\_ParagraphCount –** кількість абзаців у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2907">**Data\_ParagraphCount -** paragraph count of the document</span></span>

  - <span data-ttu-id="1bd6a-2908">**Data\_Play –** чи вперше Word читає вголос</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2908">**Data\_Play -** Is this the first time for Word to read aloud</span></span>

  - <span data-ttu-id="1bd6a-2909">**Data\_ViewKind –** перегляд типу документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2909">**Data\_ViewKind -** view type of the document</span></span>

  - <span data-ttu-id="1bd6a-2910">**Data\_WordCount –** кількість слів у документі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2910">**Data\_WordCount -** word count of the document</span></span>

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a><span data-ttu-id="1bd6a-2911">Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2911">Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud</span></span>

<span data-ttu-id="1bd6a-2912">Ця подія вказує, що Office Word припиняє читання тексту в документі вголос.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2912">This event indicates Office Word stops reading aloud the text in the document.</span></span> <span data-ttu-id="1bd6a-2913">Подія дозволяє Microsoft оцінити справність функції читання тексту вголос, за допомогою вимірювання тривалості її роботи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2913">The event allows Microsoft to evaluate the feature health of read-aloud-text by measuring the working duration.</span></span>

<span data-ttu-id="1bd6a-2914">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2914">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2915">Нічого</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2915">None</span></span>

### <a name="privacy-subtype"></a><span data-ttu-id="1bd6a-2916">*Підтип конфіденційності*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2916">*Privacy subtype*</span></span>

<span data-ttu-id="1bd6a-2917">Настройки конфіденційності Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2917">Office privacy settings</span></span> 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a><span data-ttu-id="1bd6a-2918">Office.IntelligentService.PrivacyConsent.PrivacyEvent</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2918">Office.IntelligentService.PrivacyConsent.PrivacyEvent</span></span>

<span data-ttu-id="1bd6a-2919">Ця подія представляє дію користувача або системи в рамках взаємодії користувача з Office у справах конфіденційності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2919">This event represents a user or system initiated action that is part of the privacy User experience for Office.</span></span> <span data-ttu-id="1bd6a-2920">Вона активується в діалогових вікнах першого запуску системи конфіденційності, діалоговому вікні "Конфіденційність облікових записів" і сповіщеннях про конфіденційність.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2920">It is triggered on the privacy First Run dialogs, Account Privacy dialog, and privacy notifications.</span></span> <span data-ttu-id="1bd6a-2921">Ця подія сповіщає, що користувачі погоджуються з настройками конфіденційності Office, що користувачі змінюють настройки конфіденційності Office, а також що настройки конфіденційності Office оновлюються в сеансах користувачів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2921">The event is used to understand the following: users consenting to Office privacy settings, users changing Office privacy settings, and Office privacy settings getting updated in user sessions.</span></span>

<span data-ttu-id="1bd6a-2922">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2922">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2923">**Data_ActionId** – дія користувача в діалоговому вікні конфіденційності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2923">**Data_ActionId -** User action in a privacy dialog</span></span>

  - <span data-ttu-id="1bd6a-2924">**Data_ControllerConnectedServicesState** – параметр політики користувача для додаткових необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2924">**Data_ControllerConnectedServicesState -** User policy setting for additional optional connected experiences</span></span>

  - <span data-ttu-id="1bd6a-2925">**Data_DownloadedContentServiceGroupState** – настройка користувача для завантаженого вмісту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2925">**Data_DownloadedContentServiceGroupState -** User setting for downloaded content</span></span> 
 
  - <span data-ttu-id="1bd6a-2926">**Data_ForwardLinkId** – посилання на документацію з конфіденційності для сценарію користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2926">**Data_ForwardLinkId -** Link to privacy documentation for the user scenario</span></span>

  - <span data-ttu-id="1bd6a-2927">**Data_HRESULT** – запис помилок під час взаємодії з діалоговим вікном конфіденційності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2927">**Data_HRESULT -** Record of errors during interaction with a privacy dialog</span></span>

  - <span data-ttu-id="1bd6a-2928">**Data_IsEnterpriseUser** – категорія ліцензії користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2928">**Data_IsEnterpriseUser -** User license category</span></span>

  - <span data-ttu-id="1bd6a-2929">**Data_OfficeServiceConnectionState** – настройка користувача для підключених служб</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2929">**Data_OfficeServiceConnectionState -** User setting for connected services</span></span>

  - <span data-ttu-id="1bd6a-2930">**Data_RecordRegistry** – запис відображення діалогового вікна корпоративної конфіденційності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2930">**Data_RecordRegistry -** Record of showing the enterprise privacy dialog</span></span>

  - <span data-ttu-id="1bd6a-2931">**Data_Scenario** – сценарій першого запуску виходячи з ліцензії та категорії користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2931">**Data_Scenario -** First run scenario based on the user license and category</span></span>

  - <span data-ttu-id="1bd6a-2932">**Data_SeenInsidersDialog** – запис відображення діалогового вікна конфіденційності оцінювачів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2932">**Data_SeenInsidersDialog -** Record of showing the Insiders privacy dialog</span></span>

  - <span data-ttu-id="1bd6a-2933">**Data_SendTelemetryOption** – настройка користувача для телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2933">**Data_SendTelemetryOption -** User setting for telemetry</span></span>

  - <span data-ttu-id="1bd6a-2934">**Data_SendTelemetryOptionPolicy** – параметр політики користувача для телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2934">**Data_SendTelemetryOptionPolicy -** User policy setting for telemetry</span></span>

  - <span data-ttu-id="1bd6a-2935">**Data_UserCategory** – тип облікового запису користувача</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2935">**Data_UserCategory -** User account type</span></span>  

  - <span data-ttu-id="1bd6a-2936">**Data_UserCCSDisabled** – перевизначення користувача для додаткових необов’язкових підключених можливостей</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2936">**Data_UserCCSDisabled -** User override for additional optional connected experiences</span></span>

   - <span data-ttu-id="1bd6a-2937">**Data_UserContentServiceGroupState** – настройка користувача для аналізу вмісту</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2937">**Data_UserContentServiceGroupState -** User setting for analyzing content</span></span>

  - <span data-ttu-id="1bd6a-2938">**Data_WillShowDialogs-**  – запис користувача, якому потрібно бачити діалогові вікна першого запуску конфіденційності</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2938">**Data_WillShowDialogs -** Record of user needing to see privacy First Run dialogs</span></span>



## <a name="product-and-service-performance-data-events"></a><span data-ttu-id="1bd6a-2939">Дані подій якості роботи продуктів і служб</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2939">Product and service performance data events</span></span>

<span data-ttu-id="1bd6a-2940">Нижче наведено підтипи даних у цій категорії:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2940">The following are the data subtypes in this category:</span></span>
- [<span data-ttu-id="1bd6a-2941">Неочікуване закриття (аварійне завершення роботи) програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2941">Unexpected application exit (crash)</span></span>](#unexpected-application-exit-crash-subtype)
- [<span data-ttu-id="1bd6a-2942">Якість виконання функцій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2942">Application feature performance </span></span>](#application-feature-performance-subtype)
- [<span data-ttu-id="1bd6a-2943">Помилки дій програми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2943">Application activity error</span></span>](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a><span data-ttu-id="1bd6a-2944">*Підтип неочікуваного закриття (аварійного завершення роботи) програми*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2944">*Unexpected application exit (crash) subtype*</span></span>

<span data-ttu-id="1bd6a-2945">Неочікуване закриття (аварійне завершення роботи) програми та стан програми на цей момент.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2945">Unexpected application exits and the state of the application when that happens.</span></span>

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a><span data-ttu-id="1bd6a-2946">Office.AppDomain.UnhandledExceptionHandlerFailed</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2946">Office.AppDomain.UnhandledExceptionHandlerFailed</span></span>

<span data-ttu-id="1bd6a-2947">Збирає відомості для будь-який необроблених винятків за допомогою програми транслятор даних.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2947">Collects information for any unhandled exceptions using the Data Streamer App.</span></span> <span data-ttu-id="1bd6a-2948">Ці дані використовуються, щоб відстежувати справність програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2948">This data is used to monitor the health of the application.</span></span> <span data-ttu-id="1bd6a-2949">Ця подія генерується службою Транслятор Даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2949">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-2950">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2950">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-2951">**Exception** – Стек викликів для винятку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2951">**Exception** - Call stack for the Exception</span></span>

- <span data-ttu-id="1bd6a-2952">**Event Name** – Назва події – це категорія події та підпис події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2952">**Event Name** - Event Name is the Event Category and Event Label.</span></span>

#### <a name="officeextensibilitycomaddinunhandledexception"></a><span data-ttu-id="1bd6a-2953">Office.Extensibility.COMAddinUnhandledException</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2953">Office.Extensibility.COMAddinUnhandledException</span></span>

<span data-ttu-id="1bd6a-2954">Подія створюється при аварійному завершенні роботи надбудови COM</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2954">Event generated when COM Add-in crashes</span></span>

<span data-ttu-id="1bd6a-2955">Класична аналітика: використовується як чисельник в обчислені стану готовності підприємства для надбудов, що дає змогу визначати ще під час пілотного проекту, чи можна оновлювати надбудову у процесі виробництва.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2955">Desktop Analytics: This is used as numerator in the computation of enterprise-specific health status for add-ins which is used to infer during pilot if the add-in is "ready to upgrade" in the production ring.</span></span>  
<span data-ttu-id="1bd6a-2956">Глобальні висновки: використовуються для обчислення глобальної готовності для надбудови (не на рівні підприємства), що потім публікується на readyforwindows.com і в інших інструментах як Readiness Toolkit</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2956">Global insights: this is used to compute a global, non-enterprise-specific "readiness" for an add-in which is then published on readyforwindows.com and other tools like the Readiness Toolkit</span></span>

<span data-ttu-id="1bd6a-2957">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2957">The following fields are collected:</span></span>

<span data-ttu-id="1bd6a-2958">**ScopeId** – поточна область потоку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2958">**ScopeId** – the current thread scope</span></span>

<span data-ttu-id="1bd6a-2959">**Method** – метод Office де стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2959">**Method** – Office method where exception occurred</span></span>

<span data-ttu-id="1bd6a-2960">**Interface** – інтерфейс Office де стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2960">**Interface** – Office interface where exception occurred</span></span>

<span data-ttu-id="1bd6a-2961">**AddinId** – ідентифікатор класу надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2961">**AddinId** – the add-in Class Id</span></span>

<span data-ttu-id="1bd6a-2962">**AddinProgId** – ідентифікатор програми надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2962">**AddinProgId** – the add-in Prog Id</span></span>

<span data-ttu-id="1bd6a-2963">**AddinFriendlyName** – зрозуміле ім’я надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2963">**AddinFriendlyName** – the add-in friendly name</span></span>

<span data-ttu-id="1bd6a-2964">**AddinTimeDateStamp** – позначка часу надбудови з метаданих DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2964">**AddinTimeDateStamp** – the add-in timestamp from the DLL metadata</span></span>

<span data-ttu-id="1bd6a-2965">**AddinVersion** – версія надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2965">**AddinVersion** – the add-in version</span></span>

<span data-ttu-id="1bd6a-2966">**AddinFileName** – ім’я файлу надбудови зі шляхом до нього</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2966">**AddinFileName** – add-in file name excluding file path</span></span>

<span data-ttu-id="1bd6a-2967">**VSTOAddIn** – чи надбудова VSTO</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2967">**VSTOAddIn** – whether add-in is VSTO</span></span>

<span data-ttu-id="1bd6a-2968">**AddinConnectFlag** – поведінка поточного завантаження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2968">**AddinConnectFlag** – current load behavior</span></span>

<span data-ttu-id="1bd6a-2969">**LoadAttempts** – кількість спроб завантаження надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2969">**LoadAttempts** – number of attempts to load add-in</span></span>

#### <a name="officeextensibilityvbatelemetrybreak"></a><span data-ttu-id="1bd6a-2970">Office.Extensibility.VbaTelemetryBreak</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2970">Office.Extensibility.VbaTelemetryBreak</span></span>

<span data-ttu-id="1bd6a-2971">Подія створюється коли у файлі з підтримкою макросів виникає помилка компіляції або часу виконання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2971">Event generated when a macro-enabled file runs into a compile or runtime error</span></span>

<span data-ttu-id="1bd6a-2972">Класична аналітика: використовується як чисельник в обчислені стану готовності підприємства для макросів (наприклад, макроси Word, Excel тощо), що дає змогу визначати ще під час пілотного проекту, чи можна оновлювати надбудову у процесі виробництва.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2972">Desktop Analytics: This is used as numerator in the computation of enterprise-specific health status for macro types (e.g. Word macros, Excel macros, etc.) which is used to infer during pilot if the add-in is "ready to upgrade" in the production ring.</span></span>

<span data-ttu-id="1bd6a-2973">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2973">The following fields are collected:</span></span>

<span data-ttu-id="1bd6a-2974">**TagId** – ідентифікатор тега телеметрії</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2974">**TagId** – the id of the telemetry tag</span></span>

<span data-ttu-id="1bd6a-2975">**BreakReason** – причина перерви (час виконання, компіляція, інші помилки)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2975">**BreakReason** – the reason for the break (runtime, compile, other error)</span></span>

<span data-ttu-id="1bd6a-2976">**SolutionType** – тип рішення (документ, шаблон, надбудова програми, надбудова COM)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2976">**SolutionType** – type of solution (document, template, app add-in, COM add-in)</span></span>

<span data-ttu-id="1bd6a-2977">**Data.ErrorCode** – код помилки повідомлений VBA</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2977">**Data.ErrorCode** – error code reported by VBA engine</span></span>

#### <a name="officeoutlookdesktophangbucketmetrics"></a><span data-ttu-id="1bd6a-2978">Office.Outlook.Desktop.HangBucketMetrics</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2978">Office.Outlook.Desktop.HangBucketMetrics</span></span>

<span data-ttu-id="1bd6a-2979">Збирає час зависання програми Outlook. Це унікальний ідентифікатор витраченого часу кожного зависання, та відомостей стеку виклику.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2979">Collects hang time for outlook hangs – a unique identifier per hang, elapsed time, and call stack information.</span></span> <span data-ttu-id="1bd6a-2980">Дані використовуються для визначення аварійних завершень роботи програми, щоб виправити їх у майбутніх версіях.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2980">The data is used to detect and identify app crashes in order to fix in future updates.</span></span>

<span data-ttu-id="1bd6a-2981">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2981">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2982">**BucketId** – гешування стеку викликів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2982">**BucketId** - hash of the call stack</span></span>

  - <span data-ttu-id="1bd6a-2983">**ElapsedTotal** – загальний час виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2983">**ElapsedTotal** - total time spent in the call</span></span>

  - <span data-ttu-id="1bd6a-2984">**ElapsedHanging** – час зависання протягом виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2984">**ElapsedHanging** - hang time spent in the call</span></span>

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a><span data-ttu-id="1bd6a-2985">Office.Outlook.Desktop.HangReportingScopePerfMetrics</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2985">Office.Outlook.Desktop.HangReportingScopePerfMetrics</span></span>

<span data-ttu-id="1bd6a-2986">Збирається час, витрачений на базові сценарії Outlook – switchfolder, switchmodule, sendmailoutbox, openitemclassic, sendmailtransport.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2986">Collects time taken for outlook core scenarios – switchfolder, switchmodule, sendmailoutbox, openitemclassic, sendmailtransport.</span></span> <span data-ttu-id="1bd6a-2987">Дані активно перевіряються на незвичайні проблем продуктивності.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2987">The data is actively monitored for anomalous performance issues.</span></span> <span data-ttu-id="1bd6a-2988">Це використовується для виявлення та діагностики проблем продуктивності, а також її підвищення з кожним оновленням.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2988">It is used to detect and diagnose performance issues as well as improve performance with each update.</span></span>

<span data-ttu-id="1bd6a-2989">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2989">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2990">**ElapsedTotal** – загальний час виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2990">**ElapsedTotal** - Total time spent in this call</span></span>

  - <span data-ttu-id="1bd6a-2991">**ScopeId** – назва функції, що містить оголошення або спеціальну назву, надану через область визначення</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2991">**ScopeId** - name of the function containing the declaration or a custom name given through scope definition</span></span>

#### <a name="officeoutlookdesktopwatsonbuckets"></a><span data-ttu-id="1bd6a-2992">Office.Outlook.Desktop.WatsonBuckets</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2992">Office.Outlook.Desktop.WatsonBuckets</span></span>

<span data-ttu-id="1bd6a-2993">Це правило збирає відомості аварійного завершення роботи з журналу подій, коли під час попереднього сеансу, програма Outlook аварійно припинила роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2993">This rule collects the crash information from the event logs when Outlook crashed in the previous session.</span></span>

<span data-ttu-id="1bd6a-2994">Дані активно перевіряються на незвичайні зависання роботи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2994">The data is actively monitored for anomalous hangs.</span></span> <span data-ttu-id="1bd6a-2995">Це використовується для визначення зависань, щоб виправити їх у майбутніх версіях.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2995">It is used to detect and identify hangs in order to fix in future updates.</span></span>

<span data-ttu-id="1bd6a-2996">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2996">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-2997">**BucketId** – гешування стеку викликів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2997">**BucketId** – hash of the call stack</span></span>

  - <span data-ttu-id="1bd6a-2998">**ElapsedTotal** – загальний час виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2998">**ElapsedTotal** - total time spent in the call</span></span>

  - <span data-ttu-id="1bd6a-2999">**ElapsedHanging** – час зависання протягом виклику</span><span class="sxs-lookup"><span data-stu-id="1bd6a-2999">**ElapsedHanging** - hang time spent in the call</span></span>

#### <a name="officepowerpointsession"></a><span data-ttu-id="1bd6a-3000">**Office.PowerPoint.Session**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3000">**Office.PowerPoint.Session**</span></span>

<span data-ttu-id="1bd6a-3001">Збір використання функцій під час кожного сеансу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3001">Collecting feature usages on each PowerPoint session.</span></span><span data-ttu-id="1bd6a-3002">Ці дані використовуються, щоб обчислити коефіцієнт неправильного завершення роботи PowerPoint під час використання функції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3002"> This data is used to calculate the ratio of PowerPoint ungraceful exit while using a feature.</span></span> <span data-ttu-id="1bd6a-3003">Коефіцієнт неправильного завершення роботи PowerPoint – це головна гарантія, що PowerPoint працює належним чином.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3003">The ratio of PowerPoint ungraceful exit is a key signal to guarantee PowerPoint is running as expected.</span></span>

<span data-ttu-id="1bd6a-3004">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3004">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3005">**Flag** – позначки сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3005">**Flag** – session flags</span></span>

  - <span data-ttu-id="1bd6a-3006">**Usage** – використання функцій</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3006">**Usage** – feature usages</span></span>

#### <a name="officepowerpointuaedialog"></a><span data-ttu-id="1bd6a-3007">Office.PowerPoint.UAE.Dialog</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3007">Office.PowerPoint.UAE.Dialog</span></span>

<span data-ttu-id="1bd6a-3008">Збирається щоразу, коли PowerPoint неправильно завершує роботу під час відкриття діалогового вікна поверх головного вікна PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3008">Collected every time when PowerPoint ungracefully exited while a dialog open on top of PowerPoint main window.</span></span> <span data-ttu-id="1bd6a-3009">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершує роботу через активне діалогове вікно, що блокує головне.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3009">This information is critical to catch PowerPoint ungracefully exits due to an active dialog blocking PowerPoint main window.</span></span> <span data-ttu-id="1bd6a-3010">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3010">Microsoft is using this data to diagnose the issue in order to guarantee PowerPoint running as expected.</span></span>

<span data-ttu-id="1bd6a-3011">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3011">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3012">**DlgCnt** – загальна кількість відкритих діалогових вікон під час аварійного завершення сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3012">**DlgCnt** – total number of open dialogs when session crashed</span></span>

  - <span data-ttu-id="1bd6a-3013">**DlgId** – відкриття ідентифікатора діалогового вікна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3013">**DlgId** – open dialog identifier</span></span>

  - <span data-ttu-id="1bd6a-3014">**IdType** – тип відкриття ідентифікатора діалогового вікна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3014">**IdType** – open dialog identifier type</span></span>

  - <span data-ttu-id="1bd6a-3015">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3015">**InitTime** – crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3016">**SessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3016">**SessionId** – crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3017">**TopId** – ідентифікатор верхнього діалогового вікна</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3017">**TopId** – top dialog identifier</span></span>

  - <span data-ttu-id="1bd6a-3018">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3018">**Version** – crashed session version</span></span>

#### <a name="officepowerpointuaedocument"></a><span data-ttu-id="1bd6a-3019">Office.PowerPoint.UAE.Document</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3019">Office.PowerPoint.UAE.Document</span></span>

<span data-ttu-id="1bd6a-3020">Збираються функції, що використовувалися у документі коли PowerPoint неправильно завершив роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3020">Collecting what feature is being used on a document when PowerPoint ungracefully exited.</span></span> <span data-ttu-id="1bd6a-3021">Ці функції включають показ слайдів, відкриття документа, збереження, редагування, співавторство, завершення роботи.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3021">These features include slide show, document open, save, edit, co-authoring, shutdown.</span></span> <span data-ttu-id="1bd6a-3022">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершує роботу під час використання функції.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3022">This information is critical to catch PowerPoint ungracefully exits while using a feature.</span></span> <span data-ttu-id="1bd6a-3023">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3023">Microsoft is using this data to diagnose the issue in order to guarantee PowerPoint running as expected.</span></span>

<span data-ttu-id="1bd6a-3024">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3024">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3025">**CoauthFlag** – позначки спільного використання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3025">**CoauthFlag** – coauth usage flags</span></span>

  - <span data-ttu-id="1bd6a-3026">**CommandFlag** – позначки змінення документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3026">**CommandFlag** – document modification flags</span></span>

  - <span data-ttu-id="1bd6a-3027">**FileIOFlag** – позначки використання файлу вводу-виводу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3027">**FileIOFlag** – file IO usage flags</span></span>

  - <span data-ttu-id="1bd6a-3028">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3028">**InitTime** - crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3029">**Location** – розташування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3029">**Location** – document location</span></span>

  - <span data-ttu-id="1bd6a-3030">**ServerDocId** – ідентифікатор документа на сервері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3030">**ServerDocId** – server document identifier</span></span>

  - <span data-ttu-id="1bd6a-3031">**SessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3031">**SessionId** - crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3032">**UrlHash** – гешування URL-адреси документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3032">**UrlHash** – document URL hash</span></span>

  - <span data-ttu-id="1bd6a-3033">**Usage** – використання функцій</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3033">**Usage** – feature usages</span></span>

  - <span data-ttu-id="1bd6a-3034">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3034">**Version** - crashed session version</span></span>

#### <a name="officepowerpointuaeopen"></a><span data-ttu-id="1bd6a-3035">Office.PowerPoint.UAE.Open</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3035">Office.PowerPoint.UAE.Open</span></span>

<span data-ttu-id="1bd6a-3036">Збирається кожен випадок, коли PowerPoint неправильно завершив роботу під час відкриття документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3036">Collecting every time when PowerPoint ungracefully exit while opening a document.</span></span> <span data-ttu-id="1bd6a-3037">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершує роботу під час відкриття документа.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3037">This information is critical to catch PowerPoint ungracefully exits while opening a document.</span></span> <span data-ttu-id="1bd6a-3038">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3038">Microsoft is using this data to diagnose the issue in order to guarantee PowerPoint running as expected.</span></span>

<span data-ttu-id="1bd6a-3039">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3039">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3040">**FileUrlLocation** – розташування URL-адреси документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3040">**FileUrlLocation** – document URL location</span></span>

  - <span data-ttu-id="1bd6a-3041">**Flag** – позначки відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3041">**Flag** – open flags</span></span>

  - <span data-ttu-id="1bd6a-3042">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3042">**InitTime** - crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3043">**Location** – розташування документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3043">**Location** - document location</span></span>

  - <span data-ttu-id="1bd6a-3044">**OpenReason** – причина відкриття</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3044">**OpenReason** – open reason</span></span>

  - <span data-ttu-id="1bd6a-3045">**ServerDocId** – ідентифікатор документа на сервері</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3045">**ServerDocId** – server document identifier</span></span>

  - <span data-ttu-id="1bd6a-3046">**SessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3046">**SessionId** - crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3047">**UrlHash** – гешування URL-адреси документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3047">**UrlHash** - document URL hash</span></span>

  - <span data-ttu-id="1bd6a-3048">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3048">**Version** - crashed session version</span></span>

#### <a name="officepowerpointuaesession"></a><span data-ttu-id="1bd6a-3049">Office.PowerPoint.UAE.Session</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3049">Office.PowerPoint.UAE.Session</span></span>

<span data-ttu-id="1bd6a-3050">Збираються функції, що використовувалися коли сеанс PowerPoint неправильно завершив роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3050">Collecting what feature have been used when PowerPoint session ungracefully exited.</span></span><span data-ttu-id="1bd6a-3051">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершив роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3051">  This information is critical to catch PowerPoint ungracefully exits.</span></span> <span data-ttu-id="1bd6a-3052">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3052">Microsoft is using this data to diagnose the issue in order to guarantee PowerPoint running as expected.</span></span>

<span data-ttu-id="1bd6a-3053">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3053">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3054">**Flag** – позначки сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3054">**Flag** – session flags</span></span>

  - <span data-ttu-id="1bd6a-3055">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3055">**InitTime** - crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3056">**PreviousSessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3056">**PreviousSessionId** - crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3057">**Usage** – використання функцій</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3057">**Usage** – feature usages</span></span>

  - <span data-ttu-id="1bd6a-3058">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3058">**Version** - crashed session version</span></span>

#### <a name="officepowerpointuaeshutdown"></a><span data-ttu-id="1bd6a-3059">Office.PowerPoint.UAE.Shutdown</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3059">Office.PowerPoint.UAE.Shutdown</span></span>

<span data-ttu-id="1bd6a-3060">Збираються дані про неправильне завершення роботи PowerPoint під час закриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3060">Collecting PowerPoint ungracefully exit while shutting down.</span></span> <span data-ttu-id="1bd6a-3061">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершує роботу під закриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3061">This information is critical to catch PowerPoint ungraceful exits while shutting down.</span></span> <span data-ttu-id="1bd6a-3062">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3062">Microsoft uses this data to diagnose the issue in order to guarantee PowerPoint runs as expected.</span></span>

<span data-ttu-id="1bd6a-3063">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3063">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3064">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3064">**InitTime** - crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3065">**SessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3065">**SessionId** - crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3066">**Stage** – етап завершення роботи</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3066">**Stage** – shutdown stage</span></span>

  - <span data-ttu-id="1bd6a-3067">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3067">**Version** - crashed session version</span></span>

#### <a name="officepowerpointuaeslideshow"></a><span data-ttu-id="1bd6a-3068">Office.PowerPoint.UAE.SlideShow</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3068">Office.PowerPoint.UAE.SlideShow</span></span>

<span data-ttu-id="1bd6a-3069">Збираються дані про неправильне завершення роботи PowerPoint під час закриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3069">Collecting PowerPoint ungracefully exit while shutting down.</span></span> <span data-ttu-id="1bd6a-3070">Ця інформація необхідна, щоб відстежити коли PowerPoint неправильно завершує роботу під закриття.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3070">This information is critical to catch PowerPoint ungraceful exits while shutting down.</span></span> <span data-ttu-id="1bd6a-3071">Microsoft використовує ці дані, щоб визначити проблему та гарантувати належну роботу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3071">Microsoft uses this data to diagnose the issue in order to guarantee PowerPoint runs as expected.</span></span>

<span data-ttu-id="1bd6a-3072">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3072">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3073">**InitTime** – ініційований час несправного сеансу </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3073">**InitTime** - crashed session initialized time</span></span>

  - <span data-ttu-id="1bd6a-3074">**Mode** – режим показу слайдів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3074">**Mode** – slide show mode</span></span>

  - <span data-ttu-id="1bd6a-3075">**SessionId** – ідентифікатор несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3075">**SessionId** - crashed session identifier</span></span>

  - <span data-ttu-id="1bd6a-3076">**State** – стан показу слайдів</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3076">**State** – slide show state</span></span>

  - <span data-ttu-id="1bd6a-3077">**Version** – версія несправного сеансу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3077">**Version** - crashed session version</span></span>

#### <a name="officeprogrammabilitytelemetryaddincrash"></a><span data-ttu-id="1bd6a-3078">Office.Programmability.Telemetry.AddInCrash</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3078">Office.Programmability.Telemetry.AddInCrash</span></span>

<span data-ttu-id="1bd6a-3079">Подія створюється при завантаження надбудови COM.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3079">Event generated when a COM Add-in is loaded.</span></span> <span data-ttu-id="1bd6a-3080">Ця інформація необхідна, щоб виявити, чи викликала надбудова аварійне завершення роботи програми Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3080">This information is critical to determine whether an add-in caused an Office application crash.</span></span> <span data-ttu-id="1bd6a-3081">Це використовується для оцінювання загальної сумісності надбудови з програмами Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3081">It is used to assess global add-in compatibility with Office applications.</span></span>

<span data-ttu-id="1bd6a-3082">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3082">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3083">**CLSID** – ідентифікатор класу надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3083">**CLSID** – the add-in Class identifier</span></span>

  - <span data-ttu-id="1bd6a-3084">**ConnectFlag** – поведінка поточної надбудови під час завантаження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3084">**ConnectFlag** – the current add-in load behavior</span></span>

  - <span data-ttu-id="1bd6a-3085">**FileName** – ім’я файлу надбудови, без шляху до нього</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3085">**FileName** – the add-in file name, excluding the file path</span></span>

  - <span data-ttu-id="1bd6a-3086">**FriendlyName** – зрозуміле ім’я надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3086">**FriendlyName** – the add-in friendly name</span></span>

  - <span data-ttu-id="1bd6a-3087">**Interface** – інтерфейс Office де стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3087">**Interface** – the Office interface where the exception occurred</span></span>

  - <span data-ttu-id="1bd6a-3088">**LoadAttempts** – кількість спроб завантаження надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3088">**LoadAttempts** – the number of attempts to load the add-in</span></span>

  - <span data-ttu-id="1bd6a-3089">**Method** – метод Office де стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3089">**Method** – the Office method where the exception occurred</span></span>

  - <span data-ttu-id="1bd6a-3090">**OfficeApplication** – програма Office де стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3090">**OfficeApplication** – the Office application where the exception occurred</span></span>

  - <span data-ttu-id="1bd6a-3091">**OfficeVersion** -версії Office</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3091">**OfficeVersion** – the versions of Office</span></span>

  - <span data-ttu-id="1bd6a-3092">**ProgID** – ідентифікатор програми надбудови</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3092">**ProgID** – the add-in Prog identifier</span></span>

#### <a name="officethisaddinstartupfailed"></a><span data-ttu-id="1bd6a-3093">Office.ThisAddIn.StartupFailed</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3093">Office.ThisAddIn.StartupFailed</span></span>

<span data-ttu-id="1bd6a-3094">Збираються відомості про виняток, що стався під час запуску програми Data Streamer.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3094">Collects information for exception that occur during startup of the Data Streamer App.</span></span> <span data-ttu-id="1bd6a-3095">Ці дані використовуються, щоб відстежувати справність програми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3095">This data is used to monitor the health of the application.</span></span> <span data-ttu-id="1bd6a-3096">Ця подія генерується службою Транслятор Даних Microsoft для надбудови Excel.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3096">This event is generated by Microsoft Data Streamer for Excel Add-in.</span></span>

<span data-ttu-id="1bd6a-3097">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3097">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-3098">**Exception** – Стек викликів для винятку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3098">**Exception** - Call stack for the Exception</span></span>

- <span data-ttu-id="1bd6a-3099">**Event Name** – Назва події – це категорія події та підпис події.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3099">**Event Name** - Event Name is the Event Category and Event Label.</span></span>


### <a name="application-feature-performance-subtype"></a><span data-ttu-id="1bd6a-3100">*Підтип виконання функцій програми*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3100">*Application feature performance subtype*</span></span>

<span data-ttu-id="1bd6a-3101">Повільна або погана робота в таких ситуаціях, як запуск програми або відкриття файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3101">Poor response time or performance for scenarios such as application start up or opening a file.</span></span>

#### <a name="officemanageabilityserviceapplypolicy"></a><span data-ttu-id="1bd6a-3102">Office.Manageability.Service.ApplyPolicy</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3102">Office.Manageability.Service.ApplyPolicy</span></span>

<span data-ttu-id="1bd6a-3103">Необхідні телеметрії для відстеження помилки \\Успіх застосування параметрів політики хмари до реєстру.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3103">Critical telemetry to track failure\\Success of applying cloud policy settings to registry.</span></span> <span data-ttu-id="1bd6a-3104">LastError вказує на знаходження та причину помилки застосування політики в реєстрі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3104">LastError tells why and where the Application of policy in registry failed.</span></span>

<span data-ttu-id="1bd6a-3105">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3105">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3106">**Data.ApplyLogMsg** - виняток msg під час застосівання політики</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3106">**Data.ApplyLogMsg** - The exception msg if any while policy was being applied</span></span>

  - <span data-ttu-id="1bd6a-3107">**Data.Cid** – динамічно створений ідентифікатор кореляції надісланий до служби, під час виклику для отримання віддаленого доступу до політики хмари.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3107">**Data.Cid** - dynamically generated correlation identifier sent to the service when the service call was made to fetch the cloud policy.</span></span> <span data-ttu-id="1bd6a-3108">Використовується для узгодження виклику, що спричинив помилку під час застосування політик у хмарі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3108">Used to correlate which call caused an issue while applying the policies on the cloud.</span></span>

  - <span data-ttu-id="1bd6a-3109">**Data.Last Error** – одне з п'яти рядкових значень (нумераторів) для запису етапу використання політики, що виконувався коли стався виняток</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3109">**Data.Last Error** - One of five string values (enumerators) to log which stage of policy application was being executed when the exception occurred</span></span>

#### <a name="officeoutlookdesktopbootperfmetrics"></a><span data-ttu-id="1bd6a-3110">Office.Outlook.Desktop.BootPerfMetrics</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3110">Office.Outlook.Desktop.BootPerfMetrics</span></span>

<span data-ttu-id="1bd6a-3111">Збирається час, витрачений на завантаження Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3111">Collects time taken to boot Outlook.</span></span> <span data-ttu-id="1bd6a-3112">Час завантаження Outlook активно відстежується для визначення та діагностики регресії.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3112">The boot time of Outlook is actively monitored to detect and diagnose regressions.</span></span> <span data-ttu-id="1bd6a-3113">Це також використовується для діагностики ескалації клієнта та підвищення продуктивності завантаження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3113">It is also used to diagnose customer escalations as well as improve boot performance over time.</span></span>

<span data-ttu-id="1bd6a-3114">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3114">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3115">**AddinElapsedTotal** – Загальний час, витрачений на завантаження надбудов</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3115">**AddinElapsedTotal** - Total time spent for loading add-ins</span></span>

  - <span data-ttu-id="1bd6a-3116">**CredPromptCount** – Кількість показаних запитів облікових даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3116">**CredPromptCount** – Number of credential prompts shown</span></span>

  - <span data-ttu-id="1bd6a-3117">**ElapsedTotal** – Загальний час завантаження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3117">**ElapsedTotal** - Total time spent for boot</span></span>

  - <span data-ttu-id="1bd6a-3118">**IsLoggingEnabled** – Чи увімкнуто журналювання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3118">**IsLoggingEnabled** - Is logging enabled</span></span>

  - <span data-ttu-id="1bd6a-3119">**ShowChooseProfileDlg** – Чи показувалося діалогове вікно «Вибір профілю»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3119">**ShowChooseProfileDlg** – Whether the Choose Profile Dialog was shown</span></span>

  - <span data-ttu-id="1bd6a-3120">**ShowFirstRunDlg** – Чи запускається Outlook вперше</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3120">**ShowFirstRunDlg** - is outlook launched for the first time</span></span>

  - <span data-ttu-id="1bd6a-3121">**ShowIMAPSrchfldWarningDlg** – Попередження про обліковий запис IMAP із ANSI PST</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3121">**ShowIMAPSrchfldWarningDlg** - Warnings in case we have an IMAP account with an ANSI PST</span></span>

  - <span data-ttu-id="1bd6a-3122">**ShowNeedSupportDlg** – Помилки завантаження викликана діалоговим вікном підтримки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3122">**ShowNeedSupportDlg** - Boot failure triggered support dialog</span></span>

  - <span data-ttu-id="1bd6a-3123">**ShowSafeModeDlg** – Чи відкрито сеанс в безпечному режимі</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3123">**ShowSafeModeDlg** - is the session opened in safe mode</span></span>

  - <span data-ttu-id="1bd6a-3124">**ShowScanPstDlg** – Store repair check відображає повідомлення про помилку</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3124">**ShowScanPstDlg** - Store repair check displayed error message</span></span>

#### <a name="officeperformanceboot"></a><span data-ttu-id="1bd6a-3125">Office.Performance.Boot</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3125">Office.Performance.Boot</span></span>

<span data-ttu-id="1bd6a-3126">Ці поля збираються після запуску програми Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3126">Collected when an Office application is booted.</span></span> <span data-ttu-id="1bd6a-3127">У них наведено відомості про спосіб завантаження (відкриття файлу чи через меню "Пуск"), обсяг пам’яті, яку використовує програма, а також про те, чи це її перше завантаження та чи відображалися користувачу будь-які елементи інтерфейсу, які блокують роботу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3127">Includes whether the boot was initiated by opening a file or launching via the Start menu, whether this was the first boot of the application, how much memory the application is using, and whether there was any blocking UI shown to the user.</span></span> <span data-ttu-id="1bd6a-3128">Ці дані дають змогу оцінити швидкість завантаження програм Office і обсяг пам’яті, яка використовується під час запуску. Це допомагає оптимізувати інтерфейс користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3128">Used to measure how fast Office applications boot and how much memory they use when they start, to ensure there is an acceptable user experience.</span></span>

<span data-ttu-id="1bd6a-3129">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3129">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3130">**ActivationKind** – визначає спосіб запуску програми (за допомогою файлу, технології OLE Automation чи через меню "Пуск").</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3130">**ActivationKind** - Whether the application was started by launching from the Start menu, by opening a file, or through OLE Automation.</span></span>

  - <span data-ttu-id="1bd6a-3131">**Firstboot** – визначає, чи програму завантажено вперше.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3131">**FirstBoot** - Whether this was a first boot of the application.</span></span>

  - <span data-ttu-id="1bd6a-3132">**InitializationDuration** – тривалість початкової ініціалізації процесу Office (у мікросекундах).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3132">**InitializationDuration** - The duration in microseconds it took to first initialize the Office process.</span></span>

  - <span data-ttu-id="1bd6a-3133">**InterruptionMessageId** – визначає, чи переривався запуск появою діалогового вікна введення даних (ідентифікатор діалогового вікна).</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3133">**InterruptionMessageId** - If the boot was interrupted by a dialog asking for user input, the ID of the dialog.</span></span>

  - <span data-ttu-id="1bd6a-3134">**TotalWorkingSetMB** – обсяг пам’яті (у мегабайтах) у робочому наборі процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3134">**TotalWorkingSetMB** - The amount of memory in megabytes in the process’s working set.</span></span>

  - <span data-ttu-id="1bd6a-3135">**VirtualSetMB** – обсяг пам’яті (у мегабайтах) у віртуальному наборі процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3135">**VirtualSetMB** - The amount of memory in megabytes in the process’s virtual set.</span></span> <span data-ttu-id="1bd6a-3136">(Лише macOS/iOS)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3136">(MacOS / iOS only)</span></span>

  - <span data-ttu-id="1bd6a-3137">**Workingsetpeakmb** – найбільший обсяг пам’яті (у мегабайтах), який коли-небудь використовувався в робочому наборі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3137">**WorkingSetPeakMB** - The largest amount of memory in megabytes that was ever in the process’s working set so far.</span></span>

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a><span data-ttu-id="1bd6a-3138">Office.UX.OfficeInsider.CanShowOfficeInsiderSlab</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3138">Office.UX.OfficeInsider.CanShowOfficeInsiderSlab</span></span>

<span data-ttu-id="1bd6a-3139">Визначає, чи можна показувати користувачу елементи програми оцінювання Office на вкладці "Обліковий запис" в інтерфейсі Office Backstage.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3139">Activity tracking whether the Office Insider slab can be shown to the user on the Account tab in the Office Backstage UI.</span></span>

<span data-ttu-id="1bd6a-3140">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3140">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3141">**Data_CanShow** – указує, чи можна показувати користувачу елементи програми оцінювання Office на вкладці "Обліковий запис" в інтерфейсі Office Backstage.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3141">**Data_CanShow** - Indicates whether the Office Insider Slab can be shown to the user on the Account tab in the Office Backstage UI.</span></span>
  
  - <span data-ttu-id="1bd6a-3142">**Data_Event** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3142">**Data_Event** - Unused</span></span>

  - <span data-ttu-id="1bd6a-3143">**Data_EventInfo** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3143">**Data_EventInfo** - Unused</span></span>

  - <span data-ttu-id="1bd6a-3144">**Data_Reason** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3144">**Data_Reason** - Unused</span></span>

#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a><span data-ttu-id="1bd6a-3145">Office.UX.OfficeInsider.ShowOfficeInsiderDlg</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3145">Office.UX.OfficeInsider.ShowOfficeInsiderDlg</span></span>

<span data-ttu-id="1bd6a-3146">Відстежує використання та продуктивність діалогового вікна програми оцінювання Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3146">Activity tracking the usage and performance of the Office Insider dialog.</span></span>

<span data-ttu-id="1bd6a-3147">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3147">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3148">**Data_AcceptedContactMeNew** – указує, чи надав користувач згоду на отримання відомостей від корпорації Майкрософт, коли подав заявку на участь у програмі оцінювання та після реєстрації вибору.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3148">**Data_AcceptedContactMeNew** - When opting into an Insider level, and when the user's choice was recorded successfully, indicates whether the user accepted to be contacted by Microsoft.</span></span>

  - <span data-ttu-id="1bd6a-3149">**Data_DialogChoice** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3149">**Data_DialogChoice** = Unused</span></span>
  
  - <span data-ttu-id="1bd6a-3150">**Data_DialogId** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3150">**Data_DialogId** = Unused</span></span>
  
  - <span data-ttu-id="1bd6a-3151">**Data_Event** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3151">**Data_Event** - Unused</span></span>
  
  - <span data-ttu-id="1bd6a-3152">**Data_EventInfo** – не використовується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3152">**Data_EventInfo** - Unused</span></span>
  
  - <span data-ttu-id="1bd6a-3153">**Data_InsiderLevel** – рівень програми оцінювання під час першого відображення діалогового вікна.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3153">**Data_InsiderLevel** - The Insider Level when the dialog is first shown to the user.</span></span>
  
  - <span data-ttu-id="1bd6a-3154">**Data_InsiderLevelNew** – новий рівень програми оцінювання, вибраний користувачем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3154">**Data_InsiderLevelNew** - The new Insider level selected by the user.</span></span>
  
  - <span data-ttu-id="1bd6a-3155">**Data_IsInternalUser** – указує, чи програма запускається під обліковими даними @microsoft.com.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3155">**Data_IsInternalUser** - Indicates whether the application runs under the credentials of an @microsoft.com account.</span></span>
  
  - <span data-ttu-id="1bd6a-3156">**Data_IsInternalUserInit** – указує на можливість коду визначати, чи програма запускається під обліковими даними @microsoft.com.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3156">**Data_IsInternalUserInit** - Indicates whether the code could determine whether the application runs under the credentials of an @microsoft.com account.</span></span>
  
  - <span data-ttu-id="1bd6a-3157">**Data_OpenNewsletterWebpage** – коли користувач підписується на розсилку новин за програмою оцінювання Office і змінює рівень програми оцінювання з Production на інший, указує, чи ініціюється в браузері перехід за посиланням на сторінку підписки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3157">**Data_OpenNewsletterWebpage** - When the Office Insider Newsletter Subscription feature is enabled, and the user switches to an Insider level from Production, indicates whether browser navigation to the Office Insider Newsletter Subscription link was triggered.</span></span>

#### <a name="officevisiosharedvisiofilerender"></a><span data-ttu-id="1bd6a-3158">Office.Visio.Shared.VisioFileRender</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3158">Office.Visio.Shared.VisioFileRender</span></span>

<span data-ttu-id="1bd6a-3159">Ця подія записує час відтворення файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3159">This event captures file render time.</span></span> <span data-ttu-id="1bd6a-3160">Це допомагає зберегти продуктивність відтворення файлу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3160">This event helps us keep file render performance in check.</span></span>

<span data-ttu-id="1bd6a-3161">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3161">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3162">**Data\_AvgTime: integer** – середній час, витрачений на відтворення програми Visio drawing за сеанс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3162">**Data\_AvgTime: integer** - Average time it took to render Visio drawing in a session</span></span>

  - <span data-ttu-id="1bd6a-3163">**Data\_CompositeSurfEnabled: bool** – значення true, коли складений режим рендерінгу активовано</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3163">**Data\_CompositeSurfEnabled: bool** - true is composite rendering mode is enabled</span></span>

  - <span data-ttu-id="1bd6a-3164">**Data\_Count: integer** – кількість разів Visio відтворює креслення за сеанс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3164">**Data\_Count: integer** - Number of time Visio renders the drawing in a session</span></span>

  - <span data-ttu-id="1bd6a-3165">**Data\_FirstRenderTime: long** – тривалість відтворення файлу під час першого запуску в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3165">**Data\_FirstRenderTime: long** - duration to render file on first launch in millisecond</span></span>

  - <span data-ttu-id="1bd6a-3166">**Data\_MaxTime: integer** – максимальний час, витрачений на відтворення програми Visio drawing за сеанс</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3166">**Data\_MaxTime: integer** - Max time it took to render Visio drawing in a session</span></span>

#### <a name="officevisiovisiofileopenreliability"></a><span data-ttu-id="1bd6a-3167">Office.Visio.VisioFileOpenReliability</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3167">Office.Visio.VisioFileOpenReliability</span></span>

<span data-ttu-id="1bd6a-3168">Ця подія збирає дані продуктивності відкриття файлу для Visio Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3168">This event collects File open perf data for Visio Dev16.</span></span> <span data-ttu-id="1bd6a-3169">Подія стежить за продуктивністю відкриття файлу і пов'язує це з його властивостями, як-от розмір файлу для Visio Dev16.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3169">This event is used to monitor performance of File open and associates it with file properties like file size for Visio Dev16.</span></span> <span data-ttu-id="1bd6a-3170">Властивості файлу допомагають швидше визначити та налагодити основні причини проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3170">File properties enable us debug and root cause issues faster.</span></span>

<span data-ttu-id="1bd6a-3171">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3171">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3172">**Data\_CorrelationId: string -** – ідентифікатор кореляції документа</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3172">**Data\_CorrelationId: string -** Document correlation identifier</span></span>

  - <span data-ttu-id="1bd6a-3173">**Data\_DocIsEnterpriseProtected: bool –** значення true, якщо документ підлягає захисту даних у Windows</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3173">**Data\_DocIsEnterpriseProtected: bool -** true if document is protected with Windows information protection</span></span>

  - <span data-ttu-id="1bd6a-3174">**Data\_DocumentId: string –** глобальний унікальний ідентифікатор шляху до файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3174">**Data\_DocumentId: string -** GUID of file path</span></span>

  - <span data-ttu-id="1bd6a-3175">**Data\_DurationToCompleteInMilliseconds: double –** тривалість збереження в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3175">**Data\_DurationToCompleteInMilliseconds: double -** Duration to complete save as in millisecond</span></span>

  - <span data-ttu-id="1bd6a-3176">**Data\_DurationToCompleteInMillisecondsSquared: double –** квадратне значення DurationToCompleteInMilliseconds</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3176">**Data\_DurationToCompleteInMillisecondsSquared: double -** squared value for DurationToCompleteInMilliseconds</span></span>

  - <span data-ttu-id="1bd6a-3177">**Data\_ErrorCode: integer –** внутрішній код помилки для відмови відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3177">**Data\_ErrorCode: integer -** Internal error code for file open failure</span></span>

  - <span data-ttu-id="1bd6a-3178">**Data\_Extension\_Docs: string –** розширення файлу відкритої схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3178">**Data\_Extension\_Docs: string -** File extension of diagram opened</span></span>

  - <span data-ttu-id="1bd6a-3179">**Data\_FileIOBytesRead: int –** загальна кількість прочитаних байтів під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3179">**Data\_FileIOBytesRead: int -** total bytes read while saving</span></span>

  - <span data-ttu-id="1bd6a-3180">**Data\_FileIOBytesReadSquared: int –** квадратне значення Data\_FileIOBytesRead</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3180">**Data\_FileIOBytesReadSquared: int -** squared value of Data\_FileIOBytesRead</span></span>

  - <span data-ttu-id="1bd6a-3181">**Data\_FileIOBytesWritten: int –** загальна кількість записаних байтів під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3181">**Data\_FileIOBytesWritten: int -** total bytes written while saving</span></span>

  - <span data-ttu-id="1bd6a-3182">**Data\_FileIOBytesWrittenSquared: int –** квадратне значення Data\_FileIOBytesWritten</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3182">**Data\_FileIOBytesWrittenSquared: int -** squared value of Data\_FileIOBytesWritten</span></span>

  - <span data-ttu-id="1bd6a-3183">**Data\_FileName: binary –** двійкове гешування назви файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3183">**Data\_FileName: binary -** Binary Hash of file name</span></span>

  - <span data-ttu-id="1bd6a-3184">**Data\_FileOpenDownloadDurationInMs: long –** тривалість завантаження файлу в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3184">**Data\_FileOpenDownloadDurationInMs: long -** duration to download file in milliseconds</span></span>

  - <span data-ttu-id="1bd6a-3185">**Data\_FileOpenEndDurationInMs: long: –** тривалість відкриття файлу в мілісекундах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3185">**Data\_FileOpenEndDurationInMs: long: -** duration to open file in millisecond</span></span>

  - <span data-ttu-id="1bd6a-3186">**Data\_FileOpenTimeStamp: time: –** позначка часу початку відкриття файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3186">**Data\_FileOpenTimeStamp: time: -** Time stamp when file started opening</span></span>

  - <span data-ttu-id="1bd6a-3187">**Data\_FilePathHash: binary –** глобальний унікальний ідентифікатор шляху до файлу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3187">**Data\_FilePathHash: binary -** GUID for file path</span></span>

  - <span data-ttu-id="1bd6a-3188">**Data\_FileSize: long –** розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3188">**Data\_FileSize: long -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-3189">**Data\_FileType: string –** розширення файлу відкритої схеми</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3189">**Data\_FileType: string -** File extension of diagram opened</span></span>

  - <span data-ttu-id="1bd6a-3190">**Data\_IsInternalFile: bool –** значення true, якщо файл є внутрішнім.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3190">**Data\_IsInternalFile: bool -** true if file is an internal file.</span></span> <span data-ttu-id="1bd6a-3191">Наприклад, Трафарет</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3191">e.g. Stencil</span></span>

  - <span data-ttu-id="1bd6a-3192">**Data\_IsIRM: bool –** значення true, якщо інформаційне право файлу захищено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3192">**Data\_IsIRM: bool -** true if file is Information Right Protected</span></span>

  - <span data-ttu-id="1bd6a-3193">**Data\_IsReadOnly: bool –** значення True, якщо файл лише для читання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3193">**Data\_IsReadOnly: bool -** true if the file is read only</span></span>

  - <span data-ttu-id="1bd6a-3194">**Data\_IsSuccess: bool –** значення true, якщо файл відкрився успішно</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3194">**Data\_IsSuccess: bool -** true when file open was successful</span></span>

  - <span data-ttu-id="1bd6a-3195">**Data\_Location: string –** розташування файлу, як-от Local, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3195">**Data\_Location: string -** location of the file like Local, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer</span></span>

  - <span data-ttu-id="1bd6a-3196">**Data\_NetworkIOBytesRead: int –** загальна кількість прочитаних байтів мережі під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3196">**Data\_NetworkIOBytesRead: int -** total network bytes read while saving</span></span>

  - <span data-ttu-id="1bd6a-3197">**Data\_NetworkIOBytesReadSquared: int –** квадратне значення Data\_NetworkIOBytesRead</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3197">**Data\_NetworkIOBytesReadSquared: int -** squared value of Data\_NetworkIOBytesRead</span></span>

  - <span data-ttu-id="1bd6a-3198">**Data\_NetworkIOBytesWritten: int –** загальна кількість записаних байтів мережі під час збереження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3198">**Data\_NetworkIOBytesWritten: int -** total network bytes written while saving</span></span>

  - <span data-ttu-id="1bd6a-3199">**Data\_NetworkIOBytesWrittenSquared: int –** квадратне значення NetworkIOBytesWritten</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3199">**Data\_NetworkIOBytesWrittenSquared: int -** squared value of NetworkIOBytesWritten</span></span>

  - <span data-ttu-id="1bd6a-3200">**Data\_OpenLocation: integer –** розташування з якого було відкрито файл 0 Local, 1, Network, 2, SharePoint, 3 – Web</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3200">**Data\_OpenLocation: integer -** Location of the file from which it was opened 0 , Local, 1, Network, 2, SharePoint, 3 – Web</span></span>

  - <span data-ttu-id="1bd6a-3201">**Data\_Size\_Docs: integer –** розмір документа в байтах</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3201">**Data\_Size\_Docs: integer -** Document size in bytes</span></span>

  - <span data-ttu-id="1bd6a-3202">**Data\_Tag: string –** унікальний ідентифікатор події «Зберегти як» </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3202">**Data\_Tag: string -** unique identifier to identify Save AS event</span></span>

  - <span data-ttu-id="1bd6a-3203">**Data\_WasSuccessful: bool –** значення true, якщо «Відкрити як» виконано успішно</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3203">**Data\_WasSuccessful: bool -** true if open as was successful</span></span>

### <a name="application-activity-error-subtype"></a><span data-ttu-id="1bd6a-3204">*Підтип помилки дій програми*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3204">*Application activity error subtype*</span></span>

<span data-ttu-id="1bd6a-3205">Помилки виконання функцій або взаємодії з користувачем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3205">Errors in functionality of a feature or user experience.</span></span>

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a><span data-ttu-id="1bd6a-3206">Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3206">Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang</span></span> 

<span data-ttu-id="1bd6a-3207">Допомагає Microsoft відокремити довгі зависання драйвера відеоадаптера від коротких, що сприяє виявленню драйверів які можуть мати проблеми.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3207">Helps Microsoft separate long video card driver hangs from short ones, which in turn helps make decisions about which video card drivers may be having problems.</span></span> <span data-ttu-id="1bd6a-3208">Драйвер відеоадаптера користувача призводить до зависання Office, проте наслідки цього ще не відомі.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3208">The user's video card driver has caused Office to hang, but the impact of the hang is not known yet</span></span>

<span data-ttu-id="1bd6a-3209">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3209">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3210">**Data\_InDeviceCall** – метод запущений на відео картці, що призвів до зависання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3210">**Data\_InDeviceCall** - The method called on the video card that produced the hang</span></span>

  - <span data-ttu-id="1bd6a-3211">**Data\_Timeout** – тривалість зависання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3211">**Data\_Timeout** - How long the hang lasted</span></span>

#### <a name="officegraphicsarcexceptions"></a><span data-ttu-id="1bd6a-3212">Office.Graphics.ARCExceptions</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3212">Office.Graphics.ARCExceptions</span></span> 

<span data-ttu-id="1bd6a-3213">Ці відомості про винятки важливі для оцінки загального стану графічного стеку і визначення частини коду, де часто відбуваються помилки, щоб встановити пріоритети дослідження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3213">This exception reporting information is important for assessing the overall health of the graphics stack, as well as identifying parts of the code where failures are occurring at high frequency, in order to prioritize investigation.</span></span> <span data-ttu-id="1bd6a-3214">Ці відомості про винятки важливі для оцінки загального стану графічного стеку і визначення частини коду, де часто відбуваються помилки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3214">This exception reporting information is important for assessing the overall health of the graphics stack, as well as identifying parts of the code where failures are occurring at high frequency.</span></span> <span data-ttu-id="1bd6a-3215">Це допомагає спеціалісту визначити, з якими проблеми відтворення стикається більшість користувачів, завдяки чому пріоритет досліджень віддається усуненню найпотрібніших проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3215">This helps an engineer to determine which rendering failures are impacting the most users, enabling us to prioritize our investigations toward fixing issues that will have the greatest user benefit.</span></span>

<span data-ttu-id="1bd6a-3216">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3216">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3217">**Data\_HResult** – код помилки повернений відмовою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3217">**Data\_HResult** - The error code returned from failure</span></span>

  - <span data-ttu-id="1bd6a-3218">**Data\_TagCount** – кількість виникнення кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3218">**Data\_TagCount** - The count of each failure that occurred</span></span>

  - <span data-ttu-id="1bd6a-3219">**Data\_TagID** – ідентифікатор помилки, що відбулася</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3219">**Data\_TagID** - The identifier of the failure that occurred</span></span>

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a><span data-ttu-id="1bd6a-3220">Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3220">Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error</span></span>

<span data-ttu-id="1bd6a-3221">Збираються відомості виникнення помилки під час переходу до спільного Календаря Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3221">Collects information when any failure occurs when while Navigation to shared Calendar.</span></span> <span data-ttu-id="1bd6a-3222">Ці дані використовуються, щоб відстежувати стан API спільного календаря та його взаємодії з Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3222">This data is used to monitor the health of the calendar sharing API as well as Outlooks interaction with shared calendars.</span></span>

<span data-ttu-id="1bd6a-3223">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3223">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3224">**FailedCaseHResult** – код помилки повернений відмовою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3224">**FailedCaseHResult** - The error code returned from Failure</span></span>

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a><span data-ttu-id="1bd6a-3225">Office.Outlook.Desktop.EDP.EDPOpenStoreFailure</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3225">Office.Outlook.Desktop.EDP.EDPOpenStoreFailure</span></span>

<span data-ttu-id="1bd6a-3226">Успіх або помилка відкриття поштового сховища з захищеними корпоративними даними, що базуються на результаті виклику до API для Windows, для отримання ключа дешифрування сховища.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3226">Success or failure to open the Enterprise Data Protection protected mail store based on result of Windows API call to get the key to decrypt the store.</span></span> <span data-ttu-id="1bd6a-3227">Це використовується для діагностики однієї з найважливіших проблем захисту корпоративних даних, що може зашкодити завантаженню Outlook.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3227">We use this diagnose one of the top Enterprise Data Protection issues which can prevent Outlook from booting.</span></span> <span data-ttu-id="1bd6a-3228">Основна причина помилки - це взаємодія Outlook з Windows API, що використовується для дешифрування ключа сховища.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3228">Primary cause of failure is Outlooks interaction with Windows APIs used to decrypt the store key.</span></span>

<span data-ttu-id="1bd6a-3229">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3229">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3230">**Робота HVA** **-** з користувацькими даними</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3230">**HVA Activity** **-** with custom data fields</span></span>

  - <span data-ttu-id="1bd6a-3231">**IsFlightOn** – вказує, чи активовано EDPDecryption Flight</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3231">**IsFlightOn** – Indicates whether the EDPDecryption Flight is enabled</span></span>

#### <a name="officeoutlookdesktopndbcorruptionresult"></a><span data-ttu-id="1bd6a-3232">Office.Outlook.Desktop.NdbCorruptionResult</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3232">Office.Outlook.Desktop.NdbCorruptionResult</span></span>

<span data-ttu-id="1bd6a-3233">Office.Outlook.Desktop.NdbCorruptionResult та Office.Outlook.Desktop.NDBCorruptStore.Warning, збираються під час виявлення пошкодження у PST або OST користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3233">Office.Outlook.Desktop.NdbCorruptionResult and Office.Outlook.Desktop.NDBCorruptStore.Warning are collected when we detect corruption in a user’s PST/OST.</span></span> <span data-ttu-id="1bd6a-3234">Коли пошкодження виявлено, Microsoft збирає формат бази даних, місце виявлення та трохи відомостей про пошкодження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3234">When we detect corruption, Microsoft collects the format of the database, the place where detected it, and a small amount of context about the corruption.</span></span> <span data-ttu-id="1bd6a-3235">Пошкодження OST/PST не дає користувачам відкривати електронну пошту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3235">OST/PST corruption prevents users from accessing their emails.</span></span> <span data-ttu-id="1bd6a-3236">Незвичайна активність у цих даних активно відстежується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3236">We actively monitor this data for anomalous activity.</span></span> <span data-ttu-id="1bd6a-3237">Щоб обмежити втрату даних клієнтів, проводиться діагностика та дослідження проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3237">We aim to investigate and diagnose issues to limit loss of customer data.</span></span>

<span data-ttu-id="1bd6a-3238">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3238">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3239">**0 –** назва процесу, що повідомляє про пошкодження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3239">**0 -** The Process name which reported corruption</span></span>

  - <span data-ttu-id="1bd6a-3240">**1 –** Bool, що визначає чи вибирає користувач новий файл</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3240">**1 -** Bool indicating if the user chooses new file or not</span></span>

  - <span data-ttu-id="1bd6a-3241">**2 –** кількість інших процесів з відкриттям бази даних</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3241">**2 -** the number of other processes which have the database open</span></span>

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a><span data-ttu-id="1bd6a-3242">Office.Outlook.Desktop.NDBCorruptStore.Warning</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3242">Office.Outlook.Desktop.NDBCorruptStore.Warning</span></span>

<span data-ttu-id="1bd6a-3243">Office.Outlook.Desktop.NdbCorruptionResult та Office.Outlook.Desktop.NDBCorruptStore.Warning, збираються під час виявлення пошкодження у PST або OST користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3243">Office.Outlook.Desktop.NdbCorruptionResult and Office.Outlook.Desktop.NDBCorruptStore.Warning are collected when we detect corruption in a user’s PST/OST.</span></span> <span data-ttu-id="1bd6a-3244">Коли пошкодження виявлено, Microsoft збирає формат бази даних, місце виявлення та трохи відомостей про пошкодження.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3244">When we detect corruption, Microsoft collects the format of the database, the place where detected it, and a small amount of context about the corruption.</span></span> <span data-ttu-id="1bd6a-3245">Пошкодження OST/PST не дає користувачам відкривати електронну пошту.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3245">OST/PST corruption prevents users from accessing their emails.</span></span> <span data-ttu-id="1bd6a-3246">Незвичайна активність у цих даних активно відстежується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3246">We actively monitor this data for anomalous activity.</span></span> <span data-ttu-id="1bd6a-3247">Щоб обмежити втрату даних клієнтів, проводиться діагностика та дослідження проблем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3247">We aim to investigate and diagnose issues to limit loss of customer data.</span></span>

<span data-ttu-id="1bd6a-3248">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3248">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3249">**CollectionTime** – час збору</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3249">**CollectionTime** - collection time</span></span>

  - <span data-ttu-id="1bd6a-3250">**Context** – Corrupt Store Context, де виявлено пошкодження</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3250">**Context** - Corrupt Store Context, where corruption was detected</span></span>

  - <span data-ttu-id="1bd6a-3251">**CreatedWithVersion** – (необов'язково) поле з версією сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3251">**CreatedWithVersion** – (Optional) field with version of store</span></span>

  - <span data-ttu-id="1bd6a-3252">**Details** – відомості про аварійне завершення роботи</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3252">**Details** – Details about the crash</span></span>

  - <span data-ttu-id="1bd6a-3253">**NdbType** – тип сховища, може бути 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3253">**NdbType** - Store Type, can be 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis</span></span>

  - <span data-ttu-id="1bd6a-3254">**ProcessName** – назва процесу, що викликає пошкодження сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3254">**ProcessName** - Process Name causing the store to get corrupted</span></span>

  - <span data-ttu-id="1bd6a-3255">**PstVersion** – версія MSPST32.DLL</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3255">**PstVersion** - Version of the MSPST32.DLL</span></span>

  - <span data-ttu-id="1bd6a-3256">**Version** – версія формату файлу сховища</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3256">**Version** - Version of store file format</span></span>

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a><span data-ttu-id="1bd6a-3257">Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3257">Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16</span></span>

<span data-ttu-id="1bd6a-3258">Збирається успіх та помилки команд «Переслати», «Переслати як вкладення», «Переслати як iCalendar» для одиничної, повторюваної та виняткової відповіді на нараду в поданні «Пошта», «Календар» й «Інспектор читання Outlook».</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3258">Collects success and failure of the Forward, Forward as Attachment, and Forward as iCalendar action for Single, Recurring, and Exceptional Meeting Responses in the Mail, Calendar, and Inspector Outlook view.</span></span> <span data-ttu-id="1bd6a-3259">Аномалії у частоті помилок команд «Переслати», «Переслати як вкладення», «Переслати як iCalendar» активно відстежуються.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3259">The failure rate of the Forward, Forward as Attachment, and Forward as iCalendar actions are actively monitored for anomalies.</span></span> <span data-ttu-id="1bd6a-3260">Аномальна статистика позначає, що Outlook не може провести основні операції календаря.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3260">Anomalous statistics indicate a failure Outlooks ability to conduct core calendar operations.</span></span> <span data-ttu-id="1bd6a-3261">Ці дані також використовуються, щоб діагностувати інші пов'язані з цим проблеми календаря Outlook, які можуть бути виявлені.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3261">This data is also used to diagnose other Calendar related issues that may be detected.</span></span>

<span data-ttu-id="1bd6a-3262">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3262">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3263">**CountExceptionForward – кількість пересланих винятків наради**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3263">**CountExceptionForward- Count of the forwarded Meetings Exceptions**</span></span>

  - <span data-ttu-id="1bd6a-3264">**CountExceptionForwardAsiCa – кількість винятків наради пересланих як iCal**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3264">**CountExceptionForwardAsiCal- Count of the forwarded Meetings Exceptions as an iCal**</span></span>

  - <span data-ttu-id="1bd6a-3265">**CountExceptionForwardInSplit – кількість винятків наради пересланих з меню стрічки**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3265">**CountExceptionForwardInSplit- Count of the forwarded Meetings Exceptions from the Split Menu in Ribbon**</span></span>

  - <span data-ttu-id="1bd6a-3266">**CountExceptionForwardWithAttach – кількість винятків наради пересланих як посилання**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3266">**CountExceptionForwardWithAttach- Count of the forwarded Meetings Exceptions as an Attachment**</span></span>

  - <span data-ttu-id="1bd6a-3267">**CountRecurringForward – кількість пересланих повторюваних нарад**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3267">**CountRecurringForward- Count of the forwarded Recurring Meetings**</span></span>

  - <span data-ttu-id="1bd6a-3268">**CountRecurringForwardAsiCal – кількість повторюваних нарад пересланих як iCal**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3268">**CountRecurringForwardAsiCal- Count of the forwarded Recurring Meetings as an iCal**</span></span>

  - <span data-ttu-id="1bd6a-3269">**CountRecurringForwardInSplit**– кількість повторюваних нарад пересланих з меню стрічки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3269">**CountRecurringForwardInSplit**- Count of the forwarded Recurring Meetings from the Split Menu in Ribbon</span></span>

  - <span data-ttu-id="1bd6a-3270">**CountRecurringForwardWithAttach – кількість повторюваних нарад пересланих як посилання**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3270">**CountRecurringForwardWithAttach- Count of the forwarded Recurring Meetings as an Attachment**</span></span>

  - <span data-ttu-id="1bd6a-3271">**CountSingleForward – кількість пересланих одиничних нарад**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3271">**CountSingleForward- Count of the forwarded Single Meetings**</span></span>

  - <span data-ttu-id="1bd6a-3272">**CountSingleForwardAsiCal – кількість одиничних нарад пересланих як iCal**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3272">**CountSingleForwardAsiCal- Count of the forwarded Single Meetings as an iCal**</span></span>

  - <span data-ttu-id="1bd6a-3273">**CountSingleForwardInSplit– кількість одиничних нарад пересланих з меню стрічки**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3273">**CountSingleForwardInSplit- Count of the forwarded Single Meetings from the Split Menu in Ribbon**</span></span>

  - <span data-ttu-id="1bd6a-3274">**CountSingleForwardWithAttach – кількість одиничних нарад пересланих як посилання**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3274">**CountSingleForwardWithAttach- Count of the forwarded Single Meetings as an Attachment**</span></span>

  - <span data-ttu-id="1bd6a-3275">**HResult – код помилки**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3275">**HResult- ErrorCode**</span></span>

  - <span data-ttu-id="1bd6a-3276">**OlkViewName – Вказує на подання «Пошта», «Календар» або «Інспектор читання»**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3276">**OlkViewName -- Indicates Mail, Calendar, or Inspector View**</span></span>

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a><span data-ttu-id="1bd6a-3277">Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3277">Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16</span></span>

<span data-ttu-id="1bd6a-3278">Збирається успіх та помилки команд «Відповісти», «Відповісти всім», «Відповісти в миттєвому повідомленні» та «Відповісти всім в миттєвому повідомленні» для одиничної, повторюваної та виняткової відповіді на нараду в поданні «Пошта», «Календар» й «Інспектор читання Outlook».</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3278">Collects success and failure of the Reply, Reply All, Reply With IM, and Reply All with IM action for Single, Recurring, and Exception Meeting Responses in the Mail, Calendar, and Inspector Outlook view.</span></span> <span data-ttu-id="1bd6a-3279">Аномалії у частоті помилок команд «Відповісти», «Відповісти всім», «Відповісти в миттєвому повідомленні» та «Відповісти всім в миттєвому повідомленні» активно відстежуються.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3279">The failure rate of the Reply, Reply All, Reply With IM, and Reply All with IM actions are actively monitored for anomalies.</span></span> <span data-ttu-id="1bd6a-3280">Аномальна статистика позначає, що Outlook не може провести основні операції календаря.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3280">Anomalous statistics indicate a failure Outlooks ability to conduct core calendar operations.</span></span> <span data-ttu-id="1bd6a-3281">Ці дані також використовуються, щоб діагностувати інші пов'язані з цим проблеми календаря Outlook, які можуть бути виявлені.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3281">This data is also used to diagnose other Calendar related issues that may be detected.</span></span>

<span data-ttu-id="1bd6a-3282">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3282">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3283">**CountExceptionReply – кількість винятків команди «Відповісти» у нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3283">**CountExceptionReply - Count of the Meetings Reply on exceptions**</span></span>

  - <span data-ttu-id="1bd6a-3284">**CountExceptionReplyAl – кількість винятків команди «Відповісти всім» у нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3284">**CountExceptionReplyAll - Count of the Meetings ReplyAll on exceptions**</span></span>

  - <span data-ttu-id="1bd6a-3285">**CountExceptionReplyAllWithIM – кількість винятків команди «Відповісти всім в миттєвому повідомленні» у нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3285">**CountExceptionReplyAllWithIM- Count of the Meetings ReplyAll with IM on exceptions**</span></span>

  - <span data-ttu-id="1bd6a-3286">**CountExceptionReplyWithIM – кількість винятків команди «Відповісти в миттєвому повідомленні» у нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3286">**CountExceptionReplyWithIM- Count of the Meetings Reply with IM on exceptions**</span></span>

  - <span data-ttu-id="1bd6a-3287">**CountRecurringReply – кількість команд «Відповісти» у повторюваних нарадах**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3287">**CountRecurringReply - Count of the Recurring Meetings Reply**</span></span>

  - <span data-ttu-id="1bd6a-3288">**CountRecurringReplyAll – кількість команд «Відповісти всім» у повторюваних нарадах**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3288">**CountRecurringReplyAll- Count of the Recurring Meetings ReplyAll**</span></span>

  - <span data-ttu-id="1bd6a-3289">**CountRecurringReplyAllWithIM – кількість команд «Відповісти всім в миттєвому повідомленні» у повторюваних нарадах**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3289">**CountRecurringReplyAllWithIM- Count of the Recurring Meetings ReplyAll with IM**</span></span>

  - <span data-ttu-id="1bd6a-3290">**CountRecurringReplyWithIM – кількість команд «Відповісти в миттєвому повідомленні» у повторюваних нарадах**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3290">**CountRecurringReplyWithIM- Count of the Recurring Meetings Reply with IM**</span></span>

  - <span data-ttu-id="1bd6a-3291">**CountSingleReply– кількість «Відповісти» в одиничній нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3291">**CountSingleReply- Count of the Single Meetings Reply**</span></span>

  - <span data-ttu-id="1bd6a-3292">**CountSingleReplyAll– кількість «Відповісти всім» в одиничній нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3292">**CountSingleReplyAll- Count of the Single Meetings ReplyAll**</span></span>

  - <span data-ttu-id="1bd6a-3293">**CountSingleReplyAllWithIM– кількість «Відповісти всім в миттєвому повідомленні» в одиничній нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3293">**CountSingleReplyAllWithIM- Count of the Single Meetings ReplyAll with IM**</span></span>

  - <span data-ttu-id="1bd6a-3294">**CountSingleReplyAllWithIM– кількість «Відповісти в миттєвому повідомленні» в одиничній нараді**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3294">**CountSingleReplyWithIM- Count of the Single Meetings Reply with IM**</span></span>

  - <span data-ttu-id="1bd6a-3295">**HResult – код помилки**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3295">**HResult- ErrorCode**</span></span>

  - <span data-ttu-id="1bd6a-3296">**OlkViewName – Вказує на подання «Пошта», «Календар» або «Інспектор читання»**</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3296">**OlkViewName- Indicates Mail, Calendar, or Inspector View**</span></span>

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a><span data-ttu-id="1bd6a-3297">Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3297">Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail</span></span>

<span data-ttu-id="1bd6a-3298">Це правило збирає помилки спільного доступу до Календаря Outlook під час додавання нового користувача (типу EX або SMTP) з адресної книги.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3298">This rule collects Calendar Sharing errors when adding a new user (of type EX or SMTP) from the Address book.</span></span> <span data-ttu-id="1bd6a-3299">Ці дані використовуються, щоб діагностувати та вирішити проблеми, виявлені у діалоговому вікні «Спільний доступ до Календаря Outlook»</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3299">This data is used to diagnose and resolve issues detected in the Calendar Sharing dialog</span></span>

<span data-ttu-id="1bd6a-3300">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3300">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3301">**CountAccountWizardEnd** – кількість разів діалогове вікно «Legacy wizard» завершувало роботу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3301">**CountAccountWizardEnd** - How many times the legacy wizard dialog ended</span></span>

  - <span data-ttu-id="1bd6a-3302">**CountCreatePIMAccount** – кількість разів коли користувач створював профіль PIM</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3302">**CountCreatePIMAccount** - How many times user created a PIM Profile</span></span>

#### <a name="officesystemsystemhealthasserts"></a><span data-ttu-id="1bd6a-3303">Office.System.SystemHealthAsserts</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3303">Office.System.SystemHealthAsserts</span></span>

<span data-ttu-id="1bd6a-3304">Ця подія визначає помилки, що допомагають зрозуміти, коли якість програмного забезпечення погіршується.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3304">The errors this event identifies help us understand when the customer experience is degrading.</span></span> <span data-ttu-id="1bd6a-3305">Багато ShipAsserts призвели до аварійного завершення роботи, і ця інформація дає змогу виправити їх велику кількість.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3305">Many of these ShipAsserts lead to crashes and this information makes it possible to fix many of those.</span></span> <span data-ttu-id="1bd6a-3306">Збирає ShipAsserts продукту, що допомагає визначити помилки.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3306">Collects ShipAsserts from the product which helps to identify errors.</span></span>

<span data-ttu-id="1bd6a-3307">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3307">The following fields are collected:</span></span>

<span data-ttu-id="1bd6a-3308">Count – кількість копій кожної повідомленої перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3308">Count – The count of each assert reported</span></span>

  - <span data-ttu-id="1bd6a-3309">**EndTime** – час виникнення останньої повідомленої перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3309">**EndTime** – Time at which the last assert reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3310">**ErrorGroup** – ідентифікатор сегментування кожної перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3310">**ErrorGroup** – A bucketing identifier for each assert</span></span>

  - <span data-ttu-id="1bd6a-3311">**FirstTimeStamp** – перше виникнення перевірки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3311">**FirstTimeStamp** – The first time at which the assert occurred</span></span>

  - <span data-ttu-id="1bd6a-3312">**Trackback** – унікальний ідентифікатор визначених перевірок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3312">**Trackback** – A unique identifier for a specific assert</span></span>

#### <a name="officesystemsystemhealtherrorsetwshim"></a><span data-ttu-id="1bd6a-3313">Office.System.SystemHealthErrorsEtwShim</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3313">Office.System.SystemHealthErrorsEtwShim</span></span>

<span data-ttu-id="1bd6a-3314">Використовується для визначення проблем, що виникають під час роботи програми, які проявляються як аварійне завершення або порушено функціонування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3314">Used to identify customer impacting issues within the running app that may manifest as crashes or degraded functionality.</span></span> <span data-ttu-id="1bd6a-3315">Записує помилки, які виникають під час виконання процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3315">Records errors that occur during process run time.</span></span>

<span data-ttu-id="1bd6a-3316">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3316">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3317">**EndTime** – час виникнення останньої повідомленої помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3317">**EndTime** – The time at which the last error reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3318">**Trackback** – унікальний ідентифікатор визначених помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3318">**Trackback** – A unique identifier for a specific error</span></span>

  - <span data-ttu-id="1bd6a-3319">**ErrorGroup** – ідентифікатор сегментування кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3319">**ErrorGroup** – A bucketing identifier for each error</span></span>

  - <span data-ttu-id="1bd6a-3320">**Count**– кількість копій кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3320">**Count** – The count of each error</span></span>

  - <span data-ttu-id="1bd6a-3321">**FirstTimeStamp** – перше виникнення помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3321">**FirstTimeStamp** – The first time at which the error occurred</span></span>

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a><span data-ttu-id="1bd6a-3322">Office.System.SystemHealthErrorsUlsAndAsserts</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3322">Office.System.SystemHealthErrorsUlsAndAsserts</span></span>

<span data-ttu-id="1bd6a-3323">Використовується для визначення проблем, що виникають під час роботи програми, які проявляються як аварійне завершення або порушено функціонування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3323">Used to identify customer impacting issues within the running app that may manifest as crashes or degraded functionality.</span></span> <span data-ttu-id="1bd6a-3324">Записує помилки, які виникають під час виконання процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3324">Records errors that occur during process run time.</span></span>

<span data-ttu-id="1bd6a-3325">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3325">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3326">**EndTime** – час виникнення останньої повідомленої помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3326">**EndTime** – The time at which the last error reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3327">**Trackback** – унікальний ідентифікатор визначених помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3327">**Trackback** – A unique identifier for a specific error</span></span>

  - <span data-ttu-id="1bd6a-3328">**ErrorGroup** – ідентифікатор сегментування кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3328">**ErrorGroup** – A bucketing identifier for each error</span></span>

  - <span data-ttu-id="1bd6a-3329">**Count**– кількість копій кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3329">**Count** – The count of each error</span></span>

  - <span data-ttu-id="1bd6a-3330">**FirstTimeStamp** – перше виникнення помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3330">**FirstTimeStamp** – The first time at which the error occurred</span></span>

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a><span data-ttu-id="1bd6a-3331">Office.System.SystemHealthErrorsUlsWorkaround</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3331">Office.System.SystemHealthErrorsUlsWorkaround</span></span>

<span data-ttu-id="1bd6a-3332">Використовується для визначення проблем, що виникають під час роботи програми, які проявляються як аварійне завершення або порушено функціонування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3332">Used to identify customer impacting issues within the running app that may manifest as crashes or degraded functionality.</span></span> <span data-ttu-id="1bd6a-3333">Записує помилки, які виникають під час виконання процесу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3333">Records errors that occur during process runtime</span></span>

<span data-ttu-id="1bd6a-3334">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3334">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3335">**EndTime** – час виникнення останньої повідомленої помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3335">**EndTime** – The time at which the last error reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3336">**Trackback** – унікальний ідентифікатор визначених помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3336">**Trackback** – A unique identifier for a specific error</span></span>

  - <span data-ttu-id="1bd6a-3337">**ErrorGroup** – ідентифікатор сегментування кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3337">**ErrorGroup** – A bucketing identifier for each error</span></span>

  - <span data-ttu-id="1bd6a-3338">**Count**– кількість копій кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3338">**Count** – The count of each error</span></span>

#### <a name="officesystemsystemhealtherrorswithouttag"></a><span data-ttu-id="1bd6a-3339">Office.System.SystemHealthErrorsWithoutTag</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3339">Office.System.SystemHealthErrorsWithoutTag</span></span>

<span data-ttu-id="1bd6a-3340">Використовується для визначення проблем, що виникають під час роботи програми, які проявляються як аварійне завершення або порушено функціонування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3340">Used to identify customer impacting issues within the running app that may manifest as crashes or degraded functionality.</span></span> <span data-ttu-id="1bd6a-3341">Записує помилки, які виникають під час виконання процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3341">Records errors that occur during process runtime.</span></span>

<span data-ttu-id="1bd6a-3342">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3342">The following fields are collected:</span></span>

<span data-ttu-id="1bd6a-3343">Count – кількість копій кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3343">Count - The count of each error</span></span>

  - <span data-ttu-id="1bd6a-3344">**EndTime** – час виникнення останньої повідомленої помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3344">**EndTime** - The time at which the last error reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3345">**ErrorCode** – ідентифікатор для помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3345">**ErrorCode** – An identifier for the error</span></span>

  - <span data-ttu-id="1bd6a-3346">**ErrorGroup** – ідентифікатор сегментування кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3346">**ErrorGroup** - A bucketing identifier for each error</span></span>

  - <span data-ttu-id="1bd6a-3347">**ErrorId** – ідентифікатор для помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3347">**ErrorId** – An identifier for the error</span></span>

  - <span data-ttu-id="1bd6a-3348">**FirstTimeStamp** – перше виникнення помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3348">**FirstTimeStamp** - The first time at which the error occurred</span></span>

  - <span data-ttu-id="1bd6a-3349">**Trackback** – унікальний ідентифікатор визначених помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3349">**Trackback** - A unique identifier for a specific error</span></span>

#### <a name="officesystemsystemhealtherrorswithtag"></a><span data-ttu-id="1bd6a-3350">Office.System.SystemHealthErrorsWithTag</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3350">Office.System.SystemHealthErrorsWithTag</span></span>

<span data-ttu-id="1bd6a-3351">Використовується для визначення проблем, що виникають під час роботи програми, які проявляються як аварійне завершення або порушено функціонування.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3351">Used to identify customer impacting issues within the running app that may manifest as crashes or degraded functionality.</span></span> <span data-ttu-id="1bd6a-3352">Записує помилки, які виникають під час виконання процесу.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3352">Records errors that occur during process runtime.</span></span>

<span data-ttu-id="1bd6a-3353">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3353">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3354">**Count** – кількість копій кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3354">**Count** - The count of each error</span></span>

  - <span data-ttu-id="1bd6a-3355">**EndTime** – час виникнення останньої повідомленої помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3355">**EndTime** - The time at which the last error reported occurred</span></span>

  - <span data-ttu-id="1bd6a-3356">**ErrorCode** – ідентифікатор для помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3356">**ErrorCode** – An identifier for the error</span></span>

  - <span data-ttu-id="1bd6a-3357">**ErrorGroup** – ідентифікатор сегментування кожної помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3357">**ErrorGroup** - A bucketing identifier for each error</span></span>

  - <span data-ttu-id="1bd6a-3358">**ErrorId** – ідентифікатор для помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3358">**ErrorId** – An identifier for the error</span></span>

  - <span data-ttu-id="1bd6a-3359">**FirstTimeStamp** – перше виникнення помилки</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3359">**FirstTimeStamp** - The first time at which the error occurred</span></span>

  - <span data-ttu-id="1bd6a-3360">**Trackback** – унікальний ідентифікатор визначених помилок</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3360">**Trackback** - A unique identifier for a specific error</span></span>

## <a name="device-connectivity-and-configuration-data-events"></a><span data-ttu-id="1bd6a-3361">Дані подій підключення та конфігурації пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3361">Device connectivity and configuration data events</span></span>

<span data-ttu-id="1bd6a-3362">Нижче наведено підтипи даних у цій категорії:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3362">The following are the data subtypes in this category:</span></span>

- [<span data-ttu-id="1bd6a-3363">Підключення та конфігурація пристрою</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3363">Device connectivity and configuration</span></span>](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a><span data-ttu-id="1bd6a-3364">*Підтип підключення та конфігурації пристрою*</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3364">*Device connectivity and configuration subtype*</span></span>

<span data-ttu-id="1bd6a-3365">Стан підключення до мережі та параметри пристрою, наприклад пам'ять.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3365">Network connection state and device settings, such as memory.</span></span>

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a><span data-ttu-id="1bd6a-3366">Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3366">Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated</span></span>

<span data-ttu-id="1bd6a-3367">Користувач оновив драйвер відеоадаптера, що викликав аварійне завершення роботи Office, тому він більше не використовується для відображення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3367">User has updated a video card driver that was previously causing Office crashes and thus no longer being used to render.</span></span> <span data-ttu-id="1bd6a-3368">Це повідомляє Microsoft що користувачі з не повністю оптимальним станом відтворення, повернулися до рекомендованого стану.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3368">Informs Microsoft that users who were once in a sub-optimal rendering state are once again in the recommended rendering state.</span></span>

<span data-ttu-id="1bd6a-3369">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3369">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3370">**Data\_BlockedDriverVersion** – версія заблокованого драйвера.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3370">**Data\_BlockedDriverVersion** - Version of the driver that was blocklisted.</span></span>

  - <span data-ttu-id="1bd6a-3371">**Data\_DeviceId** – ідентифікатор заблокованого відеоадаптера пристрою.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3371">**Data\_DeviceId** -identifier of the video card device that was blocklisted.</span></span>

  - <span data-ttu-id="1bd6a-3372">**Data\_UpdatedDriverVersion** – версія оновленого драйвера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3372">**Data\_UpdatedDriverVersion** - Version of the updated driver</span></span>

#### <a name="officeairspaceairspacelocalblocklistinfo"></a><span data-ttu-id="1bd6a-3373">Office.AirSpace.AirSpaceLocalBlocklistInfo</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3373">Office.AirSpace.AirSpaceLocalBlocklistInfo</span></span>

<span data-ttu-id="1bd6a-3374">Відомості про драйвер відеоадаптера користувача, що призвів до кількох останніх аварійних завершень роботи програм Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3374">Details on the user's video card driver that has caused multiple recent crashes of Office applications.</span></span> <span data-ttu-id="1bd6a-3375">Office не використовуватиме цей відеоадаптер під час сеансу (використовуватиметься програмний рендерінг), доки драйвер не оновиться.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3375">Office will not use this video card in this Office session (using software rendering instead) until the driver is updated.</span></span> <span data-ttu-id="1bd6a-3376">Це інформує Microsoft про драйвери відеоадаптера, через які виникають проблеми в Office, що дозволяє визначити тенденції та проаналізувати вплив на користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3376">Informs Microsoft of video card drivers that are causing problems in Office so trends can be identified and the user of impact of such drivers can be analyzed.</span></span> <span data-ttu-id="1bd6a-3377">Корпорація Microsoft повідомляється про кількість користувачів в не повністю оптимальному стані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3377">Tell Microsoft how many users are in this sub-optimal state.</span></span>

<span data-ttu-id="1bd6a-3378">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3378">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3379">**Data\_AllAppsBlocked** – чи всі програми Office заблоковані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3379">**Data\_AllAppsBlocked** - Whether all Office apps are blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3380">**Data\_BlockedDeviceId** – ідентифікатор заблокованого відеоадаптера пристрою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3380">**Data\_BlockedDeviceId** - identifier of the video card device that was blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3381">**Data\_BlockedDriverVersion** – версія заблокованого драйвера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3381">**Data\_BlockedDriverVersion** - Version of the driver that was blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3382">**Data\_CrashHistory** – рядок з історією аварійних завершень роботи драйвера відеоадаптера для аналізу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3382">**Data\_CrashHistory** - A string that represents the history of video card driver caused crashes for analysis</span></span>

  - <span data-ttu-id="1bd6a-3383">**Data\_SecsBetweenCrashes** – частота виникнення аварійних завершень роботи драйвера відеоадаптера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3383">**Data\_SecsBetweenCrashes** - How frequently driver card crashes are occurring</span></span>

#### <a name="officeairspaceairspacewincompisenabled"></a><span data-ttu-id="1bd6a-3384">Office.AirSpace.AirSpaceWinCompIsEnabled</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3384">Office.AirSpace.AirSpaceWinCompIsEnabled</span></span>

<span data-ttu-id="1bd6a-3385">Чи використовується найновіша платформа низькорівневого відтворення Office на основі складу Windows Composition.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3385">Whether the latest Office low-level rendering platform based on Windows Composition is being used.</span></span>

<span data-ttu-id="1bd6a-3386">Створення та випуск найновішої платформи низькорівневого відтворення Office дозволяє Microsoft побачити кількість користувачів кожної версії та переконатися, що платформи залишається вільною від помилок.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3386">As the latest Office low-level rendering platform is developed and begins to be released to customers, this allows Microsoft to see how many users are on each version to ensure the platform remains bug-free.</span></span>

<span data-ttu-id="1bd6a-3387">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3387">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3388">**Data\_WinCompEnabled** – чи використовується внутрішній сервер на основі Windows Composition</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3388">**Data\_WinCompEnabled** -Whether the Windows Composition-based backend is in use</span></span>

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a><span data-ttu-id="1bd6a-3389">Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3389">Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp</span></span>

<span data-ttu-id="1bd6a-3390">Виявляється відеоадаптер користувача, що спричиняє критичне зависання.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3390">User’s video card has been detected as causing long or unrecoverable hangs.</span></span> <span data-ttu-id="1bd6a-3391">Office не використовуватиме цей відеоадаптер під час сеансу (використовуватиметься програмний рендерінг), доки драйвер не оновиться.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3391">Office will not use this video card in this Office session (using software rendering instead) until the driver is updated.</span></span> <span data-ttu-id="1bd6a-3392">Це інформує Microsoft про драйвери відеоадаптера, через які виникають проблеми в Office, що дозволяє визначити тенденції та проаналізувати вплив на користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3392">Informs Microsoft of video card drivers that are causing problems in Office so trends can be identified and the user of impact of such drivers can be analyzed.</span></span> <span data-ttu-id="1bd6a-3393">А також допомагає проінформувати про кількість користувачів в не повністю оптимальному стані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3393">Also helps in informing how many users are in this sub-optimal state.</span></span>

<span data-ttu-id="1bd6a-3394">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3394">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3395">**Data\_AppName** – програма, що спричинила зависання драйвера відеоадаптера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3395">**Data\_AppName** - Which app has encountered video card driver hangs</span></span>

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a><span data-ttu-id="1bd6a-3396">Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3396">Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite</span></span>

<span data-ttu-id="1bd6a-3397">Office визначає, що драйвер відеоадаптера користувача призвів до зависання, яке має бути проаналізовано під наступного запуску програми Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3397">Office has identified that the user's video card driver has caused a hang that should be analyzed at the next Office application boot.</span></span> <span data-ttu-id="1bd6a-3398">Це використовується, щоб визначити, чи покращить інший драйвер або адаптер взаємодію з користувачем.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3398">Used to determine whether using a different video card driver or adapter would offer a better user experience.</span></span> <span data-ttu-id="1bd6a-3399">Коли схема повторюється, Microsoft може вносити зміни до інтерфейсу, щоб зберегти якомога комфортнішу взаємодію з Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3399">As patterns occur, Microsoft may make adjustments to keep the Office experience as smooth as possible.</span></span>

<span data-ttu-id="1bd6a-3400">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3400">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3401">**Data\_HangDetected** – чи виявлено зависання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3401">**Data\_HangDetected** - Whether a hang was detected</span></span>

  - <span data-ttu-id="1bd6a-3402">**Data\_InDeviceCall** – який відеоадаптер відтворював виклик Office, коли сталося зависання</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3402">**Data\_InDeviceCall** - Which video card rendering call Office was in when the hang occurred</span></span>

  - <span data-ttu-id="1bd6a-3403">**Data\_Timeout** – тривалість зависання, якщо його виправлено</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3403">**Data\_Timeout** - How long the hang lasted, if it recovered</span></span>

  - <span data-ttu-id="1bd6a-3404">**Data\_UnrecoverableCommand** – чи виправляється зависання відтворення відеоадаптера звичайним способом.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3404">**Data\_UnrecoverableCommand** - Whether the hang in this video card rendering command is typically recoverable.</span></span>

#### <a name="officeairspacebackendwin32localblocklistactivity"></a><span data-ttu-id="1bd6a-3405">Office.AirSpace.Backend.Win32.LocalBlocklistActivity</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3405">Office.AirSpace.Backend.Win32.LocalBlocklistActivity</span></span>

<span data-ttu-id="1bd6a-3406">Відомості про драйвер відеоадаптера користувача, що призвів до кількох останніх аварійних завершень роботи програм Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3406">Details on the user's video card driver that has caused multiple recent crashes of Office applications.</span></span> <span data-ttu-id="1bd6a-3407">Office не використовуватиме цей відеоадаптер під час сеансу (використовуватиметься програмний рендерінг), доки драйвер не оновиться.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3407">Office will not use this video card in this Office session (using software rendering instead) until the driver is updated.</span></span> <span data-ttu-id="1bd6a-3408">Це інформує Microsoft про драйвери відеоадаптера, через які виникають проблеми в Office, що дозволяє визначити тенденції та проаналізувати вплив на користувача.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3408">Informs Microsoft of video card drivers that are causing problems in Office so trends can be identified and the user of impact of such drivers can be analyzed.</span></span> <span data-ttu-id="1bd6a-3409">Корпорація Microsoft повідомляється про кількість користувачів в не повністю оптимальному стані.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3409">Tell Microsoft how many users are in this sub-optimal state.</span></span>

<span data-ttu-id="1bd6a-3410">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3410">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3411">**Data.AllAppsBlocked** – чи всі програми Office заблоковані</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3411">**Data.AllAppsBlocked** - Whether all Office apps are blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3412">**Data.BlockedDeviceId** – ідентифікатор заблокованого відеоадаптера пристрою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3412">**Data.BlockedDeviceId** - identifier of the video card device that was blocked</span></span>

  - <span data-ttu-id="1bd6a-3413">**Data.BlockedDriverVersion** – версія заблокованого драйвера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3413">**Data.BlockedDriverVersion** - Version of the driver that was blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3414">**Data.CrashHistory System.String** – рядок з історією аварійних завершень роботи драйвера відеоадаптера для аналізу</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3414">**Data.CrashHistory System.String** - A string that represents the history of video card driver caused crashes for analysis</span></span>

  - <span data-ttu-id="1bd6a-3415">**Data.SecsBetweenCrashes** – частота виникнення аварійних завершень роботи драйвера відеоадаптера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3415">**Data.SecsBetweenCrashes** - How frequently driver card crashes are occurring</span></span>

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a><span data-ttu-id="1bd6a-3416">Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3416">Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity</span></span>

<span data-ttu-id="1bd6a-3417">Користувач оновив драйвер відеоадаптера, що викликав аварійне завершення роботи Office, тому він більше не використовується для відображення.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3417">User has updated a video card driver that was previously causing Office crashes and thus no longer being used to render.</span></span> <span data-ttu-id="1bd6a-3418">Це повідомляє Microsoft що користувачі з не повністю оптимальним станом відтворення, повернулися до рекомендованого стану.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3418">Informs Microsoft that users who were once in a sub-optimal rendering state are once again in the recommended rendering state.</span></span>

<span data-ttu-id="1bd6a-3419">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3419">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3420">**Data\_BlockedDeviceId** – ідентифікатор заблокованого відеоадаптера пристрою </span><span class="sxs-lookup"><span data-stu-id="1bd6a-3420">**Data\_BlockedDeviceId** - identifier of the video card device that was blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3421">**Data\_BlockedDriverVersion** – версія заблокованого драйвера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3421">**Data\_BlockedDriverVersion** - Version of the driver that was blocklisted</span></span>

  - <span data-ttu-id="1bd6a-3422">**Data\_UpdatedDriverVersion** – версія оновленого драйвера</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3422">**Data\_UpdatedDriverVersion** - Version of the updated driver</span></span>

#### <a name="officegraphicsspritememcorrupt"></a><span data-ttu-id="1bd6a-3423">Office.Graphics.SpriteMemCorrupt</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3423">Office.Graphics.SpriteMemCorrupt</span></span>

<span data-ttu-id="1bd6a-3424">Повідомляє про виявлені помилки, в телеметрії обліку пам'яті графічних об'єктів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3424">Reports any errors detected in the sprite memory accounting telemetry.</span></span> <span data-ttu-id="1bd6a-3425">Необхідно для оцінки справності телеметрії використання пам'яті графічних об'єктів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3425">Critical for assessing health of the graphics memory usage telemetry.</span></span> <span data-ttu-id="1bd6a-3426">Ці відомості потрібні для перевірити правильності телеметрії пам'яті графічних об'єктів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3426">This information is needed to validate the correctness of our SpriteMem telemetry.</span></span>

<span data-ttu-id="1bd6a-3427">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3427">The following fields are collected:</span></span>

  - <span data-ttu-id="1bd6a-3428">**Data\_CurrentSpriteMem** – загальний обсяг пам'яті, виділений на утримання графічних об'єктів (зображень), що стають вмістом екрана.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3428">**Data\_CurrentSpriteMem** - Total amount of memory that is actively allocated to hold sprites (images) that result in screen content.</span></span>

  - <span data-ttu-id="1bd6a-3429">**Data\_Function** – назва функції, які намагається звільнити пам'ять графічних об'єктів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3429">**Data\_Function** - The name of the function that is attempting to release sprite memory.</span></span>

  - <span data-ttu-id="1bd6a-3430">**Data\_SpriteMemToRemove** – обсяг пам'яті видаленої з розподілу графічних об'єктів.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3430">**Data\_SpriteMemToRemove** - Amount of memory to be removed from sprite allocation.</span></span>

#### <a name="officepowerpointpptsharednointernetconnectivity"></a><span data-ttu-id="1bd6a-3431">Office.PowerPoint.PPT.Shared.NoInternetConnectivity</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3431">Office.PowerPoint.PPT.Shared.NoInternetConnectivity</span></span>

<span data-ttu-id="1bd6a-3432">Збирається щоразу, коли PowerPoint виявляє відсутність підключення до Інтернету.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3432">Collected whenever PowerPoint detects there is no internet connectivity.</span></span> <span data-ttu-id="1bd6a-3433">Корпорація Microsoft використовує ці дані для отримання діагностичних відомостей про підключення користувача до Інтернету, щоб зрозуміти вплив цього на підключення до служб Office.</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3433">Microsoft uses this data to get diagnostic information about the user's internet connection to be able to understand how that impacts connectivity to Office services.</span></span>

<span data-ttu-id="1bd6a-3434">Збираються такі поля:</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3434">The following fields are collected:</span></span>

- <span data-ttu-id="1bd6a-3435">**Data\_IsNexusDetected:bool** - показує чи отриманий стан підключення до Інтернету, під час виклику служби Nexus (значення true) або під час виклику універсального API веб-сервісу (значення false)</span><span class="sxs-lookup"><span data-stu-id="1bd6a-3435">**Data\_IsNexusDetected:bool** - shows whether we got the Internet connectivity status when calling Nexus service (value true) or when calling generic web service API call (value false)</span></span>
