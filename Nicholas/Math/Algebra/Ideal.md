---
Last time checked: 2023-11-20
Complete: false
aliases:
---
# Ideal
***
###### tags: #Algebra 
***
#### Ring ideals
>[!dsn]+ Definition
>A subset $I$ of a ring $R$ is said to be the *(two-sided) ideal* if it's closed under addition, and satisfies axiom $(1)$-$(4)$ from definition of a ring, and absorption property
>$$\forall a\in I,\forall r\in R\quad (ra\in I)\land(ar\in I)$$
>.^[[Lectures at KAU - Yevgen Polulyakh 6](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>If $R$ is non-commutative the absorption may not be "two-sided" and we obtain two definitions namely
>$$\forall a\in I,\forall r\in R\quad ra\in I$$
>$I$ is a *left ideal*
>and
>$$\forall a\in I,\forall r\in R\quad ar\in I$$
>$I$ is a *right ideal*.

>[!example]+
>Let $R=M_{2}(\mathbb{R})$, $$I=\left\{\begin{pmatrix}a&0\\b&0 \end{pmatrix}\in M_{2}(\mathbb{R}) \right\}$$
>As addition is "component-wise" $I$ is closed under addition and axioms $(1)$-$(4)$ from [[ring]] is satisfied.
>
>Let 
>$$ A=\begin{pmatrix}a&0\\b&0 \end{pmatrix}\in I,\quad B=\begin{pmatrix}c&d\\e&f \end{pmatrix}\in R$$
>then
>$$B\cdot A=\begin{pmatrix}c&d\\e&f \end{pmatrix}\cdot\begin{pmatrix}a&0\\b&0 \end{pmatrix}=\begin{pmatrix}ca+db&0\\ae+bf&0 \end{pmatrix}\in I$$
>$$A\cdot B=\begin{pmatrix}a&0\\b&0 \end{pmatrix}\cdot\begin{pmatrix}c&d\\e&f \end{pmatrix}=\begin{pmatrix}ac&ad\\ bc &bd \end{pmatrix}\notin I$$
>Thus $I$ is a left ideal but not the right ideal.

#### Ideals in Lie algebras
>[!dsn]+ Definition
>Let $I$ be some subspace of lie algebra $L$. If $[a,b]\in I$ for all $a\in L$ and $b\in I$ then $I$ is said to be the *ideal* in algebra $L$. In another words $I$ is ideal of $L$ if
>$$[L,I]\subseteq I$$
>by anticommutativity ($[a,b]=-[b,a]$) we have that
>$$[L,I]=[I,L]$$
>Ideals are denoted as $I\triangleleft L$. Algebra always has the $<0>$ and $L$ ideals. 

>Ideal is always a subalgebra
>>[!proof]+
>>Let $I\triangleleft L$. Then
>>$$[I,I]\subseteq[L,I]\subseteq I$$
>>therefore $[I,I]\subseteq I$, and thus $I$ is a subalgebra of $L$. But the converse is *false* not all subalgebras are ideals. 

>[!example]+ 
>

#### Ideals in Leibniz algebras
>[!dsn]+ Definition
>The subspace $I$ of a Leibniz algebra $L$ is said to be *left ideal* of $L$, if $[a,b]\in I$ for all $a\in L$,$b\in I$, i.e. subspace $I$ of $L$ is a left ideal of $L$ if
>$$[L,I]\subseteq I$$

>Similarly a subspace $U$ of $L$ is said to be the *right ideal* of $L$ if $[b,a]\in U$ for all $a\in L$, $b\in U$, or
>$$[U,L]\subseteq U$$

>If the subspace $V$ is both right and left ideal of $L$, then we just saying that $V$ is an *ideal* of $L$, equivalently
>$$[L,V],[V,L]\subseteq V$$
>Often denoted as $V\triangleleft L$.

>Every ideal(left, right or both) is a subalgebra.
>$$[I,I]\subseteq[L,I]\subseteq I$$
>$$[I,I]\subseteq[I,L]\subseteq I$$
>But not all subalgebras are ideals.

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Ring]],
- [[Commutative property]],
- [[Ring of matrices]],
- [[Matrix]],
- [[Lie algebra]],
- [[Vector space]]
- [[Leibniz algebra]],
- [[Properties of subalgebras, ideals and sums of subalgebras in Lie algebras]],
- [[Algebra]],
- [[Commutant in algebras]]
#### Possibly related
- 
***
#### Sources:
