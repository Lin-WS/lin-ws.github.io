---
title: test
toc: true
sticky: true
date: 2024-12-26 17:10:07
tags:
    - Hexo
    - markdown
categories:
    - test
article:
    highlight:
        fold: unfolded
---

测试hexo markdown与MathJax渲染的效果
<!--more-->
<span id="jump" style="color: red;"> 跳转到此</span>

# 标题
# 一级标题
## 二级标题
### 三级标题

```text
# 一级标题
## 二级标题
### 三级标题
```

# 字体
*斜体* 或 _斜体_

**加粗**

~~删除线~~

```text
*斜体* 或 _斜体_
**加粗**
~~删除线~~
```

# 图片
<center>
    <img src="./test.jpg" alt="test" style="zoom:80%;"/>
</center>

```text 
<center>
    <img src="./test.jpg" alt="test" style="zoom:80%;"/>
</center>
```

# 代码
{% codeblock test lang:c %}
#include <stdio.h>
int main() {
    for(int i = 0; i < 10; ++i) {
        printf("Hello World!");
    }
    return 0;
}
{% endcodeblock %}

```text
{% codeblock test lang:c %}
#include <stdio.h>
int main() {
    for(int i = 0; i < 10; ++i) {
        printf("Hello World!");
    }
    return 0;
}
{% endcodeblock %}
```

# 引用
> 一级引用
>> 二级引用
>>> 三级引用

```text
> 一级引用
>> 二级引用
>>> 三级引用
```

# 跳转
[点击跳转](#jump)

```text
[点击跳转](#jump)

<span id="jump" style="color: red;"> 跳转到此</span>
```

# 超链接
[www.baidu.com](https://www.baidu.com)

```text
[www.baidu.com](https://www.baidu.com)
```

# 表格
| 姓名 | 技能 | 排行 |
| :--: | :--: | :--: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |

```text
| 姓名 | 技能 | 排行 |
| :--: | :--: | :--: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |
```

# 序列
1. test one
2. test two
3. test three

* test 1
* test 2
* test 3

```text
1. test one
2. test two
3. test three

* test 1
* test 2
* test 3
```

# 强调
这是`强调`的内容

```text
这是`强调`的内容
```

# 公式
网站使用Hexo框架搭建，在解析公式时，使用与markdown语法略有不同。

行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $

```text
用法为：文字文字$公式$文字文字
行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $
```

行间公式：
<div>
$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$
</div>

```text
用法为：
文字文字
<div>
$$公式$$
</div>
文字文字

行间公式：
<div>
$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$
</div>
```

# 希腊字母

|    名称    |    大写    |         转义         |     小写      |         转义         |
| :--------: | :--------: | :------------------: | :-----------: | :------------------: |
|   alpha    |    $A$     |       \\$A\\$        |   $\alpha$    |    \\$\alpha\\$      |
|    beta    |    $B$     |       \\$B\\$        |    $\beta$    |    \\$\beta\\$       |
|   gamma    |  $\Gamma$  |     \\$\Gamma\\$     |   $\gamma$    |    \\$\gamma\\$      |
|   delta    |  $\Delta$  |     \\$\Delta\\$     |   $\delta$    |    \\$\delta\\$      |
|  epsilon   |    $E$     |       \\$E\\$        |  $\epsilon$   |    \\$\epsilon\\$    |
| varepsilon |    $E$     |       \\$E\\$        | $\varepsilon$ |  \\$\varepsilon\\$   |
|    zeta    |    $Z$     |       \\$Z\\$        |    $\zeta$    |    \\$\zeta\\$       |
|    eta     |    $H$     |       \\$H\\$        |    $\eta$     |    \\$\eta\\$        |
|   theta    |  $\Theta$  |     \\$\Theta\\$     |   $\theta$    |    \\$\theta\\$      |
|    iota    |    $I$     |       \\$I\\$        |    $\iota$    |    \\$\iota\\$       |
|   kappa    |    $K$     |       \\$K\\$        |   $\kappa$    |    \\$\kappa\\$      |
|   lambda   | $\Lambda$  |    \\$\Lambda\\$     |   $\lambda$   |    \\$\lambda\\$     |
|     mu     |    $M$     |       \\$M\\$        |     $\mu$     |    \\$\mu\\$         |
|     nu     |    $N$     |       \\$N\\$        |     $\nu$     |    \\$\nu\\$         |
|     xi     |   $\Xi$    |      \\$\Xi\\$       |     $\xi$     |    \\$\xi\\$         |
|  omicron   |    $O$     |       \\$O\\$        |  $\omicron$   |    \\$\omicron\\$    |
|     pi     |   $\Pi$    |      \\$\Pi\\$       |     $\pi$     |    \\$\pi\\$         |
|    rho     |    $P$     |       \\$P\\$        |    $\rho$     |    \\$\rho\\$        |
|   sigma    |  $\Sigma$  |     \\$\Sigma\\$     |   $\sigma$    |    \\$\sigma\\$      |
|    tau     |    $T$     |       \\$T\\$        |    $\tau$     |    \\$\tau\\$        |
|  upsilon   | $\Upsilon$ |   \\$\Upsilon\\$     |  $\upsilon$   |    \\$\upsilon\\$    |
|    phi     |   $\Phi$   |      \\$\Phi\\$      |    $\phi$     |    \\$\phi\\$        |
|   varphi   |   $\Phi$   |      \\$\Phi\\$      |   $\varphi$   |    \\$\varphi\\$     |
|    chi     |    $X$     |       \\$X\\$        |    $\chi$     |    \\$\chi\\$        |
|    psi     |   $\Psi$   |      \\$\Psi\\$      |    $\psi$     |    \\$\psi\\$        |
|   omega    |  $\Omega$  |     \\$\Omega\\$     |   $\omega$    |    \\$\omega\\$      |

# 上下标
上标使用 `^` 符号，后接 `{}` ，下标使用 `_` 符号，将需要作为上标或下标的符号写在各自的花括号中

上下标表示：$x^{2}_{ij}$

```text
上下标表示：$x^{2}_{ij}$
```

# 括号
小括号：()

中括号：[]

花括号：{}

公式的括号：$\left(\frac{x}{y}\right)$，$\left[\frac{x}{y}\right]$，$\left\\{\frac{x}{y}\right\\}$
花括号由于有分组的作用，因此用在公式时使用 `\\{\\}` 转义符号来表示

尖括号：<> 或 $\langle$ $\rangle$

上取整：$\lceil$ $\rceil$

下取整：$\lfloor$ $\rfloor$

```text
小括号：()

中括号：[]

花括号：{}

公式的括号：$\left(\frac{x}{y}\right)$，$\left[\frac{x}{y}\right]$，$\left\\{\frac{x}{y}\right\\}$

尖括号：<> 或 $\langle$ $\rangle$

上取整：$\lceil$ $\rceil$

下取整：$\lfloor$ $\rfloor$
```

# 求和
求和：$\sum\_{r=1}^{\infty}n$ 或 $\sum\limits\_{n=1}^{\infty}n$
由于使用了多个 `_` ，被markdown认为是斜体符号，因此使用转义符号 `\_`

```text
求和：$\sum\_{r=1}^{\infty}n$ 或 $\sum\limits\_{n=1}^{\infty}n$
```

# 积分
积分：$\int_{r=1}^\infty$

多重积分：$\iiint_{r=1}^\infty$

```text
积分：$\int_{r=1}^\infty$
多重积分：$\iiint_{r=1}^\infty$
多重积分只需增加 i 的数量
```

# 连乘
连乘：$\prod\_{i=1}^{k} (a\_i+b\_i)$ 或 $\prod\limits\_{i=1}^{k} (a\_i+b\_i)$

```text
连乘：$\prod\_{i=1}^{k} (a\_i+b\_i)$ 或 $\prod\limits\_{i=1}^{k} (a\_i+b\_i)$
```

# 分式
分式：$\frac {a+b}{c+d}$

```text
分式：$\frac {a+b}{c+d}$
```

# 根式