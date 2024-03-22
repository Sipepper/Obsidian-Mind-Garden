---
Last time checked: 2024-02-27
Complete: true
aliases:
---
# Closed subgroup of real line
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>Let $G$ be a closed subgroup of $\mathbb{R}$. Then $G=\{0\}$, $G=\mathbb{R}$ or $G$ is a discrete group of the form 
>$$a\mathbb{Z}=\{0,\pm a,\pm2a,\dots\}$$
>for some $a>0$.^[[[Sidney A. Morris - Topology without tears.pdf#page=538|Sidney A. Morris - "Topology without tears" p.538]]]

>[!proof]+
>Assume $G\ne\mathbb{R}$. As $G$ is closed, and hence not dense in $\mathbb{R}$, thus by [[every non-discrete subgroup of real line is dense]] $G$ must be discrete. If $G\ne\{0\}$, then $G$ contains some positive real number $b$ So $[0,b]\cap G$ is a closed non-empty subset of the compact set $[0,b]$. Thus by [[closed subset of compact space is compact]] $[0,b]\cap G$ is compact and discrete. Hence $[0,b]\cap G$ is finite, and so there exists a least element $a>0$ in $G$.
>
>For each $x\in G$, let $\left[\frac{x}{a}\right]$ denote the integer part of $\frac{x}{a}$. Then $x-\left[\frac{x}{a}\right]a\in G$ and
>$$0\le x-\left[\frac{x}{a}\right]a=x-\left(\frac{x}{a}-\left\{\frac{x}{a} \right\}\right)a=a\left\{\frac{x}{a} \right\} <a$$
>as $\left\{\frac{x}{a} \right\}$ be a fractional part of a number is greater than $0$ and less than $1$.
>So $x-\left[\frac{x}{a}\right]a=0$(as $a$ is minimal); that is, $x=na$, for some $n\in\mathbb{Z}$, as required.

***
#### Keywords
- [[Open and closed subsets]],
- [[Real line]],
- [[Discrete group]],
- [[Dense subset]],
- [[Interval]],
- [[Compact set]],
- [[Cardinality of a set]],
- [[Set of integers]]
#### Possibly related
- [[Greatest element, upper bound and maximal element of a partially ordered set]]
***
#### Sources: