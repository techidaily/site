---
title: "Google Chrome Version 127: Enhanced Security Against Web-Based Threats"
date: 2024-09-16T22:56:29.544Z
updated: 2024-09-24T06:24:10.371Z
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
<li><a href="https://video-capture.techidaily.com/new-chorus-cache-secure-and-inspect-audio-recordings-for-2024/"><u>[New] Chorus Cache Secure & Inspect Audio Recordings for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-harnessing-the-power-of-gratuitous-text-animations-for-2024/"><u>[Updated] Harnessing the Power of Gratuitous Text Animations for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-understanding-livestream-technology-explained/"><u>[Updated] In 2024, Understanding Livestream Technology Explained</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-visual-flow-control-simple-fade-strategies-for-2024/"><u>[Updated] Visual Flow Control Simple Fade Strategies for 2024</u></a></li>
<li><a href="https://techidaily.com/1-free-online-conversion-change-webm-files-into-high-quality-flac-audio-format/"><u>1. Free Online Conversion: Change WebM Files Into High-Quality FLAC Audio Format</u></a></li>
<li><a href="https://techidaily.com/4-efektivni-tridy-nahravani-webovyh-stranek-do-audiotekstu-podrobny-pruvodce-s-movavi/"><u>4 Efektivní Třídy Nahrávání Webovyh Stránek Do Audiotekstu: Podrobný Průvodce S Movavi</u></a></li>
<li><a href="https://techidaily.com/1726233783102-productsrecorderproductname/"><u>获取{{ product('srecorder').product_name}}的免费访问金钥匙序列号</u></a></li>
<li><a href="https://techidaily.com/1726233776228-flv-movavi/"><u>簡便無需下載的線上 FLV格式自由切換器 - Movavi</u></a></li>
<li><a href="https://techidaily.com/1726233776256-3gpwma-movavi/"><u>線上即時 3GP至WMA無成本導航 - Movavi 轉換器解決方案</u></a></li>
<li><a href="https://techidaily.com/best-video-smoothing-applications-of-202-the-year-with-pay-free-choices-available/"><u>Best Video Smoothing Applications of 202 the Year, With Pay-Free Choices Available</u></a></li>
<li><a href="https://techidaily.com/cambia-file-aac-a-mp3-online-gratuitamente-con-movavi/"><u>Cambia File AAC a MP3 Online Gratuitamente Con Movavi</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-outriders-freezing-and-stuttering-on-pc/"><u>How to Fix Outriders Freezing & Stuttering on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-zte-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from ZTE .</u></a></li>
<li><a href="https://extra-information.techidaily.com/igniting-laughter-a-path-to-meme-fame/"><u>Igniting Laughter A Path to Meme Fame</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-metaverse-meets-omniverse-a-comparative-guide/"><u>In 2024, Metaverse Meets Omniverse A Comparative Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-mac-visual-seize-methods-reviewed-limit-156-chars/"><u>Top Mac Visual Seize Methods Reviewed (Limit 156 Chars)</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1726233744406-png-pgm-movavi/"><u>웹 안에서 비용 없이 PNG을 PGM로 전환하는 방법 - Movavi</u></a></li>
<li><a href="https://techidaily.com/1726233804388-caf/"><u>オンラインで簡単! CAF形式の画像を変換するための特別便利な無料ツール</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

