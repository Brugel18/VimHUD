VimHUD is used an addon for Vim built in python and VimScript, that recommends commands for you to learn. VimHUD 
remembers which commands you know and can identify which commands will reduce the most amount of keystrokes
and displays a new command on the bottom of your screen. 

Installation:
The easiest way to install is to use pathogen. After installing pathogen clone this repo into your .vim/bundle folder.
Then you need to add the following line in your .bashrc,
alias vim='vim -w ~/.vimlog "$@"'

Usage:
TODO

This is needed for VimHUD to record you keystrokes while you are in vim. This may change in the future if we find
a better way of doing this.

Please understand that we are still in a development state, so please bare with us and report any bugs :)

TODO:
Find a better why of matching strings for finding commands that will minimize keystrokes
More commands with better description
Better why to record keystrokes
