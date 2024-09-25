---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-09-19T23:41:42.681Z
updated: 2024-09-24T20:52:18.772Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Wait for It to Finish Running

 Windows launches the Windows Modules Installer Worker when there’s an update to install or a PC maintenance task to run. You should generally let the process finish running, even if it’s using up a lot of CPU.

 When the update or maintenance task has finished, the process will stop running.

 If it continues to run for an extended period or you want to perform other tasks, use the troubleshooting tips below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Windows Update Troubleshooter

 Windows Modules Installer Worker often runs longer than expected when there is a problem with an update. In this case, run the Windows Update troubleshooter to [find and fix any update problems](https://extra-guidance.techidaily.com/2024-approved-smoothing-out-the-rough-edges-in-photo-booth-videos/).

 Microsoft is phasing out troubleshooters in favor of the Get Help app on Windows 11\. In the future, use that app to resolve issues with your PC.

 If you’re on Windows 11, navigate to Settings > System > Troubleshoot > Other Troubleshooters, then click the "Run" button next to Windows Update.

!['Run' highlighted for 'Windows Update' troubleshooter in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-windows-update-troubleshooter-windows-11.jpg) 

 On Windows 10, head to Settings > Update & Security > Troubleshoot > Additional Troubleshooters. Select "Windows Update" and click "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for 'Windows Update' troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-windows-update-troubleshooter-windows-10.jpg) 

 Follow the on-screen instructions in the tool to resolve any update issues.

##  Temporarily End the Windows Modules Installer Process

 If you need to perform a task and the Windows Modules Installer Worker process is using up so much CPU that your PC has become unresponsive, you can [temporarily end the process](https://extra-guidance.techidaily.com/updated-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/). We don't recommend you do this unless you have a really need to. 

 To end the process, right-click the Start Menu icon and select "Task Manager." Open the "Processes" tab, right-click "Windows Modules Installer Worker," and select "End Task."

!['End Task' highlighted for 'Windows Modules Installer Worker' in Task Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-end-windows-modules-installer-worker-process.jpg) 

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

 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-able.techidaily.com/sons-of-the-forest-sudden-shutdowns-on-pc-diagnosis-and-solutions-explained/"><u>'Sons of the Forest' Sudden Shutdowns on PC: Diagnosis & Solutions Explained</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-vr-shopping-interface-prototyping/"><u>[New] 2024 Approved VR Shopping Interface Prototyping</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-smooth-transition-tips-for-inshot-editors/"><u>[New] Smooth Transition Tips for Inshot Editors</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-affordable-wonders-in-virtual-reality-headsets-from-china/"><u>[Updated] Affordable Wonders in Virtual Reality Headsets From China</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-a-new-take-on-favorite-movies-7-alternatives/"><u>2024 Approved A New Take on Favorite Movies - #7 Alternatives</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/an-intimate-look-at-the-innovative-sidekick-attachment-for-mods-new-generation-e-bike/"><u>An Intimate Look At The Innovative Sidekick Attachment For Mod’s New Generation E-Bike</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-vivo-s17e-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Vivo S17e Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-infinix-note-30-vip-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Infinix Note 30 VIP Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-motorola-g24-power-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Motorola G24 Power.</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-from-apple-iphone-15-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data from Apple iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 To Other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-vivo-y200-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Vivo Y200 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-lava-blaze-pro-5g-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Lava Blaze Pro 5G unlock screen</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-rog-phone-7-ultimate-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on ROG Phone 7 Ultimate without backup.</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-s18-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo S18 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/top-choice-webcams-boosting-podcast-quality-for-2024/"><u>Top Choice Webcams Boosting Podcast Quality for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-apex-legends-fixing-the-elusive-engine-glitch/"><u>Troubleshooting Apex Legends: Fixing the Elusive Engine Glitch</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-vivo-v27e-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Vivo V27e | Dr.fone</u></a></li>
</ul></div>

