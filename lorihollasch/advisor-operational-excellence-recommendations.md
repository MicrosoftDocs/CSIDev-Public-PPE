---
title: Improve operational excellency with Advisor
description: Use Azure Advisor to optimize and mature your operational excellence for your Azure subscriptions.
ms.topic: article
ms.date: 10/24/2019
author: jasonwhowell
ms.author: jasonh

---

# Achieve operational excellence by using Azure Advisor

Operational excellence recommendations in Azure Advisor can help you with: 
- Process and workflow efficiency.
- Resource manageability.
- Deployment best practices. 

You can get these recommendations on the **Operational Excellence** tab of the Advisor dashboard.

## Create Azure Service Health alerts to be notified when Azure problems affect you

We recommend that you set up Azure Service Health alerts so you'll be notified when Azure service problems affect you. [Azure Service Health](https://azure.microsoft.com/features/service-health/) is a free service that provides personalized guidance and support when you're affected by an Azure service problem. Advisor identifies subscriptions that don't have alerts configured and recommends configuring them.


## Design your storage accounts to prevent reaching the maximum subscription limit

An Azure region can support a maximum of 250 storage accounts per subscription. After you reach that limit, you won't be able to create storage accounts in that region/subscription combination. Advisor checks your subscriptions and provides recommendations for you to design for fewer storage accounts for any region/subscription that's close to reaching the limit.

## Ensure you have access to Azure cloud experts when you need it

When running a business-critical workload, it's important to have access to technical support when you need it. Advisor identifies potential business-critical subscriptions that don't have technical support included in their support plan. It recommends upgrading to an option that includes technical support.

## Delete and re-create your pool to remove a deprecated internal component

If your pool is using a deprecated internal component, delete and re-create the pool for improved stability and performance.
