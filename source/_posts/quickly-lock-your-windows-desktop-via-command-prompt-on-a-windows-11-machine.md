---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-11-21T22:53:30.388Z
updated: 2024-11-23T16:38:30.074Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-choices-top-10-best-video-editing-software-free-2023/"><u>[Updated] In 2024, Essential Choices Top 10 Best Video Editing Software (Free, 2023)</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-initial-steps-towards-perfect-transitional-sound-levels/"><u>[Updated] Initial Steps Towards Perfect Transitional Sound Levels</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-a59-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo A59 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-tecno-phantom-v-fold-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Tecno Phantom V Fold Hard Reset | Dr.fone</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/comment-synchroniser-des-fichiers-gratuitement-en-duo-a-laide-de-robocopy-sur-les-systemes-dexploitation-windows-11-10-8-et-7/"><u>Comment Synchroniser Des Fichiers Gratuitement en Duo À L'aide De Robocopy Sur Les Systèmes D'Exploitation Windows 11, 10, 8 Et 7</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-honor-play-40c-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Honor Play 40C Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-realme-narzo-60-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Realme Narzo 60 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/fortnite-login-restrictions-heres-how-to-secure-your-rightful-entry-into-gameplay/"><u>Fortnite Login Restrictions? Here’s How to Secure Your Rightful Entry Into Gameplay</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-11-pro-max-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 11 Pro Max to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-a-stepwise-strategy-to-make-mark-with-memes-at-9gag/"><u>In 2024, A Stepwise Strategy to Make Mark with Memes at 9GAG</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-razr-40-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Razr 40 To Phone | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-top-tech-choice-screen-recording-leaders-on-the-web/"><u>In 2024, Top Tech Choice Screen Recording Leaders on the Web</u></a></li>
<li><a href="https://extra-skills.techidaily.com/podcasts-vs-youtube-which-one-is-the-right-choice-in-2024/"><u>Podcasts Vs. YouTube Which One Is the Right Choice, In 2024</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-tecno-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Tecno</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-moto-g14-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Moto G14</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-y55s-5g-2023-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Y55s 5G (2023).</u></a></li>
<li><a href="https://techidaily.com/why-stellar-data-recovery-for-iphone-se-2020-takes-time-in-scanning-my-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why Stellar Data Recovery for iPhone SE (2020) takes time in scanning my iPhone? | Stellar</u></a></li>
</ul></div>

