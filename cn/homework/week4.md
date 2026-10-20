# 作业 4

> **定理 2.8** (施罗德-伯恩斯坦定理)<br>若同时存在 $X\to Y$ 与 $Y\to X$ 的单射, 则 $X$ 与 $Y$ 基数相等. (教材 $\S2$)

> **定理 2.13** (实数与自然数幂集等势)<br>$\left|\mathbb R\right|=\left|\mathcal P\left(\mathbb N\right)\right|$. (教材 $\S2$)

> **定义 3.19** (子空间拓扑)<br>设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 $\S3$)

> **定义 3.20** (边界)<br>$\partial A=\overline A\setminus\operatorname{int}\left(A\right)$. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.26** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定理 4.1** (区间连通)<br>$\left[0,1\right]$ 连通; 由此任意区间连通. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f:X\to Y$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.3** (路径连通蕴含连通)<br>路径连通空间是连通的. (教材 $\S4$)

> **定理 4.5** (可数度量空间完全不连通)<br>每个可数度量空间都是完全不连通的. (教材 $\S4$)

> **定理 4.6** (扇形连通)<br>一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 $\S4$)

> **定理 4.7** (乘积连通)<br>连通集 $A,B$ 之积 $A\times B$ 连通; 有限个连通集的乘积连通. (教材 $\S4$)

> **定义 4.8** (连通分支)<br>含点 $x$ 的唯一极大连通集 $A\left(x\right)$; 它是闭集; 分支数有限时分支开. (教材 $\S4$)

> **定义 4.10** (局部路径连通)<br>每点有由路径连通邻域组成的邻域基; 局部路径连通且连通蕴含路径连通. (题集 $\S2.1$)

> **定义 4.14** ($\epsilon$-链空间)<br>$X$ 是 $\epsilon$-链的, 若任意 $a,b\in X$ 可由相邻距离 $<\epsilon$ 的有限点列连接; 对一切 $\epsilon>0$ 都成立称 $\epsilon$-链空间. (题集 $\S4.5$)

> **定理 4.15** (闭包保持连通性)<br>连通集的闭包仍连通. (教材 $\S4$)

> **定义 4.18** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.19** (既开又闭集)<br>既开又闭的集合称为既开又闭集; $X$ 连通当且仅当 $\emptyset$ 与 $X$ 是仅有的既开又闭集. (教材 $\S4$)

> **定义 4.20** (完全不连通)<br>空间的唯一连通子集是单点集. (教材 $\S4$)

> **定义 4.22** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $\gamma:\left[0,1\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.23** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定义 4.24** (拓扑学家正弦曲线)<br>$y=\sin\left(1/x\right)$ 在 $\left(0,1\right]$ 上的图像与 $y$ 轴上 $\left[-1,1\right]$ 的并; 它连通但不路径连通. (教材 $\S4$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.36** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

### 习题一

证明下列定理: $\mathbb R$ 的任一开子集 $U$ 可唯一地写成可数个互不相交的开区间之并, 且这些区间的端点不属于 $U$. 提示: 可考虑含 $x\in U$ 的极大开区间 $I_x\subset U$.

### 解答 习题一

由**定义 6.36** (开球), $\mathbb R$ 的通常拓扑以开区间为基. 对每个 $x\in U$, 令 $I_x$ 为一切含 $x$ 且含于 $U$ 的开区间之并. 因每个这样的开区间都含 $x$, 其并仍是含 $x$ 的开区间 (一族两两相交于同一点的开区间之并为开区间), 含于 $U$, 且在含 $x$ 且含于 $U$ 的开区间中极大.

断言: 对 $x,y\in U$, 或者 $I_x=I_y$, 或者 $I_x\cap I_y=\emptyset$. 事实上, 若 $I_x\cap I_y\neq\emptyset$, 则 $I_x\cup I_y$ 是含 $x,y$ 且含于 $U$ 的开区间, 由 $I_x$ 与 $I_y$ 的极大性, $I_x\cup I_y\subset I_x$ 且 $I_x\cup I_y\subset I_y$, 故 $I_x=I_y=I_x\cup I_y$.

可数性: 每个 $I_x$ 是非空开区间, 可取其中一个有理数 $q_x$. 因诸 $I_x$ 互不相交, 不同 $x$ 给出不同 $q_x$, 故 $\left\{I_x:x\in U\right\}$ 与 $\mathbb Q$ 的某子集一一对应, 因而是可数族. 又因每个 $x\in U$ 都含于 $I_x$, 故 $U=\bigcup_{x\in U}I_x$.

端点: 写 $I_x=\left(a_x,b_x\right)$. 若 $a_x\in U$, 则 $a_x\in I_y$ 对某 $y\in U$. 因 $I_y$ 开, 存在 $\epsilon>0$ 使 $\left(a_x-\epsilon,a_x+\epsilon\right)\subset I_y\subset U$. 于是 $\left(a_x-\epsilon,b_x\right)$ 是含 $x$ 且含于 $U$ 的开区间, 它比 $I_x$ 向左更长, 与 $I_x$ 的极大性矛盾. 故 $a_x\notin U$. 同理 $b_x\notin U$.

唯一性: 若另有分解 $U=\bigcup_{j\in J}J_j$, 其中 $J_j$ 为互不相交开区间. 对每个 $x\in U$, $x$ 属于唯一的 $J_{j\left(x\right)}$. $J_{j\left(x\right)}$ 是含 $x$ 且含于 $U$ 的开区间, 由 $I_x$ 的极大性 $J_{j\left(x\right)}\subset I_x$; 反之, $I_x$ 是含 $x$ 且含于 $U$ 的开区间, 而 $J_{j\left(x\right)}$ 是含 $x$ 的极大连通开块, 故 $I_x\subset J_{j\left(x\right)}$. 因此 $J_{j\left(x\right)}=I_x$, 两分解一致. $\blacksquare$

### 习题二

证明 $\mathbb R$ 与 $\mathbb R^2$ 基数相同, 但不同胚. 提示: 可考察 $\mathbb R^2-\left\{0\right\}$ 的像.

### 解答 习题二

先证基数相同. 由**定理 2.13** (实数与自然数幂集等势), $\mathbb R$ 与 $\mathcal P\left(\mathbb N\right)$ 等势. 映射 $\mathbb R^2\to\mathbb R$ 如下构造: 由**定理 2.13** (实数与自然数幂集等势), 把一对实数对应到一对子集 $\left(A,B\right)\subset\mathcal P\left(\mathbb N\right)^2$, 再作

$$
\left(A,B\right)\longmapsto\left\{2n:n\in A\right\}\cup\left\{2n+1:n\in B\right\}\subset\mathbb N.
$$

该映射是单射 (偶数位编码 $A$, 奇数位编码 $B$), 故 $\mathbb R^2\to\mathcal P\left(\mathbb N\right)\cong\mathbb R$ 有单射. 反过来 $x\mapsto\left(x,0\right)$ 给出 $\mathbb R\to\mathbb R^2$ 的单射. 由**定理 2.8** (施罗德-伯恩斯坦定理), $\mathbb R$ 与 $\mathbb R^2$ 基数相等.

再证不同胚. 反设存在同胚 $h:\mathbb R\to\mathbb R^2$. 由**定义 3.23** (同胚), $h$ 限制到 $\mathbb R-\left\{0\right\}$ 上, 配以**定义 3.19** (子空间拓扑), 仍给出到 $\mathbb R^2-\left\{h\left(0\right)\right\}$ 的同胚. 考察两边挖去一点后的连通分支数.

在 $\mathbb R$ 一侧,

$$
\mathbb R-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right).
$$

由**定理 4.1** (区间连通), 两区间各自连通; 它们是不相交非空开集, 故由**定义 4.18** (连通空间) $\mathbb R-\left\{0\right\}$ 不连通, 由**定义 4.8** (连通分支) 它恰有两个连通分支.

在 $\mathbb R^2$ 一侧, $\mathbb R^2-\left\{0\right\}$ 路径连通: 任取两点 $u,v$, 选点 $w$ 使 $0,u,w$ 与 $0,w,v$ 均不共线, 折线 $u\to w\to v$ 避开原点. 由**定理 4.3** (路径连通蕴含连通), $\mathbb R^2-\left\{0\right\}$ 连通, 由**定义 4.8** (连通分支) 它只有一个连通分支.

同胚保持连通分支的个数 (连通集映为连通集, 极大性保持). 但上述同胚把有两个分支的 $\mathbb R-\left\{0\right\}$ 映到只有一个分支的 $\mathbb R^2-\left\{h\left(0\right)\right\}$, 矛盾. 故 $\mathbb R$ 与 $\mathbb R^2$ 不同胚. $\blacksquare$

### 习题三

证明不存在连续函数 $f:\mathbb R\to\mathbb R$ 满足 $f\left(P\right)\subset\mathbb Q$ 且 $f\left(\mathbb Q\right)\subset P$, 其中 $P$ 为素数全体. 提示: 可考察 $f\left(\mathbb R\right)$.

### 解答 习题三

$\mathbb R$ 是**定义 4.23** (凸集) 意义下的凸集, 故路径连通, 由**定理 4.3** (路径连通蕴含连通) $\mathbb R$ 连通. 由**定理 4.2** (连续像连通), $f\left(\mathbb R\right)$ 是 $\mathbb R$ 中的连通子集.

$\mathbb Q$ 在 $\mathbb R$ 中稠密 (**定义 3.32** (稠密)). 由 $f$ 连续, $f\left(\mathbb Q\right)$ 在 $f\left(\mathbb R\right)$ 中稠密: 对任意 $y=f\left(x\right)\in f\left(\mathbb R\right)$, 取有理数列 $q_n\to x$, 则 $f\left(q_n\right)\to f\left(x\right)=y$.

由题设 $f\left(\mathbb Q\right)\subset P$. 素数集 $P$ 在 $\mathbb R$ 中是闭集 (每个素数孤立, 无聚点), 故由**定义 3.26** (闭包),

$$
f\left(\mathbb R\right)\subset\overline{f\left(\mathbb Q\right)}\subset\overline{P}=P.
$$

于是连通集 $f\left(\mathbb R\right)$ 含于 $P$. 素数集 $P$ 作为子空间是离散的 (每点孤立), 而离散空间的任一子集既开又闭, 由**定义 4.18** (连通空间) 离散空间的连通子集只能是单点集. 故 $f\left(\mathbb R\right)=\left\{p_0\right\}$, 即 $f$ 必为常值映射. 因此满足条件的连续函数只能是常值映射, 不存在非常值的这类连续函数. $\blacksquare$

### 习题四

证明连通且局部路径连通的空间必路径连通. 提示: 可考察某点的"路径连通"分支.

### 解答 习题四

设 $X$ 连通且局部路径连通, 固定 $x\in X$, 令

$$
C=\left\{y\in X:y\text{ 与 }x\text{ 之间有连续路径相连}\right\}.
$$

先证 $C$ 开. 任取 $y\in C$. 由**定义 4.10** (局部路径连通), $y$ 有路径连通邻域 $V$. 对任意 $z\in V$, $z$ 与 $y$ 在 $V$ 中有路径, $y$ 与 $x$ 有路径, 两段拼接即得 $z$ 与 $x$ 的路径, 故 $z\in C$, 从而 $V\subset C$. 由 $y$ 任意, $C$ 开.

再证 $C$ 闭. 取 $y\in\overline C$ (**定义 3.26** (闭包)). 由**定义 4.10** (局部路径连通), $y$ 有路径连通邻域 $V$. 由 $\overline C$ 的定义, $V\cap C\neq\emptyset$, 取 $z\in V\cap C$. $z$ 与 $x$ 有路径, $y$ 与 $z$ 在 $V$ 中有路径, 拼接得 $y$ 与 $x$ 的路径, 故 $y\in C$. 于是 $\overline C\subset C$, $C$ 闭.

故 $C$ 既开又闭 (**定义 4.19** (既开又闭集)). $X$ 连通 (**定义 4.18** (连通空间)), 且 $C\neq\emptyset$ ($x\in C$), 故由**定义 4.19** (既开又闭集) 得 $C=X$. 由**定义 4.22** (路径连通), $X$ 路径连通. $\blacksquare$

### 习题五

证明多于一点的连通度量空间不可数.

### 解答 习题五

反设 $\left(X,d\right)$ 是**定义 6.35** (度量空间) 意义下的连通度量空间, $\left|X\right|\ge2$, 且 $X$ 可数. 由**定理 4.5** (可数度量空间完全不连通), $X$ 是**定义 4.20** (完全不连通) 意义下的完全不连通空间, 即其唯一连通子集是单点集.

但 $X$ 本身作为子集由题设连通 (**定义 4.18** (连通空间)), 且 $\left|X\right|\ge2$, 与完全不连通矛盾. 故 $X$ 不可数. $\blacksquare$

### 习题六

证明一般线性群 $GL\left(n,\mathbb R\right)$ (即 $n\times n$ 实可逆矩阵之群) 由两个连通分支组成: 行列式为正者与行列式为负者; 特别地它不连通. 证明与之对照, $GL\left(n,\mathbb C\right)$ 连通.

### 解答 习题六

行列式映射 $\det:GL\left(n,\mathbb R\right)\to\mathbb R-\left\{0\right\}$ 是矩阵元素的多项式, 故由**定义 3.22** (连续映射) 它连续. 由**定理 4.2** (连续像连通), $GL\left(n,\mathbb R\right)$ 中连通子集的行列式必落入 $\mathbb R-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right)$ 的同一连通分支. 故

$$
GL\left(n,\mathbb R\right)=GL^{+}\sqcup GL^{-}
$$

其中 $GL^{+}=\left\{A:\det A>0\right\}$, $GL^{-}=\left\{A:\det A<0\right\}$, 二者不相交且各自为开集.

现证 $GL^{+}$ 路径连通. 对任意 $A\in GL^{+}$, 作格拉姆-施密特分解 $A=QR$, 其中 $Q\in SO\left(n\right)$, $R$ 为对角元全正的上三角阵. 全体这样的 $R$ 构成**定义 4.23** (凸集) 意义下的凸集, 故路径连通; $SO\left(n\right)$ 中任一正交阵可分解为平面旋转之积, 各旋转角连续收缩到 $0$ 即与单位阵相连. 拼接两条路径, $A$ 与单位阵在 $GL^{+}$ 中路径相连. 同理, 若 $A\in GL^{-}$, 取 $D=\operatorname{diag}\left(-1,1,\dots,1\right)$, 则 $AD\in GL^{+}$, $AD$ 与单位阵路径相连, 从而 $A$ 与 $D$ 路径相连. 故 $GL^{+}$ 与 $GL^{-}$ 各自路径连通, 由**定义 4.8** (连通分支) 它们正是 $GL\left(n,\mathbb R\right)$ 的两个连通分支; 由**定义 4.18** (连通空间) $GL\left(n,\mathbb R\right)$ 不连通.

对复的情形, 任意 $A\in GL\left(n,\mathbb C\right)$, 格拉姆-施密特分解 $A=QU$, 其中 $U$ 为酉阵. 酉阵可对角化, 特征值均在单位圆上, 各辐角连续收缩到 $0$ 即与单位阵相连, 故 $U$ 与单位阵路径相连, 从而 $A$ 与单位阵路径相连. 故 $GL\left(n,\mathbb C\right)$ 路径连通, 由**定理 4.3** (路径连通蕴含连通) 它连通. $\blacksquare$

### 习题七

证明拓扑学家正弦曲线连通但不路径连通.

### 解答 习题七

记

$$
G=\left\{\left(x,\sin\frac1x\right):0<x\le1\right\},\quad L=\left\{0\right\}\times\left[-1,1\right],\quad S=G\cup L.
$$

由**定义 4.24** (拓扑学家正弦曲线), $S$ 即拓扑学家正弦曲线.

先证连通. $G$ 以 $x$ 为参数路径连通, 故由**定理 4.3** (路径连通蕴含连通) $G$ 连通. 当 $x\to0^{+}$ 时 $\sin\left(1/x\right)$ 在 $\left[-1,1\right]$ 上稠密振荡, 故 $G$ 的闭包 $\overline G=G\cup L=S$ (**定义 3.26** (闭包)). 由**定理 4.15** (闭包保持连通性), $\overline G$ 连通, 故 $S$ 连通 (**定义 4.18** (连通空间)).

再证不路径连通. 反设存在路径 $\gamma:\left[0,1\right]\to S$ 以 $\left(0,0\right)\in L$ 为起点, 以 $\left(1,\sin1\right)\in G$ 为终点. 令 $t_0=\inf\left\{t:\gamma\left(t\right)\text{ 的横坐标}>0\right\}$. 由连续性 $\gamma\left(t_0\right)\in L$. 取 $t_n\downarrow t_0$, 则 $\gamma\left(t_n\right)=\left(x_n,\sin\left(1/x_n\right)\right)$, $x_n\to0^{+}$. 序列 $\sin\left(1/x_n\right)$ 既有收敛到 $1$ 的子列, 又有收敛到 $-1$ 的子列, 不可能收敛到 $\gamma\left(t_0\right)$ 的纵坐标, 与 $\gamma$ 连续矛盾. 故不存在这样的路径, $S$ 不路径连通, 即它不是**定义 4.22** (路径连通) 意义下的路径连通空间. $\blacksquare$

### 习题八

连通性与连续函数. 证明: $X$ 是**定义 4.18** (连通空间) 当且仅当一切连续映射 $f:X\to\left\{0,1\right\}$ (目标装备离散拓扑) 都是常值的. 再设 $A,B$ 是两个连通度量空间, $X,Y$ 分别是 $A,B$ 的真子集. 证明 $C=\left(A\times B\right)\setminus\left(X\times Y\right)$ 是 $A\times B$ 的连通子集.

### 解答 习题八

$\left(\Rightarrow\right)$ 设 $X$ 是**定义 4.18** (连通空间), $f:X\to\left\{0,1\right\}$ 连续. 由**定理 4.2** (连续像连通), $f\left(X\right)$ 连通; 离散两点集 $\left\{0,1\right\}$ 的连通子集只有单点, 故 $f\left(X\right)$ 是单点集, 即 $f$ 常值.

$\left(\Leftarrow\right)$ 若 $X$ 不连通, 则 $X=U\cup V$, $U,V$ 非空不相交开集. 定义 $f$ 在 $U$ 上取 $0$, 在 $V$ 上取 $1$; 因 $U,V$ 既开又闭, 由**定义 3.22** (连续映射) $f$ 连续, 但 $f$ 非常值. 矛盾.

第二问: $C=\left(\left(A\setminus X\right)\times B\right)\cup\left(A\times\left(B\setminus Y\right)\right)$. 因 $X,Y$ 是真子集, 可取 $a_0\in A\setminus X$, $b_0\in B\setminus Y$. 固定 $b_0$, 集合 $A\times\left\{b_0\right\}$ 由**定理 4.7** (乘积连通) 连通. 对每个 $a\in A\setminus X$, 纤维 $\left\{a\right\}\times B$ 连通 (**定理 4.7** (乘积连通)), 且与 $A\times\left\{b_0\right\}$ 交于 $\left(a,b_0\right)$. 由**定理 4.6** (扇形连通), $S=A\times\left\{b_0\right\}\cup\bigcup_{a\in A\setminus X}\left\{a\right\}\times B$ 连通. 再对每个 $b\in B\setminus Y$, 纤维 $A\times\left\{b\right\}$ 连通, 且与 $S$ 交于 $\left(a_0,b\right)$. 再用**定理 4.6** (扇形连通), 加入所有 $A\times\left\{b\right\}$ 后仍连通, 所得正是 $C$. $\blacksquare$

### 习题九

连通性与边界. 设 $E$ 是连通度量空间, $F$ 是 $E$ 的闭集. 证明: 若 $F$ 的边界 $\partial F$ 连通, 则 $F$ 连通. 可先证明连续函数的限制连续. 再举例说明 $F$ 不假设闭时结论失效.

### 解答 习题九

反设 $F$ 不连通. 则 $F$ 有非空分离 $F=A\cup B$, $A,B$ 非空不相交, 且在 $F$ 中既开又闭. 因 $F$ 在 $E$ 中闭, 由**定义 3.21** (闭集), $A,B$ 在 $E$ 中也闭. 边界 $\partial F=F\cap\overline{E\setminus F}$. 断言

$$
\partial F=\left(A\cap\overline{E\setminus F}\right)\cup\left(B\cap\overline{E\setminus F}\right),
$$

两边都非空. 若 $A\cap\overline{E\setminus F}=\emptyset$, 则 $A\subset\operatorname{int}\left(F\right)$; 又 $A$ 在 $F$ 中开, 即 $A=F\cap O$ ($O$ 开于 $E$), 于是 $A=O\cap\operatorname{int}\left(F\right)$ 在 $E$ 中开. $A$ 在 $E$ 中既开又闭, 由**定义 4.19** (既开又闭集), $E$ 连通推出 $A=\emptyset$ 或 $E$, 与 $A$ 是 $F$ 的非空真子集矛盾. 故 $A\cap\overline{E\setminus F}\neq\emptyset$, 同理 $B\cap\overline{E\setminus F}\neq\emptyset$. 这两个非空不交闭集分离了 $\partial F$, 与 $\partial F$ 连通矛盾. 故 $F$ 连通.

反例: 取 $E=\left[0,1\right]$, $F=\left[0,1/2\right)\cup\left(1/2,1\right]$. $F$ 不闭, 且不连通; 但 $\partial F=\left\{1/2\right\}$ 是单点, 连通. $\blacksquare$

### 习题十

链空间. 称度量空间 $X$ 是 $\epsilon$-链的, 若任意 $a,b\in X$ 可由有限点列 $x_0=a,\dots,x_n=b$ 连接使 $d\left(x_i,x_{i+1}\right)<\epsilon$; 对一切 $\epsilon>0$ 都成立称**定义 4.14** ($\epsilon$-链空间). 证明: $X$ 连通则 $X$ 是 $\epsilon$-链空间; $X$ 紧且 $\epsilon$-链则 $X$ 连通; 举例说明 $\epsilon$-链空间可以不连通.

### 解答 习题十

连通 $\Rightarrow$ $\epsilon$-链: 固定 $\epsilon>0$, 定义 $a\sim b$ 为存在 $\epsilon$-链. 等价类在**定义 6.36** (开球) $B\left(x,\epsilon\right)$ 下封闭, 故每个等价类开; 其余等价类之并也开. 由**定义 4.19** (既开又闭集), 连通空间只有一个等价类, 即 $X$ 是**定义 4.14** ($\epsilon$-链空间).

紧且 $\epsilon$-链 $\Rightarrow$ 连通: 反设 $X$ 不连通, 则 $X=A\cup B$ 为非空不交闭集分离. $A,B$ 是紧度量空间, 距离 $\delta=d\left(A,B\right)>0$: 取 $a_n\in A$, $b_n\in B$ 使 $d\left(a_n,b_n\right)\to\delta$, 由**定理 6.1** (紧=序列紧) 抽子列 $a_{n_j}\to a\in A$, $b_{n_j}\to b\in B$, 得 $d\left(a,b\right)=\delta>0$. 取 $\epsilon<\delta$, 则 $\epsilon$-链不可能从 $A$ 跨到 $B$, 与 $\epsilon$-链矛盾.

$\epsilon$-链但不连通的例子: 有理数集 $\mathbb Q$ 装备通常度量. 对任意 $\epsilon>0$, 任意两个有理数之间可插入间距小于 $\epsilon$ 的有理点列, 故 $\mathbb Q$ 是 $\epsilon$-链的; 但 $\mathbb Q$ 完全不连通. $\blacksquare$

### 习题十一

不动点与连通性. 设 $X$ 是度量空间, 假设一切连续映射 $f:X\to X$ 都有不动点. 证明 $X$ 连通. 再问: 若 $X$ 紧且连通, 是否一切连续映射 $f:X\to X$ 都有不动点?

### 解答 习题十一

反设 $X$ 不连通, 则 $X=A\cup B$, $A,B$ 非空不相交且由**定义 4.19** (既开又闭集) 既开又闭. 取 $a\in A$, $b\in B$, 定义 $f$: 在 $A$ 上取常值 $b$, 在 $B$ 上取常值 $a$. 因 $A,B$ 既开又闭, 由**定义 3.22** (连续映射) $f$ 连续; 但 $f\left(A\right)\subset B$, $f\left(B\right)\subset A$, 而 $A\cap B=\emptyset$, 故 $f$ 无不动点. 矛盾. 故 $X$ 连通.

紧且连通不足以保证不动点: 取圆周 $X=S^1$, 旋转 $90^\circ$ 的映射 $f\left(e^{i\theta}\right)=e^{i\left(\theta+\pi/2\right)}$. $S^1$ 紧且连通, $f$ 连续, 但 $f$ 无不动点. $\blacksquare$

### 习题十二

(连通边界) 设 $\left(E,d\right)$ 是连通度量空间, $F\subset E$ 闭, 且 $\partial F$ 连通. 证明 $F$ 连通.

### 解答 习题十二

反证. 若 $F$ 不连通, 由**定义 4.18** (连通空间), 存在 $F=A\sqcup B$, $A,B$ 非空、在 $F$ 中既开又闭. 因 $F$ 闭于 $E$, $A,B$ 闭于 $E$.

由**定义 3.20** (边界), $\partial F=\overline F\setminus\operatorname{int}\left(F\right)=F\setminus\operatorname{int}\left(F\right)$. 因 $\partial F$ 连通, 它不能同时与 $A,B$ 相交 (否则 $\partial F\cap A$ 与 $\partial F\cap B$ 是 $\partial F$ 的非空分离). 故不妨 $\partial F\subset A$. 于是 $B\cap\partial F=\emptyset$, 即 $B\subset\operatorname{int}\left(F\right)$.

$B$ 闭于 $E$, 且 $B\subset\operatorname{int}\left(F\right)$. 又 $B$ 在 $F$ 中开, 即 $B=F\cap O$, $O$ 开于 $E$. 因 $B\subset\operatorname{int}\left(F\right)$, $B=O\cap\operatorname{int}\left(F\right)$, 即 $B$ 开于 $E$. 故 $B$ 既开又闭于 $E$, 非空且不等于 $E$ ($B\subset F\subsetneq E$, 否则 $\partial F=\emptyset$). 这与 $E$ 连通矛盾. 故 $F$ 连通. $\blacksquare$

### 习题十三

设 $f:\left[0,1\right]\to\mathbb R$ 是一个连续函数并且 $f\left(0\right)=f\left(1\right)$.

(1) (10 分) 证明存在 $x\in\left[0,\frac12\right]$ 使得 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) (10 分) 证明对于任意的整数 $n\ge2$, 存在 $x\in\left[0,1-\frac1n\right]$ 使得 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) (5 分) 证明存在一个连续函数 $f:\left[0,1\right]\to\mathbb R$ 使得对于任意的 $x\in\left[0,\frac35\right]$ 都有 $f\left(x\right)\neq f\left(x+\frac25\right)$.

### 解答 习题十三

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
