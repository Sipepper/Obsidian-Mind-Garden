---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Surjective homomorphic image of an ideal is an ideal
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Lemma
>Let $f:R\to S$ be a surjective ring homomorphism. Let $I$ be an ideal in $R$. Then $f(I)$ is an ideal in $S$.^[[Lectures at KAU - Yevgen Polulyakh 7](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>A set $f(I)\subset S$ is closed under addition and multiplication in $S$. Indeed, let $r,u\in R$. Then $f(r)+f(u)=f(r+u)\in f(R)$, $f(r)\cdot f(u)=f(r\cdot u)\in f(R)$, as $f$ is a homomorphism.
>
>A set $f(I)$ has the absorption property. Let $w\in f(I)$, $u\in f^{-1}(w)\subset I$, $s\in S$. From surjectivity of $f$ it follows that, there exists $r\in f^{-1}(s)$. Then $ws=f(u)f(r)=f(ur)\subset f(I)$, because $ur\in I$ as $I$ is an ideal. Analogously, $sw=f(r)f(u)=f(ru)\subset f(I)$.

>[!example]+ 
>Consider the rings $\mathbb{Z}$ and $\mathbb{Q}$. Denote $i:\mathbb{Z}\hookrightarrow\mathbb{Q}$ is an inclusion: $\forall n\in\mathbb{Z}$, $i(n)=n\in\mathbb{Z}$. Indeed $i$ is a ring homomorphism. Let $I=\langle 2 \rangle=2\mathbb{Z}$ - be a principal ideal in $\mathbb{Z}$, generated by element $2\in\mathbb{Z}$. Consider $2\in I$, $\frac{1}{3}\in\mathbb{Q}$. Then $2\cdot\frac{1}{3}=\frac{2}{3}\notin i(I)$, so $i(I)$ *is not* an ideal in $\mathbb{Q}$.
***
#### Keywords
- [[Function(mapping)]],
- [[Homomorphism]],
- [[Ring]],
- [[Ideal]],
- [[Set]],
- [[Preimage]],
- [[Set of integers]],
- [[Rational numbers]],
- [[Ideal generated by a set]],
- [[Principal ideal]]
#### Possibly related
- 
***
#### Sources: