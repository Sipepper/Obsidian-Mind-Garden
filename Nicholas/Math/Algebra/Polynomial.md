---
Last time checked: 2024-01-25
Complete: true
aliases:
---
# Polynomial
***
###### tags: #Fundamental_math_objects #Algebra 
***
>[!dsn]+ Definition
>Let $(R,+,\cdot)$ be a ring. Then the formal expression
>$$\alpha=\sum\limits_{i=0}^{n}a_{i}x^{i}=a_{0}+a_{1}x+a_{2}x^{2}+\dots+a_{n}x^{n}$$
>where $a_{i}\in R$, $\forall i$, is said to be the *polynomial* over a ring $R$.
>
>The set of all polynomials over $R$ is denoted as $R[x]$.^[[Lectures at KAU - Eugene Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>$R[x]$ has a ring structure with respect to operations of addition
>$$\alpha+\beta:=\sum\limits_{i=0}^{n}(a_{i}+b_{i})x^{i}=(a_{0}+b_{0})+(a_{1}+b_{1})x+\dots$$
>and multiplication
>$$\alpha\cdot\beta:=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}a_{r}b_{s} \right)x^{i}$$
>>[!proof]+
>>As $R$ is a ring and addition in $R[x]$ is component-wise, all axioms of a ring except of distributivity, associativity of multiplication and existence of multiplicative identity.
>>
>>So suppose we have $1_{R[x]}$, then
>>$$\alpha\cdot 1_{R[x]}=\alpha$$
>>and
>>$$\sum\limits_{r+s=i} a_{r}b_{s}=a_{i}$$ 
>>for $a_{0}$, $b_{0}=1_{R}$, 
>>for $a_{1}$, 
>>$$a_{0}b_{1}+a_{1}b_{0}=a_{1}\Rightarrow a_{0}b_{1}+a_{1}=a_{1}\Rightarrow a_{0}b_{1}=0_{R}$$
>>so if it's true for all $a_{0}\in R$, $b_{1}=0_{R}$
>>for $a_{2}$,
>>$$a_{2}b_{0}+a_{1}b_{1}+a_{0}b_{2}=a_{2}$$
>>$$a_{1}b_{1}+a_{0}b_{2}=0_{R}\Rightarrow a_{0}b_{2}=0_{R}\Rightarrow b_{2}=0_{R}$$
>>etc. Thus $1_{R}$ is a multiplicative identity of $R[x]$.
>>*Distributivity*:
>>$$\begin{align}\gamma(\alpha+\beta)&=\sum\limits_{i=0}^{n}c_{i}x^{i}\cdot\left(\sum\limits_{i=0}^{n}(a_{i}+b_{i})x^{i} \right)\\ &=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}c_{r}(a_{s}+b_{s}) \right)x^{i}\\ &=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}c_{r}a_{s}+c_{r}b_{s})\right)x^{i}\\ &=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}c_{r}a_{s} \right)x^{i}+\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}c_{r}b_{s}\right)x^{i}\\ &=\gamma\alpha+\gamma\beta \end{align}$$
>>*Associativity*:
>>$$\begin{align}(\alpha\beta)\gamma&=\left(\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}a_{r}b_{s} \right)x^{i}\right)\sum\limits\limits_{i=0}^{n}c_{i}x^{i}\\ &= \sum\limits_{i=0}^{n}\left(\sum\limits_{k+l=i}\left(\sum\limits_{r+s=k}a_{r}b_{s} \right)c_{l}\right)x^{i}\\ &=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s+l=i}(a_{r} b_{s})c_{l} \right)x^{i}\\ &=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s+l=i}a_{r}(b_{s}c_{l}) \right)x^{i}\\&=\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}a_{r}\left(\sum\limits_{s+l=k}b_{s}c_{l} \right) \right)x^{i}\\ &= \left(\sum\limits_{i=0}^{n}\alpha_{i} \right)\sum\limits_{i=0}^{n}\left(\sum\limits_{r+s=i}a_{r}b_{s} \right)\\ &=\alpha(\beta\gamma) \end{align}$$

>Analogously we can define polynomial over $n$ variables, $R[x_{1},\dots,x_{n}]$.^[[Lectures at KAU - Eugene Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+ 
>Let $R=\mathbb{R}$, then $\mathbb{R}[x]$ is a well known set of polynomials with real coefficients, i.e. formal expressions with operations defined above.
***
#### Keywords
- [[Ring]],
- [[Set]],
- [[Law of composition]],
- [[Real line]]
#### Possibly related
- 
***
#### Sources: