# week1

> **定义 1.2 (拓扑空间)**
> 
> 集合 $X$ 配上一族开集 $\mathcal{O}\subset\mathcal{P}\left(X\right)$ 称为拓扑空间, 要求: (1) $\emptyset,X\in\mathcal{O}$; (2) 任意 $U,V\in\mathcal{O}$ 有 $U\cap{}V\in\mathcal{O}$; (3) 任意 $\mathcal{A}\subset\mathcal{O}$ 有 $\bigcup\mathcal{A}\in\mathcal{O}$. (讲义第 1 讲, p9)

> **定义 1.3 (闭集)**
> 
> 称 $F\subset{}X$ 是闭集, 若 $X-F$ 是开集. (讲义第 1 讲, p10)

> **定义 1.6 (拓扑基)**
>
> 一族子集 $\mathcal{B}$ 称为 $X$ 上某拓扑的基, 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $x\in{}X$ 与 $B_1,B_2\in\mathcal{B}$ 满足 $x\in{}B_1\cap{}B_2$, 存在 $B_3\in\mathcal{B}$ 使 $x\in{}B_3\subset{}B_1\cap{}B_2$; 该拓扑的开集恰为 $\mathcal{B}$ 中元素之并. (讲义第 1 讲, p12)

> **定理 1.7 (基判据)**
> 
> $\mathcal{B}$ 是拓扑 $\mathcal{O}$ 的基当且仅当 $\mathcal{B}\subset\mathcal{O}$, 且对任意 $O\in\mathcal{O}$ 与 $x\in{}O$ 存在 $B\in\mathcal{B}$ 使 $x\in{}B\subset{}O$. (讲义第 1 讲, p13)

## 1.1 (富斯滕贝格拓扑: 基, 既开又闭集与素数无穷)

考虑整数组成的空间 $\mathbb{Z}$. 在这个空间上定义一个拓扑, 称为富斯滕贝格拓扑. 这个拓扑的一组基是所有非平凡的双边无穷长等差数列

$$
S\left(a,b\right)=a\mathbb{Z}+b=\left\{an+b:n\in\mathbb{Z}\right\},
$$

其中要求 $a\neq0$.

(0) 证明上面给出的集合 $S\left(a,b\right)$ 的确能构成某个拓扑的基. 证明 $\mathbb{Z}$ 的子集是开集当且仅当该子集是空集, $\mathbb{Z}$, 或者是一些上述集合 $S\left(a,b\right)$ 的并;

(1) 证明 $\mathbb{Z}$ 的子集 $U$ 是开集当且仅当对任意 $U$ 中的元素 $x$, 都存在 $a\neq0$ 使得 $S\left(a,x\right)\subset{}U$;

(2) 证明任何一个非平凡的集合 $S\left(a,b\right)$ ($a\neq0$) 都是既开又闭的;

(3) 证明 $\mathbb{Z}$ 的非空有限子集不可能是开集;

(4) 证明如果 $P$ 是所有 $\mathbb{Z}$ 中质数组成的集合, 那么 $\mathbb{Z}\setminus\{\pm1\}=\bigcup_{p\in{}P}S\left(p,0\right)$;

(5) 证明 $\mathbb{Z}$ 中的质数有无穷多个.

2025 年卷 A 题一.

### 解答 1.1

(0) 依据**定义 1.6 (拓扑基)**, $\mathbb{Z}=S\left(1,0\right)$; 定义 $S_1=S\left(a_1,b_1\right)$, $S_2=S\left(a_2,b_2\right)$, 令 $x\in{}S_1\cap{}S_2$. 而 $S_1\cap{}S_2$ 是两个数列的交, 仍是一个数列, 故可令 $S_3=S_1\cap{}S_2$, 即 $x\in{}S_3$, $S$ 确实是富斯滕贝格拓扑的基. $\blacksquare$ 因为全集, 空集即开又闭, 且依据 **定义 1.6 (拓扑基)**, $\mathbb{Z}$ 的子集是开集当且仅当该子集是 $S\left(a,b\right)$ 的并. $\blacksquare$

(1) ($\Rightarrow$) 已知 $U$ 开, $x\in{}U$. 由**定理 1.7 (基判据)**, 存在基元素 $S\left(a,b\right)$ 使 $x\in{}S\left(a,b\right)\subset{}U$, 进而有 $S\left(a,x\right)\subset{}U$. $\blacksquare$ ($\Leftarrow$) 已知任意的 $x\in{}U$, 都存在 $a\ne0$ 使得 $S\left(a,x\right)\subset{}U$. 对每个 $x\in{}U$ 取 $a_x$ 使 $S\left(a_x,x\right)\subset{}U$. 由于 $U=\bigcup_{x\in{}U}x$, 则 $U=\bigcup_{x\in{}U}S\left(a_x,x\right)$. 由**定义 1.6 (拓扑基)** $U$ 开. $\blacksquare$

(2) 由**定义 1.6 (拓扑基)**, $S\left(a,b\right)$ 开. $\blacksquare$ 由于 $\mathbb{Z}=\bigcup_{b=0}^{a-1}S(a,b)$, 则 $\mathbb{Z}$ 去掉一个 $S(a,b)$ 后, 剩余的仍然是 $S$ 的并, 故仍开. 由**定义 1.3 (闭集)**, $S\left(a,b\right)$ 闭, 故既开又闭. $\blacksquare$

(3) 由 (1), $U$ 是开集当且仅当对任意 $U$ 中的元素 $x$, 都存在 $a\neq0$ 使得 $S\left(a,x\right)\subset{}U$, $S$ 是无限集故 $U$ 必是无限集. 故非空有限开集有限, 不可能是开集. $\blacksquare$

(4) 由于任意的 $\mathbb{Z}\setminus\{\pm1\}$ 都有质因数分解, 因此 $\mathbb{Z}\setminus\{\pm1\}=\bigcup_{p\in{}P}S\left(p,0\right)$. $\blacksquare$

(5) 由 (2) 知 $S(p,0)$ 既开又闭. 反设 $P$ 只有有限个, 则 $\bigcap_{p\in{}P}S(p,0)$ 既开又闭. 由 (4) 知 $\bigcap_{p\in{}P}S(p,0)=\mathbb{Z}\setminus\{\pm1\}$, 则 $\mathbb{Z}\setminus\{\pm1\}$ 既开又闭, $\{\pm1\}$ 既开又闭, 而由 (3), 开集不可能有限, 故 $\{\pm1\}$ 不开, 矛盾. $\blacksquare$
