# TVS can be covered by union of scaled neighborhoods of zero
***
###### tags: #Topology #Algebra/Linear 
***
>[!dsn]+ Direct strict note
>Let $\mathcal{V}$ be a neighborhood of zero in $U$. If $\set{r_{n}}$ is a sequence such that $r_{n}>0$, $\forall n\in\mathbb{N}$, and $\lim\limits_{n\to\infty}r_{n}=\infty$, then $U\subset\bigcup\limits_{n=1}^{\infty}r_{n}\mathcal{V}$.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.9]

>[!proof]+
>Let $u\in U$, then $\alpha u\in\mathcal{V}$ for any $\alpha$ sufficiently small, from the [[every vector from TVS can be scaled down to fit into a neighborhood of zero]] $u\in\frac{1}{\alpha}\mathcal{V}$. As $r_{n}\to\infty$ we have that $r>\frac{1}{\alpha}$ for $n$ sufficiently big, so that $u\in r_{n}\mathcal{V}$, which completes the proof.

>[!example]+ 
>
***
#### Keywords
- [[Neighborhood in topological space]],
- [[Sequence]],
- [[Convergence in topological vector spaces]]
#### Possibly related
- 
***
#### Sources: