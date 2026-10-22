# 作业 9

> **定义 3.18** (拓扑空间)<br>集合 $X$ 装备开集族, 满足: $\emptyset,X$ 开; 任意个开集之并开; 有限个开集之交开. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>双射 $f:X\to Y$ 双向连续 ( $f$ 与 $f^{-1}$ 都连续). (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定理 4.2** (连通空间的连续像)<br>连通空间在连续映射下的像仍连通. (教材 $\S4$)

> **定理 4.6** (扇形连通)<br>有限或可数个有公共点的连通集之并仍连通. (教材 $\S4$)

> **定义 4.18** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.23** (凸集)<br>$K\subset\mathbb R^n$ 凸即 $x,y\in K$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 $\S4$)

> **定理 5.2** (区间紧)<br>区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 6.1** (紧 $=$ 序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.3** (紧度量空间完备)<br>紧度量空间是**定义 6.38** (完备度量空间). (教材 $\S6$)

> **定理 6.7** (连续函数的一致极限连续)<br>连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **定理 6.8** ($C\left(X,Y\right)$ 完备)<br>$Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 可数个无处稠密集之并不是全空间. (教材 $\S6$)

> **定理 6.14** (递增闭集族)<br>完备度量空间 (或局部紧豪斯多夫空间) 若为可数个闭集之并, 则至少一个闭集含非空开集. (教材 $\S6$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备赋范线性空间. (2025 卷 B)

> **定义 6.22** (绝对收敛级数)<br>级数 $\sum x_n$ 绝对收敛, 若 $\sum\left\|x_n\right\|<\infty$. (题集 $\S4.4$)

> **定义 6.23** (幂零映射)<br>线性算子 $T$ 满足 $T^n=0$ 对某个 $n$. (2025 卷 B)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.36** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.41** (一致收敛与一致度量)<br>$d\left(f,g\right)=\sup_X\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛当且仅当 $d\left(f_n,g\right)\to0$. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.49** (等距映射)<br>满足 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)$ 的映射 $f$. (题集 $\S3.4$)

> **定义 7.4** (局部紧空间)<br>称 $X$ 是局部紧的, 若每点有紧邻域; 局部紧豪斯多夫空间中每点有由闭紧邻域构成的邻域基. (Munkres $\S29$)

### 习题一

设 $Y$ 为**定义 6.38** (完备度量空间), $X$ 为拓扑空间. 证明在 $Y^X$ 中以**定义 6.41** (一致收敛与一致度量) 给出的有界连续函数集 $C_b\left(X,Y\right)$ 是完备的.

### 解答 习题一

设 $\left(f_n\right)\subset C_b\left(X,Y\right)$ 是一致度量下的**定义 6.37** (柯西列). 固定 $x\in X$, $\left(f_n\left(x\right)\right)$ 是 $Y$ 中的柯西列, 由**定义 6.38** (完备度量空间), 逐点极限 $f\left(x\right)$ 存在. 又由柯西条件 $\sup_x d\left(f_n\left(x\right),f_m\left(x\right)\right)\to0$, 令 $m\to\infty$ 得 $\sup_x d\left(f_n\left(x\right),f\left(x\right)\right)\to0$, 即 $f_n$ 一致收敛到 $f$. 由**定理 6.7** (连续函数的一致极限连续), $f$ 连续; 有界性由 $d\left(f\left(x\right),f_1\left(x\right)\right)\le d\left(f,f_1\right)$ 得. 故 $f\in C_b\left(X,Y\right)$ 且 $f_n\to f$. 这就是**定理 6.8** ($C\left(X,Y\right)$ 完备). $\blacksquare$

### 习题二

设 $K\subset X$ 是紧度量空间. 证明 $C\left(K,\mathbb R\right)$ 完备. 这里 $X$ 是**定义 6.38** (完备度量空间).

### 解答 习题二

由**定理 6.3** (紧度量空间完备), $K$ 紧故 $K$ 完备. 但此处 $C\left(K,\mathbb R\right)$ 中的函数定义在 $K$ 上而取值于 $\mathbb R$, $\mathbb R$ 完备. 由习题一的论证, 柯西列逐点收敛且一致收敛, 由**定理 6.7** (连续函数的一致极限连续) 极限连续, 故 $C\left(K,\mathbb R\right)$ 完备, 即**定理 6.8** ($C\left(X,Y\right)$ 完备) 的特例. $\blacksquare$

### 习题三

(巴拿赫空间) 设 $E$ 是**定义 6.20** (赋范线性空间).

(1) 证明: $E$ 中每个**定义 6.22** (绝对收敛级数) 都收敛, 当且仅当 $E$ 是完备的 (即巴拿赫空间);

(2) 举例说明若 $E$ 不完备, 存在绝对收敛但不收敛的级数.

### 解答 习题三

**第 1 小题**: ($\Rightarrow$) 设 $E$ 中每个绝对收敛级数都收敛. 取**定义 6.37** (柯西列) $\left(x_n\right)$. 由柯西性, 可选子列 $x_{n_k}$ 使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$. 则

$$
\sum_{k=1}^\infty\left\|x_{n_{k+1}}-x_{n_k}\right\|<\sum_{k=1}^\infty2^{-k}<\infty,
$$

即 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛. 其部分和即 $x_{n_{k+1}}-x_{n_1}$, 故子列 $x_{n_k}$ 收敛. 柯西列若有收敛子列则全列收敛 (若 $x_{n_k}\to L$, 由柯西性 $\left\|x_n-L\right\|\le\left\|x_n-x_{n_k}\right\|+\left\|x_{n_k}-L\right\|\to0$). 故 $E$ 完备.

($\Leftarrow$) 设 $E$ 完备, $\sum\left\|x_n\right\|<\infty$. 部分和 $S_N=\sum_{n=1}^Nx_n$ 满足对 $M>N$,

$$
\left\|S_M-S_N\right\|\le\sum_{n=N+1}^M\left\|x_n\right\|\to0,
$$

故 $\left(S_N\right)$ 是**定义 6.37** (柯西列). 由**定义 6.38** (完备度量空间), $S_N$ 收敛, 即级数收敛.

**第 2 小题**: 取 $E=C\left(\left[0,1\right]\right)$ 装备 $L^1$ 范数 $\left\|f\right\|_1=\int_0^1\left|f\right|$, 它不完备. 构造折线函数列 $f_n$, 使 $f_n$ 从 $0$ 线性升到 $1$ 的区间长度为 $1/n$. 则 $\sum\left\|f_n\right\|_1<\infty$ (每段面积 $\le1/n$), 但 $\sum f_n$ 在 $\left(0,1\right)$ 上无界, 不作为连续函数存在. 故绝对收敛但不收敛于 $E$ 中. $\blacksquare$

### 习题四

(贝尔纲, 局部紧版本) 证明: 在局部紧豪斯多夫空间中, 可数个稠密开集之交仍稠密.

### 解答 习题四

设 $\left\{U_n\right\}$ 是稠密开集, $V_0$ 是任意非空开集. 归纳构造非空开集 $V_n$: 由 $U_1$ 稠密, $V_0\cap U_1\neq\emptyset$. 取非空开 $V_1$ 使 $\overline{V_1}\subset V_0\cap U_1$ 且 $\overline{V_1}$ 紧 (由**定义 7.4** (局部紧空间), 局部紧豪斯多夫提供紧邻域基, 可在 $V_0\cap U_1$ 内取闭紧邻域). 归纳地, 由 $U_n$ 稠密, $V_{n-1}\cap U_n\neq\emptyset$, 取非空开 $V_n$ 使 $\overline{V_n}\subset V_{n-1}\cap U_n$ 且 $\overline{V_n}$ 紧.

于是 $\left\{\overline{V_n}\right\}$ 是非空紧集套, 由有限交性质 (紧空间闭集套交非空, 由**定义 3.18** (拓扑空间) 与紧性), 存在 $x\in\bigcap_n\overline{V_n}$. 由 $\overline{V_n}\subset U_n$ 与 $\overline{V_n}\subset V_0$, 有 $x\in V_0\cap\bigcap_nU_n$. 故 $V_0$ 与 $\bigcap_nU_n$ 相交. $V_0$ 任意, 由**定理 6.13** (贝尔纲定理), $\bigcap_nU_n$ 稠密. $\blacksquare$

### 习题五

(不可数个稠密开集不必相交) 证明: $\mathbb Q$ 是可数个无处稠密集之并. 由此说明**定理 6.13** (贝尔纲定理) 中可数性不能放宽到不可数.

### 解答 习题五

$\mathbb Q=\bigcup_{q\in\mathbb Q}\left\{q\right\}$, 每个单点集 $\left\{q\right\}$ 是闭集且内部为空 ($\mathbb R$ 无孤立点, 任何开区间含非 $q$ 的点), 故无处稠密. 这是可数个 ( $\mathbb Q$ 可数) 无处稠密集之并等于 $\mathbb R$ 的稠密子集. 另一方面, 由**定理 6.13** (贝尔纲定理) 及其推论**定理 6.14** (递增闭集族), $\mathbb R$ (完备度量空间) 不能写成可数个无处稠密集之并, 但 $\mathbb R=\mathbb Q\cup\left(\mathbb R\setminus\mathbb Q\right)$ 中 $\mathbb Q$ 是可数个无处稠密集之并, 说明可数个无处稠密集之并可以是稠密的 ( $\mathbb Q$ 在 $\mathbb R$ 中稠密), 但不能等于全空间 $\mathbb R$. 若把可数放宽到不可数, 则 $\mathbb R=\bigcup_{x\in\mathbb R}\left\{x\right\}$ 是不可数个无处稠密集之并, 与**定理 6.14** (递增闭集族) 矛盾, 故可数性不能去掉. $\blacksquare$

### 习题六

设 $E$ 是**定义 6.20** (赋范线性空间). 证明: 若 $E$ 中每个**定义 6.22** (绝对收敛级数) 都收敛, 则 $E$ 完备.

### 解答 习题六

这是习题三第 1 小题中 $\left(\Rightarrow\right)$ 方向的重述. 设柯西列 $\left(x_n\right)$, 选子列 $\left(x_{n_k}\right)$ 使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$. 则 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛, 部分和即 $x_{n_{k+1}}-x_{n_1}$, 故子列收敛. 柯西列含收敛子列则全列收敛 (证明同习题三), 故 $E$ 完备. $\blacksquare$

### 习题七

(勒贝格非常数连续函数) 设 $\lambda$ 是 $\left[0,1\right]$ 上勒贝格测度, $C\left(\left[0,1\right]\right)$ 装备上确界范数. 设

$$
A_n=\left\{f\in C\left(\left[0,1\right]\right):\exists\ a<b\text{ 使 }\lambda\left(\left[a,b\right]\right)\ge\frac1n\text{ 且 }f\text{ 在 }\left[a,b\right]\text{ 上为常数}\right\}.
$$

证明 $A_n$ 无处稠密, 由此得出存在连续函数在任何正测度区间上都不常数.

### 解答 习题七

$A_n$ 闭: 若 $f_k\in A_n$ 且 $f_k\to f$ 一致, 则每个 $f_k$ 在某区间 $\left[a_k,b_k\right]$ (长度 $\ge1/n$) 上为常数. 区间端点抽子列收敛到 $\left[a,b\right]$, $b-a\ge1/n$, 由一致收敛 $f$ 在 $\left[a,b\right]$ 上为常数. 故 $A_n$ 闭.

$A_n$ 无内部: 任给 $f$ 与 $\epsilon>0$, 用锯齿形连续函数 $g$, 在长度 $\ge1/n$ 的区间上振幅 $>\epsilon/2$, 且 $\left\|g-f\right\|_\infty<\epsilon$. 则 $g\notin A_n$, 而 $g\in B\left(f,\epsilon\right)$. 由**定义 3.21** (闭集), $A_n$ 的内部为空.

由**定理 6.13** (贝尔纲定理), $C\left(\left[0,1\right]\right)$ 完备 (即**定理 6.8** ($C\left(X,Y\right)$ 完备)) 不能写成可数个无处稠密集之并, 故 $\bigcup_nA_n\neq C\left(\left[0,1\right]\right)$. 取 $f\notin\bigcup_nA_n$, 则 $f$ 在任何长度 $\ge1/n$ 的区间上不常数对一切 $n$ 成立, 即在任何正测度区间 (长度 $>0$, 从而 $\ge1/n$ 对某个 $n$) 上不常数. 由**定义 3.32** (稠密) 的反面, 这样的 $f$ 存在. $\blacksquare$

### 习题八

设 $E$ 是**定义 6.20** (赋范线性空间). 证明: $E$ 是**定义 6.38** (完备度量空间) 当且仅当 $E$ 中每个**定义 6.22** (绝对收敛级数) 都收敛.

### 解答 习题八

($\Rightarrow$) 设 $E$ 完备, $\sum\left\|x_n\right\|<\infty$. 部分和 $S_N=\sum_{n=1}^Nx_n$ 对 $M>N$ 满足 $\left\|S_M-S_N\right\|\le\sum_{n=N+1}^M\left\|x_n\right\|\to0$, 故 $\left(S_N\right)$ 是**定义 6.37** (柯西列); 由**定义 6.38** (完备度量空间) $S_N$ 收敛.

($\Leftarrow$) 若每个绝对收敛级数收敛, 取**定义 6.37** (柯西列) $\left(x_n\right)$, 选子列使 $\left\|x_{n_{k+1}}-x_{n_k}\right\|<2^{-k}$, 则 $\sum_k\left(x_{n_{k+1}}-x_{n_k}\right)$ 绝对收敛, 由假设收敛, 子列收敛, 柯西列含收敛子列则全列收敛. 故 $E$ 完备.

即**定义 6.22** (绝对收敛级数) 收敛性等价于**定义 6.38** (完备度量空间). $\blacksquare$

### 习题九

(2025 年卷 B 题目三, 20 分). 记 $C\left(\left[0,1\right],\mathbb R\right)$ 为 $\left[0,1\right]$ 上连续实值函数集合, 赋予通常的一致范数. 对 $f\in C\left(\left[0,1\right],\mathbb R\right)$, 定义 $V\left(f\right)=\left\{g\circ f:g\in C\left(\mathbb R,\mathbb R\right)\right\}$.

(1) 证明 $V\left(f\right)$ 是 $C\left(\left[0,1\right],\mathbb R\right)$ 的闭线性子空间.

(2) 证明若 $f$ 单调, 则 $V\left(f\right)=C\left(\left[0,1\right],\mathbb R\right)$.

(3) 证明若 $f$ 不单调, 则 $V\left(f\right)$ 不是 $C\left(\left[0,1\right],\mathbb R\right)$ 的稠密子集.

### 解答 习题九

(1) 线性: $\left(g_1+g_2\right)\circ f=g_1\circ f+g_2\circ f$, $\left(\lambda g_1\right)\circ f=\lambda\left(g_1\circ f\right)$. 闭: 若 $g_n\circ f\to h$ 一致, 则 $h$ 在 $f$ 的每个纤维 $f^{-1}\left(t\right)$ 上为常数. 由此可定义 $g\left(t\right)=h\left(x\right)$ ( $x\in f^{-1}\left(t\right)$ ). $g$ 连续 (由**定义 3.22** (连续映射) 与 $f$ 连续), 故 $h=g\circ f\in V\left(f\right)$. 由**定义 3.21** (闭集), $V\left(f\right)$ 闭.

(2) 若 $f$ 单调, $f$ 的纤维至多单点. $f\left(\left[0,1\right]\right)$ 是区间 $\left[a,b\right]$. 任给 $h\in C\left(\left[0,1\right]\right)$, 定义 $g$ 在 $\left[a,b\right]$ 上为 $g\left(t\right)=h\left(f^{-1}\left(t\right)\right)$; 由单调双射 $f:\left[0,1\right]\to\left[a,b\right]$ (或到其子区间) 连续, $g$ 连续. 由**定义 3.23** (同胚) 单调性即同胚嵌入, $h=g\circ f$, 故 $h\in V\left(f\right)$.

(3) 若 $f$ 不单调, 则存在 $a<b<c$ 使 $f\left(a\right)=f\left(c\right)\neq f\left(b\right)$. 于是 $V\left(f\right)$ 中函数在 $a,c$ 处必取同值. 而函数 $h$ 满足 $h\left(a\right)\neq h\left(c\right)$ 的连续函数不在 $V\left(f\right)$ 中, 且与 $V\left(f\right)$ 保持正距离. 由**定理 6.13** (贝尔纲定理) 与**定理 6.14** (递增闭集族), 完备空间中闭而无内部的子空间不稠密. $\blacksquare$

### 习题十

(等距与拓扑) 设 $\left(X,d_X\right)$, $\left(Y,d_Y\right)$ 是度量空间, $f:X\to Y$ 是**定义 6.49** (等距映射). 证明 $f$ 是单射, 连续, 且 $f^{-1}:f\left(X\right)\to X$ 也是**定义 6.49** (等距映射). 若 $X$ 完备, 证明 $f\left(X\right)$ 完备. 若 $f$ 是满射, 证明 $f$ 是**定义 3.23** (同胚).

### 解答 习题十

单: 由**定义 6.49** (等距映射), $f\left(x\right)=f\left(y\right)\Rightarrow d_Y\left(f\left(x\right),f\left(y\right)\right)=0=d_X\left(x,y\right)\Rightarrow x=y$.

连续: 对任意 $\epsilon>0$, 取 $\delta=\epsilon$, 由**定义 6.35** (度量空间) 与**定义 6.49** (等距映射), $d_X\left(x,y\right)<\delta$ 蕴含 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)<\epsilon$. 由**定义 6.36** (开球) 与**定义 3.22** (连续映射), $f$ 连续.

$f^{-1}$ 是等距: 对 $u=f\left(x\right)$, $v=f\left(y\right)$, $d_X\left(f^{-1}\left(u\right),f^{-1}\left(v\right)\right)=d_X\left(x,y\right)=d_Y\left(u,v\right)$.

$X$ 完备 $\Rightarrow f\left(X\right)$ 完备: 设 $\left(y_n\right)$ 是 $f\left(X\right)$ 中的**定义 6.37** (柯西列), $y_n=f\left(x_n\right)$. 则 $d_X\left(x_n,x_m\right)=d_Y\left(y_n,y_m\right)\to0$, $\left(x_n\right)$ 是柯西列. 由**定义 6.38** (完备度量空间), $x_n\to x\in X$, 故 $y_n=f\left(x_n\right)\to f\left(x\right)\in f\left(X\right)$. 由**定义 6.38** (完备度量空间), $f\left(X\right)$ 完备.

$f$ 满则 $f^{-1}$ 连续 (上面已证 $f^{-1}$ 是等距故连续), $f$ 连续, 故 $f$ 是**定义 3.23** (同胚). $\blacksquare$

### 习题十一

(2025 年卷 B 题目四, 20 分). 设 $X$ 为非空完备度量空间. 证明: 若 $X$ 被可数个闭集 $F_1,F_2,\dots$ 覆盖, 则至少存在一个 $F_n$ 包含非空开集.

### 解答 习题十一

反证, 设每个 $F_n$ 的内部为空. 由**定义 3.18** (拓扑空间), 补集 $G_n=X\setminus F_n$ 是稠密开集 ( $F_n$ 闭且无内部 $\Leftrightarrow G_n$ 开且稠密). 由**定理 6.13** (贝尔纲定理), $\bigcap_nG_n$ 稠密, 特别非空. 取 $x\in\bigcap_nG_n$, 则 $x\notin F_n$ 对一切 $n$, 与 $\bigcup_nF_n=X$ 矛盾. 故存在 $n$ 使 $F_n$ 含非空开集. 这就是**定理 6.14** (递增闭集族). $\blacksquare$

### 习题十二

(2024 年卷 A 题目二, 20 分). 我们记 $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 为 $\mathbb R^3$ 中的单位球面, $D=\left\{\left(x,y\right)\in\mathbb R^2:x^2+y^2\le1\right\}$ 为单位圆盘.

(1) 证明集合 $D^+=\left\{\left(x,y,\sqrt{1-x^2-y^2}\right):\left(x,y\right)\in D\right\}$ 与 $D^-=\left\{\left(x,y,-\sqrt{1-x^2-y^2}\right):\left(x,y\right)\in D\right\}$ 都连通. 由此推导 $S^2$ 连通.

(2) 证明球面 $S^2$ 是路径连通的.

(3) 证明 $\mathbb R^3\setminus\left\{P\right\}$ 与 $S^2$ 同胚, 其中 $P=\left(0,0,2\right)$. 你可以使用球极投影

$$
\pi:\mathbb R^2\to S^2\setminus\left\{\left(0,0,1\right)\right\},\quad
\pi\left(u,v\right)=\frac{\left(2u,2v,u^2+v^2-1\right)}{u^2+v^2+1}.
$$

(4) 证明球面 $S^2$ 是紧的.

### 解答 习题十二

(1) 闭单位圆盘 $D\subset\mathbb R^2$ 由**定义 4.23** (凸集) 是凸集, 凸集中任意两点可由线段连接故路径连通, 路径连通蕴含连通. 映射 $\phi^+:\left(u,v\right)\mapsto\left(u,v,\sqrt{1-u^2-v^2}\right)$ 连续, 其像为 $D^+$. 由**定理 4.2** (连通空间的连续像), $D^+$ 连通. 同理 $D^-$ 连通.

$D^+\cap D^-=\left\{\left(x,y,0\right):x^2+y^2=1\right\}\neq\emptyset$. 由**定理 4.6** (扇形连通), 两个连通集有公共点其并连通, 故 $S^2=D^+\cup D^-$ 连通. 由**定义 4.18** (连通空间), $S^2$ 连通.

(2) 已证 $D^+$ 是 $D$ 在连续映射下的像, $D$ 凸故路径连通, 连续像路径连通; 同理 $D^-$ 路径连通. $D^+\cap D^-\neq\emptyset$, 故 $S^2=D^+\cup D^-$ 路径连通.

(3) 球极投影 $\pi:\mathbb R^2\to S^2\setminus\left\{\left(0,0,1\right)\right\}$ 是双射且双向连续, 由**定义 3.23** (同胚), $\mathbb R^2\cong S^2\setminus\left\{\left(0,0,1\right)\right\}$. 要证 $\mathbb R^3\setminus\left\{P\right\}\cong S^2$, 从 $\mathbb R^3\setminus\left\{P\right\}$ 作以 $P$ 为中心的中心投影到平面 $z=0$, 再经 $\pi$ 映到 $S^2\setminus\left\{\left(0,0,1\right)\right\}$; 北极 $\left(0,0,1\right)$ 对应平面方向无穷远点. 该映射连续双射, 逆连续, 为同胚.

(4) $S^2$ 是函数 $f:\mathbb R^2\to\mathbb R$, $f\left(u,v\right)=\left(u,v,\sqrt{1-u^2-v^2}\right)$ 在闭单位圆盘 $D$ 上的图, 加下半球面. 或: $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 是 $\mathbb R^3$ 中有界闭集, 由**定理 5.2** (区间紧) 在高维的推广 ( $\mathbb R^n$ 中有界闭集紧, 即海涅-博雷尔), $S^2$ 紧. 也可由 $S^2$ 是紧集 $D$ 在连续映射下的像 ($D^+$), 与另一半球面拼接; $D$ 闭且有界故紧 (**定理 6.1** (紧 $=$ 序列紧)), 连续像紧, 故 $S^2$ 紧. $\blacksquare$

### 习题十三

(2025 年卷 B 题目五, 20 分). 记 $X$ 为巴拿赫空间, $T:X\to X$ 为连续线性映射, 记 $\left\|T\right\|=\sup_{\left\|x\right\|=1}\left\|T\left(x\right)\right\|$.

(1) 证明若 $\left\|T\right\|<1$, 则映射 $f:X\to X$, $f\left(x\right)=x-T\left(x\right)$ 为单射.

(2) 进一步证明 $f$ 为满射.

(3) 证明 $f$ 为**定义 3.23** (同胚).

(4) 假设存在 $n\ge1$ 使得 $T^n$ 是**定义 6.23** (幂零映射). 证明 $f$ 是双射.

### 解答 习题十三

(1) 设 $f\left(x\right)=f\left(y\right)$, 则 $x-T\left(x\right)=y-T\left(y\right)$, 即 $\left(x-y\right)=T\left(x-y\right)$. 于是

$$
\left\|x-y\right\|=\left\|T\left(x-y\right)\right\|\le\left\|T\right\|\left\|x-y\right\|.
$$

若 $x\neq y$, 则 $\left\|x-y\right\|>0$, 两边除以 $\left\|x-y\right\|$ 得 $1\le\left\|T\right\|$, 与 $\left\|T\right\|<1$ 矛盾. 故 $x=y$, $f$ 单射.

(2) 对任意 $y\in X$, 考虑迭代 $x_{n+1}=y+T\left(x_n\right)$. 则

$$
\left\|x_{n+1}-x_n\right\|=\left\|T\left(x_n-x_{n-1}\right)\right\|\le\left\|T\right\|\left\|x_n-x_{n-1}\right\|\le\left\|T\right\|^n\left\|x_1-x_0\right\|.
$$

由**定义 6.22** (绝对收敛级数), $\sum_n\left\|x_{n+1}-x_n\right\|<\sum_n\left\|T\right\|^n\left\|x_1-x_0\right\|<\infty$. 由**定义 6.21** (巴拿赫空间) 即 $X$ 完备, 由习题三结论 (绝对收敛级数收敛), $x_n$ 收敛到某 $x$. 取极限 $x=y+T\left(x\right)$, 即 $f\left(x\right)=y$. 故 $f$ 满射.

(3) $f=I-T$ 连续 ( $T$ 连续, $I$ 连续). 由第 1、2 步, $f$ 双射. 逆映射由级数给出: $f^{-1}=I+T+T^2+\cdots$, 且 $\left\|f^{-1}\right\|\le1/\left(1-\left\|T\right\|\right)$, 故 $f^{-1}$ 连续. 由**定义 3.23** (同胚), $f$ 是同胚.

(4) 设 $T^n=0$. 对任意 $y$, 令 $x=y+T\left(y\right)+T^2\left(y\right)+\cdots+T^{n-1}\left(y\right)$. 则

$$
\left(I-T\right)x=\left(I-T\right)\sum_{k=0}^{n-1}T^k\left(y\right)=\left(I-T^n\right)\left(y\right)=y,
$$

因 $T^n=0$. 故 $f\left(x\right)=y$, $f$ 满射. 单射: $f\left(x\right)=0\Rightarrow x=T\left(x\right)\Rightarrow x=T^n\left(x\right)=0$. 故 $f$ 双射. $\blacksquare$
