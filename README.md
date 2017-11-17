# bash-insulter
Randomly insults the user when typing wrong command.

Change insults as needed :)

![zshInsults](https://github.com/matmutant/zsh-insulter/blob/master/zshInsults.png)

# Installation

    git clone https://github.com/matmutant/zsh-insulter.git zsh-insulter
    grab the zsh.command-not-found and paste it where-ever you want. 
    (e.g. ~/.zshInsulter/ to keep it for you. and not bothering other users)

Then source the file automatically for new logins by adding the following to `/etc/bash.bashrc`:
```
if [ -f ~/.zshInsulter/zsh.command-not-found ]; then
    . ~/.zshInsulter/zsh.command-not-found
fi
```
Start a new zsh shell and type some invalid commands for the effects to be visible.
