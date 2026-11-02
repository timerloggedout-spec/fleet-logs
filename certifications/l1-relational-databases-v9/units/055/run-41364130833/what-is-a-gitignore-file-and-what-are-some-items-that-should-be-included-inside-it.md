## Answers to FreeCodeCamp Relational Databases v9 Lesson: ".gitignore File"

**KEY Q1:** To specify files and directories that Git should ignore and not track.

**Q1:** What is the purpose of a .gitignore file?

**A:**  To specify files and directories that Git should ignore and not track.

**Justification:** This is the definition provided in the lesson: ".gitignore files tell Git which files and directories to **ignore**—that is, not to track."

**KEY Q2:** Git will continue to track the file until you explicitly remove it from tracking.

**Q2:** If you've already committed a file to Git and later add it to .gitignore, what will happen?

**A:** Git will continue to track the file until you explicitly remove it from tracking.

**Justification:**  The lesson states: "If you've already committed a file and then add it to a .gitignore file, Git **will continue to track the file** until you explicitly remove it from tracking."

**KEY Q3:** directory/*, !directory/important-file.txt

**Q3:** What syntax would you use in a .gitignore file to ignore all files in a directory, but then make an exception for one specific file?

**A:** directory/*, !directory/important-file.txt

**Justification:** The lesson provides this example: "To ignore **all files** in a directory but make an exception for one specific file, use the following syntax: `directory/*, !directory/important-file.txt`"