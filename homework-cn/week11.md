# week11

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.16 (巴拿赫不动点定理)**
> 
> 非空完备度量空间上的压缩映射有唯一不动点. (题集 §4.3 Q1)

> **定义 6.19 (压缩映射)**
> 
> 称 $f:X\to{X}$ 是压缩的, 若存在 $0<{}k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. (题集 §4.3 Q1)

> **定义 6.27 (规范函数)**
> 
> 凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in{C},t>0\right\}$ (等价地 $\inf\left\{t>0:x\in{t}C\right\}$). (题集 §5 Q14)

> **定义 6.35 (度量空间)**
> 
> 度量 $d:X\times{X}\to\mathbb{R}_{\ge0}$ 满足:
> 
> (1) $d\left(x,x\right)=0$;
> 
> (2) 若 $d\left(x,y\right)=0$ 则 $x=y$;
> 
> (3) $d\left(x,y\right)=d\left(y,x\right)$;
> 
> (4) $d\left(x,y\right)\le{d}\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; "拓扑学"(原书第2版) $\S29$)

## 11.1 (贝尔纲定理的局部紧版本)

(贝尔纲, 局部紧版本) 证明: 在局部紧豪斯多夫空间中, 可数个稠密开集之交仍稠密.

题集 §5.1 C6.

### 解答 11.1

设 $\left\{U_n\right\}_{n=1}^{\infty}$ 是稠密开集, $V_0$ 是任意非空开集. 归纳构造非空开集 $V_n$: 由 $U_1$ 稠密, $V_0\cap{U}_1\neq\emptyset$. 取非空开 $V_1$ 使 $\overline{V_1}\subset{V}_0\cap{U}_1$ 且 $\overline{V_1}$ 紧 (由**定义 7.4 (局部紧空间)**, 局部紧豪斯多夫提供闭紧邻域基, 可在 $V_0\cap{U}_1$ 内取闭紧邻域). 归纳地, 由 $U_n$ 稠密, $V_{n-1}\cap{U}_n\neq\emptyset$, 取非空开 $V_n$ 使 $\overline{V_n}\subset{V}_{n-1}\cap{U}_n$ 且 $\overline{V_n}$ 紧.

于是 $\left\{\overline{V_n}\right\}$ 是非空紧集套. 由紧集的有限交性质 (紧空间中具有有限交性质的闭集族之交非空), 存在 $x\in\bigcap_n\overline{V_n}$. 由 $\overline{V_n}\subset{U}_n$ 与 $\overline{V_n}\subset{V}_0$, 有 $x\in{V}_0\cap\bigcap_nU_n$. 故 $V_0$ 与 $\bigcap_nU_n$ 相交. $V_0$ 任意, 由**定义 3.32 (稠密)**, $\bigcap_nU_n$ 稠密. 这正是**定理 6.13 (贝尔纲定理)** 的局部紧版本. $\blacksquare$

## 11.2 (克罗夫特引理: 题集的版本与两份卷子的版本)

(1) 设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 连续, 且对每个 $x>0$ 序列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 收敛到 $0$. 证明 $\lim_{x\to\infty}f\left(x\right)=0$. 此结论称为克罗夫特引理;

(2) (2024 卷 A 题四) 取定 $\varepsilon>0$, 令 $F_n=\left\{x\ge0:\forall{p}\in\mathbb{N},p\ge{n},\left|f\left(px\right)\right|\le\varepsilon\right\}$. 证明每个 $F_n$ 闭, $\bigcup_nF_n\supset\left(0,\infty\right)$, 再用贝尔纲定理由此推出 (1);

(3) (2024 卷 B 题四) 设 $\Omega\subset\left(0,\infty\right)$ 非空开且无界, 令 $\Omega_n=\left\{x\in\mathbb{R}:\exists{p}\ge{n},px\in\Omega\right\}$. 证明每个 $\Omega_n$ 是稠密开集, 再用贝尔纲定理由此推出 (1).

题集 $\S6$ C8; 2024 卷 A 题四; 2024 卷 B 题四.

### 解答 11.2

(1) 反设结论不真. 则存在 $\varepsilon>0$ 与趋于无穷的 $x_k$ 使 $\left|f\left(x_k\right)\right|>\varepsilon$.

对 $n\ge1$ 令 $F_n=\left\{x\ge0:\forall{p}\ge{n},\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}\right\}$. 它是闭集 (**定义 3.21 (闭集)**): 每个 $\left\{x:\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}\right\}$ 是连续函数 $\left|f\left(p\cdot\right)\right|$ 的闭水平集.

$F_n$ 覆盖 $\left(0,\infty\right)$: 固定 $x>0$, 由假设 $f\left(px\right)\to0$, 故存在 $n$ 使 $p\ge{n}$ 时 $\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}$, 即 $x\in{F}_n$.

$\left(0,\infty\right)$ 是完备空间 $\mathbb{R}$ 的开子集, 故它自身是贝尔空间. 由**定理 6.13 (贝尔纲定理)**, 闭集的可数并不整个覆盖它而不留内点, 故某个 $F_N$ 含非退化区间 $\left(u,v\right)\subset\left(0,\infty\right)$.

取 $y\in\left(u,v\right)$ 固定. 对 $k$ 令 $p_k=\left\lfloor\frac{x_k}{y}\right\rfloor$. 因 $x_k\to\infty$, 有 $p_k\to\infty$, 故 $p_k\ge{N}$ 对大的 $k$ 成立; 又

$$
\frac{x_k}{p_k}=\frac{x_k}{\left\lfloor{x}_k/y\right\rfloor}\longrightarrow{y},
$$

故 $\frac{x_k}{p_k}\in\left(u,v\right)\subset{F}_N$ 对大的 $k$ 成立. 于是 $x_k=p_k\cdot\frac{x_k}{p_k}$ 且 $p_k\ge{N}$, 由 $F_N$ 的定义 $\left|f\left(x_k\right)\right|\le\frac{\varepsilon}{2}$, 与 $\left|f\left(x_k\right)\right|>\varepsilon$ 矛盾. $\blacksquare$

(2) 闭性同 (1). 覆盖: 固定 $x>0$, $f\left(px\right)\to0$ 故存在 $n$ 使 $p\ge{n}$ 时 $\left|f\left(px\right)\right|\le\varepsilon$, 即 $x\in{F}_n$; 于是 $\bigcup_nF_n\supset\left(0,\infty\right)$. 收尾与 (1) 完全一样, 只把 $\frac{\varepsilon}{2}$ 换成 $\varepsilon$. 这两步正是卷 A 的分法. $\blacksquare$

(3) $\Omega_n$ 开: $\Omega_n=\bigcup_{p\ge{n}}\frac{1}{p}\Omega$, 而 $\frac{1}{p}\Omega$ 是开集在连续映射 $x\mapsto\frac{x}{p}$ 下的像, 开. 稠密: 取非退化区间 $J\subset\mathbb{R}$, 要证 $J\cap\Omega_n\neq\emptyset$. 因 $\Omega$ 无界开, 取 $q\in\Omega$ 使 $q>{}n\cdot\max\left\{\left|t\right|:t\in{J}\right\}$; 则 $\frac{q}{p}\in{J}$ 对某个 $p\ge{n}$ 成立 (因 $\frac{q}{p}$ 随 $p$ 从 $\frac{q}{n}$ 递减到 $0$, 而 $J$ 含区间内所有足够小的正数), 且 $p\cdot\frac{q}{p}=q\in\Omega$, 故 $\frac{q}{p}\in\Omega_n$.

由**定理 6.13 (贝尔纲定理)**, 可数个稠密开集之交稠密, 取 $x_0\in\bigcap_n\Omega_n$ 且 $x_0>0$. 则对每个 $n$ 有 $p\ge{n}$ 使 $px_0\in\Omega$; 若 $\lim_{x\to\infty}f\left(x\right)\neq0$, 取 $\varepsilon$ 与 $y_m\to\infty$ 使 $\left|f\left(y_m\right)\right|>\varepsilon$, 则那些 $px_0$ 任意大而 $f\left(px_0\right)\to0$, 与 $\Omega$ 内 $\left|f\right|$ 一致地大于 $\varepsilon$ 的取法矛盾. 严格地说: 由 $\Omega$ 与 $\varepsilon$ 的取法 (把 $\Omega$ 取成 $\left|f\right|>\varepsilon$ 的开集, 它无界), Baire 给出的 $x_0$ 使无穷多个 $px_0$ 落在 $\Omega$, 于是沿这列 $\left|f\left(px_0\right)\right|>\varepsilon$, 与 $f\left(px_0\right)\to0$ 矛盾. $\blacksquare$

> 三个版本是同一件事的三种包装: 卷 A 用闭集 $F_n$ 逼近, 卷 B 用稠密开集 $\Omega_n$ 逼近. 反设之后必须把"沿某个 $y$ 的所有整数倍"与"给定的坏列 $x_k$"接起来, 这一步靠的是 $\frac{x_k}{\left\lfloor{x}_k/y\right\rfloor}\to{y}$.

## 11.3 (对平移量的收敛在紧区间上一致)

设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 连续, 且对每个 $\lambda\ge0$ 有 $\lim_{x\to\infty}\left(f\left(x+\lambda\right)-f\left(x\right)\right)=0$. 证明对任意 $\left[a,b\right]\subset\mathbb{R}_{\ge0}$, 该收敛对 $\lambda\in\left[a,b\right]$ 一致, 即 $\sup_{\lambda\in\left[a,b\right]}\left|f\left(x+\lambda\right)-f\left(x\right)\right|\to0$ ($x\to\infty$).

题集 $\S6$ C10.

### 解答 11.3

对 $x\ge0$ 令 $M\left(x\right)=\sup_{\lambda\in\left[a,b\right]}\left|f\left(x+\lambda\right)-f\left(x\right)\right|$. 它是有限值: 固定 $x$ 时 $\lambda\mapsto{f}\left(x+\lambda\right)-f\left(x\right)$ 在紧区间 $\left[a,b\right]$ 上连续, 故有界.

对 $\varepsilon>0$ 令 $A_\varepsilon=\left\{x\ge0:M\left(x\right)\le\varepsilon\right\}$. 它是闭集: $M$ 是连续函数族 $\left(x,\lambda\right)\mapsto\left|f\left(x+\lambda\right)-f\left(x\right)\right|$ 对紧参数 $\lambda$ 取上确界, 故 $M$ 下半连续, 而下半连续函数的 $\left\{M\le\varepsilon\right\}$ 是闭集.

覆盖: $\bigcup_{\varepsilon>0}A_\varepsilon=\left[0,\infty\right)$, 由上面的有限性.

由**定理 6.13 (贝尔纲定理)**, 在完备空间 $\left[0,\infty\right)$ 中, 对任意非退化区间 $J\subset\left(0,\infty\right)$, 闭集族 $\left\{A_{1/n}\cap{J}\right\}$ 覆盖 $J$ 且 $J$ 完备, 故某个 $A_{1/n}\cap{J}$ 含 $J$ 中的非退化区间. 于是

$$
D_\varepsilon=\bigcup_{n}\operatorname{int}\left(A_\varepsilon\right)
$$

在每个 $J$ 中非空, 故稠密; 它开, 故稠密开.

下面用稠密性把 $M$ 压到 $0$. 反设 $\lim_{x\to\infty}M\left(x\right)=0$ 不成立: 存在 $\varepsilon>0$ 与属于某一个 $x_k\to\infty$ 的序列, 使 $M\left(x_k\right)>3\varepsilon$, 即存在 $\lambda_k\in\left[a,b\right]$ 使 $\left|f\left(x_k+\lambda_k\right)-f\left(x_k\right)\right|>3\varepsilon$.

固定 $k$. 函数 $f$ 在紧区间 $\left[x_k,x_k+b\right]$ 上一致连续, 故存在 $\delta_k>0$ 使 $\left|u-v\right|\le\delta_k$ 且 $u,v\in\left[x_k,x_k+b\right]$ 时 $\left|f\left(u\right)-f\left(v\right)\right|\le\varepsilon$. 对 $y\in\left(x_k-\delta_k,x_k+\delta_k\right)$ 与 $\lambda\in\left[a,b\right]$,

$$
\left|f\left(y+\lambda\right)-f\left(y\right)\right|\ge\left|f\left(x_k+\lambda\right)-f\left(x_k\right)\right|-2\varepsilon>3\varepsilon-2\varepsilon=\varepsilon,
$$

其中用到了 $\left|y+\lambda-\left(x_k+\lambda\right)\right|=\left|y-x_k\right|\le\delta_k$. 故 $M\left(y\right)>\varepsilon$ 对整个区间 $\left(x_k-\delta_k,x_k+\delta_k\right)$ 成立, 即该区间与 $D_\varepsilon$ 不交. 但 $D_\varepsilon$ 稠密, 任何非空开区间必与它相交, 矛盾. $\blacksquare$

> 一致性不能从"每个 $\lambda$ 都收敛"直接读出, 因为对 $\lambda$ 的收敛可能被 $\lambda$ 的微小移动放大; 贝尔纲在这里的作用就是禁止这种放大发生在任意大的 $x$ 处.

## 11.4 (完备度量空间上严格压缩映射的不动点)

设 $\left(X,d\right)$ 是非空完备度量空间, $f:X\to{X}$ 是严格压缩的, 即存在 $0<{}k<1$ 使对一切 $x,y\in{X}$ 有 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in{X}$ 使 $f\left(x\right)=x$.

题集 §4.3 Q1.

### 解答 11.4

任取初值 $x_0\in{X}$, 迭代 $x_{n+1}=f\left(x_n\right)$. 由压缩条件,

$$
d\left(x_{n+1},x_n\right)=d\left(f\left(x_n\right),f\left(x_{n-1}\right)\right)\le{k}\,d\left(x_n,x_{n-1}\right)\le\cdots\le{k}^nd\left(x_1,x_0\right).
$$

对 $m>{}n$, 由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x_m,x_n\right)\le\sum_{j=n}^{m-1}d\left(x_{j+1},x_j\right)\le{d}\left(x_1,x_0\right)\sum_{j=n}^{\infty}k^j=\frac{k^n}{1-k}d\left(x_1,x_0\right).
$$

右端当 $n\to\infty$ 时趋于 $0$, 故 $\left(x_n\right)$ 是**定义 6.37 (柯西列)**. 由 $X$ 是**定义 6.38 (完备度量空间)**, $x_n\to{x}\in{X}$. 压缩映射满足 $d\left(f\left(x_n\right),f\left(x\right)\right)\le{k}\,d\left(x_n,x\right)\to0$, 即 $f$ 连续, 故 $f\left(x_n\right)\to{f}\left(x\right)$; 但 $f\left(x_n\right)=x_{n+1}\to{x}$, 由极限唯一性得 $f\left(x\right)=x$.

唯一性: 若 $f\left(x\right)=x$, $f\left(y\right)=y$, 则 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$, 而 $0<{}k<1$, 故 $d\left(x,y\right)=0$, 由**定义 6.35 (度量空间)** 的正定性得 $x=y$. 这就是**定理 6.16 (巴拿赫不动点定理)**. $\blacksquare$

## 11.5 (连续线性映射的利普希茨估计)

设 $\left(E,\left\|\cdot\right\|\right)$ 是域 $\mathbb{K}$ 上的赋范线性空间, $f:E\to{E}$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in{E}$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{K}\left\|x-y\right\|$.

题集 §4.3 Q2.

### 解答 11.5

由 $f$ 在 $0$ 连续 (按**定义 3.22 (连续映射)**, $\left\|z\right\|\to0$ 时 $\left\|f\left(z\right)\right\|\to0$), 存在 $\delta>0$, 使 $\left\|z\right\|<\delta$ 时 $\left\|f\left(z\right)\right\|\le1$. 对任意 $x\neq0$, 令 $z=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|z\right\|=\delta/2<\delta$, 故 $\left\|f\left(z\right)\right\|\le1$. 由线性性,

$$
\left\|f\left(x\right)\right\|=\frac{2\left\|x\right\|}{\delta}\left\|f\left(z\right)\right\|\le\frac{2}{\delta}\left\|x\right\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f\left(x\right)-f\left(y\right)=f\left(x-y\right)$, 故

$$
\left\|f\left(x\right)-f\left(y\right)\right\|=\left\|f\left(x-y\right)\right\|\le{K}\left\|x-y\right\|.
$$

$\blacksquare$

## 11.6 (压缩映射 $g_a$ 与解算子 $J$)

沿用习题 11.5 的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb{K}$ 满足 $\left|\lambda\right|>{}K$, 固定 $a\in{E}$, 映射

$$
g_a\left(x\right)=\frac{a-f\left(x\right)}{\lambda}
$$

是压缩映射; 用巴拿赫不动点定理推出 $g_a$ 有唯一不动点 $J\left(a\right)\in{E}$.

题集 §4.3 Q3.

### 解答 11.6

对 $x,y\in{E}$, 由习题 11.5,

$$
\left\|g_a\left(x\right)-g_a\left(y\right)\right\|=\frac{\left\|f\left(x\right)-f\left(y\right)\right\|}{\left|\lambda\right|}\le\frac{K}{\left|\lambda\right|}\left\|x-y\right\|.
$$

由假设 $\left|\lambda\right|>{}K$, 故 $k=K/\left|\lambda\right|<1$. 由**定义 6.19 (压缩映射)**, $g_a$ 是压缩映射. $E$ 非空且是**定义 6.38 (完备度量空间)**, 由**定理 6.16 (巴拿赫不动点定理)**, $g_a$ 有唯一不动点, 记为 $J\left(a\right)$. $\blacksquare$

## 11.7 (解算子 $J$ 的利普希茨估计)

证明 $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$.

题集 §4.3 Q4.

### 解答 11.7

由 $J\left(a\right)$ 与 $J\left(b\right)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J\left(a\right)=\frac{a-f\left(J\left(a\right)\right)}{\lambda},\quad{J}\left(b\right)=\frac{b-f\left(J\left(b\right)\right)}{\lambda}.
$$

两式相减,

$$
J\left(a\right)-J\left(b\right)=\frac{a-b-f\left(J\left(a\right)\right)+f\left(J\left(b\right)\right)}{\lambda}.
$$

取范数并用三角不等式与习题 11.5 的估计,

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{\left\|a-b\right\|+\left\|f\left(J\left(a\right)\right)-f\left(J\left(b\right)\right)\right\|}{\left|\lambda\right|}\le\frac{\left\|a-b\right\|+K\left\|J\left(a\right)-J\left(b\right)\right\|}{\left|\lambda\right|}.
$$

移项得 $\left(\left|\lambda\right|-K\right)\left\|J\left(a\right)-J\left(b\right)\right\|\le\left\|a-b\right\|$, 即

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|.
$$

$\blacksquare$

## 11.8 (方程 $f\left(x\right)-\lambda{x}=a$ 的唯一可解性与解的连续性)

总结如下结论: 对任意连续线性映射 $f:E\to{E}$, 存在 $K>0$, 使对一切满足 $\left|\lambda\right|>{}K$ 的 $\lambda$ 与一切 $a\in{E}$, 方程 $f\left(x\right)-\lambda{x}=a$ (未知量 $x\in{E}$) 有唯一解 $J\left(a\right)$, 且映射 $a\mapsto{J}\left(a\right)$ 连续.

题集 §4.3 Q5.

### 解答 11.8

由习题 11.5, 存在 $K>0$ 使 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{K}\left\|x-y\right\|$. 设 $\left|\lambda\right|>{}K$. 方程 $f\left(x\right)-\lambda{x}=a$ 等价于

$$
x=\frac{a-f\left(x\right)}{\lambda}=g_a\left(x\right).
$$

由习题 11.6, $g_a$ 是**定义 6.19 (压缩映射)**, 由**定理 6.16 (巴拿赫不动点定理)**, 该方程有唯一解 $J\left(a\right)$. $\blacksquare$

由习题 11.7, $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$, 即 $J$ 是利普希茨映射. 由利普希茨映射连续, $J$ 连续. $\blacksquare$

## 11.9 (交集的规范函数是各规范函数的上确界)

设 $E$ 是 $\mathbb{K}$ 上拓扑向量空间, $C$ 是 $0$ 的凸邻域, 规范函数 $\left\|\cdot\right\|_C:E\to\left[0,\infty\right)$ 由规范函数给出. 若 $\left\{C_\alpha\right\}_{\alpha\in{A}}$ 是 $E$ 中一族凸集且其交是 $0$ 的凸邻域, 证明

$$
\left\|\cdot\right\|_{\bigcap_{\alpha\in{A}}C_\alpha}=\sup_{\alpha\in{A}}\left\|\cdot\right\|_{C_\alpha}.
$$

题集 §5 Q14.

### 解答 11.9

记 $C=\bigcap_{\alpha\in{A}}C_\alpha$. 由**定义 6.27 (规范函数)**,

$$
\left\|x\right\|_C=\inf\left\{t>0:x\in{t}C\right\}=\inf\left\{t>0:\;x\in{t}C_\alpha\;\text{对一切}\;\alpha\right\}.
$$

而 $x\in{t}C_\alpha$ 当且仅当 $t\ge\left\|x\right\|_{C_\alpha}$ (规范函数的次水平集刻画). 故同时对一切 $\alpha$ 成立当且仅当

$$
t\ge\sup_{\alpha\in{A}}\left\|x\right\|_{C_\alpha}.
$$

取下确界即得

$$
\left\|x\right\|_C=\sup_{\alpha\in{A}}\left\|x\right\|_{C_\alpha}.
$$

两边对一切 $x\in{E}$ 成立, 故函数相等. $\blacksquare$
