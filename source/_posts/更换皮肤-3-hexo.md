---
title: 更换皮肤 3-hexo
date: 2019-07-20 20:27:00
tags: 随笔
---

------

## 换皮肤

如果觉的自带的皮肤太难看。可以根据以下步奏更换皮肤
在[官网](https://hexo.io/themes/) 可以查看各种各样的皮肤，挑选自己喜欢的皮肤

这里以 `3-hexo` 这款皮肤为例（这款皮肤是笔者写的，效果可查看 [yelog.org](http://yelog.org/)）
1）进入皮肤的 `github` 官网，如[3-hexo](https://github.com/yelog/hexo-theme-3-hexo)的网址
找到 `clone or download` ,复制它的url：https://github.com/yelog/hexo-theme-3-hexo.git

2）进入 `myblog` 目录，打开 `git bash` 命令框，执行以下命令将皮肤下载到themes目录下

```
$ git clone https://github.com/yelog/hexo-theme-3-hexo.git themes/3-hexo
1
```

3) 修改 `myblog/_config.yml` 中的 `theme: landscape` 为 `theme: 3-hexo`

> 如果使用 `3-hexo` 主题的话，还需要注意两点
> ①因为主题使用了自己的高亮效果，还需要修改 `highlight enable: true` 的 `true` 改为 `false`。
> ②由于主题启用了文章字数统计功能，需要安装一个插件，在 `myblog` 目录下，打开 `git bash` 命令框，执行 `npm i --save hexo-wordcount` 即可

4) 重新渲染，启动服务器

```
$ hexo clean && hexo g && hexo s
```