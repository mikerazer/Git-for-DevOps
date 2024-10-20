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

  ls
pwd
mkdir Github
cd Github
pwd
mkdir git-tutorial
ls
cd git-tutorial
pwd
clear
vim hello-dosto.txt
cat hello-dosto.txt
ls
ls -l
rm hello-dosto.txt
vim hello-dosto.txt
cat hello-dosto.txt
git init
ls -a
git status
touch nibba.txt nibbi.txt
git add nibbi.txt
git add nibba.txt
git rm --cached nibba.txt
rm nibba.txt
touch nibba.txt
git add nibba.txt
git add hello-dosto.txt
git commit -m "adding f1 f2 f3 hello-dosto nibba nibbi"
git config --global user.name "Mikerazer"
git config --global user.email "mikerazer@gmail.com"
rm nibbi.txt
git restore nibbi.txt
vim nibbi.txt
git add nibbi.txt
git commit -m "added new change to nibbi"
git log
vim nibba.txt
git add nibba.txt
git commit -m "added nibba changes"
git branch
git checkout -b dev
touch babu.txt
git add babu.txt
git commit -m "added babu"
git checkout master
git log
git checkout dev
git branch
git checkout -b tester
git log --oneline
history
