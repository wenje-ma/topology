# week12

> **定义 1.3 (闭集)**
> 
> 称 $F\subset{}X$ 是闭集, 若 $X-F$ 是开集; 度量空间中单点集是闭集. (讲义第 1 讲, p10)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **命题 1.9 (连续的复合与基上的判定)**
> 
> 连续映射的复合连续. (讲义第 1 讲, p14)

> **推论 4.11 (递增闭集的覆盖)**
> 
> 若 $X$ 完备且 $X=\bigcup_iF_i$, 其中 $F_1\subset{}F_2\subset\cdots$ 是递增闭集, 则某个 $F_i$ 有内点. (讲义第 4 讲, p31)

> **定义 5.1 (拓扑向量空间)**
> 
> 赋范线性空间是拓扑向量空间: 加法与数乘连续, 平移与伸缩是同胚, 范数诱导度量与拓扑. (讲义第 5 讲, p15)

> **命题 5.2 (线性映射连续的条件)**
> 
> 赋范线性空间之间的线性映射连续当且仅当它在 $0$ 连续, 当且仅当存在 $C$ 使 $\left|f\left(x\right)\right|\le{}C\left|x\right|$. (讲义第 5 讲, p17)

## 12.1 (巴拿赫空间上逐点有限次归零的线性映射)

称完备的赋范线性空间为巴拿赫空间. 考虑巴拿赫空间 $X$ 与连续线性映射 $f:X\to{}X$. 假设对每个 $x\in{}X$ 存在 $n\in\mathbb{N}$ 使 $f^n\left(x\right)=0$, 其中 $f^n$ 是 $n$ 次复合.

(1) 考虑 $F_n=\left\{x\in{}X:f^n\left(x\right)=0\right\}$. 证明对每个 $n\in\mathbb{N}$, $F_n$ 都是 $X$ 的闭子集;

(2) 证明存在 $N\in\mathbb{N}$ 使 $F_N$ 有内点;

(3) 证明第 (2) 小题中的 $F_N$ 一定是 $X$;

(4) 证明 $f$ 是幂零映射;

(5) 考虑多项式空间 $\mathbb{R}\left[X\right]$ 中的线性映射 $f:P\mapsto{}P'$. 讨论这个例子与上述结果的关系.

2025 年卷 B 题二.

### 解答 12.1

(1) $F_n=\ker\left(f^n\right)$. 由**命题 1.9 (连续的复合与基上的判定)** 与**命题 5.2 (线性映射连续的条件)**, $f^n$ 是连续线性映射; 由**定义 1.3 (闭集)** 与**定义 1.8 (连续映射)**, 单点集 $\left\{0\right\}$ 闭, 故 $F_n=\left(f^n\right)^{-1}\left(\left\{0\right\}\right)$ 闭; 线性显然, 故 $F_n$ 是闭子空间.

$\blacksquare$

(2) 由假设 $X=\bigcup_nF_n$, 且 $F_1\subset{}F_2\subset\cdots$. 由**定义 5.1 (拓扑向量空间)** 巴拿赫空间完备, 故由**推论 4.11 (递增闭集的覆盖)** 某个 $F_N$ 有内点.

$\blacksquare$

(3) 设闭子空间 $F_N$ 含球 $B\left(x_0,r\right)$. 对 $x\neq0$, 向量

$$
x_0+\frac{r}{2\left|x\right|}x\in{}B\left(x_0,r\right)\subset{}F_N,
$$

而 $x_0\in{}F_N$, 由线性得 $\frac{r}{2\left|x\right|}x\in{}F_N$, 再由线性得 $x\in{}F_N$. 故 $F_N=X$.

$\blacksquare$

(4) $F_N=X$ 即对一切 $x\in{}X$ 有 $f^N\left(x\right)=0$, 故 $f^N=0$, $f$ 幂零.

$\blacksquare$

(5) 在 $\mathbb{R}\left[X\right]$ 上取 $D\left(P\right)=P'$. 每个 $P$ 有 $\deg{}P'=\deg{}P-1$, 故 $m>\deg{}P$ 时 $D^m\left(P\right)=0$: 逐点最终归零成立. 但 $D$ 不幂零: 对任意 $m$ 有 $D^m\left(X^{m}\right)=m!\neq0$.

与 (1)-(4) 的结论对照, 差别在于 $\mathbb{R}\left[X\right]$ 不是巴拿赫空间. 此时 $F_n=\ker\left(D^n\right)$ 是次数小于 $n$ 的多项式之集, 都是 $D$-不变的真闭子空间且没有内点 (含 $P$ 的任一球含更高次的多项式), 于是 $\mathbb{R}\left[X\right]=\bigcup_nF_n$ 而没有任何 $F_n$ 有内点, 由**推论 4.11 (递增闭集的覆盖)** 可见该空间不能完备: 逐点到幂零的跳跃依赖贝尔纲, 其代价正是完备性.

$\blacksquare$
