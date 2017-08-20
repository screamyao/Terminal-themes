# Terminal-themes
OSX Terminal setup

## Initial Setup
1. Type below in Terminal
`nano .bash_profile`

2. Copy and Paste below 4 lines
```export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'```

3. Press Ctrl + O to save; Ctrl + X to exit

4. The first line changes the bash prompt to be colorized, and rearranges the prompt to be “username@hostname:cwd $”

5. The next two lines enable command line colors, and define colors for the ‘ls’ command

6. Finally, we alias ls to include a few flags by default. -G colorizes output, -h makes sizes human readable, and -F throws a / after a directory, * after an executable, and a @ after a symlink, making it easier to quickly identify things in directory listings.


## Themes
* Peppermint: https://noahfrederick.com/log/lion-terminal-theme-peppermint
* Dracula: https://draculatheme.com/terminal/


