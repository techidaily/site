---
title: "Step-by-Step Guide: Clearing Your DNS Cache in Windows 11"
date: 2024-12-18T16:50:48.175Z
updated: 2024-12-24T23:35:38.228Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d046e3f1a50f3eab0c2328a8c65f9cdfeb961e04c1487439cf5694d3a9ccaf02.jpg
---

## Step-by-Step Guide: Clearing Your DNS Cache in Windows 11

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Does the DNS Cache Do?](https://screen-video-capture.techidaily.com/new-2024-approved-simplified-game-recording-setups-for-stardew-villagers/)
* [Flushing Your DNS Cache](https://facebook-video-share.techidaily.com/updated-swipe-right-on-creativity-youtubes-top-techniques-for-greenscreens/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* The DNS cache stores information that translates domain names into IP addresses, saving time when you connect to websites.
* Flushing your PC's DNS cache can help fix internet connection issues caused by corrupted, outdated, or poisoned cache.
* To flush your DNS Cache, run "ipconfig /flushdns" in Command Prompt or PowerShell, or just restart your PC.

 A problem with your PC's DNS cache can result in trouble connecting to the internet. If you've tried the usual tricks [like clearing your browser cache and cookies](https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-huawei-nova-y71-drfone-by-drfone-fix-android-problems-fix-android-problems/), flushing Windows 10's DNS may fix your problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Does the DNS Cache Do? 

 A [Domain Network System (DNS) server](https://instagram-clips.techidaily.com/new-2024-approved-revealing-the-top-10-hidden-story-supporters/) is what translates familiar domain names like howtogeek.com into the IP addresses computers use to connect with each other. When a program tries to connect to a domain name like google.com or facebook.com, your computer queries a DNS server on the internet to get the corresponding numerical IP address. To save time, Windows 10 stores a copy of the information it gets from DNS servers locally on your PC. This is called the DNS cache.

 Your PC's DNS cache can save time, but if something goes wrong with it, it can cause connection errors. The DNS cache can become corrupted, where the information relating IP addresses to domain names is lost due to a glitch. The cache can also become outdated, meaning that either the domain name or the IP address of the site you're trying to reach has changed since the cache was last updated. The DNS cache can also be poisoned, where it is [given incorrect information by DNS servers](https://vimeo-videos.techidaily.com/new-in-2024-premium-downloader-suite-for-vimeo-content/). DNS cache poisoning can be accidental, but it can also be used maliciously to steal login credentials or other sensitive data.

 The DNS cache affects all internet traffic on your PC, so if you're having trouble with only one program or a single website, the problem probably isn't your DNS cache. If you can't reach a specific website, you can use a tool like [IsItDownRightNow](https://www.isitdownrightnow.com/) to check the website's status. If a single application isn't able to connect to the internet, try [checking your firewall settings](https://screen-mirror.techidaily.com/in-2024-how-to-cast-apple-iphone-7-to-chromecast-drfone-by-drfone-ios/).

##  Flushing Your DNS Cache

 The DNS cache is not stored as a file on your PC, it is stored in system memory. System memory gets cleared every time your computer powers off, which is part of the reason [why restarting your computer fixes so many problems](https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-motorola-moto-g13-drfone-by-drfone-virtual-android/). It also means the simplest way to flush your DNS cache is to restart your PC.

 If you want to manually flush your DNS cache on Windows 10, you can use Command Prompt or Windows PowerShell. Some commands must be "[Run as administrator](https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual/)," but it doesn't matter in this case.

 To launch Command Prompt, click the start button, type "cmd" or "command prompt" into the search bar on the Start menu, and then hit Enter.

![Running Command Prompt from the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can use Windows PowerShell. Click the Start button, type "powershell" into the search bar in the Start menu, and hit Enter.

![Enter "PowerShell" in the Start Menu search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-powershell.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With either Command Prompt or Windows PowerShell opened, enter the following command:

        `ipconfig /flushdns`
    
 If the DNS cache was flushed, you should see the "Successfully flushed the DNS Resolver Cache" message. You can now close the window.

 If you're using PowerShell 5 (which is still default on Windows 10) your Window will be blue instead of black. 

![The DNS Cache has been flushed successfully in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/flush-dns-powershell.png) 

 You can now test the websites or application you were having problems with. Is it working? If you're still experiencing problems, you'll have to try [other internet connection troubleshooting steps](https://article-posts.techidaily.com/pioneering-medical-messaging-in-digital-advertising/).

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-10-best-webcam-recorders-windows-11-for-2024/"><u>[New] 10 Best Webcam Recorders Windows 11 for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-securing-memories-a-comprehensive-guide-for-scanning-and-storing-vintage-photos/"><u>[New] In 2024, Securing Memories A Comprehensive Guide for Scanning and Storing Vintage Photos</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-breaking-barriers-7-top-tools-for-artists-transforming-into-nfts/"><u>2024 Approved Breaking Barriers 7 Top Tools for Artists Transforming Into NFTs</u></a></li>
<li><a href="https://techtrends.techidaily.com/boost-your-productivity-5-simple-tips-for-enhancing-facebook-usage/"><u>Boost Your Productivity: 5 Simple Tips for Enhancing Facebook Usage</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-dell-router-driver-files-free-now/"><u>Get the Newest Dell Router Driver Files Free Now</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-motorola-edge-40-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Motorola Edge 40 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xr-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XR To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-x-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone X to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-7-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 7 without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-craft-a-compelling-narrative-with-your-igtv-video-titles-and-texts/"><u>In 2024, Craft a Compelling Narrative with Your IGTV Video Titles & Texts</u></a></li>
<li><a href="https://techidaily.com/is-your-nubia-red-magic-8s-proplus-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Nubia Red Magic 8S Pro+ working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/precision-zoom-mastery-in-microsoft-teams-sessions/"><u>Precision Zoom Mastery in Microsoft Teams Sessions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-p60-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on P60 ?</u></a></li>
</ul></div>

