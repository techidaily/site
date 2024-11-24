---
title: "Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device"
date: 2024-11-21T21:29:25.775Z
updated: 2024-11-24T03:28:20.858Z
tags:
  - mobile
categories:
  - tech
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device

### Key Takeaways

* USB debugging in Android isn't just for developers - it can be used to recover data and control your phone from a computer.
* Remember to keep USB debugging enabled to access files or control your phone even if the screen is broken.
* Be cautious - enabling USB debugging can allow unwanted access to your data, but Android's security can prevent this.

 You may think that Android's USB debugging feature, hidden within the developer options, is only for, well, developers. But it can be very useful for just about anyone and could very well save your back someday. To do that, you'll need to have enabled the feature beforehand.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  USB Debugging Can Help Recover Data

 On-device [developer options](https://youtube-docs.techidaily.com/approved-decode-your-youtube-preferences-with-these-6-fan-favorite-questionnaires/) exist to help app developers debug (find and fix technical issues) and test apps. Typically, developers code apps in Android Studio on a PC. Enabling USB debugging allows them to send data and commands between their computer and their phone.

 But debugging isn’t all. We can use the same feature to access a phone’s files and control them from our computer. The cool part? It works even if the device display or touch screen is broken. As long as the phone is turned on, you can interact with it. The only requirement is that USB debugging _has_ to be enabled already since you can't do it after the fact on a device with a broken screen.

 If you have it enabled, you can simply plug your phone into a pre-authorized computer via USB cable. Then you just have to install [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) (ADB) tools on the computer, and you get full access to your phone—messages, photos, contacts, essentially everything.

 Leaving USB debugging enabled comes with a serious caveat. With USB debugging on, anyone who gains physical access can read your data, modify things, or install malicious apps. Even the screen lock won’t protect you. Thankfully, Android’s security stops unwanted access like that. You have to grant permission on your phone to each computer to establish a connection manually. That’s where you can pre-authorize a computer for future use.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Enable USB Debugging

 Enabling USB Debugging is simple enough. Just go to Settings > About Phone > Build Number. Tap “Build Number” seven times to enable Developer Options.

![The step-by-step process of enabling developer options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-8.png) 

 Then open Developer Options > USB Debugging. Enable the toggle and confirm.

![Two red arrows highlighting USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-9.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 These settings and menus vary slightly between Android manufacturers. If you can’t find these menus, we have a detailed guide on how to [enable Developer Options and USB Debugging](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

##  How to Recover Data Using ADB

 Once you have enabled “USB Debugging,” we need to set up a recovery point (to use in case your phone malfunctions or breaks).

###  Everything You Need

 To create a “recovery point,” you need:

* ADB tools
* USB Cable
* Scrcpy

 You can grab [ADB Tools from the official website](https://developer.android.com/tools/releases/platform-tools#downloads) and [Scrcpy from its GitHub](https://github.com/Genymobile/scrcpy) repo. ADB tools let you interact with the phone through the command line. We’ll pull files off the phone using ADB. [Scrcpy is an awesome tool for mirroring](https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/) and controlling your phone using your computer’s mouse.

###  Installing ADB

 ADB is officially bundled in "Platform Tools." Extract the Platform Tools archive (that you just downloaded) anywhere on your computer. Open the extracted folder. Hold down shift and right-click anywhere on the blank space. Click “Open PowerShell window here” and wait for the terminal to open.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

 Connect your phone to the computer using a USB cable (make sure “USB Debugging” is still enabled). A small pop-up should appear on your phone as soon as you do that. Select “Always Allow From This Computer” and then tap “OK” to allow the connection.

![Allowing USB debugging for a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240801-014110.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It’s crucial that you keep “Always Allow From This Computer” checked. It’ll safelist your computer. So you won’t have to manually grant this permission on your phone if it ever breaks.

 Now back to the PowerShell window we just opened. Type the following command and press Enter:

adb devices

 You’ll get a list of attached devices, along with their identifier strings.

![Using the PowerShell terminal to verify a successful ADB connection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012651.png) 

 If the “adb devices” is returning a blank result, your computer is likely missing the relevant Android drivers. You can install the official drivers from the device manufacturer’s website, restart the computer, and try again.

###  Installing Scrcpy

 Open the official [Scrcpy repository](https://github.com/Genymobile/scrcpy/releases/tag/v2.5) on GitHub and download the relevant package for your operating system. I downloaded the “win64” zip archive. Extract it anywhere on your computer and open the extracted folder.

![Launching Scrcpy from the extracted folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014359.png) 

 You can double-click “scrcpy.exe” to instantly mirror the Android screen on your computer. You should be able to interact with this mirrored screen using your mouse right away.

![Mirrored Android phone screen using Scrcpy.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014500.png) 

 I tested Scrcpy on an older phone, and the mouse didn't work on its own. If you're having trouble with the mouse control, click the “open a terminal here” file. Once the command prompt window opens, type in the following command and press Enter.

scrcpy --mouse=uhid

Close 

 A rectangular window should automatically pop up, but it might be blank at first. Simply press the power button on your phone or the right-click button on your mouse to wake it up. Scrcpy will “capture” the cursor, and it’ll stick within the mirrored window. You can release it and use the mouse normally by pressing the Window or Alt key (Command or Option on Mac).

 If the mouse isn’t working in the mirrored window, close the window and try again with this command: scrcpy --mouse=aoa

 Scrcpy will only start streaming the screen after you’ve unlocked the phone. You can unlock it by using the fingerprint scanner. Alternatively, you can wake up the screen by right-clicking anywhere.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Recovering Data

 There are two ways you can recover your data. The simplest solution is just opening a Scrcpy instance with mouse interaction enabled. From there, it’s a simple matter of uploading your important files, contacts, messages, and photos to the personal cloud service of your choice. Alternatively, you can use [Nearby Share](https://article-knowledge.techidaily.com/new-2024-approved-the-gopro-camera-leap-hero4-to-hero5/) to send files to your computer.

 Pulling files directly from your phone is a little bit trickier. One way to do it is to connect the phone to your computer using a USB cable. Then, mirror the phone screen via Scrcpy, use the mouse to pull down the notification shade, and set the USB preferences to “File Transfer.” The phone’s storage should pop up as a [separate drive in Windows Explorer](https://tech-renaissance.techidaily.com/boosting-the-quality-of-photography-on-your-iphoneipad-a-comprehensive-guide/).

 We’re going to run a different ADB command on our computer to get the job done.

 Navigate to the “Platform Tools” folder, hold down shift, and right-click anywhere blank to open the context menu. Select “Open a Powershell Window Here,” just like you did before.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the transfer, you’ll need the location of the file on your phone. Open the [file manager](https://visual-screen-recording.techidaily.com/updated-2024-approved-comprehensive-manual-best-practices-for-using-mobizen-recording-tool/) of your choice on your phone and locate the file you want to transfer (you can do this by interacting with the phone using Srncpy on your computer). Tap the file to open it, click the three-dot button, and select “File Info.” It’ll reveal the file’s location.

Close 

 Type the following command in the Powershell window and press Enter. Replace the example location in this command with the location of your file.

adb pull /storage/emulated/0/Pictures/pic.png

![Pulling a file from an Android phone using an ADB command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-020401.png) 

 You’ll find this pulled file inside the Users directory in your Windows drive.

---

 Sliding one toggle on your phone’s settings can save you the headache of taking it to the shop just to recover your important files.

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
<li><a href="https://fox-direct.techidaily.com/new-elevate-your-design-skills-mastering-3d-text-effects-for-2024/"><u>[New] Elevate Your Design Skills Mastering 3D Text Effects for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-investigating-instagrams-videography-cap-for-2024/"><u>[New] Investigating Instagram's Videography Cap for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-uncharted-territories-virtual-realitys-role-in-leisure/"><u>[New] Uncharted Territories Virtual Reality's Role in Leisure</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-action-camera-faceoff-gopro-hero-vs-sony-dslr-for-adventure-seekers/"><u>[Updated] 2024 Approved Action Camera Faceoff GoPro Hero Vs. Sony DSLR for Adventure Seekers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-best-practices-saving-whatsapp-conversations-audio-wise/"><u>[Updated] In 2024, Best Practices Saving WhatsApp Conversations Audio-Wise</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unmatched-smartphone-camera-apps-on-ios-and-android-devices/"><u>[Updated] Unmatched Smartphone Camera Apps on iOS & Android Devices</u></a></li>
<li><a href="https://extra-hints.techidaily.com/close-up-clarity-mastering-the-art-of-intense-focus-for-2024/"><u>Close-Up Clarity Mastering the Art of Intense Focus for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-smart-8-plus-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Smart 8 Plus If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-vivo-x-fold-2-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Vivo X Fold 2 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-xs-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone XS Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-vivo-y78plus-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Vivo Y78+</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-innovative-techniques-for-unique-canon-timelapse-vids/"><u>In 2024, Innovative Techniques for Unique Canon Timelapse Vids</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-xiaomi-redmi-note-12t-pro-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-70-lite-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor 70 Lite 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-vivo-y100-5g-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Vivo Y100 5G.</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-g42-5g-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of G42 5G on Mac?</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-infinix-note-30-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Infinix Note 30 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-driver-optimization-a-user-friendly-approach-with-revo-uninstaller-tutorials/"><u>Windows 11 Driver Optimization: A User-Friendly Approach with Revo Uninstaller Tutorials</u></a></li>
</ul></div>

