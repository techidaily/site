---
title: Resolving Windows 10 Installation Issue - Fix Error Code 80 #
date: 2024-10-04T22:04:03.613Z
updated: 2024-10-11T22:39:03.740Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Resolving Windows 10 Installation Issue - Fix Error Code 80 #
excerpt: This Article Describes Resolving Windows 10 Installation Issue - Fix Error Code 80 #
thumbnail: https://thmb.techidaily.com/f051850e231be7d8e7141a137d6f961668fd1698700240c7348f6738ce5b4e95.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://screen-recording.techidaily.com/new-high-quality-live-streaming-games-via-obs/"><u>[New] High-Quality Live Streaming Games via OBS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-master-the-art-of-streamlined-screen-recordings-on-mac/"><u>[New] In 2024, Master the Art of Streamlined Screen Recordings on Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-loop-creating-impactful-content-for-instagram/"><u>[Updated] 2024 Approved Mastering the Art of Loop Creating Impactful Content for Instagram</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-strategies-for-improved-zoom-visuals-via-filters/"><u>[Updated] 2024 Approved Strategies for Improved Zoom Visuals via Filters</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-picks-for-integrating-frame-elements-with-images/"><u>[Updated] Top Picks for Integrating Frame Elements with Images</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-webcam-wonders-your-macbook-video-journey/"><u>2024 Approved Webcam Wonders Your MacBook Video Journey</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/all-purpose-capture-software-azs-app-critiques/"><u>All-Purpose Capture Software - AZ's App Critiques</u></a></li>
<li><a href="https://data-wizards.techidaily.com/damians-journey-fixing-ms-sql-systems-right/"><u>Damian's Journey - Fixing MS SQL Systems Right</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-xs-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone XS Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-samsung-galaxy-m34-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Samsung Galaxy M34 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-vivo-y36-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-12-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Apple iPhone 12 Pro Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-nord-n30-se-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Nord N30 SE Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-comprehensive-methods-for-adding-sound-to-modernized-avi-videos/"><u>New Comprehensive Methods for Adding Sound to Modernized AVI Videos</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quickly-install-your-corsair-void-pro-drivers-with-our-step-by-step-tutorial/"><u>Quickly Install Your Corsair Void Pro Drivers with Our Step-by-Step Tutorial!</u></a></li>
<li><a href="https://techidaily.com/sony-xperia-10-v-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Sony Xperia 10 V won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-samsung-galaxy-s24-by-fonelab-android-recover-music/"><u>The way to get back lost music from Samsung Galaxy S24</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-tecno-spark-go-2023-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Tecno Spark Go (2023) Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/v-purse-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>V Purse support - Turn Off Screen Lock.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

