---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# There is no homomorphism from residue ring to integers
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>Let $n\in\mathbb{Z}$, $n>0$. There is no homomorphism $\mathbb{Z}/n\mathbb{Z}\to\mathbb{Z}$.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>Suppose that such homomorphism exists
>$$\phi:\mathbb{Z}/n\mathbb{Z}\to\mathbb{Z}$$
>Let $n=1$. Then $\mathbb{Z}/1\mathbb{Z}=\{0\}$. Thus by definition $0=1$, $\phi(1)=1$. On the other side $\phi(1)=\phi(0)=0$. But $0=0_{\mathbb{Z}}\ne 1_{\mathbb{Z}}=1$.
>Let $n>1$. Then $\mathbb{Z}/n\mathbb{Z}\ne\{0\}$. By definition $\phi([1]_{n})=1$. On the other hand, $\forall a\in\mathbb{Z}/n\mathbb{Z}$ and $\forall m\in\mathbb{Z}$ we have that $\phi(ma)=m\phi(a)$.
>Therefore $\phi(n [1]_{n})=n\phi([1]_{n})=n$. But $n [1]_{n}=[0]_{n}$, thus $\phi(n [1]_{n})=\phi([0]_{n})=0$ which leads to contradiction.

***
#### Keywords
- [[Set of integers]],
- [[Homomorphism]],
- [[Modular arithmetic]],
- [[Trivial ring]],
- [[Residue class]]
#### Possibly related
- 
***
#### Sources: