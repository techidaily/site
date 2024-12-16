---
title: "Mastering Minimalism: Steps to Remove the Taskbar in Windows 11 Setup"
date: 2024-12-10T23:00:04.521Z
updated: 2024-12-15T19:50:44.797Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d10946fd797c909f3b766507ccc413e54b73231c6b47eda0442887da93806c3f.jpg
---

## Mastering Minimalism: Steps to Remove the Taskbar in Windows 11 Setup

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

 You can also right-click the taskbar and select "Taskbar Settings" to access the same Settings window, if you prefer that.

![Right-click the taskbar, then select 'Taskbar Settings.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/taskbar-settings-on-taskbar.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

 You can undo these settings by toggling the sliders back to the "Off" position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Command Prompt, run this command to toggle the taskbar automatically hide option to on:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to on from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-on-from-command-prompt.png) 

 And to toggle the taskbar auto-hide option to off, run this command:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=2;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to off from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-off-from-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Hide Taskbar with a PowerShell Command

 You may have noticed that the command we used in Command Prompt actually invoked PowerShell first. You can skip the middleman and just run it with PowerShell directly, if you want.

 Search for "PowerShell" in the Start menu search, then launch it. It doesn't need to be run as administrator, but it won't hurt anything if you do.

![Search for 'powershell' in the Start menu search bar, then click "Open' or 'Run as Administrator.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/launch-powershell.png) 

 To auto-hide your taskbar, copy and paste the following command into PowerShell:

$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer

![The command to auto-hide the taskbar in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/powershell-command.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/new-essential-tips-for-fbx-based-game-recording-for-2024/"><u>[New] Essential Tips for FBX-Based Game Recording for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-spread-the-rhythm-sharing-playlists-in-minutes/"><u>[Updated] Spread the Rhythm Sharing Playlists in Minutes</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-infinix-gt-10-pro-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-realme-10t-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Realme 10T 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://solve-hot.techidaily.com/five-proven-fixes-for-when-your-onedrive-videos-wont-start-step-by-step-instructions/"><u>Five Proven Fixes for When Your OneDrive Videos Won't Start: Step-by-Step Instructions</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-screen-tearing-issues-on-pc/"><u>Fix Screen Tearing Issues on PC</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209560312-9781507210239-friendship-signs/"><u>Friendship Signs | Free Book</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oneplus-11r-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an OnePlus 11R Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-discover-the-power-of-panasonics-hx-a1-actioncam/"><u>In 2024, Discover the Power of Panasonic's HX-A1 ActionCam</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-honor-90-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Honor 90 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-ultimate-hue-harmonizer-software/"><u>In 2024, Ultimate Hue Harmonizer Software</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/prime-day-prep-discover-the-ultimate-budget-friendly-lenovo-and-dell-alternative-for-your-2-in-1-laptop-needs-on-zdnet/"><u>Prime Day Prep: Discover the Ultimate, Budget-Friendly Lenovo & Dell Alternative for Your 2-in-1 Laptop Needs on ZDNET!</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-lava-blaze-2-pro-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Lava Blaze 2 Pro</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-sony-xperia-5-v-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Sony Xperia 5 V Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/update-your-hardware-drivers-with-device-manager-in-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Update your hardware drivers with Device Manager in Windows 11 & 10 & 7</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-your-drivers-on-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to update your drivers on Windows 11/10/7</u></a></li>
</ul></div>

