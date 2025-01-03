---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-12-28T05:45:30.498Z
updated: 2025-01-03T03:00:02.033Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52687750468_dc6bdda141_o-19.jpg
---

## Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-in-2024-the-insiders-guide-to-crafting-insta-tones/"><u>[New] In 2024, The Insider's Guide to Crafting Insta Tones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-10-highly-trusted-free-video-communication-tools-with-security-features/"><u>[Updated] 2024 Approved 10 Highly-Trusted Free Video Communication Tools with Security Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-a-step-by-step-guide-to-posting-on-instagram-for-2024/"><u>[Updated] A Step-by-Step Guide to Posting on Instagram for 2024</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-itel-p40plus-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Itel P40+ Hard Reset | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/go-big-or-go-home-selecting-the-most-satisfying-1tbplus-cloud-services-for-2024/"><u>Go Big or Go Home - Selecting the Most Satisfying 1TB+ Cloud Services for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/how-does-photodna-thwart-digital-image-theft/"><u>How Does PhotoDNA Thwart Digital Image Theft?</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-pop-7-pro-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Pop 7 Pro in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-samsung-galaxy-s23-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Samsung Galaxy S23 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Infinix Hot 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-7-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 7 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862695493-huge-savings-opportunity-snag-an-alienware-m18-r2-laptop-powered-by-rtx-4090-for-700-less/"><u>Huge Savings Opportunity: Snag an Alienware M18 R2 Laptop Powered by RTX 4090 for $700 Less</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-hits-and-misses-the-photographers-account/"><u>In 2024, Hits and Misses The Photographer's Account</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-y100-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Y100 5G</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/revolutionize-your-click-experience-ranking-the-best-wireless-mice-innovations-of-2024/"><u>Revolutionize Your Click Experience: Ranking the Best Wireless Mice Innovations of 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/the-ultimate-method-for-resetting-and-deleting-iphone-data-safely/"><u>The Ultimate Method for Resetting and Deleting iPhone Data Safely</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-infinix-hot-40i-by-fonelab-android-recover-data/"><u>The way to get back lost data from Infinix Hot 40i</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-honor-magic5-ultimate-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Honor Magic5 Ultimate</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-itel-a60s-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Itel A60s.</u></a></li>
</ul></div>

