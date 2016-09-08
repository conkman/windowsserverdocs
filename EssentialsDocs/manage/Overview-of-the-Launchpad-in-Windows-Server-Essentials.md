---
title: "Overview of the Launchpad in Windows Server Essentials"
ms.custom: na
ms.date: 01/14/2014
ms.prod: windows-server-2012-r2-essentials
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
applies_to: 
  - Windows Server 2012 Essentials
  - Windows Server 2012 R2 Essentials
ms.assetid: 198d16cb-3d07-4706-be89-ad14a5f7dc47
caps.latest.revision: 15
author: DonGill
manager: stevenka
translation.priority.ht: 
  - de-at
  - de-de
  - es-es
  - fr-be
  - fr-fr
  - it-ch
  - it-it
  - ja-jp
  - ko-kr
  - pt-br
  - ru-ru
  - zh-cn
  - zh-tw
---
# Overview of the Launchpad in Windows Server Essentials
The Windows Server Essentials Launchpad is a small application that is installed on a computer the first time the computer connects to the server. The Launchpad provides authenticated users with access to key features of Windows Server Essentials including computer backups, shared files and media, and the Remote Web Access site. Users can access these features from either domain-joined computers or non-domain joined computers. The Launchpad also provides real-time information and notifications about the health of the computer. Administrators can use the Launchpad to access the server Dashboard, even if the computer is not connected to the network.  
  
 OEMs and Independent Software Vendors (ISVs) who develop add-ins for Windows Server Essentials can use the Launchpad to extend add-in functionality to computers on the network.  
  
 The following Windows operating systems support the use of the Windows Server Essentials Launchpad:  
  
-   **Windows 8**: All editions.  
  
-   **Windows 7**: All editions.  
  
 The following operating systems do not support the use of the Windows Server Essentials Launchpad:  
  
-   **Additional servers**: You cannot run the Windows Server Essentials Launchpad on any additional computers that run a Windows Server operating system.  
  
 In this topic:  
  
-   [Use the Launchpad](../windows-server-essentials-manage/Overview-of-the-Launchpad-in-Windows-Server-Essentials.md#BKMK_Launchpad)  
  
-   [Use the Launchpad with a Mac computer](../windows-server-essentials-manage/Overview-of-the-Launchpad-in-Windows-Server-Essentials.md#BKMK_Mac)  
  
##  <a name="BKMK_Launchpad"></a> Use the Launchpad  
 The following links and information are available on the Windows Server Essentials Launchpad.  
  
### Backup  
 Click **Backup** to open the **Backup Properties** for the computer. On the **Backup Properties** page, you can:  
  
-   Start or stop a backup.  
  
-   View the status and details for the most recent backup.  
  
-   Specify how to manage computer power when backup runs.  
  
 For information about how to use Launchpad to back up your computer, see [Manage Client Backup](../windows-server-essentials-manage/Manage-Client-Computer-Backup-in-Windows-Server-Essentials.md).  
  
### Remote Web Access  
 Click **Remote Web Access** to open the web browser to the Remote Web Access site. The Remote Web Access site enables you to connect to other computers and to access some of the network resources from within the office or from any remote location with an Internet-enabled computer. For more information about Remote Web Access, see [Manage Remote Web Access](../windows-server-essentials-manage/Manage-Remote-Web-Access-in-Windows-Server-Essentials.md).  
  
### Shared Folders  
 Click **Shared Folders** to open Windows Explorer to the location of the shared folders on the server. For information about sharing files and folders, see the topic [Manage Server Folders](../windows-server-essentials-manage/Manage-Server-Folders-in-Windows-Server-Essentials.md).  
  
### Dashboard  
 Click  **Dashboard** to open the **Sign in** page for access to the Windows Server Essentials Dashboard. After you sign in, a Remote Desktop connection to the server Dashboard opens. For more information about the Dashboard, see [Dashboard Overview](../windows-server-essentials-manage/Overview-of-the-Dashboard-in-Windows-Server-Essentials.md).  
  
> [!NOTE]
>  To use this feature, you must have the proper access or permissions to log on to the server.  
  
### Microsoft Office 365  
 The **Microsoft Office 365** link only appears on the Launchpad if the user has an Office 365 account. Click  **Microsoft Office 365** to access additional links to the Office 365 resources. For more information, see [Quick Start Guide to Using Microsoft Office 365](../Topic/Quick%20Start%20Guide%20to%20Using%20Microsoft%20Office%20365%20with%20Windows%20Server%20Essentials.md).  
  
### Computer health alerts  
 Alerts that appear on the Launchpad provide a quick status as to the immediate health of the computer. To view information about a health alert, click an alert indicator to open the alert viewer. Health alerts appear in the viewer based on level of severity. The most severe alerts appear first in the list; less severe alerts appear later in the list. For more information about computer health alerts, see [Manage System Health](../windows-server-essentials-manage/Manage-System-Health-in-Windows-Server-Essentials.md).  
  
##  <a name="BKMK_Mac"></a> Use the Launchpad with a Mac computer  
 You can connect a Mac® computer running Mac OS X® 10.5 or later to [!INCLUDE[sbs_sbs8_2](../windows-server-essentials-manage/includes/sbs_sbs8_2_md.md)], [!INCLUDE[wseblue_2](../windows-server-essentials-manage/includes/wseblue_2_md.md)], or [!INCLUDE[winblue_server_2](../windows-server-essentials-manage/includes/winblue_server_2_md.md)] or by downloading and installing the connector software. When you finish installing the connector software, you can choose to automatically start the Launchpad at startup.  
  
 The Launchpad is a small application that provides authenticated users with access to key features of the server, including shared files and media, add-ins, and Remote Web Access. The Launchpad also provides real-time information and notifications about the health of the computer.  
  
> [!NOTE]
>  Server administrators cannot use the Launchpad or Remote Web Access on a Mac computer to open the server Dashboard and manage the server.  
  
### Backup  
 Click **Backup** to set up Time Machine to back up your computer and to change Time Machine settings. For more information about Time Machine, see the documentation from the manufacturer of your computer.  
  
### Remote Web Access  
 Click **Remote Web Access** to open the web browser to the [!INCLUDE[sbs8_rwa](../windows-server-essentials-manage/includes/sbs8_rwa_md.md)] site. The [!INCLUDE[sbs8_rwa](../windows-server-essentials-manage/includes/sbs8_rwa_md.md)] enables you to access the shared files and folders on the server from any remote location with an Internet-enabled computer. You can upload files, play music and videos on the web-based Media Play, and view pictures and play slide shows. For more information, see [Use Remote Web Access](../Topic/Use%20Remote%20Web%20Access%20in%20Windows%20Server%20Essentials.md).  
  
### Shared Folders  
 Click **Shared Folders** to open Finder to the location of the shared folders on the server. For information about sharing files and folders, see [Use Shared Folders](../Topic/Use%20Shared%20Folders%20in%20Windows%20Server%20Essentials.md).  
  
### Computer health alerts  
 Alerts that appear on the Launchpad provide a quick status about the immediate health of the computer. To view information about a health alert, click an alert indicator to open the alert viewer. Health alerts appear in the viewer based on level of severity. The most severe alerts appear first in the list. Less severe alerts appear later in the list.  
  
## See also  
  
-   [Get Connected](../Topic/Get%20Connected%20in%20Windows%20Server%20Essentials.md)  
  
-   [Use Windows Server Essentials](../Topic/Use%20Windows%20Server%20Essentials.md)  
  
-   [Manage Windows Server Essentials](../windows-server-essentials-manage/Manage-Windows-Server-Essentials.md)