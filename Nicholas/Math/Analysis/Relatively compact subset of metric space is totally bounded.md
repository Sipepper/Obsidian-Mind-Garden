# Relatively compact subset of metric space is totally bounded
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $(U,d)$ be a metric space, then
>1. If $A\subset U$ is relatively compact, then $A$ is totally bounded.
>2. If $(U,d)$ is complete metric space and $A\subset U$ is totally bounded, then $A$ is relatively compact.^[Botelho - Functional analysis and Applied Optimization in Banach Spaces p.18-19]

>[!proof]+
>1. Suppose that $A\subset U$ is relatively compact. By [[Relative compactness by subsequences]] we know that from any sequence in $A$ we can extract a converging subsequence. And by [[Total-boundedness by subsequences]] $A$ is totally bounded.
>2. Let $(U,d)$ be a metric space, and let $A$ be a totally bounded subset of $U$. Let $\{u_{n}\}$ be a sequence in $A$. As $A$ is totally bounded then for every $k\in\mathbb{N}$ we can choose an $\varepsilon_{k}$-net with $\varepsilon_{k}=1/k$, denoted as
>   $$N_{k}=\left\{v_{1}^{(k)},v_{2}^{(k)},\dots,v_{n_{k}}^{(k)}\right\}$$
>   In particular for $k=1$, $\{u_{n}\}$ is lie in $1$-net $N_{1}$. Therefore at least one ball of radius $1$ from $N_{1}$ contains infinitely many elements from $\{u_{n}\}$. Choose subsequence $\left\{u_{n_{k}}^{(1)}\right\}_{k\in\mathbb{N}}$ which contained in ball of radius $1$. Similarly we can choose subsequence with renamed elements $\left\{u_{n_{l}}^{(2)} \right\}_{l\in\mathbb{N}}$ from sequence $\left\{u_{n_{k}}^{(1)} \right\}$ which contained in one of balls from $\frac{1}{2}$-net. Repeating such operation for every $k\in\mathbb{N}$ we obtain a subsequence $\left\{u_{n_{m}}^{(k)}\right\}_{m\in\mathbb{N}}$ of a initial sequence which contained in a ball of radius $1/k$.
>   Now consider a diagonal sequence $\left\{u_{n_{k}}^{(k)}\right\}_{k\in\mathbb{N}}=\{z_{k}\}$. Then $d(z_{n},z_{m})<\frac{2}{k}$ if $m,n>k$, i.e. $\{z_{k}\}$ is a Cauchy sequence, and because $(U,d)$ is a complete metric space, then there exists an element $u\in U$ such that 
>   $$z_{k}\to u\quad k\to\infty$$
>   And by [[Relative compactness by subsequences]] $A$ is relatively compact. 

>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Relatively compact set]],
- [[Totally bounded subset of a metric space]],
- [[Complete metric space]],
- [[Sequence]],
- [[Convergence in metric spaces]],
- [[Epsilon-net]],
- [[Open ball in metric space]],
- [[Cauchy sequence]]
#### Possibly related
- 
***
#### Sources: