---
title: Resolving Windows 10 Installation Issue - Fix Error Code 80 #
date: 2024-09-18T23:45:16.076Z
updated: 2024-09-24T04:59:41.616Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Resolving Windows 10 Installation Issue - Fix Error Code 80 #
excerpt: This Article Describes Resolving Windows 10 Installation Issue - Fix Error Code 80 #
thumbnail: https://thmb.techidaily.com/f051850e231be7d8e7141a137d6f961668fd1698700240c7348f6738ce5b4e95.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-aesthetic-instagram-panoramas/"><u>[New] In 2024, Aesthetic Instagram Panoramas</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-simplifying-transition-workflows-audacitys-crossfade-capabilities/"><u>[New] Simplifying Transition Workflows Audacity's Crossfade Capabilities</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-efficiently-implementing-youtube-end-screens/"><u>[Updated] 2024 Approved Efficiently Implementing Youtube End Screens</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-connect-your-content-from-twitch-to-facebook/"><u>[Updated] In 2024, Connect Your Content From Twitch to Facebook</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-music-merging-techniques-for-premiere-pro-editors/"><u>[Updated] Music Merging Techniques for Premiere Pro Editors</u></a></li>
<li><a href="https://techidaily.com/1726233723807-avimp4-movavi/"><u>無料で簡単なAVIファイルのMP4へのオンライン変換 - Movavi</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-htc-u23-pro-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve HTC U23 Pro Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-adobe-lightroom-essentials-review/"><u>In 2024, Adobe Lightroom Essentials Review</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pinnacle-enterprise-data-vaulting-for-2024/"><u>Pinnacle Enterprise Data Vaulting for 2024</u></a></li>
<li><a href="https://techidaily.com/top-green-screen-apps-compatible-with-pc-android-and-ios-devices/"><u>Top Green Screen Apps Compatible with PC, Android & iOS Devices</u></a></li>
<li><a href="https://techidaily.com/top-video-converters-for-ts-to-mp4-conversion-reviews-and-comparisons/"><u>Top Video Converters for TS to MP4 Conversion - Reviews and Comparisons</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/transform-your-vob-videos-into-avi-for-free-using-movavis-web-service/"><u>Transform Your VOB Videos Into AVI for Free Using Movavi's Web Service</u></a></li>
<li><a href="https://techidaily.com/transforma-tus-clips-wav-al-formato-avi-sin-costo-alguno-usando-el-convertidor-en-linea-de-movavi/"><u>Transforma Tus Clips WAV Al Formato AVI Sin Costo Alguno Usando El Convertidor en Línea De Movavi</u></a></li>
<li><a href="https://techidaily.com/transformar-imagenes-de-rw2-a-jpg-sin-coste-adicional-con-la-herramienta-online-de-muoviavi/"><u>Transformar Imágenes De RW2 a JPG Sin Coste Adicional Con La Herramienta Online De MuoviAVI</u></a></li>
<li><a href="https://techidaily.com/wmvswf-pdfepub/"><u>WMV/SWF 파일을 원거나 보다 강력한 구성으로 PDF/EPUB로 무료 바이트 단위로 온라인 전송</u></a></li>
<li><a href="https://techidaily.com/webp-gifmovavi/"><u>オンライン無料WEBP画像直し - GIF形式にMovavi変換する方法</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

