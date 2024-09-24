---
title: "Preserving Your Group Policy Preferences: A Step-by-Step Guide to Backing Up GPOs in Windows"
date: 2024-09-18T01:58:46.921Z
updated: 2024-09-24T06:44:15.425Z
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
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* Backing up the Local Group Policy Editor settings is very easy. To do this, navigate to the "C:\\Windows\\System32\\GroupPolicy" folder and copy all of the files inside it. Then, navigate to the location where you want to back up the settings, create a new folder, and paste the copied files inside it.
* To restore your Local Group Policy Editor settings, open the folder where you backed up the settings and copy all the files inside it. Then, navigate to the "C:\\Windows\\System32\\GroupPolicy" folder and paste the copied files into it.

 Do you enjoy trying out experimental app features or Windows beta releases to stay ahead of the curve? If so, you must back up your Local Group Policy Editor settings, since this gives you the ability to hit rewind if your tinkering messes them up. Here are the different ways to do it.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, click "File" in the top-left corner and choose "Save as". Name the file whatever you wish, with ".bat" appended. Then, select "All files" from the "Save as type" drop-down menu and click "Save".

![All files option in Notepad](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/all-files.jpg) 

 Now, to back up your Local Group Policy Editor settings, go to the location where you saved the batch file, [right-click](https://desktop-recording.techidaily.com/updated-the-art-of-recording-fun-6-techniques-to-document-minecraft-for-2024/) on it, and choose "Run as administrator". This will create a new folder named "Local Group Policy Editor settings back up folder", which will contain all of your settings.

![Run as admin option in context menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/run-as-admin-option.jpg) 

 You will need to run the batch file again each time you change the Local Group Policy Editor settings, since the two aren't synced.

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

 Now, open the Start menu, type "Task Scheduler," and press Enter.

 In the Task Scheduler window, click the "Action" tab and choose "Create Basic Task". Type an appropriate name for the task in the "Name" field and click "Next".

![Name field in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/name-field.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the Trigger tab, choose "When the computer starts" and click "Next".

![When the computer starts option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/when-the-computer-starts.jpg) 

 In the Action tab, choose "Start a program" and click "Next".

![Start a program in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/start-a-program.jpg) 

 In the Start a Program tab, paste the following location in the "Program/script" field:

        `C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe`
    
 Type the following in the "Add arguments" field. Replace "PowerShell\_Script\_Address" with the location where you have saved the PowerShell script:

        `-ExecutionPolicy Bypass -WindowStyle Hidden -File "PowerShell_Script_Address"`
    
![Next option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/next-option.jpg) 

 Then, click "Next" and "Finish".

![Finish option in Task Scheduler](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/finish-option.jpg) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, whenever you change the Local Group Policy settings, the script runs automatically and saves the changes to the "Group Policy Backup" folder.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Restore the Local Group Policy Editor Settings

 As mentioned above, Windows stores the Local Group Policy Editor settings in the System32 folder. Therefore, regardless of how you backed up the settings, you can restore them by simply moving the backup files to the System32 folder.

 To do this, open the backup folder and copy all the files inside it. Then, navigate to the following location and paste the copied files to restore the Local Group Policy Editor settings:

        `C:\Windows\System32\GroupPolicy  
`
    
![GroupPolicy folder in the C drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/grouppolicy-folder.jpg) 

##  How to Back Up and Restore the Local Group Policy Editor Settings Using LGPO

 Local Group Policy Object (LGPO) is a [command-line](https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) utility that you can use to automate the management of local group policy. It can export the current Local Group Policy settings to a file. This can be especially useful when you are switching to a new system and want to transfer your current device's Local Group Policy Editor settings.

 To use LGPO, visit this [Microsoft page](https://www.microsoft.com/en-us/download/details.aspx?id=55319) and click "Download". Then, select "LGPO.zip" and click the "Download" button.

![Download option in Microsoft Site](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/download.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the file is downloaded, [extract it](https://techtrends.techidaily.com/how-neo-qled-stacks-up-against-oled-a-comprehensive-guide/) somewhere on your computer. Then, open the extracted folder, copy the LGPO.exe file, and paste it in the following location:

        `C:\Windows\System32`
    
![LGPO File in File Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/lgpo-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Open the Start menu, type "Command Prompt" in the search bar, and click "Run as administrator". Type the following command in Command Prompt and press Enter. Replace "<backup\_folder\_address>" with the address of the folder where you want the utility to back up the Local Group Policy Editor settings.

        `LGPO.exe /b "<backup_folder_address>"`
    
![LGPO command in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/lgpo-command.jpg) 

 After that, open the backup folder, and you will see a folder with a random GUID name containing the settings. [Copy the folder to a pen drive](https://facebook-video-recording.techidaily.com/updated-introducing-top-tier-facebook-update-insights-for-2024/) or hard drive and move it to your new computer.

![GUID name folder in File Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/guid-name-folder.jpg) 

 To restore local GPO settings on your new computer, open Command Prompt as administrative rights on your new computer, type the following command, and press Enter. Replace "<GUID\_folder\_address>" with the address where you have saved the backup folder.

        `LGPO.exe /g "<GUID_folder_address>"`
    
![Restore command in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/restore-command.jpg) 

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
<li><a href="https://youtube-webster.techidaily.com/ross-platform-strategies-to-boost-youtube-presence/"><u>[New] Cross-Platform Strategies to Boost YouTube Presence</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-selecting-the-top-cameras-for-smooth-twitch-broadcasts-for-2024/"><u>[New] Selecting the Top Cameras for Smooth Twitch Broadcasts for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/outube-as-a-learning-tool-insider-advice-for-teachers/"><u>[New] YouTube as a Learning Tool Insider Advice for Teachers</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-from-good-to-great-unveiling-video-enhance-22-secrets/"><u>[Updated] From Good to Great Unveiling Video Enhance 2.2 Secrets</u></a></li>
<li><a href="https://win-dash.techidaily.com/comprehensive-guide-install-and-update-elans-smbus-driver-for-optimal-performance-on-windows-computers/"><u>Comprehensive Guide: Install and Update ELAN's SMBus Driver for Optimal Performance on Windows Computers</u></a></li>
<li><a href="https://techidaily.com/effortless-aiff-to-mp3-transformation-explore-movavis-free-service-options/"><u>Effortless AIFF-to-MP3 Transformation - Explore Movavi’s Free Service Options</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-guide-to-the-top-5-windows-snipper-tools-for-2024/"><u>Essential Guide to The Top 5 Windows Snipper Tools for 2024</u></a></li>
<li><a href="https://techidaily.com/f4v-to-mp3-converter-professionele-online-konvertiering-ohne-kosten-movavi/"><u>F4V-to-MP3 Converter: Professionele Online Konvertiering Ohne Kosten - Movavi</u></a></li>
<li><a href="https://techidaily.com/formato-de-archivo-libre-conversion-wav-a-ogg-sin-coste/"><u>Formato De Archivo Libre Conversión WAV a OGG Sin Coste</u></a></li>
<li><a href="https://techidaily.com/free-and-online-conversion-how-to-transform-your-avi-files-into-quicktime-mov-format/"><u>Free and Online Conversion: How to Transform Your AVI Files Into QuickTime MOV Format</u></a></li>
<li><a href="https://techidaily.com/free-mp3-conversion-mov-to-mp3-with-moveavis-reliable-online-tool/"><u>Free MP3 Conversion: MOV to MP3 with Moveavi's Reliable Online Tool</u></a></li>
<li><a href="https://techidaily.com/free-mp4-wmv-file-transformation-service-available-on-movavi-platform/"><u>Free MP4-WMV File Transformation Service Available on Movavi Platform</u></a></li>
<li><a href="https://techidaily.com/free-online-conversion-transform-wtv-files-into-mp4-format-with-just-a-click/"><u>Free Online Conversion: Transform WTV Files Into MP4 Format with Just a Click</u></a></li>
<li><a href="https://techidaily.com/free-online-conversion-transforming-video-output-bundles-vob-into-mobile-compatible-mov-files-easily/"><u>Free Online Conversion: Transforming Video Output Bundles (VOB) Into Mobile-Compatible MOV Files Easily</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-disabled-iphone-xs-maxipad-without-computer-by-drfone-ios/"><u>How to Unlock Disabled iPhone XS Max/iPad Without Computer</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-gionee-f3-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Gionee F3 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mix-magic-how-to-download-top-dj-content/"><u>Mix Magic How to Download Top DJ Content</u></a></li>
</ul></div>

