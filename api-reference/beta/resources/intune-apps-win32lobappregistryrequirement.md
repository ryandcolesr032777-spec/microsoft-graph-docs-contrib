---
title: "win32LobAppRegistryRequirement resource type"
description: "Contains registry properties to detect a Win32 App"
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: resourcePageType
ms.date: 08/01/2024
---

# win32LobAppRegistryRequirement resource type

Namespace: microsoft.graph

> **Important:** Microsoft supports Intune /beta APIs, but they are subject to more frequent change. Microsoft recommends using version v1.0 when possible. Check an API's availability in version v1.0 using the Version selector.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Contains registry properties to detect a Win32 App


Inherits from [win32LobAppRequirement](../resources/intune-apps-win32lobapprequirement.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|operator|[win32LobAppDetectionOperator](../resources/intune-apps-win32lobappdetectionoperator.md)|The operator for detection Inherited from [win32LobAppRequirement](../resources/intune-apps-win32lobapprequirement.md). Possible values are: `notConfigured`, `equal`, `notEqual`, `greaterThan`, `greaterThanOrEqual`, `lessThan`, `lessThanOrEqual`.|
|detectionValue|String|The detection value Inherited from [win32LobAppRequirement](../resources/intune-apps-win32lobapprequirement.md)|
|check32BitOn64System|Boolean|A value indicating whether this registry path is for checking 32-bit app on 64-bit system|
|keyPath|String|The registry key path to detect Win32 Line of Business (LoB) app|
|valueName|String|The registry value name|
|detectionType|[win32LobAppRegistryDetectionType](../resources/intune-apps-win32lobappregistrydetectiontype.md)|The registry data detection type. Possible values are: `notConfigured`, `exists`, `doesNotExist`, `string`, `integer`, `version`.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.win32LobAppRegistryRequirement"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.win32LobAppRegistryRequirement",
  "operator": "String",
  "detectionValue": "String",
  "check32BitOn64System": true,
  "keyPath": "String",
  "valueName": "String",
  "detectionType": "String"
}
```