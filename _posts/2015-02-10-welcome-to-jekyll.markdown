---
layout: post
title:  "基于自然演化的机构设计系统（一）"
date:   2018-03-22 22:08:54
categories: 构想
tags: 构想
excerpt: 一些初步想法
mathjax: true
---
## 线索

某些古生物的身体构造是随着自然演化不断改变，从而使自己不断适应环境的。例如[奇虾][qixia]的捕食器官从一根用于勾取猎物的触手演化为只用于滤食的触须，或是移动方式从游泳肢的屈伸变成依靠“鳍”这样的器官来驱动身体。

[qixia]:      https://baike.baidu.com/item/奇虾/748050?fr=aladdin

令我感兴趣的是，如果我们可以设计一套演算方法去模拟这种自然演化过程，输入一种初始机构，让其在随后的演化计算中不断优化自己的形态，最终得到一个新的东西，这或许将使某一类型的机械设计变得方便快捷起来！

![1.png](https://kohn172.github.io/images/2.png)

当开始这一想法时，我们需要把这一程序里有待输入的“动物”看作是一个孤立的机械系统，而这一系统内各功能性器官的演化过程或许可以看作是各机构的运动方式随着环境的变化而做出了相应的调整。

如果要把甲壳动物视作某种机械，它们的肢节首先令我联想到了连杆，那么就让我们沿着这一线索入手来构建一个生物单元。第一个需要解决的问题是`如何得到一个能画出任意曲线轨迹的连杆机构`


## 自动生成的连杆系统

锈规作图问题




[k]:      /Users/kohn/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/5dc3dda4a64089121865f347c149449a/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/201553268554_.pic_hd.jpg















