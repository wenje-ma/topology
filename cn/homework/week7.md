# 作业 7

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in V}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 4.18** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4** (闭子集紧)<br>若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **定理 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定理 5.9** (吉洪诺夫定理)<br>任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.10** (有限交判据)<br>$X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定理 5.11** (紧空间上连续函数取最大值)<br>紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 5.16** (紧致空间)<br>称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1** (紧 $=$ 序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **教材 §6** (度量空间是豪斯多夫的)<br>度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定理 6.18** (蒂茨-乌雷松扩张定理)<br>度量空间闭子集 $A$ 上的连续有界函数可保持上确界与下确界地扩张到全空间. (题集 $\S7.1$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.37** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.49** (等距映射)<br>满足 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)$ 的映射 $f$. (题集 $\S3.4$)

> **定义 11.16** (无向图与子图)<br>$G=\left(V,E\right)$, $E\subset V\times V$ 无序; 子图保持 $V$ 只删边. (题集 $\S3.3$)

> **定义 11.17** ($k$-染色与 $k$-可染色)<br>$f:V\to\left\{1,\dots,k\right\}$ 使相邻点异色; 存在则称 $k$-可染色. (题集 $\S3.3$)

### 习题一

若 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 证明 $X_F$ 闭. （$X_F$ 见文首记号）

### 解答 习题一

一条边 $\left(x,y\right)$ 的染色条件即 $f\left(x\right)\neq f\left(y\right)$. 故

$$
X_F=\bigcup_{i\neq j}\left\{f:f\left(x\right)=i,\ f\left(y\right)=j\right\}.
$$

每个柱集 $C_{ij}=\left\{f:f\left(x\right)=i,\ f\left(y\right)=j\right\}$ 是坐标投影 $\pi_x:X\to\left\{1,\dots,k\right\}$ 与 $\pi_y$ 的纤维之交. 由**定义 3.11** (乘积拓扑), 坐标投影连续; 离散空间 $\left\{1,\dots,k\right\}$ 中单点 $\left\{i\right\}$ 闭, 由**定义 3.22** (连续映射) 其原像 $\pi_x^{-1}\left(\left\{i\right\}\right)$ 闭. 故 $C_{ij}$ 闭. 而 $X_F$ 是有限个 $C_{ij}$ ($i\neq j$) 之并, 闭集的有限并仍闭. 故 $X_F$ 闭. $\blacksquare$

### 习题二

证明: 对任意 $F\subset E$, $X_F$ 闭.

### 解答 习题二

一个映射是 $\left(V,F\right)$ 的染色, 当且仅当它对每条边 $e\in F$ 都合法. 故

$$
X_F=\bigcap_{e\in F}X_{\left\{e\right\}}.
$$

由习题一, 每个 $X_{\left\{e\right\}}$ 闭; 由**定义 3.21** (闭集), 闭集的任意交仍闭 (补集为开集的任意并). 故 $X_F$ 闭. $\blacksquare$

### 习题三

现设图 $G$ 的任意有限子图都可 $k$-染色. 证明 $\mathcal F$ 中任意有限个集合之交非空. （$\mathcal F$ 见文首记号）

### 解答 习题三

设 $F_1,\dots,F_n\subset E$ 有限. 由染色条件逐条叠加,

$$
\bigcap_{i=1}^{n}X_{F_i}=X_{\bigcup_{i=1}^{n}F_i}.
$$

边集 $\bigcup_{i=1}^{n}F_i$ 有限, 由假设对应的子图可 $k$-染色, 即由**定义 11.17** ($k$-染色与 $k$-可染色), $X_{\bigcup_iF_i}\neq\emptyset$. 故有限交非空. $\blacksquare$

### 习题四

用 $X$ 的紧致性证明: $\mathcal F$ 中所有集合之交非空.

### 解答 习题四

由文首记号, $X=\prod_{v\in V}\left\{1,\dots,k\right\}$; 每个因子 $\left\{1,\dots,k\right\}$ 为有限离散空间故紧 (任意开覆盖每点选一覆盖元即有限子覆盖, 由**定义 5.16** (紧致空间)), 由**定理 5.9** (吉洪诺夫定理), $X$ 在乘积拓扑下紧. 由习题二, 每个 $X_F$ 是紧空间 $X$ 中的闭集. 由习题三, $\mathcal F=\left\{X_F:F\subset E\text{ 有限}\right\}$ 具有限交性质 (由**定义 5.17** (有限交性质)). 由**定理 5.10** (有限交判据),

$$
\bigcap_{F\subset E\text{ 有限}}X_F\neq\emptyset.
$$

$\blacksquare$

### 习题五

证明德布鲁因-埃尔德什定理: 若图 $G$ 的任意有限子图都可 $k$-染色, 则 $G$ 可 $k$-染色. 即使 $G$ 有不可数个顶点也成立.

### 解答 习题五

由习题四, 可取

$$
f\in\bigcap_{F\subset E\text{ 有限}}X_F.
$$

对任意边 $e=\left(x,y\right)\in E$, 取 $F=\left\{e\right\}$; 因 $f\in X_{\left\{e\right\}}$, 由**定义 11.17** ($k$-染色与 $k$-可染色), $f\left(x\right)\neq f\left(y\right)$. 故 $f$ 是全图 $G=\left(V,E\right)$ 的合法 $k$-染色. $\blacksquare$

### 习题六

设 $X$ 是紧度量空间, $\left\{u_n\right\}_{n\ge0}$ 是 $X$ 中序列且 $d\left(u_n,u_{n+1}\right)\to0$. 证明 $\left\{u_n\right\}$ 的聚点集紧致, 并且连通.

### 解答 习题六

令

$$
L=\bigcap_{N\ge1}\overline{\left\{u_n:n\ge N\right\}}.
$$

$L$ 正是序列 $\left\{u_n\right\}$ 的聚点集. 每个闭包是闭集, 故 $L$ 是紧空间 $X$ 的闭子集, 由**定理 5.4** (闭子集紧), $L$ 紧致.

下证 $L$ 连通. 反证, 设 $L=C\cup D$, $C,D$ 为 $L$ 中非空不相交闭集. 因 $L$ 紧, $C,D$ 紧; 函数 $C\times D\to\mathbb R$, $\left(c,d\right)\mapsto d\left(c,d\right)$ 连续且 $C\times D$ 紧, 由**定理 5.11** (紧空间上连续函数取最大值) (及最小值情形) 其最小值 $\delta=d\left(C,D\right)$ 可达; 又 $C\cap D=\emptyset$, 故 $\delta>0$. 由 $d\left(u_n,u_{n+1}\right)\to0$, 存在 $N$ 使 $n\ge N$ 时 $d\left(u_n,u_{n+1}\right)<\delta/3$. 因 $C,D\subset L$, 对任意 $c\in C$ 与 $d\in D$, 由 $L=\cap_N\overline{\left\{u_n:n\ge N\right\}}$ 的定义, $c$ 的每个邻域与 $\left\{u_n:n\ge N\right\}$ 相交, 故存在任意大的 $n,m\ge N$ 使 $d\left(u_n,C\right)<\delta/6$, $d\left(u_m,D\right)<\delta/6$. 沿链 $u_n,u_{n+1},\dots,u_m$, 函数 $h\left(t\right)=d\left(u_t,C\right)$ 从 $<\delta/6$ 变到 $\ge\delta-\delta/6=5\delta/6$ (后一步用三角不等式: $d\left(u_m,C\right)\ge d\left(C,D\right)-d\left(u_m,D\right)>\delta-\delta/6$), 且每步变化 $<\delta/3$, 故存在 $p$ 使

$$
\delta/6\le h\left(p\right)\le\delta/2.
$$

对任意大的这样的 $n,m$ 重复选取 $p$, 并由 $X$ 紧致经**定理 6.1** (紧 $=$ 序列紧) 提取收敛子列, 其极限 $z$ 满足 $d\left(z,C\right)\ge\delta/6$ 且 $d\left(z,D\right)\ge\delta/2$, 故 $z$ 是聚点但 $z\notin C\cup D=L$, 矛盾. 由**定义 4.18** (连通空间), $L$ 连通. $\blacksquare$

### 习题七

设 $\left(X,d\right)$ 是度量空间, $f:X\to X$ 是**定义 6.49** (等距映射). 证明: 若 $X$ 紧致, 则 $f$ 双射且是同胚.

### 解答 习题七

$f$ 单: 由**定义 6.49** (等距映射), $f\left(x\right)=f\left(y\right)$ 蕴含 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)=0$, 故 $x=y$.

证 $f$ 满. 反证, 取 $a\notin f\left(X\right)$. $f$ 连续 (等距蕴含利普希茨连续), $f\left(X\right)$ 是紧空间 $X$ 的连续像, 由**定理 5.1** (紧空间连续像紧), $f\left(X\right)$ 紧致. 度量空间是**教材 §6** (度量空间是豪斯多夫的), 由**定理 5.5** (豪斯多夫中紧集闭), $f\left(X\right)$ 闭. 故 $\varepsilon=d\left(a,f\left(X\right)\right)>0$. 对 $n\neq m$, 由**定义 6.49** (等距映射) 及 $f$ 的迭代仍是等距,

$$
d\left(f^n\left(a\right),f^m\left(a\right)\right)=d\left(a,f^{\left|n-m\right|}\left(a\right)\right)\ge\varepsilon.
$$

但 $\left\{f^n\left(a\right)\right\}$ 是紧空间 $X$ 中的序列, 由**定理 6.1** (紧 $=$ 序列紧) 有收敛子列, 它必是**定义 6.37** (柯西列), 与两两距离 $\ge\varepsilon$ 矛盾. 故 $f$ 满.

$f$ 连续 (等距蕴含利普希茨连续), $X$ 紧致故为紧豪斯多夫空间, 由**定理 5.6** (紧豪斯多夫间的连续双射), $f$ 是同胚. $\blacksquare$

### 习题八

(紧集的膨胀) 设 $X$ 是某赋范线性空间的紧子空间. 设 $f:X\to X$ 满足对一切 $x,y\in X$, $\left|f\left(y\right)-f\left(x\right)\right|\ge\left|y-x\right|$. 证明 $f$ 是**定义 6.49** (等距映射) 且双射. 再证明满的 $1$-利普希茨函数 $g:X\to X$ 是等距.

### 解答 习题八

固定 $a,b\in X$, 记 $c_n=\left|f^n\left(a\right)-f^n\left(b\right)\right|$. 由膨胀条件应用于 $\left(f^{n-1}\left(a\right),f^{n-1}\left(b\right)\right)$, $c_{n+1}\ge c_n$, 又 $c_n\le\operatorname{diam}\left(X\right)$, 故 $c_n\uparrow L$. 由**定理 6.1** (紧 $=$ 序列紧), $X\times X$ 紧, $\left(f^n\left(a\right),f^n\left(b\right)\right)$ 有子列 $\left(f^{n_j}\left(a\right),f^{n_j}\left(b\right)\right)\to\left(u,v\right)$, 于是 $\left|u-v\right|=L$. 因 $c_{n_j}\to L$ 且 $c_{n_j+1}\to L$, 由三角不等式,

$$
\left|c_{n_j+1}-c_{n_j}\right|\le\left|f^{n_j+1}\left(a\right)-f^{n_j}\left(a\right)\right|+\left|f^{n_j+1}\left(b\right)-f^{n_j}\left(b\right)\right|.
$$

左端趋于 $0$, 故两项都趋于 $0$. 由 $f$ 连续 (膨胀条件蕴含利普希茨), $f\left(f^{n_j}\left(a\right)\right)=f^{n_j+1}\left(a\right)\to f\left(u\right)$; 而它也 $\to u$, 故 $f\left(u\right)=u$. 同理 $f\left(v\right)=v$. 由膨胀条件应用于 $\left(a,u\right)$: $\left|f^{n_j}\left(a\right)-f^{n_j}\left(u\right)\right|\ge\left|a-u\right|$, 即 $\left|f^{n_j}\left(a\right)-u\right|\ge\left|a-u\right|$. 令 $j\to\infty$ 得 $0\ge\left|a-u\right|$, 故 $u=a$. 同理 $v=b$. 于是 $L=\left|u-v\right|=\left|a-b\right|=c_0$, 而 $c_n$ 从 $c_0$ 起不减且收敛到 $c_0$, 故 $c_1=c_0$, 即 $\left|f\left(a\right)-f\left(b\right)\right|=\left|a-b\right|$. 由**定义 6.49** (等距映射), $f$ 是等距.

再由**定理 5.1** (紧空间连续像紧) 及习题七的论证, $f$ 双射.

现设 $g:X\to X$ 满且 $\left|g\left(y\right)-g\left(x\right)\right|\le\left|y-x\right|$. 对任意 $u,v\in X$, 取原像 $x,y$ 使 $g\left(x\right)=u$, $g\left(y\right)=v$, 则 $\left|u-v\right|\le\left|x-y\right|$, 即 $g^{-1}$ 满足膨胀条件. 由上一段, $g^{-1}$ 是等距, 故 $g$ 也是等距. $\blacksquare$

### 习题九

(紧空间不动点定理) 设 $K$ 是某赋范线性空间的紧子空间. 设 $f:K\to K$ 严格压缩, 即 $x\neq y$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\left|y-x\right|$. 证明 $f$ 在 $K$ 中有唯一不动点, 且对一切 $a\in K$, $f^n\left(a\right)$ 收敛到该不动点.

### 解答 习题九

严格压缩条件蕴含 $f$ 连续 ($\left|f\left(y\right)-f\left(x\right)\right|<\left|y-x\right|$ 即利普希茨常数 $<1$). 令 $g\left(x\right)=\left|f\left(x\right)-x\right|\ge0$; 由**定义 3.22** (连续映射) 与**定理 3.1** (复合连续), $g$ 连续. 由**定理 5.11** (紧空间上连续函数取最大值) (及其最小值情形), $g$ 在紧集 $K$ 上取到最小值, 设为 $g\left(x_0\right)$. 若 $g\left(x_0\right)>0$, 则由严格压缩,

$$
\left|f^2\left(x_0\right)-f\left(x_0\right)\right|<\left|f\left(x_0\right)-x_0\right|=g\left(x_0\right),
$$

即 $g\left(f\left(x_0\right)\right)<g\left(x_0\right)$, 矛盾. 故 $g\left(x_0\right)=0$, $x_0$ 是不动点. 唯一性: 若另有不动点 $y$, 则 $0<\left|y-x_0\right|=\left|f\left(y\right)-f\left(x_0\right)\right|<\left|y-x_0\right|$, 矛盾. 对 $a\in K$, $\left|f^{n+1}\left(a\right)-x_0\right|<\left|f^n\left(a\right)-x_0\right|$ 单调下降, 由 $K$ 紧 (**定理 6.1** (紧 $=$ 序列紧)) 收敛到 $x_0$. $\blacksquare$

### 习题十

(两个子列极限) 设 $K$ 是某**定义 6.20** (赋范线性空间) 的紧子空间.

(1) 证明 $K$ 中序列收敛当且仅当它只有唯一子列极限;

(2) 设 $f:K\to K$ 连续, $x\in K$, 序列 $f^n\left(x\right)$ 恰有两个子列极限 $z_0,z_1$. 证明: 对 $z_0,z_1$ 的任意邻域 $V_0,V_1$, 序列最终落入 $V_0\cup V_1$; 并证明 $f\left(z_0\right)=z_1$, $f\left(z_1\right)=z_0$, 且 $f^{2k}\left(x\right)$ 与 $f^{2k+1}\left(x\right)$ 分别收敛到 $z_0,z_1$.

### 解答 习题十

(1) ($\Rightarrow$) 显然. ($\Leftarrow$) 设唯一子列极限为 $L$. 若序列不收敛到 $L$, 则存在 $\varepsilon>0$ 与子列恒在 $B\left(L,\varepsilon\right)$ 外; 由**定理 6.1** (紧 $=$ 序列紧), 该子列有收敛子列, 其极限异于 $L$, 矛盾. 故序列收敛到 $L$.

(2) 若序列不最终落入 $V_0\cup V_1$, 则有子列恒在 $V_0\cup V_1$ 外; 由紧性它有收敛子列, 其极限不在 $V_0\cup V_1$ 中, 即第三个子列极限, 矛盾.

$f$ 连续, 把子列极限映为序列 $f^{n+1}\left(x\right)$ 的子列极限, 而后者的子列极限集同为 $\left\{z_0,z_1\right\}$. 故 $f\left(z_0\right),f\left(z_1\right)\in\left\{z_0,z_1\right\}$. 若 $f\left(z_0\right)=z_0$, 则偶子列将只有一个子列极限, 与 (1) 矛盾; 故 $f\left(z_0\right)=z_1$, 同理 $f\left(z_1\right)=z_0$. 于是 $f^{2k}\left(x\right)$ 恰在 $z_0$ 附近累积, $f^{2k+1}\left(x\right)$ 恰在 $z_1$ 附近累积, 由 (1) 分别收敛到 $z_0,z_1$. $\blacksquare$

### 习题十一

设 $E$ 是紧度量空间, $f:E\to E$ 连续, 且对一切 $x,y\in E$ 满足 $d\left(f\left(x\right),f\left(y\right)\right)\ge d\left(x,y\right)$.

(1) 证明 $f$ 实际上是**定义 6.49** (等距映射), 即 $d\left(f\left(x\right),f\left(y\right)\right)=d\left(x,y\right)$;

(2) 证明 $f$ 是双射. 可考虑 $\left(x_n,y_n\right)=\left(f^n\left(x\right),f^n\left(y\right)\right)$ 的子列;

(3) 最后证明: 若 $g:E\to E$ 是连续双射且 $d\left(g\left(x\right),g\left(y\right)\right)\le d\left(x,y\right)$ 对一切 $x,y$ 成立, 则 $g$ 也是**定义 6.49** (等距映射).

### 解答 习题十一

(1) 固定 $x,y\in E$, 记 $a_n=d\left(f^n\left(x\right),f^n\left(y\right)\right)$. 由条件应用于 $\left(f^{n-1}\left(x\right),f^{n-1}\left(y\right)\right)$, $a_{n+1}\ge a_n$, 又 $a_n\le\operatorname{diam}\left(E\right)$, 故 $a_n\uparrow L$. 由**定理 6.1** (紧 $=$ 序列紧), $E\times E$ 紧, $\left(f^n\left(x\right),f^n\left(y\right)\right)$ 有子列 $\left(f^{n_j}\left(x\right),f^{n_j}\left(y\right)\right)\to\left(u,v\right)$, 于是 $d\left(u,v\right)=L$. 因 $a_{n_j}\to L$ 且 $a_{n_j+1}\to L$, 由三角不等式

$$
\left|a_{n_j+1}-a_{n_j}\right|\le d\bigl(f^{n_j+1}\left(x\right),f^{n_j}\left(x\right)\bigr)+d\bigl(f^{n_j+1}\left(y\right),f^{n_j}\left(y\right)\bigr).
$$

左端趋于 $0$, 故 $d\left(f^{n_j+1}\left(x\right),f^{n_j}\left(x\right)\right)\to0$ 且 $d\left(f^{n_j+1}\left(y\right),f^{n_j}\left(y\right)\right)\to0$. 由 $f$ 连续, $f\left(f^{n_j}\left(x\right)\right)=f^{n_j+1}\left(x\right)\to f\left(u\right)$; 而它也 $\to u$, 故 $f\left(u\right)=u$. 同理 $f\left(v\right)=v$.

由条件应用于 $\left(x,u\right)$: $d\left(f^{n_j}\left(x\right),f^{n_j}\left(u\right)\right)\ge d\left(x,u\right)$, 即 $d\left(f^{n_j}\left(x\right),u\right)\ge d\left(x,u\right)$. 令 $j\to\infty$ 得 $0\ge d\left(x,u\right)$, 故 $u=x$. 同理 $v=y$. 于是 $L=d\left(u,v\right)=d\left(x,y\right)=a_0$, 而 $a_n$ 从 $a_0$ 起不减且收敛到 $a_0$, 故 $a_1=a_0$, 即 $d\left(f\left(x\right),f\left(y\right)\right)=d\left(x,y\right)$. 由**定义 6.49** (等距映射), $f$ 是等距.

(2) 反设 $f$ 不满, 取 $p\notin f\left(E\right)$. 由**定理 5.1** (紧空间连续像紧), $f\left(E\right)$ 紧; 度量空间是**教材 §6** (度量空间是豪斯多夫的), 由**定理 5.5** (豪斯多夫中紧集闭), $f\left(E\right)$ 闭. 由**定义 6.46** (点到集合的距离), $\delta=d\left(p,f\left(E\right)\right)>0$. 轨道 $p,f\left(p\right),f^2\left(p\right),\dots$ 满足

$$
d\left(f^{n+1}\left(p\right),f^n\left(p\right)\right)\ge d\left(f^n\left(p\right),f^{n-1}\left(p\right)\right)\ge\cdots\ge d\left(f\left(p\right),p\right)\ge\delta,
$$

其中最后一步用 $f\left(p\right)\in f\left(E\right)$ 而 $p\notin f\left(E\right)$. 但由**定理 6.1** (紧 $=$ 序列紧), 紧度量空间 $E$ 中序列 $\left(f^n\left(p\right)\right)$ 有收敛子列, 而收敛子列必是**定义 6.37** (柯西列), 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. 结合第 1 小题的等距性, $d\left(f\left(x\right),f\left(y\right)\right)=0$ 推出 $d\left(x,y\right)=0$ 即 $x=y$, $f$ 单射. 故 $f$ 双射.

(3) $E$ 紧且是**教材 §6** (度量空间是豪斯多夫的), $g$ 是紧豪斯多夫空间之间的连续双射, 由**定理 5.6** (紧豪斯多夫间的连续双射), $g^{-1}$ 连续. 条件 $d\left(g\left(x\right),g\left(y\right)\right)\le d\left(x,y\right)$ 改写为: 对任意 $u,v\in E$, 令 $u=g\left(x\right)$, $v=g\left(y\right)$, 则 $d\left(g^{-1}\left(u\right),g^{-1}\left(v\right)\right)\ge d\left(u,v\right)$. 即 $g^{-1}$ 是紧度量空间上连续且距离不减的映射. 由第 1 小题, $g^{-1}$ 是**定义 6.49** (等距映射), 从而 $g$ 也是等距. $\blacksquare$

### 习题十二

等距与紧性. 设 $K\subset\mathbb R^n$ 是非空紧集, $\varepsilon>0$. 称 $A\subset K$ 是 $\varepsilon$-分离的, 若 $x\neq y$ 蕴含 $\left|x-y\right|>\varepsilon$. 证明存在有限数 $M\left(\varepsilon\right)$, 使 $K$ 中任何 $\varepsilon$-分离集的基数不超过 $M\left(\varepsilon\right)$. 再证明: 若 $f:K\to K$ 是**定义 6.49** (等距映射), 则 $f$ 满.

### 解答 习题十二

反设存在任意大的 $\varepsilon$-分离集. 则可取两两不同的点列 $x_m\in K$ 使 $m\neq m'$ 时 $\left|x_m-x_{m'}\right|>\varepsilon$. 由**定理 5.3** ($\mathbb R^n$ 中的紧集) 与**定理 6.1** (紧 $=$ 序列紧), $\left(x_m\right)$ 有收敛子列; 收敛子列是**定义 6.37** (柯西列), 充分靠后两项距离 $<\varepsilon$, 与 $\varepsilon$-分离矛盾. 故存在 $M\left(\varepsilon\right)$.

满性: 反设 $f$ 不满, 取 $p\notin f\left(K\right)$. $f\left(K\right)$ 紧, 由**定理 5.3** ($\mathbb R^n$ 中的紧集) 闭, 故 $\delta=d\left(p,f\left(K\right)\right)>0$. 轨道 $p,f\left(p\right),f^2\left(p\right),\dots$ 满足

$$
\left|f^{n+1}\left(p\right)-f^n\left(p\right)\right|=\left|f\left(f^n\left(p\right)\right)-f\left(f^{n-1}\left(p\right)\right)\right|=\left|f^n\left(p\right)-f^{n-1}\left(p\right)\right|\ge\cdots\ge\left|f\left(p\right)-p\right|\ge\delta,
$$

其中等号用了**定义 6.49** (等距映射). 但由**定理 6.1** (紧 $=$ 序列紧), $K$ 中轨道有收敛子列, 必为**定义 6.37** (柯西列), 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. $\blacksquare$

### 习题十三

(7.1 紧性)

(1) 设 $\left(E,d\right)$ 是度量空间, $f:E\to\mathbb R$ 连续, $K\subset E$ 紧. 假设 $f$ 在 $K$ 上单射, 且对每个 $x\in K$ 存在 $\varepsilon>0$ 使 $f$ 在 $B\left(x,\varepsilon\right)$ 上单射. 证明存在含 $K$ 的开集 $\Omega$ 使 $f$ 在 $\Omega$ 上单射.

(2) (里茨定理) 设 $E$ 是实无穷维赋范线性空间. 证明 $E$ 的闭单位球不能被有限个半径 $1$ 的开球覆盖.

(3) (蒂茨-乌雷松扩张定理) 设 $\left(E,d\right)$ 是度量空间, $A\subset E$ 闭, $f:A\to\mathbb R$ 连续有界. 证明存在连续 $g:E\to\mathbb R$, $g\big|_A=f$, 且

$$
\sup_{x\in E}g\left(x\right)=\sup_{x\in A}f\left(x\right),\quad
\inf_{x\in E}g\left(x\right)=\inf_{x\in A}f\left(x\right).
$$

### 解答 习题十三

**第 1 小题**: 对 $n\ge 1$, 定义 $K_n=\left\{x\in E:d\left(x,K\right)<1/n\right\}$. 每个 $K_n$ 是开集且含 $K$. 反证: 若对每个 $n$, $f$ 在 $K_n$ 上不单射, 则存在 $x_n,y_n\in K_n$, $x_n\neq y_n$, 使 $f\left(x_n\right)=f\left(y_n\right)$. 由 $x_n,y_n\in K_n$, 可取 $x'_n,y'_n\in K$ 使 $d\left(x_n,x'_n\right)<1/n$, $d\left(y_n,y'_n\right)<1/n$. 由**定义 5.16** (紧致空间), $K\times K$ 紧; 由**定理 6.1** (紧 $=$ 序列紧), 存在子列 $\left(x'_{\varphi\left(n\right)},y'_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in K\times K$. 由三角不等式, $x_{\varphi\left(n\right)}\to x$, $y_{\varphi\left(n\right)}\to y$. 由 $f$ 连续, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$ 取极限得 $f\left(x\right)=f\left(y\right)$. 因 $f$ 在 $K$ 上单射, $x=y$. 但由假设, $x$ 有邻域 $B\left(x,\varepsilon\right)$ 使 $f$ 单射, 而 $x_{\varphi\left(n\right)}\neq y_{\varphi\left(n\right)}$ 且当 $n$ 充分大时二者都在 $B\left(x,\varepsilon\right)$ 内, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$, 矛盾. 故存在 $n$ 使 $f$ 在 $K_n$ 上单射, 取 $\Omega=K_n$ 即可.

**第 2 小题**: 反证. 设闭单位球 $\overline B\left(0,1\right)$ 被开单位球 $B\left(x_i,1\right)$ ($i=1,\dots,m$) 覆盖. 令 $F=\operatorname{span}\left(x_1,\dots,x_m\right)$, 它是有限维子空间. 因 $E$ 无穷维, 存在 $y\in E\setminus F$. 由有限维子空间闭, 取 $x\in F$ 使 $\left\|y-x\right\|=d\left(y,F\right)$ (有限维中距离可达). 令

$$
x_0=\frac{y-x}{\left\|y-x\right\|}.
$$

则 $\left\|x_0\right\|=1$. 对任意 $z\in F$,

$$
\left\|x_0-z\right\|=\frac{\left\|y-\left(x+\left\|y-x\right\|z\right)\right\|}{\left\|y-x\right\|}\ge\frac{d\left(y,F\right)}{\left\|y-x\right\|}=1.
$$

故 $d\left(x_0,F\right)\ge 1$. 但每个 $x_i\in F$, 故 $\left\|x_0-x_i\right\|\ge 1$, 即 $x_0\notin B\left(x_i,1\right)$ 对一切 $i$ 成立. 而 $x_0\in\overline B\left(0,1\right)$, 与覆盖矛盾. 这就是**定理 6.17** (里茨定理).

**第 3 小题**: 由**定义 6.46** (点到集合的距离), 对 $x\notin A$ 定义

$$
g\left(x\right)=\frac{1}{d\left(x,A\right)}\inf_{y\in A}\left(f\left(y\right)d\left(x,y\right)\right),
$$

对 $x\in A$ 令 $g\left(x\right)=f\left(x\right)$. 由平移缩放 (不妨设 $\inf_A f=1$, $\sup_A f=2$), 可验证 $g$ 连续: $x\in\operatorname{int}A$ 时 $g=f$ 连续; $x\notin A$ 时由三角不等式 $d\left(x,A\right)$ 连续且正, $g$ 连续; $x\in\partial A$ 时由 $f$ 在 $A$ 上连续, 对 $\varepsilon>0$ 取 $r>0$ 使 $y\in B\left(x,r\right)\cap A$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\varepsilon$, 再对 $z\notin A$ 且 $\left\|z-x\right\|<r/4$ 用三角不等式估计得 $\left|g\left(z\right)-f\left(x\right)\right|<\varepsilon$. 由**定义 3.22** (连续映射), $g$ 在全 $E$ 上连续. 由构造 $\inf_E g=\inf_A f$, $\sup_E g=\sup_A f$. 这就是**定理 6.18** (蒂茨-乌雷松扩张定理). $\blacksquare$

### 习题十四

(2025 年卷 B 题目一, 50 分). 考虑一个无向图 $G$, 记 $V$ 为顶点集, $E$ 为边集. 称图 $G=\left(V,E\right)$ 的子图 $\widetilde G=\left(\widetilde V,\widetilde E\right)$ 满足 $\widetilde V=V$ 且 $\widetilde E\subset E$. 一个图 $G$ 的 $k$-染色 ($k\ge2$) 指函数 $f:V\to\left\{1,\dots,k\right\}$ 使对任意边 $\left(x,y\right)\in E$ 都有 $f\left(x\right)\neq f\left(y\right)$. 称图是 $k$-可染色的若这种函数存在.

(0) 考虑 $\left\{1,\dots,k\right\}$ 上的离散拓扑. 证明在这个拓扑下 $\left\{1,\dots,k\right\}$ 是紧致的.

(1) 给定图 $G$. 记 $X$ 为所有从 $V$ 到 $\left\{1,\dots,k\right\}$ 的函数所成集合. 证明 $X=\left\{1,\dots,k\right\}^{\left|V\right|}$, 并且若 $\left\{1,\dots,k\right\}$ 赋予离散拓扑, 则 $X$ 在乘积拓扑下是紧致的. 对边集 $F\subset E$, 记 $X_F=\left\{f:V\to\left\{1,\dots,k\right\}:f\text{ 是子图 }\left(V,F\right)\text{ 的 }k\text{-染色}\right\}$.

(2) 证明如果 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 那么 $X_F$ 是闭的.

(3) 证明对于任意的 $F\subset E$, $X_F$ 都是闭的.

(4) 设图 $G$ 的所有有限子图都是 $k$-可染色的. 考虑 $\mathcal F=\left\{X_F:F\subset E\text{ 有限}\right\}$. 证明 $\mathcal F$ 中有限个元素之交非空, 然后证明 $\mathcal F$ 中所有元素之交也非空.

(5) 证明德布鲁因-埃尔德什定理: 如果图 $G$ 的任意有限子图都是 $k$-可染色的, 那么 $G$ 也是 $k$-可染色的.

### 解答 习题十四

(0) $\left\{1,\dots,k\right\}$ 是有限集. 任意开覆盖中, 每个点选一个覆盖元, 仅需 $k$ 个即可覆盖, 故由**定义 5.16** (紧致空间) 它紧.

(1) $X=\prod_{v\in V}\left\{1,\dots,k\right\}=\left\{1,\dots,k\right\}^{\left|V\right|}$. 由第 0 小题每个因子 $\left\{1,\dots,k\right\}$ 紧, 由**定理 5.9** (吉洪诺夫定理), 乘积 $X$ 在乘积拓扑下紧.

(2) 单条边时, $X_{\left\{\left(x,y\right)\right\}}=\left\{f:f\left(x\right)\neq f\left(y\right)\right\}$. 其补集为

$$
X\setminus X_F=\bigcup_{c=1}^k\left\{f:f\left(x\right)=c,\ f\left(y\right)=c\right\}.
$$

每个集合是两个连续取值映射 ($f\mapsto f\left(x\right)$) 的纤维之交, 在离散拓扑下既开又闭, 故为闭集; 有限并闭. 因此补集闭, 由**定义 3.21** (闭集), $X_F$ 闭.

(3) $X_F=\bigcap_{\left(x,y\right)\in F}X_{\left\{\left(x,y\right)\right\}}$. 由第 2 小题每个 $X_{\left\{\left(x,y\right)\right\}}$ 闭, 闭集任意交仍闭 (由**定义 3.21** (闭集) 对应拓扑公理), 故 $X_F$ 闭.

(4) 任取有限个 $F_1,\dots,F_m$, 则 $\bigcap_{i=1}^m X_{F_i}=X_{F_1\cup\dots\cup F_m}$. 因 $\bigcup_i F_i$ 有限, 由**定义 11.16** (无向图与子图) 子图 $\left(V,\bigcup_i F_i\right)$ 是有限子图, 由题设它 $k$-可染色, 故 $X_{\cup F_i}$ 非空. 故 $\mathcal F$ 具有限交性质 (由**定义 5.17** (有限交性质)). 又 $\mathcal F$ 中元素都是紧空间 $X$ 中的闭集, 由**定理 5.10** (有限交判据), 全族交 $\bigcap_{F\text{ 有限}}X_F$ 非空.

(5) 取 $f\in\bigcap_{F\text{ 有限}}X_F$. 由**定义 11.17** ($k$-染色与 $k$-可染色), $f$ 是子图 $\left(V,F\right)$ 的 $k$-染色对每个有限 $F$ 成立. 特别对任意边 $e\in E$, 取有限集 $F=\left\{e\right\}$, 则 $f\left(x\right)\neq f\left(y\right)$ 对该边成立. 故 $f$ 是整图 $G$ 的 $k$-染色, $G$ 可 $k$-染色. $\blacksquare$
