---
title: "Ultimate Guide: Deleting Items Using PowerShell Scripts"
date: 2024-09-05T06:19:36.639Z
updated: 2024-09-06T06:19:36.639Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/423415d175d6eec024525c4afdad758a2e4f561184514d4182ee660b64af6137.jpg
---

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Ultimate Guide: Deleting Items Using PowerShell Scripts

### Quick Links

* [Before You Begin: How to Find a File or Folder’s Full Path](https://extra-lessons.techidaily.com/navigate-iphones-dual-task-capabilities-effortlessly/)
* [How to Delete a Specific File Using PowerShell](https://youtube-video-recordings.techidaily.com/new-5-inspirational-winter-bgs-to-heat-your-videos/)
* [How to Delete a Specific Folder Using PowerShell](https://screen-mirror.techidaily.com/in-2024-how-can-honor-magic-5-litemirror-share-to-pc-drfone-by-drfone-android/)
* [How to Delete All Files in a Folder But Keep the Folder](https://extra-skills.techidaily.com/new-pushing-creative-boundaries-with-these-top-7-film-color-techniques/)
* [How to Delete All Files From a Folder and Its Subfolders](https://win-able.techidaily.com/how-i-finally-managed-to-start-rocket-league-after-persistent-problems/)
* [How to Delete Files With Wildcards](https://extra-lessons.techidaily.com/new-gamer-era-starts-djis-mavic-air-versus-spark-battle/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* To delete a file or folder, use the "Remove-Item PATH" cmdlet in PowerShell. In this command, replace "PATH" with the full path to the file or folder you want to remove.
* To delete all files in a folder but keep the folder, use the "Remove-Item PATH\\\*.\*" command, where "PATH" is the full path to the folder.
* To remove all files from a folder and its subfolders, use the "Remove-Item PATH -Recurse -Include \*.\*" command, replacing "PATH" with the full path to your parent folder.

 PowerShell offers a straightforward way to delete files and folders on your Windows 11 or Windows 10 PC. You can remove folders, all files inside a folder, specific files from the specified directory, and so on using just a few commands. Here's how to do that.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094477/7443" target="_top" id="2094477">
  <img src="//a.impactradius-go.com/display-ad/7443-2094477" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094477/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Before You Begin: How to Find a File or Folder’s Full Path

 To remove files or folders from your Windows PC, you’ll need the item’s full path. If you know [how to get file or folder paths](https://fox-links.techidaily.com/updated-2024-approved-unparalleled-screenplay-craftsmanship-across-varied-fields/), skip to the relevant section below. If you aren't sure how to copy a file or folder’s full path, we’ll show you how.

 First, [open a File Explorer window](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) and locate the file or folder whose path you want to find. Then, hold down the Shift key on your keyboard, right-click your file or folder, and choose "Copy as Path."

!['Copy as Path' highlighted in Windows' context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/1-copy-file-folder-path-windows.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-essential-10-sport-streaming-tools-for-football-enthusiasts-for-2024/"><u>[New] Essential 10 Sport Streaming Tools for Football Enthusiasts for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-explore-a-world-of-delicious-treats-top-rated-cookie-shops/"><u>[New] Explore a World of Delicious Treats  Top-Rated Cookie Shops</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-5-pro-tips-to-perfectly-tag-videos-and-maximize-views/"><u>[New] In 2024, 5 Pro Tips to Perfectly Tag Videos and Maximize Views</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-content-creation-conundrum-where-to-go/"><u>[Updated] In 2024, Content Creation Conundrum  Where to Go?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-essential-screenshot-and-recording-tools-for-learning-environments/"><u>[Updated] In 2024, Essential Screenshot & Recording Tools for Learning Environments</u></a></li>
<li><a href="https://techidaily.com/1-idoc-scanner-app-effortless-pdf-conversion-using-ios-and-android/"><u>1. IDoc Scanner App - Effortless PDF Conversion Using iOS & Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hololens-review-pioneering-virtual-spacecraft/"><u>2024 Approved  HoloLens Review  Pioneering Virtual Spacecraft</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-art-of-vivid-visuals-on-your-computer-with-windows-hdr/"><u>2024 Approved  The Art of Vivid Visuals on Your Computer with Windows HDR</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/7-critical-practices-for-controlling-instagram-tv-videosize-for-2024/"><u>7 Critical Practices for Controlling Instagram TV Videosize for 2024</u></a></li>
<li><a href="https://techidaily.com/abbyy-and-the-hamburg-football-association-a-strategic-partnership/"><u>ABBYY and the Hamburg Football Association: A Strategic Partnership</u></a></li>
<li><a href="https://techidaily.com/abbyys-board-guidance-by-expert-alex-beregovsky/"><u>ABBYY's Board Guidance by Expert, Alex Beregovsky</u></a></li>
<li><a href="https://techidaily.com/advancements-in-ai-and-reducing-value-delivery-gaps-within-smart-businesses/"><u>Advancements in AI and Reducing Value Delivery Gaps Within Smart Businesses</u></a></li>
<li><a href="https://techidaily.com/beyond-mundane-chores-how-abbyy-is-transforming-standard-operations/"><u>Beyond Mundane Chores: How ABBYY Is Transforming Standard Operations</u></a></li>
<li><a href="https://os-tips.techidaily.com/breaking-news-apple-ceases-production-on-watch-series-9-and-upcoming-ultra-edition/"><u>Breaking News: Apple Ceases Production on Watch Series 9 and Upcoming Ultra Edition</u></a></li>
<li><a href="https://extra-information.techidaily.com/calculating-expenses-for-youtubers-success/"><u>Calculating Expenses for YouTubers' Success</u></a></li>
<li><a href="https://techidaily.com/cookiebot-driven-analytics-boost-your-websites-performance-and-insights/"><u>Cookiebot Driven Analytics - Boost Your Website's Performance and Insights</u></a></li>
<li><a href="https://techidaily.com/cookiebot-driven-performance-unleashing-advanced-website-traffic/"><u>Cookiebot-Driven Performance: Unleashing Advanced Website Traffic</u></a></li>
<li><a href="https://techidaily.com/cookiebot-driven-personalization-tailoring-your-websites-interaction-for-optimal-engagement/"><u>Cookiebot-Driven Personalization: Tailoring Your Website's Interaction for Optimal Engagement</u></a></li>
<li><a href="https://techidaily.com/cookiebot-enabled-personalized-experience/"><u>Cookiebot-Enabled Personalized Experience</u></a></li>
<li><a href="https://techidaily.com/cookiebot-enabled-enhance-your-websites-performance/"><u>Cookiebot-Enabled: Enhance Your Website's Performance</u></a></li>
<li><a href="https://techidaily.com/cookiebot-enabled-enhance-your-websites-user-experience-with-smart-tracking/"><u>Cookiebot-Enabled: Enhance Your Website's User Experience with Smart Tracking</u></a></li>
<li><a href="https://techidaily.com/cookiebot-enhanced-sites-boost-your-visibility-with-advanced-tracking/"><u>Cookiebot-Enhanced Sites: Boost Your Visibility with Advanced Tracking</u></a></li>
<li><a href="https://techidaily.com/cookiebot-the-key-ingredient-in-boosting-website-engagement-and-personalization/"><u>Cookiebot: The Key Ingredient in Boosting Website Engagement and Personalization</u></a></li>
<li><a href="https://techidaily.com/cookiebots-revolutionary-impact-on-seo-and-conversion-optimization-for-enhanced-digital-marketing-results/"><u>Cookiebot's Revolutionary Impact on SEO and Conversion Optimization for Enhanced Digital Marketing Results</u></a></li>
<li><a href="https://techidaily.com/drive-traffic-with-cutting-edge-automated-tracking-the-power-of-cookiebot/"><u>Drive Traffic with Cutting-Edge Automated Tracking: The Power of Cookiebot</u></a></li>
<li><a href="https://techidaily.com/elevate-user-engagement-optimized-tracking-through-innovative-cookiebot-solutions/"><u>Elevate User Engagement: Optimized Tracking Through Innovative Cookiebot Solutions</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722991259439-end-code-vein-freeze-woes-effective-troubleshooting-methods-revealed/"><u>End Code Vein Freeze Woes: Effective Troubleshooting Methods Revealed!</u></a></li>
<li><a href="https://techidaily.com/enhanced-targeting-with-the-cookiebot-technology/"><u>Enhanced Targeting with the Cookiebot Technology</u></a></li>
<li><a href="https://techidaily.com/entendiendo-la-politica-de-recetas-en-el-software-abbyy-una-guia-completa/"><u>Entendiendo La Política De Recetas en El Software Abbyy: Una Guía Completa</u></a></li>
<li><a href="https://techidaily.com/experience-swift-scanning-solutions-with-new-abbyy-finescanner-for-ios-maximizing-your-productivity-and-streamlining-document-management/"><u>Experience Swift Scanning Solutions with New ABBYY FineScanner for iOS - Maximizing Your Productivity and Streamlining Document Management!</u></a></li>
<li><a href="https://techidaily.com/explore-the-future-of-document-management-with-abbyy-join-us-at-pegaworld-inspire-2023-event/"><u>Explore the Future of Document Management with ABBYY - Join Us at PegaWorld Inspire 2023 Event</u></a></li>
<li><a href="https://techidaily.com/harnessing-cookiebot-technology-for-improved-online-engagement/"><u>Harnessing Cookiebot Technology for Improved Online Engagement</u></a></li>
<li><a href="https://techidaily.com/how-artificial-intelligence-is-reshaping-accounts-payable-a-deep-dive-with-abbyy-experts/"><u>How Artificial Intelligence Is Reshaping Accounts Payable - A Deep Dive with ABBYY Experts</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-launch-multiversus-successfully-after-encountering-errors-on-desktop/"><u>How to Launch MultiVersus Successfully After Encountering Errors on Desktop</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-quickly-download-and-install-sandisk-drivers-on-your-windows-11-device/"><u>How to Quickly Download and Install SanDisk Drivers on Your Windows 11 Device</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y27-5g-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo Y27 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-xiaomi-mix-fold-3-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Xiaomi Mix Fold 3? Try These Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nokia-g42-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nokia G42 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-ispoofer-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Vivo V30? | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723964499541-include-at-least-three-rhetorical-questions-to-engage-the-audience/"><u>Include at Least Three Rhetorical Questions to Engage the Audience.</u></a></li>
<li><a href="https://win-amazing.techidaily.com/instant-connection-with-your-xbox-gamepad-secure-your-controller-drivers-today/"><u>Instant Connection with Your Xbox Gamepad - Secure Your Controller Drivers Today!</u></a></li>
<li><a href="https://techidaily.com/intelligence-driven-document-processing-elevating-your-companys-service-offerings/"><u>Intelligence-Driven Document Processing: Elevating Your Company's Service Offerings</u></a></li>
<li><a href="https://techidaily.com/is-upgrading-to-ios-14-a-smart-move-pros-and-cons-explored/"><u>Is Upgrading to iOS 14 a Smart Move? – Pros and Cons Explored</u></a></li>
<li><a href="https://techidaily.com/leveraging-cookiebots-power-for-superior-web-presence/"><u>Leveraging Cookiebot's Power for Superior Web Presence</u></a></li>
<li><a href="https://techidaily.com/leveraging-neural-networks-for-id-document-image-extraction-with-abbyy-techniques/"><u>Leveraging Neural Networks for ID Document Image Extraction with ABBYY Techniques</u></a></li>
<li><a href="https://fox-that.techidaily.com/locate-and-secure-your-disappearing-iphone-with-the-find-my-tool/"><u>Locate and Secure Your Disappearing iPhone with the Find My Tool</u></a></li>
<li><a href="https://techidaily.com/model-c-safety-first-1920-5-fixed-rear-sight-safety-feature-incorporated-into-the-design-of-the-grip-assembly-underneath-the-hammer-similar-to-a-cross-bolt-18/"><u>Model C (Safety First) - 1920-5, Fixed Rear Sight, Safety Feature Incorporated Into the Design of the Grip Assembly Underneath the Hammer (Similar to a Cross Bolt Screwdriver), Fluted Grip</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-crafting-impactful-hashtags-for-instagram-content-for-2024/"><u>The Art of Crafting Impactful Hashtags for Instagram Content for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-analysis-amazfit-bip-the-ideal-beginners-smartwatch/"><u>Ultimate Analysis: Amazfit Bip - The Ideal Beginner's Smartwatch</u></a></li>
<li><a href="https://techidaily.com/unleashing-traffic-with-cookiebot-technology-a-game-changer-for-seo-strategies/"><u>Unleashing Traffic with Cookiebot Technology: A Game-Changer for SEO Strategies</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-motorola-moto-g23-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Motorola Moto G23 Phones</u></a></li>
</ul></div>
