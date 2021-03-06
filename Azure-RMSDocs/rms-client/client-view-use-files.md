---
# required metadata

title: View and use protected files | Azure Information Protection
description: Instructions to view and use a protected file that requires you to have the Azure Information Protection client installed.
author: cabailey
ms.author: cabailey
manager: mbaldwin
ms.date: 02/10/2017
ms.topic: article
ms.prod:
ms.service: information-protection
ms.technology: techgroup-identity
ms.assetid: ce1c7d4c-b5ff-4672-8b9a-a72129bac992

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: esaggese
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# View and use files that have been protected by Rights Management

>*Applies to: Active Directory Rights Management Services, Azure Information Protection, Windows 10, Windows 8.1, Windows 8, Windows 7 with SP1*

You can often view a protected file by simply opening it. For example, you might double-click an attachment in an email message or double-click a file from File Explorer, or you might click a link to a file.

If the file doesn't open, you can use the **Azure Information Protection Viewer** to open it. This viewer automatically installs as part of the Azure Information Protection client, or you can install it separately. You can install both the client and the viewer from the [Microsoft Azure Information Protection](https://go.microsoft.com/fwlink/?LinkId=303970) page on the Microsoft website. For more information about installing the client, see [Download and install the Azure Information Protection client](install-client-app.md).

> [!NOTE]
> Although installing the client provides more functionality, it requires local administrator permissions and the full functionality requires a corresponding service for your organization:
> 
> - Azure Information Protection
> 
> - Azure Rights Management
> 
> - Active Directory Rights Management Services 
> 
> Install the viewer if you have been sent a protected document by somebody from another organization or if you do not have local administrator permissions to your PC.

## Prompts for authentication

Before you can view the protected file, the Rights Management service that was used to protect the file must first confirm that you are authorized to view the file. The service does this by checking your user name and password. In some cases, this might be cached and you will not see a prompt that asks for your credentials. In other cases, you will be prompted to supply your credentials.

If your organization does not have a cloud-based account for you to use (for Office 365 or Azure) and does not use an equivalent on-premises version (AD RMS), you can apply for a free account that will accept your credentials so that you can open files that are protected by Rights Management:

-   To apply for this account, click the link to apply for [RMS for individuals](http://go.microsoft.com/fwlink/?LinkId=309469).
    
    When you sign up, use your company email address rather than a personal email address. If you are signing up because you were emailed a protected attachment, use the same email address that was used to send you the email message.
    
-   For more information, see [RMS for individuals and Azure Rights Management](../understand-explore/rms-for-individuals.md).

## To view and use a protected file

1. Open the protected file (for example, by double-clicking the file or attachment, or by clicking the link to the file). If you are prompted to select an app, select **Azure Information Protection Viewer**. 

2. If you see a page to **Sign in** or **Sign up**: Click **Sign in** and enter your credentials. If the protected file was sent to you as an attachment, be sure to specify the same email address that was used to send you the file.
    
    If you do not have an account that is accepted, see the [Prompts for authentication](#prompts-for-authentication) section on this page. Sign up for a free account and return to these instructions.

3. A read-only version of the file opens in the **Azure Information Protection Viewer**. If you have sufficient permissions, you can print the file, and edit it. 

    You can check your permissions for the file by clicking **Permissions**. From the **Permissions** dialog box, you can also identify the file owner to contact if you want to request a new version of the file with additional permissions.
    
    For more detailed information about the permissions and the usage rights that each contains, see [Rights included in permissions levels](../deploy-use/configure-usage-rights.md#rights-included-in-permissions-levels).

4. To edit the file, click **Save As**, which lets you save the file without protection to its original file name extension. You can then edit the file by using the application that's associated with that file type.

5. If you have additional protected files to open, you can browse directly to them from the viewer, by using the **Open** option. Your selected file replaces the original file in the viewer. 

> [!TIP]
> If the protected file does not open, download and use the [RMS Analyzer tool](https://www.microsoft.com/en-us/download/details.aspx?id=46437). Follow the instructions in the tool to check for problems on your computer that might prevent a protected document from opening.


## Other instructions
More how-to instructions from the Azure Information Protection user guide:

-   [What do you want to do?](client-user-guide.md#what-do-you-want-to-do)


[!INCLUDE[Commenting house rules](../includes/houserules.md)]