# 🧠 Git Command Tutorial – Beginner to Pro

This project README is not just a file — it's a complete **Git command reference** for learning and practicing Git through your terminal. It includes **commands, explanations, use cases**, and real-world notes.

---

## 📌 What is Git?

**Git** is a distributed version control system that lets you track changes in code and collaborate with others. It helps developers:
- Manage project versions
- Revert mistakes
- Work together without overwriting each other's work

---

## 📦 Git Setup & Configuration

```bash
# Check Git version
git --version

# Set your name and email globally (only once)
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Verify Git config
git config --list


## Initialize a Git Repository
bash
Copy
Edit
# Start tracking a project with Git
git init
Creates a hidden .git folder that stores your version history.


# Show current status (what's changed)
git status

# Show commit history
git log

# Show log in one line per commit
git log --oneline


# Stage a specific file
git add filename

# Stage all changes
git add .

# Commit staged files with a message
git commit -m "Write your commit message"


# Undo staged changes (unstage)
git restore --staged filename

# Discard local changes to a file
git restore filename

# Undo last commit but keep files
git reset --soft HEAD~1

# Undo last commit and discard changes
git reset --hard HEAD~1


# Create a new branch
git branch feature-branch

# Switch to a branch
git checkout feature-branch

# Create and switch in one step
git checkout -b feature-branch

# List all branches
git branch

# Merge another branch into current one
git merge feature-branch

# Delete a branch
git branch -d feature-branch


# Add a GitHub remote
git remote add origin https://github.com/yourusername/your-repo.git

# View remote details
git remote -v

# Change existing remote URL
git remote set-url origin NEW_URL


# Push your branch to GitHub (first time)
git push -u origin main

# Push changes after that
git push

# Pull latest changes from GitHub
git pull origin main



# Delete a file and stage the deletion
git rm filename

# Commit the deletion
git commit -m "Remove filename"

#.gitignore
node_modules/
.env
*.log
__pycache__/


#hrlp
git help
git help commit


#Git Best Practices
Commit often, but meaningfully

Pull before pushing to stay up to date

Use branches for features or experiments

Don’t commit sensitive files (use .gitignore)

Write clear commit messages (present tense: “Add login feature”)



✍️ Author
John Fallah (@legend979)
📧 thecleverprogrammer2025@gmail.com
📍 India
🧑‍💻 Exploring Git, GitHub, and AI tools

