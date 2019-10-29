---
layout: post
title:  "Tensorflow lite for Microcontroller 内存分配"
date:   2019-10-29 12:30:13
categories: tf-lite mcu
---
TF lite for micro 里有两种内存分配策略，分别是：  
*线性分配方式  
*贪婪算法分配方式  

线性分配方式是最简单的内存分配方式，为所有的tensr都分配内存，没有复用  

贪婪算法分配方式会复用内存，具体的过程后面再来补充完整，正在看中  


