# Countably compact set
***
###### tags: #Topology  
***
>[!dsn] Direct strict note
>A set $A$ is called *countably compact* if every countable subset of $A$ has a limit point in $A$.^[Botelho - Functional analysis and Applied Optimization in Banach Spaces с.10]

>[!example]
>

#### Relation to compactness
>[!dsn] 
>Every compact set is countably compact.

>[!proof]
>Let $B$ be a countable subset of a set $A$, suppose that $B$ has no limit points. 
>Choose a sequence $\{x_{1},x_{2},\dots\}\subset B$ and denote it by $F$. Because $B$ has no limits points, $F$ as well has no limit point. Therefore, for any $n\in\mathbb{N}$ there exists and open set $O_{n}$ such that $O_{n}\cap F=\{x_{n}\}$. Also, for all $x\in A\setminus F$, exists $O_{x}$ such that $x\in O_{x}$ and $O_{x}\cap F=\emptyset$. Thus $\set{O_{x},x\in A\setminus F}$ is an open covering of $A$ without finite subcover which contradicts compactness of $A$.
***
#### Keywords
- [[Set]],
- [[Cardinality of a set]],
- [[Limit point in topological space]],
- [[Compact set]],
- [[Topological space]],
- [[Sequence]],
- [[Open and closed subsets]],
- [[Covering of a set]],
#### Possibly related
- 
***
#### Sources: