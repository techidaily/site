---
title: "Mastering Minimalism: Steps to Remove the Taskbar in Windows 11 Setup"
date: 2024-12-28T16:52:29.817Z
updated: 2025-01-01T21:53:25.832Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d10946fd797c909f3b766507ccc413e54b73231c6b47eda0442887da93806c3f.jpg
---

## Mastering Minimalism: Steps to Remove the Taskbar in Windows 11 Setup

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Automatically Hide the Taskbar in Settings](https://screen-video-capture.techidaily.com/new-2024-approved-capturing-every-moment-with-switch-hd-tech/)
* [Automatically Hide the Taskbar Using Command Prompt](https://instagram-videos.techidaily.com/updated-in-2024-achieve-flawless-video-for-instagram-perfection/)
* [Hide Taskbar with a PowerShell Command](https://some-techniques.techidaily.com/updated-excellence-in-video-selecting-peak-frame-rates-for-slow-motion-effects/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Your taskbar will now automatically hide. This means that, unless you get a notification from an app in the taskbar or you hover your mouse over where the taskbar should be, it won't show up.

**![GIF showing the taskbar auto hiding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/GIF-showing-the-taskbar-auto-hiding.gif)** 

 You can undo these settings by toggling the sliders back to the "Off" position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Automatically Hide the Taskbar Using Command Prompt

 If you're feeling like a hacker, you can also toggle the auto-hide option between on and off by running [commands using the Command Prompt](https://some-knowledge.techidaily.com/how-to-leverage-slug-lines-in-articles-for-2024/).

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing "command prompt" in the Windows Search bar and then select the "Command Prompt" app from the search results.

![Search 'command prompt' in the Start menu search, then open the result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/run-command-prompt.png) 

 In Command Prompt, run this command to toggle the taskbar automatically hide option to on:

powershell -command "&{$p='HKCU:SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3';$v=(Get-ItemProperty -Path $p).Settings;$v[8]=3;&Set-ItemProperty -Path $p -Name Settings -Value $v;&Stop-Process -f -ProcessName explorer}"

![toggle autohide option to on from command prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/06/toggle-autohide-option-to-on-from-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-precision-in-recordings-discover-the-best-10-free-slack-apps/"><u>[New] In 2024, Precision in Recordings Discover the Best 10 Free Slack Apps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-six-winning-strategies-to-recording-and-saving-mov-on-windows-11/"><u>[New] Six Winning Strategies to Recording and Saving .mov on Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ocial-media-integration-for-amplified-youtube-shorts-reach/"><u>[New] Social Media Integration for Amplified YouTube Shorts Reach</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-scaling-success-the-tactics-for-increasing-youtube-audiences/"><u>[Updated] 2024 Approved Scaling Success The Tactics for Increasing YouTube Audiences</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-harmonizing-your-calendar-with-zoom-appointments-on-all-screens/"><u>[Updated] In 2024, Harmonizing Your Calendar With Zoom Appointments on All Screens</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-streamlining-video-content-in-zoom-with-custom-filters/"><u>2024 Approved Streamlining Video Content in Zoom With Custom Filters</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-xiaomi-redmi-note-13-pro-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Xiaomi Redmi Note 13 Pro 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/coherent-and-curated-youtube-playlists-online-and-mobile-assembly-guide/"><u>Coherent and Curated YouTube Playlists Online & Mobile Assembly Guide</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-oneplus-nord-3-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for OnePlus Nord 3 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-vivo-y100i-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Vivo Y100i Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-xiaomi-redmi-a2-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Xiaomi Redmi A2 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-htc-u23-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-mini-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 mini iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-mini-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 mini To Other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-tecno-pova-6-pro-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Tecno Pova 6 Pro 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/the-ultimate-guide-for-amateurs-and-pros-on-windows-11-video-creation/"><u>The Ultimate Guide for Amateurs & Pros on Windows 11 Video Creation</u></a></li>
</ul></div>

