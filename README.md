## my app-shell - where apps are generated

This is my shell for cooking up new apps - calling it a shell because it's just commands I use in my interface between me and my PC to execute processes - in my Command Line Interface(CLI) or Terminal

[**In Laymans Terms:** Shell aka a Graphical Window/Box also called a Command Line Interface can be used on your computer screen to type words into using your keyboard except, these words are actually commands that the shell recognizes so, whatever you type into your shell is better termed a command that the shell will execute within your Operating System - after typing a command hit the [**Enter** key] to run your command in the Shell and get a response]

## What does this app-shell do using Yeoman?

Yeoman see it at [link](http://yeoman.io "Title") actually works by typing in commands to the shell/CLI/Terminal so, I have setup some things called generators that respond to certain things you type into the shell window.

[**In Laymans Terms:** By typing in these things and hitting the [**Enter** key] you will cause the shell to respond to you- you can start typing into your Terminal in **2nd** below - all Terminal commands in this guide are proceeded by **$** (you don't have to type **$** just type the command that proceeds afterwards)

*Using a PC running MacOS*

#Get XCode setup in your CLI
## 1st - Make sure your XCode App on your Mac is up to date, this app.... https://itunes.apple.com/us/app/xcode/id497799835?mt=12 
![Alt](http://res.cloudinary.com/hrscywv4p/image/upload/c_limit,h_9000,w_1200,f_auto,q_90/v1/270318/Screen_Shot_2017-02-10_at_12.47.46_AM_s5yvoy.png "Title")
* Inside your AppStore update XCode if it appears under **Updates Available** 
![Alt](http://res.cloudinary.com/hrscywv4p/image/upload/c_limit,h_9000,w_1200,f_auto,q_90/v1/270318/Screen_Shot_2017-02-10_at_12.47.05_AM_pieoc7.png "Title")
* So, if XCode is in this list then Update it

## 2nd - In your CLI aka the Terminal App in MacOS execute the following command....
```
$  xcode-select --install [^1]
```
[^1]: This will install the XCode CLI/Shell Developer Tools
![Alt](http://res.cloudinary.com/hrscywv4p/image/upload/c_limit,h_9000,w_1200,f_auto/v1/270318/Screen_Shot_2017-02-10_at_12.40.05_AM_frvsyl.png "Title")
## 3rd - Other responses you may get, i.e. If your CLI responds with....
```
xcode-select: error: command line tools are already installed, use "Software Update" to install updates
``` 
If you see this response then your tools have been installed already and you may only need to update XCode in the AppStore as mentioned above in **1st**

#Install Homebrew package manager for MacOS using the CLI
## 4th - Installing Homebrew will allow you to install and update other tools using the Terminal so, install it using this command....
```
$  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
## 5th - Check for issues that Homebrew has with your system before adding tools by using this command....
```
$  brew doctor
```
## 6th - Based on warnings you may be getting you should be aware of what these warnings mean - use google or....
* Enter this gitter chatroom at [link](https://gitter.im/caskroom/homebrew-cask?utm_source=share-link&utm_medium=link&utm_campaign=share-link "Title") and I will try to get to your issue asap! *I'm st.fresh or @st-fresh on gitter*

# With Homebrew added - Install Node + npm using the CLI
## 7th - Node + npm can be installed using the following command in the CLI....
```
$  brew install Node
```
## 8th - To check that Node + npm properly installed execute the following command in the CLI....
```
$  node --version && npm --version //response should be on 2 lines
```
* Responses should look like....
```
v7.5.0
4.1.2
```


> > At this point it's safe to say that you could be struggling with environmental variables etc. within your Operating System - meaning you're not past a clean Homebrew install yet!
> > **If** you are having a lot of weird errors or warnings as a response to the `brew doctor` command in the CLI then you need to get these sorted out **before** installing Node + npm and before moving forward - get on gitter at [link](https://gitter.im/caskroom/homebrew-cask?utm_source=share-link&utm_medium=link&utm_campaign=share-link "Title") and handle it!

# Moving Forward with Git for Version Control

# Installing Git for Version Management of your Apps Code**
## 9th - Git will allow you to manage all the changes you make to your apps code use this command in CLI to check for git....
```
$  git --version [^2]
``` 
[^2]: The **response** in your Terminal should be something like `git version 2.10.1 (Apple Git-78)` if git is working
## 10th - If Git is not installed use...
This [link](https://git-scm.com/ "Title") to install Git in your MacOS 
## 11th -  Again check for successful installation by repeating 9th above
## 12th -  If you still don't see the response above in 9th you need to....
* Add the Git installation location in your computers file directory to the file that controls your path permissions however, This location and/or file you need to update with a new PATH variable could be different depending on your MacOS version etc. so, it's best to troubleshoot this more specifically so ask me using [link](https://gitter.im/gitterHQ/nodejs?utm_source=share-link&utm_medium=link&utm_campaign=share-link "Title") on gitter in the nodejs gitter chatroom *I'm st.fresh or @st-fresh on gitter*
##13th - If Git is installed correctly in your MacOS it will be an app that you use from the CLI by executing many different types of commands....
* To understand what commands you can execute in the Terminal now that Git is installed check out [link](https://try.github.io/levels/1/challenges/1 "Title") 
##14th - I recommend at this point you finish completing everything at the link in 13th above before moving forward so that....
* You can record your coding progress after you generate the apps code next - this will help you properly maintain your work each time you finish for the day
# The NBMGN Generator is being cooked up right now - standby
*Using a PC running Windows OS -- Coming Soon*
*Using a PC running Linux OS -- Coming Soon*

## Motivation

This was made to help me track my development of applications and, easily generate from within the seed branch new apps with Yeoman commands.

## API Reference

## Contributors

## License