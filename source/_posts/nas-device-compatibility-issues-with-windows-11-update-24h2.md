---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-10-07T21:31:00.588Z
updated: 2024-10-11T19:12:12.100Z
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
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-elevate-your-virtual-meetings-mastering-zoom-filter-tech/"><u>[Updated] 2024 Approved Elevate Your Virtual Meetings Mastering Zoom Filter Tech</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-civ-5-problems-on-a-pc/"><u>Addressing Civ 5 Problems on a PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cutting-edge-subtitling-solutions-the-ultimate-top-10-list-online/"><u>Cutting-Edge Subtitling Solutions The Ultimate Top 10 List (Online)</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-samsung-galaxy-s21-fe-5g-2023-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Samsung Galaxy S21 FE 5G (2023) Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-xfffeeee-error-on-your-office-printer/"><u>Eliminating XFFFEEEE Error on Your Office Printer</u></a></li>
<li><a href="https://driver-download.techidaily.com/free-download-latest-nvidia-geforce-gt-710-graphics-card-driver-for-windows/"><u>Free Download: Latest NVIDIA GeForce GT #710 Graphics Card Driver for Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-itel-p40plus-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/macos-15-sequoia-detailed-overview-of-release-plans-enhancements-and-rumors/"><u>MacOS 15 (Sequoia) – Detailed Overview of Release Plans, Enhancements, and Rumors</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a15-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Samsung Galaxy A15 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a25-5g-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Samsung Galaxy A25 5G Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-realme-gt-5-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Realme GT 5 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-apple-iphone-xs-max-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone XS Max Without iTunes in 5 Ways</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

