---
title: "Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide"
date: 2024-09-12T01:10:17.644Z
updated: 2024-09-13T01:10:17.644Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/81ac4ba09f7fbb502f897ca0c55434cc97c04fe41c01b4f05dc48044320b63e0.jpg
---

## Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* Open the Disks app and select the disk you want to format. Click the settings button and then select "Format Partition".
* Fill in each field, such as the partition name and file system, with the correct data, and hit "Next".
* Confirm the settings and click "Format" to format the disk.

 Need to format a disk on Ubuntu but not sure how to proceed? Disk formatting can seem difficult, especially because it's about your hard disk and not just software. Here are two easy methods, either of which will format your disk quickly and safely.

 For demonstration purposes, I'm using Ubuntu 22.04\. But you can follow this guide for newer or older versions of Ubuntu as well.

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Read This Before Formatting a Disk

 Disk formatting is a risky process. It involves deleting all data from a disk or its partitions. If you have any sensitive data on your device, then make sure to [create a backup of it first](https://blog-min.techidaily.com/how-to-downgrade-iphone-6-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/).

 The next thing you must confirm is which disk you'd like to format. If you accidentally format the wrong disk, it may even mess up your whole system. If you have many disks on your device, go through each one to ensure you're formatting the right disk.

##  Which Method Should You Use?

 Before implementing any of the methods, you should know which one will be the best for you. Both the Disks and GParted apps have graphical interfaces. So, in both methods, you don't need to write any commands to format a disk.

 If you're comparing the beginner-friendliness of each method, GParted is a bit easier to use and understand than the default Disks app.

 However, since GParted doesn't come installed by default, you need to install it first to do any disk formatting. If that's not an issue, use GParted. Otherwise, Disks will also do the trick.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 And that successfully formatted your desired disk. There is only one catch. It didn't create a partition table by default. You can do that using GParted, which I'll show you now.

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
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

 Once selected, you can create a partition table in case you don't have it already. For that, click "Device" from the top menu bar. Then, select the "Create Partition Table" button.

![GParted interface showcasing the process of creating a partition table on a disk](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12-2.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll get a warning about erasing all the data on the disk. Select the partition table type from the dropdown menu. If you're unsure, select "gpt" from all the options. Then, hit "Apply".

 In my case, I already have partition tables created, so I won't be doing that. After that, you need to unmount the partition. Right-click on the partition name and click "Unmount".

![The process of unmounting a partition from a disk using GParted on ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/13-1.png) 

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can delete that partition and convert it into unallocated space. To do that, again right-click on the partition and click "Delete".

![The GParted application showing the process of deleting an unmounted partition on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/14-2.png) 

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, right-click on the partition, and this time, click "New".

![The GParted interface displaying the process of creating a new partition from an unallocated space on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/15-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should see a new window containing many options. You can set the size, give the partition a name and label, choose the file system, and do more. I'm keeping the default values here. You should fill in the fields according to your needs. Once you're done, click "Add".

![The Create new Parition window on GParted displaying different settings of the partition that will be created](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/16-1.png) 

 However, you will notice that the operations you just performed are listed at the bottom of the window. That's because these operations are waiting for your approval. To confirm all these changes, press the green tick button from the menu bar.

![The GParted interface listing some pending operations to be confirmed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/17.png) 

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

 You will receive a warning about data loss. If you're sure about the operations, click "Apply". Once the operations are done, you'll get a message about it. Hit the "Close" button to exit the window.

![A window on GParted confirming that all the operations have been completed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/18.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And now you will find the formatted disk listed in GParted with the settings you specified earlier.

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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-hour-high-viewers-the-best-of-youtube-now/"><u>[New] In 2024, Hour-High Viewers The Best of YouTube Now</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-engaging-visuals-meet-smooth-play-with-lgs-4k-freesync-tv-for-2024/"><u>[Updated] Engaging Visuals Meet Smooth Play with LG's 4K FreeSync TV for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-unlock-instagrams-hidden-features-voice-modification/"><u>[Updated] In 2024, Unlock Instagram's Hidden Features Voice Modification</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-the-fundamentals-of-creating-dynamic-podcast-feeds-for-2024/"><u>[Updated] The Fundamentals of Creating Dynamic Podcast Feeds for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/enhanced-audio-editing-features-unveiled-in-the-latest-microsoft-clipchamp-update/"><u>Enhanced Audio Editing Features Unveiled in the Latest Microsoft Clipchamp Update</u></a></li>
<li><a href="https://techidaily.com/experience-enhanced-windows-11-upgraded-copilot-photos-widgets-and-additional-features/"><u>Experience Enhanced Windows 11: Upgraded Copilot, Photos, Widgets, and Additional Features</u></a></li>
<li><a href="https://techidaily.com/feeling-disconnected-from-your-own-windows-machine-heres-what-to-do/"><u>Feeling Disconnected From Your Own Windows Machine? Here’s What to Do!</u></a></li>
<li><a href="https://techidaily.com/four-key-moves-for-microsoft-to-rescue-copilot-and-dodge-the-cortana-mistake/"><u>Four Key Moves for Microsoft to Rescue Copilot and Dodge the Cortana Mistake</u></a></li>
<li><a href="https://techidaily.com/guide-activating-windows-latest-test-features-with-vivetool/"><u>Guide: Activating Windows' Latest Test Features with ViVeTool</u></a></li>
<li><a href="https://techidaily.com/how-microsoft-closed-the-backdoor-local-account-setup-flaw-patched-in-windows-11/"><u>How Microsoft Closed the Backdoor: Local Account Setup Flaw Patched in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-nokia-xr21-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/master-your-images-top-10-pixlr-hacks-revealed-for-2024/"><u>Master Your Images Top 10 Pixlr Hacks Revealed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-keyboard-backspace-issue/"><u>Troubleshooting Guide: Fixing the Keyboard Backspace Issue</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Vivo S18e? | Dr.fone</u></a></li>
</ul></div>

