
# DevOps Git Project

## 🎯 Objective
To manage a DevOps project using Git best practices like branching, pull requests, tags, and commits.

## 📁 Branching Structure
- `main`: Production-ready code
- `dev`: Active development
- `feature/login`: New login feature

## 🛠 Tools Used
- Git
- GitHub
- VS Code / Terminal

## 📝 Workflow Followed

<img width="1662" height="766" alt="image" src="https://github.com/user-attachments/assets/8babc246-1cf1-40b3-bf21-549df964457b" />



1. Initialized Git repo and pushed to GitHub
2. Created `dev` and `feature/login` branches
3. Made commits on feature branch
4. Created a Pull Request to merge feature → dev → main
5. Created Git tags for release versioning

## 🧾 Git Commands Used

```bash
git init
git checkout -b dev
git checkout -b feature/login
git add .
git commit -m "Commit message"
git push
git tag -a v1.0 -m "First release"
