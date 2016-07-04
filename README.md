# 💕

```sh
$ cd ~
$ git clone https://github.com/jlobos/dotfiles.git
$ mv dotfiles .dotfiles
```

### Base16 Shell

```
$ cd ~/.dotfiles/
$ git clone https://github.com/chriskempson/base16-shell.git config/base16-shell
```

## arch (master)

```bash
ln -s ~/.dotfiles/bashrc ~/.bashrc
ln -s ~/.dotfiles/config/git/gitconfig ~/.gitconfig
ln -s ~/.dotfiles/config/i3/config ~/.config/i3/config
ln -s ~/.dotfiles/config/nvim/init.vim ~/.config/nvim/init.vim
ln -s ~/.dotfiles/config/termite/config ~/.config/termite/config
```

## termux (android)

```sh
$ cd /data/data/com.termux/files/usr/etc/
$ echo 'source ~/.dotfiles/bashrc' >> bash.bashrc
$ ln -s ~/.dotfiles/bashrc ~/.bashrc
$ ln -s ~/.dotfiles/config/git/gitconfig ~/.gitconfig
$ ln -s ~/.dotfiles/config/nvim/init.vim ~/.config/nvim/init.vim
```
