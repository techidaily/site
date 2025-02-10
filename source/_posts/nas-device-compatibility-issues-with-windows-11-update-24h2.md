---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2025-02-06T17:49:28.060Z
updated: 2025-02-09T17:01:36.105Z
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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-high-resolution-blu-ray-delight-top-3d-player-selections/"><u>[New] In 2024, High-Resolution Blu-Ray Delight Top 3D Player Selections</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-add-cinematic-shake-to-images-using-ps-for-2024/"><u>[Updated] Add Cinematic Shake to Images Using PS for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-crafting-gentle-volume-declines-using-logic-pro/"><u>[Updated] In 2024, Crafting Gentle Volume Declines Using Logic Pro</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/critical-security-notice-for-iphone-owners-apple-warns-of-advanced-spyware-threats-by-rogue-agents-is-it-time-to-get-concerned/"><u>Critical Security Notice for iPhone Owners: Apple Warns of Advanced Spyware Threats by Rogue Agents – Is It Time to Get Concerned?</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-lenovo-thinkphone-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Lenovo ThinkPhone Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/end-dark-mode-woes-in-win11-after-fall-upgrade/"><u>End Dark Mode Woes in Win11 After Fall Upgrade</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/step-into-the-world-of-bug-hunting-get-a-payday-at-openai/"><u>Step Into the World of Bug Hunting; Get a Payday at OpenAI!</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-realme-c67-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-asus-rog-phone-8-pro-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Asus ROG Phone 8 Pro password or pattern lock</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-realme-gt-5-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Realme GT 5 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

