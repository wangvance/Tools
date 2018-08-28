# Git commands overview
ref:https://www.cnblogs.com/ludashi/p/8053382.html
* .gitignore 文件配置
* git diff 查看修改内容
* git rm: git 中文件移除
* git mv: git 文件重命名
* git log: 查看git提交日志
* git commit --amend: 往提交中追加文件的操作
* git tag: 打标签
* aliase 应用

## .gitignore
该文件记录了那些不被 git 管理的被忽略的文件。

## git log 相关
* git log
* git log -p
使用 git log -p 1 来查看最近一次提交的差异，也可以使用 git log -p 来查看所有的差异
* git log --stat
使用 git log --stat 命令来查看简化版的 diff 日志信息
* git log --graph
可以让 log 以更直观的方式来展示
* git log --pretty
可以让每次的 commit 在一行上显示，每一行就是一个 commit。

## git commit --amend
使用 --amend 选项的提交会与最后一次的提交进行合并生成一个新的提交，之前的提交会被废弃掉

## git tag
打标签其实是给特定的 commit 做个标记，类似于里程碑的东西。
* git tag -l
展示所有的标签
