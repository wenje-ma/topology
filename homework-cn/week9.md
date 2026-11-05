# week9

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.11 (乘积拓扑)**
> 
> 设 $X,Y$ 为拓扑空间. $X\times{Y}$ 上的乘积拓扑以形如 $U\times{V}$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in{V}}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$, p17)

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

> **定义 3.25 (邻域与极限)**
> 
> $b\in{X}$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to{b}$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in{U}$. (教材 $\S3$, p16)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset{X}$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $x,y\in{K}$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.2 (区间紧)**
> 
> 区间 $\left[0,1\right]$ 是紧的. (教材 $\S5$)

> **定理 5.3 ($\mathbb{R}^n$ 中的紧集)**
> 
> $K\subset\mathbb{R}^n$ 紧当且仅当 $K$ 闭且有界. (教材 $\S5$)

> **定理 5.4 (闭子集紧)**
> 
> 若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset{X}$ 也紧致. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.7))

> **定理 5.9 (吉洪诺夫定理)**
> 
> 任意一族紧空间的乘积在乘积拓扑下紧. (教材 $\S5$)

> **定理 5.10 (有限交判据)**
> 
> $X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定理 5.11 (紧空间上连续函数取最大值)**
> 
> 紧致空间 $X$ 上的连续函数 $f:X\to\mathbb{R}$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

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

> **定理 6.7 (连续函数的一致极限连续)**
> 
> 连续函数列的一致极限连续, 即连续函数空间在有界函数空间中闭. (教材 $\S6$)

> **定理 6.8 ($C\left(X,Y\right)$ 完备)**
> 
> $Y$ 完备时 $C\left(X,Y\right)$ 装备一致度量后完备. (教材 $\S6$)

> **定理 6.12 (阿尔泽拉-阿斯科利定理)**
> 
> 设 $K$ 为紧度量空间, $F\subset{C}\left(K\right)$ 为等度连续且一致有界的函数族, 则 $F$ 是紧的. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定理 6.14 (递增闭集族)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 若为可数个闭集之并 $X=\bigcup_nF_n$, 则至少一个 $F_n$ 含非空开集. (教材 §6)

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

> **定义 6.21 (巴拿赫空间)**
> 
> 完备的赋范线性空间. (题集 §5)

> **定义 6.22 (绝对收敛级数)**
> 
> 级数 $\sum_nx_n$ 绝对收敛, 若 $\sum_n\left\|x_n\right\|<\infty$. (题集 §4.4)

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

> **定义 6.36 (开球)**
> 
> 开球 $B\left(x,r\right)=\left\{y\in{X}:d\left(x,y\right)<{}r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.37 (柯西列)**
> 
> 序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>{}N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38 (完备度量空间)**
> 
> 度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.39 (完备化)**
> 
> 任意度量空间可自然嵌入一个完备度量空间; 实数轴 $\mathbb{R}$ 是有理数集的完备化, 故 $\mathbb{R}$ 完备. (教材 $\S6$)

> **定义 6.41 (一致收敛与一致度量)**
> 
> $d\left(f,g\right)=\sup_{x\in{X}}\left|f\left(x\right)-g\left(x\right)\right|$; $f_n$ 一致收敛于 $g$ 当且仅当 $d\left(f_n,g\right)\to0$. (教材 §6)

> **定义 6.43 (上确界度量)**
> 
> 紧集 $K$ 上连续函数空间 $C\left(K\right)$ 装备 $d\left(f,g\right)=\sup_{x\in{K}}\left|f\left(x\right)-g\left(x\right)\right|$, 即上确界范数诱导的度量. (教材 $\S6$)

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
> $d\left(A,B\right)=\inf\left\{r>0:A\subset{U}_r\left(B\right),\,B\subset{U}_r\left(A\right)\right\}$; 在紧子集族 $\mathcal{K}\left(X\right)$ 上是真度量. (题集 $\S3.2$)

> **定义 6.49 (等距映射)**
> 
> 满足 $d_Y\left(f\left(x\right),f\left(y\right)\right)=d_X\left(x,y\right)$ 的映射 $f:X\to{Y}$. (题集 §3.4)

> **说明 6.50 (度量空间是豪斯多夫的)**
> 
> 度量空间 $X$ 是豪斯多夫的, 故极限唯一. (教材 $\S6$, p33)

> **定义 7.4 (局部紧空间)**
> 
> 设 $X$ 为豪斯多夫空间. 若 $X$ 有由紧集组成的基 $\left\{B\right\}$, 则称 $X$ 局部紧. 等价地, $X$ 在 $x$ 处局部紧, 若存在 $X$ 的紧子空间 $C$ 包含着 $x$ 的一个邻域; 每点如此则称 $X$ 局部紧. (教材 $\S7$, p44; 《拓扑学》(原书第2版) $\S29$)

> **定义 11.16 (无向图与子图)**
> 
> $G=\left(V,E\right)$, $E\subset{V}\times{V}$ 无序; 子图保持 $V$ 只删边. (题集 $\S3.3$)

> **定义 11.17 ($k$-染色与 $k$-可染色)**
> 
> $f:V\to\left\{1,\dots,k\right\}$ 使相邻点异色; 存在则称 $k$-可染色. (题集 $\S3.3$)

## 9.1 (序列收敛等价于唯一子列极限（附两个子列极限的轨道）)

(两个子列极限) 设 $K$ 是某**定义 6.20 (赋范线性空间)** 的紧子空间.

(1) 证明 $K$ 中序列收敛当且仅当它只有唯一子列极限;

(2) 设 $f:K\to{K}$ 连续, $x\in{K}$, 序列 $f^n\left(x\right)$ 恰有两个子列极限 $z_0,z_1$. 证明: 对 $z_0,z_1$ 的任意邻域 $V_0,V_1$, 序列最终落入 $V_0\cup{V}_1$; 并证明 $f\left(z_0\right)=z_1$, $f\left(z_1\right)=z_0$, 且 $f^{2k}\left(x\right)$ 与 $f^{2k+1}\left(x\right)$ 分别收敛到 $z_0,z_1$.

### 解答 6.10

(1) ($\Rightarrow$) 显然. ($\Leftarrow$) 设唯一子列极限为 $L$. 若序列不收敛到 $L$, 则存在 $\varepsilon>0$ 与子列恒在 $B\left(L,\varepsilon\right)$ 外; 由**定理 6.1 (紧 $=$ 序列紧)**, 该子列有收敛子列, 其极限异于 $L$, 矛盾. 故序列收敛到 $L$.

(2) 若序列不最终落入 $V_0\cup{V}_1$, 则有子列恒在 $V_0\cup{V}_1$ 外; 由紧性它有收敛子列, 其极限不在 $V_0\cup{V}_1$ 中, 即第三个子列极限, 矛盾.

$f$ 连续, 把子列极限映为序列 $f^{n+1}\left(x\right)$ 的子列极限, 而后者的子列极限集同为 $\left\{z_0,z_1\right\}$. 故 $f\left(z_0\right),f\left(z_1\right)\in\left\{z_0,z_1\right\}$. 若 $f\left(z_0\right)=z_0$, 则偶子列将只有一个子列极限, 与第 (1) 小题矛盾; 故 $f\left(z_0\right)=z_1$, 同理 $f\left(z_1\right)=z_0$. 于是 $f^{2k}\left(x\right)$ 恰在 $z_0$ 附近累积, $f^{2k+1}\left(x\right)$ 恰在 $z_1$ 附近累积, 由第 (1) 小题分别收敛到 $z_0,z_1$. $\blacksquare$

## 9.2 (紧度量空间中不减距离的连续自映射是等距且双射)

设 $E$ 是紧度量空间, $f:E\to{E}$ 连续, 且对一切 $x,y\in{E}$ 满足 $d\left(f\left(x\right),f\left(y\right)\right)\ge{d}\left(x,y\right)$.

(1) 证明 $f$ 实际上是**定义 6.49 (等距映射)**, 即 $d\left(f\left(x\right),f\left(y\right)\right)=d\left(x,y\right)$;

(2) 证明 $f$ 是双射. 可考虑 $\left(x_n,y_n\right)=\left(f^n\left(x\right),f^n\left(y\right)\right)$ 的子列;

(3) 最后证明: 若 $g:E\to{E}$ 是连续双射且 $d\left(g\left(x\right),g\left(y\right)\right)\le{d}\left(x,y\right)$ 对一切 $x,y$ 成立, 则 $g$ 也是**定义 6.49 (等距映射)**.

### 解答 6.11

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

### 解答 6.12

反设存在任意大的 $\varepsilon$-分离集. 则可取两两不同的点列 $x_m\in{K}$ 使 $m\neq{m}'$ 时 $\left|x_m-x_{m'}\right|>\varepsilon$. 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 与**定理 6.1 (紧 $=$ 序列紧)**, $\left(x_m\right)$ 有收敛子列; 收敛子列是**定义 6.37 (柯西列)**, 充分靠后两项距离 $<\varepsilon$, 与 $\varepsilon$-分离矛盾. 故存在 $M\left(\varepsilon\right)$.

满性: 反设 $f$ 不满, 取 $p\notin{f}\left(K\right)$. $f\left(K\right)$ 紧, 由**定理 5.3 ($\mathbb{R}^n$ 中的紧集)** 闭, 故 $\delta=d\left(p,f\left(K\right)\right)>0$. 轨道 $p,f\left(p\right),f^2\left(p\right),\dots$ 满足

$$
\left|f^{n+1}\left(p\right)-f^n\left(p\right)\right|=\left|f\left(f^n\left(p\right)\right)-f\left(f^{n-1}\left(p\right)\right)\right|=\left|f^n\left(p\right)-f^{n-1}\left(p\right)\right|\ge\cdots\ge\left|f\left(p\right)-p\right|\ge\delta,
$$

其中等号用了**定义 6.49 (等距映射)**. 但由**定理 6.1 (紧 $=$ 序列紧)**, $K$ 中轨道有收敛子列, 必为**定义 6.37 (柯西列)**, 与相邻项距离恒 $\ge\delta$ 矛盾. 故 $f$ 满. $\blacksquare$

## 9.4 (紧性三题：局部单射的扩张、里茨定理与蒂茨–乌雷松扩张)

(7.1 紧性)

(1) 设 $\left(E,d\right)$ 是度量空间, $f:E\to\mathbb{R}$ 连续, $K\subset{E}$ 紧. 假设 $f$ 在 $K$ 上单射, 且对每个 $x\in{K}$ 存在 $\varepsilon>0$ 使 $f$ 在 $B\left(x,\varepsilon\right)$ 上单射. 证明存在含 $K$ 的开集 $\Omega$ 使 $f$ 在 $\Omega$ 上单射.

(2) (里茨定理) 设 $E$ 是实无穷维赋范线性空间. 证明 $E$ 的闭单位球不能被有限个半径 $1$ 的开球覆盖.

(3) (蒂茨-乌雷松扩张定理) 设 $\left(E,d\right)$ 是度量空间, $A\subset{E}$ 闭, $f:A\to\mathbb{R}$ 连续有界. 证明存在连续 $g:E\to\mathbb{R}$, $g\big|_A=f$, 且

$$
\sup_{x\in{E}}g\left(x\right)=\sup_{x\in{A}}f\left(x\right),\quad
\inf_{x\in{E}}g\left(x\right)=\inf_{x\in{A}}f\left(x\right).
$$

### 解答 6.13

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

## 9.5 (2025 卷 B 题一：图染色的紧致性证明)

(2025 年卷 B 题目一, 50 分). 考虑一个无向图 $G$, 记 $V$ 为顶点集, $E$ 为边集. 称图 $G=\left(V,E\right)$ 的子图 $\widetilde{G}=\left(\widetilde{V},\widetilde{E}\right)$ 满足 $\widetilde{V}=V$ 且 $\widetilde{E}\subset{E}$. 一个图 $G$ 的 $k$-染色 ($k\ge2$) 指函数 $f:V\to\left\{1,\dots,k\right\}$ 使对任意边 $\left(x,y\right)\in{E}$ 都有 $f\left(x\right)\neq{f}\left(y\right)$. 称图是 $k$-可染色的若这种函数存在.

(0) 考虑 $\left\{1,\dots,k\right\}$ 上的离散拓扑. 证明在这个拓扑下 $\left\{1,\dots,k\right\}$ 是紧致的.

(1) 给定图 $G$. 记 $X$ 为所有从 $V$ 到 $\left\{1,\dots,k\right\}$ 的函数所成集合. 证明 $X=\left\{1,\dots,k\right\}^{\left|V\right|}$, 并且若 $\left\{1,\dots,k\right\}$ 赋予离散拓扑, 则 $X$ 在乘积拓扑下是紧致的. 对边集 $F\subset{E}$, 记 $X_F=\left\{f:V\to\left\{1,\dots,k\right\}:f\text{~是子图~}\left(V,F\right)\text{~的~}k\text{-染色}\right\}$.

(2) 证明如果 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 那么 $X_F$ 是闭的.

(3) 证明对于任意的 $F\subset{E}$, $X_F$ 都是闭的.

(4) 设图 $G$ 的所有有限子图都是 $k$-可染色的. 考虑 $\mathcal{F}=\left\{X_F:F\subset{E}\text{~有限}\right\}$. 证明 $\mathcal{F}$ 中有限个元素之交非空, 然后证明 $\mathcal{F}$ 中所有元素之交也非空.

(5) 证明德布鲁因-埃尔德什定理: 如果图 $G$ 的任意有限子图都是 $k$-可染色的, 那么 $G$ 也是 $k$-可染色的.

### 解答 6.14

(0) $\left\{1,\dots,k\right\}$ 是有限集. 任意开覆盖中, 每个点选一个覆盖元, 仅需 $k$ 个即可覆盖, 故由**定义 5.16 (紧致空间)** 它紧.

(1) $X=\prod_{v\in{V}}\left\{1,\dots,k\right\}=\left\{1,\dots,k\right\}^{\left|V\right|}$. 由第 (0) 小题每个因子 $\left\{1,\dots,k\right\}$ 紧, 由**定理 5.9 (吉洪诺夫定理)**, 乘积 $X$ 在乘积拓扑下紧.

(2) 单条边时, $X_{\left\{\left(x,y\right)\right\}}=\left\{f:f\left(x\right)\neq{f}\left(y\right)\right\}$. 其补集为

$$
X\setminus{X}_F=\bigcup_{c=1}^k\left\{f:f\left(x\right)=c,\,f\left(y\right)=c\right\}.
$$

每个集合是两个连续取值映射 ($f\mapsto{f}\left(x\right)$) 的纤维之交, 在离散拓扑下既开又闭, 故为闭集; 有限并闭. 因此补集闭, 由**定义 3.21 (闭集)**, $X_F$ 闭.

(3) $X_F=\bigcap_{\left(x,y\right)\in{F}}X_{\left\{\left(x,y\right)\right\}}$. 由第 (2) 小题每个 $X_{\left\{\left(x,y\right)\right\}}$ 闭, 闭集任意交仍闭 (由**定义 3.21 (闭集)** 对应拓扑公理), 故 $X_F$ 闭.

(4) 任取有限个 $F_1,\dots,F_m$, 则 $\bigcap_{i=1}^mX_{F_i}=X_{F_1\cup\dots\cup{F}_m}$. 因 $\bigcup_iF_i$ 有限, 由**定义 11.16 (无向图与子图)** 子图 $\left(V,\bigcup_iF_i\right)$ 是有限子图, 由题设它 $k$-可染色, 故 $X_{\cup{F}_i}$ 非空. 故 $\mathcal{F}$ 具有限交性质 (由**定义 5.17 (有限交性质)**). 又 $\mathcal{F}$ 中元素都是紧空间 $X$ 中的闭集, 由**定理 5.10 (有限交判据)**, 全族交 $\bigcap_{F\text{~有限}}X_F$ 非空.

(5) 取 $f\in\bigcap_{F\text{~有限}}X_F$. 由**定义 11.17 ($k$-染色与 $k$-可染色)**, $f$ 是子图 $\left(V,F\right)$ 的 $k$-染色对每个有限 $F$ 成立. 特别对任意边 $e\in{E}$, 取有限集 $F=\left\{e\right\}$, 则 $f\left(x\right)\neq{f}\left(y\right)$ 对该边成立. 故 $f$ 是整图 $G$ 的 $k$-染色, $G$ 可 $k$-染色. $\blacksquare$

## 9.6 (紧凸集上的严格压缩映射与紧度量空间上的不动点)

证明:

(1) 紧凸集 $K$ 上的严格压缩映射 (即 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ 对 $x\neq{y}$) 有不动点.

(2) 在巴拿赫不动点定理的条件中, 把完备度量空间换为紧度量空间, 结论仍成立.

### 解答 6.15

第 (1) 小题: 由**定义 4.23 (凸集)**, $K$ 凸. 由**定理 6.3 (紧度量空间完备)**, $K$ 完备. 在严格条件 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ ($x\neq{y}$) 下, 由 $K$ 紧 (由**定理 6.1 (紧 $=$ 序列紧)** 取最小距离对), 可推出 $f$ 实际上是**定义 6.19 (压缩映射)** 意义下的压缩映射 (存在统一的 $0<{}k<1$). 故由**定理 6.16 (巴拿赫不动点定理)**, $f$ 有不动点.

第 (2) 小题: 设 $X$ 紧度量, $f:X\to{X}$ 连续. 由紧性, $d\left(x,f\left(x\right)\right)$ 达到最小. 若最小值 $>0$, 则 $d\left(f\left(x\right),f^2\left(x\right)\right)<{}d\left(x,f\left(x\right)\right)$ (严格压缩), 与最小性矛盾. 故最小值为 $0$, 即存在 $x$ 使 $f\left(x\right)=x$. 紧度量空间豪斯多夫 (由**定义 3.10 (豪斯多夫空间)**, 度量空间豪斯多夫). $\blacksquare$

## 9.7 (紧凸集上连续仿射映射的不动点（角谷–马尔可夫定理）)

证明: 紧凸集到自身的连续仿射映射有不动点 (角谷-马尔可夫定理).

### 解答 6.16

设 $K\subset{E}$ 紧凸, $f:K\to{K}$ 连续仿射. 考虑 $K$ 的所有非空闭凸子集族, 它们在 $f$ 下不变. 由**定理 5.1 (紧空间连续像紧)** 与**定义 4.23 (凸集)**, $f$ 把闭凸集映为闭凸集. 由**定义 5.17 (有限交性质)** 与**定理 5.10 (有限交判据)**, 这些不变闭凸子集族具有有限交性质, 其交 $K_0$ 非空. 取 $K_0$ 为极小不变闭凸集. 由极小性, $f\left(K_0\right)=K_0$. 若 $K_0$ 多于一点, 由凸性与仿射性可进一步收缩, 矛盾. 故 $K_0$ 为单点 $\left\{x\right\}$, 即 $f\left(x\right)=x$. $\blacksquare$

## 9.8 (集合间下确界距离一般不是度量)

设 $\left(X,d\right)$ 是度量空间. 证明朴素定义 $d\left(A,B\right)=\inf_{a\in{A},\,b\in{B}}d\left(a,b\right)$ 一般不是度量.

### 解答 7.1

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

## 9.9 ($\varepsilon$-邻域的嵌套不等式)

定义集合 $A\subset{X}$ 的 $\varepsilon$-邻域 $U_\varepsilon\left(A\right)=\left\{x\in{X}:d\left(x,A\right)<\varepsilon\right\}$, 其中 $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. 证明: 对 $r_1,r_2>0$ 与任意 $A\subset{X}$,

$$
U_{r_1}\left(U_{r_2}\left(A\right)\right)\subset{U}_{r_1+r_2}\left(A\right),
$$

但反过来一般不成立.

### 解答 7.2

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

## 9.10 (豪斯多夫距离是伪距离)

定义子集 $A,B\subset{X}$ 之间的豪斯多夫距离

$$
d_H\left(A,B\right)=\inf\left\{r>0:A\subset{U}_r\left(B\right),\,B\subset{U}_r\left(A\right)\right\}.
$$

证明豪斯多夫距离是伪距离, 即满足度量的全部公理, 只是 $d_H\left(A,B\right)=0$ 不一定蕴含 $A=B$.

### 解答 7.3

由**定义 6.48 (豪斯多夫距离)**, 非负性与对称性是显然的 (定义关于 $A,B$ 对称). 又 $d_H\left(A,A\right)=0$, 因为对任意 $r>0$, $A\subset{U}_r\left(A\right)$ 恒成立.

剩证三角不等式. 设 $A,B,C\subset{X}$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,B\right)<{}r$ 意味着 $A\subset{U}_r\left(B\right)$ 且 $B\subset{U}_r\left(A\right)$. 若 $A\subset{U}_r\left(B\right)$ 且 $B\subset{U}_s\left(C\right)$, 由**习题 7.2**的包含关系 (**定义 6.47 ($\varepsilon$-邻域)**),

$$
A\subset{U}_r\left(B\right)\subset{U}_r\left(U_s\left(C\right)\right)\subset{U}_{r+s}\left(C\right).
$$

同理 $C\subset{U}_{r+s}\left(A\right)$. 由**定义 6.48 (豪斯多夫距离)**, $d_H\left(A,C\right)\le{r}+s$. 令 $r\downarrow{d}_H\left(A,B\right)$, $s\downarrow{d}_H\left(B,C\right)$, 即得三角不等式

$$
d_H\left(A,C\right)\le{d}_H\left(A,B\right)+d_H\left(B,C\right).
$$

由**定义 6.44 (伪距离)**, 它满足除"距离为零蕴含相等"外全部公理, 故是伪距离. $\blacksquare$

> $d_H\left(A,B\right)=0\not\Rightarrow{A}=B$: 取 $A=\left(0,1\right)$, $B=\left[0,1\right]$, $d_H\left(A,B\right)=0$ 但 $A\ne{B}$.

## 9.11 (闭集间豪斯多夫距离为零蕴含两集相等)

证明: 对一切 $A\subset{X}$, $d_H\left(A,A\right)=0$. 若 $A,B$ 闭, 则 $d_H\left(A,B\right)=0$ 蕴含 $A=B$.

### 解答 7.4

现设 $A,B$ 闭且 $d_H\left(A,B\right)=0$. 任取 $a\in{A}$. 对每个 $n$, 由**定义 6.48 (豪斯多夫距离)** 与 $d_H\left(A,B\right)=0$, 存在 $b_n\in{B}$ 使 $d_H\left(a,b_n\right)<1/n$. 于是 $b_n\to{a}$. 由**定义 3.21 (闭集)**, 闭集含其中序列的极限, 故 $a\in{B}$. 这证明 $A\subset{B}$. 交换 $A,B$ 同理得 $B\subset{A}$, 故 $A=B$. $\blacksquare$

## 9.12 (豪斯多夫距离限制在紧子集族上是真度量)

证明: 若把豪斯多夫距离限制在紧子集族 $\mathcal{K}\left(X\right)$ 上, 则它是 $\mathcal{K}\left(X\right)$ 上的真度量.

### 解答 7.5

由**习题 7.3**, $d_H$ 是伪距离, 已满足非负性, 对称性与三角不等式. 剩证分离性. 设 $A,B\in\mathcal{K}\left(X\right)$ 紧致且 $d_H\left(A,B\right)=0$. 度量空间是**定义 3.10 (豪斯多夫空间)**, 由**定理 5.5 (豪斯多夫中紧集闭)**, 紧集 $A,B$ 在 $X$ 中闭. 由**习题 7.4**的结论, $d_H\left(A,B\right)=0$ 且 $A,B$ 闭蕴含 $A=B$. 故分离性成立. $\blacksquare$
