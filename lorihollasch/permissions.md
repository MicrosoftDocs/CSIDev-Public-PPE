---
title: Permissions in Azure Advisor 
description: Advisor permissions and how they may block your ability to configure subscriptions or postpone or dismiss recommendations.
ms.topic: article
author: jasonwhowell
ms.author: jasonh
ms.date: 04/03/2019
---

# Permissions in Azure Advisor

Azure Advisor provides recommendations based on the usage and configuration of your Azure resources and subscriptions.

Test test.

## Roles and their access

The following table defines the roles and the access they have within Advisor:

| **Role** | **View recommendations** | **Edit rules** | **Edit subscription configuration** | **Edit resource group configuration**| **Dismiss and postpone recommendations**|
|---|:---:|:---:|:---:|:---:|:---:|
|Subscription Owner|**X**|**X**|**X**|**X**|**X**|
|Subscription Contributor|**X**|**X**|**X**|**X**|**X**|
|Subscription Reader|**X**|--|--|--|--|
|Resource group Owner|**X**|--|--|**X**|**X**|
|Resource group Contributor|**X**|--|--|**X**|**X**|
|Resource group Reader|**X**|--|--|--|--|
|Resource Owner|**X**|--|--|--|**X**|
|Resource Contributor|**X**|--|--|--|**X**|
|Resource Reader|**X**|--|--|--|--|

> [!NOTE]
> Access to view recommendations is dependent on your access to the recommendation's impacted resource.

## Permissions and unavailable actions

Lack of proper permissions can block your ability to perform actions in Advisor. Following are some common problems.
