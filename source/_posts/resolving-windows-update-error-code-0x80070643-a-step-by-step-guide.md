---
title: "Resolving Windows Update Error Code 0X80070643: A Step-by-Step Guide"
date: 2024-12-02T18:22:18.982Z
updated: 2024-12-09T17:10:14.565Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/bbcc4a007f0a07614972fe24eb730165421ff81b1eea5d7fad50043a76fd78c0.jpg
---

## Resolving Windows Update Error Code 0X80070643: A Step-by-Step Guide

### Quick Links

* [Is Downloading the Windows 10 KB5034441 Update Important?](https://unlock-android.techidaily.com/5-solutions-for-tecno-spark-10c-unlock-without-password-by-drfone-android/)
* [What is the WinRE Recovery Partition?](https://vp-tips.techidaily.com/mastering-subtitle-craft-with-the-best-online-resources-today/)
* [How to Fix the Windows Update Error 0x80070643](https://win11.techidaily.com/unlocking-dangers-hacked-fingerprints-on-windows-pcs/)

### Key Takeaways

* The Windows Recovery Environment (WinRE) is a tool that helps you restore your system to its factory settings in case of severe system corruption.
* If your Windows Recovery partition doesn't have at least 250 MB of free space, you'll encounter the error 0x80070643 when downloading the Windows 10 KB503441 update.
* To fix this issue, you'll need to resize the Recovery partition using the Command Prompt.

 Microsoft releases updates for Windows to add new features and fix bugs in the current version. Most updates download without problems, but some can cause errors during the download. One such error is Windows update error 0x80070643, which occurs while downloading the Windows 10 KB5034441 update.

##  Is Downloading the Windows 10 KB5034441 Update Important?

 Microsoft released the [KB5034441 update](https://support.microsoft.com/en-au/topic/kb5034441-windows-recovery-environment-update-for-windows-10-version-21h2-and-22h2-january-9-2024-62c04204-aaa5-4fee-a02a-2fdea17075a8) in January 2024\. If your computer uses Windows Recovery Environment (WinRE), this update automatically applies the Safe OS Dynamic Update to address a security vulnerability. If left unpatched, attackers could exploit this vulnerability to bypass [BitLocker encryption](https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/) through WinRE.

 That means there's no question about downloading the KB5034441 update for Windows 10—it's a crucial security fix, and it's important to install it. However, there is a catch.

 It turns out the error 0x80070643 occurs even on systems that lack a Recovery partition. The exact error is:

 There were some problems installing updates, but we’ll try again later. If you keep seeing this and want to search the web or contact support for information, this may help: (0x80070643).

![Windows Update Error 0x80070643](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/windows-update-error-0x80070643.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Microsoft clearly states that if your system doesn't have a Recovery partition, you don't need to download the KB5034441 update and you can ignore this error. However, if your system does feature a Recovery partition, it's important for you to download the update and, unfortunately, Microsoft isn't going to release an automatic fix that will solve the 0x80070643 error.

 Earlier, when the report broke about users facing this issue, Microsoft acknowledged it and said they were working on a fix. However, that hasn't panned out (yet). 

 They have [updated their blog](https://learn.microsoft.com/en-us/windows/release-health/resolved-issues-windows-10-22h2#3231msgdesc) that discusses the error to mention that "Automatic resolution of this issue won't be available in a future Windows update. Manual steps are necessary to complete the installation of this update on devices which are experiencing this error." This means the only way for you to get rid of the problem is to perform the manual fix released by Microsoft, which is resizing the partition.

##  What is the WinRE Recovery Partition?

 When you [open the Disk Management tool](https://extra-resources.techidaily.com/picture-posters-best-frame-enhancing-software-recommendations/) on your computer, you will see a Recovery partition section in the area where the drive with the operating system is listed. But what exactly is this Recovery partition?

![Recovery partition in Disk Management](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/recovery-partition-in-disk-management.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows Recovery Environment (WinRE) is a built-in feature provided by Windows that helps you recover your computer when it has been corrupted for various reasons, and you cannot boot it. Additionally, it will help recover your system when it has become unusable due to incorrect updates or accidental removal of system files.

 To check if the Recovery partition is configured properly on your computer, [open Command Prompt as an administrator](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/), type **reagentc /info**, and hit Enter. If you see "Enabled" next to Windows RE status, it means your computer has a Recovery partition, and it is working properly.

![Windows RE status in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/windows-re-status-in-command-prompt.jpg) 

 For you to install the KB5034441 update, there must be 250 MB of free space in the Recovery partition. If the partition has less than that, you will encounter the 0x80070643 error when downloading the update.

##  How to Fix the Windows Update Error 0x80070643

 As mentioned earlier, the 0x80070643 error occurs when the Recovery partition doesn't have 250 MB of free space. This means that to fix the problem, you will need to provide more space to the Recovery partition. To do that, open Command Prompt as an administrator, type **reagentc /disable** to disable the Recovery partition, and hit Enter.

![Disable Recovery Partition command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/disable-recovery-partition-command.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Type **diskpart** and hit Enter.

![Diskpart command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/diskpart-command-in-cmd.jpg) 

 Execute the **list disk** command to list all the disks.

![List disk command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-disk-command-in-cmd.jpg) 

 Select the disk where your operating system is installed. For example, if it is Disk 1, type **select disk 1** and hit Enter.

![Select disk command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-disk-command-in-cmd.jpg) 

 Type **list partition** to list the partitions on the disk.

![List partition command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-partition-command-in-cmd.jpg) 

 Select the primary disk partition. For example, if it is Partition 3, type **select partition 3** and hit Enter.

![Select partition 3 command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-partition-3-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll now have to shrink the partition. For that, type **shrink desired=250 minimum=250** and hit Enter.

![Shrink command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/shrink-command-in-cmd.jpg) 

 Now, select the Recovery partition. It will be labeled as "Recovery." For example, if it is Partition 4, type **select partition 4** and hit Enter.

![select partition 4 command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-partition-4-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Type **delete partition override** and hit Enter to delete the recovery partition.

![delete partition override command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/delete-partition-override-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Here's the most important step. Scroll up in your Command Prompt window and check the [disk partition style](https://facebook-video-footage.techidaily.com/updated-pro-level-gif-generation-a-critical-review/). If there's an asterisk (\*) in the GPT column of your operating system disk, it means you have GUID Partition Table (GPT) partition style. If there's no asterisk in the GPT column, then it's [MBR partition style](https://instagram-videos.techidaily.com/2024-approved-exclusive-guide-ranking-most-effective-ig-money-makers/).

![Asterick mark in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/asterick-mark-in-cmd.jpg) 

 If your disk is GPT, type **create partition primary id=de94bba4-06d1-4d40-a16a-bfd50179d6ac** and hit Enter. Then, type **gpt attributes =0x8000000000000001** and hit Enter. If your disk is MBR, type **create partition primary id=27** and hit Enter.

Close 

 Type **format** **quick fs=ntfs label="Windows RE tools"** and hit Enter. This will format the partition.

![Format command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/format-command-in-cmd.jpg) 

 Execute **list vol** to confirm that the recovery partition has been created.

![List vol command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-vol-command-in-cmd.jpg) 

 Type **exit** and hit Enter to exit Diskpart.

![Exit command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/exit-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Re-enable the Recovery partition by typing **reagentc /enable** and hitting Enter.

![Recovery parition enable command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/recovery-parition-enable-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Finally, to confirm the Recovery partition is configured properly on your computer, type **reagentc /info** and hit Enter. If you see "Enabled" next to Windows RE status, it means the Recovery partition is working properly. After that, [restart your computer](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) and try downloading the Windows update again. This time, the error code 0x80070643 shouldn't interrupt the download process.

---

 Windows updates and error codes are a never-ending story, and this definitely won't be the last time you encounter an error code interfering with the Windows update process. But, like any other problem in the world, Windows update errors have their own solutions. Hopefully, the above fix has helped you get rid of the Windows update error 0x80070643, and you're able to successfully download the KB5034441 security update from Microsoft.

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
<li><a href="https://discover-excellent.techidaily.com/1732515254580-b-54/"><u> [B = 54 </u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-effortless-audio-transfer-on-iphone-pick-top-6-tools-to-convert-youtube/"><u>[New] 2024 Approved Effortless Audio Transfer on iPhone Pick Top 6 Tools to Convert YouTube</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-mastering-ios-perfecting-podcast-playback/"><u>[New] 2024 Approved Mastering iOS Perfecting Podcast Playback</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-strategies-for-earnings-on-youtube-revealing-minimum-view-targets/"><u>[New] In 2024, Strategies for Earnings on YouTube Revealing Minimum View Targets</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-the-prime-monitor-companion-for-gaming-on-xbox-series-x/"><u>[Updated] 2024 Approved The Prime Monitor Companion for Gaming on Xbox Series X</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-imagemosaic-supreme-online-blend-and-designers-choice/"><u>[Updated] In 2024, ImageMosaic Supreme Online Blend & Designer's Choice</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-viewing-solution-projector-or-tv-for-top-4k-quality/"><u>[Updated] Optimal Viewing Solution Projector or TV for Top 4K Quality</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-beginners-guide-to-the-top-10-filmmaking-cameras/"><u>2024 Approved Beginner's Guide to the Top 10 Filmmaking Cameras</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-blending-bits-volume-manipulation-mastery-with-reaper/"><u>2024 Approved Blending Bits Volume Manipulation Mastery with Reaper</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-xs-max-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone XS Max Data Permanently | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-itel-s23-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Itel S23 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-realme-c51-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Realme C51</u></a></li>
<li><a href="https://techidaily.com/samsung-data-retrieval-tool-restore-lost-data-from-samsung-by-fonelab-android-recover-data/"><u>Samsung Data Retrieval tool – restore lost data from Samsung</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-motorola-by-fonelab-android-recover-music/"><u>Undelete lost music from Motorola</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-tecno-spark-20-pro-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Tecno Spark 20 Pro</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-u23-by-fonelab-android-recover-video/"><u>Undeleted lost videos from U23</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
</ul></div>

