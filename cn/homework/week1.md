# 作业 1

> **定义 3.9** (可分)<br>称拓扑空间 $X$ 是可分的, 若它有可数稠密子集. (题集 $\S1.1$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. 此时极限是唯一的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 3.12** (对角线)<br>集合 $\Delta=\left\{\left(x,x\right):x\in X\right\}\subset X\times X$ 称为对角线. (题集 $\S1.1$)

> **定义 3.13** (细)<br>称 $\mathcal O_1$ 比 $\mathcal O_2$ 细, 若 $\mathcal O_2\subset\mathcal O_1$. (题集 $\S1.1$)

> **定义 3.14** (初始拓扑)<br>设 $f:X\to Y$ 是函数, 且 $Y$ 赋予拓扑 $\mathcal O$. 称 $\mathcal O_f=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 为 $X$ 上由 $f$ 诱导的**初始拓扑**; 它是使 $f$ 连续的最粗拓扑. (题集 $\S1.1$)

> **定义 3.18** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$. 即 $U\subset X$ 是开的当且仅当 $U\in T$. 我们要求:<br>(1) $\emptyset,X\in T$;<br>(2) 若 $U,V\in T$, 则 $U\cap V\in T$;<br>(3) 若 $A\subset T$, 则 $\bigcup A\in T$. (教材 $\S3$)

> **定义 3.21** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $X\setminus F$ 是开的. (教材 $\S3$)

> **定义 3.22** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.23** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续. 这等价于说: $U$ 是开的当且仅当 $f\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.25** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. 我们称 $a_n\to b$, 若对 $b$ 的任何邻域 $U$, 对所有充分大的 $n$ 都有 $a_n\in U$. (教材 $\S3$)

> **定义 3.26** (闭包)<br>集合 $A\subset X$ 的闭包 $\overline A$ 就是包含 $A$ 的最小闭集; 它存在, 因为闭集的交集仍是闭的. (教材 $\S3$)

> **定义 3.31** (内部)<br>类似地, $A$ 的内部 $\operatorname{int}\left(A\right)$ 是含于 $A$ 的最大开集. (教材 $\S3$)

> **定义 3.32** (稠密)<br>我们称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

### 习题一

考虑谢尔宾斯基空间, 其中 $X=\left\{0,1\right\}$, $\mathcal O=\left\{\emptyset,\left\{0\right\},\left\{0,1\right\}\right\}$.

(1) 计算 $\left\{1\right\}$ 的闭包;

(2) 问 $\left(X,\mathcal O\right)$ 是否是豪斯多夫空间;

(3) 考虑 $\mathcal O'=\left\{\emptyset,\left\{1\right\},\left\{0,1\right\}\right\}
$ 通过构造一个连续映射 $f:\left(X,\mathcal O\right)\to\left(X,\mathcal O'\right)$, 证明 $\mathcal O$ 与 $\mathcal O'$ 是同胚的;

(4) 证明 $\left(X,\mathcal O\right)$ 中所有序列都收敛到 $1$;

(5) 描述 $\left(X,\mathcal O\right)$ 中收敛到 $0$ 的序列所成的集合;

(6) 构造一个既收敛到 $0$ 又收敛到 $1$ 的序列;

(7) 证明从 $\left(X,\mathcal O\right)$ 到自身的连续映射恰有三个.

### 解答 习题一

(1) 由**定义 3.18** (拓扑空间), $\mathcal O$ 的开集为 $\emptyset,\left\{0\right\},\left\{0,1\right\}$. 由**定义 3.21** (闭集), 闭集是开集的补集, 故 $\mathcal O$ 的闭集为 $X,\left\{1\right\},\emptyset$. 因 $\left\{1\right\}$ 是闭集, 由**定义 3.26** (闭包) 其为包含 $\left\{1\right\}$ 的最小闭集, 故

$$
\overline{\left\{1\right\}}=\left\{1\right\}.
$$

(2) 由**定义 3.10** (豪斯多夫空间), (不妨) 需看点 $0$ 与 $1$ 能否被不相交的邻域分离. 由**定义 3.25** (邻域与极限), $1$ 的邻域是含 $1$ 的开集, 而含 $1$ 的开集只有 $\left\{0,1\right\}$ (因 $\left\{1\right\}\notin\mathcal O$), 它同时含 $0$. 故不存在不相交的开集分别含 $0$ 与 $1$, $\left(X,\mathcal O\right)$ **不是**豪斯多夫空间.

(3) 定义 $f:\left(X,\mathcal O\right)\to\left(X,\mathcal O'\right)$ 为 $f\left(0\right)=1$, $f\left(1\right)=0$. $f$ 是双射. 验证 $f$ 连续: 由**定义 3.22** (连续映射), 需 $\mathcal O'$ 中开集的逆像是 $\mathcal O$ 中的开集. $\mathcal O'$ 中开集为 $\emptyset,\left\{1\right\},\left\{0,1\right\}$, 其逆像分别为 $\emptyset,\left\{0\right\},\left\{0,1\right\}$, 由**定义 3.18** (拓扑空间) 均在 $\mathcal O$ 中, 故 $f$ 连续. 同理, $\mathcal O$ 中开集 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 在 $f^{-1}$ 下的逆像分别为 $\emptyset,\left\{1\right\},\left\{0,1\right\}$, 均在 $\mathcal O'$ 中, 故由**定义 3.22** (连续映射) $f^{-1}$ 连续. 由**定义 3.23** (同胚), $f$ 是同胚, $\mathcal O$ 与 $\mathcal O'$ 同胚.

(4) 由**定义 3.25** (邻域与极限), 序列 $\left\{x_n\right\}$ 收敛到 $1$, 若含 $1$ 的每个邻域对所有充分大的 $n$ 都含 $x_n$. 由第 2 小题, 含 $1$ 的开集只有 $\left\{0,1\right\}=X$, 由**定义 3.25** (邻域与极限) 它是 $1$ 的唯一邻域, 且 $X$ 含所有项. 故 $\left(X,\mathcal O\right)$ 中**每个**序列都收敛到 $1$.

(5) 由**定义 3.18** (拓扑空间), 含 $0$ 的开集为 $\left\{0\right\}$ 与 $\left\{0,1\right\}$, 故由**定义 3.25** (邻域与极限), $0$ 的邻域恰为含 $\left\{0\right\}$ 或 $\left\{0,1\right\}$ 的开集. 序列收敛到 $0$, 当且仅当邻域 $\left\{0\right\}$ 对所有充分大的 $n$ 含 $x_n$, 即存在 $N$ 使 $n\ge N$ 时 $x_n=0$. 故收敛到 $0$ 的序列恰为**从某项起恒为 $0$** 的序列.

(6) 取常值序列 $x_n=0$ (对所有 $n$). 由第 4 小题, 它收敛到 $1$; 由第 5 小题, 它从某项起恒为 $0$, 故也收敛到 $0$. 故 $x_n=0$ 既收敛到 $0$ 又收敛到 $1$.

(7) 设 $f:\left(X,\mathcal O\right)\to\left(X,\mathcal O\right)$ 连续. 由**定义 3.22** (连续映射), 对每个开集 $V\in\mathcal O$, $f^{-1}\left(V\right)$ 是 $\mathcal O$ 中的开集. 特别地, $f^{-1}\left(\left\{0\right\}\right)$ 是 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 之一 (由**定义 3.18** (拓扑空间)).

(a) 若 $f^{-1}\left(\left\{0\right\}\right)=\emptyset$, 则 $f$ 不取值 $0$, 即 $f\equiv1$ (常值映射);

(b) 若 $f^{-1}\left(\left\{0\right\}\right)=\left\{0\right\}$, 则 $f\left(0\right)=0$ 且 $f\left(1\right)\neq0$, 故 $f\left(1\right)=1$, 即 $f$ 为恒等映射;

(c) 若 $f^{-1}\left(\left\{0\right\}\right)=\left\{0,1\right\}$, 则 $f\equiv0$ (常值映射).

反之, 常值映射 $f\equiv0$ 与 $f\equiv1$ 及恒等映射都满足: 对 $\mathcal O$ 中每个开集 $V$, 其逆像 $f^{-1}\left(V\right)$ 是 $\emptyset,\left\{0\right\},\left\{0,1\right\}$ 之一, 由**定义 3.18** (拓扑空间) 均为开集, 由**定义 3.22** (连续映射) 故它们都连续. 因此从 $\left(X,\mathcal O\right)$ 到自身的连续映射恰为这三个. $\blacksquare$

> 看似我们未讨论 $f^{-1}\left(\emptyset\right)$ 与 $f^{-1}\left(\left\{0,1\right\}\right)$, 只讨论了 $f^{-1}\left(\left\{0\right\}\right)$, 但实际上我们永远有 $f^{-1}\left(\emptyset\right)\equiv\emptyset$, $f^{-1}\left(\left\{0,1\right\}\right)\equiv\left\{0,1\right\}$, 因此其为平凡情形故省略.

### 习题二

设 $f:X\to Y$ 是函数, 且 $Y$ 赋予一个拓扑 $\mathcal O$. 证明: 若 $\mathcal O_f=\left\{f^{-1}\left(O\right)\subset X:O\in\mathcal O\right\}$, 则 $\mathcal O_f$ 是 $X$ 上的拓扑; 且它是使 $f$ 连续的最粗拓扑. 上述拓扑称为由 $f$ 诱导的初始拓扑.

### 解答 习题二

先证 $\mathcal O_f$ 是拓扑, 由**定义 3.18** (拓扑空间) 逐条验证:

(1) 因 $Y\in\mathcal O$ 且 $f^{-1}\left(Y\right)=X$, 由**定义 3.14** (初始拓扑) 得 $X\in\mathcal O_f$; 因 $\emptyset\in\mathcal O$ 且 $f^{-1}\left(\emptyset\right)=\emptyset$, 由**定义 3.14** (初始拓扑) 得 $\emptyset\in\mathcal O_f$.

(2) 设 $\left\{f^{-1}\left(O_\alpha\right)\right\}_{\alpha\in A}\subset\mathcal O_f$. 由原像与并运算交换 $f^{-1}\left(\bigcup_\alpha O_\alpha\right)=\bigcup_\alpha f^{-1}\left(O_\alpha\right)$, 且由**定义 3.18** (拓扑空间) $Y$ 中开集的任意并仍开, 故

$$
\bigcup_{\alpha\in A}f^{-1}\left(O_\alpha\right)=f^{-1}\left(\bigcup_{\alpha\in A}O_\alpha\right)\in\mathcal O_f.
$$

(3) 设 $f^{-1}\left(O_1\right),f^{-1}\left(O_2\right)\in\mathcal O_f$. 由原像与交运算交换及**定义 3.18** (拓扑空间) 中开集的有限交仍开,

$$
f^{-1}\left(O_1\right)\cap f^{-1}\left(O_2\right)=f^{-1}\left(O_1\cap O_2\right)\in\mathcal O_f.
$$

故 $\mathcal O_f$ 是 $X$ 上的拓扑.

其次, $f$ 关于 $\mathcal O_f$ 连续: 对任意 $O\in\mathcal O$, $f^{-1}\left(O\right)\in\mathcal O_f$ 是开集, 由**定义 3.22** (连续映射) 即得 $f$ 连续. 最粗性: 设 $\tau$ 是 $X$ 上任意使 $f$ 连续的拓扑, 则对任意 $O\in\mathcal O$, 由**定义 3.22** (连续映射) $f^{-1}\left(O\right)\in\tau$, 故 $\mathcal O_f\subset\tau$. 所以 $\mathcal O_f$ 是使 $f$ 连续的最粗拓扑. 由**定义 3.14** (初始拓扑), 它正是 $f$ 诱导的初始拓扑. $\blacksquare$

> 证明拓扑最粗的思路是: 证明该拓扑最小.

### 习题三

证明: 给定一族拓扑 $\left\{\left(X,\mathcal O_\alpha\right)\right\}_{\alpha\in A}$, 它们的交集 (即 $X$ 的子集 $U$ 使得 $U$ 在每个 $\mathcal O_\alpha$ 中都是开的) 仍是拓扑. 论证将交集换成并集则不成立.

### 解答 习题三

设 $\mathcal O=\bigcap_{\alpha\in A}\mathcal O_\alpha$. 由**定义 3.18** (拓扑空间) 逐条验证:

(1) 对每个 $\alpha$, 由**定义 3.18** (拓扑空间) $\emptyset,X\in\mathcal O_\alpha$, 故 $\emptyset,X\in\mathcal O$.

(2) 设 $\left\{U_i\right\}_{i\in I}\subset\mathcal O$. 则对每个 $\alpha$ 与每个 $i$, $U_i\in\mathcal O_\alpha$; 因 $\mathcal O_\alpha$ 是拓扑, 由**定义 3.18** (拓扑空间) 故 $\bigcup_i U_i\in\mathcal O_\alpha$. 由 $\alpha$ 任意,

$$
\bigcup_{i\in I}U_i\in\bigcap_{\alpha\in A}\mathcal O_\alpha=\mathcal O.
$$

(3) 设 $U,V\in\mathcal O$. 则对每个 $\alpha$, $U,V\in\mathcal O_\alpha$, 由**定义 3.18** (拓扑空间) 故 $U\cap V\in\mathcal O_\alpha$, 从而 $U\cap V\in\mathcal O$.

故 $\mathcal O$ 是拓扑.

将交集换成并集不成立. 考虑 $X=\left\{0,1,2\right\}$, 取 $\mathcal O_1=\left\{\emptyset,X,\left\{0,1\right\}\right\}$, $\mathcal O_2=\left\{\emptyset,X,\left\{1,2\right\}\right\}$. 由**定义 3.18** (拓扑空间) 直接验证, 两者都是拓扑 (都含 $\emptyset,X$, 且含于其中的有限交与任意并仍是空集、$X$ 或自身). 但并集中 $\left\{0,1\right\}$ 与 $\left\{1,2\right\}$ 的交 $\left\{1\right\}$ 不在并集中, 由**定义 3.18** (拓扑空间) 并集对有限交不封闭, 故不是拓扑. $\blacksquare$

> 在拓扑的 3 条公理中, 对有限交封闭这一性质最难保持, 因此反例的寻找策略就是找两个拓扑 $\mathcal O_1$, $\mathcal O_2$, 使得存在 $U\in\mathcal O_1$, $V\in\mathcal O_2$, 但是 $U\cap V\not\in\mathcal O_1 \cup\mathcal O_2$.

### 习题四

证明下列是 "$\mathcal O_1$ 比 $\mathcal O_2$ 细" 的等价定义:

(1) $\mathcal O_2$ 的每个闭集在 $\mathcal O_1$ 中都是闭的;

(2) 恒等映射 $\left(E,\mathcal O_1\right)\to\left(E,\mathcal O_2\right)$ 连续;

(3) 对任意 $x\in X$, $\mathcal O_2$ 中 $x$ 的每个邻域都是 $\mathcal O_1$ 中 $x$ 的邻域.

### 解答 习题四

由**定义 3.13** (细), "$\mathcal O_1$ 比 $\mathcal O_2$ 细" 即 $\mathcal O_2\subset\mathcal O_1$. 我们证明链条 $\mathcal O_2\subset\mathcal O_1\Rightarrow$ (1) $\Rightarrow$ (2) $\Rightarrow$ (3) $\Rightarrow\mathcal O_2\subset\mathcal O_1$, 从而三者都与细等价.

**$\mathcal O_2\subset\mathcal O_1\Rightarrow$ (1)**: 设 $F$ 在 $\mathcal O_2$ 中闭. 由**定义 3.21** (闭集), $F^{c}\in\mathcal O_2$; 由**定义 3.13** (细), $F^{c}\in\mathcal O_1$, 再由**定义 3.21** (闭集) $F$ 在 $\mathcal O_1$ 中闭.

**(1) $\Rightarrow$ (2)**: 对任意 $V\in\mathcal O_2$, 由**定义 3.21** (闭集) 其补集 $V^{c}$ 在 $\mathcal O_2$ 中闭, 由假设在 $\mathcal O_1$ 中闭, 再由**定义 3.21** (闭集) $V$ 在 $\mathcal O_1$ 中开. 而恒等映射 $\operatorname{id}$ 的逆像 $\operatorname{id}^{-1}\left(V\right)=V$, 故 $V$ 在 $\mathcal O_1$ 中开. 由**定义 3.22** (连续映射), $\operatorname{id}$ 连续.

**(2) $\Rightarrow$ (3)**: 设 $N$ 是 $x$ 在 $\mathcal O_2$ 中的邻域. 由**定义 3.25** (邻域与极限), 存在 $V\in\mathcal O_2$ 使 $x\in V\subset N$. 因 $\operatorname{id}$ 连续, 由**定义 3.22** (连续映射) $V=\operatorname{id}^{-1}\left(V\right)\in\mathcal O_1$, 故 $N$ 含 $\mathcal O_1$ 中的开集 $V$, 由**定义 3.25** (邻域与极限) $N$ 是 $x$ 在 $\mathcal O_1$ 中的邻域.

**(3) $\Rightarrow\mathcal O_2\subset\mathcal O_1$**: 设 $V\in\mathcal O_2$. 任取 $x\in V$, 由**定义 3.25** (邻域与极限) $V$ 是 $x$ 在 $\mathcal O_2$ 中的邻域, 由假设也是 $x$ 在 $\mathcal O_1$ 中的邻域, 故存在 $U_x\in\mathcal O_1$ 使 $x\in U_x\subset V$. 于是 $V=\bigcup_{x\in V}U_x$, 由**定义 3.18** (拓扑空间) $V\in\mathcal O_1$. 故 $\mathcal O_2\subset\mathcal O_1$. $\blacksquare$

### 习题五

设 $\left(X,\mathcal O_1\right)$ 比 $\left(X,\mathcal O_2\right)$ 细. 证明:

(1) 若 $\mathcal O_2$ 是豪斯多夫的, 则 $\mathcal O_1$ 也是豪斯多夫的;

(2) 若 $\mathcal O_1$ 是可分的 (即含可数稠密子集), 则 $\mathcal O_2$ 也是可分的;

(3) 对一切 $A\subset X$, 其在 $\mathcal O_1$ 中的闭包含于其在 $\mathcal O_2$ 中的闭包, 其在 $\mathcal O_2$ 中的内部含于其在 $\mathcal O_1$ 中的内部.

### 解答 习题五

因第 2 小题要用到第 3 小题的闭包包含关系, 故先证第 1、3 小题, 再证第 2 小题.

**第 1 小题**: 设 $x\neq y$. 因 $\mathcal O_2$ 是豪斯多夫的, 由**定义 3.10** (豪斯多夫空间) 存在 $\mathcal O_2$ 中不相交的开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.13** (细) $\mathcal O_2\subset\mathcal O_1$, 故 $U,V\in\mathcal O_1$. 由**定义 3.10** (豪斯多夫空间), $\mathcal O_1$ 中也有不相交开集分离 $x,y$, $\mathcal O_1$ 是豪斯多夫的.

**第 3 小题**: 固定 $A\subset X$. 由**定义 3.26** (闭包), $\overline A^{1}$ 是 $\mathcal O_1$ 中包含 $A$ 的最小闭集, $\overline A^{2}$ 是 $\mathcal O_2$ 中包含 $A$ 的最小闭集. 因 $\mathcal O_2\subset\mathcal O_1$, $\mathcal O_1$ 中闭集多于 $\mathcal O_2$ 中闭集, 故 $\overline A^{1}$ (它是 $\mathcal O_1$ 中闭集, 由**定义 3.21** (闭集) 也是 $\mathcal O_2$ 中闭集) 是 $\mathcal O_2$ 中包含 $A$ 的一个闭集, 不小于最小的 $\overline A^{2}$:

$$
\overline A^{1}\subset\overline A^{2}.
$$

同理, 由**定义 3.31** (内部), $\operatorname{int}^{2}\left(A\right)$ 是 $\mathcal O_2$ 中含于 $A$ 的最大开集, 而 $\mathcal O_2\subset\mathcal O_1$ 使它在 $\mathcal O_1$ 中也开, 故

$$
\operatorname{int}^{2}\left(A\right)\subset\operatorname{int}^{1}\left(A\right).
$$

**第 2 小题**: 由**定义 3.9** (可分), $\mathcal O_1$ 有可数稠密子集 $D$, 即由**定义 3.32** (稠密) $\overline D^{1}=X$. 由第 3 小题, $\overline D^{1}\subset\overline D^{2}$, 故 $X\subset\overline D^{2}$, 即 $\overline D^{2}=X$. 由**定义 3.32** (稠密), $D$ 在 $\mathcal O_2$ 中稠密, 再由**定义 3.9** (可分) $\mathcal O_2$ 可分. $\blacksquare$

### 习题六

证明: $X$ 是豪斯多夫空间, 当且仅当对角线 $\Delta=\left\{\left(x,x\right):x\in X\right\}\subset X\times X$ 在 $X\times X$ 的乘积拓扑下是闭的.

### 解答 习题六

**$\left(\Rightarrow\right)$** 已知 $X$ 是豪斯多夫的, 证 $\Delta$ 闭, 即由**定义 3.21** (闭集) 证其补集 $\left(X\times X\right)\setminus\Delta$ 开. 取 $\left(x,y\right)\notin\Delta$, 由**定义 3.12** (对角线) 则 $x\neq y$. 由**定义 3.10** (豪斯多夫空间), 存在不相交开集 $U,V$ 使 $x\in U$, $y\in V$. 由**定义 3.11** (乘积拓扑), $U\times V$ 是乘积拓扑的开集, 且因 $U\cap V=\emptyset$, $U\times V\cap\Delta=\emptyset$, 即

$$
\left(x,y\right)\in U\times V\subset\left(X\times X\right)\setminus\Delta.
$$

故 $\left(X\times X\right)\setminus\Delta$ 每点都有开邻域含于其中, 由**定义 3.18** (拓扑空间) 它是开集, 由**定义 3.21** (闭集) $\Delta$ 闭.

**$\left(\Leftarrow\right)$** 已知 $\Delta$ 闭. 取 $x\neq y$, 由**定义 3.12** (对角线) 则 $\left(x,y\right)\notin\Delta$, 故存在乘积拓扑开集 $W$ 使 $\left(x,y\right)\in W\subset\left(X\times X\right)\setminus\Delta$. 由**定义 3.11** (乘积拓扑), $W$ 是若干基本开集之并, 故存在基本开集 $U\times V$ 使 $\left(x,y\right)\in U\times V\subset W\subset\left(X\times X\right)\setminus\Delta$, 其中 $U,V$ 为开集. 则 $x\in U$, $y\in V$ 且 $U\cap V=\emptyset$ (否则 $U\times V\cap\Delta\neq\emptyset$, 与含于 $\left(X\times X\right)\setminus\Delta$ 矛盾). 由**定义 3.10** (豪斯多夫空间), $X$ 是豪斯多夫的. $\blacksquare$
