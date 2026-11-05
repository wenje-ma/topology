# week5

> **定理 2.8 (施罗德-伯恩斯坦定理)**
> 
> 若同时存在 $X\to Y$ 与 $Y\to X$ 的单射, 则 $X$ 与 $Y$ 基数相等. (教材 §2)

> **定理 2.13 (实数与自然数幂集等势)**
> 
> $\left|\mathbb R\right|=\left|\mathcal P\left(\mathbb N\right)\right|$. (教材 §2)

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定理 3.5 (闭包与极限点)**
> 
> $A$ 的闭包是 $A$ 与其全体极限点之并: $\overline A=A\cup A'$. (教材 $\S3$, 定理 3.5)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.15 (拓扑基)**
> 
> 设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:
> 
> (1) $\emptyset,X\in T$;
> 
> (2) 若 $U,V\in T$, 则 $U\cap V\in T$;
> 
> (3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$, p12)

> **定义 3.19 (子空间拓扑)**
> 
> 设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 §3, p17; 题集 §1.2)

> **定义 3.20 (边界)**
> 
> $\partial A=\overline A\setminus\operatorname{int}\left(A\right)$. 等价地, $\partial F=F\cap\overline{E\setminus F}$ 当 $F\subset E$ 闭. (教材 §3)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset X$ 是闭的, 若 $X\setminus F$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.23 (同胚)**
> 
> 空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 §3, p15)

> **定义 3.25 (邻域与极限)**
> 
> $b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$, p16)

> **定义 3.26 (闭包)**
> 
> 集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 3.33 ($T_1$ 空间)**
> 
> 单点集皆闭; 豪斯多夫空间必为 $T_1$ 空间. (教材 §3)

> **定理 4.1 (区间连通)**
> 
> $\left[0,1\right]$ 连通; 由此任意区间连通. (教材 §4, p23; 《拓扑学》(原书第2版) §24 推论 24.2)

> **定理 4.2 (连续像连通)**
> 
> $X$ 连通, $f:X\to Y$ 连续, 则 $f\left(X\right)$ 连通. (教材 §4, p23)

> **定理 4.3 (路径连通蕴含连通)**
> 
> 路径连通空间是连通的. (教材 §4, p24)

> **定理 4.5 (可数度量空间完全不连通)**
> 
> 每个可数度量空间都是完全不连通的. (教材 §4, p25)

> **定理 4.6 (扇形连通)**
> 
> 一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 §4, p26)

> **定理 4.7 (乘积连通)**
> 
> 连通集 $A,B$ 之积 $A\times B$ 连通; 有限个连通集的乘积连通. (教材 §4, p26 推论 4.7)

> **定义 4.8 (连通分支)**
> 
> 含点 $x$ 的唯一极大连通集 $A\left(x\right)$; 它是闭集; 分支数有限时分支开. (教材 §4, p27)

> **定义 4.9 (局部连通)**
> 
> 每点有由连通邻域组成的邻域基. (题集 §2.1)

> **定义 4.10 (局部路径连通)**
> 
> 每点有由路径连通邻域组成的邻域基. (题集 §2.1 Q3)

> **定义 4.11 (弗斯滕伯格拓扑)**
> 
> $\mathbb Z$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$ ($a\neq0$) 为基的拓扑; $S\left(a,b\right)$ 既开又闭. (题集 §2.2)

> **定义 4.12 (戈洛姆拓扑)**
> 
> $\mathbb Z_{> 0}$ 上以 $\left\{an+b:n\in\mathbb N\right\}$ ($a,b$ 互素) 为基的拓扑. (题集 §2.2)

> **定义 4.13 (基尔希拓扑)**
> 
> $\mathbb Z_{> 0}$ 上以 $\left\{pn+b:n\in\mathbb N\right\}$ ($p$ 为素数且 $p\nmid b$) 为基的拓扑. (题集 §2.2)

> **定义 4.14 ($\varepsilon$-链空间)**
> 
> $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in X$ 可由相邻距离 $< \varepsilon$ 的有限点列连接; 对一切 $\varepsilon> 0$ 都成立称全链. (题集 §4.5 C5)

> **定理 4.15 (闭包保持连通性)**
> 
> 连通集的闭包仍连通. (教材 §4, p27)

> **定理 4.16 (谢尔宾斯基同胚定理)**
> 
> 任意两个无孤立点的可数可度量化空间互相同胚. (题集 §2.2)

> **定义 4.17 (不动点)**
> 
> $f:X\to X$ 的不动点是满足 $f\left(x\right)=x$ 的点 $x\in X$. (题集 §7.2)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset X$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

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
> 任意 $x,y\in X$ 有连续路径 $\gamma:\left[0,1\right]\to X$ 以 $x,y$ 为端点. (教材 §4, p24)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb R^n$ 凸即 $x,y\in K$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定义 4.24 (拓扑学家正弦曲线)**
> 
> $y=\sin\left(1/x\right)$ 在 $\left(0,1\right]$ 上的图像与 $y$ 轴上 $\left[-1,1\right]$ 的并; 它连通但不路径连通. (教材 §4, p24)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3 ($\mathbb R^n$ 中的紧集)**
> 
> $K\subset\mathbb R^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4 (闭子集紧)**
> 
> 若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **定理 5.11 (紧空间上连续函数取最大值)**
> 
> 紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.17 (里茨定理)**
> 
> 无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定义 6.35 (度量空间)**
> 
> 度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:
> 
> (1) $d\left(x,x\right)=0$;
> 
> (2) 若 $d\left(x,y\right)=0$ 则 $x=y$;
> 
> (3) $d\left(x,y\right)=d\left(y,x\right)$;
> 
> (4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.36 (开球)**
> 
> 开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)< r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.7 (正则空间)**
> 
> 闭集 $A$ 与不在 $A$ 中的点有不相交开邻域. (教材 §7)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to Y$ 使 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to Z$ 连续当且仅当 $gf:X\to Z$ 连续. (教材 §11, p61; 《基础拓扑学》(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定理 24.3 (介值定理)**
> 
> 设 $f:X\to Y$ 连续, $X$ 连通, $Y$ 为序拓扑全序集; 若 $r$ 介于 $f\left(a\right)$ 与 $f\left(b\right)$ 之间, 则存在 $c\in X$ 使 $f\left(c\right)=r$. 特别地, 连续函数在区间上取到中间值. (《拓扑学》(原书第2版) §24 定理 24.3, p118)

> **定理 34.1 (乌雷松度量化定理)**
> 
> 每一个具有可数基的正则空间都是可度量化的. (《拓扑学》(原书第2版) §34 定理 34.1, p165; 教材 §7 定理 7.3, p43 表述为正规空间加可数基可度量化, 而正则加可数基蕴含正规)

## 5.1 (拓扑学家正弦曲线连通但不路径连通)

证明拓扑学家正弦曲线连通但不路径连通.

### 解答 3.7

记

$$
G=\left\{\left(x,\sin\frac1x\right):0< x\le1\right\},\quad L=\left\{0\right\}\times\left[-1,1\right],\quad S=G\cup L.
$$

由**定义 4.24 (拓扑学家正弦曲线)**, $S$ 即拓扑学家正弦曲线.

先证连通. $G$ 以 $x$ 为参数路径连通, 故由**定理 4.3 (路径连通蕴含连通)** $G$ 连通. 当 $x\to0^{+}$ 时 $\sin\left(1/x\right)$ 在 $\left[-1,1\right]$ 上稠密振荡, 故 $G$ 的闭包 $\overline G=G\cup L=S$ (**定义 3.26 (闭包)**). 由**定理 4.15 (闭包保持连通性)**, $\overline G$ 连通, 故 $S$ 连通 (**定义 4.18 (连通空间)**).

再证不路径连通. 反设存在路径 $\gamma:\left[0,1\right]\to S$ 以 $\left(0,0\right)\in L$ 为起点, 以 $\left(1,\sin1\right)\in G$ 为终点. 令 $t_0=\inf\left\{t:\gamma\left(t\right)\text{ 的横坐标}> 0\right\}$. 由连续性 $\gamma\left(t_0\right)\in L$. 取 $t_n\downarrow t_0$, 则 $\gamma\left(t_n\right)=\left(x_n,\sin\left(1/x_n\right)\right)$, $x_n\to0^{+}$. 序列 $\sin\left(1/x_n\right)$ 既有收敛到 $1$ 的子列, 又有收敛到 $-1$ 的子列, 不可能收敛到 $\gamma\left(t_0\right)$ 的纵坐标, 与 $\gamma$ 连续矛盾. 故不存在这样的路径, $S$ 不路径连通, 即它不是**定义 4.22 (路径连通)** 意义下的路径连通空间. $\blacksquare$

## 5.2 (连通等价于到两点空间的连续映射常值，以及乘积去方块后的连通性)

连通性与连续函数. 证明: $X$ 是**定义 4.18 (连通空间)** 当且仅当一切连续映射 $f:X\to\left\{0,1\right\}$ (目标装备离散拓扑) 都是常值的. 再设 $A,B$ 是两个连通度量空间, $X,Y$ 分别是 $A,B$ 的真子集. 证明 $C=\left(A\times B\right)\setminus\left(X\times Y\right)$ 是 $A\times B$ 的连通子集.

### 解答 3.8

($\Rightarrow$) 设 $X$ 是**定义 4.18 (连通空间)**, $f:X\to\left\{0,1\right\}$ 连续. 由**定理 4.2 (连续像连通)**, $f\left(X\right)$ 连通; 离散两点集 $\left\{0,1\right\}$ 的连通子集只有单点, 故 $f\left(X\right)$ 是单点集, 即 $f$ 常值.

($\Leftarrow$) 若 $X$ 不连通, 则 $X=U\cup V$, $U,V$ 非空不相交开集. 定义 $f$ 在 $U$ 上取 $0$, 在 $V$ 上取 $1$; 因 $U,V$ 既开又闭, 由**定义 3.22 (连续映射)** $f$ 连续, 但 $f$ 非常值. 矛盾.

第二问: $C=\left(\left(A\setminus X\right)\times B\right)\cup\left(A\times\left(B\setminus Y\right)\right)$. 因 $X,Y$ 是真子集, 可取 $a_0\in A\setminus X$, $b_0\in B\setminus Y$. 固定 $b_0$, 集合 $A\times\left\{b_0\right\}$ 由**定理 4.7 (乘积连通)** 连通. 对每个 $a\in A\setminus X$, 集合 $\left\{a\right\}\times B$ 连通 (**定理 4.7 (乘积连通)**), 且与 $A\times\left\{b_0\right\}$ 交于 $\left(a,b_0\right)$. 由**定理 4.6 (扇形连通)**, $S=A\times\left\{b_0\right\}\cup\bigcup_{a\in A\setminus X}\left\{a\right\}\times B$ 连通. 再对每个 $b\in B\setminus Y$, 集合 $A\times\left\{b\right\}$ 连通, 且与 $S$ 交于 $\left(a_0,b\right)$. 再用**定理 4.6 (扇形连通)**, 加入所有 $A\times\left\{b\right\}$ 后仍连通, 所得正是 $C$. $\blacksquare$

## 5.3 (边界连通蕴含闭集连通（附闭性不可少的反例）)

连通性与边界. 设 $E$ 是连通度量空间, $F$ 是 $E$ 的闭集. 证明: 若 $F$ 的边界 $\partial F$ 连通, 则 $F$ 连通. 再举例说明 $F$ 不假设闭时结论失效.

### 解答 3.9

反设 $F$ 不连通. 则 $F$ 有非空分离 $F=A\cup B$, $A,B$ 非空不相交, 且在 $F$ 中既开又闭. 因 $F$ 在 $E$ 中闭, 由**定义 3.21 (闭集)**, $A,B$ 在 $E$ 中也闭. 由**定义 3.20 (边界)**, $\partial F=F\cap\overline{E\setminus F}$. 断言

$$
\partial F=\left(A\cap\overline{E\setminus F}\right)\cup\left(B\cap\overline{E\setminus F}\right),
$$

两边都非空. 若 $A\cap\overline{E\setminus F}=\emptyset$, 则 $A\subset\operatorname{int}\left(F\right)$; 又 $A$ 在 $F$ 中开, 即 $A=F\cap O$ ($O$ 开于 $E$), 于是 $A=O\cap\operatorname{int}\left(F\right)$ 在 $E$ 中开. $A$ 在 $E$ 中既开又闭, 由**定义 4.19 (既开又闭集)**, $E$ 连通推出 $A=\emptyset$ 或 $E$, 与 $A$ 是 $F$ 的非空真子集矛盾. 故 $A\cap\overline{E\setminus F}\neq\emptyset$, 同理 $B\cap\overline{E\setminus F}\neq\emptyset$. 这两个非空不交闭集分离了 $\partial F$, 与 $\partial F$ 连通矛盾. 故 $F$ 连通.

反例: 取 $E=\left[0,1\right]$, $F=\left[0,1/2\right)\cup\left(1/2,1\right]$. $F$ 不闭, 且不连通; 但 $\partial F=\left\{1/2\right\}$ 是单点, 连通. $\blacksquare$

## 5.4 ($\varepsilon$-链空间：连通蕴含链性，紧且链性蕴含连通)

链空间. 称度量空间 $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in X$ 可由有限点列 $x_0=a,\dots,x_n=b$ 连接使 $d\left(x_i,x_{i+1}\right)< \varepsilon$; 对一切 $\varepsilon> 0$ 都成立称**定义 4.14 ($\varepsilon$-链空间)**. 证明: $X$ 连通则 $X$ 是 $\varepsilon$-链空间; $X$ 紧且 $\varepsilon$-链则 $X$ 连通; 举例说明 $\varepsilon$-链空间可以不连通.

### 解答 3.10

连通 $\Rightarrow$ $\varepsilon$-链: 固定 $\varepsilon> 0$, 定义 $a\sim b$ 为存在 $\varepsilon$-链. 等价类在**定义 6.36 (开球)** $B\left(x,\varepsilon\right)$ 下封闭, 故每个等价类开; 其余等价类之并也开. 由**定义 4.19 (既开又闭集)**, 连通空间只有一个等价类, 即 $X$ 是**定义 4.14 ($\varepsilon$-链空间)**.

紧且 $\varepsilon$-链 $\Rightarrow$ 连通: 反设 $X$ 不连通, 则 $X=A\cup B$ 为非空不交闭集分离. 因 $X$ 紧, $A,B$ 是闭子集, 由**定理 5.4 (闭子集紧)** 它们紧. 距离 $\delta=d\left(A,B\right)> 0$: 取 $a_n\in A$, $b_n\in B$ 使 $d\left(a_n,b_n\right)\to\delta$, 由**定理 6.1 (紧 $=$ 序列紧)** 抽子列 $a_{n_j}\to a\in A$, $b_{n_j}\to b\in B$, 若 $\delta=0$ 则 $d\left(a,b\right)=0$, 即 $a=b$, 与 $A\cap B=\emptyset$ 矛盾, 故 $\delta> 0$. 取 $\varepsilon< \delta$, 则 $\varepsilon$-链不可能从 $A$ 跨到 $B$, 与 $\varepsilon$-链矛盾.

$\varepsilon$-链但不连通的例子: 有理数集 $\mathbb Q$ 装备通常度量. 对任意 $\varepsilon> 0$, 任意两个有理数之间可插入间距小于 $\varepsilon$ 的有理点列, 故 $\mathbb Q$ 是 $\varepsilon$-链的; 但 $\mathbb Q$ 完全不连通. $\blacksquare$

## 5.5 (自映射皆有不动点蕴含连通，而紧连通不足)

不动点与连通性. 设 $X$ 是度量空间, 假设一切连续映射 $f:X\to X$ 都有不动点. 证明 $X$ 连通. 再问: 若 $X$ 紧且连通, 是否一切连续映射 $f:X\to X$ 都有不动点?

### 解答 3.11

反设 $X$ 不连通, 则 $X=A\cup B$, $A,B$ 非空不相交且由**定义 4.19 (既开又闭集)** 既开又闭. 取 $a\in A$, $b\in B$, 定义 $f$: 在 $A$ 上取常值 $b$, 在 $B$ 上取常值 $a$. 因 $A,B$ 既开又闭, 由**定义 3.22 (连续映射)** $f$ 连续; 但 $f\left(A\right)\subset B$, $f\left(B\right)\subset A$, 而 $A\cap B=\emptyset$, 故 $f$ 无不动点. 矛盾. 故 $X$ 连通.

不一定. 紧且连通不足以保证不动点: 取圆周 $X=S^1$, 旋转 $90^\circ$ 的映射 $f\left(e^{i\theta}\right)=e^{i\left(\theta+\pi/2\right)}$. $S^1$ 紧且连通, $f$ 连续, 但 $f$ 无不动点. $\blacksquare$

> 紧与连通只能保证空间是连在一起的, 而不动点与空间的自同胚相关, 这是两件事.

## 5.6 (连通边界蕴含闭集连通（重述）)

(连通边界) 设 $\left(E,d\right)$ 是连通度量空间, $F\subset E$ 闭, 且 $\partial F$ 连通. 证明 $F$ 连通.

### 解答 3.12

反设 $F$ 不连通. 则 $F$ 有非空分离 $F=A\cup B$, $A,B$ 非空不相交, 且在 $F$ 中既开又闭. 因 $F$ 在 $E$ 中闭, 由**定义 3.21 (闭集)**, $A,B$ 在 $E$ 中也闭. 由**定义 3.20 (边界)**, $\partial F=F\cap\overline{E\setminus F}$. 断言

$$
\partial F=\left(A\cap\overline{E\setminus F}\right)\cup\left(B\cap\overline{E\setminus F}\right),
$$

两边都非空. 若 $A\cap\overline{E\setminus F}=\emptyset$, 则 $A\subset\operatorname{int}\left(F\right)$; 又 $A$ 在 $F$ 中开, 即 $A=F\cap O$ ($O$ 开于 $E$), 于是 $A=O\cap\operatorname{int}\left(F\right)$ 在 $E$ 中开. $A$ 在 $E$ 中既开又闭, 由**定义 4.19 (既开又闭集)**, $E$ 连通推出 $A=\emptyset$ 或 $E$, 与 $A$ 是 $F$ 的非空真子集矛盾. 故 $A\cap\overline{E\setminus F}\neq\emptyset$, 同理 $B\cap\overline{E\setminus F}\neq\emptyset$. 这两个非空不交闭集分离了 $\partial F$, 与 $\partial F$ 连通矛盾. 故 $F$ 连通. $\blacksquare$

## 5.7 (周期连续函数的中点等值问题)

设 $f:\left[0,1\right]\to\mathbb R$ 是一个连续函数并且 $f\left(0\right)=f\left(1\right)$.

(1) (10 分) 证明存在 $x\in\left[0,\frac12\right]$ 使得 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) (10 分) 证明对于任意的整数 $n\ge2$, 存在 $x\in\left[0,1-\frac1n\right]$ 使得 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) (5 分) 证明存在一个连续函数 $f:\left[0,1\right]\to\mathbb R$ 使得对于任意的 $x\in\left[0,\frac35\right]$ 都有 $f\left(x\right)\neq f\left(x+\frac25\right)$.

### 解答 3.13

(1) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac12\right)$, 定义域 $\left[0,\frac12\right]$. 若 $g\left(0\right)=0$, 则 $x=0$ 已满足. 否则

$$
g\left(\frac12\right)=f\left(\frac12\right)-f\left(1\right)=f\left(\frac12\right)-f\left(0\right)=-g\left(0\right),
$$

故 $g\left(0\right)$ 与 $g\left(\frac12\right)$ 异号. 由**定理 24.3 (介值定理)**, 存在 $x\in\left[0,\frac12\right]$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac1n\right)$, 定义域 $\left[0,1-\frac1n\right]$. 累加得

$$
\sum_{j=0}^{n-1}g\left(\frac{j}{n}\right)=\sum_{j=0}^{n-1}\left(f\left(\frac{j}{n}\right)-f\left(\frac{j+1}{n}\right)\right)=f\left(0\right)-f\left(1\right)=0.
$$

若 $g$ 在 $\left[0,1-\frac1n\right]$ 上恒不为 $0$, 因该区间连通 (由**定理 4.1 (区间连通)**), 连续函数 $g$ 的像由**定理 4.2 (连续像连通)** 是 $\mathbb R$ 中不含 $0$ 的连通集, 故必恒正或恒负, 从而各 $g\left(\frac{j}{n}\right)$ 同号, 其和不为 $0$, 矛盾. 故存在 $x$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) 取 $f\left(x\right)=x$. 它连续, 且对任意 $x\in\left[0,\frac35\right]$, $f\left(x+\frac25\right)-f\left(x\right)=\frac25\neq0$, 故 $f\left(x\right)\neq f\left(x+\frac25\right)$. 此例即满足要求. $\blacksquare$

> 这说明, 当步长为 $1/n$ 时能取等, 不是 $1/n$ 则不一定.
> 
> $1/n$ 特殊的原因在于其经过有限次求和后为 $1$, 因此可以利用望远镜级数, 最终求和得到 $f\left(0\right)-f\left(1\right)=0$, 即第 2 问的证明过程.

## 5.8 (球面的连通性、路径连通性、挖去一点后的同胚与紧性)

(2024 年卷 A 题目二, 20 分). 我们记 $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 为 $\mathbb R^3$ 中的单位球面, $D=\left\{\left(x,y\right)\in\mathbb R^2:x^2+y^2\le1\right\}$ 为单位圆盘.

(1) 证明集合 $D^+=\left\{\left(x,y,\sqrt{1-x^2-y^2}\right):\left(x,y\right)\in D\right\}$ 与 $D^-=\left\{\left(x,y,-\sqrt{1-x^2-y^2}\right):\left(x,y\right)\in D\right\}$ 都连通. 由此推导 $S^2$ 连通.

(2) 证明球面 $S^2$ 是路径连通的.

(3) 证明 $\mathbb R^3\setminus\left\{P\right\}$ 与 $S^2$ 同胚, 其中 $P=\left(0,0,2\right)$. 你可以使用球极投影

$$
\pi:\mathbb R^2\to S^2\setminus\left\{\left(0,0,1\right)\right\},\quad
\pi\left(u,v\right)=\frac{\left(2u,2v,u^2+v^2-1\right)}{u^2+v^2+1}.
$$

(4) 证明球面 $S^2$ 是紧的.

### 解答 3.14

(1) 闭单位圆盘 $D\subset\mathbb R^2$ 由**定义 4.23 (凸集)** 是凸集, 凸集中任意两点可由线段连接故路径连通, 路径连通蕴含连通. 映射 $\phi^+:\left(u,v\right)\mapsto\left(u,v,\sqrt{1-u^2-v^2}\right)$ 连续, 其像为 $D^+$. 由**定理 4.2 (连续像连通)**, $D^+$ 连通. 同理 $D^-$ 连通.

$D^+\cap D^-=\left\{\left(x,y,0\right):x^2+y^2=1\right\}\neq\emptyset$. 由**定理 4.6 (扇形连通)**, 两个连通集有公共点其并连通, 故 $S^2=D^+\cup D^-$ 连通. 由**定义 4.18 (连通空间)**, $S^2$ 连通.

(2) 已证 $D^+$ 是 $D$ 在连续映射下的像, $D$ 凸故路径连通, 连续像路径连通; 同理 $D^-$ 路径连通. $D^+\cap D^-\neq\emptyset$, 故 $S^2=D^+\cup D^-$ 路径连通.

(3) 球极投影 $\pi:\mathbb R^2\to S^2\setminus\left\{\left(0,0,1\right)\right\}$ 是双射且双向连续, 由**定义 3.23 (同胚)**, $\mathbb R^2\cong S^2\setminus\left\{\left(0,0,1\right)\right\}$. 要证 $\mathbb R^3\setminus\left\{P\right\}\cong S^2$, 从 $\mathbb R^3\setminus\left\{P\right\}$ 作以 $P$ 为中心的中心投影到平面 $z=0$, 再经 $\pi$ 映到 $S^2\setminus\left\{\left(0,0,1\right)\right\}$; 北极 $\left(0,0,1\right)$ 对应平面方向无穷远点. 该映射连续双射, 逆连续, 为同胚.

(4) $S^2=\left\{\left(x,y,z\right)\in\mathbb R^3:x^2+y^2+z^2=1\right\}$ 是 $\mathbb R^3$ 中有界闭集, 由海涅-博雷尔定理 ($\mathbb R^n$ 中有界闭集紧), $S^2$ 紧. 也可由 $S^2$ 是紧集 $D$ 在连续映射下的像 ($D^+$), 与另一半球面拼接; $D$ 闭且有界故紧 (**定理 6.1 (紧 $=$ 序列紧)**), 连续像紧, 故 $S^2$ 紧. $\blacksquare$

## 5.9 (弗斯滕伯格拓扑的开集刻画与素数无穷)

在 $\mathbb Z$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$ ($a\neq0$) 为基定义拓扑, 即**定义 4.11 (弗斯滕伯格拓扑)**.

(1) 证明 $U\subset\mathbb Z$ 开当且仅当对任意 $x\in U$, 存在某非零 $a\in\mathbb Z$ 使 $S\left(a,x\right)\subset U$;

(2) 验证这确实给出 $\mathbb Z$ 上的拓扑;

(3) 证明 $\mathbb Z$ 中非空有限集不能开; 特别地 $\mathbb Z-\left\{-1,1\right\}$ 不闭;

(4) 证明 $S\left(a,b\right)$ ($a\neq0$) 既开又闭;

(5) 证明对素数 $p$ 取并 $\bigcup_{p\in P}S\left(p,0\right)=\mathbb Z-\left\{-1,1\right\}$;

(6) 证明素数有无穷多个 (弗斯滕伯格的拓扑证明).

### 解答 4.1

(1) 由**定义 3.15 (拓扑基)**, 开集恰为若干 $S\left(a,b\right)$ 之并. 若 $U$ 开且 $x\in U$, 则 $x$ 含于某个并项 $S\left(a,b\right)\subset U$, 而 $x\in S\left(a,b\right)$ 等价于 $b\equiv x\pmod a$, 即 $S\left(a,b\right)=S\left(a,x\right)$. 故存在 $a\neq0$ 使 $S\left(a,x\right)\subset U$. 反过来, 若每点 $x\in U$ 都含某 $S\left(a,x\right)\subset U$, 则 $U=\bigcup_{x\in U}S\left(a_x,x\right)$ 是基元素之并, 故开.

(2) 先验证基条件. 这正是**定义 4.11 (弗斯滕伯格拓扑)** 的基. 两个基元素之交

$$
S\left(a,b\right)\cap S\left(c,d\right)=\left\{x:x\equiv b\pmod a,\ x\equiv d\pmod c\right\}.
$$

它非空当且仅当 $b\equiv d\pmod{\gcd\left(a,c\right)}$; 此时交本身是一个以 $\operatorname{lcm}\left(a,c\right)$ 为步长的等差数列 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$. 故交含某基元素. 又 $S\left(1,0\right)=\mathbb Z$ 覆盖全空间. 由**定义 3.15 (拓扑基)**, 以此生成的开集族满足**定义 3.18 (拓扑空间)** 的全部公理: 任意并由生成方式保证, 有限交由基条件 (2) 保证, $\emptyset$ 与 $\mathbb Z$ 分别为空并与 $S\left(1,0\right)$.

(3) 任一基元素 $S\left(a,x\right)=\left\{an+x:n\in\mathbb Z\right\}$ 是无限集. 非空开集由第 (1) 小题必含某无限集 $S\left(a,x\right)$, 故它本身无限. 因而非空有限集不能开. 特别地 $\left\{-1,1\right\}$ 非空有限, 故不开; 由**定义 3.21 (闭集)**, 其补集 $\mathbb Z-\left\{-1,1\right\}$ 不闭.

(4) $S\left(a,b\right)$ 是基元素, 故开. 其补集

$$
\mathbb Z-S\left(a,b\right)=\bigcup_{r=1}^{a-1}S\left(a,b+r\right)
$$

是其余 $a-1$ 个模 $a$ 剩余类之并, 每个都是基元素, 故补集开. 由**定义 3.21 (闭集)**, $S\left(a,b\right)$ 闭. 故 $S\left(a,b\right)$ 既开又闭 (**定义 4.19 (既开又闭集)**).

(5) $S\left(p,0\right)=\left\{pn:n\in\mathbb Z\right\}$ 是 $p$ 的倍数全体. 整数 $n$ 被某素数整除当且仅当 $\left|n\right|\ge2$; $0$ 被一切素数整除; $\pm1$ 不被任何素数整除. 故

$$
\bigcup_{p\in P}S\left(p,0\right)=\mathbb Z-\left\{-1,1\right\}.
$$

(6) 反设素数只有有限个 $p_1,\dots,p_k$. 由第 (5) 小题,

$$
\bigcup_{i=1}^{k}S\left(p_i,0\right)=\mathbb Z-\left\{-1,1\right\}.
$$

由第 (4) 小题每个 $S\left(p_i,0\right)$ 既开又闭, 有限个既开又闭集之并仍既开又闭 (**定义 4.19 (既开又闭集)**). 故 $\mathbb Z-\left\{-1,1\right\}$ 既开又闭, 其补集 $\left\{-1,1\right\}$ 也既开又闭. 但由第 (3) 小题 $\left\{-1,1\right\}$ 非空有限, 不能开, 矛盾. 故素数有无穷多个. $\blacksquare$

## 5.10 (戈洛姆拓扑与基尔希拓扑的基约化)

在 $\mathbb Z_{> 0}$ 上分别用 (非平凡) 等差数列 $a\mathbb N+b=\left\{an+b:n\in\mathbb N\right\}$ ($a,b$ 互素) 与 $p\mathbb N+b=\left\{pn+b:n\in\mathbb N\right\}$ ($p$ 为素数且 $p\nmid b$) 为基 (前者) 与子基 (后者) 定义两个拓扑.

(1) (戈洛姆) 证明基可限制到满足 $0\le b< a$ 且 $a,b$ 互素的偶对;

(2) (戈洛姆) 验证这确实给出 $\mathbb Z_{> 0}$ 上的拓扑;

(3) (基尔希) 证明基可限制到满足 $0\le b< p$ 且 $p\nmid b$ 的偶对;

(4) (基尔希) 验证这确实给出 $\mathbb Z_{> 0}$ 上的拓扑.

### 解答 4.2

(1) 对基元素 $S\left(a,b\right)=\left\{an+b:n\in\mathbb N\right\}$, $\gcd\left(a,b\right)=1$. 作带余除法 $b=qa+r$, $0\le r< a$. 则 $\gcd\left(a,r\right)=\gcd\left(a,b\right)=1$, 且 $S\left(a,b\right)=\left\{a\left(n+q\right)+r:n\in\mathbb N\right\}\subset S\left(a,r\right)$. 反之, 对 $x=an_0+b\in S\left(a,b\right)$, $\gcd\left(a,x\right)=\gcd\left(a,an_0+b\right)=\gcd\left(a,b\right)=1$, 于是

$$
S\left(a,x\right)=\left\{an+x:n\in\mathbb N\right\}\subset\left\{b+am:m\ge n_0\right\}\subset S\left(a,b\right).
$$

故每点 $x$ 的邻域都可由满足 $0\le r< a$ 的基元素生成, 基可限制到 $0\le b< a$ 且互素的偶对.

(2) 验证基条件. $S\left(a,b\right)\cap S\left(c,d\right)$ 非空当且仅当 $\gcd\left(a,c\right)\mid\left(b-d\right)$; 此时交为 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$, 且 $\gcd\left(\operatorname{lcm}\left(a,c\right),x_0\right)=1$. 它仍是**定义 4.12 (戈洛姆拓扑)** 的基元素. 又 $S\left(1,1\right)=\mathbb Z_{> 0}$ 覆盖全空间. 由**定义 3.15 (拓扑基)** 与**定义 3.18 (拓扑空间)**, 这给出 $\mathbb Z_{> 0}$ 上的拓扑.

(3) 对基尔希的 $S\left(p,b\right)=\left\{pn+b:n\in\mathbb N\right\}$, $p$ 素数, $p\nmid b$. 作带余除法 $b=qp+r$, $0\le r< p$, 则 $p\nmid r$ (否则 $p\mid b$), 且 $S\left(p,b\right)\subset S\left(p,r\right)$. 同第 (1) 小题, 对 $x=pn_0+b\in S\left(p,b\right)$ 有 $p\nmid x$, 故 $S\left(p,x\right)\subset S\left(p,b\right)$. 基可限制到 $0\le b< p$ 且 $p\nmid b$ 的偶对.

(4) 以 $\left\{S\left(p,b\right)\right\}$ 为子基, 其有限交

$$
S\left(p_1,b_1\right)\cap\cdots\cap S\left(p_k,b_k\right)
$$

由中国剩余定理 为 $\left\{x\equiv b_i\pmod{p_i}\right\}=S\left(M,x_0\right)$, 其中 $M=p_1\cdots p_k$, $p_i\nmid x_0$. 两个这样的有限交之交仍是同形的有限交. 故有限交全体构成一个基, 由**定义 3.15 (拓扑基)** 与**定义 3.18 (拓扑空间)** 生成 $\mathbb Z_{> 0}$ 上的**定义 4.13 (基尔希拓扑)**. $\blacksquare$

## 5.11 (三种等差数列拓扑的豪斯多夫性、正则性与连通性)

考察上述拓扑的拓扑性质.

(1) 证明弗斯滕伯格拓扑是豪斯多夫的且正则; 它可度量化但不可完备度量化, 实际上它与带通常子空间拓扑的有理数集 $\mathbb Q$ 同胚;

(2) 证明戈洛姆拓扑与基尔希拓扑是豪斯多夫的但不正则;

(3) 证明弗斯滕伯格拓扑完全不连通, 戈洛姆拓扑连通但不局部连通, 基尔希拓扑既连通又局部连通.

### 解答 4.3

(1) 豪斯多夫: 取 $x\neq y$. 选非零 $a$ 使 $a> \left|x-y\right|$. 若 $S\left(a,x\right)\cap S\left(a,y\right)\neq\emptyset$, 则 $x+an=y+am$, 即 $a\left(n-m\right)=y-x$, 与 $a> \left|x-y\right|$ 矛盾. 故 $S\left(a,x\right)$ 与 $S\left(a,y\right)$ 不相交. 由**定义 3.10 (豪斯多夫空间)**, 弗斯滕伯格拓扑是豪斯多夫的. 由**定义 3.33 ($T_1$ 空间)**, 单点集皆闭.

正则: 设 $A$ 闭, $x\notin A$. 则 $\mathbb Z-A$ 是开集且含 $x$, 由习题 4.1 第 (1) 小题存在 $a\neq0$ 使 $S\left(a,x\right)\subset\mathbb Z-A$, 即 $S\left(a,x\right)\cap A=\emptyset$. 由习题 4.1 第 (4) 小题 $S\left(a,x\right)$ 既开又闭 (**定义 4.19 (既开又闭集)**), 且 $A\subset\mathbb Z-S\left(a,x\right)$, 后者开. 故 $x$ 与 $A$ 有不相交开邻域, 由**定义 7.7 (正则空间)** 弗斯滕伯格拓扑正则.

可度量化与同胚于 $\mathbb Q$: $\mathbb Z$ 可数, 故该拓扑有可数基; 由**定理 34.1 (乌雷松度量化定理)**, 有可数基的正则空间可度量化. 又该拓扑无孤立点: 每点 $x$ 的邻域 $S\left(a,x\right)$ 无限. 由**定理 4.16 (谢尔宾斯基同胚定理)**, 任意两个无孤立点的可数可度量化空间互相同胚, 故它与带通常子空间拓扑的 $\mathbb Q$ 同胚.

不可完备度量化: 反证法. 若它可完备度量化, 则同胚于它的 $\mathbb Q$ 也可完备度量化. 则 $\mathbb Q=\left\{q_1,q_2,\dots\right\}$. 对每一个 $q_n\in\mathbb Q$, 定义 $U_n=\mathbb Q-\left\{q_n\right\}$. 由于 $\left\{q_n\right\}$ 闭, 故 $U_n$ 开, $\left\{U_n\right\}$ 是一族可数稠密开集. 而 $\bigcap_{n=1}^\infty U_n=\bigcap_{n=1}^\infty\left(\mathbb Q-\left\{q_n\right\}\right)=\mathbb Q-\bigcap_{n=1}^\infty\left\{q_n\right\}=\mathbb Q-\mathbb Q=\emptyset$ 是空集, 与**定理 6.13 (贝尔纲定理)** 矛盾. 故它不可完备度量化.

(2) 豪斯多夫: 取 $x\neq y\in\mathbb Z_{> 0}$. 选素数 $p$ 使 $p> \left|x-y\right|$ 且 $p\nmid x$, $p\nmid y$ (这样的素数存在, 因素数无穷). 则 $S\left(p,x\right)$ 与 $S\left(p,y\right)$ 分别是**定义 4.12 (戈洛姆拓扑)** 与**定义 4.13 (基尔希拓扑)** 的基元素; 若相交则 $p\mid\left(x-y\right)$, 与 $p> \left|x-y\right|$ 矛盾. 由**定义 3.10 (豪斯多夫空间)**, 两拓扑均豪斯多夫.

不正则: 以戈洛姆拓扑为例. 取闭集 $E$ 为全体偶正整数 (奇数集开: 对奇 $x$, $S\left(2,x\right)=\left\{x+2n\right\}$ 全奇且 $\gcd\left(2,x\right)=1$), 再取点 $1$. 点 $1$ 的任一邻域形如 $S\left(a,1\right)=\left\{1+an:n\in\mathbb N\right\}$, 而含偶数 $2$ 的任一开集必含某 $S\left(b,2\right)=\left\{2+bn:n\in\mathbb N\right\}$ ($\gcd\left(b,2\right)=1$, 即 $b$ 奇). 由同余式相容, $S\left(a,1\right)\cap S\left(b,2\right)$ 非空, 故无法用不相交开集分离 $1$ 与闭集 $E$. 由**定义 7.7 (正则空间)**, 戈洛姆拓扑不正则. 基尔希拓扑同理不正则.

(3) 弗斯滕伯格完全不连通: 取 $x\neq y$. 选 $a$ 使 $y\notin S\left(a,x\right)$. 由习题 4.1 第 (4) 小题 $S\left(a,x\right)$ 既开又闭且含 $x$ 不含 $y$, 故任何同时含 $x,y$ 的子集都被这个非平凡既开又闭集切断, 不能连通. 由**定义 4.20 (完全不连通)**, 弗斯滕伯格拓扑完全不连通.

戈洛姆连通: 设 $C$ 既开又闭且 $1\in C$. 由标准归纳 (取 $\mathbb Z_{> 0}-C$ 中最小元 $n$, 由于开集 $C$ 必然含 $S\left(a,1\right)$, 可推出 $n\in C$), 得 $C=\mathbb Z_{> 0}$. 故 $\mathbb Z_{> 0}$ 仅有的既开又闭非空集是全空间, 由**定义 4.18 (连通空间)** 戈洛姆拓扑连通. 它不**定义 4.9 (局部连通)**: 点 $1$ 的任一邻域 $S\left(a,1\right)$ 都含非平凡既开又闭子集, 故没有连通邻域基.

基尔希连通且局部连通: 基尔希的基元素 $S\left(p,b\right)$ 本身在该拓扑下连通 (同理由既开又闭集归纳), 故每点有连通邻域, 由**定义 4.9 (局部连通)** 它局部连通; 又全空间仅有的既开又闭非空集是全空间, 由**定义 4.18 (连通空间)** 它连通. $\blacksquare$

> 三个拓扑的精细程度为: $\text{弗斯滕伯格}> \text{戈洛姆}> \text{基尔希}$, 因此 (3) 的结论从直觉上也是成立的. 具体说来, 基尔希连通且局部连通是最粗糙的例子, 因为 $S\left(A,B\right)$ 中的 $A$ 只能是不同素数的乘积, 这导致其局部无法再被分割, 因为找不到更细的 $S$ 了; 而戈洛姆不局部连通, 是因为 $S\left(A,B\right)$ 中的 $A$ 可以是素数的幂, 此时的选择更多, 可以找到更细的 $S$; 弗斯滕伯格不联通, 是因为 $S\left(A,B\right)$ 中的 $A$ 可以是任意数, 此时的选择最多, 以至于 $X$ 可以任意被分割.
