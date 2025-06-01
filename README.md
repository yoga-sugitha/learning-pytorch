This file won't serve for the actual purpose for now.

Git Commands Cheat Sheet for Your Cloned Repo

1. Check current repo status
git status
Shows changes, untracked files, and branch info.
2. Add files to staging area
git add filename.ipynb
Add a specific file.
Or add all changes:

git add .
3. Commit changes with a message
git commit -m "Describe what you changed"
4. Push your commits to GitHub
git push origin main
Replace main with your branch name if different.
5. Pull latest changes from GitHub
git pull origin main
Useful if you or collaborators pushed updates.
6. Create a new branch
git checkout -b new-feature
Work on a feature or fix without touching main.
7. Switch to an existing branch
git checkout main
8. Check commit history
git log --oneline --graph --decorate --all
A nice visual summary of your commits.
