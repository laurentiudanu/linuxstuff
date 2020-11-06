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
:nnoremap <C-e> <C-w>
autocmd StdinReadPre * let s:std_in=1
autocmd VimEnter * if argc() == 0 && !exists("s:std_in") | NERDTree | endif
let NERDTreeMapOpenInTab='\r'
nmap <F3> :NERDTreeToggle<CR>
