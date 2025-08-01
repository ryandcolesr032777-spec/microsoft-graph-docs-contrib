---
title: "macOSKernelExtension resource type"
description: "Represents a specific macOS kernel extension. A macOS kernel extension can be described by its team identifier plus its bundle identifier."
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: resourcePageType
ms.date: 08/01/2024
---

# macOSKernelExtension resource type

Namespace: microsoft.graph

> **Important:** Microsoft supports Intune /beta APIs, but they are subject to more frequent change. Microsoft recommends using version v1.0 when possible. Check an API's availability in version v1.0 using the Version selector.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Represents a specific macOS kernel extension. A macOS kernel extension can be described by its team identifier plus its bundle identifier.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|teamIdentifier|String|The team identifier that was used to sign the kernel extension.|
|bundleId|String|Bundle ID of the kernel extension.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.macOSKernelExtension"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSKernelExtension",
  "teamIdentifier": "String",
  "bundleId": "String"
}
```