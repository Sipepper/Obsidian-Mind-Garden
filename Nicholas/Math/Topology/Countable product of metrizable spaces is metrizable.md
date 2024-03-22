---
Last time checked: 2024-03-05
Complete: false
aliases:
---
# Countable product of metrizable spaces is metrizable
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(X_{i},\tau_{i})$, $i\in\mathbb{N}$, be a countably infinite family of metrizable spaces. Then $\prod_{i=1}^{\infty}(X_{i},\tau_{i})$ is metrizable.^[[[Sidney A. Morris - Topology without tears.pdf#page=232|Sidney A. Morris - "Topology without tears" p.232]]]

>[!proof]+
>For each $i\in\mathbb{N}$, let $d_{i}$ be a metric on $X_{i}$ which induces the topology $\tau_{i}$. If we put $e_{i}(a,b)=\min(1,d_{i}(a,b))$, for all $a$ and $b$ in $X_{i}$, then $e_{i}$ is a metric and it induces the topology $\tau_{i}$ on $X_{i}$. So we can, without loss of generality, assume that $d_{i}(a,b)\le1$, for all $a$ and $b$ in $X_{i}$, $i\in\mathbb{N}$.
>
>Define $d:\prod_{i=1}^{\infty}X_{i}\times\prod_{i=1}^{\infty}X_{i}\to\mathbb{R}$ by
>$$d\left(\prod\limits_{i=1}^{\infty}a_{i},\prod\limits_{i=1}^{\infty}b_{i}\right)=\sum\limits_{i=1}^{\infty}\frac{d_{i}(a_{i},b_{i})}{2^{i}}\quad\forall a_{i},b_{i}\in X_{i}$$
>Observe that the series on the right hand side converges because each $d_{i}(a_{i},b_{i})\le1$ and so it is bounded above by $\sum\limits_{i=1}^{\infty}\frac{1}{2^{i}}=1$.
>It is easily verified that $d$ is a metric on $\prod_{i=1}^{\infty}X_{i}$ . Observe that $d'_{i}$, defined by $d'_{i}(a,b)=\frac{d_{i}(a,b)}{2^{i}}$, is a metric on $X_{i}$, which induces the same topology $\tau_{i}$ as $d_{i}$. We claim that $d$ induces the product topology on $\prod_{i=1}^{\infty}X_{i}$.
>
>To see this consider the following. Since
>$$d\left(\prod\limits_{i=1}^{\infty}a_{i},\prod\limits_{i=1}^{\infty}b_{i}\right)\ge\frac{d_{i}(a_{i},b_{i})}{2^{i}}=d'_{i}(a_{i},b_{i})$$
>it follows that the projection $p_{i}:\left(\prod_{i=1}^{\infty}X_{i},d\right)\to(X_{i},d'_{i})$ is continuous, for each $i$. As $d'_{i}$ induces the topology $\tau'_{i}$, [[projection map in product spaces#countable case]] implies that the topology induced on $\prod_{i=1}^{\infty}X_{i}$ by $d$ is *finer* than the product topology.
>To prove that the topology induced by $d$ is also coarser than the product topology, let $B_{\varepsilon}(a)$ is a basic open set in the topology induced by $d$. We have to show that there is a set $W\ni a$ such that $W\subseteq B_{\varepsilon}(a)$, and $W$ is open in the product topology. Let $N$ be a positive integer such that $\sum_{i=N}^{\infty}\frac{1}{2^{i}}<\frac{\varepsilon}{2}$. Let $O_{i}$ be the open ball in $(X_{i},d_{i})$ of radius $\frac{\varepsilon}{2N}$ about the point $a_{i}$, $i=1,\dots,N$. Define
>$$W=O_{1}\times O_{2}\times\dots\times O_{N}\times X_{N+1}\times X_{N+2}\times\dots$$
>Then $W$ is an open set in the product topology, $a\in W$, and clearly $W\subseteq B_{\varepsilon}(a)$, as required.

***
#### Keywords
- [[Cardinality of a set]],
- [[Metrizable space]],
- [[Product topology]],
- [[Set of natural numbers]],
- [[Metric space]],
- [[Topology induced by a metric]],
- [[Equivalent metrics]],
- [[Real line]],
- [[Bounded set]],
- [[Projection map in product spaces]],
- [[Topology comparison]],
- [[Open ball in metric space]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]]
#### Possibly related
- 
***
#### Sources: