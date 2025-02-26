---
title: Improve performance of Azure apps with Advisor
description: Use performance recommendations in Azure Advisor to improve the speed and responsiveness of your business-critical applications.
ms.topic: article
author: lorihollasch
ms.author: loriwhip
ms.date: 07/29/2020
---

# Improve the performance of Azure applications by using Azure Advisor

The performance recommendations in Azure Advisor can help improve the speed and responsiveness of your business-critical applications. You can get performance recommendations from Advisor on the **Performance** tab of the Advisor dashboard.

## Upgrade your Storage client library to the latest version for better reliability and performance

The latest version of the Storage client library SDK contains fixes to problems reported by customers and proactively identified through our QA process. The latest version also carries reliability and performance optimization together with new features that can improve your overall experience with using Azure Storage. Advisor provides recommendations and steps needed to upgrade to the latest version of the SDK if you're using a stale version. The recommendations are for supported languages: C++ and .NET.

## Use managed disks to prevent disk I/O throttling

Advisor identifies virtual machines that belong to a storage account that's reaching its scalability target. This condition makes those VMs susceptible to I/O throttling. Advisor will recommend that they use managed disks to prevent performance degradation.
