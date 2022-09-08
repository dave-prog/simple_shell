# **Simple Shell Project**



## **Project details**
-----
Welcome to the `Simple Shell` project!! This program is a simple shell that can be compiled and launched from the command line.


## **Syntax**
-----
When using this shell, the syntax for running any command follows the familiar syntax when running a command in any other shell.


## **Builtins**
| Command | Synopsis | Description |
| ------- | -------- | ----------- |
| `alias` | `alias [NAME[='VALUE'] ...]` | Print and define command aliases |
| `cd` | `cd [DIRECTORY]` | Change the current working directory |
| `env` | `env` | Print the environment |
| `exit` | `exit [STATUS]` | Exit the shell |
| `help` | `help [BUILTIN]` | Print a help messages for built-ins | 
| `setenv` | `setenv VARIABLE VALUE` | Set an environment variable |
| `unsetenv` | `unsetenv VARIABLE` | Unset an environment variable |

## List of allowed functions / syscalls
| Functions | Reference |
| --------- | --------- |
| `access` | [man 2 access](https://linux.die.net/man/2/access) |
| `chdir` | [man 2 chdir](https://linux.die.net/man/2/chdir) |
| `close` | [man 2 close](https://linux.die.net/man/2/close) |
| `closedir` | [man 3 closedir](https://linux.die.net/man/3/closedir) |
| `execve` | [man 2 execve](https://linux.die.net/man/2/execve) |
| `exit` | [man 3 exit](https://linux.die.net/man/3/exit) |
| `_exit` | [man 2 \_exit](https://linux.die.net/man/2/_exit) |
| `fflush` | [man 3 fflush](https://linux.die.net/man/3/fflush) |
| `fork` | [man 2 fork](https://linux.die.net/man/2/fork) |
| `free` | [man 3 free](https://linux.die.net/man/3/free) |
| `getcwd` | [man 3 getcwd](https://linux.die.net/man/3/getcwd) |
| `getline` | [man 3 getline](https://linux.die.net/man/3/getline) |
| `isatty` | [man 3 isatty](https://linux.die.net/man/3/isatty) |
| `kill` | [man 2 kill](https://linux.die.net/man/2/kill) |
| `malloc` | [man 3 malloc](https://linux.die.net/man/3/malloc) |
| `open` | [man 2 open](https://linux.die.net/man/2/open) |
| `opendir` | [man 3 opendir](https://linux.die.net/man/3/opendir) |
| `perror` | [man 3 perror](https://linux.die.net/man/3/perror) |
| `read` | [man 2 read](https://linux.die.net/man/2/read) |
| `readdir` | [man 3 readdir](https://linux.die.net/man/3/readdir) |
| `signal` | [man 2 signal](https://linux.die.net/man/2/signal) |
| `stat` | [(\_\_xstat) man 2 stat](https://linux.die.net/man/2/stat) |
| `lstat` | [(\_\_lxstat) man 2 lstat](https://linux.die.net/man/2/lstat) |
| `fstat` | [(\_\_fxstat) man 2 fstat](https://linux.die.net/man/2/fstat) |
| `strtok` | [man 3 strtok](https://linux.die.net/man/3/strtok) |
| `wait` | [man 2 wait](https://linux.die.net/man/2/wait) |
| `waitpid` | [man 2 waitpid](https://linux.die.net/man/2/waitpid) |
| `wait3` | [man 2 wait3](https://linux.die.net/man/2/wait3) |
| `wait4` | [man 2 wait4](https://linux.die.net/man/2/wait4) |
| `write` | [man 2 write](https://linux.die.net/man/2/write) |


## **Environment**
---
* Language: C
* OS: Ubuntu 20.04 LTS
* Compiler: gcc
* Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

## **How To Install, Compile, and Use**
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

## Tasks
### Mandatory:
1. README, man, AUTHORS
- Write a README
- Write a man for your shell.
- You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.

2. Simple shell 0.1
- Write a UNIX command line interpreter.
- Your Shell should:
Display a prompt and wait for the user to type a command. A command line always ends with a new line.
The prompt is displayed again each time a command has been executed.
The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
The command lines are made only of one word. No arguments will be passed to programs.
If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
You have to handle the “end of file” condition (Ctrl+D)
- You don’t have to:
use the PATH
implement built-ins
handle special characters : ", ', `, \, *, &, #
be able to move the cursor
handle commands with arguments

3. Simple shell 0.2
- Handle command lines with arguments

4. Simple shell 0.3
- Handle the PATH

5. Simple shell 0.4
- Implement the exit built-in, that exits the shell
- Usage: exit
- You don’t have to handle any argument to the built-in exit

6. Simple shell 1.0
- Implement the env built-in, that prints the current environment

7. Write a blogpost "What happens when you type ls -l in the shell"

### Advanced
1. Test suite 
- Contribute to a test suite for your shell

2. Simple shell 0.2.1
- Write your own strtok function

3. Simple shell 0.4.1
- handle arguments for the built-in exit

4. Simple shell 0.4.2
- Handle Ctrl+C: your shell should not quit when the user inputs ^C

5. setenv, unsetenv
- Implement the setenv and unsetenv builtin commands

6. cd
- Implement the builtin command cd

7. ;
- Handle the commands separator ;

8. alias 
- Implement the alias builtin command

19. Comments
- Handle comments (#)

10. help 
- Implement the help built-in

11. File as an input 
- Your shell should take a file as a command line argument


## **Authors**
---
#### [Olanrewaju David](https://github.com/dave-prog)
#### [Musana Yusuf](https://github.com/HOURIZ)
