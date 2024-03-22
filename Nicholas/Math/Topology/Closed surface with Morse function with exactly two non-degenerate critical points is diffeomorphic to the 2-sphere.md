---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Closed surface with Morse function with exactly two non-degenerate critical points is diffeomorphic to the 2-sphere
***
###### tags: #Topology/Differential/Morse_theory 
***
>[!dsn]+ Theorem
>Let $M$ be a closed surface. Suppose that there exists a Morse function $f:M\to\mathbb{R}$ with exactly two non-degenerate critical points (and no other critical points). Then $M$ is diffeomorphic to the sphere $\mathbb{S}^{2}$.^[[[Yukio Matsumoto - An introduction to Morse theory.pdf#page= 31|Yukio Matsumoto - "An introduction to Morse theory" p.17]]]

>[!proof]+
>Notice that a closed surface $M$ is compact(in fact as [[Surfaces are topological manifolds]] a closed surface is a two-dimensional compact manifold without boundary). 
>By [[continuous image of compact set to a real line has least and greatest elements]], the Morse function $f:M\to\mathbb{R}$ takes the maximum value at some point $p_{0}$ and the minimum value at some other point $q_{0}$ in $M$. The points $p_{0}$ and $q_{0}$ are non-degenerate critical points.
>According to [[Morse lemma]], we can express $f$ in a standard form with a suitable coordinate system $(x,y)$ about $p_{0}$ and another coordinate system $(X,Y)$ about $q_{0}$.
>
>Then index of $p_{0}$ is $2$ since $f$ takes the maximum value at this point, and the index of $q_{0}$ is $0$ because $f$ takes the minimum value
>![[Pasted image 20230815224532.png]]
>there. Thus we have the following expression for $f$ in these coordinate systems:
>$$f=\begin{cases}-x^{2}-y^{2}+A&(\text{near }p_{0})\\ X^{2}+Y^{2}+a&(\text{near }q_{0}) \end{cases} \qquad(*)$$
>Here $A$ and $a$ are the maximum and minimum values of respectively. Let $\varepsilon$ be a small enough positive number, and denote by $D(p_{0})$ the set of points in a neighborhood of $p_{0}$ with
>$$A-\varepsilon\le f(p)\le A$$
>The upside-down bowl in the left of Figure 1.10 descries the set $D(p_{0})$ which, in the local coordinates $(x,y)$, corresponds to the inequality
>$$x^{2}+y^{2}\le\varepsilon$$
>according to the equality $(*)$. In other words, $D(p_{0})$ is diffeomorphic to the $2$-disk(two dimensional disk) defined by the inequality above. Similarly the set $D(q_{0})$ of points in a neighborhood of $q_{0}$, satisfying
>$$a\le f(p)\le a+\varepsilon$$
>corresponds to the bowl in the right of the Figure 1.10. In terms of the local coordinates $(X,Y)$, $D(q_{0})$ has the expression
>$$X^{2}+Y^{2}\le\varepsilon$$
>and so it is also diffeomorphic to the $2$-disk.
>
>Now remove the interiors of $D(p_{0})$ and $D(q_{0})$ from the surface $M$, and denote by $M_{0}$ the resulting surface with boundary.
>![[Pasted image 20230816214522.png]]
>The boundary $\partial M_{0}$ consists of two circles $C(p_{0})$ and $C(q_{0})$, so that
>$$\partial M_{0}=C(p_{0})\cup C(q_{0})$$
>From definition of $D(p_{0})$ and $D(q_{0})$, the restriction of the function $f$ to $M_{0}$, $f:M_{0}\to\mathbb{R}$, takes the constant values $A-\varepsilon$ and $a+\varepsilon$ on the boundary circles $C(p_{0})$ and $C(q_{0})$ respectively.
>
>Recall that it was assumed that the Morse function has exactly two critical points $p_{0}$ and $q_{0}$. Thus, having removed the interior of $D(p_{0})$ and $D(q_{0})$, we no longer have any critical points for $f:M_{0}\to\mathbb{R}$. 
>
>Since the boundary $C(q_{0})$ is diffeomorphic to the unit circle, [[Morse functions with no critical value in the interval]] implies that $M_{0}$ is diffeomorphic to the direct product
>$$\mathbb{S}^{1}\times[0,1]$$
>i.e. Annulus.
>Set
>$$N_{0}=M_{0}\cup D(q_{0})$$
>that is, $N_{0}$ is the union of $M_{0}$ and the upright bowl $D(q_{0})$. More precisely, one obtains $N_{0}$ by attaching the disk $D(q_{0})$ to $M_{0}$ along the boundary of $D(q_{0})$, and therefore $N_{0}$ is also diffeomorphic to the disk.
>
>We past $D(p_{0})$ along the boundary of $N_{0}$ to recover $M$. This shows that $M$ is a closed surface diffeomorphic to the sphere $\mathbb{S}^{2}$, and the proof of theorem is complete.

>[!example]+ 
>
***
#### Keywords
- 
#### Possibly related
- 
***
#### Sources: