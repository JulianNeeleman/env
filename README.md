Installation:

    git clone git://github.com/julianneeleman/env.git ~/.env

Create symlinks:

    ln -s ~/.env/vim/vimrc ~/.vimrc
    ln -s ~/.env/vim ~/.vim
    ln -s ~/.env/gitconfig ~/.gitconfig

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.env
    git submodule init
    git submodule update
