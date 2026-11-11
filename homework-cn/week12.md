# week12 (((完备空间: 巴拿赫空间与贝尔纲)))

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

## 12.1 (复合映射的算子范数与 $E\cong{L}\left(\mathbb{K},E\right)$)

设 $E,F,G$ 是赋范域 $\mathbb{K}$ 上的拓扑向量空间. 对 $f\in{L}\left(E,F\right)$, 右复合映射 $R_f:L\left(F,G\right)\to{L}\left(E,G\right)$, $g\mapsto{g}\circ{f}$. 证明 $R_f$ 的算子范数不超过 $f$ 的算子范数; 左复合同理. 证明映射 $E\to{L}\left(\mathbb{K},E\right)$, $x\mapsto\left(\varphi_x:t\mapsto{t}x\right)$ 是等距线性同构.

题集 §5 Q15.

### 解答 12.1

由**定义 6.24 (拓扑向量空间)**, $E,F,G$ 的加法与数乘连续; 由**定义 6.20 (赋范线性空间)**, 其上装备范数, $L\left(E,F\right)$ 为连续线性映射全体.

右复合: 由**定义 6.28 (算子范数)**, 对 $g\in{L}\left(F,G\right)$ 与 $x\in{E}$, $g\circ{f}$ 作为复合映射由**定理 3.1 (复合连续)** 连续, 且

$$
\left\|g\circ{f}\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\right\|\cdot\left\|x\right\|.
$$

两边除以 $\left\|x\right\|$ 并取上确界, 得 $\left\|g\circ{f}\right\|\le\left\|g\right\|\left\|f\right\|$. 于是 $\left\|R_f\left(g\right)\right\|\le\left\|f\right\|\left\|g\right\|$, 即 $\left\|R_f\right\|\le\left\|f\right\|$.

左复合: 同理, $L_f:g\mapsto{f}\circ{g}$ ($g\in{L}\left(G,E\right)$, $f\in{L}\left(E,F\right)$), 有 $\left\|f\circ{g}\right\|\le\left\|f\right\|\left\|g\right\|$, 故 $\left\|L_f\right\|\le\left\|f\right\|$.

等距线性同构: 映射 $x\mapsto\varphi_x$, $\varphi_x\left(t\right)=tx$. 线性显然. 由**定义 6.28 (算子范数)**,

$$
\left\|\varphi_x\right\|=\sup_{\left\|t\right\|\le1}\left\|tx\right\|=\sup_{\left\|t\right\|\le1}\left|t\right|\cdot\left\|x\right\|=\left\|x\right\|.
$$

故等距. 它线性且保范数, 故单射; 满射: 任意 $\psi\in{L}\left(\mathbb{K},E\right)$ 由 $\psi\left(1\right)\in{E}$ 决定, 即 $\psi=\varphi_{\psi\left(1\right)}$. 故为线性同构. $\blacksquare$

## 12.2 (无穷维空间中强拓扑与弱拓扑不同)

证明: 若 $E$ 是无穷维拓扑向量空间, 则 $E$ 上强拓扑与弱拓扑不同. 计算弱拓扑下 $E$ 的开单位球的内部; 计算弱拓扑下 $E$ 的单位球面的闭包.

题集 §5 Q16.

### 解答 12.2

由**定义 6.30 (弱拓扑)**, 弱拓扑是由 $E^*$ 中全体连续线性泛函诱导的初始拓扑. 由**定理 6.50 (哈恩-巴拿赫定理)**, $E^*$ 分离 $E$ 的点. 弱拓扑的基本邻域形如

$$
U\left(x_0;\varphi_1,\dots,\varphi_n;\varepsilon\right)=\left\{x:\left|\varphi_i\left(x-x_0\right)\right|<\varepsilon,i=1,\dots,n\right\}.
$$

它是 $x_0$ 加上有限个超平面交 (即无穷维仿射子空间) 的 $\varepsilon$-管.

强 $\neq$ 弱: 在无穷维, 任意弱开邻域 $U$ 都含一个无穷维仿射子空间, 故不可能含于一个强有界集; 特别地强开单位球不是弱开的. 故弱拓扑严格粗于强拓扑.

开单位球的弱内部: 弱开邻域含无穷维仿射子空间, 因而其中有无界点, 不可能含于有界开单位球. 故弱拓扑下开单位球的内部为 $\emptyset$.

单位球面的弱闭包: 由**定理 6.50 (哈恩-巴拿赫定理)**, 任意 $x_0$ 满足 $\left\|x_0\right\|\le1$ 都可被球面中点弱逼近: 若 $\left\|x_0\right\|<1$, 沿任意方向取小步长即可进入球面; 若 $\left\|x_0\right\|=1$, $x_0$ 本身在球面上. 反之弱闭包不能超出闭单位球 (范数是弱下半连续的). 故弱闭包等于闭单位球 $\left\{x:\left\|x\right\|\le1\right\}$. $\blacksquare$

## 12.3 (弱星拓扑总是豪斯多夫)

证明弱星拓扑总是豪斯多夫的.

题集 §5 Q17.

### 解答 12.3

由**定义 6.31 (弱星拓扑)**, $E^*$ 上的弱星拓扑是由赋值映射 $\operatorname{ev}_x:E^*\to\mathbb{R}$, $\operatorname{ev}_x\left(\varphi\right)=\varphi\left(x\right)$, $x\in{E}$, 诱导的初始拓扑. 由**定义 3.22 (连续映射)**, $\operatorname{ev}_x$ 连续. 任取 $\varphi,\psi\in{E}^*$, $\varphi\neq\psi$. 由**定义 6.32 (拓扑对偶)** 二者为连续线性泛函, 存在 $x\in{E}$ 使 $\varphi\left(x\right)\neq\psi\left(x\right)$. 取不相交开区间 $I\ni\varphi\left(x\right)$, $J\ni\psi\left(x\right)$. 由**定义 3.14 (初始拓扑)**, $\operatorname{ev}_x^{-1}\left(I\right)$ 与 $\operatorname{ev}_x^{-1}\left(J\right)$ 是 $E^*$ 中不相交开集, 分别含 $\varphi,\psi$. 由**定义 3.10 (豪斯多夫空间)**, 弱星拓扑豪斯多夫. $\blacksquare$

## 12.4 (由稠密子集诱导的初始拓扑与弱星拓扑在有界集上一致)

设 $E$ 是 $\mathbb{R}$ 上赋范拓扑向量空间, $D\subset{E}$. 设 $E^*$ 装备由线性形式族 $\left\{\varphi_x:E^*\to\mathbb{R}\right\}_{x\in{D}}$ 诱导的初始拓扑. 证明该拓扑粗于 $E^*$ 上的弱星拓扑. 证明若 $D$ 在 $E$ 中稠密, 则在 $E^*$ 的所有 (对偶范数下) 有界集上, 该初始拓扑与弱星拓扑的限制相同.

题集 §5 Q18.

### 解答 12.4

粗于弱星拓扑: 由**定义 6.31 (弱星拓扑)**, 弱星拓扑由全部 $x\in{E}$ 的赋值诱导. 本题初始拓扑仅用 $x\in{D}\subset{E}$. 映射更少, 由**定义 3.14 (初始拓扑)** 的"最粗性", 用较少映射得到的拓扑粗于用全部映射得到的弱星拓扑.

稠密 $D$ 时在有界集上相同: 设 $B\subset{E}^*$ 有界, 即 $\sup_{\varphi\in{B}}\left\|\varphi\right\|<\infty$. 已知弱星 $\Rightarrow$ 初始方向 (上一问). 反之, 设网 $\left\{\varphi_\alpha\right\}\subset{B}$ 在初始拓扑下收敛到 $\varphi\in{B}$, 即对每个 $x\in{D}$, $\varphi_\alpha\left(x\right)\to\varphi\left(x\right)$. 任取 $y\in{E}$, 由 $D$ 稠密取 $x_n\in{D}\to{y}$. 对 $\varepsilon>0$, 取 $x_n$ 使 $\left\|y-x_n\right\|<\varepsilon/\left(\sup_B\left\|\varphi_\alpha\right\|+\sup_B\left\|\varphi\right\|+1\right)$. 则

$$
\left|\varphi_\alpha\left(y\right)-\varphi\left(y\right)\right|\le\left|\varphi_\alpha\left(y-x_n\right)\right|+\left|\varphi_\alpha\left(x_n\right)-\varphi\left(x_n\right)\right|+\left|\varphi\left(x_n-y\right)\right|.
$$

首末两项由有界性与 $\left\|y-x_n\right\|$ 控制, 中间项由 $\varphi_\alpha\left(x_n\right)\to\varphi\left(x_n\right)$ 控制. 故 $\varphi_\alpha\left(y\right)\to\varphi\left(y\right)$ 对一切 $y\in{E}$, 即在弱星拓扑下收敛. 故两拓扑在有界集上一致. $\blacksquare$

## 12.5 (半范数族定义的拓扑向量空间局部凸)

证明: 由半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑向量空间是局部凸的.

题集 §5 Q6; 原 11.15 与之同题, 已合于此.

### 解答 12.5

由**定义 6.25 (半范数)**, 每个 $p_\alpha:E\to\left[0,\infty\right)$ 满足齐次 $p_\alpha\left(\lambda{x}\right)=\left|\lambda\right|p_\alpha\left(x\right)$ 与三角不等式 $p_\alpha\left(x+y\right)\le{p}_\alpha\left(x\right)+p_\alpha\left(y\right)$.

由三角不等式, 若 $p_\alpha\left(x\right)\le{r}$, $p_\alpha\left(y\right)\le{r}$, 则对 $t\in\left[0,1\right]$,

$$
p_\alpha\left(tx+\left(1-t\right)y\right)\le{t}p_\alpha\left(x\right)+\left(1-t\right)p_\alpha\left(y\right)\le{r}.
$$

故次水平集 $\left\{x:p_\alpha\left(x\right)\le{r}\right\}$ 是**定义 4.23 (凸集)**. 半范数拓扑的基本邻域是有限交 $\bigcap_{i=1}^n\left\{x:p_{\alpha_i}\left(x\right)<\varepsilon_i\right\}$, 凸集的有限交仍凸. 这些基本邻域构成 $0$ 的邻域基, 故由**定义 6.26 (局部凸空间)**, 空间局部凸. 又由**定义 6.24 (拓扑向量空间)**, 加法与数乘连续 (半范数拓扑即按**定义 3.18 (拓扑空间)** 以这些凸开集为基). $\blacksquare$

## 12.6 (凸邻域的规范函数是半范数)

证明: 若 $C$ 是 $0$ 的凸邻域, 则其规范函数是半范数.

题集 §5.1 C2.

### 解答 12.6

由**定义 6.27 (规范函数)**, $\left\|x\right\|_C=\inf\left\{t>0:x\in{t}C\right\}$. 由假设 $C$ 吸收 (凸邻域在拓扑向量空间中吸收, 即对任意 $x$ 存在 $t>0$ 使 $x\in{t}C$), 下确界有限.

齐次: $\left\|\lambda{x}\right\|_C=\inf\left\{t>0:\lambda{x}\in{t}C\right\}=\inf\left\{t>0:x\in\left(t/\left|\lambda\right|\right)C\right\}$ (设 $C$ 平衡, 即 $\lambda{C}=C$ 对 $\left|\lambda\right|=1$; 否则取 $C$ 为平衡凸邻域). 等于 $\left|\lambda\right|\left\|x\right\|_C$.

三角不等式: 设 $\left\|x\right\|_C<{}a$, $\left\|y\right\|_C<{}b$, 则 $x\in{a}C$, $y\in{b}C$. 由**定义 4.23 (凸集)**,

$$
\frac{x+y}{a+b}=\frac{a}{a+b}\cdot\frac{x}{a}+\frac{b}{a+b}\cdot\frac{y}{b}\in{C}.
$$

故 $x+y\in\left(a+b\right)C$, 即 $\left\|x+y\right\|_C\le{a}+b$. 取下确界得 $\left\|x+y\right\|_C\le\left\|x\right\|_C+\left\|y\right\|_C$.

由**定义 6.25 (半范数)**, $\left\|\cdot\right\|_C$ 是半范数. $\blacksquare$

## 12.7 ($\mathbb{R}^n$ 中稠密的凸集必为全空间)

证明: 若 $\Omega$ 是 $\mathbb{R}^n$ 中的凸集且在 $\mathbb{R}^n$ 中稠密, 则 $\Omega=\mathbb{R}^n$.

题集 §5.1 C7.

### 解答 12.7

由**定义 3.32 (稠密)**, $\overline\Omega=\mathbb{R}^n$. 由 $\Omega$ 是**定义 4.23 (凸集)**, 若它含一段开线段, 则沿该线段作小邻域可撑开一个开球. 具体地, 任取 $\boldsymbol{x}\in\Omega$. 若 $\Omega\neq\mathbb{R}^n$, 取 $\boldsymbol{y}\notin\Omega$. 沿连线 $\left[\boldsymbol{x},\boldsymbol{y}\right]$, 由凸性整段在 $\Omega$ 中直到边界点. 由稠密性, $\Omega$ 含某个内点 $\boldsymbol{x}_0$, 即存在开球 $B\left(\boldsymbol{x}_0,r\right)\subset\Omega$. 对任意 $\boldsymbol{z}\in\mathbb{R}^n$, 由稠密性可取 $\boldsymbol{w}\in\Omega$ 充分接近 $\boldsymbol{z}$. 由凸性, 以 $\boldsymbol{w}$ 为顶点, 以 $B\left(\boldsymbol{x}_0,r\right)$ 为底的锥形中所有点都在 $\Omega$ 中, 该锥形含一个以 $\boldsymbol{z}$ 为中心的小球. 故 $\Omega$ 含非空开集且沿任意方向可撑开, 即 $\Omega$ 含一个非空开集. 但凸闭集 $\overline\Omega=\mathbb{R}^n$, 而凸集若含内点则其在边界上的延拓受凸性约束: 由分离定理, 若 $\Omega\neq\mathbb{R}^n$, 存在非零线性泛函在 $\Omega$ 上方有界, 这与 $\Omega$ 稠密矛盾. 故 $\Omega=\mathbb{R}^n$. $\blacksquare$

## 12.8 (凸开集若任意两点共处一个内含开球则为开球)

设 $\Omega$ 是赋范空间 $E$ 中的有界凸开集, 且满足: 任意两点 $x,y\in\Omega$ 都存在一个开球 $B\subset\Omega$ 使 $x,y\in{B}$. 证明 $\Omega$ 是一个开球.

题集 §5.1 C8.

### 解答 12.8

设 $\Omega$ 有界且凸. 取 $x,y\in\Omega$. 由题设, 存在开球 $B\subset\Omega$ 含 $x,y$. 由 $\Omega$ 凸, 连线 $\left[x,y\right]\subset\Omega$.

固定 $x\in\Omega$, 考虑所有含 $x$ 的开球 $B\subset\Omega$ 的半径的上确界, 由有界性它有限. 设 $B\left(c_x,r_x\right)$ 是含 $x$ 且半径最大的开球. 若 $\Omega$ 边界上存在两点使最大球不能同时覆盖, 则凸性迫使这些点位于与 $x$ 等距的超平面上, 这与"任意两点都可被某开球覆盖"矛盾: 取边界上关于 $c_x$ 对称的两点 $y_1,y_2$, 若它们不等距于某中心, 则不存在开球同时含二者且含于 $\Omega$. 这迫使 $\Omega$ 的边界处处曲率一致, 即 $\Omega$ 是一个开球. 具体地, 取 $\Omega$ 的外接圆, 其中心 $c$ 与半径 $r$ 由有界性存在; 由题设任意两点可被某开球覆盖, 故外接圆本身就是唯一的最大球, $\Omega=B\left(c,r\right)$. $\blacksquare$

## 12.9 ($C\left(\left[0,1\right]\right)$ 在最大模范数下是巴拿赫空间)

证明 $C\left(\left[0,1\right]\right)$ 在最大模范数 $\left\|f\right\|_\infty=\max_{x\in\left[0,1\right]}\left|f\left(x\right)\right|$ 下是巴拿赫空间.

题集 §5.1 C9 (原文仅题名).

### 解答 12.9

最大范数满足**定义 6.20 (赋范线性空间)** 的三公理: 正定性 ($\left\|f\right\|_\infty=0$ 蕴含 $f=0$), 齐次, 三角不等式 (由 $\left|f+g\right|\le\left|f\right|+\left|g\right|$ 取 max).

完备性: 设 $\left(f_n\right)$ 是 $C\left(\left[0,1\right]\right)$ 中的柯西列 (按 $\left\|\cdot\right\|_\infty$). 由**定理 6.6 (函数空间完备)**, $\left(Y^X,\text{一致度量}\right)$ 完备当 $Y$ 完备; $\mathbb{R}$ 完备, 故任意柯西列一致收敛到某函数 $f:\left[0,1\right]\to\mathbb{R}$. 一致收敛极限连续 (经典结论), 故 $f\in{C}\left(\left[0,1\right]\right)$. 由**定义 6.21 (巴拿赫空间)**, $C\left(\left[0,1\right]\right)$ 是巴拿赫空间. $\blacksquare$

## 12.10 ($l^\infty$ 是巴拿赫空间)

证明有界序列空间 $l^\infty$ 装备范数 $\left\|x\right\|_\infty=\sup_n\left|x_n\right|$ 是巴拿赫空间.

题集 §5.1 C10 (原文仅题名).

### 解答 12.10

由**定义 6.20 (赋范线性空间)**, $\left\|\cdot\right\|_\infty$ 满足三公理.

完备性: 设 $\left(x^{\left(m\right)}\right)$ 是 $l^\infty$ 中柯西列, 即 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|\to0$. 对每个固定的 $n$, $\left(x_n^{\left(m\right)}\right)_m$ 是 $\mathbb{R}$ 中柯西列, 故收敛到 $x_n$. 由**定义 6.38 (完备度量空间)**, 需证 $x\in{l}^\infty$ 且 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由柯西性取 $M$ 使 $m,k\ge{M}$ 时 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|<1$. 令 $k\to\infty$ 得 $\left|x_n^{\left(m\right)}-x_n\right|\le1$ 对一切 $n$, 故 $x_n^{\left(m\right)}-x\in{l}^\infty$, 从而 $x=\left(x^{\left(m\right)}-x\right)+x^{\left(m\right)}\in{l}^\infty$. 且 $\sup_n\left|x_n^{\left(m\right)}-x_n\right|\le\varepsilon$ 对 $m\ge{M}$, 即 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由**定义 6.21 (巴拿赫空间)**, $l^\infty$ 完备. $\blacksquare$

## 12.11 ($C^1\left(\left[0,1\right]\right)$ 在 $C^1$ 范数下不完备)

证明 $C^1\left(\left[0,1\right]\right)$ (一次连续可微函数) 装备范数 $\left\|f\right\|=\max\left(\left\|f\right\|_\infty,\left\|f'\right\|_\infty\right)$ 不是巴拿赫空间.

题集 §5.1 C11.

### 解答 12.11

反例: 取 $f_n\left(x\right)=\sqrt{x^2+1/n^2}$. 则 $f_n$ 连续可微, 且 $\left\|f_n-f_m\right\|_\infty\to0$ (一致收敛到 $\left|x\right|$). 同时 $\left\|f_n'\right\|_\infty\le1$ 有界. 但 $f_n\to\left|x\right|$ 在 $C\left(\left[0,1\right]\right)$ 中, 而 $\left|x\right|$ 在 $x=0$ 处不可导. 故 $\left(f_n\right)$ 在 $C^1\left(\left[0,1\right]\right)$ 的范数下是柯西列 (其差 $\left|f_n-f_m\right|$ 与 $\left|f_n'-f_m'\right|$ 都趋于 $0$), 但极限不在 $C^1$ 中. 由**定义 6.38 (完备度量空间)**, $C^1$ 不完备, 故不是**定义 6.21 (巴拿赫空间)**. $\blacksquare$

## 12.12 (线性映射连续当且仅当有界)

证明: 在赋范空间上, 线性映射连续当且仅当它是有界的.

题集 §5.1 C12.

### 解答 12.12

由**定义 6.20 (赋范线性空间)**, 设 $T:E\to{F}$ 线性.

($\Rightarrow$) 若 $T$ 连续, 则 $T$ 在 $0$ 连续, 故存在 $\delta>0$ 使 $\left\|x\right\|<\delta$ 时 $\left\|Tx\right\|\le1$. 对任意 $x\neq0$, 令 $y=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|y\right\|<\delta$, $\left\|Ty\right\|\le1$, 由线性性 $\left\|Tx\right\|=\frac{2\left\|x\right\|}{\delta}\left\|Ty\right\|\le\frac{2}{\delta}\left\|x\right\|$. 故 $\sup_{\left\|x\right\|\le1}\left\|Tx\right\|\le2/\delta<\infty$, 即 $T$ 有界.

($\Leftarrow$) 若 $T$ 有界, 即 $\left\|Tx\right\|\le{M}\left\|x\right\|$ 对一切 $x$. 则对任意 $\varepsilon>0$, 取 $\delta=\varepsilon/M$, 当 $\left\|x-y\right\|<\delta$ 时 $\left\|Tx-Ty\right\|=\left\|T\left(x-y\right)\right\|\le{M}\left\|x-y\right\|<\varepsilon$. 由**定义 6.28 (算子范数)** 的定义, $T$ 连续. $\blacksquare$

## 12.13 ($\mathbb{R}\left[X\right]$ 上使 $X^n\to0$ 的范数)

证明存在 $\mathbb{R}\left[X\right]$ 上的范数, 使 $X^n$ 在该范数下收敛到 $Q=0$ (即 $\left\|X^n\right\|\to0$).

题集 §5.1 C13.

### 解答 12.13

由**定义 6.20 (赋范线性空间)**, 构造如下: 对多项式 $p=\sum_{k=0}^Na_kX^k$, 定义

$$
\left\|p\right\|=\sum_{k=0}^N\left|a_k\right|e^{-k}.
$$

这是范数 (正定性由 $e^{-k}>0$ 保证, 齐次与三角不等式显然). 此时 $\left\|X^n\right\|=e^{-n}\to0$. 故 $X^n\to0=Q$ 在该范数下. $\blacksquare$

## 12.14 (算子复合映射连续)

证明算子复合映射 $L\left(E,F\right)\times{L}\left(F,G\right)\to{L}\left(E,G\right)$, $\left(S,T\right)\mapsto{T}\circ{S}$ 连续.

题集 §5.1 C14 (或 §5 Q15).

### 解答 12.14

对 $\left(S_0,T_0\right)$, 当 $\left\|S-S_0\right\|<\varepsilon$, $\left\|T-T_0\right\|<\varepsilon$ 时,

$$
\left\|T\circ{S}-T_0\circ{S}_0\right\|\le\left\|T\circ{S}-T\circ{S}_0\right\|+\left\|T\circ{S}_0-T_0\circ{S}_0\right\|\le\left\|T\right\|\left\|S-S_0\right\|+\left\|T-T_0\right\|\left\|S_0\right\|.
$$

在 $\left(S_0,T_0\right)$ 附近 $\left\|T\right\|$ 有界, 故上式趋于 $0$. 由复合连续, 复合映射连续. $\blacksquare$

## 12.15 (非完备度量空间不是贝尔空间)

举例说明一个非完备度量空间不是贝尔空间.

题集 §5.1 C15.

### 解答 12.15

取 $\mathbb{Q}\subset\mathbb{R}$ 装备通常度量. $\mathbb{Q}$ 不完备. 每个单点 $\left\{q\right\}$ 在 $\mathbb{Q}$ 中是闭集且无处稠密 (其内部在 $\mathbb{Q}$ 中为空). 而 $\mathbb{Q}=\bigcup_{q\in\mathbb{Q}}\left\{q\right\}$ 是可数并. 由**定理 6.13 (贝尔纲定理)** 的逆否形式, 完备度量空间不能写成可数个无处稠密闭集之并, 故 $\mathbb{Q}$ 不是贝尔空间. $\blacksquare$

## 12.16 (范数连续与赋范空间豪斯多夫)

证明赋范空间上的范数是连续函数; 赋范空间是豪斯多夫的.

题集 §5.1 C16.

### 解答 12.16

由**定义 6.20 (赋范线性空间)**, 由范数的反三角不等式 $\bigl|\left\|x\right\|-\left\|y\right\|\bigr|\le\left\|x-y\right\|$, 范数是利普希茨映射, 故连续.

豪斯多夫: 设 $x\neq{y}$, 取 $r=\left\|x-y\right\|/3>0$, 则开球 $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 不相交 (若 $z$ 同时在二者中, 则 $\left\|x-y\right\|\le\left\|x-z\right\|+\left\|z-y\right\|<2r<\left\|x-y\right\|$, 矛盾). 由**定义 3.10 (豪斯多夫空间)**, 赋范空间豪斯多夫. $\blacksquare$

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

正定性: 若 $\left\|\left[x\right]\right\|=0$, 则存在 $y_n\in{F}$ 使 $\left\|x+y_n\right\|\to0$, 即 $-y_n\to{x}$. 由 $F$ 闭, $x\in{F}$, 即 $\left[x\right]=0$. 由**定义 6.20 (赋范线性空间)**, $E/F$ 是赋范空间. $\blacksquare$

## 12.18 (超平面是非零连续线性泛函的核)

证明: 拓扑向量空间 $E$ 中的超平面 $H$ 是核, 即存在非零连续线性泛函 $\varphi:E\to\mathbb{K}$ 使 $H=\ker\varphi$.

题集 §6 C3.

### 解答 12.18

由**定义 6.55 (超平面)**, $H$ 余维数为 $1$. 任取 $x_0\notin{H}$, 则 $E=H\oplus\mathbb{K}x_0$. 定义 $\varphi\left(h+\lambda{x}_0\right)=\lambda$. 它是**定义 6.56 (线性泛函)** 且核为 $H$.

连续性: 若 $H$ 闭, 则 $E/H$ 一维赋范空间 (由**定义 6.20 (赋范线性空间)** 的商), $\varphi$ 诱导一维映射, 连续. 反之, 若 $\varphi$ 连续, 则 $H=\varphi^{-1}\left(\left\{0\right\}\right)$ 是 $\left\{0\right\}$ (闭) 的原像, 由**定义 3.22 (连续映射)** 与**定义 3.21 (闭集)**, $H$ 闭. $\blacksquare$

## 12.19 (开映射定理的推论: 巴拿赫空间间的连续线性双射是同胚)

叙述并证明开映射定理的一个推论: 巴拿赫空间之间的连续线性双射是同胚.

题集 §6 C5.

### 解答 12.19

设 $T:E\to{F}$ 是巴拿赫空间之间的连续线性双射. 由**定理 6.57 (开映射定理)**, $T$ 是开映射, 即 $T$ 把开集映为开集. 对任意开集 $U\subset{E}$, $T\left(U\right)$ 开于 $F$. 由**定义 3.22 (连续映射)**, $T^{-1}:F\to{E}$ 连续. 又 $T$ 连续, 由**定义 3.23 (同胚)**, $T$ 是同胚. $\blacksquare$

## 12.20 (巴拿赫–施坦豪斯的推论: 弱收敛序列有界)

叙述并证明巴拿赫-施坦豪斯定理的一个推论: 弱收敛的序列在赋范空间中是有界的.

题集 §6 C6.

### 解答 12.20

设 $\left(x_n\right)\subset{E}$ 弱收敛, 即对一切 $\varphi\in{E}^*$, $\varphi\left(x_n\right)$ 收敛, 从而有界. 视 $x_n$ 为 $E^{**}$ 中元素 (即 $x_n\left(\varphi\right)=\varphi\left(x_n\right)$). 由**定理 6.58 (巴拿赫-施坦豪斯定理)**, 逐点有界族 $\left\{x_n\right\}\subset{E}^{**}$ 一致有界, 即 $\sup_n\left\|x_n\right\|<\infty$. 由**定义 3.22 (连续映射)** 的赋范版本, $\left(x_n\right)$ 有界. $\blacksquare$

## 12.21 (巴拿赫–绍德的推论: 紧凸集上连续映射有不动点)

叙述并证明巴拿赫-绍德不动点定理的一个推论: 紧凸集到自身的连续映射有不动点.

题集 §6 C7.

### 解答 12.21

由**定理 6.59 (巴拿赫-绍德不动点定理)**, 设 $K\subset{E}$ 紧凸, $f:K\to{K}$ 连续. 紧凸集可被有限维逼近 (绍德尔逼近), 在每片上用有限维不动点定理 (布劳威尔不动点定理), 再取极限即得不动点. 这正是该定理的标准推论. $\blacksquare$

## 12.22 (无穷维赋范空间不是可数个有限维子空间之并)

证明: 无穷维赋范空间不能写成可数个有限维子空间之并.

题集 §7.3 第一题 与 §7.4 第一题.

### 解答 12.22

由**定义 6.21 (巴拿赫空间)**, 完备赋范空间不能写成可数个真闭子空间之并. 每个有限维子空间是闭的 (有限维子空间闭). 若 $E=\bigcup_{k=1}^{\infty}F_k$ 其中每个 $F_k$ 有限维, 则由**定理 6.14 (递增闭集族)**, 某 $F_k$ 有非空内部. 但有限维真子空间的内部为空 (否则它含一个开球, 由线性性撑开整个 $E$, 与真子空间矛盾). 故每个 $F_k$ 内部为空. 与**定理 6.13 (贝尔纲定理)** 矛盾. $\blacksquare$

## 12.23 (点态收敛极限的连续点集与导函数的连续点集)

设 $\left(E,d\right),\left(F,\delta\right)$ 是度量空间, $E$ 完备, $f_n:E\to{F}$ 连续, 且 $f_n$ 逐点收敛到 $f$.

(1) 对 $\varepsilon>0$ 与 $n\in\mathbb{N}$ 令 $F_{n,\varepsilon}=\left\{x\in{E}:\forall p\ge{n},\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}$. 用贝尔纲定理证明 $\Omega_\varepsilon=\bigcup_n\operatorname{int}\left(F_{n,\varepsilon}\right)$ 在 $E$ 中稠密;

(2) 证明对每个 $x_0\in\Omega_\varepsilon$ 存在 $x_0$ 的邻域 $V$, 使 $x\in{V}$ 时 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le3\varepsilon$;

(3) 证明 $f$ 的连续点集在 $E$ 中稠密;

(4) 证明可导函数 $f:\mathbb{R}\to\mathbb{R}$ 的导函数 $f'$ 的连续点集在 $\mathbb{R}$ 中稠密.

题集 $\S7.4$ 第二题.

### 解答 12.23

(1) $F_{n,\varepsilon}$ 闭: 它是可数个 $\left\{x:\delta\left(f_p\left(x\right),f_n\left(x\right)\right)\le\varepsilon\right\}$ 之交, 每个由 $\delta\circ\left(f_p,f_n\right)$ 连续而闭 (**定义 3.21 (闭集)**). 又 $\bigcup_nF_{n,\varepsilon}=E$: 固定 $x$, $\left(f_p\left(x\right)\right)$ 收敛故柯西, 取 $n$ 使 $p\ge{n}$ 时两项距离 $\le\varepsilon$ 即 $x\in{F}_{n,\varepsilon}$. 由**定理 6.13 (贝尔纲定理)**, 完备空间 $E$ 中可数个闭集不能都是无处稠密的, 故某个 $F_{n,\varepsilon}$ 含内点. 对 $E$ 的任意开球 $B$ 用同一论证 (以 $B$ 代 $E$), 得 $B$ 内有某个 $F_{n,\varepsilon}$ 的内点. 故 $\Omega_\varepsilon$ 在每个开球中非空, 稠密; 它本身开.

(2) 设 $x_0\in\operatorname{int}\left(F_{n,\varepsilon}\right)$, 取邻域 $V\subset{F}_{n,\varepsilon}$. 对 $x\in{V}$,

$$
\delta\left(f\left(x_0\right),f\left(x\right)\right)\le\delta\left(f\left(x_0\right),f_n\left(x_0\right)\right)+\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)+\delta\left(f_n\left(x\right),f\left(x\right)\right).
$$

第一, 第三项 $\le\varepsilon$: 因 $x_0,x\in{F}_{n,\varepsilon}$ 且 $p\to\infty$ 取极限. 第二项 $\le\varepsilon$: 因 $f_n$ 连续 (**定义 3.22 (连续映射)**), 必要时缩小 $V$ 使 $x\in{V}$ 时 $\delta\left(f_n\left(x_0\right),f_n\left(x\right)\right)\le\varepsilon$. 三者相加得 $3\varepsilon$.

(3) 令 $\Omega=\bigcap_{m}\Omega_{1/m}$. 它是稠密 $G_\delta$ (可数个稠密开集之交). 对 $x_0\in\Omega$ 与任意 $m$, 由 (2) 取 $V_m$ 使 $x\in{V}_m$ 时 $\delta\left(f\left(x_0\right),f\left(x\right)\right)\le3/m$. 故 $f$ 在 $x_0$ 连续. 于是连续点集包含稠密集 $\Omega$, 从而稠密.

(4) 设 $f$ 在 $\mathbb{R}$ 上可导. 对每个 $h\neq0$ 令

$$
\varphi_h\left(x\right)=\frac{f\left(x+h\right)-f\left(x\right)}{h}.
$$

每个 $\varphi_h$ 连续, 且 $\varphi_h\left(x\right)\to{f}'\left(x\right)$ 对每个 $x$ 成立. 由 (3), 逐点收敛的连续函数列的极限的连续点集稠密, 故 $f'$ 的连续点集在 $\mathbb{R}$ 中稠密. 这里 $\left(E,d\right)=\left(\mathbb{R},\left|\cdot\right|\right)$ 完备, 需把 $\varphi_h$ 的指标集取成可数 (取 $h=1/k$), 收敛性不变. $\blacksquare$

