---
layout: post
title: Jekyll搭建个人博客
date: 2016-10-14
tags: 博客
---


```
$ gem install jekyll
```


![](/images/posts/jekyll/image1.png)


### 目录结构
　
　Jekyll 的核心其实是一个文本转换引擎。它的概念其实就是： 你用你最喜欢的标记语言来写文章，可以是 Markdown，也可以是 Textile,或者就是简单的 HTML, 然后 Jekyll 就会帮你套入一个或一系列的布局中。在整个过程中你可以设置URL路径, 你的文本在布局中的显示样式等等。这些都可以通过纯文本编辑来实现，最终生成的静态页面就是你的成品了。


title: 显示的文章名， 如：title: 我的第一篇文章                    
date: 显示的文章发布日期，如：date: 2016-10-16
categories: tag标签的分类，如：categories: 随笔

注意：文章头部格式必须为上面的，.... 就是文章的正文内容。

我写文章使用的是 Sublime Text2 编辑器，如果你对 markdown 语法不熟悉的话，可以看看[作业部落的教程](https://www.zybuluo.com/)




> 1、打开当前目录下的 _config.yml 文件，把 gems: [jekyll-paginate,jekyll-sitemap] 换成 gems: [jekyll-paginate] ，也就是去掉jekyll-sitemap。
> 2、升级 jekyll 版本，我当前的是 jekyll 3.1.2 。


>* 如果你想使用我的模板请把 _posts/ 目录下的文章都去掉。
>* 修改 _config.yml 文件里面的内容为你自己的。



> 问题：最近 `baixin.io`
> 解决：里面的baixin.io修改
