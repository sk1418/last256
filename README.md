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
- Some colors/highlightings was changed, e.g. visual selection, cursorLine, background
(`Normal`) ...
- Some hi-groups were added: `FIXME`, `Important`, `MK1`, `MK2`,
  `MK3`:(screenshot see below section)

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
![hi-groups](https://lh3.googleusercontent.com/-F1OzMBdrQHA/UVRcseDSM_I/AAAAAAAAGrQ/jTaBjj71kEQ/s218/last256-higroups.png)

###Vimscript:
![Vimscript](https://lh5.googleusercontent.com/-5GBEOK5HViI/UVRqQAYiEGI/AAAAAAAAGsg/XWsSI9B2Dn4/s895/last256-vim.png)

###VimHelp:
![VimHelp](https://lh3.googleusercontent.com/-ApXts2uCmD0/UVRqQA0q3UI/AAAAAAAAGsU/PnHjn9lFHrw/s871/last256-vimhelp.png)

###python:
![python](https://lh4.googleusercontent.com/--nyxf6DYOPI/UVRqO9cK-LI/AAAAAAAAGr8/pmoTaSUZmbQ/s853/last256-python.png)

###Java:
![java](https://lh3.googleusercontent.com/-LYYN95PBTw8/UVRqN6cd0_I/AAAAAAAAGro/a7mqEQQ4SVU/s879/last256-java.png)

###Ruby:
![ruby](https://lh3.googleusercontent.com/-0ZYOYL26_Rg/UVRqPBwlj6I/AAAAAAAAGsA/ASQCEjsflW0/s726/last256-ruby.png)

###Shell:
![shell](https://lh5.googleusercontent.com/-k1-q8w7j6jk/UVRqPb1H6eI/AAAAAAAAGsQ/Q0WlgOPWq4M/s1038/last256-shell.png)

###xml:
![xml](https://lh5.googleusercontent.com/-FfhFqNHez3Q/UVRqQpUeqiI/AAAAAAAAGsk/kFyJV81O08A/s882/last256-xml.png)

###HTML:
![html](https://lh5.googleusercontent.com/-THhsu8jcFIU/UVRqNts0zmI/AAAAAAAAGrc/g5aRS410BQo/s1027/last256-html.png)

###Javascript:
![js](https://lh5.googleusercontent.com/-Cmi-c2jBC8A/UVRqN4ODH1I/AAAAAAAAGrw/8NuBDuSzaa4/s750/last256-js.png)

###Markdown:
![md](https://lh5.googleusercontent.com/-aWxAYpuH5ls/UVSUm5bms7I/AAAAAAAAGs4/-f7YX8Ey65o/s735/last256-md.png)

###Diff:
![diff](https://lh6.googleusercontent.com/-DaE61lZYmUY/UVSV-4O1MYI/AAAAAAAAGtE/D3a7oJyqO-k/s843/last256-diff.png)



vim: ft=markdown:sw=2:ts=2
