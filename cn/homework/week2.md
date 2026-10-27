# week2

> **基础知识: 原像的定义**<br>对函数 $f:X\to Y$ 与 $O\subset Y$, 原像为 $f^{-1}\left(O\right)=\left\{x\in X:f\left(x\right)\in O\right\}$.

> **基础知识: 集合运算恒等式**<br>对 $A,F'\subset X$, 有 $A\setminus F'=A\cap\left(X\setminus F'\right)$, $A\setminus\left(F'\cap A\right)=A\setminus F'$, 且 $X\setminus\left(F'\cap A\right)=\left(X\setminus F'\right)\cup\left(X\setminus A\right)$.

> **基础知识: 交与并的分配律**<br>对集合 $A$ 与集族 $\left\{B_\alpha\right\}_{\alpha\in A}$, 有 $A\cap\left(\bigcup_{\alpha\in A}B_\alpha\right)=\bigcup_{\alpha\in A}\left(A\cap B_\alpha\right)$.

> **基础知识: $\min$ 与加法**<br>对任意 $a,b\ge0$, 有 $\min\left(a+b,1\right)\le\min\left(a,1\right)+\min\left(b,1\right)$.

> **基础知识: 函数 $\varphi$ 的性质**<br>记 $\varphi\left(t\right)=\frac{t}{1+t}$, $t\ge0$. 则 $\varphi$ 在 $\left[0,\infty\right)$ 上严格递增, $\varphi\left(0\right)=0$, 且对任意 $a,b\ge0$ 有 $\varphi\left(a+b\right)\le\varphi\left(a\right)+\varphi\left(b\right)$.

> **基础知识: 分式恒等式**<br>对 $0<r<1$ 与 $d\ge0$, 有 $\frac{d}{1+d}<r$ 当且仅当 $d<\frac{r}{1-r}$.

> **定义 3.10 (豪斯多夫空间)**<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 §3, p20)

> **定义 3.14 (初始拓扑)**<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 §1.1)

> **定义 3.15 (拓扑基)**<br>设 $\mathcal B\subset\mathcal P\left(X\right)$. 若 $X=\bigcup_{B\in\mathcal B}B$, 且对任意 $B_1,B_2\in\mathcal B$ 与任意 $x\in B_1\cap B_2$ 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$, 则以 $\mathcal B$ 中元素的任意并为开集, 生成 $X$ 上最粗拓扑. (教材 §3, p13)

> **定义 3.18 (拓扑空间)**<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 §3, p12)

> **定义 3.19 (子空间拓扑)**<br>设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射. 称 $U\subset A$ 是开的, 若存在 $X$ 中开集 $O$ 使 $U=O\cap A$; 这些集合构成 $A$ 上的子空间拓扑, 它是使 $\iota$ 连续的最粗拓扑. (教材 §3, p17)

> **定义 3.21 (闭集)**<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 §3, p13)

> **定义 3.22 (连续映射)**<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 §3, p14)

> **定义 3.26 (闭包)**<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 §3, p18)

> **定义 3.32 (稠密)**<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 §3)

> **定义 6.33 (等价度量)**<br>两度量若诱导同一拓扑则称等价, 例如 $\min\left(d,1\right)$ 与 $d$. (题集 §1.3)

> **定义 6.34 (球面)**<br>以 $x$ 为心, 半径 $r$ 的球面为 $S\left(x,r\right)=\left\{y\in X:d\left(x,y\right)=r\right\}$. (题集 §1.3)

> **定义 6.35 (度量空间)**<br>度量 $d:X\times X\to\mathbb R_{\ge0}$ 满足:<br>(1) $d\left(x,x\right)=0$;<br>(2) 若 $d\left(x,y\right)=0$ 则 $x=y$;<br>(3) $d\left(x,y\right)=d\left(y,x\right)$;<br>(4) $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. 装备了度量 $d$ 的集合 $X$ 称为度量空间. (题集 §1.3 Q2; 教材 §6 由此给出度量拓扑)

> **定义 6.36 (开球)**<br>开球 $B\left(x,r\right)=\left\{y\in X:d\left(x,y\right)<r\right\}$. 全体开球构成度量拓扑的一个基. (教材 §6)

> **定义 6.45 (超度量)**<br>满足度量空间四条公理且三角不等式加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的度量. (题集 §1.3 Q2)

---

## 习题一

设 $\left(X,\mathcal O_X\right)$ 为拓扑空间, $A\subset X$, $\iota:A\to X$ 为包含映射; $A$ 的子空间拓扑规定 $U\subset A$ 开当且仅当存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 证明: $F\subset A$ 在 $A$ 中闭, 当且仅当存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$.

### 解答 习题一

**($\Leftarrow$)** 设存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. 由**定义 3.21 (闭集)**, $X\setminus F'$ 是 $X$ 中开集. 由**定义 3.19 (子空间拓扑)**, $A\cap\left(X\setminus F'\right)$ 是 $A$ 中开集. 由**基础知识: 集合运算恒等式**, $A\setminus\left(F'\cap A\right)=A\cap\left(X\setminus F'\right)$; 故 $A\setminus F$ 是 $A$ 中开集. 再由**定义 3.21 (闭集)**, $F$ 在 $A$ 中闭.

**($\Rightarrow$)** 设 $F$ 在 $A$ 中闭. 由**定义 3.21 (闭集)**, $A\setminus F$ 是 $A$ 中开集. 由**定义 3.19 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $A\setminus F=O\cap A$. 令 $F'=X\setminus O$, 则由**定义 3.21 (闭集)** $F'$ 是 $X$ 中闭集; 由**基础知识: 集合运算恒等式**, $F=A\setminus\left(O\cap A\right)=A\cap\left(X\setminus O\right)=F'\cap A$. 故存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. $\blacksquare$

---

## 习题二

证明: 若 $\mathcal B$ 是 $X$ 的拓扑基, 则 $\left\{O\cap A:O\in\mathcal B\right\}$ 是 $A$ 的拓扑基.

### 解答 习题二

记 $\mathcal B_A=\left\{O\cap A:O\in\mathcal B\right\}$. 由**定义 3.15 (拓扑基)**, 需验证 $\mathcal B_A$ 满足两条:

(1) $A=\bigcup_{U\in\mathcal B_A}U$. 由**定义 3.15 (拓扑基)**, $X=\bigcup_{O\in\mathcal B}O$; 由**基础知识: 交与并的分配律**,

$$
A=A\cap X=A\cap\left(\bigcup_{O\in\mathcal B}O\right)=\bigcup_{O\in\mathcal B}\left(A\cap O\right)=\bigcup_{U\in\mathcal B_A}U.
$$

(2) 取 $O_1\cap A,O_2\cap A\in\mathcal B_A$ 与 $x\in\left(O_1\cap A\right)\cap\left(O_2\cap A\right)=\left(O_1\cap O_2\right)\cap A$. 由**定义 3.15 (拓扑基)**, 存在 $O_3\in\mathcal B$ 使 $x\in O_3\subset O_1\cap O_2$. 则 $O_3\cap A\in\mathcal B_A$, 且

$$
x\in O_3\cap A\subset\left(O_1\cap A\right)\cap\left(O_2\cap A\right).
$$

由**定义 3.15 (拓扑基)**, $\mathcal B_A$ 满足基的两条刻画, 故 $\mathcal B_A$ 是 $A$ 的拓扑基. $\blacksquare$

---

## 习题三

证明: $A$ 在 $X$ 中开 (闭), 当且仅当 $A$ 的每个开集 (闭集) $U$ 在 $X$ 中开 (相应地, 闭).

### 解答 习题三

先证开的情形.

**($\Rightarrow$)** 设 $A$ 在 $X$ 中开. 设 $U$ 是 $A$ 的开集. 由**定义 3.19 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 由**定义 3.18 (拓扑空间)**, $O$ 与 $A$ 都是 $X$ 中开集, 其有限交 $O\cap A=U$ 也是 $X$ 中开集.

**($\Leftarrow$)** 设 $A$ 的每个开集都是 $X$ 中开集. 由**定义 3.18 (拓扑空间)**, 全空间 $A$ 自身是 $A$ 中开集, 故由假设 $A$ 是 $X$ 中开集.

再证闭的情形.

**($\Rightarrow$)** 设 $A$ 在 $X$ 中闭. 设 $F$ 是 $A$ 的闭集. 由**习题一**的结论, 存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. 由**定义 3.21 (闭集)**, $X\setminus F'$ 与 $X\setminus A$ 都是 $X$ 中开集. 由**定义 3.18 (拓扑空间)**, 其并 $\left(X\setminus F'\right)\cup\left(X\setminus A\right)$ 是 $X$ 中开集. 由**基础知识: 集合运算恒等式**, $\left(X\setminus F'\right)\cup\left(X\setminus A\right)=X\setminus\left(F'\cap A\right)$; 故 $X\setminus F$ 是 $X$ 中开集. 由**定义 3.21 (闭集)**, $F$ 是 $X$ 中闭集.

**($\Leftarrow$)** 设 $A$ 的每个闭集都是 $X$ 中闭集. 由**定义 3.21 (闭集)**, 全空间 $A$ 自身是 $A$ 中闭集, 故由假设 $A$ 是 $X$ 中闭集. $\blacksquare$

---

## 习题四

证明: 包含映射 $\iota:A\to X$ 连续, 且子空间拓扑与 $\iota$ 诱导的初始拓扑相同.

### 解答 习题四

对任意 $X$ 中开集 $O$, 由**基础知识: 原像的定义**, $\iota^{-1}\left(O\right)=\left\{a\in A:\iota\left(a\right)\in O\right\}$; 因 $\iota$ 是包含映射, $\iota\left(a\right)=a$, 故 $\left\{a\in A:a\in O\right\}=A\cap O=O\cap A$. 由**定义 3.19 (子空间拓扑)**, $\iota^{-1}\left(O\right)=O\cap A$ 恰为 $A$ 中的开集. 由**定义 3.22 (连续映射)**, 对每个 $X$ 中开集 $O$, $\iota^{-1}\left(O\right)$ 在 $A$ 中开, 故 $\iota$ 连续.

由**定义 3.14 (初始拓扑)**, $\iota$ 在 $A$ 上诱导的初始拓扑为 $\left\{\iota^{-1}\left(O\right):O\;\text{是}\;X\;\text{中开集}\right\}=\left\{O\cap A:O\;\text{是}\;X\;\text{中开集}\right\}$, 这恰是**定义 3.19 (子空间拓扑)** 给出的开集族. 又由**定义 3.14 (初始拓扑)**, 该拓扑是使 $\iota$ 连续的最粗拓扑; 而**定义 3.19 (子空间拓扑)** 亦给出使 $\iota$ 连续的最粗拓扑, 故两者相同. $\blacksquare$

---

## 习题五

设 $A\subset B\subset X$, $B$ 装备 $X$ 诱导的子空间拓扑. 证明: $A$ 在 $B$ 中的闭包等于 $A$ 在 $X$ 中的闭包与 $B$ 的交.

### 解答 习题五

记 $\overline A^{X}$ 为 $A$ 在 $X$ 中的闭包, $\overline A^{B}$ 为 $A$ 在 $B$ 中的闭包. 由**定义 3.26 (闭包)**, $\overline A^{B}$ 是 $B$ 中包含 $A$ 的最小闭集. 由**习题一**, $B$ 中闭集恰为形如 $F'\cap B$ 的集合, 其中 $F'$ 是 $X$ 中闭集. 故 $B$ 中包含 $A$ 的闭集族恰为 $\left\{F'\cap B:F'\;\text{是}\;X\;\text{中闭集且}\;A\subset F'\right\}$.

先证 $\overline A^{B}\subset\overline A^{X}\cap B$. 由**定义 3.26 (闭包)**, $\overline A^{X}$ 是 $X$ 中包含 $A$ 的闭集, 故 $\overline A^{X}$ 是上式闭集族中一员, 其与 $B$ 的交 $\overline A^{X}\cap B$ 是 $B$ 中包含 $A$ 的闭集. 由**定义 3.26 (闭包)**, $\overline A^{B}$ 是其中最小者, 故 $\overline A^{B}\subset\overline A^{X}\cap B$.

再证反包含. 任取 $B$ 中包含 $A$ 的闭集 $F'\cap B$ (其中 $F'$ 是 $X$ 中闭集且 $A\subset F'$). 由**定义 3.26 (闭包)**, $\overline A^{X}\subset F'$, 故 $\overline A^{X}\cap B\subset F'\cap B$. 即 $\overline A^{X}\cap B$ 含于 $B$ 中每个包含 $A$ 的闭集, 特别地含于最小者 $\overline A^{B}$. 故

$$
\overline A^{B}=\overline A^{X}\cap B.
$$

$\blacksquare$

---

## 习题六

证明: 若 $A$ 等于 $A$ 在 $X$ 中的闭包, 则 $A$ 在 $A$ (装备 $A$ 上的诱导拓扑) 中稠密.

### 解答 习题六

由题设 $A=\overline A^{X}$. 在**习题五**的公式中取 $B=A$, 则 $A$ 在其自身子空间拓扑下的闭包为

$$
\overline A^{A}=\overline A^{X}\cap A=A\cap A=A.
$$

由**定义 3.32 (稠密)**, $A$ 在 $A$ 中稠密当且仅当其在 $A$ 中的闭包等于 $A$ 自身. 上式恰给出此条件, 故 $A$ 在 $A$ 中稠密. $\blacksquare$

---

## 习题七

证明: 若 $X$ 是带距离 $d$ 的度量空间, 则 $A$ 上的子空间拓扑也是度量拓扑, 其度量为 $d$ 在 $A$ 上的限制.

### 解答 习题七

记 $d_A=d|_{A\times A}$. 由**定义 6.35 (度量空间)**, $d:X\times X\to\mathbb R_{\ge0}$ 满足四条度量公理; 限制 $d_A$ 在 $A\times A$ 上逐点取值不变, 故同样满足这四条公理. 由**定义 6.35 (度量空间)**, $\left(A,d_A\right)$ 是度量空间.

由**定义 6.36 (开球)**, $A$ 中以 $a\in A$ 为心, 半径 $r>0$ 的开球为

$$
B_A\left(a,r\right)=\left\{y\in A:d_A\left(a,y\right)<r\right\}=A\cap\left\{y\in X:d\left(a,y\right)<r\right\}=A\cap B_X\left(a,r\right).
$$

由**定义 6.36 (开球)**, 开球族 $\left\{B_X\left(a,r\right)\right\}$ 是 $X$ 的一个拓扑基; 由**习题二**, 它们与 $A$ 的交 $\left\{A\cap B_X\left(a,r\right)\right\}$ 是 $A$ 的拓扑基. 上式表明这恰是 $\left(A,d_A\right)$ 的开球族. 故 $A$ 上的子空间拓扑与 $d_A$ 诱导的度量拓扑一致. $\blacksquare$

---

## 习题八

证明: 若 $X$ 是豪斯多夫度量空间, 则装备诱导拓扑的 $A$ 也是豪斯多夫空间.

### 解答 习题八

任取 $x,y\in A$ 且 $x\neq y$. 由**定义 3.10 (豪斯多夫空间)**, 因 $X$ 是豪斯多夫的, 存在 $X$ 中不相交的开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.19 (子空间拓扑)**, $U\cap A$ 与 $V\cap A$ 都是 $A$ 中开集, 且 $x\in U\cap A$, $y\in V\cap A$. 又因 $U\cap V=\emptyset$, 故 $\left(U\cap A\right)\cap\left(V\cap A\right)=\emptyset$. 由**定义 3.10 (豪斯多夫空间)**, $A$ 中任意一对不同点都有不相交的邻域, 故 $A$ 是豪斯多夫空间. $\blacksquare$

---

## 习题九

构造例子: 子空间 $A\subset Y$ 是豪斯多夫的, 但 $A$ 中两点在 $Y$ 中没有不相交的邻域. 可考虑 $Y=X\cup\left\{\omega\right\}$, 其中 $\omega$ 是额外一点, $Y$ 的任一非空开集形如 $O\cup\left\{\omega\right\}$, 其中 $O$ 是 $X$ 中的开集.

### 解答 习题九

取 $X=\mathbb R$ 装备通常拓扑, 由**定义 3.10 (豪斯多夫空间)** 它是豪斯多夫的. 令 $Y=X\cup\left\{\omega\right\}$, 规定 $Y$ 的开集为 $\emptyset$ 与一切形如 $O\cup\left\{\omega\right\}$ 的集合, 其中 $O$ 取遍 $X$ 中开集. 验证这是 $Y$ 上的拓扑, 由**定义 3.18 (拓扑空间)** 逐条验证: $\emptyset$ 开 (题设); 取 $O=X$ 得 $Y=X\cup\left\{\omega\right\}$ 开. 任意并

$$
\bigcup_i\left(O_i\cup\left\{\omega\right\}\right)=\left(\bigcup_iO_i\right)\cup\left\{\omega\right\},
$$

由**定义 3.18 (拓扑空间)** $\bigcup_iO_i$ 是 $X$ 中开集, 故 $\left(\bigcup_iO_i\right)\cup\left\{\omega\right\}$ 是 $Y$ 中开集 (若 $\bigcup_iO_i=\emptyset$, 则并集为 $\emptyset$, 亦开). 有限交

$$
\left(O_1\cup\left\{\omega\right\}\right)\cap\left(O_2\cup\left\{\omega\right\}\right)=\left(O_1\cap O_2\right)\cup\left\{\omega\right\},
$$

同理由**定义 3.18 (拓扑空间)** 是 $Y$ 中开集. 故这确为 $Y$ 上的拓扑.

取 $A=X$ 作为 $Y$ 的子空间. 由**定义 3.19 (子空间拓扑)**, $A$ 中开集为 $\left(O\cup\left\{\omega\right\}\right)\cap A=O$, 即 $X$ 的通常开集, 故 $A$ 上的拓扑就是原来的通常拓扑, 由**定义 3.10 (豪斯多夫空间)** $A$ 是豪斯多夫的.

另一方面, 任取 $x,y\in A$ 且 $x\neq y$. $Y$ 中含 $x$ 的开集必非空, 故形如 $O\cup\left\{\omega\right\}$ 且 $x\in O$, 因而含 $\omega$; $Y$ 中含 $y$ 的开集同理形如 $O'\cup\left\{\omega\right\}$ 且 $y\in O'$, 亦含 $\omega$. 任何 $x$ 的邻域含某含 $x$ 的开集, 任何 $y$ 的邻域含某含 $y$ 的开集, 因而两邻域都含 $\omega$, 必相交. 故 $A$ 中任两点在 $Y$ 中没有不相交的邻域. $\blacksquare$

---

## 习题十

回忆距离 $d:X\times X\to\mathbb R_{\ge0}$ 满足四条公理: (1) $d\left(x,x\right)=0$; (2) 若 $d\left(x,y\right)=0$ 则 $x=y$; (3) $d\left(x,y\right)=d\left(y,x\right)$; (4) 三角不等式 $d\left(x,y\right)\le d\left(x,z\right)+d\left(z,y\right)$. $\left(X,d\right)$ 称为度量空间. 超度量是将第 (4) 条加强为 $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$ 的距离 (例如通常的 $p$-进度量). 设 $d$ 是超度量, 证明:

(1) 若 $d\left(x,y\right)\neq d\left(x,z\right)$, 则 $d\left(y,z\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)$;

(2) 开球中任一点都是该开球的中心;

(3) 开球中任一点都是由该开球所定球面的中心;

(4) 任意两个开球或者不相交, 或者一个含于另一个.

### 解答 习题十

由**定义 6.45 (超度量)**, 对任意 $x,y,z\in X$ 有

$$
d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right).
$$

(1) 设 $d\left(x,y\right)\neq d\left(x,z\right)$. 不妨设 $d\left(x,y\right)<d\left(x,z\right)$ (反号同理). 由上式, $d\left(x,z\right)\le\max\left(d\left(x,y\right),d\left(y,z\right)\right)$. 因右端 $\ge d\left(x,z\right)$ 而 $d\left(x,y\right)<d\left(x,z\right)$, 故 $\max\left(d\left(x,y\right),d\left(y,z\right)\right)=d\left(y,z\right)$, 且 $d\left(y,z\right)\ge d\left(x,z\right)$. 另一方面, 由**定义 6.45 (超度量)** 在基点 $y$ 处, $d\left(y,z\right)\le\max\left(d\left(y,x\right),d\left(x,z\right)\right)$; 因 $d\left(y,x\right)=d\left(x,y\right)<d\left(x,z\right)$, 故 $\max\left(d\left(y,x\right),d\left(x,z\right)\right)=d\left(x,z\right)$, 从而 $d\left(y,z\right)\le d\left(x,z\right)$. 合并得 $d\left(y,z\right)=d\left(x,z\right)=\max\left(d\left(x,y\right),d\left(x,z\right)\right)$.

(2) 设 $z\in B\left(x,r\right)$, 即由**定义 6.36 (开球)** $d\left(x,z\right)<r$. 任取 $w\in B\left(x,r\right)$, 即 $d\left(x,w\right)<r$. 由**定义 6.45 (超度量)**, $d\left(z,w\right)\le\max\left(d\left(z,x\right),d\left(x,w\right)\right)$; 因两项都 $<r$, 故 $d\left(z,w\right)<r$, 即 $w\in B\left(z,r\right)$. 于是 $B\left(x,r\right)\subset B\left(z,r\right)$. 反之, 任取 $w\in B\left(z,r\right)$, 即 $d\left(z,w\right)<r$. 由**定义 6.45 (超度量)**, $d\left(x,w\right)\le\max\left(d\left(x,z\right),d\left(z,w\right)\right)<r$, 故 $w\in B\left(x,r\right)$. 于是 $B\left(z,r\right)\subset B\left(x,r\right)$. 因此 $B\left(x,r\right)=B\left(z,r\right)$, 即 $z$ 也是该开球的中心.

(3) 由**定义 6.34 (球面)**, $S\left(x,r\right)=\left\{y:d\left(x,y\right)=r\right\}$. 设 $z\in B\left(x,r\right)$, 即 $d\left(x,z\right)<r$. 任取 $w\in S\left(x,r\right)$, 即 $d\left(x,w\right)=r$. 因 $d\left(x,z\right)<r=d\left(x,w\right)$, 故 $d\left(x,z\right)\neq d\left(x,w\right)$; 由第 (1) 小题, $d\left(z,w\right)=\max\left(d\left(x,z\right),d\left(x,w\right)\right)=r$, 故 $w\in S\left(z,r\right)$, 即 $S\left(x,r\right)\subset S\left(z,r\right)$. 反之, 任取 $w\in S\left(z,r\right)$, 即 $d\left(z,w\right)=r$. 因 $d\left(z,x\right)=d\left(x,z\right)<r=d\left(z,w\right)$, 对以 $z$ 为基点的三元组 $\left(z,x,w\right)$ 用第 (1) 小题, 得 $d\left(x,w\right)=\max\left(d\left(z,x\right),d\left(z,w\right)\right)=r$, 故 $w\in S\left(x,r\right)$, 即 $S\left(z,r\right)\subset S\left(x,r\right)$. 故 $S\left(x,r\right)=S\left(z,r\right)$, 即 $z$ 也是该球面的中心.

(4) 设 $B\left(x,r\right)$ 与 $B\left(y,s\right)$ 为两个开球. 若不相交则结论已成立. 若相交, 取 $z\in B\left(x,r\right)\cap B\left(y,s\right)$. 由第 (2) 小题, $B\left(x,r\right)=B\left(z,r\right)$ 且 $B\left(y,s\right)=B\left(z,s\right)$. 不妨设 $r\le s$. 若 $w\in B\left(z,r\right)$, 则由**定义 6.36 (开球)** $d\left(z,w\right)<r\le s$, 故 $w\in B\left(z,s\right)$. 因此 $B\left(z,r\right)\subset B\left(z,s\right)$, 即 $B\left(x,r\right)\subset B\left(y,s\right)$. $\blacksquare$

---

## 习题十一

设 $\left(X,d\right)$ 是度量空间. 证明 $d^{*}\left(x,y\right)=\min\left(d\left(x,y\right),1\right)$ 与 $d^{**}\left(x,y\right)=\frac{d\left(x,y\right)}{1+d\left(x,y\right)}$ 都是度量, 且与 $d$ 诱导同一拓扑. 注意有界性依赖于度量的选取, 而不依赖于拓扑.

### 解答 习题十一

先验证 $d^{*}$ 是度量, 由**定义 6.35 (度量空间)** 逐条:

(1) $d^{*}\left(x,x\right)=\min\left(0,1\right)=0$.

(2) 若 $d^{*}\left(x,y\right)=0$, 则 $\min\left(d\left(x,y\right),1\right)=0$, 故 $d\left(x,y\right)=0$; 由**定义 6.35 (度量空间)**, $x=y$.

(3) 由 $d\left(x,y\right)=d\left(y,x\right)$, $d^{*}\left(x,y\right)=\min\left(d\left(x,y\right),1\right)=\min\left(d\left(y,x\right),1\right)=d^{*}\left(y,x\right)$.

(4) 由**基础知识: $\min$ 与加法**, 对 $a,b\ge0$ 有 $\min\left(a+b,1\right)\le\min\left(a,1\right)+\min\left(b,1\right)$. 取 $a=d\left(x,y\right)$, $b=d\left(y,z\right)$, 由**定义 6.35 (度量空间)** 的三角不等式 $d\left(x,z\right)\le d\left(x,y\right)+d\left(y,z\right)$, 得 $d^{*}\left(x,z\right)\le d^{*}\left(x,y\right)+d^{*}\left(y,z\right)$. 故 $d^{*}$ 是度量.

再验证 $d^{**}$ 是度量. 记 $\varphi\left(t\right)=\frac{t}{1+t}$. 由**基础知识: 函数 $\varphi$ 的性质**, $\varphi$ 在 $\left[0,\infty\right)$ 上严格递增, $\varphi\left(0\right)=0$, 且对 $a,b\ge0$ 有 $\varphi\left(a+b\right)\le\varphi\left(a\right)+\varphi\left(b\right)$.

(1) $d^{**}\left(x,x\right)=\varphi\left(0\right)=0$.

(2) 若 $d^{**}\left(x,y\right)=0$, 则 $\varphi\left(d\left(x,y\right)\right)=0$; 由 $\varphi$ 严格递增与 $\varphi\left(0\right)=0$, $d\left(x,y\right)=0$; 由**定义 6.35 (度量空间)**, $x=y$.

(3) 由 $d\left(x,y\right)=d\left(y,x\right)$, $d^{**}\left(x,y\right)=\varphi\left(d\left(x,y\right)\right)=\varphi\left(d\left(y,x\right)\right)=d^{**}\left(y,x\right)$.

(4) 由**定义 6.35 (度量空间)** 的三角不等式与 $\varphi$ 递增, $d^{**}\left(x,z\right)=\varphi\left(d\left(x,z\right)\right)\le\varphi\left(d\left(x,y\right)+d\left(y,z\right)\right)$; 由**基础知识: 函数 $\varphi$ 的性质** $\varphi\left(a+b\right)\le\varphi\left(a\right)+\varphi\left(b\right)$, 得 $d^{**}\left(x,z\right)\le\varphi\left(d\left(x,y\right)\right)+\varphi\left(d\left(y,z\right)\right)=d^{**}\left(x,y\right)+d^{**}\left(y,z\right)$. 故 $d^{**}$ 是度量.

同一拓扑: 对 $0<r<1$, 由**定义 6.36 (开球)**, $B_{d^{*}}\left(x,r\right)=\left\{y:\min\left(d\left(x,y\right),1\right)<r\right\}$; 因 $r<1$, $\min\left(d\left(x,y\right),1\right)<r$ 当且仅当 $d\left(x,y\right)<r$, 故 $B_{d^{*}}\left(x,r\right)=\left\{y:d\left(x,y\right)<r\right\}=B_{d}\left(x,r\right)$. 而对 $d^{**}$, 半径 $r\in\left(0,1\right)$ 的球为 $B_{d^{**}}\left(x,r\right)=\left\{y:\frac{d\left(x,y\right)}{1+d\left(x,y\right)}<r\right\}$; 由**基础知识: 分式恒等式**, $\frac{d\left(x,y\right)}{1+d\left(x,y\right)}<r$ 当且仅当 $d\left(x,y\right)<\frac{r}{1-r}$, 故 $B_{d^{**}}\left(x,r\right)=\left\{y:d\left(x,y\right)<\frac{r}{1-r}\right\}=B_{d}\left(x,\frac{r}{1-r}\right)$.

故 $d^{*}$ 与 $d$ 的半径小于 $1$ 的球族完全相同, $d^{**}$ 的球与 $d$ 的球一一对应. 由**定义 6.36 (开球)**, 全体开球族是度量拓扑的基, 故三者生成同一拓扑. 由**定义 6.33 (等价度量)**, $d^{*}$ 与 $d^{**}$ 都与 $d$ 等价. $\blacksquare$
