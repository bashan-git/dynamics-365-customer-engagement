---
redirect_url: https://docs.microsoft.com/powerapps/developer/common-data-service/enable-disable-duplicate-detection
title: "Sample: Enable duplicate detection and retrieve duplicates (Developer Guide for Dynamics 365 for Customer Engagement) | MicrosoftDocs"
description: "Sample demonstrating how to enable duplicate detection and retrieve duplicate records based on active duplicate detection rules."
ms.custom: 
ms.date: 11/15/2017
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: samples
applies_to: 
  - Dynamics 365 for Customer Engagement (online)
helpviewer_keywords: 
  - detecting duplicate data in Microsoft Dynamics CRM, sample for enabling duplicate detection and retrieving duplicates
  - duplicate detection, sample for enabling duplicate detection and retrieving duplicates
  - enabling duplicate detection and retrieving duplicates sample
  - sample for enabling duplicate detection and retrieving duplicates
ms.assetid: f3c2e3c0-5d17-43d8-a614-d772ae1c747e
caps.latest.revision: 14
author: JimDaly
ms.author: jdaly
manager: amyla
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# Sample: Enable duplicate detection and retrieve duplicates

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

This sample code is for [!INCLUDE[pn_dynamics_crm_online](../../includes/pn-dynamics-crm-online.md)] apps. Download the sample: [work with duplicate detections](https://code.msdn.microsoft.com/Work-with-duplicate-9c7d6f59).

## Prerequisites
[!INCLUDE[sdk-prerequisite](../../includes/sdk-prerequisite.md)]
  
## Requirements  
[!INCLUDE[sdk_SeeConnectionHelper](../../includes/sdk-seeconnectionhelper.md)]
  
## Demonstrates  
 This sample shows how to enable duplicate detection and retrieve duplicate records.  
  
## Example  
 [!code-csharp[DuplicateDetection#EnableDuplicateDetectionAndRetrieveDuplicates](../../snippets/csharp/CRMV8/duplicatedetection/cs/enableduplicatedetectionandretrieveduplicates.cs#enableduplicatedetectionandretrieveduplicates)]  
  
### See also  
 [Detect duplicate data in Dynamics 365 for Customer Engagement apps](../detect-duplicate-data-for-developers.md)   
 [Enable and disable duplicate detection](../enable-disable-duplicate-detection.md)  
 [Manage duplicate detection during Create and Update operations](manage-duplicate-detection-create-update.md)  
 [Run Duplicate Detection](../run-duplicate-detection.md)   
 <xref:Microsoft.Crm.Sdk.Messages.RetrieveDuplicatesRequest>   
 [Sample: Invoke Duplicate Detection For Creating and Updating Records](sample-use-duplicate-detection-when-creating-and-updating-records.md)
