---
title: "[SOLVED] Restore Windows Photo Viewer in Windows 10"
date: 2024-10-06T16:32:35.750Z
updated: 2024-10-12T05:18:08.527Z
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
<li><a href="https://techidaily.com/how-to-hard-reset-nokia-130-music-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Nokia 130 Music Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Android? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-lava-blaze-2-5g-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-nba-live-action-your-guide-to-15-effective-livestream-tips/"><u>In 2024, NBA Live Action Your Guide to 15 Effective Livestream Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unmatched-download-experience-with-our-top-tools-list/"><u>In 2024, Unmatched Download Experience with Our Top Tools List</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/pcs-gateway-to-the-past-selecting-top-5-ps1-game-emulators-for-2024/"><u>PC's Gateway to the Past - Selecting Top 5 PS1 Game Emulators for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-vivo-x-fold-2-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Vivo X Fold 2</u></a></li>
<li><a href="https://discover-guides.techidaily.com/top-14-windowszoftware-voor-diavorstbeeld-maaksters-nieuwe-trends-en-tipps/"><u>Top 14 Windowszoftware Voor Diavorstbeeld Maaksters : Nieuwe Trends en Tipps</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-motorola-moto-g23-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Motorola Moto G23 Hard Reset | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475">
  <img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

