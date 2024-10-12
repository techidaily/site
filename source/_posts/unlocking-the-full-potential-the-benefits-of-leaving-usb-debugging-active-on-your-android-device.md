---
title: "Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device"
date: 2024-10-07T23:52:51.071Z
updated: 2024-10-12T01:04:05.585Z
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

##  USB Debugging Can Help Recover Data

 On-device [developer options](https://youtube-docs.techidaily.com/approved-decode-your-youtube-preferences-with-these-6-fan-favorite-questionnaires/) exist to help app developers debug (find and fix technical issues) and test apps. Typically, developers code apps in Android Studio on a PC. Enabling USB debugging allows them to send data and commands between their computer and their phone.

 But debugging isn’t all. We can use the same feature to access a phone’s files and control them from our computer. The cool part? It works even if the device display or touch screen is broken. As long as the phone is turned on, you can interact with it. The only requirement is that USB debugging _has_ to be enabled already since you can't do it after the fact on a device with a broken screen.

 If you have it enabled, you can simply plug your phone into a pre-authorized computer via USB cable. Then you just have to install [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) (ADB) tools on the computer, and you get full access to your phone—messages, photos, contacts, essentially everything.

 Leaving USB debugging enabled comes with a serious caveat. With USB debugging on, anyone who gains physical access can read your data, modify things, or install malicious apps. Even the screen lock won’t protect you. Thankfully, Android’s security stops unwanted access like that. You have to grant permission on your phone to each computer to establish a connection manually. That’s where you can pre-authorize a computer for future use.

##  How to Enable USB Debugging

 Enabling USB Debugging is simple enough. Just go to Settings > About Phone > Build Number. Tap “Build Number” seven times to enable Developer Options.

![The step-by-step process of enabling developer options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-8.png) 

 Then open Developer Options > USB Debugging. Enable the toggle and confirm.

![Two red arrows highlighting USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-9.png) 

 These settings and menus vary slightly between Android manufacturers. If you can’t find these menus, we have a detailed guide on how to [enable Developer Options and USB Debugging](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

##  How to Recover Data Using ADB

 Once you have enabled “USB Debugging,” we need to set up a recovery point (to use in case your phone malfunctions or breaks).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049378/7443" target="_top" id="2049378">
  <img src="//a.impactradius-go.com/display-ad/7443-2049378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Everything You Need

 To create a “recovery point,” you need:

* ADB tools
* USB Cable
* Scrcpy

 You can grab [ADB Tools from the official website](https://developer.android.com/tools/releases/platform-tools#downloads) and [Scrcpy from its GitHub](https://github.com/Genymobile/scrcpy) repo. ADB tools let you interact with the phone through the command line. We’ll pull files off the phone using ADB. [Scrcpy is an awesome tool for mirroring](https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/) and controlling your phone using your computer’s mouse.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Installing ADB

 ADB is officially bundled in "Platform Tools." Extract the Platform Tools archive (that you just downloaded) anywhere on your computer. Open the extracted folder. Hold down shift and right-click anywhere on the blank space. Click “Open PowerShell window here” and wait for the terminal to open.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

 Connect your phone to the computer using a USB cable (make sure “USB Debugging” is still enabled). A small pop-up should appear on your phone as soon as you do that. Select “Always Allow From This Computer” and then tap “OK” to allow the connection.

![Allowing USB debugging for a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240801-014110.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 It’s crucial that you keep “Always Allow From This Computer” checked. It’ll safelist your computer. So you won’t have to manually grant this permission on your phone if it ever breaks.

 Now back to the PowerShell window we just opened. Type the following command and press Enter:

adb devices

 You’ll get a list of attached devices, along with their identifier strings.

![Using the PowerShell terminal to verify a successful ADB connection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012651.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the “adb devices” is returning a blank result, your computer is likely missing the relevant Android drivers. You can install the official drivers from the device manufacturer’s website, restart the computer, and try again.

###  Installing Scrcpy

 Open the official [Scrcpy repository](https://github.com/Genymobile/scrcpy/releases/tag/v2.5) on GitHub and download the relevant package for your operating system. I downloaded the “win64” zip archive. Extract it anywhere on your computer and open the extracted folder.

![Launching Scrcpy from the extracted folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014359.png) 

 You can double-click “scrcpy.exe” to instantly mirror the Android screen on your computer. You should be able to interact with this mirrored screen using your mouse right away.

![Mirrored Android phone screen using Scrcpy.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014500.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 I tested Scrcpy on an older phone, and the mouse didn't work on its own. If you're having trouble with the mouse control, click the “open a terminal here” file. Once the command prompt window opens, type in the following command and press Enter.

scrcpy --mouse=uhid

Close 

 A rectangular window should automatically pop up, but it might be blank at first. Simply press the power button on your phone or the right-click button on your mouse to wake it up. Scrcpy will “capture” the cursor, and it’ll stick within the mirrored window. You can release it and use the mouse normally by pressing the Window or Alt key (Command or Option on Mac).

 If the mouse isn’t working in the mirrored window, close the window and try again with this command: scrcpy --mouse=aoa

 Scrcpy will only start streaming the screen after you’ve unlocked the phone. You can unlock it by using the fingerprint scanner. Alternatively, you can wake up the screen by right-clicking anywhere.

##  Recovering Data

 There are two ways you can recover your data. The simplest solution is just opening a Scrcpy instance with mouse interaction enabled. From there, it’s a simple matter of uploading your important files, contacts, messages, and photos to the personal cloud service of your choice. Alternatively, you can use [Nearby Share](https://article-knowledge.techidaily.com/new-2024-approved-the-gopro-camera-leap-hero4-to-hero5/) to send files to your computer.

 Pulling files directly from your phone is a little bit trickier. One way to do it is to connect the phone to your computer using a USB cable. Then, mirror the phone screen via Scrcpy, use the mouse to pull down the notification shade, and set the USB preferences to “File Transfer.” The phone’s storage should pop up as a [separate drive in Windows Explorer](https://tech-renaissance.techidaily.com/boosting-the-quality-of-photography-on-your-iphoneipad-a-comprehensive-guide/).

 We’re going to run a different ADB command on our computer to get the job done.

 Navigate to the “Platform Tools” folder, hold down shift, and right-click anywhere blank to open the context menu. Select “Open a Powershell Window Here,” just like you did before.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

 To make the transfer, you’ll need the location of the file on your phone. Open the [file manager](https://visual-screen-recording.techidaily.com/updated-2024-approved-comprehensive-manual-best-practices-for-using-mobizen-recording-tool/) of your choice on your phone and locate the file you want to transfer (you can do this by interacting with the phone using Srncpy on your computer). Tap the file to open it, click the three-dot button, and select “File Info.” It’ll reveal the file’s location.

Close 

 Type the following command in the Powershell window and press Enter. Replace the example location in this command with the location of your file.

adb pull /storage/emulated/0/Pictures/pic.png

![Pulling a file from an Android phone using an ADB command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-020401.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-lead-the-charge-with-our-12-best-tycoon-games-ever-played/"><u>[New] 2024 Approved Lead the Charge with Our #12 Best Tycoon Games Ever Played</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ime-warp-in-media-youtube-content-upside-down-for-2024/"><u>[New] Time Warp in Media YouTube Content Upside Down for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-dissecting-popularity-ten-facts-about-reels-unmasked-for-2024/"><u>[Updated] Dissecting Popularity Ten Facts About Reels, Unmasked for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-skyrocket-mobile-images-flawlessly-free-for-2024/"><u>[Updated] Skyrocket Mobile Images Flawlessly, Free for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-apex-1-written-by-assistant/"><u>2024 Approved Apex 1 Written by Assistant</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-vivo-y02t-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Vivo Y02T Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-samsung-galaxy-a23-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-14-plus-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 14 Plus to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-mastering-mac-snipers-top-5-recommended-tools/"><u>In 2024, Mastering Mac Snipers Top 5 Recommended Tools</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-motorola-moto-g-stylus-2023-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Motorola Moto G Stylus (2023) on Windows</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-motorola-moto-g-stylus-2023-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://change-location.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-master-your-automotive-tunes-top-5-mac-friendly-music-mixing-software-selections/"><u>Updated Master Your Automotive Tunes Top 5 Mac-Friendly Music Mixing Software Selections</u></a></li>
<li><a href="https://techidaily.com/what-to-do-if-iphone-15-plus-is-not-listed-when-i-run-the-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What to do if iPhone 15 Plus is not listed when I run the software? | Stellar</u></a></li>
</ul></div>

