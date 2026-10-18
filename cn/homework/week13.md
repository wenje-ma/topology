# 作业 13

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0$ 推出 $x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.19** (压缩映射)<br>称 $f:X\to X$ 是压缩的, 若存在 $0<k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. (题集 $\S4.3$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理的 $\left\|\cdot\right\|$. (题集 $\S4.3$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空**定义 6.4** (完备度量空间) 上的**定义 6.19** (压缩映射) 有唯一不动点. (题集 $\S4.3$)

### 习题一

设 $\left(X,d\right)$ 是非空**定义 6.4** (完备度量空间), $f:X\to X$ 是严格压缩的, 即存在 $0<k<1$ 使对一切 $x,y\in X$ 有 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in X$ 使 $f\left(x\right)=x$.

### 解答 习题一

任取初值 $x_0\in X$, 迭代 $x_{n+1}=f\left(x_n\right)$. 由压缩条件,

$$
d\left(x_{n+1},x_n\right)=d\left(f\left(x_n\right),f\left(x_{n-1}\right)\right)\le k\,d\left(x_n,x_{n-1}\right)\le\cdots\le k^n d\left(x_1,x_0\right).
$$

对 $m>n$, 由三角不等式,

$$
d\left(x_m,x_n\right)\le\sum_{j=n}^{m-1}d\left(x_{j+1},x_j\right)\le d\left(x_1,x_0\right)\sum_{j=n}^{\infty}k^j=\frac{k^n}{1-k}d\left(x_1,x_0\right).
$$

右端当 $n\to\infty$ 时趋于 $0$, 故 $\left(x_n\right)$ 是**定义 6.3** (柯西列). 由 $X$ 是**定义 6.4** (完备度量空间), $x_n\to x\in X$. 由 $f$ 连续 (压缩蕴含利普希茨连续), $f\left(x_n\right)\to f\left(x\right)$; 但 $f\left(x_n\right)=x_{n+1}\to x$, 故 $f\left(x\right)=x$.

唯一性: 若 $f\left(x\right)=x$, $f\left(y\right)=y$, 则 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$, 而 $0<k<1$, 故 $d\left(x,y\right)=0$, 由**定义 6.1** (度量空间) 得 $x=y$. 这就是**定理 6.16** (巴拿赫不动点定理). $\blacksquare$

### 习题二

设 $\left(E,\left\|\cdot\right\|\right)$ 是域 $\mathbb K$ 上的**定义 6.20** (赋范线性空间), $f:E\to E$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in E$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le K\left\|x-y\right\|$.

### 解答 习题二

$\left(E,\left\|\cdot\right\|\right)$ 是**定义 6.20** (赋范线性空间). 由 $f$ 在 $0$ 连续, 存在 $\delta>0$, 使 $\left\|z\right\|<\delta$ 时 $\left\|f\left(z\right)\right\|\le1$. 对任意 $x\neq0$, 令 $z=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|z\right\|=\delta/2<\delta$, 故 $\left\|f\left(z\right)\right\|\le1$. 由线性性,

$$
\left\|f\left(x\right)\right\|=\frac{2\left\|x\right\|}{\delta}\left\|f\left(z\right)\right\|\le\frac{2}{\delta}\left\|x\right\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f\left(x\right)-f\left(y\right)=f\left(x-y\right)$, 故

$$
\left\|f\left(x\right)-f\left(y\right)\right\|=\left\|f\left(x-y\right)\right\|\le K\left\|x-y\right\|.
$$

$\blacksquare$

### 习题三

沿用习题二的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb K$ 满足 $\left|\lambda\right|>K$, 固定 $a\in E$, 映射

$$
g_a\left(x\right)=\frac{a-f\left(x\right)}{\lambda}
$$

是**定义 6.19** (压缩映射); 用**定理 6.16** (巴拿赫不动点定理) 推出 $g_a$ 有唯一不动点 $J\left(a\right)\in E$.

### 解答 习题三

对 $x,y\in E$, 由习题二,

$$
\left\|g_a\left(x\right)-g_a\left(y\right)\right\|=\frac{\left\|f\left(x\right)-f\left(y\right)\right\|}{\left|\lambda\right|}\le\frac{K}{\left|\lambda\right|}\left\|x-y\right\|.
$$

由假设 $\left|\lambda\right|>K$, 故 $k=K/\left|\lambda\right|<1$. 由**定义 6.19** (压缩映射), $g_a$ 是压缩映射. $E$ 非空且是**定义 6.4** (完备度量空间), 由**定理 6.16** (巴拿赫不动点定理), $g_a$ 有唯一不动点, 记为 $J\left(a\right)$. $\blacksquare$

### 习题四

证明 $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$.

### 解答 习题四

由 $J\left(a\right)$ 与 $J\left(b\right)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J\left(a\right)=\frac{a-f\left(J\left(a\right)\right)}{\lambda},\quad J\left(b\right)=\frac{b-f\left(J\left(b\right)\right)}{\lambda}.
$$

两式相减,

$$
J\left(a\right)-J\left(b\right)=\frac{a-b-f\left(J\left(a\right)\right)+f\left(J\left(b\right)\right)}{\lambda}.
$$

取范数并用三角不等式与习题二的估计,

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{\left\|a-b\right\|+\left\|f\left(J\left(a\right)\right)-f\left(J\left(b\right)\right)\right\|}{\left|\lambda\right|}\le\frac{\left\|a-b\right\|+K\left\|J\left(a\right)-J\left(b\right)\right\|}{\left|\lambda\right|}.
$$

移项得 $\left(\left|\lambda\right|-K\right)\left\|J\left(a\right)-J\left(b\right)\right\|\le\left\|a-b\right\|$, 即

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|.
$$

$\blacksquare$

### 习题五

总结如下结论: 对任意连续线性映射 $f:E\to E$, 存在 $K>0$, 使对一切满足 $\left|\lambda\right|>K$ 的 $\lambda$ 与一切 $a\in E$, 方程 $f\left(x\right)-\lambda x=a$ (未知量 $x\in E$) 有唯一解 $J\left(a\right)$, 且映射 $a\mapsto J\left(a\right)$ 连续.

### 解答 习题五

由习题二, 存在 $K>0$ 使 $\left\|f\left(x\right)-f\left(y\right)\right\|\le K\left\|x-y\right\|$. 设 $\left|\lambda\right|>K$. 方程 $f\left(x\right)-\lambda x=a$ 等价于

$$
x=\frac{a-f\left(x\right)}{\lambda}=g_a\left(x\right).
$$

由习题三, $g_a$ 是**定义 6.19** (压缩映射), 由**定理 6.16** (巴拿赫不动点定理), 该方程有唯一解 $J\left(a\right)$.

由习题四, $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$, 即 $J$ 是利普希茨映射. 利普希茨映射连续: 对任意开集 $U\subset E$ 与 $a\in J^{-1}\left(U\right)$, 取 $\epsilon>0$ 使 $B\left(J\left(a\right),\epsilon\right)\subset U$, 则 $\left\|b-a\right\|<\left(\left|\lambda\right|-K\right)\epsilon$ 蕴含 $\left\|J\left(b\right)-J\left(a\right)\right\|<\epsilon$, 即 $J^{-1}\left(U\right)$ 含 $a$ 的一个邻域. 由**定义 3.3** (连续映射), $J$ 连续. $\blacksquare$
