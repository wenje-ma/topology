# week11

> **定义 4.4 (柯西列)**
> 
> 度量空间中的序列 $\left\{x_i\right\}$ 称为柯西列, 若 $\lim_{i,j\to\infty}d\left(x_i,x_j\right)=0$. (讲义第 4 讲, p6)

> **定义 4.5 (完备度量空间)**
> 
> 每个柯西列都收敛 (极限属于该空间) 的度量空间称为完备的. (讲义第 4 讲, p6)

## 11.1 (绝对收敛级数与完备性)

考虑一个赋范线性空间 $E$. 称 $E$ 中的级数 $\sum_{n\ge0}u_n$ 绝对收敛, 如果实级数 $\sum_{n\ge0}\left|u_n\right|$ 收敛.

(1) 证明如果 $E$ 是完备的, 那么所有绝对收敛的级数 $\sum_{n\ge0}u_n$ 都是收敛的;

(2) 现在不假设 $E$ 是完备的, 但假设 $E$ 中所有绝对收敛级数都是收敛的. 设 $S_n$ 是 $E$ 中的柯西列. 证明可以用归纳法找出 $\phi\left(1\right)<\phi\left(2\right)<\cdots$ 使得 $\forall{}n\ge\phi\left(k\right)$, $\left|S_n-S_{\phi\left(k\right)}\right|<2^{-k}$;

(3) 定义 $u_k=S_{\phi\left(k+1\right)}-S_{\phi\left(k\right)}$, 证明在第 (2) 小题的条件下 $E$ 是完备的.

2024 年卷 A 题二.

### 解答 11.1

(1) 记部分和 $S_n=\sum_{k=0}^{n}u_k$. 设 $\sum_k\left|u_k\right|$ 收敛, 则对任意 $\epsilon>0$ 存在 $N$ 使 $m>n\ge{}N$ 时 $\sum_{k=n+1}^{m}\left|u_k\right|<\epsilon$. 由三角不等式,

$$
\left|S_m-S_n\right|=\left|\sum_{k=n+1}^{m}u_k\right|\le\sum_{k=n+1}^{m}\left|u_k\right|<\epsilon,
$$

故 $\left\{S_n\right\}$ 是柯西列 (**定义 4.4 (柯西列)**), 由 $E$ 完备 (**定义 4.5 (完备度量空间)**) 它收敛, 即级数收敛.

$\blacksquare$

(2) 记 $N_k$ 为使得 $n,m\ge{}N_k$ 时 $\left|S_n-S_m\right|<2^{-\left(k+1\right)}$ 的整数, 它存在因 $\left\{S_n\right\}$ 柯西 (**定义 4.4 (柯西列)**). 令 $\phi\left(1\right)=N_1$, 并归纳地令

$$
\phi\left(k+1\right)=\max\left\{\phi\left(k\right)+1,N_{k+1}\right\},
$$

则 $\phi$ 严格递增且 $\phi\left(k\right)\ge{}N_k$ 对一切 $k$ 成立. 于是对 $n\ge\phi\left(k\right)$, 下标 $n$ 与 $\phi\left(k\right)$ 都不小于 $N_k$, 故

$$
\left|S_n-S_{\phi\left(k\right)}\right|<2^{-\left(k+1\right)}<2^{-k}.
$$

$\blacksquare$

(3) 由第 (2) 小题 $\left|u_k\right|=\left|S_{\phi\left(k+1\right)}-S_{\phi\left(k\right)}\right|<2^{-k}$, 故 $\sum_k\left|u_k\right|\le\sum_k2^{-k}<+\infty$, 即 $\sum_ku_k$ 绝对收敛. 由假设 $\sum_ku_k$ 收敛, 其部分和

$$
\sum_{k=1}^{m}u_k=S_{\phi\left(m+1\right)}-S_{\phi\left(1\right)}
$$

收敛, 故子列 $S_{\phi\left(m\right)}$ 收敛到某 $S\in{}E$.

设 $\epsilon>0$, 取 $K$ 使 $2^{-K}<\frac{\epsilon}{2}$ 且 $m\ge{}K$ 时 $\left|S_{\phi\left(m\right)}-S\right|<\frac{\epsilon}{2}$. 对 $n\ge\phi\left(K\right)$,

$$
\left|S_n-S\right|\le\left|S_n-S_{\phi\left(K\right)}\right|+\left|S_{\phi\left(K\right)}-S\right|<2^{-K}+\frac{\epsilon}{2}<\epsilon,
$$

故 $S_n\to{}S$. 于是 $E$ 中每个柯西列收敛, 由**定义 4.5 (完备度量空间)** $E$ 完备.

$\blacksquare$
