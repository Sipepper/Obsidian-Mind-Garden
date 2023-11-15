---
Last time checked: 2023-11-03
Complete: true
aliases:
---
# Integer Bases
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Direct strict note
>Let $b\in\mathbb{Z}$, $b\ge2$. Then $\forall h\in\mathbb{Z}$, $h>0$, a number $h$ can be uniquely expressed in *base $b$* in the following form
>$$h=d_{k}b^{k}+d_{k-1}b^{k-1}+\ldots+d_{1}b+d_{0}$$
>where $0\le d_{i}<b$, $\forall i\in\{0,\dots,k\}$.
>
>Numbers $d_{k},\dots,d_{0}$ are said to be *integral coefficients (digits) of $h$ in base $10$*.^[Lectures at KAU - by Eugene Polulyakh]

>[!proof]+
>*Existence*
>It follows from [[Euclidean algorithm]] and can be proved by induction on $h$.
>When $h=1$, $h=d_{0}$ and $d_{0}=1$. Suppose that
>$$h=qb+d_{0}\quad\text{where}\quad0\le d_{0}<b$$
>Then $h\ge qb\ge 2q$, as $q\ge2$ from which $q<h$, so
>$$\begin{align}q&=d'_{k}b^{k}+\dots+d'_{0}\\ &\Rightarrow \\ h&=(d'_{k}b^{k}+\dots+d'_{0})b+d_{0}\\&= d'_{k}b^{k+1}+\dots+d'_{0}b+d_{0}\end{align}$$
>
>*Uniqueness*
>Also can be proven by induction and follows from uniqueness of [[division with remainder]].

>[!example]+ 
>$37$ can be expressed as
>$$37=1\cdot 32+0\cdot 16+0\cdot 8+1\cdot 4+0\cdot 2+1$$
***
#### Keywords
- [[Set of integers]],
- [[Mathematical induction]]
#### Possibly related
- 
***
#### Sources: