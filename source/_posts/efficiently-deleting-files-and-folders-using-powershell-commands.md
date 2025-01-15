---
title: Efficiently Deleting Files & Folders Using PowerShell Commands
date: 2025-01-09T17:27:48.904Z
updated: 2025-01-15T19:31:52.165Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Before You Begin: How to Find a File or Folder’s Full Path

 To remove files or folders from your Windows PC, you’ll need the item’s full path. If you know [how to get file or folder paths](https://fox-links.techidaily.com/updated-2024-approved-unparalleled-screenplay-craftsmanship-across-varied-fields/), skip to the relevant section below. If you aren't sure how to copy a file or folder’s full path, we’ll show you how.

 First, [open a File Explorer window](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) and locate the file or folder whose path you want to find. Then, hold down the Shift key on your keyboard, right-click your file or folder, and choose "Copy as Path."

!['Copy as Path' highlighted in Windows' context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/1-copy-file-folder-path-windows.jpg) 

 You’ve successfully copied the selected item’s path to your clipboard. You can now [paste this path](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/) (using Ctrl+V) wherever required within the PowerShell window.

##  How to Delete a Specific File Using PowerShell

 To remove a specific file from your PC, use PowerShell’s "Remove-Item" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 Start by [opening a PowerShell window on your PC](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type the following command, replace "PATH" with the full path to the item you want to delete, and press Enter:

Remove-Item PATH

 As an example, to delete a file named "Old-List.txt" on your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old-List.txt"

![The 'Remove-Item' cmdlet to delete a file in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/2-delete-file-powershell.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that the command won’t ask for a confirmation before deleting your file. If you’d like the command to do that, add the "Confirm" parameter as follows:

Remove-Item "C:\Users\username\Desktop\Old-List.txt" -Confirm

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Delete All Files in a Folder But Keep the Folder

 If you want to remove all files from a folder but retain the folder, use the "Remove-Item" cmdlet as follows.

 In your PowerShell window, type the following command, replace "PATH" with the full path to the folder you want to empty, add "\\\*.\*" before the final quotation mark, and press Enter:

Remove-Item PATH\*.*

 For example, to delete all files from a folder named "Your Files" from the desktop, run:

Remove-Item "C:\Users\username\Desktop\Your Files\*.*"

![The 'Remove-Item' cmdlet to delete all files inside a folder on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/4-delete-all-files-retain-folder-powershell.jpg) 

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-become-a-shorts-connoisseur-must-know-facts/"><u>[New] 2024 Approved Become a Shorts Connoisseur Must-Know Facts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-mastering-your-content-on-facebook-after-algorithms-change/"><u>[New] Mastering Your Content on Facebook After Algorithms Change</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-apple-iphone-8-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On Apple iPhone 8 How to Bypass?</u></a></li>
<li><a href="https://techidaily.com/beginning-online-easy-instructions-for-crafting-a-google-id/"><u>Beginning Online: Easy Instructions for Crafting a Google ID</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bypassing-troublesome-skype-errors-a-guide-to-10-key-solutions/"><u>Bypassing Troublesome Skype Errors: A Guide to 10 Key Solutions</u></a></li>
<li><a href="https://techidaily.com/1723808102827-cant-access-chatgpt-here-are-5-quick-solutions-to-get-it-running-again/"><u>Can't Access ChatGPT? Here Are 5 Quick Solutions To Get It Running Again</u></a></li>
<li><a href="https://some-guidance.techidaily.com/descargar-conversion-de-mkv-a-lineal-sin-costo-con-movavi/"><u>Descargar Conversion De MKV a Lineal Sin Costo Con Movavi</u></a></li>
<li><a href="https://techidaily.com/1723808105093-fixing-a-frozen-windows-update-easily-get-your-system-updating-again/"><u>Fixing a Frozen Windows Update Easily – Get Your System Updating Again</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-14-pro-without-losing-any-content-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 14 Pro without Losing Any Content? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808210693-maintenance-therapy-typically-involves-lower-doses-of-steroids-with-azathioprine-or-continued-use-of-mycophenolate-mofetil-to-prevent-relapses/"><u>Maintenance Therapy Typically Involves Lower Doses of Steroids with Azathioprine or Continued Use of Mycophenolate Mofetil to Prevent Relapses.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/maximize-fun-choose-from-heres-top-5-chrome-extensions-for-facebook-vids/"><u>Maximize Fun Choose From Here's Top 5 Chrome Extensions for Facebook Vids</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-10plus-free-online-audio-to-text-converters-for-2024/"><u>New 10+ Free Online Audio to Text Converters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://techidaily.com/ultimate-tutorial-gaining-full-access-with-the-command-prompt-in-windows-through-admin-rights/"><u>Ultimate Tutorial: Gaining Full Access with the Command Prompt in Windows Through Admin Rights</u></a></li>
<li><a href="https://techidaily.com/understanding-random-password-generators-a-comprehensive-guide-on-functionality-and-application/"><u>Understanding Random Password Generators: A Comprehensive Guide on Functionality & Application</u></a></li>
<li><a href="https://techidaily.com/windows-10-tweaks-and-tips-for-a-superior-gaming-setup-enhance-your-play-today/"><u>Windows 10 Tweaks and Tips for a Superior Gaming Setup – Enhance Your Play Today!</u></a></li>
<li><a href="https://techidaily.com/windows-users-unite-mastering-graphics-driver-resets-in-11-10-and-7/"><u>Windows Users Unite! Mastering Graphics Driver Resets in 11, 10 & 7</u></a></li>
</ul></div>

