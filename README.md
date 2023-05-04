le Shell

The Simple Shell is a command-line interface (CLI) that allows users to interact with the operating system by typing commands. It is a basic implementation of a Unix shell, which is a program that provides users with an interface to interact with the underlying operating system.

### Features

The Simple Shell has the following features:

- Built-in commands: The Simple Shell has a set of built-in commands that are executed directly by the shell without creating a new process. These include cd, exit, echo, and pwd.
- Standard commands: The Simple Shell can also execute standard Unix commands like ls, cat, mkdir, and rm.
- Pipes and redirection: The Simple Shell supports pipes and redirection, allowing users to redirect the output of one command to the input of another, or to redirect input or output to a file.
- Background processes: Users can execute commands in the background by appending an ampersand (&) to the end of the command.
- Signal handling: The Simple Shell can handle signals like Ctrl-C and Ctrl-\.

### Getting Started

To use the Simple Shell, simply open a terminal and type ./shell in the directory where the shell executable is located. You can then type commands into the shell and press Enter to execute them.

### Command Syntax

The syntax for commands in the Simple Shell is similar to that of other Unix shells. A command consists of the command name, followed by any arguments and options. Arguments are separated by spaces, and options begin with a hyphen (-).

For example, the ls command can be used with the -l option to list files in long format:

ls -l

### Exit Status

When a command is executed, it returns an exit status, which is a number that indicates whether the command was successful or not. In the Simple Shell, an exit status of 0 indicates success, while any other value indicates failure.

### License

The Simple Shell is released under the MIT License. See the LICENSE file for details.
