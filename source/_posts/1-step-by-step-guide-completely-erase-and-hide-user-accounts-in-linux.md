---
title: "1. Step-by-Step Guide: Completely Erase and Hide User Accounts in Linux"
date: 2024-12-13T19:47:16.393Z
updated: 2024-12-15T21:37:06.053Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## 1. Step-by-Step Guide: Completely Erase and Hide User Accounts in Linux

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [User Accounts on Linux](https://tech-haven.techidaily.com/understanding-ai-prompt-injection-an-overview-of-the-technique-and-its-mechanisms/)
* [Why Delete an Account?](https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-realme-12plus-5g-tips-tricks-and-helpful-advice-by-drfone-android/)
* [Check the Login](https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-14-pro-by-drfone-ios/)
* [Reviewing The User's Processes](https://youtube-data.techidaily.com/ed-unlocking-collective-watch-strategies-for-multiple-channels-for-2024/)
* [Locking the Account](https://on-screen-recording.techidaily.com/2024-approved-joining-the-dots-obs-and-zoom-pairing-explained/)
* [Killing the Processes](https://unlock-android.techidaily.com/in-2024-how-to-reset-a-xiaomi-redmi-13c-phone-that-is-locked-by-drfone-android/)
* [Archiving the User's home Directory](https://unlock-android.techidaily.com/how-to-reset-a-locked-vivo-y100t-phone-by-drfone-android/)
* [Removing cron Jobs](https://screen-recording.techidaily.com/updated-in-2024-playcapture-pro-your-own-screen-recorder-free/)
* [Removing Print Jobs](https://some-skills.techidaily.com/2024-approved-the-complete-guide-to-shooting-with-a-green-screen/)
* [Deleting the User Account](https://extra-lessons.techidaily.com/volume-control-soft-fades-within-logic-pro-environment/)
* [It's a Wrap](https://techtrends.techidaily.com/master-the-internet-a-users-guide-on-enabling-browser-cookies/)

 Deleting a user on Linux involves more than you think. If you're a system administrator, you'll want to purge all traces of the account and its access from your systems. We'll show you the steps to take.

 If you just want to delete a user account from your system and aren't concerned about ending any running processes and other cleanup tasks, follow the steps in the "Deleting the User Account" section below. You'll need the `deluser` command on Debian-based distributions and the `userdel` command on other Linux distributions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  User Accounts on Linux

 Ever since the [first time-sharing systems appeared in the early 1960s](https://en.wikipedia.org/wiki/Compatible%5FTime-Sharing%5FSystem) and brought with them the capability for multiple users to work on a single computer, there's been a need to isolate and compartmentalize the files and data of each user from all the other users. And so user accounts—[and passwords—](https://en.wikipedia.org/wiki/Fernando%5FJ.%5FCorbat%C3%B3)were born.

 User accounts have an administrative overhead. They need to [be created](https://bypass-frp.techidaily.com/full-guide-to-bypass-itel-p55plus-frp-by-drfone-android/) when the user first needs access to the computer. They need to be removed when that access is no longer required. On Linux, there's a sequence of steps that should be followed in order to correctly and methodically remove the user, their files, and their account from the computer.

 If you're the system administrator that responsibility falls to you. Here's how to go about it.

##  Why Delete an Account?

 There's any number of reasons an account might need to be deleted. A staff member might be moving to a different team or leaving the company altogether. The account might have been set up for a short term collaboration with a visitor from another company. Team-ups are common in academia, where research projects can span departments, different universities, and even commercial entities. At the conclusion of the project, the system administrator has to perform the housekeeping and remove unnecessary accounts.

 The worst-case scenario is when someone leaves under a cloud because of a misdemeanor. Such events usually happen suddenly, with little fore-warning. That gives the system administrator very little time to plan, and an urgency to get the account locked, closed and deleted—with a copy of the user's files backed up in case they are needed for any post-closure forensics.

 In our scenario, we'll pretend that a user, Eric, has done something that warrants his immediate removal from the premises. At this moment he is unaware of this, he's still working, and logged in. As soon as you give the nod to security he's going to be escorted from the building.

 Everything's set. All eyes are on you.

##  Check the Login

 Let's see if he really is logged in and, if he is, how many sessions he's working with. The `who` command [will list active sessions](http://man7.org/linux/man-pages/man1/who.1.html).

who

![who in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/1-2.png) 

 Eric is logged in once. Let's see what processes he's running.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Reviewing The User's Processes

 We can use the `ps` command to [list the processes this user is running](http://man7.org/linux/man-pages/man1/ps.1.html). The `-u` (user) option lets us tell `ps` to restrict its output to the processes running under the ownership of that user account.

ps -u eric

![ps -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/2-2.png) 

 We can see the same processes with more information using the `top` command. `top` also has an `-U` (user) option to restrict the output to the processes owned by a single user. Note that this time it is an uppercase "U."

top -U eric

![top -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/3-3.png) 

 We can see the memory and CPU usage of each task, and can quickly look for anything with suspicious activity. We're about to forcibly kill all of his processes, so it is safest to take a moment to quickly review the processes, and check and make sure that other users are not going to be inconvenienced when you terminate user account `eric`'s processes.

![Output from top -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/4-2.png) 

 It doesn't look like he's doing much, just using `less` to view a file. We're safe to proceed. But before we kill his processes, we'll freeze the account by locking the password.

##  Locking the Account

 We'll lock the account before we kill the processes because when we kill the processes it will log out the user. If we've already changed his password, he won't be able to log back in.

 The encrypted user passwords are stored in the `/etc/shadow` file. You wouldn't normally bother with these next steps, but so that you can see what happens in the `/etc/shadow ` file when you lock the account we'll take a slight detour. We can use the following command to look at the first two fields of the entry for the `eric` user account.

sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow

![sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/20-1.png) 

 The awk command [parses fields from text files](http://man7.org/linux/man-pages/man1/awk.1p.html) and optionally manipulates them. We're using the `-F` (field separator) option to tell `awk` that the file uses a colon " `:` " to separate the fields. We're going to search for a line with the pattern "eric" in it. For matching lines, we'll print the first and second fields. These are the account name and the encrypted password.

 The entry for user account eric is printed for us.

 To lock the account we use the `passwd` command. We'll use the `-l` (lock) option and [pass in the name of the user account to lock](http://man7.org/linux/man-pages/man1/passwd.1.html).

sudo passwd -l eric

![sudo passwd -l eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/18.png) 

 If we check the `/etc/passwd` file again, we'll see what's happened.

sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow

![sudo awk -F: '/eric/ {print $1,$2}' /etc/shadow in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/21-1.png) 

 An exclamation mark has been added to the start of the encrypted password. It doesn't overwrite the first character, it's just added to the start of the password. That's all that's required to prevent a user from being able to log in to that account.

 Now that we've prevented the user from logging back in, we can kill his processes and log him out.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Killing the Processes

 There are different ways to [kill a user's processes](https://pokemon-go-android.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-honor-magic-v2-drfone-by-drfone-virtual-android/), but the command shown here is widely available and is a more modern implementation than some of the alternatives. The `pkill` command will find and kill processes. We're passing in the KILL signal, and using the `-u` (user) option.

sudo pkill -KILL -u eric

![sudo pkill -KILL -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/6-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You're returned to the command prompt in a decidedly anti-climactic fashion. To make sure something happened let's check `who` again:

who

![who in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/7-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 His session is gone. He's been logged off and his processes have been stopped. That's taken some of the urgency out of the situation. Now we can relax a bit and carry on with the rest of the mopping up as security takes a walk over to Eric's desk.

Related: [How to Add and Remove Users on Ubuntu](https://fox-links.techidaily.com/updated-gif-magic-transformations-without-extra-files-downloaded-for-2024/) 

##  Archiving the User's home Directory

 It's not out of the question that in a scenario such as this, access to the user's files will be required in the future. Either as part of an investigation or simply because their replacement may need to refer back to their predecessor's work. We'll use the `tar` command [to archive their entire home directory](http://man7.org/linux/man-pages/man1/tar.1.html).

 The options we're using are:

* **c**: Create an archive file.
* **f**: Use the specified filename for the name of the archive.
* **j**: Use bzip2 compression.
* **v**: Provide verbose output as the archive is created.

sudo tar cfjv eric-20200820.tar.bz /home/eric

![sudo tar cfjv eric-20200820.tar.bz /home/eric  in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/8-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A lot of screen output will scroll in the terminal window. To check the archive has been created, use the `ls` command. We're using the `-l` (long format) and `-h` (human-readable) options.

ls -lh eric-20200802.tar.bz

![sudo tar cfjv eric-20200820.tar.bz /home/eric  in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/9-1.png) 

 A file of 722 MB has been created. This can be copied somewhere safe for later review.

##  Removing cron Jobs

 We'd better check in case there are any `cron` jobs scheduled for user account `eric`. A `cron` job is a command that is triggered at specified times or intervals. We can check if there are any `cron` jobs scheduled for this user account by using `ls`:

sudo ls -lh /var/spool/cron/crontabs/eric

![sudo ls -lh /var/spool/cron/crontabs/eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/10-1.png) 

 If anything exists in this location it means there are `cron` jobs queued for that user account. We can delete them with this `crontab` command. The `-r` (remove) option will remove the jobs, and the `-u` (user) option tells `crontab` [whose jobs to remove](http://man7.org/linux/man-pages/man1/crontab.1.html).

sudo crontab -r -u eric

![sudo crontab -r -u eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/11-2.png) 

 The jobs are silently deleted. For all we know, if Eric had suspected he was about to be evicted he might have scheduled a malicious job. This step is best practice.

##  Removing Print Jobs

 Perhaps the user had pending print jobs? Just to be sure, we can purge the print queue of any jobs belonging to user account `eric`. The `lprm` command [removes jobs from the print queue](http://man7.org/linux/man-pages/man1/lprm.1.html). The `-U` (username) option lets you remove jobs owned by the named user account:

lprm -U eric

![lprm -U eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/12-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The jobs are removed and you are returned to the command line.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Deleting the User Account

 We've already backed up the files from the `/home/eric/` directory, so we can go ahead and delete the user account and delete the `/home/eric/` directory at the same time.

 The command to use depends on which distribution of Linux you're using. For [Debian based Linux distributions](https://manpages.ubuntu.com/manpages/noble/en/man8/deluser.8.html), the command is `deluser`, and [for the rest of the Linux world](http://man7.org/linux/man-pages/man8/userdel.8.html), it is `userdel`.

 Actually, on Ubuntu both commands are available. I half-expected one to be an alias of the other, but they are distinct binaries.

type deluser

type userdel

![type deluser in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/22-1.png) 

 Although they're both available, the recommendation is to use `deluser` [on Debian-derived distributions](http://manpages.ubuntu.com/manpages/eoan/man8/userdel.8.html):

 "`userdel` is a low level utility for removing users. On Debian, administrators should usually use `deluser`(8) instead."

 That's clear enough, so the command to use on this Ubuntu computer is `deluser`. Because we also want their home directory to be removed we're using the `--remove-home` flag:

sudo deluser --remove-home eric

![sudo deluser --remove-home eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/14-2.png) 

 The command to use for non-Debian distributions is `userdel`, with the `--remove` flag:

sudo userdel --remove eric

 All traces of user account `eric` have been erased. We can check that the ` /home/eric/`directory has been removed:

ls /home

![ls /home in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/15-1.png) 

 The `eric` group has also been removed because the user account `eric` was the only entry in it. We can check this quite easily by piping the contents of `/etc/group` through `grep`:

sudo less /etc/group | grep eric

![sudo less /etc/group | grep eric in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/02/16-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  It's a Wrap

 Eric, for his sins, is gone. Security is still walking him out of the building and you've already secured and archived his files, deleted his account, and purged the system of any remnants.

 Accuracy always trumps speed. Make sure you consider each step before you take it. You don't want someone walking up to your desk and saying "No, the other Eric."

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
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-instantaneous-viewership-metering/"><u>[Updated] 2024 Approved Instantaneous Viewership Metering</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-professionalscreenx-insiders-take-on-software/"><u>[Updated] In 2024, ProfessionalScreenX Insider’s Take on Software</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/combine-the-fractions-on-the-left-side-since-they-have-the-same-denominator/"><u>Combine the Fractions on the Left Side Since They Have the Same Denominator:</u></a></li>
<li><a href="https://facebook.techidaily.com/1719153450268-cryptocurrency-and-sheep-zuckerbergs-surprising-pet-name/"><u>Cryptocurrency and Sheep? Zuckerberg’s Surprising Pet Name</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-smart-8-bootloader-easily-by-drfone-android/"><u>How to Unlock Infinix Smart 8 Bootloader Easily</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-11-pro-max-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 11 Pro Max Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-collection-of-10-inspirational-movies/"><u>In 2024, The Ultimate Collection of 10 Inspirational Movies</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-art-of-picture-sharing-with-carver-photo-displays/"><u>The Art of Picture Sharing with Carver Photo Displays</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-samsung-galaxy-m54-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-infinix-note-30-vip-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Infinix Note 30 VIP</u></a></li>
<li><a href="https://extra-resources.techidaily.com/thrill-in-the-cold-olympic-showcase-snowboarders-at-peak-performance/"><u>Thrill in the Cold Olympic Showcase - Snowboarders at Peak Performance</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-itel-a60-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Itel A60</u></a></li>
</ul></div>

