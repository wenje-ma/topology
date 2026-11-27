# week9

> **命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)**
> 
> $\mathbb{R}$ 的子集连通当且仅当它是区间. (讲义第 1 讲, p6)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **定义 1.10 (同胚)**
> 
> 连续双射 $f:X\to{}Y$ 若其逆也连续, 称为同胚; $x\mapsto{}px$ ($p>0$) 是 $\mathbb{R}$ 的自同胚. (讲义第 1 讲, p15)

> **定义 1.11 (闭包, 内部与边界)**
> 
> $A\subset{}X$ 的闭包 $\overline{A}$ 是包含 $A$ 的最小闭集; 内部是含于 $A$ 的最大开集. (讲义第 1 讲, p17)

> **定义 1.12 (稠密与可分)**
> 
> 称 $A\subset{}X$ 稠密, 若 $\overline{A}=X$; 有可数稠密子集的空间称为可分的. (讲义第 1 讲, p17)

> **命题 1.14 (连续函数构成代数)**
> 
> $X$ 上连续实值函数之集对加法与乘法封闭, 且绝对值仍连续. (讲义第 1 讲, p22)

> **定理 2.2 (连续像连通)**
> 
> 连通空间的连续像连通. (讲义第 2 讲, p14)

> **定义 2.3 (凸集)**
> 
> 称 $K\subset\mathbb{R}^n$ 凸, 若 $K$ 中任意两点之间的连线段含于 $K$; 凸集对凸组合封闭, 即 $\sum_i\lambda_ix_i\in{}K$ 只要 $x_i\in{}K$, $\lambda_i\ge0$, $\sum_i\lambda_i=1$. (讲义第 2 讲, p16)

> **命题 2.4 (凸集路径连通)**
> 
> $\mathbb{R}^n$ 中的凸集路径连通, 从而连通. (讲义第 2 讲, p16)

> **定理 2.7 (连通族之并)**
> 
> 若连通集族中任意两个都可由族中有限个成员连成链 (例如有公共点), 则其并连通. (讲义第 2 讲, p24)

> **命题 4.1 (度量空间的序列刻画)**
> 
> 在度量空间中, $x$ 是 $A$ 的极限点当且仅当有 $\left\{x_n\right\}\subset{}A-\left\{x\right\}$ 使 $x_n\to{}x$; $A$ 闭当且仅当其中收敛序列的极限仍在 $A$ 中. (讲义第 4 讲, p2)

> **定义 4.4 (柯西列)**
> 
> 度量空间中的序列 $\left\{x_i\right\}$ 称为柯西列, 若 $\lim_{i,j\to\infty}d\left(x_i,x_j\right)=0$. (讲义第 4 讲, p6)

> **定义 4.5 (完备度量空间)**
> 
> 每个柯西列都收敛 (极限属于该空间) 的度量空间称为完备的. (讲义第 4 讲, p6)

> **定理 4.6 (完备空间的闭子集完备)**
> 
> 完备度量空间的闭子集在诱导度量下完备. (讲义第 4 讲, p7)

> **命题 4.8 ($\mathbb{R}^n$ 完备)**
> 
> $\mathbb{R}^n$ 在通常度量下完备. (讲义第 4 讲, p9)

> **定理 4.10 (贝尔纲定理)**
> 
> 若 $X$ 完备, 则可数个稠密开集之交仍稠密, 特别地非空. (讲义第 4 讲, p31)

> **推论 4.11 (递增闭集的覆盖)**
> 
> 若 $X$ 完备且 $X=\bigcup_iF_i$, 其中 $F_1\subset{}F_2\subset\cdots$ 是递增闭集, 则某个 $F_i$ 有内点. (讲义第 4 讲, p31)

## 9.1 (贝尔纲定理: 无界开集与无穷远处的刻度)

设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 连续, 且对任意 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 收敛到 $0$.

(1) 设 $\Omega\subset\left(0,\infty\right)$ 是一个非平凡开集且无界. 考虑集合 $\Omega_n=\left\{x\in\mathbb{R}:\exists{}p\ge{}n,px\in\Omega\right\}$. 证明对任意 $n\ge1$, $\Omega_n$ 在 $\mathbb{R}$ 中是稠密开集;

(2) 利用贝尔纲定理, 证明 $\exists{}x_0,\forall{}N\in\mathbb{N},\exists{}n\ge{}N,nx_0\in\Omega$;

(3) 证明 $\lim_{x\to\infty}f\left(x\right)=0$.

2024 年卷 B 题四.

### 解答 9.1

(1) 由**定义 1.10 (同胚)**, $x\mapsto{}px$ 是 $\mathbb{R}$ 的自同胚, 故 $\Omega/p=\left\{x:px\in\Omega\right\}$ 是开集, 且

$$
\Omega_n=\bigcup_{p\ge{}n}\left(\Omega/p\right).
$$

因 $\Omega$ 无界且 $\Omega\subset\left(0,\infty\right)$, $\Omega_n\subset\left(0,\infty\right)$; 下面的论证给出 $\Omega_n$ 在 $\left(0,\infty\right)$ 中稠密 (**定义 1.12 (稠密与可分)**).

设 $0<{}a<{}b$ 是任一开区间. 取 $y\in\Omega$ 充分大, 使 $y\left(\frac{1}{a}-\frac{1}{b}\right)>1$ (因 $\Omega$ 无界), 则区间 $\left(\frac{y}{b},\frac{y}{a}\right)$ 长度大于 $1$, 取其中整数 $p\ge{}n$, 则

$$
\frac{y}{p}\in\left(a,b\right),\quad{}p\cdot\frac{y}{p}=y\in\Omega,
$$

故 $\frac{y}{p}\in\Omega_n\cap\left(a,b\right)$. 于是每个开区间都含 $\Omega_n$ 的点, 由**定义 1.11 (闭包, 内部与边界)** $\Omega_n$ 在 $\left(0,\infty\right)$ 中稠密.

$\blacksquare$

(2) 由第 (1) 小题每个 $\Omega_n\cap\left[1,\infty\right)$ 是 $\left[1,\infty\right)$ 中的稠密开集. 由**命题 4.8 ($\mathbb{R}^n$ 完备)** 与**定理 4.6 (完备空间的闭子集完备)**, $\left[1,\infty\right)$ 完备; 由**定理 4.10 (贝尔纲定理)**,

$$
\bigcap_{n\ge1}\left(\Omega_n\cap\left[1,\infty\right)\right)
$$

是 $\left[1,\infty\right)$ 中的稠密集, 特别非空. 取其中的点 $x_0$, 则 $x_0>0$ 且对每个 $n$ 存在 $p\ge{}n$ 使 $px_0\in\Omega$; 即对每个 $N$ 取 $n=N$ 得所需.

$\blacksquare$

(3) 设 $\epsilon>0$, 令 $\Omega=\left\{x>0:\left|f\left(x\right)\right|>\epsilon\right\}$. 由 $f$ 连续与**定义 1.8 (连续映射)** 及**命题 1.14 (连续函数构成代数)**, $\Omega$ 是 $\left(0,\infty\right)$ 中的开集. 若 $\lim_{x\to\infty}f\left(x\right)\neq0$, 则存在 $\epsilon>0$ 与 $x_k\to\infty$ 使 $\left|f\left(x_k\right)\right|>\epsilon$, 即 $\Omega$ 无界, 于是第 (2) 小题给出 $x_0>0$ 与一列 $n_j\to\infty$ 使 $n_jx_0\in\Omega$, 即 $\left|f\left(n_jx_0\right)\right|>\epsilon$ 对无穷多个 $j$ 成立, 与 $f\left(nx_0\right)\to0$ 矛盾. 故对每个 $\epsilon>0$, $\Omega$ 有界, 即存在 $X$ 使 $x>X$ 时 $\left|f\left(x\right)\right|\le\epsilon$; 由 $\epsilon$ 任意, $\lim_{x\to\infty}f\left(x\right)=0$.

$\blacksquare$


## 9.2 (贝尔纲版本, 球面与双曲面的连通性, 开子空间的完备化)

本大题各小题相互独立.

(1) 写出贝尔纲定理的一个版本;

(2) 证明空间 $S^2=\left\{\left(x,y,z\right)\in\mathbb{R}^3:x^2+y^2+z^2=1\right\}$ 是连通的; 证明空间 $H^2=\left\{\left(x,y,z\right)\in\mathbb{R}^3:x^2+y^2-z^2=-1\right\}$ 不是连通的;

(3) 设 $\left(X,d\right)$ 是完备度量空间. 证明若 $F\subset{}X$ 是闭子空间, 则 $\left(F,d\right)$ 完备; 证明若 $O\subset{}X$ 是开子空间, 则 $\left(O,d\right)$ 不一定完备;

(4) 附加题. 设 $\left(X,d\right)$ 完备, $O\subset{}X$ 开. 证明存在 $O$ 上由 $d$ 诱导的度量 $d'$ 使 $\left(O,d'\right)$ 完备.

2024 年卷 C 题一.

### 解答 9.2

(1) 由**定理 4.10 (贝尔纲定理)**: 若 $X$ 是完备度量空间, $\left\{U_i\right\}_{i\ge1}$ 是一列稠密开集, 则 $\bigcap_iU_i$ 稠密. 等价地, 由**推论 4.11 (递增闭集的覆盖)**, 若 $X$ 完备且 $X$ 是一列递增闭集之并, 则其中某个闭集有内点.

$\blacksquare$

(2) 记 $D=\left\{\left(x,y\right):x^2+y^2\le1\right\}$, 它是 $\mathbb{R}^2$ 中的凸集 (**定义 2.3 (凸集)**), 由**命题 2.4 (凸集路径连通)** 连通. 映射

$$
\left(x,y\right)\longmapsto\left(x,y,\sqrt{1-x^2-y^2}\right),\quad{}\left(x,y\right)\longmapsto\left(x,y,-\sqrt{1-x^2-y^2}\right)
$$

在 $D$ 上连续 (根号在 $\left[0,1\right]$ 上连续), 由**定理 2.2 (连续像连通)** 它们的像 $D_+,D_-$ 连通, 且 $D_+\cup{}D_-=S^2$. 两者都含赤道圆 $\left\{\left(x,y,0\right):x^2+y^2=1\right\}\neq\emptyset$, 由**定理 2.7 (连通族之并)** $S^2=D_+\cup{}D_-$ 连通.

对 $H^2$: 由 $x^2+y^2-z^2=-1$ 得 $z^2=1+x^2+y^2\ge1$, 故 $H^2\subset\left\{z\ge1\right\}\cup\left\{z\le-1\right\}$, 且 $\left(0,0,\pm1\right)\in{}H^2$. 投影 $\left(x,y,z\right)\mapsto{}z$ 在 $H^2$ 上连续, 若 $H^2$ 连通, 由**定理 2.2 (连续像连通)** 其像 $\pi\left(H^2\right)$ 连通, 由**命题 1.1 ($\mathbb{R}$ 中的连通集与紧集)** 是区间; 但 $\pi\left(H^2\right)$ 含 $1$ 与 $-1$ 而不含 $0$, 不是区间, 矛盾. 故 $H^2$ 不连通.

$\blacksquare$

(3) 闭的情形即**定理 4.6 (完备空间的闭子集完备)**: $F$ 中的柯西列是 $X$ 中的柯西列, 其极限在 $X$ 中存在, 又 $F$ 闭, 由**命题 4.1 (度量空间的序列刻画)** 极限属于 $F$.

开的情形: 取 $X=\mathbb{R}$, $O=\left(0,1\right)$. 序列 $x_n=\frac{1}{n}$ 在 $\left(0,1\right)$ 中柯西 (**定义 4.4 (柯西列)**); 若它在 $\left(0,1\right)$ 的子空间度量下收敛到 $x$, 则它作为 $\mathbb{R}$ 中的序列也收敛到 $x$, 而 $\frac{1}{n}\to0$ 于 $\mathbb{R}$ 且极限唯一, 故 $x=0\notin{}O$, 矛盾. 由**定义 4.5 (完备度量空间)** $\left(O,d\right)$ 不完备.

$\blacksquare$

(4) 令 $g\left(x\right)=d\left(x,X-O\right)=\inf\left\{d\left(x,y\right):y\in{}X-O\right\}$, $\phi\left(x\right)=\frac{1}{g\left(x\right)}$, 及

$$
d'\left(x,y\right)=d\left(x,y\right)+\left|\phi\left(x\right)-\phi\left(y\right)\right|.
$$

$g$ 满足 $\left|g\left(x\right)-g\left(y\right)\right|\le{}d\left(x,y\right)$, 故连续; 又 $x\in{}O$ 而 $X-O$ 闭, 故 $g\left(x\right)>0$ (否则 $x$ 是 $X-O$ 中序列的极限, 由**命题 4.1 (度量空间的序列刻画)** 属于 $X-O$). 于是 $\phi$ 是 $O$ 上连续正函数, $d'$ 正定, 对称, 三角不等式由 $d$ 与实数的同名不等式给出, 故 $d'$ 是 $O$ 上的度量, 且 $d\le{}d'$.

先设 $\left\{x_n\right\}$ 在 $d'$ 下柯西. 由 $d\le{}d'$ 它在 $d$ 下柯西, 由 $X$ 完备 (**定义 4.5 (完备度量空间)**) 存在 $x\in{}X$ 使 $d\left(x_n,x\right)\to0$; 又 $\left|\phi\left(x_n\right)-\phi\left(x_m\right)\right|\le{}d'\left(x_n,x_m\right)$, 故 $\left\{\phi\left(x_n\right)\right\}$ 是 $\mathbb{R}$ 中的柯西列, 由**命题 4.8 ($\mathbb{R}^n$ 完备)** 它收敛, 从而有界.

若 $x\notin{}O$, 即 $x\in{}X-O$, 则 $g\left(x_n\right)\le{}d\left(x_n,x\right)\to0$, 于是 $\phi\left(x_n\right)=\frac{1}{g\left(x_n\right)}\to+\infty$, 与 $\left\{\phi\left(x_n\right)\right\}$ 有界矛盾. 故 $x\in{}O$. 由 $\phi$ 在 $x$ 连续, $\phi\left(x_n\right)\to\phi\left(x\right)$, 于是

$$
d'\left(x_n,x\right)=d\left(x_n,x\right)+\left|\phi\left(x_n\right)-\phi\left(x\right)\right|\longrightarrow0.
$$

故 $\left(O,d'\right)$ 完备.

$\blacksquare$
