```
apk add bash bash-completion shadow
```
```
usermod -s /bin/bash user
```
var1
```
chsh -s /bin/bash
cat /etc/passwd | grep $(whoami)
```
var2
```
chsh `username`
```
.bash_profile
```
if [ -f ~/.bashrc ]; then
        . ~/.bashrc
fi
```
.bashrc
```
alias update='apk update && apk upgrade'
export HISTTIMEFORMAT="%d/%m/%y %T "
export PS1='\u@\h:\W \$ '
alias l='ls -CF'
alias la='ls -A'
alias ll='ls -alF'
alias ls='ls --color=auto'
source /etc/bash/bash_completion.sh
export PS1="\[\e[31m\][\[\e[m\]\[\e[38;5;172m\]\u\[\e[m\]@\[\e[38;5;153m\]\h\[\e[m\] \[\e[38;5;214m\]\W\[\e[m\]\[\e[31m\]]\[\e[m\]\\$ "
```
