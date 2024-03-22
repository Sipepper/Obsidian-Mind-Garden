---
Last time checked: 2024-02-27
Complete: false
aliases:
---
# Every non-discrete subgroup of real line is dense
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Theorem
>Every non-discrete subgroup $G$ of $\mathbb{R}$ is dense.^[[[Sidney A. Morris - Topology without tears.pdf#page=537|Sidney A. Morris - "Topology without tears" p.537]]]

>[!proof]+
>We have to show that for each $x\in\mathbb{R}$ and each $\varepsilon>0$, there exists an element $g\in G\cap[x-\varepsilon,x+\varepsilon]$.
>As $G$ is not discrete, $0$ is not an isolated point. So there exists an element 
>$$x_{\varepsilon}\in(G\setminus\{0\})\cap[0,\varepsilon]$$
>then the intervals $[nx_{\varepsilon},(n+1)x_{\varepsilon}]$, $n=0,\pm1,\pm2,\dots$ cover $\mathbb{R}$ and are of length $\le\varepsilon$. So for some $n$, $nx_{\varepsilon}\in[x-\varepsilon,x+\varepsilon]$ and of course $nx_{\varepsilon}\in G$.

>[!example]+ 
>
***
#### Keywords
- [[Discrete group]],
- [[Topological group]],
- [[Real line]],
- [[Dense subset]],
- [[Interval]],
- [[Isolated point]],
- [[Covering of a set]],
- [[Delta covering]]
#### Possibly related
- 
***
#### Sources: