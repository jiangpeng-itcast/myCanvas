这是第一个功能
回滚到上次备份的版本  “git reset --hard Head^^”里面的尖尖表示回到上次的储存
1、也可以使用快捷操作，直接回退到第几次 “git reset --hard Head~2” 表示回退到倒数第三次
### 查看分支  “git branch”
### 当demo页面下又不希望备份的文件时，可以在给文件同级上创建 “.gitignore”文件，文件里写上"/.idea"(idea表示该文不需要备份的文件夹)
1、#表示注释行文字，可以给“.gitignore”文件里写上哪些文件不需要备份

### “git reflog” 表示查看每一次对版本的切换和提交


##  切换分支 “git branch dev”表示创建分支成功   然后切换到分支  “git checkout dev”


1、创建并切换到指定分支  ”git checkout -b dev“


最后在分支上完成功能后切换回到主分支上  “git checkout master”

2、然后在主分支下，可以将当前的分支可dev分至合并  “git merge dev“

3、最后可以将dev分支删除  ”git branch -d dev“ 