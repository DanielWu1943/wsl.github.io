---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 硕士毕业于中国科学院大学上海微系统与信息技术研究所， 2022 - 2025
* 本科毕业于西安电子科技大学， 2018 - 2022

项目经历
======
* 2023.11 - 2024.8 : 面向电力线载波通信的STM32开发(通信协议实现)
  * 基于STM32L496进行通信协议设计与开发：基于FreeRTOS操作系统，搭建STM32L496的驱动程序。
  * 通信协议设计：针对高压电缆信道特征，基于G3-PLC标准和时分复用设计通信协议。
  * 功能开发与调试：基于ST8500开放的接口，在STM32L496上实现对ST8500的控制和数据交互，完成通信协议的功能开发，并基于设计的PCB版进行软硬功能调试。

* 2022.10 -2023.01 : 基于YOLOv5的数字表计数值识别
  * 数据集制作：采集数字表计图像，进行标注，制作训练与测试用数据集。
  * 模型训练与推理：在docker上使用YOLOv5进行训练，生成权重模型。推理使用TensorRT进行模型加速，并基于pyqt5制作交互界面。


技能
======
* Matlab
* Python
  * PyTorch
* C
  * 嵌入式开发
  * RUST
  * rCore
  * CUDA

论文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
