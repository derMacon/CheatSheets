# Vim Commands
![VimOverview](https://github.com/derMacon/CheatSheets/blob/master/vi-vim-cheat-sheet.gif)
### Navigation
Commands | Explanation
-------- | -------
z + z | Move current line in the middle of the screen
z + t | Move current line to the top of the screen 
z + b | Move current line to the bottom of the screen 
Ctrl + y | Move Screen up one line 
Ctrl + e | Move Screen down one line 
Ctrl + b | Move Screen up one page
Shift + G | Move to bottom of the page
g + g | Move to beginning of the file

### Delete
Commands | Explanation
---------| ----------
`dG` | delete all lines
`dd` | delete current line

### Copy / Paste
Commands | Explanation
---------| ----------
`v` | enter character selection mode 
`V` | enter line selection mode
`y` | copy selection
`yy` | copy current line 
`d` | cut selection
`dd` | cut current line 
`p` | paste after cursor
`P` | paste before cursor

### Save
Command | Explanation
-------- | -------
: + w | save file 
: + w + q | save and quit 
u | undo changes
Ctrl + r | redo undone changes
: + q + ! | quit without saving

### Settings
Command | Explanation
-------- | -------
In terminal type `vim .vimrc` | safe settings for all instances
:set mouse=a | Settup mouse 
:colorscheme elflord | Change theme to elflord theme
:set number | setsup line numbers
:set tabstop=<num> | set tabstop size to <num> chars

For Markdown syntax: [sourceforge.net](https://sourceforge.net/p/tabulator/wiki/markdown_syntax/#md_ex_tables)
