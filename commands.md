# 🧭 Git Commands Reference (Practice Summary)

This file contains all Git commands used during practice — organized **topic-wise** for quick learning and reference.

---

## 🧩 1. Git Installation & Version Check

```bash
sudo apt-get install git
sudo apt-get upgrade git
sudo apt autoremove
git --version
```

---

## ⚙️ 2. Git Configuration

```bash
# Set username and email globally
git config --global user.name "Sachin Mishra"
git config --global user.email "sachinmishrasm214@gmail.com"

# View all configurations
git config --list

# Check specific configs
git config user.name
git config user.email

# Unset (remove) user configuration
git config --global --unset user.name
```

---

## 📁 3. Repository Setup

```bash
# Create and navigate to a folder
mkdir git-practice
cd git-practice/

# Initialize a Git repository
git init

# View hidden files (including .git)
ls -a

# Check repository status
git status
```

---

## 📝 4. File Creation & Editing

```bash
# Create files
touch index.html
touch nibba.txt nibbi.txt nibbu.txt

# Edit files
vim index.html
vim nibba.txt
vim nibbi.txt
```

---

## 📦 5. Adding & Removing Files from Staging Area

```bash
# Add files to staging area
git add nibba.txt
git add nibbi.txt
git add -A      # or --all

# Remove files from staging area
git rm --cached index.html
git rm --cached nibba.txt
git rm --cached nibba.txt nibbi.txt
```

---

## 💾 6. Committing Changes

```bash
# Commit with a message
git commit -m "adding nibba nibbi"
git commit -m "added new changes to nibbi"
git commit -m "added nibba changes"
git commit -m "nibbu was added"

# View commit history
git log
git log --oneline
```

---

## 🔁 7. Restoring & Removing Files

```bash
# Restore deleted file from the last commit
git restore nibbi.txt

# Remove file manually
rm hello.txt
rm nibbi.txt
```

---

## 🌿 8. Branching

```bash
# Check branches
git branch

# Create new branches
git checkout -b dev
git checkout -b from-dev
git checkout -b from-master

# Switch between branches
git switch dev
git switch master

# View branch list again
git branch
```

---

## 🧠 9. Miscellaneous Useful Commands

```bash
# List directory contents
ls

# Clear terminal
clear

# View command history
history
```

---

## ✅ 10. Summary

You successfully practiced:
- Installing & configuring Git  
- Initializing a local repository  
- Tracking, staging, committing, and restoring files  
- Creating and switching between multiple branches  

---

📘 **Tip:**  
To check your configuration anytime:
```bash
git config --list
```

To remove a file from tracking but keep it locally:
```bash
git rm --cached <filename>
```

---

**Author:** Sachin Mishra  
**File:** `commands.md`  
**Purpose:** Git practice documentation  
