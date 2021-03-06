# vim-dotfiles
## For dotfile management:
https://github.com/RichiH/vcsh

Initialize:
```sh
vcsh init vim
vcsh vim remote add origin <remote>
vcsh vim pull origin master
```
# Neovim mac guide

## Install neovim with brew
https://github.com/neovim/neovim
```
brew tap neovim/neovim
brew install --HEAD neovim
```

## Install neobundle
```
curl https://raw.githubusercontent.com/Shougo/neobundle.vim/master/bin/install.sh > install.sh
sh ./install.sh
```

## Install pip
`sudo easy_install pip`

## Install neovim with python
`pip install neovim`

## Initialize nvim plugins
Simply open `nvim` for the first time - plugins declared in this projects configuration file will be downloaded and installed.

## Install the silver searcher
`brew install the_silver_searcher`

## Install YouCompleteMe
```sh
cd ~/.config/nvim/bundle/YouCompleteMe
./install.sh
```

## To run tests with shortcut
`sudo chmod ugo-x /usr/libexec/path_helper`

## Install universal-tags
`https://github.com/universal-ctags`

