---
layout: post
title:  "物流机器人工作日报 2016／04/29"
date:   2016-04-27 20:51:11
categories: blog
---

今日工作：Cammera界面按键功能开发，以及代码整理，必要注释添加。
明天计划：完成Cammera界面按键功能开发，开始测试阶段，并继续对代码的整理工作。
出现的问题:
	MFC提供了两个重载版的AfxBeginThread，一个用于用户界面线程，另一个用于工作者线程。
	Motion程序即是Client也是server，server部分的函数在server_thd中，而client函数部分在ConnectThread类中。

