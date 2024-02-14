---
Last time checked: 2024-02-04
Complete: false
aliases:
---
# Determinant
***
###### tags: #Algebra/Linear  
***
>[!dsn]+ Definition
>Determinant of the matrix, is a scalar value which shows "hom much" and "to which direction" a matrix, as a linear transformation, acts on a vector space.

#### Formal definition by permutations
#### Calculation of determinants
For a $2\times2$ matrix, determinant is calculated as follows $$\Delta=\begin{vmatrix}a&b\\ c&d \end{vmatrix}=ad-bc$$
For a $3\times3$ we can use the following decomposition $$\Delta=\begin{vmatrix}a_{11}&a_{12}&a_{13}\\ a_{21}&a_{22}&a_{23}\\ a_{31}&a_{32}&a_{33} \end{vmatrix}=a_{11}
\begin{vmatrix}
a_{22}&a_{23} \\ 
a_{32}&a_{33}
\end{vmatrix}-
a_{12}
\begin{vmatrix}
a_{21}&a_{23} \\ 
a_{31}&a_{33}
\end{vmatrix}+
a_{13}
\begin{vmatrix}
a_{21}&a_{22} \\ 
a_{31}&a_{32}
\end{vmatrix}$$
For the $n\times n$ matrices following decomposition is true. $$\Delta=\sum\limits_{j=1}^{n}(-1)^{1+j}a_{1j}M_{1j}$$ where $M_{1j}$ is a minors to elements $a_{1j}$, i.e. determinants of $(n-1)\times (n-1)$ matrix obtained by deleting the column and row which contains element $a_{1j}$. Such decomposition is called a *Laplace row decomposition*.
#### Properties of determinants
- $\det I=1$, i.e. determinant of unit matrix is equals to 1.
- $\det(cA)=c^{n}\det A$
- $\det(A^{t})=\det A$, determinant is invariant to matrix transposition.
- $\det(AB)=\det A\cdot\det B$
- $\det(A^{-1})=(\det A)^{-1}$, moreover matrix is invertible if and only if it has nonzero determinant.
***
#### Keywords
- [[Matrix]],
- [[Vector space]],
- [[Transpose]]
#### Possibly related
- [[Linear map]],
***
#### Sources:
1. https://en.wikipedia.org/wiki/Determinant 