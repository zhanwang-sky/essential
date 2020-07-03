# essential

## build essential
* OS X
    * xcode-select --install
    * install Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
* Ubuntu\
`sudo apt install build-essential`

## Vim
(Usage: PluginInstall!)
1. setup Vundle\
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
2. install ctags\
`brew install ctags`\
`sudo apt install exuberant-ctags`
3. (optional) install powerline fonts\
`https://github.com/powerline/fonts.git ("Droid Sans Mono Dotted for Powerline" is preferred)`

## tofrodos
* OS X\
`brew install tofrodos`
* Ubuntu\
`sudo apt install tofrodos`

## Rust
`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`\
notice: it will modify ~/.zprofile and ~/.profile according to your system type.
