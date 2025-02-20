---
title: "Step-by-Step Guide: Clearing Your DNS Cache in Windows 11"
date: 2025-02-14T18:54:26.425Z
updated: 2025-02-19T20:48:44.895Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d046e3f1a50f3eab0c2328a8c65f9cdfeb961e04c1487439cf5694d3a9ccaf02.jpg
---

## Step-by-Step Guide: Clearing Your DNS Cache in Windows 11

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Does the DNS Cache Do?](https://screen-video-capture.techidaily.com/new-2024-approved-simplified-game-recording-setups-for-stardew-villagers/)
* [Flushing Your DNS Cache](https://facebook-video-share.techidaily.com/updated-swipe-right-on-creativity-youtubes-top-techniques-for-greenscreens/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* The DNS cache stores information that translates domain names into IP addresses, saving time when you connect to websites.
* Flushing your PC's DNS cache can help fix internet connection issues caused by corrupted, outdated, or poisoned cache.
* To flush your DNS Cache, run "ipconfig /flushdns" in Command Prompt or PowerShell, or just restart your PC.

 A problem with your PC's DNS cache can result in trouble connecting to the internet. If you've tried the usual tricks [like clearing your browser cache and cookies](https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-huawei-nova-y71-drfone-by-drfone-fix-android-problems-fix-android-problems/), flushing Windows 10's DNS may fix your problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Does the DNS Cache Do? 

 A [Domain Network System (DNS) server](https://instagram-clips.techidaily.com/new-2024-approved-revealing-the-top-10-hidden-story-supporters/) is what translates familiar domain names like howtogeek.com into the IP addresses computers use to connect with each other. When a program tries to connect to a domain name like google.com or facebook.com, your computer queries a DNS server on the internet to get the corresponding numerical IP address. To save time, Windows 10 stores a copy of the information it gets from DNS servers locally on your PC. This is called the DNS cache.

 Your PC's DNS cache can save time, but if something goes wrong with it, it can cause connection errors. The DNS cache can become corrupted, where the information relating IP addresses to domain names is lost due to a glitch. The cache can also become outdated, meaning that either the domain name or the IP address of the site you're trying to reach has changed since the cache was last updated. The DNS cache can also be poisoned, where it is [given incorrect information by DNS servers](https://vimeo-videos.techidaily.com/new-in-2024-premium-downloader-suite-for-vimeo-content/). DNS cache poisoning can be accidental, but it can also be used maliciously to steal login credentials or other sensitive data.

 The DNS cache affects all internet traffic on your PC, so if you're having trouble with only one program or a single website, the problem probably isn't your DNS cache. If you can't reach a specific website, you can use a tool like [IsItDownRightNow](https://www.isitdownrightnow.com/) to check the website's status. If a single application isn't able to connect to the internet, try [checking your firewall settings](https://screen-mirror.techidaily.com/in-2024-how-to-cast-apple-iphone-7-to-chromecast-drfone-by-drfone-ios/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Flushing Your DNS Cache

 The DNS cache is not stored as a file on your PC, it is stored in system memory. System memory gets cleared every time your computer powers off, which is part of the reason [why restarting your computer fixes so many problems](https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-motorola-moto-g13-drfone-by-drfone-virtual-android/). It also means the simplest way to flush your DNS cache is to restart your PC.

 If you want to manually flush your DNS cache on Windows 10, you can use Command Prompt or Windows PowerShell. Some commands must be "[Run as administrator](https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual/)," but it doesn't matter in this case.

 To launch Command Prompt, click the start button, type "cmd" or "command prompt" into the search bar on the Start menu, and then hit Enter.

![Running Command Prompt from the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can use Windows PowerShell. Click the Start button, type "powershell" into the search bar in the Start menu, and hit Enter.

![Enter "PowerShell" in the Start Menu search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/run-powershell.png) 

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
<li><a href="https://extra-information.techidaily.com/updated-boost-call-quality-and-creativity-learn-to-apply-filters-in-zoom/"><u>[Updated] Boost Call Quality & Creativity Learn to Apply Filters in Zoom</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-tailoring-your-whatsapp-ringtone-for-ios-and-android-devices/"><u>[Updated] Tailoring Your WhatsApp Ringtone for iOS and Android Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-your-guide-to-stellar-igtv-talent/"><u>2024 Approved Your Guide to Stellar IGTV Talent</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-10t-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme 10T 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-s23plus-by-fonelab-android-recover-contacts/"><u>How To Restore Missing Contacts Files from S23+.</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-samsung-galaxy-m34-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Samsung Galaxy M34 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-a1-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo A1 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-art-of-pdf-reading-a-comprehensive-guide-for-your-amazon-kindle/"><u>Mastering the Art of PDF Reading: A Comprehensive Guide for Your Amazon Kindle</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/masterpiece-tools-filmoras-loved-9-edits-unraveled-for-2024/"><u>Masterpiece Tools Filmora's Loved 9 Edits Unraveled for 2024</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-xiaomi-14-pro-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win-news.techidaily.com/troubleshooting-steps-for-repairing-your-faulty-printer-drivers-expert-tips-from-yl-computings-tech-specialists/"><u>Troubleshooting Steps for Repairing Your Faulty Printer Drivers - Expert Tips From YL Computing's Tech Specialists</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-or-malfunctioning-your-hardware-drivers-with-windows-device-manager-on-windows-1110-by-drivereasy-guide/"><u>Use Device Manager to identify missing or malfunctioning your hardware drivers with Windows Device Manager on Windows 11/10</u></a></li>
<li><a href="https://techidaily.com/vivo-x100-pro-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Vivo X100 Pro Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
</ul></div>

