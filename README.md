# simple-unix-shell
Unix Shell and History Feature


This project consists of modifying a C program which serves a shell interface that accepts user com- mands and then executes each command in a separate process. A shell interface provides the user a prompt after which the next command is entered. 

The design of the unix shell
Enter command in shell. 
After reading user input, fork a child process using fork() 
The child process will invoke execvp() 
If command included &, the parent will invoke wait()


Enter “history” command for the command history,
Press ctrl c will give the command history.
