---
title: Efficiently Deleting Files & Folders Using PowerShell Commands
date: 2025-02-16T23:51:59.936Z
updated: 2025-02-19T19:04:33.066Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To delete a file or folder, use the "Remove-Item PATH" cmdlet in PowerShell. In this command, replace "PATH" with the full path to the file or folder you want to remove.
* To delete all files in a folder but keep the folder, use the "Remove-Item PATH\\\*.\*" command, where "PATH" is the full path to the folder.
* To remove all files from a folder and its subfolders, use the "Remove-Item PATH -Recurse -Include \*.\*" command, replacing "PATH" with the full path to your parent folder.

 PowerShell offers a straightforward way to delete files and folders on your Windows 11 or Windows 10 PC. You can remove folders, all files inside a folder, specific files from the specified directory, and so on using just a few commands. Here's how to do that.

##  Before You Begin: How to Find a File or Folder’s Full Path

 To remove files or folders from your Windows PC, you’ll need the item’s full path. If you know [how to get file or folder paths](https://fox-links.techidaily.com/updated-2024-approved-unparalleled-screenplay-craftsmanship-across-varied-fields/), skip to the relevant section below. If you aren't sure how to copy a file or folder’s full path, we’ll show you how.

 First, [open a File Explorer window](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) and locate the file or folder whose path you want to find. Then, hold down the Shift key on your keyboard, right-click your file or folder, and choose "Copy as Path."

!['Copy as Path' highlighted in Windows' context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/1-copy-file-folder-path-windows.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You’ve successfully copied the selected item’s path to your clipboard. You can now [paste this path](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/) (using Ctrl+V) wherever required within the PowerShell window.

##  How to Delete a Specific File Using PowerShell

 To remove a specific file from your PC, use PowerShell’s "Remove-Item" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 Start by [opening a PowerShell window on your PC](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type the following command, replace "PATH" with the full path to the item you want to delete, and press Enter:

Remove-Item PATH

 As an example, to delete a file named "Old-List.txt" on your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old-List.txt"

![The 'Remove-Item' cmdlet to delete a file in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/2-delete-file-powershell.jpg) 

 Note that the command won’t ask for a confirmation before deleting your file. If you’d like the command to do that, add the "Confirm" parameter as follows:

Remove-Item "C:\Users\username\Desktop\Old-List.txt" -Confirm

##  How to Delete a Specific Folder Using PowerShell

 You can use PowerShell’s "Remove-Item" cmdlet to remove any directory from your PC.

 Deleting a folder removes all the subfolders and files inside it.

 To start, launch PowerShell, type the following command, replace "PATH" with your directory’s full path, and press Enter:

Remove-Item PATH

 As an example, to delete a directory named "Old Files" from your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old Files"

![The 'Remove-Item' cmdlet to delete a folder in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/3-delete-folder-powershell.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Delete All Files in a Folder But Keep the Folder

 If you want to remove all files from a folder but retain the folder, use the "Remove-Item" cmdlet as follows.

 In your PowerShell window, type the following command, replace "PATH" with the full path to the folder you want to empty, add "\\\*.\*" before the final quotation mark, and press Enter:

Remove-Item PATH\*.*

 For example, to delete all files from a folder named "Your Files" from the desktop, run:

Remove-Item "C:\Users\username\Desktop\Your Files\*.*"

![The 'Remove-Item' cmdlet to delete all files inside a folder on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/4-delete-all-files-retain-folder-powershell.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In this command, the first asterisk selects files with any name, and the second asterisk chooses files with any extension. This translates to selecting all the files in the specified folder.

##  How to Delete All Files From a Folder and Its Subfolders

 If you’re looking to remove all files from a folder and its subfolders, add the "Recurse" and "Include" parameters to the "Remove-Item" cmdlet.

 Open a PowerShell window, enter the following command, replace "PATH" with the full path to the folder, and press Enter:

Remove-Item PATH -Recurse -Include *.*

 Here, the "Recurse" parameter ensures the subfolders’ files are deleted as well. The "Include" parameter ensures files with any name and extension are removed.

 As an example, to remove all files from the "Downloads" folder and its subfolders on the desktop, run:

Remove-Item "C:\Users\username\Desktop\Downloads" -Recurse -Include *.*

![The 'Remove-Item' cmdlet to recursively delete items on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/5-delete-files-subfolders-powershell.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-optimize-your-zoom-soundscape-clear-channel-balance-achieved/"><u>[New] 2024 Approved Optimize Your Zoom Soundscape Clear Channel Balance Achieved</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-ultimate-platforms-for-animated-3d-creation/"><u>[New] 2024 Approved Ultimate Platforms for Animated 3D Creation</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-vmixfusion-for-dual-environments/"><u>[New] 2024 Approved VMixFusion for Dual Environments</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-action-footage-enhanced-top-mic-picks/"><u>[New] In 2024, Action Footage Enhanced Top Mic Picks</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/"><u>[New] In 2024, Virtual Voyage YouTube's Premier 10-VR Video Experience</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-insightful-guide-to-sharex-critiques-and-counterparts/"><u>[New] Insightful Guide to ShareX Critiques & Counterparts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-conquer-the-viewer-void-10-tactics-for-youtube-video-growth-for-2024/"><u>[Updated] Conquer the Viewer Void 10 Tactics for YouTube Video Growth for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-dive-deep-into-the-past-with-these-top-10-student-friendly-yt-channels/"><u>[Updated] Dive Deep Into the Past with These Top 10 Student-Friendly YT Channels</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-samsung-galaxy-s24-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oneplus-nord-3-5g-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an OnePlus Nord 3 5G Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-realme-narzo-60x-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Realme Narzo 60x 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-m6-pro-4g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco M6 Pro 4G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oneplus-open-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset OnePlus Open phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xr-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XR To Other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-honor-90-gt-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Honor 90 GT Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-k11x-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo K11x working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-vivo-v29e-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Vivo V29e working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-huawei-p60-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Huawei P60 Reset Code | Dr.fone</u></a></li>
</ul></div>

