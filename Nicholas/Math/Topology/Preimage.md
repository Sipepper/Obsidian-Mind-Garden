# Preimage
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Direct strict note
>Let $f$ be a mapping from $X$ to $Y$. If $S$ is an arbitrary subset of $Y$, then set $f^{-1}(S)$ defined as
>$$f^{-1}(S)=\left\{x\in X:f(x)\in S\right\}$$
>is said to be a *preimage* of $S$.^[Sidney A. Morris - "Topology without tears" p.42]

>[!example]+ 
>Let $f:\mathbb{Z}\to\mathbb{Z}$ defined as $f(z)=|z|$. Function $f$ is not injective, becase $f(1)=f(-1)$. Also $f$ is not surjective, because there is no such $z\in\mathbb{Z}$ that $f(z)=-1$. Thus $f$ definitely is not bijective. Therefore by [[Existence of inverse function]], $f$ has no inverse function. But preimages do exists
>$$f^{-1}(\{1,2,3\})=\{-1,-2,-3,1,2,3\}$$
>$$f^{-1}(\{-5,3,5,7,9\})=\{-3,-5,-7,-9,3,5,7,9\}$$ 

>In another words, *any* function has a preimage.

>[!example]+
>Let $(Y,\tau)$ be a topological space and $X$ is a nonempty set. Let $f:X\to Y$. By putting $\tau_{1}=\{f^{-1}(s):S\in\tau\}$ we get the topology on $X$.^[Sidney A. Morris - "Topology without tears" p.43]
>>[!proof]
>>It's true because 
>>1. $f^{-1}(Y)=X$ and $f^{-1}(\emptyset)=\emptyset$
>>2. $A_{1}\cap A_{2}=f^{-1}(B_1)\cap f^{-1}(B_2)=f^{-1}(B_{1}\cap B_2)$
>>3. $\bigcup\limits_{j\in J} f^{-1}(B_j)=f^{-1}(\bigcup\limits_{j\in J}B_j)$
>>
>>For all $A_{i}\in\tau_{1}$ and $B_{j}\in\tau$.
***
#### Keywords
- [[Function(mapping)]],
- [[Set]],
- [[Set of integers]],
- [[Inverse function]],
- [[Topological space]],
#### Possibly related
- 
***
#### Sources: