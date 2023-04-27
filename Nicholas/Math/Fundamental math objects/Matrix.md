# Matrix
***
###### tags: #Fundamental_math_objects #Algebra/Linear 
***
>[!dsn]+ Direct strict note
>Let $m,n\in\mathbb{N}$. The two dimensional $m\times b$ array of numbers arranged in a "table-like" structure is said to be matrix
>$$\begin{bmatrix}a_{11}&\dots&a_{1n}\\ \vdots&\ddots&\vdots\\ a_{m1}&\dots& a_{mn} \end{bmatrix}$$ 
>elements of matrix are denoted as $a_{ij}$ where $i$ is a row number and $j$ is a column number. If $m=n$ then matrix is said to be *square*.

#### Basic operations
>[!dsn]+ Direct strict note
>We can add matrices element by element, that is if $A=(a_{ij})$ and $B=(b_{ij})$, i.e. matrices with same dimensions, then
>$$A+B=(a_{ij}+b_{ij})$$
>Also we can multiply matrices by a scalar
>$$cA=(ca_{ij})$$
>And we can multiply matrices with eachother, but they must have the following property
>$$(l\times m)(m\times n)=(l\times n)$$
>i.e. the number of columns of the first matrix must coincide with number of rows of the second matrix. Then multiplication is defined as 
>$$AB=a_{i1}b_{1j}+a_{i2}b_{2j}+\dots+a_{im}b_{mj}=a_{iv}b_{vj}$$
>thus we can see that in general $AB\ne BA$, i.e. matrix multiplication is *not* commutative.

>Multiplication and addition have the following properties:
>- $$A(B+B')=AB+AB'\quad(A+A')B=AB+A'B$$
>- $$(AB)C=A(BC)$$

#### Relation to systems of linear equations
>[!dsn]+ Direct strict note
>Suppose we have the following system of linear equations
>$$\begin{cases}a_{11}x_{1}+&\dots&+a_{1n}x_{n}&=&b_{1} \\ a_{21}x_{1}+&\dots&+a_{2n}x_{n}&=&b_{2}\\ \quad\;\vdots&&\quad\quad\vdots&&\vdots\\ a_{m1}x_{1}+&\dots&+a_{mn}x_{n}&=&b_{m}\end{cases}$$
>then we can rewrite it in *matrix form* as
>$$AX=B,\quad A=(a_{ij})$$

#### Common type of matrices
- *Zero*-matrix - matrix with all elements equal to zero.
- *Diagonal* matrix - square matrix with non-zero elements only on diagonal, that is $a_{ij}=0$ if $i\ne j$.
  $$A=\begin{bmatrix}a_{11}&0&\dots&0\\ 0&a_{22}&\dots&0\\ \vdots&\vdots&\ddots&\vdots\\ 0&0&\dots&1 \end{bmatrix}$$
- *Identity* matrix - diagonal matrix all non-zero elements of which is equal to $1$.
  $$I_{n}=\begin{bmatrix}1&0&\dots&0\\ 0&1&\dots&0\\ \vdots&\vdots&\ddots&\vdots\\ 0&0&\dots&1 \end{bmatrix}$$
- *Upper(lower) triangular* matrix - matrix element that are located *over*(*under*) main diagonal, that is
  $$A=\begin{bmatrix}a_{11}&a_{12}&\dots&a_{1m}\\ 0&a_{22}&\dots&a_{2m}\\ \vdots&\vdots&\ddots&\vdots\\ 0&0&\dots&a_{nm}\end{bmatrix}\quad B=\begin{bmatrix}b_{11}&0&\dots&0\\ b_{21}&b_{22}&\dots&0\\ \vdots&\vdots&\ddots&\vdots\\ b_{n1}&b_{n2}&\dots&b_{nm}\end{bmatrix}$$

#### Invertible matrix
>[!dsn]+ Direct strict note
>Let $A$ be a squared matrix of size $n\times n$. If there exists a matrix $B$ such that $AB=I_{n}$ and $BA=I_{n}$, then $B$ is said to be the *inverse* of $A$ and denoted as $A^{-1}$, and $A$ is said to be *invertible*.

>Let $A$ and $B$ be invertible $n\times n$ matrices, then $AB$ and $A^{-1}$ are invertible, that is 
>$$(AB)^{-1}=B^{-1}A^{-1}\qquad(A^{-1})^{-1}=A$$

>Square matrix $A$ with at least one column(row) which consists fully from zeros then $A$ is not invertible, as by multiplying $A$ by any other matrix we obtain zero on main diagonal.

#### Block multiplication
>[!dsn]+ Direct strict note
>Every matrix $M$ we can express in *block* form, i.e. matrix with matrix as elements
>$$M=\begin{bmatrix}A&B\\ C&D\end{bmatrix}$$
>Thus suppose we have two matrices
>$$M=\begin{bmatrix}A&B\\ C&D\end{bmatrix}\qquad M'=\begin{bmatrix}A'&B'\\ C'&D'\end{bmatrix}$$
>then
>$$MM'=\begin{bmatrix}A&B\\ C&D\end{bmatrix}\begin{bmatrix}A'&B'\\ C'&D'\end{bmatrix}=\begin{bmatrix}AA'+BC'&AB'+BD'\\ CA'+DC'& CB'+DD' \end{bmatrix}$$
>Of course matrices in block must be multipliable.

>[!proof]+
>

>[!example]+ 
>

#### Relation to linear operators
***
#### Keywords
- [[Set of natural numbers]],
- [[Vector space]],

#### Possibly related
- [[Linear map]],
- [[Operator]] 
***
#### Sources: