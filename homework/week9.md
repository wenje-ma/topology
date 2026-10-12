# 作业 9

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 3.11** (乘积拓扑)<br>设 $X,Y$ 为拓扑空间. $X\times Y$ 上的乘积拓扑以形如 $U\times V$ 的集合为基, 其中 $U,V$ 分别是 $X,Y$ 中的开集. (教材 $\S3$)

> **定义 5.1** (开覆盖与有限子覆盖)<br>开覆盖 $\left\{U_i\right\}$ 满足 $X=\bigcup_i U_i$; 有限子覆盖为仍覆盖 $X$ 的有限子族. (教材 $\S5$)

> **定义 5.2** (紧致空间)<br>称 $X$ 是紧致的, 若 $X$ 的每个开覆盖都有有限子覆盖. (教材 $\S5$)

> **定义 5.3** (有限交性质)<br>闭集族 $\mathcal F$ 具有有限交性质, 若其任意有限子族之交非空; $X$ 紧致当且仅当任意具有限交性质的闭集族之交非空. (教材 $\S5$; 题集 $\S3.1$)

> **定理 5.9** (吉洪诺夫定理)<br>任意一族紧致空间的乘积在乘积拓扑下紧致. (教材 $\S5$)

> **定理 5.10** (有限交判据)<br>$X$ 紧致: 若闭集族 $\mathcal F$ 具有限交性质, 则 $\bigcap_{F\in\mathcal F}F\neq\emptyset$. (教材 $\S5$)

> **定理 5.15** (德布鲁因-埃尔德什定理)<br>若图 $G$ 的每个有限子图都可 $k$-染色, 则 $G$ 本身可 $k$-染色 (允许 $G$ 有不可数个顶点). (题集 $\S3.3$)

> **定义 11.16** (无向图与子图)<br>$G=\left(V,E\right)$, $E\subset V\times V$ 无序, 允许多重边; 子图保持顶点集 $V$ 只删边. (题集 $\S3.3$)

> **定义 11.17** ($k$-染色与 $k$-可染色)<br>$f:V\to\left\{1,\dots,k\right\}$ 使相邻点异色; 存在这样的 $f$ 则称 $G$ 可 $k$-染色. (题集 $\S3.3$)

### 习题一

给 $\left\{1,\dots,k\right\}$ 赋离散拓扑. 证明 $\left\{1,\dots,k\right\}$ 在该拓扑下紧致.

### 解答 习题一

设 $\mathcal U$ 是 $\left\{1,\dots,k\right\}$ 的任意开覆盖. 由**定义 5.1** (开覆盖与有限子覆盖), 对每个点 $i\in\left\{1,\dots,k\right\}$ 选取 $U_i\in\mathcal U$ 使 $i\in U_i$. 则 $\left\{U_1,\dots,U_k\right\}$ 是有限子族且仍覆盖 $\left\{1,\dots,k\right\}$. 由**定义 5.2** (紧致空间), $\left\{1,\dots,k\right\}$ 紧致. $\blacksquare$

### 习题二

用吉洪诺夫定理证明: 映射集合 $X=\left\{f:V\to\left\{1,\dots,k\right\}\right\}$ 紧致.

### 解答 习题二

由**定义 11.16** (无向图与子图), $V$ 是图的顶点集. 集合 $X=\left\{1,\dots,k\right\}^{V}=\prod_{v\in V}\left\{1,\dots,k\right\}$ 是离散有限空间 $\left\{1,\dots,k\right\}$ 的乘积. 由习题一, 每个因子紧致. 由**定理 5.9** (吉洪诺夫定理), 乘积 $X$ 在乘积拓扑下紧致. $\blacksquare$

### 习题三

对任意边子集 $F\subset E$, 定义

$$
X_F=\left\{f:V\to\left\{1,\dots,k\right\}:f\text{ 是 }\left(V,F\right)\text{ 的染色}\right\}.
$$

若 $F=\left\{\left(x,y\right)\right\}$ 只有一条边, 证明 $X_F$ 闭.

### 解答 习题三

一条边 $\left(x,y\right)$ 的染色条件即 $f\left(x\right)\neq f\left(y\right)$. 故

$$
X_F=\bigcup_{i\neq j}\left\{f:f\left(x\right)=i,\ f\left(y\right)=j\right\}.
$$

每个柱集 $C_{ij}=\left\{f:f\left(x\right)=i,\ f\left(y\right)=j\right\}$ 在乘积拓扑下是闭的: 由**定义 3.11** (乘积拓扑), 其补集是其余柱集之并, 故为开集; 由**定义 3.2** (闭集), $C_{ij}$ 闭. 而 $X_F$ 是有限个 $C_{ij}$ ($i\neq j$) 之并, 闭集的有限并仍闭. 故 $X_F$ 闭. $\blacksquare$

### 习题四

证明: 对任意 $F\subset E$, $X_F$ 闭.

### 解答 习题四

一个映射是 $\left(V,F\right)$ 的染色, 当且仅当它对每条边 $e\in F$ 都合法. 故

$$
X_F=\bigcap_{e\in F}X_{\left\{e\right\}}.
$$

由习题三, 每个 $X_{\left\{e\right\}}$ 闭; 由**定义 3.2** (闭集), 闭集的任意交仍闭. 故 $X_F$ 闭. $\blacksquare$

### 习题五

现设图 $G$ 的任意有限子图都可 $k$-染色, 即 $F\subset E$ 有限时 $X_F\neq\emptyset$. 考虑闭集族 $\mathcal F=\left\{X_F:F\subset E\text{ 有限}\right\}$. 证明 $\mathcal F$ 中任意有限个集合之交非空.

### 解答 习题五

设 $F_1,\dots,F_n\subset E$ 有限. 由染色条件逐条叠加,

$$
\bigcap_{i=1}^{n}X_{F_i}=X_{\bigcup_{i=1}^{n}F_i}.
$$

边集 $\bigcup_{i=1}^{n}F_i$ 有限, 由假设对应的子图可 $k$-染色, 即由**定义 11.17** ($k$-染色与 $k$-可染色), $X_{\bigcup_iF_i}\neq\emptyset$. 故有限交非空. 由**定义 5.3** (有限交性质), 闭集族 $\mathcal F$ 具有限交性质. $\blacksquare$

### 习题六

用 $X$ 的紧致性证明: $\mathcal F$ 中所有集合之交非空.

### 解答 习题六

由习题二, $X$ 紧致; 由习题四, 每个 $X_F$ 闭; 由习题五, $\mathcal F=\left\{X_F:F\subset E\text{ 有限}\right\}$ 是具有限交性质的非空闭集族. 由**定理 5.10** (有限交判据),

$$
\bigcap_{F\subset E\text{ 有限}}X_F\neq\emptyset.
$$

$\blacksquare$

### 习题七

证明德布鲁因-埃尔德什定理: 若图 $G$ 的任意有限子图都可 $k$-染色, 则 $G$ 可 $k$-染色. 即使 $G$ 有不可数个顶点也成立.

### 解答 习题七

由习题六, 可取

$$
f\in\bigcap_{F\subset E\text{ 有限}}X_F.
$$

对任意边 $e=\left(x,y\right)\in E$, 取 $F=\left\{e\right\}$; 因 $f\in X_{\left\{e\right\}}$, 由**定义 11.17** ($k$-染色与 $k$-可染色), $f\left(x\right)\neq f\left(y\right)$. 故 $f$ 是全图 $G=\left(V,E\right)$ 的合法 $k$-染色.

上述论证只用到**定理 5.9** (吉洪诺夫定理) 与**定理 5.10** (有限交判据), 二者对任意指标集 $V$ 都成立, 不依赖 $V$ 的可数性. 故顶点集 $V$ 可以不可数. 这证明了**定理 5.15** (德布鲁因-埃尔德什定理). $\blacksquare$
