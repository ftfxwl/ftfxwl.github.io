---
title: hexo博客主题next安装及配置
date: 2019-04-22 18:46:23
tags: 随笔
categories: hexo
---

# 前言

hexo 博客主题next安装及配置方法

# 安装

在hexo博客主目录运行 Git bash，执行下列命令，下载安装next主题。

> `$ git clone https://github.com/theme-next/hexo-theme-next themes/next`

# 配置

hexo配置有两个_config.yml文件，一个是主目录下的，一个是theme主题目录下的。_

## 博客语言

_安装next主题后，首先查看next目录下的languages文件夹下的简体中文文件名是什么，如zh-CN.yml，然后，将此名字填入主目录下的_config.yml文件中的language: 位置上，使得next主题支持简体中文。

## next 主题类型选择

> Schemes
> #scheme: Muse
> #scheme: Mist
> #scheme: Pisces
> scheme: Gemini

选用哪个主题类型，即将其前面的#去掉即可。