# 作业 6

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.5** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10** (豪斯多夫 空间)<br>称 $X$ 是 豪斯多夫 的, 若任意一对不同点都有不相交的邻域. (教材 $\S3$)

> **定义 3.15** (拓扑基)<br>$\mathcal B\subset\mathcal P\left(X\right)$ 满足 $X=\bigcup\mathcal B$ 且 $B_1\cap B_2$ 含某 $B_3$, 则以 $\mathcal B$ 中元素之并为开集生成最粗拓扑. (教材 $\S3$)

> **定义 3.19** (子空间拓扑)<br>$T_A=\left\{U\cap A:U\in T_X\right\}$; 它是使含映射 $\iota:A\to X$ 连续的意义下的最粗拓扑. (教材 $\S3$)

> **定义 3.28** (扎里斯基拓扑)<br>$\mathbb A^n\left(K\right)$ 中闭集为若干多项式公共零点集. (题集 $\S1.4$)

> **定义 3.30** (基本邻域系)<br>$x$ 的邻域族 $\mathcal P$, 使 $x$ 的每个邻域都含某个 $\mathcal P$ 中元素. (题集 $\S2.4$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.2** (开球)<br>$B\left(x,r\right)=\left\{y:d\left(x,y\right)<r\right\}$; 开球全体是度量拓扑的基. (教材 $\S6$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.16** ($\epsilon$-邻域)<br>$U_{\varepsilon}\left(A\right)=\left\{x:d\left(x,A\right)<\varepsilon\right\}$. (题集 $\S3.2$)

> **定义 7.1** (正规空间)<br>单点闭且任意两不相交闭集可被不相交开集分离, 即 $T_4$. (教材 $\S7$)

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

### 习题一

可分空间与具有可数基的空间.

(1) 证明具有可数基的拓扑空间必可分;

(2) 考虑 $\mathbb R$ 上以 $\mathcal B=\left\{\left(a,b\right]\subset\mathbb R:a<b\right\}$ 为基. 证明 $\mathcal B$ 确实是某拓扑 $\mathcal O$ 的基; 证明 $\mathcal O$ 可分但没有可数基; 证明 $\mathcal O$ 不来自度量拓扑 (即不可度量化).

### 解答 习题一

(1) 设 $\left\{B_n\right\}_{n\ge1}$ 是 $X$ 的可数基. 每点取 $x_n\in B_n$, 令 $D=\left\{x_n:n\ge1\right\}$. 任取非空开集 $U$, 由**定义 3.15** (拓扑基) 存在某 $B_n\subset U$, 故 $x_n\in D\cap U\neq\emptyset$. 由**定义 3.8** (稠密), $D$ 在 $X$ 中稠密; 由**定义 3.9** (可分), $X$ 可分.

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

**不可度量化**: 若 $\mathcal O$ 来自某度量 $d$ (**定义 6.1** (度量空间)), 则因 $\mathcal O$ 可分, 取可数稠密集 $D$, 全体开球 $B\left(q,1/k\right)$ ($q\in D$, $k\ge1$, 见**定义 6.2** (开球)) 构成 $\mathcal O$ 的可数基, 与上一段矛盾. 故 $\mathcal O$ 不可度量化. $\blacksquare$

### 习题二

基本邻域系. 回忆点 $x$ (或子集 $A$) 的邻域; $x$ (或 $A$) 的基本邻域系是 $x$ (或 $A$) 的一族邻域 $\mathcal P$, 使 $x$ (或 $A$) 的每个邻域都含某个 $\mathcal P$ 中元素 (**定义 3.30** (基本邻域系)).

(1) 证明度量空间中, 任取 $r_n\to0$, $B\left(x,r_n\right)$ 是 $x$ 的基本邻域系;

(2) 但当 $A$ 是子集时, $V_{\varepsilon}\left(A\right)=\left\{x:d\left(x,A\right)<\varepsilon\right\}$ 不一定是 $A$ 的基本邻域系. 例如取 $A=\left\{xy=1,x>0\right\}\subset\mathbb R^2$ 与 $U=\left\{x,y>0\right\}\subset\mathbb R^2$.

### 解答 习题二

(1) 设 $U$ 是 $x$ 的任一邻域 (**定义 3.5** (邻域与极限)). 由**定义 6.2** (开球), 度量拓扑中存在 $r>0$ 使 $B\left(x,r\right)\subset U$. 由 $r_n\to0$, 存在 $n$ 使 $r_n<r$, 于是

$$
B\left(x,r_n\right)\subset B\left(x,r\right)\subset U.
$$

由**定义 3.30** (基本邻域系), $\left\{B\left(x,r_n\right)\right\}$ 是 $x$ 的基本邻域系.

(2) 取题中 $A=\left\{\left(x,1/x\right):x>0\right\}\subset\mathbb R^2$, $U=\left\{\left(x,y\right):x>0,y>0\right\}$. $U$ 开且 $A\subset U$, 故 $U$ 是 $A$ 的邻域. 对任意 $\varepsilon>0$, 取点

$$
a=\left(\frac{\varepsilon}{2},\frac{2}{\varepsilon}\right)\in A,
$$

再取 $a'=\left(-\frac{\varepsilon}{4},\frac{2}{\varepsilon}\right)$. 由**定义 6.15** (点到集合的距离), $d\left(a',A\right)\le d\left(a',a\right)=\frac{3\varepsilon}{4}<\varepsilon$, 故 $a'\in V_{\varepsilon}\left(A\right)$ (**定义 6.16** ($\epsilon$-邻域)). 但 $a'$ 的横坐标为负, $a'\notin U$. 于是对每个 $\varepsilon>0$, $V_{\varepsilon}\left(A\right)\not\subset U$. 故没有任何 $V_{\varepsilon}\left(A\right)$ 含于 $U$, 由**定义 3.30** (基本邻域系), $\left\{V_{\varepsilon}\left(A\right)\right\}$ 不是 $A$ 的基本邻域系. $\blacksquare$

### 习题三

豪斯多夫条件.

(1) 证明度量空间总是 豪斯多夫 的;

(2) 证明 $\mathbb A^n\left(\mathbb R\right)$ (或 $\mathbb R^n$) 的每个扎里斯基开集在通常拓扑下既开又稠密; 证明 $\mathbb A^n\left(\mathbb R\right)$ 的扎里斯基拓扑对任意 $n>0$ 都不是 豪斯多夫 的.

### 解答 习题三

(1) 设 $\left(X,d\right)$ 是**定义 6.1** (度量空间). 取 $x\neq y$, 令 $r=\frac13 d\left(x,y\right)>0$. 由**定义 6.2** (开球), $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 是开集. 若二者相交, 由三角不等式

$$
d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)<2r=\frac23 d\left(x,y\right),
$$

矛盾. 故 $B\left(x,r\right)\cap B\left(y,r\right)=\emptyset$. 由**定义 3.10** (豪斯多夫 空间), 度量空间是 豪斯多夫 的.

(2) 由**定义 3.28** (扎里斯基拓扑), 扎里斯基闭集是若干多项式公共零点集. 非零多项式不能在任一通常开集上恒为零, 故扎里斯基闭集在通常拓扑下内部为空. 于是其补集, 即扎里斯基开集, 在通常拓扑下稠密 (**定义 3.8** (稠密)).

再证非 豪斯多夫. 任取 $x\neq y$. 任一非空扎里斯基开集都稠密, 故任意两个非空扎里斯基开集相交. 因而不存在不相交的两个扎里斯基开集分别含 $x$ 与 $y$, 由**定义 3.10** (豪斯多夫 空间), 扎里斯基拓扑不是 豪斯多夫 的. $\blacksquare$

### 习题四

正规空间. 称拓扑空间 $X$ 是正规的, 若对任意含于开集 $V$ 的闭集 $F$, 存在开集 $U$ 使 $F\subset U\subset\overline U\subset V$. 证明这等价于说 $X$ 是 豪斯多夫 的, 且任意两不相交闭集有不相交邻域 (即**定义 7.1** (正规空间)). 证明度量空间正规 (可先证 $f:x\mapsto d\left(x,F\right)$ 当 $F$ 闭时连续).

### 解答 习题四

先证两种定义等价. 设 $F$ 闭, $V$ 开, $F\subset V$. 若 $X$ 满足**定义 7.1** (正规空间), 对不相交闭集 $F$ 与 $X-V$ 取不相交开集 $U\supset F$ 与 $W\supset X-V$. 则 $\overline U\subset X-W\subset V$, 故 $F\subset U\subset\overline U\subset V$. 反过来, 设任意闭 $F\subset$ 开 $V$ 有 $U$ 使 $F\subset U\subset\overline U\subset V$. 对不相交闭集 $F,F'$, 取 $V=X-F'$ (开). 由假设存在 $U\supset F$ 使 $\overline U\subset X-F'$. 令 $W=X-\overline U$ (开, 由**定义 3.6** (闭包) 与**定义 3.2** (闭集)), 则 $F'\subset W$ 且 $U\cap W=\emptyset$. 故 $F,F'$ 有不相交邻域. 特别地单点闭 (取 $F=\left\{x\right\}$, 若 $X$ 满足条件则单点为闭), 即 $T_1$, 故为 豪斯多夫 的.

再证度量空间正规. 设 $F$ 闭. 由**定义 6.15** (点到集合的距离), $d\left(x,F\right)=\inf_{a\in F}d\left(x,a\right)$. 由**定义 6.1** (度量空间) 的三角不等式,

$$
\left|d\left(x,F\right)-d\left(y,F\right)\right|\le d\left(x,y\right),
$$

故 $x\mapsto d\left(x,F\right)$ 连续. 现取不相交闭集 $F,F'$. 令

$$
U=\left\{x:d\left(x,F\right)<d\left(x,F'\right)\right\},\qquad
V=\left\{x:d\left(x,F'\right)<d\left(x,F\right)\right\}.
$$

二者开 (连续函数的原像, 由**定义 3.3** (连续映射)), 不相交, 且 $F\subset U$ (因 $x\in F$ 时 $d\left(x,F\right)=0<d\left(x,F'\right)$), $F'\subset V$. 由**定义 7.1** (正规空间), 度量空间正规. $\blacksquare$

### 习题五

混合烧烤. 考虑 $\left[0,1\right]\subset\mathbb R$ 与另外两个不属于它的元 $\left\{0^{-},0^{+}\right\}$, 令 $X=\left\{0^{-},0^{+}\right\}\cup\left(0,1\right]$. 定义

$$
\mathcal B\left(x\right)=\left\{\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]:n\in\mathbb Z_{>0}\right\}\quad\left(x\in\left(0,1\right]\right),
$$

与

$$
\mathcal B\left(0^{\pm}\right)=\left\{\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right):n\in\mathbb Z_{>0}\right\}.
$$

证明 $\mathcal B=\bigcup_{x\in X}\mathcal B\left(x\right)$ 是某拓扑的基; 证明该拓扑不是 豪斯多夫 的; 证明 $0^{+}$ 没有由闭邻域组成的基本邻域系.

### 解答 习题五

先验基条件. 对 $x\in\left(0,1\right]$, 两个形如 $\left(x-\frac1n,x+\frac1n\right)\cap\left(0,1\right]$ 的集之交仍含一个同形集; 对 $0^{\pm}$, $\left\{0^{\pm}\right\}\cup\left(0,\frac1n\right)$ 之交为 $\left\{0^{\pm}\right\}\cup\left(0,1/\max\left(n,m\right)\right)$. 全体覆盖 $X$. 由**定义 3.15** (拓扑基), $\mathcal B$ 是某拓扑的基.

**非 豪斯多夫**: 任取 $0^{-}$ 的邻域, 它含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$; $0^{+}$ 的邻域含某 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$. 二者都含 $\left(0,1/\max\left(n,m\right)\right)$, 故相交. 不存在不相交开集分别含 $0^{-}$ 与 $0^{+}$, 由**定义 3.10** (豪斯多夫 空间), 该拓扑非 豪斯多夫.

**$0^{+}$ 无闭邻域基本系**: 设 $C$ 是 $0^{+}$ 的任一闭邻域. 它必含某基本开邻域 $\left\{0^{+}\right\}\cup\left(0,\frac1m\right)$, 特别含区间 $\left(0,\frac1m\right)$. 点 $0^{-}$ 的每个邻域含某 $\left\{0^{-}\right\}\cup\left(0,\frac1n\right)$, 与 $\left(0,\frac1m\right)$ 相交, 故 $0^{-}\in\overline{\left(0,\frac1m\right)}$ (**定义 3.6** (闭包)). $C$ 闭且含 $\left(0,\frac1m\right)$, 故 $C$ 含其闭包, 从而 $0^{-}\in C$. 于是 $0^{+}$ 的任何闭邻域都含 $0^{-}$, 不可能含于开集 $U=\left\{0^{+}\right\}\cup\left(0,1\right)$ (它不含 $0^{-}$). 由**定义 3.30** (基本邻域系), $0^{+}$ 没有由闭邻域组成的基本邻域系. $\blacksquare$

### 习题六

泛性质. 设 $X$ 是拓扑空间, $Y\subset X$ 配自然含映射 $\iota:Y\to X$. 证明 $Y$ 上的子空间拓扑具有如下性质: 对任意拓扑空间 $Z$ 与映射 $f:Z\to Y$, $f$ 连续当且仅当 $\iota\circ f:Z\to X$ 连续.

### 解答 习题六

$(\Rightarrow)$ 若 $f:Z\to Y$ 连续, 由**定义 3.19** (子空间拓扑), 含映射 $\iota:Y\to X$ 连续. 由**定理 3.1** (复合连续), $\iota\circ f:Z\to X$ 连续.

$(\Leftarrow)$ 设 $\iota\circ f:Z\to X$ 连续. 任取 $Y$ 中开集 $O$. 由**定义 3.19** (子空间拓扑), $O=Y\cap U$, 其中 $U$ 是 $X$ 中开集. 于是

$$
f^{-1}\left(O\right)=f^{-1}\left(Y\cap U\right)=f^{-1}\left(U\right)=\left(\iota\circ f\right)^{-1}\left(U\right),
$$

最后一步用到 $f$ 映到 $Y$ 中. 由 $\iota\circ f$ 连续及**定义 3.3** (连续映射), 右端为 $Z$ 中开集. 故 $f^{-1}\left(O\right)$ 开, 由**定义 3.3** (连续映射), $f$ 连续. $\blacksquare$
