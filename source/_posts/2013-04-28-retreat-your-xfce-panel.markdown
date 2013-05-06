---
layout: post
title: "retreat your xfce panel"
date: 2013-04-28 05:50
comments: true
categories: 
---
# 如何把XFCE的面板恢复到默认状态

Gnome 3实在是用不明白啊。之前都是fall back到Gnome 2来用的，但随着Ubuntu和Gnome的不断发展，fall back变得越来越不稳定，于是乎我就投奔了XFCE。

这两天自己定制XFCE的时候，不小心把面板玩坏了。具体来说，就是把面板上显示当前正在运行的程序的那一部分搞没了，而且不知道怎么搞回来，搞的我只能用Alt + Tab来切换程序。

在配置Linux最不爽的地方就是，出了小问题以后就要花大量的时间来弥补。网上查了半天，没有看到能用的方法。后来，用**英文搜索'XFCE panel default'**，就直接找到可行的方法了。看来中文的资料还是太少了。

解决的基本思路是，把自己的面板配置文件删除掉，这样在XFCE加载的时候，就会加载默认的面板配置了。代码如下：
'''

'''
