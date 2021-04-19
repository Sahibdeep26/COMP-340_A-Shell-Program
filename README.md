# COMP-340_A-Shell-Program
You can check out the README.pdf to check out the details of this project


Overview: 
I created a basic shell program which has the ability to execute commands which are entered by a user in a Linux terminal. 

The basic information of this program is:
•	char input  is used to store tokens
•	*ptrToken is the pointer for a token
•	*ptrTokens is used to store all the tokens
•	int i is a counter
•	fgets takes user input till 200 using stdin input fill stream
•	strtok will return an address to token from input and split it where there is "  " or new line.
•	pid_t returns a process id of the child process
•	It would be equal to 0 for the child process
•	If child_pid is less than 0 it means that there is an error in forking
•	If the execvp returns -1 it means that there is an error in executing the  process
•	If waitpid is -1 it means that there is an error
•	If waitpid is some other value, it means that the code executed successfully
•	waitpid makes the program to wait for completion of the process. It accepts child_pid and the address of status of process.

