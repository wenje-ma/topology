# 作业 12

> **定理 5.2** (区间紧)<br>区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.5** (完备化)<br>任意度量空间可自然嵌入一个完备度量空间; 实数轴 $\mathbb R$ 是有理数集的完备化, 故 $\mathbb R$ 完备. (教材 $\S6$)

> **定义 6.7** (一致收敛与一致度量)<br>$d\left(f,g\right)=\sup_X\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛当且仅当 $d\left(f_n,g\right)\to0$. (教材 $\S6$)

> **定义 6.9** (上确界度量)<br>紧集 $K$ 上连续函数空间 $C\left(K\right)$ 装备 $d\left(f,g\right)=\sup_{x\in K}\left|f\left(x\right)-g\left(x\right)\right|$, 即上确界范数诱导的度量. (教材 $\S6$)

> **定理 6.7** (连续函数的一致极限连续)<br>连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **推论 6.8** ($C\left(X,Y\right)$ 完备)<br>$Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

### 习题一

第一部分是对角线论证. 设 $f_n\left(m\right)$ 是正整数上的函数列, 一致有界, 即存在常数 $C$ 使对一切 $n,m$ 有 $\left|f_n\left(m\right)\right|\le C$. 证明序列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 有收敛子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$.

### 解答 习题一

数列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 含于有界闭区间 $\left[-C,C\right]$. 由**定理 5.2** (区间紧) 平移即知 $\left[-C,C\right]$ 是紧集; 由**定理 6.1** (紧=序列紧), 紧度量空间中每个序列都有收敛子列. 故存在子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$ 收敛. $\blacksquare$

### 习题二

沿用习题一的记号. 证明可以依次构造子列 $\left(f_{n_i^{\left(k\right)}}\left(m\right)\right)_{i\ge0}$, 使 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛.

### 解答 习题二

归纳构造. $k=1$ 时由习题一已得子列 $\left(f_{n_i^{\left(1\right)}}\right)$, 使 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)$ 收敛. 设已构造第 $k$ 个子列 $\left(f_{n_i^{\left(k\right)}}\right)$. 数列 $\left(f_{n_i^{\left(k\right)}}\left(k+1\right)\right)_{i\ge0}$ 仍含于 $\left[-C,C\right]$, 由**定理 5.2** (区间紧) 与**定理 6.1** (紧=序列紧), 有收敛子列, 记为 $\left(f_{n_i^{\left(k+1\right)}}\left(k+1\right)\right)_{i\ge0}$, 其中 $\left(n_i^{\left(k+1\right)}\right)$ 是 $\left(n_i^{\left(k\right)}\right)$ 的子列. 于是 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且由构造 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 收敛. 归纳完成. $\blacksquare$

### 习题三

证明存在子列 $\left(f_{n_i}\left(m\right)\right)$, 使对每个固定的 $m$, $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛. 可考虑序列 $n_k=n_k^{\left(k\right)}$.

### 解答 习题三

取对角子列 $n_i=n_i^{\left(i\right)}$. 固定 $m$. 对一切 $i\ge m$, 由嵌套关系, $\left(n_j^{\left(i\right)}\right)_{j\ge1}$ 是 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 的子列, 特别地 $n_i=n_i^{\left(i\right)}$ 本身是第 $m$ 个子列 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 中序号充分大的一项. 而由构造, $\left(f_{n_j^{\left(m\right)}}\left(m\right)\right)_{j\ge1}$ 收敛. 收敛序列的尾部仍收敛, 故子列 $\left(f_{n_i}\left(m\right)\right)_{i\ge m}$ 收敛, 即 $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 收敛. 对一切 $m$ 同时成立. $\blacksquare$

### 习题四

第二部分是 $\epsilon/3$ 论证. 设 $C\left[a,b\right]$ 是 $\left[a,b\right]$ 上连续实值函数空间, 装备**定义 6.9** (上确界度量) $d\left(f,g\right)=\sup_{x\in\left[a,b\right]}\left|f\left(x\right)-g\left(x\right)\right|$. 设 $\left(f_n\right)$ 是该度量下的**定义 6.3** (柯西列). 证明对每个 $x\in\left[a,b\right]$, $\left(f_n\left(x\right)\right)$ 收敛到某个 $f\left(x\right)\in\mathbb R$.

### 解答 习题四

由 $\left(f_n\right)$ 是**定义 6.3** (柯西列), 对任意 $\epsilon>0$ 存在 $N$, 使 $n,m\ge N$ 时

$$
\sup_{x\in\left[a,b\right]}\left|f_n\left(x\right)-f_m\left(x\right)\right|<\epsilon.
$$

固定 $x\in\left[a,b\right]$, 则 $\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\sup<\epsilon$, 故 $\left(f_n\left(x\right)\right)$ 是 $\mathbb R$ 中的**定义 6.3** (柯西列). 由**定义 6.5** (完备化), $\mathbb R$ 是**定义 6.4** (完备度量空间), 故 $\left(f_n\left(x\right)\right)$ 收敛. 记其极限为 $f\left(x\right)$. 逐点极限 $f$ 由此定义. $\blacksquare$

### 习题五

设 $f$ 是连续函数列 $\left(f_n\right)$ 的极限. 固定 $x\in\left[a,b\right]$ 与 $\epsilon>0$. 证明可选取 $n$ 使 $\left\|f_n-f\right\|_\infty<\epsilon/3$; 证明可选取 $\delta>0$, 使 $\left|x-y\right|<\delta$ 蕴含 $\left|f_n\left(x\right)-f_n\left(y\right)\right|<\epsilon/3$; 由此证明 $f$ 连续.

### 解答 习题五

第一步, 由习题六的结论 $\left(f_n\right)$ 依**定义 6.7** (一致收敛与一致度量) 一致收敛到 $f$, 故存在 $n$ 使 $\left\|f_n-f\right\|_\infty<\epsilon/3$.

第二步, 固定该 $n$, 由 $f_n$ 连续, 存在 $\delta>0$, 使 $y\in\left[a,b\right]$ 且 $\left|x-y\right|<\delta$ 时 $\left|f_n\left(x\right)-f_n\left(y\right)\right|<\epsilon/3$.

第三步, 对满足 $\left|x-y\right|<\delta$ 的 $y$,

$$
\left|f\left(x\right)-f\left(y\right)\right|\le\left|f\left(x\right)-f_n\left(x\right)\right|+\left|f_n\left(x\right)-f_n\left(y\right)\right|+\left|f_n\left(y\right)-f\left(y\right)\right|<\frac{\epsilon}{3}+\frac{\epsilon}{3}+\frac{\epsilon}{3}=\epsilon.
$$

这正是**定理 6.7** (连续函数的一致极限连续) 的 $\epsilon/3$ 论证, 故 $f$ 在 $x$ 连续. $x$ 任意, $f$ 在 $\left[a,b\right]$ 上连续. $\blacksquare$

### 习题六

证明 $f_n\to f$ 在 $C\left[a,b\right]$ 中, 即依**定义 6.9** (上确界度量) 收敛; 由此得出 $C\left[a,b\right]$ 是完备的.

### 解答 习题六

由习题四, $\left(f_n\right)$ 逐点收敛到 $f$. 由 $\left(f_n\right)$ 是**定义 6.3** (柯西列), 对任意 $\epsilon>0$ 存在 $N$, 使 $n,m\ge N$ 时 $\sup_x\left|f_n\left(x\right)-f_m\left(x\right)\right|<\epsilon$. 固定 $n\ge N$ 与任意 $x$, 令 $m\to\infty$, 由习题四 $f_m\left(x\right)\to f\left(x\right)$, 故

$$
\left|f_n\left(x\right)-f\left(x\right)\right|=\lim_{m\to\infty}\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\epsilon.
$$

对 $x$ 取上确界, 得 $\left\|f_n-f\right\|_\infty\le\epsilon$ 对一切 $n\ge N$ 成立. 由**定义 6.7** (一致收敛与一致度量) 与**定义 6.9** (上确界度量), $f_n\to f$ 一致收敛, 即在 $C\left[a,b\right]$ 中收敛.

由习题五, $f$ 连续, 故 $f\in C\left[a,b\right]$. 于是 $C\left[a,b\right]$ 中每个**定义 6.3** (柯西列) 都收敛到 $C\left[a,b\right]$ 中的元素, 由**定义 6.4** (完备度量空间), $C\left[a,b\right]$ 完备, 即**推论 6.8** ($C\left(X,Y\right)$ 完备) 的特例. $\blacksquare$
