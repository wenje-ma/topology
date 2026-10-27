# week8

> **基础知识: 拉格朗日中值定理**<br>若 $f$ 在 $\left[a,b\right]$ 上连续且在 $\left(a,b\right)$ 上可微, 则存在 $\xi\in\left(a,b\right)$ 使 $f\left(b\right)-f\left(a\right)=f'\left(\xi\right)\left(b-a\right)$; 特别地, 若 $\left|f'\right|\le M$, 则 $\left|f\left(x\right)-f\left(r\right)\right|\le M\left|x-r\right|$.

> **定义 3.10 (豪斯多夫空间)**<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.21 (闭集)**<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$, p13)

> **定义 3.25 (邻域与极限)**<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$, p16)

> **定义 3.32 (稠密)**<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定理 5.2 (区间紧)**<br>区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**<br>若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **定理 5.8 ($\mathbb R^n$ 紧集判据)**<br>$F\subset\mathbb R^n$ 紧当且仅当 $F$ 闭且有界. (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.7 (连续函数的一致极限连续)**<br>连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **定理 6.8 ($C\left(X,Y\right)$ 完备)**<br>$Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.12 (阿尔泽拉-阿斯科利定理)**<br>设 $K$ 为紧度量空间, $F\subset C\left(K\right)$ 为等度连续且一致有界的函数族, 则 $F$ 是紧的. (教材 $\S6$)

> **定义 6.35 (度量空间)**<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.36 (开球)**<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)< r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37 (柯西列)**<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j> N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.39 (完备化)**<br>任意度量空间可自然嵌入一个完备度量空间; 实数轴 $\mathbb R$ 是有理数集的完备化, 故 $\mathbb R$ 完备. (教材 $\S6$)

> **定义 6.41 (一致收敛与一致度量)**<br>$d\left(f,g\right)=\sup_X\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛当且仅当 $d\left(f_n,g\right)\to0$. (教材 $\S6$)

> **定义 6.43 (上确界度量)**<br>紧集 $K$ 上连续函数空间 $C\left(K\right)$ 装备 $d\left(f,g\right)=\sup_{x\in K}\left|f\left(x\right)-g\left(x\right)\right|$, 即上确界范数诱导的度量. (教材 $\S6$)

> **定义 6.44 (伪距离)**<br>满足除 "$d\left(x,y\right)=0\Rightarrow x=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 $\S1.3$)

> **定义 6.46 (点到集合的距离)**<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.47 ($\varepsilon$-邻域)**<br>$U_\varepsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)< \varepsilon\right\}$. (题集 $\S3.2$)

> **定义 6.48 (豪斯多夫距离)**<br>$d\left(A,B\right)=\inf\left\{r> 0:A\subset U_r\left(B\right),\,B\subset U_r\left(A\right)\right\}$; 在紧子集族 $\mathcal K\left(X\right)$ 上是真度量. (题集 $\S3.2$)

---

## 习题一

设 $\left(X,d\right)$ 是度量空间. 证明朴素定义 $d\left(A,B\right)=\inf_{a\in A,\,b\in B}d\left(a,b\right)$ 一般不是度量.

### 解答 习题一

在 $\mathbb R^2$ (配通常欧氏距离) 中取

$$
A=\left\{\left(x,0\right):x\in\mathbb R\right\},\quad B=\left\{\left(n,1/n\right):n\in\mathbb Z_{> 0}\right\}.
$$

由**定义 6.46 (点到集合的距离)**,

$$
d\left(A,B\right)\le d\left(\left(n,0\right),\left(n,1/n\right)\right)=1/n\to0,
$$

故 $d\left(A,B\right)=0$, 但 $A\neq B$. 这不满足**定义 6.35 (度量空间)** 中"距离为零蕴含两点相等"的公理 (应用于集合时即两集合相等). 故该朴素定义一般不是度量. $\blacksquare$

> 这给出了我们需要定义豪斯多夫距离的一个原因.

---

## 习题二

定义集合 $A\subset X$ 的 $\varepsilon$-邻域 $U_\varepsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)< \varepsilon\right\}$, 其中 $d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. 证明: 对 $r_1,r_2> 0$ 与任意 $A\subset X$,

$$
U_{r_1}\left(U_{r_2}\left(A\right)\right)\subset U_{r_1+r_2}\left(A\right),
$$

但反过来一般不成立.

### 解答 习题二

设 $x\in U_{r_1}\left(U_{r_2}\left(A\right)\right)$. 由**定义 6.47 ($\varepsilon$-邻域)**, 存在 $y\in U_{r_2}\left(A\right)$ 使 $d\left(x,y\right)< r_1$; 再由**定义 6.46 (点到集合的距离)**, 存在 $a\in A$ 使 $d\left(y,a\right)< r_2$. 由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x,a\right)\le d\left(x,y\right)+d\left(y,a\right)< r_1+r_2.
$$

故 $x\in U_{r_1+r_2}\left(A\right)$, 包含关系成立.

反之不真. 取 $X=\left\{0,1,3\right\}$ 赋通常距离, $A=\left\{0,3\right\}$, $r_1=r_2=1$. 由**定义 6.46 (点到集合的距离)** 与**定义 6.47 ($\varepsilon$-邻域)**, $d\left(1,A\right)=1$, 故

$$
U_1\left(A\right)=\left\{x:d\left(x,A\right)< 1\right\}=\left\{0,3\right\},
$$

从而 $U_1\left(U_1\left(A\right)\right)=\left\{0,3\right\}$. 但 $d\left(1,A\right)=1< 2$, 故 $1\in U_2\left(A\right)$. 因此 $U_{r_1+r_2}\left(A\right)\not\subset U_{r_1}\left(U_{r_2}\left(A\right)\right)$. $\blacksquare$

> 不可逆的原因正是因为邻域是严格小于, 这导致三角不等式变成了严格成立.

---

## 习题三

定义子集 $A,B\subset X$ 之间的豪斯多夫距离

$$
d_H\left(A,B\right)=\inf\left\{r> 0:A\subset U_r\left(B\right),\,B\subset U_r\left(A\right)\right\}.
$$

证明豪斯多夫距离是伪距离, 即满足度量的全部公理, 只是 $d_H\left(A,B\right)=0$ 不一定蕴含 $A=B$.

### 解答 习题三

由**定义 6.48 (豪斯多夫距离)**, 非负性与对称性是显然的 (定义关于 $A,B$ 对称). 又 $d_H\left(A,A\right)=0$, 因为对任意 $r> 0$, $A\subset U_r\left(A\right)$ 恒成立.

剩证三角不等式. 设 $A,B,C\subset X$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,B\right)< r$ 意味着 $A\subset U_r\left(B\right)$ 且 $B\subset U_r\left(A\right)$. 若 $A\subset U_r\left(B\right)$ 且 $B\subset U_s\left(C\right)$, 由**习题二**的包含关系 (**定义 6.47 ($\varepsilon$-邻域)**),

$$
A\subset U_r\left(B\right)\subset U_r\left(U_s\left(C\right)\right)\subset U_{r+s}\left(C\right).
$$

同理 $C\subset U_{r+s}\left(A\right)$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,C\right)\le r+s$. 令 $r\downarrow d_H\left(A,B\right)$, $s\downarrow d_H\left(B,C\right)$, 即得三角不等式

$$
d_H\left(A,C\right)\le d_H\left(A,B\right)+d_H\left(B,C\right).
$$

由**定义 6.44 (伪距离)**, 它满足除"距离为零蕴含相等"外全部公理, 故是伪距离. $\blacksquare$

> $d_H\left(A,B\right)=0\not\Rightarrow A=B$: 取 $A=\left(0,1\right)$, $B=\left[0,1\right]$, $d_H\left(A,B\right)=0$ 但 $A\ne B$.

---

## 习题四

证明: 对一切 $A\subset X$, $d_H\left(A,A\right)=0$. 若 $A,B$ 闭, 则 $d_H\left(A,B\right)=0$ 蕴含 $A=B$.

### 解答 习题四

现设 $A,B$ 闭且 $d_H\left(A,B\right)=0$. 任取 $a\in A$. 对每个 $n$, 由**定义 6.48 (豪斯多夫距离)** 与 $d_H\left(A,B\right)=0$, 存在 $b_n\in B$ 使 $d_H\left(a,b_n\right)< 1/n$. 于是 $b_n\to a$. 由**定义 3.21 (闭集)**, 闭集含其中序列的极限, 故 $a\in B$. 这证明 $A\subset B$. 交换 $A,B$ 同理得 $B\subset A$, 故 $A=B$. $\blacksquare$

---

## 习题五

证明: 若把豪斯多夫距离限制在紧子集族 $\mathcal K\left(X\right)$ 上, 则它是 $\mathcal K\left(X\right)$ 上的真度量.

### 解答 习题五

由**习题三**, $d_H$ 是伪距离, 已满足非负性, 对称性与三角不等式. 剩证分离性. 设 $A,B\in\mathcal K\left(X\right)$ 紧致且 $d_H\left(A,B\right)=0$. 度量空间是**定义 3.10 (豪斯多夫空间)**, 由**定理 5.5 (豪斯多夫中紧集闭)**, 紧集 $A,B$ 在 $X$ 中闭. 由**习题四**的结论, $d_H\left(A,B\right)=0$ 且 $A,B$ 闭蕴含 $A=B$. 故分离性成立. $\blacksquare$

---

## 习题六

(2024 年卷 B 题目二) 在 $\left(0,\infty\right)$ 上定义 $\delta\left(x,y\right)=\left|\frac1x-\frac1y\right|$.

(1) 证明 $\delta$ 是 $\left(0,\infty\right)$ 上的度量;

(2) 证明 $\delta$ 诱导通常拓扑;

(3) 证明 $\left(\left(0,\infty\right),\delta\right)$ 不完备;

(4) 证明 $\left(\left(0,1\right],\delta\right)$ 完备.

### 解答 习题六

**(1)** 令 $\varphi\left(x\right)=1/x$, 则 $\delta\left(x,y\right)=\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$ 由绝对值诱导, 满足**定义 6.35 (度量空间)** 的全部四条公理.

**(2)** $\varphi:\left(0,\infty\right)\to\left(0,\infty\right)$ 在通常拓扑下是同胚 (连续双射, 逆 $x\mapsto1/x$ 连续). $\delta$ 是 $\varphi$ 拉回的通常距离, 故诱导通常拓扑.

**(3)** 取 $x_n=n$. 则 $\delta\left(x_n,x_m\right)=\left|1/n-1/m\right|\to0$, 是**定义 6.37 (柯西列)**; 但若收敛于 $x\in\left(0,\infty\right)$, 则 $\delta\left(x_n,x\right)\to\left|0-1/x\right|=1/x> 0$, 矛盾. 故它不收敛, $\left(\left(0,\infty\right),\delta\right)$ 不是**定义 6.38 (完备度量空间)**.

**(4)** 设 $x_n\in\left(0,1\right]$ 是 $\delta$-柯西列. 则 $1/x_n\in\left[1,\infty\right)$ 通常柯西, 由**定义 6.39 (完备化)** (即 $\mathbb R$ 完备), $1/x_n\to L\ge1$. 令 $x=1/L\in\left(0,1\right]$, 则 $\delta\left(x_n,x\right)\to0$. 故 $\left(\left(0,1\right],\delta\right)$ 完备. $\blacksquare$

---

## 习题七

设 $E=\mathbb R^n$ 装备通常拓扑, $K$ 是 $E$ 中的紧集, $F$ 是 $E$ 中的闭集.

(1) 证明存在 $x\in K$ 与 $y\in F$ 使 $d\left(K,F\right)=d\left(x,y\right)$, 其中 $d\left(K,F\right)=\inf_{x\in K,\,y\in F}d\left(x,y\right)$;

(2) 举例说明把 $E$ 换成 $l^\infty$ 后结论不成立. 可考虑 $F=\left\{\left(1+2^{-n}\right)e_n\right\}_{n\ge0}$, 其中 $e_n$ 是第 $n$ 位为 $1$ 其余为 $0$ 的序列.

### 解答 习题七

**(1)** 由**定义 6.46 (点到集合的距离)**, $d\left(K,F\right)=\inf_{x\in K,\,y\in F}\left\|x-y\right\|$. 取序列 $x_n\in K$, $y_n\in F$ 使 $\left\|x_n-y_n\right\|\to d\left(K,F\right)$. 由**定理 6.1 (紧 $=$ 序列紧)**, $K$ 紧故 $\left(x_n\right)$ 有收敛子列 $x_{n_j}\to x\in K$. 此时 $\left\|y_{n_j}\right\|\le\left\|y_{n_j}-x_{n_j}\right\|+\left\|x_{n_j}-x\right\|+\left\|x\right\|$ 有界, 故 $y_{n_j}$ 落在某个闭球内; 由**定理 5.8 ($\mathbb R^n$ 紧集判据)** 该闭球闭且有界故紧, 再由**定理 6.1 (紧 $=$ 序列紧)** 抽出子列 $y_{n_{j_k}}\to y$. 因 $F$ 闭, 由**定义 3.21 (闭集)** $y\in F$. 取极限得

$$
\left\|x-y\right\|=\lim_{k\to\infty}\left\|x_{n_{j_k}}-y_{n_{j_k}}\right\|=d\left(K,F\right).
$$

即距离在 $x\in K$, $y\in F$ 处取得.

**(2)** 令 $E=l^\infty$, 范数 $\left\|a\right\|=\sup_n\left|a_n\right|$. 取紧集 $K=\left\{0\right\}$ 与闭集 $F=\left\{y_n=\left(1+2^{-n}\right)e_n:n\ge0\right\}$. 先验证 $F$ 闭: 对 $n\neq m$,

$$
\left\|y_n-y_m\right\|=\max\left(1+2^{-n},1+2^{-m}\right)\ge1,
$$

故 $\left(y_n\right)$ 不是**定义 6.37 (柯西列)**, 其中任何子列都不收敛; 度量空间中集合闭当且仅当它包含自身一切收敛序列的极限, 由**定义 3.21 (闭集)** $F$ 是闭集. 而

$$
d\left(K,F\right)=\inf_n\left\|y_n\right\|=\inf_n\left(1+2^{-n}\right)=1,
$$

且该下确界是 $n\to\infty$ 时的极限, 没有任何 $y_n$ 满足 $\left\|y_n\right\|=1$ (均严格大于 $1$). 故距离 $d\left(K,F\right)=1$ 不能在某对 $x\in K$, $y\in F$ 处取得. $\blacksquare$

---

## 习题八

这是**定理 6.12 (阿尔泽拉-阿斯科利定理)** 的一个婴儿版本. 设 $M\ge0$, $\left(f_n\right)$ 是 $\left[0,1\right]$ 上的连续可微函数列, 满足 $\left|f_n\left(x\right)\right|+\left|f_n'\left(x\right)\right|\le M$ 对一切 $x\in\left[0,1\right]$. 证明存在 $\left(f_n\right)$ 的子列在 $\left[0,1\right]$ 上一致收敛.

(1) 用对角线论证证明 $\left(f_n\right)$ 有子列在 $\left[0,1\right]$ 的全体有理点处逐点收敛;

(2) 记该子列为 $\left(g_n\right)$, 用 $\varepsilon/3$ 论证证明 $\left(g_n\right)$ 在 $\left[0,1\right]$ 的每一点都逐点收敛;

(3) 记上一问中的逐点极限为 $g$, 再用 $\varepsilon/3$ 论证证明 $g$ 实际上是 $\left(g_n\right)$ 在 $\left[0,1\right]$ 上的一致极限.

### 解答 习题八

**(1)** 设 $\left\{r_1,r_2,\dots\right\}$ 是 $\left[0,1\right]$ 中全体有理数. 固定 $k$, 数列 $\left(f_n\left(r_k\right)\right)_{n\ge1}$ 有界: $\left|f_n\left(r_k\right)\right|\le M$. 由**定理 5.2 (区间紧)**, 有界闭区间 $\left[-M,M\right]$ 紧, 再由**定理 6.1 (紧 $=$ 序列紧)**, $\left(f_n\left(r_1\right)\right)$ 有收敛子列 $\left(f_{n_i^{\left(1\right)}}\left(r_1\right)\right)$. 接着在该子列内取子列使 $\left(f_n\left(r_2\right)\right)$ 收敛; 如此归纳, 得一串嵌套子列 $\left(f_{n_i^{\left(k\right)}}\right)$ 使第 $k$ 个子列在 $r_1,\dots,r_k$ 处都收敛. 对角线子列 $g_i=f_{n_i^{\left(i\right)}}$ 是每个嵌套子列的尾部, 故在每个有理点 $r_k$ 处收敛.

**(2)** 固定 $x\in\left[0,1\right]$ 与 $\varepsilon> 0$. 由 $\left|g_n'\left(t\right)\right|\le M$ 与**基础知识: 拉格朗日中值定理**, $\left|g_n\left(x\right)-g_n\left(r\right)\right|\le M\left|x-r\right|$. 取有理点 $r$ 使 $\left|x-r\right|< \varepsilon/\left(3M\right)$. 则

$$
\left|g_n\left(x\right)-g_m\left(x\right)\right|\le\left|g_n\left(x\right)-g_n\left(r\right)\right|+\left|g_n\left(r\right)-g_m\left(r\right)\right|+\left|g_m\left(r\right)-g_m\left(x\right)\right|.
$$

由有理点处收敛, $\left(g_n\left(r\right)\right)$ 是**定义 6.37 (柯西列)**, 对充分大的 $n,m$ 中间项 $< \varepsilon/3$; 两端各 $< \varepsilon/3$. 故 $\left|g_n\left(x\right)-g_m\left(x\right)\right|< \varepsilon$, 即 $\left(g_n\left(x\right)\right)$ 是柯西列. 由**定义 6.39 (完备化)** (即 $\mathbb R$ 完备), 逐点极限 $g\left(x\right)$ 存在.

**(3)** 由**定理 5.2 (区间紧)** 与**定理 6.1 (紧 $=$ 序列紧)**, $\left[0,1\right]$ 可被有限个有理点 $r^{\left(1\right)},\dots,r^{\left(L\right)}$ 的邻域覆盖, 使每个 $x$ 到某 $r^{\left(j\right)}$ 的距离 $< \varepsilon/\left(3M\right)$. 对这有限个有理点, 由收敛性可取公共的 $N$, 使 $n\ge N$ 时 $\left|g_n\left(r^{\left(j\right)}\right)-g\left(r^{\left(j\right)}\right)\right|< \varepsilon/3$ 对一切 $j$ 成立. 又由 $\left|g_n'\right|\le M$ 取极限得 $\left|g\left(x\right)-g\left(r^{\left(j\right)}\right)\right|\le M\left|x-r^{\left(j\right)}\right|< \varepsilon/3$. 于是对任意 $x$,

$$
\left|g_n\left(x\right)-g\left(x\right)\right|\le\left|g_n\left(x\right)-g_n\left(r^{\left(j\right)}\right)\right|+\left|g_n\left(r^{\left(j\right)}\right)-g\left(r^{\left(j\right)}\right)\right|+\left|g\left(r^{\left(j\right)}\right)-g\left(x\right)\right|< \varepsilon.
$$

由**定义 6.41 (一致收敛与一致度量)**, $g_n$ 一致收敛到 $g$. $\blacksquare$

---

## 习题九

第一部分是对角线论证. 设 $f_n\left(m\right)$ 是正整数上的函数列, 一致有界, 即存在常数 $C$ 使对一切 $n,m$ 有 $\left|f_n\left(m\right)\right|\le C$. 证明序列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 有收敛子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$.

### 解答 习题九

数列 $\left(f_n\left(1\right)\right)_{n\ge0}$ 含于有界闭区间 $\left[-C,C\right]$. 由**定理 5.2 (区间紧)** 平移即知 $\left[-C,C\right]$ 是紧集; 由**定理 6.1 (紧 $=$ 序列紧)**, 紧度量空间中每个序列都有收敛子列. 故存在子列 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)_{i\ge0}$ 收敛. $\blacksquare$

---

## 习题十

沿用习题一的记号. 证明可以依次构造子列 $\left(f_{n_i^{\left(k\right)}}\left(m\right)\right)_{i\ge0}$, 使 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛.

### 解答 习题十

归纳构造. $k=1$ 时由**习题九**已得子列 $\left(f_{n_i^{\left(1\right)}}\right)$, 使 $\left(f_{n_i^{\left(1\right)}}\left(1\right)\right)$ 收敛. 设已构造第 $k$ 个子列 $\left(f_{n_i^{\left(k\right)}}\right)$. 数列 $\left(f_{n_i^{\left(k\right)}}\left(k+1\right)\right)_{i\ge0}$ 仍含于 $\left[-C,C\right]$, 由**定理 5.2 (区间紧)** 与**定理 6.1 (紧 $=$ 序列紧)**, 有收敛子列, 记为 $\left(f_{n_i^{\left(k+1\right)}}\left(k+1\right)\right)_{i\ge0}$, 其中 $\left(n_i^{\left(k+1\right)}\right)$ 是 $\left(n_i^{\left(k\right)}\right)$ 的子列. 于是 $\left(f_{n_i^{\left(k+1\right)}}\right)$ 是 $\left(f_{n_i^{\left(k\right)}}\right)$ 的子列, 且由构造 $\left(f_{n_i^{\left(k\right)}}\left(k\right)\right)_{i\ge0}$ 收敛. 归纳完成. $\blacksquare$

---

## 习题十一

证明存在子列 $\left(f_{n_i}\left(m\right)\right)$, 使对每个固定的 $m$, $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 当 $i\to\infty$ 时收敛. 可考虑序列 $n_k=n_k^{\left(k\right)}$.

### 解答 习题十一

取对角子列 $n_i=n_i^{\left(i\right)}$. 固定 $m$. 对一切 $i\ge m$, 由嵌套关系, $\left(n_j^{\left(i\right)}\right)_{j\ge1}$ 是 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 的子列, 特别地 $n_i=n_i^{\left(i\right)}$ 本身是第 $m$ 个子列 $\left(n_j^{\left(m\right)}\right)_{j\ge1}$ 中序号充分大的一项. 而由构造, $\left(f_{n_j^{\left(m\right)}}\left(m\right)\right)_{j\ge1}$ 收敛. 收敛序列的尾部仍收敛, 故子列 $\left(f_{n_i}\left(m\right)\right)_{i\ge m}$ 收敛, 即 $\left(f_{n_i}\left(m\right)\right)_{i\ge0}$ 收敛. 对一切 $m$ 同时成立. $\blacksquare$

---

## 习题十二

第二部分是 $\varepsilon/3$ 论证. 设 $C\left[a,b\right]$ 是 $\left[a,b\right]$ 上连续实值函数空间, 装备**定义 6.43 (上确界度量)** $d\left(f,g\right)=\sup_{x\in\left[a,b\right]}\left|f\left(x\right)-g\left(x\right)\right|$. 设 $\left(f_n\right)$ 是该度量下的**定义 6.37 (柯西列)**. 证明对每个 $x\in\left[a,b\right]$, $\left(f_n\left(x\right)\right)$ 收敛到某个 $f\left(x\right)\in\mathbb R$.

### 解答 习题十二

由 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon> 0$ 存在 $N$, 使 $n,m\ge N$ 时

$$
\sup_{x\in\left[a,b\right]}\left|f_n\left(x\right)-f_m\left(x\right)\right|< \varepsilon.
$$

固定 $x\in\left[a,b\right]$, 则 $\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\sup< \varepsilon$, 故 $\left(f_n\left(x\right)\right)$ 是 $\mathbb R$ 中的**定义 6.37 (柯西列)**. 由**定义 6.39 (完备化)**, $\mathbb R$ 是**定义 6.38 (完备度量空间)**, 故 $\left(f_n\left(x\right)\right)$ 收敛. 记其极限为 $f\left(x\right)$. 逐点极限 $f$ 由此定义. $\blacksquare$

---

## 习题十三

设 $f$ 是连续函数列 $\left(f_n\right)$ 的极限. 固定 $x\in\left[a,b\right]$ 与 $\varepsilon> 0$. 证明可选取 $n$ 使 $\left\|f_n-f\right\|_\infty< \varepsilon/3$; 证明可选取 $\delta> 0$, 使 $\left|x-y\right|< \delta$ 蕴含 $\left|f_n\left(x\right)-f_n\left(y\right)\right|< \varepsilon/3$; 由此证明 $f$ 连续.

### 解答 习题十三

由**习题十二**, $\left(f_n\right)$ 逐点收敛到 $f$. 又 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon> 0$ 存在 $N$, 使 $n,m\ge N$ 时 $\sup_x\left|f_n\left(x\right)-f_m\left(x\right)\right|< \varepsilon/3$. 固定 $n\ge N$, 令 $m\to\infty$, 由**习题十二** $f_m\left(x\right)\to f\left(x\right)$, 故

$$
\left|f_n\left(x\right)-f\left(x\right)\right|=\lim_{m\to\infty}\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\varepsilon/3.
$$

对 $x$ 取上确界得 $\left\|f_n-f\right\|_\infty\le\varepsilon/3< \varepsilon/3$ (取严格不等号即可). 故存在 $n$ 使 $\left\|f_n-f\right\|_\infty< \varepsilon/3$.

固定该 $n$, 由 $f_n$ 连续, 存在 $\delta> 0$, 使 $y\in\left[a,b\right]$ 且 $\left|x-y\right|< \delta$ 时 $\left|f_n\left(x\right)-f_n\left(y\right)\right|< \varepsilon/3$.

第三步, 对满足 $\left|x-y\right|< \delta$ 的 $y$,

$$
\left|f\left(x\right)-f\left(y\right)\right|\le\left|f\left(x\right)-f_n\left(x\right)\right|+\left|f_n\left(x\right)-f_n\left(y\right)\right|+\left|f_n\left(y\right)-f\left(y\right)\right|< \frac{\varepsilon}{3}+\frac{\varepsilon}{3}+\frac{\varepsilon}{3}=\varepsilon.
$$

这正是**定理 6.7 (连续函数的一致极限连续)** 的 $\varepsilon/3$ 论证, 故 $f$ 在 $x$ 连续. $x$ 任意, $f$ 在 $\left[a,b\right]$ 上连续. $\blacksquare$

---

## 习题十四

证明 $f_n\to f$ 在 $C\left[a,b\right]$ 中, 即依**定义 6.43 (上确界度量)** 收敛; 由此得出 $C\left[a,b\right]$ 是完备的.

### 解答 习题十四

由**习题十二**, $\left(f_n\right)$ 逐点收敛到 $f$. 由 $\left(f_n\right)$ 是**定义 6.37 (柯西列)**, 对任意 $\varepsilon> 0$ 存在 $N$, 使 $n,m\ge N$ 时 $\sup_x\left|f_n\left(x\right)-f_m\left(x\right)\right|< \varepsilon$. 固定 $n\ge N$ 与任意 $x$, 令 $m\to\infty$, 由**习题十二** $f_m\left(x\right)\to f\left(x\right)$, 故

$$
\left|f_n\left(x\right)-f\left(x\right)\right|=\lim_{m\to\infty}\left|f_n\left(x\right)-f_m\left(x\right)\right|\le\varepsilon.
$$

对 $x$ 取上确界, 得 $\left\|f_n-f\right\|_\infty\le\varepsilon$ 对一切 $n\ge N$ 成立. 由**定义 6.41 (一致收敛与一致度量)** 与**定义 6.43 (上确界度量)**, $f_n\to f$ 一致收敛, 即在 $C\left[a,b\right]$ 中收敛.

由**习题十三**, $f$ 连续, 故 $f\in C\left[a,b\right]$. 于是 $C\left[a,b\right]$ 中每个**定义 6.37 (柯西列)** 都收敛到 $C\left[a,b\right]$ 中的元素, 由**定义 6.38 (完备度量空间)**, $C\left[a,b\right]$ 完备, 即**定理 6.8 ($C\left(X,Y\right)$ 完备)** 的特例. $\blacksquare$

---

## 习题十五

序列与度量空间. 证明: **定义 3.10 (豪斯多夫空间)** 中序列的极限唯一. 证明: 在**定义 6.35 (度量空间)** 中, 序列的聚点就是其子列极限. 若空间不是度量空间, 会发生什么?

### 解答 习题十五

极限唯一: 设 $x_n\to x$ 且 $x_n\to y$, $x\neq y$. 由**定义 3.10 (豪斯多夫空间)**, 存在不相交开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.25 (邻域与极限)**, 对充分大的 $n$ 有 $x_n\in U$, 又对充分大的 $n$ 有 $x_n\in V$, 与 $U\cap V=\emptyset$ 矛盾. 故 $x=y$.

聚点即子列极限: 在**定义 6.35 (度量空间)** 中, 设 $x$ 是 $\left(x_n\right)$ 的聚点, 即 $x$ 的每个邻域含序列中无穷多项. 归纳地选 $n_k$ 严格递增, 使 $x_{n_k}\in B\left(x,1/k\right)$; 由**定义 6.36 (开球)**, $d\left(x_{n_k},x\right)< 1/k\to0$, 故 $x_{n_k}\to x$. 反之, 若 $x_{n_k}\to x$, 由**定义 3.25 (邻域与极限)**, $x$ 的每个邻域含无穷多项, $x$ 是聚点.

若不是度量空间: 豪斯多夫性仍保证极限唯一, 但聚点一般不再是子列极限, 因为没有可数邻域基把"每个邻域含无穷多项"逐步收窄成一个子列; 此时需要用网来刻画聚点. $\blacksquare$

---

## 习题十六

恰一个聚点. 设 $f:\mathbb R^n\to\mathbb R^n$ 连续, 且序列 $\left(f^n\left(x_0\right)\right)$ 恰有一个聚点. 证明该序列收敛.

### 解答 习题十六

记 $x_n=f^n\left(x_0\right)$, 设唯一聚点为 $z$. 取子列 $x_{n_j}\to z$. 由 $f$ 连续, $x_{n_j+1}=f\left(x_{n_j}\right)\to f\left(z\right)$. 而 $\left(x_{n_j+1}\right)$ 是 $\left(x_n\right)$ 的子列, 其极限 $f\left(z\right)$ 必为聚点, 由唯一性 $f\left(z\right)=z$.

反设 $\left(x_n\right)$ 不收敛到 $z$. 则存在 $\varepsilon> 0$ 与无穷多个 $n$ 使 $\left\|x_n-z\right\|\ge\varepsilon$. 从每个 $n_j$ 出发, 若其后轨道始终在 $B\left(z,\varepsilon\right)$ 内, 则尾部落在紧闭球中, 由**定理 5.8 ($\mathbb R^n$ 紧集判据)** 与**定理 6.1 (紧 $=$ 序列紧)**, 该尾部的任何聚点都是 $z$, 矛盾于不收敛. 故从每个 $n_j$ 出发, 存在第一个 $m_j> n_j$ 使 $\left\|x_{m_j}-z\right\|=\varepsilon$. 点 $x_{m_j}$ 都落在紧球面 $\partial B\left(z,\varepsilon\right)$ 上, 抽子列 $x_{m_{j_k}}\to w$, $\left\|w-z\right\|=\varepsilon$. 则 $w$ 是 $\left(x_n\right)$ 的聚点且 $w\neq z$, 矛盾. 故 $\left(x_n\right)\to z$. $\blacksquare$

---

## 习题十七

闭集之和. 设 $E=\mathbb R^n$, $A,B\subset E$.

(1) 证明: 若 $A$ 紧而 $B$ 闭, 则 $A+B=\left\{a+b:a\in A,b\in B\right\}$ 闭;

(2) 证明: 若 $A,B$ 都闭, $A+B$ 不必闭.

### 解答 习题十七

**(1)** 取序列 $a_n+b_n\in A+B$ 收敛到 $y$. 由**定理 6.1 (紧 $=$ 序列紧)**, $A$ 紧, 故 $\left(a_n\right)$ 有子列 $a_{n_j}\to a\in A$. 则 $b_{n_j}=\left(a_{n_j}+b_{n_j}\right)-a_{n_j}\to y-a$. 因 $B$ 闭, 由**定义 3.21 (闭集)**, $y-a\in B$. 故 $y=a+\left(y-a\right)\in A+B$. $A+B$ 含一切收敛序列的极限, 故闭.

**(2)** 反例: 取 $A=\left\{\left(x,0\right):x\in\mathbb R\right\}$, $B=\left\{\left(x,1/x\right):x> 0\right\}$. $A$ 与 $B$ 都闭. 但

$$
A+B=\left\{\left(x+t,1/t\right):t> 0\right\}=\left\{\left(u,v\right):v> 0\right\},
$$

即开的上半平面, 由**定义 3.21 (闭集)** 它不是闭集. $\blacksquare$

---

## 习题十八

(完备化) 设 $\left(M,d\right)$ 不完备. 考虑全体柯西列 $\left\{x_n\right\}$, 等价关系 $\left\{x_n\right\}\sim\left\{y_n\right\}$ 当且仅当 $\lim_{n\to\infty}d\left(x_n,y_n\right)=0$. 令 $\widehat M$ 为等价类集合, 距离 $\widehat d\left(\left[x\right],\left[y\right]\right)=\lim_{n\to\infty}d\left(x_n,y_n\right)$. 证明 $\widehat M$ 完备, 且 $M$ 在嵌入 $x\mapsto\left(x,x,\dots\right)$ 下在 $\widehat M$ 中稠密.

### 解答 习题十八

$\widehat d$ 适定: 若 $\left[x_n\right]=\left[x_n'\right]$, $\left[y_n\right]=\left[y_n'\right]$, 则 $d\left(x_n,y_n\right)-d\left(x_n',y_n'\right)$ 由三角不等式趋于 $0$, 极限与代表元无关. 由**定义 6.35 (度量空间)**, $\widehat d$ 满足四公理. 这里等价关系中出现的 $\left\{x_n\right\}$ 是**定义 6.37 (柯西列)** 意义下的柯西列.

**完备**: 设 $\left\{\xi_k\right\}$ 是 $\widehat M$ 中柯西列, $\xi_k=\left[\left(x_n^{\left(k\right)}\right)_n\right]$. 对每个 $k$, 取代表列使其前 $k$ 项稳定逼近; 对角化取 $z_k=x_k^{\left(k\right)}$. 由柯西性与三角不等式, $\left(z_k\right)$ 是 $M$ 中柯西列, 记其等价类为 $\xi$. 则 $\xi_k\to\xi$. 由**定义 6.38 (完备度量空间)**, $\widehat M$ 完备.

**稠密嵌入**: 映射 $i:M\to\widehat M$, $i\left(x\right)=\left[\left(x,x,\dots\right)\right]$. 任意 $\xi=\left[\left(x_n\right)\right]\in\widehat M$, $x_n\to\xi$ 在 $\widehat M$ 中, 而 $x_n\in i\left(M\right)$. 故 $i\left(M\right)$ 的闭包为全空间, 由**定义 3.32 (稠密)** $M$ 在 $\widehat M$ 中稠密. 由**定义 6.39 (完备化)**, 这就是 $M$ 的完备化. $\blacksquare$
