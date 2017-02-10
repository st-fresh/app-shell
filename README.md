## appshell

This is my shell for cooking up new apps - calling it a shell because it's just commands I use in my interface between me and my PC to execute processes - a Command Line Interface(CLI) or Terminal

[LaymensTerms: Shell aka a Graphical Window/Box also called a Command Line Interface can be used on your computer screen to type words into using your keyboard except, these words are actually commands that the shell recognizes so, what you type into the shell is better termed a command that the shell will execute within your Operating System - aftering typing a command hit the [**Enter** key] to run your command in the Shell and get a response]

## What does this appshell do using Yeoman?

Yeoman actually works by typing in commands to the shell so, I have setup some things called generators that respond to certain things you type into the shell window and then, by typing in these things and hitting the [**Enter** key] you will cause the shell to respond to you with responses- here's what you can type to get started with an app in the shell:
//Using a PC running MacOS

**Get XCode setup in your CLI**
1st - Make sure your XCode App on your Mac is up to date, this app https://itunes.apple.com/us/app/xcode/id497799835?mt=12 <screenshot of app>
    - Inside your AppStore you should see "# Updates Available" <screenshot> so, if XCode is in this list then Update it
2nd - In your CLI aka the Terminal App in MacOS execute the following command:
$  xcode-select --install //this will install the XCode CLI/Shell Developer Tools <screenshot>
3rd - Other responses you may get - if your CLI responds with
`xcode-select: error: command line tools are already installed, use "Software Update" to install updates` 
then your tools have been installed already and you may only need to update XCode in the AppStore as mentioned above in 1st

**Install Homebrew package manager for MacOS using the CLI**
1st - Installing Homebrew will allow you to install and update other tools using the Terminal so, install it using this command:
$  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
2nd - Check for issues that Homebrew has with your system before adding tools by using this command:
#  brew doctor
3rd - Based on an warnings you may be getting you should be aware of what these warnings mean - use google or, jump into this gitter chatroom and I will try to get to your issue asap: `https://gitter.im/caskroom/homebrew-cask?utm_source=share-link&utm_medium=link&utm_campaign=share-link` (I'm st.fresh or @st-fresh on gitter)

**With Homebrew added - Install Node + npm using the CLI**
1st - Node + npm can be installed using the following command in the CLI:
$  brew install Node
2nd - To check that Node + npm properly installed execute the following command in the CLI:
$  node --version && npm --version //response should be on 2 lines:
`v#.#.#` 
`#.#.#`
for me my response was:
`v7.5.0`
`4.1.2`

----------- At this point it's safe to say that you could be struggling with environmental variables etc. and not be past a clean Homebrew install yet ------------------

**If** you are having a lot of weird errors or warnings as a response to the `brew doctor` command in the CLI then you need to get these sorted out before installing Node + npm and before moving forward - get on gitter and handle it!

----------- Moving Forward -------------

**Installing Git for Version Management of your Apps Code**
1st - Git will allow you to manage all the changes you make to your apps code use this command in CLI to check for git:
$  git --version 
2nd - If Git is not installed use https://git-scm.com/ to install it in your MacOS 
3rd - Again check for successful installation using this command in CLI:
$ git --version //successful response to this command should be `git version 2.10.1 (Apple Git-78)`
4th - If you still don't see that response above in 3rd you need to add gits installation location in your computers file directory to the file that controls your path permissions - because this could be different depending on your MacOS version etc. it's best to troubleshoot this more specifically so ask me in `https://gitter.im/gitterHQ/nodejs?utm_source=share-link&utm_medium=link&utm_campaign=share-link` the nodejs gitter chatroom (I'm st.fresh or @st-fresh on gitter)
5th - If Git is installed correctly in your MacOS it will be an app that you use from the CLI by executing many different types of commands, to understand what commands you can execute the CLI now that Git is installed check out https://try.github.io/levels/1/challenges/1 
6th - I recommend at this point you finish completing everything at the link in 5th above before moving forward so that you can save the app you generate next in your CLI below with Git and maintain the code properly.

**










//Using a PC running Windows OS

//Using a PC running Linux OS

- Generator 1: NodeJS + Bower + MongoDB + Gulp + Nodemon = generator-NBMGN

## Motivation

This appshell was made to help me track my development of applications

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)