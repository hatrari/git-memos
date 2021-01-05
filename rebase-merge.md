# How to rebase and merge myBranch to develop

`git checkout myBranch`

`git add .`

`git commit -m 'commit description'`

`git checkout develop`

`git pull origin develop`

`git checkout myBranch`

`git rebase develop`

> Resolve conflicts

`git add .`

`git rebase --continue`

`git push origin myBranch`

`git checkout develop`

`git merge myBranch`

`git push origin develop`
