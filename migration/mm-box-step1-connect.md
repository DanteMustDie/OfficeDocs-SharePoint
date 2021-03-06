---
title: "Connect to Box with Migration Manager"
ms.date:  01/21/2021
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: serdars
audience: ITPro
f1.keywords:
- NOCSH
ms.topic: article
ms.service: sharepoint-online
localization_priority: Normal
mscollection:
- SPMigration
- M365-collaboration
search.appverid: MET150
description: "Steps to connect to Box when using Migration Manager in the SharePoint Admin center."
---

# Preview Step 1:  Connect your Box account to Microsoft 365

>[!Important]
> This feature is currently in private preview and subject to change without notice.

Sign in to your Box account and add the Microsoft 365 migration app to your Box account custom apps. 

1. From the [Migration page in the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=migrationCenter&modern), under **Box**, select **Get started**.
2. Select **Connect to Box**. 
3. Select **Authorize Mover**. Sign in with an account that has [admin permissions](/sharepoint/sharepoint-admin-role) for your organization. Click **Next**.
4. Select **Go to Enterprise applications**. This takes you to Azure.
5. Select the **Office 365 migration app**.
6. On the left hand panel under Security, select **Permissions**.
7. Click **Grant admin consent** for your account. You may be prompted for your credentials again. Return to the Migration Manager wizard screen.  Click **Next**.
8. Click **Authenticate account**. 
9. Sign in to grant access to Box. Select **Authorize** and then **Grant access to Box**.
10. You're now connected to Box. Click **Finish** to close the window.

>[!Important]
>For security reasons, you have 10 minutes to complete the steps to connect to Box. After 10 minutes of inactivity, the session will expire.

[Step 2: Scan and assess](mm-box-step2-scan-assess.md)