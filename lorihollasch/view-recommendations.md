---
title: View Azure Advisor recommendations that matter to you
description: View and filter Azure Advisor recommendations to reduce noise.
ms.topic: article
author: lorihollasch
ms.author: loriwhip
ms.date: 04/03/2019
---

# View Azure Advisor recommendations that matter to you

Azure Advisor provides recommendations to help you optimize your Azure deployments. Within Advisor, you have access to a few features that help you to narrow down your recommendations to only those that matter to you.

## Configure subscriptions and resource groups

Advisor gives you the ability to select Subscriptions and Resource Groups that matter to you and your organization. You only see recommendations for the subscriptions and resource groups that you select. By default, all are selected. Configuration settings apply to the subscription or resource group, so the same settings apply to everyone that has access to that subscription or resource group. Configuration settings can be changed in the Azure portal or programmatically.

To make changes in the Azure portal:

1. Open [Azure Advisor](https://aka.ms/azureadvisordashboard) in the Azure portal.

1. Select **Configuration** from the menu.

   ![Advisor configuration menu](./media/view-recommendations/configuration.png)

1. Check the box in the **Include** column for any subscriptions or resource groups to receive Advisor recommendations. If the box is disabled, you may not have permission to make a configuration change on that subscription or resource group. Learn more about [permissions in Azure Advisor](permissions.md).
