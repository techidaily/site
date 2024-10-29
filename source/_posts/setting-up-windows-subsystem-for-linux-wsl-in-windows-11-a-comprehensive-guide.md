---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-10-26T21:01:59.818Z
updated: 2024-10-29T19:56:18.659Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

##  The Slow Way: Enable WSL and Install a Distro

 You can also enable the Windows Subsystem for Linux (WSL) the older way. This takes more clicking, and we recommend just running the command above.

 If you install a Linux distro before installing and enabling WSL you may experience problems. If this happens, run wsl -l to list your current Linux distros, then use enter the command **wsl --unregister** followed by the name of the distro. Try launching the Linux distro again. 

 To do this, open your Start menu and search for "Windows features." (You can press the Windows key to open the Start menu and just start typing.) Launch the "Turn Windows Features On or Off" shortcut.

 Enable the "Windows Subsystem for Linux" checkbox here and click "OK." You will be prompted to reboot your computer.

![Enable the &quot;Windows Subsystem for Linux&quot; option and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/b1-install-wsl.png) 

 After you do, open the Microsoft Store app and search for the Linux distribution that you want to use. For example, you might search for "Ubuntu."

 Install the Linux distribution that you want to use (like Ubuntu) as you would any other application. Just click the "Get" button on its Store page.

![Search for "Ubuntu," then click "Get."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/ubuntu.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-shot-selection-mastery-making-every-frame-count-on-youtube/"><u>[Updated] 2024 Approved Shot Selection Mastery Making Every Frame Count on YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-youtube-channel-art-make-banners-icons-and-thumbnails/"><u>[Updated] In 2024, YouTube Channel Art - Make Banners, Icons, and Thumbnails</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-laughterlink-join-now-and-start-your-journey/"><u>[Updated] LaughterLink Join Now & Start Your Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-delete-temporary-files-in-windows-try-these-fixes/"><u>Can’t Delete Temporary Files in Windows? Try These Fixes</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-lava-yuva-3-pro-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-vivo-y36-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Vivo Y36 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-itel-p55-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Itel P55 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-realme-11x-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Realme 11X 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-upgrade-your-mac-with-macos-sierra-simplified-for-2024/"><u>How to Upgrade Your Mac with macOS Sierra Simplified for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-accessing-your-subscriber-details-directly/"><u>In 2024, Accessing Your Subscriber Details Directly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-nubia-red-magic-8s-proplus-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Nubia Red Magic 8S Pro+ Phone? Unlock It Now</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-nokia-c110-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Nokia C110 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/transfiere-archivo-pgm-a-formato-png-sin-coste-metodo-online-de-convertir-imagenes/"><u>Transfiere Archivo PGM a Formato PNG Sin Coste: Método Online De Convertir Imágenes</u></a></li>
</ul></div>

