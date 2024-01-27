---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Subring criterion
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>Let $(R,+,\cdot)$ be a ring, $S\subset R$ such that $0_{R}\in S$ and $1_{R}\in S$. $S$ is a subring of $R$ if and only if the following conditions hold
>1. $S$ is closed under $+$ and $\cdot$ ,
>2. $\forall a\in S$ the additive inverse $-a$ is in $S$.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>$\Rightarrow$
>Let $S$ be a subring of $R$. Then by definition of a [[ring]] and subring the properties $(1)-(2)$ follows.
>
>$\Leftarrow$
>Suppose that $S$ has the properties $(1)-(2)$, we only need to prove the
>- existence of neutral element
>- existence of additive inverse
>- existence of multiplicative identity
>
>It is true as $R$ is closed under addition and multiplication, and as $0_{R}\in S$ and $1_{R}\in S$.

>We can swap condition $(2)$ by
>$$-a=a\cdot(-1)\qquad -1\in S$$

>[!example]+ 
>Let $R=\mathbb{C}$ and $S=\mathbb{Z}[i]$, then $\mathbb{Z}[i]$ is closed under addition and multiplication.
>Let $a+bi\in\mathbb{Z}[i]$, then $-(a+bi)=-a-bi\in\mathbb{Z}[i]$, thus $\mathbb{Z}[i]$ is a subring of $\mathbb{C}$.
***
#### Keywords
- [[Ring]],
- [[Complex plane]],
- [[Gaussian integers]]
#### Possibly related
- 
***
#### Sources: