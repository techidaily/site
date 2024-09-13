---
title: "Google Chrome Version 127: Enhanced Security Against Web-Based Threats"
date: 2024-09-12T01:06:35.971Z
updated: 2024-09-13T01:06:35.971Z
tags:
  - web
categories:
  - tech
thumbnail: https://thmb.techidaily.com/26e5a5bed3537105229e89d2df536f43cfadace1d3a287d0f50c6226ff3d146f.png
---

## Google Chrome Version 127: Enhanced Security Against Web-Based Threats

In an effort to fight infostealer malware, the recent Chrome 127 update now utilizes App-Bound Encryption on Windows. This should prevent infostealer malware from accessing critical user data, specifically browser cookies and saved passwords.

 Private data in Chrome is already encrypted. That said, security methods vary by operating system. Chrome uses Apple's Keychain services on macOS, for example, and it taps into system-provided wallets on Linux. These cybersecurity systems successfully protect most macOS and Linux users from [infostealer malware](https://www.anrdoezrs.net/links/3607085/type/dlg/sid/UUhtgUeUpU2004582/https://www.malwarebytes.com/blog/threats/info-stealers), but Windows' system, called the [Data Protection API](https://en.wikipedia.org/wiki/Data%5FProtection%5FAPI) (DPAPI), is comparatively vulnerable. It doesn't prevent malicious applications from executing code at the user level, and as a result, any infostealer malware that manages to dodge Windows Defender may interact with encrypted app data.

 Infostealer malware tends to be quite sophisticated. The hackers that distribute such malware are clever, too. We recently reported on an infostealer malware that was [slipped into Google Search ads](https://blog-min.techidaily.com/how-to-fix-iphone-12-pro-stuck-at-attempting-data-recovery-loop-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/). Humans are easy to fool and operating systems are flawed, so instead of waiting for Microsoft to improve DPAPI, Google is adding App-Bound Encryption on top of the existing security system.

> "In Chrome 127 we are introducing a new protection on Windows that improves on the DPAPI by providing Application-Bound (App-Bound) Encryption primitives. Rather than allowing any app running as the logged in user to access this data, Chrome can now encrypt data tied to app identity, similar to how the Keychain operates on macOS."

 Data protected by App-Bound Encryption can only be accessed by an app with the correct decryption key. So, cookies and passwords that are saved by Chrome 127 on Windows can only be accessed by the Chrome browser. This data cannot be accessed by malware or any other software (be it malicious or benign).

 Yes, there are circumstances in which App-Bound Encryption may be bypassed. Malware could circumvent this encryption method by elevating itself to system privileges or injecting code into Chrome, for example. But, as Google explains, these actions are almost guaranteed to trigger a response from Windows Defender. Chrome's App-Bound Encryption method, while not bulletproof, is a massive improvement over standard DPAPI behavior. It's a protection that should be offered by more Windows apps, especially as infostealer malware grows more common.

 These security improvements are available in [Chrome 127](https://chromereleases.googleblog.com/) on Windows. The Chrome 127 update rolled out in late July, so it should already be installed on your system. You can [check your Chrome version](https://techtrends.techidaily.com/step-by-step-restoring-functionality-to-a-broken-macbook-pro-keyboard/) from the browser's "About Google Chrome" submenu.

 Source: [Google](https://security.googleblog.com/2024/07/improving-security-of-chrome-cookies-on.html)

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
<li><a href="https://video-screen-grab.techidaily.com/new-proven-strategies-for-flawless-xbox-video-capture/"><u>[New] Proven Strategies for Flawless Xbox Video Capture</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-simplify-live-streaming-and-archiving-with-vlc-webcam-integration/"><u>[New] Simplify Live Streaming and Archiving with VLC Webcam Integration</u></a></li>
<li><a href="https://techidaily.com/1-monitoring-pc-heat-a-guide-to-measuring-cpu-temperatures-in-windows-11/"><u>1. Monitoring PC Heat: A Guide to Measuring CPU Temperatures in Windows 11</u></a></li>
<li><a href="https://techidaily.com/1-solve-your-altplustab-navigation-issues-in-windows-with-these-easy-fixes/"><u>1. Solve Your Alt+Tab Navigation Issues in Windows with These Easy Fixes!</u></a></li>
<li><a href="https://techidaily.com/boost-your-pcs-performance-by-locating-and-disabling-covert-programs-that-overload-your-windows-boot-sequence/"><u>Boost Your PC's Performance by Locating & Disabling Covert Programs that Overload Your Windows Boot Sequence</u></a></li>
<li><a href="https://fix-guide.techidaily.com/boosting-your-network-an-expert-review-of-the-ac1200-wireless-repeater-by-netgear-ex6200-series/"><u>Boosting Your Network: An Expert Review of the AC1200 Wireless Repeater by Netgear (EX6200 Series)</u></a></li>
<li><a href="https://techidaily.com/can-pending-downloads-proceed-once-you-exit-windows-sleep-state/"><u>Can Pending Downloads Proceed Once You Exit Windows' Sleep State?</u></a></li>
<li><a href="https://techidaily.com/comparing-windows-10-editions-home-vs-pro-key-features-and-differences-explained/"><u>Comparing Windows 10 Editions: Home Vs. Pro – Key Features and Differences Explained</u></a></li>
<li><a href="https://techidaily.com/comprehensive-test-drive-of-the-plugable-dock-with-two-hdmi-ports-over-usb-c-a-game-changer-for-windows-users/"><u>Comprehensive Test Drive of the Plugable Dock with Two HDMI Ports over USB-C – A Game Changer for Windows Users?</u></a></li>
<li><a href="https://techidaily.com/concealing-the-desktop-edge-a-guide-to-disabling-windows-11s-taskbar/"><u>Concealing the Desktop Edge: A Guide to Disabling Windows 11'S Taskbar</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/guia-simplificado-de-gravacao-de-conteudo-do-dvd-diretamente-no-pendrive-utilizando-o-windows-ou-macos/"><u>Guia Simplificado De Gravação De Conteúdo Do DVD Diretamente No Pendrive Utilizando O Windows Ou macOS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-tecno-phantom-v-fold-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Tecno Phantom V Fold? Fixed | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/mastering-melodies-with-magix-music-maker-software/"><u>Mastering Melodies with Magix Music Maker Software</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-tally-unveiling-the-highest-rated-threads-on-reddit/"><u>The Ultimate Tally Unveiling the Highest-Rated Threads on Reddit</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

