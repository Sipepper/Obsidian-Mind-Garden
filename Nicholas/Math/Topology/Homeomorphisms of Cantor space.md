---
Last time checked: 2024-03-07
Complete: true
aliases:
---
# Homeomorphisms of Cantor space
***
###### tags: #Topology 
***
#### Product of discrete finite spaces
>[!dsn]+ Proposition
>Let $(G,\tau)$ be a Cantor space and $\left(\prod_{i=1}^{\infty}A_{i},\tau' \right)$ be a product of discrete spaces $\{0,2\}$. Then mapping $f:(G,\tau)\to\left(\prod_{i=1}^{\infty}A_{i},\tau'\right)$ given by
>$$f\left(\sum\limits_{n=1}^{\infty}\frac{a_{n}}{3^{n}}\right)=(a_{1},a_{2},\dots,a_{n},\dots)$$
>is a homeomorphism.^[[[Sidney A. Morris - Topology without tears.pdf#page=228|Sidney A. Morris - "Topology without tears" p.228]]]

>[!proof]+
>By definition of [[Cantor space]] we know that such mapping is a bijection. As $(G,\tau)$ is compact and $\left(\prod_{i=1}^{\infty}A_{i},\tau'\right)$ is a Hausdorff space, then $f$ is a homeomorphism if it is continuous by [[Continuous bijection between compact and Hausdorff spaces is a homeomorphism]].
>To prove continuity of $f$ is sufficient to show that for any basic open set $U=U_{1}\times U_{2}\times\dots\times U_{N}\times A_{N+1}\times A_{N+2}\times\dots$ and any element $a=(a_{1},a_{2},\dots,a_{n},\dots)\in U$ exist an open set $W\ni\sum_{n=1}^{\infty}\frac{a_{n}}{3^{n}}$ such that $F(W)\subseteq U$.
>
>Consider the following open interval
>$$\left(\sum\limits_{n=1}^{\infty}\frac{a_{n}}{3^{n}}-\frac{1}{3^{N+2}},\sum\limits_{n=1}^{\infty}\frac{a_{n}}{3^{n}}+\frac{1}{3^{N+2}}\right)$$
>and let $W$ be the intersection of such interval with $G$. Then $W$ be open in $(G,\tau)$ and if $x=\sum_{n=1}^{\infty}\frac{x_{n}}{3^{n}}\in W$, then $x_{i}=a_{i}$, where $i=1,2,\dots,N$.
>Therefore
>$$f(x)\in U_{1}\times U_{2}\times\dots\times U_{N}\times A_{N+1}\times A_{N+2}\times\dots$$
>and thus $f(W)\subseteq U$ as required.

#### Cantor space is homeomorhic to a countable product of cantor spaces
>[!dsn]+ Proposition
>Let $(G_{i},\tau_{i})$, $i\in\mathbb{N}$ be a countable family of topological spaces, every of which homeomorphic to a Cantor Space $(G,\tau)$. Then
>$$(G,\tau)\cong\prod\limits_{i=1}^{n}(G_{i},\tau_{i})\cong\prod\limits_{i=1}^{\infty}(G_{i},\tau_{i})\quad\forall n\in\mathbb{N}$$
>.^[[[Sidney A. Morris - Topology without tears.pdf#page=229|Sidney A. Morris - "Topology without tears" p.229]]]

>[!proof]+
>Firstly we verify that $(G,\tau)\cong(G_{1},\tau_{1})\times(G_{2},\tau_{2})$, which is equivalent, by [[Homeomorphisms of Cantor space#Product of discrete finite spaces|Cantor space is homeomorphic to a countable product of dinite discrete spaces]], to showing that
>$$\prod\limits_{i=1}^{\infty}(A_{i},\tau_{i})\cong\prod\limits_{i=1}^{\infty}(A_{i},\tau_{i})\times\prod\limits_{i=1}^{\infty}(A_{i},\tau_{i})$$
>where each $(A_{i},\tau_{i})$ is the set $\{0,2\}$ with the discrete topology.
>Now we define a function $\theta$ from the set $\prod_{i=1}^{\infty}(A_{i},\tau_{i})\times\prod_{i=1}^{\infty}(A_{i},\tau_{i})$ to the set $\prod_{i=1}^{\infty}(A_{i},\tau_{i})$ by
>$$\theta((a_{1},a_{2},a_{3},\dots),(b_{1},b_{2},b_{3},\dots))=(a_{1},b_{1},a_{2},b_{2},a_{3},b_{3},\dots)$$
>(proof of $\theta$ being homeomorphism) and so $(G_{1},\tau_{1})\times(G_{2},\tau_{2})=(G,\tau)$.
>By induction, then, $(G,\tau)\cong\prod_{n=1}^{n}(G_{i},\tau_{i})$, for every positive integer $n$.
>Turning to the infinite product case, define the mapping
>$$\phi:\left[\prod_{i=1}^{\infty}(A_{i},\tau_{i})\times\prod_{i=1}^{\infty}(A_{i},\tau_{i})\times\prod_{i=1}^{\infty}(A_{i},\tau_{i})\times\dots\right]\to\prod_{i=1}^{\infty}(A_{i},\tau_{i})$$
>by 
>$$\begin{align}&\phi((a_{1},a_{2}, \dots),(b_{1},b_{2},\dots),(c_{1},c_{2},\dots),(d_{1},d_{2},\dots),(e_{1},e_{2}\dots),\dots)\\ &= (a_{1},a_{2},b_{1},a_{3},b_{2},c_{1},a_{4},b_{3},c_{2},d_{1},a_{5},b_{4},c_{3},d_{2},e_{1},\dots)\end{align}$$
>(proof that $\phi$ is a homeomorphism) and the proof is complete.

#### Interval is a continuous image of a Cantor space
>[!dsn]+ Proposition
>The topological space $[0,1]$ is a continuous image the Cantor Space $(G,\tau)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=230|Sidney A. Morris - "Topology without tears" p.230]]]

>[!proof]+
>In view of [[homeomorphisms of Cantor space#product of discrete finite spaces|cantor space is homeomorphic to a countable product of dinite discrete spaces]] it suffices to find a continous mapping $\phi$ of $\prod_{i=1}^{\infty}(A_{i},\tau_{i})$ onto $[0,1]$. Such mapping is given by
>$$\phi((a_{1},a_{2},\dots,a_{i},\dots))=\sum\limits_{i=1}^{\infty}\frac{a_{i}}{2^{i+1}}$$
>Recalling that each $a_{i}\in\{0,2\}$ and that each number $x\in[0,1]$ has a dyadic expansion of the form $\sum_{j=1}^{\infty}\frac{b_{j}}{2^{j}}$, where $b_{j}\in\{0,1\}$, we see that $\phi$ is an onto mapping. To show that $\phi$ is continous it suffices, by [[continuous mapping#continuity by image]], to verify that if $U$ is the open interval
>$$\left(\sum\limits_{i=1}^{\infty}\frac{a_{i}}{2^{i+1}}-\varepsilon,\sum\limits_{i=1}^{\infty}\frac{a_{i}}{2^{i+1}}+\varepsilon \right)\ni\sum\limits_{i=1}^{\infty}\frac{a_{i}}{2^{i+1}}\quad\forall\varepsilon>0$$
>then there exists an open set $W\ni(a_{1},a_{2},\dots,a_{i},\dots)$ such that $\psi(W)\subseteq U$. Choose $N$ sufficiently large that $\sum_{i=N}^{\infty}\frac{a_{i}}{2^{i+1}}<\varepsilon$, and put
>$$W=\{a_{1}\}\times\{a_{2}\}\times\dots\times\{a_{N}\}\times A_{N+1}\times A_{N+2}\times\dots$$
>Then $W$ is open in $\prod_{i=1}^{\infty}(A_{i},\tau_{i})$, $W\ni(a_{1},a_{2},\dots,a_{i},\dots)$, and $\phi(W)\subseteq U$, as required. 

***
#### Keywords
- [[Cantor space]],
- [[Product topology]],
- [[Discrete topology]],
- [[Function(mapping)]],
- [[Homeomorphism]],
- [[Compact set]],
- [[Hausdorff space]],
- [[Continuous mapping]],
- [[Topology basis]],
- [[Open and closed subsets]],
- [[Cartesian product of sets]],
- [[Interval]],
- [[Cardinality of a set]],
- [[Set]],
- [[Mathematical induction]],
- [[Integer Bases]]
#### Possibly related
***
#### Sources: