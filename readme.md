# Alias for linux

### Open bash

    sudo nano ~/.bashrc
  
### Add alias in .bashrc

    # alias
    alias sag='sudo apt-get'
    alias clean="sag autoremove && sag autoclean && sag clean"
    alias createReadme="cp /home/nax/Documentos/Misc/readme.md ./"
    alias postman='/home/nax/Documentos/Postman/Postman'
    alias dist="cd dist; npm start"
    alias start="yarn start"
    alias uc="update && clean"
    alias update="sag update && sag upgrade"
    alias bashrc="nano ~/.bashrc"
    alias doc="cd ~/Documentos"
    alias lg='cd && cd Documentos/LG'
    alias n14='nvm use 14'
    alias n10='nvm use 10'
    alias c='clear'
    alias qd='n14 && quasar dev'
    alias qb='n14 && quasar build'
    alias qds='n14 && quasar dev -m ssr'
    alias qbs='n14 && quasar build -m ssr'
    alias yd='yarn dev'
    alias ant='cd ..'
    alias mouse='sudo modprobe -r psmouse && sudo modprobe psmouse'
    alias time='uptime -p && uptime -s'

    # git
    alias ga='git add'
    alias cm="git commit -m"
    alias st="git status"
    alias ch="git checkout"
    alias br="git branch"
    alias push="git push origin"
    alias commit="git add . && git commit -m"
    alias pushm="git push origin master"
    alias amend='git commit --amend -m'
    alias reset="git reset --soft HEAD~1"
    
### Reload .bashrc

    sudo source ~/.bashrc

En windows es necesario reiniciar
