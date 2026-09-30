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

(4) 证明如果 $P$ 是所有 $\mathbb{Z}$ 中质数组成的集合, 那么 $\mathbb{Z}-\left\{-1,1\right\}=\bigcup_{p\in{}P}S\left(p,0\right)$;

(5) 证明 $\mathbb{Z}$ 中的质数有无穷多个.

2025 年卷 A 题一.

### 解答 1.1

(0) 先验基条件. 覆盖: $S\left(1,0\right)=\mathbb{Z}$, 故 $\mathbb{Z}=\bigcup_{a\neq0,b\in\mathbb{Z}}S\left(a,b\right)$. 加细: 设 $x\in{}S\left(a,b\right)\cap{}S\left(c,d\right)$, 令 $e=\operatorname{lcm}\left(a,c\right)$. 因 $x\in{}S\left(a,b\right)$, 有 $a\mid{}x-b$; 取 $y=x+en$, 则 $a\mid{}en$ 故 $a\mid{}y-b$, 即 $y\in{}S\left(a,b\right)$; 同理由 $c\mid{}en$ 得 $y\in{}S\left(c,d\right)$. 于是

$$
x\in{}S\left(e,x\right)\subset{}S\left(a,b\right)\cap{}S\left(c,d\right).
$$

由**定义 1.6 (拓扑基)**, $\mathcal{B}=\left\{S\left(a,b\right):a\neq0\right\}$ 生成 $\mathbb{Z}$ 上的拓扑, 其开集恰为 $\mathcal{B}$ 中元素之并与空集; 而 $\mathbb{Z}=S\left(1,0\right)$ 本身就是基元素. 由**定义 1.2 (拓扑空间)**, 这族开集满足拓扑三公理: $\emptyset$ 与 $\mathbb{Z}$ 分别为空并与基元素, 有限交的封闭性由加细条件给出, 任意并的封闭性由生成方式给出. 故开集是空集, $\mathbb{Z}$ 或若干 $S\left(a,b\right)$ 之并.

$\blacksquare$

(1) 设 $U$ 开, $x\in{}U$. 由**定理 1.7 (基判据)**, 存在基元素 $S\left(a,b\right)$ 使 $x\in{}S\left(a,b\right)\subset{}U$. 由 $x\in{}S\left(a,b\right)$ 得 $a\mid{}x-b$, 故 $S\left(a,b\right)=S\left(a,x\right)$, 于是 $S\left(a,x\right)\subset{}U$.

反之设 $U$ 满足题设. 对每个 $x\in{}U$ 取 $a_x$ 使 $S\left(a_x,x\right)\subset{}U$, 则

$$
U=\bigcup_{x\in{}U}S\left(a_x,x\right)
$$

是基元素之并, 由**定义 1.6 (拓扑基)** $U$ 开.

$\blacksquare$

(2) $S\left(a,b\right)$ 是基元素, 由**定义 1.6 (拓扑基)** 开. 记 $a>0$ ($a<0$ 时换 $|a|$, 因 $S\left(a,b\right)=S\left(-a,b\right)$). 模 $a$ 的剩余类给出 $\mathbb{Z}$ 的不交分解 $\mathbb{Z}=\bigcup_{r=0}^{a-1}S\left(a,r\right)$, 而 $S\left(a,b\right)=S\left(a,r_0\right)$, 其中 $r_0$ 是 $b$ 模 $a$ 的余数. 故

$$
\mathbb{Z}-S\left(a,b\right)=\bigcup_{r\neq{}r_0}S\left(a,r\right)
$$

是基元素之并, 由**定义 1.6 (拓扑基)** 开. 由**定义 1.3 (闭集)**, $S\left(a,b\right)$ 闭, 故既开又闭.

$\blacksquare$

(3) 设 $F$ 非空有限且开, 取 $x\in{}F$. 由第 (1) 小题, 存在 $a\neq0$ 使 $S\left(a,x\right)\subset{}F$. 因 $a\neq0$, 映射 $n\mapsto{}an+x$ 是单射, 故 $S\left(a,x\right)$ 无限, 与 $F$ 有限矛盾.

$\blacksquare$

(4) 设 $n\in\mathbb{Z}$, $n\neq\pm1$. 若 $n=0$, 则 $n=p\cdot0\in{}S\left(p,0\right)$ 对任意素数 $p$ 成立. 若 $|n|\ge2$, 则 $n$ 有素因子 $p$, 即 $n\in{}S\left(p,0\right)$. 故 $\mathbb{Z}-\left\{-1,1\right\}\subset\bigcup_{p\in{}P}S\left(p,0\right)$. 反之 $S\left(p,0\right)$ 的元素都是 $p$ 的倍数, 不为 $\pm1$, 故 $\bigcup_{p\in{}P}S\left(p,0\right)\subset\mathbb{Z}-\left\{-1,1\right\}$.

$\blacksquare$

(5) 反设 $P$ 有限, 记为 $p_1,\dots,p_k$, 令 $N=p_1\cdots{}p_k$. 对每个整数 $n\ge1$, 数 $Nn+1\ge2$, 故 $Nn+1\neq\pm1$, 由第 (4) 小题存在 $i$ 使 $Nn+1\in{}S\left(p_i,0\right)$, 即 $p_i\mid{}Nn+1$. 但 $p_i\mid{}N$, 故 $p_i\mid1$, 矛盾. 故 $P$ 无限.

$\blacksquare$
