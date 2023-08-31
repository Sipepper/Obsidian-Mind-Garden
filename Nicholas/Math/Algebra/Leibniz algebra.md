# Leibniz algebra
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $L$ be an algebra over field $F$. Then $L$ is said to be the *left Leibniz algebra*, if it's law of composition satisfies the *left Leibniz identity*:
>$$[[a,b],c]=[a,[b,c]]-[b,[a,c]]\quad\forall a,b,c\in L$$
>analogously there is a *right Leibniz algebra* with the *right Leibniz identity*:
>$$[a,[b,c]]=[[a,b],c]-[[a,c],b]\quad\forall a,b,c\in L$$

>Leigniz algebra $L$ is said to be *abelian*, if $[a,b]=0$ forall $a,b\in L$. In particular abelian Leibniz algebra is precisely a Lie Algebra. 

>[!example] 
>Let $F$ be a field and $L$ be a vector space over $F$, with basis $\set{x,y}$. Consider the law of composition $[\cdot,\cdot]$ on $L$ which defined as follows
>$$[x,x]=y,\quad [x,y]=y,$$
>$$[y,x]=0,\quad [y,y]=0$$
>We need to check that $L$ is a left Leibniz algebra. 
>>[!proof] 
>>We need to check $8$ possible identities
>>1. $$[[x,x],x]=[x,[x,x]]-[x,[x,x]]$$
>>   $$[y,x]=0$$
>>   $$0=0$$
>>2. $$[[x,x],y]=[x,[x,y]]-[x,[x,y]]$$
>>   $$[y,y]=0$$
>>   $$0=0$$
>>3. $$[[x,y],x]=[x,[y,x]]-[x,[y,x]]$$
>>   $$[y,x]=[x,0]-[y,y]$$
>>   $$0=0$$
>>4. $$[[x,y],y]=[x,[y,y]]-[x,[y,y]]$$
>>   $$[y,y]=[x,0]-[y,y]$$
>>   $$0=0$$
>>5. $$[[y,x],x]=[y,[x,x]]-[y,[x,x]]$$
>>   $$[0,x]=[y,y]-[x,0]$$
>>   $$0=0$$
>>6. $$[[y,x],y]=[y,[x,y]]-[y,[x,y]]$$
>>   $$[0,y]=[y,y]-[x,0]$$
>>   $$0=0$$
>>7. $$[[y,y],x]=[y,[y,x]]-[y,[y,x]]$$
>>   $$[0,x]=0$$
>>   $$0=0$$
>>8. $$[[y,y],y]=[y,[y,y]]-[y,[y,y]]$$
>>   $$[0,y]=0$$
>>   $$0=0$$
>>
>>Thus $L$ is indeed a left Leibniz algebra. 
>
>But as $[x,x]=y\ne0$, $L$ is *not* a Lie algebra.
>
>Let's check if $L$ is a right Leibniz algebra.
>
>Let $a=b=c=x$. Then
>$$[x,[x,x]]=[[x,x],x]-[[x,x],x]$$
>$$[x,y]=0$$
>$$y=0$$
>But $y$ is a basis vector, and it cannot be zero. This means that $L$ is *not* a right Leibniz algebra.

>Leibniz algebra is said to be *symmetrical* if it left and right Leibniz algebra simultaneously.
#### Relation between left and right Leibniz algebras
>[!dsn] Direct strict note
>Let $R$ be a right Leibniz algebra. Define new law of composition $[\![\cdot,\cdot]\!]$, such that $[\![a,b]\!]=[b,a]$. Then
>$$\begin{align}[\![[\![a,b]\!],c]\!]&=[c,[b,a]]\\ &=[[c,b],a]-[[c,a],b]\\ &=[\![a,[\![b,c]\!]]\!]-[\![b,[\![a,c]\!]]\!] \end{align}$$
>Thus we get the left leibniz algebra. From this we can say that *all* properties which yield for left Leibniz algebras are also true for right algebras and vice versa.


***
#### Keywords
- [[Algebra]],
- [[Field]],
- [[Law of composition]],
- [[Vector space]],
- [[Basis of vector space]],
- [[Lie algebra]]
#### Possibly related
- 
***
#### Sources:

# Leibniz subalgebras
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $L$ be a Leibniz algebra, a subspace $A$ of $L$ is said to be a *subalgebra* of algebra $L$, if $[a,b]\in A$ for all $a,b\in A$. In other words subspace $A$ of $L$ is a subalgebra of $L$ if
>$$[A,A]\subseteq A$$
>Denoted as $A\le L$.

>[!example] 
>
***
#### Keywords
- [[Leibniz algebra]],
- [[Vector space]],
- [[Algebra]]
- [[Commutant of two subsets in Leibniz algebra]]
#### Possibly related
- 
***
#### Sources: