---
Last time checked: 2024-01-27
Complete: false
aliases:
---
# Dual topological space
***
###### tags: #Topology #Analysis/Functional 
***
>[!dsn]+ Definition
>Let $U$ be a Banach space, then topological space $U^{*}$ is said to be a *dual topological space* to $U$, if it's consists of all continuous functionals defined on $U$. In another words, let $f:U\to\mathbb{R}$ be a linear continuous functional, then exists an element $u^{*}\in U^{*}$ such that
>$$f(u)=\langle u,u^{*}\rangle_{U},\quad\forall u\in U$$
>where $\langle\cdot,\cdot\rangle_{U}:U\times U^{*}\to\mathbb{R}$ is a bilinear form on $U\times U^{*}\to\mathbb{R}$ called *dual pairing*.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 60|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.42-43]]]

>We can define the norm $\|f\|_{U^{*}}$ on $U^{*}$  in the following way
>$$\|f\|_{U^{*}}=\sup_{u\in U}\left\{|\langle u,u^{*}\rangle_{U}|:\|u\|_{U}\le1\right\}$$
>>[!proof]+
>>

>[!example]+ 
>Consider the $l^{p}$ space, then $(l^{p})^{*}$ can be identified with the space $l^{q}$, where $q$ and $p$ such that $\frac{1}{p}+\frac{1}{q}=1$.
***
#### Keywords
- [[Banach space]],
- [[Topological space]],
- [[Continuous mapping]],
- [[Functional]],
- [[Linear map]],
- [[Real line]],
- [[Bilinear form]],
- [[Cartesian product of sets]],
- [[Normed space]],
- [[Absolute value]],
- [[Supremum and infinum]],
- [[Sequence spaces]]
#### Possibly related
- [[Product topology]]
***
#### Sources: