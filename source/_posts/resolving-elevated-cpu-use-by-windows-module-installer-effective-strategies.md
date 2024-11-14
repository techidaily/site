---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-11-06T16:03:54.359Z
updated: 2024-11-13T16:12:32.270Z
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
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On Windows 10, head to Settings > Update & Security > Troubleshoot > Additional Troubleshooters. Select "Windows Update" and click "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for 'Windows Update' troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-windows-update-troubleshooter-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528681/16446" target="_top" id="1528681">
  <img src="//a.impactradius-go.com/display-ad/16446-1528681" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528681/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Computer Maintenance at Your Specified Time

 Windows Modules Installer Worker runs when your PC is performing a maintenance task. Luckily, you can [change when the system runs those tasks](https://twitter-videos.techidaily.com/new-2024-approved-tweeting-with-videos-a-quick-tutorial/), allowing you to prevent the process from running when you’re working on important tasks.

 To make that change, open the Start Menu and find "Security and Maintenance". Click it to open it. Then, expand the "Maintenance" section and choose "Change Maintenance Settings."

!['Change Maintenance Settings' highlighted in Control Panel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-change-windows-maintenance-settings.jpg) 

 Select the "Run Maintenance Tasks Daily at" drop-down menu and select when you want your PC to run the maintenance tasks. This should be when you aren’t working on important tasks on your PC. Then, select "OK."

!['Run Maintenance Tasks Daily at' and 'OK' highlighted on the 'Automatic Maintenance' screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-modify-windows-maintenance-time.jpg) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-knowledge.techidaily.com/new-chronoscape-controls-rewinding-iphone-footage-efficiently-for-2024/"><u>[New] Chronoscape Controls Rewinding iPhone Footage Efficiently for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-football-vids-premier-insights-into-youtube-tracks-for-2024/"><u>[Updated] Football Vids Premier Insights Into YouTube Tracks for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-master-your-remote-work-with-these-5-video-conference-recorders/"><u>2024 Approved Master Your Remote Work with These 5 Video Conference Recorders</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-xiaomi-14-pro-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-effective-substitutes-to-chatgpt-for-autonomous-code-generation/"><u>Exploring Effective Substitutes to ChatGPT for Autonomous Code Generation</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-tecno-pova-5-pro-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-pova-5-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-smart-8-pro-phone-without-pin-by-drfone-android/"><u>How to Unlock Infinix Smart 8 Pro Phone without PIN</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-xs-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone XS Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Tecno Spark 10 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-honor-70-lite-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Honor 70 Lite 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/simple-methods-swap-sea-creature-sounds-in-windows-os/"><u>Simple Methods Swap Sea Creature Sounds in Windows OS</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-vivo-v29e-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Vivo V29e</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-c12-pro-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from C12 Pro</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solution-guide-getting-your-dolby-advanced-audio-running-again-in-windows-11-after-driver-failure/"><u>Solution Guide: Getting Your Dolby Advanced Audio Running Again in Windows 11 After Driver Failure</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-process-performing-a-total-system-reset-on-your-ios-gadget/"><u>Step-by-Step Process: Performing a Total System Reset on Your iOS Gadget</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-vivo-y78-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Vivo Y78 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-or-malfunctioning-your-drivers-with-windows-device-manager-in-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing or malfunctioning your drivers with Windows Device Manager in Windows 11 & 10 & 7</u></a></li>
</ul></div>

