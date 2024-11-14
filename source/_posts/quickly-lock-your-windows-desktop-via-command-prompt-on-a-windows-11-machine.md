---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-11-09T16:21:05.384Z
updated: 2024-11-13T16:11:08.614Z
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

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-how-to-record-google-meet-for-free/"><u>[Updated] 2024 Approved How to Record Google Meet for Free?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-diving-deep-into-the-world-of-professional-voice-overs-for-videos/"><u>2024 Approved Diving Deep Into the World of Professional Voice Overs for Videos</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-nokia-c110-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Nokia C110 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-nokia-c02-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Nokia C02 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/fallout-n-forge-a-flawless-gaming-experience-tips-to-stop-your-pc-crashing-mid-game/"><u>Fallout N' Forge a Flawless Gaming Experience - Tips To Stop Your PC Crashing Mid-Game</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-google-pixel-fold-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Google Pixel Fold Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-recovery-mode-on-apple-iphone-11-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-11-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 11 To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-youtube-playlist-creation-tips-and-tricks/"><u>In 2024, Mastering YouTube Playlist Creation Tips and Tricks</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-the-jscriptdll-file-absent-or-lost-issue/"><u>Resolving the 'JScript.dll' File Absent or Lost Issue</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-five-essential-features-desired-in-proton-beyond-artificial-intelligence-and-digital-assets/"><u>Top Five Essential Features Desired in Proton Beyond Artificial Intelligence & Digital Assets</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-realme-v30-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Realme V30 Hard Reset | Dr.fone</u></a></li>
</ul></div>

