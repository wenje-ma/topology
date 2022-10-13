# 作业 3

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.5** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$)

> **定义 3.8** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.14** (初始拓扑)<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.15** (拓扑基)<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$)

> **定义 3.17** (余有限拓扑)<br>称 $X$ 上的余有限拓扑为: 闭集恰为有限集与 $X$ 自身, 即非空开集的补集是有限集. (教材 $\S3$)

> **定义 3.27** (余可数拓扑)<br>称 $X$ 上的余可数拓扑为: 非空开集恰为可数集的补集. (题集 $\S1.4$)

> **定义 3.28** (扎里斯基拓扑)<br>设 $K$ 为域, $\mathbb A^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in I}$ 的公共零点集 $\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.29** (由子集族生成的拓扑)<br>包含某子集族 $\mathcal S$ 的最粗拓扑; 其元素恰为 $\mathcal S$ 中元素之有限交的任意并. (题集 $\S1.4$)

> **定义 6.1** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.2** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.13** (超度量)<br>满足度量空间四条公理且三角不等式加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的度量. (题集 $\S1.3$)

> **定义 6.33** (等价度量)<br>两度量若诱导同一拓扑则称等价, 例如 $\min\left(d,1\right)$ 与 $d$. (题集 $\S1.3$)

> **定义 6.34** (球面)<br>以 $x$ 为心、半径 $r$ 的球面为 $S\left(x,r\right)=\left\{y\in X:d\left(x,y\right)=r\right\}$. (题集 $\S1.3$)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S1.4$)

### 习题一

证明下列定理: $\mathbb R$ 的任一开子集 $U$ 可唯一地写成可数个互不相交的开区间之并, 且这些区间的端点不属于 $U$. 提示: 可考虑含 $x\in U$ 的极大开区间 $I_x\subset U$.

### 解答 习题一

由**定义 6.2** (开球), $\mathbb R$ 的通常拓扑以开区间为基. 对每个 $x\in U$, 令 $I_x$ 为一切含 $x$ 且含于 $U$ 的开区间之并. 因每个这样的开区间都含 $x$, 其并仍是含 $x$ 的开区间 (一族两两相交于同一点的开区间之并为开区间), 含于 $U$, 且在含 $x$ 且含于 $U$ 的开区间中极大.

断言: 对 $x,y\in U$, 或者 $I_x=I_y$, 或者 $I_x\cap I_y=\emptyset$. 事实上, 若 $I_x\cap I_y\neq\emptyset$, 则 $I_x\cup I_y$ 是含 $x,y$ 且含于 $U$ 的开区间, 由 $I_x$ 与 $I_y$ 的极大性, $I_x\cup I_y\subset I_x$ 且 $I_x\cup I_y\subset I_y$, 故 $I_x=I_y=I_x\cup I_y$.

可数性: 每个 $I_x$ 是非空开区间, 可取其中一个有理数 $q_x$. 因诸 $I_x$ 互不相交, 不同 $x$ 给出不同 $q_x$, 故 $\left\{I_x:x\in U\right\}$ 与 $\mathbb Q$ 的某子集一一对应, 因而是可数族. 又因每个 $x\in U$ 都含于 $I_x$, 故 $U=\bigcup_{x\in U}I_x$.

端点: 写 $I_x=\left(a_x,b_x\right)$. 若 $a_x\in U$, 则 $a_x\in I_y$ 对某 $y\in U$. 因 $I_y$ 开, 存在 $\varepsilon>0$ 使 $\left(a_x-\varepsilon,a_x+\varepsilon\right)\subset I_y\subset U$. 于是 $\left(a_x-\varepsilon,b_x\right)$ 是含 $x$ 且含于 $U$ 的开区间, 它比 $I_x$ 向左更长, 与 $I_x$ 的极大性矛盾. 故 $a_x\notin U$. 同理 $b_x\notin U$.

唯一性: 若另有分解 $U=\bigcup_{j\in J}J_j$, 其中 $J_j$ 为互不相交开区间. 对每个 $x\in U$, $x$ 属于唯一的 $J_{j\left(x\right)}$. $J_{j\left(x\right)}$ 是含 $x$ 且含于 $U$ 的开区间, 由 $I_x$ 的极大性 $J_{j\left(x\right)}\subset I_x$; 反之, $I_x$ 是含 $x$ 且含于 $U$ 的开区间, 而 $J_{j\left(x\right)}$ 是含 $x$ 的极大连通开块, 故 $I_x\subset J_{j\left(x\right)}$. 因此 $J_{j\left(x\right)}=I_x$, 两分解一致. $\blacksquare$

### 习题二

回忆距离 $d:X\times X\to\mathbb R_{\ge0}$ 满足四条公理: (1) $d\left(x,x\right)=0$; (2) 若 $d\left(x,y\right)=0$ 则 $x=y$; (3) $d\left(x,y\right)=d\left(y,x\right)$; (4) 三角不等式 $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. $\left(X,d\right)$ 称为度量空间. 超度量是将第 (4) 条加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的距离 (例如通常的 $p$-进度量). 设 $d$ 是超度量, 证明:

(1) 若 $d\left(x,y\right)\neq d\left(x,z\right)$, 则 $d\left(y,z\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)$;

(2) 开球中任一点都是该开球的中心;

(3) 开球中任一点都是由该开球所定球面的中心;

(4) 任意两个开球或者不相交, 或者一个含于另一个.

### 解答 习题二

由**定义 6.13** (超度量), 对任意 $x,y,z\in X$ 有

$$
d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right).
$$

(1) 设 $d\left(x,y\right)\neq d\left(x,z\right)$. 不妨设 $d\left(x,y\right)<d\left(x,z\right)$. 由上式,

$$
d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right).
$$

因右端 $\ge d\left(x,z\right)$ 而 $d\left(x,y\right)<d\left(x,z\right)$, 故必须 $\max\left(d\left(x,y\right),d\left(y,z\right)\right)=d\left(y,z\right)\ge d\left(x,z\right)$. 再对三元组 $\left(y,x,z\right)$ 用**定义 6.13** (超度量):

$$
d\left(y,z\right)\le\max\left(d\left(y,x\right),d\left(x,z\right)\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)=d\left(x,z\right).
$$

合之得 $d\left(y,z\right)=d\left(x,z\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)$.

(2) 设 $z\in B\left(x,r\right)$, 即由**定义 6.2** (开球) $d\left(x,z\right)<r$. 任取 $w\in B\left(x,r\right)$, 由**定义 6.13** (超度量),

$$
d\left(z,w\right)\le\max\left(d\left(z,x\right),d\left(x,w\right)\right)<r,
$$

故 $w\in B\left(z,r\right)$, 即 $B\left(x,r\right)\subset B\left(z,r\right)$. 反之, 任取 $w\in B\left(z,r\right)$, 即 $d\left(z,w\right)<r$, 由**定义 6.13** (超度量)

$$
d\left(x,w\right)\le\max\left(d\left(x,z\right),d\left(z,w\right)\right)<r,
$$

故 $w\in B\left(x,r\right)$. 因此 $B\left(x,r\right)=B\left(z,r\right)$, 即 $z$ 也是该开球的中心.

(3) 由**定义 6.34** (球面), $S\left(x,r\right)=\left\{y:d\left(x,y\right)=r\right\}$. 设 $z\in B\left(x,r\right)$, 即 $d\left(x,z\right)<r$. 任取 $w\in S\left(x,r\right)$, 即 $d\left(x,w\right)=r$. 因 $d\left(x,z\right)<r=d\left(x,w\right)$, 故 $d\left(x,z\right)\neq d\left(x,w\right)$; 由第 1 小题,

$$
d\left(z,w\right)=\max\left(d\left(x,z\right),d\left(x,w\right)\right)=r,
$$

即 $w\in S\left(z,r\right)$. 反之, 任取 $w\in S\left(z,r\right)$, 即 $d\left(z,w\right)=r$. 因 $d\left(z,x\right)=d\left(x,z\right)<r=d\left(z,w\right)$, 对以 $z$ 为基点的三元组 $\left(z,x,w\right)$ 用第 1 小题, 得

$$
d\left(x,w\right)=\max\left(d\left(z,x\right),d\left(z,w\right)\right)=r,
$$

即 $w\in S\left(x,r\right)$. 故 $S\left(x,r\right)=S\left(z,r\right)$, 即 $z$ 也是该球面的中心.

(4) 设 $B\left(x,r\right)$ 与 $B\left(y,s\right)$ 为两个开球. 若不相交则结论已成立. 若相交, 取 $z\in B\left(x,r\right)\cap B\left(y,s\right)$. 由第 2 小题, $B\left(x,r\right)=B\left(z,r\right)$ 且 $B\left(y,s\right)=B\left(z,s\right)$. 不妨设 $r\le s$. 若 $w\in B\left(z,r\right)$, 则 $d\left(z,w\right)<r\le s$, 故 $w\in B\left(z,s\right)$. 因此 $B\left(z,r\right)\subset B\left(z,s\right)$, 即 $B\left(x,r\right)\subset B\left(y,s\right)$. $\blacksquare$

### 习题三

设 $\left(X,d\right)$ 是度量空间. 证明 $d^{*}\left(x,y\right)=\min\left(d\left(x,y\right),1\right)$ 与 $d^{**}\left(x,y\right)=\dfrac{d\left(x,y\right)}{1+d\left(x,y\right)}$ 都是度量, 且与 $d$ 诱导同一拓扑. 注意有界性依赖于度量的选取, 而不依赖于拓扑.

### 解答 习题三

先验证 $d^{*}$ 是度量. 由**定义 6.1** (度量空间) 逐条: (1) $d^{*}\left(x,x\right)=\min\left(0,1\right)=0$. (2) 若 $d^{*}\left(x,y\right)=0$, 则 $\min\left(d\left(x,y\right),1\right)=0$, 故 $d\left(x,y\right)=0$, 由**定义 6.1** (度量空间) 得 $x=y$. (3) 对称性由 $d$ 的对称性直接得到. (4) 对任意 $a,b\ge0$, 有 $\min\left(a+b,1\right)\le\min\left(a,1\right)+\min\left(b,1\right)$; 取 $a=d\left(x,y\right)$, $b=d\left(y,z\right)$, 并用**定义 6.1** (度量空间) 的三角不等式 $d\left(x,z\right)\le d\left(x,y\right)+d\left(y,z\right)$, 得 $d^{*}\left(x,z\right)\le d^{*}\left(x,y\right)+d^{*}\left(y,z\right)$. 故 $d^{*}$ 是度量.

再验证 $d^{**}$ 是度量. 记 $\varphi\left(t\right)=\dfrac{t}{1+t}$, 它在 $\left[0,\infty\right)$ 上严格递增, $\varphi\left(0\right)=0$, 反函数 $\varphi^{-1}\left(t\right)=\dfrac{t}{1-t}$. (1) $d^{**}\left(x,x\right)=\varphi\left(0\right)=0$. (2) 若 $d^{**}\left(x,y\right)=0$, 则 $\varphi\left(d\left(x,y\right)\right)=0$, 由 $\varphi$ 严格递增知 $d\left(x,y\right)=0$, 由**定义 6.1** (度量空间) 得 $x=y$. (3) 对称性显然. (4) 由**定义 6.1** (度量空间) 的三角不等式与 $\varphi$ 递增, $d^{**}\left(x,z\right)=\varphi\left(d\left(x,z\right)\right)\le\varphi\left(d\left(x,y\right)+d\left(y,z\right)\right)$. 而对 $a,b\ge0$ 有

$$
\varphi\left(a+b\right)=\frac{a+b}{1+a+b}\le\frac{a}{1+a}+\frac{b}{1+b}=\varphi\left(a\right)+\varphi\left(b\right),
$$

故 $d^{**}\left(x,z\right)\le d^{**}\left(x,y\right)+d^{**}\left(y,z\right)$. 故 $d^{**}$ 是度量.

同一拓扑: 对 $0<r<1$, 由**定义 6.2** (开球),

$$
B_{d^{*}}\left(x,r\right)=\left\{y:\min\left(d\left(x,y\right),1\right)<r\right\}=\left\{y:d\left(x,y\right)<r\right\}=B_{d}\left(x,r\right).
$$

而对 $d^{**}$, 半径 $r\in\left(0,1\right)$ 的球为

$$
B_{d^{**}}\left(x,r\right)=\left\{y:\frac{d\left(x,y\right)}{1+d\left(x,y\right)}<r\right\}=\left\{y:d\left(x,y\right)<\frac{r}{1-r}\right\}=B_{d}\left(x,\frac{r}{1-r}\right).
$$

故 $d^{*}$ 与 $d$ 的半径小于 $1$ 的球族完全相同, $d^{**}$ 的球与 $d$ 的球一一对应. 由**定义 6.2** (开球), 全体开球族是度量拓扑的基, 故三者生成同一拓扑. 由**定义 6.33** (等价度量), $d^{*}$ 与 $d^{**}$ 都与 $d$ 等价. $\blacksquare$

### 习题四

回忆 $\mathbb R^n$ 上的通常度量拓扑. 证明 $\mathbb R^n$ 中任意一族开集之并仍是开集. 证明开集的交未必是开集.

### 解答 习题四

由**定义 6.2** (开球), $\mathbb R^n$ 的通常度量拓扑以欧氏开球 $B\left(x,r\right)$ 为基, 故每个开集是若干开球之并. 设 $\left\{U_i\right\}_{i\in I}$ 是一族开集, $U=\bigcup_{i\in I}U_i$. 任取 $x\in U$, 则 $x\in U_{i_0}$ 对某 $i_0$; 因 $U_{i_0}$ 开, 由**定义 6.2** (开球) 存在开球 $B$ 使 $x\in B\subset U_{i_0}\subset U$. 故 $U$ 的每一点都有开球邻域含于 $U$, 由**定义 3.1** (拓扑空间) $U$ 是开集.

但任意交未必开. 取 $\mathbb R$ 中一列开区间 $\left(-\frac1n,\frac1n\right)$ ($n\ge1$), 其交为

$$
\bigcap_{n=1}^{\infty}\left(-\frac1n,\frac1n\right)=\left\{0\right\}.
$$

由**定义 6.2** (开球), 任何含 $0$ 的开球都含非零点, 故 $\left\{0\right\}$ 不含任何开球, 不是开集. $\blacksquare$

### 习题五

回忆函数的原像. 证明原像运算与并运算、交运算可交换. 那直接像呢?

### 解答 习题五

设 $f:X\to Y$. 原像定义为 $f^{-1}\left(B\right)=\left\{x\in X:f\left(x\right)\in B\right\}$, 其中 $B\subset Y$. 对任意一族 $\left\{B_j\right\}_{j\in J}$ 有

$$
f^{-1}\left(\bigcup_jB_j\right)=\bigcup_jf^{-1}\left(B_j\right),\qquad f^{-1}\left(\bigcap_jB_j\right)=\bigcap_jf^{-1}\left(B_j\right).
$$

事实上, $x$ 属于左端当且仅当 $f\left(x\right)$ 属于相应的并或交, 直接由定义展开即得. 故原像与并、交均可交换.

直接像 $f\left(A\right)=\left\{f\left(x\right):x\in A\right\}$ 则不然: 并运算可交换, $f\left(\bigcup_jA_j\right)=\bigcup_jf\left(A_j\right)$; 但交运算只含一边,

$$
f\left(\bigcap_jA_j\right)\subset\bigcap_jf\left(A_j\right),
$$

等号一般不成立. 反例: 取 $f\left(t\right)=t^2$, $A_1=\left[-1,0\right]$, $A_2=\left[0,1\right]$. 则 $A_1\cap A_2=\left\{0\right\}$, 故 $f\left(A_1\cap A_2\right)=\left\{0\right\}$; 但 $f\left(A_1\right)=f\left(A_2\right)=\left[0,1\right]$, 故 $\bigcap_jf\left(A_j\right)=\left[0,1\right]$. 包含而不相等. $\blacksquare$

### 习题六

回忆由一族向量生成的向量子空间. 给出一个利用向量空间对交集稳定性的抽象构造, 以及一个利用有限线性组合的具体构造.

### 解答 习题六

设 $E$ 是域上向量空间, $\mathcal F=\left\{v_\alpha\right\}_{\alpha\in A}\subset E$.

抽象构造: 令 $\mathcal S$ 为 $E$ 中一切包含 $\mathcal F$ 的向量子空间所成之族, 定义 $\operatorname{span}\left(\mathcal F\right)=\bigcap_{S\in\mathcal S}S$. 因任意一族向量子空间的交集仍是向量子空间 (对加法与数乘封闭, 且含零向量), 故 $\operatorname{span}\left(\mathcal F\right)$ 是包含 $\mathcal F$ 的子空间, 且是其中最小者.

具体构造: 令

$$
\operatorname{span}\left(\mathcal F\right)=\left\{\sum_{k=1}^{m}c_kv_{\alpha_k}:m\ge1,\ c_k\text{ 为域中元素},\ v_{\alpha_k}\in\mathcal F\right\},
$$

即 $\mathcal F$ 中元素的有限线性组合全体. 它本身是包含 $\mathcal F$ 的向量子空间, 故含于抽象构造. 反之, 任何包含 $\mathcal F$ 的向量子空间对线性组合封闭, 故包含全部有限线性组合, 因而抽象构造 (一切子空间之交) 也含于该具体集合. 两者相等. $\blacksquare$

### 习题七

证明: 集合 $F$ 在 $\mathbb R$ 的通常度量拓扑下闭, 当且仅当 $F$ 的每个收敛序列的极限都在 $F$ 中.

### 解答 习题七

**($\Rightarrow$)** 设 $F$ 闭. 由**定义 3.2** (闭集), $\mathbb R\setminus F$ 开. 设 $x_n\in F$ 且 $x_n\to L$. 若 $L\notin F$, 则 $L\in\mathbb R\setminus F$, 而 $\mathbb R\setminus F$ 是 $L$ 的邻域. 由**定义 3.5** (邻域与极限), 对所有充分大的 $n$ 有 $x_n\in\mathbb R\setminus F$, 与 $x_n\in F$ 矛盾. 故 $L\in F$.

**($\Leftarrow$)** 反证. 设 $F$ 不闭. 由**定义 3.2** (闭集), $\mathbb R\setminus F$ 不开. 故存在 $L\notin F$ 使 $L$ 的任何邻域都不含于 $\mathbb R\setminus F$, 即 $L$ 的任何邻域都与 $F$ 相交. 由**定义 6.2** (开球), 球 $B\left(L,1/n\right)=\left(L-\frac1n,L+\frac1n\right)$ 与 $F$ 相交, 取 $x_n\in F\cap B\left(L,1/n\right)$, 则 $d\left(x_n,L\right)<1/n$. 任给 $L$ 的邻域, 由**定义 6.2** (开球) 它包含某 $B\left(L,\varepsilon\right)$; 当 $n>1/\varepsilon$ 时 $x_n\in B\left(L,\varepsilon\right)$, 故由**定义 3.5** (邻域与极限) $x_n\to L$. 但 $L\notin F$, 与假设矛盾. 故 $F$ 闭. $\blacksquare$

### 习题八

回忆同一空间 $X$ 上一族拓扑的交集仍是拓扑. 回忆由 $X$ 的一族子集生成的拓扑是什么. 是否有一个利用有限交的具体构造?

### 解答 习题八

同一空间 $X$ 上一族拓扑 $\left\{\mathcal O_\alpha\right\}_{\alpha\in A}$ 的交集 $\mathcal O=\bigcap_{\alpha\in A}\mathcal O_\alpha$ 仍是拓扑: $\emptyset$ 与 $X$ 属于每个 $\mathcal O_\alpha$, 故属于 $\mathcal O$; 若 $\left\{U_i\right\}\subset\mathcal O$, 则对每个 $\alpha$ 有 $\left\{U_i\right\}\subset\mathcal O_\alpha$, 由**定义 3.1** (拓扑空间) $\bigcup_iU_i\in\mathcal O_\alpha$, 故 $\bigcup_iU_i\in\mathcal O$; 有限交同理.

由**定义 3.29** (由子集族生成的拓扑), 给定子集族 $\mathcal S\subset\mathcal P\left(X\right)$, 它生成的拓扑即包含 $\mathcal S$ 的最粗拓扑, 存在且等于一切包含 $\mathcal S$ 的拓扑之交. 其具体构造为: 先取 $\mathcal S$ 中元素的有限交 (约定空交为 $X$), 再取这些有限交的任意并 (约定空并为 $\emptyset$). 所得族 $\tau$ 确实是拓扑: $\emptyset,X\in\tau$; 任意并仍是任意并; 两个有限交的有限交仍是有限交, 故有限交封闭; 由**定义 3.1** (拓扑空间) $\tau$ 是拓扑. 它包含 $\mathcal S$ (每个 $S\in\mathcal S$ 是单元素族的有限交). 反之, 任何包含 $\mathcal S$ 的拓扑由**定义 3.1** (拓扑空间) 对有限交与任意并封闭, 必包含 $\tau$ 的全部元素, 故 $\tau$ 是最粗的. $\blacksquare$

### 习题九

证明: 若 $f:X\to\left(Y,\mathcal O\right)$ 是到拓扑空间 $Y$ 的映射, 则集合族 $\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 在 $X$ 上定义一个拓扑. 证明它是使 $f$ 连续的最粗拓扑, 即初始拓扑. 研究 $f$ 为包含映射的情形, 例如 $f:\mathbb R\to\mathbb R^2$, 其中 $\mathbb R^2$ 装备欧氏拓扑. 反过来, 能否把 $X$ 上的拓扑前推, 在 $Y$ 上定义所谓最终拓扑?

### 解答 习题九

记 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$. 由原像与并、交可交换, $\mathcal O_f$ 满足**定义 3.1** (拓扑空间) 的三条: $\emptyset=f^{-1}\left(\emptyset\right)$ 与 $X=f^{-1}\left(Y\right)$ 在 $\mathcal O_f$ 中; 任意并 $\bigcup_jf^{-1}\left(O_j\right)=f^{-1}\left(\bigcup_jO_j\right)$ 仍在 $\mathcal O_f$ 中; 有限交 $f^{-1}\left(O_1\right)\cap f^{-1}\left(O_2\right)=f^{-1}\left(O_1\cap O_2\right)$ 仍在其中. 故 $\mathcal O_f$ 是 $X$ 上的拓扑.

对任意 $O\in\mathcal O$, $f^{-1}\left(O\right)\in\mathcal O_f$ 是开集, 由**定义 3.3** (连续映射) $f$ 连续. 反之, 若 $\tau$ 是 $X$ 上任一使 $f$ 连续的拓扑, 则对每个 $O\in\mathcal O$, 由**定义 3.3** (连续映射) $f^{-1}\left(O\right)\in\tau$, 故 $\mathcal O_f\subset\tau$. 由**定义 3.14** (初始拓扑), $\mathcal O_f$ 正是 $f$ 诱导的初始拓扑.

包含映射的情形: 取 $f:\mathbb R\to\mathbb R^2$, $f\left(t\right)=\left(t,0\right)$, $\mathbb R^2$ 装备欧氏拓扑. 则 $f^{-1}\left(U\right)=U\cap\left(\mathbb R\times\left\{0\right\}\right)$, 它在 $x$ 轴上的截口恰为 $\mathbb R$ 的通常开集, 故 $\mathcal O_f$ 就是 $\mathbb R$ 的通常拓扑.

反过来的构造: 由**定义 11.14** (最终拓扑), 对映射 $f:X\to Y$, 在 $Y$ 上规定 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 在 $X$ 中开. 这是使 $f$ 连续的最细拓扑, 即最终拓扑. $\blacksquare$

### 习题十

设 $X$ 为集合. 证明下列是拓扑: 所有非平凡开集都是 $X$ 的某有限子集的补集; 这称为 $X$ 上的余有限拓扑. 证明序列 $\left\{1,2,3,4,\dots\right\}$ 在 $\mathbb R$ 的余有限拓扑中收敛到 $\mathbb R$ 的每一点. 能否在 $X$ 上定义余可数拓扑? 现在取 $X=\mathbb R$ 装备余可数拓扑, 考虑 $\left(-1,1\right)\subset\mathbb R$. 证明 $\overline{\left(-1,1\right)}=\mathbb R$. 证明 $\left(-1,1\right)$ 中没有序列收敛到 $2\in\mathbb R$.

### 解答 习题十

由**定义 3.17** (余有限拓扑), $X$ 上余有限拓扑的开集为 $\emptyset$ 与所有余有限集 $X\setminus F$ ($F$ 有限). 验证它是拓扑: $\emptyset$ 与 $X$ 开; 任意并 $\bigcup_i\left(X\setminus F_i\right)=X\setminus\bigcap_iF_i$, 而任意一族有限集之交仍有限, 故仍余有限; 有限交 $\bigcap_{k=1}^{m}\left(X\setminus F_k\right)=X\setminus\bigcup_{k=1}^{m}F_k$, 有限个有限集之并仍有限. 由**定义 3.1** (拓扑空间) 这是拓扑.

序列 $\left\{n\right\}_{n\ge1}$ 在余有限拓扑 $\mathbb R$ 中收敛到任一点 $x$: $x$ 的任一邻域是 $X\setminus F$ ($F$ 有限). 因 $F$ 只含有限个自然数, 除有限个 $n$ 外 $n\notin F$, 故 $n\in X\setminus F$ 最终成立. 由**定义 3.5** (邻域与极限), $n\to x$.

余可数拓扑: 由**定义 3.27** (余可数拓扑), 开集为 $\emptyset$ 与所有余可数集 $X\setminus C$ ($C$ 可数). 现在取 $X=\mathbb R$ 装备余可数拓扑, 令 $A=\left(-1,1\right)$. 任取 $x\in\mathbb R$ 与其任一邻域 $U=\mathbb R\setminus C$ ($C$ 可数). 因 $\left(-1,1\right)$ 不可数而 $C$ 可数, 故 $A\setminus C=\left(-1,1\right)\setminus C\neq\emptyset$, 即 $U\cap A\neq\emptyset$. 由**定义 3.6** (闭包), $x$ 属于 $A$ 的闭包. 故 $\overline A=\mathbb R$.

最后, 设 $x_n\in A$ 且 $x_n\to2$. 令 $C=\left\{x_n:n\ge1\right\}$, 它可数. 则 $U=\mathbb R\setminus C$ 是余可数开集, 含 $2$, 但不含任何 $x_n$. 由**定义 3.5** (邻域与极限), 这与 $x_n\to2$ 矛盾. 故 $A$ 中没有序列收敛到 $2$. $\blacksquare$

### 习题十一

设 $K$ 为域, $n\in\mathbb N$ 为非负整数, $\mathbb A^n\left(K\right)=K^n$. $\mathbb A^n\left(K\right)$ 中扎里斯基闭集形如 $F=\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$, 其中 $\left(P_i\right)_{i\in I}$ 是一族多项式. 证明这确实定义了一个拓扑 (即扎里斯基拓扑). 证明 $\mathbb R^2$ 中扎里斯基开集在 $\mathbb R^2$ 中稠密. 求 $\left\{\left(0,\frac1{2^n}\right):n\ge0\right\}\subset\mathbb R^2$ 的扎里斯基闭包.

### 解答 习题十一

由**定义 3.28** (扎里斯基拓扑), 记 $Z\left(P_i\right)_{i\in I}=\left\{x:\forall i\in I,P_i\left(x\right)=0\right\}$. 验证闭集族满足**定义 3.2** (闭集): 空集 $Z\left(1\right)$ (常数多项式 $1$ 无零点); 全空间 $Z\left(0\right)$ (零多项式处处为零); 任意交

$$
\bigcap_{\alpha}Z\left(P_{\alpha,j}\right)_{j\in J_\alpha}=Z\left(\bigcup_\alpha\left\{P_{\alpha,j}\right\}\right)
$$

仍为公共零点集; 两个闭集之并

$$
Z\left(P_i\right)_{i\in I}\cup Z\left(Q_j\right)_{j\in J}=Z\left(P_iQ_j\right)_{i,j}
$$

(因 $x$ 在左端当且仅当某 $P_i\left(x\right)=0$ 或某 $Q_j\left(x\right)=0$, 当且仅当对一切 $\left(i,j\right)$ 有 $P_i\left(x\right)Q_j\left(x\right)=0$). 故闭集族满足**定义 3.2** (闭集), 扎里斯基拓扑成立.

扎里斯基开集稠密: 非空扎里斯基开集是某非零多项式 $P$ 的零点集的补集 $\mathbb R^2\setminus Z\left(P\right)$. 若 $Z\left(P\right)$ 含某开球, 则该开球内沿任一直线限制 $P$ 所得一元多项式在无限多点为零, 故恒为零; 从而 $P$ 在该开球上恒为零, 进而 $P\equiv0$, 矛盾. 故 $Z\left(P\right)$ 无内部. 由**定义 3.8** (稠密), 其补集 (扎里斯基开集) 稠密.

求闭包: 令 $S=\left\{\left(0,2^{-n}\right):n\ge0\right\}$. 多项式 $P$ 在 $S$ 上恒零当且仅当一元多项式 $P\left(0,y\right)$ 在无限多点 $y=2^{-n}$ 为零, 当且仅当 $P\left(0,\cdot\right)\equiv0$, 即 $x\mid P\left(x,y\right)$. 全体这样的 $P$ 的公共零点集为 $\left\{\left(0,y\right):y\in\mathbb R\right\}$, 即 $y$ 轴. 由**定义 3.6** (闭包), 这就是 $S$ 的扎里斯基闭包. $\blacksquare$

### 习题十二

回忆拓扑基的定义. 回忆其等价刻画. 若去掉其中任一条件会怎样? 证明定义与刻画的等价性.

### 解答 习题十二

由**定义 3.15** (拓扑基), 拓扑基的定义是: $\mathcal B\subset\mathcal P\left(X\right)$ 中元素的任意并构成 $X$ 上一个拓扑. 其等价刻画为: (1) $X=\bigcup_{B\in\mathcal B}B$; (2) 对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$, 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$.

**定义 $\Rightarrow$ 刻画**: 若 $\mathcal B$ 的任意并构成拓扑, 由**定义 3.1** (拓扑空间), 则 $X=\bigcup_{B\in\mathcal B}B$ 是开集, 即 (1). 又 $B_1\cap B_2$ 是两开集之交, 仍开, 故可表为 $\mathcal B$ 中元素之并; 任取 $x\in B_1\cap B_2$, 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 即 (2).

**刻画 $\Rightarrow$ 定义**: 设 (1)(2) 成立. 令 $\tau=\left\{\bigcup_{B\in\mathcal C}B:\mathcal C\subset\mathcal B\right\}$. 由 (1) $X\in\tau$, 空并 $\emptyset\in\tau$. $\tau$ 中任意并显然仍在 $\tau$ 中. 设 $U=\bigcup_{\alpha}B_\alpha\in\tau$, $V=\bigcup_{\beta}B'_\beta\in\tau$, 则 $U\cap V=\bigcup_{\alpha,\beta}\left(B_\alpha\cap B'_\beta\right)$. 对每个 $x\in B_\alpha\cap B'_\beta$, 由 (2) 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_\alpha\cap B'_\beta$, 故 $B_\alpha\cap B'_\beta$ 是若干 $\mathcal B$ 中元素之并, 从而 $U\cap V\in\tau$. 由**定义 3.1** (拓扑空间), $\tau$ 是拓扑.

去掉条件: 若去掉 (1), 例如 $\mathcal B=\left\{\emptyset\right\}$, 其任意并只能得 $\emptyset$, 盖不住 $X$; 若去掉 (2), 例如 $X=\mathbb R$, $\mathcal B=\left\{\left(-\infty,a\right):a\in\mathbb R\right\}\cup\left\{\left(b,+\infty\right):b\in\mathbb R\right\}$, 则 $\left(-\infty,1\right)\cap\left(0,+\infty\right)=\left(0,1\right)$ 不能表为 $\mathcal B$ 中元素之并, 故 $\mathcal B$ 的任意并不构成拓扑. $\blacksquare$
