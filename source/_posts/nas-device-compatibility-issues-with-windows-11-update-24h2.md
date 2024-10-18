---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-10-13T03:33:47.702Z
updated: 2024-10-17T22:32:17.470Z
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
<li><a href="https://facebook-video-files.techidaily.com/new-strategic-shifts-in-social-media-predictions-for-facebooks-future/"><u>[New] Strategic Shifts in Social Media Predictions for Facebook's Future</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-how-to-make-macbook-pro-video-tutorials-easy-for-2024/"><u>[Updated] How to Make Macbook Pro Video Tutorials Easy for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-instilling-illusions-blur-wonders-in-adobes-visual-staging-tools-for-2024/"><u>[Updated] Instilling Illusions Blur Wonders in Adobe's Visual Staging Tools for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streamlined-steps-easy-recording-on-vimeo/"><u>[Updated] Streamlined Steps Easy Recording on Vimeo</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/conquering-cloud-storage-with-easy-tv-series-capture-methods/"><u>Conquering Cloud Storage with Easy TV Series Capture Methods</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-tecno-spark-10-4g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Tecno Spark 10 4G Phone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/microsoft-copilot-now-on-new-laptops-browse-the-best-selection-of-snapdragon-elite-x-machines-for-immediate-purchase/"><u>Microsoft Copilot Now on New Laptops - Browse the Best Selection of Snapdragon Elite X Machines for Immediate Purchase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-designations-c-and-d-varieties/"><u>Navigating Disk Designations: C and D Varieties</u></a></li>
<li><a href="https://printer-issues.techidaily.com/rapid-recovery-from-common-pcl-xl-failures/"><u>Rapid Recovery From Common PCL XL Failures</u></a></li>
<li><a href="https://techidaily.com/the-quickest-ways-to-isolate-and-save-audio-from-online-videos/"><u>The Quickest Ways to Isolate and Save Audio From Online Videos</u></a></li>
<li><a href="https://techidaily.com/top-5-netflix-friendly-vpns-enhancing-streaming-privacy/"><u>Top 5 Netflix-Friendly VPNs Enhancing Streaming Privacy</u></a></li>
<li><a href="https://techidaily.com/top-7-solutions-to-resolve-goose-duck-glitch-in-pc-games/"><u>Top 7 Solutions to Resolve 'Goose-Duck' Glitch in PC Games</u></a></li>
<li><a href="https://techidaily.com/transfer-your-chrome-favorites-to-firefox-in-a-flash-a-step-by-step-guide/"><u>Transfer Your Chrome Favorites to Firefox in a Flash: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-guide-for-resolving-the-0x80070422-error-on-windows-10-devices/"><u>Troubleshooting Guide for Resolving the 0X80070422 Error on Windows 10 Devices</u></a></li>
<li><a href="https://techidaily.com/troubleshooting-user-authentication-errors-successfully-logging-into-windows-10-systems/"><u>Troubleshooting User Authentication Errors: Successfully Logging Into Windows 10 Systems</u></a></li>
<li><a href="https://techidaily.com/unlock-the-secrets-to-accessing-blocked-torrent-sites-legally/"><u>Unlock the Secrets to Accessing Blocked Torrent Sites Legally</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

