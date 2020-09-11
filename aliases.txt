alias lt='ls --human-readable --size -1 -S --classify'

alias mnt="mount | awk -F' ' '{ printf \"%s\t%s\n\",\$1,\$3; }' | column -t | egrep ^/dev/ | sort"

alias gh='history|grep'

alias left='ls -t -1'

alias count='find . -type f | wc -l'

alias ve='python3 -m venv ./venv'
alias va='source ./venv/bin/activate'

alias cpv='rsync -ah --info=progress2'

alias studio=studio.sh
alias stold=studio-old.sh

alias gs="git status"
alias ga="git add"
alias gaa="git add -A"
alias gca="git commit -a"
alias gcm="git commit -m"
alias gchko="git checkout"
alias gchkob="git checkout -b"
alias gpuo="git push -u origin"
alias gca="git commit --amend"
alias grsth="git reset --hard"
alias grsthh="git reset HEAD --hard"
alias gchpk="git cherry-pick"
alias gchpka="git cherry-pick --abort"
alias gchpkc="git cherry-pick --continue"
alias gdf="git diff"
alias gf="git fetch"
alias gpl="git pull"
alias gm="git merge"
alias gb="git branch"

alias sau="sudo apt update"
alias sagu="sudo apt-get update"
alias sagi="sudo apt-get install"

alias clr='clear'

alias src='source ~/.bashrc'

alias tcn='mv --force -t ~/.local/share/Trash '
