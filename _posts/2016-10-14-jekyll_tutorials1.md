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
> 1、打开当前目录下的 _config.yml 文件，把 gems: [jekyll-paginate,jekyll-sitemap] 换成 gems: [jekyll-paginate] ，也就是去掉jekyll-sitemap。
> 2、升级 jekyll 版本，我当前的是 jekyll 3.1.2 。
>* 如果你想使用我的模板请把 _posts/ 目录下的文章都去掉。
>* 修改 _config.yml 文件里面的内容为你自己的。
> 问题：最近 `baixin.io`
> 解决：里面的baixin.io修改
