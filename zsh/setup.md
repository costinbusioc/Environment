# ZSH settings

## Add git aliases
```bash
vim ~/.zshrc

alias ga='git add'
alias gf='git fetch'
alias gm='git merge'
alias gst='git status'
alias gl='git pull'
alias gpo='git push origin'
alias gd='git diff'
alias gc='git commit'
alias gcm='git commit -m'
alias gcmn='git commit --no-verify -m'
alias gb='git branch'
alias gco='git checkout'
alias gcob='git checkout -b'
```
Exit and run: 
```bash
source ~/.zshrc
```

## Install oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Add zsh plugins
```bash
vim ~/.zshrc

plugins=(
    git
    django
    docker
    virtualenv
)
```
Exit and run: 
```bash
source ~/.zshrc
```
