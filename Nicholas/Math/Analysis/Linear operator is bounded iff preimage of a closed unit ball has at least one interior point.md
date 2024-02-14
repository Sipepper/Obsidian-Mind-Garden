---
Last time checked: 2024-02-01
Complete: false
aliases:
---
# Linear operator is bounded iff preimage of a closed unit ball has at least one interior point
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Proposition
>Let $U$ and $V$ be Banach spaces and let $A:U\to V$ is a linear operator. Then $A$ is bounded if and only if the preimage $A^{-1}(\{v\in V:\|v\|_{V}\le1\})$ of a closed unit ball in $V$ has at least one interior point.^[Fabio Silvia Botelho "Functional Analysis and Applied Optimization in Banach Spaces" p.24-25]

>[!proof]+
>Suppose that there exist an element $u_{0}\in U$ in the interior of $C=A^{-1}(\{v\in V:\|v\|_{V}\le1\})$. Therefore exist $r>0$ such that
>$$B_{r}(u_{0})=\{u\in U:\|u-u_{0}\|_{U}<r\}\subset C$$
>Fix $u\in U$ such that $\|u\|_{U}<r$. Then we get that
>$$\|A(u)\|_{V}\le\|A(u+u_{0})\|_{V}+\|A(u_{0})\|_{V}$$
>Note that as $\|(u+u_{0})-u_{0}\|_{U}<r$ is such that $u+u_{0}\in B_{r}(u_{0})\subset C$ and thus $\|A(u+u_{0})\|_{V}\le1$.
>Therefore
>$$\|A(u)\|_{V}\le1+\|A(u_{0})\|_{V}\quad(*)$$
>for all $u\in U$ such that $\|u\|_{U}<r$. Fix an arbitrary element $u\in U$ such that $u\ne\theta$.
>Let $w=\frac{u}{\|u\|_{U}}\frac{r}{2}$. By inequality $(*)$ we obtain
>$$\|A(w)\|_{V}=\frac{\|A(u)\|_{V}}{\|u\|_{U}}\frac{r}{2}\le1+\|A(u_{0})\|_{V}$$
>and thus
>$$\|A(u)\|_{V}\le\left(1+\|A(u_{0})\|_{V} \right)\|u\|_{U}\frac{2}{r}$$
>As $u\in U$ was chosen arbitrarily, $A$ is a bounded operator.
>
>Conversely, suppose that $A$ is bounded. Then
>$$\|A(u)\|_{V}\le K\|u\|_{U}\quad\forall u\in U$$
>for some $K>0$. In particular 
>$$D=\left\{u\in U:\|u\|_{U}\le\frac{1}{K} \right\}\subset C$$
>which completes the proof.

>[!example]+ 
>
***
#### Keywords
- [[Banach space]],
- [[Operator]],
- [[Linear map]],
- [[Bounded operator]],
- [[Preimage]],
- [[Open ball in metric space]],
- [[Open and closed subsets]],
- [[Normed space]],
- [[Interior, Exterior and boundary of a set in topological space]],
#### Possibly related
- 
***
#### Sources: