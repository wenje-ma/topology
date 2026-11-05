# week3（连续函数与商、积构造）

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

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
> 设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in V}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$, p17)

> **定义 3.15 (拓扑基)**
> 
> 设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

> **定义 3.16 (离散拓扑与平凡拓扑)**
> 
> 离散拓扑: $X$ 的所有子集都开; 平凡拓扑: 仅 $\emptyset,X$ 开. (教材 §3)

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

> **定义 3.27 (余可数拓扑)**
> 
> 称 $X$ 上的余可数拓扑为: 非空开集恰为可数集的补集. (题集 §1.4)

> **定义 3.28 (扎里斯基拓扑)**
> 
> 设 $K$ 为域, $\mathbb A^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in I}$ 的公共零点集 $\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,\,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.30 (基本邻域系)**
> 
> $x$ 的邻域族 $\mathcal P$, 使 $x$ 的每个邻域都含某个 $\mathcal P$ 中元素. (题集 §2.4)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.7))

> **定理 5.7 (有限乘积紧)**
> 
> 有限个紧空间的乘积紧. (教材 $\S5$, 定理 5.7)

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

> **定义 6.44 (伪距离)**
> 
> 满足除 "$d\left(x,y\right)=0\Rightarrow x=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 §1.3; 题集 §3.2 Q3; 题集 §5 Q5)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.47 ($\varepsilon$-邻域)**
> 
> $U_\varepsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)< \varepsilon\right\}$. (题集 $\S3.2$)

> **定理 7.2 (乌雷松引理)**
> 
> 正规空间中不相交闭集可被连续函数分离. (题集 §6 C13)

> **定义 7.6 (正规空间)**
> 
> 单点闭且任意两不相交闭集可被不相交开集分离, 即 $T_4$. (教材 §7, p42)

> **定义 11.1 (商拓扑)**
> 
> 满射 $\pi:X\to Y$ 下, $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 §11, p61; 《拓扑学》(原书第2版) §22, p105; 《基础拓扑学》(修订版) 第4章 4.2, p55)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to Y$ 使 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to Z$ 连续当且仅当 $gf:X\to Z$ 连续. (教材 §11, p61; 《基础拓扑学》(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定义 11.3 (等价关系粘合)**
> 
> $X/{\sim}$ 配商拓扑, $\pi:X\to X/{\sim}$ 为典范投影; 即将每个等价类黏合成一点. (教材 §11, p61; 《拓扑学》(原书第2版) §22, p106)

> **定义 11.6 (锥)**
> 
> 从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in X$, $0\le t< 1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (教材 $\S11$, p63; 题集 $\S5$ Q9; 《基础拓扑学》(修订版) 第4章)

> **定义 11.7 (环面)**
> 
> 正方形对边同向粘合所得 $S^1\times S^1$, 即 $\mathbb R^2/\mathbb Z^2$. (《基础拓扑学》(修订版) 第4章 4.2, p56; 教材 §11, p64)

> **定义 11.11 (悬垂)**
> 
> $SX=X\times\left[-1,1\right]/\left(X\times\left\{-1\right\}\cup X\times\left\{1\right\}\right)$, 两端各捏成一点. (题集 §5 Q10)

> **定义 11.12 (塌缩商)**
> 
> $X/\left\langle A\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 §5 Q11; 《基础拓扑学》(修订版) 第4章, p57)

> **定义 11.13 ($n$-维环面)**
> 
> $T^n=\mathbb R^n/\mathbb Z^n\cong\left(S^1\right)^n$. (题集 §5 Q13; 教材 §11, p65)

> **定义 11.14 (最终拓扑)**
> 
> 关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 §1.4 C6; 题集 §5 Q1-Q2)

> **定义 11.15 (等价关系的生成)**
> 
> 包含给定二元关系 $R$ 的最小等价关系, 即全体含 $R$ 的等价关系之交. (题集 §5 Q4)

> **定义 11.18 (不交和拓扑)**
> 
> 一族拓扑空间 $\left\{X_i\right\}_{i\in I}$ 的不交和 $\coprod_{i\in I}X_i$ 上, $U$ 开当且仅当每个 $U\cap X_i$ 在 $X_i$ 中开. (题集 §5 Q1; 《基础拓扑学》(修订版) 第4章 定理(4.7), p58)

## 3.1 (基本邻域系：点成立而子集未必)

基本邻域系. 回忆点 $x$ (或子集 $A$) 的邻域; $x$ (或 $A$) 的基本邻域系是 $x$ (或 $A$) 的一族邻域 $\mathcal P$, 使 $x$ (或 $A$) 的每个邻域都含某个 $\mathcal P$ 中元素.

(1) 证明度量空间中, 任取 $r_n\to0$, $B\left(x,r_n\right)$ 是 $x$ 的基本邻域系;

(2) 但当 $A$ 是子集时, $V_{\varepsilon}\left(A\right)=\left\{x:d\left(x,A\right)< \varepsilon\right\}$ 不一定是 $A$ 的基本邻域系. 例如取 $A=\left\{xy=1,x> 0\right\}\subset\mathbb R^2$ 与 $U=\left\{x,y> 0\right\}\subset\mathbb R^2$.

### 解答 2.5

(1) 设 $U$ 是 $x$ 的任一邻域 (**定义 3.25 (邻域与极限)**). 由**定义 6.36 (开球)**, 度量拓扑中存在 $r> 0$ 使 $B\left(x,r\right)\subset U$. 由 $r_n\to0$, 存在 $n$ 使 $r_n< r$, 于是

$$
B\left(x,r_n\right)\subset B\left(x,r\right)\subset U.
$$

由**定义 3.30 (基本邻域系)**, $\left\{B\left(x,r_n\right)\right\}$ 是 $x$ 的基本邻域系.

(2) 取题中 $A=\left\{\left(x,1/x\right):x> 0\right\}\subset\mathbb R^2$, $U=\left\{\left(x,y\right):x> 0,y> 0\right\}$. $U$ 开且 $A\subset U$, 故 $U$ 是 $A$ 的邻域. 对任意 $\varepsilon> 0$, 取点

$$
a=\left(\frac{\varepsilon}{2},\frac{2}{\varepsilon}\right)\in A,
$$

再取 $a'=\left(-\frac{\varepsilon}{4},\frac{2}{\varepsilon}\right)$. 由**定义 6.46 (点到集合的距离)**, $d\left(a',A\right)\le d\left(a',a\right)=\frac{3\varepsilon}{4}< \varepsilon$, 故由**定义 6.47 ($\varepsilon$-邻域)** $a'\in V_{\varepsilon}\left(A\right)$. 但 $a'$ 的横坐标为负, $a'\notin U$. 于是对每个 $\varepsilon> 0$, $V_{\varepsilon}\left(A\right)\not\subset U$. 故没有任何 $V_{\varepsilon}\left(A\right)$ 含于 $U$, 由**定义 3.30 (基本邻域系)**, $\left\{V_{\varepsilon}\left(A\right)\right\}$ 不是 $A$ 的基本邻域系. $\blacksquare$

> 同样的构造基本邻域系的规则, 为什么全集就满足, 子集就不满足呢? 因为全集上定义的邻域必定全在全集内部; 而对于子集, 我们可以找到该子集的边界作为反例的邻域, 在其上的任何 $\varepsilon$-邻域都会超出其范围, 导致了这种构造方法的失效.

## 3.2 (度量空间豪斯多夫，扎里斯基拓扑不豪斯多夫)

豪斯多夫条件.

(1) 证明度量空间总是豪斯多夫的;

(2) 证明 $\mathbb A^n\left(\mathbb R\right)$ (或 $\mathbb R^n$) 的每个扎里斯基开集在通常拓扑下既开又稠密; 证明 $\mathbb A^n\left(\mathbb R\right)$ 的扎里斯基拓扑对任意 $n> 0$ 都不是豪斯多夫的.

### 解答 2.6

(1) 设 $\left(X,d\right)$ 是**定义 6.35 (度量空间)**. 取 $x\neq y$, 令 $r=\frac13 d\left(x,y\right)> 0$. 由**定义 6.36 (开球)**, $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 是开集. 若二者相交, 取交点 $z$, 由**定义 6.35 (度量空间)** (4) 的三角不等式

$$
d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)< 2r=\frac23 d\left(x,y\right),
$$

矛盾. 故 $B\left(x,r\right)\cap B\left(y,r\right)=\emptyset$. 由**定义 3.10 (豪斯多夫空间)**, 度量空间是豪斯多夫的.

(2) 由**定义 3.28 (扎里斯基拓扑)**, 扎里斯基闭集是若干多项式公共零点集. 非零多项式不能在任一通常开集上恒为零 (一元多项式恒零判据), 故扎里斯基闭集在通常拓扑下内部为空. 于是其补集, 即扎里斯基开集, 在通常拓扑下稠密 (**定义 3.32 (稠密)**).

再证非豪斯多夫. 任取 $x\neq y$. 任一非空扎里斯基开集都稠密, 故任意两个非空扎里斯基开集相交. 因而不存在不相交的两个扎里斯基开集分别含 $x$ 与 $y$, 由**定义 3.10 (豪斯多夫空间)**, 扎里斯基拓扑不是豪斯多夫的. $\blacksquare$

## 3.3 (正规性的两种刻画与度量空间的正规性)

正规空间. 称拓扑空间 $X$ 是正规的, 若对任意含于开集 $V$ 的闭集 $F$, 存在开集 $U$ 使 $F\subset U\subset\overline U\subset V$. 证明这等价于说 $X$ 是豪斯多夫的, 且任意两不相交闭集有不相交邻域 (即**定义 7.6 (正规空间)**). 证明度量空间正规 (可先证 $f:x\mapsto d\left(x,F\right)$ 当 $F$ 闭时连续).

### 解答 2.7

先证两种定义等价. 设 $F$ 闭, $V$ 开, $F\subset V$. 若 $X$ 满足**定义 7.6 (正规空间)**, 对不相交闭集 $F$ 与 $X\setminus V$ 取不相交开集 $U\supset F$ 与 $W\supset X\setminus V$. 则 $\overline U\subset X\setminus W\subset V$, 故 $F\subset U\subset\overline U\subset V$. 反过来, 设任意闭 $F\subset$ 开 $V$ 有 $U$ 使 $F\subset U\subset\overline U\subset V$. 对不相交闭集 $F,F'$, 取 $V=X\setminus F'$ (开). 由假设存在 $U\supset F$ 使 $\overline U\subset X\setminus F'$. 令 $W=X\setminus\overline U$ (开, 由**定义 3.26 (闭包)** 与**定义 3.21 (闭集)**), 则 $F'\subset W$ 且 $U\cap W=\emptyset$. 故 $F,F'$ 有不相交邻域. 特别地单点闭 (取 $F=\left\{x\right\}$, 若 $X$ 满足条件则单点为闭), 即 $T_1$, 故为豪斯多夫的.

再证度量空间正规. 设 $F$ 闭. 由**定义 6.46 (点到集合的距离)**, $d\left(x,F\right)=\inf_{a\in F}d\left(x,a\right)$. 由**定义 6.35 (度量空间)** 的三角不等式,

$$
\left|d\left(x,F\right)-d\left(y,F\right)\right|\le d\left(x,y\right),
$$

故 $x\mapsto d\left(x,F\right)$ 连续. 现取不相交闭集 $F,F'$. 令

$$
U=\left\{x:d\left(x,F\right)< d\left(x,F'\right)\right\},\quad
V=\left\{x:d\left(x,F'\right)< d\left(x,F\right)\right\}.
$$

二者开 (连续函数的原像, 由**定义 3.22 (连续映射)**), 不相交, 且 $F\subset U$ (因 $x\in F$ 时 $d\left(x,F\right)=0< d\left(x,F'\right)$), $F'\subset V$. 由**定义 7.6 (正规空间)**, 度量空间正规. $\blacksquare$

## 3.4 (混合烧烤拓扑：非豪斯多夫且无闭邻域基本系)

混合烧烤. 考虑 $\left[0,1\right]\subset\mathbb R$ 与另外两个不属于它的元 $\left\{0^{-},0^{+}\right\}$, 令 $X=\left\{0^{-},0^{+}\right\}\cup\left(0,1\right]$. 定义

$$
\mathcal B\left(x\right)=\left\{\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]:n\in\mathbb Z_{> 0}\right\}\quad\left(x\in\left(0,1\right]\right),
$$

与

$$
\mathcal B\left(0^{\pm}\right)=\left\{\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right):n\in\mathbb Z_{> 0}\right\}.
$$

证明 $\mathcal B=\bigcup_{x\in X}\mathcal B\left(x\right)$ 是某拓扑的基; 证明该拓扑不是豪斯多夫的; 证明 $0^{+}$ 没有由闭邻域组成的基本邻域系.

### 解答 2.8

先验基条件. 对 $x\in\left(0,1\right]$, 两个形如 $\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]$ 的集之交仍含一个同形集; 对 $0^{\pm}$, $\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right)$ 之交为 $\left\{0^{\pm}\right\}\cup\left(0,1/\max\left(n,m\right)\right)$. 全体覆盖 $X$. 由**定义 3.15 (拓扑基)**, $\mathcal B$ 是某拓扑的基.

非豪斯多夫: 任取 $0^{-}$ 的邻域, 它含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$; $0^{+}$ 的邻域含某 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$. 二者都含 $\left(0,1/\max\left(n,m\right)\right)$, 故相交. 不存在不相交开集分别含 $0^{-}$ 与 $0^{+}$, 由**定义 3.10 (豪斯多夫空间)**, 该拓扑非豪斯多夫.

$0^{+}$ 无闭邻域基本系: 设 $C$ 是 $0^{+}$ 的任一闭邻域. 它必含某基本开邻域 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$, 特别含区间 $\left(0,\frac1m\right)$. 点 $0^{-}$ 的每个邻域含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$, 与 $\left(0,\frac1m\right)$ 相交, 故 $0^{-}\in\overline{\left(0,\frac1m\right)}$ (**定义 3.26 (闭包)**). $C$ 闭且含 $\left(0,\frac1m\right)$, 故 $C$ 含其闭包, 从而 $0^{-}\in C$. 于是 $0^{+}$ 的任何闭邻域都含 $0^{-}$, 不可能含于开集 $U=\left\{0^{+}\right\}\cup\left(0,1\right)$ (它不含 $0^{-}$). 由**定义 3.30 (基本邻域系)**, $0^{+}$ 没有由闭邻域组成的基本邻域系. $\blacksquare$

## 3.5 (子空间拓扑的泛性质)

泛性质. 设 $X$ 是拓扑空间, $Y\subset X$ 配自然含映射 $\iota:Y\to X$. 证明 $Y$ 上的子空间拓扑具有如下性质: 对任意拓扑空间 $Z$ 与映射 $f:Z\to Y$, $f$ 连续当且仅当 $\iota\circ f:Z\to X$ 连续.

### 解答 2.9

($\Rightarrow$) 若 $f:Z\to Y$ 连续, 由**定义 3.19 (子空间拓扑)**, 含映射 $\iota:Y\to X$ 连续. 由**定理 3.1 (复合连续)**, $\iota\circ f:Z\to X$ 连续.

($\Leftarrow$) 设 $\iota\circ f:Z\to X$ 连续. 任取 $Y$ 中开集 $O$. 由**定义 3.19 (子空间拓扑)**, $O=Y\cap U$, 其中 $U$ 是 $X$ 中开集. 于是

$$
f^{-1}\left(O\right)=f^{-1}\left(Y\cap U\right)=f^{-1}\left(U\right)=\left(\iota\circ f\right)^{-1}\left(U\right),
$$

最后一步用到 $f$ 映到 $Y$ 中. 由 $\iota\circ f$ 连续及**定义 3.22 (连续映射)**, 右端为 $Z$ 中开集. 故 $f^{-1}\left(O\right)$ 开, 由**定义 3.22 (连续映射)**, $f$ 连续. $\blacksquare$

> 证明中的核心步骤是 $f^{-1}\left(U\right)=\left(\iota\circ f\right)^{-1}\left(U\right)$, 这都归功于 $\iota$ 是含入映射, 即映射到 $Y$ 上的就相当于映射到 $X$ 上.

## 3.6 (投影是开映射，但不必是闭映射，且开性不可逆)

设 $\prod_{i\in I}X_i$ 装备乘积拓扑, $p_k$ 是到第 $k$ 个因子的投影.

(1) 证明每个投影 $p_k$ 都是开映射, 即把开集映成开集;

(2) 举例说明投影一般不是闭映射, 即存在闭集其投影不闭;

(3) 证明开性的逆命题不成立: 存在 $W\subset\prod_{i\in I}X_i$ 使所有 $p_i\left(W\right)$ 都是开集, 但 $W$ 本身不是开集. 可在 $\mathbb R^2$ 中去掉若干点构造反例.

### 解答 2.10

(1) 由**定义 3.11 (乘积拓扑)**, 乘积拓扑的基本开集形如 $\prod_{i\in I}U_i$, 其中 $U_i$ 在 $X_i$ 中开且除有限个外 $U_i=X_i$. 对固定的 $k$, 投影满足

$$
p_k\left(\prod_{i\in I}U_i\right)=U_k,
$$

而 $U_k$ 是 $X_k$ 中的开集. 任一开集 $W\subset\prod_{i\in I}X_i$ 都是基本开集之并 $W=\bigcup_{\alpha}V_\alpha$, 故

$$
p_k\left(W\right)=\bigcup_{\alpha}p_k\left(V_\alpha\right),
$$

由**定义 3.18 (拓扑空间)** (开集任意并仍开), $p_k\left(W\right)$ 是开集. 故每个 $p_k$ 都是开映射.

(2) 取 $\mathbb R^2$, 令 $A=\left\{\left(x,y\right):xy=1\right\}$. $A$ 包含它所有的极限点, 故是闭集; 由**定义 3.21 (闭集)** 其补集 $\left\{xy\neq1\right\}$ 开. 但

$$
p_1\left(A\right)=\left\{x\in\mathbb R:\exists y,\,xy=1\right\}=\mathbb R\setminus\left\{0\right\},
$$

由**定义 3.21 (闭集)** $\mathbb R\setminus\left\{0\right\}$ 不是闭集 ($0$ 是其极限点). 故投影不是闭映射.

(3) 取 $W=\mathbb R^2\setminus\left(\left\{0\right\}\times\left(0,1\right)\right)$. 先看两个投影: 对任意 $x\in\mathbb R$, 取 $y=2$ 则 $\left(x,2\right)\in W$, 故 $p_1\left(W\right)=\mathbb R$; 对任意 $y\in\mathbb R$, 取 $x=1$ 则 $\left(1,y\right)\in W$, 故 $p_2\left(W\right)=\mathbb R$. 两个投影都是开集. 但 $W$ 的补集为 $\left\{0\right\}\times\left(0,1\right)$, 它的闭包是 $\left\{0\right\}\times\left[0,1\right]$, 不等于自身, 由**定义 3.21 (闭集)** 补集不闭, 故 $W$ 不是开集. 这说明所有投影开不能推出原集合开. $\blacksquare$

## 3.7 (度量空间中连续等价于序列保持收敛)

序列, 度量空间与连续. 证明: 对**定义 6.35 (度量空间)** 之间的映射 $f:X\to Y$, $f$ 连续当且仅当 $X$ 中每个收敛序列的像列在 $Y$ 中收敛. 证明中哪些地方用到了度量结构? 能否放松假设?

### 解答 2.11

($\Rightarrow$) 设 $f$ 连续, $x_n\to x$. 任取 $f\left(x\right)$ 的邻域 $V$, 由**定义 3.22 (连续映射)**, $f^{-1}\left(V\right)$ 是 $x$ 的邻域; 由**定义 3.25 (邻域与极限)**, 充分大的 $n$ 有 $x_n\in f^{-1}\left(V\right)$, 即 $f\left(x_n\right)\in V$. 故 $f\left(x_n\right)\to f\left(x\right)$.

($\Leftarrow$) 设序列保持收敛. 反设 $f$ 在 $x$ 不连续, 则存在 $f\left(x\right)$ 的邻域 $V$ 使 $f^{-1}\left(V\right)$ 不是 $x$ 的邻域. 由**定义 6.36 (开球)**, $B\left(x,1/n\right)\not\subset f^{-1}\left(V\right)$, 取 $x_n\in B\left(x,1/n\right)\setminus f^{-1}\left(V\right)$. 则 $d\left(x_n,x\right)< 1/n\to0$, 即 $x_n\to x$, 但 $f\left(x_n\right)\notin V$, 故 $\left(f\left(x_n\right)\right)$ 不收敛到 $f\left(x\right)$, 矛盾.

用到度量结构之处在于: 用可数邻域基 $B\left(x,1/n\right)$ 把 "$f^{-1}\left(V\right)$ 不是邻域" 翻译成一列点 $\left(x_n\right)$, 即把否定连续性直接转化为序列. 在一般拓扑空间中, 这一翻译不成立, 但可放松为第一可数空间 (每点有可数邻域基). $\blacksquare$

## 3.8 (稠密集的邻域未必覆盖全空间)

稠密集的邻域. $X$ 中稠密集的任意邻域是否覆盖 $X$? 可考虑 $\bigcup_{p/q}B\left(p/q,1/q^k\right)$ ($p/q\in\mathbb Q$, $k$ 充分大) 的例子.

### 解答 2.12

不覆盖. 设 $X=\mathbb R$, $D=\mathbb Q$ 是**定义 3.32 (稠密)** 的. 取 $U=\mathbb R\setminus\left\{\sqrt2\right\}$. $U$ 是开集, 由**定义 3.21 (闭集)** 单点 $\left\{\sqrt2\right\}$ 闭故其补集开; $U$ 含 $\mathbb Q$, 即 $U$ 是稠密集 $\mathbb Q$ 的一个邻域, 但 $U\neq\mathbb R$. $\blacksquare$

> 一般地, 若 $D$ 稠密而 $U$ 是含 $D$ 的开集, 只能推出 $\overline U=X$: 由**定义 3.26 (闭包)**, $D\subset U$ 给出 $X=\overline D\subset\overline U$; 开集稠密不必等于全空间. 题中 $\bigcup_{p/q}B\left(p/q,1/q^k\right)$ 也是开稠密集, 取 $k$ 充分大时仍遗漏某些有理逼近系数很小的无理数, 故不等于 $\mathbb R$.

## 3.9 (离散拓扑、单点族的最终拓扑与不交和的三者等价)

设 $X$ 是拓扑空间. 证明下列三条等价:

(1) $X$ 具有离散拓扑;

(2) $X$ 具有由单点族 $\left\{\left\{x\right\}\right\}_{x\in X}$ 诱导的弱 (最终) 拓扑;

(3) 从不交和 $\coprod_{x\in X}\left\{x\right\}$ 到 $X$ 的典范映射是同胚.

### 解答 2.13

记 $i_x:\left\{x\right\}\to X$ 为把单点映到其唯一点的含入映射.

(1) $\Rightarrow$ (2): 设 $X$ 具离散拓扑, 由**定义 3.16 (离散拓扑与平凡拓扑)** 每个子集都开. 由**定义 3.18 (拓扑空间)** 这是一个合法拓扑. 由**定义 11.14 (最终拓扑)**, 由 $\left\{i_x\right\}$ 诱导的最终拓扑是使每个 $i_x$ 连续的最细拓扑; 离散拓扑本身使每个 $i_x$ 连续 (单点空间唯一可能), 且它已是最细拓扑, 故二者相同.

(2) $\Rightarrow$ (1): 设 $X$ 上的拓扑就是由 $\left\{i_x\right\}$ 诱导的最终拓扑. 由**定义 11.14 (最终拓扑)**, $U\subset X$ 开当且仅当对每个 $x$, $i_x^{-1}\left(U\right)$ 在单点空间 $\left\{x\right\}$ 中开. 而单点空间的任意子集 (仅 $\emptyset$ 与 $\left\{x\right\}$) 都开, 故 $X$ 的任意子集 $U$ 都开. 由**定义 3.16 (离散拓扑与平凡拓扑)**, 这就是离散拓扑.

(2) $\Leftrightarrow$ (3): 由**定义 11.18 (不交和拓扑)**, 不交和 $Z=\coprod_{x\in X}\left\{x\right\}$ 上的拓扑是每个单点都开, 即离散拓扑. 典范映射 $i:Z\to X$ 把每个 $\left\{x\right\}$ 映到 $x$, 是双射. 由**定义 11.14 (最终拓扑)**, $i$ 连续当且仅当 $X$ 的拓扑粗于由 $\left\{i_x\right\}$ 诱导的最终拓扑; 反过来 $i^{-1}$ 连续当且仅当该最终拓扑粗于 $X$ 的拓扑. 由**定义 3.23 (同胚)**, $i$ 是同胚当且仅当 $X$ 的拓扑等于由 $\left\{i_x\right\}$ 诱导的最终拓扑, 即 (2). 三链贯通, 三条等价. $\blacksquare$

## 3.10 (递增闭子空间列的最终拓扑与闭性)

设 $X_i$ 是拓扑空间, $X_i\subset X_{i+1}$, $X=\bigcup_{i=1}^{\infty}X_i$. 设每个 $X_i$ 在 $X_{i+1}$ 中闭, 且 $X_i$ 的拓扑就是 $X_{i+1}$ 的拓扑在 $X_i$ 上诱导的子空间拓扑. 证明: 对每个 $i$, $X_i$ 的拓扑等于 $X$ 上由族 $\left\{X_i\right\}$ 诱导的弱 (最终) 拓扑在 $X_i$ 上诱导的子空间拓扑; 进一步每个 $X_i$ 在 $X$ 中闭.

### 解答 2.14

记 $\tau$ 为 $X$ 上由含入 $j_i:X_i\to X$ 诱导的最终拓扑. 由**定义 11.14 (最终拓扑)**, $U\subset X$ 在 $\tau$ 中开当且仅当对每个 $k$, $U\cap X_k$ 在 $X_k$ 中开. 由题设归纳可知: 对 $k\ge i$, $X_i$ 在 $X_k$ 中闭; 且 $X_i$ 的拓扑就是 $X_k$ 的拓扑在 $X_i$ 上的子空间拓扑.

先证子空间一致性. 由**定义 3.19 (子空间拓扑)**, $X_i$ 从 $\left(X,\tau\right)$ 继承的开集为 $\left\{U\cap X_i:U\in\tau\right\}$.

(a) 包含 $\supset$: 若 $U\in\tau$, 由上面的刻画 $U\cap X_i$ 在 $X_i$ 中开, 故继承开集都是原拓扑开集.

(b) 包含 $\subset$: 任取原开集 $V\subset X_i$. 构造

$$
U=V\cup\left(X\setminus X_i\right).
$$

则 $U\cap X_i=V$. 验证 $U\in\tau$: 对 $k=i$, $U\cap X_i=V$ 开; 对 $k< i$, $X_k\subset X_i$, 故 $U\cap X_k=V\cap X_k$, 由 $X_k$ 的子空间性质它在 $X_k$ 中开; 对 $k> i$, $X_i$ 在 $X_k$ 中闭, 故 $X_k\setminus X_i$ 在 $X_k$ 中开, 而 $V$ 在 $X_i$ 中开, 由 $X_i$ 是 $X_k$ 的子空间可写 $V=X_i\cap W$, $W$ 在 $X_k$ 中开, 于是 $U\cap X_k=\left(X_i\cap W\right)\cup\left(X_k\setminus X_i\right)=W\cup\left(X_k\setminus X_i\right)$ 在 $X_k$ 中开. 故 $U\in\tau$, 且 $V=U\cap X_i$ 是继承开集.

故 $X_i$ 的原拓扑等于继承拓扑.

再证 $X_i$ 在 $X$ 中闭. 只需证 $X\setminus X_i$ 在 $\tau$ 中开. 对 $k\le i$, $\left(X\setminus X_i\right)\cap X_k=\emptyset$ 开; 对 $k> i$, $X_i$ 在 $X_k$ 中闭, 故 $\left(X\setminus X_i\right)\cap X_k=X_k\setminus X_i$ 在 $X_k$ 中开. 由**定义 11.14 (最终拓扑)**, $X\setminus X_i\in\tau$, 故 $X_i$ 闭. $\blacksquare$

## 3.11 (由二元关系生成的最小等价关系)

(二元关系生成的等价关系) 设 $X$ 是集合, $R\subset X\times X$ 是二元关系 (未必是等价关系). 证明: 存在唯一的最小等价关系 $\sim$ 包含 $R$ (在 $X\times X$ 的子集意义下), 称为由 $R$ 生成的等价关系.

### 解答 2.15

先证一族等价关系的交仍是等价关系. 设 $\left\{\sim_\alpha\right\}_{\alpha\in A}$ 是 $X$ 上的等价关系族, 定义 $x\sim y$ 当且仅当对一切 $\alpha$ 有 $x\sim_\alpha y$.

(a) 自反: 每个 $\sim_\alpha$ 自反, 故 $x\sim_\alpha x$ 对一切 $\alpha$, 即 $x\sim x$.

(b) 对称: $x\sim y$ 蕴含 $x\sim_\alpha y$ 对一切 $\alpha$, 由每个 $\sim_\alpha$ 对称得 $y\sim_\alpha x$, 故 $y\sim x$.

(c) 传递: $x\sim y$ 且 $y\sim z$, 则对一切 $\alpha$, $x\sim_\alpha y$ 且 $y\sim_\alpha z$, 由每个 $\sim_\alpha$ 传递得 $x\sim_\alpha z$, 故 $x\sim z$.

故 $\sim$ 是等价关系.

现令 $\mathcal E$ 为 $X$ 上全体包含 $R$ 的等价关系所成之族. 全体成员的交 $\bigcap\mathcal E$ 仍含 $R$ (每个成员含 $R$), 且由上面的交性质是等价关系. 它是含 $R$ 的最小等价关系: 任何含 $R$ 的等价关系都在 $\mathcal E$ 中, 从而包含这个交. 唯一性由"最小"即集包含意义下唯一决定. 由**定义 11.15 (等价关系的生成)**, 这个交就是由 $R$ 生成的等价关系. $\blacksquare$

## 3.12 (伪距离的商距离与商拓扑一致)

(伪距离的商距离) 回顾伪距离 $d$ 是除 $d\left(x,y\right)=0\Rightarrow x=y$ 外满足全部度量公理的函数. 伪距离空间 $\left(X,d\right)$ 以开球 $B\left(x,\varepsilon\right)$ 为基有拓扑. 定义 $x\sim y$ 当且仅当 $d\left(x,y\right)=0$. 证明: $\sim$ 是等价关系; 商空间 $X/{\sim}$ 上可赋予距离 $d'$ 使 $d'\left(\left[x\right],\left[y\right]\right)=d\left(x,y\right)$; 验证 $d'$ 定义适定; 证明度量空间 $\left(X/{\sim},d'\right)$ 与商空间 $X/{\sim}$ 拓扑相同; 并证明若 $F$ 是豪斯多夫空间且 $f:X\to F$ 连续, 则 $f$ 可分解为 $f=f'\circ\pi$, 其中 $f':X/{\sim}\to F$.

### 解答 2.16

$\sim$ 是等价关系: 由**定义 6.44 (伪距离)**, $d\left(x,x\right)=0$ 给出自反; $d\left(x,y\right)=d\left(y,x\right)$ 给出对称; 三角不等式 $d\left(x,z\right)\le d\left(x,y\right)+d\left(y,z\right)$ 在 $d\left(x,y\right)=d\left(y,z\right)=0$ 时给出 $d\left(x,z\right)=0$, 即传递.

$d'$ 适定: 若 $x\sim x'$, $y\sim y'$, 则 $d\left(x,x'\right)=d\left(y,y'\right)=0$, 由三角不等式,

$$
d\left(x,y\right)\le d\left(x,x'\right)+d\left(x',y'\right)+d\left(y',y\right)=d\left(x',y'\right),
$$

同理 $d\left(x',y'\right)\le d\left(x,y\right)$. 故二者相等, $d'\left(\left[x\right],\left[y\right]\right):=d\left(x,y\right)$ 与代表元选取无关.

$d'$ 是度量: 非负, 对称, 三角不等式都从 $d$ 继承; 而 $d'\left(\left[x\right],\left[y\right]\right)=0$ 即 $d\left(x,y\right)=0$, 即 $x\sim y$, 即 $\left[x\right]=\left[y\right]$. 正定性成立.

拓扑相同: 记 $\pi:X\to X/{\sim}$ 为商投影. 对任意 $x,\varepsilon$,

$$
\pi^{-1}\left(B_{d'}\left(\left[x\right],\varepsilon\right)\right)=B_d\left(x,\varepsilon\right).
$$

包含 $\subset$: 若 $z$ 使 $d'\left(\left[z\right],\left[x\right]\right)< \varepsilon$, 即 $d\left(z,x\right)< \varepsilon$, 则 $z\in B_d\left(x,\varepsilon\right)$. 包含 $\supset$: 若 $z\in B_d\left(x,\varepsilon\right)$, 则 $d'\left(\left[z\right],\left[x\right]\right)=d\left(z,x\right)< \varepsilon$. 由**定义 11.1 (商拓扑)**, $B_{d'}\left(\left[x\right],\varepsilon\right)$ 是商开集, 故度量拓扑粗于商拓扑. 反之, 若 $U$ 是商开集, 则 $\pi^{-1}\left(U\right)$ 是 $d$-开集, 从而是若干 $d$-球之并, 其像 $U=\pi\left(\pi^{-1}\left(U\right)\right)$ 是若干 $d'$-球之并, 故 $U$ 是度量开集. 二者一致.

泛分解: 设 $F$ 豪斯多夫, $f:X\to F$ 连续. 先证 $f$ 在等价类上取常值. 若 $x\sim x'$, 即 $d\left(x,x'\right)=0$, 则 $x$ 与 $x'$ 在 $X$ 中无法用开集分离: 对任意 $\varepsilon> 0$, $B_d\left(x,\varepsilon\right)=B_d\left(x',\varepsilon\right)$. 若 $f\left(x\right)\neq f\left(x'\right)$, 由**定义 3.10 (豪斯多夫空间)** 存在不相交开邻域 $V\ni f\left(x\right)$, $W\ni f\left(x'\right)$. 由**定义 3.22 (连续映射)**, $f^{-1}\left(V\right)$ 是 $x$ 的开邻域, 从而含 $x'$, 故 $f\left(x'\right)\in V$, 与 $V\cap W=\emptyset$ 及 $f\left(x'\right)\in W$ 矛盾. 故 $f\left(x\right)=f\left(x'\right)$.

于是可定义 $f'\left(\left[x\right]\right)=f\left(x\right)$, 适定. 由**定义 11.2 (粘合映射)**, 为证 $f'$ 连续, 只需对任意开集 $O\subset F$, $\left(f'\right)^{-1}\left(O\right)$ 商开, 即 $\pi^{-1}\left(\left(f'\right)^{-1}\left(O\right)\right)=f^{-1}\left(O\right)$ 在 $X$ 中开; 这由 $f$ 连续保证. 故 $f=f'\circ\pi$. $\blacksquare$
