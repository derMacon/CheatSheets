# Essentials
Command | Explanation
--------| ---------
`clean -f -d` | delete all untracked files / local changes
`for /d %i in (*.*) do cd %i & git pull & cd..` | pull all repos in subdirectories

# Branching
Command | Explanation
--------| ---------
`git pull` -> `git checkout -b [newBranchName]` -> `git push origin [newBranchName]` | Generates a new Branch and pushes it to the upstream
`git branch -d [branchName]` | delete specific branch

