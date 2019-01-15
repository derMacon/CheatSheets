`clean -f -d` | delete all untracked files / local changes
`for /d %i in (*.*) do cd %i & git pull & cd..` | pull all repos in subdirectories
