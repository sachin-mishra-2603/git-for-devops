# Git Commands
📂 Repository Initialization

git init # Initialize a Git repository
ls -a # Show hidden files (.git will appear)
git status # Show working tree status

➕ Adding Files

git add <file> # Stage a file
git add . # Stage all changes

➖ Removing Files

git rm --cached <file> # Unstage file but keep it in working dir
git restore <file> # Restore deleted/modified file

✅ Committing Changes

git commit -m "message" # Commit staged changes
git log # Show full commit history
git log --oneline # Show commits in one-line format

⚙️ Configuring Git

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com
"

🌿 Branching

git branch # List branches
git branch <branch-name> # Create new branch
git checkout <branch-name> # Switch branch
git checkout -b <branch> # Create + switch branch
git switch <branch> # Switch branch (modern command)

🔄 Branch Workflow Example
Create and switch to dev branch

git checkout -b dev

Add a new file in dev branch

touch nibbu.txt
git add nibbu.txt
git commit -m "added nibbu"

Switch back to master

git checkout master

Create new branch from master

git checkout -b from-master
