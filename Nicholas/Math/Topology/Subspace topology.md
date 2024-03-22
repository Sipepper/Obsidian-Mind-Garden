---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Subspace topology
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $Y$ be a non-empty subset of topological space $(X,\tau)$. Then family $\tau_{Y}=\{O\cap Y:O\in\tau\}$ of subsets of $Y$ is a topology on $Y$ which is called *subspace topology*( or *induced topology* or *topology induced by $\tau$ on $Y$*).
>
>Topological space $(Y,\tau_{Y})$ is said to be a *subspace* of $(X,\tau)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=91|Sidney A. Morris - "Topology without tears" p.91]]]

>[!proof]+
>

>[!example]+ 
>Let $X=\{a,b,c,d,e,f\}$,
>$$\tau=\{X,\emptyset,\{a\},\{c,d\},\{a,c,d\},\{b,c,d,e,f\} \}$$
>and $Y=\{b,c,e\}$. Then subspace topology $Y$ will have the following form
>$$\tau_{Y}=\{Y,\emptyset,\{c\}\}$$

>[!example]+
>Let $\mathbb{Z}\subset\mathbb{R}$. Then subspace topology on $\mathbb{Z}$ is a *discrete topology* from euclidean topology $\tau_{st}$.
>>[!proof]+
>>Let $n\in\mathbb{Z}$. Then $\{n\}=(n-1,n+1)\cap\mathbb{Z}$. But $(n-1,n+1)$ is open in $\mathbb{R}$ and therefore $\{n\}$ is open in the subspace topology on $\mathbb{Z}$. Thus every singleton set in $\mathbb{Z}$ is open in the subspace topology on $\mathbb{Z}$. So the subspace topology is discrete.

>[!example]+
>Consider the subset $[1,2]$ of $\mathbb{R}$. A basis for the subspace topology $\tau$ on $[1,2]$ is
>$$\{(a,b)\cap[1,2]:a,b\in\mathbb{R},a<b\}$$
>that is,
>$$\{(a,b):1\le a<b\le2\}\cup\{[1,b):1<b\le2\}\cup\{(a,2]:1\le a<2\}\cup\{[1,2]\}$$
>is a basis for $\tau$.
>But $\left[1,\frac{3}{2}\right)$ is certainly *not* an open set in $\mathbb{R}$, but $\left[1,\frac{3}{2}\right)=\left[1,\frac{3}{2}\right)\cap[1,2]$, is an open set in the subspace $[1,2]$.
>Also $(1,2]$ is not open in $\mathbb{R}$ but is open in $[1,2]$. Even $[1,2]$ is not open in $\mathbb{R}$, but is an open set in $[1,2]$.

>So whenever we speak of a set being open we must make perfectly clear in what space or what topology it is an open set.

#### Basis of subspace topology
>[!dsn]+ Direct strict note
>Let $\mathcal{B}$ be a basis for the topology $\tau$ on $X$ and let $Y$ be non-empty subset of $X$. Then it is not hard to show that the collection $\mathcal{B}_{Y}=\{B\cap Y:B\in\mathcal{B}\}$ is a basis for the subspace topology $\tau_{Y}$ on $Y$.^[Sidney A. Morris - "Topology without tears" p.91]

>[!proof]+
>

>[!example]+
>Consider the subset $(1,2)$ of $\mathbb{R}$. A basis for the induced topology on $(1,2)$ is the collection $\{(a,b)\cap(1,2):a,b\in\mathbb{R},a<b\}$; that is, $\{(a,b):a,b\in\mathbb{R},1\le a<b\le2\}$ is a basis for the induced topology on $(1,2)$.
***
#### Keywords
- [[Set]],
- [[Topological space]],
- [[Set of integers]],
- [[Real line]],
- [[Discrete topology]],
- [[Euclidean topology]],
- [[Interval]],
- [[Open and closed subsets]],
- [[Topology basis]],
#### Possibly related
- 
***
#### Sources: