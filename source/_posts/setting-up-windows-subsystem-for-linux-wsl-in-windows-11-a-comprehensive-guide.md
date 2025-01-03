---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-12-30T19:17:21.772Z
updated: 2025-01-02T22:02:37.604Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-the-ultimate-hunt-and-harvest-game-plan/"><u>[New] In 2024, The Ultimate Hunt and Harvest Game Plan</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-finding-those-who-fled-my-insta-friends/"><u>[Updated] Finding Those Who Fled My Insta Friends</u></a></li>
<li><a href="https://change-location.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-ways-to-lock-apps-on-apple-iphone-6-plus-and-ipad-securely-drfone-by-drfone-ios/"><u>7 Ways to Lock Apps on Apple iPhone 6 Plus and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-guide-to-8-premium-free-software-apps-windowsmac/"><u>Essential Guide to 8 Premium Free Software Apps (Windows/Mac)</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-meizu-21-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Meizu 21 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-xs-ios-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone XS iOS System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-system-issues-of-apple-iphone-12-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System Issues of Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-nokia-105-classic-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Nokia 105 Classic Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-v29-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo V29 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-apple-iphone-xs-max-drfone-by-drfone-ios/"><u>Remove Device Supervision From your Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-broken-or-corrupt-video-files-of-zte-axon-40-lite-by-stellar-video-repair-mobile-video-repair/"><u>Repair broken or corrupt video files of ZTE Axon 40 Lite</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-gionee-f3-pro-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Gionee F3 Pro</u></a></li>
<li><a href="https://technical-tips.techidaily.com/streaming-with-fandango-on-your-apple-tv-a-comprehensive-walkthrough/"><u>Streaming with Fandango on Your Apple TV - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-seamless-media-magic-turning-xml-ssa-into-dynamic-srts/"><u>The Seamless Media Magic Turning XML, SSA Into Dynamic SRTs</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-m34-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy M34 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-samsung-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Samsung .</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-oppo-a56s-5g-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Oppo A56s 5G</u></a></li>
<li><a href="https://win-superb.techidaily.com/troubleshooting-windows-security-access-problems-in-windows-10-learn-4-proven-fixes/"><u>Troubleshooting Windows Security Access Problems in Windows 10 - Learn 4 Proven Fixes</u></a></li>
</ul></div>

