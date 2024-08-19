---
title: "Prevent Automatic Driver Updates During Windows 10 System Rollouts: A Comprehensive Guide"
date: 2024-08-18T03:41:21.820Z
updated: 2024-08-19T03:41:21.820Z
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
<li><a href="https://instagram-clips.techidaily.com/new-how-to-create-a-puzzle-feed-on-instagram-to-catch-attention/"><u>[New] How to Create a Puzzle Feed on Instagram to Catch Attention</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-optimal-webcam-use-and-recording-techniques-for-macbook/"><u>[New] Optimal Webcam Use and Recording Techniques for MacBook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-optimizing-film-length-for-instagram-on-mac/"><u>[New] Optimizing Film Length for Instagram on Mac</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-add-shimmer-to-photos-illustrators-motion-blur-guide/"><u>[Updated] Add Shimmer to Photos  Illustrator's Motion Blur Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-budget-friendly-1-decade-of-excellent-desktop-recorders/"><u>[Updated] Budget-Friendly #1 Decade of Excellent Desktop Recorders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-infographic-analysis-the-hottest-2023-trends/"><u>[Updated] Infographic Analysis  The Hottest 2023 Trends</u></a></li>
<li><a href="https://win-solutions.techidaily.com/assassins-creed-valhalla-pc-stability-issues-heres-what-you-need-to-know/"><u>Assassin's Creed Valhalla PC Stability Issues? Here’s What You Need to Know!</u></a></li>
<li><a href="https://games-able.techidaily.com/best-led-options-reviewed/"><u>Best LED Options Reviewed</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-samsung-galaxy-f15-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-xr-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone XR Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-x-to-an-older-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone X to an Older Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-12-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi 12 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-13c-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi 13C 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-15-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-lava-blaze-2-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Lava Blaze 2 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-x-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-pro-to-other-iphone-15-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Pro to other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-pro-max-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 Pro Max to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-14-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 14 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-se-2020-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone SE (2020) without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-beyond-glitter-the-pure-reality-of-recordcast-experience/"><u>In 2024, Beyond Glitter  The Pure Reality of RecordCast Experience</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-iphone-12-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 12 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-13-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 13 Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-s23plus-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for S23+</u></a></li>
<li><a href="https://win-dash.techidaily.com/secure-and-fast-the-latest-nvidia-mx150-drivers-for-your-windows-laptop-or-desktop/"><u>Secure & Fast: The Latest NVIDIA MX150 Drivers for Your Windows Laptop or Desktop</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-won-t-play-on-vivo-v27-pro-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on Vivo V27 Pro</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-samsung-galaxy-s23-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-realme-12-5g-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Realme 12 5G</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-oppo-k11x-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Oppo K11x without backup.</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-itel-p40plus-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Itel P40+.</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-drivers-on-windows-11-and-10-by-drivereasy-guide/"><u>Use Device Manager to reinstall drivers on Windows 11 & 10</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-samsung-galaxy-m14-4g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Samsung Galaxy M14 4G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/why-can-t-i-play-mp4-files-on-my-redmi-a2plus-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Why can’t I play MP4 files on my Redmi A2+?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->