# Crystallographic group acts discretely on real plane
***
###### tags: #Geometry 
***
>[!dsn]+ Direct strict note
>Let $G$ be a crystallographic group and $E$ is a real(euclidean) plane. Then $G$ acts discretely on $E$.^[Marcel Berger - "Geometry 1" p.15]

>This means that, for any $a\in E$, the orbit $G(a)$ is discrete in $E$, that is it consists solely of isolated points. In particular, the intersection of any orbit with a compact set is finite, since a discrete compact set is finite.

>[!proof]+
>First note that every compact set of $E$ contains only a finite number of distinct tiles $g(P)$. This comes from second axiom of [[axioms for tilings and crystallographic group]] and the fact that as $\mathbb{R}^{2}$ is a metric space, so by [[Equivalence of compactness and sequentially compactness in metric spaces]] every sequence of points has a convergent subsequence(why?).
>Next, observe that the stabilizer of a tile $P'=g(P)$, defined as 
>$$G_{P'}=\{g\in G:g(P')=P'\}$$
>is always finite. In fact by [[isometries which preserve some compact subset lies in isometries which preserve one point]] there exists $a'\in E$ such that 
>$$G_{P'}\subset G_{a'}=\{g\in G:g(a')=a'\}$$
>Choose another tile $P''$ such that the associated point $a''$ is different from $a'$. Since only the identity leaves both $a''$ and $a'$ fixed, the cardinality of $G_{P'}$ is equal to the number of tiles $g(P'')$, for $g\in G_{P'}$. Since these tiles are distinct and contained in a circle of fixed radius, there are only finitely many of them.
>![[Pasted image 20230802135016.png]]
>
>Since $G$ is a group of isometries, it is enough to show that $a$ is isolated in $G(a)$. Take an arbitrary $\eta>0$. The number of points of $G(a)\cap B(a,\eta)$ lying in any given tile is finite, by proven before, and the number of tiles intersecting $B(a,\eta)$ is also finite, since they are all contained in the compact disc $B(a,\eta+\delta)$, where $\delta$ is the diameneter of a tile. Thus $G(a)\cap B(a,\eta)$ is a finite set, and we can find $\varepsilon$ such that $G(a)\cap B(a,\varepsilon)=\{a\}$.

>[!example]+ 
>
***
#### Keywords
- [[Axioms for tilings and crystallographic group]],
- [[Euclidean space]],
- [[Group acting on a set]],
- [[Orbit in homogeneous space]],
- [[Discrete topology]],
- [[Isolated point]],
- [[Compact set]],
- [[Cardinality of a set]],
- [[Metric space]],
- [[Convergence in metric spaces]],
- [[Sequence]],
- [[Stabilizer subgroup]],
- [[Group of isometries]],
- [[Open ball in metric space]],
- [[Set diameter]]
#### Possibly related
- 
***
#### Sources: