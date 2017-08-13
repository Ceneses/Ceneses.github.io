---
layout:     post
title:      Android version & API
subtitle:   Android version发展史和API版本和android版本之间的关系
date:       2017-08-13
author:     HCY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - Android
    - API
---
# Android_version
> * Alpha|Beta版本
> * Android操作系统有两个预发布的内部版本，它们分别是原子小金刚（Astro）和机器人班亭（Bender，电视动画《Futurama》角色）
> * 纸杯蛋糕（Cupcake）----->Android1.5基于Linux kernel 2.6.67
> * 甜甜圈（Donut）--------->Android 1.6基于Linux Kernel 2.6.29
> * 闪电泡芙（Eclair）------>Android 2.0/2.0.1/2.1基于Linux Kernel 2.6.29
> * 冻酸奶（Froyo）--------->Android 2.2/2.2.1/2.2.2/2.2.3基于Linux Kernel 2.6.32
> * 姜饼（Gingerbread）----->Android 2.3基于Linux Kernel 2.6.35
> * 蜂巢（Honeycomb）------->Android 3.0.1/3.1/3.2基于Linux Kernel 2.6.36
> * 冰淇淋三明治（Ice Cream Sandwich）---->Android 4.0基于Linux Kernel 3.0.1
> * 果冻豆（Jelly Bean）---->Android 4.1/4.2/4.3基于Linux Kernel 3.4.0
> * 奇巧巧克力（KitKat）---->Android 4.4/4.4.1/4.4.2/4.4.3/4.4.4基于Linux Kernel 3.4.0
> * 棒棒糖（Lollipop）------>Android 5.0/5.0.1/5.0.2基于Linux Kernel 3.4.0
> * 棉花糖（Marshmallow）--->Android 5.1/5.1.1基于Linux Kernel 3.4.0
> * 牛轧糖（Nougat)--------->Android 6.0/6.0.1基于Linux Kernel 3.14.52
# API 级别
>API 级别是一个对 Android 平台版本提供的框架 API 修订版进行唯一标识的整数值。
>Android 平台提供了一种框架 API，应用可利用它与底层 Android 系统进行交互。 该框架 API 由以下部分组成：
+ 一组核心软件包和类
+ 一组用于声明清单文件的 XML 元素和属性
+ 一组用于声明和访问资源的 XML 元素和属性
+ 一组 Intent
+ 一组应用可请求的权限，以及系统中包括的权限强制执行。
+ 每个后续版本的 Android 平台均可包括对其提供的 Android 应用框架 API 的更新。
> 下表列出了各 Android 平台版本支持的 API 级别。

|平台版本|API 级别| VERSION_CODE |备注|
|:-------|:-------|:-------|:-------|
|Android 7.0|	24	|N	|平台亮点|
|Android 6.0|	23|	M	|平台亮点|
|Android 5.1|	22	|LOLLIPOP_MR1	|平台亮点|
|Android 5.0	|21|	LOLLIPOP|
|Android 4.4W|	20	|KITKAT_WATCH	|仅限 KitKat for Wearables|
|Android 4.4	|19	|KITKAT	|平台亮点|
|Android 4.3|	18|	JELLY_BEAN_MR2|	平台亮点|
|Android 4.2、4.2.2	|17	|JELLY_BEAN_MR1	|平台亮点|
|Android 4.1、4.1.1	|16|	JELLY_BEAN|	平台亮点|
|Android 4.0.3、4.0.4	|15|	ICE_CREAM_SANDWICH_MR1	|平台亮点|
|Android 4.0、4.0.1、4.0.2	|14	|ICE_CREAM_SANDWICH|
|Android 3.2	|13	|HONEYCOMB_MR2	|
|Android 3.1.x	|12|	HONEYCOMB_MR1	|平台亮点|
|Android 3.0.x	|11	|HONEYCOMB	|平台亮点|
|Android 2.3.4|
|Android 2.3.3	|10	|GINGERBREAD_MR1	|平台亮点|
|Android 2.3.2|
|Android 2.3.1|
|Android 2.3	|9	|GINGERBREAD|
|Android 2.2.x	|8	|FROYO	|平台亮点|
|Android 2.1.x	|7	|ECLAIR_MR1	|平台亮点|
|Android 2.0.1	|6	|ECLAIR_0_1|
|Android 2.0	|5|	ECLAIR|
|Android 1.6	v|4|	DONUT	|平台亮点|
|Android 1.5	|3	|CUPCAKE|	平台亮点|
|Android 1.1	|2	|BASE_1_1	|
|Android 1.0	|1	|BASE	|
# 链接
+ [uses-sdk](https://developer.android.com/guide/topics/manifest/uses-sdk-element.html#uses)
+ [Android version history](https://en.wikipedia.org/wiki/Android_version_history)
