# week7

> **定义 1.3 (闭集)**
> 
> 称 $F\subset{}X$ 是闭集, 若 $X-F$ 是开集. (讲义第 1 讲, p10)

> **命题 1.4 (闭集的运算)**
> 
> 闭集族的任意交闭, 有限并闭. (讲义第 1 讲, p10)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **定义 1.15 (邻域与序列收敛)**
> 
> $x$ 的邻域是含 $x$ 的开集. 称 $x_n\to{}x$, 若对 $x$ 的每个邻域 $V$ 存在 $N$ 使 $n\ge{}N$ 时 $x_n\in{}V$. (讲义第 1 讲, p23)

> **定理 4.6 (完备空间的闭子集完备)**
> 
> 完备度量空间的闭子集在诱导度量下完备. (讲义第 4 讲, p7)

> **命题 4.8 ($\mathbb{R}^n$ 完备)**
> 
> $\mathbb{R}^n$ 在通常度量下完备. (讲义第 4 讲, p9)

> **推论 4.11 (递增闭集的覆盖)**
> 
> 若 $X$ 完备且 $X=\bigcup_iF_i$, 其中 $F_1\subset{}F_2\subset\cdots$ 是递增闭集, 则某个 $F_i$ 有内点. (讲义第 4 讲, p31)

## 7.1 ($\left\{f\left(nx\right)\right\}$ 收敛到零蕴含 $f$ 在无穷远处趋于零)

设 $f:\mathbb{R}_{\ge0}\to\mathbb{R}$ 是一个连续函数, 并且对任意的 $x>0$, 数列 $\left\{f\left(nx\right)\right\}_{n\ge1}$ 都收敛到 $0$.

(1) 取定 $\epsilon>0$, 考虑集合 $F_n=\left\{x\ge0:\forall{}p\in\mathbb{N}, p\ge{}n, \left|f\left(px\right)\right|\le\epsilon\right\}$. 证明对任意 $n\ge0$, $F_n$ 都是闭集;

(2) 证明所有 $F_n$ 的并包含 $\left(0,\infty\right)$;

(3) 利用贝尔纲定理证明 $\lim_{x\to\infty}f\left(x\right)=0$.

2024 年卷 A 题四.

### 解答 7.1

(1) 因 $f$ 连续, 每个 $f^{-1}\left(\left[-\epsilon,\epsilon\right]\right)$ 是 $\mathbb{R}_{\ge0}$ 中的闭集 (**定义 1.8 (连续映射)** 与**定义 1.3 (闭集)**: $\left[-\epsilon,\epsilon\right]$ 的补集开, 其原像 $f^{-1}\left(\mathbb{R}-\left[-\epsilon,\epsilon\right]\right)$ 开). 于是

$$
F_n=\bigcap_{p\ge{}n}f^{-1}\left(\left[-\epsilon,\epsilon\right]\right)
$$

是可数个闭集之交, 由**命题 1.4 (闭集的运算)** 闭.

$\blacksquare$

(2) 设 $x>0$. 由假设 $f\left(px\right)\to0$, 故对上述 $\epsilon$ 存在 $n_x$ 使 $p\ge{}n_x$ 时 $\left|f\left(px\right)\right|\le\epsilon$, 即 $x\in{}F_{n_x}$. 故 $\left(0,\infty\right)\subset\bigcup_nF_n$.

$\blacksquare$

(3) 设 $\epsilon>0$. 记 $G_n=F_n\cap\left[1,\infty\right)$. 由**命题 4.8 ($\mathbb{R}^n$ 完备)** 与**定理 4.6 (完备空间的闭子集完备)**, $\left[1,\infty\right)$ 完备; $G_n$ 是 $\left[1,\infty\right)$ 中的闭集且在 $\epsilon$ 固定时随 $n$ 递增. 由第 (2) 小题 $\bigcup_nG_n\supset\left[1,\infty\right)$, 故由**推论 4.11 (递增闭集的覆盖)** 存在 $N$ 使 $G_N$ 在 $\left[1,\infty\right)$ 中有内点, 即存在 $1\le{}c<d$ 使 $\left(c,d\right)\subset{}G_N\subset{}F_N$.

对 $x>Nc$, 区间 $\left(\frac{x}{d},\frac{x}{c}\right)$ 长度为正, 取其中的整数 $p\ge{}N$, 则 $\frac{x}{p}\in\left(c,d\right)\subset{}F_N$, 且 $p\ge{}N$, 故由 $F_N$ 的定义 $\left|f\left(x\right)\right|=\left|f\left(p\cdot\frac{x}{p}\right)\right|\le\epsilon$.

于是对每个 $\epsilon>0$ 存在 $X=Nc$ 使 $x>X$ 时 $\left|f\left(x\right)\right|\le\epsilon$, 即由**定义 1.15 (邻域与序列收敛)** 一般的 $\epsilon$-$N$ 语言, $\lim_{x\to\infty}f\left(x\right)=0$.

$\blacksquare$
