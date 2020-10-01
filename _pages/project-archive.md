---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

## Table of Contents
[Optimal Control](#optimal-control)

* [Double-Inverted Pendulum](#stabilizing-a-double-inverted-pendulum-system)

[Deep Learning](#deep-learning)

* [Style Transfer](#style-transfer)

* [Cancer Detection](#cancer-detection)

## _Optimal Control_
### <ins>Stabilizing a Double-Inverted Pendulum System</ins>
I worked with a small group to find a way to balance the double pendulum above the
cart by only exerting force on the cart. Our approach utilized the Linear Quadratic Regulator feedback
controller to exert optimal control on the cart and stabilize the system. Read our [project report](https://drewjohnston13.github.io/optimal_control.pdf) for more information! Here are some examples of stabilization from different intial conditions:

![Stabilizing Double-Inverted Pendulum](https://drewjohnston13.github.io/video_2.gif)
![Stabilizing Double-Inverted Pendulum](https://drewjohnston13.github.io/video_3.gif)
![Stabilizing Double-Inverted Pendulum](https://drewjohnston13.github.io/video_4.gif)

## _Deep Learning_
### <ins>Style Transfer</ins>
As I explored interesting areas of deep learning, I came across style transfer. I used the VGG-19 Convolutional Neural Network model to fuse the style of one image with the content of another image. The results are a beautiful example of what can be accomplished with deep learning!
![Style](https://github.com/drewjohnston13/drewjohnston13.github.io/blob/master/assets/images/download-1.png)

### <ins>Cancer Detection</ins>
In this project, I created a PyTorch radiologist. I utilized U-Net architecture to develop and train a deep neural network who learned how to identify which areas of a picture are cancerous. The model performed well, ultimately being able to correctly identify cancer with over 95% accuracy on the validation set. In this image, we see a picture of skin cells, followed by the groun truth indicating where cancer is present in the picture, and then my model's identification of the cancer.
![Cancer](https://github.com/drewjohnston13/drewjohnston13.github.io/blob/master/assets/images/download.png)
