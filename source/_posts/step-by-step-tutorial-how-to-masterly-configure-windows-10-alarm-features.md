---
title: "Step-by-Step Tutorial: How To Masterly Configure Windows 10 Alarm Features"
date: 2024-09-23T03:37:05.368Z
updated: 2024-09-23T19:10:11.216Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step Tutorial: How To Masterly Configure Windows 10 Alarm Features"
excerpt: "This Article Describes Step-by-Step Tutorial: How To Masterly Configure Windows 10 Alarm Features"
thumbnail: https://thmb.techidaily.com/5cbe5314b93a999758b5a00e2527a722031ccfee99834737192b083e09532191.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-viral-photo-trends-capturing-memes-true-essence/"><u>[New] In 2024, Viral Photo Trends Capturing Memes' True Essence</u></a></li>
<li><a href="https://techidaily.com/boost-your-laptops-performance-swiftly-on-windows-11781-with-these-easy-tips/"><u>Boost Your Laptop's Performance Swiftly on Windows 11/7/8.1 with These Easy Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/cambiar-tus-archivos-de-formato-snd-a-pdfaudio-gratis-online-con-conversor-de-archivo/"><u>Cambiar Tus Archivos De Formato SND a PDF/Audio Gratis Online Con Conversor De Archivo</u></a></li>
<li><a href="https://techidaily.com/connecting-multiple-screens-to-your-computer-explained/"><u>Connecting Multiple Screens to Your Computer Explained</u></a></li>
<li><a href="https://techidaily.com/diablo-ii-reimagined-ultimate-tips-and-tricks-for-maximizing-frame-rate/"><u>Diablo II Reimagined: Ultimate Tips & Tricks for Maximizing Frame Rate</u></a></li>
<li><a href="https://techidaily.com/directx-12-downloading-made-easy-tips-and-steps-for-windows-10-users/"><u>DirectX 12 Downloading Made Easy - Tips & Steps for Windows 10 Users</u></a></li>
<li><a href="https://techidaily.com/easy-guide-sharing-gameplay-experiences-with-loved-ones-on-xbox-one/"><u>Easy Guide: Sharing Gameplay Experiences with Loved Ones on Xbox One</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-poco-by-drfone-android/"><u>How to Show Wi-Fi Password on Poco</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-advanced-recording-software-outshining-fbx-methods/"><u>In 2024, Advanced Recording Software Outshining FBX Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-amplify-engagement-through-linked-story-sharing/"><u>In 2024, Amplify Engagement Through Linked Story Sharing</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-innovative-ways-to-control-your-iphones-picture-angles/"><u>In 2024, Innovative Ways to Control Your iPhone's Picture Angles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-recmaster-screen-recorder-review/"><u>In 2024, Recmaster Screen Recorder Review</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-vivo-x-fold-2-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Vivo X Fold 2 Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

