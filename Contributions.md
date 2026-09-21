### Team Collaboration Guidelines

Welcome! To keep our codebase clean, stable, and easy to maintain, all team members are expected to follow these rules when contributing to this repository. 

### ➡️ 1. Branching Strategy

We use **GitHub Flow** for our development cycle. 

* **Never push directly to the main branch.** All changes must be made on a separate branch and merged via a Pull Request.
* **Keep branches isolated.** One feature or bug fix per branch.
* **Use naming conventions.** Prefix your branch name based on the task type: 

  * feature/short-description (e.g., feature/user-login)
  * bugfix/short-description (e.g., bugfix/api-timeout)
  * chore/short-description (e.g., chore/update-packages)

### ➡️ 2. Commit Standards

* **Commit often.** Small, atomic commits make it easier to isolate bugs and roll back changes if needed.
* **Write meaningful messages.** Use the imperative present tense (e.g., Add authentication logic instead of Added authentication logic or Adding auth stuff).
* **Keep secrets out.** Never commit passwords, local environment files (.env), or private API keys. Ensure these are listed in the .gitignore file.

### ➡️ 3. Pull Request (PR) Workflow

* **Keep PRs small.** Large PRs take longer to review and are more prone to hidden bugs. Aim for under 300 lines of code changes per PR.
* **Verify locally first.** Run the application and execute all tests locally before opening a PR.
* **Describe your changes.** When creating a PR, clearly state: 

  1. What this PR does.
  2. Why this change is necessary.
  3. Any testing steps the reviewer should take.

### ➡️ 4. Code Review Expectations

* **Everyone is a reviewer.** Be prepared to review your teammates' code. Aim to respond to PR requests within 24 hours.
* **Be constructive and kind.** Frame feedback as a discussion rather than an order. (e.g., *"What do you think about using a map function here instead of a loop?"*).
* **Approve to merge.** A branch can only be merged into main after it has received at least one **Approved** review and passes all automated checks.
