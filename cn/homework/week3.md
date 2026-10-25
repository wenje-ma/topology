# 作业 3

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$, p17)

> **定义 3.14** (初始拓扑)<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.15** (拓扑基)<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

> **定义 3.17** (余有限拓扑)<br>称 $X$ 上的余有限拓扑为: 闭集恰为有限集与 $X$ 自身, 即非空开集的补集是有限集. (教材 $\S3$, p16)

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$, p12)

> **定义 3.19** (子空间拓扑)<br>设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 $\S3$, p17)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$, p13)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.25** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$, p16)

> **定义 3.26** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **定义 3.27** (余可数拓扑)<br>称 $X$ 上的余可数拓扑为: 非空开集恰为可数集的补集. (题集 $\S1.4$)

> **定义 3.28** (扎里斯基拓扑)<br>设 $K$ 为域, $\mathbb A^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in I}$ 的公共零点集 $\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.29** (由子集族生成的拓扑)<br>包含某子集族 $\mathcal S$ 的最粗拓扑; 其元素恰为 $\mathcal S$ 中元素之有限交的任意并. (题集 $\S1.4$)

> **定义 3.30** (基本邻域系)<br>$x$ 的邻域族 $\mathcal P$, 使 $x$ 的每个邻域都含某个 $\mathcal P$ 中元素. (题集 $\S2.4$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$, p18)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.36** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)< r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.47** ($\varepsilon$-邻域)<br>$U_\varepsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)< \varepsilon\right\}$. (题集 $\S3.2$)

> **命题** (可分度量空间必有可数基)<br>若度量空间 $X$ 有可数稠密子集, 则 $X$ 有可数基. 事实上对可度量化空间, 可分与第二可数等价. (Munkres $\S30$, 习题 5(a))

> **定义 7.6** (正规空间)<br>单点闭且任意两不相交闭集可被不相交开集分离, 即 $T_4$. (教材 $\S7$, p42)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S1.4$)

### 习题一

回忆 $\mathbb R^n$ 上的通常度量拓扑. 证明 $\mathbb R^n$ 中任意一族开集之并仍是开集. 证明开集的交未必是开集.

### 解答 习题一

由**定义 6.36** (开球), $\mathbb R^n$ 的通常度量拓扑以欧氏开球 $B\left(x,r\right)$ 为基, 故每个开集是若干开球之并. 设 $\left\{U_i\right\}_{i\in I}$ 是一族开集, $U=\bigcup_{i\in I}U_i$. 任取 $x\in U$, 则 $x\in U_{i_0}$ 对某 $i_0$; 因 $U_{i_0}$ 开, 由**定义 6.36** (开球) 存在开球 $B$ 使 $x\in B\subset U_{i_0}\subset U$. 故 $U$ 的每一点都有开球邻域含于 $U$, 由**定义 3.18** (拓扑空间) $U$ 是开集.

但任意交未必开. 取 $\mathbb R$ 中一列开区间 $\left(-\frac1n,\frac1n\right)$ ($n\ge1$), 其交为

$$
\bigcap_{n=1}^{\infty}\left(-\frac1n,\frac1n\right)=\left\{0\right\}.
$$

由**定义 6.36** (开球), 任何含 $0$ 的开球都含非零点, 故 $\left\{0\right\}$ 不含任何开球, 不是开集. $\blacksquare$

### 习题二

回忆函数的原像. 证明原像运算与并运算、交运算可交换. 那直接像呢?

### 解答 习题二

设 $f:X\to Y$. 原像定义为 $f^{-1}\left(B\right)=\left\{x\in X:f\left(x\right)\in B\right\}$, 其中 $B\subset Y$. 对任意一族 $\left\{B_j\right\}_{j\in J}$ 有

$$
f^{-1}\left(\bigcup_jB_j\right)=\bigcup_jf^{-1}\left(B_j\right),\quad f^{-1}\left(\bigcap_jB_j\right)=\bigcap_jf^{-1}\left(B_j\right).
$$

事实上, $x$ 属于左端当且仅当 $f\left(x\right)$ 属于相应的并或交, 直接由定义展开即得. 故原像与并、交均可交换.

直接像 $f\left(A\right)=\left\{f\left(x\right):x\in A\right\}$ 则不然: 并运算可交换, $f\left(\bigcup_jA_j\right)=\bigcup_jf\left(A_j\right)$; 但交运算只含一边,

$$
f\left(\bigcap_jA_j\right)\subset\bigcap_jf\left(A_j\right),
$$

等号一般不成立. 反例: 取 $f\left(t\right)=t^2$, $A_1=\left[-1,0\right]$, $A_2=\left[0,1\right]$. 则 $A_1\cap A_2=\left\{0\right\}$, 故 $f\left(A_1\cap A_2\right)=\left\{0\right\}$; 但 $f\left(A_1\right)=f\left(A_2\right)=\left[0,1\right]$, 故 $\bigcap_jf\left(A_j\right)=\left[0,1\right]$. 包含而不相等. $\blacksquare$

> (1) 原像的交可交换, 但直接像的交不可交换: 因为考虑原像时是看着 $x$ 找 $y$, 都是一一对应的; 考虑直接像时是看着 $y$ 找 $x$, 而一个 $y$ 可能对应多个 $x$, 因此不可逆, 自然也不可交换.<br>(2) 直接像的并可交换, 但直接像的交不可交换: 考虑并时, 虽然是看着 $y$ 找 $x$, 但并集的含义是 "存在一个" 即可, 因此虽然可能有多个 $x$, 找到一个就行; 考虑交时, 交集的含义是 "任意一个" 均需要满足, 这就要求了 $x$ 需唯一才行, 因此不可逆, 自然也不可交换.

### 习题三

回忆由一族向量生成的向量子空间. 给出一个利用向量空间对交集稳定性的抽象构造, 以及一个利用有限线性组合的具体构造.

### 解答 习题三

设 $E$ 是域上向量空间, $\mathcal F=\left\{v_\alpha\right\}_{\alpha\in A}\subset E$.

抽象构造: 令 $\mathcal S$ 为 $E$ 中一切包含 $\mathcal F$ 的向量子空间所成之族, 定义 $\operatorname{span}\left(\mathcal F\right)=\bigcap_{S\in\mathcal S}S$. 因任意一族向量子空间的交集仍是向量子空间 (对加法与数乘封闭, 且含零向量), 故 $\operatorname{span}\left(\mathcal F\right)$ 是包含 $\mathcal F$ 的子空间, 且是其中最小者.

具体构造: 令

$$
\operatorname{span}\left(\mathcal F\right)=\left\{\sum_{k=1}^{m}c_kv_{\alpha_k}:m\ge1,\ c_k\text{ 为域中元素},\ v_{\alpha_k}\in\mathcal F\right\},
$$

即 $\mathcal F$ 中元素的有限线性组合全体. 它本身是包含 $\mathcal F$ 的向量子空间, 故含于抽象构造. 反之, 任何包含 $\mathcal F$ 的向量子空间对线性组合封闭, 故包含全部有限线性组合, 因而抽象构造 (一切子空间之交) 也含于该具体集合. 两者相等. $\blacksquare$

### 习题四

证明: 集合 $F$ 在 $\mathbb R$ 的通常度量拓扑下闭, 当且仅当 $F$ 的每个收敛序列的极限都在 $F$ 中.

### 解答 习题四

**($\Rightarrow$)** 设 $F$ 闭. 由**定义 3.21** (闭集), $\mathbb R\setminus F$ 开. 设 $x_n\in F$ 且 $x_n\to L$. 若 $L\notin F$, 则 $L\in\mathbb R\setminus F$, 而 $\mathbb R\setminus F$ 是 $L$ 的邻域. 由**定义 3.25** (邻域与极限), 对所有充分大的 $n$ 有 $x_n\in\mathbb R\setminus F$, 与 $x_n\in F$ 矛盾. 故 $L\in F$.

**($\Leftarrow$)** 反证. 设 $F$ 不闭. 由**定义 3.21** (闭集), $\mathbb R\setminus F$ 不开. 故存在 $L\notin F$ 使 $L$ 的任何邻域都不含于 $\mathbb R\setminus F$, 即 $L$ 的任何邻域都与 $F$ 相交. 由**定义 6.36** (开球), 球 $B\left(L,1/n\right)=\left(L-\frac1n,L+\frac1n\right)$ 与 $F$ 相交, 取 $x_n\in F\cap B\left(L,1/n\right)$, 则 $d\left(x_n,L\right)< 1/n$. 任给 $L$ 的邻域, 由**定义 6.36** (开球) 它包含某 $B\left(L,\varepsilon\right)$; 当 $n> 1/\varepsilon$ 时 $x_n\in B\left(L,\varepsilon\right)$, 故由**定义 3.25** (邻域与极限) $x_n\to L$. 但 $L\notin F$, 与假设矛盾. 故 $F$ 闭. $\blacksquare$

### 习题五

回忆同一空间 $X$ 上一族拓扑的交集仍是拓扑. 回忆由 $X$ 的一族子集生成的拓扑是什么. 是否有一个利用有限交的具体构造?

### 解答 习题五

同一空间 $X$ 上一族拓扑 $\left\{\mathcal O_\alpha\right\}_{\alpha\in A}$ 的交集 $\mathcal O=\bigcap_{\alpha\in A}\mathcal O_\alpha$ 仍是拓扑: $\emptyset$ 与 $X$ 属于每个 $\mathcal O_\alpha$, 故属于 $\mathcal O$; 若 $\left\{U_i\right\}\subset\mathcal O$, 则对每个 $\alpha$ 有 $\left\{U_i\right\}\subset\mathcal O_\alpha$, 由**定义 3.18** (拓扑空间) $\bigcup_iU_i\in\mathcal O_\alpha$, 故 $\bigcup_iU_i\in\mathcal O$; 有限交同理.

由**定义 3.29** (由子集族生成的拓扑), 给定子集族 $\mathcal S\subset\mathcal P\left(X\right)$, 它生成的拓扑即包含 $\mathcal S$ 的最粗拓扑, 存在且等于一切包含 $\mathcal S$ 的拓扑之交. 其具体构造为: 先取 $\mathcal S$ 中元素的有限交 (约定空交为 $X$), 再取这些有限交的任意并 (约定空并为 $\emptyset$). 所得族 $\tau$ 确实是拓扑: $\emptyset,X\in\tau$; 任意并仍是任意并; 两个有限交的有限交仍是有限交, 故有限交封闭; 由**定义 3.18** (拓扑空间) $\tau$ 是拓扑. 它包含 $\mathcal S$ (每个 $S\in\mathcal S$ 是单元素族的有限交). 反之, 任何包含 $\mathcal S$ 的拓扑由**定义 3.18** (拓扑空间) 对有限交与任意并封闭, 必包含 $\tau$ 的全部元素, 故 $\tau$ 是最粗的. $\blacksquare$

