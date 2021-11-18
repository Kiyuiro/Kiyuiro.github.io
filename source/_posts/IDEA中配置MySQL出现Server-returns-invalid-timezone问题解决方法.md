---
title: IDEA中配置MySQL出现Server returns invalid timezone问题解决方法
date: 2020-12-17 08:33:06
tags: [MySql, IDEA]
cover: https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/IDEA中配置MySQL出现Server-returns-invalid-timezone问题解决方法/cover-2021-11-18-11-02-37-0721a860f4791b9fba20da6dcccad7a3-5b904f.png
---

## 原因：
首先，出现该问题的原因是MySQL驱动jar中的默认时区是UTC。

UTC代表的是全球标准时间 ，但是我们使用的时间是北京时区也就是东八区，领先UTC八个小时。

因为时区不一致，所以提示Server returns invalid timezone. Go to 'Advanced' tab and set 'serverTimezone' property manually

## 解决方案：
服务器返回了无效的时区，去“高级”标签中手工设置“serverTimezon"属性值.

![]()

{%  image
    url="https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/IDEA中配置MySQL出现Server-returns-invalid-timezone问题解决方法/1-2021-11-18-11-02-37-31981e7b760dbd161068212e18c751ce-c4128e.png"
%}