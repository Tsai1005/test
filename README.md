尝试本地建立工作区，再关联到远端`

add 后再尝试修改本地，git diff 查看与暂存区的差别

local 在git init 后，git remote add origin git@github.com:Tsai1005/test.git 

git checkout -b dev 相当于git branch dev & git checkout dev

dev 作修改后 git diff 无论在身处dev 或者master 分支都能看到差异

仅在git add & git commit 后才看到不同的差异

git checkout master 到本地，then git merge dev & git branch -d dev合并分支改动后删除

重复新建分支，但主分支和新建分支同时修改，尝试合并
