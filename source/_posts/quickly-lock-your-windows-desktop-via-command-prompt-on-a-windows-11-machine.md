---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-09-01T02:16:59.912Z
updated: 2024-09-02T02:16:59.912Z
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-essential-steps-for-resizing-videos-in-igtv/"><u>[New] 2024 Approved  Essential Steps for Resizing Videos in IGTV</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-essential-techniques-for-sizing-up-your-instagram-video-reach/"><u>[New] 2024 Approved  Essential Techniques for Sizing Up Your Instagram Video Reach</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-behind-the-scenes-look-at-creating-dynamic-facebook-reels/"><u>[New] In 2024, Behind-the-Scenes Look at Creating Dynamic Facebook Reels</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-tweeted-timelines-a-complete-guide-to-video-backups-for-2024/"><u>[New] Tweeted Timelines  A Complete Guide to Video Backups for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-digital-fortune-makers-top-earning-youtubers/"><u>[Updated] Digital Fortune Makers  Top Earning YouTubers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-scripting-signal-sequences/"><u>[Updated] Scripting Signal Sequences</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-unlock-creativity-the-best-collection-of-free-slide-show-patterns/"><u>2024 Approved  Unlock Creativity  The Best Collection of Free Slide Show Patterns</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-a54-5g-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy A54 5G FRP Bypass</u></a></li>
<li><a href="https://techidaily.com/beginning-online-easy-instructions-for-crafting-a-google-id/"><u>Beginning Online: Easy Instructions for Crafting a Google ID</u></a></li>
<li><a href="https://techidaily.com/boost-your-productivity-with-enhanced-precision-upgrading-mouse-sensitivity-and-performance/"><u>Boost Your Productivity with Enhanced Precision: Upgrading Mouse Sensitivity & Performance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-tabletop-adventures-integrating-chatgpt-into-dungeons-and-dragons-gaming/"><u>Boosting Tabletop Adventures: Integrating ChatGPT Into Dungeons & Dragons Gaming</u></a></li>
<li><a href="https://techidaily.com/1723808102827-cant-access-chatgpt-here-are-5-quick-solutions-to-get-it-running-again/"><u>Can't Access ChatGPT? Here Are 5 Quick Solutions To Get It Running Again</u></a></li>
<li><a href="https://techidaily.com/comprehensive-tutorial-how-to-disable-and-rollback-recent-windows-10-patches/"><u>Comprehensive Tutorial: How to Disable and Rollback Recent Windows 10 Patches</u></a></li>
<li><a href="https://techidaily.com/disabling-the-auto-update-feature-for-drivers-in-windows-10-a-comprehensive-guide/"><u>Disabling the Auto-Update Feature for Drivers in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-epson-ds-530-printer-driver-for-windows-11-x64-systems/"><u>Download Epson DS-530 Printer Driver for Windows 11 X64 Systems</u></a></li>
<li><a href="https://techidaily.com/easily-locate-and-launch-the-control-panel-on-your-windows-10-pc/"><u>Easily Locate and Launch the Control Panel on Your Windows 10 PC</u></a></li>
<li><a href="https://techidaily.com/easy-steps-for-swiftly-upgrading-to-windows-11-with-a-clean-slate-setup/"><u>Easy Steps for Swiftly Upgrading to Windows 11 with a Clean Slate Setup!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/efficient-methods-for-sharing-powerful-ppt-in-google-meet-sessions-for-2024/"><u>Efficient Methods for Sharing Powerful PPT in Google Meet Sessions for 2024</u></a></li>
<li><a href="https://techidaily.com/effortless-setup-linking-wireless-headphones-to-your-desktop-computer-on-windows-10/"><u>Effortless Setup: Linking Wireless Headphones to Your Desktop Computer on Windows 10</u></a></li>
<li><a href="https://techidaily.com/elevate-your-roblox-experience-achieve-higher-fps-using-latest-techniques/"><u>Elevate Your Roblox Experience: Achieve Higher FPS Using Latest Techniques</u></a></li>
<li><a href="https://techidaily.com/embark-on-a-lone-quest-with-offline-mode-in-minecraft-for-windows-10-users/"><u>Embark on a Lone Quest with Offline Mode in Minecraft for Windows 10 Users</u></a></li>
<li><a href="https://techidaily.com/essential-techniques-to-refresh-bios-in-a-windows-11-environment/"><u>Essential Techniques to Refresh BIOS in a Windows 11 Environment</u></a></li>
<li><a href="https://techidaily.com/five-effective-methods-to-utilize-the-open-group-policy-editor-in-windows-10/"><u>Five Effective Methods to Utilize the Open Group Policy Editor in Windows 10</u></a></li>
<li><a href="https://techidaily.com/fix-superfetchs-full-disk-utilization-issue-a-complete-guide/"><u>Fix Superfetch's Full Disk Utilization Issue: A Complete Guide</u></a></li>
<li><a href="https://techidaily.com/1723808105093-fixing-a-frozen-windows-update-easily-get-your-system-updating-again/"><u>Fixing a Frozen Windows Update Easily – Get Your System Updating Again</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-the-bad-pool-header-error-on-windows-10-8-and-7-a-comprehensive-guide/"><u>Fixing the 'Bad Pool Header' Error on Windows 10, 8 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://techidaily.com/getting-started-with-fallout-3-compatibility-and-setup-for-windows-11-gaming/"><u>Getting Started with Fallout 3: Compatibility and Setup for Windows 11 Gaming</u></a></li>
<li><a href="https://techidaily.com/how-to-fix-battlenet-slow-download-speed-2024-tips/"><u>How to Fix Battle.net Slow Download Speed – 2024 Tips</u></a></li>
<li><a href="https://techidaily.com/how-to-fix-cd-or-dvd-drive-issue-with-error-code-39/"><u>How to Fix CD or DVD Drive Issue with Error Code 39</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y28-5g-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y28 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-set-up-remote-desktop-on-windows-10/"><u>How to Set up Remote Desktop on Windows 10</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>How to Stop My Spouse from Spying on My Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-turn-your-iphone-into-a-personal-wi-fi-network/"><u>How to Turn Your iPhone Into a Personal Wi-Fi Network</u></a></li>
<li><a href="https://techidaily.com/how-to-use-external-hard-drive-on-ps4/"><u>How to Use External Hard Drive on PS4</u></a></li>
<li><a href="https://fox-that.techidaily.com/imessage-glossary-guide-dealing-with-contacts-showing-as-numbers-not-names/"><u>IMessage Glossary Guide: Dealing with Contacts Showing as Numbers, Not Names</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-asus-rog-phone-7-ultimate-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Asus ROG Phone 7 Ultimate to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808210693-maintenance-therapy-typically-involves-lower-doses-of-steroids-with-azathioprine-or-continued-use-of-mycophenolate-mofetil-to-prevent-relapses/"><u>Maintenance Therapy Typically Involves Lower Doses of Steroids with Azathioprine or Continued Use of Mycophenolate Mofetil to Prevent Relapses.</u></a></li>
<li><a href="https://techidaily.com/master-the-setup-of-logitechs-wireless-keyboards-for-effortless-typing/"><u>Master the Setup of Logitech's Wireless Keyboards for Effortless Typing</u></a></li>
<li><a href="https://techidaily.com/online-consumer-protection-strategies-for-a-risk-free-digital-shopping-experience/"><u>Online Consumer Protection: Strategies for a Risk-Free Digital Shopping Experience</u></a></li>
<li><a href="https://techidaily.com/overcome-slowness-in-windows-11-with-these-effective-8-step-solutions/"><u>Overcome Slowness in Windows 11 with These Effective 8-Step Solutions</u></a></li>
<li><a href="https://techidaily.com/overcoming-format-errors-in-windows-ensuring-a-successful-drive-preparation/"><u>Overcoming Format Errors in Windows: Ensuring a Successful Drive Preparation</u></a></li>
<li><a href="https://techidaily.com/quick-guide-to-turning-off-driver-signature-protection-in-windows-10/"><u>Quick Guide to Turning Off Driver Signature Protection in Windows 10</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-honor-100-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Honor 100 Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/revamp-your-streaming-experience-changing-netflix-regions-made-easy/"><u>Revamp Your Streaming Experience: Changing Netflix Regions Made Easy!</u></a></li>
<li><a href="https://techidaily.com/seamless-setup-how-to-pair-a-ds4-wireless-controller-with-ps4/"><u>Seamless Setup: How to Pair a DS4 Wireless Controller with PS4</u></a></li>
<li><a href="https://techidaily.com/simple-guide-capturing-screen-images-effortlessly-on-your-asus-computer/"><u>Simple Guide: Capturing Screen Images Effortlessly on Your ASUS Computer</u></a></li>
<li><a href="https://techidaily.com/simple-solution-resolving-lag-issues-with-your-logitech-keyboard/"><u>Simple Solution: Resolving Lag Issues with Your Logitech Keyboard</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-accessing-the-bios-menu-in-windows-107/"><u>Step-by-Step Guide: Accessing the BIOS Menu in Windows 10/7</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamline-your-workflow-must-know-win-10-tactics-for-2024/"><u>Streamline Your Workflow  Must-Know Win 10 Tactics for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-vivo-s17e-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Vivo S17e Device</u></a></li>
<li><a href="https://facebook.techidaily.com/the-line-between-satire-and-misinformation/"><u>The Line Between Satire & Misinformation</u></a></li>
<li><a href="https://techidaily.com/the-ultimate-guide-understanding-the-benefits-of-using-a-vpn/"><u>The Ultimate Guide: Understanding the Benefits of Using a VPN</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-rated-group-chat-and-conference-calls-applications/"><u>Top-Rated Group Chat & Conference Calls Applications</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722973653860-toshiba-copier-drivers-downloads-for-windows-users-fast-and-easy-setup/"><u>Toshiba Copier Drivers Downloads for Windows Users - Fast and Easy Setup!</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-like-a-pro-effective-hard-restart-techniques-for-windows-10-users/"><u>Troubleshooting Like a Pro: Effective Hard Restart Techniques for Windows 10 Users</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-tips-for-cddvd-device-malfunctions-and-overcoming-error-39/"><u>Troubleshooting Tips for CD/DVD Device Malfunctions and Overcoming Error 39</u></a></li>
<li><a href="https://techidaily.com/ultimate-tutorial-gaining-full-access-with-the-command-prompt-in-windows-through-admin-rights/"><u>Ultimate Tutorial: Gaining Full Access with the Command Prompt in Windows Through Admin Rights</u></a></li>
<li><a href="https://techidaily.com/understanding-random-password-generators-a-comprehensive-guide-on-functionality-and-application/"><u>Understanding Random Password Generators: A Comprehensive Guide on Functionality & Application</u></a></li>
<li><a href="https://techidaily.com/windows-10-tweaks-and-tips-for-a-superior-gaming-setup-enhance-your-play-today/"><u>Windows 10 Tweaks and Tips for a Superior Gaming Setup – Enhance Your Play Today!</u></a></li>
<li><a href="https://techidaily.com/windows-users-unite-mastering-graphics-driver-resets-in-11-10-and-7/"><u>Windows Users Unite! Mastering Graphics Driver Resets in 11, 10 & 7</u></a></li>
</ul></div>
