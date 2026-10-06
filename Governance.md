# Repository Governance

### 1. Access Model & Roles
* **Owner (AmberAvahi):** Full admin control. Responsible for managing settings, visibility, and adding collaborators.
* **Collaborators (Team/Reviewers):** Read and Write access. Allowed to create branches, open Pull Requests, and review code. They cannot change repository settings or delete the repo.

### 2. Branch Protection Rules
* **Target:** `main` branch.
* **Rules Enabled:** 
  * Require a Pull Request and approvals before merging (prevents accidental direct pushes to main).
  * Require status checks to pass before merging (ensures code doesn't break workflows).

### 3. Secrets Management
* **Secret Configured:** `ONBOARDING_SECRET`
* **Purpose:** Stores sensitive environment variables or API keys securely so they can be used in GitHub Actions without exposing them in the plain code.
