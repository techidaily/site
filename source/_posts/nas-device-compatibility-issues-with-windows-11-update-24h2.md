---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-12-17T18:52:55.632Z
updated: 2024-12-24T20:20:54.084Z
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
<li><a href="https://fox-info.techidaily.com/updated-in-2024-mirthful-mayhem-makers/"><u>[Updated] In 2024, Mirthful Mayhem Makers</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-itel-p55t-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Itel P55T | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722969855312-download-and-update-drivers-for-hp-deskjet-3700-enhance-printing-quality-now/"><u>Download and Update Drivers for HP DeskJet 3700 - Enhance Printing Quality Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ecoflow-river-vee-a-top-pick-for-budget-friendly-high-performance-portable-power-solutions-reviewed-by-tech-expert/"><u>EcoFlow River Vee: A Top Pick for Budget-Friendly, High-Performance Portable Power Solutions Reviewed by Tech Expert</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhancing-social-media-impact-with-high-quality-360-facebook-content-for-2024/"><u>Enhancing Social Media Impact with High-Quality 360 Facebook Content for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a18-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A18 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-se-2020-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone SE (2020) Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-12-pro-max-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 12 Pro Max Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/investigating-economical-recording-a-look-into-vixias-hf-r800/"><u>Investigating Economical Recording: A Look Into VIXIA's HF R800</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/samsung-smart-tv-app-malfunction-diagnosis-and-solutions/"><u>Samsung Smart TV App Malfunction: Diagnosis and Solutions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-10-news-aggregator-apps-to-follow-in-2eby/"><u>Top 10 News Aggregator Apps to Follow in 2Eby</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-drivers-with-windows-device-manager-on-windows-11-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning drivers with Windows Device Manager on Windows 11</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-s23-ultra-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

