# Separability criterion for metric spaces
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,d)$ be a metric space and $\tau$ be topology induced by $d$. Then $(X,\tau)$ is a separable space if and only if it is satisfies the second axiom of countability.^[Sidney A. Morris - "Topology without tears" p.241-242]

>[!proof]+
>$\Rightarrow$
>Let $(X,\tau)$ be separable. Then it has a countable dense subset $Y=\{Y_{i}:i\in\mathbb{N}\}$. Let $\mathcal{B}$ be a family of open balls in $d$ centered at points $y_{i}$ and radius $\frac{1}{n}$ for some positive integer. Clearly $\mathcal{B}$ is countable and we shall show that it is a basis for $\tau$.
>
>Let $V\in\tau$. Then for any element $v\in V$, $V$ contains an open ball $B$ with radius $\frac{1}{n}$ at point $v$, for some $n$. As $Y$ is dense in $X$, then there exist $y_{m}\in Y$, such that $d(y_{m},v)<\frac{1}{2n}$. Let $B'$ be an open ball centered at $y_{m}$ with radius $\frac{1}{2n}$. Then by the triangle inequality $B'\subseteq V\subseteq V$. Also $B'\in\mathcal{B}$. Therefore $\mathcal{B}$ is a basis for $\tau$. Thus $(X,\tau)$ is second countable.
>
>$\Leftarrow$
>Conversely, let $(X,\tau)$ satisfies the second axiom of countability, and has a countable basis $\mathcal{B}_{1}=\{B_{i}:i\in\mathbb{N}\}$. For each $B_{i}\ne\emptyset$ let $b_{i}$ be an arbitrary element from $B_{i}$, put $Z$ as a set of all such $b_{i}$. Then $Z$ is a countable set. Further let $V\in\tau$, then $V\supseteq B_{i}$, for some $i$, and so $b_{i}\in V$. Therefore $V\cap Z\ne\emptyset$. Thus $Z$ is dense in $X$. Consequently $(X,\tau)$ is separable.
>

>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Topological space]],
- [[Topology induced by a metric]],
- [[Separable space]],
- [[Second axiom of countability]],
- [[Cardinality of a set]],
- [[Open ball in metric space]],
- [[Set of integers]],
- [[Topology basis]],
- [[Dense subset]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: