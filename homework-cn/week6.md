# week6（道路连通）

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

> **定义 3.21 (闭集)**
> 
> 称 $F\subset X$ 是闭的, 若 $X\setminus F$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

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

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.7 (正则空间)**
> 
> 闭集 $A$ 与不在 $A$ 中的点有不相交开邻域. (教材 §7)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to Y$ 使 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to Z$ 连续当且仅当 $gf:X\to Z$ 连续. (教材 §11, p61; 《基础拓扑学》(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定理 34.1 (乌雷松度量化定理)**
> 
> 每一个具有可数基的正则空间都是可度量化的. (《拓扑学》(原书第2版) §34 定理 34.1, p165; 教材 §7 定理 7.3, p43 表述为正规空间加可数基可度量化, 而正则加可数基蕴含正规)

## 6.1 (平面区域的单连通与 $n$ 重连通)

(单连通性) 平面区域 $G\subset\mathbb R^2$ 指开且路径连通的子集. 若其余集连通, 称 $G$ 单连通; 若余集由 $n$ 个连通分支组成, 称 $G$ $n$ 重连通. 证明:

(1) 余集的每个分支 $F$ 闭;

(2) $\mathbb R^2\setminus F$ 是单连通区域;

(3) $n$ 重连通区域的边界由 $n$ 个连通分支组成;

(4) $n$ 重连通区域只能连续映到另一个 $n$ 重连通区域; 反过来, 任意两个 $n$ 重连通区域之间是否必有同胚?

### 解答 4.4

(1) $G$ 开, 故由**定义 3.21 (闭集)**, $\mathbb R^2\setminus G$ 闭. 连通分支是闭的 (由**定义 4.18 (连通空间)** 配合分支含其闭包, 而闭包仍连通, 故分支闭). 故 $F$ 闭.

(2) $U=\mathbb R^2\setminus F$ 开. 它路径连通: $G\subset U$ 由**定义 4.22 (路径连通)** 路径连通; 其余余集分支中的点可经边界走入 $G$ (平面余集中恰有一个无界分支, 有界分支被 $G$ 环绕). 而 $U$ 的余集恰为 $F$, 由 (1) 它闭且连通, 由单连通定义即得 $U$ 单连通.

(3) 每个余集分支对应一个边界分支 (如带孔圆盘的典型情形); 由平面拓扑标准事实, 边界分支数等于余集分支数, 即 $n$.

(4) 平面 $n$ 重连通区域彼此同胚 (同胚于带 $n-1$ 个洞的圆盘), 故连续双射 (进而同胚) 保持分支数. 反过来: 是, 任意两个 $n$ 重连通平面区域之间存在同胚. 由**定理 4.3 (路径连通蕴含连通)** 与**定义 4.18 (连通空间)** 可作拓扑分类. (阿尔福斯五岛定理是复分析值分布的著名结果, 可自行检索.) $\blacksquare$

## 6.2 (删齿梳空间的路径分支与证明回顾)

(证明回顾) 回顾路径连通的定义. 回顾删齿梳空间的定义及其非路径连通性的证明. 问: 删齿梳空间有多少个路径连通分支? 若现在允许路径由 $f:\left[0,\infty\right)\to X$ 连续参数化, 同一证明还成立吗? 课上另一个用紧致性的证明呢?

### 解答 4.5

由**定义 4.22 (路径连通)**, $X$ 路径连通指任意两点间有连续路径. 删齿梳空间指

$$
D=\left\{\left(0,0\right),\left(0,1\right)\right\}\cup\bigcup_{n\ge1}\left\{1/n\right\}\times\left[0,1\right]\cup\left(0,1\right]\times\left\{0\right\}.
$$

它是**定义 4.18 (连通空间)** 的, 但不路径连通: 从 $\left(0,1\right)$ 出发的连续路径, 由连续性起步时必在高齿上; 小时间区间连通迫使横坐标取常值, 与离开 $\left(0,1\right)$ 矛盾. 它有两个路径连通分支: $\left\{\left(0,1\right)\right\}$ 与其余部分 (其余部分经底边连通, 由**定理 4.3 (路径连通蕴含连通)** 为一个分支).

改用 $\left[0,\infty\right)$ 参数化时, 上述连通性论证在首个逃逸时刻附近局部成立, 不依赖定义域紧致, 故仍无路径. 课上用紧致性的证明 (连续像 $\gamma\left(\left[0,1\right]\right)$ 紧致, 由**定理 5.1 (紧空间连续像紧)**) 对 $\left[0,\infty\right)$ 失效, 但连通性证明已足够. $\blacksquare$

## 6.3 (差商的像与导函数的值域)

(2024年卷A 题目一) 设 $f:\mathbb R\to\mathbb R$ 可微但不假设 $f'$ 连续, $I\subset\mathbb R$ 为非平凡开区间.

(1) 证明 $A=\left\{\left(x,y\right)\in I^2:x< y\right\}$ 连通;

(2) 令 $F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}$, 证明 $\Gamma=F\left(A\right)$ 在 $\mathbb R$ 中连通;

(3) 证明 $\Gamma\subset f'\left(I\right)\subset\overline\Gamma$;

(4) 证明 $f'\left(I\right)$ 是区间.

### 解答 4.6

(1) $A$ 由不等式 $x< y$ 定义, 是凸集; 由**定义 4.23 (凸集)**, 凸集路径连通, 再由**定理 4.3 (路径连通蕴含连通)**, $A$ 连通.

(2) $f$ 可微故连续, 在 $A$ 上分母非零, $F$ 连续. 由**定理 4.2 (连续像连通)**, $\Gamma=F\left(A\right)$ 连通.

(3) 对 $\left(x,y\right)\in A$ ($x< y$), 由微分中值定理 给出 $c\in\left(x,y\right)\subset I$ 使 $F\left(x,y\right)=f'\left(c\right)$, 故 $\Gamma\subset f'\left(I\right)$. 反之, 对 $x\in I$, 取 $y_n\to x$, $y_n\neq x$, 则 $F\left(x,y_n\right)=\frac{f\left(x\right)-f\left(y_n\right)}{x-y_n}\to f'\left(x\right)$, 而 $F\left(x,y_n\right)\in\Gamma$, 故 $f'\left(x\right)\in\overline\Gamma$.

(4) $\Gamma$ 连通故是区间; 闭包 $\overline\Gamma$ 也是区间 (连通集的闭包仍连通); $f'\left(I\right)$ 夹在二者之间, 故 $f'\left(I\right)$ 是区间. $\blacksquare$

## 6.4 (商映射保持连通性、路径连通性与局部连通性)

设 $X$ 是拓扑空间, $\pi:X\to Y$ 是商映射, $Y$ 配以由 $\pi$ 诱导的商拓扑.

(1) 证明若 $X$ 连通, 则 $Y$ 连通;

(2) 证明若 $X$ 路径连通, 则 $Y$ 路径连通;

(3) 证明若 $\pi$ 是开映射且 $X$ 局部连通 (分别: 局部路径连通), 则 $Y$ 局部连通 (分别: 局部路径连通).

### 解答 4.7

第 (1) 小题: 反证. 若 $Y$ 不连通, 由**定义 4.18 (连通空间)** 存在不相交非空开集 $V,W\subset Y$ 使 $Y=V\sqcup W$. 由**定义 11.2 (粘合映射)**, $\pi^{-1}\left(V\right)$ 与 $\pi^{-1}\left(W\right)$ 是 $X$ 中不相交非空开集, 且 $X=\pi^{-1}\left(V\right)\cup\pi^{-1}\left(W\right)$. 由**定义 4.18 (连通空间)**, 这与 $X$ 连通矛盾. 故 $Y$ 连通.

第 (2) 小题: 任取 $y_1,y_2\in Y$, 取原像 $x_1,x_2\in X$. 由 $X$ 路径连通与**定义 4.22 (路径连通)**, 存在连续路径 $\gamma:\left[0,1\right]\to X$ 以 $x_1,x_2$ 为端点. 由**定理 3.1 (复合连续)**, $\pi\circ\gamma:\left[0,1\right]\to Y$ 连续, 且端点为 $y_1,y_2$. 故 $Y$ 路径连通.

第 (3) 小题: 只证局部连通情形, 局部路径连通完全平行. 任取 $y\in Y$ 与由**定义 3.25 (邻域与极限)** 给出的开邻域 $O\subset Y$. 取 $x\in\pi^{-1}\left(y\right)$. 由**定义 11.2 (粘合映射)**, $\pi^{-1}\left(O\right)$ 是 $x$ 的开邻域. 由 $X$ 局部连通与**定义 4.9 (局部连通)**, 存在连通开集 $U\subset X$ 使 $x\in U\subset\pi^{-1}\left(O\right)$. 因 $\pi$ 是开映射, $\pi\left(U\right)$ 是 $Y$ 中开集; 它含 $y$, 含于 $O$, 且由**定理 4.2 (连续像连通)** 它连通. 故 $y$ 有含于 $O$ 的连通开邻域, $Y$ 局部连通. 对局部路径连通, 把 "连通开集" 换成 "路径连通开集", 由**定义 4.10 (局部路径连通)** 同样在每点取得路径连通开邻域, 再由**定理 3.1 (复合连续)** 路径的连续像仍是路径, 故 $\pi\left(U\right)$ 路径连通, 即得 $Y$ 局部路径连通. $\blacksquare$

## 6.5 (无穷维赋范空间中紧集的余集道路连通)

设 $E$ 是无穷维赋范线性空间, $K\subset E$ 是紧集. 证明 $E\setminus K$ 道路连通. 问有限维赋范线性空间中此结论是否成立?

### 解答 4.8

无穷维情形: 由**定理 6.17 (里茨定理)**, 无穷维赋范线性空间的闭单位球非紧, 故任何紧集 $K$ 必无内部 (否则 $K$ 含某闭球的平移, 该闭球紧, 与里茨定理矛盾).

任取 $x,y\in E\setminus K$. 由**定义 6.46 (点到集合的距离)**, $d\left(x,K\right)> 0$. 考虑从 $x$ 出发的单位方向球面 $S\left(E\right)=\left\{v:\left\|v\right\|=1\right\}$. 连续映射 $r:K\to S\left(E\right)$ 定义为 $r\left(k\right)=\left(k-x\right)/\left\|k-x\right\|$ ($k\neq x$; 因 $x\notin K$ 良定义). 由**定理 5.1 (紧空间连续像紧)**, $r\left(K\right)\subset S\left(E\right)$ 紧. 由**定理 6.17 (里茨定理)**, $S\left(E\right)$ 中任一紧子集无内部, 故可取方向 $v\in S\left(E\right)\setminus r\left(K\right)$. 于是射线 $\left\{x+tv:t\ge 0\right\}$ 与 $K$ 不相交 (若某 $k=x+tv\in K$, 则 $v=r\left(k\right)\in r\left(K\right)$, 矛盾).

取 $L> 0$ 充分大使 $z=x+Lv$ 满足 $\left\|z-y\right\|> d\left(y,K\right)$ 且 $z$ 不在 $K$ 中. 直线段 $\left[x,z\right]$ 避开 $K$. 同理从 $y$ 出发选一好方向 $w$ 使射线 $\left\{y+sw:s\ge 0\right\}$ 避开 $K$, 取 $z'=y+Mw$ 充分远. 最后在远离 $K$ 的地方用直线段 $\left[z,z'\right]$ 连接 (因 $K$ 紧有界, 取 $L,M$ 充分大时该线段也在 $K$ 之外). 所得折线 $x\to z\to z'\to y$ 由**定义 4.22 (路径连通)** 是连续路径, 且全段避开 $K$. 故 $E\setminus K$ 道路连通.

有限维情形: 结论不成立. 取 $E=\mathbb R^2$, $K=S^1=\left\{\left(u,v\right):u^2+v^2=1\right\}$. $S^1$ 由**定理 5.3 ($\mathbb R^n$ 中的紧集)** 是闭有界集, 故紧. 但 $\mathbb R^2\setminus S^1=\left\{u^2+v^2< 1\right\}\cup\left\{u^2+v^2> 1\right\}$ 是两个非空不相交开集之并, 由**定义 4.18 (连通空间)** 不连通, 因而不道路连通. $\blacksquare$

## 6.6 (等值集皆紧的连续函数必取到极值)

设 $f:\mathbb R^n\to\mathbb R$ 连续, $n\ge 2$, 且对每个 $a\in\mathbb R$, 等值集 $f^{-1}\left(a\right)$ 紧. 证明 $f$ 取得全局极值 (上确界或下确界之一达到). 问 $n=1$ 时结论如何?

### 解答 4.9

取定 $a$ 使 $f^{-1}\left(a\right)\neq\emptyset$ (若非空), 即存在 $x_0$ 使 $f\left(x_0\right)=a$. 由假设 $f^{-1}\left(a\right)$ 紧, 由**定理 5.3 ($\mathbb R^n$ 中的紧集)** 它是闭有界集, 故存在 $R> 0$ 使 $f^{-1}\left(a\right)\subset B\left(0,R\right)$.

球面 $\partial B\left(0,R\right)$ 在 $n\ge 2$ 时连通 (它是 $\mathbb R^n$ 中连通紧集). 由**定义 3.22 (连续映射)**, $f\left(\partial B\left(0,R\right)\right)$ 是 $\mathbb R$ 中不含 $a$ 的连通集; 由**定理 4.2 (连续像连通)** 它连通, 故必全在 $\left(a,\infty\right)$ 或全在 $\left(-\infty,a\right)$ 中. 不妨设 $f> a$ 在 $\partial B\left(0,R\right)$ 上.

反证: 假设 $f$ 既无全局最大值也无全局最小值. 由 $f$ 无最小值, 存在 $x$ 使 $f\left(x\right)< a$. 若 $\left\|x\right\|> R$, 考虑从 $x$ 到球心 $0$ 的径向线段; 由**定理 4.1 (区间连通)** 该线段连通, 其上 $f$ 连续, 在端点 $x$ 处 $f< a$, 在球面处 $f> a$, 由连续函数的介值定理 必有点 $p$ 在该线段上使 $f\left(p\right)=a$ 且 $\left\|p\right\|> R$, 这与 $f^{-1}\left(a\right)\subset B\left(0,R\right)$ 矛盾. 故 $f$ 无最小值只能在 $\left\|x\right\|< R$ 内发生.

同理, 由 $f$ 无最大值, 存在 $y$ 使 $f\left(y\right)> a$. 若 $\left\|y\right\|> R$, 则因外部区域 $\mathbb R^n\setminus \overline B\left(0,R\right)$ 在 $n\ge 2$ 时连通且 $f> a$ 在其边界 $\partial B\left(0,R\right)$ 上, 由**定理 4.2 (连续像连通)** 与连续函数的介值定理 推出外部某处 $f=a$, 矛盾. 故 $f$ 的上无界性也只能在 $\overline B\left(0,R\right)$ 内发生.

于是在紧集 $\overline B\left(0,R\right)$ 上由**定理 5.11 (紧空间上连续函数取最大值)**, $f$ 取得最大值与最小值; 而在 $\mathbb R^n\setminus \overline B\left(0,R\right)$ 上 $f> a$, 故 $f$ 在 $\overline B\left(0,R\right)$ 上取得的最小值就是全局最小值. 故 $f$ 取得全局极值.

$n=1$: 结论不成立. 取 $f\left(x\right)=x$, 则 $f^{-1}\left(a\right)=\left\{a\right\}$ 是单点集紧, 但 $f:\mathbb R\to\mathbb R$ 既无最大值也无最小值. $\blacksquare$

## 6.7 (超平面的余集道路连通当且仅当超平面不闭)

设 $E$ 是赋范线性空间, $H$ 是超平面. 证明 $E\setminus H$ 道路连通当且仅当 $H$ 不是闭集.

注: 题集原文误作 "当且仅当 $H$ 是闭集", 与其附证方向不符 (附证证的正是 $H$ 非闭时道路连通, $H$ 闭时 $E\setminus H$ 分裂为两个凸分支); 此处按数学本意改正.

### 解答 4.10

取线性泛函 $\varphi$ 使 $H=\ker\varphi$ (习题 8.25). 记

$$
H^{-}=\varphi^{-1}\left(\left(-\infty,0\right)\right),\quad H^{+}=\varphi^{-1}\left(\left(0,\infty\right)\right).
$$

由 $\varphi$ 线性, $H^{-}$ 与 $H^{+}$ 都是凸集, 由**定义 4.23 (凸集)** 它们道路连通.

($H$ 闭 $\Rightarrow$ $E\setminus H$ 不道路连通): 由习题 8.25, $H$ 闭时 $\varphi$ 连续. 由**定义 3.22 (连续映射)**, $H^{-}$ 与 $H^{+}$ 都是开集, 且 $E\setminus H=H^{-}\sqcup H^{+}$ 是两个非空不相交开集之并. 由**定义 4.18 (连通空间)**, $E\setminus H$ 不连通, 故不道路连通. 直观地, 若有连续路径 $\gamma:\left[0,1\right]\to E\setminus H$ 从 $H^{-}$ 到 $H^{+}$, 则 $\varphi\circ\gamma$ 是**定理 4.1 (区间连通)** 上的连续实函数, 在两端异号, 由连续函数的介值定理 必取 $0$, 即某 $\gamma\left(t\right)\in H$, 矛盾.

($H$ 不闭 $\Rightarrow$ $E\setminus H$ 道路连通): 由习题 8.25, $H$ 不闭时 $\varphi$ 不连续, 此时 $\overline H=E$ (即 $H$ 在 $E$ 中稠密). 取 $e\in E$ 使 $\varphi\left(e\right)=1$. 则 $\varphi^{-1}\left(1\right)=e+H$ 在 $E$ 中稠密 (平移不改变稠密性). 任取 $-e\in H^{-}$ ($\varphi\left(-e\right)=-1$), 由**定义 3.32 (稠密)** 可取序列 $x_n\in e+H$ 使 $x_n\to -e$, 且不妨设 $x_1=e$.

定义路径 $\gamma:\left[0,1\right]\to E$: 在 $t\in\left[1/\left(k+1\right),1/k\right]$ 上, $\gamma$ 沿直线段从 $x_{k+1}$ 走到 $x_k$, 并令 $\gamma\left(0\right)=-e$. 因 $x_n\to -e$, 该折线在 $0$ 处连续. 对 $t> 0$, $\gamma\left(t\right)\in e+H$, 故 $\varphi\left(\gamma\left(t\right)\right)=1$; 而 $\varphi\left(\gamma\left(0\right)\right)=\varphi\left(-e\right)=-1$. 故 $\gamma$ 全段在 $E\setminus H$ 中, 从 $-e$ 连到 $e$. 由**定义 4.22 (路径连通)**, $H^{-}$ 与 $H^{+}$ 各自道路连通, 任意两点可经 $-e\to e$ 折线互相连通. 故 $E\setminus H$ 道路连通. $\blacksquare$

## 6.8 (不动点性质、截面连通与 $\left[0,1\right]$ 上映射的不动点)

(7.2 连通性)

(1) 设 $\left(E,d\right)$ 是度量空间, 且每个连续映射 $f:E\to E$ 都有**定义 4.17 (不动点)**. 证明 $E$ 连通.

(2) 设 $K\subset\left[0,1\right]^2$ 闭, 且对每个 $x\in\left[0,1\right]$, 截面 $K_x=\left\{y\in\left[0,1\right]:\left(x,y\right)\in K\right\}$ 是非平凡区间. 证明 $K$ 连通. 进一步证明存在 $x\in\left[0,1\right]$ 使 $x\in K_x$.

(3) 设 $f:\left[0,1\right]\to\left[0,1\right]$. (a) 设 $f$ 非递减 (不必连续). 证明 $f$ 有不动点. (b) 设 $f$ 连续 (不必递增). 证明 $f$ 有不动点. (c) 设 $f,g:\left[0,1\right]\to\left[0,1\right]$ 连续且 $f\circ g=g\circ f$. 证明存在 $a\in\left[0,1\right]$ 使 $f\left(a\right)=g\left(a\right)$. (d) 设 $f:\mathbb R\to\mathbb R$ 连续, 且 $f\circ f$ 有不动点. 证明 $f$ 有不动点.

### 解答 4.11

第 (1) 小题: 反证. 若 $E$ 不连通, 由**定义 4.18 (连通空间)**, $E=U\sqcup V$, 其中 $U,V$ 是非空不相交开集. 取 $u\in U$, $v\in V$. 定义 $f:E\to E$ 为 $f\left(U\right)=\left\{v\right\}$, $f\left(V\right)=\left\{u\right\}$. 由**定义 3.22 (连续映射)**, $f$ 连续 (常值映射在开集上连续, 拼接不相交开集). 但 $f$ 无不动点: 对 $x\in U$, $f\left(x\right)=v\notin U$; 对 $x\in V$, $f\left(x\right)=u\notin V$. 矛盾. 故 $E$ 连通.

第 (2) 小题: 证明任一连续 $h:K\to\left\{0,1\right\}$ 常值. 对固定 $x$, $K_x$ 是区间故连通 (由**定理 4.1 (区间连通)** 与**定义 4.18 (连通空间)**), $h|_{K_x}$ 连续像连通, 故常值, 记为 $g\left(x\right)$. 下证 $g$ 局部常值. 若不然, 存在 $x_n\to x$ 但 $g\left(x_n\right)\neq g\left(x\right)$. 取 $y_n\in K_{x_n}$. 由 $K$ 紧 ($\left[0,1\right]^2$ 由**定理 5.3 ($\mathbb R^n$ 中的紧集)** 紧, $K$ 是其闭子集, 由**定理 5.4 (闭子集紧)** 紧), 存在子列 $\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in K$. 由 $h$ 连续,

$$
g\left(x\right)=h\left(x,y\right)=\lim_n h\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)=\lim_n g\left(x_{\varphi\left(n\right)}\right),
$$

而 $\left\{0,1\right\}$ 离散, 故 $g\left(x_{\varphi\left(n\right)}\right)$ 最终等于 $g\left(x\right)$, 矛盾. 故 $g$ 局部常值. 由**定义 4.21 (局部常值函数)** 与 $\left[0,1\right]$ 连通 (**定理 4.1 (区间连通)**), $g$ 常值, 从而 $h$ 常值. 由**定义 4.18 (连通空间)** $K$ 连通.

进一步证明存在 $x$ 使 $x\in K_x$. 定义 $F=\left\{x\in\left[0,1\right]:\inf K_x\ge x\right\}$ 与 $G=\left\{x\in\left[0,1\right]:\sup K_x\le x\right\}$. 二者闭. 若 $F\cap G=\emptyset$, 则 $\left[0,1\right]=F\sqcup\left(\left[0,1\right]\setminus F\right)$, 但 $0\in F$ (因 $\inf K_0\ge 0$) 且 $1\in G$ (因 $\sup K_1\le 1$), 由连通性必有某点 $x\in F\cap G$, 即 $\inf K_x\ge x$ 且 $\sup K_x\le x$, 故 $x\in K_x$.

第 (3) 小题 (a): 令 $A=\left\{x\in\left[0,1\right]:x\le f\left(x\right)\right\}$. $0\in A$. 令 $a=\sup A$. 对 $x\in A$, $x\le f\left(x\right)\le f\left(a\right)$ (由 $f$ 非递减且 $x\le a$), 故 $a\le f\left(a\right)$. 于是 $f\left(a\right)\le f\left(f\left(a\right)\right)$, 即 $f\left(a\right)\in A$, 故 $f\left(a\right)\le a$. 因而 $f\left(a\right)=a$. 由**定义 4.17 (不动点)**, $a$ 是不动点.

(b): 令 $h\left(x\right)=f\left(x\right)-x$. $h\left(0\right)=f\left(0\right)\ge 0$, $h\left(1\right)=f\left(1\right)-1\le 0$. 由**定理 4.1 (区间连通)** 与连续函数的介值定理, 存在 $a$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=a$.

(c): 由 (b), $f$ 有不动点集 $E=\left\{x:f\left(x\right)=x\right\}$ 非空. 对 $x\in E$, $f\left(g\left(x\right)\right)=g\left(f\left(x\right)\right)=g\left(x\right)$, 故 $g\left(x\right)\in E$. 令 $m=\inf E$, $M=\sup E$. $E$ 闭 (由 $f-\operatorname{id}$ 连续), 故 $m,M\in E$. 考虑 $h=f-g$. $h\left(m\right)=f\left(m\right)-g\left(m\right)=m-g\left(m\right)$. 因 $g\left(m\right)\in E$, $g\left(m\right)\ge m$, 故 $h\left(m\right)\le 0$. 同理 $h\left(M\right)=M-g\left(M\right)\ge 0$. 由连续函数的介值定理, 存在 $a\in\left[m,M\right]\subset E$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=g\left(a\right)$.

(d): 设 $f\circ f$ 有不动点 $p$, 即 $f\left(f\left(p\right)\right)=p$. 若 $f\left(p\right)=p$, 则 $p$ 已是 $f$ 的不动点. 若 $f\left(p\right)\neq p$, 令 $h\left(x\right)=f\left(x\right)-x$. 则 $h\left(p\right)=f\left(p\right)-p$ 与 $h\left(f\left(p\right)\right)=f\left(f\left(p\right)\right)-f\left(p\right)=p-f\left(p\right)$ 异号. 由**定理 4.1 (区间连通)** 与连续函数的介值定理, $h$ 在 $p$ 与 $f\left(p\right)$ 之间有零点 $a$, 即 $f\left(a\right)=a$. $\blacksquare$

## 6.9 (差商像的连通性与导函数的值域（2024 卷 A 题一重述）)

考虑一个可微的函数 $f:\mathbb R\to\mathbb R$, 但不假设 $f'$ 是连续的. 取 $\mathbb R$ 上一个非平凡开区间 $I$.

(1) (10 分) 考虑集合 $A=\left\{\left(x,y\right)\in I^2:x< y\right\}$. 证明 $A$ 在最自然的拓扑下是一个连通集合.

(2) (10 分) 考虑在 $A$ 上定义的实函数 $F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}$. 证明 $\Gamma=F\left(A\right)$ 是 $\mathbb R$ 中的一个连通集.

(3) (5 分) 证明 $\Gamma\subset f'\left(I\right)\subset\overline{\Gamma}$ (这里 $f'\left(I\right)$ 指的是 $I$ 被 $f'$ 这个函数映射到的像集).

(4) (5 分) 证明 $f'\left(I\right)$ 是 $\mathbb R$ 中的一个区间.

### 解答 4.12

(1) 任取两点 $P_1=\left(x_1,y_1\right),P_2=\left(x_2,y_2\right)\in A$, 则 $x_1< y_1$ 且 $x_2< y_2$. 对 $t\in\left[0,1\right]$, 线段上的点为 $x\left(t\right)=\left(1-t\right)x_1+tx_2$, $y\left(t\right)=\left(1-t\right)y_1+ty_2$. 于是

$$
y\left(t\right)-x\left(t\right)=\left(1-t\right)\left(y_1-x_1\right)+t\left(y_2-x_2\right)> 0,
$$

故整条线段含于 $A$. 由**定义 4.23 (凸集)**, $A$ 是凸集, 凸集必路径连通 (由**定义 4.22 (路径连通)**), 再由**定理 4.3 (路径连通蕴含连通)** $A$ 连通.

(2) 因 $f$ 可微, $f$ 连续; 在 $A$ 上恒有 $x-y\neq0$, 故 $F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}$ 是 $A$ 上的连续函数. 由第 (1) 小题 $A$ 连通, 由**定理 4.2 (连续像连通)**, $\Gamma=F\left(A\right)$ 连通.

(3) 先证 $\Gamma\subset f'\left(I\right)$. 任取 $\left(x,y\right)\in A$, $x< y$. 由微分中值定理, 存在 $c\in\left(x,y\right)\subset I$ 使 $\frac{f\left(x\right)-f\left(y\right)}{x-y}=f'\left(c\right)$. 故 $F\left(x,y\right)\in f'\left(I\right)$, 即 $\Gamma\subset f'\left(I\right)$.

再证 $f'\left(I\right)\subset\overline{\Gamma}$. 任取 $t\in I$ (因 $I$ 为开区间, $t$ 非端点). 取充分小的 $h$ 使 $t+h\in I$, 则 $q_h=\frac{f\left(t+h\right)-f\left(t\right)}{h}\in\Gamma$. 由导数定义 $q_h\to f'\left(t\right)$ ($h\to0$). 故 $f'\left(t\right)$ 是 $\Gamma$ 的极限点, 由**定理 3.5 (闭包与极限点)** 它含于 $\overline{\Gamma}$ (由**定义 3.26 (闭包)**, $\overline{\Gamma}$ 是含 $\Gamma$ 的最小闭集). 即 $f'\left(I\right)\subset\overline{\Gamma}$.

(4) 由第 (2) 小题, $\Gamma$ 是 $\mathbb R$ 中的连通集, 而 $\mathbb R$ 中连通集必为区间 (若 $a< c< b$ 且 $a,b\in S$, $c\notin S$, 则 $S=\left(S\cap\left(-\infty,c\right)\right)\cup\left(S\cap\left(c,\infty\right)\right)$ 是一个分离, 矛盾). 故 $\Gamma$ 是区间. 由第 (3) 小题, $\Gamma\subset f'\left(I\right)\subset\overline{\Gamma}$. 一个区间与其闭包之间的差别至多是它的两个端点; 在区间上任意添去两端点的一个子集仍得区间. 因此夹在区间 $\Gamma$ 与 $\overline{\Gamma}$ 之间的 $f'\left(I\right)$ 仍是区间. $\blacksquare$
