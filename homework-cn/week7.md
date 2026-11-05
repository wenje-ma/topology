# week7

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定理 3.5 (闭包与极限点)**
> 
> $A$ 的闭包是 $A$ 与其全体极限点之并: $\overline{A}=A\cup{A}'$. (教材 $\S3$, 定理 3.5)

> **定理 3.6 (豪斯多夫的遗传性)**
> 
> 两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定义 3.9 (可分)**
> 
> 称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.11 (乘积拓扑)**
> 
> 设 $X,Y$ 为拓扑空间. $X\times{Y}$ 上的乘积拓扑以形如 $U\times{V}$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in{V}}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$, p17)

> **定义 3.15 (拓扑基)**
> 
> 设 $\mathcal{B}\subset\mathcal{P}\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $B_1,B_2\in\mathcal{B}$ 与任意 $x\in{B}_1\cap{B}_2$ 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_1\cap{B}_2$, 则以 $\mathcal{B}$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

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

> **定义 3.28 (扎里斯基拓扑)**
> 
> 设 $K$ 为域, $\mathbb{A}^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in{I}}$ 的公共零点集 $\left\{x\in\mathbb{A}^n\left(K\right):\forall{i}\in{I},\,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 3.33 ($T_1$ 空间)**
> 
> 单点集皆闭; 豪斯多夫空间必为 $T_1$ 空间. (教材 §3)

> **命题 3.33 (点态收敛判据)**
> 
> 设 $X=A^{S}$ 赋乘积拓扑. 则序列 $f_n\in{X}$ 收敛到 $g$, 当且仅当对一切 $s\in{S}$ 有 $f_n\left(s\right)\to{g}\left(s\right)$; 乘积拓扑在 $X=A^{S}$ 的情形又叫点态收敛拓扑. (教材 $\S3$, p22)

> **定理 4.1 (区间连通)**
> 
> $\left[0,1\right]$ 连通; 由此任意区间连通. (教材 §4, p23; 《拓扑学》(原书第2版) §24 推论 24.2)

> **定理 4.2 (连续像连通)**
> 
> $X$ 连通, $f:X\to{Y}$ 连续, 则 $f\left(X\right)$ 连通. (教材 §4, p23)

> **定理 4.3 (路径连通蕴含连通)**
> 
> 路径连通空间是连通的. (教材 §4, p24)

> **定义 4.9 (局部连通)**
> 
> 每点有由连通邻域组成的邻域基. (题集 §2.1)

> **定义 4.10 (局部路径连通)**
> 
> 每点有由路径连通邻域组成的邻域基. (题集 §2.1 Q3)

> **定义 4.11 (弗斯滕伯格拓扑)**
> 
> $\mathbb{Z}$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb{Z}+b=\left\{an+b:n\in\mathbb{Z}\right\}$ ($a\neq0$) 为基的拓扑; $S\left(a,b\right)$ 既开又闭. (题集 §2.2)

> **定义 4.12 (戈洛姆拓扑)**
> 
> $\mathbb{Z}_{>0}$ 上以 $\left\{an+b:n\in\mathbb{N}\right\}$ ($a,b$ 互素) 为基的拓扑. (题集 §2.2)

> **定义 4.13 (基尔希拓扑)**
> 
> $\mathbb{Z}_{>0}$ 上以 $\left\{pn+b:n\in\mathbb{N}\right\}$ ($p$ 为素数且 $p\nmid{b}$) 为基的拓扑. (题集 §2.2)

> **定理 4.16 (谢尔宾斯基同胚定理)**
> 
> 任意两个无孤立点的可数可度量化空间互相同胚. (题集 §2.2)

> **定义 4.17 (不动点)**
> 
> $f:X\to{X}$ 的不动点是满足 $f\left(x\right)=x$ 的点 $x\in{X}$. (题集 §7.2)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset{X}$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

> **定义 4.19 (既开又闭集)**
> 
> 既开又闭的集合称为既开又闭集; $X$ 连通当且仅当 $\emptyset$ 与 $X$ 是仅有的既开又闭集. (教材 §4, p23)

> **定义 4.20 (完全不连通)**
> 
> 空间的唯一连通子集是单点集. (教材 §4, p23)

> **定义 4.21 (局部常值函数)**
> 
> $f$ 局部常值: 每点有邻域使 $f$ 在其上取常值; 连通空间上局部常值的连续函数必常值. (教材 §4, p24)

> **定义 4.22 (路径连通)**
> 
> 任意 $x,y\in{X}$ 有连续路径 $\gamma:\left[0,1\right]\to{X}$ 以 $x,y$ 为端点. (教材 §4, p24)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $x,y\in{K}$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

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
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.7))

> **定理 5.7 (有限乘积紧)**
> 
> 有限个紧空间的乘积紧. (教材 $\S5$, 定理 5.7)

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

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

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

> **定义 6.42 (完全有界)**
> 
> 对每个 $r>0$, $X$ 可被有限个半径 $r$ 的球覆盖. (教材 $\S6$)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

> **说明 6.50 (度量空间是豪斯多夫的)**
> 
> 度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

> **说明 6.51 (度量连续与序列)**
> 
> 度量空间之间的映射 $f:X\to{Y}$ 连续, 当且仅当 $x_i\to{x}$ 蕴含 $f\left(x_i\right)\to{f}\left(x\right)$. (教材 $\S6$, p34)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; 《拓扑学》(原书第2版) $\S29$)

> **定义 7.5 (单点紧化)**
> 
> 亚历山德罗夫紧化 $\overline{X}=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset{X}$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

> **定义 7.7 (正则空间)**
> 
> 闭集 $A$ 与不在 $A$ 中的点有不相交开邻域. (教材 §7)

> **定义 11.1 (商拓扑)**
> 
> 满射 $\pi:X\to{Y}$ 下, $U\subset{Y}$ 开当且仅当 $\pi^{-1}\left(U\right)\subset{X}$ 开. (教材 §11, p61; 《拓扑学》(原书第2版) §22, p105; 《基础拓扑学》(修订版) 第4章 4.2, p55)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to{Y}$ 使 $U\subset{Y}$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to{Z}$ 连续当且仅当 $gf:X\to{Z}$ 连续. (教材 §11, p61; 《基础拓扑学》(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定义 11.6 (锥)**
> 
> 从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in{X}$, $0\le{t}<1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (教材 $\S11$, p63; 题集 $\S5$ Q9; 《基础拓扑学》(修订版) 第4章)

> **定义 11.12 (塌缩商)**
> 
> $X/\left\langle{A}\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 §5 Q11; 《基础拓扑学》(修订版) 第4章, p57)

> **定理 34.1 (乌雷松度量化定理)**
> 
> 每一个具有可数基的正则空间都是可度量化的. (《拓扑学》(原书第2版) §34 定理 34.1, p165; 教材 §7 定理 7.3, p43 表述为正规空间加可数基可度量化, 而正则加可数基蕴含正规)

## 7.1 (无界闭凸集含一条从原点出发的无穷射线)

考虑一个 $\mathbb{R}^2$ 中的闭集 $A$. 还假设 $A$ 是一个凸集, 原点 $O\in{A}$, 并且 $A$ 不是有界的.

(1) (10 分) 证明对于任意的正整数 $p\ge1$, 都存在一个点 $M_p\in{A}$, 线段 $OM_p$ 属于 $A$, 并且其长度 $\left|OM_p\right|\ge{p}$.

(2) (10 分) 记线段 $OM_p$ 与单位圆周的交点为 $u_p$. 证明存在一个 $\left\{u_p\right\}_{p\ge1}$ 的子列收敛到单位圆周上的某一点 $u$.

(3) (10 分) 证明 $A$ 包含一条从原点出发的长度无穷的半直线.

### 解答 4.13

(1) 因 $A$ 无界, 对每个 $p$, 存在 $M_p\in{A}$ 使 $\left|M_p\right|\ge{p}$ (否则 $A$ 含于半径 $p$ 的球内, 有界). 由**定义 4.23 (凸集)**, $O\in{A}$ 与 $M_p\in{A}$ 的连线线段 $OM_p$ 含于 $A$, 且其长度 $\left|OM_p\right|=\left|M_p\right|\ge{p}$.

(2) 令 $r_p=\left|M_p\right|$, $u_p=\frac{M_p}{r_p}$, 则 $u_p$ 在单位圆周 $S^1=\left\{v\in\mathbb{R}^2:\left|v\right|=1\right\}$ 上. $S^1$ 闭且有界, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** $S^1$ 紧. 由**定理 6.1 (紧 $=$ 序列紧)**, 序列 $\left(u_p\right)\subset{S}^1$ 有收敛子列 $u_{p_j}\to{u}\in{S}^1$.

(3) 固定 $\lambda\ge0$. 对充分大的 $j$, $r_{p_j}\ge\lambda$ (因 $r_{p_j}\ge{p}_j\to\infty$). 由**定义 4.23 (凸集)**, $\lambda{u}_{p_j}=\frac{\lambda}{r_{p_j}}M_{p_j}+\left(1-\frac{\lambda}{r_{p_j}}\right)O$ 是 $M_{p_j}$ 与 $O$ 的凸组合, 故 $\lambda{u}_{p_j}\in{A}$. 当 $j\to\infty$, $u_{p_j}\to{u}$, 故 $\lambda{u}_{p_j}\to\lambda{u}$. 因 $A$ 闭 (由**定义 3.21 (闭集)**, 闭集含其序列极限), $\lambda{u}\in{A}$. 由 $\lambda\ge0$ 任意, 半直线 $\left\{\lambda{u}:\lambda\ge0\right\}\subset{A}$, 即 $A$ 含一条从原点出发的无穷长半直线. $\blacksquare$

## 7.2 (2025 卷 A 题一：弗斯滕伯格拓扑的完整证明)

(2025 年卷 A 题目一, 50 分). 考虑整数组成的空间 $\mathbb{Z}$. 我们在这个空间上定义一个拓扑, 称为弗斯滕伯格拓扑. 这个拓扑的一组基是所有非平凡的双边无穷长等差数列 $S\left(a,b\right)=a\mathbb{Z}+b=\left\{an+b:n\in\mathbb{Z}\right\}$, 其中要求 $a\neq0$.

(0) 证明上面给出的集合 $S\left(a,b\right)$ 的确能构成某个拓扑的基. 证明 $\mathbb{Z}$ 的一个子集是开集当且仅当它是空集, $\mathbb{Z}$, 或者是一些上述集合 $S\left(a,b\right)$ 的并.

(1) 证明 $\mathbb{Z}$ 的子集 $U$ 是开集当且仅当对于任意 $U$ 中的元素 $x$, 都存在 $a\neq0$ 使得 $S\left(a,x\right)\subset{U}$.

(2) 证明任何一个非平凡的集合 $S\left(a,b\right)$ ($a\neq0$) 都是既开又闭的.

(3) 证明 $\mathbb{Z}$ 的非空有限子集不可能是开集.

(4) 证明如果 $P$ 是所有 $\mathbb{Z}$ 中质数组成的集合, 那么 $\mathbb{Z}\setminus\left\{-1,1\right\}=\bigcup_{p\in{P}}S\left(p,0\right)$.

(5) 证明 $\mathbb{Z}$ 中的质数有无穷多个.

### 解答 4.14

(0) 由**定义 3.15 (拓扑基)** 验证: $\mathbb{Z}=\bigcup_aS\left(a,0\right)$ (例如 $S\left(1,0\right)=\mathbb{Z}$). 两等差数列之交 $S\left(a,b\right)\cap{S}\left(c,d\right)$ 或者为空, 或者仍是一个等差数列 (公差为 $a,c$ 的最小公倍数), 从而含某 $S\left(e,f\right)$. 故 $\left\{S\left(a,b\right)\right\}$ 满足基条件, 由**定义 4.11 (弗斯滕伯格拓扑)** 生成弗斯滕伯格拓扑, 开集恰为这些 $S\left(a,b\right)$ 之并.

(1) 若 $U$ 开, 由第 (0) 小题 $U$ 是若干 $S\left(a,b\right)$ 之并, 故每个 $x\in{U}$ 含于某 $S\left(a,b\right)\subset{U}$, 而该等差数列以 $x$ 为一项即 $S\left(a,x\right)\subset{U}$. 反之, 若每个 $x\in{U}$ 都含某 $S\left(a,x\right)\subset{U}$, 则 $U=\bigcup_{x\in{U}}S\left(a_x,x\right)$ 是基元素之并, 故开.

(2) 由第 (0) 小题 $S\left(a,b\right)$ 是基元素, 故开. 再证闭: 任取 $x\notin{S}\left(a,b\right)$, 即 $x\not\equiv{b}\pmod{a}$. 则 $S\left(a,x\right)=\left\{an+x\right\}$ 与 $S\left(a,b\right)=\left\{am+b\right\}$ 不交 (否则 $x-b=a\left(m-n\right)$, 矛盾). 故 $S\left(a,x\right)\subset\mathbb{Z}\setminus{S}\left(a,b\right)$, 由第 (1) 小题补集开. 由**定义 4.19 (既开又闭集)**, $S\left(a,b\right)$ 既开又闭.

(3) 设 $F$ 非空有限, 取 $x\in{F}$. 任何 $S\left(a,x\right)$ ($a\neq0$) 都是无穷集, 不可能含于 $F$. 由第 (1) 小题, $F$ 不满足开集条件, 故不是开集.

(4) 若 $x\in\mathbb{Z}\setminus\left\{-1,1\right\}$, 则 $\left|x\right|>1$, $x$ 有质因子 $p$, 即 $x=pn\in{S}\left(p,0\right)$. 反之 $S\left(p,0\right)=\left\{pn\right\}$ 对 $p\ge2$ 不含 $\pm1$, 故 $S\left(p,0\right)\subset\mathbb{Z}\setminus\left\{-1,1\right\}$. 两边相等.

(5) 反设质数有限: $P=\left\{p_1,\dots,p_r\right\}$. 由第 (4) 小题, $\mathbb{Z}\setminus\left\{-1,1\right\}=\bigcup_{i=1}^rS\left(p_i,0\right)$. 由第 (2) 小题每个 $S\left(p_i,0\right)$ 既开又闭, 有限个既开又闭集之并既开又闭. 故补集 $\left\{-1,1\right\}$ 既开又闭, 特别它是开集, 与第 (3) 小题 (非空有限集不能开) 矛盾. 故质数无穷多. $\blacksquare$

## 7.3 ($\left\{0,1\right\}^{\left[0,1\right]}$ 在乘积拓扑下不序列紧)

证明 $\left\{0,1\right\}^{\left[0,1\right]}$ 赋通常乘积拓扑不是序列紧致的.

### 解答 5.1

把 $\left\{0,1\right\}^{\left[0,1\right]}$ 中的点视为函数 $f:\left[0,1\right]\to\left\{0,1\right\}$. 由**定义 3.11 (乘积拓扑)** 与**命题 3.33 (点态收敛判据)**, 在乘积拓扑下 $f_n\to{f}$ 当且仅当每个坐标 $t\in\left[0,1\right]$ 都有 $f_n\left(t\right)\to{f}\left(t\right)$; 该判据对任意因子空间 $A^{S}$ 成立, 因为乘积拓扑的基与因子空间无关.

对每个 $n\ge1$, 定义 $f_n\left(t\right)$ 为 $t$ 的二进制展开中小数点后第 $n$ 位数字 (二进有理点固定取其一展开). 任取严格递增的正整数列 $n_1<{}n_2<\dots$, 我们证明 $\left\{f_{n_k}\right\}$ 不收敛. 取 $t^{*}\in\left[0,1\right]$, 使其二进制展开在第 $n_{2k-1}$ 位为 $0$, 在第 $n_{2k}$ 位为 $1$, 其余位任意 (例如取 $0$). 则坐标 $t^{*}$ 处 $f_{n_k}\left(t^{*}\right)$ 依次为 $0,1,0,1,\dots$, 在离散空间 $\left\{0,1\right\}$ 中不收敛: 由**定义 3.25 (邻域与极限)**, $\left\{0\right\}$ 是 $0$ 的邻域而不含无穷多个 $f_{n_k}\left(t^{*}\right)$. 由**命题 3.33 (点态收敛判据)**, $\left\{f_{n_k}\right\}$ 在乘积拓扑下不收敛. 因每个子列都有同样形式, 由**定义 6.40 (序列紧致)**, $\left\{0,1\right\}^{\left[0,1\right]}$ 不是序列紧致的. $\blacksquare$

## 7.4 (紧致等价于具有限交性质的闭集族交非空)

称集合族 $\mathcal{F}$ 具有有限交性质, 若其任意有限子族之交非空. 证明: 空间 $X$ 紧致等价于, $X$ 中任意具有限交性质的闭集族 $\mathcal{F}$ 都满足 $\bigcap_{F\in\mathcal{F}}F\neq\emptyset$.

### 解答 5.2

由**定义 5.15 (开覆盖与有限子覆盖)** 与**定义 5.16 (紧致空间)**, 分两个方向证明.

($\Rightarrow$) 设 $X$ 紧致, $\mathcal{F}$ 是具有限交性质的闭集族. 若 $\bigcap_{F\in\mathcal{F}}F=\emptyset$, 则 $\left\{X\setminus{F}:F\in\mathcal{F}\right\}$ 是 $X$ 的开覆盖: 各 $F$ 闭, 由**定义 3.21 (闭集)** 其补开. 由**定义 5.16 (紧致空间)**, 它有有限子覆盖 $X\setminus{F}_1,\dots,X\setminus{F}_k$, 即 $X=\bigcup_{i=1}^{k}\left(X\setminus{F}_i\right)$. 取补集得 $\bigcap_{i=1}^{k}F_i=\emptyset$, 与**定义 5.17 (有限交性质)** 矛盾. 故全族之交非空.

($\Leftarrow$) 设任意具有限交性质的闭集族之交非空. 任取 $X$ 的开覆盖 $\left\{U_i\right\}$. 令 $F_i=X\setminus{U}_i$, 由**定义 3.21 (闭集)** 各 $F_i$ 闭. 若 $\left\{U_i\right\}$ 无有限子覆盖, 则任意有限个 $F_{i_1},\dots,F_{i_k}$ 满足

$$
\bigcap_{j=1}^{k}F_{i_j}=X\setminus\bigcup_{j=1}^{k}U_{i_j}\neq\emptyset,
$$

即 $\left\{F_i\right\}$ 具有限交性质. 由假设 $\bigcap_iF_i\neq\emptyset$, 即 $X\setminus\bigcup_iU_i\neq\emptyset$, 与 $\left\{U_i\right\}$ 覆盖 $X$ 矛盾. 故存在有限子覆盖, 由**定义 5.16 (紧致空间)**, $X$ 紧致. $\blacksquare$

## 7.5 (紧集与不相交闭集的距离为正)

设 $A,B$ 是度量空间 $\left(X,d\right)$ 中不相交的闭集, 且 $A$ 紧致. 证明 $d\left(A,B\right)>0$.

### 解答 5.3

令 $g\left(x\right)=d\left(x,B\right)$. 由**定义 6.46 (点到集合的距离)**, $g$ 有定义. 由**定义 6.35 (度量空间)** 的三角不等式与**定义 6.46 (点到集合的距离)**, 对任意 $x,y\in{X}$ 与 $b\in{B}$ 有 $d\left(x,b\right)\le{d}\left(x,y\right)+d\left(y,b\right)$, 对 $b$ 取下确界再对称化得 $\left|g\left(x\right)-g\left(y\right)\right|\le{d}\left(x,y\right)$; 于是 $x_n\to{x}$ 蕴含 $g\left(x_n\right)\to{g}\left(x\right)$, 由**说明 6.51 (度量连续与序列)**, $g$ 连续. 因 $A$ 紧致, 由**定理 5.11 (紧空间上连续函数取最大值)**, $g$ 在 $A$ 上取到最小值

$$
m=\min_{a\in{A}}g\left(a\right)=\inf_{a\in{A},\,b\in{B}}d\left(a,b\right)=d\left(A,B\right).
$$

若 $m=0$, 则存在 $a_0\in{A}$ 使 $d\left(a_0,B\right)=0$, 即对每个 $r>0$ 开球 $B\left(a_0,r\right)$ 都与 $B$ 相交 (由**定义 6.36 (开球)**); 因 $a_0\notin{B}$ (由 $A\cap{B}=\emptyset$), 由**定义 3.24 (极限点)** $a_0$ 是 $B$ 的极限点. 由**定理 3.5 (闭包与极限点)** $a_0\in\overline{B}$, 而 $B$ 闭, 由**定义 3.26 (闭包)** $\overline{B}=B$, 故 $a_0\in{B}$, 与 $A\cap{B}=\emptyset$ 矛盾. 故 $m>0$, 即 $d\left(A,B\right)>0$. $\blacksquare$

## 7.6 (无孤立点度量空间中紧致等价于闭集间距离皆为正)

设 $\left(X,d\right)$ 是无孤立点的度量空间. 证明: $X$ 紧致当且仅当对任意一对不相交闭集 $A,B$, 都有 $d\left(A,B\right)>0$.

### 解答 5.4

($\Rightarrow$) 设 $X$ 紧致, $A,B$ 为不相交闭集. 由**定理 5.4 (闭子集紧)**, $A$ 紧致. 由**习题 5.3**的论证 (连续函数 $d\left(\cdot,B\right)$ 在 $A$ 上取到正最小值) 即得 $d\left(A,B\right)>0$.

($\Leftarrow$) 反证, 设 $X$ 不紧致. 由**定理 6.1 (紧 $=$ 序列紧)**, $X$ 不是序列紧致的, 故存在序列 $\left\{x_n\right\}$ 无收敛子列. 必要时取子列使 $x_n$ 两两不同. 于是 $S=\left\{x_n:n\ge1\right\}$ 无极限点: 若 $x$ 是 $S$ 的极限点, 由**定义 3.24 (极限点)** 每个开球 $B\left(x,1/k\right)$ 都含 $S\setminus\left\{x\right\}$ 的点, 且事实上含无穷多个 (若某球只含有限个, 取半径小于这些点到 $x$ 的距离, 得与极限点定义矛盾的球), 故可归纳选取两两不同的 $x_{n_k}\in{B}\left(x,1/k\right)$, 得收敛于 $x$ 的子列, 矛盾. 故 $S'=\emptyset$, 由**定理 3.5 (闭包与极限点)** $\overline{S}=S$, 由**定义 3.26 (闭包)** $S$ 闭. 因 $X$ 无孤立点, 每个 $x_n$ 的任意邻域都含异于 $x_n$ 的点; 归纳地选取 $y_n$, 使 $0<{}d\left(y_n,x_n\right)<1/n$, 且 $y_n\notin{S}\cup\left\{y_1,\dots,y_{n-1}\right\}$. 则 $\left\{y_n\right\}$ 也无收敛子列: 若 $y_{n_k}\to{y}$, 则由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x_{n_k},y\right)\le{d}\left(x_{n_k},y_{n_k}\right)+d\left(y_{n_k},y\right)\to0,
$$

与 $\left\{x_n\right\}$ 无收敛子列矛盾. 故 $T=\left\{y_n:n\ge1\right\}$ 也闭 (同上). 令 $A=S$, $B=T$, 则二者不相交闭, 但对一切 $n$ 有 $d\left(A,B\right)\le{d}\left(x_n,y_n\right)<1/n$, 故 $d\left(A,B\right)=0$, 与假设矛盾. 因此 $X$ 紧致. $\blacksquare$

## 7.7 (黎曼球面（单点紧化）紧致)

考虑 $\mathbb{C}$ 与一个无穷远点 $\left\{\infty\right\}$. 记 $\overline{\mathbb{C}}=\mathbb{C}\cup\left\{\infty\right\}$, 规定 $U\subset\overline{\mathbb{C}}$ 的拓扑为: 若 $\infty\notin{U}$, 则 $U$ 开当且仅当它是 $\mathbb{C}$ 中通常开集; 若 $\infty\in{U}$, 则 $U$ 开当且仅当 $\mathbb{C}\setminus\left(U\cap\mathbb{C}\right)$ 在 $\mathbb{C}$ 中紧致. 证明 $\overline{\mathbb{C}}$ 紧致. 此即亚历山德罗夫单点紧化, $\overline{\mathbb{C}}$ 称为黎曼球面.

### 解答 5.5

由**定义 7.5 (单点紧化)**, $\overline{\mathbb{C}}$ 正是 $\mathbb{C}$ 的单点紧化. 任取 $\overline{\mathbb{C}}$ 的开覆盖 $\mathcal{U}$. 取 $U_\infty\in\mathcal{U}$ 使 $\infty\in{U}_\infty$. 由拓扑定义, $K=\mathbb{C}\setminus\left(U_\infty\cap\mathbb{C}\right)$ 在 $\mathbb{C}$ 中紧致. 族

$$
\left\{U\cap\mathbb{C}:U\in\mathcal{U}\setminus\left\{U_\infty\right\}\right\}
$$

中每个集合是 $\mathbb{C}$ 中开集 (不含 $\infty$ 的开集在 $\overline{\mathbb{C}}$ 与在 $\mathbb{C}$ 中同样开), 且它们覆盖 $K$ (因 $K$ 与 $U_\infty$ 无交). 由 $K$ 紧致, 即由**定义 5.16 (紧致空间)**, 有有限子族 $U_1,\dots,U_m$ 使 $K\subset\bigcup_{i=1}^{m}U_i$. 于是 $U_\infty,U_1,\dots,U_m$ 覆盖 $\overline{\mathbb{C}}$: $U_\infty$ 含 $\infty$ 与 $U_\infty\cap\mathbb{C}$, 其余集合覆盖 $K$. 故 $\overline{\mathbb{C}}$ 的任意开覆盖都有有限子覆盖, 由**定义 5.16 (紧致空间)**, $\overline{\mathbb{C}}$ 紧致. $\blacksquare$

## 7.8 (有限离散空间紧致)

给 $\left\{1,\dots,k\right\}$ 赋离散拓扑. 证明 $\left\{1,\dots,k\right\}$ 在该拓扑下紧致.

### 解答 5.6

设 $\mathcal{U}$ 是 $\left\{1,\dots,k\right\}$ 的任意开覆盖. 由**定义 5.15 (开覆盖与有限子覆盖)**, 对每个点 $i\in\left\{1,\dots,k\right\}$ 选取 $U_i\in\mathcal{U}$ 使 $i\in{U}_i$. 则 $\left\{U_1,\dots,U_k\right\}$ 是有限子族且仍覆盖 $\left\{1,\dots,k\right\}$. 由**定义 5.16 (紧致空间)**, $\left\{1,\dots,k\right\}$ 紧致. $\blacksquare$

> 离散拓扑: 每个点自己就是开集, 开集的并也是开集, 这么说每个点又都是闭集, 所以每个点都是开闭集.

## 7.9 (吉洪诺夫定理：映射空间 $\left\{1,\dots,k\right\}^{V}$ 紧致)

用吉洪诺夫定理证明: 映射集合 $X=\left\{f:V\to\left\{1,\dots,k\right\}\right\}$ 紧致.

### 解答 5.7

集合 $X=\left\{1,\dots,k\right\}^{V}=\prod_{v\in{V}}\left\{1,\dots,k\right\}$ 是离散有限空间 $\left\{1,\dots,k\right\}$ 的乘积. 由**习题 5.6**, 每个因子 $\left\{1,\dots,k\right\}$ 紧致. 由**定理 5.9 (吉洪诺夫定理)**, 乘积 $X$ 在乘积拓扑下紧致. $\blacksquare$

## 7.10 (连续等价于在每个紧子集上连续)

设 $X,Y$ 是度量空间, $f:X\to{Y}$. 证明: $f$ 连续当且仅当 $f$ 在任意紧子集 $K\subset{X}$ 上的限制都连续.

### 解答 5.8

($\Rightarrow$) 设 $f$ 连续, $K\subset{X}$ 紧. 由**定义 3.22 (连续映射)** 与**定义 3.19 (子空间拓扑)**, $f|_K$ 连续: 对 $Y$ 中开集 $U$, $\left(f|_K\right)^{-1}\left(U\right)=f^{-1}\left(U\right)\cap{K}$ 是 $K$ 中开集.

($\Leftarrow$) 反设 $f$ 在某点 $x$ 不连续. 由**说明 6.51 (度量连续与序列)** 的逆否与**定义 3.25 (邻域与极限)**, 存在 $\varepsilon>0$ 与序列 $x_n\to{x}$ 使 $d_Y\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon$. 集合 $K=\left\{x\right\}\cup\left\{x_n\right\}$ 紧致: 任取开覆盖, 含 $x$ 的开集 $U$ 是 $x$ 的邻域 (由**定义 3.25 (邻域与极限)**), 由 $x_n\to{x}$ 它含除有限个外的所有 $x_n$; 其余有限个点再各取一个覆盖元, 得有限子覆盖. 由假设 $f|_K$ 连续, 故 $x_n\to{x}$ 时由**说明 6.51 (度量连续与序列)** 应有 $f\left(x_n\right)\to{f}\left(x\right)$, 矛盾. 因此 $f$ 处处连续. $\blacksquare$

## 7.11 (豪斯多夫空间中局部紧的两种表述等价)

设 $X$ 是豪斯多夫空间. 证明: $X$ 局部紧 (即每点有紧邻域基) 当且仅当每点有一个紧邻域.

### 解答 5.9

($\Rightarrow$) 设每点有紧邻域基 (即题目括号中的表述, 见**定义 7.4 (局部紧空间)**). 则对每个 $x$, 其紧邻域基的任一成员都是 $x$ 的一个紧邻域. 故每点有一个紧邻域.

($\Leftarrow$) 设每点有一个紧邻域. 取 $x$ 的紧邻域 $K$; 由**定理 5.5 (豪斯多夫中紧集闭)**, $K$ 闭. 任取 $x$ 的邻域 $U$, 即含 $x$ 的开集 (由**定义 3.25 (邻域与极限)**). 令 $L=K\setminus{U}$, 它是紧集 $K$ 的闭子集, 由**定理 5.4 (闭子集紧)** 紧. 对每个 $y\in{L}$, 由**定义 3.10 (豪斯多夫空间)** 有不相交开集 $O_y\ni{x}$, $W_y\ni{y}$; 因 $L$ 紧, $L\subset\bigcup_{i=1}^{m}W_{y_i}$ 对某个有限子族成立. 令 $O=\bigcap_{i=1}^{m}O_{y_i}$, 由**定义 3.18 (拓扑空间)** (有限交仍开) $O$ 是含 $x$ 的开集, 且 $O\cap\bigcup_{i=1}^{m}W_{y_i}=\emptyset$, 故 $O\cap{L}=\emptyset$. 记 $W=\bigcup_{i=1}^{m}W_{y_i}$, 则 $O\subset{X}\setminus{W}$ 且 $X\setminus{W}$ 闭, 由**定义 3.26 (闭包)** $\overline{O}\subset{X}\setminus{W}$; 于是 $\overline{O}\cap{K}\subset\left(X\setminus{W}\right)\cap{K}\subset{K}\setminus{L}=K\cap{U}\subset{U}$. 又 $\overline{O}\cap{K}$ 是紧集 $K$ 的闭子集 ($\overline{O}$ 闭, 见**定义 3.26 (闭包)**), 由**定理 5.4 (闭子集紧)** 紧; 它含 $x$ 的开邻域 $O\cap\operatorname{int}\left(K\right)$. 故 $x$ 有含于 $U$ 的紧邻域; 因 $U$ 任意, $x$ 有紧邻域基. 由题目括号中的表述 (局部紧即每点有紧邻域基), $X$ 局部紧. $\blacksquare$

## 7.12 (单位球紧致当且仅当空间维数有限)

(维数与紧性) 证明: 任意实赋范线性空间的单位球紧致, 当且仅当该空间维数有限.

### 解答 5.10

设 $E$ 是**定义 6.20 (赋范线性空间)** 中的空间.

($\Leftarrow$) 设 $\dim{E}=n<\infty$. 由有限维实赋范线性空间与欧几里得空间线性同胚, $E$ 线性同构于 $\mathbb{R}^n$ 且该同胚是同胚. 单位球是有界闭集: 有界由范数定义, 闭由 $\left\|\cdot\right\|$ 连续 (三角不等式 (**定义 6.20 (赋范线性空间)**) 给出 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$) 得出. 故其在 $\mathbb{R}^n$ 中的像闭且有界, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 紧; 紧性在同胚下保持 (由**定理 5.1 (紧空间连续像紧)** 或同胚定义), 故单位球紧.

($\Rightarrow$) 反之, 若 $E$ 无穷维, 由**定理 6.17 (里茨定理)**, 其闭单位球非紧. 故单位球紧致蕴含维数有限. $\blacksquare$

## 7.13 (单射连续当且仅当紧集的像皆紧)

设 $E,F$ 是两个度量空间, $f:E\to{F}$ 是单射.

(1) 证明: $f$ 连续当且仅当对每个紧集 $K\subset{E}$, 像集 $f\left(K\right)$ 在 $F$ 中是紧集;

(2) 举例说明若 $f$ 不单射, 上述等价可以失效.

### 解答 5.11

(1) ($\Rightarrow$) 设 $f$ 连续, $K\subset{E}$ 紧. $f|_K$ 连续 (由**定义 3.22 (连续映射)** 与**定义 3.19 (子空间拓扑)**, 同**习题 5.8** ($\Rightarrow$)), 由**定理 5.1 (紧空间连续像紧)**, $f\left(K\right)$ 紧.

($\Leftarrow$) 设对每个紧集 $K\subset{E}$, $f\left(K\right)$ 紧. 反设 $f$ 在某点 $x$ 不连续. 由**说明 6.51 (度量连续与序列)** 的逆否与**定义 3.25 (邻域与极限)**, 存在 $\varepsilon>0$ 与序列 $x_n\to{x}$ 使 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon$. 由 $f$ 单射及 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon>0$ 知 $x_n\neq{x}$. 令 $K=\left\{x\right\}\cup\left\{x_n:n\ge1\right\}$, 它紧 (同**习题 5.8**的论证: 收敛序列加极限). 由假设 $f\left(K\right)$ 紧; $F$ 是度量空间, 由**说明 6.50 (度量空间是豪斯多夫的)** 豪斯多夫, 由**定理 5.5 (豪斯多夫中紧集闭)**, $f\left(K\right)$ 在 $F$ 中闭.

由**定理 6.1 (紧 $=$ 序列紧)**, $f\left(x_n\right)$ 在紧集 $f\left(K\right)$ 中有收敛子列 $f\left(x_{n_j}\right)\to{y}\in{f}\left(K\right)$. 设 $y=f\left(z\right)$, $z\in{K}$. 若 $z=x$, 则 $f\left(x_{n_j}\right)\to{f}\left(x\right)$, 与 $d_F\left(f\left(x_{n_j}\right),f\left(x\right)\right)\ge\varepsilon$ 矛盾. 故 $z=x_m$ 是某固定项. 取尾部紧集 $K'=\left\{x\right\}\cup\left\{x_{n_j}:j>{}m\right\}$. 由假设 $f\left(K'\right)$ 紧, 再由**定理 5.5 (豪斯多夫中紧集闭)** $f\left(K'\right)$ 闭. 但 $f\left(x_{n_j}\right)\to{f}\left(x_m\right)$ 且 $x_m\notin{K}'$, 由 $f$ 单射 $f\left(x_m\right)\notin{f}\left(K'\right)$; 而 $f\left(x_m\right)$ 是 $f\left(K'\right)$ 的极限点 (每个邻域含充分大的 $f\left(x_{n_j}\right)$, 由**定义 3.25 (邻域与极限)**), 由**定理 3.5 (闭包与极限点)** 与**定义 3.26 (闭包)** 应有 $f\left(x_m\right)\in\overline{f\left(K'\right)}=f\left(K'\right)$, 矛盾. 故 $f$ 连续.

(2) 取 $E=\left\{0\right\}\cup\left\{1/n:n\ge1\right\}$, $F=\left\{0,1\right\}$ 装备离散度量, $f\left(0\right)=0$, $f\left(1/n\right)=1$ 对一切 $n$. $f$ 不单射. 对 $E$ 中任何紧集 $K$, 像 $f\left(K\right)\subset\left\{0,1\right\}$; 离散空间中任何有限子集都紧 (**习题 5.6**), 故 $f$ 保持紧集; 但 $x_n=1/n\to0$ 时 $f\left(x_n\right)=1$ 不趋于 $f\left(0\right)=0$, 由**定义 3.25 (邻域与极限)** $f$ 不连续. 可见单射不可少. $\blacksquare$
