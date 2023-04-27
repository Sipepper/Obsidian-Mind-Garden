# Topology basis
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ be a topological space. A family $\mathfrak{B}$ of open subsets of $X$ is said to be *basis* of topology $\tau$ if every open set in $\tau$ is a union of elements from $\mathfrak{B}$, i.e. if $\mathfrak{B}$ is a basis then $U$ is open if and only if it is a union of members from $\mathfrak{B}$.^[Sidney A. Morris - "Topology without tears" p.57] 

>We say that $\mathfrak{B}$ *generates* topology $\tau$.

>Let $\mathfrak{B}$ be a basis for a topology $\tau$ on $X$ and $\mathfrak{B}_{1}$ is a collection of open subsets of $X$ such that $\mathfrak{B}\subseteq\mathfrak{B}_{1}\subseteq\tau$, then $\mathfrak{B}_{1}$ is also a basis for $\tau$. I.e. *topology can have multiple bases*.

>[!example]+ 
>Let $\mathfrak{B}$ is a family of all *open rectangles* in $\mathbb{R}^{2}$
>$$\{(x,y):(x,y)\in\mathbb{R}^{2},a<x<b,b<y<d \}$$
>every edge of which is parallel to $X$ or $Y$ axes.
>Then $\mathfrak{B}$ is a basis for a topology on $\mathbb{R}^{2}$, *euclidean topology*.
>This can be generalized to $\mathbb{R}^{n}$ using $n$-dimensional *open parallelopipeds*.

>[!example]+
>Let $X=\{a,b,c,d,e,f\}$ and $\tau_{1}=\{X,\emptyset,\{a\}, \{c,d\},\{a,c,d\},\{b,c,d,e,f\}\}$
>Then $\mathfrak{B}=\{\{a\},\{c,d\},\{b,c,d,e,f\}\}$ is a basis for $\tau_{1}$ as $\mathfrak{B}\subseteq\tau_{1}$ and every member of $\tau_{1}$ can be viewed as a union of members from $\mathfrak{B}$.
>And $\tau_{1}$ is a basis for itself.

>[!example]+
>Let $(X,\tau)$ be a discrete space and $\mathfrak{B}$ is a family of singleton subsets of $X$, i.e. $\mathfrak{B}=\{\{x\}:x\in X\}$. Then $\mathfrak{B}$ is a basis of $\tau$ following the definition of [[Discrete topology]].

>[!example]+
>Let $X=\{a,b,c\}$ and $\mathfrak{B}=\{\{a\},\{c\},\{a,b\},\{b,c\}\}$. Then $\mathfrak{B}$ is *not* a basis for *any* possible topology on $X$.
>
>>[!proof]+
>>Suppose that $\mathfrak{B}$ consists of union from $\mathfrak{B}$, namely
>>$$\tau=\{X,\emptyset,\{a\},\{c\},\{a,c\},\{a,b\},\{b,c\}\}$$
>>But $\tau$ is not a topology as $\{b\}=\{a,b\}\cap\{b,c\}$ don't belong to $\tau$ and thus $\tau$ is not a topology. Therefore we come to contradiction thus $\mathfrak{B}$ cannot be a basis for any topology on $X$.

#### Basis criterions
>[!dsn]+ Direct strict note
>Let $X$ be a non-empty set and let $\mathcal{B}$ be a collection of subsets of $X$. Then $\mathcal{B}$ is a basis for a topology on $X$ if and only if $\mathcal{B}$ has the following properties:
>1. $X=\bigcup\limits_{B\in\mathcal{B}}B$, and
>2. for any $B_{1},B_{2}\in\mathcal{B}$, the set $B_{1}\cap B_{2}$ is a union of members of $\mathcal{B}$.^[Sidney A. Morris - "Topology without tears" p.59]

