# git-command

### Add files

git add <filename>
  
git add *

git add --all
  
  
### Commit

git commit -m "Commit message"

git commit -a


### Push

git push origin master


### Status

>List the files you've changed and those you still need to add or commit:

git status


### Branches

git checkout <branchname>

git branch

git branch -d <branchname>  // delete


### Tags

git tag 1.0.0 <commitID>
  

git remote update origin --prune

git pull origin master --allow-unrelated-histories


### Delete files

find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

find . -name '*.DS_Store' -type f -delete

git commit -m '.DS_Store banished!'

### Merge error

git reset --merge

### discard changes

git reflog 

git reset --hard

git reset --hard HEAD@{n}

### config

git config --global user.email "you@example.com"

git config --global user.name "Your Name"

https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
https://www.jianshu.com/p/fdaa8be7f6c3

### rebase
git pull --rebase origin develop

