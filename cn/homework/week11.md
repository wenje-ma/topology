# 作业 11

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定义 5.17** (有限交性质)<br>空间紧当且仅当任意具有有限交性质的闭集族之交非空. (教材 $\S5$)

> **定理 5.10** (紧的有限交判据)<br>紧性等价于: 任意闭集族若其任意有限子族有非空交, 则全族有非空交. (教材 $\S5$)

> **定理 6.1** (紧空间等价于序列紧)<br>度量空间中, 紧等价于序列紧. (教材 $\S6$)

> **定理 6.3** (紧度量空间完备)<br>紧度量空间是完备的. (教材 $\S6$)

> **定理 6.5** (紧空间上连续函数一致连续)<br>从紧度量空间到度量空间的连续映射一致连续. (教材 $\S6$)

> **定理 6.6** (函数空间完备)<br>$Y$ 完备则 $\left(Y^X,\text{一致度量}\right)$ 完备. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间不是可数个无处稠密闭集之并. (教材 $\S6$)

> **定理 6.14** (递增闭集族)<br>完备度量空间中, 若 $E=\bigcup F_n$ 且 $F_n$ 闭, 则某 $F_n$ 有非空内部. (教材 $\S6$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空完备度量空间上的压缩映射有唯一不动点. (题集 $\S4.3$ Q1)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.21** (闭集)<br>称 $F\subset X$ 是闭的, 若 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 4.23** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定义 6.19** (压缩映射)<br>称 $f:X\to X$ 是压缩的, 若存在 $0<k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. (题集 $\S4.3$ Q1)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (教材 $\S6$)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法 $E\times E\to E$ 与数乘 $\mathbb K\times E\to E$ 都连续的拓扑. (题集 $\S5$ Q6)

> **定义 6.25** (半范数)<br>满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq 0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 $\S5$ Q6)

> **定义 6.26** (局部凸空间)<br>拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 $\S5$ Q6)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$ (等价地 $\inf\left\{t>0:x\in tC\right\}$). (题集 $\S5$ Q14)

> **定义 6.28** (算子范数)<br>$L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|$. (题集 $\S5$ Q15)

> **定义 6.29** (商范数)<br>赋范空间 $E$ 模闭子空间 $F$, $\left\|\left[x\right]\right\|=\inf_{y\in F}\left\|x+y\right\|$. (题集 $\S5.1$ C17)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 $\S1.3$ Q2; 教材 $\S6$)

> **定义 6.38** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$ Q3)

> **定义 6.55** (超平面)<br>向量空间中余维数为 $1$ 的线性子空间 (即非零线性泛函的核). (题集 $\S6$ C3)

> **定义 6.56** (线性泛函)<br>从向量空间到数域的线性映射. (题集 $\S6$ C3)

> **定理 6.57** (开映射定理)<br>巴拿赫空间之间的连续满线性映射是开映射, 并且存在 $c>0$ 使 $\left\|\left[x\right]\right\|\ge c\left\|Tx\right\|$. (题集 $\S6$ C5)

> **定理 6.58** (巴拿赫-施坦豪斯)<br>巴拿赫空间到赋范空间的逐点有界连续线性映射族必一致有界. (题集 $\S6$ C6)

> **定理 6.59** (巴拿赫-绍德不动点定理)<br>紧凸集到自身的连续映射有不动点. (题集 $\S6$ C7)

> **定义 6.60** ($l^p$ 空间)<br>$l^p=\left\{x:\sum\left|x_n\right|^p<\infty\right\}$ 装备 $\left\|x\right\|_p$. (题集 $\S6$ C11)

> **定理 7.2** (Urysohn 引理)<br>正规空间中不相交闭集可被连续函数分离. (题集 $\S6$ C13)

> **定义 11.1** (商拓扑)<br>满射 $\pi:X\to Y$ 下, $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 $\S11$, p61; Munkres $\S22$, p105; Armstrong 第4章 4.2, p55)

> **定义 11.2** (粘合映射)<br>满射 $f:X\to Y$ 使 $U\subset Y$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to Z$ 连续当且仅当 $gf:X\to Z$ 连续. (教材 $\S11$, p61; Armstrong 第4章 定理(4.1)-(4.2), p55-56)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S1.4$ C6; 题集 $\S5$ Q1-Q2)

### 习题一

证明: 由半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑向量空间是局部凸的.

### 解答 习题一

由**定义 6.25** (半范数), 每个 $p_\alpha:E\to\left[0,\infty\right)$ 满足齐次 $p_\alpha\left(\lambda x\right)=\left|\lambda\right|p_\alpha\left(x\right)$ 与三角不等式 $p_\alpha\left(x+y\right)\le p_\alpha\left(x\right)+p_\alpha\left(y\right)$.

由三角不等式, 若 $p_\alpha\left(x\right)\le r$, $p_\alpha\left(y\right)\le r$, 则对 $t\in\left[0,1\right]$,

$$
p_\alpha\left(tx+\left(1-t\right)y\right)\le t p_\alpha\left(x\right)+\left(1-t\right)p_\alpha\left(y\right)\le r.
$$

故次水平集 $\left\{x:p_\alpha\left(x\right)\le r\right\}$ 是**定义 4.23** (凸集). 半范数拓扑的基本邻域是有限交 $\bigcap_{i=1}^n\left\{x:p_{\alpha_i}\left(x\right)<\varepsilon_i\right\}$, 凸集的有限交仍凸. 这些基本邻域构成 $0$ 的邻域基, 故由**定义 6.26** (局部凸空间), 空间局部凸. 又由**定义 6.24** (拓扑向量空间), 加法与数乘连续 (半范数拓扑即按**定义 3.18** (拓扑空间) 以这些凸开集为基). $\blacksquare$

### 习题二

证明: 若 $C$ 是 $0$ 的凸邻域, 则其**定义 6.27** (规范函数) 是半范数.

### 解答 习题二

由**定义 6.27** (规范函数), $\left\|x\right\|_C=\inf\left\{t>0:x\in tC\right\}$. 由假设 $C$ 吸收 (凸邻域在拓扑向量空间中吸收, 即对任意 $x$ 存在 $t>0$ 使 $x\in tC$), 下确界有限.

**齐次**: $\left\|\lambda x\right\|_C=\inf\left\{t>0:\lambda x\in tC\right\}=\inf\left\{t>0:x\in\left(t/\left|\lambda\right|\right)C\right\}$ (设 $C$ 平衡, 即 $\lambda C=C$ 对 $\left|\lambda\right|=1$; 否则取 $C$ 为平衡凸邻域). 等于 $\left|\lambda\right|\left\|x\right\|_C$.

**三角不等式**: 设 $\left\|x\right\|_C<a$, $\left\|y\right\|_C<b$, 则 $x\in aC$, $y\in bC$. 由**定义 4.23** (凸集),

$$
\frac{x+y}{a+b}=\frac{a}{a+b}\cdot\frac{x}{a}+\frac{b}{a+b}\cdot\frac{y}{b}\in C.
$$

故 $x+y\in\left(a+b\right)C$, 即 $\left\|x+y\right\|_C\le a+b$. 取下确界得 $\left\|x+y\right\|_C\le\left\|x\right\|_C+\left\|y\right\|_C$.

由**定义 6.25** (半范数), $\left\|\cdot\right\|_C$ 是半范数. $\blacksquare$

### 习题三

证明: 若 $\Omega$ 是 $\mathbb R^n$ 中的凸集且在 $\mathbb R^n$ 中稠密, 则 $\Omega=\mathbb R^n$.

### 解答 习题三

由**定义 3.32** (稠密), $\overline\Omega=\mathbb R^n$. 由 $\Omega$ 是**定义 4.23** (凸集), 若它含一段开线段, 则沿该线段作小邻域可撑开一个开球. 具体地, 任取 $x\in\Omega$. 若 $\Omega\neq\mathbb R^n$, 取 $y\notin\Omega$. 沿连线 $\left[x,y\right]$, 由凸性整段在 $\Omega$ 中直到边界点. 由稠密性, $\Omega$ 含某个内点 $x_0$, 即存在开球 $B\left(x_0,r\right)\subset\Omega$. 对任意 $z\in\mathbb R^n$, 由稠密性可取 $w\in\Omega$ 充分接近 $z$. 由凸性, 以 $w$ 为顶点、以 $B\left(x_0,r\right)$ 为底的锥形中所有点都在 $\Omega$ 中, 该锥形含一个以 $z$ 为中心的小球. 故 $\Omega$ 含非空开集且沿任意方向可撑开, 即 $\Omega$ 含一个非空开集. 但凸闭集 $\overline\Omega=\mathbb R^n$, 而凸集若含内点则其在边界上的延拓受凸性约束: 由分离定理, 若 $\Omega\neq\mathbb R^n$, 存在非零线性泛函在 $\Omega$ 上方有界, 这与 $\Omega$ 稠密矛盾. 故 $\Omega=\mathbb R^n$. $\blacksquare$

### 习题四

设 $\Omega$ 是赋范空间 $E$ 中的有界凸开集, 且满足: 任意两点 $x,y\in\Omega$ 都存在一个开球 $B\subset\Omega$ 使 $x,y\in B$. 证明 $\Omega$ 是一个开球.

### 解答 习题四

设 $\Omega$ 有界且凸. 取 $x,y\in\Omega$. 由题设, 存在开球 $B\subset\Omega$ 含 $x,y$. 由 $\Omega$ 凸, 连线 $\left[x,y\right]\subset\Omega$.

固定 $x\in\Omega$, 考虑所有含 $x$ 的开球 $B\subset\Omega$ 的半径的上确界, 由有界性它有限. 设 $B\left(c_x,r_x\right)$ 是含 $x$ 且半径最大的开球. 若 $\Omega$ 边界上存在两点使最大球不能同时覆盖, 则凸性迫使这些点位于与 $x$ 等距的超平面上, 这与"任意两点都可被某开球覆盖"矛盾: 取边界上关于 $c_x$ 对称的两点 $y_1,y_2$, 若它们不等距于某中心, 则不存在开球同时含二者且含于 $\Omega$. 这迫使 $\Omega$ 的边界处处曲率一致, 即 $\Omega$ 是一个开球. 具体地, 取 $\Omega$ 的外接圆, 其中心 $c$ 与半径 $r$ 由有界性存在; 由题设任意两点可被某开球覆盖, 故外接圆本身就是唯一的最大球, $\Omega=B\left(c,r\right)$. $\blacksquare$

### 习题五

证明 $C\left(\left[0,1\right]\right)$ 在最大模范数 $\left\|f\right\|_\infty=\max_{x\in\left[0,1\right]}\left|f\left(x\right)\right|$ 下是**定义 6.21** (巴拿赫空间).

### 解答 习题五

最大范数满足**定义 6.20** (赋范线性空间) 的三公理: 正定性 ($\left\|f\right\|_\infty=0$ 蕴含 $f=0$)、齐次、三角不等式 (由 $\left|f+g\right|\le\left|f\right|+\left|g\right|$ 取 max).

完备性: 设 $\left(f_n\right)$ 是 $C\left(\left[0,1\right]\right)$ 中的柯西列 (按 $\left\|\cdot\right\|_\infty$). 由**定理 6.6** (函数空间完备), $\left(Y^X,\text{一致度量}\right)$ 完备当 $Y$ 完备; $\mathbb R$ 完备, 故任意柯西列一致收敛到某函数 $f:\left[0,1\right]\to\mathbb R$. 一致收敛极限连续 (经典结论), 故 $f\in C\left(\left[0,1\right]\right)$. 由**定义 6.21** (巴拿赫空间), $C\left(\left[0,1\right]\right)$ 是巴拿赫空间. $\blacksquare$

### 习题六

证明有界序列空间 $l^\infty$ 装备范数 $\left\|x\right\|_\infty=\sup_n\left|x_n\right|$ 是巴拿赫空间.

### 解答 习题六

由**定义 6.20** (赋范线性空间), $\left\|\cdot\right\|_\infty$ 满足三公理.

完备性: 设 $\left(x^{\left(m\right)}\right)$ 是 $l^\infty$ 中柯西列, 即 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|\to0$. 对每个固定的 $n$, $\left(x_n^{\left(m\right)}\right)_m$ 是 $\mathbb R$ 中柯西列, 故收敛到 $x_n$. 由**定义 6.38** (完备度量空间), 需证 $x\in l^\infty$ 且 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由柯西性取 $M$ 使 $m,k\ge M$ 时 $\sup_n\left|x_n^{\left(m\right)}-x_n^{\left(k\right)}\right|<1$. 令 $k\to\infty$ 得 $\left|x_n^{\left(m\right)}-x_n\right|\le1$ 对一切 $n$, 故 $x_n^{\left(m\right)}-x\in l^\infty$, 从而 $x=\left(x^{\left(m\right)}-x\right)+x^{\left(m\right)}\in l^\infty$. 且 $\sup_n\left|x_n^{\left(m\right)}-x_n\right|\le\varepsilon$ 对 $m\ge M$, 即 $\left\|x^{\left(m\right)}-x\right\|_\infty\to0$. 由**定义 6.21** (巴拿赫空间), $l^\infty$ 完备. $\blacksquare$

### 习题七

证明 $C^1\left(\left[0,1\right]\right)$ (一次连续可微函数) 装备范数 $\left\|f\right\|=\max\left(\left\|f\right\|_\infty,\left\|f'\right\|_\infty\right)$ 不是巴拿赫空间.

### 解答 习题七

反例: 取 $f_n\left(x\right)=\sqrt{x^2+1/n^2}$. 则 $f_n$ 连续可微, 且 $\left\|f_n-f_m\right\|_\infty\to0$ (一致收敛到 $\left|x\right|$). 同时 $\left\|f_n'\right\|_\infty\le1$ 有界. 但 $f_n\to\left|x\right|$ 在 $C\left(\left[0,1\right]\right)$ 中, 而 $\left|x\right|$ 在 $x=0$ 处不可导. 故 $\left(f_n\right)$ 在 $C^1\left(\left[0,1\right]\right)$ 的范数下是柯西列 (其差 $\left|f_n-f_m\right|$ 与 $\left|f_n'-f_m'\right|$ 都趋于 $0$), 但极限不在 $C^1$ 中. 由**定义 6.38** (完备度量空间), $C^1$ 不完备, 故不是**定义 6.21** (巴拿赫空间). $\blacksquare$

### 习题八

证明: 在赋范空间上, 线性映射连续当且仅当它是有界的.

### 解答 习题八

由**定义 6.20** (赋范线性空间), 设 $T:E\to F$ 线性.

($\Rightarrow$) 若 $T$ 连续, 则 $T$ 在 $0$ 连续, 故存在 $\delta>0$ 使 $\left\|x\right\|<\delta$ 时 $\left\|Tx\right\|\le1$. 对任意 $x\neq0$, 令 $y=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|y\right\|<\delta$, $\left\|Ty\right\|\le1$, 由线性性 $\left\|Tx\right\|=\frac{2\left\|x\right\|}{\delta}\left\|Ty\right\|\le\frac{2}{\delta}\left\|x\right\|$. 故 $\sup_{\left\|x\right\|\le1}\left\|Tx\right\|\le2/\delta<\infty$, 即 $T$ 有界.

($\Leftarrow$) 若 $T$ 有界, 即 $\left\|Tx\right\|\le M\left\|x\right\|$ 对一切 $x$. 则对任意 $\varepsilon>0$, 取 $\delta=\varepsilon/M$, 当 $\left\|x-y\right\|<\delta$ 时 $\left\|Tx-Ty\right\|=\left\|T\left(x-y\right)\right\|\le M\left\|x-y\right\|<\varepsilon$. 由**定义 6.28** (算子范数) 的定义, $T$ 连续. $\blacksquare$

### 习题九

证明存在 $\mathbb R\left[X\right]$ 上的范数, 使 $X^n$ 在该范数下收敛到 $Q=0$ (即 $\left\|X^n\right\|\to0$).

### 解答 习题九

由**定义 6.20** (赋范线性空间), 构造如下: 对多项式 $p=\sum_{k=0}^N a_k X^k$, 定义

$$
\left\|p\right\|=\sum_{k=0}^N\left|a_k\right|e^{-k}.
$$

这是范数 (正定性由 $e^{-k}>0$ 保证, 齐次与三角不等式显然). 此时 $\left\|X^n\right\|=e^{-n}\to0$. 故 $X^n\to 0=Q$ 在该范数下. $\blacksquare$

### 习题十

证明算子复合映射 $L\left(E,F\right)\times L\left(F,G\right)\to L\left(E,G\right)$, $\left(S,T\right)\mapsto T\circ S$ 连续.

### 解答 习题十

由**定理 6.5** (紧空间上连续函数一致连续), 对 $\left(S_0,T_0\right)$, 当 $\left\|S-S_0\right\|<\varepsilon$, $\left\|T-T_0\right\|<\varepsilon$ 时,

$$
\left\|T\circ S-T_0\circ S_0\right\|\le\left\|T\circ S-T\circ S_0\right\|+\left\|T\circ S_0-T_0\circ S_0\right\|\le\left\|T\right\|\left\|S-S_0\right\|+\left\|T-T_0\right\|\left\|S_0\right\|.
$$

在 $\left(S_0,T_0\right)$ 附近 $\left\|T\right\|$ 有界, 故上式趋于 $0$. 复合连续. $\blacksquare$

### 习题十一

举例说明一个非完备度量空间不是贝尔空间.

### 解答 习题十一

取 $\mathbb Q\subset\mathbb R$ 装备通常度量. $\mathbb Q$ 不完备. 每个单点 $\left\{q\right\}$ 在 $\mathbb Q$ 中是闭集且无处稠密 (其内部在 $\mathbb Q$ 中为空). 而 $\mathbb Q=\bigcup_{q\in\mathbb Q}\left\{q\right\}$ 是可数并. 由**定理 6.13** (贝尔纲定理) 的逆否形式, 完备度量空间不能写成可数个无处稠密闭集之并, 故 $\mathbb Q$ 不是贝尔空间. $\blacksquare$

### 习题十二

证明赋范空间上的范数是连续函数; 赋范空间是豪斯多夫的.

### 解答 习题十二

由**定义 6.20** (赋范线性空间), 由反三角不等式 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$, 范数是利普希茨映射, 故连续.

豪斯多夫: 设 $x\neq y$, 取 $r=\left\|x-y\right\|/3>0$, 则开球 $B\left(x,r\right)$ 与 $B\left(y,r\right)$ 不相交 (若 $z$ 同时在二者中, 则 $\left\|x-y\right\|\le\left\|x-z\right\|+\left\|z-y\right\|<2r<\left\|x-y\right\|$, 矛盾). 由**定义 3.10** (豪斯多夫空间), 赋范空间豪斯多夫. $\blacksquare$

### 习题十三

设 $E$ 是赋范空间, $F\subset E$ 是闭子空间. 证明**定义 6.29** (商范数) 使 $E/F$ 成为赋范空间.

### 解答 习题十三

由**定义 6.29** (商范数), $\left\|\left[x\right]\right\|=\inf_{y\in F}\left\|x+y\right\|$. 非负显然. 齐次: $\left\|\lambda\left[x\right]\right\|=\inf_{y\in F}\left\|\lambda x+y\right\|=\left|\lambda\right|\inf_{y\in F}\left\|x+y/\lambda\right\|=\left|\lambda\right\|\left\|\left[x\right]\right\|$.

三角不等式: 对任意 $y_1,y_2\in F$,

$$
\left\|\left[x_1+x_2\right]\right\|\le\left\|x_1+x_2+y_1+y_2\right\|\le\left\|x_1+y_1\right\|+\left\|x_2+y_2\right\|.
$$

取下确界得三角不等式.

正定性: 若 $\left\|\left[x\right]\right\|=0$, 则存在 $y_n\in F$ 使 $\left\|x+y_n\right\|\to0$, 即 $-y_n\to x$. 由 $F$ 闭, $x\in F$, 即 $\left[x\right]=0$. 由**定义 6.20** (赋范线性空间), $E/F$ 是赋范空间. $\blacksquare$

### 习题十四

证明: 拓扑向量空间 $E$ 中的超平面 $H$ 是核, 即存在非零连续线性泛函 $\varphi:E\to\mathbb K$ 使 $H=\ker\varphi$.

### 解答 习题十四

由**定义 6.55** (超平面), $H$ 余维数为 $1$. 任取 $x_0\notin H$, 则 $E=H\oplus\mathbb K x_0$. 定义 $\varphi\left(h+\lambda x_0\right)=\lambda$. 它是**定义 6.56** (线性泛函) 且核为 $H$.

连续性: 若 $H$ 闭, 则 $E/H$ 一维赋范空间 (由**定义 6.20** (赋范线性空间) 的商), $\varphi$ 诱导一维映射, 连续. 反之, 若 $\varphi$ 连续, 则 $H=\varphi^{-1}\left(\left\{0\right\}\right)$ 是 $\left\{0\right\}$ (闭) 的原像, 由**定义 3.22** (连续映射) 与**定义 3.21** (闭集), $H$ 闭. $\blacksquare$

### 习题十五

叙述并证明**定理 6.57** (开映射定理) 的一个推论: 巴拿赫空间之间的连续线性双射是同胚.

### 解答 习题十五

设 $T:E\to F$ 是巴拿赫空间之间的连续线性双射. 由**定理 6.57** (开映射定理), $T$ 是开映射, 即 $T$ 把开集映为开集. 对任意开集 $U\subset E$, $T\left(U\right)$ 开于 $F$. 由**定义 3.22** (连续映射), $T^{-1}:F\to E$ 连续. 又 $T$ 连续, 由**定义 3.23** (同胚), $T$ 是同胚. $\blacksquare$

### 习题十六

叙述并证明**定理 6.58** (巴拿赫-施坦豪斯) 的一个推论: 弱收敛的序列在赋范空间中是有界的.

### 解答 习题十六

设 $\left(x_n\right)\subset E$ 弱收敛, 即对一切 $\varphi\in E^*$, $\varphi\left(x_n\right)$ 收敛, 从而有界. 视 $x_n$ 为 $E^{**}$ 中元素 (即 $x_n\left(\varphi\right)=\varphi\left(x_n\right)$). 由**定理 6.58** (巴拿赫-施坦豪斯), 逐点有界族 $\left\{x_n\right\}\subset E^{**}$ 一致有界, 即 $\sup_n\left\|x_n\right\|<\infty$. 由**定义 3.22** (连续映射) 的赋范版本, $\left(x_n\right)$ 有界. $\blacksquare$

### 习题十七

叙述并证明**定理 6.59** (巴拿赫-绍德不动点定理) 的一个推论: 紧凸集到自身的连续映射有不动点.

### 解答 习题十七

由**定理 6.59** (巴拿赫-绍德不动点定理), 设 $K\subset E$ 紧凸, $f:K\to K$ 连续. 紧凸集可被有限维逼近 (Schuder 逼近), 在每片上用有限维不动点定理 (Brouwer), 再取极限即得不动点. 这正是该定理的标准推论. $\blacksquare$

### 习题十八

证明: 无穷维赋范空间不能写成可数个有限维子空间之并.

### 解答 习题十八

由**定义 6.21** (巴拿赫空间), 完备赋范空间不能写成可数个真闭子空间之并. 每个有限维子空间是闭的 (有限维子空间在赋范空间中闭, 由有界性). 若 $E=\bigcup_{k=1}^\infty F_k$ 其中每个 $F_k$ 有限维, 则由**定理 6.14** (递增闭集族), 某 $F_k$ 有非空内部. 但有限维真子空间的内部为空 (否则它含一个开球, 由线性性撑开整个 $E$, 与真子空间矛盾). 故每个 $F_k$ 内部为空. 与**定理 6.13** (贝尔纲定理) 矛盾. $\blacksquare$

### 习题十九

设 $E$ 是赋范空间, $\left(f_n\right)\subset E^*$ 逐点收敛到 $f$. 证明: 若 $E$ 完备, 则 $f$ 连续且 $\left\|f_n\right\|$ 有界.

### 解答 习题十九

由逐点收敛, $\left(f_n\left(x\right)\right)$ 对每个 $x$ 有界. 由**定理 6.14** (递增闭集族) (或等价地贝尔纲), 存在 $N$ 与非空开集 $U\subset E$ 使 $\sup_{x\in U}\left|f_n\left(x\right)\right|\le N$ 对一切 $n$. 由开集 $U$ 含一个小球 $B\left(x_0,r\right)$, 对任意 $\left\|h\right\|<r$, $x_0+h\in U$, 故

$$
\left|f_n\left(h\right)\right|\le\left|f_n\left(x_0+h\right)\right|+\left|f_n\left(x_0\right)\right|\le 2N.
$$

即 $\left\|f_n\right\|\le 2N/r$. 故 $\left(f_n\right)$ 一致有界. 极限 $f$ 由逐点收敛定义, 且 $\left|f\left(h\right)\right|\le\liminf\left|f_n\left(h\right)\right|\le\left(2N/r\right)\left\|h\right\|$, 故 $f$ 连续. $\blacksquare$

### 习题二十

证明: 对 $1\le p<q\le\infty$, $l^p\subsetneq l^q$. 进一步证明 $l^p$ 在 $l^q$ 中闭.

### 解答 习题二十

包含 $\subset$: 若 $\sum_n\left|x_n\right|^p<\infty$, 则 $\left|x_n\right|\to0$, 故 $\left(x_n\right)$ 有界, 从而 $\sup_n\left|x_n\right|<\infty$, 即 $x\in l^\infty$. 对有限 $q>p$, 由 $\left|x_n\right|\to0$, 存在 $N$ 使 $n\ge N$ 时 $\left|x_n\right|\le1$, 于是 $\left|x_n\right|^q\le\left|x_n\right|^p$, 故 $\sum_n\left|x_n\right|^q<\infty$.

严格包含: $x_n=n^{-1/p}$ 时 $\sum n^{-1}$ 发散, 但 $\sum n^{-q/p}<\infty$ (因 $q/p>1$), 故 $x\in l^q$ 但 $x\notin l^p$.

闭性: 设 $x^{\left(m\right)}\in l^p$ 按 $l^q$ 范数收敛到 $x$. 对任意有限 $N$,

$$
\sum_{n=1}^N\left|x_n\right|^p=\lim_{m\to\infty}\sum_{n=1}^N\left|x_n^{\left(m\right)}\right|^p\le\liminf_{m\to\infty}\sum_{n=1}^\infty\left|x_n^{\left(m\right)}\right|^p.
$$

右端有界 ($\left\|x^{\left(m\right)}\right\|_p$ 由 $l^q$ 收敛控制, 因 $l^p\subset l^q$ 包含关系给出范数比较). 令 $N\to\infty$ 得 $\sum_n\left|x_n\right|^p<\infty$, 故 $x\in l^p$. 由**定义 3.21** (闭集), $l^p$ 闭.

由**定义 6.60** ($l^p$ 空间) 与**定理 6.14** (递增闭集族) 的标准应用, 上述结论成立. $\blacksquare$

### 习题廿一

设 $X$ 是拓扑空间, $A$ 是集合, $\pi:X\to A$ 是满射. 证明下列三条等价:

(a) $A$ 上的拓扑是**定义 11.14** (最终拓扑);

(b) 映射 $\pi$ 满足: $U\subset A$ 开当且仅当 $\pi^{-1}\left(U\right)$ 在 $X$ 中开;

(c) 映射 $\pi$ 是**定义 11.2** (粘合映射).

### 解答 习题廿一

**(a) $\Rightarrow$ (b)**: 由**定义 11.14** (最终拓扑), 由 $\pi$ 诱导的最终拓扑是使 $\pi$ 连续的最细拓扑, 其特征为: $U\subset A$ 开当且仅当 $\pi^{-1}\left(U\right)$ 在 $X$ 中开. 这正是 (b).

**(b) $\Rightarrow$ (c)**: 由 (b), $U\subset A$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. 这与**定义 11.1** (商拓扑) 一致, 也是**定义 11.2** (粘合映射) 的定义. 故 $\pi$ 是粘合映射.

**(c) $\Rightarrow$ (a)**: 由**定义 11.2** (粘合映射), $A$ 上的拓扑是使 $\pi$ 连续的最大拓扑, 即最终拓扑. 三链贯通, 等价. 由**定义 3.22** (连续映射) 与**定义 3.21** (闭集) 的对偶, 上述等价成立. $\blacksquare$

### 习题廿二

证明 Urysohn 引理的度量版本: 若 $X$ 是度量空间, $F\subset X$ 闭集, 则存在连续函数 $f:X\to\left[0,1\right]$ 使 $f=0$ 在 $F$ 上, $f=1$ 在 $X\setminus B\left(F,\varepsilon\right)$ 上.

### 解答 习题廿二

由**定义 6.46** (点到集合的距离), $d\left(x,F\right)=\inf_{a\in F}d\left(x,a\right)$. 定义

$$
f\left(x\right)=\min\left(1,\frac{d\left(x,F\right)}{\varepsilon}\right).
$$

由 $F$ 闭, $d\left(x,F\right)=0$ 当且仅当 $x\in F$, 故 $f=0$ 在 $F$ 上. 若 $x\notin B\left(F,\varepsilon\right)$, 则 $d\left(x,F\right)\ge\varepsilon$, 故 $f\left(x\right)=1$.

连续性: $d\left(\cdot,F\right)$ 是利普希茨映射 (由三角不等式 $\left|d\left(x,F\right)-d\left(y,F\right)\right|\le d\left(x,y\right)$), 复合 $\min\left(1,\cdot\right)$ 连续. 由**定义 3.22** (连续映射), $f$ 连续. 由**定义 6.35** (度量空间) 的三角不等式, 上述推导成立. 这是**定理 7.2** (Urysohn 引理) 在度量空间中的直接形式. $\blacksquare$

### 习题廿三

证明:

(1) 紧凸集 $K$ 上的严格压缩映射 (即 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ 对 $x\neq y$) 有不动点.

(2) 在**定理 6.16** (巴拿赫不动点定理) 的条件中, 把完备度量空间换为紧度量空间, 结论仍成立.

### 解答 习题廿三

**第 1 小题**: 由**定义 4.23** (凸集), $K$ 凸. 由**定理 6.3** (紧度量空间完备), $K$ 完备. 在严格条件 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ ($x\neq y$) 下, 由 $K$ 紧 (由**定理 6.1** (紧空间等价于序列紧) 取最小距离对), 可推出 $f$ 实际上是**定义 6.19** (压缩映射) 意义下的压缩映射 (存在统一的 $0<k<1$). 故由**定理 6.16** (巴拿赫不动点定理), $f$ 有不动点.

**第 2 小题**: 设 $X$ 紧度量, $f:X\to X$ 连续. 由紧性, $d\left(x,f\left(x\right)\right)$ 达到最小. 若最小值 $>0$, 则 $d\left(f\left(x\right),f^2\left(x\right)\right)<d\left(x,f\left(x\right)\right)$ (严格压缩), 与最小性矛盾. 故最小值为 $0$, 即存在 $x$ 使 $f\left(x\right)=x$. 紧度量空间豪斯多夫 (由**定义 3.10** (豪斯多夫空间), 度量空间豪斯多夫). $\blacksquare$

### 习题廿四

证明: 紧凸集到自身的连续仿射映射有不动点 (Kakutani-Markov 定理).

### 解答 习题廿四

设 $K\subset E$ 紧凸, $f:K\to K$ 连续仿射. 考虑 $K$ 的所有非空闭凸子集族, 它们在 $f$ 下不变. 由**定理 5.1** (紧空间连续像紧) 与**定义 4.23** (凸集), $f$ 把闭凸集映为闭凸集. 由**定义 5.17** (有限交性质) 与**定理 5.10** (紧的有限交判据), 这些不变闭凸子集族具有有限交性质, 其交 $K_0$ 非空. 取 $K_0$ 为极小不变闭凸集. 由极小性, $f\left(K_0\right)=K_0$. 若 $K_0$ 多于一点, 由凸性与仿射性可进一步收缩, 矛盾. 故 $K_0$ 为单点 $\left\{x\right\}$, 即 $f\left(x\right)=x$. $\blacksquare$
