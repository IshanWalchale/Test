# Test

# Local setup
git init
git remote add origin https://github.com/username/git_assi.git
git add .
git commit -m "Initial commit"
git push -u origin main

# Branching
git checkout -b feature1
# make changes
git add .
git commit -m "Added new feature"
git push origin feature1

# Merge
git checkout main
git merge feature1

# Rebase
git checkout feature1
git rebase main

# Delete branch
git branch -d feature1
git push origin --delete feature1

# Undo
git reset --soft HEAD~1
