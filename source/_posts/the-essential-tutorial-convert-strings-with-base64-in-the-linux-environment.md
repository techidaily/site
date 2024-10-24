---
title: "The Essential Tutorial: Convert Strings with Base64 in the Linux Environment"
date: 2024-10-19T18:45:39.417Z
updated: 2024-10-23T19:48:47.400Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Similar to the echo command, here-strings also add a newline character at the end of the string.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Encoding Files Using the base64 Command

 To encode a file using base64, you can pass the file directly as an option to the base64 command.

 To test it out, [create a new file](https://youtube-sure.techidaily.com/ed-2024-approved-effortless-subtitling-and-cc-addition-techniques-for-youtube-users/) and [append some text to it](https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-8-by-drfone-ios/). If you already have a text file, then use that. I've created a file called base.txt. To encode the file's content to base64, run:

base64 base.txt

![The Linux terminal displaying the process of encoding a file to base64 using the base64 command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-7.png) 

 Remember to replace base.txt with your file name. The above command only displays the output in the terminal. It doesn't save the encoded string anywhere. However, you can easily do that by redirecting the output to a new file. I've created another file called output.txt. This time I'll save the output to that empty file. Here's the command for that:

base64 base.txt > output.txt

![The Linux terminal showcasing the process of encoding the content of a file to base64 and saving it to another file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-7.png) 

 As you can see, the terminal didn't display the output. This command saved it to another file instead.

##  Decoding a base64 String Using the base64 Command

 For decoding a base64 string and turning it into a regular string, you'll need to use the "-d" flag with the base64 command. Let's see a demonstration using the echo command.

echo 'SG93VG9HZWVrCg==' | base64 -d

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of the echo command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-8.png) 

 If you'd like to use here-strings for decoding a base64 string, then use:

base64 -d <<< SG93VG9HZWVrCg==

![The Linux terminal displaying the process of decoding a base64 string using the base64 command with the help of here-strings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-7.png) 

 Sometimes, there might be non-alphanumeric characters in a string. You can ignore those while decoding the string by using the "-i" option.

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Using Python to Encode and Decode a base64 String

 If you're a Python programmer or are more familiar with the [Python programming language](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/) than Bash, then this method will be more suitable for you. Python has a base64 module that you can use for encoding and decoding strings. You can either use the python3 terminal command or write a full program. I'll show you both ways.

 The python3 command has a "-m" or module flag. You can use this flag to invoke the base64 module. Then you can pass your string with the help of the echo command or here-strings. Here's the full command:

echo 'I love Linux' | python3 -m base64 # Using the echo commandpython3 -m base64 <<< 'I love Linux' # Using here-strings

![The Linux terminal displays the process of encoding a string to base64 using Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-4.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To decode a base64 string, all you need to do is use the "-d" flag as seen previously with the base64 command. The syntax is below:

echo 'SSBsb3ZlIExpbnV4Cg==' | python3 -m base64 -d # Using the echo command​​​​​​python3 -m base64 -d <<< 'SSBsb3ZlIExpbnV4Cg==' # Using here-strings

![The Linux terminal showing the process of decoding a base64 string using the Python language](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-5.png) 

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Of course, the convenient way is to create a Python program that can handle the encoding and decoding by taking user input. First, let's create a program that will encode a string. Here's the encoding code:

        `import base64  

## Get input string from the user  
input_string = input("Enter the string to encode: ")  

## Encode the string using base64  
encoded_string = base64.b64encode(input_string.encode('utf-8'))  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Decode the encoded string to ensure it's correct (optional)  
decoded_string = base64.b64decode(encoded_string).decode('utf-8')  

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-maximize-your-youtube-reach-key-tips-for-enhancing-video-seo/"><u>[Updated] 2024 Approved Maximize Your YouTube Reach Key Tips for Enhancing Video SEO</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-embrace-a-new-identity-free-fire-sound-alteration-techniques-for-beginners/"><u>2024 Approved Embrace a New Identity Free Fire Sound Alteration Techniques for Beginners</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-make-any-tiktok-audio-the-ultimate-cellphone-sound/"><u>2024 Approved How To Make Any TikTok Audio, the Ultimate Cellphone Sound</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-optimize-your-video-library-youtubes-to-dailymotion-directly/"><u>2024 Approved Optimize Your Video Library YouTubes to Dailymotion Directly</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-guide-pairing-your-beats-headphones-with-windows-11-the-ultimate-troubleshooting/"><u>Easy Guide: Pairing Your Beats Headphones with Windows 11 – The Ultimate Troubleshooting</u></a></li>
<li><a href="https://techidaily.com/hard-reset-samsung-galaxy-s23plus-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Samsung Galaxy S23+ in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-vivo-s17-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817458455-nvidiaintel-graphics-issue-no-more-on-windows-10/"><u>Nvidia/Intel Graphics Issue No More on Windows 10</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-honor-magic-v2-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transforming-trips-into-tales-the-roadmap-to-becoming-a-travel-blogger-for-2024/"><u>Transforming Trips Into Tales The Roadmap to Becoming a Travel Blogger for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/next-travel-companion-best-youtubers-list/"><u>Your Next Travel Companion Best Youtubers' List</u></a></li>
</ul></div>

