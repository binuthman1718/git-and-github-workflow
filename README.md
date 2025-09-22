# Git and GitHub Workflow Project

This project demonstrates the Git and GitHub workflow for version control and collaboration.  
It explains how to:
- Initialize and manage repositories
- Commit and push changes
- Use branches for new features
- Work with `.gitignore` and licenses
## 🌿 Branching Strategy

In this project, we are using the **GitHub Flow** workflow.

- The `main` branch is always stable.  
- For every new change, we create a **feature branch**.  
- After finishing the work, we push the branch to GitHub.  
- Then we create a **Pull Request (PR)** and merge it into `main`.  

### Example:
```bash
# Create a new branch
git checkout -b feature-update-readme

# Make changes, then save them
git add README.md
git commit -m "Update README with branching strategy"

# Push branch to GitHub
git push origin feature-update-readme
