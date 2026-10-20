# 作业 11

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 4.23** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.10** (有限交判据)<br>$X$ 紧: 闭集族具有限交性质, 则全族交非空. (教材 $\S5$)

> **定义 5.17** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 6.1** (紧 $=$ 序列紧)<br>度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

> **定理 6.3** (紧度量空间完备)<br>紧度量空间是完备的. (教材 $\S6$)

> **定理 6.5** (紧空间上连续一致连续)<br>紧度量空间上连续映射一致连续. (教材 $\S6$)

> **定理 6.6** (函数空间完备)<br>$Y$ 完备则 $\left(Y^X,\text{一致度量}\right)$ 完备. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **定理 6.14** (递增闭集族)<br>完备度量空间若 $X=\bigcup_n F_n$ ($F_n$ 闭递增), 则某个 $F_n$ 有非空内部. (教材 $\S6$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空**定义 6.38** (完备度量空间) 上的**定义 6.19** (压缩映射) 有唯一不动点. (题集 $\S4.3$)

> **定义 6.19** (压缩映射)<br>称 $f:X\to X$ 是压缩的, 若存在 $0<k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. (题集 $\S4.3$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (题集 2025 年卷 B)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法 $E\times E\to E$ 与数乘 $\mathbb K\times E\to E$ 都连续的拓扑. (题集 $\S5$)

> **定义 6.25** (半范数)<br>满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq 0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 $\S5$)

> **定义 6.26** (局部凸空间)<br>拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 $\S5$)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$. (题集 $\S5$)

> **定义 6.28** (算子范数)<br>$L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|$. (题集 $\S5$)

> **定义 6.29** (商范数)<br>赋范空间商掉闭子空间后诱导的范数 $\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|$. (题集 $\S5$)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.38** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.46** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.55** (超平面)<br>赋范线性空间 $E$ 中余维数为 $1$ 的线性子空间 $H$, 即 $E/H$ 维数为 $1$. (题集 $\S6$)

> **定义 6.56** (线性泛函)<br>$E\to\mathbb R$ 的线性映射 $\varphi$ 称为线性泛函. (题集 $\S6$)

> **定理 6.57** (开映射定理)<br>巴拿赫空间之间的连续满线性映射是开映射 (把开集映为开集); 推论: 巴拿赫空间之间的连续线性双射之逆连续. (题集 $\S6$)

> **定理 6.58** (巴拿赫-施坦豪斯定理)<br>设 $E$ 是巴拿赫空间, $F$ 是赋范线性空间, $\left\{T_i\right\}_{i\in I}$ 是一族连续线性映射 $T_i:E\to F$. 若对每个 $x\in E$, $\sup_i\left\|T_i x\right\|<\infty$, 则 $\sup_i\left\|T_i\right\|<\infty$. (题集 $\S6$)

> **定理 6.59** (巴拿赫-绍德不动点定理)<br>巴拿赫空间中非空紧凸子集到自身的连续映射有不动点. (题集 $\S6$)

> **定义 6.60** (序列空间 $\ell^p$)<br>$\ell^p=\left\{x=\left(x_n\right):\sum_{n\ge 1}\left|x_n\right|^p<\infty\right\}$, 装备 $\left\|x\right\|_p=\left(\sum\left|x_n\right|^p\right)^{1/p}$; 当 $1\le p<\infty$ 时是巴拿赫空间. (题集 $\S6$)

> **定理 7.2** (乌雷松引理)<br>正规空间中不相交闭集 $A,B$ 有连续 $f:X\to\left[0,1\right]$, $f\big|_A=0$, $f\big|_B=1$. (教材 $\S7$)

> **定义 11.1** (商拓扑)<br>满射 $\pi:X\to Y$ 下, $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 $\S11$)

> **定义 11.2** (商映射)<br>满射 $\pi:X\to Y$ 使 $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. (教材 $\S11$)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S1.4$)

### 习题一

(半范数拓扑) 设 $E$ 是向量空间, $\left\{p_\alpha\right\}_{\alpha\in A}$ 是一族半范数. 证明以

$$
\left\{x:p_{\alpha_i}\left(x\right)<\epsilon,\ i=1,\dots,n\right\}
$$

为 $0$ 的邻域基生成的拓扑使 $E$ 成为**定义 6.24** (拓扑向量空间) 意义下的拓扑向量空间, 且 $E$ 局部凸.

### 解答 习题一

由**定义 6.25** (半范数), 每个 $p_\alpha$ 是凸函数. 上面的基本邻域是有限个凸集之交, 由**定义 4.23** (凸集) 仍凸, 故 $0$ 有凸邻域基, 由**定义 6.26** (局部凸空间) $E$ 局部凸.

加法连续: 对 $0$ 的基本邻域 $U=\left\{p_{\alpha_i}<\epsilon\right\}$, 取 $V=\left\{p_{\alpha_i}<\epsilon/2\right\}$, 则 $V+V\subset U$. 数乘连续由半范数齐次性与 $p_\alpha\left(\lambda x\right)$ 在 $\left(\lambda,x\right)$ 上连续 (局部估计) 推出. 由**定义 6.24** (拓扑向量空间), 加法与数乘连续, 故 $E$ 是拓扑向量空间. 由**定义 3.18** (拓扑空间) 该邻域基满足拓扑公理. $\blacksquare$

### 习题二

(凸集的规范函数) 设 $C$ 是向量空间 $E$ 中平衡、凸、吸收的集合. 证明其规范函数 $p\left(x\right)=\inf\left\{t>0:x\in tC\right\}$ 是**定义 6.25** (半范数) 意义下的半范数.

### 解答 习题二

由**定义 6.27** (规范函数), $p\left(x\right)=\inf\left\{t>0:x\in tC\right\}$.

(a) 齐次: 由 $C$ 平衡, $x\in tC$ 当且仅当 $\lambda x\in t\left|\lambda\right|C$, 故 $p\left(\lambda x\right)=\left|\lambda\right|p\left(x\right)$.

(b) 三角不等式: 若 $x\in sC$, $y\in tC$, 则由 $C$ 凸,

$$
x+y\in sC+tC=\left(s+t\right)\left(\frac{s}{s+t}C+\frac{t}{s+t}C\right)\subset\left(s+t\right)C.
$$

故 $p\left(x+y\right)\le s+t$, 取下确界得 $p\left(x+y\right)\le p\left(x\right)+p\left(y\right)$.

由**定义 6.25** (半范数), $p$ 是半范数. $\blacksquare$

### 习题三

(稠密凸集) 证明 $\mathbb R^n$ 中稠密凸集必为全空间. 用魏尔斯特拉斯多项式逼近定理说明在无穷维此结论不成立.

### 解答 习题三

**有限维**: 设 $C\subset\mathbb R^n$ 凸且稠密, 即由**定义 3.32** (稠密) $\overline C=\mathbb R^n$. 任取 $x\in\mathbb R^n$. 取 $n+1$ 个点 $c_0,\dots,c_n\in C$ (由稠密性可取到) 使 $x$ 落在它们的凸包内部. 具体地, 取 $c_i$ 充分靠近 $x$ 且方向张成 $\mathbb R^n$, 则 $x=\sum_{i=0}^n\lambda_i c_i$, $\lambda_i>0$, $\sum\lambda_i=1$. 由**定义 4.23** (凸集) 的凸性迭代, $x\in C$. 故 $C=\mathbb R^n$.

**无穷维反例**: 在 $C\left(\left[0,1\right]\right)$ 配上确界范数中, 全体多项式所成集合 $P$ 是线性子空间, 因而凸. 由魏尔斯特拉斯逼近定理, $P$ 在 $C\left(\left[0,1\right]\right)$ 中稠密. 但 $P\neq C\left(\left[0,1\right]\right)$ (例如 $\sin x$ 不是多项式). 故无穷维稠密凸集不必为全空间. $\blacksquare$

### 习题四

(巴拿赫空间中的开球) 设 $X=\mathbb R^n$, $\Omega$ 是有界非空开集, 且对任意 $x,y\in\Omega$, 存在含于 $\Omega$ 的开球同时含 $x,y$. 证明 $\Omega$ 本身是开球. 找一个去掉有界性假设后的反例. 对任意巴拿赫空间同样讨论.

### 解答 习题四

**有界情形**: 条件蕴含 $\Omega$ 凸: 对 $x,y\in\Omega$, 含二者的开球凸, 故线段 $\left[x,y\right]\subset\Omega$. 又条件要求任意两点都能被一个含于 $\Omega$ 的开球同时覆盖, 这迫使 $\Omega$ 的边界处处曲率一致, 即 $\Omega$ 是一个开球. 具体地, 取 $\Omega$ 的外接圆 (由有界闭包 $\overline\Omega$ 的紧致性, 存在最小外接球), 条件迫使 $\Omega$ 等于该外接球内部.

**无界反例**: 上半空间 $\Omega=\left\{\left(x,y\right):y>0\right\}$ 无界, 但任意两点 $x,y\in\Omega$ 都可被一个大半径、中心足够高的开球覆盖且球仍在 $\Omega$ 内. 它不是开球.

**巴拿赫空间**: 同样结论在任意巴拿赫空间成立: 有界凸开集若任意两点可被含于其中的开球同时覆盖, 则它是一个开球; 上半空间式无界反例仍存在. $\blacksquare$

### 习题五

(巴拿赫空间示例 I) 证明 $C\left(\left[0,1\right]\right)$ 配上确界范数 $\left\|f\right\|_\infty=\sup_{x\in\left[0,1\right]}\left|f\left(x\right)\right|$ 是**定义 6.21** (巴拿赫空间).

### 解答 习题五

由**定义 6.20** (赋范线性空间), $\left\|\cdot\right\|_\infty$ 满足范数三公理 (正定性由 $f$ 连续, $\left\|f\right\|_\infty=0\Rightarrow f\equiv 0$; 齐次与三角不等式显然). 完备性: 由**定理 6.6** (函数空间完备), $\mathbb R$ 完备, 故 $\left(\mathbb R^{\left[0,1\right]},\text{一致度量}\right)$ 完备; $C\left(\left[0,1\right]\right)$ 是其闭子空间 (一致收敛连续函数的极限连续), 故完备. 由**定义 6.21** (巴拿赫空间), $C\left(\left[0,1\right]\right)$ 是巴拿赫空间. $\blacksquare$

### 习题六

(巴拿赫空间示例二) 证明有界序列空间 $\ell^\infty=\left\{\left(x_n\right):\sup_n\left|x_n\right|<\infty\right\}$ 配上确界范数 $\left\|x\right\|_\infty=\sup_n\left|x_n\right|$ 是巴拿赫空间.

### 解答 习题六

范数三公理由逐点取上确界直接验证, 故由**定义 6.20** (赋范线性空间) 是赋范空间. 完备性: 设 $\left(x^{\left(k\right)}\right)_k$ 是 $\ell^\infty$ 中柯西列. 对每个坐标 $n$, $x_n^{\left(k\right)}$ 是 $\mathbb R$ 中柯西列, 记极限为 $x_n$. 由柯西一致性, $\sup_n\left|x_n^{\left(k\right)}-x_n\right|\to 0$, 且 $\left(x_n\right)$ 有界. 故 $x\in\ell^\infty$ 且 $x^{\left(k\right)}\to x$. 由**定义 6.38** (完备度量空间), $\ell^\infty$ 完备, 即**定义 6.21** (巴拿赫空间). $\blacksquare$

### 习题七

(非巴拿赫空间示例) 证明 $C^1\left(\left[0,1\right]\right)$ 配上确界范数 $\left\|\cdot\right\|_\infty$ 不是巴拿赫空间.

### 解答 习题七

由魏尔斯特拉斯逼近定理, 连续函数 $g\left(x\right)=\left|x-\frac12\right|$ 可被一列多项式 $p_n$ 一致逼近. 每个 $p_n\in C^1\left(\left[0,1\right]\right)$, 且 $\left(p_n\right)$ 在 $\left\|\cdot\right\|_\infty$ 下是柯西列 (一致收敛). 但极限 $g$ 在 $x=\frac12$ 处不可微, 故 $g\notin C^1\left(\left[0,1\right]\right)$. 因而该柯西列在 $C^1\left(\left[0,1\right]\right)$ 中不收敛. 由**定义 6.38** (完备度量空间), $C^1\left(\left[0,1\right]\right)$ 配 $\left\|\cdot\right\|_\infty$ 不完备, 故不是**定义 6.21** (巴拿赫空间). $\blacksquare$

### 习题八

(连续与有界等价) 设 $T:E\to F$ 是赋范线性空间之间的线性映射. 证明下列等价:

(1) $T$ 在某点连续;

(2) $T$ 在所有点连续;

(3) $T$ 有界, 即 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|<\infty$.

### 解答 习题八

**(1) $\Rightarrow$ (2)**: 由线性, $T\left(x\right)-T\left(x_0\right)=T\left(x-x_0\right)$. 在 $0$ 连续即 $\left\|h\right\|\to 0$ 时 $\left\|Th\right\|\to 0$, 平移即得在任意 $x_0$ 连续.

**(2) $\Rightarrow$ (3)**: 在 $0$ 连续, 存在 $\delta>0$ 使 $\left\|h\right\|<\delta$ 时 $\left\|Th\right\|<1$. 对任意 $\left\|x\right\|\le 1$, 取 $h=\delta x/2$, 则 $\left\|h\right\|<\delta$, $\left\|Th\right\|<1$, 故 $\left\|Tx\right\|<2/\delta$. 由**定义 6.28** (算子范数), $\left\|T\right\|\le 2/\delta<\infty$.

**(3) $\Rightarrow$ (1)**: $\left\|Tx-Tx_0\right\|=\left\|T\left(x-x_0\right)\right\|\le\left\|T\right\|\left\|x-x_0\right\|$, 故 $x\to x_0$ 时 $Tx\to Tx_0$. 由**定义 6.20** (赋范线性空间) 的范数拓扑, 连续. $\blacksquare$

### 习题九

(范数选取) 设 $Q\in\mathbb R\left[X\right]$. 在 $\mathbb R\left[X\right]$ 上构造一个范数, 使序列 $\left\{X^n\right\}_{n\ge 0}$ 在该范数下收敛到 $Q$.

### 解答 习题九

取基 $e_0=Q$, $e_n=X^n-Q$ ($n\ge 1$). 任意 $P\in\mathbb R\left[X\right]$ 唯一写为 $P=a_0e_0+\sum_{n\ge 1}a_ne_n$ (因 $\left\{e_n\right\}$ 与 $\left\{1,X,X^2,\dots\right\}$ 只差一个基变换). 定义

$$
\left\|P\right\|=\left|a_0\right|+\sum_{n\ge 1}\frac{\left|a_n\right|}{2^n}.
$$

它满足范数三公理, 由**定义 6.20** (赋范线性空间) 这是 $\mathbb R\left[X\right]$ 上的一个范数. 而 $X^n=e_n+e_0$, 故

$$
\left\|X^n-Q\right\|=\left\|e_n\right\|=\frac{1}{2^n}\to 0.
$$

即 $X^n\to Q$. $\blacksquare$

### 习题十

(复合的连续性) 设 $E=C\left(\left[a,b\right],\mathbb R\right)$ 配 $\left\|\cdot\right\|_\infty$, $\varphi:\mathbb R\to\mathbb R$ 连续. 证明映射 $f\mapsto\varphi\circ f$ 从 $E$ 到 $E$ 连续.

### 解答 习题十

由**定理 6.5** (紧空间上连续一致连续), $\left[a,b\right]$ 紧, $\varphi$ 在 $\mathbb R$ 上连续, 但 $f$ 的像有界; 进一步, $\varphi$ 在有界区间上一致连续. 对 $\epsilon>0$, 存在 $\delta>0$, 使 $\left|u-v\right|<\delta$ 时 $\left|\varphi\left(u\right)-\varphi\left(v\right)\right|<\epsilon$. 若 $\left\|f-g\right\|_\infty<\delta$, 则对一切 $x\in\left[a,b\right]$, $\left|f\left(x\right)-g\left(x\right)\right|<\delta$, 故

$$
\left\|\varphi\circ f-\varphi\circ g\right\|_\infty=\sup_x\left|\varphi\left(f\left(x\right)\right)-\varphi\left(g\left(x\right)\right)\right|\le\epsilon.
$$

故 $f\mapsto\varphi\circ f$ 连续. $\blacksquare$

### 习题十一

(非贝尔) 设 $E$ 是不满足**定理 6.13** (贝尔纲定理) 的赋范空间. 证明 $E$ 是可数个无处稠密闭集之并.

### 解答 习题十一

$E$ 非贝尔, 由定义 (即**定理 6.13** (贝尔纲定理) 不成立), 存在可数个稠密开集 $\left\{U_n\right\}$ 使 $\bigcap_n U_n=\emptyset$. 令 $F_n=E\setminus U_n$. 每个 $F_n$ 闭. $F_n$ 无处稠密: $U_n$ 稠密意味着 $F_n$ 内部为空 (否则其开邻域与 $U_n$ 不交, 与稠密矛盾). 而

$$
E=E\setminus\bigcap_n U_n=\bigcup_n\left(E\setminus U_n\right)=\bigcup_n F_n.
$$

故 $E$ 是可数个无处稠密闭集之并. $\blacksquare$

### 习题十二

(赋范空间命题) 证明: 赋范线性空间上范数映射 $x\mapsto\left\|x\right\|$ 连续, 且赋范空间在范数拓扑下是豪斯多夫的.

### 解答 习题十二

由**定义 6.20** (赋范线性空间), 范数满足三角不等式, 故 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$. 当 $x\to y$ 时 $\left\|x\right\|\to\left\|y\right\|$, 即范数连续.

豪斯多夫: 设 $x\neq y$, $r=\left\|x-y\right\|>0$. 取 $\epsilon=r/3$. 由**定义 3.10** (豪斯多夫空间), 开球 $B\left(x,\epsilon\right)$ 与 $B\left(y,\epsilon\right)$ 不相交 (否则由三角不等式 $\left\|x-y\right\|\le 2\epsilon<r$, 矛盾). 故赋范空间豪斯多夫. $\blacksquare$

### 习题十三

(商范数) 设 $E$ 是赋范线性空间, $F\subset E$ 是闭子空间. 证明 $E/F$ 配上

$$
\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|
$$

是一个赋范线性空间 (即**定义 6.29** (商范数)).

### 解答 习题十三

由**定义 6.29** (商范数), $\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|$.

(a) 非负与齐次显然.

(b) 三角不等式: $\left\|\left[x+y\right]\right\|\le\left\|x+f\right\|+\left\|y+g\right\|$ 对任意 $f,g\in F$, 取下确界得 $\left\|\left[x+y\right]\right\|\le\left\|\left[x\right]\right\|+\left\|\left[y\right]\right\|$.

(c) 正定性: 若 $\left\|\left[x\right]\right\|=0$, 则存在 $f_n\in F$ 使 $\left\|x+f_n\right\|\to 0$, 即 $-f_n\to x$. 因 $F$ 闭, $x\in F$, 故 $\left[x\right]=0$.

由**定义 6.20** (赋范线性空间), $E/F$ 是赋范空间. $\blacksquare$

### 习题十四

设 $E$ 是**定义 6.20** (赋范线性空间) 意义下的赋范线性空间, $H$ 是**定义 6.55** (超平面). 证明存在**定义 6.56** (线性泛函) $\varphi:E\to\mathbb R$ 使 $H=\ker\varphi$. 进一步证明 $H$ 是闭集当且仅当 $\varphi$ 连续.

### 解答 习题十四

由**定义 6.55** (超平面), $\dim\left(E/H\right)=1$. 取 $v\notin H$, 则 $E=H\oplus\mathbb R v$. 任取 $u\in E$, 唯一分解 $u=h+tv$, $h\in H$, $t\in\mathbb R$. 定义**定义 6.56** (线性泛函) $\varphi\left(u\right)=t$. 则 $\varphi$ 线性且 $\ker\varphi=H$. 这里 $E$ 是**定义 6.20** (赋范线性空间).

**($\varphi$ 连续 $\Rightarrow$ $H$ 闭)**: 由**定义 3.22** (连续映射), $\varphi^{-1}\left(\left\{0\right\}\right)$ 是闭集 ($\left\{0\right\}\subset\mathbb R$ 闭), 而 $H=\ker\varphi=\varphi^{-1}\left(\left\{0\right\}\right)$, 由**定义 3.21** (闭集) $H$ 闭.

**($H$ 闭 $\Rightarrow$ $\varphi$ 连续)**: 反证. 设 $H$ 闭但 $\varphi$ 不连续, 即 $\varphi$ 无界. 故存在序列 $\left(x_n\right)$ 使 $\left\|x_n\right\|=1$ 而 $\left|\varphi\left(x_n\right)\right|\to\infty$. 任取 $u\in E$, 定义

$$
u_n=u-\frac{\varphi\left(u\right)}{\varphi\left(x_n\right)}\,x_n.
$$

则 $\varphi\left(u_n\right)=\varphi\left(u\right)-\varphi\left(u\right)=0$, 故 $u_n\in H$. 又

$$
\left\|u-u_n\right\|=\left|\frac{\varphi\left(u\right)}{\varphi\left(x_n\right)}\right|\cdot\left\|x_n\right\|=\frac{\left|\varphi\left(u\right)\right|}{\left|\varphi\left(x_n\right)\right|}\to 0.
$$

由**定义 3.21** (闭集) $H$ 闭, 故 $u=\lim u_n\in H$, 即 $\varphi\left(u\right)=0$. 由 $u$ 任意, $\varphi\equiv 0$, 与 $H$ 是余维 $1$ 的超平面矛盾. 故 $\varphi$ 必连续. $\blacksquare$

### 习题十五

(开映射定理的推论) 设 $E,F$ 都是**定义 6.21** (巴拿赫空间), $T:E\to F$ 是连续线性双射. 证明 $T^{-1}:F\to E$ 连续, 即 $T$ 是同胚.

### 解答 习题十五

由**定理 6.57** (开映射定理), 巴拿赫空间之间的连续满线性映射把开集映为开集. $T$ 是双射, 故满. 对任意开集 $U\subset E$, $T\left(U\right)\subset F$ 是开集. 而 $T^{-1}$ 的逆像

$$
\left(T^{-1}\right)^{-1}\left(U\right)=T\left(U\right)
$$

是开集. 由**定义 3.22** (连续映射), $T^{-1}$ 连续. 故 $T$ 是**定义 3.23** (同胚) 意义下的同胚. $\blacksquare$

### 习题十六

(巴拿赫-施坦豪斯定理的推论) 设 $E$ 是巴拿赫空间, $F$ 是赋范线性空间, $T_n:E\to F$ 是连续线性映射, 且对每个 $x\in E$, $T_n x$ 在 $F$ 中收敛. 证明 $\sup_n\left\|T_n\right\|<\infty$, 且极限映射 $T x=\lim_n T_n x$ 是连续线性映射.

### 解答 习题十六

由假设, 对每个 $x\in E$, $\sup_n\left\|T_n x\right\|<\infty$ (收敛数列有界). 由**定理 6.58** (巴拿赫-施坦豪斯定理), $\sup_n\left\|T_n\right\|<\infty$, 记 $M=\sup_n\left\|T_n\right\|$.

线性: 对 $x,y\in E$ 与 $\alpha\in\mathbb R$,

$$
T\left(\alpha x+y\right)=\lim_n T_n\left(\alpha x+y\right)=\lim_n\left(\alpha T_n x+T_n y\right)=\alpha T x+T y.
$$

有界性: $\left\|T x\right\|=\lim_n\left\|T_n x\right\|\le M\left\|x\right\|$. 由**定义 3.22** (连续映射) 赋范空间间的有界线性映射连续, 故 $T$ 连续. $\blacksquare$

### 习题十七

(巴拿赫-绍德定理的推论) 设 $K$ 是巴拿赫空间中非空紧凸子集, $f:K\to K$ 连续. 证明 $f$ 有不动点. 有限维情形推出: 非空紧凸子集 (例如闭单位球) 到自身的连续映射有不动点.

### 解答 习题十七

由**定理 6.59** (巴拿赫-绍德不动点定理), 巴拿赫空间中非空紧凸子集到自身的连续映射有不动点, 故存在 $x\in K$ 使 $f\left(x\right)=x$.

有限维情形: $\mathbb R^n$ 是巴拿赫空间, 其非空紧凸子集 $K$ 满足绍德定理条件, 故 $f$ 有不动点. 这就是有限维的布劳威尔不动点定理. $\blacksquare$

### 习题十八

设 $E$ 是有限维实向量空间, $1\le n<\infty$, $\left\{F_k\right\}_{k\in\mathbb N}$ 是一列 $p$ 维子空间. 证明 $\bigcup_{k\in\mathbb N}F_k\neq E$. 进一步证明存在子空间 $W\subset E$ 使对一切 $k$, $W\oplus F_k=E$.

### 解答 习题十八

有限维赋范空间是**定义 6.21** (巴拿赫空间) 意义下的巴拿赫空间. 每个 $F_k$ 是真子空间 ($p<n$), 且在 $E$ 中闭 (有限维子空间闭). 若 $E=\bigcup_k F_k$, 由**定理 6.14** (递增闭集族) (注意 $F_k$ 虽不递增, 令 $G_N=\bigcup_{k\le N}F_k$ 为递增闭集列且 $E=\bigcup_N G_N$), 某个 $G_N$ 有非空内部; 但有限个真子空间之并仍无内部 (否则含开球, 含开球的子空间必为全空间), 矛盾. 故 $\bigcup_k F_k\neq E$.

**存在 $W$**: 归纳构造 $w_1,\dots,w_{n-p}$. 假设已选 $w_1,\dots,w_j$ ($j<n-p$), 令 $V_j=\operatorname{span}\left(w_1,\dots,w_j\right)$. 对每个 $k$, $F_k+V_j$ 是真子空间 (因为 $F_k$ 维数 $p$, 加 $V_j$ 维数 $p+j<p+\left(n-p\right)=n$), 因而闭且无内部. 由**定理 6.13** (贝尔纲定理), 可数并 $\bigcup_k\left(F_k+V_j\right)\neq E$, 故可取

$$
w_{j+1}\in E\setminus\bigcup_k\left(F_k+V_j\right).
$$

则 $w_{j+1}\notin F_k+V_j$ 对一切 $k$. 令 $W=\operatorname{span}\left(w_1,\dots,w_{n-p}\right)$. 则对每个 $k$, $W\cap F_k=\left\{0\right\}$ (若非零 $w\in W\cap F_k$, 则 $w\in F_k+V_j$ 对最大 $j$ 矛盾), 且 $\dim W+\dim F_k=\left(n-p\right)+p=n=\dim E$, 故 $W\oplus F_k=E$. $\blacksquare$

### 习题十九

设 $f:\mathbb R_{\ge 0}\to\mathbb R$ 连续, 且对每个 $\lambda\ge 0$, $\lim_{x\to\infty}\left(f\left(x+\lambda\right)-f\left(x\right)\right)=0$. 证明对任意区间 $\left[a,b\right]\subset\mathbb R_{\ge 0}$, 收敛在 $\lambda\in\left[a,b\right]$ 上一致.

### 解答 习题十九

固定 $\epsilon>0$. 定义

$$
F_m=\left\{\lambda\in\left[a,b\right]:\ \text{对一切 }x\ge m,\ \left|f\left(x+\lambda\right)-f\left(x\right)\right|\le\epsilon\right\}.
$$

对固定 $x$, 条件 $\left|f\left(x+\lambda\right)-f\left(x\right)\right|\le\epsilon$ 是 $\lambda$ 的闭条件 ($f$ 连续); $F_m$ 是这些闭集 ($x\ge m$) 之交, 故闭. 由假设, 每个 $\lambda\in\left[a,b\right]$ 属于某个 $F_m$, 故 $\left[a,b\right]=\bigcup_m F_m$, 且 $F_m$ 递增.

$\left[a,b\right]$ 是紧度量空间, 因而完备. 由**定理 6.14** (递增闭集族), 某个 $F_N$ 有非空内部, 即存在开区间 $\left(c,d\right)\subset F_N$. 对任意 $\lambda\in\left[a,b\right]$, 取 $\lambda_0\in\left(c,d\right)$ 使 $\left|\lambda-\lambda_0\right|$ 很小. 分解

$$
f\left(x+\lambda\right)-f\left(x\right)=\left[f\left(x+\lambda\right)-f\left(x+\lambda_0\right)\right]+\left[f\left(x+\lambda_0\right)-f\left(x\right)\right].
$$

第二项对 $x\ge N$ 绝对值 $\le\epsilon$. 第一项是 $f\left(\left(x+\lambda_0\right)+\delta\right)-f\left(x+\lambda_0\right)$, 其中 $\delta=\lambda-\lambda_0$ 固定. 由假设, 对每个固定 $\delta$, 当 $x+\lambda_0\to\infty$ 时该项趋于 $0$.

由 $\left[c,d\right]$ 紧与贝尔纲得到的非空内部, 进一步用有限覆盖: $\left[a,b\right]$ 被有限个形如 $\lambda_0+\eta$ 的平移区间覆盖 ($\eta$ 取自一个固定有限网), 对每个固定的 $\eta$ 取 $M_\eta$ 使 $x\ge M_\eta$ 时 $\left|f\left(x+\eta\right)-f\left(x\right)\right|\le\epsilon$. 取 $M=\max\left(N,M_\eta\right)$, 则对一切 $\lambda\in\left[a,b\right]$ 与 $x\ge M$, 上述两项均 $\le\epsilon$, 故 $\left|f\left(x+\lambda\right)-f\left(x\right)\right|\le 2\epsilon$. 收敛一致. $\blacksquare$

### 习题二十

设 $1<q<\infty$. 证明在**定义 6.60** (序列空间 $\ell^p$) 意义下, $\ell^q\neq\bigcup_{1<p<q}\ell^p$.

### 解答 习题二十

对 $1\le p<q<\infty$, 在**定义 6.60** (序列空间 $\ell^p$) 意义下 $\ell^p\subset\ell^q$. 事实上若 $x\in\ell^p$, 则 $x_n\to 0$, 故存在 $N$ 使 $n\ge N$ 时 $\left|x_n\right|\le 1$, 于是 $\left|x_n\right|^q\le\left|x_n\right|^p$, 从而 $\sum\left|x_n\right|^q<\infty$.

下面证明每个 $\ell^p$ ($p<q$) 在 $\ell^q$ 中是无处稠密的. 由**定义 3.21** (闭集), $\ell^p$ 在 $\ell^q$ 中闭: 若 $x^{\left(m\right)}\in\ell^p$ 在 $\ell^q$ 中收敛到 $x$, 则 $x^{\left(m\right)}_n\to x_n$ 对每个 $n$, 由法图引理 (点集分析基本事实) $\sum\left|x_n\right|^p\le\liminf_m\sum\left|x^{\left(m\right)}_n\right|^p<\infty$, 故 $x\in\ell^p$.

$\ell^p$ 无内部: 任取 $x\in\ell^p$ 与 $\epsilon>0$, 构造 $y$ 使 $\left\|y-x\right\|_q<\epsilon$ 但 $y\notin\ell^p$. 取稀疏下标 $n_k$ 使 $\left|x_{n_k}\right|$ 很小, 令 $y_{n_k}=k^{-1/p}$ (其余 $y_n=x_n$). 则 $\sum\left|y_{n_k}\right|^p=\sum 1/k=\infty$, 故 $y\notin\ell^p$; 而 $\sum\left|y_{n_k}\right|^q=\sum k^{-q/p}<\infty$ (因 $q/p>1$), 且可使 $\left\|y-x\right\|_q$ 任意小. 故 $\ell^p$ 在 $\ell^q$ 中无内部.

由**定理 6.14** (递增闭集族), $\ell^q$ (完备, 因 $\ell^q$ 是巴拿赫空间) 不能写成可数个无内部闭集之并. 取有理数集 $\mathbb Q\cap\left(1,q\right)$, 它是可数稠密子集; $\bigcup_{p\in\mathbb Q\cap\left(1,q\right)}\ell^p$ 是可数个无内部闭集之并, 故不等于 $\ell^q$. 而

$$
\bigcup_{1<p<q}\ell^p\supset\bigcup_{p\in\mathbb Q\cap\left(1,q\right)}\ell^p,
$$

故更大的并集 $\bigcup_{1<p<q}\ell^p$ 也不等于 $\ell^q$. $\blacksquare$

### 习题廿一

检查商拓扑三种定义的等价性: (a) $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开; (b) 商拓扑是使 $\pi$ 连续的最细拓扑; (c) $F\subset Y$ 闭当且仅当 $\pi^{-1}\left(F\right)\subset X$ 闭.

### 解答 习题廿一

**(a) $\Leftrightarrow$ (b)**: 由**定义 11.1** (商拓扑), 拓扑 $\mathcal O_Y=\left\{U\subset Y:\pi^{-1}\left(U\right)\text{ 开}\right\}$ 使 $\pi$ 连续 (由**定义 3.22** (连续映射)). 若 $\mathcal O'$ 是另一个使 $\pi$ 连续的拓扑, 则对 $U\in\mathcal O'$, $\pi^{-1}\left(U\right)$ 开, 故 $U\in\mathcal O_Y$, 即 $\mathcal O'\subset\mathcal O_Y$. 故 $\mathcal O_Y$ 是使 $\pi$ 连续的最细拓扑, 即**定义 11.14** (最终拓扑) 意义下的最终拓扑. 反之最终拓扑由该条件唯一确定.

**(a) $\Leftrightarrow$ (c)**: 由**定义 3.21** (闭集), $F\subset Y$ 闭当且仅当 $Y\setminus F$ 开; 而 $\pi^{-1}\left(Y\setminus F\right)=X\setminus\pi^{-1}\left(F\right)$. 由 (a), $Y\setminus F$ 开当且仅当 $X\setminus\pi^{-1}\left(F\right)$ 开, 即 $\pi^{-1}\left(F\right)$ 闭. 故 (a) 与 (c) 等价.

三者一致, 且由**定义 11.2** (商映射), $\pi:X\to Y$ 满足 $U$ 开 $\Leftrightarrow$ $\pi^{-1}\left(U\right)$ 开, 故 $\pi$ 是商映射. $\blacksquare$

### 习题廿二

(树皮定理, 函数法证明) 设 $\left(E,d\right)$ 是度量空间, $A,B\subset E$ 是不相交闭集. 证明存在连续函数 $f:E\to\left[0,1\right]$ 使 $f\big|_A=0$, $f\big|_B=1$. 此即度量空间版本的**定理 7.2** (乌雷松引理).

### 解答 习题廿二

由**定义 6.46** (点到集合的距离), 考虑 $d\left(x,A\right)$ 与 $d\left(x,B\right)$. 先证 $x\mapsto d\left(x,A\right)$ 连续: 对 $x,y$, 由三角不等式 (**定义 6.35** (度量空间)), 对任意 $a\in A$, $d\left(x,a\right)\le d\left(x,y\right)+d\left(y,a\right)$, 取下确界得 $d\left(x,A\right)\le d\left(x,y\right)+d\left(y,A\right)$; 交换 $x,y$ 得 $\left|d\left(x,A\right)-d\left(y,A\right)\right|\le d\left(x,y\right)$, 故利普希茨连续.

因 $A,B$ 不相交闭且不相交, 对 $x\in E$, $d\left(x,A\right)+d\left(x,B\right)>0$ (若为 $0$, 则 $x\in\overline A=A$ 且 $x\in\overline B=B$, 矛盾). 定义

$$
f\left(x\right)=\frac{d\left(x,A\right)}{d\left(x,A\right)+d\left(x,B\right)}.
$$

分母连续且正, 分子连续, 故 $f$ 连续 (由**定义 3.22** (连续映射)). 当 $x\in A$, $d\left(x,A\right)=0$, 故 $f\left(x\right)=0$; 当 $x\in B$, $d\left(x,B\right)=0$, 故 $f\left(x\right)=1$. 由构造 $0\le f\le 1$. 这就用函数法构造了分离 $A,B$ 的连续函数, 即**定理 7.2** (乌雷松引理) 在度量空间上的形式. $\blacksquare$

### 习题廿三

考虑一个赋范线性空间 $E$ 及其中的一个紧致子集 $K\subset E$. 假设 $K$ 还是凸的. 假设 $f:K\to K$ 是一个连续映射并且对于任意 $x,y\in K$, $\left\|f\left(x\right)-f\left(y\right)\right\|\le\left\|x-y\right\|$.

(1) (10 分) 证明如果条件改为对于任意 $x,y\in K$ 且 $x\neq y$ 时 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$, 那么 $f$ 一定至少有一个不动点. (不需要证明, 只需要说出相关定理或构造即可.)

(2) (10 分) 取定 $a\in K$. 证明对于任意 $n\ge1$, 函数 $f_n\left(x\right)=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x\right)$ 是一个从 $K$ 到 $K$ 的映射. 证明对于任意 $n\ge1$, $f_n$ 至少有一个不动点 $x_n\in K$.

(3) (5 分) 运用数列 $\left\{x_n\right\}$ 及 $K$ 的紧性证明满足最初题设条件的 $f$ 也有一个不动点.

### 解答 习题廿三

(1) 在严格条件 $\left\|f\left(x\right)-f\left(y\right)\right\|<\left\|x-y\right\|$ ($x\neq y$) 下, 由 $K$ 紧可推出 $f$ 实际上是**定义 6.19** (压缩映射) 意义下的压缩映射 (存在统一的 $0<k<1$). 再由**定理 6.16** (巴拿赫不动点定理), $f$ 有唯一不动点.

(2) 由**定义 4.23** (凸集), $a\in K$ 且 $f\left(x\right)\in K$, 故凸组合 $f_n\left(x\right)=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x\right)\in K$, 即 $f_n:K\to K$. 对 $x,y\in K$,

$$
\left\|f_n\left(x\right)-f_n\left(y\right)\right\|=\left(1-\frac{1}{n}\right)\left\|f\left(x\right)-f\left(y\right)\right\|\le\left(1-\frac{1}{n}\right)\left\|x-y\right\|,
$$

其中压缩系数 $k=1-\frac{1}{n}<1$, 故 $f_n$ 是**定义 6.19** (压缩映射). 又 $K$ 紧, 由**定理 6.3** (紧度量空间完备) $K$ 完备. 由**定理 6.16** (巴拿赫不动点定理), $f_n$ 有唯一不动点 $x_n\in K$, 即 $x_n=f_n\left(x_n\right)$.

(3) 因 $K$ 紧, 由**定理 6.1** (紧 $=$ 序列紧), 序列 $\left(x_n\right)\subset K$ 有收敛子列 $x_{n_j}\to x\in K$. 由 $x_n=f_n\left(x_n\right)=\frac{1}{n}a+\left(1-\frac{1}{n}\right)f\left(x_n\right)$ 整理得

$$
f\left(x_n\right)=\frac{n\,x_n-a}{n-1}.
$$

沿子列 $n_j\to\infty$, $x_{n_j}\to x$, 故 $\frac{n_j x_{n_j}-a}{n_j-1}\to x$, 即 $f\left(x_{n_j}\right)\to x$. 另一方面 $f$ 连续, 故 $f\left(x_{n_j}\right)\to f\left(x\right)$. 由**定义 3.10** (豪斯多夫空间) 极限唯一, 得 $f\left(x\right)=x$. 即 $f$ 有不动点. $\blacksquare$

### 习题廿四

(2025 年卷 A 题目二, 50 分). 研究角谷-马尔可夫不动点定理的一个简单版本. 设 $E$ 为一个有限维 $\mathbb R$ 线性空间. 设 $K$ 为 $E$ 的一个非空紧凸集合. 设 $u:E\to E$ 是一个线性映射使得 $u\left(K\right)\subset K$. 对 $n\ge1$ 定义 $u_n=\frac1n\left(\operatorname{Id}_E+u+u^2+\cdots+u^{n-1}\right)$, 其中 $\operatorname{Id}_E$ 是 $E$ 上的恒同映射.

(0) 证明 $u$ 是连续的.

(1) 证明对于任意 $n\ge1$, $u_n\left(K\right)$ 是 $K$ 中的一个紧致凸集合.

(2) 证明 $u_4\left(K\right)\subset u_2\left(K\right)$.

(3) 证明对于任意 $n\ge2$, $u_{n!}\left(K\right)\subset u_{\left(n-1\right)!}\left(K\right)$.

(4) 证明 $\bigcap_{n\ge1}u_{n!}\left(K\right)$ 是一个非空紧致凸集, 并且 $\bigcap_{n\ge1}u_{n!}\left(K\right)=\bigcap_{n\ge1}u_n\left(K\right)$.

(5) 证明 $\bigcap_{n\ge1}u_n\left(K\right)$ 就是 $u$ 的所有不动点的集合.

### 解答 习题廿四

(0) 有限维线性空间之间的线性映射关于欧氏范数连续, 故 $u$ 连续. 同理每个 $u_n$ 是线性映射, 连续.

(1) $u_n$ 线性连续. 由**定理 5.1** (紧空间连续像紧), $u_n\left(K\right)$ 紧. 又线性映射把凸集映成凸集: 由**定义 4.23** (凸集), $K$ 凸, $u_n\left(K\right)$ 凸. 且 $u_n\left(K\right)\subset K$, 故 $u_n\left(K\right)$ 是 $K$ 中紧致凸集.

(2) 对 $x\in K$,

$$
u_4\left(x\right)=\frac14\left(x+ux+u^2x+u^3x\right)=\frac12\left(u_2\left(x\right)+u_2\left(ux\right)\right).
$$

因 $u\left(K\right)\subset K$, $ux\in K$, 故 $u_2\left(x\right),u_2\left(ux\right)\in u_2\left(K\right)$. 由**定义 4.23** (凸集), 凸组合 $\in u_2\left(K\right)$. 故 $u_4\left(K\right)\subset u_2\left(K\right)$.

(3) $n!=n\cdot\left(n-1\right)!$. 把 $u_{n!}$ 的平均分成 $n$ 个长度为 $\left(n-1\right)!$ 的块:

$$
u_{n!}\left(x\right)=\frac1n\sum_{j=0}^{n-1}u^{j\left(n-1\right)!}\,u_{\left(n-1\right)!}\left(x\right).
$$

每个 $u_{\left(n-1\right)!}\left(x\right)\in u_{\left(n-1\right)!}\left(K\right)\subset K$, 且 $u^{j\left(n-1\right)!}$ 把 $K$ 映入 $K$, 故上式各项都在 $u_{\left(n-1\right)!}\left(K\right)$ 中, 其凸组合由**定义 4.23** (凸集) 仍在其中. 故 $u_{n!}\left(K\right)\subset u_{\left(n-1\right)!}\left(K\right)$.

(4) 集列 $u_{n!}\left(K\right)$ 递降, 每个紧 (由第 1 小题) 故闭, 且具有限交性质 (由**定义 5.17** (有限交性质), 递降非空闭集族任意有限交非空). $K$ 紧, 由**定理 5.10** (有限交判据), 全族交 $\bigcap_{n\ge1}u_{n!}\left(K\right)$ 非空. 凸集之交凸, 紧集之交闭, 故它是非空紧致凸集. 由第 3 小题及递推可知阶乘子列与全列等价, $\bigcap_n u_{n!}\left(K\right)=\bigcap_n u_n\left(K\right)$.

(5) 先设 $z$ 是 $u$ 的不动点, 即 $uz=z$, $z\in K$. 则 $u_n\left(z\right)=z$, 故 $z\in u_n\left(K\right)$ 对一切 $n$, 即 $z\in\bigcap_n u_n\left(K\right)$.

   再设 $z\in\bigcap_n u_n\left(K\right)$. 则对每个 $n$ 存在 $x_n\in K$ 使 $z=u_n\left(x_n\right)$. 于是

$$
u\left(z\right)-z=\frac1n\left(u^n\left(x_n\right)-x_n\right).
$$

因 $K$ 紧故有界, $\left\|u^n x_n\right\|,\left\|x_n\right\|$ 有界, 右端范数 $O\left(1/n\right)\to0$. 故 $u\left(z\right)-z=0$, 即 $uz=z$. 两者相等. $\blacksquare$
