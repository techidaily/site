---
title: "Resolving Elevated CPU Use by Windows Module Installer: Effective Strategies"
date: 2024-09-30T05:35:13.162Z
updated: 2024-09-30T19:27:14.856Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Follow the on-screen instructions in the tool to resolve any update issues.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Temporarily End the Windows Modules Installer Process

 If you need to perform a task and the Windows Modules Installer Worker process is using up so much CPU that your PC has become unresponsive, you can [temporarily end the process](https://extra-guidance.techidaily.com/updated-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/). We don't recommend you do this unless you have a really need to. 

 To end the process, right-click the Start Menu icon and select "Task Manager." Open the "Processes" tab, right-click "Windows Modules Installer Worker," and select "End Task."

!['End Task' highlighted for 'Windows Modules Installer Worker' in Task Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-end-windows-modules-installer-worker-process.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Now that your update cache is deleted, pause the updates. [On Windows 11](https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-14-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/), navigate to Settings > Windows Update. On the right pane, next to "Pause Updates," click the drop-down menu and choose how long to pause the updates.

!['Pause Updates' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-pause-updates-windows-11.jpg) 

[On Windows 10](https://instagram-video-recordings.techidaily.com/climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification/), go to Settings > Update & Security > Windows Update. On the right pane, click "Advanced Options." In the "Pause Updates" section, click the "Pause Until" drop-down menu and select a time duration.

!['Pause Until' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-pause-updates-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capturing-your-lenovo-display-with-ease/"><u>[New] 2024 Approved Capturing Your Lenovo Display with Ease</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-pro-tips-for-streaming-and-screening-netflix-on-mac/"><u>[New] In 2024, Pro-Tips for Streaming & Screening Netflix on Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-quick-guide-to-insta-influence-mastery/"><u>[New] In 2024, Quick Guide to Insta-Influence Mastery</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-navigating-the-world-of-social-media-with-a-focused-brand/"><u>[New] Navigating the World of Social Media with a Focused Brand</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-total-earning-summary-for-pewdiepie-star/"><u>[New] Total Earning Summary for PewDiePie Star</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sj6-mastery-showdown-sjcam-vs-xiaomis-yi-pro-4k/"><u>2024 Approved SJ6 Mastery Showdown SJCam Vs. Xiaomi's Yi Pro 4K</u></a></li>
<li><a href="https://win-amazing.techidaily.com/acer-nitro-5-user-manual-how-to-ensure-the-latest-drivers-are-installed-correctly/"><u>Acer Nitro 5 User Manual: How to Ensure the Latest Drivers Are Installed Correctly</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/airbus-defence-and-space/"><u>Airbus Defence & Space</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-zte-blade-a73-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for ZTE Blade A73 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effiziente-treibstoffquelle-um-die-geschaftsleistung-anzukurbeln/"><u>Effiziente Treibstoffquelle, Um Die Geschäftsleistung Anzukurbeln</u></a></li>
<li><a href="https://techidaily.com/hard-reset-xiaomi-14-pro-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Xiaomi 14 Pro in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-samsung-galaxy-m54-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Samsung Galaxy M54 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-xiaomi-redmi-12-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Xiaomi Redmi 12 Without Password | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2022-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2022) to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/some-mp4-won-t-play-on-my-nova-y91-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Nova Y91</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-samsung-galaxy-s23-tactical-edition-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-xs-screen-lock-without-data-loss-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone XS screen lock without data loss</u></a></li>
</ul></div>

