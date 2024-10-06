---
title: "Protect Personal Information: Learn How to Encrypt USB Drives Using Windows 11 Features"
date: 2024-09-28T16:12:19.221Z
updated: 2024-10-05T20:39:12.037Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4a2496ce821a6c52eaf0cfecea597eea88a88766153a92e1f9e8401a4428c9fb.jpg
---

## Protect Personal Information: Learn How to Encrypt USB Drives Using Windows 11 Features

### Quick Links

* [What Is BitLocker (And Why Use It)?](https://www.howtogeek.com/encrypt-usb-flash-drive-windows/#what-is-bitlocker-and-why-use-it)
* [How to Encrypt a USB Flash Drive in Windows 10 or 11](https://fox-that.techidaily.com/iphone-glitched-into-headphones-try-these-8-troubleshooting-steps-to-restore-normal-functioning/)
* [How to Decrypt a USB Flash Drive in Windows 10 or 11](https://extra-resources.techidaily.com/the-ultimate-platform-showdown-podcast-vs-youtube/)
* [Third-Party Encryption Options](https://tech-hub.techidaily.com/how-to-harness-the-power-of-gpt-3-in-your-openai-experiments/)

### Key Takeaways

* Windows 10 and 11 Pro users can easily encrypt and decrypt flash drives using the built-in BitLocker feature, providing a convenient way to protect sensitive information.
* BitLocker uses powerful encryption technology (AES-128) that is virtually impossible to crack, ensuring the security of your data.
* While BitLocker is suitable for protecting sensitive information on portable computers, there are third-party encryption options available for Windows Home users.

 Flash drives are convenient, but they're also easy to lose and often contain sensitive information you don't want in the wrong hands. Luckily, Windows 10 and 11 Pro users can easily encrypt and decrypt flash drives with no additional software.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What Is BitLocker (And Why Use It)?

 BitLocker is a powerful encryption feature in Windows 10 and 11 Pro that protects the data on your drives so that no one can read their contents without the encryption key. The default level of encryption is AES-128, which would take millions or even billions of years to crack using current supercomputers.

 To use BitLocker, in addition to having the right version of Windows, your computer must be equipped with a TPM (Trusted Platform Module) of at least version 1.2\. If your computer doesn't have one, you'll need to [create a startup USB key](https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/). However, this is only relevant to internal system drives, and here we're discussing removable media. Likewise, encrypting the drive that contains Windows has special requirements regarding how the drive must be partitioned, but these requirements don't apply to secondary internal drives or removable, non-bootable drives.

 Full disk encryption isn't something everyone needs to do, but if your computer has sensitive information on it that could harm you if the drive were stolen, BitLocker is a good way to protect yourself. It's particularly useful for portable computers, since these have a much higher chance of being lost or stolen than a desktop system.

##  How to Encrypt a USB Flash Drive in Windows 10 or 11

 If you've decided that BitLocker is the right solution for your removable drive, here's how to set it up:

 1\. Plug in your USB drive.

 2\. Open File Explorer. You can use Windows+E to do this quickly.

 3\. Right-click on the flash drive in Explorer and select "Turn on BitLocker". In Windows 11, you'll have to click on "Show more details" first.

![A red arrow points to the 'Turn on bitlocker' option in the right-click context menu for a drive in Windows Explorer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4\. Wait for BitLocker to initialize the drive.

![Window showing the startup sequence for BitLocker Drive Encryption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2.jpg) 

 5\. Choose a password.

![BItLocker Window asking how the user wants to unlock the drive that's about to be encrypted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/3.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6\. Choose where and how to save your recovery key, which will let you decrypt the drive if you forget your password.

![BitLocker offering several recovery key back up options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/4.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7\. Choose whether to encrypt the whole drive or only used space. If the drive is empty and formatted, choose "Used Space"; otherwise, choose "Entire Drive."

![Bitlocker asking the user whether they want to encrypt the entire disk or only part of it](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/5.jpg) 

 8\. Choose the encryption type, which in almost all cases should be "Compatibility Mode." This ensures that older versions of Windows can read the drive. Since we're encrypting a portable drive, this is presumably something you want. However, if you're only going to use this drive with one computer, feel free to select the newer encryption option instead.

![Bitlocker offering either the new encryption mode or the older compatible mode](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/7.jpg) 

 9\. Click "Start Encrypting" and wait for the process to finish.

![The BitLocker Ready screen with a 'Start Encrypting' button.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/8.jpg) 

 If the process was successful, your drive is now protected by strong encryption and can only be accessed using its password.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Decrypt a USB Flash Drive in Windows 10 or 11

 So what if you don't want to have an encrypted flash drive anymore? One option is simply to format the drive, which will get rid of the encryption, but also all the data on the drive! If you don't need the data anymore, this is the fastest and easiest way to get the drive back to its factory condition.

 If you still need the data, you should simply copy it to another drive that's not encrypted before formatting the encrypted drive. This is just a fast workaround, however. The proper way to [decrypt the drive](https://desktop-recording.techidaily.com/androids-top-10-moba-gaming-spectacles/) and preserve all the data on it is as follows:

 Right-click on the drive in File Explorer and select "Manage BitLocker." On Windows 11, you'll have to click "Show more options" first.

![A right-click context menu showing the option to manage BitLocker](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/9.jpg) 

 In the BitLocker management Windows, choose "Turn off BitLocker" for the drive in question.

![A window showing the option to turn off Bitlocker](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/10.jpg) 

 Then simply confirm as you did when first encrypting the drive.

##  Third-Party Encryption Options

 As mentioned earlier, BitLocker isn't included in Home versions of Windows. That doesn't mean you have to be left in the lurch when it comes to keeping your data safe.

 If you're using a Home version of Windows, third-party apps like [VeraCrypt](https://www.veracrypt.fr/code/VeraCrypt/) (a free, open-source tool known for its robust security features) and [AxCrypt](https://axcrypt.net/) (a user-friendly app with a subscription model) are great alternatives.

 VeraCrypt is best for those who need high-level security without cost concerns, while AxCrypt offers a balance of ease of use and security for a modest fee.

---

 Securing your data, especially on portable media that's easily lost or stolen, is more important than ever. If you must carry sensitive information on-the-go, BitLocker is an excellent and easy solution.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-vegas-pro-gambit-unveiled-a-21-comprehensive-review/"><u>[New] 2024 Approved Vegas Pro Gambit Unveiled A '21 Comprehensive Review</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-skyrocketing-your-tiktok-content-speed/"><u>[New] Skyrocketing Your TikTok Content Speed</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-videotwit-grabber-capture-tweets-visuals-for-ios/"><u>[New] VideoTwit Grabber Capture Tweets' Visuals for iOS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-aspect-ratio-essentials-for-social-network-videos/"><u>2024 Approved Aspect Ratio Essentials for Social Network Videos</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-12plus-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme 12+ 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-12-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-nokia-xr21-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Nokia XR21 phone? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-article-implementing-robotic-helpers-in-your-discord-channels-efficiently/"><u>How-To Article: Implementing Robotic Helpers in Your Discord Channels Efficiently</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-cutting-edge-filmmaking-kinemasters-seamless-segments/"><u>In 2024, Cutting-Edge Filmmaking Kinemaster's Seamless Segments</u></a></li>
<li><a href="https://techidaily.com/is-your-motorola-edge-40-neo-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Motorola Edge 40 Neo working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-itel-p55-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Itel P55 Phone Now with These Tips</u></a></li>
<li><a href="https://techidaily.com/sign-word-2000-documents-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2000 Documents Online for Free</u></a></li>
<li><a href="https://fox-info.techidaily.com/swiftly-seek-and-find-discarded-reddit-posts/"><u>Swiftly Seek and Find Discarded Reddit Posts</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-xiaomi-13t-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Xiaomi 13T</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winservicesexe-on-your-pc/"><u>Troubleshooting Winservices.exe on Your PC</u></a></li>
<li><a href="https://techidaily.com/you-must-know-how-to-share-your-winning-forex-trades-with-friends-and-family-on-local-trade-copier-tm-together-by-mt4copier-guide/"><u>You must know how to Share Your Winning Forex Trades With Friends and Family on Local Trade Copier™ Together</u></a></li>
</ul></div>

