# Shell scripts.
The scripts used here are to help me automate repetitive tasks

## Tecnology use
* Bash

## The Tools

| Tool      | Description
| ----------| ----------
| `build`| A tool that compiles C programs with all the necessary flags and warnings. `gcc -Wall -pedantic -Werror -Wextra -std=gnu89`. It takes at least one argument and gives an error if no argument is passed. The script was inspired by `betty` script used by ALX and created by  [Holberton school](https://github.com/holbertonschool/Betty)
| `.vimrc` | vim editor settings to simplifies and making working with C files on the terminal easy. 
| `add`| A tool to replace the long `git add` (file)
|`commit`| A tool to replace `git commit -m` ensures I comment the file name correctly
|`update`| A tool to replace `git commit -m` update message with `git commit -m` update *file name*
|`push`| A tool to replace `git push`

## Known bugs.
The script `build` does not give an error message

## Usage.
Move the script to `$PATH` before using them.
Don't forget to give them excution permissions, use `chmod a+x`
