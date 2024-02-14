---
Last time checked: 2024-02-09
Complete: false
aliases:
---
# Properties of countable sets
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Proposition
>1. Every subset of a countable set is again countable.
>2. Let $S$ be a countable and let $f:S\to T$ be a map. The image $f(S)$ is again countable.
>3. The union of countably many countable sets is again countable.
>4. Let $T$ be a set and let $S$ be a subset such that $T\setminus S$ is countable. Then $S$ is countable if and only if $T$ is countable.
>5. The product of finitely many countable sets is again countable.
>6. If $S$ is a finite set and if $T$ is countable set, then the set of maps from $S$ to $T$ is also countable.^[[[Stefan Friedl - Algebraic topology.pdf#page=78|Stefan Friedl - "Algebraic topology" p.78-79 ]]]

>[!proof]+
>1. After excluding the case that $S$ is finite and the case that $T$ is finite we see that we need to prove that: given infinite subset $T$ of $\mathbb{N}$ there exists a bijection $\phi:\mathbb{N}\to T$. Such a bijection is given by defining $\phi(i)$ as the $i$-th smallest element of $T$.
>2. Let $S$ be a countable set and let $f:S\to T$ be a map. We only need to consider the case that $S=\mathbb{N}$ and that $f(S)$ is infinite. In this case the bijection $\phi:\mathbb{N}\to f(S)$ is given by defining $\phi(1)=f(1)$ and by defining iteratively
>   $$\phi(i+1):=\left\{f(k)\Bigg|\begin{matrix}\;k\in\mathbb{N}\text{ is the smallest number such} \\ \text{that }f(k)\notin\{\phi(1),\dots,\phi(i) \} \end{matrix} \right\}$$
>3. 
>4. It follows from $(2)$ and $(3)$.
>5. By induction and by ignoring the rather dull case of finite sets it remains to show that $\mathbb{N}_{0}\times\mathbb{N}_{0}$ is countable. This can be shown by following argument
>   ![[Pasted image 20230705171442.png]]
>6. Let $S=\{v_{1},\dots,v_{n}\}$ be a finite set and let $T$ be a countable set. We have an obvious bijection between $T^{n}$ and the set of maps from $S$ to $T$. Thus is follows from $(4)$ that the set of maps from $S$ to $T$ is countable.

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Cardinality of a set]],
- [[Function(mapping)]],
- [[Kernel and image of a mapping]],
- [[Set of natural numbers]],
- [[Cartesian product of sets]],
#### Possibly related
- 
***
#### Sources: