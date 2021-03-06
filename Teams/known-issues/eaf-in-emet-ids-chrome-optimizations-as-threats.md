---
title: Chromium sandbox optimizations incorrectly identified as threats by EAF policy in the Enhanced Mitigation Experience Toolkit (EMET)
ms.author: v-todmc
author: todmccoy
ms.date: 4/8/2020
audience: ITPro
ms.topic: article
manager: dcscontentpm
ms.service: msteams
localization_priority: Normal
search.appverid:
- SPO160
- MET150
appliesto:
- Microsoft Teams
ms.custom: 
- CI 113425
- CSSTroubleshoot 
ms.reviewer: scapero
description: Describes a workaround for an issue where the EAF policy in EMET identifies Chromium optimizations as threats.
---

# EAF policy in the EMET identifies Chromium sandbox optimizations as threats

## Symptoms

An issue has been identified with Chromium sandbox in which the Export Address Table Access Filtering (EAF) policy in the Enhanced Mitigation Experience Toolkit (EMET) and in Windows Defender Advanced Threat Protection (ATP) incorrectly identifies Chromium sandbox optimizations as threats. This issue causes Teams to work incorrectly.

## Workaround

To work around this issue, turn off EAF for Teams. More about this issue can be found in the [EMET mitigations guidelines](https://support.microsoft.com/help/2909257/emet-mitigations-guidelines). 

## More information
For more information about Windows Defender ATP and EAF policy, see [Enable exploit protection](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/enable-exploit-protection).

Still need help? Go to [Microsoft Community](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fanswers.microsoft.com%2F&data=02%7C01%7Cv-todmc%40microsoft.com%7C98910814456c474880f108d7cf62d97d%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637205895885805857&sdata=9%2FYStDGvrU5ZIYXB7guowmaPlKazab0U%2BTpiBIItDaQ%3D&reserved=0).