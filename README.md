# Installation

Start by cloning the dotfiles: `git clone git@github.com:pszals/newdotfiles.git`

Install Zsh using Homebrew: `brew install zsh`

Make Zsh your default shell: `chsh -s $(which zsh)`

Get oh-my-zsh: `git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh`

Install the Zsh dotfiles: `ln -s newdotfiles/zsh/zshrc ~/.zshrc`

Configure Git: `ln -s newdotfiles/git/gitconfig ~/.gitconfig`

## VIM

Move the current configuration folders somewhere safe: 

`mv ~/.vim ~/.vim`

`mv ~/.vimrc ~/.vimrc`

Link up the new configs:

`ln -s newdotfiles/vim ~/.vim`

`ln -s newdotfiles/vim/vimrc ~/.vimrc`

Use the config submodules:

`cd newdotfiles/vim`

`git submodule init`

`git submodule update`

## Atom

Move the current atom configuration somewhere safe: `mv ~/.atom ~/.atom_old`

Link the config folder from the dotfiles: `ln -s newdotfiles/tagatom/atom ~/.atom`
