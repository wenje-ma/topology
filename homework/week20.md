# 作业 20

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定理 3.5** (闭包与极限点)<br>$\overline A=A\cup A'$, 即闭包等于 $A$ 与其全体极限点之并. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 4.5** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $f:\left[a,b\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸当且仅当 $x,y\in K$ 蕴含连线含于 $K$; 凸集必路径连通. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.3** (路径连通蕴含连通)<br>路径连通空间必连通. (教材 $\S4$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价. (教材 $\S6$)

> **推论 6.3** (紧度量空间完备)<br>紧度量空间必完备. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛. (教材 $\S6$)

> **定义 6.19** (压缩映射)<br>存在 $0<k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. (题集 $\S4.3$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空完备度量空间上压缩映射有唯一不动点. (题集 $\S4.3$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理的 $\left\|\cdot\right\|$. (题集 $\S4.3$)

> **定义 6.22** (绝对收敛级数)<br>$\sum\left\|u_n\right\|$ 收敛; 赋范空间完备当且仅当一切绝对收敛级数都收敛. (题集 $\S4.4$)

> **推论 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

### 习题一

考虑一个可微的函数 $f:\mathbb R\to\mathbb R$, 但不假设 $f'$ 是连续的. 取 $\mathbb R$ 上一个非平凡开区间 $I$.

(1) (10 分) 考虑集合 $A=\left\{\left(x,y\right)\in I^2:x<y\right\}$. 证明 $A$ 在最自然的拓扑下是一个连通集合.

(2) (10 分) 考虑在 $A$ 上定义的实函数 $F\left(x,y\right)=\dfrac{f\left(x\right)-f\left(y\right)}{x-y}$. 证明 $\Gamma=F\left(A\right)$ 是 $\mathbb R$ 中的一个连通集.

(3) (5 分) 证明 $\Gamma\subset f'\left(I\right)\subset\overline{\Gamma}$ (这里 $f'\left(I\right)$ 指的是 $I$ 被 $f'$ 这个函数映射到的像集).

(4) (5 分) 证明 $f'\left(I\right)$ 是 $\mathbb R$ 中的一个区间.

### 解答 习题一

(1) 任取两点 $P_1=\left(x_1,y_1\right),P_2=\left(x_2,y_2\right)\in A$, 则 $x_1<y_1$ 且 $x_2<y_2$. 对 $t\in\left[0,1\right]$, 线段上的点为 $x\left(t\right)=\left(1-t\right)x_1+tx_2$, $y\left(t\right)=\left(1-t\right)y_1+ty_2$. 于是

$$
y\left(t\right)-x\left(t\right)=\left(1-t\right)\left(y_1-x_1\right)+t\left(y_2-x_2\right)>0,
$$

故整条线段含于 $A$. 由**定义 4.6** (凸集), $A$ 是凸集, 凸集必路径连通 (由**定义 4.5** (路径连通)), 再由**定理 4.3** (路径连通蕴含连通) $A$ 连通.

(2) 因 $f$ 可微, $f$ 连续; 在 $A$ 上恒有 $x-y\neq0$, 故 $F\left(x,y\right)=\dfrac{f\left(x\right)-f\left(y\right)}{x-y}$ 是 $A$ 上的连续函数. 由第 1 小题 $A$ 连通, 由**定理 4.2** (连续像连通), $\Gamma=F\left(A\right)$ 连通.

(3) 先证 $\Gamma\subset f'\left(I\right)$. 任取 $\left(x,y\right)\in A$, $x<y$. 因 $f$ 在 $\left[x,y\right]$ 上连续且在 $\left(x,y\right)$ 上可微, 由微分中值定理, 存在 $c\in\left(x,y\right)\subset I$ 使 $\dfrac{f\left(x\right)-f\left(y\right)}{x-y}=f'\left(c\right)$. 故 $F\left(x,y\right)\in f'\left(I\right)$, 即 $\Gamma\subset f'\left(I\right)$.

再证 $f'\left(I\right)\subset\overline{\Gamma}$. 任取 $t\in I$ (因 $I$ 为开区间, $t$ 非端点). 取充分小的 $h$ 使 $t+h\in I$, 则 $q_h=\dfrac{f\left(t+h\right)-f\left(t\right)}{h}\in\Gamma$. 由导数定义 $q_h\to f'\left(t\right)$ ($h\to0$). 故 $f'\left(t\right)$ 是 $\Gamma$ 的极限点, 由**定理 3.5** (闭包与极限点) 它含于 $\overline{\Gamma}$ (由**定义 3.6** (闭包), $\overline{\Gamma}$ 是含 $\Gamma$ 的最小闭集). 即 $f'\left(I\right)\subset\overline{\Gamma}$.

(4) 由第 2 小题, $\Gamma$ 是 $\mathbb R$ 中的连通集, 而 $\mathbb R$ 中连通集必为区间 (若 $a<c<b$ 且 $a,b\in S$, $c\notin S$, 则 $S=\left(S\cap\left(-\infty,c\right)\right)\cup\left(S\cap\left(c,\infty\right)\right)$ 是一个分离, 矛盾). 故 $\Gamma$ 是区间. 由第 3 小题, $\Gamma\subset f'\left(I\right)\subset\overline{\Gamma}$. 一个区间与其闭包之间的差别至多是它的两个端点; 在区间上任意添去两端点的一个子集仍得区间. 因此夹在区间 $\Gamma$ 与 $\overline{\Gamma}$ 之间的 $f'\left(I\right)$ 仍是区间. $\blacksquare$

### 习题二

考虑一个赋范线性空间 $E$. 称 $E$ 中的级数 $\sum_{n\ge0}u_n$ 绝对收敛, 如果级数 $\sum_{n\ge0}\left\|u_n\right\|$ 收敛.

(1) (10 分) 证明如果 $E$ 是完备的, 那么所有绝对收敛的级数 $\sum_{n\ge0}u_n$ 都是收敛的.

(2) (10 分) 现在不假设 $E$ 是完备的, 但假设 $E$ 中所有的绝对收敛级数都是收敛的. 假设 $S_n$ 是 $E$ 中的一个柯西列. 证明可以用归纳法找出 $\varphi\left(1\right)<\varphi\left(2\right)<\cdots$ 使得对一切 $n\ge\varphi\left(k\right)$, $\left\|S_n-S_{\varphi\left(k\right)}\right\|<2^{-k}$.

(3) (10 分) 通过定义 $u_k=S_{\varphi\left(k+1\right)}-S_{\varphi\left(k\right)}$, 证明在第 2 小题的条件下 $E$ 是完备的.

### 解答 习题二

设 $E$ 由**定义 6.20** (赋范线性空间) 装备范数 $\left\|\cdot\right\|$.

(1) 设 $\sum_{n\ge0}u_n$ 绝对收敛, 即由**定义 6.22** (绝对收敛级数) $\sum\left\|u_n\right\|$ 收敛. 记部分和 $s_n=\sum_{j=0}^n u_j$. 对 $m>n$, 由范数的三角不等式,

$$
\left\|s_m-s_n\right\|=\left\|\sum_{j=n+1}^m u_j\right\|\le\sum_{j=n+1}^m\left\|u_j\right\|.
$$

因 $\sum\left\|u_j\right\|$ 收敛, 其尾部 $\sum_{j>n}\left\|u_j\right\|$ 趋于 $0$, 故由**定义 6.3** (柯西列) $s_n$ 是柯西列. 由**定义 6.4** (完备度量空间) $E$ 完备, $s_n$ 收敛, 即原级数收敛.

(2) 因 $\left(S_n\right)$ 是柯西列, 由**定义 6.3** (柯西列), 对每个 $k\ge1$, 存在 $N_k$ 使当 $n,m\ge N_k$ 时 $\left\|S_n-S_m\right\|<2^{-k}$. 归纳选取: 取 $\varphi\left(1\right)\ge N_1$; 选定 $\varphi\left(k\right)$ 后, 取 $\varphi\left(k+1\right)>\max\left(\varphi\left(k\right),N_{k+1}\right)$. 于是 $\varphi\left(1\right)<\varphi\left(2\right)<\cdots$. 对任意 $n\ge\varphi\left(k\right)\ge N_k$, 由 $n,\varphi\left(k\right)\ge N_k$ 得 $\left\|S_n-S_{\varphi\left(k\right)}\right\|<2^{-k}$.

(3) 令 $u_k=S_{\varphi\left(k+1\right)}-S_{\varphi\left(k\right)}$. 因 $\varphi\left(k+1\right)\ge\varphi\left(k\right)$, 由第 2 小题 (取 $n=\varphi\left(k+1\right)$) 得 $\left\|u_k\right\|<2^{-k}$. 故 $\sum_{k\ge1}\left\|u_k\right\|\le\sum_{k\ge1}2^{-k}<\infty$, 由**定义 6.22** (绝对收敛级数) 级数 $\sum u_k$ 绝对收敛. 由题设 (一切绝对收敛级数收敛), $\sum_{k\ge1}u_k$ 收敛于某 $s\in E$. 而

$$
S_{\varphi\left(k\right)}=S_{\varphi\left(1\right)}+\sum_{j=1}^{k-1}u_j\longrightarrow S_{\varphi\left(1\right)}+s.
$$

故子列 $\left(S_{\varphi\left(k\right)}\right)$ 收敛. 柯西列若有收敛子列则整体收敛 (设子列收敛于 $L$, 由柯西性, 全列与子列距离趋于 $0$, 故全列收敛于 $L$). 由**定义 6.4** (完备度量空间), $E$ 中任意柯西列都收敛, $E$ 完备. $\blacksquare$

### 习题三

考虑一个赋范线性空间 $E$ 及其中的一个紧致子集 $K\subset E$. 假设 $K$ 还是凸的. 假设 $f:K\to K$ 是一个连续映射并且对于任意 $x,y\in K$, $\left\|f\left(x\right)-f\left(y\right)\right\|\le\left\|x-y\right\|$.

(1) (10 分) 证明如果条件改为对于任意 $x,y\in K$ 且 $x\neq y$ 时 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$, 那么 $f$ 一定至少有一个不动点. (不需要证明, 只需要说出相关定理或构造即可.)

(2) (10 分) 取定 $a\in K$. 证明对于任意 $n\ge1$, 函数 $f_n\left(x\right)=\dfrac{1}{n}a+\left(1-\dfrac{1}{n}\right)f\left(x\right)$ 是一个从 $K$ 到 $K$ 的映射. 证明对于任意 $n\ge1$, $f_n$ 至少有一个不动点 $x_n\in K$.

(3) (5 分) 运用数列 $\left\{x_n\right\}$ 及 $K$ 的紧性证明满足最初题设条件的 $f$ 也有一个不动点.

### 解答 习题三

(1) 在严格条件 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ ($x\neq y$) 下, 由 $K$ 紧可推出 $f$ 实际上是**定义 6.19** (压缩映射) 意义下的压缩映射 (存在统一的 $0<k<1$). 再由**定理 6.16** (巴拿赫不动点定理), $f$ 有唯一不动点.

(2) 由**定义 4.6** (凸集), $a\in K$ 且 $f\left(x\right)\in K$, 故凸组合 $f_n\left(x\right)=\dfrac{1}{n}a+\left(1-\dfrac{1}{n}\right)f\left(x\right)\in K$, 即 $f_n:K\to K$. 对 $x,y\in K$,

$$
\left\|f_n\left(x\right)-f_n\left(y\right)\right\|=\left(1-\dfrac{1}{n}\right)\left\|f\left(x\right)-f\left(y\right)\right\|\le\left(1-\dfrac{1}{n}\right)\left\|x-y\right\|,
$$

其中压缩系数 $k=1-\dfrac{1}{n}<1$, 故 $f_n$ 是**定义 6.19** (压缩映射). 又 $K$ 紧, 由**推论 6.3** (紧度量空间完备) $K$ 完备. 由**定理 6.16** (巴拿赫不动点定理), $f_n$ 有唯一不动点 $x_n\in K$, 即 $x_n=f_n\left(x_n\right)$.

(3) 因 $K$ 紧, 由**定理 6.1** (紧=序列紧), 序列 $\left(x_n\right)\subset K$ 有收敛子列 $x_{n_j}\to x\in K$. 由 $x_n=f_n\left(x_n\right)=\dfrac{1}{n}a+\left(1-\dfrac{1}{n}\right)f\left(x_n\right)$ 整理得

$$
f\left(x_n\right)=\dfrac{n\,x_n-a}{n-1}.
$$

沿子列 $n_j\to\infty$, $x_{n_j}\to x$, 故 $\dfrac{n_j x_{n_j}-a}{n_j-1}\to x$, 即 $f\left(x_{n_j}\right)\to x$. 另一方面 $f$ 连续, 故 $f\left(x_{n_j}\right)\to f\left(x\right)$. 由**定义 3.10** (豪斯多夫空间) 极限唯一, 得 $f\left(x\right)=x$. 即 $f$ 有不动点. $\blacksquare$

### 习题四

设 $f:\mathbb R_{\ge0}\to\mathbb R$ 是一个连续函数, 并且对于任意的 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 都收敛到 $0$.

(1) (5 分) 取定 $\epsilon>0$ 并考虑集合 $F_n=\left\{x\ge0:\forall p\in\mathbb N,\ p\ge n,\ \left|f\left(px\right)\right|\le\epsilon\right\}$. 证明对于任意的 $n\ge0$, $F_n$ 都是闭集合.

(2) (5 分) 证明所有 $F_n$ 的并包含 $\left(0,\infty\right)$.

(3) (5 分) 利用贝尔纲定理证明 $\lim_{x\to\infty}f\left(x\right)=0$.

### 解答 习题四

(1) 写 $F_n=\bigcap_{p\ge n}\left\{x\ge0:\left|f\left(px\right)\right|\le\epsilon\right\}$. 对固定 $p$, 映射 $x\mapsto px$ 连续, $f$ 连续, 由**定义 3.3** (连续映射) 复合 $x\mapsto f\left(px\right)$ 连续; 而 $\left[-\epsilon,\epsilon\right]\subset\mathbb R$ 是闭集, 故其原像 $\left\{x:\left|f\left(px\right)\right|\le\epsilon\right\}$ 由**定义 3.2** (闭集) 是闭集. 闭集的任意交仍闭: 补集为开集的任意并, 由**定义 3.1** (拓扑空间) 的拓扑公理仍是开集, 再由**定义 3.2** (闭集) 得交为闭集, 故 $F_n$ 闭.

(2) 任取 $x>0$, 由题设 $f\left(nx\right)\to0$, 故存在 $n$ 使对一切 $p\ge n$ 都有 $\left|f\left(px\right)\right|\le\epsilon$, 即 $x\in F_n$. 故 $x\in\bigcup_{n\ge1}F_n$, 即 $\left(0,\infty\right)\subset\bigcup_n F_n$. 又显然 $F_n\subset F_{n+1}$ (条件 $p\ge n+1$ 弱于 $p\ge n$), 闭集族递增.

(3) 取紧区间 $\left[1,2\right]\subset\left(0,\infty\right)$. 由第 2 小题, $\left[1,2\right]=\bigcup_{n\ge1}\left(F_n\cap\left[1,2\right]\right)$. 每个 $F_n\cap\left[1,2\right]$ 在 $\left[1,2\right]$ 中闭 (闭集与闭区间之交闭), 且递增. 因 $\left[1,2\right]$ 紧, 由**推论 6.3** (紧度量空间完备) 它完备. 由**推论 6.14** (递增闭集族), 存在 $N$ 使 $F_N\cap\left[1,2\right]$ 在 $\left[1,2\right]$ 中有非空内部, 即存在 $a<b$ 使 $\left(a,b\right)\subset F_N$. 于是对一切 $p\ge N$ 与 $x\in\left(a,b\right)$, $\left|f\left(px\right)\right|\le\epsilon$.

对充分大的 $t>0$, 区间族 $\left(pa,pb\right)$ ($p\ge N$) 相互重叠 (当 $p\left(b-a\right)\ge a$ 时, $pb\ge\left(p+1\right)a$), 故 $\bigcup_{p\ge N}\left(pa,pb\right)$ 包含某个 $\left[T,\infty\right)$. 任取 $t\ge T$, 则 $t\in\left(pa,pb\right)$ 对某 $p\ge N$ 成立, 即 $t=px$, $x\in\left(a,b\right)\subset F_N$, 从而 $\left|f\left(t\right)\right|=\left|f\left(px\right)\right|\le\epsilon$. 由 $\epsilon>0$ 任意, $\lim_{t\to\infty}f\left(t\right)=0$. $\blacksquare$
