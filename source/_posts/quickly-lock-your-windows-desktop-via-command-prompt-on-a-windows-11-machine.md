---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-11-27T23:03:46.522Z
updated: 2024-12-02T09:41:02.739Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52687750468_dc6bdda141_o-19.jpg
---

## Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-the-filmmakers-toolbox-in-depth-guide-to-cinematic-techniques-in-24/"><u>[New] 2024 Approved The Filmmaker’s Toolbox In-Depth Guide to Cinematic Techniques in '24</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-ms-edges-picture-in-picture-magic/"><u>[New] Unveiling MS Edge's Picture-in-Picture Magic</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-how-to-optimize-your-content-for-higher-views-and-more-likes/"><u>[Updated] In 2024, How to Optimize Your Content for Higher Views and More 'Likes'</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-premier-webcam-lineup-for-next-gen-windows-pcs-for-2024/"><u>[Updated] The Premier Webcam Lineup for Next-Gen Windows PCs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-tecno-pova-5-pro-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-se-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-oppo-a18-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Oppo A18 Without Password | Dr.fone</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/how-to-restore-your-windows-7-system-after-a-lost-recovery-partition-easy-fixes-and-solutions/"><u>How to Restore Your Windows 7 System After a Lost Recovery Partition - Easy Fixes and Solutions</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-nokia-g22-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-bypassing-the-pin-lock-on-windows-11/"><u>Quick Guide to Bypassing the PIN Lock on WIndows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/savor-sweetness-on-the-go-the-ultimate-guide-to-cookies-for-travelers/"><u>Savor Sweetness on the Go The Ultimate Guide to Cookies for Travelers</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-infinix-hot-40-pro-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Infinix Hot 40 Pro</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-xiaomi-mix-fold-3-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-se-2020-lock-with-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone SE (2020) lock with iCloud</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-drivers-with-windows-device-manager-on-windows-10-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning drivers with Windows Device Manager on Windows 10</u></a></li>
</ul></div>

