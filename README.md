# Shell

# Requirements
-  `gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh`
- Betty style.
- No memory leaks
- No more than 5 functions per file

#  1. Simple shell 0.1 

    Usage: simple_shell

features:

- Display a prompt and wait for the user to type a command. A command line always ends with a new line.

- The prompt is displayed again each time a command has been executed.
- The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
- The command lines are made only of one word. No arguments will be passed to programs.
- If an executable cannot be found, print an error message and display the prompt again.
- Handle errors.
- You have to handle the “end of file” condition (Ctrl+D)
# old_shell
