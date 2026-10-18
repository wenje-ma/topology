# 作业 17

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$ 配以开集族 $T$, 满足空集与全集开, 有限交开, 任意并开. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. (教材 $\S3$)

> **定义 3.20** (边界)<br>$\partial A=\overline A\setminus\operatorname{int}\left(A\right)$. (教材 $\S3$)

> **定义 3.28** (扎里斯基拓扑)<br>$\mathbb A^n\left(K\right)$ 中闭集为若干多项式公共零点集. (题集 $\S1.4$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线全在 $K$ 中. (教材 $\S4$)

> **定义 5.2** (紧致空间)<br>$X$ 紧当且仅当每个开覆盖有有限子覆盖. (教材 $\S5$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge 0}$ 满足正定性, 对称, 三角不等式. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛. (教材 $\S6$)

> **定义 6.5** (完备化)<br>任意度量空间可自然嵌入一个完备度量空间. (教材 $\S6$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.21** (巴拿赫空间)<br>完备的赋范线性空间. (题集 $\S5$)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法与数乘都连续的拓扑. (题集 $\S5$)

> **定义 6.25** (半范数)<br>满足齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq 0$ 的函数. (题集 $\S5$)

> **定义 6.26** (局部凸空间)<br>$0$ 有由凸邻域组成的邻域基. (题集 $\S5$)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$. (题集 $\S5$)

> **定义 6.28** (算子范数)<br>$L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|$. (题集 $\S5$)

> **定义 6.29** (商范数)<br>赋范空间商掉闭子空间后诱导的范数 $\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|$. (题集 $\S5$)

> **定理 6.6** (函数空间完备)<br>$Y$ 完备则 $\left(Y^X,\text{一致度量}\right)$ 完备. (教材 $\S6$)

> **推论 6.5** (紧空间上连续一致连续)<br>紧度量空间上连续映射一致连续. (教材 $\S6$)

> **定理 6.13** (贝尔纲定理)<br>完备度量空间中可数个稠密开集之交非空 (且稠密). (教材 $\S6$)

> **定义 7.5** (单点紧化)<br>豪斯多夫局部紧空间 $X$ 的单点紧化 $X^*=X\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(X\setminus K\right)\cup\left\{\infty\right\}$. (教材 $\S7$)

### 习题一

(半范数拓扑) 设 $E$ 是向量空间, $\left\{p_\alpha\right\}_{\alpha\in A}$ 是一族半范数. 证明以

$$
\left\{x:p_{\alpha_i}\left(x\right)<\epsilon,\ i=1,\dots,n\right\}
$$

为 $0$ 的邻域基生成的拓扑使 $E$ 成为**定义 6.24** (拓扑向量空间) 意义下的拓扑向量空间, 且 $E$ 局部凸.

### 解答 习题一

由**定义 6.25** (半范数), 每个 $p_\alpha$ 是凸函数. 上面的基本邻域是有限个凸集之交, 由**定义 4.6** (凸集) 仍凸, 故 $0$ 有凸邻域基, 由**定义 6.26** (局部凸空间) $E$ 局部凸.

加法连续: 对 $0$ 的基本邻域 $U=\left\{p_{\alpha_i}<\epsilon\right\}$, 取 $V=\left\{p_{\alpha_i}<\epsilon/2\right\}$, 则 $V+V\subset U$. 数乘连续由半范数齐次性与 $p_\alpha\left(\lambda x\right)$ 在 $\left(\lambda,x\right)$ 上连续 (局部估计) 推出. 由**定义 6.24** (拓扑向量空间), 加法与数乘连续, 故 $E$ 是拓扑向量空间. 由**定义 3.1** (拓扑空间) 该邻域基满足拓扑公理. $\blacksquare$

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

(扎里斯基紧不蕴含扎里斯基闭) 在 $\mathbb A^1\left(\mathbb R\right)=\mathbb R$ 上配**定义 3.28** (扎里斯基拓扑), 即余有限拓扑. 证明子集 $\left(0,1\right)$ 在扎里斯基拓扑下紧但不闭.

### 解答 习题三

扎里斯基拓扑下, 由**定义 3.28** (扎里斯基拓扑), 闭集为有限集或全空间, 开集为余有限集或空集.

**紧**: 任取 $\left(0,1\right)$ 的开覆盖 $\left\{U_i\right\}$. 取其中一个非空开集 $U_0$; 由余有限性, $\mathbb R\setminus U_0$ 有限, 故 $\left(0,1\right)\setminus U_0$ 至多有限个点, 每个点再选一个覆盖元覆盖. 即得有限子覆盖. 由**定义 5.2** (紧致空间), $\left(0,1\right)$ 紧.

**不闭**: $\mathbb R\setminus\left(0,1\right)=\left(-\infty,0\right]\cup\left[1,\infty\right)$ 是无限集, 不是有限集, 故不是扎里斯基闭集; 因而它的补集 $\left(0,1\right)$ 不是扎里斯基开集的补, 即 $\left(0,1\right)$ 不闭. 故紧不蕴含闭. $\blacksquare$

### 习题四

(单点紧化) 回顾**定义 7.5** (单点紧化). 证明 $\mathbb R$ 的单点紧化同胚于单位圆 $S^1$.

### 解答 习题四

由**定义 7.5** (单点紧化), $\mathbb R^*=\mathbb R\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(\mathbb R\setminus K\right)\cup\left\{\infty\right\}$, $K$ 紧 (即有界闭).

构造映射 $F:\mathbb R^*\to S^1$, 把 $x\in\mathbb R$ 映到平面上圆周上的点 (球极投影), 把 $\infty$ 映到北极. 球极投影是从 $\mathbb R$ 到 $S^1\setminus\left\{\text{北极}\right\}$ 的同胚, 且 $\mathbb R$ 中"趋向无穷"对应于 $S^1$ 中趋向北极. 故 $F$ 连续双射. $\mathbb R^*$ 紧, $S^1$ 豪斯多夫, 故 $F$ 为同胚. $\blacksquare$

### 习题五

(完备化) 设 $\left(M,d\right)$ 不完备. 考虑全体柯西列 $\left\{x_n\right\}$, 等价关系 $\left\{x_n\right\}\sim\left\{y_n\right\}$ 当且仅当 $\lim_{n\to\infty}d\left(x_n,y_n\right)=0$. 令 $\widehat M$ 为等价类集合, 距离 $\widehat d\left(\left[x\right],\left[y\right]\right)=\lim_{n\to\infty}d\left(x_n,y_n\right)$. 证明 $\widehat M$ 完备, 且 $M$ 在嵌入 $x\mapsto\left(x,x,\dots\right)$ 下在 $\widehat M$ 中稠密.

### 解答 习题五

$\widehat d$ 适定: 若 $\left[x_n\right]=\left[x_n'\right]$, $\left[y_n\right]=\left[y_n'\right]$, 则 $d\left(x_n,y_n\right)-d\left(x_n',y_n'\right)$ 由三角不等式趋于 $0$, 极限与代表元无关. 由**定义 6.1** (度量空间), $\widehat d$ 满足四公理. 这里等价关系中出现的 $\left\{x_n\right\}$ 是**定义 6.3** (柯西列) 意义下的柯西列.

**完备**: 设 $\left\{\xi_k\right\}$ 是 $\widehat M$ 中柯西列, $\xi_k=\left[\left(x_n^{\left(k\right)}\right)_n\right]$. 对每个 $k$, 取代表列使其前 $k$ 项稳定逼近; 对角化取 $z_k=x_k^{\left(k\right)}$. 由柯西性与三角不等式, $\left(z_k\right)$ 是 $M$ 中柯西列, 记其等价类为 $\xi$. 则 $\xi_k\to\xi$. 由**定义 6.4** (完备度量空间), $\widehat M$ 完备.

**稠密嵌入**: 映射 $i:M\to\widehat M$, $i\left(x\right)=\left[\left(x,x,\dots\right)\right]$. 任意 $\xi=\left[\left(x_n\right)\right]\in\widehat M$, $x_n\to\xi$ 在 $\widehat M$ 中, 而 $x_n\in i\left(M\right)$. 故 $i\left(M\right)$ 的闭包为全空间, 由**定义 3.8** (稠密) $M$ 在 $\widehat M$ 中稠密. 由**定义 6.5** (完备化), 这就是 $M$ 的完备化. $\blacksquare$

### 习题六

(贝尔纲定理) 回顾**定理 6.13** (贝尔纲定理). 证明该定理在局部紧豪斯多夫空间中也成立.

### 解答 习题六

设 $X$ 局部紧豪斯多夫, $\left\{U_n\right\}_{n\ge 1}$ 是可数个稠密开集. 任取非空开集 $W_0$. 归纳构造: 给定非空开 $W_{n-1}$, 因 $U_n$ 稠密, $W_{n-1}\cap U_n\neq\emptyset$; 取非空开 $V_n$ 使 $\overline{V_n}\subset W_{n-1}\cap U_n$ 且 $\overline{V_n}$ 紧 (局部紧豪斯多夫提供紧邻域基). 于是

$$
\overline{V_1}\supset\overline{V_2}\supset\cdots,\quad\overline{V_n}\subset U_n,\quad\overline{V_n}\text{ 非空紧}.
$$

紧集族的有限交性质给出 $\bigcap_n\overline{V_n}\neq\emptyset$. 该交含于 $W_0\cap\bigcap_n U_n$. 故 $\bigcap_n U_n$ 与任意非空开集相交, 即稠密. 这正是**定理 6.13** (贝尔纲定理) 的结论. $\blacksquare$

### 习题七

(稠密凸集) 证明 $\mathbb R^n$ 中稠密凸集必为全空间. 用魏尔斯特拉斯多项式逼近定理说明在无穷维此结论不成立.

### 解答 习题七

**有限维**: 设 $C\subset\mathbb R^n$ 凸且稠密, 即由**定义 3.8** (稠密) $\overline C=\mathbb R^n$. 任取 $x\in\mathbb R^n$. 取 $n+1$ 个点 $c_0,\dots,c_n\in C$ (由稠密性可取到) 使 $x$ 落在它们的凸包内部. 具体地, 取 $c_i$ 充分靠近 $x$ 且方向张成 $\mathbb R^n$, 则 $x=\sum_{i=0}^n\lambda_i c_i$, $\lambda_i>0$, $\sum\lambda_i=1$. 由**定义 4.6** (凸集) 的凸性迭代, $x\in C$. 故 $C=\mathbb R^n$.

**无穷维反例**: 在 $C\left(\left[0,1\right]\right)$ 配上确界范数中, 全体多项式所成集合 $P$ 是线性子空间, 因而凸. 由魏尔斯特拉斯逼近定理, $P$ 在 $C\left(\left[0,1\right]\right)$ 中稠密. 但 $P\neq C\left(\left[0,1\right]\right)$ (例如 $\sin x$ 不是多项式). 故无穷维稠密凸集不必为全空间. $\blacksquare$

### 习题八

(巴拿赫空间中的开球) 设 $X=\mathbb R^n$, $\Omega$ 是有界非空开集, 且对任意 $x,y\in\Omega$, 存在含于 $\Omega$ 的开球同时含 $x,y$. 证明 $\Omega$ 本身是开球. 找一个去掉有界性假设后的反例. 对任意巴拿赫空间同样讨论.

### 解答 习题八

**有界情形**: 条件蕴含 $\Omega$ 凸: 对 $x,y\in\Omega$, 含二者的开球凸, 故线段 $\left[x,y\right]\subset\Omega$. 又条件要求任意两点都能被一个含于 $\Omega$ 的开球同时覆盖, 这迫使 $\Omega$ 的边界处处曲率一致, 即 $\Omega$ 是一个开球. 具体地, 取 $\Omega$ 的外接圆 (由有界闭包 $\overline\Omega$ 的紧致性, 存在最小外接球), 条件迫使 $\Omega$ 等于该外接球内部.

**无界反例**: 上半空间 $\Omega=\left\{\left(x,y\right):y>0\right\}$ 无界, 但任意两点 $x,y\in\Omega$ 都可被一个大半径、中心足够高的开球覆盖且球仍在 $\Omega$ 内. 它不是开球.

**巴拿赫空间**: 同样结论在任意巴拿赫空间成立: 有界凸开集若任意两点可被含于其中的开球同时覆盖, 则它是一个开球; 上半空间式无界反例仍存在. $\blacksquare$

### 习题九

(巴拿赫空间示例 I) 证明 $C\left(\left[0,1\right]\right)$ 配上确界范数 $\left\|f\right\|_\infty=\sup_{x\in\left[0,1\right]}\left|f\left(x\right)\right|$ 是**定义 6.21** (巴拿赫空间).

### 解答 习题九

由**定义 6.20** (赋范线性空间), $\left\|\cdot\right\|_\infty$ 满足范数三公理 (正定性由 $f$ 连续, $\left\|f\right\|_\infty=0\Rightarrow f\equiv 0$; 齐次与三角不等式显然). 完备性: 由**定理 6.6** (函数空间完备), $\mathbb R$ 完备, 故 $\left(\mathbb R^{\left[0,1\right]},\text{一致度量}\right)$ 完备; $C\left(\left[0,1\right]\right)$ 是其闭子空间 (一致收敛连续函数的极限连续), 故完备. 由**定义 6.21** (巴拿赫空间), $C\left(\left[0,1\right]\right)$ 是巴拿赫空间. $\blacksquare$

### 习题十

(巴拿赫空间示例二) 证明有界序列空间 $\ell^\infty=\left\{\left(x_n\right):\sup_n\left|x_n\right|<\infty\right\}$ 配上确界范数 $\left\|x\right\|_\infty=\sup_n\left|x_n\right|$ 是巴拿赫空间.

### 解答 习题十

范数三公理由逐点取上确界直接验证, 故由**定义 6.20** (赋范线性空间) 是赋范空间. 完备性: 设 $\left(x^{\left(k\right)}\right)_k$ 是 $\ell^\infty$ 中柯西列. 对每个坐标 $n$, $x_n^{\left(k\right)}$ 是 $\mathbb R$ 中柯西列, 记极限为 $x_n$. 由柯西一致性, $\sup_n\left|x_n^{\left(k\right)}-x_n\right|\to 0$, 且 $\left(x_n\right)$ 有界. 故 $x\in\ell^\infty$ 且 $x^{\left(k\right)}\to x$. 由**定义 6.4** (完备度量空间), $\ell^\infty$ 完备, 即**定义 6.21** (巴拿赫空间). $\blacksquare$

### 习题十一

(非巴拿赫空间示例) 证明 $C^1\left(\left[0,1\right]\right)$ 配上确界范数 $\left\|\cdot\right\|_\infty$ 不是巴拿赫空间.

### 解答 习题十一

由魏尔斯特拉斯逼近定理, 连续函数 $g\left(x\right)=\left|x-\frac12\right|$ 可被一列多项式 $p_n$ 一致逼近. 每个 $p_n\in C^1\left(\left[0,1\right]\right)$, 且 $\left(p_n\right)$ 在 $\left\|\cdot\right\|_\infty$ 下是柯西列 (一致收敛). 但极限 $g$ 在 $x=\frac12$ 处不可微, 故 $g\notin C^1\left(\left[0,1\right]\right)$. 因而该柯西列在 $C^1\left(\left[0,1\right]\right)$ 中不收敛. 由**定义 6.4** (完备度量空间), $C^1\left(\left[0,1\right]\right)$ 配 $\left\|\cdot\right\|_\infty$ 不完备, 故不是**定义 6.21** (巴拿赫空间). $\blacksquare$

### 习题十二

(连续与有界等价) 设 $T:E\to F$ 是赋范线性空间之间的线性映射. 证明下列等价:

(1) $T$ 在某点连续;

(2) $T$ 在所有点连续;

(3) $T$ 有界, 即 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|<\infty$.

### 解答 习题十二

**(1) $\Rightarrow$ (2)**: 由线性, $T\left(x\right)-T\left(x_0\right)=T\left(x-x_0\right)$. 在 $0$ 连续即 $\left\|h\right\|\to 0$ 时 $\left\|Th\right\|\to 0$, 平移即得在任意 $x_0$ 连续.

**(2) $\Rightarrow$ (3)**: 在 $0$ 连续, 存在 $\delta>0$ 使 $\left\|h\right\|<\delta$ 时 $\left\|Th\right\|<1$. 对任意 $\left\|x\right\|\le 1$, 取 $h=\delta x/2$, 则 $\left\|h\right\|<\delta$, $\left\|Th\right\|<1$, 故 $\left\|Tx\right\|<2/\delta$. 由**定义 6.28** (算子范数), $\left\|T\right\|\le 2/\delta<\infty$.

**(3) $\Rightarrow$ (1)**: $\left\|Tx-Tx_0\right\|=\left\|T\left(x-x_0\right)\right\|\le\left\|T\right\|\left\|x-x_0\right\|$, 故 $x\to x_0$ 时 $Tx\to Tx_0$. 由**定义 6.20** (赋范线性空间) 的范数拓扑, 连续. $\blacksquare$

### 习题十三

(范数选取) 设 $Q\in\mathbb R\left[X\right]$. 在 $\mathbb R\left[X\right]$ 上构造一个范数, 使序列 $\left\{X^n\right\}_{n\ge 0}$ 在该范数下收敛到 $Q$.

### 解答 习题十三

取基 $e_0=Q$, $e_n=X^n-Q$ ($n\ge 1$). 任意 $P\in\mathbb R\left[X\right]$ 唯一写为 $P=a_0e_0+\sum_{n\ge 1}a_ne_n$ (因 $\left\{e_n\right\}$ 与 $\left\{1,X,X^2,\dots\right\}$ 只差一个基变换). 定义

$$
\left\|P\right\|=\left|a_0\right|+\sum_{n\ge 1}\frac{\left|a_n\right|}{2^n}.
$$

它满足范数三公理, 由**定义 6.20** (赋范线性空间) 这是 $\mathbb R\left[X\right]$ 上的一个范数. 而 $X^n=e_n+e_0$, 故

$$
\left\|X^n-Q\right\|=\left\|e_n\right\|=\frac{1}{2^n}\to 0.
$$

即 $X^n\to Q$. $\blacksquare$

### 习题十四

(复合的连续性) 设 $E=C\left(\left[a,b\right],\mathbb R\right)$ 配 $\left\|\cdot\right\|_\infty$, $\varphi:\mathbb R\to\mathbb R$ 连续. 证明映射 $f\mapsto\varphi\circ f$ 从 $E$ 到 $E$ 连续.

### 解答 习题十四

由**推论 6.5** (紧空间上连续一致连续), $\left[a,b\right]$ 紧, $\varphi$ 在 $\mathbb R$ 上连续, 但 $f$ 的像有界; 进一步, $\varphi$ 在有界区间上一致连续. 对 $\epsilon>0$, 存在 $\delta>0$, 使 $\left|u-v\right|<\delta$ 时 $\left|\varphi\left(u\right)-\varphi\left(v\right)\right|<\epsilon$. 若 $\left\|f-g\right\|_\infty<\delta$, 则对一切 $x\in\left[a,b\right]$, $\left|f\left(x\right)-g\left(x\right)\right|<\delta$, 故

$$
\left\|\varphi\circ f-\varphi\circ g\right\|_\infty=\sup_x\left|\varphi\left(f\left(x\right)\right)-\varphi\left(g\left(x\right)\right)\right|\le\epsilon.
$$

故 $f\mapsto\varphi\circ f$ 连续. $\blacksquare$

### 习题十五

(非贝尔) 设 $E$ 是不满足**定理 6.13** (贝尔纲定理) 的赋范空间. 证明 $E$ 是可数个无处稠密闭集之并.

### 解答 习题十五

$E$ 非贝尔, 由定义 (即**定理 6.13** (贝尔纲定理) 不成立), 存在可数个稠密开集 $\left\{U_n\right\}$ 使 $\bigcap_n U_n=\emptyset$. 令 $F_n=E\setminus U_n$. 每个 $F_n$ 闭. $F_n$ 无处稠密: $U_n$ 稠密意味着 $F_n$ 内部为空 (否则其开邻域与 $U_n$ 不交, 与稠密矛盾). 而

$$
E=E\setminus\bigcap_n U_n=\bigcup_n\left(E\setminus U_n\right)=\bigcup_n F_n.
$$

故 $E$ 是可数个无处稠密闭集之并. $\blacksquare$

### 习题十六

(赋范空间命题) 证明: 赋范线性空间上范数映射 $x\mapsto\left\|x\right\|$ 连续, 且赋范空间在范数拓扑下是豪斯多夫的.

### 解答 习题十六

由**定义 6.20** (赋范线性空间), 范数满足三角不等式, 故 $\left|\left\|x\right\|-\left\|y\right\|\right|\le\left\|x-y\right\|$. 当 $x\to y$ 时 $\left\|x\right\|\to\left\|y\right\|$, 即范数连续.

豪斯多夫: 设 $x\neq y$, $r=\left\|x-y\right\|>0$. 取 $\epsilon=r/3$. 由**定义 3.10** (豪斯多夫空间), 开球 $B\left(x,\epsilon\right)$ 与 $B\left(y,\epsilon\right)$ 不相交 (否则由三角不等式 $\left\|x-y\right\|\le 2\epsilon<r$, 矛盾). 故赋范空间豪斯多夫. $\blacksquare$

### 习题十七

(商范数) 设 $E$ 是赋范线性空间, $F\subset E$ 是闭子空间. 证明 $E/F$ 配上

$$
\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|
$$

是一个赋范线性空间 (即**定义 6.29** (商范数)).

### 解答 习题十七

由**定义 6.29** (商范数), $\left\|\left[x\right]\right\|=\inf_{f\in F}\left\|x+f\right\|$.

(a) 非负与齐次显然.

(b) 三角不等式: $\left\|\left[x+y\right]\right\|\le\left\|x+f\right\|+\left\|y+g\right\|$ 对任意 $f,g\in F$, 取下确界得 $\left\|\left[x+y\right]\right\|\le\left\|\left[x\right]\right\|+\left\|\left[y\right]\right\|$.

(c) 正定性: 若 $\left\|\left[x\right]\right\|=0$, 则存在 $f_n\in F$ 使 $\left\|x+f_n\right\|\to 0$, 即 $-f_n\to x$. 因 $F$ 闭, $x\in F$, 故 $\left[x\right]=0$.

由**定义 6.20** (赋范线性空间), $E/F$ 是赋范空间. $\blacksquare$

### 习题十八

(连通边界) 设 $\left(E,d\right)$ 是连通度量空间, $F\subset E$ 闭, 且 $\partial F$ 连通. 证明 $F$ 连通.

### 解答 习题十八

反证. 若 $F$ 不连通, 由**定义 4.1** (连通空间), 存在 $F=A\sqcup B$, $A,B$ 非空、在 $F$ 中既开又闭. 因 $F$ 闭于 $E$, $A,B$ 闭于 $E$.

由**定义 3.20** (边界), $\partial F=\overline F\setminus\operatorname{int}\left(F\right)=F\setminus\operatorname{int}\left(F\right)$. 因 $\partial F$ 连通, 它不能同时与 $A,B$ 相交 (否则 $\partial F\cap A$ 与 $\partial F\cap B$ 是 $\partial F$ 的非空分离). 故不妨 $\partial F\subset A$. 于是 $B\cap\partial F=\emptyset$, 即 $B\subset\operatorname{int}\left(F\right)$.

$B$ 闭于 $E$, 且 $B\subset\operatorname{int}\left(F\right)$. 又 $B$ 在 $F$ 中开, 即 $B=F\cap O$, $O$ 开于 $E$. 因 $B\subset\operatorname{int}\left(F\right)$, $B=O\cap\operatorname{int}\left(F\right)$, 即 $B$ 开于 $E$. 故 $B$ 既开又闭于 $E$, 非空且不等于 $E$ ($B\subset F\subsetneq E$, 否则 $\partial F=\emptyset$). 这与 $E$ 连通矛盾. 故 $F$ 连通. $\blacksquare$
