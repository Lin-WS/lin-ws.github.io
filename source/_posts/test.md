---
title: test
toc: true
sticky: true
date: 2024-12-26 17:10:07
tags:
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

```
# 一级标题
## 二级标题
### 三级标题
```

# 字体
*斜体* 或 _斜体_

**加粗**

~~删除线~~

```
*斜体* 或 _斜体_
**加粗**
~~删除线~~
```

# 图片
<center>
    <img src="./test.jpg" alt="test" style="zoom:80%;"/>
</center>

```markdown 
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

```
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

```
> 一级引用
>> 二级引用
>>> 三级引用
```

# 跳转
[点击跳转](#jump)

```
[点击跳转](#jump)

<span id="jump" style="color: red;"> 跳转到此</span>
```

# 超链接
[www.baidu.com](https://www.baidu.com)

```
[www.baidu.com](https://www.baidu.com)
```

# 表格
| 姓名 | 技能 | 排行 |
| :--: | :--: | :--: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |

```
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

```
1. test one
2. test two
3. test three

* test 1
* test 2
* test 3
```

# 强调
这是`强调`的内容

```
这是`强调`的内容
```

# 公式
网站使用Hexo框架搭建，在解析公式时，使用与markdown语法略有不同。

行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $

```
用法为：文字文字$公式$文字文字
行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $
```

行间公式：
<div>
$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$
</div>

```
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

## 希腊字母

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

## 上下标
上下标表示：$x^{2}_{ij}$

```
上下标表示：$x^{2}_{ij}$
```

