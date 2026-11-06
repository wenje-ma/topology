# week4

> **定理 2.8 (施罗德-伯恩斯坦定理)**
> 
> 若同时存在 $X\to{Y}$ 与 $Y\to{X}$ 的单射, 则 $X$ 与 $Y$ 基数相等. (教材 §2)

> **定理 2.13 (实数与自然数幂集等势)**
> 
> $\left|\mathbb{R}\right|=\left|\mathcal{P}\left(\mathbb{N}\right)\right|$. (教材 §2)

> **定理 3.1 (复合连续)**
> 
> 两个连续映射的复合连续. (教材 $\S3$)

> **定理 3.6 (豪斯多夫的遗传性)**
> 
> 两豪斯多夫空间之乘积仍豪斯多夫; 豪斯多夫空间的子空间仍豪斯多夫. (教材 $\S3$)

> **定义 3.9 (可分)**
> 
> 称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10 (豪斯多夫空间)**
> 
> 称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$, p20)

> **定义 3.11 (乘积拓扑)**
> 
> 设 $X,Y$ 为拓扑空间. $X\times{Y}$ 上的乘积拓扑以形如 $U\times{V}$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集; 任意乘积 $\prod_{v\in{V}}X_v$ 同理. 坐标投影是连续的. (教材 $\S3$, p17)

> **定义 3.15 (拓扑基)**
> 
> 设 $\mathcal{B}\subset\mathcal{P}\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal{B}}B$, 且对任意 $B_1,B_2\in\mathcal{B}$ 与任意 $x\in{B}_1\cap{B}_2$ 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_1\cap{B}_2$, 则以 $\mathcal{B}$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$, p13)

> **定义 3.16 (离散拓扑与平凡拓扑)**
> 
> 离散拓扑: $X$ 的所有子集都开; 平凡拓扑: 仅 $\emptyset,X$ 开. (教材 §3)

> **定义 3.18 (拓扑空间)**
> 
> 拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal{P}\left(X\right)$. 即 $U\subset{X}$ 是开的当且仅当 $U\in{T}$. 我们要求:
> 
> (1) $\emptyset,X\in{T}$;
> 
> (2) 若 $U,V\in{T}$, 则 $U\cap{V}\in{T}$;
> 
> (3) 若 $A\subset{T}$, 则 $\bigcup{A}\in{T}$. (教材 $\S3$, p12)

> **定义 3.19 (子空间拓扑)**
> 
> 设 $\left(X,\mathcal{O}_X\right)$ 为拓扑空间, $A\subset{X}$, $\iota:A\to{X}$ 为包含映射. 称 $U\subset{A}$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap{A}$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 §3, p17; 题集 §1.2)

> **定义 3.20 (边界)**
> 
> $\partial{A}=\overline{A}\setminus\operatorname{int}\left(A\right)$. 等价地, $\partial{F}=F\cap\overline{E\setminus{F}}$ 当 $F\subset{E}$ 闭. (教材 §3)

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

> **定义 3.26 (闭包)**
> 
> 集合 $A\subset{X}$ 的闭包 $\overline{A}$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$, p18)

> **定义 3.27 (余可数拓扑)**
> 
> 称 $X$ 上的余可数拓扑为: 非空开集恰为可数集的补集. (题集 §1.4)

> **定义 3.28 (扎里斯基拓扑)**
> 
> 设 $K$ 为域, $\mathbb{A}^n\left(K\right)=K^n$. 扎里斯基闭集是一族多项式 $\left(P_i\right)_{i\in{I}}$ 的公共零点集 $\left\{x\in\mathbb{A}^n\left(K\right):\forall{i}\in{I},P_i\left(x\right)=0\right\}$. (题集 $\S1.4$)

> **定义 3.30 (基本邻域系)**
> 
> $x$ 的邻域族 $\mathcal{P}$, 使 $x$ 的每个邻域都含某个 $\mathcal{P}$ 中元素. (题集 §2.4)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 4.1 (区间连通)**
> 
> $\left[0,1\right]$ 连通; 由此任意区间连通. (教材 §4, p23; 《拓扑学》(原书第2版) §24 推论 24.2)

> **定理 4.2 (连续像连通)**
> 
> $X$ 连通, $f:X\to{Y}$ 连续, 则 $f\left(X\right)$ 连通. (教材 §4, p23)

> **定理 4.3 (路径连通蕴含连通)**
> 
> 路径连通空间是连通的. (教材 §4, p24)

> **定理 4.5 (可数度量空间完全不连通)**
> 
> 每个可数度量空间都是完全不连通的. (教材 §4, p25)

> **定理 4.6 (扇形连通)**
> 
> 一族两两有公共点的连通集之并连通; 更一般地, 一个连通集与一族每个都和它相交的连通集之并连通. (教材 §4, p26)

> **定理 4.7 (乘积连通)**
> 
> 连通集 $A,B$ 之积 $A\times{B}$ 连通; 有限个连通集的乘积连通. (教材 §4, p26 推论 4.7)

> **定义 4.8 (连通分支)**
> 
> 含点 $x$ 的唯一极大连通集 $A\left(x\right)$; 它是闭集; 分支数有限时分支开. (教材 §4, p27)

> **定义 4.10 (局部路径连通)**
> 
> 每点有由路径连通邻域组成的邻域基. (题集 §2.1 Q3)

> **定义 4.14 ($\varepsilon$-链空间)**
> 
> $X$ 是 $\varepsilon$-链的, 若任意 $a,b\in{X}$ 可由相邻距离 $<\varepsilon$ 的有限点列连接; 对一切 $\varepsilon>0$ 都成立称全链. (题集 §4.5 C5)

> **定理 4.15 (闭包保持连通性)**
> 
> 连通集的闭包仍连通. (教材 §4, p27)

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

> **定义 4.23 (凸集)**
> 
> $K\subset\mathbb{R}^n$ 凸即 $x,y\in{K}$ 蕴含线段 $\left(1-t\right)x+ty$ ($t\in\left[0,1\right]$) 全在 $K$ 中; 凸集必路径连通, 路径连通蕴含连通. (教材 §4, p24)

> **定义 4.24 (拓扑学家正弦曲线)**
> 
> $y=\sin\left(1/x\right)$ 在 $\left(0,1\right]$ 上的图像与 $y$ 轴上 $\left[-1,1\right]$ 的并; 它连通但不路径连通. (教材 §4, p24)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.4 (闭子集紧)**
> 
> 若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset{X}$ 也紧致. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; 《基础拓扑学》(修订版) 第3章 定理(3.7))

> **定理 5.7 (有限乘积紧)**
> 
> 有限个紧空间的乘积紧. (教材 $\S5$, 定理 5.7)

> **定理 6.1 (紧 $=$ 序列紧)**
> 
> 度量空间中紧致与序列紧致等价, 即每个序列都有收敛子列. (教材 $\S6$)

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

> **定义 6.44 (伪距离)**
> 
> 满足除 "$d\left(x,y\right)=0\Rightarrow{x}=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 §1.3; 题集 §3.2 Q3; 题集 §5 Q5)

> **定义 6.46 (点到集合的距离)**
> 
> $d\left(x,A\right)=\inf_{a\in{A}}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.47 ($\varepsilon$-邻域)**
> 
> $U_\varepsilon\left(A\right)=\left\{x\in{X}:d\left(x,A\right)<\varepsilon\right\}$. (题集 $\S3.2$)

> **定理 7.2 (乌雷松引理)**
> 
> 正规空间中不相交闭集可被连续函数分离. (题集 §6 C13)

> **定义 7.6 (正规空间)**
> 
> 单点闭且任意两不相交闭集可被不相交开集分离, 即 $T_4$. (教材 §7, p42)

> **定义 11.1 (商拓扑)**
> 
> 满射 $\pi:X\to{Y}$ 下, $U\subset{Y}$ 开当且仅当 $\pi^{-1}\left(U\right)\subset{X}$ 开. (教材 §11, p61; 《拓扑学》(原书第2版) §22, p105; 《基础拓扑学》(修订版) 第4章 4.2, p55)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to{Y}$ 使 $U\subset{Y}$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to{Z}$ 连续当且仅当 $gf:X\to{Z}$ 连续. (教材 §11, p61; 《基础拓扑学》(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定义 11.3 (等价关系粘合)**
> 
> $X/{\sim}$ 配商拓扑, $\pi:X\to{X}/{\sim}$ 为典范投影; 即将每个等价类黏合成一点. (教材 §11, p61; 《拓扑学》(原书第2版) §22, p106)

> **定义 11.6 (锥)**
> 
> 从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in{X}$, $0\le{t}<1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (教材 $\S11$, p63; 题集 $\S5$ Q9; 《基础拓扑学》(修订版) 第4章)

> **定义 11.7 (环面)**
> 
> 正方形对边同向粘合所得 $S^1\times{S}^1$, 即 $\mathbb{R}^2/\mathbb{Z}^2$. (《基础拓扑学》(修订版) 第4章 4.2, p56; 教材 §11, p64)

> **定义 11.11 (悬垂)**
> 
> $SX=X\times\left[-1,1\right]/\left(X\times\left\{-1\right\}\cup{X}\times\left\{1\right\}\right)$, 两端各捏成一点. (题集 §5 Q10)

> **定义 11.12 (塌缩商)**
> 
> $X/\left\langle{A}\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 §5 Q11; 《基础拓扑学》(修订版) 第4章, p57)

> **定义 11.13 ($n$-维环面)**
> 
> $T^n=\mathbb{R}^n/\mathbb{Z}^n\cong\left(S^1\right)^n$. (题集 §5 Q13; 教材 §11, p65)

> **定义 11.14 (最终拓扑)**
> 
> 关于一族映射 $f_i:X_i\to{Y}$ 使每个 $f_i$ 连续的最细拓扑; $U\subset{Y}$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 §1.4 C6; 题集 §5 Q1-Q2)

> **定义 11.15 (等价关系的生成)**
> 
> 包含给定二元关系 $R$ 的最小等价关系, 即全体含 $R$ 的等价关系之交. (题集 §5 Q4)

> **定义 11.18 (不交和拓扑)**
> 
> 一族拓扑空间 $\left\{X_i\right\}_{i\in{I}}$ 的不交和 $\coprod_{i\in{I}}X_i$ 上, $U$ 开当且仅当每个 $U\cap{X}_i$ 在 $X_i$ 中开. (题集 §5 Q1; 《基础拓扑学》(修订版) 第4章 定理(4.7), p58)

> **定理 24.3 (介值定理)**
> 
> 设 $f:X\to{Y}$ 连续, $X$ 连通, $Y$ 为序拓扑全序集; 若 $r$ 介于 $f\left(a\right)$ 与 $f\left(b\right)$ 之间, 则存在 $c\in{X}$ 使 $f\left(c\right)=r$. 特别地, 连续函数在区间上取到中间值. (《拓扑学》(原书第2版) §24 定理 24.3, p118)

## 4.1 (环面上有理斜率与无理斜率直线的像)

设 $\pi:\mathbb{R}^2\to{T}^2$ 是典范投影, $\alpha\in\mathbb{R}\cup\left\{\infty\right\}$, $D$ 是 $\mathbb{R}^2$ 中斜率为 $\alpha$ 的直线. 证明: 若 $\alpha\in\mathbb{Q}\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 同胚于一个圆; 若 $\alpha\notin\mathbb{Q}\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 在 $T^2$ 中稠密, 且 $\pi|_D$ 是 $D$ 到 $\pi\left(D\right)$ 的连续双射.

### 解答 2.17

由**定义 11.7 (环面)**, $T^2=\mathbb{R}^2/\mathbb{Z}^2$, $\pi$ 为商投影. 不妨取 $D=\left\{\left(t,\alpha{t}\right):t\in\mathbb{R}\right\}$ (竖直直线 $\alpha=\infty$ 同理).

有理斜率: 设 $\alpha=p/q$, $p,q\in\mathbb{Z}$, $\gcd\left(p,q\right)=1$. 映射 $g:\mathbb{R}/q\mathbb{Z}\to{T}^2$, $g\left(t\right)=\pi\left(t,\alpha{t}\right)$. 它良定义且连续 (由**定义 11.2 (粘合映射)**, $\mathbb{R}/q\mathbb{Z}$ 上的映射经由商投影分解). 它是单射: 若 $\pi\left(t,\alpha{t}\right)=\pi\left(t',\alpha{t}'\right)$, 则 $t-t'\in\mathbb{Z}$ 且 $p\left(t-t'\right)/q\in\mathbb{Z}$, 即 $q\mid{p}\left(t-t'\right)$; 由 $\gcd\left(p,q\right)=1$, $q\mid{t}-t'$, 即在 $\mathbb{R}/q\mathbb{Z}$ 中相等. $\mathbb{R}/q\mathbb{Z}$ 是紧圆 (同胚于 $S^1$), $T^2$ 是豪斯多夫的 (由**定义 11.7 (环面)** $T^2\cong{S}^1\times{S}^1$, 而 $S^1$ 是 $\mathbb{R}^2$ 的子空间故豪斯多夫, 由**定理 3.6 (豪斯多夫的遗传性)** 乘积仍豪斯多夫). 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $g$ 是同胚. 故 $\pi\left(D\right)=g\left(\mathbb{R}/q\mathbb{Z}\right)$ 同胚于圆.

无理斜率: 设 $\alpha\notin\mathbb{Q}$. 先证 $\pi\left(D\right)$ 在 $T^2$ 中稠密. 记 $H=\pi\left(D\right)=\left\{\pi\left(t,\alpha{t}\right):t\in\mathbb{R}\right\}\subset{T}^2$. 由狄利克雷逼近, 对任意 $\varepsilon>0$ 存在非零整数 $m$ 使 $\left\|m\alpha\right\|<\varepsilon$ (到最近整数距离), 即 $\pi\left(m,m\alpha\right)$ 离 $\left(0,0\right)\in{T}^2$ 任意近. $H$ 中含任意接近单位元的非零点. 而 $H$ 在第一坐标上的投影 $t\mapsto{t}\pmod1$ 是满射到 $S^1$ (因 $t$ 取遍 $\mathbb{R}$), 结合第二坐标 $t\mapsto\alpha{t}\pmod1$ 的无理旋转 (稠密), 即得 $H$ 在 $T^2$ 中稠密.

$\pi|_D:D\to\pi\left(D\right)$ 连续 (它是商映射 $\pi$ 在子空间 $D$ 上的限制, 由**定义 3.19 (子空间拓扑)** 连续). 它是双射: 若 $\pi\left(t,\alpha{t}\right)=\pi\left(t',\alpha{t}'\right)$, 则 $t-t'\in\mathbb{Z}$ 且 $\alpha\left(t-t'\right)\in\mathbb{Z}$, 由 $\alpha$ 无理必有 $t-t'=0$. $\blacksquare$

## 4.2 (环面按稠密子群粘合：豪斯多夫当且仅当斜率为有理数)

设 $\pi:\mathbb{R}^2\to{T}^2$ 是典范投影, $\alpha\in\mathbb{R}\cup\left\{\infty\right\}$. 在 $T^2$ 上定义关系: $x'\sim{y}'$ 当且仅当存在 $x,y\in\mathbb{R}^2$ 与斜率为 $\alpha$ 的直线使 $\pi\left(x\right)=x'$, $\pi\left(y\right)=y'$. 证明 $\sim$ 是等价关系; 证明商空间 $T^2/{\sim}$ 豪斯多夫当且仅当 $\alpha\in\mathbb{Q}$, 此时商空间同胚于一个圆; 若 $\alpha\notin\mathbb{Q}$, 证明商空间 $T^2/{\sim}$ 具有平凡拓扑.

### 解答 2.18

把 $\pi\left(D\right)$ 记为 $H\subset{T}^2$, 其中 $D=\left\{\left(t,\alpha{t}\right)\right\}$. 关系 $x'\sim{y}'$ 即 $y'-x'\in{H}$ ($T^2$ 中的群运算).

等价关系: $H$ 是 $T^2$ 的子群: 含单位元; 对减法封闭. 故按子群取陪集是等价关系: 自反 ($0\in{H}$), 对称 ($H$ 对逆元封闭), 传递 ($H$ 对加法封闭). 由**定义 11.3 (等价关系粘合)**, $T^2/{\sim}=T^2/H$.

有理斜率: 设 $\alpha=p/q\in\mathbb{Q}$. 由习题 2.17, $H=\pi\left(D\right)$ 同胚于一个圆, 故 $H$ 紧; 又 $T^2$ 豪斯多夫 (见习题 2.17), 由**定理 5.5 (豪斯多夫中紧集闭)**, $H$ 是 $T^2$ 中的闭子群. 定义

$$
\varphi:T^2\to{S}^1,\quad\varphi\left(u,v\right)=qu-pv\pmod1.
$$

$\varphi$ 连续, 其核恰为 $H$ (即 $\varphi\left(u,v\right)=0\Leftrightarrow\left(u,v\right)\in{H}$). 由**定义 11.2 (粘合映射)** 的泛性质, $\varphi$ 诱导连续双射 $\overline\varphi:T^2/H\to{S}^1$. $T^2/H$ 紧 ($T^2$ 紧, 由**定理 5.1 (紧空间连续像紧)** 商连续像紧), $S^1$ 豪斯多夫. 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $\overline\varphi$ 是同胚. 故 $T^2/H$ 同胚于圆, 且圆豪斯多夫, 由**定义 3.10 (豪斯多夫空间)** 商空间豪斯多夫.

无理斜率: 由习题 2.17, $H$ 在 $T^2$ 中稠密. 商拓扑下, 由**定义 11.1 (商拓扑)**, 开集 $U\subset{T}^2/H$ 对应于 $T^2$ 中的 $H$-饱和开集. 若 $U$ 非空, 取饱和开集 $V\subset{T}^2$, $V\neq\emptyset$. 因 $H$ 稠密, $V+H=T^2$; 而 $V$ 已饱和, $V+H=V$, 故 $V=T^2$, 即 $U=T^2/H$. 故仅有的开集是 $\emptyset$ 与全空间, 即平凡拓扑. 此时商空间不豪斯多夫 (除非单点), 与有理情形对照. $\blacksquare$

## 4.3 (锥空间的嵌入与函子性)

(锥) 设 $CX$ 是 $X$ 上的锥空间, 为 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 证明: 映射 $X\to{C}X$, $x\mapsto\left[\left(x,0\right)\right]$ 是到其像的同胚, 从而 $X$ 可视为 $CX$ 的子集. 证明: 若 $f:X\to{Y}$ 连续, 则 $Cf:CX\to{C}Y$, $\left[\left(x,t\right)\right]\mapsto\left[\left(f\left(x\right),t\right)\right]$ 连续.

### 解答 2.19

嵌入: 由**定义 11.6 (锥)**, $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 记 $\pi:X\times\left[0,1\right]\to{C}X$ 为商投影, $j:X\to{C}X$, $j\left(x\right)=\left[\left(x,0\right)\right]$. 因 $X\times\left\{0\right\}$ 与被捏合集 $X\times\left\{1\right\}$ 不相交, $\pi$ 在 $X\times\left\{0\right\}$ 上是单射, 故 $j$ 是双射到 $j\left(X\right)$.

$j$ 连续: 它是含入 $X\cong{X}\times\left\{0\right\}\hookrightarrow{X}\times\left[0,1\right]$ 与 $\pi$ 的复合, 由**定理 3.1 (复合连续)** 连续.

逆连续: 任取 $X$ 中开集 $U$. 需证 $j\left(U\right)$ 是 $j\left(X\right)$ (子空间) 中的开集. 构造 $V=U\times\left[0,1/2\right)\subset{X}\times\left[0,1\right]$. 由**定义 3.11 (乘积拓扑)**, $V$ 开. 它不与 $X\times\left\{1\right\}$ 相交, 故饱和 (与等价类只交整体不交), 由**定义 11.1 (商拓扑)**, $\pi\left(V\right)$ 在 $CX$ 中开. 而 $\pi\left(V\right)\cap{j}\left(X\right)=j\left(U\right)$. 故 $j\left(U\right)$ 是 $CX$ 的开集与 $j\left(X\right)$ 的交, 即 $j\left(X\right)$ 中的开集. 由**定义 3.23 (同胚)**, $j$ 是 $X$ 到 $j\left(X\right)$ 的同胚.

$Cf$ 连续: 由**定义 11.2 (粘合映射)**, 只需证对任意开集 $W\subset{C}Y$, $\left(Cf\right)^{-1}\left(W\right)$ 在 $CX$ 中开, 即 $\pi_X^{-1}\left(\left(Cf\right)^{-1}\left(W\right)\right)$ 在 $X\times\left[0,1\right]$ 中开. 该原像等于

$$
\left\{\left(x,t\right):\left(f\left(x\right),t\right)\in\pi_Y^{-1}\left(W\right)\right\}=\left(f\times\operatorname{id}\right)^{-1}\left(\pi_Y^{-1}\left(W\right)\right).
$$

$\pi_Y^{-1}\left(W\right)$ 在 $Y\times\left[0,1\right]$ 中开, $f\times\operatorname{id}$ 连续 (由 $f$ 连续与 $\operatorname{id}$ 连续, 乘积映射连续), 故由**定义 3.22 (连续映射)**, 上式在 $X\times\left[0,1\right]$ 中开. 故 $Cf$ 连续. $\blacksquare$

## 4.4 (悬垂把 $S^n$ 抬高一维)

(悬垂) 设 $S^n=\left\{x\in\mathbb{R}^{n+1}:x_1^2+\cdots+x_{n+1}^2=1\right\}$. 证明悬垂 $S\left(S^n\right)$ 同胚于 $S^{n+1}$.

### 解答 2.20

由**定义 11.11 (悬垂)**, $S\left(S^n\right)=S^n\times\left[-1,1\right]/\left(S^n\times\left\{-1\right\}\cup{S}^n\times\left\{1\right\}\right)$, 这是**定义 11.3 (等价关系粘合)** 意义下的商空间. 定义

$$
F:S^n\times\left[-1,1\right]\to{S}^{n+1}\subset\mathbb{R}^{n+1}\times\mathbb{R},\quad{F}\left(u,t\right)=\left(\sqrt{1-t^2}\,u,t\right).
$$

验证: $\left\|\sqrt{1-t^2}\,u\right\|^2+t^2=\left(1-t^2\right)\left\|u\right\|^2+t^2=1$, 故像在 $S^{n+1}$ 上. $F$ 连续. $F\left(u,1\right)=\left(0,1\right)$ 对一切 $u$, $F\left(u,-1\right)=\left(0,-1\right)$ 对一切 $u$, 故两端被压成两点, $F$ 经由商映射分解为连续双射 $\overline{F}:S\left(S^n\right)\to{S}^{n+1}$.

紧性: $S^n$ 是 $\mathbb{R}^{n+1}$ 的有界闭子集故紧, $\left[-1,1\right]$ 紧, 由**定理 5.7 (有限乘积紧)**, $S^n\times\left[-1,1\right]$ 紧; 再由**定理 5.1 (紧空间连续像紧)**, $S\left(S^n\right)$ 紧. $S^{n+1}$ 是豪斯多夫的 ($\mathbb{R}^{n+2}$ 的子空间, 由**定理 3.6 (豪斯多夫的遗传性)**). 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $\overline{F}$ 是同胚. $\blacksquare$

## 4.5 (塌缩商限制在余集上是同胚，锥商同胚于悬垂)

(塌缩) 证明: 若 $A\subset{X}$ 是开 (或闭) 集, 则投影 $X\to{X}/\left\langle{A}\right\rangle$ 限制在 $X\setminus{A}$ 上是同胚. 证明 $CX/\left\langle{X}\right\rangle$ 与 $SX$ 同胚 (这里把 $X$ 等同于 $\pi\left(X\times\left\{0\right\}\right)\subset{C}X$).

### 解答 2.21

记 $\pi:X\to{X}/\left\langle{A}\right\rangle$ 为商投影, 见**定义 11.12 (塌缩商)**. $\pi|_{X\setminus{A}}:X\setminus{A}\to\pi\left(X\setminus{A}\right)$ 连续且为双射 ($X\setminus{A}$ 内任意两点不被粘合).

$A$ 闭: $X\setminus{A}$ 开. 任取 $U\subset{X}\setminus{A}$ 为子空间开集, 由**定义 3.19 (子空间拓扑)** $U=V\cap\left(X\setminus{A}\right)$, $V$ 开于 $X$; 因 $X\setminus{A}$ 开, $U$ 开于 $X$. 又 $U\cap{A}=\emptyset$, 故 $\pi^{-1}\left(\pi\left(U\right)\right)=U$ 开. 由**定义 11.1 (商拓扑)**, $\pi\left(U\right)$ 开, 故 $\left(\pi|_{X\setminus{A}}\right)^{-1}$ 连续.

$A$ 开: 任取子空间开 $U=V\cap\left(X\setminus{A}\right)$, $V$ 开. 令 $W=V\cup{A}$. 由 $A$ 开, $W$ 开于 $X$. 而 $\pi^{-1}\left(\pi\left(W\right)\right)=W\cup{A}=W$ (因 $A$ 已被捏合), 故 $\pi\left(W\right)$ 商开. 且 $\pi\left(W\right)\cap\pi\left(X\setminus{A}\right)=\pi\left(V\cap\left(X\setminus{A}\right)\right)=\pi\left(U\right)$. 故 $\pi\left(U\right)$ 是商开集与 $\pi\left(X\setminus{A}\right)$ 的交, 即子空间开. 逆连续. 由**定义 3.23 (同胚)**, 限制为同胚.

$CX/\left\langle{X}\right\rangle\cong{S}X$: 由**定义 11.6 (锥)**, $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 在 $CX$ 中再把 $\pi\left(X\times\left\{0\right\}\right)$ 捏成一点, 等价于在 $X\times\left[0,1\right]$ 上把 $X\times\left\{0\right\}$ 与 $X\times\left\{1\right\}$ 各捏成一点. 这正是**定义 11.11 (悬垂)** 中的 $SX$ (经 $t\mapsto2t-1$ 把 $\left[0,1\right]$ 线性映到 $\left[-1,1\right]$). $\blacksquare$

## 4.6 ($n$ 维环面与环面乘积同胚)

($n$-维环面) 设 $T^n=\mathbb{R}^n/\mathbb{Z}^n$, 映射

$$
\phi:\left[\left(t_1,\dots,t_n\right)\right]\mapsto\left(e^{2\pi{i}t_1},\dots,e^{2\pi{i}t_n}\right).
$$

(1) 证明 $\phi$ 连续;

(2) 证明 $T^n$ 豪斯多夫;

(3) 证明 $\phi$ 是同胚.

### 解答 2.22

第 (1) 小题: 由**定义 11.13 ($n$-维环面)**, $\mathbb{R}^n\to\left(S^1\right)^n$ 的映射 $F\left(t\right)=\left(e^{2\pi{i}t_1},\dots,e^{2\pi{i}t_n}\right)$ 连续, 且在 $\mathbb{Z}^n$ 陪集上取等值. 由**定义 11.2 (粘合映射)**, $F$ 经由商映射分解为连续 $\phi:T^n\to\left(S^1\right)^n$.

第 (2) 小题: $T^n$ 是豪斯多夫的: 下一问证 $\phi$ 是到 $\left(S^1\right)^n$ 的同胚, 而 $\left(S^1\right)^n$ 由**定理 3.6 (豪斯多夫的遗传性)** 是豪斯多夫的, 故 $T^n$ 豪斯多夫.

第 (3) 小题: $\phi$ 是双射: $\left(e^{2\pi{i}t_1},\dots\right)$ 的原像陪集唯一. $T^n$ 紧: 它是 $n$ 方体 $\left[0,1\right]^n$ 的商, 由**定理 5.1 (紧空间连续像紧)** 紧. $\left(S^1\right)^n$ 豪斯多夫. 由**定理 5.6 (紧豪斯多夫间的连续双射)**, $\phi$ 是同胚. $\blacksquare$

## 4.7 (最终拓扑, 商拓扑与粘合映射的三者等价)

设 $X$ 是拓扑空间, $A$ 是集合, $\pi:X\to{A}$ 是满射. 证明下列三条等价:

(a) $A$ 上的拓扑是最终拓扑;

(b) 映射 $\pi$ 满足: $U\subset{A}$ 开当且仅当 $\pi^{-1}\left(U\right)$ 在 $X$ 中开;

(c) 映射 $\pi$ 是粘合映射.

### 解答 2.23

(a) $\Rightarrow$ (b): 由**定义 11.14 (最终拓扑)**, 由 $\pi$ 诱导的最终拓扑是使 $\pi$ 连续的最细拓扑, 其特征为: $U\subset{A}$ 开当且仅当 $\pi^{-1}\left(U\right)$ 在 $X$ 中开. 这正是 (b).

(b) $\Rightarrow$ (c): 由 (b), $U\subset{A}$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. 这与**定义 11.1 (商拓扑)** 一致, 也是**定义 11.2 (粘合映射)** 的定义. 故 $\pi$ 是粘合映射.

(c) $\Rightarrow$ (a): 由**定义 11.2 (粘合映射)**, $A$ 上的拓扑是使 $\pi$ 连续的最大拓扑, 即最终拓扑. 三链贯通, 等价. 由**定义 3.22 (连续映射)** 与**定义 3.21 (闭集)** 的对偶, 上述等价成立. $\blacksquare$

## 4.8 (乌雷松引理的度量版本)

证明乌雷松引理的度量版本: 若 $X$ 是度量空间, $F\subset{X}$ 闭集, 则存在连续函数 $f:X\to\left[0,1\right]$ 使 $f=0$ 在 $F$ 上, $f=1$ 在 $X\setminus{B}\left(F,\varepsilon\right)$ 上.

### 解答 2.24

由**定义 6.46 (点到集合的距离)**, $d\left(x,F\right)=\inf_{a\in{F}}d\left(x,a\right)$. 定义

$$
f\left(x\right)=\min\left(1,\frac{d\left(x,F\right)}{\varepsilon}\right).
$$

由 $F$ 闭, $d\left(x,F\right)=0$ 当且仅当 $x\in{F}$, 故 $f=0$ 在 $F$ 上. 若 $x\notin{B}\left(F,\varepsilon\right)$, 则 $d\left(x,F\right)\ge\varepsilon$, 故 $f\left(x\right)=1$.

连续性: $d\left(\cdot,F\right)$ 是利普希茨映射 (由**定义 6.35 (度量空间)** 的三角不等式 $\left|d\left(x,F\right)-d\left(y,F\right)\right|\le{d}\left(x,y\right)$), 复合 $\min\left(1,\cdot\right)$ 连续. 由**定义 3.22 (连续映射)**, $f$ 连续. 这是**定理 7.2 (乌雷松引理)** 在度量空间中的直接形式. $\blacksquare$

## 4.9 ($\mathbb{R}$ 的开子集分解为可数个互不相交的开区间)

证明下列定理: $\mathbb{R}$ 的任一开子集 $U$ 可唯一地写成可数个互不相交的开区间之并, 且这些区间的端点不属于 $U$. 提示: 可考虑含 $x\in{U}$ 的极大开区间 $I_x\subset{U}$.

### 解答 3.1

由**定义 6.36 (开球)**, $\mathbb{R}$ 的通常拓扑以开区间为基. 对每个 $x\in{U}$, 令 $I_x$ 为一切含 $x$ 且含于 $U$ 的开区间之并. 因每个这样的开区间都含 $x$, 其并仍是含 $x$ 的开区间 (一族两两相交于同一点的开区间之并为开区间), 含于 $U$, 且在含 $x$ 且含于 $U$ 的开区间中极大.

断言: 对 $x,y\in{U}$, 或者 $I_x=I_y$, 或者 $I_x\cap{I}_y=\emptyset$. 事实上, 若 $I_x\cap{I}_y\neq\emptyset$, 则 $I_x\cup{I}_y$ 是含 $x,y$ 且含于 $U$ 的开区间, 由 $I_x$ 与 $I_y$ 的极大性, $I_x\cup{I}_y\subset{I}_x$ 且 $I_x\cup{I}_y\subset{I}_y$, 故 $I_x=I_y=I_x\cup{I}_y$.

可数性: 每个 $I_x$ 是非空开区间, 由有理数在实直线上稠密 可取其中一个有理数 $q_x$. 因诸 $I_x$ 互不相交, 不同 $x$ 给出不同 $q_x$, 故 $\left\{I_x:x\in{U}\right\}$ 与 $\mathbb{Q}$ 的某子集一一对应, 因而是可数族. 又因每个 $x\in{U}$ 都含于 $I_x$, 故 $U=\bigcup_{x\in{U}}I_x$.

端点: 写 $I_x=\left(a_x,b_x\right)$. 若 $a_x\in{U}$, 则 $a_x\in{I}_y$ 对某 $y\in{U}$. 因 $I_y$ 开, 存在 $\varepsilon>0$ 使 $\left(a_x-\varepsilon,a_x+\varepsilon\right)\subset{I}_y\subset{U}$. 于是 $\left(a_x-\varepsilon,b_x\right)$ 是含 $x$ 且含于 $U$ 的开区间, 它比 $I_x$ 向左更长, 与 $I_x$ 的极大性矛盾. 故 $a_x\notin{U}$. 同理 $b_x\notin{U}$.

唯一性: 若另有分解 $U=\bigcup_{j\in{J}}J_j$, 其中 $J_j$ 为互不相交开区间. 对每个 $x\in{U}$, $x$ 属于唯一的 $J_{j\left(x\right)}$. $J_{j\left(x\right)}$ 是含 $x$ 且含于 $U$ 的开区间, 由 $I_x$ 的极大性 $J_{j\left(x\right)}\subset{I}_x$; 反之, $I_x$ 是含 $x$ 且含于 $U$ 的开区间, 而 $J_{j\left(x\right)}$ 是含 $x$ 的极大连通开块, 故 $I_x\subset{J}_{j\left(x\right)}$. 因此 $J_{j\left(x\right)}=I_x$, 两分解一致. $\blacksquare$

## 4.10 ($\mathbb{R}$ 与 $\mathbb{R}^2$ 等势但不同胚)

证明 $\mathbb{R}$ 与 $\mathbb{R}^2$ 基数相同, 但不同胚. 提示: 可考察 $\mathbb{R}^2-\left\{0\right\}$ 的像.

### 解答 3.2

先证基数相同. 由**定理 2.13 (实数与自然数幂集等势)**, $\mathbb{R}$ 与 $\mathcal{P}\left(\mathbb{N}\right)$ 等势. 由**定理 2.13 (实数与自然数幂集等势)**, 把一对实数对应到一对子集 $\left(A,B\right)\subset\mathcal{P}\left(\mathbb{N}\right)^2$, 再作

$$
\left(A,B\right)\longmapsto\left\{2n:n\in{A}\right\}\cup\left\{2n+1:n\in{B}\right\}\subset\mathbb{N}.
$$

该映射是单射 (偶数位编码 $A$, 奇数位编码 $B$), 故 $\mathbb{R}^2\to\mathcal{P}\left(\mathbb{N}\right)\cong\mathbb{R}$ 有单射. 反过来 $x\mapsto\left(x,0\right)$ 给出 $\mathbb{R}\to\mathbb{R}^2$ 的单射. 由**定理 2.8 (施罗德-伯恩斯坦定理)**, $\mathbb{R}$ 与 $\mathbb{R}^2$ 基数相等.

再证不同胚. 反设存在同胚 $h:\mathbb{R}\to\mathbb{R}^2$. 由**定义 3.23 (同胚)**, $h$ 限制到 $\mathbb{R}-\left\{0\right\}$ 上, 配以**定义 3.19 (子空间拓扑)**, 仍给出到 $\mathbb{R}^2-\left\{h\left(0\right)\right\}$ 的同胚. 考察两边挖去一点后的连通分支数.

在 $\mathbb{R}$ 一侧,

$$
\mathbb{R}-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right).
$$

由**定理 4.1 (区间连通)**, 两区间各自连通; 它们是不相交非空开集, 故由**定义 4.18 (连通空间)** $\mathbb{R}-\left\{0\right\}$ 不连通, 由**定义 4.8 (连通分支)** 它恰有两个连通分支.

在 $\mathbb{R}^2$ 一侧, $\mathbb{R}^2-\left\{0\right\}$ 路径连通: 任取两点 $u,v$, 选点 $w$ 使 $0,u,w$ 与 $0,w,v$ 均不共线, 折线 $u\to{w}\to{v}$ 避开原点. 由**定理 4.3 (路径连通蕴含连通)**, $\mathbb{R}^2-\left\{0\right\}$ 连通, 由**定义 4.8 (连通分支)** 它只有一个连通分支.

同胚保持连通分支的个数 (连通集映为连通集, 极大性保持). 但上述同胚把有两个分支的 $\mathbb{R}-\left\{0\right\}$ 映到只有一个分支的 $\mathbb{R}^2-\left\{h\left(0\right)\right\}$, 矛盾. 故 $\mathbb{R}$ 与 $\mathbb{R}^2$ 不同胚. $\blacksquare$

## 4.11 (不存在以素数集与有理数集互换的连续函数)

证明不存在连续函数 $f:\mathbb{R}\to\mathbb{R}$ 满足 $f\left(P\right)\subset\mathbb{Q}$ 且 $f\left(\mathbb{Q}\right)\subset{P}$, 其中 $P$ 为素数全体. 提示: 可考察 $f\left(\mathbb{R}\right)$.

### 解答 3.3

$\mathbb{R}$ 是**定义 4.23 (凸集)** 意义下的凸集, 故路径连通, 由**定理 4.3 (路径连通蕴含连通)** $\mathbb{R}$ 连通. 由**定理 4.2 (连续像连通)**, $f\left(\mathbb{R}\right)$ 是 $\mathbb{R}$ 中的连通子集.

$\mathbb{Q}$ 在 $\mathbb{R}$ 中稠密 (有理数在实直线上稠密). 由 $f$ 连续, $f\left(\mathbb{Q}\right)$ 在 $f\left(\mathbb{R}\right)$ 中稠密: 对任意 $y=f\left(x\right)\in{f}\left(\mathbb{R}\right)$, 取有理数列 $q_n\to{x}$, 则由**定义 3.22 (连续映射)** $f\left(q_n\right)\to{f}\left(x\right)=y$.

由题设 $f\left(\mathbb{Q}\right)\subset{P}$. 由素数集在实直线上闭且离散, $P$ 是闭集, 故由**定义 3.26 (闭包)**,

$$
f\left(\mathbb{R}\right)\subset\overline{f\left(\mathbb{Q}\right)}\subset\overline{P}=P.
$$

于是连通集 $f\left(\mathbb{R}\right)$ 含于 $P$. 由素数集在实直线上闭且离散, $P$ 作为子空间是离散的, 而离散空间的任一子集既开又闭, 由**定义 4.18 (连通空间)** 离散空间的连通子集只能是单点集. 故 $f\left(\mathbb{R}\right)=\left\{p_0\right\}$, 即 $f$ 必为常值映射. 因此满足条件的连续函数只能是常值映射, 不存在非常值的这类连续函数. $\blacksquare$

## 4.12 (连通且局部路径连通蕴含路径连通)

证明连通且局部路径连通的空间必路径连通. 提示: 可考察某点的 "路径连通" 分支.

### 解答 3.4

设 $X$ 连通且局部路径连通, 固定 $x\in{X}$, 令

$$
C=\left\{y\in{X}:y\text{~与~}x\text{~之间有连续路径相连}\right\}.
$$

先证 $C$ 开. 任取 $y\in{C}$. 由**定义 4.10 (局部路径连通)**, $y$ 有路径连通邻域 $V$. 对任意 $z\in{V}$, $z$ 与 $y$ 在 $V$ 中有路径, $y$ 与 $x$ 有路径, 两段拼接即得 $z$ 与 $x$ 的路径, 故 $z\in{C}$, 从而 $V\subset{C}$. 由 $y$ 任意, $C$ 开.

再证 $C$ 闭. 取 $y\in\overline{C}$ (**定义 3.26 (闭包)**). 由**定义 4.10 (局部路径连通)**, $y$ 有路径连通邻域 $V$. 由 $\overline{C}$ 的定义, $V\cap{C}\neq\emptyset$, 取 $z\in{V}\cap{C}$. $z$ 与 $x$ 有路径, $y$ 与 $z$ 在 $V$ 中有路径, 拼接得 $y$ 与 $x$ 的路径, 故 $y\in{C}$. 于是 $\overline{C}\subset{C}$, $C$ 闭.

故 $C$ 既开又闭 (**定义 4.19 (既开又闭集)**). $X$ 连通 (**定义 4.18 (连通空间)**), 且 $C\neq\emptyset$ ($x\in{C}$), 故由**定义 4.19 (既开又闭集)** 得 $C=X$. 由**定义 4.22 (路径连通)**, $X$ 路径连通. $\blacksquare$

## 4.13 (多于一点的连通度量空间不可数)

证明多于一点的连通度量空间不可数.

### 解答 3.5

反设 $\left(X,d\right)$ 是**定义 6.35 (度量空间)** 意义下的连通度量空间, $\left|X\right|\ge2$, 且 $X$ 可数. 由**定理 4.5 (可数度量空间完全不连通)**, $X$ 是**定义 4.20 (完全不连通)** 意义下的完全不连通空间, 即其唯一连通子集是单点集.

但 $X$ 本身作为子集由题设连通 (**定义 4.18 (连通空间)**), 且 $\left|X\right|\ge2$, 与完全不连通矛盾. 故 $X$ 不可数. $\blacksquare$

## 4.14 ($GL\left(n,\mathbb{R}\right)$ 与 $GL\left(n,\mathbb{C}\right)$ 的连通分支)

证明一般线性群 $GL\left(n,\mathbb{R}\right)$ (即 $n\times{n}$ 实可逆矩阵之群) 由两个连通分支组成: 行列式为正者与行列式为负者; 特别地它不连通. 证明与之对照, $GL\left(n,\mathbb{C}\right)$ 连通.

### 解答 3.6

行列式映射 $\det:GL\left(n,\mathbb{R}\right)\to\mathbb{R}-\left\{0\right\}$ 是矩阵元素的多项式, 故由**定义 3.22 (连续映射)** 它连续. 由**定理 4.2 (连续像连通)**, $GL\left(n,\mathbb{R}\right)$ 中连通子集的行列式必落入 $\mathbb{R}-\left\{0\right\}=\left(-\infty,0\right)\cup\left(0,\infty\right)$ 的同一连通分支. 故

$$
GL\left(n,\mathbb{R}\right)=GL^{+}\sqcup{G}L^{-}
$$

其中 $GL^{+}=\left\{A:\det{A}>0\right\}$, $GL^{-}=\left\{A:\det{A}<0\right\}$, 二者不相交且各自为开集.

现证 $GL^{+}$ 路径连通. 对任意 $A\in{G}L^{+}$, 作格拉姆-施密特分解 $A=QR$, 其中 $Q\in{S}O\left(n\right)$, $R$ 为对角元全正的上三角阵. 全体这样的 $R$ 构成**定义 4.23 (凸集)** 意义下的凸集, 故路径连通; $SO\left(n\right)$ 中任一正交阵可分解为平面旋转之积, 各旋转角连续收缩到 $0$ 即与单位阵相连. 拼接两条路径, $A$ 与单位阵在 $GL^{+}$ 中路径相连. 同理, 若 $A\in{G}L^{-}$, 取 $D=\operatorname{diag}\left(-1,1,\dots,1\right)$, 则 $AD\in{G}L^{+}$, $AD$ 与单位阵路径相连, 从而 $A$ 与 $D$ 路径相连. 故 $GL^{+}$ 与 $GL^{-}$ 各自路径连通, 由**定义 4.8 (连通分支)** 它们正是 $GL\left(n,\mathbb{R}\right)$ 的两个连通分支; 由**定义 4.18 (连通空间)** $GL\left(n,\mathbb{R}\right)$ 不连通.

对复的情形, 任意 $A\in{G}L\left(n,\mathbb{C}\right)$, 格拉姆-施密特分解 $A=QU$, 其中 $U$ 为酉阵. 酉阵可对角化, 特征值均在单位圆上, 各辐角连续收缩到 $0$ 即与单位阵相连, 故 $U$ 与单位阵路径相连, 从而 $A$ 与单位阵路径相连. 故 $GL\left(n,\mathbb{C}\right)$ 路径连通, 由**定理 4.3 (路径连通蕴含连通)** 它连通. $\blacksquare$
