# git status
alias gs='git status'

# git pull origin ${branch}
alias gp='git pull origin $(git symbolic-ref HEAD 2> /dev/null)'

# git push origin ${branch}
alias gpush='git push origin $(git symbolic-ref HEAD 2> /dev/null)'

# git reset hard
alias grh='git reset --hard'

# git commit
alias ga='git add . && git commit -m'

# git checkoout ${branch}
alias gc='git checkout'

# git branch ${branch}
alias gb='git branch'

# yarn start
alias ns='yarn start'

# yarn install
alias ni='yarn install'
