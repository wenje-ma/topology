# week4

> **定义 1.3 (闭集)**
> 
> 称 $F\subset{}X$ 是闭集, 若 $X-F$ 是开集. (讲义第 1 讲, p10)

> **定义 2.3 (凸集)**
> 
> 称 $K\subset\mathbb{R}^n$ 凸, 若 $K$ 中任意两点之间的连线段含于 $K$; 凸集对凸组合封闭, 即 $\sum_i\lambda_ix_i\in{}K$ 只要 $x_i\in{}K$, $\lambda_i\ge0$, $\sum_i\lambda_i=1$. (讲义第 2 讲, p16)

> **命题 3.6 ($\mathbb{R}^n$ 中的紧集)**
> 
> $\mathbb{R}^n$ 的子集紧当且仅当它闭且有界. (讲义第 3 讲, p10)

> **定理 4.3 (度量空间中紧与序列紧)**
> 
> 度量空间紧当且仅当每个序列都有收敛子列. (讲义第 4 讲, p4)

## 4.1 (无界闭凸集含一条从原点出发的半直线)

考虑 $\mathbb{R}^2$ 中的闭集 $A$. 假设 $A$ 是凸集, 原点 $O\in{}A$, 且 $A$ 不是有界的.

(1) 证明对任意正整数 $p\ge1$, 存在点 $M_p\in{}A$, 线段 $OM_p$ 属于 $A$, 且其长度 $\left|OM_p\right|\ge{}p$;

(2) 记线段 $OM_p$ 与单位圆周的交点为 $u_p$. 证明存在 $\left\{u_p\right\}_{p\ge1}$ 的子列收敛到单位圆周上的某一点 $u$;

(3) 证明 $A$ 包含一条从原点出发的长度无穷的半直线.

2024 年卷 B 题三.

### 解答 4.1

(1) 因 $A$ 无界, 对每个 $p$ 存在 $M_p\in{}A$ 使 $\left|M_p\right|\ge{}p$. 由**定义 2.3 (凸集)**, $O$ 与 $M_p$ 的连线线段含于 $A$, 其长度即 $\left|M_p\right|\ge{}p$.

$\blacksquare$

(2) 令 $u_p=\frac{M_p}{\left|M_p\right|}$, 它满足 $\left|u_p\right|=1$, 落在单位圆周 $S^1$ 上. $S^1$ 闭且有界, 由**命题 3.6 ($\mathbb{R}^n$ 中的紧集)** 紧, 由**定理 4.3 (度量空间中紧与序列紧)** 序列紧, 故 $\left\{u_p\right\}$ 有子列 $u_{p_j}\to{}u$, 且 $\left|u\right|=1$.

$\blacksquare$

(3) 记 $r_p=\left|M_p\right|\ge{}p$. 固定 $\lambda\ge0$. 对充分大的 $j$ 有 $r_{p_j}\ge\lambda$, 由**定义 2.3 (凸集)**,

$$
\lambda{}u_{p_j}=\frac{\lambda}{r_{p_j}}M_{p_j}+\left(1-\frac{\lambda}{r_{p_j}}\right)O
$$

是 $M_{p_j}$ 与 $O$ 的凸组合, 属于 $A$. 由第 (2) 小题 $u_{p_j}\to{}u$, 故 $\lambda{}u_{p_j}\to\lambda{}u$. 若 $\lambda{}u\notin{}A$, 由**定义 1.3 (闭集)** $A$ 闭故 $\mathbb{R}^2-A$ 开, 它含有 $\lambda{}u$ 的一个开球, 而 $\lambda{}u_{p_j}$ 对充分大的 $j$ 落在此球内, 矛盾. 故 $\lambda{}u\in{}A$. 由 $\lambda\ge0$ 任意, 半直线 $\left\{\lambda{}u:\lambda\ge0\right\}$ 含于 $A$.

$\blacksquare$
