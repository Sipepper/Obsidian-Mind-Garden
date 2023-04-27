# Tychonoff's theorem
***
###### tags: #Topology 
***
#### Finite case
>[!dsn]+ Direct strict note
>If $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ are compact spaces, then $\prod_{i=1}^{\infty}(X_{i},\tau_{i})$ is a compact space.^[Sidney A. Morris - "Topology without tears" p.203]

>[!proof]+
>Consider first the product of two compact spaces $(X,\tau_{1})$ and $(Y,\tau_{2})$. Let $U_{i}$, $i\in I$ be any open covering of $X\times Y$. Then for each $x\in X$ and $y\in Y$, there exists an $i\in I$ such that $(x,y)\in U_{i}$. So there is a basic open set $V(x,y)\times W(x,y)$, such that $V(x,y)\in\tau_{1}$, $W(x,y)\in\tau_{2}$ and $(x,y)\in V(x,y)\times W(x,y)\subseteq U_{i}$.
>As $(x,y)$ ranges over all points of $X\times Y$ we obtain an open covering $V(x,y)\times W(x,y)$, $x\in X$, $y\in Y$, of $X\times Y$ such that each $V(x,y)\times W(x,y)$ is a subset of some $U_{i}$, $i\in I$. Thus to prove $(X,\tau_{1})\times(Y,\tau_{2})$ is compact it suffices to find a finite subcovering of the open covering $V(x,y)\times W(x,y)$, $x\in X$, $y\in Y$.
>Now fix $x_{0}\in X$ and consider the subspace $\{x_{0}\}\times Y$ of $X\times Y$. As seen in [[Projection map in product spaces#8.2.8. О гомеоморфности проекции подпространству]] this subspace is homeomorphic to $(Y,\tau_{2})$ and so is compact. As $V(x_{0},y)\times W(x_{0},y)$, $y\in Y$, is an open covering of $\{x_{0}\}\times Y$ it has a finite subcovering:
>$$V(x_{0},y_{1})\times W(x_{0},y_{1}),V(x_{0},y_{2})\times W(x_{0},y_{2}),\dots,V(x_{0},y_{m})\times W(x_{0},y_{m})$$
>Put $V(x_{0})=V(x_{0},y_{1})\cap V(x_{0},y_{2})\cap\dots\cap V(x_{0},y_{m})$. Then we see that the set $V(x_{0})\times Y$ is contained in the union of a finite number of sets of the form $V(x_{0},y)\times W(x_{0},y)$, $y\in Y$.
>Thus to prove $X\times Y$ is compact it suffices to show that $X\times Y$ is contained in a finite union of sets of the form $V(x)\times Y$. As each $V(x)$ is an open set containing $x\in X$, the family $V(x)$, $x\in X$, is an open covering of the compact space $(X,\tau_{1})$. Therefore there exist $x_{1},x_{2},\dots,x_{k}$ such that $X\subseteq V(x_{1})\cup V(x_{2})\cup\dots\cup V(x_{k})$. Thus  $X\times Y\subseteq(V(x_{1})\times Y)\cup(V(x_{2})\times Y)\cup\dots\cup(V(x_{k})\times Y)$, as required. Hence $(X,\tau_{1})\times(Y,\tau_{2})$ is compact.
>The proof is completed by induction. Assume that the product of any $N$ compact spaces is compact. Consider the product $(X_{1},\tau_{1})\times(X_{2},\tau_{2})\times\dots\times(X_{N+1},\tau_{N+1})$ of compact spaces $(X_{i},\tau_{i})$, $i=1,\dots,N+1$. Then
>$$\begin{align}&(X_{1},\tau_{1})\times(X_{2},\tau_{2})\times\dots\times(X_{N+1},\tau_{N+1})\\\cong&[(X_{1},\tau_{1})\times\dots\times(X_{N},\tau_{N})]\times(X_{N+1},\tau_{N+1}) \end{align}$$
>By our inductive hypothesis $(X_{1},\tau_{1})\times\dots\times(X_{N},\tau_{N})$ is compact, so the right-hand side is the product of two compact spaces and thus is compact. Therefore the left-hand side is also compact. This completes the induction and the proof of the theorem.

>[!example]+
>The subspace $\mathbb{S}^{1}\times[0,1]$ of $\mathbb{R}^{3}$ is the product of two compact spaces and so is compact.
>
>>[!proof]+
>>

##### Converse of Tychonoff's theorem
>[!dsn]+ Direct strict note
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be topological spaces. If $\prod_{i=1}^{\infty}(X_{i},\tau_{i})$ is compact, then each $(X_{i},\tau_{i})$ is compact.^[Sidney A. Morris - "Topology without tears" p.204]

>[!proof]+
>

#### Arbitrary cardinality
>[!dsn]+ Direct strict note
>Let $\{(X_{i},\tau_{i}):i\in I\}$ be any family of topological spaces. Then $\prod_{i\in I}(X_{i},\tau_{i})$ is compact if and only if each $(X_{i},\tau_{i})$ is compact.^[Sidney A. Morris - "Topology without tears" p.273]

>[!proof]+
>We shall use [[Compactness by finite intersection property]] to show that $(X,\tau)=\prod_{i\in I}(X_{i},\tau_{i})$ is compact, if each $(X_{i},\tau_{i})$ is compact. Let $\mathcal{F}$ be any family of closed subsets of $X$ with the finite intersection property. We have to prove that $\bigcap_{F\in\mathcal{F}}F\ne\emptyset$.
>By [[Existence of maximal family of sets with finite intersection property]] there is a maximal family $\mathcal{H}$ of (not necessarily closed) subsets of $(X,\tau)$ that contains $\mathcal{F}$ and has the finite intersection property. We shall prove that $\bigcap_{H\in\mathcal{H}}\overline{H}\ne\emptyset$, from which follows the required result $\bigcap_{F\in\mathcal{F}}\ne\emptyset$, since each $F\in\mathcal{F}$ is closed.
>As $\mathcal{H}$ is maximal with the property that it contains $\mathcal{F}$ and has the finite intersection property, if $H_{1},H_{2},\dots,H_{n}\in\mathcal{H}$, for any $n\in\mathbb{N}$, then the set $H'=H_{1}\cap H_{2}\cap\dots\cap H_{n}\in\mathcal{H}$. Suppose this was not the case. Then the set $\mathcal{H}'=\mathcal{H}\cup\{H'\}$ would properly contain $\mathcal{H}$ and also have the property that it contains $\mathcal{F}$ and has the finite intersection property. This is a contradiction to $\mathcal{H}$ being maximal. So $\mathcal{H}=\mathcal{H}$ and $H'=H_{1}\cap H_{2}\cap\dots\cap H_{n}\in\mathcal{H}$.
>Let $S$ be any subset of $X$ that intersects non-trivially every member of $\mathcal{H}$. We claim that $\mathcal{H}\cup\{S\}$ has the finite intersection property. To see this let $H'_{1},H'_{2},\dots,H'_{m}$ be members of $\mathcal{H}$. We shall show that $S\cap H'_{1}\cap H'_{2}\cap\dots\cap H'_{m}\ne\emptyset$. By the previous paragraph, $H'_{1}\cap H'_{2}\cap\dots\cap H'_{m}\in\mathcal{H}$. So by assumption $S\cap\left(H'_{1}\cap H'_{2}\cap\dots\cap H'_{m}\right)\ne\emptyset$. Hence $\mathcal{H}\cup\{S\}$ has the finite intersection property and contains $\mathcal{F}$. Again using the fact that $\mathcal{H}$ is maximal with the property that it contains $\mathcal{F}$ and has the finite intersection property, we see that $S\in\mathcal{H}$.
>Fix $i\in I$ and let $p_{i}:\prod_{i\in I}(X_{i},\tau_{i})\to(X_{i},\tau_{i})$ be the projection mapping. Then the family $\{p_{i}(H):H\in\mathcal{H} \}$ has the finite intersection property. Therefore the family $\{\overline{p_{i}(H)}:H\in\mathcal{H}\}$ has the finite intersection property. As $(X_{i},\tau_{i})$ is compact, $\bigcap_{H\in\mathcal{H}}\overline{p(H)}\ne\emptyset$. So let $x_{i}\in\bigcap_{H\in\mathcal{H}}\overline{p_{i}(H)}$. Then for each $i\in I$, we can find a point $x_{i}\in\bigcap_{H\in\mathcal{H}}\overline{p_{i}(H)}$. Put $x=\prod_{i\in I}x_{i}\in X$.
>We shall prove that $x\in\bigcap_{H\in\mathcal{H}}\overline{H}$. Let $O$ be any open set containing $x$. Then $O$ contains a basic open set about $x$ of the form $\bigcap_{i\in J}p^{-1}_{i}(U_{i})$, where $U_{i}\in\tau_{i}$, $x_{i}\in U_{i}$ and $J$ is a finite subset of $I$. As $x_{i}\in\overline{p_{i}(H)}$, $U_{i}\cap p_{i}(H)\ne\emptyset$, for all $H\in\mathcal{H}$. Thus $p_{i}^{-1}(U_{i})\in\mathcal{H}$, for all $i\in J$. As $\mathcal{H}$ has the finite intersection property, $\bigcap_{i\in J}p_{i}^{-1}(U_{1})\cap H\ne\emptyset$, for all $H\in\mathcal{H}$. So $O\cap H\ne\emptyset$ for all $H\in\mathcal{H}$. Hence $x\in\bigcap_{H\in\mathcal{H}}\overline{H}$, as required.
>Conversely, if $\prod_{i\in I}(X_{i},\tau_{i})$ is compact, then by [[Compactness is preserved under surjective continuous mapping]] and [[Projection map in product spaces#10.1.5. Случай произвольной мощности]] each $(X_{i},\tau_{i})$ is compact.

>[!example]+ 
>
***
#### Keywords
- [[Compact set]],
- [[Product topology]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[Topology basis]],
- [[Homeomorphism]],
- [[Subspace topology]],
- [[Set]],
- [[Cardinality of a set]],
- [[Mathematical induction]],
- [[Sphere]],
- [[Euclidean space]],
- [[Topological space]],
- [[Finite intersection property]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]],
- [[Closure of a set]],
- [[Projection map in product spaces]]
#### Possibly related
- 
***
#### Sources: