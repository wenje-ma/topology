# 作业 10

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

> **定理 3.6** (豪斯多夫的遗传性)<br>两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 3.14** (初始拓扑)<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.16** (离散拓扑与平凡拓扑)<br>离散拓扑: $X$ 的所有子集都开; 平凡拓扑: 仅 $\emptyset,X$ 开. (教材 $\S3$)

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.19** (子空间拓扑)<br>设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 4.23** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定理 6.16** (巴拿赫不动点定理)<br>非空**定义 6.38** (完备度量空间) 上的**定义 6.19** (压缩映射) 有唯一不动点. (题集 $\S4.3$)

> **定义 6.19** (压缩映射)<br>称 $f:X\to X$ 是压缩的, 若存在 $0<k<1$ 使 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. (题集 $\S4.3$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法 $E\times E\to E$ 与数乘 $\mathbb K\times E\to E$ 都连续的拓扑. (题集 $\S5$)

> **定义 6.25** (半范数)<br>满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq 0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 $\S5$)

> **定义 6.26** (局部凸空间)<br>拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 $\S5$)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$. (题集 $\S5$)

> **定义 6.28** (算子范数)<br>$L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|$. (题集 $\S5$)

> **定义 6.30** (弱拓扑)<br>$E$ 上由全体连续线性泛函 $\varphi\in E^*$ 的拉回生成的初始拓扑. (题集 $\S5$)

> **定义 6.31** (弱星拓扑)<br>对偶 $E^*$ 上由赋值映射 $\left\{\varphi\mapsto\varphi\left(x\right)\right\}_{x\in E}$ 诱导的初始拓扑. (题集 $\S5$)

> **定义 6.32** (拓扑对偶)<br>$E^*=E$ 上全体连续线性泛函. (题集 $\S5$)

> **定义 6.35** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.37** (柯西列)<br>序列 $\left(x_n\right)$ 是柯西列, 若 $\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.38** (完备度量空间)<br>度量空间是完备的, 若其中每个柯西列都收敛. (教材 $\S6$)

> **定义 6.44** (伪距离)<br>满足除 "$d\left(x,y\right)=0\Rightarrow x=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 $\S1.3$)

> **定理 6.50** (哈恩-巴拿赫定理)<br>赋范线性空间上, 点与不相交闭凸集可被连续线性泛函严格分离; 特别地 $E^*$ 分离 $E$ 的点. (题集 $\S5$)

> **定义 11.1** (商拓扑)<br>满射 $\pi:X\to Y$ 下, $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 $\S11$)

> **定义 11.2** (商映射)<br>满射 $\pi:X\to Y$ 使 $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. (教材 $\S11$)

> **定义 11.3** (等价关系粘合)<br>$X/{\sim}$ 配商拓扑, $\pi:X\to X/{\sim}$ 为典范投影. (教材 $\S11$)

> **定义 11.6** (锥)<br>$CX=X\times\left[0,1\right]/X\times\left\{1\right\}$, 即将 $X\times\left\{1\right\}$ 整捏成一点. (教材 $\S11$)

> **定义 11.7** (环面)<br>正方形对边同向粘合所得 $S^1\times S^1$, 即 $\mathbb R^2/\mathbb Z^2$. (教材 $\S11$)

> **定义 11.11** (悬垂)<br>$SX=X\times\left[-1,1\right]/\left(X\times\left\{-1\right\}\cup X\times\left\{1\right\}\right)$, 两端各捏成一点. (题集 $\S5$)

> **定义 11.12** (塌缩商)<br>$X/\left\langle A\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 $\S5$)

> **定义 11.13** ($n$-维环面)<br>$T^n=\mathbb R^n/\mathbb Z^n\cong\left(S^1\right)^n$. (题集 $\S5$)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S1.4$)

> **定义 11.15** (等价关系的生成)<br>包含给定二元关系 $R$ 的最小等价关系, 即全体含 $R$ 的等价关系之交. (题集 $\S5$)

> **定义 11.18** (不交和拓扑)<br>一族拓扑空间 $\left\{X_i\right\}_{i\in I}$ 的不交和 $\coprod_{i\in I}X_i$ 上, $U$ 开当且仅当每个 $U\cap X_i$ 在 $X_i$ 中开. (题集 $\S5$)

### 习题一

设 $\left(X,d\right)$ 是非空**定义 6.38** (完备度量空间), $f:X\to X$ 是严格压缩的, 即存在 $0<k<1$ 使对一切 $x,y\in X$ 有 $d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$. 证明 $f$ 在 $X$ 中有唯一不动点, 即存在唯一的 $x\in X$ 使 $f\left(x\right)=x$.

### 解答 习题一

任取初值 $x_0\in X$, 迭代 $x_{n+1}=f\left(x_n\right)$. 由压缩条件,

$$
d\left(x_{n+1},x_n\right)=d\left(f\left(x_n\right),f\left(x_{n-1}\right)\right)\le k\,d\left(x_n,x_{n-1}\right)\le\cdots\le k^n d\left(x_1,x_0\right).
$$

对 $m>n$, 由三角不等式,

$$
d\left(x_m,x_n\right)\le\sum_{j=n}^{m-1}d\left(x_{j+1},x_j\right)\le d\left(x_1,x_0\right)\sum_{j=n}^{\infty}k^j=\frac{k^n}{1-k}d\left(x_1,x_0\right).
$$

右端当 $n\to\infty$ 时趋于 $0$, 故 $\left(x_n\right)$ 是**定义 6.37** (柯西列). 由 $X$ 是**定义 6.38** (完备度量空间), $x_n\to x\in X$. 由 $f$ 连续 (压缩蕴含利普希茨连续), $f\left(x_n\right)\to f\left(x\right)$; 但 $f\left(x_n\right)=x_{n+1}\to x$, 故 $f\left(x\right)=x$.

唯一性: 若 $f\left(x\right)=x$, $f\left(y\right)=y$, 则 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)\le k\,d\left(x,y\right)$, 而 $0<k<1$, 故 $d\left(x,y\right)=0$, 由**定义 6.35** (度量空间) 得 $x=y$. 这就是**定理 6.16** (巴拿赫不动点定理). $\blacksquare$

### 习题二

设 $\left(E,\left\|\cdot\right\|\right)$ 是域 $\mathbb K$ 上的**定义 6.20** (赋范线性空间), $f:E\to E$ 是连续线性映射. 证明存在常数 $K>0$, 使对一切 $x,y\in E$ 有 $\left\|f\left(x\right)-f\left(y\right)\right\|\le K\left\|x-y\right\|$.

### 解答 习题二

$\left(E,\left\|\cdot\right\|\right)$ 是**定义 6.20** (赋范线性空间). 由 $f$ 在 $0$ 连续, 存在 $\delta>0$, 使 $\left\|z\right\|<\delta$ 时 $\left\|f\left(z\right)\right\|\le1$. 对任意 $x\neq0$, 令 $z=\frac{\delta}{2\left\|x\right\|}x$, 则 $\left\|z\right\|=\delta/2<\delta$, 故 $\left\|f\left(z\right)\right\|\le1$. 由线性性,

$$
\left\|f\left(x\right)\right\|=\frac{2\left\|x\right\|}{\delta}\left\|f\left(z\right)\right\|\le\frac{2}{\delta}\left\|x\right\|.
$$

取 $K=2/\delta$. 对任意 $x,y$, 由线性性 $f\left(x\right)-f\left(y\right)=f\left(x-y\right)$, 故

$$
\left\|f\left(x\right)-f\left(y\right)\right\|=\left\|f\left(x-y\right)\right\|\le K\left\|x-y\right\|.
$$

$\blacksquare$

### 习题三

沿用习题二的设定, $E$ 完备. 证明: 对给定的 $\lambda\in\mathbb K$ 满足 $\left|\lambda\right|>K$, 固定 $a\in E$, 映射

$$
g_a\left(x\right)=\frac{a-f\left(x\right)}{\lambda}
$$

是**定义 6.19** (压缩映射); 用**定理 6.16** (巴拿赫不动点定理) 推出 $g_a$ 有唯一不动点 $J\left(a\right)\in E$.

### 解答 习题三

对 $x,y\in E$, 由习题二,

$$
\left\|g_a\left(x\right)-g_a\left(y\right)\right\|=\frac{\left\|f\left(x\right)-f\left(y\right)\right\|}{\left|\lambda\right|}\le\frac{K}{\left|\lambda\right|}\left\|x-y\right\|.
$$

由假设 $\left|\lambda\right|>K$, 故 $k=K/\left|\lambda\right|<1$. 由**定义 6.19** (压缩映射), $g_a$ 是压缩映射. $E$ 非空且是**定义 6.38** (完备度量空间), 由**定理 6.16** (巴拿赫不动点定理), $g_a$ 有唯一不动点, 记为 $J\left(a\right)$. $\blacksquare$

### 习题四

证明 $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$.

### 解答 习题四

由 $J\left(a\right)$ 与 $J\left(b\right)$ 分别是 $g_a$ 与 $g_b$ 的不动点,

$$
J\left(a\right)=\frac{a-f\left(J\left(a\right)\right)}{\lambda},\quad J\left(b\right)=\frac{b-f\left(J\left(b\right)\right)}{\lambda}.
$$

两式相减,

$$
J\left(a\right)-J\left(b\right)=\frac{a-b-f\left(J\left(a\right)\right)+f\left(J\left(b\right)\right)}{\lambda}.
$$

取范数并用三角不等式与习题二的估计,

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{\left\|a-b\right\|+\left\|f\left(J\left(a\right)\right)-f\left(J\left(b\right)\right)\right\|}{\left|\lambda\right|}\le\frac{\left\|a-b\right\|+K\left\|J\left(a\right)-J\left(b\right)\right\|}{\left|\lambda\right|}.
$$

移项得 $\left(\left|\lambda\right|-K\right)\left\|J\left(a\right)-J\left(b\right)\right\|\le\left\|a-b\right\|$, 即

$$
\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|.
$$

$\blacksquare$

### 习题五

总结如下结论: 对任意连续线性映射 $f:E\to E$, 存在 $K>0$, 使对一切满足 $\left|\lambda\right|>K$ 的 $\lambda$ 与一切 $a\in E$, 方程 $f\left(x\right)-\lambda x=a$ (未知量 $x\in E$) 有唯一解 $J\left(a\right)$, 且映射 $a\mapsto J\left(a\right)$ 连续.

### 解答 习题五

由习题二, 存在 $K>0$ 使 $\left\|f\left(x\right)-f\left(y\right)\right\|\le K\left\|x-y\right\|$. 设 $\left|\lambda\right|>K$. 方程 $f\left(x\right)-\lambda x=a$ 等价于

$$
x=\frac{a-f\left(x\right)}{\lambda}=g_a\left(x\right).
$$

由习题三, $g_a$ 是**定义 6.19** (压缩映射), 由**定理 6.16** (巴拿赫不动点定理), 该方程有唯一解 $J\left(a\right)$.

由习题四, $\left\|J\left(a\right)-J\left(b\right)\right\|\le\frac{1}{\left|\lambda\right|-K}\left\|a-b\right\|$, 即 $J$ 是利普希茨映射. 利普希茨映射连续: 对任意开集 $U\subset E$ 与 $a\in J^{-1}\left(U\right)$, 取 $\epsilon>0$ 使 $B\left(J\left(a\right),\epsilon\right)\subset U$, 则 $\left\|b-a\right\|<\left(\left|\lambda\right|-K\right)\epsilon$ 蕴含 $\left\|J\left(b\right)-J\left(a\right)\right\|<\epsilon$, 即 $J^{-1}\left(U\right)$ 含 $a$ 的一个邻域. 由**定义 3.22** (连续映射), $J$ 连续. $\blacksquare$

### 习题六

设 $X$ 是拓扑空间. 证明下列三条等价:

(1) $X$ 具有离散拓扑;

(2) $X$ 具有由单点族 $\left\{\left\{x\right\}\right\}_{x\in X}$ 诱导的弱 (最终) 拓扑;

(3) 从不交和 $\coprod_{x\in X}\left\{x\right\}$ 到 $X$ 的典范映射是同胚.

### 解答 习题六

记 $i_x:\left\{x\right\}\to X$ 为把单点映到其唯一点的含入映射.

**(1) $\Rightarrow$ (2)**: 设 $X$ 具离散拓扑, 由**定义 3.16** (离散拓扑与平凡拓扑) 每个子集都开. 由**定义 3.18** (拓扑空间) 这是一个合法拓扑. 由**定义 11.14** (最终拓扑), 由 $\left\{i_x\right\}$ 诱导的最终拓扑是使每个 $i_x$ 连续的最细拓扑; 离散拓扑本身使每个 $i_x$ 连续 (单点空间唯一可能), 且它已是最细拓扑, 故二者相同.

**(2) $\Rightarrow$ (1)**: 设 $X$ 上的拓扑就是由 $\left\{i_x\right\}$ 诱导的最终拓扑. 由**定义 11.14** (最终拓扑), $U\subset X$ 开当且仅当对每个 $x$, $i_x^{-1}\left(U\right)$ 在单点空间 $\left\{x\right\}$ 中开. 而单点空间的任意子集 (仅 $\emptyset$ 与 $\left\{x\right\}$) 都开, 故 $X$ 的任意子集 $U$ 都开. 由**定义 3.16** (离散拓扑与平凡拓扑), 这就是离散拓扑.

**(2) $\Leftrightarrow$ (3)**: 由**定义 11.18** (不交和拓扑), 不交和 $Z=\coprod_{x\in X}\left\{x\right\}$ 上的拓扑是每个单点都开, 即离散拓扑. 典范映射 $i:Z\to X$ 把每个 $\left\{x\right\}$ 映到 $x$, 是双射. 由**定义 3.11** (乘积拓扑) 的构造思路, $Z$ 上的最终拓扑 (关于含入 $Z\hookleftarrow\left\{x\right\}$) 恰为离散拓扑, 故 $i$ 连续当且仅当 $X$ 的拓扑粗于由 $\left\{i_x\right\}$ 诱导的最终拓扑; 反过来 $i^{-1}$ 连续当且仅当该最终拓扑粗于 $X$ 的拓扑. 由**定义 3.23** (同胚), $i$ 是同胚当且仅当 $X$ 的拓扑等于由 $\left\{i_x\right\}$ 诱导的最终拓扑, 即 (2). 三链贯通, 三条等价. $\blacksquare$

### 习题七

设 $X_i$ 是拓扑空间, $X_i\subset X_{i+1}$, $X=\bigcup_{i=1}^{\infty}X_i$. 设每个 $X_i$ 在 $X_{i+1}$ 中闭, 且 $X_i$ 的拓扑就是 $X_{i+1}$ 的拓扑在 $X_i$ 上诱导的子空间拓扑. 证明: 对每个 $i$, $X_i$ 的拓扑等于 $X$ 上由族 $\left\{X_i\right\}$ 诱导的弱 (最终) 拓扑在 $X_i$ 上诱导的子空间拓扑; 进一步每个 $X_i$ 在 $X$ 中闭.

### 解答 习题七

记 $\tau$ 为 $X$ 上由含入 $j_i:X_i\to X$ 诱导的最终拓扑. 由**定义 11.14** (最终拓扑), $U\subset X$ 在 $\tau$ 中开当且仅当对每个 $k$, $U\cap X_k$ 在 $X_k$ 中开. 由题设归纳可知: 对 $k\ge i$, $X_i$ 在 $X_k$ 中闭; 且 $X_i$ 的拓扑就是 $X_k$ 的拓扑在 $X_i$ 上的子空间拓扑.

先证子空间一致性. 由**定义 3.19** (子空间拓扑), $X_i$ 从 $\left(X,\tau\right)$ 继承的开集为 $\left\{U\cap X_i:U\in\tau\right\}$.

(a) 包含 $\supset$: 若 $U\in\tau$, 由上面的刻画 $U\cap X_i$ 在 $X_i$ 中开, 故继承开集都是原拓扑开集.

(b) 包含 $\subset$: 任取原开集 $V\subset X_i$. 构造

$$
U=V\cup\left(X\setminus X_i\right).
$$

则 $U\cap X_i=V$. 验证 $U\in\tau$: 对 $k=i$, $U\cap X_i=V$ 开; 对 $k<i$, $X_k\subset X_i$, 故 $U\cap X_k=V\cap X_k$, 由 $X_k$ 的子空间性质它在 $X_k$ 中开; 对 $k>i$, $X_i$ 在 $X_k$ 中闭, 故 $X_k\setminus X_i$ 在 $X_k$ 中开, 而 $V$ 在 $X_i$ 中开, 由 $X_i$ 是 $X_k$ 的子空间可写 $V=X_i\cap W$, $W$ 在 $X_k$ 中开, 于是 $U\cap X_k=\left(X_i\cap W\right)\cup\left(X_k\setminus X_i\right)=W\cup\left(X_k\setminus X_i\right)$ 在 $X_k$ 中开. 故 $U\in\tau$, 且 $V=U\cap X_i$ 是继承开集.

故 $X_i$ 的原拓扑等于继承拓扑.

再证 $X_i$ 在 $X$ 中闭. 由**定义 3.19** (子空间拓扑) 的逆运算思路, 只需证 $X\setminus X_i$ 在 $\tau$ 中开. 对 $k\le i$, $\left(X\setminus X_i\right)\cap X_k=\emptyset$ 开; 对 $k>i$, $X_i$ 在 $X_k$ 中闭, 故 $\left(X\setminus X_i\right)\cap X_k=X_k\setminus X_i$ 在 $X_k$ 中开. 由**定义 11.14** (最终拓扑), $X\setminus X_i\in\tau$, 故 $X_i$ 闭. $\blacksquare$

### 习题八

(二元关系生成的等价关系) 设 $X$ 是集合, $R\subset X\times X$ 是二元关系 (未必是等价关系). 证明: 存在唯一的最小等价关系 $\sim$ 包含 $R$ (在 $X\times X$ 的子集意义下), 称为由 $R$ 生成的等价关系.

### 解答 习题八

先证一族等价关系的交仍是等价关系. 设 $\left\{\sim_\alpha\right\}_{\alpha\in A}$ 是 $X$ 上的等价关系族, 定义 $x\sim y$ 当且仅当对一切 $\alpha$ 有 $x\sim_\alpha y$.

(a) 自反: 每个 $\sim_\alpha$ 自反, 故 $x\sim_\alpha x$ 对一切 $\alpha$, 即 $x\sim x$.

(b) 对称: $x\sim y$ 蕴含 $x\sim_\alpha y$ 对一切 $\alpha$, 由每个 $\sim_\alpha$ 对称得 $y\sim_\alpha x$, 故 $y\sim x$.

(c) 传递: $x\sim y$ 且 $y\sim z$, 则对一切 $\alpha$, $x\sim_\alpha y$ 且 $y\sim_\alpha z$, 由每个 $\sim_\alpha$ 传递得 $x\sim_\alpha z$, 故 $x\sim z$.

故 $\sim$ 是等价关系.

现令 $\mathcal E$ 为 $X$ 上全体包含 $R$ 的等价关系所成之族. 全体成员的交 $\bigcap\mathcal E$ 仍含 $R$ (每个成员含 $R$), 且由上面的交性质是等价关系. 它是含 $R$ 的最小等价关系: 任何含 $R$ 的等价关系都在 $\mathcal E$ 中, 从而包含这个交. 唯一性由"最小"即集包含意义下唯一决定. 由**定义 11.15** (等价关系的生成), 这个交就是由 $R$ 生成的等价关系. $\blacksquare$

### 习题九

(伪距离的商距离) 回顾伪距离 $d$ 是除 $d\left(x,y\right)=0\Rightarrow x=y$ 外满足全部度量公理的函数, 见**定义 6.44** (伪距离). 伪距离空间 $\left(X,d\right)$ 以开球 $B\left(x,\epsilon\right)$ 为基有拓扑. 定义 $x\sim y$ 当且仅当 $d\left(x,y\right)=0$. 证明: $\sim$ 是等价关系; 商空间 $X/{\sim}$ 上可赋予距离 $d'$ 使 $d'\left(\left[x\right],\left[y\right]\right)=d\left(x,y\right)$; 验证 $d'$ 定义适定; 证明度量空间 $\left(X/{\sim},d'\right)$ 与商空间 $X/{\sim}$ 拓扑相同; 并证明若 $F$ 是豪斯多夫空间且 $f:X\to F$ 连续, 则 $f$ 可分解为 $f=f'\circ\pi$, 其中 $f':X/{\sim}\to F$.

### 解答 习题九

**$\sim$ 是等价关系**: 由**定义 6.44** (伪距离), $d\left(x,x\right)=0$ 给出自反; $d\left(x,y\right)=d\left(y,x\right)$ 给出对称; 三角不等式 $d\left(x,z\right)\le d\left(x,y\right)+d\left(y,z\right)$ 在 $d\left(x,y\right)=d\left(y,z\right)=0$ 时给出 $d\left(x,z\right)=0$, 即传递.

**$d'$ 适定**: 若 $x\sim x'$, $y\sim y'$, 则 $d\left(x,x'\right)=d\left(y,y'\right)=0$, 由三角不等式,

$$
d\left(x,y\right)\le d\left(x,x'\right)+d\left(x',y'\right)+d\left(y',y\right)=d\left(x',y'\right),
$$

同理 $d\left(x',y'\right)\le d\left(x,y\right)$. 故二者相等, $d'\left(\left[x\right],\left[y\right]\right):=d\left(x,y\right)$ 与代表元选取无关.

**$d'$ 是度量**: 非负、对称、三角不等式都从 $d$ 继承; 而 $d'\left(\left[x\right],\left[y\right]\right)=0$ 即 $d\left(x,y\right)=0$, 即 $x\sim y$, 即 $\left[x\right]=\left[y\right]$. 正定性成立.

**拓扑相同**: 记 $\pi:X\to X/{\sim}$ 为商投影. 对任意 $x,\epsilon$,

$$
\pi^{-1}\left(B_{d'}\left(\left[x\right],\epsilon\right)\right)=B_d\left(x,\epsilon\right).
$$

包含 $\subset$: 若 $z$ 使 $d'\left(\left[z\right],\left[x\right]\right)<\epsilon$, 即 $d\left(z,x\right)<\epsilon$, 则 $z\in B_d\left(x,\epsilon\right)$. 包含 $\supset$: 若 $z\in B_d\left(x,\epsilon\right)$, 则 $d'\left(\left[z\right],\left[x\right]\right)=d\left(z,x\right)<\epsilon$. 由**定义 11.1** (商拓扑), $B_{d'}\left(\left[x\right],\epsilon\right)$ 是商开集, 故度量拓扑粗于商拓扑. 反之, 若 $U$ 是商开集, 则 $\pi^{-1}\left(U\right)$ 是 $d$-开集, 从而是若干 $d$-球之并, 其像 $U=\pi\left(\pi^{-1}\left(U\right)\right)$ 是若干 $d'$-球之并, 故 $U$ 是度量开集. 二者一致.

**泛分解**: 设 $F$ 豪斯多夫, $f:X\to F$ 连续. 先证 $f$ 在等价类上取常值. 若 $x\sim x'$, 即 $d\left(x,x'\right)=0$, 则 $x$ 与 $x'$ 在 $X$ 中无法用开集分离: 对任意 $\epsilon>0$, $B_d\left(x,\epsilon\right)=B_d\left(x',\epsilon\right)$. 若 $f\left(x\right)\neq f\left(x'\right)$, 由**定义 3.10** (豪斯多夫空间) 存在不相交开邻域 $V\ni f\left(x\right)$, $W\ni f\left(x'\right)$. 由**定义 3.22** (连续映射), $f^{-1}\left(V\right)$ 是 $x$ 的开邻域, 从而含 $x'$, 故 $f\left(x'\right)\in V$, 与 $V\cap W=\emptyset$ 及 $f\left(x'\right)\in W$ 矛盾. 故 $f\left(x\right)=f\left(x'\right)$.

于是可定义 $f'\left(\left[x\right]\right)=f\left(x\right)$, 适定. 由**定义 11.2** (商映射), 为证 $f'$ 连续, 只需对任意开集 $O\subset F$, $\left(f'\right)^{-1}\left(O\right)$ 商开, 即 $\pi^{-1}\left(\left(f'\right)^{-1}\left(O\right)\right)=f^{-1}\left(O\right)$ 在 $X$ 中开; 这由 $f$ 连续保证. 故 $f=f'\circ\pi$. $\blacksquare$

### 习题十

证明: 实或复拓扑向量空间是局部凸的, 当且仅当其拓扑由一族半范数定义. 进一步证明: 在实或复拓扑向量空间中, $0$ 有可数凸邻域基, 当且仅当拓扑由可数族半范数定义.

### 解答 习题十

**($\Leftarrow$)**: 设拓扑由半范数族 $\left\{p_\alpha\right\}_{\alpha\in A}$ 定义. 由**定义 6.25** (半范数), 每个 $p_\alpha$ 是凸函数 (由三角不等式 $p_\alpha\left(\left(1-t\right)x+ty\right)\le\left(1-t\right)p_\alpha\left(x\right)+tp_\alpha\left(y\right)$). 形如

$$
U_{\alpha_1,\dots,\alpha_n;\epsilon}=\left\{x:p_{\alpha_i}\left(x\right)<\epsilon,\ i=1,\dots,n\right\}
$$

的集合是有限个凸集的交, 由**定义 4.23** (凸集) 仍是凸集; 它们构成 $0$ 的邻域基. 故由**定义 6.26** (局部凸空间), 空间局部凸.

**($\Rightarrow$)**: 设空间局部凸. 由**定义 6.26** (局部凸空间), $0$ 有凸邻域基 $\left\{C_\alpha\right\}_{\alpha\in A}$. 由**定义 6.24** (拓扑向量空间), 加法与数乘连续, 故可在不损失凸性的前提下取每个 $C_\alpha$ 为平衡凸邻域 (即 $x\in C_\alpha$ 蕴含 $\lambda x\in C_\alpha$ 对一切 $\left|\lambda\right|\le 1$). 定义

$$
p_\alpha\left(x\right)=\inf\left\{t>0:x\in t\,C_\alpha\right\}.
$$

这正是**定义 6.27** (规范函数). 由 $C_\alpha$ 凸且平衡, $p_\alpha$ 满足**定义 6.25** (半范数) 的两条: 齐次 $p_\alpha\left(\lambda x\right)=\left|\lambda\right|p_\alpha\left(x\right)$; 三角不等式由 $C_\alpha$ 凸推出. 邻域 $\left\{p_\alpha<\epsilon\right\}$ 就是 $\epsilon C_\alpha$, 故半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑与原拓扑相同.

**可数情形**: 若 $0$ 有可数凸邻域基 $\left\{C_n\right\}_{n\ge 1}$, 上面的构造给出可数半范数族 $\left\{p_n\right\}$. 反之, 若拓扑由可数半范数族 $\left\{p_n\right\}$ 定义, 则 $\left\{x:p_i\left(x\right)<1/k,\ i=1,\dots,n\right\}$ ($n,k\ge 1$) 是可数凸邻域基. $\blacksquare$

### 习题十一

设 $\pi:\mathbb R^2\to T^2$ 是典范投影, $\alpha\in\mathbb R\cup\left\{\infty\right\}$, $D$ 是 $\mathbb R^2$ 中斜率为 $\alpha$ 的直线. 证明: 若 $\alpha\in\mathbb Q\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 同胚于一个圆; 若 $\alpha\notin\mathbb Q\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 在 $T^2$ 中稠密, 且 $\pi|_D$ 是 $D$ 到 $\pi\left(D\right)$ 的连续双射.

### 解答 习题十一

由**定义 11.7** (环面), $T^2=\mathbb R^2/\mathbb Z^2$, $\pi$ 为商投影. 不妨取 $D=\left\{\left(t,\alpha t\right):t\in\mathbb R\right\}$ (竖直直线 $\alpha=\infty$ 同理).

**有理斜率**: 设 $\alpha=p/q$, $p,q\in\mathbb Z$, $\gcd\left(p,q\right)=1$. 映射 $g:\mathbb R/q\mathbb Z\to T^2$, $g\left(t\right)=\pi\left(t,\alpha t\right)$. 它良定义且连续. 它是单射: 若 $\pi\left(t,\alpha t\right)=\pi\left(t',\alpha t'\right)$, 则 $t-t'\in\mathbb Z$ 且 $p\left(t-t'\right)/q\in\mathbb Z$, 即 $q\mid p\left(t-t'\right)$; 由 $\gcd\left(p,q\right)=1$, $q\mid t-t'$, 即在 $\mathbb R/q\mathbb Z$ 中相等. $\mathbb R/q\mathbb Z$ 是紧圆 (同胚于 $S^1$), $T^2$ 是豪斯多夫的 (乘积空间 $S^1\times S^1$ 豪斯多夫). 由**定理 5.6** (紧豪斯多夫间的连续双射), $g$ 是同胚. 故 $\pi\left(D\right)=g\left(\mathbb R/q\mathbb Z\right)$ 同胚于圆.

**无理斜率**: 设 $\alpha\notin\mathbb Q$. 先证 $\pi\left(D\right)$ 在 $T^2$ 中稠密. 由**定义 3.32** (稠密), 只需证其闭包为全空间. 注意 $\pi\left(D\right)$ 是 $T^2$ 的子群, 且包含循环子群 $H=\left\{\pi\left(n,n\alpha\right):n\in\mathbb Z\right\}$. 由无理数的狄利克雷逼近, 对任意 $\epsilon>0$, 存在非零整数 $n$ 使 $\left\|n\alpha\right\|<\epsilon$ ($\left\|\cdot\right\|$ 表示到最近整数距离). 于是 $H$ 中含一个离 $\left(0,0\right)$ 极近的非零点, 其整数倍数在 $T^2$ 中环绕出稠密的一维子群; 故 $H$ 在 $T^2$ 中稠密. 因 $\pi\left(D\right)\supset H$, $\pi\left(D\right)$ 在 $T^2$ 中稠密.

$\pi|_D:D\to\pi\left(D\right)$ 连续 (商映射限制) 且为双射: 若 $\pi\left(t,\alpha t\right)=\pi\left(t',\alpha t'\right)$, 则 $t-t'\in\mathbb Z$ 且 $\alpha\left(t-t'\right)\in\mathbb Z$, 由 $\alpha$ 无理必有 $t-t'=0$. 但它不是同胚: $D$ 与 $\mathbb R$ 同胚, 不紧, 而 $\pi\left(D\right)$ 在 $T^2$ 中稠密 (因 $T^2$ 紧, $\pi\left(D\right)$ 的闭包紧); 若它同胚于 $D\cong\mathbb R$, 则它不闭, 但上面已证它稠密, 不影响连续性, 关键是开映射性失效: 取 $D$ 中一小段, 其像在 $\pi\left(D\right)$ 中并不总是开的. $\blacksquare$

### 习题十二

设 $\pi:\mathbb R^2\to T^2$ 是典范投影, $\alpha\in\mathbb R\cup\left\{\infty\right\}$. 在 $T^2$ 上定义关系: $x'\sim y'$ 当且仅当存在 $x,y\in\mathbb R^2$ 与斜率为 $\alpha$ 的直线使 $\pi\left(x\right)=x'$, $\pi\left(y\right)=y'$. 证明 $\sim$ 是等价关系; 证明商空间 $T^2/{\sim}$ 豪斯多夫当且仅当 $\alpha\in\mathbb Q$, 此时商空间同胚于一个圆; 若 $\alpha\notin\mathbb Q$, 证明商空间 $T^2/{\sim}$ 具有平凡拓扑.

### 解答 习题十二

把 $\pi\left(D\right)$ 记为 $H\subset T^2$, 其中 $D=\left\{\left(t,\alpha t\right)\right\}$. 关系 $x'\sim y'$ 即 $y'-x'\in H$ ($T^2$ 中的群运算).

**等价关系**: $H$ 是 $T^2$ 的子群: 含单位元; 对减法封闭. 故按子群取陪集是等价关系: 自反 ($0\in H$), 对称 ($H$ 对逆元封闭), 传递 ($H$ 对加法封闭). 由**定义 11.3** (等价关系粘合), $T^2/{\sim}=T^2/H$.

**有理斜率**: 设 $\alpha=p/q\in\mathbb Q$. 由习题七, $H$ 是 $T^2$ 中的一个闭圆子群. 定义

$$
\varphi:T^2\to S^1,\quad \varphi\left(u,v\right)=qu-pv\pmod 1.
$$

$\varphi$ 连续, 其核恰为 $H$ (即 $\varphi\left(u,v\right)=0\Leftrightarrow\left(u,v\right)\in H$). 由商空间泛性质, $\varphi$ 诱导连续双射 $\overline\varphi:T^2/H\to S^1$. $T^2/H$ 紧 ($T^2$ 紧, 商连续像紧), $S^1$ 豪斯多夫. 由**定理 5.6** (紧豪斯多夫间的连续双射), $\overline\varphi$ 是同胚. 故 $T^2/H$ 同胚于圆, 且圆豪斯多夫, 由**定义 3.10** (豪斯多夫空间) 商空间豪斯多夫.

**无理斜率**: 由习题七, $H$ 在 $T^2$ 中稠密. 商拓扑下, 由**定义 11.1** (商拓扑), 开集 $U\subset T^2/H$ 对应于 $T^2$ 中的 $H$-饱和开集. 若 $U$ 非空, 取饱和开集 $V\subset T^2$, $V\neq\emptyset$. 因 $H$ 稠密, $V+H=T^2$; 而 $V$ 已饱和, $V+H=V$, 故 $V=T^2$, 即 $U=T^2/H$. 故仅有的开集是 $\emptyset$ 与全空间, 即平凡拓扑. 此时商空间不豪斯多夫 (除非单点), 与有理情形对照. $\blacksquare$

### 习题十三

(锥) 设 $CX$ 是 $X$ 上的锥空间, 由**定义 11.6** (锥) 为 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 证明: 映射 $X\to CX$, $x\mapsto\left[\left(x,0\right)\right]$ 是到其像的同胚, 从而 $X$ 可视为 $CX$ 的子集. 证明: 若 $f:X\to Y$ 连续, 则 $Cf:CX\to CY$, $\left[\left(x,t\right)\right]\mapsto\left[\left(f\left(x\right),t\right)\right]$ 连续.

### 解答 习题十三

**嵌入**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 记 $\pi:X\times\left[0,1\right]\to CX$ 为商投影, $j:X\to CX$, $j\left(x\right)=\left[\left(x,0\right)\right]$. 因 $X\times\left\{0\right\}$ 与被捏合集 $X\times\left\{1\right\}$ 不相交, $\pi$ 在 $X\times\left\{0\right\}$ 上是单射, 故 $j$ 是双射到 $j\left(X\right)$.

$j$ 连续: 它是含入 $X\cong X\times\left\{0\right\}\hookrightarrow X\times\left[0,1\right]$ 与 $\pi$ 的复合, 由**定理 3.1** (复合连续) 连续.

逆连续: 任取 $X$ 中开集 $U$. 需证 $j\left(U\right)$ 是 $j\left(X\right)$ (子空间) 中的开集. 构造 $V=U\times\left[0,1/2\right)\subset X\times\left[0,1\right]$. 由**定义 3.11** (乘积拓扑), $V$ 开. 它不与 $X\times\left\{1\right\}$ 相交, 故饱和 (与等价类只交整体不交), 由**定义 11.1** (商拓扑), $\pi\left(V\right)$ 在 $CX$ 中开. 而 $\pi\left(V\right)\cap j\left(X\right)=j\left(U\right)$. 故 $j\left(U\right)$ 是 $CX$ 的开集与 $j\left(X\right)$ 的交, 即 $j\left(X\right)$ 中的开集. 由**定义 3.23** (同胚), $j$ 是 $X$ 到 $j\left(X\right)$ 的同胚.

**$Cf$ 连续**: 由**定义 11.2** (商映射), 只需证对任意开集 $W\subset CY$, $\left(Cf\right)^{-1}\left(W\right)$ 在 $CX$ 中开, 即 $\pi_X^{-1}\left(\left(Cf\right)^{-1}\left(W\right)\right)$ 在 $X\times\left[0,1\right]$ 中开. 该原像等于

$$
\left\{\left(x,t\right):\left(f\left(x\right),t\right)\in\pi_Y^{-1}\left(W\right)\right\}=\left(f\times\operatorname{id}\right)^{-1}\left(\pi_Y^{-1}\left(W\right)\right).
$$

$\pi_Y^{-1}\left(W\right)$ 在 $Y\times\left[0,1\right]$ 中开, $f\times\operatorname{id}$ 连续 (由 $f$ 连续与 $\operatorname{id}$ 连续, 乘积映射连续), 故由**定义 3.22** (连续映射), 上式在 $X\times\left[0,1\right]$ 中开. 故 $Cf$ 连续. $\blacksquare$

### 习题十四

(悬垂) 设 $S^n=\left\{x\in\mathbb R^{n+1}:x_1^2+\cdots+x_{n+1}^2=1\right\}$. 证明悬垂 $S\left(S^n\right)$ 同胚于 $S^{n+1}$.

### 解答 习题十四

由**定义 11.11** (悬垂), $S\left(S^n\right)=S^n\times\left[-1,1\right]/\left(S^n\times\left\{-1\right\}\cup S^n\times\left\{1\right\}\right)$, 这是**定义 11.3** (等价关系粘合) 意义下的商空间. 定义

$$
F:S^n\times\left[-1,1\right]\to S^{n+1}\subset\mathbb R^{n+1}\times\mathbb R,\quad F\left(u,t\right)=\left(\sqrt{1-t^2}\,u,t\right).
$$

验证: $\left\|\sqrt{1-t^2}\,u\right\|^2+t^2=\left(1-t^2\right)\left\|u\right\|^2+t^2=1$, 故像在 $S^{n+1}$ 上. $F$ 连续. $F\left(u,1\right)=\left(0,1\right)$ 对一切 $u$, $F\left(u,-1\right)=\left(0,-1\right)$ 对一切 $u$, 故两端被压成两点, $F$ 经由商映射分解为连续双射 $\overline F:S\left(S^n\right)\to S^{n+1}$.

紧性: $S^n$ 紧, $\left[-1,1\right]$ 紧, 由**定义 3.11** (乘积拓扑) 之乘积紧, 再由**定理 5.1** (紧空间连续像紧), $S\left(S^n\right)$ 紧. $S^{n+1}$ 是豪斯多夫的 ($\mathbb R^{n+2}$ 的子空间, 由**定理 3.6** (豪斯多夫的遗传性)). 由**定理 5.6** (紧豪斯多夫间的连续双射), $\overline F$ 是同胚. $\blacksquare$

### 习题十五

(塌缩) 证明: 若 $A\subset X$ 是开 (或闭) 集, 则投影 $X\to X/\left\langle A\right\rangle$ 限制在 $X\setminus A$ 上是同胚. 证明 $CX/\left\langle X\right\rangle$ 与 $SX$ 同胚 (这里把 $X$ 等同于 $\pi\left(X\times\left\{0\right\}\right)\subset CX$).

### 解答 习题十五

记 $\pi:X\to X/\left\langle A\right\rangle$ 为商投影, 见**定义 11.12** (塌缩商). $\pi|_{X\setminus A}:X\setminus A\to\pi\left(X\setminus A\right)$ 连续且为双射 ($X\setminus A$ 内任意两点不被粘合).

**$A$ 闭**: $X\setminus A$ 开. 任取 $U\subset X\setminus A$ 为子空间开集, 由**定义 3.19** (子空间拓扑) $U=V\cap\left(X\setminus A\right)$, $V$ 开于 $X$; 因 $X\setminus A$ 开, $U$ 开于 $X$. 又 $U\cap A=\emptyset$, 故 $\pi^{-1}\left(\pi\left(U\right)\right)=U$ 开. 由**定义 11.1** (商拓扑), $\pi\left(U\right)$ 开, 故 $\left(\pi|_{X\setminus A}\right)^{-1}$ 连续.

**$A$ 开**: 任取子空间开 $U=V\cap\left(X\setminus A\right)$, $V$ 开. 令 $W=V\cup A$. 由 $A$ 开, $W$ 开于 $X$. 而 $\pi^{-1}\left(\pi\left(W\right)\right)=W\cup A=W$ (因 $A$ 已被捏合), 故 $\pi\left(W\right)$ 商开. 且 $\pi\left(W\right)\cap\pi\left(X\setminus A\right)=\pi\left(V\cap\left(X\setminus A\right)\right)=\pi\left(U\right)$. 故 $\pi\left(U\right)$ 是商开集与 $\pi\left(X\setminus A\right)$ 的交, 即子空间开. 逆连续. 由**定义 3.23** (同胚), 限制为同胚.

**$CX/\left\langle X\right\rangle\cong SX$**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 在 $CX$ 中再把 $\pi\left(X\times\left\{0\right\}\right)$ 捏成一点, 等价于在 $X\times\left[0,1\right]$ 上把 $X\times\left\{0\right\}$ 与 $X\times\left\{1\right\}$ 各捏成一点. 这正是**定义 11.11** (悬垂) 中的 $SX$ (经 $t\mapsto 2t-1$ 把 $\left[0,1\right]$ 线性映到 $\left[-1,1\right]$). $\blacksquare$

### 习题十六

($n$-维环面) 设 $T^n=\mathbb R^n/\mathbb Z^n$, 映射

$$
\phi:\left[\left(t_1,\dots,t_n\right)\right]\mapsto\left(e^{2\pi i t_1},\dots,e^{2\pi i t_n}\right).
$$

(1) 证明 $\phi$ 连续;

(2) 证明 $T^n$ 豪斯多夫;

(3) 证明 $\phi$ 是同胚.

### 解答 习题十六

**第 1 小题**: 由**定义 11.13** ($n$-维环面), $\mathbb R^n\to\left(S^1\right)^n$ 的映射 $F\left(t\right)=\left(e^{2\pi i t_1},\dots,e^{2\pi i t_n}\right)$ 连续, 且在 $\mathbb Z^n$ 陪集上取等值. 由**定义 11.2** (商映射), $F$ 经由商映射分解为连续 $\phi:T^n\to\left(S^1\right)^n$.

**第 2 小题**: $T^n$ 是豪斯多夫的: 下一问证 $\phi$ 是到 $\left(S^1\right)^n$ 的同胚, 而 $\left(S^1\right)^n$ 由**定理 3.6** (豪斯多夫的遗传性) 是豪斯多夫的, 故 $T^n$ 豪斯多夫.

**第 3 小题**: $\phi$ 是双射: $\left(e^{2\pi i t_1},\dots\right)$ 的原像陪集唯一. $T^n$ 紧: 它是 $n$ 方体 $\left[0,1\right]^n$ 的商, 由**定理 5.1** (紧空间连续像紧) 紧. $\left(S^1\right)^n$ 豪斯多夫. 由**定理 5.6** (紧豪斯多夫间的连续双射), $\phi$ 是同胚. $\blacksquare$

### 习题十七

设 $E$ 是 $\mathbb K$ 上拓扑向量空间, $C$ 是 $0$ 的凸邻域, 规范函数 $\left\|\cdot\right\|_C:E\to\left[0,\infty\right)$ 由**定义 6.27** (规范函数) 给出. 若 $\left\{C_\alpha\right\}_{\alpha\in A}$ 是 $E$ 中一族凸集且其交是 $0$ 的凸邻域, 证明

$$
\left\|\cdot\right\|_{\bigcap_{\alpha\in A}C_\alpha}=\sup_{\alpha\in A}\left\|\cdot\right\|_{C_\alpha}.
$$

### 解答 习题十七

记 $C=\bigcap_{\alpha\in A}C_\alpha$. 由**定义 6.27** (规范函数),

$$
\left\|x\right\|_C=\inf\left\{t>0:x\in tC\right\}=\inf\left\{t>0:\text{对一切 $\alpha$, }x\in tC_\alpha\right\}.
$$

而 $x\in tC_\alpha$ 当且仅当 $t\ge\left\|x\right\|_{C_\alpha}$ (规范函数的次水平集刻画). 故同时对一切 $\alpha$ 成立当且仅当

$$
t\ge\sup_{\alpha\in A}\left\|x\right\|_{C_\alpha}.
$$

取下确界即得

$$
\left\|x\right\|_C=\sup_{\alpha\in A}\left\|x\right\|_{C_\alpha}.
$$

两边对一切 $x\in E$ 成立, 故函数相等. $\blacksquare$

### 习题十八

设 $E,F,G$ 是赋范域 $\mathbb K$ 上的拓扑向量空间. 对 $f\in L\left(E,F\right)$, 右复合映射 $R_f:L\left(F,G\right)\to L\left(E,G\right)$, $g\mapsto g\circ f$. 证明 $R_f$ 的算子范数不超过 $f$ 的算子范数; 左复合同理. 证明映射 $E\to L\left(\mathbb K,E\right)$, $x\mapsto\left(\varphi_x:t\mapsto tx\right)$ 是等距线性同构.

### 解答 习题十八

由**定义 6.24** (拓扑向量空间), $E,F,G$ 的加法与数乘连续; 由**定义 6.20** (赋范线性空间), 其上装备范数, $L\left(E,F\right)$ 为连续线性映射全体.

**右复合**: 由**定义 6.28** (算子范数), 对 $g\in L\left(F,G\right)$ 与 $x\in E$, $g\circ f$ 作为复合映射由**定理 3.1** (复合连续) 连续, 且

$$
\left\|g\circ f\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\left(x\right)\right\|\le\left\|g\right\|\cdot\left\|f\right\|\cdot\left\|x\right\|.
$$

两边除以 $\left\|x\right\|$ 并取上确界, 得 $\left\|g\circ f\right\|\le\left\|g\right\|\left\|f\right\|$. 于是 $\left\|R_f\left(g\right)\right\|\le\left\|f\right\|\left\|g\right\|$, 即 $\left\|R_f\right\|\le\left\|f\right\|$.

**左复合**: 同理, $L_f:g\mapsto f\circ g$ ($g\in L\left(G,E\right)$, $f\in L\left(E,F\right)$), 有 $\left\|f\circ g\right\|\le\left\|f\right\|\left\|g\right\|$, 故 $\left\|L_f\right\|\le\left\|f\right\|$.

**等距线性同构**: 映射 $x\mapsto\varphi_x$, $\varphi_x\left(t\right)=tx$. 线性显然. 由**定义 6.28** (算子范数),

$$
\left\|\varphi_x\right\|=\sup_{\left\|t\right\|\le 1}\left\|tx\right\|=\sup_{\left\|t\right\|\le 1}\left|t\right|\cdot\left\|x\right\|=\left\|x\right\|.
$$

故等距. 它线性且保范数, 故单射; 满射: 任意 $\psi\in L\left(\mathbb K,E\right)$ 由 $\psi\left(1\right)\in E$ 决定, 即 $\psi=\varphi_{\psi\left(1\right)}$. 故为线性同构. $\blacksquare$

### 习题十九

证明: 若 $E$ 是无穷维拓扑向量空间, 则 $E$ 上强拓扑与弱拓扑不同. 计算弱拓扑下 $E$ 的开单位球的内部; 计算弱拓扑下 $E$ 的单位球面的闭包.

### 解答 习题十九

由**定义 6.30** (弱拓扑), 弱拓扑是由 $E^*$ 中全体连续线性泛函诱导的初始拓扑. 由**定理 6.50** (哈恩-巴拿赫定理), $E^*$ 分离 $E$ 的点. 弱拓扑的基本邻域形如

$$
U\left(x_0;\varphi_1,\dots,\varphi_n;\epsilon\right)=\left\{x:\left|\varphi_i\left(x-x_0\right)\right|<\epsilon,\ i=1,\dots,n\right\}.
$$

它是 $x_0$ 加上有限个超平面交 (即无穷维仿射子空间) 的 $\epsilon$-管.

**强 $\neq$ 弱**: 在无穷维, 任意弱开邻域 $U$ 都含一个无穷维仿射子空间, 故不可能含于一个强有界集; 特别地强开单位球不是弱开的. 故弱拓扑严格粗于强拓扑.

**开单位球的弱内部**: 弱开邻域含无穷维仿射子空间, 因而其中有无界点, 不可能含于有界开单位球. 故弱拓扑下开单位球的内部为 $\emptyset$.

**单位球面的弱闭包**: 由**定理 6.50** (哈恩-巴拿赫定理), 任意 $x_0$ 满足 $\left\|x_0\right\|\le 1$ 都可被球面中点弱逼近: 若 $\left\|x_0\right\|<1$, 沿任意方向取小步长即可进入球面; 若 $\left\|x_0\right\|=1$, $x_0$ 本身在球面上. 反之弱闭包不能超出闭单位球 (范数是弱下半连续的). 故弱闭包等于闭单位球 $\left\{x:\left\|x\right\|\le 1\right\}$. $\blacksquare$

### 习题二十

证明弱星拓扑总是豪斯多夫的.

### 解答 习题二十

由**定义 6.31** (弱星拓扑), $E^*$ 上的弱星拓扑是由赋值映射 $\operatorname{ev}_x:E^*\to\mathbb R$, $\operatorname{ev}_x\left(\varphi\right)=\varphi\left(x\right)$, $x\in E$, 诱导的初始拓扑. 由**定义 3.22** (连续映射), $\operatorname{ev}_x$ 连续. 任取 $\varphi,\psi\in E^*$, $\varphi\neq\psi$. 由**定义 6.32** (拓扑对偶) 二者为连续线性泛函, 存在 $x\in E$ 使 $\varphi\left(x\right)\neq\psi\left(x\right)$. 取不相交开区间 $I\ni\varphi\left(x\right)$, $J\ni\psi\left(x\right)$. 由**定义 3.14** (初始拓扑), $\operatorname{ev}_x^{-1}\left(I\right)$ 与 $\operatorname{ev}_x^{-1}\left(J\right)$ 是 $E^*$ 中不相交开集, 分别含 $\varphi,\psi$. 由**定义 3.10** (豪斯多夫空间), 弱星拓扑豪斯多夫. $\blacksquare$

### 习题廿一

设 $E$ 是 $\mathbb R$ 上赋范拓扑向量空间, $D\subset E$. 设 $E^*$ 装备由线性形式族 $\left\{\varphi_x:E^*\to\mathbb R\right\}_{x\in D}$ 诱导的初始拓扑. 证明该拓扑粗于 $E^*$ 上的弱星拓扑. 证明若 $D$ 在 $E$ 中稠密, 则在 $E^*$ 的所有 (对偶范数下) 有界集上, 该初始拓扑与弱星拓扑的限制相同.

### 解答 习题廿一

**粗于弱星拓扑**: 由**定义 6.31** (弱星拓扑), 弱星拓扑由全部 $x\in E$ 的赋值诱导. 本题初始拓扑仅用 $x\in D\subset E$. 映射更少, 由**定义 3.14** (初始拓扑) 的"最粗性", 用较少映射得到的拓扑粗于用全部映射得到的弱星拓扑.

**稠密 $D$ 时在有界集上相同**: 设 $B\subset E^*$ 有界, 即 $\sup_{\varphi\in B}\left\|\varphi\right\|<\infty$. 已知弱星 $\Rightarrow$ 初始方向 (上一问). 反之, 设网 $\left\{\varphi_\alpha\right\}\subset B$ 在初始拓扑下收敛到 $\varphi\in B$, 即对每个 $x\in D$, $\varphi_\alpha\left(x\right)\to\varphi\left(x\right)$. 任取 $y\in E$, 由 $D$ 稠密取 $x_n\in D\to y$. 对 $\epsilon>0$, 取 $x_n$ 使 $\left\|y-x_n\right\|<\epsilon/\left(\sup_B\left\|\varphi_\alpha\right\|+\sup_B\left\|\varphi\right\|+1\right)$. 则

$$
\left|\varphi_\alpha\left(y\right)-\varphi\left(y\right)\right|\le\left|\varphi_\alpha\left(y-x_n\right)\right|+\left|\varphi_\alpha\left(x_n\right)-\varphi\left(x_n\right)\right|+\left|\varphi\left(x_n-y\right)\right|.
$$

首末两项由有界性与 $\left\|y-x_n\right\|$ 控制, 中间项由 $\varphi_\alpha\left(x_n\right)\to\varphi\left(x_n\right)$ 控制. 故 $\varphi_\alpha\left(y\right)\to\varphi\left(y\right)$ 对一切 $y\in E$, 即在弱星拓扑下收敛. 故两拓扑在有界集上一致. $\blacksquare$
