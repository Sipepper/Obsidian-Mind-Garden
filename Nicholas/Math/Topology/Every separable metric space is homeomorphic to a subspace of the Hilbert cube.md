---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Every separable metric space is homeomorphic to a subspace of the Hilbert cube
***
###### tags: #Topology 
***
>[!dsn]+ Theorem
>Every separable metric space $(X,d)$ is homeomorphic to a subspace of the Hilbert cube.^[[[Sidney A. Morris - Topology without tears.pdf#page=240|Sidney A. Morris - "Topology without tears" p.240]]]

>[!proof]+
>By [[the embedding lemma]] this result will follow if we can find a countably infinite family of mappings $f_{i}:(X,d)\to[0,1]$, which are $(1)$ continuous, and $(2)$ separate points and closed sets.
>Without loss of generality we can assume that $d(a,b)\le1$, for all $a$ and $b$ in $X$, since every metric is equivalent to such a metric.
>As $(X,d)$ is separable, there exists a countable dense subset $Y=\{y_{i}\}$, $i\in\mathbb{N}$. For each $i\in\mathbb{N}$, define $f_{i}:X\to[0,1]$ by $f_{i}(x)=d(x,y_{i})$. It is clear that each mapping $f_{i}$ is continous.
>To see that the mappings $\{f_{i}\}$, $i\in\mathbb{N}$, separate points and closed sets, let $x\in X$ and $A$ be any closed set not containing $x$. Now $X\setminus A$ is an open set about $x$ and so contains an open ball $B$ of radius $\varepsilon$ and centre $x$, for some $\varepsilon>0$.
>Further, as $Y$ is dense in $X$, there exists a $y_{n}$ such that $d(x,y_{n})<\frac{\varepsilon}{2}$. Thus $d(y_{n},a)\ge\frac{\varepsilon}{2}$, for all $a\in A$.
>So $[0,\frac{\varepsilon}{2})$ is an open set in $[0,1]$ which contains $f_{n}(x)$, but $f_{n}(a)\notin[0,\frac{\varepsilon}{2})$, for all $a\in A$. This implies $f_{n}(A)\subseteq[\frac{\varepsilon}{2},1]$. As the set $[\frac{\varepsilon}{2},1]$ is closed, this implies $\overline{f_{n}(A)}\subseteq[\frac{\varepsilon}{2},1]$.
>Hence $f_{n}(x)\notin\overline{f_{n}(A)}$ and thus the family $\{f_{i}\}$, $i\in\mathbb{N}$ separates points and closed sets.

>[!example]+ 
>
***
#### Keywords
- [[Separable space]],
- [[Metric space]],
- [[Homeomorphism]],
- [[Hilbert's cube]],
- [[Subspace topology]],
- [[Cardinality of a set]],
- [[Function(mapping)]],
- [[Interval]],
- [[Open and closed subsets]],
- [[Equivalent metrics]],
- [[Continuous mapping]],
- [[Dense subset]],
- [[Open ball in metric space]],
- [[Closure of a set]]
- [[Set]],
#### Possibly related
- 
***
#### Sources: