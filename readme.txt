Git is a version control system.
Git is free software

Git is a distributed version control system.
Git is free software

Git is a distributed version control system.
Git is free software distributed under the GPL.

Creating a new branch is quick AND simple.

2020-08-31
命令：git pull --allow-unrelated-histories
含义：把两段不相干的 分支进行强行合并

相关的命令
命令：git pull 
作用：取远程主机某个分支代码，再与本地的指定分支进行合并。
基本用法：git pull <远程主机名> <远程分支名> <本地分支名>
用例：git pull origin master:brantest 【说明：将远程主机origin的master分支拉取过来，与本地的branchtest分支进行合并。后面的冒号可以省略，git pull origin master，表示将远程origin主句的master分支拉取过来和本地的当前分支进行合并。】

git pull = git fetch + git merge

命令：git fetch 
作用：拉取远程主机某个分支的代码。不执行合并分支的操作。如需要合并分支，可以使用git merge 命令进行合并。
基本用法：跟git pull 一致
说明：相比git pull，git fetch更安全些。
git push --set-upstream origin master

相关学习链接
https://www.cnblogs.com/wbl001/p/11495110.html
