---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-11-09T04:23:06.270Z
updated: 2024-11-14T01:04:31.478Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/updated-in-2024-best-storytelling-youtube-channels-to-follow-this-year/"><u>[Updated] In 2024, Best Storytelling YouTube Channels to Follow This Year</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-the-ultimate-screen-recorders-handbook-by-zd-soft-professionals/"><u>2024 Approved The Ultimate Screen Recorder’s Handbook by ZD Soft Professionals</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-realme-gt-5-240w-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Realme GT 5 (240W) Hard Reset | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-video-game-top-tips-for-perfect-live-thumbnails-for-2024/"><u>Elevate Your Video Game Top Tips for Perfect Live Thumbnails for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/enhancing-virtual-meeting-clarity-with-zoom-focus-for-2024/"><u>Enhancing Virtual Meeting Clarity with Zoom Focus for 2024</u></a></li>
<li><a href="https://fox-sure.techidaily.com/erfolgreiches-recovery-von-geloschten-photoshop-dateien-mit-myrecover-expertenanleitung/"><u>Erfolgreiches Recovery Von Gelöschten Photoshop-Dateien Mit MyRecover - Expertenanleitung</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-k11x-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo K11x Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-pro-max-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 Pro Max System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-15-plus-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 15 Plus iOS System? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-7-plus-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 7 Plus to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-remedying-silent-tweets-with-audio-integration/"><u>In 2024, Remedying Silent Tweets with Audio Integration</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/qidi-techs-q1-pro-headset-uncovered-a-detailed-performance-assessment-for-gamers/"><u>QIDI Tech's Q1 Pro Headset Uncovered: A Detailed Performance Assessment for Gamers.</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-11-pro-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 11 Pro Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/sky-gazers-rejoice-discovering-the-elevation-expertise-of-dji-spark/"><u>Sky Gazers Rejoice! Discovering the Elevation Expertise of DJI Spark</u></a></li>
<li><a href="https://techidaily.com/some-mp4-wont-play-on-my-civi-3-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Civi 3</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-honor-magic-vs-2-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Honor Magic Vs 2 Phone</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-honor-magic-6-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Honor Magic 6 Pro</u></a></li>
<li><a href="https://techidaily.com/what-to-do-if-iphone-11-pro-max-is-not-listed-when-i-run-the-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What to do if iPhone 11 Pro Max is not listed when I run the software? | Stellar</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-note-13-5g-won-t-play-mp4-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Xiaomi Redmi Note 13 5G won’t play MP4 files</u></a></li>
</ul></div>

