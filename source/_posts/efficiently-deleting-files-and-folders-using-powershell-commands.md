---
title: Efficiently Deleting Files & Folders Using PowerShell Commands
date: 2024-09-05T06:19:37.482Z
updated: 2024-09-06T06:19:37.482Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/52880885757_aff84061b0_o-1.jpg
---

## Efficiently Deleting Files & Folders Using PowerShell Commands

### Quick Links

* [Before You Begin: How to Find a File or Folder’s Full Path](https://extra-lessons.techidaily.com/navigate-iphones-dual-task-capabilities-effortlessly/)
* [How to Delete a Specific File Using PowerShell](https://youtube-video-recordings.techidaily.com/new-5-inspirational-winter-bgs-to-heat-your-videos/)
* [How to Delete a Specific Folder Using PowerShell](https://screen-mirror.techidaily.com/in-2024-how-can-honor-magic-5-litemirror-share-to-pc-drfone-by-drfone-android/)
* [How to Delete All Files in a Folder But Keep the Folder](https://extra-skills.techidaily.com/new-pushing-creative-boundaries-with-these-top-7-film-color-techniques/)
* [How to Delete All Files From a Folder and Its Subfolders](https://win-able.techidaily.com/how-i-finally-managed-to-start-rocket-league-after-persistent-problems/)
* [How to Delete Files With Wildcards](https://extra-lessons.techidaily.com/new-gamer-era-starts-djis-mavic-air-versus-spark-battle/)

### Key Takeaways

* To delete a file or folder, use the "Remove-Item PATH" cmdlet in PowerShell. In this command, replace "PATH" with the full path to the file or folder you want to remove.
* To delete all files in a folder but keep the folder, use the "Remove-Item PATH\\\*.\*" command, where "PATH" is the full path to the folder.
* To remove all files from a folder and its subfolders, use the "Remove-Item PATH -Recurse -Include \*.\*" command, replacing "PATH" with the full path to your parent folder.

 PowerShell offers a straightforward way to delete files and folders on your Windows 11 or Windows 10 PC. You can remove folders, all files inside a folder, specific files from the specified directory, and so on using just a few commands. Here's how to do that.

##  Before You Begin: How to Find a File or Folder’s Full Path

 To remove files or folders from your Windows PC, you’ll need the item’s full path. If you know [how to get file or folder paths](https://fox-links.techidaily.com/updated-2024-approved-unparalleled-screenplay-craftsmanship-across-varied-fields/), skip to the relevant section below. If you aren't sure how to copy a file or folder’s full path, we’ll show you how.

 First, [open a File Explorer window](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) and locate the file or folder whose path you want to find. Then, hold down the Shift key on your keyboard, right-click your file or folder, and choose "Copy as Path."

!['Copy as Path' highlighted in Windows' context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/1-copy-file-folder-path-windows.jpg) 

 You’ve successfully copied the selected item’s path to your clipboard. You can now [paste this path](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/) (using Ctrl+V) wherever required within the PowerShell window.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete a Specific File Using PowerShell

 To remove a specific file from your PC, use PowerShell’s "Remove-Item" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 Start by [opening a PowerShell window on your PC](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type the following command, replace "PATH" with the full path to the item you want to delete, and press Enter:

Remove-Item PATH

 As an example, to delete a file named "Old-List.txt" on your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old-List.txt"

![The 'Remove-Item' cmdlet to delete a file in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/2-delete-file-powershell.jpg) 

 Note that the command won’t ask for a confirmation before deleting your file. If you’d like the command to do that, add the "Confirm" parameter as follows:

Remove-Item "C:\Users\username\Desktop\Old-List.txt" -Confirm

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete a Specific Folder Using PowerShell

 You can use PowerShell’s "Remove-Item" cmdlet to remove any directory from your PC.

 Deleting a folder removes all the subfolders and files inside it.

 To start, launch PowerShell, type the following command, replace "PATH" with your directory’s full path, and press Enter:

Remove-Item PATH

 As an example, to delete a directory named "Old Files" from your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old Files"

![The 'Remove-Item' cmdlet to delete a folder in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/3-delete-folder-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete All Files in a Folder But Keep the Folder

 If you want to remove all files from a folder but retain the folder, use the "Remove-Item" cmdlet as follows.

 In your PowerShell window, type the following command, replace "PATH" with the full path to the folder you want to empty, add "\\\*.\*" before the final quotation mark, and press Enter:

Remove-Item PATH\*.*

 For example, to delete all files from a folder named "Your Files" from the desktop, run:

Remove-Item "C:\Users\username\Desktop\Your Files\*.*"

![The 'Remove-Item' cmdlet to delete all files inside a folder on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/4-delete-all-files-retain-folder-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In this command, the first asterisk selects files with any name, and the second asterisk chooses files with any extension. This translates to selecting all the files in the specified folder.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete All Files From a Folder and Its Subfolders

 If you’re looking to remove all files from a folder and its subfolders, add the "Recurse" and "Include" parameters to the "Remove-Item" cmdlet.

 Open a PowerShell window, enter the following command, replace "PATH" with the full path to the folder, and press Enter:

Remove-Item PATH -Recurse -Include *.*

 Here, the "Recurse" parameter ensures the subfolders’ files are deleted as well. The "Include" parameter ensures files with any name and extension are removed.

 As an example, to remove all files from the "Downloads" folder and its subfolders on the desktop, run:

Remove-Item "C:\Users\username\Desktop\Downloads" -Recurse -Include *.*

![The 'Remove-Item' cmdlet to recursively delete items on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/5-delete-files-subfolders-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Delete Files With Wildcards

 PowerShell offers wildcards, allowing you to delete various kinds of files by just specifying those file types in your command. In all the examples below, replace "PATH" with the full path to your folder.

 For example, if you want to remove all the [JPG](https://change-location.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-vivo-y27s-drfone-by-drfone-virtual-android/) files from a folder, use the following command:

Remove-Item PATH -Include *.jpg

 Another use of wildcards is to delete all but a specific file type from your directory. For example, to remove all files except for [PDF](https://extra-support.techidaily.com/new-obs-vs-wirecast-which-should-you-trust-for-live/) files from a folder, use the following command:

Remove-Item PATH -Exclude *.pdf

 Another advanced use of PowerShell is to remove all empty folders from the given directory. In this case, use the following command, replacing "PATH" with the full path to the directory:

Get-ChildItem -Recurse PATH | where { $_.PSISContainer -and @($_ | Get-ChildItem).Count -eq 0 } | Remove-Item

 And you're set.

---

 Now that you know how to delete items with PowerShell, you won't be stuck when File Explorer refuses to work. PowerShell offers more ways than File Explorer to help you remove content, like the ability to only remove specific files with a single command.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-effortlessly-access-fb-beats/"><u>[New] 2024 Approved  Effortlessly Access FB Beats</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-canvas-and-chroma-mastering-color-interaction/"><u>[New] Canvas and Chroma  Mastering Color Interaction</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snappy-secrets-learn-screen-recording-with-ease-on-smartphones/"><u>[New] In 2024, Snappy Secrets  Learn Screen Recording with Ease on Smartphones</u></a></li>
<li><a href="https://techidaily.com/solved-download-directx-12-for-windows-11/"><u>[SOLVED] Download DirectX 12 for Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-smoothing-face-transitions-motion-blur-techniques-in-picsart/"><u>[Updated] Smoothing Face Transitions  Motion Blur Techniques in Picsart</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-passport-photo-creation-made-easy-10-images-at-no-cost/"><u>2024 Approved  Passport Photo Creation Made Easy  10 Images at No Cost</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/amplify-your-influence-an-instagram-guide/"><u>Amplify Your Influence  An Instagram Guide</u></a></li>
<li><a href="https://techidaily.com/diagnosing-lag-problems-understanding-the-reason-behind-fps-drops-and-stutters-during-your-diablo-4-adventure/"><u>Diagnosing Lag Problems - Understanding the Reason Behind FPS Drops and Stutters During Your Diablo 4 Adventure</u></a></li>
<li><a href="https://techidaily.com/easy-steps-for-hooking-up-your-computers-to-a-wi-fi-network-securely-and-quickly/"><u>Easy Steps for Hooking up Your Computers to a Wi-Fi Network Securely and Quickly</u></a></li>
<li><a href="https://techidaily.com/easy-steps-to-download-and-generate-your-own-windows-ebyte-7-iso-file/"><u>Easy Steps to Download & Generate Your Own Windows Ebyte 7 ISO File</u></a></li>
<li><a href="https://techidaily.com/easy-tutorial-updating-and-downloading-epson-scanner-software-compatible-with-windows-11/"><u>Easy Tutorial: Updating and Downloading Epson Scanner Software Compatible with Windows 11</u></a></li>
<li><a href="https://techidaily.com/effortless-driver-updates-for-windows-7810-systems-a-guide/"><u>Effortless Driver Updates for Windows 7/8/10 Systems - A Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/expert-tips-resolving-iphones-inability-to-place-calls-easily/"><u>Expert Tips: Resolving iPhone's Inability to Place Calls Easily</u></a></li>
<li><a href="https://techidaily.com/expert-tutorial-enabling-and-using-remote-desktop-feature-in-windows-11/"><u>Expert Tutorial: Enabling and Using Remote Desktop Feature in Windows 11</u></a></li>
<li><a href="https://techidaily.com/exploring-vpn-tunneling-protocols-an-overview-and-typology/"><u>Exploring VPN Tunneling Protocols: An Overview and Typology</u></a></li>
<li><a href="https://technical-tips.techidaily.com/find-your-muse-with-these-top-11-inspirational-films-to-watch-now/"><u>Find Your Muse with These Top 11 Inspirational Films to Watch Now</u></a></li>
<li><a href="https://techidaily.com/how-to-change-icon-size-on-windows-11/"><u>How to Change Icon Size on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-securely-transfer-windows-11-documents-in-just-seven-steps/"><u>How to Securely Transfer Windows 11 Documents in Just Seven Steps!</u></a></li>
<li><a href="https://techidaily.com/how-to-unblock-torrent-sites-or-check-torrent-site-alternatives/"><u>How to Unblock Torrent Sites (Or Check Torrent Site Alternatives)</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/instant-vpn-configuration-tips-a-simple-step-by-step-process-for-secure-browsing/"><u>Instant VPN Configuration Tips: A Simple Step-by-Step Process for Secure Browsing</u></a></li>
<li><a href="https://techidaily.com/master-safe-mode-on-windows-10-explore-4-effective-methods-and-their-screenshots/"><u>Master Safe Mode on Windows 10: Explore 4 Effective Methods and Their Screenshots</u></a></li>
<li><a href="https://techidaily.com/maximize-your-pubg-matches-expert-strategies-to-skyrocket-fps-in-2020/"><u>Maximize Your PUBG Matches: Expert Strategies to Skyrocket FPS in 2020</u></a></li>
<li><a href="https://techidaily.com/overcome-high-disk-usage-problems-a-successful-fix-for-windows-10s-task-manager-dilemma/"><u>Overcome High Disk Usage Problems - A Successful Fix for Windows 10’S Task Manager Dilemma</u></a></li>
<li><a href="https://techidaily.com/quick-fix-removing-temporary-data-and-cache-for-a-smoother-windows-10-experience/"><u>Quick Fix: Removing Temporary Data & Cache for a Smoother Windows 10 Experience</u></a></li>
<li><a href="https://techidaily.com/quick-guide-how-to-seamlessly-translate-pages-with-google-chrome-mozilla-firefox-and-microsoft-edge/"><u>Quick Guide: How to Seamlessly Translate Pages with Google Chrome, Mozilla Firefox, and Microsoft Edge</u></a></li>
<li><a href="https://techidaily.com/reset-this-pc-windows-11-when-and-how-to-use-it/"><u>Reset This PC Windows 11 - When & How to Use It</u></a></li>
<li><a href="https://techidaily.com/simple-guide-discovering-your-pcs-specifications-on-windows-11/"><u>Simple Guide: Discovering Your PC's Specifications on Windows 11</u></a></li>
<li><a href="https://techidaily.com/simple-steps-for-finding-deleted-microsoft-word-documents-on-windows-10-plus-images/"><u>Simple Steps for Finding Deleted Microsoft Word Documents on Windows 10 + Images!</u></a></li>
<li><a href="https://techidaily.com/sleeker-starts-for-windows-10-systems-mastering-quick-boots/"><u>Sleeker Starts for Windows 10 Systems – Mastering Quick Boots</u></a></li>
<li><a href="https://techidaily.com/solution-found-thaw-your-stalled-windows-update-now/"><u>Solution Found: Thaw Your Stalled Windows Update Now</u></a></li>
<li><a href="https://techidaily.com/solving-non-functional-f8-on-windows-11-a-step-by-step-guide-for-successful-access-to-safe-mode/"><u>Solving Non-Functional F8 on Windows 11: A Step-by-Step Guide for Successful Access to Safe Mode</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-capturing-high-quality-videos-directly-from-your-pc/"><u>Step-by-Step Guide: Capturing High-Quality Videos Directly From Your PC</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-creating-a-bootable-win-11-usb-drive-from-iso-file/"><u>Step-by-Step Guide: Creating a Bootable Win 11 USB Drive From ISO File</u></a></li>
<li><a href="https://techidaily.com/step-by-step-techniques-to-overcome-latency-problems-with-your-logitech-mouse/"><u>Step-by-Step Techniques to Overcome Latency Problems with Your Logitech Mouse</u></a></li>
<li><a href="https://techidaily.com/step-by-step-tutorial-on-configuring-a-three-monitor-workstation/"><u>Step-by-Step Tutorial on Configuring a Three-Monitor Workstation</u></a></li>
<li><a href="https://techidaily.com/step-by-step-tutorial-on-enablingdisabling-hibernate-mode-for-windows-10-users/"><u>Step-by-Step Tutorial on Enabling/Disabling Hibernate Mode for Windows 10 Users</u></a></li>
<li><a href="https://techidaily.com/successful-guide-disabling-onedrive-integration-in-windows-11-file-explorer/"><u>Successful Guide: Disabling OneDrive Integration in Windows 11 File Explorer</u></a></li>
<li><a href="https://techidaily.com/tech-guide-detailed-steps-to-perform-a-complete-factory-reset-on-your-toshiba-computer/"><u>Tech Guide: Detailed Steps to Perform a Complete Factory Reset on Your Toshiba Computer</u></a></li>
<li><a href="https://techidaily.com/top-rated-vpn-services-for-enhancing-your-pc-gaming-experience/"><u>Top Rated VPN Services for Enhancing Your PC Gaming Experience</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-guide-resolving-windows-11-desktop-apps-and-data-sync-issues/"><u>Troubleshooting Guide: Resolving Windows 11 Desktop Apps and Data Sync Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-cant-change-resolution-solved/"><u>Windows 10 Can’t Change Resolution [SOLVED]</u></a></li>
</ul></div>
