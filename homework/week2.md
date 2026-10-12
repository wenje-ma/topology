# 作业 2

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.6** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$)

> **定义 3.8** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.10** (豪斯多夫 空间)<br>称 $X$ 是 豪斯多夫 的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.14** (初始拓扑)<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.15** (拓扑基)<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 $\S3$)

> **定义 3.19** (子空间拓扑)<br>设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 $\S3$)

> **定义 6.1** (度量空间)<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (教材 $\S6$)

> **定义 6.2** (开球)<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 $\S6$)

### 习题一

设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射; $A$ 的子空间拓扑规定 $U\subset A$ 开当且仅当存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 证明: $F\subset A$ 在 $A$ 中闭, 当且仅当存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$.

### 解答 习题一

**($\Leftarrow$)** 设存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. 由**定义 3.2** (闭集), $X\setminus F'$ 是 $X$ 中开集. 由**定义 3.19** (子空间拓扑), $A\cap\left(X\setminus F'\right)$ 是 $A$ 中开集. 由集合恒等式 $A\setminus\left(F'\cap A\right)=A\cap\left(X\setminus F'\right)$, 故 $A\setminus F$ 是 $A$ 中开集. 再由**定义 3.2** (闭集), $F$ 在 $A$ 中闭.

**($\Rightarrow$)** 设 $F$ 在 $A$ 中闭. 由**定义 3.2** (闭集), $A\setminus F$ 是 $A$ 中开集. 由**定义 3.19** (子空间拓扑), 存在 $X$ 中开集 $O$ 使 $A\setminus F=O\cap A$. 令 $F'=X\setminus O$, 则由**定义 3.2** (闭集) $F'$ 是 $X$ 中闭集, 且

$$
F=A\setminus\left(O\cap A\right)=A\cap\left(X\setminus O\right)=F'\cap A.
$$

故存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. $\blacksquare$

### 习题二

证明: 若 $\mathcal B$ 是 $X$ 的拓扑基, 则 $\left\{O\cap A:O\in\mathcal B\right\}$ 是 $A$ 的拓扑基.

### 解答 习题二

记 $\mathcal B_A=\left\{O\cap A:O\in\mathcal B\right\}$. 由**定义 3.15** (拓扑基), 需验证 $\mathcal B_A$ 满足两条:

(1) $A=\bigcup_{U\in\mathcal B_A}U$. 由**定义 3.15** (拓扑基), $X=\bigcup_{O\in\mathcal B}O$, 故

$$
A=A\cap X=A\cap\left(\bigcup_{O\in\mathcal B}O\right)=\bigcup_{O\in\mathcal B}\left(A\cap O\right)=\bigcup_{U\in\mathcal B_A}U.
$$

(2) 取 $O_1\cap A,O_2\cap A\in\mathcal B_A$ 与 $x\in\left(O_1\cap A\right)\cap\left(O_2\cap A\right)=\left(O_1\cap O_2\right)\cap A$. 由**定义 3.15** (拓扑基), 存在 $O_3\in\mathcal B$ 使 $x\in O_3\subset O_1\cap O_2$. 则 $O_3\cap A\in\mathcal B_A$, 且

$$
x\in O_3\cap A\subset\left(O_1\cap A\right)\cap\left(O_2\cap A\right).
$$

由**定义 3.15** (拓扑基), $\mathcal B_A$ 满足基的两条刻画, 故 $\mathcal B_A$ 是 $A$ 的拓扑基. $\blacksquare$

### 习题三

证明: $A$ 在 $X$ 中开 (相应地, 闭), 当且仅当 $A$ 的每个开集 (相应地, 闭集) $U$ 在 $X$ 中开 (相应地, 闭).

### 解答 习题三

先证开的情形.

**($\Rightarrow$)** 设 $A$ 在 $X$ 中开. 设 $U$ 是 $A$ 的开集. 由**定义 3.19** (子空间拓扑), 存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 由**定义 3.1** (拓扑空间), $O$ 与 $A$ 都是 $X$ 中开集, 其有限交 $O\cap A=U$ 也是 $X$ 中开集.

**($\Leftarrow$)** 设 $A$ 的每个开集都是 $X$ 中开集. 由**定义 3.1** (拓扑空间), 全空间 $A$ 自身是 $A$ 中开集, 故由假设 $A$ 是 $X$ 中开集.

再证闭的情形.

**($\Rightarrow$)** 设 $A$ 在 $X$ 中闭. 设 $F$ 是 $A$ 的闭集. 由**习题一**的结论, 存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. 由**定义 3.2** (闭集), 闭集的任意交仍闭 (其补集为开集的任意并), 故 $F'\cap A=F$ 是 $X$ 中闭集.

**($\Leftarrow$)** 设 $A$ 的每个闭集都是 $X$ 中闭集. 由**定义 3.2** (闭集), 全空间 $A$ 自身是 $A$ 中闭集, 故由假设 $A$ 是 $X$ 中闭集. $\blacksquare$

### 习题四

证明: 包含映射 $\iota:A\to X$ 连续, 且子空间拓扑与 $\iota$ 诱导的初始拓扑相同.

### 解答 习题四

对任意 $X$ 中开集 $O$, $\iota^{-1}\left(O\right)=\left\{a\in A:\iota\left(a\right)\in O\right\}=A\cap O=O\cap A$. 由**定义 3.19** (子空间拓扑), $\iota^{-1}\left(O\right)=O\cap A$ 恰为 $A$ 中的开集. 由**定义 3.3** (连续映射), 对每个 $X$ 中开集 $O$, $\iota^{-1}\left(O\right)$ 在 $A$ 中开, 故 $\iota$ 连续.

由**定义 3.14** (初始拓扑), $\iota$ 在 $A$ 上诱导的初始拓扑为 $\left\{\iota^{-1}\left(O\right):O\text{ 是 }X\text{ 中开集}\right\}=\left\{O\cap A:O\text{ 是 }X\text{ 中开集}\right\}$, 这恰是**定义 3.19** (子空间拓扑) 给出的开集族. 又由**定义 3.14** (初始拓扑), 该拓扑是使 $\iota$ 连续的最粗拓扑; 而**定义 3.19** (子空间拓扑) 亦给出使 $\iota$ 连续的最粗拓扑, 故两者相同. $\blacksquare$

### 习题五

设 $A\subset B\subset X$, $B$ 装备 $X$ 诱导的子空间拓扑. 证明: $A$ 在 $B$ 中的闭包等于 $A$ 在 $X$ 中的闭包与 $B$ 的交.

### 解答 习题五

