---
author: jasonsandlin
title: "PFGroupsGroupBlock"
description: "PFGroupsGroupBlock data model. Describes an entity that is blocked from joining a group."
ms.author: jasonsa
ms.topic: reference
ms.service: playfab
ms.date: 05/24/2023
---

# PFGroupsGroupBlock  

PFGroupsGroupBlock data model. Describes an entity that is blocked from joining a group.  

## Syntax  
  
```cpp
typedef struct PFGroupsGroupBlock {  
    PFGroupsEntityWithLineage const* entity;  
    PFEntityKey const* group;  
} PFGroupsGroupBlock;  
```
  
### Members  
  
**`entity`** &nbsp; [PFGroupsEntityWithLineage](pfgroupsentitywithlineage.md) const*  
*may be nullptr*  
  
(Optional) The entity that is blocked.
  
**`group`** &nbsp; [PFEntityKey](../../pftypes/structs/pfentitykey-c.md) const*  
  
ID of the group that the entity is blocked from.
  
  
## Requirements  
  
**Header:** PFGroupsTypes.h
  
## See also  
[PFGroupsTypes members](../pfgroupstypes_members.md)  

  
  
