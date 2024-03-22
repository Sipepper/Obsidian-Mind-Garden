---
Last time checked: 2024-02-28
Complete: true
aliases:
---
# Ring of p-adic integers
***
###### tags: #p-adic 
***
>[!dsn]+ Definition
>By the *ring of $p$-adic integers* $\mathbb{Z}_{p}$ we mean either the number $\alpha$ for which his $p$-adic norm $\|\alpha\|\le1$ in $\mathbb{Q}$, or the set of all possible formal sequences $\sum\limits_{i\ge0}$ in which all integral coefficients are such that 
>$$0\le a_{i}\le p-1$$
>thus every such number can be associated with sequence $\set{a_{i}}_{i\ge0}$. Also the set $\mathbb{Z}_{p}$ can be associated with product set
>$$\mathbb{Z}_{p}=\prod_{i\ge0}\set{0,1,\dots,p-1}=\set{0,1,\dots,p-1}^{\mathbb{N}}$$ this set allows to  introduce the multiplication and addition therefore it has *commutative ring structure*.^[[[Alain M. Robert - A course in p-adic analysis.pdf#page=19|Alain M. Robert - "A course in p-adic analysis" p.3]]]

>Utilizing the analog of [[Cantor's diagonal argument]] we can see that $\mathbb{Z}_{p}$ is not countable.

#### Ring operations
##### Addition
>[!dsn]+ Definition
>We can define addition on $\mathbb{Z}_{p}$ componentwise with a *law of carries*, i.e. similarly to addition of decimal integers, when we perform addition in "column" every time we must add $a_{i}+b_{i}-kp$ to the next component in formal series.

>[!example]+
>Let $a=1=1+0p+0p^{2}+\dots$ and $b=(p-1)+(p-1)p+(p-1)p^{2}$
>Then the sum $a+b$ will have $0$ as the first component, because $1+(p-1)=p$. But we must not forget the law of carries, therefore we should add one to the next component, repeating that we will also get zero and so on. In the end we get that $1+b=0$, i.e. $b$ is a *negative*(*additive inverse*) to an element $a=1$, and thus can be denoted as $b=-1$. 

##### Multiplication
>[!dsn]+ Definition
>We can define multiplication in similar manner, i.e. we perform multiplication componentwise but preserve the law of carries.

>[!example]+
>Let's represent $-1$ as a $p$-adic integer, we have that $-1=\sum(p-1)p^{i}$. After some algebra we obtain
>$$\sum_{i\ge0}p^{i}=\frac{1}{1-p}$$ 
>Therefore $1-p$ be invertible in $\mathbb{Z}_{p}$ with inverse element defined as following formal geometric series.

>Because
>$$p\cdot\sum_{i\ge0}a_{i}p^{i}=a_{0}p+a_{1}p^{2}+\dots\ne1+0p+0p^{2}+\dots$$
>i.e. prime $p$ has no multiplicative inverse in $\mathbb{Z}_{p}$

>We can define an additive inverses for all possible elements, by multiplying by $-1$
>$$-m=(-1)\cdot m-\sum(p-1)p^{i}\cdot\sum_{i\ge0}m_{i}p^{i}$$
>but it's not that easy.

>When $p\ne 2$ every ring $\mathbb{Z}_{p}$ will have a fixed point with respect to involution $\sigma$ which can be computed in the following way
>$$a=\sum_{i\ge0}\frac{p-1}{2}\cdot p^{i}=\frac{p-1}{2}\cdot\sum_{i\ge0}p^{i}=\frac{p-1}{2}\cdot\frac{1}{1-p}=-\frac{1}{2}$$
>for $p=2$ involution has no fixed point because $2$ is not invertible in $\mathbb{Z}_{2}$.
***
#### Keywords
- [[p-adic norm]],
- [[Set]],
- [[Sequence]],
- [[Cartesian product of sets]],
- [[Ring]],
- [[Cardinality of a set]],
- [[Prime number]],
- [[Unit in a ring]],
- [[Involution]],
- [[Fixed point]]
#### Possibly related
- 
***
#### Sources: