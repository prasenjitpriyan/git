# Git

Here’s a list of essential **Git commands** for web development, covering everything from setting up a repository to collaborating with teams and deploying projects.  

---

### 🚀 **Basic Git Commands** (Setup & Initialization)  
```sh
git --version                          # Check Git version
git config --global user.name "Your Name"  # Set global username
git config --global user.email "your@email.com"  # Set global email
git init                               # Initialize a new Git repository
git clone <repo_url>                   # Clone an existing repository
git status                             # Check the status of changes
git add <file>                         # Stage a file for commit
git add .                               # Stage all files
git commit -m "Commit message"         # Commit changes with a message
```

---

### 🔄 **Branching & Merging** (Feature Development)  
```sh
git branch                              # List all branches
git branch <branch_name>                # Create a new branch
git checkout <branch_name>              # Switch to another branch
git switch <branch_name>                # Alternative to checkout
git checkout -b <branch_name>           # Create and switch to new branch
git merge <branch_name>                 # Merge another branch into current
git branch -d <branch_name>             # Delete a branch (after merging)
git branch -D <branch_name>             # Force delete a branch
```

---

### 📤 **Working with Remote Repositories** (GitHub, GitLab, Bitbucket)  
```sh
git remote -v                          # Show remote URLs
git remote add origin <repo_url>       # Add a remote repository
git push -u origin main                # Push the main branch to remote
git push -u origin <branch_name>       # Push a specific branch
git pull origin main                   # Pull latest changes from remote
git fetch origin                       # Fetch changes without merging
```

---

### 🚨 **Undoing Changes & Fixing Mistakes**  
```sh
git restore <file>                     # Discard changes in a file
git reset HEAD <file>                   # Unstage a file
git reset --soft HEAD~1                 # Undo last commit, keep changes
git reset --hard HEAD~1                 # Undo last commit, discard changes
git revert <commit_hash>                # Create a new commit that undoes a previous commit
```

---

### 🏷️ **Tags & Versioning**  
```sh
git tag                                # List all tags
git tag -a v1.0 -m "Version 1.0"      # Create an annotated tag
git push origin v1.0                   # Push tag to remote
```

---

### 🔀 **Stashing & Temporary Work**  
```sh
git stash                              # Save uncommitted changes
git stash list                         # View stashed changes
git stash pop                          # Reapply stashed changes
git stash drop                         # Remove last stash
```

---

### 🛠️ **Collaboration & Code Review** (For Teams)  
```sh
git log                                # Show commit history
git log --oneline --graph --decorate   # Pretty commit history
git diff                               # Show changes between commits
git blame <file>                       # Show who last modified each line
git show <commit_hash>                 # Show details of a commit
```

---

### 🔐 **Security & Deployment**  
```sh
gitignore                             # Create .gitignore file
echo "node_modules/" >> .gitignore    # Ignore node_modules
git rm --cached <file>                # Remove file from Git but keep locally
git config credential.helper store     # Store GitHub login credentials
```

---

### 🌎 **Deployment-Related Git Commands** (For Web Dev)  
```sh
git remote add production <server_url>  # Add a production server
git push production main                # Deploy to production
git pull production main                 # Pull latest live changes
```

---

These are the most **common Git commands** for web development. Let me know if you need more details on any! 🚀🔥
