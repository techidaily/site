---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-12-26T19:38:44.435Z
updated: 2025-01-02T08:44:18.847Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e5207beb7032dbe2a223f71bc8ac9ba7ae1e50509055968df3fdf501a1448078.jpg
---

## Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How WSL Works on Windows 11](https://screen-sharing-recording.techidaily.com/easy-ways-to-record-steam-gameplay-2023-for-2024/)
* [Install WSL through Windows Terminal](https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-8-plus-with-7-methods-by-drfone-ios/)
* [The Slow Way: Enable WSL and Install a Distro](https://smart-video-creator.techidaily.com/new-blur-unwanted-parts-of-your-videos-with-these-mobile-apps/)

### Key Takeaways

 To install the Windows Subsystem for Linux (WSL) on Windows 11, run Terminal as administrator, then enter "wsl --install" into the window. Run "wsl --install -d Distro", replacing "Distro" with the name of a Linux distro, to install a specific distribution instead of Ubuntu. You can install additional Linux distros from the Terminal or the Microsoft Store.

 The Windows Subsystem for Linux (WSL) lets you run Linux software on your Windows 11 PC. When you enable WSL, Windows will install a custom-built Linux kernel. You can then install Ubuntu or another Linux distribution of your choice.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How WSL Works on Windows 11

 You can enable the Windows Subsystem for Linux (WSL) on all editions of [Windows 11](https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/)—even Windows 11 Home. (You can also [install WSL on Windows 10](https://tech-haven.techidaily.com/ais-role-in-todays-misinformation-landscape/).)

 Like more recent versions of Windows 10, Windows 11 uses WSL 2\. This second version is redesigned and runs a full Linux kernel in a [Hyper-V](https://facebook-record-videos.techidaily.com/updated-the-infographic-index-youtubes-surprising-stat-treasury-2017/) hypervisor for improved compatibility. When you enable the feature, Windows 11 downloads a [Microsoft-built Linux kernel](https://win-answers.techidaily.com/god-of-war-not-working-overcome-inadequate-memory-error-here/) that it runs in the background. Windows Update keeps the kernel updated. (You can use your own custom Linux kernel if you prefer, too.)

 To use WSL, you'll need to install a Linux distribution. By default, WSL installs Ubuntu. This will give you access to a full Ubuntu command-line environment using the Bash shell or any other command-line shell of your choice.

 You can access your Linux shell environments in the Windows Terminal app included with Windows 11, too.

 You can also run graphical Linux apps out of the box (Just install them in the Linux command-line environment and run the command). Windows 11 also includes support for running Linux apps with GPU access, making GPU-accelerated Linux computing workloads run well on Windows.

 It is also worth noting that most new, interesting developments for WSL are shifting to Windows 11—Windows 10 users won't be able to use them. 

##  Install WSL through Windows Terminal

 Microsoft has made this process extremely simple on Windows 11\. You can enable the Windows Subsystem for Linux and install a Linux distribution like Ubuntu with a single command.

 To do this, you will need to use a command-line window with Administrator permissions. We'll do this with the Windows Terminal, although you can also just launch Command Prompt.

 To launch a Windows Terminal with Administrator permissions, right-click the Start button on the taskbar or press Windows+X and click "Terminal (Admin)." (You can also find the Windows Terminal shortcut in your Start menu—right-click it and select "Run as Administrator.") Agree to the User Account Control prompt that appears.

![Right-click the Start button, then select "Terminal (Admin)."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-9.png) 

 To enable the Windows Subsystem for Linux and install Ubuntu, which is the default distribution, just run the following command:

wsl --install

 When the process is complete, Windows will ask you to reboot your PC. Restart your computer by entering **shutdown /r /t 0** into the Terminal. You'll be able to use your Linux system after you do. (You can right-click the Start menu and click Shut Down or Sign Out > Restart to quickly reboot.)

![Run the &quot;wsl --install&quot; command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/a2-install-wsl-and-ubuntu.png) 

 To list other available Linux distributions, run the following command instead. This lists (-l) distributions that are available online (-o).

wsl -l -o

 You can install a Linux distribution of your choice by running the following command, replacing "Name" with the name of the Linux distro, as displayed in the "Name" column:

wsl --install -d Name

 For example, to install Debian instead of Ubuntu, you'd run:

wsl --install -d Debian

 You can also run this command multiple times to install several Linux distributions on your system.

![List available Linux distributions and install one.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/a3-list-distros.png) 

 Once your computer has rebooted, you can launch the Linux distro that you installed from your Start menu.

![Launch the &quot;Ubuntu&quot; shortcut.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/ubuntu-start-menu.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The Slow Way: Enable WSL and Install a Distro

 You can also enable the Windows Subsystem for Linux (WSL) the older way. This takes more clicking, and we recommend just running the command above.

 If you install a Linux distro before installing and enabling WSL you may experience problems. If this happens, run wsl -l to list your current Linux distros, then use enter the command **wsl --unregister** followed by the name of the distro. Try launching the Linux distro again. 

 To do this, open your Start menu and search for "Windows features." (You can press the Windows key to open the Start menu and just start typing.) Launch the "Turn Windows Features On or Off" shortcut.

 Enable the "Windows Subsystem for Linux" checkbox here and click "OK." You will be prompted to reboot your computer.

![Enable the &quot;Windows Subsystem for Linux&quot; option and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/b1-install-wsl.png) 

 After you do, open the Microsoft Store app and search for the Linux distribution that you want to use. For example, you might search for "Ubuntu."

 Install the Linux distribution that you want to use (like Ubuntu) as you would any other application. Just click the "Get" button on its Store page.

![Search for "Ubuntu," then click "Get."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/ubuntu.png) 

 You can now launch it from your Start menu just as if it were installed from the command above. 

 New Linux distros are occasionally added to the Microsoft Store, and you can find the currently available distros by searching for "Linux" rather than a specific distro. If your preferred Linux flavor isn't available, you can always import your preferred distro into WSL manually.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-engaging-audiences-through-vimeo-shares/"><u>[New] 2024 Approved Engaging Audiences Through Vimeo Shares</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-comprehensive-explanation-of-googles-automatic-transcription-technology/"><u>[New] Comprehensive Explanation of Google's Automatic Transcription Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-explore-and-enjoy-virtual-reality-cinema-on-your-ipad/"><u>[New] Explore and Enjoy Virtual Reality Cinema on Your iPad</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-vintage-track-simulators-the-quintet/"><u>[New] In 2024, Vintage Track Simulators The Quintet</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-honor-90-lite-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Honor 90 Lite Hard Reset | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/disabled-iphone-8-how-to-unlock-a-disabled-iphone-8-drfone-by-drfone-ios/"><u>Disabled iPhone 8 How to Unlock a Disabled iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-advice-on-picking-your-next-device-at-toms-tech-oasis/"><u>Expert Advice on Picking Your Next Device at Tom's Tech Oasis</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-11-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover iPhone 11 Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6 To Android? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-11-pro-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 11 Pro to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-se-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone SE without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-motorola-moto-g-stylus-5g-2023-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Motorola Moto G Stylus 5G (2023) Phone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-poco-m6-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Poco M6 5G FRP Bypass</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-oppo-a59-5g-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Oppo A59 5G</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-galaxy-s23-tactical-edition-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Galaxy S23 Tactical Edition</u></a></li>
</ul></div>

