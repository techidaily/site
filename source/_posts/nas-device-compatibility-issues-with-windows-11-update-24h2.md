---
title: NAS Device Compatibility Issues with Windows 11 Update 24H2
date: 2024-11-22T22:16:45.644Z
updated: 2024-11-24T03:29:32.817Z
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
<li><a href="https://youtube-sure.techidaily.com/uided-approach-to-saving-exact-youtube-segments/"><u>[New] Guided Approach to Saving Exact YouTube Segments</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-m1-deciphered-apples-computing-game-changer/"><u>[New] M1 Deciphered Apple's Computing Game-Changer</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-vr-comfort-mastery-top-10-strategies/"><u>[Updated] 2024 Approved VR Comfort Mastery Top 10 Strategies</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-discover-the-power-of-video-filters-in-your-zoom-sessions/"><u>[Updated] Discover the Power of Video Filters in Your Zoom Sessions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-a-step-by-step-journey-through-vo-and-powerpoint-magic/"><u>[Updated] In 2024, A Step-by-Step Journey Through VO and Powerpoint Magic</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-for-the-ordinary-person-claude-versus-gpt-analysis/"><u>AI for the Ordinary Person: Claude Versus GPT Analysis</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-nokia-c300-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Nokia C300 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-13-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Apple iPhone 13 Pro Max Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-realme-c33-2023-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Realme C33 2023 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-realme-gt-5-240w-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Realme GT 5 (240W) phone? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-ultimate-playbook-for-fine-tuning-video-soundtracks-including-tips-for-modern-platforms/"><u>New The Ultimate Playbook for Fine-Tuning Video Soundtracks Including Tips for Modern Platforms</u></a></li>
<li><a href="https://techidaily.com/repair-broken-or-corrupt-video-files-of-nubia-red-magic-8s-proplus-by-stellar-video-repair-mobile-video-repair/"><u>Repair broken or corrupt video files of Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-on-repairing-a-failed-remote-server-link/"><u>Step-by-Step Tutorial on Repairing a Failed Remote Server Link</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-tecno-spark-go-2024-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Tecno Spark Go (2024)</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-tecno-phantom-v-fold-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Tecno Phantom V Fold? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

