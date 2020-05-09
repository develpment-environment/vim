# Vim Editor MacOS Solutions

## Preinstalled on HighSierra

- /usr/bin/vim
- outdated

## Building from sources (Recommended)

[how-to](https://www.vim.org/git.php)

- clone 
```
git clone https://github.com/vim/vim.git
```
- build
```
cd src
make distclean  # if you build Vim before
make
sudo make install
```
- update runtime files
```
% cd vimgithub/runtime
% cp -rf * $VIMRUNTIME
```
## Plugins
- [vim-rainbow]
- [vim-cheat40]
- [coc.nvim](https://github.com/neoclide/coc.nvim)
- [nerd-tree]
- [nerd-commenter]
- [lightline]
- [fzf]

- resources:
  - https://opensource.com/article/20/2/how-install-vim-plugins
  


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
