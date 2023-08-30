# dotfiles
## Setup
### Brew 
```console
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Applications
```console
brew install --cask 
  slack
  visual-studio-code
  spotify
  hyper
  rectangle
  figma
  google-chrome 
```

### Terminal 
```console  
brew install 
  wget
  git
  nvm
```

### Hyper
``` console
 hyper install
  hyper
  hyper-pane 
  hyper-active-tab
  hyperline
  hyper-font-ligatures
  hyper-one-dark
```

### zsh
```console
brew install zsh
```
```console
which zsh
```
update hyper.js with results:
```console
shell: '/bin/zsh',
```
```
cd ~/.zsh && git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zdharma/fast-syntax-highlighting.git
cd ~/.zsh && wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/lib/completion.zsh
cd ~/.zsh && git clone https:/zsh-users/zsh-autosuggestions.git
cd ~/.zsh && wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/lib/history.zsh
cd ~/.zsh && wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/lib/key-bindings.zsh
touch aliases.zsh 
```
### FiraCode
```
brew tap homebrew/cask-fonts
brew install --cask font-fira-code
```

### .hyper.js
```
fontSize: 16,
fontFamily: 'Fira Code, Menlo, "DejaVu Sans Mono", Consolas, "Lucida Console", monospace',
```

### Starship
```
brew install starship
echo 'eval "$(starship init zsh)"' >> ~/.zshrc
```

* https://tjay.dev/howto-my-terminal-shell-setup-hyper-js-zsh-starship/
* https://www.robinwieruch.de/mac-setup-web-development/

## System Preference 
* Desktop & Dock
  * Enable Minimize windows into the application icon
  * Disable Show recent applications in Dock    
* Mouse
  * Disable Natural Scrolling
* Display
  * Night Shift
    * 7:00 pm - 7:00 am
    * More Warm
  

## Chrome
* Extensions
  * 1Password – Password Manager
  * axe DevTools - Web Accessibility Testing
  * EditThisCookie
  * Grammarly: Grammar Checker and AI Writing App
  * Quick Javascript Switcher
  * React Developer Tools
* Chrome Apps
  * Gmail
  * Google Calendar
  * Google Meet
  * Grammarly
  * ChatGPT

## Finder
* Applications
* Desktop
* Downloads
* Users
* My Drive https://www.google.com/drive/download/

