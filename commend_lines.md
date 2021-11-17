1. git status: 让我们时刻掌握仓库当前的状态(是个好命令)
2. git diff: diff-different 显示相比上次提交的改变内容
3. git log: 查看历史提交信息, 可以在后面添加`--pretty=oneline`将一次提交信息汇成一行
4. git reset: 可以用于历史回退, 当前版本由HEAD指针指向, 前一个版本为`HEAD^`, 一次类推`HEAD^^, HEAD^^^, HEAD~100`
   使用时 `git reset --hard HEAD^(或是commit_id(只需前几位))`
5. git reflog: 查询每次的指令
6. 使用`git add +file`命令是修改添加到暂存区, 使用`git commit`命令是将暂存区的所有修改添加到当前分支(master)中
7. `git restore + file`: 撤销修改操作: 1. 没有使用`git add`, 撤销修改, 2.使用`git add`, 撤销修改到上一次commit