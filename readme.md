# install nvim

```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
```

# install vim-plug

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

# install node

```
wget https://nodejs.org/download/release/v15.14.0/node-v15.14.0-linux-x64.tar.xz
```
export `node-v15.14.0-linux-x64/bin` to PATH

# config

copy `init.vim` into `~/.config/nvim/init.vim`

