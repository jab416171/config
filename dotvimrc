" Turn off backwards compatibility with VI
set nocompatible

syntax on

" Prevents some security exploits. Not sure what modelines are...
set modelines=0

" Set tabs to be TABs that take 3 characters
set shiftwidth=3
set tabstop=3
set autoindent

set encoding=utf-8
set scrolloff=5

" Line numbers relative to where the cursor is
set number
set relativenumber
set ruler

" Create a persistent undo file
set undofile

" Make auto-complete Ctr+space
inoremap <C-space> <C-x><C-o>

"" Improve searching ""

" Make regex more like perl/python
nnoremap / /\v
vnoremap / /\v

" Make search case-insensitive unless there's a capital letter in the search
set ignorecase
set smartcase

" apply substitutions globally on lines. Override with /g
set gdefault

" Highlight search results as you type 
set incsearch
set showmatch
set hlsearch

" Prevent text from wrapping
set nowrap

" \<space> clears search
nnoremap <leader><space> :noh<cr>

" 80char lines
"set textwidth=79
"set colorcolumn=80

" Use textmate whitespace characters
set list
set listchars=tab:▸\ ,eol:¬

" Only allow real-vim navigation
nnoremap <up> <nop>
nnoremap <down> <nop>
nnoremap <left> <nop>
nnoremap <right> <nop>
inoremap <up> <nop>
inoremap <down> <nop>
inoremap <left> <nop>
inoremap <right> <nop>
nnoremap j gj
nnoremap k gk

" Save on focus lost
au FocusLost * :wa

" Sort CSS with \S
nnoremap <leader>S ?{<CR>jV/^\s*\}?$<CR>k:sort<CR>:noh<CR>

"" Split windows

" vertical split with \w 
nnoremap <leader>w <C-w>v<C-w>l

"ctr+h/j/k/l moves around split windows
nnoremap <C-h> <C-w>h
nnoremap <C-j> <C-w>j
nnoremap <C-k> <C-w>k
nnoremap <C-l> <C-w>l

