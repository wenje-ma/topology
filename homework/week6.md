# week6

> **定理 3.5 (闭包与极限点)**
> 
> $A$ 的闭包是 $A$ 与其全体极限点之并: $\overline{A}=A\cup{A}'$. (教材 $\S3$, 定理 3.5)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.11 (乘积拓扑)**
> 
> 设 $X,Y$ 为拓扑空间. $X\times{Y}$ 上的乘积拓扑以形如 $U\times{V}$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in{V}}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$, p17)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{X}$ 是开的当且仅当 $U\in{T}$. 我们要求:
> 
> (1) $\emptyset,X\in{T}$;
> 
> (2) 若 $U,V\in{T}$, 则 $U\cap{V}\in{T}$;
> 
> (3) 若 $A\subset{T}$, 则 $\bigcup{A}\in{T}$. (教材 $\S3$, p12)

> **定义 3.19 (子空间拓扑)**
> 
> 设 $\left(X,\mathcal{O}_X\right)$ 为拓扑空间, $A\subset{X}$, $\iota:A\to{X}$ 为包含映射. 称 $U\subset{A}$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap{A}$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 §3, p17; 题集 §1.2)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.24 (极限点)**
> 
> 称 $x$ 是 $A$ 的极限点, 若 $x$ 的每个邻域都含有 $A$ 中异于 $x$ 的点. (教材 $\S3$, p18)

> **定义 3.25 (邻域与极限)**
> 
> $b\in{X}$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to{b}$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in{U}$. (教材 $\S3$, p16)

> **定义 3.26 (闭包)**
> 
> 集合 $A\subset{X}$ 的闭包 $\overline{A}$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **命题 3.33 (点态收敛判据)**
> 
> 设 $X=A^{S}$ 赋乘积拓扑. 则序列 $f_n\in{X}$ 收敛到 $g$, 当且仅当对一切 $s\in{S}$ 有 $f_n\left(s\right)\to{g}\left(s\right)$; 乘积拓扑在 $X=A^{S}$ 的情形又叫点态收敛拓扑. (教材 $\S3$, p22)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $\boldsymbol{x},\boldsymbol{y}\in{K}$ 蕴含线段 $\left(1-t\right)\boldsymbol{x}+t\boldsymbol{y}$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3 ($\mathbb{R}^n$ 中的紧集)**
> 
> $K\subset\mathbb{R}^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4 (闭子集紧)**
> 
> 若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset{X}$ 也紧致. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.6))

> **定理 5.9 (吉洪诺夫定理)**
> 
> 任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.11 (紧空间上连续函数取最大值)**
> 
> 紧致空间 $X$ 上的连续函数 $f:X\to\mathbb{R}$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 5.15 (开覆盖与有限子覆盖)**
> 
> 开覆盖 $\left\{U_i\right\}$ 满足 $X=\bigcup_iU_i$; 有限子覆盖为仍覆盖 $X$ 的有限子族. (教材 $\S5$)

> **定义 5.16 (紧致空间)**
> 
> 称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17 (有限交性质)**
> 
> 闭集族 $\mathcal{F}$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.17 (里茨定理)**
> 
> 无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定义 6.20 (赋范线性空间)**
> 
> 向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

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

> **定义 6.40 (序列紧致)**
> 
> 称 $X$ 是序列紧致的, 若 $X$ 中每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; "拓扑学"(原书第2版) $\S29$)

> **定义 7.5 (单点紧化)**
> 
> 亚历山德罗夫紧化 $\overline{X}=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset{X}$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

## 6.4 (商映射保持连通性, 路径连通性与局部连通性)

设 $X$ 是拓扑空间, $\pi:X\to{Y}$ 是商映射, $Y$ 配以由 $\pi$ 诱导的商拓扑.

(1) 证明若 $X$ 连通, 则 $Y$ 连通;

(2) 证明若 $X$ 路径连通, 则 $Y$ 路径连通;

(3) 证明若 $\pi$ 是开映射且 $X$ 局部连通 (局部路径连通), 则 $Y$ 局部连通 (局部路径连通).

题集 §5 Q3.

### 解答 6.4

(1) 反证. 若 $Y$ 不连通, 由**定义 4.18 (连通空间)** 存在不相交非空开集 $V,W\subset{Y}$ 使 $Y=V\sqcup{W}$. 由**定义 11.2 (粘合映射)**, $\pi^{-1}\left(V\right)$ 与 $\pi^{-1}\left(W\right)$ 是 $X$ 中不相交非空开集, 且 $X=\pi^{-1}\left(V\right)\cup\pi^{-1}\left(W\right)$. 由**定义 4.18 (连通空间)**, 这与 $X$ 连通矛盾. 故 $Y$ 连通.

$\blacksquare$

(2) 任取 $y_1,y_2\in{Y}$, 取原像 $x_1,x_2\in{X}$. 由 $X$ 路径连通与**定义 4.22 (路径连通)**, 存在连续路径 $\gamma:\left[0,1\right]\to{X}$ 以 $x_1,x_2$ 为端点. 由**定理 3.1 (复合连续)**, $\pi\circ\gamma:\left[0,1\right]\to{Y}$ 连续, 且端点为 $y_1,y_2$. 故 $Y$ 路径连通.

$\blacksquare$

(3) 只证局部连通情形, 局部路径连通完全平行. 任取 $y\in{Y}$ 与由**定义 3.25 (邻域与极限)** 给出的开邻域 $O\subset{Y}$. 取 $x\in\pi^{-1}\left(y\right)$. 由**定义 11.2 (粘合映射)**, $\pi^{-1}\left(O\right)$ 是 $x$ 的开邻域. 由 $X$ 局部连通与**定义 4.9 (局部连通)**, 存在连通开集 $U\subset{X}$ 使 $x\in{U}\subset\pi^{-1}\left(O\right)$. 因 $\pi$ 是开映射, $\pi\left(U\right)$ 是 $Y$ 中开集; 它含 $y$, 含于 $O$, 且由**定理 4.2 (连续像连通)** 它连通. 故 $y$ 有含于 $O$ 的连通开邻域, $Y$ 局部连通.

$\blacksquare$

## 6.5 (无穷维赋范空间中紧集的补集道路连通)

设 $E$ 是无穷维赋范线性空间, $K\subset{E}$ 是紧集. 证明:

(1) $E\setminus{K}$ 道路连通;

(2) 问有限维赋范线性空间中此结论是否成立?

题集 §6 C1.

### 解答 6.5

(1) 无穷维情形: 由**定理 6.17 (里茨定理)**, 无穷维赋范线性空间的闭单位球非紧, 故任何紧集 $K$ 必无内部 (否则 $K$ 含某闭球的平移, 该闭球紧, 与里茨定理矛盾). 任取 $x,y\in{E}\setminus{K}$. 由**定义 6.46 (点到集合的距离)**, $d\left(x,K\right)>0$. 考虑从 $x$ 出发的指向某方向的单位向量, 保证其沿该方向延长却永远与 $K$ 不相交, 设向量延长到 $z$; $y$ 同理, 设向量延长到 $z'$. 最后在远离 $K$ 的地方用直线段 $\left[z,z'\right]$ 连接. 所得折线 $x\to{z}\to{z}'\to{y}$ 由**定义 4.22 (路径连通)** 是连续路径, 且全段避开 $K$. 故 $E\setminus{K}$ 道路连通.

$\blacksquare$

(2) 有限维情形: 结论不成立. 取 $E=\mathbb{R}^2$, $K=S^1=\left\{\left(u,v\right):u^2+v^2=1\right\}$. $S^1$ 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 是闭有界集, 故紧. 但 $\mathbb{R}^2\setminus{S}^1=\left\{u^2+v^2<1\right\}\cup\left\{u^2+v^2>1\right\}$ 是两个非空不相交开集之并, 由**定义 4.18 (连通空间)** 不连通, 因而不道路连通.

$\blacksquare$

> 由此可见, 无穷维赋范线性空间中的任何紧集都是很小的, 而有限维则不然, 存在与边界相交的紧集把空间一分为二.

## 6.6 (等值集皆紧的连续函数必取到极值)

设 $f:\mathbb{R}^n\to\mathbb{R}$ 连续, $n\ge2$, 且对每个 $a\in\mathbb{R}$, 等值集 $f^{-1}\left(a\right)$ 紧. 证明:

(1) $f$ 取得全局极值 (上确界或下确界之一达到);

(2) 问 $n=1$ 时结论如何?

题集 §6 C2.

### 解答 6.6

(1) 取定 $a$ 使 $f^{-1}\left(a\right)\neq\emptyset$ (若非空), 即存在 $\boldsymbol{x}_0$ 使 $f\left(\boldsymbol{x}_0\right)=a$. 由假设 $f^{-1}\left(a\right)$ 紧, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 它是闭有界集, 故存在 $R>0$ 使 $f^{-1}\left(a\right)\subset{B}\left(0,R\right)$.

球面 $\partial{B}\left(0,R\right)$ 在 $n\ge2$ 时连通 (它是 $\mathbb{R}^n$ 中连通紧集). 由**定义 3.22 (连续映射)**, $f\left(\partial{B}\left(0,R\right)\right)$ 是 $\mathbb{R}$ 中不含 $a$ 的连通集; 由**定理 4.2 (连续像连通)** 它连通, 故必全在 $\left(a,\infty\right)$ 或全在 $\left(-\infty,a\right)$ 中. 不妨设 $f>a$ 在 $\partial{B}\left(0,R\right)$ 上.

反证: 假设 $f$ 既无全局最大值也无全局最小值. 由 $f$ 无最小值, 存在 $\boldsymbol{x}$ 使 $f\left(\boldsymbol{x}\right)<{}a$. 若 $\left\|\boldsymbol{x}\right\|>R$, 考虑从 $\boldsymbol{x}$ 到球心 $0$ 的径向线段; 由**定理 4.1 (区间连通)** 该线段连通, 其上 $f$ 连续, 在端点 $\boldsymbol{x}$ 处 $f<{}a$, 在球面处 $f>a$, 由连续函数的介值定理 必有点 $\boldsymbol{p}$ 在该线段上使 $f\left(\boldsymbol{p}\right)=a$ 且 $\left\|\boldsymbol{p}\right\|>R$, 这与 $f^{-1}\left(a\right)\subset{B}\left(0,R\right)$ 矛盾. 故 $f$ 无最小值只能在 $\left\|\boldsymbol{x}\right\|<{}R$ 内发生.

于是在紧集 $\overline{B}\left(0,R\right)$ 上由**定理 5.11 (紧空间上连续函数取最大值)**, $f$ 取得最大值与最小值; 而在 $\mathbb{R}^n\setminus\overline{B}\left(0,R\right)$ 上 $f>a$, 故 $f$ 在 $\overline{B}\left(0,R\right)$ 上取得的最小值就是全局最小值. 故 $f$ 取得全局极值, 与假设矛盾.

$\blacksquare$

(2) $n=1$: 结论不成立. 取 $f\left(x\right)=x$, 则 $f^{-1}\left(a\right)=\left\{a\right\}$ 是单点集紧, 但 $f:\mathbb{R}\to\mathbb{R}$ 既无最大值也无最小值.

$\blacksquare$

## 6.7 (超平面的补集道路连通当且仅当超平面不闭)

设 $E$ 是赋范线性空间, $H$ 是超平面. 证明 $E\setminus{H}$ 道路连通当且仅当 $H$ 不是闭集.

题集 §6 C4.

### 解答 6.7

取线性泛函 $\varphi$ 使 $H=\ker\varphi$ (习题 12.18). 记

$$
H^{-}=\varphi^{-1}\left(\left(-\infty,0\right)\right),\quad{H}^{+}=\varphi^{-1}\left(\left(0,\infty\right)\right).
$$

由 $\varphi$ 线性, $H^{-}$ 与 $H^{+}$ 都是凸集, 由**定义 4.23 (凸集)** 它们道路连通.

($H$ 闭 $\Rightarrow$ $E\setminus{H}$ 不道路连通): 由习题 12.18, $H$ 闭时 $\varphi$ 连续. 由**定义 3.22 (连续映射)**, $H^{-}$ 与 $H^{+}$ 都是开集, 且 $E\setminus{H}=H^{-}\sqcup{H}^{+}$ 是两个非空不相交开集之并. 由**定义 4.18 (连通空间)**, $E\setminus{H}$ 不连通, 故不道路连通. 直观地, 若有连续路径 $\gamma:\left[0,1\right]\to{E}\setminus{H}$ 从 $H^{-}$ 到 $H^{+}$, 则 $\varphi\circ\gamma$ 是**定理 4.1 (区间连通)** 上的连续实函数, 在两端异号, 由连续函数的介值定理 必取 $0$, 即某 $\gamma\left(t\right)\in{H}$, 矛盾.

$\blacksquare$

($H$ 不闭 $\Rightarrow$ $E\setminus{H}$ 道路连通): 由习题 12.18, $H$ 不闭时 $\varphi$ 不连续, 此时 $\overline{H}=E$ (即 $H$ 在 $E$ 中稠密). 取 $e\in{E}$ 使 $\varphi\left(e\right)=1$. 则 $\varphi^{-1}\left(1\right)=e+H$ 在 $E$ 中稠密 (平移不改变稠密性). 任取 $-e\in{H}^{-}$ ($\varphi\left(-e\right)=-1$), 由**定义 3.32 (稠密)** 可取序列 $x_n\in{e}+H$ 使 $x_n\to-e$, 且不妨设 $x_1=e$.

定义路径 $\gamma:\left[0,1\right]\to{E}$: 在 $t\in\left[1/\left(k+1\right),1/k\right]$ 上, $\gamma$ 沿直线段从 $x_{k+1}$ 走到 $x_k$, 并令 $\gamma\left(0\right)=-e$. 因 $x_n\to-e$, 该折线在 $0$ 处连续. 对 $t>0$, $\gamma\left(t\right)\in{e}+H$, 故 $\varphi\left(\gamma\left(t\right)\right)=1$; 而 $\varphi\left(\gamma\left(0\right)\right)=\varphi\left(-e\right)=-1$. 故 $\gamma$ 全段在 $E\setminus{H}$ 中, 从 $-e$ 连到 $e$. 由**定义 4.22 (路径连通)**, $H^{-}$ 与 $H^{+}$ 各自道路连通, 任意两点可经 $-e\to{e}$ 折线互相连通. 故 $E\setminus{H}$ 道路连通.

$\blacksquare$

## 6.8 (不动点性质, 截面连通与 $\left[0,1\right]$ 上映射的不动点)

(1) 设 $\left(E,d\right)$ 是度量空间, 且每个连续映射 $f:E\to{E}$ 都有**定义 4.17 (不动点)**. 证明 $E$ 连通.

(2) 设 $K\subset\left[0,1\right]^2$ 闭, 且对每个 $x\in\left[0,1\right]$, 截面 $K_x=\left\{y\in\left[0,1\right]:\left(x,y\right)\in{K}\right\}$ 是非平凡区间. 证明 $K$ 连通. 进一步证明存在 $x\in\left[0,1\right]$ 使 $x\in{K}_x$.

(3) 设 $f:\left[0,1\right]\to\left[0,1\right]$.

(a) 设 $f$ 非递减 (不必连续). 证明 $f$ 有不动点.
(b) 设 $f$ 连续 (不必递增). 证明 $f$ 有不动点.
(c) 设 $f,g:\left[0,1\right]\to\left[0,1\right]$ 连续且 $f\circ{g}=g\circ{f}$. 证明存在 $a\in\left[0,1\right]$ 使 $f\left(a\right)=g\left(a\right)$.

(4) 设 $f:\mathbb{R}\to\mathbb{R}$ 连续, 且 $f\circ{f}$ 有不动点. 证明 $f$ 有不动点.

题集 §7.2 (三题).

### 解答 6.8

(1) 反证. 若 $E$ 不连通, 由**定义 4.18 (连通空间)**, $E=U\sqcup{V}$, 其中 $U,V$ 是非空不相交开集. 取 $u\in{U}$, $v\in{V}$. 定义 $f:E\to{E}$ 为 $f\left(U\right)=\left\{v\right\}$, $f\left(V\right)=\left\{u\right\}$. 由**定义 3.22 (连续映射)**, $f$ 连续 (常值映射在开集上连续, 拼接不相交开集). 但 $f$ 无不动点: 对 $x\in{U}$, $f\left(x\right)=v\notin{U}$; 对 $x\in{V}$, $f\left(x\right)=u\notin{V}$. 矛盾. 故 $E$ 连通.

$\blacksquare$

(2) 证明任一连续 $h:K\to\left\{0,1\right\}$ 常值. 对固定 $x$, $K_x$ 是区间故连通 (由**定理 4.1 (区间连通)** 与**定义 4.18 (连通空间)**), $h|_{K_x}$ 连续像连通, 故常值, 记为 $g\left(x\right)$. 下证 $g$ 局部常值. 若不然, 存在 $x_n\to{x}$ 但 $g\left(x_n\right)\neq{g}\left(x\right)$. 取 $y_n\in{K}_{x_n}$. 由 $K$ 紧 ($\left[0,1\right]^2$ 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 紧, $K$ 是其闭子集, 由**定理 5.4 (闭子集紧)** 紧), 存在子列 $\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in{K}$. 由 $h$ 连续,

$$
g\left(x\right)=h\left(x,y\right)=\lim_nh\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)=\lim_ng\left(x_{\varphi\left(n\right)}\right),
$$

而 $\left\{0,1\right\}$ 离散, 故 $g\left(x_{\varphi\left(n\right)}\right)$ 最终等于 $g\left(x\right)$, 矛盾. 故 $g$ 局部常值. 由**定义 4.21 (局部常值函数)** 与 $\left[0,1\right]$ 连通 (**定理 4.1 (区间连通)**), $g$ 常值, 从而 $h$ 常值. 由**定义 4.18 (连通空间)** $K$ 连通.

$\blacksquare$

进一步证明存在 $x$ 使 $x\in{K}_x$. 定义 $F=\left\{x\in\left[0,1\right]:\inf{K}_x\ge{x}\right\}$ 与 $G=\left\{x\in\left[0,1\right]:\sup{K}_x\le{x}\right\}$. 二者闭. 若 $F\cap{G}=\emptyset$, 则 $\left[0,1\right]=F\sqcup\left(\left[0,1\right]\setminus{F}\right)$, 但 $0\in{F}$ (因 $\inf{K}_0\ge0$) 且 $1\in{G}$ (因 $\sup{K}_1\le1$), 由连通性必有某点 $x\in{F}\cap{G}$, 即 $\inf{K}_x\ge{x}$ 且 $\sup{K}_x\le{x}$, 故 $x\in{K}_x$.

$\blacksquare$

(3) (a) 令 $A=\left\{x\in\left[0,1\right]:x\le{f}\left(x\right)\right\}$. $0\in{A}$. 令 $a=\sup{A}$. 对 $x\in{A}$, $x\le{f}\left(x\right)\le{f}\left(a\right)$ (由 $f$ 非递减且 $x\le{a}$), 故 $a\le{f}\left(a\right)$. 于是 $f\left(a\right)\le{f}\left(f\left(a\right)\right)$, 即 $f\left(a\right)\in{A}$, 故 $f\left(a\right)\le{a}$. 因而 $f\left(a\right)=a$. 由**定义 4.17 (不动点)**, $a$ 是不动点.

$\blacksquare$

(b): 令 $h\left(x\right)=f\left(x\right)-x$. $h\left(0\right)=f\left(0\right)\ge0$, $h\left(1\right)=f\left(1\right)-1\le0$. 由**定理 4.1 (区间连通)** 与连续函数的介值定理, 存在 $a$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=a$.

$\blacksquare$

(c): 由 (b), $f$ 有不动点集 $E=\left\{x:f\left(x\right)=x\right\}$ 非空. 对 $x\in{E}$, $f\left(g\left(x\right)\right)=g\left(f\left(x\right)\right)=g\left(x\right)$, 故 $g\left(x\right)\in{E}$. 令 $m=\inf{E}$, $M=\sup{E}$. $E$ 闭 (由 $f-\operatorname{id}$ 连续), 故 $m,M\in{E}$. 考虑 $h=f-g$. $h\left(m\right)=f\left(m\right)-g\left(m\right)=m-g\left(m\right)$. 因 $g\left(m\right)\in{E}$, $g\left(m\right)\ge{m}$, 故 $h\left(m\right)\le0$. 同理 $h\left(M\right)=M-g\left(M\right)\ge0$. 由连续函数的介值定理, 存在 $a\in\left[m,M\right]\subset{E}$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=g\left(a\right)$.

$\blacksquare$

(4): 设 $f\circ{f}$ 有不动点 $p$, 即 $f\left(f\left(p\right)\right)=p$. 若 $f\left(p\right)=p$, 则 $p$ 已是 $f$ 的不动点. 若 $f\left(p\right)\neq{p}$, 令 $h\left(x\right)=f\left(x\right)-x$. 则 $h\left(p\right)=f\left(p\right)-p$ 与 $h\left(f\left(p\right)\right)=f\left(f\left(p\right)\right)-f\left(p\right)=p-f\left(p\right)$ 异号. 由**定理 4.1 (区间连通)** 与连续函数的介值定理, $h$ 在 $p$ 与 $f\left(p\right)$ 之间有零点 $a$, 即 $f\left(a\right)=a$.

$\blacksquare$

## 7.1 (无界闭凸集含一条从原点出发的无穷射线)

考虑一个 $\mathbb{R}^2$ 中的闭集 $A$. 还假设 $A$ 是一个凸集, 原点 $O\in{A}$, 并且 $A$ 不是有界的.

(1) (10 分) 证明对于任意的正整数 $p\ge1$, 都存在一个点 $M_p\in{A}$, 线段 $OM_p$ 属于 $A$, 并且其长度 $\left|OM_p\right|\ge{p}$.

(2) (10 分) 记线段 $OM_p$ 与单位圆周的交点为 $u_p$. 证明存在一个 $\left\{u_p\right\}_{p\ge1}$ 的子列收敛到单位圆周上的某一点 $u$.

(3) (10 分) 证明 $A$ 包含一条从原点出发的长度无穷的半直线.

卷 B 题三.

### 解答 7.1

(1) 因 $A$ 无界, 对每个 $p$, 存在 $\boldsymbol{M}_p\in{A}$ 使 $\left|\boldsymbol{M}_p\right|\ge{p}$ (否则 $A$ 含于半径 $p$ 的球内, 有界). 由**定义 4.23 (凸集)**, $O\in{A}$ 与 $\boldsymbol{M}_p\in{A}$ 的连线线段 $O\boldsymbol{M}_p$ 含于 $A$, 且其长度 $\left|O\boldsymbol{M}_p\right|=\left|\boldsymbol{M}_p\right|\ge{p}$.

$\blacksquare$

(2) 令 $r_p=\left|\boldsymbol{M}_p\right|$, $\boldsymbol{u}_p=\frac{\boldsymbol{M}_p}{r_p}$, 则 $\boldsymbol{u}_p$ 在单位圆周 $S^1=\left\{\boldsymbol{v}\in\mathbb{R}^2:\left|\boldsymbol{v}\right|=1\right\}$ 上. $S^1$ 闭且有界, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** $S^1$ 紧. 由**定理 6.1 (紧 $=$ 序列紧)**, 序列 $\left(\boldsymbol{u}_p\right)\subset{S}^1$ 有收敛子列 $\boldsymbol{u}_{p_j}\to\boldsymbol{u}\in{S}^1$.

$\blacksquare$

(3) 固定 $\lambda\ge0$. 对充分大的 $j$, $r_{p_j}\ge\lambda$ (因 $r_{p_j}\ge{p}_j\to\infty$). 由**定义 4.23 (凸集)**, $\lambda\boldsymbol{u}_{p_j}=\frac{\lambda}{r_{p_j}}\boldsymbol{M}_{p_j}+\left(1-\frac{\lambda}{r_{p_j}}\right)O$ 是 $\boldsymbol{M}_{p_j}$ 与 $O$ 的凸组合, 故 $\lambda\boldsymbol{u}_{p_j}\in{A}$. 当 $j\to\infty$, $\boldsymbol{u}_{p_j}\to\boldsymbol{u}$, 故 $\lambda\boldsymbol{u}_{p_j}\to\lambda\boldsymbol{u}$. 因 $A$ 闭 (由**定义 3.21 (闭集)**, 闭集含其序列极限), $\lambda\boldsymbol{u}\in{A}$. 由 $\lambda\ge0$ 任意, 半直线 $\left\{\lambda\boldsymbol{u}:\lambda\ge0\right\}\subset{A}$, 即 $A$ 含一条从原点出发的无穷长半直线.

$\blacksquare$

## 7.2 ($\left\{0,1\right\}^{\left[0,1\right]}$ 在乘积拓扑下不序列紧)

证明 $\left\{0,1\right\}^{\left[0,1\right]}$ 赋通常乘积拓扑不是序列紧致的.

题集 §3.1 Q1.

### 解答 7.2

把 $\left\{0,1\right\}^{\left[0,1\right]}$ 中的点视为函数 $f:\left[0,1\right]\to\left\{0,1\right\}$. 由**定义 3.11 (乘积拓扑)** 与**命题 3.33 (点态收敛判据)**, 在乘积拓扑下 $f_n\to{f}$ 当且仅当每个坐标 $t\in\left[0,1\right]$ 都有 $f_n\left(t\right)\to{f}\left(t\right)$; 该判据对任意因子空间 $A^{S}$ 成立, 因为乘积拓扑的基与因子空间无关.

对每个 $n\ge1$, 定义 $f_n\left(t\right)$ 为 $t$ 的二进制展开中小数点后第 $n$ 位数字 (二进有理点固定取其一展开). 任取严格递增的正整数列 $n_1<{}n_2<\dots$, 我们证明 $\left\{f_{n_k}\right\}$ 不收敛. 取 $t^{*}\in\left[0,1\right]$, 使其二进制展开在第 $n_{2k-1}$ 位为 $0$, 在第 $n_{2k}$ 位为 $1$, 其余位任意 (例如取 $0$). 则坐标 $t^{*}$ 处 $f_{n_k}\left(t^{*}\right)$ 依次为 $0,1,0,1,\dots$, 在离散空间 $\left\{0,1\right\}$ 中不收敛: 由**定义 3.25 (邻域与极限)**, $\left\{0\right\}$ 是 $0$ 的邻域而不含无穷多个 $f_{n_k}\left(t^{*}\right)$. 由**命题 3.33 (点态收敛判据)**, $\left\{f_{n_k}\right\}$ 在乘积拓扑下不收敛. 因每个子列都有同样形式, 由**定义 6.40 (序列紧致)**, $\left\{0,1\right\}^{\left[0,1\right]}$ 不是序列紧致的.

$\blacksquare$

## 7.3 (紧致等价于具有限交性质的闭集族交非空)

称集合族 $\mathcal{F}$ 具有有限交性质, 若其任意有限子族之交非空. 证明: 空间 $X$ 紧致等价于, $X$ 中任意具有限交性质的闭集族 $\mathcal{F}$ 都满足 $\bigcap_{F\in\mathcal{F}}F\neq\emptyset$.

题集 §3.1 Q2.

### 解答 7.3

由**定义 5.15 (开覆盖与有限子覆盖)** 与**定义 5.16 (紧致空间)**, 分两个方向证明.

($\Rightarrow$) 设 $X$ 紧致, $\mathcal{F}$ 是具有限交性质的闭集族. 若 $\bigcap_{F\in\mathcal{F}}F=\emptyset$, 则 $\left\{X\setminus{F}:F\in\mathcal{F}\right\}$ 是 $X$ 的开覆盖: 各 $F$ 闭, 由**定义 3.21 (闭集)** 其补开. 由**定义 5.16 (紧致空间)**, 它有有限子覆盖 $X\setminus{F}_1,\dots,X\setminus{F}_k$, 即 $X=\bigcup_{i=1}^{k}\left(X\setminus{F}_i\right)$. 取补集得 $\bigcap_{i=1}^{k}F_i=\emptyset$, 与**定义 5.17 (有限交性质)** 矛盾. 故全族之交非空.

$\blacksquare$

($\Leftarrow$) 设任意具有限交性质的闭集族之交非空. 任取 $X$ 的开覆盖 $\left\{U_i\right\}$. 令 $F_i=X\setminus{U}_i$, 由**定义 3.21 (闭集)** 各 $F_i$ 闭. 若 $\left\{U_i\right\}$ 无有限子覆盖, 则任意有限个 $F_{i_1},\dots,F_{i_k}$ 满足

$$
\bigcap_{j=1}^{k}F_{i_j}=X\setminus\bigcup_{j=1}^{k}U_{i_j}\neq\emptyset,
$$

即 $\left\{F_i\right\}$ 具有限交性质. 由假设 $\bigcap_iF_i\neq\emptyset$, 即 $X\setminus\bigcup_iU_i\neq\emptyset$, 与 $\left\{U_i\right\}$ 覆盖 $X$ 矛盾. 故存在有限子覆盖, 由**定义 5.16 (紧致空间)**, $X$ 紧致.

$\blacksquare$

## 7.4 (紧集与不相交闭集的距离为正)

设 $A,B$ 是度量空间 $\left(X,d\right)$ 中不相交的闭集, 且 $A$ 紧致. 证明 $d\left(A,B\right)>0$.

题集 §3.1 Q3.

### 解答 7.4

令 $g\left(x\right)=d\left(x,B\right)$. 由**定义 6.46 (点到集合的距离)**, $g$ 有定义. 由**定义 6.35 (度量空间)** 的三角不等式与**定义 6.46 (点到集合的距离)**, 对任意 $x,y\in{X}$ 与 $b\in{B}$ 有 $d\left(x,b\right)\le{d}\left(x,y\right)+d\left(y,b\right)$, 对 $b$ 取下确界再对称化得 $\left|g\left(x\right)-g\left(y\right)\right|\le{d}\left(x,y\right)$; 于是 $x_n\to{x}$ 蕴含 $g\left(x_n\right)\to{g}\left(x\right)$, 由**说明 6.51 (度量连续与序列)**, $g$ 连续. 因 $A$ 紧致, 由**定理 5.11 (紧空间上连续函数取最大值)**, $g$ 在 $A$ 上取到最小值

$$
m=\min_{a\in{A}}g\left(a\right)=\inf_{a\in{A},b\in{B}}d\left(a,b\right)=d\left(A,B\right).
$$

若 $m=0$, 则存在 $a_0\in{A}$ 使 $d\left(a_0,B\right)=0$, 即对每个 $r>0$ 开球 $B\left(a_0,r\right)$ 都与 $B$ 相交 (由**定义 6.36 (开球)**); 因 $a_0\notin{B}$ (由 $A\cap{B}=\emptyset$), 由**定义 3.24 (极限点)** $a_0$ 是 $B$ 的极限点. 由**定理 3.5 (闭包与极限点)** $a_0\in\overline{B}$, 而 $B$ 闭, 由**定义 3.26 (闭包)** $\overline{B}=B$, 故 $a_0\in{B}$, 与 $A\cap{B}=\emptyset$ 矛盾. 故 $m>0$, 即 $d\left(A,B\right)>0$.

$\blacksquare$

## 7.5 (无孤立点度量空间中紧致等价于闭集间距离皆为正)

设 $\left(X,d\right)$ 是无孤立点的度量空间. 证明: $X$ 紧致当且仅当对任意一对不相交闭集 $A,B$, 都有 $d\left(A,B\right)>0$.

题集 §3.1 Q4.

### 解答 7.5

($\Rightarrow$) 设 $X$ 紧致, $A,B$ 为不相交闭集. 由**定理 5.4 (闭子集紧)**, $A$ 紧致. 由**习题 7.4**的论证 (连续函数 $d\left(\cdot,B\right)$ 在 $A$ 上取到正最小值) 即得 $d\left(A,B\right)>0$.

$\blacksquare$

($\Leftarrow$) 反证, 设 $X$ 不紧致. 由**定理 6.1 (紧 $=$ 序列紧)**, $X$ 不是序列紧致的, 故存在序列 $\left\{x_n\right\}$ 无收敛子列. 必要时取子列使 $x_n$ 两两不同. 于是 $S=\left\{x_n:n\ge1\right\}$ 无极限点: 若 $x$ 是 $S$ 的极限点, 由**定义 3.24 (极限点)** 每个开球 $B\left(x,1/k\right)$ 都含 $S\setminus\left\{x\right\}$ 的点, 且事实上含无穷多个 (若某球只含有限个, 取半径小于这些点到 $x$ 的距离, 得与极限点定义矛盾的球), 故可归纳选取两两不同的 $x_{n_k}\in{B}\left(x,1/k\right)$, 得收敛于 $x$ 的子列, 矛盾. 故 $S'=\emptyset$, 由**定理 3.5 (闭包与极限点)** $\overline{S}=S$, 由**定义 3.26 (闭包)** $S$ 闭. 因 $X$ 无孤立点, 每个 $x_n$ 的任意邻域都含异于 $x_n$ 的点; 归纳地选取 $y_n$, 使 $0<{}d\left(y_n,x_n\right)<1/n$, 且 $y_n\notin{S}\cup\left\{y_1,\dots,y_{n-1}\right\}$. 则 $\left\{y_n\right\}$ 也无收敛子列: 若 $y_{n_k}\to{y}$, 则由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x_{n_k},y\right)\le{d}\left(x_{n_k},y_{n_k}\right)+d\left(y_{n_k},y\right)\to0,
$$

与 $\left\{x_n\right\}$ 无收敛子列矛盾. 故 $T=\left\{y_n:n\ge1\right\}$ 也闭 (同上). 令 $A=S$, $B=T$, 则二者不相交闭, 但对一切 $n$ 有 $d\left(A,B\right)\le{d}\left(x_n,y_n\right)<1/n$, 故 $d\left(A,B\right)=0$, 与假设矛盾. 因此 $X$ 紧致.

$\blacksquare$

## 7.6 (黎曼球面 (单点紧化) 紧致)

考虑 $\mathbb{C}$ 与一个无穷远点 $\left\{\infty\right\}$. 记 $\overline{\mathbb{C}}=\mathbb{C}\cup\left\{\infty\right\}$, 规定 $U\subset\overline{\mathbb{C}}$ 的拓扑为: 若 $\infty\notin{U}$, 则 $U$ 开当且仅当它是 $\mathbb{C}$ 中通常开集; 若 $\infty\in{U}$, 则 $U$ 开当且仅当 $\mathbb{C}\setminus\left(U\cap\mathbb{C}\right)$ 在 $\mathbb{C}$ 中紧致. 证明 $\overline{\mathbb{C}}$ 紧致. 此即亚历山德罗夫单点紧化, $\overline{\mathbb{C}}$ 称为黎曼球面.

题集 §3.1 Q5.

### 解答 7.6

由**定义 7.5 (单点紧化)**, $\overline{\mathbb{C}}$ 正是 $\mathbb{C}$ 的单点紧化. 任取 $\overline{\mathbb{C}}$ 的开覆盖 $\mathcal{U}$. 取 $U_\infty\in\mathcal{U}$ 使 $\infty\in{U}_\infty$. 由拓扑定义, $K=\mathbb{C}\setminus\left(U_\infty\cap\mathbb{C}\right)$ 在 $\mathbb{C}$ 中紧致. 族

$$
\left\{U\cap\mathbb{C}:U\in\mathcal{U}\setminus\left\{U_\infty\right\}\right\}
$$

中每个集合是 $\mathbb{C}$ 中开集 (不含 $\infty$ 的开集在 $\overline{\mathbb{C}}$ 与在 $\mathbb{C}$ 中同样开), 且它们覆盖 $K$ (因 $K$ 与 $U_\infty$ 无交). 由 $K$ 紧致, 即由**定义 5.16 (紧致空间)**, 有有限子族 $U_1,\dots,U_m$ 使 $K\subset\bigcup_{i=1}^{m}U_i$. 于是 $U_\infty,U_1,\dots,U_m$ 覆盖 $\overline{\mathbb{C}}$: $U_\infty$ 含 $\infty$ 与 $U_\infty\cap\mathbb{C}$, 其余集合覆盖 $K$. 故 $\overline{\mathbb{C}}$ 的任意开覆盖都有有限子覆盖, 由**定义 5.16 (紧致空间)**, $\overline{\mathbb{C}}$ 紧致.

$\blacksquare$

## 7.7 (有限离散空间紧致)

给 $\left\{1,\dots,k\right\}$ 赋离散拓扑. 证明 $\left\{1,\dots,k\right\}$ 在该拓扑下紧致.

题集 §3.3 Q1; 2025 卷 B 题一 第 0 小问.

### 解答 7.7

设 $\mathcal{U}$ 是 $\left\{1,\dots,k\right\}$ 的任意开覆盖. 由**定义 5.15 (开覆盖与有限子覆盖)**, 对每个点 $i\in\left\{1,\dots,k\right\}$ 选取 $U_i\in\mathcal{U}$ 使 $i\in{U}_i$. 则 $\left\{U_1,\dots,U_k\right\}$ 是有限子族且仍覆盖 $\left\{1,\dots,k\right\}$. 由**定义 5.16 (紧致空间)**, $\left\{1,\dots,k\right\}$ 紧致.

$\blacksquare$

> 离散拓扑: 每个点自己就是开集, 开集的并也是开集, 这么说每个点又都是闭集, 所以每个点都是开闭集.

## 7.8 (吉洪诺夫定理: 映射空间 $\left\{1,\dots,k\right\}^{V}$ 紧致)

用吉洪诺夫定理证明: 映射集合 $X=\left\{f:V\to\left\{1,\dots,k\right\}\right\}$ 紧致.

题集 §3.3 Q2; 2025 卷 B 题一 第 1 小问.

### 解答 7.8

集合 $X=\left\{1,\dots,k\right\}^{V}=\prod_{v\in{V}}\left\{1,\dots,k\right\}$ 是离散有限空间 $\left\{1,\dots,k\right\}$ 的乘积. 由**习题 7.7**, 每个因子 $\left\{1,\dots,k\right\}$ 紧致. 由**定理 5.9 (吉洪诺夫定理)**, 乘积 $X$ 在乘积拓扑下紧致.

$\blacksquare$
