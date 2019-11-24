---
layout: post
title:  "量化的几个概念之一"
date:   2019-11-24 19:30:13
categories: tf-lite mcu quantization
---

训练后量化（Post-training quantization），即前期用一个浮点模型（float）训练好后，再将模型转换为定点模型（int8或者uint8）。
训练后量化会造成精度损失，需要重训练将精度拉回。



