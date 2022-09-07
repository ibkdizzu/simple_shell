Description

simple_shell is a command line interpreter, or shell, in the tradition of the first Unix shell written by Ken Thompson in 1971. This shell is intentionally minimalistic, yet includes the basic functionality of a traditional Unix-like command line user interface. Standard functions and system calls employed in simple_shell include: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.

File Structure

AUTHORS - List of contributors to this repository

man_1_simple_shell - Manual page for the simple_shell

shell.h - program header file

builtins.c - major builtin functions

check_for_builtins - checks to see if the user's command matches a builtin

new_exit - exits the shell with the option of a specified status

_env - prints the shell's environment variables to the standard output

new_setenv - initializes a new environment variable, or modifies an existing one

new_unsetenv - removes an environment variable


