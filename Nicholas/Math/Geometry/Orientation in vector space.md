---
Last time checked: 2024-02-11
Complete: true
aliases:
---
# Orientation in vector space
***
###### tags: #Geometry #Algebra/Linear  
***
>[!dsn]+ Definition
>Let $e=\{e_{i}\}$ and $f=\{f_{i}\}$, $i=1,\dots,n$, be a two ordered bases of $n$-dimensional vector space $V$. It said that they have *same orientation* if change of basis matrix has positive determinant. We can denote this relation as $e\sim f$. By the properties of determinant we can obtain:
>1. $e\sim e$.
>2. If $e\sim f$, then $f\sim e$.
>3. If $e\sim f,f\sim g$, then $e\sim g$.

>Thus relation $\sim$ is indeed an equivalence relation. Thus set of all bases can be divided to *two* equivalence clases.

>Every such equivalence called the *orientation* of space $V$.^[Manfredo P. do Carmo - Differential Geometry of Curves and Surfaces с.12]

>[!example]+ 
>Let $V=\mathbb{R}^{3}$, let $e_{1}=(1,0,0)$,$e_{2}(0,1,0)$,$e_{3}(0,0,1)$ - be a standart ordered basis. Every other basis equivalent to this is called *positive*, or having *positive orientation*, basis of space $\mathbb{R}^{3}$ from this we can construct *negative* of $\mathbb{R}^{3}$ by changing order of basis vectors.
>
>Thus ordered basis $e_{1},e_{3},e_{2}$ is negative, because matrix of change from this basis to $e_{1},e_{2},e_{3}$ has a determinant equal to $-1$.
***
#### Keywords
- [[Basis of vector space]],
- [[Dimension]],
- [[Vector space]],
- [[Determinant]],
- [[Change of basis matrix]],
- [[Equivalence relation]],
- [[Equivalence class]],
- [[Euclidean space]]
#### Possibly related
- 
***
#### Sources: