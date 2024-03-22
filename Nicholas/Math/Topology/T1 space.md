---
Last time checked: 2024-03-01
Complete: true
aliases:
---
# T1 space
***
###### tags: #Topology 
***
#### Definition by closed points
>[!dsn]+ Definition
>Topological space $(X,\tau)$ is said to be a $T_{1}$*-space* if every singleton set $\set{x}$, $x\in X$, is a closed set in $\tau$.^[[[Sidney A. Morris - Topology without tears.pdf#page=239|Sidney A. Morris - "Topology without tears" p.239]]]

>[!example]+ 
>Let $X=\{a,b,c\}$ with topology $\tau=\{\emptyset,X,\{a\},\{b\},\{a,b\}\}$. Then $(X,\tau)$ is not a $T_{1}$ space because for $a,b\in X$, we have open sets $\{a\}$ and $X$ such that $a\in a$ and $c\notin\{a\}$. This shows that we cannot find an open set which contains $c$ but not $a$, so $(X,\tau)$ is not a $T_{1}$ space.
>
>Furthermore $(X,\tau)$ is not even $T_{0}$ space.

#### Definition by neighborhoods
>[!dsn]+ Definition
>Topological space $(X,\tau)$ is said to be a $T_{1}$*-space* if for any two points $x\ne y$ there exists an open neighborhood of $x$ which don't contain $y$ and vice versa.^[[[Glen E. Bredon - Geometry and Topology.pdf#page=26|Glen E. Bredon - "Geometry and Topology" p.13]]]

>[!example]+ 
>The real line $\mathbb{R}$ with usual topology is a $T_{1}$ space.
>>[!proof]+
>>Suppose that $x,y\in\mathbb{R}$, $x\ne y$. Further assume that $x<y$. Then there exists an open intervals
>>$$U=(-\infty,y)\qquad V=(x,\infty)$$
>>such that $x\in U$, $y\notin U$ and $y\in V$, $x\notin V$. Thus $\mathbb{R}$ with euclidean topology is a $T_{1}$ space.

#### Equivalence of definitions
>[!proof]+ 
>Indeed, let's remove $x$ from $X$, and as open neighborhoods of $y$ which don't contain $x$, then $X\setminus\set{x}=\bigcup U_{y}$ be an open set as a union of open sets.
>
>Conversely, if $\set{x}$ is closed then open set $X\setminus\set{x}$ can be interpreted as open set containing any other point.
***
#### Keywords
- [[Topological space]],
- [[Set]],
- [[Open and closed subsets]],
- [[T0 space]],
- [[Real line]],
- [[Euclidean topology]],
- [[Neighborhood in topological space]],
- [[Interval]],
#### Possibly related
- 
***
#### Sources: