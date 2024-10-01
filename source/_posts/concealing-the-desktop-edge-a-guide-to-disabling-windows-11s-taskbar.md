---
title: "Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar"
date: 2024-09-25T18:54:44.874Z
updated: 2024-09-30T19:08:03.154Z
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

##  Automatically Hide the Taskbar in Settings

 To automatically hide your taskbar, right-click anywhere on your PC's desktop and select "Personalize" from the pop-up menu.

![Right-click empty space on your desktop, then select 'Personalize.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/right-click-personalize.png) 

 The "Settings" window will appear. In the left-hand pane, select "Taskbar." From here, toggle the slider to "On" under "Automatically Hide The Taskbar In Desktop Mode." If your PC is able to switch over to tablet mode, you can hide the taskbar by toggling that option to "On," as well.

![Select the 'Taskbar' tab, then enable 'Automatically hide the taskbar in desktop mode' and 'automatically hide the taskbar in tablet mode.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also right-click the taskbar and select "Taskbar Settings" to access the same Settings window, if you prefer that.

![Right-click the taskbar, then select 'Taskbar Settings.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings-on-taskbar.png) 

 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

 You can undo these settings by toggling the sliders back to the "Off" position.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Command Prompt, run this command to toggle the taskbar automatically hide option to on:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to on from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-on-from-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And to toggle the taskbar auto-hide option to off, run this command:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to off from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-off-from-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Hide Taskbar with a PowerShell Command

 You may have noticed that the command we used in Command Prompt actually invoked PowerShell first. You can skip the middleman and just run it with PowerShell directly, if you want.

 Search for "PowerShell" in the Start menu search, then launch it. It doesn't need to be run as administrator, but it won't hurt anything if you do.

![Search for 'powershell' in the Start menu search bar, then click "Open' or 'Run as Administrator.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/launch-powershell.png) 

 To auto-hide your taskbar, copy and paste the following command into PowerShell:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![The command to auto-hide the taskbar in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/powershell-command.png) 

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-loom-studio-sync-screen-record-features-explained/"><u>[New] 2024 Approved Loom Studio Sync Screen Record Features Explained</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-tips-for-easily-accessing-videos-on-facebook/"><u>[New] 2024 Approved Tips for Easily Accessing Videos on Facebook</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-ultimate-flashy-game-collection-quick-and-lightweight/"><u>[New] 2024 Approved Ultimate Flashy Game Collection - Quick and Lightweight</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-organizing-epics-implementing-chapters-in-vimeo-media/"><u>[Updated] 2024 Approved Organizing Epics Implementing Chapters in Vimeo Media</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-maintaining-softness-fading-effects-in-fl-studio-mixes/"><u>[Updated] Maintaining Softness Fading Effects in FL Studio Mixes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-take-full-page-screen-images-for-2024/"><u>[Updated] Take Full-Page Screen Images for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-access-denial-windows-11-graphic-issue/"><u>Device Access Denial - Windows 11 Graphic Issue</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-v29-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-7-to-factory-settings-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Reset Apple iPhone 7 to Factory Settings? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-honor-x50-gt-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Honor X50 GT Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-realme-12-pro-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Realme 12 Pro 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-samsung-galaxy-m54-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Samsung Galaxy M54 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-top-strategies-sharing-youtube-content-on-facebook/"><u>In 2024, Top Strategies Sharing YouTube Content on Facebook</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-lava-storm-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-infinix-hot-30i-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Infinix Hot 30i without backup.</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-vivo-y27-4g-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Vivo Y27 4G.</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-gt-5-pro-by-fonelab-android-recover-video/"><u>Undeleted lost videos from GT 5 Pro</u></a></li>
</ul></div>

