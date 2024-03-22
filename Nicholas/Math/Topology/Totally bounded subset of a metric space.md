---
Last time checked: 2024-03-01
Complete: false
aliases:
---
# Totally bounded subset of a metric space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(U,d)$ be a metric space. A subset $A\subset U$ is said to be *totally bounded* if for every $\varepsilon>0$ there exist a finite $\varepsilon$-net with respect to $A$.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page=33|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.15]]]

>If $U$ is totally bounded then $U$ is also a bounded set.
>>[!proof]+
>>Choose $u,v\in A$. Let $\set{u_{1},\dots,u_{n}}$ be a $1$-net with respect to $A$. Define
>>$$R=\max\set{d(u_{i},u_{j}):i,h\in\set{1,\dots,n}}$$ 
>>note that there exist $i,j\in\set{1,\dots,n}$ such that
>>$$d(u,u_{i})<1,\quad d(v,u_{j})<1$$
>>Therefore
>>$$d(u,v)\le d(u,u_{i})+d(u_{i},u_{j})+d(u_{j},v)\le R+2$$
>>Because we choose $u,v\in A$ arbitrarily, $A$ is a bounded subset.

>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Set]],
- [[Epsilon-net]],
- [[Bounded set]],
#### Possibly related
- 
***
#### Sources: