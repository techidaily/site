---
title: Solved Microsoft Excel 2003 File Error The document cannot be saved
date: 2024-08-01T17:20:02.677Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2003 File Error The document cannot be saved
keywords: repair excel 2003,repair .xltx,repair excel 2019,repair excel 2021,repair excel 2007,repair .xltm
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## **Methods to Fix Excel VBA Error ‘Subscript out of Range’**

Following are some workarounds you can try to fix the runtime error 9 in Excel.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![Modified Code From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/modified-code-from-emp-to-emp2.jpg)

- Now run the code.
- The content in ‘emp’ worksheet will be copied to ‘emp2’ (see below).

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-unveiling-the-secrets-of-video-captioning-in-vimeo/"><u>[New] 2024 Approved  Unveiling the Secrets of Video Captioning in Vimeo</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-cartoonhub-complete-guide-and-assessment-2024/"><u>[New] CartoonHub Complete Guide & Assessment 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premier-ios-choices-for-superior-video-experience/"><u>[New] Premier iOS Choices for Superior Video Experience</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-smooth-steps-top-20-chill-out-country-hits-for-grooving-tiktok/"><u>[New] Smooth Steps  Top 20 Chill-Out Country Hits for Grooving (TikTok)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-elusive-footage-the-systematic-guide-to-youtube-secrets/"><u>[Updated] Unlocking Elusive Footage  The Systematic Guide to YouTube Secrets</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi Phone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-from-iphone-12-pro-max-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock From iPhone 12 Pro Max Online</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-videos-with-precision-leveraging-storyremix-in-windows-11/"><u>Crafting Videos with Precision  Leveraging StoryRemix in Windows 11</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-oppo-f23-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Oppo F23 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-oneplus-ace-3-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-nokia-c02-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Nokia C02 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-magic-6-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor Magic 6 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-motorola-moto-g-5g-2023-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Motorola Moto G 5G (2023) Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-xiaomi-redmi-13c-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Xiaomi Redmi 13C 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-ios-beta-version-on-apple-iphone-14-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on Apple iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-ios-beta-version-on-apple-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-15-pro-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 15 Pro Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-mini-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 mini to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-plus-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Plus to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-on-your-iphone-se-2020-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled On your iPhone SE (2020)? How to Fix</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-infinix-hot-40i-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Infinix Hot 40i</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-xiaomi-redmi-13c-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Xiaomi Redmi 13C</u></a></li>
<li><a href="https://techidaily.com/some-mp4-won-t-play-on-my-galaxy-s23-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Galaxy S23</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-realme-c33-2023-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-asus-rog-phone-7-ultimate-by-fonelab-android-recover-data/"><u>The way to get back lost data from Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-htc-u23-pro-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from HTC U23 Pro</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-motorola-moto-g24-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Motorola Moto G24 Reset Code | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/top-notch-chromebook-snapshot-tool-for-2024/"><u>Top-Notch Chromebook Snapshot Tool for 2024</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-galaxy-s23-ultra-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Galaxy S23 Ultra</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-itel-a05s-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Itel A05s</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-spark-20c-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Spark 20C password or pattern lock</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-nokia-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Nokia on Windows?</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-vivo-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Vivo on Windows?</u></a></li>
</ul></div>
