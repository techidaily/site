---
title: Solved Microsoft Excel 2000 File Error The document cannot be saved
date: 2024-08-01T17:20:01.655Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

Many users have reported encountering the error “Subscript out of range” (runtime error 9) when using VBA code in Excel. The error often occurs when the object you are referring to in a code is not available, deleted, or not defined earlier. Sometimes, it occurs if you have declared an array in code but forgot to specify the DIM or ReDIM statement to define the length of array.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
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
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
### **Method 3: Change Macro Security Settings**

The Runtime error 9: Subscript out of range can also occur if there is an issue with the macros or macros are disabled in the Macro Security Settings. In such a case, you can check and change the macro settings. Follow these steps:

- Open your Microsoft Excel.
- Navigate to **File > Options > Trust Center**.
- Under **Trust Center**, select **Trust Center Settings**.
- Click **Macro Settings**, select **Enable all macros**, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-precision-recording-a-stepwise-plan-for-pc-ios-macbooks/"><u>[New] 2024 Approved  Precision Recording  A Stepwise Plan for PC, iOS, MacBooks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-your-online-presence-audios-for-your-channel-for-2024/"><u>[New] Elevate Your Online Presence  Audios for Your Channel for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfect-pair-of-timers-ios-and-android-wedding-clock-essentials/"><u>[New] Perfect Pair of Timers  IOS & Android Wedding Clock Essentials</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-drama-to-film-shaping-realistic-dialogue/"><u>[Updated] From Drama to Film  Shaping Realistic Dialogue</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-best-matches-top-ten-gimbals-for-quality-shoots/"><u>2024 Approved  Best Matches  Top Ten Gimbals for Quality Shoots</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-game-masters-guide-to-4k-monitors/"><u>2024 Approved  Game Masters' Guide to 4K Monitors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mastering-video-trimming-for-maximum-instagram-impact-mac/"><u>2024 Approved  Mastering Video Trimming for Maximum Instagram Impact (Mac)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-x100-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo X100 Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-lava-yuva-3-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Lava Yuva 3 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-tecno-camon-20-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-itel-p55t-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Itel P55T Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-x50iplus-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-hot-40i-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-realme-c53-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Realme C53 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-14-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 14 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-12-mini-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 12 mini Data Permanently | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-infinix-smart-7-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Infinix Smart 7 Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-tecno-spark-go-2023-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Tecno Spark Go (2023) Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-honor-magic-6-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Honor Magic 6 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-vivo-s17t-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Vivo S17t Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-moto-g13-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Moto G13 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 To Other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-pro-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Pro To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-mini-to-androidios-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 mini to Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-pro-to-android-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Pro to Android? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xr-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone XR to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-7-plus-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 7 Plus without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-13-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 13 without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-enter-the-ispoofer-discord-server-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, How to enter the iSpoofer discord server On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-vivo-y27-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Vivo Y27 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top-7-converting-audio-to-text-tools/"><u>New Top 7 Converting Audio to Text Tools</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-vivo-v29-pro-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Vivo V29 Pro</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-galaxy-a05s-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Galaxy A05s</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-nokia-g310-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-c32-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from C32</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-v29-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo V29 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-huawei-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Huawei</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-realme-12plus-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-samsung-galaxy-m54-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-honor-x50i-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Honor X50i</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-google-pixel-fold-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Google Pixel Fold.</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-realme-note-50-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Realme Note 50.</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-oppo-by-fonelab-android-recover-data/"><u>Undelete lost data from Oppo</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-galaxy-m34-5g-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Galaxy M34 5G</u></a></li>
<li><a href="https://techidaily.com/vivo-y78-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Vivo Y78 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-11-pro-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 11 Pro files after scanning? | Stellar</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-11-pro-max-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 11 Pro Max files after scanning? | Stellar</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-6s-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 6s files after scanning? | Stellar</u></a></li>
</ul></div>
