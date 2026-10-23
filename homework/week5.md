# week5

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **命题 1.9 (连续的复合与基上的判定)**
> 
> 连续映射的复合连续; 验证 $f:X\to{}Y$ 连续只需对 $Y$ 的基元素 $U$ 验证 $f^{-1}\left(U\right)$ 开. (讲义第 1 讲, p14)

> **命题 1.14 (连续函数构成代数)**
> 
> $X$ 上连续实值函数之集对加法与乘法封闭, 且含常值 $1$. (讲义第 1 讲, p22)

> **定义 2.3 (凸集)**
> 
> 称 $K\subset\mathbb{R}^n$ 凸, 若 $K$ 中任意两点之间的连线段含于 $K$; 凸集对凸组合封闭, 即 $\sum_i\lambda_ix_i\in{}K$ 只要 $x_i\in{}K$, $\lambda_i\ge0$, $\sum_i\lambda_i=1$. (讲义第 2 讲, p16)

> **定理 3.2 (连续像紧)**
> 
> 紧空间的连续像是紧的: 若 $f:X\to{}Y$ 连续且 $X$ 紧, 则 $f\left(X\right)$ 紧. (讲义第 3 讲, p5)

> **定理 3.3 (紧空间的闭子集紧)**
> 
> 若 $X$ 紧, 则 $X$ 的每个闭子集紧. (讲义第 3 讲, p6)

> **定理 3.4 (豪斯多夫空间中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 的每个紧子集闭. (讲义第 3 讲, p7)

> **定理 3.5 (有限交性质)**
> 
> 设 $X$ 紧, $\mathcal{F}$ 是 $X$ 的一族闭子集, 且其中任意有限个交非空, 则 $\bigcap_{F\in\mathcal{F}}F$ 非空. (讲义第 3 讲, p9)

> **命题 3.6 ($\mathbb{R}^n$ 中的紧集)**
> 
> $\mathbb{R}^n$ 的子集紧当且仅当它闭且有界. (讲义第 3 讲, p10)

> **定理 3.7 (紧集上的极值)**
> 
> 紧集上的连续实值函数取到最大值与最小值. (讲义第 3 讲, p11)

## 5.1 (紧凸集上连续仿射映射的不动点: 角谷-马尔可夫定理)

设 $E$ 为一个有限维的 $\mathbb{R}$ 线性空间, $K$ 为 $E$ 的一个非空紧凸集. 设 $u:E\to{}E$ 是线性映射, 且 $u\left(K\right)\subset{}K$. 对任意 $n\ge1$, 定义

$$
u_n=\frac{1}{n}\left(\operatorname{Id}_E+u+u^2+\cdots+u^{n-1}\right),
$$

其中 $\operatorname{Id}_E$ 是 $E$ 上的恒同映射.

(0) 证明 $u$ 是连续的;

(1) 证明对任意 $n\ge1$, $u_n\left(K\right)$ 是 $K$ 中的紧致凸集合;

(2) 证明 $u_4\left(K\right)\subset{}u_2\left(K\right)$;

(3) 证明对任意 $n\ge1$, $u_{n!}\left(K\right)\subset{}u_{\left(n-1\right)!}\left(K\right)$, 其中 $n!$ 是 $n$ 的阶乘;

(4) 证明 $\bigcap_{n\ge1}u_{n!}\left(K\right)$ 是非空紧致凸集, 且 $\bigcap_{n\ge1}u_{n!}\left(K\right)=\bigcap_{n\ge1}u_n\left(K\right)$;

(5) 证明 $\bigcap_{n\ge1}u_n\left(K\right)$ 就是 $u$ 的所有不动点的集合.

2025 年卷 A 题二.

### 解答 5.1

(0) 取 $E$ 的一组基 $\boldsymbol{e}_1,\dots,\boldsymbol{e}_n$, 记 $x=\sum_ia_i\left(x\right)\boldsymbol{e}_i$. 令

$$
P=\left\{\sum_ia_i\boldsymbol{e}_i:\sum_i\left|a_i\right|=1\right\}.
$$

映射 $a\mapsto\sum_ia_i\boldsymbol{e}_i$ 连续, 因 $\left|\sum_i\left(a_i-a_i'\right)\boldsymbol{e}_i\right|\le\left(\sum_i\left|\boldsymbol{e}_i\right|\right)\max_i\left|a_i-a_i'\right|$; 集合 $\left\{a\in\mathbb{R}^n:\sum_i\left|a_i\right|=1\right\}$ 闭且有界, 由**命题 3.6 ($\mathbb{R}^n$ 中的紧集)** 紧, 故由**定理 3.2 (连续像紧)** $P$ 紧. 函数 $x\mapsto\left|x\right|$ 满足 $\left|\left|x\right|-\left|y\right|\right|\le\left|x-y\right|$, 故连续, 而 $0\notin{}P$, 由**定理 3.7 (紧集上的极值)** 它在 $P$ 上取到最小值 $m>0$.

对 $x\neq0$, 向量 $\sum_i\frac{a_i\left(x\right)}{\sum_j\left|a_j\left(x\right)\right|}\boldsymbol{e}_i$ 属于 $P$, 故 $\left|x\right|\ge{}m\sum_i\left|a_i\left(x\right)\right|$. 于是

$$
\left|u\left(x\right)\right|\le\sum_i\left|a_i\left(x\right)\right|\left|u\left(\boldsymbol{e}_i\right)\right|\le\frac{1}{m}\left(\sum_i\left|u\left(\boldsymbol{e}_i\right)\right|\right)\left|x\right|,
$$

即 $u$ 利普希茨, 由**定义 1.8 (连续映射)** 连续.

$\blacksquare$

(1) 由第 (0) 小题与**命题 1.14 (连续函数构成代数)** 与**命题 1.9 (连续的复合与基上的判定)**, $u_n$ 连续; $K$ 紧, 由**定理 3.2 (连续像紧)** $u_n\left(K\right)$ 紧. 又 $u^k\left(x\right)\in{}K$ 对 $k\ge0$ 与 $x\in{}K$ 成立 ($u^0=\operatorname{Id}_E$), 而 $u_n\left(x\right)$ 是 $K$ 中 $n$ 个点的凸组合, 由**定义 2.3 (凸集)** $u_n\left(x\right)\in{}K$. 故 $u_n\left(K\right)\subset{}K$. 凸性: 设 $x,y\in{}K$, $t\in\left[0,1\right]$, 则

$$
tu_n\left(x\right)+\left(1-t\right)u_n\left(y\right)=u_n\left(tx+\left(1-t\right)y\right)\in{}u_n\left(K\right),
$$

其中末步用 $tx+\left(1-t\right)y\in{}K$ 与 $u_n$ 线性. 故 $u_n\left(K\right)$ 凸.

$\blacksquare$

(2) 对 $x\in{}E$ 直接展开: $u_2\left(x\right)=\frac{1}{2}\left(x+u\left(x\right)\right)$, $u_2\left(u^2\left(x\right)\right)=\frac{1}{2}\left(u^2\left(x\right)+u^3\left(x\right)\right)$, 故

$$
u_4\left(x\right)=\frac{1}{4}\left(x+u\left(x\right)+u^2\left(x\right)+u^3\left(x\right)\right)=\frac{1}{2}\left(u_2\left(x\right)+u_2\left(u^2\left(x\right)\right)\right).
$$

设 $x\in{}K$. 则 $x,u^2\left(x\right)\in{}K$, 故 $u_2\left(x\right),u_2\left(u^2\left(x\right)\right)\in{}u_2\left(K\right)$, 由第 (1) 小题 $u_2\left(K\right)$ 凸, 于是 $u_4\left(x\right)\in{}u_2\left(K\right)$. 故 $u_4\left(K\right)\subset{}u_2\left(K\right)$.

$\blacksquare$

(3) 一般地证明 $u_{mn}\left(K\right)\subset{}u_n\left(K\right)$ 对 $m,n\ge1$ 成立. 对 $x\in{}E$,

$$
u_{mn}\left(x\right)=\frac{1}{mn}\sum_{k=0}^{mn-1}u^k\left(x\right)=\frac{1}{m}\sum_{j=0}^{m-1}u_n\left(u^{jn}\left(x\right)\right),
$$

因 $\frac{1}{n}\sum_{i=0}^{n-1}u^i\left(u^{jn}\left(x\right)\right)$ 恰是上式内层求和. 若 $x\in{}K$, 则 $u^{jn}\left(x\right)\in{}K$, 故各项 $u_n\left(u^{jn}\left(x\right)\right)\in{}u_n\left(K\right)$, 由第 (1) 小题 $u_n\left(K\right)$ 凸, 平均值属于 $u_n\left(K\right)$. 取 $m=n$ 并用 $n!=n\cdot\left(n-1\right)!$ 即得 $u_{n!}\left(K\right)\subset{}u_{\left(n-1\right)!}\left(K\right)$.

$\blacksquare$

(4) 记 $G_n=u_{n!}\left(K\right)$. 由第 (3) 小题 $\left\{G_n\right\}$ 递减, 每个 $G_n$ 由第 (1) 小题紧且非空, 凸. 赋范空间是豪斯多夫空间 (不同点 $x,y$ 的开球 $B\left(x,\frac{\left|x-y\right|}{2}\right)$, $B\left(y,\frac{\left|x-y\right|}{2}\right)$ 不交), 故由**定理 3.4 (豪斯多夫空间中紧集闭)** 每个 $G_n$ 闭. 递减闭集族具有有限交性质, 由**定理 3.5 (有限交性质)** $\bigcap_nG_n$ 非空. 又 $\bigcap_nG_n\subset{}G_1=u_1\left(K\right)=K$, 且它是 $K$ 的闭子集, 由**定理 3.3 (紧空间的闭子集紧)** 紧; 凸集之交凸, 故它凸.

等式: 由第 (3) 小题的 $u_{mn}\left(K\right)\subset{}u_n\left(K\right)$, 对每个 $n$ 取 $m$ 使 $n\mid{}m!$, 则 $u_{m!}\left(K\right)\subset{}u_n\left(K\right)$, 于是

$$
\bigcap_{n\ge1}u_{n!}\left(K\right)\subset{}u_{m!}\left(K\right)\subset{}u_n\left(K\right),
$$

对一切 $n$ 成立, 故 $\bigcap_{n}u_{n!}\left(K\right)\subset\bigcap_nu_n\left(K\right)$; 反向包含由 $\left\{n!\right\}\subset\mathbb{N}$ 显然.

$\blacksquare$

(5) 设 $u\left(x\right)=x$. 则 $u^k\left(x\right)=x$, 故 $u_n\left(x\right)=x$, 于是 $x\in{}u_n\left(K\right)$ 对一切 $n$ 成立, 即不动点集含于 $\bigcap_nu_n\left(K\right)$.

反之设 $x\in\bigcap_nu_n\left(K\right)$. 由 $u_1=\operatorname{Id}_E$ 与第 (4) 小题的等式, $x\in{}K$. 对每个 $n$ 存在 $y_n\in{}K$ 使

$$
x=u_n\left(y_n\right)=\frac{1}{n}\sum_{k=0}^{n-1}u^k\left(y_n\right),
$$

于是

$$
x-u\left(x\right)=\frac{1}{n}\left(y_n-u^n\left(y_n\right)\right),
$$

两端取范数, 由 $y_n,u^n\left(y_n\right)\in{}K$ 与**定理 3.7 (紧集上的极值)** (函数 $\left|\cdot\right|$ 在 $K$ 上有上界 $M$) 得

$$
\left|x-u\left(x\right)\right|\le\frac{2M}{n}\longrightarrow0,
$$

故 $u\left(x\right)=x$. 于是 $\bigcap_nu_n\left(K\right)$ 恰为不动点集.

$\blacksquare$
