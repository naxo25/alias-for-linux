### Alias for linux

##### Open terminal

    sudo nano ~/.bashrc
  
##### Alias in .bashrc

    # alias
    alias p='pnpm'
    alias pi='pnpm i'
    alias d='pnpm run dev || yarn dev || qd'
    alias dp='pnpm deploy || yarn deploy'
    alias b='pnpm build || yarn build'
    
    alias .='subl .'
    alias sm='smerge .'
    alias doc='cd ~/Documentos/'
    alias pega='cd ~/Pega/'
    alias work='pega'
    alias dc='cd Documentos; cd '
    alias lg='cd ~/Pega/lg-smart-tv'
    alias Samsung='cd ~/Pega/Samsung'
    alias ay='cd ~/Pega/ayayay'
    alias aytv='cd ~/Pega/ayayaytvvite'
    alias est='cd ~/Pega/est*front-3'
    alias ott='cd ~/Pega/OTT'
    alias n='npm run'
    alias news='/home/nax/Documentos/"Proyectos nuevos"'
    alias pry='/home/nax/Documentos/Proyectos'
    alias sag='sudo apt-get'
    alias sag='sudo apt-get'
    alias clean="sag autoremove && sag autoclean && sag clean"
    alias cpreadme="cp /home/nax/Documentos/Misc/readme.md ./"
    alias start="yarn start"
    alias uc="update && clean"
    alias update="sag update && sag upgrade"
    alias brc="bashrc"
    alias bashrc="subl ~/.bashrc"
    alias sourcerc="source ~/.bashrc"
    alias src="source ~/.bashrc"
    alias n18='nvm use 18'
    alias n16='nvm use 16'
    alias n14='nvm use 14'
    alias n10='nvm use 10'
    alias n8='nvm use 8'
    alias c='clear'
    alias qd='yarn quasar dev'
    alias qb='yarn quasar build'
    alias qds='yarn quasar dev -m ssr'
    alias qbs='yarn quasar build -m ssr'
    alias qdw='yarn quasar dev -m pwa'
    alias qbw='yarn quasar build -m pwa'
    alias nr='npm run'
    alias b='build'
    alias d='n10; yarn dev'
    alias ydp='yarn dev:prod'
    alias postman='/home/nax/Documentos/Postman/Postman'
    alias ant='cd ..'
    alias mouse='sudo modprobe -r psmouse && sudo modprobe psmouse'
    alias time='uptime -p && uptime -s'
    alias clavenet='aSjNDRiPo4BAf5qDxrRa'
    alias android='/home/nax/android-studio/bin/studio.sh'
    alias y='yarn'
    alias fb='firebase logout && firebase login'
    alias fd='firebase deploy --only hosting'
    alias snp='subl /home/nax/.config/sublime-text/Packages/User/example.sublime-snippet'
    alias cpservor='cp /home/nax/Documentos/_.Servor/package.json ./ && cp -r /home/nax/Documentos/_.Servor/node_modules ./'
    alias cps='cpservor && dev'
    alias dist='cd dist && cps'
    alias tasks='/home/nax/Documentos/naxTasksApp/dist/electron/Packaged/naxTasksApp-*.AppImage'
    alias t='tasks & disown'
    alias gh='yarn git'
    alias pg='yarn pag'
    alias cloud='brave-browser https://platform.cloudways.com/apps/2682466/deployment'
    alias publish='npm version patch && npm publish'
    
    # LG
    alias device='ares-setup-device'
    alias nova='ares-novacom --device tvlg --getkey'
    alias deploylg='yarn build && node ./lg/build.js'
    
    alias buildlg='deploylg && ares-package -o dist/lg dist/spa'
    alias installlg='ares-install --device tvlg dist/lg/com.*.app*.ipk'
    alias launchlg='ares-launch --device tvlg com.ayayay.app'
    alias ylg='buildlg; installlg; launchlg'
    
    alias installlgs='ares-install --device tvlgs dist/lg/com.*.app*.ipk'
    alias launchlgs='ares-launch --device tvlgs com.ayayay.app'
    alias dlg='deploylg'
    alias ilg='installlg'
    alias ylgs='buildlg; installlgs; launchlgs'
    
    # git
    alias pm='git add .; git commit -m $1; push'
    alias ga='git add'
    alias cm='git commit -m'
    alias st='c && git status'
    alias ch='git checkout'
    alias br='git branch'
    alias push='yarn push || git push origin'
    alias commit='git add . && git commit -m'
    alias cmm='git add . && git commit -m'
    alias pushm='git push origin master'
    alias amend='git commit --amend -m'
    alias reset='git reset --soft HEAD~1'
    alias gc='git clone'
    alias gp='git pull'

#### Otras variables de entorno

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

* En windows es necesario reiniciar
