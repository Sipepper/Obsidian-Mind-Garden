# Index of normalizer
***
###### tags: #Group_Theory 
***
>[!dsn] Direct strict note
>Let $G$ be a group, and $S$ is a subset of $G$, then the number of distinct subsets of $G$ which are conjugates of $S$ is $[G:N_{G}(S)]$.^[https://proofwiki.org/wiki/Number_of_Distinct_Conjugate_Subsets_is_Index_of_Normalizer]

>In particular when $S$ consists of one elements $a$, we have the following
>$$|a^{G}|=|G:N_{G}(a)|$$
>i.e. the number of elements in conjugacy class of element $a$.

>[!proof]
>If two sets are conjugate to the set $S$ we can write the following
>$$S^{a}=S^{b}$$
>then it's equivalent to
>$$S^{ab^{-1}}=S$$
>That is
>$$S^{a}=S^{b}\Longleftrightarrow ab^{-1}\in N_{G}(S)$$
>Thus we have a bijection between the conjugacy class $C_{S}$ of subsets of $G$ conjugate to $S$ and the left coset space $G/N_{G}(S)$ given by
>$$S^{a}\to a^{-1}N_{G}(S)$$
>
>Since $G/N_{G}$ has $[G:N_{G}(S)]$ elements, the result is follows.

>[!example] 
>
***
#### Keywords
- [[Group]],
- [[Set]],
- [[Conjugacy class]],
- [[Conjugation in groups]],
- [[Index of a subgroup]],
- [[Group coset]],
- [[Function(mapping)]],
- [[Cardinality of a set]]
#### Possibly related
- 
***
#### Sources: