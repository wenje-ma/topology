# week2

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

> **定义 3.12 (对角线)**
> 
> 集合 $\Delta=\left\{\left(x,x\right):x\in{X}\right\}\subset{X}\times{X}$ 称为对角线. (题集 §1.1)

> **定义 3.13 (细)**
> 
> 称 $\mathcal{O}_1$ 比 $\mathcal{O}_2$ 细, 若 $\mathcal{O}_2\subset\mathcal{O}_1$. (题集 §1.1)

> **定义 3.14 (初始拓扑)**
> 
> 设 $f:X\to{Y}$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal{O}$. 称 $\mathcal{O}_f=\left\{f^{-1}\left(O\right):O\in\mathcal{O}\right\}$ 为 $X$ 上由 $f$ 诱导的初始拓扑; 它是使 $f$ 连续的最粗拓扑. (题集 §1.1 Q2; 题集 §1.4 C6)

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

> **定义 3.29 (由子集族生成的拓扑)**
> 
> 包含某子集族 $\mathcal{S}$ 的最粗拓扑; 其元素恰为 $\mathcal{S}$ 中元素之有限交的任意并. (题集 §1.4)

> **定义 3.30 (基本邻域系)**
> 
> $x$ 的邻域族 $\mathcal{P}$, 使 $x$ 的每个邻域都含某个 $\mathcal{P}$ 中元素. (题集 §2.4)

> **定义 3.31 (内部)**
> 
> 类似地, $A$ 的内部 $\operatorname{int}\left(A\right)$ 是含于 $A$ 的最大开集. (教材 §3, p18)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

> **定理 5.1 (紧空间连续像紧)**
> 
> 紧空间在连续映射下的像是紧的. (教材 $\S5$)

> **定理 5.5 (豪斯多夫中紧集闭)**
> 
> 若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset{X}$ 是闭的. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.6))

> **定理 5.6 (紧豪斯多夫间的连续双射)**
> 
> 紧豪斯多夫空间之间的连续双射是同胚. (教材 §5; "基础拓扑学"(修订版) 第3章 定理(3.7))

> **定理 5.7 (有限乘积紧)**
> 
> 有限个紧空间的乘积紧. (教材 $\S5$, 定理 5.7)

> **定义 6.33 (等价度量)**
> 
> 两度量若诱导同一拓扑则称等价, 例如 $\min\left(d,1\right)$ 与 $d$. (题集 §1.3)

> **定义 6.34 (球面)**
> 
> 以 $x$ 为心, 半径 $r$ 的球面为 $S\left(x,r\right)=\left\{y\in{X}:d\left(x,y\right)=r\right\}$. (题集 §1.3)

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

> **定义 6.45 (超度量)**
> 
> 满足度量空间四条公理且三角不等式加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的度量. (题集 §1.3 Q2)

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
> 满射 $\pi:X\to{Y}$ 下, $U\subset{Y}$ 开当且仅当 $\pi^{-1}\left(U\right)\subset{X}$ 开. (教材 §11, p61; "拓扑学"(原书第2版) §22, p105; "基础拓扑学"(修订版) 第4章 4.2, p55)

> **定义 11.2 (粘合映射)**
> 
> 满射 $f:X\to{Y}$ 使 $U\subset{Y}$ 开当且仅当 $f^{-1}\left(U\right)$ 开; 等价地, $Y$ 上的拓扑是使 $f$ 连续的最大拓扑. 此时 $g:Y\to{Z}$ 连续当且仅当 $gf:X\to{Z}$ 连续. (教材 §11, p61; "基础拓扑学"(修订版) 第4章 定理(4.1)-(4.2), p55-56)

> **定义 11.3 (等价关系粘合)**
> 
> $X/{\sim}$ 配商拓扑, $\pi:X\to{X}/{\sim}$ 为典范投影; 即将每个等价类黏合成一点. (教材 §11, p61; "拓扑学"(原书第2版) §22, p106)

> **定义 11.6 (锥)**
> 
> 从 $X\times\left[0,1\right]$ 出发, 以 (a) 子集 $X\times\left\{1\right\}$ 与 (b) 单点集 $\left\{\left(x,t\right)\right\}$ ($x\in{X}$, $0\le{t}<1$) 为划分作粘合空间, 所得 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$ 叫作 $X$ 上的锥形; 被捏成的点 $X\times\left\{1\right\}$ 叫尖顶. (教材 $\S11$, p63; 题集 $\S5$ Q9; "基础拓扑学"(修订版) 第4章)

> **定义 11.7 (环面)**
> 
> 正方形对边同向粘合所得 $S^1\times{S}^1$, 即 $\mathbb{R}^2/\mathbb{Z}^2$. ("基础拓扑学"(修订版) 第4章 4.2, p56; 教材 §11, p64)

> **定义 11.11 (悬垂)**
> 
> $SX=X\times\left[-1,1\right]/\left(X\times\left\{-1\right\}\cup{X}\times\left\{1\right\}\right)$, 两端各捏成一点. (题集 §5 Q10)

> **定义 11.12 (塌缩商)**
> 
> $X/\left\langle{A}\right\rangle$ 将子集 $A$ 整捏成一点所得商空间. (题集 §5 Q11; "基础拓扑学"(修订版) 第4章, p57)

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
> 一族拓扑空间 $\left\{X_i\right\}_{i\in{I}}$ 的不交和 $\coprod_{i\in{I}}X_i$ 上, $U$ 开当且仅当每个 $U\cap{X}_i$ 在 $X_i$ 中开. (题集 §5 Q1; "基础拓扑学"(修订版) 第4章 定理(4.7), p58)

## 2.1 (豪斯多夫性对子空间遗传)

证明: 若 $X$ 是豪斯多夫度量空间, 则装备诱导拓扑的 $A$ 也是豪斯多夫空间.

### 解答 1.14

任取 $x,y\in{A}$ 且 $x\neq{y}$. 由**定义 3.10 (豪斯多夫空间)**, 因 $X$ 是豪斯多夫的, 存在 $X$ 中不相交的开集 $U,V$ 使 $x\in{U}$, $y\in{V}$. 由**定义 3.19 (子空间拓扑)**, $U\cap{A}$ 与 $V\cap{A}$ 都是 $A$ 中开集, 且 $x\in{U}\cap{A}$, $y\in{V}\cap{A}$. 又因 $U\cap{V}=\emptyset$, 故 $\left(U\cap{A}\right)\cap\left(V\cap{A}\right)=\emptyset$. 由**定义 3.10 (豪斯多夫空间)**, $A$ 中任意一对不同点都有不相交的邻域, 故 $A$ 是豪斯多夫空间. $\blacksquare$

## 2.2 (子空间豪斯多夫而全空间不豪斯多夫的例子)

构造例子: 子空间 $X\subset{Y}$ 是豪斯多夫的, 但 $X$ 中两点在 $Y$ 中没有不相交的邻域. 可考虑 $Y=X\cup\left\{\omega\right\}$, 其中 $\omega$ 是额外一点, $Y$ 的任一非空开集形如 $O\cup\left\{\omega\right\}$, 其中 $O$ 是 $X$ 中的开集.

### 解答 1.15

取 $X=\mathbb{R}$ 装备通常拓扑, 由**定义 3.10 (豪斯多夫空间)** 它是豪斯多夫的. 令 $Y=X\cup\left\{\omega\right\}$, 规定 $Y$ 的开集为 $\emptyset$ 与一切形如 $O\cup\left\{\omega\right\}$ 的集合, 其中 $O$ 取遍 $X$ 中开集. 验证这是 $Y$ 上的拓扑, 由**定义 3.18 (拓扑空间)** 逐条验证: $\emptyset$ 开 (题设); 取 $O=X$ 得 $Y=X\cup\left\{\omega\right\}$ 开. 任意并

$$
\bigcup_i\left(O_i\cup\left\{\omega\right\}\right)=\left(\bigcup_iO_i\right)\cup\left\{\omega\right\},
$$

由**定义 3.18 (拓扑空间)** $\bigcup_iO_i$ 是 $X$ 中开集, 故 $\left(\bigcup_iO_i\right)\cup\left\{\omega\right\}$ 是 $Y$ 中开集 (若 $\bigcup_iO_i=\emptyset$, 则并集为 $\emptyset$, 亦开). 有限交

$$
\left(O_1\cup\left\{\omega\right\}\right)\cap\left(O_2\cup\left\{\omega\right\}\right)=\left(O_1\cap{O}_2\right)\cup\left\{\omega\right\},
$$

同理由**定义 3.18 (拓扑空间)** 是 $Y$ 中开集. 故这确为 $Y$ 上的拓扑.

任取 $x,y\in{X}$ 且 $x\neq{y}$. $Y$ 中含 $x$ 的开集形如 $O\cup\left\{\omega\right\}$ 且 $x\in{O}$; $Y$ 中含 $y$ 的开集同理形如 $O'\cup\left\{\omega\right\}$ 且 $y\in{O}'$. 而两邻域含 $\omega$ 必相交. 故 $X$ 中任两点在 $Y$ 中没有不相交的邻域. $\blacksquare$

## 2.3 (超度量的球, 球面与球族结构)

回忆距离 $d:X\times{X}\to\mathbb{R}_{\ge0}$ 满足四条公理. 超度量是将三角不等式加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的距离 (例如通常的 $p$-进度量). 设 $d$ 是超度量, 证明:

(1) 若 $d\left(x,y\right)\neq{d}\left(x,z\right)$, 则 $d\left(y,z\right)=\max\left\{d\left(x,y\right),d\left(x,z\right)\right\}$;

(2) 开球中任一点都是该开球的中心;

(3) 开球中任一点都是由该开球所定球面的中心;

(4) 任意两个开球或者不相交, 或者一个含于另一个.

### 解答 1.16

(1) 不妨设 $d\left(x,y\right)<{}d\left(x,z\right)$, 则欲证 $d\left(y,z\right)=\max\left\{d\left(x,y\right),d\left(x,z\right)\right\}$, 只需证 $d\left(x,z\right)=d\left(y,z\right)$.

由加强的三角不等式,

$$
d\left(x,z\right)\le\max\left\{d\left(x,y\right),d\left(y,z\right)\right\},
$$

由于 $d\left(x,y\right)<{}d\left(x,z\right)$, 则 $\max\left\{d\left(x,y\right),d\left(y,z\right)\right\}=d\left(y,z\right)$, 即 $d\left(x,z\right)\le{d}\left(y,z\right)$.

同理,

$$
d\left(y,z\right)\le\max\left\{d\left(x,y\right),d\left(x,z\right)\right\},
$$

由于 $d\left(x,y\right)<{}d\left(x,z\right)$, 则 $\max\left\{d\left(x,y\right),d\left(x,z\right)\right\}=d\left(x,z\right)$, 即 $d\left(y,z\right)\le{d}\left(x,z\right)$. 合并得 $d\left(y,z\right)=d\left(x,z\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)$.

(2) 设 $z\in{B}\left(x,r\right)$, 即由**定义 6.36 (开球)** $d\left(x,z\right)<{}r$. 任取 $w\in{B}\left(x,r\right)$, 即 $d\left(x,w\right)<{}r$. 由**定义 6.45 (超度量)**, $d\left(z,w\right)\le\max\left(d\left(z,x\right),d\left(x,w\right)\right)$; 因两项都 $<{}r$, 故 $d\left(z,w\right)<{}r$, 即 $w\in{B}\left(z,r\right)$. 于是 $B\left(x,r\right)\subset{B}\left(z,r\right)$. 同理 $B\left(z,r\right)\subset{B}\left(x,r\right)$. 因此 $B\left(x,r\right)=B\left(z,r\right)$, 即 $z$ 也是该开球的中心.

(3) 由**定义 6.34 (球面)**, $S\left(x,r\right)=\left\{y:d\left(x,y\right)=r\right\}$. 设 $z\in{B}\left(x,r\right)$, 即 $d\left(x,z\right)<{}r$. 任取 $w\in{S}\left(x,r\right)$, 即 $d\left(x,w\right)=r$. 因 $d\left(x,z\right)<{}r=d\left(x,w\right)$, 故 $d\left(x,z\right)\neq{d}\left(x,w\right)$; 由第 (1) 小题, $d\left(z,w\right)=\max\left(d\left(x,z\right),d\left(x,w\right)\right)=r$, 故 $w\in{S}\left(z,r\right)$, 即 $S\left(x,r\right)\subset{S}\left(z,r\right)$, 同理, $S\left(z,r\right)\subset{S}\left(x,r\right)$. 故 $S\left(x,r\right)=S\left(z,r\right)$, 即 $z$ 也是该球面的中心.

(4) 设 $B\left(x,r\right)$ 与 $B\left(y,s\right)$ 为两个开球. 若不相交则结论已成立. 若相交, 取 $z\in{B}\left(x,r\right)\cap{B}\left(y,s\right)$. 由第 (2) 小题, $B\left(x,r\right)=B\left(z,r\right)$ 且 $B\left(y,s\right)=B\left(z,s\right)$. 不妨设 $r\le{s}$, 则 $B\left(z,r\right)\subset{B}\left(z,s\right)$, 即 $B\left(x,r\right)\subset{B}\left(y,s\right)$. $\blacksquare$

## 2.4 (两个有界化度量诱导同一拓扑)

设 $\left(X,d\right)$ 是度量空间, 再定义度量 $d^{*}\left(x,y\right)=\min\left(d\left(x,y\right),1\right)$ 与 $d^{**}\left(x,y\right)=\frac{d\left(x,y\right)}{1+d\left(x,y\right)}$. 证明他们与 $d$ 诱导同一拓扑. 注意有界性依赖于度量的选取, 而不依赖于拓扑.

### 解答 1.17

对 $r\in\left(0,1\right)$, $d^{*}\left(x,y\right)=\min\left(d\left(x,y\right),1\right)=d\left(x,y\right)$, 故 $d^{*}$ 与 $d$ 的半径小于 $1$ 的球族完全相同;

而对 $d^{**}$, 半径 $r\in\left(0,1\right)$ 的球为 $B_{d^{**}}\left(x,r\right)=\left\{y:\frac{d\left(x,y\right)}{1+d\left(x,y\right)}<{}r\right\}$; 由分式恒等式, $\frac{d\left(x,y\right)}{1+d\left(x,y\right)}<{}r$ 当且仅当 $d\left(x,y\right)<\frac{r}{1-r}$, 故 $B_{d^{**}}\left(x,r\right)=\left\{y:d\left(x,y\right)<\frac{r}{1-r}\right\}=B_{d}\left(x,\frac{r}{1-r}\right)$, 即 $d^{**}$ 的球与 $d$ 的球一一对应.

由**定义 6.36 (开球)**, 全体开球族是度量拓扑的基, 故三者生成同一拓扑. 由**定义 6.33 (等价度量)**, $d^{*}$ 与 $d^{**}$ 都与 $d$ 等价. $\blacksquare$

> 详细说来, $d$ 与 $d'$ 比较, 虽然 $d'$ 的拓扑基并不和 $d$ 完全相同, 但 $d$ 中很容易就能找到一组基, 满足其半径均 $r\in\left(0,1\right)$, 此时就与 $d'$ 的拓扑基一致, 因此二者生成同一拓扑;
> 
> 而 $d'$ 与 $d''$ 比较, 则只是换了一个参数: 对于 $r\in\left(0,1\right)$, $r\mapsto\frac{r}{1-r}=:\rho$. 因此二者自然生成同一拓扑.

## 2.5 (开集的任意并开而任意交未必开)

回忆 $\mathbb{R}^n$ 上的通常度量拓扑. 证明 $\mathbb{R}^n$ 中任意一族开集之并仍是开集. 证明开集的交未必是开集.

### 解答 1.18

由**定义 3.18 (拓扑空间)**, 开集的任意并仍开; 但任意交未必开. 取 $\mathbb{R}$ 中一列开区间 $\left(-\frac1n,\frac1n\right)$ ($n\ge1$), 其交为

$$
\bigcap_{n=1}^{\infty}\left(-\frac1n,\frac1n\right)=\left\{0\right\}.
$$

由**定义 6.36 (开球)**, 任何含 $0$ 的开球都含非零点, 故 $\left\{0\right\}$ 不含任何开球, 不是开集. $\blacksquare$

## 2.6 (原像与并, 交交换, 而直接像不然)

回忆函数的原像. 证明原像运算与并运算, 交运算可交换. 那直接像呢?

### 解答 1.19

对于原像, 由原像与并运算交换与原像与交运算交换易证:

$$
f^{-1}\left(\bigcup_jA_j\right)=\bigcup_jf^{-1}\left(A_j\right),\quad{f}^{-1}\left(\bigcap_jA_j\right)=\bigcap_jf^{-1}\left(A_j\right).
$$

直接像 $f\left(A\right)=\left\{f\left(x\right):x\in{A}\right\}$ 则不然: 并运算可交换, $f\left(\bigcup_jA_j\right)=\bigcup_jf\left(A_j\right)$; 但交运算只含一边,

$$
f\left(\bigcap_jA_j\right)\subset\bigcap_jf\left(A_j\right),
$$

等号一般不成立.

反例: 取 $f\left(t\right)=t^2$, $A_1=\left[-1,0\right]$, $A_2=\left[0,1\right]$. 则 $A_1\cap{A}_2=\left\{0\right\}$, 故 $f\left(A_1\cap{A}_2\right)=\left\{0\right\}$; 但 $f\left(A_1\right)=f\left(A_2\right)=\left[0,1\right]$, 故 $\bigcap_jf\left(A_j\right)=\left[0,1\right]$. 包含而不相等. $\blacksquare$

> (1) 考虑原像时, 是看着 $x$ 找 $y$, 都是一一对应的; 考虑直接像时是看着 $y$ 找 $x$, 而一个 $y$ 可能对应多个 $x$, 因此不可逆, 自然也不可交换.
> 
> (2) 直接像的并可交换, 但直接像的交不可交换: 考虑并时, 虽然是看着 $y$ 找 $x$, 但并集的含义是 "存在一个" 即可, 因此虽然可能有多个 $x$, 找到一个就行; 考虑交时, 交集的含义是 "任意一个" 均需要满足, 这就要求了 $x$ 需唯一才行, 因此不可逆, 自然也不可交换.

## 2.7 (生成子空间的两种构造)

回忆由一族向量生成的向量子空间. 给出一个利用向量空间对交集稳定性的抽象构造, 以及一个利用有限线性组合的具体构造.

### 解答 1.20

设 $E$ 是域上向量空间, $\mathcal{F}=\left\{v_\alpha\right\}_{\alpha\in{A}}\subset{E}$.

抽象构造: 令 $\mathcal{S}$ 为 $E$ 中一切包含 $\mathcal{F}$ 的向量子空间所成之族, 定义 $\operatorname{span}\left(\mathcal{F}\right)=\bigcap_{S\in\mathcal{S}}S$. 因任意一族向量子空间的交集仍是向量子空间 (对加法与数乘封闭, 且含零向量), 故 $\operatorname{span}\left(\mathcal{F}\right)$ 是包含 $\mathcal{F}$ 的子空间, 且是其中最小者.

具体构造: 令

$$
\operatorname{span}\left(\mathcal{F}\right)=\left\{\sum_{k=1}^{m}c_kv_{\alpha_k}:m\ge1,c_k\text{~为域中元素},v_{\alpha_k}\in\mathcal{F}\right\},
$$

即 $\mathcal{F}$ 中元素的有限线性组合全体. 它本身是包含 $\mathcal{F}$ 的向量子空间, 故含于抽象构造. 反之, 任何包含 $\mathcal{F}$ 的向量子空间对线性组合封闭, 故包含全部有限线性组合, 因而抽象构造 (一切子空间之交) 也含于该具体集合. 两者相等. $\blacksquare$

## 2.8 ($\mathbb{R}$ 中闭集与序列极限的刻画)

证明: 集合 $F$ 在 $\mathbb{R}$ 的通常度量拓扑下闭, 当且仅当 $F$ 的每个收敛序列的极限都在 $F$ 中.

### 解答 1.21

($\Rightarrow$) 设 $F$ 闭. 由**定义 3.21 (闭集)**, $\mathbb{R}\setminus{F}$ 开. 设 $x_n\in{F}$ 且 $x_n\to{x}$. 若 $x\notin{F}$, 则 $x\in\mathbb{R}\setminus{F}$, 而 $\mathbb{R}\setminus{F}$ 是 $x$ 的邻域. 由**定义 3.25 (邻域与极限)**, 对所有充分大的 $n$ 有 $x_n\in\mathbb{R}\setminus{F}$, 与 $x_n\in{F}$ 矛盾. 故 $x\in{F}$.

($\Leftarrow$) 反证. 设 $F$ 不闭. 由**定义 3.21 (闭集)**, $\mathbb{R}\setminus{F}$ 不开. 故存在 $x\notin{F}$ 使 $x$ 的任何邻域都不含于 $\mathbb{R}\setminus{F}$, 即 $x$ 的任何邻域都与 $F$ 相交, 说明 $x$ 在 $F$ 的边界上. 由**定义 6.36 (开球)**, 球 $B\left(x,1/n\right)=\left(x-\frac1n,x+\frac1n\right)$ 与 $F$ 相交, 取 $x_n\in{F}\cap{B}\left(x,1/n\right)$, 则 $d\left(x_n,x\right)<1/n$. 任给 $x$ 的邻域, 由**定义 6.36 (开球)** 它包含某 $B\left(x,\varepsilon\right)$; 当 $n>1/\varepsilon$ 时 $x_n\in{B}\left(x,\varepsilon\right)$, 故由**定义 3.25 (邻域与极限)** $x_n\to{x}$. 但 $x\notin{F}$, 与假设矛盾. 故 $F$ 闭. $\blacksquare$

## 2.9 (由子集族生成的拓扑及其有限交构造)

回忆同一空间 $X$ 上一族拓扑的交集仍是拓扑. 回忆由 $X$ 的一族子集生成的拓扑是什么. 是否有一个利用有限交的具体构造?

### 解答 1.22

同一空间 $X$ 上一族拓扑 $\left\{\mathcal{O}_\alpha\right\}_{\alpha\in{A}}$ 的交集 $\mathcal{O}=\bigcap_{\alpha\in{A}}\mathcal{O}_\alpha$ 仍是拓扑: 由原像保空集与全集类的平凡性, $\emptyset$ 与 $X$ 属于每个 $\mathcal{O}_\alpha$, 故属于 $\mathcal{O}$; 若 $\left\{U_i\right\}\subset\mathcal{O}$, 则对每个 $\alpha$ 有 $\left\{U_i\right\}\subset\mathcal{O}_\alpha$, 由**定义 3.18 (拓扑空间)** (开集的任意并仍开) $\bigcup_iU_i\in\mathcal{O}_\alpha$, 故 $\bigcup_iU_i\in\mathcal{O}$; 有限交同理 (**定义 3.18 (拓扑空间)** (2)).

由**定义 3.29 (由子集族生成的拓扑)**, 给定子集族 $\mathcal{S}\subset\mathcal{P}\left(X\right)$, 它生成的拓扑即包含 $\mathcal{S}$ 的最粗拓扑, 存在且等于一切包含 $\mathcal{S}$ 的拓扑之交. 其具体构造为: 先取 $\mathcal{S}$ 中元素的有限交 (约定空交为 $X$), 再取这些有限交的任意并 (约定空并为 $\emptyset$). 所得族 $\tau$ 确实是拓扑: $\emptyset,X\in\tau$; 任意并仍是任意并; 两个有限交的有限交仍是有限交, 故有限交封闭; 由**定义 3.18 (拓扑空间)** $\tau$ 是拓扑. 它包含 $\mathcal{S}$ (每个 $S\in\mathcal{S}$ 是单元素族的有限交). 反之, 任何包含 $\mathcal{S}$ 的拓扑由**定义 3.18 (拓扑空间)** 对有限交与任意并封闭, 必包含 $\tau$ 的全部元素, 故 $\tau$ 是最粗的. $\blacksquare$

## 2.10 (初始拓扑, 最终拓扑与包含映射的例子)

证明: 若 $f:X\to\left(Y,\mathcal{O}\right)$ 是到拓扑空间 $Y$ 的映射, 则集合族 $\left\{f^{-1}\left(O\right):O\in\mathcal{O}\right\}$ 在 $X$ 上定义一个拓扑. 证明它是使 $f$ 连续的最粗拓扑, 即初始拓扑. 研究 $f$ 为包含映射的情形, 例如 $f:\mathbb{R}\to\mathbb{R}^2$, 其中 $\mathbb{R}^2$ 装备欧氏拓扑. 反过来, 能否把 $X$ 上的拓扑前推, 在 $Y$ 上定义所谓最终拓扑?

### 解答 1.23

记 $\mathcal{O}_f=\left\{f^{-1}\left(O\right):O\in\mathcal{O}\right\}$. 由原像与并运算交换, 原像与交运算交换 与原像保空集与全集, $\mathcal{O}_f$ 满足**定义 3.18 (拓扑空间)** 的三条: $\emptyset=f^{-1}\left(\emptyset\right)$ 与 $X=f^{-1}\left(Y\right)$ 在 $\mathcal{O}_f$ 中; 任意并 $\bigcup_jf^{-1}\left(O_j\right)=f^{-1}\left(\bigcup_jO_j\right)$ 仍在 $\mathcal{O}_f$ 中; 有限交 $f^{-1}\left(O_1\right)\cap{f}^{-1}\left(O_2\right)=f^{-1}\left(O_1\cap{O}_2\right)$ 仍在其中. 故 $\mathcal{O}_f$ 是 $X$ 上的拓扑.

对任意 $O\in\mathcal{O}$, $f^{-1}\left(O\right)\in\mathcal{O}_f$ 是开集, 由**定义 3.22 (连续映射)** $f$ 连续. 反之, 若 $\tau$ 是 $X$ 上任一使 $f$ 连续的拓扑, 则对每个 $O\in\mathcal{O}$, 由**定义 3.22 (连续映射)** $f^{-1}\left(O\right)\in\tau$, 故 $\mathcal{O}_f\subset\tau$. 由**定义 3.14 (初始拓扑)**, $\mathcal{O}_f$ 正是 $f$ 诱导的初始拓扑.

包含映射的情形: 取 $f:\mathbb{R}\to\mathbb{R}^2$, $f\left(t\right)=\left(t,0\right)$, $\mathbb{R}^2$ 装备欧氏拓扑. 则 $f^{-1}\left(U\right)=U\cap\left(\mathbb{R}\times\left\{0\right\}\right)$, 它在 $x$ 轴上的投影恰为 $\mathbb{R}$ 的通常开集, 故 $\mathcal{O}_f$ 就是 $\mathbb{R}$ 的通常拓扑.

反过来的构造: 由**定义 11.14 (最终拓扑)**, 对映射 $f:X\to{Y}$, 在 $Y$ 上规定 $U\subset{Y}$ 开当且仅当 $f^{-1}\left(U\right)$ 在 $X$ 中开. 这是使 $f$ 连续的最细拓扑, 即最终拓扑. $\blacksquare$

## 2.11 (余有限拓扑与余可数拓扑中的收敛和闭包)

设 $X$ 为集合. 证明下列是拓扑: 所有非平凡开集都是 $X$ 的某有限子集的补集; 这称为 $X$ 上的余有限拓扑. 证明序列 $\left\{1,2,3,4,\dots\right\}$ 在 $\mathbb{R}$ 的余有限拓扑中收敛到 $\mathbb{R}$ 的每一点. 能否在 $X$ 上定义余可数拓扑? 现在取 $X=\mathbb{R}$ 装备余可数拓扑, 考虑 $\left(-1,1\right)\subset\mathbb{R}$. 证明 $\overline{\left(-1,1\right)}=\mathbb{R}$. 证明 $\left(-1,1\right)$ 中没有序列收敛到 $2\in\mathbb{R}$.

### 解答 2.1

$\emptyset$ 与 $X$ 开; 任意并 $\bigcup_i\left(X\setminus{F}_i\right)=X\setminus\bigcap_iF_i$, 而任意一族有限集之交仍有限, 故仍余有限; 有限交 $\bigcap_{k=1}^{m}\left(X\setminus{F}_k\right)=X\setminus\bigcup_{k=1}^{m}F_k$, 有限个有限集之并仍有限. 由**定义 3.18 (拓扑空间)** 这是拓扑.

序列 $\left\{n\right\}_{n\ge1}$ 在余有限拓扑 $\mathbb{R}$ 中收敛到任一点 $x$: $x$ 的任一邻域是 $X\setminus{F}$ ($F$ 有限). 因 $F$ 只含有限个自然数, 除有限个 $n$ 外 $n\notin{F}$, 故 $n\in{X}\setminus{F}$ 最终成立. 由**定义 3.25 (邻域与极限)**, $n\to{x}$.

余可数拓扑: 由**定义 3.27 (余可数拓扑)**, 开集为 $\emptyset$ 与所有余可数集 $X\setminus{C}$ ($C$ 可数). 现在取 $X=\mathbb{R}$ 装备余可数拓扑, 令 $A=\left(-1,1\right)$. 任取 $x\in\mathbb{R}$ 与其任一邻域 $U=\mathbb{R}\setminus{C}$ ($C$ 可数). 因 $\left(-1,1\right)$ 不可数而 $C$ 可数, 故 $A\setminus{C}=\left(-1,1\right)\setminus{C}\neq\emptyset$, 即 $U\cap{A}\neq\emptyset$. 由**定义 3.26 (闭包)**, $x$ 属于 $A$ 的闭包. 故 $\overline{A}=\mathbb{R}$.

最后, 设 $x_n\in{A}$ 且 $x_n\to2$. 令 $C=\left\{x_n:n\ge1\right\}$, 它可数. 则 $U=\mathbb{R}\setminus{C}$ 是余可数开集, 含 $2$, 但不含任何 $x_n$. 由**定义 3.25 (邻域与极限)**, 这与 $x_n\to2$ 矛盾. 故 $A$ 中没有序列收敛到 $2$. $\blacksquare$

## 2.12 (扎里斯基拓扑, 扎里斯基开集的稠密性与闭包)

设 $K$ 为域, $n\in\mathbb{N}$ 为非负整数, $\mathbb{A}^n\left(K\right)=K^n$. $\mathbb{A}^n\left(K\right)$ 中扎里斯基闭集形如 $F=\left\{x\in\mathbb{A}^n\left(K\right):\forall{i}\in{I},P_i\left(x\right)=0\right\}$, 其中 $\left(P_i\right)_{i\in{I}}$ 是一族多项式. 证明这确实定义了一个拓扑 (即扎里斯基拓扑). 证明 $\mathbb{R}^2$ 中扎里斯基开集在 $\mathbb{R}^2$ 中稠密. 求 $\left\{\left(0,\frac1{2^n}\right):n\ge0\right\}\subset\mathbb{R}^2$ 的扎里斯基闭包.

### 解答 2.2

由**定义 3.28 (扎里斯基拓扑)**, 记 $Z\left(P_i\right)_{i\in{I}}=\left\{x:\forall{i}\in{I},P_i\left(x\right)=0\right\}$. 验证闭集族满足**定义 3.21 (闭集)**: 空集 $Z\left(1\right)$ (常数多项式 $1$ 无零点); 全空间 $Z\left(0\right)$ (零多项式处处为零); 任意交

$$
\bigcap_{\alpha}Z\left(P_{\alpha,j}\right)_{j\in{J}_\alpha}=Z\left(\bigcup_\alpha\left\{P_{\alpha,j}\right\}\right)
$$

仍为公共零点集; 两个闭集之并

$$
Z\left(P_i\right)_{i\in{I}}\cup{Z}\left(Q_j\right)_{j\in{J}}=Z\left(P_iQ_j\right)_{i,j}
$$

(因 $x$ 在左端当且仅当某 $P_i\left(x\right)=0$ 或某 $Q_j\left(x\right)=0$, 当且仅当对一切 $\left(i,j\right)$ 有 $P_i\left(x\right)Q_j\left(x\right)=0$). 故闭集族满足**定义 3.21 (闭集)**, 扎里斯基拓扑成立.

扎里斯基开集稠密: 非空扎里斯基开集是某非零多项式 $P$ 的零点集的补集 $\mathbb{R}^2\setminus{Z}\left(P\right)$. 若 $Z\left(P\right)$ 含某开球, 则该开球内沿任一直线限制 $P$ 所得一元多项式在无限多点为零, 由一元多项式恒零判据 故恒为零; 从而 $P$ 在该开球上恒为零, 进而 $P\equiv0$, 矛盾. 故 $Z\left(P\right)$ 无内部. 由**定义 3.32 (稠密)**, 其补集 (扎里斯基开集) 稠密.

求闭包: 令 $S=\left\{\left(0,2^{-n}\right):n\ge0\right\}$. 多项式 $P$ 在 $S$ 上恒零当且仅当一元多项式 $P\left(0,y\right)$ 在无限多点 $y=2^{-n}$ 为零, 由一元多项式恒零判据 当且仅当 $P\left(0,\cdot\right)\equiv0$, 即 $x\mid{P}\left(x,y\right)$. 全体这样的 $P$ 的公共零点集为 $\left\{\left(0,y\right):y\in\mathbb{R}\right\}$, 即 $y$ 轴. 由**定义 3.26 (闭包)**, 这就是 $S$ 的扎里斯基闭包. $\blacksquare$

## 2.13 (拓扑基的定义与等价刻画及其等价性)

回忆拓扑基的定义. 回忆其等价刻画. 若去掉其中任一条件会怎样? 证明定义与刻画的等价性.

### 解答 2.3

由**定义 3.15 (拓扑基)**, 拓扑基的定义是: $\mathcal{B}\subset\mathcal{P}\left(X\right)$ 中元素的任意并构成 $X$ 上一个拓扑. 其等价刻画为: (1) $X=\bigcup_{B\in\mathcal{B}}B$; (2) 对任意 $B_1,B_2\in\mathcal{B}$ 与任意 $x\in{B}_1\cap{B}_2$, 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_1\cap{B}_2$.

定义 $\Rightarrow$ 刻画: 若 $\mathcal{B}$ 的任意并构成拓扑, 由**定义 3.18 (拓扑空间)**, 则 $X=\bigcup_{B\in\mathcal{B}}B$ 是开集, 即 (1). 又 $B_1\cap{B}_2$ 是两开集之交, 仍开, 故可表为 $\mathcal{B}$ 中元素之并; 任取 $x\in{B}_1\cap{B}_2$, 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_1\cap{B}_2$, 即 (2).

刻画 $\Rightarrow$ 定义: 设 (1)(2) 成立. 令 $\tau=\left\{\bigcup_{B\in\mathcal{C}}B:\mathcal{C}\subset\mathcal{B}\right\}$. 由 (1) $X\in\tau$, 空并 $\emptyset\in\tau$. $\tau$ 中任意并显然仍在 $\tau$ 中. 设 $U=\bigcup_{\alpha}B_\alpha\in\tau$, $V=\bigcup_{\beta}B'_\beta\in\tau$, 则 $U\cap{V}=\bigcup_{\alpha,\beta}\left(B_\alpha\cap{B}'_\beta\right)$. 对每个 $x\in{B}_\alpha\cap{B}'_\beta$, 由 (2) 存在 $B_3\in\mathcal{B}$ 使 $x\in{B}_3\subset{B}_\alpha\cap{B}'_\beta$, 故 $B_\alpha\cap{B}'_\beta$ 是若干 $\mathcal{B}$ 中元素之并, 从而 $U\cap{V}\in\tau$. 由**定义 3.18 (拓扑空间)**, $\tau$ 是拓扑.

去掉条件: 若去掉 (1), 例如 $\mathcal{B}=\left\{\emptyset\right\}$, 其任意并只能得 $\emptyset$, 盖不住 $X$; 若去掉 (2), 例如 $X=\mathbb{R}$, $\mathcal{B}=\left\{\left(-\infty,a\right):a\in\mathbb{R}\right\}\cup\left\{\left(b,+\infty\right):b\in\mathbb{R}\right\}$, 则 $\left(-\infty,1\right)\cap\left(0,+\infty\right)=\left(0,1\right)$ 不能表为 $\mathcal{B}$ 中元素之并, 故 $\mathcal{B}$ 的任意并不构成拓扑. $\blacksquare$

## 2.14 (可数基蕴含可分; 半开区间基的反例)

可分空间与具有可数基的空间.

(1) 证明具有可数基的拓扑空间必可分;

(2) 考虑 $\mathbb{R}$ 上以 $\mathcal{B}=\left\{\left(a,b\right]\subset\mathbb{R}:a<{}b\right\}$ 为基. 证明 $\mathcal{B}$ 确实是某拓扑 $\mathcal{O}$ 的基; 证明 $\mathcal{O}$ 可分但没有可数基; 证明 $\mathcal{O}$ 不来自度量拓扑 (即不可度量化).

### 解答 2.4

(1) 设 $\left\{B_n\right\}_{n\ge1}$ 是 $X$ 的可数基. 每点取 $x_n\in{B}_n$, 令 $D=\left\{x_n:n\ge1\right\}$. 由于 $\overline{D}\subset{X}$ 显然, 只需证明 $X\subset\overline{D}$. 任取 $x\in{X}$ 与非空开集 $U\ni{x}$, 由**定义 3.15 (拓扑基)** 存在某 $B_n\subset{U}$, 故存在一个 $x_n$ 满足 $x_n\in{D}\cap{U}\neq\emptyset$, 这说明 $x$ 是 $D$ 的闭包点, 即 $x\in\overline{D}$. 由**定义 3.32 (稠密)**, $D$ 在 $X$ 中稠密; 由**定义 3.9 (可分)**, $X$ 可分.

(2) 先验基条件:

$$
\left(a,b\right]\cap\left(c,d\right]=\left(\max\left(a,c\right),\min\left(b,d\right)\right]
$$

当非空时仍是 $\mathcal{B}$ 中元素, 且 $\mathbb{R}=\bigcup_{a,b}\left(a,b\right]$ 覆盖全空间. 由**定义 3.15 (拓扑基)**, $\mathcal{B}$ 生成 $\mathbb{R}$ 上某拓扑 $\mathcal{O}$.

可分: 有理数集 $\mathbb{Q}$ 在 $\mathcal{O}$ 中稠密, 因由有理数在实直线上稠密 每个 $\left(a,b\right]$ 都含有理数. 由**定义 3.9 (可分)**, $\mathcal{O}$ 可分.

无可数基: 反设 $\left\{W_n\right\}$ 是可数基. 对每个 $x\in\mathbb{R}$, 选基元素 $W_{n\left(x\right)}$ 使

$$
x\in{W}_{n\left(x\right)}\subset\left(x-1,x\right].
$$

$W_{n\left(x\right)}$ 作为某 $\left(a,b\right]$ 之并, 其右端点不超过 $x$ 且含 $x$, 故其右端点恰为 $x$. 于是 $x\neq{y}$ 时 $W_{n\left(x\right)}\neq{W}_{n\left(y\right)}$ (右端点不同). 这给出从不可数集 $\mathbb{R}$ 到可数集 $\left\{W_n\right\}$ 的单射, 矛盾. 故 $\mathcal{O}$ 无可数基.

不可度量化: 反设 $\mathcal{O}$ 来自某度量拓扑. 前面已证 $\mathcal{O}$ 可分 (有理数集 $\mathbb{Q}$ 稠密). 由**命题 M30.1 (可分度量空间必有可数基)**, $\mathcal{O}$ 作为可分度量空间必有可数基; 但前面刚证 $\mathcal{O}$ 没有可数基, 矛盾. 故 $\mathcal{O}$ 不可度量化. $\blacksquare$
