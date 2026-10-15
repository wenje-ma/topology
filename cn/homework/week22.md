# 作业 22

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.15** (拓扑基)<br>$\mathcal B\subset\mathcal P\left(X\right)$ 满足 $X=\bigcup\mathcal B$ 且 $B_1\cap B_2$ 含某 $B_3$, 则以 $\mathcal B$ 中元素之并为开集生成最粗拓扑. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.2** (既开又闭集)<br>既开又闭; $X$ 连通当且仅当仅 $\emptyset,X$ 既开又闭. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸当且仅当 $x,y\in K$ 蕴含连线含于 $K$; 凸集必路径连通. (教材 $\S4$)

> **定义 4.11** (弗斯滕伯格拓扑)<br>$\mathbb Z$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb Z+b$ ($a\neq0$) 为基的拓扑; $S\left(a,b\right)$ 既开又闭. (题集 $\S2.2$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.6** (扇形连通)<br>一族两两有公共点的连通集之并连通. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像紧. (教材 $\S5$)

> **定义 5.2** (紧致空间)<br>$X$ 紧当且仅当每个开覆盖有有限子覆盖. (教材 $\S5$)

> **定义 5.3** (有限交性质)<br>闭集族 $\mathcal F$ 的任意有限子族交非空; $X$ 紧当且仅当任意有限交性质闭集族之交非空. (教材 $\S5$)

> **定理 5.9** (吉洪诺夫定理)<br>任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.10** (有限交判据)<br>$X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定义 6.2** (开球)<br>$B\left(x,r\right)=\left\{y:d\left(x,y\right)<r\right\}$; 开球全体是度量拓扑的基. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛. (教材 $\S6$)

> **定义 6.8** (完全有界)<br>对每个 $r>0$, $X$ 可被有限个半径 $r$ 的球覆盖. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **推论 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (题集 2025 年卷 B)

> **定义 6.23** (幂零映射)<br>连续线性映射 $f$, 每点被 $f$ 的某次复合映到 $0$. (题集 2025 年卷 B)

> **定义 11.16** (无向图与子图)<br>$G=\left(V,E\right)$, $E\subset V\times V$ 无序; 子图保持 $V$ 只删边. (题集 $\S3.3$)

> **定义 11.17** ($k$-染色与 $k$-可染色)<br>$f:V\to\left\{1,\dots,k\right\}$ 使相邻点异色; 存在则称 $k$-可染色. (题集 $\S3.3$)

### 习题一

(2024 年卷 C 题目一, 60 分). 本大题中各小题相互独立.

(1) (20 分) 写出贝尔纲定理的一个版本.

(2) (20 分) 证明空间 $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 是连通的. 证明空间 $H^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2-z^2=-1\right\}$ 不是连通的.

(3) (20 分) 设 $\left(X,d\right)$ 是一个完备度量空间. 证明如果 $F\subset X$ 是 $X$ 的闭子空间, 那么 $\left(F,d\right)$ 是完备的. 证明如果 $O\subset X$ 是 $X$ 的开子空间, 那么 $\left(O,d\right)$ 不一定是完备的.

(4) (附加题, 10 分) 设 $\left(X,d\right)$ 是完备度量空间, $O\subset X$ 开. 证明存在 $O$ 上由 $d$ 诱导的度量 $d'$ 使 $\left(O,d'\right)$ 完备. 提示: 考虑 $\phi\left(x\right)=\frac1{d\left(x,X-O\right)}$ 及嵌入 $x\mapsto\left(x,\phi\left(x\right)\right)$.

### 解答 习题一

(1) 贝尔纲定理即**定理 6.13** (贝尔纲定理): 完备度量空间中可数个稠密开集之交非空 (且稠密).

(2) 记上半球 $D^+=\left\{\left(x,y,z\right)\in S^2:z\ge0\right\}$ 与下半球 $D^-=\left\{z\le0\right\}$. 映射 $\left(u,v\right)\mapsto\left(u,v,\sqrt{1-u^2-v^2}\right)$ 把闭单位圆盘 $\left\{u^2+v^2\le1\right\}$ 映成 $D^+$, 是同胚; 闭单位圆盘由**定义 4.6** (凸集) 是凸集故连通, 由**定理 4.2** (连续像连通) $D^+$ 连通. 同理 $D^-$ 连通. 二者之交为赤道 $\left\{z=0\right\}\cap S^2$, 非空. 由**定理 4.6** (扇形连通), $S^2=D^+\cup D^-$ 连通.

   对 $H^2$, 由方程 $z^2=x^2+y^2+1$ 知 $z\neq0$. 令 $H^+=\left\{z>0\right\}\cap H^2$, $H^-=\left\{z<0\right\}\cap H^2$. 二者非空, 不交, 且都是 $H^2$ 在子空间拓扑下的开集 ($H^+=H^2\cap\left\{z>0\right\}$). 于是 $H^2$ 写成两个非空不相交开集之并, 由**定义 4.1** (连通空间) 它不连通.

(3) 设 $\left(x_n\right)$ 是 $F$ 中的柯西列. 因 $F$ 上度量即 $d$, 它也是 $X$ 中的柯西列; 由**定义 6.4** (完备度量空间) $X$ 完备, 故 $x_n\to x\in X$. 因 $F$ 闭 (由**定义 3.2** (闭集)), 序列极限 $x\in F$. 故 $F$ 中柯西列在 $F$ 中收敛, 由**定义 6.4** (完备度量空间) $F$ 完备.

   开子空间不必完备: 取 $X=\mathbb R$ (完备), $O=\left(0,1\right)$ 开. $x_n=\frac1n$ 由**定义 6.3** (柯西列) 是 $O$ 中柯西列, 但其极限 $0\notin O$, 故不收敛, $\left(O,d\right)$ 不完备.

(4) 由**定义 6.15** (点到集合的距离), $d\left(x,X-O\right)>0$ 对 $x\in O$ 成立. 令 $\phi\left(x\right)=\frac1{d\left(x,X-O\right)}$, 定义嵌入 $i:O\to X\times\mathbb R$, $i\left(x\right)=\left(x,\phi\left(x\right)\right)$. 证 $i\left(O\right)$ 在 $X\times\mathbb R$ 中闭: 取 $i\left(x_n\right)\to\left(y,t\right)$, 则 $x_n\to y$ 于 $X$. 若 $y\in O$, 则 $\phi$ 在 $O$ 上连续, $\phi\left(x_n\right)\to\phi\left(y\right)$, 故 $t=\phi\left(y\right)$, $\left(y,t\right)=i\left(y\right)$. 若 $y\notin O$, 则 $d\left(x_n,X-O\right)\to0$, $\phi\left(x_n\right)\to\infty$, 与有限 $t$ 矛盾. 故 $y\in O$, $i\left(O\right)$ 闭. $X\times\mathbb R$ 完备 (两完备空间之积), 由第 3 小题闭子空间 $i\left(O\right)$ 完备. 用 $i$ 把度量拉回 $O$: $d'\left(x,y\right)=d_{X\times\mathbb R}\left(i\left(x\right),i\left(y\right)\right)$, 则 $\left(O,d'\right)$ 与完备空间 $i\left(O\right)$ 等距, 故完备. $\blacksquare$

### 习题二

(2024 年卷 C 题目二, 40 分). 考虑一个度量空间 $X$, 使得其中任意无穷子集都有一个极限点.

(1) (10 分) 证明对于任意的 $\delta>0$, $X$ 能被有限个半径为 $\delta$ 的小球覆盖.

(2) (10 分) 证明 $X$ 是可分度量空间, 即 $X$ 中有一个可数稠密子集.

(3) (10 分) 证明 $X$ 有一个可数的基, 即存在可数个 $X$ 中的开集 $V_\alpha$, 使得任意 $X$ 的开集都是一些 $V_\alpha$ 之并.

(4) (10 分) 证明 $X$ 是一个紧致空间, 即任意 $X$ 的开覆盖都有一个有限子覆盖.

(5) (附加题, 10 分) 证明一个紧致度量空间 $K$ 一定是可分的.

### 解答 习题二

(1) 固定 $\delta>0$. 依次选 $x_1,x_2,\dots$ 使 $d\left(x_i,x_j\right)\ge\delta$ ($i\neq j$). 若此过程无穷, $\left\{x_i\right\}$ 是无穷集, 由题设有极限点 $x$. 由**定义 6.2** (开球), $B\left(x,\frac\delta2\right)$ 含两个不同的 $x_i,x_j$, 则 $d\left(x_i,x_j\right)<\delta$, 矛盾. 故过程有限停止, 得 $x_1,\dots,x_m$, 且 $\bigcup_{i=1}^m B\left(x_i,\delta\right)=X$ (否则可再选一点), 即有限 $\delta$-覆盖. 由**定义 6.8** (完全有界), $X$ 完全有界.

(2) 对每个 $n$, 由第 1 小题取半径 $1/n$ 的有限覆盖球心集 $C_n$. 令 $C=\bigcup_{n\ge1}C_n$, 可数. 任取 $x$ 与 $r>0$, 取 $n$ 使 $1/n<r$, 存在 $c\in C_n$ 使 $d\left(x,c\right)<1/n<r$, 即 $c\in B\left(x,r\right)$. 故 $C$ 稠密, 由**定义 3.9** (可分) $X$ 可分.

(3) 令 $\mathcal B=\left\{B\left(c,q\right):c\in C,\ q\in\mathbb Q_{>0}\right\}$. 它可数 ($C$ 可数, $\mathbb Q_{>0}$ 可数). 由**定义 3.15** (拓扑基) 验证: 任取开集 $U$ 与 $x\in U$, 存在 $r>0$ 使 $B\left(x,r\right)\subset U$ (由**定义 6.2** (开球) 度量拓扑). 由 $C$ 稠密取 $c\in C$ 使 $d\left(x,c\right)<r/3$, 再取有理数 $q$ 使 $d\left(x,c\right)<q<r/3$. 则 $x\in B\left(c,q\right)$ 且 $B\left(c,q\right)\subset B\left(x,r\right)\subset U$. 故 $U$ 是 $\mathcal B$ 中元素之并, $\mathcal B$ 是可数基.

(4) 设 $\left\{U_\alpha\right\}$ 是任意开覆盖. 由第 3 小题的可数基, 可选可数子族 $\left\{G_n\right\}$ 仍覆盖 $X$. 反证无有限子覆盖: 取 $x_n\notin G_1\cup\dots\cup G_n$. 集合 $\left\{x_n\right\}$ 无穷, 由题设有极限点 $x$. 则 $x\in G_N$ 对某个 $N$. 但 $G_N$ 是开集, 作为极限点它含无穷多个 $x_n$; 而对 $n\ge N$, $x_n\notin G_1\cup\dots\cup G_n\supset G_N$, 故 $G_N$ 至多含 $x_1,\dots,x_{N-1}$ 有限个, 矛盾. 故存在有限子覆盖, 由**定义 5.2** (紧致空间) $X$ 紧.

(5) 设 $K$ 紧. 对每个 $n$, 由**定义 5.2** (紧致空间), 开覆盖 $\left\{B\left(x,1/n\right):x\in K\right\}$ 有有限子覆盖, 取其球心集 $C_n$. 令 $C=\bigcup_n C_n$, 可数. 任取 $x\in K$ 与 $r>0$, 取 $n$ 使 $1/n<r$, 有限覆盖给出 $c\in C_n$ 使 $d\left(x,c\right)<1/n<r$, 故 $C$ 稠密. 由**定义 3.9** (可分), $K$ 可分. $\blacksquare$

### 习题三

(2025 年卷 A 题目一, 50 分). 考虑整数组成的空间 $\mathbb Z$. 我们在这个空间上定义一个拓扑, 称为弗斯滕伯格拓扑. 这个拓扑的一组基是所有非平凡的双边无穷长等差数列 $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$, 其中要求 $a\neq0$.

(0) 证明上面给出的集合 $S\left(a,b\right)$ 的确能构成某个拓扑的基. 证明 $\mathbb Z$ 的一个子集是开集当且仅当它是空集、$\mathbb Z$、或者是一些上述集合 $S\left(a,b\right)$ 的并.

(1) 证明 $\mathbb Z$ 的子集 $U$ 是开集当且仅当对于任意 $U$ 中的元素 $x$, 都存在 $a\neq0$ 使得 $S\left(a,x\right)\subset U$.

(2) 证明任何一个非平凡的集合 $S\left(a,b\right)$ ($a\neq0$) 都是既开又闭的.

(3) 证明 $\mathbb Z$ 的非空有限子集不可能是开集.

(4) 证明如果 $P$ 是所有 $\mathbb Z$ 中质数组成的集合, 那么 $\mathbb Z\setminus\left\{-1,1\right\}=\bigcup_{p\in P}S\left(p,0\right)$.

(5) 证明 $\mathbb Z$ 中的质数有无穷多个.

### 解答 习题三

(0) 由**定义 3.15** (拓扑基) 验证: $\mathbb Z=\bigcup_a S\left(a,0\right)$ (例如 $S\left(1,0\right)=\mathbb Z$). 两等差数列之交 $S\left(a,b\right)\cap S\left(c,d\right)$ 或者为空, 或者仍是一个等差数列 (公差为 $a,c$ 的最小公倍数), 从而含某 $S\left(e,f\right)$. 故 $\left\{S\left(a,b\right)\right\}$ 满足基条件, 由**定义 4.11** (弗斯滕伯格拓扑) 生成弗斯滕伯格拓扑, 开集恰为这些 $S\left(a,b\right)$ 之并.

(1) 若 $U$ 开, 由第 0 小题 $U$ 是若干 $S\left(a,b\right)$ 之并, 故每个 $x\in U$ 含于某 $S\left(a,b\right)\subset U$, 而该等差数列以 $x$ 为一项即 $S\left(a,x\right)\subset U$. 反之, 若每个 $x\in U$ 都含某 $S\left(a,x\right)\subset U$, 则 $U=\bigcup_{x\in U}S\left(a_x,x\right)$ 是基元素之并, 故开.

(2) 由第 0 小题 $S\left(a,b\right)$ 是基元素, 故开. 再证闭: 任取 $x\notin S\left(a,b\right)$, 即 $x\not\equiv b\pmod a$. 则 $S\left(a,x\right)=\left\{an+x\right\}$ 与 $S\left(a,b\right)=\left\{am+b\right\}$ 不交 (否则 $x-b=a\left(m-n\right)$, 矛盾). 故 $S\left(a,x\right)\subset\mathbb Z\setminus S\left(a,b\right)$, 由第 1 小题补集开. 由**定义 4.2** (既开又闭集), $S\left(a,b\right)$ 既开又闭.

(3) 设 $F$ 非空有限, 取 $x\in F$. 任何 $S\left(a,x\right)$ ($a\neq0$) 都是无穷集, 不可能含于 $F$. 由第 1 小题, $F$ 不满足开集条件, 故不是开集.

(4) 若 $x\in\mathbb Z\setminus\left\{-1,1\right\}$, 则 $\left|x\right|>1$, $x$ 有质因子 $p$, 即 $x=pn\in S\left(p,0\right)$. 反之 $S\left(p,0\right)=\left\{pn\right\}$ 对 $p\ge2$ 不含 $\pm1$, 故 $S\left(p,0\right)\subset\mathbb Z\setminus\left\{-1,1\right\}$. 两边相等.

(5) 反设质数有限: $P=\left\{p_1,\dots,p_r\right\}$. 由第 4 小题, $\mathbb Z\setminus\left\{-1,1\right\}=\bigcup_{i=1}^r S\left(p_i,0\right)$. 由第 2 小题每个 $S\left(p_i,0\right)$ 既开又闭, 有限个既开又闭集之并既开又闭. 故补集 $\left\{-1,1\right\}$ 既开又闭, 特别它是开集, 与第 3 小题 (非空有限集不能开) 矛盾. 故质数无穷多. $\blacksquare$

### 习题四

(2025 年卷 A 题目二, 50 分). 研究角谷-马尔可夫不动点定理的一个简单版本. 设 $E$ 为一个有限维 $\mathbb R$ 线性空间. 设 $K$ 为 $E$ 的一个非空紧凸集合. 设 $u:E\to E$ 是一个线性映射使得 $u\left(K\right)\subset K$. 对 $n\ge1$ 定义 $u_n=\frac1n\left(\operatorname{Id}_E+u+u^2+\cdots+u^{n-1}\right)$, 其中 $\operatorname{Id}_E$ 是 $E$ 上的恒同映射.

(0) 证明 $u$ 是连续的.

(1) 证明对于任意 $n\ge1$, $u_n\left(K\right)$ 是 $K$ 中的一个紧致凸集合.

(2) 证明 $u_4\left(K\right)\subset u_2\left(K\right)$.

(3) 证明对于任意 $n\ge2$, $u_{n!}\left(K\right)\subset u_{\left(n-1\right)!}\left(K\right)$.

(4) 证明 $\bigcap_{n\ge1}u_{n!}\left(K\right)$ 是一个非空紧致凸集, 并且 $\bigcap_{n\ge1}u_{n!}\left(K\right)=\bigcap_{n\ge1}u_n\left(K\right)$.

(5) 证明 $\bigcap_{n\ge1}u_n\left(K\right)$ 就是 $u$ 的所有不动点的集合.

### 解答 习题四

(0) 有限维线性空间之间的线性映射关于欧氏范数连续, 故 $u$ 连续. 同理每个 $u_n$ 是线性映射, 连续.

(1) $u_n$ 线性连续. 由**定理 5.1** (紧空间连续像紧), $u_n\left(K\right)$ 紧. 又线性映射把凸集映成凸集: 由**定义 4.6** (凸集), $K$ 凸, $u_n\left(K\right)$ 凸. 且 $u_n\left(K\right)\subset K$, 故 $u_n\left(K\right)$ 是 $K$ 中紧致凸集.

(2) 对 $x\in K$,

$$
u_4\left(x\right)=\frac14\left(x+ux+u^2x+u^3x\right)=\frac12\left(u_2\left(x\right)+u_2\left(ux\right)\right).
$$

因 $u\left(K\right)\subset K$, $ux\in K$, 故 $u_2\left(x\right),u_2\left(ux\right)\in u_2\left(K\right)$. 由**定义 4.6** (凸集), 凸组合 $\in u_2\left(K\right)$. 故 $u_4\left(K\right)\subset u_2\left(K\right)$.

(3) $n!=n\cdot\left(n-1\right)!$. 把 $u_{n!}$ 的平均分成 $n$ 个长度为 $\left(n-1\right)!$ 的块:

$$
u_{n!}\left(x\right)=\frac1n\sum_{j=0}^{n-1}u^{j\left(n-1\right)!}\,u_{\left(n-1\right)!}\left(x\right).
$$

每个 $u_{\left(n-1\right)!}\left(x\right)\in u_{\left(n-1\right)!}\left(K\right)\subset K$, 且 $u^{j\left(n-1\right)!}$ 把 $K$ 映入 $K$, 故上式各项都在 $u_{\left(n-1\right)!}\left(K\right)$ 中, 其凸组合由**定义 4.6** (凸集) 仍在其中. 故 $u_{n!}\left(K\right)\subset u_{\left(n-1\right)!}\left(K\right)$.

(4) 集列 $u_{n!}\left(K\right)$ 递降, 每个紧 (由第 1 小题) 故闭, 且具有限交性质 (由**定义 5.3** (有限交性质), 递降非空闭集族任意有限交非空). $K$ 紧, 由**定理 5.10** (有限交判据), 全族交 $\bigcap_{n\ge1}u_{n!}\left(K\right)$ 非空. 凸集之交凸, 紧集之交闭, 故它是非空紧致凸集. 由第 3 小题及递推可知阶乘子列与全列等价, $\bigcap_n u_{n!}\left(K\right)=\bigcap_n u_n\left(K\right)$.

(5) 先设 $z$ 是 $u$ 的不动点, 即 $uz=z$, $z\in K$. 则 $u_n\left(z\right)=z$, 故 $z\in u_n\left(K\right)$ 对一切 $n$, 即 $z\in\bigcap_n u_n\left(K\right)$.

   再设 $z\in\bigcap_n u_n\left(K\right)$. 则对每个 $n$ 存在 $x_n\in K$ 使 $z=u_n\left(x_n\right)$. 于是

$$
u\left(z\right)-z=\frac1n\left(u^n\left(x_n\right)-x_n\right).
$$

因 $K$ 紧故有界, $\left\|u^n x_n\right\|,\left\|x_n\right\|$ 有界, 右端范数 $O\left(1/n\right)\to0$. 故 $u\left(z\right)-z=0$, 即 $uz=z$. 两者相等. $\blacksquare$

### 习题五

(2025 年卷 B 题目一, 50 分). 考虑一个无向图 $G$, 记 $V$ 为顶点集, $E$ 为边集. 称图 $G=\left(V,E\right)$ 的子图 $\widetilde G=\left(\widetilde V,\widetilde E\right)$ 满足 $\widetilde V=V$ 且 $\widetilde E\subset E$. 一个图 $G$ 的 $k$-染色 ($k\ge2$) 指函数 $f:V\to\left\{1,\dots,k\right\}$ 使对任意边 $\left(x,y\right)\in E$ 都有 $f\left(x\right)\neq f\left(y\right)$. 称图是 $k$-可染色的若这种函数存在.

(0) 考虑 $\left\{1,\dots,k\right\}$ 上的离散拓扑. 证明在这个拓扑下 $\left\{1,\dots,k\right\}$ 是紧致的.

(1) 给定图 $G$. 记 $X$ 为所有从 $V$ 到 $\left\{1,\dots,k\right\}$ 的函数所成集合. 证明 $X=\left\{1,\dots,k\right\}^{\left|V\right|}$, 并且若 $\left\{1,\dots,k\right\}$ 赋予离散拓扑, 则 $X$ 在乘积拓扑下是紧致的. 对边集 $F\subset E$, 记 $X_F=\left\{f:V\to\left\{1,\dots,k\right\}:f\text{ 是子图 }\left(V,F\right)\text{ 的 }k\text{-染色}\right\}$.

(2) 证明如果 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 那么 $X_F$ 是闭的.

(3) 证明对于任意的 $F\subset E$, $X_F$ 都是闭的.

(4) 设图 $G$ 的所有有限子图都是 $k$-可染色的. 考虑 $\mathcal F=\left\{X_F:F\subset E\text{ 有限}\right\}$. 证明 $\mathcal F$ 中有限个元素之交非空, 然后证明 $\mathcal F$ 中所有元素之交也非空.

(5) 证明德布鲁因-埃尔德什定理: 如果图 $G$ 的任意有限子图都是 $k$-可染色的, 那么 $G$ 也是 $k$-可染色的.

### 解答 习题五

(0) $\left\{1,\dots,k\right\}$ 是有限集. 任意开覆盖中, 每个点选一个覆盖元, 仅需 $k$ 个即可覆盖, 故由**定义 5.2** (紧致空间) 它紧.

(1) $X=\prod_{v\in V}\left\{1,\dots,k\right\}=\left\{1,\dots,k\right\}^{\left|V\right|}$. 由第 0 小题每个因子 $\left\{1,\dots,k\right\}$ 紧, 由**定理 5.9** (吉洪诺夫定理), 乘积 $X$ 在乘积拓扑下紧.

(2) 单条边时, $X_{\left\{\left(x,y\right)\right\}}=\left\{f:f\left(x\right)\neq f\left(y\right)\right\}$. 其补集为

$$
X\setminus X_F=\bigcup_{c=1}^k\left\{f:f\left(x\right)=c,\ f\left(y\right)=c\right\}.
$$

每个集合是两个连续取值映射 ($f\mapsto f\left(x\right)$) 的纤维之交, 在离散拓扑下既开又闭, 故为闭集; 有限并闭. 因此补集闭, 由**定义 3.2** (闭集), $X_F$ 闭.

(3) $X_F=\bigcap_{\left(x,y\right)\in F}X_{\left\{\left(x,y\right)\right\}}$. 由第 2 小题每个 $X_{\left\{\left(x,y\right)\right\}}$ 闭, 闭集任意交仍闭 (由**定义 3.2** (闭集) 对应拓扑公理), 故 $X_F$ 闭.

(4) 任取有限个 $F_1,\dots,F_m$, 则 $\bigcap_{i=1}^m X_{F_i}=X_{F_1\cup\dots\cup F_m}$. 因 $\bigcup_i F_i$ 有限, 由**定义 11.16** (无向图与子图) 子图 $\left(V,\bigcup_i F_i\right)$ 是有限子图, 由题设它 $k$-可染色, 故 $X_{\cup F_i}$ 非空. 故 $\mathcal F$ 具有限交性质 (由**定义 5.3** (有限交性质)). 又 $\mathcal F$ 中元素都是紧空间 $X$ 中的闭集, 由**定理 5.10** (有限交判据), 全族交 $\bigcap_{F\text{ 有限}}X_F$ 非空.

(5) 取 $f\in\bigcap_{F\text{ 有限}}X_F$. 由**定义 11.17** ($k$-染色与 $k$-可染色), $f$ 是子图 $\left(V,F\right)$ 的 $k$-染色对每个有限 $F$ 成立. 特别对任意边 $e\in E$, 取有限集 $F=\left\{e\right\}$, 则 $f\left(x\right)\neq f\left(y\right)$ 对该边成立. 故 $f$ 是整图 $G$ 的 $k$-染色, $G$ 可 $k$-染色. $\blacksquare$

### 习题六

(2025 年卷 B 题目二, 50 分). 一个巴拿赫空间是完备的赋范线性空间. 考虑一个巴拿赫空间 $X$ 和一个连续线性映射 $f:X\to X$. 假设对于任意的 $x\in X$, 都存在 $n\in\mathbb N$ 使 $f^n\left(x\right)=0$, 其中 $f^n$ 是 $n$ 次复合.

(1) 考虑 $F_n=\left\{x\in X:f^n\left(x\right)=0\right\}$. 证明对于任意 $n\in\mathbb N$, $F_n$ 都是 $X$ 的一个闭子集.

(2) 证明存在某个 $N\in\mathbb N$, 使得 $F_N$ 有内点.

(3) 证明上一问中的 $F_N$ 一定是 $X$.

(4) 证明 $f$ 是一个幂零映射.

(5) 考虑多项式空间 $\mathbb R\left[X\right]$ 中的线性映射 $f:P\mapsto P'$, 其中 $P'$ 是多项式 $P$ 的导数. 讨论这个例子与上面结果的关系.

### 解答 习题六

(1) $f^n$ 是连续线性映射的复合, 故连续. $F_n=\left(f^n\right)^{-1}\left(\left\{0\right\}\right)$. 在巴拿赫空间 $X$ (由**定义 6.21** (巴拿赫空间), 它是豪斯多夫的) 中单点集 $\left\{0\right\}$ 闭, 由**定义 3.2** (闭集), 其原像 $F_n$ 闭.

(2) 由题设每个 $x$ 被某次复合映到 $0$, 故 $X=\bigcup_{n\ge1}F_n$. 又 $F_n\subset F_{n+1}$ (若 $f^n x=0$ 则 $f^{n+1}x=f^n\left(fx\right)=0$), 闭集族递增. $X$ 由**定义 6.21** (巴拿赫空间) 完备. 由**推论 6.14** (递增闭集族) (即**定理 6.13** (贝尔纲定理) 的推论), 存在 $N$ 使 $F_N$ 有非空内部.

(3) 设 $B\left(x_0,r\right)\subset F_N$, 即 $f^N\left(x_0\right)=0$ 且 $f^N$ 在该球上取 $0$. 任取 $y\in X$, 取充分小 $t>0$ 使 $t y$ 范数小于 $r$, 则 $x_0+t y\in B\left(x_0,r\right)\subset F_N$. 由线性 $f^N\left(x_0+t y\right)=f^N\left(x_0\right)+t f^N\left(y\right)=0$, 而 $f^N\left(x_0\right)=0$, 故 $t f^N\left(y\right)=0$, 即 $f^N\left(y\right)=0$. 由 $y$ 任意, $F_N=X$.

(4) 由第 3 小题存在统一的 $N$ 使对一切 $x\in X$, $f^N\left(x\right)=0$. 由**定义 6.23** (幂零映射), $f$ 是幂零映射.

(5) 对 $P\in\mathbb R\left[X\right]$, $f\left(P\right)=P'$. 若 $\deg P=d$, 则 $f^{d+1}\left(P\right)=0$, 故题设的"每点被某次复合映到 $0$"成立. 但 $\mathbb R\left[X\right]$ (装备任一通常范数) 不完备, 且不存在统一的 $N$ 使 $f^N=0$ (次数无界). 这正说明第 2、3 步用到的完备性 (**推论 6.14** (递增闭集族)) 是本质的: 在非完备空间上, 逐点幂零不必推出一致幂零. $\blacksquare$
