---
Last time checked: 2024-03-10
Complete: true
aliases:
---
# Neighborhood in topological space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(X,\tau)$ be a topological space, $N\subset X$ and $p$ a point from $N$. Then the subset $N$ is said to be a *neighborhood* of the point $p$ if there exists an open set $U$ such that $p\in U\subseteq N$.^[[[Sidney A. Morris - Topology without tears.pdf#page=81|Sidney A. Morris - "Topology without tears" p.81]]]

>[!example]+ 
>The closed interval $[0,1]$ in $\mathbb{R}$ is a neighborhood of the point $\frac{1}{2}$, since $\frac{1}{2}\in\left(\frac{1}{4},\frac{3}{4}\right)\subseteq[0,1]$.

>Let $(X,\tau)$ be a topological space, and $N$ a neighborhood of a point $p$. If $S$ is any subset of $X$ such that $N\subseteq S$, then $S$ is a neigborhood of $p$.

>[!example]+ Nonexample
>The interval $(0,1]$ in $\mathbb{R}$ is a neighborhood of the point $\frac{1}{4}$, as $\frac{1}{4}\in\left(0,\frac{1}{2}\right)\subseteq(0,1]$. But $(0,1]$ is *not* a neighborhood of the point $1$.
>>[!proof]+
>>Because there is no such open interval $(a,b)$ that 
>>$$(a,b)\subseteq(0,1]\;\text{and}\;1\in(a,b)$$

>[!example]+
>If $(X,\tau)$ is any topological space and $U\in\tau$, then by definition it follows that $U$ is a neighborhood of every point $p\in U$. 

***
#### Keywords
- [[Topological space]],
- [[Set]],
- [[Open and closed subsets]],
- [[Interval]],
- [[Real line]],
#### Possibly related
- 
***
#### Sources: