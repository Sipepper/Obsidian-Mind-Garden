---
Last time checked: 2024-03-01
Complete: false
aliases:
---
# Interior, Exterior and boundary of a set in topological space
***
###### tags: #Topology 
***
#### Interior
>[!dsn]+ Definition
>Let $(X,\tau)$ be a topological space and $A\subset X$. Let $x\in A$ and $U\in\tau$ is an open neighbourhood of $x$ which contained in $A$, i.e. $U\subseteq A$, then if for any $x$ there exists such neighbourhood then $x$ is said to be *interior point* of $A$. The set of all interior points of $A$ is denoted as $\text{Int}(A)$.

>The $\text{Int}(A)$ is equivalent to the biggest open set contained in $A$.

>[!example]+ 
>

#### Exterior
>[!dsn]+ Definition
>Let $(X,\tau)$ be a topological space and $A\subset X$. The set $\text{Ext}(A)$ defined as $\text{Int}(X\setminus A)$ is said to be the *exterior* of a set $A$.  Every point of $\text{Ext}(A)$ is a point such that there exist an open neighbourhood of $x$ which contained in complement to $A$. Points of $\text{Ext}(A)$ is said to be the *exterior points* of $A$.

>[!example]+
>

#### Boundary
>[!dsn]+ Definition
>A set $\partial A=\overline{A}\setminus\text{Int}(A)$ is said to be the *boundary* of $A$. Points of $\partial A$ is said to be the *boundary points* of $A$.

>Boundary is a closed set, as a complement to an open set.

>[!example]+
>

#### Properties
>[!dsn]+ Proposition
>1. $X=\text{Int}(A)\sqcup\partial A\sqcup\text{Ext}(A)$
>2. $\text{Int}(X\setminus A)=\text{Ext}(A)$
>3. $\partial(X\setminus A)=\partial A$
>4. $\overline{X\setminus A}=X\setminus\text{Int}(A)$
>5. $\text{Ext}(X\setminus A)=\text{Int}(A)$

>[!proof]+
>1. As $\overline{A}=\text{Int}(A)\cup\partial(A)$ we show that $\text{Int}(A)\cap\partial A=\emptyset$. Let $x\in\text{Int}(A)\cap\partial(A)$, then there exists an open neighbourhood $U_{x}$ which is contained in $A$ but every neighbourhood of $x$ must intersect $A$ and $X\setminus A$ simultaneously, which is impossible. Thus $\text{Int}(A)\cap\partial(A)=\emptyset$.
>   Further, show that $\overline{A}\cap\text{Ext}(A)=\emptyset$. Let $x\in\overline{A}\cap\text{Ext}(A)$, then $x\in A$ and $x\in X\setminus A$, which is impossible, thus $\overline{A}\cap\text{Ext}(A)$. Further let $X\setminus\overline{A}$, then
>   $$x\in X\setminus(\text{Int}(A)\cup\partial(A))=(X\setminus\text{Int}(A))\cap(X\setminus\partial A)$$
>   i.e. there is no neighbourhood of $x$ such that $U\cap A\ne\emptyset$, i.e. $X\setminus\overline{A}=\text{Ext}(A)$.
>   
>2. Let $x\in\text{Int}(X\setminus A)$, then there exists an open neighbourhood of $x$ which is contained in $X\setminus A$, i.e. $x$ is a exterior point.
>3. Let $x\in\partial(X\setminus A)$, then every neighbourhood of $x$ intersects $X\setminus A$ and $X\setminus(X\setminus A)$, i.e. $X\setminus A$ and $A$, which is precisely the definition of exterior point of $A$, i.e. $\partial(X\setminus A)=\partial A$.
>4. Let $x\in\overline{X\setminus A}$, then every open neighbourhood of $x$ intersects a set $X\setminus A$. Which is equivalent to say that there are no   neighbourhood of $x$ is contained in $A$. Thus $x\in X\setminus\text{Int}(A)$.
>   Let $x\in X\setminus\text{Int}(A)$, i.e. $x$ is a point such that there is no open neighbourhood $U$ such that $U\subseteq A$. Thus every neighbourhood of $x$ will intersect $X\setminus A$, and thus $x\in\overline{X\setminus A}$.
>5. Let $x\in\text{Ext}(X\setminus A)$, then exist a neighbourhood $U$ of $x$ such that $U\subset X\setminus(X\setminus A)$, i.e. contained in $A$. Therefore $x$ is an interior point of $A$.
>   The reversed statement can be proved analogously. 
***
#### Keywords
- [[Topological space]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Set]],
- [[Closure of a set]]
#### Possibly related
- 
***
#### Sources: