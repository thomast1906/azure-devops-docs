---
title: Code Churn tables 
titleSuffix: Azure DevOps Server 
ms.technology: devops-analytics
ms.topic: reference
description: Query for data about the changes in the code that is under version control  
ms.assetid: c158a791-7f9d-4440-aa47-87a9497da9e2
ms.author: kaelli
author: KathrynEE
ms.date: 10/17/2017
---

# Code Churn tables

[!INCLUDE [temp](../includes/tfs-report-platform-version.md)]

You can query for data about the changes in the code that is under version control by using FactCodeChurn and the associated dimension tables. The fact table contains one record for each revision of a file in each changeset.  
  
 For a description of the measures and dimensions that are associated with these tables in the Analysis Services cube, see [Code churn and code coverage](perspective-code-analyze-report-code-churn-coverage.md).  
  
 ![Fact Table for Code Churn](media/teamproj_factcodechurn.png "TeamProj_FactCodeChurn")  
  
 FactCodeChurn is associated with the following dimension tables:  
  
-   DimChangeset  
  
-   DimDate  
  
-   DimFile  
  
-   DimTeamProject  
  
## Related articles
-  [Code churn and code coverage](perspective-code-analyze-report-code-churn-coverage.md)   
-  [Code Churn](/previous-versions/azure/devops/report/excel/code-churn-excel-report)   
-  [Run Coverage tables](run-coverage-tables.md)   
-  [Table reference for the relational warehouse database](table-reference-relational-warehouse-database.md)