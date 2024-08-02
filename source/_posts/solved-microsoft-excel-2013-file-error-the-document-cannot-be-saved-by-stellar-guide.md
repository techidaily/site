---
title: Solved Microsoft Excel 2013 File Error The document cannot be saved
date: 2024-08-01T17:20:09.113Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2013 File Error The document cannot be saved
keywords: repair excel 2021,repair excel,repair excel 2016,repair excel 2000,repair .csv
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### **Method 3: Change Macro Security Settings**

The Runtime error 9: Subscript out of range can also occur if there is an issue with the macros or macros are disabled in the Macro Security Settings. In such a case, you can check and change the macro settings. Follow these steps:

- Open your Microsoft Excel.
- Navigate to **File > Options > Trust Center**.
- Under **Trust Center**, select **Trust Center Settings**.
- Click **Macro Settings**, select **Enable all macros**, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-pinnacle-of-amusement-select-15-laughing-out-loud-channels/"><u>[New] 2024 Approved  The Pinnacle of Amusement  Select 15 Laughing-Out-Loud Channels</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-discover-the-top-10-igtv-editing-app-wonders-for-2024/"><u>[New] Discover the Top 10 IGTV Editing App Wonders for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-skype-recording-excellence-the-years-leading-tools-for-2024/"><u>[New] Skype Recording Excellence  The Year's Leading Tools for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-financial-face-off-comparing-dailymotion-and-youtube-profitability/"><u>[Updated] In 2024, Financial Face-Off  Comparing Dailymotion & YouTube Profitability</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-navigating-through-instagram-video-hiccups/"><u>[Updated] In 2024, Navigating Through Instagram Video Hiccups</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-add-chapters-to-a-youtube-video/"><u>2024 Approved  How To Add Chapters To A YouTube Video</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oppo-find-x6-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-14-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi 14 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-samsung-galaxy-f04-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Samsung Galaxy F04 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-poco-c51-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Poco C51 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-oppo-reno-11-pro-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Oppo Reno 11 Pro 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-itel-p55plus-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Itel P55+ Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-2020-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE (2020) without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-2022-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE (2022) without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-90-gt-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor 90 GT If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-play-40c-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor Play 40C in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-itel-p40plus-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Itel P40+ without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-dfu-mode-on-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of DFU Mode on Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-moto-g73-5g-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from Moto G73 5G.</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-12-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-13-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 13 System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-se-2020-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone SE (2020) iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-se-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone SE iOS System? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-poco-c55-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Poco C55 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-realme-c55-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Realme C55 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oppo-a78-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Oppo A78 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6 To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-13-mini-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 13 mini Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-7-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-11-pro-max-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 11 Pro Max to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-14-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 14 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-6-methods-to-mirror-apple-iphone-13-to-your-windows-pc-drfone-by-drfone-ios/"><u>In 2024, 6 Methods to Mirror Apple iPhone 13 to your Windows PC | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-google-pixel-8-pro-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Google Pixel 8 Pro working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-mix-fold-3-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Mix Fold 3 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/no-more-walls-mondly-bridges-linguistic-gaps-in-ukraine/"><u>No More Walls: Mondly Bridges Linguistic Gaps in Ukraine</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-honor-x50-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Honor X50</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-nubia-z50s-pro-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Nubia Z50S Pro without backup.</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-v-purse-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on V Purse</u></a></li>
<li><a href="https://techidaily.com/unable-to-save-excel-workbook-issue-fix-2024-by-stellar-guide/"><u>Unable to Save Excel Workbook Issue Fix 2024</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-lava-yuva-2-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Lava Yuva 2.</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-y27s-by-fonelab-android-recover-music/"><u>Undelete lost music from Y27s</u></a></li>
<li><a href="https://techidaily.com/unlock-locked-iphone-11-pro-without-passcode-or-face-id-by-drfone-ios-unlock-ios-unlock/"><u>Unlock locked iPhone 11 Pro without Passcode or Face ID</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-drivers-with-windows-device-manager-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning drivers with Windows Device Manager on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-tecno-camon-20-premier-5g-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Tecno Camon 20 Premier 5G</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-honor-100-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Honor 100 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-samsung-galaxy-f15-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Samsung Galaxy F15 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/xiaomi-13-ultra-won-t-play-avchd-mts-files-by-aiseesoft-video-converter-play-mts-on-android/"><u>Xiaomi 13 Ultra won’t play AVCHD .mts files</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-note-12-4g-music-recovery-recover-deleted-music-from-xiaomi-redmi-note-12-4g-by-fonelab-android-recover-music/"><u>Xiaomi Redmi Note 12 4G Music Recovery - Recover Deleted Music from Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-nokia-xr21-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Nokia XR21 | Dr.fone</u></a></li>
</ul></div>
