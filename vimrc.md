execute pathogen#infect()
set number
set wrap linebreak nolist
syntax on
filetype plugin indent on
set ruler
set laststatus=2
set visualbell
set t_vb=
set shiftwidth=2
set softtabstop=2
set expandtab
set cursorline
set omnifunc=syntaxcomplete#Complete
colorscheme molokai
inoremap " ""<left>
inoremap ' ''<left>
inoremap ( ()<left>
inoremap [ []<left>
inoremap { {}<left>
inoremap {<CR> {<CR>}<ESC>O
inoremap {;<CR> {<CR>};<ESC>O
