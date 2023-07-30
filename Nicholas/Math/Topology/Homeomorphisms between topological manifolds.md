# Homeomorphisms between topological manifolds
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $M$ and $N$ be two topological manifolds.
>1. If $f\colon M\to N$ is a local homeomorphism, then $f(\partial M)=(\partial N)\cap f(M)$.
>2. If $f\colon M\to N$ is in fact a homeomorphism, then $f$ restricts to a homeomorphism $\partial M\to\partial N$.^[Stefan Friedl - "Algebraic topology" p.265]

>[!proof]+
>Let $f\colon M\to N$ be a local homeomorphism, that is for every point $x\in M$ there exist an open set $U$ containing $x$ (neighborhood), such that the image $f(U)$ is open in $Y$ and the restriction $f|_{U}\colon U\to f(U)$ is a homeomorphism.
>Consider a point $b\in\partial M$, and respective chart $(U,\Phi)$, where $\Phi\colon U\to H_{n}$. 
>Observe that restriction of a chart *do not* change it's type, thus $f(b)\in\partial N$. Thus 
>$$f(\partial M)=(\partial N)\cap f(M)$$
>
>And if $f$ is a homeomorphism, then every open neighborhood in $M$ is of the form $f^{-1}(N)$ and conversely every neighborhood in $N$ is of the form $f(M)$. As every homeomorphism is a local-homeomorphism $f(\partial M)=\partial N\cap N=\partial N$. And we only care about boundary points as every chart of type $(i)$ in $M$ is in one-to-one correspondence with chart of type $(i)$ in $N$. 

>[!example]+ 
>
***
#### Keywords
- [[Topological manifold]],
- [[Local homeomorphism]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Kernel and image of a mapping]],
- [[Restriction and extension of a mapping]],
- [[n-dimensional chart]],
- [[Homeomorphism]]
#### Possibly related
- 
***
#### Sources: