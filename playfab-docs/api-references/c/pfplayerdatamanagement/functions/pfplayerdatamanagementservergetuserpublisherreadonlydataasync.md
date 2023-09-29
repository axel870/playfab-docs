---
author: jasonsandlin
title: "PFPlayerDataManagementServerGetUserPublisherReadOnlyDataAsync"
description: "Retrieves the publisher-specific custom data for the user which can only be read by the client"
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 09/25/2023
---

# PFPlayerDataManagementServerGetUserPublisherReadOnlyDataAsync  

Retrieves the publisher-specific custom data for the user which can only be read by the client  

## Syntax  
  
```cpp
HRESULT PFPlayerDataManagementServerGetUserPublisherReadOnlyDataAsync(  
    PFEntityHandle titleEntityHandle,  
    const PFPlayerDataManagementGetUserDataRequest* request,  
    XAsyncBlock* async  
)  
```  
  
### Parameters  
  
**`titleEntityHandle`** &nbsp; PFEntityHandle  
  
PFEntityHandle for a title Entity obtained using PFAuthenticationGetEntityWithSecretKeyAsync.  
  
**`request`** &nbsp; [PFPlayerDataManagementGetUserDataRequest*](../../pfplayerdatamanagementtypes/structs/pfplayerdatamanagementgetuserdatarequest.md)  
  
Populated request object.  
  
**`async`** &nbsp; XAsyncBlock*  
*_Inout_*  
  
XAsyncBlock for the async operation.  
  
  
### Return value
Type: HRESULT
  
Result code for this API operation.
  
## Remarks  
  
This API is available on Win32. Data is stored as JSON key-value pairs. If the Keys parameter is provided, the data object returned will only contain the data specific to the indicated Keys. Otherwise, the full set of custom user data will be returned. See also ServerGetUserPublisherDataAsync, ServerGetUserPublisherInternalDataAsync, ServerUpdateUserPublisherDataAsync, ServerUpdateUserPublisherInternalDataAsync, ServerUpdateUserPublisherReadOnlyDataAsync. When the asynchronous task is complete, call [PFPlayerDataManagementServerGetUserPublisherReadOnlyDataGetResultSize](pfplayerdatamanagementservergetuserpublisherreadonlydatagetresultsize.md) and [PFPlayerDataManagementServerGetUserPublisherReadOnlyDataGetResult](pfplayerdatamanagementservergetuserpublisherreadonlydatagetresult.md) to get the result.
  
## Requirements  
  
**Header:** PFPlayerDataManagement.h
  
## See also  
[PFPlayerDataManagement members](../pfplayerdatamanagement_members.md)  

  
  