# Set
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Direct strict note
>Naively speaking a *set* is a "family" of objects which called *elements* of e set with some specific properties. Formalized definition was provided in [[ZFC]].^[Philippe G.Ciarlet - "Linear and Nonlinear Functional Anallysis with Applications" p.2]
 

#### Basic operations on sets
>[!dsn]+ Direct strict note
>Let $X$ be a set, then
>- If $x\in A$ implies $x\in X$ then we say that $A$ is a *subset* of $X$, denoted as $A\subset X$. If $A\ne X$ then $A$ is said to be *proper subset* of $X$.
>- There exists a set of *all* subsets of $X$ called *power set* denoted as $\mathcal{P}(X)$(or $2^{X}$).
>- Set which contains no elements is said to be *empty set*.
>- Let $A\subset X$, then the set $A^{c}=X\setminus A:=\left\{x\in X:x\notin A \right\}$ is said to be *complement of $A$ in $X$*.
>- Let $A,B$ be subsets of $X$, then the sets
>  $$A\cup B=\{x\in X:x\in A\lor y\in B\}$$
>  and
>  $$A\cap B=\{x\in X:x\in A\land y\in B\}$$
>  are said to be the *union* and *intersection* of $A$ and $B$ respectively.
>
>- Sets $A$ and $B$ are said to be *disjoint* if $A\cap B=\emptyset$.
>- Let $A$ and $B$ be sets, then
>  $$A\cup(B\cap C)=(A\cup B)\cap(A\cup C)$$
>  and
>  $$A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$$

#### Algebra of relative complements 
>[!dsn]+ Direct strict note
>Let $A,B,C\subset X$, then the following identities holds
>1. $C\setminus(A\cap B)=(C\setminus A)\cup(C\setminus B)$
>2. $C\setminus(A\cup B)=(C\setminus A)\cap(C\setminus B)$
>3. $C\setminus(B\setminus A)=(A\cap C)\cup(C\setminus B)$
>4. $(B\setminus A)\cap C=(B\cap C)\setminus A=B\cap(C\setminus A)$
>5. $(B\setminus A)\cup C=(B\cup C)\setminus(A\setminus C)$
>6. $(B\setminus A)\setminus C=B\setminus(A\cup C)$
>7. $A\setminus A=\emptyset$
>8. $\emptyset\setminus A=\emptyset$
>9. $A\setminus\emptyset=A$
>10. $B\setminus A=A^{c}\cap B$
>11. $(B\setminus A)^{c}=A\cup B^{c}$
>12. $A\setminus X=\emptyset$


>[!proof]+
>

***
#### Keywords
- [[Logical operators]]
#### Possibly related
- 
***
#### Sources: