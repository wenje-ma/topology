# 作业 8

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>若 $X$ 是豪斯多夫空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.12** (伪距离)<br>满足除 "$d\left(x,y\right)=0\Rightarrow x=y$" 外全部度量公理的函数; 商掉 $d=0$ 的等价类即得真度量. (题集 $\S1.3$)

> **定义 6.15** (点到集合的距离)<br>$d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. (题集 $\S3.2$)

> **定义 6.16** ($\epsilon$-邻域)<br>$U_\epsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)<\epsilon\right\}$. (题集 $\S3.2$)

> **定义 6.17** (豪斯多夫距离)<br>$d\left(A,B\right)=\inf\left\{r>0:A\subset U_r\left(B\right),\,B\subset U_r\left(A\right)\right\}$; 在紧子集族 $\mathcal K\left(X\right)$ 上是真度量. (题集 $\S3.2$)

### 习题一

设 $\left(X,d\right)$ 是度量空间. 证明朴素定义 $d\left(A,B\right)=\inf_{a\in A,\,b\in B}d\left(a,b\right)$ 一般不是度量.

### 解答 习题一

在 $\mathbb R^2$ (配通常欧氏距离) 中取

$$
A=\left\{\left(x,0\right):x\in\mathbb R\right\},\quad B=\left\{\left(n,1/n\right):n\in\mathbb Z_{>0}\right\}.
$$

由**定义 6.15** (点到集合的距离),

$$
d\left(A,B\right)\le d\left(\left(n,0\right),\left(n,1/n\right)\right)=1/n\to0,
$$

故 $d\left(A,B\right)=0$, 但 $A\neq B$. 这不满足**定义 6.1** (度量空间) 中"距离为零蕴含两点相等"的公理 (应用于集合时即两集合相等). 故该朴素定义一般不是度量. $\blacksquare$

> 这给出了我们需要定义豪斯多夫距离的一个原因.

### 习题二

定义集合 $A\subset X$ 的 $\epsilon$-邻域 $U_\epsilon\left(A\right)=\left\{x\in X:d\left(x,A\right)<\epsilon\right\}$, 其中 $d\left(x,A\right)=\inf_{a\in A}d\left(x,a\right)$. 证明: 对 $r_1,r_2>0$ 与任意 $A\subset X$,

$$
U_{r_1}\left(U_{r_2}\left(A\right)\right)\subset U_{r_1+r_2}\left(A\right),
$$

但反过来一般不成立.

### 解答 习题二

设 $x\in U_{r_1}\left(U_{r_2}\left(A\right)\right)$. 由**定义 6.16** ($\epsilon$-邻域), 存在 $y\in U_{r_2}\left(A\right)$ 使 $d\left(x,y\right)<r_1$; 再由**定义 6.15** (点到集合的距离), 存在 $a\in A$ 使 $d\left(y,a\right)<r_2$. 由**定义 6.1** (度量空间) 的三角不等式,

$$
d\left(x,a\right)\le d\left(x,y\right)+d\left(y,a\right)<r_1+r_2.
$$

故 $x\in U_{r_1+r_2}\left(A\right)$, 包含关系成立.

反之不真. 取 $X=\left\{0,1,3\right\}$ 赋通常距离, $A=\left\{0,3\right\}$, $r_1=r_2=1$. 由**定义 6.15** (点到集合的距离) 与**定义 6.16** ($\epsilon$-邻域), $d\left(1,A\right)=1$, 故

$$
U_1\left(A\right)=\left\{x:d\left(x,A\right)<1\right\}=\left\{0,3\right\},
$$

从而 $U_1\left(U_1\left(A\right)\right)=\left\{0,3\right\}$. 但 $d\left(1,A\right)=1<2$, 故 $1\in U_2\left(A\right)$. 因此 $U_{r_1+r_2}\left(A\right)\not\subset U_{r_1}\left(U_{r_2}\left(A\right)\right)$. $\blacksquare$

> 不可逆的原因正是因为邻域是严格小于, 这导致三角不等式变成了严格成立.

### 习题三

定义子集 $A,B\subset X$ 之间的豪斯多夫距离

$$
d_H\left(A,B\right)=\inf\left\{r>0:A\subset U_r\left(B\right),\,B\subset U_r\left(A\right)\right\}.
$$

证明豪斯多夫距离是伪距离, 即满足度量的全部公理, 只是 $d_H\left(A,B\right)=0$ 不一定蕴含 $A=B$.

### 解答 习题三

由**定义 6.17** (豪斯多夫距离), 非负性与对称性是显然的 (定义关于 $A,B$ 对称). 又 $d_H\left(A,A\right)=0$, 因为对任意 $r>0$, $A\subset U_r\left(A\right)$ 恒成立.

剩证三角不等式. 设 $A,B,C\subset X$. 由**定义 6.17** (豪斯多夫距离), $d_H\left(A,B\right)<r$ 意味着 $A\subset U_r\left(B\right)$ 且 $B\subset U_r\left(A\right)$. 若 $A\subset U_r\left(B\right)$ 且 $B\subset U_s\left(C\right)$, 由习题二的包含关系 (**定义 6.16** ($\epsilon$-邻域)),

$$
A\subset U_r\left(B\right)\subset U_r\left(U_s\left(C\right)\right)\subset U_{r+s}\left(C\right).
$$

同理 $C\subset U_{r+s}\left(A\right)$. 由**定义 6.17** (豪斯多夫距离), $d_H\left(A,C\right)\le r+s$. 令 $r\downarrow d_H\left(A,B\right)$, $s\downarrow d_H\left(B,C\right)$, 即得三角不等式

$$
d_H\left(A,C\right)\le d_H\left(A,B\right)+d_H\left(B,C\right).
$$

由**定义 6.12** (伪距离), 它满足除"距离为零蕴含相等"外全部公理, 故是伪距离. $\blacksquare$

> $d_H(A,B)=0\not\Rightarrow A=B$: 取 $A=(0,1)$, $B=[0,1]$, $d_H(A,B)=0$ 但 $A\ne B$.

### 习题四

证明: 对一切 $A\subset X$, $d_H\left(A,A\right)=0$. 若 $A,B$ 闭, 则 $d_H\left(A,B\right)=0$ 蕴含 $A=B$.

### 解答 习题四

现设 $A,B$ 闭且 $d_H\left(A,B\right)=0$. 任取 $a\in A$. 对每个 $n$, 由**定义 6.17** (豪斯多夫距离) 与 $d_H\left(A,B\right)=0$, 存在 $b_n\in B$ 使 $d_H\left(a,b_n\right)<1/n$. 于是 $b_n\to a$. 由**定义 3.2** (闭集), 闭集含其中序列的极限, 故 $a\in B$. 这证明 $A\subset B$. 交换 $A,B$ 同理得 $B\subset A$, 故 $A=B$. $\blacksquare$

### 习题五

证明: 若把豪斯多夫距离限制在紧子集族 $\mathcal K\left(X\right)$ 上, 则它是 $\mathcal K\left(X\right)$ 上的真度量.

### 解答 习题五

由习题三, $d_H$ 是伪距离, 已满足非负性、对称性与三角不等式. 剩证分离性. 设 $A,B\in\mathcal K\left(X\right)$ 紧致且 $d_H\left(A,B\right)=0$. 度量空间是豪斯多夫的, 由**定理 5.5** (豪斯多夫中紧集闭), 紧集 $A,B$ 在 $X$ 中闭. 由习题四的结论, $d_H\left(A,B\right)=0$ 且 $A,B$ 闭蕴含 $A=B$. 故分离性成立. $\blacksquare$
