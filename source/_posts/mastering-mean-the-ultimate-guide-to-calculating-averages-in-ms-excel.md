---
title: "Mastering Mean: The Ultimate Guide to Calculating Averages in MS Excel"
date: 2024-12-18T17:01:45.539Z
updated: 2024-12-24T20:01:04.067Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In cell D5, we would type the following formula:

=AVERAGEA(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and their average scores, calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-calculated.png) 

 Unlike the AVERAGE function, which ignores logical values, the AVERAGEA calculation includes FALSE within the calculation as 0\. If this were instead TRUE, this would be counted as 1\. As a result, in our example, Student C's score of 0 is included, and Student F is also calculated as having scored 0\. This is why the result is lower for this calculation than the previous one.

 AVERAGEA counts any other text as 0 (for example, if you type FOUR, this is still represented as 0, and not 4), and ignores empty cells.

 As with AVERAGE, if any of the values being used in the AVERAGEA calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would return an error.

##  How to Use AVERAGEIF in Excel

 AVERAGEIF effectively performs two calculations in one go, first identifying data that meet a certain criterion before then finding the average of these data. AVERAGEIF uses the following syntax:

=AVERAGEIF(A,B,C)

 where A is the range of values or cells to include in the average, B is the criterion, and C (optional) is the actual set of cells to average. Confusing? Let's look at this example.

 We want to work out two things from this table. First, we want to find the average score of all students who scored more than 10 in the exam, and second, we want to work out the average scores of all students over 12 years of age.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table are cells where the AVERAGEIF functions will be tested.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-uncalculated.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To work out the average score of all students who scored more than 10, we would use the following formula:

=AVERAGEIF(B2:B8,">10")

 Notice two things in this formula. First, the criteria must always be enclosed in double quotes. Second, we've only included two arguments within the parentheses, as there's no need to refer to any other data elsewhere within our calculation.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, the first AVERAGEIF calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as these are all more than 10.

 To work out the average scores of all students over 12 years of age, we would use the following formula:

=AVERAGEIF(C2:C8,">12",B2:B8)

 Notice the difference between the two formulas. Where the previous calculation contained two arguments, this one contains three, as we are assessing two sets of data.

 The "C2:C8" part of the formula tells Excel to look in that range (the students' ages) for the criteria, the ">12" part tells Excel to identify any values over 12 in the C2:C8 range (the students' ages), and "B2:B8" (the students' scores) is the part being averaged.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, both AVERAGEIF calculations have been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-2-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This has correctly picked up the scores of Students A, B, D, and E, as they are all over 12 years of age. The calculation also ignores logical values, which is why it hasn't considered Student F, even though they are over 12 years old.

 The criteria used in AVERAGEIF can use one of Excel's six logical operators—these are > (greater than), < (less than), = (equal to), <= (less than or equal to), >= (greater than or equal to), or <> (not equal to)—and wildcards (\* and ?). If you want to include an actual question mark or asterisk, add a tilde (\~) before the character.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-action-cameras-clash-gopro-vs-sony-in-film-quality-debate/"><u>[New] Action Cameras Clash GoPro Vs. Sony in Film Quality Debate</u></a></li>
<li><a href="https://youtube-web.techidaily.com/astering-privacy-in-media-cutting-out-unwanted-visibility/"><u>[New] Mastering Privacy in Media Cutting Out Unwanted Visibility</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-dish-to-screen-your-recipe-video-blueprint-for-2024/"><u>[Updated] Dish to Screen Your Recipe Video Blueprint for 2024</u></a></li>
<li><a href="https://techidaily.com/factory-reset-apple-iphone-12-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/gaming-smoothly-on-pc-with-aliens-fireteam-elite-how-to-stop-the-crashes/"><u>Gaming Smoothly on PC with Aliens: Fireteam Elite - How to Stop the Crashes</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-lava-yuva-3-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Lava Yuva 3 Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-20-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark 20 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-realme-gt-5-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Realme GT 5 phone? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-nokia-c02-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Nokia C02 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1429457-9781608827503-mindfulness-for-prolonged-grief/"><u>Mindfulness for Prolonged Grief | Free Book</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-sony-xperia-1-v-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Sony Xperia 1 V to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/stellar-data-recovery-for-iphone-6-failed-to-recognize-my-iphone-how-to-fix-it-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Stellar Data Recovery for iPhone 6 failed to recognize my iPhone. How to fix it? | Stellar</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-ultimate-guide-to-your-unique-tiktok-hash-code/"><u>The Ultimate Guide to Your Unique TikTok Hash Code</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-realme-11x-5g-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Realme 11X 5G fingerprint</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-htc-u23-pro-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of HTC U23 Pro on Windows?</u></a></li>
</ul></div>

