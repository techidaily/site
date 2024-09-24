---
title: "Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues"
date: 2024-09-18T19:36:26.788Z
updated: 2024-09-23T17:54:25.354Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues"
excerpt: "This Article Describes Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues"
thumbnail: https://thmb.techidaily.com/3c089195526935c85a4cb3e6dde5d5ebf9d1e09e8343d1ce6aea5ca384c30ca3.jpg
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
<li><a href="https://some-approaches.techidaily.com/new-ultimate-microphone-selection-for-high-res-video-shooting/"><u>[New] Ultimate Microphone Selection for High-Res Video Shooting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-ideal-subscription-list-10-youtube-analysts-picks/"><u>[Updated] Ideal Subscription List 10 YouTube Analysts' Picks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-networking-galore-places-for-youtube-affiliate-marketing/"><u>[Updated] Networking Galore Places for YouTube Affiliate Marketing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-revisiting-reruns-the-classic-goofy-movie/"><u>[Updated] Revisiting Reruns The Classic 'Goofy Movie'</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-minecrafts-oriental-elegance-6-top-ideas/"><u>2024 Approved Minecraft's Oriental Elegance 6 Top Ideas</u></a></li>
<li><a href="https://techidaily.com/how-to-set-up-and-utilize-the-locate-this-pc-tool-in-windows-11/"><u>How to Set Up and Utilize the Locate This PC Tool in Windows 11</u></a></li>
<li><a href="https://techidaily.com/huge-savings-alert-transition-to-windows-11-pro-with-an-unbeatable-88-reduction-offer-today-only/"><u>Huge Savings Alert! Transition to Windows 11 Pro with an Unbeatable 88% Reduction Offer – Today Only!</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-meme-magic-online/"><u>In 2024, Meme Magic Online</u></a></li>
<li><a href="https://techidaily.com/latest-ipv6-related-flaw-affecting-personal-computers-an-overview/"><u>Latest IPv6-Related Flaw Affecting Personal Computers: An Overview</u></a></li>
<li><a href="https://techidaily.com/master-your-macs-menu-bar-discover-the-ultimate-free-app-solution/"><u>Master Your Mac's Menu Bar: Discover the Ultimate Free App Solution</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-frame-rates-for-best-slow-motion-effects/"><u>Mastering Frame Rates for Best Slow Motion Effects</u></a></li>
<li><a href="https://techidaily.com/mastering-mean-the-ultimate-guide-to-calculating-averages-in-ms-excel/"><u>Mastering Mean: The Ultimate Guide to Calculating Averages in MS Excel</u></a></li>
<li><a href="https://techidaily.com/mastering-ubuntu-linux-effective-techniques-for-initiating-the-terminal-interface/"><u>Mastering Ubuntu Linux: Effective Techniques for Initiating the Terminal Interface</u></a></li>
<li><a href="https://techidaily.com/maximize-windows-11-efficiency-effective-debloating-techniques/"><u>Maximize Windows 11 Efficiency: Effective Debloating Techniques</u></a></li>
<li><a href="https://techidaily.com/native-installation-of-google-chrome-available-on-windows-pcs-with-arm-processors/"><u>Native Installation of Google Chrome Available on Windows PCs with ARM Processors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Tecno Spark 20 Pro? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-oneplus-11r-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent OnePlus 11R Fingerprint Not Working Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

