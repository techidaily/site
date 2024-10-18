---
title: "Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
date: 2024-10-10T17:19:59.631Z
updated: 2024-10-18T05:08:55.825Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
excerpt: "This Article Describes Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
thumbnail: https://thmb.techidaily.com/e64ba1588493794efe1f30713a2c1b387c63e2ee11d657d48f4608e17ab1d777.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-a-step-by-step-approach-to-youtube-gold-music-reaction-magic/"><u>[New] 2024 Approved A Step-by-Step Approach to YouTube Gold Music Reaction Magic</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-flat-screens-to-spatial-storytelling-understanding-vr/"><u>[New] From Flat Screens to Spatial Storytelling Understanding VR</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-seamless-integration-transferring-snapchat-images-directly/"><u>[Updated] 2024 Approved Seamless Integration Transferring Snapchat Images Directly</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-the-art-of-youtube-trailers-using-filmora-tools/"><u>[Updated] In 2024, The Art of YouTube Trailers Using Filmora Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-strategies-for-itunes-podcast-enrollment-success/"><u>[Updated] Strategies for iTunes Podcast Enrollment Success</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-leveraging-health-data-in-online-healthcare-ads/"><u>2024 Approved Leveraging Health Data in Online Healthcare Ads</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-vivo-y55s-5g-2023-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Vivo Y55s 5G (2023) Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-x8b-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor X8b in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-edge-40-neo-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola Edge 40 Neo in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-ios-beta-version-on-apple-iphone-8-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-11-pro-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 11 Pro System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-reno-10-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo Reno 10 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-tech-gurus-rate-them-all-unveiling-apeaksofts-screen-recording-capabilities/"><u>In 2024, Tech Gurus Rate Them All Unveiling Apeaksoft’s Screen Recording Capabilities</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/instant-impact-facebook-vids/"><u>Instant Impact Facebook Vids</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-motorola-moto-g34-5g-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Motorola Moto G34 5G has been deleted</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-gionee-f3-pro-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Gionee F3 Pro</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-motorola-edgeplus-2023-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Motorola Edge+ (2023)</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-90-pro-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on 90 Pro without backup.</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
</ul></div>

