# Git-Use
```
checkout the branch : git checkout <name>
create a new branch AND check it out at the same time : git checkout -b [yourbranchname]
in bugFix branch, rebase to master: git rebase master, 
in master branch, rebase master to new bugFix branch: git rebase bugFix
parent of master: git checkout master^
HEAD ref: git checkout HEAD^
grandparent of master: git checkout master^^
move number of times: git checkout HEAD~4
directly reassign a branch to a commit with branch forcing(-f): git branch -f master HEAD~3
reset: git reset HEAD~1
revert(create a new commit, shared with remote): git revert HEAD
```
