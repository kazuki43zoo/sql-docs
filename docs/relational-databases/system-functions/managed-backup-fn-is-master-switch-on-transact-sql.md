---
title: "managed_backup.fn_is_master_switch_on (Transact-SQL) | Microsoft Docs"
ms.custom: ""
ms.date: "06/10/2016"
ms.prod: "sql-non-specified"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "language-reference"
f1_keywords: 
  - "fn_is_master_switch_on"
  - "fn_is_master_switch_on_TSQL"
  - "smart_admin.fn_is_master_switch_on"
  - "smart_admin.fn_is_master_switch_on_TSQL"
dev_langs: 
  - "TSQL"
helpviewer_keywords: 
  - "smart_admin.fn_is_master_switch_on"
  - "fn_is_master_switch_on"
ms.assetid: e8c2108d-b104-46cb-9645-a15f46112c86
caps.latest.revision: 12
author: "MikeRayMSFT"
ms.author: "mikeray"
manager: "jhubbard"
ms.workload: "Inactive"
---
# managed_backup.fn_is_master_switch_on (Transact-SQL)
[!INCLUDE[tsql-appliesto-ss2016-xxxx-xxxx-xxx_md](../../includes/tsql-appliesto-ss2016-xxxx-xxxx-xxx-md.md)]

  Returns the state of the [!INCLUDE[ss_smartbackup](../../includes/ss-smartbackup-md.md)] operations on the instance of SQL Server.  
  
 Use this function to get the current state of [!INCLUDE[ss_smartbackup](../../includes/ss-smartbackup-md.md)].  
  
 
 ![Topic link icon](../../database-engine/configure-windows/media/topic-link.gif "Topic link icon") [Transact-SQL Syntax Conventions](../../t-sql/language-elements/transact-sql-syntax-conventions-transact-sql.md)  
  
## Syntax  
  
```tsql  
managed_backup.fn_is_master_switch_on ()  
```  
  
##  <a name="Arguments"></a> Arguments  
 None  
  
## Return Type  
 **BIT**  
  
 1 = [!INCLUDE[ss_smartbackup](../../includes/ss-smartbackup-md.md)] is active, 0 = [!INCLUDE[ss_smartbackup](../../includes/ss-smartbackup-md.md)] is paused.  
  
## Security  
  
### Permissions  
 Requires SELECT permissions on the function.  
  
## See Also  
 [SQL Server Managed Backup to Microsoft Azure](../../relational-databases/backup-restore/sql-server-managed-backup-to-microsoft-azure.md)  
  
  
