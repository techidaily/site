---
title: "The Essential Tutorial: Convert Strings with Base64 in the Linux Environment"
date: 2024-11-24T17:40:06.713Z
updated: 2024-12-02T02:17:45.349Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f5b8e36c4ebd6a9ca109693d88c7c440e68928a27daf3516cb90c9a543d54e11.jpeg
---

## The Essential Tutorial: Convert Strings with Base64 in the Linux Environment

Want to learn how to encode and decode strings using the base64 binary-to-text scheme? This tutorial will show you two methods to encode and decode a string on Linux using the base64 command and the Python programming language.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Where Is base64 Used?

 base64 is widely used in different domains. Some of the most common areas include email attachments, web development, networking, and URL encoding.

 Some email systems use base64 to encode binary data such as images and documents into text format so that these can be safely transmitted with the message. Web developers also use base64 to embed images into HTML and CSS to reduce the number of HTTP requests and improve page load speed.

 Another common use of base64 encoding is in authentication tokens. Usernames and passwords are sometimes masked using this encoding scheme and added to HTTP headers or URL parameters. In networking, base64 is used in protocols that use text-based communication, such as HTTP and SMTP, for transmitting data without corruption.

 What you should know is that base64 is only an encoding scheme. The encoded data can be easily decoded to get the original data back. You should never use it if you need to [encrypt data instead](https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-g54-5g-drfone-by-drfone-virtual-android/).

##  Encoding a String Using the base64 Command

 The most basic way to encode a string using base64 is to output it to the terminal using [the echo command](https://facebook.techidaily.com/cut-out-controversy-refresh-your-feed-focus/). The trick is to [pipe the output](https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) of the echo command to base64, like this:

echo 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-9.png) 

 Because of the default behavior of the echo command, there's a trailing newline character at the end of the string. If you'd like to omit that and only use the string, run:

echo -n 'I love Linux' | base64

![The Linux terminal displaying the process of encoding a string using base64 omitting the newline character](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-10.png) 

 As you can notice, the output is different from the previous one. You can also do this using the printf command which doesn't automatically append a newline character to the string. The format is given below:

printf 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string received from the printf command using base64](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-8.png) 

 This output is the same as the previous one because there are no newline characters this time. If you're familiar with [here-strings](https://tldp.org/LDP/abs/html/x17837.html) on Linux, you can also use them to send your string output to the base64 command like this:

base64 <<< 'I love Linux'

![The Linux terminal showcases how to encode a string using the base64 command with the help of here string operator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-9.png) 

 Similar to the echo command, here-strings also add a newline character at the end of the string.

##  Encoding Files Using the base64 Command

 To encode a file using base64, you can pass the file directly as an option to the base64 command.

 To test it out, [create a new file](https://youtube-sure.techidaily.com/ed-2024-approved-effortless-subtitling-and-cc-addition-techniques-for-youtube-users/) and [append some text to it](https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-8-by-drfone-ios/). If you already have a text file, then use that. I've created a file called base.txt. To encode the file's content to base64, run:

base64 base.txt

![The Linux terminal displaying the process of encoding a file to base64 using the base64 command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-7.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Remember to replace base.txt with your file name. The above command only displays the output in the terminal. It doesn't save the encoded string anywhere. However, you can easily do that by redirecting the output to a new file. I've created another file called output.txt. This time I'll save the output to that empty file. Here's the command for that:

base64 base.txt > output.txt

![The Linux terminal showcasing the process of encoding the content of a file to base64 and saving it to another file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-7.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As you can see, the terminal didn't display the output. This command saved it to another file instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Decoding a base64 String Using the base64 Command

 For decoding a base64 string and turning it into a regular string, you'll need to use the "-d" flag with the base64 command. Let's see a demonstration using the echo command.

echo 'SG93VG9HZWVrCg==' | base64 -d

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of the echo command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-8.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you'd like to use here-strings for decoding a base64 string, then use:

base64 -d <<< SG93VG9HZWVrCg==

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of here-strings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-7.png) 

 Sometimes, there might be non-alphanumeric characters in a string. You can ignore those while decoding the string by using the "-i" option.

##  Using Python to Encode and Decode a base64 String

 If you're a Python programmer or are more familiar with the [Python programming language](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/) than Bash, then this method will be more suitable for you. Python has a base64 module that you can use for encoding and decoding strings. You can either use the python3 terminal command or write a full program. I'll show you both ways.

 The python3 command has a "-m" or module flag. You can use this flag to invoke the base64 module. Then you can pass your string with the help of the echo command or here-strings. Here's the full command:

echo 'I love Linux' | python3 -m base64 # Using the echo commandpython3 -m base64 <<< 'I love Linux' # Using here-strings

![The Linux terminal displays the process of encoding a string to base64 using Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-4.png) 

 To decode a base64 string, all you need to do is use the "-d" flag as seen previously with the base64 command. The syntax is below:

echo 'SSBsb3ZlIExpbnV4Cg==' | python3 -m base64 -d # Using the echo command​​​​​​python3 -m base64 -d <<< 'SSBsb3ZlIExpbnV4Cg==' # Using here-strings

![The Linux terminal showing the process of decoding a base64 string using the Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-5.png) 

 Of course, the convenient way is to create a Python program that can handle the encoding and decoding by taking user input. First, let's create a program that will encode a string. Here's the encoding code:

        `import base64  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get input string from the user  
input_string = input("Enter the string to encode: ")  

## Encode the string using base64  
encoded_string = base64.b64encode(input_string.encode('utf-8'))  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Decode the encoded string to ensure it's correct (optional)  
decoded_string = base64.b64decode(encoded_string).decode('utf-8')  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Print the encoded and decoded strings  
print("Encoded string:", encoded_string.decode('utf-8'))  
print("Decoded string (verification):", decoded_string)  
`
    
 Save the file with a suitable name and a ".py" extension. I'm saving it by the name base64\_encoder.py. Once done, run the program with:

python3 base64_encoder.py

![The Linux terminal showcasing the process of encoding a string using a Python program](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/11-3.png) 

 You can also create a program to decode a base64 string. Here's a code snippet you can use:

        `import base64  

## Get input base64 string from the user  
encoded_string = input("Enter the Base64 string to decode: ")  
try:  
   # Decode the string using base64.b64decode()  
   decoded_string = base64.b64decode(encoded_string).decode('utf-8')  
   print("Decoded string:", decoded_string)  
except Exception as e:  
   print(f"Error decoding string: {e}")  
`
    
 Save the file and run the program in the same way.

python3 base64_decoder.py

![The Linux terminal displaying the process of decoding a base64 string using a Python program](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12-4.png) 

 Now you can use these Python programs to encode and decode any strings.

---

 So these are two of the easiest ways to encode and decode strings using base64\. If you'd like to learn more about the base64 command on Linux, it's better to check out [its manual page](https://linux.die.net/man/1/base64).

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-build-your-wealth-on-youtube-a-guide-to-creating-content-without-ads/"><u>[New] 2024 Approved Build Your Wealth on YouTube A Guide to Creating Content Without Ads</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ow-cost-leverage-to-youtube-lore-sponsorship-hacks-for-small-spheres/"><u>[New] Low-Cost Leverage to YouTube Lore Sponsorship Hacks for Small Spheres</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-best-ways-to-record-and-save-itunes-videos/"><u>[Updated] In 2024, Best Ways to Record and Save iTunes Videos</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-vivo-t2-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Vivo T2 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-vivo-y36-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Vivo Y36 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-y100-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-honor-x50-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from Honor X50.</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-edge-2023-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Edge 2023 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-8-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 8 To Other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-top-5-web-streaming-recorders/"><u>In 2024, Top 5 Web Streaming Recorders</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723000062939-mastering-stability-prevent-guardians-of-the-galaxy-from-collapsing-on-your-pc-with-our-tricks/"><u>Mastering Stability: Prevent Guardians of the Galaxy From Collapsing on Your PC with Our Tricks!</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-honor-magic-v2-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Honor Magic V2</u></a></li>
<li><a href="https://techidaily.com/the-5-best-methods-to-track-a-lost-or-stolen-iphone-15-pro-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>The 5 Best Methods to Track a Lost or Stolen iPhone 15 Pro | Stellar</u></a></li>
<li><a href="https://os-tips.techidaily.com/the-long-lasting-test-of-a-biodegradable-phone-case-a-5-month-update/"><u>The Long-Lasting Test of a Biodegradable Phone Case - A 5-Month Update</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-metaverse-gear-showdown-top-8-compared/"><u>The Ultimate Metaverse Gear Showdown Top 8 Compared</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-affordable-bluetooth-speakers-of-2022-your-ultimate-guide-to-summer-soundtracks/"><u>Top Affordable Bluetooth Speakers of 2022 - Your Ultimate Guide to Summer Soundtracks</u></a></li>
</ul></div>

