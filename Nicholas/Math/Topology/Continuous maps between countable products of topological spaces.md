# Continuous maps between countable products of topological spaces
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X_{i},\tau_{i})$ and $(Y_{i},\tau'_{i})$, $i\in\mathbb{N}$, be countably infinite families of topological spaces having product spaces $\left(\prod_{i=1}^{\infty},\tau\right)$ and $\left(\prod_{i=1}^{\infty}Y_{i},\tau'\right)$, respectively. If the mapping $h_{i}:(X_{i},\tau_{i})\to(Y_{i},\tau'_{i})$ is continuous for each $i\in\mathbb{N}$, then so is the mapping $h:\left(\prod_{i=1}^{\infty}X_{i},\tau\right)\to\left(\prod_{i=1}^{\infty}Y_{i},\tau'\right)$ given by $h\left(\prod_{i=1}^{\infty}x_{i} \right)=\prod_{i=1}^{\infty}h_{i}(x_{i})$; that is, $h((x_{1},x_{2},\dots,x_{n},\dots))=(h_{1}(x_{1}),h_{2}(x_{2}),\dots,h_{n}(x_{n}),\dots)$.^[Sidney A. Morris - "Topology without tears" p.226]

>[!proof]+
>It suffices to show that if $O$ is a basic open set in $\left(\prod_{i=1}^{\infty}Y_{i},\tau' \right)$, then $h^{-1}(O)$ is open in $\left(\prod_{i=1}^{\infty}X_{i},\tau\right)$. Consider the basic open set $U_{1}\times U_{2}\times\dots\times U_{n}\times Y_{n+1}\times Y_{n+2}\times\dots$ where $U_{i}\in\tau'_{i}$, for $i=1,\dots,n$. Then
>$$h^{-1}(U_{1}\times\dots\times U_{n}\times Y_{n+1}\times Y_{n+2}\times\dots)=h_{1}^{-1}(U_{1})\times\dots\times h_{n}^{-1}(U_{n})\times X_{n+1}\times X_{n+2}\times\dots$$
>and the set on the right hand side is in $\tau$, since the continuity of each $h_{i}$ implies $h_{i}^{-1}(U_{i})\in\tau_{i}$, for $i=1,\dots,n$. So $h$ is continuous.

>[!example]+ 
>
***
#### Keywords
- [[Cardinality of a set]],
- [[Product topology]],
- [[Topological space]],
- [[Function(mapping)]],
- [[Continuous mapping]],
- [[Preimage]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: