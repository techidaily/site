---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-09-20T21:17:52.228Z
updated: 2024-09-24T19:27:02.275Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

##  The Slow Way: Enable WSL and Install a Distro

 You can also enable the Windows Subsystem for Linux (WSL) the older way. This takes more clicking, and we recommend just running the command above.

 If you install a Linux distro before installing and enabling WSL you may experience problems. If this happens, run wsl -l to list your current Linux distros, then use enter the command **wsl --unregister** followed by the name of the distro. Try launching the Linux distro again. 

 To do this, open your Start menu and search for "Windows features." (You can press the Windows key to open the Start menu and just start typing.) Launch the "Turn Windows Features On or Off" shortcut.

 Enable the "Windows Subsystem for Linux" checkbox here and click "OK." You will be prompted to reboot your computer.

![Enable the &quot;Windows Subsystem for Linux&quot; option and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/b1-install-wsl.png) 

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you do, open the Microsoft Store app and search for the Linux distribution that you want to use. For example, you might search for "Ubuntu."

 Install the Linux distribution that you want to use (like Ubuntu) as you would any other application. Just click the "Get" button on its Store page.

![Search for "Ubuntu," then click "Get."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/ubuntu.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-flipping-the-script-how-to-invert-snapchat-movements/"><u>[New] 2024 Approved Flipping the Script How to Invert Snapchat Movements</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-a-stepwise-approach-to-srt-mastery-and-expert-tips/"><u>[New] A Stepwise Approach to SRT Mastery and Expert Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-srt-mastery-a-technological-deep-dive-for-media-professionals/"><u>[New] SRT Mastery A Technological Deep-Dive for Media Professionals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-social-media-insta-to-tiksync/"><u>[Updated] Mastering Social Media Insta-To-TikSync</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-your-guide-to-top-6-free-online-video-downloads/"><u>[Updated] Your Guide to Top 6 Free, Online Video Downloads</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-infinix-note-30-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Infinix Note 30 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-tecno-pova-6-pro-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Tecno Pova 6 Pro 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-realme-v30-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Realme V30 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-11-pro-max-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 11 Pro Max To Other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-11-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 11 Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-quick-quality-grabs-for-your-vids/"><u>In 2024, Quick, Quality Grabs for Your Vids</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-realme-11x-5g-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Realme 11X 5G on Windows</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-itel-p55-5g-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Itel P55 5G</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-sound-of-success-tailoring-audio-for-instagram-content-for-2024/"><u>The Sound of Success Tailoring Audio for Instagram Content for 2024</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-realme-v30-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Realme V30 Reset Code | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723009954483-troubled-by-bluestacks-crashes-fix-them-all-within-5-minutes/"><u>Troubled by BlueStacks Crashes? Fix Them All Within 5 Minutes</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-buyers-guide-to-top-6-hdmi-monitors-21-for-2024/"><u>Ultimate Buyer's Guide to Top 6 HDMI Monitors (2.1) for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-xiaomi-redmi-note-12r-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Xiaomi Redmi Note 12R Hard Reset | Dr.fone</u></a></li>
</ul></div>

