# 作业 19

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并. (教材 $\S4$)

> **定义 4.4** (局部常值函数)<br>$f$ 局部常值: 每点有邻域使 $f$ 在其上取常值; 连通空间上局部常值函数必常值. (教材 $\S4$)

> **定义 4.17** (不动点)<br>$f:X\to X$ 的不动点是满足 $f\left(x\right)=x$ 的点 $x\in X$. (题集 $\S7.2$)

> **定义 5.2** (紧致空间)<br>$X$ 紧当且仅当每个开覆盖有有限子覆盖. (教材 $\S5$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛. (教材 $\S6$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.22** (绝对收敛级数)<br>$\sum\left\|u_n\right\|$ 收敛; 赋范空间完备当且仅当一切绝对收敛级数都收敛. (题集 $\S4.4$)

> **定理 4.1** (区间连通)<br>$\left[0,1\right]$ 连通. (教材 $\S4$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **推论 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup_n F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定理 6.18** (蒂茨-乌雷松扩张定理)<br>度量空间闭子集 $A$ 上的连续有界函数可保持上确界与下确界地扩张到全空间. (题集 $\S7.1$)

### 习题一

(7.1 紧性)

(1) 设 $\left(E,d\right)$ 是度量空间, $f:E\to\mathbb R$ 连续, $K\subset E$ 紧. 假设 $f$ 在 $K$ 上单射, 且对每个 $x\in K$ 存在 $\varepsilon>0$ 使 $f$ 在 $B\left(x,\varepsilon\right)$ 上单射. 证明存在含 $K$ 的开集 $\Omega$ 使 $f$ 在 $\Omega$ 上单射.

(2) (里茨定理) 设 $E$ 是实无穷维赋范线性空间. 证明 $E$ 的闭单位球不能被有限个半径 $1$ 的开球覆盖.

(3) (蒂茨-乌雷松扩张定理) 设 $\left(E,d\right)$ 是度量空间, $A\subset E$ 闭, $f:A\to\mathbb R$ 连续有界. 证明存在连续 $g:E\to\mathbb R$, $g\big|_A=f$, 且

$$
\sup_{x\in E}g\left(x\right)=\sup_{x\in A}f\left(x\right),\qquad
\inf_{x\in E}g\left(x\right)=\inf_{x\in A}f\left(x\right).
$$

### 解答 习题一

**第 1 小题**: 对 $n\ge 1$, 定义 $K_n=\left\{x\in E:d\left(x,K\right)<1/n\right\}$. 每个 $K_n$ 是开集且含 $K$. 反证: 若对每个 $n$, $f$ 在 $K_n$ 上不单射, 则存在 $x_n,y_n\in K_n$, $x_n\neq y_n$, 使 $f\left(x_n\right)=f\left(y_n\right)$. 由 $x_n,y_n\in K_n$, 可取 $x'_n,y'_n\in K$ 使 $d\left(x_n,x'_n\right)<1/n$, $d\left(y_n,y'_n\right)<1/n$. 由**定义 5.2** (紧致空间), $K\times K$ 紧; 由**定理 6.1** (紧=序列紧), 存在子列 $\left(x'_{\varphi\left(n\right)},y'_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in K\times K$. 由三角不等式, $x_{\varphi\left(n\right)}\to x$, $y_{\varphi\left(n\right)}\to y$. 由 $f$ 连续, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$ 取极限得 $f\left(x\right)=f\left(y\right)$. 因 $f$ 在 $K$ 上单射, $x=y$. 但由假设, $x$ 有邻域 $B\left(x,\varepsilon\right)$ 使 $f$ 单射, 而 $x_{\varphi\left(n\right)}\neq y_{\varphi\left(n\right)}$ 且当 $n$ 充分大时二者都在 $B\left(x,\varepsilon\right)$ 内, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$, 矛盾. 故存在 $n$ 使 $f$ 在 $K_n$ 上单射, 取 $\Omega=K_n$ 即可.

**第 2 小题**: 反证. 设闭单位球 $\overline B\left(0,1\right)$ 被开单位球 $B\left(x_i,1\right)$ ($i=1,\dots,m$) 覆盖. 令 $F=\operatorname{span}\left(x_1,\dots,x_m\right)$, 它是有限维子空间. 因 $E$ 无穷维, 存在 $y\in E\setminus F$. 由有限维子空间闭, 取 $x\in F$ 使 $\left\|y-x\right\|=d\left(y,F\right)$ (有限维中距离可达). 令

$$
x_0=\frac{y-x}{\left\|y-x\right\|}.
$$

则 $\left\|x_0\right\|=1$. 对任意 $z\in F$,

$$
\left\|x_0-z\right\|=\frac{\left\|y-\left(x+\left\|y-x\right\|z\right)\right\|}{\left\|y-x\right\|}\ge\frac{d\left(y,F\right)}{\left\|y-x\right\|}=1.
$$

故 $d\left(x_0,F\right)\ge 1$. 但每个 $x_i\in F$, 故 $\left\|x_0-x_i\right\|\ge 1$, 即 $x_0\notin B\left(x_i,1\right)$ 对一切 $i$ 成立. 而 $x_0\in\overline B\left(0,1\right)$, 与覆盖矛盾. 这就是**定理 6.17** (里茨定理).

**第 3 小题**: 由**定义 6.15** (点到集合的距离), 对 $x\notin A$ 定义

$$
g\left(x\right)=\frac{1}{d\left(x,A\right)}\inf_{y\in A}\left(f\left(y\right)d\left(x,y\right)\right),
$$

对 $x\in A$ 令 $g\left(x\right)=f\left(x\right)$. 由平移缩放 (不妨设 $\inf_A f=1$, $\sup_A f=2$), 可验证 $g$ 连续: $x\in\operatorname{int}A$ 时 $g=f$ 连续; $x\notin A$ 时由三角不等式 $d\left(x,A\right)$ 连续且正, $g$ 连续; $x\in\partial A$ 时由 $f$ 在 $A$ 上连续, 对 $\varepsilon>0$ 取 $r>0$ 使 $y\in B\left(x,r\right)\cap A$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\varepsilon$, 再对 $z\notin A$ 且 $\left\|z-x\right\|<r/4$ 用三角不等式估计得 $\left|g\left(z\right)-f\left(x\right)\right|<\varepsilon$. 由**定义 3.3** (连续映射), $g$ 在全 $E$ 上连续. 由构造 $\inf_E g=\inf_A f$, $\sup_E g=\sup_A f$. 这就是**定理 6.18** (蒂茨-乌雷松扩张定理). $\blacksquare$

### 习题二

(7.2 连通性)

(1) 设 $\left(E,d\right)$ 是度量空间, 且每个连续映射 $f:E\to E$ 都有**定义 4.17** (不动点). 证明 $E$ 连通.

(2) 设 $K\subset\left[0,1\right]^2$ 闭, 且对每个 $x\in\left[0,1\right]$, 截面 $K_x=\left\{y\in\left[0,1\right]:\left(x,y\right)\in K\right\}$ 是非平凡区间. 证明 $K$ 连通. 进一步证明存在 $x\in\left[0,1\right]$ 使 $x\in K_x$.

(3) 设 $f:\left[0,1\right]\to\left[0,1\right]$. (a) 设 $f$ 非递减 (不必连续). 证明 $f$ 有不动点. (b) 设 $f$ 连续 (不必递增). 证明 $f$ 有不动点. (c) 设 $f,g:\left[0,1\right]\to\left[0,1\right]$ 连续且 $f\circ g=g\circ f$. 证明存在 $a\in\left[0,1\right]$ 使 $f\left(a\right)=g\left(a\right)$. (d) 设 $f:\mathbb R\to\mathbb R$ 连续, 且 $f\circ f$ 有不动点. 证明 $f$ 有不动点.

### 解答 习题二

**第 1 小题**: 反证. 若 $E$ 不连通, 由**定义 4.1** (连通空间), $E=U\sqcup V$, 其中 $U,V$ 是非空不相交开集. 取 $u\in U$, $v\in V$. 定义 $f:E\to E$ 为 $f\left(U\right)=\left\{v\right\}$, $f\left(V\right)=\left\{u\right\}$. 由**定义 3.3** (连续映射), $f$ 连续 (常值映射在开集上连续, 拼接不相交开集). 但 $f$ 无不动点: 对 $x\in U$, $f\left(x\right)=v\notin U$; 对 $x\in V$, $f\left(x\right)=u\notin V$. 矛盾. 故 $E$ 连通.

**第 2 小题**: 证明任一连续 $h:K\to\left\{0,1\right\}$ 常值. 对固定 $x$, $K_x$ 是区间故连通 (由**定理 4.1** (区间连通) 与**定义 4.1** (连通空间)), $h|_{K_x}$ 连续像连通, 故常值, 记为 $g\left(x\right)$. 下证 $g$ 局部常值. 若不然, 存在 $x_n\to x$ 但 $g\left(x_n\right)\neq g\left(x\right)$. 取 $y_n\in K_{x_n}$. 由 $K$ 紧 ($\left[0,1\right]^2$ 的闭子集), 存在子列 $\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in K$. 由 $h$ 连续,

$$
g\left(x\right)=h\left(x,y\right)=\lim_n h\left(x_{\varphi\left(n\right)},y_{\varphi\left(n\right)}\right)=\lim_n g\left(x_{\varphi\left(n\right)}\right),
$$

而 $\left\{0,1\right\}$ 离散, 故 $g\left(x_{\varphi\left(n\right)}\right)$ 最终等于 $g\left(x\right)$, 矛盾. 故 $g$ 局部常值. 由**定义 4.4** (局部常值函数) 与 $\left[0,1\right]$ 连通 (**定理 4.1** (区间连通)), $g$ 常值, 从而 $h$ 常值. 由**定义 4.1** (连通空间) $K$ 连通.

进一步证明存在 $x$ 使 $x\in K_x$. 定义 $F=\left\{x\in\left[0,1\right]:\inf K_x\ge x\right\}$ 与 $G=\left\{x\in\left[0,1\right]:\sup K_x\le x\right\}$. 二者闭. 若 $F\cap G=\emptyset$, 则 $\left[0,1\right]=F\sqcup\left(\left[0,1\right]\setminus F\right)$, 但 $0\in F$ (因 $\inf K_0\ge 0$) 且 $1\in G$ (因 $\sup K_1\le 1$), 由连通性必有某点 $x\in F\cap G$, 即 $\inf K_x\ge x$ 且 $\sup K_x\le x$, 故 $x\in K_x$.

**第 3 小题 (a)**: 令 $A=\left\{x\in\left[0,1\right]:x\le f\left(x\right)\right\}$. $0\in A$. 令 $a=\sup A$. 对 $x\in A$, $x\le f\left(x\right)\le f\left(a\right)$ (由 $f$ 非递减且 $x\le a$), 故 $a\le f\left(a\right)$. 于是 $f\left(a\right)\le f\left(f\left(a\right)\right)$, 即 $f\left(a\right)\in A$, 故 $f\left(a\right)\le a$. 因而 $f\left(a\right)=a$. 由**定义 4.17** (不动点), $a$ 是不动点.

**(b)**: 令 $h\left(x\right)=f\left(x\right)-x$. $h\left(0\right)=f\left(0\right)\ge 0$, $h\left(1\right)=f\left(1\right)-1\le 0$. 由**定理 4.1** (区间连通) 与介值定理, 存在 $a$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=a$.

**(c)**: 由 (b), $f$ 有不动点集 $E=\left\{x:f\left(x\right)=x\right\}$ 非空. 对 $x\in E$, $f\left(g\left(x\right)\right)=g\left(f\left(x\right)\right)=g\left(x\right)$, 故 $g\left(x\right)\in E$. 令 $m=\inf E$, $M=\sup E$. $E$ 闭 (由 $f-\operatorname{id}$ 连续), 故 $m,M\in E$. 考虑 $h=f-g$. $h\left(m\right)=f\left(m\right)-g\left(m\right)=m-g\left(m\right)$. 因 $g\left(m\right)\in E$, $g\left(m\right)\ge m$, 故 $h\left(m\right)\le 0$. 同理 $h\left(M\right)=M-g\left(M\right)\ge 0$. 由介值定理, 存在 $a\in\left[m,M\right]\subset E$ 使 $h\left(a\right)=0$, 即 $f\left(a\right)=g\left(a\right)$.

**(d)**: 设 $f\circ f$ 有不动点 $p$, 即 $f\left(f\left(p\right)\right)=p$. 若 $f\left(p\right)=p$, 则 $p$ 已是 $f$ 的不动点. 若 $f\left(p\right)\neq p$, 令 $h\left(x\right)=f\left(x\right)-x$. 则 $h\left(p\right)=f\left(p\right)-p$ 与 $h\left(f\left(p\right)\right)=f\left(f\left(p\right)\right)-f\left(p\right)=p-f\left(p\right)$ 异号. 由**定理 4.1** (区间连通) 与介值定理, $h$ 在 $p$ 与 $f\left(p\right)$ 之间有零点 $a$, 即 $f\left(a\right)=a$. $\blacksquare$

### 习题三

(7.3 完备性)

(1) 证明赋范线性空间 $E$ 完备当且仅当每个**定义 6.22** (绝对收敛级数) 绝对收敛级数都收敛.

(2) 设 $E$ 是有可数无穷基的赋范线性空间. 取规范基 $\left\{e_n\right\}_{n\ge 1}$, $\left\|e_n\right\|=1$. 令 $F_n=\operatorname{span}\left(e_1,\dots,e_n\right)$, 定义 $\lambda_1=1/3$, $\lambda_{n+1}=\frac{1}{3}d\left(\lambda_n e_n,F_{n-1}\right)$. 证明 $\sum\lambda_n e_n$ 绝对收敛但不收敛, 因而 $E$ 不完备.

### 解答 习题三

**第 1 小题**: ($\Rightarrow$) 设 $E$ 是**定义 6.20** (赋范线性空间) 且完备, $\sum u_n$ 是**定义 6.22** (绝对收敛级数), 即 $\sum\left\|u_n\right\|<\infty$. 部分和 $S_n=\sum_{k=1}^n u_k$ 是**定义 6.3** (柯西列): 对 $m>n$,

$$
\left\|S_m-S_n\right\|=\left\|\sum_{k=n+1}^m u_k\right\|\le\sum_{k=n+1}^m\left\|u_k\right\|\to 0.
$$

由**定义 6.4** (完备度量空间), $S_n$ 收敛.

($\Leftarrow$) 设每个**定义 6.22** (绝对收敛级数) 都收敛. 任取**定义 6.3** (柯西列) $\left(x_n\right)$. 选子列 $\left(x_{\varphi\left(n\right)}\right)$ 使对 $p\ge\varphi\left(n\right)$, $\left\|x_p-x_{\varphi\left(n\right)}\right\|\le 2^{-n}$. 令

$$
a_1=x_{\varphi\left(1\right)},\qquad a_n=x_{\varphi\left(n\right)}-x_{\varphi\left(n-1\right)}\ \left(n\ge 2\right).
$$

则 $\left\|a_n\right\|\le 2^{-\left(n-1\right)}$, 故 $\sum a_n$ 绝对收敛. 由假设它收敛于 $s$, 其部分和正是 $x_{\varphi\left(n\right)}$, 故子列收敛于 $s$. 由柯西列性质, 原列 $x_n\to s$. 故 $E$ 完备.

**第 2 小题**: 由递推, $\lambda_n\le 3^{-n}$ (归纳: $\lambda_1=1/3$, $\lambda_{n+1}=\frac{1}{3}d\left(\lambda_n e_n,F_{n-1}\right)\le\frac{1}{3}\lambda_n\left\|e_n\right\|=\lambda_n/3$). 故 $\sum\left\|\lambda_n e_n\right\|=\sum\lambda_n<\infty$, 绝对收敛.

反设 $\sum\lambda_n e_n$ 收敛于 $x$. 因 $E$ 是可数基的, $x\in F_N$ 对某个 $N$ (有限展开). 令 $y=x-\sum_{i=1}^N\lambda_i e_i\in F_N$. 则

$$
3\lambda_{N+2}\le d\left(\lambda_{N+1}e_{N+1},F_N\right)\le\left\|\lambda_{N+1}e_{N+1}-y\right\|=\left\|\sum_{i=N+2}^{\infty}\lambda_i e_i\right\|\le\sum_{i=N+2}^{\infty}\lambda_i\le\frac{3}{2}\lambda_{N+2},
$$

其中最后一步由 $\lambda_{i+1}\le\lambda_i/3$ 得等比和 $\sum_{i=N+2}^\infty\lambda_i\le\frac{3}{2}\lambda_{N+2}$. 这给出 $3\lambda_{N+2}\le\frac{3}{2}\lambda_{N+2}$, 矛盾 ($\lambda_{N+2}>0$). 故级数不收敛. 由第 1 小题, $E$ 不完备. $\blacksquare$

### 习题四

(7.4 贝尔纲定理)

(1) 设 $E$ 是有可数无穷基的赋范线性空间. 令 $F_n=\operatorname{span}\left(e_1,\dots,e_n\right)$. 用**定理 6.13** (贝尔纲定理) 证明 $E$ 不完备.

(2) 设 $\left(E,d\right)$ 完备, $\left(F,\delta\right)$ 是度量空间, $f_n:E\to F$ 连续且逐点收敛到 $f:E\to F$. (a) 对 $\varepsilon>0$ 与 $n\in\mathbb N$, 令

$$
F_{n,\varepsilon}=\left\{x\in E:\ \forall p\ge n,\ \delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}.
$$

用贝尔纲定理证明 $\Omega_\varepsilon=\bigcup_n\operatorname{int}F_{n,\varepsilon}$ 在 $E$ 中稠密. (b) 证明对 $x_0\in\Omega_\varepsilon$, 存在邻域 $V$ 使对 $x\in V$, $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le 3\varepsilon$. (c) 证明 $f$ 的连续点集稠密. (d) 证明可导函数 $f:\mathbb R\to\mathbb R$ 的导函数 $f'$ 的连续点集在 $\mathbb R$ 中稠密.

### 解答 习题四

**第 1 小题**: 每个 $F_n$ 是有限维子空间, 故闭 (**定义 3.2** (闭集)), 且无内部 (真子空间不含开球). $E=\bigcup_n F_n$. 若 $E$ 完备, 由**推论 6.14** (递增闭集族), 某个 $F_n$ 有非空内部, 矛盾. 故 $E$ 不完备.

**第 2 小题 (a)**: 每个 $F_{n,\varepsilon}$ 闭: 对固定 $p\ge n$, $\left\{x:\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}$ 由**定义 3.3** (连续映射) 连续, 故闭; $F_{n,\varepsilon}$ 是它们的交, 闭. 因 $f_n$ 逐点收敛, $\bigcup_n F_{n,\varepsilon}=E$. 令 $G=E\setminus\Omega_\varepsilon=\bigcap_n\left(E\setminus\operatorname{int}F_{n,\varepsilon}\right)$. $G$ 闭. 每个 $G\cap F_{n,\varepsilon}$ 是闭且无内部 (因 $G$ 去掉了所有内部). 由**定理 6.13** (贝尔纲定理) 及其**推论 6.14** (递增闭集族), $G$ 无内部, 即 $\Omega_\varepsilon$ 稠密.

**(b)**: 取 $x_0\in\Omega_\varepsilon$, 则 $x_0\in\operatorname{int}F_{n,\varepsilon}$ 对某个 $n$, 故存在邻域 $V\subset F_{n,\varepsilon}$. 对 $x\in V$ 与 $p\ge n$, $\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon$. 令 $p\to\infty$ 得 $\delta\left(f\left(x\right),f_n\left(x\right)\right)\le\varepsilon$. 特别对 $x_0\in V$, $\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)\le\varepsilon$. 故

$$
\delta\left(f\left(x_0\right),f\left(x\right)\right)\le\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)+\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)+\delta\left(f_n\left(x\right),f\left(x\right)\right).
$$

第三项 $\le\varepsilon$. 第一项 $\le\varepsilon$. 中间项由 $f_n$ 连续, 可取 $V$ 更小使 $\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)\le\varepsilon$. 合计 $\le 3\varepsilon$.

**(c)**: 令 $\Omega=\bigcap_{m\ge 1}\Omega_{1/m}$. 由**定义 3.8** (稠密), 每个 $\Omega_{1/m}$ 稠密开 (或至少稠密), 由**定理 6.13** (贝尔纲定理), $\Omega$ 稠密. 对 $x_0\in\Omega$ 与任意 $\varepsilon>0$, 由 (b) 存在邻域 $V$ 使 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le 3/m<\varepsilon$ (取 $m$ 使 $3/m<\varepsilon$). 故 $f$ 在 $x_0$ 连续. 因而连续点集 $\Omega$ 稠密.

**(d)**: 令 $f:\mathbb R\to\mathbb R$ 可导. 定义差商

$$
g_n\left(x\right)=n\left(f\left(x+\frac{1}{n}\right)-f\left(x\right)\right).
$$

每个 $g_n$ 连续, 且 $g_n\left(x\right)\to f'\left(x\right)$ 逐点. 由 (c), $g_n$ 的逐点极限 $f'$ 的连续点集在 $\mathbb R$ 中稠密. $\blacksquare$
