# vim-aptfile

Syntax highlighting and folding for the [aptfile](https://github.com/seatgeek/bash-aptfile) filetype.

## Installation

### [vim-plug](https://github.com/junegunn/vim-plug)

- [Install vim-plug](https://github.com/junegunn/vim-plug#installation) in your preferred method.

- Configure your vimrc
```vim
" .vimrc
Plug 'Monster0506/vim-aptfile'
```
- Then, run `:PlugInstall` and reload vim.

### [Pathogen](https://github.com/tpope/vim-pathogen)

- [Install pathogen](https://github.com/tpope/vim-pathogen) in your preferred method.1

- Get the files and configure your vimrc.

```bash
$ cd ~/.vim/bundle
$ git clone https://github.com/Monster0506/vim-aptfile
```

```vim
" .vimrc
execute pathogen#infect()

" for syntax highlighting and setting filetypes
filetype plugin indent on
syntax on
```

Once done, simply open an `aptfile` file, or a file titled `packages`. 


