call plug#begin('~/.vim/plugged')
Plug 'preservim/nerdtree'
Plug 'vim-airline/vim-airline'
Plug 'pangloss/vim-javascript'
Plug 'sheerun/vim-polyglot'
Plug 'alvan/vim-closetag'
Plug 'neoclide/coc.nvim', {'branch': 'release'}
Plug 'sbdchd/neoformat'
Plug 'vim-airline/vim-airline-themes'

call plug#end()

syntax on
set autoindent 
set number
set ruler

"this is for vim polyglot
set nocompatible

" vim airline themes
let g:airline_theme='fruit_punch'

" python syntax highlighting
let python_highlight_all = 1


" for typescript being cringe
set re=0
