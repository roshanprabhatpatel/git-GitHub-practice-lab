# Git & GitHub Practice Lab

A simple Git & GitHub command reference for practice.

---

## 1. Git Setup

git --version
--> Check Git version

git config --global user.name "Your Name"
--> Set Git username

git config --global user.email "you@example.com"
--> Set Git email

git config --list
--> Check Git configuration


## 2. Start / Check Repository

git init
--> Create a new local Git repository Or make repository to git repository

git remote add origin <-github link-> 
--> Make local repo to remote repo

git status
--> Check current repository status

git clone <repository-url>
--> Copy a remote repository to local computer


## 3. Track Changes

git add <file>
--> Add a file to staging

git add .
--> Add all changed files to staging

## 4. Commit

git commit -m "message"
--> Save staged changes in Git history

git log
--> Show commit history

## 5. Push

git push origin main
--> Upload local main branch to remote repo

git push origin main
--> Upload main branch

## 6. Pull

git pull origin main
--> Download and integrate changes from remote repo to local repo from remote main branch


## 7. Branch

git branch
--> Check branches

git branch <branch-name>
--> Create a new branch

git branch -d <branch-name>
--> Delete a local branch

git switch <branch-name>
--> Switch to another branch

git switch -c <branch-name>
--> Create and switch to a new branch

git checkout <branch-name>
--> Switch to another branch (older/common method)

git checkout -b <branch-name>
--> Create and switch to a new branch


## 8. Merge

git merge <branch-name>
--> Merge another branch into current branch


## 9. Undo Changes

git restore <file>
--> Undo unstaged changes in a file

git restore --staged <file>
--> Remove file from staging

git reset
--> Unstage changes

git reset --hard HEAD~1
--> Undo last commit and delete changes
⚠️ Use carefully


## 10. Merge Conflict

git status
--> Check files involved in conflict

git merge --abort
--> Cancel the merge


## 11. Useful Commands

git help
--> Show Git help

git <command> --help
--> Show help for a specific command

git status
--> Check what is happening right now

git log
--> See commit history