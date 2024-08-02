---
title: Solved Microsoft Excel 2007 File Error The document cannot be saved
date: 2024-08-01T17:20:05.345Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2007 File Error The document cannot be saved
keywords: repair excel 2010,repair excel 2019,repair excel,repair .csv
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

[![Free Download for Windows](https://www.stellarinfo.com/images/free-download-windows.png)](https://tools.techidaily.com/stellardata-recovery/repaire-for-excel/ "Free Download for Windows")

Many users have reported encountering the error “Subscript out of range” (runtime error 9) when using VBA code in Excel. The error often occurs when the object you are referring to in a code is not available, deleted, or not defined earlier. Sometimes, it occurs if you have declared an array in code but forgot to specify the DIM or ReDIM statement to define the length of array.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Method 3: Change Macro Security Settings**

The Runtime error 9: Subscript out of range can also occur if there is an issue with the macros or macros are disabled in the Macro Security Settings. In such a case, you can check and change the macro settings. Follow these steps:

- Open your Microsoft Excel.
- Navigate to **File > Options > Trust Center**.
- Under **Trust Center**, select **Trust Center Settings**.
- Click **Macro Settings**, select **Enable all macros**, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Macro Settings In Trust Center](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/macro-settings-in-trust-center.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-no-hassle-sending-tweeted-videos-to-whatsapp/"><u>[New] In 2024, No Hassle  Sending Tweeted Videos to WhatsApp</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-understanding-the-shift-navigating-posting-in-an-algorithm-world/"><u>[New] In 2024, Understanding the Shift  Navigating Posting in an Algorithm World</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unpacking-the-multifaceted-nature-of-wirecast-tools/"><u>[New] Unpacking the Multifaceted Nature of WireCast Tools</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-winter-wonderland-spins-and-jumps/"><u>[New] Winter Wonderland Spins and Jumps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-vidoetwitter-fetcher-gather-twitter-videos-effortlessly/"><u>[Updated] 2024 Approved  VidoeTwitter Fetcher  Gather Twitter Videos Effortlessly</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unveiling-the-secrets-of-instagrams-musical-emoji-usage/"><u>[Updated] In 2024, Unveiling the Secrets of Instagram's Musical Emoji Usage</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfectly-blending-iphones-multimedia/"><u>[Updated] Perfectly Blending iPhones' Multimedia</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-techniques-for-exceptional-audio-recording-without-a-mic/"><u>2024 Approved  Techniques for Exceptional Audio Recording without a Mic</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-list-of-superior-live-streaming-services/"><u>2024 Approved  The Ultimate List of Superior Live Streaming Services</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>4 Feasible Ways to Fake Location on Facebook For your Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-itel-s23plus-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Itel S23+? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-v30-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo V30</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comedic-content-coder/"><u>Comedic Content Coder</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-vivo-y100i-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-oppo-reno-10-proplus-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Oppo Reno 10 Pro+ 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-11-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 11 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-f5-pro-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco F5 Pro 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-s17e-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo S17e without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-infinix-zero-5g-2023-turbo-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Infinix Zero 5G 2023 Turbo Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-x-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone X Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-12r-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus 12R Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 To Other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-to-other-iphone-11-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 to other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-14-pro-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock iPhone 14 Pro Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-11-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 11 without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-11-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 11 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-10-sandbox-innovations-you-shouldnt-skip/"><u>In 2024, 10 Sandbox Innovations You Shouldn't Skip</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-tecno-spark-go-2023-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Tecno Spark Go (2023) FRP In 3 Different Ways</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-step-by-step-io-screen-capture-tutorial/"><u>In 2024, Step-by-Step IO Screen Capture Tutorial</u></a></li>
<li><a href="https://techidaily.com/is-your-samsung-galaxy-s23-fe-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Samsung Galaxy S23 FE working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-y78t-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Y78t</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-nubia-red-magic-9-proplus-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Nubia Red Magic 9 Pro+ on Mac</u></a></li>
<li><a href="https://techidaily.com/repair-office-2013-files-word-excel-and-powerpointon-windows-by-stellar-guide/"><u>Repair Office 2013 Files (Word, Excel and PowerPoint)on Windows</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-oppo-a38-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Oppo A38 on Mac</u></a></li>
<li><a href="https://techidaily.com/samsung-data-retrieval-tool-restore-lost-data-from-samsung-galaxy-s23-tactical-edition-by-fonelab-android-recover-data/"><u>Samsung Data Retrieval tool – restore lost data from Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a54-5g-cant-play-avchd-mts-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Samsung Galaxy A54 5G can’t play AVCHD .mts video</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-xiaomi-redmi-a2plus-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Xiaomi Redmi A2+</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-oppo-find-x6-pro-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Oppo Find X6 Pro</u></a></li>
<li><a href="https://techidaily.com/some-mp4-wont-play-on-my-razr-40-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Razr 40</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-infinix-zero-5g-2023-turbo-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-itel-p40-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Itel P40 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-samsung-galaxy-s23-tactical-edition-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-vivo-y100i-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Vivo Y100i? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-oppo-a18-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Oppo A18</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-honor-70-lite-5g-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Honor 70 Lite 5G.</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-honor-magic-5-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Honor Magic 5 Pro</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-honor-x7b-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Honor X7b</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-12-pro-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 12 Pro files after scanning? | Stellar</u></a></li>
</ul></div>
