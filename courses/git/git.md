GIT cheatsheet 
==============================

` git clone ` download & create remote

` git branch -d {name} ` 

` git merge ` : strategiess recursive | fast forward

```
   <<<<<<<<<<<<< HEAD 
	This contains my local version  !!!!
   =======================
	This is from server
   >>>>>>>>>>>>>>>>>>>>>>>>>>>>>
 ```

 ` git push {remote} {branch}`

 ` git branch -r ` remote branches

 ` git remote show {remote} `

 ` git push: {branch}` deletes remote branch

 ` git branch -D {branch}` force to delete locally

 ` git remote prune origin ` to clean up delete remoted branches

 ` git push {remote}  {localBranch} : {serverBranch}`

 GIT TAG
 --------------------

 `git tag`

 `git tag -a v0.0.0.3 -m 'Version 0.0.0.3'`

 ` git push --tags`

 ` git checkout {tag}`


 GIT REBASE 
 --------------------

- Move all changes to temp
- Run all commits
- Move all commits in the temp one at a time

 `git rebase`

Options

`git rebase --continue`

`git rebase --skip`

`git rebase --abort`

`git rebase -i HEAD~3`

In Popup
----

`.pick`

`.reword`

`.edit`

`.squash`

GIT LOG
------------------

`git log --pretty=oneline`

`git log --oneline -p`

`git log --oneline -graph`

`git blame`

`git rm --cached`


GIT CONFIG
------------------

`git config --global color.ui true`

`git config --global merge.tool {tool}`

`git config user.email {myMail}`

`git config --global alias.{myAlias}  log --`


GIT STASH
---------------

`git stash save`

`git stash apply`

`git stash list`

`git stash drop`

`git stash save --keep-index ` : causes the staging area not to be stashed

`git stash save --included-untracked ` : causes the untracked files to be staged

`git stash list --stat`

`git stash show`

`git stash clear`

