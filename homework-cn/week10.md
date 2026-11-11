# week10 (((完备空间: 柯西列与完备性)))

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.25 (邻域与极限)**
> 
> $b\in{X}$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to{b}$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in{U}$. (教材 $\S3$, p16)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 5.2 (区间紧)**
> 
> 区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 5.3 ($\mathbb{R}^n$ 中的紧集)**
> 
> $K\subset\mathbb{R}^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.7 (连续函数的一致极限连续)**
> 
> 连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **定理 6.8 ($C\left(X,Y\right)$ 完备)**
> 
> $Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.12 (阿尔泽拉-阿斯科利定理)**
> 
> 设 $K$ 为紧度量空间, $F\subset{C}\left(K\right)$ 为等度连续且一致有界的函数族, 则 $F$ 是紧的. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

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

> **定义 6.36 (开球)**
> 
> 开球 $B\left(x,r\right)=\left\{y\in{X}:d\left(x,y\right)<{}r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.39 (完备化)**
> 
> 任意度量空间可自然嵌入一个完备度量空间; 实数轴 $\mathbb{R}$ 是有理数集的完备化, 故 $\mathbb{R}$ 完备. (教材 $\S6$)

> **定义 6.41 (一致收敛与一致度量)**
> 
> $d\left(f,g\right)=\sup_{x\in{X}}\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛于 $g$ 当且仅当 $d\left(f_n,g\right)\to0$. (教材 §6)

> **定义 6.43 (上确界度量)**
> 
> 紧集 $K$ 上连续函数空间 $C\left(K\right)$ 装备 $d\left(f,g\right)=\sup_{x\in{K}}\left|f\left(x\right)-g\left(x\right)\right|$, 即上确界范数诱导的度量. (教材 $\S6$)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

## 10.1 ($\left(0,\infty\right)$ 上的倒数度量: 诱导通常拓扑却不完备)

(2024 年卷 B 题目二) 在 $\left(0,\infty\right)$ 上定义 $\delta\left(x,y\right)=\left|\frac1x-\frac1y\right|$.

(1) 证明 $\delta$ 是 $\left(0,\infty\right)$ 上的度量;

(2) 证明 $\delta$ 诱导通常拓扑;

(3) 证明 $\left(\left(0,\infty\right),\delta\right)$ 不完备;

(4) 证明 $\left(\left(0,1\right],\delta\right)$ 完备.

卷 B 题二 (即题集 §3.5 C5).

### 解答 10.1

(1) 令 $\varphi\left(x\right)=1/x$, 则 $\delta\left(x,y\right)=\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$ 由绝对值诱导, 满足**定义 6.35 (度量空间)** 的全部四条公理. $\blacksquare$

(2) $\varphi:\left(0,\infty\right)\to\left(0,\infty\right)$ 在通常拓扑下是同胚 (连续双射, 逆 $x\mapsto1/x$ 连续). $\delta$ 是 $\varphi$ 拉回的通常距离, 故诱导通常拓扑. $\blacksquare$

(3) 取 $x_n=n$. 则 $\delta\left(x_n,x_m\right)=\left|1/n-1/m\right|\to0$, 是**定义 6.37 (柯西列)**; 但若收敛于 $x\in\left(0,\infty\right)$, 则 $\delta\left(x_n,x\right)\to\left|0-1/x\right|=1/x>0$, 矛盾. 故它不收敛, $\left(\left(0,\infty\right),\delta\right)$ 不是**定义 6.38 (完备度量空间)**. $\blacksquare$

(4) 设 $x_n\in\left(0,1\right]$ 是 $\delta$-柯西列. 则 $1/x_n\in\left[1,\infty\right)$ 通常柯西, 由**定义 6.39 (完备化)** (即 $\mathbb{R}$ 完备), $1/x_n\to{L}\ge1$. 令 $x=1/L\in\left(0,1\right]$, 则 $\delta\left(x_n,x\right)\to0$. 故 $\left(\left(0,1\right],\delta\right)$ 完备. $\blacksquare$

## 10.2 ($\mathbb{R}^n$ 中紧集与闭集的距离可达, $l^\infty$ 中不可达)

设 $E=\mathbb{R}^n$ 装备通常拓扑, $K$ 是 $E$ 中的紧集, $F$ 是 $E$ 中的闭集.

(1) 证明存在 $\boldsymbol{x}\in{K}$ 与 $\boldsymbol{y}\in{F}$ 使 $d\left(K,F\right)=d\left(\boldsymbol{x},\boldsymbol{y}\right)$, 其中 $d\left(K,F\right)=\inf_{\boldsymbol{x}\in{K},\boldsymbol{y}\in{F}}d\left(\boldsymbol{x},\boldsymbol{y}\right)$;

(2) 举例说明把 $E$ 换成 $l^\infty$ 后结论不成立. 可考虑 $F=\left\{\left(1+2^{-n}\right)e_n\right\}_{n\ge0}$, 其中 $e_n$ 是第 $n$ 位为 $1$ 其余为 $0$ 的序列.

题集 §4.1 Q2.

### 解答 10.2

(1) 由**定义 6.46 (点到集合的距离)**, $d\left(K,F\right)=\inf_{\boldsymbol{x}\in{K},\boldsymbol{y}\in{F}}\left\|\boldsymbol{x}-\boldsymbol{y}\right\|$. 取序列 $\boldsymbol{x}_n\in{K}$, $\boldsymbol{y}_n\in{F}$ 使 $\left\|\boldsymbol{x}_n-\boldsymbol{y}_n\right\|\to{d}\left(K,F\right)$. 由**定理 6.1 (紧 $=$ 序列紧)**, $K$ 紧故 $\left(\boldsymbol{x}_n\right)$ 有收敛子列 $\boldsymbol{x}_{n_j}\to\boldsymbol{x}\in{K}$. 此时 $\left\|\boldsymbol{y}_{n_j}\right\|\le\left\|\boldsymbol{y}_{n_j}-\boldsymbol{x}_{n_j}\right\|+\left\|\boldsymbol{x}_{n_j}-\boldsymbol{x}\right\|+\left\|\boldsymbol{x}\right\|$ 有界, 故 $\boldsymbol{y}_{n_j}$ 落在某个闭球内; 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 该闭球闭且有界故紧, 再由**定理 6.1 (紧 $=$ 序列紧)** 抽出子列 $\boldsymbol{y}_{n_{j_k}}\to\boldsymbol{y}$. 因 $F$ 闭, 由**定义 3.21 (闭集)** $\boldsymbol{y}\in{F}$. 取极限得

$$
\left\|\boldsymbol{x}-\boldsymbol{y}\right\|=\lim_{k\to\infty}\left\|\boldsymbol{x}_{n_{j_k}}-\boldsymbol{y}_{n_{j_k}}\right\|=d\left(K,F\right).
$$

即距离在 $\boldsymbol{x}\in{K}$, $\boldsymbol{y}\in{F}$ 处取得. $\blacksquare$

(2) 令 $E=l^\infty$, 范数 $\left\|a\right\|=\sup_n\left|a_n\right|$. 取紧集 $K=\left\{0\right\}$ 与闭集 $F=\left\{y_n=\left(1+2^{-n}\right)e_n:n\ge0\right\}$. 先验证 $F$ 闭: 对 $n\neq{m}$,

$$
\left\|y_n-y_m\right\|=\max\left(1+2^{-n},1+2^{-m}\right)\ge1,
$$

故 $\left(y_n\right)$ 不是**定义 6.37 (柯西列)**, 其中任何子列都不收敛; 度量空间中集合闭当且仅当它包含自身一切收敛序列的极限, 由**定义 3.21 (闭集)** $F$ 是闭集. 而

$$
d\left(K,F\right)=\inf_n\left\|y_n\right\|=\inf_n\left(1+2^{-n}\right)=1,
$$

且该下确界是 $n\to\infty$ 时的极限, 没有任何 $y_n$ 满足 $\left\|y_n\right\|=1$ (均严格大于 $1$). 故距离 $d\left(K,F\right)=1$ 不能在某对 $x\in{K}$, $y\in{F}$ 处取得. $\blacksquare$

## 10.3 (连续但处处不可导的函数在 $C\left[0,1\right]$ 中稠密)

证明在 $\left(C\left[0,1\right],\left\|\cdot\right\|_\infty\right)$ 中, 连续但处处不可导的函数构成稠密子集.

题集 $\S4.1$ Q3.

### 解答 10.3

对 $k\in\mathbb{N}$ 令 $D_k=\left\{f\in{C}\left[0,1\right]:\exists{x}\in\left[0,1\right],\forall{h},0<\left|h\right|\le1/k,x+h\in\left[0,1\right]\Rightarrow\left|f\left(x+h\right)-f\left(x\right)\right|\le{k}\left|h\right|\right\}$.

$D_k$ 是闭集. 设 $f_j\in{D}_k$ 一致收敛到 $f$, 对应点 $x_j$. 由**定理 6.1 (紧 $=$ 序列紧)** 取子列 $x_{j'}\to{x}$. 固定 $h$, $0<\left|h\right|\le1/k$, 当 $j'$ 大时 $x_{j'}+h\in\left[0,1\right]$, 且

$$
\left|f\left(x+h\right)-f\left(x\right)\right|=\lim_{j'}\left|f_{j'}\left(x_{j'}+h\right)-f_{j'}\left(x_{j'}\right)\right|\le{k}\left|h\right|,
$$

故 $f\in{D}_k$.

$D_k$ 无处稠密. 取 $f\in{C}\left[0,1\right]$ 与 $\varepsilon>0$, 取三角波 $w$: 连续, $w\left(0\right)=0$, 斜率在每段上为 $\pm{S}$, 相邻折点间距 $\lambda/2$, 满足 $\left\|w\right\|_\infty<\varepsilon$ 与 $S\ge4k$; 记 $g=f+w$. 对任意 $x$ 与 $\rho\le1/k$, 由折点间距为 $\lambda/2$, $x$ 的某一侧必有长为 $\lambda/4$ 的单调段, 取 $\left|h\right|=\min\left\{\rho,\lambda/4\right\}$ 沿该侧, 则 $w$ 在 $\left[x,x+h\right]$ 上单调, $\left|w\left(x+h\right)-w\left(x\right)\right|=S\left|h\right|$. 由 $f$ 在 $\left[0,1\right]$ 上一致连续, 把 $\lambda$ 取小可使 $\left|f\left(x+h\right)-f\left(x\right)\right|\le\varepsilon\left|h\right|$ 对这时的 $h$ 成立. 于是

$$
\left|g\left(x+h\right)-g\left(x\right)\right|\ge{S}\left|h\right|-\varepsilon\left|h\right|>{k}\left|h\right|,
$$

故 $g\notin{D}_k$. 又 $\left\|g-f\right\|_\infty<\varepsilon$, 故 $D_k$ 不含开球, 无处稠密.

可导处必落在某个 $D_k$: 若 $f$ 在 $x$ 可导, 取 $M>\left|f'\left(x\right)\right|$ 与 $\delta>0$ 使 $\left|f\left(x+h\right)-f\left(x\right)\right|\le{M}\left|h\right|$ 对 $\left|h\right|\le\delta$ 成立, 再取 $k$ 使 $1/k\le\delta$ 且 $k\ge{M}$, 即 $f\in{D}_k$.

由**定理 6.13 (贝尔纲定理)**, $C\left[0,1\right]$ 完备, 可数个无处稠密集之并不能覆盖它, 故 $\bigcup_kD_k$ 的余集稠密; 而由上段, 该余集中的每个函数处处不可导. $\blacksquare$

> 三个 $D_k$ 只是把"某点附近所有割线斜率不超过 $k$"这件事固定下来; 无处稠密性靠一个振幅很小, 斜率极大的三角波, 它在每个点附近都有陡割线.

## 10.4 (有界导数函数列的阿尔泽拉–阿斯科利婴儿版)

这是**定理 6.12 (阿尔泽拉-阿斯科利定理)** 的一个婴儿版本. 设 $M\ge0$, $\left(f_n\right)$ 是 $\left[0,1\right]$ 上的连续可微函数列, 满足 $\left|f_n\left(x\right)\right|+\left|f_n'\left(x\right)\right|\le{M}$ 对一切 $x\in\left[0,1\right]$. 证明存在 $\left(f_n\right)$ 的子列在 $\left[0,1\right]$ 上一致收敛.

(1) 用对角线论证证明 $\left(f_n\right)$ 有子列在 $\left[0,1\right]$ 的全体有理点处逐点收敛;

(2) 记该子列为 $\left(g_n\right)$, 用 $\varepsilon/3$ 论证证明 $\left(g_n\right)$ 在 $\left[0,1\right]$ 的每一点都逐点收敛;

(3) 记上一问中的逐点极限为 $g$, 再用 $\varepsilon/3$ 论证证明 $g$ 实际上是 $\left(g_n\right)$ 在 $\left[0,1\right]$ 上的一致极限.

题集 §4.4 Q1.

### 解答 10.4

(1) 设 $\left\{r_1,r_2,\dots\right\}$ 是 $\left[0,1\right]$ 中全体有理数. 固定 $k$, 数列 $\left(f_n\left(r_k\right)\right)_{n\ge1}$ 有界: $\left|f_n\left(r_k\right)\right|\le{M}$. 由**定理 5.2 (区间紧)**, 有界闭区间 $\left[-M,M\right]$ 紧, 再由**定理 6.1 (紧 $=$ 序列紧)**, $\left(f_n\left(r_1\right)\right)$ 有收敛子列 $\left(f_{n_i^{\left(1\right)}}\left(r_1\right)\right)$. 接着在该子列内取子列使 $\left(f_n\left(r_2\right)\right)$ 收敛; 如此归纳, 得一串嵌套子列 $\left(f_{n_i^{\left(k\right)}}\right)$ 使第 $k$ 个子列在 $r_1,\dots,r_k$ 处都收敛. 对角线子列 $g_i=f_{n_i^{\left(i\right)}}$ 是每个嵌套子列的尾部, 故在每个有理点 $r_k$ 处收敛. $\blacksquare$

(2) 固定 $x\in\left[0,1\right]$ 与 $\varepsilon>0$. 由 $\left|g_n'\left(t\right)\right|\le{M}$ 与拉格朗日中值定理, $\left|g_n\left(x\right)-g_n\left(r\right)\right|\le{M}\left|x-r\right|$. 取有理点 $r$ 使 $\left|x-r\right|<\varepsilon/\left(3M\right)$. 则

$$
\left|g_n\left(x\right)-g_m\left(x\right)\right|\le\left|g_n\left(x\right)-g_n\left(r\right)\right|+\left|g_n\left(r\right)-g_m\left(r\right)\right|+\left|g_m\left(r\right)-g_m\left(x\right)\right|.
$$

由有理点处收敛, $\left(g_n\left(r\right)\right)$ 是**定义 6.37 (柯西列)**, 对充分大的 $n,m$ 中间项 $<\varepsilon/3$; 两端各 $<\varepsilon/3$. 故 $\left|g_n\left(x\right)-g_m\left(x\right)\right|<\varepsilon$, 即 $\left(g_n\left(x\right)\right)$ 是柯西列. 由**定义 6.39 (完备化)** (即 $\mathbb{R}$ 完备), 逐点极限 $g\left(x\right)$ 存在. $\blacksquare$

(3) 由**定理 5.2 (区间紧)** 与**定理 6.1 (紧 $=$ 序列紧)**, $\left[0,1\right]$ 可被有限个有理点 $r^{\left(1\right)},\dots,r^{\left(L\right)}$ 的邻域覆盖, 使每个 $x$ 到某 $r^{\left(j\right)}$ 的距离 $<\varepsilon/\left(3M\right)$. 对这有限个有理点, 由收敛性可取公共的 $N$, 使 $n\ge{N}$ 时 $\left|g_n\left(r^{\left(j\right)}\right)-g\left(r^{\left(j\right)}\right)\right|<\varepsilon/3$ 对一切 $j$ 成立. 又由 $\left|g_n'\right|\le{M}$ 取极限得 $\left|g\left(x\right)-g\left(r^{\left(j\right)}\right)\right|\le{M}\left|x-r^{\left(j\right)}\right|<\varepsilon/3$. 于是对任意 $x$,

$$
\left|g_n\left(x\right)-g\left(x\right)\right|\le\left|g_n\left(x\right)-g_n\left(r^{\left(j\right)}\right)\right|+\left|g_n\left(r^{\left(j\right)}\right)-g\left(r^{\left(j\right)}\right)\right|+\left|g\left(r^{\left(j\right)}\right)-g\left(x\right)\right|<\varepsilon.
$$

由**定义 6.41 (一致收敛与一致度量)**, $g_n$ 一致收敛到 $g$. $\blacksquare$

## 10.5 (点态收敛的连续函数列的极限不可能处处不连续)

设 $f_n:\left[0,1\right]\to\mathbb{R}$ 连续, 且 $f_n$ 逐点收敛到 $f$. 证明 $f$ 不可能处处不连续; 更精确地, $f$ 的连续点集在 $\left[0,1\right]$ 中稠密.

题集 $\S4.4$ Q3.

### 解答 10.5

对 $\varepsilon>0$ 与 $n\in\mathbb{N}$ 令 $F_{n,\varepsilon}=\left\{x\in\left[0,1\right]:\forall{p}\ge{n},\left|f_p\left(x\right)-f_n\left(x\right)\right|\le\varepsilon\right\}$. 每个 $F_{n,\varepsilon}$ 是闭集: 它是可数个 $\left|f_p-f_n\right|$ 的零水平集的交, 而 $f_p-f_n$ 连续, 由**定义 3.21 (闭集)** $\left\{x:\left|f_p\left(x\right)-f_n\left(x\right)\right|\le\varepsilon\right\}$ 闭.

$F_{n,\varepsilon}$ 覆盖 $\left[0,1\right]$: 固定 $x$, 数列 $f_p\left(x\right)$ 收敛故柯西, 取 $n$ 使 $p,q\ge{n}$ 时 $\left|f_p\left(x\right)-f_q\left(x\right)\right|\le\varepsilon$, 特别取 $q=n$ 得 $x\in{F}_{n,\varepsilon}$.

于是 $\left[0,1\right]=\bigcup_{n}F_{n,\varepsilon}$ 是闭集的可数并. 由**定理 6.13 (贝尔纲定理)**, 在完备空间 $\left[0,1\right]$ 中可数个无处稠密集之并不能覆盖全空间, 故某个 $F_{N,\varepsilon}$ 不是无处稠密的, 即它含一个非退化区间.

对任意子区间 $J\subset\left[0,1\right]$ 用同一论证 (以 $J$ 代 $\left[0,1\right]$, $J$ 完备), 得: 每个 $J$ 内都有某个 $F_{N,\varepsilon}$ 的内点. 于是

$$
\Omega_\varepsilon=\bigcup_{n}\operatorname{int}\left(F_{n,\varepsilon}\right)
$$

在每个 $J$ 中非空, 故 $\Omega_\varepsilon$ 稠密; 它是开集, 故稠密开.

在 $\Omega_\varepsilon$ 上 $f$ 连续: 若 $x_0\in\operatorname{int}\left(F_{N,\varepsilon}\right)$, 取邻域 $V\subset{F}_{N,\varepsilon}$. 则对 $x\in{V}$ 与一切 $p\ge{N}$ 有 $\left|f_p\left(x\right)-f_N\left(x\right)\right|\le\varepsilon$; 令 $p\to\infty$ 得 $\left|f\left(x\right)-f_N\left(x\right)\right|\le\varepsilon$. 故 $f$ 在 $V$ 上是连续函数列 $f_N$ 的一致极限, 由一致极限的连续性 (题集 $\S4.2$ Q5) $f$ 在 $V$ 上连续. 特别 $x_0$ 是连续点.

最后令 $\Omega=\bigcap_{m}\Omega_{1/m}$, 它是稠密 $G_\delta$ (可数个稠密开集之交). 由上一段, $f$ 在 $\Omega$ 上每点连续. 稠密子集 $\Omega$ 中每点都是连续点, 故 $f$ 的连续点集稠密, 它不可能处处不连续. $\blacksquare$

> 关键是"$\Omega_\varepsilon$ 在每个子区间里都有点", 这是对每个 $J$ 单独用一次贝尔纲得到的, 这样稠密性才不依赖于整体.

## 10.6 (对角线的第一步: 有界数列取收敛子列)

第一部分是对角线论证. 设 $f_n\left(m\right)$ 是正整数上的函数列, 一致有界, 即存在常数 $C$ 使对一切 $n,m$ 有 $\left|f_n\left(m\right)\right|\le{C}$. 证明序列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 有收敛子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$.

题集 §4.2 Q1.

### 解答 10.6

数列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 含于有界闭区间 $\left[-C,C\right]$. 由**定理 5.2 (区间紧)** 平移即知 $\left[-C,C\right]$ 是紧集; 由**定理 6.1 (紧 $=$ 序列紧)**, 紧度量空间中每个序列都有收敛子列. 故存在子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$ 收敛. $\blacksquare$

## 10.7 (对角线子列的归纳构造)

沿用习题 10.6 的记号. 证明可以依次构造子列 $\left(f_{n_i^{\left(k\right)}}\left(m\right)\right)_{i\ge0}$, 使 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛.

题集 §4.2 Q2.

### 解答 10.7

归纳构造. $k=1$ 时由**习题 10.6**已得子列 $\left(f_{n_i^{\left(1\right)}}\right)$, 使 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)$ 收敛. 设已构造第 $k$ 个子列 $\left(f_{n_i^{\left(k\right)}}\right)$. 数列 $\left(f_{n_i^{\left(k\right)}}\left(k+1\right)\right)_{i\ge0}$ 仍含于 $\left[-C,C\right]$, 由**定理 5.2 (区间紧)** 与**定理 6.1 (紧 $=$ 序列紧)**, 有收敛子列, 记为 $\left(f_{n_i^{\left(k+1\right)}}\left(k+1\right)\right)_{i\ge0}$, 其中 $\left(n_i^{\left(k+1\right)}\right)$ 是 $\left(n_i^{\left(k\right)}\right)$ 的子列. 于是 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且由构造 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 收敛. 归纳完成. $\blacksquare$

## 10.8 (对角子列使各点收敛)

证明存在子列 $\left(f_{n_i}\left(m\right)\right)$, 使对每个固定的 $m$, $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛. 可考虑序列 $n_k=n_k^{\left(k\right)}$.

题集 §4.2 Q3.

### 解答 10.8

取对角子列 $n_i=n_i^{\left(i\right)}$. 固定 $m$. 对一切 $i\ge{m}$, 由嵌套关系, $\left(n_j^{\left(i\right)}\right)_{j\ge1}$ 是 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 的子列, 特别地 $n_i=n_i^{\left(i\right)}$ 本身是第 $m$ 个子列 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 中序号充分大的一项. 而由构造, $\left(f_{n_j^{\left(m\right)}}\left(m\right)\right)_{j\ge1}$ 收敛. 收敛序列的尾部仍收敛, 故子列 $\left(f_{n_i}\left(m\right)\right)_{i\ge{m}}$ 收敛, 即 $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 收敛. 对一切 $m$ 同时成立. $\blacksquare$

## 10.9 (上确界度量下的柯西列逐点收敛)

第二部分是 $\varepsilon/3$ 论证. 设 $C\left[a,b\right]$ 是 $\left[a,b\right]$ 上连续实值函数空间, 装备**定义 6.43 (上确界度量)** $d\left(f,g\right)=\sup_{x\in\left[a,b\right]}\left|f\left(x\right)-g\left(x\right)\right|$. 设 $\left(f_n\right)$ 是该度量下的**定义 6.37 (柯西列)**. 证明对每个 $x\in\left[a,b\right]$, $\left(f_n\left(x\right)\right)$ 收敛到某个 $f\left(x\right)\in\mathbb{R}$.

题集 §4.2 Q4.

### 解答 10.9

由 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon>0$ 存在 $N$, 使 $n,m\ge{N}$ 时

$$
\sup_{x\in\left[a,b\right]}\left|f_n\left(x\right)-f_m\left(x\right)\right|<\varepsilon.
$$

固定 $x\in\left[a,b\right]$, 则 $\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\sup<\varepsilon$, 故 $\left(f_n\left(x\right)\right)$ 是 $\mathbb{R}$ 中的**定义 6.37 (柯西列)**. 由**定义 6.39 (完备化)**, $\mathbb{R}$ 是**定义 6.38 (完备度量空间)**, 故 $\left(f_n\left(x\right)\right)$ 收敛. 记其极限为 $f\left(x\right)$. 逐点极限 $f$ 由此定义. $\blacksquare$

## 10.10 (一致极限的连续性 ($\varepsilon/3$ 论证))

设 $f$ 是连续函数列 $\left(f_n\right)$ 的极限. 固定 $x\in\left[a,b\right]$ 与 $\varepsilon>0$. 证明:

(1) 可选取 $n$ 使 $\left\|f_n-f\right\|_\infty<\varepsilon/3$;

(2) 可选取 $\delta>0$, 使 $\left|x-y\right|<\delta$ 蕴含 $\left|f_n\left(x\right)-f_n\left(y\right)\right|<\varepsilon/3$;

(3) $f$ 连续.

题集 §4.2 Q5.

### 解答 10.10

(1) 由**习题 10.9**, $\left(f_n\right)$ 逐点收敛到 $f$. 又 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon>0$ 存在 $N$, 使 $n,m\ge{N}$ 时 $\sup_x\left|f_n\left(x\right)-f_m\left(x\right)\right|<\varepsilon/3$. 固定 $n\ge{N}$, 令 $m\to\infty$, 由**习题 10.9** $f_m\left(x\right)\to{f}\left(x\right)$, 故

$$
\left|f_n\left(x\right)-f\left(x\right)\right|=\lim_{m\to\infty}\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\varepsilon/3.
$$

对 $x$ 取上确界得 $\left\|f_n-f\right\|_\infty\le\varepsilon/3<\varepsilon/3$ (取严格不等号即可). 故存在 $n$ 使 $\left\|f_n-f\right\|_\infty<\varepsilon/3$. $\blacksquare$

(2) 固定该 $n$, 由 $f_n$ 连续, 存在 $\delta>0$, 使 $y\in\left[a,b\right]$ 且 $\left|x-y\right|<\delta$ 时 $\left|f_n\left(x\right)-f_n\left(y\right)\right|<\varepsilon/3$. $\blacksquare$

(3) 对满足 $\left|x-y\right|<\delta$ 的 $y$,

$$
\left|f\left(x\right)-f\left(y\right)\right|\le\left|f\left(x\right)-f_n\left(x\right)\right|+\left|f_n\left(x\right)-f_n\left(y\right)\right|+\left|f_n\left(y\right)-f\left(y\right)\right|<\frac{\varepsilon}{3}+\frac{\varepsilon}{3}+\frac{\varepsilon}{3}=\varepsilon.
$$

这正是**定理 6.7 (连续函数的一致极限连续)** 的 $\varepsilon/3$ 论证, 故 $f$ 在 $x$ 连续. $x$ 任意, $f$ 在 $\left[a,b\right]$ 上连续. $\blacksquare$

## 10.11 ($C\left[a,b\right]$ 在上确界度量下完备)

证明 $f_n\to{f}$ 在 $C\left[a,b\right]$ 中, 即依**定义 6.43 (上确界度量)** 收敛; 由此得出 $C\left[a,b\right]$ 是完备的.

题集 §4.2 Q6.

### 解答 10.11

由**习题 10.9**, $\left(f_n\right)$ 逐点收敛到 $f$. 由 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon>0$ 存在 $N$, 使 $n,m\ge{N}$ 时 $\sup_x\left|f_n\left(x\right)-f_m\left(x\right)\right|<\varepsilon$. 固定 $n\ge{N}$ 与任意 $x$, 令 $m\to\infty$, 由**习题 10.9** $f_m\left(x\right)\to{f}\left(x\right)$, 故

$$
\left|f_n\left(x\right)-f\left(x\right)\right|=\lim_{m\to\infty}\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\varepsilon.
$$

对 $x$ 取上确界, 得 $\left\|f_n-f\right\|_\infty\le\varepsilon$ 对一切 $n\ge{N}$ 成立. 由**定义 6.41 (一致收敛与一致度量)** 与**定义 6.43 (上确界度量)**, $f_n\to{f}$ 一致收敛, 即在 $C\left[a,b\right]$ 中收敛. $\blacksquare$

由**习题 10.10**, $f$ 连续, 故 $f\in{C}\left[a,b\right]$. 于是 $C\left[a,b\right]$ 中每个**定义 6.37 (柯西列)** 都收敛到 $C\left[a,b\right]$ 中的元素, 由**定义 6.38 (完备度量空间)**, $C\left[a,b\right]$ 完备, 即**定理 6.8 ($C\left(X,Y\right)$ 完备)** 的特例. $\blacksquare$

## 10.12 (豪斯多夫空间中极限唯一, 度量空间中聚点即子列极限)

序列与度量空间. 证明:

(1) **定义 3.10 (豪斯多夫空间)** 中序列的极限唯一;

(2) 在**定义 6.35 (度量空间)** 中, 序列的聚点就是其子列极限;

(3) 若空间不是度量空间, 会发生什么?

题集 §4.5 C1.

### 解答 10.12

(1) 设 $x_n\to{x}$ 且 $x_n\to{y}$, $x\neq{y}$. 由**定义 3.10 (豪斯多夫空间)**, 存在不相交开集 $U,V$ 使 $x\in{U}$, $y\in{V}$. 由**定义 3.25 (邻域与极限)**, 对充分大的 $n$ 有 $x_n\in{U}$, 又对充分大的 $n$ 有 $x_n\in{V}$, 与 $U\cap{V}=\emptyset$ 矛盾. 故 $x=y$. $\blacksquare$

(2) 在**定义 6.35 (度量空间)** 中, 设 $x$ 是 $\left(x_n\right)$ 的聚点, 即 $x$ 的每个邻域含序列中无穷多项. 归纳地选 $n_k$ 严格递增, 使 $x_{n_k}\in{B}\left(x,1/k\right)$; 由**定义 6.36 (开球)**, $d\left(x_{n_k},x\right)<1/k\to0$, 故 $x_{n_k}\to{x}$. 反之, 若 $x_{n_k}\to{x}$, 由**定义 3.25 (邻域与极限)**, $x$ 的每个邻域含无穷多项, $x$ 是聚点. $\blacksquare$

(3) 若不是度量空间: 豪斯多夫性仍保证极限唯一, 但聚点一般不再是子列极限, 因为没有可数邻域基把"每个邻域含无穷多项"逐步收窄成一个子列; 此时需要用网来刻画聚点. $\blacksquare$

## 10.13 (恰有一个聚点蕴含收敛)

恰一个聚点. 设 $f:\mathbb{R}^n\to\mathbb{R}^n$ 连续, 且序列 $\left(f^n\left(\boldsymbol{x}_0\right)\right)$ 恰有一个聚点. 证明该序列收敛.

题集 §4.5 C7.

### 解答 10.13

记 $\boldsymbol{x}_n=f^n\left(\boldsymbol{x}_0\right)$, 设唯一聚点为 $\boldsymbol{z}$. 取子列 $\boldsymbol{x}_{n_j}\to\boldsymbol{z}$. 由 $f$ 连续, $\boldsymbol{x}_{n_j+1}=f\left(\boldsymbol{x}_{n_j}\right)\to{f}\left(\boldsymbol{z}\right)$. 而 $\left(\boldsymbol{x}_{n_j+1}\right)$ 是 $\left(\boldsymbol{x}_n\right)$ 的子列, 其极限 $f\left(\boldsymbol{z}\right)$ 必为聚点, 由唯一性 $f\left(\boldsymbol{z}\right)=\boldsymbol{z}$.

反设 $\left(\boldsymbol{x}_n\right)$ 不收敛到 $\boldsymbol{z}$. 则存在 $\varepsilon>0$ 与无穷多个 $n$ 使 $\left\|\boldsymbol{x}_n-\boldsymbol{z}\right\|\ge\varepsilon$. 从每个 $n_j$ 出发, 若其后轨道始终在 $B\left(\boldsymbol{z},\varepsilon\right)$ 内, 则尾部落在紧闭球中, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 与**定理 6.1 (紧 $=$ 序列紧)**, 该尾部的任何聚点都是 $\boldsymbol{z}$, 矛盾于不收敛. 故从每个 $n_j$ 出发, 存在第一个 $m_j>{}n_j$ 使 $\left\|\boldsymbol{x}_{m_j}-\boldsymbol{z}\right\|=\varepsilon$. 点 $\boldsymbol{x}_{m_j}$ 都落在紧球面 $\partial{B}\left(\boldsymbol{z},\varepsilon\right)$ 上, 抽子列 $\boldsymbol{x}_{m_{j_k}}\to\boldsymbol{w}$, $\left\|\boldsymbol{w}-\boldsymbol{z}\right\|=\varepsilon$. 则 $\boldsymbol{w}$ 是 $\left(\boldsymbol{x}_n\right)$ 的聚点且 $\boldsymbol{w}\neq\boldsymbol{z}$, 矛盾. 故 $\left(\boldsymbol{x}_n\right)\to\boldsymbol{z}$. $\blacksquare$

## 10.14 (紧集与闭集之和闭, 两闭集之和未必闭)

闭集之和. 设 $E=\mathbb{R}^n$, $A,B\subset{E}$.

(1) 证明: 若 $A$ 紧而 $B$ 闭, 则 $A+B=\left\{\boldsymbol{a}+\boldsymbol{b}:\boldsymbol{a}\in{A},\boldsymbol{b}\in{B}\right\}$ 闭;

(2) 证明: 若 $A,B$ 都闭, $A+B$ 不必闭.

题集 §4.5 C10.

### 解答 10.14

(1) 取序列 $a_n+b_n\in{A}+B$ 收敛到 $y$. 由**定理 6.1 (紧 $=$ 序列紧)**, $A$ 紧, 故 $\left(a_n\right)$ 有子列 $a_{n_j}\to{a}\in{A}$. 则 $b_{n_j}=\left(a_{n_j}+b_{n_j}\right)-a_{n_j}\to{y}-a$. 因 $B$ 闭, 由**定义 3.21 (闭集)**, $y-a\in{B}$. 故 $y=a+\left(y-a\right)\in{A}+B$. $A+B$ 含一切收敛序列的极限, 故闭. $\blacksquare$

(2) 反例: 取 $A=\left\{\left(x,0\right):x\in\mathbb{R}\right\}$, $B=\left\{\left(x,1/x\right):x>0\right\}$. $A$ 与 $B$ 都闭. 但

$$
A+B=\left\{\left(x+t,1/t\right):t>0\right\}=\left\{\left(u,v\right):v>0\right\},
$$

即开的上半平面, 由**定义 3.21 (闭集)** 它不是闭集. $\blacksquare$

## 10.15 (度量空间的完备化)

(完备化) 设 $\left(M,d\right)$ 不完备. 考虑全体柯西列 $\left\{x_n\right\}$, 等价关系 $\left\{x_n\right\}\sim\left\{y_n\right\}$ 当且仅当 $\lim_{n\to\infty}d\left(x_n,y_n\right)=0$. 令 $\widehat{M}$ 为等价类集合, 距离 $\widehat{d}\left(\left[x\right],\left[y\right]\right)=\lim_{n\to\infty}d\left(x_n,y_n\right)$. 证明 $\widehat{M}$ 完备, 且 $M$ 在嵌入 $x\mapsto\left(x,x,\dots\right)$ 下在 $\widehat{M}$ 中稠密.

题集 §5.1 C5.

### 解答 10.15

$\widehat{d}$ 良定义: 若 $\left[x_n\right]=\left[x_n'\right]$, $\left[y_n\right]=\left[y_n'\right]$, 则 $d\left(x_n,y_n\right)-d\left(x_n',y_n'\right)$ 由三角不等式趋于 $0$, 极限与代表元无关. 由**定义 6.35 (度量空间)**, $\widehat{d}$ 满足四公理. 这里等价关系中出现的 $\left\{x_n\right\}$ 是**定义 6.37 (柯西列)** 意义下的柯西列.

完备: 设 $\left\{\xi_k\right\}$ 是 $\widehat{M}$ 中柯西列, $\xi_k=\left[\left(x_n^{\left(k\right)}\right)_n\right]$. 对每个 $k$, 取代表列使其前 $k$ 项稳定逼近; 对角化取 $z_k=x_k^{\left(k\right)}$. 由柯西性与三角不等式, $\left(z_k\right)$ 是 $M$ 中柯西列, 记其等价类为 $\xi$. 则 $\xi_k\to\xi$. 由**定义 6.38 (完备度量空间)**, $\widehat{M}$ 完备. $\blacksquare$

稠密嵌入: 映射 $i:M\to\widehat{M}$, $i\left(x\right)=\left[\left(x,x,\dots\right)\right]$. 任意 $\xi=\left[\left(x_n\right)\right]\in\widehat{M}$, $x_n\to\xi$ 在 $\widehat{M}$ 中, 而 $x_n\in{i}\left(M\right)$. 故 $i\left(M\right)$ 的闭包为全空间, 由**定义 3.32 (稠密)** $M$ 在 $\widehat{M}$ 中稠密. 由**定义 6.39 (完备化)**, 这就是 $M$ 的完备化. $\blacksquare$

## 10.16 (巴拿赫空间等价于绝对收敛级数皆收敛)

(巴拿赫空间) 设 $E$ 是赋范线性空间.

(1) 证明: $E$ 中每个绝对收敛级数都收敛, 当且仅当 $E$ 是完备的 (即巴拿赫空间);

(2) 举例说明若 $E$ 不完备, 存在绝对收敛但不收敛的级数.

题集 §4.4 Q4; 与 2024 卷 A 题二, 原 11.3, 11.5 同题, 已合于此.

### 解答 10.16

(1) ($\Rightarrow$) 设 $E$ 中每个绝对收敛级数都收敛. 取**定义 6.37 (柯西列)** $\left(x_n\right)$. 由柯西性, 可选子列 $x_{n_k}$ 使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$. 则

$$
\sum_{k=1}^{\infty}\left\|x_{n_{k+1}}-x_{n_k}\right\|<\sum_{k=1}^{\infty}2^{-k}<\infty,
$$

即 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛. 其部分和即 $x_{n_{k+1}}-x_{n_1}$, 故子列 $x_{n_k}$ 收敛. 由柯西列含收敛子列则全列收敛, 全列 $x_n$ 收敛. 故 $E$ 完备. $\blacksquare$

($\Leftarrow$) 设 $E$ 完备, $\sum_n\left\|x_n\right\|<\infty$. 部分和 $S_N=\sum_{n=1}^Nx_n$ 满足对 $M>{}N$,

$$
\left\|S_M-S_N\right\|=\left\|\sum_{n=N+1}^Mx_n\right\|\le\sum_{n=N+1}^M\left\|x_n\right\|\to0,
$$

故 $\left(S_N\right)$ 是**定义 6.37 (柯西列)**. 由**定义 6.38 (完备度量空间)**, $S_N$ 收敛, 即级数收敛. $\blacksquare$

(2) 取 $E=C\left(\left[0,1\right]\right)$ 装备 $L^1$ 范数 $\left\|f\right\|_1=\int_0^1\left|f\left(t\right)\right|\,\mathrm{d}t$, 它不完备. 构造折线函数列 $f_n$, 使 $f_n$ 从 $0$ 线性升到 $1$ 的区间长度为 $1/n$. 则 $\sum_n\left\|f_n\right\|_1<\infty$ (每段面积 $\le1/n$), 但 $\sum_nf_n$ 在 $\left(0,1\right)$ 上无界, 不作为连续函数存在. 故绝对收敛但不收敛于 $E$ 中. $\blacksquare$
