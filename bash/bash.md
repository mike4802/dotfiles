# Bash files

## Add to ~/.bashrc
```
# for vim style cli operations
set -o vi

# any local binaries go here
export PATH=~/.local:$PATH

# To get nice man page format
export GROFF_NO_SGR=1
export MANPAGER='less -R --use-color -Dd+g -Du+r'
```
