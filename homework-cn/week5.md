# week5

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.15 (拓扑基)**
> 
> 设 $\mathcal{B}\subset\mathcal{P}\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $B_1,B_2\in\mathcal{B}$ 与任意 $x\in{B}_1\cap{B}_2$ 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_1\cap{B}_2$, 则以 $\mathcal{B}$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{X}$ 是开的当且仅当 $U\in{T}$. 我们要求:
> 
> (1) $\emptyset,X\in{T}$;
> 
> (2) 若 $U,V\in{T}$, 则 $U\cap{V}\in{T}$;
> 
> (3) 若 $A\subset{T}$, 则 $\bigcup{A}\in{T}$. (教材 $\S3$, p12)

> **定义 3.20 (边界)**
> 
> $\partial{A}=\overline{A}\setminus\operatorname{int}\left(A\right)$. 等价地, $\partial{F}=F\cap\overline{E\setminus{F}}$ 当 $F\subset{E}$ 闭. (教材 §3)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{X}$ 是闭的, 若 $X\setminus{F}$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{Y}$ 是连续的, 若对所有开集 $U\subset{Y}$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.26 (闭包)**
> 
> 集合 $A\subset{X}$ 的闭包 $\overline{A}$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **定义 3.33 ($T_1$ 空间)**
> 
> 单点集皆闭; 豪斯多夫空间必为 $T_1$ 空间. (教材 §3)

> **定理 4.1 (区间连通)**
> 
> $\left[0,1\right]$ 连通; 由此任意区间连通. (教材 §4, p23; "拓扑学"(原书第2版) §24 推论 24.2)

> **定理 4.2 (连续像连通)**
> 
> $X$ 连通, $f:X\to{Y}$ 连续, 则 $f\left(X\right)$ 连通. (教材 §4, p23)

> **定理 4.3 (路径连通蕴含连通)**
> 
> 路径连通空间是连通的. (教材 §4, p24)

> **定理 4.6 (扇形连通)**
> 
> 一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 §4, p26)

> **定理 4.7 (乘积连通)**
> 
> 连通集 $A,B$ 之积 $A\times{B}$ 连通; 有限个连通集的乘积连通. (教材 §4, p26 推论 4.7)

> **定义 4.9 (局部连通)**
> 
> 每点有由连通邻域组成的邻域基. (题集 §2.1)

> **定义 4.11 (弗斯滕伯格拓扑)**
> 
> $\mathbb{Z}$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb{Z}+b=\left\{an+b:n\in\mathbb{Z}\right\}$ ($a\neq0$) 为基的拓扑; $S\left(a,b\right)$ 既开又闭. (题集 §2.2)

> **定义 4.12 (戈洛姆拓扑)**
> 
> $\mathbb{Z}_{>0}$ 上以 $\left\{an+b:n\in\mathbb{N}\right\}$ ($a,b$ 互素) 为基的拓扑. (题集 §2.2)

> **定义 4.13 (基尔希拓扑)**
> 
> $\mathbb{Z}_{>0}$ 上以 $\left\{pn+b:n\in\mathbb{N}\right\}$ ($p$ 为素数且 $p\nmid{b}$) 为基的拓扑. (题集 §2.2)

> **定义 4.14 ($\varepsilon$-链空间)**
> 
> $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in{X}$ 可由相邻距离 $<\varepsilon$ 的有限点列连接; 对一切 $\varepsilon>0$ 都成立称全链. (题集 §4.5 C5)

> **定理 4.15 (闭包保持连通性)**
> 
> 连通集的闭包仍连通. (教材 §4, p27)

> **定理 4.16 (谢尔宾斯基同胚定理)**
> 
> 任意两个无孤立点的可数可度量化空间互相同胚. (题集 §2.2)

> **定义 4.18 (连通空间)**
> 
> $X$ 不能写成两个非空不相交开集之并; 子集 $A\subset{X}$ 连通指其在子空间拓扑下连通. (教材 §4, p23)

> **定义 4.19 (既开又闭集)**
> 
> 既开又闭的集合称为既开又闭集; $X$ 连通当且仅当 $\emptyset$ 与 $X$ 是仅有的既开又闭集. (教材 §4, p23)

> **定义 4.20 (完全不连通)**
> 
> 空间的唯一连通子集是单点集. (教材 §4, p23)

> **定义 4.22 (路径连通)**
> 
> 任意 $x,y\in{X}$ 有连续路径 $\gamma:\left[0,1\right]\to{X}$ 以 $x,y$ 为端点. (教材 §4, p24)

> **定义 4.24 (拓扑学家正弦曲线)**
> 
> $y=\sin\left(1/x\right)$ 在 $\left(0,1\right]$ 上的图像与 $y$ 轴上 $\left[-1,1\right]$ 的并; 它连通但不路径连通. (教材 §4, p24)

> **定理 5.4 (闭子集紧)**
> 
> 若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset{X}$ 也紧致. (教材 $\S5$)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定义 6.36 (开球)**
> 
> 开球 $B\left(x,r\right)=\left\{y\in{X}:d\left(x,y\right)<{}r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 7.7 (正则空间)**
> 
> 闭集 $A$ 与不在 $A$ 中的点有不相交开邻域. (教材 §7)

> **定理 24.3 (介值定理)**
> 
> 设 $f:X\to{Y}$ 连续, $X$ 连通, $Y$ 为序拓扑全序集; 若 $r$ 介于 $f\left(a\right)$ 与 $f\left(b\right)$ 之间, 则存在 $c\in{X}$ 使 $f\left(c\right)=r$. 特别地, 连续函数在区间上取到中间值. ("拓扑学"(原书第2版) §24 定理 24.3, p118)

> **定理 34.1 (乌雷松度量化定理)**
> 
> 每一个具有可数基的正则空间都是可度量化的. ("拓扑学"(原书第2版) §34 定理 34.1, p165; 教材 §7 定理 7.3, p43 表述为正规空间加可数基可度量化, 而正则加可数基蕴含正规)

## 5.1 (拓扑学家正弦曲线连通但不路径连通)

证明拓扑学家正弦曲线连通但不路径连通.

题集 §2.3 Q3.

### 解答 5.1

记

$$
G=\left\{\left(x,\sin\frac1x\right):0<{}x\le1\right\},\quad{L}=\left\{0\right\}\times\left[-1,1\right],\quad{S}=G\cup{L}.
$$

由**定义 4.24 (拓扑学家正弦曲线)**, $S$ 即拓扑学家正弦曲线.

先证连通. $G$ 以 $x$ 为参数路径连通, 故由**定理 4.3 (路径连通蕴含连通)** $G$ 连通. 当 $x\to0^{+}$ 时 $\sin\left(1/x\right)$ 在 $\left[-1,1\right]$ 上稠密振荡, 故 $G$ 的闭包 $\overline{G}=G\cup{L}=S$ (**定义 3.26 (闭包)**). 由**定理 4.15 (闭包保持连通性)**, $\overline{G}$ 连通, 故 $S$ 连通 (**定义 4.18 (连通空间)**).

再证不路径连通. 反设存在路径 $\gamma:\left[0,1\right]\to{S}$ 以 $\left(0,0\right)\in{L}$ 为起点, 以 $\left(1,\sin1\right)\in{G}$ 为终点. 令 $t_0=\inf\left\{t:\gamma\left(t\right)\text{~的横坐标}>0\right\}$. 由连续性 $\gamma\left(t_0\right)\in{L}$. 取 $t_n\downarrow{t}_0$, 则 $\gamma\left(t_n\right)=\left(x_n,\sin\left(1/x_n\right)\right)$, $x_n\to0^{+}$. 序列 $\sin\left(1/x_n\right)$ 既有收敛到 $1$ 的子列, 又有收敛到 $-1$ 的子列, 不可能收敛到 $\gamma\left(t_0\right)$ 的纵坐标, 与 $\gamma$ 连续矛盾. 故不存在这样的路径, $S$ 不路径连通, 即它不是**定义 4.22 (路径连通)** 意义下的路径连通空间. $\blacksquare$

## 5.2 (连通等价于到两点空间的连续映射常值, 以及乘积去方块后的连通性)

连通性与连续函数. 证明: $X$ 是**定义 4.18 (连通空间)** 当且仅当一切连续映射 $f:X\to\left\{0,1\right\}$ (目标装备离散拓扑) 都是常值的. 再设 $A,B$ 是两个连通度量空间, $X,Y$ 分别是 $A,B$ 的真子集. 证明 $C=\left(A\times{B}\right)\setminus\left(X\times{Y}\right)$ 是 $A\times{B}$ 的连通子集.

题集 §4.5 C3.

### 解答 5.2

($\Rightarrow$) 设 $X$ 是**定义 4.18 (连通空间)**, $f:X\to\left\{0,1\right\}$ 连续. 由**定理 4.2 (连续像连通)**, $f\left(X\right)$ 连通; 离散两点集 $\left\{0,1\right\}$ 的连通子集只有单点, 故 $f\left(X\right)$ 是单点集, 即 $f$ 常值.

($\Leftarrow$) 若 $X$ 不连通, 则 $X=U\cup{V}$, $U,V$ 非空不相交开集. 定义 $f$ 在 $U$ 上取 $0$, 在 $V$ 上取 $1$; 因 $U,V$ 既开又闭, 由**定义 3.22 (连续映射)** $f$ 连续, 但 $f$ 非常值. 矛盾.

第二问: $C=\left(\left(A\setminus{X}\right)\times{B}\right)\cup\left(A\times\left(B\setminus{Y}\right)\right)$. 因 $X,Y$ 是真子集, 可取 $a_0\in{A}\setminus{X}$, $b_0\in{B}\setminus{Y}$. 固定 $b_0$, 集合 $A\times\left\{b_0\right\}$ 由**定理 4.7 (乘积连通)** 连通. 对每个 $a\in{A}\setminus{X}$, 集合 $\left\{a\right\}\times{B}$ 连通 (**定理 4.7 (乘积连通)**), 且与 $A\times\left\{b_0\right\}$ 交于 $\left(a,b_0\right)$. 由**定理 4.6 (扇形连通)**, $S=A\times\left\{b_0\right\}\cup\bigcup_{a\in{A}\setminus{X}}\left\{a\right\}\times{B}$ 连通. 再对每个 $b\in{B}\setminus{Y}$, 集合 $A\times\left\{b\right\}$ 连通, 且与 $S$ 交于 $\left(a_0,b\right)$. 再用**定理 4.6 (扇形连通)**, 加入所有 $A\times\left\{b\right\}$ 后仍连通, 所得正是 $C$. $\blacksquare$

## 5.3 (边界连通蕴含闭集连通 (附闭性不可少的反例))

连通性与边界. 设 $E$ 是连通度量空间, $F$ 是 $E$ 的闭集. 证明: 若 $F$ 的边界 $\partial{F}$ 连通, 则 $F$ 连通. 再举例说明 $F$ 不假设闭时结论失效.

题集 §4.5 C4; 题集 §5.1 C18 同题.

### 解答 5.3

反设 $F$ 不连通. 则 $F$ 有非空分离 $F=A\cup{B}$, $A,B$ 非空不相交, 且在 $F$ 中既开又闭. 因 $F$ 在 $E$ 中闭, 由**定义 3.21 (闭集)**, $A,B$ 在 $E$ 中也闭. 由**定义 3.20 (边界)**, $\partial{F}=F\cap\overline{E\setminus{F}}$. 断言

$$
\partial{F}=\left(A\cap\overline{E\setminus{F}}\right)\cup\left(B\cap\overline{E\setminus{F}}\right),
$$

两边都非空. 若 $A\cap\overline{E\setminus{F}}=\emptyset$, 则 $A\subset\operatorname{int}\left(F\right)$; 又 $A$ 在 $F$ 中开, 即 $A=F\cap{O}$ ($O$ 开于 $E$), 于是 $A=O\cap\operatorname{int}\left(F\right)$ 在 $E$ 中开. $A$ 在 $E$ 中既开又闭, 由**定义 4.19 (既开又闭集)**, $E$ 连通推出 $A=\emptyset$ 或 $E$, 与 $A$ 是 $F$ 的非空真子集矛盾. 故 $A\cap\overline{E\setminus{F}}\neq\emptyset$, 同理 $B\cap\overline{E\setminus{F}}\neq\emptyset$. 这两个非空不交闭集分离了 $\partial{F}$, 与 $\partial{F}$ 连通矛盾. 故 $F$ 连通.

反例: 取 $E=\left[0,1\right]$, $F=\left[0,1/2\right)\cup\left(1/2,1\right]$. $F$ 不闭, 且不连通; 但 $\partial{F}=\left\{1/2\right\}$ 是单点, 连通. $\blacksquare$

## 5.4 ($\varepsilon$-链空间: 连通蕴含链性, 紧且链性蕴含连通)

链空间. 称度量空间 $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in{X}$ 可由有限点列 $x_0=a,\dots,x_n=b$ 连接使 $d\left(x_i,x_{i+1}\right)<\varepsilon$; 对一切 $\varepsilon>0$ 都成立称**定义 4.14 ($\varepsilon$-链空间)**. 证明: $X$ 连通则 $X$ 是 $\varepsilon$-链空间; $X$ 紧且 $\varepsilon$-链则 $X$ 连通; 举例说明 $\varepsilon$-链空间可以不连通.

题集 §4.5 C5.

### 解答 5.4

连通 $\Rightarrow$ $\varepsilon$-链: 固定 $\varepsilon>0$, 定义 $a\sim{b}$ 为存在 $\varepsilon$-链. 等价类在**定义 6.36 (开球)** $B\left(x,\varepsilon\right)$ 下封闭, 故每个等价类开; 其余等价类之并也开. 由**定义 4.19 (既开又闭集)**, 连通空间只有一个等价类, 即 $X$ 是**定义 4.14 ($\varepsilon$-链空间)**.

紧且 $\varepsilon$-链 $\Rightarrow$ 连通: 反设 $X$ 不连通, 则 $X=A\cup{B}$ 为非空不交闭集分离. 因 $X$ 紧, $A,B$ 是闭子集, 由**定理 5.4 (闭子集紧)** 它们紧. 距离 $\delta=d\left(A,B\right)>0$: 取 $a_n\in{A}$, $b_n\in{B}$ 使 $d\left(a_n,b_n\right)\to\delta$, 由**定理 6.1 (紧 $=$ 序列紧)** 抽子列 $a_{n_j}\to{a}\in{A}$, $b_{n_j}\to{b}\in{B}$, 若 $\delta=0$ 则 $d\left(a,b\right)=0$, 即 $a=b$, 与 $A\cap{B}=\emptyset$ 矛盾, 故 $\delta>0$. 取 $\varepsilon<\delta$, 则 $\varepsilon$-链不可能从 $A$ 跨到 $B$, 与 $\varepsilon$-链矛盾.

$\varepsilon$-链但不连通的例子: 有理数集 $\mathbb{Q}$ 装备通常度量. 对任意 $\varepsilon>0$, 任意两个有理数之间可插入间距小于 $\varepsilon$ 的有理点列, 故 $\mathbb{Q}$ 是 $\varepsilon$-链的; 但 $\mathbb{Q}$ 完全不连通. $\blacksquare$

## 5.5 (自映射皆有不动点蕴含连通, 而紧连通不足)

不动点与连通性. 设 $X$ 是度量空间, 假设一切连续映射 $f:X\to{X}$ 都有不动点. 证明 $X$ 连通. 再问: 若 $X$ 紧且连通, 是否一切连续映射 $f:X\to{X}$ 都有不动点?

题集 §4.5 C6.

### 解答 5.5

反设 $X$ 不连通, 则 $X=A\cup{B}$, $A,B$ 非空不相交且由**定义 4.19 (既开又闭集)** 既开又闭. 取 $a\in{A}$, $b\in{B}$, 定义 $f$: 在 $A$ 上取常值 $b$, 在 $B$ 上取常值 $a$. 因 $A,B$ 既开又闭, 由**定义 3.22 (连续映射)** $f$ 连续; 但 $f\left(A\right)\subset{B}$, $f\left(B\right)\subset{A}$, 而 $A\cap{B}=\emptyset$, 故 $f$ 无不动点. 矛盾. 故 $X$ 连通.

不一定. 紧且连通不足以保证不动点: 取圆周 $X=S^1$, 旋转 $90^\circ$ 的映射 $f\left(e^{i\theta}\right)=e^{i\left(\theta+\pi/2\right)}$. $S^1$ 紧且连通, $f$ 连续, 但 $f$ 无不动点. $\blacksquare$

> 紧与连通只能保证空间是连在一起的, 而不动点与空间的自同胚相关, 这是两件事.

## 5.6 (周期连续函数的中点等值问题)

设 $f:\left[0,1\right]\to\mathbb{R}$ 是一个连续函数并且 $f\left(0\right)=f\left(1\right)$.

(1) (10 分) 证明存在 $x\in\left[0,\frac12\right]$ 使得 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) (10 分) 证明对于任意的整数 $n\ge2$, 存在 $x\in\left[0,1-\frac1n\right]$ 使得 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) (5 分) 证明存在一个连续函数 $f:\left[0,1\right]\to\mathbb{R}$ 使得对于任意的 $x\in\left[0,\frac35\right]$ 都有 $f\left(x\right)\neq{f}\left(x+\frac25\right)$.

卷 B 题一.

### 解答 5.6

(1) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac12\right)$, 定义域 $\left[0,\frac12\right]$. 若 $g\left(0\right)=0$, 则 $x=0$ 已满足. 否则

$$
g\left(\frac12\right)=f\left(\frac12\right)-f\left(1\right)=f\left(\frac12\right)-f\left(0\right)=-g\left(0\right),
$$

故 $g\left(0\right)$ 与 $g\left(\frac12\right)$ 异号. 由**定理 24.3 (介值定理)**, 存在 $x\in\left[0,\frac12\right]$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac12\right)$.

(2) 令 $g\left(x\right)=f\left(x\right)-f\left(x+\frac1n\right)$, 定义域 $\left[0,1-\frac1n\right]$. 累加得

$$
\sum_{j=0}^{n-1}g\left(\frac{j}{n}\right)=\sum_{j=0}^{n-1}\left(f\left(\frac{j}{n}\right)-f\left(\frac{j+1}{n}\right)\right)=f\left(0\right)-f\left(1\right)=0.
$$

若 $g$ 在 $\left[0,1-\frac1n\right]$ 上恒不为 $0$, 因该区间连通 (由**定理 4.1 (区间连通)**), 连续函数 $g$ 的像由**定理 4.2 (连续像连通)** 是 $\mathbb{R}$ 中不含 $0$ 的连通集, 故必恒正或恒负, 从而各 $g\left(\frac{j}{n}\right)$ 同号, 其和不为 $0$, 矛盾. 故存在 $x$ 使 $g\left(x\right)=0$, 即 $f\left(x\right)=f\left(x+\frac1n\right)$.

(3) 取 $f\left(x\right)=x$. 它连续, 且对任意 $x\in\left[0,\frac35\right]$, $f\left(x+\frac25\right)-f\left(x\right)=\frac25\neq0$, 故 $f\left(x\right)\neq{f}\left(x+\frac25\right)$. 此例即满足要求. $\blacksquare$

> 这说明, 当步长为 $1/n$ 时能取等, 不是 $1/n$ 则不一定.
> 
> $1/n$ 特殊的原因在于其经过有限次求和后为 $1$, 因此可以利用望远镜级数, 最终求和得到 $f\left(0\right)-f\left(1\right)=0$, 即第 2 问的证明过程.

## 5.7 (2024 卷 C 题一: 贝尔纲定理, 球面与双曲面的连通性, 开子空间的完备化)

本大题各小问相互独立.

(1) 叙述贝尔纲定理的一个版本;

(2) 证明球面 $S^2=\left\{\left(x,y,z\right)\in\mathbb{R}^3:x^2+y^2+z^2=1\right\}$ 连通, 而曲面 $H^2=\left\{\left(x,y,z\right)\in\mathbb{R}^3:x^2+y^2-z^2=-1\right\}$ 不连通;

(3) 设 $\left(X,d\right)$ 是完备度量空间, $F\subset{X}$ 是闭子空间. 证明 $\left(F,d\right)$ 完备; 再证明当 $O\subset{X}$ 是开子空间时 $\left(O,d\right)$ 不必完备;

(4) 设 $\left(X,d\right)$ 是完备度量空间, $O\subset{X}$ 开. 证明存在 $O$ 上由 $d$ 诱导的度量 $d'$, 使 $\left(O,d'\right)$ 完备.

2024 卷 C 题一.

### 解答 5.7

(1) 完备度量空间中可数个稠密开集之交仍稠密; 等价地, 可数个无处稠密闭集之并不含非空开集. 这正是**定理 6.13 (贝尔纲定理)** 的陈述.

(2) 记 $S^2_+=\left\{z\ge0\right\}\cap{S}^2$, $S^2_-=\left\{z\le0\right\}\cap{S}^2$, $D=\left\{\left(x,y\right):x^2+y^2\le1\right\}$. 投影 $\left(x,y,z\right)\mapsto\left(x,y\right)$ 在 $S^2_+$ 上是到 $D$ 的双射, 其逆为 $\left(x,y\right)\mapsto\left(x,y,\sqrt{1-x^2-y^2}\right)$, 由**定义 3.22 (连续映射)** 两者都连续 (根号在 $D$ 上连续), 故 $S^2_+$ 同胚于 $D$. 而 $D$ 是 $\mathbb{R}^2$ 中的凸集, 由**定义 4.18 (连通空间)** 与**定理 4.1 (区间连通)** 的一般形式, 凸集连通: 任意两点可由线段连接, 线段是闭区间的连续像. 故 $S^2_+$ 连通; 同理 $S^2_-$ 连通. 二者之交 $S^2_+\cap{S}^2_-=\left\{z=0\right\}\cap{S}^2$ 是赤道, 非空. 两个有公共点的连通集之并连通, 故 $S^2$ 连通.

$H^2$ 上 $z^2=x^2+y^2+1\ge1$, 故 $\left|z\right|\ge1$. 令 $A=H^2\cap\left\{z\ge1\right\}$, $B=H^2\cap\left\{z\le-1\right\}$. 二者非空, 不交, 并为 $H^2$, 且都是 $H^2$ 中相对闭集 (分别是闭集 $\left\{z\ge1\right\}$ 与 $\left\{z\le-1\right\}$ 与 $H^2$ 之交). 由**定义 4.18 (连通空间)**, $H^2$ 不连通, 它恰有两个连通分支 $A,B$.

(3) 设 $\left(x_n\right)$ 是 $F$ 中的柯西列. 它在 $X$ 中柯西, 由 $X$ 完备收敛到某 $x\in{X}$. 因 $F$ 闭, 由**定义 3.21 (闭集)** $x\in{F}$. 故 $F$ 中每个柯西列在 $F$ 中收敛, $\left(F,d\right)$ 完备.

开而不完备的例子: $X=\mathbb{R}$ 带通常度量, $O=\left(0,1\right)$. 列 $x_n=1/n$ 在 $O$ 中柯西, 若在 $O$ 中收敛到 $x\in\left(0,1\right)$, 则在 $\mathbb{R}$ 中也收敛到 $x$, 而它在 $\mathbb{R}$ 中收敛到 $0\notin{O}$, 矛盾. 故 $\left(O,d\right)$ 不完备.

(4) 由**定义 6.46 (点到集合的距离)**, 令 $\varphi\left(x\right)=1/d\left(x,X-O\right)$, 它在 $O$ 上连续且为正: 因 $X-O$ 闭, $d\left(x,X-O\right)>0$ 对 $x\in{O}$ 成立. 令 $d'\left(x,y\right)=d\left(x,y\right)+\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$. 它是 $O$ 上的度量: 正定与对称显然, 三角不等式由 $d$ 与绝对值各自的三角不等式相加得到.

作嵌入 $f:O\to{X}\times\mathbb{R}$, $f\left(x\right)=\left(x,\varphi\left(x\right)\right)$. 由**定义 3.22 (连续映射)**, $f$ 连续. 且 $d'\left(x,y\right)$ 正是 $X\times\mathbb{R}$ 上乘积度量 $d+\left|\cdot\right|$ 沿 $f$ 的拉回, 故 $f$ 是 $O$ 到 $f\left(O\right)$ 的等距.

证 $f\left(O\right)$ 在 $X\times\mathbb{R}$ 中闭. 设 $f\left(x_k\right)\to\left(x,t\right)$. 则 $x_k\to{x}$ 且 $\varphi\left(x_k\right)\to{t}$. 若 $x\notin{O}$, 则 $x\in{X}-O$, 由**定义 6.46 (点到集合的距离)** $d\left(x_k,X-O\right)\le{d}\left(x_k,x\right)\to0$, 故 $\varphi\left(x_k\right)\to+\infty$, 与 $\varphi\left(x_k\right)\to{t}$ 矛盾. 故 $x\in{O}$, 从而 $\left(x,t\right)=f\left(x\right)\in{f}\left(O\right)$. 于是 $f\left(O\right)$ 闭.

$X\times\mathbb{R}$ 完备 (两个完备空间之积完备), 由第 (3) 小题 $f\left(O\right)$ 完备; $f$ 是等距, 故 $\left(O,d'\right)$ 完备. $\blacksquare$

> 度量 $d'$ 就是让 $O$ 上"逃向边界"的柯西列不再柯西, 代价是把边界推到无穷远.

## 5.8 (弗斯滕伯格拓扑的开集刻画与素数无穷)

在 $\mathbb{Z}$ 上以非平凡等差数列 $S\left(a,b\right)=a\mathbb{Z}+b=\left\{an+b:n\in\mathbb{Z}\right\}$ ($a\neq0$) 为基定义拓扑, 即**定义 4.11 (弗斯滕伯格拓扑)**.

(1) 证明 $U\subset\mathbb{Z}$ 开当且仅当对任意 $x\in{U}$, 存在某非零 $a\in\mathbb{Z}$ 使 $S\left(a,x\right)\subset{U}$;

(2) 验证这确实给出 $\mathbb{Z}$ 上的拓扑;

(3) 证明 $\mathbb{Z}$ 中非空有限集不能开; 特别地 $\mathbb{Z}-\left\{-1,1\right\}$ 不闭;

(4) 证明 $S\left(a,b\right)$ ($a\neq0$) 既开又闭;

(5) 证明对素数 $p$ 取并 $\bigcup_{p\in{P}}S\left(p,0\right)=\mathbb{Z}-\left\{-1,1\right\}$;

(6) 证明素数有无穷多个 (弗斯滕伯格的拓扑证明).

题集 §2.2 A1-A6; 2025 卷 A 题一 与之大面积重叠, 已合于此.

### 解答 5.8

(1) 由**定义 3.15 (拓扑基)**, 开集恰为若干 $S\left(a,b\right)$ 之并. 若 $U$ 开且 $x\in{U}$, 则 $x$ 含于某个并项 $S\left(a,b\right)\subset{U}$, 而 $x\in{S}\left(a,b\right)$ 等价于 $b\equiv{x}\pmod{a}$, 即 $S\left(a,b\right)=S\left(a,x\right)$. 故存在 $a\neq0$ 使 $S\left(a,x\right)\subset{U}$. 反过来, 若每点 $x\in{U}$ 都含某 $S\left(a,x\right)\subset{U}$, 则 $U=\bigcup_{x\in{U}}S\left(a_x,x\right)$ 是基元素之并, 故开.

(2) 先验证基条件. 这正是**定义 4.11 (弗斯滕伯格拓扑)** 的基. 两个基元素之交

$$
S\left(a,b\right)\cap{S}\left(c,d\right)=\left\{x:x\equiv{b}\pmod{a},x\equiv{d}\pmod{c}\right\}.
$$

它非空当且仅当 $b\equiv{d}\pmod{\gcd\left(a,c\right)}$; 此时交本身是一个以 $\operatorname{lcm}\left(a,c\right)$ 为步长的等差数列 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$. 故交含某基元素. 又 $S\left(1,0\right)=\mathbb{Z}$ 覆盖全空间. 由**定义 3.15 (拓扑基)**, 以此生成的开集族满足**定义 3.18 (拓扑空间)** 的全部公理: 任意并由生成方式保证, 有限交由基条件 (2) 保证, $\emptyset$ 与 $\mathbb{Z}$ 分别为空并与 $S\left(1,0\right)$.

(3) 任一基元素 $S\left(a,x\right)=\left\{an+x:n\in\mathbb{Z}\right\}$ 是无限集. 非空开集由第 (1) 小题必含某无限集 $S\left(a,x\right)$, 故它本身无限. 因而非空有限集不能开. 特别地 $\left\{-1,1\right\}$ 非空有限, 故不开; 由**定义 3.21 (闭集)**, 其补集 $\mathbb{Z}-\left\{-1,1\right\}$ 不闭.

(4) $S\left(a,b\right)$ 是基元素, 故开. 其补集

$$
\mathbb{Z}-S\left(a,b\right)=\bigcup_{r=1}^{a-1}S\left(a,b+r\right)
$$

是其余 $a-1$ 个模 $a$ 剩余类之并, 每个都是基元素, 故补集开. 由**定义 3.21 (闭集)**, $S\left(a,b\right)$ 闭. 故 $S\left(a,b\right)$ 既开又闭 (**定义 4.19 (既开又闭集)**).

(5) $S\left(p,0\right)=\left\{pn:n\in\mathbb{Z}\right\}$ 是 $p$ 的倍数全体. 整数 $n$ 被某素数整除当且仅当 $\left|n\right|\ge2$; $0$ 被一切素数整除; $\pm1$ 不被任何素数整除. 故

$$
\bigcup_{p\in{P}}S\left(p,0\right)=\mathbb{Z}-\left\{-1,1\right\}.
$$

(6) 反设素数只有有限个 $p_1,\dots,p_k$. 由第 (5) 小题,

$$
\bigcup_{i=1}^{k}S\left(p_i,0\right)=\mathbb{Z}-\left\{-1,1\right\}.
$$

由第 (4) 小题每个 $S\left(p_i,0\right)$ 既开又闭, 有限个既开又闭集之并仍既开又闭 (**定义 4.19 (既开又闭集)**). 故 $\mathbb{Z}-\left\{-1,1\right\}$ 既开又闭, 其补集 $\left\{-1,1\right\}$ 也既开又闭. 但由第 (3) 小题 $\left\{-1,1\right\}$ 非空有限, 不能开, 矛盾. 故素数有无穷多个. $\blacksquare$

## 5.9 (戈洛姆拓扑与基尔希拓扑的基约化)

在 $\mathbb{Z}_{>0}$ 上分别用 (非平凡) 等差数列 $a\mathbb{N}+b=\left\{an+b:n\in\mathbb{N}\right\}$ ($a,b$ 互素) 与 $p\mathbb{N}+b=\left\{pn+b:n\in\mathbb{N}\right\}$ ($p$ 为素数且 $p\nmid{b}$) 为基 (前者) 与子基 (后者) 定义两个拓扑.

(1) (戈洛姆) 证明基可限制到满足 $0\le{b}<{}a$ 且 $a,b$ 互素的偶对;

(2) (戈洛姆) 验证这确实给出 $\mathbb{Z}_{>0}$ 上的拓扑;

(3) (基尔希) 证明基可限制到满足 $0\le{b}<{}p$ 且 $p\nmid{b}$ 的偶对;

(4) (基尔希) 验证这确实给出 $\mathbb{Z}_{>0}$ 上的拓扑.

题集 §2.2 B1-B4.

### 解答 5.9

(1) 对基元素 $S\left(a,b\right)=\left\{an+b:n\in\mathbb{N}\right\}$, $\gcd\left(a,b\right)=1$. 作带余除法 $b=qa+r$, $0\le{r}<{}a$. 则 $\gcd\left(a,r\right)=\gcd\left(a,b\right)=1$, 且 $S\left(a,b\right)=\left\{a\left(n+q\right)+r:n\in\mathbb{N}\right\}\subset{S}\left(a,r\right)$. 反之, 对 $x=an_0+b\in{S}\left(a,b\right)$, $\gcd\left(a,x\right)=\gcd\left(a,an_0+b\right)=\gcd\left(a,b\right)=1$, 于是

$$
S\left(a,x\right)=\left\{an+x:n\in\mathbb{N}\right\}\subset\left\{b+am:m\ge{n}_0\right\}\subset{S}\left(a,b\right).
$$

故每点 $x$ 的邻域都可由满足 $0\le{r}<{}a$ 的基元素生成, 基可限制到 $0\le{b}<{}a$ 且互素的偶对.

(2) 验证基条件. $S\left(a,b\right)\cap{S}\left(c,d\right)$ 非空当且仅当 $\gcd\left(a,c\right)\mid\left(b-d\right)$; 此时交为 $S\left(\operatorname{lcm}\left(a,c\right),x_0\right)$, 且 $\gcd\left(\operatorname{lcm}\left(a,c\right),x_0\right)=1$. 它仍是**定义 4.12 (戈洛姆拓扑)** 的基元素. 又 $S\left(1,1\right)=\mathbb{Z}_{>0}$ 覆盖全空间. 由**定义 3.15 (拓扑基)** 与**定义 3.18 (拓扑空间)**, 这给出 $\mathbb{Z}_{>0}$ 上的拓扑.

(3) 对基尔希的 $S\left(p,b\right)=\left\{pn+b:n\in\mathbb{N}\right\}$, $p$ 素数, $p\nmid{b}$. 作带余除法 $b=qp+r$, $0\le{r}<{}p$, 则 $p\nmid{r}$ (否则 $p\mid{b}$), 且 $S\left(p,b\right)\subset{S}\left(p,r\right)$. 同第 (1) 小题, 对 $x=pn_0+b\in{S}\left(p,b\right)$ 有 $p\nmid{x}$, 故 $S\left(p,x\right)\subset{S}\left(p,b\right)$. 基可限制到 $0\le{b}<{}p$ 且 $p\nmid{b}$ 的偶对.

(4) 以 $\left\{S\left(p,b\right)\right\}$ 为子基, 其有限交

$$
S\left(p_1,b_1\right)\cap\cdots\cap{S}\left(p_k,b_k\right)
$$

由中国剩余定理 为 $\left\{x\equiv{b}_i\pmod{p_i}\right\}=S\left(M,x_0\right)$, 其中 $M=p_1\cdots{p}_k$, $p_i\nmid{x}_0$. 两个这样的有限交之交仍是同形的有限交. 故有限交全体构成一个基, 由**定义 3.15 (拓扑基)** 与**定义 3.18 (拓扑空间)** 生成 $\mathbb{Z}_{>0}$ 上的**定义 4.13 (基尔希拓扑)**. $\blacksquare$

## 5.10 (三种等差数列拓扑的豪斯多夫性, 正则性与连通性)

考察上述拓扑的拓扑性质.

(1) 证明弗斯滕伯格拓扑是豪斯多夫的且正则; 它可度量化但不可完备度量化, 实际上它与带通常子空间拓扑的有理数集 $\mathbb{Q}$ 同胚;

(2) 证明戈洛姆拓扑与基尔希拓扑是豪斯多夫的但不正则;

(3) 证明弗斯滕伯格拓扑完全不连通, 戈洛姆拓扑连通但不局部连通, 基尔希拓扑既连通又局部连通.

题集 §2.2 C1-C3.

### 解答 5.10

(1) 豪斯多夫: 取 $x\neq{y}$. 选非零 $a$ 使 $a>\left|x-y\right|$. 若 $S\left(a,x\right)\cap{S}\left(a,y\right)\neq\emptyset$, 则 $x+an=y+am$, 即 $a\left(n-m\right)=y-x$, 与 $a>\left|x-y\right|$ 矛盾. 故 $S\left(a,x\right)$ 与 $S\left(a,y\right)$ 不相交. 由**定义 3.10 (豪斯多夫空间)**, 弗斯滕伯格拓扑是豪斯多夫的. 由**定义 3.33 ($T_1$ 空间)**, 单点集皆闭.

正则: 设 $A$ 闭, $x\notin{A}$. 则 $\mathbb{Z}-A$ 是开集且含 $x$, 由习题 5.8 第 (1) 小题存在 $a\neq0$ 使 $S\left(a,x\right)\subset\mathbb{Z}-A$, 即 $S\left(a,x\right)\cap{A}=\emptyset$. 由习题 5.8 第 (4) 小题 $S\left(a,x\right)$ 既开又闭 (**定义 4.19 (既开又闭集)**), 且 $A\subset\mathbb{Z}-S\left(a,x\right)$, 后者开. 故 $x$ 与 $A$ 有不相交开邻域, 由**定义 7.7 (正则空间)** 弗斯滕伯格拓扑正则.

可度量化与同胚于 $\mathbb{Q}$: $\mathbb{Z}$ 可数, 故该拓扑有可数基; 由**定理 34.1 (乌雷松度量化定理)**, 有可数基的正则空间可度量化. 又该拓扑无孤立点: 每点 $x$ 的邻域 $S\left(a,x\right)$ 无限. 由**定理 4.16 (谢尔宾斯基同胚定理)**, 任意两个无孤立点的可数可度量化空间互相同胚, 故它与带通常子空间拓扑的 $\mathbb{Q}$ 同胚.

不可完备度量化: 反证法. 若它可完备度量化, 则同胚于它的 $\mathbb{Q}$ 也可完备度量化. 则 $\mathbb{Q}=\left\{q_1,q_2,\dots\right\}$. 对每一个 $q_n\in\mathbb{Q}$, 定义 $U_n=\mathbb{Q}-\left\{q_n\right\}$. 由于 $\left\{q_n\right\}$ 闭, 故 $U_n$ 开, $\left\{U_n\right\}$ 是一族可数稠密开集. 而 $\bigcap_{n=1}^\infty{U}_n=\bigcap_{n=1}^\infty\left(\mathbb{Q}-\left\{q_n\right\}\right)=\mathbb{Q}-\bigcap_{n=1}^\infty\left\{q_n\right\}=\mathbb{Q}-\mathbb{Q}=\emptyset$ 是空集, 与**定理 6.13 (贝尔纲定理)** 矛盾. 故它不可完备度量化.

(2) 豪斯多夫: 取 $x\neq{y}\in\mathbb{Z}_{>0}$. 选素数 $p$ 使 $p>\left|x-y\right|$ 且 $p\nmid{x}$, $p\nmid{y}$ (这样的素数存在, 因素数无穷). 则 $S\left(p,x\right)$ 与 $S\left(p,y\right)$ 分别是**定义 4.12 (戈洛姆拓扑)** 与**定义 4.13 (基尔希拓扑)** 的基元素; 若相交则 $p\mid\left(x-y\right)$, 与 $p>\left|x-y\right|$ 矛盾. 由**定义 3.10 (豪斯多夫空间)**, 两拓扑均豪斯多夫.

不正则: 以戈洛姆拓扑为例. 取闭集 $E$ 为全体偶正整数 (奇数集开: 对奇 $x$, $S\left(2,x\right)=\left\{x+2n\right\}$ 全奇且 $\gcd\left(2,x\right)=1$), 再取点 $1$. 点 $1$ 的任一邻域形如 $S\left(a,1\right)=\left\{1+an:n\in\mathbb{N}\right\}$, 而含偶数 $2$ 的任一开集必含某 $S\left(b,2\right)=\left\{2+bn:n\in\mathbb{N}\right\}$ ($\gcd\left(b,2\right)=1$, 即 $b$ 奇). 由同余式相容, $S\left(a,1\right)\cap{S}\left(b,2\right)$ 非空, 故无法用不相交开集分离 $1$ 与闭集 $E$. 由**定义 7.7 (正则空间)**, 戈洛姆拓扑不正则. 基尔希拓扑同理不正则.

(3) 弗斯滕伯格完全不连通: 取 $x\neq{y}$. 选 $a$ 使 $y\notin{S}\left(a,x\right)$. 由习题 5.8 第 (4) 小题 $S\left(a,x\right)$ 既开又闭且含 $x$ 不含 $y$, 故任何同时含 $x,y$ 的子集都被这个非平凡既开又闭集切断, 不能连通. 由**定义 4.20 (完全不连通)**, 弗斯滕伯格拓扑完全不连通.

戈洛姆连通: 设 $C$ 既开又闭且 $1\in{C}$. 由标准归纳 (取 $\mathbb{Z}_{>0}-C$ 中最小元 $n$, 由于开集 $C$ 必然含 $S\left(a,1\right)$, 可推出 $n\in{C}$), 得 $C=\mathbb{Z}_{>0}$. 故 $\mathbb{Z}_{>0}$ 仅有的既开又闭非空集是全空间, 由**定义 4.18 (连通空间)** 戈洛姆拓扑连通. 它不**定义 4.9 (局部连通)**: 点 $1$ 的任一邻域 $S\left(a,1\right)$ 都含非平凡既开又闭子集, 故没有连通邻域基.

基尔希连通且局部连通: 基尔希的基元素 $S\left(p,b\right)$ 本身在该拓扑下连通 (同理由既开又闭集归纳), 故每点有连通邻域, 由**定义 4.9 (局部连通)** 它局部连通; 又全空间仅有的既开又闭非空集是全空间, 由**定义 4.18 (连通空间)** 它连通. $\blacksquare$

> 三个拓扑的精细程度为: $\text{弗斯滕伯格}>\text{戈洛姆}>\text{基尔希}$, 因此 (3) 的结论从直觉上也是成立的. 具体说来, 基尔希连通且局部连通是最粗糙的例子, 因为 $S\left(A,B\right)$ 中的 $A$ 只能是不同素数的乘积, 这导致其局部无法再被分割, 因为找不到更细的 $S$ 了; 而戈洛姆不局部连通, 是因为 $S\left(A,B\right)$ 中的 $A$ 可以是素数的幂, 此时的选择更多, 可以找到更细的 $S$; 弗斯滕伯格不联通, 是因为 $S\left(A,B\right)$ 中的 $A$ 可以是任意数, 此时的选择最多, 以至于 $X$ 可以任意被分割.
