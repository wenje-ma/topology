# week8

> **定义 1.6 (拓扑基)**
> 
> 一族子集 $\mathcal{B}$ 称为 $X$ 上某拓扑的基, 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $x\in{}X$ 与 $B_1,B_2\in\mathcal{B}$ 满足 $x\in{}B_1\cap{}B_2$, 存在 $B_3\in\mathcal{B}$ 使 $x\in{}B_3\subset{}B_1\cap{}B_2$; 该拓扑的开集恰为 $\mathcal{B}$ 中元素之并. (讲义第 1 讲, p12)

> **定理 1.7 (基判据)**
> 
> $\mathcal{B}$ 是拓扑 $\mathcal{O}$ 的基当且仅当 $\mathcal{B}\subset\mathcal{O}$, 且对任意 $O\in\mathcal{O}$ 与 $x\in{}O$ 存在 $B\in\mathcal{B}$ 使 $x\in{}B\subset{}O$. (讲义第 1 讲, p13)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **定义 1.10 (同胚)**
> 
> 连续双射 $f:X\to{}Y$ 若其逆也连续, 称为同胚; $x\mapsto{}px$ ($p>0$) 是 $\mathbb{R}$ 的自同胚. (讲义第 1 讲, p15)

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

## 8.1 (倒数度量)

考虑在 $x,y\in\left(0,\infty\right)$ 上定义的函数 $\delta\left(x,y\right)=\left|\frac{1}{x}-\frac{1}{y}\right|$.

(1) 证明 $\delta$ 是一个在 $\left(0,\infty\right)$ 上的度量;

(2) 证明由 $\delta$ 在 $\left(0,\infty\right)$ 上诱导的拓扑就是最常见的拓扑;

(3) 证明度量空间 $\left(\left(0,\infty\right),\delta\right)$ 不是完备的;

(4) 证明度量空间 $\left(\left(0,1\right],\delta\right)$ 是完备的.

2024 年卷 B 题二.

### 解答 8.1

(1) 正定性: $\delta\left(x,y\right)\ge0$, 且 $\delta\left(x,y\right)=0$ 当且仅当 $\frac{1}{x}=\frac{1}{y}$ 当且仅当 $x=y$. 对称性显然. 三角不等式: $\delta\left(x,z\right)=\left|\frac{1}{x}-\frac{1}{z}\right|\le\left|\frac{1}{x}-\frac{1}{y}\right|+\left|\frac{1}{y}-\frac{1}{z}\right|=\delta\left(x,y\right)+\delta\left(y,z\right)$, 由实数的三角不等式.

$\blacksquare$

(2) 令 $\phi\left(x\right)=\frac{1}{x}$, 它在 $\left(0,\infty\right)$ 上连续且 $\phi^{-1}=\phi$, 故由**定义 1.10 (同胚)** $\phi$ 是 $\left(0,\infty\right)$ 的自同胚, 且

$$
\delta\left(x,y\right)=\left|\phi\left(x\right)-\phi\left(y\right)\right|.
$$

设 $B_\delta\left(x,r\right)=\left\{y:\delta\left(x,y\right)<{}r\right\}$ 与 $B\left(u,r\right)=\left\{v:\left|v-u\right|<{}r\right\}$. 则

$$
B_\delta\left(x,r\right)=\phi^{-1}\left(B\left(\phi\left(x\right),r\right)\right),
$$

由 $\phi$ 连续 (**定义 1.8 (连续映射)**) 它是通常拓扑下的开集. 反之设 $x\in\left(0,\infty\right)$, $r>0$, $y\in{}B\left(x,r\right)$. 由 $\phi$ 连续于 $y$ 与 $\phi^{-1}$ 连续于 $\phi\left(y\right)$, 存在 $s>0$ 使 $\phi^{-1}\left(B\left(\phi\left(y\right),s\right)\right)\subset{}B\left(x,r\right)$, 即 $B_\delta\left(y,s\right)\subset{}B\left(x,r\right)$. 故通常拓扑的开球都是 $\delta$ 开集. 两个度量拓扑都以各自开球为基 (**定义 1.6 (拓扑基)**), 于是由**定理 1.7 (基判据)** 两面包含得两拓扑相同.

$\blacksquare$

(3) 取 $x_n=n$. 对 $m,n$ 有 $\delta\left(x_n,x_m\right)=\left|\frac{1}{n}-\frac{1}{m}\right|\to0$ ($m,n\to\infty$), 故 $\left\{x_n\right\}$ 是柯西列 (**定义 4.4 (柯西列)**). 若它在 $\left(0,\infty\right)$ 中 $\delta$-收敛到 $x$, 则 $\frac{1}{n}=\phi\left(x_n\right)\to\phi\left(x\right)=\frac{1}{x}$ (由 $\phi$ 连续), 但 $\frac{1}{n}\to0$, 故 $\frac{1}{x}=0$, 不可能. 故 $\left(\left(0,\infty\right),\delta\right)$ 不完备 (**定义 4.5 (完备度量空间)**).

$\blacksquare$

(4) $\phi$ 把 $\left(0,1\right]$ 双射到 $\left[1,\infty\right)$, 且

$$
\delta\left(x,y\right)=\left|\phi\left(x\right)-\phi\left(y\right)\right|,
$$

即 $\phi$ 是 $\left(\left(0,1\right],\delta\right)$ 到 $\left(\left[1,\infty\right),\left|\cdot\right|\right)$ 的等距双射. $\left[1,\infty\right)$ 在 $\mathbb{R}$ 中闭, 由**命题 4.8 ($\mathbb{R}^n$ 完备)** 与**定理 4.6 (完备空间的闭子集完备)** 它完备. 设 $\left\{x_n\right\}$ 在 $\delta$ 下柯西, 则 $\left\{\phi\left(x_n\right)\right\}$ 在 $\left[1,\infty\right)$ 中柯西 (**定义 4.4 (柯西列)**), 故 $\phi\left(x_n\right)\to{}u\in\left[1,\infty\right)$; 由 $\phi^{-1}$ 连续, $x_n=\phi^{-1}\left(\phi\left(x_n\right)\right)\to\phi^{-1}\left(u\right)\in\left(0,1\right]$, 且 $\delta\left(x_n,\phi^{-1}\left(u\right)\right)=\left|\phi\left(x_n\right)-u\right|\to0$. 故 $\left(\left(0,1\right],\delta\right)$ 完备.

$\blacksquare$
