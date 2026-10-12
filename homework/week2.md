# 作业 2

> **注 1.B** (开集之交)<br>开集的任意并保持开, 但交不一定: 有限个开集的交仍开, 无限个未必, $\bigcap_{n\ge1}\left(-\frac1n,\frac1n\right)=\left\{0\right\}$, 而 $\left\{0\right\}$ 不是开集.

> **定义 3.1** (连续)<br>$f:\left(X,\mathcal O_X\right)\to\left(Y,\mathcal O_Y\right)$ **连续**, 若任意开集 $V$ 的原像 $f^{-1}\left(V\right)$ 是开集.

> **命题 3.2** (复合连续)<br>连续映射的复合 $g\circ f$ 连续.

> **定义 4.1** (拓扑)<br>$\mathcal O\subset2^X$ 满足 $\varnothing,X\in\mathcal O$; 任意并封闭; 有限交封闭.

> **定义 4.2** (闭集)<br>$F$ 闭 $\Leftrightarrow F^{c}$ 开; 闭集族对任意交, 有限并封闭.

> **0922 §6** (闭包的邻域定义与稠密)<br>$x\in\overline A$, 若 $x$ 的每个邻域 $U$ 都使 $U\cap A\neq\varnothing$; $\overline A$ 是最小的包含 $A$ 的闭集; $A$ 稠密 $\Leftrightarrow\overline A=X$.

> **命题 7.3** (基判定开集)<br>$O$ 是开集, 当且仅当对任意 $x\in O$, 存在 $B_x\in\mathcal B$ 使 $x\in B_x\subset O$.

> **定义 9.1** (子空间拓扑)<br>$\mathcal O_A=\left\{U\cap A:U\in\mathcal O\right\}$.

> **命题 9.4** (子空间拓扑的泛性质)<br>$f:Z\to A$ 连续 $\Leftrightarrow\iota\circ f:Z\to X$ 连续, 且子空间拓扑正是使 $\iota$ 连续的最粗糙拓扑.

> **定义 10.1** (初始/拉回拓扑)<br>由 $f:X\to\left(Y,\mathcal O_Y\right)$ 诱导的初始拓扑为 $\mathcal O_X=\left\{f^{-1}\left(V\right):V\in\mathcal O_Y\right\}$.

> **命题 13.2**<br>$T2\Rightarrow T1$; 度量空间, 有限维欧氏空间皆 Hausdorff.

> **命题 13.4** (Hausdorff 的继承)<br>Hausdorff 空间的乘积仍 Hausdorff; Hausdorff 空间的子空间仍 Hausdorff.

> **定义 18.1** (豪斯多夫, T2 分离)<br>$X$ 是**豪斯多夫** ($T_2$), 若对任意 $x\neq y$, 存在开邻域 $O_x\ni x$, $O_y\ni y$ 使 $O_x\cap O_y=\varnothing$.

> **定义 20.1** (乘积拓扑的基)<br>$X\times Y$ 上以 $\left\{U\times V:U\subset X,V\subset Y\text{ 开}\right\}$ 为基.

> **定理 20.4** (Thm 3.4)<br>乘积拓扑是使投影 $p_X,p_Y$ 连续的最小拓扑; $f=\left(f_1,f_2\right):Z\to X\times Y$ 连续 $\Leftrightarrow$ 坐标 $f_1,f_2$ 都连续.

> **定义 21.1** (无限乘积的三种拓扑)<br>(1) 乘积拓扑: $A'\subset\mathcal A$ 有限, 由
>
> $$
> \prod_{\alpha\in A'}U_\alpha\times\prod_{\alpha\notin A'}X_\alpha
> $$
>
> 生成; (3) box 拓扑: 由 $\prod_{\alpha\in\mathcal A}U_\alpha$ (所有坐标都取开集) 生成.

> **例 21.2** (对角映射的连续性取决于所用拓扑)<br>$f:\mathbb R\to\mathbb R^{\mathbb N}$, $f\left(x\right)=\left(x,x,x,\dots\right)$ 在 (1) 乘积拓扑下连续, 在 (3) box 拓扑下不连续.

> **定理 21.3** (Thm 3.7)<br>$f:Z\to\prod_iX_i$ 连续 $\Leftrightarrow$ 每个坐标 $f_i:Z\to X_i$ 连续.

> **定义 24.2** (笛卡尔积的泛性质)<br>$A\times B$ 伴随投影 $\pi_A,\pi_B$, 使对任意 $f:Z\to A$, $g:Z\to B$, 存在唯一 $h:Z\to A\times B$ 满足 $f=\pi_A\circ h$, $g=\pi_B\circ h$.

> **证明 24.A** (良定义)<br>存在性取 $h\left(z\right)=\left(f\left(z\right),g\left(z\right)\right)$; 唯一性由投影在各坐标上的取值决定.

> **习题 25.2** (不交和的泛性质)<br>$A\sqcup B$ 伴随含入 $i_A,i_B$, 使对任意 $f:A\to Z$, $g:B\to Z$, 存在唯一 $h:A\sqcup B\to Z$ 满足 $h\circ i_A=f$, $h\circ i_B=g$.

## 1

设 $f:\mathbb R\to\mathbb R^{\mathbb N}$, $f\left(x\right)=\left(x,x,x,\dots\right)$. 证明:

(1) 在 $\mathbb R^{\mathbb N}$ 取 (1) 乘积拓扑 (有限多坐标取开集) 时, $f$ 连续;

(3) 在 (3) box 拓扑 (所有坐标都取开集) 时, $f$ 不连续.

### 解答 1

本例即**例 21.2 (对角映射的连续性取决于所用拓扑)**.

(1) 对每个 $i\in\mathbb N$, 第 $i$ 坐标映射 $f_i=\pi_i\circ f:\mathbb R\to\mathbb R$ 为 $f_i\left(x\right)=x$, 即恒等映射, 连续. 由**定理 21.3 (Thm 3.7)** ($f:Z\to\prod_iX_i$ 连续 $\Leftrightarrow$ 每个坐标 $f_i$ 连续), $f$ 连续.

也可直接验证: 由**定义 21.1 (1)**, 乘积拓扑的基开集形如

$$
U=\prod_{i\in F}U_i\times\prod_{i\notin F}\mathbb R\qquad\left(F\subset\mathbb N\text{ 有限},U_i\subset\mathbb R\text{ 开}\right).
$$

其原像为

$$
f^{-1}\left(U\right)=\left\{x\in\mathbb R:\forall i\in F,\ x\in U_i\right\}=\bigcap_{i\in F}U_i,
$$

是有限个开集之交, 由**定义 4.1 (拓扑)** 知其开. 再由**定义 3.1 (连续)**, $f$ 连续. $\blacksquare$

(3) 取定 $x_0\in\mathbb R$, 令

$$
V=\prod_{i\ge1}\left(x_0-\frac1i,\,x_0+\frac1i\right).
$$

每个坐标都取开集, 由**定义 21.1 (3) (box 拓扑)**, $V$ 是 box 拓扑下的开集. 其原像为

$$
f^{-1}\left(V\right)=\left\{x\in\mathbb R:\forall i\ge1,\ x\in\left(x_0-\frac1i,x_0+\frac1i\right)\right\}=\bigcap_{i\ge1}\left(x_0-\frac1i,x_0+\frac1i\right)=\left\{x_0\right\}.
$$

由**注 1.B (开集之交)**, 无限个开区间的交 $\left\{x_0\right\}$ 不是 $\mathbb R$ 中的开集. 故开集 $V$ 的原像 $f^{-1}\left(V\right)$ 不开, 由**定义 3.1 (连续)**, $f$ 在 box 拓扑下不连续. $\blacksquare$

## 2

(1) 乘积拓扑的泛性质;

(2) 不交和的泛性质;

(3) 子空间拓扑的泛性质.

### 解答 2

(1) **乘积拓扑的泛性质.** 设 $X\times Y$ 带乘积拓扑, 投影 $\pi_X:X\times Y\to X$, $\pi_Y:X\times Y\to Y$. 此即**定义 24.2 (笛卡尔积的泛性质)** 的拓扑版本. 断言: 对任意连续 $f:Z\to X$, $g:Z\to Y$, 存在唯一连续 $h:Z\to X\times Y$ 使

$$
f=\pi_X\circ h,\qquad g=\pi_Y\circ h.
$$

存在性: 由**证明 24.A (良定义)**, 取

$$
h\left(z\right)=\left(f\left(z\right),g\left(z\right)\right).
$$

其两坐标为 $f,g$, 均连续; 由**定理 20.4 (Thm 3.4)** ($f=\left(f_1,f_2\right):Z\to X\times Y$ 连续 $\Leftrightarrow$ 坐标都连续), $h$ 连续, 且 $\pi_X\circ h=f$, $\pi_Y\circ h=g$.

唯一性: 若 $h'$ 也满足, 写 $h'\left(z\right)=\left(h'_X\left(z\right),h'_Y\left(z\right)\right)$; 由 $\pi_X\circ h'=f$ 得 $h'_X=f$, 由 $\pi_Y\circ h'=g$ 得 $h'_Y=g$, 故 $h'=h$. $\blacksquare$

(2) **不交和的泛性质.** 设 $C=A\sqcup B=\left(A\times\left\{0\right\}\right)\cup\left(B\times\left\{1\right\}\right)$, 含入 $i_A:A\to C$, $i_B:B\to C$. 断言: 对任意 $f:A\to Z$, $g:B\to Z$, 存在唯一 $h:C\to Z$ 使

$$
h\circ i_A=f,\qquad h\circ i_B=g.
$$

存在性: 定义

$$
h\left(a,0\right)=f\left(a\right),\qquad h\left(b,1\right)=g\left(b\right).
$$

唯一性: $C$ 被 $i_A\left(A\right)$ 与 $i_B\left(B\right)$ 两块覆盖, $h$ 在这两块上的取值已分别被 $f,g$ 唯一确定, 故 $h$ 唯一 (**习题 25.2 (不交和的泛性质)**). 若 $f,g$ 连续, 在不交和拓扑 ($U\subset C$ 开 $\Leftrightarrow U\cap\left(A\times\left\{0\right\}\right)$ 在 $A$ 开且 $U\cap\left(B\times\left\{1\right\}\right)$ 在 $B$ 开; 它满足**定义 4.1 (拓扑)** 三公理) 下, 对任意开 $W\subset Z$,

$$
h^{-1}\left(W\right)\cap\left(A\times\left\{0\right\}\right)=\left\{\left(a,0\right):f\left(a\right)\in W\right\}=i_A\left(f^{-1}\left(W\right)\right)
$$

在 $A\times\left\{0\right\}$ 开, 同理 $h^{-1}\left(W\right)\cap\left(B\times\left\{1\right\}\right)$ 在 $B\times\left\{1\right\}$ 开, 故 $h^{-1}\left(W\right)$ 在 $C$ 开, 即 $h$ 连续. $\blacksquare$

(3) **子空间拓扑的泛性质.** 设 $A\subset X$, $\iota:A\to X$ 为包含映射, $A$ 带子空间拓扑. 断言: 对任意 $f:Z\to A$,

$$
f\text{ 连续}\iff\iota\circ f:Z\to X\text{ 连续}.
$$

($\Rightarrow$) 由**命题 3.2 (复合连续)**, $\iota\circ f$ 连续.

($\Leftarrow$) 设 $\iota\circ f$ 连续. 任取 $A$ 中开集 $U$; 由**定义 9.1 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $U=O\cap A=\iota^{-1}\left(O\right)$. 则

$$
f^{-1}\left(U\right)=f^{-1}\left(\iota^{-1}\left(O\right)\right)=\left(\iota\circ f\right)^{-1}\left(O\right),
$$

由 $\iota\circ f$ 连续知其开. 故由**定义 3.1 (连续)**, $f$ 连续. 这正是**命题 9.4 (子空间拓扑的泛性质)**. $\blacksquare$

## 3

(习题册 1.1 Q6) 证明: $X$ 是 Hausdorff, 当且仅当对角线 $\Delta=\left\{\left(x,x\right):x\in X\right\}\subset X\times X$ 在 $X\times X$ 的乘积拓扑下闭.

### 解答 3

($\Rightarrow$) 设 $X$ Hausdorff (**定义 18.1**). 由**定义 4.2 (闭集)**, 只需证 $\left(X\times X\right)\setminus\Delta$ 开. 任取 $\left(x,y\right)\notin\Delta$, 即 $x\neq y$. 由 Hausdorff, 存在不交开邻域 $O_x\ni x$, $O_y\ni y$, $O_x\cap O_y=\varnothing$. 由**定义 20.1 (乘积拓扑的基)**, $O_x\times O_y$ 是乘积拓扑的开集且含 $\left(x,y\right)$. 又 $O_x\times O_y$ 不含任何对角线点: 若 $\left(z,z\right)\in O_x\times O_y$, 则 $z\in O_x\cap O_y=\varnothing$, 矛盾. 故

$$
O_x\times O_y\subset\left(X\times X\right)\setminus\Delta.
$$

于是 $\left(X\times X\right)\setminus\Delta$ 中每一点都有含于其中的开邻域, 即 $\left(X\times X\right)\setminus\Delta$ 是这些 $O_x\times O_y$ 之并, 故其开. 由**定义 4.2**, $\Delta$ 闭.

($\Leftarrow$) 设 $\Delta$ 闭, 则 $\left(X\times X\right)\setminus\Delta$ 开. 任取 $x\neq y\in X$, 则 $\left(x,y\right)\in\left(X\times X\right)\setminus\Delta$ 为开集. 由**定义 20.1 (乘积拓扑的基)**, 存在开邻域 $O_x\ni x$, $O_y\ni y$ 使

$$
O_x\times O_y\subset\left(X\times X\right)\setminus\Delta.
$$

断言 $O_x\cap O_y=\varnothing$: 若 $z\in O_x\cap O_y$, 则 $\left(z,z\right)\in O_x\times O_y$, 与上式矛盾 (因 $\left(z,z\right)\in\Delta$). 故 $O_x,O_y$ 是 $x,y$ 的不相交开邻域, 由**定义 18.1**, $X$ Hausdorff. $\blacksquare$

## 4

(习题册 1.2 Main exercise Q1) 设 $A\subset X$, $F\subset A$. 证明: $F$ 在 $A$ 中闭当且仅当存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$.

### 解答 4

($\Leftarrow$) 设 $F'$ 在 $X$ 中闭, $F=F'\cap A$. 则

$$
A\setminus F=A\setminus\left(F'\cap A\right)=A\cap\left(X\setminus F'\right).
$$

$X\setminus F'$ 在 $X$ 中开 (**定义 4.2**), 故 $A\cap\left(X\setminus F'\right)$ 是 $A$ 的子空间开集 (**定义 9.1**). 由**定义 4.2**, $F$ 在 $A$ 中闭.

($\Rightarrow$) 设 $F$ 在 $A$ 中闭, 则 $A\setminus F$ 在 $A$ 中开. 由**定义 9.1 (子空间拓扑)**, 存在 $X$ 中开集 $O$ 使 $A\setminus F=O\cap A$. 令 $F'=X\setminus O$, 则 $F'$ 在 $X$ 中闭 (**定义 4.2**), 且

$$
F'\cap A=\left(X\setminus O\right)\cap A=A\setminus\left(O\cap A\right)=A\setminus\left(A\setminus F\right)=F.
$$

$\blacksquare$

## 5

(习题册 1.2 Q2) 若 $\mathcal B$ 是 $X$ 的基, 证明 $\left\{B\cap A:B\in\mathcal B\right\}$ 是 $A$ (子空间拓扑) 的基.

### 解答 5

记 $\mathcal B_A=\left\{B\cap A:B\in\mathcal B\right\}$. 每个 $B\cap A$ 是 $A$ 中开集 (**定义 9.1**). 用**命题 7.3 (基判定开集)**: 任取 $A$ 中开集 $U$ 与 $x\in U$. 由**定义 9.1**, 存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 则 $x\in U\subset O$, 即 $x\in O$. 因 $\mathcal B$ 是 $X$ 的基, 由**命题 7.3** 存在 $B\in\mathcal B$ 使 $x\in B\subset O$. 于是

$$
x\in B\cap A\subset O\cap A=U,\qquad B\cap A\in\mathcal B_A.
$$

再由**命题 7.3**, $\mathcal B_A$ 是 $A$ 的基. $\blacksquare$

## 6

(习题册 1.2 Q3) 若 $A$ 在 $X$ 中开 (闭), 证明 $A$ 的开 (闭) 集在 $X$ 中也开 (闭).

### 解答 6

**开集情形.** 设 $U$ 是 $A$ 中开集. 由**定义 9.1**, 存在 $X$ 中开集 $O$ 使 $U=O\cap A$. 因 $A$ 在 $X$ 中开, $O$ 与 $A$ 都是 $X$ 中开集, 其交 $U=O\cap A$ 是有限个开集之交, 由**定义 4.1 (拓扑)** 知其开.

**闭集情形.** 设 $F$ 是 $A$ 中闭集. 由第 4 题 ($\Rightarrow$) 方向, 存在 $X$ 中闭集 $F'$ 使 $F=F'\cap A$. 因 $A$ 在 $X$ 中闭, $F'$ 与 $A$ 都是 $X$ 中闭集; 闭集族对任意交封闭 (**定义 4.2**), 故 $F=F'\cap A$ 在 $X$ 中闭. $\blacksquare$

## 7

(习题册 1.2 Q4) 证明包含映射 $\iota:A\to X$ 连续; 子空间拓扑即 $\iota$ 诱导的初始 (弱) 拓扑.

### 解答 7

**连续性.** 任取 $X$ 中开集 $O$, 则

$$
\iota^{-1}\left(O\right)=O\cap A,
$$

是 $A$ 的子空间开集 (**定义 9.1**). 由**定义 3.1 (连续)**, $\iota$ 连续.

**初始拓扑.** 由**定义 10.1 (初始/拉回拓扑)**, 由 $\iota:A\to X$ 诱导的 $A$ 上初始拓扑为

$$
\left\{\iota^{-1}\left(O\right):O\text{ 在 }X\text{ 中开}\right\}=\left\{O\cap A:O\text{ 在 }X\text{ 中开}\right\},
$$

这恰是**定义 9.1 (子空间拓扑)** 中的 $\mathcal O_A$. 故子空间拓扑就是 $\iota$ 诱导的初始拓扑. $\blacksquare$

## 8

(习题册 1.2 Q5) 设 $A\subset B\subset X$, $B$ 带 $X$ 诱导的子空间拓扑. 证明: $A$ 在 $B$ 中的闭包等于 $A$ 在 $X$ 中的闭包交 $B$.

### 解答 8

记 $\overline A^{\,X}$ 为 $A$ 在 $X$ 中的闭包, $\overline A^{\,B}$ 为 $A$ 在 $B$ 中的闭包. 用**0922 §6 (闭包的邻域定义)**: $x\in\overline A^{\,X}\Leftrightarrow x$ 在 $X$ 中的每个邻域都与 $A$ 相交.

($\subset$) 取 $x\in\overline A^{\,B}$. 首先 $x\in B$. 任取 $X$ 中开邻域 $U\ni x$. 则 $U\cap B$ 是 $B$ 中开集且含 $x$ (**定义 9.1**). 由 $x\in\overline A^{\,B}$,

$$
\varnothing\neq\left(U\cap B\right)\cap A=U\cap A,
$$

其中用到 $A\subset B$. 故 $x$ 在 $X$ 中的每个邻域都与 $A$ 相交, $x\in\overline A^{\,X}$. 结合 $x\in B$ 得 $x\in\overline A^{\,X}\cap B$.

($\supset$) 取 $x\in\overline A^{\,X}\cap B$, 即 $x\in B$ 且 $x\in\overline A^{\,X}$. 任取 $B$ 中开邻域 $W\ni x$. 由**定义 9.1**, 存在 $X$ 中开集 $U$ 使 $W=U\cap B$. 则 $U$ 是 $x$ 在 $X$ 中的开邻域, 由 $x\in\overline A^{\,X}$ 得 $U\cap A\neq\varnothing$. 因 $A\subset B$,

$$
U\cap A=\left(U\cap B\right)\cap A=W\cap A,
$$

故 $W\cap A\neq\varnothing$. 即 $x$ 在 $B$ 中的每个邻域都与 $A$ 相交, $x\in\overline A^{\,B}$.

综上,

$$
\boxed{\overline A^{\,B}=\overline A^{\,X}\cap B}.
$$

$\blacksquare$

## 9

(习题册 1.2 Q6) 设 $\overline A$ 是 $A$ 在 $X$ 中的闭包. 证明 $A$ 在 $\overline A$ (带 $\overline A$ 上的诱导拓扑) 中稠密.

### 解答 9

由**0922 §6 (闭包的邻域定义与稠密)**, 要证 $A$ 在 $\overline A$ 中稠密, 即证 $A$ 在 $\overline A$ 中的闭包等于 $\overline A$.

一方面, $A\subset\overline A$, 故 $A$ 在 $\overline A$ 中的闭包作为 $\overline A$ 的子集, 含于 $\overline A$. 另一方面, 任取 $x\in\overline A$. 任取 $x$ 在 $\overline A$ 中的开邻域 $W$. 由**定义 9.1 (子空间拓扑)**, 存在 $X$ 中开集 $U$ 使 $W=U\cap\overline A$. 因 $x\in\overline A$ 且 $U$ 是 $x$ 在 $X$ 中的开邻域, 由**0922 §6 (闭包的邻域定义)** 得 $U\cap A\neq\varnothing$. 又 $A\subset\overline A$, 故

$$
U\cap A=\left(U\cap\overline A\right)\cap A=W\cap A\neq\varnothing.
$$

即 $x$ 在 $\overline A$ 中的每个邻域都与 $A$ 相交, 故 $x$ 属于 $A$ 在 $\overline A$ 中的闭包. 于是 $\overline A$ 含于 $A$ 在 $\overline A$ 中的闭包, 结合反向包含得 $A$ 在 $\overline A$ 中的闭包恰为 $\overline A$, 即 $A$ 在 $\overline A$ 中稠密. $\blacksquare$

## 10

(习题册 1.2 Q8) 若 $X$ 是 Hausdorff 空间, 证明 $A$ (带诱导拓扑) 也是 Hausdorff.

### 解答 10

这是**命题 13.4 (Hausdorff 的继承)** 的子空间部分, 证明如下. 任取 $a\neq b\in A$. 因 $A\subset X$ 且 $X$ Hausdorff (**定义 18.1**), 存在 $X$ 中不交开邻域 $O_a\ni a$, $O_b\ni b$, $O_a\cap O_b=\varnothing$. 由**定义 9.1 (子空间拓扑)**,

$$
U_a:=O_a\cap A,\qquad U_b:=O_b\cap A
$$

是 $A$ 中开集, 分别含 $a,b$. 且

$$
U_a\cap U_b=\left(O_a\cap O_b\right)\cap A=\varnothing\cap A=\varnothing.
$$

故 $a,b$ 在 $A$ 中有不相交开邻域. 由**定义 18.1**, $A$ 是 Hausdorff. $\blacksquare$

## 11

(习题册 1.2 Q9) 构造例子: 子空间 $A\subset X$ 是 Hausdorff, 但 $A$ 中某两点在 $X$ 中没有不相交邻域. (提示: $Y=X\cup\left\{\omega\right\}$, $\omega$ 为额外点, $Y$ 中非空开集形如 $O\cup\left\{\omega\right\}$, $O$ 为 $X$ 中开集.)

### 解答 11

取 $X_0=\mathbb R$ 带通常拓扑, $\omega$ 为额外点, 令 ambient 空间 $Z=X_0\cup\left\{\omega\right\}$. 规定 $Z$ 中开集为 $\varnothing$ 以及所有形如

$$
O\cup\left\{\omega\right\}\qquad\left(O\text{ 为 }X_0=\mathbb R\text{ 中开集}\right)
$$

的集合.

先验证这是拓扑 (**定义 4.1 (拓扑)**): $\varnothing$ 开; $Z=\mathbb R\cup\left\{\omega\right\}$ 对应 $O=\mathbb R$ 开. 任意并 $\bigcup_\alpha\left(O_\alpha\cup\left\{\omega\right\}\right)=\left(\bigcup_\alpha O_\alpha\right)\cup\left\{\omega\right\}$ 开; 有限交 $\left(O_1\cup\left\{\omega\right\}\right)\cap\left(O_2\cup\left\{\omega\right\}\right)=\left(O_1\cap O_2\right)\cup\left\{\omega\right\}$ 开.

取子空间 $A=X_0=\mathbb R\subset Z$. 由**定义 9.1 (子空间拓扑)**, $A$ 中开集为 $U\cap A$ ($U$ 为 $Z$ 中开): $U=\varnothing$ 给 $\varnothing$, $U=O\cup\left\{\omega\right\}$ 给 $U\cap A=O$. 故 $A$ 的子空间拓扑就是 $\mathbb R$ 的通常拓扑, 因而 $A$ 是 Hausdorff (**命题 13.2**: 度量空间皆 Hausdorff).

但取任意 $a\neq b\in A$. $Z$ 中任何含 $a$ ($a\neq\omega$) 的非空开邻域 $V_a$, 必形如 $O_a\cup\left\{\omega\right\}$, 故 $\omega\in V_a$; 同理 $\omega\in V_b$. 于是

$$
\omega\in V_a\cap V_b,
$$

即 $V_a,V_b$ 不可能不相交. 故 $A$ 中两点 $a,b$ 在 ambient 空间 $Z$ 中没有不相交邻域. $\blacksquare$
