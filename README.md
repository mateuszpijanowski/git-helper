# Git basic commands helper

### Commits
Init git:
```
git init
```
Add changes to commit:
```
git add [files path]
```
Add new remote:
```
git remote add origin [url]
```
Commit changes:
```
git commit -m"[commit comment]"
```
Push change to remote repo:
```
git push
```
### Branches
Create new branch:
```
git branch [branch name]
```
Change branch:
```
git checkout [branch name]
```
Merge branch:
```
git merge [branch name]
```
Remove local branch:
```
git branch -D [branch name]
```
Remove remote branch:
```
git push --delete [remote name] [branch name]
```
Synchronize local branch with remote branch:
```
git rebase
git fetch origin
git pull [remote branch name]
```
### Commit manipulations
Remove a commit before pushed:
```
git reset --hard [HEAD - np origin/master]
```
Remove pushed commit:
```
git reset --hard [commit key]
git push -f
```
Change commit comment:
```
git reset --soft [commit key]
git commit -m "[new comment]"
git push -f
```
### Others
Show current status:
```
git status
```
Log list:
```
git log
```
Remote list:
```
git remote -v
```
Edit remotes:
```
git remote set-url origin [new remote url]
```
