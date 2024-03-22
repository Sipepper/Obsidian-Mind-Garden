---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Quotient topology
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $(X,\tau)$ and $(Y,\tau_{1})$ be topological spaces. Then $(Y,\tau_{1})$ is said to be a *quotient space* of $(X,\tau)$ if there exists a surjective mapping $f:(X,\tau)\to(Y,\tau_{1})$ with the property
>$$\forall U\subseteq Y,\quad U\in\tau_{1}\Leftrightarrow f^{-1}(U)\in\tau$$
>A surjective mapping $f$ with the property above is said to be a *quotient mapping*.^[[[Sidney A. Morris - Topology without tears.pdf#page=338|Sidney A. Morris - "Topology without tears" p.338]]]

>Every quotient map is a continuous map.
>>[!proof]+
>>It follows from definition.

>We can restate the definition using closed sets
>$$\forall A\subseteq Y,\quad A\text{ is closed in }(Y,\tau_{1})\Leftrightarrow f^{-1}(A)\text{ is closed in }(X,\tau)$$
>>[!proof]+
>>

>Let $f$ be a one-to-one mapping of a topological space $(X,\tau)$ onto a topological space $(Y,\tau_{1})$. Then $f$ is a homeomorphism if and only if it is a quotient mapping.
>>[!proof]+
>>

>[!example]+ 
>

#### Definition of quotient space by equivalence classes
>[!dsn]+ Definition
>Let $(X,\tau)$ be any topological space and $\sim$ any equivalence relation on $X$. Let $Y$ be the set of all equivalence classes of $\sim$. We can denote $Y$ by $X/\sim$. Then natural topology to put on the set $Y=X/\sim$ is the quotient topology under the map which *identifies* the equivalence classes; that is, maps each equivalence class to a point.^[[[Sidney A. Morris - Topology without tears.pdf#page=343|Sidney A. Morris - "Topology without tears" p.343]]]

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Function(mapping)]],
- [[Preimage]],
- [[Continuous mapping]],
- [[Open and closed subsets]],
- [[Homeomorphism]],
- [[Quotient set]],
- [[Equivalence relation]],
- [[Equivalence class]],
#### Possibly related
- 
***
#### Sources: