---
title: Solved Microsoft Excel 2016 File Error The document cannot be saved
date: 2024-05-20T10:20:29.903Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2016 File Error The document cannot be saved
keywords: repair excel 2013,repair excel 2019,repair excel 2003,repair excel 2000,repair .csv
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
<li><a href="https://techidaily.com/things-you-dont-know-about-oneplus-nord-ce-3-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About OnePlus Nord CE 3 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-vivo-t2x-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Vivo T2x 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-poco-x6-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Poco X6 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-mini-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 mini to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-infinix-zero-30-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Infinix Zero 30 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-infinix-note-30i-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Infinix Note 30i Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-motorola-moto-g-5g-2023-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Motorola Moto G 5G (2023)</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-vivo-y77t-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Vivo Y77t without backup.</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-hardware-drivers-in-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to update hardware drivers in Windows 11 & 10 & 7</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-samsung-galaxy-f04-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-lava-yuva-3-pro-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Lava Yuva 3 Pro</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oneplus-ace-2-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset OnePlus Ace 2 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/why-can-t-i-play-mp4-files-on-my-galaxy-s24-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Why can’t I play MP4 files on my Galaxy S24?</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-go-2023-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark Go (2023) without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-c65-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from C65</u></a></li>
<li><a href="https://techidaily.com/sign-a-pdf-v20-document-with-digital-signature-software-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Sign a PDF v2.0 document with digital signature software</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-oppo-find-x6-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Oppo Find X6 on Mac?</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-redmi-k70e-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Redmi K70E</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-xs-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone XS without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-itel-s23-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Itel S23</u></a></li>
<li><a href="https://techidaily.com/update-hardware-drivers-with-device-manager-on-windows-1110-by-drivereasy-guide/"><u>Update hardware drivers with Device Manager on Windows 11/10</u></a></li>
<li><a href="https://techidaily.com/sign-word-2007-online-with-digisigner-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2007 Online with DigiSigner</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-realme-narzo-n53-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-magic-5-lite-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor Magic 5 Lite Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-tecno-phantom-v-flip-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Tecno Phantom V Flip</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-12-mini-to-an-older-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 12 mini to an Older iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-lava-blaze-2-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Lava Blaze 2</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-beyond-the-basics-secrets-for-tiktok-live-studio-success-for-2024/"><u>Updated Beyond the Basics Secrets for TikTok Live Studio Success for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-nokia-c22-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-ubuntu-video-editors-top-picks-for-creators/"><u>Updated Free Ubuntu Video Editors Top Picks for Creators</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-realme-gt-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-asus-rog-phone-7-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Asus ROG Phone 7 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-poco-m6-pro-5g-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Poco M6 Pro 5G Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-7-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 7, Apples New iPhone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-tecno-spark-10-pro-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Tecno Spark 10 Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-iphone-se-2020-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your iPhone SE (2020) Apple ID and Apple Pay</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your Apple iPhone SE (2020)?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-oppo-reno-11-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Oppo Reno 11 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-tecno-camon-20-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Tecno Camon 20 Phones with/without a PC</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-v27e-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo V27e Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-lava-blaze-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Lava Blaze Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-g22-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Nokia G22 Phone Without Password?</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Samsung Galaxy F54 5G? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Realme 12 5G? | Dr.fone</u></a></li>
</ul></div>


