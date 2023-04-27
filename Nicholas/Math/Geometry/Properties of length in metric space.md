# Properties of length in metric space
***
###### tags: #Geometry 
***
>[!dsn] Direct strict note
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
>   whenever $n>N(\varepsilon)$.^[Martin R. Bridson - "Metric spaces of non-positive curvature" p.12-13]

>[!proof]
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
- [[Uniform convergence]],
- [[Curve in metric space]],
- [[Metric space]],
- [[Monotonic function]],
- [[Function(mapping)]],
- [[Interval]],
- [[Continuous mapping]],
- [[Restriction and extension of a mapping]],
#### Possibly related
- [[Regular curves, arc length and natural parametrization]]
***
#### Sources: