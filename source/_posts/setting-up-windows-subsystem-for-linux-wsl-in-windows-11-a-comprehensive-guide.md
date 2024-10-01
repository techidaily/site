---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-09-25T20:56:06.805Z
updated: 2024-10-01T02:12:10.009Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e5207beb7032dbe2a223f71bc8ac9ba7ae1e50509055968df3fdf501a1448078.jpg
---

## Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide

### Quick Links

* [How WSL Works on Windows 11](https://screen-sharing-recording.techidaily.com/easy-ways-to-record-steam-gameplay-2023-for-2024/)
* [Install WSL through Windows Terminal](https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-8-plus-with-7-methods-by-drfone-ios/)
* [The Slow Way: Enable WSL and Install a Distro](https://smart-video-creator.techidaily.com/new-blur-unwanted-parts-of-your-videos-with-these-mobile-apps/)

### Key Takeaways

 To install the Windows Subsystem for Linux (WSL) on Windows 11, run Terminal as administrator, then enter "wsl --install" into the window. Run "wsl --install -d Distro", replacing "Distro" with the name of a Linux distro, to install a specific distribution instead of Ubuntu. You can install additional Linux distros from the Terminal or the Microsoft Store.

 The Windows Subsystem for Linux (WSL) lets you run Linux software on your Windows 11 PC. When you enable WSL, Windows will install a custom-built Linux kernel. You can then install Ubuntu or another Linux distribution of your choice.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896560/19272" target="_top" id="1896560">
  <img src="//a.impactradius-go.com/display-ad/19272-1896560" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896560/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-premier-moba-games-on-android-top-10-edition-for-2024/"><u>[New] Premier MOBA Games on Android - TOP 10 Edition for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-the-leading-free-subtitle-tools-online/"><u>[Updated] Explore the Leading Free Subtitle Tools Online</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-exploring-new-realms-a-detailed-jaunt-vr-review/"><u>[Updated] Exploring New Realms A Detailed Jaunt VR Review</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-youtube-growth-secrets-masterful-narration-techniques/"><u>[Updated] In 2024, YouTube Growth Secrets Masterful Narration Techniques</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-simplified-approach-to-removing-youtube-comments-with-ease-for-2024/"><u>[Updated] Simplified Approach to Removing YouTube Comments with Ease for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-smart-selections-17-apps-for-flawless-image-correction/"><u>[Updated] Smart Selections 17 Apps for Flawless Image Correction</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/elite-display-decoded-examining-samsungs-ue590-monitor-for-2024/"><u>Elite Display Decoded Examining Samsung's UE590 Monitor for 2024</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-vivo-y78-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-12-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-12-mini-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 12 mini Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2022-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2022) to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-se-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone SE Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-oppo-reno-10-proplus-5g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Oppo Reno 10 Pro+ 5G Pattern Lock Screen</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/make-every-snap-spectacular-20-top-filter-recommendations-for-2024/"><u>Make Every Snap Spectacular 20 Top Filter Recommendations for 2024</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-motorola-moto-g-stylus-2023-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-vivo-s17e-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Vivo S17e without backup.</u></a></li>
<li><a href="https://techidaily.com/what-to-do-if-iphone-se-2022-is-not-listed-when-i-run-the-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What to do if iPhone SE (2022) is not listed when I run the software? | Stellar</u></a></li>
<li><a href="https://buynow-help.techidaily.com/wire-free-wonderment-the-allure-of-m06-headphones/"><u>Wire-Free Wonderment: The Allure of M06 Headphones</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-oppo-a78-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Oppo A78 5G | Dr.fone</u></a></li>
</ul></div>

