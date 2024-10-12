---
title: "Resolved: Complete Hard Drive Consumption on Task Manager with Windows 10"
date: 2024-10-09T05:06:36.980Z
updated: 2024-10-11T16:11:44.713Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Resolved: Complete Hard Drive Consumption on Task Manager with Windows 10"
excerpt: "This Article Describes Resolved: Complete Hard Drive Consumption on Task Manager with Windows 10"
thumbnail: https://thmb.techidaily.com/4d915015b14faa5b1fd5a4cf5496ee0a4d386e84bd18007683e60195b160e324.jpg
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
<li><a href="https://youtube-docs.techidaily.com/rinciples-of-crafting-compelling-youtube-introduction-vids-for-2024/"><u>[New] Principles of Crafting Compelling YouTube Introduction Vids for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-innovative-rhymes-dominating-tiktok-challenges/"><u>[Updated] In 2024, Innovative Rhymes Dominating TikTok Challenges</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-television-or-projector-unraveling-the-best-for-4k-viewing-pleasure/"><u>[Updated] Television or Projector? Unraveling the Best for 4K Viewing Pleasure</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-av1-vs-vp9-a-detailed-comparison/"><u>2024 Approved AV1 Vs. VP9 A Detailed Comparison</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-eye-shadow-and-lips-tutorials/"><u>2024 Approved Eye Shadow & Lips Tutorials</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-oppo-a56s-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-oppo-a78-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-itel-a60s-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Itel A60s? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Infinix Note 30 VIP? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-90-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor 90 Reset Code | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tricks-to-perfect-time-lapses-using-samsung-cameras/"><u>Tricks to Perfect Time-Lapses Using Samsung Cameras</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-fixing-compiling-shaders-issue-in-call-of-duty-black-ops-cold-war/"><u>Troubleshooting Guide: Fixing 'Compiling Shaders' Issue in Call of Duty: Black Ops Cold War</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-y36-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Y36</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-samsung-galaxy-f14-5g-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-samsung-galaxy-f34-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Samsung Galaxy F34 5G ?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