记 $\overline A^{X}$ 为 $A$ 在 $X$ 中的闭包, $\overline A^{B}$ 为 $A$ 在 $B$ 中的闭包. 由**定义 3.6** (闭包), $\overline A^{B}$ 是 $B$ 中包含 $A$ 的最小闭集. 由**习题一**, $B$ 中闭集恰为形如 $F'\cap B$ 的集合, 其中 $F'$ 是 $X$ 中闭集. 故 $B$ 中包含 $A$ 的闭集族恰为 $\left\{F'\cap B:F'\text{ 是 }X\text{ 中闭集且 }A\subset F'\right\}$.

先证 $\overline A^{X}\cap B\subset\overline A^{B}$. 由**定义 3.6** (闭包), $\overline A^{X}$ 是 $X$ 中包含 $A$ 的闭集, 故 $\overline A^{X}$ 是上式闭集族中一员, 其与 $B$ 的交 $\overline A^{X}\cap B$ 是 $B$ 中包含 $A$ 的闭集. 由**定义 3.6** (闭包), $\overline A^{B}$ 是其中最小者, 故 $\overline A^{X}\cap B\supset\overline A^{B}$.

再证反包含. 任取 $B$ 中包含 $A$ 的闭集 $F'\cap B$ (其中 $F'$ 是 $X$ 中闭集且 $A\subset F'$). 由**定义 3.6** (闭包), $\overline A^{X}\subset F'$, 故 $\overline A^{X}\cap B\subset F'\cap B$. 即 $\overline A^{X}\cap B$ 含于 $B$ 中每个包含 $A$ 的闭集, 特别地含于最小者 $\overline A^{B}$. 故

$$
\overline A^{B}=\overline A^{X}\cap B.
$$

$\blacksquare$

### 习题六

证明: 若 $A$ 等于 $A$ 在 $X$ 中的闭包, 则 $A$ 在 $A$ (装备 $A$ 上的诱导拓扑) 中稠密.

### 解答 习题六

由题设 $A=\overline A^{X}$. 在**习题五**的公式中取 $B=A$, 则 $A$ 在其自身子空间拓扑下的闭包为

$$
\overline A^{A}=\overline A^{X}\cap A=A\cap A=A.
$$

由**定义 3.8** (稠密), $A$ 在 $A$ 中稠密当且仅当其在 $A$ 中的闭包等于 $A$ 自身. 上式恰给出此条件, 故 $A$ 在 $A$ 中稠密. $\blacksquare$

### 习题七

证明: 若 $X$ 是带距离 $d$ 的度量空间, 则 $A$ 上的子空间拓扑也是度量拓扑, 其度量为 $d$ 在 $A$ 上的限制.

### 解答 习题七

记 $d_A=d|_{A\times A}$. 由**定义 6.1** (度量空间), $d:X\times X\to\mathbb R_{\ge0}$ 满足四条度量公理; 限制 $d_A$ 在 $A\times A$ 上逐点取值不变, 故同样满足这四条公理. 由**定义 6.1** (度量空间), $\left(A,d_A\right)$ 是度量空间.

由**定义 6.2** (开球), $A$ 中以 $a\in A$ 为心、半径 $r>0$ 的开球为

$$
B_A\left(a,r\right)=\left\{y\in A:d_A\left(a,y\right)<r\right\}=A\cap\left\{y\in X:d\left(a,y\right)<r\right\}=A\cap B_X\left(a,r\right).
$$

由**定义 6.2** (开球), 开球族 $\left\{B_X\left(a,r\right)\right\}$ 是 $X$ 的一个拓扑基; 由**习题二**, 它们与 $A$ 的交 $\left\{A\cap B_X\left(a,r\right)\right\}$ 是 $A$ 的拓扑基. 上式表明这恰是 $\left(A,d_A\right)$ 的开球族. 故 $A$ 上的子空间拓扑与 $d_A$ 诱导的度量拓扑一致. $\blacksquare$

### 习题八

证明: 若 $X$ 是豪斯多夫度量空间, 则装备诱导拓扑的 $A$ 也是豪斯多夫空间.

### 解答 习题八

任取 $x,y\in A$ 且 $x\neq y$. 由**定义 3.10** (豪斯多夫 空间), 因 $X$ 是豪斯多夫 的, 存在 $X$ 中不相交的开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.19** (子空间拓扑), $U\cap A$ 与 $V\cap A$ 都是 $A$ 中开集, 且 $x\in U\cap A$, $y\in V\cap A$. 又因 $U\cap V=\emptyset$, 故 $\left(U\cap A\right)\cap\left(V\cap A\right)=\emptyset$. 由**定义 3.10** (豪斯多夫 空间), $A$ 中任意一对不同点都有不相交的邻域, 故 $A$ 是 豪斯多夫 空间. $\blacksquare$

### 习题九

构造例子: 子空间 $A\subset Y$ 是 豪斯多夫 的, 但 $A$ 中两点在 $Y$ 中没有不相交的邻域. 可考虑 $Y=X\cup\left\{\omega\right\}$, 其中 $\omega$ 是额外一点, $Y$ 的任一非空开集形如 $O\cup\left\{\omega\right\}$, 其中 $O$ 是 $X$ 中的开集.

### 解答 习题九

取 $X=\mathbb R$ 装备通常拓扑, 由**定义 3.10** (豪斯多夫 空间) 它是 豪斯多夫 的. 令 $Y=X\cup\left\{\omega\right\}$, 规定 $Y$ 的开集为 $\emptyset$ 与一切形如 $O\cup\left\{\omega\right\}$ 的集合, 其中 $O$ 取遍 $X$ 中开集. 验证这是 $Y$ 上的拓扑: $\emptyset$ 开; 取 $O=X$ 得 $Y=X\cup\left\{\omega\right\}$ 开; 任意并

$$
\bigcup_i\left(O_i\cup\left\{\omega\right\}\right)=\left(\bigcup_iO_i\right)\cup\left\{\omega\right\},
$$

由**定义 3.1** (拓扑空间) $\bigcup_iO_i$ 是 $X$ 中开集, 故它是 $Y$ 中非空开集; 有限交

$$
\left(O_1\cup\left\{\omega\right\}\right)\cap\left(O_2\cup\left\{\omega\right\}\right)=\left(O_1\cap O_2\right)\cup\left\{\omega\right\},
$$

同理由**定义 3.1** (拓扑空间) 是 $Y$ 中开集. 故这确为 $Y$ 上的拓扑.

取 $A=X$ 作为 $Y$ 的子空间. 由**定义 3.19** (子空间拓扑), $A$ 中开集为 $\left(O\cup\left\{\omega\right\}\right)\cap A=O$, 即 $X$ 的通常开集, 故 $A$ 上的拓扑就是原来的通常拓扑, 由**定义 3.10** (豪斯多夫 空间) $A$ 是 豪斯多夫 的.

另一方面, 任取 $x,y\in A$ 且 $x\neq y$. $Y$ 中含 $x$ 的开集必非空, 故形如 $O\cup\left\{\omega\right\}$ 且 $x\in O$, 因而含 $\omega$; $Y$ 中含 $y$ 的开集同理形如 $O'\cup\left\{\omega\right\}$ 且 $y\in O'$, 亦含 $\omega$. 任何 $x$ 的邻域含某含 $x$ 的开集, 任何 $y$ 的邻域含某含 $y$ 的开集, 因而两邻域都含 $\omega$, 必相交. 故 $A$ 中任两点在 $Y$ 中没有不相交的邻域. $\blacksquare$
