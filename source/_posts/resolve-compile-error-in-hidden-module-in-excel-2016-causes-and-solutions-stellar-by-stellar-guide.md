---
title: Resolve Compile Error in Hidden Module in Excel 2016 Causes & Solutions | Stellar
date: 2024-05-20T10:20:28.119Z
updated: 2024-05-21T10:20:28.119Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Resolve Compile Error in Hidden Module in Excel 2016 Causes & Solutions
excerpt: This article describes Resolve Compile Error in Hidden Module in Excel 2016 Causes & Solutions
keywords: repair corrupt .xls,repair corrupt .xltx files,repair corrupt .csv,repair damaged excel,repair damaged .xlsm files,repair excel 2019
thumbnail: https://www.lifewire.com/thmb/asCAao3Tfs8ZxVZumyLz52-mVek=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-increase-internet-speed-5181475-b6fd84098c634a04a6934302184c5b1b.jpg
---

## Resolve Compile Error in Hidden Module in Excel: Causes & Solutions

The hidden module in Excel refers to a container with VBA codes, custom queries, and complex macros. The compile error in a hidden (protected) module in the Excel worksheet usually occurs when doing different activities on a macro-enabled sheet, such as merging .xls files. The error can result in macros execution failure. You need to quickly resolve this compile error to restore full functionality of the VBA code. Below, we’ll be discussing the solutions to fix this Excel error. But before that, let’s see why this error occurs.

You may encounter the Compile error in hidden module due to one of the following reasons:

- The code in the workbook is not compatible with the Excel application.
- Manual queries created in a previous version are no longer compatible with your current version of Excel.
- Missing references.
- Invalid .exe files (control information cache files) are automatically created with ActiveX control insertion in Excel file.
- Protected module is corrupted.
- The workbook with hidden module is damaged or corrupted.
- Incompatible add-ins.
- Incompatible Excel file version.
- The module is protected or password-protected.
- Missing or corrupted mscomctl.ocx file.

Excel can throw the compile error while compiling the code that exists in the protected module. So, first check the error and identify the hidden module that is creating the issue. You can unprotect the module. Also, ensure that you have permission to access the VBA code in the module. If the error still exists, follow the below troubleshooting methods.

### Method 1: Re-register ActiveX Control Files or mscomctl.ocx Files

You can get the compile error in the Excel file, containing the VBA code related to ActiveX controls or OCX files. The ActiveX control files and OCX files (mscomctl.ocx files) are the components of Microsoft’s standard controls library. The compile error in the hidden module can occur if these files are missing. In this case, you can use the Regsvr32 tool to re-register the OCX files. The [Regsvr32](https://support.microsoft.com/en-au/topic/how-to-use-the-regsvr32-tool-and-troubleshoot-regsvr32-error-messages-a98d960a-7392-e6fe-d90a-3f4e0cb543e5) is a command-line utility to register and unregister OLE controls in the Windows registry.

### Method 2: Delete .exd Files

 The .exd files are temporary files created by Excel when inserting ActiveX controls objects. These temporary files can lead to a compile error if they are corrupted. So, if this issue has occurred, particularly in the Excel file containing ActiveX controls, then deleting .exd files might fix the issue. To delete the .exd file, follow the below steps:

- First, open the **Run** window by pressing the Windows+R keys.

![Open The Run Window](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/open-the-run-window.jpg)

- In the **Run** window, type **%appdata%**.

![Type App Data Command](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/type-app-data-command.jpg)

- In the **Roaming** window, click on the **Microsoft** option.

![Click On Microsoft Option Under Roaming](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/click-on-microsoft-option-under-roaming.jpg)

- Under **Microsoft**, you will see a list of folders. Search and click on **Forms.**
- Right-click on a file with .exd extension and select **Delete**.
- Once you delete the .exd files, restart your Excel application.

### Method 3: Rollback the Office Updates

MS Office updates or upgrades may also cause the compile error in hidden module in Excel. If the error has occurred after downloading the recent Microsoft Office updates, try [reverting to the previous version](https://support.microsoft.com/en-us/topic/how-to-revert-to-an-earlier-version-of-office-2bd5c457-a917-d57e-35a1-f709e3dda841) or uninstalling the recent updates to fix the issue.

### Method 4: Unselect Missing References

The compile error in hidden module determine path in Excel can also occur if your file contains a reference to object library/type library, which is labelled as Missing. You can locate, check, and uncheck the references marked as ‘Missing’ to fix the issue. Here are the steps:

- Open your **Excel** and press **Alt + F11** keys.
- The **Visual Basic Editor** is displayed.

![Visual Basic Editor](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/visual-basic-editor.jpg)

- Go to the **Tools** option and then click **References**.

![Click On References Under Tools Option](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/click-on-references-under-tools-option.jpg)

- In the **References-VBAProject** window, under **Available References**, search and unselect the references starting as “Missing”.

![Unselect Missing References](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/unselect-missing-references.jpg)

- Click **OK**.

### Method 5: Check the Code in Module

The compile error in hidden module can occur if there are issues in the code within the module. The problems include incorrect or missing syntaxes, missing parameters/references, or the code contains incompatible functions or a wrong name of the object. You can check and fix these issues in the code by opening the VBA editor.

### Method 6: Check and Remove Add-ins

In Excel, the compile error in macro-enabled files can also occur due to incompatible add-ins. You can check and disable the **add-ins** in Excel using the below steps:

- First, open the **Run** window and type excel /safe and then click **OK**. The Excel application will open in safe mode.
- Now try to open the affected Excel file. If it opens without the error, then check and remove the latest installed Excel add-ins.
- Navigate to the **File** option and then select **Options**.
- In the **Excel Options** window, click **Add-ins**.

![Click Addins Select Latest Addins](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/click-add-ins-select-latest-add-ins.jpg)

- Under **Add-ins**, search and select the latest add-ins, and then click on **Go**.
- In the **Add-ins** window, uncheck the add-ins and then click **OK**.

![Select  Analysis Toolpak](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/select-analysis-toolpak.jpg)

- Restart Excel and then check if the error is fixed or not.

### Method 7: Repair the Corrupt Excel File

Corruption in the Excel file can affect the macros in the hidden module, which may result in the compile error. In such a case, you can try repairing the Excel file using Microsoft’s inbuilt utility -Open and Repair. To use this tool, follow these steps:

- Open your Excel application.
- Click the **File** tab and then click **Open**.
- Click **Browse** to select the affected workbook.
- The **Open** dialog box will appear. Click on the corrupted file.
- Click the arrow next to the **Open** button and then **Open and Repair**.
- You will see a dialog box with three buttons - Repair, Extract Data, and Cancel.

![Click On Repair Option](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/click-on-repair-option-1.jpg)

- Click on the Repair button to recover as much of the data as possible.
- After repair, a message is displayed. Click **Close**.

![Message Appear After Repair](https://www.stellarinfo.com/blog/wp-content/uploads/2023/07/message-appear-after-repair.jpg)

## **What if None of the Above Solutions Works?**

If the above methods fail to get rid of the “compile error in hidden module” in Excel, then use an Excel repair tool such as Stellar Repair for Excel. This tool is specifically designed to repair the corrupted Excel file. It can recover all the components from corrupted Excel file (macros, queries, formulas, etc.) without changing their original formatting. The tool is compatible with all Excel versions and can be downloaded on a Windows system. You can download the free trial version of Stellar Repair for Excel to scan the corrupted Excel file and preview the data.

## **Closure**

You can get the “compile error in hidden module” when Excel detects any issue while compiling the code in a protected module. It can occur when there is an issue with the macro-enabled Excel workbook or Excel add-ins. You can follow the above-mentioned methods to fix the issue. If the error occurs due to corruption in the database file, then you can try [Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/). It can repair severely corrupted Excel files. It also helps recover all the Excel workbook’s components, including macros and queries. The tool has a simple and user-friendly interface.


## \[Solved\] : How to Fix MS Excel Crash Issue

Microsoft [Excel may stop responding](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/), hang, freeze, or stop working due to several reasons, such as in compatible add-ins. In such a case, you may receive one of the following error messages.

- Excel has stopped working

![Excel has stopped working](https://www.stellarinfo.com/public/image/catalog//article/email-repair/exchange/excelnew1.jpg)

- Excel is not responding

![Excel is not responding](https://www.stellarinfo.com/image/catalog/article/excelnew2.jpg)

- A problem caused the program to stop working correctly. Windows will close the program and notify you if a solution is available.

![A problem caused the MS Excel to stop working correctly](https://www.stellarinfo.com/image/catalog/article/excelnew3.jpg)

## Why Does Excel Keep Crashing?

If Excel keeps crashing on your PC while opening a workbook, saving Excel file, scrolling or editing cells, etc., it indicates a problem with your Excel program or the Excel file.

Microsoft Excel may crash due to any one or more reasons given below,

-  Incompatible Add-Ins
- Outdated MS Excel program
- Conflict with other programs or antivirus tool
-  Excel file created by third party software
- Problem with network connection
-  Combination of Cell formatting and stylings
- Problem with MS Office installation
- Partially damaged or corrupt Excel file

## Problems Caused by Excel Crash Issue

Microsoft Excel crash may cause damage to Excel file and also lead to Excel (XLS/XLSX) file corruption.

Such corrupt Excel files can't be opened or accessed via MS Excel app. If you try to access a corrupt Excel file, MS Excel may fail to open the file or stop responding and crash. Additionally, you may receive the following or similar error message,

![Excel files can't be opened or accessed](https://www.stellarinfo.com/image/catalog/article/excelnew4.jpg)

In such a case, you should immediately try to recover the Excel file. You may do so by restoring the Excel file from backup or by using an [Excel File Repair software.](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/) Otherwise, continue following this guide.

## How to Solve Excel Crash Issue?

Before heading to solutions, follow these troubleshooting steps to resolve the Excel Crash issue.

### **Step 1: Copy File to Local Drive**

If you are trying to access and edit or view an Excel file from a network drive, try moving the file to local drive. This will help you find if there is something wrong with the file or the network.

### **Step 2: Ensure Sufficient Memory**

Excel files can grow fairly large when you start adding lots of formatting and shapes. Make sure that your system has enough RAM to run the application.

![Ensure Sufficient Memory](https://www.stellarinfo.com/image/catalog/article/excelnew5.jpg)

If you often work with large Excel files and complex data values& formulas, then install 64-bit versions of MS Office. It will give you an advantage of larger processing capacities and prevent Excel from crash or freeze.

### **Step 3: Check If Excel is Open and In Use by Another Process**

Open **Task Manager** and close all processes or apps (tasks) that may be using or have access to your Excel file that you are working on. You can find this detail in status bar of Excel program at the bottom of program window.

![Task Manager](https://www.stellarinfo.com/image/catalog/article/excel6.jpg)

After closing the tasks, try to access the Excel file and check if this fixes the performance and crash problem in Excel.

### Step 4: Test and Repair Excel File

Create a copy of the Excel file and install **Stellar Repair for Excel** software. It's free to download. Scan and repair your Excel file using the software. After repair, save the Excel file at your desired location and then open the Excel file in the MS Excel program.

![Stellar Repair for Excel software](https://www.stellarinfo.com/image/catalog/article/excel7.jpg)

This should ideally fix all the issues with Excel.

However, if the Excel program still crashes, the problem lies within the system or program. Follow the solutions discussed in this guide to try to fix the Excel crash issue.

**NOTE:** To save repaired Excel file using the mentioned software, you must purchase the activation key and activate it.

## Solutions to Fix MS Excel Crash Issue

Following are some solutions to resolve problems with MS Excel such as,

- Excel not responding
- Excel won't open
- Excel keeps crashing

Follow these solutions in the given order. In case a method doesn't work, move to the next one.

### Solution 1: Restart Excel in Safe Mode

By starting MS Excel in safe mode, you can run the program without loading the Excel add-ins and with limited features. But COM add-ins are excluded.

To launch Excel in safe mode, close MS Excel and follow these steps,

- Create a shortcut of MS Excel (.exe) on Desktop
- Press and hold the Ctrl key while launching the program
- Click 'Yes' when a prompt appears to confirm

Alternatively, press Windows+R, type excel /safe and press 'Enter'. Use this to open Excel in safe mode on Windows 10, 8.1, 8, or 7 system.

![type excel /safe](https://www.stellarinfo.com/image/catalog/article/excel8.jpg)

Now try to open and access the Excel file and check if the issue is resolved. If it's not, head on to the next solution.

### Solution 2: Check and Remove Faulty Add-ins

In case Excel doesn't crash in Safe Mode, it's possible that some faulty add-ins are the culprit behind frequent Excel crash and freeze. These Excel add-ins may interfere or conflict with the Excel program.

![Check and Remove Faulty Add-ins](https://www.stellarinfo.com/image/catalog/article/excel9.jpg)

Find and remove the faulty add-in. It can resolve the issue. To do so, follow these steps,

- Restart Excel in normal mode and go to File> Options> Add-ins
- Choose COM Add-ins from the drop-down and click Go

![COM Add-ins](https://www.stellarinfo.com/image/catalog/article/excel10.jpg)

- Uncheck all the checkboxes and click OK

![Uncheck all the check boxes](https://www.stellarinfo.com/image/catalog/article/excel11.jpg)

- Restart Excel and check if the issue is resolved
-  If Excel doesn't crash or freeze anymore, open COM Add-ins and enable one add-in at a time followed by Excel restart. Then observe Excel for freeze or crash problem

This will help you find out the faulty add-in, which is causing the problem. Remove the add-in which is causing the problem to resolve the issue. If that doesn't fix, move to the next solution.

### Solution 3: Check and Install the Latest Updates

If you haven't set Windows to Download and Install Updates automatically, do it now.

Apart from updating the operating system, latest Windows updates sometimes fixes bugs for other applications installed on the system such as MS Office. Often installing an important update that you might have missed may correct the Excel crash problem.

You can also update MS Office manually. Follow these steps,

Go to File > Account

 Under Product Information, select Update Options and click Update Now

![Product Information](https://www.stellarinfo.com/image/catalog/article/excel12.jpg)

If you have installed MS Excel from Microsoft Store, open the store and update your Office applications.

NOTE: This also works if you can't open Excel file or Excel crashes after Windows upgrade from Windows 7 or Windows 8/8.1 to Windows 10.

After installing the latest MS Office updates, check if Excel works fine. If not, head to the next solution.

### Solution 4: Clear Conditional Formatting Rules

If a sheet is causing Excel to freeze or crash, there might be a problem with that particular sheet. In such a case, you may try clearing the Conditional Formatting rules. The steps are as follows,

- Under Home, click 'Conditional Formatting > Clear Rules\> Clear Rules from Entire Sheet'

![Conditional Formatting](https://www.stellarinfo.com/image/catalog/article/excel13.jpg)

- You may repeat this step for all other sheets in the Excel workbook
- Then click File> Save as and save the Sheet as a new file at a different location

This avoids overwriting or making changes to the original Excel file. Once done, try working on the sheet.

If this doesn't work out, move to the next solution.

### Solution 5: Remove Multiple Cell Formatting and Styles

If a workbook is being shared and edited by others on different platforms then it's possible that many cells are formatted differently. This can cause issues with Excel such as crash and freeze. It can also lead to Excel file corruption. The problem mostly occurs when a workbook contains multiple worksheets using different formatting.

You can [follow this guide](https://docs.microsoft.com/en-gb/office/troubleshoot/excel/too-many-different-cell-formats-in-excel) to remove different cell formats and styles, and then open the Excel file.

### Solution 6: Disable Microsoft Excel Animation

Animations require additional processing power and resources. By disabling animations in Excel, you may resolve Excel freeze and crash issue. This also improves MS Excel performance.

To disable the animations in MS Excel, follow these steps:

- Go to File > Options
- Click 'Advanced' and check 'Disable hardware graphics acceleration'animation

![Disable hardware graphics acceleration](https://www.stellarinfo.com/image/catalog/article/excel14.jpg)

- Click 'OK' to close the window and then restart MS Excel

This has helped many users in fixing the Excel crash issue. If it doesn't work for you, head to the next solution.

### Solution 7: Check If Excel File is Generated by a Third-Party Application

There are applications which you may have used to generate Excel files to fetch data. For instance, downloading data from Google Analytics in Excel format.

Sometimes, these Excel files are not generated correctly by such third-party apps. Thus, some features in Excel may not work as intended when you access the files in MS Excel.

In such a case, you should get in touch with the app developer for help with the file or use Stellar Repair for Excel to repair such Excel files.

### Solution 8: Check If Antivirus or Other Apps are Conflicting with MS Excel

Ensure your antivirus is up-to-date and not conflicting with MS Excel. An outdated antivirus tool may conflict with Excel which can cause the application to hang, freeze, or crash.

- Update your antivirus
- Try disabling the add-in or integration between Excel and antivirus. See if it works

Alternatively, you may disable the anti-virus tool temporarily to check if it is the culprit behind Excel performance issue and crash. If that resolves the problem, get in touch with your antivirus vendor and report the problem.

They might provide you with a better solution or workaround to fix this problem without disabling the antivirus protection.

IMPORTANT NOTE: Disabling or altering antivirus protection makes your PC vulnerable to malicious attacks and virus or malware intrusion.

### Solution 9: Clean Boot Windows to Inspect the Cause Behind Excel Crash

When Windows boot, it starts several processes, services, and application during start up automatically, which runs in the background.

These startup apps and services can interfere with other applications such as MS Excel. To find out if that's the cause behind Excel crash, you can perform a Clean Boot.

This helps you identify processes, services, or applications that are conflicting with Excel. Steps to perform Clean Boot are as follows,

- Press Windows key + R, type MSConfig, and press 'Enter'
- In System Configuration window, click on the General tab and choose Selective startup

![System Configuration](https://www.stellarinfo.com/image/catalog/article/excel15.jpg)

Uncheck 'Load startup items' and click 'OK'

After this, close all running applications and restart your PC

Check if the crash problem with Excel is resolved. Uninstall the conflicting apps or update them. If your issue is not resolved, follow the next solution.

### Solution 10: Repair or Reinstall MS Office

Repairing Office programs may also resolve Excel crash issues if caused by damaged MS Excel program or MS Office files. The steps are as follow,

- Close all MS Office apps and open the Control Panel
- Click Uninstall a program under Programs

![Uninstall a program](https://www.stellarinfo.com/image/catalog/article/excel16.jpg)

- Click on Microsoft Office and then click on the Change option
- Choose 'Quick repair' and then select 'Repair'
- Click 'Continue' to repair MS Office installation

You may also try 'Online Repair' if this fails to fix the issue. After repair, if the Excel issue persists, reinstall MS Office.

## Need More Help?

If none of the above-mentioned solutions worked for you, it indicates that the problem is not with the Excel program but with the Excel file. If you haven't tried the Stellar Repair for Excel software, do it now.

Select the Excel file which is causing the problem and repair it with the software. It's a powerful Excel repair software that can fix all the problems with Excel files (XLS/XLSX). It repairs corrupt and severely damaged Excel files.

The software is compatible with all Excel files created using MS Excel 2019, 2016, 2013, 2010, 2007, 2003 or 2000.

After repairing and saving the Excel file, you can open it in your MS Excel program and work on it without any performance issue. To know more about this software, visit [this page.](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)


## Excel Stuck at Opening File 0% - Resolve Performance Issues

**Summary:** If an Excel workbook is stuck at opening file 0%, it usually indicates a problem with the Excel file and its objects. This may happen due to Excel file corruption and a few other reasons. In this post, we have discussed these reasons along with the methods to fix and prevent ‘Excel stuck at opening file 0%’ issue.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

When you open an Excel file (XLS/XLSX) in MS Excel, the program reads and then loads the file data along with all its objects and properties. While opening and loading an Excel file, MS Excel displays an “_Opening percentage_.” You won’t usually notice or see this Excel file opening progress percentage while accessing smaller worksheets.

It’s more noticeable when you open a large Excel file or workbook with multiple objects, formulae, formatting, etc. However, after opening an Excel file with double-click, if it is stuck at _Splash Screen_ with a message “**Opening: FileName.xlsx (0%)”** for a while (say 15-30 minutes) and does not progress, it indicates a problem with the Excel file, MS Excel program, or the system.  

![excel stuck at 0 percent](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/excel-stuck-at-opening-1024x576.png)

## Why Excel is Stuck at Opening File 0%?

If you have encountered this error, it may happen due to one of the following issues,

1. Damaged or corrupt Excel file
2. Incompatible or faulty Excel add-ins
3. Problem with the system’s display driver
4. Damaged MS Office (Excel) application

## Methods to Fix ‘Excel Stuck at Opening File 0%’ Issue

Before fixing and troubleshooting the problem, check and confirm if the Excel file is working and not corrupt. For this, you can try opening it on another PC. Now there could be two scenarios,

### **Scenario 1:  Excel File Does Not Open**

If the Excel file doesn’t open on another PC also, it indicates Excel file corruption. In such cases, look for the backup copy of the file, if you have downloaded it from an email or a website.

However, if there’s no backup, then you need an Excel file repair software, such as **Stellar Repair for Excel** to repair the corrupt file. This software preserves Excel file properties, such as cell formatting, formula bar, freeze panes, gridlines, etc. and helps you restore the damaged or corrupt worksheets to its original state with 100% integrity.

[![free download](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2022/09/free-download-1.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)

To repair Excel file, download and launch _Stellar Repair for Excel_ software on your PC, choose the corrupt Excel (XLS/XLSX) file and click ‘**Repair’**. You can see the preview of your Excel file with all data and then save the repaired file at your desired location on the system as a new Excel file.

![stellar repair excel file](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Stellar-repair-for-excel.jpg)

### **Scenario 2: Excel File Is Accessible on Another PC**

If the Excel file opens successfully on another PC, then follow the troubleshooting methods below to resolve the Excel file stuck opening at 0%.

## Method 1: Open MS Excel in Safe Mode

To check if an incompatible or faulty add-in or setting is causing the error, restart MS Excel in safe mode and then open the worksheet from the MS Excel ‘**File**’ options. The steps are as follows,

1. Press **Windows+R** and type **excel.exe /safe**
2. Hit **Enter** or press ‘**OK**’ to open MS Excel in safe mode

![open excel in safe mode](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/run-excel-in-safe-mode.png)

- Go to **File > Open** and then choose the Excel file to open it
- If it opens, the problem is probably caused by the add-ins. Go to **File > Options > Add-ins > Manage > COM Add-ins** and disable all the third-party add-ins

![remove faulty add in from excel](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/check-and-remove-faulty-add-ins-1024x540.png)

- Restart MS Excel normally and then go to **File > Open** and open the same Excel file. If it opens, the problem is solved.

However, if you want to keep the add-ins, enable one add-in at a time and open the same file to find which add-in is causing the problem. When found, remove the faulty add-in.

If it doesn’t work, head to the next solution.

## Method 2. Disable Hardware Graphics Acceleration

If you’re using hardware graphics acceleration adapter to run an external monitor, you may encounter problems with the Excel application. If the adapter is plugged in but doesn’t work correctly, Excel will usually hang on the loading screen. To resolve this problem, you will need to disable the hardware graphics acceleration adapter by following these steps,

- Quit all running instances of Excel from **Task Manager**

![task manager to close program](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Check-task-manager.png)

- Launch MS Excel directly, don’t _double-click_ on the faulty workbook file to open MS Excel as it won’t open
- Click on **File > Options > Advanced**

![Disable hardware graphics acceleration](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Disable-hardware-graphics-acceleration.png)

- Under the ‘**Display**’ options, check the box ‘**Disable hardware graphics acceleration**’
- Click on ‘**OK**’

Try to open the Excel file now. If it still doesn’t work, move to the next solution.

## Method 3. Repair MS Excel Application and Install the Latest Updates

Problems within MS Excel installation could also be a source of many unknown issues. Messed up registry settings, bugged updates, and even wrong user ‘**Preferences**’ can cause your Excel application to behave unusually. The fix for all such issues is to repair the Excel installation. To do so, follow these steps,

- Open **Control Panel**
- From **Category** view, under **Programs**, select **Uninstall a program**
- Click on the MS Office and then click ‘**Change**’

![repair ms office](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Repair-MS-Office-installation-1024x577.png)

- When prompted, click on ‘**Repair’** and then follow the instructions to complete the repair process

![quick repair ms office](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Quick-repair-MS-Excel.png)

**To update the MS Excel,**

- Go to **File > Account** and click on **Update options**

![check MS Excel updates](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Check-MS-Excel-updates-1024x539.png)

- Then click ‘**Update’**

![Download MS Excel updates](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Install-MS-Excel-Updates-1024x539.png)

- MS Excel will start downloading the latest updates and then apply it, which might fix this Excel error

![Apply MS Excel updates](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/09/Applying-updates-to-Excel.png)

Still, Excel stuck on processing file at 0%? That means the Excel file you’re trying to open is severely corrupted. Thus, as mentioned earlier, use **Stellar Repair for Excel** software to repair corrupt or damaged Excel (XLS/XLSX) files and restore everything to a new Excel file. With the help of some best-in-class repair algorithms, this software enables you to fix problems within Excel files and recover tables, charts, cell comments, images, formulae, sorts, and filters. It is compatible with MS Excel 2019, 2016, 2013, 2010, 2007, and 2003.

## Conclusion

Hopefully, one of the above-mentioned solutions has helped you overcome the “Excel stuck at Opening file 0%” error and Excel hangs on opening file issues. Also, you are able to access your MS Excel worksheet now. If you face any problems with your Excel workbooks in future, remember to get to the root of the issue first. Also, inculcate the habit of backing up your critical files regularly (if possible) and keep products like **[Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)** in mind to save the day, when nothing else works.


## How to Repair Multiple Excel Files by Using Stellar

With Stellar Repair for Excel, it is quite easy and simple to repair multiple MS Excel (XLS and XLSX) files that are damaged. This is because the software has a self-explanatory interface and hence is a Do-it-yourself software. Nonetheless, when using this software to repair multiple Excel files, you would have to add all of the files into the software by following a few pre-defined steps. Follow the steps mentioned below:

- Launch **[Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)** software.
- Under Home menu, click Select file

![Select file option](https://www.stellarinfo.com/blog/wp-content/uploads/2019/08/select-file-option.jpg)

- Click **Browse** and select corrupt Excel files. Select the checkbox to repair multiple files.

![Search file](https://www.stellarinfo.com/blog/wp-content/uploads/2019/08/22-search-file.png)

- Click Repair
- The software provides the preview facility. You can check the it on left pane.

![Preview of file](https://www.stellarinfo.com/blog/wp-content/uploads/2019/08/4-preview.png)

- Save the repired filr ether **Default location** or **Select New Folder** radio button.

![select destination](https://www.stellarinfo.com/blog/wp-content/uploads/2019/08/6-save-file.jpg)

Stellar Repair for Excel Stellar Repair for Excel is the best choice for repairing corrupt or damaged Excel (.XLS/.XLSX) files. This Excel recovery software restores everything from corrupt file to a new blank Excel file.

[Learn More ![red arrow](https://www.stellarinfo.com/image/catalog/blacktheme/data-recovery-standard/red-arrow.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)


## Recover Excel Files from Virus-Infected Pen Drives for Free

**Summary:** Imagine you lost your important Excel file on which you had been working since the morning and in the next moment you realized that the file was not saved and you just lost hours of work. Wondering how to deal with this situation? Read this blog to know how Stellar free data recovery software can help you.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

From making annual reports to business growth representation figures, excel is a commonly used program for organizing data, creating pivot tables, charts etc. People from all walks of life, know the importance of Excel and the part it plays. Although it is a common file, there is a probability that you may accidentally delete excel files while working or are unable to access it due to unexpected errors. In addition, one of the major issues users face is to recover excel files from a virus infected pen drive.

Pen drives have made it possible to store and carry our important files such as excel, word document, photos, videos, etc. with us day in and day out. They just fit perfectly in our pockets and are compatible with almost every device; hence, they are widely used for transferring data from one system to another. But what if your pen drive is infected by a virus and due to it you end up losing your excel files, how will you recover your excel files for free?

A user reported that his pen drive got virus-infected and to remove the virus from it, he ran an antivirus program which removed the virus but also deleted excel files stored on it.

When your pen drive is infected by a virus, the first thing you ought to do is stop using it, even not for removing virus as an antivirus utility may remove your files as well. Further, if you have a backup, then you can recover your excel files from it, else you can use these free data recovery methods to recover your excel files.

**1\. [Free File Recovery Software Approach](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)**

Stellar Windows Data Recovery – Free Edition is an easy to use tool to recover files from a virus-infected pen drive. The software is equipped with powerful utilities to recover lost and deleted files for free. Further, it supports a wide range of file systems and is efficient in recovering files such as Excel, emails, word files, photos, audio and video files.

Using **Stellar Windows Data Recovery – Free Edition**, you can recover your files from all storage devices for free. Here’s how the software works:

- From the website, [**download**](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/) Stellar Windows Data Recovery – Free Edition. Connect your pen drive to your system and launch the software
- On ‘**Select What to Recover**’ screen, select file types from the given option that you wish to recover. For instance, if you want to recover photos, then under **Multimedia Files**, select ‘**Photos**’ and click on ‘**Next**’

![Stellar](https://www.stellarinfo.com/blog/wp-content/uploads/2021/02/FDR1-2-1024x721.png)

- From ‘**Select Location**’ screen, select the connected pen drive and click ‘**Scan**’

![Stellar](https://www.stellarinfo.com/blog/wp-content/uploads/2021/02/FDR2-1-1024x717.png)

- The scanning process starts and once the process is complete, software lists all the recoverable files

![Stellar](https://www.stellarinfo.com/blog/wp-content/uploads/2021/02/FDR3-2-1024x714.png)

- Select the files from the list and click on ‘**Recover**’ to save the files

**2\. Restore Excel File from the Previous Version**

If excel files are deleted from your pen drive or from your system; then you can recover them from the previous version. This feature works when Windows Backup option is enabled, else, it will not work.

Follow these steps to recover excel files:

- Connect your pen drive to your system, go to This PC and navigate to the folder of excel files
- Select the folder, right-click on it and select ‘Restore previous versions’
- From the available version of excel files, select the required one and click on ‘Restore’

**3\. Use Command Line to Recover Excel Files**

The Command prompt should be your first choice to recover excel files from the virus-infected pen drive. Here’s how command prompt recovers your files:

- Connect your virus-infected pen drive to your system and then in the search box type ‘CMD’ and hit ‘Enter’
- In the command window, type in attrib –h-r-s /s/ drive letter:\\\*.\*”, for example, “attrib -h -r -s /s /d G:\\\*.\*” and hit ‘Enter’

![attrib command](https://www.stellarinfo.com/blog/wp-content/uploads/2017/10/attrib-command.png)

- Windows starts repairing the virus-infected pen drive and once the process is complete, you can access your pen drive and recover excel files.

Even after following the above-mentioned steps you’re unable to recover your excel files, then try a Home approach i.e. a data recovery tool.

**To Sum Up**

It is always a good idea to create a backup of important files since no one can anticipate what might go wrong. The scenario presented in the blog paints a clear picture of how you can recover your Microsoft excel files for free from a virus-infected pen drive. For quick and better results, you can always go with Stellar Windows Data Recovery – Free Edition.


## Simple ways to Open Corrupt Excel file Without any Backup

**Summary:** The blog describes simple ways to open corrupt Excel file without any backup. It explains some manual workarounds that you can try to open the file. Also, it mentions about an Excel file repair tool that can quickly fix the corrupt file and recover data from it.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

Do you have an Excel file that does not open because of corruption issue? And every time you try to open it, an error message ‘the file is corrupt and cannot be opened’ pops-up?

![Excel file is corrupt and cannot be opened message](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/05/Excel-file-corruption-message-300x139.png)

Excel File Corruption Message

Also, you don’t have a healthy backup of the Excel file to restore the data? If so, you can try repairing the corrupt file by using a few simple yet effective manual workarounds mentioned below.

## **How to Open a Corrupt Excel File without Backup?**

Following are some manual methods that can help you open a corrupt Excel file:

### **Method 1: Repair Corrupt Excel File**

When attempting to open a corrupt file, Excel automatically starts ‘File Recovery’ mode to repair the file. But, if the recovery mode doesn’t start, try Microsoft Excel’s built-in ‘Open and Repair’ feature to manually repair the file.

To use this feature, perform the following steps:

**Step 1:** Open a **Blank workbook** in Excel, and then click **File > Open**.

**Step 2:** In the **Open** window, browse and select the corrupt file.

**Step 3:** Click the arrow that is beside the **Open** tab, and select **Open and Repair**.

![Open a blank workbook in Excel, navigate to File > Open, choose the corrupt file, and, in the Open window, click the arrow beside the Open tab, selecting Open and Repair for file recovery.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/05/Open-and-repair.png)

Open and Repair Option

**Step 4:** Implement one of the following:

- Click the **Repair** button. (This is to recover as much data as possible.)
- Click the **Extract Data** button. (This is to recover values and formulas from the Excel file if the repair process fails to recover the entire data.)

![Initiate file recovery by selecting the Repair tab, and if necessary, retrieve values and formulas using the Extract Data tab in Excel.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2018/04/repair-excel-file-1-768x158.jpg)

Excel Built-in Repair Options

If using [Open and Repair does not work](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/), move to the next method.

### **Method 2: Disable the Protected View Feature**

Some Excel users have reported that turning off the ‘protected view’ feature in Excel helped them open the corrupt file. You can also try to disable this feature and open the file. To do so, follow these steps:

**Step 1:** Open a blank Excel file, click on **File** > **Options**.

**Step 2:** In the **Excel Options** window, select **Trust Center**, and then click **Trust Center Settings**.

![In the Trust Center tab, click on Trust Center Settings...](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/05/Excel-trust-center-settings.png)

Excel Trust Center Settings

**Step 3:** Click **OK.**

Now check if you can open the corrupt file. If not, try implementing the next method.

### **Method 3: Look For Automatically Recovered Excel File**

If you have Excel’s AutoRecover feature enabled, you’ll have access to a copy of the **Excel file corrupted** or lost due to application crash, power outage, or accidental deletion.

**The ‘AutoRecover’** feature saves Excel worksheets at a temporary location after a certain time interval. It saves the worksheets automatically and is turned on by default to reduce the chance of data loss.

Check if you can **[recover corrupted Excel file](https://support.microsoft.com/en-us/office/repair-a-corrupted-workbook-153a45f4-6cab-44b1-93ca-801ddcd4ea53)** by following these steps:

**Step 1:** In Excel, open a **Blank workbook**.

**Step 2:** Go to **File** and click **Options**.

![Open a new Excel workbook, then access additional settings by navigating to File and selecting Options.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/08/Select-options-in-Excel-2013.jpg)

Figure 5 – Excel Options

**Step 3:** In the **Excel Options** dialog box, click **Save**, and then copy the ‘AutoRecover file location’.

![Copy the 'AutoRecover file location' for configuration or backup purposes.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2020/05/Autorecover-excel-file.png)

Excel Options Window

**Step 4:** Open File Explorer window and paste the copied AutoRecover file location, and press **Enter**.

**Step 5:** A list of saved Excel files will be displayed. Choose the file you want to recover.


_**TIP:** Use Excel’s AutoBackup feature to reduce chances of data loss, by saving a previous version of your spreadsheet automatically._

## **Use an Excel File Repair Software**

If the above manual methods fail, repair the **corrupt Excel file** by using a third-party software, such as Stellar Repair for Excel**.** The software helps repair Excel (XLS and XLSX) files easily and effectively.

[![Free Download for windows](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/01/Free-download-for-windows-1.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/)

**Read this: [How to repair corrupt Excel file using Stellar Repair for Excel?](https://www.stellarinfo.com/support/kb/index.php/article/repair-corrupt-excel-file)**

Some key features of Excel Repair software are as follows:

- Fixes all errors in the MS Excel file.
- Repairs multiple damaged Excel files in a go.
- Recovers chart, chart sheet, table, cell comment, image, formula, and sort & filter.
- Preserves properties and cell formatting of Excel worksheets.
- Previews recoverable Excel file data before saving.
- Recovers all data components from the corrupt files and saves them in a new blank Excel file.
- Compatible with Excel 2019, 2016, 2013, 2010, 2007, and lower versions.

## Conclusion

You can try the workarounds discussed in the blog to open a corrupt Excel file without a backup. Disabling the protected view feature can help you open the file. If the issue persists then try repairing the corrupted Excel file using the Open and Repair utility. Although, it may not be able to fix a severely corrupted workbook. In such a case you can use [Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/). It is an advanced tool that can help you repair a corrupted Excel file with 100% integrity.




## Filter Not Working Error in Excel [Fix 2024]

**Summary:** The filter is not working issue in Excel can occur due to several reasons, like blank rows, hidden rows, merged cells, corrupted data, etc. In this post, we will mention the reasons why the filter is not working correctly in Excel and several fixes to resolve the issue. We will also mention an advanced Excel repair tool to repair the Excel file if corruption in file is the cause of the issue.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

You can use the Filter function in Excel to filter data in large-sized Excel files quickly. While using Excel filters, sometimes, you face a situation where the filter is disabled or may fail to function properly.

![Filter Option Disabled](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/filter-option-disabled-1024x112.jpg)

The Excel filter usually fails to work if you have not selected the complete and correct range of data. Let’s learn more about the “Sort and Filter not working in Excel” issue and look at the possible methods to fix it.

## **Why the Filter is not Working in Excel?**

You can face the “filter is not working” issue if you are applying the filter on a protected worksheet or trying to find the data from a hidden row. Besides this, there could be many other reasons contributing to this issue, such as:

- The data you are trying to filter is in merged cells.
- The Excel file automatically selected the data up to the first empty cell, excluding the remaining rows.
- Grouped sheets in Excel file.
- Blank row in the Excel sheet.
- You are trying to apply a filter on an invalid data range.
- The workbooks in which you’re facing the filter issues are corrupted.
- You are specifying incorrect criteria in the filter columns.

## **Solutions to Resolve the Filter is not Working Issue in Excel**

There might be two scenarios: the Excel filter option is disabled/grayed out or the filters fail to function properly. You can follow the given troubleshooting solutions to resolve the issue based on the scenario you’re facing.

## **Scenario 1 – Filter Option is Disabled or Grayed Out**

### **Method 1: Check and Un-group the Worksheet**

When you apply filters to a single sheet in a grouped set, Excel disables the filter option in other sheets within the group. You can check the grouped sheets and try ungrouping them to enable the filter option. Here’s how to do so:

- In the Excel file, go to the **Group** section.

![Excel file navigation: Accessing the Group section
](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/go-to-group-section-1024x114.jpg)

- Right-click on the **Ungroup Sheets.**

Alternatively, you can press the Shift + Alt + Left keys to ungroup the sheets.

### **Method 2: Unprotect Worksheet**

The “disabled Excel filter” issue can also occur if your worksheet is protected. You can unprotect the worksheet to enable the filter option. To do so, go to the **Review** tab and then select **Unprotect Sheet.**

![Excel file: Navigating to Group section, resolving 'disabled Excel filter' issue with worksheet protection, unprotecting sheet from Review tab for filter activation.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/go-to-review-and-select-unprotect-sheet-1024x115.jpg)

### **Method 3: Check and Uninstall Excel Add-ins**

Sometimes, the Excel filter gets disabled due to faulty or corrupted Excel add-ins. You can run the Excel in Safe mode to check whether the issue has occurred due to add-ins. To do this, type excel /safe in the Run window and click **OK.**

![Troubleshooting disabled Excel filter caused by add-ins: Running Excel in Safe mode with 'excel /safe' in Run window](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/type-excel-safe-command.jpg)

In safe mode, if you see the filter option, it indicates some problematic Excel add-ins were causing the issue. In such a case, you can check and uninstall the faulty Excel add-ins to fix the issue.

## **Scenario 2 – Filter is not Working**

### **Method 1: Try Clearing Filters**

Sometimes, the Excel filter fails to work correctly if some filters from the previous sessions are still active. In such a case, you can clear the applied filters. Follow the below steps:

- In Excel file, click Sort & Filter option.
- Select clear.

![Excel: Clicking 'Sort & Filter' and selecting 'Clear' option.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/click-clear-option.jpg)

### **Method 2: Select Entire Data**

The filter not working issue in Excel can occur when the range selected for filtering is incomplete or incorrect. You need to make sure that you’ve selected the entire data range in Excel. You can use the Ctrl+A keys to select the entire content in the worksheet.

### **Method 3: Check and Delete Blank Cells from the Table’s Columns**

When you apply a filter to the data, Excel expects data to be in a continuous range. Excel filters do not consider the blank cells, thereby resulting in incorrect functioning of the filter. To resolve this issue, check and delete all blank cells. In case your Excel file is too large to delete the blank cells, then you can add a “Serial number” row as an alternative. Adding serial number row creates a data continuity, thus helping in fixing the filter-related issue.

### **Method 4: Unhide Hidden Rows and Columns**

Hidden rows or columns in worksheets can also affect the filter functionality. You can check and unhide rows/columns to troubleshoot the issue. Here is how to do so:

- In the affected Excel file, go to Home.
- Click on **Format > Hide & Unhide**.

![Excel file: Navigating to Home, accessing Format > Hide & Unhide.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/click-format-select-hide-or-unhide-option-1024x228.jpg)

- Click **Unhide Rows** or **Unhide Columns** (as required).

![Selective unhiding in Excel: 'Unhide Rows' or 'Unhide Columns' as needed.](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/10/click-unhide-rows-unhide-columns.jpg)

### **Method 5: Unmerge Cells**

You can experience the filter in Excel is not working issue if you are using the filter to extract data from merged cells. Ensure to unmerge the “merged cells” before applying a filter in Excel. Follow the below steps to unmerge the merged cells in Excel:

- Navigate to the **Home** option.
- In the toolbar, select the **Merge & Center** option.
- Click **Unmerge Cells.**

### **Method 6: Repair the Workbook**

Sometimes, the **Filter Not Working in Excel** issue can occur due to inconsistencies in file structure. If these issues occurred due to corruption in the worksheet, you can repair it using the Open and Repair tool. It is an in-built tool in Excel that is used to repair corrupted Excel files. Here are the steps to use this tool:

- In the Excel application, navigate to the **File** option.
- Click **Open** and then click **Browse** to choose the Excel file.
- In the **Open** dialog box, click the problematic Excel file.
- Click the arrow next to the **Open** option and select **Open and Repair.**
- Click **Repair** to recover as much data as possible.
- The application prompts a message after the repair process is complete. Click **Close**.

In most cases, the Open and Repair tool can easily fix corruption issues in the Excel file. However, for any reason, if the [open and repair tool doesn’t work](https://www.stellarinfo.com/blog/ms-excel-open-and-repair-option-is-not-working/) you can consider repairing the file using a professional Excel Repair tool. Stellar Repair for Excel is one such advanced and secure tool to repair Excel files. With this tool’s powerful scanning capabilities, you can repair highly corrupted Excel files and recover all their objects with complete integrity. The tool is compatible with all Windows editions, including the latest Windows 11.

## **Closure**

Several reasons are associated with the **filter not working issue in Excel**. The filter option may not work as expected if you have not selected the complete and correct range of data or for many other reasons. You can follow the troubleshooting methods discussed above to fix the issue. If the filter fails to work due to corruption in the workbook, then try [Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/). It is an advanced tool that can even repair severely damaged files. It also helps to recover all the data from corrupted files without changing the original formatting. You can check the tool’s functionality by downloading its demo version. It allows you to preview all the repairable objects in the corrupted Excel file.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>




