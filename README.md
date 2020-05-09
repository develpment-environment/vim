# Vim Editor MacOS Solutions

## Preinstalled on HighSierra

- /usr/bin/vim
- outdated

## Installing with brew

- 

## mvim

- download: https://github.com/macvim-dev/macvim/releases/latest
- install
- make default
```
sudo ln -s /Applications/MacVim.app/Contents/bin/mvim /usr/local/bin/mvim
```
- add to ~/.bash_profile or ~/.zshrc
```
# ----------------------
# MacVim alias
# ----------------------
# use mvim as a default text editor, assuming you already have mvim installed
alias vim="mvim -v" 
```
