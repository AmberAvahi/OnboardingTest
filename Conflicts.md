# How I Solved Merge Conflicts

1. **Created a branch from main:** Named it `AddingWrongAnswers`.
2. **Added placeholder text:** Put "Wrong Answer" on all questions and opened a Pull Request.
3. **Created a second branch from main:** Named it `AddingRightAnswers` to add correct answers for Q1-Q5 and fix the Markdown formatting.
4. **Merged the first branch:** Merged `AddingWrongAnswers` into `main` first.
5. **Encountered conflicts:** The PR for `AddingRightAnswers` now showed merge conflicts with `main`.
6. **Configured Git strategy:** Set my default Git behavior to merge during a pull.
7. **Pulled latest updates:** Did a `git pull origin main` into my current branch.
8. **Resolved conflicts:** Fixed the code clashes manually in the files.
9. **Committed changes:** Made a new commit named `solving conflicts`.
10. **Final Merge:** Merged everything successfully into `main`.
