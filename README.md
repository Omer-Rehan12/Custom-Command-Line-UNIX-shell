Custom Unix Shell

  A custom Unix/Linux command-line shell developed in C that replicates core functionalities of a traditional terminal environment.
  The project demonstrates concepts of operating systems, process management, and inter-process communication.

Features

  Execute basic Unix commands


  Support for multiple commands using pipes (|)


  Input and output redirection (<, >)


  Parent and child process handling using fork()


  Command execution using execvp()


  Process synchronization with wait()


  Custom shell prompt and interactive terminal behavior


  Error handling for invalid commands



Tech Stack


  C Programming


  Linux/Unix System Calls


  GCC Compiler



Concepts Implemented


  Process Creation and Management


  Inter-Process Communication (Pipes)


  File Descriptors


  Input/Output Redirection


  System Calls in Unix/Linux


  Command Parsing and Tokenization



How to Run


  Compile
  
  
  gcc shell.c shell_functions.c -o myshell
  
 
  Execute
  
  
  ./myshell



Example Commands


  lspwdcat file.txtls | wc

  
  sort < input.txt

  
  echo Hello > output.txt



What I Learned


  Working with low-level system programming


  Understanding how Unix shells operate internally


  Managing processes and file descriptors


  Building interactive command-line applications
