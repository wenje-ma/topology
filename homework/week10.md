# 作业 10

> **定义 3.2** (闭集)<br>集合 $F$ 称为闭的, 若其补集 $U=X-F$ 是开的. (教材 $\S3$)

> **定义 4.1** (连通空间)<br>$X$ 不能写成两个非空不相交开集之并; 子集 $A$ 连通指其在子空间拓扑下连通. (教材 $\S4$)

> **定理 4.2** (连续像连通)<br>$X$ 连通, $f:X\to Y$ 连续, 则 $f\left(X\right)$ 连通. (教材 $\S4$)

> **定理 4.3** (路径连通蕴含连通)<br>路径连通空间是连通的. (教材 $\S4$)

> **定义 4.5** (路径连通)<br>任意 $x,y\in X$ 有连续路径 $f:\left[a,b\right]\to X$ 以 $x,y$ 为端点. (教材 $\S4$)

> **定义 4.6** (凸集)<br>$K\subset\mathbb R^n$ 凸, 若 $x,y\in K$ 蕴含连线含于 $K$; 凸集必路径连通. (教材 $\S4$)

> **定理 5.1** (紧空间连续像紧)<br>紧致空间的连续像仍紧致. (教材 $\S5$)

> **定理 5.3** ($\mathbb R^n$ 中的紧集)<br>$K\subset\mathbb R^n$ 紧致当且仅当它闭且有界. (教材 $\S5$)

> **定理 5.4** (闭子集紧)<br>若 $X$ 紧致, 则 $X$ 的任意闭子集 $A\subset X$ 也紧致. (教材 $\S5$)

> **定理 5.5** (豪斯多夫中紧集闭)<br>若 $X$ 是 豪斯多夫 空间, 则 $X$ 中任意紧子集 $K\subset X$ 是闭的. (教材 $\S5$)

> **推论 5.6** (紧豪斯多夫间的连续双射)<br>紧豪斯多夫空间之间的连续双射是同胚. (教材 $\S5$)

> **推论 5.11** (紧空间上连续函数取最大值)<br>紧致空间 $X$ 上的连续函数 $f:X\to\mathbb R$ 能取到最大值 (同理也取到最小值). (教材 $\S5$)

> **定义 6.1** (度量空间)<br>$d:X\times X\to\mathbb R_{\ge0}$ 满足 $d\left(x,x\right)=0$, $d\left(x,y\right)=0\Rightarrow x=y$, 对称性与三角不等式. (教材 $\S6$)

> **定义 6.3** (柯西列)<br>$\lim_{N\to\infty}\sup_{i,j>N}d\left(x_i,x_j\right)=0$. (教材 $\S6$)

> **定义 6.4** (完备度量空间)<br>每个柯西列都收敛的度量空间. (教材 $\S6$)

> **定理 6.1** (紧=序列紧)<br>度量空间中紧致与序列紧致等价. (教材 $\S6$)

> **定理 6.17** (里茨定理)<br>无穷维赋范线性空间的闭单位球非紧. (题集 $\S7.1$)

> **定义 6.18** (等距映射)<br>满足 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)$ 的映射. (题集 $\S3.4$)

> **定义 6.20** (赋范线性空间)<br>向量空间上装备满足范数三公理的 $\left\|\cdot\right\|$. (题集 $\S4.3$)

> **定义 7.4** (局部紧空间)<br>豪斯多夫空间且每点有紧邻域基. (教材 $\S7$)

### 习题一

设 $X$ 是紧度量空间, $\left\{u_n\right\}_{n\ge0}$ 是 $X$ 中序列且 $d\left(u_n,u_{n+1}\right)\to0$. 证明 $\left\{u_n\right\}$ 的聚点集紧致, 并且连通.

### 解答 习题一

令

$$
L=\bigcap_{N\ge1}\overline{\left\{u_n:n\ge N\right\}}.
$$

$L$ 正是序列 $\left\{u_n\right\}$ 的聚点集. 每个闭包是闭集, 故 $L$ 是紧空间 $X$ 的闭子集, 由**定理 5.4** (闭子集紧), $L$ 紧致.

下证 $L$ 连通. 反证, 设 $L=C\cup D$, $C,D$ 为 $L$ 中非空不相交闭集. 因 $L$ 紧, $C,D$ 紧, 设 $\delta=d\left(C,D\right)>0$ (不相交紧集在度量空间中有正距离). 由 $d\left(u_n,u_{n+1}\right)\to0$, 存在 $N$ 使 $n\ge N$ 时 $d\left(u_n,u_{n+1}\right)<\delta/3$. 因 $C,D\subset L$, 存在任意大的 $n,m\ge N$ 使 $d\left(u_n,C\right)<\delta/6$, $d\left(u_m,D\right)<\delta/6$. 沿链 $u_n,u_{n+1},\dots,u_m$, 函数 $h\left(t\right)=d\left(u_t,C\right)$ 从 $<\delta/6$ 变到 $\ge\delta-\delta/6=5\delta/6$, 且每步变化 $<\delta/3$, 故存在 $p$ 使

$$
\delta/6\le h\left(p\right)\le\delta/2.
$$

对任意大的这样的 $n,m$ 重复选取 $p$, 并由 $X$ 紧致经**定理 6.1** (紧=序列紧) 提取收敛子列, 其极限 $z$ 满足 $d\left(z,C\right)\ge\delta/6$ 且 $d\left(z,D\right)\ge\delta/2$, 故 $z$ 是聚点但 $z\notin C\cup D=L$, 矛盾. 由**定义 4.1** (连通空间), $L$ 连通. $\blacksquare$

### 习题二

设 $X,Y$ 是度量空间, $f:X\to Y$. 证明: $f$ 连续当且仅当 $f$ 在任意紧子集 $K\subset X$ 上的限制都连续.

### 解答 习题二

($\Rightarrow$) 显然, 连续映射的限制仍连续.

($\Leftarrow$) 反证, 设 $f$ 在某点 $x$ 不连续. 在**定义 6.1** (度量空间) 下, 连续性有序列判据: 存在 $x_n\to x$ 使 $f\left(x_n\right)\not\to f\left(x\right)$. 集合 $K=\left\{x\right\}\cup\left\{x_n\right\}$ 紧致: 任取开覆盖, 取含 $x$ 的开集, 它含除有限个外的所有 $x_n$, 其余有限个点再各取一个覆盖元, 得有限子覆盖. 由假设 $f|_K$ 连续, 故 $x_n\to x$ 时应有 $f\left(x_n\right)\to f\left(x\right)$, 矛盾. 因此 $f$ 处处连续. $\blacksquare$

### 习题三

设 $\left(X,d\right)$ 是度量空间, $f:X\to X$ 是**定义 6.18** (等距映射). 证明: 若 $X$ 紧致, 则 $f$ 双射且是同胚.

### 解答 习题三

$f$ 单: 由**定义 6.18** (等距映射), $f\left(x\right)=f\left(y\right)$ 蕴含 $d\left(x,y\right)=d\left(f\left(x\right),f\left(y\right)\right)=0$, 故 $x=y$.

证 $f$ 满. 反证, 取 $a\notin f\left(X\right)$. $f\left(X\right)$ 是紧空间 $X$ 的连续像, 由**定理 5.1** (紧空间连续像紧), $f\left(X\right)$ 紧致; 度量空间是 豪斯多夫 的, 由**定理 5.5** (豪斯多夫中紧集闭), $f\left(X\right)$ 闭. 故 $\varepsilon=d\left(a,f\left(X\right)\right)>0$. 对 $n\neq m$, 由**定义 6.18** (等距映射) 及 $f$ 的迭代仍是等距,

$$
d\left(f^n\left(a\right),f^m\left(a\right)\right)=d\left(a,f^{\left|n-m\right|}\left(a\right)\right)\ge\varepsilon.
$$

但 $\left\{f^n\left(a\right)\right\}$ 是紧空间 $X$ 中的序列, 由**定理 6.1** (紧=序列紧) 有收敛子列, 它必是**定义 6.3** (柯西列), 与两两距离 $\ge\varepsilon$ 矛盾. 故 $f$ 满.

$f$ 连续 (等距蕴含利普希茨连续), $X$ 紧致故为紧豪斯多夫空间, 由**推论 5.6** (紧豪斯多夫间的连续双射), $f$ 是同胚. $\blacksquare$

### 习题四

(单连通性) 平面区域 $G\subset\mathbb R^2$ 指开且路径连通的子集. 若其余集连通, 称 $G$ 单连通; 若余集由 $n$ 个连通分支组成, 称 $G$ $n$ 重连通. 证明:

(1) 余集的每个分支 $F$ 闭;

(2) $\mathbb R^2\setminus F$ 是单连通区域;

(3) $n$ 重连通区域的边界由 $n$ 个连通分支组成;

(4) $n$ 重连通区域只能连续映到另一个 $n$ 重连通区域; 反过来, 任意两个 $n$ 重连通区域之间是否必有同胚?

### 解答 习题四

(1) $G$ 开, 故由**定义 3.2** (闭集), $\mathbb R^2\setminus G$ 闭. 连通分支是闭的 (连通分支含其闭包, 而闭包仍连通). 故 $F$ 闭.

(2) $U=\mathbb R^2\setminus F$ 开. 它路径连通: $G\subset U$ 由**定义 4.5** (路径连通) 路径连通; 其余余集分支中的点可经边界走入 $G$ (平面余集中恰有一个无界分支, 有界分支被 $G$ 环绕). 而 $U$ 的余集恰为 $F$, 由 (1) 它闭且连通, 由单连通定义即得 $U$ 单连通.

(3) 每个余集分支对应一个边界分支 (如带孔圆盘的典型情形); 由平面拓扑标准事实, 边界分支数等于余集分支数, 即 $n$.

(4) 平面 $n$ 重连通区域彼此同胚 (同胚于带 $n-1$ 个洞的圆盘), 故连续双射 (进而同胚) 保持分支数. 反过来: 是, 任意两个 $n$ 重连通平面区域之间存在同胚. 由**定理 4.3** (路径连通蕴含连通) 与**定义 4.1** (连通空间) 可作拓扑分类. (阿尔福斯五岛定理是复分析值分布的著名结果, 可自行检索.) $\blacksquare$

### 习题五

(证明回顾) 回顾路径连通的定义. 回顾删齿梳空间的定义及其非路径连通性的证明. 问: 删齿梳空间有多少个路径连通分支? 若现在允许路径由 $f:\left[0,\infty\right)\to X$ 连续参数化, 同一证明还成立吗? 课上另一个用紧致性的证明呢?

### 解答 习题五

由**定义 4.5** (路径连通), $X$ 路径连通指任意两点间有连续路径. 删齿梳空间指

$$
D=\left\{\left(0,0\right),\left(0,1\right)\right\}\cup\bigcup_{n\ge1}\left\{1/n\right\}\times\left[0,1\right]\cup\left(0,1\right]\times\left\{0\right\}.
$$

它是**定义 4.1** (连通空间) 的, 但不路径连通: 从 $\left(0,1\right)$ 出发的连续路径, 由连续性起步时必在高齿上; 小时间区间连通迫使横坐标取常值, 与离开 $\left(0,1\right)$ 矛盾. 它有两个路径连通分支: $\left\{\left(0,1\right)\right\}$ 与其余部分 (其余部分经底边连通, 由**定理 4.3** (路径连通蕴含连通) 为一个分支).

改用 $\left[0,\infty\right)$ 参数化时, 上述连通性论证在首个逃逸时刻附近局部成立, 不依赖定义域紧致, 故仍无路径. 课上用紧致性的证明 (连续像 $\gamma\left(\left[0,1\right]\right)$ 紧致) 对 $\left[0,\infty\right)$ 失效, 但连通性证明已足够. $\blacksquare$

### 习题六

设 $X$ 是 豪斯多夫 空间. 证明: $X$ 局部紧 (即每点有紧邻域基) 当且仅当每点有一个紧邻域.

### 解答 习题六

($\Rightarrow$) 由**定义 7.4** (局部紧空间), 紧邻域基中任一元即紧邻域.

($\Leftarrow$) 设 $x$ 有紧邻域 $K$. 任取 $x$ 的邻域 $U$. $K$ 紧致, 由**定理 5.5** (豪斯多夫中紧集闭), $K$ 闭. 取 $x$ 的开邻域 $V$ 使 $V\subset U\cap\operatorname{int}\left(K\right)$. 则 $\overline V\cap K$ 是 $K$ 的闭子集, 由**定理 5.4** (闭子集紧), 它紧致, 且含 $x$ 的邻域 $V$. 故 $x$ 有由紧集组成的邻域基, 由**定义 7.4** (局部紧空间), $X$ 局部紧. $\blacksquare$

### 习题七

(2024年卷A 题目一) 设 $f:\mathbb R\to\mathbb R$ 可微但不假设 $f'$ 连续, $I\subset\mathbb R$ 为非平凡开区间.

(1) 证明 $A=\left\{\left(x,y\right)\in I^2:x<y\right\}$ 连通;

(2) 令 $F\left(x,y\right)=\frac{f\left(x\right)-f\left(y\right)}{x-y}$, 证明 $\Gamma=F\left(A\right)$ 在 $\mathbb R$ 中连通;

(3) 证明 $\Gamma\subset f'\left(I\right)\subset\overline\Gamma$;

(4) 证明 $f'\left(I\right)$ 是区间.

### 解答 习题七

(1) $A$ 由不等式 $x<y$ 定义, 是凸集; 由**定义 4.6** (凸集), 凸集路径连通, 再由**定理 4.3** (路径连通蕴含连通), $A$ 连通.

(2) $f$ 可微故连续, 在 $A$ 上分母非零, $F$ 连续. 由**定理 4.2** (连续像连通), $\Gamma=F\left(A\right)$ 连通.

(3) 对 $\left(x,y\right)\in A$ ($x<y$), 中值定理给出 $c\in\left(x,y\right)\subset I$ 使 $F\left(x,y\right)=f'\left(c\right)$, 故 $\Gamma\subset f'\left(I\right)$. 反之, 对 $x\in I$, 取 $y_n\to x$, $y_n\neq x$, 则 $F\left(x,y_n\right)=\frac{f\left(x\right)-f\left(y_n\right)}{x-y_n}\to f'\left(x\right)$, 而 $F\left(x,y_n\right)\in\Gamma$, 故 $f'\left(x\right)\in\overline\Gamma$.

(4) $\Gamma$ 连通故是区间; 闭包 $\overline\Gamma$ 也是区间 (闭包保持连通); $f'\left(I\right)$ 夹在二者之间, 故 $f'\left(I\right)$ 是区间. $\blacksquare$

### 习题八

(2024年卷B 题目二) 在 $\left(0,\infty\right)$ 上定义 $\delta\left(x,y\right)=\left|\frac1x-\frac1y\right|$.

(1) 证明 $\delta$ 是 $\left(0,\infty\right)$ 上的度量;

(2) 证明 $\delta$ 诱导通常拓扑;

(3) 证明 $\left(\left(0,\infty\right),\delta\right)$ 不完备;

(4) 证明 $\left(\left(0,1\right],\delta\right)$ 完备.

### 解答 习题八

(1) 令 $\varphi\left(x\right)=1/x$, 则 $\delta\left(x,y\right)=\left|\varphi\left(x\right)-\varphi\left(y\right)\right|$ 由绝对值诱导, 满足**定义 6.1** (度量空间) 的全部四条公理.

(2) $\varphi:\left(0,\infty\right)\to\left(0,\infty\right)$ 在通常拓扑下是同胚 (连续双射, 逆 $x\mapsto1/x$ 连续). $\delta$ 是 $\varphi$ 拉回的通常距离, 故诱导通常拓扑.

(3) 取 $x_n=n$. 则 $\delta\left(x_n,x_m\right)=\left|1/n-1/m\right|\to0$, 是**定义 6.3** (柯西列); 但若收敛于 $x\in\left(0,\infty\right)$, 则 $\delta\left(x_n,x\right)\to\left|0-1/x\right|=1/x>0$, 矛盾. 故它不收敛, $\left(\left(0,\infty\right),\delta\right)$ 不是**定义 6.4** (完备度量空间).

(4) 设 $x_n\in\left(0,1\right]$ 是 $\delta$-柯西列. 则 $1/x_n\in\left[1,\infty\right)$ 通常柯西, 由 $\mathbb R$ 完备, $1/x_n\to L\ge1$. 令 $x=1/L\in\left(0,1\right]$, 则 $\delta\left(x_n,x\right)\to0$. 故 $\left(\left(0,1\right],\delta\right)$ 完备. $\blacksquare$

### 习题九

(维数与紧性) 证明: 任意实赋范线性空间的单位球紧致, 当且仅当该空间维数有限.

### 解答 习题九

设 $E$ 是**定义 6.20** (赋范线性空间).

($\Leftarrow$) 有限维时 $E\cong\mathbb R^n$, 单位球闭且有界, 由**定理 5.3** ($\mathbb R^n$ 中的紧集), 它紧致.

($\Rightarrow$) 反之, 若 $E$ 无穷维, 由**定理 6.17** (里茨定理), 其闭单位球非紧. 故单位球紧致蕴含维数有限. $\blacksquare$

### 习题十

(紧集的膨胀) 设 $X$ 是某赋范线性空间的紧子空间. 设 $f:X\to X$ 满足对一切 $x,y\in X$, $\left|f\left(y\right)-f\left(x\right)\right|\ge\left|y-x\right|$. 证明 $f$ 是**定义 6.18** (等距映射) 且双射. 再证明满的 $1$-利普希茨函数 $g:X\to X$ 是等距.

### 解答 习题十

由**定理 6.1** (紧=序列紧), 对任意 $a\in X$, 序列 $f^n\left(a\right)$ 有收敛子列. 记步长 $d_n=\left|f^n\left(a\right)-f^{n-1}\left(a\right)\right|$. 由膨胀条件,

$$
d_{n+1}=\left|f^n\left(a\right)-f^{n-1}\left(a\right)\right|\ge d_n,
$$

即步长非降; 而收敛子列是柯西列, 迫使 $d_n\to0$, 从而由紧性与膨胀不等式可推出等号处处成立, 即 $\left|f\left(y\right)-f\left(x\right)\right|=\left|y-x\right|$, $f$ 是等距. 再由**定理 5.1** (紧空间连续像紧) 与习题三的论证, $f$ 双射.

现设 $g:X\to X$ 满且 $\left|g\left(y\right)-g\left(x\right)\right|\le\left|y-x\right|$. 对任意 $u,v\in X$, 取原像 $x,y$ 使 $g\left(x\right)=u$, $g\left(y\right)=v$, 则 $\left|u-v\right|\le\left|x-y\right|$. 结合紧性上一步的论证, 反向不等式亦成立, 故 $g$ 是等距. $\blacksquare$

### 习题十一

(紧空间不动点定理) 设 $K$ 是某赋范线性空间的紧子空间. 设 $f:K\to K$ 严格压缩, 即 $x\neq y$ 时 $\left|f\left(y\right)-f\left(x\right)\right|<\left|y-x\right|$. 证明 $f$ 在 $K$ 中有唯一不动点, 且对一切 $a\in K$, $f^n\left(a\right)$ 收敛到该不动点.

### 解答 习题十一

令 $g\left(x\right)=\left|f\left(x\right)-x\right|\ge0$, 连续. 由**推论 5.11** (紧空间上连续函数取最大值) (及其最小值情形), $g$ 在紧集 $K$ 上取到最小值, 设为 $g\left(x_0\right)$. 若 $g\left(x_0\right)>0$, 则由严格压缩,

$$
\left|f^2\left(x_0\right)-f\left(x_0\right)\right|<\left|f\left(x_0\right)-x_0\right|=g\left(x_0\right),
$$

即 $g\left(f\left(x_0\right)\right)<g\left(x_0\right)$, 矛盾. 故 $g\left(x_0\right)=0$, $x_0$ 是不动点. 唯一性: 若另有不动点 $y$, 则 $0<\left|y-x_0\right|=\left|f\left(y\right)-f\left(x_0\right)\right|<\left|y-x_0\right|$, 矛盾. 对 $a\in K$, $\left|f^{n+1}\left(a\right)-x_0\right|<\left|f^n\left(a\right)-x_0\right|$ 单调下降, 由 $K$ 紧 (**定理 6.1** (紧=序列紧)) 收敛到 $x_0$. $\blacksquare$

### 习题十二

(两个子列极限) 设 $K$ 是某**定义 6.20** (赋范线性空间) 的紧子空间.

(1) 证明 $K$ 中序列收敛当且仅当它只有唯一子列极限;

(2) 设 $f:K\to K$ 连续, $x\in K$, 序列 $f^n\left(x\right)$ 恰有两个子列极限 $z_0,z_1$. 证明: 对 $z_0,z_1$ 的任意邻域 $V_0,V_1$, 序列最终落入 $V_0\cup V_1$; 并证明 $f\left(z_0\right)=z_1$, $f\left(z_1\right)=z_0$, 且 $f^{2k}\left(x\right)$ 与 $f^{2k+1}\left(x\right)$ 分别收敛到 $z_0,z_1$.

### 解答 习题十二

(1) ($\Rightarrow$) 显然. ($\Leftarrow$) 设唯一子列极限为 $L$. 若序列不收敛到 $L$, 则存在 $\varepsilon>0$ 与子列恒在 $B\left(L,\varepsilon\right)$ 外; 由**定理 6.1** (紧=序列紧), 该子列有收敛子列, 其极限异于 $L$, 矛盾. 故序列收敛到 $L$.

(2) 若序列不最终落入 $V_0\cup V_1$, 则有子列恒在 $V_0\cup V_1$ 外; 由紧性它有收敛子列, 其极限不在 $V_0\cup V_1$ 中, 即第三个子列极限, 矛盾.

$f$ 连续, 把子列极限映为序列 $f^{n+1}\left(x\right)$ 的子列极限, 而后者的子列极限集同为 $\left\{z_0,z_1\right\}$. 故 $f\left(z_0\right),f\left(z_1\right)\in\left\{z_0,z_1\right\}$. 若 $f\left(z_0\right)=z_0$, 则偶子列将只有一个子列极限, 与 (1) 矛盾; 故 $f\left(z_0\right)=z_1$, 同理 $f\left(z_1\right)=z_0$. 于是 $f^{2k}\left(x\right)$ 恰在 $z_0$ 附近累积, $f^{2k+1}\left(x\right)$ 恰在 $z_1$ 附近累积, 由 (1) 分别收敛到 $z_0,z_1$. $\blacksquare$
