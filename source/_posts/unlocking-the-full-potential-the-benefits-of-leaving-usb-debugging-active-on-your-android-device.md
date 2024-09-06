---
title: "Unlocking the Full Potential: The Benefits of Leaving USB Debugging Active on Your Android Device"
date: 2024-09-05T06:19:35.087Z
updated: 2024-09-06T06:19:35.087Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then open Developer Options > USB Debugging. Enable the toggle and confirm.

![Two red arrows highlighting USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-9.png) 

 These settings and menus vary slightly between Android manufacturers. If you can’t find these menus, we have a detailed guide on how to [enable Developer Options and USB Debugging](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Recover Data Using ADB

 Once you have enabled “USB Debugging,” we need to set up a recovery point (to use in case your phone malfunctions or breaks).

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Connect your phone to the computer using a USB cable (make sure “USB Debugging” is still enabled). A small pop-up should appear on your phone as soon as you do that. Select “Always Allow From This Computer” and then tap “OK” to allow the connection.

![Allowing USB debugging for a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240801-014110.jpg) 

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It’s crucial that you keep “Always Allow From This Computer” checked. It’ll safelist your computer. So you won’t have to manually grant this permission on your phone if it ever breaks.

 Now back to the PowerShell window we just opened. Type the following command and press Enter:

adb devices

 You’ll get a list of attached devices, along with their identifier strings.

![Using the PowerShell terminal to verify a successful ADB connection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012651.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938698/19272" target="_top" id="1938698">
  <img src="//a.impactradius-go.com/display-ad/19272-1938698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938698/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the “adb devices” is returning a blank result, your computer is likely missing the relevant Android drivers. You can install the official drivers from the device manufacturer’s website, restart the computer, and try again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

##  Recovering Data

 There are two ways you can recover your data. The simplest solution is just opening a Scrcpy instance with mouse interaction enabled. From there, it’s a simple matter of uploading your important files, contacts, messages, and photos to the personal cloud service of your choice. Alternatively, you can use [Nearby Share](https://article-knowledge.techidaily.com/new-2024-approved-the-gopro-camera-leap-hero4-to-hero5/) to send files to your computer.

 Pulling files directly from your phone is a little bit trickier. One way to do it is to connect the phone to your computer using a USB cable. Then, mirror the phone screen via Scrcpy, use the mouse to pull down the notification shade, and set the USB preferences to “File Transfer.” The phone’s storage should pop up as a [separate drive in Windows Explorer](https://tech-renaissance.techidaily.com/boosting-the-quality-of-photography-on-your-iphoneipad-a-comprehensive-guide/).

 We’re going to run a different ADB command on our computer to get the job done.

 Navigate to the “Platform Tools” folder, hold down shift, and right-click anywhere blank to open the context menu. Select “Open a Powershell Window Here,” just like you did before.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To make the transfer, you’ll need the location of the file on your phone. Open the [file manager](https://visual-screen-recording.techidaily.com/updated-2024-approved-comprehensive-manual-best-practices-for-using-mobizen-recording-tool/) of your choice on your phone and locate the file you want to transfer (you can do this by interacting with the phone using Srncpy on your computer). Tap the file to open it, click the three-dot button, and select “File Info.” It’ll reveal the file’s location.

Close 

 Type the following command in the Powershell window and press Enter. Replace the example location in this command with the location of your file.

adb pull /storage/emulated/0/Pictures/pic.png

![Pulling a file from an Android phone using an ADB command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-020401.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-soundtweetify-quick-audible-maker/"><u>[New] SoundTweetify  Quick Audible Maker</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-elite-upgrades-for-enhanced-gopro-images-for-2024/"><u>[Updated] Elite Upgrades for Enhanced GoPro Images for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/8-ultimate-free-3d-players-perfect-for-pcmac-users-out-there-for-2024/"><u>8 Ultimate Free 3D Players  Perfect for PC/Mac Users Out There for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/batch-automation-for-file-repositioning-in-win-11/"><u>Batch Automation for File Repositioning in Win 11</u></a></li>
<li><a href="https://techidaily.com/cookiebot-enhanced-experience-optimizing-your-sites-performance/"><u>Cookiebot-Enhanced Experience: Optimizing Your Site's Performance</u></a></li>
<li><a href="https://techidaily.com/cookiebot-the-secret-ingredient-boosting-your-websites-seo/"><u>Cookiebot: The Secret Ingredient Boosting Your Website's SEO</u></a></li>
<li><a href="https://techidaily.com/cookiebot-your-ultimate-marketing-automation-partner/"><u>Cookiebot: Your Ultimate Marketing Automation Partner</u></a></li>
<li><a href="https://techidaily.com/customized-engagement-through-the-power-of-cookiebot-technology/"><u>Customized Engagement Through the Power of Cookiebot Technology</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-mouse-driver-for-windows-7-solved/"><u>Download Mouse Driver for Windows 7 [Solved]</u></a></li>
<li><a href="https://techidaily.com/drive-engagement-with-lead-forms-boost-your-site-with-cookiebot/"><u>Drive Engagement with Lead Forms: Boost Your Site with Cookiebot</u></a></li>
<li><a href="https://techidaily.com/driving-digital-marketing-success-through-smart-data-insights-introducing-cookiebots-innovation/"><u>Driving Digital Marketing Success Through Smart Data Insights - Introducing Cookiebot's Innovation</u></a></li>
<li><a href="https://techidaily.com/effortless-scan-ocr-iphone-solution-transform-pdf-and-jpg-to-text-using-finereader/"><u>Effortless Scan, OCR iPhone Solution - Transform PDF & JPG to Text Using FineReader!</u></a></li>
<li><a href="https://techidaily.com/empower-your-site-with-cookiebot-technology/"><u>Empower Your Site with Cookiebot Technology</u></a></li>
<li><a href="https://techidaily.com/enhance-user-experience-and-boost-engagement-through-smart-ai-solutions-by-cookiebot/"><u>Enhance User Experience and Boost Engagement Through Smart AI Solutions by Cookiebot</u></a></li>
<li><a href="https://techidaily.com/enhanced-marketing-strategies-with-advanced-cookiebot-technology/"><u>Enhanced Marketing Strategies with Advanced Cookiebot Technology</u></a></li>
<li><a href="https://techidaily.com/exploring-core-techniques-in-process-analysis-aabby-vs-alternative-approach-comprehensive-guide-pdf/"><u>Exploring Core Techniques in Process Analysis: AABBY vs Alternative Approach – Comprehensive Guide (PDF)</u></a></li>
<li><a href="https://techidaily.com/exploring-musical-insights-bcr-guide-and-nostalgic-reflections-aabbys-latest-post/"><u>Exploring Musical Insights: BCR Guide & Nostalgic Reflections - AABBY's Latest Post</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hassle-free-downloads-and-updates-for-amds-smbus-driver-do-it-today/"><u>Hassle-Free Downloads & Updates for AMD's Smbus Driver: Do It Today!</u></a></li>
<li><a href="https://techidaily.com/how-abbyys-cutting-edge-process-automation-redefines-efficiency-at-the-us-food-and-drug-administration/"><u>How ABBYY's Cutting-Edge Process Automation Redefines Efficiency at The US Food & Drug Administration</u></a></li>
<li><a href="https://techidaily.com/ignacio-et-abbyy-sallient-pour-renforcer-lautomatisation-de-la-comptabilite-des-parties-prenantes/"><u>Ignacio Et ABBYY S'Allient Pour Renforcer L'Automatisation De La Comptabilité Des Parties Prenantes</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-realme-12plus-5gwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Realme 12+ 5Gwith/without a PC</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-innovative-techniques-for-ppts-and-webcams-2023-edition/"><u>In 2024, Innovative Techniques for PPTs and Webcams, 2023 Edition</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-the-smart-strategies-for-itunes-video-logging/"><u>In 2024, The Smart Strategies for iTunes Video Logging</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-itel-s23-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Itel S23 Phone Network-Ready</u></a></li>
<li><a href="https://techidaily.com/leveraging-cookiebot-for-superior-search-engine-visibility/"><u>Leveraging Cookiebot for Superior Search Engine Visibility</u></a></li>
<li><a href="https://techidaily.com/liberateur-du-potentiel-de-lentreprise-grace-a-la-digitisation-et-a-la-simulation-des-processus/"><u>Libérateur Du Potentiel De L'entreprise Grâce À La Digitisation Et À La Simulation Des Processus</u></a></li>
<li><a href="https://techidaily.com/master-essential-skills-instantly-your-personalized-vantage-point-blueprint/"><u>Master Essential Skills Instantly: Your Personalized Vantage Point Blueprint</u></a></li>
<li><a href="https://techidaily.com/prospects-turned-champions-inspiring-journeys-from-customer-queries-to-successful-engagements/"><u>Prospects Turned Champions: Inspiring Journeys From Customer Queries to Successful Engagements</u></a></li>
<li><a href="https://techidaily.com/revolutionizing-retail-the-journey-of-metro-ags-partnership-with-abbyy-for-optimized-business-processes/"><u>Revolutionizing Retail: The Journey of Metro AG's Partnership with ABBYY for Optimized Business Processes</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-preventing-crusader-kings-3-from-crashing-on-windows/"><u>Troubleshooting: Preventing Crusader Kings 3 From Crashing on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On OnePlus Nord 3 5G | Dr.fone</u></a></li>
</ul></div>
