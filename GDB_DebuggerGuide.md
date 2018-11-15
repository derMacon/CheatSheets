# DGB - Console Debugger for C
**[further information](http://openbook.rheinwerk-verlag.de/linux_unix_programmierung/Kap17-005.htm)**

### Getting started
Command | Explanation
--------| ---------
`gdb <programmname>` | open debugger
`l` | list first n lines of of code (default value = 10)
`l <lineNum>` | See 5 lines before and after given line
`set args <args>` | sets input parameters for the programm
`r` | run debugger
`q` | quit gdb

### Breakpoints
Command | Explanation
--------| ---------
`break <lineNum>` | set breakpoint at line number
`info breakpoints` | get an overview over set breakpoints
`cl <lineNum>` | clear breakpoint at given line number
`dissable <lineNum>` | dissable breakpoint at given line number

### Navigation
`next` | step over
`step` | step into

### See stored data
Command | Explanation
--------| ---------
`print <varName>` | prints the value of the given variable
`whatis <varName>` | gives the type of the given variable
