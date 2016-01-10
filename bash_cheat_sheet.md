#Cheat Sheet for Bash (Media^Alps 2016)#

Command | Flags | Arguments | What it Does
-------- | -------------- | ----------------- | ---------------
`$ ls` | None | None | Lists contents of a directory
 | `-a` | None | Includes hidden files in list of contents
 | `-l` | None | Prints a detailed list of file sizes, permissions, and date last modified
`$ cp` | None | `<source file> <destination>` | Copies the source file to the destination
 | `-i` | `<source file> <destination>` | Interactive mode (to prevent unwanted overwriting)
 | `-R` | `<source file> <destination>` | Recursive mode: includes all folders and files
`$ man` | None | <command> | Display manual page for a given command
`$ mv` | None | `<source file> <destination>`| Moves a file from its source to its destination 
 | `-i` | `<source file> <destination>` | Interactive mode (to prevent unwanted overwriting)
 | `-R` | `<source file> <destination>` | Recursive mode: includes all folders and files