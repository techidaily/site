---
title: "Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide"
date: 2024-11-07T00:40:08.378Z
updated: 2024-11-14T00:11:33.556Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/81ac4ba09f7fbb502f897ca0c55434cc97c04fe41c01b4f05dc48044320b63e0.jpg
---

## Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide

### Key Takeaways

* Open the Disks app and select the disk you want to format. Click the settings button and then select "Format Partition".
* Fill in each field, such as the partition name and file system, with the correct data, and hit "Next".
* Confirm the settings and click "Format" to format the disk.

 Need to format a disk on Ubuntu but not sure how to proceed? Disk formatting can seem difficult, especially because it's about your hard disk and not just software. Here are two easy methods, either of which will format your disk quickly and safely.

 For demonstration purposes, I'm using Ubuntu 22.04\. But you can follow this guide for newer or older versions of Ubuntu as well.

##  Read This Before Formatting a Disk

 Disk formatting is a risky process. It involves deleting all data from a disk or its partitions. If you have any sensitive data on your device, then make sure to [create a backup of it first](https://blog-min.techidaily.com/how-to-downgrade-iphone-6-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/).

 The next thing you must confirm is which disk you'd like to format. If you accidentally format the wrong disk, it may even mess up your whole system. If you have many disks on your device, go through each one to ensure you're formatting the right disk.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Which Method Should You Use?

 Before implementing any of the methods, you should know which one will be the best for you. Both the Disks and GParted apps have graphical interfaces. So, in both methods, you don't need to write any commands to format a disk.

 If you're comparing the beginner-friendliness of each method, GParted is a bit easier to use and understand than the default Disks app.

 However, since GParted doesn't come installed by default, you need to install it first to do any disk formatting. If that's not an issue, use GParted. Otherwise, Disks will also do the trick.

##  Method 1: Formatting a Disk on Ubuntu Using the Disks App

 First, open the applications menu by pressing the "Show Applications" button.

![Ubuntu 22.04 version homescreen](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-3.png) 

 In the applications grid, click the "Utilities" app group.

![All applications displayed in a grid layout on the Ubuntu applications menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-5.png) 

 It should display all the utility software on your system. From there, click "Disks" to launch it.

![The utility app group displaying all the available utility software on Ubuntu including 'Disks'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-5.png) 

 When the application opens, you will find your system storage, both internal and external, listed on the left sidebar. Select the disk that you want to format. Ideally, you're supposed to have multiple disks from which you will format one or more. In my case, since I'm on a virtual machine, there's only one disk. After selecting the disk, click the settings icon.

![An example of the Disks utility app on Ubuntu where a disk is selected](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-4.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That should open a context menu. Click the "Format Partition" button to continue.

![A context menu displaying different operations that can be performed on the selected hard disk on the Disks app](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-2.png) 

 You should see a new menu about the selected volume. There are many options here. Let's go through them one by one.

1. First, you can give a name to the new volume. Insert the name in the "Volume Name" field. I named it "Test".
2. Next, there's a toggle button that lets you completely delete or keep the existing data. If you decide to turn it on, make sure to get a backup of any important data before you erase it. I'm keeping it disabled.
3. Select the type of file system you want to use for the partition. If you only want to use the disk for Linux, you can keep the default "Ext4" option selected. If you want to use it for Windows only, then select [NTFS](https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/). However, if you want to use the disk for [file transfer between several operating systems](https://screen-capture.techidaily.com/in-2024-step-by-step-approach-to-mastering-the-steam-pro-controller-on-switch/), go with FAT. I'm going to use Ext4.

 Once you're done with the settings, click "Next".

![The 'Format Volume' window on the Disks utility containing several options about disk formatting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-3.png) 

 A new window with confirmation details will appear. You can double-check the details here just to be sure. If all looks good, click "Format" to begin the formatting. On the other hand, click the "Previous" button to navigate to the previous window.

![The final confirmation window in Ubuntu's Disks utility prompting the user to confirm formatting details before proceeding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-4.png) 

 You'll be asked to authenticate the action. Enter your password and click "Authenticate."

![The Ubuntu authentication window asking for user password](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-3.png) 

 After that, you will be brought back to the initial Disks window. This time, you will notice a triangle-shaped play button beside the settings button. Click it to mount the partition.

![Disks utility window after you formatted a drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-2.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that successfully formatted your desired disk. There is only one catch. It didn't create a partition table by default. You can do that using GParted, which I'll show you now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 2: Formatting a Disk on Ubuntu Using GParted

[GParted](https://gparted.org/) is a graphical partition editing application. Since it's not installed by default on your system, you need to install it first.

 Before installing it though, you should update your software repository cache to make sure you have access to the latest packages. Open your terminal by pressing Ctrl+Alt+T and run:

sudo apt update

 After that, install GParted on Ubuntu by running:

sudo apt install gparted

![The Linux terminal prompting the user to confirm the installation of GParted on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-2.png) 

 After GParted is installed, you can either launch it from the applications menu or the terminal. Since you're already on the terminal, launch GParted using:

gparted

 You'll be asked to authenticate by entering your password. Once you do that, the application should open. The first thing you must do is select the disk you want to format. You can do that from the dropdown menu in the top-right corner of the software. Click the drop-down menu and select a disk.

![An example of GParted interface while selecting a drive from the dropdown menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/11-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once selected, you can create a partition table in case you don't have it already. For that, click "Device" from the top menu bar. Then, select the "Create Partition Table" button.

![GParted interface showcasing the process of creating a partition table on a disk](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12-2.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll get a warning about erasing all the data on the disk. Select the partition table type from the dropdown menu. If you're unsure, select "gpt" from all the options. Then, hit "Apply".

 In my case, I already have partition tables created, so I won't be doing that. After that, you need to unmount the partition. Right-click on the partition name and click "Unmount".

![The process of unmounting a partition from a disk using GParted on ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/13-1.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can delete that partition and convert it into unallocated space. To do that, again right-click on the partition and click "Delete".

![The GParted application showing the process of deleting an unmounted partition on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/14-2.png) 

 After that, right-click on the partition, and this time, click "New".

![The GParted interface displaying the process of creating a new partition from an unallocated space on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/15-1.png) 

 You should see a new window containing many options. You can set the size, give the partition a name and label, choose the file system, and do more. I'm keeping the default values here. You should fill in the fields according to your needs. Once you're done, click "Add".

![The Create new Parition window on GParted displaying different settings of the partition that will be created](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/16-1.png) 

 However, you will notice that the operations you just performed are listed at the bottom of the window. That's because these operations are waiting for your approval. To confirm all these changes, press the green tick button from the menu bar.

![The GParted interface listing some pending operations to be confirmed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/17.png) 

 You will receive a warning about data loss. If you're sure about the operations, click "Apply". Once the operations are done, you'll get a message about it. Hit the "Close" button to exit the window.

![A window on GParted confirming that all the operations have been completed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/18.png) 

 And now you will find the formatted disk listed in GParted with the settings you specified earlier.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948909/19272" target="_top" id="1948909">
  <img src="//a.impactradius-go.com/display-ad/19272-1948909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Disk Formatting on Ubuntu Made Easy!

 So that wraps up this guide. I hope you were able to format your targeted disk successfully on Ubuntu. If you have made a backup, now is the time to restore it to the newly formatted disk.

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
<li><a href="https://fox-info.techidaily.com/new-proven-sites-for-downloading-premier-pixel-tones/"><u>[New] Proven Sites for Downloading Premier Pixel Tones</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-the-ultimate-guide-to-whatsapp-audio-chat-for-2024/"><u>[New] The Ultimate Guide to WhatsApp Audio Chat for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-monitoring-instagram-disconnects-immediately/"><u>[Updated] 2024 Approved Monitoring Instagram Disconnects Immediately</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-resonance-and-rhythm-guide-to-downloading-vintage-ringtones-for-2024/"><u>[Updated] Resonance and Rhythm Guide to Downloading Vintage Ringtones for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-piracy-safe-youtube-to-mp4-conversion-tips/"><u>Avoid Piracy Safe YouTube to MP4 Conversion Tips</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-itel-p55-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Itel P55 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-tecno-phantom-v-flip-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-not-present-screen-blank/"><u>GPU Not Present, Screen Blank</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-f54-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy F54 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y200e-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y200e 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nubia-red-magic-9-proplus-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nubia Red Magic 9 Pro+ without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-ace-2v-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Ace 2V Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2020-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2020) to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-igniting-virality-with-captivating-fb-giveaway-campaigns/"><u>In 2024, Igniting Virality with Captivating FB Giveaway Campaigns</u></a></li>
<li><a href="https://facebook.techidaily.com/picture-perfect-panoramas-creating-a-facebook-photo-mosaic/"><u>Picture Perfect Panoramas: Creating a Facebook Photo Mosaic</u></a></li>
<li><a href="https://video-capture.techidaily.com/pioneering-apps-for-diverse-game-file-logging-needs/"><u>Pioneering Apps for Diverse Game File Logging Needs</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-13-pro-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 13 Pro Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/xiaomi-14-pro-messages-recovery-recover-deleted-messages-from-xiaomi-14-pro-by-fonelab-android-recover-messages/"><u>Xiaomi 14 Pro Messages Recovery - Recover Deleted Messages from Xiaomi 14 Pro</u></a></li>
</ul></div>

