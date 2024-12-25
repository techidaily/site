---
title: "Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar"
date: 2024-12-19T19:49:49.094Z
updated: 2024-12-24T19:10:03.437Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar in Settings

 To automatically hide your taskbar, right-click anywhere on your PC's desktop and select "Personalize" from the pop-up menu.

![Right-click empty space on your desktop, then select 'Personalize.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/right-click-personalize.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The "Settings" window will appear. In the left-hand pane, select "Taskbar." From here, toggle the slider to "On" under "Automatically Hide The Taskbar In Desktop Mode." If your PC is able to switch over to tablet mode, you can hide the taskbar by toggling that option to "On," as well.

![Select the 'Taskbar' tab, then enable 'Automatically hide the taskbar in desktop mode' and 'automatically hide the taskbar in tablet mode.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings.png) 

 You can also right-click the taskbar and select "Taskbar Settings" to access the same Settings window, if you prefer that.

![Right-click the taskbar, then select 'Taskbar Settings.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings-on-taskbar.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

 You can undo these settings by toggling the sliders back to the "Off" position.

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 If you want to re-enable your taskbar, you need to change "$v\[8\]=3" to "$v\[8\]=2" instead. Your complete command will look like this:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![Re-enable the taskbar through PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/reenable.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-clips.techidaily.com/updated-digital-darlings-facebooks-favorites/"><u>[Updated] Digital Darlings Facebook's Favorites</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-how-to-fix-obs-studio-drop-frames-issue/"><u>[Updated] How To Fix OBS Studio Drop Frames Issue?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-unveiling-the-20-core-strategies-for-effective-facebook-video-ads-for-2024/"><u>[Updated] Unveiling the 20 Core Strategies for Effective Facebook Video Ads for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/asmr-explained-why-it-might-be-good-for-you/"><u>ASMR Explained Why It Might Be Good For You</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/comment-remonter-et-restaurer-une-partition-asus-manquante-methodes-efficaces/"><u>Comment Remonter Et Restaurer Une Partition Asus Manquante - Méthodes Efficaces</u></a></li>
<li><a href="https://article-files.techidaily.com/drone-pilots-guide-to-best-vr-headsets-for-2024/"><u>Drone Pilots' Guide to Best VR Headsets for 2024</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-nokia-g310-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Nokia G310 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-smart-7-hd-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a58-4g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A58 4G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-itel-p40plus-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE To Other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-mini-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 mini to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oneplus-11r-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from OnePlus 11R to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-windows-11s-top-video-capture-tools-essentials-edition/"><u>In 2024, Windows 11'S Top Video Capture Tools Essentials Edition</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-15-pro-data-from-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 15 Pro Data From iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-tecno-pova-5-pro-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Tecno Pova 5 Pro</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-guide-resolving-the-msvcr80dll-is-missing-system-failure/"><u>Ultimate Guide: Resolving the 'Msvcr80.dll Is Missing' System Failure</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-y78plus-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Y78+.</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-xiaomi-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Xiaomi Redmi Note 13 Pro+ 5G ?</u></a></li>
</ul></div>

