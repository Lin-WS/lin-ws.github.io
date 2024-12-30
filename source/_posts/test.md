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
---

测试hexo markdown与MathJax渲染的效果
<!--more-->
<span id="jump" style="color: red;"> 跳转到此</span>

# 标题
# 一级标题
## 二级标题
### 三级标题

``` text 点击展开代码 >folded
# 一级标题
## 二级标题
### 三级标题
```

# 字体
*斜体* 或 _斜体_

**加粗**

~~删除线~~

``` text 点击展开代码 >folded
*斜体* 或 _斜体_
**加粗**
~~删除线~~
```

# 图片
<center>
    <img src="./test.jpg" alt="test" style="zoom:80%;"/>
</center>

``` text 点击展开代码 >folded
<center>
    <img src="./test.jpg" alt="test" style="zoom:80%;"/>
</center>
```

# 代码
{% codeblock 点击展开代码 lang:c %}
#include <stdio.h>
int main() {
    for(int i = 0; i < 10; ++i) {
        printf("Hello World!");
    }
    return 0;
}
{% endcodeblock %}

``` text 点击展开代码 >folded
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

``` text 点击展开代码 >folded
> 一级引用
>> 二级引用
>>> 三级引用
```

# 跳转
[点击跳转](#jump)

``` text 点击展开代码 >folded
[点击跳转](#jump)

<span id="jump" style="color: red;"> 跳转到此</span>
```

# 超链接
[www.baidu.com](https://www.baidu.com)

``` text 点击展开代码 >folded
[www.baidu.com](https://www.baidu.com)
```

# 序列
1. test one
2. test two
3. test three

* test 1
* test 2
* test 3

``` text 点击展开代码 >folded
1. test one
2. test two
3. test three

* test 1
* test 2
* test 3
```

# 强调
这是`强调`的内容

``` text 点击展开代码 >folded
这是`强调`的内容
```

# 公式
网站使用Hexo框架搭建，在解析公式时，使用与markdown语法略有不同。

行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $

``` text 点击展开代码 >folded
用法为：文字文字$公式$文字文字
行内公式：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,. $
```

行间公式：
<div>
$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$
</div>

``` text 点击展开代码 >folded
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

|    名称    |    大写    |         code         |     小写      |         code         |
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

# 特殊符号

|      code      |         符号         |        code        |           符号           |
| :------------: | :------------------: | :----------------: | :----------------------:|
|     $sinx$     |      \\$sinx\\$      |     $arctanx$      |       \\$arctanx\\$     |
|     $\lt$      |      \\$\lt$\\$      |       $\gt$        |         \\$\gt$\\$      |
|     $\le$      |      \\$\le$\\$      |       $\ge$        |         \\$\ge$\\$      |
|     $\ll$      |      \\$\ll$\\$      |       $\gg$        |         \\$\gg$\\$      |
|     $\ne$      |      \\$\ne$\\$      |       $\not$       |         \\$\not$\\$     |
|  $\varnothing$ |  \\$\varnothing$\\$  |       $\in$        |         \\$\in$\\$      |
|     $\cup$     |      \\$\cup$\\$     |       $\cap$       |         \\$\cap$\\$     |
|    $\subset$   |    \\$\subset$\\$    |    $\subseteq$     |      \\$\subseteq$\\$   |
|    $\supset$   |    \\$\supset$\\$    |  $\binom{n+1}{2k}$ |  \\$\binom{n+1}{2k}$\\$ |
|  $\rightarrow$ |  \\$\rightarrow$\\$  |     $\leftarrow$   |      \\$\leftarrow$\\$  |
|  $\Rightarrow$ |  \\$\Rightarrow$\\$  |     $\Leftarrow$   |      \\$\Leftarrow$\\$  |
|    $\mapsto$   |    \\$\mapsto$\\$    |       $\land$      |        \\$\land$\\$     |
|     $\lor$     |      \\$\lor$\\$     |       $\lnot$      |        \\$\lnot$\\$     |
|    $\forall$   |    \\$\forall$\\$    |     $\exists$      |       \\$\exists$\\$    |
|     $\top$     |      \\$\top$\\$     |       $\bot$       |         \\$\bot$\\$     |
|    $\vdash$    |     \\$\vdash$\\$    |      $\vDash$      |        \\$\vDash$\\$    |
|     $\star$    |     \\$\star$\\$     |       $\ast$       |         \\$\ast$\\$     |
|     $\oplus$   |     \\$\oplus$\\$    |       $\circ$      |        \\$\circ$\\$     |
|    $\bullet$   |    \\$\bullet$\\$    |      $\approx$     |       \\$\approx$\\$    |
|     $\sim$     |      \\$\sim$\\$     |       $\cong$      |        \\$\cong$\\$     |
|    $\equiv$    |     \\$\equiv$\\$    |       $\prec$      |        \\$\prec$\\$     |
|    $\infty$    |     \\$\infty$\\$    |       $\nabla$     |        \\$\nabla$\\$    |
|   $\partial$   |    \\$\partial$\\$   |        $\Im$       |         \\$\Im$\\$      |
|   $a \mod b$   |    \\$a \mod b$\\$   |      $\ldots$      |        \\$\ldots$\\$    |
|     $\cdots$   |     \\$\cdots$\\$    |       $\cdot$      |        \\$\cdot$\\$     |
|     $\hat x$   |     \\$\hat x$\\$    |   $\widehat {xy}$  |   \\$\widehat {xy}$\\$  |
|     $\bar x$   |     \\$\bar x$\\$    |       $\vec A$     |        \\$\vec A$\\$    |
| $\overline {AB}$| \\$\overline {AB}$\\$| $\overrightarrow {AB}$| \overrightarrow AB  |
|     $\dot x$   |     \\$\dot x$\\$    |   $\dot {\dot x}$  |   \\$\dot {\dot x}$\\$  |
|    $\ddot x$   |    \\$\ddot x$\\$    |                    |                         |

# 上下标

上下标：$x^{2}_{ij}$

``` text 点击展开代码 >folded
上下标：$x^{2}_{ij}$
```

上标使用 `^` 符号，后接 `{}` ，下标使用 `_` 符号，将需要作为上标或下标的符号写在各自的花括号中

# 括号
小括号：()

中括号：[]

花括号：{}

公式的括号：$\left(\frac{x}{y}\right)$，$\left[\frac{x}{y}\right]$，$\left\\{\frac{x}{y}\right\\}$
花括号由于有分组的作用，因此用在公式时使用 `\\{\\}` 转义符号来表示

尖括号：<> 或 $\langle$ $\rangle$

上取整：$\lceil$ $\rceil$

下取整：$\lfloor$ $\rfloor$

``` text 点击展开代码 >folded
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

``` text 点击展开代码 >folded
求和：$\sum\_{r=1}^{\infty}n$ 或 $\sum\limits\_{n=1}^{\infty}n$
```

由于使用了多个 `_` ，被markdown认为是斜体符号，因此使用转义符号 `\_`

# 积分
积分：$\int_{r=1}^\infty$

多重积分：$\iiint_{r=1}^\infty$

``` text 点击展开代码 >folded
积分：$\int_{r=1}^\infty$
多重积分：$\iiint_{r=1}^\infty$
```

多重积分只需增加 `i` 的数量

# 连乘
连乘：$\prod\_{i=1}^{k} (a\_i+b\_i)$ 或 $\prod\limits\_{i=1}^{k} (a\_i+b\_i)$

``` text 点击展开代码 >folded
连乘：$\prod\_{i=1}^{k} (a\_i+b\_i)$ 或 $\prod\limits\_{i=1}^{k} (a\_i+b\_i)$
```

# 分式
分式：$\frac {a+b}{c+d}$ 或 $\cfrac {a+b}{c+d}$

``` text 点击展开代码 >folded
分式：$\frac {a+b}{c+d}$ 或 $\cfrac {a+b}{c+d}$
```

# 根式
根式：$\sqrt[3]{x}$

``` text 点击展开代码 >folded
根式：$\sqrt[3]{x}$

```

# 多行表达式
## 分段函数
<div>
$$
f(n)=
\begin{cases}
\cfrac {n}{2}, & \text{n是偶数}\\[2ex]
3n + 1, & \text{n是奇数}
\end{cases}
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
f(n)=
\begin{cases}
\cfrac {n}{2}, & \text{n是偶数}\\[2ex]
3n + 1, & \text{n是奇数}
\end{cases}
$$
</div>
```

其中，`\` 表示分类换行，`&` 表示对齐，`\text{}` 表示文本，`\[2ex]` 表示两行的间隔，`\[1ex]` 是初始距离

## 多行式子
<div>
$$
\begin{equation}\begin{split} 
a&=b+c-d \\ 
&\quad +e-f\\ 
&=g+h\\ 
& =i 
\end{split}\end{equation}
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\begin{equation}\begin{split} 
a&=b+c-d \\ 
&\quad +e-f\\ 
&=g+h\\ 
& =i 
\end{split}\end{equation}
$$
</div>
```

其中 `\begin{equation}` 表示开始式子，`\end{equation}` 表示式子结束；`\begin{split}` 表示开始多行公式，`\end{split}` 表示结束；公式中用`\` 表示换行，`&` 表示对齐的位置，`\quad` 表示占位

## 方程组
<div>
$$
\left \{ 
\begin{array}{c}
a_1x+b_1y+c_1z=d_1 \\ 
a_2x+b_2y+c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{array}
\right.
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\left \{ 
\begin{array}{c}
a_1x+b_1y+c_1z=d_1 \\ 
a_2x+b_2y+c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{array}
\right.
$$
</div>
```

使用 `\begin{array}{c}...\end{array}` 与 `\left \{` 与 `\right.` 配合表示方程组，也可以使用上述分段函数的表示方法

# 表格
| 姓名 | 技能 | 排行 |
| :--: | :--: | :--: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |

``` text 点击展开代码 >folded
| 姓名 | 技能 | 排行 |
| :--: | :--: | :--: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |
```
或
<div>
$$
\begin{array}{c|ccc}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i \\
\end{array}
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\begin{array}{c|ccc}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i \\
\end{array}
$$
</div>
```

使用 `\begin{array}{列样式}…\end{array}` 这样的形式来创建任意形式的表格，列样式中定义表格总体形状，可以是 `lcr`，分别表示左，中，右对齐，使用 `|` 表示一条竖线。表格中各行使用 `\\` 分隔，各列使用 `&` 分隔。使用 `\hline` 加入一行直线。

# 矩阵
<div>
$$
\left (
\begin{matrix}
1 & x & x^2 \\
1 & y & y^2 \\
1 & z & z^2 \\
\end{matrix}
\right )
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\left (
\begin{matrix}
1 & x & x^2 \\
1 & y & y^2 \\
1 & z & z^2 \\
\end{matrix}
\right )
$$
</div>
```

使用 `\begin{matrix}…\end{matrix}` 这样的形式来表示矩阵，在 `\begin` 与 `\end` 之间加入矩阵中的元素即可。矩阵的行之间使用 `\\` 分隔，列之间使用 `&` 分隔，使用 `\left` 与 `\right` 配合表示各种括号符号。

使用 `\cdots`，`\ddots`，`\vdots` 来省略矩阵中的元素，如：
<div>
$$
\left (
\begin{matrix}
1&a_1&a_1^2&\cdots&a_1^n\\
1&a_2&a_2^2&\cdots&a_2^n\\
\vdots&\vdots&\vdots&\ddots&\vdots\\
1&a_m&a_m^2&\cdots&a_m^n\\
\end{matrix}
\right )
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\left (
\begin{matrix}
1&a_1&a_1^2&\cdots&a_1^n\\
1&a_2&a_2^2&\cdots&a_2^n\\
\vdots&\vdots&\vdots&\ddots&\vdots\\
1&a_m&a_m^2&\cdots&a_m^n\\
\end{matrix}
\right )
$$
</div>
```

# 标记
标记：
<div>
$$
x^2 + 2x + 1 = 0\tag{1}\label{1}
$$
</div>

``` text 点击展开代码 >folded
标记：
<div>
$$
x^2 + 2x + 1 = 0\tag{1}\label{1}
$$
</div>
```

使用 `\tag{}` 来标记公式，使用 `\label{}` 作为引用公式的标签
<div>
$$
\left (x + y \right )^2 \stackrel{\eqref{1}}= 1 
$$
</div>

``` text 点击展开代码 >folded
<div>
$$
\left (x + y \right )^2 \stackrel{\eqref{1}}= 1 
$$
</div>
```

使用 `\stackrel{\eqref{labelnumber}}` 来引用某一公式

# 标签页

<div class="tabs is-toggle"><ul>
<li class="is-active"><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-image" aria-hidden="true"></i></span>
<span>Pictures</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-music" aria-hidden="true"></i></span>
<span>Music</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-film" aria-hidden="true"></i></span>
<span>Videos</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="far fa-file-alt" aria-hidden="true"></i></span>
<span>Documents</span>
</a></li>
</ul></div>

<div id="Pictures" class="tab-content" style="display: block;">
  <a href="https://pixabay.com/zh/">Pixabay</a>是全球知名的图库网站及充满活力的创意社区,拥有上百万张免费正版高清照片素材,涵盖风景、人物、动态、静物等多种分类,你可以在任何地方使用 Pixabay 图库中的素材...
</div>
<div id="Music" class="tab-content">
  <a href="https://music.163.com/">网易云音乐</a >是一款专注于发现与分享的音乐产品,依托专业音乐人、DJ、好友推荐及社交功能,为用户打造全新的音乐生活。
</div>
<div id="Videos" class="tab-content">
  <a href="https://www.bilibili.com/">哔哩哔哩</a >是国内知名的视频弹幕网站,这里有最及时的动漫新番,最棒的ACG氛围,最有创意的Up主。大家可以在这里找到许多欢乐。
</div>
<div id="Documents" class="tab-content">
  <a href="https://shimo.im/">石墨文档</a >是全新一代云 Office 办公软件,支持多人在线协作编辑文档和表格,独有内容级安全,全过程留痕可追溯。PC 端和移动端全覆盖,随时随地远程办公。即写即存...
</div>

<style type="text/css">
  .tabs ul {
    margin: 0;
  }

  .tab-content {
    display: none;
    padding: 10px; /* 内边距 */
    margin: 0; /* 外边距 */
    width: 100%;
    text-align: left; /* 左对齐 */
    box-sizing: border-box;
    clear: both; /* 确保内容不会与浮动元素重叠 */
  }

  /* 激活选项卡时显示相应内容 */
  .tab-content.is-active {
    display: block;
  }
</style>

<script>
function onTabClick (event) {
    var tabTitle = $(event.currentTarget).children('span:last-child').text(); // 获取标签名称
    // 隐藏所有tab内容
    $('.tab-content').removeClass('is-active').css('display', 'none'); 
    // 激活对应的tab内容
    $('#' + tabTitle).addClass('is-active').css('display', 'block');
    
    // 删除其他标签的is-active类，并将当前标签设置为激活状态
    $('.tabs li').removeClass('is-active');
    $(event.currentTarget).parent().addClass('is-active');
}
</script>

``` text 点击展开代码 >folded
<div class="tabs is-toggle"><ul>
<li class="is-active"><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-image" aria-hidden="true"></i></span>
<span>Pictures</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-music" aria-hidden="true"></i></span>
<span>Music</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="fas fa-film" aria-hidden="true"></i></span>
<span>Videos</span>
</a></li>
<li><a onclick="onTabClick(event)">
<span class="icon is-small"><i class="far fa-file-alt" aria-hidden="true"></i></span>
<span>Documents</span>
</a></li>
</ul></div>

<div id="Pictures" class="tab-content" style="display: block;">
  <a href="https://pixabay.com/zh/">Pixabay</a>是全球知名的图库网站及充满活力的创意社区,拥有上百万张免费正版高清照片素材,涵盖风景、人物、动态、静物等多种分类,你可以在任何地方使用 Pixabay 图库中的素材...
</div>
<div id="Music" class="tab-content">
  <a href="https://music.163.com/">网易云音乐</a >是一款专注于发现与分享的音乐产品,依托专业音乐人、DJ、好友推荐及社交功能,为用户打造全新的音乐生活。
</div>
<div id="Videos" class="tab-content">
  <a href="https://www.bilibili.com/">哔哩哔哩</a >是国内知名的视频弹幕网站,这里有最及时的动漫新番,最棒的ACG氛围,最有创意的Up主。大家可以在这里找到许多欢乐。
</div>
<div id="Documents" class="tab-content">
  <a href="https://shimo.im/">石墨文档</a >是全新一代云 Office 办公软件,支持多人在线协作编辑文档和表格,独有内容级安全,全过程留痕可追溯。PC 端和移动端全覆盖,随时随地远程办公。即写即存...
</div>

<style type="text/css">
  .tabs ul {
    margin: 0;
  }

  .tab-content {
    display: none;
    padding: 10px; /* 内边距 */
    margin: 0; /* 外边距 */
    width: 100%;
    text-align: left; /* 左对齐 */
    box-sizing: border-box;
    clear: both; /* 确保内容不会与浮动元素重叠 */
  }

  /* 激活选项卡时显示相应内容 */
  .tab-content.is-active {
    display: block;
  }
</style>

<script>
function onTabClick (event) {
    var tabTitle = $(event.currentTarget).children('span:last-child').text(); // 获取标签名称
    // 隐藏所有tab内容
    $('.tab-content').removeClass('is-active').css('display', 'none'); 
    // 激活对应的tab内容
    $('#' + tabTitle).addClass('is-active').css('display', 'block');
    
    // 删除其他标签的is-active类，并将当前标签设置为激活状态
    $('.tabs li').removeClass('is-active');
    $(event.currentTarget).parent().addClass('is-active');
}
</script>
```