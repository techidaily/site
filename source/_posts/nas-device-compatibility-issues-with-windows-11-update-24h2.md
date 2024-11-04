---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-10-29T10:52:11.548Z
updated: 2024-11-04T02:03:25.456Z
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
<li><a href="https://some-skills.techidaily.com/updated-the-language-of-cinema-writing-as-an-art/"><u>[Updated] The Language of Cinema Writing as an Art</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-disk-distinctions-c-and-d/"><u>A Guide to Understanding Disk Distinctions (C & D)</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-samsung-galaxy-m14-5g-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/elite-15-high-definition-action-recorders/"><u>Elite 15 High-Definition Action Recorders</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-oculus-headset-up-and-running-latest-windows-11-10-8-and-7-drivers-download/"><u>Get Your Oculus Headset Up and Running: [Latest] Windows 11, 10, 8 & 7 Drivers Download</u></a></li>
<li><a href="https://techidaily.com/hard-reset-lava-blaze-2-pro-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Lava Blaze 2 Pro in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-m54-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy M54 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-note-30-pro-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Infinix Note 30 Pro Phone without Any Data Loss</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-poco-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Poco</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-13-pro-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 13 Pro files after scanning? | Stellar</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

