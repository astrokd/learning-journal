# Linux Tutorial pre-work
[RyansTutorials](https://ryanstutorials.net/linuxtutorial/)

### The Command Line

> I will typically have 3 terminals open: 1 in which I do my working, another to bring up ancilliary data and a final one for viewing Manual pages (more on these later).

### Basic Navigation

- `pwd` print working directory (Tells us where we are, current directory)
- `ls [options][location]` lists (Lists what is in our current directory)
	- `ls -l` does a long list
	- `ls [location]` list contents in sub-directory
- `cd [location] change directory (Moves youto another directory)

+ `~` (tilde) shortcut for home dir
+ `.` (dot) reference to current dir
+ `..` (dotdot) reference to parent dir

### About Files
- Everything is a File
- Linux is an extensionless system
- Linux is case sensitive
- Spaces in names (use quotes ' ' or escape characters \  )
- Hidden Files and Directories (`ls -a` lists contents plus hidden files)

### Manual Pages
- `man <command to look up>` Look up commands (q to quit)
- `man -k <search term>` Search for keyword in manual
- `/<term>` Search inside manual page
- `n` Inside manual page search select next found item

### File Manipulation
- `mkdir [options] <Directory>` Make a directory
- `rmdir [options] <Directory>` Remove a directory(that is empty)
- `touch [options] <filename>` Create a blank file
- `cp [options] <source> <destination>` Copy file or directory
- `mv [options] <source> <destination>` Move file or directory (you can also rename with this)
- `rm [options] <file>` Remove a file (and a non empty dir with `-r`)

Note Linux command line has no undo feature

### Cheat Sheet
[Linux Tutorial - Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

[Readme learning journal](README.md)