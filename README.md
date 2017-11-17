# bash-insulter
Randomly insults the user when typing wrong command.

Change insults as needed :)

```bash
noob@bender:~ $ sl

  Y u no speak computer???

-bash: sl: command not found
noob@bender:~ $ gti status

  This is why nobody likes you.

-bash: gti: command not found
noob@bender:~ $ sp aux

  Go outside.

-bash: sp: command not found
```

# Installation

    grab the zsh.command-not-found and paste it where-ever you want. (e.g. ~/.zshInsulter/ to keep it for you. and not bothering other users)

Then source the file automatically for new logins by adding the following to `/etc/bash.bashrc`:
```
if [ -f ~/.zshInsulter/zsh.command-not-found ]; then
    . ~/.zshInsulter/zsh.command-not-found
fi
```
Start a new zsh shell and type some invalid commands for the effects to be visible.
