# Dense subset
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $A$ be a subset of a topological space $(X,\tau)$. Then $A$ is said to be *dense* in $X$ or *everywhere dense* in $X$ if $\overline{A}=X$.^[Sidney A. Morris - "Topology without tears" p.78]

>[!example]+ 
>Let $(X,\tau)$ be a discrete space. Then every subset of $X$ is closed (since complement is open). Therefore the only dense subset of $X$ is $X$ itself, since each subset of $X$ is its own closure.
#### Density criterion
>[!dsn]+ Direct strict note
>Let $A$ be a subset of a topological space $(X,\tau)$. Then $A$ is dense in $X$ if and only if every non-empty open subset of $X$ intersects $A$ non-trivially (that is, if $U\in\tau$ and $U\ne\emptyset$ then $A\cap U\ne\emptyset$).^[Sidney A. Morris - "Topology without tears" p.79]

>[!proof]+
>Assume, firstly that every non-empty open set intersects $A$ non-trivially. If $A=X$, then clearly $A$ is dense in $X$. If $A\ne X$, let $x\in X\setminus A$. If $U\in\tau$ and $x\in U$ then $U\cap A\ne\emptyset$. So $x$ is a limit point of $A$. As $x$ is an arbitrary point in $X\setminus A$, every point of $X\setminus A$ is a limit point of $A$. So $A'\supseteq X\setminus A$ and then, by definition of [[Closure of a set]], $\overline{A}=A'\cup A=X$; that is, $A$ is dense in $X$.
>
>Conversely, assume $A$ is dense in $X$. Let $U$ be any non-empty open subset of $X$. Suppose $U\cap A=\emptyset$. Then if $x\in U$, $x\notin A$ and $x$ is *not* a limit point of $A$, since $U$ is an open set containing $x$ which does not contain any element of $A$. This is a contradiction since, as $A$ is dense in $X$, every element of $X\setminus A$ is a limit point of $A$. So our supposition is false and $U\cap A\ne\emptyset$, as required.
***
#### Keywords
- [[Set]],
- [[Topological space]],
- [[Closure of a set]],
- [[Discrete topology]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Limit point in topological space]]
#### Possibly related
- 
***
#### Sources: