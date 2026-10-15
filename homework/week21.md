# 作业 21

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$, 满足空集与全集开, 有限交开, 任意并开. (教材 $\S3$)

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.4** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. (教材 $\S3$)

> **定理 4.1** (区间连通)<br>$\left[0,1\right]$ 连通; 由此任意区间连通. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸当且仅当 $x,y\in K$ 蕴含连线含于 $K$; 凸集必路径连通. (教材 $\S4$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧当且仅当闭且有界. (教材 $\S5$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价. (教材 $\S6$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性, 三角不等式. (教材 $\S6$)

> **定义 6.2** (开球)<br>$B\left(x,r\right)=\left\{y:d\left(x,y\right)<r\right\}$; 开球全体是度量拓扑的基. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛. (教材 $\S6$)

> **定义 6.18** (等距映射)<br>满足 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)$ 的映射. (题集 $\S3.4$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

### 习题一

设 $f:\left[0,1\right]\to\mathbb R$ 是一个连续函数并且 $f\left(0\right)=f\left(1\right)$.

(1) (10 分) 证明存在 $x\in\left[0,\frac12\right]$ 使得 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) (10 分) 证明对于任意的整数 $n\ge2$, 存在 $x\in\left[0,1-\frac1n\right]$ 使得 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) (5 分) 证明存在一个连续函数 $f:\left[0,1\right]\to\mathbb R$ 使得对于任意的 $x\in\left[0,\frac35\right]$ 都有 $f\left(x\right)\neq f\left(x+\frac25\right)$.

### 解答 习题一

(1) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac12\right)$, 定义域 $\left[0,\frac12\right]$. 若 $g\left(0\right)=0$, 则 $x=0$ 已满足. 否则

$$
g\left(\frac12\right)=f\left(\frac12\right)-f\left(1\right)=f\left(\frac12\right)-f\left(0\right)=-g\left(0\right),
$$

故 $g\left(0\right)$ 与 $g\left(\frac12\right)$ 异号. 由介值定理 (连续函数在区间上取得中间值), 存在 $x\in\left[0,\frac12\right]$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac1n\right)$, 定义域 $\left[0,1-\frac1n\right]$. 累加得

$$
\sum_{j=0}^{n-1}g\left(\frac{j}{n}\right)=\sum_{j=0}^{n-1}\left(f\left(\frac{j}{n}\right)-f\left(\frac{j+1}{n}\right)\right)=f\left(0\right)-f\left(1\right)=0.
$$

若 $g$ 在 $\left[0,1-\frac1n\right]$ 上恒不为 $0$, 因该区间连通 (由**定理 4.1** (区间连通)), 连续函数 $g$ 必恒正或恒负, 从而各 $g\left(\frac{j}{n}\right)$ 同号, 其和不为 $0$, 矛盾. 故存在 $x$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) 取 $f\left(x\right)=x$. 它连续, 且对任意 $x\in\left[0,\frac35\right]$, $f\left(x+\frac25\right)-f\left(x\right)=\frac25\neq0$, 故 $f\left(x\right)\neq f\left(x+\frac25\right)$. 此例即满足要求. $\blacksquare$

### 习题二

考虑在 $x,y\in\left(0,\infty\right)$ 上定义的函数 $\delta\left(x,y\right)=\left|\frac1x-\frac1y\right|$.

(1) (10 分) 证明 $\delta$ 是一个在 $\left(0,\infty\right)$ 上的度量.

(2) (10 分) 证明由 $\delta$ 在 $\left(0,\infty\right)$ 上诱导的拓扑就是最常见的拓扑.

(3) (5 分) 证明度量空间 $\left(\left(0,\infty\right),\delta\right)$ 不是完备的.

(4) (5 分) 证明度量空间 $\left(\left(0,1\right],\delta\right)$ 是完备的.

### 解答 习题二

(1) 令 $\varphi:\left(0,\infty\right)\to\left(0,\infty\right)$ 为 $\varphi\left(x\right)=\frac1x$, 则 $\delta\left(x,y\right)=\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$. 它是由通常绝对值度量经双射 $\varphi$ 拉回的. 逐条验证**定义 6.1** (度量空间) 的公理: $\delta\left(x,x\right)=0$; $\delta\left(x,y\right)=0\Rightarrow\left|\varphi\left(x\right)-\varphi\left(y\right)\right|=0\Rightarrow\varphi\left(x\right)=\varphi\left(y\right)\Rightarrow x=y$; 对称性显然; 三角不等式由绝对值的三角不等式给出:

$$
\delta\left(x,z\right)=\left|\varphi\left(x\right)-\varphi\left(z\right)\right|\le\left|\varphi\left(x\right)-\varphi\left(y\right)\right|+\left|\varphi\left(y\right)-\varphi\left(z\right)\right|=\delta\left(x,y\right)+\delta\left(y,z\right).
$$

故 $\delta$ 是度量.

(2) 映射 $\varphi\left(x\right)=\frac1x$ 及其逆 $\varphi^{-1}\left(y\right)=\frac1y$ 在通常拓扑下都连续, 故由**定义 3.4** (同胚), $\varphi$ 是 $\left(0,\infty\right)$ 到自身的同胚, 且由第 1 小题它保持距离 (即**定义 6.18** (等距映射)). 由**定义 6.2** (开球), $\delta$ 的开球 $B_\delta\left(x,r\right)=\varphi^{-1}\left(\left(\varphi\left(x\right)-r,\varphi\left(x\right)+r\right)\right)$ 是通常拓扑下的开集; 反之通常开球也同理是 $\delta$-开集. 故两种开球生成同一拓扑, 即 $\delta$ 诱导通常拓扑.

(3) 取 $x_n=n$. 则 $\delta\left(n,m\right)=\left|\frac1n-\frac1m\right|\to0$ ($n,m\to\infty$), 由**定义 6.3** (柯西列) $\left(x_n\right)$ 是 $\delta$-柯西列. 若它在 $\left(0,\infty\right)$ 中收敛于 $x$, 则 $\delta\left(n,x\right)=\left|\frac1n-\frac1x\right|\to0$, 即 $\frac1x=0$, 不可能. 故该柯西列不收敛, 由**定义 6.4** (完备度量空间), $\left(\left(0,\infty\right),\delta\right)$ 不完备.

(4) 在 $\varphi\left(x\right)=\frac1x$ 下, $\left(\left(0,1\right],\delta\right)$ 等距 (由**定义 6.18** (等距映射)) 于 $\left(\left[1,\infty\right),\left|\cdot\right|\right)$. 设 $\left(y_n\right)$ 是 $\left[1,\infty\right)$ 中的柯西列, 则它也是 $\mathbb R$ 中的柯西列, 故在 $\mathbb R$ 中收敛于 $y$; 又每个 $y_n\ge1$, 极限保持 $y\ge1$, 故 $y\in\left[1,\infty\right]$, 即 $\left[1,\infty\right)$ 完备. 等距把收敛性搬过去, 故 $\left(\left(0,1\right],\delta\right)$ 完备. $\blacksquare$

### 习题三

考虑一个 $\mathbb R^2$ 中的闭集 $A$. 还假设 $A$ 是一个凸集, 原点 $O\in A$, 并且 $A$ 不是有界的.

(1) (10 分) 证明对于任意的正整数 $p\ge1$, 都存在一个点 $M_p\in A$, 线段 $OM_p$ 属于 $A$, 并且其长度 $\left|OM_p\right|\ge p$.

(2) (10 分) 记线段 $OM_p$ 与单位圆周的交点为 $u_p$. 证明存在一个 $\left\{u_p\right\}_{p\ge1}$ 的子列收敛到单位圆周上的某一点 $u$.

(3) (10 分) 证明 $A$ 包含一条从原点出发的长度无穷的半直线.

### 解答 习题三

(1) 因 $A$ 无界, 对每个 $p$, 存在 $M_p\in A$ 使 $\left|M_p\right|\ge p$ (否则 $A$ 含于半径 $p$ 的球内, 有界). 由**定义 4.6** (凸集), $O\in A$ 与 $M_p\in A$ 的连线线段 $OM_p$ 含于 $A$, 且其长度 $\left|OM_p\right|=\left|M_p\right|\ge p$.

(2) 令 $r_p=\left|M_p\right|$, $u_p=\frac{M_p}{r_p}$, 则 $u_p$ 在单位圆周 $S^1=\left\{v\in\mathbb R^2:\left|v\right|=1\right\}$ 上. $S^1$ 闭且有界, 由**定理 5.3** ($\mathbb R^n$ 中的紧集) $S^1$ 紧. 由**定理 6.1** (紧=序列紧), 序列 $\left(u_p\right)\subset S^1$ 有收敛子列 $u_{p_j}\to u\in S^1$.

