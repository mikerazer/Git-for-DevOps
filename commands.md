# Git Commands :-

## 📂 Repository Management
- **Create a new repository**: 
  git init
- **Clone a repository**: 
  git clone <repository_url>

## 🌳 Branching
- **List branches**: 
  git branch
- **Create a new branch**: 
  git checkout -b <branch_name>
- **Switch to a branch**: 
  git checkout <branch_name>
- **Delete a branch**: 
  git branch -d <branch_name>

## 📝 Committing Changes
- **Stage changes**: 
  git add <file_name>
- **Commit changes**: 
  git commit -m "commit message"
- **View commit history**: 
  git log
- **Check status of files**: 
  git status

## 🌐 Remote Repositories
- **Add a remote repository**: 
  git remote add <name> <url>
- **Fetch changes from a remote**: 
  git fetch <remote>
- **Push changes to a remote**: 
  git push <remote> <branch_name>
- **Pull changes from a remote**: 
  git pull <remote> <branch_name>

## 📁 File Management
- **Remove a file**: 
  git rm <file_name>
- **Restore a deleted file**: 
  git restore <file_name>
- **View changes in a file**: 
  git diff

## 🏷️ Tags
- **Create a tag**: 
  git tag <tag_name>
- **List tags**: 
  git tag
- **Push tags to remote**: 
  git push <remote> --tags

## ⚙️ Configuration
- **Set username**: 
  git config --global user.name "Your Name"
- **Set email**: 
  git config --global user.email "your.email@example.com"
- **View configuration**: 
  git config --list

## 💼 Stashing
- **Stash changes**: 
  git stash
- **Apply stashed changes**: 
  git stash apply
- **List stashed changes**: 
  git stash list
