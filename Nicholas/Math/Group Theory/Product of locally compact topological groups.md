# Product of locally compact topological groups
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $\{G_{i}:i\in I\}$ be a family of topological groups. Then
>1. $\prod\limits_{i\in I}G_{i}$ is locally compact if and only if each $G_{i}$ is locally compact and all but a finite number of $G_{i}$ are compact.
>2. $\prod\limits_{i\in I}^{r}G_{i}$ is locally compact Hausdorff if and only if each $G_{i}$ is locally compact Hausdorff and $G_{i}=\{e\}$ for all but a finite number of $G_{i}$.^[Sidney A. Morris - "Topology without tears" p.530]

>[!proof]+
>1. Let $\prod\limits_{i\in I}G_{i}$ be a locally compact topological group, then for every element $\prod\limits_{i\in I}g_{i}$ there exists a compact neighborhood $U$. Then by [[Projection map in product spaces]] and [[Continuous image of compact space is compact]] $p_{i}(U)$ is a compact neighborhood of point $g_{i}\in G_{i}$. As $p_{i}$ is surjective then every point of $G_{i}$ has a compact neighborhood, that is $G_{i}$ is locally compact.
>   ${}$
>   Conversely every compact neighborhood $U$ of $\prod\limits_{i\in I}g_{i}$ is a product of $U_{i}$, where $i\in\{1,\dots,n\}$ all other component of neighborhood consists of whole groups $G_{i}$ , compact neighborhoods of $g_{i}$, by converse of [[Tychonoff's theorem]].
>2. Let $g=g_{1}\times\dots\times g_{n}\times\prod\limits_{i\in J}e_{i}$, and $U=U_{1}\times\dots\times U_{n}\times\prod\limits_{i\in J}e_{i}$ be a compact neighborhood of $g$, where $U_{i}$ is a compact neighborhoods of $g_{i}$ and $\prod\limits_{i\in J}e_{i}$ is compact set as product of finite(thus compact) sets. Then as projection map $p_{i}$ is continuous and surjective
>   $$p_{i}(U)=\begin{cases}U_{i}&i\in\{1,\dots,n\}\\e_{i}&\text{otherwise} \end{cases}$$ 
>   Thus every $G_{i}$ is locally compact and $G_{i}=\{e\}$ for all but a finite number of $G_{i}$.
>   Then as [[T1 topological group is a Hausdorff space]], it sufficient to show that every singleton subsets of $G_{i}$ is closed.
>   Let $g=g_{1}\times\dots\times g_{n}\times\prod\limits_{i\in J}e_{i}$, then $G\setminus\{g\}$ is an open neighborhood which don't contain $g$, as $\{g\}$ is closed as a singleton subset of hausdorff space. Then as $p_{i}$ is surjective and open 
>   $$p_{i}(G\setminus\{g\})=\begin{cases}G_{i}\setminus\{g_{i}\}&i\in\{1,\dots,n\}\\ G_{i}&\text{otherwise} \end{cases}$$
>   in both cases the image is open, thus $\{g_{i}\}$, or $\{e_{i}\}$ are open in $G_{i}$, therefore every $G_{i}$ is a $T_{1}$ group and Hausdorff. 
>   ${}$
>   Conversely every compact neighborhood in $\prod\limits_{i\in I}^{r}G_{i}$ contains a compact subset of the form $U_{1}\times\dots\times U_{n}\times\prod\limits_{i\in J}e_{i}$, that is the product of compact neighborhoods in finite number of $G_{i}$. 

>[!example]+ 
>
***
#### Keywords
- [[Topological group]],
- [[Locally compact space]],
- [[Cardinality of a set]],
- [[Product topology]],
- [[Hausdorff space]],
- [[Compact set]],
- [[Neighborhood in topological space]],
- [[Function(mapping)]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: