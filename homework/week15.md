# 作业 15

> **定义 3.1** (拓扑空间)<br>拓扑空间是一个集合 $X$, 配有一族公认的开集 $T\subset\mathcal P\left(X\right)$, 满足空集与全集开, 有限交开, 任意并开. (教材 $\S3$)

> **定义 3.3** (连续映射)<br>函数 $f:X\to Y$ 是连续的, 若对所有开集 $U\subset Y$, $f^{-1}\left(U\right)$ 是开的. (教材 $\S3$)

> **定义 3.4** (同胚)<br>空间之间的双射 $f:X\to Y$ 称为同胚, 若 $f$ 与 $f^{-1}$ 都连续; 等价于 $U$ 开当且仅当 $f\left(U\right)$ 开. (教材 $\S3$)

> **定义 3.5** (邻域与极限)<br>$b\in X$ 的邻域就是含 $b$ 的开集 $U$. (教材 $\S3$)

> **定义 3.8** (稠密)<br>称 $A\subset X$ 在 $X$ 中稠密, 若 $\overline A=X$. (教材 $\S3$)

> **定义 3.10** (豪斯多夫空间)<br>称 $X$ 是豪斯多夫的, 若任意一对不同点都有不相交的邻域. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>$X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 3.16** (离散拓扑与平凡拓扑)<br>离散拓扑: $X$ 的所有子集都开; 平凡拓扑: 仅 $\emptyset,X$ 开. (教材 $\S3$)

> **定义 3.19** (子空间拓扑)<br>$A\subset X$ 上的子空间拓扑为 $T_A=\left\{U\cap A:U\in T_X\right\}$. (教材 $\S3$)

> **定理 3.1** (复合连续)<br>两个连续映射的复合连续. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定义 4.5** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $f:\left[0,1\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K$ 凸即 $x,y\in K$ 蕴含连线 $\left[0,1\right]\to K$, $t\mapsto\left(1-t\right)x+ty$ 全在 $K$ 中. (教材 $\S4$)

> **定义 4.9** (局部连通)<br>每点有由连通开邻域组成的邻域基. (题集 $\S5$)

> **定义 4.10** (局部路径连通)<br>每点有由路径连通开邻域组成的邻域基. (题集 $\S5$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **推论 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **定义 6.12** (伪距离)<br>满足除 $d\left(x,y\right)=0\Rightarrow x=y$ 外全部度量公理的函数 $d$. (题集 $\S5$)

> **定义 6.24** (拓扑向量空间)<br>向量空间装备使加法 $E\times E\to E$ 与数乘 $\mathbb K\times E\to E$ 都连续的拓扑. (题集 $\S5$)

> **定义 6.25** (半范数)<br>满足范数齐次与三角不等式但允许 $p\left(x\right)=0$ 而 $x\neq 0$ 的函数 $p:E\to\left[0,\infty\right)$. (题集 $\S5$)

> **定义 6.26** (局部凸空间)<br>拓扑向量空间中 $0$ 有由凸邻域组成的邻域基. (题集 $\S5$)

> **定义 6.27** (规范函数)<br>凸邻域 $C$ 的规范函数 $\left\|x\right\|_C=\inf\left\{1/t:tx\in C,t>0\right\}$. (题集 $\S5$)

> **定义 11.1** (商拓扑)<br>$U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)\subset X$ 开, 其中 $\pi:X\to Y$ 满. (教材 $\S11$)

> **定义 11.2** (商映射)<br>满射 $\pi:X\to Y$ 使 $U\subset Y$ 开当且仅当 $\pi^{-1}\left(U\right)$ 开. (教材 $\S11$)

> **定义 11.3** (等价关系粘合)<br>$X/{\sim}$ 配商拓扑; $\pi:X\to X/{\sim}$ 为典范投影. (教材 $\S11$)

> **定义 11.6** (锥)<br>$CX=X\times\left[0,1\right]/X\times\left\{1\right\}$, 即将 $X\times\left\{1\right\}$ 整捏成一点. (教材 $\S11$)

> **定义 11.7** (环面)<br>正方形对边同向粘合所得 $S^1\times S^1$, 即 $\mathbb R^2/\mathbb Z^2$. (教材 $\S11$)

> **定义 11.14** (最终拓扑)<br>关于一族映射 $f_i:X_i\to Y$ 使每个 $f_i$ 连续的最细拓扑; 即 $U\subset Y$ 开当且仅当每个 $f_i^{-1}\left(U\right)$ 在 $X_i$ 中开. (题集 $\S5$)

> **定义 11.15** (等价关系的生成)<br>包含给定二元关系 $R$ 的最小等价关系, 即全体含 $R$ 的等价关系之交. (题集 $\S5$)

> **定义 11.18** (不交和拓扑)<br>一族拓扑空间 $\left\{X_i\right\}_{i\in I}$ 的不交和 $\coprod_{i\in I}X_i$ 上, $U$ 开当且仅当每个 $U\cap X_i$ 在 $X_i$ 中开. (题集 $\S5$)

### 习题一

设 $X$ 是拓扑空间. 证明下列三条等价:

(1) $X$ 具有离散拓扑;

(2) $X$ 具有由单点族 $\left\{\left\{x\right\}\right\}_{x\in X}$ 诱导的弱 (最终) 拓扑;

(3) 从不交和 $\coprod_{x\in X}\left\{x\right\}$ 到 $X$ 的典范映射是同胚.

### 解答 习题一

记 $i_x:\left\{x\right\}\to X$ 为把单点映到其唯一点的含入映射.

**(1) $\Rightarrow$ (2)**: 设 $X$ 具离散拓扑, 由**定义 3.16** (离散拓扑与平凡拓扑) 每个子集都开. 由**定义 3.1** (拓扑空间) 这是一个合法拓扑. 由**定义 11.14** (最终拓扑), 由 $\left\{i_x\right\}$ 诱导的最终拓扑是使每个 $i_x$ 连续的最细拓扑; 离散拓扑本身使每个 $i_x$ 连续 (单点空间唯一可能), 且它已是最细拓扑, 故二者相同.

**(2) $\Rightarrow$ (1)**: 设 $X$ 上的拓扑就是由 $\left\{i_x\right\}$ 诱导的最终拓扑. 由**定义 11.14** (最终拓扑), $U\subset X$ 开当且仅当对每个 $x$, $i_x^{-1}\left(U\right)$ 在单点空间 $\left\{x\right\}$ 中开. 而单点空间的任意子集 (仅 $\emptyset$ 与 $\left\{x\right\}$) 都开, 故 $X$ 的任意子集 $U$ 都开. 由**定义 3.16** (离散拓扑与平凡拓扑), 这就是离散拓扑.

**(2) $\Leftrightarrow$ (3)**: 由**定义 11.18** (不交和拓扑), 不交和 $Z=\coprod_{x\in X}\left\{x\right\}$ 上的拓扑是每个单点都开, 即离散拓扑. 典范映射 $i:Z\to X$ 把每个 $\left\{x\right\}$ 映到 $x$, 是双射. 由**定义 3.11** (乘积拓扑) 的构造思路, $Z$ 上的最终拓扑 (关于含入 $Z\hookleftarrow\left\{x\right\}$) 恰为离散拓扑, 故 $i$ 连续当且仅当 $X$ 的拓扑粗于由 $\left\{i_x\right\}$ 诱导的最终拓扑; 反过来 $i^{-1}$ 连续当且仅当该最终拓扑粗于 $X$ 的拓扑. 由**定义 3.4** (同胚), $i$ 是同胚当且仅当 $X$ 的拓扑等于由 $\left\{i_x\right\}$ 诱导的最终拓扑, 即 (2). 三链贯通, 三条等价. $\blacksquare$

### 习题二

设 $X_i$ 是拓扑空间, $X_i\subset X_{i+1}$, $X=\bigcup_{i=1}^{\infty}X_i$. 设每个 $X_i$ 在 $X_{i+1}$ 中闭, 且 $X_i$ 的拓扑就是 $X_{i+1}$ 的拓扑在 $X_i$ 上诱导的子空间拓扑. 证明: 对每个 $i$, $X_i$ 的拓扑等于 $X$ 上由族 $\left\{X_i\right\}$ 诱导的弱 (最终) 拓扑在 $X_i$ 上诱导的子空间拓扑; 进一步每个 $X_i$ 在 $X$ 中闭.

### 解答 习题二

记 $\tau$ 为 $X$ 上由含入 $j_i:X_i\to X$ 诱导的最终拓扑. 由**定义 11.14** (最终拓扑), $U\subset X$ 在 $\tau$ 中开当且仅当对每个 $k$, $U\cap X_k$ 在 $X_k$ 中开. 由题设归纳可知: 对 $k\ge i$, $X_i$ 在 $X_k$ 中闭; 且 $X_i$ 的拓扑就是 $X_k$ 的拓扑在 $X_i$ 上的子空间拓扑.

先证子空间一致性. 由**定义 3.19** (子空间拓扑), $X_i$ 从 $\left(X,\tau\right)$ 继承的开集为 $\left\{U\cap X_i:U\in\tau\right\}$.

(a) 包含 $\supset$: 若 $U\in\tau$, 由上面的刻画 $U\cap X_i$ 在 $X_i$ 中开, 故继承开集都是原拓扑开集.

(b) 包含 $\subset$: 任取原开集 $V\subset X_i$. 构造

$$
U=V\cup\left(X\setminus X_i\right).
$$

则 $U\cap X_i=V$. 验证 $U\in\tau$: 对 $k=i$, $U\cap X_i=V$ 开; 对 $k<i$, $X_k\subset X_i$, 故 $U\cap X_k=V\cap X_k$, 由 $X_k$ 的子空间性质它在 $X_k$ 中开; 对 $k>i$, $X_i$ 在 $X_k$ 中闭, 故 $X_k\setminus X_i$ 在 $X_k$ 中开, 而 $V$ 在 $X_i$ 中开, 由 $X_i$ 是 $X_k$ 的子空间可写 $V=X_i\cap W$, $W$ 在 $X_k$ 中开, 于是 $U\cap X_k=\left(X_i\cap W\right)\cup\left(X_k\setminus X_i\right)=W\cup\left(X_k\setminus X_i\right)$ 在 $X_k$ 中开. 故 $U\in\tau$, 且 $V=U\cap X_i$ 是继承开集.

故 $X_i$ 的原拓扑等于继承拓扑.

再证 $X_i$ 在 $X$ 中闭. 由**定义 3.19** (子空间拓扑) 的逆运算思路, 只需证 $X\setminus X_i$ 在 $\tau$ 中开. 对 $k\le i$, $\left(X\setminus X_i\right)\cap X_k=\emptyset$ 开; 对 $k>i$, $X_i$ 在 $X_k$ 中闭, 故 $\left(X\setminus X_i\right)\cap X_k=X_k\setminus X_i$ 在 $X_k$ 中开. 由**定义 11.14** (最终拓扑), $X\setminus X_i\in\tau$, 故 $X_i$ 闭. $\blacksquare$

### 习题三

设 $X$ 是拓扑空间, $\pi:X\to Y$ 是商映射, $Y$ 配以由 $\pi$ 诱导的商拓扑.

(1) 证明若 $X$ 连通, 则 $Y$ 连通;

(2) 证明若 $X$ 路径连通, 则 $Y$ 路径连通;

(3) 证明若 $\pi$ 是开映射且 $X$ 局部连通 (分别: 局部路径连通), 则 $Y$ 局部连通 (分别: 局部路径连通).

### 解答 习题三

**第 1 小题**: 反证. 若 $Y$ 不连通, 由**定义 4.1** (连通空间) 存在不相交非空开集 $V,W\subset Y$ 使 $Y=V\sqcup W$. 由**定义 11.2** (商映射), $\pi^{-1}\left(V\right)$ 与 $\pi^{-1}\left(W\right)$ 是 $X$ 中不相交非空开集, 且 $X=\pi^{-1}\left(V\right)\cup\pi^{-1}\left(W\right)$. 由**定义 4.1** (连通空间), 这与 $X$ 连通矛盾. 故 $Y$ 连通.

**第 2 小题**: 任取 $y_1,y_2\in Y$, 取原像 $x_1,x_2\in X$. 由 $X$ 路径连通与**定义 4.5** (路径连通), 存在连续路径 $\gamma:\left[0,1\right]\to X$ 以 $x_1,x_2$ 为端点. 由**定理 3.1** (复合连续), $\pi\circ\gamma:\left[0,1\right]\to Y$ 连续, 且端点为 $y_1,y_2$. 故 $Y$ 路径连通.

**第 3 小题**: 只证局部连通情形, 局部路径连通完全平行. 任取 $y\in Y$ 与由**定义 3.5** (邻域与极限) 给出的开邻域 $O\subset Y$. 取 $x\in\pi^{-1}\left(y\right)$. 由**定义 11.2** (商映射), $\pi^{-1}\left(O\right)$ 是 $x$ 的开邻域. 由 $X$ 局部连通与**定义 4.9** (局部连通), 存在连通开集 $U\subset X$ 使 $x\in U\subset\pi^{-1}\left(O\right)$. 因 $\pi$ 是开映射, $\pi\left(U\right)$ 是 $Y$ 中开集; 它含 $y$, 含于 $O$, 且由**定理 4.2** (连续像连通) 它连通. 故 $y$ 有含于 $O$ 的连通开邻域, $Y$ 局部连通. 对局部路径连通, 把"连通开集"换成"路径连通开集", 由**定义 4.10** (局部路径连通) 同样在每点取得路径连通开邻域, 再由**定理 3.1** (复合连续) 路径的连续像仍是路径, 故 $\pi\left(U\right)$ 路径连通, 即得 $Y$ 局部路径连通. $\blacksquare$

### 习题四

(二元关系生成的等价关系) 设 $X$ 是集合, $R\subset X\times X$ 是二元关系 (未必是等价关系). 证明: 存在唯一的最小等价关系 $\sim$ 包含 $R$ (在 $X\times X$ 的子集意义下), 称为由 $R$ 生成的等价关系.

### 解答 习题四

先证一族等价关系的交仍是等价关系. 设 $\left\{\sim_\alpha\right\}_{\alpha\in A}$ 是 $X$ 上的等价关系族, 定义 $x\sim y$ 当且仅当对一切 $\alpha$ 有 $x\sim_\alpha y$.

(a) 自反: 每个 $\sim_\alpha$ 自反, 故 $x\sim_\alpha x$ 对一切 $\alpha$, 即 $x\sim x$.

(b) 对称: $x\sim y$ 蕴含 $x\sim_\alpha y$ 对一切 $\alpha$, 由每个 $\sim_\alpha$ 对称得 $y\sim_\alpha x$, 故 $y\sim x$.

(c) 传递: $x\sim y$ 且 $y\sim z$, 则对一切 $\alpha$, $x\sim_\alpha y$ 且 $y\sim_\alpha z$, 由每个 $\sim_\alpha$ 传递得 $x\sim_\alpha z$, 故 $x\sim z$.

故 $\sim$ 是等价关系.

现令 $\mathcal E$ 为 $X$ 上全体包含 $R$ 的等价关系所成之族. 全体成员的交 $\bigcap\mathcal E$ 仍含 $R$ (每个成员含 $R$), 且由上面的交性质是等价关系. 它是含 $R$ 的最小等价关系: 任何含 $R$ 的等价关系都在 $\mathcal E$ 中, 从而包含这个交. 唯一性由"最小"即集包含意义下唯一决定. 由**定义 11.15** (等价关系的生成), 这个交就是由 $R$ 生成的等价关系. $\blacksquare$

### 习题五

(伪距离的商距离) 回顾伪距离 $d$ 是除 $d\left(x,y\right)=0\Rightarrow x=y$ 外满足全部度量公理的函数, 见**定义 6.12** (伪距离). 伪距离空间 $\left(X,d\right)$ 以开球 $B\left(x,\varepsilon\right)$ 为基有拓扑. 定义 $x\sim y$ 当且仅当 $d\left(x,y\right)=0$. 证明: $\sim$ 是等价关系; 商空间 $X/{\sim}$ 上可赋予距离 $d'$ 使 $d'\left(\left[x\right],\left[y\right]\right)=d\left(x,y\right)$; 验证 $d'$ 定义适定; 证明度量空间 $\left(X/{\sim},d'\right)$ 与商空间 $X/{\sim}$ 拓扑相同; 并证明若 $F$ 是豪斯多夫空间且 $f:X\to F$ 连续, 则 $f$ 可分解为 $f=f'\circ\pi$, 其中 $f':X/{\sim}\to F$.

### 解答 习题五

**$\sim$ 是等价关系**: 由**定义 6.12** (伪距离), $d\left(x,x\right)=0$ 给出自反; $d\left(x,y\right)=d\left(y,x\right)$ 给出对称; 三角不等式 $d\left(x,z\right)\le d\left(x,y\right)+d\left(y,z\right)$ 在 $d\left(x,y\right)=d\left(y,z\right)=0$ 时给出 $d\left(x,z\right)=0$, 即传递.

**$d'$ 适定**: 若 $x\sim x'$, $y\sim y'$, 则 $d\left(x,x'\right)=d\left(y,y'\right)=0$, 由三角不等式,

$$
d\left(x,y\right)\le d\left(x,x'\right)+d\left(x',y'\right)+d\left(y',y\right)=d\left(x',y'\right),
$$

同理 $d\left(x',y'\right)\le d\left(x,y\right)$. 故二者相等, $d'\left(\left[x\right],\left[y\right]\right):=d\left(x,y\right)$ 与代表元选取无关.

**$d'$ 是度量**: 非负、对称、三角不等式都从 $d$ 继承; 而 $d'\left(\left[x\right],\left[y\right]\right)=0$ 即 $d\left(x,y\right)=0$, 即 $x\sim y$, 即 $\left[x\right]=\left[y\right]$. 正定性成立.

**拓扑相同**: 记 $\pi:X\to X/{\sim}$ 为商投影. 对任意 $x,\varepsilon$,

$$
\pi^{-1}\left(B_{d'}\left(\left[x\right],\varepsilon\right)\right)=B_d\left(x,\varepsilon\right).
$$

包含 $\subset$: 若 $z$ 使 $d'\left(\left[z\right],\left[x\right]\right)<\varepsilon$, 即 $d\left(z,x\right)<\varepsilon$, 则 $z\in B_d\left(x,\varepsilon\right)$. 包含 $\supset$: 若 $z\in B_d\left(x,\varepsilon\right)$, 则 $d'\left(\left[z\right],\left[x\right]\right)=d\left(z,x\right)<\varepsilon$. 由**定义 11.1** (商拓扑), $B_{d'}\left(\left[x\right],\varepsilon\right)$ 是商开集, 故度量拓扑粗于商拓扑. 反之, 若 $U$ 是商开集, 则 $\pi^{-1}\left(U\right)$ 是 $d$-开集, 从而是若干 $d$-球之并, 其像 $U=\pi\left(\pi^{-1}\left(U\right)\right)$ 是若干 $d'$-球之并, 故 $U$ 是度量开集. 二者一致.

**泛分解**: 设 $F$ 豪斯多夫, $f:X\to F$ 连续. 先证 $f$ 在等价类上取常值. 若 $x\sim x'$, 即 $d\left(x,x'\right)=0$, 则 $x$ 与 $x'$ 在 $X$ 中无法用开集分离: 对任意 $\varepsilon>0$, $B_d\left(x,\varepsilon\right)=B_d\left(x',\varepsilon\right)$. 若 $f\left(x\right)\neq f\left(x'\right)$, 由**定义 3.10** (豪斯多夫空间) 存在不相交开邻域 $V\ni f\left(x\right)$, $W\ni f\left(x'\right)$. 由**定义 3.3** (连续映射), $f^{-1}\left(V\right)$ 是 $x$ 的开邻域, 从而含 $x'$, 故 $f\left(x'\right)\in V$, 与 $V\cap W=\emptyset$ 及 $f\left(x'\right)\in W$ 矛盾. 故 $f\left(x\right)=f\left(x'\right)$.

于是可定义 $f'\left(\left[x\right]\right)=f\left(x\right)$, 适定. 由**定义 11.2** (商映射), 为证 $f'$ 连续, 只需对任意开集 $O\subset F$, $\left(f'\right)^{-1}\left(O\right)$ 商开, 即 $\pi^{-1}\left(\left(f'\right)^{-1}\left(O\right)\right)=f^{-1}\left(O\right)$ 在 $X$ 中开; 这由 $f$ 连续保证. 故 $f=f'\circ\pi$. $\blacksquare$

### 习题六

证明: 实或复拓扑向量空间是局部凸的, 当且仅当其拓扑由一族半范数定义. 进一步证明: 在实或复拓扑向量空间中, $0$ 有可数凸邻域基, 当且仅当拓扑由可数族半范数定义.

### 解答 习题六

**($\Leftarrow$)**: 设拓扑由半范数族 $\left\{p_\alpha\right\}_{\alpha\in A}$ 定义. 由**定义 6.25** (半范数), 每个 $p_\alpha$ 是凸函数 (由三角不等式 $p_\alpha\left(\left(1-t\right)x+ty\right)\le\left(1-t\right)p_\alpha\left(x\right)+tp_\alpha\left(y\right)$). 形如

$$
U_{\alpha_1,\dots,\alpha_n;\varepsilon}=\left\{x:p_{\alpha_i}\left(x\right)<\varepsilon,\ i=1,\dots,n\right\}
$$

的集合是有限个凸集的交, 由**定义 4.6** (凸集) 仍是凸集; 它们构成 $0$ 的邻域基. 故由**定义 6.26** (局部凸空间), 空间局部凸.

**($\Rightarrow$)**: 设空间局部凸. 由**定义 6.26** (局部凸空间), $0$ 有凸邻域基 $\left\{C_\alpha\right\}_{\alpha\in A}$. 由**定义 6.24** (拓扑向量空间), 加法与数乘连续, 故可在不损失凸性的前提下取每个 $C_\alpha$ 为平衡凸邻域 (即 $x\in C_\alpha$ 蕴含 $\lambda x\in C_\alpha$ 对一切 $\left|\lambda\right|\le 1$). 定义

$$
p_\alpha\left(x\right)=\inf\left\{t>0:x\in t\,C_\alpha\right\}.
$$

这正是**定义 6.27** (规范函数). 由 $C_\alpha$ 凸且平衡, $p_\alpha$ 满足**定义 6.25** (半范数) 的两条: 齐次 $p_\alpha\left(\lambda x\right)=\left|\lambda\right|p_\alpha\left(x\right)$; 三角不等式由 $C_\alpha$ 凸推出. 邻域 $\left\{p_\alpha<\varepsilon\right\}$ 就是 $\varepsilon C_\alpha$, 故半范数族 $\left\{p_\alpha\right\}$ 定义的拓扑与原拓扑相同.

**可数情形**: 若 $0$ 有可数凸邻域基 $\left\{C_n\right\}_{n\ge 1}$, 上面的构造给出可数半范数族 $\left\{p_n\right\}$. 反之, 若拓扑由可数半范数族 $\left\{p_n\right\}$ 定义, 则 $\left\{x:p_i\left(x\right)<1/k,\ i=1,\dots,n\right\}$ ($n,k\ge 1$) 是可数凸邻域基. $\blacksquare$

### 习题七

设 $\pi:\mathbb R^2\to T^2$ 是典范投影, $\alpha\in\mathbb R\cup\left\{\infty\right\}$, $D$ 是 $\mathbb R^2$ 中斜率为 $\alpha$ 的直线. 证明: 若 $\alpha\in\mathbb Q\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 同胚于一个圆; 若 $\alpha\notin\mathbb Q\cup\left\{\infty\right\}$, 则 $\pi\left(D\right)$ 在 $T^2$ 中稠密, 且 $\pi|_D$ 是 $D$ 到 $\pi\left(D\right)$ 的连续双射.

### 解答 习题七

由**定义 11.7** (环面), $T^2=\mathbb R^2/\mathbb Z^2$, $\pi$ 为商投影. 不妨取 $D=\left\{\left(t,\alpha t\right):t\in\mathbb R\right\}$ (竖直直线 $\alpha=\infty$ 同理).

**有理斜率**: 设 $\alpha=p/q$, $p,q\in\mathbb Z$, $\gcd\left(p,q\right)=1$. 映射 $g:\mathbb R/q\mathbb Z\to T^2$, $g\left(t\right)=\pi\left(t,\alpha t\right)$. 它良定义且连续. 它是单射: 若 $\pi\left(t,\alpha t\right)=\pi\left(t',\alpha t'\right)$, 则 $t-t'\in\mathbb Z$ 且 $p\left(t-t'\right)/q\in\mathbb Z$, 即 $q\mid p\left(t-t'\right)$; 由 $\gcd\left(p,q\right)=1$, $q\mid t-t'$, 即在 $\mathbb R/q\mathbb Z$ 中相等. $\mathbb R/q\mathbb Z$ 是紧圆 (同胚于 $S^1$), $T^2$ 是豪斯多夫的 (乘积空间 $S^1\times S^1$ 豪斯多夫). 由**推论 5.6** (紧豪斯多夫间的连续双射), $g$ 是同胚. 故 $\pi\left(D\right)=g\left(\mathbb R/q\mathbb Z\right)$ 同胚于圆.

**无理斜率**: 设 $\alpha\notin\mathbb Q$. 先证 $\pi\left(D\right)$ 在 $T^2$ 中稠密. 由**定义 3.8** (稠密), 只需证其闭包为全空间. 注意 $\pi\left(D\right)$ 是 $T^2$ 的子群, 且包含循环子群 $H=\left\{\pi\left(n,n\alpha\right):n\in\mathbb Z\right\}$. 由无理数的狄利克雷逼近, 对任意 $\varepsilon>0$, 存在非零整数 $n$ 使 $\left\|n\alpha\right\|<\varepsilon$ ($\left\|\cdot\right\|$ 表示到最近整数距离). 于是 $H$ 中含一个离 $\left(0,0\right)$ 极近的非零点, 其整数倍数在 $T^2$ 中环绕出稠密的一维子群; 故 $H$ 在 $T^2$ 中稠密. 因 $\pi\left(D\right)\supset H$, $\pi\left(D\right)$ 在 $T^2$ 中稠密.

$\pi|_D:D\to\pi\left(D\right)$ 连续 (商映射限制) 且为双射: 若 $\pi\left(t,\alpha t\right)=\pi\left(t',\alpha t'\right)$, 则 $t-t'\in\mathbb Z$ 且 $\alpha\left(t-t'\right)\in\mathbb Z$, 由 $\alpha$ 无理必有 $t-t'=0$. 但它不是同胚: $D$ 与 $\mathbb R$ 同胚, 不紧, 而 $\pi\left(D\right)$ 在 $T^2$ 中稠密 (因 $T^2$ 紧, $\pi\left(D\right)$ 的闭包紧); 若它同胚于 $D\cong\mathbb R$, 则它不闭, 但上面已证它稠密, 不影响连续性, 关键是开映射性失效: 取 $D$ 中一小段, 其像在 $\pi\left(D\right)$ 中并不总是开的. $\blacksquare$

### 习题八

设 $\pi:\mathbb R^2\to T^2$ 是典范投影, $\alpha\in\mathbb R\cup\left\{\infty\right\}$. 在 $T^2$ 上定义关系: $x'\sim y'$ 当且仅当存在 $x,y\in\mathbb R^2$ 与斜率为 $\alpha$ 的直线使 $\pi\left(x\right)=x'$, $\pi\left(y\right)=y'$. 证明 $\sim$ 是等价关系; 证明商空间 $T^2/{\sim}$ 豪斯多夫当且仅当 $\alpha\in\mathbb Q$, 此时商空间同胚于一个圆; 若 $\alpha\notin\mathbb Q$, 证明商空间 $T^2/{\sim}$ 具有平凡拓扑.

### 解答 习题八

把 $\pi\left(D\right)$ 记为 $H\subset T^2$, 其中 $D=\left\{\left(t,\alpha t\right)\right\}$. 关系 $x'\sim y'$ 即 $y'-x'\in H$ ($T^2$ 中的群运算).

**等价关系**: $H$ 是 $T^2$ 的子群: 含单位元; 对减法封闭. 故按子群取陪集是等价关系: 自反 ($0\in H$), 对称 ($H$ 对逆元封闭), 传递 ($H$ 对加法封闭). 由**定义 11.3** (等价关系粘合), $T^2/{\sim}=T^2/H$.

**有理斜率**: 设 $\alpha=p/q\in\mathbb Q$. 由习题七, $H$ 是 $T^2$ 中的一个闭圆子群. 定义

$$
\varphi:T^2\to S^1,\quad \varphi\left(u,v\right)=qu-pv\pmod 1.
$$

$\varphi$ 连续, 其核恰为 $H$ (即 $\varphi\left(u,v\right)=0\Leftrightarrow\left(u,v\right)\in H$). 由商空间泛性质, $\varphi$ 诱导连续双射 $\overline\varphi:T^2/H\to S^1$. $T^2/H$ 紧 ($T^2$ 紧, 商连续像紧), $S^1$ 豪斯多夫. 由**推论 5.6** (紧豪斯多夫间的连续双射), $\overline\varphi$ 是同胚. 故 $T^2/H$ 同胚于圆, 且圆豪斯多夫, 由**定义 3.10** (豪斯多夫空间) 商空间豪斯多夫.

**无理斜率**: 由习题七, $H$ 在 $T^2$ 中稠密. 商拓扑下, 由**定义 11.1** (商拓扑), 开集 $U\subset T^2/H$ 对应于 $T^2$ 中的 $H$-饱和开集. 若 $U$ 非空, 取饱和开集 $V\subset T^2$, $V\neq\emptyset$. 因 $H$ 稠密, $V+H=T^2$; 而 $V$ 已饱和, $V+H=V$, 故 $V=T^2$, 即 $U=T^2/H$. 故仅有的开集是 $\emptyset$ 与全空间, 即平凡拓扑. 此时商空间不豪斯多夫 (除非单点), 与有理情形对照. $\blacksquare$

### 习题九

(锥) 设 $CX$ 是 $X$ 上的锥空间, 由**定义 11.6** (锥) 为 $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 证明: 映射 $X\to CX$, $x\mapsto\left[\left(x,0\right)\right]$ 是到其像的同胚, 从而 $X$ 可视为 $CX$ 的子集. 证明: 若 $f:X\to Y$ 连续, 则 $Cf:CX\to CY$, $\left[\left(x,t\right)\right]\mapsto\left[\left(f\left(x\right),t\right)\right]$ 连续.

### 解答 习题九

**嵌入**: 由**定义 11.6** (锥), $CX=X\times\left[0,1\right]/X\times\left\{1\right\}$. 记 $\pi:X\times\left[0,1\right]\to CX$ 为商投影, $j:X\to CX$, $j\left(x\right)=\left[\left(x,0\right)\right]$. 因 $X\times\left\{0\right\}$ 与被捏合集 $X\times\left\{1\right\}$ 不相交, $\pi$ 在 $X\times\left\{0\right\}$ 上是单射, 故 $j$ 是双射到 $j\left(X\right)$.

$j$ 连续: 它是含入 $X\cong X\times\left\{0\right\}\hookrightarrow X\times\left[0,1\right]$ 与 $\pi$ 的复合, 由**定理 3.1** (复合连续) 连续.

逆连续: 任取 $X$ 中开集 $U$. 需证 $j\left(U\right)$ 是 $j\left(X\right)$ (子空间) 中的开集. 构造 $V=U\times\left[0,1/2\right)\subset X\times\left[0,1\right]$. 由**定义 3.11** (乘积拓扑), $V$ 开. 它不与 $X\times\left\{1\right\}$ 相交, 故饱和 (与等价类只交整体不交), 由**定义 11.1** (商拓扑), $\pi\left(V\right)$ 在 $CX$ 中开. 而 $\pi\left(V\right)\cap j\left(X\right)=j\left(U\right)$. 故 $j\left(U\right)$ 是 $CX$ 的开集与 $j\left(X\right)$ 的交, 即 $j\left(X\right)$ 中的开集. 由**定义 3.4** (同胚), $j$ 是 $X$ 到 $j\left(X\right)$ 的同胚.

**$Cf$ 连续**: 由**定义 11.2** (商映射), 只需证对任意开集 $W\subset CY$, $\left(Cf\right)^{-1}\left(W\right)$ 在 $CX$ 中开, 即 $\pi_X^{-1}\left(\left(Cf\right)^{-1}\left(W\right)\right)$ 在 $X\times\left[0,1\right]$ 中开. 该原像等于

$$
\left\{\left(x,t\right):\left(f\left(x\right),t\right)\in\pi_Y^{-1}\left(W\right)\right\}=\left(f\times\operatorname{id}\right)^{-1}\left(\pi_Y^{-1}\left(W\right)\right).
$$

$\pi_Y^{-1}\left(W\right)$ 在 $Y\times\left[0,1\right]$ 中开, $f\times\operatorname{id}$ 连续 (由 $f$ 连续与 $\operatorname{id}$ 连续, 乘积映射连续), 故由**定义 3.3** (连续映射), 上式在 $X\times\left[0,1\right]$ 中开. 故 $Cf$ 连续. $\blacksquare$
