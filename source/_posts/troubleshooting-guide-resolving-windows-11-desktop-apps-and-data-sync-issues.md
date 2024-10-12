---
title: "Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues"
date: 2024-10-09T07:56:52.424Z
updated: 2024-10-11T19:54:00.545Z
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-from-novice-to-pro-expert-tips-for-spotifys-advertisers/"><u>[New] In 2024, From Novice to Pro Expert Tips for Spotify's Advertisers</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-strategies-for-maximizing-your-twitter-archive/"><u>[New] In 2024, Strategies for Maximizing Your Twitter Archive</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-navigating-sales-for-inexpensive-gopros-for-2024/"><u>[New] Navigating Sales for Inexpensive GoPros for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-profiling-excellence-a-guide-to-refined-youtube-summaries-for-2024/"><u>[Updated] Profiling Excellence A Guide to Refined YouTube Summaries for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-itel-p40plus-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-vivo-y100t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Vivo Y100t Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/defeating-everspace-2-pc-issues-a-comprehensive-guide-to-fixing-in-game-crashes/"><u>Defeating Everspace 2 PC Issues: A Comprehensive Guide to Fixing In-Game Crashes</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-zebra-gkseriesdriver-instantly-and-easy-peasy/"><u>Get Your Zebra GK_Series_Driver Instantly and Easy-Peasy</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-8-plus-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 8 Plus To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-12-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 12 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-step-up-your-content-game-top-30-video-plans/"><u>In 2024, Step Up Your Content Game Top 30 Video Plans</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-honor-play-7t-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Honor Play 7T Phone Pattern Lock</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-nubia-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Nubia on Windows</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-tecno-spark-20-proplus-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-infinix-note-30-vip-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Infinix Note 30 VIP.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

