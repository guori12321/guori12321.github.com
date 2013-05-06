---
layout: post
title: "关于XFCE与双屏"
date: 2013-05-06 10:56
comments: true
categories: 
---

在实验室有一个22寸的显示器，于是就想把它接到我的笔记本上来用。在Windows下用着很舒服，直接拖拽就好，两个显示器高度不同调整起来也很方便。但在Linux下，就没有找到合适的办法。

因为实在用不习惯GNOME 3，而fall back GNOME 2又不怎么稳定，所以说，就转用XFCE了，但XFCE对双屏的支持实在不行。使用命令xrandr --output VGA-0 --left-of LVDS来支持双屏，要么我的外接显示器的分辨率过低，要么左右两个屏幕的显示区域会重叠很大一部分。后来又使用ARandR这个GUI软件来设置，如果想横着显示的话，会出现提示“显示范围超出虚拟屏幕范围”的信息，原来这个所谓的`虚拟屏幕范围`这么小啊。！[截图](./XFCE&&MultiScreen.png)

怀疑是XFCE这样的轻量级桌面给`虚拟屏幕`的内存太少了。

看来XFCE是不可能很好的支持双屏了，我还是接着折腾`KDE`吧...
