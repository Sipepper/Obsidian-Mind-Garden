---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Connectedness via discrete-valued function
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>A topological space $(X,\tau)$ is connected if and only if every discrete-valued map from $X$ is constant.^[[[Glen E. Bredon - Geometry and Topology.pdf#page=23|Glen E. Bredon - "Geometry and Topology" p.10]]]

>[!proof]+
>Let $X$ be connected and $d:X\to D$ is a discrete-valued map. if $y\in D$ lies in image of $d$, then $d^{-1}(y)$ be clopen as a preimage of continuous map and non-empty. Therefore such preimage is equal to $X$, and thus $d$ is a constant map.
>
>Conversely, let $X$ be disconnected space, then $X=U\cup V$ for some disjoint clopen sets $U$ and $V$. Then mapping $d:X\to\{0,1\}$ such that $d(U)=0$ and $d(V)=1$. Thus it's not a constant map.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Connected topological space]],
- [[Discrete valued map]],
- [[Preimage]],
- [[Open and closed subsets]],
- [[Continuous mapping]],
- [[Function(mapping)]],
- [[Set]]
#### Possibly related
- [[Kernel and image of a mapping]],
***
#### Sources: