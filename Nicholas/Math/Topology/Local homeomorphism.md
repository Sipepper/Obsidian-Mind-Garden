# Local homeomorphism
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>A function $f:X\to Y$ between two topological spaces is called a *local homeomorphism* if for every point $x\in X$ there exists an open set $U$ containing $x$, such that the image $f(U)$ is open in $Y$ and the restriction $f|_{U}:U\to f(U)$ is a homeomorphism, with respective subspace topologies on $U$ and $f(U)$.^[https://en.wikipedia.org/wiki/Local_homeomorphism]

>Local homeomorphism is an open map.
>>[!proof]+
>>

>If there is a local homeomorphism from $X$ to $Y$, then $X$ is locally homeomorphic to $Y$, but the converse is not always true. 
>
>For example, the two dimensional sphere, being a manifold, is locally homeomorphic to $\mathbb{R}^{2}$, but there is not *no* local homeomorphism $\mathbb{S}^{2}\to\mathbb{R}^{2}$.
>>[!proof]+
>>Suppose there exists a local homeomorphism $f:\mathbb{S}^{2}\to\mathbb{R}^{2}$. Consider $f(\mathbb{S}^{2})$, it's open subset of $\mathbb{R}^{2}$. As $\mathbb{R}^{2}$ is Hausdorff and $\mathbb{S}^{2}$ is compact, by [[compact subset of Hausdorff space is closed]] $f(\mathbb{S}^{2})$ is closed, thus it is a clopen subset of $\mathbb{R}^{2}$ therefore $f(\mathbb{S}^{2})=\mathbb{R}^{2}$ as $\mathbb{R}^{2}$ is a connected space by [[clopen subsets of the set of real numbers]].
>>But [[Continuous image of compact space is compact]] $\mathbb{R}^{2}$ must be compact, but it's certainly not.

>[!example]+ 
>The two dimensional sphere $S^{2}$ is locally homeomorphic to the real plane $\mathbb{R}^{2}$.
***
#### Keywords
- [[Function(mapping)]],
- [[Topological space]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Kernel and image of a mapping]],
- [[Restriction and extension of a mapping]],
- [[Homeomorphism]],
- [[Subspace topology]],
- [[Sphere]],
- [[Topological manifold]],
- [[Euclidean space]],
- [[Compact set]],
- [[Hausdorff space]],
- [[Connected topological space]]
#### Possibly related
- 
***
#### Sources: