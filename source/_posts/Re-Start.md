---
title: 'Re: Start'
date: 2018-03-03 00:30:00
updated: 2018-03-03 00:30:00
categories:
- 杂谈
tags:
- Hexo
- Blog
---
## 又一个新的Blog架好了.
<!--more-->
这个大概算是第四代, 前三代死因:
WSKaCrs.NET/WSNET 2016-2017: 想换域名乱改数据库导致500, 无奈删库跑路.
C.R.S'S (ZeroNet版) 201707-201711: 安装ZeroNet才能访问, 自定义有许多限制, 外网镜像经常挂.
C.R.S'S (Typecho版) 201801-201802: 服务器莫名其妙所有文件变成只读, 水平不够没法修.

## 那么怎么样才能保持网站稳定呢?
说到稳定还不要钱, 当然就是白嫖GithubPages的空间了. 不限流量, 超赞的.
本来打算用Jekyll, 后来一看比较复杂就懒得用了, 就Hexo吧. 这主题我也比较熟悉了.
至于CodingPages和其他杂七杂八的, 从稳定性来说根本就无法和Github相提并论.

## 修改名称
CRS' Space(C.R.S'S)这个名称感觉还是不太适合博客用.
想了想把博客的日文"ブログ"转成罗马音"Burogu", 合在一起就是CRS' Burogu.
设置为CRS' Space的一个子类, 原来的CRSS就给了[https://crs.mainstars.net](https://crs.mainstars.net)这个导航页.
至于域名wska.mainstars.net, 我打算做一个关于页面(短期内不会做出来, 毕竟要cool就要一堆动效)

## 更多功能, 更多繁琐, 更多折腾
不愧是还在开发的版本, 小功能就是比Typecho上的多.
右上角那个步骤按钮我心水很久了...

## 麻烦的留言功能
那几个看上去就活不长的评论功能我直接就不考虑了, DISQUS被墙,
想了想干脆用Github issues作评论算了.
界面勉强算美观和支持中文是我用gitalk的原因, gitment只有英文直接不考虑.
只会用Google翻译的英语渣想搞个东西是真的难...
在config里配置了一下, 迷之Error: Not Found  Error: Validation Failed二连把我难住了.
怀念Typecho的原生评论.

## 文件托管 / 主题更新
用几天的时间了解了一下Hexo, 我选择了稳定性最高的方案——源文件和生成文件全部放在Github.
如你所见([https://github.com/wskacrs/burogu](https://github.com/wskacrs/burogu)), master分支存放源文件, gh-pages分支存放生成文件.
如果我格盘重装系统(最近很有可能发生)或者换了电脑, 只需要从Github把源文件下载会来重新部署就可以.

因为Hexo-Material主题还是满足不了我瞎折腾的心, 这次我也会修改成Materialw.
修改项多了以后会单独发个帖子作为主题引导页, 这次所有文件都放在Github所以需要的话还请自行提取.