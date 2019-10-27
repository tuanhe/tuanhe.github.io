---
layout: post
title:  "Jekyll的使用命令"
date:   2019-10-27 11:48:13
categories: jekyll command
---

进入到下载的kejyll主题根目录后， 
运行命令  
`jekyll serve`  
即可在本地端口预览网页（打开浏览器，输入http://127.0.0.1:4000）
可能会遇到报错，如下:  
```
in `check_for_activated_spec!':   
You have already activated i18n 1.7.0, but your Gemfile requires i18n 0.9.5. 
Prepending `bundle exec` to your command may solve this. (Gem::LoadError)
```  
则运行命令  
`bundle exec jekyll serve`  
即可

jekyll serve --detach 和jekyll serve命令相同，但是会脱离终端在后台运行，如果你想关闭服务器，可以使用命令    
`kill -9 1234`  
其中1234 是进程号（PID）。  
如果你找不到进程号，那么就用   
`ps aux | grep jekyll`   
命令来查看，然后关闭服务器。


