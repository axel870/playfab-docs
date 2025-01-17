---
author: jasonsandlin
title: "PFPushNotificationRegistrationModel"
description: "PFPushNotificationRegistrationModel data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFPushNotificationRegistrationModel  

PFPushNotificationRegistrationModel data model.  

## Syntax  
  
```cpp
typedef struct PFPushNotificationRegistrationModel {  
    const char* notificationEndpointARN;  
    PFPushNotificationPlatform const* platform;  
} PFPushNotificationRegistrationModel;  
```
  
### Members  
  
**`notificationEndpointARN`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Notification configured endpoint.
  
**`platform`** &nbsp; [PFPushNotificationPlatform](../enums/pfpushnotificationplatform.md) const*  
*may be nullptr*  
  
(Optional) Push notification platform.
  
  
## Requirements  
  
**Header:** PFTypes.h
  
## See also  
[PFTypes members](../pftypes_members.md)  

  
  
