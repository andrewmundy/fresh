# New Machine Setup
![](https://github.com/andrewmundy/fresh/blob/master/freshimg.gif)


## Install Homebrew
- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- check if your machine is ready to brew `brew doctor`
- Add homebrews location to path `export PATH="/usr/local/bin:$PATH"`
- install node `brew install node`

## Install NVM 
- `sudo node ~/.zshrc`
- add `plugins=(zsh-nvm)`
- `nvm install stable`

## Install ZSH
- install `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
- update Oh My ZSH `upgrade_oh_my_zsh`
- to add `code .` Open Visual Studio Code and press Command + Shift + P then type Shell in command palette now you are able to find this option like Shell Command : Install code in PATH from suggested list in command palette. Select that options.

## VS Code Plugins
- install `settings sync` from VS Code Marketplace