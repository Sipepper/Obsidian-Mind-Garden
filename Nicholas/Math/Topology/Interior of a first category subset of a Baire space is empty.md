---
Last time checked: 2024-03-10
Complete: false
aliases:
---
# Interior of a first category subset of a Baire space is empty
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>If $Y$ is a first category subset of a Baire space $(X,\tau)$, then the interior of $Y$ is empty.^[[[Sidney A. Morris - Topology without tears.pdf#page=167|Sidney A. Morris - "Topology without tears" p.167]]]

>[!proof]+
>As $Y$ is first category, $Y=\bigcup\limits_{n=1}^{\infty}Y_{n}$, where each $Y_{n}$, $n\in\mathbb{N}$, is nowhere dense.
>Let $U\in\tau$ be such that $U\subseteq Y$. Then $U\subseteq\bigcup\limits_{n=1}^{\infty}Y_{n}\subseteq\bigcup\limits_{n=1}^{\infty}\overline{Y_{n}}$.
>So $X\setminus U\supseteq\bigcap\limits_{n=1}^{\infty}\left(X\setminus\overline{Y_{n}}\right)$, and each of the sets $X\setminus\overline{Y_{n}}$ is open and dense in $(X,\tau)$. As $(X,\tau)$ is a Baire space, $\bigcap\limits_{n=1}^{\infty}\left(X\setminus\overline{Y_{n}} \right)$ is dense in $(X,\tau)$. So the closed set $X\setminus U$ is dense in $(X,\tau)$. This implies $X\setminus U=X$. Hence $U=\emptyset$. This completes the proof.

>[!example]+ 
>
***
#### Keywords
- [[First and second category subsets of topological space]],
- [[Baire space]],
- [[Interior, Exterior and boundary of a set in topological space]],
- [[Nowhere dense set]],
- [[Closure of a set]],
- [[Set]],
- [[Open and closed subsets]],
- [[Dense subset]]
#### Possibly related
- 
***
#### Sources: