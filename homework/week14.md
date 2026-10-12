# 作业 14

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}(U)$ 是开的. (教材 $\S3$)

> **定义 3.5** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 是包含 $A$ 的最小闭集. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.10** (豪斯多夫 空间)<br>称 $X$ 是 豪斯多夫 的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.2** (既开又闭集)<br>既开又闭的集合称为既开又闭集; $X$ 连通当且仅当 $\emptyset$ 与 $X$ 是仅有的既开又闭集. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f$ 连续, 则 $f(X)$ 连通. (教材 $\S4$)

> **定理 4.6** (扇形连通)<br>一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 $\S4$)

> **推论 4.7** (乘积连通)<br>连通集 $A,B$ 之积 $A\times B$ 连通; 有限个连通集的乘积连通. (教材 $\S4$)

> **定义 4.14** ($\epsilon$-链空间)<br>$X$ 是 $\varepsilon$-链的, 若任意 $a,b\in X$ 可由相邻距离 $<\varepsilon$ 的有限点列连接; 对一切 $\varepsilon>0$ 都成立称 $\varepsilon$-链空间. (题集 $\S4.5$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **推论 5.8** ($\mathbb R^n$ 紧集判据)<br>$F\subset\mathbb R^n$ 紧当且仅当 $F$ 闭且有界. (教材 $\S5$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d(x,x)=0$, $d(x,y)=0$ 推出 $x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.2** (开球)<br>$B(x,r)=\{y:d(x,y)<r\}$; 开球全体是度量拓扑的基. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>序列 $(x_n)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d(x_i,x_j)=0$. (教材 $\S6$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.18** (等距映射)<br>满足 $d(x,y)=d(f(x),f(y))$ 的映射 $f$. (题集 $\S3.4$)

### 习题一

序列与度量空间. 证明: **定义 3.10** (豪斯多夫 空间) 中序列的极限唯一. 证明: 在**定义 6.1** (度量空间) 中, 序列的聚点就是其子列极限. 若空间不是度量空间, 会发生什么?

### 解答 习题一

极限唯一: 设 $x_n\to x$ 且 $x_n\to y$, $x\neq y$. 由**定义 3.10** (豪斯多夫 空间), 存在不相交开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.5** (邻域与极限), 对充分大的 $n$ 有 $x_n\in U$, 又对充分大的 $n$ 有 $x_n\in V$, 与 $U\cap V=\emptyset$ 矛盾. 故 $x=y$.

聚点即子列极限: 在**定义 6.1** (度量空间) 中, 设 $x$ 是 $(x_n)$ 的聚点, 即 $x$ 的每个邻域含序列中无穷多项. 归纳地选 $n_k$ 严格递增, 使 $x_{n_k}\in B(x,1/k)$; 由**定义 6.2** (开球), $d(x_{n_k},x)<1/k\to0$, 故 $x_{n_k}\to x$. 反之, 若 $x_{n_k}\to x$, 由**定义 3.5** (邻域与极限), $x$ 的每个邻域含无穷多项, $x$ 是聚点.

若不是度量空间: 豪斯多夫性仍保证极限唯一, 但聚点一般不再是子列极限, 因为没有可数邻域基把"每个邻域含无穷多项"逐步收窄成一个子列; 此时需要用网来刻画聚点. $\blacksquare$

### 习题二

序列, 度量空间与连续. 证明: 对**定义 6.1** (度量空间) 之间的映射 $f:X\to Y$, $f$ 连续当且仅当 $X$ 中每个收敛序列的像列在 $Y$ 中收敛. 证明中哪些地方用到了度量结构? 能否放松假设?

### 解答 习题二

$(\Rightarrow)$ 设 $f$ 连续, $x_n\to x$. 任取 $f(x)$ 的邻域 $V$, 由**定义 3.3** (连续映射), $f^{-1}(V)$ 是 $x$ 的邻域; 由**定义 3.5** (邻域与极限), 充分大的 $n$ 有 $x_n\in f^{-1}(V)$, 即 $f(x_n)\in V$. 故 $f(x_n)\to f(x)$.

$(\Leftarrow)$ 设序列保持收敛. 反设 $f$ 在 $x$ 不连续, 则存在 $f(x)$ 的邻域 $V$ 使 $f^{-1}(V)$ 不是 $x$ 的邻域. 由**定义 6.2** (开球), $B(x,1/n)\not\subset f^{-1}(V)$, 取 $x_n\in B(x,1/n)\setminus f^{-1}(V)$. 则 $d(x_n,x)<1/n\to0$, 即 $x_n\to x$, 但 $f(x_n)\notin V$, 故 $(f(x_n))$ 不收敛到 $f(x)$, 矛盾.

用到度量结构之处在于: 用可数邻域基 $B(x,1/n)$ 把"$f^{-1}(V)$ 不是邻域"翻译成一列点 $(x_n)$, 即把否定连续性直接转化为序列. 在一般拓扑空间中, 这一翻译不成立, 但可放松为第一可数空间 (每点有可数邻域基); 一般空间中相应的等价刻画要用网. $\blacksquare$

### 习题三

连通性与连续函数. 证明: $X$ 是**定义 4.1** (连通空间) 当且仅当一切连续映射 $f:X\to\{0,1\}$ (目标装备离散拓扑) 都是常值的. 再设 $A,B$ 是两个连通度量空间, $X,Y$ 分别是 $A,B$ 的真子集. 证明 $C=(A\times B)\setminus(X\times Y)$ 是 $A\times B$ 的连通子集.

### 解答 习题三

$(\Rightarrow)$ 设 $X$ 是**定义 4.1** (连通空间), $f:X\to\{0,1\}$ 连续. 由**定理 4.2** (连续像连通), $f(X)$ 连通; 离散两点集 $\{0,1\}$ 的连通子集只有单点, 故 $f(X)$ 是单点集, 即 $f$ 常值.

$(\Leftarrow)$ 若 $X$ 不连通, 则 $X=U\cup V$, $U,V$ 非空不相交开集. 定义 $f$ 在 $U$ 上取 $0$, 在 $V$ 上取 $1$; 因 $U,V$ 既开又闭, 由**定义 3.3** (连续映射) $f$ 连续, 但 $f$ 非常值. 矛盾.

第二问: $C=((A\setminus X)\times B)\cup(A\times(B\setminus Y))$. 因 $X,Y$ 是真子集, 可取 $a_0\in A\setminus X$, $b_0\in B\setminus Y$. 固定 $b_0$, 集合 $A\times\{b_0\}$ 由**推论 4.7** (乘积连通) 连通. 对每个 $a\in A\setminus X$, 纤维 $\{a\}\times B$ 连通 (**推论 4.7** (乘积连通)), 且与 $A\times\{b_0\}$ 交于 $(a,b_0)$. 由**定理 4.6** (扇形连通), $S=A\times\{b_0\}\cup\bigcup_{a\in A\setminus X}\{a\}\times B$ 连通. 再对每个 $b\in B\setminus Y$, 纤维 $A\times\{b\}$ 连通, 且与 $S$ 交于 $(a_0,b)$. 再用**定理 4.6** (扇形连通), 加入所有 $A\times\{b\}$ 后仍连通, 所得正是 $C$. $\blacksquare$

### 习题四

连通性与边界. 设 $E$ 是连通度量空间, $F$ 是 $E$ 的闭集. 证明: 若 $F$ 的边界 $\partial F$ 连通, 则 $F$ 连通. 可先证明连续函数的限制连续. 再举例说明 $F$ 不假设闭时结论失效.

### 解答 习题四

反设 $F$ 不连通. 则 $F$ 有非空分离 $F=A\cup B$, $A,B$ 非空不相交, 且在 $F$ 中既开又闭. 因 $F$ 在 $E$ 中闭, 由**定义 3.2** (闭集), $A,B$ 在 $E$ 中也闭. 边界 $\partial F=F\cap\overline{E\setminus F}$. 断言

$$
\partial F=(A\cap\overline{E\setminus F})\cup(B\cap\overline{E\setminus F}),
$$

两边都非空. 若 $A\cap\overline{E\setminus F}=\emptyset$, 则 $A\subset\operatorname{int}(F)$; 又 $A$ 在 $F$ 中开, 即 $A=F\cap O$ ($O$ 开于 $E$), 于是 $A=O\cap\operatorname{int}(F)$ 在 $E$ 中开. $A$ 在 $E$ 中既开又闭, 由**定义 4.2** (既开又闭集), $E$ 连通推出 $A=\emptyset$ 或 $E$, 与 $A$ 是 $F$ 的非空真子集矛盾. 故 $A\cap\overline{E\setminus F}\neq\emptyset$, 同理 $B\cap\overline{E\setminus F}\neq\emptyset$. 这两个非空不交闭集分离了 $\partial F$, 与 $\partial F$ 连通矛盾. 故 $F$ 连通.

反例: 取 $E=[0,1]$, $F=[0,1/2)\cup(1/2,1]$. $F$ 不闭, 且不连通; 但 $\partial F=\{1/2\}$ 是单点, 连通. $\blacksquare$

### 习题五

链空间. 称度量空间 $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in X$ 可由有限点列 $x_0=a,\dots,x_n=b$ 连接使 $d(x_i,x_{i+1})<\varepsilon$; 对一切 $\varepsilon>0$ 都成立称**定义 4.14** ($\epsilon$-链空间). 证明: $X$ 连通则 $X$ 是 $\varepsilon$-链空间; $X$ 紧且 $\varepsilon$-链则 $X$ 连通; 举例说明 $\varepsilon$-链空间可以不连通.

### 解答 习题五

连通 $\Rightarrow$ $\varepsilon$-链: 固定 $\varepsilon>0$, 定义 $a\sim b$ 为存在 $\varepsilon$-链. 等价类在**定义 6.2** (开球) $B(x,\varepsilon)$ 下封闭, 故每个等价类开; 其余等价类之并也开. 由**定义 4.2** (既开又闭集), 连通空间只有一个等价类, 即 $X$ 是**定义 4.14** ($\epsilon$-链空间).

紧且 $\varepsilon$-链 $\Rightarrow$ 连通: 反设 $X$ 不连通, 则 $X=A\cup B$ 为非空不交闭集分离. $A,B$ 是紧度量空间, 距离 $\delta=d(A,B)>0$: 取 $a_n\in A$, $b_n\in B$ 使 $d(a_n,b_n)\to\delta$, 由**定理 6.1** (紧=序列紧) 抽子列 $a_{n_j}\to a\in A$, $b_{n_j}\to b\in B$, 得 $d(a,b)=\delta>0$. 取 $\varepsilon<\delta$, 则 $\varepsilon$-链不可能从 $A$ 跨到 $B$, 与 $\varepsilon$-链矛盾.

$\varepsilon$-链但不连通的例子: 有理数集 $\mathbb Q$ 装备通常度量. 对任意 $\varepsilon>0$, 任意两个有理数之间可插入间距小于 $\varepsilon$ 的有理点列, 故 $\mathbb Q$ 是 $\varepsilon$-链的; 但 $\mathbb Q$ 完全不连通. $\blacksquare$

### 习题六

不动点与连通性. 设 $X$ 是度量空间, 假设一切连续映射 $f:X\to X$ 都有不动点. 证明 $X$ 连通. 再问: 若 $X$ 紧且连通, 是否一切连续映射 $f:X\to X$ 都有不动点?

### 解答 习题六

反设 $X$ 不连通, 则 $X=A\cup B$, $A,B$ 非空不相交且由**定义 4.2** (既开又闭集) 既开又闭. 取 $a\in A$, $b\in B$, 定义 $f$: 在 $A$ 上取常值 $b$, 在 $B$ 上取常值 $a$. 因 $A,B$ 既开又闭, 由**定义 3.3** (连续映射) $f$ 连续; 但 $f(A)\subset B$, $f(B)\subset A$, 而 $A\cap B=\emptyset$, 故 $f$ 无不动点. 矛盾. 故 $X$ 连通.

紧且连通不足以保证不动点: 取圆周 $X=S^1$, 旋转 $90^\circ$ 的映射 $f(e^{i\theta})=e^{i(\theta+\pi/2)}$. $S^1$ 紧且连通, $f$ 连续, 但 $f$ 无不动点. $\blacksquare$

### 习题七

恰一个聚点. 设 $f:\mathbb R^n\to\mathbb R^n$ 连续, 且序列 $(f^n(x_0))$ 恰有一个聚点. 证明该序列收敛.

### 解答 习题七

记 $x_n=f^n(x_0)$, 设唯一聚点为 $z$. 取子列 $x_{n_j}\to z$. 由 $f$ 连续, $x_{n_j+1}=f(x_{n_j})\to f(z)$. 而 $(x_{n_j+1})$ 是 $(x_n)$ 的子列, 其极限 $f(z)$ 必为聚点, 由唯一性 $f(z)=z$.

反设 $(x_n)$ 不收敛到 $z$. 则存在 $\varepsilon>0$ 与无穷多个 $n$ 使 $\|x_n-z\|\ge\varepsilon$. 从每个 $n_j$ 出发, 若其后轨道始终在 $B(z,\varepsilon)$ 内, 则尾部落在紧闭球中, 由**推论 5.8** ($\mathbb R^n$ 紧集判据) 与**定理 6.1** (紧=序列紧), 该尾部的任何聚点都是 $z$, 矛盾于不收敛. 故从每个 $n_j$ 出发, 存在第一个 $m_j>n_j$ 使 $\|x_{m_j}-z\|=\varepsilon$. 点 $x_{m_j}$ 都落在紧球面 $\partial B(z,\varepsilon)$ 上, 抽子列 $x_{m_{j_k}}\to w$, $\|w-z\|=\varepsilon$. 则 $w$ 是 $(x_n)$ 的聚点且 $w\neq z$, 矛盾. 故 $(x_n)\to z$. $\blacksquare$

### 习题八

等距与紧性. 设 $K\subset\mathbb R^n$ 是非空紧集, $\varepsilon>0$. 称 $A\subset K$ 是 $\varepsilon$-分离的, 若 $x\neq y$ 蕴含 $|x-y|>\varepsilon$. 证明存在有限数 $M(\varepsilon)$, 使 $K$ 中任何 $\varepsilon$-分离集的基数不超过 $M(\varepsilon)$. 再证明: 若 $f:K\to K$ 是**定义 6.18** (等距映射), 则 $f$ 满.

### 解答 习题八

反设存在任意大的 $\varepsilon$-分离集. 则可取两两不同的点列 $x_m\in K$ 使 $m\neq m'$ 时 $|x_m-x_{m'}|>\varepsilon$. 由**定理 5.3** ($\mathbb R^n$ 中的紧集) 与**定理 6.1** (紧=序列紧), $(x_m)$ 有收敛子列; 收敛子列是**定义 6.3** (柯西列), 充分靠后两项距离 $<\varepsilon$, 与 $\varepsilon$-分离矛盾. 故存在 $M(\varepsilon)$.

满性: 反设 $f$ 不满, 取 $p\notin f(K)$. $f(K)$ 紧, 由**定理 5.3** ($\mathbb R^n$ 中的紧集) 闭, 故 $\delta=d(p,f(K))>0$. 轨道 $p,f(p),f^2(p),\dots$ 满足

$$
|f^{n+1}(p)-f^n(p)|=|f(f^n(p))-f(f^{n-1}(p))|=|f^n(p)-f^{n-1}(p)|\ge\cdots\ge|f(p)-p|\ge\delta,
$$

其中等号用了**定义 6.18** (等距映射). 但由**定理 6.1** (紧=序列紧), $K$ 中轨道有收敛子列, 必为**定义 6.3** (柯西列), 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. $\blacksquare$

### 习题九

稠密集的邻域. $X$ 中稠密集的任意邻域是否覆盖 $X$? 可考虑 $\bigcup_{p/q}B(p/q,1/q^k)$ ($p/q\in\mathbb Q$, $k$ 充分大) 的例子.

### 解答 习题九

不覆盖. 设 $X=\mathbb R$, $D=\mathbb Q$ 是**定义 3.8** (稠密) 的. 取 $U=\mathbb R\setminus\{\sqrt2\}$. $U$ 是开集, 由**定义 3.2** (闭集) 单点 $\{\sqrt2\}$ 闭故其补集开; $U$ 含 $\mathbb Q$, 即 $U$ 是稠密集 $\mathbb Q$ 的一个邻域, 但 $U\neq\mathbb R$.

一般地, 若 $D$ 稠密而 $U$ 是含 $D$ 的开集, 只能推出 $\overline U=X$: 由**定义 3.6** (闭包), $D\subset U$ 给出 $X=\overline D\subset\overline U$; 开集稠密不必等于全空间. 题中 $\bigcup_{p/q}B(p/q,1/q^k)$ 也是开稠密集, 取 $k$ 充分大时仍遗漏某些有理逼近系数很小的无理数, 故不等于 $\mathbb R$. $\blacksquare$

### 习题十

闭集之和. 设 $E=\mathbb R^n$, $A,B\subset E$.

(1) 证明: 若 $A$ 紧而 $B$ 闭, 则 $A+B=\{a+b:a\in A,b\in B\}$ 闭;

(2) 证明: 若 $A,B$ 都闭, $A+B$ 不必闭.

### 解答 习题十

(1) 取序列 $a_n+b_n\in A+B$ 收敛到 $y$. 由**定理 6.1** (紧=序列紧), $A$ 紧, 故 $(a_n)$ 有子列 $a_{n_j}\to a\in A$. 则 $b_{n_j}=(a_{n_j}+b_{n_j})-a_{n_j}\to y-a$. 因 $B$ 闭, 由**定义 3.2** (闭集), $y-a\in B$. 故 $y=a+(y-a)\in A+B$. $A+B$ 含一切收敛序列的极限, 故闭.

(2) 反例: 取 $A=\{(x,0):x\in\mathbb R\}$, $B=\{(x,1/x):x>0\}$. $A$ 与 $B$ 都闭. 但

$$
A+B=\{(x+t,1/t):t>0\}=\{(u,v):v>0\},
$$

即开的上半平面, 由**定义 3.2** (闭集) 它不是闭集. $\blacksquare$
