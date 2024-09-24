---
title: "[SOLVED] Restore Windows Photo Viewer in Windows 10"
date: 2024-09-20T10:56:31.618Z
updated: 2024-09-24T10:27:29.707Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes [SOLVED] Restore Windows Photo Viewer in Windows 10
excerpt: This Article Describes [SOLVED] Restore Windows Photo Viewer in Windows 10
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-mycam-review-a-step-toward-future-proofing-your-videos-for-2024/"><u>[New] MyCam Review A Step Toward Future-Proofing Your Videos for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-iphone-light-balancing/"><u>[New] The Ultimate Guide to iPhone Light Balancing</u></a></li>
<li><a href="https://techidaily.com/1723808314537-solved-how-to-configure-vpn-on-android-quickly-and-easily/"><u>[SOLVED] How to Configure VPN on Android | Quickly & Easily</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-clockwise-conundrum-video-undo-for-iphone-users/"><u>[Updated] Clockwise Conundrum Video Undo for iPhone Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/device-unlock-infinix-smart-8-hd-by-drfone-android-unlock-android-unlock/"><u>Device unlock Infinix Smart 8 HD</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/guide-to-offline-viewing-downloading-videos-from-youtube-on-your-2017-ipad-pro-with-ios-11/"><u>Guide to Offline Viewing: Downloading Videos From YouTube on Your 2017 iPad Pro with iOS 11</u></a></li>
<li><a href="https://techidaily.com/1723808240127-how-to-change-system-language-on-windows-10-easy-steps/"><u>How to Change System Language on Windows 10? Easy Steps</u></a></li>
<li><a href="https://techidaily.com/1723807983333-mastering-the-basics-a-comprehensive-guide-to-starting-with-google-services-today/"><u>Mastering the Basics: A Comprehensive Guide to Starting with Google Services Today</u></a></li>
<li><a href="https://extra-tips.techidaily.com/professional-pathway-setting-up-wm6/"><u>Professional Pathway Setting Up WM6</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-oneplus-nord-ce-3-lite-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your OnePlus Nord CE 3 Lite 5G Screen | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808024449-speed-hacks-supercharge-minecraft-gameplay/"><u>Speed Hacks - Supercharge Minecraft Gameplay</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-motorola-moto-e13-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unveiling-high-definition-the-essence-of-4k/"><u>Unveiling High Definition: The Essence of 4K</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

