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

 

