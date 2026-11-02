## Answers to FreeCodeCamp Relational Databases v9 Lesson: Merge Conflicts

**KEY Q1:** When Git cannot automatically merge changes due to conflicting edits in the same part of a file.

**Q1: What is a merge conflict in Git?**

**Correct Option:**  When Git cannot automatically merge changes due to conflicting edits in the same part of a file.

**Justification:** This is the standard definition of a merge conflict in Git.

**Evidence:** *"A merge conflict happens when Git cannot automatically merge changes due to conflicting edits in the same part of a file."*

**KEY Q2:** git add <file>, git commit

**Q2: After manually resolving a merge conflict in your local repository, what commands do you need to run to complete the merge?**

**Correct Option:** git add <file>, git commit

**Justification:** After resolving conflicts, you stage the resolved file(s) using `git add` and then commit the merge with `git commit`.

**Evidence:** *"Once you've manually resolved the conflicts, you'll need to stage the resolved files using `git add <file>` and then commit the merge using `git commit`."*

**KEY Q3:** Merging creates a merge commit, while rebasing rewrites history for a linear timeline.

**Q3: What is the main difference between merging and rebasing when dealing with branch conflicts?**

**Correct Option:** Merging creates a merge commit, while rebasing rewrites history for a linear timeline.

**Justification:**  Merging results in a new commit that combines the histories of both branches, while rebasing moves commits from one branch onto another, creating a linear history.

**Evidence:** *"Merging creates a new commit that combines the histories of both branches, while rebasing rewrites history by moving commits from one branch onto another."*