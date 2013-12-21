A vim 256color scheme

	    __               __     ___   ___________
	   / /   ____ ______/ /_   |__ \ / ____/ ___/
	  / /   / __ `/ ___/ __/   __/ //___ \/ __ \ 
	 / /___/ /_/ (__  ) /_    / __/____/ / /_/ / 
	/_____/\__,_/____/\__/   /____/_____/\____/  
	

#Introduction

last256 is a dark vim color-scheme, it was created based on
[vim-hybrid](https://github.com/w0ng/vim-hybrid).

- Xresource color supports was removed
- Some colors/highlightings were changed, e.g. visual selection, cursorLine, background (`Normal`) ...
- Some hi-groups were added: `FIXME`, `Important`, `MK1`, `MK2`, `MK3`:(screenshot see below section)

		autocmd BufWinEnter * call matchadd("Important","!Important!")
		autocmd BufWinEnter * call matchadd("MK1","!MARK1")
		autocmd BufWinEnter * call matchadd("MK2","!MARK2")
		autocmd BufWinEnter * call matchadd("MK3","!MARK3")
		autocmd BufWinEnter * call matchadd("FIXME","FIXME")

#Requirements

- gvim7.3 (linux, windows and Mac)
- vim7.3 on Terminal, a 256 color enabled terminal is required

#Screenshots

for a colorscheme readme, **screenshots** might be the most important section:

**All screenshots were taken from terminal vim 7.3 with tmux under urxvt**

###new `hi-groups`:
![hi-groups](https://raw.github.com/sk1418/sharedResources/master/last256/last256-higroups.png)

###Vimscript:
![Vimscript](https://raw.github.com/sk1418/sharedResources/master/last256/last256-vim.png)

###VimHelp:
![VimHelp](https://raw.github.com/sk1418/sharedResources/master/last256/last256-vimhelp.png)

###python:
![python](https://raw.github.com/sk1418/sharedResources/master/last256/last256-python.png)

###Java:
![java](https://raw.github.com/sk1418/sharedResources/master/last256/last256-java.png)

###Ruby:
![ruby](https://raw.github.com/sk1418/sharedResources/master/last256/last256-ruby.png)

###Shell:
![shell](https://raw.github.com/sk1418/sharedResources/master/last256/last256-shell.png)

###xml:
![xml](https://raw.github.com/sk1418/sharedResources/master/last256/last256-xml.png)

###HTML:
![html](https://raw.github.com/sk1418/sharedResources/master/last256/last256-html.png)

###Javascript:
![js](https://raw.github.com/sk1418/sharedResources/master/last256/last256-js.png)

###Markdown:
![md](https://raw.github.com/sk1418/sharedResources/master/last256/last256-md.png)

###Diff:
![diff](https://raw.github.com/sk1418/sharedResources/master/last256/last256-diff.png)



"  vim: ft=markdown sw=2 ts=2
