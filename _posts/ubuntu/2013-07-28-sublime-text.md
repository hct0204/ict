---
published: true
layout: post
category: ubuntu
tags: 
  - "sublime-text"
---

## Sublime Text 2

## Install From Ubuntu PPA
ref. [Sublime Text 2 Ubuntu PPA](http://www.webupd8.org/2011/03/sublime-text-2-ubuntu-ppa.html)

    sudo add-apt-repository ppa:webupd8team/sublime-text-2
    sudo apt-get update
    sudo apt-get install sublime-text

## Installation Script
https://github.com/TCattd/sublime-text-bash-installer

    sudo bash st2install

## Q&A

### Sublime Text 2.0.2 sidebar missing on ubuntu 10.04
ref. 

* [Weird sidebar and tabs](http://www.sublimetext.com/forum/viewtopic.php?f=3&t=12167&start=0&hilit=sidebar)
* [Reverting to a Freshly Installed State](http://www.sublimetext.com/docs/2/revert.html)

To revert to a frestly installed state, you can:

1. Exit Sublime Text 2
2. Delete (or move) the data folder (~/.config/sublime-text-2)
3. Start Sublime Text 2

