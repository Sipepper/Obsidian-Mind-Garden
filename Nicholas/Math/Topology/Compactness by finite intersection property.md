# Compactness by finite intersection property
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,\tau)$ be a topological space. Then $(X,\tau)$ is compact if and only if every family $\mathcal{F}$ of closed subsets of $X$ with the finite intersection property satisfies
>$$\bigcap_{F\in\mathcal{F}}F\ne\emptyset$$
>.^[Sidney A. Morris - "Topology without tears" p.272]

>[!proof]
>Assume that every family $\mathcal{F}$ of closed subsets of $X$ with the finite intersection property satisfies $\bigcap_{F\in\mathcal{F}}F\ne\emptyset$. Let $\mathcal{U}$ be any open covering of $X$. Put $\mathcal{F}$ equal to the family of complements of members of $\mathcal{U}$. So each $F\in\mathcal{F}$ is closed in $(X,\tau)$. As $\mathcal{U}$ is an open covering of $X$, $\bigcap_{F\in\mathcal{F}}F=\emptyset$. By our assumption, then, $\mathcal{F}$ does not have the finite intersection property. So for some $F_{1},F_{2},\dots, F_{n}$ in $\mathcal{F}$, $F_{1}\cap F_{2}\cap\dots\cap F_{n}=\emptyset$. Thus $U_{1}\cap U_{2}\cup\dots\cup U_{n}=X$, where $U_{i}=X\setminus F_{i}$, $i=1,\dots,n$. So $\mathcal{U}$ has a finite subcovering. Hence $(X,\tau)$ is compact. 
>The converse statement is proved similarly.

>[!example] 
>
***
#### Keywords
- [[Finite intersection property]],
- [[Topological space]],
- [[Compact set]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[Set]],
- [[Cardinality of a set]]
#### Possibly related
- 
***
#### Sources: