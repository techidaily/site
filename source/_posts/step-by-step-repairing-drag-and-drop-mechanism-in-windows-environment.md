---
title: "Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
date: 2024-08-18T03:46:18.840Z
updated: 2024-08-19T03:46:18.840Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
excerpt: "This Article Describes Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
thumbnail: https://thmb.techidaily.com/e64ba1588493794efe1f30713a2c1b387c63e2ee11d657d48f4608e17ab1d777.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-redefine-viewing-premium-platforms-for-videos/"><u>[New] 2024 Approved  Redefine Viewing  Premium Platforms for Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-essential-titles-your-gateway-to-open-worlds/"><u>[New] In 2024, Essential Titles  Your Gateway to Open Worlds</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-perfect-your-gaming-capture-console-gameplay-on-a-computer/"><u>[New] In 2024, Perfect Your Gaming Capture  Console Gameplay on a Computer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-transformation-of-video-on-facebook/"><u>[New] The Transformation of Video on Facebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-effortless-downloads-at-zero-cost-find-the-top-20-tools-for-youtube-sound-ripping/"><u>[Updated] 2024 Approved  Effortless Downloads at Zero Cost  Find the Top 20 Tools for YouTube Sound Ripping</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-hitting-the-sweet-spot-balancing-images-in-your-instagram-story-for-2024/"><u>[Updated] Hitting the Sweet Spot  Balancing Images in Your Instagram Story for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-substitutes-for-winmovie-new-windows-editors/"><u>[Updated] Substitutes for WinMovie  New Windows Editors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-understanding-whatsapps-voice-communication-system/"><u>[Updated] Understanding WhatsApp's Voice Communication System</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unveiling-the-secrets-of-instagrams-musical-emoji-usage-for-2024/"><u>[Updated] Unveiling the Secrets of Instagram's Musical Emoji Usage for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimal-chuckle-inducing-layout/"><u>2024 Approved  Optimal Chuckle-Inducing Layout</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-secrets-to-perfect-green-screen-in-kinemaster/"><u>2024 Approved  Unveiling the Secrets to Perfect Green Screen in Kinemaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-your-onedrive-save-point-on-windows-10/"><u>Altering Your OneDrive Save Point on Windows 10</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-vivo-x90s-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Vivo X90S Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-asus-rog-phone-7-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Asus ROG Phone 7 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-on-getting-a-stuck-paradox-launcher-back-in-action/"><u>Expert Advice on Getting a Stuck Paradox Launcher Back in Action</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-a2-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo A2 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Vivo Y100i? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-11-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 11 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-xr-without-losing-any-content-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone XR without Losing Any Content? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-m14-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-zte-axon-40-lite-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-google-pixel-fold-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Google Pixel Fold without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y200e-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y200e 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oppo-f23-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Oppo F23 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-12-mini-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 12 mini without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-6s-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 6s Plus without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-14-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 14 Pro Max without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oppo-reno-11-5g-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-infinix-smart-8-plus-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Infinix Smart 8 Plus Devices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-streamlining-post-production-adding-annotations-to-videos/"><u>In 2024, Streamlining Post-Production  Adding Annotations to Videos</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-15-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 15 Pro Max Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-narzo-60-5g-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Narzo 60 5G</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-moto-g73-5g-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Moto G73 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-common-problems-with-your-hp-wireless-keyboard-step-by-step-guide/"><u>Solving Common Problems with Your HP Wireless Keyboard: Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-dsounddll-file-absence-issue-a-step-by-step-guide/"><u>Solving the dsound.dll File Absence Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-nubia-red-magic-8s-pro-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Motorola Edge 2023? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-lava-blaze-2-5g-by-fonelab-android-recover-data/"><u>The way to get back lost data from Lava Blaze 2 5G</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-lava-blaze-pro-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Lava Blaze Pro 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-huawei-p60-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Huawei P60.</u></a></li>
<li><a href="https://techidaily.com/top-ways-to-unlock-iphone-se-2022-screen-lock-by-drfone-ios-unlock-ios-unlock/"><u>Top ways to unlock iPhone SE (2022) screen lock</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-honor-x7b-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Honor X7b</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-x50iplus-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/zoomed-up-enhancing-action-film-clarity/"><u>Zoomed Up  Enhancing Action Film Clarity</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->