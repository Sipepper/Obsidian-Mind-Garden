---
Last time checked: 2024-02-19
Complete: true
aliases:
  - Группа
  - Група
---
# Group
***
###### tags: #Group_Theory #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $G$ be a set together with the law of composition $\cdot$ . Then it is called a *group* if:
>1. Law of composition is *associative*, i.e. $(ab)c=a(bc)$,$\forall a,b,c\in G$
>2. With respect to a law of composition there is a neutral element, i.e. some $e\in G$ such that $ae=ea=a$, $\forall a\in G$.
>3. With respect to a law of comosition exists an inverse elements to all elements of $G$, i.e. $\forall x\in G$ there is $a\in G$ such that $ax=xa=e$.

>[!example]+
>Let $GL_{2}(\mathbb{R})$ be a set of all $2\times2$ matrices with non-zero determinant, then under multiplication of matrices this set forms a group.

>*Group* $G$ is just a monoid, in which for every element $x\in G$ there exists a unique element $y\in G$ such that $xy=yx=e$. Such element is called an *inverse* to $x$.

#### Subgroup
>[!dsn]+ Definition
>Let $H$ be a subset of a group $G$. If such subset is closed under group operation from $G$, then $H$ is said to be a *subgroup* of $G$. And denoted as $H\leqslant G$, or $H<G$ if $H\ne G$. 

>[!example]+
>Let $GL_{n}(\mathbb{R})$ be a set of all $n\times n$ matrices, then the subset $SL_{n}(\mathbb{R})$ which consists of all matrices with determinant equal to one is a subgroup of $GL_{n}(\mathbb{R})$ because multipying two matrices with the determinant equal to $1$ will always give us the matrix with determinant equal to $1$.
***
#### Keywords
- [[Set]],
- [[Law of composition]],
- [[Associative property]],
- [[Linear groups]],
- [[Determinant]],
- [[Matrix]],
- [[Monoid]]
#### Possibly related
- 
***
#### Sources: