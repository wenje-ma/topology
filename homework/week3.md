# week3

> **命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)**
> 
> $\mathbb{R}$ 的子集连通当且仅当它是区间; 紧当且仅当它闭且有界. (讲义第 1 讲, p6)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **命题 1.14 (连续函数构成代数)**
> 
> $X$ 上连续实值函数之集对加法与乘法封闭, 且含常值 $1$. (讲义第 1 讲, p22)

> **定理 2.2 (连续像连通)**
> 
> 若 $f:X\to{}Y$ 连续且 $X$ 连通, 则 $f\left(X\right)$ 连通. (讲义第 2 讲, p14)

> **定义 2.3 (凸集)**
> 
> 称 $K\subset\mathbb{R}^n$ 凸, 若 $K$ 中任意两点之间的连线段含于 $K$; 凸集对凸组合封闭, 即 $\sum_i\lambda_ix_i\in{}K$ 只要 $x_i\in{}K$, $\lambda_i\ge0$, $\sum_i\lambda_i=1$. (讲义第 2 讲, p16)

> **命题 2.4 (凸集路径连通)**
> 
> $\mathbb{R}^n$ 中的凸集路径连通. (讲义第 2 讲, p16)

> **定理 2.5 (路径连通蕴含连通)**
> 
> 路径连通空间连通. (讲义第 2 讲, p16)

> **定理 3.7 (紧集上的极值)**
> 
> 紧集上的连续实值函数取到最大值与最小值. (讲义第 3 讲, p11)

> **定理 4.3 (度量空间中紧与序列紧)**
> 
> 度量空间紧当且仅当每个序列都有收敛子列. (讲义第 4 讲, p4)

## 3.1 (周期连续函数的中点等值问题)

设 $f:\left[0,1\right]\to\mathbb{R}$ 是一个连续函数并且 $f\left(0\right)=f\left(1\right)$.

(1) 证明存在 $x\in\left[0,\frac{1}{2}\right]$ 使得 $f\left(x\right)=f\left(x+\frac{1}{2}\right)$;

(2) 证明对于任意的整数 $n\ge2$, 存在 $x\in\left[0,1-\frac{1}{n}\right]$ 使得 $f\left(x\right)=f\left(x+\frac{1}{n}\right)$;

(3) 证明存在一个连续函数 $f:\left[0,1\right]\to\mathbb{R}$ 使得对于任意的 $x\in\left[0,\frac{3}{5}\right]$ 都有 $f\left(x\right)\neq{}f\left(x+\frac{2}{5}\right)$.

2024 年卷 B 题一.

### 解答 3.1

(1) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac{1}{2}\right)$, 定义在 $\left[0,\frac{1}{2}\right]$ 上. 由**命题 1.14 (连续函数构成代数)** $g$ 连续, 且

$$
g\left(0\right)+g\left(\frac{1}{2}\right)=f\left(0\right)-f\left(1\right)=0.
$$

若 $g\left(0\right)=0$, 则 $x=0$ 即为所求; 否则 $g\left(0\right)$ 与 $g\left(\frac{1}{2}\right)$ 异号. 区间 $\left[0,\frac{1}{2}\right]$ 是凸集, 由**命题 2.4 (凸集路径连通)** 与**定理 2.5 (路径连通蕴含连通)** 它连通, 故由**定理 2.2 (连续像连通)**, $g$ 的像连通, 由**命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)** 是含 $g\left(0\right)$ 与 $g\left(\frac{1}{2}\right)$ 的区间, 从而含 $0$. 故存在 $x$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac{1}{2}\right)$.

$\blacksquare$

(2) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac{1}{n}\right)$, 定义在 $\left[0,1-\frac{1}{n}\right]$ 上. 累加得

$$
\sum_{j=0}^{n-1}g\left(\frac{j}{n}\right)=\sum_{j=0}^{n-1}\left(f\left(\frac{j}{n}\right)-f\left(\frac{j+1}{n}\right)\right)=f\left(0\right)-f\left(1\right)=0.
$$

若 $g$ 无零点, 由同第 (1) 小题的理由, $g$ 的像是不含 $0$ 的连通集, 由**命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)** 是不含 $0$ 的区间, 故 $g$ 恒正或恒负, 于是各 $g\left(\frac{j}{n}\right)$ 同号且非零, 其和不为 $0$, 矛盾. 故存在 $x$ 使 $g\left(x\right)=0$.

$\blacksquare$

(3) 取 $f$ 为以 $0,\frac{1}{5},\frac{2}{5},\frac{3}{5},\frac{4}{5},1$ 为节点的分段线性函数, 节点处的取值依次为

$$
0,\quad{}2,\quad{}-1,\quad{}1,\quad{}-3,\quad{}0.
$$

它连续且 $f\left(0\right)=f\left(1\right)=0$. 在 $\left[0,\frac{3}{5}\right]$ 上 $x+\frac{2}{5}$ 落在 $\left[\frac{2}{5},1\right]$, 分段计算差:

当 $x\in\left[0,\frac{1}{5}\right]$, 两段斜率为 $10$ 与 $10$, 故 $f\left(x\right)-f\left(x+\frac{2}{5}\right)=0-\left(-1\right)=1$;

当 $x\in\left[\frac{1}{5},\frac{2}{5}\right]$, 两段斜率为 $-15$ 与 $-20$, 故

$$
f\left(x\right)-f\left(x+\frac{2}{5}\right)=1+5\left(x-\frac{1}{5}\right)\ge1;
$$

当 $x\in\left[\frac{2}{5},\frac{3}{5}\right]$, 两段斜率为 $10$ 与 $15$, 故

$$
f\left(x\right)-f\left(x+\frac{2}{5}\right)=2-5\left(x-\frac{2}{5}\right)\ge1.
$$

三段上差恒正, 故 $f\left(x\right)\neq{}f\left(x+\frac{2}{5}\right)$ 对一切 $x\in\left[0,\frac{3}{5}\right]$ 成立.

$\blacksquare$


## 3.2 (紧凸集上非扩张映射的不动点)

考虑一个赋范线性空间 $E$ 及其中的一个紧致的子集 $K\subset{}E$. 假设 $K$ 还是凸的. 假设 $f:K\to{}K$ 是一个连续映射并且对于任意 $x,y\in{}K$,

$$
\left|f\left(x\right)-f\left(y\right)\right|\le\left|x-y\right|.
$$

(1) 证明如果条件改为对任意 $x,y\in{}K$ 有 $\left|f\left(x\right)-f\left(y\right)\right|<\left|x-y\right|$, 那么 $f$ 一定至少有一个不动点;

(2) 取定 $a\in{}K$. 证明对任意 $n\ge1$, 函数 $f_n\left(x\right)=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x\right)$ 是从 $K$ 到 $K$ 的映射, 且对任意 $n\ge1$, $f_n$ 至少有一个不动点 $x_n\in{}K$;

(3) 运用数列 $\left\{x_n\right\}$ 及 $K$ 的紧性证明满足最初题设条件的 $f$ 也有一个不动点.

2024 年卷 A 题三.

### 解答 3.2

(1) 令 $g\left(x\right)=\left|f\left(x\right)-x\right|$. 范数连续, $f$ 连续, 故 $g$ 连续 (**命题 1.14 (连续函数构成代数)** 与**定义 1.8 (连续映射)**). 由**定理 3.7 (紧集上的极值)** 用于 $-g$, $g$ 在紧集 $K$ 上取到最小值 $m$ 于某 $x_0\in{}K$. 若 $m>0$, 则

$$
g\left(f\left(x_0\right)\right)=\left|f\left(f\left(x_0\right)\right)-f\left(x_0\right)\right|<\left|f\left(x_0\right)-x_0\right|=m,
$$

与 $m$ 的最小性矛盾. 故 $m=0$, 即 $f\left(x_0\right)=x_0$.

$\blacksquare$

(2) 由**定义 2.3 (凸集)**, $K$ 凸, 而 $f_n\left(x\right)$ 是 $a$ 与 $f\left(x\right)$ 的凸组合 (系数 $\frac{1}{n}$ 与 $1-\frac{1}{n}$ 非负且和为 $1$), 故 $f_n\left(x\right)\in{}K$. 又

$$
\left|f_n\left(x\right)-f_n\left(y\right)\right|=\left(1-\frac{1}{n}\right)\left|f\left(x\right)-f\left(y\right)\right|\le\left(1-\frac{1}{n}\right)\left|x-y\right|<\left|x-y\right|
$$

对 $x\neq{}y$ 成立, 故 $f_n$ 是 $K$ 到自身的严格压缩映射. 由第 (1) 小题, $f_n$ 有不动点 $x_n\in{}K$.

$\blacksquare$

(3) 由 $x_n=f_n\left(x_n\right)$ 得 $x_n=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x_n\right)$, 即

$$
x_n-f\left(x_n\right)=\frac{1}{n}\left(a-f\left(x_n\right)\right).
$$

函数 $x\mapsto\left|x\right|$ 连续, 由**定理 3.7 (紧集上的极值)** 它在 $K$ 上有上界 $M$, 且 $\left|a\right|\le{}M$, $\left|f\left(x_n\right)\right|\le{}M$, 故

$$
\left|x_n-f\left(x_n\right)\right|\le\frac{2M}{n}\longrightarrow0.
$$

由**定理 4.3 (度量空间中紧与序列紧)**, 紧集 $K$ 中的序列 $\left\{x_n\right\}$ 有子列 $x_{n_k}\to{}x\in{}K$. 由 $f$ 连续, $f\left(x_{n_k}\right)\to{}f\left(x\right)$, 于是

$$
\left|x-f\left(x\right)\right|=\lim_{k\to\infty}\left|x_{n_k}-f\left(x_{n_k}\right)\right|=0,
$$

即 $f\left(x\right)=x$.

$\blacksquare$
