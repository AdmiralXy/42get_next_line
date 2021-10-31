## get_next_line


### About

The aim of this project is function that returns a line,
read from a file descriptor.

* Calling get_next_line() in a loop will then allow you to read the text
available on the file descriptor one line at a time until the end of it.
* The function behaves well both when reading from a file and when reading from standard input.
* Function get_next_line has undefined behavior when reading from a binary file.

All functions are created in accordance with [Norm](https://github.com/42School/norminette) - the bunch of rules how code should be formatted.

### Requirements & compiling
Project requires:
* C Lang compiler: **gcc** or **clang**

Tested on:
* MacOS 10.15
* Linux Ubuntu 20.04
* Windows 10 | 19042.1288

Compiling:

Program can compile with the flag -D BUFFER_SIZE=xx which will be used
as the buffer size for the read calls in get_next_line().
```
gcc -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c <other_files.c>
```
