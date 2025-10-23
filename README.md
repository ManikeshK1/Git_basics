# Git_basics

Just basic Git commands for reference. 🚀

```bash
# 1️⃣ Initialize Git
git init  # 🆕 Create a Git repository

# 2️⃣ Stage all files
git add .  # 📂 Stage all files

# If any subfolder is a Git repo, remove its .git folder
# Linux / Mac:
# cd folder_name
# rm -rf .git  # ❌ Remove nested Git repo
# cd ..
# Windows:
# cd folder_name
# rmdir /s /q .git  # ❌ Remove nested Git repo
# cd ..


# 3️⃣ Commit files
git commit -m "Initial commit"  # 💾 Save changes

# 4️⃣ Rename branch to main
git branch -M main  # 🔀 Rename branch to main

# 5️⃣ Add GitHub remote
git remote add origin https://github.com/UserName/REpoNAMe.git  # 🌐 Connect to GitHub

# 6️⃣ Push to GitHub
git push -u origin main  # 🚀 Push changes online
