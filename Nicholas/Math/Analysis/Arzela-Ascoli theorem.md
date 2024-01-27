---
Last time checked: 2024-01-27
Complete: false
aliases:
---
# Arzela-Ascoli theorem
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Theorem
>Let $\mathcal{F}$ be a family of point-wise bounded equicontinuous complex functions defined on metric space $(U,d)$ and $U$ is separable. Then every sequence $\{f_{n}\}\subset\mathcal{F}$ has a subsequence which converges uniformly on every compact subset of $U$.^[Fabio Silva Botelho - "Functional analysis and Applied Optimization in Banach Spaces" p.19-21]

>[!proof]+
>Let $\{u_{n}\}$ be a countable dense subset of $(U,d)$. By assumption $\{f_{n}(u_{1})\}$ is a bounded sequence; and thus it has converging subsequence which we denote as $\{f_{n_{k}}(u_{1})\}$. Introduce new notation 
>$$f_{n_{k}}(u_{1})=\tilde{f}_{1,k}(u_{1})\quad\forall k\in\mathbb{N}$$
>Thereore exist $g_{1}\in\mathbb{C}$ such that $\tilde{f}_{1,k}(u_{1})\to g_{1}$ as $k\to\infty$. Note that $\{f_{n_{k}}(u_{2})\}$ is also a bounded sequence and thus also has a converging subsequence, which we denote as $\{\tilde{f}_{2,k}(u_{2})\}$. Again exist $g_{2}\in\mathbb{C}$ such that $\tilde{f}_{2,k}(u_{1})\to g_{1}$ and $\tilde{f}_{2,k}(u_{2})\to g_{2}$ as $k\to\infty$. Continuing in a similar manner we obtain a sequence $\left\{\tilde{f}_{m,k}\right\}$, $\forall m\in\mathbb{N}$, such that
>$$\tilde{f}_{m,k}(u_{j})\to g_{j}\quad k\to\infty\quad\forall j\in\{1,\dots,m\}$$
>Consider the diagonal sequence $\left\{\tilde{f}_{k,k}\right\}$ and note that for a sequence $\left\{\tilde{f}_{k,k}(u_{m}) \right\}_{k>m}$ the following is true
>$$\tilde{f}_{k,k}(u_{m})\to g_{m}\in\mathbb{C}\quad k\to\infty\quad\forall m\in\mathbb{N}$$
>Therefore we can assume that from $\{f_{n}\}$ we can extract converging subsequence which we can denote as $\{f_{n_{k}}\}=\{\tilde{f}_{k,k}\}$ which is converging on $E=\{u_{n}\}_{n\in\mathbb{N}}$.
>Suppose that $K$ is a compact subset of $U$. Let $\varepsilon>0$ is a given real number.By equicontinuity there exist $\delta>0$ such that if $u,v\in U$ and $d(u,v)<\delta$ we have that
>$$|f_{n_{k}}(u)-f_{n_{k}}(u)|<\frac{\varepsilon}{3}\quad\forall k\in\mathbb{N}$$
>Note that $K\subset\bigcup\limits_{u\in K}B_{\delta/2}(u)$. By compactness of $K$ it follows that we can choose $\{\tilde{u}_{1},\dots,\tilde{u}_{M}\}$ such that $K\subset\bigcup\limits_{j=1}^{M}B_{\delta/2}(\tilde{u}_{j})$. 
>As $E$ is dense in $U$, there exists elements $v_{j}\in B_{\delta/2}(\tilde{u}_{j})\cap E$, $\forall j\in\{1,\dots,M\}$. By fixing $j\in\{1,\dots,M\}$, $v_{j}\in E$ we get that $\lim\limits_{k\to\infty}f_{n_{k}}(v_{j})$ exists as $k\to\infty$. Therefore exists some number $K_{0_{j}}\in\mathbb{N}$ such that if $k,l>K_{0_{j}}$ then
>$$|f_{n_{k}}(v_{j})-f_{n_{l}}(v_{j})|<\frac{\varepsilon}{3}$$
>Choose arbitrary $u\in K$, then $u\in B_{\delta/2}(\tilde{u}_{\hat{j}})$ for some $\hat{j}\in\{1,\dots,M\}$, such that $d(u,v_{\hat{j}})<\delta$. Thus if $k,l>\max\left\{K_{0_{1}},\dots,K_{0_{M}} \right\}$ then
>$$\begin{align}|f_{n_{k}}(u)-f_{n_{l}}(u)|&\le|f_{n_{k}}(u)-f_{n_{k}}(v_{\hat{j}})|+\\ &\quad\;|f_{n_{k}}(v_{\hat{j}})-f_{n_{l}}(v_{\hat{j}})|+\\ &\quad\;|f_{n_{l}}(v_{\hat{j}})-f_{n_{l}}(v_{\hat{j}})|\\ &\le\frac{\varepsilon}{3}+\frac{\varepsilon}{3}+\frac{\varepsilon}{3}=\varepsilon \end{align}$$
>As $u\in K$ was chosen arbitrarily, then we can assume that $\{f_{n_{k}}\}$ is uniformly convergent Cauchy sequence on $K$.

***
#### Keywords
- [[Pointwise bounded function]],
- [[Equicontinuity]],
- [[Complex function]],
- [[Metric space]],
- [[Separable space]],
- [[Sequence]],
- [[Uniform convergence]],
- [[Compact set]],
- [[Set]],
- [[Cardinality of a set]],
- [[Dense subset]],
- [[Complex plane]],
- [[Convergence]],
- [[Bounded set]],
- [[Cauchy sequence]],
- [[Set of natural numbers]],
- [[Limit]],
- [[Absolute value]],
- [[Open ball in metric space]]
#### Possibly related
- 
***
#### Sources: