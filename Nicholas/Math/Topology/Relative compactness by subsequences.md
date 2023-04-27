# Relative compactness by subsequences
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(U,d)$ be a metric space. Then $A\subset U$ is a relatively compact if and only if from which sequence in $A$ we can extract converging subsequence.^[Fabio Silva Botelho - "Functional analysis and Applied Optimization in Banach Spaces" p.18]

>[!proof]
>Suppose that $A$ is relatively compact. Then it's closure $\overline{A}$ is compact, and sequentially compact by [[Equivalence of compactness and sequentially compactness]].
>
>Then from every sequence in $\overline{A}$ we can extract a converging subsequence. In particular for any sequence from $A\subset\overline{A}$, we can extract some subsequence converging to some element in $\overline{A}$.
>
>Conversely, suppose that for every sequence in $A$, we can extract a convergent subsequence. Then it's sufficient to prove that $\overline{A}$ is  sequentially compact. Let $\set{v_{n}}$ be a sequence in $\overline{A}$. Because $A$ is dense in $\overline{A}$, then there exists some sequence $\set{u_{n}}\subset A$ such that
>$$d(u_{n},v_{n})<\frac{1}{n}$$
>By supposition, we can extract some convergent subsequence $\set{u_{n_{k}}}$ and $u_{0}\in\overline{A}$ such that
>$$u_{n_{k}}\to u_{0},\quad k\to\infty$$
>And thus $\overline{A}$ is a sequentially compact, and therefore compact.

***
#### Keywords
- [[Metric space]],
- [[Relatively compact set]],
- [[Sequence]],
- [[Convergence in metric spaces]],
- [[Closure of a set]],
- [[Compact subsets of a metric space]],
- [[Sequentially compact set]],
- [[Compact set]]
#### Possibly related
- 
***
#### Sources: