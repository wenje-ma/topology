# 作业 7

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 5.1** (开覆盖与有限子覆盖)<br>开覆盖 $\left\{U_i\right\}$ 满足 $X=\bigcup_i U_i$; 有限子覆盖为仍覆盖 $X$ 的有限子族. (教材 $\S5$)

> **定义 5.2** (紧致空间)<br>称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.3** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 5.4** (闭子集紧)<br>若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **推论 5.11** (紧空间上连续函数取最大值)<br>紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价. (教材 $\S6$)

> **定义 6.6** (序列紧致)<br>称 $X$ 是序列紧致的, 若 $X$ 中每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.5** (单点紧化)<br>亚历山德罗夫紧化 $\overline X=X\cup\left\{\infty\right\}$, 以 $\left(X-K\right)\cup\left\{\infty\right\}$ (其中 $K\subset X$ 紧致) 为 $\infty$ 的邻域. (教材 $\S7$)

### 习题一

证明 $\left\{0,1\right\}^{\left[0,1\right]}$ 赋通常乘积拓扑不是序列紧致的.

### 解答 习题一

把 $\left\{0,1\right\}^{\left[0,1\right]}$ 中的点视为函数 $f:\left[0,1\right]\to\left\{0,1\right\}$. 由**定义 3.11** (乘积拓扑), 在乘积拓扑下 $f_n\to f$ 当且仅当每个坐标 $t\in\left[0,1\right]$ 都有 $f_n\left(t\right)\to f\left(t\right)$.

对每个 $n\ge1$, 定义 $f_n\left(t\right)$ 为 $t$ 的二进制展开中小数点后第 $n$ 位数字 (二进有理点固定取其一展开). 任取严格递增的正整数列 $n_1<n_2<\dots$, 我们证明 $\left\{f_{n_k}\right\}$ 不收敛. 取 $t^{*}\in\left[0,1\right]$, 使其二进制展开在第 $n_{2k-1}$ 位为 $0$, 在第 $n_{2k}$ 位为 $1$, 其余位任意 (例如取 $0$). 则坐标 $t^{*}$ 处 $f_{n_k}\left(t^{*}\right)$ 依次为 $0,1,0,1,\dots$, 不收敛. 由上一段的坐标判据, $\left\{f_{n_k}\right\}$ 在乘积拓扑下不收敛. 由**定义 6.6** (序列紧致), 任意子列都不收敛, 故 $\left\{0,1\right\}^{\left[0,1\right]}$ 不是序列紧致的.

### 习题二

称集合族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空. 证明: 空间 $X$ 紧致等价于, $X$ 中任意具有限交性质的闭集族 $\mathcal F$ 都满足 $\bigcap_{F\in\mathcal F}F\neq\emptyset$.

### 解答 习题二

由**定义 5.1** (开覆盖与有限子覆盖) 与**定义 5.2** (紧致空间), 分两个方向证明.

($\Rightarrow$) 设 $X$ 紧致, $\mathcal F$ 是具有限交性质的闭集族. 若 $\bigcap_{F\in\mathcal F}F=\emptyset$, 则 $\left\{X\setminus F:F\in\mathcal F\right\}$ 是 $X$ 的开覆盖 (闭集之补为开). 由**定义 5.2** (紧致空间), 它有有限子覆盖 $X\setminus F_1,\dots,X\setminus F_k$, 即 $X=\bigcup_{i=1}^{k}\left(X\setminus F_i\right)$. 取补集得 $\bigcap_{i=1}^{k}F_i=\emptyset$, 与**定义 5.3** (有限交性质) 矛盾. 故全族之交非空.

($\Leftarrow$) 设任意具有限交性质的闭集族之交非空. 任取 $X$ 的开覆盖 $\left\{U_i\right\}$. 令 $F_i=X\setminus U_i$, 则各 $F_i$ 闭. 若 $\left\{U_i\right\}$ 无有限子覆盖, 则任意有限个 $F_{i_1},\dots,F_{i_k}$ 满足

$$
\bigcap_{j=1}^{k}F_{i_j}=X\setminus\bigcup_{j=1}^{k}U_{i_j}\neq\emptyset,
$$

即 $\left\{F_i\right\}$ 具有限交性质. 由假设 $\bigcap_iF_i\neq\emptyset$, 即 $X\setminus\bigcup_iU_i\neq\emptyset$, 与 $\left\{U_i\right\}$ 覆盖 $X$ 矛盾. 故存在有限子覆盖, 由**定义 5.2** (紧致空间), $X$ 紧致. $\blacksquare$

### 习题三

设 $A,B$ 是度量空间 $\left(X,d\right)$ 中不相交的闭集, 且 $A$ 紧致. 证明 $d\left(A,B\right)>0$.

### 解答 习题三

令 $g\left(x\right)=d\left(x,B\right)$. 由**定义 6.15** (点到集合的距离), $g$ 有定义. 由**定义 6.1** (度量空间) 的三角不等式, $\left|d\left(x,B\right)-d\left(y,B\right)\right|\le d\left(x,y\right)$, 故 $g$ 连续. 因 $A$ 紧致, 由**推论 5.11** (紧空间上连续函数取最大值), $g$ 在 $A$ 上取到最小值

$$
m=\min_{a\in A}g\left(a\right)=\inf_{a\in A,\,b\in B}d\left(a,b\right)=d\left(A,B\right).
$$

若 $m=0$, 则存在 $a_0\in A$ 使 $d\left(a_0,B\right)=0$, 即 $a_0$ 是 $B$ 的极限点; 但 $B$ 是闭集, 故 $a_0\in B$, 与 $A\cap B=\emptyset$ 矛盾. 故 $m>0$, 即 $d\left(A,B\right)>0$. $\blacksquare$

### 习题四

设 $\left(X,d\right)$ 是无孤立点的度量空间. 证明: $X$ 紧致当且仅当对任意一对不相交闭集 $A,B$, 都有 $d\left(A,B\right)>0$.

### 解答 习题四

($\Rightarrow$) 设 $X$ 紧致, $A,B$ 为不相交闭集. 由**定理 5.4** (闭子集紧), $A$ 紧致. 由习题三的论证 (连续函数 $d\left(\cdot,B\right)$ 在 $A$ 上取到正最小值) 即得 $d\left(A,B\right)>0$.

($\Leftarrow$) 反证, 设 $X$ 不紧致. 由**定理 6.1** (紧=序列紧), $X$ 不是序列紧致的, 故存在序列 $\left\{x_n\right\}$ 无收敛子列. 必要时取子列使 $x_n$ 两两不同. 于是 $S=\left\{x_n:n\ge1\right\}$ 无极限点, 故 $S$ 闭 (否则其极限点给出收敛子列). 因 $X$ 无孤立点, 每个 $x_n$ 的任意邻域都含异于 $x_n$ 的点; 归纳地选取 $y_n$, 使 $0<d\left(y_n,x_n\right)<1/n$, 且 $y_n\notin S\cup\left\{y_1,\dots,y_{n-1}\right\}$. 则 $\left\{y_n\right\}$ 也无收敛子列: 若 $y_{n_k}\to y$, 则由**定义 6.1** (度量空间) 的三角不等式,

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

中每个集合是 $\mathbb C$ 中开集 (不含 $\infty$ 的开集在 $\overline{\mathbb C}$ 与在 $\mathbb C$ 中同样开), 且它们覆盖 $K$. 由 $K$ 紧致, 即由**定义 5.2** (紧致空间), 有有限子族 $U_1,\dots,U_m$ 使 $K\subset\bigcup_{i=1}^{m}U_i$. 于是 $U_\infty,U_1,\dots,U_m$ 覆盖 $\overline{\mathbb C}$: $U_\infty$ 含 $\infty$ 与 $U_\infty\cap\mathbb C$, 其余集合覆盖 $K$. 故 $\overline{\mathbb C}$ 的任意开覆盖都有有限子覆盖, 由**定义 5.2** (紧致空间), $\overline{\mathbb C}$ 紧致. $\blacksquare$
