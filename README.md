# CLI

## Commands
```
git --version
git --help
```
## Configure Git
```
git config --global user.name "Sakib-Sobaha"
git config --global user.email "1905021@ugrad.cse.buet.ac.bd"
git config --global color.ui auto
git config
git config -l
```
## Initializing Git Repository
```
git init .
ls -a
```
## Staging n Commit
```
git status
git add <file>
git add .
git rm --cached <file> (Make files untracked)
git rm -r --cached .
git add -A (To add all files of parent directory from a child directory)
git commit -m "javascript project"
git log
git show (<hash>)
git diff
gh auth login
git restore <file> (To undo changes)
git commit --amend -m "msg" (To change the recent commit message)
```

 ## Push to Github
 ```
git remote add origin repository_HTTP
git branch -M main
git pull --rebase origin main
git push -u origin main
```
Used to authenticate in local machine. [Add SSH Key for authentication](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)


### Do authentication staffs in the project directory

## Branch
```
git branch  (print the current branch I'm on)
git branch -a
git branch -r
git branch feature-a (create a new branch)
git checkout feature-a (switch to feature-a branch)
git checkout - (switch to the previous branch)
git checkout -b branch_name (create and switch to the new branch)
git branch -d branch_name (delete a branch)
git log --oneline
```

