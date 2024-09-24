---
title: Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine
date: 2024-09-18T21:34:34.572Z
updated: 2024-09-23T20:08:49.813Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52687750468_dc6bdda141_o-19.jpg
---

## Quickly Lock Your Window's Desktop via Command Prompt on a Windows 11 Machine

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://screen-activity-recording.techidaily.com/new-dividing-recordings-top-cam-scrutiny-review-for-2024/"><u>[New] Dividing Recordings Top Cam Scrutiny Review for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-newbies-netflix-nook-deciphering-resolution-ratings/"><u>[New] In 2024, Newbie's Netflix Nook Deciphering Resolution Ratings</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-achieve-professional-aesthetics-embedding-watermarks-and-branding-in-videos-for-2024/"><u>[Updated] Achieve Professional Aesthetics Embedding Watermarks & Branding in Videos for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-optimal-4k-player-picks-best-8-free-cross-platform-compatible/"><u>[Updated] Optimal 4K Player Picks Best 8 FREE, Cross-Platform Compatible</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevating-creative-content-vimeo-vs-youtubes-approach/"><u>2024 Approved Elevating Creative Content Vimeo vs YouTube's Approach</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/djis-minis-and-air-2-free-fun-luts-for-ultimate-mixes/"><u>DJI's Minis & Air 2 Free, Fun LUTS for Ultimate Mixes</u></a></li>
<li><a href="https://techidaily.com/gratis-ogg-to-m4r-converter-online-vrije-en-eenvoudige-voorbereiding-met-movavi/"><u>Gratis OGG-to-M4R Converter Online - Vrije en Eenvoudige Voorbereiding Met Movavi</u></a></li>
<li><a href="https://techidaily.com/gratuit-online-konvertereen-avi-naar-nsv-professioneel-movavi/"><u>Gratuit Online Konvertereen AVI Naar NSV - Professioneel Movavi</u></a></li>
<li><a href="https://win-blog.techidaily.com/guia-paso-a-paso-agregar-sincronizacion-de-titulos-cc-en-videos-con-movavi/"><u>Guía Paso a Paso: Agregar Sincronización De Títulos (CC) en Videos Con Movavi</u></a></li>
<li><a href="https://techidaily.com/guide-facile-dapres-vente-convertir-des-fichiers-mxf-en-mp3-sans-frais-sur-movavi/"><u>Guide Facile D'après-Vente: Convertir Des Fichiers MXF en MP3 Sans Frais Sur Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-google-pixel-8-pro-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Google Pixel 8 Pro Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-harmonizing-visual-narratives-with-live-sounds/"><u>In 2024, Harmonizing Visual Narratives with Live Sounds</u></a></li>
<li><a href="https://techidaily.com/les-13-meilleurs-convertisseurs-youtube-vers-mp3-pour-2024-une-selection-complete/"><u>Les 13 Meilleurs Convertisseurs YouTube Vers MP3 Pour 2024 : Une Sélection Complète</u></a></li>
<li><a href="https://techidaily.com/les-meilleurs-outils-en-ligne-pour-capturer-des-contenu-video-a-partir-de-la-toile/"><u>Les Meilleurs Outils en Ligne Pour Capturer Des Contenu Vidéo À Partir De La Toile</u></a></li>
<li><a href="https://techidaily.com/los-mejores-programas-libres-de-corte-de-videos-que-debes-usar-en-el-ano-2024/"><u>Los Mejores Programas Libres De Corte De Vídeos Que Debes Usar en El Año 2024</u></a></li>
<li><a href="https://techidaily.com/m4v-afbeeldingen-in-wms-kletsen-voor-zwdaarom-eenvoudig-gratis-en-betrouwbaar-met-movavi-converter/"><u>M4V-Afbeeldingen in Wms Kletsen Voor ZwDaarom - Eenvoudig, Gratis en Betrouwbaar Met Movavi Converter</u></a></li>
<li><a href="https://techidaily.com/mastering-facetime-recording-a-step-by-step-tutorial-for-superior-sound/"><u>Mastering FaceTime Recording: A Step-by-Step Tutorial for Superior Sound</u></a></li>
<li><a href="https://techidaily.com/movavis-ultimate-guide-to-optimizing-your-obs-setup-for-professional-quality-streaming/"><u>Movavi's Ultimate Guide to Optimizing Your OBS Setup for Professional Quality Streaming</u></a></li>
<li><a href="https://win-answers.techidaily.com/stop-dota-2-from-freezing-expert-tips-and-fixes/"><u>Stop Dota 2 From Freezing: Expert Tips and Fixes!</u></a></li>
</ul></div>

