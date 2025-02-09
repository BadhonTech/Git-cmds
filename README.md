
# Git Commands Cheat Sheet

## 1. Configuration

```bash
git config --global user.name "Your Name"   # Set username
```

```bash
git config --global user.email "your@email.com"   # Set email
```

```bash
git config --global color.ui auto   # Enable colored output
```

```bash
git config --list   # View all global configurations
```

## 2. Initializing and Cloning

```bash
git init   # Initialize a new Git repository
```

```bash
git clone <repo_url>   # Clone an existing repository
```

```bash
git clone <repo_url> <folder_name>   # Clone into a specific folder
```

## 3. Staging and Committing

```bash
git status   # Check status of working directory
```

```bash
git add <file>   # Stage a specific file
```

```bash
git add .   # Stage all changes
```

```bash
git commit -m "Commit message"   # Commit staged files
```

```bash
git commit -am "Commit message"   # Add and commit in one step (tracked files only)
```

## 4. Branching and Merging

```bash
git branch   # List all branches
```

```bash
git branch <branch_name>   # Create a new branch
```

```bash
git checkout <branch_name>   # Switch to a branch
```

```bash
git checkout -b <branch_name>   # Create and switch to a new branch
```

```bash
git merge <branch_name>   # Merge a branch into the current branch
```

```bash
git branch -d <branch_name>   # Delete a branch
```

## 5. Remote Repositories

```bash
git remote -v   # View remote repositories
```

```bash
git remote add origin <repo_url>   # Add a remote repository
```

```bash
git push origin <branch_name>   # Push changes to remote repository
```

```bash
git push -u origin <branch_name>   # Push and set upstream
```

```bash
git pull origin <branch_name>   # Pull latest changes from remote
```

```bash
git fetch origin   # Fetch changes without merging
```

## 6. Undoing Changes

```bash
git reset <file>   # Unstage a file
```

```bash
git reset --hard <commit_hash>   # Reset to a previous commit and discard changes
```

```bash
git revert <commit_hash>   # Revert a specific commit
```

```bash
git restore <file>   # Restore a file to the last committed version
```

```bash
git checkout -- <file>   # Discard changes in a file
```

## 7. Viewing History

```bash
git log   # View commit history
```

```bash
git log --oneline   # View commit history in one line
```

```bash
git log --graph --decorate --all   # View a graphical log
```

```bash
git diff   # Show differences in unstaged changes
```

```bash
git diff --staged   # Show differences in staged changes
```

## 8. Stashing Changes

```bash
git stash   # Save changes temporarily
```

```bash
git stash list   # List stashed changes
```

```bash
git stash pop   # Apply and remove the latest stash
```

```bash
git stash apply   # Apply the latest stash without removing
```

```bash
git stash drop   # Delete the latest stash
```

## 9. Tagging

```bash
git tag   # List all tags
```

```bash
git tag -a v1.0 -m "Version 1.0"   # Create an annotated tag
```

```bash
git push origin --tags   # Push all tags to remote
```

## 10. Submodules

```bash
git submodule add <repo_url> <path>   # Add a submodule
```

```bash
git submodule update --init --recursive   # Update all submodules
```
