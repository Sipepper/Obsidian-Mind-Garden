---
Last time checked: 2024-01-27
Complete: false
aliases:
---
# Countably compact set
***
###### tags: #Topology  
***
>[!dsn]+ Definition
>A set $A$ is called *countably compact* if every countable subset of $A$ has a limit point in $A$.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page=28|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.10]]]

>[!example]+
>

#### Relation to compactness
>[!dsn]+ Proposition
>Every compact set is countably compact.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page=28|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.10]]]

>[!proof]+
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