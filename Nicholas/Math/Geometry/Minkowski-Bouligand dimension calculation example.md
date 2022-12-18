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
- [[Компактное множество]],
- [[Интервал]],
- [[Размерность Минковского-Булигана]],
- [[Диаметр множества]],
- [[Дельта покрытие]],
- [[Покрытие множества]],
#### Possibly related
- 
***
#### Sources: