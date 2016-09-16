---
layout: post
title: "github博客文章时间显示问题"
date: 2016-09-14 12:16:26 +0800
comments: true 
---

github博客文章时间显示问题
============
今天用markdown写文章时，在github博客上的列表中实现不出来，搞了好久，也没找到解决方案。

在[网上](http://ju.outofmemory.cn/entry/244024)找到如下解决方案：

偶然在Jekyll官网的3.0升级指南里，看到一个关于时区问题的说明。给头里的date部分加上了+0800是时区标识，即可以显示正常

> date: 2016-09-16 12:11:36 +0800


