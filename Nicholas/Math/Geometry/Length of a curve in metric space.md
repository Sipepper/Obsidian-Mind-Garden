---
Last time checked: 2024-02-16
Complete: true
aliases:
---
# Length of a curve in metric space
***
###### tags: #Geometry 
***
>[!dsn]+ Definition
>Let $X$ be a metric space. The *length* $l(c)$ of a curve $c:[a,b]\to X$ is 
>$$l(c)=\sup_{a=t_{0}\le t_{1}\le\dots\le t_{n}}\sum\limits_{i=0}^{n-1}d(c(t_{i}),c(t_{i+1}))$$
>where the supremum is taken over all possible partitions(no bound on $n$) with $a=t_{0}\le t_{1}\le\dots\le t_{n}=b$.^[[[Martin R. Bridson, Andrea Haefliger - Metric spaces of non-positive curvature.pdf#page=31|Martin R. Bridson, Andrea Haefliger - "Metric spaces of non-positive curvature" p.12]]]

>The length of $c$ is either a non-negative number or it is infinite.

>The curve $c$ is said to be *rectifiable* if its length is finite.

>[!example]+ 
>Let $X=[0,1]$ with euclidean metric. Let $0=t_{0}<t_{1}<\dots<t_{n}<\dots$ be an infinite sequence of real numbers in $[0,1]$ such that $\lim\limits_{n\to\infty}t_{n}=1$. Let $c:[0,1]\to X$ be any path such that $c(0)=0$ and $c(t_{n})=\sum\limits_{k=1}^{n}(-1)^{k+1}/k$. This is not a rectifiable path, because its length is bounde below by the sum of the harmonic series
>$$\begin{align}d(c(t_{n}),c(t_{n+1}))&=\left|\sum\limits_{k=1}^{n+1}(-1)^{k+1}/k-\sum\limits_{k=1}^{n}(-1)^{k+1}/k\right|\\ &=\left|\frac{(-1)^{n+2}}{n+1}\right|=\frac{1}{n+1}\end{align}$$
#### Properties 
>[!dsn]+ Proposition
>Let $(X,d)$ be a metric space and let $c:[a,b]\to X$ be a path.
>1. $l(c)\ge d(c(a),c(b))$
>   $l(c)=0$ if and only if $c$ is a constant map.
>
>2. If $\phi$ is a weakly monotonic map from an interval $[a',b']$ onto $[a,b]$, then $l(c)=l(c\circ\phi)$
>3. *Additivity*: if $c$ is the concatenation of two paths $c_{1}$ and $c_{2}$, then $l(c)=l(c_{1})+l(c_{2})$.
>4. The *reverse path* $\overline{c}:[a,b]\to X$ defined by $\overline{c}(t)=c(b+a-t)$ satisfies $l(\overline{c})=l(c)$.
>5. If $c$ is rectifiable of length $l$, then the function $\lambda:[a,b]\to[0,l]$ defined by $\lambda(t)=l(c|_{[a,t]})$ is a continuous weakly monotonic function.
>6. *Reparametrization by arc length*: If $c$ and $\lambda$ are as in (4.), then there is a unique path $\tilde{c}:[0,l]\to X$ such that 
>   $$\tilde{c}\circ\lambda=c\;\;\text{and}\;\;l(\tilde{c}|_{[0,t]})=t$$
>7. *Lower semicontinuity*: Let $(c_{n})$ be a sequence of paths $[a,b]\to X$ converging uniformly to a path $c$. If $c$ is rectifiable, then for every $\varepsilon>0$ there exists an integer $N(\varepsilon)$ such that
>   $$l(c)\le l(c_{n})+\varepsilon$$
>   whenever $n>N(\varepsilon)$.^[[[Martin R. Bridson, Andrea Haefliger - Metric spaces of non-positive curvature.pdf#page=31|Martin R. Bridson, Andrea Haefliger - "Metric spaces of non-positive curvature" p.12-13]]]

>[!proof]+
>Properties $(1)-(4)$ are immediate. Property $(3)$ reduces the proof of $(5)$ to showing that, given $\varepsilon>0$, one can partition $[a,b]$ into finitely many subintervals so that the length of $c$ restricted to each of these subintervals is at most $\varepsilon$. To see that this can be done, we first use the uniform continuity of the map $c:[a,b]\to X$ to choose $\delta>0$ such that $d(c(t),c(t'))<\varepsilon/2$, $\forall t,t'\in[a,b]$ with $|t-t'|<\delta$. Since $l(c)$ is finite, we can find a partition $a=t_{0}<t_{1}<\dots<t_{k}=b$ such that
>$$\sum\limits_{i=0}^{k-1}d(c(t_{i}),c(t_{i+1}))>l(c)-\varepsilon/2$$
>Taking a refinement of this partition if necessary, we may assume that $|t_{i}-t_{i+1}|<\delta$ for $i=0,\dots,k-1$, and hence $d(c(t_{i}),c(t_{i+1}))<\varepsilon/2$. But $l(c|_{[t_{i},t_{i+1}]})\ge d(c(t_{i}),c(t_{i+1}))$, and $l(c)=\sum l(c|_{[t_{i},t_{i+1}]})$ by $(3)$. Hence
>$$l(c)=\sum\limits_{i=0}^{k-1}l(c|_{[t_{i},t_{i+1}]})\ge\sum\limits_{i=0}^{k-1}d(c(t_{i}),c(t_{i+1}))>l(c)-\varepsilon/2$$
>with each summand in the first sum no less than the corresponding summand in the second sum. Hence, for all $i$ we have $l(c|_{[t_{i},t_{i+1}]})-d(c(t_{i}),c(t_{i+1}))\le\varepsilon/2$, and in particular $l(c|_{[t_{i},t_{i+1}]})<\varepsilon$.
>
>$(6)$ follows from $(5)$ and $(2)$. To check $(7)$, we again choose $a=t_{0}<t_{1}<\dots<t_{k}=b$ such that
>$$l(c)\le\sum\limits_{i=0}^{k-1}d(c(t_{i}),c(t_{i+1}))+\varepsilon/2$$
>Then we choose $N(\varepsilon)$ big enough to ensure that $d(c(t),c_{n}(t))<\varepsilon/4k$ for all $n>N(\varepsilon)$ and all $t\in[a,b]$. By the triangle inequality, $d(c(t_{i}),c(t_{i+1}))\le2\varepsilon/4k+d(c_{n}(t_{i}),c_{n}(t_{i+1}))$. Hence
>$$l(c)\le k\frac{\varepsilon}{2k}+\sum\limits_{i=0}^{k-1}d(c_{n}(t_{i}),c_{n}(t_{i+1}))+\frac{\varepsilon}{2}\le\varepsilon+l(c_{n})$$
***
#### Keywords
- [[Metric space]],
- [[Curve in metric space]],
- [[Interval]],
- [[Supremum and infinum]],
- [[Euclidean space]],
- [[Cardinality of a set]],
- [[Sequence]],
- [[Convergence]],
- [[Bounded set]],
- [[Absolute value]],
- [[Harmonic series]],
- [[Uniform convergence]],
- [[Monotonic function]],
- [[Function(mapping)]],
- [[Continuous mapping]],
- [[Restriction and extension of a mapping]],
#### Possibly related
- [[Regular curves, arc length and natural parametrization]]
***
#### Sources:

***
#### Keywords
#### Possibly related
***
#### Sources: