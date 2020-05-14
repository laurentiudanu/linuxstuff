execute pathogen#infect()
set number
set wrap linebreak nolist
syntax on
set ruler
set laststatus=2
set visualbell
set shiftwidth=2
set softtabstop=2
set expandtab
set cursorline
filetype plugin on
set omnifunc=syntaxcomplete#Complete
inoremap " ""<left>
inoremap ' ''<left>
inoremap ( ()<left>
inoremap [ []<left>
inoremap { {}<left>
inoremap {<CR> {<CR>}<ESC>O
inoremap {;<CR> {<CR>};<ESC>O
