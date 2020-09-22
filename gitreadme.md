# 基础命令

```git
$mkdir leargit                                       创建文件夹   
$cd leargint                                         进入文件夹
$pwd                                                 显示所在目录
$git init                                            初始化文件夹作为git仓库
$git add <file>                                      把file添加到暂存区
$git commit -m"revise"                               存档，注释revise
$git status                                          显示当前工作区状态
$git diff readme.txt                                 对比当前文件
$git log                                             显示版本历史
$git reset --hard <edition>                          返回edition版本
$git reflog                                          显示历史存档改变记录
$git checkout -- <file>                              撤销更改
$git reset HEAD readme.txt                           返回存档
$rm <file>                                           删除文件夹中文件
$git rm <file>                                       删除存档中文件
```

# 与Github链接推送的命令

```
$git remote add origin git@github.com:michaelliao/learngit.git
与远程仓库origin建立链接
$git push -u origin master
把本地仓库提交到远程空仓库
$git push -u origin master
强制把本地仓库提交到远程空仓库
```



# 分支命令

```
$git checkout -b dev                                 创建名称为dev的分支并切换分支
$git branch dev                                      创建分支，名称为dev
$git checkout dev                                    切换到dev分支
$git branch                                          查看当前分支
$git merge dev                                       合并dev至当前分支
$git branch -d dev                                   删除dev分支

```

