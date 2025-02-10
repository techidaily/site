---
title: "Preserving Your Group Policy Preferences: A Step-by-Step Guide to Backing Up GPOs in Windows"
date: 2025-02-03T17:56:06.603Z
updated: 2025-02-09T19:24:19.083Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/1323edf73cef5ddeb6760a28b46d407c0ed89a3159fd177b98bcbf03f2bf6c24.jpg
---

## Preserving Your Group Policy Preferences: A Step-by-Step Guide to Backing Up GPOs in Windows

### Quick Links

* [Why You Should Back Up the Local Group Policy Editor Settings](https://android-location-track.techidaily.com/in-2024-3-ways-to-track-realme-12-proplus-5g-without-them-knowing-drfone-by-drfone-virtual-android/)
* [Back Up Local Group Policy Editor Settings With File Explorer](https://buynow-tips.techidaily.com/ultimate-comparison-how-the-samsung-galaxy-s23-ultra-stacks-up-against-the-s21-ultra/)
* [Back Up Local Group Policy Editor Settings With a Batch File](https://buynow-marvelous.techidaily.com/ultimate-guide-to-netgear-orbi-top-choice-in-mesh-wifi-routers/)
* [Back Up Local Group Policy Editor Settings With a PowerShell Script](https://tech-hub.techidaily.com/top-11-essential-gpt4-prompts-for-crafting-book-characters/)
* [How to Restore the Local Group Policy Editor Settings](https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-realme-c55-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [How to Back Up and Restore the Local Group Policy Editor Settings Using LGPO](https://fake-location.techidaily.com/will-ispoofer-update-on-oppo-f23-5g-drfone-by-drfone-virtual-android/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Backing up the Local Group Policy Editor settings is very easy. To do this, navigate to the "C:\\Windows\\System32\\GroupPolicy" folder and copy all of the files inside it. Then, navigate to the location where you want to back up the settings, create a new folder, and paste the copied files inside it.
* To restore your Local Group Policy Editor settings, open the folder where you backed up the settings and copy all the files inside it. Then, navigate to the "C:\\Windows\\System32\\GroupPolicy" folder and paste the copied files into it.

 Do you enjoy trying out experimental app features or Windows beta releases to stay ahead of the curve? If so, you must back up your Local Group Policy Editor settings, since this gives you the ability to hit rewind if your tinkering messes them up. Here are the different ways to do it.

##  Why You Should Back Up the Local Group Policy Editor Settings

 The Local Group Policy Editor is a [handy Windows utility](https://youtube-sure.techidaily.com/egize-your-content-approach-unveil-youtube-metrics-via-social-blade/) that allows you to configure [group policy](https://youtube-clips.techidaily.com/2024-approved-building-a-custom-link-for-youtubes-auto-subscribe/) settings on your computer. It's mainly aimed at network administrators, but it can also be used by individuals to manage how their machine performs. You can use the Local Group Policy Editor to change password requirements, [configure startup programs](https://fox-direct.techidaily.com/bigger-photos-uncompromised-clarity/), define which applications and settings a user can change, and more.

 Because the Local Group Policy Editor manages a wide range of necessary settings, it's important to back it up. Doing so gives you the freedom to try out different apps, unstable Windows releases, and experimental features without worrying about losing your settings. Even if something goes wrong, you can quickly restore the Local Group Policy Editor settings to bring your computer back to a known good state.

 It also means that you can transfer the settings to another machine, if you have got a new computer or want to deploy the same configuration across multiple systems.

##  1\. Back Up Local Group Policy Editor Settings With File Explorer

 The Local Group Policy Editor stores all its settings inside the [System32 folder](https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-messages-from-apple-iphone-7-plus-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/). You can quickly back up the Local Group Policy Editor settings by copying its relevant files and folders to a safe place.

 To do this, press Windows+E to open File Explorer and navigate to the following location:

        `C:\Windows\System32\GroupPolicy`
    
![GroupPolicy folder in the C drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/grouppolicy-folder.jpg) 

 Press Ctrl+A to select all the content of the "GroupPolicy" folder, and then press Ctrl+C to copy them. Now, go to the location where you want to store the backup. While this could be anywhere, we recommend backing it up on a separate hard drive or [Google Drive](https://data-wizards.techidaily.com/effortless-tactics-for-better-footage/). This way, the backup will remain safe even if your [computer crashes](https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-motorola-moto-g24-phone-by-drfone-android/) completely.

[Create a new folder](https://visual-screen-recording.techidaily.com/recording-made-simple-a-compreenasite-for-capturing-netflix-content/) in the location where you want to create the backup, then [paste the copied content](https://hardware-tips.techidaily.com/inside-look-at-new-electronics-tips-reviews-and-tech-news-from-tom/) inside the newly created folder.

##  2\. Back Up Local Group Policy Editor Settings With a Batch File

 A batch file is a script file that contains a series of commands that execute automatically when you run it. You can [create a batch file](https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-vivo-t2-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/) that will back up your Local Group Policy Editor settings.

 To do this, open the Start menu, type "Notepad" in the search bar, and press Enter. In Notepad, copy-paste the following code:

        `@echo off  
set BACKUP_DIR=%USERPROFILE%\Desktop\Local Group Policy Editor settings backup folder  
if not exist "%BACKUP_DIR%" (
md "%BACKUP_DIR%"  
)  
xcopy /E /I /Y "C:\Windows\System32\GroupPolicy" "%BACKUP_DIR%"  
attrib -H -S "%BACKUP_DIR%"  
attrib -H -S "%BACKUP_DIR%\*.*" /S /D`
    
![Back up script in Notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/back-up-script-1.jpg) 

 Then, click "File" in the top-left corner and choose "Save as". Name the file whatever you wish, with ".bat" appended. Then, select "All files" from the "Save as type" drop-down menu and click "Save".

![All files option in Notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/all-files.jpg) 

 Now, to back up your Local Group Policy Editor settings, go to the location where you saved the batch file, [right-click](https://desktop-recording.techidaily.com/updated-the-art-of-recording-fun-6-techniques-to-document-minecraft-for-2024/) on it, and choose "Run as administrator". This will create a new folder named "Local Group Policy Editor settings back up folder", which will contain all of your settings.

![Run as admin option in context menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/run-as-admin-option.jpg) 

 You will need to run the batch file again each time you change the Local Group Policy Editor settings, since the two aren't synced.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  3\. Back Up Local Group Policy Editor Settings With a PowerShell Script

 Backing up your local Group Policy Editor settings by running a batch file is a simple and straightforward process, but it can be easy to forget to run the batch file before [resetting your computer](https://extra-support.techidaily.com/2024-approved-mastering-video-editing-on-a-budget-with-free-fcp/). To avoid this, you can create a Windows PowerShell script and set up a backup task using the Task Scheduler. This way, Windows will automatically save a backup whenever you change the Local Group Policy settings.

 First, start by creating a Windows PowerShell script. To do this, open Notepad and paste the following code:

        `$source = 'C:\Windows\System32\GroupPolicy'  
$backupFolder = "$env:USERPROFILE\Desktop\Group Policy Backup"  
if (-not (Test-Path $backupFolder)) {  
    New-Item -ItemType Directory -Path $backupFolder | Out-Null  

$watcher = New-Object System.IO.FileSystemWatcher  
$watcher.Path = $source  
$watcher.IncludeSubdirectories = $true  
$watcher.EnableRaisingEvents = $true  
$action = {  
    if ($Event.SourceEventArgs.Name -eq "GPT.ini") {  
        Copy-Item -Path $source\* -Destination $backupFolder -Recurse -Force  

Register-ObjectEvent $watcher "Changed" -Action $action | Out-Null  
while ($true) {  
    Start-Sleep -Seconds 1  
}`
    
![PowerShell script in Notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/powershell-script.jpg) 

 Then, click "File" in the top-left corner and choose "Save as". Name the file, appending ".PS1". Then, select "All files" from the "Save as type" drop-down menu and click "Save".

![Save option in Notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/save-option.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, open the Start menu, type "Task Scheduler," and press Enter.

 In the Task Scheduler window, click the "Action" tab and choose "Create Basic Task". Type an appropriate name for the task in the "Name" field and click "Next".

![Name field in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/name-field.jpg) 

 In the Trigger tab, choose "When the computer starts" and click "Next".

![When the computer starts option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/when-the-computer-starts.jpg) 

 In the Action tab, choose "Start a program" and click "Next".

![Start a program in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/start-a-program.jpg) 

 In the Start a Program tab, paste the following location in the "Program/script" field:

        `C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe`
    
 Type the following in the "Add arguments" field. Replace "PowerShell\_Script\_Address" with the location where you have saved the PowerShell script:

        `-ExecutionPolicy Bypass -WindowStyle Hidden -File "PowerShell_Script_Address"`
    
![Next option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/next-option.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, click "Next" and "Finish".

![Finish option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/finish-option.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, whenever you change the Local Group Policy settings, the script runs automatically and saves the changes to the "Group Policy Backup" folder.

##  How to Restore the Local Group Policy Editor Settings

 As mentioned above, Windows stores the Local Group Policy Editor settings in the System32 folder. Therefore, regardless of how you backed up the settings, you can restore them by simply moving the backup files to the System32 folder.

 To do this, open the backup folder and copy all the files inside it. Then, navigate to the following location and paste the copied files to restore the Local Group Policy Editor settings:

        `C:\Windows\System32\GroupPolicy  
`
    
![GroupPolicy folder in the C drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/grouppolicy-folder.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Back Up and Restore the Local Group Policy Editor Settings Using LGPO

 Local Group Policy Object (LGPO) is a [command-line](https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) utility that you can use to automate the management of local group policy. It can export the current Local Group Policy settings to a file. This can be especially useful when you are switching to a new system and want to transfer your current device's Local Group Policy Editor settings.

 To use LGPO, visit this [Microsoft page](https://www.microsoft.com/en-us/download/details.aspx?id=55319) and click "Download". Then, select "LGPO.zip" and click the "Download" button.

![Download option in Microsoft Site](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/download.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the file is downloaded, [extract it](https://techtrends.techidaily.com/how-neo-qled-stacks-up-against-oled-a-comprehensive-guide/) somewhere on your computer. Then, open the extracted folder, copy the LGPO.exe file, and paste it in the following location:

        `C:\Windows\System32`
    
![LGPO File in File Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/lgpo-file.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Open the Start menu, type "Command Prompt" in the search bar, and click "Run as administrator". Type the following command in Command Prompt and press Enter. Replace "<backup\_folder\_address>" with the address of the folder where you want the utility to back up the Local Group Policy Editor settings.

        `LGPO.exe /b "<backup_folder_address>"`
    
![LGPO command in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/lgpo-command.jpg) 

 After that, open the backup folder, and you will see a folder with a random GUID name containing the settings. [Copy the folder to a pen drive](https://facebook-video-recording.techidaily.com/updated-introducing-top-tier-facebook-update-insights-for-2024/) or hard drive and move it to your new computer.

![GUID name folder in File Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/guid-name-folder.jpg) 

 To restore local GPO settings on your new computer, open Command Prompt as administrative rights on your new computer, type the following command, and press Enter. Replace "<GUID\_folder\_address>" with the address where you have saved the backup folder.

        `LGPO.exe /g "<GUID_folder_address>"`
    
![Restore command in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/restore-command.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the command is successfully executed, the Local Group Policy Editor settings will be restored on your new computer.

---

 After following these backup methods, you can now continue using experimental features on your computer without worrying about losing your local Group Policy Editor settings.

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
<li><a href="https://twitter-videos.techidaily.com/updated-reverse-silent-tweets-audible-video-connection/"><u>[Updated] Reverse Silent Tweets Audible Video Connection</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hack-high-speed-videos-for-engaging-instagram-stories/"><u>2024 Approved Hack High-Speed Videos for Engaging Instagram Stories</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-top-voice-transformation-tools-for-personal-use/"><u>2024 Approved Top Voice Transformation Tools for Personal Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-netstat-on-windows-11-a-guide-to-tracking-data-flow/"><u>Explore Netstat on Windows 11: A Guide to Tracking Data Flow</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-xs-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-t2-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-nord-3-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Nord 3 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x-fold-2-bootloader-easily-by-drfone-android/"><u>How to Unlock Vivo X Fold 2 Bootloader Easily</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-14-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 14 Pro Max Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-wasteland-ii-directors-cut-a-riveting-strategic-turn-based-adventure/"><u>In-Depth Analysis of Wasteland II (Director’s Cut): A Riveting Strategic Turn-Based Adventure</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/sonys-sonic-revolution-hearing-3d/"><u>Sony's Sonic Revolution: Hearing 3D</u></a></li>
</ul></div>

