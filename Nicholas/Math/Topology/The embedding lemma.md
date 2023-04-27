# The embedding lemma
***
###### tags: #Topology 
***
#### Countable case
>[!dsn]+ Direct strict note
>Let $(Y_{i},\tau_{i})$, $i\in\mathbb{N}$, be a countably infinite family of topological spaces and for each $i$, let $f_{i}$ be a mapping of a topological space $(X,\tau)$ into $(Y_{i},\tau_{i})$. Further, let $e:(X,\tau)\to\prod_{i=1}^{\infty}(Y_{i},\tau_{i})$ be the *evaluation map*; that is, $e(x)=\prod_{i=1}^{\infty}f_{i}(x)$, for all $x\in X$. Then $e$ is a homeomorphism of $(X,\tau)$ onto the space $(e(X),\tau')$, where $\tau'$ is the subspace topology on $e(X)$, if
>1. each $f_{i}$ is continuous
>2. the family $\{f_{i}:i\in\mathbb{N}\}$ *separates points* of $X$; that is, if $x_{1}$ and $x_{2}$ are in $X$ with $x_{1}\ne x_{2}$, then for some $i$, $f_{i}(x_{1})\ne f_{i}(x_{2})$
>3. the family $\{f_{i}:i\in\mathbb{N}\}$ *separates points and closed sets*; that is, for $x\in X$ and $A$ any closed subset of $(X,\tau)$ not containing $x$, $f_{i}(x)\notin\overline{f_{i}(A)}$, for some $i$.^[Sidney A. Morris - "Topology without tears" p.238]

>[!proof]+
>That the mapping $e:(X,\tau)\to(e(X),\tau')$ is onto is obvious, while condition (2) clearly implies that it is one-to-one (injective).
>As $p_{i}\circ e=f_{i}$ is a continuous mapping of $(X,\tau)$ into $(Y_{i},\tau_{i})$, for each $i$, [[Continuity criterion of maps into product of topological spaces]] implies that the mapping $e:(X,\tau)\to\prod_{i=1}^{\infty}(Y_{i},\tau_{i})$ is continuous. Hence $e:(X,\tau)\to(e(X),\tau')$ is continuous by [[Restriction of continuous mapping of a subspace is continuous]].
>To prove that $e:(X,\tau)\to(e(X),\tau')$ is an open mapping. It suffices to verify that for each $U\in\tau$ and $x\in U$, there exists a set $W\in\tau'$ such that $e(x)\in W\subseteq e(U)$. As the family $f_{i}$, $i\in\mathbb{N}$, separates points and closed sets, there exists a $j\in\mathbb{N}$ such that $f_{j}(x)\notin\overline{f_{j}(X\setminus U)}$. Put
>$$W=(Y_{1}\times Y_{2}\times\dots\times Y_{j-1}\times\left(Y_{j}\setminus\overline{f_{j}(X\setminus U)}\right)\times Y_{j+1}\times Y_{j+2}\times\dots)\cap e(X)$$
>Then clearly $e(x)\in W$ and $W\in\tau'$. It remains to show that $W\subseteq e(U)$. So let $e(t)\in W$. Then
>$$\begin{align}&f_{j}(t)\in Y_{j}\setminus\overline{f_{j}(X\setminus U)}\\ \Rightarrow\quad&f_{j}(t)\notin\overline{f_{j}(X\setminus U)}\\ \Rightarrow\quad& f_{j}(t)\notin f_{j}(X\setminus U)\\ \Rightarrow\quad& t\notin X\setminus U\\ \Rightarrow\quad& t\in U \end{align}$$
>So $e(t)\in e(U)$ and hence $W\subseteq e(U)$. Therefore $e$ is a homeomorphism.

>[!example]+
>

#### Arbitrary cardinality case
>[!dsn]+ Direct strict note
>Let $I$ be an index set and $\{(Y_{i},\tau_{i}):i\in I\}$ a family of topological spaces and for each $i\in I$, let $f_{i}$ be a mapping of a topological space $(X,\tau)$ into $(Y_{i},\tau_{i})$. Further let $e:(X,\tau)\to\prod_{i\in I}(Y_{i},\tau_{i})$ be the *evaluation map*; that is, $e(x)=\prod_{i\in I}f_{i}(x)$, for all $x\in X$. Then $e$ is a homeomorphism of $(X,\tau)$ onto the space $(e(X),\tau')$, where $\tau'$ is the subspace topology on $e(X)$ if
>1. each $f_{i}$ is continuous
>2. the family $\{f_{i}:i\in I\}$ *separates points* of $X$; that is, if $x_{1}$ and $x_{2}$ are in $X$ with $x_{1}\ne x_{2}$, then for some $i\in I$, $f_{i}(x_{1})\ne f_{1}(x_{2})$
>3. the family $\{f_{i}:i\in I\}$ separates points and closed sets; that is, for $x\in X$ and $A$ any closed subset of $(X,\tau)$ not containing $x$, $f_{i}(x)\notin\overline{f_{i}(A)}$, for some $i\in I$.^[Sidney A. Morris - "Topology without tears" p.262]

>[!proof]+
>

>[!example]+ 
>
***
#### Keywords
- [[Cardinality of a set]],
- [[Topological space]],
- [[Function(mapping)]],
- [[Product topology]],
- [[Homeomorphism]],
- [[Subspace topology]],
- [[Continuous mapping]],
- [[Open and closed subsets]],
- [[Projection map in product spaces]],
- [[Open and closed mappings]],
- [[Closure of a set]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: