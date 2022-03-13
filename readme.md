# Alias for linux

### Open bash

    sudo nano ~/.bashrc
  
### Add alias in .bashrc

    # alias
    alias sag='sudo apt-get'
    alias clean="sag autoremove && sag autoclean && sag clean"
    alias createReadme="cp /home/nax/Documentos/Misc/readme.md ./"
    alias dist="cd dist; npm start"
    alias start="yarn start"
    alias uc="update && clean"
    alias update="sag update && sag upgrade"
    alias bashrc="nano ~/.bashrc"
    alias upcdf='npm run deploy:production:cdf'
    alias n14='nvm use 14'
    alias n10='nvm use 10'
    alias c='clear'
    alias qd='n14 && quasar dev'
    alias qb='n14 && quasar build'
    alias qds='n14 && quasar dev -m ssr'
    alias qbs='n14 && quasar build -m ssr'
    alias qdw='n14 && quasar dev -m pwa'
    alias qbw='n14 && quasar build -m pwa'
    alias dev='n14; yarn dev'
    alias ydp='yarn dev:prod'
    alias postman='/home/nax/Documentos/Postman/Postman'
    alias ant='cd ..'
    alias mouse='sudo modprobe -r psmouse && sudo modprobe psmouse'
    alias time='uptime -p && uptime -s'
    alias promo='subl /home/nax/Documentos/estadiocdf-front-3/src/views/landing/guest.vue'
    alias cdf='npm run deploy:production:cdf'
    alias android='/home/nax/android-studio/bin/studio.sh'
    alias y='yarn'
    alias yp='yarn push'
    alias fb='firebase logout && firebase login'
    alias sn='subl /home/nax/Documentos/SnippetsCopilot/example.sublime-snippet'alias cpservor='cp /home/nax/Documentos/_.Servor/package.json ./ && cp -r /home/nax/Documentos/_.Servor/node_modules ./'

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
    alias gc='git clone'
    alias gp='git pull'

    # yarn
    export PATH="$(yarn global bin):$PATH"
    export PATH="/home/nax/Documentos/LG/lg/CLI/bin:$PATH"

    # Variables entorno
    export ANDROID_HOME="$HOME/Android/Sdk"
    export ANDROID_SDK_ROOT="$HOME/Android/Sdk"
    export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"
    export GRADLE="$ANDROID_SDK_ROOT/gradle-4.10.3/bin"

    export PATH=$PATH:$ANDROID_SDK_ROOT/tools;
    export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools;
    export PATH=$PATH:$JAVA_HOME;
    export PATH=$PATH:$GRADLE;
    export PATH=$PATH:$HOME/tizen-studio/tools/ide/bin;
    export PATH=$PATH:$HOME/tizen-studio/tools;

    
### Reload .bashrc

    sudo source ~/.bashrc

En windows es necesario reiniciar
