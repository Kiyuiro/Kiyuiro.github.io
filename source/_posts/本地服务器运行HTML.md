---
title: 本地服务器运行HTML
date: 2021-11-09 08:37:06
tags: [HTML, Node]
cover: https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/本地服务器运行HTML/cover-2021-11-18-11-03-07-71f9e96715716d8aebafcf10f15f2a40-1978b0.jpg
---

## 原因
之前在编写JS代码的时候使用ES6语法对其他JS文件进行导入, 就需要对html文件中的script标签添加type="module".
但这样会导致程序内的路径从本地相对路径变为服务器的路径, 导致查找不到需要的文件. 因为是直接运行, 不想其他服务
一样, 启动时都会使用一个本地的端口作为服务器, 因此需要一个在运行本地html文件时, 像运行在服务器上一样的模块.

## 解决
首先是我们需要安装一个 http-server 的服务.
``` bash
# 建议全局安装, 以便于以后的使用
npm install http-server -g
```

安装好之后, 就可以在当前html目录下执行http-server, 就启动一个http服务.
启动后进行给出的端口就可以了.
```bash
http-server
```

## 注意
开启服务之后, 浏览器会缓存当前端口的内容, 因此在更换浏览的内容或修改代码后, 必须要清空浏览器
的缓存, 这样才能正常使用, 否则页面的内容不会出现变更.

