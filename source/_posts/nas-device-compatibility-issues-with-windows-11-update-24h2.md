---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-12-11T01:48:13.900Z
updated: 2024-12-16T02:13:03.272Z
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-perfecting-online-presence-key-to-knowing-and-using-fb-video-ratios/"><u>[New] 2024 Approved Perfecting Online Presence Key to Knowing and Using FB Video Ratios</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-embracing-constructive-feedback-ignoring-the-rest/"><u>[Updated] 2024 Approved Embracing Constructive Feedback, Ignoring the Rest</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-mastering-online-team-interactions/"><u>[Updated] 2024 Approved Mastering Online Team Interactions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-video-voyaging-navigating-twittersphere-and-tumbleverse/"><u>2024 Approved Video Voyaging Navigating Twittersphere & Tumbleverse</u></a></li>
<li><a href="https://fox-that.techidaily.com/address-iphones-vanishing-act-with-contacts-expert-solutions-to-make-them-visible-again/"><u>Address iPhone's Vanishing Act with Contacts: Expert Solutions to Make Them Visible Again</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cutting-edge-systems-for-effective-language-study/"><u>Cutting-Edge Systems for Effective Language Study</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y100t-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y100t without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-htc-u23-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on HTC U23? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-uncovering-budget-friendly-video-conferencing-tools-for-all-systems/"><u>In 2024, Uncovering Budget-Friendly Video Conferencing Tools for All Systems</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-y100t-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Y100t</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-infinix-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Infinix</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-samsung-galaxy-m14-5g-by-fonelab-android-recover-music/"><u>Undelete lost music from Samsung Galaxy M14 5G</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-15-plus-using-icloud-website-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 15 Plus using icloud website</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

