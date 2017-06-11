vim settings step
=====

##### Depend Package

    brew install vim git npm ctags
    sudo npm -g install instant-markdown-d jshint
    sudo pip install isort jedi yapf flake8 virtualenvwrapper autopep8

##### Usage

- install vundle

    `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

- config vim

    copy `.vimrc` and exec `:PluginInstall`
