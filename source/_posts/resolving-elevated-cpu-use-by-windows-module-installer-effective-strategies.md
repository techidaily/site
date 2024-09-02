---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-09-01T02:18:07.319Z
updated: 2024-09-02T02:18:07.319Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/786e0982cfdee2d5f20c6d4b4308fc64b7f3b17fc6a8a55e95bfdc13a652344b.jpg
---

## Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies

### Key Takeaways

* Let the Windows Modules Installer Worker process finish running even if it's using a lot of CPU. It will stop working once the update or maintenance task is complete.
* To stop the process as you want to do something on your PC, open Task Manager, access the "Processes" tab, right-click the process, and choose "End Task."
* Other troubleshooting methods include running Windows Update troubleshooter, clearing Windows Update cache and pausing the updates, and running the PC's maintenance tasks at your chosen time.

 Windows Modules Installer Worker (TiWorker.exe) is a normal Windows process related to your PC’s updates and maintenance. However, if it uses up a lot of CPU for an extended period it may be due to an error. Here are some things you can do to fix it.

##  Wait for It to Finish Running

 Windows launches the Windows Modules Installer Worker when there’s an update to install or a PC maintenance task to run. You should generally let the process finish running, even if it’s using up a lot of CPU.

 When the update or maintenance task has finished, the process will stop running.

 If it continues to run for an extended period or you want to perform other tasks, use the troubleshooting tips below.

##  Run Windows Update Troubleshooter

 Windows Modules Installer Worker often runs longer than expected when there is a problem with an update. In this case, run the Windows Update troubleshooter to [find and fix any update problems](https://extra-guidance.techidaily.com/2024-approved-smoothing-out-the-rough-edges-in-photo-booth-videos/).

 Microsoft is phasing out troubleshooters in favor of the Get Help app on Windows 11\. In the future, use that app to resolve issues with your PC.

 If you’re on Windows 11, navigate to Settings > System > Troubleshoot > Other Troubleshooters, then click the "Run" button next to Windows Update.

!['Run' highlighted for 'Windows Update' troubleshooter in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-windows-update-troubleshooter-windows-11.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 On Windows 10, head to Settings > Update & Security > Troubleshoot > Additional Troubleshooters. Select "Windows Update" and click "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for 'Windows Update' troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-windows-update-troubleshooter-windows-10.jpg) 

 Follow the on-screen instructions in the tool to resolve any update issues.

##  Temporarily End the Windows Modules Installer Process

 If you need to perform a task and the Windows Modules Installer Worker process is using up so much CPU that your PC has become unresponsive, you can [temporarily end the process](https://extra-guidance.techidaily.com/updated-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/). We don't recommend you do this unless you have a really need to. 

 To end the process, right-click the Start Menu icon and select "Task Manager." Open the "Processes" tab, right-click "Windows Modules Installer Worker," and select "End Task."

!['End Task' highlighted for 'Windows Modules Installer Worker' in Task Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-end-windows-modules-installer-worker-process.jpg) 

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Clear Windows Update Cache and Pause Updates

 If you want to prevent Windows Modules Installer Worker from running, clear your Windows Update cache and pause the updates. This way, the process won’t have updates to install and won’t be able to check for new updates. 

 We don’t recommend pausing updates as newer updates often bring bug fixes and security patches that improve and safeguard your system.

 To start, open a Run window by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Windows Update." Right-click it and select "Stop."

!['Stop' highlighted for 'Windows Update' on the 'Services' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-stop-windows-update-service.jpg) 

 Open Run again by pressing Windows+R, type the following path in the box, and press Enter:

C:\Windows\SoftwareDistribution\

 Select all files in the folder by pressing Ctrl+A, then right-click a selected file and choose "Delete" (a trash can icon on Windows 11). Make sure to [empty the Recycle Bin](https://some-guidance.techidaily.com/new-the-complete-powerdirector-2024-users-handbook/) as well.

!['Delete' highlighted for Windows Update cache.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-delete-windows-update-cache.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 And that’s all there is to eliminating or reducing Windows Modules Installer Worker’s CPU usage on a Windows computer. It isn't the only process related to Windows Updates that can cause problems, though. There are other [troubleshooting steps you can try if Windows Update is stuck](https://extra-guidance.techidaily.com/2024-approved-smoothing-out-the-rough-edges-in-photo-booth-videos/).

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
<li><a href="https://facebook-record-videos.techidaily.com/new-achieving-youtube-earnings-excellence-strategies-and-beyond-for-2024/"><u>[New] Achieving YouTube Earnings Excellence - Strategies and Beyond for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-latest-pulse-of-facebooks-evolution-for-2024/"><u>[New] Latest Pulse of Facebook's Evolution for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-soundscapes-for-vimeo-a-compreayers-manual/"><u>[New] Soundscapes for Vimeo  A Compreayer's Manual</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweeting-to-whatsapp-direct-video-distribution/"><u>[New] Tweeting to WhatsApp  Direct Video Distribution</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-charting-success-top-15-investment-educational-videos/"><u>[Updated] 2024 Approved  Charting Success  Top 15 Investment Educational Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-creative-commons-chill-vibes/"><u>[Updated] 2024 Approved  Creative Commons Chill Vibes</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-earnings-escalation-leveraging-your-youtube-channel-on-mobile-devices/"><u>[Updated] Earnings Escalation  Leveraging Your YouTube Channel on Mobile Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-reel-it-in-8-online-utilities-for-creating-and-sharing-instagram-videos-for-2024/"><u>[Updated] Reel It In  8 Online Utilities For Creating & Sharing Instagram Videos for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-essentials-of-time-stamped-photography/"><u>[Updated] The Essentials of Time-Stamped Photography</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-cycling-sims-worth-your-time-in-2024/"><u>[Updated] Top Cycling Sims Worth Your Time, In 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-oppo-find-x7-ultra-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Oppo Find X7 Ultra Wont Charge | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-unleash-the-full-potential-of-youtube-videos-with-srt-download-tutorial/"><u>2024 Approved  Unleash the Full Potential of YouTube Videos With SRT Download Tutorial</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/affordable-shutterbug-gear-for-dynamic-action-scenes-for-2024/"><u>Affordable Shutterbug Gear for Dynamic Action Scenes for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-poco-c51-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Poco C51</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://techidaily.com/discover-the-worlds-leading-torrent-platforms-a-comprehensive-top-10-guide/"><u>Discover the World's Leading Torrent Platforms: A Comprehensive Top 10 Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/dissecting-the-mistakes-5-incidents-that-mark-facebooks-record/"><u>Dissecting the Mistakes: 5 Incidents That Mark Facebook’s Record</u></a></li>
<li><a href="https://techidaily.com/effortless-way-to-upgrade-graphics-device-drivers-in-windows-10-system/"><u>Effortless Way to Upgrade Graphics Device Drivers in Windows 10 System</u></a></li>
<li><a href="https://techidaily.com/essential-tips-for-successful-windows-10-os-installation/"><u>Essential Tips for Successful Windows 10 OS Installation</u></a></li>
<li><a href="https://techidaily.com/expert-recommendations-top-video-editors-specially-designed-for-mac-by-apple/"><u>Expert Recommendations: Top Video Editors Specially Designed for Mac by Apple</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/explore-5-premier-mac-cam-recording-software-beyond-bandicam-for-2024/"><u>Explore 5 Premier Mac Cam Recording Software Beyond Bandicam for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/filmfusion-studio-win8/"><u>FilmFusion Studio Win8</u></a></li>
<li><a href="https://techidaily.com/fix-printer-driver-issues-on-windows-11/"><u>Fix Printer Driver Issues on Windows 11</u></a></li>
<li><a href="https://techidaily.com/fixing-an-undetected-sd-card-quick-troubleshooting-steps/"><u>Fixing an Undetected SD Card: Quick Troubleshooting Steps</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-best-pc-gaming-experience-on-windows-download-nvidia-drivers-now/"><u>Get Your Best PC Gaming Experience on Windows: Download Nvidia Drivers Now!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-galaxy-s23-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Galaxy S23?</u></a></li>
<li><a href="https://techidaily.com/how-to-activate-or-deactivate-hibernation-mode-on-your-windows-10-pc/"><u>How to Activate or Deactivate Hibernation Mode on Your Windows 10 PC</u></a></li>
<li><a href="https://techidaily.com/how-to-boost-fps-in-rust/"><u>How to Boost FPS in Rust</u></a></li>
<li><a href="https://techidaily.com/how-to-change-screen-resolution-windows-11-solved/"><u>How to Change Screen Resolution Windows 11 [Solved]</u></a></li>
<li><a href="https://techidaily.com/how-to-connect-laptop-to-tv-with-hdmi-with-pictures/"><u>How to Connect Laptop to TV with HDMI [with Pictures]</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-find-and-install-new-driver-updates-for-windows-10-and-11/"><u>How to Easily Find and Install New Driver Updates for Windows 10 and 11</u></a></li>
<li><a href="https://techidaily.com/how-to-install-inf-drivers-windows-1178xpvista/"><u>How to Install Inf Drivers (Windows 11/7/8/XP/Vista)</u></a></li>
<li><a href="https://techidaily.com/how-to-optimize-minecraft-gameplay-fixing-low-fps-in-the-latest-high-performance-gear/"><u>How to Optimize Minecraft Gameplay: Fixing Low FPS in the Latest High-Performance Gear</u></a></li>
<li><a href="https://techidaily.com/identifying-your-systems-graphics-processing-unit-a-step-by-step-guide/"><u>Identifying Your System's Graphics Processing Unit: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-becoming-a-seo-guru-top-ten-facebook-optimization-tactics/"><u>In 2024, Becoming a SEO Guru  Top Ten Facebook Optimization Tactics</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-direct-tweeting-to-your-facebook-followers/"><u>In 2024, Direct Tweeting to Your Facebook Followers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-the-latest-hp-deskjet-all-in-one-3755-printer-driver-on-windows-11-8-or-7-free-downloads/"><u>Install the Latest HP DeskJet All-in-One 3755 Printer Driver on Windows 11, 8 or 7 - Free Downloads!</u></a></li>
<li><a href="https://techidaily.com/master-playing-games-with-a-ps4-controller-on-steam-a-detailed-tutorial/"><u>Master Playing Games with a PS4 Controller on Steam - A Detailed Tutorial</u></a></li>
<li><a href="https://techidaily.com/mastering-pubg-settings-discover-the-best-techniques-for-a-smoother-gaming-experience-top-7-strategies/"><u>Mastering PUBG Settings: Discover the Best Techniques for a Smoother Gaming Experience (Top 7 Strategies)</u></a></li>
<li><a href="https://techidaily.com/mastering-the-art-of-window-11-screenshotting-tutorials/"><u>Mastering the Art of Window 11 Screenshotting Tutorials</u></a></li>
<li><a href="https://win-amazing.techidaily.com/maximize-audio-fidelity-get-behringer-pro-driver-software-for-free/"><u>Maximize Audio Fidelity: Get [Behringer Pro Driver] Software for Free</u></a></li>
<li><a href="https://techidaily.com/maximize-your-fps-in-fortnite-essential-tips/"><u>Maximize Your FPS in Fortnite - Essential Tips</u></a></li>
<li><a href="https://techidaily.com/maximize-your-pubg-gameplay-top-strategies-to-increase-fps-in-2020/"><u>Maximize Your PUBG Gameplay: Top Strategies to Increase FPS in 2020</u></a></li>
<li><a href="https://techidaily.com/navigating-windows-10-advanced-startup-features-with-minimal-hassle-a-how-to-guide/"><u>Navigating Windows 10 Advanced Startup Features with Minimal Hassle: A How-To Guide</u></a></li>
<li><a href="https://techidaily.com/optimize-and-overclock-the-ultimate-list-of-tricks-to-make-your-laptop-faster/"><u>Optimize and Overclock: The Ultimate List of Tricks to Make Your Laptop Faster.</u></a></li>
<li><a href="https://techidaily.com/optimize-windows-11-for-gamers-by-switching-off-mouse-acceleration-feature/"><u>Optimize Windows 11 for Gamers by Switching Off Mouse Acceleration Feature</u></a></li>
<li><a href="https://techidaily.com/quick-fixes-rebuilding-the-icon-cache-on-your-windows-7-8-or-vista-pc/"><u>Quick Fixes: Rebuilding the Icon Cache on Your Windows 7, 8 or Vista PC</u></a></li>
<li><a href="https://techidaily.com/self-fixing-operating-system-tools-for-windows-11-users/"><u>Self-Fixing Operating System Tools for Windows 11 Users</u></a></li>
<li><a href="https://techidaily.com/solving-high-disk-usage-woes-tips-for-windows-11-users-facing-a-full-disk-scenario/"><u>Solving High Disk Usage Woes - Tips for Windows 11 Users Facing a Full Disk Scenario</u></a></li>
<li><a href="https://techidaily.com/step-by-step-tutorial-how-to-perform-a-successful-system-restore-in-windows-10/"><u>Step by Step Tutorial: How to Perform a Successful System Restore in Windows 10</u></a></li>
<li><a href="https://techidaily.com/step-by-step-fixes-for-non-functional-windows-system-diagnostic-app/"><u>Step-by-Step Fixes for Non-Functional Windows System Diagnostic App</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-capturing-images-with-your-lenovo-computers-built-in-camera/"><u>Step-by-Step Guide: Capturing Images with Your Lenovo Computer's Built-In Camera</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-clearing-viruses-off-your-android-smartphone-without-erasing-everything/"><u>Step-by-Step Guide: Clearing Viruses Off Your Android Smartphone Without Erasing Everything</u></a></li>
<li><a href="https://techidaily.com/tackling-the-trouble-easy-ways-to-fix-your-frozen-windows-update-dilemma/"><u>Tackling the Trouble: Easy Ways to Fix Your Frozen Windows Update Dilemma</u></a></li>
<li><a href="https://techidaily.com/the-ultimate-guide-how-to-upgrade-bios-compatible-with-windows-11/"><u>The Ultimate Guide: How to Upgrade BIOS Compatible with Windows 11</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-guide-fixing-seagate-hdd-visibility-issues-on-windows-11/"><u>Troubleshooting Guide: Fixing Seagate HDD Visibility Issues on Windows 11</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-guide-managing-high-cpu-consumption-by-antimalware-service-executable-on-windows-systems/"><u>Troubleshooting Guide: Managing High CPU Consumption by 'Antimalware Service Executable' On Windows Systems</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-tips-resolving-issues-with-your-logitech-k780-keyboard/"><u>Troubleshooting Tips: Resolving Issues with Your Logitech K780 Keyboard</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-tips-solving-the-black-webcam-issue-in-windows-11-and-10/"><u>Troubleshooting Tips: Solving the Black Webcam Issue in Windows 11 & 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/vision-quest-movies-in-augmented-reality/"><u>Vision Quest  Movies in Augmented Reality</u></a></li>
</ul></div>
