---
title: Configure Application Gateway in front of static website
description: Learn how to manage traffic to a static website using an Azure Application Gateway.
author: rbaker
ms.service: storage
ms.subservice: blobs
ms.topic: how-to
ms.author: normesta
ms.date: 12/07/2020
---

# Configure Application Gateway in front of static website

You can deploy a [static website](storage-blob-static-website.md) behind an [Azure Application Gateway](../../web-application-firewall/ag/ag-overview.md) to manage traffic.  You can use Azure Application Gateway to configure routing rules, manage TLS/SSL Certificates and apply a [Web Application Firewall](../../application-gateway/overview.md). Configuring Azure Application Gateway results in additional charges, but provides more control over traffic to you static website.

For information on Azure Application Gateway pricing, see [Application Gateway pricing](https://azure.microsoft.com/pricing/details/application-gateway/).

## Configure Azure Application Gateway



