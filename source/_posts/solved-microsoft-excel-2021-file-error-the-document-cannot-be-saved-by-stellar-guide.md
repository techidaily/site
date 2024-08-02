---
title: Solved Microsoft Excel 2021 File Error The document cannot be saved
date: 2024-08-01T17:20:14.134Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2021 File Error The document cannot be saved
keywords: repair .xlb,repair excel 2010,repair excel 2021
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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

## **Methods to Fix Excel VBA Error ‘Subscript out of Range’**

Following are some workarounds you can try to fix the runtime error 9 in Excel.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![Modified Code From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/modified-code-from-emp-to-emp2.jpg)

- Now run the code.
- The content in ‘emp’ worksheet will be copied to ‘emp2’ (see below).

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-charting-success-with-youtube-income-streams-for-2024/"><u>[New] Charting Success with YouTube Income Streams for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-essential-apps-to-extract-and-save-your-vimeo-videos-for-2024/"><u>[New] Essential Apps to Extract and Save Your Vimeo Videos for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/tream-away-the-leading-online-video-havens/"><u>[New] Stream Away  The Leading Online Video Havens</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-how-to-convert-twitter-videos-to-gifs/"><u>[Updated] 2024 Approved  How To Convert Twitter Videos To GIFS?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-exploring-the-top-hashtags-for-a-boost-on-ig/"><u>[Updated] Exploring the Top Hashtags for a Boost on IG</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-vivo-y100-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Vivo Y100 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-itel-a05s-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Itel A05s</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/advance-your-teaching-with-these-top-5-language-apps/"><u>Advance Your Teaching with These Top 5 Language Apps</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-xiaomi-redmi-a2-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-samsung-galaxy-s23-ultra-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Samsung Galaxy S23 Ultra Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exploring-the-financial-benefits-in-podcasting/"><u>Exploring the Financial Benefits in Podcasting</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-xs-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-realme-v30t-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Realme V30T Phone Screen?</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-honor-play-7t-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-t2-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-poco-c50-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Poco C50 Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-of-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-samsung-galaxy-s23-ultra-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Samsung Galaxy S23 Ultra Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-nord-3-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Nord 3 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-14-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 14 Pro Max Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-discreetly-see-fb-snapshots/"><u>In 2024, Discreetly See FB Snapshots</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-xs-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone XS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-office-2003-files-word-excel-and-powerpointon-windows-stellar-by-stellar-guide/"><u>Repair Office 2003 Files (Word, Excel and PowerPoint)on Windows | Stellar</u></a></li>
<li><a href="https://techidaily.com/sign-doc-file-online-add-signature-to-doc-file-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .doc file Online - Add Signature to .doc file for Free</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-narzo-n53-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Narzo N53</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggling-with-non-appearing-iphone-notifications-try-these-7-fixes-now/"><u>Struggling with Non-Appearing iPhone Notifications? Try These 7 Fixes Now!</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-infinix-note-30-pro-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Infinix Note 30 Pro</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-huawei-nova-y91-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Huawei Nova Y91 without backup.</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-edge-40-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Edge 40.</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-samsung-galaxy-a05s-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-y78-5g-by-fonelab-android-recover-music/"><u>Undelete lost music from Y78 5G</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-s23-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from S23</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-itel-s23plus-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Itel S23+ Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-vivo-y78-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Vivo Y78 5G | Dr.fone</u></a></li>
</ul></div>
