# 作业 4

> **定理 2.8** (施罗德-伯恩斯坦定理)<br>若同时存在 $X\to Y$ 与 $Y\to X$ 的单射, 则 $X$ 与 $Y$ 基数相等. (教材 $\S2$)

> **定理 2.13** (实数与自然数幂集等势)<br>$\left|\mathbb R\right|=\left|\mathcal P\left(\mathbb N\right)\right|$. (教材 $\S2$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.4** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.19** (子空间拓扑)<br>$T_A=\left\{U\cap A:U\in T_X\right\}$; 它是使含映射 $\iota:A\to X$ 连续的意义下的最粗拓扑. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.2** (既开又闭集)<br>既开又闭的集合称为既开又闭集; $X$ 连通当且仅当仅 $\emptyset,X$ 既开又闭. (教材 $\S4$)

> **定义 4.3** (完全不连通)<br>空间的唯一连通子集是单点集. (教材 $\S4$)

> **定义 4.5** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $f:\left[a,b\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸当且仅当 $x,y\in K$ 蕴含连线含于 $K$; 凸集必路径连通. (教材 $\S4$)

> **定义 4.7** (拓扑学家正弦曲线)<br>$y=\sin\left(1/x\right)$ 在 $\left(0,1\right]$ 上的图像与 $y$ 轴上 $\left[-1,1\right]$ 的并; 它连通但不路径连通. (教材 $\S4$)

> **定义 4.8** (连通分支)<br>含点 $x$ 的唯一极大连通集 $A\left(x\right)$; 它是闭集; 分支数有限时分支开. (教材 $\S4$)

> **定义 4.10** (局部路径连通)<br>每点有由路径连通邻域组成的邻域基; 局部路径连通且连通蕴含路径连通. (题集 $\S2.1$)

> **定理 4.1** (区间连通)<br>$\left[0,1\right]$ 连通; 故一切区间连通. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通且 $f$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.3** (路径连通蕴含连通)<br>路径连通空间必连通. (教材 $\S4$)

> **定理 4.5** (可数度量空间完全不连通)<br>每个可数度量空间都是完全不连通的. (教材 $\S4$)

> **定理 4.15** (闭包保持连通性)<br>连通集的闭包仍连通. (教材 $\S4$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性与三角不等式. (教材 $\S6$)

### 习题一

证明 $\mathbb R$ 与 $\mathbb R^2$ 基数相同, 但不同胚. 提示: 可考察 $\mathbb R^2-\left\{0\right\}$ 的像.

### 解答 习题一

先证基数相同. 由**定理 2.13** (实数与自然数幂集等势), $\mathbb R$ 与 $\mathcal P\left(\mathbb N\right)$ 等势. 映射 $\mathbb R^2\to\mathbb R$ 如下构造: 由**定理 2.13** (实数与自然数幂集等势), 把一对实数对应到一对子集 $\left(A,B\right)\subset\mathcal P\left(\mathbb N\right)^2$, 再作

$$
\left(A,B\right)\longmapsto\left\{2n:n\in A\right\}\cup\left\{2n+1:n\in B\right\}\subset\mathbb N.
$$

该映射是单射 (偶数位编码 $A$, 奇数位编码 $B$), 故 $\mathbb R^2\to\mathcal P\left(\mathbb N\right)\cong\mathbb R$ 有单射. 反过来 $x\mapsto\left(x,0\right)$ 给出 $\mathbb R\to\mathbb R^2$ 的单射. 由**定理 2.8** (施罗德-伯恩斯坦定理), $\mathbb R$ 与 $\mathbb R^2$ 基数相等.

再证不同胚. 反设存在同胚 $h:\mathbb R\to\mathbb R^2$. 由**定义 3.4** (同胚), $h$ 限制到 $\mathbb R-\left\{0\right\}$ 上, 配以**定义 3.19** (子空间拓扑), 仍给出到 $\mathbb R^2-\left\{h\left(0\right)\right\}$ 的同胚. 考察两边挖去一点后的连通分支数.

在 $\mathbb R$ 一侧,

$$
\mathbb R-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right).
$$

由**定理 4.1** (区间连通), 两区间各自连通; 它们是不相交非空开集, 故由**定义 4.1** (连通空间) $\mathbb R-\left\{0\right\}$ 不连通, 由**定义 4.8** (连通分支) 它恰有两个连通分支.

在 $\mathbb R^2$ 一侧, $\mathbb R^2-\left\{0\right\}$ 路径连通: 任取两点 $u,v$, 选点 $w$ 使 $0,u,w$ 与 $0,w,v$ 均不共线, 折线 $u\to w\to v$ 避开原点. 由**定理 4.3** (路径连通蕴含连通), $\mathbb R^2-\left\{0\right\}$ 连通, 由**定义 4.8** (连通分支) 它只有一个连通分支.

同胚保持连通分支的个数 (连通集映为连通集, 极大性保持). 但上述同胚把有两个分支的 $\mathbb R-\left\{0\right\}$ 映到只有一个分支的 $\mathbb R^2-\left\{h\left(0\right)\right\}$, 矛盾. 故 $\mathbb R$ 与 $\mathbb R^2$ 不同胚. $\blacksquare$

### 习题二

证明不存在连续函数 $f:\mathbb R\to\mathbb R$ 满足 $f\left(P\right)\subset\mathbb Q$ 且 $f\left(\mathbb Q\right)\subset P$, 其中 $P$ 为素数全体. 提示: 可考察 $f\left(\mathbb R\right)$.

### 解答 习题二

$\mathbb R$ 是**定义 4.6** (凸集) 意义下的凸集, 故路径连通, 由**定理 4.3** (路径连通蕴含连通) $\mathbb R$ 连通. 由**定理 4.2** (连续像连通), $f\left(\mathbb R\right)$ 是 $\mathbb R$ 中的连通子集.

$\mathbb Q$ 在 $\mathbb R$ 中稠密 (**定义 3.8** (稠密)). 由 $f$ 连续, $f\left(\mathbb Q\right)$ 在 $f\left(\mathbb R\right)$ 中稠密: 对任意 $y=f\left(x\right)\in f\left(\mathbb R\right)$, 取有理数列 $q_n\to x$, 则 $f\left(q_n\right)\to f\left(x\right)=y$.

由题设 $f\left(\mathbb Q\right)\subset P$. 素数集 $P$ 在 $\mathbb R$ 中是闭集 (每个素数孤立, 无聚点), 故由**定义 3.6** (闭包),

$$
f\left(\mathbb R\right)\subset\overline{f\left(\mathbb Q\right)}\subset\overline{P}=P.
$$

于是连通集 $f\left(\mathbb R\right)$ 含于 $P$. 素数集 $P$ 作为子空间是离散的 (每点孤立), 而离散空间的任一子集既开又闭, 由**定义 4.1** (连通空间) 离散空间的连通子集只能是单点集. 故 $f\left(\mathbb R\right)=\left\{p_0\right\}$, 即 $f$ 必为常值映射. 因此满足条件的连续函数只能是常值映射, 不存在非常值的这类连续函数. $\blacksquare$

### 习题三

证明连通且局部路径连通的空间必路径连通. 提示: 可考察某点的"路径连通"分支.

### 解答 习题三

设 $X$ 连通且局部路径连通, 固定 $x\in X$, 令

$$
C=\left\{y\in X:y\text{ 与 }x\text{ 之间有连续路径相连}\right\}.
$$

先证 $C$ 开. 任取 $y\in C$. 由**定义 4.10** (局部路径连通), $y$ 有路径连通邻域 $V$. 对任意 $z\in V$, $z$ 与 $y$ 在 $V$ 中有路径, $y$ 与 $x$ 有路径, 两段拼接即得 $z$ 与 $x$ 的路径, 故 $z\in C$, 从而 $V\subset C$. 由 $y$ 任意, $C$ 开.

再证 $C$ 闭. 取 $y\in\overline C$ (**定义 3.6** (闭包)). 由**定义 4.10** (局部路径连通), $y$ 有路径连通邻域 $V$. 由 $\overline C$ 的定义, $V\cap C\neq\emptyset$, 取 $z\in V\cap C$. $z$ 与 $x$ 有路径, $y$ 与 $z$ 在 $V$ 中有路径, 拼接得 $y$ 与 $x$ 的路径, 故 $y\in C$. 于是 $\overline C\subset C$, $C$ 闭.

故 $C$ 既开又闭 (**定义 4.2** (既开又闭集)). $X$ 连通 (**定义 4.1** (连通空间)), 且 $C\neq\emptyset$ ($x\in C$), 故由**定义 4.2** (既开又闭集) 得 $C=X$. 由**定义 4.5** (路径连通), $X$ 路径连通. $\blacksquare$

### 习题四

证明多于一点的连通度量空间不可数.

### 解答 习题四

反设 $\left(X,d\right)$ 是**定义 6.1** (度量空间) 意义下的连通度量空间, $\left|X\right|\ge2$, 且 $X$ 可数. 由**定理 4.5** (可数度量空间完全不连通), $X$ 是**定义 4.3** (完全不连通) 意义下的完全不连通空间, 即其唯一连通子集是单点集.

但 $X$ 本身作为子集由题设连通 (**定义 4.1** (连通空间)), 且 $\left|X\right|\ge2$, 与完全不连通矛盾. 故 $X$ 不可数. $\blacksquare$

### 习题五

证明一般线性群 $GL\left(n,\mathbb R\right)$ (即 $n\times n$ 实可逆矩阵之群) 由两个连通分支组成: 行列式为正者与行列式为负者; 特别地它不连通. 证明与之对照, $GL\left(n,\mathbb C\right)$ 连通.

### 解答 习题五

行列式映射 $\det:GL\left(n,\mathbb R\right)\to\mathbb R-\left\{0\right\}$ 是矩阵元素的多项式, 故由**定义 3.3** (连续映射) 它连续. 由**定理 4.2** (连续像连通), $GL\left(n,\mathbb R\right)$ 中连通子集的行列式必落入 $\mathbb R-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right)$ 的同一连通分支. 故

$$
GL\left(n,\mathbb R\right)=GL^{+}\sqcup GL^{-}
$$

其中 $GL^{+}=\left\{A:\det A>0\right\}$, $GL^{-}=\left\{A:\det A<0\right\}$, 二者不相交且各自为开集.

现证 $GL^{+}$ 路径连通. 对任意 $A\in GL^{+}$, 作格拉姆-施密特分解 $A=QR$, 其中 $Q\in SO\left(n\right)$, $R$ 为对角元全正的上三角阵. 全体这样的 $R$ 构成**定义 4.6** (凸集) 意义下的凸集, 故路径连通; $SO\left(n\right)$ 中任一正交阵可分解为平面旋转之积, 各旋转角连续收缩到 $0$ 即与单位阵相连. 拼接两条路径, $A$ 与单位阵在 $GL^{+}$ 中路径相连. 同理, 若 $A\in GL^{-}$, 取 $D=\operatorname{diag}\left(-1,1,\dots,1\right)$, 则 $AD\in GL^{+}$, $AD$ 与单位阵路径相连, 从而 $A$ 与 $D$ 路径相连. 故 $GL^{+}$ 与 $GL^{-}$ 各自路径连通, 由**定义 4.8** (连通分支) 它们正是 $GL\left(n,\mathbb R\right)$ 的两个连通分支; 由**定义 4.1** (连通空间) $GL\left(n,\mathbb R\right)$ 不连通.

对复的情形, 任意 $A\in GL\left(n,\mathbb C\right)$, 格拉姆-施密特分解 $A=QU$, 其中 $U$ 为酉阵. 酉阵可对角化, 特征值均在单位圆上, 各辐角连续收缩到 $0$ 即与单位阵相连, 故 $U$ 与单位阵路径相连, 从而 $A$ 与单位阵路径相连. 故 $GL\left(n,\mathbb C\right)$ 路径连通, 由**定理 4.3** (路径连通蕴含连通) 它连通. $\blacksquare$

### 习题六

证明拓扑学家正弦曲线连通但不路径连通.

### 解答 习题六

记

$$
G=\left\{\left(x,\sin\frac1x\right):0<x\le1\right\},\quad L=\left\{0\right\}\times\left[-1,1\right],\quad S=G\cup L.
$$

由**定义 4.7** (拓扑学家正弦曲线), $S$ 即拓扑学家正弦曲线.

先证连通. $G$ 以 $x$ 为参数路径连通, 故由**定理 4.3** (路径连通蕴含连通) $G$ 连通. 当 $x\to0^{+}$ 时 $\sin\left(1/x\right)$ 在 $\left[-1,1\right]$ 上稠密振荡, 故 $G$ 的闭包 $\overline G=G\cup L=S$ (**定义 3.6** (闭包)). 由**定理 4.15** (闭包保持连通性), $\overline G$ 连通, 故 $S$ 连通 (**定义 4.1** (连通空间)).

再证不路径连通. 反设存在路径 $\gamma:\left[0,1\right]\to S$ 以 $\left(0,0\right)\in L$ 为起点, 以 $\left(1,\sin1\right)\in G$ 为终点. 令 $t_0=\inf\left\{t:\gamma\left(t\right)\text{ 的横坐标}>0\right\}$. 由连续性 $\gamma\left(t_0\right)\in L$. 取 $t_n\downarrow t_0$, 则 $\gamma\left(t_n\right)=\left(x_n,\sin\left(1/x_n\right)\right)$, $x_n\to0^{+}$. 序列 $\sin\left(1/x_n\right)$ 既有收敛到 $1$ 的子列, 又有收敛到 $-1$ 的子列, 不可能收敛到 $\gamma\left(t_0\right)$ 的纵坐标, 与 $\gamma$ 连续矛盾. 故不存在这样的路径, $S$ 不路径连通, 即它不是**定义 4.5** (路径连通) 意义下的路径连通空间. $\blacksquare$
