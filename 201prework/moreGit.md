# Git Tutorial

[https://learngitbranching.js.org/](https://learngitbranching.js.org/)

Intro to Git commits

`Git commit` commits changes

## Git Branches
> branch early, and branch often

`git branch newImage`  Makes new branch call newImage

To get on the new branch use `git checkout newImage`

`git checkout -b [yourbranchname]` will create a new branch and check it out at the same time.

## Git Merge

`git merge [branchname]` will merge current checked out branch with branch choosen.

A Git is a snapshot in time of files and code called a repository(repo).  Git tracks changes of files and code as you work.  Changes in Git are staged with `git add` committed to the repo with `git commit`.  Branches in a repo can be made with `git branch <branchname>`.  You can switch between branches with `git checkout <branchname>`.  And branches can be merged into the current branch with `git merge <branchname>`. Using Git helps minimize data loss and keep trace of changes.

[Readme learning journal](README.md)