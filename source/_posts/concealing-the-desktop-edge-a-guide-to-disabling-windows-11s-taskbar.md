---
title: "Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar"
date: 2024-09-01T02:19:35.542Z
updated: 2024-09-02T02:19:35.542Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
##  Automatically Hide the Taskbar in Settings

 To automatically hide your taskbar, right-click anywhere on your PC's desktop and select "Personalize" from the pop-up menu.

![Right-click empty space on your desktop, then select 'Personalize.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/right-click-personalize.png) 

 The "Settings" window will appear. In the left-hand pane, select "Taskbar." From here, toggle the slider to "On" under "Automatically Hide The Taskbar In Desktop Mode." If your PC is able to switch over to tablet mode, you can hide the taskbar by toggling that option to "On," as well.

![Select the 'Taskbar' tab, then enable 'Automatically hide the taskbar in desktop mode' and 'automatically hide the taskbar in tablet mode.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings.png) 

 You can also right-click the taskbar and select "Taskbar Settings" to access the same Settings window, if you prefer that.

![Right-click the taskbar, then select 'Taskbar Settings.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings-on-taskbar.png) 

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

 You can undo these settings by toggling the sliders back to the "Off" position.

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In Command Prompt, run this command to toggle the taskbar automatically hide option to on:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to on from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-on-from-command-prompt.png) 

 And to toggle the taskbar auto-hide option to off, run this command:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to off from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-off-from-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
##  Hide Taskbar with a PowerShell Command

 You may have noticed that the command we used in Command Prompt actually invoked PowerShell first. You can skip the middleman and just run it with PowerShell directly, if you want.

 Search for "PowerShell" in the Start menu search, then launch it. It doesn't need to be run as administrator, but it won't hurt anything if you do.

![Search for 'powershell' in the Start menu search bar, then click "Open' or 'Run as Administrator.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/launch-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To auto-hide your taskbar, copy and paste the following command into PowerShell:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![The command to auto-hide the taskbar in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/powershell-command.png) 

 If you want to re-enable your taskbar, you need to change "$v\[8\]=3" to "$v\[8\]=2" instead. Your complete command will look like this:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![Re-enable the taskbar through PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/reenable.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guide-youtube-to-mp4-ensuring-data-security/"><u>[New] In 2024, Guide  YouTube to MP4 - Ensuring Data Security</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-strategic-use-of-creative-commons-copyright-law/"><u>[New] In 2024, Strategic Use of Creative Commons Copyright Law</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-igtv-shutdown-for-beginners/"><u>[Updated] In 2024, IGTV Shutdown for Beginners</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-maximizing-impact-uploading-srt-subtitles-to-popular-networks-seamlessly/"><u>2024 Approved  Maximizing Impact  Uploading SRT Subtitles to Popular Networks Seamlessly</u></a></li>
<li><a href="https://techidaily.com/beginning-online-easy-instructions-for-crafting-a-google-id/"><u>Beginning Online: Easy Instructions for Crafting a Google ID</u></a></li>
<li><a href="https://techidaily.com/boost-your-productivity-with-enhanced-precision-upgrading-mouse-sensitivity-and-performance/"><u>Boost Your Productivity with Enhanced Precision: Upgrading Mouse Sensitivity & Performance</u></a></li>
<li><a href="https://techidaily.com/1723808102827-cant-access-chatgpt-here-are-5-quick-solutions-to-get-it-running-again/"><u>Can't Access ChatGPT? Here Are 5 Quick Solutions To Get It Running Again</u></a></li>
<li><a href="https://techidaily.com/comprehensive-tutorial-how-to-disable-and-rollback-recent-windows-10-patches/"><u>Comprehensive Tutorial: How to Disable and Rollback Recent Windows 10 Patches</u></a></li>
<li><a href="https://techidaily.com/disabling-the-auto-update-feature-for-drivers-in-windows-10-a-comprehensive-guide/"><u>Disabling the Auto-Update Feature for Drivers in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://techidaily.com/easily-locate-and-launch-the-control-panel-on-your-windows-10-pc/"><u>Easily Locate and Launch the Control Panel on Your Windows 10 PC</u></a></li>
<li><a href="https://techidaily.com/easy-steps-for-swiftly-upgrading-to-windows-11-with-a-clean-slate-setup/"><u>Easy Steps for Swiftly Upgrading to Windows 11 with a Clean Slate Setup!</u></a></li>
<li><a href="https://techidaily.com/effortless-setup-linking-wireless-headphones-to-your-desktop-computer-on-windows-10/"><u>Effortless Setup: Linking Wireless Headphones to Your Desktop Computer on Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effortless-solutions-to-restore-pubg-voice-chatting-functionality/"><u>Effortless Solutions to Restore PubG Voice Chatting Functionality</u></a></li>
<li><a href="https://techidaily.com/elevate-your-roblox-experience-achieve-higher-fps-using-latest-techniques/"><u>Elevate Your Roblox Experience: Achieve Higher FPS Using Latest Techniques</u></a></li>
<li><a href="https://techidaily.com/embark-on-a-lone-quest-with-offline-mode-in-minecraft-for-windows-10-users/"><u>Embark on a Lone Quest with Offline Mode in Minecraft for Windows 10 Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/embracing-digital-transformation-the-emergence-of-abbyys-process-digital-twin/"><u>Embracing Digital Transformation: The Emergence of ABBYY's Process Digital Twin</u></a></li>
<li><a href="https://techidaily.com/essential-techniques-to-refresh-bios-in-a-windows-11-environment/"><u>Essential Techniques to Refresh BIOS in a Windows 11 Environment</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/first-look-at-organizing-zoom-session-rooms/"><u>First Look at Organizing Zoom Session Rooms</u></a></li>
<li><a href="https://techidaily.com/five-effective-methods-to-utilize-the-open-group-policy-editor-in-windows-10/"><u>Five Effective Methods to Utilize the Open Group Policy Editor in Windows 10</u></a></li>
<li><a href="https://techidaily.com/fix-superfetchs-full-disk-utilization-issue-a-complete-guide/"><u>Fix Superfetch's Full Disk Utilization Issue: A Complete Guide</u></a></li>
<li><a href="https://techidaily.com/1723808105093-fixing-a-frozen-windows-update-easily-get-your-system-updating-again/"><u>Fixing a Frozen Windows Update Easily – Get Your System Updating Again</u></a></li>
<li><a href="https://techidaily.com/getting-started-with-fallout-3-compatibility-and-setup-for-windows-11-gaming/"><u>Getting Started with Fallout 3: Compatibility and Setup for Windows 11 Gaming</u></a></li>
<li><a href="https://techidaily.com/how-to-fix-battlenet-slow-download-speed-2024-tips/"><u>How to Fix Battle.net Slow Download Speed – 2024 Tips</u></a></li>
<li><a href="https://techidaily.com/how-to-fix-cd-or-dvd-drive-issue-with-error-code-39/"><u>How to Fix CD or DVD Drive Issue with Error Code 39</u></a></li>
<li><a href="https://techidaily.com/how-to-set-up-remote-desktop-on-windows-10/"><u>How to Set up Remote Desktop on Windows 10</u></a></li>
<li><a href="https://techidaily.com/how-to-turn-your-iphone-into-a-personal-wi-fi-network/"><u>How to Turn Your iPhone Into a Personal Wi-Fi Network</u></a></li>
<li><a href="https://techidaily.com/how-to-use-external-hard-drive-on-ps4/"><u>How to Use External Hard Drive on PS4</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-the-ultimate-social-watchlist-2023s-top-tweets/"><u>In 2024, The Ultimate Social Watchlist - 2023'S Top Tweets</u></a></li>
<li><a href="https://techidaily.com/1723808210693-maintenance-therapy-typically-involves-lower-doses-of-steroids-with-azathioprine-or-continued-use-of-mycophenolate-mofetil-to-prevent-relapses/"><u>Maintenance Therapy Typically Involves Lower Doses of Steroids with Azathioprine or Continued Use of Mycophenolate Mofetil to Prevent Relapses.</u></a></li>
<li><a href="https://techidaily.com/master-the-setup-of-logitechs-wireless-keyboards-for-effortless-typing/"><u>Master the Setup of Logitech's Wireless Keyboards for Effortless Typing</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/minimize-mbs-avoid-fb-video-ads-for-2024/"><u>Minimize MBs  Avoid FB Video Ads for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-the-ultimate-guide-to-filmora-discounts-4-top-secrets-revealed/"><u>New 2024 Approved The Ultimate Guide to Filmora Discounts 4 Top Secrets Revealed</u></a></li>
<li><a href="https://techidaily.com/online-consumer-protection-strategies-for-a-risk-free-digital-shopping-experience/"><u>Online Consumer Protection: Strategies for a Risk-Free Digital Shopping Experience</u></a></li>
<li><a href="https://techidaily.com/quick-and-simple-taking-perfect-screenshots-with-windows-11/"><u>Quick and Simple: Taking Perfect Screenshots with Windows 11</u></a></li>
<li><a href="https://techidaily.com/quick-fix-changing-picture-dimensions-on-windowsmac-devices/"><u>Quick Fix: Changing Picture Dimensions on Windows/Mac Devices</u></a></li>
<li><a href="https://techidaily.com/quick-guide-how-to-seamlessly-roll-back-your-pc-from-windows-10s-anniversary-update/"><u>Quick Guide: How to Seamlessly Roll Back Your PC From Windows 10'S Anniversary Update</u></a></li>
<li><a href="https://techidaily.com/re-download-and-setup-of-realtek-hd-sound-driver-for-windows-1011-systems/"><u>Re-Download & Setup of Realtek HD Sound Driver for Windows 10/11 Systems</u></a></li>
<li><a href="https://techidaily.com/rendering-workload/"><u>Rendering Workload</u></a></li>
<li><a href="https://techidaily.com/resolving-windows-10-installation-issue-fix-error-code-80/"><u>Resolving Windows 10 Installation Issue - Fix Error Code 80 #</u></a></li>
<li><a href="https://techidaily.com/seamless-website-translation-swift-conversion-in-chrome-firefox-and-edge/"><u>Seamless Website Translation: Swift Conversion in Chrome, Firefox & Edge</u></a></li>
<li><a href="https://techidaily.com/simple-guide-capturing-images-on-your-pc-using-windows-7/"><u>Simple Guide: Capturing Images on Your PC Using Windows 7</u></a></li>
<li><a href="https://techidaily.com/simple-steps-to-determine-your-current-windows-operating-system/"><u>Simple Steps to Determine Your Current Windows Operating System</u></a></li>
<li><a href="https://techidaily.com/skype-cant-connect-5-ways-to-fix-on-windows-11-easily/"><u>Skype Can't Connect: 5 Ways to Fix on Windows 11 Easily!</u></a></li>
<li><a href="https://techidaily.com/solving-frame-rate-issues-why-do-i-experience-drop-in-frames-per-second-fps-while-playing-diablo-4-on-pc/"><u>Solving Frame Rate Issues: Why Do I Experience Drop in Frames Per Second (FPS) While Playing Diablo 4 on PC?</u></a></li>
<li><a href="https://techidaily.com/ultimate-tutorial-gaining-full-access-with-the-command-prompt-in-windows-through-admin-rights/"><u>Ultimate Tutorial: Gaining Full Access with the Command Prompt in Windows Through Admin Rights</u></a></li>
<li><a href="https://techidaily.com/understanding-random-password-generators-a-comprehensive-guide-on-functionality-and-application/"><u>Understanding Random Password Generators: A Comprehensive Guide on Functionality & Application</u></a></li>
<li><a href="https://techidaily.com/windows-10-tweaks-and-tips-for-a-superior-gaming-setup-enhance-your-play-today/"><u>Windows 10 Tweaks and Tips for a Superior Gaming Setup – Enhance Your Play Today!</u></a></li>
<li><a href="https://techidaily.com/windows-users-unite-mastering-graphics-driver-resets-in-11-10-and-7/"><u>Windows Users Unite! Mastering Graphics Driver Resets in 11, 10 & 7</u></a></li>
</ul></div>
