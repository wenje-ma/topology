# week6

> **定义 1.3 (闭集)**
> 
> 称 $F\subset{}X$ 是闭集, 若 $X-F$ 是开集. (讲义第 1 讲, p10)

> **命题 1.4 (闭集的运算)**
> 
> 闭集族的任意交闭, 有限并闭; 开集族的任意并开, 有限交开. (讲义第 1 讲, p10)

> **定义 1.5 (粗细, 平凡拓扑与离散拓扑)**
> 
> 若 $\mathcal{O}\subset\mathcal{O}'$, 称 $\mathcal{O}'$ 比 $\mathcal{O}$ 细. 只有 $\emptyset,X$ 开的是平凡拓扑, 所有子集都开的是离散拓扑. (讲义第 1 讲, p11)

> **定义 1.8 (连续映射)**
> 
> 称 $f:X\to{}Y$ 连续, 若对任意开集 $U\subset{}Y$, 原像 $f^{-1}\left(U\right)$ 是 $X$ 中的开集. (讲义第 1 讲, p14)

> **命题 1.16 (乘积拓扑的刻画)**
> 
> $X\times{}Y$ 上的乘积拓扑以 $U\times{}V$ 为基 ($U,V$ 各自开); 它是使两个投影都连续的最粗拓扑. 映射 $z\mapsto\left(f_1\left(z\right),f_2\left(z\right)\right)$ 连续当且仅当两个分量都连续. 任意乘积 $\prod_{i\in{}I}X_i$ 同理, 其基是有限个坐标的非平凡开集之积 (柱集). (讲义第 1 讲, p25)

> **定义 3.1 (开覆盖与紧致)**
> 
> $X$ 的开覆盖是一族开集 $\left\{U_i\right\}$ 使 $\bigcup_iU_i=X$; 若从中能取出有限个仍覆盖 $X$, 称它有有限子覆盖. 每个开覆盖都有有限子覆盖的空间称为紧致空间. (讲义第 3 讲, p2)

> **定理 3.5 (有限交性质)**
> 
> 设 $X$ 紧, $\mathcal{F}$ 是 $X$ 的一族闭子集, 且其中任意有限个交非空, 则 $\bigcap_{F\in\mathcal{F}}F$ 非空. (讲义第 3 讲, p9)

> **定理 3.8 (吉洪诺夫定理)**
> 
> 任意一族紧空间的乘积在乘积拓扑下紧. (讲义第 3 讲, p16)

## 6.1 (德布鲁因-埃尔德什定理)

考虑无向图 $G$, 顶点集 $V$, 边集 $E$; $E$ 中元素记为 $\left(x,y\right)=\left(y,x\right)$ ($x,y\in{}V$), 两个顶点也可以不被边连接. 称 $G$ 为有限图, 若 $E$ 有限. 称 $\widetilde{G}=\left(\widetilde{V},\widetilde{E}\right)$ 是 $G=\left(V,E\right)$ 的子图, 若 $\widetilde{V}=V$ 且 $\widetilde{E}\subset{}E$ (只删边). 称 $f:V\to\left\{1,\dots,k\right\}$ 是 $G$ 的 $k$ 染色, 若对任意边 $\left(x,y\right)\in{}E$ 有 $f\left(x\right)\neq{}f\left(y\right)$; 存在这样的 $f$ 时称 $G$ 可 $k$ 染色.

(0) 考虑 $\left\{1,\dots,k\right\}$ 上的离散拓扑. 证明在这个拓扑下 $\left\{1,\dots,k\right\}$ 紧致;

(1) 给定图 $G$. 记 $X$ 为所有从 $V$ 到 $\left\{1,\dots,k\right\}$ 的函数之集. 证明 $X=\left\{1,\dots,k\right\}^{\left|V\right|}$, 且若 $\left\{1,\dots,k\right\}$ 赋离散拓扑, 则 $X$ 在乘积拓扑下紧致;

(2) 对 $F\subset{}E$ 记 $X_F=\left\{f:V\to\left\{1,\dots,k\right\}:f\text{ 是子图 }\left(V,F\right)\text{ 的 }k\text{ 染色}\right\}$. 证明若 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 则 $X_F$ 闭;

(3) 证明对任意 $F\subset{}E$, $X_F$ 都闭;

(4) 设 $G$ 的所有有限子图都可 $k$ 染色, $\mathcal{F}=\left\{X_F:F\subset{}E\text{ 有限}\right\}$. 证明 $\mathcal{F}$ 中有限个元素之交非空, 再证明 $\mathcal{F}$ 中所有元素之交非空;

(5) 证明德布鲁因-埃尔德什定理: 若 $G$ 的任意有限子图都可 $k$ 染色, 则 $G$ 可 $k$ 染色.

2025 年卷 B 题一.

### 解答 6.1

(0) 设 $\left\{U_i\right\}$ 是 $\left\{1,\dots,k\right\}$ 的开覆盖. 由**定义 1.5 (粗细, 平凡拓扑与离散拓扑)**, 每个单点 $\left\{j\right\}$ 是开集且属于某个 $U_{i_j}$, 故 $\left\{U_{i_j}:j=1,\dots,k\right\}$ 是有限子覆盖. 由**定义 3.1 (开覆盖与紧致)** 空间紧致.

$\blacksquare$

(1) 函数 $f:V\to\left\{1,\dots,k\right\}$ 就是给每个顶点指定一个值, 故 $X=\prod_{v\in{}V}\left\{1,\dots,k\right\}=\left\{1,\dots,k\right\}^{\left|V\right|}$. 由第 (0) 小题每个因子紧, 由**定理 3.8 (吉洪诺夫定理)** $X$ 在乘积拓扑下紧.

$\blacksquare$

(2) 一条边 $\left(x,y\right)$ 的染色条件即 $f\left(x\right)\neq{}f\left(y\right)$, 故

$$
X_F=\bigcup_{i\neq{}j}\left(\pi_x^{-1}\left(\left\{i\right\}\right)\cap\pi_y^{-1}\left(\left\{j\right\}\right)\right).
$$

由**命题 1.16 (乘积拓扑的刻画)**, 投影 $\pi_x,\pi_y$ 连续; 由**定义 1.5 (粗细, 平凡拓扑与离散拓扑)**, 单点 $\left\{i\right\}$ 在离散拓扑下闭, 而连续映射下闭集的原像闭 (**定义 1.8 (连续映射)** 与**定义 1.3 (闭集)**: 原像把补集映为补集的原像). 故每个 $\pi_x^{-1}\left(\left\{i\right\}\right)\cap\pi_y^{-1}\left(\left\{j\right\}\right)$ 闭, 由**命题 1.4 (闭集的运算)** 它们的有限并闭, 即 $X_F$ 闭.

$\blacksquare$

(3) 一个函数是 $\left(V,F\right)$ 的染色当且仅当它对 $F$ 中每条边都合法, 故

$$
X_F=\bigcap_{e\in{}F}X_{\left\{e\right\}}.
$$

由第 (2) 小题每个 $X_{\left\{e\right\}}$ 闭, 由**命题 1.4 (闭集的运算)** 任意交闭, 故 $X_F$ 闭.

$\blacksquare$

(4) 设 $F_1,\dots,F_l\subset{}E$ 有限. 由染色条件逐条叠加,

$$
\bigcap_{i=1}^{l}X_{F_i}=X_{\bigcup_iF_i}.
$$

边集 $\bigcup_iF_i$ 有限, 其子图 $\left(V,\bigcup_iF_i\right)$ 由假设可 $k$ 染色, 故 $X_{\bigcup_iF_i}\neq\emptyset$.

再由**定理 3.5 (有限交性质)**: $X$ 紧 (第 (1) 小题), 每个 $X_F$ 闭 (第 (3) 小题), 且有限交非空, 故 $\bigcap_{F}X_F$ 非空.

$\blacksquare$

(5) 取 $f\in\bigcap_{F\subset{}E}X_F$, 其中 $F$ 取遍有限子集. 对任一 $e=\left(x,y\right)\in{}E$, 取 $F=\left\{e\right\}$, 则 $f\in{}X_F$, 故 $f\left(x\right)\neq{}f\left(y\right)$. 于是 $f$ 是 $G$ 的 $k$ 染色, $G$ 可 $k$ 染色.

$\blacksquare$
