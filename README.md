# .vimrc config
<hr>

```vim
"  whoxer vimrc |
"  --------------

set number
set mouse=a
set title
set cursorline

set encoding=utf-8

let g:ycm_global_ycm_extra_conf = '~/.vim/.ycm_extra_conf.py'
set completeopt-=preview
let g:ycm_show_diagnostics_ui = 0

map q :quit<CR>
map <C-t> :NERDTreeToggle<CR>
map <C-s> :write<CR> "echo 'stty -ixon' >> ~/.bashrc && exec $SHELL'

let g:ycm_language_server =
  \ [{
  \   'name': 'ccls',
  \   'cmdline': [ 'ccls' ],
  \   'filetypes': [ 'c', 'cpp', 'cuda', 'objc', 'objcpp' ],
  \   'project_root_files': [ '.ccls-root', 'compile_commands.json' ]
  \ }]

let g:ycm_clangd_args=['--header-insertion=never']
let g:ycm_key_list_select_completion = ['<C-n>', '<Down>']
let g:ycm_key_list_previous_completion = ['<C-p>', '<Up>']
let g:SuperTabDefaultCompletionType = '<C-n>'
let g:UltiSnipsExpandTrigger = "<tab>"
let g:UltiSnipsJumpForwardTrigger = "<tab>"
let g:UltiSnipsJumpBackwardTrigger = "<s-tab>"

call plug#begin('~/.vim/plugged')
	Plug 'vim-airline/vim-airline'
	Plug 'preservim/nerdtree'
	Plug 'tpope/vim-surround'
	Plug 'junegunn/vim-easy-align'
	Plug 'https://github.com/jiangmiao/auto-pairs.git'
	Plug 'rainglow/vim'
	Plug 'ycm-core/YouCompleteMe'
	Plug 'jiangmiao/auto-pairs'
	Plug 'SirVer/ultisnips'
	Plug 'honza/vim-snippets'
	Plug 'ervandew/supertab'
call plug#end()

```
<hr>
<h3>desktop</h3>

```c
/*
                    -`                    whoxer@arch-wox 
                  .o+`                   --------------- 
                 `ooo/                   OS: Arch Linux x86_64 
                `+oooo:                  Host: S14BW01 1.20.X 
               `+oooooo:                 Kernel: 6.3.1-arch2-1 
               -+oooooo+:                Uptime: 3 hours, 58 mins 
             `/:-:++oooo+:               Packages: 929 (pacman), 26 (flatpak) 
            `/++++/+++++++:              Shell: bash 5.1.16 
           `/++++++++++++++:             Resolution: 1366x768 
          `/+++ooooooooooooo/`           DE: Plasma 5.27.5 
         ./ooosssso++osssssso+`          WM: kwin 
        .oossssso-````/ossssss+`         WM Theme: Utterly-Round-Dark 
       -osssssso.      :ssssssso.        Theme: [Plasma], Breeze [GTK2/3] 
      :osssssss/        osssso+++.       Icons: breeze-dark [Plasma], breeze-dark [GTK2/3] 
     /ossssssss/        +ssssooo/-       Terminal: konsole 
   `/ossssso+/:-        -:/+osssso+-     CPU: Intel Celeron N3010 (2) @ 2.240GHz 
  `+sso+:-`                 `.-/+oso:    GPU: Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx 
 `++:.                           `-/+/   Memory: 2369MiB / 3774MiB 
 .``                                 `/
*/
```
<details>
 <summary>contato</summary>
 <ul>
  <li>e-mail: natanaelvsant@gmail.com</li>
  <li>
   instagram: <a href="https://instagram.com/natanaelv1eira">whoxer</a>
  </li>
  <li> 
   twitter: <a href="https://twitter.com/Natanaelv1eira">Natanaelv1eira</a>
  </li>
 </ul>
</details>
