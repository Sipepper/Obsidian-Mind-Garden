# Every normed space is a geodesic space
***
###### tags: #Geometry 
***
>[!dsn] Direct strict note
>Every normed vector space $V$ is a geodesic space.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.5-6]
>
>It is uniquely geodesic if and only iff the unit ball in $V$ is strictly convex(in the sense that if $u_{1}$ and $u_{2}$ are distinct vectors of norm $1$, then $\|(1-t)u_{1}+tu_{2} \|<1$ for all $t\in(0,1)$).

>[!proof]
>Because mapping $t\mapsto(1-t)v+tw$ defines a path $[0,1]\to X$ which is a linearly parametrized geodesic from $v$ to $w$ with image denoted by $[v,w]$ we see that $V$ is uniquely geodesic if and only if, given any $v,v',v''\in V$, the equality $d(v,v')+d(v',v'')=d(v,v'')$ implies that $v'\in[v,v'']$. Thus, writing $v_{1}$ in place of $v'-v$ and $v_{2}$ in place of $v''-v'$, we see that $V$ is uniquely geodesic if and only if $\|v_{1}+v_{2}\|<\|v_{1} \|+\|v_{2}\|$ whenever $v_{1}$ and $v_{2}$ are linearly independent.
>
>If we write $v_{i}=a_{i}u_{i}$, where $a_{i}=\|v_{i}\|$, and let $t=a_{1}/(a_{1}+a_{2})$, then $$\begin{align}v_{1}+v_{2}&=(a_{1}+a_{2})\left(\frac{a_{1}}{a_{1}+a_{2}}u_{1}+\frac{a_{2}}{a_{1}+a_{2}}u_{2}\right)\\ &=(a_{1}+a_{2})(tu_{1}+(1-t)u_{2} \end{align}$$ Hence $\|v_{1}+v_{2}\|<\|v_{1}\|+\|v_{2}\|$ if and only if $\|tu_{1}+(1-t)u_{2}\|<1$.
***
#### Keywords
- [[Geodesic path in metric space]],
- [[Normed space]],
- [[Vector space]],
- [[Open ball in metric space]],
- [[Convex set]],
- [[Function(mapping)]],
#### Possibly related
- 
***
#### Sources: