---
title: Dfsdiag TestReferral
description: "Windows Commands topic for **** -- "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 877c60dc-e993-4bd5-87dd-e892e3f98a1a
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Dfsdiag TestReferral

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Checks Distributed File System \(DFS\) referrals by performing the following tests:  
  
-   When you use the DFSPath parameter without arguments, this command validates that the referral list includes all trusted domains.  
  
-   When you specify a domain, the command performs a health check of domain controllers \(Dfsdiag \/testdcs\) and tests the site associations and domain cache of the local host.  
  
-   When you specify a domain and \\SYSVOL or \\NETLOGON, in addition to performing the same health checks as when you specify a domain, the command checks that the Time To Live \(TTL\) of SYSVOL or NETLOGON referrals match the default value of 900 seconds.  
  
-   When you specify a namespace root, in addition to performing the same health checks as when you specify a domain, the command performs a DFS configuration check \(Dfsdiag \/TestDFSConfig\) and a namespace integrity check \(Dfsdiag \/TestDFSIntegrity\).  
  
-   When you specify a DFS folder \(link\), in addition to performing the same health checks as when you specify a namespace root, the command validates the site configuration for folder targets \(Dfsdiag \/testsites\) and validates the site association of the local host.  
  
  
  
## Syntax  
  
```  
DFSDiag /TestReferral /DFSPath:<DFS path for getting referrals> [/Full]  
```  
  
### Parameters  
  
|Parameter|Description|  
|-------------|---------------|  
|\/DFSPath:<Path for getting referrals>|This DFS path can be one of the following:<br /><br />-   \(blank\): Tests trusted domains.<br />-   \\\\Domain: Domain controller referrals.<br />-   \\\\Domain\\SYSVOL: SYSVOL referrals.<br />-   \\\\Domain\\NETLOGON: NETLOGON referrals.<br />-   \\\\<Domain or server>\\<Namespace Root>: Namespace root referrals.<br />-   \\\\<Domain or server>\\<Namespace root>\\<DFS folder>: DFS folder \(link\) referrals.|  
|\/Full|Applied only to Domain and Root  referrals. Verifies the consistency of site association information between the registry and Active Directory Domain Services \(AD DS\).|  
  
## <a name="BKMK_Examples"></a>Examples  
To TBD, type:  
  
```  
DFSDiag /TestReferral /DFSPath:\\Contoso.com\MyNamespace  
```  
  
To TBD, type:  
  
```  
DFSDiag /TestReferral /DFSPath:  
```  
  
## Additional references  
  
-   [Command-Line Syntax Key](Command-Line-Syntax-Key.md)  
  
