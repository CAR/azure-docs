---
title: Sample API management policy - Add capabilities to backend service
titleSuffix: Azure API Management
description: Azure API management policy sample - Demonstrates how to add capabilities to a backend service. For example, accept a name of the place instead of latitude and longitude in a weather forecast API.
services: api-management
documentationcenter: ''
author: dlepow
manager: cfowler
editor: ''

ms.service: api-management
ms.workload: mobile
ms.tgt_pltfrm: na
ms.topic: article
ms.date: 10/13/2017
ms.author: danlep
---

# Add capabilities to a backend service

This article shows an Azure API management policy sample that demonstrates how to add capabilities to a backend service. For example, accept a name of the place instead of latitude and longitude in a weather forecast API. To set or edit a policy code, follow the steps described in [Set or edit a policy](../set-edit-policies.md). To see other examples, see [policy samples](../policy-reference.md).

## Policy

Paste the code into the **inbound** block.

[!code-xml[Main](../../../api-management-policy-samples/examples/Call out to an HTTP endpoint and cache the response.policy.xml)]

## Next steps

Learn more about APIM policies:

+ [Transformation policies](../api-management-transformation-policies.md)
+ [Policy samples](../policy-reference.md)