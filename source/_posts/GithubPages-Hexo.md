---
title: GithubPages + Hexo 博客建设教程
date: 2018-03-03 07:00:00
updated: 2018-03-03 07:30:00
categories:
- 折腾
- 教程
tags:
- Hexo
- GithubPages
---
这篇文 详细 的写了如何在GithubPages的基础上架设Hexo博客.
<!--more-->
## 没什么用的前言
感觉网上很多教程写的不怎么详细, 我在部署的时候也遇到了不少坑.
所以我想记录一下那些造成麻烦的细节, 至于有没有人看到就无所谓了. (自娱自乐ing)

## 相比WordPress/Typecho的优劣
GithubPages + Hexo的组合稳定性更强(纯静态页, 把源文件备份好就不会有问题),
但也因此丧失了一些便利性(直接在网页上码字/管理是Hexo不具备的).

## 准备
默认认为读者有一定耐心, 稍微会点英文或能熟练使用机翻, 了解电脑基础知识且使用Windows系统.
username.github.io实在很难看, 所以我推荐购买一个域名. 没考虑好IDC的话, 可以尝试[shop.mainstars.net](http://shop.mainstars.net)(专业硬广)

### 安装 Git
前往 [https://git-scm.com/](https://git-scm.com/download/win) 下载, 下载后直接运行安装即可.
重启电脑后会发现右键菜单多了"Git GUI", "Git Bash"等工具.

### 安装 Node.js
前往 [https://nodejs.org/](https://nodejs.org/en/download/) 下载, 双击运行安装.

### 注册 Github
前往 [https://github.com/](https://github.com/) 进行注册. 如果已经有账号可以直接略过.