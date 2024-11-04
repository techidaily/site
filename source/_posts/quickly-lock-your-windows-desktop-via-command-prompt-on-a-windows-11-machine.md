---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-10-30T02:25:15.278Z
updated: 2024-11-04T07:44:42.279Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/updated-in-2024-unlocking-visual-clarity-bypassing-background-in-photopea/"><u>[Updated] In 2024, Unlocking Visual Clarity Bypassing Background in Photopea</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-depth-giroptic-360-angle-reviews/"><u>[Updated] In-Depth Giroptic 360-Angle Reviews</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-select-12-high-tech-action-cams-with-added-geo-location-features/"><u>[Updated] Select 12 High-Tech Action Cams with Added Geo Location Features</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-choosing-the-right-gimbal-for-flawless-youtube-footage/"><u>2024 Approved Choosing the Right Gimbal for Flawless YouTube Footage</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-oppo-k11-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Oppo K11 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-samsung-galaxy-a14-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Samsung Galaxy A14 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-8-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-motorola-moto-g73-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Motorola Moto G73 5G phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xr-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XR To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-getting-to-grips-with-graphic-animation-basics/"><u>In 2024, Getting to Grips with Graphic Animation Basics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-vivo-y36i-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Vivo Y36i to Apple TV | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-the-comparative-guide-to-content-mastery-on-youtube/"><u>In 2024, The Comparative Guide to Content Mastery on YouTube</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-infinix-gt-10-pro-by-fonelab-android-recover-music/"><u>The way to get back lost music from Infinix GT 10 Pro</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-oppo-reno-10-5g-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Oppo Reno 10 5G without backup.</u></a></li>
<li><a href="https://win-dash.techidaily.com/trouble-free-setup-of-hp-beats-audio-drivers-across-windows-platforms-windows-1087-expert-advice-and-tips/"><u>Trouble-Free Setup of HP Beats Audio Drivers Across Windows Platforms (Windows 10/8/7): Expert Advice and Tips</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-your-hardware-drivers-on-windows-11-by-drivereasy-guide/"><u>Use Device Manager to reinstall your hardware drivers on Windows 11</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-honor-play-8t-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Honor Play 8T on Windows?</u></a></li>
</ul></div>

