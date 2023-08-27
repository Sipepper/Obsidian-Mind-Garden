# Continuous maps between metric space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,d)$ and $(Y,d_{1})$ be metric spaces and $f$ is a mapping from $X$ to $Y$. Let $\tau$ and $\tau_{1}$ be topologies induced by metrics respectively. Then $f:(X,\tau)\to(Y,\tau_{1})$ is continuous if and only if $x_{n}\to x\Rightarrow f(x_{n})\to f(x)$; i.e. if $\set{x_{n}}$ is convergent in $(X,d)$ then $\set{f(x_{n})}$ is also convergent sequence in $(Y,d_{1})$.^[Sidney A. Morris - "Topology without tears" p.143]

>[!proof]
>Assume that $x_{n}\to x\Rightarrow f(x_{n})\to f(x)$. To verify that $f$ is continuous it suffices to show that the inverse image of every closed set in $(Y,\tau_{1})$ is closed in $(X,\tau)$. So let $A$ be closed in $(Y,\tau_{1})$. Let $\set{x_{n}}$ be a sequence of points in $f^{-1}(A)$ convergent to a point $x\in X$. As $x_{n}\to x$, $f(x_{n})\to f(x)$. But since each $f(x_{n})\in A$ and $A$ is closed, [[Open and closed subsets#6.2.3. Замкнутость через последовательности]] then implies that $f(x)\in A$. Thus $x\in f^{-1}(A)$. So we have shown that every convergent sequence of points from $f^{-1}(A)$ converges to a point of $f^{-1}(A)$. Thus $f^{-1}(A)$ is closed, and hence $f$ is continuous.
>Conversely, let $f$ be continuous and $x_{n}\to x$. Let $\varepsilon>0$. Then the open ball $B_{\varepsilon}(f(x))$ is an open set in $(Y,\tau_{1})$. As $f$ is continuous, $f^{-1}(B_{\varepsilon}(f(x)))$ is an open set in $(X,\tau)$ and it contains $x$. Therefore there exists a $\delta>0$ such that
>$$x\in B_{\delta}(x)\subseteq f^{-1}(B_{\varepsilon}(f(x)))$$
>As $x_{n}\to x$, there exists a positive integer $n_{0}$ such that $\forall n\ge n_{0}$, $x\in B_{\delta}(x)$. Therefore
>$$f(x_{n})\in f(B_{\delta}(x))\subseteq B_\varepsilon (f(x)),\quad\forall n\ge n_{0}$$
>Thus $f(x_{n})\to f(x)$.

>[!example] 
>

#### Continuity using distance between limit points
>[!dsn] Direct strict note
>Let $(X,d)$ and $(Y,d_{1})$ be metric spaces, $f$ a mapping of $X$ into $Y$, and $\tau$ and $\tau_{1}$ the topologies induced by metric $d$ and $d_{1}$ respectively. Then $f:(X,\tau)\to(Y,\tau_{1})$ is continuous if and only if $\forall x_{0}\in X$ and $\forall\varepsilon>0$, there exists a $\delta>0$ such that $x\in X$ and $d(x,x_{0})<\delta\Rightarrow d_{1}(f(x),f(x_{0}))<\varepsilon$.^[Sidney A. Morris - "Topology without tears" p.144]

>[!proof]
>It's a corollary from proposition above, [[Continuous maps between metric spaces]]
***
#### Keywords
- [[Metric space]],
- [[Function(mapping)]],
- [[Topology induced by a metric]],
- [[Continuous mapping]],
- [[Convergence]],
- [[Open and closed mappings]],
- [[Preimage]],
- [[Sequence]],
- [[Open ball in metric space]],
- [[Limit point in topological space]]
#### Possibly related
- 
***
#### Sources: