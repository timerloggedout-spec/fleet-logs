## Answers to FreeCodeCamp Relational Databases v9 Lesson: Bash Scripting

**KEY Q1:** It indicates what interpreter should be used for the script.

**Q1: What is the purpose of the "shebang" line in a Bash script?**

**Correct Option:** It indicates what interpreter should be used for the script.

**Justification:** The shebang line specifies the path to the interpreter (like Bash) that should execute the script.

**Evidence:** *"The first line of a Bash script is often referred to as the shebang. It tells the system which interpreter to use to run the script. In the case of Bash scripts, it usually looks like this:
`#!/bin/bash`*

**KEY Q2:** It iterates through each element in the servers array.

**Q2: In the example script, what does the line `for server in "${servers[@}"` accomplish?**

**Correct Option:** It iterates through each element in the servers array.

**Justification:** The code snippet uses a `for` loop with an array variable (`${servers[@]}`) which is the standard syntax for iterating over each element in an array in Bash.

**Evidence:** *"For loops are used to iterate over a list of items. In this case, we're iterating over each server in the servers array."*

**KEY Q3:** Bash scripts run faster than Python or JavaScript.

**Q3: Which of the following is NOT mentioned as an advantage of Bash scripting?**

**Correct Option:** Bash scripts run faster than Python or JavaScript.

**Justification:** While the lesson mentions performance as an advantage, it doesn't specifically state that Bash scripts are faster than Python or JavaScript.

**Evidence:**  The lesson discusses performance in terms of Bash being lightweight and efficient for system administration tasks, but doesn't make a direct comparison to other languages' execution speed.