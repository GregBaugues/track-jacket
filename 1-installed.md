# What did Seth just put on my machine? 

Of your recently added apps, iTerm2 and Sublime text are the most important. We'll be spending a bulk of our time in there. 

## [iTerm2](http://iterm2.com/)
A "console" or "terminal" gives you Godlike control over you machine from a command line. Your Mac came with an app called Terminal. iTerm2 is a slightly better version of that. We'll start off by using iTerm to do a lot of the things you currently do in finder: navigating directories, moving files around, running programs. 

Some basic commands in iTerm: 
* ```cp filename1 filename2``` -- Copy a file from filename1 to filename2
* ```mv filename1 filename2``` -- Move a file (also used to rename files) 
* ```mkdir newdirectoryname``` -- Create a new directory
* ```cd directoryname``` -- Change Directory (same as opening a folder in Finder) 
* ```ls``` -- List the files in a directory 
* ```cd .. ``` -- Goes back on folder 
* ```cd ~``` -- The ```~``` is a shortcut for "Home directory," so this changes to your home directory. 
* ```touch filename``` --  Creates a blank file. Be careful though, if you run this on an existing file, it will erase it.
* ```rm filename``` -- Remove (delete) a file

## [Sublime Text](http://www.sublimetext.com/3)

My best friend is a chef. First thing he taught me when I was learning to cook was the power of a good chef's knife. Super simple but elegant tool used for an unbelievable number of tasks. Get good with the knife and everything else gets a little easier. 

The text editor is a developer's chef knife. It's a minimalistic application with which we'll do most of our heavy lifting. There are strong opinions on which text editor is superior, but Sublime is currently the most popular. It is also the easiest to learn. 

## [Alfred](http://support.alfredapp.com/)

Coding involves switching between a lot of apps. The more we can keep our hands on the keyboard the faster we can move. Alfred will [save us some keystrokes](http://support.alfredapp.com/cheatsheet). Primarily we'll use it for launching new applications instead of clicking on them in the launch bar. 

## [ngrok](http://ngrok.com)

Eventually we'll set up a webserver on your machine. Twilio will need to access that web sever, but your computer is hiding behind the corporate router. Ngrok creates a "tunnel" between your computer and the public internet so that Twilio can communicate directly with it. 

## [Postman](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm?hl=en)

Postman is a Chrome extension. After we've built a program to interact with Twilio, we'll use Postman to figure out if it's working and to debug if things go wrong. 

## Before we go on

Two more bits of installation that we need to do inside iTerm. First, we'll install a package called Oh my Zsh which will make our terminal a bit prettier and marginally more user friendly: 

```
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

Second, we'll set up a shortcut so that we can launch Submlime text from the command line:

```
ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```

