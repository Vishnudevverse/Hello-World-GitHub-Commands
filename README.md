# 👋 Hello World GitHub Commands

This repository is my **personal playground** to learn and practice **Git** and **GitHub** commands for solo development.  
Below is a handy reference for the most common commands I use. 🚀


---

## 🔧 Setup Your Identity
### Check your Git configuration
    git config --list

### Set your username and email
    git config --global user.name "YourName"
###
    git config --global user.email "you@example.com"

---

## 📁 Initialize or Clone a Repository
### Initialize a new local repository
    git init

### Or clone an existing remote repository
    git clone <repo-url>

---

## 📝 Basic Workflow
### Check status of your files
    git status

### Add specific file(s)
    git add file.txt

### Add all changes
    git add .

### Commit changes with a message
    git commit -m "Your commit message"

### Push changes to remote
    git push

### Push and set upstream to main branch
    git push -u origin main

### Pull latest changes from remote
    git pull

---

## 🌿 Working with Branches
### See all branches
    git branch

### Create a new branch
    git checkout -b new-branch

### Switch back to main branch
    git checkout main

### Merge a branch into main
    git merge new-branch

### Delete a branch
    git branch -d new-branch

---

## 🧹 Undoing Changes
### Restore a specific file to last commit
    git restore file.txt

### Unstage a staged file
    git restore --staged file.txt

### Reset last commit but keep changes staged
    git reset --soft HEAD~1

---

## 📡 Working with Remote Repos
### Show remote URLs
    git remote -v

### Add a remote repo
    git remote add origin <url>

### Rename default branch to main
    git branch -M main

### Push changes and set upstream
    git push -u origin main

---

## 🔍 View Commit History
    git log

# 🎉 Happy Coding!
This README.md is a living document.
I’ll update it as I learn more Git tricks! ✨


---

If you want, you can copy this entire `README.md` into your repository.  
When you push it to GitHub, it will render nicely on your repo’s front page!

Would you like me to help you make an even more customized version with badges, your name, or a license? Just let me know! 🚀✨

