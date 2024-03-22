---
Last time checked: 2024-03-05
Complete: false
aliases:
---
# Every closed subspace of the Cantor Space is a continuous image of Cantor Space
***
###### tags: #Topology 
***
>[!dsn]+ Theorem
>Let $(Y,\tau_{1})$ be a (non-empty) closed subspace of the Cantor Space $(G,\tau)$. Then there exists a continuous mapping of $(G,\tau)$ *onto* $(Y,\tau_{1})$.^[[[Sidney A. Morris - Topology without tears.pdf#page=248|Sidney A. Morris - "Topology without tears" p.248]]]

>[!proof]+
>Let $(G',\tau')$ be the set of all real numbers which can be written in the form $\sum_{i=1}^{\infty}\frac{a_{i}}{6^{i}}$, where each $a_{i}=0$ or $5$, with the subspace topology induced from $\mathbb{R}$. The space $(G',\tau')$ is called the *middle two-thirds Cantor Space*. Clearly $(G',\tau')$ is homeomorphic to the Cantor Space $(G,\tau)$.
>
>We can regard $(Y,\tau_{1})$ as a closed subspace of $(G',\tau')$ and seek a continuous mapping of $(G',\tau')$ onto $(Y,\tau_{1})$. Before proceeding, observe from the construction of  the middle two thirds Cantor space that if $g_{1}\in G'$ and $g_{2}\in G'$, then $\frac{g_{1}+g_{2}}{2}\notin G'$.
>
>The map $\psi:(G',\tau')\to(Y,\tau_{1})$ which we seek is defined as follows: for $g\in G'$, $\psi(g)$ is the unique element of $Y$ which is closest to $g$ in the euclidean metric on $\mathbb{R}$. However we have to prove that such a unique closest element exists.
>
>Fix $g\in G'$. Then the map $d_{g}:(Y,\tau_{1})\to\mathbb{R}$ given by $d_{g}(y)=|g-y|$ is continuous. As $(Y,\tau_{1})$ is compact, [[continuous image of compact set to a real line has least and greatest elements]] implies that $d_{g}(Y)$ has a least element. So there exists an element of $(Y,\tau_{1})$ which is closest to $g$. Suppose there are two such elements $y_{1}$ and $y_{2}$ in $Y$ which are equally close to $g$. Then $g=\frac{y_{1}+y_{2}}{2}$. But $y_{1}\in G'$ and $y_{2}\in G'$ and so, as observed above, $g=\frac{y_{1}+y_{2}}{2}\notin G'$, which is a contradiction. So there exists a unique element of $Y$ which is closest to $g$. Call this element $\psi(g)$.
>
>It is clear that the map $\psi:(G',\tau')\to(Y,\tau_{1})$ is surjective, since for each $y\in Y$, $\psi(y)=y$. To prove continuity of $\psi$, let $g\in G'$. Let $\varepsilon$ be any given positive real number. Then it suffices, by [[continuous maps between metric spaces#continuity using distance between limit points]], to find a $\delta>0$, such that if $x\in G'$ and $|g-x|<\delta$ then $|\psi(g)-\psi(x)|<\varepsilon$.
>
>Consider firstly the case when $g\in Y$, so $\psi(g)=g$. Put $\delta=\frac{\varepsilon}{2}$. Then for $x\in G'$ with $|g-x|<\delta$ we have
>$$\begin{align}|\psi(g)-\psi(x)|&=|g-\psi(x)|\\ &\le|x-\psi(x)|+|g-x|\\ &\le |x-g|+|g-x|,\text{ by definition of }\psi\text{ since }g\in Y\\ &=2|x-g|\\ &<2\delta\\&=\varepsilon,\text{ as required}\end{align}$$
>Now consider the case when $g\notin Y$, so $g\ne\psi(g)$.
>Without loss of generality, assume $\psi(g)<g$ and put $a=g-\psi(g)$. If the set $Y\cap[g,1]=\emptyset$, then $\psi(x)=\psi(g)$ for all $x\in\left(g-\frac{a}{2},g+\frac{a}{2}\right)$. Thus for $\delta<\frac{a}{2}$, we have $|\psi(x)-\psi(g)|=0<\varepsilon$, as required.
>If $Y\cap[g,1]\ne\emptyset$, then as $Y\cap[g,1]$ is compact it has a least element $y>g$. Indeed by the definition of $\psi$, if $b=y-g$, then $b>a$.
>Now put $\delta=\frac{b-a}{2}$.
>So if $x\in G'$ with $|g-x|<\delta$, then either $\psi(x)=\psi(g)$ or $\psi(x)=y$. Observe that
>$$|x-\psi(g)|\le|x-g|+|g-\psi(g)|<\delta+a=\frac{b-a}{2}+a=\frac{b}{2}+\frac{a}{2}$$
>while
>$$|x-y|\ge|g-y|-|g-x|\ge b-\frac{b-a}{2}=\frac{b}{2}+\frac{a}{2}$$
>So $\psi(x)=\psi(g)$.
>
>Thus $|\psi(x)-\psi(g)|=0<\varepsilon$, as required. Hence $\psi$ is continuous.

>[!example]+ 
>
***
#### Keywords
- [[Open and closed subsets]],
- [[Cantor space]],
- [[Continuous mapping]],
- [[Set]],
- [[Real line]],
- [[Integer Bases]],
- [[Subspace topology]],
- [[Homeomorphism]],
- [[Function(mapping)]],
- [[Compact subsets of a metric space]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]],
- [[Absolute value]],
- [[Continuous maps between metric spaces]],
- 
#### Possibly related
- 
***
#### Sources:
