# simple_shell

<h1>SIMPLE SHELL ALX PROJECT.</h1>

Description This is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included.

Installation Clone this repository into your working directory. Files should be compiled this way: "gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh"

Usage After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

Interactive Mode In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

Non-Interactive Mode In non-interactive mode, echo your desired command and pipe it into the program like this:

echo "ls" | ./shell In non-interactive mode, the program will exit after finishing your desired command(s).

This is the man page which contains all functions and descriptions of all the functions used in this Simple shell project. To access this page, Do:

Features Display a prompt and wait for the user to type a command. A command-line always ends with a new line. The prompt is displayed again each time a command has been executed. The command lines are simple, no semicolons, no pipes, no redirections, or any other advanced features. The command lines are made only of one word.No arguement will be passed to the programs. If an executable is not found the shell prints an error message and displayu the prompt again.

Authors Written by Godsfavour Farida Momoh and Joyce Talabi.
