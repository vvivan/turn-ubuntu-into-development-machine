# How to install VIM editor on Ubuntu
![VIM editor](/img/vim/vim-200.png)

## What is VIM
Vim is an advanced text editor that seeks to provide the power of the de-facto Unix editor 'Vi', with a more complete feature set. It's useful whether you're already using vi or using a different editor. Users of Vim 5 and 6 should consider upgrading to Vim 7.

For more info about VIM you can visit [VIM web page](http://www.vim.org)

### What VIM Can Do?

![VIM comics](/img/vim/vim-comics.png)

 Copyright (c) 2007 Laurent Gregoire

Vim is a highly configurable text editor built to enable efficient text editing. It is an improved version of the vi editor distributed with most UNIX systems.

Vim is often called a "programmer's editor," and so useful for programming that many consider it an entire IDE. It's not just for programmers, though. Vim is perfect for all kinds of text editing, from composing email to editing configuration files.

Despite what the above comic suggests, Vim can be configured to work in a very simple (Notepad-like) way, called evim or Easy Vim.

### What VIM is NOT?
Vim isn't an editor designed to hold its users' hands. It is a tool, the use of which must be learned.

Vim isn't a word processor. Although it can display text with various forms of highlighting and formatting, it isn't there to provide WYSIWYG editing of typeset documents. (It is great for editing TeX, though.)

## Installation
Vim (Vi Improved) text editor has reached the 8.0 release, the first major Vim release in ten years. Here’s how to install it in Ubuntu 16.04, Ubuntu 14.04 via PPA.

Vim 8.0 brings some interesting new features, many small improvements and lots of bug fixes. Here are some of them:

- Asynchronous I/O support, channels, JSON
- Jobs
- Timers
- Partials, Lambdas and Closures
- Packages
- New style testing
- Viminfo merged by timestamp
- GTK+ 3 support
- MS-Windows DirectX support

### How to install Vim 8.0 in Ubuntu
For Ubuntu 16.04, Ubuntu 14.04, Linux Mint 18/17, and their derivatives, Vim 8.0 has been made into this backport PPA

* Open terminal (Ctrl+Alt+T) and run command to add the PPA:
```
sudo add-apt-repository ppa:jonathonf/vim
```
* First update repos and then install VIM
```
sudo apt update
sudo apt install vim
```
* VIM is installed and now you can check VIM version:
```
vim -version
```
### How to start VIM
VIM editor can be started via search:
![VIM editor start](/img/vim/vim-start.png)

or from the terminal:

![VIM editor start from terminal](/img/vim/vim-terminal.png)

VIM editor basic look:

![VIM editor](/img/vim/vim-editor.png)

You are ready using VIM now - happy VIM-ing !!!

### Installation Video

[![Install VIM on UBUNTU](/img/vim/video-vim.png)](https://www.youtube.com/watch?v=m-eSK1gUIZA&t=9s)

## Uninstall VIM
To uninstall Vim 8.0 and downgrade it to the stock version in Ubuntu repository, run the command below to purge the PPA:
```
sudo apt install ppa-purge && sudo ppa-purge ppa:jonathonf/vim
```
