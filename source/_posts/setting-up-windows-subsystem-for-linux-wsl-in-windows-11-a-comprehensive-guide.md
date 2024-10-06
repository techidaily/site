---
title: "Setting Up Windows Subsystem for Linux (WSL) in Windows 11: A Comprehensive Guide"
date: 2024-10-02T09:31:03.600Z
updated: 2024-10-06T11:09:03.323Z
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
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
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

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

##  The Slow Way: Enable WSL and Install a Distro

 You can also enable the Windows Subsystem for Linux (WSL) the older way. This takes more clicking, and we recommend just running the command above.

 If you install a Linux distro before installing and enabling WSL you may experience problems. If this happens, run wsl -l to list your current Linux distros, then use enter the command **wsl --unregister** followed by the name of the distro. Try launching the Linux distro again. 

 To do this, open your Start menu and search for "Windows features." (You can press the Windows key to open the Start menu and just start typing.) Launch the "Turn Windows Features On or Off" shortcut.

 Enable the "Windows Subsystem for Linux" checkbox here and click "OK." You will be prompted to reboot your computer.

![Enable the &quot;Windows Subsystem for Linux&quot; option and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/b1-install-wsl.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you do, open the Microsoft Store app and search for the Linux distribution that you want to use. For example, you might search for "Ubuntu."

 Install the Linux distribution that you want to use (like Ubuntu) as you would any other application. Just click the "Get" button on its Store page.

![Search for "Ubuntu," then click "Get."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/ubuntu.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-choosing-a-professional-video-editor-filmora-against-democreator/"><u>[New] 2024 Approved Choosing a Professional Video Editor Filmora Against Democreator</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-earning-stream-start-small-see-big-on-youtube-for-2024/"><u>[New] Earning Stream Start Small, See Big on YouTube for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-future-scrutiny-alternate-viewpoints/"><u>2024 Approved Future Scrutiny Alternate Viewpoints</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-instant-video-creation-uploading-images/"><u>2024 Approved Instant Video Creation Uploading Images</u></a></li>
<li><a href="https://buynow-help.techidaily.com/affordable-performance-unleashed-tp-link-archer-c9-router-revealed/"><u>Affordable Performance Unleashed: TP-Link Archer C9 Router Revealed!</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/download-ultimate-collection-of-erito-adult-films-in-high-definition-formats-like-mp4-mov-avi-and-flv/"><u>Download Ultimate Collection of Erito Adult Films in High-Definition Formats Like MP4, MOV, AVI, and FLV</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-oneplus-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-apple-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/1716465099560-how-to-make-a-youtube-subscribe-link-easy/"><u>How to Make a YouTube Subscribe Link - Easy!</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-infinix-hot-30i-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Infinix Hot 30i Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-itel-p40-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Itel P40 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-15-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 15 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-se-2022-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone SE (2022) to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-essential-guide-to-low-cost-cloud-storage-plans-for-2024/"><u>The Essential Guide to Low-Cost Cloud Storage Plans for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-samsung-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Samsung without backup.</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-oppo-find-x7-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-your-guide-to-computer-components/"><u>Tom's Tech Insights - Your Guide to Computer Components</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-realme-narzo-60x-5g-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Realme Narzo 60x 5G</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-hardware-drivers-on-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated hardware drivers on Windows 11/10/7</u></a></li>
</ul></div>

