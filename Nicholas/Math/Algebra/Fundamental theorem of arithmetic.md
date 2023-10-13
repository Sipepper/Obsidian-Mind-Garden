---
Last time checked: 2023-10-11
Complete: true
aliases: 
- Фундаментальная теорема арифметики
- Фундаментальна теорема арифметики
---
# Fundamental theorem of arithmetic
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>For all $n\in\mathbb{Z}\setminus\{0,\pm1\}$, there exists irreducible integers $q_{1},\dots,q_{r}$, such that
>$$n=q_{1}\cdot q_{2}\cdot\ldots\cdot q_{r}$$
>If there exist another list of numbers $p_{1},\dots,p_{s}$, such that
>$$n=q_{1}\cdot\ldots\cdot q_{r}=p_{1}\cdot\ldots\cdot p_{s}$$
>then $r=s$ and after permutation, we obtain that
>$$p_{i}=\pm q_{i},\quad i=\overline{1,r}$$

>If $r=1$, then $n=q_{1}$. If $n=1$, by *convention*, we say that there is an empty product on a right side, i.e. $r=0$.

>In another words, we can restate the theorem as follows: Every $c\in\mathbb{Z}\setminus\{0\}$ can be uniquely expressed as
>$$c=\pm2^{\nu_{2}}\cdot 3^{\nu_{3}}\cdot 5^{\nu_{4}}\cdot 7^{\nu_{5}}\cdot 11^{\nu_{6}}\cdot \ldots$$ 
>where $\nu_{p}\ge0$ for all prime numbers $p$ and $\nu_{p}\ne0$ for only finite number of indices.

>[!proof]+
>*Existence*
>Consider a set
>$$S=\{n\in\mathbb{Z},n>1: \text{there is no such decomposition}\}$$
>Suppose that $S\ne\emptyset$, as $S\subset\mathbb{N}$ and $\mathbb{N}$ is totally ordered set, there exist a minimal element $m\in S$.
>So we cannot decompose $m$ into product of irreducible elements, thus, $m$ is not irreducible, so $m=a\cdot b$, $1<a,b<m$ from which $a,b\notin S$, so they can be decomposed into product of irreducible elements
>$$a=q'_{1}\cdot\ldots\cdot q'_{n}\qquad b=q''_{1}\cdot\ldots\cdot q''_{v}$$
>thus
>$$m=q'_{1}\cdot\ldots\cdot q'_{n}\cdot q''_{1}\cdot\ldots\cdot q''_{v}$$
>which contradicts the fact that $m\in S$.
>
>*Uniqueness*
>Without loss of generality we can assume that $n$ and all elements in decomposition are positive.
>Consider a set
>$$T=\{n\in\mathbb{Z},n\ge 2:\text{have non-unique decomposition}\}$$
>Suppose that $T$ is not empty. The as $\mathbb{N}\subset T$ has linear order, there exist $m=\min\{n:n\in T\}$ and $m\in T$. Let
>$$m=q_{1}\cdot\ldots\cdot q_{r}=p_{1}\cdot\ldots\cdot p_{s}$$
>as $m>1$, then $r,s\ge1$. A number $q_{1}\ne0$ is irreducible so $q_{1}$ is prime by [[equivalence of irreducibility and being prime in set of integers]].
>As $q_{1}|p_{1}\cdot\dots p_{s}$, then there exist $i\in\overline{1,s}$, such that $q_{1}|p_{i}$.
>But $p_{i}\ne 0$ is irreducible, so $q_{1}\in\{\pm1,\pm p_{i}\}$, as $q_{1}$ is irreducible and positive, $p_{i}=q_{1}$.
>Now we can change numeration of $p_{i}$, such that 
>$$m=q_{1}\cdot(q_{2}\cdot\ldots\cdot q_{r})=q_{1}\cdot(p_{2}\cdot\ldots\cdot p_{s})$$
>So exist some positive $l<m$, such that $l\notin T$, and after permutation of $p_{2},\dots,p_{r}$ we have that $p_{i}=q_{i}$, $i=\overline{2,r}$, and so on.
>Therefore $m\notin T$, and $T=\emptyset$.

>[!example]+ 
>$$1153425=3\cdot 5^{2}\cdot 7\cdot13^{3}$$
***
#### Keywords
- [[Set of integers]],
- [[Irreducible element]],
- [[Permutation]],
- [[Prime number]],
- [[Cardinality of a set]],
- [[Set]],
- [[Linearly ordered set]],
- [[Set of integers has linear order]],
- [[Divisibility]]
#### Possibly related
- 
***
#### Sources: