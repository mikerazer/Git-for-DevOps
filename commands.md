Commands.md File:

## 📂 Directory and File Management

```bash
# Create directories
📁 mkdir Github
📁 mkdir git-tutorial
📁 mkdir git-practice

# Navigate directories
➡️ cd Github
➡️ cd git-tutorial
➡️ cd git-for-devops
➡️ cd ..

# Check current directory
📍 pwd

# List files
📜 ls
📜 ls -a
📜 ls -l
________________________________________
📄 File Operations
bash
Copy code
# Create files
📝 touch nibba.txt nibbi.txt
📝 touch babu.txt

# View file content
👁️ cat hello-dosto.txt
👁️ cat nibba.txt

# Edit files
✏️ vim hello-dosto.txt
✏️ vim nibbi.txt
✏️ vim nibba.txt

# Remove files
🗑️ rm hello-dosto.txt
🗑️ rm nibbi.txt
🗑️ rm nibba.txt
________________________________________
🚀 Git Commands
🔧 Initialization & Setup
bash
Copy code
# Initialize a repository
💻 git init

# Set global config
🔧 git config --global user.name "Mikerazer"
🔧 git config --global user.email "mikerazer@gmail.com"
🗃️ Add, Commit, and Status
bash
Copy code
# Check status of the repository
📊 git status

# Add files to the staging area
🗂️ git add nibba.txt
🗂️ git add nibbi.txt
🗂️ git add hello-dosto.txt
🗂️ git add babu.txt

# Remove files from staging
❌ git rm --cached nibba.txt
❌ git rm --cached nibbi.txt

# Commit changes
💾 git commit -m "Initial commit"
💾 git commit -m "Added hello-dosto and nibba"
💾 git commit -m "Added babu file"
🌳 Branching and Checkout
bash
Copy code
# View, create, and switch branches
🌿 git branch
🌿 git branch -a
🔀 git checkout master
🔀 git checkout -b dev
🔀 git checkout -b tester
📜 Logs and History
bash
Copy code
# View commit history
📝 git log
📝 git log --oneline

# View command history
🕒 history
🔄 Miscellaneous Git Commands
bash
Copy code
# Restore files
♻️ git restore nibbi.txt

# Check the status of uncommitted changes
📊 git status
________________________________________
🧹 Clean Up
bash
Copy code
# Clear terminal

