# Fo'sshL - The best SSH client that doesn't exist.. 

Until now. 

## Bash 
vim ~/.bash_aliases

alias fosshl=/usr/bin/ssh 

vim ~/.bash_profile 

if [ -f ~/.bash_aliases ]; then
   source ~/.bash_aliases
fi
