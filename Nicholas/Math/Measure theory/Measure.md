---
Last time checked: 2024-02-27
Complete: false
aliases:
---
# Measure
***
###### tags: #Fundamental_math_objects #Measure_theory 
***
>[!dsn]+ Definition
>Let $X$ be a set and $\Sigma$ a $\sigma$-algebra over $X$. A function $\mu$ from $\Sigma$ to $\mathbb{R}\cup\{+\infty\}$ is called *measure* if it satisfies the following properties:
>- *Non-negativity*: $\forall E\in\Sigma$, we have $\mu(E)\ge0$.
>- *Null empty set*: $\mu(\emptyset)=0$.
>- *Countable additivity*: For all countable collections $\{E_{k}\}_{k=1}^{\infty}$ of pairwise disjoint sets in $\Sigma$
>  $$\mu\left(\bigcup_{k=1}^{\infty}E_{k}\right)=\sum\limits_{k=1}^{\infty}\mu(E_{k})$$
>
>The pair $(X,\Sigma)$ is called a *measurable space*, and the members of $\Sigma$ are called *measurable sets*. A *triple* $(X,\Sigma,\mu)$ is called a *measure space*.^[https://en.wikipedia.org/wiki/Measure_(mathematics)]

>[!example]+
> 
###### Basic properties
1. *Monotonicity*
   If $E_{1}$ and $E_{2}$ are measurable sets with $E_{1}\subseteq E_{2}$ then
   $$\mu(E_{1})\le\mu(E_{2})$$
2. *Subadditivity*
   For any countable sequence $E_{1},E_{2},E_{3},\dots$ of (not necessarily disjoint) measurable sets $E_{n}$ in $\Sigma$:
   $$\mu\left(\bigcup_{i=1}^{\infty}E_{i}\right)\le\sum\limits_{i=1}^{\infty}\mu(E_{i})$$
3. *Continuity from below*
   If $E_{1},E_{2},E_{3},\dots$ are measurable sets that are increasing ($E_{i}\subseteq E_{i+1}$) then the union of the sets $E_{n}$ is measurable and
   $$\mu\left(\bigcup_{i=1}^{\infty}E_{i}\right)=\lim_{i\to\infty}\mu(E_{i})=\sup_{i\ge1}\mu(E_{i})$$
4. *Continuity from above*
   If $E_{1},E_{2},E_{3},\dots$ are measurable sets that are decreasing ($E_{i}\supseteq E_{i+1}$) then the intersection of the sets $E_{n}$ is measurable; furthermore, if at least one of the $E_{n}$ has finite measure then $$\mu\left(\bigcap_{i=1}^{\infty}E_{i}\right)=\lim_{i\to\infty}\mu(E_{i})=\inf_{i\ge1}\mu(E_{i})$$
   This property is false without the assumption that at least one of the $E_{n}$ has finite measure. As an example $\forall n\in\mathbb{N}$, let $E_{n}=[n,\infty)\subseteq\mathbb{R}$, which all have infinite Lebesgue measure, but the intersection is empty.
***
#### Keywords
- [[Set]],
- [[Sigma-algebra of sets]],
- [[Function(mapping)]],
- [[Real line]],
- [[Cardinality of a set]],
- [[Monotonicity]],
- [[Lebesgue measure]],
- [[Sequence]],
#### Possibly related
- [[Continuous mapping]]
***
#### Sources: