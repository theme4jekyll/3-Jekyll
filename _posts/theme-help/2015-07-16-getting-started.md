---
layout: post
title: Getting Started
categories: theme-help
tags: []
date: 2015-07-16T23:06:41+08:00
---
# 开始使用

当你成功部署了本站后，就可以开始使用了。

## 新建文章

本站使用octopress来新建一篇文章

    bundle exec octopress new post "Post Title"

 这样就会在_post文件夹下面建立一个名叫Post-Title的文章。
 本站左栏默认使用categories来区分，所以最好利用下面的命令：
 
	 bundle exec octopress new post "Post Title" --dir cat

这样就会在_post/cat/目录下建立这篇文章，并且文章具有categories: cat这个属性。在网站左栏分类中就会出现这个cat。