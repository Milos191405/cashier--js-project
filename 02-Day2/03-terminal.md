## Terminal

- The terminal is a text interface to your computer
- Often refered to as the shell, bash, console, prompt and various other names
- Learning how to use terminal can increase your productivity
- It makes computing a lot of fun!

### Nomenclature

- Command:
    - A keyword or name of a program that you can use in a terminal,
        to perform a specific task or operation.

- Argument: 
    - Additional information provided to a command

- Options: 
    - Also known as 'flags' or 'switches', 
        these are special arguments prefixed (usually) by a dash (-) or double dash (--)
    - Options modify the behavior of a command
    - They are not always required
    - When used, they provide additional instructions or settings to the command

## Linux File System
- Linux/Unix uses a tree-like hierarchical file system, 
    with the top node of the system being the root or simply "/"
- There are no drives in Linux
- Linux/Unix file naming convention is case sensitive. 
    Thus, sample and SAMPLE are 2 different files in Linux/Unix operating system
- For every user /home/username directory is created which is called their home directory

## Paths

- Absolute paths:
    - An absolute path is where one directory is in relation to the root directory
    - It starts with '/'

- Relative paths:
    - A relative path is where one directory is, in relation to another directory
    - Using a relative path means,
        that the place you end up at depends on your current working directory


## Basic Commands

### Navigating the file system

**pwd**     :- to print the working directory (gives us the absolute path)

**cd /**    :- to go to the root directory

**cd ..**   :- to go one level up

**cd ~**    :- to go to the home directory

**cd -**    :- to go to the previous working directory'

**.**       :- the current location

**ls**      :- to list the files and directories

**ls -l**   :- to print a long list

**ls -a**   :- to list all files and folders including hidden ones

**ls -la**  :- the combination of -l and -a

**ll**      :- shortcut of ls -la

**history** :- to view the history of all executed commands


### Manipulating files and folders

**mkdir trial**             :- to create the trial directory

**mv trial playground**     :- to rename trial to playground

**touch file1**             :- to create a file named file1

**mv file1 file2**          :- to rename file1 to file2

**cp file1 file2**          :- copies file1 to file2

**cp -r**                   :- copy directories recursively

**rm file2**                :- to remove the file

**rm -r playground**        :- to recursively remove the directory named playground

**rm -f**                   :- to force remove a file

**rm -rf**                  :- to force remove a folder recursively

**rmdir**                   :- delete and empty directory


### Editing and viewing files

**nano file1**              :- to edit the file

**cat file1**               :- to view the file content

**less file1**              :- to have a scrollable view

**head file1**              :- shows the first 10 lines

**tail file1**              :- shows the last 10 lines


### The standard input and output

- The standard input is the keyboard and the standard output is the screen
- We can change this, and that is called redirection
- cat file1 > file2
- echo helloworld > file1

### The man command

**man** :- (short for "manual") provides detailed manual pages for a wide range of commands