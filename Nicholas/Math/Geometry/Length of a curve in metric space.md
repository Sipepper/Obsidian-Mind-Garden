# Length of a curve in metric space
***
###### tags: #Geometry 
***
>[!dsn] Direct strict note
>Let $X$ be a metric space. The *length* $l(c)$ of a curve $c:[a,b]\to X$ is 
>$$l(c)=\sup_{a=t_{0}\le t_{1}\le\dots\le t_{n}}\sum\limits_{i=0}^{n-1}d(c(t_{i}),c(t_{i+1}))$$
>where the supremum is taken over all possible partitions(no bound on $n$) with $a=t_{0}\le t_{1}\le\dots\le t_{n}=b$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.12]

>The length of $c$ is either a non-negative number or it is infinite.

>The curve $c$ is said to be *rectifiable* if its length is finite.

>[!example] 
>Let $X=[0,1]$ with euclidean metric. Let $0=t_{0}<t_{1}<\dots<t_{n}<\dots$ be an infinite sequence of real numbers in $[0,1]$ such that $\lim\limits_{n\to\infty}t_{n}=1$. Let $c:[0,1]\to X$ be any path such that $c(0)=0$ and $c(t_{n})=\sum\limits_{k=1}^{n}(-1)^{k+1}/k$. This is not a rectifiable path, because its length is bounde below by the sum of the harmonic series
>$$\begin{align}d(c(t_{n}),c(t_{n+1}))&=\left|\sum\limits_{k=1}^{n+1}(-1)^{k+1}/k-\sum\limits_{k=1}^{n}(-1)^{k+1}/k\right|\\ &=\left|\frac{(-1)^{n+2}}{n+1}\right|=\frac{1}{n+1}\end{align}$$
***
#### Keywords
- [[Metric space]],
- [[Curve in metric space]],
- [[Supremum and infinum]],
- [[Euclidean space]],
- [[Sequence]],
- [[Bounded set]],
#### Possibly related
- 
***
#### Sources: