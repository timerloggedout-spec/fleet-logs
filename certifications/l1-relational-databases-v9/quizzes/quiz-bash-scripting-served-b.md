# Unit 029 — SERVED SET B (live capture 2026-11-01 15:09–15:10 PT; stable across loads this session)
1. What is a correct shebang line in bash script? — /#!/bin/bash / !#/bin/bash / /#!bin/bash / #!/bin/bash
2. Which command would define MY_VAR and print it to the console? — $MY_VAR=10; echo $MY_VAR / MY_VAR=10; echo $MY_VAR / $MY_VAR=10; echo MY_VAR / MY_VAR=10; echo MY_VAR
3. Which command is used to view all variables in the shell? — declare -p env / declare -x bashrc / declare -n env / declare -p
4. Which command would run a script.sh file? — ./sh script.sh / script.sh bash / ./script.sh / zsh ./script.sh
5. How to view the manual for the less command in bash? — man --less / less --man / less man / man less
6. How would you call the print_arguments function to print a and b to the terminal? — print_arguments "a" "b" / print_arguments{a, b} / print_arguments("a", "b") / print_arguments(a, b)
7. How do you initialize an array in bash? — ARR=["item1" "item2" "item3"] / ARR={"item1" "item2" "item3"} / ARR=[["item1" "item2" "item3"]] / ARR=("item1" "item2" "item3")
8. How do you print the third value of an array in bash? — echo ${ARR[3]} / echo ${ARR[2]} / echo $ARR[2] / echo $ARR[3]
9. How do you assign user input to a variable in bash? — read MY_VAR / cin MY_VAR / get MY_VAR / input MY_VAR
10. What will be the permission flags for the 1.txt file after executing the command chmod 765 1.txt? — rwxrw-r-x / rwxrwxrwx / r-xrw-rwx / rwxr-xrw-
11. What keyword does the statement if ... then ... end with? — done / end / stop / fi
12. What keyword does the statement for ... do ... end with? — od / done / end / stop
13. How do you create a comment in bash? — // comment / !comment / # comment / /* comment
14. What line should you add to the beginning of this snippet to create a for loop? (snippet: do echo $i done) — for (( i = 0; i < 10; i++ )) / for ( int i = 0; i < 10; i++ ) / for (( let i = 0; i < 10; i++ )) / for (( int i = 0; i < 10; i++ ))
15. How would you assign the result of the sum of variables A and B to the variable C? — $C=$(( $A + $B )) / C=$( A + B ) / C=$A + $B / C=$(( A + B ))
16. Which command is used to create a new file? — touch / newfile / fileargs / echo new_file
17. What does the command echo $? do? — Prints the value of the last executed condition. / Prints the exit code of the last executed command. / Prints the value of the last used variable. / Prints the value of the last used arithmetic operation.
18. What advantage does Bash provide when testing parts of a script? — You can only test scripts using an IDE. / Bash automatically generates test cases. / Script sections can be pasted directly into the terminal for testing. / Bash scripts must be compiled before testing.
19. What types of loops exist in bash? — for, while, until, forEach / for, while / for / for, while, until
20. How do you print all values of an array in bash? — echo {ARR[@]} / echo ${ARR[$@]} / echo $ARR[@] / echo ${ARR[@]}
## Advisory keys (Platforms)
1 #!/bin/bash · 2 MY_VAR=10; echo $MY_VAR · 3 declare -p · 4 ./script.sh · 5 man less · 6 print_arguments "a" "b" · 7 ARR=("item1" "item2" "item3") · 8 echo ${ARR[2]} · 9 read MY_VAR · 10 rwxrw-r-x · 11 fi · 12 done · 13 # comment · 14 for (( i = 0; i < 10; i++ )) · 15 C=$(( A + B )) · 16 touch · 17 Prints the exit code of the last executed command. · 18 Script sections can be pasted directly into the terminal for testing. · 19 for, while, until · 20 echo ${ARR[@]}
