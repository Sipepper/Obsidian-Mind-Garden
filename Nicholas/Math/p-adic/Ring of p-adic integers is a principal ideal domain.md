---
Last time checked: 2024-02-29
Complete: false
aliases:
---
# Ring of p-adic integers is a principal ideal domain
***
###### tags: #p-adic 
***
#### Principal ideals
>[!dsn]+ Theorem
>Principal ideals of $\mathbb{Z}_{p}$ are
>$$\langle p^{k}\rangle=p^{k}\mathbb{Z}_{p}=\{x\in\mathbb{Z}_{p}:\text{ord}_{p}(x)\ge k\}$$
>and 
>$$\mathbb{Z}_{p}\supset p\mathbb{Z}_{p}\supset\dots\supset p^{k}\mathbb{Z}_{p}\supset\dots\supset\bigcap\limits_{k\ge0}p^{k}\mathbb{Z}_{p}=\{0\}$$

>[!proof]+
>Every element $a\ne0$ with order $v(a)=k$ is such that $a\notin\langle p^{k+1}\rangle$. 

#### $p$-adic integers is a PID
>[!dsn]+ Proposition
>A ring $\mathbb{Z}_{p}$ is a *PID*(*principial ideal domain*). Furthermore, only ideals $\{0\}$ and $p^{k}\mathbb{Z}_{p}$ are principal.^[[[Alain M. Robert - A course in p-adic analysis.pdf#page=22 |Alain M. Robert - "A course in p-adic analysis" p.6]]]

>[!proof]+
>Let $I\ne\{0\}$ be an ideal of $\mathbb{Z}_{p}$ and $0\ne a\in I$ be element of minimal order, say $k=v(a)<\infty$. Express $a$ in the canonical form, that is $a=p^{k}u$, where $u$ is invertible in $\mathbb{Z}_{p}$. Then $p^{k}=u^{-1}a\in I$ and $\langle p^{k}\rangle=p^{k}\mathbb{Z}_{p}\subset I$.
>Conversely, for every $b\in I$ define $w=v(b)\ge k$ and write
>$$b=p^{w}u'=p^{k}\cdot p^{w-k}u'\in p^{k}\mathbb{Z}_{p}$$
>this proves the $I\subset p^{k}\mathbb{Z}_{p}$ inclusion.

***
#### Keywords
- [[Ideal]],
- [[Principal ideal]]
- [[Ring of p-adic integers]],
- [[p-adic order]],
- [[Canonical representation of a p-adic integer]]
#### Possibly related
- 
***
#### Sources: