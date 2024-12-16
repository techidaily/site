---
title: "Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide"
date: 2024-12-13T20:37:02.745Z
updated: 2024-12-15T17:38:47.797Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/81ac4ba09f7fbb502f897ca0c55434cc97c04fe41c01b4f05dc48044320b63e0.jpg
---

## Two Methods for Formatting Drives in Ubuntu: A Comprehensive Guide

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When the application opens, you will find your system storage, both internal and external, listed on the left sidebar. Select the disk that you want to format. Ideally, you're supposed to have multiple disks from which you will format one or more. In my case, since I'm on a virtual machine, there's only one disk. After selecting the disk, click the settings icon.

![An example of the Disks utility app on Ubuntu where a disk is selected](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-4.png) 

 That should open a context menu. Click the "Format Partition" button to continue.

![A context menu displaying different operations that can be performed on the selected hard disk on the Disks app](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should see a new menu about the selected volume. There are many options here. Let's go through them one by one.

1. First, you can give a name to the new volume. Insert the name in the "Volume Name" field. I named it "Test".
2. Next, there's a toggle button that lets you completely delete or keep the existing data. If you decide to turn it on, make sure to get a backup of any important data before you erase it. I'm keeping it disabled.
3. Select the type of file system you want to use for the partition. If you only want to use the disk for Linux, you can keep the default "Ext4" option selected. If you want to use it for Windows only, then select [NTFS](https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/). However, if you want to use the disk for [file transfer between several operating systems](https://screen-capture.techidaily.com/in-2024-step-by-step-approach-to-mastering-the-steam-pro-controller-on-switch/), go with FAT. I'm going to use Ext4.

 Once you're done with the settings, click "Next".

![The 'Format Volume' window on the Disks utility containing several options about disk formatting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A new window with confirmation details will appear. You can double-check the details here just to be sure. If all looks good, click "Format" to begin the formatting. On the other hand, click the "Previous" button to navigate to the previous window.

![The final confirmation window in Ubuntu's Disks utility prompting the user to confirm formatting details before proceeding](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-4.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll be asked to authenticate the action. Enter your password and click "Authenticate."

![The Ubuntu authentication window asking for user password](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-3.png) 

 After that, you will be brought back to the initial Disks window. This time, you will notice a triangle-shaped play button beside the settings button. Click it to mount the partition.

![Disks utility window after you formatted a drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-2.png) 

 And that successfully formatted your desired disk. There is only one catch. It didn't create a partition table by default. You can do that using GParted, which I'll show you now.

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

 You'll get a warning about erasing all the data on the disk. Select the partition table type from the dropdown menu. If you're unsure, select "gpt" from all the options. Then, hit "Apply".

 In my case, I already have partition tables created, so I won't be doing that. After that, you need to unmount the partition. Right-click on the partition name and click "Unmount".

![The process of unmounting a partition from a disk using GParted on ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/13-1.png) 

 Now you can delete that partition and convert it into unallocated space. To do that, again right-click on the partition and click "Delete".

![The GParted application showing the process of deleting an unmounted partition on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/14-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After that, right-click on the partition, and this time, click "New".

![The GParted interface displaying the process of creating a new partition from an unallocated space on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/15-1.png) 

 You should see a new window containing many options. You can set the size, give the partition a name and label, choose the file system, and do more. I'm keeping the default values here. You should fill in the fields according to your needs. Once you're done, click "Add".

![The Create new Parition window on GParted displaying different settings of the partition that will be created](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/16-1.png) 

 However, you will notice that the operations you just performed are listed at the bottom of the window. That's because these operations are waiting for your approval. To confirm all these changes, press the green tick button from the menu bar.

![The GParted interface listing some pending operations to be confirmed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/17.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will receive a warning about data loss. If you're sure about the operations, click "Apply". Once the operations are done, you'll get a message about it. Hit the "Close" button to exit the window.

![A window on GParted confirming that all the operations have been completed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/18.png) 

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-explore-best-selections-for-youtube-ringtone-downloads/"><u>[New] 2024 Approved Explore Best Selections for YouTube Ringtone Downloads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-pros-picks-top-10-spotify-recording-applications/"><u>[New] Pro's Picks Top 10 Spotify Recording Applications</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-perfecting-your-youtube-presence-a-video-upload-manual/"><u>[Updated] Perfecting Your YouTube Presence A Video Upload Manual</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-step-by-step-screen-capture-on-apple-device/"><u>2024 Approved Step-by-Step Screen Capture on Apple Device</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-top-10-hilarious-song-mock-ups-laughter-unleashed/"><u>2024 Approved Top 10 Hilarious Song Mock-Ups Laughter Unleashed</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-ultimate-list-of-no-cost-webcam-tools-for-pc-users-windows-nt/"><u>Discover the Ultimate List of No-Cost Webcam Tools for PC Users (Windows nT)</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-nokia-c300-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-samsung-galaxy-a23-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Samsung Galaxy A23 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-15-to-the-previous-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 15 to the Previous iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-mini-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 mini System Issues? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-lava-yuva-3-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Lava Yuva 3 phone? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-samsung-galaxy-f15-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Samsung Galaxy F15 5G to Another | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-7-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 7 without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-se-2022-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone SE (2022) to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-14-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 14 Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-oppo-find-x7-ultra-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Oppo Find X7 Ultra</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210399241-9789389157635-the-seven-laws-of-teaching/"><u>The Seven Laws of Teaching | Free Book</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-ultra-hd-films-downloaded-safely-and-quickly-a-comprehensive-guide/"><u>Top Ultra HD Films Downloaded Safely and Quickly: A Comprehensive Guide</u></a></li>
</ul></div>

