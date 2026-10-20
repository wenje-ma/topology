# 作业 6

> **定理 3.6** (豪斯多夫的遗传性)<br>两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 3.15** (拓扑基)<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$)

> **定义 3.25** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$)

> **定义 3.28** (扎里斯基拓扑)<br>设 $K$ 为域, $\mathbb A^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in I}$ 的公共零点集 $\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4** (闭子集紧)<br>若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **定理 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定理 5.9** (吉洪诺夫定理)<br>任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.11** (紧空间上连续函数取最大值)<br>紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 5.15** (开覆盖与有限子覆盖)<br>开覆盖 $\left\{U_i\right\}$ 满足 $X=\bigcup_i U_i$; 有限子覆盖为仍覆盖 $X$ 的有限子族. (教材 $\S5$)

> **定义 5.16** (紧致空间)<br>称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.36** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.40** (序列紧致)<br>称 $X$ 是序列紧致的, 若 $X$ 中每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.42** (完全有界)<br>对每个 $r>0$, $X$ 可被有限个半径 $r$ 的球覆盖. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.4** (局部紧空间)<br>豪斯多夫空间且每点有紧邻域基. (教材 $\S7$)

> **定义 7.5** (单点紧化)<br>亚历山德罗夫紧化 $\overline X=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset X$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

> **定义 11.6** (锥)<br>$CX=X\times\left[0,1\right]/X\times\left\{1\right\}$, 即将 $X\times\left\{1\right\}$ 整捏成一点. (教材 $\S11$)

> **定义 11.12** (塌缩商)<br>$X/\left\langle A\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 $\S5$)

### 习题一

证明 $\left\{0,1\right\}^{\left[0,1\right]}$ 赋通常乘积拓扑不是序列紧致的.

### 解答 习题一

把 $\left\{0,1\right\}^{\left[0,1\right]}$ 中的点视为函数 $f:\left[0,1\right]\to\left\{0,1\right\}$. 由**定义 3.11** (乘积拓扑), 在乘积拓扑下 $f_n\to f$ 当且仅当每个坐标 $t\in\left[0,1\right]$ 都有 $f_n\left(t\right)\to f\left(t\right)$.

对每个 $n\ge1$, 定义 $f_n\left(t\right)$ 为 $t$ 的二进制展开中小数点后第 $n$ 位数字 (二进有理点固定取其一展开). 任取严格递增的正整数列 $n_1<n_2<\dots$, 我们证明 $\left\{f_{n_k}\right\}$ 不收敛. 取 $t^{*}\in\left[0,1\right]$, 使其二进制展开在第 $n_{2k-1}$ 位为 $0$, 在第 $n_{2k}$ 位为 $1$, 其余位任意 (例如取 $0$). 则坐标 $t^{*}$ 处 $f_{n_k}\left(t^{*}\right)$ 依次为 $0,1,0,1,\dots$, 不收敛. 由上一段的坐标判据, $\left\{f_{n_k}\right\}$ 在乘积拓扑下不收敛. 由**定义 6.40** (序列紧致), 任意子列都不收敛, 故 $\left\{0,1\right\}^{\left[0,1\right]}$ 不是序列紧致的.

### 习题二

称集合族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空. 证明: 空间 $X$ 紧致等价于, $X$ 中任意具有限交性质的闭集族 $\mathcal F$ 都满足 $\bigcap_{F\in\mathcal F}F\neq\emptyset$.

### 解答 习题二

由**定义 5.15** (开覆盖与有限子覆盖) 与**定义 5.16** (紧致空间), 分两个方向证明.

($\Rightarrow$) 设 $X$ 紧致, $\mathcal F$ 是具有限交性质的闭集族. 若 $\bigcap_{F\in\mathcal F}F=\emptyset$, 则 $\left\{X\setminus F:F\in\mathcal F\right\}$ 是 $X$ 的开覆盖 (闭集之补为开). 由**定义 5.16** (紧致空间), 它有有限子覆盖 $X\setminus F_1,\dots,X\setminus F_k$, 即 $X=\bigcup_{i=1}^{k}\left(X\setminus F_i\right)$. 取补集得 $\bigcap_{i=1}^{k}F_i=\emptyset$, 与**定义 5.17** (有限交性质) 矛盾. 故全族之交非空.

($\Leftarrow$) 设任意具有限交性质的闭集族之交非空. 任取 $X$ 的开覆盖 $\left\{U_i\right\}$. 令 $F_i=X\setminus U_i$, 则各 $F_i$ 闭. 若 $\left\{U_i\right\}$ 无有限子覆盖, 则任意有限个 $F_{i_1},\dots,F_{i_k}$ 满足

$$
\bigcap_{j=1}^{k}F_{i_j}=X\setminus\bigcup_{j=1}^{k}U_{i_j}\neq\emptyset,
$$

即 $\left\{F_i\right\}$ 具有限交性质. 由假设 $\bigcap_iF_i\neq\emptyset$, 即 $X\setminus\bigcup_iU_i\neq\emptyset$, 与 $\left\{U_i\right\}$ 覆盖 $X$ 矛盾. 故存在有限子覆盖, 由**定义 5.16** (紧致空间), $X$ 紧致. $\blacksquare$

### 习题三

设 $A,B$ 是度量空间 $\left(X,d\right)$ 中不相交的闭集, 且 $A$ 紧致. 证明 $d\left(A,B\right)>0$.

### 解答 习题三

令 $g\left(x\right)=d\left(x,B\right)$. 由**定义 6.46** (点到集合的距离), $g$ 有定义. 由**定义 6.35** (度量空间) 的三角不等式, $\left|d\left(x,B\right)-d\left(y,B\right)\right|\le d\left(x,y\right)$, 故 $g$ 连续. 因 $A$ 紧致, 由**定理 5.11** (紧空间上连续函数取最大值), $g$ 在 $A$ 上取到最小值

$$
m=\min_{a\in A}g\left(a\right)=\inf_{a\in A,\,b\in B}d\left(a,b\right)=d\left(A,B\right).
$$

若 $m=0$, 则存在 $a_0\in A$ 使 $d\left(a_0,B\right)=0$, 即 $a_0$ 是 $B$ 的极限点; 但 $B$ 是闭集, 故 $a_0\in B$, 与 $A\cap B=\emptyset$ 矛盾. 故 $m>0$, 即 $d\left(A,B\right)>0$. $\blacksquare$

### 习题四

设 $\left(X,d\right)$ 是无孤立点的度量空间. 证明: $X$ 紧致当且仅当对任意一对不相交闭集 $A,B$, 都有 $d\left(A,B\right)>0$.

### 解答 习题四

($\Rightarrow$) 设 $X$ 紧致, $A,B$ 为不相交闭集. 由**定理 5.4** (闭子集紧), $A$ 紧致. 由习题三的论证 (连续函数 $d\left(\cdot,B\right)$ 在 $A$ 上取到正最小值) 即得 $d\left(A,B\right)>0$.

($\Leftarrow$) 反证, 设 $X$ 不紧致. 由**定理 6.1** (紧=序列紧), $X$ 不是序列紧致的, 故存在序列 $\left\{x_n\right\}$ 无收敛子列. 必要时取子列使 $x_n$ 两两不同. 于是 $S=\left\{x_n:n\ge1\right\}$ 无极限点, 故 $S$ 闭 (否则其极限点给出收敛子列). 因 $X$ 无孤立点, 每个 $x_n$ 的任意邻域都含异于 $x_n$ 的点; 归纳地选取 $y_n$, 使 $0<d\left(y_n,x_n\right)<1/n$, 且 $y_n\notin S\cup\left\{y_1,\dots,y_{n-1}\right\}$. 则 $\left\{y_n\right\}$ 也无收敛子列: 若 $y_{n_k}\to y$, 则由**定义 6.35** (度量空间) 的三角不等式,

$$
d\left(x_{n_k},y\right)\le d\left(x_{n_k},y_{n_k}\right)+d\left(y_{n_k},y\right)\to0,
$$

与 $\left\{x_n\right\}$ 无收敛子列矛盾. 故 $T=\left\{y_n:n\ge1\right\}$ 也闭. 令 $A=S$, $B=T$, 则二者不相交闭, 但对一切 $n$ 有 $d\left(A,B\right)\le d\left(x_n,y_n\right)<1/n$, 故 $d\left(A,B\right)=0$, 与假设矛盾. 因此 $X$ 紧致. $\blacksquare$

### 习题五

考虑 $\mathbb C$ 与一个无穷远点 $\left\{\infty\right\}$. 记 $\overline{\mathbb C}=\mathbb C\cup\left\{\infty\right\}$, 规定 $U\subset \overline{\mathbb C}$ 的拓扑为: 若 $\infty\notin U$, 则 $U$ 开当且仅当它是 $\mathbb C$ 中通常开集; 若 $\infty\in U$, 则 $U$ 开当且仅当 $\mathbb C\setminus\left(U\cap\mathbb C\right)$ 在 $\mathbb C$ 中紧致. 证明 $\overline{\mathbb C}$ 紧致. 此即亚历山德罗夫单点紧化, $\overline{\mathbb C}$ 称为黎曼球面.

### 解答 习题五

由**定义 7.5** (单点紧化), $\overline{\mathbb C}$ 正是 $\mathbb C$ 的单点紧化. 任取 $\overline{\mathbb C}$ 的开覆盖 $\mathcal U$. 取 $U_\infty\in\mathcal U$ 使 $\infty\in U_\infty$. 由拓扑定义, $K=\mathbb C\setminus\left(U_\infty\cap\mathbb C\right)$ 在 $\mathbb C$ 中紧致. 族

$$
\left\{U\cap\mathbb C:U\in\mathcal U\setminus\left\{U_\infty\right\}\right\}
$$

中每个集合是 $\mathbb C$ 中开集 (不含 $\infty$ 的开集在 $\overline{\mathbb C}$ 与在 $\mathbb C$ 中同样开), 且它们覆盖 $K$. 由 $K$ 紧致, 即由**定义 5.16** (紧致空间), 有有限子族 $U_1,\dots,U_m$ 使 $K\subset\bigcup_{i=1}^{m}U_i$. 于是 $U_\infty,U_1,\dots,U_m$ 覆盖 $\overline{\mathbb C}$: $U_\infty$ 含 $\infty$ 与 $U_\infty\cap\mathbb C$, 其余集合覆盖 $K$. 故 $\overline{\mathbb C}$ 的任意开覆盖都有有限子覆盖, 由**定义 5.16** (紧致空间), $\overline{\mathbb C}$ 紧致. $\blacksquare$

### 习题六

给 $\left\{1,\dots,k\right\}$ 赋离散拓扑. 证明 $\left\{1,\dots,k\right\}$ 在该拓扑下紧致.

### 解答 习题六

设 $\mathcal U$ 是 $\left\{1,\dots,k\right\}$ 的任意开覆盖. 由**定义 5.15** (开覆盖与有限子覆盖), 对每个点 $i\in\left\{1,\dots,k\right\}$ 选取 $U_i\in\mathcal U$ 使 $i\in U_i$. 则 $\left\{U_1,\dots,U_k\right\}$ 是有限子族且仍覆盖 $\left\{1,\dots,k\right\}$. 由**定义 5.16** (紧致空间), $\left\{1,\dots,k\right\}$ 紧致. $\blacksquare$

> 离散拓扑: 每个点自己就是开集, 开集的并也是开集, 这么说每个点又都是闭集, 所以每个点都是开闭集.

### 习题七

用吉洪诺夫定理证明: 映射集合 $X=\left\{f:V\to\left\{1,\dots,k\right\}\right\}$ 紧致.

### 解答 习题七

集合 $X=\left\{1,\dots,k\right\}^{V}=\prod_{v\in V}\left\{1,\dots,k\right\}$ 是离散有限空间 $\left\{1,\dots,k\right\}$ 的乘积. 由习题一, 每个因子紧致. 由**定理 5.9** (吉洪诺夫定理), 乘积 $X$ 在乘积拓扑下紧致. $\blacksquare$

### 习题八

设 $X,Y$ 是度量空间, $f:X\to Y$. 证明: $f$ 连续当且仅当 $f$ 在任意紧子集 $K\subset X$ 上的限制都连续.

### 解答 习题八

($\Rightarrow$) 显然, 连续映射的限制仍连续.

($\Leftarrow$) 反证, 设 $f$ 在某点 $x$ 不连续. 在**定义 6.35** (度量空间) 下, 连续性有序列判据: 存在 $x_n\to x$ 使 $f\left(x_n\right)\not\to f\left(x\right)$. 集合 $K=\left\{x\right\}\cup\left\{x_n\right\}$ 紧致: 任取开覆盖, 取含 $x$ 的开集, 它含除有限个外的所有 $x_n$, 其余有限个点再各取一个覆盖元, 得有限子覆盖. 由假设 $f|_K$ 连续, 故 $x_n\to x$ 时应有 $f\left(x_n\right)\to f\left(x\right)$, 矛盾. 因此 $f$ 处处连续. $\blacksquare$

### 习题九

设 $X$ 是豪斯多夫空间. 证明: $X$ 局部紧 (即每点有紧邻域基) 当且仅当每点有一个紧邻域.

### 解答 习题九

($\Rightarrow$) 由**定义 7.4** (局部紧空间), 紧邻域基中任一元即紧邻域.

($\Leftarrow$) 设 $x$ 有紧邻域 $K$. 任取 $x$ 的邻域 $U$. $K$ 紧致, 由**定理 5.5** (豪斯多夫中紧集闭), $K$ 闭. 取 $x$ 的开邻域 $V$ 使 $V\subset U\cap\operatorname{int}\left(K\right)$. 则 $\overline V\cap K$ 是 $K$ 的闭子集, 由**定理 5.4** (闭子集紧), 它紧致, 且含 $x$ 的邻域 $V$. 故 $x$ 有由紧集组成的邻域基, 由**定义 7.4** (局部紧空间), $X$ 局部紧. $\blacksquare$

### 习题十

(维数与紧性) 证明: 任意实赋范线性空间的单位球紧致, 当且仅当该空间维数有限.

### 解答 习题十

设 $E$ 是**定义 6.20** (赋范线性空间).

($\Leftarrow$) 有限维时 $E\cong\mathbb R^n$, 单位球闭且有界, 由**定理 5.3** ($\mathbb R^n$ 中的紧集), 它紧致.

($\Rightarrow$) 反之, 若 $E$ 无穷维, 由**定理 6.17** (里茨定理), 其闭单位球非紧. 故单位球紧致蕴含维数有限. $\blacksquare$

### 习题十一

设 $E,F$ 是两个度量空间, $f:E\to F$ 是单射.

(1) 证明: $f$ 连续当且仅当对每个紧集 $K\subset E$, 像集 $f\left(K\right)$ 在 $F$ 中是紧集;

(2) 举例说明若 $f$ 不单射, 上述等价可以失效.

### 解答 习题十一

(1) $\left(\Rightarrow\right)$ 设 $f$ 连续, $K\subset E$ 紧. 由**定理 5.1** (紧空间连续像紧), $f\left(K\right)$ 紧.

   $\left(\Leftarrow\right)$ 设对每个紧集 $K\subset E$, $f\left(K\right)$ 紧. 反设 $f$ 在某点 $x$ 不连续. 由**定义 3.25** (邻域与极限), 存在 $\epsilon>0$ 与序列 $x_n\to x$ 使 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\epsilon$. 由 $f$ 单射及 $d_F\left(f\left(x_n\right),f\left(x\right)\right)\ge\epsilon>0$ 知 $x_n\neq x$. 令 $K=\left\{x\right\}\cup\left\{x_n:n\ge1\right\}$, 它是收敛序列加极限, 故紧. 由假设 $f\left(K\right)$ 紧; 度量空间是**定义 3.10** (豪斯多夫空间), 由**定理 5.5** (豪斯多夫中紧集闭), $f\left(K\right)$ 在 $F$ 中闭.

   由**定理 6.1** (紧=序列紧), $f\left(x_n\right)$ 在紧集 $f\left(K\right)$ 中有收敛子列 $f\left(x_{n_j}\right)\to y\in f\left(K\right)$. 设 $y=f\left(z\right)$, $z\in K$. 若 $z=x$, 则 $f\left(x_{n_j}\right)\to f\left(x\right)$, 与 $d_F\left(f\left(x_{n_j}\right),f\left(x\right)\right)\ge\epsilon$ 矛盾. 故 $z=x_m$ 是某固定项. 取尾部紧集 $K'=\left\{x\right\}\cup\left\{x_{n_j}:j>m\right\}$. 由假设 $f\left(K'\right)$ 紧, 再由**定理 5.5** (豪斯多夫中紧集闭) $f\left(K'\right)$ 闭. 但 $f\left(x_{n_j}\right)\to f\left(x_m\right)$ 且 $x_m\notin K'$, 由 $f$ 单射 $f\left(x_m\right)\notin f\left(K'\right)$, 与 $f\left(K'\right)$ 闭矛盾. 故 $f$ 连续.

(2) 取 $E=\left\{0\right\}\cup\left\{1/n:n\ge1\right\}$, $F=\left\{0,1\right\}$ 装备离散度量, $f\left(0\right)=0$, $f\left(1/n\right)=1$ 对一切 $n$. $f$ 不单射. $E$ 中任何紧集 (即 $E$ 的子集) 的像为 $\left\{0\right\}$, $\left\{1\right\}$ 或 $\left\{0,1\right\}$, 在离散空间中皆紧, 故 $f$ 保持紧集; 但 $x_n=1/n\to0$ 时 $f\left(x_n\right)=1$ 不趋于 $f\left(0\right)=0$, 由**定义 3.25** (邻域与极限) $f$ 不连续. 可见单射不可少. $\blacksquare$

### 习题十二

设 $X$ 是紧豪斯多夫空间. 证明锥空间 $CX$ 同胚于 $X\times\left[0,1\right)$ 的单点紧化. 若 $A\subset X$ 闭, 证明 $X/\left\langle A\right\rangle$ 同胚于 $X\setminus A$ 的单点紧化.

### 解答 习题十二

**第一问**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 空间 $X\times\left[0,1\right)$ 是豪斯多夫局部紧的 (由**定理 3.6** (豪斯多夫的遗传性), $X$ 豪斯多夫, $\left[0,1\right)$ 局部紧). 因 $X$ 紧, $X$ 的紧子集皆闭, 由**定理 5.5** (豪斯多夫中紧集闭), $X$ 的闭子集皆紧. 由**定义 7.5** (单点紧化), 其单点紧化为 $\left(X\times\left[0,1\right)\right)^*=X\times\left[0,1\right)\cup\left\{\infty\right\}$.

构造双射 $\psi:CX\to\left(X\times\left[0,1\right)\right)^*$: 把 $\left[\left(x,t\right)\right]$ ($t<1$) 映到 $\left(x,t\right)$, 把被捏合点 $\left[\left(x,1\right)\right]$ 映到 $\infty$. 它连续: $CX$ 中开集在 $t<1$ 部分对应 $X\times\left[0,1\right)$ 中开集; 含被捏合点的开集对应于含 $X\times\left\{1\right\}$ 的饱和开集, 其补集在 $X\times\left[0,1\right)$ 中是紧的 (因 $X$ 紧, 投影到 $t$ 方向远离 $1$), 故对应于 $\infty$ 的标准邻域. $CX$ 紧 (连续像 $X\times\left[0,1\right]$), $\left(X\times\left[0,1\right)\right)^*$ 豪斯多夫. 由**定理 5.6** (紧豪斯多夫间的连续双射), $\psi$ 是同胚.

**第二问**: $A$ 闭于紧豪斯多夫 $X$. 由**定义 11.12** (塌缩商), $X/\left\langle A\right\rangle$ 将 $A$ 捏成一点. $X\setminus A$ 是局部紧豪斯多夫 (开子集). 类似构造: $X/\left\langle A\right\rangle\setminus\left\{\pi\left(A\right)\right\}\cong X\setminus A$, 且 $\pi\left(A\right)$ 的邻域恰为 $\left(X\setminus A\right)\setminus K$ 加 $\pi\left(A\right)$, $K$ 跑遍 $X\setminus A$ 的紧子集. $X/\left\langle A\right\rangle$ 紧, 单点紧化豪斯多夫, 由**定理 5.6** (紧豪斯多夫间的连续双射) 二者同胚. $\blacksquare$

### 习题十三

(扎里斯基紧不蕴含扎里斯基闭) 在 $\mathbb A^1\left(\mathbb R\right)=\mathbb R$ 上配**定义 3.28** (扎里斯基拓扑), 即余有限拓扑. 证明子集 $\left(0,1\right)$ 在扎里斯基拓扑下紧但不闭.

### 解答 习题十三

扎里斯基拓扑下, 由**定义 3.28** (扎里斯基拓扑), 闭集为有限集或全空间, 开集为余有限集或空集.

**紧**: 任取 $\left(0,1\right)$ 的开覆盖 $\left\{U_i\right\}$. 取其中一个非空开集 $U_0$; 由余有限性, $\mathbb R\setminus U_0$ 有限, 故 $\left(0,1\right)\setminus U_0$ 至多有限个点, 每个点再选一个覆盖元覆盖. 即得有限子覆盖. 由**定义 5.16** (紧致空间), $\left(0,1\right)$ 紧.

**不闭**: $\mathbb R\setminus\left(0,1\right)=\left(-\infty,0\right]\cup\left[1,\infty\right)$ 是无限集, 不是有限集, 故不是扎里斯基闭集; 因而它的补集 $\left(0,1\right)$ 不是扎里斯基开集的补, 即 $\left(0,1\right)$ 不闭. 故紧不蕴含闭. $\blacksquare$

### 习题十四

(单点紧化) 回顾**定义 7.5** (单点紧化). 证明 $\mathbb R$ 的单点紧化同胚于单位圆 $S^1$.

### 解答 习题十四

由**定义 7.5** (单点紧化), $\mathbb R^*=\mathbb R\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(\mathbb R\setminus K\right)\cup\left\{\infty\right\}$, $K$ 紧 (即有界闭).

构造映射 $F:\mathbb R^*\to S^1$, 把 $x\in\mathbb R$ 映到平面上圆周上的点 (球极投影), 把 $\infty$ 映到北极. 球极投影是从 $\mathbb R$ 到 $S^1\setminus\left\{\text{北极}\right\}$ 的同胚, 且 $\mathbb R$ 中"趋向无穷"对应于 $S^1$ 中趋向北极. 故 $F$ 连续双射. $\mathbb R^*$ 紧, $S^1$ 豪斯多夫, 故 $F$ 为同胚. $\blacksquare$

### 习题十五

(2024 年卷 C 题目二, 40 分). 考虑一个度量空间 $X$, 使得其中任意无穷子集都有一个极限点.

(1) (10 分) 证明对于任意的 $\delta>0$, $X$ 能被有限个半径为 $\delta$ 的小球覆盖.

(2) (10 分) 证明 $X$ 是可分度量空间, 即 $X$ 中有一个可数稠密子集.

(3) (10 分) 证明 $X$ 有一个可数的基, 即存在可数个 $X$ 中的开集 $V_\alpha$, 使得任意 $X$ 的开集都是一些 $V_\alpha$ 之并.

(4) (10 分) 证明 $X$ 是一个紧致空间, 即任意 $X$ 的开覆盖都有一个有限子覆盖.

(5) (附加题, 10 分) 证明一个紧致度量空间 $K$ 一定是可分的.

### 解答 习题十五

(1) 固定 $\delta>0$. 依次选 $x_1,x_2,\dots$ 使 $d\left(x_i,x_j\right)\ge\delta$ ($i\neq j$). 若此过程无穷, $\left\{x_i\right\}$ 是无穷集, 由题设有极限点 $x$. 由**定义 6.36** (开球), $B\left(x,\frac\delta2\right)$ 含两个不同的 $x_i,x_j$, 则 $d\left(x_i,x_j\right)<\delta$, 矛盾. 故过程有限停止, 得 $x_1,\dots,x_m$, 且 $\bigcup_{i=1}^m B\left(x_i,\delta\right)=X$ (否则可再选一点), 即有限 $\delta$-覆盖. 由**定义 6.42** (完全有界), $X$ 完全有界.

(2) 对每个 $n$, 由第 1 小题取半径 $1/n$ 的有限覆盖球心集 $C_n$. 令 $C=\bigcup_{n\ge1}C_n$, 可数. 任取 $x$ 与 $r>0$, 取 $n$ 使 $1/n<r$, 存在 $c\in C_n$ 使 $d\left(x,c\right)<1/n<r$, 即 $c\in B\left(x,r\right)$. 故 $C$ 稠密, 由**定义 3.9** (可分) $X$ 可分.

(3) 令 $\mathcal B=\left\{B\left(c,q\right):c\in C,\ q\in\mathbb Q_{>0}\right\}$. 它可数 ($C$ 可数, $\mathbb Q_{>0}$ 可数). 由**定义 3.15** (拓扑基) 验证: 任取开集 $U$ 与 $x\in U$, 存在 $r>0$ 使 $B\left(x,r\right)\subset U$ (由**定义 6.36** (开球) 度量拓扑). 由 $C$ 稠密取 $c\in C$ 使 $d\left(x,c\right)<r/3$, 再取有理数 $q$ 使 $d\left(x,c\right)<q<r/3$. 则 $x\in B\left(c,q\right)$ 且 $B\left(c,q\right)\subset B\left(x,r\right)\subset U$. 故 $U$ 是 $\mathcal B$ 中元素之并, $\mathcal B$ 是可数基.

(4) 设 $\left\{U_\alpha\right\}$ 是任意开覆盖. 由第 3 小题的可数基, 可选可数子族 $\left\{G_n\right\}$ 仍覆盖 $X$. 反证无有限子覆盖: 取 $x_n\notin G_1\cup\dots\cup G_n$. 集合 $\left\{x_n\right\}$ 无穷, 由题设有极限点 $x$. 则 $x\in G_N$ 对某个 $N$. 但 $G_N$ 是开集, 作为极限点它含无穷多个 $x_n$; 而对 $n\ge N$, $x_n\notin G_1\cup\dots\cup G_n\supset G_N$, 故 $G_N$ 至多含 $x_1,\dots,x_{N-1}$ 有限个, 矛盾. 故存在有限子覆盖, 由**定义 5.16** (紧致空间) $X$ 紧.

(5) 设 $K$ 紧. 对每个 $n$, 由**定义 5.16** (紧致空间), 开覆盖 $\left\{B\left(x,1/n\right):x\in K\right\}$ 有有限子覆盖, 取其球心集 $C_n$. 令 $C=\bigcup_n C_n$, 可数. 任取 $x\in K$ 与 $r>0$, 取 $n$ 使 $1/n<r$, 有限覆盖给出 $c\in C_n$ 使 $d\left(x,c\right)<1/n<r$, 故 $C$ 稠密. 由**定义 3.9** (可分), $K$ 可分. $\blacksquare$
