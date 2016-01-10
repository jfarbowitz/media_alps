#Cheat Sheet for Bash (Media^Alps 2016)#

Command | Flags | Arguments | What it Does
-------- | -------------- | ----------------- | ---------------
`$ ls` | None | None | Lists contents of a directory
 | `-a` | None | Includes hidden files in list of contents
 | `-l` | None | Prints a detailed list of file sizes, permissions, and date last modified
 | `-R` | None | Prints the content of all the folders included in the directory
`$ cp` | None | `<source file> <destination>` | Copies the source file to the destination
 | `-i` | `<source file> <destination>` | Interactive mode (to prevent unwanted overwriting)
 | `-R` | `<source file> <destination>` | Recursive mode: includes all folders and files
`$ man` | None | <command> | Display manual page for a given command
 `>` | None | before the redirect <command> after the redirect <output file> | "mean": redirects output to a file and overwrites content if the file is already existing
`|` | None | None | takes the output of one command and puts it into another