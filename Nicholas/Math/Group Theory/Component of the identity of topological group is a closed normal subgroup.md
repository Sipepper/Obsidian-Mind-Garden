---
Last time checked: 2024-02-25
Complete: false
aliases:
---
# Component of the identity of topological group is a closed normal subgroup
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>The component of the identity (that is, the largest connected subset containing $e$) of a topological group is a closed normal subgroup.^[[[Sidney A. Morris - Topology without tears.pdf#page=523|Sidney A. Morris - "Topology without tears" p.523]]]

>[!proof]+
>Let $C$ be the component of the identity in a topological group $G$. As in any topological space components are closed sets, $C$ is closed.
>Let $a\in C$. Then $a^{-1}C\subseteq C$, as $a^{-1}C$ is connected (being a homeomorphic image of $C$) and contains $e$.
>So $\bigcup\limits_{a\in C}a^{-1}C=C^{-1}C\subseteq C$, which implies that $C$ is a subgroup.
>To see that $C$ is a normal subgroup, simply note that for each $x\in G$, $x^{-1}Cx$ is a connected set containing $e$ and so $x^{-1}Cx\subseteq C$.

>[!example]+ 
>
***
#### Keywords
- [[Component of topological space]],
- [[Connected topological space]],
- [[Topological group]],
- [[Open and closed subsets]],
- [[Normal subgroup]],
- [[Topological group translations are homeomorphisms]],
- [[Homeomorphism]],
- [[Group#Subgroup]]
#### Possibly related
- [[Conjugation in groups]],
***
#### Sources: