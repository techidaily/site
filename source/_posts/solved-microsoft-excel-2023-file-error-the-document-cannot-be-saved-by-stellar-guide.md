---
title: Solved Microsoft Excel 2023 File Error The document cannot be saved
date: 2024-08-01T17:20:16.545Z
tags: 
  - repair
  - repair excel
  - fix excel
categories: 
  - apps
  - windows
description: This article describes Solved Microsoft Excel 2023 File Error The document cannot be saved
keywords: repair .xlsx,repair excel 2007,repair excel 2000,repair excel 2016
---

## \[Fixed\] Excel VBA Runtime Error 9: Subscript Out of Range

**Summary:** The runtime error 9 in Excel usually occurs when you use different objects in a code or the object you are trying to use is not defined. This post will discuss the reasons behind the Excel VBA error "Subscript out of Range” and the solutions to resolve the issue. It will also mention an Excel repair tool that can help fix the error if it occurs due to corruption in worksheet.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-quick-shot-guide-for-chromebook-users/"><u>[New] Quick Shot Guide for Chromebook Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-amplify-earnings-monetize-youtube-on-the-go-with-effective-techniques/"><u>[Updated] 2024 Approved  Amplify Earnings  Monetize YouTube on the Go with Effective Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-the-ultimate-guide-to-the-most-effective-pc-screen-capture-apps/"><u>[Updated] 2024 Approved  The Ultimate Guide to the Most Effective PC Screen Capture Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-easily-download-your-favorites-handpicked-tools-reviewed-for-2024/"><u>[Updated] Easily Download Your Favorites  Handpicked Tools Reviewed for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-craft-your-channels-moniker-youtube-naming-tools-and-tips/"><u>[Updated] In 2024, Craft Your Channel's Moniker  YouTube Naming Tools and Tips</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-mastering-youtube-permanently-stop-video-snips-complete-guide/"><u>2024 Approved  Mastering YouTube  Permanently Stop Video Snips [Complete Guide]</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-lava-blaze-2-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Lava Blaze 2 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-note-12-proplus-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi Note 12 Pro+ 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-x-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-tecno-spark-20c-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Tecno Spark 20C Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-xs-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone XS Data Permanently | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-6-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-recovery-mode-on-apple-iphone-13-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-spark-20-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Spark 20 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oppo-f23-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Oppo F23 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-samsung-galaxy-m14-4g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Samsung Galaxy M14 4G Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-2020-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE (2020) To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-8-plus-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 8 Plus to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-edge-40-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Edge 40 to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-swiftvideo-pro-accelerate-your-android-content/"><u>In 2024, SwiftVideo Pro  Accelerate Your Android Content</u></a></li>
<li><a href="https://techidaily.com/is-your-samsung-galaxy-s21-fe-5g-2023-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Samsung Galaxy S21 FE 5G (2023) working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pros-and-cons-of-inshot-is-it-the-ultimate-editor-in-2024/"><u>Pros and Cons of InShot  Is It the Ultimate Editor, In 2024</u></a></li>
<li><a href="https://techidaily.com/solved-photos-disappeared-from-iphone-15-suddenly-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Photos Disappeared from iPhone 15 Suddenly | Stellar</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-ace-screen-recorders-list-for-the-winning-setup/"><u>The Ace Screen Recorders List - For the Winning Setup</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-itel-s23-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Itel S23 without backup.</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-honor-v-purse-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Honor V Purse</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-honor-x8b-by-fonelab-android-recover-data/"><u>Undelete lost data from Honor X8b</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-7-plus-without-a-computer-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 7 Plus without a computer</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-realme-gt-5-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Realme GT 5 Pro</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-nokia-c02-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Nokia C02 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/xiaomi-mix-fold-3-can-t-play-avchd-mts-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Xiaomi Mix Fold 3 can’t play AVCHD .mts video</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/your-guide-to-flawless-images-on-android-our-selection-of-top-editors-for-2024/"><u>Your Guide to Flawless Images on Android  Our Selection of Top Editors for 2024</u></a></li>
</ul></div>
