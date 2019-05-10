---
title: Acrolinx report
description: This article discusses issues and fixes planned for the Acrolinx report. 
author: adunndevster
ms.author: adunndevster
manager: erifkin
ms.date: 01/10/2019
ms.prod: non-product-specific
ms.topic: contributor-guide
ms.custom: internal-contributor-guide
---
# Acrolinx report

The Acrolinx report has been restored to the SkyEye site thanks to work by the CGA team and Acrolinx. To access the report, go to [https://aka.ms/skyeye](https://aka.ms/skyeye) and click the Acrolinx Report tile.

## Things you need to know
- The columns/fields now should match the data in the actual scorecards - before this, there were some confusing legacy columns__.
- All content that has been run through the GitHub integration should be in the report.
- VSCode does not write results to the report. So the report contains no info for repos that are public only and where VSCode is the only Acrolinx tooling.
- There is currently no baseline for an entire repo, so there will only be results for content that has been updated intentionally by someone through a pull request. We are working with Acrolinx so that by end of February 2019 the GitHub integration will automatically baseline the content for an entire repo. In the meantime, do NOT artificially provoke massive runs of Acrolinx just to get data into the report.
 
## Improvement plan for the Acrolinx report

Here's the plan for making complete and correct Acrolinx data available to content teams.

| Action | Status |
|---|---|
| Correct the export of data from Acrolinx to MSFT. | Complete November 13, 2018 |
| Updated ingestion of data and mapping to MSFT article metadata, display in Power BI Acrolinx report, repost the report. | Complete January 10, 2019 |
| Acrolinx enables baseline scanning for new and existing repos. This new feature will let us make complete data available in the updated Acrolinx report. | Estimated delivery - March 2019. |

## Questions

If you have questions, contact tysonn.

