---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-10-10T20:59:02.964Z
updated: 2024-10-11T17:14:06.366Z
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

 On Windows 10, head to Settings > Update & Security > Troubleshoot > Additional Troubleshooters. Select "Windows Update" and click "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for 'Windows Update' troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-windows-update-troubleshooter-windows-10.jpg) 

 Follow the on-screen instructions in the tool to resolve any update issues.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Temporarily End the Windows Modules Installer Process

 If you need to perform a task and the Windows Modules Installer Worker process is using up so much CPU that your PC has become unresponsive, you can [temporarily end the process](https://extra-guidance.techidaily.com/updated-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/). We don't recommend you do this unless you have a really need to. 

 To end the process, right-click the Start Menu icon and select "Task Manager." Open the "Processes" tab, right-click "Windows Modules Installer Worker," and select "End Task."

!['End Task' highlighted for 'Windows Modules Installer Worker' in Task Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-end-windows-modules-installer-worker-process.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1972679/19272" target="_top" id="1972679">
  <img src="//a.impactradius-go.com/display-ad/19272-1972679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037338/7443" target="_top" id="2037338">
  <img src="//a.impactradius-go.com/display-ad/7443-2037338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037338/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-2024-approved-premium-memory-device-for-sony-a7s-cameras/"><u>[New] 2024 Approved Premium Memory Device for Sony A7S Cameras</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-your-compre-agent-in-finding-superior-hdr-cameras/"><u>[New] 2024 Approved Your Compre Agent in Finding Superior HDR Cameras</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-chromes-fullscreen-mode-a-complete-guide-to-pip-usage/"><u>[New] Chrome's Fullscreen Mode A Complete Guide to PIP Usage</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-the-key-to-profit-youtube-shorts-insights/"><u>[New] In 2024, The Key to Profit YouTube Shorts Insights</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-game-ahead-the-ultimate-list-of-premier-gba-emulator-programs-for-2024/"><u>[Updated] Game Ahead The Ultimate List of Premier GBA Emulator Programs for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-breakthrough-in-recording-nine-revolutionary-online-microphones/"><u>[Updated] In 2024, Breakthrough in Recording Nine Revolutionary Online Microphones</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-poco-m6-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-your-polyglot-skills-through-innovative-tech-discover-how-chatgpt-plus-aids-language-education/"><u>Boost Your Polyglot Skills Through Innovative Tech: Discover How ChatGPT Plus Aids Language Education</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-honor-magic-5-lite-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Honor Magic 5 Lite Hard Reset | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/easy-guide-performing-a-gentle-restart-on-your-iphone/"><u>Easy Guide: Performing a Gentle Restart on Your iPhone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-realme-v30t-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Realme V30T | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-evaluating-apowersofts-tech-against-other-screen-recorders/"><u>In 2024, Evaluating Apowersoft's Tech Against Other Screen Recorders</u></a></li>
<li><a href="https://techidaily.com/is-your-motorola-moto-g04-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Motorola Moto G04 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-vivo-v27-pro-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Vivo V27 Pro and Browser | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/sign-word-2000-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2000 Online for Free</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-realme-c55-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Realme C55 Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-xiaomi-13t-pro-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Xiaomi 13T Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-13c-5g-can-t-play-avchd-mts-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Xiaomi Redmi 13C 5G can’t play AVCHD .mts video</u></a></li>
</ul></div>

