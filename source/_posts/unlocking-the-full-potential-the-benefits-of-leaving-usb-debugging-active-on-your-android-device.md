---
title: "Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device"
date: 2024-09-12T01:07:57.153Z
updated: 2024-09-13T01:07:57.153Z
tags:
  - mobile
categories:
  - tech
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then open Developer Options > USB Debugging. Enable the toggle and confirm.

![Two red arrows highlighting USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-9.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 These settings and menus vary slightly between Android manufacturers. If you can’t find these menus, we have a detailed guide on how to [enable Developer Options and USB Debugging](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Connect your phone to the computer using a USB cable (make sure “USB Debugging” is still enabled). A small pop-up should appear on your phone as soon as you do that. Select “Always Allow From This Computer” and then tap “OK” to allow the connection.

![Allowing USB debugging for a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240801-014110.jpg) 

 It’s crucial that you keep “Always Allow From This Computer” checked. It’ll safelist your computer. So you won’t have to manually grant this permission on your phone if it ever breaks.

 Now back to the PowerShell window we just opened. Type the following command and press Enter:

adb devices

 You’ll get a list of attached devices, along with their identifier strings.

![Using the PowerShell terminal to verify a successful ADB connection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012651.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the “adb devices” is returning a blank result, your computer is likely missing the relevant Android drivers. You can install the official drivers from the device manufacturer’s website, restart the computer, and try again.

###  Installing Scrcpy

 Open the official [Scrcpy repository](https://github.com/Genymobile/scrcpy/releases/tag/v2.5) on GitHub and download the relevant package for your operating system. I downloaded the “win64” zip archive. Extract it anywhere on your computer and open the extracted folder.

![Launching Scrcpy from the extracted folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014359.png) 

 You can double-click “scrcpy.exe” to instantly mirror the Android screen on your computer. You should be able to interact with this mirrored screen using your mouse right away.

![Mirrored Android phone screen using Scrcpy.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014500.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/n-2024-mastering-the-art-of-design-selecting-ideal-dimensions-for-yt-branding/"><u>[New] In 2024, Mastering the Art of Design Selecting Ideal Dimensions for YT Branding</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-essential-tips-for-crafting-perfect-drone-video-edits/"><u>[Updated] In 2024, Essential Tips for Crafting Perfect Drone Video Edits</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimizing-footage-variety-in-your-video-production/"><u>2024 Approved Optimizing Footage Variety in Your Video Production</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-winning-software-to-capture-your-display-on-windows-10/"><u>2024 Approved Winning Software to Capture Your Display on Windows 10</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guia-paso-a-paso-para-grabar-imagenes-iso-en-un-dvd-con-windows-10-8-o-7/"><u>Guía Paso a Paso Para Grabar Imágenes ISO en Un DVD Con Windows 10, 8 O 7.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-samsung-galaxy-m14-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Samsung Galaxy M14 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-tf2-crashes-ultimate-troubleshooting-guide/"><u>How to Fix TF2 Crashes - Ultimate Troubleshooting Guide</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-official-dell-multiport-hub-device-driver-on-your-windows-machine/"><u>Install Official Dell Multiport Hub Device Driver on Your Windows Machine</u></a></li>
<li><a href="https://techidaily.com/the-downside-of-touch-button-overuse-why-companies-must-rethink-their-digital-interfaces/"><u>The Downside of Touch Button Overuse: Why Companies Must Rethink Their Digital Interfaces</u></a></li>
<li><a href="https://techidaily.com/the-evolution-of-grok-into-it-jargon-tracing-its-origins-and-adoption-in-computing/"><u>The Evolution of 'Grok' Into IT Jargon: Tracing Its Origins and Adoption in Computing</u></a></li>
<li><a href="https://techidaily.com/the-expansion-of-metas-artificnial-intelligence-in-messenger-applications/"><u>The Expansion of Meta's Artificnial Intelligence in Messenger Applications</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/transformacion-gratuita-de-archivos-dvd-a-hevc-mp4-maximizar-calidad-y-reducir-tamano/"><u>Transformación Gratuita De Archivos DVD a HEVC MP4: Maximizar Calidad Y Reducir Tamaño</u></a></li>
</ul></div>