(3) 固定 $\lambda\ge0$. 对充分大的 $j$, $r_{p_j}\ge\lambda$ (因 $r_{p_j}\ge p_j\to\infty$). 由**定义 4.6** (凸集), $\lambda u_{p_j}=\frac{\lambda}{r_{p_j}}M_{p_j}+\left(1-\frac{\lambda}{r_{p_j}}\right)O$ 是 $M_{p_j}$ 与 $O$ 的凸组合, 故 $\lambda u_{p_j}\in A$. 当 $j\to\infty$, $u_{p_j}\to u$, 故 $\lambda u_{p_j}\to\lambda u$. 因 $A$ 闭 (由**定义 3.2** (闭集), 闭集含其序列极限), $\lambda u\in A$. 由 $\lambda\ge0$ 任意, 半直线 $\left\{\lambda u:\lambda\ge0\right\}\subset A$, 即 $A$ 含一条从原点出发的无穷长半直线. $\blacksquare$

### 习题四

设 $f:\mathbb R_{\ge0}\to\mathbb R$ 是一个连续函数, 并且对于任意的 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 都收敛到 $0$.

(1) (5 分) 设 $\Omega\subset\left(0,\infty\right)$ 是一个非平凡开集且 $\Omega$ 不是有界的. 考虑集合 $\Omega_n=\left\{x\in\mathbb R:\exists p\ge n,\ px\in\Omega\right\}$. 证明对于任意 $n\ge1$, $\Omega_n$ 都是在 $\mathbb R$ 中的稠密开集合.

(2) (5 分) 利用贝尔纲定理, 证明存在 $x_0$, 使得对任意 $N\in\mathbb N$, 存在 $n\ge N$ 使 $n x_0\in\Omega$.

(3) (5 分) 证明 $\lim_{x\to\infty}f\left(x\right)=0$.

### 解答 习题四

(1) 开: $\Omega_n=\bigcup_{p\ge n}\left\{x:px\in\Omega\right\}=\bigcup_{p\ge n}\frac1p\,\Omega$. 每个 $\frac1p\Omega$ 是开集的相似像, 由**定义 3.3** (连续映射) 相似映射 $x\mapsto px$ 是同胚, 故 $\frac1p\Omega$ 开; 由**定义 3.1** (拓扑空间) 开集任意并开, $\Omega_n$ 开.

稠: 任取非空开区间 $\left(a,b\right)$. 因 $\Omega$ 无界, 取 $y\in\Omega$ 充分大. 取 $p=\left\lceil\frac yb\right\rceil$, 则 $pb\ge y$ 且 $\left(p-1\right)b<y$, 从而 $x=\frac yp$ 满足 $x\le b$ 且 $x>\frac{\left(p-1\right)b}{p}=b\left(1-\frac1p\right)$. 取 $y$ 足够大使 $p\ge n$ 且 $b\left(1-\frac1p\right)>a$, 则 $x\in\left(a,b\right)$ 且 $px=y\in\Omega$. 故 $\left(a,b\right)$ 交 $\Omega_n$, $\Omega_n$ 稠密.

(2) $\mathbb R$ 完备. 由第 1 小题, 每个 $\Omega_n$ 是稠密开集. 由**定理 6.13** (贝尔纲定理), 可数交 $\bigcap_{n\ge1}\Omega_n$ 稠密, 故非空, 取 $x_0\in\bigcap_{n\ge1}\Omega_n$. 则对任意 $N$, $x_0\in\Omega_N$, 即存在 $p\ge N$ 使 $px_0\in\Omega$.

(3) 取定 $\epsilon>0$, 令 $\Omega=\left\{x>0:\left|f\left(x\right)\right|>\epsilon\right\}$. 由**定义 3.3** (连续映射), $f$ 连续, 故 $\Omega$ 是开集. 若 $\Omega$ 无界, 由第 2 小题存在 $x_0$ 使 $\left|f\left(nx_0\right)\right|>\epsilon$ 对任意大的 $n$ 成立, 与题设 $f\left(nx_0\right)\to0$ 矛盾. 故 $\Omega$ 有界, 即存在 $T$ 使 $x>T$ 时 $x\notin\Omega$, 亦即 $\left|f\left(x\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{x\to\infty}f\left(x\right)=0$. $\blacksquare$
