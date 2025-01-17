---
author: jasonsandlin
title: "PFSegmentsPlayerLinkedAccount"
description: "PFSegmentsPlayerLinkedAccount data model."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFSegmentsPlayerLinkedAccount  

PFSegmentsPlayerLinkedAccount data model.  

## Syntax  
  
```cpp
typedef struct PFSegmentsPlayerLinkedAccount {  
    const char* email;  
    PFLoginIdentityProvider const* platform;  
    const char* platformUserId;  
    const char* username;  
} PFSegmentsPlayerLinkedAccount;  
```
  
### Members  
  
**`email`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Linked account's email.
  
**`platform`** &nbsp; [PFLoginIdentityProvider](../../pftypes/enums/pfloginidentityprovider.md) const*  
*may be nullptr*  
  
(Optional) Authentication platform.
  
**`platformUserId`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Platform user identifier.
  
**`username`** &nbsp; const char*  
*is null-terminated*  
  
(Optional) Linked account's username.
  
  
## Requirements  
  
**Header:** PFSegmentsTypes.h
  
## See also  
[PFSegmentsTypes members](../pfsegmentstypes_members.md)  

  
  
