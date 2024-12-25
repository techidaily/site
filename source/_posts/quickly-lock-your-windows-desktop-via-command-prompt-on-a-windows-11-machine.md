---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-12-19T22:07:55.639Z
updated: 2024-12-24T17:11:04.866Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-enhancing-engagement-the-art-of-animated-fb-advertising/"><u>[New] 2024 Approved Enhancing Engagement The Art of Animated FB Advertising</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-building-brands-earning-dollars-a-comprehensive-guide-to-insta-sponsorships/"><u>[New] In 2024, Building Brands, Earning Dollars A Comprehensive Guide to Insta-Sponsorships</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-optimizing-video-clarity-with-youtube-tools/"><u>[New] Optimizing Video Clarity with YouTube Tools</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-the-ultimate-guide-to-sourcing-premium-background-images-for-2024/"><u>[Updated] The Ultimate Guide to Sourcing Premium Background Images for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-eliminate-blur-in-zoom-calls-actionable-strategies/"><u>2024 Approved Eliminate Blur in Zoom Calls – Actionable Strategies</u></a></li>
<li><a href="https://win-bits.techidaily.com/complete-windows-11-user-manual-expert-advice-for-a-smooth-upgrade-with-insights-from-zdnet/"><u>Complete Windows 11 User Manual: Expert Advice for a Smooth Upgrade with Insights From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-text-input-experience-integrating-wordpad-triggers-in-windows-11/"><u>Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-s18e-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo S18e phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-x-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone X To Android devices? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-nokia-c02-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Nokia C02</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-15-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 15 Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-realme-c67-5g-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Realme C67 5G</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-12-pro-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from 12 Pro 5G</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722971489756-trouble-free-guide-to-address-your-logitech-c610-headset-driver-glitches-swift-and-straightforward-methods-inside/"><u>Trouble-Free Guide to Address Your Logitech C610 Headset Driver Glitches – Swift & Straightforward Methods Inside</u></a></li>
<li><a href="https://techidaily.com/unable-to-save-excel-2016-workbook-issue-fix-2024-by-stellar-guide/"><u>Unable to Save Excel 2016 Workbook Issue Fix 2024</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-infinix-smart-8-hd-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Infinix Smart 8 HD.</u></a></li>
<li><a href="https://techidaily.com/vivo-data-recovery-recover-lost-data-from-vivo-v29-by-fonelab-android-recover-data/"><u>Vivo Data Recovery – recover lost data from Vivo V29</u></a></li>
</ul></div>

