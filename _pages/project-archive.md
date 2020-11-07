---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

## Table of Contents
[Data Visualization](#data-visualization)

* [COVID-19](#the-spread-of-covid-19-in-the-united-states)

* [The Solar System](#the-solar-system)

[Optimal Control](#optimal-control)

* [Double-Inverted Pendulum](#stabilizing-a-double-inverted-pendulum-system)

[Deep Learning](#deep-learning)

* [Style Transfer](#style-transfer)

* [Cancer Detection](#cancer-detection)

## _Data Visualization_
### <ins>The Spread of COVID-19 in the United States</ins>
Using data from [_The New York Times_](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv) and the GeoPandas python package, we can track the spread of the Coronavirus in the United States by county and visualizes the results. This animation shows the spread of positive cases from January 21, 2020 to June 21, 2020.

![Covid Spread](assets/images/covid_spread.gif)

### <ins>Inner Planetary Orbits in the Solar System</ins>
3D animation is a valuable tool in data visualization. Here, I animate the orbits of the four inner planets or our solar system. It was an invaluable exercise in both animating data and 3D plotting in Python. 

![Orbits](assets/images/planet_ani.gif)

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
![Style](/assets/images/download-1.png)

### <ins>Cancer Detection</ins>
In this project, I created a PyTorch radiologist. I utilized U-Net architecture to develop and train a deep neural network who learned how to identify which areas of a picture are cancerous. The model performed well, ultimately being able to correctly identify cancer with over 95% accuracy on the validation set. In this image, we see a picture of skin cells, followed by the groun truth indicating where cancer is present in the picture, and then my model's identification of the cancer.
![Cancer](/assets/images/download.png)
