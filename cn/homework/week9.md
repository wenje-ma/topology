# 作业 9

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f:X\to Y$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.6** (扇形连通)<br>一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 $\S4$)

> **定义 4.18** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.23** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定理 5.2** (区间紧)<br>区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.3** (紧度量空间完备)<br>紧度量空间是完备的. (教材 $\S6$)

> **定理 6.7** (连续函数的一致极限连续)<br>连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **定理 6.8** ($C\left(X,Y\right)$ 完备)<br>$Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **定理 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup_n F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (题集 2025 年卷 B)

> **定义 6.22** (绝对收敛级数)<br>$\sum\left\|u_n\right\|$ 收敛的级数 $\sum u_n$; 赋范空间完备当且仅当一切绝对收敛级数都收敛. (题集 $\S4.4$)

> **定义 6.23** (幂零映射)<br>连续线性映射 $f$, 每点被 $f$ 的某次复合映到 $0$. (题集 2025 年卷 B)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.36** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.41** (一致收敛与一致度量)<br>$d\left(f,g\right)=\sup_X\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛当且仅当 $d\left(f_n,g\right)\to0$. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.49** (等距映射)<br>满足 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)$ 的映射 $f$. (题集 $\S3.4$)

### 习题一

用**定理 6.13** (贝尔纲定理) 构造 $\mathbb R\to\mathbb R$ 的连续但处处不可导的函数所成的稠密函数族.

### 解答 习题一

在 $C\left[0,1\right]$ 上装备**定义 6.41** (一致收敛与一致度量) 中的上确界度量. 由**定理 6.8** ($C\left(X,Y\right)$ 完备) 该空间是**定义 6.38** (完备度量空间).

对每个正整数 $n$, 定义

$$
A_n=\left\{f\in C\left[0,1\right]:\exists x\in\left[0,1-1/n\right],\ \text{使 }\left|f\left(x+h\right)-f\left(x\right)\right|\le nh\text{ 对一切 }0<h<1/n\text{ 成立}\right\}.
$$

先证 $A_n$ 闭. 设 $f_k\in A_n$ 且 $f_k$ 依**定义 6.41** (一致收敛与一致度量) 一致收敛到 $f$. 取见证点 $x_k$; 由**定理 5.2** (区间紧) 与**定理 6.1** (紧=序列紧), $\left[0,1-1/n\right]$ 中 $\left(x_k\right)$ 有收敛子列 $x_{k_j}\to x$. 对一切 $0<h<1/n$, 由一致收敛可在 $\left|f_{k_j}\left(x_{k_j}+h\right)-f_{k_j}\left(x_{k_j}\right)\right|\le n h$ 中取极限, 得 $\left|f\left(x+h\right)-f\left(x\right)\right|\le n h$, 即 $f\in A_n$. 由**定义 3.21** (闭集), $A_n$ 闭.

再证 $A_n$ 无内部. 任给 $f\in C\left[0,1\right]$ 与 $\epsilon>0$, 用折线函数 $g$ 一致逼近 $f$ 使 $\left\|g-f\right\|_\infty<\epsilon$, 并把 $g$ 的每个折段改造成斜率绝对值大于 $n$ 的细密锯齿, 改造幅度仍小于 $\epsilon$. 则 $g\notin A_n$ (任何点 $x$ 处都有任意小的 $h$ 使 $\left|g\left(x+h\right)-g\left(x\right)\right|/h>n$). 故 $A_n$ 的每个邻域都含 $A_n$ 外的点, $A_n$ 无内部, 即 $A_n$ 是无处稠密闭集.

由**定理 6.13** (贝尔纲定理), 完备度量空间中可数个无处稠密闭集之并不能是全空间, 故

$$
C\left[0,1\right]\setminus\bigcup_{n=1}^{\infty}A_n\neq\emptyset.
$$

取 $f$ 属于该差集. 对任意 $x$ 与任意 $n$, $f\notin A_n$ 意味着在 $x$ 处不存在商 $\left|f\left(x+h\right)-f\left(x\right)\right|/h$ 被 $n$ 控制的 $h$; 即差商沿 $h\to0$ 无有界极限, $f$ 在每一点都不可导. 这样的 $f$ 全体在 $C\left[0,1\right]$ 中稠密 (因 $\bigcup_n A_n$ 是第一纲集, 其补集为第二纲稠密), 即得连续但处处不可导函数的稠密族. $\blacksquare$

### 习题二

用**定理 6.13** (贝尔纲定理) 证明: 若连续函数列 $f_n:\left[0,1\right]\to\mathbb R$ 逐点收敛到 $f:\left[0,1\right]\to\mathbb R$, 则 $f$ 不可能处处不连续.

### 解答 习题二

$\left[0,1\right]$ 紧, 由**定理 6.3** (紧度量空间完备), 它是**定义 6.38** (完备度量空间). 对正整数 $N$, 定义

$$
E_N=\left\{x\in\left[0,1\right]:\text{对一切 }m,n\ge N,\ \left|f_m\left(x\right)-f_n\left(x\right)\right|\le\frac1N\right\}.
$$

对固定的 $m,n$, 函数 $x\mapsto\left|f_m\left(x\right)-f_n\left(x\right)\right|$ 连续, 其取值落在 $\left[0,1/N\right]$ 中的点集是闭集; $E_N$ 是这样的闭集之交, 由**定义 3.21** (闭集) 它闭. 逐点收敛意味着每个 $x$ 处 $\left(f_n\left(x\right)\right)$ 是**定义 6.37** (柯西列), 故存在 $N$ 使 $x\in E_N$, 即 $\left[0,1\right]=\bigcup_{N\ge1}E_N$. 由**定理 6.14** (递增闭集族), 存在 $N_0$ 使 $E_{N_0}$ 有非空内部, 即存在开区间 $I\subset E_{N_0}$.

在 $I$ 上, 对一切 $m,n\ge N_0$, $\left|f_m\left(x\right)-f_n\left(x\right)\right|\le1/N_0$; 令 $m\to\infty$ 得 $\left|f_n\left(x\right)-f\left(x\right)\right|\le1/N_0$ 对一切 $n\ge N_0$ 与 $x\in I$ 成立. 由**定义 6.41** (一致收敛与一致度量), $f_n$ 在 $I$ 上一致收敛到 $f$. 由**定理 6.7** (连续函数的一致极限连续), $f$ 在 $I$ 上连续. 故 $f$ 至少在一个非空开区间上连续, 不可能处处不连续. $\blacksquare$

### 习题三

证明: 赋范线性空间 $E$ 是完备的, 当且仅当 $E$ 中一切**定义 6.22** (绝对收敛级数) 绝对收敛级数都收敛.

### 解答 习题三

设 $E$ 是**定义 6.20** (赋范线性空间), 它按距离 $d\left(x,y\right)=\left\|x-y\right\|$ 成为**定义 6.35** (度量空间).

$\left(\Rightarrow\right)$ 设 $E$ 是**定义 6.38** (完备度量空间), 由**定义 6.22** (绝对收敛级数), $\sum u_n$ 绝对收敛指 $\sum\left\|u_n\right\|<\infty$. 部分和 $s_n=\sum_{k=1}^n u_k$ 满足

$$
\left\|s_{n+p}-s_n\right\|\le\sum_{k=n+1}^{n+p}\left\|u_k\right\|.
$$

右端是收敛级数 $\sum\left\|u_k\right\|$ 的尾项, 当 $n$ 充分大时任意小, 故 $\left(s_n\right)$ 是**定义 6.37** (柯西列). 由 $E$ 完备, $\left(s_n\right)$ 收敛, 即 $\sum u_n$ 收敛.

$\left(\Leftarrow\right)$ 设一切绝对收敛级数都收敛. 取任意**定义 6.37** (柯西列) $\left(x_n\right)$. 依次选 $n_1<n_2<\cdots$ 使 $i,j\ge n_k$ 时 $\left\|x_i-x_j\right\|<2^{-k}$. 则

$$
x_{n_k}=x_{n_1}+\sum_{j=1}^{k-1}\left(x_{n_{j+1}}-x_{n_j}\right),
$$

且 $\sum_{j=1}^{\infty}\left\|x_{n_{j+1}}-x_{n_j}\right\|\le\sum_{j=1}^{\infty}2^{-j}<\infty$. 由假设, 级数 $\sum_j\left(x_{n_{j+1}}-x_{n_j}\right)$ 收敛, 即子列 $\left(x_{n_k}\right)$ 收敛到某 $x\in E$. 最后, 柯西列若有收敛子列则本身收敛:

$$
\left\|x_n-x\right\|\le\left\|x_n-x_{n_k}\right\|+\left\|x_{n_k}-x\right\|,
$$

右端两项当 $n,k$ 充分大时任意小. 故 $\left(x_n\right)$ 收敛, $E$ 完备. $\blacksquare$

### 习题四

(贝尔纲定理) 回顾**定理 6.13** (贝尔纲定理). 证明该定理在局部紧豪斯多夫空间中也成立.

### 解答 习题四

设 $X$ 局部紧豪斯多夫, $\left\{U_n\right\}_{n\ge 1}$ 是可数个稠密开集. 任取非空开集 $W_0$. 归纳构造: 给定非空开 $W_{n-1}$, 因 $U_n$ 稠密, $W_{n-1}\cap U_n\neq\emptyset$; 取非空开 $V_n$ 使 $\overline{V_n}\subset W_{n-1}\cap U_n$ 且 $\overline{V_n}$ 紧 (局部紧豪斯多夫提供紧邻域基). 于是

$$
\overline{V_1}\supset\overline{V_2}\supset\cdots,\quad\overline{V_n}\subset U_n,\quad\overline{V_n}\text{ 非空紧}.
$$

紧集族的有限交性质给出 $\bigcap_n\overline{V_n}\neq\emptyset$. 该交含于 $W_0\cap\bigcap_n U_n$. 故 $\bigcap_n U_n$ 与任意非空开集相交, 即稠密. 这正是**定理 6.13** (贝尔纲定理) 的结论. $\blacksquare$

### 习题五

设 $f:\mathbb R_{\ge 0}\to\mathbb R$ 连续, 且对每个 $x\ge 0$, 序列 $\left\{f\left(nx\right)\right\}_{n\ge 0}$ 收敛到 $0$. 证明 $\lim_{x\to\infty}f\left(x\right)=0$ (克罗夫特引理).

### 解答 习题五

固定 $\epsilon>0$. 定义

$$
F_m=\left\{x\ge 0:\ \text{对一切 }k\ge m,\ \left|f\left(kx\right)\right|\le\epsilon\right\}.
$$

对固定 $k$, 条件 $\left|f\left(kx\right)\right|\le\epsilon$ 是 $x$ 的闭条件 ($f$ 连续); $F_m$ 是这些闭集 ($k\ge m$) 之交, 故闭. 由假设, 每个 $x\ge 0$ 属于某个 $F_m$, 故 $\mathbb R_{\ge 0}=\bigcup_{m\ge 1}F_m$, 且 $F_m$ 递增.

由**定理 6.13** (贝尔纲定理) 及其**定理 6.14** (递增闭集族), 某个 $F_N$ 有非空内部, 故存在区间 $\left[a,b\right]\subset F_N$, $0<a<b$. 于是对一切 $x\in\left[a,b\right]$ 与 $k\ge N$, $\left|f\left(kx\right)\right|\le\epsilon$.

任取 $t$ 充分大, 考虑整数区间 $\left[t/b,t/a\right]$. 其长度为 $t\left(1/a-1/b\right)\to\infty$, 故当 $t$ 充分大时其中含某整数 $k\ge N$. 令 $x=t/k$, 则 $x\in\left[a,b\right]$, 故 $\left|f\left(t\right)\right|=\left|f\left(kx\right)\right|\le\epsilon$. 因而 $\limsup_{t\to\infty}\left|f\left(t\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{t\to\infty}f\left(t\right)=0$. $\blacksquare$

### 习题六

(7.3 完备性)

(1) 证明赋范线性空间 $E$ 完备当且仅当每个**定义 6.22** (绝对收敛级数) 绝对收敛级数都收敛.

(2) 设 $E$ 是有可数无穷基的赋范线性空间. 取规范基 $\left\{e_n\right\}_{n\ge 1}$, $\left\|e_n\right\|=1$. 令 $F_n=\operatorname{span}\left(e_1,\dots,e_n\right)$, 定义 $\lambda_1=1/3$, $\lambda_{n+1}=\frac{1}{3}d\left(\lambda_n e_n,F_{n-1}\right)$. 证明 $\sum\lambda_n e_n$ 绝对收敛但不收敛, 因而 $E$ 不完备.

### 解答 习题六

**第 1 小题**: ($\Rightarrow$) 设 $E$ 是**定义 6.20** (赋范线性空间) 且完备, $\sum u_n$ 是**定义 6.22** (绝对收敛级数), 即 $\sum\left\|u_n\right\|<\infty$. 部分和 $S_n=\sum_{k=1}^n u_k$ 是**定义 6.37** (柯西列): 对 $m>n$,

$$
\left\|S_m-S_n\right\|=\left\|\sum_{k=n+1}^m u_k\right\|\le\sum_{k=n+1}^m\left\|u_k\right\|\to 0.
$$

由**定义 6.38** (完备度量空间), $S_n$ 收敛.

($\Leftarrow$) 设每个**定义 6.22** (绝对收敛级数) 都收敛. 任取**定义 6.37** (柯西列) $\left(x_n\right)$. 选子列 $\left(x_{\varphi\left(n\right)}\right)$ 使对 $p\ge\varphi\left(n\right)$, $\left\|x_p-x_{\varphi\left(n\right)}\right\|\le 2^{-n}$. 令

$$
a_1=x_{\varphi\left(1\right)},\quad a_n=x_{\varphi\left(n\right)}-x_{\varphi\left(n-1\right)}\ \left(n\ge 2\right).
$$

则 $\left\|a_n\right\|\le 2^{-\left(n-1\right)}$, 故 $\sum a_n$ 绝对收敛. 由假设它收敛于 $s$, 其部分和正是 $x_{\varphi\left(n\right)}$, 故子列收敛于 $s$. 由柯西列性质, 原列 $x_n\to s$. 故 $E$ 完备.

**第 2 小题**: 由递推, $\lambda_n\le 3^{-n}$ (归纳: $\lambda_1=1/3$, $\lambda_{n+1}=\frac{1}{3}d\left(\lambda_n e_n,F_{n-1}\right)\le\frac{1}{3}\lambda_n\left\|e_n\right\|=\lambda_n/3$). 故 $\sum\left\|\lambda_n e_n\right\|=\sum\lambda_n<\infty$, 绝对收敛.

反设 $\sum\lambda_n e_n$ 收敛于 $x$. 因 $E$ 是可数基的, $x\in F_N$ 对某个 $N$ (有限展开). 令 $y=x-\sum_{i=1}^N\lambda_i e_i\in F_N$. 则

$$
3\lambda_{N+2}\le d\left(\lambda_{N+1}e_{N+1},F_N\right)\le\left\|\lambda_{N+1}e_{N+1}-y\right\|=\left\|\sum_{i=N+2}^{\infty}\lambda_i e_i\right\|\le\sum_{i=N+2}^{\infty}\lambda_i\le\frac{3}{2}\lambda_{N+2},
$$

其中最后一步由 $\lambda_{i+1}\le\lambda_i/3$ 得等比和 $\sum_{i=N+2}^\infty\lambda_i\le\frac{3}{2}\lambda_{N+2}$. 这给出 $3\lambda_{N+2}\le\frac{3}{2}\lambda_{N+2}$, 矛盾 ($\lambda_{N+2}>0$). 故级数不收敛. 由第 1 小题, $E$ 不完备. $\blacksquare$

### 习题七

(7.4 贝尔纲定理)

(1) 设 $E$ 是有可数无穷基的赋范线性空间. 令 $F_n=\operatorname{span}\left(e_1,\dots,e_n\right)$. 用**定理 6.13** (贝尔纲定理) 证明 $E$ 不完备.

(2) 设 $\left(E,d\right)$ 完备, $\left(F,\delta\right)$ 是度量空间, $f_n:E\to F$ 连续且逐点收敛到 $f:E\to F$. (a) 对 $\epsilon>0$ 与 $n\in\mathbb N$, 令

$$
F_{n,\epsilon}=\left\{x\in E:\ \forall p\ge n,\ \delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\epsilon\right\}.
$$

用贝尔纲定理证明 $\Omega_\epsilon=\bigcup_n\operatorname{int}F_{n,\epsilon}$ 在 $E$ 中稠密. (b) 证明对 $x_0\in\Omega_\epsilon$, 存在邻域 $V$ 使对 $x\in V$, $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le 3\epsilon$. (c) 证明 $f$ 的连续点集稠密. (d) 证明可导函数 $f:\mathbb R\to\mathbb R$ 的导函数 $f'$ 的连续点集在 $\mathbb R$ 中稠密.

### 解答 习题七

**第 1 小题**: 每个 $F_n$ 是有限维子空间, 故闭 (**定义 3.21** (闭集)), 且无内部 (真子空间不含开球). $E=\bigcup_n F_n$. 若 $E$ 完备, 由**定理 6.14** (递增闭集族), 某个 $F_n$ 有非空内部, 矛盾. 故 $E$ 不完备.

**第 2 小题 (a)**: 每个 $F_{n,\epsilon}$ 闭: 对固定 $p\ge n$, $\left\{x:\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\epsilon\right\}$ 由**定义 3.22** (连续映射) 连续, 故闭; $F_{n,\epsilon}$ 是它们的交, 闭. 因 $f_n$ 逐点收敛, $\bigcup_n F_{n,\epsilon}=E$. 令 $G=E\setminus\Omega_\epsilon=\bigcap_n\left(E\setminus\operatorname{int}F_{n,\epsilon}\right)$. $G$ 闭. 每个 $G\cap F_{n,\epsilon}$ 是闭且无内部 (因 $G$ 去掉了所有内部). 由**定理 6.13** (贝尔纲定理) 及其**定理 6.14** (递增闭集族), $G$ 无内部, 即 $\Omega_\epsilon$ 稠密.

**(b)**: 取 $x_0\in\Omega_\epsilon$, 则 $x_0\in\operatorname{int}F_{n,\epsilon}$ 对某个 $n$, 故存在邻域 $V\subset F_{n,\epsilon}$. 对 $x\in V$ 与 $p\ge n$, $\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\epsilon$. 令 $p\to\infty$ 得 $\delta\left(f\left(x\right),f_n\left(x\right)\right)\le\epsilon$. 特别对 $x_0\in V$, $\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)\le\epsilon$. 故

$$
\delta\left(f\left(x_0\right),f\left(x\right)\right)\le\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)+\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)+\delta\left(f_n\left(x\right),f\left(x\right)\right).
$$

第三项 $\le\epsilon$. 第一项 $\le\epsilon$. 中间项由 $f_n$ 连续, 可取 $V$ 更小使 $\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)\le\epsilon$. 合计 $\le 3\epsilon$.

**(c)**: 令 $\Omega=\bigcap_{m\ge 1}\Omega_{1/m}$. 由**定义 3.32** (稠密), 每个 $\Omega_{1/m}$ 稠密开 (或至少稠密), 由**定理 6.13** (贝尔纲定理), $\Omega$ 稠密. 对 $x_0\in\Omega$ 与任意 $\epsilon>0$, 由 (b) 存在邻域 $V$ 使 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le 3/m<\epsilon$ (取 $m$ 使 $3/m<\epsilon$). 故 $f$ 在 $x_0$ 连续. 因而连续点集 $\Omega$ 稠密.

**(d)**: 令 $f:\mathbb R\to\mathbb R$ 可导. 定义差商

$$
g_n\left(x\right)=n\left(f\left(x+\frac{1}{n}\right)-f\left(x\right)\right).
$$

每个 $g_n$ 连续, 且 $g_n\left(x\right)\to f'\left(x\right)$ 逐点. 由 (c), $g_n$ 的逐点极限 $f'$ 的连续点集在 $\mathbb R$ 中稠密. $\blacksquare$

### 习题八

考虑一个赋范线性空间 $E$. 称 $E$ 中的级数 $\sum_{n\ge0}u_n$ 绝对收敛, 如果级数 $\sum_{n\ge0}\left\|u_n\right\|$ 收敛.

(1) (10 分) 证明如果 $E$ 是完备的, 那么所有绝对收敛的级数 $\sum_{n\ge0}u_n$ 都是收敛的.

(2) (10 分) 现在不假设 $E$ 是完备的, 但假设 $E$ 中所有的绝对收敛级数都是收敛的. 假设 $S_n$ 是 $E$ 中的一个柯西列. 证明可以用归纳法找出 $\varphi\left(1\right)<\varphi\left(2\right)<\cdots$ 使得对一切 $n\ge\varphi\left(k\right)$, $\left\|S_n-S_{\varphi\left(k\right)}\right\|<2^{-k}$.

(3) (10 分) 通过定义 $u_k=S_{\varphi\left(k+1\right)}-S_{\varphi\left(k\right)}$, 证明在第 2 小题的条件下 $E$ 是完备的.

### 解答 习题八

设 $E$ 由**定义 6.20** (赋范线性空间) 装备范数 $\left\|\cdot\right\|$.

(1) 设 $\sum_{n\ge0}u_n$ 绝对收敛, 即由**定义 6.22** (绝对收敛级数) $\sum\left\|u_n\right\|$ 收敛. 记部分和 $s_n=\sum_{j=0}^n u_j$. 对 $m>n$, 由范数的三角不等式,

$$
\left\|s_m-s_n\right\|=\left\|\sum_{j=n+1}^m u_j\right\|\le\sum_{j=n+1}^m\left\|u_j\right\|.
$$

因 $\sum\left\|u_j\right\|$ 收敛, 其尾部 $\sum_{j>n}\left\|u_j\right\|$ 趋于 $0$, 故由**定义 6.37** (柯西列) $s_n$ 是柯西列. 由**定义 6.38** (完备度量空间) $E$ 完备, $s_n$ 收敛, 即原级数收敛.

(2) 因 $\left(S_n\right)$ 是柯西列, 由**定义 6.37** (柯西列), 对每个 $k\ge1$, 存在 $N_k$ 使当 $n,m\ge N_k$ 时 $\left\|S_n-S_m\right\|<2^{-k}$. 归纳选取: 取 $\varphi\left(1\right)\ge N_1$; 选定 $\varphi\left(k\right)$ 后, 取 $\varphi\left(k+1\right)>\max\left(\varphi\left(k\right),N_{k+1}\right)$. 于是 $\varphi\left(1\right)<\varphi\left(2\right)<\cdots$. 对任意 $n\ge\varphi\left(k\right)\ge N_k$, 由 $n,\varphi\left(k\right)\ge N_k$ 得 $\left\|S_n-S_{\varphi\left(k\right)}\right\|<2^{-k}$.

(3) 令 $u_k=S_{\varphi\left(k+1\right)}-S_{\varphi\left(k\right)}$. 因 $\varphi\left(k+1\right)\ge\varphi\left(k\right)$, 由第 2 小题 (取 $n=\varphi\left(k+1\right)$) 得 $\left\|u_k\right\|<2^{-k}$. 故 $\sum_{k\ge1}\left\|u_k\right\|\le\sum_{k\ge1}2^{-k}<\infty$, 由**定义 6.22** (绝对收敛级数) 级数 $\sum u_k$ 绝对收敛. 由题设 (一切绝对收敛级数收敛), $\sum_{k\ge1}u_k$ 收敛于某 $s\in E$. 而

$$
S_{\varphi\left(k\right)}=S_{\varphi\left(1\right)}+\sum_{j=1}^{k-1}u_j\longrightarrow S_{\varphi\left(1\right)}+s.
$$

故子列 $\left(S_{\varphi\left(k\right)}\right)$ 收敛. 柯西列若有收敛子列则整体收敛 (设子列收敛于 $L$, 由柯西性, 全列与子列距离趋于 $0$, 故全列收敛于 $L$). 由**定义 6.38** (完备度量空间), $E$ 中任意柯西列都收敛, $E$ 完备. $\blacksquare$

### 习题九

设 $f:\mathbb R_{\ge0}\to\mathbb R$ 是一个连续函数, 并且对于任意的 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 都收敛到 $0$.

(1) (5 分) 取定 $\epsilon>0$ 并考虑集合 $F_n=\left\{x\ge0:\forall p\in\mathbb N,\ p\ge n,\ \left|f\left(px\right)\right|\le\epsilon\right\}$. 证明对于任意的 $n\ge0$, $F_n$ 都是闭集合.

(2) (5 分) 证明所有 $F_n$ 的并包含 $\left(0,\infty\right)$.

(3) (5 分) 利用贝尔纲定理证明 $\lim_{x\to\infty}f\left(x\right)=0$.

### 解答 习题九

(1) 写 $F_n=\bigcap_{p\ge n}\left\{x\ge0:\left|f\left(px\right)\right|\le\epsilon\right\}$. 对固定 $p$, 映射 $x\mapsto px$ 连续, $f$ 连续, 由**定义 3.22** (连续映射) 复合 $x\mapsto f\left(px\right)$ 连续; 而 $\left[-\epsilon,\epsilon\right]\subset\mathbb R$ 是闭集, 故其原像 $\left\{x:\left|f\left(px\right)\right|\le\epsilon\right\}$ 由**定义 3.21** (闭集) 是闭集. 闭集的任意交仍闭: 补集为开集的任意并, 由**定义 3.18** (拓扑空间) 的拓扑公理仍是开集, 再由**定义 3.21** (闭集) 得交为闭集, 故 $F_n$ 闭.

(2) 任取 $x>0$, 由题设 $f\left(nx\right)\to0$, 故存在 $n$ 使对一切 $p\ge n$ 都有 $\left|f\left(px\right)\right|\le\epsilon$, 即 $x\in F_n$. 故 $x\in\bigcup_{n\ge1}F_n$, 即 $\left(0,\infty\right)\subset\bigcup_n F_n$. 又显然 $F_n\subset F_{n+1}$ (条件 $p\ge n+1$ 弱于 $p\ge n$), 闭集族递增.

(3) 取紧区间 $\left[1,2\right]\subset\left(0,\infty\right)$. 由第 2 小题, $\left[1,2\right]=\bigcup_{n\ge1}\left(F_n\cap\left[1,2\right]\right)$. 每个 $F_n\cap\left[1,2\right]$ 在 $\left[1,2\right]$ 中闭 (闭集与闭区间之交闭), 且递增. 因 $\left[1,2\right]$ 紧, 由**定理 6.3** (紧度量空间完备) 它完备. 由**定理 6.14** (递增闭集族), 存在 $N$ 使 $F_N\cap\left[1,2\right]$ 在 $\left[1,2\right]$ 中有非空内部, 即存在 $a<b$ 使 $\left(a,b\right)\subset F_N$. 于是对一切 $p\ge N$ 与 $x\in\left(a,b\right)$, $\left|f\left(px\right)\right|\le\epsilon$.

对充分大的 $t>0$, 区间族 $\left(pa,pb\right)$ ($p\ge N$) 相互重叠 (当 $p\left(b-a\right)\ge a$ 时, $pb\ge\left(p+1\right)a$), 故 $\bigcup_{p\ge N}\left(pa,pb\right)$ 包含某个 $\left[T,\infty\right)$. 任取 $t\ge T$, 则 $t\in\left(pa,pb\right)$ 对某 $p\ge N$ 成立, 即 $t=px$, $x\in\left(a,b\right)\subset F_N$, 从而 $\left|f\left(t\right)\right|=\left|f\left(px\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{t\to\infty}f\left(t\right)=0$. $\blacksquare$

### 习题十

考虑在 $x,y\in\left(0,\infty\right)$ 上定义的函数 $\delta\left(x,y\right)=\left|\frac1x-\frac1y\right|$.

(1) (10 分) 证明 $\delta$ 是一个在 $\left(0,\infty\right)$ 上的度量.

(2) (10 分) 证明由 $\delta$ 在 $\left(0,\infty\right)$ 上诱导的拓扑就是最常见的拓扑.

(3) (5 分) 证明度量空间 $\left(\left(0,\infty\right),\delta\right)$ 不是完备的.

(4) (5 分) 证明度量空间 $\left(\left(0,1\right],\delta\right)$ 是完备的.

### 解答 习题十

(1) 令 $\varphi:\left(0,\infty\right)\to\left(0,\infty\right)$ 为 $\varphi\left(x\right)=\frac1x$, 则 $\delta\left(x,y\right)=\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$. 它是由通常绝对值度量经双射 $\varphi$ 拉回的. 逐条验证**定义 6.35** (度量空间) 的公理: $\delta\left(x,x\right)=0$; $\delta\left(x,y\right)=0\Rightarrow\left|\varphi\left(x\right)-\varphi\left(y\right)\right|=0\Rightarrow\varphi\left(x\right)=\varphi\left(y\right)\Rightarrow x=y$; 对称性显然; 三角不等式由绝对值的三角不等式给出:

$$
\delta\left(x,z\right)=\left|\varphi\left(x\right)-\varphi\left(z\right)\right|\le\left|\varphi\left(x\right)-\varphi\left(y\right)\right|+\left|\varphi\left(y\right)-\varphi\left(z\right)\right|=\delta\left(x,y\right)+\delta\left(y,z\right).
$$

故 $\delta$ 是度量.

(2) 映射 $\varphi\left(x\right)=\frac1x$ 及其逆 $\varphi^{-1}\left(y\right)=\frac1y$ 在通常拓扑下都连续, 故由**定义 3.23** (同胚), $\varphi$ 是 $\left(0,\infty\right)$ 到自身的同胚, 且由第 1 小题它保持距离 (即**定义 6.49** (等距映射)). 由**定义 6.36** (开球), $\delta$ 的开球 $B_\delta\left(x,r\right)=\varphi^{-1}\left(\left(\varphi\left(x\right)-r,\varphi\left(x\right)+r\right)\right)$ 是通常拓扑下的开集; 反之通常开球也同理是 $\delta$-开集. 故两种开球生成同一拓扑, 即 $\delta$ 诱导通常拓扑.

(3) 取 $x_n=n$. 则 $\delta\left(n,m\right)=\left|\frac1n-\frac1m\right|\to0$ ($n,m\to\infty$), 由**定义 6.37** (柯西列) $\left(x_n\right)$ 是 $\delta$-柯西列. 若它在 $\left(0,\infty\right)$ 中收敛于 $x$, 则 $\delta\left(n,x\right)=\left|\frac1n-\frac1x\right|\to0$, 即 $\frac1x=0$, 不可能. 故该柯西列不收敛, 由**定义 6.38** (完备度量空间), $\left(\left(0,\infty\right),\delta\right)$ 不完备.

(4) 在 $\varphi\left(x\right)=\frac1x$ 下, $\left(\left(0,1\right],\delta\right)$ 等距 (由**定义 6.49** (等距映射)) 于 $\left(\left[1,\infty\right),\left|\cdot\right|\right)$. 设 $\left(y_n\right)$ 是 $\left[1,\infty\right)$ 中的柯西列, 则它也是 $\mathbb R$ 中的柯西列, 故在 $\mathbb R$ 中收敛于 $y$; 又每个 $y_n\ge1$, 极限保持 $y\ge1$, 故 $y\in\left[1,\infty\right]$, 即 $\left[1,\infty\right)$ 完备. 等距把收敛性搬过去, 故 $\left(\left(0,1\right],\delta\right)$ 完备. $\blacksquare$

### 习题十一

设 $f:\mathbb R_{\ge0}\to\mathbb R$ 是一个连续函数, 并且对于任意的 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 都收敛到 $0$.

(1) (5 分) 设 $\Omega\subset\left(0,\infty\right)$ 是一个非平凡开集且 $\Omega$ 不是有界的. 考虑集合 $\Omega_n=\left\{x\in\mathbb R:\exists p\ge n,\ px\in\Omega\right\}$. 证明对于任意 $n\ge1$, $\Omega_n$ 都是在 $\mathbb R$ 中的稠密开集合.

(2) (5 分) 利用贝尔纲定理, 证明存在 $x_0$, 使得对任意 $N\in\mathbb N$, 存在 $n\ge N$ 使 $n x_0\in\Omega$.

(3) (5 分) 证明 $\lim_{x\to\infty}f\left(x\right)=0$.

### 解答 习题十一

(1) 开: $\Omega_n=\bigcup_{p\ge n}\left\{x:px\in\Omega\right\}=\bigcup_{p\ge n}\frac1p\,\Omega$. 每个 $\frac1p\Omega$ 是开集的相似像, 由**定义 3.22** (连续映射) 相似映射 $x\mapsto px$ 是同胚, 故 $\frac1p\Omega$ 开; 由**定义 3.18** (拓扑空间) 开集任意并开, $\Omega_n$ 开.

稠: 任取非空开区间 $\left(a,b\right)$. 因 $\Omega$ 无界, 取 $y\in\Omega$ 充分大. 取 $p=\left\lceil\frac yb\right\rceil$, 则 $pb\ge y$ 且 $\left(p-1\right)b<y$, 从而 $x=\frac yp$ 满足 $x\le b$ 且 $x>\frac{\left(p-1\right)b}{p}=b\left(1-\frac1p\right)$. 取 $y$ 足够大使 $p\ge n$ 且 $b\left(1-\frac1p\right)>a$, 则 $x\in\left(a,b\right)$ 且 $px=y\in\Omega$. 故 $\left(a,b\right)$ 交 $\Omega_n$, $\Omega_n$ 稠密.

(2) $\mathbb R$ 完备. 由第 1 小题, 每个 $\Omega_n$ 是稠密开集. 由**定理 6.13** (贝尔纲定理), 可数交 $\bigcap_{n\ge1}\Omega_n$ 稠密, 故非空, 取 $x_0\in\bigcap_{n\ge1}\Omega_n$. 则对任意 $N$, $x_0\in\Omega_N$, 即存在 $p\ge N$ 使 $px_0\in\Omega$.

(3) 取定 $\epsilon>0$, 令 $\Omega=\left\{x>0:\left|f\left(x\right)\right|>\epsilon\right\}$. 由**定义 3.22** (连续映射), $f$ 连续, 故 $\Omega$ 是开集. 若 $\Omega$ 无界, 由第 2 小题存在 $x_0$ 使 $\left|f\left(nx_0\right)\right|>\epsilon$ 对任意大的 $n$ 成立, 与题设 $f\left(nx_0\right)\to0$ 矛盾. 故 $\Omega$ 有界, 即存在 $T$ 使 $x>T$ 时 $x\notin\Omega$, 亦即 $\left|f\left(x\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{x\to\infty}f\left(x\right)=0$. $\blacksquare$

### 习题十二

(2024 年卷 C 题目一, 60 分). 本大题中各小题相互独立.

(1) (20 分) 写出贝尔纲定理的一个版本.

(2) (20 分) 证明空间 $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 是连通的. 证明空间 $H^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2-z^2=-1\right\}$ 不是连通的.

(3) (20 分) 设 $\left(X,d\right)$ 是一个完备度量空间. 证明如果 $F\subset X$ 是 $X$ 的闭子空间, 那么 $\left(F,d\right)$ 是完备的. 证明如果 $O\subset X$ 是 $X$ 的开子空间, 那么 $\left(O,d\right)$ 不一定是完备的.

(4) (附加题, 10 分) 设 $\left(X,d\right)$ 是完备度量空间, $O\subset X$ 开. 证明存在 $O$ 上由 $d$ 诱导的度量 $d'$ 使 $\left(O,d'\right)$ 完备. 提示: 考虑 $\phi\left(x\right)=\frac1{d\left(x,X-O\right)}$ 及嵌入 $x\mapsto\left(x,\phi\left(x\right)\right)$.

### 解答 习题十二

(1) 贝尔纲定理即**定理 6.13** (贝尔纲定理): 完备度量空间中可数个稠密开集之交非空 (且稠密).

(2) 记上半球 $D^+=\left\{\left(x,y,z\right)\in S^2:z\ge0\right\}$ 与下半球 $D^-=\left\{z\le0\right\}$. 映射 $\left(u,v\right)\mapsto\left(u,v,\sqrt{1-u^2-v^2}\right)$ 把闭单位圆盘 $\left\{u^2+v^2\le1\right\}$ 映成 $D^+$, 是同胚; 闭单位圆盘由**定义 4.23** (凸集) 是凸集故连通, 由**定理 4.2** (连续像连通) $D^+$ 连通. 同理 $D^-$ 连通. 二者之交为赤道 $\left\{z=0\right\}\cap S^2$, 非空. 由**定理 4.6** (扇形连通), $S^2=D^+\cup D^-$ 连通.

   对 $H^2$, 由方程 $z^2=x^2+y^2+1$ 知 $z\neq0$. 令 $H^+=\left\{z>0\right\}\cap H^2$, $H^-=\left\{z<0\right\}\cap H^2$. 二者非空, 不交, 且都是 $H^2$ 在子空间拓扑下的开集 ($H^+=H^2\cap\left\{z>0\right\}$). 于是 $H^2$ 写成两个非空不相交开集之并, 由**定义 4.18** (连通空间) 它不连通.

(3) 设 $\left(x_n\right)$ 是 $F$ 中的柯西列. 因 $F$ 上度量即 $d$, 它也是 $X$ 中的柯西列; 由**定义 6.38** (完备度量空间) $X$ 完备, 故 $x_n\to x\in X$. 因 $F$ 闭 (由**定义 3.21** (闭集)), 序列极限 $x\in F$. 故 $F$ 中柯西列在 $F$ 中收敛, 由**定义 6.38** (完备度量空间) $F$ 完备.

   开子空间不必完备: 取 $X=\mathbb R$ (完备), $O=\left(0,1\right)$ 开. $x_n=\frac1n$ 由**定义 6.37** (柯西列) 是 $O$ 中柯西列, 但其极限 $0\notin O$, 故不收敛, $\left(O,d\right)$ 不完备.

(4) 由**定义 6.46** (点到集合的距离), $d\left(x,X-O\right)>0$ 对 $x\in O$ 成立. 令 $\phi\left(x\right)=\frac1{d\left(x,X-O\right)}$, 定义嵌入 $i:O\to X\times\mathbb R$, $i\left(x\right)=\left(x,\phi\left(x\right)\right)$. 证 $i\left(O\right)$ 在 $X\times\mathbb R$ 中闭: 取 $i\left(x_n\right)\to\left(y,t\right)$, 则 $x_n\to y$ 于 $X$. 若 $y\in O$, 则 $\phi$ 在 $O$ 上连续, $\phi\left(x_n\right)\to\phi\left(y\right)$, 故 $t=\phi\left(y\right)$, $\left(y,t\right)=i\left(y\right)$. 若 $y\notin O$, 则 $d\left(x_n,X-O\right)\to0$, $\phi\left(x_n\right)\to\infty$, 与有限 $t$ 矛盾. 故 $y\in O$, $i\left(O\right)$ 闭. $X\times\mathbb R$ 完备 (两完备空间之积), 由第 3 小题闭子空间 $i\left(O\right)$ 完备. 用 $i$ 把度量拉回 $O$: $d'\left(x,y\right)=d_{X\times\mathbb R}\left(i\left(x\right),i\left(y\right)\right)$, 则 $\left(O,d'\right)$ 与完备空间 $i\left(O\right)$ 等距, 故完备. $\blacksquare$

### 习题十三

(2025 年卷 B 题目二, 50 分). 一个巴拿赫空间是完备的赋范线性空间. 考虑一个巴拿赫空间 $X$ 和一个连续线性映射 $f:X\to X$. 假设对于任意的 $x\in X$, 都存在 $n\in\mathbb N$ 使 $f^n\left(x\right)=0$, 其中 $f^n$ 是 $n$ 次复合.

(1) 考虑 $F_n=\left\{x\in X:f^n\left(x\right)=0\right\}$. 证明对于任意 $n\in\mathbb N$, $F_n$ 都是 $X$ 的一个闭子集.

(2) 证明存在某个 $N\in\mathbb N$, 使得 $F_N$ 有内点.

(3) 证明上一问中的 $F_N$ 一定是 $X$.

(4) 证明 $f$ 是一个幂零映射.

(5) 考虑多项式空间 $\mathbb R\left[X\right]$ 中的线性映射 $f:P\mapsto P'$, 其中 $P'$ 是多项式 $P$ 的导数. 讨论这个例子与上面结果的关系.

### 解答 习题十三

(1) $f^n$ 是连续线性映射的复合, 故连续. $F_n=\left(f^n\right)^{-1}\left(\left\{0\right\}\right)$. 在巴拿赫空间 $X$ (由**定义 6.21** (巴拿赫空间), 它是豪斯多夫的) 中单点集 $\left\{0\right\}$ 闭, 由**定义 3.21** (闭集), 其原像 $F_n$ 闭.

(2) 由题设每个 $x$ 被某次复合映到 $0$, 故 $X=\bigcup_{n\ge1}F_n$. 又 $F_n\subset F_{n+1}$ (若 $f^n x=0$ 则 $f^{n+1}x=f^n\left(fx\right)=0$), 闭集族递增. $X$ 由**定义 6.21** (巴拿赫空间) 完备. 由**定理 6.14** (递增闭集族) (即**定理 6.13** (贝尔纲定理) 的推论), 存在 $N$ 使 $F_N$ 有非空内部.

(3) 设 $B\left(x_0,r\right)\subset F_N$, 即 $f^N\left(x_0\right)=0$ 且 $f^N$ 在该球上取 $0$. 任取 $y\in X$, 取充分小 $t>0$ 使 $t y$ 范数小于 $r$, 则 $x_0+t y\in B\left(x_0,r\right)\subset F_N$. 由线性 $f^N\left(x_0+t y\right)=f^N\left(x_0\right)+t f^N\left(y\right)=0$, 而 $f^N\left(x_0\right)=0$, 故 $t f^N\left(y\right)=0$, 即 $f^N\left(y\right)=0$. 由 $y$ 任意, $F_N=X$.

(4) 由第 3 小题存在统一的 $N$ 使对一切 $x\in X$, $f^N\left(x\right)=0$. 由**定义 6.23** (幂零映射), $f$ 是幂零映射.

(5) 对 $P\in\mathbb R\left[X\right]$, $f\left(P\right)=P'$. 若 $\deg P=d$, 则 $f^{d+1}\left(P\right)=0$, 故题设的"每点被某次复合映到 $0$"成立. 但 $\mathbb R\left[X\right]$ (装备任一通常范数) 不完备, 且不存在统一的 $N$ 使 $f^N=0$ (次数无界). 这正说明第 2、3 步用到的完备性 (**定理 6.14** (递增闭集族)) 是本质的: 在非完备空间上, 逐点幂零不必推出一致幂零. $\blacksquare$
