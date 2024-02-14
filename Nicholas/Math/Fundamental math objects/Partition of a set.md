---
Last time checked: 2024-02-09
Complete: true
aliases:
---
# Partition of a set
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $A$ be a set. Consider a family of subsets $\{Q_{\alpha}\}_{\alpha\in\Lambda}$, such that 
>1. $A=\bigcup\limits_{\alpha}Q_{\alpha}$
>2. $Q_{\alpha}\cap Q_{\beta}=\emptyset$, if $\alpha\ne\beta$
>
>And if $a\sim b\Leftrightarrow\exists\alpha:a,b\in Q_{\alpha}$, i.e. $a,b$ lies inside same equivalence class(we now see that $Q_{\alpha}$ are equivalence classes).

>[!example]+ 
>Let $A=\mathbb{Z}$ and $Q_{i}=[i]_{6}$, then
>$$\mathbb{Z}=\bigcup_{i=0}^{5}[i]_{6}$$
>as all $[i]_{6}$ contains numbers with remainder equal to $i$ when divided by $6$. Also $[i]_{6}\cap[j]_{6}=\emptyset$ if $i\ne j$, by [[properties of residue classes]].
***
#### Keywords
- [[Set]],
- [[Equivalence relation]],
- [[Equivalence class]],
- [[Set of integers]],
- [[Residue class]],
- [[Division with remainder]]
#### Possibly related
- 
***
#### Sources: