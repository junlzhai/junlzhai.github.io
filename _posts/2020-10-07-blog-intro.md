---
layout: post
title: 博客模板功能介绍
date: 2020-10-07
tags: jekyll
description: "jekyll+Github，搭建自己的博客"
---

## 博客特性

苟富贵

## 博客模块

### _config.yml

`_config.yml` 是博客的配置文件，整个站点的信息都在这修改，想要把我的模板改成你自己的也需要修改`_config.yml` 

**重要字段说明** 

* enableToc: 是否开启文章自动生成目录，设置为false文章不会自动生成目录
* comment/livere: livere评论系统，支持微信、qq、微博、豆瓣、twitter等登录后可以直接评论
* comment/disqus: disqus评论系统，支持facebook、twitter等登录后可以直接评论
* social/weibo、github、zhihu、jianshu等: 个人站底部展示的微博等三方社交按钮，点击后直接跳转到个人微博或其他社交主页
* baidu/id: 百度统计，用来统计你个人站点的用户访问情况
* ga/id: google统计，用来统计你个人站点的用户访问情况

_config.yml 文件除以上字段还有一些可以自行修改，例如title之类的字段

### _posts

`_posts` 目录是用来存放文章的目录，写新文章，直接放在这个目录即可

使用博客模板时，请把博客自带的文章给去掉，如果想使用博客自带的文章请 `注明出处`。



