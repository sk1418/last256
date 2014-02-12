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

**All screenshots were taken from terminal vim 7.4 with tmux under urxvt**

**new `hi-groups`**

![hi-groups](https://raw.github.com/sk1418/sharedResources/master/last256/last256-higroups.png)

**Python**

![python](https://raw.github.com/sk1418/sharedResources/master/last256/last256-python-new.png)

**xml**

![xml](https://raw.github.com/sk1418/sharedResources/master/last256/last256-xml-new.png)

**>>under Solarized terminal color scheme<<**


**Java**

![java](https://raw.github.com/sk1418/sharedResources/master/last256/last256-java-new.png)


**tabbar and vimscript**

![tab](https://raw.github.com/sk1418/sharedResources/master/last256/last256-tab-new.png)

**Diff**

![diff](https://raw.github.com/sk1418/sharedResources/master/last256/last256-diff-new.png)


"  vim: ft=markdown sw=2 ts=2
