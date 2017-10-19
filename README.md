1 Installation:

    git clone git://github.com/julianneeleman/env.git ~/.env

2 Create symlinks

    ln -s ~/.env/vim/vimrc ~/.vimrc
    ln -s ~/.env/vim ~/.vim
    ln -s ~/.env/gitconfig ~/.gitconfig
    ln -s ~/.env/zshrc ~/.zshrc
    ln -s ~/.env/oh-my-zsh ~/.oh-my-zsh
    ln -s ~/.env/zsh-completions ~/.oh-my-zsh/custom/plugins/zsh-completions

3 Fetch submodules

    cd ~/.env
    git submodule init
    git submodule update

4 Change default shell (requires reboot)

    chsh -s /bin/zsh
