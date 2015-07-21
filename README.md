# dotfiles

Michael's configuration files for power tools
* [Vim](http://www.vim.org)/[Neovim](http://neovim.io/)
* [Zsh](http://www.zsh.org)
* [Tmux](http://tmux.github.io)

## How to use ?

If you don't install these power tools, please install them. On MAC OS, it's recommended
to use [brew](http://brew.sh)

```sh
git clone
cd dotfiles
./install.sh
```

## Zsh

zsh is configured with help of [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
Taking MAC OS as an example to show *How to let zsh as default shell on Mac OS ?*

```sh
chsh -s /usr/local/bin/zsh $USER
sudo echo /usr/local/bin/zsh >> /etc/shells
```
