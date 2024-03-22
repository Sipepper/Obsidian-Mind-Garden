---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Baire space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>A topological space $(X,\tau)$ is said to be a *Baire space* if for every sequence $\set{X_{n}}$ of open dense subsets of $X$, the set $\bigcap_{n=1}^{\infty}X_{n}$ is also dense.^[[[Sidney A. Morris - Topology without tears.pdf#page=165|Sidney A. Morris - "Topology without tears" p.165-166]]]

>Every complete metrizable space is a Baire space.
>>[!proof]+
>>

>[!example] 
>The topological space $\mathbb{Q}$ is not a Baire space and so is not completely metrizable. 
>>[!proof]
>>Note that $\mathbb{Q}$ is countable, let $\mathbb{Q}=\set{x_{1},x_{2},\dots,x_{n},\dots}$. Each of the sets $X_{n}=\mathbb{Q}\setminus\{x_{n}\}$ is open and dense in $\mathbb{Q}$, however $\bigcap_{n=1}^{\infty}X_{n}=\emptyset$. Thus $\mathbb{Q}$ does not have the Baire space property.
***
#### Keywords
- [[Topological space]],
- [[Sequence]],
- [[Open and closed subsets]],
- [[Set]],
- [[Dense subset]],
- [[Completely metrizable space]],
- [[Rational numbers]]
- [[Cardinality of a set]],
#### Possibly related
- 
***
#### Sources: