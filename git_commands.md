- The repo from which you fork is called upstream
- We cannot push directly to the upstream
- you can't do git push upstream rahul(rahul is a branch)

## One branch can only open one pull request
## only one branch can be associated to one pull request so we need different branches for different pull requests

### Git stash - It moves the staged files to the back areas which will not be included in the commit

### git fetch --all --prune
- It fetches all the changes from the main

### git reset --hard upstream/main - It resets our local repo to the main forked repo

### git pull upstream main - pull the changes from the main upstream

### Squashing the git commits
- git rebase -i <commit hash>
- we can either squash and pick 
- press :x to exit


