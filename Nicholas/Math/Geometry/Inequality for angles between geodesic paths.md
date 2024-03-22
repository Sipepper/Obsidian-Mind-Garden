---
Last time checked: 2024-02-15
Complete: false
aliases:
---
# Inequality for angles between geodesic paths
***
###### tags: #Geometry 
***
>[!dsn]+ Proposition
>Let $X$ be a metric space and let $c$,$c'$ and $c''$ be three geodesic paths in $X$ issuing from the same point $p$. Then,
>$$\angle(c',c'')\le\angle(c,c')+\angle(c,c'')$$
>.^[[[Martin R. Bridson, Andrea Haefliger - Metric spaces of non-positive curvature.pdf#page=29|Martin R. Bridson, Andrea Haefliger - "Metric spaces of non-positive curvature" p.10]]]

>[!proof]+
>We argue by contradiction. If this inequality were not true, then there would exist $\delta>0$ such that $\angle(c',c'')>\angle(c,c')+\angle(c,c'')+3\delta$. Using the definition of the $\limsup$, we could then find an $\varepsilon>0$ such that:
>1. $$\angle_{p}(c(t),c'(t'))<\angle(c,c')+\delta\quad\forall t,t'<\varepsilon$$
>2. $$\angle_{p}(c(t),c''(t''))<\angle(c,c'')+\delta\quad\forall t,t''<\varepsilon$$
>3. $$\angle_{p}(c'(t),c''(t''))>\angle(c',c'')-\delta\quad\text{for some}\;t',t''<\varepsilon$$
>
>Let $t'$ and $t''$ be as in $(3)$. Consider a triangle in $\mathbb{E}^{2}$ with vertices $0,x',x''$ such that $d(0,x')=t'$, $d(0,x'')=t''$, and such that the angle $\alpha$ at the vertex $0$ satisfies:
>$$\overline{\angle}_{p}(c'(t'),c''(t''))>\alpha>\angle(c',c'')-\delta$$
>In particular $\alpha<\pi$, so the triangle is non-degenerate. The left-most inequality implies that $d(x',x'')<d(c'(t'),c''(t''))$. The right-most inequality implies that $\alpha>\angle(c,c')+\angle(c,c'')+2\delta$, and hence enables us to choose a point $x\in[x',x'']$ such that the angle $\alpha'$($\alpha''$ respectively) between the Euclidean segments $[0,x']$ and $[0,x]$($[0,x'']$ and $[0,x]$) is bigger than $\angle(c,c')+\delta$(respectively $\angle(c,c'')+\delta$).
>Let $t=d(0,x)$. Because $t\le\max\{t',t''\}<\varepsilon$, condition $(1)$ implies that
>$$\overline{\angle}_{p}(c(t),c'(t'))<\angle(c,c')+\delta<\alpha' $$
>and hence $d(c(t),c'(t'))<d(x,x')$. Similarly, $d(c(t),c''(t''))<d(x,x'')$. Thus 
>$$d(c'(t'),c''(t''))>d(x',x'')=d(x,x')+d(x,x'')>d(c(t),c'(t'))+d(c(t),c''(t''))$$
>which contradicts the triangle inequality in $X$.

>[!example]+
>
***
#### Keywords
- [[Metric space]],
- [[Geodesic path in metric space]],
- [[Angle between the geodesic paths]],
- [[Supremum and infinum]],
- [[Upper and lower limit]],
- [[Euclidean space]],
#### Possibly related
- 
***
#### Sources: