---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Weierstrass Intermediate Value theorem
***
###### tags: #Topology #Analysis 
***
>[!dsn]+ Theorem
>Let $f:[a,b]\to\mathbb{R}$ be continuous and let $f(a)\ne f(b)$. Then for every number $p$ between $f(a)$ and $f(b)$ there is a point $c\in[a,b]$ such that $f(c)=p$.^[[[Sidney A. Morris - Topology without tears.pdf#page=119|Sidney A. Morris - "Topology without tears" p.119]]]

>[!proof]+
>As $[a,b]$ is connected and $f$ is continuous, [[Connected topological space#Continuous surjective mappings preserve connectedness|Continuous surjective mappings preserve connectedness]] says that $f([a,b])$ is connected. By [[Connected subspaces of real line]] this implies that $f([a,b])$ is an interval. Now $f(a)$ and $f(b)$ are in $f([a,b])$. So if $p$ is between $f(a)$ and $f(b)$, $p\in f([a,b])$, that is, $p=f(c)$, for some $c\in[a,b]$.

>[!example]+ 
>
***
#### Keywords
- [[Interval]],
- [[Real line]]
- [[Continuous mapping]],
- [[Connected topological space]],
- [[Euclidean topology]]
#### Possibly related
- 
***
#### Sources: