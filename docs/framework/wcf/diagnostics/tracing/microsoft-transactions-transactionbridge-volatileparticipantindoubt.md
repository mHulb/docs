---
title: "Microsoft.Transactions.TransactionBridge.VolatileParticipantInDoubt | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 3e8fc825-9f22-47e7-9c16-d64ef291c932
caps.latest.revision: 5
author: "Erikre"
ms.author: "erikre"
manager: "erikre"
---
# Microsoft.Transactions.TransactionBridge.VolatileParticipantInDoubt
The WS-AT protocol service received a Prepared or Replay message from an unrecognized volatile participant. A fault was returned to the participant, declares that the transaction's outcome is in doubt.  
  
## Description  
 Traced when the local Transaction Manager receives a Prepared or Replay message from a Volatile enlistment that it has already forgotten.  
  
## Troubleshooting  
 Investigate potential causes of late messages coming from the Volatile participant.  
  
## See Also  
 [Tracing](../../../../../docs/framework/wcf/diagnostics/tracing/index.md)   
 [Using Tracing to Troubleshoot Your Application](../../../../../docs/framework/wcf/diagnostics/tracing/using-tracing-to-troubleshoot-your-application.md)   
 [Administration and Diagnostics](../../../../../docs/framework/wcf/diagnostics/index.md)