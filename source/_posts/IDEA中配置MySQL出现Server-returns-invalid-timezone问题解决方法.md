---
title: IDEA中配置MySQL出现Server returns invalid timezone问题解决方法
date: 2020-12-17 08:33:06
tags: [MySql, IDEA]
cover: /images/IDEA中配置MySQL出现Server-returns-invalid-timezone问题解决方法/cover.jpg
---

## 原因：
首先，出现该问题的原因是MySQL驱动jar中的默认时区是UTC。

UTC代表的是全球标准时间 ，但是我们使用的时间是北京时区也就是东八区，领先UTC八个小时。

因为时区不一致，所以提示Server returns invalid timezone. Go to 'Advanced' tab and set 'serverTimezone' property manually

## 解决方案：
服务器返回了无效的时区，去“高级”标签中手工设置“serverTimezon"属性值.
{%  image
    url="/images/IDEA中配置MySQL出现Server-returns-invalid-timezone问题解决方法/1.png"
%}