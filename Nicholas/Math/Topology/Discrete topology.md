---
Last time checked: 2024-02-29
Complete: true
aliases:
---
# Discrete topology
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $X$ be any non-empty set and let $\tau$ be the collection of all subsets of $X$. Then $\tau$ is called the *discrete topology* on the set $X$. The topological space $(X,\tau)$ is called a *discrete space*.^[[[Sidney A. Morris - Topology without tears.pdf#page=27|Sidney A. Morris - "Topology without tears" p.27]]]

>[!example]+
>If $X=\set{a,b,c}$ and $\tau$ is a topology on $X$ with $\{a\}\in\tau$, $\{b\}\in\tau$ and $\{c\}\in\tau$, then $\tau$ is a discrete topology. Because every possible subset of $X$ can be viewed as a union of singleton sets.^[[[Sidney A. Morris - Topology without tears.pdf#page=28|Sidney A. Morris - "Topology without tears" p.28]]]

#### Necessary and sufficient conditions to be discrete space
>[!dsn]+ Proposition
>If $(X,\tau)$ is a topological space such that, for every $x\in X$, the singleton set $\{x\}$ is in $\tau$, then $\tau$ is the discrete topology.^[[[Sidney A. Morris - Topology without tears.pdf#page=29|Sidney A. Morris - "Topology without tears" p.29]]]

>[!proof]+
>First, we can see that every set is the union of all its singleton subsets, i.e. $S\subseteq X$, then
>$$S=\bigcup_{x\in S}\{x\}$$
>Since we are given that each $\{x\}\in\tau$ than any arbitrary subset of $X$ is in $\tau$, thus $\tau$ is the discrete topology.

#### Limit points
>[!dsn]+ Proposition
>Let $(X,\tau)$ be a discrete space and $A$ a subset of $X$. Then $A$ has no limits points, since for each $x\in X$, $\{x\}$ is an open set containing no point of $A$ different from $x$.^[[[Sidney A. Morris - Topology without tears.pdf#page=75|Sidney A. Morris - "Topology without tears" p.75]]]

***
#### Keywords
- [[Set]],
- [[Power set]],
- [[Topological space]],
- [[Limit point in topological space]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: