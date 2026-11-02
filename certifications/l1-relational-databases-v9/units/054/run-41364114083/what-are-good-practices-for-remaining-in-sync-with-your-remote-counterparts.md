## Answers to FreeCodeCamp Relational Databases v9 Lesson: Remaining in Sync

**KEY Q1:** It will cause your local main branch to diverge from upstream, causing complications when syncing.

**Q1:** What's the main reason you should avoid committing changes directly to your main branch when working with forked repositories?

**A:**  *It will cause your local main branch to diverge from upstream, causing complications when syncing.*

This is correct because the lesson emphasizes the importance of keeping your local `main` branch in sync with the original repository's `main` branch. Committing directly to your local `main` will create a divergence, making it harder to integrate changes from the upstream repository later.

**Lesson Evidence:** *"Avoid committing directly to your main branch when working with forked repositories. This is because your local main branch will then diverge from the original repository’s main branch, which can cause complications when trying to sync with the original repository later on."*

**KEY Q2:** git fetch upstream, git checkout main, git merge upstream/main

**Q2:** Which series of commands will correctly update your local main branch with changes from the original repository?

**A:** *git fetch upstream, git checkout main, git merge upstream/main*

This sequence ensures you fetch the latest changes from the upstream repository, switch to your local `main` branch, and then merge the changes from the upstream `main` branch into your local one.

**Lesson Evidence:**  *"To update your local main branch with changes from the original repository, you can use the following commands:

```bash
git fetch upstream
git checkout main
git merge upstream/main
```*

**KEY Q3:** git reset --hard upstream/main

**Q3:** If you've accidentally committed to your main branch and can't merge upstream changes, what command can you use to forcibly reset your branch to match the upstream (assuming you haven't made any pull requests)?

**A:** *git reset --hard upstream/main*

A hard reset will discard all local changes in your `main` branch and set it to exactly match the state of the `upstream/main` branch.

**Lesson Evidence:** *"If you accidentally committed to your main branch and can’t merge upstream changes, you can use the following command to forcibly reset your branch to match upstream (assuming you haven’t made any pull requests):

```bash
git reset --hard upstream/main
```*