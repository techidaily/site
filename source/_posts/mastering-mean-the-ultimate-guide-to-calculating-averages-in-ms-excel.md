---
title: "Mastering Mean: The Ultimate Guide to Calculating Averages in MS Excel"
date: 2024-09-01T02:17:57.868Z
updated: 2024-09-02T02:17:57.868Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d046e3f1a50f3eab0c2328a8c65f9cdfeb961e04c1487439cf5694d3a9ccaf02.jpg
---

## Mastering Mean: The Ultimate Guide to Calculating Averages in MS Excel

### Quick Links

* [How Many Average Functions Are There in Excel?](https://instagram-video-files.techidaily.com/updated-in-2024-rapid-route-learning-the-ins-and-outs-of-insta-talks/)
* [How to Use AVERAGE in Excel](https://data-safeguard.techidaily.com/photoshop-cs8-installation-tutorial-for-windows-users-start-editing/)
* [How to Use AVERAGEA in Excel](https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-huawei-p60-drfone-by-drfone-virtual-android/)
* [How to Use AVERAGEIF in Excel](https://program-issues.techidaily.com/solving-the-mystery-a-step-by-step-guide-to-resolve-dev-error-6034-on-pc-and-xbox/)
* [How to Use AVERAGEIFS in Excel](https://extra-hints.techidaily.com/slowly-quieting-tracks-with-fl-studio/)

 Excel has hundreds of functions that can help you to quickly and accurately perform calculations, among which are the AVERAGE functions. You might want to calculate the average sales figures, get the average of a group of data that contains numbers and text, or work out the average of all student scores over a certain number.

##  How Many Average Functions Are There in Excel?

 There are four AVERAGE functions and each has different uses:

* **AVERAGE**: This produces the arithmetic mean (the sum of all numbers divided by the number of values) of a set of data, ignoring anything that isn't a number.
* **AVERAGEA**: This returns the mean of a set of numbers, text, and logical arguments.
* **AVERAGEIF**: This calculates the arithmetic mean of a set of numerical data that fulfill a single criterion.
* **AVERAGEIFS**: This tells you the arithmetic mean of a set of numerical data that fulfill several criteria.

 Let's explore these in more detail.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use AVERAGE in Excel

 To calculate the average in Excel, use the following syntax:

=AVERAGE(A,B)

 where A is the first number, cell reference, or range, and B is up to a maximum of 255 additional numbers, cell references, or ranges to include in the average calculation.

 In this example, we have a set of seven students and want to calculate their average exam score.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores will be calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-uncalculated.png) 

 As you can see, Student C scored 0 and Student F has yet to take the exam. As a result, we want Excel to work out the scores of those who have taken the exam (all students except for Student F).

 To do this, we would type the following formula into cell D2:

=AVERAGE(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores has been calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-calculated-1.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The AVERAGE function includes 0 within its calculations, but ignores all empty cells, text, and logical values (TRUE or FALSE). So, we can be confident that this calculation will include Student C's score, but ignore Student F's score.

 If any of the values being used in the AVERAGE calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would not work.

 To save time, you can instead calculate the average through a few simple clicks. First, select your data to average, click the "Home" tab on the ribbon, and in the "Editing" group, click on the drop-down arrow next to the sigma (Σ) symbol. From there, click "Average". The result will appear at the end of your data.

##  How to Use AVERAGEA in Excel

 AVERAGEA works in a very similar way to AVERAGE, but includes more than just numbers within the calculation. Here's the syntax for this function:

=AVERAGE(A,B)

 where A is the first value (including numbers, logical values such as TRUE or FALSE, and text), and B is up to a maximum of 255 additional values to include in the average calculation.

 The AVERAGEA function is useful if you have a mixed set of data containing numbers, logical values, and text, and you want to include them all within your calculation.

 Taking the same set of data that we used in the example above, we now want to work out the average using AVERAGEA.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and a space where their average scores will be calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-uncalculated.png) 

 In cell D5, we would type the following formula:

=AVERAGEA(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and their average scores, calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-calculated.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 Unlike the AVERAGE function, which ignores logical values, the AVERAGEA calculation includes FALSE within the calculation as 0\. If this were instead TRUE, this would be counted as 1\. As a result, in our example, Student C's score of 0 is included, and Student F is also calculated as having scored 0\. This is why the result is lower for this calculation than the previous one.

 AVERAGEA counts any other text as 0 (for example, if you type FOUR, this is still represented as 0, and not 4), and ignores empty cells.

 As with AVERAGE, if any of the values being used in the AVERAGEA calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would return an error.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
##  How to Use AVERAGEIF in Excel

 AVERAGEIF effectively performs two calculations in one go, first identifying data that meet a certain criterion before then finding the average of these data. AVERAGEIF uses the following syntax:

=AVERAGEIF(A,B,C)

 where A is the range of values or cells to include in the average, B is the criterion, and C (optional) is the actual set of cells to average. Confusing? Let's look at this example.

 We want to work out two things from this table. First, we want to find the average score of all students who scored more than 10 in the exam, and second, we want to work out the average scores of all students over 12 years of age.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table are cells where the AVERAGEIF functions will be tested.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-uncalculated.png) 

 To work out the average score of all students who scored more than 10, we would use the following formula:

=AVERAGEIF(B2:B8,">10")

 Notice two things in this formula. First, the criteria must always be enclosed in double quotes. Second, we've only included two arguments within the parentheses, as there's no need to refer to any other data elsewhere within our calculation.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, the first AVERAGEIF calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-1.png) 

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This has correctly picked up the scores of Students A, B, D, and E, as these are all more than 10.

 To work out the average scores of all students over 12 years of age, we would use the following formula:

=AVERAGEIF(C2:C8,">12",B2:B8)

 Notice the difference between the two formulas. Where the previous calculation contained two arguments, this one contains three, as we are assessing two sets of data.

 The "C2:C8" part of the formula tells Excel to look in that range (the students' ages) for the criteria, the ">12" part tells Excel to identify any values over 12 in the C2:C8 range (the students' ages), and "B2:B8" (the students' scores) is the part being averaged.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, both AVERAGEIF calculations have been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-2-1.png) 

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This has correctly picked up the scores of Students A, B, D, and E, as they are all over 12 years of age. The calculation also ignores logical values, which is why it hasn't considered Student F, even though they are over 12 years old.

 The criteria used in AVERAGEIF can use one of Excel's six logical operators—these are > (greater than), < (less than), = (equal to), <= (less than or equal to), >= (greater than or equal to), or <> (not equal to)—and wildcards (\* and ?). If you want to include an actual question mark or asterisk, add a tilde (\~) before the character.

##  How to Use AVERAGEIFS in Excel

 The AVERAGEIFs function allows you to include several criteria to assess before calculating the average. It works using the following syntax:

=AVERAGEIFS(A,B,C)

 where A identifies the cells to average, B is the cells used to identify the criteria, and C is the criteria. There can be up to 127 criteria, so multiple pairs of cells (B) and criteria (C) can be used.

 Take this example, where we want to work out the exam scores of students in Green House over the age of 10.

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where AVERAGEIFS will be performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-uncalculated.png) 

 To do this, we would use the following formula:

=AVERAGEIFS(B2:B8,C2:C8,"Green",D2:D8,">10")

 "B2:B8" contains the data to be averaged (the students' scores), "C2:C8" is the first range to be tested with the criterion of "Green" (the student's house), and "D2:D18" is the second range to be tested with the criterion of ">10" (the student's age).

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where an AVERAGEIFS calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-calculated-1.png) 

 This has correctly averaged the scores of Students D and G, as they are both in Green House and are over 10 years old.

 Other things to note about AVERAGEIFS:

* TRUE is counted as 1, and FALSE is counted as 0.
* In the criteria, you can use a question mark (?) as a wildcard to match any single character, or an asterisk (\*) as a wildcard to match any sequence of characters. Use a tilde (\~) before the character if you're looking to identify an actual question mark or asterisk.

---

 As well as using AVERAGEIF and AVERAGEIFS, you can [sort and filter data in Excel](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) to only show certain figures within your tables.

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-discovering-the-magic-behind-youtube-shorts/"><u>[New] 2024 Approved  Discovering the Magic Behind Youtube Shorts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-routines-for-easy-webinar-saves-on-windows-platform/"><u>[New] Essential Routines for Easy Webinar Saves on Windows Platform</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-mastering-canva-imagery-top-10-pro-level-techniques/"><u>[New] Mastering Canva Imagery  Top 10 Pro-Level Techniques</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-filmmakers-toolkit-essential-color-grading-of-7-techniques-for-2024/"><u>[New] The Filmmaker's Toolkit  Essential Color Grading of 7 Techniques for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-navigating-through-powerpoints-automatic-text-conversion-features/"><u>[Updated] 2024 Approved  Navigating Through PowerPoint's Automatic Text Conversion Features</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-mastering-igtv-title-and-description-revision/"><u>[Updated] In 2024, Mastering IGTV Title & Description Revision</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unraveling-video-platform-distinctions-a-youtube-vs-dailymention-analysis/"><u>[Updated] Unraveling Video Platform Distinctions  A YouTube Vs. DailyMention Analysis</u></a></li>
<li><a href="https://techidaily.com/0x800705b3-error-code-when-tried-to-update-on-windows-10-solved/"><u>0X800705B3 Error Code When Tried to Update on Windows 10 [Solved]</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-tecno-spark-10-pro-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Tecno Spark 10 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/a-sweet-symphony-blending-ingredients-correctly/"><u>A Sweet Symphony: Blending Ingredients Correctly</u></a></li>
<li><a href="https://techidaily.com/achieve-smooth-gameplay-on-roblox-advanced-tips-and-tricks-for-optimal-fps-upgrades/"><u>Achieve Smooth Gameplay on Roblox: Advanced Tips and Tricks for Optimal FPS Upgrades</u></a></li>
<li><a href="https://techidaily.com/bust-the-glitch-essential-troubleshooting-tips-for-pc-players-of-goose-goose-duck/"><u>Bust the Glitch: Essential Troubleshooting Tips for PC Players of Goose Goose Duck</u></a></li>
<li><a href="https://techidaily.com/1723808021228-common-logitech-mouse-malfunctions-on-windows-11-pcs-heres-how-to-get-them-working-again/"><u>Common Logitech Mouse Malfunctions on Windows 11 PCs? Here's How to Get Them Working Again!</u></a></li>
<li><a href="https://techidaily.com/comprehensive-solution-for-windows-security-correcting-errsslversionorciphermismatch/"><u>Comprehensive Solution for Windows Security: Correcting Err_SSL_Version_or_Cipher_Mismatch</u></a></li>
<li><a href="https://techidaily.com/connecting-additional-displays-to-your-laptop-a-comprehensive-walkthrough/"><u>Connecting Additional Displays to Your Laptop – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://techidaily.com/diy-how-to-install-and-use-bluetooth-on-a-desktop-or-laptop/"><u>DIY: How to Install and Use Bluetooth on a Desktop or Laptop</u></a></li>
<li><a href="https://techidaily.com/easy-tutorial-on-setting-up-your-laptops-connection-to-wi-fi/"><u>Easy Tutorial on Setting Up Your Laptop's Connection to Wi-Fi</u></a></li>
<li><a href="https://techidaily.com/effective-techniques-to-remove-malware-from-windows-11-a-guide-with-four-approaches/"><u>Effective Techniques to Remove Malware From Windows 11: A Guide with Four Approaches</u></a></li>
<li><a href="https://techidaily.com/effortless-guide-set-google-as-your-default-browser-home-page/"><u>Effortless Guide: Set Google as Your Default Browser Home Page</u></a></li>
<li><a href="https://techidaily.com/effortless-methods-to-refresh-icon-cache-on-windows-7-8-and-vista/"><u>Effortless Methods to Refresh Icon Cache on Windows 7, 8 & Vista</u></a></li>
<li><a href="https://techidaily.com/effortless-tutorial-update-your-computers-linguistic-settings-in-windows-10/"><u>Effortless Tutorial: Update Your Computer's Linguistic Settings in Windows 10</u></a></li>
<li><a href="https://techidaily.com/elevate-your-gameplay-discover-the-best-techniques-for-enhancing-pubgs-performance-and-speed-7-insights-inside/"><u>Elevate Your Gameplay: Discover the Best Techniques for Enhancing PUBG's Performance and Speed [#7 Insights Inside]</u></a></li>
<li><a href="https://techidaily.com/fix-guide-dealing-with-a-required-cddvd-drive-device-driver-is-absent-problem-on-your-pc/"><u>Fix Guide: Dealing with 'A Required CD/DVD Drive Device Driver Is Absent' Problem on Your PC</u></a></li>
<li><a href="https://techidaily.com/fix-how-to-resolve-your-external-hard-drive-missing-on-windows-10-pc/"><u>Fix: How to Resolve Your External Hard Drive Missing on Windows 10 PC</u></a></li>
<li><a href="https://techidaily.com/fixing-your-beyond-light-gameplay-issues-enhance-frame-rate-now/"><u>Fixing Your 'Beyond Light' Gameplay Issues - Enhance Frame Rate Now</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-football-live-learn-and-cut-your-match-footage-for-2024/"><u>Free Football  Live-Learn & Cut Your Match Footage for 2024</u></a></li>
<li><a href="https://techidaily.com/guaranteed-fixes-for-slow-down-and-stop-mouse-speed-changes/"><u>Guaranteed Fixes for Slow Down and Stop Mouse Speed Changes</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808221412-how-to-block-calls-on-iphone-and-android-phone-quickly-and-easily/"><u>How to Block Calls on iPhone & Android Phone | Quickly & Easily</u></a></li>
<li><a href="https://techidaily.com/how-to-clean-up-and-delete-hiberfilsys-in-windows-tenth-for-optimal-performance/"><u>How to Clean Up and Delete Hiberfil.sys in Windows Tenth for Optimal Performance</u></a></li>
<li><a href="https://techidaily.com/how-to-enable-compatibility-mode-for-legacy-software-on-windows-11/"><u>How to Enable Compatibility Mode for Legacy Software on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-a-thorough-system-restore-on-windows-10-using-only-4-main-steps/"><u>How to Perform a Thorough System Restore on Windows 10 Using Only 4 Main Steps</u></a></li>
<li><a href="https://techidaily.com/1723808212332-how-to-play-fortnite-on-pc-easy-guide-for-beginners/"><u>How to Play Fortnite on PC - Easy Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-spotlight-wallpaper-icon-from-windows-11s-desktop/"><u>How to Remove the Spotlight Wallpaper Icon From Windows 11’S Desktop</u></a></li>
<li><a href="https://techidaily.com/how-to-update-windows-10/"><u>How to Update Windows 10</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-xiaomi-civi-3-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Xiaomi Civi 3 to Another | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/lost-gmail-password-recover-it-with-these-2022-verification-tips/"><u>Lost Gmail Password? Recover It with These 2022 Verification Tips</u></a></li>
<li><a href="https://techidaily.com/mastering-control-over-your-pc-preventing-unwanted-windows-10-updates-forever/"><u>Mastering Control Over Your PC: Preventing Unwanted Windows 10 Updates Forever</u></a></li>
<li><a href="https://techidaily.com/navigate-with-confidence-and-cut-costs-take-advantage-of-our-official-2n04-driver-easy-promo-offer-save-20-today/"><u>Navigate with Confidence & Cut Costs: Take Advantage of Our Official 2N04 Driver Easy Promo Offer - Save 20%% Today</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-vivo-v30-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Vivo V30 and Browser | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/silent-blades-and-righteous-honor-your-next-game-adventure-awaits-in-2024/"><u>Silent Blades & Righteous Honor  Your Next Game Adventure Awaits, In 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/simple-techniques-for-downloading-youtube-content/"><u>Simple Techniques for Downloading YouTube Content</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-windows-11-movie-file-saving-for-2024/"><u>Step-by-Step  Windows 11 Movie File Saving for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-realme-c55-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Realme C55 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/1723808313778-troubleshooting-pc-starts-without-screen-output-solved/"><u>Troubleshooting: PC Starts without Screen Output – Solved!</u></a></li>
<li><a href="https://techidaily.com/update-usb-drivers-in-windows-11-7-8-and-81-easily/"><u>Update USB Drivers in Windows 11, 7, 8 & 8.1. Easily</u></a></li>
<li><a href="https://techidaily.com/vitalik-buterins-proposal-of-ethereum-as-a-decentralized-platform/"><u>Vitalik Buterin's Proposal of Ethereum as a Decentralized Platform</u></a></li>
</ul></div>
