# Terminal環境構築

1. 必要なソフトウェアをTerminalでインストールする

```
 brew install neovim
 brew install tmux
 brew install rg
 pip3 install -U neovim

 curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
 sh ./installer.sh ~/.vim/dein
```

2. NerdFontのインストール & iTermのフォント設定

  https://www.nerdfonts.com/font-downloads

3. configファイルを設置する
 ~/.config/nvim/init.vim
 ~/.tmux.conf

4. DeinVimインストール時のコンフィグをnvim/init.vimに追記する

5. VimでDein.vimのPluginをインストールする
````
 :call dein#install()
````