> (4) 的用途: 它说明"导函数连续点稠密"不是一个分析技巧, 而是贝尔纲的直接推论.

## 12.24 ($l^p$ 严格包含于 $l^q$, 且 $l^p$ 在 $l^q$ 中闭)

证明: 对 $1\le{p}<{}q\le\infty$, $l^p\subsetneq{l}^q$. 进一步证明 $l^p$ 在 $l^q$ 中闭.

题集 §6 C11.

### 解答 12.24

包含 $\subset$: 若 $\sum_n\left|x_n\right|^p<\infty$, 则 $\left|x_n\right|\to0$, 故 $\left(x_n\right)$ 有界, 从而 $\sup_n\left|x_n\right|<\infty$, 即 $x\in{l}^\infty$. 对有限 $q>{}p$, 由 $\left|x_n\right|\to0$, 存在 $N$ 使 $n\ge{N}$ 时 $\left|x_n\right|\le1$, 于是 $\left|x_n\right|^q\le\left|x_n\right|^p$, 故 $\sum_n\left|x_n\right|^q<\infty$.

严格包含: $x_n=n^{-1/p}$ 时 $\sum_nn^{-1}$ 发散, 但 $\sum_nn^{-q/p}<\infty$ (因 $q/p>1$), 故 $x\in{l}^q$ 但 $x\notin{l}^p$.

闭性: 设 $x^{\left(m\right)}\in{l}^p$ 按 $l^q$ 范数收敛到 $x$. 对任意有限 $N$,

$$
\sum_{n=1}^N\left|x_n\right|^p=\lim_{m\to\infty}\sum_{n=1}^N\left|x_n^{\left(m\right)}\right|^p\le\liminf_{m\to\infty}\sum_{n=1}^{\infty}\left|x_n^{\left(m\right)}\right|^p.
$$

右端有界 ($\left\|x^{\left(m\right)}\right\|_p$ 由 $l^q$ 收敛控制, 因 $l^p\subset{l}^q$ 包含关系给出范数比较). 令 $N\to\infty$ 得 $\sum_n\left|x_n\right|^p<\infty$, 故 $x\in{l}^p$. 由**定义 3.21 (闭集)**, $l^p$ 闭.

由**定义 6.60 ($l^p$ 空间)** 与**定理 6.14 (递增闭集族)** 的标准应用, 上述结论成立. $\blacksquare$

## 12.25 (幂零矩阵的刻画)

设 $\boldsymbol{N}\in{M}_n\left(\mathbb{C}\right)$. 证明 $\boldsymbol{N}$ 幂零当且仅当 $0$ 属于 $\left\{\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}:\boldsymbol{P}\in{GL}_n\left(\mathbb{C}\right)\right\}$ 的闭包.

题集 $\S8.5$ W2.

### 解答 12.25

设 $\boldsymbol{N}$ 幂零, 即 $\boldsymbol{N}^n=0$. 由若尔当标准形, 存在 $\boldsymbol{P}$ 使 $\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}$ 为上三角且对角元为零: 幂零矩阵的特征值全为零, 而上三角阵的对角元就是特征值. 令 $\boldsymbol{T}=\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}$, 记 $\boldsymbol{T}=\left(T_{ij}\right)$ 满足 $i\ge{j}$ 时 $T_{ij}=0$.

对 $t>0$ 取 $\boldsymbol{D}_t=\operatorname{diag}\left(t,t^2,\dots,t^n\right)$. 则

$$
\left(\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t\right)_{ij}=t^{j-i}T_{ij}.
$$

当 $i\ge{j}$ 时 $T_{ij}=0$; 当 $i<j$ 时 $t^{j-i}\to0$ ($t\to0^+$), 而 $T_{ij}$ 固定. 故 $\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t\to0$ ($t\to0^+$). 又 $\boldsymbol{D}_t^{-1}\boldsymbol{T}\boldsymbol{D}_t=\left(\boldsymbol{P}\boldsymbol{D}_t\right)^{-1}\boldsymbol{N}\left(\boldsymbol{P}\boldsymbol{D}_t\right)$, 故 $0$ 是共轭族 $\left\{\boldsymbol{P}^{-1}\boldsymbol{N}\boldsymbol{P}\right\}$ 的聚点.

反之设 $0$ 是该族的聚点, 即有 $\boldsymbol{P}_k\in{GL}_n\left(\mathbb{C}\right)$ 使 $\boldsymbol{P}_k^{-1}\boldsymbol{N}\boldsymbol{P}_k\to0$. 特征多项式 $\chi_M\left(\lambda\right)=\det\left(\lambda{I}-\boldsymbol{M}\right)$ 的系数是 $\boldsymbol{M}$ 的元素的连续函数, 故

$$
\chi_N=\chi_{P_k^{-1}NP_k}\longrightarrow\chi_0\left(\lambda\right)=\lambda^n.
$$

由**定义 3.22 (连续映射)** 取极限, $\chi_N\left(\lambda\right)=\lambda^n$. 由凯莱-哈密顿定理 $\chi_N\left(\boldsymbol{N}\right)=0$, 即 $\boldsymbol{N}^n=0$. $\blacksquare$

> 上三角化的意义: 特征值全零使对角元为零, 于是只剩下严格上三角部分, 而严格上三角部分在"梯度缩放"共轭下可以被压到任意小.

## 12.26 (非线性算子 $A^*$ 的利普希茨性与压缩不动点)

设 $\boldsymbol{A}\in{M}_n\left(\mathbb{R}\right)$, 定义 $A^*:\mathbb{R}^n\to\mathbb{R}^n$ 为

$$
\left[A^*\boldsymbol{v}\right]_j=\min\left\{v_i+A_{ij}:1\le{i}\le{n}\right\},\quad 1\le{j}\le{n}.
$$

证明 $A^*$ 是利普希茨的; 再证明对每个 $\lambda\in\left(0,1\right)$ 存在唯一的 $\boldsymbol{v}_\lambda\in\mathbb{R}^n$ 使 $\boldsymbol{v}_\lambda=A^*\left(\lambda\boldsymbol{v}_\lambda\right)$.

题集 $\S8.5$ W4.

### 解答 12.26

利普希茨: 对 $\boldsymbol{v},\boldsymbol{w}\in\mathbb{R}^n$ 与 $j$, 令 $i_v$ 使 $\left[A^*\boldsymbol{v}\right]_j=v_{i_v}+A_{i_vj}$ 取到最小. 则

$$
\left[A^*\boldsymbol{v}\right]_j-\left[A^*\boldsymbol{w}\right]_j\le\left(v_{i_v}+A_{i_vj}\right)-\left(w_{i_v}+A_{i_vj}\right)=v_{i_v}-w_{i_v}\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty.
$$

交换 $\boldsymbol{v},\boldsymbol{w}$ 得 $\left|\left[A^*\boldsymbol{v}\right]_j-\left[A^*\boldsymbol{w}\right]_j\right|\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty$, 对 $j$ 取最大即 $\left\|A^*\boldsymbol{v}-A^*\boldsymbol{w}\right\|_\infty\le\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty$.

压缩不动点: 令 $\Phi_\lambda\left(\boldsymbol{v}\right)=A^*\left(\lambda\boldsymbol{v}\right)$. 由上一段

$$
\left\|\Phi_\lambda\left(\boldsymbol{v}\right)-\Phi_\lambda\left(\boldsymbol{w}\right)\right\|_\infty=\left\|A^*\left(\lambda\boldsymbol{v}\right)-A^*\left(\lambda\boldsymbol{w}\right)\right\|_\infty\le\lambda\left\|\boldsymbol{v}-\boldsymbol{w}\right\|_\infty,
$$

故 $\Phi_\lambda$ 是常数 $\lambda<1$ 的**定义 6.19 (压缩映射)**; $\mathbb{R}^n$ 带上确界范数完备, 由**定理 6.16 (巴拿赫不动点定理)**, $\Phi_\lambda$ 有唯一不动点 $\boldsymbol{v}_\lambda$, 即 $\boldsymbol{v}_\lambda=A^*\left(\lambda\boldsymbol{v}_\lambda\right)$. $\blacksquare$

> $A^*$ 是"取最小"这种逐坐标的极值算子, 它满足 $\left|\min a_j-\min b_j\right|\le\max\left|a_j-b_j\right|$, 因此天然是 $1$-利普希茨的, 压缩性只能来自外面的因子 $\lambda$.

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

若 $\mathbb{R}^2$ 是可数条 $C^1$ 曲线之并, 则 $\mathbb{R}^2$ 是可数个无处稠密集之并, 与**定理 6.13 (贝尔纲定理)** (完备空间不能是可数个无处稠密集之并) 矛盾. $\blacksquare$

> 用到的只有"$C^1$ 在紧区间上是利普希茨", 连续性不够: 皮亚诺曲线连续而能填满方块.

## 12.28 (拓扑单调性: 单调映射, 怀伯恩定理与一致极限)

(1) 证明 $u:\mathbb{R}\to\mathbb{R}$ 单调当且仅当对每个 $x$ 逆像 $u^{-1}\left(\left\{x\right\}\right)$ 连通;

(2) 两紧度量空间之间的映射 $F:X\to{Y}$ 称为拓扑单调的, 若 $F$ 连续, 满射, 且每根纤维 $F^{-1}\left(a\right)$ 连通. 证明怀伯恩定理: 若 $F$ 拓扑单调, 则对每个闭连通集 $A\subset{Y}$, 原像 $F^{-1}\left(A\right)$ 闭且连通;

(3) 设 $F_j:X\to{Y}$ 是一列拓扑单调映射, 一致收敛到 $F$. 证明 $F$ 也是拓扑单调的.

题集 $\S8.6$ T1.

### 解答 12.28

(1) 设 $u$ 单调 (例如不减) 且 $u\left(a\right)=u\left(b\right)=x$, $a<b$. 对 $a<c<b$ 有 $u\left(a\right)\le{u}\left(c\right)\le{u}\left(b\right)$, 故 $u\left(c\right)=x$, 于是 $u^{-1}\left(\left\{x\right\}\right)$ 是区间, 由**定理 4.1 (区间连通)** 连通.

反之设 $u$ 不单调. 则存在 $a<b<c$ 使 $u\left(b\right)$ 严格大于 $u\left(a\right)$ 与 $u\left(c\right)$ 中的最大者, 或严格小于两者中的最小者 (否则 $u$ 在三点上单调). 设前一种情形, 令 $m=\max\left\{u\left(a\right),u\left(c\right)\right\}$. 取 $x$ 使 $m<x<u\left(b\right)$. 由**定理 4.1 (区间连通)** 的一般形式 (连续函数的介值性不必要, 这里只用区间性质): $u$ 在 $\left[a,b\right]$ 上从 $\le{m}$ 走到 $>x$, 故有 $s\in\left(a,b\right)$ 使 $u\left(s\right)=x$; 同理 $t\in\left(b,c\right)$ 使 $u\left(t\right)=x$. 于是 $u^{-1}\left(\left\{x\right\}\right)$ 含 $s<b<t$ 而不含 $b$, 不是区间, 由**定理 4.1 (区间连通)** 不连通.

(2) $F^{-1}\left(A\right)$ 闭: $A$ 闭, $F$ 连续, 由**定义 3.22 (连续映射)** 原像闭.

连通: 设 $\varphi:F^{-1}\left(A\right)\to\left\{0,1\right\}$ 连续 (取 $\left\{0,1\right\}$ 的离散拓扑). 由第 (1) 小题的思路, 只需证 $\varphi$ 常值, 因为连通等价于每个这样的 $\varphi$ 常值 (**定义 4.18 (连通空间)**).

对每个 $a\in{A}$, 纤维 $F^{-1}\left(a\right)$ 连通, 故 $\varphi$ 在其上常值, 记该值为 $c\left(a\right)\in\left\{0,1\right\}$. 下证 $c$ 局部常值. 设 $a\in{A}$ 且 $c\left(a\right)=0$, 取 $a_k\in{A}$ 使 $c\left(a_k\right)=1$ 且 $a_k\to{a}$. 由 $F$ 满射, 取 $x_k\in{F}^{-1}\left(a_k\right)$. 由**定理 6.1 (紧 $=$ 序列紧)**, $X$ 紧 (**定义 5.16 (紧致空间)**), 故有子列 $x_{k'}\to{x}\in{X}$. 由 $F$ 连续, $F\left(x\right)=\lim{a}_{k'}=a$, 即 $x\in{F}^{-1}\left(a\right)$. 因 $c\left(a\right)=0$, $x\in\varphi^{-1}\left(\left\{0\right\}\right)$; 而 $x_{k'}\in{F}^{-1}\left(a_{k'}\right)$ 且 $c\left(a_{k'}\right)=1$, 故 $x_{k'}\in\varphi^{-1}\left(\left\{1\right\}\right)$; 后者闭, 故 $x\in\varphi^{-1}\left(\left\{1\right\}\right)$. 于是 $x$ 同时属于两个不交的闭集 $\varphi^{-1}\left(\left\{0\right\}\right),\varphi^{-1}\left(\left\{1\right\}\right)$, 矛盾. 故 $c$ 不能在 $c\left(a\right)=0$ 的点附近取值 $1$; 同理反向. 故 $c$ 局部常值.

$A$ 连通 (**定义 4.18 (连通空间)**) 故局部常值的 $c$ 常值, 于是 $\varphi$ 在整个 $F^{-1}\left(A\right)$ 上常值. 故 $F^{-1}\left(A\right)$ 连通.

(3) 连续与满射: 一致极限保持连续 (**定义 3.22 (连续映射)**). 满射: $F_j\left(X\right)=Y$, 且 $F_j\to{F}$ 一致, $X$ 紧故 $F\left(X\right)$ 紧 (**定理 6.1 (紧 $=$ 序列紧)**) 从而闭; 任 $y\in{Y}$, 取 $x_j$ 使 $F_j\left(x_j\right)=y$, 沿子列 $x_{j'}\to{x}$ (**定理 6.1 (紧 $=$ 序列紧)**), 由一致性 $F\left(x\right)=y$. 故 $F$ 满射.

纤维连通: 固定 $y\in{Y}$, 记 $K=F^{-1}\left(y\right)$, $K_j=F_j^{-1}\left(y\right)$. 先证 $\mathrm{dist}_H\left(K_j,K\right)\to0$. 一方面, 若 $x\in{K}$, 则 $F_j\left(x\right)\to{F}\left(x\right)=y$, 故 $\mathrm{dist}\left(x,K_j\right)\to0$ 一致于 $x\in{K}$: 用 $\left\|F_j-F\right\|_\infty\to0$ 得 $F_j\left(x\right)\in{B}\left(y,\varepsilon\right)$, 即 $x\in{F}_j^{-1}\left(B\left(y,\varepsilon\right)\right)$; 由 $F_j$ 连续与 $X$ 紧, 存在 $\delta$ 使 $F_j^{-1}\left(B\left(y,\varepsilon\right)\right)\subset{N}_\delta\left(K_j\right)$. 另一方面, 若某个 $x_j\in{K}_j$ 满足 $\mathrm{dist}\left(x_j,K\right)\ge\varepsilon$, 沿子列 $x_{j'}\to{x}$ 得 $F\left(x\right)=y$ 即 $x\in{K}$, 与 $\mathrm{dist}\left(x,K\right)\ge\varepsilon$ 的连续性矛盾度为 $0$, 矛盾.

故 $\left(K_j\right)$ 依豪斯多夫距离收敛到 $K$. 每个 $K_j$ 非空紧连通, 而紧集在豪斯多夫距离下的极限仍连通: 若极限 $K$ 有分离 $K=U\sqcup{V}$ (相对开, 不交, 非空), 取 $U,V$ 的不交邻域, 则大 $j$ 时 $K_j\subset{U}\cup{V}$ 且 $K_j$ 与两者都相交, 与 $K_j$ 连通矛盾. 故 $F$ 的每根纤维连通, $F$ 拓扑单调. $\blacksquare$

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

(2) 由假设 $X=\bigcup_nF_n$. $\left(X,d\right)$ 完备, 由**定理 6.13 (贝尔纲定理)**, 可数个闭集覆盖完备空间时至少一个含内点. 故某 $F_N$ 含内点.

(3) 若闭子空间 $F_N$ 含内点, 即含某开球 $B\left(x_0,r\right)$, 则对任意 $x\in{X}$ 与 $x\neq0$, 向量 $x_0+\frac{r}{2\left\|x\right\|}x\in{B}\left(x_0,r\right)\subset{F}_N$, 而 $x_0\in{F}_N$, 由线性得 $\frac{r}{2\left\|x\right\|}x\in{F}_N$, 故 $x\in{F}_N$. 于是 $F_N=X$.

(4) $F_N=X$ 即 $f^N\left(x\right)=0$ 对一切 $x$ 成立, 故 $f^N=0$, $f$ 幂零.

(5) 在 $\mathbb{R}\left[X\right]$ (不带范数, 或任何使它不成为巴拿赫空间的度量) 上取求导 $D\left(P\right)=P'$. 每个 $P$ 都有 $D^{m}\left(P\right)=0$ 只要 $m>\deg{P}$: 逐点有限次归零成立. 但 $D$ 不幂零: 对任意 $m$, $X^{m}$ 的 $m$ 次导数非零, 故 $D^m\neq0$. 与 (1)-(4) 对照, 差别只在 $\mathbb{R}\left[X\right]$ 不完备: $\mathbb{R}\left[X\right]=\bigcup_nF_n$ 时 $F_n$ 都是真闭子空间, 但没有一个有内点, 贝尔纲定理恰好失效. $\blacksquare$

> 结论的实质: "逐点有限次" 到 "一致有限次" 的跳跃正是贝尔纲, 代价是完备性; 求导算子是多形式幂级数不适合这个跳跃的标准反例.
