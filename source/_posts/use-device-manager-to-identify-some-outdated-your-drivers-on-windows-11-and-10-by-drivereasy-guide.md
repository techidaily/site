---
title: Use Device Manager to identify some outdated your drivers on Windows 11 & 10
date: 2024-11-07T16:30:32.912Z
tags: 
  - driver
  - device driver
categories: 
  - apps
  - windows
description: This article describes Use Device Manager to identify some outdated your drivers on Windows 11 & 10. Device Manager is a control panel applet in Microsoft Windows operating systems. It allows users to view and control the hardware attached to the computer. When a piece of hardware is not working, the offending hardware is highlighted for the user to deal with. The list of hardware can be sorted by various criteria. Device Manager was introduced with Windows 95 and later added to Windows 2000. In NT-based versions, it is included as a Microsoft Management Console snap-in.
keywords: identify some outdated drivers in Windows 11 & 10,device manager,identify some outdated drivers in Windows 7,identify some outdated drivers in Windows 10,identify some outdated drivers in Windows 10 & 7,identify some outdated drivers in Windows 11
---

## How to identify (some) outdated drivers with Windows Device Manager

Identifying outdated drivers with Device Manager is a very tedious process. You can’t tell, just by looking at the device in Device Manager, if its driver is out of date. You have to actually try to update the driver, If Windows thinks the driver is out of date, it will update it for you; if not, it will tell you you already have the latest driver.

