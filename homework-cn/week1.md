# week1 (((拓扑空间)))

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

> **定义 3.31 (内部)**
> 
> 类似地, $A$ 的内部 $\operatorname{int}\left(A\right)$ 是含于 $A$ 的最大开集. (教材 §3, p18)

> **定义 3.32 (稠密)**
> 
> 我们称 $A\subset{X}$ 在 $X$ 中稠密, 若 $\overline{A}=X$. (教材 $\S3$; 题集 $\S1.1$)

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

## 1.1 (谢尔宾斯基空间: 闭包, 收敛与连续自映射)
考虑谢尔宾斯基空间, 其中 $X=\left\{0,1\right\}$, $\mathcal{O}=\left\{\emptyset,\left\{0\right\},\left\{0,1\right\}\right\}$.

(1) 计算 $\left\{1\right\}$ 的闭包;

(2) 问 $\left(X,\mathcal{O}\right)$ 是否是豪斯多夫空间;

(3) 考虑 $\mathcal{O}'=\left\{\emptyset,\left\{1\right\},\left\{0,1\right\}\right\}$, 通过构造一个连续映射 $f:\left(X,\mathcal{O}\right)\to\left(X,\mathcal{O}'\right)$, 证明 $\mathcal{O}$ 与 $\mathcal{O}'$ 是同胚的;

(4) 证明 $\left(X,\mathcal{O}\right)$ 中所有序列都收敛到 $1$;

(5) 描述 $\left(X,\mathcal{O}\right)$ 中收敛到 $0$ 的序列所成的集合;

(6) 构造一个既收敛到 $0$ 又收敛到 $1$ 的序列;

(7) 证明从 $\left(X,\mathcal{O}\right)$ 到自身的连续映射恰有三个.

题集 §1.1 Q1.

### 解答 1.1

(1) 由**定义 3.18 (拓扑空间)**, $\mathcal{O}$ 的开集为 $\emptyset,\left\{0\right\},\left\{0,1\right\}$. 由**定义 3.21 (闭集)**, 闭集是开集的补集, 故 $\mathcal{O}$ 的闭集为 $X,\left\{1\right\},\emptyset$. 因 $\left\{1\right\}$ 是闭集, 由**定义 3.26 (闭包)** 其为包含 $\left\{1\right\}$ 的最小闭集, 故 $\overline{\left\{1\right\}}=\left\{1\right\}$.

(2) 由**定义 3.10 (豪斯多夫空间)**, 需看点 $0$ 与 $1$ 能否被不相交的邻域分离. 由**定义 3.25 (邻域与极限)**, $1$ 的邻域是含 $1$ 的开集, 而含 $1$ 的开集只有 $\left\{0,1\right\}$ (因 $\left\{1\right\}\notin\mathcal{O}$), 它同时含 $0$. 故不存在不相交的开集分别含 $0$ 与 $1$, $\left(X,\mathcal{O}\right)$ 不是豪斯多夫空间.

(3) 定义 $f:\left(X,\mathcal{O}\right)\to\left(X,\mathcal{O}'\right)$ 为 $f\left(0\right)=1$, $f\left(1\right)=0$. 则 $f$ 是双射. 验证 $f$ 连续: 由**定义 3.22 (连续映射)**, 需 $\mathcal{O}'$ 中每个开集的逆像是 $\mathcal{O}$ 中的开集. $\mathcal{O}'$ 的开集为 $\emptyset,\left\{1\right\},\left\{0,1\right\}$, 其逆像分别为 $\emptyset,\left\{0\right\},\left\{0,1\right\}$, 由**定义 3.18 (拓扑空间)** 均在 $\mathcal{O}$ 中, 故 $f$ 连续. 同理, $\mathcal{O}$ 的开集 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 在 $f^{-1}$ 下的逆像分别为 $\emptyset,\left\{1\right\},\left\{0,1\right\}$, 由**定义 3.22 (连续映射)** 均在 $\mathcal{O}'$ 中, 故 $f^{-1}$ 连续. 由**定义 3.23 (同胚)**, $f$ 是同胚, $\mathcal{O}$ 与 $\mathcal{O}'$ 同胚.

(4) 由**定义 3.25 (邻域与极限)**, 序列 $\left\{x_n\right\}$ 收敛到 $1$, 若含 $1$ 的每个邻域对所有充分大的 $n$ 都含 $x_n$. 由第 (2) 小题, 含 $1$ 的开集只有 $\left\{0,1\right\}=X$, 由**定义 3.25 (邻域与极限)** 它是 $1$ 的唯一邻域, 且 $X$ 含所有项. 故 $\left(X,\mathcal{O}\right)$ 中每个序列都收敛到 $1$.

(5) 由**定义 3.18 (拓扑空间)**, 含 $0$ 的开集为 $\left\{0\right\}$ 与 $\left\{0,1\right\}$, 故由**定义 3.25 (邻域与极限)**, $0$ 的邻域恰为含 $0$ 的开集. 序列收敛到 $0$, 当且仅当邻域 $\left\{0\right\}$ 对所有充分大的 $n$ 含 $x_n$, 即存在 $N$ 使 $n\ge{N}$ 时 $x_n=0$. 故收敛到 $0$ 的序列恰为从某项起恒为 $0$ 的序列.

(6) 取常值序列 $x_n=0$ (对所有 $n$). 由第 (4) 小题, 它收敛到 $1$; 由第 (5) 小题, 它从某项起恒为 $0$, 故也收敛到 $0$. 故 $x_n=0$ 既收敛到 $0$ 又收敛到 $1$.

(7) 设 $f:\left(X,\mathcal{O}\right)\to\left(X,\mathcal{O}\right)$ 连续. 由**定义 3.22 (连续映射)**, 对每个开集 $V\in\mathcal{O}$, $f^{-1}\left(V\right)$ 是 $\mathcal{O}$ 中的开集. 特别地, $f^{-1}\left(\left\{0\right\}\right)$ 是 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 之一 (由**定义 3.18 (拓扑空间)**).

(a) 若 $f^{-1}\left(\left\{0\right\}\right)=\emptyset$, 由原像的定义, 不存在 $x\in{X}$ 使 $f\left(x\right)=0$; 因 $f$ 的值域是 $\left\{0,1\right\}$, 故 $f\left(x\right)=1$ 对一切 $x$ 成立, 即 $f\equiv1$ (常值映射).

(b) 若 $f^{-1}\left(\left\{0\right\}\right)=\left\{0\right\}$, 由原像的定义, $f\left(0\right)=0$ 且 $f\left(1\right)\neq0$; 因值域是 $\left\{0,1\right\}$, 故 $f\left(1\right)=1$, 即 $f$ 为恒等映射.

(c) 若 $f^{-1}\left(\left\{0\right\}\right)=\left\{0,1\right\}$, 由原像的定义, 一切 $x$ 都满足 $f\left(x\right)=0$, 即 $f\equiv0$ (常值映射).

反之, 常值映射 $f\equiv0$ 与 $f\equiv1$ 及恒等映射都满足: 对 $\mathcal{O}$ 中每个开集 $V$, 其逆像 $f^{-1}\left(V\right)$ 是 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 之一, 由**定义 3.18 (拓扑空间)** 均为开集, 由**定义 3.22 (连续映射)** 故它们都连续. 因此从 $\left(X,\mathcal{O}\right)$ 到自身的连续映射恰为这三个. $\blacksquare$

> 看似未讨论 $f^{-1}\left(\emptyset\right)$ 与 $f^{-1}\left(\left\{0,1\right\}\right)$, 只讨论了 $f^{-1}\left(\left\{0\right\}\right)$; 实际上由原像保空集与全集, 恒有 $f^{-1}\left(\emptyset\right)=\emptyset$, $f^{-1}\left(\left\{0,1\right\}\right)=\left\{0,1\right\}$, 此为平凡情形故省略.

## 1.2 (由映射诱导的初始拓扑)
设 $f:X\to{Y}$ 是函数, 且 $Y$ 赋予一个拓扑 $\mathcal{O}$. 证明: 若 $\mathcal{O}_f=\left\{f^{-1}\left(O\right)\subset{X}:O\in\mathcal{O}\right\}$, 则 $\mathcal{O}_f$ 是 $X$ 上的拓扑; 且它是使 $f$ 连续的最粗拓扑. 上述拓扑称为由 $f$ 诱导的初始拓扑.

题集 §1.1 Q2.

### 解答 1.2

先证 $\mathcal{O}_f$ 是拓扑, 由**定义 3.18 (拓扑空间)** 逐条验证:

(1) 因 $Y\in\mathcal{O}$ 且由原像保空集与全集 $f^{-1}\left(Y\right)=X$, 由**定义 3.14 (初始拓扑)** 得 $X\in\mathcal{O}_f$; 因 $\emptyset\in\mathcal{O}$ 且 $f^{-1}\left(\emptyset\right)=\emptyset$, 由**定义 3.14 (初始拓扑)** 得 $\emptyset\in\mathcal{O}_f$.

(2) 设 $\left\{f^{-1}\left(O_\alpha\right)\right\}_{\alpha\in{A}}\subset\mathcal{O}_f$. 由原像与并运算交换, $\bigcup_{\alpha\in{A}}f^{-1}\left(O_\alpha\right)=f^{-1}\left(\bigcup_{\alpha\in{A}}O_\alpha\right)$. 因每个 $O_\alpha\in\mathcal{O}$ 且 $\mathcal{O}$ 是 $Y$ 上的拓扑, 由**定义 3.18 (拓扑空间)** (开集的任意并仍开) 得 $\bigcup_{\alpha\in{A}}O_\alpha\in\mathcal{O}$. 故 $f^{-1}\left(\bigcup_{\alpha\in{A}}O_\alpha\right)\in\mathcal{O}_f$, 即 $\bigcup_{\alpha\in{A}}f^{-1}\left(O_\alpha\right)\in\mathcal{O}_f$.

(3) 设 $f^{-1}\left(O_1\right),f^{-1}\left(O_2\right)\in\mathcal{O}_f$. 由原像与交运算交换, $f^{-1}\left(O_1\right)\cap{f}^{-1}\left(O_2\right)=f^{-1}\left(O_1\cap{O}_2\right)$. 由**定义 3.18 (拓扑空间)** (开集的有限交仍开) 得 $O_1\cap{O}_2\in\mathcal{O}$, 故 $f^{-1}\left(O_1\cap{O}_2\right)\in\mathcal{O}_f$.

故 $\mathcal{O}_f$ 是 $X$ 上的拓扑.

其次, $f$ 关于 $\mathcal{O}_f$ 连续: 对任意 $O\in\mathcal{O}$, 由**定义 3.14 (初始拓扑)** $f^{-1}\left(O\right)\in\mathcal{O}_f$ 是开集, 由**定义 3.22 (连续映射)** 即得 $f$ 连续. 最粗性: 设 $\tau$ 是 $X$ 上任意使 $f$ 连续的拓扑, 则对任意 $O\in\mathcal{O}$, 由**定义 3.22 (连续映射)** $f^{-1}\left(O\right)\in\tau$; 故 $\mathcal{O}_f\subset\tau$. 所以 $\mathcal{O}_f$ 是使 $f$ 连续的最粗拓扑. 由**定义 3.14 (初始拓扑)**, 它正是 $f$ 诱导的初始拓扑. $\blacksquare$

> 证明拓扑最粗的思路是: 证明该拓扑最小.

## 1.3 (拓扑之交仍是拓扑, 而并不必是拓扑)
证明: 给定一族拓扑 $\left\{\left(X,\mathcal{O}_\alpha\right)\right\}_{\alpha\in{A}}$, 它们的交集 (即 $X$ 的子集 $U$ 使得 $U$ 在每个 $\mathcal{O}_\alpha$ 中都是开的) 仍是拓扑. 论证将交集换成并集则不成立.

题集 §1.1 Q3.

### 解答 1.3

设 $\mathcal{O}=\bigcap_{\alpha\in{A}}\mathcal{O}_\alpha$. 由**定义 3.18 (拓扑空间)** 逐条验证:

(1) 对每个 $\alpha$, 由**定义 3.18 (拓扑空间)** $\emptyset,X\in\mathcal{O}_\alpha$, 故 $\emptyset,X\in\bigcap_{\alpha\in{A}}\mathcal{O}_\alpha=\mathcal{O}$.

(2) 设 $\left\{U_i\right\}_{i\in{I}}\subset\mathcal{O}$. 则对每个 $\alpha$ 与每个 $i$, $U_i\in\mathcal{O}_\alpha$. 因 $\mathcal{O}_\alpha$ 是拓扑, 由**定义 3.18 (拓扑空间)** (开集的任意并仍开) 故 $\bigcup_iU_i\in\mathcal{O}_\alpha$. 由 $\alpha$ 任意, $\bigcup_{i\in{I}}U_i\in\bigcap_{\alpha\in{A}}\mathcal{O}_\alpha=\mathcal{O}$.

(3) 设 $U,V\in\mathcal{O}$. 则对每个 $\alpha$, $U,V\in\mathcal{O}_\alpha$. 因 $\mathcal{O}_\alpha$ 是拓扑, 由**定义 3.18 (拓扑空间)** (开集的有限交仍开) 故 $U\cap{V}\in\mathcal{O}_\alpha$. 由 $\alpha$ 任意, 从而 $U\cap{V}\in\bigcap_{\alpha\in{A}}\mathcal{O}_\alpha=\mathcal{O}$.

故 $\mathcal{O}$ 是拓扑.

将交集换成并集不成立. 考虑 $X=\left\{0,1,2\right\}$, 取 $\mathcal{O}_1=\left\{\emptyset,\left\{0,1\right\},X\right\}$, $\mathcal{O}_2=\left\{\emptyset,\left\{1,2\right\},X\right\}$. 由**定义 3.18 (拓扑空间)** 直接验证, 两者都是拓扑 (都含 $\emptyset,X$, 且含于其中的有限交与任意并仍是空集, $X$ 或自身). 但 $\left\{0,1\right\}\in\mathcal{O}_1$, $\left\{1,2\right\}\in\mathcal{O}_2$, 其交 $\left\{1\right\}\notin\mathcal{O}_1\cup\mathcal{O}_2$; 由**定义 3.18 (拓扑空间)** 并集对有限交不封闭, 故不是拓扑. $\blacksquare$

> 在拓扑的 3 条公理中, 对有限交封闭这一性质最难保持.

## 1.4 ($\mathcal{O}_1$ 比 $\mathcal{O}_2$ 细的等价刻画)
证明下列是 "$\mathcal{O}_1$ 比 $\mathcal{O}_2$ 细" 的等价定义:

(1) $\mathcal{O}_2$ 的每个闭集在 $\mathcal{O}_1$ 中都是闭的;

(2) 恒等映射 $\left(E,\mathcal{O}_1\right)\to\left(E,\mathcal{O}_2\right)$ 连续;

(3) 对任意 $x\in{X}$, $\mathcal{O}_2$ 中 $x$ 的每个邻域都是 $\mathcal{O}_1$ 中 $x$ 的邻域.

题集 §1.1 Q4.

### 解答 1.4

由**定义 3.13 (细)**, "$\mathcal{O}_1$ 比 $\mathcal{O}_2$ 细" 即 $\mathcal{O}_2\subset\mathcal{O}_1$.

$\mathcal{O}_2\subset\mathcal{O}_1\Rightarrow$ (1): 设 $F$ 在 $\mathcal{O}_2$ 中闭. 由**定义 3.21 (闭集)**, $F^{c}\in\mathcal{O}_2$; 由**定义 3.13 (细)**, $F^{c}\in\mathcal{O}_1$; 再由**定义 3.21 (闭集)**, $F$ 在 $\mathcal{O}_1$ 中闭.

(1) $\Rightarrow$ (2): 对任意 $V\in\mathcal{O}_2$, 由**定义 3.21 (闭集)** 其补集 $V^{c}$ 在 $\mathcal{O}_2$ 中闭; 由假设 $V^{c}$ 在 $\mathcal{O}_1$ 中闭; 由**定义 3.21 (闭集)** 故 $V$ 在 $\mathcal{O}_1$ 中开. 恒等映射 $\operatorname{id}$ 的逆像 $\operatorname{id}^{-1}\left(V\right)=V$, 故 $V$ 在 $\mathcal{O}_1$ 中开. 由**定义 3.22 (连续映射)**, $\operatorname{id}$ 连续.

(2) $\Rightarrow$ (3): 由**定义 3.25 (邻域与极限)**, 设 $V$ 是 $x$ 在 $\mathcal{O}_2$ 中的邻域. 因 $\operatorname{id}$ 连续, 由**定义 3.22 (连续映射)** $V=\operatorname{id}^{-1}\left(V\right)\in\mathcal{O}_1$; 故由**定义 3.25 (邻域与极限)** $V$ 是 $x$ 在 $\mathcal{O}_1$ 中的邻域.

(3) $\Rightarrow\mathcal{O}_2\subset\mathcal{O}_1$: 由**定义 3.25 (邻域与极限)**, 设 $V$ 是 $x$ 在 $\mathcal{O}_2$ 中的邻域, 即 $V\in\mathcal{O}_2$; 由假设 $V$ 也是 $x$ 在 $\mathcal{O}_1$ 中的邻域, 即 $V\in\mathcal{O}_1$. 故 $\mathcal{O}_2\subset\mathcal{O}_1$. $\blacksquare$

## 1.5 (加细拓扑保持豪斯多夫性, 闭包, 内部与可分性)
设 $\left(X,\mathcal{O}_1\right)$ 比 $\left(X,\mathcal{O}_2\right)$ 细. 证明:

(1) 若 $\mathcal{O}_2$ 是豪斯多夫的, 则 $\mathcal{O}_1$ 也是豪斯多夫的;

(2) 对一切 $A\subset{X}$, 其在 $\mathcal{O}_1$ 中的闭包含于其在 $\mathcal{O}_2$ 中的闭包, 其在 $\mathcal{O}_2$ 中的内部含于其在 $\mathcal{O}_1$ 中的内部.

(3) 若 $\mathcal{O}_1$ 是可分的 (即含可数稠密子集), 则 $\mathcal{O}_2$ 也是可分的;

题集 §1.1 Q5.

### 解答 1.5

(1) 设 $x\neq{y}$. 因 $\mathcal{O}_2$ 是豪斯多夫的, 由**定义 3.10 (豪斯多夫空间)** 存在 $\mathcal{O}_2$ 中不相交的开集 $U,V$ 使 $x\in{U}$, $y\in{V}$. 由**定义 3.13 (细)** $\mathcal{O}_2\subset\mathcal{O}_1$, 故 $U,V\in\mathcal{O}_1$. 由**定义 3.10 (豪斯多夫空间)**, $\mathcal{O}_1$ 中也有不相交开集分离 $x,y$, 故 $\mathcal{O}_1$ 是豪斯多夫的.

(2) 固定 $A\subset{X}$. 由**定义 3.26 (闭包)**, $\overline{A}^{1}$ 是 $\mathcal{O}_1$ 中包含 $A$ 的最小闭集, $\overline{A}^{2}$ 是 $\mathcal{O}_2$ 中包含 $A$ 的最小闭集. 因 $\mathcal{O}_2\subset\mathcal{O}_1$, 任一 $\mathcal{O}_2$ 中闭集 $F$ (其补集 $\in\mathcal{O}_2\subset\mathcal{O}_1$) 也是 $\mathcal{O}_1$ 中闭集 (由**定义 3.21 (闭集)**). 特别地, $\overline{A}^{2}$ 是 $\mathcal{O}_1$ 中包含 $A$ 的一个闭集; 而 $\overline{A}^{1}$ 是 $\mathcal{O}_1$ 中包含 $A$ 的最小闭集, 故 $\overline{A}^{1}\subset\overline{A}^{2}$.

同理, 由**定义 3.31 (内部)**, $\operatorname{int}^{2}\left(A\right)$ 是 $\mathcal{O}_2$ 中含于 $A$ 的最大开集; 因 $\mathcal{O}_2\subset\mathcal{O}_1$, $\operatorname{int}^{2}\left(A\right)$ 在 $\mathcal{O}_1$ 中也开, 故 $\operatorname{int}^{2}\left(A\right)\subset\operatorname{int}^{1}\left(A\right)$.

(3) 由**定义 3.9 (可分)**, $\mathcal{O}_1$ 有可数稠密子集 $D$, 即由**定义 3.32 (稠密)** $\overline{D}^{1}=X$. 由第 (2) 小题, $\overline{D}^{1}\subset\overline{D}^{2}$, 故 $X\subset\overline{D}^{2}$, 即 $\overline{D}^{2}=X$. 由**定义 3.32 (稠密)**, $D$ 在 $\mathcal{O}_2$ 中稠密; 再由**定义 3.9 (可分)**, $\mathcal{O}_2$ 可分. $\blacksquare$

## 1.6 (对角线闭当且仅当空间豪斯多夫)
证明: $X$ 是豪斯多夫空间, 当且仅当对角线 $\Delta=\left\{\left(x,x\right):x\in{X}\right\}\subset{X}\times{X}$ 在 $X\times{X}$ 的乘积拓扑下是闭的.

题集 §1.1 Q6.

### 解答 1.6

$\left(\Rightarrow\right)$ 已知 $X$ 是豪斯多夫的, 证 $\Delta$ 闭, 即由**定义 3.21 (闭集)** 证其补集 $\left(X\times{X}\right)\setminus\Delta$ 开. 取 $\left(x,y\right)\notin\Delta$, 由**定义 3.12 (对角线)** 则 $x\neq{y}$. 由**定义 3.10 (豪斯多夫空间)**, 存在不相交开集 $U,V$ 使 $x\in{U}$, $y\in{V}$. 由**定义 3.11 (乘积拓扑)**, $U\times{V}$ 是乘积拓扑的开集; 且因 $U\cap{V}=\emptyset$, $U\times{V}\cap\Delta=\emptyset$, 故

$$
\left(x,y\right)\in{U}\times{V}\subset\left(X\times{X}\right)\setminus\Delta.
$$

故 $\left(X\times{X}\right)\setminus\Delta$ 每点都有开邻域含于其中, 由**定义 3.18 (拓扑空间)** 它是开集; 由**定义 3.21 (闭集)**, $\Delta$ 闭.

$\left(\Leftarrow\right)$ 已知 $\Delta$ 闭. 取 $x\neq{y}$, 由**定义 3.12 (对角线)** 则 $\left(x,y\right)\notin\Delta$. 由**定义 3.11 (乘积拓扑)**, 存在基本开集 $U\times{V}$ 使 $\left(x,y\right)\in{U}\times{V}\subset\left(X\times{X}\right)\setminus\Delta$, 其中 $U,V$ 为开集. 则 $x\in{U}$, $y\in{V}$, 且 $U\cap{V}=\emptyset$ (否则 $U\times{V}\cap\Delta\neq\emptyset$, 与含于 $\left(X\times{X}\right)\setminus\Delta$ 矛盾). 由**定义 3.10 (豪斯多夫空间)**, $X$ 是豪斯多夫的. $\blacksquare$

## 1.7 (子空间中闭集的刻画)
设 $\left(X,\mathcal{O}_X\right)$ 为拓扑空间, $A\subset{X}$, $\iota:A\to{X}$ 为包含映射; $A$ 的子空间拓扑规定 $U\subset{A}$ 开当且仅当存在 $X$ 中开集 $O$ 使 $U=O\cap{A}$. 证明: $F\subset{A}$ 在 $A$ 中闭, 当且仅当存在 $X$ 中闭集 $F'$ 使 $F=F'\cap{A}$.

题集 §1.2 Q1.

### 解答 1.7

($\Leftarrow$) 设存在 $X$ 中闭集 $F'$ 使 $F=F'\cap{A}$. 由**定义 3.21 (闭集)**, $X\setminus{F}'$ 是 $X$ 中开集. 由**定义 3.19 (子空间拓扑)**, $A\cap\left(X\setminus{F}'\right)$ 是 $A$ 中开集. 由集合运算恒等式, $A\setminus{F}=A\setminus\left(F'\cap{A}\right)=A\cap\left(X\setminus{F}'\right)$; 故 $A\setminus{F}$ 是 $A$ 中开集. 再由**定义 3.21 (闭集)**, $F$ 在 $A$ 中闭.

($\Rightarrow$) 设 $F$ 在 $A$ 中闭. 由**定义 3.21 (闭集)**, $A\setminus{F}$ 是 $A$ 中开集. 由**定义 3.19 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $A\setminus{F}=O\cap{A}$. 令 $F'=X\setminus{O}$, 则由**定义 3.21 (闭集)** $F'$ 是 $X$ 中闭集; 由集合运算恒等式, $F=A\setminus\left(O\cap{A}\right)=A\cap\left(X\setminus{O}\right)=F'\cap{A}$. 故存在 $X$ 中闭集 $F'$ 使 $F=F'\cap{A}$. $\blacksquare$

## 1.8 (拓扑基限制到子空间仍是基)
证明: 若 $\mathcal{B}$ 是 $X$ 的拓扑基, 则 $\left\{O\cap{A}:O\in\mathcal{B}\right\}$ 是 $A$ 的拓扑基.

题集 §1.2 Q2.

### 解答 1.8

记 $\mathcal{B}_A=\left\{U:=O\cap{A}:O\in\mathcal{B}\right\}$. 由**定义 3.15 (拓扑基)**, 需验证 $\mathcal{B}_A$ 满足两条:

(1) $A=\bigcup_{U\in\mathcal{B}_A}U$. 由**定义 3.15 (拓扑基)**, $X=\bigcup_{O\in\mathcal{B}}O$; 由交与并的分配律,

$$
A=A\cap{X}=A\cap\left(\bigcup_{O\in\mathcal{B}}O\right)=\bigcup_{O\in\mathcal{B}}\left(A\cap{O}\right)=\bigcup_{U\in\mathcal{B}_A}U.
$$

(2) 取 $O_1\cap{A},O_2\cap{A}\in\mathcal{B}_A$ 与 $x\in\left(O_1\cap{A}\right)\cap\left(O_2\cap{A}\right)=\left(O_1\cap{O}_2\right)\cap{A}$. 由**定义 3.15 (拓扑基)**, 存在 $O_3\in\mathcal{B}$ 使 $x\in{O}_3\subset{O}_1\cap{O}_2$. 则 $O_3\cap{A}\in\mathcal{B}_A$, 且

$$
x\in{O}_3\cap{A}\subset\left(O_1\cap{A}\right)\cap\left(O_2\cap{A}\right).
$$

由**定义 3.15 (拓扑基)**, $\mathcal{B}_A$ 满足基的两条刻画, 故 $\mathcal{B}_A$ 是 $A$ 的拓扑基. $\blacksquare$

## 1.9 (子空间的开集与闭集何时在原空间中开, 闭)
证明: $A$ 在 $X$ 中开 (闭), 当且仅当 $A$ 的每个开集 $U$ (闭集 $F$) 在 $X$ 中开 (闭).

题集 §1.2 Q3.

### 解答 1.9

先证开的情形.

($\Rightarrow$) 设 $A$ 在 $X$ 中开. 设 $U$ 是 $A$ 的开集. 由**定义 3.19 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $U=O\cap{A}$. 由**定义 3.18 (拓扑空间)**, $O$ 与 $A$ 都是 $X$ 中开集, 其有限交 $O\cap{A}=U$ 也是 $X$ 中开集.

($\Leftarrow$) 设 $A$ 的每个开集都是 $X$ 中开集. 由**定义 3.18 (拓扑空间)**, 全空间 $A$ 自身是 $A$ 中开集, 故由假设 $A$ 是 $X$ 中开集.

再证闭的情形.

($\Rightarrow$) 设 $A$ 在 $X$ 中闭. 设 $F$ 是 $A$ 的闭集. 由**习题 1.7**的结论, 存在 $X$ 中闭集 $F'$ 使 $F=F'\cap{A}$. 由**定义 3.21 (闭集)**, $X\setminus{F}'$ 与 $X\setminus{A}$ 都是 $X$ 中开集. 由**定义 3.18 (拓扑空间)**, 其并 $\left(X\setminus{F}'\right)\cup\left(X\setminus{A}\right)$ 是 $X$ 中开集. 由集合运算恒等式, $\left(X\setminus{F}'\right)\cup\left(X\setminus{A}\right)=X\setminus\left(F'\cap{A}\right)$; 故 $X\setminus{F}$ 是 $X$ 中开集. 由**定义 3.21 (闭集)**, $F$ 是 $X$ 中闭集.

($\Leftarrow$) 设 $A$ 的每个闭集都是 $X$ 中闭集. 由**定义 3.21 (闭集)**, 全空间 $A$ 自身是 $A$ 中闭集, 故由假设 $A$ 是 $X$ 中闭集. $\blacksquare$

## 1.10 (包含映射连续且诱导的初始拓扑恰为子空间拓扑)
证明: 包含映射 $\iota:A\to{X}$ 连续, 且子空间拓扑与 $\iota$ 诱导的初始拓扑相同.

题集 §1.2 Q4.

### 解答 1.10

对任意 $X$ 中开集 $O$, 由原像的定义, $\iota^{-1}\left(O\right)=\left\{a\in{A}:\iota\left(a\right)\in{O}\right\}$; 因 $\iota$ 是包含映射, $\iota\left(a\right)=a$, 故 $\left\{a\in{A}:a\in{O}\right\}=A\cap{O}$. 由**定义 3.19 (子空间拓扑)**, $\iota^{-1}\left(O\right)=O\cap{A}$ 恰为 $A$ 中的开集. 由**定义 3.22 (连续映射)**, 对每个 $X$ 中开集 $O$, $\iota^{-1}\left(O\right)$ 在 $A$ 中开, 故 $\iota$ 连续.

由**定义 3.14 (初始拓扑)**, $\iota$ 在 $A$ 上诱导的初始拓扑为 $\left\{\iota^{-1}\left(O\right):O\;\text{是}\;X\;\text{中开集}\right\}=\left\{O\cap{A}:O\;\text{是}\;X\;\text{中开集}\right\}$, 且该拓扑是使 $\iota$ 连续的最粗拓扑; 而**定义 3.19 (子空间拓扑)** 亦给出使 $\iota$ 连续的最粗拓扑, 故两者相同. $\blacksquare$

## 1.11 (子空间闭包的传递公式)
设 $A\subset{B}\subset{X}$, $B$ 装备 $X$ 诱导的子空间拓扑. 证明: $A$ 在 $B$ 中的闭包等于 $A$ 在 $X$ 中的闭包与 $B$ 的交.

题集 §1.2 Q5.

### 解答 1.11

记 $\overline{A}^{X}$ 为 $A$ 在 $X$ 中的闭包, $\overline{A}^{B}$ 为 $A$ 在 $B$ 中的闭包. 由**定义 3.26 (闭包)**, $\overline{A}^{B}$ 是 $B$ 中包含 $A$ 的最小闭集. 由**习题 1.7**, $B$ 中闭集恰为形如 $F'\cap{B}$ 的集合, 其中 $F'$ 是 $X$ 中闭集. 故 $B$ 中包含 $A$ 的闭集族恰为 $\left\{F'\cap{B}:F'\;\text{是}\;X\;\text{中闭集且}\;A\subset{F}'\right\}$.

先证 $\overline{A}^{B}\subset\overline{A}^{X}\cap{B}$. 由**定义 3.26 (闭包)**, $\overline{A}^{X}$ 是 $X$ 中包含 $A$ 的闭集, 故 $\overline{A}^{X}$ 是上式闭集族中一员, 其与 $B$ 的交 $\overline{A}^{X}\cap{B}$ 是 $B$ 中包含 $A$ 的闭集. 由**定义 3.26 (闭包)**, $\overline{A}^{B}$ 是其中最小者, 故 $\overline{A}^{B}\subset\overline{A}^{X}\cap{B}$.

再证反包含. 任取 $B$ 中包含 $A$ 的闭集 $F'\cap{B}$ (其中 $F'$ 是 $X$ 中闭集且 $A\subset{F}'$). 由**定义 3.26 (闭包)**, $\overline{A}^{X}\subset{F}'$, 故 $\overline{A}^{X}\cap{B}\subset{F}'\cap{B}$. 即 $\overline{A}^{X}\cap{B}$ 含于 $B$ 中每个包含 $A$ 的闭集, 特别地含于最小者 $\overline{A}^{B}$. 故 $\overline{A}^{B}\supset\overline{A}^{X}\cap{B}$. 综上 $\overline{A}^{B}=\overline{A}^{X}\cap{B}$. $\blacksquare$

## 1.12 (闭集在自身中稠密)
证明: 若 $A$ 等于 $A$ 在 $X$ 中的闭包, 则 $A$ 在 $A$ (装备 $A$ 上的诱导拓扑) 中稠密.

题集 §1.2 Q6.

### 解答 1.12

由题设 $A=\overline{A}^{X}$. 在**习题 1.11**的公式中取 $B=A$, 则 $A$ 在其自身子空间拓扑下的闭包为

$$
\overline{A}^{A}=\overline{A}^{X}\cap{A}=A\cap{A}=A.
$$

由**定义 3.32 (稠密)**, $A$ 在 $A$ 中稠密当且仅当其在 $A$ 中的闭包等于 $A$ 自身. 上式恰给出此条件, 故 $A$ 在 $A$ 中稠密. $\blacksquare$

## 1.13 (度量空间子空间的拓扑由限制度量给出)
证明: 若 $X$ 是带距离 $d$ 的度量空间, 则 $A$ 上的子空间拓扑也是度量拓扑, 其度量为 $d$ 在 $A$ 上的限制.

题集 §1.2 Q7.

### 解答 1.13

记 $d_A=d|_{A}$. 由**定义 6.35 (度量空间)**, $d:X\to\mathbb{R}_{\ge0}$ 满足四条度量公理; 限制 $d_A$ 在 $A$ 上逐点取值不变, 故同样满足这四条公理. 由**定义 6.35 (度量空间)**, $\left(A,d_A\right)$ 是度量空间.

由**定义 6.36 (开球)**, $A$ 中以 $a\in{A}$ 为心, 半径 $r>0$ 的开球为

$$
B_A\left(a,r\right)=\left\{y\in{A}:d_A\left(a,y\right)<{}r\right\}=A\cap\left\{y\in{X}:d\left(a,y\right)<{}r\right\}=A\cap{B}_X\left(a,r\right).
$$

由**定义 6.36 (开球)**, 开球族 $\left\{B_X\left(a,r\right)\right\}$ 是 $X$ 的一个拓扑基; 由**习题 1.8**, 它们与 $A$ 的交 $\left\{A\cap{B}_X\left(a,r\right)\right\}$ 是 $A$ 的拓扑基. 上式表明这恰是 $\left(A,d_A\right)$ 的开球族. 故 $A$ 上的子空间拓扑与 $d_A$ 诱导的度量拓扑一致. $\blacksquare$
