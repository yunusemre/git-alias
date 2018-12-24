#git status
alias gs='git status'

# git pull origin ${branch}
alias gp='git pull origin $(git symbolic-ref HEAD 2> /dev/null)'

#git push origin ${branch}
alias gpush='git push origin $(git symbolic-ref HEAD 2> /dev/null)'

#git reset 
alias grh='git reset --hard'

#git add
alias gc='git add . && git commit -am'

#git checkoout
alias gb='git checkout'
