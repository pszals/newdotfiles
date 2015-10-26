# Installation

`git clone git@github.com:pszals/newdotfiles.git`

`ln -s newdotfiles/vim .vim`
`ln -s newdotfiles/vim/vimrc .vimrc`
`ln -s newdotfiles/zsh/zshrc .zshrc`
`ln -s newdotfiles/git/gitconfig .gitconfig`

`cd newdotfiles/vim`
`git submodule init`
`git submodule update`

This assumes that no config files exist. Remove/save them elsewhere for these to take over.
