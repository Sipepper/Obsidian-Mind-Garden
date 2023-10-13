# There exist only five plane crystallographic groups up to conjugation
***
###### tags: #Geometry 
***
>[!dsn]+ Direct strict note
>Let $E$ be the Euclidean plane. Up to conjugation in the $GL(\mathbb{R}^{2})$, there exist only *five* crystallographic groups $G$, corresponding to figures 1.7.4.1 through 1.7.4.5.
>![[Pasted image 20230723155203.png]]
>These pictures depicts [[Fundamental tilings]].

>[!proof]+
>Let $\vec{E}$ be the vector space underlying $E$, and $\text{Is}^{+}(E)\to\text{GL}(\vec{E})$ the homomorphism whose kernel $T(E)$ is the group of translations of $E$. By [[isometries of real plane]] map $f\in\text{Is}^{+}(E)\setminus T(E)$ is necessarily a rotation by some angle around its unique fixed point, called its center.
>
>The first idea of the proof is a fact that [[crystallographic group acts discretely on real plane]]
>The second key point in the proof is a fact that [[subgroup of translations of euclidean plane is a lattice]].
>
>Let $G'=G\setminus\Gamma$. If $G'$ is empty, we're in the situation of figure 1.7.4.1; otherwise, the elements of $G'$ are all true rotations, and they must be of *finite* order by second axiom of [[axioms for tilings and crystallographic group]]. Assume first that they all have order two; then we're in the situation of figure 1.7.4.2. Suppose now that $r\in G'$ has order $\alpha\ge3$, and assume also its angle is $2\pi/\alpha$, which is always possible. Call it's center $a$. Let $b\ne a$ be the center of a rotation in $G'$ such that $d(b,a)$ is minimal, and let $s$ be a rotation of center $b$, order $\beta\ge3$ and angle $2\pi/\beta$. Put $t=(rs)^{-1}$, so that $rst=\text{Id}_{E}$. Now [[Structure of plane isometries]] shows that the center $c$ of $t$ is such that the angles of the triangle formed by $a,b,c$ are half the angles of $r,s,t$, respectively
>![[Pasted image 20230827213512.png]]
>We now show that the choice of $b$ implies that the angle of $t$ is $2\pi/\gamma$, where $\gamma$ is the order of $t$. In fact, if $t$ had angle $2\pi n/\gamma$, $n\ge2$, there would exist a rotation $t'\in G'$ with center $t$ and angle less than $2\pi n/\gamma$. Then, applying the [[Structure of plane isometries]], it would follow that $(rt')^{-1}\in G'$ has center $a'$, a point closer to $a$ than $b$ is, contradicting the choice of $b$(right figure above).
>Since the sum of angles of a triangle is $\pi$, we obtain the basic oncdition
>$$\frac{1}{\alpha}+\frac{1}{\beta}+\frac{1}{\gamma}=1$$
>But $\alpha\ge3$, $\beta\ge3$, $\gamma\ge2$ are all integers, so the only possibilities are the following:
>
>||$\alpha$|$\beta$|$\gamma$|
>|---|---|---|---|
>|case I|3|3|3|
>|case II|2|4|4|
>|case III|2|3|6|
>
>We easily deduce 1.7.4, by showing that cases I, II and III correspond to the groups associated with figures 1.7.4.3, 1.7.4.4 and 1.7.4.5, respectively.




>[!example]+ 
>
***
#### Keywords
- [[Linear groups]]
#### Possibly related
- 
***
#### Sources: