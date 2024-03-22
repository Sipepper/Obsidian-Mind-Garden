---
Last time checked: 2024-02-11
Complete: true
aliases:
---
# Box counting dimension
***
###### tags: #Geometry/Fractal 
***
>[!dsn]+ Definition
>Let $F$ be a bounded non-empty subset of $\mathbb{R}^{n}$ and let $N_{\delta}(F)$ be the smallest number of sets which covers $F$ with diameter at most $\delta$. By *lower* and *upper box-counting dimension*(*Minkowski-Bouligand dimension*) of a set $F$ we mean the following expressions:
>$$\underline\dim_{B}F=\underline\lim\limits_{\delta\to0}\frac{\log N_{\delta}(F)}{\log(1/\delta)}\quad (1)$$
>$$\overline\dim_{B}F=\overline\lim\limits_{\delta\to0}\frac{\log N_{\delta}(F)}{\log(1/\delta)}\quad (2)$$
>If those dimensions are equal then we saying that *box-counting dimension* of $F$ is
>$$\dim_{B}F=\lim_{\delta\to0}\frac{\log N_{\delta}}{\log(1/\delta)}\quad(3)$$.^[Kenneth Falconner - "Fractal geometry 2e." p.41-45]

>Often as $N_{\delta}(F)$ we can take the following families of sets:
>- smallest number of closed balls of radius $\delta$ which covers $F$
>- smallest number of cubes with side $\delta$ which covers $F$
>- number of cubes in $\delta$-net of cubes which intersect $F$
>- biggest number of non-intersecting balls with radius $\delta$ and centers in $F$
>  
>![[Pasted image 20220901130638.png]]


***
#### Keywords
- [[Bounded set]],
- [[Set]],
- [[Euclidean space]],
- [[Set diameter]],
- [[Covering of a set]],
- [[Open ball in metric space]],
- [[Open and closed subsets]],
- [[Convergence]],
- [[Limit]],
- [[Logarithm]],
- [[Delta covering]],
- [[Epsilon-net]]
#### Possibly related
- [[Hausdorff dimension]]
***
#### Sources:

# Minkowski-Bouligand dimension calculation example
***
###### tags: #Geometry/Fractal 
***
>[!example]
>Let $F=\set{0,1,\frac{1}{2},\frac{1}{3},\dots}$ be a compact subset of the $[0,1]$ interval, then $\dim_{B}=\frac{1}{2}$.^[Kenneth Falconner - "Fractal geometry 2e" p. 49]

>[!proof]
>Let $0<\delta<\frac{1}{2}$ and let $k$ be some integer such that
>$$\frac{1}{(k-1)k}>\delta\ge\frac{1}{k(k+1)}$$
>Let $|U|\le\delta$, then $U$ can cover at most one of the points $\set{1,\frac{1}{2},\dots,1/k}$ because $\frac{1}{(k-1)}-\frac{1}{k}=\frac{1}{(k-1)k}>\delta$. Therefore, we need at least $k$ sets of diameter $\delta$ to cover $F$, and thus $N_{\delta}(F)\ge k$ and we obtain
>$$\frac{\log N_{\delta}(F)}{-\log\delta}\ge\frac{\log k}{\log k(k+1)}$$
>Letting $\delta\to0$ and accordingly $k\to\infty$ we obtain that $\underline{\dim}_{B}F\ge\frac{1}{2}$. On the other hand, if $\frac{1}{2}>\delta>0$, if we take $k$ such that $\frac{1}{(k-1)k}>\delta\ge\frac{1}{k(k+1)}$, then $k+1$ intervals of length $\delta$ will cover interval $[0,1/k]$, leaving $k-1$ points from $F$ which can be covered with $k-1$ intervals. Therefore $N_{\delta}(F)\le2k$, then
>$$\frac{\log N_{\delta}(F)}{-\log\delta}\le\frac{\log(2k)}{\log k(k-1)}$$
>thus we have that
>$$\overline{\dim}_{B}F\le\frac{1}{2}$$
***
#### Keywords
- [[Compact set]],
- [[Interval]],
- [[Box counting dimension]],
- [[Set diameter]],
- [[Delta covering]],
- [[Covering of a set]],
#### Possibly related
- 
***
#### Sources: