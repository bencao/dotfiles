配置文件说明
============

常用配置文件，部分参考了[YARD](https://github.com/skwp/dotfiles)

Vim安装流程
-----------

0. 安装[Macvim](https://github.com/b4winckler/macvim/wiki/FAQ):

```
brew install macvim --custom-icons --override-system-vim --with-lua --with-luajit --HEAD
```

1. 安装[vundle](https://github.com/gmarik/Vundle.vim):

```
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

2. 建立软连接:

```
cd ~ && ln -s ~/.dotfiles/vimrc .vimrc && ln -s ~/.dotfiles/gvimrc .gvimrc
```

3. 安装插件, 打开vim执行`:PluginInstall`

4. 需要进入插件vimproc的目录运行`make`
