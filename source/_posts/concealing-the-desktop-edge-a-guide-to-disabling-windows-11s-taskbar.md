---
title: "Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar"
date: 2024-09-30T05:21:24.654Z
updated: 2024-10-06T11:38:44.247Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ff400978108e83c0a6a7c70de81b2956e47e27eb0d08af1f2750035e91422572.jpg
---

## Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar

### Quick Links

* [Automatically Hide the Taskbar in Settings](https://screen-video-capture.techidaily.com/new-2024-approved-capturing-every-moment-with-switch-hd-tech/)
* [Automatically Hide the Taskbar Using Command Prompt](https://instagram-videos.techidaily.com/updated-in-2024-achieve-flawless-video-for-instagram-perfection/)
* [Hide Taskbar with a PowerShell Command](https://some-techniques.techidaily.com/updated-excellence-in-video-selecting-peak-frame-rates-for-slow-motion-effects/)

### Key Takeaways

* You can save screen space by automatically hiding the taskbar on Windows 10.
* To hide the taskbar, right-click empty space on your desktop, then go to Personalization > Taskbar, and enable the toggle next to "Automatically Hide."
* Alternatively, you can use the Command Prompt or PowerShell to toggle the auto-hide option.

 The [Windows taskbar](https://remote-screen-capture.techidaily.com/updated-your-essential-guide-to-unmissable-gaming-adventures-for-2024/) is great for quickly accessing frequently used applications on your computer. However, some users prefer to hide it in order to save screen space. Here's how to hide the taskbar on Windows 10.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar in Settings

 To automatically hide your taskbar, right-click anywhere on your PC's desktop and select "Personalize" from the pop-up menu.

![Right-click empty space on your desktop, then select 'Personalize.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/right-click-personalize.png) 

 The "Settings" window will appear. In the left-hand pane, select "Taskbar." From here, toggle the slider to "On" under "Automatically Hide The Taskbar In Desktop Mode." If your PC is able to switch over to tablet mode, you can hide the taskbar by toggling that option to "On," as well.

![Select the 'Taskbar' tab, then enable 'Automatically hide the taskbar in desktop mode' and 'automatically hide the taskbar in tablet mode.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings.png) 

 You can also right-click the taskbar and select "Taskbar Settings" to access the same Settings window, if you prefer that.

![Right-click the taskbar, then select 'Taskbar Settings.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings-on-taskbar.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can undo these settings by toggling the sliders back to the "Off" position.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

 In Command Prompt, run this command to toggle the taskbar automatically hide option to on:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to on from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-on-from-command-prompt.png) 

 And to toggle the taskbar auto-hide option to off, run this command:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to off from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-off-from-command-prompt.png) 

##  Hide Taskbar with a PowerShell Command

 You may have noticed that the command we used in Command Prompt actually invoked PowerShell first. You can skip the middleman and just run it with PowerShell directly, if you want.

 Search for "PowerShell" in the Start menu search, then launch it. It doesn't need to be run as administrator, but it won't hurt anything if you do.

![Search for 'powershell' in the Start menu search bar, then click "Open' or 'Run as Administrator.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/launch-powershell.png) 

 To auto-hide your taskbar, copy and paste the following command into PowerShell:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![The command to auto-hide the taskbar in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/powershell-command.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151855/7443" target="_top" id="2151855">
  <img src="//a.impactradius-go.com/display-ad/7443-2151855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151855/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable your taskbar, you need to change "$v\[8\]=3" to "$v\[8\]=2" instead. Your complete command will look like this:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![Re-enable the taskbar through PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/reenable.png) 

 If you just don't like how the taskbar looks, you may want to try [customizing the taskbar](https://remote-screen-capture.techidaily.com/updated-your-essential-guide-to-unmissable-gaming-adventures-for-2024/) instead of hiding it. There are even third-party apps, like [Start11](https://www.stardock.com/products/start11/), that give you even more granular control.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-navigating-virtual-meeting-platforms-zooming-onto-your-android/"><u>[New] 2024 Approved Navigating Virtual Meeting Platforms Zooming Onto Your Android</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-the-elite-circle-of-online-av-masters-for-2024/"><u>[New] The Elite Circle of Online AV Masters for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ultimate-list-of-non-fbx-game-recording-solutions/"><u>[New] Ultimate List of Non-FBX Game Recording Solutions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-mastering-video-capture-in-adobe-presenter/"><u>[Updated] 2024 Approved Mastering Video Capture in Adobe Presenter</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-crafting-a-visual-identity-a-guide-to-perfect-pfp-on-discord/"><u>[Updated] In 2024, Crafting a Visual Identity A Guide to Perfect Pfp on Discord</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mixing-made-easy-free-luts-bundle-includes-dji-miniair-2/"><u>[Updated] Mixing Made Easy Free LUTS Bundle Includes DJI Mini/Air 2</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-chuckle-forge-mutant-comedy-creatures/"><u>2024 Approved Chuckle Forge Mutant Comedy Creatures</u></a></li>
<li><a href="https://youtube-data.techidaily.com/te-narrative-flow-expert-tips-on-using-jump-cuts/"><u>Elevate Narrative Flow Expert Tips on Using Jump Cuts</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-from-apple-iphone-13-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data from Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-vivo-y36-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Vivo Y36</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-honor-x50i-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Honor X50i</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-htc-u23-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from HTC U23</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-docm-file-documents-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>The best electronic signature way to sign .docm file documents online</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-motorola-defy-2-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Motorola Defy 2</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-infinix-smart-8-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Infinix Smart 8</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-slow-motion-video-editors-to-look-out-for-for-2024/"><u>Updated Slow Motion Video Editors To Look Out For for 2024</u></a></li>
</ul></div>

