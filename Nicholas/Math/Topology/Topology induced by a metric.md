---
Last time checked: 2024-03-13
Complete: true
aliases:
---
# Topology induced by a metric
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(X,d)$ be a metric space. Then the collection of open balls in $(X,d)$ is a basis for a topology $\tau$ on $X$. The topology $\tau$ in this cased is referred to as *the topology induced by the metric $d$*.^[[[Sidney A. Morris - Topology without tears.pdf#page=|Sidney A. Morris - "Topology without tears" p.131]]]

>[!proof]+
>This follows from [[topology basis#basis criterions]] and definition of [[open ball in metric space]].

>[!example]+ 
>If $d$ is the euclidean metric on $\mathbb{R}$ then a basis for the topology $\tau$ induced by the metric $d$ is the set of all open balls. But $B_{\delta}(a)=(a-\delta,a+\delta)$. From this it s readily seen that $\tau$ is the euclidean topology on $\mathbb{R}$. So *the euclidean metric on $\mathbb{R}$ induces the euclidean topology on $\mathbb{R}$*.

>[!example]+
>If $d$ is the discrete metric on a set $X$ then for each $x\in X$, $B_{\frac{1}{2}}\{x\}$. So all singleton sets are open in the topology $\tau$ induced on $X$ by $d$. Consequently, $\tau$ is the discrete topology.


***
#### Keywords
- [[Metric space]],
- [[Open and closed subsets]],
- [[Open ball in metric space]],
- [[Topological space]],
- [[Topology basis]],
- [[Euclidean space]]
- [[Euclidean topology]],
- [[Interval]],
- [[Real line]],
- [[Discrete topology]],
#### Possibly related
- 
***
#### Sources: 