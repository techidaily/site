---
title: Solved Microsoft Excel 2021 File Error The document cannot be saved
date: 2024-05-20T10:20:29.910Z
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
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-motorola-g24-power-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-ace-3-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Ace 3 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-poco-x6-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Poco X6 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-11-pro-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 11 Pro To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-xiaomi-redmi-13c-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Xiaomi Redmi 13C</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-x90s-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo X90S in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-nokia-g22-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Nokia G22 Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-oneplus-nord-3-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-samsung-galaxy-z-fold-5-by-fonelab-android-recover-data/"><u>Undelete lost data from Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-vivo-v29-pro-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Vivo V29 Pro Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-oneplus-nord-3-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-vivo-t2-pro-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Vivo T2 Pro 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-12-pro-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 12 Pro without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-tecno-spark-go-2023-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Tecno Spark Go (2023) Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-vivo-y17s-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Vivo Y17s.</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-xiaomi-redmi-a2-by-fonelab-android-recover-music/"><u>The way to get back lost music from Xiaomi Redmi A2</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xs-max-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XS Max To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-13-pro-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 13 Pro Data From iOS iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-vivo-y27-4g-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Vivo Y27 4G</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-realme-c55-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Realme C55 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-xiaomi-redmi-13c-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Xiaomi Redmi 13C 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/tecno-data-recovery-recover-lost-data-from-tecno-spark-20-proplus-by-fonelab-android-recover-data/"><u>Tecno Data Recovery – recover lost data from Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-hot-40-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-reno-8t-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo Reno 8T If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-motorola-moto-g14-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-xiaomi-redmi-a2-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Xiaomi Redmi A2</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-y77t-by-fonelab-android-recover-music/"><u>The way to get back lost music from Y77t</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-f04-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy F04 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-vivo-t2x-5g-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Vivo T2x 5G.</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-y78plus-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-2022-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE (2022) without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-honor-play-7t-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Honor Play 7T in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-zte-nubia-z60-ultra-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For ZTE Nubia Z60 Ultra</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-meizu-21-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Meizu 21 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-on-apple-iphone-14-plus-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code On Apple iPhone 14 Plus in the Best Ways</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-motorola-moto-e13-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Motorola Moto E13 Location by Number | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-cropping-video-in-vlc-step-by-step/"><u>New 2024 Approved Cropping Video in VLC Step by Step</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-vivo-y100-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from Vivo Y100.</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-meizu-21-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-s18-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Vivo S18 Phone with Broken Screen</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-in-2024-how-to-auto-translate-youtube-videos-into-different-languages/"><u>Updated In 2024, How To Auto Translate YouTube Videos Into Different Languages</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/lava-yuva-2-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Lava Yuva 2 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-oppo-a78-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Oppo A78 Phones</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-nokia-130-music-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-on-iphone-15-pro-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue On iPhone 15 Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-max-withwithout-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 Pro Max with/without SIM Card</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-a25-5g-has-native-hevc-support-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Does Samsung Galaxy A25 5G has native HEVC support?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-tecno-phantom-v-fold-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Tecno Phantom V Fold</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-motorola-edge-40-pro-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Motorola Edge 40 Pro</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-easy-guide-how-to-make-talking-head-videos/"><u>In 2024, Easy Guide How To Make Talking Head Videos</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-vivo-v27e-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Vivo V27e FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://iphone-location.techidaily.com/3-smart-and-simple-ways-to-change-home-address-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>3 Smart and Simple Ways to Change Home Address on Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-export-imovie/"><u>Updated How to Export iMovie?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-poco-c55-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Poco C55? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://review-topics.techidaily.com/reinstall-your-hardware-drivers-with-device-manager-in-windows-1110-by-drivereasy-guide/"><u>Reinstall your hardware drivers with Device Manager in Windows 11/10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-apple-iphone-xs-max-by-drfone-ios/"><u>How To Factory Unlock Your Telstra Apple iPhone XS Max</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-iphone-15-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your iPhone 15 for Free</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Apple iPhone 13 Pro | Dr.fone</u></a></li>
</ul></div>


