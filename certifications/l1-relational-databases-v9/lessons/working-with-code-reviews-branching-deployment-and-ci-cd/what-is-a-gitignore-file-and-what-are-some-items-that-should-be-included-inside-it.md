# Unit 055 — Theory: What Is a .gitignore File, and What Are Some Items That Should Be Included Inside It?
- URL: https://www.freecodecamp.org/learn/relational-databases-v9/lecture-working-with-code-reviews-branching-deployment-and-ci-cd/what-is-a-gitignore-file-and-what-are-some-items-that-should-be-included-inside-it
## Questions (verbatim, signed-in capture 2026-11-01)
- Q1: What is the purpose of a .gitignore file? — To specify files and directories that Git should ignore and not track. / To list files that Git should always track. / To configure Git's global settings. / To store sensitive information securely.
- Q2: If you've already committed a file to Git and later add it to .gitignore, what will happen? — Git will automatically stop tracking the file. / Git will continue to track the file until you explicitly remove it from tracking. / Git will delete the file from your local system. / Git will move the file to a hidden directory.
- Q3: What syntax would you use in a .gitignore file to ignore all files in a directory, but then make an exception for one specific file? — directory/*, !directory/important-file.txt / directory/, !directory/important-file.txt / directory/*, exception: directory/important-file.txt / directory/**, include: directory/important-file.txt
## Expected keys (advisory)
- Q1 To specify files and directories that Git should ignore and not track. · Q2 Git will continue to track the file until you explicitly remove it from tracking. · Q3 directory/*, !directory/important-file.txt

## SERVED-SET Δ (2026-11-01 15:55–15:58 PT, at submit): live lesson served a DIFFERENT question set than this capture (theory lessons rotate sets per load, like quizzes). Session selected semantic-equivalent answers from the lesson body; all marked Correct, lesson PASSED. Fleet run keyed this captured set; served answers recorded in the lane report ↑mgr (Δ43/64 message).
