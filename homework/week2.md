# week2

> **命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)**
> 
> $\mathbb{R}$ 的子集连通当且仅当它是区间; 紧当且仅当它闭且有界. (讲义第 1 讲, p6)

> **命题 1.9 (连续的复合与基上的判定)**
> 
> 连续映射的复合连续; 验证 $f:X\to{}Y$ 连续只需对 $Y$ 的基元素 $U$ 验证 $f^{-1}\left(U\right)$ 开. (讲义第 1 讲, p14)

> **定义 1.11 (闭包, 内部与边界)**
> 
> $A\subset{}X$ 的闭包 $\overline{A}$ 是包含 $A$ 的最小闭集; 内部是含于 $A$ 的最大开集; 边界是 $\overline{A}$ 与内部的差. (讲义第 1 讲, p17)

> **命题 1.14 (连续函数构成代数)**
> 
> 设 $C\left(X\right)$ 是 $X$ 上连续实值函数之集, 则它对加法与乘法封闭, 且含常值 $1$. (讲义第 1 讲, p22)

> **定义 1.15 (邻域与序列收敛)**
> 
> $x$ 的邻域是含 $x$ 的开集. 称 $x_n\to{}x$, 若对 $x$ 的每个邻域 $V$ 存在 $N$ 使 $n\ge{}N$ 时 $x_n\in{}V$. (讲义第 1 讲, p23)

> **定义 2.1 (连通空间)**
> 
> 称 $X$ 连通, 若它不能写成两个不交非空开集之并; 子集 $A\subset{}X$ 连通指它在子空间拓扑下连通. (讲义第 2 讲, p11)

> **定理 2.2 (连续像连通)**
> 
> 若 $f:X\to{}Y$ 连续且 $X$ 连通, 则 $f\left(X\right)$ 连通. (讲义第 2 讲, p14)

> **定义 2.3 (凸集)**
> 
> 称 $K\subset\mathbb{R}^n$ 凸, 若 $K$ 中任意两点之间的线段含于 $K$; 凸集对凸组合封闭, 即 $\sum_i\lambda_ix_i\in{}K$ 只要 $x_i\in{}K$, $\lambda_i\ge0$, $\sum_i\lambda_i=1$. (讲义第 2 讲, p16)

> **命题 2.4 (凸集路径连通)**
> 
> $\mathbb{R}^n$ 中的凸集路径连通. (讲义第 2 讲, p16)

> **定理 2.5 (路径连通蕴含连通)**
> 
> 路径连通空间连通. (讲义第 2 讲, p16)

> **定理 2.6 (夹逼与闭包保持连通)**
> 
> 若 $E$ 连通且 $E\subset{}D\subset\overline{E}$, 则 $D$ 连通; 特别地连通集的闭包连通. (讲义第 2 讲, p20)

## 2.1 (差商的像与导函数的值域)

考虑一个可微的函数 $f:\mathbb{R}\to\mathbb{R}$, 不假设 $f'$ 连续. 考虑 $\mathbb{R}$ 上的非平凡开区间 $I$.

(1) 考虑集合 $A=\left\{\left(x,y\right)\in{}I^2:x<y\right\}$. 证明 $A$ 在最自然的拓扑下是连通集;

(2) 考虑在 $A$ 上定义的实函数 $F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}$. 证明 $\Gamma=F\left(A\right)$ 是 $\mathbb{R}$ 中的连通集;

(3) 证明 $\Gamma\subset{}f'\left(I\right)\subset\overline{\Gamma}$;

(4) 证明 $f'\left(I\right)$ 是 $\mathbb{R}$ 中的区间.

2024 年卷 A 题一.

### 解答 2.1

(1) 设 $\left(x_1,y_1\right),\left(x_2,y_2\right)\in{}A$, $t\in\left[0,1\right]$. 则

$$
\left(1-t\right)x_1+tx_2<\left(1-t\right)y_1+ty_2
$$

是 $x_1<y_1$ 与 $x_2<y_2$ 的非负系数加权和, 故组合点属于 $A$. 由**定义 2.3 (凸集)**, $A$ 凸; 由**命题 2.4 (凸集路径连通)** $A$ 路径连通; 由**定理 2.5 (路径连通蕴含连通)** $A$ 连通.

$\blacksquare$

(2) $f$ 可微故连续, 于是 $\left(x,y\right)\mapsto{}f\left(x\right)-f\left(y\right)$ 连续 (**命题 1.14 (连续函数构成代数)**), $\left(x,y\right)\mapsto{}x-y$ 连续. 在 $A$ 上 $x-y\neq0$, 而 $t\mapsto\frac{1}{t}$ 在 $\mathbb{R}-\left\{0\right\}$ 上连续, 故 $\left(x,y\right)\mapsto\frac{1}{x-y}$ 连续 (**命题 1.9 (连续的复合与基上的判定)**). 再由**命题 1.14 (连续函数构成代数)**, $F$ 是二者之积, 故连续. 定义域 $A$ 连通, 由**定理 2.2 (连续像连通)** $\Gamma=F\left(A\right)$ 连通.

$\blacksquare$

(3) 设 $x<y$ 属于 $I$. 由微分中值定理, 存在 $c\in\left(x,y\right)\subset{}I$ 使

$$
F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}=f'\left(c\right),
$$

故 $\Gamma\subset{}f'\left(I\right)$.

反之设 $x\in{}I$. 取 $y_n\in{}I-\left\{x\right\}$ 使 $y_n\to{}x$, 由导数定义

$$
F\left(x,y_n\right)=\frac{f\left(x\right)-f\left(y_n\right)}{x-y_n}\longrightarrow{}f'\left(x\right).
$$

若 $f'\left(x\right)\notin\overline{\Gamma}$, 由**定义 1.11 (闭包, 内部与边界)**, $\overline{\Gamma}$ 闭故 $\mathbb{R}-\overline{\Gamma}$ 开, 于是存在 $\varepsilon>0$ 使 $\left(f'\left(x\right)-\varepsilon,f'\left(x\right)+\varepsilon\right)\subset\mathbb{R}-\overline{\Gamma}$. 但由**定义 1.15 (邻域与序列收敛)**, 该邻域含 $F\left(x,y_n\right)\in\Gamma\subset\overline{\Gamma}$ 对充分大的 $n$, 矛盾. 故 $f'\left(x\right)\in\overline{\Gamma}$.

$\blacksquare$

(4) 由第 (2) 小题与**定理 2.6 (夹逼与闭包保持连通)**, $\overline{\Gamma}$ 连通, 由**命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)** 它是区间.

设 $a<b$ 属于 $f'\left(I\right)$, $c\in\left(a,b\right)$ 而 $c\notin{}f'\left(I\right)$. 由第 (3) 小题, $\Gamma\subset{}f'\left(I\right)\subset\mathbb{R}-\left\{c\right\}=\left(-\infty,c\right)\cup\left(c,+\infty\right)$, 右端是两个不交开集之并, 故由**定义 2.1 (连通空间)** 与 $\Gamma$ 连通, $\Gamma$ 落在其中一个, 设 $\Gamma\subset\left(-\infty,c\right)$. 集合 $\left(-\infty,c\right]$ 闭, 由**定义 1.11 (闭包, 内部与边界)** $\overline{\Gamma}\subset\left(-\infty,c\right]$, 于是 $f'\left(I\right)\subset\left(-\infty,c\right]$, 与 $b>c$ 矛盾. 故 $f'\left(I\right)$ 中任意两点的中间点仍属于它, 由**命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)** 它是区间.

$\blacksquare$
