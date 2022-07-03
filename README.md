<p align="center">
    <img alt="shirotelin logo" src="./images/shirotelin.png" height="200" />
    <h2 align="center">shirotelin</h2>
    <p align="center">shirotelin is Ultimate standard light colorscheme for Vim and Neovim!</p>
</p>

![reviewdog](https://github.com/yasukotelin/shirotelin/workflows/reviewdog/badge.svg)

- Supports Windows, macOS and Linux!
- Supported CUI and GUI.

<table>
    <tr>
        <th>NeoVim (MacOS)</th>
    </tr>
    <tr>
        <td><img src="images/shirotelin-macos.png"></td>
    </tr>
    <tr>
        <th>GVim (Windows)</th>
    </tr>
    <tr>
        <td><img src="images/shirotelin-windows-gvim.png"></td>
    </tr>
</table>

## shirotelin family!

- for Terminal.app ([yasukotelin/shirotelin-terminal-app](https://github.com/yasukotelin/shirotelin-terminal-app))
- for JetBrains IDE ([yasukotelin/shirotelin-intellij](https://github.com/yasukotelin/shirotelin-intellij))
- for Visual Studio Code ([yasukotelin/shirotelin-vscode](https://github.com/yasukotelin/shirotelin-vscode))
- for Kakoune ([esessoms/shirotelin-kakoune](https://github.com/esessoms/shirotelin-kakoune))
- for Emacs ([esessoms/shirotelin-theme](https://github.com/esessoms/shirotelin-theme))
- for iTerm2 ([tatsuya4559/shirotelin-iterm2](https://github.com/tatsuya4559/shirotelin-iterm2))

## Supported Plugins Color⛏

- [✔] Markdown https://github.com/plasticboy/vim-markdown
- [✔] lightline.vim https://github.com/itchyny/lightline.vim
- [✔] NERDTree https://github.com/preservim/nerdtree
- [✔] NERDTree + vim-devicons https://github.com/ryanoasis/vim-devicons
- [✔] dart-vim-plugin https://github.com/dart-lang/dart-vim-plugin
- [✔] vim-lsp https://github.com/prabirshrestha/vim-lsp
- [✔] coc.nvim https://github.com/neoclide/coc.nvim
- [✔] coc-flutter https://www.npmjs.com/package/coc-flutter
- [✔] vim-go https://github.com/fatih/vim-go
- [✔] vim-clap https://github.com/liuchengxu/vim-clap

## Install

If you use any vim plugin manager, refer to the following.

**vim-plug**

```vim
Plug 'yasukotelin/shirotelin'
```

**dein.vim**

```vim
call dein#add('yasukotelin/shirotelin')
```

**Manual Install**

If you want to manual install, you download `colors/shirotelin.vim` and puts on your `~/.vim/colors` directory.

Finally, Write to your `.vimrc` or `init.vim`.

```vimrc
colorscheme shirotelin
```

## Settings

If you want to show the Tab, white space, and EOL, you write a like below to `.vimrc` or `init.vim`.
shirotelin shows nice them.

```
set list
set listchars=tab:»-,eol:↲,extends:»,precedes:«,space:.
```

![](./images/shirotelin-list.png)

If you want to show the cursorline, you write this.
shirotelin's cursorline is underline.

```
set cursorline
```

You doesn't want to show the cursorline. You write this.

```
set nocursorline
```

## Screenshots

### Complete

Complete and popup are simple and classical color 😍

<img src="images/complete.gif">

### TODO

TODO is highlighted with background Green.

<img src="images/todo.png">


### Diff

Supported diff color 🤷‍♂️

<img src="images/shirotelin-diff.png">

## Supported Plugins

I add colors for plugins actively.

### Markdown

https://github.com/plasticboy/vim-markdown

<img src="./images/shirotelin-markdown.png" alt="shirotelin for Markdown">

### lightline.vim

https://github.com/itchyny/lightline.vim

If you use lightline.vim, you can write the below code in your .vimrc and use shirotelin colorscheme on lightline!

```vim
let g:lightline = {
      \ 'colorscheme': 'shirotelin',
      \ }
```

<img src="./images/lightline.png" alt="shirotelin for lightline.vim">

### NERDTree

https://github.com/scrooloose/nerdtree

<img src="images/shirotelin-nerd-tree.png" alt="shirotelin for NERDTree">

#### with vim-devicons

https://github.com/ryanoasis/vim-devicons

<img src="images/shirotelin-nerd-tree-with-vim-devicons.png" alt="shirotelin for NERDTree with vim-devicons">

### dart-vim-plugin

https://github.com/dart-lang/dart-vim-plugin

<img src="images/shirotelin-dart-vim-plugin.png" alt="shirotelin for dar-vim-plugin">

### coc.nvim

Supported for [coc.nvim](https://github.com/neoclide/coc.nvim).<br>

<img src="images/coc-nvim.gif" alt="shirotelin for coc.nvim">

### coc-flutter

Supported for Closing Label on the [coc-flutter](https://www.npmjs.com/package/coc-flutter)

> **NOTE** Closing Label is supported on only Neovim.

![](./images/coc-flutter-closinglabel.png)

### vim-go

Supported for [vim-go](https://github.com/fatih/vim-go)

> **NOTE** vim-go default config is a less highlited. If you want to more highlight, you can refer vim-go WIKI pages and setting them.

![](./images/shirotelin-vim-go.png)

### vim-clap

Supported for [vim-clap](https://github.com/liuchengxu/vim-clap)

![](./images/vim-clap.png)

## Licence

MIT Licence

## Author

yasukotelin
