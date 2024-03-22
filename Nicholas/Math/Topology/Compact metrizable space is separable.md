---
Last time checked: 2024-03-03
Complete: false
aliases:
---
# Compact metrizable space is separable
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(X,\tau)$ be a compact metrizable space. Then $(X,\tau)$ is also a separable space.^[[[Sidney A. Morris - Topology without tears.pdf#page=236|Sidney A. Morris - "Topology without tears" p.236]]]

>[!proof]
>Let $d$ be a metric on $X$ which induces the topology $\tau$. For every positive integer $n$ we define $\mathcal{S}_{n}$ as family of open balls with centers in $X$ with radius $\frac{1}{n}$. Then $\mathcal{S}_{n}$ be an open cover($\frac{1}{n}$-cover) of $X$ and there exist a finite subcovering $\mathcal{U}_{n}=\set{U_{n_{1}},U_{n_{2}},\dots,U_{n_{k}}}$, for some $n\in\mathbb{N}$. Let $y_{n_{j}}$ be the center of $U_{n_{j}}$, $j=1,\dots,k$, and $Y_{n}=\set{y_{n_{1}},y_{n_{2}},\dots,y_{n_{k}}}$. Put $Y=\bigcup_{n=1}^{\infty}Y_{n}$. Then $Y$ will be a countable subset of $X$. We now show that $Y$ will be dense in $(X,\tau)$.
>
>Let $V$ be some non-empty subset of $(X,\tau)$, then for any $v\in V$, $V$ contains an open ball $B$ with radius $\frac{1}{n}$ at $v$ for some $n\in\mathbb{N}$. Because $\mathcal{U}_{n}$ is an open covering of $X$, then $v\in U_{n_{j}}$, for some $j$. Therefore $d(v,y_{n_{j}})<\frac{1}{n}$ and thus $y_{n_{j}}\in B\subseteq V$. From which be get that $V\cap Y\ne\emptyset$, therefore $Y$ is dense in $X$.

>[!example]+
>

***
#### Keywords
- [[Compact set]],
- [[Metrizable space]],
- [[Separable space]],
- [[Metric space]],
- [[Topology induced by a metric]],
- [[Set of integers]],
- [[Open ball in metric space]],
- [[Covering of a set]],
- [[Open and closed subsets]],
- [[Dense subset]]
- [[Delta covering]],
- [[Cardinality of a set]],
#### Possibly related
- 
***
#### Sources: