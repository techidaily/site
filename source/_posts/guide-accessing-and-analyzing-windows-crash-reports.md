---
title: "Guide: Accessing and Analyzing Windows Crash Reports"
date: 2024-08-18T03:38:41.106Z
updated: 2024-08-19T03:38:41.106Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Guide: Accessing and Analyzing Windows Crash Reports"
excerpt: "This Article Describes Guide: Accessing and Analyzing Windows Crash Reports"
thumbnail: https://thmb.techidaily.com/71650fe6339aad7562a7ef4730d038972f077e65bec2cbda43e5ae4d18379e11.jpg
---

## WinSxS Folder: Clean Up and Save Space on Windows 11 Easily

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-online-photo-grid-creators-for-enhanced-clarity/"><u>[New] 2024 Approved  Top Online Photo Grid Creators for Enhanced Clarity</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-color-correction-best-practices-top-11/"><u>[New] The Art of Color Correction  Best Practices (Top 11)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-maximize-collaboration-via-zooms-share-feature/"><u>[Updated] In 2024, Maximize Collaboration via Zoom's Share Feature</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-unlocking-social-media-potential-stream-to-fb-via-obs/"><u>[Updated] In 2024, Unlocking Social Media Potential  Stream to FB via OBS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-impact-vectors-discover-the-best-10-websites/"><u>2024 Approved  High-Impact Vectors  Discover the Best 10 Websites</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-key-pillars-top-6-social-platforms-benefiting-businesses/"><u>2024 Approved  Key Pillars  Top 6 Social Platforms Benefiting Businesses</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-storage-space-used-for-daily-extended-videography/"><u>2024 Approved  Storage Space Used for Daily Extended Videography</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-lava-yuva-2-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Lava Yuva 2 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/artistic-defense-the-collective-suit-against-meta-and-openais-ai/"><u>Artistic Defense: The Collective Suit Against Meta & OpenAI's AI</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-tecno-spark-go-2024-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Tecno Spark Go (2024) Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-honor-play-8t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Honor Play 8T Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-free-up-apple-iphone-13-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up Apple iPhone 13 Space | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-motorola-moto-g13-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-google-pixel-fold-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Google Pixel Fold in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-moto-g-5g-2023-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola Moto G 5G (2023) in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-phantom-v-fold-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Phantom V Fold without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-se-2020-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-issues-of-apple-iphone-11-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System Issues of Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-samsung-galaxy-xcover-6-pro-tactical-edition-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Samsung Galaxy XCover 6 Pro Tactical Edition Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-honor-magic-5-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Honor Magic 5 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-pova-6-pro-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Pova 6 Pro 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-pro-max-to-other-iphone-12-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Pro Max To Other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6-plus-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6 Plus To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-plus-to-other-iphone-15-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Plus to other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-15-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 15 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-realme-11-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-elevate-your-expression-a-gallery-of-stunning-video-themes-for-tiktok/"><u>In 2024, Elevate Your Expression  A Gallery of Stunning Video Themes for TikTok</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-concept-to-creation-top-10-podcast-design-principles/"><u>In 2024, From Concept to Creation  Top 10 Podcast Design Principles</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-electronic-analysis-by-the-pros-at-toms-hardware-review/"><u>In-Depth Electronic Analysis by the Pros at Tom's Hardware Review</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-through-new-camera-settings-in-ios-11/"><u>Navigating Through New Camera Settings in iOS 11</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-honor-x50-gt-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Honor X50 GT</u></a></li>
<li><a href="https://techidaily.com/sign-xltm-files-online-for-free-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>Sign .xltm files Online for Free</u></a></li>
<li><a href="https://techidaily.com/sign-jpg-online-add-signature-to-jpg-for-free-by-ldigisigner-sign-a-jpg-sign-a-jpg/"><u>Sign JPG Online - Add Signature to JPG for Free</u></a></li>
<li><a href="https://techidaily.com/solved-excel-2013-spreadsheet-disappears-after-opening-stellar-by-stellar-guide/"><u>Solved Excel 2013 Spreadsheet Disappears after Opening | Stellar</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-itel-p55-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-xiaomi-redmi-k70-pro-by-fonelab-android-recover-data/"><u>The way to get back lost data from Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-tecno-pova-5-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Tecno Pova 5</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-motorola-edge-2023-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Motorola Edge 2023 Phone</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-100-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of 100 on Mac?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-vivo-v27-pro-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Vivo V27 Pro Phone Network-Ready</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->