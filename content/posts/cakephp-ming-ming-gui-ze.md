---
title: "CakePHP 命名规则"
date: 2013-10-17T09:26:00+08:00
categories: 
draft: false
toc: true
---

**表名和控制器为复数，模型名为单数。**

  1. 一般来说，文件名是由下划线将单词分开，但是类名通常使用驼峰命名法。
  2. 模型类别名称是单数且使用骆驼命名法。
  3. 数据表名称对应到CakePHP 模型是复数且以下划线分隔单字。
  4. 控制器的类别名称是复数，使用骆驼命名法，并在最后加上Controller 。
  5. 如果一控制器的函数已加上下划线，函数将不可直接从网站上取存，但是可以供内部使用。
  6. url 应该由小写字母和下划线组成。
  7. 网址遵循下面这种形式 http://域名/Cake应用文件夹名/控制器名/操作名
  8. Cake所有的视图文件都保存在app文件夹下的视图文件夹里，在这个文件夹里，单个控制器的所有视图都被保存在以控制器命名的子文件夹里