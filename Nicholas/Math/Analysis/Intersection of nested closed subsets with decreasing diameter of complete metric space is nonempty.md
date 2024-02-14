---
Last time checked: 2024-01-31
Complete: false
aliases:
---
# Intersection of nested subsets with decreasing diameter of complete metric space is nonempty
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(U,d)$ be a metric space. We say that a sequence $\{F_{k}\}\subset U$ is *nested sequence of sets* if 
>$$F_{1}\supset F_{2}\supset F_{3}\supset\dots$$
>Let $(U,d)$ be a complete metric space, then every nested sequence of non-empty closed subsets $\{F_{k}\}$ such that
>$$\lim\limits_{k\to\infty}|F_{k}|=0$$
>has a non-empty intersection, i.e.
>$$\bigcap\limits_{k=1}^{\infty}F_{k}\ne\emptyset$$
>.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page=31|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.13-14]]]

>[!proof]+
>Let $\{F_{k}\}$ be a nested sequence of sets and $\lim\limits_{k\to\infty}|F_{k}|=0$. For every $n\in\mathbb{N}$ choose $u_{n}\in F_{n}$. Suppose that $\varepsilon>0$ is chosen. As $\lim\limits_{k\to\infty}|F_{n}|=0$ there exists a number $N\in\mathbb{N}$ such that when $n\ge N$ we have $|F_{n}|<\varepsilon$. 
>Then if $m,n>N$ we have that $u_{m},u_{n}\in F_{N}$ are such that
>$$d(u_{n},u_{m})<\varepsilon$$
>Which means that $\{u_{n}\}$ is a Cauchy sequence. By completeness of $U$ there exists an element $u\in U$ such that $u_{n}\to n$, as $n\to\infty$.
>Now choose some $m\in\mathbb{N}$. We have that $u_{n}\in F_{m}$, $\forall n>m$, and thus
>$$u\in\overline{F_{m}}=F_{m}$$. And as $m\in\mathbb{N}$ was chosed arbitrarily 
>$$u\in\bigcap\limits_{m=1}^{\infty}F_{m}$$

>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Sequence]],
- [[Set]],
- [[Complete metric space]]
- [[Open and closed subsets]],
- [[Set diameter]],
- [[Cauchy sequence]],
- [[Set of natural numbers]],
- [[Closure of a set]]
#### Possibly related
- 
***
#### Sources: