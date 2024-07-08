---
title: Solved Microsoft Excel 2010 File Error The document cannot be saved
date: 2024-05-20T10:20:29.879Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2010 File Error The document cannot be saved
keywords: repair .xlsx,repair excel 2010,repair excel 2021,repair excel
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
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-v29e-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of V29e on Mac</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-to-other-iphone-11-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 To Other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-honor-x9b-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Honor X9b | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-gionee-f3-pro-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Gionee F3 Pro</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-nubia-red-magic-8s-proplus-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-xiaomi-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Xiaomi fingerprint</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-blaze-2-pro-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Blaze 2 Pro on Windows</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-poco-x5-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Poco X5 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-poco-m6-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-of-apple-iphone-14-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of Apple iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-xs-ios-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone XS iOS? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-honor-90-gt-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Honor 90 GT</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-nokia-c22-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Nokia C22 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-pop-8-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Pop 8.</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-play-40c-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-pova-6-pro-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Pova 6 Pro 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-samsung-galaxy-a54-5g-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Samsung Galaxy A54 5G Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-to-do-if-iphone-14-plus-is-not-listed-when-i-run-the-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What to do if iPhone 14 Plus is not listed when I run the software? | Stellar</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2022-to-other-iphone-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2022) to other iPhone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-asus-rog-phone-8-pro-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Asus ROG Phone 8 Pro in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-sony-xperia-1-v-by-fonelab-android-recover-data/"><u>The way to get back lost data from Sony Xperia 1 V</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-12-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 12 Pro Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-infinix-hot-40i-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Infinix Hot 40i without backup.</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-11-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 11 To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-xiaomi-civi-3-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Xiaomi Civi 3 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-vivo-y100i-power-5g-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Vivo Y100i Power 5G?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-11-pro-to-android-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 11 Pro to Android? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-itel-p40plus-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-13-mini-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 13 mini Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-14-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 14 Pro Max without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/solved-mac-doesnt-recognize-my-iphone-13-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Mac Doesnt Recognize my iPhone 13 | Stellar</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-honor-v-purse-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-xiaomi-14-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Xiaomi 14 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-itel-p55-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Itel P55</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-xr-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone XR</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-wondering-about-how-to-easily-create-a-slideshow-on-your-iphone-well-take-note-of-some-of-the-finest-apps-to-turn-your-vision-into-reality-for-2024/"><u>New Wondering About How to Easily Create a Slideshow on Your iPhone? Well, Take Note of some of the Finest Apps to Turn Your Vision Into Reality for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-create-slide-masking-effect-introfilmora/"><u>2024 Approved Create Slide Masking Effect Intro【Filmora】</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-tecno-pova-6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-apple-iphone-11-pro-max-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 11 Pro Max Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-honor-x50-gt-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-have-you-ever-wanted-to-speed-up-or-slow-down-a-video-maybe-it-was-too-long-or-you-wanted-to-draw-out-an-exciting-part-of-the-video-without-having-t/"><u>Updated Have You Ever Wanted to Speed up or Slow Down a Video? Maybe It Was Too Long, or You Wanted to Draw Out an Exciting Part of the Video without Having to Watch the Boring Parts</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-vivo-v27-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Vivo V27 Phone Now with These Tips</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-samsung-galaxy-a24-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Samsung Galaxy A24 Location on Twitter | Dr.fone</u></a></li>
</ul></div>


