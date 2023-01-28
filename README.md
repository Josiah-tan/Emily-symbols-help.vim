# Emily symbols help

help docs for Emily symbols in vim (because I don't want to keep looking at the poster)

# install

## vim-plug

```vim
plug "Emily-symbols-help.vim"
```

# usage

```vim
:help Emily-symbols-help
```

# developers

feel free fork and make changes:

```vim
if isdirectory(expand("~/Emily-symbols-help.vim/"))
	" set rtp+=~/plover-vim-tutor/
	Plug '~/Emily-symbols-help.vim/'
else
	Plug 'Josiah-tan/Emily-symbols-help.vim'
endif
```
