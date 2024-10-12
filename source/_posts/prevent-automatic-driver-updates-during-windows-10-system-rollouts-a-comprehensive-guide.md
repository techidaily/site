---
title: "Prevent Automatic Driver Updates During Windows 10 System Rollouts: A Comprehensive Guide"
date: 2024-10-11T03:04:06.698Z
updated: 2024-10-11T20:30:54.544Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Prevent Automatic Driver Updates During Windows 10 System Rollouts: A Comprehensive Guide"
excerpt: "This Article Describes Prevent Automatic Driver Updates During Windows 10 System Rollouts: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/dec6d7b37184535a38bb760c8f68a296f6e3b58ddf3c516e8b89cc8c9c1d5757.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-streamline-your-slide-show-secrets-to-excellent-ppt-recording/"><u>[New] In 2024, Streamline Your Slide Show Secrets to Excellent PPT Recording</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamlined-audio-processing-in-windows-media-player/"><u>[New] Streamlined Audio Processing in Windows Media Player</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-videos-that-vibe-a-novices-roadmap-on-a-mac-and-youtube-for-2024/"><u>[Updated] Videos That Vibe A Novice's Roadmap on a Mac and YouTube for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-multiple-camera-editing-software-compare-manycam-alternatives/"><u>Best Multiple Camera Editing Software - Compare ManyCam Alternatives</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-enabled-user-experience-enhancement/"><u>Cookiebot-Enabled User Experience Enhancement</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-a38-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo A38 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-poco-f5-pro-5g-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Poco F5 Pro 5G without backup.</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/tutti-i-numeri-italiani-divisi-in-1000-esperienze/"><u>Tutti I Numeri Italiani Divisi in 1000 Esperienze</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-hardware-drivers-in-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to reinstall hardware drivers in Windows 11/10/7</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-hardware-drivers-on-windows-11-by-drivereasy-guide/"><u>Use Device Manager to update hardware drivers on Windows 11</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-galaxy-xcover-6-pro-tactical-edition-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Galaxy XCover 6 Pro Tactical Edition on Mac?</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-honor-x9b-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Honor X9b Hard Reset | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

