**Q1. What GitHub features allow contributors to make simple code changes directly from the web browser? Describe at least two.**
R: The **Web Editor** (clicking the pencil icon) and **github.dev** (pressing "." to open VS Code in the browser).

**Q2. What are the lifecycle phases of a GitHub Codespace, and what happens in each phase?**
R: 
- **Creation:** Builds the environment using your repo config.
- **Running:** The space is active and ready to code.
- **Stopped:** Freezes and saves your work when you stop using it.
- **Deletion:** Permanently deletes the space and its data.

**Q3. What happens to your work if you stop a GitHub Codespace without committing your changes?**
R: **Nothing**, your work stays saved inside the codespace until you open it again or delete it.

**Q4. Who should enable two-factor authentication (2FA) on GitHub, and why?**
R: **Everyone**, because it is an extra layer of security that protects your account if someone finds your password.

**Q5. What permission levels exist for repositories owned by a personal GitHub account?**
R: 
- **Owner:** Full admin control over the repo.
- **Collaborator:** Read and write access to push changes.

**Q6. What repository visibility options does GitHub provide, and when would you use each?**
R: 
- **Public:** Anyone can see it.
- **Private:** Only you and your collaborators can see it.
- **Internal:** Only members of your enterprise organization can see it.

**Q7. What is the purpose of a CODEOWNERS file?**
R: To **define who is responsible** for specific files or folders in a repository. GitHub will automatically request reviews from them when a PR changes those files.

**Q8. How can you enforce that status checks must pass before merging into the main branch?**
R: By setting up a **Branch Protection Rule** for `main` and checking the box **"Require status checks to pass before merging"**.

**Q9. What steps can you take to ensure changes to main require approval from at least two reviewers?**
R: By setting up a **Branch Protection Rule** for `main` and checking the box **"Require a pull request before merging"**, then check **"Require approvals"** and set the number to **2**.

**Q10. What is CodeQL, and how is it used in GitHub?**
R: It is an **analysis engine** used by GitHub Advanced Security to scan your code for vulnerabilities and security flaws automatically during your workflows.

**Q11. What is a fork in GitHub, and when should you use one?**
R: A **copy of another user's repository** stored in your own account. Use it when you want to propose changes to someone else's open-source project or use their code as a starting point.

**Q12. What is a pull request in GitHub?**
R: A **proposal to merge changes** from one branch into another. It lets you show your code, discuss modifications, and run automated tests before the code is merged.

**Q13. When creating a pull request from feature-a into main, which branch is the base and which is the compare?**
R: 
- **Base:** `main` (the target branch receiving the changes).
- **Compare:** `feature-a` (the branch with your new code).

**Q14. What are draft pull requests, and when should they be used?**
R: A type of pull request that **cannot be merged** until changed to "ready for review". Use them when you want to share a work-in-progress to get early feedback or keep track of your task without triggering automatic review requests.
