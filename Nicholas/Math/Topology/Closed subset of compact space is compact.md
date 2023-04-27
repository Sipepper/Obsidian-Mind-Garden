# Closed subset of compact space is compact
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Every closed subset of a compact space is compact.^[Sidney A. Morris - "Topology without tears" p.181]

>[!proof]+
>Let $A$ be a closed subset of a compact space $(X,\tau)$. Let $U_{i}\in\tau$, $i\in I$, be any open covering of $A$. Then
>$$X\subseteq\left(\bigcup\limits_{i\in I}U_{i}\right)\cup(X\setminus A)$$
>that is, $U_{i}$, $i\in I$, together with the open set $X\setminus A$ is an open covering of $X$. Therefore there exists a finite subcovering $U_{i_{1}},U_{i_{2}},\dots,U_{i_{k}},X\setminus A$, as if $X\setminus A$ is not in the finite subcovering then we can include it and still have a finite subcovering of $X$.
>So 
>$$X\subseteq U_{i_{1}}\cup U_{i_{2}}\cup\dots\cup U_{i_{k}}\cup(X\setminus A)$$
>Therefore,
>$$A\subseteq U_{i_{1}}\cup U_{i_{2}}\cup\dots\cup U_{i_{k}}\cup(X\setminus A)$$
>which clearly implies
>$$A\subseteq U_{i_{1}}\cup U_{i_{2}}\cup\dots\cup U_{i_{k}}$$
>since $A\cap(X\setminus A)=\emptyset$. Hence $A$ has a finite subcovering and so is compact.

>[!example]+ 
>
***
#### Keywords
- [[Open and closed subsets]],
- [[Compact set]],
- [[Covering of a set]],
- [[Cardinality of a set]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: