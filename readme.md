1. List Branches
# List local branches
git branch

# List remote branches
git branch -r

# List all branches (local + remote)
git branch -a

2. Create a Branch
# Create a new branch (local only)
git branch feature-login

# Switch to branch
git checkout feature-login

# Or create + switch in one command
git checkout -b feature-login

3. Switch Branches
# Switch to another branch
git checkout master

4. Push a Branch to GitHub
git push -u origin feature-login


-u sets upstream so future git push works automatically.

checkout branch is master but push code with other branch