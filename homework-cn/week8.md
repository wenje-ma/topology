# week8

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

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.24 (极限点)**
> 
> 称 $x$ 是 $A$ 的极限点, 若 $x$ 的每个邻域都含有 $A$ 中异于 $x$ 的点. (教材 $\S3$, p18)

> **定义 3.26 (闭包)**
> 
> 集合 $A\subset{X}$ 的闭包 $\overline{A}$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **定义 3.28 (扎里斯基拓扑)**
> 
> 设 $K$ 为域, $\mathbb{A}^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in{I}}$ 的公共零点集 $\left\{x\in\mathbb{A}^n\left(K\right):\forall{i}\in{I},P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset{X}$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

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

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.7))

> **定理 5.7 (有限乘积紧)**
> 
> 有限个紧空间的乘积紧. (教材 $\S5$, 定理 5.7)

> **定理 5.9 (吉洪诺夫定理)**
> 
> 任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.10 (有限交判据)**
> 
> $X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定理 5.11 (紧空间上连续函数取最大值)**
> 
> 紧致空间 $X$ 上的连续函数 $f:X\to\mathbb{R}$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 5.16 (紧致空间)**
> 
> 称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17 (有限交性质)**
> 
> 闭集族 $\mathcal{F}$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

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

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.42 (完全有界)**
> 
> 对每个 $r>0$, $X$ 可被有限个半径 $r$ 的球覆盖. (教材 $\S6$)

> **定义 6.49 (等距映射)**
> 
> 满足 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)$ 的映射 $f:X\to{Y}$. (题集 §3.4)

> **说明 6.50 (度量空间是豪斯多夫的)**
> 
> 度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

> **说明 6.51 (度量连续与序列)**
> 
> 度量空间之间的映射 $f:X\to{Y}$ 连续, 当且仅当 $x_i\to{x}$ 蕴含 $f\left(x_i\right)\to{f}\left(x\right)$. (教材 $\S6$, p34)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; "拓扑学"(原书第2版) $\S29$)

> **定义 7.5 (单点紧化)**
> 
> 亚历山德罗夫紧化 $\overline{X}=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset{X}$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

> **定义 11.1 (商拓扑)**
> 
> 满射 $\pi:X\to{Y}$ 下, $U\subset{Y}$ 开当且仅当 $\pi^{-1}\left(U\right)\subset{X}$ 开. (教材 §11, p61; "拓扑学"(原书第2版) §22, p105; "基础拓扑学"(修订版) 第4章 4.2, p55)

> **定义 11.6 (锥)**
> 
> 从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in{X}$, $0\le{t}<1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (教材 $\S11$, p63; 题集 $\S5$ Q9; "基础拓扑学"(修订版) 第4章)

> **定义 11.12 (塌缩商)**
> 
> $X/\left\langle{A}\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 §5 Q11; "基础拓扑学"(修订版) 第4章, p57)

> **定义 11.17 ($k$-染色与 $k$-可染色)**
> 
> $f:V\to\left\{1,\dots,k\right\}$ 使相邻点异色; 存在则称 $k$-可染色. (题集 $\S3.3$)

## 8.1 (紧豪斯多夫空间中锥与塌缩商的单点紧化描述)

设 $X$ 是紧豪斯多夫空间. 证明锥空间 $CX$ 同胚于 $X\times\left[0,1\right)$ 的单点紧化. 若 $A\subset{X}$ 闭, 证明 $X/\left\langle{A}\right\rangle$ 同胚于 $X\setminus{A}$ 的单点紧化.

### 解答 8.1

第一问: 由**定义 11.6 (锥)**, $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$, 商映射 $\pi:X\times\left[0,1\right]\to{C}X$ 把 $X\times\left\{1\right\}$ 捏成一点, 在 $X\times\left[0,1\right)$ 上单射 (划分 (b) 为单点类). 令 $Y=X\times\left[0,1\right)$. $Y$ 豪斯多夫: 由**定理 3.6 (豪斯多夫的遗传性)**, $X$ 豪斯多夫 (题设), $\left[0,1\right)$ 是度量空间 $\mathbb{R}$ 的子空间故豪斯多夫 (由**说明 6.50 (度量空间是豪斯多夫的)** 与**定理 3.6 (豪斯多夫的遗传性)**), 乘积仍豪斯多夫. $Y$ 局部紧 (按**定义 7.4 (局部紧空间)** 的等价表述): 对 $\left(x,t\right)\in{Y}$, 取 $t'$ 使 $t<{}t'<1$; $\left[0,t'\right]\subset\mathbb{R}$ 闭且有界, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 紧, $X$ 紧 (题设), 由**定理 5.7 (有限乘积紧)** $X\times\left[0,t'\right]$ 紧; 它含 $\left(x,t\right)$ 的开邻域 $X\times\left(0,t'\right)$, 故是 $\left(x,t\right)$ 的紧邻域. 由**定义 7.5 (单点紧化)**, $Y^*=Y\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(Y\setminus{K}\right)\cup\left\{\infty\right\}$, $K\subset{Y}$ 紧.

构造双射 $\psi:CX\to{Y}^*$: 令 $\psi\left(\left[\left(x,t\right)\right]\right)=\left(x,t\right)$ 对 $t<1$, $\psi\left(\left[\left(x,1\right)\right]\right)=\infty$. 由**定义 11.6 (锥)** 的划分 (a)(b), 每个类恰为 $X\times\left\{1\right\}$ 或单点 $\left\{\left(x,t\right)\right\}$, 故 $\psi$ 是双射.

$\psi$ 连续: 由**定义 11.1 (商拓扑)**, 只需证对 $Y^*$ 的每个开集 $W$, $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)$ 在 $X\times\left[0,1\right]$ 中开. 若 $\infty\notin{W}$, 则 $W$ 是 $Y$ 中开集; $Y$ 是 $X\times\left[0,1\right]$ 的开子集 (其补 $X\times\left\{1\right\}$ 闭), 故 $W$ 在 $X\times\left[0,1\right]$ 中开, 且 $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)=W$. 若 $\infty\in{W}$, 则 $W=\left(Y\setminus{K}\right)\cup\left\{\infty\right\}$ 其中 $K\subset{Y}$ 紧 (由**定义 7.5 (单点紧化)**); $X\times\left[0,1\right]$ 豪斯多夫 (由**定理 3.6 (豪斯多夫的遗传性)**), 由**定理 5.5 (豪斯多夫中紧集闭)** $K$ 闭, 故 $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)=\left(X\times\left[0,1\right]\right)\setminus{K}$ 开. 故 $\psi$ 连续.

$CX$ 紧: $X\times\left[0,1\right]$ 是紧空间之积 ($X$ 紧, $\left[0,1\right]$ 闭有界由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 紧), 由**定理 5.7 (有限乘积紧)** 紧; 商映射 $\pi$ 连续 (由**定义 11.1 (商拓扑)**), 由**定理 5.1 (紧空间连续像紧)** $CX$ 紧.

$Y^*$ 豪斯多夫: 若 $\left(x,t\right)\neq\left(y,s\right)$ 皆非 $\infty$, 由 $Y$ 豪斯多夫取 $Y$ 中不相交开邻域 $U,V$; $U,V$ 不含 $\infty$, 由**定义 7.5 (单点紧化)** 它们在 $Y^*$ 中仍开. 对 $\infty$ 与 $\left(x,t\right)$: 取 $t'$ 使 $t<{}t'<1$, 令 $K=X\times\left[0,t'\right]$ (紧, 如上); 则 $U=X\times\left(0,t'\right)$ 是 $\left(x,t\right)$ 的开邻域, $\left(Y\setminus{K}\right)\cup\left\{\infty\right\}=X\times\left(t',1\right)\cup\left\{\infty\right\}$ 是 $\infty$ 的邻域 (由**定义 7.5 (单点紧化)**), 且 $U\cap\left(Y\setminus{K}\right)=\emptyset$. 故 $Y^*$ 豪斯多夫.

由**定理 5.6 (紧豪斯多夫间的连续双射)**, $\psi$ 是同胚. 第一问得证.

第二问: 由**定义 11.12 (塌缩商)**, $X/\left\langle{A}\right\rangle$ 把闭集 $A$ 整捏成一点 $\left\langle{A}\right\rangle$, 商映射 $\pi$ 在 $Z=X\setminus{A}$ 上单射; 由**定义 11.1 (商拓扑)**, $\pi$ 连续. $Z$ 豪斯多夫: $X$ 豪斯多夫 (题设), 由**定理 3.6 (豪斯多夫的遗传性)** 子空间仍豪斯多夫. $Z$ 局部紧 (按**定义 7.4 (局部紧空间)** 的等价表述): 对 $x\in{Z}$, 由**定义 3.10 (豪斯多夫空间)**, 对每个 $a\in{A}$ 有不相交开集 $U_a\ni{x}$, $V_a\ni{a}$; $A$ 是紧空间 $X$ 的闭子集, 由**定理 5.4 (闭子集紧)** 紧, 故 $A\subset\bigcup_{i=1}^{m}V_{a_i}$ 对某个有限子族成立; 令 $U=\bigcap_{i=1}^{m}U_{a_i}$, 由**定义 3.18 (拓扑空间)** $U$ 是含 $x$ 的开集且 $U\cap{A}=\emptyset$. 由**定义 3.26 (闭包)**, $\overline{U}\subset{X}\setminus\bigcup_{i=1}^{m}V_{a_i}\subset{Z}$ ($X\setminus\bigcup_iV_{a_i}$ 闭且含 $U$); $\overline{U}$ 是紧空间 $X$ 的闭子集, 由**定理 5.4 (闭子集紧)** 紧, 且是 $x$ 的紧邻域 (含 $x$ 的开邻域 $U$, 而 $U$ 在 $Z$ 中开). 故 $Z$ 局部紧.

构造双射 $\phi:X/\left\langle{A}\right\rangle\to{Z}^*$: 令 $\phi\left(\left[x\right]\right)=x$ 对 $x\in{Z}$, $\phi\left(\left\langle{A}\right\rangle\right)=\infty$. 由**定义 11.12 (塌缩商)** 的划分 ($A$ 整捏为一点, 其余单点), $\phi$ 是双射.

$\phi$ 连续: 对 $Z^*$ 的开集 $W$, 若 $\infty\notin{W}$, 则 $W$ 在 $Z$ 中开; $Z=X\setminus{A}$ 是 $X$ 的开子集 ($A$ 闭, 由**定义 3.21 (闭集)**), 故 $W$ 在 $X$ 中开, 且 $\pi^{-1}\left(\phi^{-1}\left(W\right)\right)=W$ 开. 若 $\infty\in{W}$, 则 $W=\left(Z\setminus{K}\right)\cup\left\{\infty\right\}$ 其中 $K\subset{Z}$ 紧 (由**定义 7.5 (单点紧化)**); $X$ 豪斯多夫, 由**定理 5.5 (豪斯多夫中紧集闭)** $K$ 在 $X$ 中闭, 故 $\pi^{-1}\left(\phi^{-1}\left(W\right)\right)=X\setminus{K}$ 开. 由**定义 11.1 (商拓扑)**, $\phi$ 连续.

$X/\left\langle{A}\right\rangle$ 紧: $\pi$ 连续, $X$ 紧, 由**定理 5.1 (紧空间连续像紧)**. $Z^*$ 豪斯多夫: 两点皆非 $\infty$ 时由 $Z$ 豪斯多夫及**定义 7.5 (单点紧化)** (不含 $\infty$ 的开集在 $Z^*$ 中开); 对 $\infty$ 与 $x\in{Z}$, 取上面的开集 $U$ 与紧集 $\overline{U}$, 则 $U$ 与 $\left(Z\setminus\overline{U}\right)\cup\left\{\infty\right\}$ 不相交 ($U\subset\overline{U}$), 后者是 $\infty$ 的邻域 (由**定义 7.5 (单点紧化)**). 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $\phi$ 是同胚. $\blacksquare$

## 8.2 (扎里斯基拓扑下 $\left(0,1\right)$ 紧但不闭)

(扎里斯基紧不蕴含扎里斯基闭) 在 $\mathbb{A}^1\left(\mathbb{R}\right)=\mathbb{R}$ 上配**定义 3.28 (扎里斯基拓扑)**, 即余有限拓扑. 证明子集 $\left(0,1\right)$ 在扎里斯基拓扑下紧但不闭.

### 解答 8.2

扎里斯基拓扑下, 由**定义 3.28 (扎里斯基拓扑)**, 闭集为有限集或全空间 ($n=1$ 时多项式零点集即有限集或全空间); 由**定义 3.21 (闭集)**, 开集为余有限集或空集.

紧: 任取 $\left(0,1\right)$ 的开覆盖 $\left\{U_i\right\}$. 取其中一个非空开集 $U_0$; 由余有限性, $\mathbb{R}\setminus{U}_0$ 有限, 故 $\left(0,1\right)\setminus{U}_0$ 至多有限个点, 每个点再选一个覆盖元覆盖. 即得有限子覆盖. 由**定义 5.16 (紧致空间)**, $\left(0,1\right)$ 紧.

不闭: $\mathbb{R}\setminus\left(0,1\right)=\left(-\infty,0\right]\cup\left[1,\infty\right)$ 是无限集, 不是有限集, 故不是扎里斯基闭集; 因而由**定义 3.21 (闭集)** 它的补集 $\left(0,1\right)$ 不是扎里斯基开集的补, 即 $\left(0,1\right)$ 不闭. 故紧不蕴含闭. $\blacksquare$

## 8.3 ($\mathbb{R}$ 的单点紧化同胚于 $S^1$)

(单点紧化) 回顾**定义 7.5 (单点紧化)**. 证明 $\mathbb{R}$ 的单点紧化同胚于单位圆 $S^1$.

### 解答 8.3

由**定义 7.5 (单点紧化)**, $\mathbb{R}^*=\mathbb{R}\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(\mathbb{R}\setminus{K}\right)\cup\left\{\infty\right\}$, 其中 $K\subset\mathbb{R}$ 紧, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 即闭有界集.

先证 $\mathbb{R}^*$ 紧: 任取开覆盖 $\mathcal{U}$, 取 $U_\infty\in\mathcal{U}$ 含 $\infty$. 由**定义 7.5 (单点紧化)**, $U_\infty\supset\left(\mathbb{R}\setminus{K}'\right)\cup\left\{\infty\right\}$ 对某紧集 $K'$; 于是 $K=\mathbb{R}\setminus{U}_\infty\subset{K}'$ 且 $K$ 闭 ($U_\infty$ 开), 由**定理 5.4 (闭子集紧)** $K$ 紧. 同**习题 7.7**的论证, $K$ 被 $\mathcal{U}\setminus\left\{U_\infty\right\}$ 中有限个集合覆盖, 故 $\mathcal{U}$ 有有限子覆盖; 由**定义 5.16 (紧致空间)**, $\mathbb{R}^*$ 紧.

球极投影 $\sigma:\mathbb{R}\to{S}^1\setminus\left\{N\right\}$ ($N=\left(0,1\right)$ 为北极) 由公式 $\sigma\left(x\right)=\left(\frac{2x}{x^2+1},\frac{x^2-1}{x^2+1}\right)$ 给出, 是连续双射, 其逆 $\left(X,Y\right)\mapsto\frac{X}{1-Y}$ 也连续, 故 $\sigma$ 是同胚 (双向连续的双射即同胚).

$S^1$ 是 $\mathbb{R}^2$ 的闭有界子集, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 紧; $\mathbb{R}^2$ 是度量空间 (由**定义 6.35 (度量空间)**), 由**说明 6.50 (度量空间是豪斯多夫的)** 豪斯多夫, 故 $S^1$ 作为子空间由**定理 3.6 (豪斯多夫的遗传性)** 豪斯多夫.

定义 $F:\mathbb{R}^*\to{S}^1$: $F\left(x\right)=\sigma\left(x\right)$ 对 $x\in\mathbb{R}$, $F\left(\infty\right)=N$. $F$ 是双射 ($\sigma$ 双射到 $S^1\setminus\left\{N\right\}$, $\infty\leftrightarrow{N}$). $F$ 连续: 对不含 $N$ 的开集 $W\subset{S}^1$, $F^{-1}\left(W\right)=\sigma^{-1}\left(W\right)$ 是 $\mathbb{R}$ 中开集 ($\sigma$ 同胚); $\mathbb{R}$ 是 $\mathbb{R}^*$ 的开子集 (由**定义 7.5 (单点紧化)**: $\mathbb{R}\cap\mathbb{R}=\mathbb{R}$ 开且 $\infty\notin\mathbb{R}$), 故 $F^{-1}\left(W\right)$ 在 $\mathbb{R}^*$ 中开. 对含 $N$ 的开集 $W\subset{S}^1$, $S^1\setminus{W}$ 闭于紧 $S^1$, 由**定理 5.5 (豪斯多夫中紧集闭)** 紧, 故 $K=\sigma^{-1}\left(S^1\setminus{W}\right)$ 是 $\mathbb{R}$ 中紧集 (由**定理 5.1 (紧空间连续像紧)**, $\sigma$ 连续); 于是 $F^{-1}\left(W\right)=\left(\mathbb{R}\setminus{K}\right)\cup\left\{\infty\right\}$, 它是 $\infty$ 的邻域 (由**定义 7.5 (单点紧化)**), 且在 $\mathbb{R}^*$ 中开: 其与 $\mathbb{R}$ 之交 $\mathbb{R}\setminus{K}$ 开 ($K$ 紧, 由**定理 5.5 (豪斯多夫中紧集闭)** 闭), 其补 $K$ 紧. 故 $F$ 连续.

由**定理 5.6 (紧豪斯多夫间的连续双射)**, $F$ 是同胚, 即 $\mathbb{R}$ 的单点紧化同胚于 $S^1$. $\blacksquare$

## 8.4 (每无穷子集皆有极限点的度量空间必紧 (2024 卷 C 题二))

(2024 年卷 C 题目二, 40 分). 考虑一个度量空间 $X$, 使得其中任意无穷子集都有一个极限点.

(1) (10 分) 证明对于任意的 $\delta>0$, $X$ 能被有限个半径为 $\delta$ 的小球覆盖.

(2) (10 分) 证明 $X$ 是可分度量空间, 即 $X$ 中有一个可数稠密子集.

(3) (10 分) 证明 $X$ 有一个可数的基, 即存在可数个 $X$ 中的开集 $V_\alpha$, 使得任意 $X$ 的开集都是一些 $V_\alpha$ 之并.

(4) (10 分) 证明 $X$ 是一个紧致空间, 即任意 $X$ 的开覆盖都有一个有限子覆盖.

(5) (附加题, 10 分) 证明一个紧致度量空间 $K$ 一定是可分的.

### 解答 8.4

(1) 固定 $\delta>0$. 依次选 $x_1,x_2,\dots$ 使 $d\left(x_i,x_j\right)\ge\delta$ ($i\neq{j}$). 若此过程无穷, $\left\{x_i\right\}$ 是无穷集, 由题设有极限点 $x$. 由**定义 3.24 (极限点)**, 开球 $B\left(x,\frac\delta2\right)$ 含 $S\setminus\left\{x\right\}$ 的无穷多点: 若仅含有限个, 取 $r$ 小于这些点到 $x$ 的距离, 则 $B\left(x,r\right)$ 与 $S\setminus\left\{x\right\}$ 无交, 与极限点定义矛盾. 取其中两个不同点 $x_i,x_j$, 由三角不等式 (**定义 6.35 (度量空间)**) $d\left(x_i,x_j\right)\le{d}\left(x_i,x\right)+d\left(x,x_j\right)<\delta$, 与 $d\left(x_i,x_j\right)\ge\delta$ 矛盾. 故过程有限停止, 得 $x_1,\dots,x_m$, 且 $\bigcup_{i=1}^mB\left(x_i,\delta\right)=X$ (否则可再选一点), 即有限 $\delta$-覆盖. 由**定义 6.42 (完全有界)**, $X$ 完全有界.

(2) 对每个 $n$, 由第 (1) 小题取半径 $1/n$ 的有限覆盖球心集 $C_n$. 令 $C=\bigcup_{n\ge1}C_n$, 它可数 (可数个有限集之并). 任取 $x$ 与 $r>0$, 取 $n$ 使 $1/n<{}r$, 存在 $c\in{C}_n$ 使 $d\left(x,c\right)<1/n<{}r$, 即 $c\in{B}\left(x,r\right)$. 故 $x$ 的每个开球邻域都与 $C$ 相交; 开球构成度量拓扑的基 (由**定义 6.36 (开球)**), 故 $x$ 的每个邻域都与 $C$ 相交, 由**定义 3.24 (极限点)** 与**定理 3.5 (闭包与极限点)** $x\in\overline{C}$. 因 $x$ 任意, $\overline{C}=X$, 由**定义 3.32 (稠密)** $C$ 稠密. 由**定义 3.9 (可分)** $X$ 可分.

(3) 令 $\mathcal{B}=\left\{B\left(c,q\right):c\in{C},q\in\mathbb{Q}_{>0}\right\}$. 它可数 ($C$ 可数, $\mathbb{Q}_{>0}$ 可数). 验证它是基: 任取开集 $U$ 与 $x\in{U}$, 由**定义 6.36 (开球)** 存在 $r>0$ 使 $B\left(x,r\right)\subset{U}$. 由 $C$ 稠密取 $c\in{C}$ 使 $d\left(x,c\right)<{}r/3$ (由**定义 3.32 (稠密)** 与**定义 3.26 (闭包)**), 再取有理数 $q$ 使 $d\left(x,c\right)<{}q<{}r/3$. 则 $x\in{B}\left(c,q\right)$ (因 $d\left(x,c\right)<{}q$), 且 $B\left(c,q\right)\subset{B}\left(x,r\right)\subset{U}$ (对 $z\in{B}\left(c,q\right)$, 由三角不等式 (**定义 6.35 (度量空间)**) $d\left(x,z\right)\le{d}\left(x,c\right)+d\left(c,z\right)<{}r/3+q<{}r$). 故 $U$ 是 $\mathcal{B}$ 中元素之并; 由**定义 3.15 (拓扑基)**, $\mathcal{B}$ 是可数基.

(4) 设 $\left\{U_\alpha\right\}$ 是任意开覆盖. 由第 (3) 小题的可数基 $\mathcal{B}=\left\{V_\beta\right\}$, 每个开集是基元素之并 (**定义 3.15 (拓扑基)**); 对每个基元素 $V_\beta$, 若存在覆盖元 $U\supset{V}_\beta$ 则取定其一记为 $G_\beta$, 则 $\left\{G_\beta\right\}$ 可数且仍覆盖 $X$ (每个 $x\in{X}$ 在某 $U$ 中, $x$ 又在其某基元素 $V_\beta\subset{U}$ 中, 该 $V_\beta$ 被 $G_\beta$ 覆盖). 将 $\left\{G_\beta\right\}$ 编号为 $G_1,G_2,\dots$. 反证无有限子覆盖: 取 $x_n\notin{G}_1\cup\dots\cup{G}_n$. 集合 $\left\{x_n\right\}$ 无穷 (各 $x_n$ 互异), 由题设有极限点 $x$. 因 $\left\{G_n\right\}$ 覆盖 $X$, 存在 $N$ 使 $x\in{G}_N$. 由**定义 6.36 (开球)**, $G_N$ 含开球 $B\left(x,r\right)$, 由第 (1) 小题的论证 $B\left(x,r\right)$ 含 $S\setminus\left\{x\right\}$ 的无穷多点, 故 $G_N$ 含无穷多个 $x_n$. 但对 $n\ge{N}$, $x_n\notin{G}_1\cup\dots\cup{G}_n\supset{G}_N$, 故 $G_N$ 至多含 $x_1,\dots,x_{N-1}$ 有限个, 矛盾. 故存在有限子覆盖, 由**定义 5.16 (紧致空间)** $X$ 紧.

(5) 设 $K$ 紧. 对每个 $n$, 由**定义 5.16 (紧致空间)**, 开覆盖 $\left\{B\left(x,1/n\right):x\in{K}\right\}$ 有有限子覆盖, 取其球心集 $C_n$. 令 $C=\bigcup_nC_n$, 可数. 任取 $x\in{K}$ 与 $r>0$, 取 $n$ 使 $1/n<{}r$, 有限覆盖给出 $c\in{C}_n$ 使 $d\left(x,c\right)<1/n<{}r$, 故 $x$ 的每个开球邻域都与 $C$ 相交; 由**定义 3.32 (稠密)** 与**定理 3.5 (闭包与极限点)** $C$ 在 $K$ 中稠密. 由**定义 3.9 (可分)**, $K$ 可分. $\blacksquare$

## 8.5 (单边染色集的闭性)

若 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 证明 $X_F$ 闭. ($X_F$ 见文首记号)

### 解答 8.5

一条边 $\left(x,y\right)$ 的染色条件即 $f\left(x\right)\neq{f}\left(y\right)$. 故

$$
X_F=\bigcup_{i\neq{j}}\left\{f:f\left(x\right)=i,f\left(y\right)=j\right\}.
$$

每个柱集 $C_{ij}=\left\{f:f\left(x\right)=i,f\left(y\right)=j\right\}$ 是坐标投影 $\pi_x:X\to\left\{1,\dots,k\right\}$ 与 $\pi_y$ 的纤维之交. 由**定义 3.11 (乘积拓扑)**, 坐标投影连续; 离散空间 $\left\{1,\dots,k\right\}$ 中单点 $\left\{i\right\}$ 闭, 由**定义 3.22 (连续映射)** 其原像 $\pi_x^{-1}\left(\left\{i\right\}\right)$ 闭. 故 $C_{ij}$ 闭. 而 $X_F$ 是有限个 $C_{ij}$ ($i\neq{j}$) 之并, 闭集的有限并仍闭. 故 $X_F$ 闭. $\blacksquare$

## 8.6 (任意边集的染色集闭)

证明: 对任意 $F\subset{E}$, $X_F$ 闭.

### 解答 8.6

一个映射是 $\left(V,F\right)$ 的染色, 当且仅当它对每条边 $e\in{F}$ 都合法. 故

$$
X_F=\bigcap_{e\in{F}}X_{\left\{e\right\}}.
$$

由**习题 8.5**, 每个 $X_{\left\{e\right\}}$ 闭; 由**定义 3.21 (闭集)**, 闭集的任意交仍闭 (补集为开集的任意并). 故 $X_F$ 闭. $\blacksquare$

## 8.7 (有限子图可染蕴含染色集族的有限交非空)

现设图 $G$ 的任意有限子图都可 $k$-染色. 证明 $\mathcal{F}$ 中任意有限个集合之交非空. ($\mathcal{F}$ 见文首记号)

### 解答 8.7

设 $F_1,\dots,F_n\subset{E}$ 有限. 由染色条件逐条叠加,

$$
\bigcap_{i=1}^{n}X_{F_i}=X_{\bigcup_{i=1}^{n}F_i}.
$$

边集 $\bigcup_{i=1}^{n}F_i$ 有限, 由假设对应的子图可 $k$-染色, 即由**定义 11.17 ($k$-染色与 $k$-可染色)**, $X_{\bigcup_iF_i}\neq\emptyset$. 故有限交非空. $\blacksquare$

## 8.8 (用 $X$ 的紧致性得全族交非空)

用 $X$ 的紧致性证明: $\mathcal{F}$ 中所有集合之交非空.

### 解答 8.8

由文首记号, $X=\prod_{v\in{V}}\left\{1,\dots,k\right\}$; 每个因子 $\left\{1,\dots,k\right\}$ 为有限离散空间故紧 (任意开覆盖每点选一覆盖元即有限子覆盖, 由**定义 5.16 (紧致空间)**), 由**定理 5.9 (吉洪诺夫定理)**, $X$ 在乘积拓扑下紧. 由**习题 8.6**, 每个 $X_F$ 是紧空间 $X$ 中的闭集. 由**习题 8.7**, $\mathcal{F}=\left\{X_F:F\subset{E}\text{~有限}\right\}$ 具有限交性质 (由**定义 5.17 (有限交性质)**). 由**定理 5.10 (有限交判据)**,

$$
\bigcap_{F\subset{E}\text{~有限}}X_F\neq\emptyset.
$$

$\blacksquare$

## 8.9 (德布鲁因–埃尔德什定理)

证明德布鲁因-埃尔德什定理: 若图 $G$ 的任意有限子图都可 $k$-染色, 则 $G$ 可 $k$-染色. 即使 $G$ 有不可数个顶点也成立.

### 解答 8.9

由**习题 8.8**, 可取

$$
f\in\bigcap_{F\subset{E}\text{~有限}}X_F.
$$

对任意边 $e=\left(x,y\right)\in{E}$, 取 $F=\left\{e\right\}$; 因 $f\in{X}_{\left\{e\right\}}$, 由**定义 11.17 ($k$-染色与 $k$-可染色)**, $f\left(x\right)\neq{f}\left(y\right)$. 故 $f$ 是全图 $G=\left(V,E\right)$ 的合法 $k$-染色. $\blacksquare$

## 8.10 (紧度量空间中相邻距离趋于零的序列: 聚点集紧且连通)

设 $X$ 是紧度量空间, $\left\{u_n\right\}_{n\ge0}$ 是 $X$ 中序列且 $d\left(u_n,u_{n+1}\right)\to0$. 证明 $\left\{u_n\right\}$ 的聚点集紧致, 并且连通.

### 解答 8.10

令

$$
L=\bigcap_{N\ge1}\overline{\left\{u_n:n\ge{N}\right\}}.
$$

$L$ 正是序列 $\left\{u_n\right\}$ 的聚点集. 每个闭包是闭集, 故 $L$ 是紧空间 $X$ 的闭子集, 由**定理 5.4 (闭子集紧)**, $L$ 紧致.

下证 $L$ 连通. 反证, 设 $L=C\cup{D}$, $C,D$ 为 $L$ 中非空不相交闭集. 因 $L$ 紧, $C,D$ 紧; 函数 $C\times{D}\to\mathbb{R}$, $\left(c,d\right)\mapsto{d}\left(c,d\right)$ 连续且 $C\times{D}$ 紧, 由**定理 5.11 (紧空间上连续函数取最大值)** (及最小值情形) 其最小值 $\delta=d\left(C,D\right)$ 可达; 又 $C\cap{D}=\emptyset$, 故 $\delta>0$. 由 $d\left(u_n,u_{n+1}\right)\to0$, 存在 $N$ 使 $n\ge{N}$ 时 $d\left(u_n,u_{n+1}\right)<\delta/3$. 因 $C,D\subset{L}$, 对任意 $c\in{C}$ 与 $d\in{D}$, 由 $L=\cap_N\overline{\left\{u_n:n\ge{N}\right\}}$ 的定义, $c$ 的每个邻域与 $\left\{u_n:n\ge{N}\right\}$ 相交, 故存在任意大的 $n,m\ge{N}$ 使 $d\left(u_n,C\right)<\delta/6$, $d\left(u_m,D\right)<\delta/6$. 沿链 $u_n,u_{n+1},\dots,u_m$, 函数 $h\left(t\right)=d\left(u_t,C\right)$ 从 $<\delta/6$ 变到 $\ge\delta-\delta/6=5\delta/6$ (后一步用三角不等式: $d\left(u_m,C\right)\ge{d}\left(C,D\right)-d\left(u_m,D\right)>\delta-\delta/6$), 且每步变化 $<\delta/3$, 故存在 $p$ 使

$$
\delta/6\le{h}\left(p\right)\le\delta/2.
$$

对任意大的这样的 $n,m$ 重复选取 $p$, 并由 $X$ 紧致经**定理 6.1 (紧 $=$ 序列紧)** 提取收敛子列, 其极限 $z$ 满足 $d\left(z,C\right)\ge\delta/6$ 且 $d\left(z,D\right)\ge\delta/2$, 故 $z$ 是聚点但 $z\notin{C}\cup{D}=L$, 矛盾. 由**定义 4.18 (连通空间)**, $L$ 连通. $\blacksquare$

## 8.11 (紧度量空间上的等距自映射是满射同胚)

设 $\left(X,d\right)$ 是度量空间, $f:X\to{X}$ 是**定义 6.49 (等距映射)**. 证明: 若 $X$ 紧致, 则 $f$ 双射且是同胚.

### 解答 8.11

$f$ 单: 由**定义 6.49 (等距映射)**, $f\left(x\right)=f\left(y\right)$ 蕴含 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)=0$, 故 $x=y$.

证 $f$ 满. 反证, 取 $a\notin{f}\left(X\right)$. $f$ 连续 (由等距映射蕴含利普希茨连续), $f\left(X\right)$ 是紧空间 $X$ 的连续像, 由**定理 5.1 (紧空间连续像紧)**, $f\left(X\right)$ 紧致. 度量空间是**说明 6.50 (度量空间是豪斯多夫的)**, 由**定理 5.5 (豪斯多夫中紧集闭)**, $f\left(X\right)$ 闭. 故 $\varepsilon=d\left(a,f\left(X\right)\right)>0$. 对 $n\neq{m}$, 由**定义 6.49 (等距映射)** 及 $f$ 的迭代仍是等距,

$$
d\left(f^n\left(a\right),f^m\left(a\right)\right)=d\left(a,f^{\left|n-m\right|}\left(a\right)\right)\ge\varepsilon.
$$

但 $\left\{f^n\left(a\right)\right\}$ 是紧空间 $X$ 中的序列, 由**定理 6.1 (紧 $=$ 序列紧)** 有收敛子列, 它必是**定义 6.37 (柯西列)**, 与两两距离 $\ge\varepsilon$ 矛盾. 故 $f$ 满.

$f$ 连续 (由等距映射蕴含利普希茨连续), $X$ 紧致故为紧豪斯多夫空间, 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $f$ 是同胚. $\blacksquare$

## 8.12 (紧集上的膨胀映射是等距且双射, 满 $1$-利普希茨映射是等距)

(紧集的膨胀) 设 $X$ 是某赋范线性空间的紧子空间. 设 $f:X\to{X}$ 满足对一切 $x,y\in{X}$, $\left|f\left(y\right)-f\left(x\right)\right|\ge\left|y-x\right|$. 证明 $f$ 是**定义 6.49 (等距映射)** 且双射. 再证明满的 $1$-利普希茨函数 $g:X\to{X}$ 是等距.

### 解答 8.12

固定 $a,b\in{X}$, 记 $c_n=\left|f^n\left(a\right)-f^n\left(b\right)\right|$. 由膨胀条件应用于 $\left(f^{n-1}\left(a\right),f^{n-1}\left(b\right)\right)$, $c_{n+1}\ge{c}_n$, 又 $c_n\le\operatorname{diam}\left(X\right)$, 故 $c_n\uparrow{L}$. 由**定理 6.1 (紧 $=$ 序列紧)**, $X\times{X}$ 紧, $\left(f^n\left(a\right),f^n\left(b\right)\right)$ 有子列 $\left(f^{n_j}\left(a\right),f^{n_j}\left(b\right)\right)\to\left(u,v\right)$, 于是 $\left|u-v\right|=L$. 因 $c_{n_j}\to{L}$ 且 $c_{n_j+1}\to{L}$, 由三角不等式,

$$
\left|c_{n_j+1}-c_{n_j}\right|\le\left|f^{n_j+1}\left(a\right)-f^{n_j}\left(a\right)\right|+\left|f^{n_j+1}\left(b\right)-f^{n_j}\left(b\right)\right|.
$$

左端趋于 $0$, 故两项都趋于 $0$. 由 $f$ 连续 (膨胀条件蕴含利普希茨), $f\left(f^{n_j}\left(a\right)\right)=f^{n_j+1}\left(a\right)\to{f}\left(u\right)$; 而它也 $\to{u}$, 故 $f\left(u\right)=u$. 同理 $f\left(v\right)=v$. 由膨胀条件应用于 $\left(a,u\right)$: $\left|f^{n_j}\left(a\right)-f^{n_j}\left(u\right)\right|\ge\left|a-u\right|$, 即 $\left|f^{n_j}\left(a\right)-u\right|\ge\left|a-u\right|$. 令 $j\to\infty$ 得 $0\ge\left|a-u\right|$, 故 $u=a$. 同理 $v=b$. 于是 $L=\left|u-v\right|=\left|a-b\right|=c_0$, 而 $c_n$ 从 $c_0$ 起不减且收敛到 $c_0$, 故 $c_1=c_0$, 即 $\left|f\left(a\right)-f\left(b\right)\right|=\left|a-b\right|$. 由**定义 6.49 (等距映射)**, $f$ 是等距.

再由**定理 5.1 (紧空间连续像紧)** 及**习题 8.11**的论证, $f$ 双射.

现设 $g:X\to{X}$ 满且 $\left|g\left(y\right)-g\left(x\right)\right|\le\left|y-x\right|$. 对任意 $u,v\in{X}$, 取原像 $x,y$ 使 $g\left(x\right)=u$, $g\left(y\right)=v$, 则 $\left|u-v\right|\le\left|x-y\right|$, 即 $g^{-1}$ 满足膨胀条件. 由上一段, $g^{-1}$ 是等距, 故 $g$ 也是等距. $\blacksquare$

## 8.13 (紧空间上的严格压缩映射有唯一不动点)

(紧空间不动点定理) 设 $K$ 是某赋范线性空间的紧子空间. 设 $f:K\to{K}$ 严格压缩, 即 $x\neq{y}$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\left|y-x\right|$. 证明 $f$ 在 $K$ 中有唯一不动点, 且对一切 $a\in{K}$, $f^n\left(a\right)$ 收敛到该不动点.

### 解答 8.13

严格压缩条件蕴含 $f$ 连续 ($\left|f\left(y\right)-f\left(x\right)\right|<\left|y-x\right|$ 即利普希茨常数 $<1$). 令 $g\left(x\right)=\left|f\left(x\right)-x\right|\ge0$; 由**定义 3.22 (连续映射)** 与**定理 3.1 (复合连续)**, $g$ 连续. 由**定理 5.11 (紧空间上连续函数取最大值)** (及其最小值情形), $g$ 在紧集 $K$ 上取到最小值, 设为 $g\left(x_0\right)$. 若 $g\left(x_0\right)>0$, 则由严格压缩,

$$
\left|f^2\left(x_0\right)-f\left(x_0\right)\right|<\left|f\left(x_0\right)-x_0\right|=g\left(x_0\right),
$$

即 $g\left(f\left(x_0\right)\right)<{}g\left(x_0\right)$, 矛盾. 故 $g\left(x_0\right)=0$, $x_0$ 是不动点. 唯一性: 若另有不动点 $y$, 则 $0<\left|y-x_0\right|=\left|f\left(y\right)-f\left(x_0\right)\right|<\left|y-x_0\right|$, 矛盾. 对 $a\in{K}$, $\left|f^{n+1}\left(a\right)-x_0\right|<\left|f^n\left(a\right)-x_0\right|$ 单调下降, 由 $K$ 紧 (**定理 6.1 (紧 $=$ 序列紧)**) 收敛到 $x_0$. $\blacksquare$
