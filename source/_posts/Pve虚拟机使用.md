---
title: Pve虚拟机使用
date: 2019-07-23 12:48:14
tags: 随笔
categories: pve
---

------

# 前言 

Pve虚拟机简单使用。

# 一、Pve虚拟机安装

工具准备：

1. Pve虚拟镜像：proxmox-ve_5.3-2
2. 写盘工具：win32diskimager_0.9

安装过程：（略）

# 二、Pve下群晖安装

[引用安装过程链接](https://post.smzdm.com/p/a25r8mo2/)

关键命令：在putty里输入

```
chmod +x img2kvm

./img2kvm synoboot.img 104 vm-104-disk-1
```

