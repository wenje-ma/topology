# 作业 1

> **定义 1.1** (开集)<br>$U\subset\mathbb R$ 是开集, 若 $U$ 是开区间 (或空集) 的并 $U=\bigcup_\alpha I_\alpha$.

> **注 1.A** (开集之可数表示)<br>任意开集实为**可数个**开区间的并 (每个开区间内取一个有理数作下标).

> **定义 1.2** (邻域)<br>$U$ 是点 $x$ 的**邻域**, 若存在开集 $O$ 使 $x\in O\subset U$. 邻域不必是开集, 邻域变大仍是邻域.

> **命题 1.3** (开集的邻域刻画)<br>$U$ 是开集, 当且仅当 $U$ 是它每一点的邻域: $U\text{ 开}\Leftrightarrow\forall x\in U,\,U\text{ 是 }x\text{ 的邻域}$.

> **定义 1.4** (闭集)<br>$F\subset\mathbb R$ 是**闭集**, 若 $F^{c}=\mathbb R\setminus F$ 是开集.

> **注 1.B** (开集之交)<br>开集的任意并保持开, 但交不一定: 有限个开集的交仍开, 无限个未必, 例如 $\bigcap_{n\ge1}\left(-\frac1n,\frac1n\right)=\left\{0\right\}$ 不是开集.

> **命题 1.6** (闭集的极限刻画)<br>$F$ 是闭集, 当且仅当 $F$ 中任何收敛数列的极限仍属于 $F$.

> **定义 2.2** (开球与度量拓扑)<br>$B\left(x,r\right)=\left\{y:d\left(x,y\right)<r\right\}$; 规定 $U$ 开, 若对每个 $x\in U$ 存在 $r>0$ 使 $B\left(x,r\right)\subset U$. 开球构成其一组基.

> **定义 3.1** (连续)<br>$f:\left(X,\mathcal O_X\right)\to\left(Y,\mathcal O_Y\right)$ **连续**, 若任意开集 $V$ 的原像 $f^{-1}\left(V\right)$ 是开集.

> **定义 3.4** (原像/拉回)<br>$f^{-1}\left(Y\right)=\left\{x\in E:f\left(x\right)\in Y\right\}$. 拉回保持交, 并, 包含; 直接像一般不保持.

> **定义 3.5** (同胚)<br>$f$ 是**同胚**, 若连续双射且 $f^{-1}$ 连续, 等价 $U$ 开 $\Leftrightarrow f\left(U\right)$ 开.

> **定义 4.1** (拓扑)<br>$X$ 为集合, $\mathcal O\subset2^{X}$ 满足: $\varnothing,X\in\mathcal O$; 任意并封闭; 有限交封闭. 称 $\left(X,\mathcal O\right)$ 为拓扑空间, $\mathcal O$ 为拓扑.

> **定义 4.2** (闭集)<br>$F$ 闭 $\Leftrightarrow F^{c}$ 开. 闭集族对任意交, 有限并封闭.

> **定义 4.4** (粗细)<br>$\mathcal O\subset\mathcal O'$ 时称 $\mathcal O$ 比 $\mathcal O'$ **更细 (更精密)**; 反之更粗糙.

> **定义 5.1** (收敛, 邻域语言)<br>$a_n\to b$, 若 $b$ 的每个邻域 $U$ 都含 $a_n$ 对一切足够大的 $n$.

> **例 5.2** (cofinite 拓扑)<br>$A$ 闭 $\Leftrightarrow A$ 有限或 $A=X$ (开＝补有限). $X$ 无限时任何无限序列收敛到一切点.

> **0922 §6** (闭包, 内部, 边界, 极限点, 孤立点)<br>设 $X$ 拓扑空间, $A\subset X$:<br>(i) $x\in\overline A\Leftrightarrow x$ 的每个邻域 $U$ 都使 $U\cap A\neq\varnothing$; $\overline A$ 是最小的包含 $A$ 的闭集;<br>(ii) $x\in\operatorname{Int}A\Leftrightarrow$ 存在开集 $U$ 使 $x\in U\subset A$, 即 $A$ 是 $x$ 的邻域; $\operatorname{Int}A$ 是最大的含于 $A$ 的开集;<br>(iii) $x\in\partial A=\overline A\setminus\operatorname{Int}A\Leftrightarrow x$ 的每个邻域 $U$ 都使 $U\cap A\neq\varnothing$ 且 $U\cap A^{c}\neq\varnothing$;<br>(iv) $x$ 是 $A$ 的极限点 (聚点) $\Leftrightarrow x$ 的每个邻域 $U$ 都含 $A$ 中异于 $x$ 的点, 即 $U\cap\left(A\setminus\left\{x\right\}\right)\neq\varnothing$;<br>(v) $x\in A$ 孤立 $\Leftrightarrow$ 存在邻域 $U$ 使 $U\cap A=\left\{x\right\}$.

> **例 6.1** (序列不够用; 历年 C7)<br>$X=\mathbb R$ 可数补拓扑: $U$ 开 $\Leftrightarrow U=\varnothing$ 或 $U^{c}$ 可数. 此时闭集＝可数集 (及 $\mathbb R$).

> **例 6.2** (闭包依赖拓扑)<br>可数补拓扑下 $B=\left(-1,1\right)$ (不可数) 的闭包 $\overline{\left(-1,1\right)}=\mathbb R$, 且没有 $B$ 中序列收敛到 $2$.

> **定义 7.2** (基, 并生成版本)<br>设 $\left(X,\mathcal O\right)$ 拓扑空间, $\mathcal B\subset\mathcal O$. 若任意开集都能写成 $\mathcal B$ 中元素的并, 则称 $\mathcal B$ 是拓扑的基.

> **命题 7.3** (基判定开集)<br>$O$ 是开集, 当且仅当对任意 $x\in O$, 存在 $B_x\in\mathcal B$ 使 $x\in B_x\subset O$.

> **命题 7.4** (充分公理)<br>$\mathcal B\subset2^{X}$ 能作为某拓扑的基, 只要 (1) 覆盖 $X=\bigcup\mathcal B$; (2) 交性质: 若 $x\in B_1\cap B_2$, 则存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$. 此时 $\mathcal B$ 元素之并构成含 $\mathcal B$ 的最小拓扑.

> **证明 7.A** (命题 7.3 ⇔ 定义 7.2)<br>($\Rightarrow$) $O=\bigcup_\beta B_\beta$, 取含 $x$ 的 $B_\beta$; ($\Leftarrow$) $O=\bigcup_{x\in O}B_x$ 是基元素之并.

> **证明 7.B** (命题 7.4 ⇒ 确为一个拓扑)<br>记 $\mathcal O=\left\{O:O\text{ 为 }\mathcal B\text{ 元素之并}\right\}$. $\varnothing,X\in\mathcal O$ (覆盖); 任意并仍是 $\mathcal B$ 元素之并; 有限交由交性质 $\ x\in B_3\subset B_1\cap B_2\subset O\cap O'$ 保证.

> **命题 7.5** (一族子集生成的拓扑)<br>给定 $\mathcal S\subset2^{X}$, 所有含 $\mathcal S$ 的拓扑之交仍是拓扑, 即由 $\mathcal S$ 生成的拓扑, 为含 $\mathcal S$ 的最小拓扑. 其基可用 $\mathcal S$ 元素的有限交给出.

> **例 8.1** (生成与最小: 线性空间类比)<br>包含向量 $v_1,v_2,v_3$ 的子空间有两个等价构造: 生成 (取所有线性组合); 最小 (取所有含它们的子空间之交). 拓扑同理 (**命题 7.5**).

> **定义 9.1** (子空间拓扑)<br>$\mathcal O_A=\left\{U\cap A:U\in\mathcal O\right\}$ 是 $A$ 上的拓扑, 即包含映射 $\iota:A\to X$ 诱导的初始拓扑.

> **定义 10.1** (初始/拉回拓扑)<br>设 $f:X\to\left(Y,\mathcal O_Y\right)$. 在 $X$ 上使 $f$ 连续的最小拓扑为 $\mathcal O_X=\left\{f^{-1}\left(V\right):V\in\mathcal O_Y\right\}$.

> **定义 10.2** (最终/商拓扑)<br>对满射 $\pi:X\to Y$, 在 $Y$ 上使 $\pi$ 连续的最大拓扑 $\mathcal O_Y=\left\{V\subset Y:\pi^{-1}\left(V\right)\text{ 是开集}\right\}$.

> **定义 13.1** (分离性)<br>T1: 单点集是闭集; T2 (Hausdorff): 任意两个不同点有不相交的开邻域.

> **注 13.B** (可分与导集)<br>有可数稠密子集的空间称**可分 (separable)**.

> **定义 14.1** (Zariski 闭集)<br>$\mathbb A^{n}\left(K\right)=K^{n}$. $F$ 是 Zariski 闭集, 若 $F=\left\{x\in\mathbb A^{n}:P_i\left(x\right)=0,\forall i\in I\right\}$ (一族多项式的公共零点集).

> **命题 14.2** (Zariski 确为拓扑)<br>多项式公共零点对任意交, 有限并封闭, 故以这些闭集定义的 Zariski 拓扑确为拓扑; 它非 Hausdorff, 且 Zariski 开集在通常拓扑下稠密.

> **定义 15.1** (基数的序)<br>设 $A,B$ 为集合. $\left|A\right|\le\left|B\right|$, 若存在单射 $A\to B$; $\left|A\right|=\left|B\right|$, 若存在双射.

> **基础知识**<br>(1) **选择公理 (AC)**: 对任意非空集族 $\left\{B_\alpha\right\}$, 存在选择函数从每个 $B_\alpha$ 中各取一元; 据此可对满射 $g:B\to A$ 的每个纤维 $g^{-1}\left(a\right)$ 各选一个代表元;<br>(2) **集合运算 (德摩根律, 原像/直接像)**: $f^{-1}\left(\bigcup V_\alpha\right)=\bigcup f^{-1}\left(V_\alpha\right)$, $f^{-1}\left(\bigcap V_\alpha\right)=\bigcap f^{-1}\left(V_\alpha\right)$; 直接像仅保持并 $f\left(\bigcup A_\alpha\right)=\bigcup f\left(A_\alpha\right)$, 一般不保持交;<br>(3) **实数完备性 (上确界原理)**: $\mathbb R$ 中任意有上界的非空集有上确界; 由此有初等事实: 一个开区间不能被两个非空不交开子集之并覆盖 (若 $\left(a,b\right)=U\sqcup V$, $U,V$ 非空开, 取 $c=\sup\left(U\cap\left(a,b\right)\right)$, 由开性推出 $c$ 既不能落在 $U$ 也不能落在 $V$, 矛盾);<br>(4) **模算术与数论**: $S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\}$ 即模 $a$ 余 $b$ 的整数类; 任一 $\left|n\right|\ge2$ 的整数有素因子; 有限个闭集之并仍闭 (**定义 4.2**).

## 1

课堂作业①. 设 $A,B$ 为集合, 且 $A\neq\varnothing$.

(1) 证明 $\left|A\right|\le\left|A\right|$;

(2) 在选择公理下, 证明 $\left|B\right|\ge\left|A\right|$ 等价于存在满射 $g:B\to A$ (即满射与单射在选择公理下可互化).

### 解答 1

(1) 按**定义 15.1 (基数的序)**, $\left|A\right|\le\left|A\right|$ 即要构造一个单射 $A\to A$. 若 $A=\varnothing$, 空映射是单射, 空集上一切性质 vacuously 成立; 若 $A\neq\varnothing$, 取恒等映射 $\operatorname{id}_A:A\to A$, $\operatorname{id}_A\left(x\right)=x$, 它显然是单射. 故 $\left|A\right|\le\left|A\right|$. $\blacksquare$

(2) 由**定义 15.1**, $\left|B\right|\ge\left|A\right|$ 即 $\left|A\right|\le\left|B\right|$, 亦即存在单射 $i:A\to B$. 下面证明它与"存在满射 $g:B\to A$"在选择公理下等价.

($\Leftarrow$) 设存在满射 $g:B\to A$. 对每个 $a\in A$, 纤维 $g^{-1}\left(a\right)\subset B$ 非空 (因 $g$ 满). 依**基础知识 (选择公理)**, 从每个 $g^{-1}\left(a\right)$ 中各选一元 $b_a$, 定义 $i:A\to B$, $i\left(a\right)=b_a$. 若 $a_1\neq a_2$, 则 $g\left(b_{a_1}\right)=a_1\neq a_2=g\left(b_{a_2}\right)$, 故 $b_{a_1}\neq b_{a_2}$, 即 $i$ 是单射. 于是 $\left|A\right|\le\left|B\right|$.

($\Rightarrow$) 设存在单射 $i:A\to B$. 由 $A\neq\varnothing$, 可取定 $a_0\in A$. 定义 $g:B\to A$:

$$
g\left(b\right)=\begin{cases}i^{-1}\left(b\right),& b\in i\left(A\right),\\ a_0,& b\notin i\left(A\right).\end{cases}
$$

因 $i$ 单射, $i^{-1}:i\left(A\right)\to A$ 是良定义的映射. 对任意 $a\in A$, $i\left(a\right)\in i\left(A\right)$, 故 $g\left(i\left(a\right)\right)=i^{-1}\left(i\left(a\right)\right)=a$, 即 $g$ 是满射.

两方向结合即得 $\left|B\right|\ge\left|A\right|\,\Leftrightarrow\,$存在满射 $g:B\to A$ (后者用到选择公理). $\blacksquare$

## 2

课堂作业②. 在 $\mathbb R$ 的通常 (欧氏) 拓扑下, 把**内点, 孤立点, 边界点, 聚点 (极限点)** 这四个概念, 用普通的 (对称开区间) 邻域各改写一遍.

### 解答 2

在通常拓扑下, 由**定义 1.2 (邻域)** 与**定义 2.2 (开球与度量拓扑)**, 点 $x$ 的邻域就是含某个对称开区间 $\left(x-\delta,x+\delta\right)$ ($\delta>0$) 的集合; 而由**命题 1.3 (开集的邻域刻画)**, "存在开邻域"等价于"存在这种对称开区间". 对照 **0922 §6** 的邻域定义, 改写如下.

**内点.** $x\in\operatorname{Int}A$: 存在 $\delta>0$, 使

$$
\left(x-\delta,x+\delta\right)\subset A.
$$

**孤立点.** $x\in A$ 是孤立点: 存在 $\delta>0$, 使

$$
\left(x-\delta,x+\delta\right)\cap A=\left\{x\right\}.
$$

**边界点.** $x\in\partial A$: 对任意 $\delta>0$, 都同时有

$$
\left(x-\delta,x+\delta\right)\cap A\neq\varnothing,\qquad\left(x-\delta,x+\delta\right)\cap A^{c}\neq\varnothing.
$$

**聚点 (极限点).** $x$ 是 $A$ 的聚点: 对任意 $\delta>0$, 都有

$$
\left(x-\delta,x+\delta\right)\cap\left(A\setminus\left\{x\right\}\right)\neq\varnothing.
$$

四者全部只用到"含 $x$ 的对称开区间"这一邻域语言, 不再依赖距离符号 $\varepsilon$–$\delta$ 的写法. $\blacksquare$

## 3

习题册 1.1 Q1 (Sierpiński 空间). 设 $X=\left\{0,1\right\}$, $\mathcal O=\left\{\varnothing,\left\{0\right\},\left\{0,1\right\}\right\}$.

(1) 计算 $\overline{\left\{1\right\}}$;
(2) $\left(X,\mathcal O\right)$ 是否 Hausdorff?
(3) 令 $\mathcal O'=\left\{\varnothing,\left\{1\right\},\left\{0,1\right\}\right\}$. 构造连续映射 $f:\left(X,\mathcal O\right)\to\left(X,\mathcal O'\right)$ 证明 $\mathcal O$ 与 $\mathcal O'$ 同胚;
(4) 证明 $\left(X,\mathcal O\right)$ 中任何序列都收敛到 $1$;
(5) 刻画 $\left(X,\mathcal O\right)$ 中收敛到 $0$ 的序列;
(6) 举出一个既收敛到 $0$ 又收敛到 $1$ 的序列;
(7) 证明 $\left(X,\mathcal O\right)$ 到自身只有三个连续函数.

### 解答 3

由**定义 4.1 (拓扑)** 直接验证 $\mathcal O$ 是拓扑. 由**定义 4.2 (闭集)**, 闭集即开集之补:

$$
\text{闭集}=\left\{X\setminus O:O\in\mathcal O\right\}=\left\{X,\left\{1\right\},\varnothing\right\}.
$$

(1) 由 **0922 §6 (闭包)**, $\overline{\left\{1\right\}}$ 是最小的包含 $\left\{1\right\}$ 的闭集. 上表闭集中含 $\left\{1\right\}$ 的为 $\left\{1\right\}$ 与 $X$, 最小者为 $\left\{1\right\}$. 故

$$
\boxed{\overline{\left\{1\right\}}=\left\{1\right\}}
$$

$\blacksquare$

(2) 由**定义 13.1 (分离性)**, Hausdorff 要求任意两个不同点有不相交的开邻域. 点 $1$ 的开邻域必须含 $1$, 而 $\mathcal O$ 中含 $1$ 的开集只有 $X$; 点 $0$ 的任一开邻域 ($\left\{0\right\}$ 或 $X$) 与 $X$ 的交非空. 找不到两个不相交的开邻域, 故

$$
\left(X,\mathcal O\right)\text{ 不是 Hausdorff}.
$$

$\blacksquare$

(3) 交换两点, 令 $f:X\to X$, $f\left(0\right)=1$, $f\left(1\right)=0$. 它是双射. 由**定义 3.1 (连续)**, 只需检查 $\mathcal O'$ 中开集的原像: $f^{-1}\left(\varnothing\right)=\varnothing$, $f^{-1}\left(X\right)=X$, $f^{-1}\left(\left\{1\right\}\right)=\left\{0\right\}\in\mathcal O$, 三者皆 $\mathcal O$-开, 故 $f$ 连续. 其逆映射 $f^{-1}=f$ 同理连续. 由**定义 3.5 (同胚)**, $f$ 是同胚, $\mathcal O$ 与 $\mathcal O'$ 同胚. $\blacksquare$

(4) 由**定义 5.1 (收敛, 邻域语言)**, 序列 $a_n\to1$ 要求 $1$ 的每个邻域都含 $a_n$ 对一切充分大的 $n$. 但点 $1$ 的开邻域只有 $X$, 而每个 $a_n\in X$ 恒成立, 故任何序列都最终 (事实上全程) 落在 $1$ 的邻域 $X$ 内. 所以任何序列都收敛到 $1$. $\blacksquare$

(5) 点 $0$ 的开邻域为 $\left\{0\right\}$ 与 $X$. 由**定义 5.1**, $a_n\to0$ 特别要求 $a_n$ 最终落在邻域 $\left\{0\right\}$ 内, 即 $a_n=0$ 对一切充分大的 $n$ 成立 (反之显然). 故

$$
a_n\to0\quad\Longleftrightarrow\quad a_n\text{ 最终恒为 }0.
$$

$\blacksquare$

(6) 取常值序列 $a_n\equiv0$. 由 (5) 它收敛到 $0$; 由 (4) 任何序列都收敛到 $1$, 故它也收敛到 $1$. 这就是所求序列. $\blacksquare$

(7) 由**定义 3.1 (连续)**, $f:\left(X,\mathcal O\right)\to\left(X,\mathcal O\right)$ 连续当且仅当每个 $\mathcal O$-开集的原像为 $\mathcal O$-开. $\varnothing,X$ 的原像 $\varnothing,X$ 自动为开, 唯一非平凡条件是

$$
f^{-1}\left(\left\{0\right\}\right)\in\mathcal O=\left\{\varnothing,\left\{0\right\},X\right\}.
$$

分三种情况:

- $f^{-1}\left(\left\{0\right\}\right)=X$: 即 $f\equiv0$;
- $f^{-1}\left(\left\{0\right\}\right)=\varnothing$: 即 $f$ 从不取 $0$, 故 $f\equiv1$;
- $f^{-1}\left(\left\{0\right\}\right)=\left\{0\right\}$: 即 $f\left(0\right)=0$ 且 $f\left(1\right)=1$, 即恒等映射.

三个集合 $X,\varnothing,\left\{0\right\}$ 穷尽 $\mathcal O$, 故恰有三个连续自映射: 常值 $0$, 常值 $1$, 恒等. (交换映射 $f\left(0\right)=1,f\left(1\right)=0$ 的 $f^{-1}\left(\left\{0\right\}\right)=\left\{1\right\}\notin\mathcal O$, 不连续.) $\blacksquare$

## 4

习题册 1.1 Q2 (初始拓扑). 设 $f:X\to Y$ 是函数, $Y$ 上已给拓扑 $\mathcal O$. 令

$$
f^{-1}\left(\mathcal O\right)=\left\{f^{-1}\left(O\right)\subset X:O\in\mathcal O\right\}.
$$

证明 $f^{-1}\left(\mathcal O\right)$ 是 $X$ 上的拓扑, 且它是使 $f$ 连续的**最粗**拓扑. 此即由 $f$ 诱导的初始拓扑.

### 解答 4

**$f^{-1}\left(\mathcal O\right)$ 是拓扑.** 逐条验证**定义 4.1 (拓扑)** 三公理 (用到**基础知识 (原像/直接像)** 中原像保并, 保交, 以及**定义 3.4 (原像/拉回)**):

- $\varnothing=f^{-1}\left(\varnothing_Y\right)\in f^{-1}\left(\mathcal O\right)$, $X=f^{-1}\left(Y\right)\in f^{-1}\left(\mathcal O\right)$;
- 任意并: $f^{-1}\left(\bigcup_\alpha O_\alpha\right)=\bigcup_\alpha f^{-1}\left(O_\alpha\right)$ 仍在其中;
- 有限交: $f^{-1}\left(O_1\cap O_2\right)=f^{-1}\left(O_1\right)\cap f^{-1}\left(O_2\right)$ 仍在其中.

故 $f^{-1}\left(\mathcal O\right)$ 是 $X$ 上的拓扑.

**最粗性.** 由**定义 3.1 (连续)**, $f:\left(X,\mathcal O_X\right)\to\left(Y,\mathcal O\right)$ 连续要求每个 $O\in\mathcal O$ 的原像 $f^{-1}\left(O\right)$ 在 $\mathcal O_X$ 中, 即 $f^{-1}\left(\mathcal O\right)\subset\mathcal O_X$. 故任何使 $f$ 连续的拓扑 $\mathcal O_X$ 都必须包含 $f^{-1}\left(\mathcal O\right)$. 而 $f^{-1}\left(\mathcal O\right)$ 本身已使 $f$ 连续 (其成员正是 $Y$ 开集的原像). 由**定义 4.4 (粗细)**, 它是使 $f$ 连续的最小 (最粗) 拓扑, 即**定义 10.1 (初始/拉回拓扑)**. $\blacksquare$

## 5

习题册 1.1 Q3 (拓扑族之交). 设 $\left\{\left(X,\mathcal O_\alpha\right)\right\}_{\alpha\in\mathcal A}$ 是同一集合 $X$ 上的一族拓扑. 证明: 以

$$
A\subset X\text{ 开}\quad\Longleftrightarrow\quad A\text{ 在每个 }\mathcal O_\alpha\text{ 中都开}
$$

定义的族 $\mathcal O=\bigcap_{\alpha\in\mathcal A}\mathcal O_\alpha$ 仍是 $X$ 上的拓扑. 并举反例说明: 把交换成并 $\bigcup_\alpha\mathcal O_\alpha$ 一般不是拓扑.

### 解答 5

**交是拓扑.** 逐条验证**定义 4.1 (拓扑)**:

- $\varnothing,X$ 在每个 $\mathcal O_\alpha$ 中开, 故在 $\mathcal O$ 中;
- 任意并: 若 $A_\beta\in\mathcal O$, 则每个 $A_\beta$ 在每个 $\mathcal O_\alpha$ 中开, 由 $\mathcal O_\alpha$ 对任意并封闭, $\bigcup_\beta A_\beta$ 在每个 $\mathcal O_\alpha$ 中开, 故在 $\mathcal O$ 中;
- 有限交: 若 $A_1,A_2\in\mathcal O$, 则它们在每个 $\mathcal O_\alpha$ 中开, 由 $\mathcal O_\alpha$ 对有限交封闭, $A_1\cap A_2$ 在每个 $\mathcal O_\alpha$ 中开, 故在 $\mathcal O$ 中.

所以 $\mathcal O=\bigcap_\alpha\mathcal O_\alpha$ 是拓扑 (即**命题 7.5** 中"所有含 $\mathcal S$ 的拓扑之交").

**并不是拓扑 (反例).** 取 $X=\left\{a,b,c\right\}$, 令

$$
\mathcal O_1=\left\{\varnothing,\left\{a\right\},\left\{a,b\right\},X\right\},\quad
\mathcal O_2=\left\{\varnothing,\left\{c\right\},\left\{b,c\right\},X\right\}.
$$

二者均满足**定义 4.1** 三公理, 是拓扑. 但其并

$$
\mathcal O_1\cup\mathcal O_2=\left\{\varnothing,\left\{a\right\},\left\{c\right\},\left\{a,b\right\},\left\{b,c\right\},X\right\}
$$

不含 $\left\{a,b\right\}\cap\left\{b,c\right\}=\left\{b\right\}$, 违反**定义 4.1** 的有限交封闭, 故不是拓扑. $\blacksquare$

## 6

习题册 1.1 Q4 (粗细的等价定义). 证明下列三条都是 "$\mathcal O_1$ 比 $\mathcal O_2$ 更细" (按**定义 4.4** 即 $\mathcal O_2\subset\mathcal O_1$) 的等价定义:

(1) $\mathcal O_2$ 的每个闭集在 $\mathcal O_1$ 中仍闭;
(2) 恒等映射 $\operatorname{id}_X:\left(X,\mathcal O_1\right)\to\left(X,\mathcal O_2\right)$ 连续;
(3) 对任意 $x\in X$, $x$ 在 $\mathcal O_2$ 中的邻域也是 $x$ 在 $\mathcal O_1$ 中的邻域.

### 解答 6

设 $\mathcal O_2\subset\mathcal O_1$ (即 $\mathcal O_1$ 更细).

**(细 ⇒ (1)).** 若 $F$ 在 $\mathcal O_2$ 中闭, 由**定义 4.2 (闭集)**, $F^{c}\in\mathcal O_2\subset\mathcal O_1$, 故 $F^{c}\in\mathcal O_1$, 即 $F$ 在 $\mathcal O_1$ 中闭.

**((1) ⇒ 细).** 设 $V\in\mathcal O_2$, 则 $V^{c}$ 在 $\mathcal O_2$ 中闭, 由 (1) 它在 $\mathcal O_1$ 中闭, 故 $\left(V^{c}\right)^{c}=V\in\mathcal O_1$. 于是 $\mathcal O_2\subset\mathcal O_1$.

**(细 ⇒ (2)).** 由**定义 3.1 (连续)**, 要证 $\operatorname{id}_X:\left(X,\mathcal O_1\right)\to\left(X,\mathcal O_2\right)$ 连续, 只需每个 $\mathcal O_2$-开集 $V$ 的原像 $\operatorname{id}_X^{-1}\left(V\right)=V$ 是 $\mathcal O_1$-开. 由 $\mathcal O_2\subset\mathcal O_1$, $V\in\mathcal O_1$, 成立.

**((2) ⇒ 细).** 若 $\operatorname{id}_X:\left(X,\mathcal O_1\right)\to\left(X,\mathcal O_2\right)$ 连续, 则每个 $V\in\mathcal O_2$ 的原像 $V$ 是 $\mathcal O_1$-开, 故 $\mathcal O_2\subset\mathcal O_1$.

**(细 ⇒ (3)).** 设 $U$ 是 $x$ 在 $\mathcal O_2$ 中的邻域, 由**定义 1.2 (邻域)**, 存在 $\mathcal O_2$-开集 $O$ 使 $x\in O\subset U$. 因 $\mathcal O_2\subset\mathcal O_1$, $O$ 也是 $\mathcal O_1$-开, 故同一 $O$ 表明 $U$ 是 $x$ 在 $\mathcal O_1$ 中的邻域.

**((3) ⇒ 细).** 设 $V\in\mathcal O_2$. 由**命题 1.3 (开集的邻域刻画)**, $V$ 是它每一点在 $\mathcal O_2$ 中的邻域; 由 (3), $V$ 是它每一点在 $\mathcal O_1$ 中的邻域; 再由**命题 1.3**, $V\in\mathcal O_1$. 故 $\mathcal O_2\subset\mathcal O_1$.

三条彼此等价, 且都等价于 $\mathcal O_2\subset\mathcal O_1$. $\blacksquare$

## 7

习题册 1.1 Q5 (更细拓扑的单调性). 设 $\left(X,\mathcal O_1\right)$ 比 $\left(X,\mathcal O_2\right)$ 更细 (即 $\mathcal O_2\subset\mathcal O_1$). 证明:

(1) 若 $\mathcal O_2$ 是 Hausdorff, 则 $\mathcal O_1$ 也是 Hausdorff;
(2) 若 $\mathcal O_1$ 可分, 则 $\mathcal O_2$ 也可分;
(3) 对任意 $A\subset X$, $A$ 在 $\mathcal O_1$ 中的闭包含于其在 $\mathcal O_2$ 中的闭包, $A$ 在 $\mathcal O_2$ 中的内部含于其在 $\mathcal O_1$ 中的内部.

### 解答 7

**(1).** 由**定义 13.1 (分离性)**, 任取不同两点 $x\neq y$. 因 $\mathcal O_2$ Hausdorff, 存在不相交的 $\mathcal O_2$-开邻域 $U,V$. 由 $\mathcal O_2\subset\mathcal O_1$, $U,V$ 也是 $\mathcal O_1$-开, 故在 $\mathcal O_1$ 中仍分离 $x,y$. 因而 $\mathcal O_1$ Hausdorff. (开集越多越易分离.) $\blacksquare$

**(2).** 由**注 13.B (可分与导集)**, 设 $D$ 是 $\mathcal O_1$ 的可数稠密子集, 即 $\overline D^{\,\mathcal O_1}=X$. 由本问 (3) (先证), $\overline D^{\,\mathcal O_1}\subset\overline D^{\,\mathcal O_2}$, 故 $X\subset\overline D^{\,\mathcal O_2}\subset X$, 即 $\overline D^{\,\mathcal O_2}=X$. 同一个可数集 $D$ 在更粗的 $\mathcal O_2$ 中仍稠密, 故 $\mathcal O_2$ 可分. $\blacksquare$

**(3).** 记 $\overline A^{\,\mathcal O_i}$, $\operatorname{Int}_{\mathcal O_i}A$ 为相应拓扑下的闭包与内部.

**闭包.** 由 **0922 §6 (闭包)**, $\overline A^{\,\mathcal O_2}$ 是 $\mathcal O_2$ 中最小的包含 $A$ 的闭集; 它也是 $\mathcal O_1$ 中的闭集吗? 由第 6 题 (1) ($\mathcal O_2$ 闭 $\Rightarrow$ $\mathcal O_1$ 闭), $\overline A^{\,\mathcal O_2}$ 是一个含 $A$ 的 $\mathcal O_1$-闭集. 而 $\overline A^{\,\mathcal O_1}$ 是最小的含 $A$ 的 $\mathcal O_1$-闭集, 故

$$
\overline A^{\,\mathcal O_1}\subset\overline A^{\,\mathcal O_2}.
$$

**内部.** 由 **0922 §6 (内部)**, $\operatorname{Int}_{\mathcal O_2}A$ 是 $\mathcal O_2$ 中最大的含于 $A$ 的开集. 因 $\mathcal O_2\subset\mathcal O_1$, 这个开集也是 $\mathcal O_1$-开; 而 $\operatorname{Int}_{\mathcal O_1}A$ 是最大的含于 $A$ 的 $\mathcal O_1$-开集, 故

$$
\operatorname{Int}_{\mathcal O_2}A\subset\operatorname{Int}_{\mathcal O_1}A.
$$

$\blacksquare$

## 8

习题册 1.4 C1 ($\mathbb R^n$ 的通常度量拓扑). 回忆 $\mathbb R^n$ 的通常度量拓扑. 证明: $\mathbb R^n$ 中任意多个开集之并仍开; 并举反例说明任意多个开集之交未必开.

### 解答 8

由**定义 2.2 (开球与度量拓扑)**, $U$ 开即对每个 $x\in U$ 存在 $r>0$ 使 $B\left(x,r\right)\subset U$.

**任意并保持开.** 设 $U=\bigcup_\alpha U_\alpha$, 各 $U_\alpha$ 开. 任取 $x\in U$, 则存在 $\alpha_0$ 使 $x\in U_{\alpha_0}$. 因 $U_{\alpha_0}$ 开, 存在 $r>0$ 使 $B\left(x,r\right)\subset U_{\alpha_0}\subset U$. 故 $U$ 开. 这也正是**定义 4.1 (拓扑)** 的任意并公理.

**交可不开 (反例).** 在 $\mathbb R$ 中取

$$
\bigcap_{n\ge1}\left(-\frac1n,\frac1n\right)=\left\{0\right\}.
$$

每个 $\left(-\frac1n,\frac1n\right)$ 是开球 (开集), 但其交为单点集 $\left\{0\right\}$. 由**命题 1.3 (开集的邻域刻画)**, $\left\{0\right\}$ 不是它每一点 (即 $0$) 的邻域 (任何含 $0$ 的开区间都伸出 $\left\{0\right\}$ 之外), 故 $\left\{0\right\}$ 不开. 这正是**注 1.B (开集之交)** 的例子. $\blacksquare$

## 9

习题册 1.4 C2 (原像与直接像). 回忆函数的原像 (拉回). 证明原像与并, 交运算交换; 并举反例说明直接像一般不保持交.

### 解答 9

设 $f:X\to Y$, $\left\{V_\alpha\right\}\subset Y$. 由**定义 3.4 (原像/拉回)** $f^{-1}\left(V\right)=\left\{x\in X:f\left(x\right)\in V\right\}$.

**原像保持并.** 任取 $x$,

$$
\begin{aligned}x\in f^{-1}\left(\bigcup_\alpha V_\alpha\right)
&\Leftrightarrow f\left(x\right)\in\bigcup_\alpha V_\alpha\\
&\Leftrightarrow\exists\alpha,\,f\left(x\right)\in V_\alpha\\
&\Leftrightarrow\exists\alpha,\,x\in f^{-1}\left(V_\alpha\right)\\
&\Leftrightarrow x\in\bigcup_\alpha f^{-1}\left(V_\alpha\right).
\end{aligned}
$$

**原像保持交.** 同理,

$$
\begin{aligned}x\in f^{-1}\left(\bigcap_\alpha V_\alpha\right)
&\Leftrightarrow f\left(x\right)\in\bigcap_\alpha V_\alpha\\
&\Leftrightarrow\forall\alpha,\,f\left(x\right)\in V_\alpha\\
&\Leftrightarrow\forall\alpha,\,x\in f^{-1}\left(V_\alpha\right)\\
&\Leftrightarrow x\in\bigcap_\alpha f^{-1}\left(V_\alpha\right).
\end{aligned}
$$

此即**基础知识 (原像/直接像)** 所列原像保并保交.

**直接像不保持交 (反例).** 取 $f:\mathbb R\to\mathbb R$, $f\left(x\right)=x^2$, 并令 $A=\left(-1,0\right)$, $B=\left(0,1\right)$. 则 $A\cap B=\varnothing$, 故 $f\left(A\cap B\right)=f\left(\varnothing\right)=\varnothing$; 但

$$
f\left(A\right)=\left(0,1\right),\quad f\left(B\right)=\left(0,1\right),\quad f\left(A\right)\cap f\left(B\right)=\left(0,1\right)\neq\varnothing.
$$

所以 $f\left(A\cap B\right)\neq f\left(A\right)\cap f\left(B\right)$, 直接像不保持交. $\blacksquare$

## 10

习题册 1.4 C3 (向量子空间的生成与最小). 回忆"由一族向量生成的向量子空间". 给出两种等价构造: 一种利用"向量子空间对交运算封闭"的抽象构造, 一种用有限线性组合的具体构造. (与拓扑类比.)

### 解答 10

设 $X$ 是域 $K$ 上的线性空间, $S=\left\{v_\alpha\right\}_{\alpha\in\mathcal A}\subset X$.

**抽象 (最小) 构造.** 令 $\left\{Y_\beta\right\}$ 为 $X$ 中所有包含 $S$ 的线性子空间. 因线性子空间的任意交仍是线性子空间 (对加法与数乘封闭), 定义

$$
Y_{\min}:=\bigcap_\beta Y_\beta.
$$

它是包含 $S$ 的**最小**线性子空间.

**具体 (生成) 构造.** 取 $S$ 中向量的一切有限线性组合:

$$
Y_{\mathrm{gen}}:=\left\{\sum_{i=1}^k c_i v_{\alpha_i}:k\in\mathbb N,\,c_i\in K,\,v_{\alpha_i}\in S\right\}.
$$

它本身是线性子空间, 且包含 $S$.

**二者相等.** 任一含 $S$ 的子空间 $Y_\beta$ 对线性组合封闭, 故 $Y_{\mathrm{gen}}\subset Y_\beta$ 对一切 $\beta$ 成立, 从而 $Y_{\mathrm{gen}}\subset Y_{\min}$. 反之 $Y_{\mathrm{gen}}$ 本身是一个含 $S$ 的子空间, 故它属于 $\left\{Y_\beta\right\}$, 于是 $Y_{\min}\subset Y_{\mathrm{gen}}$. 故 $Y_{\min}=Y_{\mathrm{gen}}$.

这正是**例 8.1 (生成与最小: 线性空间类比)**: 一个靠"生成", 一个靠"最小 (取交)". 拓扑学中完全平行——由一族子集 $\mathcal S$ 生成的最小拓扑, 既是"取所有含 $\mathcal S$ 的拓扑之交", 又可用"$\mathcal S$ 元素之并"具体构造 (**命题 7.5**). $\blacksquare$

## 11

习题册 1.4 C4 ($\mathbb R$ 中的闭集). 证明: 在 $\mathbb R$ 的通常度量拓扑下, $F\subset\mathbb R$ 是闭集, 当且仅当 $F$ 中任何收敛数列的极限仍属于 $F$.

### 解答 11

这正是**命题 1.6 (闭集的极限刻画)** 在通常度量拓扑下的陈述, 而其定义即**定义 1.4 (闭集)** ($F$ 闭 $\Leftrightarrow$ $F^{c}$ 开).

($\Rightarrow$) 设 $F$ 闭, 数列 $a_n\in F$ 且 $a_n\to a$. 若 $a\notin F$, 则 $a\in F^{c}$. 因 $F$ 闭, $F^{c}$ 开; 由**命题 1.3 (开集的邻域刻画)**, $F^{c}$ 是 $a$ 的邻域. 由**定义 5.1 (收敛, 邻域语言)**, $a_n$ 最终落入 $a$ 的任一邻域 $F^{c}$, 即 $a_n\in F^{c}$ 对充分大 $n$ 成立, 与 $a_n\in F$ 矛盾. 故 $a\in F$.

($\Leftarrow$) 设 $F$ 中任何收敛数列的极限仍在 $F$ 中. 反设 $F$ 不闭, 则 $F^{c}$ 不开. 由**命题 1.3**, 存在 $a\in F^{c}$, 使 $F^{c}$ 不是 $a$ 的邻域, 即每个含 $a$ 的开区间 $\left(a-\frac1n,a+\frac1n\right)$ 都不完全落在 $F^{c}$ 内, 因而与 $F$ 相交. 取 $a_n\in\left(a-\frac1n,a+\frac1n\right)\cap F$, 则 $a_n\in F$ 且 $a_n\to a$, 但 $a\in F^{c}$, 与假设矛盾. 故 $F$ 闭. $\blacksquare$

## 12

习题册 1.4 C5 (拓扑族之交与生成拓扑的基). 回忆同一集合 $X$ 上一族拓扑之交仍是拓扑. 回忆由一族子集 $\mathcal S\subset2^{X}$ 生成的拓扑. 问: 这个生成的拓扑能否用"有限交"具体构造?

### 解答 12

**交是拓扑.** 已在第 5 题证明: $\mathcal O=\bigcap_\alpha\mathcal O_\alpha$ 逐条满足**定义 4.1 (拓扑)** 三公理.

**由 $\mathcal S$ 生成的拓扑.** 由**命题 7.5 (一族子集生成的拓扑)**, 它是所有含 $\mathcal S$ 的拓扑之交, 即含 $\mathcal S$ 的最小拓扑.

**具体构造 (有限交作基).** 令

$$
\mathcal B_{\mathrm{fin}}=\left\{S_1\cap\cdots\cap S_k:k\ge0,\,S_i\in\mathcal S\right\},
$$

其中 $k=0$ 的空交约定为 $X$. 验证 $\mathcal B_{\mathrm{fin}}$ 满足**命题 7.4 (充分公理)**:

- **覆盖**: $X$ (空交) $\in\mathcal B_{\mathrm{fin}}$, 故 $X=\bigcup\mathcal B_{\mathrm{fin}}$;
- **交性质**: 若 $x\in B_1\cap B_2$, 其中 $B_1=\bigcap_{i=1}^p S_i$, $B_2=\bigcap_{j=1}^q S'_j$, 则 $B_1\cap B_2=\bigcap_{i,j}\left(S_i\cap S'_j\right)$ 仍是有限个 $\mathcal S$ 元素之交, 记为 $B_3\in\mathcal B_{\mathrm{fin}}$, 且 $x\in B_3\subset B_1\cap B_2$.

由**证明 7.B**, $\mathcal B_{\mathrm{fin}}$ 元素之并构成一个含 $\mathcal S$ 的拓扑. 任何含 $\mathcal S$ 的拓扑对有限交封闭 (**定义 4.1**), 必含全部 $\mathcal B_{\mathrm{fin}}$, 进而含其一切并, 故这就是含 $\mathcal S$ 的最小拓扑. 即:

$$
\boxed{\text{由 }\mathcal S\text{ 生成的拓扑 }=\left\{\bigcup_\beta B_\beta:B_\beta\text{ 为 }\mathcal S\text{ 元素的有限交}\right\}.}
$$

$\blacksquare$

## 13

习题册 1.4 C6 (初始拓扑与最终拓扑). 证明: 若 $f:X\to\left(Y,\mathcal O\right)$ 是到拓扑空间的映射, 则 $f^{-1}\left(\mathcal O\right)=\left\{f^{-1}\left(O\right):O\in\mathcal O\right\}$ 是 $X$ 上的拓扑, 且是使 $f$ 连续的最粗拓扑 (即初始拓扑). 研究 $f$ 为包含映射的情形 (例如 $f:\mathbb R\to\mathbb R^2$, $\mathbb R^2$ 取欧氏拓扑). 能否反过来: 在 $X$ 上推一个拓扑, 用来在 $Y$ 上定义"最终拓扑"?

### 解答 13

**初始拓扑.** $f^{-1}\left(\mathcal O\right)$ 是拓扑且最粗, 已在第 4 题证明, 即**定义 10.1 (初始/拉回拓扑)**. 要点: $\varnothing,X$ 由 $f^{-1}\left(\varnothing\right)=\varnothing$, $f^{-1}\left(Y\right)=X$ 得到, 任意并与有限交由原像保并保交 (**基础知识 (原像/直接像)**) 保持, 故为拓扑; 任何使 $f$ 连续的拓扑必含全部 $f^{-1}\left(O\right)$ (**定义 3.1**), 故它最粗.

**包含映射的情形.** 设 $f=\iota:A\to X$ 为包含映射. 则

$$
f^{-1}\left(O\right)=\iota^{-1}\left(O\right)=O\cap A,
$$

故 $\iota$ 诱导的初始拓扑正是 $\mathcal O_A=\left\{O\cap A:O\in\mathcal O\right\}$, 即**定义 9.1 (子空间拓扑)**. 例如 $\iota:\mathbb R\to\mathbb R^2$, 把 $\mathbb R$ 看作 $\mathbb R^2$ 中一条坐标轴 $\left\{\left(x,0\right):x\in\mathbb R\right\}$, 则 $\mathbb R$ 上的初始拓扑就是它从 $\mathbb R^2$ 欧氏拓扑继承的子空间拓扑, 即通常的欧氏拓扑.

**最终 (pushforward) 拓扑.** 反过来, 设 $\pi:X\to Y$ 是满射, $X$ 上已给拓扑. 由**定义 10.2 (最终/商拓扑)**, 在 $Y$ 上定义

$$
\mathcal O_Y=\left\{V\subset Y:\pi^{-1}\left(V\right)\text{ 在 }X\text{ 中开}\right\}.
$$

验证它是 $Y$ 上的拓扑: $\varnothing,Y$ 由 $\pi^{-1}\left(\varnothing\right)=\varnothing$, $\pi^{-1}\left(Y\right)=X$ 得到; 任意并与有限交仍由原像保并保交保持. 它是使 $\pi$ 连续的**最大**拓扑: 若 $\mathcal O'_Y$ 也使 $\pi$ 连续, 则每个 $V\in\mathcal O'_Y$ 的原像开, 故 $V\in\mathcal O_Y$, 即 $\mathcal O'_Y\subset\mathcal O_Y$. 这与初始拓扑"最小"对偶: 初始拓扑使"进入 $X$ 的映射连续 $\Leftrightarrow$ 复合到 $Y$ 连续", 最终拓扑使"从 $Y$ 出发的映射连续 $\Leftrightarrow$ 复合自 $X$ 连续". $\blacksquare$

## 14

习题册 1.4 C7 (cofinite 与可数补拓扑). 设 $X$ 是集合. 证明: "所有非平凡开集都是某个有限子集的补集" (即开＝补有限) 是 $X$ 上的拓扑, 称为 cofinite 拓扑. 证明 $\mathbb R$ (cofinite 拓扑) 中的序列 $\left\{1,2,3,4,\dots\right\}$ 收敛到 $\mathbb R$ 的每一点. 再在 $X$ 上定义可数补 (cocountable) 拓扑. 现令 $X=\mathbb R$ 取可数补拓扑, $B=\left(-1,1\right)\subset\mathbb R$, 证明 $\overline B=\mathbb R$; 并证明 $B$ 中没有序列收敛到 $2$.

### 解答 14

**cofinite 拓扑.** 由**例 5.2 (cofinite 拓扑)**, 开集定义为 $\varnothing$ 或补集有限者. 验证**定义 4.1**: $\varnothing,X$ 开; 任意并之补是各补之交, 有限集之交仍有限 (或为空), 故并开; 有限交之补是各补之并, 有限个有限集之并仍有限, 故交开. 确为拓扑.

**序列 $\left\{1,2,3,\dots\right\}$ 收敛到每点.** 由**定义 5.1 (收敛, 邻域语言)**, 任取 $x\in\mathbb R$ 与其任一邻域 $U$. cofinite 拓扑下 $U$ 非空开即 $U^{c}$ 有限. 序列 $\left\{n\right\}$ 中至多有限多项落在有限集 $U^{c}$ 内, 故 $a_n=n$ 对一切充分大 $n$ 落入 $U$. 因而 $a_n\to x$ 对每个 $x$ 成立. (这也复述了**例 5.2** "无限时任何序列收敛到一切点".)

**可数补拓扑.** 开集为 $\varnothing$ 或补集可数者; 其闭集恰为可数集与 $\mathbb R$ (**例 6.1 (序列不够用; 历年 C7)**). 验证同上: 有限交之补是有限个可数集之并 (仍可数), 任意并之补是各补之交 (可数集之交仍可数).

**$\overline{\left(-1,1\right)}=\mathbb R$.** 由 **0922 §6 (闭包)**, $\overline B$ 是最小的含 $B$ 的闭集. 可数补拓扑下真闭集 ($\neq\mathbb R$) 必可数 (**例 6.1**), 而 $B=\left(-1,1\right)$ 不可数, 故任何真闭集都装不下 $B$, 唯一含 $B$ 的闭集是 $\mathbb R$. 因此

$$
\boxed{\overline{\left(-1,1\right)}=\mathbb R.}
$$

此即**例 6.2 (闭包依赖拓扑)**.

**无 $B$ 中序列收敛到 $2$.** 任取序列 $a_n\in B$. 它的值域 $\left\{a_n:n\in\mathbb N\right\}$ 是可数集, 因而是可数补拓扑下的闭集 (**例 6.1**). 于是 $U:=\mathbb R\setminus\left\{a_n\right\}$ 是开集, 它是 $2$ 的一个邻域 ($2\notin\left\{a_n\right\}$, 因 $a_n\in\left(-1,1\right)$). 但这个邻域完全不含任何 $a_n$. 由**定义 5.1**, $a_n\not\to2$. 故 $B$ 中没有序列收敛到 $2$. $\blacksquare$

## 15

习题册 1.4 C8 (Zariski 拓扑). 设 $K$ 是域, $n\in\mathbb N$, $\mathbb A_n\left(K\right)=K^{n}$. 称 $F\subset\mathbb A_n\left(K\right)$ 是 Zariski 闭集, 若

$$
F=\left\{x\in\mathbb A_n\left(K\right):P_i\left(x\right)=0,\ \forall i\in I\right\},
$$

其中 $\left(P_i\right)_{i\in I}$ 是一族多项式. 证明这确为 $\mathbb A_n\left(K\right)$ 上的拓扑 (Zariski 拓扑). 证明它非 Hausdorff; 证明 $\mathbb R^2$ 中的 Zariski 开集在 (通常拓扑下的) $\mathbb R^2$ 中稠密; 求 $\left\{\left(0,\frac1n\right):n\ge0\right\}\subset\mathbb R^2$ 的 Zariski 闭包.

### 解答 15

**确为拓扑.** 由**定义 14.1 (Zariski 闭集)** 与**命题 14.2**, 以闭集族直接指定拓扑 (呼应**定义 4.2 (闭集)**: 闭集族对任意交, 有限并封闭即可). 验证:

- **任意交**: $\bigcap_\beta F_\beta$, 其中 $F_\beta=\left\{x:P_{\beta,i}\left(x\right)=0,\forall i\right\}$, 是全部多项式族 $\left\{P_{\beta,i}\right\}$ 的公共零点集, 仍 Zariski 闭;
- **有限并**: $F_1\cup F_2=\left\{x:P_1\left(x\right)P_2\left(x\right)=0\right\}$ ($P_1$ 的全部多项式与 $P_2$ 的全部多项式两两相乘所得多项式之公共零点集), 仍 Zariski 闭;
- 空集与全空间: $\varnothing=\left\{x:1=0\right\}$, $\mathbb A_n=\left\{x:0=0\right\}$.

故闭集族满足**定义 4.2** 要求, 确为拓扑.

**非 Hausdorff.** 由**命题 14.2**, Zariski 拓扑非 Hausdorff. 直观地: 任何两个非空 Zariski 开集都是"去掉一条 (或有限多条) 代数曲线"的补, 而在 $\mathbb R^n$ (或 $\mathbb C^n$) 中两条代数曲线不能覆盖整个空间, 故任意两个非空 Zariski 开集必相交, 因而无法分离两点.

**Zariski 开集在 $\mathbb R^2$ 中稠密.** 由**命题 14.2**, Zariski 开集在通常拓扑下稠密. 任一非空 Zariski 开集形如 $U=\mathbb R^2\setminus F$, $F$ 是若干多项式的公共零点集 (至多是有限条代数曲线). 任取通常拓扑下的非空开圆盘 $D$, $D$ 不可能被一条代数曲线占满 (一条非零多项式在任何开圆盘上必有非零点, 否则该多项式在二维开集上恒零, 必为零多项式). 故 $D\cap U\neq\varnothing$, 即 $U$ 在通常拓扑下稠密.

**$\left\{\left(0,\frac1n\right):n\ge0\right\}$ 的 Zariski 闭包.** 记该集为 $A=\left\{\left(0,\frac1n\right):n=1,2,\dots\right\}\cup\left\{\left(0,0\right)\right\}$ ($n=0$ 给出 $\frac10$ 无意义, 依题意取 $n\ge1$ 并含极限点 $\left(0,0\right)$). 找所有在 $A$ 上恒零的多项式 $P\left(x,y\right)$. 对每个 $n$, $P\left(0,\frac1n\right)=0$, 即一元多项式 $q\left(y\right):=P\left(0,y\right)$ 在 $y=\frac1n$ ($n\ge1$) 这无穷多个不同点上为零, 而 $q$ 是多项式, 故 $q\equiv0$. 即 $P\left(0,y\right)\equiv0$, 这等价于 $P$ 被 $x$ 整除: $P\left(x,y\right)=x\cdot R\left(x,y\right)$. 所以公共零点集恰是

$$
\overline A^{\,\mathrm{Zar}}=\left\{\left(x,y\right):x=0\right\}=y\text{-轴}.
$$

(在通常拓扑下, $\overline{\left\{\left(0,\frac1n\right)\right\}}=\left\{\left(0,\frac1n\right)\right\}\cup\left\{\left(0,0\right)\right\}$; 而 Zariski 闭包是整条 $y$-轴, 二者再次不同.) $\blacksquare$

## 16

习题册 1.4 C9 (拓扑基). 回忆拓扑基的定义及其刻画. 证明这三者等价: 基的"并生成"定义, "基判定开集"刻画, 以及作为某拓扑之基的充分公理. 并说明若去掉充分公理中的某一条会怎样.

### 解答 16

三者即**定义 7.2 (基, 并生成版本)**, **命题 7.3 (基判定开集)**, **命题 7.4 (充分公理)**. 设 $\left(X,\mathcal O\right)$ 是拓扑空间, $\mathcal B\subset\mathcal O$.

**定义 7.2 $\Leftrightarrow$ 命题 7.3.** 此即**证明 7.A**:

($\Rightarrow$) 若 $O=\bigcup_\beta B_\beta$, 任取 $x\in O$, 则 $x$ 落在某个 $B_\beta$ 中, 取 $B_x=B_\beta$ 即可, $x\in B_x\subset O$.

($\Leftarrow$) 若对每个 $x\in O$ 都有 $B_x\in\mathcal B$ 使 $x\in B_x\subset O$, 则 $O=\bigcup_{x\in O}B_x$ 是 $\mathcal B$ 元素之并.

**命题 7.4 与二者等价.** 若 $\mathcal B$ 已按定义 7.2 是 $\left(X,\mathcal O\right)$ 的基, 则: 覆盖 $X=\bigcup\mathcal B$ (因 $X$ 开, 是基元素之并); 交性质: 若 $x\in B_1\cap B_2$, 因 $B_1\cap B_2$ 是两个开集之交, 由**定义 4.1** 它开, 由命题 7.3 存在 $B_3\in\mathcal B$ 使 $x\in B_3\subset B_1\cap B_2$. 反之, 若 $\mathcal B\subset2^{X}$ 满足覆盖与交性质, 由**证明 7.B**, $\mathcal B$ 元素之并构成一个含 $\mathcal B$ 的最小拓扑, 在此拓扑下 $\mathcal B$ 按定义 7.2 是基. 故三说法等价.

**去掉条件会怎样.**

- 去掉**覆盖**条件: $X$ 不能写成 $\mathcal B$ 元素之并, 则按"基元素之并"构造时连 $X$ 都得不到, 违反**定义 4.1** ($X\in\mathcal O$), 构不成拓扑.
- 去掉**交性质**: 两个基元素 $B_1,B_2$ 之交不能写成基元素之并, 则 $B_1\cap B_2$ 虽应开, 却不是基元素之并, 违反有限交封闭, "基元素之并"不再是拓扑. 反例: 在 $X=\mathbb R$ 上取 $\mathcal B=\left\{\left(-\infty,p\right),\left(q,+\infty\right)\right\}$ (讲义 §7 开头), 任意两个相交基元素之交 (如一左射线与一右射线相交成开区间) 无法用基元素之并表示. $\blacksquare$

## 17

习题册 1.3 Q1 ($\mathbb R$ 开集的标准分解). 证明: $\mathbb R$ 的每个开子集 $U$ 可唯一写成可数个两两不交开区间之并; 这些区间的端点不属于 $U$.

### 解答 17

**存在性.** 对每个 $x\in U$, 因 $U$ 开 (**定义 1.1**), 存在开区间含 $x$ 且含于 $U$. 令 $I_x$ 为 $U$ 中包含 $x$ 的**最大**开区间:

$$
I_x=\bigcup\left\{\left(a,b\right):x\in\left(a,b\right)\subset U\right\}.
$$

它本身是一个开区间 (开区间之并仍为区间), 且 $\subset U$. 两个这样的区间 $I_x,I_y$ 要么不交, 要么重合 (若相交, 其并仍是含 $x,y$ 且含于 $U$ 的区间, 由最大性必相等). 故全体不同的 $I_x$ 是两两不交的开区间族 $\left\{I_\alpha\right\}$, 且

$$
U=\bigcup_\alpha I_\alpha.
$$

**可数性.** 每个 $I_\alpha$ 是非空开区间, 取其中一个有理数 $q_\alpha\in I_\alpha$; 因各 $I_\alpha$ 两两不交, 这些 $q_\alpha$ 两两不同. 有理数集 $\mathbb Q$ 可数, 故族 $\left\{I_\alpha\right\}$ 可数. (此即**注 1.A (开集之可数表示)**.)

**端点不在 $U$.** 设 $I_\alpha=\left(a_\alpha,b_\alpha\right)$. 若端点 $a_\alpha\in U$, 则由 $U$ 开, $a_\alpha$ 附近有小区间 $\left(a_\alpha-\varepsilon,a_\alpha+\varepsilon\right)\subset U$, 与 $I_\alpha$ 拼接后得到一个更大的含于 $U$ 的开区间, 与 $I_\alpha$ 的最大性矛盾. 故 $a_\alpha,b_\alpha\notin U$.

**唯一性.** 设有两种分解 $U=\bigcup_\alpha I_\alpha=\bigcup_\beta J_\beta$, 均为两两不交开区间. 任取一个 $I_\alpha$. 对任意 $x\in I_\alpha$, $x$ 必落在某个 $J_\beta$ 中. 于是

$$
I_\alpha=I_\alpha\cap U=I_\alpha\cap\left(\bigcup_\beta J_\beta\right)=\bigcup_\beta\left(I_\alpha\cap J_\beta\right).
$$

这里 $I_\alpha\cap J_\beta$ 都是开区间 (或空), 且因 $J_\beta$ 两两不交, 这些 $I_\alpha\cap J_\beta$ 两两不交. 但 $I_\alpha$ 是一个开区间, 由**基础知识 (实数完备性)**, 一个开区间不能被两个非空不交开子集之并覆盖. 故上述并中只能有一个非空项, 即存在唯一 $\beta$ 使 $I_\alpha\cap J_\beta=I_\alpha$, 亦即 $I_\alpha\subset J_\beta$.

对称地, 对该 $J_\beta$ 做同样论证, 由其分解的两两不交性, $J_\beta\subset I_\alpha$. 故 $I_\alpha=J_\beta$. 每个 $I_\alpha$ 都是某个 $J_\beta$, 反之亦然, 两分解一致.

综上, $\mathbb R$ 的每个开子集唯一分解为可数个两两不交开区间之并, 端点不在 $U$ 中. $\blacksquare$

## 18

考题 2025A 题目一 (Furstenberg 拓扑与质数无穷性). 考虑整数空间 $\mathbb Z$. 定义 Furstenberg 拓扑的一组基为所有非平凡双边无穷长等差数列

$$
S\left(a,b\right)=a\mathbb Z+b=\left\{an+b:n\in\mathbb Z\right\},
$$

其中 $a\neq0$ (非平凡). 回答 (0)–(5).

(0) 证明 $\left\{S\left(a,b\right)\right\}$ 确为某个拓扑的基, 并证明 $\mathbb Z$ 的子集是开集当且仅当它是空集, $\mathbb Z$, 或若干 $S\left(a,b\right)$ 之并;
(1) 证明 $\mathbb Z$ 的子集 $U$ 是开集当且仅当对每个 $x\in U$, 存在 $a\neq0$ 使 $S\left(a,x\right)\subset U$;
(2) 证明任何非平凡 $S\left(a,b\right)$ ($a\neq0$) 既开又闭;
(3) 证明 $\mathbb Z$ 的非空有限子集不可能是开集;
(4) 若 $\mathbb P$ 是全体质数, 证明 $\mathbb Z\setminus\left\{-1,1\right\}=\bigcup_{p\in\mathbb P}S\left(p,0\right)$;
(5) 证明 $\mathbb Z$ 中质数有无穷多个.

### 解答 18

(0) 验证**命题 7.4 (充分公理)** 两条件.

**覆盖.** 对任意 $x\in\mathbb Z$, $x=S\left(1,x\right)$ (即 $1\cdot\mathbb Z+x=\mathbb Z$), 故 $\mathbb Z=\bigcup_{a,b}S\left(a,b\right)$.

**交性质.** 设 $x\in S\left(a_1,b_1\right)\cap S\left(a_2,b_2\right)$, 即 $x\equiv b_1\pmod{a_1}$ 且 $x\equiv b_2\pmod{a_2}$. 令 $a_3=\operatorname{lcm}\left(a_1,a_2\right)$ (取 $a_1a_2$ 亦可), 则 $a_3$ 是 $a_1,a_2$ 的公倍数. 对任意 $y\in S\left(a_3,x\right)$, 即 $y\equiv x\pmod{a_3}$, 由 $a_3$ 是 $a_1,a_2$ 的倍数,

$$
y\equiv x\equiv b_1\pmod{a_1},\qquad y\equiv x\equiv b_2\pmod{a_2},
$$

故 $y\in S\left(a_1,b_1\right)\cap S\left(a_2,b_2\right)$. 于是 $x\in S\left(a_3,x\right)\subset S\left(a_1,b_1\right)\cap S\left(a_2,b_2\right)$. 交性质成立.

由**证明 7.B**, $\left\{S\left(a,b\right)\right\}$ 元素之并构成 $\mathbb Z$ 上一个拓扑; 由**定义 7.2 (基, 并生成版本)**, 开集恰是空集, $\mathbb Z$, 或若干基元素之并. $\blacksquare$

(1) 这正是**命题 7.3 (基判定开集)**: $U$ 开 $\Leftrightarrow$ 对每个 $x\in U$ 存在基元素 $B_x$ 使 $x\in B_x\subset U$. 而 $x\in S\left(a,x\right)$ 恒成立 (取 $n=0$), 故可取 $B_x=S\left(a,x\right)$. 即

$$
U\text{ 开}\quad\Longleftrightarrow\quad\forall x\in U,\ \exists a\neq0,\ S\left(a,x\right)\subset U.
$$

$\blacksquare$

(2) **开**: $S\left(a,b\right)$ 本身是基元素, 由 (0) 直接为开. **闭**: 证其补开. $\mathbb Z\setminus S\left(a,b\right)$ 是模 $a$ 不余 $b$ 的那些剩余类之并:

$$
\mathbb Z\setminus S\left(a,b\right)=\bigcup_{\substack{r=0,\dots,a-1\\r\neq b}}S\left(a,r\right).
$$

共 $a-1$ 个 (有限个) $S\left(a,r\right)$, 都是开集, 故其并开 (**定义 4.1** 任意并封闭). 补开即 $S\left(a,b\right)$ 闭. 故 $S\left(a,b\right)$ 既开又闭. $\blacksquare$

(3) 设 $F$ 是非空有限集, 反设 $F$ 开. 由 (1), 对每个 $x\in F$ 存在 $a\neq0$ 使 $S\left(a,x\right)\subset F$. 但 $S\left(a,x\right)=\left\{an+n\text{ 型整数}\right\}$ 当 $a\neq0$ 时有无穷多个元素, 不可能含于有限集 $F$, 矛盾. 故非空有限集不能开. $\blacksquare$

(4) $S\left(p,0\right)=p\mathbb Z$ 即 $p$ 的全体倍数. 并集 $\bigcup_{p\in\mathbb P}S\left(p,0\right)$ 就是被某个质数整除的整数全体. 对任意 $n\in\mathbb Z\setminus\left\{-1,1\right\}$ (含 $n=0$ 与 $\left|n\right|\ge2$): 若 $\left|n\right|\ge2$, 由**基础知识 (数论)**, $n$ 有素因子 $p$, 故 $n\in p\mathbb Z=S\left(p,0\right)$; 若 $n=0$, 则 $0=0\cdot p\in S\left(p,0\right)$ 对任意 $p$. 反之 $\pm1$ 不被任何质数整除, 不在并集中. 故

$$
\boxed{\mathbb Z\setminus\left\{-1,1\right\}=\bigcup_{p\in\mathbb P}S\left(p,0\right).}
$$

$\blacksquare$

(5) 反设质数只有有限多个, $\mathbb P=\left\{p_1,\dots,p_k\right\}$. 由 (4),

$$
\mathbb Z\setminus\left\{-1,1\right\}=\bigcup_{i=1}^k S\left(p_i,0\right).
$$

右边是有限个集合之并: 每个 $S\left(p_i,0\right)$ 由 (2) 是闭集, 有限个闭集之并仍闭 (**定义 4.2**); 同时每个 $S\left(p_i,0\right)$ 是开集, 有限个开集之并亦开. 故 $\mathbb Z\setminus\left\{-1,1\right\}$ 既开又闭, 其补集 $\left\{-1,1\right\}$ 既闭又开. 但 $\left\{-1,1\right\}$ 是非空有限集, 由 (3) 它不可能是开集, 矛盾.

故质数不能只有有限个, 即 $\mathbb Z$ 中质数有无穷多个. $\blacksquare$
