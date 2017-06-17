# How to install VIM editor on Ubuntu
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

## How to install Vim 8.0 in Ubuntu
For Ubuntu 16.04, Ubuntu 14.04, Linux Mint 18/17, and their derivatives, Vim 8.0 has been made into this backport PPA

- Open terminal (Ctrl+Alt+T) and run command to add the PPA:
```
sudo add-apt-repository ppa:jonathonf/vim
```
- First update repos and then install VIM
```
sudo apt update
sudo apt install vim
```
- VIM is installed and now you can check VIM version:
```
vim -version
```
## Uninstall VIM
To uninstall Vim 8.0 and downgrade it to the stock version in Ubuntu repository, run the command below to purge the PPA:
```
sudo apt install ppa-purge && sudo ppa-purge ppa:jonathonf/vim
```
