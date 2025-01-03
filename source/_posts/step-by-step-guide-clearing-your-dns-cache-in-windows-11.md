---
title: "Step-by-Step Guide: Clearing Your DNS Cache in Windows 11"
date: 2024-12-26T17:26:41.864Z
updated: 2025-01-02T18:30:56.739Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d046e3f1a50f3eab0c2328a8c65f9cdfeb961e04c1487439cf5694d3a9ccaf02.jpg
---

## Step-by-Step Guide: Clearing Your DNS Cache in Windows 11

### Quick Links

* [What Does the DNS Cache Do?](https://screen-video-capture.techidaily.com/new-2024-approved-simplified-game-recording-setups-for-stardew-villagers/)
* [Flushing Your DNS Cache](https://facebook-video-share.techidaily.com/updated-swipe-right-on-creativity-youtubes-top-techniques-for-greenscreens/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* The DNS cache stores information that translates domain names into IP addresses, saving time when you connect to websites.
* Flushing your PC's DNS cache can help fix internet connection issues caused by corrupted, outdated, or poisoned cache.
* To flush your DNS Cache, run "ipconfig /flushdns" in Command Prompt or PowerShell, or just restart your PC.

 A problem with your PC's DNS cache can result in trouble connecting to the internet. If you've tried the usual tricks [like clearing your browser cache and cookies](https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-huawei-nova-y71-drfone-by-drfone-fix-android-problems-fix-android-problems/), flushing Windows 10's DNS may fix your problem.

##  What Does the DNS Cache Do? 

 A [Domain Network System (DNS) server](https://instagram-clips.techidaily.com/new-2024-approved-revealing-the-top-10-hidden-story-supporters/) is what translates familiar domain names like howtogeek.com into the IP addresses computers use to connect with each other. When a program tries to connect to a domain name like google.com or facebook.com, your computer queries a DNS server on the internet to get the corresponding numerical IP address. To save time, Windows 10 stores a copy of the information it gets from DNS servers locally on your PC. This is called the DNS cache.

 Your PC's DNS cache can save time, but if something goes wrong with it, it can cause connection errors. The DNS cache can become corrupted, where the information relating IP addresses to domain names is lost due to a glitch. The cache can also become outdated, meaning that either the domain name or the IP address of the site you're trying to reach has changed since the cache was last updated. The DNS cache can also be poisoned, where it is [given incorrect information by DNS servers](https://vimeo-videos.techidaily.com/new-in-2024-premium-downloader-suite-for-vimeo-content/). DNS cache poisoning can be accidental, but it can also be used maliciously to steal login credentials or other sensitive data.

 The DNS cache affects all internet traffic on your PC, so if you're having trouble with only one program or a single website, the problem probably isn't your DNS cache. If you can't reach a specific website, you can use a tool like [IsItDownRightNow](https://www.isitdownrightnow.com/) to check the website's status. If a single application isn't able to connect to the internet, try [checking your firewall settings](https://screen-mirror.techidaily.com/in-2024-how-to-cast-apple-iphone-7-to-chromecast-drfone-by-drfone-ios/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Flushing Your DNS Cache

 The DNS cache is not stored as a file on your PC, it is stored in system memory. System memory gets cleared every time your computer powers off, which is part of the reason [why restarting your computer fixes so many problems](https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-motorola-moto-g13-drfone-by-drfone-virtual-android/). It also means the simplest way to flush your DNS cache is to restart your PC.

 If you want to manually flush your DNS cache on Windows 10, you can use Command Prompt or Windows PowerShell. Some commands must be "[Run as administrator](https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual/)," but it doesn't matter in this case.

 To launch Command Prompt, click the start button, type "cmd" or "command prompt" into the search bar on the Start menu, and then hit Enter.

![Running Command Prompt from the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can use Windows PowerShell. Click the Start button, type "powershell" into the search bar in the Start menu, and hit Enter.

![Enter "PowerShell" in the Start Menu search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-powershell.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With either Command Prompt or Windows PowerShell opened, enter the following command:

        `ipconfig /flushdns`
    
 If the DNS cache was flushed, you should see the "Successfully flushed the DNS Resolver Cache" message. You can now close the window.

 If you're using PowerShell 5 (which is still default on Windows 10) your Window will be blue instead of black. 

![The DNS Cache has been flushed successfully in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/flush-dns-powershell.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-becoming-a-voice-alteration-virtuoso-with-morphvox/"><u>[New] In 2024, Becoming a Voice Alteration Virtuoso with MorphVOX</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-linux-screenshot-solutions-the-ultimate-guide/"><u>[New] In 2024, Linux Screenshot Solutions The Ultimate Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-from-simple-scenes-advanced-techniques-for-snapchat-edits/"><u>[Updated] 2024 Approved From Simple Scenes Advanced Techniques for Snapchat Edits</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-expert-picks-top-5-high-performing-android-recorders/"><u>[Updated] In 2024, Expert Picks Top 5 High-Performing Android Recorders</u></a></li>
<li><a href="https://app-tips.techidaily.com/1-otter-team-edition-unveiled-revolutionize-remote-collaboration-with-adaptive-live-meeting-transcriptions-zdnet-insights/"><u>1. Otter Team Edition Unveiled: Revolutionize Remote Collaboration with Adaptive Live Meeting Transcriptions - ZDNet Insights</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722978117383-get-the-best-sound-on-your-pc-with-free-audigy-fx-driver-software/"><u>Get the Best Sound on Your PC with Free Audigy FX Driver Software</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-vivo-s18-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Vivo S18 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oneplus-open-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset OnePlus Open If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-honor-v-purse-without-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Honor V Purse Without Password?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-oppo-find-x7-ultra-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Oppo Find X7 Ultra?</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-storm-5g-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Storm 5G</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-motorola-edgeplus-2023-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/tips-and-tricks-for-streamlining-color-grading-with-luts-in-adobe-for-2024/"><u>Tips and Tricks for Streamlining Color Grading with LUTs in Adobe for 2024</u></a></li>
</ul></div>

