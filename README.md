#  GitHashingExercise

This project is for the class of Operating Systems 2023-2024 in Electrical and Computer Engineering at the Aristortle University of Thessaloniki.
The questions are as follows

1) Git

a) Create a new folder named GitHashingExercise. Create a text file named README.md in your repository and write a brief description (a few words) of the project.

b) Generate a unique 4-digit integer, i.e. by using the last four digits of your student ID (AEM). Create a script in a shell of your choice named hash_script, where it should take a 4-digit integer as input and output a hash of the input. You can use any standard hashing algorithm (like SHA-256), run the script with your unique 4-digit integer and save the output in a file named hash_output.txt
Use Git commands to add and commit hash_script and hash_output.txt to your local repository. Lastly, create a new public repository named GitHashingExercise on github.com and push your local commits to the remote repository.

Note: Ensure that have an account on github.com. Presentation 4 contains information how to do so. You DO NOT need academic verification for a regular Github account, so don't need to wait on verification in order to complete the exercise.

2) Signals

a) Write a C program mysigcatch.c that catches the SIGINT signal (usually generated by the Ctrl+C command in the terminal). Upon catching the signal, the program should print "SIGINT signal caught!" and then terminate gracefully.

b) Modify your program, in mysigcatchmodified.c in order to use a custom signal handler function. In the custom handler, display the signal number of SIGINT and a message indicating that the signal was caught. After catching SIGINT twice, the program should restore the default behavior for SIGINT and terminate upon the next signal reception.
