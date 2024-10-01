---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-09-24T21:07:15.691Z
updated: 2024-09-30T23:07:57.144Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52687750468_dc6bdda141_o-19.jpg
---

## Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111967/7443" target="_top" id="2111967">
  <img src="//a.impactradius-go.com/display-ad/7443-2111967" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111967/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-capture-peak-performance-high-end-webcams-for-quality-live-streams-on-twitch/"><u>[Updated] 2024 Approved Capture Peak Performance High-End Webcams for Quality Live Streams on Twitch</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mastery-of-viewership-hierarchy-key-aspects-examined/"><u>[Updated] Mastery of Viewership Hierarchy Key Aspects Examined</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pro-vs-pop-analyzing-gopro-and-polaroids-video-capabilities-for-2024/"><u>[Updated] Pro Vs. Pop Analyzing GoPro and Polaroid's Video Capabilities for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-capturing-moments-expert-tips-on-downloading-social-media-lives/"><u>2024 Approved Capturing Moments Expert Tips on Downloading Social Media Lives</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-a2-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi A2 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-ipad-or-apple-iphone-14-pro-stuck-on-activation-lock-by-drfone-ios/"><u>How to Fix iPad or Apple iPhone 14 Pro Stuck On Activation Lock?</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-xiaomi-14-pro-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Xiaomi 14 Pro Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-plus-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 Plus To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xr-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone XR to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-earning-on-youtube-a-step-by-step-guide-for-newbies/"><u>In 2024, Earning on YouTube A Step-by-Step Guide for Newbies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-realme-c67-4g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Realme C67 4G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/optimize-your-device-now-download-the-new-lenovo-t450-drivers-today/"><u>Optimize Your Device Now! Download the New Lenovo T450 Drivers Today</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Data From iOS iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-p55plus-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from P55+</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-honor-90-pro-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Honor 90 Pro password or pattern lock</u></a></li>
</ul></div>

