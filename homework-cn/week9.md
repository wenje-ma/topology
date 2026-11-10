# week9

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 4.17 (不动点)**
> 
> $f:X\to{X}$ 的不动点是满足 $f\left(x\right)=x$ 的点 $x\in{X}$. (题集 §7.2)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $x,y\in{K}$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.3 ($\mathbb{R}^n$ 中的紧集)**
> 
> $K\subset\mathbb{R}^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.7))

> **定理 5.10 (有限交判据)**
> 
> $X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定义 5.16 (紧致空间)**
> 
> 称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.17 (有限交性质)**
> 
> 闭集族 $\mathcal{F}$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.3 (紧度量空间完备)**
> 
> 紧度量空间是完备度量空间. (教材 §6)

> **定理 6.16 (巴拿赫不动点定理)**
> 
> 非空完备度量空间上的压缩映射有唯一不动点. (题集 §4.3 Q1)

> **定理 6.17 (里茨定理)**
> 
> 无穷维赋范线性空间的闭单位球非紧 (不能被有限个半径 $1$ 的开球覆盖). (题集 $\S7.1$)

> **定理 6.18 (蒂茨-乌雷松扩张定理)**
> 
> 度量空间闭子集 $A$ 上的连续有界函数可保持上确界与下确界地扩张到全空间. (题集 $\S7.1$)

> **定义 6.19 (压缩映射)**
> 
> 称 $f:X\to{X}$ 是压缩的, 若存在 $0<{}k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. (题集 §4.3 Q1)

> **定义 6.20 (赋范线性空间)**
> 
> 向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.35 (度量空间)**
> 
> 度量 $d:X\times{X}\to\mathbb{R}_{\ge0}$ 满足:
> 
> (1) $d\left(x,x\right)=0$;
> 
> (2) 若 $d\left(x,y\right)=0$ 则 $x=y$;
> 
> (3) $d\left(x,y\right)=d\left(y,x\right)$;
> 
> (4) $d\left(x,y\right)\le{d}\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$ 由此给出度量拓扑)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.44 (伪距离)**
> 
> 满足除 "$d\left(x,y\right)=0\Rightarrow{x}=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 §1.3; 题集 §3.2 Q3; 题集 §5 Q5)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.47 ($\varepsilon$-邻域)**
> 
> $U_\varepsilon\left(A\right)=\left\{x\in{X}:d\left(x,A\right)<\varepsilon\right\}$. (题集 $\S3.2$)

> **定义 6.48 (豪斯多夫距离)**
> 
> $d\left(A,B\right)=\inf\left\{r>0:A\subset{U}_r\left(B\right),B\subset{U}_r\left(A\right)\right\}$; 在紧子集族 $\mathcal{K}\left(X\right)$ 上是真度量. (题集 $\S3.2$)

> **定义 6.49 (等距映射)**
> 
> 满足 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)$ 的映射 $f:X\to{Y}$. (题集 §3.4)

> **说明 6.50 (度量空间是豪斯多夫的)**
> 
> 度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

## 9.1 (序列收敛等价于唯一子列极限 (附两个子列极限的轨道))
(两个子列极限) 设 $K$ 是某**定义 6.20 (赋范线性空间)** 的紧子空间.

(1) 证明 $K$ 中序列收敛当且仅当它只有唯一子列极限;

(2) 设 $f:K\to{K}$ 连续, $x\in{K}$, 序列 $f^n\left(x\right)$ 恰有两个子列极限 $z_0,z_1$. 证明: 对 $z_0,z_1$ 的任意邻域 $V_0,V_1$, 序列最终落入 $V_0\cup{V}_1$; 并证明 $f\left(z_0\right)=z_1$, $f\left(z_1\right)=z_0$, 且 $f^{2k}\left(x\right)$ 与 $f^{2k+1}\left(x\right)$ 分别收敛到 $z_0,z_1$.

题集 §3.5 C9.

### 解答 9.1

(1) ($\Rightarrow$) 显然. ($\Leftarrow$) 设唯一子列极限为 $L$. 若序列不收敛到 $L$, 则存在 $\varepsilon>0$ 与子列恒在 $B\left(L,\varepsilon\right)$ 外; 由**定理 6.1 (紧 $=$ 序列紧)**, 该子列有收敛子列, 其极限异于 $L$, 矛盾. 故序列收敛到 $L$.

(2) 若序列不最终落入 $V_0\cup{V}_1$, 则有子列恒在 $V_0\cup{V}_1$ 外; 由紧性它有收敛子列, 其极限不在 $V_0\cup{V}_1$ 中, 即第三个子列极限, 矛盾.

$f$ 连续, 把子列极限映为序列 $f^{n+1}\left(x\right)$ 的子列极限, 而后者的子列极限集同为 $\left\{z_0,z_1\right\}$. 故 $f\left(z_0\right),f\left(z_1\right)\in\left\{z_0,z_1\right\}$. 若 $f\left(z_0\right)=z_0$, 则偶子列将只有一个子列极限, 与第 (1) 小题矛盾; 故 $f\left(z_0\right)=z_1$, 同理 $f\left(z_1\right)=z_0$. 于是 $f^{2k}\left(x\right)$ 恰在 $z_0$ 附近累积, $f^{2k+1}\left(x\right)$ 恰在 $z_1$ 附近累积, 由第 (1) 小题分别收敛到 $z_0,z_1$. $\blacksquare$

## 9.2 (紧度量空间中不减距离的连续自映射是等距且双射)
设 $E$ 是紧度量空间, $f:E\to{E}$ 连续, 且对一切 $x,y\in{E}$ 满足 $d\left(f\left(x\right),f\left(y\right)\right)\ge{d}\left(x,y\right)$.

(1) 证明 $f$ 实际上是**定义 6.49 (等距映射)**, 即 $d\left(f\left(x\right),f\left(y\right)\right)=d\left(x,y\right)$;

(2) 证明 $f$ 是双射. 可考虑 $\left(x_n,y_n\right)=\left(f^n\left(x\right),f^n\left(y\right)\right)$ 的子列;

(3) 最后证明: 若 $g:E\to{E}$ 是连续双射且 $d\left(g\left(x\right),g\left(y\right)\right)\le{d}\left(x,y\right)$ 对一切 $x,y$ 成立, 则 $g$ 也是**定义 6.49 (等距映射)**.

题集 §4.4 Q2.

### 解答 9.2

(1) 固定 $x,y\in{E}$, 记 $a_n=d\left(f^n\left(x\right),f^n\left(y\right)\right)$. 由条件应用于 $\left(f^{n-1}\left(x\right),f^{n-1}\left(y\right)\right)$, $a_{n+1}\ge{a}_n$, 又 $a_n\le\operatorname{diam}\left(E\right)$, 故 $a_n\uparrow{L}$. 由**定理 6.1 (紧 $=$ 序列紧)**, $E\times{E}$ 紧, $\left(f^n\left(x\right),f^n\left(y\right)\right)$ 有子列 $\left(f^{n_j}\left(x\right),f^{n_j}\left(y\right)\right)\to\left(u,v\right)$, 于是 $d\left(u,v\right)=L$. 因 $a_{n_j}\to{L}$ 且 $a_{n_j+1}\to{L}$, 由三角不等式

$$
\left|a_{n_j+1}-a_{n_j}\right|\le{d}\left(f^{n_j+1}\left(x\right),f^{n_j}\left(x\right)\right)+d\left(f^{n_j+1}\left(y\right),f^{n_j}\left(y\right)\right).
$$

左端趋于 $0$, 故 $d\left(f^{n_j+1}\left(x\right),f^{n_j}\left(x\right)\right)\to0$ 且 $d\left(f^{n_j+1}\left(y\right),f^{n_j}\left(y\right)\right)\to0$. 由 $f$ 连续, $f\left(f^{n_j}\left(x\right)\right)=f^{n_j+1}\left(x\right)\to{f}\left(u\right)$; 而它也 $\to{u}$, 故 $f\left(u\right)=u$. 同理 $f\left(v\right)=v$.

由条件应用于 $\left(x,u\right)$: $d\left(f^{n_j}\left(x\right),f^{n_j}\left(u\right)\right)\ge{d}\left(x,u\right)$, 即 $d\left(f^{n_j}\left(x\right),u\right)\ge{d}\left(x,u\right)$. 令 $j\to\infty$ 得 $0\ge{d}\left(x,u\right)$, 故 $u=x$. 同理 $v=y$. 于是 $L=d\left(u,v\right)=d\left(x,y\right)=a_0$, 而 $a_n$ 从 $a_0$ 起不减且收敛到 $a_0$, 故 $a_1=a_0$, 即 $d\left(f\left(x\right),f\left(y\right)\right)=d\left(x,y\right)$. 由**定义 6.49 (等距映射)**, $f$ 是等距.

(2) 反设 $f$ 不满, 取 $p\notin{f}\left(E\right)$. 由**定理 5.1 (紧空间连续像紧)**, $f\left(E\right)$ 紧; 度量空间是**说明 6.50 (度量空间是豪斯多夫的)**, 由**定理 5.5 (豪斯多夫中紧集闭)**, $f\left(E\right)$ 闭. 由**定义 6.46 (点到集合的距离)**, $\delta=d\left(p,f\left(E\right)\right)>0$. 轨道 $p,f\left(p\right),f^2\left(p\right),\dots$ 满足

$$
d\left(f^{n+1}\left(p\right),f^n\left(p\right)\right)\ge{d}\left(f^n\left(p\right),f^{n-1}\left(p\right)\right)\ge\cdots\ge{d}\left(f\left(p\right),p\right)\ge\delta,
$$

其中最后一步用 $f\left(p\right)\in{f}\left(E\right)$ 而 $p\notin{f}\left(E\right)$. 但由**定理 6.1 (紧 $=$ 序列紧)**, 紧度量空间 $E$ 中序列 $\left(f^n\left(p\right)\right)$ 有收敛子列, 而收敛子列必是**定义 6.37 (柯西列)**, 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. 结合第 (1) 小题的等距性, $d\left(f\left(x\right),f\left(y\right)\right)=0$ 推出 $d\left(x,y\right)=0$ 即 $x=y$, $f$ 单射. 故 $f$ 双射.

(3) $E$ 紧且是**说明 6.50 (度量空间是豪斯多夫的)**, $g$ 是紧豪斯多夫空间之间的连续双射, 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $g^{-1}$ 连续. 条件 $d\left(g\left(x\right),g\left(y\right)\right)\le{d}\left(x,y\right)$ 改写为: 对任意 $u,v\in{E}$, 令 $u=g\left(x\right)$, $v=g\left(y\right)$, 则 $d\left(g^{-1}\left(u\right),g^{-1}\left(v\right)\right)\ge{d}\left(u,v\right)$. 即 $g^{-1}$ 是紧度量空间上连续且距离不减的映射. 由第 (1) 小题, $g^{-1}$ 是**定义 6.49 (等距映射)**, 从而 $g$ 也是等距. $\blacksquare$

## 9.3 (紧集的 $\varepsilon$-分离集基数有界)
等距与紧性. 设 $K\subset\mathbb{R}^n$ 是非空紧集, $\varepsilon>0$. 称 $A\subset{K}$ 是 $\varepsilon$-分离的, 若 $x\neq{y}$ 蕴含 $\left|x-y\right|>\varepsilon$. 证明存在有限数 $M\left(\varepsilon\right)$, 使 $K$ 中任何 $\varepsilon$-分离集的基数不超过 $M\left(\varepsilon\right)$. 再证明: 若 $f:K\to{K}$ 是**定义 6.49 (等距映射)**, 则 $f$ 满.

题集 §4.5 C8.

### 解答 9.3

反设存在任意大的 $\varepsilon$-分离集. 则可取两两不同的点列 $x_m\in{K}$ 使 $m\neq{m}'$ 时 $\left|x_m-x_{m'}\right|>\varepsilon$. 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 与**定理 6.1 (紧 $=$ 序列紧)**, $\left(x_m\right)$ 有收敛子列; 收敛子列是**定义 6.37 (柯西列)**, 充分靠后两项距离 $<\varepsilon$, 与 $\varepsilon$-分离矛盾. 故存在 $M\left(\varepsilon\right)$.

满性: 反设 $f$ 不满, 取 $p\notin{f}\left(K\right)$. $f\left(K\right)$ 紧, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 闭, 故 $\delta=d\left(p,f\left(K\right)\right)>0$. 轨道 $p,f\left(p\right),f^2\left(p\right),\dots$ 满足

$$
\left|f^{n+1}\left(p\right)-f^n\left(p\right)\right|=\left|f\left(f^n\left(p\right)\right)-f\left(f^{n-1}\left(p\right)\right)\right|=\left|f^n\left(p\right)-f^{n-1}\left(p\right)\right|\ge\cdots\ge\left|f\left(p\right)-p\right|\ge\delta,
$$

其中等号用了**定义 6.49 (等距映射)**. 但由**定理 6.1 (紧 $=$ 序列紧)**, $K$ 中轨道有收敛子列, 必为**定义 6.37 (柯西列)**, 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. $\blacksquare$

## 9.4 (紧性三题: 局部单射的扩张, 里茨定理与蒂茨–乌雷松扩张)

(1) 设 $\left(E,d\right)$ 是度量空间, $f:E\to\mathbb{R}$ 连续, $K\subset{E}$ 紧. 假设 $f$ 在 $K$ 上单射, 且对每个 $x\in{K}$ 存在 $\varepsilon>0$ 使 $f$ 在 $B\left(x,\varepsilon\right)$ 上单射. 证明存在含 $K$ 的开集 $\Omega$ 使 $f$ 在 $\Omega$ 上单射.

(2) (里茨定理) 设 $E$ 是实无穷维赋范线性空间. 证明 $E$ 的闭单位球不能被有限个半径 $1$ 的开球覆盖.

(3) (蒂茨-乌雷松扩张定理) 设 $\left(E,d\right)$ 是度量空间, $A\subset{E}$ 闭, $f:A\to\mathbb{R}$ 连续有界. 证明存在连续 $g:E\to\mathbb{R}$, $g\big|_A=f$, 且

$$
\sup_{x\in{E}}g\left(x\right)=\sup_{x\in{A}}f\left(x\right),\quad
\inf_{x\in{E}}g\left(x\right)=\inf_{x\in{A}}f\left(x\right).
$$

题集 §7.1 (三题).

### 解答 9.4

第 (1) 小题: 对 $n\ge1$, 定义 $K_n=\left\{x\in{E}:d\left(x,K\right)<1/n\right\}$. 每个 $K_n$ 是开集且含 $K$. 反证: 若对每个 $n$, $f$ 在 $K_n$ 上不单射, 则存在 $x_n,y_n\in{K}_n$, $x_n\neq{y}_n$, 使 $f\left(x_n\right)=f\left(y_n\right)$. 由 $x_n,y_n\in{K}_n$, 可取 $x'_n,y'_n\in{K}$ 使 $d\left(x_n,x'_n\right)<1/n$, $d\left(y_n,y'_n\right)<1/n$. 由**定义 5.16 (紧致空间)**, $K\times{K}$ 紧; 由**定理 6.1 (紧 $=$ 序列紧)**, 存在子列 $\left(x'_{\varphi\left(n\right)},y'_{\varphi\left(n\right)}\right)\to\left(x,y\right)\in{K}\times{K}$. 由三角不等式, $x_{\varphi\left(n\right)}\to{x}$, $y_{\varphi\left(n\right)}\to{y}$. 由 $f$ 连续, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$ 取极限得 $f\left(x\right)=f\left(y\right)$. 因 $f$ 在 $K$ 上单射, $x=y$. 但由假设, $x$ 有邻域 $B\left(x,\varepsilon\right)$ 使 $f$ 单射, 而 $x_{\varphi\left(n\right)}\neq{y}_{\varphi\left(n\right)}$ 且当 $n$ 充分大时二者都在 $B\left(x,\varepsilon\right)$ 内, $f\left(x_{\varphi\left(n\right)}\right)=f\left(y_{\varphi\left(n\right)}\right)$, 矛盾. 故存在 $n$ 使 $f$ 在 $K_n$ 上单射, 取 $\Omega=K_n$ 即可.

第 (2) 小题: 反证. 设闭单位球 $\overline{B}\left(0,1\right)$ 被开单位球 $B\left(x_i,1\right)$ ($i=1,\dots,m$) 覆盖. 令 $F=\operatorname{span}\left(x_1,\dots,x_m\right)$, 它是有限维子空间. 因 $E$ 无穷维, 存在 $y\in{E}\setminus{F}$. 由有限维子空间闭与距离可达, $F$ 闭且可取 $x\in{F}$ 使 $\left\|y-x\right\|=d\left(y,F\right)$. 令

$$
x_0=\frac{y-x}{\left\|y-x\right\|}.
$$

则 $\left\|x_0\right\|=1$. 对任意 $z\in{F}$,

$$
\left\|x_0-z\right\|=\frac{\left\|y-\left(x+\left\|y-x\right\|z\right)\right\|}{\left\|y-x\right\|}\ge\frac{d\left(y,F\right)}{\left\|y-x\right\|}=1.
$$

故 $d\left(x_0,F\right)\ge1$. 但每个 $x_i\in{F}$, 故 $\left\|x_0-x_i\right\|\ge1$, 即 $x_0\notin{B}\left(x_i,1\right)$ 对一切 $i$ 成立. 而 $x_0\in\overline{B}\left(0,1\right)$, 与覆盖矛盾. 这就是**定理 6.17 (里茨定理)**.

第 (3) 小题: 由**定义 6.46 (点到集合的距离)**, 对 $x\notin{A}$ 定义

$$
g\left(x\right)=\frac{1}{d\left(x,A\right)}\inf_{y\in{A}}\left(f\left(y\right)d\left(x,y\right)\right),
$$

对 $x\in{A}$ 令 $g\left(x\right)=f\left(x\right)$. 由平移缩放 (不妨设 $\inf_Af=1$, $\sup_Af=2$), 可验证 $g$ 连续: $x\in\operatorname{int}A$ 时 $g=f$ 连续; $x\notin{A}$ 时由三角不等式 $d\left(x,A\right)$ 连续且正, $g$ 连续; $x\in\partial{A}$ 时由 $f$ 在 $A$ 上连续, 对 $\varepsilon>0$ 取 $r>0$ 使 $y\in{B}\left(x,r\right)\cap{A}$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\varepsilon$, 再对 $z\notin{A}$ 且 $\left\|z-x\right\|<{}r/4$ 用三角不等式估计得 $\left|g\left(z\right)-f\left(x\right)\right|<\varepsilon$. 由**定义 3.22 (连续映射)**, $g$ 在全 $E$ 上连续. 由构造 $\inf_Eg=\inf_Af$, $\sup_Eg=\sup_Af$. 这就是**定理 6.18 (蒂茨-乌雷松扩张定理)**. $\blacksquare$

## 9.5 (2024 卷 A 题三: 紧凸集上非扩张映射的不动点)
设 $E$ 是赋范线性空间, $K\subset{E}$ 紧且凸, $f:K\to{K}$ 连续, 且对任意 $x,y\in{K}$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le\left\|x-y\right\|$.

(1) 证明: 若把条件加强为对 $x\neq{y}$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$, 则 $f$ 至少有一个不动点;

(2) 取定 $a\in{K}$. 证明 $f_n\left(x\right)=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x\right)$ 是 $K$ 到 $K$ 的映射, 且对每个 $n\ge1$ 有不动点 $x_n\in{K}$;

(3) 利用 $\left\{x_n\right\}$ 与 $K$ 的紧性, 证明原来的 $f$ 也有不动点.

2024 卷 A 题三.

### 解答 9.5

(1) 令 $g\left(x\right)=\left\|f\left(x\right)-x\right\|$. 由**定义 3.22 (连续映射)** $g$ 连续; 由**定义 5.16 (紧致空间)** 与**定理 6.1 (紧 $=$ 序列紧)**, $g$ 在紧集 $K$ 上取到最小值 $m$ 于某 $x_*\in{K}$. 若 $m>0$, 则由严格压缩, $g\left(f\left(x_*\right)\right)=\left\|f\left(f\left(x_*\right)\right)-f\left(x_*\right)\right\|<\left\|f\left(x_*\right)-x_*\right\|=m$, 与 $m$ 的最小性矛盾. 故 $m=0$, 即 $x_*$ 是**定义 4.17 (不动点)** 意义下的不动点. 这也可直接引用**定理 6.16 (巴拿赫不动点定理)**, 因由**定理 6.3 (紧度量空间完备)** $K$ 完备.

(2) 由**定义 4.23 (凸集)**, $K$ 凸, 故 $f_n\left(x\right)$ 是 $a$ 与 $f\left(x\right)$ 的凸组合 (系数 $\frac{1}{n}$ 与 $1-\frac{1}{n}$ 非负且和为 $1$), 从而 $f_n\left(x\right)\in{K}$. 又

$$
\left\|f_n\left(x\right)-f_n\left(y\right)\right\|=\left(1-\frac{1}{n}\right)\left\|f\left(x\right)-f\left(y\right)\right\|\le\left(1-\frac{1}{n}\right)\left\|x-y\right\|,
$$

故 $f_n$ 是以 $k=1-\frac{1}{n}<1$ 为常数的**定义 6.19 (压缩映射)**. 由**定理 6.3 (紧度量空间完备)** $K$ 完备, 由**定理 6.16 (巴拿赫不动点定理)**, $f_n$ 有唯一不动点 $x_n$.

(3) 由 $x_n=f_n\left(x_n\right)$ 得 $x_n=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x_n\right)$, 即

$$
x_n-f\left(x_n\right)=\frac{1}{n}\left(a-f\left(x_n\right)\right).
$$

$K$ 紧故有界, 于是 $\left\|x_n-f\left(x_n\right)\right\|\le\frac{1}{n}\left(\left\|a\right\|+\sup_{x\in{K}}\left\|f\left(x\right)\right\|\right)\to0$.

由**定理 6.1 (紧 $=$ 序列紧)**, $\left\{x_n\right\}$ 有子列 $x_{n_k}\to{x}$ 于某 $x\in{K}$. 由 $f$ 连续, $f\left(x_{n_k}\right)\to{f}\left(x\right)$, 故

$$
\left\|x-f\left(x\right)\right\|=\lim_k\left\|x_{n_k}-f\left(x_{n_k}\right)\right\|=0,
$$

即 $f\left(x\right)=x$. $\blacksquare$

> 三条路线放在一起看: 严格压缩直接给出最小点; 非扩张则先压一点点换成压缩映射, 再用紧性把不动点传回极限.

## 9.6 (紧凸集上连续仿射映射的不动点 (角谷–马尔可夫定理))
证明: 紧凸集到自身的连续仿射映射有不动点 (角谷-马尔可夫定理).

2025 卷 A 题二.

### 解答 9.6

设 $K\subset{E}$ 紧凸, $f:K\to{K}$ 连续仿射. 考虑 $K$ 的所有非空闭凸子集族, 它们在 $f$ 下不变. 由**定理 5.1 (紧空间连续像紧)** 与**定义 4.23 (凸集)**, $f$ 把闭凸集映为闭凸集. 由**定义 5.17 (有限交性质)** 与**定理 5.10 (有限交判据)**, 这些不变闭凸子集族具有有限交性质, 其交 $K_0$ 非空. 取 $K_0$ 为极小不变闭凸集. 由极小性, $f\left(K_0\right)=K_0$. 若 $K_0$ 多于一点, 由凸性与仿射性可进一步收缩, 矛盾. 故 $K_0$ 为单点 $\left\{x\right\}$, 即 $f\left(x\right)=x$. $\blacksquare$

## 9.7 (集合间下确界距离一般不是度量)
设 $\left(X,d\right)$ 是度量空间. 证明朴素定义 $d\left(A,B\right)=\inf_{a\in{A},b\in{B}}d\left(a,b\right)$ 一般不是度量.

题集 §3.2 Q1.

### 解答 9.7

在 $\mathbb{R}^2$ (配通常欧氏距离) 中取

$$
A=\left\{\left(x,0\right):x\in\mathbb{R}\right\},\quad{B}=\left\{\left(n,1/n\right):n\in\mathbb{Z}_{>0}\right\}.
$$

由**定义 6.46 (点到集合的距离)**,

$$
d\left(A,B\right)\le{d}\left(\left(n,0\right),\left(n,1/n\right)\right)=1/n\to0,
$$

故 $d\left(A,B\right)=0$, 但 $A\neq{B}$. 这不满足**定义 6.35 (度量空间)** 中"距离为零蕴含两点相等"的公理 (应用于集合时即两集合相等). 故该朴素定义一般不是度量. $\blacksquare$

> 这给出了我们需要定义豪斯多夫距离的一个原因.

## 9.8 ($\varepsilon$-邻域的嵌套不等式)
定义集合 $A\subset{X}$ 的 $\varepsilon$-邻域 $U_\varepsilon\left(A\right)=\left\{x\in{X}:d\left(x,A\right)<\varepsilon\right\}$, 其中 $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. 证明: 对 $r_1,r_2>0$ 与任意 $A\subset{X}$,

$$
U_{r_1}\left(U_{r_2}\left(A\right)\right)\subset{U}_{r_1+r_2}\left(A\right),
$$

但反过来一般不成立.

题集 §3.2 Q2.

### 解答 9.8

设 $x\in{U}_{r_1}\left(U_{r_2}\left(A\right)\right)$. 由**定义 6.47 ($\varepsilon$-邻域)**, 存在 $y\in{U}_{r_2}\left(A\right)$ 使 $d\left(x,y\right)<{}r_1$; 再由**定义 6.46 (点到集合的距离)**, 存在 $a\in{A}$ 使 $d\left(y,a\right)<{}r_2$. 由**定义 6.35 (度量空间)** 的三角不等式,

$$
d\left(x,a\right)\le{d}\left(x,y\right)+d\left(y,a\right)<{}r_1+r_2.
$$

故 $x\in{U}_{r_1+r_2}\left(A\right)$, 包含关系成立.

反之不真. 取 $X=\left\{0,1,3\right\}$ 赋通常距离, $A=\left\{0,3\right\}$, $r_1=r_2=1$. 由**定义 6.46 (点到集合的距离)** 与**定义 6.47 ($\varepsilon$-邻域)**, $d\left(1,A\right)=1$, 故

$$
U_1\left(A\right)=\left\{x:d\left(x,A\right)<1\right\}=\left\{0,3\right\},
$$

从而 $U_1\left(U_1\left(A\right)\right)=\left\{0,3\right\}$. 但 $d\left(1,A\right)=1<2$, 故 $1\in{U}_2\left(A\right)$. 因此 $U_{r_1+r_2}\left(A\right)\not\subset{U}_{r_1}\left(U_{r_2}\left(A\right)\right)$. $\blacksquare$

> 不可逆的原因正是因为邻域是严格小于, 这导致三角不等式变成了严格成立.

## 9.9 (豪斯多夫距离是伪距离)
定义子集 $A,B\subset{X}$ 之间的豪斯多夫距离

$$
d_H\left(A,B\right)=\inf\left\{r>0:A\subset{U}_r\left(B\right),B\subset{U}_r\left(A\right)\right\}.
$$

证明豪斯多夫距离是伪距离, 即满足度量的全部公理, 只是 $d_H\left(A,B\right)=0$ 不一定蕴含 $A=B$.

题集 §3.2 Q3.

### 解答 9.9

由**定义 6.48 (豪斯多夫距离)**, 非负性与对称性是显然的 (定义关于 $A,B$ 对称). 又 $d_H\left(A,A\right)=0$, 因为对任意 $r>0$, $A\subset{U}_r\left(A\right)$ 恒成立.

剩证三角不等式. 设 $A,B,C\subset{X}$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,B\right)<{}r$ 意味着 $A\subset{U}_r\left(B\right)$ 且 $B\subset{U}_r\left(A\right)$. 若 $A\subset{U}_r\left(B\right)$ 且 $B\subset{U}_s\left(C\right)$, 由**习题 9.8**的包含关系 (**定义 6.47 ($\varepsilon$-邻域)**),

$$
A\subset{U}_r\left(B\right)\subset{U}_r\left(U_s\left(C\right)\right)\subset{U}_{r+s}\left(C\right).
$$

同理 $C\subset{U}_{r+s}\left(A\right)$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,C\right)\le{r}+s$. 令 $r\downarrow{d}_H\left(A,B\right)$, $s\downarrow{d}_H\left(B,C\right)$, 即得三角不等式

$$
d_H\left(A,C\right)\le{d}_H\left(A,B\right)+d_H\left(B,C\right).
$$

由**定义 6.44 (伪距离)**, 它满足除"距离为零蕴含相等"外全部公理, 故是伪距离. $\blacksquare$

> $d_H\left(A,B\right)=0\not\Rightarrow{A}=B$: 取 $A=\left(0,1\right)$, $B=\left[0,1\right]$, $d_H\left(A,B\right)=0$ 但 $A\ne{B}$.

## 9.10 (闭集间豪斯多夫距离为零蕴含两集相等)
证明: 对一切 $A\subset{X}$, $d_H\left(A,A\right)=0$. 若 $A,B$ 闭, 则 $d_H\left(A,B\right)=0$ 蕴含 $A=B$.

题集 §3.2 Q4.

### 解答 9.10

现设 $A,B$ 闭且 $d_H\left(A,B\right)=0$. 任取 $a\in{A}$. 对每个 $n$, 由**定义 6.48 (豪斯多夫距离)** 与 $d_H\left(A,B\right)=0$, 存在 $b_n\in{B}$ 使 $d_H\left(a,b_n\right)<1/n$. 于是 $b_n\to{a}$. 由**定义 3.21 (闭集)**, 闭集含其中序列的极限, 故 $a\in{B}$. 这证明 $A\subset{B}$. 交换 $A,B$ 同理得 $B\subset{A}$, 故 $A=B$. $\blacksquare$

## 9.11 (豪斯多夫距离限制在紧子集族上是真度量)
证明: 若把豪斯多夫距离限制在紧子集族 $\mathcal{K}\left(X\right)$ 上, 则它是 $\mathcal{K}\left(X\right)$ 上的真度量.

题集 §3.2 Q5.

### 解答 9.11

由**习题 9.9**, $d_H$ 是伪距离, 已满足非负性, 对称性与三角不等式. 剩证分离性. 设 $A,B\in\mathcal{K}\left(X\right)$ 紧致且 $d_H\left(A,B\right)=0$. 度量空间是**定义 3.10 (豪斯多夫空间)**, 由**定理 5.5 (豪斯多夫中紧集闭)**, 紧集 $A,B$ 在 $X$ 中闭. 由**习题 9.10**的结论, $d_H\left(A,B\right)=0$ 且 $A,B$ 闭蕴含 $A=B$. 故分离性成立. $\blacksquare$
