[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16875178&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
1. Fundamental Concepts of Version Control & GitHub's Popularity
Version control tracks changes in code, allowing collaboration and rollback to previous versions. Git is a distributed system, enabling multiple developers to work without overwriting changes. GitHub is popular due to its cloud-based hosting, collaboration tools, and integration with CI/CD.

2. Setting Up a New Repository on GitHub
Steps:

Log in to GitHub.
Click New Repository.
Choose a repository name.
Set visibility (public or private).
(Optional) Add a README file.
Decisions: Repository name, visibility, inclusion of README, license, and .gitignore.

3. Importance of a README File
A README introduces the project and includes:

Title & Description (Purpose and features)
Installation Steps
Usage Instructions
Contribution Guidelines
License Information
It helps users and contributors understand the project quickly.
4. Public vs. Private Repositories
Public: Open to everyone, good for open-source projects.

Advantage: Encourages collaboration.
Disadvantage: Not secure for sensitive code.
Private: Restricted access, good for proprietary code.

Advantage: Protects sensitive data.
Disadvantage: Limits external contributions.
5. First Commit to a GitHub Repository
Steps:

Configure Git (git config --global user.name "Your Name")
Initialize repository (git init)
Stage changes (git add .)
Commit changes (git commit -m "Initial commit")
Push to GitHub (git push -u origin main)
Commits track changes, making it easy to revert and manage project versions.

6. Git Branching & Its Importance
Branching allows parallel development without affecting the main code.

Workflow:

Create a branch: git branch feature-branch
Switch to branch: git checkout feature-branch
Merge changes: git merge feature-branch
Useful for feature development and bug fixes.

7. Pull Requests (PRs) & Code Review
PRs propose changes before merging into the main branch.

Steps:

Create a PR from a feature branch.
Review/discuss changes with team members.
Make revisions if needed.
Merge PR after approval.
PRs enhance collaboration and maintain code quality.

8. Forking vs. Cloning
Forking creates a copy of a repository under your GitHub account for independent changes.
Cloning copies a repository to your local machine for personal work.
When to Fork?

Contributing to open-source projects.
Experimenting without affecting the original repository.
9. GitHub Issues & Project Boards
Issues: Track bugs, features, and tasks.
Project Boards: Organize work into "To Do," "In Progress," and "Done."
Example:

Use issues for bug tracking.
Use boards to plan features and track development progress.
10. Common Challenges & Best Practices
Challenges:

Merge conflicts: Occur when multiple people edit the same code.
Messy commit history: Too many or too few commits.
Access issues: Improper permission settings.
Best Practices:

Communicate regularly.
Use clear commit messages.
Review changes before merging.
