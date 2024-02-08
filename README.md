# neovim_pluggins
Reference for my current neo vim setup

Spell
https://johncodes.com/posts/2023/02-25-nvim-spell/

    Plug 'sheerun/vim-polyglot'
    https://github.com/sheerun/vim-polyglot
    
    Plug 'junegunn/goyo.vim'
    https://github.com/junegunn/goyo.vim
    https://tracehelms.com/blog/customizing-vim-for-writing
    
    Plug 'preservim/vim-pencil'
    https://github.com/preservim/vim-pencil
    
    Plug 'neoclide/coc.nvim', {'branch': 'release'}
    https://github.com/neoclide/coc.nvim
    https://valentjn.github.io/ltex/vscode-ltex/installation-usage-coc-ltex.html
    
"    Plug 'iamcco/markdown-preview.nvim', { 'do': 'cd app && yarn install' }
    Plug 'nvim-lua/plenary.nvim'
    
    Plug 'nvim-telescope/telescope.nvim', { 'tag': '0.1.5' }
    https://github.com/nvim-telescope/telescope.nvim
    
    Plug 'nvim-telescope/telescope-fzf-native.nvim', { 'do': 'cmake -S. -Bbuild -DCMAKE_BUILD_TYPE=Release && cmake --build build --config Release && cmake --install build --prefix build' }
    
    Plug 'nvim-treesitter/nvim-treesitter', {'do': ':TSUpdate'}
    Plug 'rbgrouleff/bclose.vim'
    Plug 'nvim-tree/nvim-web-devicons'
    
    Plug 'akinsho/bufferline.nvim', { 'tag': '*' } 
    https://github.com/akinsho/bufferline.nvim
    
    Plug 'sainnhe/sonokai'
