# My config for vim

## About

This vimrc contains plugins for autocomplete, my favorite colorschemes, syntax highlighting, nerdtree, nerdcomenter, multiple cursors, useful key mappings

## Instalation

Clone repo with `git clone https://github.com/Somed-1/my_vimrc.git`\
Install Plug manager\
Then you need to install `Nodejs` version above 16 and `yarn` gloabaly\
Coc Autocomplete extentions for:
- Python: coc-pyright (`:CocInstall coc-pyright`)
- C/C++: coc-clangd (`:CocInstall coc-clangd`)
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
