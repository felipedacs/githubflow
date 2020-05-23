# githubflow
modificação 1 após pr
```sh
git clone
git remote add upstream <url>
git fetch upstream
git rebase upstream/<branch> # git rebase upstream/master
git add .
git commit -m "blabla"
git fetch upstream
git rebase upstream/<branch> # git rebase upstream/master

# resolve conflitos
# git add .
# git commit -m "blabla"
# ou (?)
# git a .
# git rebase --continue
# ??? qq eu faço pra manter a separação dos commits mas dar rebase?
# pull request não está atualizando a cada commit novo
# atualizou, foi um bug ?
```

