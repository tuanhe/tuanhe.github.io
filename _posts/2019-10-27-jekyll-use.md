---
layout: post
title: Jekyll的使用指令
categories: [general, setup, demo]
tags: [jekyll, setup]
fullview: true
---

在本地看更改的效果的指令
jekyll serve
有时候在运行的过程中，会出现端口被占用而无法启动server的情况，可以kill掉进程
kill -9 6162
（其中6162）是进程号（PID）
如果你找不到进程号，那么就用ps aux | grep jekyll命令来查看，然后关闭服务器。

在前期安装的过程中，如果出现报错说缺少某个包，可以用这个指令来安装：
gem install jekyll -v '指定版本号'


