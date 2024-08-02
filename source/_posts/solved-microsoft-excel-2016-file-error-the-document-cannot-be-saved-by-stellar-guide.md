---
title: Solved Microsoft Excel 2016 File Error The document cannot be saved
date: 2024-08-01T17:20:10.337Z
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

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![Content Copied From emp to emp2](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-2658c43/www.stellarinfo.com/blog/wp-content/uploads/2023/04/content-copied-from-emp-to-emp2.jpg)

### Method 2: Check the Range of the Array

The VBA error “Subscript out of range” also occurs if you have declared an array in a code but didn’t specify the number of elements. For example – If you have declared an array and forgot to declare the array variable with elements, you will get the error (see below):

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-harmonious-hub-choosing-the-best-free-apps-for-your-youtube-music-streams-for-2024/"><u>[New] Harmonious Hub  Choosing the Best Free Apps for Your YouTube Music Streams for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-logging-live-video-conversations-for-2024/"><u>[New] Logging Live Video Conversations for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-voice-from-images-turning-instagram-into-mp3s/"><u>[Updated] 2024 Approved  Voice From Images  Turning Instagram Into MP3s</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-cutting-edge-techniques-pushing-boundaries-in-youtube-cinematography/"><u>[Updated] In 2024, Cutting Edge Techniques  Pushing Boundaries in YouTube Cinematography</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-unlock-the-full-potential-of-facebook-the-best-5-chrome-extensions/"><u>[Updated] In 2024, Unlock the Full Potential of Facebook  The Best 5 Chrome Extensions</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-innovative-design-crafting-youtubes-efficient-subscribe-page-for-2024/"><u>[Updated] Innovative Design  Crafting YouTube's Efficient Subscribe Page for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-increase-photographic-imagery-keeping-details-intact/"><u>2024 Approved  Increase Photographic Imagery, Keeping Details Intact</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-samsung-galaxy-a15-4g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Samsung Galaxy A15 4G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-xiaomi-redmi-13c-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-a78-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo A78 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-motorola-edge-40-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Motorola Edge 40 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/effortless-pubg-vocal-modifications/"><u>Effortless PUBG Vocal Modifications</u></a></li>
<li><a href="https://network-issues.techidaily.com/ensure-static-screens-in-windows-11-settings/"><u>Ensure Static Screens in Windows 11 Settings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-honor-by-drfone-android/"><u>Full Guide to Unlock Your Honor</u></a></li>
<li><a href="https://techidaily.com/hard-reset-poco-c55-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Poco C55 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-vivo-s18-pro-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Vivo S18 Pro in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-14-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 14 without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oneplus-ace-2-pro-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset OnePlus Ace 2 Pro in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y78t-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y78t in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-tecno-spark-20-proplus-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Tecno Spark 20 Pro+ Quickly? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oneplus-12r-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset OnePlus 12R Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-ios-beta-version-on-apple-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-oppo-a59-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Oppo A59 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-samsung-galaxy-a05s-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-system-of-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-6s-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Apple iPhone 6s Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-11-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus 11 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-7-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 7 To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-2022-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE (2022) To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-8-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 8 Plus without iTunes? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-convenient-method-to-design-original-shorts-thumbnails/"><u>In 2024, Convenient Method to Design Original Shorts Thumbnails</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-echo-enthusiasts-emporium-obtain-and-review-sound-files/"><u>In 2024, Echo Enthusiasts Emporium  Obtain & Review Sound Files</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-8-plus-location-by-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 8 Plus Location by Number | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-key-steps-to-find-your-youtube-content-creation-hub/"><u>In 2024, Key Steps to Find Your YouTube Content Creation Hub</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-seamless-audio-transfer-youtube-videos-)-mp3-macos-2023/"><u>In 2024, Seamless Audio Transfer  YouTube Videos > MP3, MacOS 2023</u></a></li>
<li><a href="https://extra-tips.techidaily.com/master-techniques-for-longevity-in-gopro-batteries/"><u>Master Techniques for Longevity in GoPro Batteries</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-v27e-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo V27e Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-poco-x5-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Poco X5</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-oppo-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Oppo</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/teacher-tools-best-screen-capture-options/"><u>Teacher Tools  Best Screen Capture Options</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-lava-blaze-curve-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Lava Blaze Curve 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-motorola-moto-g14-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Motorola Moto G14 Reset Code | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-s17-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo S17 Location | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unveiling-the-secrets-to-stellar-igtv-footage-capture/"><u>Unveiling the Secrets to Stellar IGTV Footage Capture</u></a></li>
<li><a href="https://techidaily.com/xiaomi-data-retrieval-tool-restore-lost-data-from-xiaomi-by-fonelab-android-recover-data/"><u>Xiaomi Data Retrieval tool – restore lost data from Xiaomi</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-vivo-y100-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Vivo Y100 5G | Dr.fone</u></a></li>
</ul></div>
