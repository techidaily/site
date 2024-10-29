---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-10-22T18:54:57.328Z
updated: 2024-10-29T16:30:45.154Z
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
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1959707/19272" target="_top" id="1959707">
  <img src="//a.impactradius-go.com/display-ad/19272-1959707" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959707/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-transform-your-content-reach-with-strategic-tagging-insight/"><u>[New] In 2024, Transform Your Content Reach with Strategic Tagging Insight</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-proven-pathway-to-pure-sound/"><u>[Updated] 2024 Approved Proven Pathway to Pure Sound</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-sharpening-vision-in-depth-hdr-techniques-in-photoshop/"><u>[Updated] Sharpening Vision In-Depth HDR Techniques in PhotoShop</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/st-youtube-music-reaction-video-and-how-to-make-one/"><u>10 Best YouTube Music Reaction Video & How to Make One</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-mastering-mini-gaming-memories-learn-to-record-minecraft-on-apple-devices/"><u>2024 Approved Mastering Mini-Gaming Memories Learn to Record Minecraft on Apple Devices</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721467603043-are-your-iphone-pictures-really-gone-forever-discover-8-solutions/"><u>Are Your iPhone Pictures Really Gone Forever? Discover 8 Solutions!</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-itel-a60-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Itel A60 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/different-versions-of-windowed-movie-crafting/"><u>Different Versions of Windowed Movie Crafting</u></a></li>
<li><a href="https://win-answers.techidaily.com/essential-tips-for-resolving-armored-core-6-fires-of-rubicon-pc-game-crashes-and-freezes/"><u>Essential Tips for Resolving Armored Core 6 (Fires of Rubicon) PC Game Crashes & Freezes</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-6-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 6 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/picture-paradise-expertly-selected-plugins-and-sites-for-frame-upgrades-for-2024/"><u>Picture Paradise Expertly Selected Plugins & Sites for Frame Upgrades for 2024</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-oppo-find-n3-flip-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-nokia-g22-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Nokia G22 | Dr.fone</u></a></li>
</ul></div>

