# Making a Leibniz algebra out of associative algebra
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $A$ be an associative algebra over a field $F$, i.e.
>$$(ab)c=a(bc)\quad\forall a,b,c\in A$$
>And let $f:A\to A$ be an endomorphism(linear map preserving multiplication) of algebra $A$, such that $f^{2}=f$. Now we introduce the new law of composition $[\cdot,\cdot]$ defined as 
>$$[a,b]=f(a)b-bf(a)$$
>then $A$ with such multiplication defines a left Leibniz algebra. 

>[!proof]
>Let $a,b,c\in A$, $\lambda\in F$. Then
>$$\begin{align}[a+b,c]&=f(a+b)c-cf(a+b)\\ &=(f(a)+f(b))c-c(f(a)+f(b))\\ &= f(a)c+f(b)c-cf(a)-cf(b)\\ &= (f(a)c-cf(a))+(f(b)c-cf(b))\\ &= [a,c]+[b,c] \end{align}$$
>$$\begin{align}[a,b+c]&=f(a)(b+c)-(b+c)f(a)\\ &=f(a)b+f(a)c-bf(a)-cf(a)\\ &= (f(a)b-bf(a))+(f(a)c-cf(a))\\ &= [a,b]+[a,c] \end{align}$$
>(the bilinearity and Leibniz identity i will check at some point, in the "day of great need")


>[!example] 
>
***
#### Keywords
- [[Field]],
- [[Algebra]],
- [[Linear map]],
- [[Law of composition]],
#### Possibly related
- [[Group endomorphism]],
- [[Making a Lie algebra out of associative algebra using commutator]]
***
#### Sources: