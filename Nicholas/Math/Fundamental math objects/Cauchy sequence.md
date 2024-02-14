---
Last time checked: 2024-02-03
Complete: true
aliases:
---
# Cauchy sequence
***
###### tags: #Fundamental_math_objects #Topology 
***
>[!dsn]+ Definition
>A sequence $x_{1},x_{2},\dots,x_{n},\dots$ of points in a metric space $(X,d)$ is said to be a *Cauchy sequence* if given any real number $\varepsilon>0$, there exists a positive integer $n_{0}$, such that for all integers $m\ge n_{0}$ and $n\ge n_{0}$, $d(x_{m},x_{n})<\varepsilon$.^[[[Sidney A. Morris - Topology without tears.pdf#page=148|Sidney A. Morris - "Topology without tears" p.148]]]

>Convergent sequence is a Cauchy sequence.
>>[!proof]+
>>Let $\varepsilon$ be any positive real number. Put $\delta=\varepsilon/2$. As $x_{n}\to a$, there exists a positive integer $n_{0}$, such that for all $n>n_{0}$, $d(x_{n},a)<\delta$.
>>So let $m>n_{0}$ and $n>n_{0}$. Then $d(x_{n},a)<\delta$ and $d(x_{m},a)<\delta$. By the triangle inequality we have that
>>$$\begin{align}d(x_{m},x_{n})&\le d(x_{m},a)+d(x_{n},a)\\ &<\delta+\delta\\ &=\varepsilon \end{align}$$
>>and so the sequence is indeed a Cauchy sequence.

>[!example]+
>Consider the open interval $(0,1)$ with the euclidean metric $d$. It is clear that the sequence $0.1,0.01,0.001,\dots$ is a Cauchy sequence but it does not converge to any point in $(0,1)$.
>
>i.e. *not* every Cauchy sequence is convergent sequence.

#### Equivalent Cauchy sequences
>[!dsn]+ Definition
>Let $\{y_{n}\}$ and $\{z_{n}\}$ be a Cauchy sequences in metric space $(X,d)$. Then $\{y_{n}\}$ and $\{z_{n}\}$ is said to be *equivalent* if $d(y_{n},z_{n})\to0$.
>It's an equivalence relation.^[[[Sidney A. Morris - Topology without tears.pdf#page=157|Sidney A. Morris - "Topology without tears" p.157]]]

>Equivalence of Cauchy sequences is an equivalence relation.
>>[!proof]+
>>Reflexivity and symmetry follows from definition of [[metric space]]. Thus we should only proof the transitive property. 
>>Suppose that $\{x_{n}\}\sim\{y_{n}\}$ and $\{y_{n}\}\sim\{z_{n}\}$, then $d(x_{n},y_{n})\to0$ and $d(y_{n},z_{n})\to 0$. By triangle inequality
>>$$0\le d(x_{n},z_{n})\le d(x_{n},y_{n})+d(y_{n},z_{n})\to0$$
>>therefore by [[properties of convergent sequences of real numbers]] and [[sandwich theorem]] $d(x_{n},z_{n})\to 0$, i.e. $\{x_{n}\}\sim\{z_{n}\}$.

***
#### Keywords
- [[Sequence]],
- [[Metric space]],
- [[Real line]],
- [[Set of integers]],
- [[Convergence]],
- [[Open and closed subsets]],
- [[Interval]],
- [[Euclidean space]],
- [[Equivalence relation]]
#### Possibly related
- 
***
#### Sources: