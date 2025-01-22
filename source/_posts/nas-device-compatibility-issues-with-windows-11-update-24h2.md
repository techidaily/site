---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2025-01-20T00:22:01.285Z
updated: 2025-01-21T23:39:37.024Z
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-cutting-edge-ad-strategies-for-peak-performance-on-facebook/"><u>[New] In 2024, Cutting-Edge Ad Strategies for Peak Performance on Facebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-pawsome-playtime-12-android-titles-to-try-now/"><u>[New] In 2024, Pawsome Playtime 12 Android Titles to Try Now</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-top-8-youtuber-blunders-to-avoid-and-why-theyre-common/"><u>[Updated] In 2024, Top 8 Youtuber Blunders to Avoid and Why They're Common</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ective-tricks-for-youtube-subscriber-surges/"><u>5 Effective Tricks for YouTube Subscriber Surges</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/all-in-one-iphone-support-comprehensive-solutions-to-your-ios-issues/"><u>All-in-One iPhone Support: Comprehensive Solutions to Your iOS Issues</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-note-12-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi Note 12 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/factory-reset-apple-iphone-13-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-asus-rog-phone-7-ultimate-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Asus ROG Phone 7 Ultimate in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-realme-c67-4g-by-fonelab-android-recover-photos/"><u>Undelete lost photos from Realme C67 4G.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-discover-the-top-mts-video-editing-tools-for-2024/"><u>Updated Discover the Top MTS Video Editing Tools for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

