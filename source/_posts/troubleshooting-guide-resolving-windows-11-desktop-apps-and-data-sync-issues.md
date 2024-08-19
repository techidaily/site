---
title: "Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues"
date: 2024-08-18T03:45:16.610Z
updated: 2024-08-19T03:45:16.610Z
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
<li><a href="https://extra-resources.techidaily.com/new-best-buy-in-4k-budget-savvy-camera-picks/"><u>[New] Best Buy in 4K  Budget-Savvy Camera Picks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-giggle-factor-comparing-humor-in-tiktok-and-snapchat-videos/"><u>[New] In 2024, The Giggle Factor  Comparing Humor in TikTok and Snapchat Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-survival-of-the-undead-cutthroat-top-8-zombie-titles/"><u>[New] Survival of the Undead  Cutthroat Top 8 Zombie Titles</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-future-of-human-computer-conversation-systems/"><u>[Updated] The Future of Human-Computer Conversation Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/accessing-shared-media-on-messenger/"><u>Accessing Shared Media on Messenger</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-oppo-find-n3-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-v27-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-apple-iphone-11-pro-max-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From Apple iPhone 11 Pro Max? Heres the Best Fixes</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-lava-yuva-3-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-itel-s23plus-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Itel S23+ in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-tecno-camon-20-pro-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Tecno Camon 20 Pro 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-nubia-red-magic-9-proplus-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Nubia Red Magic 9 Pro+ Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-magic-vs-2-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Honor Magic Vs 2 Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-6s-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 6s Plus without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-7-plus-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 7 Plus Data Permanently | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a1-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A1 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oppo-a56s-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Oppo A56s 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-pro-max-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 Pro Max iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-system-of-apple-iphone-13-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-11-pro-max-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 11 Pro Max To Others devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-messages-from-apple-iphone-xr-to-other-iphone-all-ios-versions-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Messages From Apple iPhone XR to other iPhone All iOS Versions | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-iphone-se-2020-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile iPhone SE (2020) online without SIM Card?</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-6-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 6 Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-oppo-k11x-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Oppo K11x Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-poco-m6-pro-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Poco M6 Pro 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-iphone-15-pro-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From iPhone 15 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-iphone-pro-tips-effortlessly-assemble-photo-collagues/"><u>In 2024, IPhone Pro Tips  Effortlessly Assemble Photo Collagues</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-nubia-z50-ultra-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Nubia Z50 Ultra working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mastering-compression-in-fcpx-a-step-by-step-guide/"><u>New Mastering Compression in FCPX A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-8-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 8 Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-corrupt-pdf-v10-files-on-my-mac-using-tool-by-stellar-guide/"><u>Repair corrupt PDF v1.0 files on my Mac using tool</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-itel-s23-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Itel S23</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-honor-play-8t-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Honor Play 8T</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-zoom-setup-ensuring-smooth-video-conferencing-for-2024/"><u>The Art of Zoom Setup  Ensuring Smooth Video Conferencing for 2024</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-odt-file-documents-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>The best electronic signature way to sign .odt file documents online</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-infinix-hot-40-pro-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Infinix Hot 40 Pro</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-moto-g14-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Moto G14 without backup.</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-nubia-red-magic-9-proplus-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Nubia Red Magic 9 Pro+.</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/unleash-your-creativity-top-rated-stop-motion-apps-for-mobile-for-2024/"><u>Unleash Your Creativity Top-Rated Stop Motion Apps for Mobile for 2024</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-se-2020-screen-lock-without-data-loss-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone SE (2020) screen lock without data loss</u></a></li>
<li><a href="https://techidaily.com/update-your-hardware-drivers-with-device-manager-on-windows-1110-by-drivereasy-guide/"><u>Update your hardware drivers with Device Manager on Windows 11/10</u></a></li>
<li><a href="https://techidaily.com/what-can-you-do-with-face-id-on-iphone-se-by-drfone-ios-unlock-ios-unlock/"><u>What can you do with Face ID on iPhone SE?</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-x50i-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor X50i | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->