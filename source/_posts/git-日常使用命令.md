---
title: git 日常使用命令
date: 2019-07-07 13:24:54
tags: 随笔
---

# 在本地对博客进行修改（添加新博文、修改样式等等）后，通过下面的流程进行管理。

1. 先git pull origin hexo同步远程仓库
2. 依次执行git add .、git commit -m “…”、git push origin hexo指令将改动推送到GitHub（此时当前分支应为hexo）；
3. 然后才执行hexo g -d发布网站到master分支上。