---
Last time checked: 2024-02-21
Complete: false
aliases:
---
# Locally compact subgroup of the Hausdorff topological group is closed
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>Let $G$ be a Hausdorff topological group, and $H$ be a locally compact subgroup of $G$. Then $H$ is a closed subgroup of $G$.^[[[Alain M. Robert - A course in p-adic analysis.pdf#page=36 |Alain M. Robert - "A course in p-adic analysis" p.20]]] In particular this is the case if $H$ is discrete.^[[[Sidney A. Morris - Topology without tears.pdf#page=521|Sidney A. Morris - "Topology without tears" p.521]]]

>[!proof]+
>Let $K$ be a compact neighbourhood in $H$ of $e$. Then there exists a neighbourhood $U$ in $G$ of $e$ such that $U\cap H=K$. In particular, $U\cap H$ is closed in $G$. Let $V$ be a neighbourhood in $G$ of $e$ such that $V^{2}\subseteq U$.
>If $x\in\overline{H}$, then as $\overline{H}$ is a group ([[closure of certain subgroups in topological groups]]), $x^{-1}\in\overline{H}$. So there exists an element $y\in Vx^{-1}\cap H$. We will show that $yx\in H$. As $y\in H$, this will imply that $x\in H$ and hence $H$ is closed, as required.
>To show that $yx\in H$ we verify that $yx$ is a limit point of $U\cap H$. As $U\cap H$ is closed this will imply that $yx\in U\cap H$ and so, in particular, $yx\in H$.
>Let $O$ be an arbitrary neighbourhood of $yx$. Then $y^{-1}O$ is a neighbourhood of $x$, and so $y^{-1}O\cap xV$ is a neighbourhood of $x$. As $x\in\overline{H}$, there is an element $h\in(y^{-1}O\cap xV)\cap H$. So $yh\in O$. Also $yh\in(Vx^{-1}(xV))=V^{2}\subseteq U$, and $yh\in H$; that is, $yh\in O\cap(U\cap H)$. As $O$ is arbitrary, this says that $yx$ is a limit point of $U\cap H$, as required.

>[!example]+ 
>
***
#### Keywords
- [[Hausdorff space]],
- [[Topological group]],
- [[Locally compact space]],
- [[Set]],
- [[Open and closed subsets]],
- [[Discrete group]],
- [[Locally closed set]],
- [[Compact set]],
- [[Neighborhood in topological space]],
- [[Closure of a set]],
- [[Limit point in topological space]],
#### Possibly related
- [[Symmetric neighborhoods in topological groups]]
***
#### Sources: