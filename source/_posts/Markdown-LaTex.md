---
title: Markdown LaTex
date: 2021-11-06 12:49:30
tags: [数学, Markdown]
cover: https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/Markdown-LaTex/cover-2021-11-18-11-03-03-976a1062189e17c386443ffab043f457-d887cc.png
mathjax: true
---

## 公式排版
* 行内公式: 使用 `$ $` 包裹公式
  * 例如 `$y=x^2+k$` $\to$ $y=x^2+k$
* 独立公式: 使用 `$$  $$` 包裹公式
  * 例如: `$$ \Delta = \frac{-b\pm\sqrt{b^2-4ac}}{2a} $$`
  $$ \Delta = \frac{-b\pm\sqrt{b^2-4ac}}{2a} $$

$\$

## LaTex 基础语法

###  上下标

| LaTex 语法 | 效果 |
| :---: | :---: |
| `x_{1}` | $x_{1}$ |
| `x^{a}` | $x^{a}$ |
| `x^{a}_{1}` | $x^{a}_{1}$ |

### 根式和分式

| LaTex 语法 | 效果 |
| :---: | :---: |
| `\displaystyle` | 修复大小(建议每个公式开头添加) |
| `\frac{a}{b}` | $\frac{a}{b}$ |
| `\displaystyle\frac{a}{b}` | $\displaystyle\frac{a}{b}$ |
| `\sqrt{a}` | $\sqrt{a}$ |
| `\sqrt[3]{a}` | $\sqrt[3]{a}$ |
| `\surd[a^2+b^2]` | $\surd[a^2+b^2]$ |

### 常见运算符

|       |       |       |       |       |       | 
| :---: | :---: | :---: | :---: | :---: | :---: |
| `\le` | $\le$ | `\ge` | $\ge$ | `\equiv` | $\equiv$ |
| `\pm` | $\pm$ | `\cdot` | $\cdot$ | `\div` | $\div$ |
| `\cup` | $\cup$ | `\cap` | $\cap$ | `\angle` | $\angle$ |
| `\lor` | $\lor$ | `\land` | $\land$ | | |
| `\forall` | $\forall$ | `\exists` | $\exists$ | | |
| `\gets` | $\gets$ | `\to` | $\to$ | `\leftrightarrow` | $\leftrightarrow$ |
| `\uparrow` | $\uparrow$ | `\downarrow` | $\downarrow$ | `\updownarrow` | $\updownarrow$ |
| `\lfloor` | $\lfloor$ | `\rfloor` | $\rfloor$ | | |
| `\lceil` | $\lceil$ | `\rceil` | $\rceil$ | | |

### 一些特殊运算

| LaTex 语法 | 效果 |
| :---: | :---: |
| `\overline{m+n}` | $\overline{m+n}$ |
| `\underline{m+n}` | $\underline{m+n}$ |
| `\displaystyle\sum_{i=0}^{n}i` | $\displaystyle\sum_{i=0}^{n}i$ |
| `\displaystyle\int_{0}^{\frac{\pi}{2}}` | $\displaystyle\int_{0}^{\frac{\pi}{2}}$ |
| `\displaystyle\prod_{a}^{b}` | $\displaystyle\prod_{a}^{b}$ |
| `\displaystyle\lim_{x \to \infty}` | $\displaystyle\lim_{x\to\infty}$ |

### 附表

![](https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/Markdown-LaTex/希腊字母-2021-11-18-12-32-49-73005227c712bd276e3c34bc4f8ef0d9-4bcaa6.png)

![](https://cdn.jsdelivr.net/gh/Kiyuiro/Images@master/Markdown-LaTex/AMS二元运算符-2021-11-18-12-32-49-6e3b459593953db5eb8c236fc88e8fca-c1f1c4.png)