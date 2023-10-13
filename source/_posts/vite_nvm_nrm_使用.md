---
title: Vite/nvm/nrm 使用
date: 2023-10-13 11:54:00
tags: [Node]
cover: https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/image/cover-2021-11-18-11-02-58-3aa107dbe9c59b9861a4ec6ea5752d77-5f239d.png
---

## Vite

### vite init

---

安装 `vite` 的最新版本

```powershell
npm init vite@latest
yarn create vite
```

### nvm

---

[nvm下载地址](https://github.com/coreybutler/nvm-windows/releases)

查看所有安装的 `node` 版本

```powershell
nvm list
```

查看所有 `node` 的官方版本

```powershell
nvm list available
```

安装对应版本号的 `node` 

```powershell
nvm install <版本号>
```

切换 `node` 版本

```powershell
nvm use <版本号>
```

### nrm

`nrm` 安装

```powershell
npm install -g nrm
```

查看所有源，星号表示当前使用源

```powershell
nrm ls
```

> 默认有的源  
> npm ---------- https://registry.npmjs.org/  
> yarn --------- https://registry.yarnpkg.com/  
> tencent ------ https://mirrors.cloud.tencent.com/npm/  
> cnpm --------- https://r.cnpmjs.org/  
> taobao ------- https://registry.npmmirror.com/  
> npmMirror ---- https://skimdb.npmjs.com/registry/  

使用源

```powershell
nrm use <名称>
```

添加源

```powershell
nrm add <名称> <源>
```

测试连接速度

```powershell
nrm test <名称>
```
