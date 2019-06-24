# plants-vs-zombies-abu
通过一个植物大战僵尸项目来讲解前端中需要掌握的技能与知识点

## 项目开发人员

本项目主要分为3个人物(也就是3个分支)

1. 架构师Architect

负责项目的架构,提供项目所需要的API，接口，并对旧代码的重构

2. 功能新增人员Features

负责新增一个需求

3. bug修复人员fix

负责常见代码修复

## 如何学习项目

具体看git中的commit提交

克隆该项目：

`git clone https://github.com/wuhaohao1234/plants-vs-zombies-abu.git`

拉取代码

`git pull`

选择分支

`git branch`

合并主干分支

`git merge master`

### 代码回滚片段

`git log`查看代码commit纪录

它是以vim进行查看

每一个commit都有一段commit-id

当然也可以用` git log --pretty=oneline`查看

` git reset --hard HEAD^` 到上一个版本

当然也可以根据每一个commit-id到指定的版本

这里推荐一个工具souseTree，大家可以选择