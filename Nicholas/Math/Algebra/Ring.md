---
Last time checked: 2023-11-16
Complete: true
aliases:
---
# Ring
***
###### tags: #Algebra #Fundamental_math_objects 
***
>[!dsn]+ Definition
>A set $R$ together with two laws of compositions $R\times R\to R$:
>- *Addition* - $(a,b)\mapsto a+b$
>- *Multiplication* - $(a,b)\mapsto a\cdot b$
>
>which have the following properties
>- Associativity of addition: $\forall a,b,c\in R$, $(a+b)+c=a+(b+c)$;
>- Existence of neutral element: $\exists 0_{R}\in R$ such that $\forall a\in R$, $a+0_{R}=0_{R}+a=a$;
>- Existence of additive inverse: $\forall a\in R$, $\exists\hat{a}\in R$, such that $a+\hat{a}=\hat{a}+a=0_{R}$;
>- Commutativity of addition: $\forall a,b\in R$, $a+b=b+a$;
>- Associativity of multiplication: $\forall a,b,c\in R$, $(a\cdot b)\cdot c=a\cdot(b\cdot c)$;
>- Existence of identity: $\exists 1_{R}\in R$, such that $\forall a\in R$, $a\cdot 1_{R}=1_{R}\cdot a=a$;
>- Distributivity: $\forall a,b,c$, $a\cdot(b+c)=a\cdot b+ a\cdot c$ and $(a+b)\cdot c=a\cdot c+b\cdot c$
>
>Is called a *ring* and denoted as $(R,+,\cdot)$.^[[Lecture at KAU - Eugene Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>In other words, ring $(R,+,\cdot)$ is an abelian group under addition and monoid under multiplication.^[https://en.wikipedia.org/wiki/Ring_(mathematics)]

>If multiplication is commutative, i.e. $a\cdot b=b\cdot a$, we say that $R$ is a *commutative ring*.

>Neutral element and multiplicative identity are unique.
>>[!proof]+
>>Suppose that $1_{R}\ne 1'_{R}$ are two multiplicative identities in $R$. Then
>>$$1_{R}=1_{R}\cdot 1'_{R}=1'_{R}$$
>>thus $1_{R}=1'_{R}$. Analogously for neutral element.

>Additive inverses are unique
>>[!proof]+
>>Let $a\in R$, $a',a''\in R$ such that 
>>$$a+a'=0_R\quad\text{and}\quad a+a''=0_{R}$$
>>then
>>$$\begin{align}a'&=a'+0_{R}\\ &=a'+(a+a'')\\ &=(a'+a)+a''\\ &=0_{R}+a''\\&=a'' \end{align}$$
>>thus $a'=a''$.

>[!example]+ 
>- $(\mathbb{Z},+,\cdot)$ is a ring, where $0_{\mathbb{Z}}=0$ and $1_{\mathbb{Z}}=1$.
>- A set $5\mathbb{Z}=\{5k|k\in\mathbb{Z}\}$ together with operations $+$ and $\cdot$ is *not* a ring, as there are no identity element with respect to multiplication.

>Let $(R,+,\cdot)$ be a ring, $S\subset R$. Suppose that $0_{R}\in S$, $1_{R}\in S$ and $S$ is closed under operations. We say that $S$ is a *subring* if it is also a ring and $0_{S}=0_{R}$, $1_{S}=1_{R}$.
>>[!example]+
>>A subset 
>>$$\Delta=\{(a,a):a\in R\}\subset R\times R$$
>>is a subring of $R$, which has similar structure to $R$ itself (because of component-wise operations).

***
#### Keywords
- [[Set]],
- [[Law of composition]],
- [[Cartesian product of sets]],
- [[Associative property]],
- [[Commutative property]],
- [[Abelian group]],
- [[Monoid]],
- [[Set of integers]],
#### Possibly related
- [[Group coset]],
- [[Diagonal of topological product space]]
***
#### Sources: