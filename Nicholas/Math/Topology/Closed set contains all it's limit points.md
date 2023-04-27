# Closed set contains all it's limit points
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $A$ be a subset of a topological space $(X,\tau)$. Then $A$ is closed in $(X,\tau)$ if and only if $A$ contains all of its limit points.^[Sidney A. Morris - "Topology without tears" p.76]

>[!proof]
>Assume that $A$ is closed in $(X,\tau)$. Suppose that $p$ is a limit point of $A$ which belongs to $X\setminus A$. Then $X\setminus A$ is an open set containing the limit point $p$ of $A$. Therefore $X\setminus A$ contains an element of $A$. Thus we have a contradiction. Therefore every limit point of $A$ must belong to $A$.
>
>Conversely, assume that $A$ contains all of its limit points. For each $z\in X\setminus A$, our assumption implies that there exists an open set $U_{z}\ni z$ such that $U_{z}\cap A=\emptyset$; that is, $U_{z}\subseteq X\setminus A$. Therefore $X\setminus A=\bigcup_{z\in X\setminus A}U_{z}$. So $X\setminus A$ is a union of open sets and hence is open. Consequently its complement, $A$, is closed.

***
#### Keywords
- [[Topological space]],
- [[Open and closed subsets]],
- [[Limit point in topological space]],
- [[Set]],
#### Possibly related
- 
***
#### Sources: