---
title: Resolving Windows 10 Installation Issue - Fix Error Code 80 #
date: 2024-08-18T03:46:07.051Z
updated: 2024-08-19T03:46:07.051Z
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
<li><a href="https://youtube-sure.techidaily.com/0-easy-youtube-video-ideas-everyone-can-make-it-for-2024/"><u>[New] 10 Easy YouTube Video Ideas Everyone Can Make It for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-capture-the-best-with-top-windows-11-hd-webcams-for-2024/"><u>[New] Capture the Best with Top Windows 11 HD Webcams for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-manual-for-crafting-youtube-playlists/"><u>[New] In 2024, How-To Manual for Crafting YouTube Playlists</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-key-tips-for-optimal-live-sports-content-capture/"><u>[New] In 2024, Key Tips for Optimal LIVE Sports Content Capture</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-seamless-integration-turning-audio-into-written-format-in-ms-word/"><u>[New] Seamless Integration  Turning Audio Into Written Format in MS Word</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/iral-vortex-keywords-that-propel-you-into-social-media-spotlight/"><u>[New] Viral Vortex  Keywords that Propel You Into Social Media Spotlight</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-choreographing-a-memorable-tiktok-fade-out/"><u>2024 Approved  Choreographing a Memorable TikTok Fade-Out</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-microsofts-hololens-adventure-a-3d-visionary-experience/"><u>2024 Approved  Microsoft’s HoloLens Adventure – A 3D Visionary Experience</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-leading-platforms-for-seamless-mp3-refinement-and-cutting/"><u>2024 Approved Leading Platforms for Seamless MP3 Refinement and Cutting</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-samsung-galaxy-a25-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Samsung Galaxy A25 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-tecno-spark-go-2023-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Tecno Spark Go (2023) Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-x90s-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo X90S Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-oneplus-open-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oppo-find-x6-pro-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Oppo Find X6 Pro Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-12-pro-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-pro-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 Pro iOS System? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-samsung-galaxy-m14-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Samsung Galaxy M14 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-20-proplus-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark 20 Pro+ without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oppo-a1-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Oppo A1 5G phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-pro-max-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Pro Max To Other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6s-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6s to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-reno-11-pro-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo Reno 11 Pro 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-11-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 11 Pro Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Honor X9a? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-honor-x8b-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Honor X8b? Fixed | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-13-pro-max-data-from-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 13 Pro Max Data From iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-pro-max-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Pro Max Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a34-5g-can-t-play-mp4-video-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Samsung Galaxy A34 5G can't play MP4 video files</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/shake-it-off-best-phones-for-unshakable-visual-experience/"><u>Shake It Off! Best Phones for Unshakable Visual Experience</u></a></li>
<li><a href="https://techidaily.com/sign-excel-online-add-signature-to-excel-for-free-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>Sign Excel Online - Add Signature to Excel for Free</u></a></li>
<li><a href="https://techidaily.com/solved-mac-doesnt-recognize-my-iphone-xs-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Mac Doesnt Recognize my iPhone XS | Stellar</u></a></li>
<li><a href="https://techidaily.com/some-ways-to-unlock-iphone-14-screen-lock-by-drfone-ios-unlock-ios-unlock/"><u>Some ways to unlock iPhone 14 screen lock</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/stylish-profiles-easy-downloads/"><u>Stylish Profiles, Easy Downloads</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-power-of-pause-effectively-responding-to-comments/"><u>The Power of Pause  Effectively Responding to Comments</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-nubia-red-magic-8s-pro-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-honor-90-pro-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Honor 90 Pro</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-honor-magic-vs-2-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from Honor Magic Vs 2</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-realme-narzo-n53-by-fonelab-android-recover-data/"><u>Undelete lost data from Realme Narzo N53</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-xiaomi-by-fonelab-android-recover-data/"><u>Undelete lost data from Xiaomi</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-blade-a73-5g-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Blade A73 5G.</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-15-pro-screen-lock-without-password-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 15 Pro screen lock without password</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-realme-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Realme on Mac?</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-poco-f5-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Poco F5 Pro 5G Hard Reset | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->