---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-09-17T16:22:18.863Z
updated: 2024-09-18T19:16:16.435Z
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

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-mastering-engagement-a-compendium-of-the-top-20-youtube-hacks/"><u>[New] 2024 Approved Mastering Engagement A Compendium of the Top 20 YouTube Hacks</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-androids-creme-de-la-creme-for-fast-vid-fixing/"><u>[Updated] In 2024, Android's Crème De La Crème for Fast Vid Fixing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-superior-visual-treatment-applying-filters-to-videos/"><u>[Updated] Superior Visual Treatment Applying Filters to Videos</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-from-glitch-to-glory-how-to-reset-final-cut-pro-x-and-resolve-issues/"><u>2024 Approved From Glitch to Glory How to Reset Final Cut Pro X and Resolve Issues</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1725290011854-digiarty-winx-dvd-faq/"><u>Digiarty WinX DVDソフトウェア:一般的なお問い合わせへの回答 - 「よくある質問(FAQ)」</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/early-release-google-unveils-pixel-9-pro-surprisingly-sooner-than-expected/"><u>Early Release: Google Unveils Pixel 9 Pro Surprisingly Sooner than Expected</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-tecno-pova-5-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Tecno Pova 5 Phone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-samsung-vs-lg-battle-of-360-degree-cameras/"><u>In 2024, Samsung Vs LG Battle of 360-Degree Cameras</u></a></li>
<li><a href="https://techidaily.com/introducing-the-gemini-nano-ai-elevating-smartphone-capabilities-in-googles-new-pixel-model/"><u>Introducing the Gemini Nano AI: Elevating Smartphone Capabilities in Google's New Pixel Model</u></a></li>
<li><a href="https://techidaily.com/meet-the-upgraded-bing-chatbot-advanced-search-features-and-elevated-usage-restrictions-now-available/"><u>Meet the Upgraded Bing Chatbot: Advanced Search Features & Elevated Usage Restrictions Now Available</u></a></li>
<li><a href="https://techidaily.com/monthly-virtual-reality-game-selections-with-meta-quests-latest-membership-plan/"><u>Monthly Virtual Reality Game Selections with Meta Quest's Latest Membership Plan</u></a></li>
<li><a href="https://techidaily.com/next-steps-for-amazon-starlink-entering-the-protoflight-phase-of-development/"><u>Next Steps for Amazon Starlink: Entering the Protoflight Phase of Development</u></a></li>
<li><a href="https://techidaily.com/next-summer-release-anticipated-launch-of-the-ford-explorer-electric-vehicle/"><u>Next Summer Release: Anticipated Launch of the Ford Explorer Electric Vehicle</u></a></li>
<li><a href="https://buynow-help.techidaily.com/uncover-the-toughness-of-the-budget-friendly-coolpix-w100/"><u>Uncover the Toughness of the Budget-Friendly Coolpix W100</u></a></li>
</ul></div>

