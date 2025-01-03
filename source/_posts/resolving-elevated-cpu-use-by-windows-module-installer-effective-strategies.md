---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-12-27T17:13:49.446Z
updated: 2025-01-03T03:03:08.699Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/786e0982cfdee2d5f20c6d4b4308fc64b7f3b17fc6a8a55e95bfdc13a652344b.jpg
---

## Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Open Run again by pressing Windows+R, type the following path in the box, and press Enter:

C:\Windows\SoftwareDistribution\

 Select all files in the folder by pressing Ctrl+A, then right-click a selected file and choose "Delete" (a trash can icon on Windows 11). Make sure to [empty the Recycle Bin](https://some-guidance.techidaily.com/new-the-complete-powerdirector-2024-users-handbook/) as well.

!['Delete' highlighted for Windows Update cache.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-delete-windows-update-cache.jpg) 

 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

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
<li><a href="https://youtube-web.techidaily.com/024-approved-building-your-first-channel-essential-video-gear-list/"><u>[New] 2024 Approved Building Your First Channel Essential Video Gear List</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-cinematic-sequence-best-video-cameras-for-extended-slow-motion/"><u>[Updated] In 2024, Cinematic Sequence Best Video Cameras for Extended Slow Motion</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974604348-boost-intel-graphics-3000-performance-with-a-simple-update-in-windows-10/"><u>Boost Intel Graphics 3000 Performance with a Simple Update in Windows 10.</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-samsung-galaxy-s24-ultra-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Samsung Galaxy S24 Ultra Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-update-and-download-enhanced-hp-deskjet-ink-advantage-3700-printer-drivers/"><u>Free Update & Download: Enhanced HP Deskjet Ink Advantage 3700 Printer Drivers</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723011703577-get-the-edge-in-gaming-tackle-and-fix-frame-rate-dips-stop-stuttering-for-maximum-playtime-efficiency/"><u>Get the Edge in Gaming: Tackle and Fix Frame Rate Dips, Stop Stuttering for Maximum Playtime Efficiency</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-nokia-xr21-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Nokia XR21? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-obtain-perfect-photos-without-marks/"><u>In 2024, How To Obtain Perfect Photos Without Marks</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-on-apple-iphone-8-plus-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes On Apple iPhone 8 Plus?</u></a></li>
<li><a href="https://techidaily.com/sign-word-2019-online-add-signature-to-word-2019-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2019 Online - Add Signature to Word 2019 for Free</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-lava-blaze-2-pro-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Lava Blaze 2 Pro without backup.</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-realme-narzo-n55-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Realme Narzo N55</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-free-3d-animation-software-is-not-easy-to-find-some-makers-are-even-free-and-simple-if-you-want-to-know-which-are-the-8-best-3d-animation-software-c/"><u>Updated Free 3D Animation Software Is Not Easy to Find. Some Makers Are Even Free and Simple. If You Want to Know Which Are the 8 Best 3D Animation Software, Check It Out for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/upgrade-your-apple-m3-macbook-pro-and-imac-to-macos-catalina-with-ease-techtips/"><u>Upgrade Your Apple M3 MacBook Pro and iMac to macOS Catalina with Ease | TechTips</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-your-hardware-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing your hardware drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-poco-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Poco</u></a></li>
</ul></div>

