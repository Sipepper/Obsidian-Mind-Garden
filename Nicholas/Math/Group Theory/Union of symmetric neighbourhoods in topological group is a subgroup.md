---
Last time checked: 2024-02-25
Complete: false
aliases:
---
# Union of symmetric neighbourhoods in topological group is a subgroup
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>Let $U$ be a symmetric neighbourhood of $e$ in a topological group $G$. Then $H=\bigcup_{n=1}^{\infty}U^{n}$ is an open (and closed) subgroup of $G$.^[[[Sidney A. Morris - Topology without tears.pdf#page=521|Sidney A. Morris - "Topology without tears" p.521]]]

>[!proof]+
>Clearly $H$ is a subgroup of $G$. Because if $a,b\in\bigcup_{n=1}^{\infty}U^{n}$, then $a\in U^{k}$ and $b^{-1}\in U^{m}$ therefore $ab^{-1}\in U^{k+m}\subseteq\bigcup_{n=1}^{\infty}U^{n}$.
>Let $h\in H$. Then $h\in U^{n}$, for some $n$. So $h\in hU\subseteq U^{n+1}\subseteq H$; that is, $H$ contains the neighbourhood $hU$ of $h$. As $h$ was an arbitrary element of $H$, $H$ is open in $G$. It is also closed in $G$, by [[any open subgroup of topological group is also closed]]. 

>[!example]+ 
>
***
#### Keywords
- [[Symmetric neighborhoods in topological groups]],
- [[Topological group]],
- [[Open and closed subsets]],
- [[Group#Subgroup]],
- [[Neighborhood in topological space]]
#### Possibly related
- 
***
#### Sources: