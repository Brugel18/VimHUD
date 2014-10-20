VimHUD is used an addon for Vim built in python and VimScript, that uses Machine Learning to generate alternate ways to preform common tasks based on your previous commands.

Installation:
The easiest way to install is to use pathogen. After installing pathogen clone this repo into your .vim/bundle folder.
Then you need to add the following line in your .bashrc,
alias vim='vim -w ~/.vimlog "$@"'
This is needed for VimHUD to record you keystrokes while you are in vim. This may change in the future if we find
a better way of doing this.

Please understand that we are still in a development state, so please bare with us and report any bugs :)

TODO:
Find a better why of matching strings for finding commands that will minimize keystrokes
More commands with better description
Better why to record keystrokes
