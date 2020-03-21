---
title: host文件更新，访问github
date: 2020-03-06 19:48:44
tags: 随笔

---

 # 前言

host文件更新，解决不能访问github问题。

<!---more--->

------

# 1、修改host文件内容，添加如下内容

192.30.253.113     github.com
185.199.108.153    github.github.io
151.101.72.133     assets-cdn.github.com
151.101.185.194    github.global.ssl.fastly.net

# 2、清除DNS解析程序缓存

win + r

cmd

ipconfig /flushdns