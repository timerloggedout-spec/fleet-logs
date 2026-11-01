# Unit 029 — Quiz: Bash Scripting Quiz (Q)
- URL: https://www.freecodecamp.org/learn/relational-databases-v9/quiz-bash-scripting/quiz-bash-scripting
- 20Q × 4, pass ≥18/20, "Finish the quiz". Option order SHUFFLES per load ⇒ key by TEXT.
## Verbatim set (signed-in capture 2026-11-01, this load's order)
1. What command would you use to make the script.sh file executable? — chmod +x script.sh / chmod -x script.sh / chmod +r script.sh / chmod +w script.sh
2. What is a bash script? — A text file with a sequence of commands that are executed by the bash program line by line. / A file that contains only binary code. / A type of database. / A graphical user interface for bash.
3. What is the purpose of the #!/bin/bash line in a script? — It is a comment that is ignored by the shell. / It tells the system which interpreter to use to execute the script. / It defines a variable. / It is used to import libraries.
4. How do you define a variable named MY_VAR with the value hello in bash? — MY_VAR=hello / MY_VAR = hello / var MY_VAR=hello / set MY_VAR=hello
5. What is the correct way to reference the value of the variable MY_VAR in a bash script? — $MY_VAR / MY_VAR / %MY_VAR% / &MY_VAR
6. Consider the following bash function: print_arguments(){ echo "Argument 1: $1" echo "Argument 2: $2" } What is the output of calling print_arguments hello world? — Argument 1: hello Argument 2: world / Argument 1: world Argument 2: hello / Argument 1: hello world Argument 2: / Argument 1: $1 Argument 2: $2
7. Which symbol is used to redirect output to a file in bash, overwriting the file's contents? — > / >> / < / |
8. What does the command ls -la do in bash? — Lists all files and directories, including hidden ones, with detailed information. / Lists only directories. / Lists files in reverse order. / Lists files with their sizes only.
9. How do you create a function in bash? — function_name() { commands } / def function_name(): commands / function function_name { commands } / create function_name() { commands }
10. What will be the permission flags for the 1.txt file after executing the command chmod 765 1.txt? — rwxrw-r-x / rw-r--r-- / rwxr-xr-x / rwxrw-rw-
11. What is the purpose of the if statement in bash scripting? — To execute commands based on a condition. / To define a function. / To create a loop. / To redirect output.
12. How do you check if a file exists in bash? — if [ -f file ] / if [ -e file ] / if [ -d file ] / if [ file ]
13. What is the purpose of the else statement in bash scripting? — To execute commands when the if condition is false. / To create a loop. / To define a variable. / To exit the script.
14. Given the following bash code: for id in 1 2 3 4 5; do echo $id done What is the output? — 1 2 3 4 5 / 12345 / 1 / 5 4 3 2 1
15. What is the purpose of the case statement in bash scripting? — To execute different commands based on the value of a variable. / To create a loop. / To define a function. / To redirect input.
16. How do you read user input into a variable in bash? — read var_name / input var_name / get var_name / scan var_name
17. What is the purpose of the while loop in bash scripting? — To execute commands repeatedly as long as a condition is true. / To define a function. / To create a variable. / To exit the script.
18. How do you access the first argument passed to a bash script? — $1 / $0 / $@ / $#
19. What are the types of loops in bash? — for, while, until, forEach / for, while / for / for, while, until
20. What is the purpose of the exit command in bash scripting? — To terminate the script with a specific exit status. / To pause the script. / To restart the script. / To display a message.
## Expected keys (advisory)
1 chmod +x script.sh · 2 A text file with a sequence of commands that are executed by the bash program line by line. · 3 It tells the system which interpreter to use to execute the script. · 4 MY_VAR=hello · 5 $MY_VAR · 6 Argument 1: hello Argument 2: world · 7 > · 8 Lists all files and directories, including hidden ones, with detailed information. · 9 function_name() { commands } · 10 rwxrw-r-x · 11 To execute commands based on a condition. · 12 if [ -f file ] (note: -e also defensible; -f = FCC-style key) · 13 To execute commands when the if condition is false. · 14 1 2 3 4 5 · 15 To execute different commands based on the value of a variable. · 16 read var_name · 17 To execute commands repeatedly as long as a condition is true. · 18 $1 · 19 for, while, until · 20 To terminate the script with a specific exit status.
