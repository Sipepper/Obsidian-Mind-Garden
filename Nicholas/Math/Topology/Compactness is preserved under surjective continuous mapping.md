# Compactness is preserved under surjective continuous mapping
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $f:(X,\tau)\to(Y,\tau_{1})$ be a continuous surjective map. If $(X,\tau)$ is compact, then $(Y,\tau_{1})$ is compact.^[Sidney A. Morris - "Topology without tears" p.180]

>[!proof]+
>Let $O_{i}$, $i\in I$, be any open covering of $Y$; that is $Y\subseteq\bigcup_{i\in I}O_{i}$.
>Then $f^{-1}(Y)\subseteq f^{-1}(\bigcup_{i\in I}O_{i})$; that is $X\subseteq\bigcup_{i\in I}f^{-1}(O_{i})$.
>So $f^{-1}(O_{i})$, $i\in I$, is an open covering of $X$.
>As $X$ is compact, there exist $i_{1},i_{2},\dots,i_{n}$ in $I$ such that
>$$X\subseteq f^{-1}(O_{i_{1}})\cup f^{-1}(O_{i_{2}})\cup\dots\cup f^{-1}(O_{i_{n}})$$
>So
>$$\begin{align}Y&=f(X)\\ &\subseteq f\left(f^{-1}(O_{i_{1}})\cup f^{-1}(O_{i_{2}})\cup\dots\cup f^{-1}(O_{i_{n}})\right)\\ &=f(f^{-1}(O_{i_{1}}))\cup f(f^{-1}(O_{i_{2}}))\cup\dots\cup f(f^{-1}(O_{i_{n}}))\\ &= O_{i_{1}}\cup O_{i_{2}}\cup\dots\cup O_{i_{n}} \end{align}$$
>since $f$ is surjective.
>
>So we have $Y\subseteq O_{i_{1}}\cup O_{i_{2}}\cup\dots\cup O_{i_{n}}$; that is, $Y$ is covered by a finite number of $O_{i}$.
>Hence $Y$ is compact.

#### Compactness is a topological property
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ and $(Y,\tau)$ be homeomorphic topological spaces. If $(X,\tau)$ is compact, then $(Y,\tau_{1})$ is compact.^[Sidney A. Morris - "Topology without tears" p.180]

>That is, compactness is a topological property.

>[!example]+ 
>

#### Closed interval is compact
>[!dsn]+ Direct strict note
>For $a$ and $b$ in $\mathbb{R}$ with $a<b$, $[a,b]$ is compact while $(a,b)$ is not compact.^[Sidney A. Morris - "Topology without tears" p.181]

>[!proof]+
>The space $[a,b]$ is homeomorphic to the compact space $[0,1]$ and so, by  [[Compactness is preserved under surjective continuous mapping]], is compact.
>
>The space $(a,b)$ is homeomorphic to $(0,\infty)$. If $(a,b)$ were compact, then $(0,\infty)$ would be compact, but $(0,\infty)$ is not compact.
***
#### Keywords
- [[Continuous mapping]],
- [[Function(mapping)]],
- [[Compact set]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[Preimage]],
- [[Cardinality of a set]],
- [[Homeomorphism]],
- [[Topological space]],
- [[Interval]],
- [[Real line]],
- [[Compact subset in euclidean topology is bounded]]
#### Possibly related
- 
***
#### Sources: