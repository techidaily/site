---
title: "Step-by-Step: Repairing Drag And Drop Mechanism in Windows Environment"
date: 2024-09-21T03:13:50.660Z
updated: 2024-09-24T00:50:16.482Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

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
<li><a href="https://facebook-clips.techidaily.com/new-unlocking-facebook-video-success-key-strategies-revealed/"><u>[New] Unlocking Facebook Video Success Key Strategies Revealed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlocking-viral-potential-with-ai-driven-video-titles/"><u>[New] Unlocking Viral Potential with AI-Driven Video Titles</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-in-depth-look-at-bandicams-functionality-for-video-creation/"><u>[Updated] 2024 Approved In-Depth Look at Bandicam's Functionality for Video Creation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-foremost-4k-camcorders-our-best-picks/"><u>[Updated] In 2024, Foremost 4K Camcorders Our Best Picks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-video-storytelling-adding-narration-step-by-step/"><u>[Updated] Mastering Video Storytelling Adding Narration Step-by-Step</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-unlock-free-tunes-steps-for-youtube-content-creators/"><u>2024 Approved Unlock Free Tunes Steps for YouTube Content Creators</u></a></li>
<li><a href="https://techidaily.com/cambia-archivos-de-tiff-a-jpg-sin-coste-con-la-herramienta-on-line-de-conversion-de-imagenes-de-movavi/"><u>Cambia Archivos De Tiff a Jpg Sin Coste Con La Herramienta On-Line De Conversión De Imágenes De Movavi</u></a></li>
<li><a href="https://techidaily.com/cambiar-facilmente-webm-a-mov-file-sin-coste-con-herramienta-de-movavi/"><u>Cambiar Fácilmente Webm a Mov File Sin Coste Con Herramienta De Movavi</u></a></li>
<li><a href="https://techidaily.com/capturing-desktop-activity-a-guide-to-screen-recording-with-audio-on-windows-systems/"><u>Capturing Desktop Activity: A Guide to Screen Recording With Audio on Windows Systems</u></a></li>
<li><a href="https://techidaily.com/choosing-the-right-video-format-a-comprehensive-guide-on-mp4-vs-mkv/"><u>Choosing the Right Video Format: A Comprehensive Guide on MP4 vs MKV</u></a></li>
<li><a href="https://techidaily.com/comparando-formatos-de-video-en-que-se-diferencian-mp4-y-wmv/"><u>Comparando Formatos De Video: En Qué Se Diferencian MP4 Y WMV</u></a></li>
<li><a href="https://techidaily.com/conversione-online-per-la-gratuita-da-wav-a-formato-m4b-senza-problemi-usando-movavi/"><u>Conversione Online per La Gratuità: Da WAV a Formato M4B Senza Problemi Usando Movavi</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-quick-fix-for-background-removal-in-figma-projects/"><u>In 2024, Quick Fix for Background Removal in Figma Projects</u></a></li>
<li><a href="https://techidaily.com/caf-mp4-movavi/"><u>무료 CAF 형식으로의 MP4 파일 변환: 구현 방법 - Movavi</u></a></li>
</ul></div>

