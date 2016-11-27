# learngit

设置自己的用户名和邮箱
git config --global user.name "Your name"
git config --global user.email "you@example.com"

**修改提交之间有一个缓存区
    提交到缓存区 git add . 当前所有修改到缓存区，也可以单独指定
    git diff --cached 查看缓存区和本地仓库的差异
    git diff HEAD 查看已缓存和当前的区别
    git diff 查看当前未缓存的和本地仓库的区别
    git diff --stat 显示摘要

**撤销缓存区里面的一个更改, 例如hello.go git reset HEAD -- hello.go
>>git rm file 将file从文件缓存区、本地目录中移除
>>git rm file --cached 从缓存区移除，保存到本地目录中的

***分支操作
>> git branch 列出可用的分支
>> git branch dev 创建dev分支
>> git checkout -b dev 检查dev分支是否存在，不存在就创建，并切换过去
>> git branch -d dev 删除分支dev

