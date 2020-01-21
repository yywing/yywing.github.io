---
title: build
date: 2020-01-21 17:59:38
tags:
---

# 搭建博客

第一篇文章就讲一下如何用 github pages + hexo 搭建个人博客吧。

- 装 npm + node
- `npm install hexo-cli -g` 装 hexo
- `hexo init 文件夹名称` 初始化博客文件夹
- `cd 文件夹名称 && git init` 初始化 git 项目
- github 上创建项目
- `git remote add origin 项目 github 地址`
- 修改 `.travis.yml` 让 ci 自动 build 项目
- `git add . && git commit -m "init" && git push origin master` 将代码 push 到 github 上
- 在 github 项目 setting 中配置 gitpage 配置，选择分支，配置 CNAME


