# Quotient group by component of identity is totally disconnected
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>If $G$ is any topological group and $C$ is the component of the identity, then $G/C$ is a totally disconnected topological group.^[Sidney A. Morris - "Topology without tears" p.524]

>[!proof]+
>By [[Component of the identity of topological group is a closed normal subgroup]] $G/C$ is a topological group.
>
>Note that all connected components of $G$ are of the form $gC$. Indeed, $C$ is a connected component of $e\in G$ and for any $g\in G$ we have a homeomorphism $f_{g}:G\to G$ such that $f_{g}(x)=gx$. Thus $f_{g}(C)=gC$ is a connected component of $g\in G$ as [[Connected topological space#Homeomorphisms preserves connectedness|homeomorphisms preserve connectedness]].
>
>Now let $\pi:G\to G/C$ be the quotient map (which is open and onto) and $A\subseteq G/C$ be an arbitrary, connected subset of $G/C$. Assume that there are at least two points in $A$. Consider the subset $\pi^{-1}(A)\subseteq G$ (which is the union of some cosets). Since $A$ has at least two points, then $\pi^{-1}(A)$ contains at least two cosets, which are connected components of $G$. Thus $\pi^{-1}(A)$ is not connected. Therefore there exist $U,V\subseteq\pi^{-1}(A)$ such that $U,V$ are open (in $\pi^{-1}(A)$), disjoint and $U\cup V=\pi^{-1}(A)$.
>
>Note that if $x\in U$, then the connected component of $x$ (which is equal to $xC$) is contained in $U$. Indeed, assue that $xC\not\subseteq U$. Then there is $h\in xC$ such that $h\notin U$. Then, since $U\cup V=\pi^{-1}(A)$ we have that $h\in V$. But then $U\cap xC$ and $V\cap xC$ are nonempty open and disjoint subsets of $xC$ such that $(U\cap xC)\cup(V\cap xC)=xC$. Contradiction, because $xC$ is connected. Analogously, whenever $x\in V$, then $xC\subseteq V$.
>
>Therefore both $U$ and $V$ are unions of cosets. Thus $\pi(U)$ and $\pi(V)$ are disjoint. Furthermore $\pi(U)\cup\pi(V)=A$ and both $\pi(U)$, $\pi(V)$ are open in $A$ (because $\pi$ is an open map). This means that $A$ is not connected. Contradiction. Thus $A$ has at most one element, which completes the proof.^[https://planetmath.org/quotientgroupofatopologicalgroupbyitsidentitycomponentistotallydisconnected]

>[!proof]+
>By [[Component of the identity of topological group is a closed normal subgroup]] $G/C$ is a topological group.
>Let $C_{G/C}(gC)$ be a component of an element $gC$. We need to show that $C_{G/C}(gC)=gC$. $gC$ is connected as a homeomorphic image of connected set([[Topological group translations are homeomorphisms]]). Suppose that $C_{G/C}(gC)=gC\cup g'C$. Then because $gC\cap g'C=\emptyset$, $gC\cup g'C$ is not connected (by [[Union of connected spaces is connected if they have nonempty intersection]]). Thus $C_{G/C}(gC)=gC$, i.e. $G/C$ is totally disconnected. 

>

***
#### Keywords
- [[Topological group]]
- [[Component of topological space]],
- [[Quotient group]],
- [[Quotient topology on a quotient group]],
- [[Component of topological space]],
- [[Homeomorphism]],
- [[Topological group translations are homeomorphisms]],
- [[Connected topological space]],
- [[Open and closed mappings]],
- [[Group coset]],
- [[Preimage]],
- [[Open and closed subsets]],
- [[Set]],
- [[Totally disconnected space]]
#### Possibly related
- 
***
#### Sources: