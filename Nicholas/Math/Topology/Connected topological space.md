---
Last time checked: 2024-03-13
Complete: true
aliases:
---
# Connected topological space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(X,\tau)$ be a topological space. Then it is said to be *connected* if only clopen subsets in $(X,\tau)$ are $X$ and $\emptyset$.^[[[Sidney A. Morris - Topology without tears.pdf#page=87|Sidney A. Morris - "Topology without tears" p.87]]]

>A topological space $(X,\tau)$ is not connected (that is, it is *disconnected*) if and only if there are non-empty open sets $A$ and $B$ such that $A\cap B=\emptyset$ and $A\cup B=X$.^[[[Sidney A. Morris - Topology without tears.pdf#page=87|Sidney A. Morris - "Topology without tears" p.87]]]

>[!example]+ 
>Let $X=\set{a,b,c,d,e}$ and $$\tau=\set{X,\emptyset,\{a\},\{c,d\},\{a,c,d\},\{b,c,d,e\}}$$ then $(X,\tau)$ is not connected, because $\set{b,c,d,e}$ is a clopen nonempty subset.

>[!example]+
>Let $(X,\tau)$ any discrete space with one or more elements, then $(X,\tau)$ is not connected because every singleton set is a clopen subset.

>[!example]+
>Topological space $\mathbb{R}$ is connected. Because only clopen subsets in $\mathbb{R}$ is $\emptyset$ and $\mathbb{R}$. This follows from [[clopen subsets of the set of real numbers]].

>Any topological space homeomorphic to a connected space, is also connected.^[[[Sidney A. Morris - Topology without tears.pdf#page=102|Sidney A. Morris - "Topology without tears" p.102]]]
>>[!proof]+
>>It's true because homeomorphism is also a surjective continuous mapping, thus such mapping preserve connectedness. Therefore homeomorhism preserve connectedness as required.

>Let $(X,\tau)$ and $(Y,\tau_{1})$ be a topological spaces and $f:(X,\tau)\to(Y,\tau_{1})$ is a surjective continuous mapping. If $(X,\tau)$ is connected, then $(Y,\tau_{1})$ will also be connected.
>>[!proof]+
>>Let $d:f(X)\to D$ be a discrete valued mapping. The $d\circ f$ be a discrete balued mapping on $X$ and thus must be constant. But it means that $d$ is a constant mapping, therefore $f(X)$ will be connected space.^[[[Glen E. Bredon - Geometry and Topology.pdf#page=24|Glen E. Bredon - "Geometry and Topology" p.11]]]


***
#### Keywords
- [[Topological space]],
- [[Open and closed subsets]],
- [[Discrete topology]],
- [[Euclidean topology]],
- [[Real line]],
- [[Function(mapping)]],
- [[Continuous mapping]],
- [[Discrete valued map]],
- [[Homeomorphism]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: