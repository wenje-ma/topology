# week10

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{}X$ 是闭的, 若 $X\setminus{}F$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{}Y$ 是连续的, 若对所有开集 $U\subset{}Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{}X$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 5.3 ($\mathbb{R}^n$ 中的紧集)**
> 
> $K\subset\mathbb{R}^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.16 (巴拿赫不动点定理)**
> 
> 非空完备度量空间上的压缩映射有唯一不动点. (题集 §4.3 Q1)

> **定义 6.19 (压缩映射)**
> 
> 称 $f:X\to{}X$ 是压缩的, 若存在 $0<{}k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le{}k\,d\left(x,y\right)$. (题集 §4.3 Q1)

> **定义 6.20 (赋范线性空间)**
> 
> 向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.24 (拓扑向量空间)**
> 
> 向量空间装备使加法 $E\times{}E\to{}E$ 与数乘 $\mathbb{K}\times{}E\to{}E$ 都连续的拓扑. (题集 §5 Q6)

> **定义 6.27 (规范函数)**
> 
> 凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in{}C,t>0\right\}$ (等价地 $\inf\left\{t>0:x\in{}tC\right\}$). (题集 §5 Q14)

> **定义 6.28 (算子范数)**
> 
> $L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le1}\left\|Tx\right\|$. (题集 §5 Q15)

> **定义 6.35 (度量空间)**
> 
> 度量 $d:X\times{}X\to\mathbb{R}_{\ge0}$ 满足:
> 
> (1) $d\left(x,x\right)=0$;
> 
> (2) 若 $d\left(x,y\right)=0$ 则 $x=y$;
> 
> (3) $d\left(x,y\right)=d\left(y,x\right)$;
> 
> (4) $d\left(x,y\right)\le{}d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.39 (完备化)**
> 
> 任意度量空间可自然嵌入一个完备度量空间; 实数轴 $\mathbb{R}$ 是有理数集的完备化, 故 $\mathbb{R}$ 完备. (教材 $\S6$)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; "拓扑学"(原书第2版) $\S29$)

## 10.13 (恰有一个聚点蕴含收敛)

恰一个聚点. 设 $f:\mathbb{R}^n\to\mathbb{R}^n$ 连续, 且序列 $\left(f^n\left(\boldsymbol{x}_0\right)\right)$ 恰有一个聚点. 证明该序列收敛.

题集 §4.5 C7.

### 解答 10.13

记 $\boldsymbol{x}_n=f^n\left(\boldsymbol{x}_0\right)$, 设唯一聚点为 $\boldsymbol{z}$. 取子列 $\boldsymbol{x}_{n_j}\to\boldsymbol{z}$. 由 $f$ 连续, $\boldsymbol{x}_{n_j+1}=f\left(\boldsymbol{x}_{n_j}\right)\to{}f\left(\boldsymbol{z}\right)$. 而 $\left(\boldsymbol{x}_{n_j+1}\right)$ 是 $\left(\boldsymbol{x}_n\right)$ 的子列, 其极限 $f\left(\boldsymbol{z}\right)$ 必为聚点, 由唯一性 $f\left(\boldsymbol{z}\right)=\boldsymbol{z}$.

反设 $\left(\boldsymbol{x}_n\right)$ 不收敛到 $\boldsymbol{z}$. 则存在 $\varepsilon>0$ 与无穷多个 $n$ 使 $\left\|\boldsymbol{x}_n-\boldsymbol{z}\right\|\ge\varepsilon$. 从每个 $n_j$ 出发, 若其后轨道始终在 $B\left(\boldsymbol{z},\varepsilon\right)$ 内, 则尾部落在紧闭球中, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 与**定理 6.1 (紧 $=$ 序列紧)**, 该尾部的任何聚点都是 $\boldsymbol{z}$, 矛盾于不收敛. 故从每个 $n_j$ 出发, 存在第一个 $m_j>n_j$ 使 $\left\|\boldsymbol{x}_{m_j}-\boldsymbol{z}\right\|=\varepsilon$. 点 $\boldsymbol{x}_{m_j}$ 都落在紧球面 $\partial{}B\left(\boldsymbol{z},\varepsilon\right)$ 上, 抽子列 $\boldsymbol{x}_{m_{j_k}}\to\boldsymbol{w}$, $\left\|\boldsymbol{w}-\boldsymbol{z}\right\|=\varepsilon$. 则 $\boldsymbol{w}$ 是 $\left(\boldsymbol{x}_n\right)$ 的聚点且 $\boldsymbol{w}\neq\boldsymbol{z}$, 矛盾. 故 $\left(\boldsymbol{x}_n\right)\to\boldsymbol{z}$.

$\blacksquare$

## 10.14 (紧集与闭集之和闭, 两闭集之和未必闭)

闭集之和. 设 $E=\mathbb{R}^n$, $A,B\subset{}E$.

(1) 证明: 若 $A$ 紧而 $B$ 闭, 则 $A+B=\left\{\boldsymbol{a}+\boldsymbol{b}:\boldsymbol{a}\in{}A,\boldsymbol{b}\in{}B\right\}$ 闭;

(2) 证明: 若 $A,B$ 都闭, $A+B$ 不必闭.

题集 §4.5 C10.

### 解答 10.14

(1) 取序列 $a_n+b_n\in{}A+B$ 收敛到 $y$. 由**定理 6.1 (紧 $=$ 序列紧)**, $A$ 紧, 故 $\left(a_n\right)$ 有子列 $a_{n_j}\to{}a\in{}A$. 则 $b_{n_j}=\left(a_{n_j}+b_{n_j}\right)-a_{n_j}\to{}y-a$. 因 $B$ 闭, 由**定义 3.21 (闭集)**, $y-a\in{}B$. 故 $y=a+\left(y-a\right)\in{}A+B$. $A+B$ 含一切收敛序列的极限, 故闭.

$\blacksquare$

(2) 反例: 取 $A=\left\{\left(x,0\right):x\in\mathbb{R}\right\}$, $B=\left\{\left(x,1/x\right):x>0\right\}$. $A$ 与 $B$ 都闭. 但

$$
A+B=\left\{\left(x+t,1/t\right):t>0\right\}=\left\{\left(u,v\right):v>0\right\},
$$

即开的上半平面, 由**定义 3.21 (闭集)** 它不是闭集.

$\blacksquare$

## 10.15 (度量空间的完备化)

(完备化) 设 $\left(M,d\right)$ 不完备. 考虑全体柯西列 $\left\{x_n\right\}$, 等价关系 $\left\{x_n\right\}\sim\left\{y_n\right\}$ 当且仅当 $\lim_{n\to\infty}d\left(x_n,y_n\right)=0$. 令 $\widehat{M}$ 为等价类集合, 距离 $\widehat{d}\left(\left[x\right],\left[y\right]\right)=\lim_{n\to\infty}d\left(x_n,y_n\right)$. 证明 $\widehat{M}$ 完备, 且 $M$ 在嵌入 $x\mapsto\left(x,x,\dots\right)$ 下在 $\widehat{M}$ 中稠密.

题集 §5.1 C5.

### 解答 10.15

$\widehat{d}$ 良定义: 若 $\left[x_n\right]=\left[x_n'\right]$, $\left[y_n\right]=\left[y_n'\right]$, 则 $d\left(x_n,y_n\right)-d\left(x_n',y_n'\right)$ 由三角不等式趋于 $0$, 极限与代表元无关. 由**定义 6.35 (度量空间)**, $\widehat{d}$ 满足四公理. 这里等价关系中出现的 $\left\{x_n\right\}$ 是**定义 6.37 (柯西列)** 意义下的柯西列.

完备: 设 $\left\{\xi_k\right\}$ 是 $\widehat{M}$ 中柯西列, $\xi_k=\left[\left(x_n^{\left(k\right)}\right)_n\right]$. 对每个 $k$, 取代表列使其前 $k$ 项稳定逼近; 对角化取 $z_k=x_k^{\left(k\right)}$. 由柯西性与三角不等式, $\left(z_k\right)$ 是 $M$ 中柯西列, 记其等价类为 $\xi$. 则 $\xi_k\to\xi$. 由**定义 6.38 (完备度量空间)**, $\widehat{M}$ 完备.

$\blacksquare$

稠密嵌入: 映射 $i:M\to\widehat{M}$, $i\left(x\right)=\left[\left(x,x,\dots\right)\right]$. 任意 $\xi=\left[\left(x_n\right)\right]\in\widehat{M}$, $x_n\to\xi$ 在 $\widehat{M}$ 中, 而 $x_n\in{}i\left(M\right)$. 故 $i\left(M\right)$ 的闭包为全空间, 由**定义 3.32 (稠密)** $M$ 在 $\widehat{M}$ 中稠密. 由**定义 6.39 (完备化)**, 这就是 $M$ 的完备化.

$\blacksquare$

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

即 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛. 其部分和即 $x_{n_{k+1}}-x_{n_1}$, 故子列 $x_{n_k}$ 收敛. 由柯西列含收敛子列则全列收敛, 全列 $x_n$ 收敛. 故 $E$ 完备.

$\blacksquare$

($\Leftarrow$) 设 $E$ 完备, $\sum_n\left\|x_n\right\|<\infty$. 部分和 $S_N=\sum_{n=1}^Nx_n$ 满足对 $M>N$,

$$
\left\|S_M-S_N\right\|=\left\|\sum_{n=N+1}^Mx_n\right\|\le\sum_{n=N+1}^M\left\|x_n\right\|\to0,
$$

故 $\left(S_N\right)$ 是**定义 6.37 (柯西列)**. 由**定义 6.38 (完备度量空间)**, $S_N$ 收敛, 即级数收敛.

$\blacksquare$

(2) 取 $E=C\left(\left[0,1\right]\right)$ 装备 $L^1$ 范数 $\left\|f\right\|_1=\int_0^1\left|f\left(t\right)\right|\,\mathrm{d}t$, 它不完备. 构造折线函数列 $f_n$, 使 $f_n$ 从 $0$ 线性升到 $1$ 的区间长度为 $1/n$. 则 $\sum_n\left\|f_n\right\|_1<\infty$ (每段面积 $\le1/n$), 但 $\sum_nf_n$ 在 $\left(0,1\right)$ 上无界, 不作为连续函数存在. 故绝对收敛但不收敛于 $E$ 中.

$\blacksquare$

## 11.1 (贝尔纲定理的局部紧版本)

(贝尔纲, 局部紧版本) 证明: 在局部紧豪斯多夫空间中, 可数个稠密开集之交仍稠密.

题集 §5.1 C6.

### 解答 11.1

设 $\left\{U_n\right\}_{n=1}^{\infty}$ 是稠密开集, $V_0$ 是任意非空开集. 归纳构造非空开集 $V_n$: 由 $U_1$ 稠密, $V_0\cap{}U_1\neq\emptyset$. 取非空开 $V_1$ 使 $\overline{V_1}\subset{}V_0\cap{}U_1$ 且 $\overline{V_1}$ 紧 (由**定义 7.4 (局部紧空间)**, 局部紧豪斯多夫提供闭紧邻域基, 可在 $V_0\cap{}U_1$ 内取闭紧邻域). 归纳地, 由 $U_n$ 稠密, $V_{n-1}\cap{}U_n\neq\emptyset$, 取非空开 $V_n$ 使 $\overline{V_n}\subset{}V_{n-1}\cap{}U_n$ 且 $\overline{V_n}$ 紧.

于是 $\left\{\overline{V_n}\right\}$ 是非空紧集套. 由紧集的有限交性质 (紧空间中具有有限交性质的闭集族之交非空), 存在 $x\in\bigcap_n\overline{V_n}$. 由 $\overline{V_n}\subset{}U_n$ 与 $\overline{V_n}\subset{}V_0$, 有 $x\in{}V_0\cap\bigcap_nU_n$. 故 $V_0$ 与 $\bigcap_nU_n$ 相交. $V_0$ 任意, 由**定义 3.32 (稠密)**, $\bigcap_nU_n$ 稠密. 这正是**定理 6.13 (贝尔纲定理)** 的局部紧版本.

$\blacksquare$

## 11.2 (克罗夫特引理: 题集的版本与两份卷子的版本)

(1) 设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 连续, 且对每个 $x>0$ 序列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 收敛到 $0$. 证明 $\lim_{x\to\infty}f\left(x\right)=0$. 此结论称为克罗夫特引理;

(2) (2024 卷 A 题四) 取定 $\varepsilon>0$, 令 $F_n=\left\{x\ge0:\forall{}p\in\mathbb{N},p\ge{}n,\left|f\left(px\right)\right|\le\varepsilon\right\}$. 证明每个 $F_n$ 闭, $\bigcup_nF_n\supset\left(0,\infty\right)$, 再用贝尔纲定理由此推出 (1);

(3) (2024 卷 B 题四) 设 $\Omega\subset\left(0,\infty\right)$ 非空开且无界, 令 $\Omega_n=\left\{x\in\mathbb{R}:\exists{}p\ge{}n,px\in\Omega\right\}$. 证明每个 $\Omega_n$ 是稠密开集, 再用贝尔纲定理由此推出 (1).

题集 $\S6$ C8; 2024 卷 A 题四; 2024 卷 B 题四.

### 解答 11.2

(1) 反设结论不真. 则存在 $\varepsilon>0$ 与趋于无穷的 $x_k$ 使 $\left|f\left(x_k\right)\right|>\varepsilon$.

对 $n\ge1$ 令 $F_n=\left\{x\ge0:\forall{}p\ge{}n,\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}\right\}$. 它是闭集 (**定义 3.21 (闭集)**): 每个 $\left\{x:\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}\right\}$ 是连续函数 $\left|f\left(p\cdot\right)\right|$ 的闭水平集.

$F_n$ 覆盖 $\left(0,\infty\right)$: 固定 $x>0$, 由假设 $f\left(px\right)\to0$, 故存在 $n$ 使 $p\ge{}n$ 时 $\left|f\left(px\right)\right|\le\frac{\varepsilon}{2}$, 即 $x\in{}F_n$.

$\left(0,\infty\right)$ 是完备空间 $\mathbb{R}$ 的开子集, 故它自身是贝尔空间. 由**定理 6.13 (贝尔纲定理)**, 闭集的可数并不整个覆盖它而不留内点, 故某个 $F_N$ 含非退化区间 $\left(u,v\right)\subset\left(0,\infty\right)$.

取 $y\in\left(u,v\right)$ 固定. 对 $k$ 令 $p_k=\lfloor\frac{x_k}{y}\rfloor$. 因 $x_k\to\infty$, 有 $p_k\to\infty$, 故 $p_k\ge{}N$ 对大的 $k$ 成立; 又

$$
\frac{x_k}{p_k}=\frac{x_k}{\lfloor{}x_k/y\rfloor}\longrightarrow{}y,
$$

故 $\frac{x_k}{p_k}\in\left(u,v\right)\subset{}F_N$ 对大的 $k$ 成立. 于是 $x_k=p_k\cdot\frac{x_k}{p_k}$ 且 $p_k\ge{}N$, 由 $F_N$ 的定义 $\left|f\left(x_k\right)\right|\le\frac{\varepsilon}{2}$, 与 $\left|f\left(x_k\right)\right|>\varepsilon$ 矛盾.

$\blacksquare$

(2) 闭性同 (1). 覆盖: 固定 $x>0$, $f\left(px\right)\to0$ 故存在 $n$ 使 $p\ge{}n$ 时 $\left|f\left(px\right)\right|\le\varepsilon$, 即 $x\in{}F_n$; 于是 $\bigcup_nF_n\supset\left(0,\infty\right)$. 收尾与 (1) 完全一样, 只把 $\frac{\varepsilon}{2}$ 换成 $\varepsilon$. 这两步正是卷 A 的分法.

$\blacksquare$

(3) $\Omega_n$ 开: $\Omega_n=\bigcup_{p\ge{}n}\frac{1}{p}\Omega$, 而 $\frac{1}{p}\Omega$ 是开集在连续映射 $x\mapsto\frac{x}{p}$ 下的像, 开. 稠密: 取非退化区间 $J\subset\mathbb{R}$, 要证 $J\cap\Omega_n\neq\emptyset$. 因 $\Omega$ 无界开, 取 $q\in\Omega$ 使 $q>n\cdot\max\left\{\left|t\right|:t\in{}J\right\}$; 则 $\frac{q}{p}\in{}J$ 对某个 $p\ge{}n$ 成立 (因 $\frac{q}{p}$ 随 $p$ 从 $\frac{q}{n}$ 递减到 $0$, 而 $J$ 含区间内所有足够小的正数), 且 $p\cdot\frac{q}{p}=q\in\Omega$, 故 $\frac{q}{p}\in\Omega_n$.

由**定理 6.13 (贝尔纲定理)**, 可数个稠密开集之交稠密, 取 $x_0\in\bigcap_n\Omega_n$ 且 $x_0>0$. 则对每个 $n$ 有 $p\ge{}n$ 使 $px_0\in\Omega$; 若 $\lim_{x\to\infty}f\left(x\right)\neq0$, 取 $\varepsilon$ 与 $y_m\to\infty$ 使 $\left|f\left(y_m\right)\right|>\varepsilon$, 则那些 $px_0$ 任意大而 $f\left(px_0\right)\to0$, 与 $\Omega$ 内 $\left|f\right|$ 一致地大于 $\varepsilon$ 的取法矛盾. 严格地说: 由 $\Omega$ 与 $\varepsilon$ 的取法 (把 $\Omega$ 取成 $\left|f\right|>\varepsilon$ 的开集, 它无界), Baire 给出的 $x_0$ 使无穷多个 $px_0$ 落在 $\Omega$, 于是沿这列 $\left|f\left(px_0\right)\right|>\varepsilon$, 与 $f\left(px_0\right)\to0$ 矛盾.

$\blacksquare$

> 三个版本是同一件事的三种包装: 卷 A 用闭集 $F_n$ 逼近, 卷 B 用稠密开集 $\Omega_n$ 逼近. 反设之后必须把"沿某个 $y$ 的所有整数倍"与"给定的坏列 $x_k$"接起来, 这一步靠的是 $\frac{x_k}{\lfloor{}x_k/y\rfloor}\to{}y$.

## 11.3 (对平移量的收敛在紧区间上一致)

设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 连续, 且对每个 $\lambda\ge0$ 有 $\lim_{x\to\infty}\left(f\left(x+\lambda\right)-f\left(x\right)\right)=0$. 证明对任意 $\left[a,b\right]\subset\mathbb{R}_{\ge0}$, 该收敛对 $\lambda\in\left[a,b\right]$ 一致, 即 $\sup_{\lambda\in\left[a,b\right]}\left|f\left(x+\lambda\right)-f\left(x\right)\right|\to0$ ($x\to\infty$).

题集 $\S6$ C10.

### 解答 11.3

对 $x\ge0$ 令 $M\left(x\right)=\sup_{\lambda\in\left[a,b\right]}\left|f\left(x+\lambda\right)-f\left(x\right)\right|$. 它是有限值: 固定 $x$ 时 $\lambda\mapsto{}f\left(x+\lambda\right)-f\left(x\right)$ 在紧区间 $\left[a,b\right]$ 上连续, 故有界.

对 $\varepsilon>0$ 令 $A_\varepsilon=\left\{x\ge0:M\left(x\right)\le\varepsilon\right\}$. 它是闭集: $M$ 是连续函数族 $\left(x,\lambda\right)\mapsto\left|f\left(x+\lambda\right)-f\left(x\right)\right|$ 对紧参数 $\lambda$ 取上确界, 故 $M$ 下半连续, 而下半连续函数的 $\left\{M\le\varepsilon\right\}$ 是闭集.

覆盖: $\bigcup_{\varepsilon>0}A_\varepsilon=\left[0,\infty\right)$, 由上面的有限性.

由**定理 6.13 (贝尔纲定理)**, 在完备空间 $\left[0,\infty\right)$ 中, 对任意非退化区间 $J\subset\left(0,\infty\right)$, 闭集族 $\left\{A_{1/n}\cap{}J\right\}$ 覆盖 $J$ 且 $J$ 完备, 故某个 $A_{1/n}\cap{}J$ 含 $J$ 中的非退化区间. 于是

$$
D_\varepsilon=\bigcup_{n}\operatorname{int}\left(A_\varepsilon\right)
$$

在每个 $J$ 中非空, 故稠密; 它开, 故稠密开.

下面用稠密性把 $M$ 压到 $0$. 反设 $\lim_{x\to\infty}M\left(x\right)=0$ 不成立: 存在 $\varepsilon>0$ 与属于某一个 $x_k\to\infty$ 的序列, 使 $M\left(x_k\right)>3\varepsilon$, 即存在 $\lambda_k\in\left[a,b\right]$ 使 $\left|f\left(x_k+\lambda_k\right)-f\left(x_k\right)\right|>3\varepsilon$.

固定 $k$. 函数 $f$ 在紧区间 $\left[x_k,x_k+b\right]$ 上一致连续, 故存在 $\delta_k>0$ 使 $\left|u-v\right|\le\delta_k$ 且 $u,v\in\left[x_k,x_k+b\right]$ 时 $\left|f\left(u\right)-f\left(v\right)\right|\le\varepsilon$. 对 $y\in\left(x_k-\delta_k,x_k+\delta_k\right)$ 与 $\lambda\in\left[a,b\right]$,

$$
\left|f\left(y+\lambda\right)-f\left(y\right)\right|\ge\left|f\left(x_k+\lambda\right)-f\left(x_k\right)\right|-2\varepsilon>3\varepsilon-2\varepsilon=\varepsilon,
$$

其中用到了 $\left|y+\lambda-\left(x_k+\lambda\right)\right|=\left|y-x_k\right|\le\delta_k$. 故 $M\left(y\right)>\varepsilon$ 对整个区间 $\left(x_k-\delta_k,x_k+\delta_k\right)$ 成立, 即该区间与 $D_\varepsilon$ 不交. 但 $D_\varepsilon$ 稠密, 任何非空开区间必与它相交, 矛盾.

$\blacksquare$

> 一致性不能从"每个 $\lambda$ 都收敛"直接读出, 因为对 $\lambda$ 的收敛可能被 $\lambda$ 的微小移动放大; 贝尔纲在这里的作用就是禁止这种放大发生在任意大的 $x$ 处.

## 11.4 (完备度量空间上严格压缩映射的不动点)

设 $\left(X,d\right)$ 是非空完备度量空间, $f:X\to{}X$ 是严格压缩的, 即存在 $0<{}k<1$ 使对一切 $x,y\in{}X$ 有 $d\left(f\left(x\right),f\left(y\right)\right)\le{}k\,d\left(x,y\right)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in{}X$ 使 $f\left(x\right)=x$.

题集 §4.3 Q1.

### 解答 11.4

任取初值 $x_0\in{}X$, 迭代 $x_{n+1}=f\left(x_n\right)$. 由压缩条件,

$$
d\left(x_{n+1},x_n\right)=d\left(f\left(x_n\right),f\left(x_{n-1}\right)\right)\le{}k\,d\left(x_n,x_{n-1}\right)\le\cdots\le{}k^nd\left(x_1,x_0\right).
$$

对 $m>n$, 由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x_m,x_n\right)\le\sum_{j=n}^{m-1}d\left(x_{j+1},x_j\right)\le{}d\left(x_1,x_0\right)\sum_{j=n}^{\infty}k^j=\frac{k^n}{1-k}d\left(x_1,x_0\right).
$$

右端当 $n\to\infty$ 时趋于 $0$, 故 $\left(x_n\right)$ 是**定义 6.37 (柯西列)**. 由 $X$ 是**定义 6.38 (完备度量空间)**, $x_n\to{}x\in{}X$. 压缩映射满足 $d\left(f\left(x_n\right),f\left(x\right)\right)\le{}k\,d\left(x_n,x\right)\to0$, 即 $f$ 连续, 故 $f\left(x_n\right)\to{}f\left(x\right)$; 但 $f\left(x_n\right)=x_{n+1}\to{}x$, 由极限唯一性得 $f\left(x\right)=x$.

唯一性: 若 $f\left(x\right)=x$, $f\left(y\right)=y$, 则 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)\le{}k\,d\left(x,y\right)$, 而 $0<{}k<1$, 故 $d\left(x,y\right)=0$, 由**定义 6.35 (度量空间)** 的正定性得 $x=y$. 这就是**定理 6.16 (巴拿赫不动点定理)**.

$\blacksquare$

## 11.5 (连续线性映射的利普希茨估计)

设 $\left(E,\left\|\cdot\right\|\right)$ 是域 $\mathbb{K}$ 上的赋范线性空间, $f:E\to{}E$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in{}E$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{}K\left\|x-y\right\|$.

题集 §4.3 Q2.

### 解答 11.5

由 $f$ 在 $0$ 连续 (按**定义 3.22 (连续映射)**, $\left\|z\right\|\to0$ 时 $\left\|f\left(z\right)\right\|\to0$), 存在 $\delta>0$, 使 $\left\|z\right\|<\delta$ 时 $\left\|f\left(z\right)\right\|\le1$. 对任意 $x\neq0$, 令 $z=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|z\right\|=\delta/2<\delta$, 故 $\left\|f\left(z\right)\right\|\le1$. 由线性性,

$$
\left\|f\left(x\right)\right\|=\frac{2\left\|x\right\|}{\delta}\left\|f\left(z\right)\right\|\le\frac{2}{\delta}\left\|x\right\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f\left(x\right)-f\left(y\right)=f\left(x-y\right)$, 故

$$
\left\|f\left(x\right)-f\left(y\right)\right\|=\left\|f\left(x-y\right)\right\|\le{}K\left\|x-y\right\|.
$$

$\blacksquare$

## 11.6 (压缩映射 $g_a$ 与解算子 $J$)

沿用习题 11.5 的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb{K}$ 满足 $\left|\lambda\right|>K$, 固定 $a\in{}E$, 映射

$$
g_a\left(x\right)=\frac{a-f\left(x\right)}{\lambda}
$$

是压缩映射; 用巴拿赫不动点定理推出 $g_a$ 有唯一不动点 $J\left(a\right)\in{}E$.

题集 §4.3 Q3.

### 解答 11.6

对 $x,y\in{}E$, 由习题 11.5,

$$
\left\|g_a\left(x\right)-g_a\left(y\right)\right\|=\frac{\left\|f\left(x\right)-f\left(y\right)\right\|}{\left|\lambda\right|}\le\frac{K}{\left|\lambda\right|}\left\|x-y\right\|.
$$

由假设 $\left|\lambda\right|>K$, 故 $k=K/\left|\lambda\right|<1$. 由**定义 6.19 (压缩映射)**, $g_a$ 是压缩映射. $E$ 非空且是**定义 6.38 (完备度量空间)**, 由**定理 6.16 (巴拿赫不动点定理)**, $g_a$ 有唯一不动点, 记为 $J\left(a\right)$.

$\blacksquare$

## 11.7 (解算子 $J$ 的利普希茨估计)

证明 $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$.

题集 §4.3 Q4.

### 解答 11.7

由 $J\left(a\right)$ 与 $J\left(b\right)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J\left(a\right)=\frac{a-f\left(J\left(a\right)\right)}{\lambda},\quad{}J\left(b\right)=\frac{b-f\left(J\left(b\right)\right)}{\lambda}.
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

## 11.8 (方程 $f\left(x\right)-\lambda{}x=a$ 的唯一可解性与解的连续性)

总结如下结论: 对任意连续线性映射 $f:E\to{}E$, 存在 $K>0$, 使对一切满足 $\left|\lambda\right|>K$ 的 $\lambda$ 与一切 $a\in{}E$, 方程 $f\left(x\right)-\lambda{}x=a$ (未知量 $x\in{}E$) 有唯一解 $J\left(a\right)$, 且映射 $a\mapsto{}J\left(a\right)$ 连续.

题集 §4.3 Q5.

### 解答 11.8

由习题 11.5, 存在 $K>0$ 使 $\left\|f\left(x\right)-f\left(y\right)\right\|\le{}K\left\|x-y\right\|$. 设 $\left|\lambda\right|>K$. 方程 $f\left(x\right)-\lambda{}x=a$ 等价于

$$
x=\frac{a-f\left(x\right)}{\lambda}=g_a\left(x\right).
$$

由习题 11.6, $g_a$ 是**定义 6.19 (压缩映射)**, 由**定理 6.16 (巴拿赫不动点定理)**, 该方程有唯一解 $J\left(a\right)$.

$\blacksquare$

由习题 11.7, $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$, 即 $J$ 是利普希茨映射. 由利普希茨映射连续, $J$ 连续.

$\blacksquare$

## 11.9 (交集的规范函数是各规范函数的上确界)

设 $E$ 是 $\mathbb{K}$ 上拓扑向量空间, $C$ 是 $0$ 的凸邻域, 规范函数 $\left\|\cdot\right\|_C:E\to\left[0,\infty\right)$ 由规范函数给出. 若 $\left\{C_\alpha\right\}_{\alpha\in{}A}$ 是 $E$ 中一族凸集且其交是 $0$ 的凸邻域, 证明

$$
\left\|\cdot\right\|_{\bigcap_{\alpha\in{}A}C_\alpha}=\sup_{\alpha\in{}A}\left\|\cdot\right\|_{C_\alpha}.
$$

题集 §5 Q14.

### 解答 11.9

记 $C=\bigcap_{\alpha\in{}A}C_\alpha$. 由**定义 6.27 (规范函数)**,

$$
\left\|x\right\|_C=\inf\left\{t>0:x\in{}tC\right\}=\inf\left\{t>0:\;x\in{}tC_\alpha\;\text{对一切}\;\alpha\right\}.
$$

而 $x\in{}tC_\alpha$ 当且仅当 $t\ge\left\|x\right\|_{C_\alpha}$ (规范函数的次水平集刻画). 故同时对一切 $\alpha$ 成立当且仅当

$$
t\ge\sup_{\alpha\in{}A}\left\|x\right\|_{C_\alpha}.
$$

取下确界即得

$$
\left\|x\right\|_C=\sup_{\alpha\in{}A}\left\|x\right\|_{C_\alpha}.
$$

两边对一切 $x\in{}E$ 成立, 故函数相等.

$\blacksquare$

## 12.1 (复合映射的算子范数与 $E\cong{}L\left(\mathbb{K},E\right)$)

设 $E,F,G$ 是赋范域 $\mathbb{K}$ 上的拓扑向量空间. 对 $f\in{}L\left(E,F\right)$, 右复合映射 $R_f:L\left(F,G\right)\to{}L\left(E,G\right)$, $g\mapsto{}g\circ{}f$. 证明:

(1) $R_f$ 的算子范数不超过 $f$ 的算子范数, 左复合同理;

(2) 映射 $E\to{}L\left(\mathbb{K},E\right)$, $x\mapsto\left(\varphi_x:t\mapsto{}tx\right)$ 是等距线性同构.

题集 §5 Q15.

### 解答 12.1

由**定义 6.24 (拓扑向量空间)**, $E,F,G$ 的加法与数乘连续; 由**定义 6.20 (赋范线性空间)**, 其上装备范数, $L\left(E,F\right)$ 为连续线性映射全体.

(1) 右复合: 由**定义 6.28 (算子范数)**, 对 $g\in{}L\left(F,G\right)$ 与 $x\in{}E$, $g\circ{}f$ 作为复合映射由**定理 3.1 (复合连续)** 连续, 且

$$
\left\|g\circ{}f\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\right\|\cdot\left\|x\right\|.
$$

两边除以 $\left\|x\right\|$ 并取上确界, 得 $\left\|g\circ{}f\right\|\le\left\|g\right\|\left\|f\right\|$. 于是 $\left\|R_f\left(g\right)\right\|\le\left\|f\right\|\left\|g\right\|$, 即 $\left\|R_f\right\|\le\left\|f\right\|$.

左复合: 同理, $L_f:g\mapsto{}f\circ{}g$ ($g\in{}L\left(G,E\right)$, $f\in{}L\left(E,F\right)$), 有 $\left\|f\circ{}g\right\|\le\left\|f\right\|\left\|g\right\|$, 故 $\left\|L_f\right\|\le\left\|f\right\|$.

$\blacksquare$

(2) 等距线性同构: 映射 $x\mapsto\varphi_x$, $\varphi_x\left(t\right)=tx$. 线性显然. 由**定义 6.28 (算子范数)**,

$$
\left\|\varphi_x\right\|=\sup_{\left\|t\right\|\le1}\left\|tx\right\|=\sup_{\left\|t\right\|\le1}\left|t\right|\cdot\left\|x\right\|=\left\|x\right\|.
$$

故等距. 它线性且保范数, 故单射; 满射: 任意 $\psi\in{}L\left(\mathbb{K},E\right)$ 由 $\psi\left(1\right)\in{}E$ 决定, 即 $\psi=\varphi_{\psi\left(1\right)}$. 故为线性同构.

$\blacksquare$
