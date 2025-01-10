---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2025-01-08T21:14:32.997Z
updated: 2025-01-10T02:55:56.811Z
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
<li><a href="https://fox-direct.techidaily.com/new-expert-tips-iphones-secrets-to-perfect-movement-capture/"><u>[New] Expert Tips IPhone's Secrets to Perfect Movement Capture</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-stream-success-starts-here-choosing-the-right-camera-for-twitch/"><u>[Updated] 2024 Approved Stream Success Starts Here Choosing the Right Camera for Twitch</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-pixelpartition-review/"><u>2024 Approved PixelPartition Review</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-the-most-massive-lifting-machines-in-the-sky/"><u>2024 Approved The Most Massive Lifting Machines in the Sky</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-approach-to-batch-installations-on-windows-11-via-winstall/"><u>A Comprehensible Approach to Batch Installations on Windows 11 via Winstall</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-12-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi 12 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-pro-max-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 Pro Max To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-essential-guide-enabling-a-full-screen-grid-on-zoom/"><u>In 2024, Essential Guide Enabling a Full-Screen Grid on Zoom</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oneplus-ace-2v-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track OnePlus Ace 2V by Phone Number | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-reno-11-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo Reno 11 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-your-entertainment-choices-using-chatgpt/"><u>Streamline Your Entertainment Choices Using ChatGPT</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016513087-troubleshooting-why-isnt-my-mic-working-solutions-inside/"><u>Troubleshooting: Why Isn't My Mic Working? Solutions Inside</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-hot-40i-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Hot 40i on Mac?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

