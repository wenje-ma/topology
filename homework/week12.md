# week12

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.14 (初始拓扑)**
> 
> 设 $f:X\to{Y}$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal{O}$. 称 $\mathcal{O}_f=\left\{f^{-1}\left(O\right):O\in\mathcal{O}\right\}$ 为 $X$ 上由 $f$ 诱导的初始拓扑; 它是使 $f$ 连续的最粗拓扑. (题集 §1.1 Q2; 题集 §1.4 C6)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{X}$ 是开的当且仅当 $U\in{T}$. 我们要求:
> 
> (1) $\emptyset,X\in{T}$;
> 
> (2) 若 $U,V\in{T}$, 则 $U\cap{V}\in{T}$;
> 
> (3) 若 $A\subset{T}$, 则 $\bigcup{A}\in{T}$. (教材 $\S3$, p12)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.23 (同胚)**
> 
> 空间之间的双射 $f:X\to{Y}$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 §3, p15)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 4.1 (区间连通)**
> 
> $\left[0,1\right]$ 连通; 由此任意区间连通. (教材 §4, p23; "拓扑学"(原书第2版) §24 推论 24.2)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset{X}$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $\boldsymbol{x},\boldsymbol{y}\in{K}$ 蕴含线段 $\left(1-t\right)\boldsymbol{x}+t\boldsymbol{y}$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定义 5.16 (紧致空间)**
> 
> 称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.6 (函数空间完备)**
> 
> $Y$ 完备则 $\left(Y^X,\text{一致度量}\right)$ 完备. (教材 §6)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.14 (递增闭集族)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 若为可数个闭集之并 $X=\bigcup_nF_n$, 则至少一个 $F_n$ 含非空开集. (教材 §6)

> **定理 6.16 (巴拿赫不动点定理)**
> 
> 非空完备度量空间上的压缩映射有唯一不动点. (题集 §4.3 Q1)

> **定义 6.19 (压缩映射)**
> 
> 称 $f:X\to{X}$ 是压缩的, 若存在 $0<{}k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le{k}\,d\left(x,y\right)$. (题集 §4.3 Q1)

> **定义 6.20 (赋范线性空间)**
> 
> 向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21 (巴拿赫空间)**
> 
> 完备的赋范线性空间. (题集 §5)

> **定义 6.24 (拓扑向量空间)**
> 
> 向量空间装备使加法 $E\times{E}\to{E}$ 与数乘 $\mathbb{K}\times{E}\to{E}$ 都连续的拓扑. (题集 §5 Q6)

> **定义 6.25 (半范数)**
> 
> 满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 §5 Q6)

> **定义 6.26 (局部凸空间)**
> 
> 拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 §5 Q6)

> **定义 6.27 (规范函数)**
> 
> 凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in{C},t>0\right\}$ (等价地 $\inf\left\{t>0:x\in{t}C\right\}$). (题集 §5 Q14)

> **定义 6.28 (算子范数)**
> 
> $L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le1}\left\|Tx\right\|$. (题集 §5 Q15)

> **定义 6.29 (商范数)**
> 
> 赋范空间 $E$ 模闭子空间 $F$, $\left\|\left[x\right]\right\|=\inf_{y\in{F}}\left\|x+y\right\|$. (题集 §5.1 C17)

> **定义 6.30 (弱拓扑)**
> 
> $E$ 上由全体连续线性泛函 $\varphi\in{E}^*$ 的拉回生成的初始拓扑. (题集 §5 Q16)

> **定义 6.31 (弱星拓扑)**
> 
> 对偶 $E^*$ 上由赋值映射 $\left\{\varphi\mapsto\varphi\left(x\right)\right\}_{x\in{E}}$ 诱导的初始拓扑. (题集 §5 Q17-Q18)

> **定义 6.32 (拓扑对偶)**
> 
> $E^*$ 为 $E$ 上全体连续线性泛函. (题集 §5 Q18)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定理 6.50 (哈恩-巴拿赫定理)**
> 
> 赋范线性空间上, 点与不相交闭凸集可被连续线性泛函严格分离; 特别地 $E^*$ 分离 $E$ 的点. (题集 §5)

> **定义 6.55 (超平面)**
> 
> 向量空间中余维数为 $1$ 的线性子空间 (即非零线性泛函的核). (题集 §6 C3)

> **定义 6.56 (线性泛函)**
> 
> 从向量空间到数域的线性映射. (题集 §6 C3)

> **定理 6.57 (开映射定理)**
> 
> 巴拿赫空间之间的连续满线性映射是开映射, 并且存在 $c>0$ 使 $\left\|\left[x\right]\right\|\ge{c}\left\|Tx\right\|$. (题集 §6 C5)

> **定理 6.58 (巴拿赫-施坦豪斯定理)**
> 
> 巴拿赫空间到赋范空间的逐点有界连续线性映射族必一致有界. (题集 §6 C6)

> **定理 6.59 (巴拿赫-绍德不动点定理)**
> 
> 紧凸集到自身的连续映射有不动点. (题集 §6 C7)

> **定义 6.60 ($l^p$ 空间)**
> 
> $l^p=\left\{x:\sum_n\left|x_n\right|^p<\infty\right\}$ 装备 $\left\|x\right\|_p=\left(\sum_n\left|x_n\right|^p\right)^{1/p}$. (题集 §6 C11)

## 12.16 (范数连续与赋范空间豪斯多夫)

证明赋范空间上的范数是连续函数; 赋范空间是豪斯多夫的.

题集 §5.1 C16.

### 解答 12.16

由**定义 6.20 (赋范线性空间)**, 由范数的反三角不等式 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$, 范数是利普希茨映射, 故连续.

$\blacksquare$

豪斯多夫: 设 $x\neq{y}$, 取 $r=\left\|x-y\right\|/3>0$, 则开球 $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 不相交 (若 $z$ 同时在二者中, 则 $\left\|x-y\right\|\le\left\|x-z\right\|+\left\|z-y\right\|<2r<\left\|x-y\right\|$, 矛盾). 由**定义 3.10 (豪斯多夫空间)**, 赋范空间豪斯多夫.

$\blacksquare$

## 12.17 (商范数使商空间成为赋范空间)

设 $E$ 是赋范空间, $F\subset{E}$ 是闭子空间. 证明商范数使 $E/F$ 成为赋范空间.

题集 §5.1 C17.

### 解答 12.17

由**定义 6.29 (商范数)**, $\left\|\left[x\right]\right\|=\inf_{y\in{F}}\left\|x+y\right\|$. 非负显然. 齐次: $\left\|\lambda\left[x\right]\right\|=\inf_{y\in{F}}\left\|\lambda{x}+y\right\|=\left|\lambda\right|\inf_{y\in{F}}\left\|x+y/\lambda\right\|=\left|\lambda\right|\left\|\left[x\right]\right\|$.

三角不等式: 对任意 $y_1,y_2\in{F}$,

$$
\left\|\left[x_1+x_2\right]\right\|\le\left\|x_1+x_2+y_1+y_2\right\|\le\left\|x_1+y_1\right\|+\left\|x_2+y_2\right\|.
$$

取下确界得三角不等式.

正定性: 若 $\left\|\left[x\right]\right\|=0$, 则存在 $y_n\in{F}$ 使 $\left\|x+y_n\right\|\to0$, 即 $-y_n\to{x}$. 由 $F$ 闭, $x\in{F}$, 即 $\left[x\right]=0$. 由**定义 6.20 (赋范线性空间)**, $E/F$ 是赋范空间.

$\blacksquare$

## 12.18 (超平面是非零连续线性泛函的核)

证明: 拓扑向量空间 $E$ 中的超平面 $H$ 是核, 即存在非零连续线性泛函 $\varphi:E\to\mathbb{K}$ 使 $H=\ker\varphi$.

题集 §6 C3.

### 解答 12.18

由**定义 6.55 (超平面)**, $H$ 余维数为 $1$. 任取 $x_0\notin{H}$, 则 $E=H\oplus\mathbb{K}x_0$. 定义 $\varphi\left(h+\lambda{x}_0\right)=\lambda$. 它是**定义 6.56 (线性泛函)** 且核为 $H$.

连续性: 若 $H$ 闭, 则 $E/H$ 一维赋范空间 (由**定义 6.20 (赋范线性空间)** 的商), $\varphi$ 诱导一维映射, 连续. 反之, 若 $\varphi$ 连续, 则 $H=\varphi^{-1}\left(\left\{0\right\}\right)$ 是 $\left\{0\right\}$ (闭) 的原像, 由**定义 3.22 (连续映射)** 与**定义 3.21 (闭集)**, $H$ 闭.

$\blacksquare$

## 12.19 (开映射定理的推论: 巴拿赫空间间的连续线性双射是同胚)

叙述并证明开映射定理的一个推论: 巴拿赫空间之间的连续线性双射是同胚.

题集 §6 C5.

### 解答 12.19

设 $T:E\to{F}$ 是巴拿赫空间之间的连续线性双射. 由**定理 6.57 (开映射定理)**, $T$ 是开映射, 即 $T$ 把开集映为开集. 对任意开集 $U\subset{E}$, $T\left(U\right)$ 开于 $F$. 由**定义 3.22 (连续映射)**, $T^{-1}:F\to{E}$ 连续. 又 $T$ 连续, 由**定义 3.23 (同胚)**, $T$ 是同胚.

$\blacksquare$

## 12.20 (巴拿赫–施坦豪斯的推论: 弱收敛序列有界)

叙述并证明巴拿赫-施坦豪斯定理的一个推论: 弱收敛的序列在赋范空间中是有界的.

题集 §6 C6.

### 解答 12.20

设 $\left(x_n\right)\subset{E}$ 弱收敛, 即对一切 $\varphi\in{E}^*$, $\varphi\left(x_n\right)$ 收敛, 从而有界. 视 $x_n$ 为 $E^{**}$ 中元素 (即 $x_n\left(\varphi\right)=\varphi\left(x_n\right)$). 由**定理 6.58 (巴拿赫-施坦豪斯定理)**, 逐点有界族 $\left\{x_n\right\}\subset{E}^{**}$ 一致有界, 即 $\sup_n\left\|x_n\right\|<\infty$. 由**定义 3.22 (连续映射)** 的赋范版本, $\left(x_n\right)$ 有界.

$\blacksquare$

## 12.21 (巴拿赫–绍德的推论: 紧凸集上连续映射有不动点)

叙述并证明巴拿赫-绍德不动点定理的一个推论: 紧凸集到自身的连续映射有不动点.

题集 §6 C7.

### 解答 12.21

由**定理 6.59 (巴拿赫-绍德不动点定理)**, 设 $K\subset{E}$ 紧凸, $f:K\to{K}$ 连续. 紧凸集可被有限维逼近 (绍德尔逼近), 在每片上用有限维不动点定理 (布劳威尔不动点定理), 再取极限即得不动点. 这正是该定理的标准推论.

$\blacksquare$

## 12.22 (无穷维赋范空间不是可数个有限维子空间之并)

证明: 无穷维赋范空间不能写成可数个有限维子空间之并.

题集 §7.3 第一题 与 §7.4 第一题.

### 解答 12.22

由**定义 6.21 (巴拿赫空间)**, 完备赋范空间不能写成可数个真闭子空间之并. 每个有限维子空间是闭的 (有限维子空间闭). 若 $E=\bigcup_{k=1}^{\infty}F_k$ 其中每个 $F_k$ 有限维, 则由**定理 6.14 (递增闭集族)**, 某 $F_k$ 有非空内部. 但有限维真子空间的内部为空 (否则它含一个开球, 由线性性撑开整个 $E$, 与真子空间矛盾). 故每个 $F_k$ 内部为空. 与**定理 6.13 (贝尔纲定理)** 矛盾.

$\blacksquare$

## 12.23 (点态收敛极限的连续点集与导函数的连续点集)

设 $\left(E,d\right),\left(F,\delta\right)$ 是度量空间, $E$ 完备, $f_n:E\to{F}$ 连续, 且 $f_n$ 逐点收敛到 $f$.

(1) 对 $\varepsilon>0$ 与 $n\in\mathbb{N}$ 令 $F_{n,\varepsilon}=\left\{x\in{E}:\forall{p}\ge{n},\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}$. 用贝尔纲定理证明 $\Omega_\varepsilon=\bigcup_n\operatorname{int}\left(F_{n,\varepsilon}\right)$ 在 $E$ 中稠密;

(2) 证明对每个 $x_0\in\Omega_\varepsilon$ 存在 $x_0$ 的邻域 $V$, 使 $x\in{V}$ 时 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le3\varepsilon$;

(3) 证明 $f$ 的连续点集在 $E$ 中稠密;

(4) 证明可导函数 $f:\mathbb{R}\to\mathbb{R}$ 的导函数 $f'$ 的连续点集在 $\mathbb{R}$ 中稠密.

题集 $\S7.4$ 第二题.

### 解答 12.23

(1) $F_{n,\varepsilon}$ 闭: 它是可数个 $\left\{x:\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}$ 之交, 每个由 $\delta\circ\left(f_p,f_n\right)$ 连续而闭 (**定义 3.21 (闭集)**). 又 $\bigcup_nF_{n,\varepsilon}=E$: 固定 $x$, $\left(f_p\left(x\right)\right)$ 收敛故柯西, 取 $n$ 使 $p\ge{n}$ 时两项距离 $\le\varepsilon$ 即 $x\in{F}_{n,\varepsilon}$. 由**定理 6.13 (贝尔纲定理)**, 完备空间 $E$ 中可数个闭集不能都是无处稠密的, 故某个 $F_{n,\varepsilon}$ 含内点. 对 $E$ 的任意开球 $B$ 用同一论证 (以 $B$ 代 $E$), 得 $B$ 内有某个 $F_{n,\varepsilon}$ 的内点. 故 $\Omega_\varepsilon$ 在每个开球中非空, 稠密; 它本身开.

$\blacksquare$

(2) 设 $x_0\in\operatorname{int}\left(F_{n,\varepsilon}\right)$, 取邻域 $V\subset{F}_{n,\varepsilon}$. 对 $x\in{V}$,

$$
\delta\left(f\left(x_0\right),f\left(x\right)\right)\le\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)+\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)+\delta\left(f_n\left(x\right),f\left(x\right)\right).
$$

第一, 第三项 $\le\varepsilon$: 因 $x_0,x\in{F}_{n,\varepsilon}$ 且 $p\to\infty$ 取极限. 第二项 $\le\varepsilon$: 因 $f_n$ 连续 (**定义 3.22 (连续映射)**), 必要时缩小 $V$ 使 $x\in{V}$ 时 $\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)\le\varepsilon$. 三者相加得 $3\varepsilon$.

$\blacksquare$

(3) 令 $\Omega=\bigcap_{m}\Omega_{1/m}$. 它是稠密 $G_\delta$ (可数个稠密开集之交). 对 $x_0\in\Omega$ 与任意 $m$, 由 (2) 取 $V_m$ 使 $x\in{V}_m$ 时 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le3/m$. 故 $f$ 在 $x_0$ 连续. 于是连续点集包含稠密集 $\Omega$, 从而稠密.

$\blacksquare$

(4) 设 $f$ 在 $\mathbb{R}$ 上可导. 对每个 $h\neq0$ 令

$$
\varphi_h\left(x\right)=\frac{f\left(x+h\right)-f\left(x\right)}{h}.
$$

每个 $\varphi_h$ 连续, 且 $\varphi_h\left(x\right)\to{f}'\left(x\right)$ 对每个 $x$ 成立. 由 (3), 逐点收敛的连续函数列的极限的连续点集稠密, 故 $f'$ 的连续点集在 $\mathbb{R}$ 中稠密. 这里 $\left(E,d\right)=\left(\mathbb{R},\left|\cdot\right|\right)$ 完备, 需把 $\varphi_h$ 的指标集取成可数 (取 $h=1/k$), 收敛性不变.

$\blacksquare$

> (4) 的用途: 它说明"导函数连续点稠密"不是一个分析技巧, 而是贝尔纲的直接推论.

## 12.24 ($l^p$ 严格包含于 $l^q$, 且 $l^p$ 在 $l^q$ 中闭)

证明: 对 $1\le{p}<{}q\le\infty$, $l^p\subsetneq{l}^q$. 进一步证明 $l^p$ 在 $l^q$ 中闭.

题集 §6 C11.

### 解答 12.24

包含 $\subset$: 若 $\sum_n\left|x_n\right|^p<\infty$, 则 $\left|x_n\right|\to0$, 故 $\left(x_n\right)$ 有界, 从而 $\sup_n\left|x_n\right|<\infty$, 即 $x\in{l}^\infty$. 对有限 $q>p$, 由 $\left|x_n\right|\to0$, 存在 $N$ 使 $n\ge{N}$ 时 $\left|x_n\right|\le1$, 于是 $\left|x_n\right|^q\le\left|x_n\right|^p$, 故 $\sum_n\left|x_n\right|^q<\infty$.

严格包含: $x_n=n^{-1/p}$ 时 $\sum_nn^{-1}$ 发散, 但 $\sum_nn^{-q/p}<\infty$ (因 $q/p>1$), 故 $x\in{l}^q$ 但 $x\notin{l}^p$.

$\blacksquare$

闭性: 设 $x^{\left(m\right)}\in{l}^p$ 按 $l^q$ 范数收敛到 $x$. 对任意有限 $N$,

$$
\sum_{n=1}^N\left|x_n\right|^p=\lim_{m\to\infty}\sum_{n=1}^N\left|x_n^{\left(m\right)}\right|^p\le\liminf_{m\to\infty}\sum_{n=1}^{\infty}\left|x_n^{\left(m\right)}\right|^p.
$$

右端有界 ($\left\|x^{\left(m\right)}\right\|_p$ 由 $l^q$ 收敛控制, 因 $l^p\subset{l}^q$ 包含关系给出范数比较). 令 $N\to\infty$ 得 $\sum_n\left|x_n\right|^p<\infty$, 故 $x\in{l}^p$. 由**定义 3.21 (闭集)**, $l^p$ 闭.

由**定义 6.60 ($l^p$ 空间)** 与**定理 6.14 (递增闭集族)** 的标准应用, 上述结论成立.

$\blacksquare$

## 12.25 (幂零矩阵的刻画)

设 $\boldsymbol{N}\in{M}_n\left(\mathbb{C}\right)$. 证明 $\boldsymbol{N}$ 幂零当且仅当 $0$ 属于 $\left\{\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}:\boldsymbol{P}\in{GL}_n\left(\mathbb{C}\right)\right\}$ 的闭包.

题集 $\S8.5$ W2.

### 解答 12.25

设 $\boldsymbol{N}$ 幂零, 即 $\boldsymbol{N}^n=0$. 由若尔当标准形, 存在 $\boldsymbol{P}$ 使 $\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}$ 为上三角且对角元为零: 幂零矩阵的特征值全为零, 而上三角阵的对角元就是特征值. 令 $\boldsymbol{T}=\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}$, 记 $\boldsymbol{T}=\left(T_{ij}\right)$ 满足 $i\ge{j}$ 时 $T_{ij}=0$.

对 $t>0$ 取 $\boldsymbol{D}_t=\operatorname{diag}\left(t,t^2,\dots,t^n\right)$. 则

$$
\left(\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t\right)_{ij}=t^{j-i}T_{ij}.
$$

当 $i\ge{j}$ 时 $T_{ij}=0$; 当 $i<{}j$ 时 $t^{j-i}\to0$ ($t\to0^+$), 而 $T_{ij}$ 固定. 故 $\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t\to0$ ($t\to0^+$). 又 $\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t=\left(\boldsymbol{P}\boldsymbol{D}_t\right)^{-1}\boldsymbol{N}\left(\boldsymbol{P}\boldsymbol{D}_t\right)$, 故 $0$ 是共轭族 $\left\{\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}\right\}$ 的聚点.

$\blacksquare$

反之设 $0$ 是该族的聚点, 即有 $\boldsymbol{P}_k\in{GL}_n\left(\mathbb{C}\right)$ 使 $\boldsymbol{P}_k^{-1}\boldsymbol{N}\boldsymbol{P}_k\to0$. 特征多项式 $\chi_M\left(\lambda\right)=\det\left(\lambda{I}-\boldsymbol{M}\right)$ 的系数是 $\boldsymbol{M}$ 的元素的连续函数, 故

$$
\chi_N=\chi_{P_k^{-1}NP_k}\longrightarrow\chi_0\left(\lambda\right)=\lambda^n.
$$

由**定义 3.22 (连续映射)** 取极限, $\chi_N\left(\lambda\right)=\lambda^n$. 由凯莱-哈密顿定理 $\chi_N\left(\boldsymbol{N}\right)=0$, 即 $\boldsymbol{N}^n=0$.

$\blacksquare$

> 上三角化的意义: 特征值全零使对角元为零, 于是只剩下严格上三角部分, 而严格上三角部分在"梯度缩放"共轭下可以被压到任意小.

## 12.26 (非线性算子 $A^*$ 的利普希茨性与压缩不动点)

设 $\boldsymbol{A}\in{M}_n\left(\mathbb{R}\right)$, 定义 $A^*:\mathbb{R}^n\to\mathbb{R}^n$ 为

$$
\left[A^*\boldsymbol{v}\right]_j=\min\left\{v_i+A_{ij}:1\le{i}\le{n}\right\},\quad1\le{j}\le{n}.
$$

证明:

(1) $A^*$ 是利普希茨的;

(2) 对每个 $\lambda\in\left(0,1\right)$ 存在唯一的 $\boldsymbol{v}_\lambda\in\mathbb{R}^n$ 使 $\boldsymbol{v}_\lambda=A^*\left(\lambda\boldsymbol{v}_\lambda\right)$.

题集 $\S8.5$ W4.

### 解答 12.26

(1) 对 $\boldsymbol{v},\boldsymbol{w}\in\mathbb{R}^n$ 与 $j$, 令 $i_v$ 使 $\left[A^*\boldsymbol{v}\right]_j=v_{i_v}+A_{i_vj}$ 取到最小. 则

$$
\left[A^*\boldsymbol{v}\right]_j-\left[A^*\boldsymbol{w}\right]_j\le\left(v_{i_v}+A_{i_vj}\right)-\left(w_{i_v}+A_{i_vj}\right)=v_{i_v}-w_{i_v}\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty.
$$

交换 $\boldsymbol{v},\boldsymbol{w}$ 得 $\left|\left[A^*\boldsymbol{v}\right]_j-\left[A^*\boldsymbol{w}\right]_j\right|\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty$, 对 $j$ 取最大即 $\left\|A^*\boldsymbol{v}-A^*\boldsymbol{w}\right\|_\infty\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty$.

$\blacksquare$

(2) 令 $\Phi_\lambda\left(\boldsymbol{v}\right)=A^*\left(\lambda\boldsymbol{v}\right)$. 由上一段

$$
\left\|\Phi_\lambda\left(\boldsymbol{v}\right)-\Phi_\lambda\left(\boldsymbol{w}\right)\right\|_\infty=\left\|A^*\left(\lambda\boldsymbol{v}\right)-A^*\left(\lambda\boldsymbol{w}\right)\right\|_\infty\le\lambda\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty,
$$

故 $\Phi_\lambda$ 是常数 $\lambda<1$ 的**定义 6.19 (压缩映射)**; $\mathbb{R}^n$ 带上确界范数完备, 由**定理 6.16 (巴拿赫不动点定理)**, $\Phi_\lambda$ 有唯一不动点 $\boldsymbol{v}_\lambda$, 即 $\boldsymbol{v}_\lambda=A^*\left(\lambda\boldsymbol{v}_\lambda\right)$.

$\blacksquare$

> $A^*$ 是"取最小"这种逐坐标的极值算子, 它满足 $\left|\min{a}_j-\min{b}_j\right|\le\max\left|a_j-b_j\right|$, 因此天然是 $1$-利普希茨的, 压缩性只能来自外面的因子 $\lambda$.

## 12.27 ($\mathbb{R}^2$ 不是可数条 $C^1$ 曲线之并)

证明 $\mathbb{R}^2$ 不能写成可数条 $C^1$ 曲线之并.

题集 $\S8.5$ W5.

### 解答 12.27

设 $\gamma:\mathbb{R}\to\mathbb{R}^2$ 是 $C^1$ 曲线. 把 $\mathbb{R}$ 拆成 $\bigcup_{m\in\mathbb{Z}}\left[m,m+1\right]$, 得 $\gamma\left(\mathbb{R}\right)=\bigcup_m\gamma\left(\left[m,m+1\right]\right)$.

固定 $\left[a,a+1\right]$. 由 $\gamma'$ 连续, 它在 $\left[a,a+1\right]$ 上有界, 设 $\left\|\gamma'\right\|\le{L}$. 由中值定理, $\gamma$ 在 $\left[a,a+1\right]$ 上是常数 $L$ 的利普希茨映射.

把 $\left[a,a+1\right]$ 分成 $N$ 段, 每段长 $\frac{1}{N}$. 每段的像含在半径 $\frac{L}{N}$ 的圆盘中, 故

$$
\lambda_2\left(\gamma\left(\left[a,a+1\right]\right)\right)\le{N}\cdot\pi\left(\frac{L}{N}\right)^2=\frac{\pi{L}^2}{N}\longrightarrow0,
$$

其中 $\lambda_2$ 是平面勒贝格测度. 故 $\gamma\left(\left[a,a+1\right]\right)$ 的测度为零.

测度为零的紧集内部为空: 若它含非空开集, 该开集测度为正. 故 $\gamma\left(\left[m,m+1\right]\right)$ 无处稠密, 从而 $\gamma\left(\mathbb{R}\right)$ 是可数个无处稠密集之并.

若 $\mathbb{R}^2$ 是可数条 $C^1$ 曲线之并, 则 $\mathbb{R}^2$ 是可数个无处稠密集之并, 与**定理 6.13 (贝尔纲定理)** (完备空间不能是可数个无处稠密集之并) 矛盾.

$\blacksquare$

> 用到的只有"$C^1$ 在紧区间上是利普希茨", 连续性不够: 皮亚诺曲线连续而能填满方块.

## 12.28 (拓扑单调性: 单调映射, 怀伯恩定理与一致极限)

(1) 证明 $u:\mathbb{R}\to\mathbb{R}$ 单调当且仅当对每个 $x$ 逆像 $u^{-1}\left(\left\{x\right\}\right)$ 连通;

(2) 两紧度量空间之间的映射 $F:X\to{Y}$ 称为拓扑单调的, 若 $F$ 连续, 满射, 且每根纤维 $F^{-1}\left(a\right)$ 连通. 证明怀伯恩定理: 若 $F$ 拓扑单调, 则对每个闭连通集 $A\subset{Y}$, 原像 $F^{-1}\left(A\right)$ 闭且连通;

(3) 设 $F_j:X\to{Y}$ 是一列拓扑单调映射, 一致收敛到 $F$. 证明 $F$ 也是拓扑单调的.

题集 $\S8.6$ T1.

### 解答 12.28

(1) 设 $u$ 单调 (例如不减) 且 $u\left(a\right)=u\left(b\right)=x$, $a<{}b$. 对 $a<{}c<{}b$ 有 $u\left(a\right)\le{u}\left(c\right)\le{u}\left(b\right)$, 故 $u\left(c\right)=x$, 于是 $u^{-1}\left(\left\{x\right\}\right)$ 是区间, 由**定理 4.1 (区间连通)** 连通.

反之设 $u$ 不单调. 则存在 $a<{}b<{}c$ 使 $u\left(b\right)$ 严格大于 $u\left(a\right)$ 与 $u\left(c\right)$ 中的最大者, 或严格小于两者中的最小者 (否则 $u$ 在三点上单调). 设前一种情形, 令 $m=\max\left\{u\left(a\right),u\left(c\right)\right\}$. 取 $x$ 使 $m<{}x<{}u\left(b\right)$. 由**定理 4.1 (区间连通)** 的一般形式 (连续函数的介值性不必要, 这里只用区间性质): $u$ 在 $\left[a,b\right]$ 上从 $\le{m}$ 走到 $>x$, 故有 $s\in\left(a,b\right)$ 使 $u\left(s\right)=x$; 同理 $t\in\left(b,c\right)$ 使 $u\left(t\right)=x$. 于是 $u^{-1}\left(\left\{x\right\}\right)$ 含 $s<{}b<{}t$ 而不含 $b$, 不是区间, 由**定理 4.1 (区间连通)** 不连通.

$\blacksquare$

(2) $F^{-1}\left(A\right)$ 闭: $A$ 闭, $F$ 连续, 由**定义 3.22 (连续映射)** 原像闭.

连通: 设 $\varphi:F^{-1}\left(A\right)\to\left\{0,1\right\}$ 连续 (取 $\left\{0,1\right\}$ 的离散拓扑). 由第 (1) 小题的思路, 只需证 $\varphi$ 常值, 因为连通等价于每个这样的 $\varphi$ 常值 (**定义 4.18 (连通空间)**).

对每个 $a\in{A}$, 纤维 $F^{-1}\left(a\right)$ 连通, 故 $\varphi$ 在其上常值, 记该值为 $c\left(a\right)\in\left\{0,1\right\}$. 下证 $c$ 局部常值. 设 $a\in{A}$ 且 $c\left(a\right)=0$, 取 $a_k\in{A}$ 使 $c\left(a_k\right)=1$ 且 $a_k\to{a}$. 由 $F$ 满射, 取 $x_k\in{F}^{-1}\left(a_k\right)$. 由**定理 6.1 (紧 $=$ 序列紧)**, $X$ 紧 (**定义 5.16 (紧致空间)**), 故有子列 $x_{k'}\to{x}\in{X}$. 由 $F$ 连续, $F\left(x\right)=\lim{a}_{k'}=a$, 即 $x\in{F}^{-1}\left(a\right)$. 因 $c\left(a\right)=0$, $x\in\varphi^{-1}\left(\left\{0\right\}\right)$; 而 $x_{k'}\in{F}^{-1}\left(a_{k'}\right)$ 且 $c\left(a_{k'}\right)=1$, 故 $x_{k'}\in\varphi^{-1}\left(\left\{1\right\}\right)$; 后者闭, 故 $x\in\varphi^{-1}\left(\left\{1\right\}\right)$. 于是 $x$ 同时属于两个不交的闭集 $\varphi^{-1}\left(\left\{0\right\}\right),\varphi^{-1}\left(\left\{1\right\}\right)$, 矛盾. 故 $c$ 不能在 $c\left(a\right)=0$ 的点附近取值 $1$; 同理反向. 故 $c$ 局部常值.

$A$ 连通 (**定义 4.18 (连通空间)**) 故局部常值的 $c$ 常值, 于是 $\varphi$ 在整个 $F^{-1}\left(A\right)$ 上常值. 故 $F^{-1}\left(A\right)$ 连通.

$\blacksquare$

(3) 连续与满射: 一致极限保持连续 (**定义 3.22 (连续映射)**). 满射: $F_j\left(X\right)=Y$, 且 $F_j\to{F}$ 一致, $X$ 紧故 $F\left(X\right)$ 紧 (**定理 6.1 (紧 $=$ 序列紧)**) 从而闭; 任 $y\in{Y}$, 取 $x_j$ 使 $F_j\left(x_j\right)=y$, 沿子列 $x_{j'}\to{x}$ (**定理 6.1 (紧 $=$ 序列紧)**), 由一致性 $F\left(x\right)=y$. 故 $F$ 满射.

纤维连通: 固定 $y\in{Y}$, 记 $K=F^{-1}\left(y\right)$, $K_j=F_j^{-1}\left(y\right)$. 先证 $\mathrm{dist}_H\left(K_j,K\right)\to0$. 一方面, 若 $x\in{K}$, 则 $F_j\left(x\right)\to{F}\left(x\right)=y$, 故 $\mathrm{dist}\left(x,K_j\right)\to0$ 一致于 $x\in{K}$: 用 $\left\|F_j-F\right\|_\infty\to0$ 得 $F_j\left(x\right)\in{B}\left(y,\varepsilon\right)$, 即 $x\in{F}_j^{-1}\left(B\left(y,\varepsilon\right)\right)$; 由 $F_j$ 连续与 $X$ 紧, 存在 $\delta$ 使 $F_j^{-1}\left(B\left(y,\varepsilon\right)\right)\subset{N}_\delta\left(K_j\right)$. 另一方面, 若某个 $x_j\in{K}_j$ 满足 $\mathrm{dist}\left(x_j,K\right)\ge\varepsilon$, 沿子列 $x_{j'}\to{x}$ 得 $F\left(x\right)=y$ 即 $x\in{K}$, 与 $\mathrm{dist}\left(x,K\right)\ge\varepsilon$ 的连续性矛盾度为 $0$, 矛盾.

故 $\left(K_j\right)$ 依豪斯多夫距离收敛到 $K$. 每个 $K_j$ 非空紧连通, 而紧集在豪斯多夫距离下的极限仍连通: 若极限 $K$ 有分离 $K=U\sqcup{V}$ (相对开, 不交, 非空), 取 $U,V$ 的不交邻域, 则大 $j$ 时 $K_j\subset{U}\cup{V}$ 且 $K_j$ 与两者都相交, 与 $K_j$ 连通矛盾. 故 $F$ 的每根纤维连通, $F$ 拓扑单调.

$\blacksquare$

> (2) 的证明只用了一条: 纤维连通使 $\varphi$ 在每根纤维上取定一个值, 而满射加紧性使这个值不能跳.

## 12.29 (2025 卷 B 题二: 处处有限次归零的线性映射)

设 $X$ 是巴拿赫空间 (**定义 6.21 (巴拿赫空间)**), $f:X\to{X}$ 连续线性, 且对每个 $x\in{X}$ 存在 $n\in\mathbb{N}$ 使 $f^n\left(x\right)=0$, 其中 $f^n$ 是 $n$ 次复合.

(1) 证明 $F_n=\left\{x\in{X}:f^n\left(x\right)=0\right\}$ 是 $X$ 的闭子空间;

(2) 证明存在 $N$ 使 $F_N$ 有内点;

(3) 证明第 (2) 小题中的 $F_N$ 一定是 $X$;

(4) 证明 $f$ 是幂零映射, 即存在 $N$ 使 $f^N=0$;

(5) 讨论多项式空间 $\mathbb{R}\left[X\right]$ 上的求导算子 $P\mapsto{P}'$, 说明它与上述结论的关系.

2025 卷 B 题二.

### 解答 12.29

(1) $F_n=\ker\left(f^n\right)$. $f^n$ 是连续线性映射 (有限次复合), 故 $F_n$ 是闭子空间: 线性显然; 闭由**定义 3.21 (闭集)** 与连续性, $\ker$ 是闭集 $\left\{0\right\}$ 的原像. 又 $F_1\subset{F}_2\subset\cdots$.

$\blacksquare$

(2) 由假设 $X=\bigcup_nF_n$. $\left(X,d\right)$ 完备, 由**定理 6.13 (贝尔纲定理)**, 可数个闭集覆盖完备空间时至少一个含内点. 故某 $F_N$ 含内点.

$\blacksquare$

(3) 若闭子空间 $F_N$ 含内点, 即含某开球 $B\left(x_0,r\right)$, 则对任意 $x\in{X}$ 与 $x\neq0$, 向量 $x_0+\frac{r}{2\left\|x\right\|}x\in{B}\left(x_0,r\right)\subset{F}_N$, 而 $x_0\in{F}_N$, 由线性得 $\frac{r}{2\left\|x\right\|}x\in{F}_N$, 故 $x\in{F}_N$. 于是 $F_N=X$.

$\blacksquare$

(4) $F_N=X$ 即 $f^N\left(x\right)=0$ 对一切 $x$ 成立, 故 $f^N=0$, $f$ 幂零.

$\blacksquare$

(5) 在 $\mathbb{R}\left[X\right]$ (不带范数, 或任何使它不成为巴拿赫空间的度量) 上取求导 $D\left(P\right)=P'$. 每个 $P$ 都有 $D^{m}\left(P\right)=0$ 只要 $m>\deg{P}$: 逐点有限次归零成立. 但 $D$ 不幂零: 对任意 $m$, $X^{m}$ 的 $m$ 次导数非零, 故 $D^m\neq0$. 与 (1)-(4) 对照, 差别只在 $\mathbb{R}\left[X\right]$ 不完备: $\mathbb{R}\left[X\right]=\bigcup_nF_n$ 时 $F_n$ 都是真闭子空间, 但没有一个有内点, 贝尔纲定理恰好失效.

$\blacksquare$

> 结论的实质: "逐点有限次" 到 "一致有限次" 的跳跃正是贝尔纲, 代价是完备性; 求导算子是多形式幂级数不适合这个跳跃的标准反例.
