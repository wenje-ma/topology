# week11

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.14 (初始拓扑)**
> 
> 设 $f:X\to{}Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal{O}$. 称 $\mathcal{O}_f=\left\{f^{-1}\left(O\right):O\in\mathcal{O}\right\}$ 为 $X$ 上由 $f$ 诱导的初始拓扑; 它是使 $f$ 连续的最粗拓扑. (题集 §1.1 Q2; 题集 §1.4 C6)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{}X$ 是开的当且仅当 $U\in{}T$. 我们要求:
> 
> (1) $\emptyset,X\in{}T$;
> 
> (2) 若 $U,V\in{}T$, 则 $U\cap{}V\in{}T$;
> 
> (3) 若 $A\subset{}T$, 则 $\bigcup{}A\in{}T$. (教材 $\S3$, p12)

> **定义 3.21 (闭集)**
> 
> 称 $F\subset{}X$ 是闭的, 若 $X\setminus{}F$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**
> 
> 函数 $f:X\to{}Y$ 是连续的, 若对所有开集 $U\subset{}Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$, p14)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{}X$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $\boldsymbol{x},\boldsymbol{y}\in{}K$ 蕴含线段 $\left(1-t\right)\boldsymbol{x}+t\boldsymbol{y}$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定理 6.6 (函数空间完备)**
> 
> $Y$ 完备则 $\left(Y^X,\text{一致度量}\right)$ 完备. (教材 §6)

> **定理 6.13 (贝尔纲定理)**
> 
> 完备度量空间 (或局部紧豪斯多夫空间) 中, 可数个稠密开集之交仍稠密; 等价地, 完备度量空间不能写成可数个无处稠密闭集之并. (教材 §6)

> **定义 6.20 (赋范线性空间)**
> 
> 向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21 (巴拿赫空间)**
> 
> 完备的赋范线性空间. (题集 §5)

> **定义 6.24 (拓扑向量空间)**
> 
> 向量空间装备使加法 $E\times{}E\to{}E$ 与数乘 $\mathbb{K}\times{}E\to{}E$ 都连续的拓扑. (题集 §5 Q6)

> **定义 6.25 (半范数)**
> 
> 满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 §5 Q6)

> **定义 6.26 (局部凸空间)**
> 
> 拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 §5 Q6)

> **定义 6.27 (规范函数)**
> 
> 凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in{}C,t>0\right\}$ (等价地 $\inf\left\{t>0:x\in{}tC\right\}$). (题集 §5 Q14)

> **定义 6.28 (算子范数)**
> 
> $L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le1}\left\|Tx\right\|$. (题集 §5 Q15)

> **定义 6.30 (弱拓扑)**
> 
> $E$ 上由全体连续线性泛函 $\varphi\in{}E^*$ 的拉回生成的初始拓扑. (题集 §5 Q16)

> **定义 6.31 (弱星拓扑)**
> 
> 对偶 $E^*$ 上由赋值映射 $\left\{\varphi\mapsto\varphi\left(x\right)\right\}_{x\in{}E}$ 诱导的初始拓扑. (题集 §5 Q17-Q18)

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

## 12.2 (无穷维空间中强拓扑与弱拓扑不同)

证明:

(1) 若 $E$ 是无穷维拓扑向量空间, 则 $E$ 上强拓扑与弱拓扑不同;

(2) 计算弱拓扑下 $E$ 的开单位球的内部;

(3) 计算弱拓扑下 $E$ 的单位球面的闭包.

题集 §5 Q16.

### 解答 12.2

由**定义 6.30 (弱拓扑)**, 弱拓扑是由 $E^*$ 中全体连续线性泛函诱导的初始拓扑. 由**定理 6.50 (哈恩-巴拿赫定理)**, $E^*$ 分离 $E$ 的点. 弱拓扑的基本邻域形如

$$
U\left(x_0;\varphi_1,\dots,\varphi_n;\varepsilon\right)=\left\{x:\left|\varphi_i\left(x-x_0\right)\right|<\varepsilon,i=1,\dots,n\right\}.
$$

它是 $x_0$ 加上有限个超平面交 (即无穷维仿射子空间) 的 $\varepsilon$-管.

(1) 在无穷维, 任意弱开邻域 $U$ 都含一个无穷维仿射子空间, 故不可能含于一个强有界集; 特别地强开单位球不是弱开的. 故弱拓扑严格粗于强拓扑.

$\blacksquare$

(2) 弱开邻域含无穷维仿射子空间, 因而其中有无界点, 不可能含于有界开单位球. 故弱拓扑下开单位球的内部为 $\emptyset$.

$\blacksquare$

(3) 由**定理 6.50 (哈恩-巴拿赫定理)**, 任意 $x_0$ 满足 $\left\|x_0\right\|\le1$ 都可被球面中点弱逼近: 若 $\left\|x_0\right\|<1$, 沿任意方向取小步长即可进入球面; 若 $\left\|x_0\right\|=1$, $x_0$ 本身在球面上. 反之弱闭包不能超出闭单位球 (范数是弱下半连续的). 故弱闭包等于闭单位球 $\left\{x:\left\|x\right\|\le1\right\}$.

$\blacksquare$

## 12.3 (弱星拓扑总是豪斯多夫)

证明弱星拓扑总是豪斯多夫的.

题集 §5 Q17.

### 解答 12.3

由**定义 6.31 (弱星拓扑)**, $E^*$ 上的弱星拓扑是由赋值映射 $\operatorname{ev}_x:E^*\to\mathbb{R}$, $\operatorname{ev}_x\left(\varphi\right)=\varphi\left(x\right)$, $x\in{}E$, 诱导的初始拓扑. 由**定义 3.22 (连续映射)**, $\operatorname{ev}_x$ 连续. 任取 $\varphi,\psi\in{}E^*$, $\varphi\neq\psi$. 由**定义 6.32 (拓扑对偶)** 二者为连续线性泛函, 存在 $x\in{}E$ 使 $\varphi\left(x\right)\neq\psi\left(x\right)$. 取不相交开区间 $I\ni\varphi\left(x\right)$, $J\ni\psi\left(x\right)$. 由**定义 3.14 (初始拓扑)**, $\operatorname{ev}_x^{-1}\left(I\right)$ 与 $\operatorname{ev}_x^{-1}\left(J\right)$ 是 $E^*$ 中不相交开集, 分别含 $\varphi,\psi$. 由**定义 3.10 (豪斯多夫空间)**, 弱星拓扑豪斯多夫.

$\blacksquare$

## 12.4 (由稠密子集诱导的初始拓扑与弱星拓扑在有界集上一致)

设 $E$ 是 $\mathbb{R}$ 上赋范拓扑向量空间, $D\subset{}E$. 设 $E^*$ 装备由线性形式族 $\left\{\varphi_x:E^*\to\mathbb{R}\right\}_{x\in{}D}$ 诱导的初始拓扑. 证明该拓扑粗于 $E^*$ 上的弱星拓扑. 证明若 $D$ 在 $E$ 中稠密, 则在 $E^*$ 的所有 (对偶范数下) 有界集上, 该初始拓扑与弱星拓扑的限制相同.

题集 §5 Q18.

### 解答 12.4

粗于弱星拓扑: 由**定义 6.31 (弱星拓扑)**, 弱星拓扑由全部 $x\in{}E$ 的赋值诱导. 本题初始拓扑仅用 $x\in{}D\subset{}E$. 映射更少, 由**定义 3.14 (初始拓扑)** 的"最粗性", 用较少映射得到的拓扑粗于用全部映射得到的弱星拓扑.

$\blacksquare$

稠密 $D$ 时在有界集上相同: 设 $B\subset{}E^*$ 有界, 即 $\sup_{\varphi\in{}B}\left\|\varphi\right\|<\infty$. 已知弱星 $\Rightarrow$ 初始方向 (上一问). 反之, 设网 $\left\{\varphi_\alpha\right\}\subset{}B$ 在初始拓扑下收敛到 $\varphi\in{}B$, 即对每个 $x\in{}D$, $\varphi_\alpha\left(x\right)\to\varphi\left(x\right)$. 任取 $y\in{}E$, 由 $D$ 稠密取 $x_n\in{}D\to{}y$. 对 $\varepsilon>0$, 取 $x_n$ 使 $\left\|y-x_n\right\|<\varepsilon/\left(\sup_B\left\|\varphi_\alpha\right\|+\sup_B\left\|\varphi\right\|+1\right)$. 则

$$
\left|\varphi_\alpha\left(y\right)-\varphi\left(y\right)\right|\le\left|\varphi_\alpha\left(y-x_n\right)\right|+\left|\varphi_\alpha\left(x_n\right)-\varphi\left(x_n\right)\right|+\left|\varphi\left(x_n-y\right)\right|.
$$

首末两项由有界性与 $\left\|y-x_n\right\|$ 控制, 中间项由 $\varphi_\alpha\left(x_n\right)\to\varphi\left(x_n\right)$ 控制. 故 $\varphi_\alpha\left(y\right)\to\varphi\left(y\right)$ 对一切 $y\in{}E$, 即在弱星拓扑下收敛. 故两拓扑在有界集上一致.

$\blacksquare$

## 12.5 (半范数族定义的拓扑向量空间局部凸)

证明: 由半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑向量空间是局部凸的.

题集 §5 Q6; 原 11.15 与之同题, 已合于此.

### 解答 12.5

由**定义 6.25 (半范数)**, 每个 $p_\alpha:E\to\left[0,\infty\right)$ 满足齐次 $p_\alpha\left(\lambda{}x\right)=\left|\lambda\right|p_\alpha\left(x\right)$ 与三角不等式 $p_\alpha\left(x+y\right)\le{}p_\alpha\left(x\right)+p_\alpha\left(y\right)$.

由三角不等式, 若 $p_\alpha\left(x\right)\le{}r$, $p_\alpha\left(y\right)\le{}r$, 则对 $t\in\left[0,1\right]$,

$$
p_\alpha\left(tx+\left(1-t\right)y\right)\le{}tp_\alpha\left(x\right)+\left(1-t\right)p_\alpha\left(y\right)\le{}r.
$$

故次水平集 $\left\{x:p_\alpha\left(x\right)\le{}r\right\}$ 是**定义 4.23 (凸集)**. 半范数拓扑的基本邻域是有限交 $\bigcap_{i=1}^n\left\{x:p_{\alpha_i}\left(x\right)<\varepsilon_i\right\}$, 凸集的有限交仍凸. 这些基本邻域构成 $0$ 的邻域基, 故由**定义 6.26 (局部凸空间)**, 空间局部凸. 又由**定义 6.24 (拓扑向量空间)**, 加法与数乘连续 (半范数拓扑即按**定义 3.18 (拓扑空间)** 以这些凸开集为基).

$\blacksquare$

## 12.6 (凸邻域的规范函数是半范数)

证明: 若 $C$ 是 $0$ 的凸邻域, 则其规范函数是半范数.

题集 §5.1 C2.

### 解答 12.6

由**定义 6.27 (规范函数)**, $\left\|x\right\|_C=\inf\left\{t>0:x\in{}tC\right\}$. 由假设 $C$ 吸收 (凸邻域在拓扑向量空间中吸收, 即对任意 $x$ 存在 $t>0$ 使 $x\in{}tC$), 下确界有限.

齐次: $\left\|\lambda{}x\right\|_C=\inf\left\{t>0:\lambda{}x\in{}tC\right\}=\inf\left\{t>0:x\in\left(t/\left|\lambda\right|\right)C\right\}$ (设 $C$ 平衡, 即 $\lambda{}C=C$ 对 $\left|\lambda\right|=1$; 否则取 $C$ 为平衡凸邻域). 等于 $\left|\lambda\right|\left\|x\right\|_C$.

三角不等式: 设 $\left\|x\right\|_C<{}a$, $\left\|y\right\|_C<{}b$, 则 $x\in{}aC$, $y\in{}bC$. 由**定义 4.23 (凸集)**,

$$
\frac{x+y}{a+b}=\frac{a}{a+b}\cdot\frac{x}{a}+\frac{b}{a+b}\cdot\frac{y}{b}\in{}C.
$$

故 $x+y\in\left(a+b\right)C$, 即 $\left\|x+y\right\|_C\le{}a+b$. 取下确界得 $\left\|x+y\right\|_C\le\left\|x\right\|_C+\left\|y\right\|_C$.

由**定义 6.25 (半范数)**, $\left\|\cdot\right\|_C$ 是半范数.

$\blacksquare$

## 12.7 ($\mathbb{R}^n$ 中稠密的凸集必为全空间)

证明: 若 $\Omega$ 是 $\mathbb{R}^n$ 中的凸集且在 $\mathbb{R}^n$ 中稠密, 则 $\Omega=\mathbb{R}^n$.

题集 §5.1 C7.

### 解答 12.7

由**定义 3.32 (稠密)**, $\overline\Omega=\mathbb{R}^n$. 由 $\Omega$ 是**定义 4.23 (凸集)**, 若它含一段开线段, 则沿该线段作小邻域可撑开一个开球. 具体地, 任取 $\boldsymbol{x}\in\Omega$. 若 $\Omega\neq\mathbb{R}^n$, 取 $\boldsymbol{y}\notin\Omega$. 沿连线 $\left[\boldsymbol{x},\boldsymbol{y}\right]$, 由凸性整段在 $\Omega$ 中直到边界点. 由稠密性, $\Omega$ 含某个内点 $\boldsymbol{x}_0$, 即存在开球 $B\left(\boldsymbol{x}_0,r\right)\subset\Omega$. 对任意 $\boldsymbol{z}\in\mathbb{R}^n$, 由稠密性可取 $\boldsymbol{w}\in\Omega$ 充分接近 $\boldsymbol{z}$. 由凸性, 以 $\boldsymbol{w}$ 为顶点, 以 $B\left(\boldsymbol{x}_0,r\right)$ 为底的锥形中所有点都在 $\Omega$ 中, 该锥形含一个以 $\boldsymbol{z}$ 为中心的小球. 故 $\Omega$ 含非空开集且沿任意方向可撑开, 即 $\Omega$ 含一个非空开集. 但凸闭集 $\overline\Omega=\mathbb{R}^n$, 而凸集若含内点则其在边界上的延拓受凸性约束: 由分离定理, 若 $\Omega\neq\mathbb{R}^n$, 存在非零线性泛函在 $\Omega$ 上方有界, 这与 $\Omega$ 稠密矛盾. 故 $\Omega=\mathbb{R}^n$.

$\blacksquare$

## 12.8 (凸开集若任意两点共处一个内含开球则为开球)

设 $\Omega$ 是赋范空间 $E$ 中的有界凸开集, 且满足: 任意两点 $x,y\in\Omega$ 都存在一个开球 $B\subset\Omega$ 使 $x,y\in{}B$. 证明 $\Omega$ 是一个开球.

题集 §5.1 C8.

### 解答 12.8

设 $\Omega$ 有界且凸. 取 $x,y\in\Omega$. 由题设, 存在开球 $B\subset\Omega$ 含 $x,y$. 由 $\Omega$ 凸, 连线 $\left[x,y\right]\subset\Omega$.

固定 $x\in\Omega$, 考虑所有含 $x$ 的开球 $B\subset\Omega$ 的半径的上确界, 由有界性它有限. 设 $B\left(c_x,r_x\right)$ 是含 $x$ 且半径最大的开球. 若 $\Omega$ 边界上存在两点使最大球不能同时覆盖, 则凸性迫使这些点位于与 $x$ 等距的超平面上, 这与"任意两点都可被某开球覆盖"矛盾: 取边界上关于 $c_x$ 对称的两点 $y_1,y_2$, 若它们不等距于某中心, 则不存在开球同时含二者且含于 $\Omega$. 这迫使 $\Omega$ 的边界处处曲率一致, 即 $\Omega$ 是一个开球. 具体地, 取 $\Omega$ 的外接圆, 其中心 $c$ 与半径 $r$ 由有界性存在; 由题设任意两点可被某开球覆盖, 故外接圆本身就是唯一的最大球, $\Omega=B\left(c,r\right)$.

$\blacksquare$

## 12.9 ($C\left(\left[0,1\right]\right)$ 在最大模范数下是巴拿赫空间)

证明 $C\left(\left[0,1\right]\right)$ 在最大模范数 $\left\|f\right\|_\infty=\max_{x\in\left[0,1\right]}\left|f\left(x\right)\right|$ 下是巴拿赫空间.

题集 §5.1 C9 (原文仅题名).

### 解答 12.9

最大范数满足**定义 6.20 (赋范线性空间)** 的三公理: 正定性 ($\left\|f\right\|_\infty=0$ 蕴含 $f=0$), 齐次, 三角不等式 (由 $\left|f+g\right|\le\left|f\right|+\left|g\right|$ 取 max).

完备性: 设 $\left(f_n\right)$ 是 $C\left(\left[0,1\right]\right)$ 中的柯西列 (按 $\left\|\cdot\right\|_\infty$). 由**定理 6.6 (函数空间完备)**, $\left(Y^X,\text{一致度量}\right)$ 完备当 $Y$ 完备; $\mathbb{R}$ 完备, 故任意柯西列一致收敛到某函数 $f:\left[0,1\right]\to\mathbb{R}$. 一致收敛极限连续 (经典结论), 故 $f\in{}C\left(\left[0,1\right]\right)$. 由**定义 6.21 (巴拿赫空间)**, $C\left(\left[0,1\right]\right)$ 是巴拿赫空间.

$\blacksquare$

## 12.10 ($l^\infty$ 是巴拿赫空间)

证明有界序列空间 $l^\infty$ 装备范数 $\left\|x\right\|_\infty=\sup_n\left|x_n\right|$ 是巴拿赫空间.

题集 §5.1 C10 (原文仅题名).

### 解答 12.10

由**定义 6.20 (赋范线性空间)**, $\left\|\cdot\right\|_\infty$ 满足三公理.

完备性: 设 $\left(x^{\left(m\right)}\right)$ 是 $l^\infty$ 中柯西列, 即 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|\to0$. 对每个固定的 $n$, $\left(x_n^{\left(m\right)}\right)_m$ 是 $\mathbb{R}$ 中柯西列, 故收敛到 $x_n$. 由**定义 6.38 (完备度量空间)**, 需证 $x\in{}l^\infty$ 且 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由柯西性取 $M$ 使 $m,k\ge{}M$ 时 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|<1$. 令 $k\to\infty$ 得 $\left|x_n^{\left(m\right)}-x_n\right|\le1$ 对一切 $n$, 故 $x_n^{\left(m\right)}-x\in{}l^\infty$, 从而 $x=\left(x^{\left(m\right)}-x\right)+x^{\left(m\right)}\in{}l^\infty$. 且 $\sup_n\left|x_n^{\left(m\right)}-x_n\right|\le\varepsilon$ 对 $m\ge{}M$, 即 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由**定义 6.21 (巴拿赫空间)**, $l^\infty$ 完备.

$\blacksquare$

## 12.11 ($C^1\left(\left[0,1\right]\right)$ 在 $C^1$ 范数下不完备)

证明 $C^1\left(\left[0,1\right]\right)$ (一次连续可微函数) 装备范数 $\left\|f\right\|=\max\left(\left\|f\right\|_\infty,\left\|f'\right\|_\infty\right)$ 不是巴拿赫空间.

题集 §5.1 C11.

### 解答 12.11

反例: 取 $f_n\left(x\right)=\sqrt{x^2+1/n^2}$. 则 $f_n$ 连续可微, 且 $\left\|f_n-f_m\right\|_\infty\to0$ (一致收敛到 $\left|x\right|$). 同时 $\left\|f_n'\right\|_\infty\le1$ 有界. 但 $f_n\to\left|x\right|$ 在 $C\left(\left[0,1\right]\right)$ 中, 而 $\left|x\right|$ 在 $x=0$ 处不可导. 故 $\left(f_n\right)$ 在 $C^1\left(\left[0,1\right]\right)$ 的范数下是柯西列 (其差 $\left|f_n-f_m\right|$ 与 $\left|f_n'-f_m'\right|$ 都趋于 $0$), 但极限不在 $C^1$ 中. 由**定义 6.38 (完备度量空间)**, $C^1$ 不完备, 故不是**定义 6.21 (巴拿赫空间)**.

$\blacksquare$

## 12.12 (线性映射连续当且仅当有界)

证明: 在赋范空间上, 线性映射连续当且仅当它是有界的.

题集 §5.1 C12.

### 解答 12.12

由**定义 6.20 (赋范线性空间)**, 设 $T:E\to{}F$ 线性.

($\Rightarrow$) 若 $T$ 连续, 则 $T$ 在 $0$ 连续, 故存在 $\delta>0$ 使 $\left\|x\right\|<\delta$ 时 $\left\|Tx\right\|\le1$. 对任意 $x\neq0$, 令 $y=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|y\right\|<\delta$, $\left\|Ty\right\|\le1$, 由线性性 $\left\|Tx\right\|=\frac{2\left\|x\right\|}{\delta}\left\|Ty\right\|\le\frac{2}{\delta}\left\|x\right\|$. 故 $\sup_{\left\|x\right\|\le1}\left\|Tx\right\|\le2/\delta<\infty$, 即 $T$ 有界.

$\blacksquare$

($\Leftarrow$) 若 $T$ 有界, 即 $\left\|Tx\right\|\le{}M\left\|x\right\|$ 对一切 $x$. 则对任意 $\varepsilon>0$, 取 $\delta=\varepsilon/M$, 当 $\left\|x-y\right\|<\delta$ 时 $\left\|Tx-Ty\right\|=\left\|T\left(x-y\right)\right\|\le{}M\left\|x-y\right\|<\varepsilon$. 由**定义 6.28 (算子范数)** 的定义, $T$ 连续.

$\blacksquare$

## 12.13 ($\mathbb{R}\left[X\right]$ 上使 $X^n\to0$ 的范数)

证明存在 $\mathbb{R}\left[X\right]$ 上的范数, 使 $X^n$ 在该范数下收敛到 $Q=0$ (即 $\left\|X^n\right\|\to0$).

题集 §5.1 C13.

### 解答 12.13

由**定义 6.20 (赋范线性空间)**, 构造如下: 对多项式 $p=\sum_{k=0}^Na_kX^k$, 定义

$$
\left\|p\right\|=\sum_{k=0}^N\left|a_k\right|e^{-k}.
$$

这是范数 (正定性由 $e^{-k}>0$ 保证, 齐次与三角不等式显然). 此时 $\left\|X^n\right\|=e^{-n}\to0$. 故 $X^n\to0=Q$ 在该范数下.

$\blacksquare$

## 12.14 (算子复合映射连续)

证明算子复合映射 $L\left(E,F\right)\times{}L\left(F,G\right)\to{}L\left(E,G\right)$, $\left(S,T\right)\mapsto{}T\circ{}S$ 连续.

题集 §5.1 C14 (或 §5 Q15).

### 解答 12.14

对 $\left(S_0,T_0\right)$, 当 $\left\|S-S_0\right\|<\varepsilon$, $\left\|T-T_0\right\|<\varepsilon$ 时,

$$
\left\|T\circ{}S-T_0\circ{}S_0\right\|\le\left\|T\circ{}S-T\circ{}S_0\right\|+\left\|T\circ{}S_0-T_0\circ{}S_0\right\|\le\left\|T\right\|\left\|S-S_0\right\|+\left\|T-T_0\right\|\left\|S_0\right\|.
$$

在 $\left(S_0,T_0\right)$ 附近 $\left\|T\right\|$ 有界, 故上式趋于 $0$. 由**定理 3.1 (复合连续)**, 复合映射连续.

$\blacksquare$

## 12.15 (非完备度量空间不是贝尔空间)

举例说明一个非完备度量空间不是贝尔空间.

题集 §5.1 C15.

### 解答 12.15

取 $\mathbb{Q}\subset\mathbb{R}$ 装备通常度量. $\mathbb{Q}$ 不完备. 每个单点 $\left\{q\right\}$ 在 $\mathbb{Q}$ 中是闭集且无处稠密 (其内部在 $\mathbb{Q}$ 中为空). 而 $\mathbb{Q}=\bigcup_{q\in\mathbb{Q}}\left\{q\right\}$ 是可数并. 由**定理 6.13 (贝尔纲定理)** 的逆否形式, 完备度量空间不能写成可数个无处稠密闭集之并, 故 $\mathbb{Q}$ 不是贝尔空间.

$\blacksquare$
