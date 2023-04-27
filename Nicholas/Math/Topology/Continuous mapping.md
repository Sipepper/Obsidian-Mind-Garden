# Continuous mapping
***
###### tags: #Topology #Fundamental_math_objects 
***
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ and $(Y,\tau_{1})$ be topological spaces and $f$ a function from $X$ into $Y$. Then $f:(X,\tau)\to(Y,\tau_{1})$ is said to be a *continuous mapping* if for each $U\in\tau_{1}$, $f^{-1}(U)\in\tau$.^[Sidney A. Morris - "Topology without tears" p.112]

>[!example]+
>Consider $f:\mathbb{R}\to\mathbb{R}$ given by $f(x)=x$, for all $x\in\mathbb{R}$; that is, $f$ is the identity function. Then for any open set $U$ in $\mathbb{R}$, $f^{-1}(U)=U$ and so is open. Hence $f$ is continuous.

>[!example]+
>Consider $f:\mathbb{R}\to\mathbb{R}$ defined by
>$$f(x)=\begin{cases}x-1,&\text{if }x\le3\\ \frac{1}{2}(x+5),&\text{if }x>3 \end{cases}$$
>then $f^{-1}((1,3))=(2,3]$, which is not an open set. Therefore $f$ is not continuous.

>Let $(X,\tau)$, $(Y,\tau_{1})$ and $(Z,\tau_{2})$ be topological spaces. If $f:(X,\tau)\to(Y,\tau_{1})$ and $g:(Y,\tau_{1})\to(Z,\tau_{2})$ are continuous mappings, then the composite function $g\circ f:(X,\tau)\to(Z,\tau_{2})$ is continuous, that is *continuity is a transitive property*.
>>[!proof]+
>>Let $U$ be open in $(Z,\tau_{2})$. Since $g$ is continuous, $g^{-1}(U)$ is open in $\tau_{1}$. Then $f^{-1}(g^{-1}(U))$ is open in $\tau$ as $f$ is continuous. But $f^{-1}(g^{-1}(U))=(g\circ f)^{-1}(U)$. Thus $g\circ f$ is continuous.

>Let $(X,\tau)$ and $(Y,\tau_{1})$ be topological spaces. Then $f:(X,\tau)\to(Y,\tau_{1})$ is continuous if and only if for every closed subset $S$ of $Y$, $f^{-1}(S)$ is a closed subset of $X$.
>>[!proof]+
>>

#### Continuity by image
>[!dsn]+ Direct strict note
>Let $f$ be a mapping of a topological space $(X,\tau)$ into a space $(Y,\tau')$. Then $f$ is continuous if and only if for each $x\in X$ and each $U\in\tau'$ with $f(x)\in U$, there exists a $V\in\tau$ such that $x\in V$ and $f(V)\subseteq U$.^[Sidney A. Morris - "Topology without tears" p.114]

>[!proof]+
>

***
#### Keywords
- [[Topological space]],
- [[Function(mapping)]],
- [[Real line]],
- [[Preimage]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources: