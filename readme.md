### Alias for linux

##### Open .bashrc in terminal

    sudo nano ~/.bashrc
  
##### Alias in .bashrc

    # alias
    alias p='pnpm'
    alias pi='pnpm i'
    alias d='pnpm run dev'
    alias gh='pnpm run git'
    alias dp='npm run deploy'
    alias b='pnpm build'
    alias lg='pnpm lg'
    alias Samsung='pnpm samsung'
    alias pega='cd ~/Pega/'
    
    alias .='subl .'
    alias snp='subl /home/nax/.config/sublime-text/Packages/User/example.sublime-snippet'
    alias sm='smerge .'
    alias doc='cd ~/Documentos/'
    alias ay='cd ~/Pega/NedTVSmart'
    alias atv='cd ~/Pega/ATVSmart/'
    alias ott='cd ~/Pega/OTT'
    alias ..='cd ..'
    alias dist='cd dist && cps'
    alias cpservor='cp /home/nax/Documentos/_.Servor/package.json ./ && cp -r /home/nax/Documentos/_.Servor/node_modules ./'
    alias cps='cpservor && d'
    
    alias sag='sudo apt-get'
    alias uc="update && clean"
    alias clean="sag autoremove && sag autoclean && sag clean"
    alias update="sag update && sag upgrade"
    alias deb="sudo dpkg -i"
    
    alias cpreadme="cp /home/nax/Documentos/Misc/readme.md ./"
    alias brc="subl ~/.bashrc"
    alias bashrc="subl ~/.bashrc"
    alias src="source ~/.bashrc"
    alias sourcerc="source ~/.bashrc"
    alias n18='nvm use 18'
    alias c='clear'
    alias postman='/home/nax/Documentos/Postman/Postman'
    alias mouse='sudo modprobe -r psmouse && sudo modprobe psmouse'
    alias time='uptime -p && uptime -s'
    alias clavenet='aSjNDRiPo4BAf5qDxrRa'
    alias android='/home/nax/android-studio/bin/studio.sh'
    alias fb='firebase logout && firebase login'
    alias fd='firebase deploy --only hosting'
    alias tasks='/home/nax/Documentos/naxTasksApp/dist/electron/Packaged/naxTasksApp-*.AppImage'
    alias t='tasks & disown'
    alias cloud='brave-browser https://platform.cloudways.com/apps/2682466/deployment'
    alias publish='npm version patch && npm publish'
    
    # LG
    alias device='ares-setup-device'
    alias nova='ares-novacom --device tvlg --getkey'
    
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
    alias pm='pushm'
    alias cm='git commit -m'
    alias st='c && git status'
    alias commit='git add . && git commit -m'
    alias cmm='git add . && git commit -m'
    alias pushm='git push origin master'
    alias push='git push origin'
    alias amend='git commit --amend -m'
    alias reset='git reset --soft HEAD~1'
    alias ch='git checkout'
    alias br='git branch'
    alias gc='git clone'
    alias gp='git pull'
    alias gl='git log'
    alias ga='git add'

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
