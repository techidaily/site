---
title: "How to Fix the Windows 10 Update Error Code 0X80248007: A Step-by-Step Guide"
date: 2024-09-23T06:06:27.763Z
updated: 2024-09-24T02:36:22.734Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes How to Fix the Windows 10 Update Error Code 0X80248007: A Step-by-Step Guide"
excerpt: "This Article Describes How to Fix the Windows 10 Update Error Code 0X80248007: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/4661968631eef5e118e434f91c87fd30d0c4ad99eff2c33463bfeb19637f99d3.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-step-by-step-selection-of-top-10-no-cost-conference-software/"><u>[New] 2024 Approved Step-By-Step Selection of Top 10 No-Cost Conference Software</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-best-student-friendly-history-vid-hubs-1-10/"><u>[Updated] In 2024, Best Student-Friendly History Vid Hubs (#1-10)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/budget-savvy-shoppers-best-cameras/"><u>Budget-Savvy Shoppers' Best Cameras</u></a></li>
<li><a href="https://techidaily.com/effective-solutions-to-overcome-access-denied-during-windows-updates-error-0x80070005/"><u>Effective Solutions to Overcome 'Access Denied' During Windows Updates (Error: 0X80070005)</u></a></li>
<li><a href="https://techidaily.com/expert-techniques-to-prevent-any-and-all-windows-10-updates-from-happening/"><u>Expert Techniques to Prevent Any and All Windows 10 Updates From Happening</u></a></li>
<li><a href="https://techidaily.com/fix-taskbar-not-working-issue-in-windows-10-step-by-step/"><u>Fix Taskbar Not Working Issue in Windows 10 (Step by Step)</u></a></li>
<li><a href="https://techidaily.com/fix-your-wiggling-desktop-icons-with-these-fast-straightforward-tips/"><u>Fix Your Wiggling Desktop Icons with These Fast, Straightforward Tips!</u></a></li>
<li><a href="https://techidaily.com/fix-ps4-wont-connect-to-wifi-2021-100-works/"><u>Fix: PS4 Won’t Connect to WiFi 2021 [100% Works]</u></a></li>
<li><a href="https://techidaily.com/fixing-frame-rate-and-loot-drop-issues-in-diablo-iv-on-pc-solutions/"><u>Fixing Frame Rate & Loot Drop Issues in Diablo IV on PC - Solutions!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-honor-magic-5-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Honor Magic 5 Pro Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-check-crash-logs-on-windows/"><u>How to Check Crash Logs on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-connect-printer-to-computer-windows-11/"><u>How to Connect Printer to Computer Windows 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-efficiently-removing-youtube-channels-a-device-centric-approach/"><u>In 2024, Efficiently Removing Youtube Channels A Device-Centric Approach</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-xiaomi-redmi-note-12t-pro-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Xiaomi Redmi Note 12T Pro Phone? Unlock It Now</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-ultimate-list-best-skype-audio-capture-tools-for-professionals-for-2024/"><u>The Ultimate List Best Skype Audio Capture Tools for Professionals for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-10-secrets-for-successful-youtube-music-reaction-videos/"><u>Top 10 Secrets for Successful YouTube Music Reaction Videos</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-unleash-your-inner-filmmaker-a-step-by-step-guide-to-professional-movie-making/"><u>Updated 2024 Approved Unleash Your Inner Filmmaker A Step-by-Step Guide to Professional Movie Making</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

