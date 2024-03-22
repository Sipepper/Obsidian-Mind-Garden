---
Last time checked: 2024-03-11
Complete: false
aliases:
---
# Open ball in metric space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(X,d)$ be a metric space and $r$ any positive real number. Then the *open ball about $a\in X$ of radius $r$* is the set $B_{r}(a)=\set{x\in X:d(a,x)<r}$.^[[[Sidney A. Morris - Topology without tears.pdf#page=129|Sidney A. Morris - "Topology without tears" p.129]]]

>[!example]+ 
>- In $\mathbb{R}$ with euclidean metric $B_{r}(a)$ is the open interval $(a-r,a+r)$.
>- In $\mathbb{R}^{2}$ with euclidean metric, $B_{r}(a)$ is the open disc with centre $a$ and radius $r$.
>- In $\mathbb{R}^{2}$ with the metric $d^{*}$ given by
>  $$d^{*}\left((a_{1},a_{2}),(b_{1},b_{2})\right)=\max\set{|a_{1}-b_{1}|,|a_{2}-b_{2}|}$$
>  the open ball $B_{1}((0,0))$ looks like square with sidelength $1$.
>- In $\mathbb{R}^{2}$ with the metric $d_{1}$ given by
>  $$d_{1}\left((a_{1},a_{2}),(b_{1},b_{2})\right)=|a_{1}-b_{1}|+|a_{2}-b_{2}|$$
>  the open ball $B_{1}((0,0))$ looks like a rhombus with diagonal equal to $1$.

>Let $\delta_{1}$ and $\delta_{2}$ be positive real numbers. If $c\in B_{\delta_{1}}(a)\cap B_{\delta_{2}}(b)$, then there exists a $\delta>0$ such that $B_{\delta}(c)\subseteq B_{\delta_{1}}(a)\cap B_{\delta_{2}}(b)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=131|Sidney A. Morris - "Topology without tears" p.131]]]
>>[!proof]+
>>

>Let $(X,d)$ be a metric space and $B_{1}$ and $B_{2}$ open balls in $(X,d)$. Then $B_{1}\cap B_{2}$ is a union of open balls in $(X,d)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=131|Sidney A. Morris - "Topology without tears" p.131]]]
>>[!proof]+
>>
***
#### Keywords
- [[Metric space]],
- [[Set]],
- [[Euclidean space]],
- [[Real line]],
#### Possibly related
- 
***
#### Sources: 