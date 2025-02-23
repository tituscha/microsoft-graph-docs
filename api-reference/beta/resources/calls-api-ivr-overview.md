---
title: "IVR scenarios in calls"
description: "The following are the Interactive Voice Response (IVR) scenarios that the calling APIs in Microsoft Graph support:"
author: "VinodRavichandran"
localization_priority: Normal
ms.prod: "cloud-communications"
doc_type: conceptualPageType
---

# IVR scenarios in calls

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

The following are the Interactive Voice Response (IVR) scenarios that the calling APIs in Microsoft Graph support:

- Playing an audio prompt - e.g., when a call is placed in a customer service agent's queue..
- Recording a response - e.g., to record the caller's audio, usually after they heard a prompt with options.
- Subscribing to tones - e.g., when you want to know what DTMF tones the caller selected, usually after hearing the audio prompt.
- Cancel Media Processing - e.g., when you want to cancel any PlayPrompt or RecordResponse operations that might be in process.
