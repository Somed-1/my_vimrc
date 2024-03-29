# My config for vim

## About

This vimrc contains plugins for autocomplete, my favorite colorschemes, syntax highlighting, nerdtree, nerdcomenter, multiple cursors, useful key mappings

## Instalation

Clone repo with `git clone https://github.com/Somed-1/my_vimrc.git` and move `.vimrc` file to your root directory  
Install Plug manager [vim-plug](https://github.com/junegunn/vim-plug  ) so you can install plugins.  
Then you need to install `Nodejs` version above 16 and `yarn` gloabaly  
Open .vimrc file and enter `:PlugInsatll` command  
Coc Autocomplete extentions for:
- Python: coc-pyright (`:CocInstall coc-pyright`)
- C/C++: coc-clangd (`:CocInstall coc-clangd`)
    > Don't forget to install [clangd](https://releases.llvm.org/8.0.0/tools/clang/tools/extra/docs/clangd/Installation.html#:~:text=Installing%20clangd&text=Download%20and%20run%20the%20LLVM%20installer%20from%20releases.llvm.org.&text=The%20clang%2Dtools%20package%20usually%20contains%20an%20old%20version%20of%20clangd.&text=If%20that%20is%20not%20found,tools%2D7%20should%20be%20available.&text=Most%20distributions%20include%20clangd%20in,in%20the%20full%20llvm%20distribution.)
- HTML/CSS: coc-html, coc-css (`:CocInstall coc-html coc-css`)
- JavaScript: coc-tsserver (`:CocInstall coc-tsserver`)
- Json: coc-json (`:CocInstall coc-json`)


## Cheat sheep

### Horizontal movement

 - % - move around two closings ({}, [], (), html tags)
 - $ - end of line
 - _ - start of line (non blank)
 - 0 - start of line
 - f/t<character> - move to character(forward)
 - F/T<character> - move to character(backward)
 - <number>h/l - move cursor n times

### Vertical movement

 - % - move around two closings ({}, [], (), html tags)
 - {} - move by paragraphs (blank lines)
 - ctrl + d/u - move down/up half of page
 - :<number> - move to line
 - <number>j/k - move cursor n times
 - z z/t/b - move page based on cursor

### Macrosses
 - @l - select []
 - @s - select ""
 - @t - select ()
 - @y - copy (gvim)
 - @p - paste (gvim)

### Key mappings
 - <F5> - run python file
 - <F6> - turn on/off mouse
 - <F12> - increase font size (gvim)
 - shift + <F12> - decrease font size (gvim)

 - ctrl + arrows - change window size
 - ctrl + h/j/k/l - move around windows

## Plugins

### NERDtree
 - <F3> - open/close NERDtree (directory tree)
 - R - reload directory
 - cd - change curent directory
 - C - move to directory
 - u - back in directory
 - m - open menu
 - ? - open help

### NERDcommenter
 - ctrl + _ - comment/uncomment line/lines
