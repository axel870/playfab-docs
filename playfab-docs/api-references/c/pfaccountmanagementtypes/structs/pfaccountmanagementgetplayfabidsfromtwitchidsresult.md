---
author: jasonsandlin
title: "PFAccountManagementGetPlayFabIDsFromTwitchIDsResult"
description: "PFAccountManagementGetPlayFabIDsFromTwitchIDsResult data model. For Twitch identifiers which have not been linked to PlayFab accounts, null will be returned."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 06/26/2023
---

# PFAccountManagementGetPlayFabIDsFromTwitchIDsResult  

PFAccountManagementGetPlayFabIDsFromTwitchIDsResult data model. For Twitch identifiers which have not been linked to PlayFab accounts, null will be returned.  

## Syntax  
  
```cpp
typedef struct PFAccountManagementGetPlayFabIDsFromTwitchIDsResult {  
    PFAccountManagementTwitchPlayFabIdPair const* data;  
    uint32_t dataCount;  
} PFAccountManagementGetPlayFabIDsFromTwitchIDsResult;  
```
  
### Members  
  
**`data`** &nbsp; [PFAccountManagementTwitchPlayFabIdPair](pfaccountmanagementtwitchplayfabidpair.md) const*  
*may be nullptr*  
  
(Optional) Mapping of Twitch identifiers to PlayFab identifiers.
  
**`dataCount`** &nbsp; uint32_t  
  
Count of data
  
  
## Requirements  
  
**Header:** PFAccountManagementTypes.h
  
## See also  
[PFAccountManagementTypes members](../pfaccountmanagementtypes_members.md)  

  
  
