# Sequences in topological vector spaces
***
###### tags: #Topology 
***
#### Every vector can be scaled down to fit into a neighborhood of zero
>[!dsn] Direct strict note
>Let $U$ be a topological vector space and $\mathcal{V}$ a neighborhood of zero in $U$.  Given $u\in U$, there exists $r\in\mathbb{R}^{+}$ such that $\beta u\in\mathcal{V}$, $\forall\beta$ such that $|\beta|<r$.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.8]

>[!proof]
>Observe that $u+\mathcal{V}$ is a neighborhood of $1\cdot u$, and then by the continuity of scalar multiplication, there exists $\mathcal{W}$ neighborhood of $u$ and $r>0$ such that
>$$\beta\mathcal{W}\subset u+\mathcal{V},\forall\beta:|\beta-1|<r$$
>so that
>$$\beta u\in u+\mathcal{V}$$
>or
>$$(\beta-1)u\in\mathcal{V},\;\text{where}\;|\beta-1|<r$$
>and thus
>$$\hat{\beta}u\in\mathcal{V},\forall\hat{\beta}:|\hat{\beta}|<r$$
>which completes the proof.

>[!example] 
>

#### Topological vector space can be covered by union of scaled neighborhoods of zero
>[!dsn] Direct strict note
>Let $\mathcal{V}$ be a neighborhood of zero in $U$. If $\set{r_{n}}$ is a sequence such that $r_{n}>0$, $\forall n\in\mathbb{N}$, and $\lim_{n\to\infty}r_{n}=\infty$, then $U\subset\bigcup_{n=1}^{\infty}r_{n}\mathcal{V}$.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.9]

>[!proof]
>Let $u\in U$, then $\alpha u\in\mathcal{V}$ for any $\alpha$ sufficiently small, from the proposition [[Sequences in topological vector spaces#Every vector can be scaled down to fit into a neighborhood of zero|about scaled neighborhoods]] $u\in\frac{1}{\alpha}\mathcal{V}$. As $r_{n}\to\infty$ we have that $r>\frac{1}{\alpha}$ for $n$ sufficiently big, so that $u\in r_{n}\mathcal{V}$, which completes the proof.

***
#### Keywords
- [[Topological vector space]],
- [[Properties of balanced and convex neighbourhoods of zeros in topological vector spaces]],
- [[Neighborhood in topological space]],
- [[Sequence]],
- [[Covering of a set]],
#### Possibly related
- 
***
#### Sources: