

## 🔹 Setup & Clone Repository
# Clone a repository from GitHub
git clone <repository-url>

# Navigate into the project folder
cd <folder-name>

# List files inside the directory
ls


## 🔹 Add, Commit & Push Changes
# Add a specific file (example: index.html)
git add index.html

# Commit changes with a message
git commit -m "Your commit message"

# Check the status of your repository
git status

# Push committed changes to remote repository
git push

# View commit history
git log


## ⚡ Handling Merge Conflicts
# Commit all changes (auto stage + commit)
git commit -am "Add message"

# Pull latest changes from remote (to merge updates)
git pull


## 🌿 Working with Branches
# Check all available branches
git branch

# Create and switch to a new branch
git checkout -b <new-branch-name>

# Merge a branch into the current branch
git merge <branch-name>


## 💡 Quick Notes
# Always pull before pushing to avoid merge conflicts
# Use 'git status' frequently to track file changes
# Use clear, descriptive commit messages for better project history

# Delete a branch locally
git branch -d <branch-name>

# Delete a branch remotely
git push origin --delete <branch-name>
