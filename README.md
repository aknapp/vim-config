# aknapp's vim config

## usage:

1. git clone the repository somewhere, and symlink ~/.vim to it:

```bash
    git clone git@github.com:aknapp/vim-config.git ~/code/vim-config
    ln -s ~/code/vim-config ~/.vim
```

2. update the submodules:

```bash
    cd ~/.vim
    git submodule update --init
```

3. symlink your .vimrc to the vimrc file in this repo:

```bash
    ln -s ~/code/vim-config/vimrc ~/.vimrc
```

4. that's it!
