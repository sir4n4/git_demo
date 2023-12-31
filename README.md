# Git Practice!!! 

### Add + Commit [tracked file]
- git commit -a -m"Updated Index"
### Check status
- git status
- git log
- git log --oneline

### Push with Upstream
- git push origin main
- git push -u origin main [Upsteam helps to pull form online]
  
### Info about branch and online branch
- git branch -v
- git branch -r
  
### Create branch 
- git branch feature-button
- git branch search

### Move to branch
- git checkout feature-button
- git chekout search
- git chekout main

### Create and chekout
- git branch -b feature-button

### Merge
first chekout to main
- git checkout main
- git merge feature-button

### To see merged and unmerged branches
- git branch --merged
- git branch --no-merged

### delete branch
- local after merged: git branch -d feature-button
- forced delete: git branch -D feature-button  [when not merged]
- online: git push origin --delete feature-button
### Tag and Release version
- git tag v0.1