> IMPORTANT: As discussed later on this page, Windows Device Manager doesn’t always detect outdated drivers. Nor does it always give you the latest available version if you update a driver. If you want to be sure you have the latest available version of a driver, you need to source the driver directly from the device manufacturer or use a tool like ours, called [Driver Easy](https://www.drivereasy.com/goto/affdownload.php?affid=108875), to do it automatically.






## Why you can’t rely on Windows to keep your drivers up-to-date

Windows comes with an inbuilt tool, called ‘Windows Update’, that’s supposed to automatically keep your drivers up to date. Unfortunately, it doesn’t work very well.

There are two reasons why…

- Device manufacturers often take a long time to get their drivers into a Windows Update – It’s a time-consuming and difficult process. Sometimes they just miss the deadline and have to wait ‘til the next Windows Update, and sometimes they just give up altogether. In fact, for older devices, this is the norm.

- Windows Update ignores driver updates it considers ‘optional’ – It categorizes driver updates as either ‘critical’, ‘automatic’ or ‘optional’, and it doesn’t usually concern itself with the ‘optional’ ones – even when they’re actually important. You can install them manually by going to the ‘Optional updates’ screen but, even then, as described above, you’re unlikely to get all the latest drivers.

## What are drivers?

Drivers are like interpreters between Windows and your devices. For example, when Windows needs to display something on your monitor, it sends a command to your graphics card, and your graphics card then displays what Windows wants on your monitor.

But Windows and your graphics card don’t actually speak the same language. To understand each other, they need a translator. That translator is called a driver. It takes the Windows command and translates it into something your graphics card can understand. Your graphics card can then do as it’s told, and display the right thing on your monitor.

Similarly, if your graphics card needs to send some sort of response back to Windows, the driver translates the response into something Windows can understand.

In this example, what we’re talking about is a video driver, but your computer has many other drivers on it too – one for each device. Your speakers, your printer, your mouse, your USB hard drives, your network card, your keyboard and so on – they each have an associated driver.

And without all these drivers, none of your devices will work.

![What are drivers?](https://tools.techidaily.com/images/apps/drivereasy/pages/why_2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What happens if a driver is missing or outdated?

Every now and then, Microsoft will change the commands Windows sends to one of your devices (e.g. your network card). When this happens, the manufacturer of that device need to change the device driver too. They need to teach it the new Windows commands. Otherwise the drivers won’t be able to translate those commands for your devices, and your devices won’t work properly.

The same thing needs to happen when your device manufacturer changes the way your device talks, or the things it can do. They need to change the driver too. Otherwise Windows won’t be able to talk to the device, or take advantage of its new functionality, and your device won’t work properly.

Now when we say “your device won’t work properly”, sometimes this means simply that you miss out on new functionality or minor bug fixes. But it’s often a lot more serious than that. Your computer may even hang, crash or stop working completely. Remember, there’s a driver that controls your hard drive, for instance. If Windows can’t talk to your hard drive, it can’t access any of the data on your drive. Similarly, if Windows can’t talk to your network card, you won’t be able to access the internet, and if it can’t talk to your graphics card, you won’t be able to see anything on your monitor. These are just a few of the more serious issues outdated drivers can cause.

![What happens if a driver is missing or outdated?](https://tools.techidaily.com/images/apps/drivereasy/pages/why_3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027167/19272" target="_top" id="2027167">
  <img src="//a.impactradius-go.com/display-ad/19272-2027167" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027167/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Download Driver Easy FREE

If you’re having computer issues, the first thing you should do is see if it has outdated drivers. If it does, updating them will very often fix things.

And for this, our tool, Driver Easy FREE, is the ideal solution.

Driver Easy FREE is a driver update tool used by more than 3 million customers around the world. It will automatically identify and download all the drivers you need, so all you have to do is install them.

In other words, it eliminates the need to find and download your drivers the difficult way (via the manufacturer’s website).

You don’t need to know what system your computer is running, you don’t need to scour the web for the right driver download, and you don’t need to risk downloading the wrong driver. Driver Easy does it all for you, automatically. No computer knowledge needed, and it’s completely free.

This page describes how to do this.

[Download Free Version](https://www.drivereasy.com/goto/affdownload.php?affid=108875)

The free version will identify all your outdated drivers, and allow you to download them all. But only one at a time and, once they’re downloaded, you have to manually install them using the standard Windows process. (To automatically update all your drivers with 1 click, you’ll need [the Pro version of Driver Easy](https://tools.techidaily.com/drivereasy/download/). Don’t worry, it comes with a 30-day, no-questions-asked, money back satisfaction guarantee.)

## Try Driver Easy for free

If you want the certainty of knowing your device drivers are always up to date (and not just sometimes up to date, which is all you get from Windows Device Manager), and you don’t have the time, patience or computer skills to continually update them manually, give the free version of [Driver Easy](https://tools.techidaily.com/drivereasy/download/) a try.

[Download Free Version](https://www.drivereasy.com/goto/affdownload.php?affid=108875)

The free version will identify all your outdated drivers, and allow you to download them all. But only one at a time and, once they’re downloaded, you have to manually install them using the standard Windows process. (To automatically update all your drivers with 1 click, you’ll need [the Pro version of Driver Easy](https://tools.techidaily.com/drivereasy/download/). Don’t worry, it comes with a 30-day, no-questions-asked, money back satisfaction guarantee.)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-face-fluidity-techniques-implementing-motion-blur-effects/"><u>[New] Face Fluidity Techniques Implementing Motion Blur Effects</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-snapmaster-z7-pro-excellence-in-picture-magnification/"><u>[New] In 2024, SnapMaster Z7 Pro Excellence in Picture Magnification</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamlining-your-avatar-on-google-meet-devices-for-2024/"><u>[Updated] Streamlining Your Avatar on Google Meet Devices for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-professional-portrait-maker-for-passports-desktop-and-online-access-only/"><u>2024 Approved Professional Portrait Maker for Passports – Desktop & Online Access Only</u></a></li>
<li><a href="https://data-wizards.techidaily.com/exchanging-praise-with-a-pro-fabio-goncalves-on-it-testimonials/"><u>Exchanging Praise with a Pro: Fabio Goncalves on IT Testimonials</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y28-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y28 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-7-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 7 to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-oppo-a56s-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Oppo A56s 5G FRP?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/lapscape-dreaming-choosing-the-best-websites-for-aesthetic-backgrounds/"><u>Lapscape Dreaming Choosing the Best Websites for Aesthetic Backgrounds</u></a></li>
<li><a href="https://fox-blue.techidaily.com/maximum-video-stowage-on-a-single-64gb-unit/"><u>Maximum Video Stowage on a Single 64Gb Unit</u></a></li>
<li><a href="https://win-blog.techidaily.com/profesyonel-destek-programi-movavi-destekleme-kolayla-bilgisayarlar-aracisindan-gelistirilmis/"><u>Profesyonel Destek Programı - Movavi: Destekleme Kolayla Bilgisayarlar Aracısından Geliştirilmiş</u></a></li>
<li><a href="https://techidaily.com/remove-samsung-lock-screen-without-password-samsung-galaxy-a24-by-drfone-android-unlock-android-unlock/"><u>Remove Samsung Lock Screen without Password(Samsung Galaxy A24)</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-xiaomi-redmi-note-13-proplus-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Xiaomi Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-tecno-spark-10c-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Tecno Spark 10C</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-a38-by-fonelab-android-recover-video/"><u>Undeleted lost videos from A38</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-lava-blaze-2-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Lava Blaze 2</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-xiaomi-redmi-note-12t-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Xiaomi Redmi Note 12T Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/why-are-your-photos-lost-from-iphone-12-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why are your photos lost from iPhone 12? | Stellar</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/zoom-video-clarity-a-step-by-step-2024-camera-repair-guide/"><u>Zoom Video Clarity - A Step-by-Step 2024 Camera Repair Guide</u></a></li>
</ul></div>

