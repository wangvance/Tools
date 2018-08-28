# Git overview

## git clone
将远程仓库中的代码克隆到本地

## git status
根据git status 提示内容，可以得到三种命令的使用:  
* 暂存文件的命令: git add <filename>
* 放弃未暂存文件的修改命令: git checkout -- <filename>
* 将修改的文件暂存并提交: git commit -a

## 命令总结
* git status: 查看当前仓库中文件的状态
* git status -s: 文件状态的简写( M - 修改, A - 添加, D - 删除, R - 重命名)
* git add <filename>: 将文件进行暂存，以便 commit
* git reset HEAD <filename>: 将已经暂存的文件进行撤销，回到未暂存的状态
* git checkout -- <filename>: 撤销对尚未暂存文件的修改，该操作不可逆，慎用
* git commit -a: 对那些被修改的文件但尚未暂存和提交的文件进行暂存和提交，对未暂存的新增文件不起作用
* git commit: 对暂存区的文件进行提交到本地仓库
* git push: 将本地仓库已经提交的内容发布到远端

## 查看和修改远端地址
### 添加远端仓库地址

