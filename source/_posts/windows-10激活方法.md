---
title: windows 10激活方法
date: 2019-05-09 15:09:03
tags: 随笔
---

# 前言

windows 10激活方法

# 查看激活状态

管理员权限打开windows powershell，输入slmgr.vbs -xpr，回车确认。

# 激活方法

1. 右击开始，打开Windows powershall（管理员）输入slmgr /ipk P9C2R-NM3BW-JR7DG-2R38J-D9MPF

回车，提示成功安装了产品密钥。

2. 输入slmgr /skms kms.xspace.in设置激活名称，回车。
3. 输入slmgr /ato激活命令，提示激活成功。
4. 输入slmgr.vbs -xpr查看是否永久激活。

