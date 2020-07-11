---
title: Параметри політики для налаштування елементів керування конфіденційністю в Office на пристроях з Android
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Ця стаття пропонує адміністраторам Office інформацію про налаштування параметрів конфіденційності в Office на пристроях з Android.
hideEdit: true
ms.openlocfilehash: 6086ecd1b2cd55bbf6cb4577879714f1d20a2f93
ms.sourcegitcommit: 81295dff0f2fa474f0db39fd40560e3a23fff32a
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/09/2020
ms.locfileid: "45092139"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a>Параметри політики для налаштування елементів керування конфіденційністю в Office на пристроях з Android

Office на пристроях з Android включає параметри політики, що дають змогу налаштувати:

- збір і надсилання до корпорації Майкрософт ***діагностичних даних*** про клієнтське програмне забезпечення Office;

- доступність додаткових хмарних ***підключених можливостей*** Office.

Докладні відомості про діагностичні дані та підключені можливості див. в статті [Огляд елементів керування конфіденційністю](overview-privacy-controls.md).

Ці параметри політики застосовуються до таких програм:
- Word для Android, Excel для Android і PowerPoint для Android версії 16.0.12228.20260 і новіших;
- Outlook для Android версії 4.1.71 і новіших;
- OneNote для Android версії 16.0.12228.20004 і новіших;
- OneDrive для Android версії 5.47 і новіших;
- Програма Office для Android версії 16.0.12430.20254 і новіших.

## <a name="policy-settings-available-for-office-on-android-devices"></a>Параметри політики, доступні для Office на пристроях з Android

У таблиці нижче наведено параметри політики, доступні для Office на пристроях з Android, і посилання на додаткові відомості про кожен параметр політики.

> [!NOTE]
>- Додаткові відомості стосуються параметрів політики для Office на пристроях під керуванням Windows. Ці відомості також стосуються параметрів політики для Office на пристроях з Android, оскільки вони співпадають.
>- Параметр політики *Дозволити використання в Office підключених можливостей*, доступний для Office на пристроях під керуванням Windows, не стосується Office на пристроях з Android. 


|Назва параметра політики  |Додаткові відомості |
|---------|---------|
|Налаштування рівня діагностичних даних клієнтського програмного забезпечення, які Office надсилає корпорації Майкрософт|[Параметр політики для діагностичних даних](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|Дозволити використання в Office підключених можливостей, які аналізують вміст| [Параметр політики для підключених можливостей, які аналізують вміст](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|Дозволити використання в Office підключених можливостей, які завантажують вміст з Інтернету |[Параметр політики для підключених можливостей, які завантажують вміст з Інтернету](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|Дозволити використання в Office додаткових необов’язкових підключених можливостей |[Параметр політики для необов'язкових підключених можливостей](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a>Застосування параметрів політики за допомогою служби хмарної політики Office

Щоб застосувати будь-який із цих чотирьох параметрів політики для Office на пристроях з Android, потрібно скористатися службою хмарної політики Office. Докладні відомості про використання служби хмарної політики Office див. в статті [Огляд служби хмарної політики Office](../overview-office-cloud-policy-service.md).

> [!NOTE]
> Якщо ви раніше використовували службу хмарної політики Office, щоб налаштувати ці параметри політики для Office на пристроях під керуванням Windows, тепер ви можете застосувати ті самі параметри до Office на пристроях з Android. Для цього вам потрібно лише ввійти в службу хмарної політики Office, яка автоматично застосує їх до Office на пристроях з Android.
