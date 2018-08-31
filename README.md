# simple-unix-shell


The design of the unix shell
Enter command in shell. 
After reading user input, fork a child process using fork() 
The child process will invoke execvp() 
If command included &, the parent will invoke wait()


Enter “history” command for the command history,
Press ctrl c will give the command history.
