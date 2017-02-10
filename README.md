# Installation

Start by cloning the dotfiles: `git clone git@github.com:pszals/newdotfiles.git`

Install Zsh using Homebrew: `brew install zsh`

Make Zsh your default shell: `chsh -s $(which zsh)`

Get oh-my-zsh: `git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh`

Install the Zsh dotfiles: `ln -s newdotfiles/zsh/zshrc ~/.zshrc`

Configure Git: `ln -s newdotfiles/git/gitconfig ~/.gitconfig`

## VIM

`ln -s newdotfiles/vim ~/.vim`

`ln -s newdotfiles/vim/vimrc ~/.vimrc`

`cd newdotfiles/vim`

`git submodule init`

`git submodule update`

This assumes that no config files exist. Remove/save them elsewhere for these to take over.
