---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-09-22T21:20:50.440Z
updated: 2024-09-24T17:21:53.365Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

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
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-text-transformation-tactics-for-images/"><u>[New] 2024 Approved Text Transformation Tactics for Images</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-unlock-iphonepcs-full-potential-with-these-top-8-converters/"><u>[New] In 2024, Unlock iPhone/PC's Full Potential With These Top 8 Converters</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-steps-for-a-smooth-experience-with-the-windows-11-photos-app/"><u>[Updated] 2024 Approved Steps for a Smooth Experience with the Windows 11 Photos App</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-infinix-smart-7-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Infinix Smart 7 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/like-a-championtop-strategies-for-beginner-youtubers/"><u>Edit Like a Champion—Top Strategies for Beginner YouTubers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-find-and-install-the-correct-canon-pixma-mx490-drivers-for-your-windows-machine/"><u>How to Find and Install the Correct Canon PIXMA MX490 Drivers for Your Windows Machine</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-oneplus-nord-n30-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on OnePlus Nord N30 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-6-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 6 Plus without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-x50-gt-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor X50 GT to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/leap-forward-with-xsplits-substitute-software/"><u>Leap Forward with Xsplit's Substitute Software</u></a></li>
<li><a href="https://win-answers.techidaily.com/prevent-and-solve-your-pcs-counter-strike-2-game-crashing-woes-latest-tricks/"><u>Prevent and Solve Your PC's Counter-Strike 2 Game Crashing Woes - Latest Tricks</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-the-graphic-error-in-destiny-2-a-comprehensive-walkthrough-for-gamers/"><u>Resolved the Graphic Error in Destiny 2 - A Comprehensive Walkthrough for Gamers</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-a24-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy A24 Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/unlock-locked-iphone-13-pro-max-without-passcode-or-face-id-by-drfone-ios-unlock-ios-unlock/"><u>Unlock locked iPhone 13 Pro Max without Passcode or Face ID</u></a></li>
</ul></div>