>[!proof]+
>If $\mathcal{B}$ is a basis for a topology $\tau$ then $\tau$ must have the properties $(1)$, $(2)$ and $(3)$ of [[Topological space]]. In particular $X$ must be an open set and the intersection of any two open sets must be an open set. As the open sets are just the unions of members of $\mathcal{B}$, this implies that $(1)$ and $(2)$ above are true.
>Conversely, assume that $\mathcal{B}$ has properties $(1)$ and $(2)$ and let $\tau$ be the collection of all subsets of $X$ which are unions of members of $\mathcal{B}$. We shall show that $\tau$ is a topology on $X$.
>By $(a)$, $X=\bigcup_{B\in\mathcal{B}}B$ and so $X\in\tau$. Note that $\emptyset$ is an empty union of members of $\mathcal{B}$ and so $\emptyset\in\tau$. So we see that $\tau$ does have property $(1)$ of [[Topological space]].
>Now let $\{T_{j}\}$ be a family of members of $\tau$. Then each $T_{j}$ is a union of members of $\mathcal{B}$. Hence the union of all the $T_{j}$ is also a union of members of $\mathcal{B}$ and so is in $\tau$. Thus $\tau$ also satisfies condition $(2)$ of [[Topological space]].
>Finally let $C$ and $D$ be in $\tau$. We need to verify that $C\cap D\in\tau$. But $C=\bigcup_{k\in K}B_{K}$, for some index set $K$ and sets $B_{K}\in\mathcal{B}$. Also $D=\bigcup_{j\in J}B_{j}$, for some index set $J$ and $B_{j}\in\mathcal{B}$. Therefore
>$$C\cap D=\left(\bigcup\limits_{k\in K}B_{k} \right)\cap\left(\bigcup\limits_{j\in J}B_{j}\right)=\bigcup\limits_{k\in K,j\in J}(B_{k}\cap B_{j})$$
>By our assumption $(2)$, each $B_{k}\cap B_{j}$ is a union of members of $\mathcal{B}$ and so $C\cap D$ is a union of members of $\mathcal{B}$. Thus $C\cap D\in\tau$. So $\tau$ has property $(3)$ of [[Topological space]]. Hence $\tau$ is indeed a topology, and $\mathcal{B}$ is a basis for this topology, as required.

>[!dsn]+ Direct strict note
>Let $(X,\tau)$ be a topological space. A family $\mathcal{B}$ of open subsets of $X$ is a basis for $\tau$ if and only if for any point $x$ belonging to any open set $U$, there is a $B\in\mathcal{B}$ such that $x\in B\subseteq U$.^[Sidney A. Morris - "Topology without tears" p.64]

>[!proof]+
>Assume $\mathcal{B}$ is a basis for $\tau$ and $x\in U\in\tau$. As $\mathcal{B}$ is a basis for $\tau$, the open set $U$ is a union of members of $\mathcal{B}$; that is, $U=\bigcup_{j\in J}B_{j}$, where $B_{j}\in\mathcal{B}$, for each $j$ in some index set $J$. But $x\in U$ implies $x\in B_{j}$, for some $j\in J$. Thus $x\in B_{j}\subseteq U$, as required.
>
>Conversely, assume that for each $U\in\tau$ and each $x\in U$, there exists a $B\in\mathcal{B}$ with $x\in B\subseteq U$. We have to show that every open set is a union of members of $\mathcal{B}$. So let $V$ be any open set. Then for each $x\in V$, there is a $B_{x}\in\mathcal{B}$ such that $x\in B_{x}\subseteq V$. Clearly $V=\bigcup_{x\in V}B_{x}$. Thus $V$ is a union of members of $\mathcal{B}$.

#### Equivalent bases
>[!dsn]+ Direct strict note
>Let $\mathcal{B}_{1}$ and $\mathcal{B}_{2}$ be bases for topologies $\tau_{1}$ and $\tau_{2}$, respectively, on a non-emptyset $X$. Then $\tau_{1}=\tau_{2}$ if and only if 
>1. for each $B\in\mathcal{B}_{1}$ and each $x\in B$, there exists a $B'\in\mathcal{B}_{2}$ sch that $x\in B'\subseteq B$, and
>2. for each $B\in\mathcal{B}_{2}$ and each $x\in B$, there exists a $B'\in\mathcal{B}_{1}$ such that $x\in B'\subseteq B$.^[Sidney A. Morris - "Topology without tears" p.65]

>[!proof]+
>Firstly, assume that $\tau_{1}=\tau_{2}$. Then $(1)$ and $(2)$ follows from [[Topology basis#Basis criterions]].
>
>Conversely, assume that $\mathcal{B}_{1}$ and $\mathcal{B}_{2}$ satisfy the conditions $(1)$ and $(2)$. By [[Topology basis#Basis criterions]] $(1)$ implies that each $B\in\mathcal{B}_{1}$ is open in $(X,\tau_{2})$; that is, $\mathcal{B}_{1}\subseteq\tau_{2}$. As every member of $\tau_{1}$ is a union of members of $\tau_{2}$. Similarly $(2)$ implies $\tau_{2}\subseteq\tau_{1}$. Hence $\tau_{1}=\tau_{2}$, as required.

>[!example]+
>Let $X=\mathbb{R}^{2}$ be a topological space with euclidean topology. Let $\mathcal{B}_{1}$ and $\mathcal{B}_{2}$ be a set of "open squares" and open circles respectively. Then $\mathcal{B}_{1}$ and $\mathcal{B}_{2}$ are equivalent.
***
#### Keywords
- 
#### Possibly related
- 
***
#### Sources: