- A shell is a program that is an interface between a user and the raw operating system

- If you ever need to enter a command that is longer than a line on your terminal, you may terminate a portion of a command by a blackslash ( \ ) character

- Some characters are processed specially by a shell and are known as *metacharacters*

- `command`: Command substition; replaced by the output of *command*

- The sequence **$ command > fileName** sends the standard output of *command* to the file with name *fileName*

- The sequence **$ command < fileName** executes *command* using the contents of file *fileName* as its standard input.  If the file does not exist or does not have read persmission an error occurs.


A shell supports two kinds of variables: environment and local variables  Both hold data in string format.
Environment variables
When you precede the name of a variable with a $, this token sequence is replaced by the shell with the valye of the named variable

