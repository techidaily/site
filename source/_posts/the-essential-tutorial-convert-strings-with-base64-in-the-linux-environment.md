---
title: "The Essential Tutorial: Convert Strings with Base64 in the Linux Environment"
date: 2024-10-02T04:17:29.777Z
updated: 2024-10-05T18:13:46.556Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f5b8e36c4ebd6a9ca109693d88c7c440e68928a27daf3516cb90c9a543d54e11.jpeg
---

## The Essential Tutorial: Convert Strings with Base64 in the Linux Environment

Want to learn how to encode and decode strings using the base64 binary-to-text scheme? This tutorial will show you two methods to encode and decode a string on Linux using the base64 command and the Python programming language.

##  Where Is base64 Used?

 base64 is widely used in different domains. Some of the most common areas include email attachments, web development, networking, and URL encoding.

 Some email systems use base64 to encode binary data such as images and documents into text format so that these can be safely transmitted with the message. Web developers also use base64 to embed images into HTML and CSS to reduce the number of HTTP requests and improve page load speed.

 Another common use of base64 encoding is in authentication tokens. Usernames and passwords are sometimes masked using this encoding scheme and added to HTTP headers or URL parameters. In networking, base64 is used in protocols that use text-based communication, such as HTTP and SMTP, for transmitting data without corruption.

 What you should know is that base64 is only an encoding scheme. The encoded data can be easily decoded to get the original data back. You should never use it if you need to [encrypt data instead](https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-g54-5g-drfone-by-drfone-virtual-android/).

##  Encoding a String Using the base64 Command

 The most basic way to encode a string using base64 is to output it to the terminal using [the echo command](https://facebook.techidaily.com/cut-out-controversy-refresh-your-feed-focus/). The trick is to [pipe the output](https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) of the echo command to base64, like this:

echo 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-9.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Because of the default behavior of the echo command, there's a trailing newline character at the end of the string. If you'd like to omit that and only use the string, run:

echo -n 'I love Linux' | base64

![The Linux terminal displaying the process of encoding a string using base64 omitting the newline character](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-10.png) 

 As you can notice, the output is different from the previous one. You can also do this using the printf command which doesn't automatically append a newline character to the string. The format is given below:

printf 'I love Linux' | base64

![The Linux terminal showing the process of encoding a string received from the printf command using base64](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-8.png) 

 This output is the same as the previous one because there are no newline characters this time. If you're familiar with [here-strings](https://tldp.org/LDP/abs/html/x17837.html) on Linux, you can also use them to send your string output to the base64 command like this:

base64 <<< 'I love Linux'

![The Linux terminal showcases how to encode a string using the base64 command with the help of here string operator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-9.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Similar to the echo command, here-strings also add a newline character at the end of the string.

##  Encoding Files Using the base64 Command

 To encode a file using base64, you can pass the file directly as an option to the base64 command.

 To test it out, [create a new file](https://youtube-sure.techidaily.com/ed-2024-approved-effortless-subtitling-and-cc-addition-techniques-for-youtube-users/) and [append some text to it](https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-8-by-drfone-ios/). If you already have a text file, then use that. I've created a file called base.txt. To encode the file's content to base64, run:

base64 base.txt

![The Linux terminal displaying the process of encoding a file to base64 using the base64 command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-7.png) 

 Remember to replace base.txt with your file name. The above command only displays the output in the terminal. It doesn't save the encoded string anywhere. However, you can easily do that by redirecting the output to a new file. I've created another file called output.txt. This time I'll save the output to that empty file. Here's the command for that:

base64 base.txt > output.txt

![The Linux terminal showcasing the process of encoding the content of a file to base64 and saving it to another file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-7.png) 

 As you can see, the terminal didn't display the output. This command saved it to another file instead.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Decoding a base64 String Using the base64 Command

 For decoding a base64 string and turning it into a regular string, you'll need to use the "-d" flag with the base64 command. Let's see a demonstration using the echo command.

echo 'SG93VG9HZWVrCg==' | base64 -d

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of the echo command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-8.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
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

## Get input string from the user  
input_string = input("Enter the string to encode: ")  

## Encode the string using base64  
encoded_string = base64.b64encode(input_string.encode('utf-8'))  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Decode the encoded string to ensure it's correct (optional)  
decoded_string = base64.b64decode(encoded_string).decode('utf-8')  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Print the encoded and decoded strings  
print("Encoded string:", encoded_string.decode('utf-8'))  
print("Decoded string (verification):", decoded_string)  
`
    
 Save the file with a suitable name and a ".py" extension. I'm saving it by the name base64\_encoder.py. Once done, run the program with:

python3 base64_encoder.py

![The Linux terminal showcasing the process of encoding a string using a Python program](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/11-3.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-ad-innovations-what-to-expect-from-facebook/"><u>[Updated] 2024 Approved Ad Innovations What to Expect From Facebook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-eye-opening-list-of-the-top-12-yt-gamers-intros-freepaid-sessions-for-2024/"><u>[Updated] Eye-Opening List of the Top 12 YT Gamers' Intros (Free/Paid Sessions) for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-get-gratis-safe-vlc-media-player-on-mac-os-x-devices/"><u>[Updated] How to Get Gratis, Safe VLC Media Player on Mac OS X Devices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-fast-friending-mastering-the-art-of-profile-searches/"><u>[Updated] In 2024, Fast Friending Mastering the Art of Profile Searches</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-innovations-in-youtube-shorts-templates-latest-trends-and-tips-for-2024/"><u>[Updated] Innovations in YouTube Shorts Templates Latest Trends & Tips for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725289325086-2024/"><u>2024年提升图像清晰度：顶级五种方法</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-htc-u23-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for HTC U23 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-s17t-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo S17t Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-vivo-x90s-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-honor-play-40c-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Honor Play 40C? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-after-deleting-from-recently-deleted-on-iphone-13-pro-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover deleted photos after deleting from Recently Deleted on iPhone 13 Pro | Stellar</u></a></li>
<li><a href="https://extra-support.techidaily.com/leveraging-look-up-table-techniques-for-richer-images-in-pscc-for-2024/"><u>Leveraging Look-Up Table Techniques for Richer Images in PSCC for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/new-frontiers-in-gaming-combatting-increasing-cyberthreats/"><u>New Frontiers in Gaming: Combatting Increasing Cyberthreats</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-uot-file-documents-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>The best electronic signature way to sign .uot file documents online</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-google-pixel-8-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Google Pixel 8.</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-hardware-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your hardware drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
</ul></div>

