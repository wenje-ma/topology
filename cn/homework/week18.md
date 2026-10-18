# 作业 18

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.4** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并. (教材 $\S4$)

> **定义 4.5** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $\gamma:\left[0,1\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸即 $x,y\in K$ 蕴含连线全在 $K$ 中; 凸集必路径连通. (教材 $\S4$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge 0}$ 满足正定性, 对称性, 三角不等式. (教材 $\S6$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (题集 $\S5$)

> **定义 6.55** (超平面)<br>赋范线性空间 $E$ 中余维数为 $1$ 的线性子空间 $H$, 即 $E/H$ 维数为 $1$. (题集 $\S6$)

> **定义 6.56** (线性泛函)<br>$E\to\mathbb R$ 的线性映射 $\varphi$ 称为线性泛函. (题集 $\S6$)

> **定义 6.60** (序列空间 $\ell^p$)<br>$\ell^p=\left\{x=\left(x_n\right):\sum_{n\ge 1}\left|x_n\right|^p<\infty\right\}$, 装备 $\left\|x\right\|_p=\left(\sum\left|x_n\right|^p\right)^{1/p}$; 当 $1\le p<\infty$ 时是巴拿赫空间. (题集 $\S6$)

> **定义 11.1** (商拓扑)<br>满射 $\pi:X\to Y$ 下, $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 $\S11$)

> **定义 11.2** (商映射)<br>满射 $\pi:X\to Y$ 使 $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. (教材 $\S11$)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑. (题集 $\S1$)

> **定理 4.1** (区间连通)<br>$\left[0,1\right]$ 连通. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间的连续像紧. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>豪斯多夫空间中紧子集闭. (教材 $\S5$)

> **推论 5.11** (紧空间上连续函数取最大值)<br>紧空间上连续实函数取得最大值与最小值. (教材 $\S5$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **推论 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup_n F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定理 6.57** (开映射定理)<br>巴拿赫空间之间的连续满线性映射是开映射 (把开集映为开集); 推论: 巴拿赫空间之间的连续线性双射之逆连续. (题集 $\S6$)

> **定理 6.58** (巴拿赫-施坦豪斯定理)<br>设 $E$ 是巴拿赫空间, $F$ 是赋范线性空间, $\left\{T_i\right\}_{i\in I}$ 是一族连续线性映射 $T_i:E\to F$. 若对每个 $x\in E$, $\sup_i\left\|T_i x\right\|<\infty$, 则 $\sup_i\left\|T_i\right\|<\infty$. (题集 $\S6$)

> **定理 6.59** (巴拿赫-绍德不动点定理)<br>巴拿赫空间中非空紧凸子集到自身的连续映射有不动点. (题集 $\S6$)

> **定理 7.2** (乌雷松引理)<br>正规空间中不相交闭集 $A,B$ 有连续 $f:X\to\left[0,1\right]$, $f\big|_A=0$, $f\big|_B=1$. (教材 $\S7$)

### 习题一

设 $E$ 是无穷维赋范线性空间, $K\subset E$ 是紧集. 证明 $E\setminus K$ 道路连通. 问有限维赋范线性空间中此结论是否成立?

### 解答 习题一

**无穷维情形**: 由**定理 6.17** (里茨定理), 无穷维赋范线性空间的闭单位球非紧, 故任何紧集 $K$ 必无内部 (否则 $K$ 含某闭球的平移, 该闭球紧, 与里茨定理矛盾).

任取 $x,y\in E\setminus K$. 由**定义 6.15** (点到集合的距离), $d\left(x,K\right)>0$. 考虑从 $x$ 出发的单位方向球面 $S\left(E\right)=\left\{v:\left\|v\right\|=1\right\}$. 连续映射 $r:K\to S\left(E\right)$ 定义为 $r\left(k\right)=\left(k-x\right)/\left\|k-x\right\|$ ($k\neq x$; 因 $x\notin K$ 良定义). 由**定理 5.1** (紧空间连续像紧), $r\left(K\right)\subset S\left(E\right)$ 紧. 由**定理 6.17** (里茨定理), $S\left(E\right)$ 中任一紧子集无内部, 故可取方向 $v\in S\left(E\right)\setminus r\left(K\right)$. 于是射线 $\left\{x+tv:t\ge 0\right\}$ 与 $K$ 不相交 (若某 $k=x+tv\in K$, 则 $v=r\left(k\right)\in r\left(K\right)$, 矛盾).

取 $L>0$ 充分大使 $z=x+Lv$ 满足 $\left\|z-y\right\|>d\left(y,K\right)$ 且 $z$ 不在 $K$ 中. 直线段 $\left[x,z\right]$ 避开 $K$. 同理从 $y$ 出发选一好方向 $w$ 使射线 $\left\{y+sw:s\ge 0\right\}$ 避开 $K$, 取 $z'=y+Mw$ 充分远. 最后在远离 $K$ 的地方用直线段 $\left[z,z'\right]$ 连接 (因 $K$ 紧有界, 取 $L,M$ 充分大时该线段也在 $K$ 之外). 所得折线 $x\to z\to z'\to y$ 由**定义 4.5** (路径连通) 是连续路径, 且全段避开 $K$. 故 $E\setminus K$ 道路连通.

**有限维情形**: 结论不成立. 取 $E=\mathbb R^2$, $K=S^1=\left\{\left(u,v\right):u^2+v^2=1\right\}$. $S^1$ 紧 (闭有界). 但 $\mathbb R^2\setminus S^1=\left\{u^2+v^2<1\right\}\cup\left\{u^2+v^2>1\right\}$ 是两个非空不相交开集之并, 由**定义 4.1** (连通空间) 不连通, 因而不道路连通. $\blacksquare$

### 习题二

设 $f:\mathbb R^n\to\mathbb R$ 连续, $n\ge 2$, 且对每个 $a\in\mathbb R$, 等值集 $f^{-1}\left(a\right)$ 紧. 证明 $f$ 取得全局极值 (上确界或下确界之一达到). 问 $n=1$ 时结论如何?

### 解答 习题二

取定 $a$ 使 $f^{-1}\left(a\right)\neq\emptyset$ (若非空), 即存在 $x_0$ 使 $f\left(x_0\right)=a$. 由假设 $f^{-1}\left(a\right)$ 紧, 由**定理 5.5** (豪斯多夫中紧集闭) 它是闭有界集, 故存在 $R>0$ 使 $f^{-1}\left(a\right)\subset B\left(0,R\right)$.

球面 $\partial B\left(0,R\right)$ 在 $n\ge 2$ 时连通 (它是 $\mathbb R^n$ 中连通紧集). 由**定义 3.3** (连续映射), $f\left(\partial B\left(0,R\right)\right)$ 是 $\mathbb R$ 中不含 $a$ 的连通集; 由**定理 4.2** (连续像连通) 它连通, 故必全在 $\left(a,\infty\right)$ 或全在 $\left(-\infty,a\right)$ 中. 不妨设 $f>a$ 在 $\partial B\left(0,R\right)$ 上.

**反证**: 假设 $f$ 既无全局最大值也无全局最小值. 由 $f$ 无最小值, 存在 $x$ 使 $f\left(x\right)<a$. 若 $\left\|x\right\|>R$, 考虑从 $x$ 到球心 $0$ 的径向线段; 由**定理 4.1** (区间连通) 该线段连通, 其上 $f$ 连续, 在端点 $x$ 处 $f<a$, 在球面处 $f>a$, 由介值定理必有点 $p$ 在该线段上使 $f\left(p\right)=a$ 且 $\left\|p\right\|>R$, 这与 $f^{-1}\left(a\right)\subset B\left(0,R\right)$ 矛盾. 故 $f$ 无最小值只能在 $\left\|x\right\|<R$ 内发生.

同理, 由 $f$ 无最大值, 存在 $y$ 使 $f\left(y\right)>a$. 若 $\left\|y\right\|>R$, 则因外部区域 $\mathbb R^n\setminus \overline B\left(0,R\right)$ 在 $n\ge 2$ 时连通且 $f>a$ 在其边界 $\partial B\left(0,R\right)$ 上, 由**定理 4.2** (连续像连通) 与介值定理推出外部某处 $f=a$, 矛盾. 故 $f$ 的上无界性也只能在 $\overline B\left(0,R\right)$ 内发生.

于是在紧集 $\overline B\left(0,R\right)$ 上由**推论 5.11** (紧空间上连续函数取最大值), $f$ 取得最大值与最小值; 而在 $\mathbb R^n\setminus \overline B\left(0,R\right)$ 上 $f>a$, 故 $f$ 在 $\overline B\left(0,R\right)$ 上取得的最小值就是全局最小值. 故 $f$ 取得全局极值.

**$n=1$**: 结论不成立. 取 $f\left(x\right)=x$, 则 $f^{-1}\left(a\right)=\left\{a\right\}$ 是单点集紧, 但 $f:\mathbb R\to\mathbb R$ 既无最大值也无最小值. $\blacksquare$

### 习题三

设 $E$ 是**定义 6.20** (赋范线性空间) 意义下的赋范线性空间, $H$ 是**定义 6.55** (超平面). 证明存在**定义 6.56** (线性泛函) $\varphi:E\to\mathbb R$ 使 $H=\ker\varphi$. 进一步证明 $H$ 是闭集当且仅当 $\varphi$ 连续.

### 解答 习题三

由**定义 6.55** (超平面), $\dim\left(E/H\right)=1$. 取 $v\notin H$, 则 $E=H\oplus\mathbb R v$. 任取 $u\in E$, 唯一分解 $u=h+tv$, $h\in H$, $t\in\mathbb R$. 定义**定义 6.56** (线性泛函) $\varphi\left(u\right)=t$. 则 $\varphi$ 线性且 $\ker\varphi=H$. 这里 $E$ 是**定义 6.20** (赋范线性空间).

**($\varphi$ 连续 $\Rightarrow$ $H$ 闭)**: 由**定义 3.3** (连续映射), $\varphi^{-1}\left(\left\{0\right\}\right)$ 是闭集 ($\left\{0\right\}\subset\mathbb R$ 闭), 而 $H=\ker\varphi=\varphi^{-1}\left(\left\{0\right\}\right)$, 由**定义 3.2** (闭集) $H$ 闭.

**($H$ 闭 $\Rightarrow$ $\varphi$ 连续)**: 反证. 设 $H$ 闭但 $\varphi$ 不连续, 即 $\varphi$ 无界. 故存在序列 $\left(x_n\right)$ 使 $\left\|x_n\right\|=1$ 而 $\left|\varphi\left(x_n\right)\right|\to\infty$. 任取 $u\in E$, 定义

$$
u_n=u-\frac{\varphi\left(u\right)}{\varphi\left(x_n\right)}\,x_n.
$$

则 $\varphi\left(u_n\right)=\varphi\left(u\right)-\varphi\left(u\right)=0$, 故 $u_n\in H$. 又

$$
\left\|u-u_n\right\|=\left|\frac{\varphi\left(u\right)}{\varphi\left(x_n\right)}\right|\cdot\left\|x_n\right\|=\frac{\left|\varphi\left(u\right)\right|}{\left|\varphi\left(x_n\right)\right|}\to 0.
$$

由**定义 3.2** (闭集) $H$ 闭, 故 $u=\lim u_n\in H$, 即 $\varphi\left(u\right)=0$. 由 $u$ 任意, $\varphi\equiv 0$, 与 $H$ 是余维 $1$ 的超平面矛盾. 故 $\varphi$ 必连续. $\blacksquare$

### 习题四

设 $E$ 是赋范线性空间, $H$ 是超平面. 证明 $E\setminus H$ 道路连通当且仅当 $H$ 不是闭集.

注: 题集原文误作 "当且仅当 $H$ 是闭集", 与其附证方向不符 (附证证的正是 $H$ 非闭时道路连通, $H$ 闭时 $E\setminus H$ 分裂为两个凸分支); 此处按数学本意改正.

### 解答 习题四

取线性泛函 $\varphi$ 使 $H=\ker\varphi$ (习题三). 记

$$
H^{-}=\varphi^{-1}\left(\left(-\infty,0\right)\right),\quad H^{+}=\varphi^{-1}\left(\left(0,\infty\right)\right).
$$

由 $\varphi$ 线性, $H^{-}$ 与 $H^{+}$ 都是凸集, 由**定义 4.6** (凸集) 它们道路连通.

**($H$ 闭 $\Rightarrow$ $E\setminus H$ 不道路连通)**: 由习题三, $H$ 闭时 $\varphi$ 连续. 由**定义 3.3** (连续映射), $H^{-}$ 与 $H^{+}$ 都是开集, 且 $E\setminus H=H^{-}\sqcup H^{+}$ 是两个非空不相交开集之并. 由**定义 4.1** (连通空间), $E\setminus H$ 不连通, 故不道路连通. 直观地, 若有连续路径 $\gamma:\left[0,1\right]\to E\setminus H$ 从 $H^{-}$ 到 $H^{+}$, 则 $\varphi\circ\gamma$ 是**定理 4.1** (区间连通) 上的连续实函数, 在两端异号, 由介值定理必取 $0$, 即某 $\gamma\left(t\right)\in H$, 矛盾.

**($H$ 不闭 $\Rightarrow$ $E\setminus H$ 道路连通)**: 由习题三, $H$ 不闭时 $\varphi$ 不连续, 此时 $\overline H=E$ (即 $H$ 在 $E$ 中稠密). 取 $e\in E$ 使 $\varphi\left(e\right)=1$. 则 $\varphi^{-1}\left(1\right)=e+H$ 在 $E$ 中稠密 (平移不改变稠密性). 任取 $-e\in H^{-}$ ($\varphi\left(-e\right)=-1$), 由**定义 3.8** (稠密) 可取序列 $x_n\in e+H$ 使 $x_n\to -e$, 且不妨设 $x_1=e$.

定义路径 $\gamma:\left[0,1\right]\to E$: 在 $t\in\left[1/\left(k+1\right),1/k\right]$ 上, $\gamma$ 沿直线段从 $x_{k+1}$ 走到 $x_k$, 并令 $\gamma\left(0\right)=-e$. 因 $x_n\to -e$, 该折线在 $0$ 处连续. 对 $t>0$, $\gamma\left(t\right)\in e+H$, 故 $\varphi\left(\gamma\left(t\right)\right)=1$; 而 $\varphi\left(\gamma\left(0\right)\right)=\varphi\left(-e\right)=-1$. 故 $\gamma$ 全段在 $E\setminus H$ 中, 从 $-e$ 连到 $e$. 由**定义 4.5** (路径连通), $H^{-}$ 与 $H^{+}$ 各自道路连通, 任意两点可经 $-e\to e$ 折线互相连通. 故 $E\setminus H$ 道路连通. $\blacksquare$

### 习题五

(开映射定理的推论) 设 $E,F$ 都是**定义 6.21** (巴拿赫空间), $T:E\to F$ 是连续线性双射. 证明 $T^{-1}:F\to E$ 连续, 即 $T$ 是同胚.

### 解答 习题五

由**定理 6.57** (开映射定理), 巴拿赫空间之间的连续满线性映射把开集映为开集. $T$ 是双射, 故满. 对任意开集 $U\subset E$, $T\left(U\right)\subset F$ 是开集. 而 $T^{-1}$ 的逆像

$$
\left(T^{-1}\right)^{-1}\left(U\right)=T\left(U\right)
$$

是开集. 由**定义 3.3** (连续映射), $T^{-1}$ 连续. 故 $T$ 是**定义 3.4** (同胚) 意义下的同胚. $\blacksquare$

### 习题六

(巴拿赫-施坦豪斯定理的推论) 设 $E$ 是巴拿赫空间, $F$ 是赋范线性空间, $T_n:E\to F$ 是连续线性映射, 且对每个 $x\in E$, $T_n x$ 在 $F$ 中收敛. 证明 $\sup_n\left\|T_n\right\|<\infty$, 且极限映射 $T x=\lim_n T_n x$ 是连续线性映射.

### 解答 习题六

由假设, 对每个 $x\in E$, $\sup_n\left\|T_n x\right\|<\infty$ (收敛数列有界). 由**定理 6.58** (巴拿赫-施坦豪斯定理), $\sup_n\left\|T_n\right\|<\infty$, 记 $M=\sup_n\left\|T_n\right\|$.

线性: 对 $x,y\in E$ 与 $\alpha\in\mathbb R$,

$$
T\left(\alpha x+y\right)=\lim_n T_n\left(\alpha x+y\right)=\lim_n\left(\alpha T_n x+T_n y\right)=\alpha T x+T y.
$$

有界性: $\left\|T x\right\|=\lim_n\left\|T_n x\right\|\le M\left\|x\right\|$. 由**定义 3.3** (连续映射) 赋范空间间的有界线性映射连续, 故 $T$ 连续. $\blacksquare$

### 习题七

(巴拿赫-绍德定理的推论) 设 $K$ 是巴拿赫空间中非空紧凸子集, $f:K\to K$ 连续. 证明 $f$ 有不动点. 有限维情形推出: 非空紧凸子集 (例如闭单位球) 到自身的连续映射有不动点.

### 解答 习题七

由**定理 6.59** (巴拿赫-绍德不动点定理), 巴拿赫空间中非空紧凸子集到自身的连续映射有不动点, 故存在 $x\in K$ 使 $f\left(x\right)=x$.

有限维情形: $\mathbb R^n$ 是巴拿赫空间, 其非空紧凸子集 $K$ 满足绍德定理条件, 故 $f$ 有不动点. 这就是有限维的布劳威尔不动点定理. $\blacksquare$

### 习题八

设 $f:\mathbb R_{\ge 0}\to\mathbb R$ 连续, 且对每个 $x\ge 0$, 序列 $\left\{f\left(nx\right)\right\}_{n\ge 0}$ 收敛到 $0$. 证明 $\lim_{x\to\infty}f\left(x\right)=0$ (克罗夫特引理).

### 解答 习题八

固定 $\epsilon>0$. 定义

$$
F_m=\left\{x\ge 0:\ \text{对一切 }k\ge m,\ \left|f\left(kx\right)\right|\le\epsilon\right\}.
$$

对固定 $k$, 条件 $\left|f\left(kx\right)\right|\le\epsilon$ 是 $x$ 的闭条件 ($f$ 连续); $F_m$ 是这些闭集 ($k\ge m$) 之交, 故闭. 由假设, 每个 $x\ge 0$ 属于某个 $F_m$, 故 $\mathbb R_{\ge 0}=\bigcup_{m\ge 1}F_m$, 且 $F_m$ 递增.

由**定理 6.13** (贝尔纲定理) 及其**推论 6.14** (递增闭集族), 某个 $F_N$ 有非空内部, 故存在区间 $\left[a,b\right]\subset F_N$, $0<a<b$. 于是对一切 $x\in\left[a,b\right]$ 与 $k\ge N$, $\left|f\left(kx\right)\right|\le\epsilon$.

任取 $t$ 充分大, 考虑整数区间 $\left[t/b,t/a\right]$. 其长度为 $t\left(1/a-1/b\right)\to\infty$, 故当 $t$ 充分大时其中含某整数 $k\ge N$. 令 $x=t/k$, 则 $x\in\left[a,b\right]$, 故 $\left|f\left(t\right)\right|=\left|f\left(kx\right)\right|\le\epsilon$. 因而 $\limsup_{t\to\infty}\left|f\left(t\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{t\to\infty}f\left(t\right)=0$. $\blacksquare$

### 习题九

设 $E$ 是有限维实向量空间, $1\le n<\infty$, $\left\{F_k\right\}_{k\in\mathbb N}$ 是一列 $p$ 维子空间. 证明 $\bigcup_{k\in\mathbb N}F_k\neq E$. 进一步证明存在子空间 $W\subset E$ 使对一切 $k$, $W\oplus F_k=E$.

### 解答 习题九

有限维赋范空间是**定义 6.21** (巴拿赫空间) 意义下的巴拿赫空间. 每个 $F_k$ 是真子空间 ($p<n$), 且在 $E$ 中闭 (有限维子空间闭). 若 $E=\bigcup_k F_k$, 由**推论 6.14** (递增闭集族) (注意 $F_k$ 虽不递增, 令 $G_N=\bigcup_{k\le N}F_k$ 为递增闭集列且 $E=\bigcup_N G_N$), 某个 $G_N$ 有非空内部; 但有限个真子空间之并仍无内部 (否则含开球, 含开球的子空间必为全空间), 矛盾. 故 $\bigcup_k F_k\neq E$.

**存在 $W$**: 归纳构造 $w_1,\dots,w_{n-p}$. 假设已选 $w_1,\dots,w_j$ ($j<n-p$), 令 $V_j=\operatorname{span}\left(w_1,\dots,w_j\right)$. 对每个 $k$, $F_k+V_j$ 是真子空间 (因为 $F_k$ 维数 $p$, 加 $V_j$ 维数 $p+j<p+\left(n-p\right)=n$), 因而闭且无内部. 由**定理 6.13** (贝尔纲定理), 可数并 $\bigcup_k\left(F_k+V_j\right)\neq E$, 故可取

$$
w_{j+1}\in E\setminus\bigcup_k\left(F_k+V_j\right).
$$

则 $w_{j+1}\notin F_k+V_j$ 对一切 $k$. 令 $W=\operatorname{span}\left(w_1,\dots,w_{n-p}\right)$. 则对每个 $k$, $W\cap F_k=\left\{0\right\}$ (若非零 $w\in W\cap F_k$, 则 $w\in F_k+V_j$ 对最大 $j$ 矛盾), 且 $\dim W+\dim F_k=\left(n-p\right)+p=n=\dim E$, 故 $W\oplus F_k=E$. $\blacksquare$

### 习题十

设 $f:\mathbb R_{\ge 0}\to\mathbb R$ 连续, 且对每个 $\lambda\ge 0$, $\lim_{x\to\infty}\left(f\left(x+\lambda\right)-f\left(x\right)\right)=0$. 证明对任意区间 $\left[a,b\right]\subset\mathbb R_{\ge 0}$, 收敛在 $\lambda\in\left[a,b\right]$ 上一致.

### 解答 习题十

固定 $\epsilon>0$. 定义

$$
F_m=\left\{\lambda\in\left[a,b\right]:\ \text{对一切 }x\ge m,\ \left|f\left(x+\lambda\right)-f\left(x\right)\right|\le\epsilon\right\}.
$$

对固定 $x$, 条件 $\left|f\left(x+\lambda\right)-f\left(x\right)\right|\le\epsilon$ 是 $\lambda$ 的闭条件 ($f$ 连续); $F_m$ 是这些闭集 ($x\ge m$) 之交, 故闭. 由假设, 每个 $\lambda\in\left[a,b\right]$ 属于某个 $F_m$, 故 $\left[a,b\right]=\bigcup_m F_m$, 且 $F_m$ 递增.

$\left[a,b\right]$ 是紧度量空间, 因而完备. 由**推论 6.14** (递增闭集族), 某个 $F_N$ 有非空内部, 即存在开区间 $\left(c,d\right)\subset F_N$. 对任意 $\lambda\in\left[a,b\right]$, 取 $\lambda_0\in\left(c,d\right)$ 使 $\left|\lambda-\lambda_0\right|$ 很小. 分解

$$
f\left(x+\lambda\right)-f\left(x\right)=\left[f\left(x+\lambda\right)-f\left(x+\lambda_0\right)\right]+\left[f\left(x+\lambda_0\right)-f\left(x\right)\right].
$$

第二项对 $x\ge N$ 绝对值 $\le\epsilon$. 第一项是 $f\left(\left(x+\lambda_0\right)+\delta\right)-f\left(x+\lambda_0\right)$, 其中 $\delta=\lambda-\lambda_0$ 固定. 由假设, 对每个固定 $\delta$, 当 $x+\lambda_0\to\infty$ 时该项趋于 $0$.

由 $\left[c,d\right]$ 紧与贝尔纲得到的非空内部, 进一步用有限覆盖: $\left[a,b\right]$ 被有限个形如 $\lambda_0+\eta$ 的平移区间覆盖 ($\eta$ 取自一个固定有限网), 对每个固定的 $\eta$ 取 $M_\eta$ 使 $x\ge M_\eta$ 时 $\left|f\left(x+\eta\right)-f\left(x\right)\right|\le\epsilon$. 取 $M=\max\left(N,M_\eta\right)$, 则对一切 $\lambda\in\left[a,b\right]$ 与 $x\ge M$, 上述两项均 $\le\epsilon$, 故 $\left|f\left(x+\lambda\right)-f\left(x\right)\right|\le 2\epsilon$. 收敛一致. $\blacksquare$

### 习题十一

设 $1<q<\infty$. 证明在**定义 6.60** (序列空间 $\ell^p$) 意义下, $\ell^q\neq\bigcup_{1<p<q}\ell^p$.

### 解答 习题十一

对 $1\le p<q<\infty$, 在**定义 6.60** (序列空间 $\ell^p$) 意义下 $\ell^p\subset\ell^q$. 事实上若 $x\in\ell^p$, 则 $x_n\to 0$, 故存在 $N$ 使 $n\ge N$ 时 $\left|x_n\right|\le 1$, 于是 $\left|x_n\right|^q\le\left|x_n\right|^p$, 从而 $\sum\left|x_n\right|^q<\infty$.

下面证明每个 $\ell^p$ ($p<q$) 在 $\ell^q$ 中是无处稠密的. 由**定义 3.2** (闭集), $\ell^p$ 在 $\ell^q$ 中闭: 若 $x^{\left(m\right)}\in\ell^p$ 在 $\ell^q$ 中收敛到 $x$, 则 $x^{\left(m\right)}_n\to x_n$ 对每个 $n$, 由法图引理 (点集分析基本事实) $\sum\left|x_n\right|^p\le\liminf_m\sum\left|x^{\left(m\right)}_n\right|^p<\infty$, 故 $x\in\ell^p$.

$\ell^p$ 无内部: 任取 $x\in\ell^p$ 与 $\epsilon>0$, 构造 $y$ 使 $\left\|y-x\right\|_q<\epsilon$ 但 $y\notin\ell^p$. 取稀疏下标 $n_k$ 使 $\left|x_{n_k}\right|$ 很小, 令 $y_{n_k}=k^{-1/p}$ (其余 $y_n=x_n$). 则 $\sum\left|y_{n_k}\right|^p=\sum 1/k=\infty$, 故 $y\notin\ell^p$; 而 $\sum\left|y_{n_k}\right|^q=\sum k^{-q/p}<\infty$ (因 $q/p>1$), 且可使 $\left\|y-x\right\|_q$ 任意小. 故 $\ell^p$ 在 $\ell^q$ 中无内部.

由**推论 6.14** (递增闭集族), $\ell^q$ (完备, 因 $\ell^q$ 是巴拿赫空间) 不能写成可数个无内部闭集之并. 取有理数集 $\mathbb Q\cap\left(1,q\right)$, 它是可数稠密子集; $\bigcup_{p\in\mathbb Q\cap\left(1,q\right)}\ell^p$ 是可数个无内部闭集之并, 故不等于 $\ell^q$. 而

$$
\bigcup_{1<p<q}\ell^p\supset\bigcup_{p\in\mathbb Q\cap\left(1,q\right)}\ell^p,
$$

故更大的并集 $\bigcup_{1<p<q}\ell^p$ 也不等于 $\ell^q$. $\blacksquare$

### 习题十二

检查商拓扑三种定义的等价性: (a) $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开; (b) 商拓扑是使 $\pi$ 连续的最细拓扑; (c) $F\subset Y$ 闭当且仅当 $\pi^{-1}\left(F\right)\subset X$ 闭.

### 解答 习题十二

**(a) $\Leftrightarrow$ (b)**: 由**定义 11.1** (商拓扑), 拓扑 $\mathcal O_Y=\left\{U\subset Y:\pi^{-1}\left(U\right)\text{ 开}\right\}$ 使 $\pi$ 连续 (由**定义 3.3** (连续映射)). 若 $\mathcal O'$ 是另一个使 $\pi$ 连续的拓扑, 则对 $U\in\mathcal O'$, $\pi^{-1}\left(U\right)$ 开, 故 $U\in\mathcal O_Y$, 即 $\mathcal O'\subset\mathcal O_Y$. 故 $\mathcal O_Y$ 是使 $\pi$ 连续的最细拓扑, 即**定义 11.14** (最终拓扑) 意义下的最终拓扑. 反之最终拓扑由该条件唯一确定.

**(a) $\Leftrightarrow$ (c)**: 由**定义 3.2** (闭集), $F\subset Y$ 闭当且仅当 $Y\setminus F$ 开; 而 $\pi^{-1}\left(Y\setminus F\right)=X\setminus\pi^{-1}\left(F\right)$. 由 (a), $Y\setminus F$ 开当且仅当 $X\setminus\pi^{-1}\left(F\right)$ 开, 即 $\pi^{-1}\left(F\right)$ 闭. 故 (a) 与 (c) 等价.

三者一致, 且由**定义 11.2** (商映射), $\pi:X\to Y$ 满足 $U$ 开 $\Leftrightarrow$ $\pi^{-1}\left(U\right)$ 开, 故 $\pi$ 是商映射. $\blacksquare$

### 习题十三

(树皮定理, 函数法证明) 设 $\left(E,d\right)$ 是度量空间, $A,B\subset E$ 是不相交闭集. 证明存在连续函数 $f:E\to\left[0,1\right]$ 使 $f\big|_A=0$, $f\big|_B=1$. 此即度量空间版本的**定理 7.2** (乌雷松引理).

### 解答 习题十三

由**定义 6.15** (点到集合的距离), 考虑 $d\left(x,A\right)$ 与 $d\left(x,B\right)$. 先证 $x\mapsto d\left(x,A\right)$ 连续: 对 $x,y$, 由三角不等式 (**定义 6.1** (度量空间)), 对任意 $a\in A$, $d\left(x,a\right)\le d\left(x,y\right)+d\left(y,a\right)$, 取下确界得 $d\left(x,A\right)\le d\left(x,y\right)+d\left(y,A\right)$; 交换 $x,y$ 得 $\left|d\left(x,A\right)-d\left(y,A\right)\right|\le d\left(x,y\right)$, 故利普希茨连续.

因 $A,B$ 不相交闭且不相交, 对 $x\in E$, $d\left(x,A\right)+d\left(x,B\right)>0$ (若为 $0$, 则 $x\in\overline A=A$ 且 $x\in\overline B=B$, 矛盾). 定义

$$
f\left(x\right)=\frac{d\left(x,A\right)}{d\left(x,A\right)+d\left(x,B\right)}.
$$

分母连续且正, 分子连续, 故 $f$ 连续 (由**定义 3.3** (连续映射)). 当 $x\in A$, $d\left(x,A\right)=0$, 故 $f\left(x\right)=0$; 当 $x\in B$, $d\left(x,B\right)=0$, 故 $f\left(x\right)=1$. 由构造 $0\le f\le 1$. 这就用函数法构造了分离 $A,B$ 的连续函数, 即**定理 7.2** (乌雷松引理) 在度量空间上的形式. $\blacksquare$
