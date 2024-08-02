---
title: Solved Microsoft Excel 2019 File Error The document cannot be saved
date: 2024-08-01T17:20:11.482Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2019 File Error The document cannot be saved
keywords: repair .xlb,repair excel 2010,repair excel 2021,repair .xltx,repair .csv,repair excel 2000
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
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
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<li><a href="https://facebook-videos.techidaily.com/new-augmenting-visual-appeal-implementing-black-bar-and-box-on-fb-for-2024/"><u>[New] Augmenting Visual Appeal  Implementing Black Bar & Box on FB for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-advice-on-how-to-remove-backgrounds/"><u>[New] Expert Advice on How to Remove Backgrounds</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leading-12-free-video-trimming-apps-for-android-users/"><u>[New] Leading 12 Free Video Trimming Apps for Android Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-10-best-mp4-players-for-music-enthusiasts/"><u>[Updated] 10 Best MP4 Players for Music Enthusiasts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-duel-masters-switch-edition-the-best-of-ten/"><u>[Updated] 2024 Approved  Duel Masters  Switch Edition - The Best of Ten</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-build-your-brand-memes-with-kinemaster/"><u>2024 Approved  Build Your Brand  Memes with KineMaster</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-key-conduct-criteria-in-the-youtube-sphere/"><u>2024 Approved  Key Conduct Criteria in the YouTube Sphere</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-the-pinnacle-of-iphone-photography-finding-ultimate-angles/"><u>2024 Approved  The Pinnacle of iPhone Photography  Finding Ultimate Angles</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-y77t-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo Y77t</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-vivo-y77t-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-honor-magic-6-lite-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Honor Magic 6 Lite Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-samsung-galaxy-a05-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Samsung Galaxy A05 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-honor-x7b-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Honor X7b Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-tecno-spark-20-pro-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Tecno Spark 20 Pro Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-lava-blaze-2-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-tecno-pop-8-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-reno-8t-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo Reno 8T Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y77t-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y77t If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-lava-yuva-3-pro-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Lava Yuva 3 Pro Safely | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-motorola-moto-e13-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Motorola Moto E13 Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-vivo-y36i-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Vivo Y36i? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-infinix-gt-10-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Infinix GT 10 Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-11-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus 11 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-20-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark 20 Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-xiaomi-13t-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Xiaomi 13T phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-itel-p55t-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Itel P55T to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-best-5-chrome-os-clipping-utilities-ranked/"><u>In 2024, Best 5 Chrome OS Clipping Utilities, Ranked</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-oppo-a18-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Oppo A18 Phone without PIN</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-lava-storm-5g-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Lava Storm 5G online without jailbreak</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Poco X6 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-zte-nubia-flip-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your ZTE Nubia Flip 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/making-the-most-out-of-your-films-b-roll/"><u>Making the Most Out of Your Film's B-Roll</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-top-locations-for-accessing-cat-themed-mp3-sounds-for-2024/"><u>New Top Locations for Accessing Cat-Themed MP3 Sounds for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimized-asus-usb-bt400-for-windows-107-users/"><u>Optimized ASUS USB-BT400 for Windows 10/7 Users</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-asus-rog-phone-7-ultimate-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Asus ROG Phone 7 Ultimate on Mac</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-asus-rog-phone-7-ultimate-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://facebook.techidaily.com/safe-online-interactions-which-sites/"><u>Safe Online Interactions: Which Sites?</u></a></li>
<li><a href="https://techidaily.com/sign-docx-file-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .docx file Online for Free</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-samsung-galaxy-s24-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-realme-narzo-60-5g-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Realme Narzo 60 5G without backup.</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-itel-p40-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Itel P40</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-redmi-13c-5g-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Redmi 13C 5G</u></a></li>
<li><a href="https://techidaily.com/unlock-locked-iphone-7-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>Unlock locked iPhone 7 without Passcode</u></a></li>
<li><a href="https://techidaily.com/vivo-x90s-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Vivo X90S Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-k70-pro-messages-recovery-recover-deleted-messages-from-xiaomi-redmi-k70-pro-by-fonelab-android-recover-messages/"><u>Xiaomi Redmi K70 Pro Messages Recovery - Recover Deleted Messages from Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-xiaomi-redmi-13c-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Xiaomi Redmi 13C | Dr.fone</u></a></li>
</ul></div>
