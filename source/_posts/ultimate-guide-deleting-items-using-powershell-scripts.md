---
title: "Ultimate Guide: Deleting Items Using PowerShell Scripts"
date: 2024-09-19T18:09:18.043Z
updated: 2024-09-23T21:02:05.200Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/423415d175d6eec024525c4afdad758a2e4f561184514d4182ee660b64af6137.jpg
---

## Ultimate Guide: Deleting Items Using PowerShell Scripts

### Quick Links

* [Before You Begin: How to Find a File or Folder’s Full Path](https://extra-lessons.techidaily.com/navigate-iphones-dual-task-capabilities-effortlessly/)
* [How to Delete a Specific File Using PowerShell](https://youtube-video-recordings.techidaily.com/new-5-inspirational-winter-bgs-to-heat-your-videos/)
* [How to Delete a Specific Folder Using PowerShell](https://screen-mirror.techidaily.com/in-2024-how-can-honor-magic-5-litemirror-share-to-pc-drfone-by-drfone-android/)
* [How to Delete All Files in a Folder But Keep the Folder](https://extra-skills.techidaily.com/new-pushing-creative-boundaries-with-these-top-7-film-color-techniques/)
* [How to Delete All Files From a Folder and Its Subfolders](https://win-able.techidaily.com/how-i-finally-managed-to-start-rocket-league-after-persistent-problems/)
* [How to Delete Files With Wildcards](https://extra-lessons.techidaily.com/new-gamer-era-starts-djis-mavic-air-versus-spark-battle/)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
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

 You’ve successfully copied the selected item’s path to your clipboard. You can now [paste this path](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/) (using Ctrl+V) wherever required within the PowerShell window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Delete a Specific File Using PowerShell

 To remove a specific file from your PC, use PowerShell’s "Remove-Item" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 Start by [opening a PowerShell window on your PC](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type the following command, replace "PATH" with the full path to the item you want to delete, and press Enter:

Remove-Item PATH

 As an example, to delete a file named "Old-List.txt" on your desktop, you'd run:

Remove-Item "C:\Users\username\Desktop\Old-List.txt"

![The 'Remove-Item' cmdlet to delete a file in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/2-delete-file-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

##  How to Delete All Files in a Folder But Keep the Folder

 If you want to remove all files from a folder but retain the folder, use the "Remove-Item" cmdlet as follows.

 In your PowerShell window, type the following command, replace "PATH" with the full path to the folder you want to empty, add "\\\*.\*" before the final quotation mark, and press Enter:

Remove-Item PATH\*.*

 For example, to delete all files from a folder named "Your Files" from the desktop, run:

Remove-Item "C:\Users\username\Desktop\Your Files\*.*"

![The 'Remove-Item' cmdlet to delete all files inside a folder on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/4-delete-all-files-retain-folder-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-boxes.techidaily.com/new-discover-the-ultimate-in-samsung-gear-vr-entertainment/"><u>[New] Discover the Ultimate in Samsung Gear VR Entertainment</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-framefixer-editor/"><u>[Updated] In 2024, FrameFixer Editor</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/10-youtube-storytelling-techniques-that-work-for-2024/"><u>10 YouTube Storytelling Techniques That Work for 2024</u></a></li>
<li><a href="https://techidaily.com/6zu75b2x5ymq5o6l5oqa5ben6iih5pon5l2c5oyh5y2x77ya5zyo57ea5lik5a6m5oiq55qe6auy57sa5pwz6iky6kqy56il/"><u>電影剪接技巧與操作指南：在線上完成的高級教育課程</u></a></li>
<li><a href="https://techidaily.com/webmogg-movavi/"><u>在線自由WEBM轉OGG的方法 - 利用 Movavi 轉換器優化</u></a></li>
<li><a href="https://techidaily.com/convert-and-edit-videos-with-movavi-on-your-mac-ideal-for-various-codecs-and-formats/"><u>Convert and Edit Videos with Movavi on Your Mac: Ideal for Various Codecs and Formats</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-of-ls-0013-in-fortnite-comprehensive-guide/"><u>Fixing the Issue of LS-0013 in Fortnite - Comprehensive Guide</u></a></li>
<li><a href="https://techidaily.com/free-online-converter-change-mp4-audio-files-to-webm-format-using-movavi-tools/"><u>Free Online Converter: Change MP4 Audio Files to WebM Format Using Movavi Tools</u></a></li>
<li><a href="https://techidaily.com/gratuit-ogg-format-converter-online-opus-naar-ogg-omzetten-met-gratis-movavi-service/"><u>Gratuit Ogg-Format Converter: Online OPUS Naar Ogg Omzetten Met Gratis Movavi Service</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-vivo-t2-5g-phone-by-drfone-android/"><u>How to Unlock a Network Locked Vivo T2 5G Phone?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-g2-phone-without-google-account-by-drfone-android/"><u>How to Unlock Vivo G2 Phone without Google Account?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-infinix-note-30-vip-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Infinix Note 30 VIP Phones with/without a PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-y77t-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-mastering-mobile-and-dslr-shooting-igtv-with-perfection/"><u>In 2024, Mastering Mobile & DSLR Shooting IGTV with Perfection</u></a></li>
<li><a href="https://extra-hints.techidaily.com/samsung-ue590-ultra-hd-4k-gaming-and-freesync-screen/"><u>Samsung UE590 - Ultra HD 4K, Gaming & FreeSync Screen</u></a></li>
<li><a href="https://techidaily.com/ultimate-guide-choosing-the-right-camera-for-professional-music-video-production/"><u>Ultimate Guide: Choosing the Right Camera for Professional Music Video Production</u></a></li>
<li><a href="https://techidaily.com/understanding-bmp-files-a-comprehensive-guide-on-the-basics-of-bmp-images-and-viewing-them/"><u>Understanding BMP Files: A Comprehensive Guide on the Basics of .bmp Images & Viewing Them</u></a></li>
<li><a href="https://techidaily.com/voorbeurteiling-krijgt-gratis-startknop-voor-productsrecorderproductname-maakt-je-ervan-een-aanvanger/"><u>Voorbeurteiling Krijgt Gratis Startknop Voor {{ product('srecorder').product_name }}, Maakt Je Ervan Een Aanvanger</u></a></li>
<li><a href="https://techidaily.com/vullend-uw-mp4-op-naar-wma-expert-online-converteertool-movavi-gratis-aanbod/"><u>Vullend Uw MP4 Op Naar WMA: Expert Online Converteertool Movavi Gratis Aanbod</u></a></li>
<li><a href="https://techidaily.com/zoom-meetinglerin-eylemlerini-kontrol-alt-montajla-eam-ile-kaydetmek-movavi/"><u>Zoom Meetinglerin Eylemlerini Kontrol Alt Montajla (EAM) Ile Kaydetmek - Movavi</u></a></li>
</ul></div>

