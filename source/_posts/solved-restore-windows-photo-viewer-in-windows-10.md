---
title: "[SOLVED] Restore Windows Photo Viewer in Windows 10"
date: 2024-08-18T03:42:39.687Z
updated: 2024-08-19T03:42:39.687Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes [SOLVED] Restore Windows Photo Viewer in Windows 10
excerpt: This Article Describes [SOLVED] Restore Windows Photo Viewer in Windows 10
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
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
<li><a href="https://extra-tips.techidaily.com/updated-action-seekers-dream-the-ultimate-review-of-sj-cam-s6/"><u>[Updated] Action Seeker's Dream  The Ultimate Review of SJ-CAM S6</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-skyrocket-your-subscribers-with-these-easy-strategies/"><u>[Updated] Skyrocket Your Subscribers with These Easy Strategies</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-freemacos-the-ultimate-screen-logger/"><u>2024 Approved  FreeMacOS  The Ultimate Screen Logger</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-infinix-hot-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-nokia-g310-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Nokia G310 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-xiaomi-redmi-note-12-pro-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Xiaomi Redmi Note 12 Pro 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/elevating-your-visuals-mastering-instagram-edits-in-fcpx/"><u>Elevating Your Visuals  Mastering Instagram Edits in FCPX</u></a></li>
<li><a href="https://techidaily.com/hard-reset-google-pixel-8-pro-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Google Pixel 8 Pro in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-huawei-p60-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Huawei P60 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-itel-p55-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Itel P55 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-a34-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy A34 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-se-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-15-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 15 iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-reno-10-proplus-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo Reno 10 Pro+ 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-zte-axon-40-lite-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset ZTE Axon 40 Lite Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-v29-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo V29 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-plus-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 Plus to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-12-mini-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 12 mini to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-14-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 14 Pro Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-v30-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo V30 Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-xiaomi-redmi-a2-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Xiaomi Redmi A2?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-vivo-s17-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Vivo S17</u></a></li>
<li><a href="https://techidaily.com/remove-lock-screen-without-password-narzo-n55-by-drfone-android-unlock-android-unlock/"><u>Remove Lock Screen without Password(Narzo N55)</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-realme-narzo-60x-5g-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Realme Narzo 60x 5G on Windows</u></a></li>
<li><a href="https://techidaily.com/solutions-to-open-excel-2016-read-only-documents-by-stellar-guide/"><u>Solutions to open Excel 2016 Read Only Documents</u></a></li>
<li><a href="https://techidaily.com/solutions-to-open-excel-read-only-documents-stellar-by-stellar-guide/"><u>Solutions to open Excel Read Only Documents | Stellar</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-true-shelf-life-assessing-how-long-do-electric-versus-gasoline-cars-last/"><u>The True Shelf Life: Assessing How Long Do Electric Versus Gasoline Cars Last</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-nokia-c110-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Nokia C110.</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-90-pro-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on 90 Pro</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-xiaomi-redmi-note-12r-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Xiaomi Redmi Note 12R? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/turning-tails-into-heads-android-video-editing/"><u>Turning Tails Into Heads  Android Video Editing</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-galaxy-s24-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Galaxy S24</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-14-pro-lock-with-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 14 Pro lock with iCloud</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-drivers-with-windows-device-manager-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your drivers with Windows Device Manager on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-drivers-in-windows-11-and-10-by-drivereasy-guide/"><u>Use Device Manager to update drivers in Windows 11 & 10</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-your-drivers-in-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to update your drivers in Windows 11 & 10 & 7</u></a></li>
<li><a href="https://techidaily.com/what-can-you-do-with-face-id-on-iphone-8-by-drfone-ios-unlock-ios-unlock/"><u>What can you do with Face ID on iPhone 8?</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-xiaomi-13-ultra-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Xiaomi 13 Ultra | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->