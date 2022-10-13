# 作业 16

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.4** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>$X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基. (教材 $\S3$)

> **定义 3.14** (初始拓扑)<br>由映射族 $f_i:Y\to X_i$ 诱导的初始拓扑是使每个 $f_i$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.19** (子空间拓扑)<br>$A\subset X$ 上的子空间拓扑为 $T_A=\left\{U\cap A:U\in T_X\right\}$. (教材 $\S3$)

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

> **定理 3.6** (豪斯多夫的遗传性)<br>两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定理 5.1** (紧空间连续像紧)<br>紧空间的连续像紧. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>豪斯多夫空间中紧子集闭. (教材 $\S5$)

> **推论 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理 (正定性, 齐次, 三角不等式) 的 $\left\|\cdot\right\|$. (题集 $\S5$)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法与数乘都连续的拓扑. (题集 $\S5$)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$. (题集 $\S5$)

> **定义 6.28** (算子范数)<br>$L\left(E,F\right)$ 上 $\left\|T\right\|=\sup_{\left\|x\right\|\le 1}\left\|Tx\right\|$. (题集 $\S5$)

> **定义 6.30** (弱拓扑)<br>$E$ 上由全体连续线性泛函 $\varphi\in E^*$ 的拉回生成的初始拓扑. (题集 $\S5$)

> **定义 6.31** (弱星拓扑)<br>对偶 $E^*$ 上由赋值映射 $\left\{\varphi\mapsto\varphi\left(x\right)\right\}_{x\in E}$ 诱导的初始拓扑. (题集 $\S5$)

> **定义 6.32** (拓扑对偶)<br>$E^*=E$ 上全体连续线性泛函. (题集 $\S5$)

> **定理 6.50** (哈恩-巴拿赫定理)<br>赋范线性空间上, 点与不相交闭凸集可被连续线性泛函严格分离; 特别地 $E^*$ 分离 $E$ 的点. (题集 $\S5$)

> **定义 7.5** (单点紧化)<br>豪斯多夫局部紧空间 $X$ 的单点紧化 $X^*=X\cup\left\{\infty\right\}$, $\infty$ 的邻域为 $\left(X\setminus K\right)\cup\left\{\infty\right\}$, $K$ 跑遍紧子集. (教材 $\S7$)

> **定义 11.1** (商拓扑)<br>$U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开. (教材 $\S11$)

> **定义 11.2** (商映射)<br>满射 $\pi:X\to Y$ 使 $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. (教材 $\S11$)

> **定义 11.3** (等价关系粘合)<br>$X/{\sim}$ 配商拓扑, $\pi:X\to X/{\sim}$ 为典范投影. (教材 $\S11$)

> **定义 11.6** (锥)<br>$CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. (教材 $\S11$)

> **定义 11.11** (悬垂)<br>$SX=X\times\left[-1,1\right]/\left(X\times\left\{-1\right\}\cup X\times\left\{1\right\}\right)$, 两端各捏成一点. (题集 $\S5$)

> **定义 11.12** (塌缩商)<br>$X/\left\langle A\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 $\S5$)

> **定义 11.13** ($n$-维环面)<br>$T^n=\mathbb R^n/\mathbb Z^n\cong\left(S^1\right)^n$. (题集 $\S5$)

### 习题一

(悬垂) 设 $S^n=\left\{x\in\mathbb R^{n+1}:x_1^2+\cdots+x_{n+1}^2=1\right\}$. 证明悬垂 $S\left(S^n\right)$ 同胚于 $S^{n+1}$.

### 解答 习题一

由**定义 11.11** (悬垂), $S\left(S^n\right)=S^n\times\left[-1,1\right]/\left(S^n\times\left\{-1\right\}\cup S^n\times\left\{1\right\}\right)$, 这是**定义 11.3** (等价关系粘合) 意义下的商空间. 定义

$$
F:S^n\times\left[-1,1\right]\to S^{n+1}\subset\mathbb R^{n+1}\times\mathbb R,\quad F\left(u,t\right)=\left(\sqrt{1-t^2}\,u,t\right).
$$

验证: $\left\|\sqrt{1-t^2}\,u\right\|^2+t^2=\left(1-t^2\right)\left\|u\right\|^2+t^2=1$, 故像在 $S^{n+1}$ 上. $F$ 连续. $F\left(u,1\right)=\left(0,1\right)$ 对一切 $u$, $F\left(u,-1\right)=\left(0,-1\right)$ 对一切 $u$, 故两端被压成两点, $F$ 经由商映射分解为连续双射 $\overline F:S\left(S^n\right)\to S^{n+1}$.

紧性: $S^n$ 紧, $\left[-1,1\right]$ 紧, 由**定义 3.11** (乘积拓扑) 之乘积紧, 再由**定理 5.1** (紧空间连续像紧), $S\left(S^n\right)$ 紧. $S^{n+1}$ 是豪斯多夫的 ($\mathbb R^{n+2}$ 的子空间, 由**定理 3.6** (豪斯多夫的遗传性)). 由**推论 5.6** (紧豪斯多夫间的连续双射), $\overline F$ 是同胚. $\blacksquare$

### 习题二

(塌缩) 证明: 若 $A\subset X$ 是开 (或闭) 集, 则投影 $X\to X/\left\langle A\right\rangle$ 限制在 $X\setminus A$ 上是同胚. 证明 $CX/\left\langle X\right\rangle$ 与 $SX$ 同胚 (这里把 $X$ 等同于 $\pi\left(X\times\left\{0\right\}\right)\subset CX$).

### 解答 习题二

记 $\pi:X\to X/\left\langle A\right\rangle$ 为商投影, 见**定义 11.12** (塌缩商). $\pi|_{X\setminus A}:X\setminus A\to\pi\left(X\setminus A\right)$ 连续且为双射 ($X\setminus A$ 内任意两点不被粘合).

**$A$ 闭**: $X\setminus A$ 开. 任取 $U\subset X\setminus A$ 为子空间开集, 由**定义 3.19** (子空间拓扑) $U=V\cap\left(X\setminus A\right)$, $V$ 开于 $X$; 因 $X\setminus A$ 开, $U$ 开于 $X$. 又 $U\cap A=\emptyset$, 故 $\pi^{-1}\left(\pi\left(U\right)\right)=U$ 开. 由**定义 11.1** (商拓扑), $\pi\left(U\right)$ 开, 故 $\left(\pi|_{X\setminus A}\right)^{-1}$ 连续.

**$A$ 开**: 任取子空间开 $U=V\cap\left(X\setminus A\right)$, $V$ 开. 令 $W=V\cup A$. 由 $A$ 开, $W$ 开于 $X$. 而 $\pi^{-1}\left(\pi\left(W\right)\right)=W\cup A=W$ (因 $A$ 已被捏合), 故 $\pi\left(W\right)$ 商开. 且 $\pi\left(W\right)\cap\pi\left(X\setminus A\right)=\pi\left(V\cap\left(X\setminus A\right)\right)=\pi\left(U\right)$. 故 $\pi\left(U\right)$ 是商开集与 $\pi\left(X\setminus A\right)$ 的交, 即子空间开. 逆连续. 由**定义 3.4** (同胚), 限制为同胚.

**$CX/\left\langle X\right\rangle\cong SX$**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 在 $CX$ 中再把 $\pi\left(X\times\left\{0\right\}\right)$ 捏成一点, 等价于在 $X\times\left[0,1\right]$ 上把 $X\times\left\{0\right\}$ 与 $X\times\left\{1\right\}$ 各捏成一点. 这正是**定义 11.11** (悬垂) 中的 $SX$ (经 $t\mapsto 2t-1$ 把 $\left[0,1\right]$ 线性映到 $\left[-1,1\right]$). $\blacksquare$

### 习题三

设 $X$ 是紧豪斯多夫空间. 证明锥空间 $CX$ 同胚于 $X\times\left[0,1\right)$ 的单点紧化. 若 $A\subset X$ 闭, 证明 $X/\left\langle A\right\rangle$ 同胚于 $X\setminus A$ 的单点紧化.

### 解答 习题三

**第一问**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 空间 $X\times\left[0,1\right)$ 是豪斯多夫局部紧的 (由**定理 3.6** (豪斯多夫的遗传性), $X$ 豪斯多夫, $\left[0,1\right)$ 局部紧). 因 $X$ 紧, $X$ 的紧子集皆闭, 由**定理 5.5** (豪斯多夫中紧集闭), $X$ 的闭子集皆紧. 由**定义 7.5** (单点紧化), 其单点紧化为 $\left(X\times\left[0,1\right)\right)^*=X\times\left[0,1\right)\cup\left\{\infty\right\}$.

构造双射 $\psi:CX\to\left(X\times\left[0,1\right)\right)^*$: 把 $\left[\left(x,t\right)\right]$ ($t<1$) 映到 $\left(x,t\right)$, 把被捏合点 $\left[\left(x,1\right)\right]$ 映到 $\infty$. 它连续: $CX$ 中开集在 $t<1$ 部分对应 $X\times\left[0,1\right)$ 中开集; 含被捏合点的开集对应于含 $X\times\left\{1\right\}$ 的饱和开集, 其补集在 $X\times\left[0,1\right)$ 中是紧的 (因 $X$ 紧, 投影到 $t$ 方向远离 $1$), 故对应于 $\infty$ 的标准邻域. $CX$ 紧 (连续像 $X\times\left[0,1\right]$), $\left(X\times\left[0,1\right)\right)^*$ 豪斯多夫. 由**推论 5.6** (紧豪斯多夫间的连续双射), $\psi$ 是同胚.

**第二问**: $A$ 闭于紧豪斯多夫 $X$. 由**定义 11.12** (塌缩商), $X/\left\langle A\right\rangle$ 将 $A$ 捏成一点. $X\setminus A$ 是局部紧豪斯多夫 (开子集). 类似构造: $X/\left\langle A\right\rangle\setminus\left\{\pi\left(A\right)\right\}\cong X\setminus A$, 且 $\pi\left(A\right)$ 的邻域恰为 $\left(X\setminus A\right)\setminus K$ 加 $\pi\left(A\right)$, $K$ 跑遍 $X\setminus A$ 的紧子集. $X/\left\langle A\right\rangle$ 紧, 单点紧化豪斯多夫, 由**推论 5.6** (紧豪斯多夫间的连续双射) 二者同胚. $\blacksquare$

### 习题四

($n$-维环面) 设 $T^n=\mathbb R^n/\mathbb Z^n$, 映射

$$
\phi:\left[\left(t_1,\dots,t_n\right)\right]\mapsto\left(e^{2\pi i t_1},\dots,e^{2\pi i t_n}\right).
$$

(1) 证明 $\phi$ 连续;

(2) 证明 $T^n$ 豪斯多夫;

(3) 证明 $\phi$ 是同胚.

### 解答 习题四

**第 1 小题**: 由**定义 11.13** ($n$-维环面), $\mathbb R^n\to\left(S^1\right)^n$ 的映射 $F\left(t\right)=\left(e^{2\pi i t_1},\dots,e^{2\pi i t_n}\right)$ 连续, 且在 $\mathbb Z^n$ 陪集上取等值. 由**定义 11.2** (商映射), $F$ 经由商映射分解为连续 $\phi:T^n\to\left(S^1\right)^n$.

**第 2 小题**: $T^n$ 是豪斯多夫的: 下一问证 $\phi$ 是到 $\left(S^1\right)^n$ 的同胚, 而 $\left(S^1\right)^n$ 由**定理 3.6** (豪斯多夫的遗传性) 是豪斯多夫的, 故 $T^n$ 豪斯多夫.

**第 3 小题**: $\phi$ 是双射: $\left(e^{2\pi i t_1},\dots\right)$ 的原像陪集唯一. $T^n$ 紧: 它是 $n$ 方体 $\left[0,1\right]^n$ 的商, 由**定理 5.1** (紧空间连续像紧) 紧. $\left(S^1\right)^n$ 豪斯多夫. 由**推论 5.6** (紧豪斯多夫间的连续双射), $\phi$ 是同胚. $\blacksquare$

### 习题五

设 $E$ 是 $\mathbb K$ 上拓扑向量空间, $C$ 是 $0$ 的凸邻域, 规范函数 $\left\|\cdot\right\|_C:E\to\left[0,\infty\right)$ 由**定义 6.27** (规范函数) 给出. 若 $\left\{C_\alpha\right\}_{\alpha\in A}$ 是 $E$ 中一族凸集且其交是 $0$ 的凸邻域, 证明

$$
\left\|\cdot\right\|_{\bigcap_{\alpha\in A}C_\alpha}=\sup_{\alpha\in A}\left\|\cdot\right\|_{C_\alpha}.
$$

### 解答 习题五

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

### 习题六

设 $E,F,G$ 是赋范域 $\mathbb K$ 上的拓扑向量空间. 对 $f\in L\left(E,F\right)$, 右复合映射 $R_f:L\left(F,G\right)\to L\left(E,G\right)$, $g\mapsto g\circ f$. 证明 $R_f$ 的算子范数不超过 $f$ 的算子范数; 左复合同理. 证明映射 $E\to L\left(\mathbb K,E\right)$, $x\mapsto\left(\varphi_x:t\mapsto tx\right)$ 是等距线性同构.

### 解答 习题六

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

### 习题七

证明: 若 $E$ 是无穷维拓扑向量空间, 则 $E$ 上强拓扑与弱拓扑不同. 计算弱拓扑下 $E$ 的开单位球的内部; 计算弱拓扑下 $E$ 的单位球面的闭包.

### 解答 习题七

由**定义 6.30** (弱拓扑), 弱拓扑是由 $E^*$ 中全体连续线性泛函诱导的初始拓扑. 由**定理 6.50** (哈恩-巴拿赫定理), $E^*$ 分离 $E$ 的点. 弱拓扑的基本邻域形如

$$
U\left(x_0;\varphi_1,\dots,\varphi_n;\varepsilon\right)=\left\{x:\left|\varphi_i\left(x-x_0\right)\right|<\varepsilon,\ i=1,\dots,n\right\}.
$$

它是 $x_0$ 加上有限个超平面交 (即无穷维仿射子空间) 的 $\varepsilon$-管.

**强 $\neq$ 弱**: 在无穷维, 任意弱开邻域 $U$ 都含一个无穷维仿射子空间, 故不可能含于一个强有界集; 特别地强开单位球不是弱开的. 故弱拓扑严格粗于强拓扑.

**开单位球的弱内部**: 弱开邻域含无穷维仿射子空间, 因而其中有无界点, 不可能含于有界开单位球. 故弱拓扑下开单位球的内部为 $\emptyset$.

**单位球面的弱闭包**: 由**定理 6.50** (哈恩-巴拿赫定理), 任意 $x_0$ 满足 $\left\|x_0\right\|\le 1$ 都可被球面中点弱逼近: 若 $\left\|x_0\right\|<1$, 沿任意方向取小步长即可进入球面; 若 $\left\|x_0\right\|=1$, $x_0$ 本身在球面上. 反之弱闭包不能超出闭单位球 (范数是弱下半连续的). 故弱闭包等于闭单位球 $\left\{x:\left\|x\right\|\le 1\right\}$. $\blacksquare$

### 习题八

证明弱星拓扑总是豪斯多夫的.

### 解答 习题八

由**定义 6.31** (弱星拓扑), $E^*$ 上的弱星拓扑是由赋值映射 $\operatorname{ev}_x:E^*\to\mathbb R$, $\operatorname{ev}_x\left(\varphi\right)=\varphi\left(x\right)$, $x\in E$, 诱导的初始拓扑. 由**定义 3.3** (连续映射), $\operatorname{ev}_x$ 连续. 任取 $\varphi,\psi\in E^*$, $\varphi\neq\psi$. 由**定义 6.32** (拓扑对偶) 二者为连续线性泛函, 存在 $x\in E$ 使 $\varphi\left(x\right)\neq\psi\left(x\right)$. 取不相交开区间 $I\ni\varphi\left(x\right)$, $J\ni\psi\left(x\right)$. 由**定义 3.14** (初始拓扑), $\operatorname{ev}_x^{-1}\left(I\right)$ 与 $\operatorname{ev}_x^{-1}\left(J\right)$ 是 $E^*$ 中不相交开集, 分别含 $\varphi,\psi$. 由**定义 3.10** (豪斯多夫空间), 弱星拓扑豪斯多夫. $\blacksquare$

### 习题九

设 $E$ 是 $\mathbb R$ 上赋范拓扑向量空间, $D\subset E$. 设 $E^*$ 装备由线性形式族 $\left\{\varphi_x:E^*\to\mathbb R\right\}_{x\in D}$ 诱导的初始拓扑. 证明该拓扑粗于 $E^*$ 上的弱星拓扑. 证明若 $D$ 在 $E$ 中稠密, 则在 $E^*$ 的所有 (对偶范数下) 有界集上, 该初始拓扑与弱星拓扑的限制相同.

### 解答 习题九

**粗于弱星拓扑**: 由**定义 6.31** (弱星拓扑), 弱星拓扑由全部 $x\in E$ 的赋值诱导. 本题初始拓扑仅用 $x\in D\subset E$. 映射更少, 由**定义 3.14** (初始拓扑) 的"最粗性", 用较少映射得到的拓扑粗于用全部映射得到的弱星拓扑.

**稠密 $D$ 时在有界集上相同**: 设 $B\subset E^*$ 有界, 即 $\sup_{\varphi\in B}\left\|\varphi\right\|<\infty$. 已知弱星 $\Rightarrow$ 初始方向 (上一问). 反之, 设网 $\left\{\varphi_\alpha\right\}\subset B$ 在初始拓扑下收敛到 $\varphi\in B$, 即对每个 $x\in D$, $\varphi_\alpha\left(x\right)\to\varphi\left(x\right)$. 任取 $y\in E$, 由 $D$ 稠密取 $x_n\in D\to y$. 对 $\varepsilon>0$, 取 $x_n$ 使 $\left\|y-x_n\right\|<\varepsilon/\left(\sup_B\left\|\varphi_\alpha\right\|+\sup_B\left\|\varphi\right\|+1\right)$. 则

$$
\left|\varphi_\alpha\left(y\right)-\varphi\left(y\right)\right|\le\left|\varphi_\alpha\left(y-x_n\right)\right|+\left|\varphi_\alpha\left(x_n\right)-\varphi\left(x_n\right)\right|+\left|\varphi\left(x_n-y\right)\right|.
$$

首末两项由有界性与 $\left\|y-x_n\right\|$ 控制, 中间项由 $\varphi_\alpha\left(x_n\right)\to\varphi\left(x_n\right)$ 控制. 故 $\varphi_\alpha\left(y\right)\to\varphi\left(y\right)$ 对一切 $y\in E$, 即在弱星拓扑下收敛. 故两拓扑在有界集上一致. $\blacksquare$
