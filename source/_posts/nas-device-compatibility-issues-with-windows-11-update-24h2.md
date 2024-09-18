---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-09-13T18:00:35.579Z
updated: 2024-09-18T18:39:50.411Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/windows-11-3.jpg
---

## NAS Device Compatibility Issues with Windows 11 Update 24H2

The Windows 11 24H2 update is nearing release, and it comes with a few changes that could break specific apps and workflows. Microsoft is now warning people (again) about changes to SMB connections that might impact NAS drives.

 Microsoft just [released the Windows 11 24H2 update in the Release Preview Channel](https://some-knowledge.techidaily.com/in-2024-illumination-in-high-dynamic-range-a-smart-option/), ahead of its rollout to all Windows 11 PCs in a few months. The update requires SMB signing on all connections and removes support for guest fallback on Windows 11 Pro edition. Those are important security upgrades, but they also mean some network drives and folders won’t work anymore without changes to settings or software upgrades.

 Microsoft said in a blog post, “SMB signing has been available in Windows for 30 years but, for the first time, is now required by default on all connections. Guest has been disabled in Windows for 25 years and SMB guest fallback disabled since Windows 10 in Enterprise, Education, and Pro for Workstation editions. Both changes will make billions of devices more secure. They've been in Windows Insider Dev and Canary builds for a year.”

 This will mainly affect older NAS devices and other network devices that aren’t configured for SMB signing. Newer NAS hardware should already have that working and configured, but there’s a chance some device manufacturers didn’t bother because it wasn’t strictly required (until now).

 Microsoft recommends setting up SMB signing on your NAS, setting up a username and password, and turning off guest sign in. If none of those options are available, you can try checking for software updates on the NAS—the manufacturer might have implemented those features after the device was shipped.

 For NAS devices that don’t support the required security features and don’t have any updates, there will be a workaround available in the Edit Group Policy app. However, Microsoft warns that that the steps “will make your Windows device and your data much less safe.”

 Windows 24H2 is expected to be released in a few months, but it might take longer than that to roll out to all Windows 11 PCs automatically.

 Source: [Microsoft Blog](https://techcommunity.microsoft.com/t5/storage-at-microsoft/accessing-a-third-party-nas-with-smb-in-windows-11-24h2-may-fail/ba-p/4154300)

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-unbeatable-ps1-emulators-for-high-quality-gaming/"><u>[New] 2024 Approved Unbeatable PS1 Emulators for High-Quality Gaming</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-expertly-crafted-cloud-microphones-for-2024/"><u>[New] Expertly-Crafted Cloud Microphones for 2024</u></a></li>
<li><a href="https://discover-best.techidaily.com/efficient-online-and-desktop-solutions-for-modifying-mpeg-video-format/"><u>Efficient Online & Desktop Solutions for Modifying MPEG Video Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/game-on-microsoft-and-blizzards-tech-symbiosis-explored-with-ai-insights-podcast-segment/"><u>Game On! Microsoft and Blizzard's Tech Symbiosis Explored with AI Insights [Podcast Segment]</u></a></li>
<li><a href="https://techidaily.com/1723808261745-guide-preventing-unwanted-windows-11-updates-without-hitches/"><u>Guide: Preventing Unwanted Windows 11 Updates Without Hitches</u></a></li>
<li><a href="https://techidaily.com/1723808074120-mastering-the-art-of-playing-minecraft-without-wifi-tips-and-steps-for-windows-11-users/"><u>Mastering the Art of Playing Minecraft Without WiFi: Tips and Steps for Windows 11 Users</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808152090-skyrim-se-upgrade-maximize-your-gameplay-with-revolutionary-fps-improvement-and-beyond/"><u>Skyrim SE Upgrade: Maximize Your Gameplay with Revolutionary FPS Improvement and Beyond!</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/uniting-technologies-mondly-plus-pearson-buttons-fusion/"><u>Uniting Technologies: Mondly + Pearson Buttons Fusion</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

