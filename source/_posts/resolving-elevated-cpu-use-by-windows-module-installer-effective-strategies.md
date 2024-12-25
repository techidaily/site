---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-12-21T21:13:39.742Z
updated: 2024-12-24T16:11:12.168Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On Windows 10, head to Settings > Update & Security > Troubleshoot > Additional Troubleshooters. Select "Windows Update" and click "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for 'Windows Update' troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-windows-update-troubleshooter-windows-10.jpg) 

 Follow the on-screen instructions in the tool to resolve any update issues.

##  Temporarily End the Windows Modules Installer Process

 If you need to perform a task and the Windows Modules Installer Worker process is using up so much CPU that your PC has become unresponsive, you can [temporarily end the process](https://extra-guidance.techidaily.com/updated-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/). We don't recommend you do this unless you have a really need to. 

 To end the process, right-click the Start Menu icon and select "Task Manager." Open the "Processes" tab, right-click "Windows Modules Installer Worker," and select "End Task."

!['End Task' highlighted for 'Windows Modules Installer Worker' in Task Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-end-windows-modules-installer-worker-process.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Clear Windows Update Cache and Pause Updates

 If you want to prevent Windows Modules Installer Worker from running, clear your Windows Update cache and pause the updates. This way, the process won’t have updates to install and won’t be able to check for new updates. 

 We don’t recommend pausing updates as newer updates often bring bug fixes and security patches that improve and safeguard your system.

 To start, open a Run window by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Windows Update." Right-click it and select "Stop."

!['Stop' highlighted for 'Windows Update' on the 'Services' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-stop-windows-update-service.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Open Run again by pressing Windows+R, type the following path in the box, and press Enter:

C:\Windows\SoftwareDistribution\

 Select all files in the folder by pressing Ctrl+A, then right-click a selected file and choose "Delete" (a trash can icon on Windows 11). Make sure to [empty the Recycle Bin](https://some-guidance.techidaily.com/new-the-complete-powerdirector-2024-users-handbook/) as well.

!['Delete' highlighted for Windows Update cache.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-delete-windows-update-cache.jpg) 

 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-knowledge.techidaily.com/new-from-monochrome-to-multicolor-grading-journey/"><u>[New] From Monochrome to Multicolor Grading Journey</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-new-era-of-advertising-embracing-the-metaverse-for-2024/"><u>[New] The New Era of Advertising Embracing the Metaverse for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-obs-for-a-clearer-better-live-stream-to-youtube-for-2024/"><u>[Updated] OBS for a Clearer, Better Live Stream to YouTube for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/easy-steps-to-resolve-crackling-sounds-from-your-windows-pc-speakers/"><u>Easy Steps to Resolve Crackling Sounds From Your Windows PC Speakers</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-magic-6-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-samsung-galaxy-f15-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Samsung Galaxy F15 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-pro-max-to-other-iphone-12-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 Pro Max To Other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-6-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 6 Plus without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-lava-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Lava Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://driver-error.techidaily.com/installing-necessary-drivers-in-windows-1087-solutions-and-tips-issue-resolved/"><u>Installing Necessary Drivers in Windows 10/8/7: Solutions and Tips [ISSUE RESOLVED]</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-12-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi 12 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-infinix-note-30-vip-racing-edition-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/split-screen-merge-creativity-top-video-editing-apps-for-mobile-devices-for-2024/"><u>Split Screen, Merge Creativity Top Video Editing Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-xiaomi-redmi-note-13-proplus-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Xiaomi Redmi Note 13 Pro+ 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://win-special.techidaily.com/1728503988755-win10117/"><u>Win10/11の秘密兵器:消えたフォルダを7つの魔法で取り戻せ！</u></a></li>
</ul></div>

