---
title: GIT首次提交项目
subtitle: 
header-img: 'git_black.png'
title-color: '#fff'
display: true
catalog: false
date: 2019-11-18 15:23:08
tags:
- coding
- git
- command
categories:
- git
---

### 首次提交项目命令
``` bash
# 初始化git项目
git init
# 把所有文件加入版本管理
git add -A
# 提交到本地仓库
git commit -m "初始化项目"
# 添加远程仓库，git@github.com:aceHubert/ace-vue.git为远程仓库地址
git remote add origin git@github.com:aceHubert/ace-vue.git
# 推送到远程仓库
git push -u origin master

```

### 设置映射远程分支
``` bash
git branch --set-upstream-to=origin/master master
```