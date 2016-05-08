尝试本地建立工作区，再关联到远端`

add 后再尝试修改本地，git diff 查看与暂存区的差别

local 在git init 后，git remote add origin git@github.com:Tsai1005/test.git 

git checkout -b dev 相当于git branch dev & git checkout dev

dev 作修改后 git diff 无论在身处dev 或者master 分支都能看到差异

仅在git add & git commit 后才看到不同的差异

git checkout master 到本地，then git merge dev & git branch -d dev合并分支改动后删除

在dev1分支修改后，master同时修改，待合并冲突

在dev2 修改后，合并到master，使用git merge --no-ff 

在dev3 中进行功能开发，然后突然发现master 需要bug fix，尝试git stash
