vim settings step
=================

##### Depend Package

    brew install vim git npm ctags
    sudo npm -g install instant-markdown-d jshint
    sudo pip install isort jedi yapf flake8 virtualenvwrapper autopep8

##### Usage

- install vundle

    ```bash
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    ```

- config vim

    copy `.vimrc` and exec `:PluginInstall`

- jedi-vim bugfix [issues721](https://github.com/davidhalter/jedi-vim/issues/721)

    ```
    cd ~/.vim/bundle/jedi-vim
    git checkout e2d79c6434f940a21c75bb86d84b9a4d88f86209
    ```
