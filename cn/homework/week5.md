# 作业 5

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X-F$ 是开的. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. (教材 $\S3$)

> **定义 3.15** (拓扑基)<br>$\mathcal B\subset\mathcal P\left(X\right)$ 满足 $X=\bigcup\mathcal B$ 且 $B_1\cap B_2$ 含某 $B_3$, 则以 $\mathcal B$ 中元素之并为开集生成最粗拓扑. (教材 $\S3$)

> **定义 3.24** ($T_1$ 空间)<br>单点集皆闭; 豪斯多夫空间必为 $T_1$ 空间. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并. (教材 $\S4$)

> **定义 4.2** (既开又闭集)<br>既开又闭的集合称为既开又闭集; $X$ 连通当且仅当仅 $\emptyset,X$ 既开又闭. (教材 $\S4$)

> **定义 4.3** (完全不连通)<br>空间的唯一连通子集是单点集. (教材 $\S4$)

> **定义 4.9** (局部连通)<br>每点有由连通邻域组成的邻域基. (题集 $\S2.1$)

> **定义 4.11** (弗斯滕伯格拓扑)<br>$\mathbb Z$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$ $\left(a\neq0\right)$ 为基的拓扑; $S\left(a,b\right)$ 既开又闭. (题集 $\S2.2$)

> **定义 4.12** (戈洛姆拓扑)<br>$\mathbb Z_{>0}$ 上以 $\left\{an+b:n\in\mathbb N\right\}$ ($a,b$ 互素) 为基的拓扑. (题集 $\S2.2$)

> **定义 4.13** (基尔希拓扑)<br>$\mathbb Z_{>0}$ 上以 $\left\{pn+b:n\in\mathbb N\right\}$ ($p$ 为素数且 $p\nmid b$) 为基的拓扑. (题集 $\S2.2$)

> **定义 7.2** (正则空间)<br>闭集 $A$ 与不在 $A$ 中的点有不相交开邻域. (教材 $\S7$)

> **定理 4.16** (谢尔宾斯基同胚定理)<br>任意两个无孤立点的可数可度量化空间互相同胚. (题集 $\S2.2$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **定理 7.3** (乌雷松度量化定理)<br>有可数基的正则空间可度量化. (教材 $\S7$)

### 习题一

在 $\mathbb Z$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$ ($a\neq0$) 为基定义拓扑, 即**定义 4.11** (弗斯滕伯格拓扑).

(1) 证明 $U\subset\mathbb Z$ 开当且仅当对任意 $x\in U$, 存在某非零 $a\in\mathbb Z$ 使 $S\left(a,x\right)\subset U$;

(2) 验证这确实给出 $\mathbb Z$ 上的拓扑;

(3) 证明 $\mathbb Z$ 中非空有限集不能开; 特别地 $\mathbb Z-\left\{-1,1\right\}$ 不闭;

(4) 证明 $S\left(a,b\right)$ ($a\neq0$) 既开又闭;

(5) 证明对素数 $p$ 取并 $\bigcup_{p\in P}S\left(p,0\right)=\mathbb Z-\left\{-1,1\right\}$;

(6) 证明素数有无穷多个 (弗斯滕伯格的拓扑证明).

### 解答 习题一

(1) 由**定义 3.15** (拓扑基), 开集恰为若干 $S\left(a,b\right)$ 之并. 若 $U$ 开且 $x\in U$, 则 $x$ 含于某个并项 $S\left(a,b\right)\subset U$, 而 $x\in S\left(a,b\right)$ 等价于 $b\equiv x\pmod a$, 即 $S\left(a,b\right)=S\left(a,x\right)$. 故存在 $a\neq0$ 使 $S\left(a,x\right)\subset U$. 反过来, 若每点 $x\in U$ 都含某 $S\left(a,x\right)\subset U$, 则 $U=\bigcup_{x\in U}S\left(a_x,x\right)$ 是基元素之并, 故开.

(2) 先验证基条件. 这正是**定义 4.11** (弗斯滕伯格拓扑) 的基. 两个基元素之交

$$
S\left(a,b\right)\cap S\left(c,d\right)=\left\{x:x\equiv b\pmod a,\ x\equiv d\pmod c\right\}.
$$

它非空当且仅当 $b\equiv d\pmod{\gcd\left(a,c\right)}$; 此时交本身是一个以 $\operatorname{lcm}\left(a,c\right)$ 为步长的等差数列 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$. 故交含某基元素. 又 $S\left(1,0\right)=\mathbb Z$ 覆盖全空间. 由**定义 3.15** (拓扑基), 以此生成的开集族满足**定义 3.1** (拓扑空间) 的全部公理: 任意并由生成方式保证, 有限交由基条件 (2) 保证, $\emptyset$ 与 $\mathbb Z$ 分别为空并与 $S\left(1,0\right)$.

(3) 任一基元素 $S\left(a,x\right)=\left\{an+x:n\in\mathbb Z\right\}$ 是无限集. 非空开集由第 1 小题必含某无限集 $S\left(a,x\right)$, 故它本身无限. 因而非空有限集不能开. 特别地 $\left\{-1,1\right\}$ 非空有限, 故不开; 由**定义 3.2** (闭集), 其补集 $\mathbb Z-\left\{-1,1\right\}$ 不闭.

(4) $S\left(a,b\right)$ 是基元素, 故开. 其补集

$$
\mathbb Z-S\left(a,b\right)=\bigcup_{r=1}^{a-1}S\left(a,b+r\right)
$$

是其余 $a-1$ 个模 $a$ 剩余类之并, 每个都是基元素, 故补集开. 由**定义 3.2** (闭集), $S\left(a,b\right)$ 闭. 故 $S\left(a,b\right)$ 既开又闭 (**定义 4.2** (既开又闭集)).

(5) $S\left(p,0\right)=\left\{pn:n\in\mathbb Z\right\}$ 是 $p$ 的倍数全体. 整数 $n$ 被某素数整除当且仅当 $\left|n\right|\ge2$; $0$ 被一切素数整除; $\pm1$ 不被任何素数整除. 故

$$
\bigcup_{p\in P}S\left(p,0\right)=\mathbb Z-\left\{-1,1\right\}.
$$

(6) 反设素数只有有限个 $p_1,\dots,p_k$. 由第 5 小题,

$$
\bigcup_{i=1}^{k}S\left(p_i,0\right)=\mathbb Z-\left\{-1,1\right\}.
$$

由第 4 小题每个 $S\left(p_i,0\right)$ 既开又闭, 有限个既开又闭集之并仍既开又闭 (**定义 4.2** (既开又闭集)). 故 $\mathbb Z-\left\{-1,1\right\}$ 既开又闭, 其补集 $\left\{-1,1\right\}$ 也既开又闭. 但由第 3 小题 $\left\{-1,1\right\}$ 非空有限, 不能开, 矛盾. 故素数有无穷多个. $\blacksquare$

### 习题二

在 $\mathbb Z_{>0}$ 上分别用 (非平凡) 等差数列 $a\mathbb N+b=\left\{an+b:n\in\mathbb N\right\}$ ($a,b$ 互素) 与 $p\mathbb N+b=\left\{pn+b:n\in\mathbb N\right\}$ ($p$ 为素数且 $p\nmid b$) 为基 (前者) 与子基 (后者) 定义两个拓扑.

(1) (戈洛姆) 证明基可限制到满足 $0\le b<a$ 且 $a,b$ 互素的偶对;

(2) (戈洛姆) 验证这确实给出 $\mathbb Z_{>0}$ 上的拓扑;

(3) (基尔希) 证明基可限制到满足 $0\le b<p$ 且 $p\nmid b$ 的偶对;

(4) (基尔希) 验证这确实给出 $\mathbb Z_{>0}$ 上的拓扑.

### 解答 习题二

(1) 对基元素 $S\left(a,b\right)=\left\{an+b:n\in\mathbb N\right\}$, $\gcd\left(a,b\right)=1$. 作带余除法 $b=qa+r$, $0\le r<a$. 则 $\gcd\left(a,r\right)=\gcd\left(a,b\right)=1$, 且 $S\left(a,b\right)=\left\{a\left(n+q\right)+r:n\in\mathbb N\right\}\subset S\left(a,r\right)$. 反之, 对 $x=an_0+b\in S\left(a,b\right)$, $\gcd\left(a,x\right)=\gcd\left(a,an_0+b\right)=\gcd\left(a,b\right)=1$, 于是

$$
S\left(a,x\right)=\left\{an+x:n\in\mathbb N\right\}\subset\left\{b+am:m\ge n_0\right\}\subset S\left(a,b\right).
$$

故每点 $x$ 的邻域都可由满足 $0\le r<a$ 的基元素生成, 基可限制到 $0\le b<a$ 且互素的偶对.

(2) 验证基条件. $S\left(a,b\right)\cap S\left(c,d\right)$ 非空当且仅当 $\gcd\left(a,c\right)\mid\left(b-d\right)$; 此时交为 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$, 且 $\gcd\left(\operatorname{lcm}\left(a,c\right),x_0\right)=1$. 它仍是**定义 4.12** (戈洛姆拓扑) 的基元素. 又 $S\left(1,1\right)=\mathbb Z_{>0}$ 覆盖全空间. 由**定义 3.15** (拓扑基) 与**定义 3.1** (拓扑空间), 这给出 $\mathbb Z_{>0}$ 上的拓扑.

(3) 对基尔希的 $S\left(p,b\right)=\left\{pn+b:n\in\mathbb N\right\}$, $p$ 素数, $p\nmid b$. 作带余除法 $b=qp+r$, $0\le r<p$, 则 $p\nmid r$ (否则 $p\mid b$), 且 $S\left(p,b\right)\subset S\left(p,r\right)$. 同第 1 小题, 对 $x=pn_0+b\in S\left(p,b\right)$ 有 $p\nmid x$, 故 $S\left(p,x\right)\subset S\left(p,b\right)$. 基可限制到 $0\le b<p$ 且 $p\nmid b$ 的偶对.

(4) 以 $\left\{S\left(p,b\right)\right\}$ 为子基, 其有限交

$$
S\left(p_1,b_1\right)\cap\cdots\cap S\left(p_k,b_k\right)
$$

由中国剩余定理为 $\left\{x\equiv b_i\pmod{p_i}\right\}=S\left(M,x_0\right)$, 其中 $M=p_1\cdots p_k$, $p_i\nmid x_0$. 两个这样的有限交之交仍是同形的有限交. 故有限交全体构成一个基, 由**定义 3.15** (拓扑基) 与**定义 3.1** (拓扑空间) 生成 $\mathbb Z_{>0}$ 上的**定义 4.13** (基尔希拓扑). $\blacksquare$

### 习题三

考察上述拓扑的拓扑性质.

(1) 证明弗斯滕伯格拓扑是豪斯多夫的且正则; 它可度量化但不可完备度量化, 实际上它与带通常子空间拓扑的有理数集 $\mathbb Q$ 同胚;

(2) 证明戈洛姆拓扑与基尔希拓扑是豪斯多夫的但不正则;

(3) 证明弗斯滕伯格拓扑完全不连通, 戈洛姆拓扑连通但不局部连通, 基尔希拓扑既连通又局部连通.

### 解答 习题三

(1) **豪斯多夫**: 取 $x\neq y$. 选非零 $a$ 使 $a>\left|x-y\right|$. 若 $S\left(a,x\right)\cap S\left(a,y\right)\neq\emptyset$, 则 $x+an=y+am$, 即 $a\left(n-m\right)=y-x$, 与 $a>\left|x-y\right|$ 矛盾. 故 $S\left(a,x\right)$ 与 $S\left(a,y\right)$ 不相交. 由**定义 3.10** (豪斯多夫空间), 弗斯滕伯格拓扑是豪斯多夫的. 由**定义 3.24** ($T_1$ 空间), 单点集皆闭.

   **正则**: 设 $A$ 闭, $x\notin A$. 则 $\mathbb Z-A$ 是开集且含 $x$, 由习题一第 1 小题存在 $a\neq0$ 使 $S\left(a,x\right)\subset\mathbb Z-A$, 即 $S\left(a,x\right)\cap A=\emptyset$. 由习题一第 4 小题 $S\left(a,x\right)$ 既开又闭 (**定义 4.2** (既开又闭集)), 且 $A\subset\mathbb Z-S\left(a,x\right)$, 后者开. 故 $x$ 与 $A$ 有不相交开邻域, 由**定义 7.2** (正则空间) 弗斯滕伯格拓扑正则.

   **可度量化与同胚于 $\mathbb Q$**: $\mathbb Z$ 可数, 故该拓扑有可数基; 由**定理 7.3** (乌雷松度量化定理), 有可数基的正则空间可度量化. 又该拓扑无孤立点: 每点 $x$ 的邻域 $S\left(a,x\right)$ 无限. 由**定理 4.16** (谢尔宾斯基同胚定理), 任意两个无孤立点的可数可度量化空间互相同胚, 故它与带通常子空间拓扑的 $\mathbb Q$ 同胚.

   **不可完备度量化**: 若它可完备度量化, 则同胚于它的 $\mathbb Q$ 也可完备度量化. 但 $\mathbb Q=\bigcup_{q\in\mathbb Q}\left\{q\right\}$ 是可数个无处稠密单点集之并, 与**定理 6.13** (贝尔纲定理) 矛盾. 故它不可完备度量化.

(2) **豪斯多夫**: 取 $x\neq y\in\mathbb Z_{>0}$. 选素数 $p$ 使 $p>\left|x-y\right|$ 且 $p\nmid x$, $p\nmid y$ (这样的素数存在, 因素数无穷). 则 $S\left(p,x\right)$ 与 $S\left(p,y\right)$ 分别是**定义 4.12** (戈洛姆拓扑) 与**定义 4.13** (基尔希拓扑) 的基元素; 若相交则 $p\mid\left(x-y\right)$, 与 $p>\left|x-y\right|$ 矛盾. 由**定义 3.10** (豪斯多夫空间), 两拓扑均豪斯多夫.

   **不正则**: 以戈洛姆拓扑为例. 取闭集 $E$ 为全体偶正整数 (奇数集开: 对奇 $x$, $S\left(2,x\right)=\left\{x+2n\right\}$ 全奇且 $\gcd\left(2,x\right)=1$), 再取点 $1$. 点 $1$ 的任一邻域形如 $S\left(a,1\right)=\left\{1+an:n\in\mathbb N\right\}$, 而含偶数 $2$ 的任一开集必含某 $S\left(b,2\right)=\left\{2+bn:n\in\mathbb N\right\}$ ($\gcd\left(b,2\right)=1$, 即 $b$ 奇). 由同余式相容, $S\left(a,1\right)\cap S\left(b,2\right)$ 非空, 故无法用不相交开集分离 $1$ 与闭集 $E$. 由**定义 7.2** (正则空间), 戈洛姆拓扑不正则. 基尔希拓扑同理不正则.

(3) **弗斯滕伯格完全不连通**: 取 $x\neq y$. 选 $a$ 使 $y\notin S\left(a,x\right)$. 由习题一第 4 小题 $S\left(a,x\right)$ 既开又闭且含 $x$ 不含 $y$, 故任何同时含 $x,y$ 的子集都被这个非平凡既开又闭集切断, 不能连通. 由**定义 4.3** (完全不连通), 弗斯滕伯格拓扑完全不连通.

   **戈洛姆连通**: 设 $C$ 既开又闭且 $1\in C$. 由标准归纳 (取 $\mathbb Z_{>0}-C$ 中最小元 $n$, 用 $\gcd$ 条件可推出 $n\in C$), 得 $C=\mathbb Z_{>0}$. 故 $\mathbb Z_{>0}$ 仅有的既开又闭非空集是全空间, 由**定义 4.1** (连通空间) 戈洛姆拓扑连通. 它不**定义 4.9** (局部连通): 点 $1$ 的任一邻域 $S\left(a,1\right)$ 都含非平凡既开又闭子集, 故没有连通邻域基.

   **基尔希连通且局部连通**: 基尔希的基元素 $S\left(p,b\right)$ 本身在该拓扑下连通 (同理由既开又闭集归纳), 故每点有连通邻域, 由**定义 4.9** (局部连通) 它局部连通; 又全空间仅有的既开又闭非空集是全空间, 由**定义 4.1** (连通空间) 它连通. $\blacksquare$
