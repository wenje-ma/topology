# week10

> **定义 1.6 (拓扑基)**
> 
> 一族子集 $\mathcal{B}$ 称为 $X$ 上某拓扑的基, 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $x\in{}X$ 与 $B_1,B_2\in\mathcal{B}$ 满足 $x\in{}B_1\cap{}B_2$, 存在 $B_3\in\mathcal{B}$ 使 $x\in{}B_3\subset{}B_1\cap{}B_2$; 该拓扑的开集恰为 $\mathcal{B}$ 中元素之并. (讲义第 1 讲, p12)

> **定理 1.7 (基判据)**
> 
> $\mathcal{B}$ 是拓扑 $\mathcal{O}$ 的基当且仅当 $\mathcal{B}\subset\mathcal{O}$, 且对任意 $O\in\mathcal{O}$ 与 $x\in{}O$ 存在 $B\in\mathcal{B}$ 使 $x\in{}B\subset{}O$. (讲义第 1 讲, p13)

> **定义 1.12 (稠密与可分)**
> 
> 称 $A\subset{}X$ 稠密, 若 $\overline{A}=X$; 有可数稠密子集的空间称为可分的. (讲义第 1 讲, p17)

> **定义 1.13 (极限点与孤立点)**
> 
> 称 $x$ 是 $A$ 的极限点, 若 $x$ 的每个邻域都含 $A-\left\{x\right\}$ 的点; 不是极限点的 $A$ 中点是孤立的. (讲义第 1 讲, p18)

> **定义 3.1 (开覆盖与紧致)**
> 
> 每个开覆盖都有有限子覆盖的空间称为紧致空间. (讲义第 3 讲, p2)

> **定理 4.2 (序列紧度量空间有可数基)**
> 
> 序列紧的度量空间有可数基. (讲义第 4 讲, p3)

## 10.1 (每个无穷子集都有极限点的度量空间紧致)

考虑一个度量空间 $X$, 使得其中任意无穷子集都有一个极限点.

(1) 证明对任意 $\delta>0$, $X$ 能被有限个半径为 $\delta$ 的小球覆盖;

(2) 证明 $X$ 是可分度量空间;

(3) 证明 $X$ 有一个可数的基;

(4) 证明 $X$ 是紧致空间;

(5) 附加题. 证明紧致度量空间 $K$ 一定可分.

2024 年卷 C 题二.

### 解答 10.1

(1) 设 $\delta>0$. 如下依次选点: 先取任一点 $x_1$; 若已选 $x_1,\dots,x_k$ 且存在 $x$ 使 $d\left(x,x_i\right)\ge\delta$ 对一切 $i\le{}k$ 成立, 就取 $x_{k+1}=x$; 否则停止.

该过程必在有限步停止: 若不然得到无穷集 $A=\left\{x_i\right\}$ 使 $i\neq{}j$ 时 $d\left(x_i,x_j\right)\ge\delta$, 由假设 $A$ 有极限点 $x$. 先注意对任意 $r>0$, $B\left(x,r\right)$ 含 $A$ 中无穷多个点. 若不然, $B\left(x,r\right)\cap{}A=\left\{a_1,\dots,a_l\right\}$ 有限, 令 $s=\min\left\{r,d\left(x,a_i\right):i\le{}l\right\}>0$, 则 $B\left(x,\frac{s}{2}\right)\cap{}A\subset\left\{x\right\}$, 与 $x$ 是 $A$ 的极限点 (**定义 1.13 (极限点与孤立点)**) 矛盾. 故 $B\left(x,\frac{\delta}{4}\right)$ 含 $A$ 中两个不同点 $a,a'$, 于是 $d\left(a,a'\right)<\frac{\delta}{2}<\delta$, 与 $\delta$ 分离矛盾.

设过程停在 $x_1,\dots,x_N$. 由停止条件, 对每个 $x\in{}X$ 存在 $i\le{}N$ 使 $d\left(x,x_i\right)<\delta$, 否则 $x$ 可被选入. 故 $X$ 被 $B\left(x_i,\delta\right)$, $i\le{}N$, 覆盖.

$\blacksquare$

(2) 对每个 $n\ge1$, 由第 (1) 小题存在有限集 $C_n$ 使 $X=\bigcup_{c\in{}C_n}B\left(c,\frac{1}{n}\right)$. 令 $C=\bigcup_nC_n$, 它是可数集. 对任意 $x\in{}X$ 与 $n$, 存在 $c\in{}C_n\subset{}C$ 使 $d\left(x,c\right)<\frac{1}{n}$, 故 $x$ 属于 $\overline{C}$. 由**定义 1.12 (稠密与可分)** $C$ 可数稠密, $X$ 可分.

$\blacksquare$

(3) 令

$$
\mathcal{B}=\left\{B\left(c,q\right):c\in{}C,q\in\mathbb{Q}_{>0}\right\},
$$

它是可数集 (由**定义 1.12 (稠密与可分)** 中 $C$ 可数). 验证**定义 1.6 (拓扑基)** 的条件: 每个 $B\left(c,q\right)$ 是开集; 又 $\bigcup\mathcal{B}=X$ (取 $c$ 充分接近 $x$ 与 $q$ 充分大). 加细: 设 $x\in{}B\left(c_1,q_1\right)\cap{}B\left(c_2,q_2\right)$, 令 $r=\min\left(q_1-d\left(x,c_1\right),q_2-d\left(x,c_2\right)\right)>0$, 取 $c\in{}C$ 使 $d\left(x,c\right)<\frac{r}{4}$, 取有理 $q$ 使 $\frac{r}{4}<{}q<\frac{r}{2}$, 则 $x\in{}B\left(c,q\right)\subset{}B\left(c_1,q_1\right)\cap{}B\left(c_2,q_2\right)$: 对 $y\in{}B\left(c,q\right)$,

$$
d\left(y,c_1\right)\le{}d\left(y,c\right)+d\left(c,x\right)+d\left(x,c_1\right)<\frac{r}{2}+\frac{r}{4}+\left(q_1-r\right)<{}q_1,
$$

同法得 $d\left(y,c_2\right)<{}q_2$. 故 $\mathcal{B}$ 是某拓扑的基; 而由**定理 1.7 (基判据)** 该拓扑与 $X$ 的原拓扑相同 (每个开集都含 $x$ 处的 $\mathcal{B}$ 元素). 故 $X$ 有可数基.

$\blacksquare$

(4) 设 $\left\{U_i\right\}$ 是 $X$ 的开覆盖, $\mathcal{B}=\left\{V_1,V_2,\dots\right\}$ 是第 (3) 小题的可数基. 对每个 $x\in{}X$ 由**定理 1.7 (基判据)** 取 $V_{j\left(x\right)}\in\mathcal{B}$ 与覆盖元 $U_{i\left(x\right)}$ 使 $x\in{}V_{j\left(x\right)}\subset{}U_{i\left(x\right)}$; 因 $\mathcal{B}$ 可数, 指标 $\left\{j\left(x\right)\right\}$ 是可数集, 对应的 $\left\{U_{i\left(x\right)}\right\}$ 给出了 $\left\{U_i\right\}$ 的可数子覆盖 $\left\{U_{i\left(j\right)}\right\}_{j\ge1}$.

反设它没有有限子覆盖. 则对每个 $m$ 存在

$$
x_m\in{}X-\bigcup_{j\le{}m}U_{i\left(j\right)}.
$$

若 $\left\{x_m\right\}$ 有限, 则某值 $x$ 出现无穷多次, 于是 $x=x_m$ 对无穷多个 $m$ 成立; 因 $x\in{}X$ 属于某个 $U_{i\left(j_0\right)}$, 取 $m\ge{}j_0$ 使 $x_m=x$, 得 $x\notin{}U_{i\left(j_0\right)}$, 矛盾. 故 $\left\{x_m\right\}$ 无穷, 由假设有极限点 $x$; 同第 (1) 小题的理由, 每球 $B\left(x,r\right)$ 含 $\left\{x_m\right\}$ 中无穷多个点. 取 $j_0$ 使 $x\in{}U_{i\left(j_0\right)}$, 由 $U_{i\left(j_0\right)}$ 开存在 $r>0$ 使 $B\left(x,r\right)\subset{}U_{i\left(j_0\right)}$, 于是存在 $m\ge{}j_0$ 使 $x_m\in{}B\left(x,r\right)\subset{}U_{i\left(j_0\right)}$, 与 $x_m\notin\bigcup_{j\le{}m}U_{i\left(j\right)}$ 矛盾. 故有可数覆盖必有有限子覆盖, 由**定义 3.1 (开覆盖与紧致)** $X$ 紧致.

$\blacksquare$

(5) 由第 (4) 小题 $K$ 紧, 故由**定理 4.2 (序列紧度量空间有可数基)** $K$ 有可数基 $\left\{V_\alpha\right\}$, 在每个非空 $V_\alpha$ 中取一点得可数集 $D$. 对 $K$ 中开集 $U$ 与 $x\in{}U$, 由基判据存在 $V_\alpha$ 使 $x\in{}V_\alpha\subset{}U$, 故 $D\cap{}U\neq\emptyset$; 于是 $\overline{D}=K$, 由**定义 1.12 (稠密与可分)** $K$ 可分.

$\blacksquare$
