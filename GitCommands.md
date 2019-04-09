# Essentials
Command | Explanation
--------| ---------
`clean -f -d` | delete all untracked files / local changes
`for /d %i in (*.*) do cd %i & git pull & cd..` | pull all repos in subdirectories
`reflog` | see commits with its messages

# Branching
Command | Explanation
--------| ---------
`git pull` -> `git checkout -b [newBranchName]` -> `git push origin [newBranchName]` | Generates a new Branch and pushes it to the upstream
`git branch -d [branchName]` | delete specific branch
`git pull origin master` -> `git checkout master` -> `git merge [newBranch]` | Merges the feature branch into the master branch

### Reset
Command | Explanation
--------| ---------
`git reflog` | see log hash num
`git reset --hard <commit>` | revert back to specific commit 
`git push --force` | reset the remote to the old commit 

# overwrite master with contents of seotweaks branch (seotweaks > master)
Command | Explanation
--------| ---------
git checkout seotweaks    # source name
git merge -s ours master  # target name
git checkout master       # target name
git merge seotweaks       # source name

### Tagging release
Command | Explanation
--------| ---------
`git tag` | see all previously created tags
`git tag -a v.[versionNum] -m "[release messgae]"` | Created a new tag with a given release message
`git push origin` | push created tag to origin remote

### Remove staged dir / file
Command | Explanation
--------| ---------
git rm -r --cached [directoryName] | Remove directory from remote repo

