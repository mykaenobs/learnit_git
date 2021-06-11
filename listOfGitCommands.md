# List Of Git Commands

git init - to instanciate git in your local working directory
---
---
git add *e.xtensionName, filename, for all files to be add use '.' the dot like so 'git add .' - to add file to the repository
---
---
git rm --cached <file> - to remove the file(s) from the git repository but still avaliable in the working directory
git rm -r --cached <file> - to remove from the staging area
---
---
git log - for commit history
git log -2 (digit like 'git log -2') - to get range commit
git log --pretty=oneline - to get the result display more readable
git log --all
---
---
git commit -m '' - to commit for push
git commit --amend to change commit message
git commit --amend --no-edit - to add new commits to already committed (new file to already committed files)
git commit -a -m 'message' - to add and commit with a single line of code
---
---
git restore --staged <file> - it used to remove file from stage
git restore <file> - it is used to discard changes made to file after the last commit or push
---
---
git remove -v - to get the where we are
---
---
git remove set-url origin 'paste ssh url from git repository'
---
---
git branch - to see all local branches
git branch -r - to see all remote branches
git branch -a - to see all branches
git checkout -b <branchName> - to create and change branch at the same time
git branch -d <branchName> - to remove branch locally
---
---
git checkout -b <nameofbranch> - to switch and create a new branch
---
---
git checkout <commitId> - to switch between commits as well as branches
---
---
git push origin --delete <branchName> - to remove branch for remote repository
---
---
* new for creating branchs
git switch <branchName> - to create branch
git switch -c <branchName> - to create an switch branch
git switch - - to switch back to the previous branch
---
---
git remote -v - to checkout the remote repository connection
git remote add origin <url> - to add a remote repository connection
git remote set-url origin <url either SSH OR HTTPS> - this is to change connection between https and ssh
---
---