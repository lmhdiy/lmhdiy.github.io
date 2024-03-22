+++
author = "Lee"
title = "凸优化笔记 01"
date = "2024-03-22"
description = "CMU 10-725 Convex Optimization"
tags = [
    "笔记",
    "CMU 10-725",
    "凸优化"
]
categories = [
    "themes",
    "syntax",
]
series = ["CMU_10-725"]
aliases = ["CMU-10-725-01"]
defaultContentLanguage = "zh"
+++

CMU 10-725 Lecture 01
<!--more-->
# Lecture 1： Introduction

## 这门课程可以让你学会：

1. 针对不同的问题，用不同的算法
2. 加深对统计过程的理解
3. 构造新的P（容易优化的问题），解决不容易被优化的问题
    
## 案例1：图像去噪 
2D fussed lasso problem & ROF模型 

三种解决方案 & 去噪效果
- ADMM：20 iters （学期末会讲）
- 近端梯度下降：1K iters
- 坐标下降法
    
    Q：上述三种方法用于优化同一个凸函数，但是他们的结果不同，那么凸优化问题应该有一个唯一最优解吗？

    A：凸优化未必有唯一最优解。但是不同的解必须 `achieve the same criteria value`，最后会讨论。

总结：
    即使对于同一个优化问题，不同的方法也会导致截然不同的效果。在本案例中ADMM方法更好，但是对另一个问题，我们仍然需要具体地分析哪一种优化方法更适合。

**<center> to be continue ... </center>**