---
Last time checked: 2024-02-25
Complete: false
aliases:
---
# Product of topological groups is a topological group
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>If each $G_{i}$, $i\in\Lambda$ is a topological group, then $\prod\limits_{i\in\Lambda}G_{i}$ is a topological group. Further $\prod^{r}\limits_{i\in\Lambda}G_{i}$ is a dense subgroup of $\prod\limits_{i\in\Lambda}G_{i}$.^[[[Sidney A. Morris - Topology without tears.pdf#page=529|Sidney A. Morris - "Topology without tears" p.529]]]

>[!proof]+
>As $\prod\limits_{i\in\Lambda}G_{i}$ has a group structure and $\prod\limits_{i\in\Lambda}G_{i}$ is a product of topological spaces $G_{i}$ it suffices to prove that $m':\left(\prod\limits_{i\in\Lambda}G_{i}\times\prod\limits_{i\in\Lambda}G_{i}\right)\to\prod\limits_{i\in\Lambda}G_{i}$ is a continuous mapping. We can construct a following commutative diagram
>$$\begin{CD}\prod\limits_{i\in\Lambda}G_{i}\times\prod\limits_{i\in\Lambda}G_{i} @>{m'}>>\prod\limits_{i\in\Lambda}G_{i}\\ @V{p_{i}\times p_{i}}VV @V{p_{i}}VV\\ G_{i}\times G_{i} @>{m_{i}}>> G_{i}\end{CD}$$
>from which we can conclude that $m'\circ p_{i}$ is equivalent to $(p_{i}\times p_{i})\circ m_{i}$ for all $i\in\Lambda$, that is if $(p_{i}\times p_{i})\circ m_{i}$ is continuous for all $i\in\Lambda$ then $m'\circ p_{i}$ continuous as well. 
>As $p_{i}\times p_{i}$ is continous as a product of projection mappings, and $m_{i}$ is continuous by a definition of topological groups. And as $p_i$ is continous $m'$ is also must be continuous. 
>
>Also such statement can be proved by noting that 
>$$m'\left(\prod\limits_{i\in\Lambda}G_{i},\prod\limits_{i\in\Lambda}G_{i}\right)=\prod\limits_{i\in\Lambda}m_{i}(G_{i},G_{i})$$
>using [[continuous maps between countable products of topological spaces]].
>
>Let $U=U_{1}\times\dots\times U_{n}\times\prod\limits_{i\in\Lambda\setminus\{1,\dots,n\}}G_{i}$ be a basic open subset of $\prod\limits_{i\in\Lambda}G_{i}$. Let $x$ be an element such that $x=(x_{1},x_{2},\dots,x_{n})\times\prod\limits_{i\in\Lambda}e_{i}\in U$, we can see that $x\in\prod\limits_{i\in\Lambda}^{r}G_{i}$ that is $U\cap\prod\limits_{i\in\Lambda}^{r}G_{i}$ is at least $x$, which imply that $\prod\limits_{i\in\Lambda}^{r}G_{i}$ is dense in $\prod\limits_{i\in\Lambda}G_{i}$. 

>[!example]+ 
>
***
#### Keywords
- [[Topological group]],
- [[Direct product of groups]],
- [[Box product of groups]],
- [[Product topology]],
- [[Dense subset]],
- [[Group]],
- [[Continuous mapping]],
- [[Commutative diagram]],
- [[Topological space]],
- [[Cartesian product of sets]],
- [[Projection map in product spaces]],
- [[Topology basis]],
- [[Open and closed subsets]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: