
# C - Simple Shell

This is a simple UNIX command line interpreter created as part of a programming project. The shell is designed to handle basic command line operations without support for advanced features such as semicolons, pipes, redirections, or arguments. The goal is to provide a minimalistic command line interface with a straightforward user experience.

# Usage

To use the simple shell, compile the source code and run the executable. The shell will display a prompt and wait for the user to type a command. Each command line should consist of a single word. After executing a command, the prompt will be displayed again.

```
$ gcc -o simple_shell simple_shell.c
$ ./simple_shell
Shell$ ls
file1.txt  file2.txt
Shell$ echo "Hello, World!"
Hello, World!
Shell$ exit
$
```
# Features

- Display a prompt and wait for user input.
- Execute commands with a single word.
- Prompt is displayed again after each command execution.
- Error handling for command not found.
- Handle the "end of file" condition (Ctrl+D).

# Getting Started

Follow these steps to get the simple shell up and running on your system:

Clone the repository:

```
$ git clone https://github.com/yourusername/simple-shell.git
$ cd simple-shell
```

Compile the source code:

```
$ gcc -o simple_shell simple_shell.c
```

Run the executable:

```
$ ./simple_shell
```

Start using the simple shell by entering commands at the prompt.

# Error Handling

If an executable cannot be found, an error message will be displayed, and the prompt will appear again. The simple shell also handles the "end of file" condition gracefully.


## Authors

- [@GwenaelB74](https://www.github.com/GwenaelB74) (Gwenael)
- [@a-sowa](https://www.github.com/a-sowa) (Axel)
## About us

Axel and Gwenael are student developers at the Holberton School in Thonon-les-Bains. This project is the final project of our chapter in the C language.


