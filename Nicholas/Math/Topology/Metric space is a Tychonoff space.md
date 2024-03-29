---
Last time checked: 2024-03-10
Complete: false
aliases:
---
# Metric space is a Tychonoff space
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(X,d)$ be a metric space and $\tau$ be a topology induced by $d$ on $X$. Then $(X,\tau)$ is a Tychonoff space.^[[[Sidney A. Morris - Topology without tears.pdf#page=275|Sidney A. Morris - "Topology without tears" p.275]]]

>[!proof]+
>Let $a\in X$ and $U$ be an open neighbourhood of $a$. Then $U$ contains an open ball of radius $\varepsilon>0$ centered at $a$.
>
>Define a map $f:(X,d)\to[0,1]$ in the following way
>$$f(x)=\min\left\{1,\frac{d(x,a)}{\varepsilon}\right\}\quad x\in X$$
>Then $f$ is continuous and has property that $f(a)=0$ and $f(y)=1$, $\forall y\in X\setminus U$. As $(X,d)$ is Hausdorff it is a Tychonoff space.


>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Topology induced by a metric]],
- [[Completely regular and Tychonoff spaces]],
- [[Neighborhood in topological space]],
- [[Open ball in metric space]],
- [[Function(mapping)]],
- [[Interval]],
- [[Continuous mapping]],
- [[Metric space is a Hausdorff space]],
- [[Hausdorff space]]
#### Possibly related
- 
***
#### Sources: