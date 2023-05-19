git从远程仓库更新最新版本到本地仓库

git remote -v

git fetch origin main:newVersion

git diff newVersion

git merge newVersion

如果newVersion 不再使用，可以删除

git branch -d newVersion