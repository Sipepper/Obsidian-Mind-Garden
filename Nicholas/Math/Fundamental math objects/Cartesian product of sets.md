# Cartesian product of sets
***
###### tags: #Fundamental_math_objects 
***
>[!dsn] Direct strict note
>The *Cartesian product* of two sets $A$ and $B$, denoted as $A\times B$, is the set of all *ordered* pairs $(a,b)$ where $a\in A$ and $b\in B$, i.e.
>$$A\times B=\set{(a,b):a\in A\;\text{and}\;b\in B}$$

>[!example] 
>The *Cartesian plane* is an example of Cartesian product. By assigning to every point on a plane a distinct ordered pair of numbers. Which allowed to extract numerical information from shapes.

###### Basic properties
- The cartesian product $A\times B$ is not commutative in general case, i.e.
  $$A\times B\ne B\times A$$
  only if 
  - $A$ is equal to $B$, or
  - $A$ or $B$ is the empty set
  
  >[!example]
  >$A=\set{1,2}$, $B=\set{3,4}$
  >$$A\times B=\set{1,2}\times\set{3,4}=\set{(1,3),(1,4),(2,3),(2,4)}$$
  >$$B\times A=\set{3,4}\times\set{1,2}=\set{(3,1),(3,2),(4,1),(4,2)}$$
  >${}$
  >$A=B=\set{1,2}$
  >$$A\times B=B\times A=\set{1,2}\times\set{1,2}=\set{(1,1),(1,2),(2,1),(2,2)}$$
  >${}$
  >$A=\set{1,2}$, $B=\emptyset$
  >$$A\times B=\set{1,2}\times\emptyset=\emptyset$$
  >$$B\times A=\emptyset\times\set{1,2}=\emptyset$$
  
- The Cartesian product is not associative, i.e.
  $$(A\times B)\times C\ne A\times(B\times C)$$
  >[!example]
  >$A=\set{1}$, then 
  >$$(A\times A)\times A=\set{((1,1),1)}\ne\set{(1,(1,1))}=A\times(A\times A)$$
  
###### Distributive laws
- ![[Pasted image 20230124201807.png]]
  This picture demonstrating the fact that
  $$A\times(B\cap C)=(A\times B)\cap(A\times C)$$
  $$A\times(B\cup C)=(A\times B)\cup(A\times C)$$
  $$A\times(B\setminus C)=(A\times B)\setminus(A\times C)$$
  >[!proof]
  >
  
- ![[Pasted image 20230124202356.png]]
  This picture demonstrating the fact that 
  $$(A\cap B)\times(C\cap D)=(A\times C)\cap(B\times D)$$
  >[!proof]
  >
  
- If we replace the intersection by a union such identity will fail, i.e.
  $$(A\cup B)\times(C\cup D)\ne(A\times C)\cup(B\times D)$$
  which can be seen on this picture
  ![[Pasted image 20230124203123.png]]
  >[!proof]
  >
  
  In fact the following is true
  $$(A\times C)\cup(B\times D)=[(A\setminus B)\times C]\cup[(A\cap B)\times(C\cup D)]\cup[(B\setminus A)\times D]$$
  >[!proof]
  >

- For the set difference we have that 
  $$(A\times C)\setminus(B\times D)=[A\times(C\setminus D)]\cup[(A\setminus B)\times C]$$
  >[!proof]
  >

- And $$(A\times B)^{c}=\left(A^{c}\times B^{c} \right)\cup\left(A^{c}\times B \right)\cup\left(A\times B^{c} \right)$$
  >[!proof]
  >
  
###### Infinite Cartesian product
>[!dsn] Direct strict note
>Let $I$ be any index set of arbitrary cardinality, and $\set{X_{i}}_{i\in I}$ is a family of sets indexed by $I$. Then the *Cartesian product* of the sets in $\set{X_{i}}_{i\in I}$ is defined to be
>$$\prod_{i\in I}X_{i}=\left\{f:I\to\bigcup_{i\in I}X_{i}:\forall i\in I, f(i)\in X_{i} \right\}$$
>that is, the set of all functions defined on the index set such that the value of the function at a particular index $i$ is an element of $X_{i}$.
***
#### Keywords
- [[Set]],
- [[Cardinality of a set]],
- [[Function(mapping)]],
#### Possibly related
- 
***
#### Sources:
1. https://en.wikipedia.org/wiki/Cartesian_product#Cartesian_products_of_several_sets