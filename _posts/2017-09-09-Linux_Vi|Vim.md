---
layout:     post
title:      LINUX的Vi
subtitle:   Linux的Vim使用
date:       2017-09-09
author:     HCY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
     Linux
     vim
---
# Vim键盘
![vim](https://github.com/Ceneses/Ceneses.github.io/blob/master/img/2017-09-09-1.gif)
# Vim的三种模式
* 命令模式(Command mode)
* 插入模式(Insert mode)
* 底线命令模式(Last line mode)
```
i切换到插入模式，以输入字符。
x删除当前光标所在处的字符。
:切换到底线命令模式，以在最底一行输入命令。
```
# 输入模式
```
字符按键以及Shift组合，输入字符
ENTER，回车键，换行
BACK SPACE，退格键，删除光标前一个字符
DEL，删除键，删除光标后一个字符
方向键，在文本中移动光标
HOME/END，移动光标到行首/行尾
Page Up/Page Down，上/下翻页
Insert，切换光标为输入/替换模式，光标将变成竖线/下划线
ESC，退出输入模式，切换到命令模式
```
# 底线命令模式
* 在命令模式下按下:（英文冒号）就进入了底线命令模式。
* 底线命令模式可以输入单个或多个字符的命令，可用的命令非常多。
![1](https://github.com/Ceneses/Ceneses.github.io/blob/master/img/2017-09-09-2.jpg)
```
 q 退出程序
 w 保存文件
 ESC键可随时退出底线命令模式
```
# 一般模式切换到编辑模式的可用的按钮说明
![3](https://github.com/Ceneses/Ceneses.github.io/blob/master/img/2017-09-09-3.jpg)
![4](https://github.com/Ceneses/Ceneses.github.io/blob/master/img/2017-09-09-4.jpg)

|字符|解释|
|:--|:---|
|i/I|进入插入模式(Insert mode)：i 为『从目前光标所在处插入』， I 为『在目前所在行的第一个非空格符处开始插入』|
|a/A|进入插入模式(Insert mode)：a 为『从目前光标所在的下一个字符处开始插入』， A 为『从光标所在行的最后一个字符处开始插入』|
|o/O|进入插入模式(Insert mode)：这是英文字母 o 的大小写。o 为『在目前光标所在的下一行处插入新的一行』； O 为在目前光标所在处的上一行插入新的一行！|
|r/R|进入取代模式(Replace mode)：r 只会取代光标所在的那一个字符一次；R会一直取代光标所在的文字，直到按下 ESC 为止|