### 习题六

证明: 若 $f:X\to\left(Y,\mathcal O\right)$ 是到拓扑空间 $Y$ 的映射, 则集合族 $\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 在 $X$ 上定义一个拓扑. 证明它是使 $f$ 连续的最粗拓扑, 即初始拓扑. 研究 $f$ 为包含映射的情形, 例如 $f:\mathbb R\to\mathbb R^2$, 其中 $\mathbb R^2$ 装备欧氏拓扑. 反过来, 能否把 $X$ 上的拓扑前推, 在 $Y$ 上定义所谓最终拓扑?

### 解答 习题六

记 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$. 由原像与并、交可交换, $\mathcal O_f$ 满足**定义 3.18** (拓扑空间) 的三条: $\emptyset=f^{-1}\left(\emptyset\right)$ 与 $X=f^{-1}\left(Y\right)$ 在 $\mathcal O_f$ 中; 任意并 $\bigcup_jf^{-1}\left(O_j\right)=f^{-1}\left(\bigcup_jO_j\right)$ 仍在 $\mathcal O_f$ 中; 有限交 $f^{-1}\left(O_1\right)\cap f^{-1}\left(O_2\right)=f^{-1}\left(O_1\cap O_2\right)$ 仍在其中. 故 $\mathcal O_f$ 是 $X$ 上的拓扑.

对任意 $O\in\mathcal O$, $f^{-1}\left(O\right)\in\mathcal O_f$ 是开集, 由**定义 3.22** (连续映射) $f$ 连续. 反之, 若 $\tau$ 是 $X$ 上任一使 $f$ 连续的拓扑, 则对每个 $O\in\mathcal O$, 由**定义 3.22** (连续映射) $f^{-1}\left(O\right)\in\tau$, 故 $\mathcal O_f\subset\tau$. 由**定义 3.14** (初始拓扑), $\mathcal O_f$ 正是 $f$ 诱导的初始拓扑.

包含映射的情形: 取 $f:\mathbb R\to\mathbb R^2$, $f\left(t\right)=\left(t,0\right)$, $\mathbb R^2$ 装备欧氏拓扑. 则 $f^{-1}\left(U\right)=U\cap\left(\mathbb R\times\left\{0\right\}\right)$, 它在 $x$ 轴上的截口恰为 $\mathbb R$ 的通常开集, 故 $\mathcal O_f$ 就是 $\mathbb R$ 的通常拓扑.

反过来的构造: 由**定义 11.14** (最终拓扑), 对映射 $f:X\to Y$, 在 $Y$ 上规定 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 在 $X$ 中开. 这是使 $f$ 连续的最细拓扑, 即最终拓扑. $\blacksquare$

### 习题七

设 $X$ 为集合. 证明下列是拓扑: 所有非平凡开集都是 $X$ 的某有限子集的补集; 这称为 $X$ 上的余有限拓扑. 证明序列 $\left\{1,2,3,4,\dots\right\}$ 在 $\mathbb R$ 的余有限拓扑中收敛到 $\mathbb R$ 的每一点. 能否在 $X$ 上定义余可数拓扑? 现在取 $X=\mathbb R$ 装备余可数拓扑, 考虑 $\left(-1,1\right)\subset\mathbb R$. 证明 $\overline{\left(-1,1\right)}=\mathbb R$. 证明 $\left(-1,1\right)$ 中没有序列收敛到 $2\in\mathbb R$.

### 解答 习题七

由**定义 3.17** (余有限拓扑), $X$ 上余有限拓扑的开集为 $\emptyset$ 与所有余有限集 $X\setminus F$ ($F$ 有限). 验证它是拓扑: $\emptyset$ 与 $X$ 开; 任意并 $\bigcup_i\left(X\setminus F_i\right)=X\setminus\bigcap_iF_i$, 而任意一族有限集之交仍有限, 故仍余有限; 有限交 $\bigcap_{k=1}^{m}\left(X\setminus F_k\right)=X\setminus\bigcup_{k=1}^{m}F_k$, 有限个有限集之并仍有限. 由**定义 3.18** (拓扑空间) 这是拓扑.

序列 $\left\{n\right\}_{n\ge1}$ 在余有限拓扑 $\mathbb R$ 中收敛到任一点 $x$: $x$ 的任一邻域是 $X\setminus F$ ($F$ 有限). 因 $F$ 只含有限个自然数, 除有限个 $n$ 外 $n\notin F$, 故 $n\in X\setminus F$ 最终成立. 由**定义 3.25** (邻域与极限), $n\to x$.

余可数拓扑: 由**定义 3.27** (余可数拓扑), 开集为 $\emptyset$ 与所有余可数集 $X\setminus C$ ($C$ 可数). 现在取 $X=\mathbb R$ 装备余可数拓扑, 令 $A=\left(-1,1\right)$. 任取 $x\in\mathbb R$ 与其任一邻域 $U=\mathbb R\setminus C$ ($C$ 可数). 因 $\left(-1,1\right)$ 不可数而 $C$ 可数, 故 $A\setminus C=\left(-1,1\right)\setminus C\neq\emptyset$, 即 $U\cap A\neq\emptyset$. 由**定义 3.26** (闭包), $x$ 属于 $A$ 的闭包. 故 $\overline A=\mathbb R$.

最后, 设 $x_n\in A$ 且 $x_n\to2$. 令 $C=\left\{x_n:n\ge1\right\}$, 它可数. 则 $U=\mathbb R\setminus C$ 是余可数开集, 含 $2$, 但不含任何 $x_n$. 由**定义 3.25** (邻域与极限), 这与 $x_n\to2$ 矛盾. 故 $A$ 中没有序列收敛到 $2$. $\blacksquare$

### 习题八

设 $K$ 为域, $n\in\mathbb N$ 为非负整数, $\mathbb A^n\left(K\right)=K^n$. $\mathbb A^n\left(K\right)$ 中扎里斯基闭集形如 $F=\left\{x\in\mathbb A^n\left(K\right):\forall i\in I,P_i\left(x\right)=0\right\}$, 其中 $\left(P_i\right)_{i\in I}$ 是一族多项式. 证明这确实定义了一个拓扑 (即扎里斯基拓扑). 证明 $\mathbb R^2$ 中扎里斯基开集在 $\mathbb R^2$ 中稠密. 求 $\left\{\left(0,\frac1{2^n}\right):n\ge0\right\}\subset\mathbb R^2$ 的扎里斯基闭包.

### 解答 习题八

由**定义 3.28** (扎里斯基拓扑), 记 $Z\left(P_i\right)_{i\in I}=\left\{x:\forall i\in I,P_i\left(x\right)=0\right\}$. 验证闭集族满足**定义 3.21** (闭集): 空集 $Z\left(1\right)$ (常数多项式 $1$ 无零点); 全空间 $Z\left(0\right)$ (零多项式处处为零); 任意交

$$
\bigcap_{\alpha}Z\left(P_{\alpha,j}\right)_{j\in J_\alpha}=Z\left(\bigcup_\alpha\left\{P_{\alpha,j}\right\}\right)
$$

仍为公共零点集; 两个闭集之并

$$
Z\left(P_i\right)_{i\in I}\cup Z\left(Q_j\right)_{j\in J}=Z\left(P_iQ_j\right)_{i,j}
$$

(因 $x$ 在左端当且仅当某 $P_i\left(x\right)=0$ 或某 $Q_j\left(x\right)=0$, 当且仅当对一切 $\left(i,j\right)$ 有 $P_i\left(x\right)Q_j\left(x\right)=0$). 故闭集族满足**定义 3.21** (闭集), 扎里斯基拓扑成立.

扎里斯基开集稠密: 非空扎里斯基开集是某非零多项式 $P$ 的零点集的补集 $\mathbb R^2\setminus Z\left(P\right)$. 若 $Z\left(P\right)$ 含某开球, 则该开球内沿任一直线限制 $P$ 所得一元多项式在无限多点为零, 故恒为零; 从而 $P$ 在该开球上恒为零, 进而 $P\equiv0$, 矛盾. 故 $Z\left(P\right)$ 无内部. 由**定义 3.32** (稠密), 其补集 (扎里斯基开集) 稠密.

求闭包: 令 $S=\left\{\left(0,2^{-n}\right):n\ge0\right\}$. 多项式 $P$ 在 $S$ 上恒零当且仅当一元多项式 $P\left(0,y\right)$ 在无限多点 $y=2^{-n}$ 为零, 当且仅当 $P\left(0,\cdot\right)\equiv0$, 即 $x\mid P\left(x,y\right)$. 全体这样的 $P$ 的公共零点集为 $\left\{\left(0,y\right):y\in\mathbb R\right\}$, 即 $y$ 轴. 由**定义 3.26** (闭包), 这就是 $S$ 的扎里斯基闭包. $\blacksquare$

### 习题九

回忆拓扑基的定义. 回忆其等价刻画. 若去掉其中任一条件会怎样? 证明定义与刻画的等价性.

### 解答 习题九

由**定义 3.15** (拓扑基), 拓扑基的定义是: $\mathcal B\subset\mathcal P\left(X\right)$ 中元素的任意并构成 $X$ 上一个拓扑. 其等价刻画为: (1) $X=\bigcup_{B\in\mathcal B}B$; (2) 对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$, 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$.

**定义 $\Rightarrow$ 刻画**: 若 $\mathcal B$ 的任意并构成拓扑, 由**定义 3.18** (拓扑空间), 则 $X=\bigcup_{B\in\mathcal B}B$ 是开集, 即 (1). 又 $B_1\cap B_2$ 是两开集之交, 仍开, 故可表为 $\mathcal B$ 中元素之并; 任取 $x\in B_1\cap B_2$, 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 即 (2).

**刻画 $\Rightarrow$ 定义**: 设 (1)(2) 成立. 令 $\tau=\left\{\bigcup_{B\in\mathcal C}B:\mathcal C\subset\mathcal B\right\}$. 由 (1) $X\in\tau$, 空并 $\emptyset\in\tau$. $\tau$ 中任意并显然仍在 $\tau$ 中. 设 $U=\bigcup_{\alpha}B_\alpha\in\tau$, $V=\bigcup_{\beta}B'_\beta\in\tau$, 则 $U\cap V=\bigcup_{\alpha,\beta}\left(B_\alpha\cap B'_\beta\right)$. 对每个 $x\in B_\alpha\cap B'_\beta$, 由 (2) 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_\alpha\cap B'_\beta$, 故 $B_\alpha\cap B'_\beta$ 是若干 $\mathcal B$ 中元素之并, 从而 $U\cap V\in\tau$. 由**定义 3.18** (拓扑空间), $\tau$ 是拓扑.

去掉条件: 若去掉 (1), 例如 $\mathcal B=\left\{\emptyset\right\}$, 其任意并只能得 $\emptyset$, 盖不住 $X$; 若去掉 (2), 例如 $X=\mathbb R$, $\mathcal B=\left\{\left(-\infty,a\right):a\in\mathbb R\right\}\cup\left\{\left(b,+\infty\right):b\in\mathbb R\right\}$, 则 $\left(-\infty,1\right)\cap\left(0,+\infty\right)=\left(0,1\right)$ 不能表为 $\mathcal B$ 中元素之并, 故 $\mathcal B$ 的任意并不构成拓扑. $\blacksquare$

### 习题十

可分空间与具有可数基的空间.

(1) 证明具有可数基的拓扑空间必可分;

(2) 考虑 $\mathbb R$ 上以 $\mathcal B=\left\{\left(a,b\right]\subset\mathbb R:a< b\right\}$ 为基. 证明 $\mathcal B$ 确实是某拓扑 $\mathcal O$ 的基; 证明 $\mathcal O$ 可分但没有可数基; 证明 $\mathcal O$ 不来自度量拓扑 (即不可度量化).

### 解答 习题十

(1) 设 $\left\{B_n\right\}_{n\ge1}$ 是 $X$ 的可数基. 每点取 $x_n\in B_n$, 令 $D=\left\{x_n:n\ge1\right\}$. 由于 $\overline D\subset X$ 显然, 只需证明 $X\subset\overline D$. 任取 $x\in B_n\subset X$, 任取非空开集 $U\ni x$, 由**定义 3.15** (拓扑基) 存在某 $B_n\subset U$, 故存在一个 $x_n$ 满足 $x_n\in D\cap U\neq\emptyset$, 这说明 $x$ 是 $D$ 的边界点, 即 $x\in\overline D$. 由**定义 3.32** (稠密), $D$ 在 $X$ 中稠密; 由**定义 3.9** (可分), $X$ 可分.

(2) 先验基条件:

$$
\left(a,b\right]\cap\left(c,d\right]=\left(\max\left(a,c\right),\min\left(b,d\right)\right]
$$

当非空时仍是 $\mathcal B$ 中元素, 且 $\mathbb R=\bigcup_{b\in\mathbb R}\left(a,b\right]$ 覆盖全空间. 由**定义 3.15** (拓扑基), $\mathcal B$ 生成 $\mathbb R$ 上某拓扑 $\mathcal O$.

**可分**: 有理数集 $\mathbb Q$ 在 $\mathcal O$ 中稠密, 因每个 $\left(a,b\right]$ 都含有理数. 由**定义 3.9** (可分), $\mathcal O$ 可分.

**无可数基**: 反设 $\left\{W_n\right\}$ 是可数基. 对每个 $x\in\mathbb R$, 选基元素 $W_{n\left(x\right)}$ 使

$$
x\in W_{n\left(x\right)}\subset\left(x-1,x\right].
$$

$W_{n\left(x\right)}$ 作为某 $\left(a,b\right]$ 之并, 其右端点不超过 $x$ 且含 $x$, 故其右端点恰为 $x$. 于是 $x\neq y$ 时 $W_{n\left(x\right)}\neq W_{n\left(y\right)}$ (右端点不同). 这给出从不可数集 $\mathbb R$ 到可数集 $\left\{W_n\right\}$ 的单射, 矛盾. 故 $\mathcal O$ 无可数基.

**不可度量化**: 反设 $\mathcal O$ 来自某度量拓扑. 前面已证 $\mathcal O$ 可分 (有理数集 $\mathbb Q$ 稠密). 由**命题** (可分度量空间必有可数基), $\mathcal O$ 作为可分度量空间必有可数基; 但前面刚证 $\mathcal O$ 没有可数基, 矛盾. 故 $\mathcal O$ 不可度量化. $\blacksquare$

### 习题十一

基本邻域系. 回忆点 $x$ (或子集 $A$) 的邻域; $x$ (或 $A$) 的基本邻域系是 $x$ (或 $A$) 的一族邻域 $\mathcal P$, 使 $x$ (或 $A$) 的每个邻域都含某个 $\mathcal P$ 中元素 (**定义 3.30** (基本邻域系)).

(1) 证明度量空间中, 任取 $r_n\to0$, $B\left(x,r_n\right)$ 是 $x$ 的基本邻域系;

(2) 但当 $A$ 是子集时, $V_{\varepsilon}\left(A\right)=\left\{x:d\left(x,A\right)< \varepsilon\right\}$ 不一定是 $A$ 的基本邻域系. 例如取 $A=\left\{xy=1,x> 0\right\}\subset\mathbb R^2$ 与 $U=\left\{x,y> 0\right\}\subset\mathbb R^2$.

### 解答 习题十一

(1) 设 $U$ 是 $x$ 的任一邻域 (**定义 3.25** (邻域与极限)). 由**定义 6.36** (开球), 度量拓扑中存在 $r> 0$ 使 $B\left(x,r\right)\subset U$. 由 $r_n\to0$, 存在 $n$ 使 $r_n< r$, 于是

$$
B\left(x,r_n\right)\subset B\left(x,r\right)\subset U.
$$

由**定义 3.30** (基本邻域系), $\left\{B\left(x,r_n\right)\right\}$ 是 $x$ 的基本邻域系.

(2) 取题中 $A=\left\{\left(x,1/x\right):x> 0\right\}\subset\mathbb R^2$, $U=\left\{\left(x,y\right):x> 0,y> 0\right\}$. $U$ 开且 $A\subset U$, 故 $U$ 是 $A$ 的邻域. 对任意 $\varepsilon> 0$, 取点

$$
a=\left(\frac{\varepsilon}{2},\frac{2}{\varepsilon}\right)\in A,
$$

再取 $a'=\left(-\frac{\varepsilon}{4},\frac{2}{\varepsilon}\right)$. 由**定义 6.46** (点到集合的距离), $d\left(a',A\right)\le d\left(a',a\right)=\frac{3\varepsilon}{4}< \varepsilon$, 故 $a'\in V_{\varepsilon}\left(A\right)$ (**定义 6.47** ($\varepsilon$-邻域)). 但 $a'$ 的横坐标为负, $a'\notin U$. 于是对每个 $\varepsilon> 0$, $V_{\varepsilon}\left(A\right)\not\subset U$. 故没有任何 $V_{\varepsilon}\left(A\right)$ 含于 $U$, 由**定义 3.30** (基本邻域系), $\left\{V_{\varepsilon}\left(A\right)\right\}$ 不是 $A$ 的基本邻域系. $\blacksquare$

> 同样的构造基本邻域系的规则, 为什么全集就满足, 子集就不满足呢? 因为全集上定义的邻域必定全在全集内部; 而对于子集, 我们可以找到该子集的边界作为反例的邻域, 在其上的任何 $\varepsilon$-邻域都会超出其范围, 导致了这种构造方法的失效.

### 习题十二

豪斯多夫条件.

(1) 证明度量空间总是豪斯多夫的;

(2) 证明 $\mathbb A^n\left(\mathbb R\right)$ (或 $\mathbb R^n$) 的每个扎里斯基开集在通常拓扑下既开又稠密; 证明 $\mathbb A^n\left(\mathbb R\right)$ 的扎里斯基拓扑对任意 $n> 0$ 都不是豪斯多夫的.

### 解答 习题十二

(1) 设 $\left(X,d\right)$ 是**定义 6.35** (度量空间). 取 $x\neq y$, 令 $r=\frac13 d\left(x,y\right)> 0$. 由**定义 6.36** (开球), $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 是开集. 若二者相交, 由三角不等式

$$
d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)< 2r=\frac23 d\left(x,y\right),
$$

矛盾. 故 $B\left(x,r\right)\cap B\left(y,r\right)=\emptyset$. 由**定义 3.10** (豪斯多夫空间), 度量空间是豪斯多夫的.

(2) 由**定义 3.28** (扎里斯基拓扑), 扎里斯基闭集是若干多项式公共零点集. 非零多项式不能在任一通常开集上恒为零, 故扎里斯基闭集在通常拓扑下内部为空. 于是其补集, 即扎里斯基开集, 在通常拓扑下稠密 (**定义 3.32** (稠密)).

再证非豪斯多夫. 任取 $x\neq y$. 任一非空扎里斯基开集都稠密, 故任意两个非空扎里斯基开集相交. 因而不存在不相交的两个扎里斯基开集分别含 $x$ 与 $y$, 由**定义 3.10** (豪斯多夫空间), 扎里斯基拓扑不是豪斯多夫的. $\blacksquare$

### 习题十三

正规空间. 称拓扑空间 $X$ 是正规的, 若对任意含于开集 $V$ 的闭集 $F$, 存在开集 $U$ 使 $F\subset U\subset\overline U\subset V$. 证明这等价于说 $X$ 是豪斯多夫的, 且任意两不相交闭集有不相交邻域 (即**定义 7.6** (正规空间)). 证明度量空间正规 (可先证 $f:x\mapsto d\left(x,F\right)$ 当 $F$ 闭时连续).

### 解答 习题十三

先证两种定义等价. 设 $F$ 闭, $V$ 开, $F\subset V$. 若 $X$ 满足**定义 7.6** (正规空间), 对不相交闭集 $F$ 与 $X-V$ 取不相交开集 $U\supset F$ 与 $W\supset X-V$. 则 $\overline U\subset X-W\subset V$, 故 $F\subset U\subset\overline U\subset V$. 反过来, 设任意闭 $F\subset$ 开 $V$ 有 $U$ 使 $F\subset U\subset\overline U\subset V$. 对不相交闭集 $F,F'$, 取 $V=X-F'$ (开). 由假设存在 $U\supset F$ 使 $\overline U\subset X-F'$. 令 $W=X-\overline U$ (开, 由**定义 3.26** (闭包) 与**定义 3.21** (闭集)), 则 $F'\subset W$ 且 $U\cap W=\emptyset$. 故 $F,F'$ 有不相交邻域. 特别地单点闭 (取 $F=\left\{x\right\}$, 若 $X$ 满足条件则单点为闭), 即 $T_1$, 故为豪斯多夫的.

再证度量空间正规. 设 $F$ 闭. 由**定义 6.46** (点到集合的距离), $d\left(x,F\right)=\inf_{a\in F}d\left(x,a\right)$. 由**定义 6.35** (度量空间) 的三角不等式,

$$
\left|d\left(x,F\right)-d\left(y,F\right)\right|\le d\left(x,y\right),
$$

故 $x\mapsto d\left(x,F\right)$ 连续. 现取不相交闭集 $F,F'$. 令

$$
U=\left\{x:d\left(x,F\right)< d\left(x,F'\right)\right\},\quad
V=\left\{x:d\left(x,F'\right)< d\left(x,F\right)\right\}.
$$

二者开 (连续函数的原像, 由**定义 3.22** (连续映射)), 不相交, 且 $F\subset U$ (因 $x\in F$ 时 $d\left(x,F\right)=0< d\left(x,F'\right)$), $F'\subset V$. 由**定义 7.6** (正规空间), 度量空间正规. $\blacksquare$

### 习题十四

混合烧烤. 考虑 $\left[0,1\right]\subset\mathbb R$ 与另外两个不属于它的元 $\left\{0^{-},0^{+}\right\}$, 令 $X=\left\{0^{-},0^{+}\right\}\cup\left(0,1\right]$. 定义

$$
\mathcal B\left(x\right)=\left\{\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]:n\in\mathbb Z_{> 0}\right\}\quad\left(x\in\left(0,1\right]\right),
$$

与

$$
\mathcal B\left(0^{\pm}\right)=\left\{\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right):n\in\mathbb Z_{> 0}\right\}.
$$

证明 $\mathcal B=\bigcup_{x\in X}\mathcal B\left(x\right)$ 是某拓扑的基; 证明该拓扑不是豪斯多夫的; 证明 $0^{+}$ 没有由闭邻域组成的基本邻域系.

### 解答 习题十四

先验基条件. 对 $x\in\left(0,1\right]$, 两个形如 $\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]$ 的集之交仍含一个同形集; 对 $0^{\pm}$, $\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right)$ 之交为 $\left\{0^{\pm}\right\}\cup\left(0,1/\max\left(n,m\right)\right)$. 全体覆盖 $X$. 由**定义 3.15** (拓扑基), $\mathcal B$ 是某拓扑的基.

**非豪斯多夫**: 任取 $0^{-}$ 的邻域, 它含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$; $0^{+}$ 的邻域含某 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$. 二者都含 $\left(0,1/\max\left(n,m\right)\right)$, 故相交. 不存在不相交开集分别含 $0^{-}$ 与 $0^{+}$, 由**定义 3.10** (豪斯多夫空间), 该拓扑非豪斯多夫.

**$0^{+}$ 无闭邻域基本系**: 设 $C$ 是 $0^{+}$ 的任一闭邻域. 它必含某基本开邻域 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$, 特别含区间 $\left(0,\frac1m\right)$. 点 $0^{-}$ 的每个邻域含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$, 与 $\left(0,\frac1m\right)$ 相交, 故 $0^{-}\in\overline{\left(0,\frac1m\right)}$ (**定义 3.26** (闭包)). $C$ 闭且含 $\left(0,\frac1m\right)$, 故 $C$ 含其闭包, 从而 $0^{-}\in C$. 于是 $0^{+}$ 的任何闭邻域都含 $0^{-}$, 不可能含于开集 $U=\left\{0^{+}\right\}\cup\left(0,1\right)$ (它不含 $0^{-}$). 由**定义 3.30** (基本邻域系), $0^{+}$ 没有由闭邻域组成的基本邻域系. $\blacksquare$

### 习题十五

泛性质. 设 $X$ 是拓扑空间, $Y\subset X$ 配自然含映射 $\iota:Y\to X$. 证明 $Y$ 上的子空间拓扑具有如下性质: 对任意拓扑空间 $Z$ 与映射 $f:Z\to Y$, $f$ 连续当且仅当 $\iota\circ f:Z\to X$ 连续.

### 解答 习题十五

$\left(\Rightarrow\right)$ 若 $f:Z\to Y$ 连续, 由**定义 3.19** (子空间拓扑), 含映射 $\iota:Y\to X$ 连续. 由**定理 3.1** (复合连续), $\iota\circ f:Z\to X$ 连续.

$\left(\Leftarrow\right)$ 设 $\iota\circ f:Z\to X$ 连续. 任取 $Y$ 中开集 $O$. 由**定义 3.19** (子空间拓扑), $O=Y\cap U$, 其中 $U$ 是 $X$ 中开集. 于是

$$
f^{-1}\left(O\right)=f^{-1}\left(Y\cap U\right)=f^{-1}\left(U\right)=\left(\iota\circ f\right)^{-1}\left(U\right),
$$

最后一步用到 $f$ 映到 $Y$ 中. 由 $\iota\circ f$ 连续及**定义 3.22** (连续映射), 右端为 $Z$ 中开集. 故 $f^{-1}\left(O\right)$ 开, 由**定义 3.22** (连续映射), $f$ 连续. $\blacksquare$

> 证明中的核心步骤是 $f^{-1}\left(U\right)=\left(\iota\circ f\right)^{-1}\left(U\right)$, 这都归功于 $\iota$ 是含入映射, 即映射到 $Y$ 上的就相当于映射到 $X$ 上.

### 习题十六

设 $\prod_{i\in I}X_i$ 装备乘积拓扑, $p_k$ 是到第 $k$ 个因子的投影.

(1) 证明每个投影 $p_k$ 都是开映射, 即把开集映成开集;

(2) 举例说明投影一般不是闭映射, 即存在闭集其投影不闭;

(3) 证明开性的逆命题不成立: 存在 $W\subset\prod_{i\in I}X_i$ 使所有 $p_i\left(W\right)$ 都是开集, 但 $W$ 本身不是开集. 可在 $\mathbb R^2$ 中去掉若干点构造反例.

### 解答 习题十六

(1) 由**定义 3.11** (乘积拓扑), 乘积拓扑的基本开集形如 $\prod_{i\in I}U_i$, 其中 $U_i$ 在 $X_i$ 中开且除有限个外 $U_i=X_i$. 对固定的 $k$, 投影满足

$$
p_k\left(\prod_{i\in I}U_i\right)=U_k,
$$

而 $U_k$ 是 $X_k$ 中的开集. 任一开集 $W\subset\prod_{i\in I}X_i$ 都是基本开集之并 $W=\bigcup_{\alpha}V_\alpha$, 故

$$
p_k\left(W\right)=\bigcup_{\alpha}p_k\left(V_\alpha\right),
$$

由开集任意并仍开, $p_k\left(W\right)$ 是开集. 故每个 $p_k$ 都是开映射.

(2) 取 $\mathbb R^2$, 令 $A=\left\{\left(x,y\right):xy=1\right\}$. $A$ 包含它所有的极限点, 故是闭集; 由**定义 3.21** (闭集) 其补集 $\left\{xy\neq1\right\}$ 开. 但

$$
p_1\left(A\right)=\left\{x\in\mathbb R:\exists y,\,xy=1\right\}=\mathbb R\setminus\left\{0\right\},
$$

由**定义 3.21** (闭集) $\mathbb R\setminus\left\{0\right\}$ 不是闭集 ($0$ 是其极限点). 故投影不是闭映射.

(3) 取 $W=\mathbb R^2\setminus\left(\left\{0\right\}\times\left(0,1\right)\right)$. 先看两个投影: 对任意 $x\in\mathbb R$, 取 $y=2$ 则 $\left(x,2\right)\in W$, 故 $p_1\left(W\right)=\mathbb R$; 对任意 $y\in\mathbb R$, 取 $x=1$ 则 $\left(1,y\right)\in W$, 故 $p_2\left(W\right)=\mathbb R$. 两个投影都是开集. 但 $W$ 的补集为 $\left\{0\right\}\times\left(0,1\right)$, 它的闭包是 $\left\{0\right\}\times\left[0,1\right]$, 不等于自身, 由**定义 3.21** (闭集) 补集不闭, 故 $W$ 不是开集. 这说明所有投影开不能推出原集合开. $\blacksquare$

### 习题十七

序列, 度量空间与连续. 证明: 对**定义 6.35** (度量空间) 之间的映射 $f:X\to Y$, $f$ 连续当且仅当 $X$ 中每个收敛序列的像列在 $Y$ 中收敛. 证明中哪些地方用到了度量结构? 能否放松假设?

### 解答 习题十七

$\left(\Rightarrow\right)$ 设 $f$ 连续, $x_n\to x$. 任取 $f\left(x\right)$ 的邻域 $V$, 由**定义 3.22** (连续映射), $f^{-1}\left(V\right)$ 是 $x$ 的邻域; 由**定义 3.25** (邻域与极限), 充分大的 $n$ 有 $x_n\in f^{-1}\left(V\right)$, 即 $f\left(x_n\right)\in V$. 故 $f\left(x_n\right)\to f\left(x\right)$.

$\left(\Leftarrow\right)$ 设序列保持收敛. 反设 $f$ 在 $x$ 不连续, 则存在 $f\left(x\right)$ 的邻域 $V$ 使 $f^{-1}\left(V\right)$ 不是 $x$ 的邻域. 由**定义 6.36** (开球), $B\left(x,1/n\right)\not\subset f^{-1}\left(V\right)$, 取 $x_n\in B\left(x,1/n\right)\setminus f^{-1}\left(V\right)$. 则 $d\left(x_n,x\right)< 1/n\to0$, 即 $x_n\to x$, 但 $f\left(x_n\right)\notin V$, 故 $\left(f\left(x_n\right)\right)$ 不收敛到 $f\left(x\right)$, 矛盾.

用到度量结构之处在于: 用可数邻域基 $B\left(x,1/n\right)$ 把"$f^{-1}\left(V\right)$ 不是邻域"翻译成一列点 $\left(x_n\right)$, 即把否定连续性直接转化为序列. 在一般拓扑空间中, 这一翻译不成立, 但可放松为第一可数空间 (每点有可数邻域基). $\blacksquare$

### 习题十八

稠密集的邻域. $X$ 中稠密集的任意邻域是否覆盖 $X$? 可考虑 $\bigcup_{p/q}B\left(p/q,1/q^k\right)$ ($p/q\in\mathbb Q$, $k$ 充分大) 的例子.

### 解答 习题十八

不覆盖. 设 $X=\mathbb R$, $D=\mathbb Q$ 是**定义 3.32** (稠密) 的. 取 $U=\mathbb R\setminus\left\{\sqrt2\right\}$. $U$ 是开集, 由**定义 3.21** (闭集) 单点 $\left\{\sqrt2\right\}$ 闭故其补集开; $U$ 含 $\mathbb Q$, 即 $U$ 是稠密集 $\mathbb Q$ 的一个邻域, 但 $U\neq\mathbb R$. $\blacksquare$

> 一般地, 若 $D$ 稠密而 $U$ 是含 $D$ 的开集, 只能推出 $\overline U=X$: 由**定义 3.26** (闭包), $D\subset U$ 给出 $X=\overline D\subset\overline U$; 开集稠密不必等于全空间. 题中 $\bigcup_{p/q}B\left(p/q,1/q^k\right)$ 也是开稠密集, 取 $k$ 充分大时仍遗漏某些有理逼近系数很小的无理数, 故不等于 $\mathbb R$.
