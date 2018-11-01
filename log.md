# git log
## 概述
`git log`命令按照从先到后的顺序，列出版本库中所有的提交信息
## 用法
```
# 列出当前分支的版本commit

git log
```
```
# 简化列出每次commit的信息，只占一行

git log --oneline
```
```
# 以图形的方式打印 commit 信息

git log –pretty=format:’%h %ad | %s%d’ –graph –date=short
```