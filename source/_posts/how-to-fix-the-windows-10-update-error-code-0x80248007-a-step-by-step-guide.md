---
title: "How to Fix the Windows 10 Update Error Code 0X80248007: A Step-by-Step Guide"
date: 2024-10-15T16:39:48.973Z
updated: 2024-10-18T03:27:27.386Z
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-eagle-essentials-best-laptop-options-for-video-editors-in-4k/"><u>[New] In 2024, Eagle Essentials Best Laptop Options for Video Editors in 4K</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-viral-visualization-top-story-filter-guide/"><u>[New] Viral Visualization Top Story Filter Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-digital-therapeutics-and-patient-engagement/"><u>[Updated] 2024 Approved Digital Therapeutics and Patient Engagement</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-non-competitive-front-row-fun-ranking-the-top-ten/"><u>[Updated] Non-Competitive Front Row Fun Ranking the Top Ten</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-unlock-new-dimensions-with-these-vr-videos-for-2024/"><u>[Updated] Unlock New Dimensions with These VR Videos for 2024</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-xiaomi-13t-pro-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-xiaomi-civi-3-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Xiaomi Civi 3 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-realme-gt-5-240w-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Realme GT 5 (240W) Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-plus-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 Plus without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-15-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-crafting-a-hit-solo-podcast-trendsetting-tips/"><u>In 2024, Crafting a Hit Solo Podcast Trendsetting Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jokesterjigsaw-toolkit/"><u>In 2024, JokesterJigsaw Toolkit</u></a></li>
<li><a href="https://techidaily.com/is-your-infinix-note-30-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Infinix Note 30 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rapid-launcher-loading/"><u>Mastering the Art of Rapid Launcher Loading</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/reimagining-business-through-chatgpt-and-whisper-apis-release/"><u>Reimagining Business Through ChatGPT & Whisper APIs' Release</u></a></li>
<li><a href="https://techidaily.com/remove-infinix-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Infinix unlock screen</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-sony-xperia-5-v-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Sony Xperia 5 V without backup.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

