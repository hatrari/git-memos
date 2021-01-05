# How to commit an Hotfix
`git checkout recette'
`git checkout -b hotfix`
> Fix issues
`git add .`
`git commit -m 'fix issues'`
`git push origin hotfix`
`git checkout recette`
`git pull origin recette`
`git merge --no-ff hotfix`
`git commit -m 'message'`
`git push origin recette`
`git branch -d hotfix`
