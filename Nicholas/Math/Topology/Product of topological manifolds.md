# Product of topological manifolds
***
###### tags: #Topology/Differential  
***
>[!dsn]+ Direct strict note
>Let $M$ be an $m$-dimensional topological manifold with possibly non-empty boundary and let $N$ be an $n$-dimensional topological manifold with empty boundary. Then the following hold:
>1. The product $M\times N$ is an $(m+n)$-dimensional topological manifold.
>2. We have $\partial(M\times N)\subset\partial M\times N$.
>3. If $M$ and $N$ are closed, then $M\times N$ is also closed.
>
>The above statements also hold with the roles of $M$ and $N$ reversed.^[Stefan Friedl - "Algebraic topology" p.265]

>[!proof]+
>1. By [[Product of Hausdorff spaces is Hausdorff]] $M\times N$ is Hausdorff and by [[product of second countable spaces is second countable]] $M\times N$ is second-countable. Then let $\Phi_{i}:M\to\mathbb{R}^{m}$ and $\Psi_{j}:N\to\mathbb{R}^{n}$ be charts. Then $\Phi_{i}\times\Psi_{j}:M\times N\to\mathbb{R}^{m+m}$ is a homeomorphism, thus $M\times N$ is a topological manifold.
>2. The product of charts of type $(i)$ is again a chart of type $(i)$.
>   
>3. By [[Tychonoff's theorem]] $M\times N$ is compact, and by $(2)$ 
>   $$\partial(M\times N)\subset\partial M\times N=\emptyset\times N=\emptyset$$
>   thus $\partial(M\times N)$ is empty, therefore $M\times N$ is closed topological manifold.

>[!example]+ 
>For any $n\in\mathbb{N}$ the $n$-dimensional torus $(S^{1})^{n}$ is a closed $n$-dimensional topological manifold.

>[!example]+ 
>The annulus $S^{1}\times[0,1]$ is a $2$-dimensional topological manifold and that $S^{1}\times\overline{B}^{2}$ is a $3$-dimensional topological manifold.

***
#### Keywords
- [[Topological manifold]],
- [[Product topology]],
- [[n-dimensional chart]],
- [[Homeomorphism]],
- [[Open ball in metric space]],
- [[Torus]],
- [[Compact set]],
- [[Set]],
- [[Annulus]]
#### Possibly related
- [[Interior, Exterior and boundary of a set in topological space]]
***
#### Sources: