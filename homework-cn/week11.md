# week11

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{X}$ 是开的当且仅当 $U\in{T}$. 我们要求:
> 
> (1) $\emptyset,X\in{T}$;
> 
> (2) 若 $U,V\in{T}$, 则 $U\cap{V}\in{T}$;
> 
> (3) 若 $A\subset{T}$, 则 $\bigcup{A}\in{T}$. (教材 $\S3$, p12)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.23 (同胚)**
> 
> 空间之间的双射 $f:X\to{Y}$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 §3, p15)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $x,y\in{K}$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定理 6.8 ($C\left(X,Y\right)$ 完备)**
> 
> $Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.14 (递增闭集族)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 若为可数个闭集之并 $X=\bigcup_nF_n$, 则至少一个 $F_n$ 含非空开集. (教材 §6)

> **定理 6.16 (巴拿赫不动点定理)**
> 
> 非空完备度量空间上的压缩映射有唯一不动点. (题集 §4.3 Q1)

> **定义 6.19 (压缩映射)**
> 
> 称 $f:X\to{X}$ 是压缩的, 若存在 $0<{}k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. (题集 §4.3 Q1)

> **定义 6.21 (巴拿赫空间)**
> 
> 完备的赋范线性空间. (题集 §5)

> **定义 6.22 (绝对收敛级数)**
> 
> 级数 $\sum_nx_n$ 绝对收敛, 若 $\sum_n\left\|x_n\right\|<\infty$. (题集 §4.4)

> **定义 6.24 (拓扑向量空间)**
> 
> 向量空间装备使加法 $E\times{E}\to{E}$ 与数乘 $\mathbb{K}\times{E}\to{E}$ 都连续的拓扑. (题集 §5 Q6)

> **定义 6.25 (半范数)**
> 
> 满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 §5 Q6)

> **定义 6.26 (局部凸空间)**
> 
> 拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 §5 Q6)

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

> **定义 6.36 (开球)**
> 
> 开球 $B\left(x,r\right)=\left\{y\in{X}:d\left(x,y\right)<{}r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.49 (等距映射)**
> 
> 满足 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)$ 的映射 $f:X\to{Y}$. (题集 §3.4)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; "拓扑学"(原书第2版) $\S29$)

## 11.1 (贝尔纲定理的局部紧版本)

(贝尔纲, 局部紧版本) 证明: 在局部紧豪斯多夫空间中, 可数个稠密开集之交仍稠密.

### 解答 11.1

设 $\left\{U_n\right\}_{n=1}^{\infty}$ 是稠密开集, $V_0$ 是任意非空开集. 归纳构造非空开集 $V_n$: 由 $U_1$ 稠密, $V_0\cap{U}_1\neq\emptyset$. 取非空开 $V_1$ 使 $\overline{V_1}\subset{V}_0\cap{U}_1$ 且 $\overline{V_1}$ 紧 (由**定义 7.4 (局部紧空间)**, 局部紧豪斯多夫提供闭紧邻域基, 可在 $V_0\cap{U}_1$ 内取闭紧邻域). 归纳地, 由 $U_n$ 稠密, $V_{n-1}\cap{U}_n\neq\emptyset$, 取非空开 $V_n$ 使 $\overline{V_n}\subset{V}_{n-1}\cap{U}_n$ 且 $\overline{V_n}$ 紧.

于是 $\left\{\overline{V_n}\right\}$ 是非空紧集套. 由紧集的有限交性质 (紧空间中具有有限交性质的闭集族之交非空), 存在 $x\in\bigcap_n\overline{V_n}$. 由 $\overline{V_n}\subset{U}_n$ 与 $\overline{V_n}\subset{V}_0$, 有 $x\in{V}_0\cap\bigcap_nU_n$. 故 $V_0$ 与 $\bigcap_nU_n$ 相交. $V_0$ 任意, 由**定义 3.32 (稠密)**, $\bigcap_nU_n$ 稠密. 这正是**定理 6.13 (贝尔纲定理)** 的局部紧版本. $\blacksquare$

## 11.2 (可数个无处稠密集之并可以是稠密集)

(不可数个稠密开集不必相交) 证明: $\mathbb{Q}$ 是可数个无处稠密集之并. 由此说明**定理 6.13 (贝尔纲定理)** 中可数性不能放宽到不可数.

### 解答 11.2

$\mathbb{Q}=\bigcup_{q\in\mathbb{Q}}\left\{q\right\}$, 每个单点集 $\left\{q\right\}$ 是闭集且内部为空 ($\mathbb{R}$ 无孤立点, 任何开区间含非 $q$ 的点), 故无处稠密. 这是可数个 ($\mathbb{Q}$ 可数) 无处稠密集之并等于 $\mathbb{R}$ 的稠密子集.

另一方面, 由**定理 6.13 (贝尔纲定理)**, $\mathbb{R}$ (完备度量空间) 不能写成可数个无处稠密闭集之并. 但 $\mathbb{R}=\mathbb{Q}\cup\left(\mathbb{R}\setminus\mathbb{Q}\right)$ 中 $\mathbb{Q}$ 是可数个无处稠密集之并, 说明可数个无处稠密集之并可以是稠密的 ($\mathbb{Q}$ 在 $\mathbb{R}$ 中稠密), 但不能等于全空间 $\mathbb{R}$. 若把可数放宽到不可数, 则 $\mathbb{R}=\bigcup_{x\in\mathbb{R}}\left\{x\right\}$ 是不可数个无处稠密集之并, 与**定理 6.14 (递增闭集族)** 矛盾, 故可数性不能去掉. $\blacksquare$

## 11.3 (绝对收敛级数皆收敛蕴含完备 (重述))

设 $E$ 是赋范线性空间. 证明: 若 $E$ 中每个绝对收敛级数都收敛, 则 $E$ 完备.

### 解答 11.3

这是习题 10.16 第 (1) 小题中 ($\Rightarrow$) 方向的重述. 设**定义 6.37 (柯西列)** $\left(x_n\right)$, 选子列 $\left(x_{n_k}\right)$ 使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$. 则 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛, 部分和即 $x_{n_{k+1}}-x_{n_1}$, 故子列收敛. 由柯西列含收敛子列则全列收敛, 全列收敛. 故 $E$ 完备. $\blacksquare$

## 11.4 (勒贝格: 无处稠密的常值集与非常数连续函数)

(勒贝格非常数连续函数) 设 $\lambda$ 是 $\left[0,1\right]$ 上勒贝格测度, $C\left(\left[0,1\right]\right)$ 装备上确界范数. 设

$$
A_n=\left\{f\in{C}\left(\left[0,1\right]\right):\exists\;a<{}b\;\text{使}\;\lambda\left(\left[a,b\right]\right)\ge\frac1n\;\text{且}\;f\;\text{在}\left[a,b\right]\;\text{上为常数}\right\}.
$$

证明 $A_n$ 无处稠密, 由此得出存在连续函数在任何正测度区间上都不常数.

### 解答 11.4

$A_n$ 闭. 若 $f_k\in{A}_n$ 且 $f_k\to{f}$ 一致, 则每个 $f_k$ 在某区间 $\left[a_k,b_k\right]$ (长度 $\ge1/n$) 上为常数. 区间端点抽子列收敛到 $\left[a,b\right]$, $b-a\ge1/n$, 由一致收敛 $f$ 在 $\left[a,b\right]$ 上为常数. 故 $A_n$ 闭.

$A_n$ 无内部. 任给 $f$ 与 $\varepsilon>0$, 用锯齿形连续函数 $g$, 在长度 $\ge1/n$ 的区间上振幅 $>\varepsilon/2$, 且 $\left\|g-f\right\|_\infty<\varepsilon$. 则 $g\notin{A}_n$, 而 $g\in{B}\left(f,\varepsilon\right)$. 由**定义 3.21 (闭集)**, $A_n$ 的内部为空.

由**定理 6.13 (贝尔纲定理)**, $C\left(\left[0,1\right]\right)$ 完备 (即**定理 6.8 ($C\left(X,Y\right)$ 完备)**) 不能写成可数个无处稠密闭集之并, 故 $\bigcup_nA_n\neq{C}\left(\left[0,1\right]\right)$. 取 $f\notin\bigcup_nA_n$, 则 $f$ 在任何长度 $\ge1/n$ 的区间上不常数对一切 $n$ 成立, 即在任何正测度区间 (长度 $>0$, 从而 $\ge1/n$ 对某个 $n$) 上不常数. 由**定义 3.32 (稠密)** 的反面, 这样的 $f$ 存在. $\blacksquare$

## 11.5 (完备等价于每个绝对收敛级数收敛)

设 $E$ 是赋范线性空间. 证明: $E$ 是完备度量空间当且仅当 $E$ 中每个绝对收敛级数都收敛.

### 解答 11.5

($\Rightarrow$) 设 $E$ 完备, $\sum_n\left\|x_n\right\|<\infty$. 部分和 $S_N=\sum_{n=1}^Nx_n$ 对 $M>{}N$ 满足

$$
\left\|S_M-S_N\right\|\le\sum_{n=N+1}^M\left\|x_n\right\|\to0,
$$

故 $\left(S_N\right)$ 是**定义 6.37 (柯西列)**; 由**定义 6.38 (完备度量空间)** $S_N$ 收敛.

($\Leftarrow$) 若每个绝对收敛级数收敛, 取**定义 6.37 (柯西列)** $\left(x_n\right)$, 选子列使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$, 则 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛, 子列收敛. 由柯西列含收敛子列则全列收敛, 全列收敛. 故 $E$ 完备.

即**定义 6.22 (绝对收敛级数)** 收敛性等价于**定义 6.38 (完备度量空间)**. $\blacksquare$

## 11.6 (2025 卷 B 题三: 复合函数子空间 $V\left(f\right)$ 的闭性与稠密性)

(2025 年卷 B 题目三, 20 分). 记 $C\left(\left[0,1\right],\mathbb{R}\right)$ 为 $\left[0,1\right]$ 上连续实值函数集合, 赋予通常的一致范数. 对 $f\in{C}\left(\left[0,1\right],\mathbb{R}\right)$, 定义 $V\left(f\right)=\left\{g\circ{f}:g\in{C}\left(\mathbb{R},\mathbb{R}\right)\right\}$.

(1) 证明 $V\left(f\right)$ 是 $C\left(\left[0,1\right],\mathbb{R}\right)$ 的闭线性子空间.

(2) 证明若 $f$ 单调, 则 $V\left(f\right)=C\left(\left[0,1\right],\mathbb{R}\right)$.

(3) 证明若 $f$ 不单调, 则 $V\left(f\right)$ 不是 $C\left(\left[0,1\right],\mathbb{R}\right)$ 的稠密子集.

### 解答 11.6

(1) 线性: $\left(g_1+g_2\right)\circ{f}=g_1\circ{f}+g_2\circ{f}$, $\left(\lambda{g}_1\right)\circ{f}=\lambda\left(g_1\circ{f}\right)$. 闭: 若 $g_n\circ{f}\to{h}$ 一致, 则 $h$ 在 $f$ 的每个纤维 $f^{-1}\left(t\right)$ 上为常数. 由此可定义 $g\left(t\right)=h\left(x\right)$ ($x\in{f}^{-1}\left(t\right)$). $g$ 连续 (由**定义 3.22 (连续映射)** 与 $f$ 连续), 故 $h=g\circ{f}\in{V}\left(f\right)$. 由**定义 3.21 (闭集)**, $V\left(f\right)$ 闭.

(2) 若 $f$ 单调, $f$ 的纤维至多单点. $f\left(\left[0,1\right]\right)$ 是区间 $\left[a,b\right]$. 任给 $h\in{C}\left(\left[0,1\right]\right)$, 定义 $g$ 在 $\left[a,b\right]$ 上为 $g\left(t\right)=h\left(f^{-1}\left(t\right)\right)$; 由单调双射 $f:\left[0,1\right]\to\left[a,b\right]$ 连续且逆连续, $g$ 连续. 由**定义 3.23 (同胚)**, 单调双射即同胚嵌入, $h=g\circ{f}$, 故 $h\in{V}\left(f\right)$.

(3) 若 $f$ 不单调, 则存在 $a<{}b<{}c$ 使 $f\left(a\right)=f\left(c\right)\neq{f}\left(b\right)$. 于是 $V\left(f\right)$ 中函数在 $a,c$ 处必取同值. 而函数 $h$ 满足 $h\left(a\right)\neq{h}\left(c\right)$ 的连续函数不在 $V\left(f\right)$ 中, 且与 $V\left(f\right)$ 保持正距离. 由**定理 6.13 (贝尔纲定理)** 与**定理 6.14 (递增闭集族)**, 完备空间中闭而无内部的子空间不稠密. $\blacksquare$

## 11.7 (等距映射的单射性, 完备性与同胚)

(等距与拓扑) 设 $\left(X,d_X\right)$, $\left(Y,d_Y\right)$ 是度量空间, $f:X\to{Y}$ 是等距映射. 证明 $f$ 是单射, 连续, 且 $f^{-1}:f\left(X\right)\to{X}$ 也是等距映射. 若 $X$ 完备, 证明 $f\left(X\right)$ 完备. 若 $f$ 是满射, 证明 $f$ 是同胚.

### 解答 11.7

单射. 由**定义 6.49 (等距映射)**, $f\left(x\right)=f\left(y\right)\Rightarrow{d}_Y\left(f\left(x\right),f\left(y\right)\right)=0=d_X\left(x,y\right)\Rightarrow{x}=y$.

连续. 对任意 $\varepsilon>0$, 取 $\delta=\varepsilon$, 由**定义 6.35 (度量空间)** 与**定义 6.49 (等距映射)**, $d_X\left(x,y\right)<\delta$ 蕴含 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)<\varepsilon$. 由**定义 6.36 (开球)** 与**定义 3.22 (连续映射)**, $f$ 连续.

$f^{-1}$ 是等距. 对 $u=f\left(x\right)$, $v=f\left(y\right)$, $d_X\left(f^{-1}\left(u\right),f^{-1}\left(v\right)\right)=d_X\left(x,y\right)=d_Y\left(u,v\right)$.

$X$ 完备蕴含 $f\left(X\right)$ 完备. 设 $\left(y_n\right)$ 是 $f\left(X\right)$ 中的**定义 6.37 (柯西列)**, $y_n=f\left(x_n\right)$. 则 $d_X\left(x_n,x_m\right)=d_Y\left(y_n,y_m\right)\to0$, $\left(x_n\right)$ 是柯西列. 由**定义 6.38 (完备度量空间)**, $x_n\to{x}\in{X}$, 故 $y_n=f\left(x_n\right)\to{f}\left(x\right)\in{f}\left(X\right)$. 由**定义 6.38 (完备度量空间)**, $f\left(X\right)$ 完备.

$f$ 满则 $f$ 是同胚. $f^{-1}$ 连续 (上面已证 $f^{-1}$ 是等距故连续), $f$ 连续, 由**定义 3.23 (同胚)**, $f$ 是同胚. $\blacksquare$

## 11.8 (可数个闭集覆盖完备空间, 其一含非空开集)

(2025 年卷 B 题目四, 20 分). 设 $X$ 为非空完备度量空间. 证明: 若 $X$ 被可数个闭集 $F_1,F_2,\dots$ 覆盖, 则至少存在一个 $F_n$ 包含非空开集.

### 解答 11.8

反证. 设每个 $F_n$ 的内部为空. 由**定义 3.18 (拓扑空间)**, 补集 $G_n=X\setminus{F}_n$ 是稠密开集 ($F_n$ 闭且无内部当且仅当 $G_n$ 开且稠密). 由**定理 6.13 (贝尔纲定理)**, $\bigcap_nG_n$ 稠密, 特别非空. 取 $x\in\bigcap_nG_n$, 则 $x\notin{F}_n$ 对一切 $n$, 与 $\bigcup_nF_n=X$ 矛盾. 故存在 $n$ 使 $F_n$ 含非空开集. 这就是**定理 6.14 (递增闭集族)**. $\blacksquare$

## 11.9 (巴拿赫空间中 $I-T$ 的同胚性 (2025 卷 B 题五))

(2025 年卷 B 题目五, 20 分). 记 $X$ 为巴拿赫空间, $T:X\to{X}$ 为连续线性映射, 记 $\left\|T\right\|=\sup_{\left\|x\right\|=1}\left\|T\left(x\right)\right\|$.

(1) 证明若 $\left\|T\right\|<1$, 则映射 $f:X\to{X}$, $f\left(x\right)=x-T\left(x\right)$ 为单射.

(2) 进一步证明 $f$ 为满射.

(3) 证明 $f$ 为同胚.

(4) 假设存在 $n\ge1$ 使得 $T^n$ 是幂零映射. 证明 $f$ 是双射.

### 解答 11.9

(1) 设 $f\left(x\right)=f\left(y\right)$, 则 $x-T\left(x\right)=y-T\left(y\right)$, 即 $\left(x-y\right)=T\left(x-y\right)$. 于是

$$
\left\|x-y\right\|=\left\|T\left(x-y\right)\right\|\le\left\|T\right\|\left\|x-y\right\|.
$$

若 $x\neq{y}$, 则 $\left\|x-y\right\|>0$, 两边除以 $\left\|x-y\right\|$ 得 $1\le\left\|T\right\|$, 与 $\left\|T\right\|<1$ 矛盾. 故 $x=y$, $f$ 单射.

(2) 对任意 $y\in{X}$, 考虑迭代 $x_{n+1}=y+T\left(x_n\right)$. 则

$$
\left\|x_{n+1}-x_n\right\|=\left\|T\left(x_n-x_{n-1}\right)\right\|\le\left\|T\right\|\left\|x_n-x_{n-1}\right\|\le\left\|T\right\|^n\left\|x_1-x_0\right\|.
$$

由几何级数, $\sum_n\left\|x_{n+1}-x_n\right\|<\sum_n\left\|T\right\|^n\left\|x_1-x_0\right\|<\infty$. 由**定义 6.21 (巴拿赫空间)** 即 $X$ 完备, 由习题 10.16 结论 (绝对收敛级数收敛), $x_n$ 收敛到某 $x$. 取极限 $x=y+T\left(x\right)$, 即 $f\left(x\right)=y$. 故 $f$ 满射.

(3) $f=I-T$ 连续 ($T$ 连续, $I$ 连续). 由第 (1), (2) 步, $f$ 双射. 逆映射由级数给出: $f^{-1}=I+T+T^2+\cdots$, 且 $\left\|f^{-1}\right\|\le\frac{1}{1-\left\|T\right\|}$, 故 $f^{-1}$ 连续. 由**定义 3.23 (同胚)**, $f$ 是同胚.

(4) 设 $T^n=0$. 对任意 $y$, 令 $x=y+T\left(y\right)+T^2\left(y\right)+\cdots+T^{n-1}\left(y\right)$. 则

$$
\left(I-T\right)x=\left(I-T\right)\sum_{k=0}^{n-1}T^k\left(y\right)=\left(I-T^n\right)\left(y\right)=y,
$$

因 $T^n=0$. 故 $f\left(x\right)=y$, $f$ 满射. 单射: $f\left(x\right)=0\Rightarrow{x}=T\left(x\right)\Rightarrow{x}=T^n\left(x\right)=0$. 故 $f$ 双射. $\blacksquare$

## 11.10 (完备度量空间上严格压缩映射的不动点)

设 $\left(X,d\right)$ 是非空完备度量空间, $f:X\to{X}$ 是严格压缩的, 即存在 $0<{}k<1$ 使对一切 $x,y\in{X}$ 有 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in{X}$ 使 $f\left(x\right)=x$.

### 解答 11.10

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

## 11.11 (连续线性映射的利普希茨估计)

设 $\left(E,\left\|\cdot\right\|\right)$ 是域 $\mathbb{K}$ 上的赋范线性空间, $f:E\to{E}$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in{E}$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{K}\left\|x-y\right\|$.

### 解答 11.11

由 $f$ 在 $0$ 连续 (按**定义 3.22 (连续映射)**, $\left\|z\right\|\to0$ 时 $\left\|f\left(z\right)\right\|\to0$), 存在 $\delta>0$, 使 $\left\|z\right\|<\delta$ 时 $\left\|f\left(z\right)\right\|\le1$. 对任意 $x\neq0$, 令 $z=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|z\right\|=\delta/2<\delta$, 故 $\left\|f\left(z\right)\right\|\le1$. 由线性性,

$$
\left\|f\left(x\right)\right\|=\frac{2\left\|x\right\|}{\delta}\left\|f\left(z\right)\right\|\le\frac{2}{\delta}\left\|x\right\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f\left(x\right)-f\left(y\right)=f\left(x-y\right)$, 故

$$
\left\|f\left(x\right)-f\left(y\right)\right\|=\left\|f\left(x-y\right)\right\|\le{K}\left\|x-y\right\|.
$$

$\blacksquare$

## 11.12 (压缩映射 $g_a$ 与解算子 $J$)

沿用习题 11.11 的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb{K}$ 满足 $\left|\lambda\right|>{}K$, 固定 $a\in{E}$, 映射

$$
g_a\left(x\right)=\frac{a-f\left(x\right)}{\lambda}
$$

是压缩映射; 用巴拿赫不动点定理推出 $g_a$ 有唯一不动点 $J\left(a\right)\in{E}$.

### 解答 11.12

对 $x,y\in{E}$, 由习题 11.11,

$$
\left\|g_a\left(x\right)-g_a\left(y\right)\right\|=\frac{\left\|f\left(x\right)-f\left(y\right)\right\|}{\left|\lambda\right|}\le\frac{K}{\left|\lambda\right|}\left\|x-y\right\|.
$$

由假设 $\left|\lambda\right|>{}K$, 故 $k=K/\left|\lambda\right|<1$. 由**定义 6.19 (压缩映射)**, $g_a$ 是压缩映射. $E$ 非空且是**定义 6.38 (完备度量空间)**, 由**定理 6.16 (巴拿赫不动点定理)**, $g_a$ 有唯一不动点, 记为 $J\left(a\right)$. $\blacksquare$

## 11.13 (解算子 $J$ 的利普希茨估计)

证明 $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$.

### 解答 11.13

由 $J\left(a\right)$ 与 $J\left(b\right)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J\left(a\right)=\frac{a-f\left(J\left(a\right)\right)}{\lambda},\quad{J}\left(b\right)=\frac{b-f\left(J\left(b\right)\right)}{\lambda}.
$$

两式相减,

$$
J\left(a\right)-J\left(b\right)=\frac{a-b-f\left(J\left(a\right)\right)+f\left(J\left(b\right)\right)}{\lambda}.
$$

取范数并用三角不等式与习题 11.11 的估计,

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{\left\|a-b\right\|+\left\|f\left(J\left(a\right)\right)-f\left(J\left(b\right)\right)\right\|}{\left|\lambda\right|}\le\frac{\left\|a-b\right\|+K\left\|J\left(a\right)-J\left(b\right)\right\|}{\left|\lambda\right|}.
$$

移项得 $\left(\left|\lambda\right|-K\right)\left\|J\left(a\right)-J\left(b\right)\right\|\le\left\|a-b\right\|$, 即

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|.
$$

$\blacksquare$

## 11.14 (方程 $f\left(x\right)-\lambda{x}=a$ 的唯一可解性与解的连续性)

总结如下结论: 对任意连续线性映射 $f:E\to{E}$, 存在 $K>0$, 使对一切满足 $\left|\lambda\right|>{}K$ 的 $\lambda$ 与一切 $a\in{E}$, 方程 $f\left(x\right)-\lambda{x}=a$ (未知量 $x\in{E}$) 有唯一解 $J\left(a\right)$, 且映射 $a\mapsto{J}\left(a\right)$ 连续.

### 解答 11.14

由习题 11.11, 存在 $K>0$ 使 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{K}\left\|x-y\right\|$. 设 $\left|\lambda\right|>{}K$. 方程 $f\left(x\right)-\lambda{x}=a$ 等价于

$$
x=\frac{a-f\left(x\right)}{\lambda}=g_a\left(x\right).
$$

由习题 11.12, $g_a$ 是**定义 6.19 (压缩映射)**, 由**定理 6.16 (巴拿赫不动点定理)**, 该方程有唯一解 $J\left(a\right)$.

由习题 11.13, $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$, 即 $J$ 是利普希茨映射. 由利普希茨映射连续, $J$ 连续. $\blacksquare$

## 11.15 (局部凸等价于由半范数族定义, 以及可数凸邻域基)

证明: 实或复拓扑向量空间是局部凸的, 当且仅当其拓扑由一族半范数定义. 进一步证明: 在实或复拓扑向量空间中, $0$ 有可数凸邻域基, 当且仅当拓扑由可数族半范数定义.

### 解答 11.15

($\Leftarrow$): 设拓扑由半范数族 $\left\{p_\alpha\right\}_{\alpha\in{A}}$ 定义. 由**定义 6.25 (半范数)**, 每个 $p_\alpha$ 是凸函数 (由三角不等式 $p_\alpha\left(\left(1-t\right)x+ty\right)\le\left(1-t\right)p_\alpha\left(x\right)+tp_\alpha\left(y\right)$). 形如

$$
U_{\alpha_1,\dots,\alpha_n;\varepsilon}=\left\{x:p_{\alpha_i}\left(x\right)<\varepsilon,i=1,\dots,n\right\}
$$

的集合是有限个凸集的交, 由**定义 4.23 (凸集)** 仍是凸集; 它们构成 $0$ 的邻域基. 故由**定义 6.26 (局部凸空间)**, 空间局部凸.

($\Rightarrow$): 设空间局部凸. 由**定义 6.26 (局部凸空间)**, $0$ 有凸邻域基 $\left\{C_\alpha\right\}_{\alpha\in{A}}$. 由**定义 6.24 (拓扑向量空间)**, 加法与数乘连续, 故可在不损失凸性的前提下取每个 $C_\alpha$ 为平衡凸邻域 (即 $x\in{C}_\alpha$ 蕴含 $\lambda{x}\in{C}_\alpha$ 对一切 $\left|\lambda\right|\le1$). 定义

$$
p_\alpha\left(x\right)=\inf\left\{t>0:x\in{t}\,C_\alpha\right\}.
$$

这正是**定义 6.27 (规范函数)**. 由 $C_\alpha$ 凸且平衡, $p_\alpha$ 满足**定义 6.25 (半范数)** 的两条: 齐次 $p_\alpha\left(\lambda{x}\right)=\left|\lambda\right|p_\alpha\left(x\right)$; 三角不等式由 $C_\alpha$ 凸推出. 邻域 $\left\{p_\alpha<\varepsilon\right\}$ 就是 $\varepsilon{C}_\alpha$, 故半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑与原拓扑相同.

可数情形: 若 $0$ 有可数凸邻域基 $\left\{C_n\right\}_{n\ge1}$, 上面的构造给出可数半范数族 $\left\{p_n\right\}$. 反之, 若拓扑由可数半范数族 $\left\{p_n\right\}$ 定义, 则 $\left\{x:p_i\left(x\right)<1/k,i=1,\dots,n\right\}$ ($n,k\ge1$) 是可数凸邻域基. $\blacksquare$

## 11.16 (交集的规范函数是各规范函数的上确界)

设 $E$ 是 $\mathbb{K}$ 上拓扑向量空间, $C$ 是 $0$ 的凸邻域, 规范函数 $\left\|\cdot\right\|_C:E\to\left[0,\infty\right)$ 由规范函数给出. 若 $\left\{C_\alpha\right\}_{\alpha\in{A}}$ 是 $E$ 中一族凸集且其交是 $0$ 的凸邻域, 证明

$$
\left\|\cdot\right\|_{\bigcap_{\alpha\in{A}}C_\alpha}=\sup_{\alpha\in{A}}\left\|\cdot\right\|_{C_\alpha}.
$$

### 解答 11.16

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
