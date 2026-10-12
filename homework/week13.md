# 作业 13

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}(U)$ 是开的. (教材 $\S3$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d(x,x)=0$, $d(x,y)=0$ 推出 $x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>序列 $(x_n)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d(x_i,x_j)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.19** (压缩映射)<br>称 $f:X\to X$ 是压缩的, 若存在 $0<k<1$ 使 $d(f(x),f(y))\le k\,d(x,y)$. (题集 $\S4.3$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理的 $\|\cdot\|$. (题集 $\S4.3$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空**定义 6.4** (完备度量空间) 上的**定义 6.19** (压缩映射) 有唯一不动点. (题集 $\S4.3$)

### 习题一

设 $(X,d)$ 是非空**定义 6.4** (完备度量空间), $f:X\to X$ 是严格压缩的, 即存在 $0<k<1$ 使对一切 $x,y\in X$ 有 $d(f(x),f(y))\le k\,d(x,y)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in X$ 使 $f(x)=x$.

### 解答 习题一

任取初值 $x_0\in X$, 迭代 $x_{n+1}=f(x_n)$. 由压缩条件,

$$
d(x_{n+1},x_n)=d(f(x_n),f(x_{n-1}))\le k\,d(x_n,x_{n-1})\le\cdots\le k^n d(x_1,x_0).
$$

对 $m>n$, 由三角不等式,

$$
d(x_m,x_n)\le\sum_{j=n}^{m-1}d(x_{j+1},x_j)\le d(x_1,x_0)\sum_{j=n}^{\infty}k^j=\frac{k^n}{1-k}d(x_1,x_0).
$$

右端当 $n\to\infty$ 时趋于 $0$, 故 $(x_n)$ 是**定义 6.3** (柯西列). 由 $X$ 是**定义 6.4** (完备度量空间), $x_n\to x\in X$. 由 $f$ 连续 (压缩蕴含利普希茨连续), $f(x_n)\to f(x)$; 但 $f(x_n)=x_{n+1}\to x$, 故 $f(x)=x$.

唯一性: 若 $f(x)=x$, $f(y)=y$, 则 $d(x,y)=d(f(x),f(y))\le k\,d(x,y)$, 而 $0<k<1$, 故 $d(x,y)=0$, 由**定义 6.1** (度量空间) 得 $x=y$. 这就是**定理 6.16** (巴拿赫不动点定理). $\blacksquare$

### 习题二

设 $(E,\|\cdot\|)$ 是域 $\mathbb K$ 上的**定义 6.20** (赋范线性空间), $f:E\to E$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in E$ 有 $\|f(x)-f(y)\|\le K\|x-y\|$.

### 解答 习题二

$(E,\|\cdot\|)$ 是**定义 6.20** (赋范线性空间). 由 $f$ 在 $0$ 连续, 存在 $\delta>0$, 使 $\|z\|<\delta$ 时 $\|f(z)\|\le1$. 对任意 $x\neq0$, 令 $z=\dfrac{\delta}{2\|x\|}x$, 则 $\|z\|=\delta/2<\delta$, 故 $\|f(z)\|\le1$. 由线性性,

$$
\|f(x)\|=\frac{2\|x\|}{\delta}\|f(z)\|\le\frac{2}{\delta}\|x\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f(x)-f(y)=f(x-y)$, 故

$$
\|f(x)-f(y)\|=\|f(x-y)\|\le K\|x-y\|.
$$

$\blacksquare$

### 习题三

沿用习题二的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb K$ 满足 $|\lambda|>K$, 固定 $a\in E$, 映射

$$
g_a(x)=\frac{a-f(x)}{\lambda}
$$

是**定义 6.19** (压缩映射); 用**定理 6.16** (巴拿赫不动点定理) 推出 $g_a$ 有唯一不动点 $J(a)\in E$.

### 解答 习题三

对 $x,y\in E$, 由习题二,

$$
\|g_a(x)-g_a(y)\|=\frac{\|f(x)-f(y)\|}{|\lambda|}\le\frac{K}{|\lambda|}\|x-y\|.
$$

由假设 $|\lambda|>K$, 故 $k=K/|\lambda|<1$. 由**定义 6.19** (压缩映射), $g_a$ 是压缩映射. $E$ 非空且是**定义 6.4** (完备度量空间), 由**定理 6.16** (巴拿赫不动点定理), $g_a$ 有唯一不动点, 记为 $J(a)$. $\blacksquare$

### 习题四

证明 $\|J(a)-J(b)\|\le\dfrac{1}{|\lambda|-K}\|a-b\|$.

### 解答 习题四

由 $J(a)$ 与 $J(b)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J(a)=\frac{a-f(J(a))}{\lambda},\qquad J(b)=\frac{b-f(J(b))}{\lambda}.
$$

两式相减,

$$
J(a)-J(b)=\frac{a-b-f(J(a))+f(J(b))}{\lambda}.
$$

取范数并用三角不等式与习题二的估计,

$$
\|J(a)-J(b)\|\le\frac{\|a-b\|+\|f(J(a))-f(J(b))\|}{|\lambda|}\le\frac{\|a-b\|+K\|J(a)-J(b)\|}{|\lambda|}.
$$

移项得 $(|\lambda|-K)\|J(a)-J(b)\|\le\|a-b\|$, 即

$$
\|J(a)-J(b)\|\le\frac{1}{|\lambda|-K}\|a-b\|.
$$

$\blacksquare$

### 习题五

总结如下结论: 对任意连续线性映射 $f:E\to E$, 存在 $K>0$, 使对一切满足 $|\lambda|>K$ 的 $\lambda$ 与一切 $a\in E$, 方程 $f(x)-\lambda x=a$ (未知量 $x\in E$) 有唯一解 $J(a)$, 且映射 $a\mapsto J(a)$ 连续.

### 解答 习题五

由习题二, 存在 $K>0$ 使 $\|f(x)-f(y)\|\le K\|x-y\|$. 设 $|\lambda|>K$. 方程 $f(x)-\lambda x=a$ 等价于

$$
x=\frac{a-f(x)}{\lambda}=g_a(x).
$$

由习题三, $g_a$ 是**定义 6.19** (压缩映射), 由**定理 6.16** (巴拿赫不动点定理), 该方程有唯一解 $J(a)$.

由习题四, $\|J(a)-J(b)\|\le\dfrac{1}{|\lambda|-K}\|a-b\|$, 即 $J$ 是利普希茨映射. 利普希茨映射连续: 对任意开集 $U\subset E$ 与 $a\in J^{-1}(U)$, 取 $\varepsilon>0$ 使 $B(J(a),\varepsilon)\subset U$, 则 $\|b-a\|<(|\lambda|-K)\varepsilon$ 蕴含 $\|J(b)-J(a)\|<\varepsilon$, 即 $J^{-1}(U)$ 含 $a$ 的一个邻域. 由**定义 3.3** (连续映射), $J$ 连续. $\blacksquare$
