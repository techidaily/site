---
title: "Resolved: Complete Hard Drive Consumption on Task Manager with Windows 10"
date: 2024-08-18T03:42:33.419Z
updated: 2024-08-19T03:42:33.419Z
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-leading-apps-to-monitor-facebook-twitter-and-instagram-tags/"><u>[New] 2024 Approved  Leading Apps to Monitor Facebook, Twitter and Instagram Tags</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-improve-your-zoom-meet-by-sharpening-views/"><u>[New] Improve Your Zoom Meet by Sharpening Views</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-foremost-editing-tools-for-device-developers/"><u>[New] In 2024, Foremost Editing Tools for Device Developers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-websites-your-source-for-youtube-branding-collabs/"><u>[New] Unveiling Websites  Your Source for YouTube Branding Collabs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-fixing-obss-full-screen-freeze-up-for-2024/"><u>[Updated] Fixing OBS's Full-Screen Freeze Up for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-pixelprofiler-yearly-review-of-best-screen-capturing-tools/"><u>[Updated] PixelProfiler  Yearly Review of Best Screen Capturing Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-subscribers-count-in-real-time/"><u>[Updated] Subscribers Count in Real-Time</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-mastering-personal-branding-essential-strategies-for-facebook-bio-crafting/"><u>2024 Approved  Mastering Personal Branding  Essential Strategies for Facebook Bio Crafting</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-noise-free-ai-transcription-technology/"><u>2024 Approved  Noise-Free AI Transcription Technology</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/a-comprehensive-guide-to-iphone-xs-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>A Comprehensive Guide to iPhone XS Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-tecno-spark-20-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Tecno Spark 20 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://media-tips.techidaily.com/best-video-transforming-tools-an-in-depth-look-at-the-leading-walkman-video-converters/"><u>Best Video Transforming Tools: An In-Depth Look at the Leading Walkman Video Converters</u></a></li>
<li><a href="https://tech-revival.techidaily.com/cease-the-comparison-game-grasping-how-siri-differs-from-chatgpt/"><u>Cease the Comparison Game - Grasping How Siri Differs From ChatGPT</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-honor-90-lite-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Honor 90 Lite Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/discover-the-secret-to-character-customization-vocal-variety-in-free-fire/"><u>Discover the Secret to Character Customization  Vocal Variety in Free Fire</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-15-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone 15 Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-poco-f5-pro-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Poco F5 Pro 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-honor-x7b-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Honor X7b Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-vivo-y78plus-t1-edition-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Vivo Y78+ (T1) Edition Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-xiaomi-redmi-k70-pro-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Xiaomi Redmi K70 Pro Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-plus-to-an-older-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 Plus to an Older iOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-y28-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-xiaomi-13-ultra-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-itel-p55plus-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Itel P55+ in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-samsung-galaxy-s24plus-phone-by-drfone-android/"><u>How to Reset a Locked Samsung Galaxy S24+ Phone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-honor-90-lite-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Honor 90 Lite without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-infinix-smart-7-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Infinix Smart 7 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-plus-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 Plus To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6s-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6s to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-se-2020-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-11-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 11 Pro Max Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-motorola-moto-e13-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Motorola Moto E13 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/no-more-interruptions-expert-advice-on-how-to-fix-recurring-multiversus-app-crashes-the-top-8-fixes/"><u>No More Interruptions: Expert Advice on How To Fix Recurring MultiVersus App Crashes - The Top 8 Fixes</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-tecno-spark-20c-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Tecno Spark 20C</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/speedy-setup-obtaining-your-thrustmaster-fcs-logitech-g25-racing-wheel-drives-in-minutes/"><u>Speedy Setup: Obtaining Your Thrustmaster FCS Logitech G25 Racing Wheel Drives in Minutes</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-itel-p40plus-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-honor-play-7t-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Honor Play 7T.</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-xiaomi-redmi-note-12t-pro-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Xiaomi Redmi Note 12T Pro.</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-tecno-pop-7-pro-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Tecno Pop 7 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-vivo-y36i-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Vivo Y36i.</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-galaxy-z-flip-5-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Galaxy Z Flip 5.</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-6s-lock-with-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 6s lock with iCloud</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-drivers-in-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to update drivers in Windows 11/10/7</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-htc-u23-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your HTC U23 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/why-can-t-i-play-mp4-files-on-my-galaxy-a14-4g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Why can’t I play MP4 files on my Galaxy A14 4G?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->