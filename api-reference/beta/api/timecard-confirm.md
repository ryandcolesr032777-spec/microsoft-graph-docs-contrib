---
title: "timeCard: confirm"
description: "Confirm a specific timeCard."
author: "akumar39"
ms.localizationpriority: medium
ms.subservice: "teams"
doc_type: apiPageType
ms.date: 04/04/2024
---

# timeCard: confirm

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Confirm a specific [timeCard](../resources/timecard.md).

[!INCLUDE [national-cloud-support](../../includes/global-only.md)]

## Permissions

Choose the permission or permissions marked as least privileged for this API. Use a higher privileged permission or permissions [only if your app requires it](/graph/permissions-overview#best-practices-for-using-microsoft-graph-permissions). For details about delegated and application permissions, see [Permission types](/graph/permissions-overview#permission-types). To learn more about these permissions, see the [permissions reference](/graph/permissions-reference).

<!-- { "blockType": "permissions", "name": "timecard_confirm" } -->
[!INCLUDE [permissions-table](../includes/permissions/timecard-confirm-permissions.md)]

> [!CAUTION]
> The support for application permissions in this API is deprecated and will end on January 1, 2026. To confirm a **timeCard** with application permissions, use [timeCard: confirmForUser](/graph/api/timecard-confirmforuser?view=graph-rest-beta&preserve-view=true) instead.

## HTTP request

<!-- { "blockType": "ignored" } -->

```http
POST /teams/{teamId}/schedule/timeCards/{timeCardId}/confirm
```

## Request headers

| Header       | Value |
|:---------------|:--------|
|Authorization|Bearer {token}. Required. Learn more about [authentication and authorization](/graph/auth/auth-concepts).|
| MS-APP-ACTS-AS (deprecated) | A user ID (GUID). Required only if the authorization token is an application token; otherwise, optional. Until January 1, 2026, this API supports application permissions only when used in combination with the deprecated `MS-APP-ACTS-AS` header.|

## Request body
Don't supply a request body for this method.

## Response

If successful, this method returns a `204 No Content` response code.

## Example

### Request
The following example shows a request.


# [HTTP](#tab/http)
<!-- {
  "blockType": "request",
  "name": "timecard-confirm",
  "sampleKeys": ["fd15cad8-80f6-484f-9666-3caf695fbf32", "TCK_cc09588d-d9d2-4fa0-85dc-2aa5ef983972"]
}-->

```http
POST https://graph.microsoft.com/beta/teams/fd15cad8-80f6-484f-9666-3caf695fbf32/schedule/timeCards/TCK_cc09588d-d9d2-4fa0-85dc-2aa5ef983972/confirm
```

# [C#](#tab/csharp)
[!INCLUDE [sample-code](../includes/snippets/csharp/timecard-confirm-csharp-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [CLI](#tab/cli)
[!INCLUDE [sample-code](../includes/snippets/cli/timecard-confirm-cli-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [Go](#tab/go)
[!INCLUDE [sample-code](../includes/snippets/go/timecard-confirm-go-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [Java](#tab/java)
[!INCLUDE [sample-code](../includes/snippets/java/timecard-confirm-java-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [JavaScript](#tab/javascript)
[!INCLUDE [sample-code](../includes/snippets/javascript/timecard-confirm-javascript-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [PHP](#tab/php)
[!INCLUDE [sample-code](../includes/snippets/php/timecard-confirm-php-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [PowerShell](#tab/powershell)
[!INCLUDE [sample-code](../includes/snippets/powershell/timecard-confirm-powershell-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

# [Python](#tab/python)
[!INCLUDE [sample-code](../includes/snippets/python/timecard-confirm-python-snippets.md)]
[!INCLUDE [sdk-documentation](../includes/snippets/snippets-sdk-documentation-link.md)]

---

### Response

The following example shows the response.

<!-- {
  "blockType": "response",
  "truncated": true
} -->

```http
HTTP/1.1 204 No Content
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "Confirm timecard",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
  ]
}
-->
