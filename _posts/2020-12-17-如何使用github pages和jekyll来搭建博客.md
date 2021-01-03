---
layout: post
title: 如何使用github pages和jekyll来搭建博客
tags: [博客搭建, jekyll]
categories: 应用流程
---

搭建博客用来总结自己学习的思考，同时也记录自己的所看、所听、所读、所思。第一篇文章先总结下如何使用github pages和jekyll来搭建博客。

# 一、需要的技术知识：

1. git
2. bash
3. html、css
4. markdown

# 二、实施步骤

1、[创建github reposotory](https://pages.github.com/)

repo名字务必使用< username >.github.io，其中< username >用你自己的账户名来代替

2、[安装Jekyll](https://jekyllrb.com/docs/)

Jekyll的运行依赖ruby，要尽量使用ruby最高版本，笔者用的是2.7.2
，建议使用[rvm](https://rvm.io/rvm/install)来安装比较靠谱。bundle install之前先配置 $ bundle config mirror.https://rubygems.org https://gems.ruby-china.com


3、[使用Jekyll模版](http://jekyllthemes.org/)

模版有一套默认的layout和样式，一次性确认好模版之后。日常博客的内容更新，只需要在_posts中编写md文件即可。

# 三、选择一个markdown编辑器

mac环境下建议使用macdown

