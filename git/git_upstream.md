# 开源项目开发流程

## fork 代码
从开源项目（upstreamURL） fork 到自己的 github 库（originURL）

## 创建开发分支
- git clone originURL
- git checkout -b develop
- git push origin develop

## 添加上游
- git remote add upstream upstreamURL

## 提交代码
- git commit (develop)
- git pull --rebase upstream master (同步 upstream)
- git rebase 过程（解决冲突）
- git push origin develop 

## 提 PR
如果 develop 与 upstream 没有 commit 冲突，直接创建 merger PR,如果有冲突，需要 git pull --rebase 之后再提 PR
