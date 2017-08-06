---
layout:     post
title:      利用Matlab Mobile获取安卓手机的数据，进行数据分析
subtitle:   利用MATLAB进行传感器数据分析
date:       2017-08-06
author:     HCY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - matlab_mobile
    - Android
---

# 下载APP
>* 在google play商店下载Matlab Mobile
>* 打开Matlab，在add on中下载Android Sensor Support from MATLAB
![1](https://Ceneses.github.io/img/2018_08_06_1.png)
![2](https://Ceneses.github.io/img/2018_08_06_2.png)
# 机脑匹配
![3](https://Ceneses.github.io/img/2018_08_06_3.png)
# 建立对象

m = mobiledev;

>接下来让我们通过一个实际的例子来详细描述MATLAB采集Android设备内置传感器的整个工作流程
# 案例讲解
## 手机发送数据方法
>*1*打开加速度传感器
>*2*发送数据给MATLAB
>*3*停止采集并查看数据
## 电脑接受数据方法
>*1*打开加速度传感器
>*2*发送数据给MATLAB
>*3*停止采集并查看数据
![4](https://Ceneses.github.io/img/2018_08_06_4.png)
# 查看数据

\[a, t\] = accellog(m);

![5](https://Ceneses.github.io/img/2018_08_06_5.png)
![6](https://Ceneses.github.io/img/2018_08_06_6.png)
# 绘制数据

plot(t, a);legend('X', 'Y', 'Z');xlabel('Relative time (s)');ylabel('Acceleration (m/s^2)');

![7](https://Ceneses.github.io/img/2018_08_06_7.png)
# 附录
*手机可以测量的数据*
![8](https://Ceneses.github.io/img/2018_08_06_8.png)
