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
`>>`| None | `before the redirect should be another command, after the redirect <destination file>` | Creates a new file if it doesn't exist yet, if the file exists it adds the message 
	