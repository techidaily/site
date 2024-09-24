---
title: Solved Microsoft Excel 2016 File Error The document cannot be saved
date: 2024-09-23T06:56:48.861Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Methods to Fix Excel VBA Error ‘Subscript out of Range’**

Following are some workarounds you can try to fix the runtime error 9 in Excel.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-help.techidaily.com/new-harmonizing-tracks-in-youtube-music/"><u>[New] Harmonizing Tracks in YouTube Music</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-mastering-the-art-of-webp-conversion-to-jpeg/"><u>[New] In 2024, Mastering the Art of WebP Conversion to JPEG</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ultimate-guide-best-video-capture-tools-for-windows/"><u>[New] Ultimate Guide Best Video Capture Tools for Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-essential-guide-to-screen-capturing-on-hp-devices/"><u>2024 Approved Essential Guide to Screen Capturing on HP Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-realme-12plus-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-vivo-t2-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-vivo-v27-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-vivo-y27-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Vivo Y27 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/easy-in-getting-vrecorder-on-your-pc-for-2024/"><u>Easy In Getting VRecorder on Your PC for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevate-imagery-quality-achieve-ultra-hd-clarity-with-4k8k10k-conversion-powered-by-winxvideo-ai-technology/"><u>Elevate Imagery Quality: Achieve Ultra HD Clarity with 4K/8K/10K Conversion Powered by Winxvideo AI Technology</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-poco-f5-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-xiaomi-redmi-note-12-4g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-samsung-galaxy-s24-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Samsung Galaxy S24 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-xiaomi-13-ultra-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Xiaomi 13 Ultra Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-7-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 7 Plus without iTunes? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-effortlessly-gain-premium-quality-pictures-online/"><u>In 2024, How to Effortlessly Gain Premium Quality Pictures Online</u></a></li>
<li><a href="https://os-tips.techidaily.com/introducing-belkins-game-changing-magsafe-triple-port-charger-a-leap-forward-in-wireless-power-solutions/"><u>Introducing Belkin's Game-Changing MagSafe Triple Port Charger - A Leap Forward in Wireless Power Solutions</u></a></li>
<li><a href="https://techidaily.com/stellar-data-recovery-for-iphone-6-plus-failed-to-recognize-my-iphone-how-to-fix-it-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Stellar Data Recovery for iPhone 6 Plus failed to recognize my iPhone. How to fix it? | Stellar</u></a></li>
<li><a href="https://buynow-info.techidaily.com/tp-link-av2000-ethernet-over-power-review-fast-performance-with-average-design-quality/"><u>TP-Link AV2000 Ethernet Over Power Review: Fast Performance with Average Design Quality</u></a></li>
</ul></div>

