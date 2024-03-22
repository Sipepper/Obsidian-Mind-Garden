---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Normality criterion or Urysohn lemma
>[!dsn]+ Proposition
>Let $(X,\tau)$ be a topological space. Then $(X,\tau)$ is normal if and only if for each pair of disjoint closed sets $A$ and $B$ in $(X,\tau)$ there exists a continuous function $f:(X,\tau)\to[0,1]$ such that $f(a)=0$ for all $a\in A$, and $f(b)=1$ for all $b\in B$.^[[[Sidney A. Morris - Topology without tears.pdf#page=278|Sidney A. Morris - "Topology without tears" p.278]]]

>[!proof]+
>Assume that for each $A$ and $B$ an $f$ with the property stated above exists. Then $U=f^{-1}\left([0,\frac{1}{2}) \right)$ and $V=f^{-1}\left((\frac{1}{2},1] \right)$ are open in $(X,\tau)$ and satisfy $A\subseteq U$, $B\subseteq V$, and $A\cap B=\emptyset$. Hence $(X,\tau)$ is normal.
>
>Conversely, assume $(X,\tau)$ is normal. We shall construct a family $\{U_{i}:i\in D\}$ of open subsets of $X$, where the set $D$ is given by $D=\{\frac{k}{2^{n}}:k=1,2,\dots,2^{n},n\in\mathbb{N}\}$.
>So $D$ is a set of dyadic rational numbers, such that $A\subseteq U_{i}$, $U_{i}\cap B\ne\emptyset$, and $d_{1}\le d_{2}$ implies $U_{d_{1}}\subseteq U_{d_{2}}$. As $(X,\tau)$ is normal, for any pair $A,B$ of disjoint closed sets, there exist disjoint open sets $U_{\frac{1}{2}}$ and $V_{\frac{1}{2}}$ such that $A\subseteq U_{\frac{1}{2}}$ and $B\subseteq V_{\frac{1}{2}}$. So we have $A\subseteq U_{\frac{1}{2}}\subseteq V_{\frac{1}{2}}^{c}\subseteq B^{c}$ where the superscript $c$ denote complements in $X$.
>
>Now consider the disjoint closed sets $A$ and $U_{\frac{1}{2}}^{c}$. Again, by normality, there exist disjoint open sets $U_{\frac{1}{4}}$ and $V_{\frac{1}{4}}$ such that $A\subseteq U_{\frac{1}{4}}$ and $U_{\frac{1}{2}}^{c}\subseteq V_{\frac{1}{4}}$. Also as $V_{\frac{1}{2}}^{c}$ and $B$ are disjoint closed sets there exists disjoint open sets $U_{\frac{3}{4}}$ and $V_{\frac{3}{4}}$ such that $V_{\frac{1}{2}}^{c}\subseteq U_{\frac{3}{4}}$ and $B\subseteq V_{\frac{3}{4}}$. So we have
>$$A\subseteq U_{\frac{1}{4}}\subseteq V_{\frac{1}{4}}^{c}\subseteq U_{\frac{1}{2}}\subseteq V_{\frac{1}{2}}^{c}\subseteq U_{\frac{3}{4}}\subseteq V_{\frac{3}{4}}^{c}\subseteq B^{c}$$
>Continuing by induction we obtain open sets $U_{d}$ and $V_{d}$ for each $d\in D$, such that
>$$A\subseteq U_{2^{-n}}\subseteq V_{2^{-n}}^{c}\subseteq U_{2\cdot2^{-n}}\subseteq V_{2\cdot2^{-n}}^{c}\subseteq\dots\subseteq U_{(2^{n-1})2^{-n}}\subseteq V_{(2^{n-1})2^{-n}}^{c}\subseteq B^{c}$$
>So we have, in particular, that for $d_{1}\le d_{2}$ in $D$, $U_{d_{1}}\subseteq U_{d_{2}}$.
>Now we define $f:(X,\tau)\to[0,1]$ by 
>$$f(x)=\begin{cases}\inf\{d:x\in U_{d}\}& x\in\bigcup\limits_{d\in D}U_{d}\\ 1,&x\notin\bigcup\limits_{d\in D}U_{d} \end{cases}$$
>Observe finally that since $A\subseteq U_{d}$, for all $d\in D$, $f(a)=0$ for all $a\in A$. Also if $b\in B$, then $b\notin\bigcup_{d\in D}U_{d}$ and so $f(b)=1$. So we have to show only that $f$ is continuous.
>
>Let $f(x)=y$, where $y\ne0,1$ and set $W=(y-\varepsilon,y+\varepsilon)$, for some $\varepsilon>0$ (with $0<y-\varepsilon<y+\varepsilon<1$). As $D$ is dense in $[0,1]$, we can choose $d_{0}$ and $d_{1}$ such that $y-\varepsilon<d_{0}<y<d_{1}<y_{0}+\varepsilon$. Then, by the definition of $f$, $x\in U=U_{d_{1}}\setminus\overline{U}_{d_{0}}$ and the open set $U$ satisfies $f(u)\subseteq W$. If $y=1$ then we put $W=(y-\varepsilon,1]$, choose $d_{0}$ such that $y-\varepsilon<d_{0}<1$, and set $U=X\setminus\overline{U}_{d_{0}}$. Again $f(U)\subseteq W$. Finally, if $y=0$ then put $W=[0,y+\varepsilon)$, choose $d_{1}$ such that $0<d_{1}<Y+\varepsilon$ and set $U=U_{d_{1}}$ to again obtain $f(U)\subseteq W$. Hence $f$ is continuous.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Normal space]],
- [[Open and closed subsets]],
- [[Set]],
- [[Continuous mapping]],
- [[Preimage]],
- [[p-adic fraction]],
- [[Mathematical induction]],
- [[Supremum and infinum]],
- [[Interval]],
- [[Closure of a set]],
- [[Dense subset]]
#### Possibly related
- 
***
#### Sources: