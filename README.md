# Simple Shell Project



## Project details
-----
Welcome to the `Simple Shell` project!! This program is a simple shell that can be compiled and launched from the command line.


## Syntax
-----
When using this shell, the syntax for running any command follows the familiar syntax when running a command in any other shell.


## Builtin Commands
-----
This shell supports a variety of commands:

`alias` - create or list an alias

`cd` - change directory

`env` - list the current environment variables

`exit` - exit the shell

`history` - display the command history for the current shell session

`setenv` - sets an environment variable

`unsetenv` - unsets an environment variable



## Files
-----
Brief description of every file in this repository. Subject to change.

| Helper File | Description |
| --- | --- |
| AUTHORS | Text file containing the contributing authors |
| prompt.c | handles outline of shell's reprompting and executing |
| non_interactive.c | handles output when shell is called outside of shell |
| _realloc.c| helper function handles reallocation |
| _strcat.c | concatenates two strings |
| _strcmp.c | compares if two strings match |
| _strcpy.c | copies a string |
| _strdup.c | duplicates a string |
| _str_tok.c | (custom) tokenizes user's command input and returns array |
| c_str_tok.c | tokenizes PATH to include ":" as Null, checks current dir |
| get_line.c | (custom) reads user's typed input into buffer |
|_which.c | appends command to PATHs, fleshes paths out, returns match |
| _cd.c | changes directories |
| linked_lists.c | adds and deletes nodes; prints and frees linked list |
| get_env.c |finds and returns copy of environmental variable |
| env_linked_list.c | prints and creates linked list of envrionmental variables |
| set_unset_env.c | finds environment variable index node, sets and unsets |
| free_double_ptrc.c | frees double pointers (user's command, arrays) |
| _execve.c | executes and frees command, then exits program |
| __exit.c | handles if user types exit or exit(value) |
| int_to_string.c | converts int to string to write error messages |
| print_error.c | prints special error messages for certain fails |


## Environment
---
* Language: C
* OS: Ubuntu 20.04 LTS
* Compiler: gcc
* Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

## How To Install, Compile, and Use
---
Install and Compile
```
(your_terminal)$ git clone https://github.com/MelissaN/simple_shell.git
(your_terminal)$ cd simple_shell
(your_terminal)$ gcc -Wall -Werror -Wextra -pedantic -Wno-format *.c -o simple_shell
```
**Non-Interactive Mode**
```
echo "ls -l" | ./simple_shell
```
**Interactive Mode***
Activate the shell
```
(your_terminal)$ ./simple_shell
$
```
Sample Usage
```
$ ls -al
total 4
-rw-rw-r-- 1 vagrant vagrant   234 Mar 28 19:32 file1.c
-rw-rw-r-- 1 vagrant vagrant    69 Mar 28 19:32 file2.c
$ echo "This is a pretty cool!"
This is pretty cool!
$ man ./man_1_simple_shell (opens our manpage for more information)
```
Stop and return to your original shell
```
$ exit
(your_terminal)$
```


## To Do
* More functionality can still be added (e.g. handle aliases, pipelines, and redirections)

## Authors
---
### [Olanrewaju David](https://github.com/dave-prog)
-
### Musana Yusuf
-
