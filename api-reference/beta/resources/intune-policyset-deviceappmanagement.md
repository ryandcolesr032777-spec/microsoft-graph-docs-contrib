---
title: "deviceAppManagement resource type"
description: "Singleton entity that acts as a container for all device and app management functionality."
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: resourcePageType
ms.date: 08/01/2024
---

# deviceAppManagement resource type

Namespace: microsoft.graph

> **Important:** Microsoft supports Intune /beta APIs, but they are subject to more frequent change. Microsoft recommends using version v1.0 when possible. Check an API's availability in version v1.0 using the Version selector.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Singleton entity that acts as a container for all device and app management functionality.

## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[Get deviceAppManagement](../api/intune-policyset-deviceappmanagement-get.md)|[deviceAppManagement](../resources/intune-policyset-deviceappmanagement.md)|Read properties and relationships of the [deviceAppManagement](../resources/intune-policyset-deviceappmanagement.md) object.|
|[Update deviceAppManagement](../api/intune-policyset-deviceappmanagement-update.md)|[deviceAppManagement](../resources/intune-policyset-deviceappmanagement.md)|Update the properties of a [deviceAppManagement](../resources/intune-policyset-deviceappmanagement.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|policySets|[policySet](../resources/intune-policyset-policyset.md) collection|The PolicySet of Policies and Applications|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceAppManagement"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceAppManagement",
  "id": "String (identifier)"
}
```