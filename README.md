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
