---
Last time checked: 2024-03-13
Complete: true
aliases:
---
# Topological space
***
###### tags: #Topology #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $X$ be a nonempty set. The family $\tau$ of subsets of $X$ is called the *topology* of $X$ if it has following properties:
>1. $X$ and $\emptyset$ belongs to $\tau$.
>2. Union of any (arbitrary cardinality) number of sets from $\tau$ belongs to $\tau$.
>3. Intersection of any two sets from $\tau$ belongs to $\tau$.
>
>The pair $(X,\tau)$ is called a *topological space*

>Elements of topological spaces are often called *points*. 

>[!example]+ 
>Let $$X = \{a,b,c,d,e,f\}$$ and $$\tau_{1}=\{X,\emptyset, \{a\},\{c,d\},\{a,c,d\},\{b,c,d,e,f\}\}$$
Then $\tau_1$ is a topology on $X$ because it satisfies all axioms from definition.

>[!example]+
>Let $$X = \{a,b,c,d,e\} $$ and $$\tau_{2}= \{X,\emptyset,\{a\},\{c,d\},\{a,c,e\},\{b,c,d\}$$
Then $\tau_2$ is *not* a topology on $X$ because a union $$\{c,d\}\cup\{a,c,e\}=\{a,c,d,e\}$$ not belong to $\tau_2$.

>[!example]+
>Let $X=\mathbb{N}$ and $\tau_4$ consists of $\mathbb{N}$,$\emptyset$, and all finite subsets of $\mathbb{N}$. Then $\tau_4$ is not a topology on $\mathbb{N}$, because the infinite union $$\{2\}\cup\{3\}\cup\dots\cup\{n\}\cup\dots = \{2,3,\dots,n,\dots\}\notin\tau_4$$ not in topology $\tau_4$.
***
#### Keywords
- [[Set]],
- [[Cardinality of a set]],
- [[Set of natural numbers]]
#### Possibly related
- 
***
#### Sources: