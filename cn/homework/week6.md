# 作业 6

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **教材 §3** (点态收敛判据)<br>设 $X=A^{S}$ 赋乘积拓扑. 则序列 $f_n\in X$ 收敛到 $g$, 当且仅当对一切 $s\in S$ 有 $f_n\left(s\right)\to g\left(s\right)$; 乘积拓扑在 $X=A^B$ 的情形又叫点态收敛拓扑. (教材 $\S3$, p22)

> **定义 3.15** (拓扑基)<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$)

> **定义 3.18** (拓扑空间)<br>开集族 $\mathcal T$ 满足公理: (1) $\varnothing,X\in\mathcal T$; (2) 若 $U,V\in\mathcal T$ 则 $U\cap V\in\mathcal T$; (3) 若 $\mathcal A\subset\mathcal T$ 则 $\bigcup\mathcal A\in\mathcal T$. (教材 $\S3$, p12)

> **定义 3.19** (子空间拓扑)<br>若 $A\subset X$, 子空间拓扑由 $\mathcal T_A=\left\{U\cap A:U\in\mathcal T_X\right\}$ 定义. (教材 $\S3$, p17)

> **定义 3.22** (连续映射)<br>称 $f:X\to Y$ 连续, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开集. (教材 $\S3$, p14)

> **定义 3.24** (极限点)<br>称 $x$ 是 $A$ 的极限点, 若 $x$ 的每个邻域都含有 $A$ 中异于 $x$ 的点. (教材 $\S3$, p18)

> **定义 3.25** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$)

> **定义 3.26** (闭包)<br>$A\subset X$ 的闭包 $\overline A$ 是包含 $A$ 的最小闭集. (教材 $\S3$, p18)

> **定义 3.27** (闭集)<br>若 $X\setminus F$ 是开集, 则称 $F$ 为闭集. (教材 $\S3$, p13)

> **定义 3.28** (扎里斯基拓扑)<br>设 $K$ 为域, $\mathbb A^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in I}$ 的公共零点集 $\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定理 3.5** (闭包与极限点)<br>$A$ 的闭包是 $A$ 与其全体极限点之并: $\overline A=A\cup A'$. (教材 $\S3$ 定理 3.5)

> **定理 3.6** (豪斯多夫的遗传性)<br>两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定义 3.32** (稠密)<br>若 $\overline A=X$, 则称 $A$ 在 $X$ 中稠密. (教材 $\S3$; 题集 $\S1.1$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4** (闭子集紧)<br>若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **定理 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定理 5.7** (有限乘积紧)<br>有限个紧空间的乘积紧. (教材 $\S5$ 定理 5.7)

> **定理 5.9** (吉洪诺夫定理)<br>任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.11** (紧空间上连续函数取最大值)<br>紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 5.15** (开覆盖与有限子覆盖)<br>开覆盖 $\left\{U_i\right\}$ 满足 $X=\bigcup_i U_i$; 有限子覆盖为仍覆盖 $X$ 的有限子族. (教材 $\S5$)

> **定义 5.16** (紧致空间)<br>称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1** (紧 $=$ 序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **教材 §6** (度量空间是豪斯多夫的)<br>度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

> **教材 §6** (度量连续与序列)<br>度量空间之间的映射 $f:X\to Y$ 连续, 当且仅当 $x_i\to x$ 蕴含 $f\left(x_i\right)\to f\left(x\right)$. (教材 $\S6$, p34)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.36** (开球与度量拓扑)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)< r\right\}$. 全体开球构成度量拓扑的一个基; 度量拓扑定义为: $U$ 开当且仅当对每个 $x\in U$ 存在 $r> 0$ 使 $B\left(x,r\right)\subset U$. (教材 $\S6$)

> **定义 6.40** (序列紧致)<br>称 $X$ 是序列紧致的, 若 $X$ 中每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.42** (完全有界)<br>对每个 $r> 0$, $X$ 可被有限个半径 $r$ 的球覆盖. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.4** (局部紧空间)<br>设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. (教材 $\S7$, p44). 标准定义 (Munkres $\S29$): $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧.

> **定义 7.5** (单点紧化)<br>亚历山德罗夫紧化 $\overline X=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset X$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

> **定义 11.2** (商拓扑)<br>设 $f:X\to A$ 为满射. $A$ 上的商拓扑定义为: $U\subset A$ 开当且仅当 $f^{-1}U\subset X$ 开. (教材 $\S11$, p61; Armstrong 第4章 4.2)

> **定义 11.6** (锥)<br>从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in X$, $0\le t< 1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (Armstrong 第4章 粘合空间 4.2; 教材 $\S11$, p63)

> **定义 11.12** (塌缩商)<br>$X/\left\langle A\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 $\S5$ Q11)

### 习题一

证明 $\left\{0,1\right\}^{\left[0,1\right]}$ 赋通常乘积拓扑不是序列紧致的.

### 解答 习题一

把 $\left\{0,1\right\}^{\left[0,1\right]}$ 中的点视为函数 $f:\left[0,1\right]\to\left\{0,1\right\}$. 由**定义 3.11** (乘积拓扑) 与**教材 §3** (点态收敛判据), 在乘积拓扑下 $f_n\to f$ 当且仅当每个坐标 $t\in\left[0,1\right]$ 都有 $f_n\left(t\right)\to f\left(t\right)$ (该判据对任意因子空间 $A^S$ 成立, 因为乘积拓扑的基与因子空间无关, 见**定义 3.11**).

对每个 $n\ge1$, 定义 $f_n\left(t\right)$ 为 $t$ 的二进制展开中小数点后第 $n$ 位数字 (二进有理点固定取其一展开). 任取严格递增的正整数列 $n_1< n_2< \dots$, 我们证明 $\left\{f_{n_k}\right\}$ 不收敛. 取 $t^{*}\in\left[0,1\right]$, 使其二进制展开在第 $n_{2k-1}$ 位为 $0$, 在第 $n_{2k}$ 位为 $1$, 其余位任意 (例如取 $0$). 则坐标 $t^{*}$ 处 $f_{n_k}\left(t^{*}\right)$ 依次为 $0,1,0,1,\dots$, 在离散空间 $\left\{0,1\right\}$ 中不收敛 (由**定义 3.25** (邻域与极限), $\left\{0\right\}$ 是 $0$ 的邻域而不含无穷多个 $f_{n_k}\left(t^{*}\right)$). 由点态收敛判据, $\left\{f_{n_k}\right\}$ 在乘积拓扑下不收敛. 因每个子列都有同样形式, 由**定义 6.40** (序列紧致), $\left\{0,1\right\}^{\left[0,1\right]}$ 不是序列紧致的. $\blacksquare$

### 习题二

称集合族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空. 证明: 空间 $X$ 紧致等价于, $X$ 中任意具有限交性质的闭集族 $\mathcal F$ 都满足 $\bigcap_{F\in\mathcal F}F\neq\emptyset$.

### 解答 习题二

由**定义 5.15** (开覆盖与有限子覆盖) 与**定义 5.16** (紧致空间), 分两个方向证明.

($\Rightarrow$) 设 $X$ 紧致, $\mathcal F$ 是具有限交性质的闭集族. 若 $\bigcap_{F\in\mathcal F}F=\emptyset$, 则 $\left\{X\setminus F:F\in\mathcal F\right\}$ 是 $X$ 的开覆盖 (各 $F$ 闭, 由**定义 3.27** (闭集) 其补开). 由**定义 5.16** (紧致空间), 它有有限子覆盖 $X\setminus F_1,\dots,X\setminus F_k$, 即 $X=\bigcup_{i=1}^{k}\left(X\setminus F_i\right)$. 取补集得 $\bigcap_{i=1}^{k}F_i=\emptyset$, 与**定义 5.17** (有限交性质) 矛盾. 故全族之交非空.

($\Leftarrow$) 设任意具有限交性质的闭集族之交非空. 任取 $X$ 的开覆盖 $\left\{U_i\right\}$. 令 $F_i=X\setminus U_i$, 由**定义 3.27** (闭集) 各 $F_i$ 闭. 若 $\left\{U_i\right\}$ 无有限子覆盖, 则任意有限个 $F_{i_1},\dots,F_{i_k}$ 满足

$$
\bigcap_{j=1}^{k}F_{i_j}=X\setminus\bigcup_{j=1}^{k}U_{i_j}\neq\emptyset,
$$

即 $\left\{F_i\right\}$ 具有限交性质. 由假设 $\bigcap_iF_i\neq\emptyset$, 即 $X\setminus\bigcup_iU_i\neq\emptyset$, 与 $\left\{U_i\right\}$ 覆盖 $X$ 矛盾. 故存在有限子覆盖, 由**定义 5.16** (紧致空间), $X$ 紧致. $\blacksquare$

### 习题三

设 $A,B$ 是度量空间 $\left(X,d\right)$ 中不相交的闭集, 且 $A$ 紧致. 证明 $d\left(A,B\right)> 0$.

### 解答 习题三

令 $g\left(x\right)=d\left(x,B\right)$. 由**定义 6.46** (点到集合的距离), $g$ 有定义. 由**定义 6.35** (度量空间) 的三角不等式与**定义 6.46**, 对任意 $x,y\in X$ 与 $b\in B$ 有 $d\left(x,b\right)\le d\left(x,y\right)+d\left(y,b\right)$, 对 $b$ 取下确界再对称化得 $\left|g\left(x\right)-g\left(y\right)\right|\le d\left(x,y\right)$; 于是 $x_n\to x$ 蕴含 $g\left(x_n\right)\to g\left(x\right)$, 由**教材 §6** (度量连续与序列), $g$ 连续. 因 $A$ 紧致, 由**定理 5.11** (紧空间上连续函数取最大值), $g$ 在 $A$ 上取到最小值

$$
m=\min_{a\in A}g\left(a\right)=\inf_{a\in A,\,b\in B}d\left(a,b\right)=d\left(A,B\right).
$$

若 $m=0$, 则存在 $a_0\in A$ 使 $d\left(a_0,B\right)=0$, 即对每个 $r> 0$ 开球 $B\left(a_0,r\right)$ 都与 $B$ 相交 (由**定义 6.36** (开球)); 因 $a_0\notin B$ (由 $A\cap B=\emptyset$), 由**定义 3.24** (极限点) $a_0$ 是 $B$ 的极限点. 由**定理 3.5** (闭包与极限点) $a_0\in\overline B$, 而 $B$ 闭, 由**定义 3.26** (闭包) $\overline B=B$, 故 $a_0\in B$, 与 $A\cap B=\emptyset$ 矛盾. 故 $m> 0$, 即 $d\left(A,B\right)> 0$. $\blacksquare$

### 习题四

设 $\left(X,d\right)$ 是无孤立点的度量空间. 证明: $X$ 紧致当且仅当对任意一对不相交闭集 $A,B$, 都有 $d\left(A,B\right)> 0$.

### 解答 习题四

($\Rightarrow$) 设 $X$ 紧致, $A,B$ 为不相交闭集. 由**定理 5.4** (闭子集紧), $A$ 紧致. 由习题三的论证 (连续函数 $d\left(\cdot,B\right)$ 在 $A$ 上取到正最小值) 即得 $d\left(A,B\right)> 0$.

($\Leftarrow$) 反证, 设 $X$ 不紧致. 由**定理 6.1** (紧 $=$ 序列紧), $X$ 不是序列紧致的, 故存在序列 $\left\{x_n\right\}$ 无收敛子列. 必要时取子列使 $x_n$ 两两不同. 于是 $S=\left\{x_n:n\ge1\right\}$ 无极限点: 若 $x$ 是 $S$ 的极限点, 由**定义 3.24** (极限点) 每个开球 $B\left(x,1/k\right)$ 都含 $S\setminus\left\{x\right\}$ 的点, 且事实上含无穷多个 (若某球只含有限个, 取半径小于这些点到 $x$ 的距离, 得与极限点定义矛盾的球), 故可归纳选取两两不同的 $x_{n_k}\in B\left(x,1/k\right)$, 得收敛于 $x$ 的子列, 矛盾. 故 $S'=\emptyset$, 由**定理 3.5** (闭包与极限点) $\overline S=S$, 由**定义 3.26** (闭包) $S$ 闭. 因 $X$ 无孤立点, 每个 $x_n$ 的任意邻域都含异于 $x_n$ 的点; 归纳地选取 $y_n$, 使 $0< d\left(y_n,x_n\right)< 1/n$, 且 $y_n\notin S\cup\left\{y_1,\dots,y_{n-1}\right\}$. 则 $\left\{y_n\right\}$ 也无收敛子列: 若 $y_{n_k}\to y$, 则由**定义 6.35** (度量空间) 的三角不等式,

$$
d\left(x_{n_k},y\right)\le d\left(x_{n_k},y_{n_k}\right)+d\left(y_{n_k},y\right)\to0,
$$

与 $\left\{x_n\right\}$ 无收敛子列矛盾. 故 $T=\left\{y_n:n\ge1\right\}$ 也闭 (同上). 令 $A=S$, $B=T$, 则二者不相交闭, 但对一切 $n$ 有 $d\left(A,B\right)\le d\left(x_n,y_n\right)< 1/n$, 故 $d\left(A,B\right)=0$, 与假设矛盾. 因此 $X$ 紧致. $\blacksquare$

### 习题五

考虑 $\mathbb C$ 与一个无穷远点 $\left\{\infty\right\}$. 记 $\overline{\mathbb C}=\mathbb C\cup\left\{\infty\right\}$, 规定 $U\subset \overline{\mathbb C}$ 的拓扑为: 若 $\infty\notin U$, 则 $U$ 开当且仅当它是 $\mathbb C$ 中通常开集; 若 $\infty\in U$, 则 $U$ 开当且仅当 $\mathbb C\setminus\left(U\cap\mathbb C\right)$ 在 $\mathbb C$ 中紧致. 证明 $\overline{\mathbb C}$ 紧致. 此即亚历山德罗夫单点紧化, $\overline{\mathbb C}$ 称为黎曼球面.

### 解答 习题五

由**定义 7.5** (单点紧化), $\overline{\mathbb C}$ 正是 $\mathbb C$ 的单点紧化. 任取 $\overline{\mathbb C}$ 的开覆盖 $\mathcal U$. 取 $U_\infty\in\mathcal U$ 使 $\infty\in U_\infty$. 由拓扑定义, $K=\mathbb C\setminus\left(U_\infty\cap\mathbb C\right)$ 在 $\mathbb C$ 中紧致. 族

$$
\left\{U\cap\mathbb C:U\in\mathcal U\setminus\left\{U_\infty\right\}\right\}
$$

中每个集合是 $\mathbb C$ 中开集 (不含 $\infty$ 的开集在 $\overline{\mathbb C}$ 与在 $\mathbb C$ 中同样开), 且它们覆盖 $K$ (因 $K$ 与 $U_\infty$ 无交). 由 $K$ 紧致, 即由**定义 5.16** (紧致空间), 有有限子族 $U_1,\dots,U_m$ 使 $K\subset\bigcup_{i=1}^{m}U_i$. 于是 $U_\infty,U_1,\dots,U_m$ 覆盖 $\overline{\mathbb C}$: $U_\infty$ 含 $\infty$ 与 $U_\infty\cap\mathbb C$, 其余集合覆盖 $K$. 故 $\overline{\mathbb C}$ 的任意开覆盖都有有限子覆盖, 由**定义 5.16** (紧致空间), $\overline{\mathbb C}$ 紧致. $\blacksquare$

### 习题六

给 $\left\{1,\dots,k\right\}$ 赋离散拓扑. 证明 $\left\{1,\dots,k\right\}$ 在该拓扑下紧致.

### 解答 习题六

设 $\mathcal U$ 是 $\left\{1,\dots,k\right\}$ 的任意开覆盖. 由**定义 5.15** (开覆盖与有限子覆盖), 对每个点 $i\in\left\{1,\dots,k\right\}$ 选取 $U_i\in\mathcal U$ 使 $i\in U_i$. 则 $\left\{U_1,\dots,U_k\right\}$ 是有限子族且仍覆盖 $\left\{1,\dots,k\right\}$. 由**定义 5.16** (紧致空间), $\left\{1,\dots,k\right\}$ 紧致. $\blacksquare$

> 离散拓扑: 每个点自己就是开集, 开集的并也是开集, 这么说每个点又都是闭集, 所以每个点都是开闭集.

### 习题七

用吉洪诺夫定理证明: 映射集合 $X=\left\{f:V\to\left\{1,\dots,k\right\}\right\}$ 紧致.

### 解答 习题七

集合 $X=\left\{1,\dots,k\right\}^{V}=\prod_{v\in V}\left\{1,\dots,k\right\}$ 是离散有限空间 $\left\{1,\dots,k\right\}$ 的乘积. 由习题六, 每个因子 $\left\{1,\dots,k\right\}$ 紧致. 由**定理 5.9** (吉洪诺夫定理), 乘积 $X$ 在乘积拓扑下紧致. $\blacksquare$

### 习题八

设 $X,Y$ 是度量空间, $f:X\to Y$. 证明: $f$ 连续当且仅当 $f$ 在任意紧子集 $K\subset X$ 上的限制都连续.

### 解答 习题八

($\Rightarrow$) 设 $f$ 连续, $K\subset X$ 紧. 由**定义 3.22** (连续映射) 与**定义 3.19** (子空间拓扑), $f|_K$ 连续: 对 $Y$ 中开集 $U$, $\left(f|_K\right)^{-1}\left(U\right)=f^{-1}\left(U\right)\cap K$ 是 $K$ 中开集.

($\Leftarrow$) 反设 $f$ 在某点 $x$ 不连续. 由**教材 §6** (度量连续与序列) 的逆否与**定义 3.25** (邻域与极限), 存在 $\varepsilon> 0$ 与序列 $x_n\to x$ 使 $d_Y\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon$. 集合 $K=\left\{x\right\}\cup\left\{x_n\right\}$ 紧致: 任取开覆盖, 含 $x$ 的开集 $U$ 是 $x$ 的邻域 (由**定义 3.25**), 由 $x_n\to x$ 它含除有限个外的所有 $x_n$; 其余有限个点再各取一个覆盖元, 得有限子覆盖. 由假设 $f|_K$ 连续, 故 $x_n\to x$ 时由**教材 §6** (度量连续与序列) 应有 $f\left(x_n\right)\to f\left(x\right)$, 矛盾. 因此 $f$ 处处连续. $\blacksquare$

### 习题九

设 $X$ 是豪斯多夫空间. 证明: $X$ 局部紧 (即每点有紧邻域基) 当且仅当每点有一个紧邻域.

### 解答 习题九

($\Rightarrow$) 设每点有紧邻域基 (即题目括号中的表述, 见**定义 7.4** (局部紧空间)). 则对每个 $x$, 其紧邻域基的任一成员都是 $x$ 的一个紧邻域. 故每点有一个紧邻域.

($\Leftarrow$) 设每点有一个紧邻域. 取 $x$ 的紧邻域 $K$; 由**定理 5.5** (豪斯多夫中紧集闭), $K$ 闭. 任取 $x$ 的邻域 $U$, 即含 $x$ 的开集 (由**定义 3.25** (邻域与极限)). 令 $L=K\setminus U$, 它是紧集 $K$ 的闭子集, 由**定理 5.4** (闭子集紧) 紧. 对每个 $y\in L$, 由**定义 3.10** (豪斯多夫空间) 有不相交开集 $O_y\ni x$, $W_y\ni y$; 因 $L$ 紧, $L\subset\bigcup_{i=1}^{m}W_{y_i}$ 对某个有限子族成立. 令 $O=\bigcap_{i=1}^{m}O_{y_i}$, 由**定义 3.18** (拓扑空间, 有限交仍开) $O$ 是含 $x$ 的开集, 且 $O\cap\bigcup_{i=1}^{m}W_{y_i}=\emptyset$, 故 $O\cap L=\emptyset$. 记 $W=\bigcup_{i=1}^{m}W_{y_i}$, 则 $O\subset X\setminus W$ 且 $X\setminus W$ 闭, 由**定义 3.26** (闭包) $\overline O\subset X\setminus W$; 于是 $\overline O\cap K\subset\left(X\setminus W\right)\cap K\subset K\setminus L=K\cap U\subset U$. 又 $\overline O\cap K$ 是紧集 $K$ 的闭子集 ($\overline O$ 闭, 定义 3.26), 由**定理 5.4** (闭子集紧) 紧; 它含 $x$ 的开邻域 $O\cap\operatorname{int}\left(K\right)$. 故 $x$ 有含于 $U$ 的紧邻域; 因 $U$ 任意, $x$ 有紧邻域基. 由题目括号中的表述 (局部紧即每点有紧邻域基), $X$ 局部紧. $\blacksquare$

### 习题十

(维数与紧性) 证明: 任意实赋范线性空间的单位球紧致, 当且仅当该空间维数有限.

### 解答 习题十

设 $E$ 是**定义 6.20** (赋范线性空间) 中的空间.

($\Leftarrow$) 设 $\dim E=n< \infty$. 由线性代数, $E$ 线性同构于 $\mathbb R^n$, 且有限维赋范空间上的线性映射连续, 故该同构是 $\mathbb R^n$ 与 $E$ 之间的同胚 (有限维赋范空间上的线性映射连续是线性代数标准事实, 题集 $\S7$ 亦默认之). 单位球是有界闭集: 有界由范数定义, 闭由 $\left\|\cdot\right\|$ 连续 (三角不等式 (定义 6.20) 给出 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$) 得出. 故其在 $\mathbb R^n$ 中的像闭且有界, 由**定理 5.3** ($\mathbb R^n$ 中的紧集) 紧; 紧性在同胚下保持 (由**定理 5.1** 或同胚定义), 故单位球紧.

($\Rightarrow$) 反之, 若 $E$ 无穷维, 由**定理 6.17** (里茨定理), 其闭单位球非紧. 故单位球紧致蕴含维数有限. $\blacksquare$

### 习题十一

设 $E,F$ 是两个度量空间, $f:E\to F$ 是单射.

(1) 证明: $f$ 连续当且仅当对每个紧集 $K\subset E$, 像集 $f\left(K\right)$ 在 $F$ 中是紧集;

(2) 举例说明若 $f$ 不单射, 上述等价可以失效.

### 解答 习题十一

(1) $\left(\Rightarrow\right)$ 设 $f$ 连续, $K\subset E$ 紧. $f|_K$ 连续 (由**定义 3.22** (连续映射) 与**定义 3.19** (子空间拓扑), 同习题八 ($\Rightarrow$)), 由**定理 5.1** (紧空间连续像紧), $f\left(K\right)$ 紧.

$\left(\Leftarrow\right)$ 设对每个紧集 $K\subset E$, $f\left(K\right)$ 紧. 反设 $f$ 在某点 $x$ 不连续. 由**教材 §6** (度量连续与序列) 的逆否与**定义 3.25** (邻域与极限), 存在 $\varepsilon> 0$ 与序列 $x_n\to x$ 使 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon$. 由 $f$ 单射及 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\varepsilon> 0$ 知 $x_n\neq x$. 令 $K=\left\{x\right\}\cup\left\{x_n:n\ge1\right\}$, 它紧 (同习题八的论证: 收敛序列加极限). 由假设 $f\left(K\right)$ 紧; $F$ 是度量空间, 由**教材 §6** (度量空间是豪斯多夫的) 豪斯多夫, 由**定理 5.5** (豪斯多夫中紧集闭), $f\left(K\right)$ 在 $F$ 中闭.

由**定理 6.1** (紧 $=$ 序列紧), $f\left(x_n\right)$ 在紧集 $f\left(K\right)$ 中有收敛子列 $f\left(x_{n_j}\right)\to y\in f\left(K\right)$. 设 $y=f\left(z\right)$, $z\in K$. 若 $z=x$, 则 $f\left(x_{n_j}\right)\to f\left(x\right)$, 与 $d_F\left(f\left(x_{n_j}\right),f\left(x\right)\right)\ge\varepsilon$ 矛盾. 故 $z=x_m$ 是某固定项. 取尾部紧集 $K'=\left\{x\right\}\cup\left\{x_{n_j}:j> m\right\}$. 由假设 $f\left(K'\right)$ 紧, 再由**定理 5.5** (豪斯多夫中紧集闭) $f\left(K'\right)$ 闭. 但 $f\left(x_{n_j}\right)\to f\left(x_m\right)$ 且 $x_m\notin K'$, 由 $f$ 单射 $f\left(x_m\right)\notin f\left(K'\right)$; 而 $f\left(x_m\right)$ 是 $f\left(K'\right)$ 的极限点 (每个邻域含充分大的 $f\left(x_{n_j}\right)$, 由**定义 3.25**), 由**定理 3.5** (闭包与极限点) 与**定义 3.26** (闭包) 应有 $f\left(x_m\right)\in\overline{f\left(K'\right)}=f\left(K'\right)$, 矛盾. 故 $f$ 连续.

(2) 取 $E=\left\{0\right\}\cup\left\{1/n:n\ge1\right\}$, $F=\left\{0,1\right\}$ 装备离散度量, $f\left(0\right)=0$, $f\left(1/n\right)=1$ 对一切 $n$. $f$ 不单射. 对 $E$ 中任何紧集 $K$, 像 $f\left(K\right)\subset\left\{0,1\right\}$; 离散空间中任何有限子集都紧 (习题六), 故 $f$ 保持紧集; 但 $x_n=1/n\to0$ 时 $f\left(x_n\right)=1$ 不趋于 $f\left(0\right)=0$, 由**定义 3.25** (邻域与极限) $f$ 不连续. 可见单射不可少. $\blacksquare$

### 习题十二

设 $X$ 是紧豪斯多夫空间. 证明锥空间 $CX$ 同胚于 $X\times\left[0,1\right)$ 的单点紧化. 若 $A\subset X$ 闭, 证明 $X/\left\langle A\right\rangle$ 同胚于 $X\setminus A$ 的单点紧化.

### 解答 习题十二

**第一问**: 由**定义 11.6** (锥, Armstrong 第4章), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$, 商映射 $\pi:X\times\left[0,1\right]\to CX$ 把 $X\times\left\{1\right\}$ 捏成一点, 在 $X\times\left[0,1\right)$ 上单射 (划分 (b) 为单点类). 令 $Y=X\times\left[0,1\right)$. $Y$ 豪斯多夫: 由**定理 3.6** (豪斯多夫的遗传性), $X$ 豪斯多夫 (题设), $\left[0,1\right)$ 是度量空间 $\mathbb R$ 的子空间故豪斯多夫 (由**教材 §6** (度量空间是豪斯多夫的) 与**定理 3.6**), 乘积仍豪斯多夫. $Y$ 局部紧 (按**定义 7.4** (局部紧空间) 中 Munkres §29 的表述): 对 $\left(x,t\right)\in Y$, 取 $t'$ 使 $t< t'< 1$; $\left[0,t'\right]\subset\mathbb R$ 闭且有界, 由**定理 5.3** 紧, $X$ 紧 (题设), 由**定理 5.7** (有限乘积紧) $X\times\left[0,t'\right]$ 紧; 它含 $\left(x,t\right)$ 的开邻域 $X\times\left(0,t'\right)$, 故是 $\left(x,t\right)$ 的紧邻域. 由**定义 7.5** (单点紧化), $Y^*=Y\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(Y\setminus K\right)\cup\left\{\infty\right\}$, $K\subset Y$ 紧.

构造双射 $\psi:CX\to Y^*$: 令 $\psi\left(\left[\left(x,t\right)\right]\right)=\left(x,t\right)$ 对 $t< 1$, $\psi\left(\left[\left(x,1\right)\right]\right)=\infty$. 由**定义 11.6** (锥) 的划分 (a)(b), 每个类恰为 $X\times\left\{1\right\}$ 或单点 $\left\{\left(x,t\right)\right\}$, 故 $\psi$ 是双射.

$\psi$ 连续: 由**定义 11.2** (商拓扑), 只需证对 $Y^*$ 的每个开集 $W$, $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)$ 在 $X\times\left[0,1\right]$ 中开. 若 $\infty\notin W$, 则 $W$ 是 $Y$ 中开集; $Y$ 是 $X\times\left[0,1\right]$ 的开子集 (其补 $X\times\left\{1\right\}$ 闭), 故 $W$ 在 $X\times\left[0,1\right]$ 中开, 且 $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)=W$. 若 $\infty\in W$, 则 $W=\left(Y\setminus K\right)\cup\left\{\infty\right\}$ 其中 $K\subset Y$ 紧 (由**定义 7.5**); $X\times\left[0,1\right]$ 豪斯多夫 (由**定理 3.6**), 由**定理 5.5** (豪斯多夫中紧集闭) $K$ 闭, 故 $\pi^{-1}\left(\psi^{-1}\left(W\right)\right)=\left(X\times\left[0,1\right]\right)\setminus K$ 开. 故 $\psi$ 连续.

$CX$ 紧: $X\times\left[0,1\right]$ 是紧空间之积 ($X$ 紧, $\left[0,1\right]$ 闭有界由**定理 5.3** 紧), 由**定理 5.7** (有限乘积紧) 紧; 商映射 $\pi$ 连续 (由**定义 11.2**), 由**定理 5.1** (紧空间连续像紧) $CX$ 紧.

$Y^*$ 豪斯多夫: 若 $\left(x,t\right)\neq\left(y,s\right)$ 皆非 $\infty$, 由 $Y$ 豪斯多夫取 $Y$ 中不相交开邻域 $U,V$; $U,V$ 不含 $\infty$, 由**定义 7.5** 它们在 $Y^*$ 中仍开. 对 $\infty$ 与 $\left(x,t\right)$: 取 $t'$ 使 $t< t'< 1$, 令 $K=X\times\left[0,t'\right]$ (紧, 如上); 则 $U=X\times\left(0,t'\right)$ 是 $\left(x,t\right)$ 的开邻域, $\left(Y\setminus K\right)\cup\left\{\infty\right\}=X\times\left(t',1\right)\cup\left\{\infty\right\}$ 是 $\infty$ 的邻域 (由**定义 7.5**), 且 $U\cap\left(Y\setminus K\right)=\emptyset$. 故 $Y^*$ 豪斯多夫.

由**定理 5.6** (紧豪斯多夫间的连续双射), $\psi$ 是同胚. 第一问得证.

**第二问**: 由**定义 11.12** (塌缩商), $X/\left\langle A\right\rangle$ 把闭集 $A$ 整捏成一点 $\left\langle A\right\rangle$, 商映射 $\pi$ 在 $Z=X\setminus A$ 上单射; 由**定义 11.2** (商拓扑), $\pi$ 连续. $Z$ 豪斯多夫: $X$ 豪斯多夫 (题设), 由**定理 3.6** 子空间仍豪斯多夫. $Z$ 局部紧 (按**定义 7.4** 中 Munkres §29 的表述): 对 $x\in Z$, 由**定义 3.10** (豪斯多夫空间), 对每个 $a\in A$ 有不相交开集 $U_a\ni x$, $V_a\ni a$; $A$ 是紧空间 $X$ 的闭子集, 由**定理 5.4** 紧, 故 $A\subset\bigcup_{i=1}^{m}V_{a_i}$ 对某个有限子族成立; 令 $U=\bigcap_{i=1}^{m}U_{a_i}$, 由**定义 3.18** $U$ 是含 $x$ 的开集且 $U\cap A=\emptyset$. 由**定义 3.26** (闭包), $\overline U\subset X\setminus\bigcup_{i=1}^{m}V_{a_i}\subset Z$ ($X\setminus\bigcup_i V_{a_i}$ 闭且含 $U$); $\overline U$ 是紧空间 $X$ 的闭子集, 由**定理 5.4** 紧, 且是 $x$ 的紧邻域 (含 $x$ 的开邻域 $U$, 而 $U$ 在 $Z$ 中开). 故 $Z$ 局部紧.

构造双射 $\phi:X/\left\langle A\right\rangle\to Z^*$: 令 $\phi\left(\left[x\right]\right)=x$ 对 $x\in Z$, $\phi\left(\left\langle A\right\rangle\right)=\infty$. 由**定义 11.12** 的划分 ($A$ 整捏为一点, 其余单点), $\phi$ 是双射.

$\phi$ 连续: 对 $Z^*$ 的开集 $W$, 若 $\infty\notin W$, 则 $W$ 在 $Z$ 中开; $Z=X\setminus A$ 是 $X$ 的开子集 ($A$ 闭, 定义 3.27), 故 $W$ 在 $X$ 中开, 且 $\pi^{-1}\left(\phi^{-1}\left(W\right)\right)=W$ 开. 若 $\infty\in W$, 则 $W=\left(Z\setminus K\right)\cup\left\{\infty\right\}$ 其中 $K\subset Z$ 紧 (由**定义 7.5**); $X$ 豪斯多夫, 由**定理 5.5** $K$ 在 $X$ 中闭, 故 $\pi^{-1}\left(\phi^{-1}\left(W\right)\right)=X\setminus K$ 开. 由**定义 11.2**, $\phi$ 连续.

$X/\left\langle A\right\rangle$ 紧: $\pi$ 连续, $X$ 紧, 由**定理 5.1** (紧空间连续像紧). $Z^*$ 豪斯多夫: 两点皆非 $\infty$ 时由 $Z$ 豪斯多夫及**定义 7.5** (不含 $\infty$ 的开集在 $Z^*$ 中开); 对 $\infty$ 与 $x\in Z$, 取上面的开集 $U$ 与紧集 $\overline U$, 则 $U$ 与 $\left(Z\setminus\overline U\right)\cup\left\{\infty\right\}$ 不相交 ($U\subset\overline U$), 后者是 $\infty$ 的邻域 (由**定义 7.5**). 由**定理 5.6** (紧豪斯多夫间的连续双射), $\phi$ 是同胚. $\blacksquare$

### 习题十三

(扎里斯基紧不蕴含扎里斯基闭) 在 $\mathbb A^1\left(\mathbb R\right)=\mathbb R$ 上配**定义 3.28** (扎里斯基拓扑), 即余有限拓扑. 证明子集 $\left(0,1\right)$ 在扎里斯基拓扑下紧但不闭.

### 解答 习题十三

扎里斯基拓扑下, 由**定义 3.28** (扎里斯基拓扑), 闭集为有限集或全空间 ($n=1$ 时多项式零点集即有限集或全空间); 由**定义 3.27** (闭集), 开集为余有限集或空集.

**紧**: 任取 $\left(0,1\right)$ 的开覆盖 $\left\{U_i\right\}$. 取其中一个非空开集 $U_0$; 由余有限性, $\mathbb R\setminus U_0$ 有限, 故 $\left(0,1\right)\setminus U_0$ 至多有限个点, 每个点再选一个覆盖元覆盖. 即得有限子覆盖. 由**定义 5.16** (紧致空间), $\left(0,1\right)$ 紧.

**不闭**: $\mathbb R\setminus\left(0,1\right)=\left(-\infty,0\right]\cup\left[1,\infty\right)$ 是无限集, 不是有限集, 故不是扎里斯基闭集; 因而由**定义 3.27** (闭集) 它的补集 $\left(0,1\right)$ 不是扎里斯基开集的补, 即 $\left(0,1\right)$ 不闭. 故紧不蕴含闭. $\blacksquare$

### 习题十四

(单点紧化) 回顾**定义 7.5** (单点紧化). 证明 $\mathbb R$ 的单点紧化同胚于单位圆 $S^1$.

### 解答 习题十四

由**定义 7.5** (单点紧化), $\mathbb R^*=\mathbb R\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(\mathbb R\setminus K\right)\cup\left\{\infty\right\}$, 其中 $K\subset\mathbb R$ 紧, 由**定理 5.3** 即闭有界集.

先证 $\mathbb R^*$ 紧: 任取开覆盖 $\mathcal U$, 取 $U_\infty\in\mathcal U$ 含 $\infty$. 由**定义 7.5**, $U_\infty\supset\left(\mathbb R\setminus K'\right)\cup\left\{\infty\right\}$ 对某紧集 $K'$; 于是 $K=\mathbb R\setminus U_\infty\subset K'$ 且 $K$ 闭 ($U_\infty$ 开), 由**定理 5.4** (闭子集紧) $K$ 紧. 同习题五的论证, $K$ 被 $\mathcal U\setminus\left\{U_\infty\right\}$ 中有限个集合覆盖, 故 $\mathcal U$ 有有限子覆盖; 由**定义 5.16** (紧致空间), $\mathbb R^*$ 紧.

球极投影 $\sigma:\mathbb R\to S^1\setminus\left\{N\right\}$ ($N=\left(0,1\right)$ 为北极) 由公式 $\sigma\left(x\right)=\left(\frac{2x}{x^2+1},\frac{x^2-1}{x^2+1}\right)$ 给出, 是连续双射, 其逆 $\left(X,Y\right)\mapsto\frac{X}{1-Y}$ 也连续, 故 $\sigma$ 是同胚 (双向连续的双射即同胚).

$S^1$ 是 $\mathbb R^2$ 的闭有界子集, 由**定理 5.3** 紧; $\mathbb R^2$ 是度量空间 (由**定义 6.35**), 由**教材 §6** (度量空间是豪斯多夫的) 豪斯多夫, 故 $S^1$ 作为子空间由**定理 3.6** (豪斯多夫的遗传性) 豪斯多夫.

定义 $F:\mathbb R^*\to S^1$: $F\left(x\right)=\sigma\left(x\right)$ 对 $x\in\mathbb R$, $F\left(\infty\right)=N$. $F$ 是双射 ($\sigma$ 双射到 $S^1\setminus\left\{N\right\}$, $\infty\leftrightarrow N$). $F$ 连续: 对不含 $N$ 的开集 $W\subset S^1$, $F^{-1}\left(W\right)=\sigma^{-1}\left(W\right)$ 是 $\mathbb R$ 中开集 ($\sigma$ 同胚); $\mathbb R$ 是 $\mathbb R^*$ 的开子集 (由**定义 7.5**: $\mathbb R\cap\mathbb R=\mathbb R$ 开且 $\infty\notin\mathbb R$), 故 $F^{-1}\left(W\right)$ 在 $\mathbb R^*$ 中开. 对含 $N$ 的开集 $W\subset S^1$, $S^1\setminus W$ 闭于紧 $S^1$, 由**定理 5.5** (豪斯多夫中紧集闭) 紧, 故 $K=\sigma^{-1}\left(S^1\setminus W\right)$ 是 $\mathbb R$ 中紧集 (由**定理 5.1**, $\sigma$ 连续); 于是 $F^{-1}\left(W\right)=\left(\mathbb R\setminus K\right)\cup\left\{\infty\right\}$, 它是 $\infty$ 的邻域 (由**定义 7.5**), 且在 $\mathbb R^*$ 中开: 其与 $\mathbb R$ 之交 $\mathbb R\setminus K$ 开 ($K$ 紧, 由**定理 5.5** 闭), 其补 $K$ 紧. 故 $F$ 连续.

由**定理 5.6** (紧豪斯多夫间的连续双射), $F$ 是同胚, 即 $\mathbb R$ 的单点紧化同胚于 $S^1$. $\blacksquare$

### 习题十五

(2024 年卷 C 题目二, 40 分). 考虑一个度量空间 $X$, 使得其中任意无穷子集都有一个极限点.

(1) (10 分) 证明对于任意的 $\delta> 0$, $X$ 能被有限个半径为 $\delta$ 的小球覆盖.

(2) (10 分) 证明 $X$ 是可分度量空间, 即 $X$ 中有一个可数稠密子集.

(3) (10 分) 证明 $X$ 有一个可数的基, 即存在可数个 $X$ 中的开集 $V_\alpha$, 使得任意 $X$ 的开集都是一些 $V_\alpha$ 之并.

(4) (10 分) 证明 $X$ 是一个紧致空间, 即任意 $X$ 的开覆盖都有一个有限子覆盖.

(5) (附加题, 10 分) 证明一个紧致度量空间 $K$ 一定是可分的.

### 解答 习题十五

(1) 固定 $\delta> 0$. 依次选 $x_1,x_2,\dots$ 使 $d\left(x_i,x_j\right)\ge\delta$ ($i\neq j$). 若此过程无穷, $\left\{x_i\right\}$ 是无穷集, 由题设有极限点 $x$. 由**定义 3.24** (极限点), 开球 $B\left(x,\frac\delta2\right)$ 含 $S\setminus\left\{x\right\}$ 的无穷多点: 若仅含有限个, 取 $r$ 小于这些点到 $x$ 的距离, 则 $B\left(x,r\right)$ 与 $S\setminus\left\{x\right\}$ 无交, 与极限点定义矛盾. 取其中两个不同点 $x_i,x_j$, 由三角不等式 (由**定义 6.35**) $d\left(x_i,x_j\right)\le d\left(x_i,x\right)+d\left(x,x_j\right)< \delta$, 与 $d\left(x_i,x_j\right)\ge\delta$ 矛盾. 故过程有限停止, 得 $x_1,\dots,x_m$, 且 $\bigcup_{i=1}^m B\left(x_i,\delta\right)=X$ (否则可再选一点), 即有限 $\delta$-覆盖. 由**定义 6.42** (完全有界), $X$ 完全有界.

(2) 对每个 $n$, 由第 1 小题取半径 $1/n$ 的有限覆盖球心集 $C_n$. 令 $C=\bigcup_{n\ge1}C_n$, 它可数 (可数个有限集之并). 任取 $x$ 与 $r> 0$, 取 $n$ 使 $1/n< r$, 存在 $c\in C_n$ 使 $d\left(x,c\right)< 1/n< r$, 即 $c\in B\left(x,r\right)$. 故 $x$ 的每个开球邻域都与 $C$ 相交; 开球构成度量拓扑的基 (由**定义 6.36**), 故 $x$ 的每个邻域都与 $C$ 相交, 由**定义 3.24** (极限点) 与**定理 3.5** (闭包与极限点) $x\in\overline C$. 因 $x$ 任意, $\overline C=X$, 由**定义 3.32** (稠密) $C$ 稠密. 由**定义 3.9** (可分) $X$ 可分.

(3) 令 $\mathcal B=\left\{B\left(c,q\right):c\in C,\ q\in\mathbb Q_{> 0}\right\}$. 它可数 ($C$ 可数, $\mathbb Q_{> 0}$ 可数). 验证它是基: 任取开集 $U$ 与 $x\in U$, 由**定义 6.36** (度量拓扑) 存在 $r> 0$ 使 $B\left(x,r\right)\subset U$. 由 $C$ 稠密取 $c\in C$ 使 $d\left(x,c\right)< r/3$ (由**定义 3.32** 与**定义 3.26**), 再取有理数 $q$ 使 $d\left(x,c\right)< q< r/3$. 则 $x\in B\left(c,q\right)$ (因 $d\left(x,c\right)< q$), 且 $B\left(c,q\right)\subset B\left(x,r\right)\subset U$ (对 $z\in B\left(c,q\right)$, 由三角不等式 (定义 6.35) $d\left(x,z\right)\le d\left(x,c\right)+d\left(c,z\right)< r/3+q< r$). 故 $U$ 是 $\mathcal B$ 中元素之并; 由**定义 3.15** (拓扑基), $\mathcal B$ 是可数基.

(4) 设 $\left\{U_\alpha\right\}$ 是任意开覆盖. 由第 3 小题的可数基 $\mathcal B=\left\{V_\beta\right\}$, 每个开集是基元素之并 (定义 3.15); 对每个基元素 $V_\beta$, 若存在覆盖元 $U\supset V_\beta$ 则取定其一记为 $G_\beta$, 则 $\left\{G_\beta\right\}$ 可数且仍覆盖 $X$ (每个 $x\in X$ 在某 $U$ 中, $x$ 又在其某基元素 $V_\beta\subset U$ 中, 该 $V_\beta$ 被 $G_\beta$ 覆盖). 将 $\left\{G_\beta\right\}$ 编号为 $G_1,G_2,\dots$. 反证无有限子覆盖: 取 $x_n\notin G_1\cup\dots\cup G_n$. 集合 $\left\{x_n\right\}$ 无穷 (各 $x_n$ 互异), 由题设有极限点 $x$. 因 $\left\{G_n\right\}$ 覆盖 $X$, 存在 $N$ 使 $x\in G_N$. 由**定义 6.36**, $G_N$ 含开球 $B\left(x,r\right)$, 由第 1 小题的论证 $B\left(x,r\right)$ 含 $S\setminus\left\{x\right\}$ 的无穷多点, 故 $G_N$ 含无穷多个 $x_n$. 但对 $n\ge N$, $x_n\notin G_1\cup\dots\cup G_n\supset G_N$, 故 $G_N$ 至多含 $x_1,\dots,x_{N-1}$ 有限个, 矛盾. 故存在有限子覆盖, 由**定义 5.16** (紧致空间) $X$ 紧.

(5) 设 $K$ 紧. 对每个 $n$, 由**定义 5.16** (紧致空间), 开覆盖 $\left\{B\left(x,1/n\right):x\in K\right\}$ 有有限子覆盖, 取其球心集 $C_n$. 令 $C=\bigcup_n C_n$, 可数. 任取 $x\in K$ 与 $r> 0$, 取 $n$ 使 $1/n< r$, 有限覆盖给出 $c\in C_n$ 使 $d\left(x,c\right)< 1/n< r$, 故 $x$ 的每个开球邻域都与 $C$ 相交; 由**定义 3.32** (稠密) 与**定理 3.5** $C$ 在 $K$ 中稠密. 由**定义 3.9** (可分), $K$ 可分. $\blacksquare$
