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
`G` | Move to bottom of the page
`[lineNum] + G` | goto line  
g + g | Move to beginning of the file
`+` | Move to first non whitespace character
`-` | Move to first non whitespace character of previous line
two apostrophes | Move back to last position of the cursor
`A` | Move to eol and switch into insert mode
`{` | Previous paragraph
`}` | next paragraph
Backspace | move one character to the back
Space | move on character to the front
`a` | positions the corsor behind the char it was hovering over in normal mode
`[m` | go to function head of the current function
`]m` | go to function head of the next function

### Delete
Commands | Explanation
---------| ----------
`d` | delete selection 
`D` | delete till eol
`dG` | delete all lines
`dd` | delete current line
`x` | delete next character

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
`ciw`| copy and delete current word
`diw` | delete current word

### Edit
Commands | Explanation
---------| ----------
`o` | open new line below cursor
`O` | open new line above cursor
`%s/[patternToReplace]/[strToReplaceWith] | Search and replace whole doc
`[upperLineNum],[lowerLineNum]s/[patternToReplace]/[strToReplaceWith] | Search and replace portion of doc

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

