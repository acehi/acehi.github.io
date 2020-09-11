---
date: 2020-07-29 01:56:56
layout: post
title: "leetcodeLCP:13-寻宝"
subtitle:
description: "wechat: Acehii"
image: /assets/img/convers/LCP:13-寻宝.jpeg
optimized_image: /assets/img/convers/LCP:13-寻宝.jpeg
category: algorithm
tags:
 - algorithm
 - leetCode
 - LCP
author: Acehi
paginate: false
insidecover: true
---

<style>
.p-style {
    margin: 3px 0 0 0 !important;
    font-size:16px !important;
    line-height:23px !important;
}
.div-style {
    font-size:16px !important;
    line-height:23px !important;
}

.attention-style {
    font-size:16px !important;
    margin: 3px 0 0 0 !important;
    line-height:23px !important;
    color: #ff0a16 !important;
}
.a-style {
    color: darkgrey !important;
    margin: 2px 0 0 0 !important;
    font-size:15px !important;
    line-height:1px !important;
    text-decoration:none !important;
}
</style>

### 题目：
<div class="div-style">
    <p class="p-style">我们得到了一副藏宝图，藏宝图显示，在一个迷宫中存在着未被世人发现的宝藏。迷宫是一个二维矩阵，用一个字符串数组表示。它标识了唯一的入口（用 'S' 表示），和唯一的宝藏地点（用 'T' 表示）。但是，宝藏被一些隐蔽的机关保护了起来。在地图上有若干个机关点（用 'M' 表示），只有所有机关均被触发，才可以拿到宝藏。要保持机关的触发，需要把一个重石放在上面。迷宫中有若干个石堆（用 'O' 表示），每个石堆都有无限个足够触发机关的重石。但是由于石头太重，我们一次只能搬一个石头到指定地点。迷宫中同样有一些墙壁（用 '#' 表示），我们不能走入墙壁。剩余的都是可随意通行的点（用 '.' 表示）。石堆、机关、起点和终点（无论是否能拿到宝藏）也是可以通行的。我们每步可以选择向上/向下/向左/向右移动一格，并且不能移出迷宫。搬起石头和放下石头不算步数。那么，从起点开始，我们最少需要多少步才能最后拿到宝藏呢？如果无法拿到宝藏，返回 -1 。</p>
    <p class="p-style">示例：</p>
</div>

````
示例 1：

输入： ["S#O", "M..", "M.T"]

输出：16

解释：最优路线为： S->O, cost = 4, 去搬石头 O->第二行的M, cost = 3, M机关触发 第二行的M->O, cost = 3, 我们需要继续回去 O 搬石头。 O->第三行的M, cost = 4, 此时所有机关均触发 第三行的M->T, cost = 2，去T点拿宝藏。 总步数为16。 

示例 2：

输入： ["S#O", "M.#", "M.T"]

输出：-1

解释：我们无法搬到石头触发机关

示例 3：

输入： ["S#O", "M.T", "M.."]

输出：17

解释：注意终点也是可以通行的。

限制：

1 <= maze.length <= 100
1 <= maze[i].length <= 100
maze[i].length == maze[j].length
S 和 T 有且只有一个
0 <= M的数量 <= 16
0 <= O的数量 <= 40，题目保证当迷宫中存在 M 时，一定存在至少一个 O 。
````

<p class="p-style"><a href="https://leetcode-cn.com/problems/xun-bao/" class="a-style">来源：LeetCode</a></p>

---

原谅我暂时还没想到好的方法，，，

### 解法：

#### 一、Brute Force

<p class="p-style">思路：</p>
<p class="p-style"></p>

```go

```

