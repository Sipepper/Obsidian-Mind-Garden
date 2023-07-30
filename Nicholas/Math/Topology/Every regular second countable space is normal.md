# Every regular second countable space is normal
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Every regular second-countable space $(X,\tau)$ is normal.^[Sidney A. Morris - "Topology without tears" p.284]

>[!proof]+
>Let $A$ and $B$ be disjoint closed subsets of $(X,\tau)$ and $B$ a countable basis for $\tau$. As $(X,\tau)$ is regular and $X\setminus B$ is an open set, for each $a\in A$ there exists a $V_{a}\in\mathcal{B}$ such that $\overline{V}_{a}\subseteq X\setminus B$.
>As $\mathcal{B}$ is countable we can list the members $\{V_{a}:a\in A\}$ so obtained by $V_{i}$, $i\in\mathbb{N}$; that is, $A\subseteq\bigcup\limits_{i=1}^{\infty}V_{i}$ and $\overline{V}_{i}\cap B=\emptyset$, for all $i\in\mathbb{N}$.
>Similarly we can find sets $U_{i}$ in $\mathcal{B}_{i}$, $i\in\mathbb{N}$, such that $B\subseteq\bigcup\limits_{i=1}^{\infty}U_{i}$ and $\overline{U}_{i}\cap A=\emptyset$, for all $i\in\mathbb{N}$.
>Now Define $U'_{1}=U_{1}\setminus\overline{V}_{1}$ and $V'_{1}=V_{1}\setminus\overline{U}_{1}$.
>So $U'_{1}\cap V'_{1}=\emptyset$, $U'_{1}\in\tau$, $V'_{1}\in\tau$, $U'_{1}\cap B=U_{1}\cap B$, and $V'_{1}\cap A=V_{1}\cap A$.
>Then we inductively define
>$$U'_{n}=U_{n}\setminus\bigcup\limits_{i=1}^{n}\overline{V}_{i}\quad\text{and}\quad V'_{n}=V_{n}\setminus\bigcup\limits_{i=1}^{n}\overline{U}_{i}$$
>So that $U'_{n}\in\tau$, $V'_{n}\in\tau$, $U'_{n}\cap B=U_{n}\cap B$, and $V'_{n}\cap A=A_{n}\cap A$.
>Now put $U=\bigcup\limits_{n=1}^{\infty}U'_{n}$ and $V=\bigcup\limits_{n=1}^{\infty}V'_{n}$.
>Then $U\cap V=\emptyset$, $U\in\tau$, $V\in\tau$, $A\subseteq V$, and $B\subseteq U$. Hence $(X,\tau)$ is a normal space.

>[!example]+ 
>
***
#### Keywords
- [[Regular and T3 space]],
- [[Second axiom of countability]],
- [[Normal space]],
- [[Open and closed subsets]],
- [[Cardinality of a set]],
- [[Topology basis]],
- [[Closure of a set]],
- [[Set]],
- [[Mathematical induction]]
#### Possibly related
- 
***
#### Sources: