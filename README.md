# Git_basics

Just basic Git commands for reference. 🚀


# 1️⃣ Initialize Git
```bash
git init  # 🆕 Create a Git repository
```

# 2️⃣ Stage all files
```bash
git add .  # 📂 Stage all files
```
# If any subfolder is a Git repo, remove its .git folder
# Linux / Mac:
```bash
# cd folder_name
# rm -rf .git  # ❌ Remove nested Git repo
# cd ..
```
# Windows:
```bash
# cd folder_name
# rmdir /s /q .git  # ❌ Remove nested Git repo
# cd ..
```


# 3️⃣ Commit files
```bash
git commit -m "Initial commit"  # 💾 Save changes
```
# 4️⃣ Rename branch to main
```bash
git branch -M main  # 🔀 Rename branch to main
```

# 5️⃣ Add GitHub remote
```bash
git remote add origin https://github.com/UserName/REpoNAMe.git  # 🌐 Connect to GitHub
```
# 6️⃣ Push to GitHub
```bash
git push -u origin main  # 🚀 Push changes online
```


# Git & GitHub Basics 🐙

Essential Git & GitHub commands for beginners. 🚀

```bash
# 0️⃣ Configure Git with your GitHub account
git config --global user.name "Your Name"       # 📝 Set your name
git config --global user.email "you@example.com" # 📧 Set your email

# Optional: check configuration
git config --list  # 🔍 View your Git settings

# 1️⃣ Initialize a Git repository
git init  # 🆕 Create a Git repository locally

# 2️⃣ Stage changes
git add .            # 📂 Stage all files
git add file_name    # 📄 Stage a specific file

# 3️⃣ Commit changes
git commit -m "message"       # 💾 Save staged changes
git commit -am "message"      # 💾 Stage & commit in one step

# 4️⃣ Branching
git branch                    # 🌿 List all branches
git branch branch_name        # ➕ Create a new branch
git checkout branch_name      # 🔀 Switch to a branch
git switch branch_name        # 🔀 Alternative to checkout

# 5️⃣ Rename branch
git branch -M main            # 🔀 Rename current branch to main

# 6️⃣ Merge branches
git merge branch_name         # 🔗 Merge branch into current branch

# 7️⃣ Remote repositories
git remote -v                 # 🌐 Show remotes
git remote add origin URL     # ➕ Link to a remote GitHub repo
git remote remove origin      # ❌ Remove a remote repo

# 8️⃣ Push & Pull
git push -u origin main       # 🚀 Push changes to GitHub
git push origin branch_name   # 🚀 Push a specific branch
git pull origin main          # ⬇️ Pull changes from GitHub

# 9️⃣ Check status & history
git status                    # 📋 Show current changes
git log                       # 🕰 Show commit history
git log --oneline             # 🕰 Short history

# 🔟 Undo & reset
git restore file_name         # ♻️ Undo changes in a file
git restore --staged file_name# ♻️ Unstage a file
git reset --hard HEAD         # ⚠️ Reset all changes to last commit

# 1️⃣1️⃣ Ignore files
echo "node_modules/" > .gitignore  # 🙈 Ignore files/folders

# 1️⃣2️⃣ Clone a repository
git clone https://github.com/UserName/RepoName.git  # 📥 Copy repo locally

# 1️⃣3️⃣ Stash changes
git stash       # 🗄 Temporarily save changes
git stash pop   # 🔄 Apply stashed changes

# 1️⃣4️⃣ Open repository on GitHub
# Go to your browser and navigate to:
# https://github.com/UserName/RepoName  🌐
