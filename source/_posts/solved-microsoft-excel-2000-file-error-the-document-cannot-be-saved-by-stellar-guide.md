---
title: Solved Microsoft Excel 2000 File Error The document cannot be saved
date: 2024-05-20T10:20:29.819Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2000 File Error The document cannot be saved
keywords: repair excel,repair excel 2013,repair excel 2000,repair .xlsm
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

Many users have reported encountering the error “Subscript out of range” (runtime error 9) when using VBA code in Excel. The error often occurs when the object you are referring to in a code is not available, deleted, or not defined earlier. Sometimes, it occurs if you have declared an array in code but forgot to specify the DIM or ReDIM statement to define the length of array.

## **Causes of VBA Runtime Error 9: Subscript Out Of Range**

The error ‘Subscript out of range’ in Excel can occur due to several reasons, such as:

- Object you are trying to use in the VBA code is not defined earlier or is deleted.
- Entered a wrong declaration syntax of the array.
- Wrong spelling of the variable name.
- Referenced a wrong array element.
- Entered incorrect name of the worksheet you are trying to refer.
- Worksheet you trying to call in the code is not available.
- Specified an invalid element.
- Not specified the number of elements in an array.
- Workbook in which you trying to use VBA is corrupted.

## **Methods to Fix Excel VBA Error ‘Subscript out of Range’**

Following are some workarounds you can try to fix the runtime error 9 in Excel.

### **Method 1: Check the Name of Worksheet in the Code**

Sometimes, Excel throws the runtime error 9: Subscript out of range if the name of the worksheet is not defined correctly in the code. For example – When trying to copy content from one Excel sheet (emp) to another sheet (emp2) via VBA code, you have mistakenly mentioned wrong name of the worksheet (see the below code).

```
Private Sub CommandButton1_Click()
Worksheets("emp").Range("A1:E5").Select
Selection.Copy
Worksheets("emp3").Activate
Worksheets("emp3").Range("A1:E5").Select
ActiveSheet.Paste
Application.CutCopyMode = False
End Sub
```

![VBA Error Subscript Out Of Range-When Incorrect Name](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/VBA-error-subscript-out-of-range-when-incorrect-name.jpg)

When you run the above code, the Excel will throw the Subscript out of range error.

So, check the name of the worksheet and correct it. Here are the steps:

- Go to the **Design** tab in the **Developer** section.
- Double-click on the **Command** button.
- Check and modify the worksheet name (e.g. from “emp” to “emp2”).

![Modified Code From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/modified-code-from-emp-to-emp2.jpg)

- Now run the code.
- The content in ‘emp’ worksheet will be copied to ‘emp2’ (see below).

![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

![Runtime Error 9 When Not Declared Array](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/run-time-error-9-when-not-declared-array.jpg)

To fix this, specify the array variable:

```
Sub FillArray()
Dim curExpense(364) As Currency
Dim intI As Integer
For intI = 0 to 364
curExpense(intI) = 20
Next
End Sub
```

### **Method 3: Change Macro Security Settings**

The Runtime error 9: Subscript out of range can also occur if there is an issue with the macros or macros are disabled in the Macro Security Settings. In such a case, you can check and change the macro settings. Follow these steps:

- Open your Microsoft Excel.
- Navigate to **File > Options > Trust Center**.
- Under **Trust Center**, select **Trust Center Settings**.
- Click **Macro Settings**, select **Enable all macros**, and then click **OK**.

![Macro Settings In Trust Center](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/macro-settings-in-trust-center.jpg)

### **Method 4: Repair your Excel File**

The name or format of the Excel file or name of the objects may get changed due to corruption in the file. When the objects are not identified in a VBA code, you may encounter the Subscript out of range error. You can use the Open and Repair utility in Excel to repair the corrupted file. To use this utility, follow these steps:

- In your MS Excel, click **File > Open**.
- Browse to the location where the affected file is stored.
- In the **Open** dialog box, select the corrupted workbook.
- In the **Open** dropdown, click on **Open and Repair**.
- You will see a prompt asking you to repair the file or extract data from it.
- Click on the **Repair** option to extract the data as much as possible. If **Repair** button fails, then click **Extract** button to recover data without formulas and values.

If the “Open and Repair” utility fails to repair the corrupted/damaged macro-enabled Excel file, then try an advanced Excel repair tool, such as Stellar Repair for Excel. It can easily repair severely corrupted Excel workbook and recover all the items, including macros, cell comments, table, charts, etc. with 100% integrity. The tool is compatible with all versions of Microsoft Excel.

## **Conclusion**

You may experience the “Subscript out of range” error while using VBA in Excel. You can follow the workarounds discussed in this blog to fix the error. If the Excel file is corrupt, then you can use [Stellar Repair for Excel](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/) to repair the file. It’s a powerful software that can help fix all the issues that occur due to corruption in the Excel file. It helps to recover all the data from the corrupt Excel files (.xls, .xlsx, .xltm, .xltx, and .xlsm) without changing the original formatting. The tool supports Excel 2021, 2019, 2016, and older versions.




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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-v27-pro-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo V27 Pro Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-realme-10t-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-honor-90-gt-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Honor 90 GT on Windows?</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-vivo-s17e-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Vivo S17e on Mac</u></a></li>
<li><a href="https://techidaily.com/solved-photos-disappeared-from-iphone-15-plus-suddenly-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Photos Disappeared from iPhone 15 Plus Suddenly | Stellar</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-honor-100-pro-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Honor 100 Pro without backup.</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-xiaomi-redmi-k70-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Xiaomi Redmi K70</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-your-drivers-in-windows-11-and-10-by-drivereasy-guide/"><u>Use Device Manager to reinstall your drivers in Windows 11 & 10</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-6s-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 6s Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-x-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-honor-x7b-by-fonelab-android-recover-data/"><u>The way to get back lost data from Honor X7b</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-13-pro-max-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 13 Pro Max to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-nokia-g42-5g-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Nokia G42 5G without backup.</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-oneplus-ace-2-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-oppo-a38-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Oppo A38 on Mac</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-6-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oneplus-ace-2-pro-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset OnePlus Ace 2 Pro Without Password | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-oneplus-open-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your OnePlus Open</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-12-best-gif-editors-to-use-for-2024/"><u>Updated 12 Best GIF Editors to Use for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-s18-pro-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo S18 Pro Phone FRP Lock</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-merge-videos-without-watermarks-top-5-tools/"><u>Updated Merge Videos Without Watermarks Top 5 Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-itel-a60s-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Itel A60s Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-samsung-galaxy-a24-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Samsung Galaxy A24 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-infinix-note-30-vip-by-fonelab-android-recover-data/"><u>Recover lost data from Infinix Note 30 VIP</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-xs-max-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your iPhone XS Max</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-mac-video-editor-reviews-the-best-of/"><u>In 2024, Mac Video Editor Reviews The Best Of</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-xiaomi-14-pro-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Xiaomi 14 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-iphone-12-stuck-at-attempting-data-recovery-loop-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix iPhone 12 Stuck at attempting data recovery Loop | Stellar</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-the-top-free-12-gif-meme-maker-at-a-glance-for-2024/"><u>New The Top Free 12 GIF Meme Maker at a Glance for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Apple iPhone 7 | Dr.fone</u></a></li>
</ul></div>


