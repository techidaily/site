---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2025-01-11T17:18:35.315Z
updated: 2025-01-15T17:26:02.405Z
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
<li><a href="https://vimeo-videos.techidaily.com/new-expertly-merge-vimeo-footage-with-ppts-using-modern-tools/"><u>[New] Expertly Merge Vimeo Footage with PPTs Using Modern Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-tips-and-tricks-for-gopro-get-the-most-from-your-gopro/"><u>[Updated] Tips and Tricks for GoPro Get the Most From Your GoPro</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-itel-a05s-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Itel A05s | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-tecno-pova-6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-pro-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 Pro to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-14-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 14 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-14-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 14 Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/learn-to-download-discord-videos-without-cost-on-all-devices/"><u>Learn to Download Discord Videos Without Cost on All Devices</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210966356-9781088233481-leila-la-hija-de-charles-la-verdadera-historia-de-yvonne-a-pereira/"><u>Leila, la hija de Charles. La verdadera historia de Yvonne A. Pereira | Free Book</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-stutter-and-lag-issues-in-the-world-of-avatar-pandora-edition/"><u>Troubleshooting Stutter and Lag Issues in the World of Avatar: Pandora Edition</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

