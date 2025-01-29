---
title: "Step-by-Step Guide: Activating and Running ChatGPT with ShellGPT in Ubuntu's Terminal Environment"
date: 2025-01-23T14:44:59.393Z
updated: 2025-01-29T00:15:25.404Z
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://thmb.techidaily.com/01edaba53137429381532b08b94562d4a741359e1c28374d3f1b3c538848d74c.jpg
---

## Step-by-Step Guide: Activating and Running ChatGPT with ShellGPT in Ubuntu's Terminal Environment

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is ShellGPT?](https://facebook-videos.techidaily.com/updated-online-oasis-secure-re-entry-to-social-networks-for-2024/)
* [Step 1: Install the Python Tools](https://vp-tips.techidaily.com/updated-high-staking-habitats-critical-commentary-for-2024/)
* [Step 2: Prepare a Python Virtual Environment](https://youtube-docs.techidaily.com/024-approved-dive-deep-into-youtube-shorts-essentials/)
* [Step 3: Create a ChatGPT API Key](https://youtube-videos.techidaily.com/new-essential-steps-for-mp3-streams-on-youtube/)
* [Step 4: Export the API Key](https://windows11.techidaily.com/step-by-step-guide-to-manipulating-fax-cover-pages-on-win11/)
* [Step 5: Install ShellGPT](https://extra-hints.techidaily.com/heartstrings-plucked-essential-vocal-masterpieces-for-a-kiss/)
* [Step 6: Use ShellGPT](https://extra-guidance.techidaily.com/in-2024-mastering-motion-effects-in-ai-enhancing-photoshop-images/)
* [Learning ShellGPT Commands](https://remote-screen-capture.techidaily.com/updated-2024-approved-maximizing-play-in-apex-legends-without-cross-platform-limitations/)
* ["In Conclusion"](https://tech-revival.techidaily.com/elevate-your-coding-game-with-costless-gpt-4-turbo-on-copilot-platforms/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

 If you want to run ChatGPT in the Ubuntu terminal, you can use a Python program called ShellGPT to send text prompts to ChatGPT and display the response. To run ShellGPT you must install it and obtain a ChatGPT API key.

 Want to use the ChatGPT in a terminal window on your Ubuntu Linux PC? ShellGPT lets you use all the features of the famous AI chatbot, on the command line. Here's how to set ShellGPT up and start using it.

##  What Is ShellGPT?

[ShellGPT](https://github.com/TheR1D/shell%5Fgpt) is a Python program that lets you access [OpenAI's ChatGPT](https://smart-video-editing.techidaily.com/new-how-to-find-free-sites-for-sound-effect-and-add-them-in-final-cut-pro-for-2024/) from the command line of a terminal window. It sends your text prompts and your ChatGPT [API](https://extra-resources.techidaily.com/2024-approved-best-unsung-free-speech-to-text-apps-for-your-mac/) key to ChatGPT and prints out ChatGPT's response.

 It's just like running ChatGPT on your own computer, without any of the hassle, and regardless of the computing power of your computer. You'll need to have a ChatGPT API key, but it only takes moments to get one, and they're free.

Related: [How to Run a ChatGPT-like AI on Your Own PC](https://tech-revival.techidaily.com/solving-the-problem-why-does-chatgpt-forget-our-talks/) 

 ChatGPT is probably the most famous of the new-wave of [large language model](https://en.wikipedia.org/wiki/Large%5Flanguage%5Fmodel) [AI](https://en.wikipedia.org/wiki/Artificial%5Fintelligence) chatbots, developed using [deep learning techniques](https://en.wikipedia.org/wiki/Deep%5Flearning) and massive data sets.

 It's able to hold convincing and lifelike conversations, and can [generate prose](https://fox-http.techidaily.com/mastering-the-use-and-maintenance-of-m1-max-clips-for-2024/) and other text format responses on just about any topic you can imagine. Just keep in mind that it's a simulation of a knowledgeable, intelligent person. It isn't genuinely intelligent, and [it'll happily make stuff up](https://youtube-help.techidaily.com/free-method-to-record-your-youtube-watching-experience-for-2024/).

 None of the following steps are difficult, and you should be up and running in ten minutes or so.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Step 1: Install the Python Tools

 Ubuntu usually ships Python as standard, but you can check if it is present by asking for its version number.

python --version

![Checking the version of Python in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/1-5.png) 

 If Python isn't installed, you can install it using this command.

sudo apt install python3

 We also need `pip`, the python package manager.

pip --version

![Checking the version of pip in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/2-6.png) 

 It wasn't installed on our test computer, so we added it using `apt`.

sudo apt install python3-pip

![Installing pip on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/3-5.png) 

 We're going to install ShellGPT in a [Python virtual environment](https://docs.python.org/3/library/venv.html). This sandboxes ShellGPT from your system Python files and libraries, and means it cannot accidentally interfere with your other Python programs. It's just a safe precaution.

 To do that, we're going to need to install the Python virtual environment packages.

sudo apt install python3-venv

![Installing the Python virtual environment module on Ubuntu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/4-4.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Step 2: Prepare a Python Virtual Environment

 Create a directory to install ShellGPT into. We named ours "shellgpt", just to keep things obvious. Change into your new directory when it's been created.

mkdir shellgpt

cd shellgpt

![Creating the shellgpt directory](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/5-5.png) 

 Next, we use the `-m` (module) option and run the Python virtual environment module and create a new virtual environment inside our new directory. We created one called "shellgpt."

python3 -m venv shellgpt

![Generating the shellgpt virtual environment](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/6-4.png) 

 This gives us a private, virtual environment called "shellgpt", inside our "shellgpt" directory. To activate it we need to run a script called "activate." This is located in the "bin" directory of our virtual environment.

source shellgpt/bin/activate

![Activating the Python shellgpt virtual environment](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/7-4.png) 

 Note the "(shellgpt)" in front of the command prompt.

##  Step 3: Create a ChatGPT API Key

 To access the features of ChatGPT, you'll need [an OpenAI API key](https://review-topics.techidaily.com/how-to-unlock-iphone-xs-without-passcode-by-drfone-ios-unlock-ios-unlock/). You can use an existing API key if you have one, or you can create one on the [OpenAI website](https://platform.openai.com/account/api-keys).

 Follow the link and either log in or sign up.

 When you're logged in, click your account name in the top-right corner and select "View API Keys" from the menu.

![The ChatGPT account menu with the "View API Keys" option highlighted](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/7a.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the API keys web page, click the "Create New Secret Key" button.

![The ChatGPT "Create new secret key" button](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/8-6.png) 

 Type in a name for your key---it can be anything---and then click the green "Create Secret Key" button.

![providing a name for the API key, with the "Create secret key" button highlghited](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/9-3.png) 

 Your new key is displayed to you. **You only get to see your key this one time**. If you log out and back in, you'll see an entry for the key, but you won't be able to view the entire key string. So, copy the key and paste it into an editor, and save the file with an obvious name.

##  Step 4: Export the API Key

 We need to make the key available to ShellGPT. The easiest way is to export it as an environment variable. You can do this on the command line, but it only lasts until you reboot your PC. Adding the export command to [your ".bashrc" file](https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nokia-xr21-drfone-by-drfone-reset-android-reset-android/) exports the environment variable for you automatically, each time you open a terminal window.

 To do it on the command line, type "export OPENAI\_API\_KEY=" and then paste your API key by pressing "Shift+Ctrl+v", so that it looks like the screenshot below.

export OPENAI_API_KEY=<your secret API key>

![Exporting the ChatGPT API key on the command line](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/10-4.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To put the export command in your ".bashrc" file, use your favorite editor and add the command to your file.

gedit ~/.bashrc

![Adding the export ChatGPT line to the .bashrc file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/11-3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Save your changes and close the editor. To force your terminal session to reread your ".bashrc" file, use the `source` command.

 source \~/.bashrc

![Using source to force the shell to read the .bashrc file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/12-2.png) 

##  Step 5: Install ShellGPT

 With all of the preparation out of the way, we can install ShellGPT using the Python `pip` command.

python pip shell-gpt

![Using pip to install the shell-gpt module](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/13-2.png) 

 The installation will begin, and a variety of package names will scroll by in your terminal window.

![Output during the installation of the shell-gpt module](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/14-2.png) 

 When it's finished we can, finally, use ShellGPT to access ChatGPT.

##  Step 6: Use ShellGPT

 The ShellGPT command is `sgpt`. We provide our text prompts to this command, and press "Enter."

sgpt "Who is Thursday named after?"

![Using the sgpt command to send input to ChatGPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/16-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 ShellGPT acts as the middleman between us and ChatGPT, and displays the response from ChatGPT.

Related: [How to Create Aliases and Shell Functions on Linux](https://hardware-help.techidaily.com/download-the-latest-logitech-camera-drivers-at-no-cost-for-windows-users/) 

 That's great, it's all working. But it's a bit long winded to have to [cd into the directory](https://audio-shaping.techidaily.com/updated-decoding-vimeos-video-dimensions-a-complete-perspective-on-aspect-ratios-for-2024/) we created the virtual environment in, and then issue the `source shellgpt/bin/activate` command before we can use ShellGPT.

 A better way is to create an alias that does all of that for us. Edit your ".bashrc" file and add this line.

alias chatgpt="cd ~/shellgpt/;source shellgpt/bin/activate"

![Adding an alias to the .bashrc file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/17-2.png) 

 Remember to use the names of the directory and virtual environment that you created. We called our alias "chatgpt", but you can use whatever name you prefer. Save your changes, and use `source ` to read the ".bashrc" file again.

source ~/.bashrc

![Using source to force the shell to read the .bashrc file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/18-2.png) 

 Now, at a normal command prompt, entering the name of your alias and hitting "Enter" places you in your Python virtual environment, which is activated and ready for your input.

chatgpt

![Using the chatgpt alias to access ShellGPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/19-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Learning ShellGPT Commands

 The [ShellGPT GitHub page](https://github.com/TheR1D/shell%5Fgpt) has much more information on using ShellGPT and its command line options.

 For example, the `--code` option limits the output of ShellGPT to show program code only. Normally, if we ask it to generate some code, it does so, but it generates a description too.

sgpt "Show me an example of a recursive function in C"

![Using ChatGPT to generate a recursive function in C](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/20-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 By adding the `--code` option, the description is suppressed. This would be handy if you want to redirect the output into a file.

sgpt --code "Show me an example of a recursive function in C"

![Using ChatGPT to generate a recursive function in C, with the --code option so only the function code is displayed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/21-2.png) 

 ShellGPT, through ChatGPT, can also generate [syntax-correct Bash commands and shell scripts](https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/).

##  "In Conclusion"

 In conclusion, ShellGPT is a powerful tool for programmers and system administrators alike. Its ability to assist with tasks such as managing operating systems and programming languages makes it an invaluable asset to any team. With its intuitive interface and vast knowledge base, ShellGPT is sure to become a go-to resource for those looking to streamline their workflow and increase productivity.

 Or at least, that's what it says.

![Using ShellGPT and ChatGPT yto write the closing paragraph](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/04/22-2.png)

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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-master-image-editing-with-these-top-8-tablets-beyond-filmoras-reach/"><u>[New] In 2024, Master Image Editing with These Top 8 Tablets Beyond Filmora's Reach</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-the-ultimate-guide-to-vivacut-a-detailed-2024-review/"><u>[New] The Ultimate Guide to VivaCut A Detailed 2024 Review</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-transform-tweets-converting-video-to-gifs-at-no-cost/"><u>[New] Transform Tweets Converting Video to GIFs at No Cost</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-connectivity-techkey-bluetooth-adapter-drivers-for-windows-10-7-and-8-free-downloads-available/"><u>Effortless Connectivity: Techkey Bluetooth Adapter Drivers for Windows 10, 7 & 8 – Free Downloads Available</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-htc-u23-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your HTC U23 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-realme-c67-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Realme C67 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-apple-iphone-15-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-7-plus-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 7 Plus System? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y27-4g-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo Y27 4G</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-pursuit-of-perfection-does-picku-outshine-other-android-tools/"><u>In Pursuit of Perfection Does PickU Outshine Other Android Tools?</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-zte-blade-a73-5g-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of ZTE Blade A73 5G on Mac?</u></a></li>
</ul></div>

