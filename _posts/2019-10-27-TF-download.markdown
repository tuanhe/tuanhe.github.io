---
layout: post
title:  "Tensorflow lite for Microcontroller的下载的安装"
date:   2019-10-27 12:00:13
categories: tf-lite mcu
---

关于tensorflow-lite for MCU的介绍可以参考这个[链接](https://tensorflow.google.cn/lite/microcontrollers/get_started)   
也可以直接下载tensorflow的源码，自己编译运行  
[下载地址](https://github.com/tensorflow/tensorflow)  
下载完成后，按照[README.md](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/micro/examples/micro_speech#getting-started)所述流程，编译运行  

在mac os上，命令为：  
```
make -f tensorflow/lite/experimental/micro/tools/make/Makefile micro_speech
```
编译完成后，执行测试程序  
```
tensorflow/lite/experimental/micro/tools/make/gen/osx_x86_64/bin/micro_speech
```  
对着电脑麦克风说出Yes或者No，可以看到屏幕上的log输出为：  
```
Heard yes (201) @4056ms
Heard no (205) @6448ms
Heard unknown (201) @13696ms
Heard yes (205) @15000ms
Heard yes (205) @16856ms
Heard unknown (204) @18704ms
Heard no (206) @21000ms
```  

